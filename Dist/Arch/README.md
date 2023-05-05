Arch - Tested Hardware & Statistics
-----------------------------------

A project to collect tested hardware configurations for Arch.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Arch/Desktop/README.md) and [notebooks](/Dist/Arch/Notebook/README.md).

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

Total: 8629

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [0aa17c06c5](https://linux-hardware.org/?probe=0aa17c06c5) | Apr 30, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [bd460bdc62](https://linux-hardware.org/?probe=bd460bdc62) | Apr 30, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [edfcd7daa6](https://linux-hardware.org/?probe=edfcd7daa6) | Apr 30, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [3c321c476a](https://linux-hardware.org/?probe=3c321c476a) | Apr 30, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [408aa18a63](https://linux-hardware.org/?probe=408aa18a63) | Apr 30, 2023 |
| MSI           | B360M MORTAR                | Desktop     | [352a47b8a0](https://linux-hardware.org/?probe=352a47b8a0) | Apr 30, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [df9cc0160a](https://linux-hardware.org/?probe=df9cc0160a) | Apr 30, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [2f3308a2ee](https://linux-hardware.org/?probe=2f3308a2ee) | Apr 29, 2023 |
| Intel         | NUC6i7KYB H90766-405        | Mini pc     | [19bb30e27a](https://linux-hardware.org/?probe=19bb30e27a) | Apr 29, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [4a8b2ebf8a](https://linux-hardware.org/?probe=4a8b2ebf8a) | Apr 29, 2023 |
| Lenovo        | ThinkPad P1 Gen 5 21DCCT... | Notebook    | [34420e9478](https://linux-hardware.org/?probe=34420e9478) | Apr 28, 2023 |
| ASUSTek       | S550CM                      | Notebook    | [068365f788](https://linux-hardware.org/?probe=068365f788) | Apr 28, 2023 |
| Apple         | Mac-77EB7D7DAF985301 iMa... | All in one  | [c53a69bd72](https://linux-hardware.org/?probe=c53a69bd72) | Apr 28, 2023 |
| Dell          | Latitude 7210 2-in-1        | Tablet      | [2de1d6f6f5](https://linux-hardware.org/?probe=2de1d6f6f5) | Apr 28, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [96194bc912](https://linux-hardware.org/?probe=96194bc912) | Apr 28, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [5d0819f25c](https://linux-hardware.org/?probe=5d0819f25c) | Apr 28, 2023 |
| Dell          | 0XNNCJ A03                  | Server      | [ad555bfde2](https://linux-hardware.org/?probe=ad555bfde2) | Apr 27, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [6926565982](https://linux-hardware.org/?probe=6926565982) | Apr 27, 2023 |
| HP            | 82F2 A01                    | Desktop     | [ea8f7364db](https://linux-hardware.org/?probe=ea8f7364db) | Apr 27, 2023 |
| ASRock        | A330GC                      | Desktop     | [d1a2e8dd13](https://linux-hardware.org/?probe=d1a2e8dd13) | Apr 27, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [640a71aea3](https://linux-hardware.org/?probe=640a71aea3) | Apr 27, 2023 |
| Dell          | Latitude 7420               | Notebook    | [7ceeb888fd](https://linux-hardware.org/?probe=7ceeb888fd) | Apr 27, 2023 |
| Dell          | Latitude E5440              | Notebook    | [0217386dbe](https://linux-hardware.org/?probe=0217386dbe) | Apr 27, 2023 |
| Sony          | SVE11113FXW                 | Notebook    | [248c7717a4](https://linux-hardware.org/?probe=248c7717a4) | Apr 26, 2023 |
| Apple         | MacBookPro14,2              | Notebook    | [4e1caf5a7a](https://linux-hardware.org/?probe=4e1caf5a7a) | Apr 26, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [62996d1f05](https://linux-hardware.org/?probe=62996d1f05) | Apr 26, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [1ce9a878f3](https://linux-hardware.org/?probe=1ce9a878f3) | Apr 26, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [bd406c08f8](https://linux-hardware.org/?probe=bd406c08f8) | Apr 25, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [50930ebe57](https://linux-hardware.org/?probe=50930ebe57) | Apr 25, 2023 |
| Lenovo        | ThinkPad X250 20CMCTO1WW    | Notebook    | [bf207e9dc3](https://linux-hardware.org/?probe=bf207e9dc3) | Apr 25, 2023 |
| MSI           | Prestige 14 A12UC           | Notebook    | [137a3623dc](https://linux-hardware.org/?probe=137a3623dc) | Apr 25, 2023 |
| Gigabyte      | H87-D3H-CF                  | Desktop     | [b3a3115f0c](https://linux-hardware.org/?probe=b3a3115f0c) | Apr 25, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [7595e7d8f9](https://linux-hardware.org/?probe=7595e7d8f9) | Apr 25, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [3f8b64c10c](https://linux-hardware.org/?probe=3f8b64c10c) | Apr 25, 2023 |
| Notebook      | N85_N87HCHNHZ               | Notebook    | [ecb3270b4a](https://linux-hardware.org/?probe=ecb3270b4a) | Apr 24, 2023 |
| eMachines     | EMCP73VT-PM                 | Desktop     | [d1a5ad5a38](https://linux-hardware.org/?probe=d1a5ad5a38) | Apr 24, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [b4b468d0db](https://linux-hardware.org/?probe=b4b468d0db) | Apr 24, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [34278ef67e](https://linux-hardware.org/?probe=34278ef67e) | Apr 24, 2023 |
| HP            | EliteBook 650 15.6 inch ... | Notebook    | [78686e5784](https://linux-hardware.org/?probe=78686e5784) | Apr 24, 2023 |
| Acer          | One S1003                   | Tablet      | [140992e52d](https://linux-hardware.org/?probe=140992e52d) | Apr 24, 2023 |
| Intel         | HM570                       | Desktop     | [1220357b3d](https://linux-hardware.org/?probe=1220357b3d) | Apr 24, 2023 |
| HP            | 240 G4                      | Notebook    | [997e6e6a0b](https://linux-hardware.org/?probe=997e6e6a0b) | Apr 24, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [f76dc1b9b7](https://linux-hardware.org/?probe=f76dc1b9b7) | Apr 24, 2023 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [6cacf7a9f9](https://linux-hardware.org/?probe=6cacf7a9f9) | Apr 24, 2023 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [c11ea1fc19](https://linux-hardware.org/?probe=c11ea1fc19) | Apr 23, 2023 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [1a316c62a1](https://linux-hardware.org/?probe=1a316c62a1) | Apr 23, 2023 |
| Notebook      | N15_N17RD1                  | Notebook    | [8bba7a7447](https://linux-hardware.org/?probe=8bba7a7447) | Apr 23, 2023 |
| Notebook      | NH5x_NH7x_HHx_HJx_HKx       | Notebook    | [0be1fdd77a](https://linux-hardware.org/?probe=0be1fdd77a) | Apr 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [52001c8ac6](https://linux-hardware.org/?probe=52001c8ac6) | Apr 23, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [b18f893905](https://linux-hardware.org/?probe=b18f893905) | Apr 23, 2023 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | Notebook    | [5ecd3ed1bd](https://linux-hardware.org/?probe=5ecd3ed1bd) | Apr 23, 2023 |
| Acidanther... | Mac-CFF7D910A743CAAF iMa... | All in one  | [332429fc14](https://linux-hardware.org/?probe=332429fc14) | Apr 23, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [ef59f5ff9b](https://linux-hardware.org/?probe=ef59f5ff9b) | Apr 23, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [dfb9f87dad](https://linux-hardware.org/?probe=dfb9f87dad) | Apr 22, 2023 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [72088721ec](https://linux-hardware.org/?probe=72088721ec) | Apr 22, 2023 |
| HP            | 240 G4                      | Notebook    | [887b406c56](https://linux-hardware.org/?probe=887b406c56) | Apr 22, 2023 |
| ASRock        | H61M/U3S3                   | Desktop     | [8fd7aea5ea](https://linux-hardware.org/?probe=8fd7aea5ea) | Apr 22, 2023 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [5eb2235e10](https://linux-hardware.org/?probe=5eb2235e10) | Apr 22, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [0de425d51e](https://linux-hardware.org/?probe=0de425d51e) | Apr 21, 2023 |
| ASRock        | H510M-HVS R2.0              | Desktop     | [1de5b776a3](https://linux-hardware.org/?probe=1de5b776a3) | Apr 21, 2023 |
| Lenovo        | ThinkPad T530 24297ZG       | Notebook    | [3f01c5df6e](https://linux-hardware.org/?probe=3f01c5df6e) | Apr 21, 2023 |
| Lenovo        | ThinkPad T530 24297ZG       | Notebook    | [a5ef39681b](https://linux-hardware.org/?probe=a5ef39681b) | Apr 21, 2023 |
| HP            | 15                          | Notebook    | [4f563db114](https://linux-hardware.org/?probe=4f563db114) | Apr 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP47... | Convertible | [e76fb532be](https://linux-hardware.org/?probe=e76fb532be) | Apr 21, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [a7b05c2528](https://linux-hardware.org/?probe=a7b05c2528) | Apr 20, 2023 |
| Valve         | Jupiter                     | Notebook    | [a0ee1dbeff](https://linux-hardware.org/?probe=a0ee1dbeff) | Apr 20, 2023 |
| Lenovo        | 300e 2nd Gen 82GK           | Convertible | [54c7413bc5](https://linux-hardware.org/?probe=54c7413bc5) | Apr 20, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [68e853f4c1](https://linux-hardware.org/?probe=68e853f4c1) | Apr 20, 2023 |
| Intel         | X79-SERVER V1.1             | Desktop     | [384c50e703](https://linux-hardware.org/?probe=384c50e703) | Apr 20, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [509d9126e1](https://linux-hardware.org/?probe=509d9126e1) | Apr 19, 2023 |
| Acer          | Aspire A715-71G             | Notebook    | [83b48fff59](https://linux-hardware.org/?probe=83b48fff59) | Apr 19, 2023 |
| ASRock        | B250M Pro4                  | Desktop     | [5d27011671](https://linux-hardware.org/?probe=5d27011671) | Apr 19, 2023 |
| ASRock        | B550 Steel Legend           | Desktop     | [35534cbfba](https://linux-hardware.org/?probe=35534cbfba) | Apr 19, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [433c482314](https://linux-hardware.org/?probe=433c482314) | Apr 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [be217cbc1e](https://linux-hardware.org/?probe=be217cbc1e) | Apr 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [d5e90c4b14](https://linux-hardware.org/?probe=d5e90c4b14) | Apr 19, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [ed5cdbbcd0](https://linux-hardware.org/?probe=ed5cdbbcd0) | Apr 18, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [c00d85072e](https://linux-hardware.org/?probe=c00d85072e) | Apr 18, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [146c678131](https://linux-hardware.org/?probe=146c678131) | Apr 18, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [d1d3cf9928](https://linux-hardware.org/?probe=d1d3cf9928) | Apr 17, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [786daebed0](https://linux-hardware.org/?probe=786daebed0) | Apr 17, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [65a5b3f43d](https://linux-hardware.org/?probe=65a5b3f43d) | Apr 17, 2023 |
| Apple         | Mac-77EB7D7DAF985301 iMa... | All in one  | [39106da598](https://linux-hardware.org/?probe=39106da598) | Apr 17, 2023 |
| MSI           | GF75 Thin 9SC               | Notebook    | [40b6c3bad6](https://linux-hardware.org/?probe=40b6c3bad6) | Apr 17, 2023 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [b715989fc4](https://linux-hardware.org/?probe=b715989fc4) | Apr 16, 2023 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [213ac87204](https://linux-hardware.org/?probe=213ac87204) | Apr 16, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [7820a9b7bc](https://linux-hardware.org/?probe=7820a9b7bc) | Apr 16, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [4375bd0fb6](https://linux-hardware.org/?probe=4375bd0fb6) | Apr 16, 2023 |
| HP            | Pavilion dv6                | Notebook    | [fc41269cf8](https://linux-hardware.org/?probe=fc41269cf8) | Apr 16, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [8d18a06897](https://linux-hardware.org/?probe=8d18a06897) | Apr 16, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [9b05d61f11](https://linux-hardware.org/?probe=9b05d61f11) | Apr 16, 2023 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [040d876c1e](https://linux-hardware.org/?probe=040d876c1e) | Apr 16, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D6S... | Notebook    | [6686a91041](https://linux-hardware.org/?probe=6686a91041) | Apr 16, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [9b23be6c48](https://linux-hardware.org/?probe=9b23be6c48) | Apr 16, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [5ce7874f2e](https://linux-hardware.org/?probe=5ce7874f2e) | Apr 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [2fcbae14f2](https://linux-hardware.org/?probe=2fcbae14f2) | Apr 16, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [fff7f3dd1f](https://linux-hardware.org/?probe=fff7f3dd1f) | Apr 15, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [71e03c5459](https://linux-hardware.org/?probe=71e03c5459) | Apr 15, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [d582f92277](https://linux-hardware.org/?probe=d582f92277) | Apr 15, 2023 |
| Lenovo        | ThinkPad P52 20MAS1LH00     | Notebook    | [06ba20dc47](https://linux-hardware.org/?probe=06ba20dc47) | Apr 15, 2023 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [e9e05a1bb3](https://linux-hardware.org/?probe=e9e05a1bb3) | Apr 15, 2023 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [0b4fdfd30e](https://linux-hardware.org/?probe=0b4fdfd30e) | Apr 15, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [0f678c5ded](https://linux-hardware.org/?probe=0f678c5ded) | Apr 15, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [ee48e89e45](https://linux-hardware.org/?probe=ee48e89e45) | Apr 15, 2023 |
| Gigabyte      | X670 GAMING X AX            | Desktop     | [57cc389eff](https://linux-hardware.org/?probe=57cc389eff) | Apr 14, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [c7b7e028e4](https://linux-hardware.org/?probe=c7b7e028e4) | Apr 14, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | Notebook    | [e0ad93045c](https://linux-hardware.org/?probe=e0ad93045c) | Apr 14, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [f604f6e212](https://linux-hardware.org/?probe=f604f6e212) | Apr 14, 2023 |
| Biostar       | G31D-M7                     | Desktop     | [bb518a8623](https://linux-hardware.org/?probe=bb518a8623) | Apr 14, 2023 |
| Dell          | Latitude 9420               | Notebook    | [529aa83bbc](https://linux-hardware.org/?probe=529aa83bbc) | Apr 14, 2023 |
| Avell High... | B.ON                        | Notebook    | [0ac252a73b](https://linux-hardware.org/?probe=0ac252a73b) | Apr 14, 2023 |
| HP            | ProBook 430 G6              | Notebook    | [9a4bce918e](https://linux-hardware.org/?probe=9a4bce918e) | Apr 14, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [71d89005dd](https://linux-hardware.org/?probe=71d89005dd) | Apr 14, 2023 |
| System76      | Pangolin                    | Notebook    | [b5dd9f13b9](https://linux-hardware.org/?probe=b5dd9f13b9) | Apr 14, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [03e40fe2cd](https://linux-hardware.org/?probe=03e40fe2cd) | Apr 14, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [9f723bfac9](https://linux-hardware.org/?probe=9f723bfac9) | Apr 14, 2023 |
| System76      | Pangolin                    | Notebook    | [a1a17fa4c4](https://linux-hardware.org/?probe=a1a17fa4c4) | Apr 14, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 5 2... | Convertible | [7ae190d0be](https://linux-hardware.org/?probe=7ae190d0be) | Apr 14, 2023 |
| Lenovo        | ThinkPad T460 20FMS0E22C    | Notebook    | [ee911053e5](https://linux-hardware.org/?probe=ee911053e5) | Apr 13, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [62dd8e069f](https://linux-hardware.org/?probe=62dd8e069f) | Apr 13, 2023 |
| MSI           | Prestige 14 A12UC           | Notebook    | [43e044c37a](https://linux-hardware.org/?probe=43e044c37a) | Apr 13, 2023 |
| HP            | ProBook 450 G6              | Notebook    | [3364cf411c](https://linux-hardware.org/?probe=3364cf411c) | Apr 13, 2023 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | Notebook    | [1280936eba](https://linux-hardware.org/?probe=1280936eba) | Apr 13, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [8e641b5fd5](https://linux-hardware.org/?probe=8e641b5fd5) | Apr 13, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [c639e22b34](https://linux-hardware.org/?probe=c639e22b34) | Apr 13, 2023 |
| MSI           | Stealth 14Studio A13VF      | Notebook    | [b6cd64a19b](https://linux-hardware.org/?probe=b6cd64a19b) | Apr 13, 2023 |
| Fujitsu       | LIFEBOOK U745               | Notebook    | [82bfc450e9](https://linux-hardware.org/?probe=82bfc450e9) | Apr 12, 2023 |
| Lenovo        | ThinkPad T480s 20L8S8XJ0... | Notebook    | [6406153cbf](https://linux-hardware.org/?probe=6406153cbf) | Apr 12, 2023 |
| Dell          | XPS 9315                    | Notebook    | [20fa2b86b9](https://linux-hardware.org/?probe=20fa2b86b9) | Apr 12, 2023 |
| ASUSTek       | PRIME B650M-A WIFI          | Desktop     | [796f3afe73](https://linux-hardware.org/?probe=796f3afe73) | Apr 12, 2023 |
| Dell          | Latitude E7440              | Notebook    | [4cfe81f687](https://linux-hardware.org/?probe=4cfe81f687) | Apr 12, 2023 |
| Toshiba       | Satellite S50-B             | Notebook    | [e9d26a9e89](https://linux-hardware.org/?probe=e9d26a9e89) | Apr 12, 2023 |
| Acer          | WG43M                       | Desktop     | [e22afb229d](https://linux-hardware.org/?probe=e22afb229d) | Apr 12, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [6bec4cb4a8](https://linux-hardware.org/?probe=6bec4cb4a8) | Apr 12, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [0daac07546](https://linux-hardware.org/?probe=0daac07546) | Apr 12, 2023 |
| HP            | Laptop 14s-cf1xxx           | Notebook    | [76c9bf81a6](https://linux-hardware.org/?probe=76c9bf81a6) | Apr 12, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [2a108e9eed](https://linux-hardware.org/?probe=2a108e9eed) | Apr 11, 2023 |
| HP            | Laptop 14s-cr0xxx           | Notebook    | [f95d67a702](https://linux-hardware.org/?probe=f95d67a702) | Apr 10, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [c31f7b3b5c](https://linux-hardware.org/?probe=c31f7b3b5c) | Apr 10, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [649a715fba](https://linux-hardware.org/?probe=649a715fba) | Apr 10, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [39c6b4afbe](https://linux-hardware.org/?probe=39c6b4afbe) | Apr 10, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [fff8cbca92](https://linux-hardware.org/?probe=fff8cbca92) | Apr 10, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [e762a4eb1d](https://linux-hardware.org/?probe=e762a4eb1d) | Apr 09, 2023 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [69ee985017](https://linux-hardware.org/?probe=69ee985017) | Apr 09, 2023 |
| MSI           | A320M PRO-VD PLUS           | Desktop     | [709cc4af2c](https://linux-hardware.org/?probe=709cc4af2c) | Apr 09, 2023 |
| Google        | Phaser360                   | Notebook    | [64953bc26c](https://linux-hardware.org/?probe=64953bc26c) | Apr 09, 2023 |
| Avell High... | A52 HYB                     | Notebook    | [7da3b9f780](https://linux-hardware.org/?probe=7da3b9f780) | Apr 09, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [cc25df15df](https://linux-hardware.org/?probe=cc25df15df) | Apr 08, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [44351926f8](https://linux-hardware.org/?probe=44351926f8) | Apr 08, 2023 |
| Lenovo        | ThinkPad 10 20C1002PUK      | Tablet      | [1133b0413b](https://linux-hardware.org/?probe=1133b0413b) | Apr 08, 2023 |
| Lenovo        | ThinkPad P51 W10DG 20MNS... | Notebook    | [5cf4615347](https://linux-hardware.org/?probe=5cf4615347) | Apr 08, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [08f117749f](https://linux-hardware.org/?probe=08f117749f) | Apr 08, 2023 |
| ASUSTek       | Zenbook UX7602ZM_UX7602Z... | Notebook    | [772414cda4](https://linux-hardware.org/?probe=772414cda4) | Apr 07, 2023 |
| Lenovo        | ThinkPad T480 20L6S4G72S    | Notebook    | [ae8c333d72](https://linux-hardware.org/?probe=ae8c333d72) | Apr 07, 2023 |
| Fujitsu       | LIFEBOOK S935               | Notebook    | [e7ba943509](https://linux-hardware.org/?probe=e7ba943509) | Apr 07, 2023 |
| HP            | ZBook 15 G5                 | Notebook    | [1927fa08d1](https://linux-hardware.org/?probe=1927fa08d1) | Apr 07, 2023 |
| MSI           | B250M PRO-VDH               | Desktop     | [123883b7dd](https://linux-hardware.org/?probe=123883b7dd) | Apr 06, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [2532af42ba](https://linux-hardware.org/?probe=2532af42ba) | Apr 06, 2023 |
| Dell          | Vostro 5620                 | Notebook    | [afdf8d46a2](https://linux-hardware.org/?probe=afdf8d46a2) | Apr 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [a02839d653](https://linux-hardware.org/?probe=a02839d653) | Apr 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [80bd0aed09](https://linux-hardware.org/?probe=80bd0aed09) | Apr 05, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [712e78de35](https://linux-hardware.org/?probe=712e78de35) | Apr 05, 2023 |
| Timi          | RedmiBook Pro 15            | Notebook    | [4eb4d46bfc](https://linux-hardware.org/?probe=4eb4d46bfc) | Apr 05, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [fef3cbc941](https://linux-hardware.org/?probe=fef3cbc941) | Apr 05, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [0b4faaa32e](https://linux-hardware.org/?probe=0b4faaa32e) | Apr 05, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [3f750a4d82](https://linux-hardware.org/?probe=3f750a4d82) | Apr 05, 2023 |
| Alienware     | M17xR3                      | Notebook    | [514f79bd8e](https://linux-hardware.org/?probe=514f79bd8e) | Apr 05, 2023 |
| HP            | Pro x360 435 13.3 inch G... | Convertible | [f211babaa5](https://linux-hardware.org/?probe=f211babaa5) | Apr 04, 2023 |
| Acer          | AO756                       | Notebook    | [4e33479949](https://linux-hardware.org/?probe=4e33479949) | Apr 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [a467a04489](https://linux-hardware.org/?probe=a467a04489) | Apr 04, 2023 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [c529f9d1cc](https://linux-hardware.org/?probe=c529f9d1cc) | Apr 03, 2023 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [b9a98e8656](https://linux-hardware.org/?probe=b9a98e8656) | Apr 03, 2023 |
| Gigabyte      | B360M D2V                   | Desktop     | [d2850d3f77](https://linux-hardware.org/?probe=d2850d3f77) | Apr 03, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [3a87280f55](https://linux-hardware.org/?probe=3a87280f55) | Apr 03, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [fc89f163b0](https://linux-hardware.org/?probe=fc89f163b0) | Apr 03, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [1cb5977d82](https://linux-hardware.org/?probe=1cb5977d82) | Apr 03, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [416152a691](https://linux-hardware.org/?probe=416152a691) | Apr 03, 2023 |
| Prestigio     | PSB133S01ZFH                | Notebook    | [ba6746febf](https://linux-hardware.org/?probe=ba6746febf) | Apr 03, 2023 |
| ASUSTek       | TUF Gaming FX705DY_TUF70... | Notebook    | [85e0077c83](https://linux-hardware.org/?probe=85e0077c83) | Apr 03, 2023 |
| Timi          | RedmiBook Pro 14S           | Notebook    | [e3eb0fe882](https://linux-hardware.org/?probe=e3eb0fe882) | Apr 02, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [8f8d89fe9a](https://linux-hardware.org/?probe=8f8d89fe9a) | Apr 02, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [a5d404ca3d](https://linux-hardware.org/?probe=a5d404ca3d) | Apr 02, 2023 |
| Toxic         | GM5MPHY                     | Notebook    | [9ce64fb49a](https://linux-hardware.org/?probe=9ce64fb49a) | Apr 02, 2023 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [b4207e264f](https://linux-hardware.org/?probe=b4207e264f) | Apr 02, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [7bfb9086ab](https://linux-hardware.org/?probe=7bfb9086ab) | Apr 02, 2023 |
| Lenovo        | ThinkPad E480 20KQS0B800    | Notebook    | [9c9b561ca2](https://linux-hardware.org/?probe=9c9b561ca2) | Apr 02, 2023 |
| Lenovo        | ThinkPad P51 W10DG 20MNS... | Notebook    | [c7791aac7c](https://linux-hardware.org/?probe=c7791aac7c) | Apr 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [45c62cbb5c](https://linux-hardware.org/?probe=45c62cbb5c) | Apr 02, 2023 |
| ASUSTek       | P8H67-V                     | Desktop     | [3a488490ce](https://linux-hardware.org/?probe=3a488490ce) | Apr 02, 2023 |
| Google        | Snappy                      | Notebook    | [6ca49159d2](https://linux-hardware.org/?probe=6ca49159d2) | Apr 01, 2023 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | Desktop     | [015b741441](https://linux-hardware.org/?probe=015b741441) | Apr 01, 2023 |
| AZW           | MINI S 10                   | Desktop     | [19d66110ff](https://linux-hardware.org/?probe=19d66110ff) | Apr 01, 2023 |
| Schenker      | S405                        | Notebook    | [6d89f7e662](https://linux-hardware.org/?probe=6d89f7e662) | Apr 01, 2023 |
| Dell          | 0MGK50 A02                  | Desktop     | [3a042b5160](https://linux-hardware.org/?probe=3a042b5160) | Apr 01, 2023 |
| ASUSTek       | X550LB                      | Notebook    | [3d35ff8b68](https://linux-hardware.org/?probe=3d35ff8b68) | Apr 01, 2023 |
| MSI           | P43T-C51                    | Desktop     | [d16b44b442](https://linux-hardware.org/?probe=d16b44b442) | Apr 01, 2023 |
| Dell          | Inspiron 13 5310            | Notebook    | [32bdbfa581](https://linux-hardware.org/?probe=32bdbfa581) | Apr 01, 2023 |
| Lenovo        | ThinkPad T440p              | Notebook    | [4057e0c5e9](https://linux-hardware.org/?probe=4057e0c5e9) | Apr 01, 2023 |
| HP            | Notebook                    | Notebook    | [7cb279c8e0](https://linux-hardware.org/?probe=7cb279c8e0) | Apr 01, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [59c335754f](https://linux-hardware.org/?probe=59c335754f) | Apr 01, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [53717700a1](https://linux-hardware.org/?probe=53717700a1) | Mar 31, 2023 |
| Dell          | XPS 17 9700                 | Notebook    | [5d0a908832](https://linux-hardware.org/?probe=5d0a908832) | Mar 31, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [8326806aa6](https://linux-hardware.org/?probe=8326806aa6) | Mar 31, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [4d69417ed0](https://linux-hardware.org/?probe=4d69417ed0) | Mar 31, 2023 |
| Lenovo        | ThinkPad T440p              | Notebook    | [1063ba3fb9](https://linux-hardware.org/?probe=1063ba3fb9) | Mar 31, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [e2c6f05595](https://linux-hardware.org/?probe=e2c6f05595) | Mar 31, 2023 |
| ASRock        | B550M-C                     | Desktop     | [c0fcfbc0ed](https://linux-hardware.org/?probe=c0fcfbc0ed) | Mar 31, 2023 |
| ASRock        | H67DE3                      | Desktop     | [b055ccc048](https://linux-hardware.org/?probe=b055ccc048) | Mar 31, 2023 |
| ASRock        | H67DE3                      | Desktop     | [c82ba90d70](https://linux-hardware.org/?probe=c82ba90d70) | Mar 31, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | Notebook    | [0ab4f4cd55](https://linux-hardware.org/?probe=0ab4f4cd55) | Mar 31, 2023 |
| Gigabyte      | Z390 M-CF                   | Desktop     | [6bce2b9bc3](https://linux-hardware.org/?probe=6bce2b9bc3) | Mar 31, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [6915349237](https://linux-hardware.org/?probe=6915349237) | Mar 31, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | Desktop     | [ebd6135034](https://linux-hardware.org/?probe=ebd6135034) | Mar 31, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | Desktop     | [88864f0e2d](https://linux-hardware.org/?probe=88864f0e2d) | Mar 31, 2023 |
| Acer          | WG43M                       | Desktop     | [3b626d2ff9](https://linux-hardware.org/?probe=3b626d2ff9) | Mar 31, 2023 |
| MSI           | A320M PRO-VD PLUS           | Desktop     | [9e43a17d1a](https://linux-hardware.org/?probe=9e43a17d1a) | Mar 30, 2023 |
| Lenovo        | ThinkPad X250 20CLS2A100    | Notebook    | [2e8eab25be](https://linux-hardware.org/?probe=2e8eab25be) | Mar 30, 2023 |
| ASUSTek       | M4A77T/USB3                 | Desktop     | [b593e25f2a](https://linux-hardware.org/?probe=b593e25f2a) | Mar 30, 2023 |
| Intel         | DQ45CB E30148-207           | Desktop     | [e47e1626c3](https://linux-hardware.org/?probe=e47e1626c3) | Mar 29, 2023 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | Notebook    | [de3828d539](https://linux-hardware.org/?probe=de3828d539) | Mar 29, 2023 |
| HP            | Victus by Laptop 16-d0xx... | Notebook    | [d96583e702](https://linux-hardware.org/?probe=d96583e702) | Mar 29, 2023 |
| IP3 Tech      | IB8                         | Desktop     | [c12033f9e7](https://linux-hardware.org/?probe=c12033f9e7) | Mar 29, 2023 |
| Timi          | Redmi Book Pro 14 2022      | Notebook    | [e9b1759970](https://linux-hardware.org/?probe=e9b1759970) | Mar 29, 2023 |
| Acer          | Aspire ES1-512              | Notebook    | [f6357798c5](https://linux-hardware.org/?probe=f6357798c5) | Mar 28, 2023 |
| Dell          | Vostro 2420                 | Notebook    | [0a1739f44c](https://linux-hardware.org/?probe=0a1739f44c) | Mar 28, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [d1e1b40549](https://linux-hardware.org/?probe=d1e1b40549) | Mar 28, 2023 |
| ASUSTek       | PRIME H370-PLUS             | Desktop     | [4a7e7763c1](https://linux-hardware.org/?probe=4a7e7763c1) | Mar 28, 2023 |
| HP            | ElitePad 1000 G2            | Notebook    | [4b16a78f3e](https://linux-hardware.org/?probe=4b16a78f3e) | Mar 28, 2023 |
| Dell          | Inspiron 16 5630            | Notebook    | [5838554410](https://linux-hardware.org/?probe=5838554410) | Mar 28, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [60012fd503](https://linux-hardware.org/?probe=60012fd503) | Mar 27, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [b62f0eaa0e](https://linux-hardware.org/?probe=b62f0eaa0e) | Mar 27, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [54f096fd88](https://linux-hardware.org/?probe=54f096fd88) | Mar 27, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [29ec74ac8b](https://linux-hardware.org/?probe=29ec74ac8b) | Mar 27, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [cebc7c547a](https://linux-hardware.org/?probe=cebc7c547a) | Mar 26, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [4391dcbdd2](https://linux-hardware.org/?probe=4391dcbdd2) | Mar 26, 2023 |
| Acer          | WG43M                       | Desktop     | [74320e2d13](https://linux-hardware.org/?probe=74320e2d13) | Mar 26, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [cba16003d7](https://linux-hardware.org/?probe=cba16003d7) | Mar 26, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [14cc8c6a5e](https://linux-hardware.org/?probe=14cc8c6a5e) | Mar 26, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | Notebook    | [0933beb0f7](https://linux-hardware.org/?probe=0933beb0f7) | Mar 26, 2023 |
| Dell          | 0MGK50 A02                  | Desktop     | [93b35b776a](https://linux-hardware.org/?probe=93b35b776a) | Mar 26, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [c722a5f7b2](https://linux-hardware.org/?probe=c722a5f7b2) | Mar 26, 2023 |
| Dell          | G3 3590                     | Notebook    | [db70257507](https://linux-hardware.org/?probe=db70257507) | Mar 26, 2023 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [b9095b98c4](https://linux-hardware.org/?probe=b9095b98c4) | Mar 25, 2023 |
| MSI           | X470 GAMING PRO             | Desktop     | [b49dbdfa77](https://linux-hardware.org/?probe=b49dbdfa77) | Mar 25, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [8060aec150](https://linux-hardware.org/?probe=8060aec150) | Mar 25, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [55c1b171dd](https://linux-hardware.org/?probe=55c1b171dd) | Mar 25, 2023 |
| Lenovo        | ThinkPad T480s 20L7S0YA0... | Notebook    | [f4cb79dbf8](https://linux-hardware.org/?probe=f4cb79dbf8) | Mar 25, 2023 |
| Lenovo        | ThinkPad X13 Gen 3 21BNC... | Notebook    | [649b881439](https://linux-hardware.org/?probe=649b881439) | Mar 25, 2023 |
| Dynabook      | PORTEGE X40L-K              | Notebook    | [9f4a50bc98](https://linux-hardware.org/?probe=9f4a50bc98) | Mar 25, 2023 |
| Gigabyte      | X399 AORUS PRO-CF           | Desktop     | [99da9866a9](https://linux-hardware.org/?probe=99da9866a9) | Mar 25, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [2f5c339d88](https://linux-hardware.org/?probe=2f5c339d88) | Mar 25, 2023 |
| MSI           | B450M BAZOOKA V2            | Desktop     | [3677f24e87](https://linux-hardware.org/?probe=3677f24e87) | Mar 25, 2023 |
| ASRock        | B550AM Gaming               | Desktop     | [be6e8f17cc](https://linux-hardware.org/?probe=be6e8f17cc) | Mar 25, 2023 |
| Lenovo        | ThinkPad L380 Yoga 20M70... | Convertible | [d1eea40764](https://linux-hardware.org/?probe=d1eea40764) | Mar 25, 2023 |
| HP            | ENVY Laptop 17-ce1xxx       | Notebook    | [f9ff96064b](https://linux-hardware.org/?probe=f9ff96064b) | Mar 24, 2023 |
| Toshiba       | Satellite C850-140          | Notebook    | [6682022c49](https://linux-hardware.org/?probe=6682022c49) | Mar 24, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [71d058eb0e](https://linux-hardware.org/?probe=71d058eb0e) | Mar 24, 2023 |
| Toshiba       | Satellite C55D-B            | Notebook    | [ae6069d9bb](https://linux-hardware.org/?probe=ae6069d9bb) | Mar 24, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [4eb8132fd2](https://linux-hardware.org/?probe=4eb8132fd2) | Mar 24, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [56942672e1](https://linux-hardware.org/?probe=56942672e1) | Mar 24, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [29fce46770](https://linux-hardware.org/?probe=29fce46770) | Mar 24, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [ded37ac14c](https://linux-hardware.org/?probe=ded37ac14c) | Mar 24, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [13046d5580](https://linux-hardware.org/?probe=13046d5580) | Mar 24, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [56854770ba](https://linux-hardware.org/?probe=56854770ba) | Mar 24, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [62a95efc48](https://linux-hardware.org/?probe=62a95efc48) | Mar 23, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [748d918a61](https://linux-hardware.org/?probe=748d918a61) | Mar 23, 2023 |
| Lenovo        | ThinkPad T450s 20BWS05G0... | Notebook    | [38b0e00744](https://linux-hardware.org/?probe=38b0e00744) | Mar 23, 2023 |
| Lenovo        | ThinkPad T450s 20BWS05G0... | Notebook    | [ad1134944b](https://linux-hardware.org/?probe=ad1134944b) | Mar 23, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [79e1666c41](https://linux-hardware.org/?probe=79e1666c41) | Mar 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e7b4dc0fd4](https://linux-hardware.org/?probe=e7b4dc0fd4) | Mar 23, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | Notebook    | [fc1c184c05](https://linux-hardware.org/?probe=fc1c184c05) | Mar 23, 2023 |
| ASUSTek       | T100HAN                     | Notebook    | [5f0061dd7b](https://linux-hardware.org/?probe=5f0061dd7b) | Mar 23, 2023 |
| MSI           | MPG X670E CARBON WIFI       | Desktop     | [a36464850a](https://linux-hardware.org/?probe=a36464850a) | Mar 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [28cd6cb051](https://linux-hardware.org/?probe=28cd6cb051) | Mar 23, 2023 |
| HP            | Spectre                     | Convertible | [c9181ab4f2](https://linux-hardware.org/?probe=c9181ab4f2) | Mar 22, 2023 |
| HP            | Spectre                     | Convertible | [5e07c68683](https://linux-hardware.org/?probe=5e07c68683) | Mar 22, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [9795961bca](https://linux-hardware.org/?probe=9795961bca) | Mar 22, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [fab7c8ab05](https://linux-hardware.org/?probe=fab7c8ab05) | Mar 22, 2023 |
| Dell          | Vostro 2420                 | Notebook    | [e885d387ee](https://linux-hardware.org/?probe=e885d387ee) | Mar 22, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | Notebook    | [0880214933](https://linux-hardware.org/?probe=0880214933) | Mar 22, 2023 |
| Lenovo        | ThinkPad X250 20CLS2A100    | Notebook    | [e7b50c8f22](https://linux-hardware.org/?probe=e7b50c8f22) | Mar 22, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [4b7801e829](https://linux-hardware.org/?probe=4b7801e829) | Mar 22, 2023 |
| MSI           | MAG B650M MORTAR WIFI       | Desktop     | [1e299101d8](https://linux-hardware.org/?probe=1e299101d8) | Mar 22, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [1da76d59b2](https://linux-hardware.org/?probe=1da76d59b2) | Mar 21, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [6fc76628d3](https://linux-hardware.org/?probe=6fc76628d3) | Mar 21, 2023 |
| MSI           | Modern 14 B10MW             | Notebook    | [2940ea3b40](https://linux-hardware.org/?probe=2940ea3b40) | Mar 21, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [7336ce9057](https://linux-hardware.org/?probe=7336ce9057) | Mar 21, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [c2191470c7](https://linux-hardware.org/?probe=c2191470c7) | Mar 21, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [01e06fb483](https://linux-hardware.org/?probe=01e06fb483) | Mar 21, 2023 |
| ASUSTek       | TUF Gaming H470-PRO         | Desktop     | [7d1cd9aded](https://linux-hardware.org/?probe=7d1cd9aded) | Mar 20, 2023 |
| HP            | ProBook 440 G3              | Notebook    | [217e9242da](https://linux-hardware.org/?probe=217e9242da) | Mar 20, 2023 |
| HP            | ProBook 440 G3              | Notebook    | [b011027d1a](https://linux-hardware.org/?probe=b011027d1a) | Mar 20, 2023 |
| Gigabyte      | P31-DS3L                    | Desktop     | [7fb5a2f07e](https://linux-hardware.org/?probe=7fb5a2f07e) | Mar 20, 2023 |
| Acer          | Aspire C24-320              | All in one  | [f320bc5964](https://linux-hardware.org/?probe=f320bc5964) | Mar 20, 2023 |
| Acer          | Aspire C24-320              | All in one  | [21de7ff6d5](https://linux-hardware.org/?probe=21de7ff6d5) | Mar 20, 2023 |
| Dell          | XPS 9315                    | Notebook    | [3a6814a18f](https://linux-hardware.org/?probe=3a6814a18f) | Mar 20, 2023 |
| Dell          | XPS 9315                    | Notebook    | [a6054e6f0e](https://linux-hardware.org/?probe=a6054e6f0e) | Mar 20, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [f9c84aa26c](https://linux-hardware.org/?probe=f9c84aa26c) | Mar 20, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [ba804b8e21](https://linux-hardware.org/?probe=ba804b8e21) | Mar 20, 2023 |
| MSI           | GS63VR 7RF                  | Notebook    | [8d13f6eef9](https://linux-hardware.org/?probe=8d13f6eef9) | Mar 20, 2023 |
| MSI           | GS63VR 7RF                  | Notebook    | [5b4e0532f8](https://linux-hardware.org/?probe=5b4e0532f8) | Mar 20, 2023 |
| Dell          | Vostro 2420                 | Notebook    | [a98665cff1](https://linux-hardware.org/?probe=a98665cff1) | Mar 20, 2023 |
| Gigabyte      | B85M-D3V-A-SI               | Desktop     | [19a060d86d](https://linux-hardware.org/?probe=19a060d86d) | Mar 20, 2023 |
| Dell          | G15 5511                    | Notebook    | [ddb34b9c1f](https://linux-hardware.org/?probe=ddb34b9c1f) | Mar 19, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [0500018bce](https://linux-hardware.org/?probe=0500018bce) | Mar 19, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [ad5218c0bf](https://linux-hardware.org/?probe=ad5218c0bf) | Mar 19, 2023 |
| Acidanther... | Mac-CFF7D910A743CAAF iMa... | All in one  | [1854e9efde](https://linux-hardware.org/?probe=1854e9efde) | Mar 19, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0FH00    | Notebook    | [aa4184ac0c](https://linux-hardware.org/?probe=aa4184ac0c) | Mar 19, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0FH00    | Notebook    | [00de843c75](https://linux-hardware.org/?probe=00de843c75) | Mar 19, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [4757b31751](https://linux-hardware.org/?probe=4757b31751) | Mar 19, 2023 |
| MSI           | GP66 Leopard 11UG           | Notebook    | [7210f8c423](https://linux-hardware.org/?probe=7210f8c423) | Mar 19, 2023 |
| ASUSTek       | X205TA                      | Notebook    | [9727a94199](https://linux-hardware.org/?probe=9727a94199) | Mar 18, 2023 |
| Lenovo        | ThinkPad T460s 20FAS6PN0... | Notebook    | [bb86a34180](https://linux-hardware.org/?probe=bb86a34180) | Mar 18, 2023 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [ed76176dfa](https://linux-hardware.org/?probe=ed76176dfa) | Mar 18, 2023 |
| Unknown       | Unknown                     | Notebook    | [e10e576833](https://linux-hardware.org/?probe=e10e576833) | Mar 18, 2023 |
| Unknown       | Unknown                     | Notebook    | [a791424f94](https://linux-hardware.org/?probe=a791424f94) | Mar 18, 2023 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [4b484ab326](https://linux-hardware.org/?probe=4b484ab326) | Mar 18, 2023 |
| Lenovo        | ThinkPad Yoga 11e 20D900... | Notebook    | [434b76d9cd](https://linux-hardware.org/?probe=434b76d9cd) | Mar 18, 2023 |
| Lenovo        | ThinkPad Yoga 11e 20D900... | Notebook    | [2ffc3ebd28](https://linux-hardware.org/?probe=2ffc3ebd28) | Mar 18, 2023 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | Notebook    | [3a565fb944](https://linux-hardware.org/?probe=3a565fb944) | Mar 18, 2023 |
| Microsoft     | Surface Laptop 4            | Tablet      | [a721b1b9d6](https://linux-hardware.org/?probe=a721b1b9d6) | Mar 18, 2023 |
| HONOR         | BOD-WXX9                    | Notebook    | [9bca2e7122](https://linux-hardware.org/?probe=9bca2e7122) | Mar 18, 2023 |
| BESSTAR Te... | HM90                        | Desktop     | [c20318c7c0](https://linux-hardware.org/?probe=c20318c7c0) | Mar 18, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [b21fb664f8](https://linux-hardware.org/?probe=b21fb664f8) | Mar 17, 2023 |
| ASUSTek       | TUF B350M-PLUS GAMING       | Desktop     | [be6db6cc62](https://linux-hardware.org/?probe=be6db6cc62) | Mar 17, 2023 |
| ASUSTek       | N550JK                      | Notebook    | [6b93d4a171](https://linux-hardware.org/?probe=6b93d4a171) | Mar 17, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [ccfa4fb30e](https://linux-hardware.org/?probe=ccfa4fb30e) | Mar 17, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [fc0e66fc8a](https://linux-hardware.org/?probe=fc0e66fc8a) | Mar 17, 2023 |
| Dell          | Precision 3520              | Notebook    | [2afa31184a](https://linux-hardware.org/?probe=2afa31184a) | Mar 17, 2023 |
| Dell          | Precision 3520              | Notebook    | [819b4aa330](https://linux-hardware.org/?probe=819b4aa330) | Mar 17, 2023 |
| Lenovo        | Legion 5-15IMH05H 81Y6      | Notebook    | [e7e152095b](https://linux-hardware.org/?probe=e7e152095b) | Mar 17, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [2215bc867b](https://linux-hardware.org/?probe=2215bc867b) | Mar 17, 2023 |
| Gigabyte      | X399 AORUS PRO-CF           | Desktop     | [fff0c55980](https://linux-hardware.org/?probe=fff0c55980) | Mar 17, 2023 |
| Gigabyte      | X399 AORUS PRO-CF           | Desktop     | [538477684f](https://linux-hardware.org/?probe=538477684f) | Mar 17, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [1b43670875](https://linux-hardware.org/?probe=1b43670875) | Mar 16, 2023 |
| HP            | 245 14 inch G9 Notebook ... | Notebook    | [03edff3e6f](https://linux-hardware.org/?probe=03edff3e6f) | Mar 16, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [304f8b71db](https://linux-hardware.org/?probe=304f8b71db) | Mar 16, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [4bfe066835](https://linux-hardware.org/?probe=4bfe066835) | Mar 16, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [f3bb3c5ef1](https://linux-hardware.org/?probe=f3bb3c5ef1) | Mar 16, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [fc7d8aee1f](https://linux-hardware.org/?probe=fc7d8aee1f) | Mar 16, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [062ba6c2b9](https://linux-hardware.org/?probe=062ba6c2b9) | Mar 16, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [8a802fa8fe](https://linux-hardware.org/?probe=8a802fa8fe) | Mar 16, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [ae258d05b1](https://linux-hardware.org/?probe=ae258d05b1) | Mar 16, 2023 |
| ASUSTek       | PRIME H610M-A D4            | Desktop     | [9765f2823e](https://linux-hardware.org/?probe=9765f2823e) | Mar 16, 2023 |
| Dell          | 0773VG A00                  | Desktop     | [53c02c1bb8](https://linux-hardware.org/?probe=53c02c1bb8) | Mar 16, 2023 |
| ASRock        | Z390M-ITX/ac                | Desktop     | [623a5ed92b](https://linux-hardware.org/?probe=623a5ed92b) | Mar 15, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [590a3ca248](https://linux-hardware.org/?probe=590a3ca248) | Mar 15, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21EM... | Notebook    | [e4254565ed](https://linux-hardware.org/?probe=e4254565ed) | Mar 15, 2023 |
| Star Labs     | StarBook                    | Notebook    | [13efc22826](https://linux-hardware.org/?probe=13efc22826) | Mar 15, 2023 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | Notebook    | [29ebc422fe](https://linux-hardware.org/?probe=29ebc422fe) | Mar 15, 2023 |
| Timi          | RedmiBook 14                | Notebook    | [ff5feda02c](https://linux-hardware.org/?probe=ff5feda02c) | Mar 14, 2023 |
| Acer          | Aspire E5-571               | Notebook    | [6c7886396a](https://linux-hardware.org/?probe=6c7886396a) | Mar 14, 2023 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [7649d9be35](https://linux-hardware.org/?probe=7649d9be35) | Mar 14, 2023 |
| Lenovo        | ThinkPad X240 20AMS1FW00    | Notebook    | [0b9501dcc9](https://linux-hardware.org/?probe=0b9501dcc9) | Mar 14, 2023 |
| Dell          | Vostro 2420                 | Notebook    | [a87952a308](https://linux-hardware.org/?probe=a87952a308) | Mar 14, 2023 |
| Dell          | 0773VG A00                  | Desktop     | [42baaa40b9](https://linux-hardware.org/?probe=42baaa40b9) | Mar 14, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [2662a08251](https://linux-hardware.org/?probe=2662a08251) | Mar 14, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [a13648959d](https://linux-hardware.org/?probe=a13648959d) | Mar 14, 2023 |
| Star Labs     | StarBook                    | Notebook    | [3e534c533a](https://linux-hardware.org/?probe=3e534c533a) | Mar 14, 2023 |
| Dell          | Inspiron 16 Plus 7620       | Notebook    | [2906d8ad11](https://linux-hardware.org/?probe=2906d8ad11) | Mar 14, 2023 |
| HP            | ProLiant DL380 G4           | Server      | [403a18bfff](https://linux-hardware.org/?probe=403a18bfff) | Mar 14, 2023 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | Notebook    | [7f06c80526](https://linux-hardware.org/?probe=7f06c80526) | Mar 14, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [7c96c962f0](https://linux-hardware.org/?probe=7c96c962f0) | Mar 13, 2023 |
| Monster       | ABRA A7 V11.3               | Notebook    | [724a9e65d8](https://linux-hardware.org/?probe=724a9e65d8) | Mar 13, 2023 |
| Panasonic     | FZ40-1                      | Notebook    | [1dfcc0c545](https://linux-hardware.org/?probe=1dfcc0c545) | Mar 13, 2023 |
| HP            | ProBook 6460b               | Notebook    | [c6b7f1ec98](https://linux-hardware.org/?probe=c6b7f1ec98) | Mar 13, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [d507b4619f](https://linux-hardware.org/?probe=d507b4619f) | Mar 13, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [87331b21e8](https://linux-hardware.org/?probe=87331b21e8) | Mar 13, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [aa74d34d26](https://linux-hardware.org/?probe=aa74d34d26) | Mar 13, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [12423f96f6](https://linux-hardware.org/?probe=12423f96f6) | Mar 13, 2023 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | Desktop     | [0b0840b785](https://linux-hardware.org/?probe=0b0840b785) | Mar 13, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [25c6ceb9e8](https://linux-hardware.org/?probe=25c6ceb9e8) | Mar 13, 2023 |
| Lenovo        | ThinkPad T510 4313CTO       | Notebook    | [c2f9a6e354](https://linux-hardware.org/?probe=c2f9a6e354) | Mar 13, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [1e2dd83baa](https://linux-hardware.org/?probe=1e2dd83baa) | Mar 13, 2023 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [a7e24ac4b6](https://linux-hardware.org/?probe=a7e24ac4b6) | Mar 13, 2023 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | Desktop     | [7c00691824](https://linux-hardware.org/?probe=7c00691824) | Mar 12, 2023 |
| ASRock        | Z97M Pro4                   | Desktop     | [7ce318cc22](https://linux-hardware.org/?probe=7ce318cc22) | Mar 12, 2023 |
| ASUSTek       | ASUS EXPERTBOOK L1500CDA... | Notebook    | [5522717dc5](https://linux-hardware.org/?probe=5522717dc5) | Mar 12, 2023 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [751bedd6a9](https://linux-hardware.org/?probe=751bedd6a9) | Mar 12, 2023 |
| MSI           | Pulse GL66 11UGKV           | Notebook    | [1abb09da1a](https://linux-hardware.org/?probe=1abb09da1a) | Mar 12, 2023 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [a081c489c9](https://linux-hardware.org/?probe=a081c489c9) | Mar 12, 2023 |
| ASUSTek       | PRIME H610M-A D4            | Desktop     | [7a20b4f81a](https://linux-hardware.org/?probe=7a20b4f81a) | Mar 12, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [053e36ef52](https://linux-hardware.org/?probe=053e36ef52) | Mar 12, 2023 |
| HP            | G61                         | Notebook    | [2f5e9f6f43](https://linux-hardware.org/?probe=2f5e9f6f43) | Mar 11, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [062687b226](https://linux-hardware.org/?probe=062687b226) | Mar 11, 2023 |
| Intel         | JSL MRD                     | Desktop     | [28832d0a36](https://linux-hardware.org/?probe=28832d0a36) | Mar 11, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [4664479644](https://linux-hardware.org/?probe=4664479644) | Mar 11, 2023 |
| Dell          | Latitude E6530              | Notebook    | [50a26c019d](https://linux-hardware.org/?probe=50a26c019d) | Mar 11, 2023 |
| Lenovo        | IdeaPad Z480                | Notebook    | [eb63a9a0d3](https://linux-hardware.org/?probe=eb63a9a0d3) | Mar 10, 2023 |
| HP            | EliteBook 8730w             | Notebook    | [a012fe4bd2](https://linux-hardware.org/?probe=a012fe4bd2) | Mar 10, 2023 |
| Panasonic     | FZ40-1                      | Notebook    | [5d082aaf0e](https://linux-hardware.org/?probe=5d082aaf0e) | Mar 10, 2023 |
| Gigabyte      | A520I AC                    | Desktop     | [f1e983c2dc](https://linux-hardware.org/?probe=f1e983c2dc) | Mar 10, 2023 |
| HP            | 8754                        | Mini pc     | [4913915d6f](https://linux-hardware.org/?probe=4913915d6f) | Mar 10, 2023 |
| Monster       | HUMA H4 V5.1                | Notebook    | [4745f71e81](https://linux-hardware.org/?probe=4745f71e81) | Mar 10, 2023 |
| Monster       | HUMA H4 V5.1                | Notebook    | [98c29f81d8](https://linux-hardware.org/?probe=98c29f81d8) | Mar 10, 2023 |
| Acer          | Aspire A715-71G             | Notebook    | [6ef05d9cbb](https://linux-hardware.org/?probe=6ef05d9cbb) | Mar 10, 2023 |
| Acer          | Aspire A715-71G             | Notebook    | [4f916d30c4](https://linux-hardware.org/?probe=4f916d30c4) | Mar 10, 2023 |
| Dell          | 0DFRFW A01                  | Desktop     | [9552c8c0ab](https://linux-hardware.org/?probe=9552c8c0ab) | Mar 10, 2023 |
| Panasonic     | FZ40-1                      | Notebook    | [9eac1dc6f5](https://linux-hardware.org/?probe=9eac1dc6f5) | Mar 10, 2023 |
| Lenovo        | ThinkPad X250 20CLS2A100    | Notebook    | [06971429a7](https://linux-hardware.org/?probe=06971429a7) | Mar 10, 2023 |
| Lenovo        | ThinkPad T450 20BUA05K00    | Notebook    | [a496755d7a](https://linux-hardware.org/?probe=a496755d7a) | Mar 10, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [1b0ea7bf68](https://linux-hardware.org/?probe=1b0ea7bf68) | Mar 10, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [ceb2734b56](https://linux-hardware.org/?probe=ceb2734b56) | Mar 09, 2023 |
| Dell          | 0XW3KG A02                  | All in one  | [d45b4c63fa](https://linux-hardware.org/?probe=d45b4c63fa) | Mar 09, 2023 |
| Dell          | 0XW3KG A02                  | All in one  | [f4e6d8e7a0](https://linux-hardware.org/?probe=f4e6d8e7a0) | Mar 09, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [447f2ec783](https://linux-hardware.org/?probe=447f2ec783) | Mar 09, 2023 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | Desktop     | [9c59079b1f](https://linux-hardware.org/?probe=9c59079b1f) | Mar 09, 2023 |
| Acer          | Veriton M480                | Desktop     | [8cd45e8525](https://linux-hardware.org/?probe=8cd45e8525) | Mar 09, 2023 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [8574146364](https://linux-hardware.org/?probe=8574146364) | Mar 09, 2023 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [c397e2fa8b](https://linux-hardware.org/?probe=c397e2fa8b) | Mar 09, 2023 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [79fc708bbd](https://linux-hardware.org/?probe=79fc708bbd) | Mar 09, 2023 |
| Lenovo        | IdeaPad Z480                | Notebook    | [bc5f204a78](https://linux-hardware.org/?probe=bc5f204a78) | Mar 08, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [59bddb27c4](https://linux-hardware.org/?probe=59bddb27c4) | Mar 08, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [69564be379](https://linux-hardware.org/?probe=69564be379) | Mar 08, 2023 |
| Intel         | B75 V124                    | Desktop     | [8a643c9a04](https://linux-hardware.org/?probe=8a643c9a04) | Mar 08, 2023 |
| Intel         | B75 V124                    | Desktop     | [777cb32ba1](https://linux-hardware.org/?probe=777cb32ba1) | Mar 08, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [0312ea16b6](https://linux-hardware.org/?probe=0312ea16b6) | Mar 08, 2023 |
| Dell          | Precision 3520              | Notebook    | [99eaeb743c](https://linux-hardware.org/?probe=99eaeb743c) | Mar 08, 2023 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [c768e8ff8f](https://linux-hardware.org/?probe=c768e8ff8f) | Mar 08, 2023 |
| Dell          | Precision 3520              | Notebook    | [acf74c7740](https://linux-hardware.org/?probe=acf74c7740) | Mar 08, 2023 |
| ASUSTek       | H81T                        | Desktop     | [c17251dbd9](https://linux-hardware.org/?probe=c17251dbd9) | Mar 08, 2023 |
| Lenovo        | ThinkPad T470 20HD0001PG    | Notebook    | [be61e16d11](https://linux-hardware.org/?probe=be61e16d11) | Mar 08, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [7b405f2925](https://linux-hardware.org/?probe=7b405f2925) | Mar 08, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [d1768ecbaa](https://linux-hardware.org/?probe=d1768ecbaa) | Mar 07, 2023 |
| Dell          | Latitude 5590               | Notebook    | [10e7ed8ff6](https://linux-hardware.org/?probe=10e7ed8ff6) | Mar 07, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [e2c5933515](https://linux-hardware.org/?probe=e2c5933515) | Mar 07, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [16c33be9a3](https://linux-hardware.org/?probe=16c33be9a3) | Mar 07, 2023 |
| GPD           | P2 MAX                      | Notebook    | [d73c7b9146](https://linux-hardware.org/?probe=d73c7b9146) | Mar 07, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [bbbf4112e4](https://linux-hardware.org/?probe=bbbf4112e4) | Mar 06, 2023 |
| HP            | Pavilion dv6                | Notebook    | [6485870687](https://linux-hardware.org/?probe=6485870687) | Mar 06, 2023 |
| Acer          | Aspire A114-31              | Notebook    | [33ce987151](https://linux-hardware.org/?probe=33ce987151) | Mar 06, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [0047dd8b2a](https://linux-hardware.org/?probe=0047dd8b2a) | Mar 06, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [ca073d764f](https://linux-hardware.org/?probe=ca073d764f) | Mar 06, 2023 |
| Lenovo        | Unknown                     | Notebook    | [2ae9263125](https://linux-hardware.org/?probe=2ae9263125) | Mar 06, 2023 |
| Lenovo        | ThinkPad E550 20DF002YUS    | Notebook    | [6a7ad331f8](https://linux-hardware.org/?probe=6a7ad331f8) | Mar 06, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CH0... | Notebook    | [6a6864f933](https://linux-hardware.org/?probe=6a6864f933) | Mar 05, 2023 |
| Acer          | Aspire A514-55              | Notebook    | [97e8238d87](https://linux-hardware.org/?probe=97e8238d87) | Mar 05, 2023 |
| IGEL Techn... | H830C                       | Notebook    | [3619b3fcee](https://linux-hardware.org/?probe=3619b3fcee) | Mar 05, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [f8eea076e5](https://linux-hardware.org/?probe=f8eea076e5) | Mar 05, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CH0... | Notebook    | [ea211d74ee](https://linux-hardware.org/?probe=ea211d74ee) | Mar 05, 2023 |
| MSI           | 970A-G46                    | Desktop     | [6f3850aa74](https://linux-hardware.org/?probe=6f3850aa74) | Mar 05, 2023 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [24d58ff4fc](https://linux-hardware.org/?probe=24d58ff4fc) | Mar 05, 2023 |
| HP            | 3397                        | Desktop     | [5250af801f](https://linux-hardware.org/?probe=5250af801f) | Mar 04, 2023 |
| MSI           | 970A-G46                    | Desktop     | [804b0fa4da](https://linux-hardware.org/?probe=804b0fa4da) | Mar 04, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [1ccfddfbc0](https://linux-hardware.org/?probe=1ccfddfbc0) | Mar 04, 2023 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [9de6b65a45](https://linux-hardware.org/?probe=9de6b65a45) | Mar 04, 2023 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [fca1ca2628](https://linux-hardware.org/?probe=fca1ca2628) | Mar 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [71f2f93645](https://linux-hardware.org/?probe=71f2f93645) | Mar 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [13fc723c9e](https://linux-hardware.org/?probe=13fc723c9e) | Mar 04, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [6181549e93](https://linux-hardware.org/?probe=6181549e93) | Mar 04, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | Notebook    | [10c12a6b8a](https://linux-hardware.org/?probe=10c12a6b8a) | Mar 04, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [c19189c929](https://linux-hardware.org/?probe=c19189c929) | Mar 04, 2023 |
| Dell          | Latitude 5480               | Notebook    | [4679c9328e](https://linux-hardware.org/?probe=4679c9328e) | Mar 03, 2023 |
| HUAWEI        | CREF-XX                     | Notebook    | [bef62e57b0](https://linux-hardware.org/?probe=bef62e57b0) | Mar 03, 2023 |
| HUAWEI        | CREF-XX                     | Notebook    | [b42f1c3f6b](https://linux-hardware.org/?probe=b42f1c3f6b) | Mar 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [5715b4e8af](https://linux-hardware.org/?probe=5715b4e8af) | Mar 03, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [d8d83e3bb3](https://linux-hardware.org/?probe=d8d83e3bb3) | Mar 03, 2023 |
| HP            | Spectre                     | Convertible | [8e2fdf7f6b](https://linux-hardware.org/?probe=8e2fdf7f6b) | Mar 03, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [5823762138](https://linux-hardware.org/?probe=5823762138) | Mar 03, 2023 |
| HP            | ENVY dv6                    | Notebook    | [357b5b3506](https://linux-hardware.org/?probe=357b5b3506) | Mar 03, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [860f53436b](https://linux-hardware.org/?probe=860f53436b) | Mar 03, 2023 |
| Dell          | Latitude E6510              | Notebook    | [80edceafbc](https://linux-hardware.org/?probe=80edceafbc) | Mar 03, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [e08a9cdac6](https://linux-hardware.org/?probe=e08a9cdac6) | Mar 03, 2023 |
| HP            | 82F2 A01                    | Desktop     | [305779159c](https://linux-hardware.org/?probe=305779159c) | Mar 02, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [13f585159e](https://linux-hardware.org/?probe=13f585159e) | Mar 02, 2023 |
| DTRI          | DT317CR                     | Notebook    | [b78d90835c](https://linux-hardware.org/?probe=b78d90835c) | Mar 02, 2023 |
| Toshiba       | TECRA Z50-C                 | Notebook    | [c30ead38bd](https://linux-hardware.org/?probe=c30ead38bd) | Mar 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [cf806f07cb](https://linux-hardware.org/?probe=cf806f07cb) | Mar 02, 2023 |
| MSI           | MEG X670E ACE               | Desktop     | [ee356bc253](https://linux-hardware.org/?probe=ee356bc253) | Mar 02, 2023 |
| Dell          | Precision 5520              | Notebook    | [9ce4c56521](https://linux-hardware.org/?probe=9ce4c56521) | Mar 02, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [8ac11055c8](https://linux-hardware.org/?probe=8ac11055c8) | Mar 02, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [72b59f777e](https://linux-hardware.org/?probe=72b59f777e) | Mar 01, 2023 |
| Lenovo        | ThinkPad T490 20N3S3UL00    | Notebook    | [f61c295d09](https://linux-hardware.org/?probe=f61c295d09) | Mar 01, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [0ffe1f9541](https://linux-hardware.org/?probe=0ffe1f9541) | Feb 28, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [a08a3c36ab](https://linux-hardware.org/?probe=a08a3c36ab) | Feb 28, 2023 |
| ASRock        | B660M-STX                   | Desktop     | [5a32d2e162](https://linux-hardware.org/?probe=5a32d2e162) | Feb 28, 2023 |
| MSI           | 760GMA-P34                  | Desktop     | [9707436005](https://linux-hardware.org/?probe=9707436005) | Feb 28, 2023 |
| ASRock        | B365M-HDV                   | Desktop     | [def987e32c](https://linux-hardware.org/?probe=def987e32c) | Feb 28, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [456504fe92](https://linux-hardware.org/?probe=456504fe92) | Feb 28, 2023 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [c070966ad7](https://linux-hardware.org/?probe=c070966ad7) | Feb 28, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [ec1f27de09](https://linux-hardware.org/?probe=ec1f27de09) | Feb 28, 2023 |
| ASUSTek       | CM6870                      | Desktop     | [e338b721af](https://linux-hardware.org/?probe=e338b721af) | Feb 28, 2023 |
| MECHREVO      | Jiaolong Series MRID6       | Notebook    | [1643b96eae](https://linux-hardware.org/?probe=1643b96eae) | Feb 28, 2023 |
| MECHREVO      | Jiaolong Series MRID6       | Notebook    | [b48cc99ce3](https://linux-hardware.org/?probe=b48cc99ce3) | Feb 28, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [62a7d7ef5c](https://linux-hardware.org/?probe=62a7d7ef5c) | Feb 28, 2023 |
| MSI           | B550-A PRO[CEC]             | Desktop     | [2465135444](https://linux-hardware.org/?probe=2465135444) | Feb 28, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [05542207ee](https://linux-hardware.org/?probe=05542207ee) | Feb 28, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [915fc4d913](https://linux-hardware.org/?probe=915fc4d913) | Feb 28, 2023 |
| Intel Clie... | LAPRC510                    | Notebook    | [925c24b3db](https://linux-hardware.org/?probe=925c24b3db) | Feb 28, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [d4bcf9b7a2](https://linux-hardware.org/?probe=d4bcf9b7a2) | Feb 28, 2023 |
| HP            | ProBook 430 G1              | Notebook    | [fa75658ee0](https://linux-hardware.org/?probe=fa75658ee0) | Feb 28, 2023 |
| Dell          | G15 5510                    | Notebook    | [77ff8fd545](https://linux-hardware.org/?probe=77ff8fd545) | Feb 28, 2023 |
| Dell          | G15 5510                    | Notebook    | [2c8f883abe](https://linux-hardware.org/?probe=2c8f883abe) | Feb 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [1f80bce21e](https://linux-hardware.org/?probe=1f80bce21e) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [08e6c7285a](https://linux-hardware.org/?probe=08e6c7285a) | Feb 27, 2023 |
| Dell          | Latitude 7390               | Notebook    | [a2167ae72b](https://linux-hardware.org/?probe=a2167ae72b) | Feb 27, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [b5a08d19e9](https://linux-hardware.org/?probe=b5a08d19e9) | Feb 27, 2023 |
| Schenker      | VISION (E22)                | Notebook    | [498444ca02](https://linux-hardware.org/?probe=498444ca02) | Feb 27, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [979b4559fe](https://linux-hardware.org/?probe=979b4559fe) | Feb 27, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [3ac3b5424a](https://linux-hardware.org/?probe=3ac3b5424a) | Feb 26, 2023 |
| ASUSTek       | A68HM-K                     | Desktop     | [d6f5b00609](https://linux-hardware.org/?probe=d6f5b00609) | Feb 26, 2023 |
| ASUSTek       | A68HM-K                     | Desktop     | [89cd5d5c44](https://linux-hardware.org/?probe=89cd5d5c44) | Feb 26, 2023 |
| HP            | ProBook 430 G1              | Notebook    | [1354e0b47e](https://linux-hardware.org/?probe=1354e0b47e) | Feb 26, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | Notebook    | [848e43f7c3](https://linux-hardware.org/?probe=848e43f7c3) | Feb 26, 2023 |
| MSI           | B350 TOMAHAWK ARCTIC        | Desktop     | [83c075f5c5](https://linux-hardware.org/?probe=83c075f5c5) | Feb 26, 2023 |
| Sony          | SVE1712C1EW                 | Notebook    | [20bd9411d9](https://linux-hardware.org/?probe=20bd9411d9) | Feb 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [9755df8e75](https://linux-hardware.org/?probe=9755df8e75) | Feb 25, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | Notebook    | [e07445a583](https://linux-hardware.org/?probe=e07445a583) | Feb 25, 2023 |
| MSI           | B550-A PRO[CEC]             | Desktop     | [9c1dad9bdc](https://linux-hardware.org/?probe=9c1dad9bdc) | Feb 25, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | Notebook    | [d475dd1788](https://linux-hardware.org/?probe=d475dd1788) | Feb 25, 2023 |
| Star Labs     | StarBook                    | Notebook    | [fbd529b953](https://linux-hardware.org/?probe=fbd529b953) | Feb 25, 2023 |
| Timi          | Xiaomi Book Pro 14 2022     | Notebook    | [46aedb5579](https://linux-hardware.org/?probe=46aedb5579) | Feb 25, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [64504d9860](https://linux-hardware.org/?probe=64504d9860) | Feb 24, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [926fcff980](https://linux-hardware.org/?probe=926fcff980) | Feb 24, 2023 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [efdc981614](https://linux-hardware.org/?probe=efdc981614) | Feb 24, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [8a573735cb](https://linux-hardware.org/?probe=8a573735cb) | Feb 24, 2023 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | Notebook    | [ac2d78d240](https://linux-hardware.org/?probe=ac2d78d240) | Feb 24, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [1b60ef35ce](https://linux-hardware.org/?probe=1b60ef35ce) | Feb 24, 2023 |
| Lenovo        | ThinkPad X61s 7667CG7       | Notebook    | [f090aa4d60](https://linux-hardware.org/?probe=f090aa4d60) | Feb 24, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [bea010d25e](https://linux-hardware.org/?probe=bea010d25e) | Feb 24, 2023 |
| HP            | Elite Dragonfly G2 Noteb... | Convertible | [51e3518d50](https://linux-hardware.org/?probe=51e3518d50) | Feb 24, 2023 |
| Lenovo        | ThinkBook 14 G4+ IAP 21C... | Notebook    | [028814b990](https://linux-hardware.org/?probe=028814b990) | Feb 24, 2023 |
| Dell          | Inspiron 3476               | Notebook    | [58bff0319e](https://linux-hardware.org/?probe=58bff0319e) | Feb 24, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [ea2663126f](https://linux-hardware.org/?probe=ea2663126f) | Feb 24, 2023 |
| Avell High... | A70 MOB                     | Notebook    | [1bf7d82ab3](https://linux-hardware.org/?probe=1bf7d82ab3) | Feb 23, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [7780f02f45](https://linux-hardware.org/?probe=7780f02f45) | Feb 23, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [82889a28a0](https://linux-hardware.org/?probe=82889a28a0) | Feb 23, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [69475d0fa7](https://linux-hardware.org/?probe=69475d0fa7) | Feb 23, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [c69ac67426](https://linux-hardware.org/?probe=c69ac67426) | Feb 23, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [d74903e764](https://linux-hardware.org/?probe=d74903e764) | Feb 23, 2023 |
| Acer          | Swift SF514-54GT            | Notebook    | [dbccc5afa9](https://linux-hardware.org/?probe=dbccc5afa9) | Feb 23, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [14cf9e07e0](https://linux-hardware.org/?probe=14cf9e07e0) | Feb 23, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [388f34d16e](https://linux-hardware.org/?probe=388f34d16e) | Feb 23, 2023 |
| Dell          | Latitude 7300               | Notebook    | [c4bb27e884](https://linux-hardware.org/?probe=c4bb27e884) | Feb 23, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [beb6e53cb7](https://linux-hardware.org/?probe=beb6e53cb7) | Feb 23, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [640957cabe](https://linux-hardware.org/?probe=640957cabe) | Feb 23, 2023 |
| HP            | Spectre                     | Convertible | [2366c11489](https://linux-hardware.org/?probe=2366c11489) | Feb 22, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | Notebook    | [d16dd6d1f3](https://linux-hardware.org/?probe=d16dd6d1f3) | Feb 22, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [701608fad1](https://linux-hardware.org/?probe=701608fad1) | Feb 22, 2023 |
| HP            | ProBook 640 G5              | Notebook    | [e90b71c2fd](https://linux-hardware.org/?probe=e90b71c2fd) | Feb 22, 2023 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [601836815c](https://linux-hardware.org/?probe=601836815c) | Feb 22, 2023 |
| Acer          | Aspire ES1-533              | Notebook    | [4a7563bd8e](https://linux-hardware.org/?probe=4a7563bd8e) | Feb 22, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [aa39c9a471](https://linux-hardware.org/?probe=aa39c9a471) | Feb 22, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [53e8b0db7d](https://linux-hardware.org/?probe=53e8b0db7d) | Feb 22, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [cfcf2ff473](https://linux-hardware.org/?probe=cfcf2ff473) | Feb 21, 2023 |
| ASUSTek       | G11CD                       | Desktop     | [4fc47f45be](https://linux-hardware.org/?probe=4fc47f45be) | Feb 21, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [ecc97fee86](https://linux-hardware.org/?probe=ecc97fee86) | Feb 21, 2023 |
| Compaq        | 430                         | Notebook    | [4bd84653a5](https://linux-hardware.org/?probe=4bd84653a5) | Feb 21, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | Notebook    | [dd12dc45d7](https://linux-hardware.org/?probe=dd12dc45d7) | Feb 21, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [f36328511d](https://linux-hardware.org/?probe=f36328511d) | Feb 21, 2023 |
| HP            | ProBook 430 G1              | Notebook    | [1505165a73](https://linux-hardware.org/?probe=1505165a73) | Feb 20, 2023 |
| ASUSTek       | X555LPB                     | Notebook    | [29eb95639c](https://linux-hardware.org/?probe=29eb95639c) | Feb 20, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [e008fd489b](https://linux-hardware.org/?probe=e008fd489b) | Feb 20, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | Notebook    | [defde684a0](https://linux-hardware.org/?probe=defde684a0) | Feb 20, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [08d8865fcf](https://linux-hardware.org/?probe=08d8865fcf) | Feb 20, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | Notebook    | [1832e70d83](https://linux-hardware.org/?probe=1832e70d83) | Feb 20, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | Notebook    | [9adf6b834b](https://linux-hardware.org/?probe=9adf6b834b) | Feb 20, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [d346153872](https://linux-hardware.org/?probe=d346153872) | Feb 20, 2023 |
| AZW           | GK55                        | Desktop     | [e8376dbc54](https://linux-hardware.org/?probe=e8376dbc54) | Feb 19, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [0f1365d8d8](https://linux-hardware.org/?probe=0f1365d8d8) | Feb 19, 2023 |
| Gigabyte      | B85M-D3V-A-SI               | Desktop     | [5b452754c0](https://linux-hardware.org/?probe=5b452754c0) | Feb 19, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [82fd276e35](https://linux-hardware.org/?probe=82fd276e35) | Feb 19, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [f8f6e2baea](https://linux-hardware.org/?probe=f8f6e2baea) | Feb 19, 2023 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [69a8710cbb](https://linux-hardware.org/?probe=69a8710cbb) | Feb 18, 2023 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [db5d2b956a](https://linux-hardware.org/?probe=db5d2b956a) | Feb 18, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6aae20aa14](https://linux-hardware.org/?probe=6aae20aa14) | Feb 18, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [61befa2690](https://linux-hardware.org/?probe=61befa2690) | Feb 18, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [c1e5226b6e](https://linux-hardware.org/?probe=c1e5226b6e) | Feb 18, 2023 |
| Acer          | Nitro AN515-46              | Notebook    | [bf63748499](https://linux-hardware.org/?probe=bf63748499) | Feb 18, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [be751c4a5b](https://linux-hardware.org/?probe=be751c4a5b) | Feb 18, 2023 |
| Google        | Celes                       | Notebook    | [3004fce0ed](https://linux-hardware.org/?probe=3004fce0ed) | Feb 18, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [2e22d32463](https://linux-hardware.org/?probe=2e22d32463) | Feb 18, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [d0bb58e003](https://linux-hardware.org/?probe=d0bb58e003) | Feb 18, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [322588bc4e](https://linux-hardware.org/?probe=322588bc4e) | Feb 18, 2023 |
| MSI           | GL65 9SD                    | Notebook    | [a702514760](https://linux-hardware.org/?probe=a702514760) | Feb 17, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [bfeb3ab070](https://linux-hardware.org/?probe=bfeb3ab070) | Feb 17, 2023 |
| Lenovo        | ThinkBook 14 G4+ IAP 21C... | Notebook    | [c4ec00ef99](https://linux-hardware.org/?probe=c4ec00ef99) | Feb 17, 2023 |
| TUXEDO        | Unknown                     | Notebook    | [d770ba8b7b](https://linux-hardware.org/?probe=d770ba8b7b) | Feb 17, 2023 |
| Gateway       | SX2803                      | Desktop     | [a1b20489b4](https://linux-hardware.org/?probe=a1b20489b4) | Feb 17, 2023 |
| Acer          | Nitro AN515-46              | Notebook    | [162b72d7a8](https://linux-hardware.org/?probe=162b72d7a8) | Feb 17, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [4948ea8836](https://linux-hardware.org/?probe=4948ea8836) | Feb 17, 2023 |
| HP            | Elite Dragonfly G2 Noteb... | Convertible | [a9d6ae7b72](https://linux-hardware.org/?probe=a9d6ae7b72) | Feb 17, 2023 |
| HP            | 18E7                        | Desktop     | [821ea2c921](https://linux-hardware.org/?probe=821ea2c921) | Feb 17, 2023 |
| Acer          | Aspire A515-51G             | Notebook    | [065827a397](https://linux-hardware.org/?probe=065827a397) | Feb 16, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [fd678baa9f](https://linux-hardware.org/?probe=fd678baa9f) | Feb 16, 2023 |
| Dell          | Latitude 5330               | Notebook    | [497897c322](https://linux-hardware.org/?probe=497897c322) | Feb 16, 2023 |
| Dell          | Latitude 5330               | Notebook    | [aa55aaad48](https://linux-hardware.org/?probe=aa55aaad48) | Feb 16, 2023 |
| Lenovo        | B40-70 20392                | Notebook    | [7197aacb00](https://linux-hardware.org/?probe=7197aacb00) | Feb 16, 2023 |
| Dell          | Latitude 5480               | Notebook    | [ee1b786fd9](https://linux-hardware.org/?probe=ee1b786fd9) | Feb 15, 2023 |
| ASRock        | Z390M Pro4                  | Desktop     | [cf96b55907](https://linux-hardware.org/?probe=cf96b55907) | Feb 15, 2023 |
| HP            | EliteBook 650 15.6 inch ... | Notebook    | [2be1a08ef2](https://linux-hardware.org/?probe=2be1a08ef2) | Feb 15, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [8f5697ea3a](https://linux-hardware.org/?probe=8f5697ea3a) | Feb 15, 2023 |
| HP            | EliteBook x360 1040 G8 N... | Convertible | [e1d323e96f](https://linux-hardware.org/?probe=e1d323e96f) | Feb 15, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [987c9b1854](https://linux-hardware.org/?probe=987c9b1854) | Feb 15, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [138839541a](https://linux-hardware.org/?probe=138839541a) | Feb 15, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [4e3ff30332](https://linux-hardware.org/?probe=4e3ff30332) | Feb 15, 2023 |
| Intel         | NUC11PHBi7 M26151-404       | Mini pc     | [77e13c5748](https://linux-hardware.org/?probe=77e13c5748) | Feb 14, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [dd2017324e](https://linux-hardware.org/?probe=dd2017324e) | Feb 14, 2023 |
| Lenovo        | ThinkPad T490 20N3S3UL00    | Notebook    | [dc352cd9dc](https://linux-hardware.org/?probe=dc352cd9dc) | Feb 14, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [a3eb6fde29](https://linux-hardware.org/?probe=a3eb6fde29) | Feb 14, 2023 |
| Dell          | Latitude 5480               | Notebook    | [ab1652f0da](https://linux-hardware.org/?probe=ab1652f0da) | Feb 14, 2023 |
| Dell          | Venue 8 Pro 5855            | Notebook    | [6e5eacb53a](https://linux-hardware.org/?probe=6e5eacb53a) | Feb 14, 2023 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [926e34c5a9](https://linux-hardware.org/?probe=926e34c5a9) | Feb 14, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d1171fb67b](https://linux-hardware.org/?probe=d1171fb67b) | Feb 14, 2023 |
| Lenovo        | G50-80 80R0                 | Notebook    | [86422b9261](https://linux-hardware.org/?probe=86422b9261) | Feb 14, 2023 |
| Toshiba       | Satellite P870              | Notebook    | [dcfa5b1fc5](https://linux-hardware.org/?probe=dcfa5b1fc5) | Feb 13, 2023 |
| Toshiba       | Satellite P870              | Notebook    | [3a4a4dedc3](https://linux-hardware.org/?probe=3a4a4dedc3) | Feb 13, 2023 |
| Dell          | Latitude E6530              | Notebook    | [c79c336ef7](https://linux-hardware.org/?probe=c79c336ef7) | Feb 13, 2023 |
| Acer          | Swift SF514-54GT            | Notebook    | [b7e961dae3](https://linux-hardware.org/?probe=b7e961dae3) | Feb 13, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [cd29998b19](https://linux-hardware.org/?probe=cd29998b19) | Feb 13, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [b3ab77c355](https://linux-hardware.org/?probe=b3ab77c355) | Feb 13, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [37c223623f](https://linux-hardware.org/?probe=37c223623f) | Feb 13, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [3f25b64868](https://linux-hardware.org/?probe=3f25b64868) | Feb 13, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [89f1272cd8](https://linux-hardware.org/?probe=89f1272cd8) | Feb 13, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [8ac5b193cb](https://linux-hardware.org/?probe=8ac5b193cb) | Feb 13, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [156fae6b82](https://linux-hardware.org/?probe=156fae6b82) | Feb 13, 2023 |
| HP            | 3397                        | Desktop     | [83dc4a9ea0](https://linux-hardware.org/?probe=83dc4a9ea0) | Feb 13, 2023 |
| ASUSTek       | X205TA                      | Notebook    | [dfc9ada1af](https://linux-hardware.org/?probe=dfc9ada1af) | Feb 13, 2023 |
| HP            | 3397                        | Desktop     | [cc7019baaa](https://linux-hardware.org/?probe=cc7019baaa) | Feb 13, 2023 |
| HP            | ProBook 430 G1              | Notebook    | [8d414de313](https://linux-hardware.org/?probe=8d414de313) | Feb 12, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [f5ef3d92cb](https://linux-hardware.org/?probe=f5ef3d92cb) | Feb 12, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [219157717b](https://linux-hardware.org/?probe=219157717b) | Feb 12, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [cdc63fb05e](https://linux-hardware.org/?probe=cdc63fb05e) | Feb 12, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [27411524db](https://linux-hardware.org/?probe=27411524db) | Feb 12, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | Notebook    | [afb25c8733](https://linux-hardware.org/?probe=afb25c8733) | Feb 12, 2023 |
| MSI           | Modern 14 B11MOU            | Notebook    | [547c8e5750](https://linux-hardware.org/?probe=547c8e5750) | Feb 12, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | Notebook    | [35d68b3769](https://linux-hardware.org/?probe=35d68b3769) | Feb 12, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [a326374047](https://linux-hardware.org/?probe=a326374047) | Feb 12, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CH0... | Notebook    | [5335da53d0](https://linux-hardware.org/?probe=5335da53d0) | Feb 11, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2K13... | Notebook    | [5f2fb779b4](https://linux-hardware.org/?probe=5f2fb779b4) | Feb 11, 2023 |
| Samsung       | 767XCL                      | Notebook    | [8a62be0577](https://linux-hardware.org/?probe=8a62be0577) | Feb 11, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [36dd5f42fc](https://linux-hardware.org/?probe=36dd5f42fc) | Feb 11, 2023 |
| Dell          | 0M017G A00                  | Desktop     | [f2deee99d1](https://linux-hardware.org/?probe=f2deee99d1) | Feb 11, 2023 |
| ASRock        | Z790M-ITX WiFi              | Desktop     | [ca7e69040a](https://linux-hardware.org/?probe=ca7e69040a) | Feb 11, 2023 |
| Unknown       | Unknown                     | Notebook    | [31d099a8db](https://linux-hardware.org/?probe=31d099a8db) | Feb 11, 2023 |
| Dell          | 0M017G A00                  | Desktop     | [30965e948d](https://linux-hardware.org/?probe=30965e948d) | Feb 10, 2023 |
| Dell          | 04YJ19 A00                  | Desktop     | [972fb9a299](https://linux-hardware.org/?probe=972fb9a299) | Feb 10, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [ca5ff923cc](https://linux-hardware.org/?probe=ca5ff923cc) | Feb 10, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [04929299d7](https://linux-hardware.org/?probe=04929299d7) | Feb 10, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [fd8d478a5b](https://linux-hardware.org/?probe=fd8d478a5b) | Feb 10, 2023 |
| MSI           | X470 GAMING PRO             | Desktop     | [a53ab3e915](https://linux-hardware.org/?probe=a53ab3e915) | Feb 10, 2023 |
| Acer          | Aspire V5-551               | Notebook    | [cb3ab0bbf5](https://linux-hardware.org/?probe=cb3ab0bbf5) | Feb 10, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | Notebook    | [482b3ea2be](https://linux-hardware.org/?probe=482b3ea2be) | Feb 10, 2023 |
| Acer          | Aspire V5-551               | Notebook    | [132d55b2ed](https://linux-hardware.org/?probe=132d55b2ed) | Feb 09, 2023 |
| ASRock        | B450M Pro4-F                | Desktop     | [35bd9cf04c](https://linux-hardware.org/?probe=35bd9cf04c) | Feb 09, 2023 |
| Sony          | VPCEH1M1E                   | Notebook    | [43f51d50c1](https://linux-hardware.org/?probe=43f51d50c1) | Feb 09, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2K13... | Notebook    | [fc292cd441](https://linux-hardware.org/?probe=fc292cd441) | Feb 09, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [f669c49cf5](https://linux-hardware.org/?probe=f669c49cf5) | Feb 09, 2023 |
| Lenovo        | ThinkPad E490 20N9S2AS00    | Notebook    | [5d2f191a6f](https://linux-hardware.org/?probe=5d2f191a6f) | Feb 09, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [af3d5cd04c](https://linux-hardware.org/?probe=af3d5cd04c) | Feb 09, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING       | Desktop     | [fa2a1dba2d](https://linux-hardware.org/?probe=fa2a1dba2d) | Feb 09, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [02b69364a6](https://linux-hardware.org/?probe=02b69364a6) | Feb 09, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [83efc68bd7](https://linux-hardware.org/?probe=83efc68bd7) | Feb 09, 2023 |
| Lenovo        | ThinkPad E490 20N9S2AS00    | Notebook    | [668b9a0bfe](https://linux-hardware.org/?probe=668b9a0bfe) | Feb 09, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [cdfbd3e72a](https://linux-hardware.org/?probe=cdfbd3e72a) | Feb 09, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [58346a45de](https://linux-hardware.org/?probe=58346a45de) | Feb 08, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [5ce86509b6](https://linux-hardware.org/?probe=5ce86509b6) | Feb 08, 2023 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [e533f4d15f](https://linux-hardware.org/?probe=e533f4d15f) | Feb 08, 2023 |
| Lenovo        | ThinkPad X280 20KEA0VCUK    | Notebook    | [e39c3cefa0](https://linux-hardware.org/?probe=e39c3cefa0) | Feb 08, 2023 |
| Dell          | Latitude E5470              | Notebook    | [e0634fdc6e](https://linux-hardware.org/?probe=e0634fdc6e) | Feb 08, 2023 |
| MSI           | H510M PRO-E                 | Desktop     | [577d1f97d8](https://linux-hardware.org/?probe=577d1f97d8) | Feb 08, 2023 |
| MSI           | H510M PRO-E                 | Desktop     | [2b7b643f2e](https://linux-hardware.org/?probe=2b7b643f2e) | Feb 08, 2023 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [0e174666ba](https://linux-hardware.org/?probe=0e174666ba) | Feb 07, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [2bb967f6b3](https://linux-hardware.org/?probe=2bb967f6b3) | Feb 07, 2023 |
| Lenovo        | ThinkBook 14 G4+ IAP 21C... | Notebook    | [a127a79277](https://linux-hardware.org/?probe=a127a79277) | Feb 07, 2023 |
| Dell          | Precision M4800             | Notebook    | [2572c61169](https://linux-hardware.org/?probe=2572c61169) | Feb 07, 2023 |
| ASUSTek       | ROG Strix G533ZW_G533ZW     | Notebook    | [6e7434a708](https://linux-hardware.org/?probe=6e7434a708) | Feb 07, 2023 |
| Microsoft     | Surface Go 2                | Tablet      | [3be676928d](https://linux-hardware.org/?probe=3be676928d) | Feb 07, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [01872da4ea](https://linux-hardware.org/?probe=01872da4ea) | Feb 07, 2023 |
| Dell          | Inspiron 7791 2n1           | Convertible | [b666459988](https://linux-hardware.org/?probe=b666459988) | Feb 06, 2023 |
| Dell          | Inspiron 7791 2n1           | Convertible | [dee03d9aff](https://linux-hardware.org/?probe=dee03d9aff) | Feb 06, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [c73a4ad56a](https://linux-hardware.org/?probe=c73a4ad56a) | Feb 06, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [149a2716a8](https://linux-hardware.org/?probe=149a2716a8) | Feb 06, 2023 |
| HP            | Stream x360 Convertible ... | Convertible | [3e487446eb](https://linux-hardware.org/?probe=3e487446eb) | Feb 06, 2023 |
| Lenovo        | G505 20240                  | Notebook    | [31e2c2f5e1](https://linux-hardware.org/?probe=31e2c2f5e1) | Feb 06, 2023 |
| Dell          | 0XNNCJ A03                  | Server      | [a0b1f2a7b4](https://linux-hardware.org/?probe=a0b1f2a7b4) | Feb 06, 2023 |
| Toshiba       | Satellite Pro L510          | Notebook    | [c8dc3a76e5](https://linux-hardware.org/?probe=c8dc3a76e5) | Feb 06, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [8d0a0a0422](https://linux-hardware.org/?probe=8d0a0a0422) | Feb 06, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | Desktop     | [f91035a72a](https://linux-hardware.org/?probe=f91035a72a) | Feb 05, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [cfcea0a331](https://linux-hardware.org/?probe=cfcea0a331) | Feb 05, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [bdd3224e6c](https://linux-hardware.org/?probe=bdd3224e6c) | Feb 05, 2023 |
| MSI           | Modern 14 B11SBU            | Notebook    | [50538fe8fd](https://linux-hardware.org/?probe=50538fe8fd) | Feb 05, 2023 |
| Microsoft     | Surface Go 2                | Tablet      | [44c671bfa6](https://linux-hardware.org/?probe=44c671bfa6) | Feb 05, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [ba7531b9db](https://linux-hardware.org/?probe=ba7531b9db) | Feb 05, 2023 |
| Acer          | Nitro AN517-52              | Notebook    | [e409f042e2](https://linux-hardware.org/?probe=e409f042e2) | Feb 05, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [72228118bb](https://linux-hardware.org/?probe=72228118bb) | Feb 05, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [79548473df](https://linux-hardware.org/?probe=79548473df) | Feb 05, 2023 |
| Unknown       | X79A                        | Desktop     | [eedea973ca](https://linux-hardware.org/?probe=eedea973ca) | Feb 05, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [90c48082e0](https://linux-hardware.org/?probe=90c48082e0) | Feb 05, 2023 |
| Apple         | MacBookPro13,1              | Notebook    | [76cf23841d](https://linux-hardware.org/?probe=76cf23841d) | Feb 05, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [42d855f568](https://linux-hardware.org/?probe=42d855f568) | Feb 04, 2023 |
| Dell          | G3 3579                     | Notebook    | [a3b4edbfd9](https://linux-hardware.org/?probe=a3b4edbfd9) | Feb 04, 2023 |
| Lenovo        | ThinkPad X240 20AMS1FW00    | Notebook    | [cee7b3fa93](https://linux-hardware.org/?probe=cee7b3fa93) | Feb 04, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [0eb4367fb4](https://linux-hardware.org/?probe=0eb4367fb4) | Feb 04, 2023 |
| Dell          | 0GDG8Y A00                  | Desktop     | [b9b0a6cccb](https://linux-hardware.org/?probe=b9b0a6cccb) | Feb 04, 2023 |
| Toshiba       | Satellite P500              | Notebook    | [78ebd7c272](https://linux-hardware.org/?probe=78ebd7c272) | Feb 04, 2023 |
| MSI           | Z490-A PRO                  | Desktop     | [d82820c304](https://linux-hardware.org/?probe=d82820c304) | Feb 04, 2023 |
| Gigabyte      | B660 GAMING X DDR4          | Desktop     | [2594dddd54](https://linux-hardware.org/?probe=2594dddd54) | Feb 04, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [4d007a868e](https://linux-hardware.org/?probe=4d007a868e) | Feb 04, 2023 |
| Lenovo        | ThinkPad X280 20KEA0VCUK    | Notebook    | [48d07b6859](https://linux-hardware.org/?probe=48d07b6859) | Feb 04, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [29dc75351d](https://linux-hardware.org/?probe=29dc75351d) | Feb 03, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [54d35f2b7f](https://linux-hardware.org/?probe=54d35f2b7f) | Feb 03, 2023 |
| Gigabyte      | G31M-S2C                    | Desktop     | [3e5a2f20cc](https://linux-hardware.org/?probe=3e5a2f20cc) | Feb 03, 2023 |
| Medion        | S17405                      | Notebook    | [85cdfa1290](https://linux-hardware.org/?probe=85cdfa1290) | Feb 03, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [830188ba1b](https://linux-hardware.org/?probe=830188ba1b) | Feb 03, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [5ce1aa97c6](https://linux-hardware.org/?probe=5ce1aa97c6) | Feb 02, 2023 |
| MSI           | GE63 Raider RGB 9SE         | Notebook    | [b7ec016843](https://linux-hardware.org/?probe=b7ec016843) | Feb 02, 2023 |
| Lenovo        | IdeaPad Slim 7 14ITL05 8... | Notebook    | [7c6794cc63](https://linux-hardware.org/?probe=7c6794cc63) | Feb 02, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [82845bb849](https://linux-hardware.org/?probe=82845bb849) | Feb 02, 2023 |
| Monster       | ABRA A7 V11.1               | Notebook    | [d839e9036f](https://linux-hardware.org/?probe=d839e9036f) | Feb 02, 2023 |
| Monster       | ABRA A7 V11.1               | Notebook    | [ed1785494a](https://linux-hardware.org/?probe=ed1785494a) | Feb 02, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [1ca0a608f9](https://linux-hardware.org/?probe=1ca0a608f9) | Feb 02, 2023 |
| Gigabyte      | Z170XP-SLI-CF               | Desktop     | [1fddf279a5](https://linux-hardware.org/?probe=1fddf279a5) | Feb 02, 2023 |
| Lenovo        | IdeaPad 720S-15IKB 81AC     | Notebook    | [1752779e0c](https://linux-hardware.org/?probe=1752779e0c) | Feb 02, 2023 |
| Lenovo        | IdeaPad 720S-15IKB 81AC     | Notebook    | [ef707954b8](https://linux-hardware.org/?probe=ef707954b8) | Feb 02, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [09430385c6](https://linux-hardware.org/?probe=09430385c6) | Feb 02, 2023 |
| Lenovo        | ThinkPad T480 20L6S3PV00    | Notebook    | [08f4e80cb9](https://linux-hardware.org/?probe=08f4e80cb9) | Feb 02, 2023 |
| Dell          | 0T10XW A02                  | Desktop     | [10e5f7904a](https://linux-hardware.org/?probe=10e5f7904a) | Feb 02, 2023 |
| Gigabyte      | B650M DS3H                  | Desktop     | [981bcc29a7](https://linux-hardware.org/?probe=981bcc29a7) | Feb 01, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [adb2f19fcd](https://linux-hardware.org/?probe=adb2f19fcd) | Feb 01, 2023 |
| MSI           | D2415 S26361-D2415-A21      | Desktop     | [3acfaaf14c](https://linux-hardware.org/?probe=3acfaaf14c) | Feb 01, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [2be076637c](https://linux-hardware.org/?probe=2be076637c) | Feb 01, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [ee219f2f82](https://linux-hardware.org/?probe=ee219f2f82) | Feb 01, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [af2f6edc6f](https://linux-hardware.org/?probe=af2f6edc6f) | Feb 01, 2023 |
| MSI           | B250M PRO-VDH               | Desktop     | [1dbacce612](https://linux-hardware.org/?probe=1dbacce612) | Feb 01, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [2d4aa2e1a0](https://linux-hardware.org/?probe=2d4aa2e1a0) | Feb 01, 2023 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | Notebook    | [3fc59532b8](https://linux-hardware.org/?probe=3fc59532b8) | Feb 01, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [caa1c9e23a](https://linux-hardware.org/?probe=caa1c9e23a) | Jan 31, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [e9525c9a86](https://linux-hardware.org/?probe=e9525c9a86) | Jan 31, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [e6cb9d8296](https://linux-hardware.org/?probe=e6cb9d8296) | Jan 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [78bd5ea99c](https://linux-hardware.org/?probe=78bd5ea99c) | Jan 31, 2023 |
| Dell          | 0J1C3P A00                  | Desktop     | [8512c1d0cc](https://linux-hardware.org/?probe=8512c1d0cc) | Jan 31, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [eb4687961f](https://linux-hardware.org/?probe=eb4687961f) | Jan 31, 2023 |
| MACHINIST     | X99Z V102 IENGINEER         | Desktop     | [d2cfaf56df](https://linux-hardware.org/?probe=d2cfaf56df) | Jan 31, 2023 |
| Lenovo        | Legion R9000P ARH7H 82RG    | Notebook    | [15cda8e776](https://linux-hardware.org/?probe=15cda8e776) | Jan 30, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | Notebook    | [0c220851f3](https://linux-hardware.org/?probe=0c220851f3) | Jan 30, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [7893a67a4b](https://linux-hardware.org/?probe=7893a67a4b) | Jan 30, 2023 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [9f093d7cff](https://linux-hardware.org/?probe=9f093d7cff) | Jan 30, 2023 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [b88f08d400](https://linux-hardware.org/?probe=b88f08d400) | Jan 29, 2023 |
| Dell          | G15 5520                    | Notebook    | [ae4bf1777e](https://linux-hardware.org/?probe=ae4bf1777e) | Jan 29, 2023 |
| Microsoft     | Surface Laptop 4            | Tablet      | [77c9cc065f](https://linux-hardware.org/?probe=77c9cc065f) | Jan 29, 2023 |
| Microsoft     | Surface Laptop 4            | Tablet      | [1ddc17833b](https://linux-hardware.org/?probe=1ddc17833b) | Jan 29, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [8727d22cba](https://linux-hardware.org/?probe=8727d22cba) | Jan 29, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [97aa61aba5](https://linux-hardware.org/?probe=97aa61aba5) | Jan 29, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [4042b92ee1](https://linux-hardware.org/?probe=4042b92ee1) | Jan 29, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [4603f92b18](https://linux-hardware.org/?probe=4603f92b18) | Jan 29, 2023 |
| ASUSTek       | Z170M-E D3                  | Desktop     | [2b466d1b19](https://linux-hardware.org/?probe=2b466d1b19) | Jan 29, 2023 |
| Gigabyte      | Z170XP-SLI-CF               | Desktop     | [b9a38b7494](https://linux-hardware.org/?probe=b9a38b7494) | Jan 29, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [608c0b8c88](https://linux-hardware.org/?probe=608c0b8c88) | Jan 29, 2023 |
| Toshiba       | STI 010433                  | Desktop     | [fead488cf1](https://linux-hardware.org/?probe=fead488cf1) | Jan 29, 2023 |
| Dell          | Latitude E6530              | Notebook    | [87bca9f2a4](https://linux-hardware.org/?probe=87bca9f2a4) | Jan 29, 2023 |
| Dell          | G15 5520                    | Notebook    | [a0c269c5b1](https://linux-hardware.org/?probe=a0c269c5b1) | Jan 28, 2023 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | Desktop     | [cba2528a29](https://linux-hardware.org/?probe=cba2528a29) | Jan 28, 2023 |
| ASRock        | X570 Pro4                   | Desktop     | [bf09bd7413](https://linux-hardware.org/?probe=bf09bd7413) | Jan 28, 2023 |
| ASUSTek       | PRIME B660M-A D4            | Desktop     | [41ff395299](https://linux-hardware.org/?probe=41ff395299) | Jan 28, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [85e23fef85](https://linux-hardware.org/?probe=85e23fef85) | Jan 28, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [7961073f5f](https://linux-hardware.org/?probe=7961073f5f) | Jan 28, 2023 |
| MSI           | 970A-G46                    | Desktop     | [ece518ec34](https://linux-hardware.org/?probe=ece518ec34) | Jan 28, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [40672aba71](https://linux-hardware.org/?probe=40672aba71) | Jan 28, 2023 |
| ASUSTek       | X555LAB                     | Notebook    | [343025f50f](https://linux-hardware.org/?probe=343025f50f) | Jan 28, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [f1f0543123](https://linux-hardware.org/?probe=f1f0543123) | Jan 28, 2023 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [f5ebfcecc5](https://linux-hardware.org/?probe=f5ebfcecc5) | Jan 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [56cb1ce2a6](https://linux-hardware.org/?probe=56cb1ce2a6) | Jan 27, 2023 |
| Acer          | Aspire ES1-572              | Notebook    | [9f745ecc18](https://linux-hardware.org/?probe=9f745ecc18) | Jan 27, 2023 |
| Acer          | Aspire E5-553G              | Notebook    | [e851efaf39](https://linux-hardware.org/?probe=e851efaf39) | Jan 27, 2023 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | Notebook    | [ff67a5eb33](https://linux-hardware.org/?probe=ff67a5eb33) | Jan 27, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [bd0b1f7e94](https://linux-hardware.org/?probe=bd0b1f7e94) | Jan 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [9912417dc3](https://linux-hardware.org/?probe=9912417dc3) | Jan 27, 2023 |
| Gigabyte      | J3455N-D3H                  | Desktop     | [3eb9131ab1](https://linux-hardware.org/?probe=3eb9131ab1) | Jan 27, 2023 |
| HP            | 8054                        | Desktop     | [864f5f225e](https://linux-hardware.org/?probe=864f5f225e) | Jan 26, 2023 |
| Acer          | Aspire ES1-411              | Notebook    | [110767fd86](https://linux-hardware.org/?probe=110767fd86) | Jan 26, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [4109360c56](https://linux-hardware.org/?probe=4109360c56) | Jan 26, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [a22071f9ec](https://linux-hardware.org/?probe=a22071f9ec) | Jan 26, 2023 |
| Dell          | G3 3500                     | Notebook    | [ea11767144](https://linux-hardware.org/?probe=ea11767144) | Jan 26, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [4ad0b3594f](https://linux-hardware.org/?probe=4ad0b3594f) | Jan 26, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [4a3c63f3f0](https://linux-hardware.org/?probe=4a3c63f3f0) | Jan 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [2026175299](https://linux-hardware.org/?probe=2026175299) | Jan 26, 2023 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [3fbe56012b](https://linux-hardware.org/?probe=3fbe56012b) | Jan 25, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [702b3c77fc](https://linux-hardware.org/?probe=702b3c77fc) | Jan 25, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [f04915614f](https://linux-hardware.org/?probe=f04915614f) | Jan 25, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [0ef51b9eda](https://linux-hardware.org/?probe=0ef51b9eda) | Jan 25, 2023 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [ec43ef5c17](https://linux-hardware.org/?probe=ec43ef5c17) | Jan 25, 2023 |
| ASUSTek       | TUF Gaming FX505DY_TUF50... | Notebook    | [92a3e34781](https://linux-hardware.org/?probe=92a3e34781) | Jan 24, 2023 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [d815a80782](https://linux-hardware.org/?probe=d815a80782) | Jan 24, 2023 |
| Dell          | Latitude E7470              | Notebook    | [5258f49771](https://linux-hardware.org/?probe=5258f49771) | Jan 24, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [270a9bf553](https://linux-hardware.org/?probe=270a9bf553) | Jan 24, 2023 |
| TUXEDO        | Unknown                     | Notebook    | [5973888b27](https://linux-hardware.org/?probe=5973888b27) | Jan 24, 2023 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [d2c9a02f60](https://linux-hardware.org/?probe=d2c9a02f60) | Jan 24, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [78b817b650](https://linux-hardware.org/?probe=78b817b650) | Jan 24, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [81c1e35182](https://linux-hardware.org/?probe=81c1e35182) | Jan 24, 2023 |
| Dell          | Latitude E7470              | Notebook    | [647c279ad4](https://linux-hardware.org/?probe=647c279ad4) | Jan 24, 2023 |
| Dell          | XPS 13 9365                 | Convertible | [f3fb4632c2](https://linux-hardware.org/?probe=f3fb4632c2) | Jan 24, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [fabda16ea6](https://linux-hardware.org/?probe=fabda16ea6) | Jan 23, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [4c6da4840e](https://linux-hardware.org/?probe=4c6da4840e) | Jan 23, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [45f94cdedc](https://linux-hardware.org/?probe=45f94cdedc) | Jan 23, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [b00e46e17f](https://linux-hardware.org/?probe=b00e46e17f) | Jan 23, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [85bfcb35ff](https://linux-hardware.org/?probe=85bfcb35ff) | Jan 23, 2023 |
| HP            | ZBook x2 G4                 | Tablet      | [f2799f616c](https://linux-hardware.org/?probe=f2799f616c) | Jan 23, 2023 |
| Fujitsu       | LIFEBOOK U9311A             | Notebook    | [6bdcfeae43](https://linux-hardware.org/?probe=6bdcfeae43) | Jan 23, 2023 |
| HP            | 2B2C                        | Desktop     | [01cb4bc77f](https://linux-hardware.org/?probe=01cb4bc77f) | Jan 23, 2023 |
| T-bao         | MINI PC V1.0                | Desktop     | [6d1c897198](https://linux-hardware.org/?probe=6d1c897198) | Jan 23, 2023 |
| MSI           | B150 PC MATE                | Desktop     | [741901eb8f](https://linux-hardware.org/?probe=741901eb8f) | Jan 23, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [023f1e3cdc](https://linux-hardware.org/?probe=023f1e3cdc) | Jan 23, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [1a9aaa1cb2](https://linux-hardware.org/?probe=1a9aaa1cb2) | Jan 22, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [4ed27b0b56](https://linux-hardware.org/?probe=4ed27b0b56) | Jan 22, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [9beaa4240c](https://linux-hardware.org/?probe=9beaa4240c) | Jan 22, 2023 |
| Lenovo        | ThinkPad P51 20HJS16Q0K     | Notebook    | [00e6c3575f](https://linux-hardware.org/?probe=00e6c3575f) | Jan 22, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [ae3846db38](https://linux-hardware.org/?probe=ae3846db38) | Jan 22, 2023 |
| Lenovo        | ThinkPad L430 2466DS2       | Notebook    | [8be9a889b7](https://linux-hardware.org/?probe=8be9a889b7) | Jan 22, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [14a5fa99db](https://linux-hardware.org/?probe=14a5fa99db) | Jan 22, 2023 |
| Dell          | G3 3500                     | Notebook    | [b3a545ee30](https://linux-hardware.org/?probe=b3a545ee30) | Jan 22, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [0ba680dd8f](https://linux-hardware.org/?probe=0ba680dd8f) | Jan 22, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [15b2f3fc5e](https://linux-hardware.org/?probe=15b2f3fc5e) | Jan 22, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [77a744c052](https://linux-hardware.org/?probe=77a744c052) | Jan 22, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [082d1b40bc](https://linux-hardware.org/?probe=082d1b40bc) | Jan 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [cd1f6d8306](https://linux-hardware.org/?probe=cd1f6d8306) | Jan 21, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [51234f64dd](https://linux-hardware.org/?probe=51234f64dd) | Jan 21, 2023 |
| Lenovo        | IdeaPad Slim 7 14ITL05 8... | Notebook    | [45bc9c5f3f](https://linux-hardware.org/?probe=45bc9c5f3f) | Jan 21, 2023 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | Desktop     | [0d70d03543](https://linux-hardware.org/?probe=0d70d03543) | Jan 21, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [b4591be73d](https://linux-hardware.org/?probe=b4591be73d) | Jan 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f33b08f626](https://linux-hardware.org/?probe=f33b08f626) | Jan 21, 2023 |
| Sony          | VPCF13Z1E                   | Notebook    | [3eaeffde09](https://linux-hardware.org/?probe=3eaeffde09) | Jan 21, 2023 |
| Gigabyte      | GB-BRR7H-4800               | Desktop     | [0f0f1ed390](https://linux-hardware.org/?probe=0f0f1ed390) | Jan 20, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [b6b4b01344](https://linux-hardware.org/?probe=b6b4b01344) | Jan 20, 2023 |
| MSI           | GP66 Leopard 11UH           | Notebook    | [cf6837bb85](https://linux-hardware.org/?probe=cf6837bb85) | Jan 20, 2023 |
| Dell          | Vostro 5620                 | Notebook    | [e70af512c8](https://linux-hardware.org/?probe=e70af512c8) | Jan 20, 2023 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [9b4b20b28d](https://linux-hardware.org/?probe=9b4b20b28d) | Jan 20, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [169ba5d31f](https://linux-hardware.org/?probe=169ba5d31f) | Jan 20, 2023 |
| Unknown       | Unknown                     | Notebook    | [1de254a697](https://linux-hardware.org/?probe=1de254a697) | Jan 20, 2023 |
| Dell          | G3 3579                     | Notebook    | [d418b797c8](https://linux-hardware.org/?probe=d418b797c8) | Jan 20, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [f872a64ba1](https://linux-hardware.org/?probe=f872a64ba1) | Jan 20, 2023 |
| HP            | 1000                        | Notebook    | [62ee01ee38](https://linux-hardware.org/?probe=62ee01ee38) | Jan 20, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [02089f3393](https://linux-hardware.org/?probe=02089f3393) | Jan 20, 2023 |
| Lenovo        | IdeaPad Duet 5 12IAU7 82... | Tablet      | [065167a01c](https://linux-hardware.org/?probe=065167a01c) | Jan 19, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [01f3a78934](https://linux-hardware.org/?probe=01f3a78934) | Jan 19, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [ebd319efff](https://linux-hardware.org/?probe=ebd319efff) | Jan 19, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [3eb4809e32](https://linux-hardware.org/?probe=3eb4809e32) | Jan 19, 2023 |
| ASUSTek       | H110M-C/BR                  | Desktop     | [58bed7db63](https://linux-hardware.org/?probe=58bed7db63) | Jan 19, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [0c77a64f45](https://linux-hardware.org/?probe=0c77a64f45) | Jan 18, 2023 |
| MSI           | MPG Z490 GAMING PLUS        | Desktop     | [457c3d4d50](https://linux-hardware.org/?probe=457c3d4d50) | Jan 18, 2023 |
| Lenovo        | ThinkPad X1 Titanium Gen... | Convertible | [cda19bda99](https://linux-hardware.org/?probe=cda19bda99) | Jan 18, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [c0667c5ea5](https://linux-hardware.org/?probe=c0667c5ea5) | Jan 18, 2023 |
| HP            | ProBook 640 G5              | Notebook    | [095355c9fc](https://linux-hardware.org/?probe=095355c9fc) | Jan 18, 2023 |
| MSI           | MAG B550M MORTAR            | Desktop     | [bcae5d5664](https://linux-hardware.org/?probe=bcae5d5664) | Jan 18, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [1aac8c57f8](https://linux-hardware.org/?probe=1aac8c57f8) | Jan 18, 2023 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [273e93cce5](https://linux-hardware.org/?probe=273e93cce5) | Jan 18, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [987dcf118c](https://linux-hardware.org/?probe=987dcf118c) | Jan 17, 2023 |
| Sony          | VPCF13Z1E                   | Notebook    | [aa93abde02](https://linux-hardware.org/?probe=aa93abde02) | Jan 17, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [133972f199](https://linux-hardware.org/?probe=133972f199) | Jan 17, 2023 |
| MSI           | GP66 Leopard 11UH           | Notebook    | [269015d6a4](https://linux-hardware.org/?probe=269015d6a4) | Jan 17, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [8474e8ce69](https://linux-hardware.org/?probe=8474e8ce69) | Jan 17, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [a5ddfa16b9](https://linux-hardware.org/?probe=a5ddfa16b9) | Jan 17, 2023 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [ea58101334](https://linux-hardware.org/?probe=ea58101334) | Jan 17, 2023 |
| Lenovo        | ThinkPad X230 2325CW1       | Notebook    | [44a8ae0b56](https://linux-hardware.org/?probe=44a8ae0b56) | Jan 17, 2023 |
| BANGHO        | MOV                         | Notebook    | [bc4f98d4ff](https://linux-hardware.org/?probe=bc4f98d4ff) | Jan 17, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [11ca9b863c](https://linux-hardware.org/?probe=11ca9b863c) | Jan 16, 2023 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | Notebook    | [5b56cf615b](https://linux-hardware.org/?probe=5b56cf615b) | Jan 16, 2023 |
| MSI           | GE66 Raider 10SF            | Notebook    | [55f5300c59](https://linux-hardware.org/?probe=55f5300c59) | Jan 16, 2023 |
| Lenovo        | Legion R70002021 82JW       | Notebook    | [5e5628739f](https://linux-hardware.org/?probe=5e5628739f) | Jan 16, 2023 |
| Lenovo        | IdeaPad 5-15ARE05 81YQ      | Notebook    | [4c9bb70ea2](https://linux-hardware.org/?probe=4c9bb70ea2) | Jan 16, 2023 |
| Lenovo        | IdeaPad Slim 7 Carbon 14... | Notebook    | [620185bf98](https://linux-hardware.org/?probe=620185bf98) | Jan 15, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [0e57f4ecbe](https://linux-hardware.org/?probe=0e57f4ecbe) | Jan 15, 2023 |
| Foxconn       | nT-i2000 Series PCB         | Desktop     | [a879fdd461](https://linux-hardware.org/?probe=a879fdd461) | Jan 15, 2023 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Server      | [bd3c9aa4fd](https://linux-hardware.org/?probe=bd3c9aa4fd) | Jan 15, 2023 |
| Lenovo        | ThinkPad E590 20NCS00800    | Notebook    | [8751d5b445](https://linux-hardware.org/?probe=8751d5b445) | Jan 15, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [f5246578fe](https://linux-hardware.org/?probe=f5246578fe) | Jan 15, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [fdf3113afb](https://linux-hardware.org/?probe=fdf3113afb) | Jan 15, 2023 |
| HP            | Pavilion Laptop 14-ce0xx... | Notebook    | [dd0a234ebb](https://linux-hardware.org/?probe=dd0a234ebb) | Jan 14, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [482cc76bce](https://linux-hardware.org/?probe=482cc76bce) | Jan 14, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [662223c5f6](https://linux-hardware.org/?probe=662223c5f6) | Jan 14, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [77adbc7487](https://linux-hardware.org/?probe=77adbc7487) | Jan 14, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [e430030b47](https://linux-hardware.org/?probe=e430030b47) | Jan 14, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [bff6278ed8](https://linux-hardware.org/?probe=bff6278ed8) | Jan 14, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [8fbf586d24](https://linux-hardware.org/?probe=8fbf586d24) | Jan 14, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [3365f7d56f](https://linux-hardware.org/?probe=3365f7d56f) | Jan 14, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [5de8333ea3](https://linux-hardware.org/?probe=5de8333ea3) | Jan 14, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [d5fb8523c7](https://linux-hardware.org/?probe=d5fb8523c7) | Jan 14, 2023 |
| ASUSTek       | ROG STRIX X370-F GAMING     | Desktop     | [fcda893618](https://linux-hardware.org/?probe=fcda893618) | Jan 13, 2023 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [e7bab74a13](https://linux-hardware.org/?probe=e7bab74a13) | Jan 13, 2023 |
| Dell          | Latitude E6430              | Notebook    | [5951bc10ca](https://linux-hardware.org/?probe=5951bc10ca) | Jan 13, 2023 |
| MSI           | 970A-G46                    | Desktop     | [32479ec724](https://linux-hardware.org/?probe=32479ec724) | Jan 13, 2023 |
| TUXEDO        | Unknown                     | Notebook    | [5721ffbc43](https://linux-hardware.org/?probe=5721ffbc43) | Jan 13, 2023 |
| ASUSTek       | N53SM                       | Notebook    | [fdf56c0639](https://linux-hardware.org/?probe=fdf56c0639) | Jan 13, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [25a1763f73](https://linux-hardware.org/?probe=25a1763f73) | Jan 13, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [e4912e6bfc](https://linux-hardware.org/?probe=e4912e6bfc) | Jan 12, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [8322c3202b](https://linux-hardware.org/?probe=8322c3202b) | Jan 12, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [855dfb5e62](https://linux-hardware.org/?probe=855dfb5e62) | Jan 12, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [998a408a04](https://linux-hardware.org/?probe=998a408a04) | Jan 12, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [5ee23ee475](https://linux-hardware.org/?probe=5ee23ee475) | Jan 12, 2023 |
| Notebook      | NS50MU                      | Notebook    | [7d94a36b67](https://linux-hardware.org/?probe=7d94a36b67) | Jan 12, 2023 |
| Nvidia        | AN-M2                       | Desktop     | [8a7aad3266](https://linux-hardware.org/?probe=8a7aad3266) | Jan 12, 2023 |
| Dell          | 0DXJD9 A01                  | Desktop     | [78549912fa](https://linux-hardware.org/?probe=78549912fa) | Jan 12, 2023 |
| MSI           | Z490-A PRO                  | Desktop     | [bbcffca1e1](https://linux-hardware.org/?probe=bbcffca1e1) | Jan 11, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [54711252e5](https://linux-hardware.org/?probe=54711252e5) | Jan 11, 2023 |
| Dell          | 0K3CM7 A00                  | Desktop     | [2c317eaef8](https://linux-hardware.org/?probe=2c317eaef8) | Jan 11, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [a1e541c1b3](https://linux-hardware.org/?probe=a1e541c1b3) | Jan 11, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [5076e36526](https://linux-hardware.org/?probe=5076e36526) | Jan 11, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2455d11a72](https://linux-hardware.org/?probe=2455d11a72) | Jan 11, 2023 |
| Lenovo        | IdeaPad 5-15ARE05 81YQ      | Notebook    | [b5d071346b](https://linux-hardware.org/?probe=b5d071346b) | Jan 11, 2023 |
| HP            | 8767 A                      | Desktop     | [7b2c61c215](https://linux-hardware.org/?probe=7b2c61c215) | Jan 11, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [a57b3e3df6](https://linux-hardware.org/?probe=a57b3e3df6) | Jan 11, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [694c5c31f9](https://linux-hardware.org/?probe=694c5c31f9) | Jan 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [3b767cfcef](https://linux-hardware.org/?probe=3b767cfcef) | Jan 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [ac7ae437c8](https://linux-hardware.org/?probe=ac7ae437c8) | Jan 10, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [47ac5c5ee1](https://linux-hardware.org/?probe=47ac5c5ee1) | Jan 10, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [8e857e93de](https://linux-hardware.org/?probe=8e857e93de) | Jan 10, 2023 |
| Dell          | Latitude 3570               | Notebook    | [2748121a05](https://linux-hardware.org/?probe=2748121a05) | Jan 10, 2023 |
| Gigabyte      | H410M S2H V3                | Desktop     | [1ec26d7d15](https://linux-hardware.org/?probe=1ec26d7d15) | Jan 10, 2023 |
| Dell          | Inspiron 5502               | Notebook    | [b09655552e](https://linux-hardware.org/?probe=b09655552e) | Jan 09, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [7193f85a8c](https://linux-hardware.org/?probe=7193f85a8c) | Jan 09, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [3e39bca3ed](https://linux-hardware.org/?probe=3e39bca3ed) | Jan 09, 2023 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [8f9cd3c097](https://linux-hardware.org/?probe=8f9cd3c097) | Jan 09, 2023 |
| MSI           | Modern 14 B11MOU            | Notebook    | [0db2c1a27c](https://linux-hardware.org/?probe=0db2c1a27c) | Jan 09, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [9bf425bc2d](https://linux-hardware.org/?probe=9bf425bc2d) | Jan 09, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [153884836e](https://linux-hardware.org/?probe=153884836e) | Jan 09, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [06f9209282](https://linux-hardware.org/?probe=06f9209282) | Jan 08, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [b6e56e8d87](https://linux-hardware.org/?probe=b6e56e8d87) | Jan 08, 2023 |
| HP            | ZHAN 66 Pro G1              | Notebook    | [76e588ab0a](https://linux-hardware.org/?probe=76e588ab0a) | Jan 08, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [66ba6bf6d3](https://linux-hardware.org/?probe=66ba6bf6d3) | Jan 08, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [7a02a3b48b](https://linux-hardware.org/?probe=7a02a3b48b) | Jan 08, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [faf4eff378](https://linux-hardware.org/?probe=faf4eff378) | Jan 08, 2023 |
| Toshiba       | Satellite C55Dt-A           | Notebook    | [e7b268e7e5](https://linux-hardware.org/?probe=e7b268e7e5) | Jan 08, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [a885b118ab](https://linux-hardware.org/?probe=a885b118ab) | Jan 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | Notebook    | [14273d90fd](https://linux-hardware.org/?probe=14273d90fd) | Jan 08, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [27c42e99db](https://linux-hardware.org/?probe=27c42e99db) | Jan 08, 2023 |
| MSI           | Z270 PC MATE                | Desktop     | [4d780d6bf9](https://linux-hardware.org/?probe=4d780d6bf9) | Jan 08, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | Notebook    | [7ce97bb3ec](https://linux-hardware.org/?probe=7ce97bb3ec) | Jan 08, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [cfabe67812](https://linux-hardware.org/?probe=cfabe67812) | Jan 07, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [ddae48cdbb](https://linux-hardware.org/?probe=ddae48cdbb) | Jan 07, 2023 |
| HP            | Pavilion dv6                | Notebook    | [7e1ac76fc9](https://linux-hardware.org/?probe=7e1ac76fc9) | Jan 07, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [8b38f9336f](https://linux-hardware.org/?probe=8b38f9336f) | Jan 07, 2023 |
| HP            | ZBook 15                    | Notebook    | [3e2f33f6c1](https://linux-hardware.org/?probe=3e2f33f6c1) | Jan 07, 2023 |
| Dell          | Inspiron 5515               | Notebook    | [3b8a41b7af](https://linux-hardware.org/?probe=3b8a41b7af) | Jan 07, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [7a2744ca03](https://linux-hardware.org/?probe=7a2744ca03) | Jan 06, 2023 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [aa21c2b75f](https://linux-hardware.org/?probe=aa21c2b75f) | Jan 06, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [6cd2288696](https://linux-hardware.org/?probe=6cd2288696) | Jan 06, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [ed168f4e29](https://linux-hardware.org/?probe=ed168f4e29) | Jan 05, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | Notebook    | [2227400f4c](https://linux-hardware.org/?probe=2227400f4c) | Jan 05, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [a2a0663674](https://linux-hardware.org/?probe=a2a0663674) | Jan 05, 2023 |
| Dell          | 0HY9JP A01                  | Desktop     | [0532ee0c1e](https://linux-hardware.org/?probe=0532ee0c1e) | Jan 05, 2023 |
| Acer          | IPMBW-BR                    | All in one  | [1485ad36a9](https://linux-hardware.org/?probe=1485ad36a9) | Jan 05, 2023 |
| ASRock        | H310M-HDV/M.2               | Desktop     | [cf98b88234](https://linux-hardware.org/?probe=cf98b88234) | Jan 05, 2023 |
| Gigabyte      | AERO 16 XE4                 | Notebook    | [e05dd3f797](https://linux-hardware.org/?probe=e05dd3f797) | Jan 05, 2023 |
| ASRock        | X570 Steel Legend           | Desktop     | [584234b202](https://linux-hardware.org/?probe=584234b202) | Jan 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [e4a7ff414a](https://linux-hardware.org/?probe=e4a7ff414a) | Jan 05, 2023 |
| Lenovo        | B40-70 20392                | Notebook    | [71c1ae09af](https://linux-hardware.org/?probe=71c1ae09af) | Jan 05, 2023 |
| MSI           | GP66 Leopard 11UH           | Notebook    | [63f0536a21](https://linux-hardware.org/?probe=63f0536a21) | Jan 04, 2023 |
| Valve         | Jupiter                     | Notebook    | [e7e5475978](https://linux-hardware.org/?probe=e7e5475978) | Jan 04, 2023 |
| MSI           | Prestige 15 A11SCX          | Notebook    | [86850a5925](https://linux-hardware.org/?probe=86850a5925) | Jan 04, 2023 |
| Lenovo        | ThinkPad X230 2320LFG       | Notebook    | [e8e510f4e6](https://linux-hardware.org/?probe=e8e510f4e6) | Jan 04, 2023 |
| Gigabyte      | H87-D3H-CF                  | Desktop     | [5b13eb0dad](https://linux-hardware.org/?probe=5b13eb0dad) | Jan 04, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [5b2857e18b](https://linux-hardware.org/?probe=5b2857e18b) | Jan 04, 2023 |
| Intel         | NUC13SBBi9 M58736-302       | Mini pc     | [f30031a156](https://linux-hardware.org/?probe=f30031a156) | Jan 04, 2023 |
| Lenovo        | ThinkPad W541 20EFCTO1WW    | Notebook    | [a10abfb25a](https://linux-hardware.org/?probe=a10abfb25a) | Jan 03, 2023 |
| Gigabyte      | Z490M GAMING X              | Desktop     | [9012a42d6e](https://linux-hardware.org/?probe=9012a42d6e) | Jan 03, 2023 |
| Acer          | Aspire R7-572G              | Notebook    | [56e5de8317](https://linux-hardware.org/?probe=56e5de8317) | Jan 03, 2023 |
| ASUSTek       | Maximus IX CODE             | Desktop     | [25d993017e](https://linux-hardware.org/?probe=25d993017e) | Jan 02, 2023 |
| Acer          | Aspire A515-57G             | Notebook    | [854bee8efb](https://linux-hardware.org/?probe=854bee8efb) | Jan 02, 2023 |
| HUAWEI        | MACH-WX9                    | Notebook    | [525ea65bc1](https://linux-hardware.org/?probe=525ea65bc1) | Jan 02, 2023 |
| HP            | ProBook 635 Aero G8         | Notebook    | [f710248f3c](https://linux-hardware.org/?probe=f710248f3c) | Jan 02, 2023 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [bc36d65732](https://linux-hardware.org/?probe=bc36d65732) | Jan 02, 2023 |
| PCWare        | IPMH110G                    | Desktop     | [a795f33f7a](https://linux-hardware.org/?probe=a795f33f7a) | Jan 02, 2023 |
| Toshiba       | Satellite P755              | Notebook    | [1296e73b50](https://linux-hardware.org/?probe=1296e73b50) | Jan 02, 2023 |
| Lenovo        | ThinkPad T480 20L5000BGE    | Notebook    | [acdb8c643e](https://linux-hardware.org/?probe=acdb8c643e) | Jan 02, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 3 ... | Convertible | [18d10ee7ac](https://linux-hardware.org/?probe=18d10ee7ac) | Jan 01, 2023 |
| Gigabyte      | B560M AORUS PRO AX          | Desktop     | [30abdaa93b](https://linux-hardware.org/?probe=30abdaa93b) | Jan 01, 2023 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | Notebook    | [0179007813](https://linux-hardware.org/?probe=0179007813) | Jan 01, 2023 |
| Acer          | Aspire A515-47              | Notebook    | [aaf0830ffc](https://linux-hardware.org/?probe=aaf0830ffc) | Jan 01, 2023 |
| ASUSTek       | X550VX                      | Notebook    | [e83ccf9576](https://linux-hardware.org/?probe=e83ccf9576) | Jan 01, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [a6540a8761](https://linux-hardware.org/?probe=a6540a8761) | Jan 01, 2023 |
| Dell          | Latitude E7450              | Notebook    | [f48717bb6f](https://linux-hardware.org/?probe=f48717bb6f) | Jan 01, 2023 |
| MSI           | B450 GAMING PRO CARBON M... | Desktop     | [0db2db0d47](https://linux-hardware.org/?probe=0db2db0d47) | Jan 01, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [162ad451eb](https://linux-hardware.org/?probe=162ad451eb) | Dec 31, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ea3b140a7f](https://linux-hardware.org/?probe=ea3b140a7f) | Dec 31, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [a30f96dea4](https://linux-hardware.org/?probe=a30f96dea4) | Dec 31, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [ecf944f539](https://linux-hardware.org/?probe=ecf944f539) | Dec 31, 2022 |
| ASUSTek       | PRIME B250M-K               | Desktop     | [9db6f0fda7](https://linux-hardware.org/?probe=9db6f0fda7) | Dec 31, 2022 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [0031785936](https://linux-hardware.org/?probe=0031785936) | Dec 31, 2022 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [4bd2096c80](https://linux-hardware.org/?probe=4bd2096c80) | Dec 31, 2022 |
| Dell          | Latitude E6430              | Notebook    | [de9b03cf29](https://linux-hardware.org/?probe=de9b03cf29) | Dec 31, 2022 |
| Dell          | Latitude 3420               | Notebook    | [05095533cd](https://linux-hardware.org/?probe=05095533cd) | Dec 31, 2022 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [fc2f55c02e](https://linux-hardware.org/?probe=fc2f55c02e) | Dec 31, 2022 |
| Dell          | G3 3579                     | Notebook    | [cad48f0160](https://linux-hardware.org/?probe=cad48f0160) | Dec 30, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [83810bf0a9](https://linux-hardware.org/?probe=83810bf0a9) | Dec 30, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [7b3c89637b](https://linux-hardware.org/?probe=7b3c89637b) | Dec 30, 2022 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [eab8778810](https://linux-hardware.org/?probe=eab8778810) | Dec 30, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [4409746122](https://linux-hardware.org/?probe=4409746122) | Dec 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [d7806eec79](https://linux-hardware.org/?probe=d7806eec79) | Dec 30, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [da9b785d2a](https://linux-hardware.org/?probe=da9b785d2a) | Dec 30, 2022 |
| ASRock        | B650M PG Riptide            | Desktop     | [614e6307eb](https://linux-hardware.org/?probe=614e6307eb) | Dec 29, 2022 |
| HP            | ProBook 430 G8 Notebook ... | Notebook    | [3f4178001d](https://linux-hardware.org/?probe=3f4178001d) | Dec 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [ce66958f69](https://linux-hardware.org/?probe=ce66958f69) | Dec 29, 2022 |
| Acer          | Aspire A715-41G             | Notebook    | [92f3c92191](https://linux-hardware.org/?probe=92f3c92191) | Dec 29, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [587aa5f819](https://linux-hardware.org/?probe=587aa5f819) | Dec 29, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [e6ac6cac6c](https://linux-hardware.org/?probe=e6ac6cac6c) | Dec 29, 2022 |
| Lenovo        | ThinkPad E580 20KS001RIX    | Notebook    | [4ca01731b4](https://linux-hardware.org/?probe=4ca01731b4) | Dec 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1cf63ef1ad](https://linux-hardware.org/?probe=1cf63ef1ad) | Dec 28, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [1219225d5d](https://linux-hardware.org/?probe=1219225d5d) | Dec 28, 2022 |
| Acer          | AO756                       | Notebook    | [d0cf64acd1](https://linux-hardware.org/?probe=d0cf64acd1) | Dec 28, 2022 |
| Acer          | Swift SF314-41              | Notebook    | [2923c4c0fc](https://linux-hardware.org/?probe=2923c4c0fc) | Dec 28, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [71d2c76079](https://linux-hardware.org/?probe=71d2c76079) | Dec 28, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Arch/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Arch Rolling     | 3164      | 51.27%  |
| Arch             | 2983      | 48.34%  |
| Arch V20.4.11    | 3         | 0.05%   |
| Arch V19.11.3    | 3         | 0.05%   |
| Arch V20.5.7     | 2         | 0.03%   |
| Arch V20.3.4     | 2         | 0.03%   |
| Arch V19.04.4    | 2         | 0.03%   |
| Arch Workstation | 1         | 0.02%   |
| Arch V6.9.2      | 1         | 0.02%   |
| Arch V19.09.1    | 1         | 0.02%   |
| Arch V19.07.9    | 1         | 0.02%   |
| Arch V19.07.11   | 1         | 0.02%   |
| Arch V19.06.1    | 1         | 0.02%   |
| Arch V19.05.2    | 1         | 0.02%   |
| Arch V19.01.4    | 1         | 0.02%   |
| Arch Breaking    | 1         | 0.02%   |
| Arch 2020.09.05  | 1         | 0.02%   |
| Arch 20.08.3     | 1         | 0.02%   |
| Arch 2.7         | 1         | 0.02%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| Arch | 6002      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version         | Computers | Percent |
|-----------------|-----------|---------|
| 5.17.1-arch1-1  | 85        | 1.2%    |
| 6.0.2-arch1-1   | 71        | 1%      |
| 5.8.5-arch1-1   | 70        | 0.98%   |
| 5.9.14-arch1-1  | 61        | 0.86%   |
| 5.9.1-arch1-1   | 60        | 0.84%   |
| 5.17.5-arch1-1  | 53        | 0.75%   |
| 5.17.9-arch1-1  | 51        | 0.72%   |
| 5.8.12-arch1-1  | 48        | 0.68%   |
| 5.8.10-arch1-1  | 48        | 0.68%   |
| 5.8.14-arch1-1  | 47        | 0.66%   |
| 5.7.12-arch1-1  | 46        | 0.65%   |
| 6.1.1-arch1-1   | 45        | 0.63%   |
| 5.13.13-arch1-1 | 45        | 0.63%   |
| 6.2.8-arch1-1   | 44        | 0.62%   |
| 5.8.1-arch1-1   | 43        | 0.6%    |
| 6.0.9-arch1-1   | 42        | 0.59%   |
| 5.11.16-arch1-1 | 42        | 0.59%   |
| 6.0.12-arch1-1  | 41        | 0.58%   |
| 6.2.10-arch1-1  | 37        | 0.52%   |
| 6.1.12-arch1-1  | 37        | 0.52%   |
| 5.6.15-arch1-1  | 37        | 0.52%   |
| 5.18.16-arch1-1 | 34        | 0.48%   |
| 5.11.6-arch1-1  | 34        | 0.48%   |
| 5.11.11-arch1-1 | 34        | 0.48%   |
| 6.1.8-arch1-1   | 33        | 0.46%   |
| 5.12.15-arch1-1 | 33        | 0.46%   |
| 5.10.16-arch1-1 | 33        | 0.46%   |
| 6.0.10-arch2-1  | 32        | 0.45%   |
| 5.19.13-arch1-1 | 32        | 0.45%   |
| 5.18.1-arch1-1  | 32        | 0.45%   |
| 6.0.7-arch1-1   | 31        | 0.44%   |
| 5.8.3-arch1-1   | 31        | 0.44%   |
| 5.19.7-arch1-1  | 31        | 0.44%   |
| 5.15.7-arch1-1  | 31        | 0.44%   |
| 5.14.14-arch1-1 | 31        | 0.44%   |
| 6.2.2-arch1-1   | 30        | 0.42%   |
| 6.1.9-arch1-1   | 30        | 0.42%   |
| 6.0.8-arch1-1   | 30        | 0.42%   |
| 5.9.11-arch2-1  | 30        | 0.42%   |
| 5.9.10-arch1-1  | 30        | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.17.1  | 105       | 1.48%   |
| 5.8.5   | 92        | 1.29%   |
| 6.0.2   | 90        | 1.27%   |
| 5.9.1   | 77        | 1.08%   |
| 5.8.12  | 73        | 1.03%   |
| 5.9.14  | 72        | 1.01%   |
| 5.17.5  | 70        | 0.98%   |
| 5.8.14  | 63        | 0.89%   |
| 5.8.10  | 62        | 0.87%   |
| 5.17.9  | 61        | 0.86%   |
| 6.1.1   | 56        | 0.79%   |
| 5.13.13 | 56        | 0.79%   |
| 6.1.12  | 53        | 0.75%   |
| 5.8.1   | 53        | 0.75%   |
| 5.7.12  | 53        | 0.75%   |
| 6.2.8   | 52        | 0.73%   |
| 6.2.2   | 52        | 0.73%   |
| 6.0.9   | 52        | 0.73%   |
| 5.11.6  | 52        | 0.73%   |
| 6.1.9   | 51        | 0.72%   |
| 5.11.16 | 51        | 0.72%   |
| 6.0.12  | 50        | 0.7%    |
| 6.2.10  | 48        | 0.68%   |
| 5.11.2  | 43        | 0.6%    |
| 6.1.8   | 42        | 0.59%   |
| 6.0.8   | 42        | 0.59%   |
| 5.12.15 | 42        | 0.59%   |
| 5.10.16 | 42        | 0.59%   |
| 6.0.11  | 41        | 0.58%   |
| 5.19.7  | 41        | 0.58%   |
| 5.18.16 | 41        | 0.58%   |
| 5.11.11 | 41        | 0.58%   |
| 6.0.10  | 40        | 0.56%   |
| 5.19.13 | 40        | 0.56%   |
| 5.7.6   | 38        | 0.53%   |
| 5.6.15  | 38        | 0.53%   |
| 5.18.1  | 38        | 0.53%   |
| 5.15.7  | 38        | 0.53%   |
| 5.14.14 | 38        | 0.53%   |
| 5.12.14 | 38        | 0.53%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.8     | 522       | 7.63%   |
| 5.15    | 477       | 6.97%   |
| 6.0     | 411       | 6.01%   |
| 6.1     | 401       | 5.86%   |
| 5.9     | 384       | 5.61%   |
| 5.18    | 366       | 5.35%   |
| 5.10    | 355       | 5.19%   |
| 5.4     | 353       | 5.16%   |
| 5.11    | 350       | 5.11%   |
| 6.2     | 345       | 5.04%   |
| 5.19    | 343       | 5.01%   |
| 5.17    | 341       | 4.98%   |
| 5.12    | 309       | 4.51%   |
| 5.16    | 305       | 4.46%   |
| 5.6     | 263       | 3.84%   |
| 5.7     | 260       | 3.8%    |
| 5.14    | 237       | 3.46%   |
| 5.13    | 234       | 3.42%   |
| 5.5     | 148       | 2.16%   |
| 5.3     | 114       | 1.67%   |
| 4.19    | 56        | 0.82%   |
| 5.2     | 54        | 0.79%   |
| 5.0     | 41        | 0.6%    |
| 4.18    | 37        | 0.54%   |
| 5.1     | 32        | 0.47%   |
| 4.20    | 22        | 0.32%   |
| 4.17    | 19        | 0.28%   |
| 4.15    | 14        | 0.2%    |
| 4.14    | 10        | 0.15%   |
| 4.16    | 9         | 0.13%   |
| 4.9     | 5         | 0.07%   |
| 4.7     | 4         | 0.06%   |
| 4.6     | 4         | 0.06%   |
| 4.11    | 4         | 0.06%   |
| 4.8     | 3         | 0.04%   |
| 4.4     | 3         | 0.04%   |
| 4.13    | 3         | 0.04%   |
| 6.3     | 2         | 0.03%   |
| 4.10    | 2         | 0.03%   |
| 4.12    | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 5997      | 99.92%  |
| i686   | 5         | 0.08%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| GNOME                    | 2022      | 32.31%  |
| KDE5                     | 1559      | 24.91%  |
| Unknown                  | 793       | 12.67%  |
| XFCE                     | 484       | 7.73%   |
| i3                       | 310       | 4.95%   |
| KDE                      | 290       | 4.63%   |
| X-Cinnamon               | 86        | 1.37%   |
| MATE                     | 82        | 1.31%   |
| Budgie                   | 82        | 1.31%   |
| sway                     | 81        | 1.29%   |
| Cinnamon                 | 79        | 1.26%   |
| Deepin                   | 67        | 1.07%   |
| LXQt                     | 51        | 0.81%   |
| LXDE                     | 38        | 0.61%   |
| bspwm                    | 36        | 0.58%   |
| Hyprland                 | 33        | 0.53%   |
| awesome                  | 31        | 0.5%    |
| qtile                    | 19        | 0.3%    |
| openbox                  | 19        | 0.3%    |
| GNOME Flashback          | 15        | 0.24%   |
| xmonad                   | 13        | 0.21%   |
| Unity                    | 11        | 0.18%   |
| DWM                      | 11        | 0.18%   |
| GNOME Classic            | 7         | 0.11%   |
| LeftWM                   | 5         | 0.08%   |
| i3-with-shmlog           | 5         | 0.08%   |
| Enlightenment            | 4         | 0.06%   |
| river                    | 2         | 0.03%   |
| jwm                      | 2         | 0.03%   |
| ICEWM                    | 2         | 0.03%   |
| GNUstep                  | 2         | 0.03%   |
| dusk                     | 2         | 0.03%   |
| default                  | 2         | 0.03%   |
| chadwm                   | 2         | 0.03%   |
| /usr/bin/openbox-session | 2         | 0.03%   |
| Yaru:ubuntu:GNOME        | 1         | 0.02%   |
| xinitrc                  | 1         | 0.02%   |
| X-Generic                | 1         | 0.02%   |
| Wayfire                  | 1         | 0.02%   |
| sway:Unity               | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 3734      | 60.06%  |
| Wayland | 1466      | 23.58%  |
| Tty     | 578       | 9.3%    |
| Unknown | 438       | 7.05%   |
| Web     | 1         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2581      | 41.63%  |
| SDDM    | 1441      | 23.24%  |
| GDM     | 883       | 14.24%  |
| LightDM | 664       | 10.71%  |
| TDM     | 398       | 6.42%   |
| Ly      | 72        | 1.16%   |
| XDM     | 56        | 0.9%    |
| LXDM    | 51        | 0.82%   |
| SLiM    | 26        | 0.42%   |
| GREETD  | 17        | 0.27%   |
| NODM    | 4         | 0.06%   |
| EMPTTY  | 4         | 0.06%   |
| XINIT   | 1         | 0.02%   |
| MDM     | 1         | 0.02%   |
| KDM     | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 2972      | 48.43%  |
| Unknown    | 617       | 10.05%  |
| en_GB      | 356       | 5.8%    |
| C          | 313       | 5.1%    |
| de_DE      | 253       | 4.12%   |
| it_IT      | 190       | 3.1%    |
| ru_RU      | 188       | 3.06%   |
| pt_BR      | 164       | 2.67%   |
| fr_FR      | 139       | 2.26%   |
| pl_PL      | 83        | 1.35%   |
| en_CA      | 65        | 1.06%   |
| es_ES      | 64        | 1.04%   |
| en_IN      | 64        | 1.04%   |
| en_AU      | 63        | 1.03%   |
| zh_CN      | 60        | 0.98%   |
| en_IE      | 34        | 0.55%   |
| en_DK      | 28        | 0.46%   |
| es_MX      | 22        | 0.36%   |
| de_AT      | 21        | 0.34%   |
| hu_HU      | 20        | 0.33%   |
| es_AR      | 18        | 0.29%   |
| en_NZ      | 17        | 0.28%   |
| nl_NL      | 16        | 0.26%   |
| ja_JP      | 16        | 0.26%   |
| tr_TR      | 14        | 0.23%   |
| es_CO      | 14        | 0.23%   |
| es_CL      | 14        | 0.23%   |
| cs_CZ      | 14        | 0.23%   |
| ru_UA      | 13        | 0.21%   |
| pt_PT      | 13        | 0.21%   |
| en_US.UTF8 | 10        | 0.16%   |
| en_SG      | 10        | 0.16%   |
| sv_SE      | 9         | 0.15%   |
| lv_LV      | 9         | 0.15%   |
| en_ZA      | 9         | 0.15%   |
| en_DE      | 9         | 0.15%   |
| de_CH      | 9         | 0.15%   |
| fi_FI      | 8         | 0.13%   |
| uk_UA      | 7         | 0.11%   |
| ko_KR      | 7         | 0.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 3778      | 61.64%  |
| BIOS | 2351      | 38.36%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 4345      | 71.45%  |
| Btrfs    | 1233      | 20.28%  |
| Unknown  | 180       | 2.96%   |
| Xfs      | 149       | 2.45%   |
| F2fs     | 85        | 1.4%    |
| Zfs      | 36        | 0.59%   |
| Overlay  | 35        | 0.58%   |
| Ext2     | 8         | 0.13%   |
| XXXXX    | 4         | 0.07%   |
| Ext3     | 2         | 0.03%   |
| XXX4     | 1         | 0.02%   |
| Reiserfs | 1         | 0.02%   |
| Jfs      | 1         | 0.02%   |
| Aufs     | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 3836      | 62.99%  |
| Unknown | 1736      | 28.51%  |
| MBR     | 518       | 8.51%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 5246      | 86.21%  |
| Yes       | 839       | 13.79%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4218      | 69.08%  |
| Yes       | 1888      | 30.92%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| ASUSTek Computer       | 1152      | 19.19%  |
| Lenovo                 | 1081      | 18.01%  |
| Dell                   | 639       | 10.65%  |
| Hewlett-Packard        | 631       | 10.51%  |
| MSI                    | 503       | 8.38%   |
| Gigabyte Technology    | 494       | 8.23%   |
| ASRock                 | 312       | 5.2%    |
| Acer                   | 288       | 4.8%    |
| Apple                  | 94        | 1.57%   |
| Intel                  | 78        | 1.3%    |
| HUAWEI                 | 59        | 0.98%   |
| Samsung Electronics    | 56        | 0.93%   |
| Toshiba                | 45        | 0.75%   |
| Notebook               | 32        | 0.53%   |
| Microsoft              | 31        | 0.52%   |
| Unknown                | 31        | 0.52%   |
| Timi                   | 26        | 0.43%   |
| Google                 | 25        | 0.42%   |
| Sony                   | 24        | 0.4%    |
| Fujitsu                | 20        | 0.33%   |
| TUXEDO                 | 18        | 0.3%    |
| Framework              | 18        | 0.3%    |
| Alienware              | 18        | 0.3%    |
| Biostar                | 15        | 0.25%   |
| Razer                  | 13        | 0.22%   |
| LG Electronics         | 11        | 0.18%   |
| Avell High Performance | 11        | 0.18%   |
| System76               | 10        | 0.17%   |
| Pegatron               | 10        | 0.17%   |
| Medion                 | 10        | 0.17%   |
| ECS                    | 10        | 0.17%   |
| Schenker               | 9         | 0.15%   |
| Supermicro             | 8         | 0.13%   |
| Positivo               | 8         | 0.13%   |
| Packard Bell           | 8         | 0.13%   |
| MECHREVO               | 7         | 0.12%   |
| Huanan                 | 6         | 0.1%    |
| Chuwi                  | 6         | 0.1%    |
| ZOTAC                  | 5         | 0.08%   |
| Teclast                | 5         | 0.08%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| ASUS All Series                  | 58        | 0.97%   |
| Unknown                          | 54        | 0.9%    |
| MSI MS-7C02                      | 29        | 0.48%   |
| MSI MS-7C37                      | 28        | 0.47%   |
| ASUS TUF Gaming X570-PLUS        | 28        | 0.47%   |
| MSI MS-7B86                      | 22        | 0.37%   |
| Gigabyte B450M DS3H              | 22        | 0.37%   |
| Dell XPS 15 9570                 | 18        | 0.3%    |
| ASUS ROG STRIX B550-F GAMING     | 18        | 0.3%    |
| MSI MS-7A34                      | 17        | 0.28%   |
| Gigabyte X570 AORUS ELITE        | 17        | 0.28%   |
| ASUS ROG STRIX B450-F GAMING     | 17        | 0.28%   |
| Framework Laptop                 | 16        | 0.27%   |
| ASUS PRIME B450M-A               | 16        | 0.27%   |
| MSI MS-7C91                      | 15        | 0.25%   |
| MSI MS-7B89                      | 15        | 0.25%   |
| MSI MS-7B79                      | 15        | 0.25%   |
| MSI MS-7A38                      | 15        | 0.25%   |
| HP Notebook                      | 15        | 0.25%   |
| ASUS PRIME X470-PRO              | 15        | 0.25%   |
| ASUS PRIME X370-PRO              | 15        | 0.25%   |
| Gigabyte X470 AORUS ULTRA GAMING | 14        | 0.23%   |
| Dell XPS 15 9500                 | 14        | 0.23%   |
| Dell XPS 13 9360                 | 13        | 0.22%   |
| ASUS ROG STRIX X570-E GAMING     | 12        | 0.2%    |
| Gigabyte 970A-DS3P               | 11        | 0.18%   |
| Dell XPS 13 9380                 | 11        | 0.18%   |
| ASUS TUF Gaming B550-PLUS        | 11        | 0.18%   |
| ASUS ROG STRIX X470-F GAMING     | 11        | 0.18%   |
| ASUS PRIME A320M-K               | 11        | 0.18%   |
| ASRock X570 Taichi               | 11        | 0.18%   |
| MSI MS-7C56                      | 10        | 0.17%   |
| Gigabyte B450 AORUS ELITE        | 10        | 0.17%   |
| Dell Latitude E6430              | 10        | 0.17%   |
| Dell Inspiron 15 7000 Gaming     | 10        | 0.17%   |
| ASUS ROG Strix G513QY_G513QY     | 10        | 0.17%   |
| ASUS ROG STRIX B550-I GAMING     | 10        | 0.17%   |
| ASRock B450M Pro4                | 10        | 0.17%   |
| HUAWEI NBLK-WAX9X                | 9         | 0.15%   |
| HP EliteBook 840 G6              | 9         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 593       | 9.88%   |
| ASUS ROG           | 223       | 3.72%   |
| ASUS PRIME         | 194       | 3.23%   |
| Lenovo IdeaPad     | 189       | 3.15%   |
| Acer Aspire        | 170       | 2.83%   |
| Dell Inspiron      | 157       | 2.62%   |
| Dell XPS           | 154       | 2.57%   |
| Dell Latitude      | 141       | 2.35%   |
| ASUS TUF           | 132       | 2.2%    |
| HP Pavilion        | 114       | 1.9%    |
| HP EliteBook       | 99        | 1.65%   |
| HP Laptop          | 66        | 1.1%    |
| HP ENVY            | 64        | 1.07%   |
| Lenovo Legion      | 59        | 0.98%   |
| Gigabyte X570      | 58        | 0.97%   |
| ASUS All           | 58        | 0.97%   |
| HP ProBook         | 57        | 0.95%   |
| ASUS VivoBook      | 57        | 0.95%   |
| Lenovo Yoga        | 56        | 0.93%   |
| Dell Precision     | 54        | 0.9%    |
| Unknown            | 54        | 0.9%    |
| Dell OptiPlex      | 50        | 0.83%   |
| Acer Nitro         | 39        | 0.65%   |
| Toshiba Satellite  | 36        | 0.6%    |
| Gigabyte B450M     | 34        | 0.57%   |
| Microsoft Surface  | 31        | 0.52%   |
| Acer Swift         | 31        | 0.52%   |
| Dell Vostro        | 30        | 0.5%    |
| ASRock X570        | 30        | 0.5%    |
| MSI MS-7C02        | 29        | 0.48%   |
| Lenovo ThinkBook   | 29        | 0.48%   |
| ASUS Zenbook       | 29        | 0.48%   |
| ASUS ASUS          | 29        | 0.48%   |
| MSI MS-7C37        | 28        | 0.47%   |
| Gigabyte B450      | 28        | 0.47%   |
| HP Spectre         | 26        | 0.43%   |
| HP OMEN            | 24        | 0.4%    |
| HP Compaq          | 23        | 0.38%   |
| MSI MS-7B86        | 22        | 0.37%   |
| Lenovo ThinkCentre | 22        | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 904       | 15.06%  |
| 2019    | 858       | 14.3%   |
| 2020    | 779       | 12.98%  |
| 2017    | 521       | 8.68%   |
| 2021    | 503       | 8.38%   |
| 2016    | 352       | 5.86%   |
| 2012    | 335       | 5.58%   |
| 2015    | 305       | 5.08%   |
| 2013    | 300       | 5%      |
| 2014    | 297       | 4.95%   |
| 2011    | 251       | 4.18%   |
| 2022    | 220       | 3.67%   |
| 2010    | 150       | 2.5%    |
| 2008    | 89        | 1.48%   |
| 2009    | 81        | 1.35%   |
| 2007    | 30        | 0.5%    |
| 2006    | 11        | 0.18%   |
| 2023    | 9         | 0.15%   |
| 2005    | 3         | 0.05%   |
| Unknown | 3         | 0.05%   |
| 2002    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 3258      | 54.28%  |
| Desktop     | 2346      | 39.09%  |
| Convertible | 214       | 3.57%   |
| Tablet      | 63        | 1.05%   |
| Mini pc     | 53        | 0.88%   |
| All in one  | 41        | 0.68%   |
| Server      | 26        | 0.43%   |
| Stick pc    | 1         | 0.02%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 5943      | 98.82%  |
| Enabled  | 71        | 1.18%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 5957      | 99.25%  |
| Yes  | 45        | 0.75%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 1761      | 28.91%  |
| 8.01-16.0       | 1175      | 19.29%  |
| 4.01-8.0        | 1142      | 18.75%  |
| 32.01-64.0      | 990       | 16.25%  |
| 3.01-4.0        | 509       | 8.36%   |
| 64.01-256.0     | 233       | 3.83%   |
| 24.01-32.0      | 151       | 2.48%   |
| 1.01-2.0        | 74        | 1.21%   |
| 2.01-3.0        | 35        | 0.57%   |
| 0.51-1.0        | 11        | 0.18%   |
| More than 256.0 | 8         | 0.13%   |
| Unknown         | 2         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 2.01-3.0    | 1570      | 23.69%  |
| 4.01-8.0    | 1566      | 23.63%  |
| 1.01-2.0    | 1435      | 21.65%  |
| 3.01-4.0    | 1064      | 16.06%  |
| 8.01-16.0   | 558       | 8.42%   |
| 0.51-1.0    | 229       | 3.46%   |
| 16.01-24.0  | 91        | 1.37%   |
| 0.01-0.5    | 57        | 0.86%   |
| 24.01-32.0  | 35        | 0.53%   |
| 32.01-64.0  | 18        | 0.27%   |
| 64.01-256.0 | 2         | 0.03%   |
| Unknown     | 2         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 3067      | 49.63%  |
| 2      | 1687      | 27.3%   |
| 3      | 701       | 11.34%  |
| 4      | 331       | 5.36%   |
| 5      | 187       | 3.03%   |
| 6      | 82        | 1.33%   |
| 7      | 46        | 0.74%   |
| 0      | 21        | 0.34%   |
| 8      | 20        | 0.32%   |
| 9      | 16        | 0.26%   |
| 11     | 5         | 0.08%   |
| 12     | 4         | 0.06%   |
| 10     | 4         | 0.06%   |
| 13     | 3         | 0.05%   |
| 14     | 2         | 0.03%   |
| 22     | 1         | 0.02%   |
| 19     | 1         | 0.02%   |
| 17     | 1         | 0.02%   |
| 15     | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 4740      | 78.46%  |
| Yes       | 1301      | 21.54%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5036      | 83.57%  |
| No        | 990       | 16.43%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4669      | 77.31%  |
| No        | 1370      | 22.69%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4207      | 69.25%  |
| No        | 1868      | 30.75%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 1151      | 19.04%  |
| Germany     | 586       | 9.69%   |
| Russia      | 396       | 6.55%   |
| Italy       | 320       | 5.29%   |
| Brazil      | 319       | 5.28%   |
| France      | 264       | 4.37%   |
| UK          | 229       | 3.79%   |
| India       | 187       | 3.09%   |
| Poland      | 180       | 2.98%   |
| Canada      | 157       | 2.6%    |
| Spain       | 132       | 2.18%   |
| Netherlands | 121       | 2%      |
| Australia   | 106       | 1.75%   |
| China       | 94        | 1.56%   |
| Austria     | 91        | 1.51%   |
| Ukraine     | 90        | 1.49%   |
| Sweden      | 90        | 1.49%   |
| Turkey      | 73        | 1.21%   |
| Finland     | 65        | 1.08%   |
| Switzerland | 56        | 0.93%   |
| Czechia     | 55        | 0.91%   |
| Hungary     | 50        | 0.83%   |
| Mexico      | 48        | 0.79%   |
| Indonesia   | 48        | 0.79%   |
| Romania     | 47        | 0.78%   |
| Belgium     | 45        | 0.74%   |
| Argentina   | 45        | 0.74%   |
| Norway      | 41        | 0.68%   |
| Japan       | 41        | 0.68%   |
| Greece      | 41        | 0.68%   |
| Denmark     | 40        | 0.66%   |
| Portugal    | 39        | 0.65%   |
| Vietnam     | 35        | 0.58%   |
| Chile       | 34        | 0.56%   |
| New Zealand | 33        | 0.55%   |
| Iran        | 32        | 0.53%   |
| Colombia    | 30        | 0.5%    |
| Bulgaria    | 26        | 0.43%   |
| Hong Kong   | 25        | 0.41%   |
| Serbia      | 24        | 0.4%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 118       | 1.84%   |
| Paris             | 67        | 1.05%   |
| St Petersburg     | 61        | 0.95%   |
| Berlin            | 55        | 0.86%   |
| Sao Paulo         | 52        | 0.81%   |
| Vienna            | 51        | 0.8%    |
| Milan             | 50        | 0.78%   |
| Warsaw            | 47        | 0.73%   |
| Melbourne         | 42        | 0.66%   |
| Munich            | 39        | 0.61%   |
| Helsinki          | 36        | 0.56%   |
| Frankfurt am Main | 32        | 0.5%    |
| Amsterdam         | 32        | 0.5%    |
| Sydney            | 30        | 0.47%   |
| New York          | 28        | 0.44%   |
| Los Angeles       | 27        | 0.42%   |
| Valencia          | 26        | 0.41%   |
| Hamburg           | 26        | 0.41%   |
| Kyiv              | 25        | 0.39%   |
| Istanbul          | 25        | 0.39%   |
| Rome              | 24        | 0.37%   |
| Prague            | 24        | 0.37%   |
| London            | 22        | 0.34%   |
| Bengaluru         | 22        | 0.34%   |
| Athens            | 22        | 0.34%   |
| Seattle           | 21        | 0.33%   |
| Madrid            | 21        | 0.33%   |
| Budapest          | 21        | 0.33%   |
| Montreal          | 20        | 0.31%   |
| Cologne           | 20        | 0.31%   |
| Krakow            | 19        | 0.3%    |
| Singapore         | 18        | 0.28%   |
| Phoenix           | 18        | 0.28%   |
| Beijing           | 18        | 0.28%   |
| Zurich            | 17        | 0.27%   |
| Stockholm         | 17        | 0.27%   |
| Barcelona         | 17        | 0.27%   |
| Stuttgart         | 16        | 0.25%   |
| Mexico City       | 16        | 0.25%   |
| Dublin            | 16        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 2022      | 3206   | 20.25%  |
| WDC                         | 1421      | 2202   | 14.23%  |
| Seagate                     | 1209      | 1816   | 12.11%  |
| SanDisk                     | 673       | 886    | 6.74%   |
| Toshiba                     | 638       | 851    | 6.39%   |
| Kingston                    | 522       | 687    | 5.23%   |
| Crucial                     | 441       | 627    | 4.42%   |
| SK hynix                    | 302       | 364    | 3.02%   |
| Intel                       | 280       | 372    | 2.8%    |
| Unknown                     | 260       | 314    | 2.6%    |
| HGST                        | 173       | 217    | 1.73%   |
| Micron Technology           | 169       | 205    | 1.69%   |
| Hitachi                     | 164       | 203    | 1.64%   |
| A-DATA Technology           | 149       | 210    | 1.49%   |
| Phison                      | 114       | 147    | 1.14%   |
| Micron/Crucial Technology   | 72        | 85     | 0.72%   |
| China                       | 66        | 83     | 0.66%   |
| Phison Electronics          | 65        | 76     | 0.65%   |
| Silicon Motion              | 64        | 77     | 0.64%   |
| Apple                       | 64        | 77     | 0.64%   |
| KIOXIA                      | 56        | 68     | 0.56%   |
| OCZ                         | 51        | 69     | 0.51%   |
| SPCC                        | 50        | 55     | 0.5%    |
| Corsair                     | 48        | 62     | 0.48%   |
| Transcend                   | 44        | 58     | 0.44%   |
| PNY                         | 42        | 51     | 0.42%   |
| LITEON                      | 40        | 43     | 0.4%    |
| Patriot                     | 39        | 48     | 0.39%   |
| Kingston Technology Company | 32        | 34     | 0.32%   |
| ADATA Technology            | 32        | 38     | 0.32%   |
| GOODRAM                     | 28        | 33     | 0.28%   |
| XPG                         | 27        | 38     | 0.27%   |
| Realtek Semiconductor       | 25        | 31     | 0.25%   |
| Plextor                     | 22        | 31     | 0.22%   |
| JMicron Technology          | 22        | 30     | 0.22%   |
| Hewlett-Packard             | 22        | 23     | 0.22%   |
| Lenovo                      | 20        | 24     | 0.2%    |
| Intenso                     | 19        | 20     | 0.19%   |
| Team                        | 18        | 26     | 0.18%   |
| Lexar                       | 18        | 24     | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 168       | 1.48%   |
| Samsung SSD 850 EVO 500GB                          | 114       | 1%      |
| Samsung SSD 860 EVO 500GB                          | 111       | 0.98%   |
| Kingston SA400S37240G 240GB SSD                    | 100       | 0.88%   |
| Seagate ST1000LM035-1RK172 970GB                   | 94        | 0.83%   |
| Samsung SSD 850 EVO 250GB                          | 82        | 0.72%   |
| Samsung NVMe SSD Drive 512GB                       | 82        | 0.72%   |
| Samsung SSD 860 EVO 1TB                            | 81        | 0.71%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 78        | 0.69%   |
| Samsung SSD 970 EVO Plus 1TB                       | 76        | 0.67%   |
| Seagate ST2000DM008-2FR102 2TB                     | 74        | 0.65%   |
| Crucial CT500MX500SSD1 500GB                       | 72        | 0.63%   |
| Crucial CT1000MX500SSD1 1TB                        | 69        | 0.61%   |
| Samsung NVMe SSD Drive 1TB                         | 67        | 0.59%   |
| Samsung SSD 970 EVO Plus 500GB                     | 65        | 0.57%   |
| Samsung NVMe SSD Drive 500GB                       | 64        | 0.56%   |
| Kingston SA400S37120G 120GB SSD                    | 61        | 0.54%   |
| Seagate ST1000DM010-2EP102 1TB                     | 58        | 0.51%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 56        | 0.49%   |
| HGST HTS721010A9E630 1TB                           | 56        | 0.49%   |
| Samsung SSD 860 EVO 250GB                          | 54        | 0.47%   |
| Toshiba MQ01ABD100 1TB                             | 53        | 0.47%   |
| Kingston SA400S37480G 480GB SSD                    | 53        | 0.47%   |
| WDC WD10EZEX-08WN4A0 1TB                           | 50        | 0.44%   |
| SanDisk NVMe SSD Drive 1TB                         | 50        | 0.44%   |
| SanDisk NVMe SSD Drive 512GB                       | 49        | 0.43%   |
| Toshiba DT01ACA100 1TB                             | 48        | 0.42%   |
| Samsung NVMe SSD Drive 256GB                       | 48        | 0.42%   |
| Seagate ST500DM002-1BD142 500GB                    | 44        | 0.39%   |
| Seagate ST2000DM006-2DM164 2TB                     | 44        | 0.39%   |
| Toshiba MQ04ABF100 1TB                             | 43        | 0.38%   |
| SK hynix NVMe SSD Drive 512GB                      | 43        | 0.38%   |
| Seagate ST4000DM004-2CV104 4TB                     | 43        | 0.38%   |
| Samsung SSD 860 QVO 1TB                            | 43        | 0.38%   |
| Kingston SV300S37A120G 120GB SSD                   | 40        | 0.35%   |
| Unknown MMC Card  64GB                             | 39        | 0.34%   |
| Unknown MMC Card  32GB                             | 39        | 0.34%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB   | 38        | 0.33%   |
| Samsung SSD 840 EVO 250GB                          | 38        | 0.33%   |
| Samsung SSD 970 EVO 500GB                          | 37        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1180      | 1769   | 35.96%  |
| WDC                 | 1086      | 1665   | 33.1%   |
| Toshiba             | 442       | 581    | 13.47%  |
| HGST                | 171       | 215    | 5.21%   |
| Hitachi             | 164       | 203    | 5%      |
| Samsung Electronics | 112       | 149    | 3.41%   |
| Unknown             | 27        | 35     | 0.82%   |
| Apple               | 25        | 25     | 0.76%   |
| JMicron Technology  | 15        | 24     | 0.46%   |
| Fujitsu             | 10        | 10     | 0.3%    |
| Maxtor              | 7         | 7      | 0.21%   |
| ASMT                | 5         | 5      | 0.15%   |
| HGST HTS            | 4         | 4      | 0.12%   |
| USB3.0              | 3         | 4      | 0.09%   |
| LaCie               | 2         | 2      | 0.06%   |
| KESU                | 2         | 2      | 0.06%   |
| Hewlett-Packard     | 2         | 2      | 0.06%   |
| Generic-            | 2         | 3      | 0.06%   |
| ASMedia             | 2         | 2      | 0.06%   |
| USB                 | 1         | 1      | 0.03%   |
| TrueNAS             | 1         | 1      | 0.03%   |
| Synology            | 1         | 1      | 0.03%   |
| StoreJet            | 1         | 1      | 0.03%   |
| SAGE                | 1         | 1      | 0.03%   |
| RSH-319             | 1         | 1      | 0.03%   |
| QNAP                | 1         | 11     | 0.03%   |
| Pioneer             | 1         | 1      | 0.03%   |
| PHD 3.0             | 1         | 1      | 0.03%   |
| NeoTech             | 1         | 1      | 0.03%   |
| Maxone              | 1         | 1      | 0.03%   |
| MaxDigital          | 1         | 1      | 0.03%   |
| MARVELL             | 1         | 1      | 0.03%   |
| LIO-ORG             | 1         | 2      | 0.03%   |
| Intenso             | 1         | 1      | 0.03%   |
| H/W                 | 1         | 1      | 0.03%   |
| Config              | 1         | 1      | 0.03%   |
| ASUSTOR             | 1         | 1      | 0.03%   |
| ASMT109x            | 1         | 1      | 0.03%   |
| ACASIS              | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 948       | 1358   | 28.22%  |
| Kingston            | 413       | 529    | 12.3%   |
| Crucial             | 400       | 568    | 11.91%  |
| SanDisk             | 334       | 456    | 9.94%   |
| WDC                 | 229       | 297    | 6.82%   |
| A-DATA Technology   | 95        | 139    | 2.83%   |
| Intel               | 79        | 92     | 2.35%   |
| China               | 66        | 83     | 1.96%   |
| Toshiba             | 54        | 90     | 1.61%   |
| OCZ                 | 51        | 69     | 1.52%   |
| SK hynix            | 48        | 56     | 1.43%   |
| Micron Technology   | 42        | 51     | 1.25%   |
| Transcend           | 41        | 55     | 1.22%   |
| SPCC                | 41        | 44     | 1.22%   |
| Patriot             | 39        | 48     | 1.16%   |
| PNY                 | 37        | 46     | 1.1%    |
| LITEON              | 35        | 37     | 1.04%   |
| Apple               | 29        | 30     | 0.86%   |
| GOODRAM             | 26        | 31     | 0.77%   |
| Corsair             | 21        | 26     | 0.63%   |
| Plextor             | 19        | 20     | 0.57%   |
| Intenso             | 18        | 19     | 0.54%   |
| LITEONIT            | 16        | 16     | 0.48%   |
| Lexar               | 16        | 21     | 0.48%   |
| KingSpec            | 15        | 16     | 0.45%   |
| Team                | 12        | 13     | 0.36%   |
| Hewlett-Packard     | 11        | 11     | 0.33%   |
| TO Exter            | 9         | 13     | 0.27%   |
| Mushkin             | 9         | 14     | 0.27%   |
| ASMT                | 9         | 10     | 0.27%   |
| Gigabyte Technology | 8         | 8      | 0.24%   |
| Unknown             | 8         | 9      | 0.24%   |
| Seagate             | 7         | 7      | 0.21%   |
| Netac               | 7         | 7      | 0.21%   |
| FORESEE             | 6         | 8      | 0.18%   |
| External            | 6         | 7      | 0.18%   |
| KingDian            | 5         | 6      | 0.15%   |
| AMD                 | 5         | 6      | 0.15%   |
| Unknown             | 4         | 4      | 0.12%   |
| HS-SSD-C100         | 4         | 4      | 0.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 3023      | 4459   | 34.25%  |
| SSD     | 2800      | 4499   | 31.72%  |
| HDD     | 2694      | 4738   | 30.52%  |
| MMC     | 220       | 264    | 2.49%   |
| Unknown | 90        | 109    | 1.02%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 4033      | 8938   | 53.2%   |
| NVMe | 3014      | 4436   | 39.76%  |
| SAS  | 314       | 431    | 4.14%   |
| MMC  | 220       | 264    | 2.9%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2877      | 4618   | 48.68%  |
| 0.51-1.0   | 1873      | 2730   | 31.69%  |
| 1.01-2.0   | 620       | 943    | 10.49%  |
| 3.01-4.0   | 228       | 383    | 3.86%   |
| 4.01-10.0  | 150       | 294    | 2.54%   |
| 2.01-3.0   | 135       | 211    | 2.28%   |
| 10.01-20.0 | 27        | 58     | 0.46%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 1352      | 21.57%  |
| 101-250        | 1335      | 21.3%   |
| 501-1000       | 1165      | 18.58%  |
| 1001-2000      | 858       | 13.69%  |
| More than 3000 | 626       | 9.99%   |
| 2001-3000      | 356       | 5.68%   |
| 51-100         | 233       | 3.72%   |
| Unknown        | 163       | 2.6%    |
| 21-50          | 96        | 1.53%   |
| 1-20           | 85        | 1.36%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1202      | 18.43%  |
| 101-250        | 1139      | 17.46%  |
| 21-50          | 919       | 14.09%  |
| 251-500        | 821       | 12.59%  |
| 51-100         | 784       | 12.02%  |
| 501-1000       | 691       | 10.59%  |
| 1001-2000      | 407       | 6.24%   |
| More than 3000 | 234       | 3.59%   |
| Unknown        | 163       | 2.5%    |
| 2001-3000      | 161       | 2.47%   |
| 0              | 1         | 0.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                                         | Computers | Drives | Percent |
|---------------------------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                               | 13        | 15     | 1.83%   |
| Seagate ST1000LM035-1RK172 970GB                              | 12        | 12     | 1.69%   |
| HGST HTS721010A9E630 1TB                                      | 10        | 10     | 1.41%   |
| HGST HTS541010A9E680 1TB                                      | 8         | 8      | 1.13%   |
| Seagate ST500LT012-1DG142 500GB                               | 7         | 8      | 0.99%   |
| Kingston SV300S37A120G 120GB SSD                              | 7         | 7      | 0.99%   |
| WDC WD20EZRZ-00Z5HB0 2TB                                      | 6         | 6      | 0.85%   |
| Seagate ST9500325AS 500GB                                     | 6         | 6      | 0.85%   |
| Seagate ST2000DM008-2FR102 2TB                                | 6         | 9      | 0.85%   |
| Seagate ST1000LX015-1U7172 1TB                                | 6         | 8      | 0.85%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                            | 6         | 10     | 0.85%   |
| OCZ VERTEX4 256GB SSD                                         | 6         | 9      | 0.85%   |
| WDC WD5000AAKX-001CA0 500GB                                   | 5         | 6      | 0.71%   |
| WDC WD20EARS-00MVWB0 2TB                                      | 5         | 7      | 0.71%   |
| Toshiba MQ01ABD100 1TB                                        | 5         | 8      | 0.71%   |
| Seagate ST500LM021-1KJ152 500GB                               | 5         | 8      | 0.71%   |
| Seagate ST31000528AS 1TB                                      | 5         | 5      | 0.71%   |
| Seagate ST2000DM006-2DM164 2TB                                | 5         | 6      | 0.71%   |
| Seagate ST1000LM014-SSHD-8GB                                  | 5         | 5      | 0.71%   |
| Seagate ST1000DM003-9YN162 1TB                                | 5         | 5      | 0.71%   |
| Samsung Electronics SSD 960 EVO 250GB                         | 5         | 11     | 0.71%   |
| HGST HTS725050A7E630 500GB                                    | 5         | 5      | 0.71%   |
| HGST HTS545050A7E680 500GB                                    | 5         | 6      | 0.71%   |
| WDC WD20EARX-00PASB0 2TB                                      | 4         | 4      | 0.56%   |
| WDC WD10EZEX-08WN4A0 1TB                                      | 4         | 4      | 0.56%   |
| SK hynix HFS128G39TND-N210A 128GB SSD                         | 4         | 4      | 0.56%   |
| Seagate ST9250315AS 250GB                                     | 4         | 4      | 0.56%   |
| Seagate ST3320620AS 320GB                                     | 4         | 4      | 0.56%   |
| Seagate ST2000LM007-1R8174 2TB                                | 4         | 4      | 0.56%   |
| Seagate ST2000DM001-1ER164 2TB                                | 4         | 4      | 0.56%   |
| Seagate ST1000DM003-1ER162 1TB                                | 4         | 4      | 0.56%   |
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 1TB | 4         | 5      | 0.56%   |
| Samsung Electronics HD103SJ 1TB                               | 4         | 6      | 0.56%   |
| LITEON CV8-8E128-HP 128GB SSD                                 | 4         | 4      | 0.56%   |
| Crucial CT525MX300SSD1 528GB                                  | 4         | 5      | 0.56%   |
| WDC WD5000AAKX-00ERMA0 500GB                                  | 3         | 3      | 0.42%   |
| WDC WD40EFRX-68WT0N0 4TB                                      | 3         | 9      | 0.42%   |
| WDC WD40EFRX-68N32N0 4TB                                      | 3         | 3      | 0.42%   |
| WDC WD30EFRX-68EUZN0 3TB                                      | 3         | 3      | 0.42%   |
| WDC WD10JPVX-22JC3T0 1TB                                      | 3         | 3      | 0.42%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 188       | 233    | 27.77%  |
| WDC                   | 149       | 201    | 22.01%  |
| Samsung Electronics   | 58        | 79     | 8.57%   |
| Toshiba               | 49        | 61     | 7.24%   |
| Hitachi               | 43        | 46     | 6.35%   |
| HGST                  | 34        | 35     | 5.02%   |
| Kingston              | 22        | 26     | 3.25%   |
| SanDisk               | 18        | 20     | 2.66%   |
| Intel                 | 18        | 21     | 2.66%   |
| Crucial               | 18        | 21     | 2.66%   |
| SK hynix              | 12        | 13     | 1.77%   |
| OCZ                   | 10        | 17     | 1.48%   |
| A-DATA Technology     | 9         | 10     | 1.33%   |
| LITEON                | 5         | 5      | 0.74%   |
| Micron Technology     | 4         | 5      | 0.59%   |
| Transcend             | 3         | 9      | 0.44%   |
| Hewlett-Packard       | 3         | 3      | 0.44%   |
| Drevo                 | 3         | 4      | 0.44%   |
| Corsair               | 3         | 3      | 0.44%   |
| ASMT                  | 3         | 3      | 0.44%   |
| XrayDisk              | 2         | 3      | 0.3%    |
| SPCC                  | 2         | 3      | 0.3%    |
| Realtek Semiconductor | 2         | 3      | 0.3%    |
| PNY                   | 2         | 3      | 0.3%    |
| Plextor               | 2         | 9      | 0.3%    |
| Patriot               | 2         | 2      | 0.3%    |
| Maxtor                | 2         | 2      | 0.3%    |
| Apple                 | 2         | 2      | 0.3%    |
| SSSTC                 | 1         | 1      | 0.15%   |
| KingSpec              | 1         | 1      | 0.15%   |
| Kingrich              | 1         | 1      | 0.15%   |
| JMicron Technology    | 1         | 1      | 0.15%   |
| INNOVATION IT         | 1         | 1      | 0.15%   |
| GLOWAY                | 1         | 1      | 0.15%   |
| Gigabyte Technology   | 1         | 1      | 0.15%   |
| China                 | 1         | 1      | 0.15%   |
| BAITITON              | 1         | 4      | 0.15%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 188       | 233    | 39.17%  |
| WDC                 | 143       | 193    | 29.79%  |
| Toshiba             | 43        | 55     | 8.96%   |
| Hitachi             | 43        | 46     | 8.96%   |
| HGST                | 34        | 35     | 7.08%   |
| Samsung Electronics | 21        | 25     | 4.38%   |
| Maxtor              | 2         | 2      | 0.42%   |
| ASMT                | 2         | 2      | 0.42%   |
| Apple               | 2         | 2      | 0.42%   |
| JMicron Technology  | 1         | 1      | 0.21%   |
| Hewlett-Packard     | 1         | 1      | 0.21%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 444       | 595    | 69.7%   |
| SSD  | 152       | 194    | 23.86%  |
| NVMe | 41        | 65     | 6.44%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Kingston SV300S37A120G 120GB SSD                 | 2         | 2      | 16.67%  |
| WDC WD4000FYYZ-01UL1B2 4TB                       | 1         | 1      | 8.33%   |
| WDC WD2500BEVT-22ZCT0 250GB                      | 1         | 1      | 8.33%   |
| Transcend TS128GMTE850 128GB                     | 1         | 1      | 8.33%   |
| Seagate ST500DM002-1BD142 500GB                  | 1         | 1      | 8.33%   |
| Seagate ST32000644NS 2TB                         | 1         | 1      | 8.33%   |
| Samsung Electronics MZVLW128HEGR-000L2 128GB     | 1         | 2      | 8.33%   |
| Samsung Electronics MZNLN128HAHQ-000H1 128GB SSD | 1         | 1      | 8.33%   |
| Samsung Electronics MZ7PC128HAFU-000H1 128GB SSD | 1         | 1      | 8.33%   |
| Samsung Electronics HM251JI 250GB                | 1         | 1      | 8.33%   |
| Phison ESO128GTLC9-E8C-2 128GB                   | 1         | 1      | 8.33%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 5      | 33.33%  |
| WDC                 | 2         | 2      | 16.67%  |
| Seagate             | 2         | 2      | 16.67%  |
| Kingston            | 2         | 2      | 16.67%  |
| Transcend           | 1         | 1      | 8.33%   |
| Phison              | 1         | 1      | 8.33%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 3184      | 7060   | 46.8%   |
| Detected | 2996      | 6141   | 44.03%  |
| Malfunc  | 611       | 854    | 8.98%   |
| Failed   | 12        | 13     | 0.18%   |
| Limited  | 1         | 1      | 0.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3341      | 39.39%  |
| AMD                              | 1637      | 19.3%   |
| Samsung Electronics              | 1220      | 14.39%  |
| SanDisk                          | 495       | 5.84%   |
| SK hynix                         | 251       | 2.96%   |
| Phison Electronics               | 225       | 2.65%   |
| ASMedia Technology               | 174       | 2.05%   |
| Kingston Technology Company      | 147       | 1.73%   |
| Toshiba America Info Systems     | 142       | 1.67%   |
| Micron Technology                | 133       | 1.57%   |
| Micron/Crucial Technology        | 109       | 1.29%   |
| ADATA Technology                 | 96        | 1.13%   |
| Silicon Motion                   | 85        | 1%      |
| Marvell Technology Group         | 67        | 0.79%   |
| KIOXIA                           | 59        | 0.7%    |
| JMicron Technology               | 40        | 0.47%   |
| Realtek Semiconductor            | 36        | 0.42%   |
| Union Memory (Shenzhen)          | 23        | 0.27%   |
| Broadcom / LSI                   | 19        | 0.22%   |
| Lite-On Technology               | 18        | 0.21%   |
| Lenovo                           | 18        | 0.21%   |
| Nvidia                           | 16        | 0.19%   |
| Solid State Storage Technology   | 14        | 0.17%   |
| Seagate Technology               | 14        | 0.17%   |
| Apple                            | 14        | 0.17%   |
| LSI Logic / Symbios Logic        | 11        | 0.13%   |
| MAXIO Technology (Hangzhou)      | 10        | 0.12%   |
| Adaptec                          | 10        | 0.12%   |
| Yangtze Memory Technologies      | 9         | 0.11%   |
| VIA Technologies                 | 7         | 0.08%   |
| Silicon Image                    | 7         | 0.08%   |
| Shenzhen Longsys Electronics     | 6         | 0.07%   |
| Hewlett-Packard                  | 6         | 0.07%   |
| Silicon Integrated Systems [SiS] | 4         | 0.05%   |
| OCZ Technology Group             | 4         | 0.05%   |
| INNOGRIT                         | 3         | 0.04%   |
| Biwin Storage Technology         | 3         | 0.04%   |
| Netac Technology                 | 2         | 0.02%   |
| Integrated Technology Express    | 2         | 0.02%   |
| Transcend                        | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 1241      | 13.06%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 728       | 7.66%   |
| AMD 400 Series Chipset SATA Controller                                         | 391       | 4.12%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 325       | 3.42%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 212       | 2.23%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 203       | 2.14%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 193       | 2.03%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 181       | 1.91%   |
| Samsung NVMe SSD Controller 980                                                | 174       | 1.83%   |
| AMD 500 Series Chipset SATA Controller                                         | 172       | 1.81%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 166       | 1.75%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 163       | 1.72%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 156       | 1.64%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 148       | 1.56%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 141       | 1.48%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 134       | 1.41%   |
| Micron NVMe Storage Controller                                                 | 130       | 1.37%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 125       | 1.32%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 120       | 1.26%   |
| Phison E12 NVMe Controller                                                     | 118       | 1.24%   |
| Intel Volume Management Device NVMe RAID Controller                            | 117       | 1.23%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 114       | 1.2%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 108       | 1.14%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 108       | 1.14%   |
| Intel SSD 660P Series                                                          | 100       | 1.05%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 98        | 1.03%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 98        | 1.03%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 98        | 1.03%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 81        | 0.85%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 75        | 0.79%   |
| AMD 300 Series Chipset SATA Controller                                         | 72        | 0.76%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 72        | 0.76%   |
| Intel SATA Controller [RAID mode]                                              | 71        | 0.75%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 67        | 0.71%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 64        | 0.67%   |
| AMD X370 Series Chipset SATA Controller                                        | 62        | 0.65%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 60        | 0.63%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 60        | 0.63%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 59        | 0.62%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 58        | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 4388      | 53.49%  |
| NVMe | 3029      | 36.92%  |
| RAID | 450       | 5.49%   |
| IDE  | 306       | 3.73%   |
| SAS  | 23        | 0.28%   |
| SCSI | 8         | 0.1%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 4001      | 66.66%  |
| AMD    | 2001      | 33.34%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor             | 111       | 1.84%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 106       | 1.76%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 97        | 1.61%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 84        | 1.4%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 78        | 1.3%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 77        | 1.28%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 76        | 1.26%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 72        | 1.2%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 71        | 1.18%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 68        | 1.13%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 67        | 1.11%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 66        | 1.1%    |
| AMD Ryzen 7 2700X Eight-Core Processor        | 63        | 1.05%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 51        | 0.85%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 51        | 0.85%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 50        | 0.83%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 50        | 0.83%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 49        | 0.81%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 48        | 0.8%    |
| AMD Ryzen 5 5600X 6-Core Processor            | 47        | 0.78%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 46        | 0.76%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 45        | 0.75%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 43        | 0.71%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 42        | 0.7%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 41        | 0.68%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 40        | 0.66%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 40        | 0.66%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 39        | 0.65%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 38        | 0.63%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 38        | 0.63%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 38        | 0.63%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 37        | 0.61%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 37        | 0.61%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 36        | 0.6%    |
| AMD Ryzen 5 2600X Six-Core Processor          | 36        | 0.6%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 33        | 0.55%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 33        | 0.55%   |
| AMD Ryzen 7 3800X 8-Core Processor            | 33        | 0.55%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 32        | 0.53%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 31        | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 1377      | 22.92%  |
| Intel Core i5           | 1277      | 21.25%  |
| AMD Ryzen 5             | 658       | 10.95%  |
| AMD Ryzen 7             | 603       | 10.03%  |
| Other                   | 400       | 6.66%   |
| Intel Core i3           | 283       | 4.71%   |
| AMD Ryzen 9             | 220       | 3.66%   |
| Intel Celeron           | 152       | 2.53%   |
| Intel Xeon              | 117       | 1.95%   |
| Intel Core 2 Duo        | 100       | 1.66%   |
| AMD Ryzen 3             | 93        | 1.55%   |
| Intel Pentium           | 87        | 1.45%   |
| AMD FX                  | 84        | 1.4%    |
| Intel Core i9           | 65        | 1.08%   |
| AMD Ryzen 7 PRO         | 65        | 1.08%   |
| Intel Atom              | 51        | 0.85%   |
| AMD A8                  | 32        | 0.53%   |
| AMD Ryzen Threadripper  | 29        | 0.48%   |
| Intel Core 2 Quad       | 26        | 0.43%   |
| AMD Ryzen 5 PRO         | 25        | 0.42%   |
| AMD A6                  | 24        | 0.4%    |
| AMD A10                 | 24        | 0.4%    |
| Intel Pentium Dual-Core | 17        | 0.28%   |
| AMD Athlon              | 17        | 0.28%   |
| AMD A4                  | 16        | 0.27%   |
| Intel Pentium Silver    | 14        | 0.23%   |
| AMD Phenom II X4        | 13        | 0.22%   |
| Intel Genuine           | 10        | 0.17%   |
| Intel Core m3           | 9         | 0.15%   |
| AMD E2                  | 8         | 0.13%   |
| AMD Athlon II X4        | 8         | 0.13%   |
| Intel Core 2            | 7         | 0.12%   |
| AMD E                   | 7         | 0.12%   |
| AMD Athlon II X2        | 7         | 0.12%   |
| Intel Pentium Dual      | 6         | 0.1%    |
| AMD Phenom II X6        | 6         | 0.1%    |
| AMD E1                  | 6         | 0.1%    |
| AMD Athlon 64 X2        | 6         | 0.1%    |
| Intel Core m5           | 5         | 0.08%   |
| AMD Athlon X4           | 4         | 0.07%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 2277      | 37.86%  |
| 2       | 1533      | 25.49%  |
| 6       | 941       | 15.65%  |
| 8       | 854       | 14.2%   |
| 12      | 162       | 2.69%   |
| 16      | 90        | 1.5%    |
| 10      | 36        | 0.6%    |
| 1       | 35        | 0.58%   |
| 14      | 32        | 0.53%   |
| 3       | 25        | 0.42%   |
| 24      | 10        | 0.17%   |
| 32      | 7         | 0.12%   |
| 64      | 4         | 0.07%   |
| 18      | 2         | 0.03%   |
| Unknown | 2         | 0.03%   |
| 40      | 1         | 0.02%   |
| 28      | 1         | 0.02%   |
| 20      | 1         | 0.02%   |
| 5       | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 5966      | 99.4%   |
| 2      | 36        | 0.6%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 4773      | 79.42%  |
| 1       | 1235      | 20.55%  |
| Unknown | 2         | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 5894      | 98.04%  |
| Unknown        | 114       | 1.9%    |
| 32-bit         | 4         | 0.07%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1971      | 31.53%  |
| 0x306a9    | 204       | 3.26%   |
| 0x08701021 | 202       | 3.23%   |
| 0x906ea    | 200       | 3.2%    |
| 0x306c3    | 199       | 3.18%   |
| 0x206a7    | 178       | 2.85%   |
| 0x906e9    | 172       | 2.75%   |
| 0x806ea    | 167       | 2.67%   |
| 0x0800820d | 146       | 2.34%   |
| 0x806ec    | 136       | 2.18%   |
| 0x806c1    | 135       | 2.16%   |
| 0x506e3    | 121       | 1.94%   |
| 0x406e3    | 110       | 1.76%   |
| 0x806e9    | 103       | 1.65%   |
| 0x0a50000c | 98        | 1.57%   |
| 0x08701013 | 96        | 1.54%   |
| 0x306d4    | 90        | 1.44%   |
| 0x40651    | 86        | 1.38%   |
| 0x08108102 | 84        | 1.34%   |
| 0x08600106 | 77        | 1.23%   |
| 0x08108109 | 72        | 1.15%   |
| 0x1067a    | 68        | 1.09%   |
| 0xa0652    | 61        | 0.98%   |
| 0x08001138 | 58        | 0.93%   |
| 0x0a201016 | 52        | 0.83%   |
| 0x20655    | 50        | 0.8%    |
| 0x0a201009 | 50        | 0.8%    |
| 0x08600104 | 50        | 0.8%    |
| 0x806eb    | 46        | 0.74%   |
| 0x08600103 | 42        | 0.67%   |
| 0x08608103 | 38        | 0.61%   |
| 0x706e5    | 37        | 0.59%   |
| 0x906ed    | 36        | 0.58%   |
| 0x0810100b | 35        | 0.56%   |
| 0x906a3    | 28        | 0.45%   |
| 0x406c4    | 27        | 0.43%   |
| 0x08001137 | 27        | 0.43%   |
| 0x06000852 | 27        | 0.43%   |
| 0x506c9    | 24        | 0.38%   |
| 0x08101016 | 24        | 0.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 1329      | 22.08%  |
| Zen 2            | 605       | 10.05%  |
| Haswell          | 447       | 7.43%   |
| Zen+             | 397       | 6.6%    |
| Skylake          | 366       | 6.08%   |
| Zen 3            | 350       | 5.82%   |
| IvyBridge        | 305       | 5.07%   |
| SandyBridge      | 273       | 4.54%   |
| Unknown          | 234       | 3.89%   |
| Zen              | 218       | 3.62%   |
| TigerLake        | 209       | 3.47%   |
| CometLake        | 162       | 2.69%   |
| Broadwell        | 144       | 2.39%   |
| Penryn           | 138       | 2.29%   |
| Piledriver       | 103       | 1.71%   |
| Westmere         | 100       | 1.66%   |
| Silvermont       | 98        | 1.63%   |
| IceLake          | 94        | 1.56%   |
| Alderlake Hybrid | 68        | 1.13%   |
| Goldmont plus    | 50        | 0.83%   |
| K10              | 47        | 0.78%   |
| Excavator        | 40        | 0.66%   |
| Nehalem          | 39        | 0.65%   |
| Core             | 38        | 0.63%   |
| Goldmont         | 32        | 0.53%   |
| K10 Llano        | 18        | 0.3%    |
| Bonnell          | 18        | 0.3%    |
| Bobcat           | 18        | 0.3%    |
| Steamroller      | 17        | 0.28%   |
| Puma             | 13        | 0.22%   |
| Jaguar           | 13        | 0.22%   |
| K8 Hammer        | 10        | 0.17%   |
| Tremont          | 8         | 0.13%   |
| NetBurst         | 7         | 0.12%   |
| Bulldozer        | 5         | 0.08%   |
| P6               | 2         | 0.03%   |
| K8 & K10 hybrid  | 2         | 0.03%   |
| Gracemont        | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3095      | 41.68%  |
| Nvidia                           | 2327      | 31.34%  |
| AMD                              | 1969      | 26.52%  |
| Matrox Electronics Systems       | 17        | 0.23%   |
| ASPEED Technology                | 9         | 0.12%   |
| Silicon Integrated Systems [SiS] | 4         | 0.05%   |
| ATI Technologies                 | 3         | 0.04%   |
| VIA Technologies                 | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 284       | 3.74%   |
| Intel UHD Graphics 620                                                                   | 238       | 3.14%   |
| AMD Renoir                                                                               | 211       | 2.78%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 205       | 2.7%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 188       | 2.48%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 187       | 2.46%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 184       | 2.42%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 178       | 2.34%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 162       | 2.13%   |
| Intel HD Graphics 630                                                                    | 148       | 1.95%   |
| Intel HD Graphics 620                                                                    | 141       | 1.86%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 140       | 1.84%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 137       | 1.8%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 130       | 1.71%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 125       | 1.65%   |
| Intel HD Graphics 5500                                                                   | 109       | 1.44%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 98        | 1.29%   |
| Intel HD Graphics 530                                                                    | 94        | 1.24%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 92        | 1.21%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 91        | 1.2%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 86        | 1.13%   |
| AMD Lucienne                                                                             | 82        | 1.08%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 80        | 1.05%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 76        | 1%      |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 76        | 1%      |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 75        | 0.99%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 72        | 0.95%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 68        | 0.9%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 59        | 0.78%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 59        | 0.78%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 58        | 0.76%   |
| Intel Core Processor Integrated Graphics Controller                                      | 56        | 0.74%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 56        | 0.74%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 55        | 0.72%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 52        | 0.69%   |
| Nvidia GP108M [GeForce MX150]                                                            | 49        | 0.65%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 49        | 0.65%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 46        | 0.61%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 45        | 0.59%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                            | 45        | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1901      | 31.39%  |
| 1 x AMD                  | 1522      | 25.13%  |
| 1 x Nvidia               | 1137      | 18.77%  |
| Intel + Nvidia           | 963       | 15.9%   |
| AMD + Nvidia             | 197       | 3.25%   |
| Intel + AMD              | 157       | 2.59%   |
| 2 x AMD                  | 98        | 1.62%   |
| 2 x Nvidia               | 30        | 0.5%    |
| 1 x Matrox               | 13        | 0.21%   |
| 2 x Intel                | 8         | 0.13%   |
| Other                    | 6         | 0.1%    |
| 1 x ASPEED               | 5         | 0.08%   |
| 1 x SiS                  | 4         | 0.07%   |
| AMD + ASPEED             | 3         | 0.05%   |
| Nvidia + Matrox          | 2         | 0.03%   |
| Intel + 2 x Nvidia       | 2         | 0.03%   |
| Intel + AMD + 1 x Nvidia | 2         | 0.03%   |
| AMD + Matrox             | 2         | 0.03%   |
| 3 x Nvidia               | 1         | 0.02%   |
| 2 x AMD + 1 x Nvidia     | 1         | 0.02%   |
| 1 x VIA                  | 1         | 0.02%   |
| Nvidia + ASPEED          | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 4376      | 72.16%  |
| Proprietary | 1634      | 26.95%  |
| Unknown     | 54        | 0.89%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 3340      | 53.98%  |
| 7.01-8.0   | 613       | 9.91%   |
| 1.01-2.0   | 569       | 9.2%    |
| 3.01-4.0   | 484       | 7.82%   |
| 0.01-0.5   | 449       | 7.26%   |
| 0.51-1.0   | 255       | 4.12%   |
| 5.01-6.0   | 237       | 3.83%   |
| 8.01-16.0  | 173       | 2.8%    |
| 2.01-3.0   | 53        | 0.86%   |
| 16.01-24.0 | 11        | 0.18%   |
| 4.01-5.0   | 3         | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 799       | 10.97%  |
| Samsung Electronics     | 798       | 10.96%  |
| BOE                     | 643       | 8.83%   |
| LG Display              | 568       | 7.8%    |
| Chimei Innolux          | 563       | 7.73%   |
| Dell                    | 512       | 7.03%   |
| Goldstar                | 441       | 6.06%   |
| Acer                    | 292       | 4.01%   |
| AOC                     | 241       | 3.31%   |
| BenQ                    | 225       | 3.09%   |
| Hewlett-Packard         | 209       | 2.87%   |
| Sharp                   | 202       | 2.77%   |
| Ancor Communications    | 187       | 2.57%   |
| Philips                 | 138       | 1.9%    |
| Lenovo                  | 124       | 1.7%    |
| ViewSonic               | 100       | 1.37%   |
| PANDA                   | 99        | 1.36%   |
| Apple                   | 87        | 1.19%   |
| Iiyama                  | 82        | 1.13%   |
| ASUSTek Computer        | 77        | 1.06%   |
| LG Electronics          | 55        | 0.76%   |
| InfoVision              | 55        | 0.76%   |
| Sony                    | 41        | 0.56%   |
| MSI                     | 39        | 0.54%   |
| Unknown                 | 36        | 0.49%   |
| NEC Computers           | 36        | 0.49%   |
| CSO                     | 34        | 0.47%   |
| Chi Mei Optoelectronics | 29        | 0.4%    |
| Eizo                    | 28        | 0.38%   |
| Gigabyte Technology     | 25        | 0.34%   |
| Fujitsu Siemens         | 19        | 0.26%   |
| Panasonic               | 18        | 0.25%   |
| Sceptre Tech            | 17        | 0.23%   |
| Toshiba                 | 16        | 0.22%   |
| Vizio                   | 14        | 0.19%   |
| HannStar                | 14        | 0.19%   |
| Pixio                   | 13        | 0.18%   |
| Unknown                 | 12        | 0.16%   |
| Valve                   | 11        | 0.15%   |
| TMX                     | 11        | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 47        | 0.62%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 41        | 0.54%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 34        | 0.45%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 33        | 0.43%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch       | 29        | 0.38%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 27        | 0.35%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 26        | 0.34%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 25        | 0.33%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch              | 25        | 0.33%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch            | 23        | 0.3%    |
| AOC 24P2W1DG5 AOC2402 1920x1080 527x296mm 23.8-inch                  | 23        | 0.3%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 22        | 0.29%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 22        | 0.29%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 22        | 0.29%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch       | 19        | 0.25%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                | 18        | 0.24%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 17        | 0.22%   |
| Ancor Communications VG248 ACI24A4 1920x1080 531x299mm 24.0-inch     | 17        | 0.22%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 16        | 0.21%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 16        | 0.21%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch        | 16        | 0.21%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 15        | 0.2%    |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 15        | 0.2%    |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch         | 15        | 0.2%    |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                | 15        | 0.2%    |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 15        | 0.2%    |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch             | 14        | 0.18%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 14        | 0.18%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 14        | 0.18%   |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                     | 14        | 0.18%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch    | 13        | 0.17%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 13        | 0.17%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 13        | 0.17%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 13        | 0.17%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 381x214mm 17.2-inch     | 13        | 0.17%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 12        | 0.16%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch     | 12        | 0.16%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 12        | 0.16%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch       | 12        | 0.16%   |
| Unknown                                                              | 12        | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 3338      | 48.72%  |
| 1366x768 (WXGA)    | 796       | 11.62%  |
| 3840x2160 (4K)     | 539       | 7.87%   |
| 2560x1440 (QHD)    | 520       | 7.59%   |
| 1920x1200 (WUXGA)  | 198       | 2.89%   |
| 1600x900 (HD+)     | 188       | 2.74%   |
| 1680x1050 (WSXGA+) | 137       | 2%      |
| 3440x1440          | 126       | 1.84%   |
| 1280x1024 (SXGA)   | 120       | 1.75%   |
| Unknown            | 114       | 1.66%   |
| 1440x900 (WXGA+)   | 94        | 1.37%   |
| 2560x1080          | 85        | 1.24%   |
| 2560x1600          | 56        | 0.82%   |
| 1280x800 (WXGA)    | 55        | 0.8%    |
| 3840x1080          | 50        | 0.73%   |
| 1360x768           | 42        | 0.61%   |
| 2880x1800          | 41        | 0.6%    |
| 3840x2400          | 33        | 0.48%   |
| 3840x1600          | 21        | 0.31%   |
| 2256x1504          | 21        | 0.31%   |
| 3200x1800 (QHD+)   | 20        | 0.29%   |
| 2160x1440          | 20        | 0.29%   |
| 1920x540           | 17        | 0.25%   |
| 2736x1824          | 15        | 0.22%   |
| 3000x2000          | 12        | 0.18%   |
| 1920x1280          | 10        | 0.15%   |
| 7680x2160          | 9         | 0.13%   |
| 3072x1920          | 9         | 0.13%   |
| 5120x1440          | 8         | 0.12%   |
| 4480x1440          | 8         | 0.12%   |
| 1600x1200          | 8         | 0.12%   |
| 5760x1080          | 7         | 0.1%    |
| 2240x1400          | 7         | 0.1%    |
| 1024x768 (XGA)     | 7         | 0.1%    |
| 1280x720 (HD)      | 6         | 0.09%   |
| 1024x600           | 6         | 0.09%   |
| 3200x2000          | 5         | 0.07%   |
| 800x1280           | 4         | 0.06%   |
| 6400x2160          | 4         | 0.06%   |
| 6400x1440          | 4         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1614      | 22.31%  |
| 13      | 736       | 10.17%  |
| 27      | 711       | 9.83%   |
| 24      | 689       | 9.52%   |
| 14      | 609       | 8.42%   |
| 23      | 501       | 6.92%   |
| 21      | 402       | 5.56%   |
| Unknown | 361       | 4.99%   |
| 17      | 247       | 3.41%   |
| 34      | 172       | 2.38%   |
| 31      | 152       | 2.1%    |
| 19      | 143       | 1.98%   |
| 12      | 127       | 1.76%   |
| 22      | 97        | 1.34%   |
| 18      | 97        | 1.34%   |
| 20      | 68        | 0.94%   |
| 16      | 57        | 0.79%   |
| 11      | 54        | 0.75%   |
| 84      | 40        | 0.55%   |
| 72      | 40        | 0.55%   |
| 25      | 36        | 0.5%    |
| 40      | 26        | 0.36%   |
| 48      | 22        | 0.3%    |
| 32      | 22        | 0.3%    |
| 54      | 21        | 0.29%   |
| 28      | 20        | 0.28%   |
| 10      | 19        | 0.26%   |
| 37      | 18        | 0.25%   |
| 26      | 18        | 0.25%   |
| 29      | 17        | 0.23%   |
| 46      | 11        | 0.15%   |
| 35      | 10        | 0.14%   |
| 33      | 8         | 0.11%   |
| 49      | 7         | 0.1%    |
| 65      | 6         | 0.08%   |
| 42      | 6         | 0.08%   |
| 74      | 5         | 0.07%   |
| 43      | 5         | 0.07%   |
| 39      | 5         | 0.07%   |
| 38      | 4         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 2602      | 37.17%  |
| 501-600        | 1696      | 24.23%  |
| 401-500        | 712       | 10.17%  |
| 201-300        | 608       | 8.69%   |
| Unknown        | 361       | 5.16%   |
| 351-400        | 307       | 4.39%   |
| 601-700        | 259       | 3.7%    |
| 701-800        | 205       | 2.93%   |
| 1501-2000      | 86        | 1.23%   |
| 1001-1500      | 84        | 1.2%    |
| 801-900        | 63        | 0.9%    |
| 901-1000       | 13        | 0.19%   |
| 101-200        | 2         | 0.03%   |
| More than 2000 | 1         | 0.01%   |
| 1-100          | 1         | 0.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 4790      | 75.95%  |
| 16/10   | 689       | 10.92%  |
| Unknown | 310       | 4.92%   |
| 21/9    | 214       | 3.39%   |
| 5/4     | 122       | 1.93%   |
| 3/2     | 107       | 1.7%    |
| 4/3     | 31        | 0.49%   |
| 32/9    | 30        | 0.48%   |
| 2.65    | 4         | 0.06%   |
| 0.62    | 3         | 0.05%   |
| 1.96    | 2         | 0.03%   |
| 3.40    | 1         | 0.02%   |
| 2.00    | 1         | 0.02%   |
| 1.03    | 1         | 0.02%   |
| 0.67    | 1         | 0.02%   |
| 0.57    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1610      | 22.61%  |
| 201-250        | 1326      | 18.62%  |
| 81-90          | 1005      | 14.11%  |
| 301-350        | 730       | 10.25%  |
| 351-500        | 380       | 5.34%   |
| Unknown        | 361       | 5.07%   |
| 71-80          | 342       | 4.8%    |
| 151-200        | 290       | 4.07%   |
| 251-300        | 253       | 3.55%   |
| 121-130        | 170       | 2.39%   |
| 141-150        | 134       | 1.88%   |
| More than 1000 | 133       | 1.87%   |
| 61-70          | 114       | 1.6%    |
| 501-1000       | 105       | 1.47%   |
| 51-60          | 57        | 0.8%    |
| 111-120        | 47        | 0.66%   |
| 131-140        | 23        | 0.32%   |
| 91-100         | 22        | 0.31%   |
| 41-50          | 17        | 0.24%   |
| 1-40           | 2         | 0.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 2077      | 30.25%  |
| 51-100        | 2045      | 29.78%  |
| 101-120       | 1466      | 21.35%  |
| 161-240       | 569       | 8.29%   |
| Unknown       | 361       | 5.26%   |
| More than 240 | 242       | 3.52%   |
| 1-50          | 106       | 1.54%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 4466      | 72.62%  |
| 2     | 1328      | 21.59%  |
| 3     | 220       | 3.58%   |
| 0     | 116       | 1.89%   |
| 4     | 17        | 0.28%   |
| 5     | 2         | 0.03%   |
| 6     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 3399      | 37.95%  |
| Realtek Semiconductor             | 3238      | 36.15%  |
| Qualcomm Atheros                  | 848       | 9.47%   |
| Broadcom                          | 318       | 3.55%   |
| MediaTek                          | 144       | 1.61%   |
| TP-Link                           | 94        | 1.05%   |
| Ralink Technology                 | 75        | 0.84%   |
| Microsoft                         | 63        | 0.7%    |
| Broadcom Limited                  | 61        | 0.68%   |
| Marvell Technology Group          | 54        | 0.6%    |
| ASIX Electronics                  | 47        | 0.52%   |
| Ralink                            | 45        | 0.5%    |
| Lenovo                            | 44        | 0.49%   |
| Samsung Electronics               | 32        | 0.36%   |
| Qualcomm                          | 31        | 0.35%   |
| Sierra Wireless                   | 30        | 0.33%   |
| Xiaomi                            | 27        | 0.3%    |
| DisplayLink                       | 27        | 0.3%    |
| Ericsson Business Mobile Networks | 25        | 0.28%   |
| Aquantia                          | 25        | 0.28%   |
| D-Link                            | 21        | 0.23%   |
| NetGear                           | 19        | 0.21%   |
| Qualcomm Atheros Communications   | 18        | 0.2%    |
| Dell                              | 17        | 0.19%   |
| Hewlett-Packard                   | 15        | 0.17%   |
| Google                            | 15        | 0.17%   |
| Apple                             | 15        | 0.17%   |
| Nvidia                            | 13        | 0.15%   |
| Huawei Technologies               | 13        | 0.15%   |
| Microchip Technology              | 11        | 0.12%   |
| Mellanox Technologies             | 11        | 0.12%   |
| ASUSTek Computer                  | 9         | 0.1%    |
| Linksys                           | 8         | 0.09%   |
| Cypress Semiconductor             | 8         | 0.09%   |
| Fibocom                           | 7         | 0.08%   |
| D-Link System                     | 7         | 0.08%   |
| JMicron Technology                | 6         | 0.07%   |
| Edimax Technology                 | 6         | 0.07%   |
| OPPO Electronics                  | 5         | 0.06%   |
| Oculus VR                         | 5         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2307      | 21.85%  |
| Intel Wi-Fi 6 AX200                                               | 521       | 4.94%   |
| Intel I211 Gigabit Network Connection                             | 367       | 3.48%   |
| Intel Wireless 8265 / 8275                                        | 261       | 2.47%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 238       | 2.25%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 193       | 1.83%   |
| Realtek RTL8125 2.5GbE Controller                                 | 188       | 1.78%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 169       | 1.6%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 167       | 1.58%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 157       | 1.49%   |
| Intel Ethernet Connection (2) I219-V                              | 154       | 1.46%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 152       | 1.44%   |
| Intel Wi-Fi 6 AX201                                               | 151       | 1.43%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 140       | 1.33%   |
| Intel Wireless 8260                                               | 135       | 1.28%   |
| Intel Wireless 7265                                               | 134       | 1.27%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 123       | 1.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 110       | 1.04%   |
| Intel Wireless 7260                                               | 104       | 0.99%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 103       | 0.98%   |
| Intel Wireless-AC 9260                                            | 100       | 0.95%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 94        | 0.89%   |
| Intel Wireless 3165                                               | 93        | 0.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 88        | 0.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 87        | 0.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 86        | 0.81%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 84        | 0.8%    |
| Intel Ethernet Connection (7) I219-V                              | 83        | 0.79%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 81        | 0.77%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 80        | 0.76%   |
| Intel Ethernet Controller I225-V                                  | 80        | 0.76%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 79        | 0.75%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 68        | 0.64%   |
| Intel Ethernet Connection I217-LM                                 | 67        | 0.63%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 63        | 0.6%    |
| Intel Ethernet Connection (4) I219-LM                             | 61        | 0.58%   |
| Intel Ethernet Connection (4) I219-V                              | 55        | 0.52%   |
| Intel Wireless 3160                                               | 50        | 0.47%   |
| Intel Ethernet Connection (2) I218-V                              | 47        | 0.45%   |
| Intel Ethernet Connection (6) I219-V                              | 46        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2654      | 54.31%  |
| Realtek Semiconductor           | 689       | 14.1%   |
| Qualcomm Atheros                | 665       | 13.61%  |
| Broadcom                        | 243       | 4.97%   |
| MediaTek                        | 140       | 2.86%   |
| TP-Link                         | 80        | 1.64%   |
| Ralink Technology               | 75        | 1.53%   |
| Microsoft                       | 56        | 1.15%   |
| Broadcom Limited                | 47        | 0.96%   |
| Ralink                          | 45        | 0.92%   |
| Qualcomm                        | 27        | 0.55%   |
| Sierra Wireless                 | 23        | 0.47%   |
| Qualcomm Atheros Communications | 18        | 0.37%   |
| D-Link                          | 18        | 0.37%   |
| NetGear                         | 17        | 0.35%   |
| Marvell Technology Group        | 16        | 0.33%   |
| Dell                            | 10        | 0.2%    |
| ASUSTek Computer                | 9         | 0.18%   |
| Linksys                         | 8         | 0.16%   |
| Fibocom                         | 7         | 0.14%   |
| Hewlett-Packard                 | 6         | 0.12%   |
| Edimax Technology               | 6         | 0.12%   |
| AVM                             | 4         | 0.08%   |
| Wilocity                        | 3         | 0.06%   |
| Mercucys                        | 3         | 0.06%   |
| D-Link System                   | 3         | 0.06%   |
| Belkin Components               | 3         | 0.06%   |
| Xiaomi                          | 2         | 0.04%   |
| Tenda                           | 2         | 0.04%   |
| Micro Star International        | 2         | 0.04%   |
| IMC Networks                    | 2         | 0.04%   |
| ZyXEL Communications            | 1         | 0.02%   |
| Sagem                           | 1         | 0.02%   |
| Quectel Wireless Solutions      | 1         | 0.02%   |
| AboCom Systems                  | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 521       | 10.61%  |
| Intel Wireless 8265 / 8275                                     | 261       | 5.32%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 167       | 3.4%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 157       | 3.2%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 152       | 3.1%    |
| Intel Wi-Fi 6 AX201                                            | 151       | 3.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 140       | 2.85%   |
| Intel Wireless 8260                                            | 135       | 2.75%   |
| Intel Wireless 7265                                            | 134       | 2.73%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 123       | 2.51%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 110       | 2.24%   |
| Intel Wireless 7260                                            | 104       | 2.12%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 103       | 2.1%    |
| Intel Wireless-AC 9260                                         | 100       | 2.04%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 94        | 1.91%   |
| Intel Wireless 3165                                            | 93        | 1.89%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 88        | 1.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 87        | 1.77%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 86        | 1.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 84        | 1.71%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 81        | 1.65%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 80        | 1.63%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 79        | 1.61%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 68        | 1.39%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 63        | 1.28%   |
| Intel Wireless 3160                                            | 50        | 1.02%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 43        | 0.88%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 43        | 0.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 39        | 0.79%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 38        | 0.77%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 38        | 0.77%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 36        | 0.73%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 35        | 0.71%   |
| Microsoft Xbox 360 Wireless Adapter                            | 30        | 0.61%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 29        | 0.59%   |
| Broadcom BCM43142 802.11b/g/n                                  | 29        | 0.59%   |
| Realtek 802.11ac NIC                                           | 27        | 0.55%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 27        | 0.55%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 27        | 0.55%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 26        | 0.53%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2937      | 54.5%   |
| Intel                                  | 1693      | 31.42%  |
| Qualcomm Atheros                       | 242       | 4.49%   |
| Broadcom                               | 118       | 2.19%   |
| ASIX Electronics                       | 47        | 0.87%   |
| Lenovo                                 | 42        | 0.78%   |
| Marvell Technology Group               | 38        | 0.71%   |
| DisplayLink                            | 27        | 0.5%    |
| Xiaomi                                 | 25        | 0.46%   |
| Aquantia                               | 25        | 0.46%   |
| Samsung Electronics                    | 18        | 0.33%   |
| Apple                                  | 15        | 0.28%   |
| TP-Link                                | 14        | 0.26%   |
| Broadcom Limited                       | 14        | 0.26%   |
| Nvidia                                 | 13        | 0.24%   |
| Google                                 | 13        | 0.24%   |
| Mellanox Technologies                  | 11        | 0.2%    |
| Cypress Semiconductor                  | 8         | 0.15%   |
| Sierra Wireless                        | 7         | 0.13%   |
| Microsoft                              | 6         | 0.11%   |
| JMicron Technology                     | 6         | 0.11%   |
| Huawei Technologies                    | 6         | 0.11%   |
| OPPO Electronics                       | 5         | 0.09%   |
| Silicon Integrated Systems [SiS]       | 4         | 0.07%   |
| Qualcomm                               | 4         | 0.07%   |
| Motorola PCS                           | 4         | 0.07%   |
| MediaTek                               | 4         | 0.07%   |
| ICS Advent                             | 4         | 0.07%   |
| D-Link System                          | 4         | 0.07%   |
| QLogic                                 | 3         | 0.06%   |
| Hewlett-Packard                        | 3         | 0.06%   |
| D-Link                                 | 3         | 0.06%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.04%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.04%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.04%   |
| NetGear                                | 2         | 0.04%   |
| IBM                                    | 2         | 0.04%   |
| HMD Global                             | 2         | 0.04%   |
| VIA Technologies                       | 1         | 0.02%   |
| Standard Microsystems [SMC]            | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2307      | 41.73%  |
| Intel I211 Gigabit Network Connection                             | 367       | 6.64%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 238       | 4.31%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 193       | 3.49%   |
| Realtek RTL8125 2.5GbE Controller                                 | 188       | 3.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 169       | 3.06%   |
| Intel Ethernet Connection (2) I219-V                              | 154       | 2.79%   |
| Intel Ethernet Connection (7) I219-V                              | 83        | 1.5%    |
| Intel Ethernet Controller I225-V                                  | 80        | 1.45%   |
| Intel Ethernet Connection I217-LM                                 | 67        | 1.21%   |
| Intel Ethernet Connection (4) I219-LM                             | 61        | 1.1%    |
| Intel Ethernet Connection (4) I219-V                              | 55        | 0.99%   |
| Intel Ethernet Connection (2) I218-V                              | 47        | 0.85%   |
| Intel Ethernet Connection (6) I219-V                              | 46        | 0.83%   |
| Intel Ethernet Connection (2) I219-LM                             | 45        | 0.81%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 42        | 0.76%   |
| Intel Ethernet Connection I219-LM                                 | 40        | 0.72%   |
| Intel Ethernet Connection (3) I218-LM                             | 40        | 0.72%   |
| ASIX AX88179 Gigabit Ethernet                                     | 40        | 0.72%   |
| Intel 82579V Gigabit Network Connection                           | 39        | 0.71%   |
| Intel Ethernet Connection (7) I219-LM                             | 37        | 0.67%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 36        | 0.65%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 34        | 0.62%   |
| Intel Ethernet Connection I218-LM                                 | 34        | 0.62%   |
| Intel 82577LM Gigabit Network Connection                          | 30        | 0.54%   |
| Intel I210 Gigabit Network Connection                             | 28        | 0.51%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 26        | 0.47%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 26        | 0.47%   |
| Intel Ethernet Connection I217-V                                  | 24        | 0.43%   |
| Intel 82567LM Gigabit Network Connection                          | 24        | 0.43%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 23        | 0.42%   |
| Intel Ethernet Connection (10) I219-V                             | 23        | 0.42%   |
| Intel Ethernet Connection (6) I219-LM                             | 22        | 0.4%    |
| Intel 82574L Gigabit Network Connection                           | 21        | 0.38%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 21        | 0.38%   |
| Intel Ethernet Connection I219-V                                  | 19        | 0.34%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 18        | 0.33%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 17        | 0.31%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 16        | 0.29%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 15        | 0.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 5026      | 51.24%  |
| WiFi     | 4665      | 47.56%  |
| Modem    | 107       | 1.09%   |
| Unknown  | 11        | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 3563      | 56.29%  |
| Ethernet | 2764      | 43.67%  |
| Modem    | 3         | 0.05%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 3186      | 52.84%  |
| 1     | 2584      | 42.86%  |
| 3     | 174       | 2.89%   |
| 0     | 52        | 0.86%   |
| 4     | 19        | 0.32%   |
| 5     | 7         | 0.12%   |
| 6     | 5         | 0.08%   |
| 10    | 1         | 0.02%   |
| 8     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 5106      | 83.8%   |
| Yes  | 987       | 16.2%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2325      | 54.46%  |
| Realtek Semiconductor           | 377       | 8.83%   |
| Cambridge Silicon Radio         | 301       | 7.05%   |
| Qualcomm Atheros Communications | 259       | 6.07%   |
| Broadcom                        | 164       | 3.84%   |
| IMC Networks                    | 153       | 3.58%   |
| Lite-On Technology              | 133       | 3.12%   |
| Foxconn / Hon Hai               | 116       | 2.72%   |
| ASUSTek Computer                | 101       | 2.37%   |
| Apple                           | 89        | 2.08%   |
| Realtek                         | 42        | 0.98%   |
| Dell                            | 32        | 0.75%   |
| MediaTek                        | 30        | 0.7%    |
| Hewlett-Packard                 | 18        | 0.42%   |
| TP-Link                         | 17        | 0.4%    |
| Marvell Semiconductor           | 15        | 0.35%   |
| Toshiba                         | 13        | 0.3%    |
| HTC (High Tech Computer)        | 13        | 0.3%    |
| Ralink                          | 11        | 0.26%   |
| USI                             | 10        | 0.23%   |
| Edimax Technology               | 8         | 0.19%   |
| Foxconn International           | 6         | 0.14%   |
| Dynex                           | 5         | 0.12%   |
| Integrated System Solution      | 4         | 0.09%   |
| Opticis                         | 3         | 0.07%   |
| Micro Star International        | 3         | 0.07%   |
| Chicony Electronics             | 3         | 0.07%   |
| Askey Computer                  | 3         | 0.07%   |
| Smart Modular Technologies      | 2         | 0.05%   |
| Ralink Technology               | 2         | 0.05%   |
| Belkin Components               | 2         | 0.05%   |
| Alps Electric                   | 2         | 0.05%   |
| Syntek                          | 1         | 0.02%   |
| SINO WEALTH                     | 1         | 0.02%   |
| Roper                           | 1         | 0.02%   |
| Fujitsu                         | 1         | 0.02%   |
| Cypress Semiconductor           | 1         | 0.02%   |
| Corsair                         | 1         | 0.02%   |
| Unknown                         | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                   | 748       | 17.5%   |
| Intel AX200 Bluetooth                                                | 497       | 11.63%  |
| Intel AX201 Bluetooth                                                | 347       | 8.12%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 306       | 7.16%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 301       | 7.04%   |
| Realtek Bluetooth Radio                                              | 237       | 5.54%   |
| Qualcomm Atheros  Bluetooth Device                                   | 191       | 4.47%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 120       | 2.81%   |
| Intel AX210 Bluetooth                                                | 104       | 2.43%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 93        | 2.18%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 86        | 2.01%   |
| Intel Bluetooth Device                                               | 63        | 1.47%   |
| IMC Networks Bluetooth Radio                                         | 53        | 1.24%   |
| Lite-On Bluetooth Device                                             | 48        | 1.12%   |
| IMC Networks Wireless_Device                                         | 47        | 1.1%    |
| Intel Centrino Bluetooth Wireless Transceiver                        | 45        | 1.05%   |
| Apple Bluetooth Host Controller                                      | 45        | 1.05%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 44        | 1.03%   |
| Foxconn / Hon Hai Bluetooth Device                                   | 43        | 1.01%   |
| Foxconn / Hon Hai Wireless_Device                                    | 42        | 0.98%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 40        | 0.94%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 37        | 0.87%   |
| IMC Networks Bluetooth Device                                        | 35        | 0.82%   |
| Realtek 802.11ac WLAN Adapter                                        | 33        | 0.77%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                           | 31        | 0.73%   |
| MediaTek Wireless_Device                                             | 29        | 0.68%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 27        | 0.63%   |
| Apple Bluetooth USB Host Controller                                  | 27        | 0.63%   |
| Broadcom BCM2045B (BDC-2.1)                                          | 23        | 0.54%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 21        | 0.49%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                              | 20        | 0.47%   |
| TP-Link UB500 Adapter                                                | 17        | 0.4%    |
| ASUS Qualcomm Bluetooth 4.1                                          | 17        | 0.4%    |
| Lite-On Wireless_Device                                              | 16        | 0.37%   |
| Realtek RTL8821A Bluetooth                                           | 15        | 0.35%   |
| ASUS Bluetooth Radio                                                 | 14        | 0.33%   |
| Lite-On Atheros AR3012 Bluetooth                                     | 13        | 0.3%    |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 13        | 0.3%    |
| Realtek RTL8723B Bluetooth                                           | 12        | 0.28%   |
| Marvell Bluetooth and Wireless LAN Composite                         | 12        | 0.28%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 3873      | 40.86%  |
| AMD                                  | 2301      | 24.28%  |
| Nvidia                               | 1744      | 18.4%   |
| C-Media Electronics                  | 223       | 2.35%   |
| Logitech                             | 104       | 1.1%    |
| Kingston Technology                  | 78        | 0.82%   |
| Focusrite-Novation                   | 67        | 0.71%   |
| Texas Instruments                    | 63        | 0.66%   |
| JMTek                                | 60        | 0.63%   |
| SteelSeries ApS                      | 57        | 0.6%    |
| Realtek Semiconductor                | 52        | 0.55%   |
| Razer USA                            | 50        | 0.53%   |
| Lenovo                               | 44        | 0.46%   |
| Creative Labs                        | 43        | 0.45%   |
| Creative Technology                  | 39        | 0.41%   |
| Corsair                              | 39        | 0.41%   |
| Blue Microphones                     | 35        | 0.37%   |
| Samson Technologies                  | 26        | 0.27%   |
| GN Netcom                            | 25        | 0.26%   |
| ASUSTek Computer                     | 24        | 0.25%   |
| Valve Software                       | 20        | 0.21%   |
| Yamaha                               | 19        | 0.2%    |
| GYROCOM C&C                          | 19        | 0.2%    |
| Generalplus Technology               | 19        | 0.2%    |
| Sony                                 | 18        | 0.19%   |
| Apple                                | 18        | 0.19%   |
| BEHRINGER International              | 17        | 0.18%   |
| Plantronics                          | 14        | 0.15%   |
| FiiO Electronics Technology          | 14        | 0.15%   |
| Audio-Technica                       | 14        | 0.15%   |
| SAVITECH                             | 13        | 0.14%   |
| XMOS                                 | 12        | 0.13%   |
| M-Audio                              | 12        | 0.13%   |
| RODE Microphones                     | 10        | 0.11%   |
| Dell                                 | 10        | 0.11%   |
| Hewlett-Packard                      | 9         | 0.09%   |
| Cambridge Silicon Radio              | 9         | 0.09%   |
| Thesycon Systemsoftware & Consulting | 8         | 0.08%   |
| Microsoft                            | 8         | 0.08%   |
| Micro Star International             | 8         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 792       | 6.95%   |
| Intel Sunrise Point-LP HD Audio                                            | 565       | 4.96%   |
| AMD Starship/Matisse HD Audio Controller                                   | 540       | 4.74%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 400       | 3.51%   |
| Intel Cannon Lake PCH cAVS                                                 | 327       | 2.87%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 317       | 2.78%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 297       | 2.61%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 284       | 2.49%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 247       | 2.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 238       | 2.09%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 225       | 1.97%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 222       | 1.95%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 209       | 1.83%   |
| Nvidia GP107GL High Definition Audio Controller                            | 196       | 1.72%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 176       | 1.54%   |
| Nvidia GP104 High Definition Audio Controller                              | 166       | 1.46%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 165       | 1.45%   |
| AMD Navi 10 HDMI Audio                                                     | 165       | 1.45%   |
| Intel 200 Series PCH HD Audio                                              | 163       | 1.43%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 138       | 1.21%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 137       | 1.2%    |
| Nvidia GP106 High Definition Audio Controller                              | 132       | 1.16%   |
| Intel Broadwell-U Audio Controller                                         | 129       | 1.13%   |
| Nvidia TU106 High Definition Audio Controller                              | 126       | 1.11%   |
| Intel Haswell-ULT HD Audio Controller                                      | 126       | 1.11%   |
| Intel 8 Series HD Audio Controller                                         | 126       | 1.11%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 124       | 1.09%   |
| Intel Comet Lake PCH cAVS                                                  | 119       | 1.04%   |
| Intel CM238 HD Audio Controller                                            | 118       | 1.04%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 117       | 1.03%   |
| Nvidia TU116 High Definition Audio Controller                              | 109       | 0.96%   |
| Intel Comet Lake PCH-LP cAVS                                               | 106       | 0.93%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 104       | 0.91%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 98        | 0.86%   |
| Nvidia TU104 HD Audio Controller                                           | 97        | 0.85%   |
| Nvidia GA104 High Definition Audio Controller                              | 96        | 0.84%   |
| AMD FCH Azalia Controller                                                  | 88        | 0.77%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 78        | 0.68%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 75        | 0.66%   |
| Nvidia GM204 High Definition Audio Controller                              | 74        | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 1067      | 20.91%  |
| SK hynix                     | 795       | 15.58%  |
| Kingston                     | 637       | 12.49%  |
| Corsair                      | 500       | 9.8%    |
| Micron Technology            | 493       | 9.66%   |
| Crucial                      | 409       | 8.02%   |
| G.Skill                      | 322       | 6.31%   |
| Unknown                      | 277       | 5.43%   |
| A-DATA Technology            | 102       | 2%      |
| Ramaxel Technology           | 79        | 1.55%   |
| Elpida                       | 47        | 0.92%   |
| Team                         | 45        | 0.88%   |
| Patriot                      | 43        | 0.84%   |
| GOODRAM                      | 31        | 0.61%   |
| Nanya Technology             | 24        | 0.47%   |
| Unknown (ABCD)               | 21        | 0.41%   |
| Smart                        | 18        | 0.35%   |
| Transcend                    | 17        | 0.33%   |
| Unknown                      | 17        | 0.33%   |
| PNY                          | 13        | 0.25%   |
| AMD                          | 11        | 0.22%   |
| Goldkey                      | 9         | 0.18%   |
| Apacer                       | 8         | 0.16%   |
| Smart Brazil                 | 6         | 0.12%   |
| Teikon                       | 5         | 0.1%    |
| Golden Empire                | 5         | 0.1%    |
| GeIL                         | 5         | 0.1%    |
| Wilk Elektronik              | 4         | 0.08%   |
| Silicon Power                | 4         | 0.08%   |
| Neo Forza                    | 4         | 0.08%   |
| Avant                        | 4         | 0.08%   |
| V-GeN                        | 3         | 0.06%   |
| Patriot Memory (PDP Systems) | 3         | 0.06%   |
| KLEVV                        | 3         | 0.06%   |
| Kingmax                      | 3         | 0.06%   |
| GSkill                       | 3         | 0.06%   |
| ASint Technology             | 3         | 0.06%   |
| 48spaces                     | 3         | 0.06%   |
| Wilk                         | 2         | 0.04%   |
| Unifosa                      | 2         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 67        | 1.23%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 61        | 1.12%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 58        | 1.06%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 53        | 0.97%   |
| Corsair RAM CMK16GX4M2B3000C15 8192MB DIMM DDR4 3200MT/s         | 53        | 0.97%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 41        | 0.75%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 36        | 0.66%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 33        | 0.61%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 33        | 0.61%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s             | 30        | 0.55%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 29        | 0.53%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 27        | 0.5%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 26        | 0.48%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 26        | 0.48%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 25        | 0.46%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 25        | 0.46%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 25        | 0.46%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 24        | 0.44%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 24        | 0.44%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 24        | 0.44%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 23        | 0.42%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 23        | 0.42%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 23        | 0.42%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s             | 22        | 0.4%    |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 22        | 0.4%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 20        | 0.37%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 20        | 0.37%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 20        | 0.37%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 20        | 0.37%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 20        | 0.37%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s                | 20        | 0.37%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s              | 20        | 0.37%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 19        | 0.35%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 18        | 0.33%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 18        | 0.33%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 17        | 0.31%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 17        | 0.31%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 17        | 0.31%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 17        | 0.31%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 17        | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 2737      | 62.43%  |
| DDR3    | 1054      | 24.04%  |
| LPDDR4  | 163       | 3.72%   |
| LPDDR3  | 132       | 3.01%   |
| Unknown | 65        | 1.48%   |
| SDRAM   | 58        | 1.32%   |
| DDR2    | 57        | 1.3%    |
| DDR5    | 53        | 1.21%   |
| LPDDR5  | 49        | 1.12%   |
| DDR     | 15        | 0.34%   |
| DRAM    | 1         | 0.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 2282      | 52.09%  |
| DIMM         | 1692      | 38.62%  |
| Row Of Chips | 360       | 8.22%   |
| Chip         | 32        | 0.73%   |
| Unknown      | 12        | 0.27%   |
| RIMM         | 2         | 0.05%   |
| FB-DIMM      | 1         | 0.02%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 2178      | 45.9%   |
| 4096  | 1093      | 23.03%  |
| 16384 | 875       | 18.44%  |
| 2048  | 327       | 6.89%   |
| 32768 | 208       | 4.38%   |
| 1024  | 57        | 1.2%    |
| 512   | 6         | 0.13%   |
| 65536 | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 814       | 16.93%  |
| 2667    | 790       | 16.43%  |
| 1600    | 693       | 14.41%  |
| 2400    | 422       | 8.78%   |
| 2133    | 261       | 5.43%   |
| 3600    | 255       | 5.3%    |
| 1333    | 201       | 4.18%   |
| 1867    | 114       | 2.37%   |
| 1334    | 89        | 1.85%   |
| 4267    | 84        | 1.75%   |
| 3266    | 80        | 1.66%   |
| 3466    | 78        | 1.62%   |
| 3400    | 70        | 1.46%   |
| 3733    | 57        | 1.19%   |
| 3000    | 54        | 1.12%   |
| 6400    | 51        | 1.06%   |
| 2933    | 46        | 0.96%   |
| 667     | 46        | 0.96%   |
| 4800    | 42        | 0.87%   |
| 3800    | 42        | 0.87%   |
| 1067    | 36        | 0.75%   |
| 1866    | 33        | 0.69%   |
| Unknown | 33        | 0.69%   |
| 3866    | 30        | 0.62%   |
| 2800    | 30        | 0.62%   |
| 1066    | 29        | 0.6%    |
| 800     | 26        | 0.54%   |
| 3666    | 25        | 0.52%   |
| 2666    | 25        | 0.52%   |
| 4266    | 22        | 0.46%   |
| 8400    | 18        | 0.37%   |
| 4199    | 18        | 0.37%   |
| 400     | 12        | 0.25%   |
| 3333    | 11        | 0.23%   |
| 2048    | 10        | 0.21%   |
| 1800    | 10        | 0.21%   |
| 4000    | 9         | 0.19%   |
| 3066    | 9         | 0.19%   |
| 2733    | 9         | 0.19%   |
| 3151    | 8         | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Hewlett-Packard          | 32        | 36.36%  |
| Brother Industries       | 15        | 17.05%  |
| Samsung Electronics      | 13        | 14.77%  |
| Canon                    | 11        | 12.5%   |
| Seiko Epson              | 4         | 4.55%   |
| Prolific Technology      | 3         | 3.41%   |
| Dymo-CoStar              | 3         | 3.41%   |
| Zebra                    | 1         | 1.14%   |
| STMicroelectronics       | 1         | 1.14%   |
| Ricoh                    | 1         | 1.14%   |
| QinHeng Electronics      | 1         | 1.14%   |
| Magic Control Technology | 1         | 1.14%   |
| Fuji Xerox               | 1         | 1.14%   |
| Dell                     | 1         | 1.14%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Samsung M2070 Series                                      | 3         | 3.41%   |
| Prolific PL2305 Parallel Port                             | 3         | 3.41%   |
| HP DeskJet 2130 series                                    | 3         | 3.41%   |
| Samsung SCX-4100 Scanner                                  | 2         | 2.27%   |
| HP Officejet Pro 8100                                     | 2         | 2.27%   |
| HP LaserJet P2015 series                                  | 2         | 2.27%   |
| HP LaserJet 1022                                          | 2         | 2.27%   |
| HP LaserJet 1012                                          | 2         | 2.27%   |
| HP DeskJet 840c                                           | 2         | 2.27%   |
| HP Deskjet 3050 J610 series                               | 2         | 2.27%   |
| HP DeskJet 2620 All-in-One Printer                        | 2         | 2.27%   |
| Dymo-CoStar LabelWriter 450                               | 2         | 2.27%   |
| Brother Printer                                           | 2         | 2.27%   |
| Brother HL-5370DW series                                  | 2         | 2.27%   |
| Zebra LP2844 Printer                                      | 1         | 1.14%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 1.14%   |
| Seiko Epson XP-7100 Series                                | 1         | 1.14%   |
| Seiko Epson WF-2530 Series                                | 1         | 1.14%   |
| Seiko Epson Printer                                       | 1         | 1.14%   |
| Seiko Epson L3110 Series                                  | 1         | 1.14%   |
| Samsung SCX-4200 series                                   | 1         | 1.14%   |
| Samsung SCX-3200 Series                                   | 1         | 1.14%   |
| Samsung ML-216x Series Laser Printer                      | 1         | 1.14%   |
| Samsung ML-1610 Mono Laser Printer                        | 1         | 1.14%   |
| Samsung M267x 287x Series                                 | 1         | 1.14%   |
| Samsung M2020 Series                                      | 1         | 1.14%   |
| Samsung CLP-325 Color Laser Printer                       | 1         | 1.14%   |
| Samsung C1860 Series                                      | 1         | 1.14%   |
| Ricoh SP 150SU                                            | 1         | 1.14%   |
| QinHeng CH340S                                            | 1         | 1.14%   |
| Magic Control BAY-3U1S1P Parallel Port                    | 1         | 1.14%   |
| HP OfficeJet 5600 (USBHUB)                                | 1         | 1.14%   |
| HP Officejet 4500 G510g-m                                 | 1         | 1.14%   |
| HP LaserJet P1005                                         | 1         | 1.14%   |
| HP LaserJet M14-M17                                       | 1         | 1.14%   |
| HP LaserJet 1320                                          | 1         | 1.14%   |
| HP LaserJet 1200                                          | 1         | 1.14%   |
| HP LaserJet 1020                                          | 1         | 1.14%   |
| HP LaserJet 1018                                          | 1         | 1.14%   |
| HP Ink Tank 310 series                                    | 1         | 1.14%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Canon          | 10        | 55.56%  |
| Seiko Epson    | 6         | 33.33%  |
| Mustek Systems | 2         | 11.11%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo]                 | 2         | 11.11%  |
| Canon CanoScan N650U/N656U                                  | 2         | 11.11%  |
| Canon CanoScan LiDE 200                                     | 2         | 11.11%  |
| Seiko Epson GT-X900 [Perfection V700/V750 Photo]            | 1         | 5.56%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]     | 1         | 5.56%   |
| Seiko Epson GT-F700 [Perfection V350]                       | 1         | 5.56%   |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO] | 1         | 5.56%   |
| Mustek Systems ScanExpress 1200 UB                          | 1         | 5.56%   |
| Mustek Systems BearPaw 1200 CU Plus                         | 1         | 5.56%   |
| Canon CanoScan LiDE 60                                      | 1         | 5.56%   |
| Canon CanoScan LIDE 25                                      | 1         | 5.56%   |
| Canon CanoScan LiDE 220                                     | 1         | 5.56%   |
| Canon CanoScan LiDE 210                                     | 1         | 5.56%   |
| Canon CanoScan LiDE 120                                     | 1         | 5.56%   |
| Canon CanoScan LiDE 110                                     | 1         | 5.56%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 771       | 20.09%  |
| IMC Networks                           | 403       | 10.5%   |
| Logitech                               | 340       | 8.86%   |
| Microdia                               | 330       | 8.6%    |
| Realtek Semiconductor                  | 253       | 6.59%   |
| Quanta                                 | 202       | 5.26%   |
| Bison Electronics                      | 197       | 5.13%   |
| Sunplus Innovation Technology          | 162       | 4.22%   |
| Acer                                   | 152       | 3.96%   |
| Cheng Uei Precision Industry (Foxlink) | 127       | 3.31%   |
| Syntek                                 | 106       | 2.76%   |
| Lite-On Technology                     | 95        | 2.48%   |
| Apple                                  | 84        | 2.19%   |
| Luxvisions Innotech Limited            | 61        | 1.59%   |
| Suyin                                  | 60        | 1.56%   |
| Microsoft                              | 49        | 1.28%   |
| Samsung Electronics                    | 44        | 1.15%   |
| Silicon Motion                         | 40        | 1.04%   |
| Alcor Micro                            | 39        | 1.02%   |
| Lenovo                                 | 27        | 0.7%    |
| Z-Star Microelectronics                | 22        | 0.57%   |
| Valve Software                         | 17        | 0.44%   |
| MacroSilicon                           | 16        | 0.42%   |
| Sonix Technology                       | 14        | 0.36%   |
| ARC International                      | 13        | 0.34%   |
| SunplusIT                              | 11        | 0.29%   |
| Razer USA                              | 11        | 0.29%   |
| KYE Systems (Mouse Systems)            | 11        | 0.29%   |
| Importek                               | 11        | 0.29%   |
| ALi                                    | 11        | 0.29%   |
| Ricoh                                  | 10        | 0.26%   |
| Primax Electronics                     | 9         | 0.23%   |
| Generalplus Technology                 | 9         | 0.23%   |
| Shenzhen Kingcome Optoelectronic       | 7         | 0.18%   |
| LG Electronics                         | 7         | 0.18%   |
| Creative Technology                    | 7         | 0.18%   |
| Jieli Technology                       | 6         | 0.16%   |
| Google                                 | 6         | 0.16%   |
| Trust                                  | 5         | 0.13%   |
| Huawei Technologies                    | 5         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 218       | 5.62%   |
| Microdia Integrated_Webcam_HD                                              | 165       | 4.25%   |
| IMC Networks Integrated Camera                                             | 142       | 3.66%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 118       | 3.04%   |
| Chicony HD WebCam                                                          | 93        | 2.4%    |
| Realtek Integrated_Webcam_HD                                               | 87        | 2.24%   |
| Logitech HD Pro Webcam C920                                                | 70        | 1.8%    |
| Syntek Integrated Camera                                                   | 69        | 1.78%   |
| Sunplus Integrated_Webcam_HD                                               | 64        | 1.65%   |
| Bison Integrated Camera                                                    | 60        | 1.55%   |
| Logitech Webcam C270                                                       | 55        | 1.42%   |
| Acer Integrated Camera                                                     | 54        | 1.39%   |
| Quanta HD User Facing                                                      | 45        | 1.16%   |
| Lite-On Integrated Camera                                                  | 45        | 1.16%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 44        | 1.13%   |
| Bison SunplusIT Integrated Camera                                          | 41        | 1.06%   |
| Bison HD Webcam                                                            | 36        | 0.93%   |
| Chicony Integrated Camera (1280x720@30)                                    | 33        | 0.85%   |
| Apple FaceTime HD Camera (Built-in)                                        | 33        | 0.85%   |
| Chicony USB2.0 Camera                                                      | 32        | 0.82%   |
| Chicony HP HD Camera                                                       | 32        | 0.82%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 31        | 0.8%    |
| Chicony HP Wide Vision HD Camera                                           | 31        | 0.8%    |
| Logitech C922 Pro Stream Webcam                                            | 30        | 0.77%   |
| Microdia Integrated Webcam                                                 | 29        | 0.75%   |
| Chicony HD User Facing                                                     | 27        | 0.7%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 26        | 0.67%   |
| Realtek USB Camera                                                         | 24        | 0.62%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 24        | 0.62%   |
| Quanta HP Wide Vision HD Camera                                            | 23        | 0.59%   |
| Chicony EasyCamera                                                         | 23        | 0.59%   |
| Realtek Integrated Webcam                                                  | 22        | 0.57%   |
| IMC Networks ov9734_azurewave_camera                                       | 22        | 0.57%   |
| Acer Lenovo EasyCamera                                                     | 22        | 0.57%   |
| Microdia Webcam Vitade AF                                                  | 21        | 0.54%   |
| Chicony USB2.0 HD UVC WebCam                                               | 21        | 0.54%   |
| Quanta HP TrueVision HD Camera                                             | 20        | 0.52%   |
| Logitech BRIO Ultra HD Webcam                                              | 20        | 0.52%   |
| Chicony HP TrueVision HD Camera                                            | 20        | 0.52%   |
| Chicony HP Truevision HD                                                   | 20        | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 322       | 38.89%  |
| Validity Sensors                   | 210       | 25.36%  |
| Shenzhen Goodix Technology         | 148       | 17.87%  |
| Elan Microelectronics              | 53        | 6.4%    |
| LighTuning Technology              | 28        | 3.38%   |
| Upek                               | 26        | 3.14%   |
| AuthenTec                          | 21        | 2.54%   |
| STMicroelectronics                 | 9         | 1.09%   |
| Samsung Electronics                | 4         | 0.48%   |
| Microsoft                          | 3         | 0.36%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.24%   |
| Focal-systems.Corp                 | 1         | 0.12%   |
| DigitalPersona                     | 1         | 0.12%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 113       | 13.65%  |
| Shenzhen Goodix  Fingerprint Device                                        | 78        | 9.42%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 52        | 6.28%   |
| Shenzhen Goodix Fingerprint Reader                                         | 42        | 5.07%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 37        | 4.47%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 31        | 3.74%   |
| Synaptics UWP WBDI                                                         | 31        | 3.74%   |
| Elan ELAN:Fingerprint                                                      | 31        | 3.74%   |
| Shenzhen Goodix FingerPrint                                                | 28        | 3.38%   |
| Validity Sensors Synaptics WBDI                                            | 24        | 2.9%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 24        | 2.9%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 23        | 2.78%   |
| Synaptics  WBDI                                                            | 22        | 2.66%   |
| Elan ELAN:ARM-M4                                                           | 20        | 2.42%   |
| Synaptics WBDI                                                             | 19        | 2.29%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 19        | 2.29%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 18        | 2.17%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 18        | 2.17%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 16        | 1.93%   |
| Validity Sensors VFS491                                                    | 13        | 1.57%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 13        | 1.57%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 13        | 1.57%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 11        | 1.33%   |
| Validity Sensors Fingerprint scanner                                       | 11        | 1.33%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 11        | 1.33%   |
| AuthenTec AES2810                                                          | 11        | 1.33%   |
| Synaptics UWP WBDI Device                                                  | 9         | 1.09%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 9         | 1.09%   |
| STMicroelectronics Fingerprint Reader                                      | 9         | 1.09%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 8         | 0.97%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 6         | 0.72%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 0.6%    |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 5         | 0.6%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 0.48%   |
| Synaptics WBDI Device                                                      | 4         | 0.48%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 0.48%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 0.36%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 0.36%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.36%   |
| Samsung Fingerprint Device                                                 | 3         | 0.36%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Alcor Micro                       | 128       | 40.51%  |
| Broadcom                          | 108       | 34.18%  |
| Upek                              | 19        | 6.01%   |
| Lenovo                            | 11        | 3.48%   |
| Clay Logic                        | 8         | 2.53%   |
| O2 Micro                          | 7         | 2.22%   |
| Advanced Card Systems             | 6         | 1.9%    |
| Yubico.com                        | 5         | 1.58%   |
| SCM Microsystems                  | 4         | 1.27%   |
| Reiner SCT Kartensysteme          | 4         | 1.27%   |
| Gemalto (was Gemplus)             | 4         | 1.27%   |
| Aladdin Knowledge Systems         | 3         | 0.95%   |
| OmniKey                           | 2         | 0.63%   |
| VASCO Data Security International | 1         | 0.32%   |
| Realtek Semiconductor             | 1         | 0.32%   |
| Hewlett-Packard                   | 1         | 0.32%   |
| Fujitsu Siemens Computers         | 1         | 0.32%   |
| Chicony Electronics               | 1         | 0.32%   |
| Aladdin R.D.                      | 1         | 0.32%   |
| Aktiv                             | 1         | 0.32%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 126       | 39.87%  |
| Broadcom 5880                                                                | 31        | 9.81%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 29        | 9.18%   |
| Broadcom BCM5880 Secure Applications Processor                               | 24        | 7.59%   |
| Broadcom 58200                                                               | 22        | 6.96%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 19        | 6.01%   |
| Lenovo Integrated Smart Card Reader                                          | 11        | 3.48%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 6         | 1.9%    |
| Yubico.com Yubikey 4 U2F+CCID                                                | 5         | 1.58%   |
| Clay Logic Nitrokey Pro                                                      | 3         | 0.95%   |
| Aladdin Knowledge Systems Token JC                                           | 3         | 0.95%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 3         | 0.95%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 0.63%   |
| Reiner SCT Kartensysteme cyberJack one                                       | 2         | 0.63%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 0.63%   |
| Clay Logic Nitrokey Start                                                    | 2         | 0.63%   |
| Clay Logic CanoKey Pigeon                                                    | 2         | 0.63%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.63%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 0.63%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.32%   |
| SCM Microsystems SCR3500 C Contact Reader                                    | 1         | 0.32%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.32%   |
| Reiner SCT Kartensysteme tanJack USB                                         | 1         | 0.32%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.32%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.32%   |
| OmniKey Smart Card Reader USB                                                | 1         | 0.32%   |
| OmniKey 5022 Smart Card Reader                                               | 1         | 0.32%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.32%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.32%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.32%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.32%   |
| Fujitsu Siemens Computers Keyboard KB100 SCR eSIG                            | 1         | 0.32%   |
| Clay Logic Nitrokey HSM                                                      | 1         | 0.32%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.32%   |
| Aladdin R.D. JaCarta                                                         | 1         | 0.32%   |
| Aktiv Rutoken lite                                                           | 1         | 0.32%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.32%   |
| Advanced Card Systems ACR1252 Dual Reader                                    | 1         | 0.32%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.32%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 4290      | 69.94%  |
| 1     | 1475      | 24.05%  |
| 2     | 292       | 4.76%   |
| 3     | 64        | 1.04%   |
| 4     | 10        | 0.16%   |
| 7     | 1         | 0.02%   |
| 6     | 1         | 0.02%   |
| 5     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 807       | 36.29%  |
| Graphics card            | 410       | 18.44%  |
| Chipcard                 | 268       | 12.05%  |
| Net/wireless             | 194       | 8.72%   |
| Multimedia controller    | 150       | 6.74%   |
| Camera                   | 120       | 5.4%    |
| Unassigned class         | 51        | 2.29%   |
| Bluetooth                | 45        | 2.02%   |
| Communication controller | 44        | 1.98%   |
| Sound                    | 35        | 1.57%   |
| Net/ethernet             | 23        | 1.03%   |
| Network                  | 20        | 0.9%    |
| Storage                  | 17        | 0.76%   |
| Card reader              | 13        | 0.58%   |
| Modem                    | 9         | 0.4%    |
| Dvb card                 | 6         | 0.27%   |
| Wireless                 | 2         | 0.09%   |
| Storage/raid             | 2         | 0.09%   |
| Storage/nvme             | 2         | 0.09%   |
| Storage/ide              | 2         | 0.09%   |
| Tv card                  | 1         | 0.04%   |
| Storage/ata              | 1         | 0.04%   |
| Flash memory             | 1         | 0.04%   |
| Firewire controller      | 1         | 0.04%   |

