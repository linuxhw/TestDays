Linux Mint - Tested Hardware & Statistics
-----------------------------------------

A project to collect tested hardware configurations for Linux Mint.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Linux_Mint/Desktop/README.md) and [notebooks](/Dist/Linux_Mint/Notebook/README.md).

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

Total: 26407

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Acer          | FRS780M                     | Desktop     | [3066c1772f](https://linux-hardware.org/?probe=3066c1772f) | Jul 01, 2023 |
| Acer          | FRS780M                     | Desktop     | [4f8ad26557](https://linux-hardware.org/?probe=4f8ad26557) | Jul 01, 2023 |
| ASUSTek       | X553MA                      | Notebook    | [969994628c](https://linux-hardware.org/?probe=969994628c) | Jun 30, 2023 |
| ASUSTek       | X553MA                      | Notebook    | [53a5b9567e](https://linux-hardware.org/?probe=53a5b9567e) | Jun 30, 2023 |
| HP            | Pavilion dv6                | Notebook    | [9e3a0f3a0b](https://linux-hardware.org/?probe=9e3a0f3a0b) | Jun 30, 2023 |
| Gigabyte      | B650 AORUS PRO AX           | Notebook    | [f8ced52649](https://linux-hardware.org/?probe=f8ced52649) | Jun 30, 2023 |
| Intel         | X99 V1.x                    | Desktop     | [8e4ce021b1](https://linux-hardware.org/?probe=8e4ce021b1) | Jun 30, 2023 |
| Fujitsu       | LIFEBOOK P771               | Notebook    | [9d6575a3aa](https://linux-hardware.org/?probe=9d6575a3aa) | Jun 30, 2023 |
| HP            | Pavilion g6                 | Notebook    | [5d632e53c6](https://linux-hardware.org/?probe=5d632e53c6) | Jun 30, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [7c3ce62039](https://linux-hardware.org/?probe=7c3ce62039) | Jun 30, 2023 |
| HP            | EliteBook 820 G2            | Notebook    | [c99236ef84](https://linux-hardware.org/?probe=c99236ef84) | Jun 30, 2023 |
| ASUSTek       | H81M-R                      | Desktop     | [83cd667719](https://linux-hardware.org/?probe=83cd667719) | Jun 30, 2023 |
| ASRock        | 775Dual-VSTA                | Desktop     | [7ddc95bb2f](https://linux-hardware.org/?probe=7ddc95bb2f) | Jun 30, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [2fe05dff41](https://linux-hardware.org/?probe=2fe05dff41) | Jun 30, 2023 |
| ASUSTek       | N76VM                       | Notebook    | [df79346cd4](https://linux-hardware.org/?probe=df79346cd4) | Jun 30, 2023 |
| Acer          | Aspire E5-575               | Notebook    | [602d134940](https://linux-hardware.org/?probe=602d134940) | Jun 30, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [5199efd89e](https://linux-hardware.org/?probe=5199efd89e) | Jun 30, 2023 |
| ASUSTek       | F1A75-V EVO                 | Desktop     | [b59f4f203c](https://linux-hardware.org/?probe=b59f4f203c) | Jun 30, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [3a814856ae](https://linux-hardware.org/?probe=3a814856ae) | Jun 30, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [fe8b1af179](https://linux-hardware.org/?probe=fe8b1af179) | Jun 30, 2023 |
| HP            | EliteBook 8760w             | Notebook    | [470630eb65](https://linux-hardware.org/?probe=470630eb65) | Jun 30, 2023 |
| Dell          | Latitude E6540              | Notebook    | [a526c901ee](https://linux-hardware.org/?probe=a526c901ee) | Jun 30, 2023 |
| Intel         | B75                         | Desktop     | [73d881c953](https://linux-hardware.org/?probe=73d881c953) | Jun 30, 2023 |
| UMAX          | VisionBook-N12R             | Notebook    | [6144190349](https://linux-hardware.org/?probe=6144190349) | Jun 30, 2023 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [03b1ea3bfa](https://linux-hardware.org/?probe=03b1ea3bfa) | Jun 30, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [ec846958c9](https://linux-hardware.org/?probe=ec846958c9) | Jun 30, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [310342d290](https://linux-hardware.org/?probe=310342d290) | Jun 30, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [593512053f](https://linux-hardware.org/?probe=593512053f) | Jun 30, 2023 |
| VALE          | Notebook Slim S132          | Notebook    | [3e381e10f7](https://linux-hardware.org/?probe=3e381e10f7) | Jun 30, 2023 |
| ASUSTek       | N76VM                       | Notebook    | [d770e894db](https://linux-hardware.org/?probe=d770e894db) | Jun 30, 2023 |
| ASUSTek       | PRIME Z370-A II             | Desktop     | [5907f43d41](https://linux-hardware.org/?probe=5907f43d41) | Jun 30, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [3c1007547d](https://linux-hardware.org/?probe=3c1007547d) | Jun 30, 2023 |
| Dell          | Latitude E4310              | Notebook    | [725b89a524](https://linux-hardware.org/?probe=725b89a524) | Jun 30, 2023 |
| Positivo      | S14CT01                     | Notebook    | [b70845bd08](https://linux-hardware.org/?probe=b70845bd08) | Jun 29, 2023 |
| Intel         | X99 V1.x                    | Desktop     | [1c7ef9ef35](https://linux-hardware.org/?probe=1c7ef9ef35) | Jun 29, 2023 |
| MSI           | GT70                        | Notebook    | [7471aab8f7](https://linux-hardware.org/?probe=7471aab8f7) | Jun 29, 2023 |
| PCWare        | IPMH61R3                    | Desktop     | [e190259144](https://linux-hardware.org/?probe=e190259144) | Jun 29, 2023 |
| Gigabyte      | H81M-S2PH                   | Desktop     | [d0ec676a22](https://linux-hardware.org/?probe=d0ec676a22) | Jun 29, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | Notebook    | [c44fba1fa2](https://linux-hardware.org/?probe=c44fba1fa2) | Jun 29, 2023 |
| Sony          | VGN-FE41M                   | Notebook    | [3bc894dc99](https://linux-hardware.org/?probe=3bc894dc99) | Jun 29, 2023 |
| Dell          | Inspiron 1440               | Notebook    | [ed9bcaecd2](https://linux-hardware.org/?probe=ed9bcaecd2) | Jun 29, 2023 |
| ASUSTek       | X541UAK                     | Notebook    | [83d0d28a2a](https://linux-hardware.org/?probe=83d0d28a2a) | Jun 29, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [8f7b4c61c0](https://linux-hardware.org/?probe=8f7b4c61c0) | Jun 29, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [ddb283952b](https://linux-hardware.org/?probe=ddb283952b) | Jun 29, 2023 |
| Dell          | 0T656F A02                  | Desktop     | [bf4264c797](https://linux-hardware.org/?probe=bf4264c797) | Jun 29, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [1e33cadd37](https://linux-hardware.org/?probe=1e33cadd37) | Jun 29, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [81868a0214](https://linux-hardware.org/?probe=81868a0214) | Jun 29, 2023 |
| Dell          | 0D28YY A03                  | Desktop     | [9c056f8643](https://linux-hardware.org/?probe=9c056f8643) | Jun 29, 2023 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [8a0d6c1825](https://linux-hardware.org/?probe=8a0d6c1825) | Jun 29, 2023 |
| Acer          | Swift SF313-53              | Notebook    | [17ea716a87](https://linux-hardware.org/?probe=17ea716a87) | Jun 29, 2023 |
| Intel         | DG41RQ AAE54511-205         | Desktop     | [0e896bc137](https://linux-hardware.org/?probe=0e896bc137) | Jun 29, 2023 |
| Acer          | Aspire V5-572P              | Notebook    | [1a28142960](https://linux-hardware.org/?probe=1a28142960) | Jun 28, 2023 |
| Dell          | Inspiron 15-3552            | Notebook    | [6197072395](https://linux-hardware.org/?probe=6197072395) | Jun 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [5819c72f02](https://linux-hardware.org/?probe=5819c72f02) | Jun 28, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [3ef19cf418](https://linux-hardware.org/?probe=3ef19cf418) | Jun 28, 2023 |
| MSI           | H110M GAMING                | Desktop     | [23de26f1b2](https://linux-hardware.org/?probe=23de26f1b2) | Jun 28, 2023 |
| MSI           | MAG Z390 TOMAHAWK           | Desktop     | [49f05e412e](https://linux-hardware.org/?probe=49f05e412e) | Jun 28, 2023 |
| Dell          | Inspiron N5010              | Notebook    | [5683980090](https://linux-hardware.org/?probe=5683980090) | Jun 28, 2023 |
| ASRock        | Z97 Extreme4                | Desktop     | [b1e629bc3c](https://linux-hardware.org/?probe=b1e629bc3c) | Jun 28, 2023 |
| ASUSTek       | ROG STRIX X370-F GAMING     | Desktop     | [793ee1e44c](https://linux-hardware.org/?probe=793ee1e44c) | Jun 28, 2023 |
| MSI           | MAG Z390 TOMAHAWK           | Desktop     | [5c049dc792](https://linux-hardware.org/?probe=5c049dc792) | Jun 28, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | Desktop     | [7f5dfae0db](https://linux-hardware.org/?probe=7f5dfae0db) | Jun 28, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [9cb1b45a65](https://linux-hardware.org/?probe=9cb1b45a65) | Jun 28, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [2b47aff042](https://linux-hardware.org/?probe=2b47aff042) | Jun 28, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [dc758ef355](https://linux-hardware.org/?probe=dc758ef355) | Jun 28, 2023 |
| Dell          | 0XJ5V0 A03                  | Desktop     | [a1595a590c](https://linux-hardware.org/?probe=a1595a590c) | Jun 28, 2023 |
| HP            | 250 G3                      | Notebook    | [90647a4b33](https://linux-hardware.org/?probe=90647a4b33) | Jun 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [f64ccf77fb](https://linux-hardware.org/?probe=f64ccf77fb) | Jun 28, 2023 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [a5dd94faa7](https://linux-hardware.org/?probe=a5dd94faa7) | Jun 28, 2023 |
| Acer          | Aspire 4349                 | Notebook    | [9064db77e4](https://linux-hardware.org/?probe=9064db77e4) | Jun 28, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [78b59f70ff](https://linux-hardware.org/?probe=78b59f70ff) | Jun 28, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [0251f7e1ab](https://linux-hardware.org/?probe=0251f7e1ab) | Jun 27, 2023 |
| HP            | Laptop 17-by2xxx            | Notebook    | [55682b5871](https://linux-hardware.org/?probe=55682b5871) | Jun 27, 2023 |
| Apple         | MacBookAir7,1               | Notebook    | [37b4621542](https://linux-hardware.org/?probe=37b4621542) | Jun 27, 2023 |
| HP            | Laptop 17-bs0xx             | Notebook    | [638a0571c3](https://linux-hardware.org/?probe=638a0571c3) | Jun 27, 2023 |
| HP            | 821D                        | Desktop     | [9b007c8a3f](https://linux-hardware.org/?probe=9b007c8a3f) | Jun 27, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [09d8109c56](https://linux-hardware.org/?probe=09d8109c56) | Jun 27, 2023 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [9cab8ca8c0](https://linux-hardware.org/?probe=9cab8ca8c0) | Jun 27, 2023 |
| Unknown       | T3 MRD                      | Desktop     | [7478cd5b81](https://linux-hardware.org/?probe=7478cd5b81) | Jun 27, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [b415502d04](https://linux-hardware.org/?probe=b415502d04) | Jun 27, 2023 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [f719df9920](https://linux-hardware.org/?probe=f719df9920) | Jun 27, 2023 |
| Acer          | Swift SFG14-71              | Notebook    | [f66ac636e6](https://linux-hardware.org/?probe=f66ac636e6) | Jun 27, 2023 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [73dfca737b](https://linux-hardware.org/?probe=73dfca737b) | Jun 27, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [fc532e9492](https://linux-hardware.org/?probe=fc532e9492) | Jun 27, 2023 |
| Dell          | Inspiron 7520               | Notebook    | [6754aac0be](https://linux-hardware.org/?probe=6754aac0be) | Jun 27, 2023 |
| Dell          | Inspiron 7520               | Notebook    | [4ff818e0cb](https://linux-hardware.org/?probe=4ff818e0cb) | Jun 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [5eac5b8b6d](https://linux-hardware.org/?probe=5eac5b8b6d) | Jun 27, 2023 |
| Supermicro    | C7Z370-CG-L                 | Server      | [5731d8f8dc](https://linux-hardware.org/?probe=5731d8f8dc) | Jun 27, 2023 |
| Acer          | Aspire VX5-591G             | Notebook    | [b4bd8360ea](https://linux-hardware.org/?probe=b4bd8360ea) | Jun 27, 2023 |
| Acer          | Aspire VX5-591G             | Notebook    | [1ffeb058e9](https://linux-hardware.org/?probe=1ffeb058e9) | Jun 27, 2023 |
| Intel         | DN2820FYK H24582-204        | Desktop     | [f296b651e4](https://linux-hardware.org/?probe=f296b651e4) | Jun 27, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [88baca047c](https://linux-hardware.org/?probe=88baca047c) | Jun 27, 2023 |
| Supermicro    | C7Z370-CG-L                 | Server      | [c373b5b24d](https://linux-hardware.org/?probe=c373b5b24d) | Jun 26, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [4b069e524d](https://linux-hardware.org/?probe=4b069e524d) | Jun 26, 2023 |
| MW            | NVR-N5105                   | Desktop     | [36ee490ef2](https://linux-hardware.org/?probe=36ee490ef2) | Jun 26, 2023 |
| MSI           | MAG X570S TORPEDO MAX       | Desktop     | [9b9eeefdef](https://linux-hardware.org/?probe=9b9eeefdef) | Jun 26, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [d3e14b3015](https://linux-hardware.org/?probe=d3e14b3015) | Jun 26, 2023 |
| eMachines     | E525                        | Notebook    | [9e477a5fad](https://linux-hardware.org/?probe=9e477a5fad) | Jun 26, 2023 |
| Pegatron      | 2A99h                       | Desktop     | [86b2544e47](https://linux-hardware.org/?probe=86b2544e47) | Jun 26, 2023 |
| Pegatron      | 2A99h                       | Desktop     | [e3716dffd6](https://linux-hardware.org/?probe=e3716dffd6) | Jun 26, 2023 |
| Lenovo        | ThinkPad T460 20FMS50T1J    | Notebook    | [91955c07a6](https://linux-hardware.org/?probe=91955c07a6) | Jun 26, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [a2a87af2a4](https://linux-hardware.org/?probe=a2a87af2a4) | Jun 26, 2023 |
| Lenovo        | V310-15ISK 80SY             | Notebook    | [824c084cce](https://linux-hardware.org/?probe=824c084cce) | Jun 26, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [bf911964a8](https://linux-hardware.org/?probe=bf911964a8) | Jun 26, 2023 |
| ASUSTek       | TP203NAH                    | Convertible | [9048d9f079](https://linux-hardware.org/?probe=9048d9f079) | Jun 25, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [faff66ca26](https://linux-hardware.org/?probe=faff66ca26) | Jun 25, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [12cc9ac9dc](https://linux-hardware.org/?probe=12cc9ac9dc) | Jun 25, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [8fb0e7a710](https://linux-hardware.org/?probe=8fb0e7a710) | Jun 25, 2023 |
| Dell          | 0J3C2F A00                  | Desktop     | [96184db86b](https://linux-hardware.org/?probe=96184db86b) | Jun 25, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [a729d9a4a8](https://linux-hardware.org/?probe=a729d9a4a8) | Jun 25, 2023 |
| Lenovo        | ThinkCentre M57 6072BJU     | Desktop     | [0343a0d640](https://linux-hardware.org/?probe=0343a0d640) | Jun 25, 2023 |
| HP            | 3397                        | Desktop     | [8d9ed6d13e](https://linux-hardware.org/?probe=8d9ed6d13e) | Jun 25, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [06a581d65d](https://linux-hardware.org/?probe=06a581d65d) | Jun 25, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [a105b6264f](https://linux-hardware.org/?probe=a105b6264f) | Jun 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [de0797cd44](https://linux-hardware.org/?probe=de0797cd44) | Jun 25, 2023 |
| Acer          | Swift SFX16-52G             | Notebook    | [28c4b7b2f3](https://linux-hardware.org/?probe=28c4b7b2f3) | Jun 25, 2023 |
| Acer          | Swift SFX16-52G             | Notebook    | [ac98f81b2a](https://linux-hardware.org/?probe=ac98f81b2a) | Jun 25, 2023 |
| Wortmann      | CR700                       | Notebook    | [b198dccb29](https://linux-hardware.org/?probe=b198dccb29) | Jun 25, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [f14b9f6ce5](https://linux-hardware.org/?probe=f14b9f6ce5) | Jun 25, 2023 |
| ASUSTek       | X75VC                       | Notebook    | [9fd44ac61e](https://linux-hardware.org/?probe=9fd44ac61e) | Jun 25, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [e172f7e955](https://linux-hardware.org/?probe=e172f7e955) | Jun 25, 2023 |
| ASUSTek       | X550LA                      | Notebook    | [225516996c](https://linux-hardware.org/?probe=225516996c) | Jun 25, 2023 |
| Dell          | Latitude D430               | Notebook    | [4e832147f4](https://linux-hardware.org/?probe=4e832147f4) | Jun 25, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [81937f18f4](https://linux-hardware.org/?probe=81937f18f4) | Jun 25, 2023 |
| Dell          | Latitude E6520              | Notebook    | [bd3986fb04](https://linux-hardware.org/?probe=bd3986fb04) | Jun 25, 2023 |
| Medion        | E2228T MD61050              | Convertible | [595ec84ebc](https://linux-hardware.org/?probe=595ec84ebc) | Jun 25, 2023 |
| Intel         | H61                         | Desktop     | [df8b50eae5](https://linux-hardware.org/?probe=df8b50eae5) | Jun 25, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [b7bbc8246f](https://linux-hardware.org/?probe=b7bbc8246f) | Jun 24, 2023 |
| Lenovo        | ThinkPad T440p 20AWS2820... | Notebook    | [0ea92a193f](https://linux-hardware.org/?probe=0ea92a193f) | Jun 24, 2023 |
| ASUSTek       | X750LN                      | Notebook    | [739ab83805](https://linux-hardware.org/?probe=739ab83805) | Jun 24, 2023 |
| ASUSTek       | P5SD2-VM                    | Desktop     | [d91441b98b](https://linux-hardware.org/?probe=d91441b98b) | Jun 24, 2023 |
| ASRock        | B85 Pro4                    | Desktop     | [f42da342bc](https://linux-hardware.org/?probe=f42da342bc) | Jun 24, 2023 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [39ff230ffe](https://linux-hardware.org/?probe=39ff230ffe) | Jun 24, 2023 |
| Toshiba       | Satellite Pro L300          | Notebook    | [96f79c634a](https://linux-hardware.org/?probe=96f79c634a) | Jun 24, 2023 |
| Gigabyte      | X79-UP4                     | Desktop     | [c269ef3dd7](https://linux-hardware.org/?probe=c269ef3dd7) | Jun 24, 2023 |
| Dell          | Inspiron 5767               | Notebook    | [9e3bf66b84](https://linux-hardware.org/?probe=9e3bf66b84) | Jun 24, 2023 |
| Timi          | RedmiBook Pro 14S           | Notebook    | [3910260d34](https://linux-hardware.org/?probe=3910260d34) | Jun 24, 2023 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [d26676c6f5](https://linux-hardware.org/?probe=d26676c6f5) | Jun 24, 2023 |
| Google        | Cave                        | Notebook    | [cc3b1bb1a3](https://linux-hardware.org/?probe=cc3b1bb1a3) | Jun 24, 2023 |
| HP            | Convertible x360            | Convertible | [83dec03aa9](https://linux-hardware.org/?probe=83dec03aa9) | Jun 24, 2023 |
| Google        | Cave                        | Notebook    | [199eb4826d](https://linux-hardware.org/?probe=199eb4826d) | Jun 24, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [bc2b97d0a8](https://linux-hardware.org/?probe=bc2b97d0a8) | Jun 24, 2023 |
| HP            | Convertible x360            | Convertible | [d752c240a8](https://linux-hardware.org/?probe=d752c240a8) | Jun 24, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [e0c5a18b09](https://linux-hardware.org/?probe=e0c5a18b09) | Jun 24, 2023 |
| ASUSTek       | X550LC                      | Notebook    | [30369c12e1](https://linux-hardware.org/?probe=30369c12e1) | Jun 24, 2023 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [f8dee044e2](https://linux-hardware.org/?probe=f8dee044e2) | Jun 24, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [44b5bb5453](https://linux-hardware.org/?probe=44b5bb5453) | Jun 23, 2023 |
| Gigabyte      | AORUS 15P YD                | Notebook    | [1e2fb31885](https://linux-hardware.org/?probe=1e2fb31885) | Jun 23, 2023 |
| ASUSTek       | X555LAB                     | Notebook    | [7b227bbaed](https://linux-hardware.org/?probe=7b227bbaed) | Jun 23, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [eea6cc91ec](https://linux-hardware.org/?probe=eea6cc91ec) | Jun 23, 2023 |
| ASRock        | A320M-HDV R3.0              | Desktop     | [a9cd7361e6](https://linux-hardware.org/?probe=a9cd7361e6) | Jun 23, 2023 |
| ASUSTek       | X751LD                      | Notebook    | [46e9b730a1](https://linux-hardware.org/?probe=46e9b730a1) | Jun 23, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [af8146f50e](https://linux-hardware.org/?probe=af8146f50e) | Jun 23, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [6968ecbe10](https://linux-hardware.org/?probe=6968ecbe10) | Jun 23, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [f87146e2d5](https://linux-hardware.org/?probe=f87146e2d5) | Jun 23, 2023 |
| ASUSTek       | A3402WBA                    | All in one  | [f2f0b0cc99](https://linux-hardware.org/?probe=f2f0b0cc99) | Jun 23, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [fa288c80f2](https://linux-hardware.org/?probe=fa288c80f2) | Jun 23, 2023 |
| Lenovo        | BRASWELL NOK                | Desktop     | [1fe857b53b](https://linux-hardware.org/?probe=1fe857b53b) | Jun 23, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [cc0361248f](https://linux-hardware.org/?probe=cc0361248f) | Jun 23, 2023 |
| TUXEDO        | Unknown                     | Notebook    | [71a75069f7](https://linux-hardware.org/?probe=71a75069f7) | Jun 23, 2023 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [184b19f00c](https://linux-hardware.org/?probe=184b19f00c) | Jun 23, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [efc582d761](https://linux-hardware.org/?probe=efc582d761) | Jun 23, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [71f5fde47b](https://linux-hardware.org/?probe=71f5fde47b) | Jun 23, 2023 |
| Lenovo        | ThinkPad T540p 20BFS1D70... | Notebook    | [c0e41e35f8](https://linux-hardware.org/?probe=c0e41e35f8) | Jun 23, 2023 |
| MSI           | PRO B660-A DDR4             | Desktop     | [1ecefb98f7](https://linux-hardware.org/?probe=1ecefb98f7) | Jun 23, 2023 |
| ASUSTek       | TP550LA                     | Notebook    | [7728203a8a](https://linux-hardware.org/?probe=7728203a8a) | Jun 22, 2023 |
| ASUSTek       | TP550LA                     | Notebook    | [fed72172d2](https://linux-hardware.org/?probe=fed72172d2) | Jun 22, 2023 |
| Lenovo        | ThinkPad E460 20ETCTO1WW    | Notebook    | [762add0eb1](https://linux-hardware.org/?probe=762add0eb1) | Jun 22, 2023 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [c1858efd7e](https://linux-hardware.org/?probe=c1858efd7e) | Jun 22, 2023 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [90bb825e51](https://linux-hardware.org/?probe=90bb825e51) | Jun 22, 2023 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [54097cc170](https://linux-hardware.org/?probe=54097cc170) | Jun 22, 2023 |
| Dell          | 0JP3NX A02                  | Desktop     | [fbfe3fab11](https://linux-hardware.org/?probe=fbfe3fab11) | Jun 22, 2023 |
| ASUSTek       | Q534UXK                     | Convertible | [56cf3a68b0](https://linux-hardware.org/?probe=56cf3a68b0) | Jun 22, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [d607d3c598](https://linux-hardware.org/?probe=d607d3c598) | Jun 22, 2023 |
| ASUSTek       | GL552VX                     | Notebook    | [348e36123f](https://linux-hardware.org/?probe=348e36123f) | Jun 22, 2023 |
| HP            | EliteBook 8540p             | Notebook    | [c72d0ef702](https://linux-hardware.org/?probe=c72d0ef702) | Jun 22, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [d7ca07df46](https://linux-hardware.org/?probe=d7ca07df46) | Jun 22, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [ef8876640e](https://linux-hardware.org/?probe=ef8876640e) | Jun 22, 2023 |
| MSI           | B360M PRO-VDH               | Desktop     | [744a4b8498](https://linux-hardware.org/?probe=744a4b8498) | Jun 22, 2023 |
| MSI           | GX60 1AC                    | Notebook    | [8e15fea8cd](https://linux-hardware.org/?probe=8e15fea8cd) | Jun 22, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [e177167295](https://linux-hardware.org/?probe=e177167295) | Jun 22, 2023 |
| Dell          | Vostro 1400                 | Notebook    | [7b5011ff7c](https://linux-hardware.org/?probe=7b5011ff7c) | Jun 22, 2023 |
| Dell          | Vostro 1400                 | Notebook    | [c41c17d657](https://linux-hardware.org/?probe=c41c17d657) | Jun 22, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [7d52f04870](https://linux-hardware.org/?probe=7d52f04870) | Jun 22, 2023 |
| Dell          | Latitude E6410              | Notebook    | [522dfb5977](https://linux-hardware.org/?probe=522dfb5977) | Jun 21, 2023 |
| Dell          | Latitude E6410              | Notebook    | [601921c51d](https://linux-hardware.org/?probe=601921c51d) | Jun 21, 2023 |
| Wortmann      | NA92                        | All in one  | [7c0d234301](https://linux-hardware.org/?probe=7c0d234301) | Jun 21, 2023 |
| Gigabyte      | Z490 GAMING X               | Desktop     | [596a01e7a5](https://linux-hardware.org/?probe=596a01e7a5) | Jun 21, 2023 |
| Acer          | Aspire 5742Z                | Notebook    | [d1513c944e](https://linux-hardware.org/?probe=d1513c944e) | Jun 21, 2023 |
| HP            | 1495                        | Desktop     | [9bdf95d92b](https://linux-hardware.org/?probe=9bdf95d92b) | Jun 21, 2023 |
| Lenovo        | ThinkPad T510 4349WHC       | Notebook    | [9134464b7a](https://linux-hardware.org/?probe=9134464b7a) | Jun 21, 2023 |
| Acer          | Extensa 2519                | Notebook    | [36f37b33d5](https://linux-hardware.org/?probe=36f37b33d5) | Jun 21, 2023 |
| Acer          | Swift SF314-52G             | Notebook    | [4eab971a60](https://linux-hardware.org/?probe=4eab971a60) | Jun 21, 2023 |
| HP            | 0B40h                       | Desktop     | [ac50670d44](https://linux-hardware.org/?probe=ac50670d44) | Jun 21, 2023 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [1a47171330](https://linux-hardware.org/?probe=1a47171330) | Jun 21, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [8518224d34](https://linux-hardware.org/?probe=8518224d34) | Jun 21, 2023 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [386c32d302](https://linux-hardware.org/?probe=386c32d302) | Jun 21, 2023 |
| Gateway       | ZX4800                      | All in one  | [fbb23975d9](https://linux-hardware.org/?probe=fbb23975d9) | Jun 21, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [186a21a6f7](https://linux-hardware.org/?probe=186a21a6f7) | Jun 21, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [5a583f77d8](https://linux-hardware.org/?probe=5a583f77d8) | Jun 21, 2023 |
| Gateway       | ZX4800                      | All in one  | [eea8b39580](https://linux-hardware.org/?probe=eea8b39580) | Jun 21, 2023 |
| Intel Clie... | LAPBC710                    | Notebook    | [6c97bec6f0](https://linux-hardware.org/?probe=6c97bec6f0) | Jun 21, 2023 |
| Lenovo        | Yoga 310-11IAP 80U2         | Convertible | [d432122ffe](https://linux-hardware.org/?probe=d432122ffe) | Jun 21, 2023 |
| Gigabyte      | H510M S2H V2                | Desktop     | [d7c44291c1](https://linux-hardware.org/?probe=d7c44291c1) | Jun 20, 2023 |
| Dell          | Latitude E5520              | Notebook    | [4c041a09f6](https://linux-hardware.org/?probe=4c041a09f6) | Jun 20, 2023 |
| TUXEDO        | P95xER                      | Notebook    | [f2f6ddaf27](https://linux-hardware.org/?probe=f2f6ddaf27) | Jun 20, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [3db68832fd](https://linux-hardware.org/?probe=3db68832fd) | Jun 20, 2023 |
| ASUSTek       | K56CB                       | Notebook    | [e00f1f735d](https://linux-hardware.org/?probe=e00f1f735d) | Jun 20, 2023 |
| Dell          | Latitude E5570              | Notebook    | [9f935b7571](https://linux-hardware.org/?probe=9f935b7571) | Jun 20, 2023 |
| Dell          | 0VHRW1 A03                  | Desktop     | [f077d9dc8f](https://linux-hardware.org/?probe=f077d9dc8f) | Jun 20, 2023 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [4131c0a5bb](https://linux-hardware.org/?probe=4131c0a5bb) | Jun 20, 2023 |
| win elemen... | MoreFine S500+              | Notebook    | [32b221a438](https://linux-hardware.org/?probe=32b221a438) | Jun 20, 2023 |
| Lenovo        | ThinkPad X230 2325CL7       | Notebook    | [7423b661e5](https://linux-hardware.org/?probe=7423b661e5) | Jun 20, 2023 |
| Alienware     | 17 R3                       | Notebook    | [45613f348f](https://linux-hardware.org/?probe=45613f348f) | Jun 20, 2023 |
| ASUSTek       | ROG STRIX B360-I GAMING     | Desktop     | [2e14ad6bce](https://linux-hardware.org/?probe=2e14ad6bce) | Jun 20, 2023 |
| POWERX        | G41                         | Desktop     | [5d1b37ec3a](https://linux-hardware.org/?probe=5d1b37ec3a) | Jun 20, 2023 |
| Timi          | RedmiBook 15                | Notebook    | [f975205ebd](https://linux-hardware.org/?probe=f975205ebd) | Jun 20, 2023 |
| ASUSTek       | X550LA                      | Notebook    | [9b58f1abd3](https://linux-hardware.org/?probe=9b58f1abd3) | Jun 20, 2023 |
| TaNix         | T3 MRD                      | Notebook    | [fea0fcfd44](https://linux-hardware.org/?probe=fea0fcfd44) | Jun 20, 2023 |
| TaNix         | T3 MRD                      | Notebook    | [5479ceec5f](https://linux-hardware.org/?probe=5479ceec5f) | Jun 20, 2023 |
| MSI           | A320M PRO-VD PLUS           | Desktop     | [0cb6da57db](https://linux-hardware.org/?probe=0cb6da57db) | Jun 19, 2023 |
| MSI           | A320M PRO-VD PLUS           | Desktop     | [17a4ba54ac](https://linux-hardware.org/?probe=17a4ba54ac) | Jun 19, 2023 |
| Toshiba       | Satellite C850-1DV          | Notebook    | [eb574aab3b](https://linux-hardware.org/?probe=eb574aab3b) | Jun 19, 2023 |
| Shuttle       | FX21V10                     | Desktop     | [d77f55da92](https://linux-hardware.org/?probe=d77f55da92) | Jun 19, 2023 |
| Gigabyte      | H510M S2H V2                | Desktop     | [f2d80b2558](https://linux-hardware.org/?probe=f2d80b2558) | Jun 19, 2023 |
| Gigabyte      | 2AC8                        | Desktop     | [bfacacbca8](https://linux-hardware.org/?probe=bfacacbca8) | Jun 19, 2023 |
| Shuttle       | FX21V10                     | Desktop     | [71a0effa3a](https://linux-hardware.org/?probe=71a0effa3a) | Jun 19, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [953a81c579](https://linux-hardware.org/?probe=953a81c579) | Jun 19, 2023 |
| Acer          | Predator PH317-54           | Notebook    | [49b9c71af7](https://linux-hardware.org/?probe=49b9c71af7) | Jun 19, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [647597be95](https://linux-hardware.org/?probe=647597be95) | Jun 19, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [d95fa943f1](https://linux-hardware.org/?probe=d95fa943f1) | Jun 19, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [4681ff2f7d](https://linux-hardware.org/?probe=4681ff2f7d) | Jun 19, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [4b5f759a01](https://linux-hardware.org/?probe=4b5f759a01) | Jun 19, 2023 |
| HP            | HDX18                       | Notebook    | [dec8492b2f](https://linux-hardware.org/?probe=dec8492b2f) | Jun 19, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [70d76362e2](https://linux-hardware.org/?probe=70d76362e2) | Jun 19, 2023 |
| ASUSTek       | TP501UA                     | Notebook    | [e883c61561](https://linux-hardware.org/?probe=e883c61561) | Jun 19, 2023 |
| Dell          | Inspiron 7737               | Notebook    | [ba4c6aac1c](https://linux-hardware.org/?probe=ba4c6aac1c) | Jun 19, 2023 |
| Dell          | Inspiron 7737               | Notebook    | [b1daf8dda0](https://linux-hardware.org/?probe=b1daf8dda0) | Jun 19, 2023 |
| MSI           | X299 TOMAHAWK               | Desktop     | [aa2a65c324](https://linux-hardware.org/?probe=aa2a65c324) | Jun 19, 2023 |
| ASUSTek       | G71GX                       | Notebook    | [b6ae9bfdd4](https://linux-hardware.org/?probe=b6ae9bfdd4) | Jun 19, 2023 |
| Multicom N... | Multicom Talisa U235        | Tablet      | [50d54b5967](https://linux-hardware.org/?probe=50d54b5967) | Jun 18, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [2192185525](https://linux-hardware.org/?probe=2192185525) | Jun 18, 2023 |
| Lenovo        | IdeaPad Flex14 SharkBay     | Notebook    | [e904a7b3ce](https://linux-hardware.org/?probe=e904a7b3ce) | Jun 18, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [b7a4e69498](https://linux-hardware.org/?probe=b7a4e69498) | Jun 18, 2023 |
| Lenovo        | IdeaPad Flex14 SharkBay     | Notebook    | [cb84a2778b](https://linux-hardware.org/?probe=cb84a2778b) | Jun 18, 2023 |
| PCWare        | IPMH61R3                    | Desktop     | [256988a55a](https://linux-hardware.org/?probe=256988a55a) | Jun 18, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [0054d0c92e](https://linux-hardware.org/?probe=0054d0c92e) | Jun 18, 2023 |
| Acer          | Aspire A315-22              | Notebook    | [f977b4851c](https://linux-hardware.org/?probe=f977b4851c) | Jun 18, 2023 |
| Dell          | Latitude 5430               | Notebook    | [cb097e3c83](https://linux-hardware.org/?probe=cb097e3c83) | Jun 18, 2023 |
| Multicom N... | Multicom Talisa U235        | Tablet      | [cb5806fefc](https://linux-hardware.org/?probe=cb5806fefc) | Jun 18, 2023 |
| MSI           | PRO Z790-P WIFI DDR4        | Desktop     | [97699ce0ff](https://linux-hardware.org/?probe=97699ce0ff) | Jun 18, 2023 |
| Dell          | XPS 17 9710                 | Notebook    | [d5ac5e48ce](https://linux-hardware.org/?probe=d5ac5e48ce) | Jun 18, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [36f8057a1d](https://linux-hardware.org/?probe=36f8057a1d) | Jun 18, 2023 |
| ASUSTek       | X556UQK                     | Notebook    | [fb675907ec](https://linux-hardware.org/?probe=fb675907ec) | Jun 18, 2023 |
| MSI           | Z77A-GD65                   | Desktop     | [93400d2b87](https://linux-hardware.org/?probe=93400d2b87) | Jun 18, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [37b1f672d0](https://linux-hardware.org/?probe=37b1f672d0) | Jun 18, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [8dc64586cc](https://linux-hardware.org/?probe=8dc64586cc) | Jun 18, 2023 |
| Dell          | Precision M4800             | Notebook    | [9f86d737f2](https://linux-hardware.org/?probe=9f86d737f2) | Jun 18, 2023 |
| HP            | 3646h                       | Desktop     | [bbe600a4ab](https://linux-hardware.org/?probe=bbe600a4ab) | Jun 18, 2023 |
| Acer          | Aspire Z24-890              | All in one  | [8f7aac560c](https://linux-hardware.org/?probe=8f7aac560c) | Jun 18, 2023 |
| HP            | Pavilion dv7                | Notebook    | [166b70ddad](https://linux-hardware.org/?probe=166b70ddad) | Jun 18, 2023 |
| Lenovo        | Yoga 310-11IAP 80U2         | Convertible | [b1d6af488d](https://linux-hardware.org/?probe=b1d6af488d) | Jun 18, 2023 |
| Dell          | Latitude 5520               | Notebook    | [09da4ee3c4](https://linux-hardware.org/?probe=09da4ee3c4) | Jun 18, 2023 |
| Dell          | Latitude 5520               | Notebook    | [5e70c1929c](https://linux-hardware.org/?probe=5e70c1929c) | Jun 18, 2023 |
| Lenovo        | ThinkPad X230 2325CL7       | Notebook    | [baadfc7e98](https://linux-hardware.org/?probe=baadfc7e98) | Jun 18, 2023 |
| ASUSTek       | X553MA                      | Notebook    | [ef0c9e5597](https://linux-hardware.org/?probe=ef0c9e5597) | Jun 18, 2023 |
| Lenovo        | ThinkPad T61 765803U        | Notebook    | [2c989696aa](https://linux-hardware.org/?probe=2c989696aa) | Jun 18, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [c0de332a8b](https://linux-hardware.org/?probe=c0de332a8b) | Jun 18, 2023 |
| VALE          | Notebook Classic C140       | Notebook    | [afa3a9de5e](https://linux-hardware.org/?probe=afa3a9de5e) | Jun 18, 2023 |
| Sony          | SVF14N13CXB                 | Notebook    | [468f2143a0](https://linux-hardware.org/?probe=468f2143a0) | Jun 18, 2023 |
| HP            | EliteBook 850 G4            | Notebook    | [3b78bd33e1](https://linux-hardware.org/?probe=3b78bd33e1) | Jun 17, 2023 |
| Sony          | SVF1421L1EW                 | Notebook    | [5d377cbe13](https://linux-hardware.org/?probe=5d377cbe13) | Jun 17, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | Notebook    | [2bfd69673e](https://linux-hardware.org/?probe=2bfd69673e) | Jun 17, 2023 |
| ASRock        | IMB-171-L                   | Desktop     | [257b925f7a](https://linux-hardware.org/?probe=257b925f7a) | Jun 17, 2023 |
| ZOTAC         | ZBOX-CI622/CI642/CI662NA... | Mini pc     | [cacfc6480f](https://linux-hardware.org/?probe=cacfc6480f) | Jun 17, 2023 |
| Sony          | SVF1421L1EW                 | Notebook    | [e4dc7d363e](https://linux-hardware.org/?probe=e4dc7d363e) | Jun 17, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [bbc5301e6b](https://linux-hardware.org/?probe=bbc5301e6b) | Jun 17, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [b61e6bc6d2](https://linux-hardware.org/?probe=b61e6bc6d2) | Jun 17, 2023 |
| Compumax C... | ONIX-CEL-0001               | Notebook    | [2fb2088533](https://linux-hardware.org/?probe=2fb2088533) | Jun 17, 2023 |
| ECS           | A890GXM-A2                  | Desktop     | [722b363829](https://linux-hardware.org/?probe=722b363829) | Jun 17, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [fa9508da6e](https://linux-hardware.org/?probe=fa9508da6e) | Jun 17, 2023 |
| MSI           | MS-AA71                     | All in one  | [b885127916](https://linux-hardware.org/?probe=b885127916) | Jun 17, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [9206f6c141](https://linux-hardware.org/?probe=9206f6c141) | Jun 17, 2023 |
| ASRock        | A320M-HDV R3.0              | Desktop     | [f7dd657c90](https://linux-hardware.org/?probe=f7dd657c90) | Jun 17, 2023 |
| Acer          | Aspire ES1-520              | Notebook    | [3d8b5e9564](https://linux-hardware.org/?probe=3d8b5e9564) | Jun 17, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [98c46aeea5](https://linux-hardware.org/?probe=98c46aeea5) | Jun 17, 2023 |
| Acer          | Aspire ES1-520              | Notebook    | [fb8da18b42](https://linux-hardware.org/?probe=fb8da18b42) | Jun 17, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [b244c822ef](https://linux-hardware.org/?probe=b244c822ef) | Jun 17, 2023 |
| Lenovo        | ThinkPad Edge E535 3260F... | Notebook    | [3fd273f672](https://linux-hardware.org/?probe=3fd273f672) | Jun 17, 2023 |
| MSI           | GT70                        | Notebook    | [3ccbd6cfb4](https://linux-hardware.org/?probe=3ccbd6cfb4) | Jun 17, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [a599147e58](https://linux-hardware.org/?probe=a599147e58) | Jun 17, 2023 |
| Acer          | Aspire E5-471               | Notebook    | [48154f868d](https://linux-hardware.org/?probe=48154f868d) | Jun 17, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | Desktop     | [29c006c668](https://linux-hardware.org/?probe=29c006c668) | Jun 17, 2023 |
| ASUSTek       | T101HA                      | Tablet      | [834705c660](https://linux-hardware.org/?probe=834705c660) | Jun 17, 2023 |
| ASRock        | B660M Steel Legend          | Desktop     | [75f3194c4e](https://linux-hardware.org/?probe=75f3194c4e) | Jun 17, 2023 |
| ASRock        | B660M Steel Legend          | Desktop     | [454fea2b00](https://linux-hardware.org/?probe=454fea2b00) | Jun 17, 2023 |
| Toshiba       | Satellite C50D-C            | Notebook    | [ea1fabfdc3](https://linux-hardware.org/?probe=ea1fabfdc3) | Jun 17, 2023 |
| Toshiba       | Satellite C50D-C            | Notebook    | [207d5f5dbd](https://linux-hardware.org/?probe=207d5f5dbd) | Jun 17, 2023 |
| Acer          | Aspire A315-510P            | Notebook    | [d1be914db1](https://linux-hardware.org/?probe=d1be914db1) | Jun 17, 2023 |
| Gigabyte      | MMLP5AP-00                  | Notebook    | [1f59319cc3](https://linux-hardware.org/?probe=1f59319cc3) | Jun 17, 2023 |
| Gigabyte      | GA-990FXA-D3                | Desktop     | [44f21e0f7e](https://linux-hardware.org/?probe=44f21e0f7e) | Jun 17, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [6e0568f0df](https://linux-hardware.org/?probe=6e0568f0df) | Jun 17, 2023 |
| Toshiba       | Satellite L775D-107         | Notebook    | [7959d73eb9](https://linux-hardware.org/?probe=7959d73eb9) | Jun 17, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [e26a82f97f](https://linux-hardware.org/?probe=e26a82f97f) | Jun 17, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [7e8ae5cb7a](https://linux-hardware.org/?probe=7e8ae5cb7a) | Jun 16, 2023 |
| HP            | 630                         | Notebook    | [493010a411](https://linux-hardware.org/?probe=493010a411) | Jun 16, 2023 |
| MSI           | MS-AA71                     | All in one  | [feaaf5fbc0](https://linux-hardware.org/?probe=feaaf5fbc0) | Jun 16, 2023 |
| ASUSTek       | K73BR                       | Notebook    | [9f4d2564bf](https://linux-hardware.org/?probe=9f4d2564bf) | Jun 16, 2023 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [1b0dd608b2](https://linux-hardware.org/?probe=1b0dd608b2) | Jun 16, 2023 |
| MSI           | Modern 14 B5M               | Notebook    | [21bd3b8234](https://linux-hardware.org/?probe=21bd3b8234) | Jun 16, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [288db43785](https://linux-hardware.org/?probe=288db43785) | Jun 16, 2023 |
| Biostar       | B450MH                      | Desktop     | [04c924ce6f](https://linux-hardware.org/?probe=04c924ce6f) | Jun 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [ccb49000fa](https://linux-hardware.org/?probe=ccb49000fa) | Jun 16, 2023 |
| HP            | 1587h                       | Desktop     | [bb361f8bca](https://linux-hardware.org/?probe=bb361f8bca) | Jun 16, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [6d154340b0](https://linux-hardware.org/?probe=6d154340b0) | Jun 16, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [87cd6547ad](https://linux-hardware.org/?probe=87cd6547ad) | Jun 16, 2023 |
| Lenovo        | Unknown                     | Notebook    | [cd3733c1d5](https://linux-hardware.org/?probe=cd3733c1d5) | Jun 16, 2023 |
| Lenovo        | Unknown                     | Notebook    | [e80d3a47d8](https://linux-hardware.org/?probe=e80d3a47d8) | Jun 16, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [852d16ee14](https://linux-hardware.org/?probe=852d16ee14) | Jun 16, 2023 |
| Dell          | Latitude E6320              | Notebook    | [f1552f3016](https://linux-hardware.org/?probe=f1552f3016) | Jun 16, 2023 |
| Lenovo        | 315F SDK0J40697 WIN 3305... | Desktop     | [dac73c9b94](https://linux-hardware.org/?probe=dac73c9b94) | Jun 16, 2023 |
| HP            | Stream Notebook PC 13       | Notebook    | [e5f0ea5412](https://linux-hardware.org/?probe=e5f0ea5412) | Jun 16, 2023 |
| Intel         | B85                         | Desktop     | [1e688ea5e1](https://linux-hardware.org/?probe=1e688ea5e1) | Jun 16, 2023 |
| Positivo      | POS-EINM70CS POS            | Desktop     | [a2d50f27d7](https://linux-hardware.org/?probe=a2d50f27d7) | Jun 16, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [dd2a8a9559](https://linux-hardware.org/?probe=dd2a8a9559) | Jun 15, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [15842a2029](https://linux-hardware.org/?probe=15842a2029) | Jun 15, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [2b4d4506c2](https://linux-hardware.org/?probe=2b4d4506c2) | Jun 15, 2023 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [d517ea1435](https://linux-hardware.org/?probe=d517ea1435) | Jun 15, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [b27c911277](https://linux-hardware.org/?probe=b27c911277) | Jun 15, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [13c74e7a46](https://linux-hardware.org/?probe=13c74e7a46) | Jun 15, 2023 |
| Lenovo        | IdeaPad N580 20182          | Notebook    | [93cb5afc77](https://linux-hardware.org/?probe=93cb5afc77) | Jun 15, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [706eeef80f](https://linux-hardware.org/?probe=706eeef80f) | Jun 15, 2023 |
| Dell          | Latitude 5420               | Notebook    | [d3327c76f1](https://linux-hardware.org/?probe=d3327c76f1) | Jun 15, 2023 |
| Dell          | Inspiron 3576               | Notebook    | [a1b979f02c](https://linux-hardware.org/?probe=a1b979f02c) | Jun 15, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [160f6f4afb](https://linux-hardware.org/?probe=160f6f4afb) | Jun 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [5141d5dd1a](https://linux-hardware.org/?probe=5141d5dd1a) | Jun 15, 2023 |
| HP            | HDX18                       | Notebook    | [9a49d14af9](https://linux-hardware.org/?probe=9a49d14af9) | Jun 15, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [1360220387](https://linux-hardware.org/?probe=1360220387) | Jun 15, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [5ce34d4e94](https://linux-hardware.org/?probe=5ce34d4e94) | Jun 15, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [92482439de](https://linux-hardware.org/?probe=92482439de) | Jun 15, 2023 |
| Positivo      | POS-PIB150DT                | Desktop     | [cddf7d4ac9](https://linux-hardware.org/?probe=cddf7d4ac9) | Jun 15, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [a3990bdddb](https://linux-hardware.org/?probe=a3990bdddb) | Jun 15, 2023 |
| HP            | ENVY Notebook               | Notebook    | [4a4602250b](https://linux-hardware.org/?probe=4a4602250b) | Jun 15, 2023 |
| HP            | Notebook                    | Notebook    | [dc40bd89f8](https://linux-hardware.org/?probe=dc40bd89f8) | Jun 15, 2023 |
| HP            | ENVY Notebook               | Notebook    | [54115f309f](https://linux-hardware.org/?probe=54115f309f) | Jun 15, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [23a8eeaa23](https://linux-hardware.org/?probe=23a8eeaa23) | Jun 15, 2023 |
| Apple         | MacBookAir4,1               | Notebook    | [e8575f0a34](https://linux-hardware.org/?probe=e8575f0a34) | Jun 15, 2023 |
| ASRock        | X99E-ITX/ac                 | Desktop     | [fd9f82a006](https://linux-hardware.org/?probe=fd9f82a006) | Jun 15, 2023 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [cc3d8c4659](https://linux-hardware.org/?probe=cc3d8c4659) | Jun 15, 2023 |
| Dell          | Latitude D430               | Notebook    | [ecf3763cf7](https://linux-hardware.org/?probe=ecf3763cf7) | Jun 15, 2023 |
| Gigabyte      | P55-USB3                    | Desktop     | [eb497abe93](https://linux-hardware.org/?probe=eb497abe93) | Jun 14, 2023 |
| Dell          | Precision M4500             | Notebook    | [5daca408ec](https://linux-hardware.org/?probe=5daca408ec) | Jun 14, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [ca0a511cd7](https://linux-hardware.org/?probe=ca0a511cd7) | Jun 14, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [1bb2844504](https://linux-hardware.org/?probe=1bb2844504) | Jun 14, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [ea8e583821](https://linux-hardware.org/?probe=ea8e583821) | Jun 14, 2023 |
| HP            | G61                         | Notebook    | [52e962e82d](https://linux-hardware.org/?probe=52e962e82d) | Jun 14, 2023 |
| Dell          | 0GU083 A00                  | Desktop     | [3d6b3b5013](https://linux-hardware.org/?probe=3d6b3b5013) | Jun 14, 2023 |
| Dell          | 0D28YY A00                  | Desktop     | [572840f1e9](https://linux-hardware.org/?probe=572840f1e9) | Jun 14, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [69048c54c9](https://linux-hardware.org/?probe=69048c54c9) | Jun 14, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [2ecd3dd29b](https://linux-hardware.org/?probe=2ecd3dd29b) | Jun 14, 2023 |
| MSI           | 970A-G46                    | Desktop     | [95a0297b20](https://linux-hardware.org/?probe=95a0297b20) | Jun 14, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [1f5318c2b4](https://linux-hardware.org/?probe=1f5318c2b4) | Jun 14, 2023 |
| MSI           | 970A-G46                    | Desktop     | [76441700d5](https://linux-hardware.org/?probe=76441700d5) | Jun 14, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [3d5cabad57](https://linux-hardware.org/?probe=3d5cabad57) | Jun 14, 2023 |
| Dell          | 0C2XKD A01                  | Desktop     | [a4ecbb165e](https://linux-hardware.org/?probe=a4ecbb165e) | Jun 14, 2023 |
| HP            | ENVY Notebook               | Notebook    | [6e714661f6](https://linux-hardware.org/?probe=6e714661f6) | Jun 14, 2023 |
| Intel         | H61                         | Desktop     | [5d4fb99018](https://linux-hardware.org/?probe=5d4fb99018) | Jun 14, 2023 |
| HP            | Pavilion 17                 | Notebook    | [bf5d126cc8](https://linux-hardware.org/?probe=bf5d126cc8) | Jun 14, 2023 |
| MSI           | GT75 Titan 8RG              | Notebook    | [9e25159fb6](https://linux-hardware.org/?probe=9e25159fb6) | Jun 14, 2023 |
| ASUSTek       | ASUS EXPERTBOOK L1500CDA... | Notebook    | [5659761c9c](https://linux-hardware.org/?probe=5659761c9c) | Jun 14, 2023 |
| Lenovo        | Legion 5 15ITH6H 82JH       | Notebook    | [448deb90fa](https://linux-hardware.org/?probe=448deb90fa) | Jun 14, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [49e4d6ccb3](https://linux-hardware.org/?probe=49e4d6ccb3) | Jun 14, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [0c3df957ce](https://linux-hardware.org/?probe=0c3df957ce) | Jun 14, 2023 |
| Lenovo        | IdeaPadFlex 5 16IRU8 82Y... | Convertible | [97e81b884c](https://linux-hardware.org/?probe=97e81b884c) | Jun 14, 2023 |
| Dell          | Inspiron 5548               | Notebook    | [e7f84bdb10](https://linux-hardware.org/?probe=e7f84bdb10) | Jun 14, 2023 |
| ASUSTek       | X750JN                      | Notebook    | [f6f21e895a](https://linux-hardware.org/?probe=f6f21e895a) | Jun 14, 2023 |
| Dell          | Inspiron 5548               | Notebook    | [7b3593a797](https://linux-hardware.org/?probe=7b3593a797) | Jun 13, 2023 |
| Toshiba       | Satellite L45-B             | Notebook    | [85b5d49142](https://linux-hardware.org/?probe=85b5d49142) | Jun 13, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [785b0849fd](https://linux-hardware.org/?probe=785b0849fd) | Jun 13, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [ab92fe4791](https://linux-hardware.org/?probe=ab92fe4791) | Jun 13, 2023 |
| Lenovo        | E41-25 81FS                 | Notebook    | [fffb0a25f1](https://linux-hardware.org/?probe=fffb0a25f1) | Jun 13, 2023 |
| ASUSTek       | A88XM-E                     | Desktop     | [1302a62eeb](https://linux-hardware.org/?probe=1302a62eeb) | Jun 13, 2023 |
| HP            | Laptop 15z-ef3xxx           | Notebook    | [8ef61f4720](https://linux-hardware.org/?probe=8ef61f4720) | Jun 13, 2023 |
| Dell          | Latitude E6540              | Notebook    | [7e731e731c](https://linux-hardware.org/?probe=7e731e731c) | Jun 13, 2023 |
| Samsung       | R540/R538/SA41/E452         | Notebook    | [678c5510d3](https://linux-hardware.org/?probe=678c5510d3) | Jun 13, 2023 |
| Dell          | Latitude 5490               | Notebook    | [1e6933ec61](https://linux-hardware.org/?probe=1e6933ec61) | Jun 13, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [d2a0d735db](https://linux-hardware.org/?probe=d2a0d735db) | Jun 13, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [1626648a8b](https://linux-hardware.org/?probe=1626648a8b) | Jun 13, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [1439681971](https://linux-hardware.org/?probe=1439681971) | Jun 13, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [3a8d104147](https://linux-hardware.org/?probe=3a8d104147) | Jun 13, 2023 |
| ASUSTek       | X556UQK                     | Notebook    | [50c975ae08](https://linux-hardware.org/?probe=50c975ae08) | Jun 13, 2023 |
| Samsung       | RV408/RV508                 | Notebook    | [4ec36cfa9e](https://linux-hardware.org/?probe=4ec36cfa9e) | Jun 13, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [b2eb89c4fd](https://linux-hardware.org/?probe=b2eb89c4fd) | Jun 13, 2023 |
| HP            | 2AE5 A01                    | Desktop     | [992b755286](https://linux-hardware.org/?probe=992b755286) | Jun 13, 2023 |
| HP            | 2AE5 A01                    | Desktop     | [43cce62781](https://linux-hardware.org/?probe=43cce62781) | Jun 13, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [488d6c38b8](https://linux-hardware.org/?probe=488d6c38b8) | Jun 13, 2023 |
| Apple         | MacBookAir7,1               | Notebook    | [d4780e9674](https://linux-hardware.org/?probe=d4780e9674) | Jun 13, 2023 |
| Acer          | Aspire A515-54              | Notebook    | [a15cb3f487](https://linux-hardware.org/?probe=a15cb3f487) | Jun 13, 2023 |
| HP            | Pavilion 17                 | Notebook    | [54eb1dbd1c](https://linux-hardware.org/?probe=54eb1dbd1c) | Jun 13, 2023 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | Notebook    | [c765305160](https://linux-hardware.org/?probe=c765305160) | Jun 13, 2023 |
| MSI           | B350M MORTAR                | Desktop     | [2b88daaaea](https://linux-hardware.org/?probe=2b88daaaea) | Jun 13, 2023 |
| MSI           | B350M MORTAR                | Desktop     | [c3f70b8f48](https://linux-hardware.org/?probe=c3f70b8f48) | Jun 13, 2023 |
| MW            | NVR-N5105                   | Desktop     | [7481711a2f](https://linux-hardware.org/?probe=7481711a2f) | Jun 13, 2023 |
| Dell          | Inspiron 3576               | Notebook    | [722f7d1224](https://linux-hardware.org/?probe=722f7d1224) | Jun 12, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [7a6d7a1885](https://linux-hardware.org/?probe=7a6d7a1885) | Jun 12, 2023 |
| MSI           | MEG X570S ACE MAX           | Desktop     | [9f509b3507](https://linux-hardware.org/?probe=9f509b3507) | Jun 12, 2023 |
| MSI           | Z97 PC Mate                 | Desktop     | [5cfb578ee0](https://linux-hardware.org/?probe=5cfb578ee0) | Jun 12, 2023 |
| MSI           | MEG X570S ACE MAX           | Desktop     | [ad78badc4f](https://linux-hardware.org/?probe=ad78badc4f) | Jun 12, 2023 |
| MouseCompu... | B360M                       | Desktop     | [6a7f26bdae](https://linux-hardware.org/?probe=6a7f26bdae) | Jun 12, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [0dfc0118d2](https://linux-hardware.org/?probe=0dfc0118d2) | Jun 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [9a4af7d5c3](https://linux-hardware.org/?probe=9a4af7d5c3) | Jun 12, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [fba7b6bdc0](https://linux-hardware.org/?probe=fba7b6bdc0) | Jun 12, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [b815ac19d4](https://linux-hardware.org/?probe=b815ac19d4) | Jun 12, 2023 |
| ASUSTek       | ASUS BR1100FKA BR1100FKA    | Convertible | [2c990e1b7b](https://linux-hardware.org/?probe=2c990e1b7b) | Jun 12, 2023 |
| Toshiba       | Satellite R630              | Notebook    | [aac5cdbb4f](https://linux-hardware.org/?probe=aac5cdbb4f) | Jun 12, 2023 |
| ASUSTek       | ASUS BR1100FKA BR1100FKA    | Convertible | [933d2b1063](https://linux-hardware.org/?probe=933d2b1063) | Jun 12, 2023 |
| HP            | Laptop 17z-ca300            | Notebook    | [e34ff97445](https://linux-hardware.org/?probe=e34ff97445) | Jun 12, 2023 |
| HP            | Laptop 17z-ca300            | Notebook    | [23024c94f1](https://linux-hardware.org/?probe=23024c94f1) | Jun 12, 2023 |
| HP            | 8703                        | Desktop     | [3bb8525ff9](https://linux-hardware.org/?probe=3bb8525ff9) | Jun 11, 2023 |
| HP            | 1497                        | Desktop     | [396e1ec78e](https://linux-hardware.org/?probe=396e1ec78e) | Jun 11, 2023 |
| HP            | 3397                        | Desktop     | [9f71c4173c](https://linux-hardware.org/?probe=9f71c4173c) | Jun 11, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [e6079c9659](https://linux-hardware.org/?probe=e6079c9659) | Jun 11, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [5a7c331645](https://linux-hardware.org/?probe=5a7c331645) | Jun 11, 2023 |
| Intel         | DQ67EP AAG12529-308         | Desktop     | [a47237c452](https://linux-hardware.org/?probe=a47237c452) | Jun 11, 2023 |
| Shuttle       | FX50V4                      | Desktop     | [f6954d1b3c](https://linux-hardware.org/?probe=f6954d1b3c) | Jun 11, 2023 |
| Shuttle       | FX50V4                      | Desktop     | [1a76b058a0](https://linux-hardware.org/?probe=1a76b058a0) | Jun 11, 2023 |
| SDZ           | X133                        | Notebook    | [83b402146d](https://linux-hardware.org/?probe=83b402146d) | Jun 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [f6e70e460f](https://linux-hardware.org/?probe=f6e70e460f) | Jun 11, 2023 |
| ASUSTek       | X75VC                       | Notebook    | [77cb4dfd02](https://linux-hardware.org/?probe=77cb4dfd02) | Jun 11, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [77310a6741](https://linux-hardware.org/?probe=77310a6741) | Jun 11, 2023 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [78fe530046](https://linux-hardware.org/?probe=78fe530046) | Jun 11, 2023 |
| Dell          | 0RN4PJ A01                  | Server      | [d318d770a8](https://linux-hardware.org/?probe=d318d770a8) | Jun 11, 2023 |
| Acer          | Aspire 5734Z                | Notebook    | [dd7a524e59](https://linux-hardware.org/?probe=dd7a524e59) | Jun 10, 2023 |
| Lenovo        | ThinkPad T440p 20AN0069U... | Notebook    | [a2ddfa44e7](https://linux-hardware.org/?probe=a2ddfa44e7) | Jun 10, 2023 |
| MSI           | MS-B0621 100                | All in one  | [aa67f8201a](https://linux-hardware.org/?probe=aa67f8201a) | Jun 10, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [edec9d7178](https://linux-hardware.org/?probe=edec9d7178) | Jun 10, 2023 |
| Gigabyte      | H57M-USB3                   | Desktop     | [91b1655f60](https://linux-hardware.org/?probe=91b1655f60) | Jun 10, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [b7dfbae839](https://linux-hardware.org/?probe=b7dfbae839) | Jun 10, 2023 |
| HP            | Pavilion dv6                | Notebook    | [1388a433de](https://linux-hardware.org/?probe=1388a433de) | Jun 10, 2023 |
| Lenovo        | IdeaPad N580 20182          | Notebook    | [8990fd0b51](https://linux-hardware.org/?probe=8990fd0b51) | Jun 10, 2023 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [cc206f52b1](https://linux-hardware.org/?probe=cc206f52b1) | Jun 10, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [9d9872a84a](https://linux-hardware.org/?probe=9d9872a84a) | Jun 10, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [770045a9fc](https://linux-hardware.org/?probe=770045a9fc) | Jun 10, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [d3480eedcd](https://linux-hardware.org/?probe=d3480eedcd) | Jun 10, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [8d07581960](https://linux-hardware.org/?probe=8d07581960) | Jun 10, 2023 |
| ASUSTek       | ASUS BR1100FKA BR1100FKA    | Convertible | [0239123977](https://linux-hardware.org/?probe=0239123977) | Jun 10, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [3554e00d28](https://linux-hardware.org/?probe=3554e00d28) | Jun 10, 2023 |
| ASUSTek       | ASUS BR1100FKA BR1100FKA    | Convertible | [e45eaed9f1](https://linux-hardware.org/?probe=e45eaed9f1) | Jun 10, 2023 |
| Samsung       | N102SP/N100SP/N101SP        | Notebook    | [c31b0e5f30](https://linux-hardware.org/?probe=c31b0e5f30) | Jun 10, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [bdca36306b](https://linux-hardware.org/?probe=bdca36306b) | Jun 10, 2023 |
| Gigabyte      | P57V6                       | Notebook    | [a2ce7ccc80](https://linux-hardware.org/?probe=a2ce7ccc80) | Jun 09, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [bd22edfae7](https://linux-hardware.org/?probe=bd22edfae7) | Jun 09, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [0e34d2ee28](https://linux-hardware.org/?probe=0e34d2ee28) | Jun 09, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [c64ff76dba](https://linux-hardware.org/?probe=c64ff76dba) | Jun 09, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [afa2a30d75](https://linux-hardware.org/?probe=afa2a30d75) | Jun 09, 2023 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [37c25e136f](https://linux-hardware.org/?probe=37c25e136f) | Jun 09, 2023 |
| Sony          | VPCEB2AFD                   | Notebook    | [1d9d6ddd74](https://linux-hardware.org/?probe=1d9d6ddd74) | Jun 09, 2023 |
| Lenovo        | ThinkStation E20 422237U    | Desktop     | [2756905647](https://linux-hardware.org/?probe=2756905647) | Jun 09, 2023 |
| Dell          | Latitude 5420               | Notebook    | [956a995580](https://linux-hardware.org/?probe=956a995580) | Jun 09, 2023 |
| Dell          | Precision M4600             | Notebook    | [a79a783515](https://linux-hardware.org/?probe=a79a783515) | Jun 09, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [50c36acc0d](https://linux-hardware.org/?probe=50c36acc0d) | Jun 09, 2023 |
| Fujitsu       | LIFEBOOK E754               | Notebook    | [4d09f42447](https://linux-hardware.org/?probe=4d09f42447) | Jun 09, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [b88712538e](https://linux-hardware.org/?probe=b88712538e) | Jun 09, 2023 |
| Dell          | 0YXT71 A00                  | Desktop     | [477afe615b](https://linux-hardware.org/?probe=477afe615b) | Jun 09, 2023 |
| Dell          | 0YXT71 A00                  | Desktop     | [463dfa5d83](https://linux-hardware.org/?probe=463dfa5d83) | Jun 09, 2023 |
| Biostar       | A68N-2100K                  | Desktop     | [9ac86a512d](https://linux-hardware.org/?probe=9ac86a512d) | Jun 09, 2023 |
| Panasonic     | CF-S10CDHEDM                | Notebook    | [19b6085754](https://linux-hardware.org/?probe=19b6085754) | Jun 09, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [c35e22de2b](https://linux-hardware.org/?probe=c35e22de2b) | Jun 09, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [68be9da7f1](https://linux-hardware.org/?probe=68be9da7f1) | Jun 09, 2023 |
| HP            | Notebook                    | Notebook    | [e292bb9d5a](https://linux-hardware.org/?probe=e292bb9d5a) | Jun 09, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [51bfdec531](https://linux-hardware.org/?probe=51bfdec531) | Jun 09, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [2dfd2a0844](https://linux-hardware.org/?probe=2dfd2a0844) | Jun 08, 2023 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [931b9e2b05](https://linux-hardware.org/?probe=931b9e2b05) | Jun 08, 2023 |
| Lenovo        | ThinkPad X280 20KES5SE22    | Notebook    | [c25a510191](https://linux-hardware.org/?probe=c25a510191) | Jun 08, 2023 |
| ASUSTek       | H81M-R                      | Desktop     | [10d01671ad](https://linux-hardware.org/?probe=10d01671ad) | Jun 08, 2023 |
| Lenovo        | Z50-70 20354                | Notebook    | [28a5b69096](https://linux-hardware.org/?probe=28a5b69096) | Jun 08, 2023 |
| ASUSTek       | X580VN                      | Notebook    | [8c1cf3f164](https://linux-hardware.org/?probe=8c1cf3f164) | Jun 08, 2023 |
| MSI           | Z87-G43                     | Desktop     | [554f8ea405](https://linux-hardware.org/?probe=554f8ea405) | Jun 08, 2023 |
| MSI           | X58M                        | Desktop     | [7f0ef36058](https://linux-hardware.org/?probe=7f0ef36058) | Jun 08, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [86dfe28c7a](https://linux-hardware.org/?probe=86dfe28c7a) | Jun 08, 2023 |
| HP            | 1494                        | Desktop     | [7e431c0351](https://linux-hardware.org/?probe=7e431c0351) | Jun 08, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [cd3bb98a1e](https://linux-hardware.org/?probe=cd3bb98a1e) | Jun 08, 2023 |
| Micro Comp... | NUCXI7                      | Notebook    | [3b930f4e22](https://linux-hardware.org/?probe=3b930f4e22) | Jun 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [3acaedf40f](https://linux-hardware.org/?probe=3acaedf40f) | Jun 08, 2023 |
| ASRock        | M3A770DE                    | Desktop     | [aa9ddf538e](https://linux-hardware.org/?probe=aa9ddf538e) | Jun 08, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [c8ee97b7b9](https://linux-hardware.org/?probe=c8ee97b7b9) | Jun 07, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [1d84d556bf](https://linux-hardware.org/?probe=1d84d556bf) | Jun 07, 2023 |
| ASUSTek       | STRIX Z270I GAMING          | Desktop     | [f836a7d0ff](https://linux-hardware.org/?probe=f836a7d0ff) | Jun 07, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [73fa9d854f](https://linux-hardware.org/?probe=73fa9d854f) | Jun 07, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [6a98d856ee](https://linux-hardware.org/?probe=6a98d856ee) | Jun 07, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | Notebook    | [6062ee64a9](https://linux-hardware.org/?probe=6062ee64a9) | Jun 07, 2023 |
| HP            | 1494                        | Desktop     | [0f032c101b](https://linux-hardware.org/?probe=0f032c101b) | Jun 07, 2023 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [14016f0f6f](https://linux-hardware.org/?probe=14016f0f6f) | Jun 07, 2023 |
| Acer          | Predator PT515-51           | Notebook    | [0a6efd54ad](https://linux-hardware.org/?probe=0a6efd54ad) | Jun 07, 2023 |
| MSI           | MS-7513                     | Desktop     | [ed69341f3c](https://linux-hardware.org/?probe=ed69341f3c) | Jun 07, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [9ef95ad480](https://linux-hardware.org/?probe=9ef95ad480) | Jun 07, 2023 |
| HP            | 0A60h                       | Desktop     | [f0498c1a54](https://linux-hardware.org/?probe=f0498c1a54) | Jun 07, 2023 |
| Samsung       | 450R5J/450R5Q/4550RJ        | Notebook    | [4b679d78eb](https://linux-hardware.org/?probe=4b679d78eb) | Jun 07, 2023 |
| ZOTAC         | ZBOX-CI622/CI642/CI662NA... | Mini pc     | [bc11217633](https://linux-hardware.org/?probe=bc11217633) | Jun 06, 2023 |
| MSI           | GE70 2PE                    | Notebook    | [c62d13879f](https://linux-hardware.org/?probe=c62d13879f) | Jun 06, 2023 |
| Fujitsu Si... | D2811-A1 S26361-D2811-A1    | Desktop     | [bcb9105121](https://linux-hardware.org/?probe=bcb9105121) | Jun 06, 2023 |
| Gigabyte      | Z68P-DS3                    | Desktop     | [3371099509](https://linux-hardware.org/?probe=3371099509) | Jun 06, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [0fd8af3392](https://linux-hardware.org/?probe=0fd8af3392) | Jun 06, 2023 |
| Intel         | NUC5i5MYBE H47797-206       | Mini pc     | [a860a6cf23](https://linux-hardware.org/?probe=a860a6cf23) | Jun 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [1e5a50fa47](https://linux-hardware.org/?probe=1e5a50fa47) | Jun 06, 2023 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [476a44deee](https://linux-hardware.org/?probe=476a44deee) | Jun 06, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [a34c3550be](https://linux-hardware.org/?probe=a34c3550be) | Jun 06, 2023 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [2f138401f6](https://linux-hardware.org/?probe=2f138401f6) | Jun 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [e8df83921f](https://linux-hardware.org/?probe=e8df83921f) | Jun 06, 2023 |
| Acer          | Aspire V5-572P              | Notebook    | [cdb5005799](https://linux-hardware.org/?probe=cdb5005799) | Jun 06, 2023 |
| Acer          | Aspire V5-572P              | Notebook    | [49745927a0](https://linux-hardware.org/?probe=49745927a0) | Jun 06, 2023 |
| Dell          | Precision M4800             | Notebook    | [f1c43c9acd](https://linux-hardware.org/?probe=f1c43c9acd) | Jun 06, 2023 |
| Dell          | 0Y2K8N A01                  | Desktop     | [13a93fdc21](https://linux-hardware.org/?probe=13a93fdc21) | Jun 05, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [9286154198](https://linux-hardware.org/?probe=9286154198) | Jun 05, 2023 |
| ASUSTek       | M5A88-M                     | Desktop     | [bb29b433c0](https://linux-hardware.org/?probe=bb29b433c0) | Jun 05, 2023 |
| Acer          | Aspire A517-53              | Notebook    | [a039ca0054](https://linux-hardware.org/?probe=a039ca0054) | Jun 05, 2023 |
| Compaq        | CQ-27                       | Notebook    | [ae3d9bce8c](https://linux-hardware.org/?probe=ae3d9bce8c) | Jun 05, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [e9d79e576b](https://linux-hardware.org/?probe=e9d79e576b) | Jun 05, 2023 |
| Acer          | Aspire ES1-711              | Notebook    | [5534470ef5](https://linux-hardware.org/?probe=5534470ef5) | Jun 05, 2023 |
| Acer          | Aspire ES1-571              | Notebook    | [ed19db3614](https://linux-hardware.org/?probe=ed19db3614) | Jun 05, 2023 |
| AMI           | Intel                       | Desktop     | [7990e6561b](https://linux-hardware.org/?probe=7990e6561b) | Jun 05, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [8ba3a60a93](https://linux-hardware.org/?probe=8ba3a60a93) | Jun 05, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [b142b6de06](https://linux-hardware.org/?probe=b142b6de06) | Jun 05, 2023 |
| Dell          | 0KWVT8 A03                  | Desktop     | [e974c8cdcd](https://linux-hardware.org/?probe=e974c8cdcd) | Jun 05, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [202c4ee201](https://linux-hardware.org/?probe=202c4ee201) | Jun 04, 2023 |
| AMI           | Intel                       | Desktop     | [966c93cbdb](https://linux-hardware.org/?probe=966c93cbdb) | Jun 04, 2023 |
| ASUSTek       | M5A88-M                     | Desktop     | [e750392f99](https://linux-hardware.org/?probe=e750392f99) | Jun 04, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [7c35e9a268](https://linux-hardware.org/?probe=7c35e9a268) | Jun 04, 2023 |
| Jumper        | EZbook                      | Notebook    | [950179fe29](https://linux-hardware.org/?probe=950179fe29) | Jun 04, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E1S    | Notebook    | [4d9e4fb129](https://linux-hardware.org/?probe=4d9e4fb129) | Jun 04, 2023 |
| Dell          | Latitude E5440              | Notebook    | [02b3462a2c](https://linux-hardware.org/?probe=02b3462a2c) | Jun 04, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [5716ed966d](https://linux-hardware.org/?probe=5716ed966d) | Jun 04, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [a3d127e3ba](https://linux-hardware.org/?probe=a3d127e3ba) | Jun 04, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [3ef3c9ec82](https://linux-hardware.org/?probe=3ef3c9ec82) | Jun 04, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [4840dda2e3](https://linux-hardware.org/?probe=4840dda2e3) | Jun 04, 2023 |
| Gigabyte      | Z87-HD3                     | Desktop     | [228a46e465](https://linux-hardware.org/?probe=228a46e465) | Jun 04, 2023 |
| Acer          | Swift SF316-51              | Notebook    | [4ba1405836](https://linux-hardware.org/?probe=4ba1405836) | Jun 04, 2023 |
| Gigabyte      | G33M-S2                     | Desktop     | [17ed1704c5](https://linux-hardware.org/?probe=17ed1704c5) | Jun 04, 2023 |
| HP            | 1493                        | Desktop     | [b7432a020a](https://linux-hardware.org/?probe=b7432a020a) | Jun 04, 2023 |
| Gigabyte      | G33M-S2                     | Desktop     | [82bab4dd6d](https://linux-hardware.org/?probe=82bab4dd6d) | Jun 04, 2023 |
| ASUSTek       | PN53                        | Mini pc     | [e541266510](https://linux-hardware.org/?probe=e541266510) | Jun 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [77d585fa03](https://linux-hardware.org/?probe=77d585fa03) | Jun 04, 2023 |
| Biostar       | B350GT5                     | Desktop     | [18e1da8cce](https://linux-hardware.org/?probe=18e1da8cce) | Jun 04, 2023 |
| Acer          | Aspire E1-572P              | Notebook    | [a90316cac7](https://linux-hardware.org/?probe=a90316cac7) | Jun 04, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [6167898a10](https://linux-hardware.org/?probe=6167898a10) | Jun 04, 2023 |
| Biostar       | B350GT5                     | Desktop     | [123beb390f](https://linux-hardware.org/?probe=123beb390f) | Jun 04, 2023 |
| ASUSTek       | P5G41T-M                    | Desktop     | [8706eff580](https://linux-hardware.org/?probe=8706eff580) | Jun 04, 2023 |
| MSI           | H81M-P32                    | Desktop     | [f2423b3ef9](https://linux-hardware.org/?probe=f2423b3ef9) | Jun 04, 2023 |
| MSI           | H81M-P32                    | Desktop     | [f1d0b1d487](https://linux-hardware.org/?probe=f1d0b1d487) | Jun 04, 2023 |
| Toshiba       | Satellite Pro L300          | Notebook    | [968005c798](https://linux-hardware.org/?probe=968005c798) | Jun 04, 2023 |
| HP            | 2AE5 A01                    | Desktop     | [ab3ab74fb6](https://linux-hardware.org/?probe=ab3ab74fb6) | Jun 04, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [60749b6e47](https://linux-hardware.org/?probe=60749b6e47) | Jun 04, 2023 |
| MSI           | P55-CD53                    | Desktop     | [88efe4b48c](https://linux-hardware.org/?probe=88efe4b48c) | Jun 04, 2023 |
| ZOTAC         | ZBOX-CI622/CI642/CI662NA... | Mini pc     | [737168e339](https://linux-hardware.org/?probe=737168e339) | Jun 04, 2023 |
| HP            | 2B43                        | Desktop     | [d66cd5f48e](https://linux-hardware.org/?probe=d66cd5f48e) | Jun 04, 2023 |
| Dell          | 0KWVT8 A03                  | Desktop     | [2250609446](https://linux-hardware.org/?probe=2250609446) | Jun 04, 2023 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [d8f9165fec](https://linux-hardware.org/?probe=d8f9165fec) | Jun 04, 2023 |
| Dell          | 0KWVT8 A03                  | Desktop     | [7f73996b8e](https://linux-hardware.org/?probe=7f73996b8e) | Jun 04, 2023 |
| ASRock        | Z590 Phantom Gaming 4       | Desktop     | [1e9eef0102](https://linux-hardware.org/?probe=1e9eef0102) | Jun 03, 2023 |
| Lenovo        | ThinkPad T430 2349DS5       | Notebook    | [e6492d37d8](https://linux-hardware.org/?probe=e6492d37d8) | Jun 03, 2023 |
| Alienware     | M15x                        | Notebook    | [4b17185ae7](https://linux-hardware.org/?probe=4b17185ae7) | Jun 03, 2023 |
| Gigabyte      | Z690 AORUS ULTRA            | Desktop     | [50cdb8a60a](https://linux-hardware.org/?probe=50cdb8a60a) | Jun 03, 2023 |
| ASUSTek       | ROG Strix G712LW_G712LW     | Notebook    | [04fdc3c3b8](https://linux-hardware.org/?probe=04fdc3c3b8) | Jun 03, 2023 |
| MSI           | B550M PRO-VDH               | Desktop     | [d09ba05086](https://linux-hardware.org/?probe=d09ba05086) | Jun 03, 2023 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [640faccae0](https://linux-hardware.org/?probe=640faccae0) | Jun 03, 2023 |
| MSI           | B550M PRO-VDH               | Desktop     | [9f13a5184c](https://linux-hardware.org/?probe=9f13a5184c) | Jun 03, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | Desktop     | [4d24b9b7d5](https://linux-hardware.org/?probe=4d24b9b7d5) | Jun 03, 2023 |
| Acer          | Veriton M2631 V:1.0         | Desktop     | [e64369d2ec](https://linux-hardware.org/?probe=e64369d2ec) | Jun 03, 2023 |
| Dell          | Precision 5540              | Notebook    | [f9f2304792](https://linux-hardware.org/?probe=f9f2304792) | Jun 03, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [2378902ae8](https://linux-hardware.org/?probe=2378902ae8) | Jun 03, 2023 |
| Gigabyte      | X79-UP4                     | Desktop     | [e3fd506f5e](https://linux-hardware.org/?probe=e3fd506f5e) | Jun 03, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [64c321d474](https://linux-hardware.org/?probe=64c321d474) | Jun 03, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [7b513e678c](https://linux-hardware.org/?probe=7b513e678c) | Jun 03, 2023 |
| Toshiba       | Satellite C55t-C            | Notebook    | [3b83df3cc9](https://linux-hardware.org/?probe=3b83df3cc9) | Jun 03, 2023 |
| Toshiba       | Satellite L50-C             | Notebook    | [7b1b547b11](https://linux-hardware.org/?probe=7b1b547b11) | Jun 03, 2023 |
| HP            | Laptop 14-bw0xx             | Notebook    | [3958079ad5](https://linux-hardware.org/?probe=3958079ad5) | Jun 03, 2023 |
| Dell          | 0DKKCF A00                  | All in one  | [48c5e3c802](https://linux-hardware.org/?probe=48c5e3c802) | Jun 03, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [8e46a969c7](https://linux-hardware.org/?probe=8e46a969c7) | Jun 03, 2023 |
| Gigabyte      | B550 AORUS MASTER           | Desktop     | [80e9681888](https://linux-hardware.org/?probe=80e9681888) | Jun 03, 2023 |
| Positivo      | POS-EINM70CS POS            | Desktop     | [80260b495c](https://linux-hardware.org/?probe=80260b495c) | Jun 03, 2023 |
| Lenovo        | ThinkPad 11e 5th Gen 20L... | Notebook    | [2f018635f3](https://linux-hardware.org/?probe=2f018635f3) | Jun 03, 2023 |
| MSI           | MPG Z790 EDGE WIFI          | Desktop     | [dae8469b17](https://linux-hardware.org/?probe=dae8469b17) | Jun 02, 2023 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [9a0f40789b](https://linux-hardware.org/?probe=9a0f40789b) | Jun 02, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [f661806559](https://linux-hardware.org/?probe=f661806559) | Jun 02, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [bdad1d1d9e](https://linux-hardware.org/?probe=bdad1d1d9e) | Jun 02, 2023 |
| Dell          | Latitude E5470              | Notebook    | [daa15a6cb0](https://linux-hardware.org/?probe=daa15a6cb0) | Jun 02, 2023 |
| Dell          | Latitude E5470              | Notebook    | [92d3a8b502](https://linux-hardware.org/?probe=92d3a8b502) | Jun 02, 2023 |
| Dell          | Latitude E6410              | Notebook    | [096873c567](https://linux-hardware.org/?probe=096873c567) | Jun 02, 2023 |
| Dell          | Inspiron N4030              | Notebook    | [3c92b81349](https://linux-hardware.org/?probe=3c92b81349) | Jun 02, 2023 |
| Dell          | Inspiron N4030              | Notebook    | [1aca93ba38](https://linux-hardware.org/?probe=1aca93ba38) | Jun 02, 2023 |
| HP            | 2AE5 A01                    | Desktop     | [c37afc3b8a](https://linux-hardware.org/?probe=c37afc3b8a) | Jun 02, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [914fa73266](https://linux-hardware.org/?probe=914fa73266) | Jun 02, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [25721b28d3](https://linux-hardware.org/?probe=25721b28d3) | Jun 02, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [2604bac5a5](https://linux-hardware.org/?probe=2604bac5a5) | Jun 02, 2023 |
| ECS           | Nettle2                     | Desktop     | [6fe297e475](https://linux-hardware.org/?probe=6fe297e475) | Jun 02, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [2cacb34a0d](https://linux-hardware.org/?probe=2cacb34a0d) | Jun 02, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [7a83a98e37](https://linux-hardware.org/?probe=7a83a98e37) | Jun 02, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [f8e0e519ad](https://linux-hardware.org/?probe=f8e0e519ad) | Jun 02, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [a78aee5f7f](https://linux-hardware.org/?probe=a78aee5f7f) | Jun 02, 2023 |
| MSI           | P55-CD53                    | Desktop     | [4f87990649](https://linux-hardware.org/?probe=4f87990649) | Jun 02, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [55c7d4b615](https://linux-hardware.org/?probe=55c7d4b615) | Jun 02, 2023 |
| HP            | 420                         | Notebook    | [0e369b273b](https://linux-hardware.org/?probe=0e369b273b) | Jun 02, 2023 |
| HP            | 1497                        | Desktop     | [9ce66d3e2e](https://linux-hardware.org/?probe=9ce66d3e2e) | Jun 02, 2023 |
| Acer          | Aspire XC-780               | Desktop     | [7789b12750](https://linux-hardware.org/?probe=7789b12750) | Jun 02, 2023 |
| HP            | Split 13 x2 PC              | Notebook    | [5e3ae671cc](https://linux-hardware.org/?probe=5e3ae671cc) | Jun 01, 2023 |
| Apple         | Mac-F2218EA9                | All in one  | [2b3a9c8097](https://linux-hardware.org/?probe=2b3a9c8097) | Jun 01, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [5430a83fca](https://linux-hardware.org/?probe=5430a83fca) | Jun 01, 2023 |
| MSI           | PRO B650-P WIFI             | Desktop     | [53d24a5962](https://linux-hardware.org/?probe=53d24a5962) | Jun 01, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | Desktop     | [e98b2555d7](https://linux-hardware.org/?probe=e98b2555d7) | Jun 01, 2023 |
| MSI           | PRO B650-P WIFI             | Desktop     | [0143308fee](https://linux-hardware.org/?probe=0143308fee) | Jun 01, 2023 |
| MSI           | H81M-E33                    | Desktop     | [50f664d550](https://linux-hardware.org/?probe=50f664d550) | Jun 01, 2023 |
| MSI           | H81M-E33                    | Desktop     | [eb2a33204c](https://linux-hardware.org/?probe=eb2a33204c) | Jun 01, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [97b54068b7](https://linux-hardware.org/?probe=97b54068b7) | Jun 01, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [fe247a0885](https://linux-hardware.org/?probe=fe247a0885) | Jun 01, 2023 |
| Portwell      | CAPB-3000VR                 | Desktop     | [53558af2be](https://linux-hardware.org/?probe=53558af2be) | Jun 01, 2023 |
| ASUSTek       | Z97-P                       | Desktop     | [b819db60d1](https://linux-hardware.org/?probe=b819db60d1) | Jun 01, 2023 |
| Packard Be... | EasyNote TK11BZ             | Notebook    | [b1cbe3b6a6](https://linux-hardware.org/?probe=b1cbe3b6a6) | Jun 01, 2023 |
| HP            | Pavilion dv6600             | Notebook    | [5e2867ee61](https://linux-hardware.org/?probe=5e2867ee61) | Jun 01, 2023 |
| Lenovo        | ThinkPad W510 4391B49       | Notebook    | [1e1004a387](https://linux-hardware.org/?probe=1e1004a387) | Jun 01, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [17621fb846](https://linux-hardware.org/?probe=17621fb846) | Jun 01, 2023 |
| ASUSTek       | N750JV                      | Notebook    | [acc54fe70f](https://linux-hardware.org/?probe=acc54fe70f) | Jun 01, 2023 |
| Gigabyte      | EP45T-DS3                   | Desktop     | [0dd3baa28d](https://linux-hardware.org/?probe=0dd3baa28d) | Jun 01, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [a57949da97](https://linux-hardware.org/?probe=a57949da97) | Jun 01, 2023 |
| ASUSTek       | M3A78-T                     | Desktop     | [e59673dcf2](https://linux-hardware.org/?probe=e59673dcf2) | Jun 01, 2023 |
| Lenovo        | V17 G3 IAP 82U1             | Notebook    | [1be071e25d](https://linux-hardware.org/?probe=1be071e25d) | May 31, 2023 |
| HP            | 1497                        | Desktop     | [cc138de04b](https://linux-hardware.org/?probe=cc138de04b) | May 31, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [58b09c521b](https://linux-hardware.org/?probe=58b09c521b) | May 31, 2023 |
| ASRock        | H81M-HDS R2.0               | Desktop     | [810f6b35ea](https://linux-hardware.org/?probe=810f6b35ea) | May 31, 2023 |
| Sony          | SVT1121B2EW                 | Notebook    | [67819a243c](https://linux-hardware.org/?probe=67819a243c) | May 31, 2023 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [2bb50cdcc7](https://linux-hardware.org/?probe=2bb50cdcc7) | May 31, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [f168bc9d53](https://linux-hardware.org/?probe=f168bc9d53) | May 31, 2023 |
| ECS           | A890GXM-A2                  | Desktop     | [c207b5f41c](https://linux-hardware.org/?probe=c207b5f41c) | May 31, 2023 |
| Fujitsu Si... | D2811-A1 S26361-D2811-A1    | Desktop     | [c0ff761729](https://linux-hardware.org/?probe=c0ff761729) | May 31, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [f93dd394e8](https://linux-hardware.org/?probe=f93dd394e8) | May 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [1ea9c869ff](https://linux-hardware.org/?probe=1ea9c869ff) | May 31, 2023 |
| Apple         | Mac-F2268DC8                | All in one  | [ecc39bf44b](https://linux-hardware.org/?probe=ecc39bf44b) | May 31, 2023 |
| HP            | 158A                        | Desktop     | [39d4ab7307](https://linux-hardware.org/?probe=39d4ab7307) | May 31, 2023 |
| Toshiba       | Satellite C645D             | Notebook    | [dc642a7011](https://linux-hardware.org/?probe=dc642a7011) | May 31, 2023 |
| Toshiba       | Satellite C645D             | Notebook    | [32407daaa6](https://linux-hardware.org/?probe=32407daaa6) | May 31, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d1f02a3055](https://linux-hardware.org/?probe=d1f02a3055) | May 31, 2023 |
| Google        | Bobba                       | Notebook    | [d47a75a3aa](https://linux-hardware.org/?probe=d47a75a3aa) | May 31, 2023 |
| HP            | 8648                        | Desktop     | [11e777087a](https://linux-hardware.org/?probe=11e777087a) | May 31, 2023 |
| Google        | Bobba                       | Notebook    | [9e2c41879c](https://linux-hardware.org/?probe=9e2c41879c) | May 31, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [1b457302ec](https://linux-hardware.org/?probe=1b457302ec) | May 31, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [b4b6bfda0c](https://linux-hardware.org/?probe=b4b6bfda0c) | May 31, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [9d3023fd1d](https://linux-hardware.org/?probe=9d3023fd1d) | May 31, 2023 |
| Acer          | E5-551G-871W                | Notebook    | [8034a1ee0b](https://linux-hardware.org/?probe=8034a1ee0b) | May 30, 2023 |
| ASRock        | Q1900B-ITX                  | Desktop     | [88e4924fa2](https://linux-hardware.org/?probe=88e4924fa2) | May 30, 2023 |
| Fujitsu       | LIFEBOOK T936               | Convertible | [fefb17a829](https://linux-hardware.org/?probe=fefb17a829) | May 30, 2023 |
| Samsung       | R610                        | Notebook    | [4e3be533ba](https://linux-hardware.org/?probe=4e3be533ba) | May 30, 2023 |
| Acer          | Aspire 5749                 | Notebook    | [3bca2af88d](https://linux-hardware.org/?probe=3bca2af88d) | May 30, 2023 |
| Gigabyte      | Z97-HD3                     | Desktop     | [8505864d45](https://linux-hardware.org/?probe=8505864d45) | May 30, 2023 |
| Toshiba       | Satellite R630              | Notebook    | [5bf801ac1f](https://linux-hardware.org/?probe=5bf801ac1f) | May 30, 2023 |
| HP            | ENVY 15                     | Notebook    | [ad3cf182fe](https://linux-hardware.org/?probe=ad3cf182fe) | May 30, 2023 |
| Biostar       | B450MH                      | Desktop     | [36947ca7e1](https://linux-hardware.org/?probe=36947ca7e1) | May 30, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [6bec5a03df](https://linux-hardware.org/?probe=6bec5a03df) | May 30, 2023 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [e51651a755](https://linux-hardware.org/?probe=e51651a755) | May 30, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [dc6256036e](https://linux-hardware.org/?probe=dc6256036e) | May 30, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [c2d144c313](https://linux-hardware.org/?probe=c2d144c313) | May 30, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [4d7ccd868f](https://linux-hardware.org/?probe=4d7ccd868f) | May 30, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [24775c04a5](https://linux-hardware.org/?probe=24775c04a5) | May 30, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [d6a2216b0f](https://linux-hardware.org/?probe=d6a2216b0f) | May 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [7653baa0f8](https://linux-hardware.org/?probe=7653baa0f8) | May 30, 2023 |
| Dell          | Latitude 5400               | Notebook    | [fb192b5416](https://linux-hardware.org/?probe=fb192b5416) | May 30, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [e9830d0123](https://linux-hardware.org/?probe=e9830d0123) | May 29, 2023 |
| Dell          | Latitude 5400               | Notebook    | [838b2db21b](https://linux-hardware.org/?probe=838b2db21b) | May 29, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [4679a6e565](https://linux-hardware.org/?probe=4679a6e565) | May 29, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [ec89dcb694](https://linux-hardware.org/?probe=ec89dcb694) | May 29, 2023 |
| MSI           | Z170A MPOWER GAMING TITA... | Desktop     | [0e9239c5f7](https://linux-hardware.org/?probe=0e9239c5f7) | May 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [89bb5ff663](https://linux-hardware.org/?probe=89bb5ff663) | May 29, 2023 |
| MSI           | 970A-G46                    | Desktop     | [180eb351d7](https://linux-hardware.org/?probe=180eb351d7) | May 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [9fce8d1e40](https://linux-hardware.org/?probe=9fce8d1e40) | May 29, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [e947dd7da1](https://linux-hardware.org/?probe=e947dd7da1) | May 29, 2023 |
| Acer          | Aspire ES1-571              | Notebook    | [6f75ba50c1](https://linux-hardware.org/?probe=6f75ba50c1) | May 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [04e1a849d0](https://linux-hardware.org/?probe=04e1a849d0) | May 29, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [f4a8ca4825](https://linux-hardware.org/?probe=f4a8ca4825) | May 29, 2023 |
| ASUSTek       | X550LD                      | Notebook    | [e091c09373](https://linux-hardware.org/?probe=e091c09373) | May 29, 2023 |
| GPU Compan... | GWTC116-2                   | Notebook    | [075486801a](https://linux-hardware.org/?probe=075486801a) | May 29, 2023 |
| Fujitsu       | CELSIUS H720                | Notebook    | [d7d19435c2](https://linux-hardware.org/?probe=d7d19435c2) | May 29, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [5ac36928a5](https://linux-hardware.org/?probe=5ac36928a5) | May 28, 2023 |
| Lenovo        | MIIX 300-10IBY 80NR         | Tablet      | [92b569d076](https://linux-hardware.org/?probe=92b569d076) | May 28, 2023 |
| ASUSTek       | H81M-R                      | Desktop     | [1a69603cc6](https://linux-hardware.org/?probe=1a69603cc6) | May 28, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [cf1c884051](https://linux-hardware.org/?probe=cf1c884051) | May 28, 2023 |
| Pegatron      | NARRA3                      | Desktop     | [5c016d4faf](https://linux-hardware.org/?probe=5c016d4faf) | May 28, 2023 |
| Acer          | Aspire ES1-571              | Notebook    | [a3da42e0e9](https://linux-hardware.org/?probe=a3da42e0e9) | May 28, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [22cbc01649](https://linux-hardware.org/?probe=22cbc01649) | May 28, 2023 |
| HP            | Compaq 6730s                | Notebook    | [fe2b8b63ac](https://linux-hardware.org/?probe=fe2b8b63ac) | May 28, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [6b863cd4a3](https://linux-hardware.org/?probe=6b863cd4a3) | May 28, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [8fe1188fd8](https://linux-hardware.org/?probe=8fe1188fd8) | May 28, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [b5aa372117](https://linux-hardware.org/?probe=b5aa372117) | May 28, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [993b013d0a](https://linux-hardware.org/?probe=993b013d0a) | May 28, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [8d008658ce](https://linux-hardware.org/?probe=8d008658ce) | May 28, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [e2e38da09f](https://linux-hardware.org/?probe=e2e38da09f) | May 28, 2023 |
| ASUSTek       | ROG Strix G713RW_G713RW     | Notebook    | [ef1ea73723](https://linux-hardware.org/?probe=ef1ea73723) | May 27, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [6465343084](https://linux-hardware.org/?probe=6465343084) | May 27, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [cb238efd5e](https://linux-hardware.org/?probe=cb238efd5e) | May 27, 2023 |
| Acer          | TravelMate 5735Z            | Notebook    | [9eea76e3ee](https://linux-hardware.org/?probe=9eea76e3ee) | May 27, 2023 |
| Wortmann      | CR700                       | Notebook    | [189f1ae92b](https://linux-hardware.org/?probe=189f1ae92b) | May 27, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [741e0e805b](https://linux-hardware.org/?probe=741e0e805b) | May 27, 2023 |
| HP            | 15                          | Notebook    | [f5373f2397](https://linux-hardware.org/?probe=f5373f2397) | May 27, 2023 |
| Acer          | Aspire ES1-571              | Notebook    | [029ea88e3b](https://linux-hardware.org/?probe=029ea88e3b) | May 27, 2023 |
| HP            | 15                          | Notebook    | [f30c3b3a95](https://linux-hardware.org/?probe=f30c3b3a95) | May 27, 2023 |
| Apple         | MacBookPro15,4              | Notebook    | [9ee2d1266b](https://linux-hardware.org/?probe=9ee2d1266b) | May 27, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [0149ec9c81](https://linux-hardware.org/?probe=0149ec9c81) | May 27, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [9984b363d1](https://linux-hardware.org/?probe=9984b363d1) | May 27, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | Desktop     | [7284c23b76](https://linux-hardware.org/?probe=7284c23b76) | May 27, 2023 |
| Lenovo        | 3716 SDK0T76461 WIN 3422... | Desktop     | [2f3952dcfe](https://linux-hardware.org/?probe=2f3952dcfe) | May 27, 2023 |
| ASUSTek       | H81M-R                      | Desktop     | [8edf21a203](https://linux-hardware.org/?probe=8edf21a203) | May 27, 2023 |
| PCChips       | P17G ECS                    | Desktop     | [0518fce589](https://linux-hardware.org/?probe=0518fce589) | May 27, 2023 |
| ASUSTek       | M4A785-M                    | Desktop     | [ff2e86c530](https://linux-hardware.org/?probe=ff2e86c530) | May 27, 2023 |
| Samsung       | 270E5G/270E5U               | Notebook    | [affdf49716](https://linux-hardware.org/?probe=affdf49716) | May 27, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [0577b02521](https://linux-hardware.org/?probe=0577b02521) | May 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [efe0b55153](https://linux-hardware.org/?probe=efe0b55153) | May 27, 2023 |
| Lenovo        | ThinkPad L512 44473HU       | Notebook    | [f9a27ab76b](https://linux-hardware.org/?probe=f9a27ab76b) | May 27, 2023 |
| Samsung       | 270E5G/270E5U               | Notebook    | [106bd355da](https://linux-hardware.org/?probe=106bd355da) | May 27, 2023 |
| Positivo      | C14CR21TV                   | Notebook    | [f3907d940d](https://linux-hardware.org/?probe=f3907d940d) | May 27, 2023 |
| Lenovo        | 3716 SDK0R32862 WIN 3258... | Desktop     | [d3137742ae](https://linux-hardware.org/?probe=d3137742ae) | May 27, 2023 |
| HP            | 81B9 1000                   | All in one  | [55380f30ca](https://linux-hardware.org/?probe=55380f30ca) | May 27, 2023 |
| HP            | 1000                        | Notebook    | [f3b014fa71](https://linux-hardware.org/?probe=f3b014fa71) | May 27, 2023 |
| Lenovo        | Unknown                     | Notebook    | [dbf5c576b2](https://linux-hardware.org/?probe=dbf5c576b2) | May 27, 2023 |
| Dell          | Latitude 5430               | Notebook    | [a0697218cc](https://linux-hardware.org/?probe=a0697218cc) | May 27, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [0d8c590c8d](https://linux-hardware.org/?probe=0d8c590c8d) | May 27, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [0f593c947e](https://linux-hardware.org/?probe=0f593c947e) | May 27, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [e7a8d68439](https://linux-hardware.org/?probe=e7a8d68439) | May 27, 2023 |
| HP            | Pavilion dm4                | Notebook    | [708daa02e2](https://linux-hardware.org/?probe=708daa02e2) | May 26, 2023 |
| Dell          | 0TP406                      | Desktop     | [c7300f35f4](https://linux-hardware.org/?probe=c7300f35f4) | May 26, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [4662e37743](https://linux-hardware.org/?probe=4662e37743) | May 26, 2023 |
| MSI           | B550M PRO-VDH               | Desktop     | [f7fddb36e8](https://linux-hardware.org/?probe=f7fddb36e8) | May 26, 2023 |
| MSI           | CX700                       | Notebook    | [ecb1aaf9c1](https://linux-hardware.org/?probe=ecb1aaf9c1) | May 26, 2023 |
| Intel         | NUC5i5RYB H40999-502        | Mini pc     | [c008c6243e](https://linux-hardware.org/?probe=c008c6243e) | May 26, 2023 |
| Compumax C... | ONIX-CEL-0001               | Notebook    | [2f5d8e6789](https://linux-hardware.org/?probe=2f5d8e6789) | May 26, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [1cbedc352f](https://linux-hardware.org/?probe=1cbedc352f) | May 26, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [6bcf3cf056](https://linux-hardware.org/?probe=6bcf3cf056) | May 26, 2023 |
| HP            | ZBook Firefly 15 G7 Mobi... | Notebook    | [1b3b8c1912](https://linux-hardware.org/?probe=1b3b8c1912) | May 26, 2023 |
| Lenovo        | ThinkPad P51 20HJS01Q04     | Notebook    | [520eb0074c](https://linux-hardware.org/?probe=520eb0074c) | May 26, 2023 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | Notebook    | [8558865a17](https://linux-hardware.org/?probe=8558865a17) | May 26, 2023 |
| Lenovo        | ThinkPad T450 20BUS06B00    | Notebook    | [d86873ceab](https://linux-hardware.org/?probe=d86873ceab) | May 26, 2023 |
| Itautec       | Infoway                     | Notebook    | [03be6afc10](https://linux-hardware.org/?probe=03be6afc10) | May 26, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [0796332e87](https://linux-hardware.org/?probe=0796332e87) | May 26, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [40af2d79f9](https://linux-hardware.org/?probe=40af2d79f9) | May 26, 2023 |
| Dell          | Latitude 7400               | Notebook    | [11ee0dea04](https://linux-hardware.org/?probe=11ee0dea04) | May 26, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [9723f3e325](https://linux-hardware.org/?probe=9723f3e325) | May 26, 2023 |
| LG Electro... | V720                        | All in one  | [5dbe7c937c](https://linux-hardware.org/?probe=5dbe7c937c) | May 26, 2023 |
| Intel Clie... | LAPBC710                    | Notebook    | [7ed6d7079c](https://linux-hardware.org/?probe=7ed6d7079c) | May 26, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [b6d4eff333](https://linux-hardware.org/?probe=b6d4eff333) | May 26, 2023 |
| Acer          | TravelMate 6292             | Notebook    | [0a4cb3e4b3](https://linux-hardware.org/?probe=0a4cb3e4b3) | May 25, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [baae1e4c8b](https://linux-hardware.org/?probe=baae1e4c8b) | May 25, 2023 |
| Sony          | SVF1521B4E                  | Notebook    | [d6eaf68ef4](https://linux-hardware.org/?probe=d6eaf68ef4) | May 25, 2023 |
| Acer          | Aspire A515-54G             | Notebook    | [a6c2011fb0](https://linux-hardware.org/?probe=a6c2011fb0) | May 25, 2023 |
| Sony          | SVF1521B4E                  | Notebook    | [03c5deb4cc](https://linux-hardware.org/?probe=03c5deb4cc) | May 25, 2023 |
| Acer          | Aspire V3-371               | Notebook    | [f9200e891b](https://linux-hardware.org/?probe=f9200e891b) | May 25, 2023 |
| Acer          | Aspire A515-54G             | Notebook    | [e58d4b4aee](https://linux-hardware.org/?probe=e58d4b4aee) | May 25, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [53db1863ab](https://linux-hardware.org/?probe=53db1863ab) | May 25, 2023 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [6e2419fcbf](https://linux-hardware.org/?probe=6e2419fcbf) | May 25, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [3f7beed595](https://linux-hardware.org/?probe=3f7beed595) | May 25, 2023 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [a88cd7c5a6](https://linux-hardware.org/?probe=a88cd7c5a6) | May 25, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [d72352c0dc](https://linux-hardware.org/?probe=d72352c0dc) | May 25, 2023 |
| Dell          | Latitude D630               | Notebook    | [ac84af2a69](https://linux-hardware.org/?probe=ac84af2a69) | May 25, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [a764ae9f3c](https://linux-hardware.org/?probe=a764ae9f3c) | May 25, 2023 |
| Wortmann      | 1220552_1470050             | Tablet      | [5717e92355](https://linux-hardware.org/?probe=5717e92355) | May 25, 2023 |
| Compal        | JHL90 REFERENCE             | Notebook    | [0c115d29f3](https://linux-hardware.org/?probe=0c115d29f3) | May 25, 2023 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | Desktop     | [769f5c0d23](https://linux-hardware.org/?probe=769f5c0d23) | May 25, 2023 |
| Dell          | Latitude 3330               | Notebook    | [a4c33168fa](https://linux-hardware.org/?probe=a4c33168fa) | May 25, 2023 |
| HP            | 21D0                        | Desktop     | [4cac4f8654](https://linux-hardware.org/?probe=4cac4f8654) | May 25, 2023 |
| HP            | 21D0                        | Desktop     | [589c780060](https://linux-hardware.org/?probe=589c780060) | May 25, 2023 |
| Biostar       | A68MHE                      | Desktop     | [d1ef52da36](https://linux-hardware.org/?probe=d1ef52da36) | May 25, 2023 |
| PHILCO ELE... | PNB15.6AP34H1W10            | Notebook    | [dc91cb92af](https://linux-hardware.org/?probe=dc91cb92af) | May 25, 2023 |
| Biostar       | A68MHE                      | Desktop     | [e2244a8ed0](https://linux-hardware.org/?probe=e2244a8ed0) | May 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [ab42ac444e](https://linux-hardware.org/?probe=ab42ac444e) | May 24, 2023 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [0c7493d8d3](https://linux-hardware.org/?probe=0c7493d8d3) | May 24, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [9fbeb26e54](https://linux-hardware.org/?probe=9fbeb26e54) | May 24, 2023 |
| Lenovo        | ThinkPad T431s 20ACA01V0... | Notebook    | [253f7d5359](https://linux-hardware.org/?probe=253f7d5359) | May 24, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [1523787171](https://linux-hardware.org/?probe=1523787171) | May 24, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [89d040ffaf](https://linux-hardware.org/?probe=89d040ffaf) | May 24, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [ddfad3653a](https://linux-hardware.org/?probe=ddfad3653a) | May 24, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [0a2dc161fe](https://linux-hardware.org/?probe=0a2dc161fe) | May 24, 2023 |
| ASUSTek       | ROG STRIX X399-E GAMING     | Desktop     | [647a30ff09](https://linux-hardware.org/?probe=647a30ff09) | May 24, 2023 |
| Dell          | Latitude D630               | Notebook    | [9e4709b942](https://linux-hardware.org/?probe=9e4709b942) | May 24, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [24e9acec30](https://linux-hardware.org/?probe=24e9acec30) | May 24, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [f77697fdd0](https://linux-hardware.org/?probe=f77697fdd0) | May 24, 2023 |
| Dell          | Precision 5570              | Notebook    | [f014c35d45](https://linux-hardware.org/?probe=f014c35d45) | May 24, 2023 |
| Acer          | Aspire V3-731               | Notebook    | [d07d017c32](https://linux-hardware.org/?probe=d07d017c32) | May 24, 2023 |
| ASRock        | B85M-HDS                    | Desktop     | [fc128a2474](https://linux-hardware.org/?probe=fc128a2474) | May 24, 2023 |
| IX1401        | Unknown                     | Notebook    | [f1799b6c3a](https://linux-hardware.org/?probe=f1799b6c3a) | May 24, 2023 |
| DEXP          | Aquilon C14                 | Notebook    | [357a7caaf8](https://linux-hardware.org/?probe=357a7caaf8) | May 24, 2023 |
| DEXP          | Aquilon C14                 | Notebook    | [cd3dc35687](https://linux-hardware.org/?probe=cd3dc35687) | May 24, 2023 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | Desktop     | [3a26097c6a](https://linux-hardware.org/?probe=3a26097c6a) | May 24, 2023 |
| Lenovo        | ThinkPad T410 2537AT1       | Notebook    | [babbb757c6](https://linux-hardware.org/?probe=babbb757c6) | May 24, 2023 |
| Acer          | Aspire E5-571G              | Notebook    | [6531b22151](https://linux-hardware.org/?probe=6531b22151) | May 24, 2023 |
| ASUSTek       | K73BR                       | Notebook    | [2b59c4c84c](https://linux-hardware.org/?probe=2b59c4c84c) | May 24, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [deff44e62e](https://linux-hardware.org/?probe=deff44e62e) | May 24, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | Notebook    | [e8bc14fc34](https://linux-hardware.org/?probe=e8bc14fc34) | May 23, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | Notebook    | [c5615351bb](https://linux-hardware.org/?probe=c5615351bb) | May 23, 2023 |
| HP            | Laptop 17-by3xxx            | Notebook    | [dcafbb2a69](https://linux-hardware.org/?probe=dcafbb2a69) | May 23, 2023 |
| HP            | Laptop 17-by3xxx            | Notebook    | [cbe27885cb](https://linux-hardware.org/?probe=cbe27885cb) | May 23, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [2bed616680](https://linux-hardware.org/?probe=2bed616680) | May 23, 2023 |
| ASRock        | AB350M Pro4                 | Desktop     | [9f7d80df58](https://linux-hardware.org/?probe=9f7d80df58) | May 23, 2023 |
| ASUSTek       | ROG STRIX X399-E GAMING     | Desktop     | [fcefb35b05](https://linux-hardware.org/?probe=fcefb35b05) | May 23, 2023 |
| Unknown       | Unknown                     | Notebook    | [da302bee4e](https://linux-hardware.org/?probe=da302bee4e) | May 23, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | Notebook    | [2cf9c98869](https://linux-hardware.org/?probe=2cf9c98869) | May 23, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | Notebook    | [4da667cc7e](https://linux-hardware.org/?probe=4da667cc7e) | May 23, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [52b95d45ca](https://linux-hardware.org/?probe=52b95d45ca) | May 23, 2023 |
| Lenovo        | ThinkPad X250 20CLS65E00    | Notebook    | [e65932f3a9](https://linux-hardware.org/?probe=e65932f3a9) | May 23, 2023 |
| Acer          | Aspire A515-54              | Notebook    | [8db69494ad](https://linux-hardware.org/?probe=8db69494ad) | May 23, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [49bd7863b7](https://linux-hardware.org/?probe=49bd7863b7) | May 23, 2023 |
| Lenovo        | ThinkPad E460 20ETCTO1WW    | Notebook    | [cd2c3fbd45](https://linux-hardware.org/?probe=cd2c3fbd45) | May 23, 2023 |
| Gigabyte      | A320M-S2H-CF SE1            | Desktop     | [61ede8f95d](https://linux-hardware.org/?probe=61ede8f95d) | May 23, 2023 |
| HP            | Notebook                    | Notebook    | [6e7c128799](https://linux-hardware.org/?probe=6e7c128799) | May 23, 2023 |
| ASUSTek       | TUF X299 MARK 1             | Desktop     | [89b378457d](https://linux-hardware.org/?probe=89b378457d) | May 23, 2023 |
| Matsushita... | CF-W7BWAYZL3                | Notebook    | [a00f38be95](https://linux-hardware.org/?probe=a00f38be95) | May 23, 2023 |
| Sony          | SVE1513Q1ESI                | Notebook    | [eef57d6c26](https://linux-hardware.org/?probe=eef57d6c26) | May 23, 2023 |
| HP            | 1495                        | Desktop     | [200cab3da9](https://linux-hardware.org/?probe=200cab3da9) | May 23, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [785f4bad86](https://linux-hardware.org/?probe=785f4bad86) | May 23, 2023 |
| Medion        | E6224                       | Notebook    | [65c26a4a09](https://linux-hardware.org/?probe=65c26a4a09) | May 23, 2023 |
| Medion        | E6224                       | Notebook    | [8e10b22b1f](https://linux-hardware.org/?probe=8e10b22b1f) | May 23, 2023 |
| ASUSTek       | TUF X299 MARK 1             | Desktop     | [2f194363a7](https://linux-hardware.org/?probe=2f194363a7) | May 23, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [1ec3710265](https://linux-hardware.org/?probe=1ec3710265) | May 23, 2023 |
| HP            | 158Ch                       | Mini pc     | [436915ebe8](https://linux-hardware.org/?probe=436915ebe8) | May 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [de52b8f296](https://linux-hardware.org/?probe=de52b8f296) | May 22, 2023 |
| Dell          | Latitude 7490               | Notebook    | [f689b559e8](https://linux-hardware.org/?probe=f689b559e8) | May 22, 2023 |
| Acer          | Aspire V3-371               | Notebook    | [c6276aaa0c](https://linux-hardware.org/?probe=c6276aaa0c) | May 22, 2023 |
| ASUSTek       | Zenbook UM6702RA_RM6702R... | Notebook    | [03e6dd8808](https://linux-hardware.org/?probe=03e6dd8808) | May 22, 2023 |
| MSI           | MS-7A66                     | Desktop     | [9be9117e62](https://linux-hardware.org/?probe=9be9117e62) | May 22, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [0a952bd502](https://linux-hardware.org/?probe=0a952bd502) | May 22, 2023 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [3c708a54f5](https://linux-hardware.org/?probe=3c708a54f5) | May 22, 2023 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [692ba9d18f](https://linux-hardware.org/?probe=692ba9d18f) | May 22, 2023 |
| Lenovo        | 36C8 SDK0J40700 WIN 3258... | Desktop     | [7e8b42ab5f](https://linux-hardware.org/?probe=7e8b42ab5f) | May 22, 2023 |
| Acer          | Extensa 5635Z               | Notebook    | [dcff2c30c6](https://linux-hardware.org/?probe=dcff2c30c6) | May 22, 2023 |
| MSI           | B360M PRO-VDH               | Desktop     | [93a41eca5e](https://linux-hardware.org/?probe=93a41eca5e) | May 22, 2023 |
| Dell          | Inspiron 3443               | Notebook    | [35923f74b5](https://linux-hardware.org/?probe=35923f74b5) | May 22, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [b3fb445705](https://linux-hardware.org/?probe=b3fb445705) | May 22, 2023 |
| Pegatron      | Benicia                     | Desktop     | [bcfa2151fc](https://linux-hardware.org/?probe=bcfa2151fc) | May 22, 2023 |
| MSI           | 760GMA-P34                  | Desktop     | [de97b76fed](https://linux-hardware.org/?probe=de97b76fed) | May 22, 2023 |
| Lenovo        | ThinkPad X230 2325AC2       | Notebook    | [bc1633cf27](https://linux-hardware.org/?probe=bc1633cf27) | May 22, 2023 |
| Lenovo        | Unknown                     | Notebook    | [563922ce1c](https://linux-hardware.org/?probe=563922ce1c) | May 22, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [0148c19bc7](https://linux-hardware.org/?probe=0148c19bc7) | May 22, 2023 |
| Alienware     | 0H869M A00                  | Desktop     | [0bac54e4b2](https://linux-hardware.org/?probe=0bac54e4b2) | May 22, 2023 |
| HP            | 805D                        | Desktop     | [2ac4992bcd](https://linux-hardware.org/?probe=2ac4992bcd) | May 22, 2023 |
| Acer          | Aspire E1-470P              | Notebook    | [aecff3f4a9](https://linux-hardware.org/?probe=aecff3f4a9) | May 21, 2023 |
| Acer          | Aspire E5-571P              | Notebook    | [7130cf8b4e](https://linux-hardware.org/?probe=7130cf8b4e) | May 21, 2023 |
| Dell          | Inspiron 5402               | Notebook    | [0bc344e305](https://linux-hardware.org/?probe=0bc344e305) | May 21, 2023 |
| Lenovo        | ThinkPad T410 2537V32       | Notebook    | [cece14e931](https://linux-hardware.org/?probe=cece14e931) | May 21, 2023 |
| HP            | 2B5E                        | Desktop     | [a221629f4d](https://linux-hardware.org/?probe=a221629f4d) | May 21, 2023 |
| Acer          | Aspire A515-52G             | Notebook    | [a80648e2a4](https://linux-hardware.org/?probe=a80648e2a4) | May 21, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [03b17bc271](https://linux-hardware.org/?probe=03b17bc271) | May 21, 2023 |
| Acer          | Aspire V5-572P              | Notebook    | [99f4730d26](https://linux-hardware.org/?probe=99f4730d26) | May 21, 2023 |
| Sony          | SVF1521B4E                  | Notebook    | [89c04d3b34](https://linux-hardware.org/?probe=89c04d3b34) | May 21, 2023 |
| MSI           | B550M PRO-VDH               | Desktop     | [3f5a6968d4](https://linux-hardware.org/?probe=3f5a6968d4) | May 21, 2023 |
| HP            | Unknown                     | Notebook    | [8894bf0f31](https://linux-hardware.org/?probe=8894bf0f31) | May 21, 2023 |
| Gigabyte      | GA-78LMT-S2PT               | Desktop     | [04ea462ce6](https://linux-hardware.org/?probe=04ea462ce6) | May 21, 2023 |
| Lenovo        | 316E NOK                    | Mini pc     | [019a851aeb](https://linux-hardware.org/?probe=019a851aeb) | May 21, 2023 |
| ASRock        | 775Dual-VSTA                | Desktop     | [2eb8cdff34](https://linux-hardware.org/?probe=2eb8cdff34) | May 21, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b344b7ea03](https://linux-hardware.org/?probe=b344b7ea03) | May 21, 2023 |
| Apple         | MacBookPro15,1              | Notebook    | [438d9b5e18](https://linux-hardware.org/?probe=438d9b5e18) | May 21, 2023 |
| Sony          | VPCEL36FJ                   | Notebook    | [c372bac204](https://linux-hardware.org/?probe=c372bac204) | May 21, 2023 |
| Lenovo        | MIIX 300-10IBY 80NR         | Tablet      | [f7d7036598](https://linux-hardware.org/?probe=f7d7036598) | May 21, 2023 |
| Acer          | Aspire V5-572P              | Notebook    | [456d6c8887](https://linux-hardware.org/?probe=456d6c8887) | May 21, 2023 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [8dcb326301](https://linux-hardware.org/?probe=8dcb326301) | May 21, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [71a87fa176](https://linux-hardware.org/?probe=71a87fa176) | May 20, 2023 |
| ASRock        | H670M Pro RS                | Desktop     | [5e17710256](https://linux-hardware.org/?probe=5e17710256) | May 20, 2023 |
| ASRock        | H670M Pro RS                | Desktop     | [d217d78446](https://linux-hardware.org/?probe=d217d78446) | May 20, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [7687732509](https://linux-hardware.org/?probe=7687732509) | May 20, 2023 |
| ASUSTek       | EB1035                      | All in one  | [ec3d9bc454](https://linux-hardware.org/?probe=ec3d9bc454) | May 20, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [ec1357e74e](https://linux-hardware.org/?probe=ec1357e74e) | May 20, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [7aef6229db](https://linux-hardware.org/?probe=7aef6229db) | May 20, 2023 |
| Alienware     | 17 R4                       | Notebook    | [c928d1557b](https://linux-hardware.org/?probe=c928d1557b) | May 20, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [87e60904b9](https://linux-hardware.org/?probe=87e60904b9) | May 20, 2023 |
| Toshiba       | Satellite C870-1FZ          | Notebook    | [1f2563578e](https://linux-hardware.org/?probe=1f2563578e) | May 20, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [f0eaf024c8](https://linux-hardware.org/?probe=f0eaf024c8) | May 20, 2023 |
| HP            | Compaq 6730s                | Notebook    | [632961079b](https://linux-hardware.org/?probe=632961079b) | May 20, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [0c87a87d33](https://linux-hardware.org/?probe=0c87a87d33) | May 20, 2023 |
| Sony          | VPCSB35FG                   | Notebook    | [81d2592989](https://linux-hardware.org/?probe=81d2592989) | May 20, 2023 |
| Sony          | VPCSB35FG                   | Notebook    | [828fb24994](https://linux-hardware.org/?probe=828fb24994) | May 20, 2023 |
| Packard Be... | EasyNote MH36               | Notebook    | [a77cfa4947](https://linux-hardware.org/?probe=a77cfa4947) | May 20, 2023 |
| Foxconn       | 2A92                        | Desktop     | [225fee02ae](https://linux-hardware.org/?probe=225fee02ae) | May 20, 2023 |
| Gigabyte      | EP45T-UD3R                  | Desktop     | [848d0db1b2](https://linux-hardware.org/?probe=848d0db1b2) | May 19, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U7S... | Notebook    | [2e78e77fef](https://linux-hardware.org/?probe=2e78e77fef) | May 19, 2023 |
| Eii           | WSA116                      | Notebook    | [cff66832fd](https://linux-hardware.org/?probe=cff66832fd) | May 19, 2023 |
| HP            | Notebook                    | Notebook    | [3664846c35](https://linux-hardware.org/?probe=3664846c35) | May 19, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [b07192ce16](https://linux-hardware.org/?probe=b07192ce16) | May 19, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B2402CBA... | Notebook    | [13d783ec86](https://linux-hardware.org/?probe=13d783ec86) | May 19, 2023 |
| Dell          | Inspiron 7586               | Convertible | [f4aaec3fda](https://linux-hardware.org/?probe=f4aaec3fda) | May 19, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [6d6cdfc735](https://linux-hardware.org/?probe=6d6cdfc735) | May 19, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [3de00073ba](https://linux-hardware.org/?probe=3de00073ba) | May 19, 2023 |
| HP            | 21B4 A01                    | Desktop     | [b57059fe59](https://linux-hardware.org/?probe=b57059fe59) | May 19, 2023 |
| Unknown       | V00                         | Mini pc     | [3abd6900c9](https://linux-hardware.org/?probe=3abd6900c9) | May 19, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [76a17acffb](https://linux-hardware.org/?probe=76a17acffb) | May 19, 2023 |
| Microsoft     | Surface Pro 8               | Tablet      | [8f2c1d7d81](https://linux-hardware.org/?probe=8f2c1d7d81) | May 19, 2023 |
| Lenovo        | C205                        | All in one  | [16ecd2d81d](https://linux-hardware.org/?probe=16ecd2d81d) | May 19, 2023 |
| Lenovo        | C205                        | All in one  | [dfb0b6c8f3](https://linux-hardware.org/?probe=dfb0b6c8f3) | May 19, 2023 |
| ASRock        | Z77 Extreme4                | Desktop     | [2ecf8b48ab](https://linux-hardware.org/?probe=2ecf8b48ab) | May 19, 2023 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [c1f8fc5eed](https://linux-hardware.org/?probe=c1f8fc5eed) | May 19, 2023 |
| Dell          | 0KWVT8 A01                  | Desktop     | [2159a4cc95](https://linux-hardware.org/?probe=2159a4cc95) | May 18, 2023 |
| ASUSTek       | P5B                         | Desktop     | [9d815bcd44](https://linux-hardware.org/?probe=9d815bcd44) | May 18, 2023 |
| ASUSTek       | P5B                         | Desktop     | [70be41e795](https://linux-hardware.org/?probe=70be41e795) | May 18, 2023 |
| Lenovo        | ThinkPad T400 2767E53       | Notebook    | [5cd6c87b7e](https://linux-hardware.org/?probe=5cd6c87b7e) | May 18, 2023 |
| ASUSTek       | PRIME B460-PLUS             | Desktop     | [97149ea35b](https://linux-hardware.org/?probe=97149ea35b) | May 18, 2023 |
| Megaware      | MW-H61M-2H v1.3 - 17/07/... | Desktop     | [72303201a3](https://linux-hardware.org/?probe=72303201a3) | May 18, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [ca3fda27b5](https://linux-hardware.org/?probe=ca3fda27b5) | May 18, 2023 |
| Lenovo        | ThinkPad T490s 20NXS01Y0... | Notebook    | [277ed003ce](https://linux-hardware.org/?probe=277ed003ce) | May 18, 2023 |
| HP            | EliteBook 745 G4            | Notebook    | [7c6154717b](https://linux-hardware.org/?probe=7c6154717b) | May 18, 2023 |
| HP            | Laptop 14s-dq0xxx           | Notebook    | [6173aa2164](https://linux-hardware.org/?probe=6173aa2164) | May 18, 2023 |
| HP            | Stream Notebook PC 14       | Notebook    | [835c46e8e2](https://linux-hardware.org/?probe=835c46e8e2) | May 18, 2023 |
| Acer          | Veriton M2610G              | Desktop     | [001e547ddf](https://linux-hardware.org/?probe=001e547ddf) | May 18, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [c9f5da779c](https://linux-hardware.org/?probe=c9f5da779c) | May 18, 2023 |
| HP            | 3398                        | Desktop     | [a49cbc797b](https://linux-hardware.org/?probe=a49cbc797b) | May 18, 2023 |
| HP            | 18E9                        | Desktop     | [2128541eb5](https://linux-hardware.org/?probe=2128541eb5) | May 18, 2023 |
| ASUSTek       | K73SV                       | Notebook    | [d1d5700b2c](https://linux-hardware.org/?probe=d1d5700b2c) | May 18, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | Notebook    | [8c15641d9d](https://linux-hardware.org/?probe=8c15641d9d) | May 18, 2023 |
| Microsoft     | Surface Pro 8               | Tablet      | [4b28001974](https://linux-hardware.org/?probe=4b28001974) | May 18, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [790c5137ba](https://linux-hardware.org/?probe=790c5137ba) | May 18, 2023 |
| Dell          | Latitude E7240              | Notebook    | [208261238e](https://linux-hardware.org/?probe=208261238e) | May 18, 2023 |
| Dell          | Latitude E7240              | Notebook    | [faf148036f](https://linux-hardware.org/?probe=faf148036f) | May 18, 2023 |
| Dell          | Latitude E6410              | Notebook    | [3718cd0c74](https://linux-hardware.org/?probe=3718cd0c74) | May 18, 2023 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [fac077457d](https://linux-hardware.org/?probe=fac077457d) | May 18, 2023 |
| ASUSTek       | X541SA                      | Notebook    | [c88acf1dbc](https://linux-hardware.org/?probe=c88acf1dbc) | May 18, 2023 |
| Unknown       | T100                        | Desktop     | [c4a7218b7b](https://linux-hardware.org/?probe=c4a7218b7b) | May 18, 2023 |
| Medion        | E6232                       | Notebook    | [a447a0aba0](https://linux-hardware.org/?probe=a447a0aba0) | May 18, 2023 |
| Alcor Digi... | Snugbook N1431              | Notebook    | [a04e4c387e](https://linux-hardware.org/?probe=a04e4c387e) | May 17, 2023 |
| Dell          | 0GXM1W A00                  | Desktop     | [908f915724](https://linux-hardware.org/?probe=908f915724) | May 17, 2023 |
| Intel         | DH57JG AAE70930-304         | Desktop     | [925438abbb](https://linux-hardware.org/?probe=925438abbb) | May 17, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [bb4c9d6b4c](https://linux-hardware.org/?probe=bb4c9d6b4c) | May 17, 2023 |
| ASUSTek       | P5G41T-M                    | Desktop     | [89d938fcef](https://linux-hardware.org/?probe=89d938fcef) | May 17, 2023 |
| HP            | Pavilion Laptop 15-eg1xx... | Notebook    | [b5aef01bc9](https://linux-hardware.org/?probe=b5aef01bc9) | May 17, 2023 |
| HP            | EliteBook 820 G2            | Notebook    | [200610da74](https://linux-hardware.org/?probe=200610da74) | May 17, 2023 |
| Unknown       | Unknown                     | Notebook    | [0323142e79](https://linux-hardware.org/?probe=0323142e79) | May 17, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [bc68a82a48](https://linux-hardware.org/?probe=bc68a82a48) | May 17, 2023 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [f93ee0d717](https://linux-hardware.org/?probe=f93ee0d717) | May 17, 2023 |
| Unknown       | Unknown                     | Notebook    | [d734e52f59](https://linux-hardware.org/?probe=d734e52f59) | May 17, 2023 |
| HP            | Laptop 14s-dq0xxx           | Notebook    | [0a08d453f7](https://linux-hardware.org/?probe=0a08d453f7) | May 17, 2023 |
| Dell          | Latitude E7240              | Notebook    | [1990186432](https://linux-hardware.org/?probe=1990186432) | May 17, 2023 |
| Lenovo        | ThinkPad Edge E530 62722... | Notebook    | [baa1b942cf](https://linux-hardware.org/?probe=baa1b942cf) | May 17, 2023 |
| Lenovo        | 317E SDK0J40700 WIN 3258... | Desktop     | [281042ebf0](https://linux-hardware.org/?probe=281042ebf0) | May 17, 2023 |
| ASUSTek       | G750JM                      | Notebook    | [2a93ec6ed8](https://linux-hardware.org/?probe=2a93ec6ed8) | May 17, 2023 |
| Lenovo        | ThinkPad Yoga 460 20EM00... | Convertible | [83edbdf941](https://linux-hardware.org/?probe=83edbdf941) | May 17, 2023 |
| Dell          | Vostro 5402                 | Notebook    | [00e3bf6a3e](https://linux-hardware.org/?probe=00e3bf6a3e) | May 17, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [44bc1d8d62](https://linux-hardware.org/?probe=44bc1d8d62) | May 17, 2023 |
| Dell          | Latitude E5510              | Notebook    | [74ecc09f16](https://linux-hardware.org/?probe=74ecc09f16) | May 17, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [e0fb89fec8](https://linux-hardware.org/?probe=e0fb89fec8) | May 17, 2023 |
| Dell          | 048DY8 A00                  | Desktop     | [1456bc7f66](https://linux-hardware.org/?probe=1456bc7f66) | May 17, 2023 |
| Dell          | Latitude 7430               | Notebook    | [eb576d7c2a](https://linux-hardware.org/?probe=eb576d7c2a) | May 17, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [228fa2798d](https://linux-hardware.org/?probe=228fa2798d) | May 16, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [87a75f9dd9](https://linux-hardware.org/?probe=87a75f9dd9) | May 16, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [32d4567b37](https://linux-hardware.org/?probe=32d4567b37) | May 16, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [87689f0ec7](https://linux-hardware.org/?probe=87689f0ec7) | May 16, 2023 |
| Lenovo        | V14 G2 ALC 82KC             | Notebook    | [de2456eae8](https://linux-hardware.org/?probe=de2456eae8) | May 16, 2023 |
| Intel         | SHARKBAY                    | Desktop     | [03b576ccc8](https://linux-hardware.org/?probe=03b576ccc8) | May 16, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [62e3c494bd](https://linux-hardware.org/?probe=62e3c494bd) | May 16, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [93805fe2f6](https://linux-hardware.org/?probe=93805fe2f6) | May 16, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [1d5a340968](https://linux-hardware.org/?probe=1d5a340968) | May 16, 2023 |
| SLIMBOOK      | Executive                   | Notebook    | [0a70f31ce9](https://linux-hardware.org/?probe=0a70f31ce9) | May 16, 2023 |
| ASUSTek       | X541UAK                     | Notebook    | [00685614c4](https://linux-hardware.org/?probe=00685614c4) | May 16, 2023 |
| HP            | EliteBook 850 G5            | Notebook    | [1b444989b5](https://linux-hardware.org/?probe=1b444989b5) | May 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [baa2041a25](https://linux-hardware.org/?probe=baa2041a25) | May 16, 2023 |
| ASUSTek       | H170-PRO/USB                | Desktop     | [2cefbf1505](https://linux-hardware.org/?probe=2cefbf1505) | May 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [c62b63f5bf](https://linux-hardware.org/?probe=c62b63f5bf) | May 16, 2023 |
| MSI           | MS-7369                     | Desktop     | [4a083f89af](https://linux-hardware.org/?probe=4a083f89af) | May 16, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [24cb48f7d7](https://linux-hardware.org/?probe=24cb48f7d7) | May 16, 2023 |
| HP            | ProBook 6570b               | Notebook    | [7d8b9d4be1](https://linux-hardware.org/?probe=7d8b9d4be1) | May 16, 2023 |
| Acer          | One Z1402                   | Notebook    | [390a684064](https://linux-hardware.org/?probe=390a684064) | May 16, 2023 |
| Lenovo        | ThinkCentre M90z 5205CTO    | All in one  | [6353fe7194](https://linux-hardware.org/?probe=6353fe7194) | May 16, 2023 |
| Dell          | Precision 5540              | Notebook    | [a97a05dd0e](https://linux-hardware.org/?probe=a97a05dd0e) | May 16, 2023 |
| PHILCO ELE... | PNB15.6AP34H1W10            | Notebook    | [4c4c7467ec](https://linux-hardware.org/?probe=4c4c7467ec) | May 16, 2023 |
| Positivo      | Q4128C-S                    | Notebook    | [05c0522fe3](https://linux-hardware.org/?probe=05c0522fe3) | May 16, 2023 |
| ASRock        | X370 Killer SLI/ac          | Desktop     | [353c940897](https://linux-hardware.org/?probe=353c940897) | May 15, 2023 |
| eMachines     | E625                        | Notebook    | [8638b2b8c8](https://linux-hardware.org/?probe=8638b2b8c8) | May 15, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [fe4f47ccc9](https://linux-hardware.org/?probe=fe4f47ccc9) | May 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [39f109f45a](https://linux-hardware.org/?probe=39f109f45a) | May 15, 2023 |
| ASRock        | X370 Killer SLI/ac          | Desktop     | [fea0d3465f](https://linux-hardware.org/?probe=fea0d3465f) | May 15, 2023 |
| HP            | 18E9                        | Desktop     | [59a47f84ec](https://linux-hardware.org/?probe=59a47f84ec) | May 15, 2023 |
| Dell          | Inspiron N5010              | Notebook    | [98f448ed70](https://linux-hardware.org/?probe=98f448ed70) | May 15, 2023 |
| Sony          | SVF1521B4E                  | Notebook    | [ec03e769b8](https://linux-hardware.org/?probe=ec03e769b8) | May 15, 2023 |
| Dell          | Precision 7520              | Notebook    | [cbfb960bae](https://linux-hardware.org/?probe=cbfb960bae) | May 15, 2023 |
| Dell          | Precision 7520              | Notebook    | [a42d1a8bf5](https://linux-hardware.org/?probe=a42d1a8bf5) | May 15, 2023 |
| Toshiba       | Satellite Pro R50-B         | Notebook    | [dda235ab03](https://linux-hardware.org/?probe=dda235ab03) | May 15, 2023 |
| Toshiba       | Satellite Pro R50-B         | Notebook    | [f9535b38b0](https://linux-hardware.org/?probe=f9535b38b0) | May 15, 2023 |
| Dell          | Latitude E6530              | Notebook    | [632b8094e3](https://linux-hardware.org/?probe=632b8094e3) | May 15, 2023 |
| HP            | 3398                        | Desktop     | [858590e655](https://linux-hardware.org/?probe=858590e655) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [a8bef903b0](https://linux-hardware.org/?probe=a8bef903b0) | May 15, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [5c97b405b5](https://linux-hardware.org/?probe=5c97b405b5) | May 15, 2023 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [3466945196](https://linux-hardware.org/?probe=3466945196) | May 15, 2023 |
| HP            | 339A                        | Desktop     | [35fdefb4eb](https://linux-hardware.org/?probe=35fdefb4eb) | May 15, 2023 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [2e2744285f](https://linux-hardware.org/?probe=2e2744285f) | May 15, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [aa218c643d](https://linux-hardware.org/?probe=aa218c643d) | May 14, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [c226d29f06](https://linux-hardware.org/?probe=c226d29f06) | May 14, 2023 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [408344938a](https://linux-hardware.org/?probe=408344938a) | May 14, 2023 |
| Sony          | VGN-FW51MF_H                | Notebook    | [572b403a00](https://linux-hardware.org/?probe=572b403a00) | May 14, 2023 |
| Sony          | VGN-FW51MF_H                | Notebook    | [0b0cc4f60e](https://linux-hardware.org/?probe=0b0cc4f60e) | May 14, 2023 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | Notebook    | [83537861c1](https://linux-hardware.org/?probe=83537861c1) | May 14, 2023 |
| Microsoft     | Surface Pro 8               | Tablet      | [fd5d8ff96d](https://linux-hardware.org/?probe=fd5d8ff96d) | May 14, 2023 |
| Foxconn       | 2ADA                        | Desktop     | [6392906ad5](https://linux-hardware.org/?probe=6392906ad5) | May 14, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [41dee90f85](https://linux-hardware.org/?probe=41dee90f85) | May 14, 2023 |
| ASRock        | B650E PG Riptide WiFi       | Desktop     | [9243456914](https://linux-hardware.org/?probe=9243456914) | May 14, 2023 |
| HP            | 829D                        | Desktop     | [a9358c228a](https://linux-hardware.org/?probe=a9358c228a) | May 14, 2023 |
| Unknown       | T100                        | Desktop     | [977cdddeb1](https://linux-hardware.org/?probe=977cdddeb1) | May 14, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [ca65ed1052](https://linux-hardware.org/?probe=ca65ed1052) | May 14, 2023 |
| MSI           | GF65 Thin 10UE              | Notebook    | [7d8bb12818](https://linux-hardware.org/?probe=7d8bb12818) | May 14, 2023 |
| Dell          | Precision 5540              | Notebook    | [22e1b4dbd4](https://linux-hardware.org/?probe=22e1b4dbd4) | May 14, 2023 |
| ASRock        | H110M-HDV PS                | Desktop     | [ba4344ac6e](https://linux-hardware.org/?probe=ba4344ac6e) | May 14, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [6941dd1931](https://linux-hardware.org/?probe=6941dd1931) | May 14, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [1bb0ed422e](https://linux-hardware.org/?probe=1bb0ed422e) | May 14, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Linux_Mint/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Linux Mint 20.3 | 3067      | 16.97%  |
| Linux Mint 20.2 | 2406      | 13.31%  |
| Linux Mint 21.1 | 2307      | 12.77%  |
| Linux Mint 20.1 | 2252      | 12.46%  |
| Linux Mint 19.3 | 2186      | 12.1%   |
| Linux Mint 20   | 2008      | 11.11%  |
| Linux Mint 21   | 1392      | 7.7%    |
| Linux Mint 19.1 | 911       | 5.04%   |
| Linux Mint 19.2 | 775       | 4.29%   |
| Linux Mint 19   | 355       | 1.96%   |
| Linux Mint 18.3 | 292       | 1.62%   |
| Linux Mint 18.2 | 55        | 0.3%    |
| Linux Mint 18.1 | 24        | 0.13%   |
| Linux Mint 18   | 21        | 0.12%   |
| Linux Mint 17.3 | 9         | 0.05%   |
| Linux Mint 21.2 | 3         | 0.02%   |
| Linux Mint 17.1 | 2         | 0.01%   |
| Linux Mint 17   | 2         | 0.01%   |
| Linux Mint 13   | 2         | 0.01%   |
| Linux Mint 17.2 | 1         | 0.01%   |
| Linux Mint 15   | 1         | 0.01%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Linux Mint | 16765     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.4.0-91-generic  | 686       | 3.39%   |
| 5.15.0-56-generic | 634       | 3.14%   |
| 5.4.0-58-generic  | 519       | 2.57%   |
| 5.4.0-74-generic  | 433       | 2.14%   |
| 5.4.0-42-generic  | 382       | 1.89%   |
| 5.15.0-58-generic | 371       | 1.83%   |
| 5.0.0-32-generic  | 346       | 1.71%   |
| 5.4.0-65-generic  | 332       | 1.64%   |
| 5.15.0-67-generic | 308       | 1.52%   |
| 5.4.0-77-generic  | 299       | 1.48%   |
| 5.15.0-60-generic | 287       | 1.42%   |
| 5.4.0-81-generic  | 284       | 1.4%    |
| 5.4.0-66-generic  | 281       | 1.39%   |
| 5.4.0-80-generic  | 273       | 1.35%   |
| 5.4.0-72-generic  | 266       | 1.32%   |
| 5.4.0-73-generic  | 255       | 1.26%   |
| 5.15.0-69-generic | 252       | 1.25%   |
| 5.4.0-100-generic | 250       | 1.24%   |
| 5.4.0-122-generic | 247       | 1.22%   |
| 4.15.0-54-generic | 246       | 1.22%   |
| 5.4.0-90-generic  | 245       | 1.21%   |
| 5.4.0-70-generic  | 244       | 1.21%   |
| 4.15.0-20-generic | 243       | 1.2%    |
| 5.4.0-88-generic  | 239       | 1.18%   |
| 5.4.0-107-generic | 233       | 1.15%   |
| 5.15.0-52-generic | 232       | 1.15%   |
| 5.4.0-89-generic  | 230       | 1.14%   |
| 5.4.0-26-generic  | 224       | 1.11%   |
| 5.15.0-71-generic | 221       | 1.09%   |
| 5.15.0-41-generic | 209       | 1.03%   |
| 5.4.0-109-generic | 206       | 1.02%   |
| 5.4.0-48-generic  | 190       | 0.94%   |
| 5.4.0-121-generic | 172       | 0.85%   |
| 5.4.0-96-generic  | 165       | 0.82%   |
| 5.15.0-73-generic | 165       | 0.82%   |
| 5.15.0-48-generic | 164       | 0.81%   |
| 5.15.0-47-generic | 163       | 0.81%   |
| 5.15.0-46-generic | 157       | 0.78%   |
| 5.4.0-84-generic  | 156       | 0.77%   |
| 5.15.0-72-generic | 156       | 0.77%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 8723      | 49.02%  |
| 5.15.0  | 3544      | 19.92%  |
| 4.15.0  | 2046      | 11.5%   |
| 5.3.0   | 901       | 5.06%   |
| 5.0.0   | 539       | 3.03%   |
| 5.13.0  | 346       | 1.94%   |
| 5.8.0   | 298       | 1.67%   |
| 5.11.0  | 251       | 1.41%   |
| 5.19.0  | 189       | 1.06%   |
| 4.10.0  | 90        | 0.51%   |
| 4.4.0   | 70        | 0.39%   |
| 4.18.0  | 63        | 0.35%   |
| 5.14.0  | 60        | 0.34%   |
| 4.13.0  | 59        | 0.33%   |
| 5.10.0  | 34        | 0.19%   |
| 4.8.0   | 27        | 0.15%   |
| 6.1.0   | 26        | 0.15%   |
| 6.0.0   | 26        | 0.15%   |
| 5.17.0  | 18        | 0.1%    |
| 5.6.0   | 15        | 0.08%   |
| 5.7.1   | 10        | 0.06%   |
| 5.9.0   | 9         | 0.05%   |
| 6.3.7   | 7         | 0.04%   |
| 6.2.0   | 7         | 0.04%   |
| 5.3.6   | 6         | 0.03%   |
| 6.3.4   | 5         | 0.03%   |
| 6.0.9   | 5         | 0.03%   |
| 5.8.18  | 5         | 0.03%   |
| 5.7.0   | 5         | 0.03%   |
| 5.18.12 | 5         | 0.03%   |
| 5.16.0  | 5         | 0.03%   |
| Unknown | 5         | 0.03%   |
| 6.2.8   | 4         | 0.02%   |
| 6.2.2   | 4         | 0.02%   |
| 6.1.4   | 4         | 0.02%   |
| 5.9.8   | 4         | 0.02%   |
| 5.9.1   | 4         | 0.02%   |
| 5.5.0   | 4         | 0.02%   |
| 5.4.1   | 4         | 0.02%   |
| 5.17.5  | 4         | 0.02%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 8739      | 49.15%  |
| 5.15    | 3574      | 20.1%   |
| 4.15    | 2049      | 11.52%  |
| 5.3     | 918       | 5.16%   |
| 5.0     | 554       | 3.12%   |
| 5.13    | 356       | 2%      |
| 5.8     | 315       | 1.77%   |
| 5.11    | 261       | 1.47%   |
| 5.19    | 196       | 1.1%    |
| 4.10    | 90        | 0.51%   |
| 4.4     | 70        | 0.39%   |
| 5.14    | 67        | 0.38%   |
| 4.18    | 66        | 0.37%   |
| 4.13    | 61        | 0.34%   |
| 5.10    | 58        | 0.33%   |
| 6.1     | 46        | 0.26%   |
| 6.0     | 40        | 0.22%   |
| 6.2     | 34        | 0.19%   |
| 5.17    | 33        | 0.19%   |
| 5.9     | 27        | 0.15%   |
| 4.8     | 27        | 0.15%   |
| 5.7     | 26        | 0.15%   |
| 6.3     | 23        | 0.13%   |
| 5.6     | 23        | 0.13%   |
| 5.18    | 17        | 0.1%    |
| 5.12    | 17        | 0.1%    |
| 5.16    | 16        | 0.09%   |
| 4.20    | 11        | 0.06%   |
| 5.5     | 9         | 0.05%   |
| 5.2     | 8         | 0.04%   |
| 5.1     | 8         | 0.04%   |
| 4.19    | 7         | 0.04%   |
| Unknown | 5         | 0.03%   |
| 4.16    | 4         | 0.02%   |
| 4.11    | 4         | 0.02%   |
| 3.13    | 4         | 0.02%   |
| 4.14    | 3         | 0.02%   |
| 4.12    | 3         | 0.02%   |
| 3.19    | 3         | 0.02%   |
| 4.17    | 2         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 16162     | 96.35%  |
| i686   | 613       | 3.65%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| X-Cinnamon      | 10171     | 59.05%  |
| MATE            | 1988      | 11.54%  |
| XFCE            | 1700      | 9.87%   |
| Cinnamon        | 1567      | 9.1%    |
| Unknown         | 1285      | 7.46%   |
| GNOME           | 355       | 2.06%   |
| KDE5            | 65        | 0.38%   |
| KDE             | 40        | 0.23%   |
| i3              | 12        | 0.07%   |
| LXDE            | 10        | 0.06%   |
| Budgie          | 5         | 0.03%   |
| Pantheon        | 4         | 0.02%   |
| KDE4            | 3         | 0.02%   |
| Deepin          | 3         | 0.02%   |
| Trinity         | 2         | 0.01%   |
| qtile           | 2         | 0.01%   |
| LXQt            | 2         | 0.01%   |
| GNOME Classic   | 2         | 0.01%   |
| openbox         | 1         | 0.01%   |
| Jwm             | 1         | 0.01%   |
| ICEWM           | 1         | 0.01%   |
| i3-with-shmlog  | 1         | 0.01%   |
| GNUstep         | 1         | 0.01%   |
| GNOME Flashback | 1         | 0.01%   |
| fluxbox         | 1         | 0.01%   |
| enlightenment   | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 16686     | 99.39%  |
| Tty     | 57        | 0.34%   |
| Wayland | 37        | 0.22%   |
| Unknown | 9         | 0.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 10101     | 59.11%  |
| LightDM | 4579      | 26.8%   |
| TDM     | 2213      | 12.95%  |
| MDM     | 82        | 0.48%   |
| SDDM    | 50        | 0.29%   |
| GDM     | 40        | 0.23%   |
| GDM3    | 19        | 0.11%   |
| LXDM    | 4         | 0.02%   |
| Ly      | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 4517      | 26.56%  |
| de_DE   | 2375      | 13.96%  |
| Unknown | 1677      | 9.86%   |
| pt_BR   | 1265      | 7.44%   |
| ru_RU   | 730       | 4.29%   |
| fr_FR   | 730       | 4.29%   |
| en_GB   | 701       | 4.12%   |
| C       | 565       | 3.32%   |
| it_IT   | 464       | 2.73%   |
| en_CA   | 388       | 2.28%   |
| es_ES   | 362       | 2.13%   |
| pl_PL   | 324       | 1.91%   |
| en_AU   | 273       | 1.61%   |
| nl_NL   | 191       | 1.12%   |
| en_IN   | 164       | 0.96%   |
| es_AR   | 140       | 0.82%   |
| cs_CZ   | 126       | 0.74%   |
| es_MX   | 123       | 0.72%   |
| en_ZA   | 110       | 0.65%   |
| hu_HU   | 109       | 0.64%   |
| de_AT   | 107       | 0.63%   |
| pt_PT   | 104       | 0.61%   |
| de_CH   | 88        | 0.52%   |
| ru_UA   | 86        | 0.51%   |
| sv_SE   | 69        | 0.41%   |
| fi_FI   | 69        | 0.41%   |
| tr_TR   | 62        | 0.36%   |
| fr_CA   | 62        | 0.36%   |
| sk_SK   | 60        | 0.35%   |
| en_NZ   | 60        | 0.35%   |
| es_CL   | 52        | 0.31%   |
| fr_BE   | 49        | 0.29%   |
| el_GR   | 49        | 0.29%   |
| es_CO   | 48        | 0.28%   |
| en_IE   | 48        | 0.28%   |
| zh_CN   | 41        | 0.24%   |
| uk_UA   | 41        | 0.24%   |
| nl_BE   | 36        | 0.21%   |
| en_PH   | 36        | 0.21%   |
| bg_BG   | 34        | 0.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 8560      | 50.35%  |
| BIOS | 8440      | 49.65%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 14814     | 87.26%  |
| Unknown  | 1193      | 7.03%   |
| Overlay  | 500       | 2.95%   |
| Btrfs    | 261       | 1.54%   |
| Zfs      | 62        | 0.37%   |
| Xfs      | 48        | 0.28%   |
| Ext3     | 34        | 0.2%    |
| Ext2     | 33        | 0.19%   |
| Tmpfs    | 21        | 0.12%   |
| Aufs     | 4         | 0.02%   |
| Jfs      | 3         | 0.02%   |
| XXXXX    | 1         | 0.01%   |
| Reiserfs | 1         | 0.01%   |
| ExX4     | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 10258     | 60.27%  |
| GPT     | 4832      | 28.39%  |
| MBR     | 1929      | 11.33%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 15634     | 92.48%  |
| Yes       | 1271      | 7.52%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 13639     | 80.59%  |
| Yes       | 3285      | 19.41%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 2579      | 15.38%  |
| Hewlett-Packard     | 2561      | 15.28%  |
| Lenovo              | 2078      | 12.39%  |
| Dell                | 1972      | 11.76%  |
| Acer                | 1140      | 6.8%    |
| Gigabyte Technology | 1132      | 6.75%   |
| MSI                 | 843       | 5.03%   |
| ASRock              | 609       | 3.63%   |
| Apple               | 362       | 2.16%   |
| Toshiba             | 326       | 1.94%   |
| Samsung Electronics | 295       | 1.76%   |
| Intel               | 293       | 1.75%   |
| Sony                | 167       | 1%      |
| Medion              | 152       | 0.91%   |
| Unknown             | 151       | 0.9%    |
| Fujitsu             | 141       | 0.84%   |
| Positivo            | 115       | 0.69%   |
| Pegatron            | 109       | 0.65%   |
| Google              | 85        | 0.51%   |
| Foxconn             | 80        | 0.48%   |
| Fujitsu Siemens     | 77        | 0.46%   |
| Biostar             | 74        | 0.44%   |
| Packard Bell        | 64        | 0.38%   |
| HUAWEI              | 64        | 0.38%   |
| ECS                 | 63        | 0.38%   |
| Notebook            | 57        | 0.34%   |
| Microsoft           | 46        | 0.27%   |
| AMI                 | 40        | 0.24%   |
| Gateway             | 39        | 0.23%   |
| Alienware           | 38        | 0.23%   |
| eMachines           | 34        | 0.2%    |
| LG Electronics      | 33        | 0.2%    |
| Itautec             | 28        | 0.17%   |
| Semp Toshiba        | 27        | 0.16%   |
| GPU Company         | 27        | 0.16%   |
| AZW                 | 25        | 0.15%   |
| Timi                | 24        | 0.14%   |
| Chuwi               | 24        | 0.14%   |
| OEM                 | 22        | 0.13%   |
| PCWare              | 21        | 0.13%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                      | Computers | Percent |
|---------------------------|-----------|---------|
| Unknown                   | 203       | 1.21%   |
| ASUS All Series           | 136       | 0.81%   |
| HP Notebook               | 70        | 0.42%   |
| HP Pavilion g6            | 49        | 0.29%   |
| HP Pavilion dv6           | 44        | 0.26%   |
| HP Pavilion 15            | 40        | 0.24%   |
| HP Pavilion dv7           | 37        | 0.22%   |
| Gigabyte B450M DS3H       | 32        | 0.19%   |
| Dell OptiPlex 790         | 32        | 0.19%   |
| Dell OptiPlex 7010        | 32        | 0.19%   |
| Dell OptiPlex 780         | 31        | 0.18%   |
| MSI MS-7693               | 30        | 0.18%   |
| HP Laptop 15-bw0xx        | 30        | 0.18%   |
| ASUS P50IJ                | 30        | 0.18%   |
| ASUS TUF Gaming X570-PLUS | 28        | 0.17%   |
| ASUS M5A78L-M/USB3        | 28        | 0.17%   |
| ASUS PRIME A320M-K        | 27        | 0.16%   |
| Positivo Mobile           | 25        | 0.15%   |
| MSI MS-7C56               | 25        | 0.15%   |
| MSI MS-7C37               | 25        | 0.15%   |
| Dell Inspiron 15-3567     | 25        | 0.15%   |
| MSI MS-7C02               | 24        | 0.14%   |
| Dell Latitude E6410       | 24        | 0.14%   |
| MSI MS-7B86               | 23        | 0.14%   |
| MSI MS-7817               | 23        | 0.14%   |
| Dell OptiPlex 3020        | 23        | 0.14%   |
| MSI MS-7721               | 22        | 0.13%   |
| HP Laptop 15-bs0xx        | 22        | 0.13%   |
| HP Compaq Elite 8300 SFF  | 22        | 0.13%   |
| Dell Latitude E6430       | 22        | 0.13%   |
| HP Pavilion Notebook      | 21        | 0.13%   |
| HP 15                     | 21        | 0.13%   |
| Dell OptiPlex 9020        | 21        | 0.13%   |
| Dell OptiPlex 755         | 21        | 0.13%   |
| Dell Latitude E6420       | 21        | 0.13%   |
| HP Pavilion g7            | 20        | 0.12%   |
| Dell Inspiron 1545        | 20        | 0.12%   |
| Apple MacBookPro9,2       | 20        | 0.12%   |
| HP EliteBook 840 G1       | 19        | 0.11%   |
| Gigabyte 970A-DS3P        | 19        | 0.11%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 835       | 4.98%   |
| Lenovo ThinkPad       | 798       | 4.76%   |
| Dell Inspiron         | 616       | 3.67%   |
| HP Pavilion           | 515       | 3.07%   |
| Dell Latitude         | 506       | 3.02%   |
| Lenovo IdeaPad        | 463       | 2.76%   |
| Dell OptiPlex         | 336       | 2%      |
| HP Compaq             | 310       | 1.85%   |
| HP Laptop             | 304       | 1.81%   |
| Toshiba Satellite     | 276       | 1.65%   |
| HP EliteBook          | 272       | 1.62%   |
| HP ProBook            | 243       | 1.45%   |
| ASUS PRIME            | 243       | 1.45%   |
| Unknown               | 203       | 1.21%   |
| Lenovo ThinkCentre    | 167       | 1%      |
| ASUS ROG              | 155       | 0.92%   |
| ASUS All              | 136       | 0.81%   |
| ASUS VivoBook         | 132       | 0.79%   |
| Dell Precision        | 130       | 0.78%   |
| ASUS TUF              | 126       | 0.75%   |
| Dell Vostro           | 124       | 0.74%   |
| Dell XPS              | 123       | 0.73%   |
| HP ENVY               | 97        | 0.58%   |
| ASUS M5A78L-M         | 73        | 0.44%   |
| HP Notebook           | 70        | 0.42%   |
| Lenovo Yoga           | 68        | 0.41%   |
| Fujitsu LIFEBOOK      | 67        | 0.4%    |
| HP EliteDesk          | 61        | 0.36%   |
| HP 250                | 56        | 0.33%   |
| Acer Swift            | 55        | 0.33%   |
| ASUS ZenBook          | 53        | 0.32%   |
| Acer TravelMate       | 49        | 0.29%   |
| HP ProDesk            | 48        | 0.29%   |
| Microsoft Surface     | 46        | 0.27%   |
| Lenovo Legion         | 45        | 0.27%   |
| HP ZBook              | 45        | 0.27%   |
| Gigabyte B450M        | 45        | 0.27%   |
| Fujitsu ESPRIMO       | 45        | 0.27%   |
| Packard Bell EasyNote | 44        | 0.26%   |
| ASUS P8H61-M          | 43        | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 1582      | 9.44%   |
| 2011    | 1485      | 8.86%   |
| 2013    | 1348      | 8.04%   |
| 2018    | 1264      | 7.54%   |
| 2019    | 1143      | 6.82%   |
| 2020    | 1142      | 6.81%   |
| 2010    | 1057      | 6.3%    |
| 2017    | 1046      | 6.24%   |
| 2014    | 1013      | 6.04%   |
| 2021    | 953       | 5.68%   |
| 2015    | 871       | 5.2%    |
| 2016    | 870       | 5.19%   |
| 2009    | 859       | 5.12%   |
| 2008    | 830       | 4.95%   |
| 2007    | 559       | 3.33%   |
| 2022    | 341       | 2.03%   |
| 2006    | 238       | 1.42%   |
| 2005    | 69        | 0.41%   |
| 2023    | 39        | 0.23%   |
| 2004    | 26        | 0.16%   |
| 2003    | 14        | 0.08%   |
| Unknown | 13        | 0.08%   |
| 2002    | 3         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 9354      | 55.79%  |
| Desktop     | 6534      | 38.97%  |
| Convertible | 278       | 1.66%   |
| All in one  | 212       | 1.26%   |
| Mini pc     | 208       | 1.24%   |
| Tablet      | 124       | 0.74%   |
| Server      | 53        | 0.32%   |
| Stick pc    | 2         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 15408     | 91.35%  |
| Enabled  | 1459      | 8.65%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 16670     | 99.43%  |
| Yes  | 96        | 0.57%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 4092      | 24.05%  |
| 3.01-4.0        | 3948      | 23.2%   |
| 8.01-16.0       | 3014      | 17.71%  |
| 16.01-24.0      | 2982      | 17.52%  |
| 32.01-64.0      | 1099      | 6.46%   |
| 1.01-2.0        | 948       | 5.57%   |
| 2.01-3.0        | 341       | 2%      |
| 64.01-256.0     | 254       | 1.49%   |
| 24.01-32.0      | 206       | 1.21%   |
| 0.51-1.0        | 126       | 0.74%   |
| More than 256.0 | 4         | 0.02%   |
| 0.01-0.5        | 2         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 1.01-2.0        | 7422      | 39.86%  |
| 2.01-3.0        | 4915      | 26.4%   |
| 3.01-4.0        | 2172      | 11.67%  |
| 4.01-8.0        | 2028      | 10.89%  |
| 0.51-1.0        | 1475      | 7.92%   |
| 8.01-16.0       | 433       | 2.33%   |
| 0.01-0.5        | 91        | 0.49%   |
| 16.01-24.0      | 53        | 0.28%   |
| 24.01-32.0      | 18        | 0.1%    |
| Unknown         | 7         | 0.04%   |
| 32.01-64.0      | 3         | 0.02%   |
| More than 256.0 | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 10234     | 59.25%  |
| 2       | 4480      | 25.93%  |
| 3       | 1360      | 7.87%   |
| 4       | 598       | 3.46%   |
| 5       | 268       | 1.55%   |
| 0       | 118       | 0.68%   |
| 6       | 111       | 0.64%   |
| 7       | 55        | 0.32%   |
| 8       | 25        | 0.14%   |
| 9       | 11        | 0.06%   |
| 10      | 4         | 0.02%   |
| 14      | 3         | 0.02%   |
| Unknown | 3         | 0.02%   |
| 27      | 2         | 0.01%   |
| 28      | 1         | 0.01%   |
| 22      | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 8747      | 51.76%  |
| Yes       | 8152      | 48.24%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 14963     | 89.05%  |
| No        | 1840      | 10.95%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 12797     | 75.84%  |
| No        | 4076      | 24.16%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 9177      | 54.01%  |
| No        | 7814      | 45.99%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 2772      | 16.44%  |
| Germany      | 2711      | 16.08%  |
| Brazil       | 1750      | 10.38%  |
| Russia       | 1074      | 6.37%   |
| France       | 789       | 4.68%   |
| UK           | 673       | 3.99%   |
| Italy        | 578       | 3.43%   |
| Canada       | 521       | 3.09%   |
| Spain        | 454       | 2.69%   |
| Poland       | 408       | 2.42%   |
| Netherlands  | 359       | 2.13%   |
| Australia    | 311       | 1.84%   |
| Ukraine      | 281       | 1.67%   |
| India        | 199       | 1.18%   |
| Switzerland  | 189       | 1.12%   |
| Mexico       | 185       | 1.1%    |
| Austria      | 183       | 1.09%   |
| Czechia      | 180       | 1.07%   |
| Argentina    | 171       | 1.01%   |
| Belgium      | 168       | 1%      |
| Sweden       | 150       | 0.89%   |
| Hungary      | 144       | 0.85%   |
| Portugal     | 142       | 0.84%   |
| Turkey       | 129       | 0.77%   |
| South Africa | 126       | 0.75%   |
| Greece       | 116       | 0.69%   |
| Finland      | 114       | 0.68%   |
| Romania      | 100       | 0.59%   |
| Slovakia     | 86        | 0.51%   |
| Bulgaria     | 82        | 0.49%   |
| Colombia     | 81        | 0.48%   |
| Denmark      | 77        | 0.46%   |
| New Zealand  | 70        | 0.42%   |
| Indonesia    | 70        | 0.42%   |
| Chile        | 67        | 0.4%    |
| Norway       | 64        | 0.38%   |
| Belarus      | 64        | 0.38%   |
| Ireland      | 60        | 0.36%   |
| Japan        | 52        | 0.31%   |
| Israel       | 51        | 0.3%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 249       | 1.39%   |
| Berlin            | 216       | 1.21%   |
| Sao Paulo         | 196       | 1.09%   |
| Vienna            | 112       | 0.63%   |
| Rio de Janeiro    | 108       | 0.6%    |
| St Petersburg     | 107       | 0.6%    |
| Hamburg           | 107       | 0.6%    |
| Paris             | 105       | 0.59%   |
| Munich            | 93        | 0.52%   |
| Warsaw            | 91        | 0.51%   |
| Sydney            | 87        | 0.49%   |
| Frankfurt am Main | 85        | 0.47%   |
| Kyiv              | 81        | 0.45%   |
| Milan             | 79        | 0.44%   |
| Amsterdam         | 71        | 0.4%    |
| Madrid            | 70        | 0.39%   |
| Rome              | 67        | 0.37%   |
| Rockville         | 67        | 0.37%   |
| Cologne           | 66        | 0.37%   |
| London            | 62        | 0.35%   |
| Chicago           | 59        | 0.33%   |
| Montreal          | 57        | 0.32%   |
| Melbourne         | 57        | 0.32%   |
| Budapest          | 57        | 0.32%   |
| Prague            | 53        | 0.3%    |
| Leipzig           | 51        | 0.28%   |
| Helsinki          | 51        | 0.28%   |
| Curitiba          | 51        | 0.28%   |
| Toronto           | 50        | 0.28%   |
| Athens            | 50        | 0.28%   |
| Barcelona         | 49        | 0.27%   |
| Porto Alegre      | 48        | 0.27%   |
| Brasília         | 47        | 0.26%   |
| Belo Horizonte    | 47        | 0.26%   |
| Zurich            | 45        | 0.25%   |
| Stuttgart         | 45        | 0.25%   |
| Brisbane          | 45        | 0.25%   |
| Sofia             | 42        | 0.23%   |
| Istanbul          | 42        | 0.23%   |
| Krasnodar         | 39        | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 4083      | 6228   | 16.72%  |
| Seagate                   | 3983      | 5954   | 16.31%  |
| Samsung Electronics       | 3345      | 4938   | 13.7%   |
| Toshiba                   | 1607      | 2028   | 6.58%   |
| Kingston                  | 1392      | 1817   | 5.7%    |
| SanDisk                   | 1203      | 1638   | 4.93%   |
| Unknown                   | 991       | 1369   | 4.06%   |
| Hitachi                   | 940       | 1194   | 3.85%   |
| Crucial                   | 902       | 1257   | 3.69%   |
| Intel                     | 469       | 626    | 1.92%   |
| HGST                      | 453       | 603    | 1.85%   |
| SK hynix                  | 441       | 502    | 1.81%   |
| A-DATA Technology         | 345       | 456    | 1.41%   |
| China                     | 281       | 345    | 1.15%   |
| Micron Technology         | 247       | 312    | 1.01%   |
| Intenso                   | 176       | 232    | 0.72%   |
| Apple                     | 152       | 195    | 0.62%   |
| PNY                       | 137       | 169    | 0.56%   |
| Maxtor                    | 134       | 183    | 0.55%   |
| Fujitsu                   | 129       | 170    | 0.53%   |
| Phison                    | 128       | 175    | 0.52%   |
| SPCC                      | 124       | 163    | 0.51%   |
| KIOXIA                    | 115       | 135    | 0.47%   |
| Patriot                   | 112       | 142    | 0.46%   |
| OCZ                       | 110       | 140    | 0.45%   |
| Transcend                 | 103       | 140    | 0.42%   |
| LITEON                    | 93        | 114    | 0.38%   |
| Unknown                   | 89        | 108    | 0.36%   |
| GOODRAM                   | 86        | 115    | 0.35%   |
| Silicon Motion            | 84        | 119    | 0.34%   |
| JMicron Technology        | 80        | 107    | 0.33%   |
| Corsair                   | 80        | 93     | 0.33%   |
| Micron/Crucial Technology | 68        | 102    | 0.28%   |
| Apacer                    | 62        | 72     | 0.25%   |
| LITEONIT                  | 59        | 68     | 0.24%   |
| KingSpec                  | 57        | 77     | 0.23%   |
| Team                      | 50        | 66     | 0.2%    |
| Plextor                   | 49        | 62     | 0.2%    |
| Netac                     | 48        | 62     | 0.2%    |
| Lexar                     | 48        | 60     | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 357       | 1.33%   |
| Unknown MMC Card  32GB                              | 210       | 0.78%   |
| Seagate ST500DM002-1BD142 500GB                     | 207       | 0.77%   |
| Samsung SSD 850 EVO 250GB                           | 206       | 0.77%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 204       | 0.76%   |
| Seagate ST1000LM035-1RK172 1TB                      | 201       | 0.75%   |
| Samsung SSD 860 EVO 500GB                           | 197       | 0.74%   |
| Toshiba MQ01ABD100 1TB                              | 187       | 0.7%    |
| Unknown MMC Card  64GB                              | 175       | 0.65%   |
| Kingston SA400S37120G 120GB SSD                     | 167       | 0.62%   |
| Kingston SA400S37480G 480GB SSD                     | 156       | 0.58%   |
| Samsung SSD 850 EVO 500GB                           | 146       | 0.55%   |
| Toshiba MQ01ABF050 500GB                            | 141       | 0.53%   |
| Seagate ST1000DM010-2EP102 1TB                      | 138       | 0.52%   |
| Toshiba DT01ACA100 1TB                              | 136       | 0.51%   |
| Samsung SSD 860 EVO 1TB                             | 134       | 0.5%    |
| Seagate ST500LT012-1DG142 500GB                     | 122       | 0.46%   |
| Crucial CT1000MX500SSD1 1TB                         | 122       | 0.46%   |
| Kingston SV300S37A120G 120GB SSD                    | 120       | 0.45%   |
| Crucial CT500MX500SSD1 500GB                        | 119       | 0.44%   |
| Crucial CT240BX500SSD1 240GB                        | 119       | 0.44%   |
| Seagate ST9500325AS 500GB                           | 114       | 0.43%   |
| Unknown SD/MMC/MS PRO 250GB                         | 108       | 0.4%    |
| Toshiba MQ04ABF100 1TB                              | 108       | 0.4%    |
| Unknown MMC Card  128GB                             | 104       | 0.39%   |
| Samsung SSD 860 EVO 250GB                           | 104       | 0.39%   |
| Seagate ST2000DM008-2FR102 2TB                      | 103       | 0.38%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 101       | 0.38%   |
| Seagate Expansion 1TB                               | 99        | 0.37%   |
| Seagate ST1000DM003-1CH162 1TB                      | 98        | 0.37%   |
| Seagate ST3500418AS 500GB                           | 95        | 0.35%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 92        | 0.34%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 92        | 0.34%   |
| HGST HTS721010A9E630 1TB                            | 91        | 0.34%   |
| SanDisk SSD PLUS 240GB                              | 89        | 0.33%   |
| Unknown                                             | 89        | 0.33%   |
| Seagate ST1000DM003-1ER162 1TB                      | 85        | 0.32%   |
| Samsung NVMe SSD Drive 500GB                        | 81        | 0.3%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 81        | 0.3%    |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 76        | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3915      | 5802   | 34.84%  |
| WDC                 | 3392      | 5196   | 30.19%  |
| Toshiba             | 1342      | 1679   | 11.94%  |
| Hitachi             | 940       | 1194   | 8.37%   |
| Samsung Electronics | 612       | 858    | 5.45%   |
| HGST                | 453       | 603    | 4.03%   |
| Maxtor              | 130       | 179    | 1.16%   |
| Fujitsu             | 127       | 167    | 1.13%   |
| Unknown             | 118       | 151    | 1.05%   |
| Apple               | 43        | 50     | 0.38%   |
| Intenso             | 17        | 20     | 0.15%   |
| ASMT                | 17        | 27     | 0.15%   |
| ASMedia             | 15        | 17     | 0.13%   |
| USB3.0              | 10        | 11     | 0.09%   |
| JMicron Technology  | 10        | 21     | 0.09%   |
| HGST HTS            | 7         | 10     | 0.06%   |
| Hewlett-Packard     | 7         | 11     | 0.06%   |
| ExcelStor           | 7         | 9      | 0.06%   |
| WD MediaMax         | 6         | 14     | 0.05%   |
| Pioneer             | 5         | 6      | 0.04%   |
| PHD 3.0             | 4         | 5      | 0.04%   |
| SAGE                | 3         | 4      | 0.03%   |
| SABRENT             | 3         | 3      | 0.03%   |
| Maxone              | 3         | 3      | 0.03%   |
| KESU                | 3         | 4      | 0.03%   |
| HPE                 | 3         | 4      | 0.03%   |
| ASMT109x            | 3         | 3      | 0.03%   |
| Apricorn            | 3         | 5      | 0.03%   |
| USB                 | 2         | 2      | 0.02%   |
| SSK                 | 2         | 2      | 0.02%   |
| RSH-319             | 2         | 2      | 0.02%   |
| Maxtor 6            | 2         | 3      | 0.02%   |
| LaCie               | 2         | 2      | 0.02%   |
| Inateck             | 2         | 2      | 0.02%   |
| IBM/Hitachi         | 2         | 2      | 0.02%   |
| HGST HUS            | 2         | 2      | 0.02%   |
| Unknown             | 2         | 4      | 0.02%   |
| USB 3.0             | 1         | 4      | 0.01%   |
| TANDBERG            | 1         | 1      | 0.01%   |
| Synology            | 1         | 1      | 0.01%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1797      | 2558   | 21.54%  |
| Kingston            | 1190      | 1560   | 14.26%  |
| SanDisk             | 858       | 1173   | 10.28%  |
| Crucial             | 836       | 1169   | 10.02%  |
| WDC                 | 520       | 676    | 6.23%   |
| A-DATA Technology   | 288       | 385    | 3.45%   |
| China               | 279       | 343    | 3.34%   |
| Intel               | 191       | 254    | 2.29%   |
| Intenso             | 135       | 178    | 1.62%   |
| PNY                 | 127       | 158    | 1.52%   |
| Toshiba             | 120       | 151    | 1.44%   |
| Micron Technology   | 115       | 149    | 1.38%   |
| SPCC                | 113       | 151    | 1.35%   |
| OCZ                 | 109       | 138    | 1.31%   |
| Patriot             | 105       | 135    | 1.26%   |
| SK hynix            | 97        | 119    | 1.16%   |
| Transcend           | 93        | 122    | 1.11%   |
| LITEON              | 86        | 107    | 1.03%   |
| GOODRAM             | 84        | 113    | 1.01%   |
| Apple               | 74        | 85     | 0.89%   |
| LITEONIT            | 59        | 68     | 0.71%   |
| Apacer              | 58        | 68     | 0.7%    |
| KingSpec            | 56        | 76     | 0.67%   |
| Corsair             | 51        | 60     | 0.61%   |
| Team                | 47        | 63     | 0.56%   |
| Lexar               | 45        | 57     | 0.54%   |
| Plextor             | 44        | 54     | 0.53%   |
| Netac               | 43        | 56     | 0.52%   |
| Unknown             | 36        | 47     | 0.43%   |
| TO Exter            | 24        | 32     | 0.29%   |
| Seagate             | 24        | 40     | 0.29%   |
| Hewlett-Packard     | 24        | 27     | 0.29%   |
| KingDian            | 23        | 34     | 0.28%   |
| Gigabyte Technology | 22        | 35     | 0.26%   |
| Dogfish             | 20        | 26     | 0.24%   |
| ASMT                | 19        | 25     | 0.23%   |
| Verbatim            | 18        | 29     | 0.22%   |
| Leven               | 15        | 19     | 0.18%   |
| KingFast            | 15        | 15     | 0.18%   |
| AMD                 | 15        | 16     | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 9488      | 16104  | 43.47%  |
| SSD     | 7388      | 11142  | 33.85%  |
| NVMe    | 3677      | 5081   | 16.85%  |
| MMC     | 899       | 1209   | 4.12%   |
| Unknown | 374       | 541    | 1.71%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 13894     | 26368  | 71.53%  |
| NVMe | 3622      | 4976   | 18.65%  |
| SAS  | 1010      | 1524   | 5.2%    |
| MMC  | 899       | 1209   | 4.63%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 10539     | 16575  | 60.25%  |
| 0.51-1.0        | 4912      | 7215   | 28.08%  |
| 1.01-2.0        | 1199      | 2036   | 6.85%   |
| 3.01-4.0        | 319       | 574    | 1.82%   |
| 4.01-10.0       | 246       | 379    | 1.41%   |
| 2.01-3.0        | 241       | 386    | 1.38%   |
| 10.01-20.0      | 32        | 78     | 0.18%   |
| 0               | 2         | 2      | 0.01%   |
| More than 100.0 | 1         | 1      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 5176      | 29.41%  |
| 251-500        | 4323      | 24.56%  |
| 501-1000       | 2744      | 15.59%  |
| 1001-2000      | 1453      | 8.26%   |
| 51-100         | 1199      | 6.81%   |
| More than 3000 | 868       | 4.93%   |
| 21-50          | 664       | 3.77%   |
| 2001-3000      | 560       | 3.18%   |
| 1-20           | 499       | 2.84%   |
| Unknown        | 113       | 0.64%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 4972      | 26.94%  |
| 21-50          | 4052      | 21.95%  |
| 101-250        | 2793      | 15.13%  |
| 51-100         | 2652      | 14.37%  |
| 251-500        | 1566      | 8.48%   |
| 501-1000       | 1117      | 6.05%   |
| 1001-2000      | 617       | 3.34%   |
| More than 3000 | 331       | 1.79%   |
| 2001-3000      | 245       | 1.33%   |
| Unknown        | 113       | 0.61%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB           | 30        | 34     | 1.89%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 29        | 30     | 1.83%   |
| Seagate ST500DM002-1BD142 500GB     | 27        | 28     | 1.7%    |
| Seagate ST1000LM035-1RK172 1TB      | 21        | 29     | 1.32%   |
| Seagate ST3500418AS 500GB           | 20        | 22     | 1.26%   |
| Seagate ST500LT012-9WS142 500GB     | 19        | 21     | 1.2%    |
| HGST HTS545050A7E680 500GB          | 19        | 41     | 1.2%    |
| Seagate ST500LT012-1DG142 500GB     | 17        | 18     | 1.07%   |
| Toshiba MQ01ABD100 1TB              | 15        | 17     | 0.95%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 15        | 16     | 0.95%   |
| HGST HTS721010A9E630 1TB            | 13        | 13     | 0.82%   |
| Toshiba MQ01ABF050 500GB            | 12        | 13     | 0.76%   |
| Seagate ST9320325AS 320GB           | 11        | 11     | 0.69%   |
| Seagate ST31000528AS 1TB            | 10        | 12     | 0.63%   |
| HGST HTS725050A7E630 500GB          | 10        | 10     | 0.63%   |
| HGST HTS541010A9E680 1TB            | 10        | 10     | 0.63%   |
| LITEON CV8-8E128-HP 128GB SSD       | 9         | 11     | 0.57%   |
| Crucial CT525MX300SSD1 528GB        | 9         | 9      | 0.57%   |
| Seagate ST9500420AS 500GB           | 8         | 8      | 0.5%    |
| Seagate ST9250315AS 250GB           | 8         | 8      | 0.5%    |
| Seagate ST1000DM003-9YN162 1TB      | 8         | 9      | 0.5%    |
| WDC WD10EARS-00Y5B1 1TB             | 7         | 7      | 0.44%   |
| Toshiba MQ04ABF100 1TB              | 7         | 7      | 0.44%   |
| Toshiba MK7575GSX 752GB             | 7         | 7      | 0.44%   |
| Seagate ST3500320AS 500GB           | 7         | 9      | 0.44%   |
| Kingston SV300S37A120G 120GB SSD    | 7         | 7      | 0.44%   |
| Hitachi HTS547575A9E384 752GB       | 7         | 7      | 0.44%   |
| HGST HTS545050A7E380 500GB          | 7         | 8      | 0.44%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 6         | 6      | 0.38%   |
| WDC WD10JPVX-22JC3T0 1TB            | 6         | 6      | 0.38%   |
| Seagate ST3500413AS 500GB           | 6         | 8      | 0.38%   |
| Seagate ST31000524AS 1TB            | 6         | 7      | 0.38%   |
| SanDisk SSD PLUS 240GB              | 6         | 6      | 0.38%   |
| Samsung Electronics HD322HJ 320GB   | 6         | 13     | 0.38%   |
| Hitachi HTS725050A9A364 500GB       | 6         | 7      | 0.38%   |
| Hitachi HTS547550A9E384 500GB       | 6         | 6      | 0.38%   |
| Hitachi HTS545050B9A300 500GB       | 6         | 7      | 0.38%   |
| Hitachi HTS545050A7E380 500GB       | 6         | 6      | 0.38%   |
| Hitachi HTS545025B9A300 250GB       | 6         | 6      | 0.38%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 5         | 5      | 0.32%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 465       | 539    | 30.21%  |
| WDC                 | 308       | 378    | 20.01%  |
| Hitachi             | 136       | 148    | 8.84%   |
| Toshiba             | 124       | 133    | 8.06%   |
| Samsung Electronics | 109       | 137    | 7.08%   |
| HGST                | 72        | 97     | 4.68%   |
| SanDisk             | 50        | 58     | 3.25%   |
| Kingston            | 41        | 43     | 2.66%   |
| Crucial             | 37        | 47     | 2.4%    |
| Intel               | 26        | 26     | 1.69%   |
| Maxtor              | 21        | 27     | 1.36%   |
| SK hynix            | 18        | 22     | 1.17%   |
| China               | 13        | 14     | 0.84%   |
| LITEON              | 11        | 13     | 0.71%   |
| A-DATA Technology   | 11        | 11     | 0.71%   |
| Fujitsu             | 9         | 13     | 0.58%   |
| OCZ                 | 7         | 8      | 0.45%   |
| Micron Technology   | 7         | 10     | 0.45%   |
| LITEONIT            | 6         | 6      | 0.39%   |
| Corsair             | 6         | 9      | 0.39%   |
| Transcend           | 5         | 5      | 0.32%   |
| Apple               | 5         | 5      | 0.32%   |
| XPG                 | 3         | 4      | 0.19%   |
| SPCC                | 3         | 4      | 0.19%   |
| Lenovo              | 3         | 3      | 0.19%   |
| KingSpec            | 3         | 3      | 0.19%   |
| Intenso             | 3         | 3      | 0.19%   |
| Plextor             | 2         | 2      | 0.13%   |
| Patriot             | 2         | 2      | 0.13%   |
| Leven               | 2         | 2      | 0.13%   |
| LDLC                | 2         | 2      | 0.13%   |
| Kingmax             | 2         | 2      | 0.13%   |
| Hewlett-Packard     | 2         | 2      | 0.13%   |
| WDC WDS2            | 1         | 1      | 0.06%   |
| USB3.0              | 1         | 1      | 0.06%   |
| Unknown             | 1         | 1      | 0.06%   |
| TrekStor            | 1         | 1      | 0.06%   |
| Team                | 1         | 1      | 0.06%   |
| SSSTC               | 1         | 1      | 0.06%   |
| Silicon Motion      | 1         | 1      | 0.06%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 465       | 539    | 38.69%  |
| WDC                 | 294       | 361    | 24.46%  |
| Hitachi             | 136       | 148    | 11.31%  |
| Toshiba             | 118       | 126    | 9.82%   |
| Samsung Electronics | 74        | 100    | 6.16%   |
| HGST                | 72        | 97     | 5.99%   |
| Maxtor              | 21        | 27     | 1.75%   |
| Fujitsu             | 9         | 13     | 0.75%   |
| Apple               | 3         | 3      | 0.25%   |
| USB3.0              | 1         | 1      | 0.08%   |
| Unknown             | 1         | 1      | 0.08%   |
| JMicron Technology  | 1         | 1      | 0.08%   |
| HGST HTS            | 1         | 1      | 0.08%   |
| Hewlett-Packard     | 1         | 1      | 0.08%   |
| FEASSO              | 1         | 2      | 0.08%   |
| ExcelStor           | 1         | 1      | 0.08%   |
| ASMT                | 1         | 1      | 0.08%   |
| ASMedia             | 1         | 1      | 0.08%   |
| Unknown             | 1         | 2      | 0.08%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 1134      | 1426   | 77.14%  |
| SSD  | 296       | 335    | 20.14%  |
| NVMe | 40        | 45     | 2.72%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-80V0TT0 500GB                   | 2         | 2      | 9.52%   |
| Toshiba DT01ACA100 1TB                         | 2         | 2      | 9.52%   |
| Samsung Electronics HD252HJ 250GB              | 2         | 2      | 9.52%   |
| WDC WD2003FYYS-18W0B0 2TB                      | 1         | 1      | 4.76%   |
| Toshiba THNSN5512GPU7 512GB                    | 1         | 1      | 4.76%   |
| Toshiba MQ01ABF032 320GB                       | 1         | 1      | 4.76%   |
| Toshiba MQ01ABD075 752GB                       | 1         | 1      | 4.76%   |
| Seagate ST9160821AS 160GB                      | 1         | 1      | 4.76%   |
| Seagate ST500LM012 HN-M500MBB 500GB            | 1         | 1      | 4.76%   |
| Seagate ST1000LM 024 HN-M101MBB 1TB            | 1         | 1      | 4.76%   |
| Samsung Electronics SSD 980 1TB                | 1         | 1      | 4.76%   |
| Samsung Electronics HD322GJ 320GB              | 1         | 1      | 4.76%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 4.76%   |
| Hitachi HTS547550A9E384 500GB                  | 1         | 1      | 4.76%   |
| Hitachi HDS721050DLE630 500GB                  | 1         | 1      | 4.76%   |
| Hitachi HDS721050CLA362 500GB                  | 1         | 1      | 4.76%   |
| HGST HTS545050A7E380 500GB                     | 1         | 1      | 4.76%   |
| HGST HTS541010B7E610 1TB                       | 1         | 1      | 4.76%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 5         | 5      | 23.81%  |
| Samsung Electronics | 4         | 4      | 19.05%  |
| WDC                 | 3         | 3      | 14.29%  |
| Seagate             | 3         | 3      | 14.29%  |
| Hitachi             | 3         | 3      | 14.29%  |
| HGST                | 2         | 2      | 9.52%   |
| Micron Technology   | 1         | 1      | 4.76%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 10885     | 22656  | 60.11%  |
| Works    | 5766      | 9593   | 31.84%  |
| Malfunc  | 1434      | 1806   | 7.92%   |
| Failed   | 21        | 21     | 0.12%   |
| Limited  | 1         | 1      | 0.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 11574     | 57.71%  |
| AMD                              | 3319      | 16.55%  |
| Samsung Electronics              | 1208      | 6.02%   |
| SanDisk                          | 596       | 2.97%   |
| Nvidia                           | 398       | 1.98%   |
| SK hynix                         | 328       | 1.64%   |
| ASMedia Technology               | 298       | 1.49%   |
| Kingston Technology Company      | 247       | 1.23%   |
| JMicron Technology               | 246       | 1.23%   |
| Marvell Technology Group         | 244       | 1.22%   |
| Phison Electronics               | 226       | 1.13%   |
| Toshiba America Info Systems     | 152       | 0.76%   |
| Micron/Crucial Technology        | 136       | 0.68%   |
| Micron Technology                | 134       | 0.67%   |
| KIOXIA                           | 124       | 0.62%   |
| Silicon Motion                   | 120       | 0.6%    |
| VIA Technologies                 | 103       | 0.51%   |
| ADATA Technology                 | 96        | 0.48%   |
| Silicon Integrated Systems [SiS] | 79        | 0.39%   |
| Union Memory (Shenzhen)          | 60        | 0.3%    |
| Realtek Semiconductor            | 58        | 0.29%   |
| Solid State Storage Technology   | 36        | 0.18%   |
| Apple                            | 34        | 0.17%   |
| LSI Logic / Symbios Logic        | 32        | 0.16%   |
| Silicon Image                    | 28        | 0.14%   |
| Lite-On Technology               | 28        | 0.14%   |
| Broadcom / LSI                   | 21        | 0.1%    |
| Adaptec                          | 20        | 0.1%    |
| MAXIO Technology (Hangzhou)      | 14        | 0.07%   |
| Shenzhen Longsys Electronics     | 13        | 0.06%   |
| Seagate Technology               | 12        | 0.06%   |
| Lenovo                           | 12        | 0.06%   |
| Hewlett-Packard                  | 10        | 0.05%   |
| Integrated Technology Express    | 7         | 0.03%   |
| Transcend                        | 5         | 0.02%   |
| OCZ Technology Group             | 5         | 0.02%   |
| HighPoint Technologies           | 5         | 0.02%   |
| ULi Electronics                  | 4         | 0.02%   |
| Yangtze Memory Technologies      | 3         | 0.01%   |
| Lite-On IT Corp. / Plextor       | 3         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 1988      | 8.33%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 883       | 3.7%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 777       | 3.26%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 751       | 3.15%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 625       | 2.62%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 588       | 2.46%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 537       | 2.25%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 536       | 2.25%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 484       | 2.03%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 447       | 1.87%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 447       | 1.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 436       | 1.83%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 388       | 1.63%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 376       | 1.58%   |
| AMD 400 Series Chipset SATA Controller                                                  | 367       | 1.54%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 363       | 1.52%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 327       | 1.37%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 314       | 1.32%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 310       | 1.3%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 288       | 1.21%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 269       | 1.13%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 268       | 1.12%   |
| Samsung NVMe SSD Controller 980                                                         | 265       | 1.11%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 265       | 1.11%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 254       | 1.06%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 253       | 1.06%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 251       | 1.05%   |
| Intel SATA Controller [RAID mode]                                                       | 236       | 0.99%   |
| AMD 500 Series Chipset SATA Controller                                                  | 222       | 0.93%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 218       | 0.91%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 216       | 0.91%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 215       | 0.9%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 203       | 0.85%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 179       | 0.75%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 173       | 0.73%   |
| Nvidia MCP61 SATA Controller                                                            | 171       | 0.72%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 168       | 0.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 162       | 0.68%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 146       | 0.61%   |
| Intel SSD 660P Series                                                                   | 143       | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 12532     | 60.63%  |
| NVMe | 3640      | 17.61%  |
| IDE  | 3214      | 15.55%  |
| RAID | 1207      | 5.84%   |
| SAS  | 42        | 0.2%    |
| SCSI | 34        | 0.16%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 12762     | 76.12%  |
| AMD          | 3998      | 23.85%  |
| CentaurHauls | 5         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 147       | 0.87%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 136       | 0.81%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 129       | 0.77%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 122       | 0.73%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 115       | 0.68%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 108       | 0.64%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 107       | 0.64%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 101       | 0.6%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 98        | 0.58%   |
| AMD Ryzen 5 3600 6-Core Processor             | 98        | 0.58%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 96        | 0.57%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 96        | 0.57%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 94        | 0.56%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 93        | 0.55%   |
| AMD FX-8350 Eight-Core Processor              | 93        | 0.55%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 92        | 0.55%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 89        | 0.53%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 86        | 0.51%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 85        | 0.51%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 85        | 0.51%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 81        | 0.48%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 78        | 0.46%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 77        | 0.46%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 76        | 0.45%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 76        | 0.45%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 76        | 0.45%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 75        | 0.45%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 74        | 0.44%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 74        | 0.44%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 73        | 0.43%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 72        | 0.43%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 72        | 0.43%   |
| AMD FX-6300 Six-Core Processor                | 72        | 0.43%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 71        | 0.42%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 71        | 0.42%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 67        | 0.4%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 66        | 0.39%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 66        | 0.39%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 65        | 0.39%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 65        | 0.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 3647      | 21.72%  |
| Intel Core i7           | 2562      | 15.26%  |
| Intel Core i3           | 1486      | 8.85%   |
| Intel Celeron           | 1005      | 5.98%   |
| Intel Core 2 Duo        | 904       | 5.38%   |
| AMD Ryzen 5             | 823       | 4.9%    |
| Other                   | 708       | 4.22%   |
| Intel Pentium           | 562       | 3.35%   |
| AMD Ryzen 7             | 544       | 3.24%   |
| Intel Atom              | 405       | 2.41%   |
| AMD FX                  | 364       | 2.17%   |
| Intel Xeon              | 323       | 1.92%   |
| Intel Pentium Dual-Core | 287       | 1.71%   |
| AMD Ryzen 3             | 208       | 1.24%   |
| Intel Core 2 Quad       | 202       | 1.2%    |
| AMD A6                  | 178       | 1.06%   |
| AMD A8                  | 165       | 0.98%   |
| AMD A4                  | 157       | 0.93%   |
| Intel Pentium Dual      | 150       | 0.89%   |
| Intel Core 2            | 132       | 0.79%   |
| AMD Ryzen 9             | 128       | 0.76%   |
| AMD A10                 | 125       | 0.74%   |
| AMD Phenom II X4        | 114       | 0.68%   |
| AMD Athlon 64 X2        | 108       | 0.64%   |
| AMD Athlon II X2        | 97        | 0.58%   |
| AMD E                   | 88        | 0.52%   |
| Intel Genuine           | 80        | 0.48%   |
| Intel Pentium Silver    | 75        | 0.45%   |
| Intel Core i9           | 70        | 0.42%   |
| AMD E2                  | 63        | 0.38%   |
| AMD E1                  | 62        | 0.37%   |
| AMD Athlon II X4        | 62        | 0.37%   |
| Intel Pentium 4         | 61        | 0.36%   |
| AMD Athlon              | 59        | 0.35%   |
| AMD Turion 64 X2 Mobile | 46        | 0.27%   |
| AMD Ryzen 7 PRO         | 44        | 0.26%   |
| Intel Pentium D         | 43        | 0.26%   |
| AMD Phenom II X6        | 41        | 0.24%   |
| AMD Ryzen 5 PRO         | 39        | 0.23%   |
| Intel Pentium Gold      | 35        | 0.21%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 8049      | 47.91%  |
| 4       | 5597      | 33.31%  |
| 6       | 1272      | 7.57%   |
| 8       | 801       | 4.77%   |
| 1       | 557       | 3.32%   |
| 12      | 159       | 0.95%   |
| 3       | 152       | 0.9%    |
| 10      | 74        | 0.44%   |
| 16      | 58        | 0.35%   |
| 14      | 44        | 0.26%   |
| Unknown | 9         | 0.05%   |
| 24      | 8         | 0.05%   |
| 20      | 6         | 0.04%   |
| 18      | 5         | 0.03%   |
| 5       | 5         | 0.03%   |
| 32      | 2         | 0.01%   |
| 64      | 1         | 0.01%   |
| 40      | 1         | 0.01%   |
| 36      | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 16673     | 99.45%  |
| 2      | 92        | 0.55%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 9954      | 59.29%  |
| 1       | 6823      | 40.64%  |
| Unknown | 9         | 0.05%   |
| 4       | 2         | 0.01%   |
| 8       | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 15771     | 93.35%  |
| Unknown        | 939       | 5.56%   |
| 32-bit         | 185       | 1.09%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1533      | 8.94%   |
| 0x206a7    | 1347      | 7.85%   |
| 0x306a9    | 1239      | 7.22%   |
| 0x306c3    | 880       | 5.13%   |
| 0x1067a    | 870       | 5.07%   |
| 0x40651    | 476       | 2.78%   |
| 0x20655    | 412       | 2.4%    |
| 0x906ea    | 374       | 2.18%   |
| 0x406e3    | 353       | 2.06%   |
| 0x506e3    | 346       | 2.02%   |
| 0x6fd      | 331       | 1.93%   |
| 0x306d4    | 325       | 1.9%    |
| 0x806c1    | 324       | 1.89%   |
| 0x806ea    | 322       | 1.88%   |
| 0x806e9    | 312       | 1.82%   |
| 0x906e9    | 289       | 1.69%   |
| 0x806ec    | 274       | 1.6%    |
| 0x06000852 | 257       | 1.5%    |
| 0x406c4    | 242       | 1.41%   |
| 0x010000c8 | 232       | 1.35%   |
| 0x30678    | 226       | 1.32%   |
| 0x10676    | 218       | 1.27%   |
| 0x08108109 | 205       | 1.2%    |
| 0x20652    | 199       | 1.16%   |
| 0x08701021 | 195       | 1.14%   |
| 0x06001119 | 169       | 0.99%   |
| 0x706a8    | 155       | 0.9%    |
| 0x0800820d | 154       | 0.9%    |
| 0x0a50000c | 148       | 0.86%   |
| 0x6fb      | 142       | 0.83%   |
| 0x506c9    | 136       | 0.79%   |
| 0x08600106 | 130       | 0.76%   |
| 0x05000119 | 130       | 0.76%   |
| 0x706e5    | 128       | 0.75%   |
| 0x706a1    | 124       | 0.72%   |
| 0x406c3    | 120       | 0.7%    |
| 0x06006705 | 119       | 0.69%   |
| 0x106e5    | 113       | 0.66%   |
| 0x08608103 | 104       | 0.61%   |
| 0x08108102 | 99        | 0.58%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 1955      | 11.64%  |
| Haswell          | 1510      | 8.99%   |
| SandyBridge      | 1457      | 8.68%   |
| IvyBridge        | 1364      | 8.12%   |
| Penryn           | 1167      | 6.95%   |
| Skylake          | 783       | 4.66%   |
| Core             | 714       | 4.25%   |
| Westmere         | 691       | 4.12%   |
| Silvermont       | 646       | 3.85%   |
| Zen 2            | 525       | 3.13%   |
| Zen+             | 503       | 3%      |
| K10              | 492       | 2.93%   |
| Piledriver       | 474       | 2.82%   |
| TigerLake        | 358       | 2.13%   |
| Broadwell        | 358       | 2.13%   |
| Zen 3            | 346       | 2.06%   |
| Unknown          | 300       | 1.79%   |
| Goldmont plus    | 290       | 1.73%   |
| Zen              | 285       | 1.7%    |
| Excavator        | 282       | 1.68%   |
| CometLake        | 253       | 1.51%   |
| K8 Hammer        | 228       | 1.36%   |
| IceLake          | 206       | 1.23%   |
| Bonnell          | 191       | 1.14%   |
| Bobcat           | 176       | 1.05%   |
| Nehalem          | 173       | 1.03%   |
| Goldmont         | 150       | 0.89%   |
| Alderlake Hybrid | 136       | 0.81%   |
| Puma             | 129       | 0.77%   |
| NetBurst         | 121       | 0.72%   |
| P6               | 110       | 0.66%   |
| K10 Llano        | 99        | 0.59%   |
| Jaguar           | 89        | 0.53%   |
| Steamroller      | 82        | 0.49%   |
| Bulldozer        | 74        | 0.44%   |
| Tremont          | 37        | 0.22%   |
| K8 & K10 hybrid  | 28        | 0.17%   |
| K6               | 5         | 0.03%   |
| Gracemont        | 2         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 9712      | 50.31%  |
| Nvidia                                       | 4915      | 25.46%  |
| AMD                                          | 4527      | 23.45%  |
| Silicon Integrated Systems [SiS]             | 62        | 0.32%   |
| VIA Technologies                             | 35        | 0.18%   |
| Matrox Electronics Systems                   | 34        | 0.18%   |
| ASPEED Technology                            | 8         | 0.04%   |
| ATI Technologies                             | 5         | 0.03%   |
| S3 Graphics                                  | 4         | 0.02%   |
| XGI Technology (eXtreme Graphics Innovation) | 2         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1108      | 5.53%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 799       | 3.99%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 493       | 2.46%   |
| Intel Core Processor Integrated Graphics Controller                                      | 445       | 2.22%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 377       | 1.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 376       | 1.88%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 331       | 1.65%   |
| Intel HD Graphics 620                                                                    | 317       | 1.58%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 317       | 1.58%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 314       | 1.57%   |
| Intel UHD Graphics 620                                                                   | 306       | 1.53%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 290       | 1.45%   |
| Intel HD Graphics 5500                                                                   | 284       | 1.42%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 275       | 1.37%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 269       | 1.34%   |
| Intel HD Graphics 530                                                                    | 241       | 1.2%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 235       | 1.17%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 235       | 1.17%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 231       | 1.15%   |
| AMD Renoir                                                                               | 225       | 1.12%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 214       | 1.07%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 200       | 1%      |
| Nvidia GK208B [GeForce GT 710]                                                           | 186       | 0.93%   |
| Intel HD Graphics 630                                                                    | 183       | 0.91%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 171       | 0.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 171       | 0.85%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 170       | 0.85%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 168       | 0.84%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 168       | 0.84%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 164       | 0.82%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 150       | 0.75%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 144       | 0.72%   |
| AMD Lucienne                                                                             | 134       | 0.67%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 126       | 0.63%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 125       | 0.62%   |
| Nvidia GT218 [GeForce 210]                                                               | 122       | 0.61%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 122       | 0.61%   |
| Intel HD Graphics 500                                                                    | 114       | 0.57%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 113       | 0.56%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 108       | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| 1 x Intel           | 7431      | 44.09%  |
| 1 x AMD             | 3608      | 21.41%  |
| 1 x Nvidia          | 3069      | 18.21%  |
| Intel + Nvidia      | 1625      | 9.64%   |
| Intel + AMD         | 467       | 2.77%   |
| 2 x AMD             | 283       | 1.68%   |
| AMD + Nvidia        | 161       | 0.96%   |
| 1 x SiS             | 62        | 0.37%   |
| 2 x Nvidia          | 43        | 0.26%   |
| 1 x VIA             | 35        | 0.21%   |
| 1 x Matrox          | 26        | 0.15%   |
| Other               | 13        | 0.08%   |
| 3 x AMD             | 5         | 0.03%   |
| Nvidia + Matrox     | 5         | 0.03%   |
| 1 x ASPEED          | 5         | 0.03%   |
| AMD + Matrox        | 4         | 0.02%   |
| 1 x S3 Graphics     | 3         | 0.02%   |
| Nvidia + ASPEED     | 3         | 0.02%   |
| Nvidia + XGI        | 2         | 0.01%   |
| Intel + 2 x Nvidia  | 1         | 0.01%   |
| Intel + S3 Graphics | 1         | 0.01%   |
| AMD + 2 x Nvidia    | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 12932     | 76.11%  |
| Proprietary | 3280      | 19.3%   |
| Unknown     | 779       | 4.58%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 8190      | 47.65%  |
| 1.01-2.0   | 2633      | 15.32%  |
| 0.01-0.5   | 2490      | 14.49%  |
| 0.51-1.0   | 1592      | 9.26%   |
| 3.01-4.0   | 1161      | 6.76%   |
| 7.01-8.0   | 515       | 3%      |
| 5.01-6.0   | 340       | 1.98%   |
| 8.01-16.0  | 133       | 0.77%   |
| 2.01-3.0   | 117       | 0.68%   |
| 16.01-24.0 | 14        | 0.08%   |
| 4.01-5.0   | 2         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 2332      | 13.32%  |
| AU Optronics            | 2111      | 12.06%  |
| LG Display              | 1597      | 9.13%   |
| Chimei Innolux          | 1312      | 7.5%    |
| BOE                     | 1250      | 7.14%   |
| Goldstar                | 950       | 5.43%   |
| Dell                    | 863       | 4.93%   |
| Acer                    | 630       | 3.6%    |
| Hewlett-Packard         | 620       | 3.54%   |
| AOC                     | 440       | 2.51%   |
| Philips                 | 386       | 2.21%   |
| Ancor Communications    | 382       | 2.18%   |
| BenQ                    | 374       | 2.14%   |
| Apple                   | 326       | 1.86%   |
| Chi Mei Optoelectronics | 303       | 1.73%   |
| Lenovo                  | 291       | 1.66%   |
| LG Electronics          | 180       | 1.03%   |
| ViewSonic               | 165       | 0.94%   |
| Iiyama                  | 164       | 0.94%   |
| Unknown                 | 159       | 0.91%   |
| Sharp                   | 153       | 0.87%   |
| Sony                    | 144       | 0.82%   |
| LG Philips              | 133       | 0.76%   |
| PANDA                   | 122       | 0.7%    |
| InfoVision              | 117       | 0.67%   |
| ASUSTek Computer        | 106       | 0.61%   |
| HannStar                | 84        | 0.48%   |
| Eizo                    | 82        | 0.47%   |
| Fujitsu Siemens         | 74        | 0.42%   |
| NEC Computers           | 73        | 0.42%   |
| Toshiba                 | 71        | 0.41%   |
| CPT                     | 64        | 0.37%   |
| Panasonic               | 59        | 0.34%   |
| Vizio                   | 50        | 0.29%   |
| Medion                  | 41        | 0.23%   |
| Sceptre Tech            | 40        | 0.23%   |
| Unknown                 | 40        | 0.23%   |
| MSI                     | 39        | 0.22%   |
| Seiko/Epson             | 37        | 0.21%   |
| Vestel Elektronik       | 36        | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch     | 98        | 0.54%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 89        | 0.49%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 81        | 0.45%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 72        | 0.4%    |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 59        | 0.33%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 59        | 0.33%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 58        | 0.32%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 54        | 0.3%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 50        | 0.28%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 50        | 0.28%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 49        | 0.27%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 49        | 0.27%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 45        | 0.25%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 44        | 0.24%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 43        | 0.24%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 42        | 0.23%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 41        | 0.23%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 40        | 0.22%   |
| Unknown                                                                  | 40        | 0.22%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch            | 39        | 0.22%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 38        | 0.21%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 37        | 0.2%    |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 37        | 0.2%    |
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x400mm 31.7-inch     | 36        | 0.2%    |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 36        | 0.2%    |
| InfoVision LCD Monitor IVO03F4 1920x1200 263x164mm 12.2-inch             | 34        | 0.19%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 34        | 0.19%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 34        | 0.19%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 32        | 0.18%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch            | 31        | 0.17%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 30        | 0.17%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 30        | 0.17%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 29        | 0.16%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 29        | 0.16%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch            | 29        | 0.16%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 28        | 0.15%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 27        | 0.15%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch            | 27        | 0.15%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 26        | 0.14%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 26        | 0.14%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 6391      | 37.51%  |
| 1366x768 (WXGA)    | 4158      | 24.4%   |
| 1600x900 (HD+)     | 940       | 5.52%   |
| 3840x2160 (4K)     | 747       | 4.38%   |
| 1280x1024 (SXGA)   | 635       | 3.73%   |
| 1280x800 (WXGA)    | 554       | 3.25%   |
| 1440x900 (WXGA+)   | 538       | 3.16%   |
| 1680x1050 (WSXGA+) | 532       | 3.12%   |
| 2560x1440 (QHD)    | 478       | 2.81%   |
| 1920x1200 (WUXGA)  | 362       | 2.12%   |
| Unknown            | 289       | 1.7%    |
| 1360x768           | 205       | 1.2%    |
| 2560x1080          | 143       | 0.84%   |
| 3840x1080          | 101       | 0.59%   |
| 1024x600           | 88        | 0.52%   |
| 1024x768 (XGA)     | 86        | 0.5%    |
| 3440x1440          | 83        | 0.49%   |
| 2560x1600          | 75        | 0.44%   |
| 1920x540           | 53        | 0.31%   |
| 1600x1200          | 51        | 0.3%    |
| 2880x1800          | 46        | 0.27%   |
| 1280x720 (HD)      | 32        | 0.19%   |
| 2160x1440          | 27        | 0.16%   |
| 2736x1824          | 25        | 0.15%   |
| 3200x1080          | 20        | 0.12%   |
| 3200x1800 (QHD+)   | 18        | 0.11%   |
| 1680x945           | 18        | 0.11%   |
| 3840x1200          | 16        | 0.09%   |
| 3600x1080          | 16        | 0.09%   |
| 3000x2000          | 14        | 0.08%   |
| 3840x2400          | 13        | 0.08%   |
| 5760x1080          | 11        | 0.06%   |
| 1280x960           | 11        | 0.06%   |
| 4480x1440          | 10        | 0.06%   |
| 3072x1920          | 10        | 0.06%   |
| 2256x1504          | 10        | 0.06%   |
| 1920x1280          | 10        | 0.06%   |
| 1280x768           | 10        | 0.06%   |
| 5120x1440          | 8         | 0.05%   |
| 3520x1080          | 8         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 4547      | 26.09%  |
| Unknown | 1379      | 7.91%   |
| 13      | 1316      | 7.55%   |
| 14      | 1241      | 7.12%   |
| 17      | 1170      | 6.71%   |
| 24      | 1076      | 6.17%   |
| 23      | 998       | 5.73%   |
| 27      | 921       | 5.29%   |
| 21      | 905       | 5.19%   |
| 19      | 578       | 3.32%   |
| 18      | 460       | 2.64%   |
| 22      | 328       | 1.88%   |
| 20      | 328       | 1.88%   |
| 31      | 307       | 1.76%   |
| 12      | 283       | 1.62%   |
| 11      | 275       | 1.58%   |
| 34      | 186       | 1.07%   |
| 84      | 120       | 0.69%   |
| 10      | 106       | 0.61%   |
| 72      | 105       | 0.6%    |
| 40      | 94        | 0.54%   |
| 32      | 91        | 0.52%   |
| 16      | 86        | 0.49%   |
| 54      | 68        | 0.39%   |
| 25      | 56        | 0.32%   |
| 26      | 50        | 0.29%   |
| 46      | 29        | 0.17%   |
| 52      | 24        | 0.14%   |
| 28      | 23        | 0.13%   |
| 48      | 21        | 0.12%   |
| 65      | 19        | 0.11%   |
| 36      | 19        | 0.11%   |
| 47      | 18        | 0.1%    |
| 37      | 18        | 0.1%    |
| 29      | 16        | 0.09%   |
| 39      | 15        | 0.09%   |
| 33      | 15        | 0.09%   |
| 42      | 14        | 0.08%   |
| 74      | 10        | 0.06%   |
| 55      | 10        | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 6655      | 38.69%  |
| 501-600        | 2845      | 16.54%  |
| 401-500        | 2237      | 13%     |
| 351-400        | 1412      | 8.21%   |
| Unknown        | 1379      | 8.02%   |
| 201-300        | 1253      | 7.28%   |
| 601-700        | 454       | 2.64%   |
| 701-800        | 311       | 1.81%   |
| 1501-2000      | 244       | 1.42%   |
| 1001-1500      | 227       | 1.32%   |
| 801-900        | 145       | 0.84%   |
| 901-1000       | 26        | 0.15%   |
| 101-200        | 10        | 0.06%   |
| More than 2000 | 3         | 0.02%   |
| 1-100          | 2         | 0.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 11662     | 72.66%  |
| 16/10   | 1994      | 12.42%  |
| Unknown | 1232      | 7.68%   |
| 5/4     | 557       | 3.47%   |
| 21/9    | 203       | 1.26%   |
| 4/3     | 187       | 1.17%   |
| 3/2     | 147       | 0.92%   |
| 6/5     | 25        | 0.16%   |
| 32/9    | 25        | 0.16%   |
| 1.96    | 5         | 0.03%   |
| 1.00    | 4         | 0.02%   |
| 3.40    | 1         | 0.01%   |
| 3.20    | 1         | 0.01%   |
| 2.00    | 1         | 0.01%   |
| 11/10   | 1         | 0.01%   |
| 0.80    | 1         | 0.01%   |
| 0.75    | 1         | 0.01%   |
| 0.67    | 1         | 0.01%   |
| 0.62    | 1         | 0.01%   |
| 0.56    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 4520      | 26.13%  |
| 201-250        | 2672      | 15.45%  |
| 81-90          | 2104      | 12.16%  |
| Unknown        | 1379      | 7.97%   |
| 151-200        | 1191      | 6.89%   |
| 301-350        | 953       | 5.51%   |
| 121-130        | 747       | 4.32%   |
| 351-500        | 638       | 3.69%   |
| 141-150        | 636       | 3.68%   |
| 71-80          | 467       | 2.7%    |
| 251-300        | 402       | 2.32%   |
| More than 1000 | 401       | 2.32%   |
| 51-60          | 277       | 1.6%    |
| 501-1000       | 249       | 1.44%   |
| 61-70          | 243       | 1.4%    |
| 131-140        | 178       | 1.03%   |
| 41-50          | 107       | 0.62%   |
| 111-120        | 76        | 0.44%   |
| 91-100         | 45        | 0.26%   |
| 1-40           | 11        | 0.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 5692      | 33.77%  |
| 101-120       | 5102      | 30.27%  |
| 121-160       | 3483      | 20.66%  |
| Unknown       | 1379      | 8.18%   |
| 161-240       | 562       | 3.33%   |
| 1-50          | 434       | 2.57%   |
| More than 240 | 205       | 1.22%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 13866     | 81.32%  |
| 2     | 2207      | 12.94%  |
| 0     | 760       | 4.46%   |
| 3     | 203       | 1.19%   |
| 4     | 14        | 0.08%   |
| 5     | 1         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 9658      | 37.29%  |
| Intel                             | 6725      | 25.97%  |
| Qualcomm Atheros                  | 3429      | 13.24%  |
| Broadcom                          | 1604      | 6.19%   |
| Ralink Technology                 | 437       | 1.69%   |
| Marvell Technology Group          | 393       | 1.52%   |
| Broadcom Limited                  | 377       | 1.46%   |
| Ralink                            | 373       | 1.44%   |
| TP-Link                           | 343       | 1.32%   |
| Nvidia                            | 315       | 1.22%   |
| MediaTek                          | 235       | 0.91%   |
| Samsung Electronics               | 138       | 0.53%   |
| ASIX Electronics                  | 117       | 0.45%   |
| Qualcomm Atheros Communications   | 101       | 0.39%   |
| Xiaomi                            | 89        | 0.34%   |
| NetGear                           | 84        | 0.32%   |
| Huawei Technologies               | 79        | 0.31%   |
| D-Link                            | 71        | 0.27%   |
| D-Link System                     | 69        | 0.27%   |
| ASUSTek Computer                  | 68        | 0.26%   |
| JMicron Technology                | 66        | 0.25%   |
| Dell                              | 66        | 0.25%   |
| Ericsson Business Mobile Networks | 65        | 0.25%   |
| Silicon Integrated Systems [SiS]  | 64        | 0.25%   |
| VIA Technologies                  | 61        | 0.24%   |
| Sierra Wireless                   | 53        | 0.2%    |
| Hewlett-Packard                   | 46        | 0.18%   |
| Edimax Technology                 | 46        | 0.18%   |
| Qualcomm                          | 45        | 0.17%   |
| Microsoft                         | 42        | 0.16%   |
| Belkin Components                 | 39        | 0.15%   |
| Motorola PCS                      | 38        | 0.15%   |
| DisplayLink                       | 36        | 0.14%   |
| Linksys                           | 35        | 0.14%   |
| Aquantia                          | 27        | 0.1%    |
| IMC Networks                      | 25        | 0.1%    |
| Lenovo                            | 23        | 0.09%   |
| ICS Advent                        | 19        | 0.07%   |
| AVM                               | 19        | 0.07%   |
| Attansic Technology               | 17        | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 6453      | 21.36%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 1490      | 4.93%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 714       | 2.36%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 492       | 1.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 491       | 1.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 477       | 1.58%   |
| Intel Wi-Fi 6 AX200                                                     | 438       | 1.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 422       | 1.4%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 399       | 1.32%   |
| Intel Wireless 7260                                                     | 354       | 1.17%   |
| Intel Wireless 7265                                                     | 309       | 1.02%   |
| Intel Wireless 8265 / 8275                                              | 307       | 1.02%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 273       | 0.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 266       | 0.88%   |
| Intel Wi-Fi 6 AX201                                                     | 251       | 0.83%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 244       | 0.81%   |
| Intel Wireless 3165                                                     | 236       | 0.78%   |
| Realtek RTL8125 2.5GbE Controller                                       | 230       | 0.76%   |
| Intel Ethernet Connection (2) I219-V                                    | 228       | 0.75%   |
| Intel Wireless 8260                                                     | 225       | 0.74%   |
| Intel Ethernet Connection I217-LM                                       | 224       | 0.74%   |
| Intel I211 Gigabit Network Connection                                   | 220       | 0.73%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 217       | 0.72%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 211       | 0.7%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 199       | 0.66%   |
| Broadcom BCM43142 802.11b/g/n                                           | 191       | 0.63%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 185       | 0.61%   |
| Ralink MT7601U Wireless Adapter                                         | 179       | 0.59%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 168       | 0.56%   |
| Realtek 802.11ac NIC                                                    | 166       | 0.55%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 166       | 0.55%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 165       | 0.55%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 162       | 0.54%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 159       | 0.53%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 157       | 0.52%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 157       | 0.52%   |
| Intel Wireless 3160                                                     | 154       | 0.51%   |
| Nvidia MCP61 Ethernet                                                   | 143       | 0.47%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 140       | 0.46%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 139       | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 4892      | 35.66%  |
| Qualcomm Atheros                      | 2751      | 20.05%  |
| Realtek Semiconductor                 | 2615      | 19.06%  |
| Broadcom                              | 1073      | 7.82%   |
| Ralink Technology                     | 437       | 3.19%   |
| Ralink                                | 373       | 2.72%   |
| TP-Link                               | 334       | 2.43%   |
| Broadcom Limited                      | 218       | 1.59%   |
| MediaTek                              | 203       | 1.48%   |
| Qualcomm Atheros Communications       | 101       | 0.74%   |
| NetGear                               | 83        | 0.61%   |
| D-Link                                | 69        | 0.5%    |
| ASUSTek Computer                      | 68        | 0.5%    |
| Sierra Wireless                       | 53        | 0.39%   |
| D-Link System                         | 47        | 0.34%   |
| Edimax Technology                     | 46        | 0.34%   |
| Microsoft                             | 36        | 0.26%   |
| Belkin Components                     | 36        | 0.26%   |
| Marvell Technology Group              | 35        | 0.26%   |
| Dell                                  | 35        | 0.26%   |
| Linksys                               | 33        | 0.24%   |
| IMC Networks                          | 25        | 0.18%   |
| AVM                                   | 19        | 0.14%   |
| Qualcomm                              | 13        | 0.09%   |
| Sitecom Europe                        | 12        | 0.09%   |
| Hewlett-Packard                       | 9         | 0.07%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 9         | 0.07%   |
| ZyDAS                                 | 7         | 0.05%   |
| Realtek                               | 7         | 0.05%   |
| Fibocom                               | 7         | 0.05%   |
| TRENDnet                              | 6         | 0.04%   |
| Texas Instruments                     | 6         | 0.04%   |
| Micro Star International              | 6         | 0.04%   |
| Gemtek                                | 6         | 0.04%   |
| Accton Technology                     | 6         | 0.04%   |
| ZyXEL Communications                  | 5         | 0.04%   |
| Philips (or NXP)                      | 3         | 0.02%   |
| Mercucys                              | 3         | 0.02%   |
| Fujitsu Siemens Computers             | 3         | 0.02%   |
| Z-Com                                 | 2         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 492       | 3.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 491       | 3.54%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 477       | 3.44%   |
| Intel Wi-Fi 6 AX200                                                     | 438       | 3.16%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 422       | 3.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 399       | 2.88%   |
| Intel Wireless 7260                                                     | 354       | 2.55%   |
| Intel Wireless 7265                                                     | 309       | 2.23%   |
| Intel Wireless 8265 / 8275                                              | 307       | 2.22%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 273       | 1.97%   |
| Intel Wi-Fi 6 AX201                                                     | 251       | 1.81%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 244       | 1.76%   |
| Intel Wireless 3165                                                     | 236       | 1.7%    |
| Intel Wireless 8260                                                     | 225       | 1.62%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 217       | 1.57%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 211       | 1.52%   |
| Broadcom BCM43142 802.11b/g/n                                           | 191       | 1.38%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 185       | 1.33%   |
| Ralink MT7601U Wireless Adapter                                         | 179       | 1.29%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 168       | 1.21%   |
| Realtek 802.11ac NIC                                                    | 166       | 1.2%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 166       | 1.2%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 165       | 1.19%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 159       | 1.15%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 157       | 1.13%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 157       | 1.13%   |
| Intel Wireless 3160                                                     | 154       | 1.11%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 140       | 1.01%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 139       | 1%      |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 135       | 0.97%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 129       | 0.93%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 123       | 0.89%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 120       | 0.87%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 114       | 0.82%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 114       | 0.82%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 113       | 0.82%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 112       | 0.81%   |
| Intel WiFi Link 5100                                                    | 109       | 0.79%   |
| Intel Wireless-AC 9260                                                  | 104       | 0.75%   |
| Intel Centrino Wireless-N 2230                                          | 103       | 0.74%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 8647      | 55%     |
| Intel                                  | 3534      | 22.48%  |
| Qualcomm Atheros                       | 1034      | 6.58%   |
| Broadcom                               | 728       | 4.63%   |
| Marvell Technology Group               | 358       | 2.28%   |
| Nvidia                                 | 314       | 2%      |
| Broadcom Limited                       | 166       | 1.06%   |
| ASIX Electronics                       | 117       | 0.74%   |
| Samsung Electronics                    | 100       | 0.64%   |
| Xiaomi                                 | 87        | 0.55%   |
| JMicron Technology                     | 66        | 0.42%   |
| Silicon Integrated Systems [SiS]       | 61        | 0.39%   |
| VIA Technologies                       | 58        | 0.37%   |
| Huawei Technologies                    | 48        | 0.31%   |
| DisplayLink                            | 36        | 0.23%   |
| MediaTek                               | 30        | 0.19%   |
| Qualcomm                               | 28        | 0.18%   |
| Aquantia                               | 27        | 0.17%   |
| Motorola PCS                           | 26        | 0.17%   |
| Lenovo                                 | 23        | 0.15%   |
| D-Link System                          | 22        | 0.14%   |
| ICS Advent                             | 19        | 0.12%   |
| Attansic Technology                    | 17        | 0.11%   |
| Hewlett-Packard                        | 16        | 0.1%    |
| OPPO Electronics                       | 15        | 0.1%    |
| Google                                 | 15        | 0.1%    |
| Sundance Technology Inc / IC Plus      | 11        | 0.07%   |
| Apple                                  | 10        | 0.06%   |
| TP-Link                                | 9         | 0.06%   |
| Sony Ericsson Mobile Communications AB | 6         | 0.04%   |
| Microsoft                              | 6         | 0.04%   |
| LG Electronics                         | 6         | 0.04%   |
| HMD Global                             | 6         | 0.04%   |
| ZTE WCDMA Technologies MSM             | 5         | 0.03%   |
| T & A Mobile Phones                    | 5         | 0.03%   |
| OnePlus Technology (Shenzhen)          | 4         | 0.03%   |
| Microchip Technology                   | 4         | 0.03%   |
| HTC (High Tech Computer)               | 4         | 0.03%   |
| 3Com                                   | 4         | 0.03%   |
| Spreadtrum Communications              | 3         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6453      | 40.39%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1490      | 9.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 714       | 4.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 266       | 1.66%   |
| Realtek RTL8125 2.5GbE Controller                                 | 230       | 1.44%   |
| Intel Ethernet Connection (2) I219-V                              | 228       | 1.43%   |
| Intel Ethernet Connection I217-LM                                 | 224       | 1.4%    |
| Intel I211 Gigabit Network Connection                             | 220       | 1.38%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 199       | 1.25%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 162       | 1.01%   |
| Nvidia MCP61 Ethernet                                             | 143       | 0.9%    |
| Intel 82579V Gigabit Network Connection                           | 134       | 0.84%   |
| Intel 82577LM Gigabit Network Connection                          | 130       | 0.81%   |
| Intel Ethernet Controller I225-V                                  | 123       | 0.77%   |
| Intel Ethernet Connection (7) I219-V                              | 109       | 0.68%   |
| Intel Ethernet Connection I218-LM                                 | 107       | 0.67%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 107       | 0.67%   |
| Intel Ethernet Connection I217-V                                  | 105       | 0.66%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 103       | 0.64%   |
| Intel Ethernet Connection I219-LM                                 | 103       | 0.64%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 97        | 0.61%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 95        | 0.59%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 95        | 0.59%   |
| ASIX AX88179 Gigabit Ethernet                                     | 88        | 0.55%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 86        | 0.54%   |
| Intel 82567LM Gigabit Network Connection                          | 86        | 0.54%   |
| Intel Ethernet Connection (4) I219-LM                             | 84        | 0.53%   |
| Intel Ethernet Connection (2) I219-LM                             | 84        | 0.53%   |
| Intel Ethernet Connection (3) I218-LM                             | 82        | 0.51%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 80        | 0.5%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 80        | 0.5%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 79        | 0.49%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 74        | 0.46%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 73        | 0.46%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 68        | 0.43%   |
| Intel Ethernet Connection (2) I218-V                              | 67        | 0.42%   |
| Intel 82574L Gigabit Network Connection                           | 61        | 0.38%   |
| Nvidia MCP79 Ethernet                                             | 60        | 0.38%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 60        | 0.38%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 59        | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 14946     | 53.17%  |
| WiFi     | 12796     | 45.52%  |
| Modem    | 316       | 1.12%   |
| Unknown  | 51        | 0.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 9963      | 56.81%  |
| Ethernet | 7560      | 43.11%  |
| Unknown  | 8         | 0.05%   |
| Modem    | 6         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 9487      | 56.41%  |
| 1     | 6745      | 40.11%  |
| 0     | 312       | 1.86%   |
| 3     | 232       | 1.38%   |
| 4     | 27        | 0.16%   |
| 5     | 7         | 0.04%   |
| 6     | 4         | 0.02%   |
| 7     | 3         | 0.02%   |
| 10    | 1         | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 13407     | 78.43%  |
| Yes     | 3686      | 21.56%  |
| Unknown | 1         | 0.01%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 3588      | 38.62%  |
| Realtek Semiconductor           | 1106      | 11.91%  |
| Qualcomm Atheros Communications | 892       | 9.6%    |
| Cambridge Silicon Radio         | 715       | 7.7%    |
| Broadcom                        | 620       | 6.67%   |
| Lite-On Technology              | 395       | 4.25%   |
| IMC Networks                    | 368       | 3.96%   |
| Apple                           | 324       | 3.49%   |
| Foxconn / Hon Hai               | 266       | 2.86%   |
| Dell                            | 160       | 1.72%   |
| ASUSTek Computer                | 155       | 1.67%   |
| Hewlett-Packard                 | 131       | 1.41%   |
| Ralink                          | 113       | 1.22%   |
| Toshiba                         | 89        | 0.96%   |
| MediaTek                        | 37        | 0.4%    |
| Realtek                         | 36        | 0.39%   |
| Alps Electric                   | 35        | 0.38%   |
| Foxconn International           | 34        | 0.37%   |
| Ralink Technology               | 31        | 0.33%   |
| Marvell Semiconductor           | 31        | 0.33%   |
| TP-Link                         | 21        | 0.23%   |
| Integrated System Solution      | 18        | 0.19%   |
| Taiyo Yuden                     | 13        | 0.14%   |
| Qcom                            | 12        | 0.13%   |
| Edimax Technology               | 11        | 0.12%   |
| Chicony Electronics             | 11        | 0.12%   |
| Belkin Components               | 10        | 0.11%   |
| Smart Modular Technologies      | 9         | 0.1%    |
| Micro Star International        | 7         | 0.08%   |
| Dynex                           | 7         | 0.08%   |
| Askey Computer                  | 7         | 0.08%   |
| Conwise Technology              | 5         | 0.05%   |
| Opticis                         | 4         | 0.04%   |
| Logitech                        | 4         | 0.04%   |
| Unknown                         | 4         | 0.04%   |
| USI                             | 3         | 0.03%   |
| Fujitsu                         | 3         | 0.03%   |
| Primax Electronics              | 2         | 0.02%   |
| Motorola PCS                    | 2         | 0.02%   |
| Sitecom Europe                  | 1         | 0.01%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 1532      | 16.47%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 714       | 7.68%   |
| Realtek Bluetooth Radio                             | 662       | 7.12%   |
| Intel AX201 Bluetooth                               | 501       | 5.39%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 480       | 5.16%   |
| Intel AX200 Bluetooth                               | 408       | 4.39%   |
| Qualcomm Atheros  Bluetooth Device                  | 401       | 4.31%   |
| Realtek  Bluetooth 4.2 Adapter                      | 320       | 3.44%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 173       | 1.86%   |
| Intel Wireless-AC 3168 Bluetooth                    | 158       | 1.7%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 154       | 1.66%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 139       | 1.49%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 136       | 1.46%   |
| Apple Bluetooth Host Controller                     | 124       | 1.33%   |
| IMC Networks Bluetooth Device                       | 120       | 1.29%   |
| Ralink RT3290 Bluetooth                             | 113       | 1.22%   |
| IMC Networks Bluetooth Radio                        | 110       | 1.18%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 101       | 1.09%   |
| Apple Bluetooth USB Host Controller                 | 95        | 1.02%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 88        | 0.95%   |
| Lite-On Bluetooth Device                            | 86        | 0.92%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 86        | 0.92%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 83        | 0.89%   |
| Intel AX210 Bluetooth                               | 83        | 0.89%   |
| Foxconn / Hon Hai Bluetooth Device                  | 80        | 0.86%   |
| Lite-On Atheros AR3012 Bluetooth                    | 74        | 0.8%    |
| Intel Bluetooth Device                              | 71        | 0.76%   |
| HP Broadcom 2070 Bluetooth Combo                    | 68        | 0.73%   |
| Broadcom BCM2045B (BDC-2.1)                         | 65        | 0.7%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 57        | 0.61%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 56        | 0.6%    |
| Broadcom BCM2045 Bluetooth                          | 55        | 0.59%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 54        | 0.58%   |
| Dell DW375 Bluetooth Module                         | 54        | 0.58%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 53        | 0.57%   |
| IMC Networks Wireless_Device                        | 50        | 0.54%   |
| Apple Bluetooth HCI                                 | 49        | 0.53%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 47        | 0.51%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 45        | 0.48%   |
| Realtek RTL8821A Bluetooth                          | 42        | 0.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 12118     | 53.96%  |
| AMD                              | 4735      | 21.08%  |
| Nvidia                           | 3536      | 15.74%  |
| C-Media Electronics              | 381       | 1.7%    |
| Creative Labs                    | 173       | 0.77%   |
| Logitech                         | 164       | 0.73%   |
| Texas Instruments                | 88        | 0.39%   |
| VIA Technologies                 | 79        | 0.35%   |
| Silicon Integrated Systems [SiS] | 79        | 0.35%   |
| Generalplus Technology           | 77        | 0.34%   |
| JMTek                            | 71        | 0.32%   |
| GN Netcom                        | 60        | 0.27%   |
| Kingston Technology              | 58        | 0.26%   |
| Creative Technology              | 45        | 0.2%    |
| Plantronics                      | 43        | 0.19%   |
| Realtek Semiconductor            | 37        | 0.16%   |
| Razer USA                        | 34        | 0.15%   |
| SteelSeries ApS                  | 30        | 0.13%   |
| Corsair                          | 28        | 0.12%   |
| ASUSTek Computer                 | 28        | 0.12%   |
| Lenovo                           | 27        | 0.12%   |
| Focusrite-Novation               | 25        | 0.11%   |
| Apple                            | 22        | 0.1%    |
| Tenx Technology                  | 19        | 0.08%   |
| Samson Technologies              | 18        | 0.08%   |
| Sennheiser Communications        | 17        | 0.08%   |
| Microsoft                        | 17        | 0.08%   |
| Hewlett-Packard                  | 16        | 0.07%   |
| Micro Star International         | 14        | 0.06%   |
| Dell                             | 14        | 0.06%   |
| M-Audio                          | 12        | 0.05%   |
| Jieli Technology                 | 12        | 0.05%   |
| Blue Microphones                 | 12        | 0.05%   |
| BEHRINGER International          | 12        | 0.05%   |
| XMOS                             | 11        | 0.05%   |
| Sony                             | 11        | 0.05%   |
| Yamaha                           | 9         | 0.04%   |
| Trust                            | 9         | 0.04%   |
| Ensoniq                          | 9         | 0.04%   |
| KTMicro                          | 8         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1376      | 5.15%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1348      | 5.05%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 1073      | 4.02%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 1058      | 3.96%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 891       | 3.34%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 838       | 3.14%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 750       | 2.81%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 681       | 2.55%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 672       | 2.52%   |
| AMD FCH Azalia Controller                                                                         | 641       | 2.4%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 600       | 2.25%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 541       | 2.03%   |
| Intel 8 Series HD Audio Controller                                                                | 498       | 1.86%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 495       | 1.85%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 429       | 1.61%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 426       | 1.6%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 412       | 1.54%   |
| Intel Cannon Lake PCH cAVS                                                                        | 411       | 1.54%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 357       | 1.34%   |
| Intel Broadwell-U Audio Controller                                                                | 344       | 1.29%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 333       | 1.25%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 319       | 1.19%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 311       | 1.16%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 303       | 1.13%   |
| AMD Kabini HDMI/DP Audio                                                                          | 303       | 1.13%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 287       | 1.07%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 281       | 1.05%   |
| Intel 200 Series PCH HD Audio                                                                     | 267       | 1%      |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 264       | 0.99%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 258       | 0.97%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 246       | 0.92%   |
| Nvidia High Definition Audio Controller                                                           | 244       | 0.91%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 243       | 0.91%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 228       | 0.85%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 227       | 0.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 209       | 0.78%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 189       | 0.71%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 179       | 0.67%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 177       | 0.66%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 174       | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1829      | 21.03%  |
| SK hynix            | 1520      | 17.48%  |
| Kingston            | 964       | 11.08%  |
| Unknown             | 896       | 10.3%   |
| Micron Technology   | 784       | 9.01%   |
| Crucial             | 521       | 5.99%   |
| Corsair             | 436       | 5.01%   |
| G.Skill             | 272       | 3.13%   |
| A-DATA Technology   | 169       | 1.94%   |
| Ramaxel Technology  | 168       | 1.93%   |
| Elpida              | 167       | 1.92%   |
| Unknown (ABCD)      | 120       | 1.38%   |
| Nanya Technology    | 117       | 1.35%   |
| Smart               | 84        | 0.97%   |
| Team                | 65        | 0.75%   |
| Patriot             | 54        | 0.62%   |
| Unknown             | 45        | 0.52%   |
| GOODRAM             | 34        | 0.39%   |
| Transcend           | 33        | 0.38%   |
| AMD                 | 25        | 0.29%   |
| Teikon              | 24        | 0.28%   |
| Apacer              | 24        | 0.28%   |
| ASint Technology    | 16        | 0.18%   |
| PNY                 | 15        | 0.17%   |
| Avant               | 14        | 0.16%   |
| Sesame              | 13        | 0.15%   |
| Qimonda             | 13        | 0.15%   |
| Unifosa             | 12        | 0.14%   |
| Kingmax             | 12        | 0.14%   |
| Silicon Power       | 11        | 0.13%   |
| Smart Brazil        | 10        | 0.11%   |
| Kllisre             | 10        | 0.11%   |
| Multilaser          | 9         | 0.1%    |
| Goldkey             | 8         | 0.09%   |
| GeIL                | 8         | 0.09%   |
| Timetec             | 7         | 0.08%   |
| PUSKILL             | 6         | 0.07%   |
| High Bridge         | 6         | 0.07%   |
| fef5                | 6         | 0.07%   |
| CSX                 | 6         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 95        | 1.02%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 79        | 0.84%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 73        | 0.78%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 73        | 0.78%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 64        | 0.68%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 61        | 0.65%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 59        | 0.63%   |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 58        | 0.62%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 57        | 0.61%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 57        | 0.61%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 52        | 0.56%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 50        | 0.53%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 50        | 0.53%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 50        | 0.53%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 49        | 0.52%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 47        | 0.5%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 45        | 0.48%   |
| Unknown                                                          | 45        | 0.48%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 44        | 0.47%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 44        | 0.47%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 42        | 0.45%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 40        | 0.43%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 38        | 0.41%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 38        | 0.41%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 36        | 0.38%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s         | 34        | 0.36%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 33        | 0.35%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 32        | 0.34%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 32        | 0.34%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 32        | 0.34%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 30        | 0.32%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 29        | 0.31%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 29        | 0.31%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 29        | 0.31%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 28        | 0.3%    |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 28        | 0.3%    |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 27        | 0.29%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 27        | 0.29%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 27        | 0.29%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 27        | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind         | Computers | Percent |
|--------------|-----------|---------|
| DDR4         | 3039      | 40.64%  |
| DDR3         | 2987      | 39.94%  |
| DDR2         | 385       | 5.15%   |
| LPDDR4       | 299       | 4%      |
| SDRAM        | 240       | 3.21%   |
| Unknown      | 227       | 3.04%   |
| LPDDR3       | 140       | 1.87%   |
| DDR          | 60        | 0.8%    |
| DDR5         | 50        | 0.67%   |
| LPDDR5       | 28        | 0.37%   |
| DRAM         | 19        | 0.25%   |
| RAM          | 2         | 0.03%   |
| EEPROM       | 1         | 0.01%   |
| DDR2 FB-DIMM | 1         | 0.01%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 4438      | 59.83%  |
| DIMM         | 2519      | 33.96%  |
| Row Of Chips | 388       | 5.23%   |
| Chip         | 31        | 0.42%   |
| Unknown      | 31        | 0.42%   |
| FB-DIMM      | 8         | 0.11%   |
| RIMM         | 3         | 0.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 2937      | 36.05%  |
| 4096  | 2566      | 31.5%   |
| 2048  | 1244      | 15.27%  |
| 16384 | 906       | 11.12%  |
| 1024  | 287       | 3.52%   |
| 32768 | 161       | 1.98%   |
| 512   | 32        | 0.39%   |
| 1536  | 5         | 0.06%   |
| 256   | 4         | 0.05%   |
| 3072  | 1         | 0.01%   |
| 16    | 1         | 0.01%   |
| 8     | 1         | 0.01%   |
| 1     | 1         | 0.01%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 1926      | 23.66%  |
| 2667    | 1014      | 12.45%  |
| 3200    | 979       | 12.02%  |
| 1333    | 694       | 8.52%   |
| 2400    | 620       | 7.61%   |
| 2133    | 344       | 4.23%   |
| 1334    | 322       | 3.95%   |
| 800     | 208       | 2.55%   |
| 667     | 206       | 2.53%   |
| 3600    | 178       | 2.19%   |
| Unknown | 175       | 2.15%   |
| 1867    | 145       | 1.78%   |
| 1067    | 114       | 1.4%    |
| 3266    | 97        | 1.19%   |
| 4267    | 88        | 1.08%   |
| 1066    | 84        | 1.03%   |
| 4199    | 61        | 0.75%   |
| 3000    | 61        | 0.75%   |
| 1866    | 58        | 0.71%   |
| 2933    | 51        | 0.63%   |
| 1800    | 50        | 0.61%   |
| 4800    | 44        | 0.54%   |
| 2048    | 44        | 0.54%   |
| 3400    | 40        | 0.49%   |
| 3733    | 38        | 0.47%   |
| 6400    | 29        | 0.36%   |
| 2666    | 28        | 0.34%   |
| 3800    | 26        | 0.32%   |
| 8400    | 24        | 0.29%   |
| 533     | 24        | 0.29%   |
| 2800    | 23        | 0.28%   |
| 400     | 23        | 0.28%   |
| 3866    | 21        | 0.26%   |
| 3533    | 21        | 0.26%   |
| 3466    | 21        | 0.26%   |
| 975     | 20        | 0.25%   |
| 333     | 20        | 0.25%   |
| 4266    | 14        | 0.17%   |
| 1639    | 14        | 0.17%   |
| 3666    | 12        | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Hewlett-Packard          | 227       | 35.86%  |
| Brother Industries       | 131       | 20.7%   |
| Canon                    | 105       | 16.59%  |
| Samsung Electronics      | 56        | 8.85%   |
| Seiko Epson              | 50        | 7.9%    |
| QinHeng Electronics      | 9         | 1.42%   |
| Kyocera                  | 8         | 1.26%   |
| Prolific Technology      | 7         | 1.11%   |
| Dymo-CoStar              | 5         | 0.79%   |
| Xerox                    | 4         | 0.63%   |
| Ricoh                    | 4         | 0.63%   |
| Pantum                   | 4         | 0.63%   |
| Lexmark International    | 4         | 0.63%   |
| Panasonic (Matsushita)   | 3         | 0.47%   |
| Oki Data                 | 3         | 0.47%   |
| Dell                     | 3         | 0.47%   |
| Seiko Instruments        | 2         | 0.32%   |
| STMicroelectronics       | 1         | 0.16%   |
| Sato                     | 1         | 0.16%   |
| NXP Semiconductors       | 1         | 0.16%   |
| Magic Control Technology | 1         | 0.16%   |
| Fuji Xerox               | 1         | 0.16%   |
| BIXOLON                  | 1         | 0.16%   |
| Agere Systems (Lucent)   | 1         | 0.16%   |
| Unknown                  | 1         | 0.16%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Samsung M2020 Series               | 10        | 1.56%   |
| HP LaserJet 1020                   | 10        | 1.56%   |
| QinHeng CH340S                     | 9         | 1.41%   |
| Samsung M2070 Series               | 8         | 1.25%   |
| Seiko Epson ET-2710 Series         | 7         | 1.1%    |
| Prolific PL2305 Parallel Port      | 7         | 1.1%    |
| HP DeskJet 2700 series             | 7         | 1.1%    |
| HP DeskJet 2620 All-in-One Printer | 7         | 1.1%    |
| Canon LiDE 400                     | 7         | 1.1%    |
| Brother Printer                    | 7         | 1.1%    |
| HP LaserJet Professional P1102w    | 6         | 0.94%   |
| HP LaserJet 1018                   | 6         | 0.94%   |
| HP Deskjet 2050 J510               | 6         | 0.94%   |
| Canon PIXMA MG2500 Series          | 6         | 0.94%   |
| Samsung SCX-3400 Series            | 5         | 0.78%   |
| HP OfficeJet 5200 series           | 5         | 0.78%   |
| HP Officejet 4620 series           | 5         | 0.78%   |
| HP Officejet 4500 G510n-z          | 5         | 0.78%   |
| HP LaserJet Professional P 1102w   | 5         | 0.78%   |
| HP LaserJet P1005                  | 5         | 0.78%   |
| HP ENVY 5000 series                | 5         | 0.78%   |
| HP ENVY 4520 series                | 5         | 0.78%   |
| HP DeskJet 3630 series             | 5         | 0.78%   |
| HP Deskjet 2540 series             | 5         | 0.78%   |
| HP DeskJet 2130 series             | 5         | 0.78%   |
| Brother HL-L2360D series           | 5         | 0.78%   |
| Brother HL-1210W series            | 5         | 0.78%   |
| Seiko Epson L210 Series            | 4         | 0.63%   |
| Samsung M267x 287x Series          | 4         | 0.63%   |
| Samsung C48x Series                | 4         | 0.63%   |
| HP OfficeJet 3830 series           | 4         | 0.63%   |
| HP LaserJet P1102                  | 4         | 0.63%   |
| HP Ink Tank Wireless 410 series    | 4         | 0.63%   |
| HP DeskJet F4200 series            | 4         | 0.63%   |
| HP Deskjet 1000 J110 series        | 4         | 0.63%   |
| Canon PIXMA MX920 Series           | 4         | 0.63%   |
| Brother MFC-J497DW                 | 4         | 0.63%   |
| Brother HL-L2340D series           | 4         | 0.63%   |
| Brother HL-1110 series             | 4         | 0.63%   |
| Brother DCP-7055 scanner/printer   | 4         | 0.63%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Canon                       | 99        | 61.49%  |
| Seiko Epson                 | 29        | 18.01%  |
| Hewlett-Packard             | 17        | 10.56%  |
| Mustek Systems              | 5         | 3.11%   |
| AGFA-Gevaert NV             | 3         | 1.86%   |
| Ultima Electronics          | 2         | 1.24%   |
| Acer Peripherals (now BenQ) | 2         | 1.24%   |
| UMAX                        | 1         | 0.62%   |
| Salix Technology            | 1         | 0.62%   |
| Microtek International      | 1         | 0.62%   |
| Canon Electronics           | 1         | 0.62%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                                               | 14        | 8.64%   |
| Canon CanoScan LIDE 25                                                                | 11        | 6.79%   |
| Canon CanoScan LiDE 120                                                               | 11        | 6.79%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 9         | 5.56%   |
| Canon CanoScan LiDE 220                                                               | 9         | 5.56%   |
| Canon CanoScan LiDE 700F                                                              | 6         | 3.7%    |
| Canon CanoScan LiDE 210                                                               | 6         | 3.7%    |
| Canon CanoScan LiDE 60                                                                | 5         | 3.09%   |
| Canon CanoScan LiDE 100                                                               | 5         | 3.09%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]                                           | 4         | 2.47%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                   | 4         | 2.47%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 3         | 1.85%   |
| Mustek Systems ScanExpress 1200 UB                                                    | 3         | 1.85%   |
| HP ScanJet 2400c                                                                      | 3         | 1.85%   |
| Canon CanoScan N650U/N656U                                                            | 3         | 1.85%   |
| Canon CanoScan LiDE 90                                                                | 3         | 1.85%   |
| Canon CanoScan LiDE 200                                                               | 3         | 1.85%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 2         | 1.23%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 2         | 1.23%   |
| Seiko Epson GT-6600U [Perfection 610]                                                 | 2         | 1.23%   |
| Seiko Epson ES-D200 [GT-S50]                                                          | 2         | 1.23%   |
| Mustek Systems SNAPSCAN e22                                                           | 2         | 1.23%   |
| HP ScanJet 3800c                                                                      | 2         | 1.23%   |
| HP Scanjet 300                                                                        | 2         | 1.23%   |
| HP ScanJet 2200c                                                                      | 2         | 1.23%   |
| Canon CanoScan N1240U/LiDE 30                                                         | 2         | 1.23%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                                | 2         | 1.23%   |
| Canon CanoScan 9000F Mark II                                                          | 2         | 1.23%   |
| AGFA-Gevaert NV SnapScan 1212U (?)                                                    | 2         | 1.23%   |
| Acer Peripherals (now BenQ) S2W 3300U/4300U                                           | 2         | 1.23%   |
| UMAX Astra 4400/4450                                                                  | 1         | 0.62%   |
| Seiko Epson Stylus Photo RX500/510                                                    | 1         | 0.62%   |
| Seiko Epson GT-X900 [Perfection V700/V750 Photo]                                      | 1         | 0.62%   |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]                                           | 1         | 0.62%   |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 1         | 0.62%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 1         | 0.62%   |
| Seiko Epson GT-F600 [Perfection 4180]                                                 | 1         | 0.62%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                                         | 1         | 0.62%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                                    | 1         | 0.62%   |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]                                         | 1         | 0.62%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 2201      | 22.13%  |
| Microdia                               | 776       | 7.8%    |
| IMC Networks                           | 744       | 7.48%   |
| Realtek Semiconductor                  | 689       | 6.93%   |
| Logitech                               | 558       | 5.61%   |
| Sunplus Innovation Technology          | 542       | 5.45%   |
| Quanta                                 | 455       | 4.57%   |
| Cheng Uei Precision Industry (Foxlink) | 440       | 4.42%   |
| Bison Electronics                      | 409       | 4.11%   |
| Suyin                                  | 396       | 3.98%   |
| Acer                                   | 261       | 2.62%   |
| Apple                                  | 259       | 2.6%    |
| Syntek                                 | 241       | 2.42%   |
| Silicon Motion                         | 215       | 2.16%   |
| Lite-On Technology                     | 174       | 1.75%   |
| Alcor Micro                            | 166       | 1.67%   |
| Samsung Electronics                    | 129       | 1.3%    |
| Microsoft                              | 110       | 1.11%   |
| Z-Star Microelectronics                | 101       | 1.02%   |
| Luxvisions Innotech Limited            | 100       | 1.01%   |
| Ricoh                                  | 99        | 1%      |
| Generalplus Technology                 | 55        | 0.55%   |
| Lenovo                                 | 54        | 0.54%   |
| Importek                               | 47        | 0.47%   |
| ALi                                    | 42        | 0.42%   |
| Sonix Technology                       | 37        | 0.37%   |
| Primax Electronics                     | 35        | 0.35%   |
| GEMBIRD                                | 33        | 0.33%   |
| USB Camera                             | 30        | 0.3%    |
| Creative Technology                    | 30        | 0.3%    |
| KYE Systems (Mouse Systems)            | 29        | 0.29%   |
| ARC International                      | 25        | 0.25%   |
| OmniVision Technologies                | 23        | 0.23%   |
| DigiTech                               | 20        | 0.2%    |
| Jieli Technology                       | 19        | 0.19%   |
| Aveo Technology                        | 19        | 0.19%   |
| SunplusIT                              | 18        | 0.18%   |
| Y Media                                | 16        | 0.16%   |
| Sunplus Technology                     | 16        | 0.16%   |
| LG Electronics                         | 15        | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 321       | 3.21%   |
| Chicony HD WebCam                                | 228       | 2.28%   |
| Microdia Integrated_Webcam_HD                    | 204       | 2.04%   |
| IMC Networks USB2.0 HD UVC WebCam                | 164       | 1.64%   |
| Realtek Integrated_Webcam_HD                     | 162       | 1.62%   |
| Sunplus Integrated_Webcam_HD                     | 143       | 1.43%   |
| IMC Networks Integrated Camera                   | 138       | 1.38%   |
| Logitech Webcam C270                             | 131       | 1.31%   |
| Samsung Galaxy A5 (MTP)                          | 126       | 1.26%   |
| Bison Integrated Camera                          | 100       | 1%      |
| Syntek Integrated Camera                         | 91        | 0.91%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 91        | 0.91%   |
| Apple Built-in iSight                            | 83        | 0.83%   |
| Chicony HP Truevision HD                         | 80        | 0.8%    |
| Chicony USB2.0 HD UVC WebCam                     | 79        | 0.79%   |
| Microdia Integrated Webcam                       | 78        | 0.78%   |
| Chicony HP HD Camera                             | 77        | 0.77%   |
| Chicony EasyCamera                               | 75        | 0.75%   |
| Chicony USB 2.0 Camera                           | 72        | 0.72%   |
| Sunplus HD WebCam                                | 67        | 0.67%   |
| Chicony HP TrueVision HD Camera                  | 67        | 0.67%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 67        | 0.67%   |
| Quanta HD User Facing                            | 66        | 0.66%   |
| Logitech HD Pro Webcam C920                      | 66        | 0.66%   |
| Chicony HP Webcam                                | 66        | 0.66%   |
| Quanta VGA WebCam                                | 65        | 0.65%   |
| Quanta HP TrueVision HD Camera                   | 65        | 0.65%   |
| Chicony HD User Facing                           | 65        | 0.65%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                  | 65        | 0.65%   |
| Realtek USB Camera                               | 61        | 0.61%   |
| Chicony Lenovo EasyCamera                        | 61        | 0.61%   |
| Chicony USB2.0 VGA UVC WebCam                    | 60        | 0.6%    |
| Alcor Micro USB 2.0 Camera                       | 60        | 0.6%    |
| Acer Integrated Camera                           | 60        | 0.6%    |
| Microdia Webcam Vitade AF                        | 59        | 0.59%   |
| Lite-On Integrated Camera                        | 59        | 0.59%   |
| Chicony VGA WebCam                               | 57        | 0.57%   |
| Chicony TOSHIBA Web Camera - HD                  | 57        | 0.57%   |
| Syntek Lenovo EasyCamera                         | 56        | 0.56%   |
| Apple FaceTime HD Camera                         | 54        | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 584       | 40.08%  |
| Synaptics                          | 272       | 18.67%  |
| AuthenTec                          | 138       | 9.47%   |
| Shenzhen Goodix Technology         | 137       | 9.4%    |
| Upek                               | 112       | 7.69%   |
| Elan Microelectronics              | 91        | 6.25%   |
| LighTuning Technology              | 68        | 4.67%   |
| STMicroelectronics                 | 27        | 1.85%   |
| Focal-systems.Corp                 | 8         | 0.55%   |
| Samsung Electronics                | 5         | 0.34%   |
| HOLTEK                             | 5         | 0.34%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 0.21%   |
| Next Biometrics                    | 2         | 0.14%   |
| Suprema                            | 1         | 0.07%   |
| Microsoft                          | 1         | 0.07%   |
| GDMicroelectronics                 | 1         | 0.07%   |
| Futronic Technology                | 1         | 0.07%   |
| Dell                               | 1         | 0.07%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 128       | 8.79%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 108       | 7.41%   |
| Shenzhen Goodix  Fingerprint Device                                        | 77        | 5.28%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 66        | 4.53%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 63        | 4.32%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 56        | 3.84%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 50        | 3.43%   |
| Shenzhen Goodix Fingerprint Reader                                         | 46        | 3.16%   |
| Validity Sensors Fingerprint scanner                                       | 42        | 2.88%   |
| Elan ELAN:Fingerprint                                                      | 42        | 2.88%   |
| AuthenTec AES2810                                                          | 42        | 2.88%   |
| Elan ELAN:ARM-M4                                                           | 40        | 2.75%   |
| Validity Sensors VFS491                                                    | 39        | 2.68%   |
| Validity Sensors Synaptics WBDI                                            | 39        | 2.68%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 31        | 2.13%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 30        | 2.06%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 29        | 1.99%   |
| Synaptics  WBDI                                                            | 28        | 1.92%   |
| STMicroelectronics Fingerprint Reader                                      | 27        | 1.85%   |
| AuthenTec AES1600                                                          | 27        | 1.85%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 26        | 1.78%   |
| Synaptics WBDI                                                             | 26        | 1.78%   |
| Synaptics UWP WBDI                                                         | 26        | 1.78%   |
| AuthenTec Fingerprint Sensor                                               | 24        | 1.65%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 23        | 1.58%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 22        | 1.51%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 21        | 1.44%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 21        | 1.44%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 21        | 1.44%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 21        | 1.44%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 19        | 1.3%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 19        | 1.3%    |
| LighTuning Fingerprint Reader                                              | 17        | 1.17%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 16        | 1.1%    |
| Shenzhen Goodix FingerPrint                                                | 14        | 0.96%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 13        | 0.89%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 11        | 0.75%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 10        | 0.69%   |
| Validity Sensors VFS Fingerprint sensor                                    | 9         | 0.62%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 9         | 0.62%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 312       | 44.83%  |
| Alcor Micro                       | 163       | 23.42%  |
| O2 Micro                          | 68        | 9.77%   |
| Upek                              | 48        | 6.9%    |
| Lenovo                            | 42        | 6.03%   |
| Gemalto (was Gemplus)             | 12        | 1.72%   |
| SCM Microsystems                  | 10        | 1.44%   |
| OmniKey                           | 10        | 1.44%   |
| Realtek Semiconductor             | 6         | 0.86%   |
| Reiner SCT Kartensysteme          | 3         | 0.43%   |
| In Focus Systems                  | 2         | 0.29%   |
| Giesecke & Devrient               | 2         | 0.29%   |
| Chicony Electronics               | 2         | 0.29%   |
| Cherry                            | 2         | 0.29%   |
| BIT4ID                            | 2         | 0.29%   |
| Aladdin Knowledge Systems         | 2         | 0.29%   |
| VASCO Data Security International | 1         | 0.14%   |
| Precise Biometrics                | 1         | 0.14%   |
| NXP Semiconductors                | 1         | 0.14%   |
| Hewlett-Packard                   | 1         | 0.14%   |
| Fujitsu Siemens Computers         | 1         | 0.14%   |
| Clay Logic                        | 1         | 0.14%   |
| C3PO                              | 1         | 0.14%   |
| Aladdin R.D.                      | 1         | 0.14%   |
| Aktiv                             | 1         | 0.14%   |
| Advanced Card Systems             | 1         | 0.14%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 153       | 21.98%  |
| Broadcom BCM5880 Secure Applications Processor                               | 144       | 20.69%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 66        | 9.48%   |
| Broadcom 5880                                                                | 59        | 8.48%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 55        | 7.9%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 48        | 6.9%    |
| Lenovo Integrated Smart Card Reader                                          | 42        | 6.03%   |
| Broadcom 58200                                                               | 39        | 5.6%    |
| O2 Micro Oz776 SmartCard Reader                                              | 13        | 1.87%   |
| Alcor Micro Watchdata W 1981                                                 | 9         | 1.29%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 7         | 1.01%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 6         | 0.86%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 5         | 0.72%   |
| OmniKey CardMan 3021 / 3121                                                  | 5         | 0.72%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 5         | 0.72%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 4         | 0.57%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 2         | 0.29%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 0.29%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 2         | 0.29%   |
| OmniKey CardMan 1021                                                         | 2         | 0.29%   |
| In Focus Systems EMV Smartcard Reader                                        | 2         | 0.29%   |
| Giesecke & Devrient StarSign CUT                                             | 2         | 0.29%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 2         | 0.29%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.29%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.14%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 0.14%   |
| Reiner SCT Kartensysteme tanJack USB                                         | 1         | 0.14%   |
| Precise Biometrics 200 MC FingerPrint and SmartCard Reader                   | 1         | 0.14%   |
| OmniKey CardMan 4321                                                         | 1         | 0.14%   |
| OmniKey CardMan 3121 (HID Technologies)                                      | 1         | 0.14%   |
| OmniKey 5422 Smartcard Reader                                                | 1         | 0.14%   |
| NXP Semiconductors PR533                                                     | 1         | 0.14%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.14%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.14%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.14%   |
| Cherry SmartTerminal XX44                                                    | 1         | 0.14%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.14%   |
| C3PO USB SMART CARD READER                                                   | 1         | 0.14%   |
| Bit4id miniLector-s                                                          | 1         | 0.14%   |
| BIT4ID miniLector EVO                                                        | 1         | 0.14%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 12047     | 70.19%  |
| 1     | 4030      | 23.48%  |
| 2     | 865       | 5.04%   |
| 3     | 150       | 0.87%   |
| 4     | 46        | 0.27%   |
| 5     | 15        | 0.09%   |
| 6     | 9         | 0.05%   |
| 7     | 2         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 1507      | 24.28%  |
| Fingerprint reader       | 1437      | 23.15%  |
| Net/wireless             | 1015      | 16.35%  |
| Chipcard                 | 651       | 10.49%  |
| Multimedia controller    | 366       | 5.9%    |
| Communication controller | 270       | 4.35%   |
| Bluetooth                | 200       | 3.22%   |
| Camera                   | 137       | 2.21%   |
| Sound                    | 116       | 1.87%   |
| Storage                  | 110       | 1.77%   |
| Unassigned class         | 76        | 1.22%   |
| Card reader              | 56        | 0.9%    |
| Net/ethernet             | 54        | 0.87%   |
| Network                  | 53        | 0.85%   |
| Modem                    | 52        | 0.84%   |
| Flash memory             | 27        | 0.43%   |
| Storage/ide              | 25        | 0.4%    |
| Storage/raid             | 23        | 0.37%   |
| Dvb card                 | 12        | 0.19%   |
| Firewire controller      | 6         | 0.1%    |
| Unclassified device      | 4         | 0.06%   |
| Tv card                  | 4         | 0.06%   |
| Storage/nvme             | 3         | 0.05%   |
| Storage/ata              | 2         | 0.03%   |
| Wireless                 | 1         | 0.02%   |

