Linux in Belarus - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Belarus.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Belarus/Desktop/README.md) and [notebooks](/Location/Belarus/Notebook/README.md).

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

Total: 2015

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASRock        | 960GM-VGS3 FX               | Desktop     | [e4da7ca430](https://linux-hardware.org/?probe=e4da7ca430) | Jan 05, 2025 |
| Biostar       | A320MH                      | Desktop     | [a6f434cc49](https://linux-hardware.org/?probe=a6f434cc49) | Jan 04, 2025 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [24988d9cd8](https://linux-hardware.org/?probe=24988d9cd8) | Jan 04, 2025 |
| HP            | Compaq 610                  | Notebook    | [794f66ac7e](https://linux-hardware.org/?probe=794f66ac7e) | Jan 03, 2025 |
| HP            | Compaq 610                  | Notebook    | [9e050e5a86](https://linux-hardware.org/?probe=9e050e5a86) | Jan 03, 2025 |
| Xiaomi        | Mi A2 Lite                  | Soc         | [c43c4ec4d3](https://linux-hardware.org/?probe=c43c4ec4d3) | Dec 27, 2024 |
| Gigabyte      | H87-HD3                     | Desktop     | [0d4b3ad560](https://linux-hardware.org/?probe=0d4b3ad560) | Dec 27, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [8c51d26687](https://linux-hardware.org/?probe=8c51d26687) | Dec 27, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [421416a69e](https://linux-hardware.org/?probe=421416a69e) | Dec 25, 2024 |
| MSI           | B450 TOMAHAWK               | Desktop     | [d999df797b](https://linux-hardware.org/?probe=d999df797b) | Dec 25, 2024 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [c57720c15f](https://linux-hardware.org/?probe=c57720c15f) | Dec 23, 2024 |
| Lenovo        | IdeaPad U330 Touch 20268    | Notebook    | [480ee6fe0c](https://linux-hardware.org/?probe=480ee6fe0c) | Dec 22, 2024 |
| HONOR         | BRN-GXXXA                   | Notebook    | [807540b5a6](https://linux-hardware.org/?probe=807540b5a6) | Dec 21, 2024 |
| Lenovo        | B50-30 20382                | Notebook    | [4ccf2f7c9a](https://linux-hardware.org/?probe=4ccf2f7c9a) | Dec 17, 2024 |
| Gigabyte      | H61M-DS2                    | Desktop     | [ed02a12fef](https://linux-hardware.org/?probe=ed02a12fef) | Dec 17, 2024 |
| ASRock        | B75 Pro3                    | Desktop     | [f470c0e8ba](https://linux-hardware.org/?probe=f470c0e8ba) | Dec 16, 2024 |
| Dell          | 0PGMR1 A00                  | All in one  | [274dc30d2c](https://linux-hardware.org/?probe=274dc30d2c) | Dec 14, 2024 |
| Unknown       | Unknown                     | Notebook    | [7b1d93f1d8](https://linux-hardware.org/?probe=7b1d93f1d8) | Dec 14, 2024 |
| ASUSTek       | ASUS Vivobook S 16 M5606... | Notebook    | [7babd755f8](https://linux-hardware.org/?probe=7babd755f8) | Dec 14, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [991cc2d32a](https://linux-hardware.org/?probe=991cc2d32a) | Dec 13, 2024 |
| Gigabyte      | 945P-S3                     | Desktop     | [47cce301db](https://linux-hardware.org/?probe=47cce301db) | Dec 12, 2024 |
| Valve         | Galileo                     | Notebook    | [43f1ef2e9b](https://linux-hardware.org/?probe=43f1ef2e9b) | Dec 09, 2024 |
| HP            | 635                         | Notebook    | [edbc6c91c9](https://linux-hardware.org/?probe=edbc6c91c9) | Dec 08, 2024 |
| HP            | 635                         | Notebook    | [d6320333bd](https://linux-hardware.org/?probe=d6320333bd) | Dec 08, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [d5bfbc4908](https://linux-hardware.org/?probe=d5bfbc4908) | Dec 08, 2024 |
| Biostar       | B450MH                      | Desktop     | [ecf1f7fc9e](https://linux-hardware.org/?probe=ecf1f7fc9e) | Nov 28, 2024 |
| Biostar       | B450MH                      | Desktop     | [b6de2bc533](https://linux-hardware.org/?probe=b6de2bc533) | Nov 25, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [05ba4aef25](https://linux-hardware.org/?probe=05ba4aef25) | Nov 25, 2024 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [6ff921cfe0](https://linux-hardware.org/?probe=6ff921cfe0) | Nov 23, 2024 |
| ASUSTek       | P8H61/USB3                  | Desktop     | [6d27d6c54c](https://linux-hardware.org/?probe=6d27d6c54c) | Nov 22, 2024 |
| ASUSTek       | P8H61/USB3                  | Desktop     | [90ebd3b804](https://linux-hardware.org/?probe=90ebd3b804) | Nov 22, 2024 |
| ASUSTek       | P8H61/USB3                  | Desktop     | [645136fe14](https://linux-hardware.org/?probe=645136fe14) | Nov 22, 2024 |
| MSI           | 760GM-P21                   | Desktop     | [7c2250da16](https://linux-hardware.org/?probe=7c2250da16) | Nov 21, 2024 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [fe0101038e](https://linux-hardware.org/?probe=fe0101038e) | Nov 21, 2024 |
| Acer          | Nitro AN16-41               | Notebook    | [951075dc66](https://linux-hardware.org/?probe=951075dc66) | Nov 20, 2024 |
| HONOR         | BRN-GXXXA                   | Notebook    | [225ca8921e](https://linux-hardware.org/?probe=225ca8921e) | Nov 20, 2024 |
| ASUSTek       | G551JM                      | Notebook    | [9a3ec47e80](https://linux-hardware.org/?probe=9a3ec47e80) | Nov 18, 2024 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [ef74bd73ca](https://linux-hardware.org/?probe=ef74bd73ca) | Nov 18, 2024 |
| HP            | ProBook 455 G7              | Notebook    | [44aae5e204](https://linux-hardware.org/?probe=44aae5e204) | Nov 17, 2024 |
| MSI           | MS-B0A41                    | Desktop     | [5d444abac4](https://linux-hardware.org/?probe=5d444abac4) | Nov 17, 2024 |
| Lenovo        | Legion Slim 5 16IRH8 82Y... | Notebook    | [315c87d17e](https://linux-hardware.org/?probe=315c87d17e) | Nov 15, 2024 |
| SYS           | H310CH5-TI2                 | Desktop     | [8d26063a45](https://linux-hardware.org/?probe=8d26063a45) | Nov 13, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [9444901be4](https://linux-hardware.org/?probe=9444901be4) | Nov 12, 2024 |
| Samsung       | N100SP                      | Notebook    | [b00ed819df](https://linux-hardware.org/?probe=b00ed819df) | Nov 09, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [64c612c343](https://linux-hardware.org/?probe=64c612c343) | Nov 08, 2024 |
| ASUSTek       | X502CA                      | Notebook    | [c3f5b58d2d](https://linux-hardware.org/?probe=c3f5b58d2d) | Nov 07, 2024 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [f9621cdfb7](https://linux-hardware.org/?probe=f9621cdfb7) | Nov 06, 2024 |
| Intel         | 600 Series Chipset          | All in one  | [6d7771e4f6](https://linux-hardware.org/?probe=6d7771e4f6) | Nov 04, 2024 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [133d4cc06b](https://linux-hardware.org/?probe=133d4cc06b) | Nov 02, 2024 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [aa9d2deca0](https://linux-hardware.org/?probe=aa9d2deca0) | Nov 01, 2024 |
| HONOR         | BMH-WDX9                    | Notebook    | [c500bafec7](https://linux-hardware.org/?probe=c500bafec7) | Nov 01, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [f08aabcfa6](https://linux-hardware.org/?probe=f08aabcfa6) | Oct 30, 2024 |
| Lenovo        | Legion Slim 5 16IRH8 82Y... | Notebook    | [eb4dd2b1af](https://linux-hardware.org/?probe=eb4dd2b1af) | Oct 29, 2024 |
| ASRock        | B75 Pro3-M                  | Desktop     | [cfd685d227](https://linux-hardware.org/?probe=cfd685d227) | Oct 26, 2024 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [b6cd810793](https://linux-hardware.org/?probe=b6cd810793) | Oct 26, 2024 |
| Acer          | Aspire A515-57              | Notebook    | [080619fd06](https://linux-hardware.org/?probe=080619fd06) | Oct 23, 2024 |
| Unknown       | Unknown                     | Notebook    | [2a37270718](https://linux-hardware.org/?probe=2a37270718) | Oct 23, 2024 |
| Unknown       | Unknown                     | Notebook    | [6dee0548b7](https://linux-hardware.org/?probe=6dee0548b7) | Oct 23, 2024 |
| HONOR         | BRN-GXXXA                   | Notebook    | [c8f365af9e](https://linux-hardware.org/?probe=c8f365af9e) | Oct 23, 2024 |
| Lenovo        | ThinkPad T60 1951PRG        | Notebook    | [089028ad63](https://linux-hardware.org/?probe=089028ad63) | Oct 23, 2024 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [a6feae9021](https://linux-hardware.org/?probe=a6feae9021) | Oct 19, 2024 |
| XIAOMI        | Redmi G Pro 2024            | Notebook    | [d147a798ae](https://linux-hardware.org/?probe=d147a798ae) | Oct 19, 2024 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | Desktop     | [01ec398b73](https://linux-hardware.org/?probe=01ec398b73) | Oct 18, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [5a1fe5a14c](https://linux-hardware.org/?probe=5a1fe5a14c) | Oct 18, 2024 |
| Intel         | NUC7i7BNB J31145-309        | Mini pc     | [23c459c9f0](https://linux-hardware.org/?probe=23c459c9f0) | Oct 16, 2024 |
| OEM           | X79G                        | Desktop     | [eff532dd89](https://linux-hardware.org/?probe=eff532dd89) | Oct 16, 2024 |
| Lenovo        | ThinkPad T60 1951PRG        | Notebook    | [365127d13e](https://linux-hardware.org/?probe=365127d13e) | Oct 16, 2024 |
| Lenovo        | B590 20208                  | Notebook    | [166b59a578](https://linux-hardware.org/?probe=166b59a578) | Oct 15, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [d2a7008bf5](https://linux-hardware.org/?probe=d2a7008bf5) | Oct 14, 2024 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [4e5f665d8f](https://linux-hardware.org/?probe=4e5f665d8f) | Oct 13, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [f9f7df5d1c](https://linux-hardware.org/?probe=f9f7df5d1c) | Oct 11, 2024 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [26f0747dd8](https://linux-hardware.org/?probe=26f0747dd8) | Oct 04, 2024 |
| ASUSTek       | Zenbook UX6404VI_UX6404V... | Notebook    | [a205518bed](https://linux-hardware.org/?probe=a205518bed) | Oct 04, 2024 |
| Lenovo        | Yoga 6 13ABR8 83B2          | Convertible | [65e2cb6b20](https://linux-hardware.org/?probe=65e2cb6b20) | Sep 30, 2024 |
| ASUSTek       | P8H61/USB3                  | Desktop     | [9abaa26cf8](https://linux-hardware.org/?probe=9abaa26cf8) | Sep 29, 2024 |
| Lenovo        | G580 20150                  | Notebook    | [a5db1c0652](https://linux-hardware.org/?probe=a5db1c0652) | Sep 27, 2024 |
| Lenovo        | G580 20150                  | Notebook    | [9f8c1e9038](https://linux-hardware.org/?probe=9f8c1e9038) | Sep 27, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JN0... | Notebook    | [2d0c60bf4e](https://linux-hardware.org/?probe=2d0c60bf4e) | Sep 27, 2024 |
| XIAOMI        | Redmi Book Pro 16 2024      | Notebook    | [6a52ea0ebd](https://linux-hardware.org/?probe=6a52ea0ebd) | Sep 25, 2024 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [62d6c200d1](https://linux-hardware.org/?probe=62d6c200d1) | Sep 23, 2024 |
| Gigabyte      | Z490M                       | Desktop     | [f58771ba9f](https://linux-hardware.org/?probe=f58771ba9f) | Sep 20, 2024 |
| ASUSTek       | K75VJ                       | Notebook    | [0d79ca1d3e](https://linux-hardware.org/?probe=0d79ca1d3e) | Sep 19, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [6e8490c300](https://linux-hardware.org/?probe=6e8490c300) | Sep 19, 2024 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [bbd5f8540d](https://linux-hardware.org/?probe=bbd5f8540d) | Sep 17, 2024 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [d95875adcb](https://linux-hardware.org/?probe=d95875adcb) | Sep 16, 2024 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [bca588f976](https://linux-hardware.org/?probe=bca588f976) | Sep 16, 2024 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [b5e40eff86](https://linux-hardware.org/?probe=b5e40eff86) | Sep 16, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [0b51bb9bd2](https://linux-hardware.org/?probe=0b51bb9bd2) | Sep 14, 2024 |
| Lenovo        | ThinkBook 16 G6 IRL 21KH    | Notebook    | [59d0bd0a62](https://linux-hardware.org/?probe=59d0bd0a62) | Sep 13, 2024 |
| ASUSTek       | P8H77-V                     | Desktop     | [ff26cf431a](https://linux-hardware.org/?probe=ff26cf431a) | Sep 12, 2024 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [4026e18342](https://linux-hardware.org/?probe=4026e18342) | Sep 11, 2024 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [379289ebbf](https://linux-hardware.org/?probe=379289ebbf) | Sep 09, 2024 |
| ASRock        | N68-S                       | Desktop     | [0655a7709d](https://linux-hardware.org/?probe=0655a7709d) | Sep 08, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [099a44d5c4](https://linux-hardware.org/?probe=099a44d5c4) | Sep 08, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [0232ff85b0](https://linux-hardware.org/?probe=0232ff85b0) | Sep 02, 2024 |
| ASRock        | B550M-HDV                   | Desktop     | [4b92cc3c63](https://linux-hardware.org/?probe=4b92cc3c63) | Sep 01, 2024 |
| HP            | ProBook 450 G1              | Notebook    | [ed328c0f34](https://linux-hardware.org/?probe=ed328c0f34) | Aug 30, 2024 |
| Google        | Eve                         | Convertible | [c7569290e0](https://linux-hardware.org/?probe=c7569290e0) | Aug 28, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [093d90b1d5](https://linux-hardware.org/?probe=093d90b1d5) | Aug 24, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [b4dc6d4025](https://linux-hardware.org/?probe=b4dc6d4025) | Aug 24, 2024 |
| Dell          | System XPS L702X            | Notebook    | [d60b03b0d1](https://linux-hardware.org/?probe=d60b03b0d1) | Aug 23, 2024 |
| HONOR         | BRN-GXXXA                   | Notebook    | [009ca8504c](https://linux-hardware.org/?probe=009ca8504c) | Aug 23, 2024 |
| HONOR         | BRN-GXXXA                   | Notebook    | [6efcf8828e](https://linux-hardware.org/?probe=6efcf8828e) | Aug 22, 2024 |
| ASUSTek       | P8H67                       | Desktop     | [54e766f338](https://linux-hardware.org/?probe=54e766f338) | Aug 21, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [cd3c86e29e](https://linux-hardware.org/?probe=cd3c86e29e) | Aug 19, 2024 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [98717af6ba](https://linux-hardware.org/?probe=98717af6ba) | Aug 17, 2024 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [3ad0429ccd](https://linux-hardware.org/?probe=3ad0429ccd) | Aug 17, 2024 |
| Gigabyte      | B360M H                     | Desktop     | [fafa37b23d](https://linux-hardware.org/?probe=fafa37b23d) | Aug 16, 2024 |
| Unknown       | Unknown                     | Notebook    | [12c94139b3](https://linux-hardware.org/?probe=12c94139b3) | Aug 15, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [9a670dddb0](https://linux-hardware.org/?probe=9a670dddb0) | Aug 15, 2024 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [d8da63d7d2](https://linux-hardware.org/?probe=d8da63d7d2) | Aug 13, 2024 |
| Unknown       | Unknown                     | Desktop     | [912389ef25](https://linux-hardware.org/?probe=912389ef25) | Aug 13, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [33ad33fe63](https://linux-hardware.org/?probe=33ad33fe63) | Aug 12, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [bfc7fb420a](https://linux-hardware.org/?probe=bfc7fb420a) | Aug 09, 2024 |
| ASRock        | B365 Pro4                   | Desktop     | [b4d1c67ec8](https://linux-hardware.org/?probe=b4d1c67ec8) | Aug 08, 2024 |
| Biostar       | B450MH                      | Desktop     | [743837e02f](https://linux-hardware.org/?probe=743837e02f) | Aug 08, 2024 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [af1581b6de](https://linux-hardware.org/?probe=af1581b6de) | Aug 08, 2024 |
| ASUSTek       | K72F                        | Notebook    | [49b3023981](https://linux-hardware.org/?probe=49b3023981) | Aug 04, 2024 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [e48819d1c3](https://linux-hardware.org/?probe=e48819d1c3) | Aug 02, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [4bdee79709](https://linux-hardware.org/?probe=4bdee79709) | Aug 01, 2024 |
| Acer          | Aspire A315-41G             | Notebook    | [0f89433c33](https://linux-hardware.org/?probe=0f89433c33) | Jul 31, 2024 |
| Unknown       | Unknown                     | Soc         | [93741bf083](https://linux-hardware.org/?probe=93741bf083) | Jul 30, 2024 |
| ASUSTek       | X751LD                      | Notebook    | [2214cc62b5](https://linux-hardware.org/?probe=2214cc62b5) | Jul 29, 2024 |
| HP            | ProBook 6570b               | Notebook    | [de1d8f4d47](https://linux-hardware.org/?probe=de1d8f4d47) | Jul 29, 2024 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [d16a09f4b0](https://linux-hardware.org/?probe=d16a09f4b0) | Jul 25, 2024 |
| Gigabyte      | Z490M                       | Desktop     | [9c57fd52d1](https://linux-hardware.org/?probe=9c57fd52d1) | Jul 25, 2024 |
| Dell          | Inspiron 3542               | Notebook    | [4ac934318c](https://linux-hardware.org/?probe=4ac934318c) | Jul 24, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [417f787589](https://linux-hardware.org/?probe=417f787589) | Jul 23, 2024 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [eac05e9202](https://linux-hardware.org/?probe=eac05e9202) | Jul 21, 2024 |
| ASUSTek       | G551JM                      | Notebook    | [2e110167ca](https://linux-hardware.org/?probe=2e110167ca) | Jul 20, 2024 |
| MSI           | 760GM-P33                   | Desktop     | [7180781cbd](https://linux-hardware.org/?probe=7180781cbd) | Jul 14, 2024 |
| Lenovo        | YB1-X91L                    | Tablet      | [94a88e48bc](https://linux-hardware.org/?probe=94a88e48bc) | Jul 10, 2024 |
| Acer          | Aspire A515-57              | Notebook    | [1b9c516078](https://linux-hardware.org/?probe=1b9c516078) | Jul 09, 2024 |
| MSI           | MS-7507                     | Desktop     | [aa3d0a38c5](https://linux-hardware.org/?probe=aa3d0a38c5) | Jul 07, 2024 |
| HP            | EliteBook 850 G6            | Notebook    | [dad6e3a225](https://linux-hardware.org/?probe=dad6e3a225) | Jul 05, 2024 |
| ASUSTek       | P5B-VM SE                   | Desktop     | [516a348cbb](https://linux-hardware.org/?probe=516a348cbb) | Jul 04, 2024 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [d325016ee3](https://linux-hardware.org/?probe=d325016ee3) | Jul 01, 2024 |
| Acer          | Aspire V5-531G              | Notebook    | [f0e61bf14e](https://linux-hardware.org/?probe=f0e61bf14e) | Jun 29, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [40a0b93e79](https://linux-hardware.org/?probe=40a0b93e79) | Jun 25, 2024 |
| Lenovo        | ThinkPad T60 1951PRG        | Notebook    | [9ce879085a](https://linux-hardware.org/?probe=9ce879085a) | Jun 22, 2024 |
| Acer          | Aspire 5520                 | Notebook    | [38b0efce2b](https://linux-hardware.org/?probe=38b0efce2b) | Jun 19, 2024 |
| Lenovo        | ThinkBook 16 G6+ AHP 21L... | Notebook    | [dda20727cf](https://linux-hardware.org/?probe=dda20727cf) | Jun 17, 2024 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [e63692d53f](https://linux-hardware.org/?probe=e63692d53f) | Jun 07, 2024 |
| Lenovo        | ThinkPad T530 239233G       | Notebook    | [345c49abb2](https://linux-hardware.org/?probe=345c49abb2) | Jun 07, 2024 |
| HP            | EliteBook 850 G6            | Notebook    | [bd85e0e901](https://linux-hardware.org/?probe=bd85e0e901) | Jun 06, 2024 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [fd1189140e](https://linux-hardware.org/?probe=fd1189140e) | Jun 03, 2024 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [8d83957016](https://linux-hardware.org/?probe=8d83957016) | Jun 02, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [2b03d3678f](https://linux-hardware.org/?probe=2b03d3678f) | Jun 02, 2024 |
| HP            | Pavilion 15                 | Notebook    | [5c070443f1](https://linux-hardware.org/?probe=5c070443f1) | Jun 01, 2024 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [e06294aab3](https://linux-hardware.org/?probe=e06294aab3) | May 31, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [272b938149](https://linux-hardware.org/?probe=272b938149) | May 29, 2024 |
| F-Plus Mob... | FLAPTOP r                   | Notebook    | [4a254dd2f6](https://linux-hardware.org/?probe=4a254dd2f6) | May 27, 2024 |
| ASUSTek       | GL503VD                     | Notebook    | [e62da11819](https://linux-hardware.org/?probe=e62da11819) | May 25, 2024 |
| MSI           | MPG B650I EDGE WIFI         | Desktop     | [a8ec581725](https://linux-hardware.org/?probe=a8ec581725) | May 25, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [bf4058990a](https://linux-hardware.org/?probe=bf4058990a) | May 23, 2024 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [82693ffe8f](https://linux-hardware.org/?probe=82693ffe8f) | May 21, 2024 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [479cc864f1](https://linux-hardware.org/?probe=479cc864f1) | May 20, 2024 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [e458694e12](https://linux-hardware.org/?probe=e458694e12) | May 15, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [7e80ab6e85](https://linux-hardware.org/?probe=7e80ab6e85) | May 14, 2024 |
| Gigabyte      | GA-MA770-US3                | Desktop     | [b1fc8c6d40](https://linux-hardware.org/?probe=b1fc8c6d40) | May 14, 2024 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [79a7d16e29](https://linux-hardware.org/?probe=79a7d16e29) | May 12, 2024 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [7cd20b2530](https://linux-hardware.org/?probe=7cd20b2530) | May 08, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [32e408088d](https://linux-hardware.org/?probe=32e408088d) | May 07, 2024 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [6e17fb9c95](https://linux-hardware.org/?probe=6e17fb9c95) | May 02, 2024 |
| Lenovo        | ThinkPad X395 20NMS0D900    | Notebook    | [47098170bb](https://linux-hardware.org/?probe=47098170bb) | May 01, 2024 |
| ASUSTek       | P5B-VM SE                   | Desktop     | [b3631ed021](https://linux-hardware.org/?probe=b3631ed021) | Apr 29, 2024 |
| HP            | ProBook 4535s               | Notebook    | [34910d04e7](https://linux-hardware.org/?probe=34910d04e7) | Apr 28, 2024 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [3dcaa02108](https://linux-hardware.org/?probe=3dcaa02108) | Apr 28, 2024 |
| Lenovo        | ThinkPad E14 20RA001HRT     | Notebook    | [714f84cadb](https://linux-hardware.org/?probe=714f84cadb) | Apr 26, 2024 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [e21d70e37d](https://linux-hardware.org/?probe=e21d70e37d) | Apr 26, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [8c81adc916](https://linux-hardware.org/?probe=8c81adc916) | Apr 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [bc0e0ae6b8](https://linux-hardware.org/?probe=bc0e0ae6b8) | Apr 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [10a878e186](https://linux-hardware.org/?probe=10a878e186) | Apr 25, 2024 |
| Lenovo        | XiaoXinPro 16 AHP9 83D5     | Notebook    | [bec1c58cef](https://linux-hardware.org/?probe=bec1c58cef) | Apr 25, 2024 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [d96419f8cf](https://linux-hardware.org/?probe=d96419f8cf) | Apr 23, 2024 |
| TECNO         | MEGABOOK T1                 | Notebook    | [01fc56cf5b](https://linux-hardware.org/?probe=01fc56cf5b) | Apr 22, 2024 |
| Lenovo        | Legion R7000P APH8 82Y9     | Notebook    | [a3f2909959](https://linux-hardware.org/?probe=a3f2909959) | Apr 22, 2024 |
| ASRock        | B85M-ITX                    | Desktop     | [c868a15a8f](https://linux-hardware.org/?probe=c868a15a8f) | Apr 20, 2024 |
| Lenovo        | Yoga 6 13ABR8 83B2          | Convertible | [31da76530e](https://linux-hardware.org/?probe=31da76530e) | Apr 13, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9a0c435db3](https://linux-hardware.org/?probe=9a0c435db3) | Apr 12, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [f73b16ab18](https://linux-hardware.org/?probe=f73b16ab18) | Apr 11, 2024 |
| ASUSTek       | K55VM                       | Notebook    | [9293006922](https://linux-hardware.org/?probe=9293006922) | Apr 09, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [2500fb4398](https://linux-hardware.org/?probe=2500fb4398) | Apr 09, 2024 |
| Toshiba       | Satellite C850-C5K          | Notebook    | [81be04c868](https://linux-hardware.org/?probe=81be04c868) | Apr 09, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [eadddcdc8e](https://linux-hardware.org/?probe=eadddcdc8e) | Apr 06, 2024 |
| ASUSTek       | K55VM                       | Notebook    | [dff985be75](https://linux-hardware.org/?probe=dff985be75) | Apr 05, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [871311fcdc](https://linux-hardware.org/?probe=871311fcdc) | Apr 03, 2024 |
| ASUSTek       | P5B-VM SE                   | Desktop     | [9e6d967077](https://linux-hardware.org/?probe=9e6d967077) | Apr 03, 2024 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [74e2ba96da](https://linux-hardware.org/?probe=74e2ba96da) | Apr 02, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B5402CVA... | Notebook    | [6d0d8895f9](https://linux-hardware.org/?probe=6d0d8895f9) | Apr 02, 2024 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | Notebook    | [a42873dcf9](https://linux-hardware.org/?probe=a42873dcf9) | Apr 01, 2024 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [48dfdf4137](https://linux-hardware.org/?probe=48dfdf4137) | Apr 01, 2024 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [d209d00332](https://linux-hardware.org/?probe=d209d00332) | Apr 01, 2024 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [953610ee17](https://linux-hardware.org/?probe=953610ee17) | Mar 28, 2024 |
| ASUSTek       | X553MA                      | Notebook    | [5d1d7ed87a](https://linux-hardware.org/?probe=5d1d7ed87a) | Mar 28, 2024 |
| XIAOMI        | Redmi Book Pro 15 2023      | Notebook    | [90ff22d8c1](https://linux-hardware.org/?probe=90ff22d8c1) | Mar 25, 2024 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [6bb15775d7](https://linux-hardware.org/?probe=6bb15775d7) | Mar 24, 2024 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [11f7843550](https://linux-hardware.org/?probe=11f7843550) | Mar 23, 2024 |
| HONOR         | BMH-WDX9                    | Notebook    | [4445879c66](https://linux-hardware.org/?probe=4445879c66) | Mar 21, 2024 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [90a25e637e](https://linux-hardware.org/?probe=90a25e637e) | Mar 21, 2024 |
| HONOR         | BMH-WDX9                    | Notebook    | [01284be05a](https://linux-hardware.org/?probe=01284be05a) | Mar 20, 2024 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [9d76e364c6](https://linux-hardware.org/?probe=9d76e364c6) | Mar 20, 2024 |
| ASRock        | B550M-HDV                   | Desktop     | [8adaf6e6b2](https://linux-hardware.org/?probe=8adaf6e6b2) | Mar 17, 2024 |
| MSI           | B450-A PRO                  | Desktop     | [de6730ef57](https://linux-hardware.org/?probe=de6730ef57) | Mar 13, 2024 |
| HP            | 650                         | Notebook    | [8968085c5a](https://linux-hardware.org/?probe=8968085c5a) | Mar 13, 2024 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [6bea275119](https://linux-hardware.org/?probe=6bea275119) | Mar 12, 2024 |
| HP            | Laptop 17-ak0xx             | Notebook    | [a5d4f19046](https://linux-hardware.org/?probe=a5d4f19046) | Mar 12, 2024 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [86024c45ed](https://linux-hardware.org/?probe=86024c45ed) | Mar 12, 2024 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [a65a82b4d4](https://linux-hardware.org/?probe=a65a82b4d4) | Mar 12, 2024 |
| HP            | ProBook 650 G2              | Notebook    | [c99a1426a1](https://linux-hardware.org/?probe=c99a1426a1) | Mar 07, 2024 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [bab57077f5](https://linux-hardware.org/?probe=bab57077f5) | Mar 06, 2024 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [544a3548cc](https://linux-hardware.org/?probe=544a3548cc) | Mar 05, 2024 |
| Intel         | B760 E1.0G                  | Desktop     | [3908f7bec6](https://linux-hardware.org/?probe=3908f7bec6) | Mar 04, 2024 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | Notebook    | [cda628788e](https://linux-hardware.org/?probe=cda628788e) | Mar 01, 2024 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | Notebook    | [08024a8cef](https://linux-hardware.org/?probe=08024a8cef) | Mar 01, 2024 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [43919c6c44](https://linux-hardware.org/?probe=43919c6c44) | Feb 29, 2024 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [19c9cc81e5](https://linux-hardware.org/?probe=19c9cc81e5) | Feb 26, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [0fa9131028](https://linux-hardware.org/?probe=0fa9131028) | Feb 26, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [367494d4cf](https://linux-hardware.org/?probe=367494d4cf) | Feb 24, 2024 |
| Sony          | SVF1521L1RB                 | Notebook    | [4b0e081c62](https://linux-hardware.org/?probe=4b0e081c62) | Feb 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [3514879254](https://linux-hardware.org/?probe=3514879254) | Feb 22, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [37b9530a2a](https://linux-hardware.org/?probe=37b9530a2a) | Feb 22, 2024 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [4aa25676bc](https://linux-hardware.org/?probe=4aa25676bc) | Feb 22, 2024 |
| HONOR         | NBR-WAX9                    | Notebook    | [6fa625a010](https://linux-hardware.org/?probe=6fa625a010) | Feb 21, 2024 |
| ASRock        | K10N78D                     | Desktop     | [31060d37cf](https://linux-hardware.org/?probe=31060d37cf) | Feb 18, 2024 |
| Lenovo        | G50-30 80G0                 | Notebook    | [16a4080794](https://linux-hardware.org/?probe=16a4080794) | Feb 17, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | Notebook    | [cdd51cbb3d](https://linux-hardware.org/?probe=cdd51cbb3d) | Feb 16, 2024 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [c98ffdb659](https://linux-hardware.org/?probe=c98ffdb659) | Feb 16, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2f303b1ad2](https://linux-hardware.org/?probe=2f303b1ad2) | Feb 15, 2024 |
| AMD           | A88DA                       | Desktop     | [89ca695711](https://linux-hardware.org/?probe=89ca695711) | Feb 14, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [2d39984c89](https://linux-hardware.org/?probe=2d39984c89) | Feb 14, 2024 |
| MSI           | Katana GF66 11UD            | Notebook    | [2adf0be9f1](https://linux-hardware.org/?probe=2adf0be9f1) | Feb 12, 2024 |
| MSI           | Katana GF66 11UD            | Notebook    | [062c0b91a4](https://linux-hardware.org/?probe=062c0b91a4) | Feb 12, 2024 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | Notebook    | [9b3e403b41](https://linux-hardware.org/?probe=9b3e403b41) | Feb 11, 2024 |
| ASRock        | N68-GS                      | Desktop     | [06f147ad72](https://linux-hardware.org/?probe=06f147ad72) | Feb 09, 2024 |
| ASRock        | H61M-HVGS                   | Desktop     | [dc3bd18c15](https://linux-hardware.org/?probe=dc3bd18c15) | Feb 09, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [1e1676f874](https://linux-hardware.org/?probe=1e1676f874) | Feb 09, 2024 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [f4251d37e2](https://linux-hardware.org/?probe=f4251d37e2) | Feb 09, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JN0... | Notebook    | [20aea10762](https://linux-hardware.org/?probe=20aea10762) | Feb 08, 2024 |
| HONOR         | HYM-WXX                     | Notebook    | [35503217de](https://linux-hardware.org/?probe=35503217de) | Feb 05, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [d731c8db9a](https://linux-hardware.org/?probe=d731c8db9a) | Feb 04, 2024 |
| Xiaomi        | Mi A2 Lite                  | Soc         | [a13944d5f3](https://linux-hardware.org/?probe=a13944d5f3) | Feb 04, 2024 |
| ASRock        | 970M Pro3                   | Desktop     | [cf54a4b360](https://linux-hardware.org/?probe=cf54a4b360) | Feb 02, 2024 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [fddf157b5f](https://linux-hardware.org/?probe=fddf157b5f) | Feb 01, 2024 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [d1a7f0cddb](https://linux-hardware.org/?probe=d1a7f0cddb) | Jan 31, 2024 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [c823432a5a](https://linux-hardware.org/?probe=c823432a5a) | Jan 30, 2024 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [c2ff3b6e2f](https://linux-hardware.org/?probe=c2ff3b6e2f) | Jan 30, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [bc89935fa2](https://linux-hardware.org/?probe=bc89935fa2) | Jan 29, 2024 |
| Apple         | MacBookPro15,1              | Notebook    | [12fb54aa81](https://linux-hardware.org/?probe=12fb54aa81) | Jan 29, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [e78406b431](https://linux-hardware.org/?probe=e78406b431) | Jan 28, 2024 |
| Unknown       | Unknown                     | Notebook    | [5c676b44c6](https://linux-hardware.org/?probe=5c676b44c6) | Jan 27, 2024 |
| Unknown       | Unknown                     | Notebook    | [52522836b8](https://linux-hardware.org/?probe=52522836b8) | Jan 27, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [7423289dfa](https://linux-hardware.org/?probe=7423289dfa) | Jan 26, 2024 |
| Lenovo        | Yoga 6 13ABR8 83B2          | Convertible | [d83af4e1b0](https://linux-hardware.org/?probe=d83af4e1b0) | Jan 26, 2024 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [c9df4c296f](https://linux-hardware.org/?probe=c9df4c296f) | Jan 26, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1500CBA... | Notebook    | [a0b0aa335e](https://linux-hardware.org/?probe=a0b0aa335e) | Jan 25, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1500CBA... | Notebook    | [2add8788ab](https://linux-hardware.org/?probe=2add8788ab) | Jan 25, 2024 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [6c409399d4](https://linux-hardware.org/?probe=6c409399d4) | Jan 25, 2024 |
| Toshiba       | Satellite C850-C5K          | Notebook    | [11b9b2c55a](https://linux-hardware.org/?probe=11b9b2c55a) | Jan 22, 2024 |
| Gigabyte      | B450 GAMING X               | Desktop     | [28be98f6c6](https://linux-hardware.org/?probe=28be98f6c6) | Jan 21, 2024 |
| HONOR         | BMH-WDX9                    | Notebook    | [cc5193ad6b](https://linux-hardware.org/?probe=cc5193ad6b) | Jan 20, 2024 |
| HONOR         | BMH-WDX9                    | Notebook    | [a244cafad7](https://linux-hardware.org/?probe=a244cafad7) | Jan 20, 2024 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [f3ba35a8ef](https://linux-hardware.org/?probe=f3ba35a8ef) | Jan 19, 2024 |
| Biostar       | A320MH                      | Desktop     | [9213e79212](https://linux-hardware.org/?probe=9213e79212) | Jan 19, 2024 |
| ASUSTek       | X541UJ                      | Notebook    | [106a1e0cd4](https://linux-hardware.org/?probe=106a1e0cd4) | Jan 17, 2024 |
| Acer          | Extensa 215-55              | Notebook    | [395b2c99b5](https://linux-hardware.org/?probe=395b2c99b5) | Jan 17, 2024 |
| HONOR         | BMH-WDX9                    | Notebook    | [e793aff68b](https://linux-hardware.org/?probe=e793aff68b) | Jan 16, 2024 |
| Unknown       | X99                         | Desktop     | [7106b28d5f](https://linux-hardware.org/?probe=7106b28d5f) | Jan 16, 2024 |
| Unknown       | X99                         | Desktop     | [c4818c1229](https://linux-hardware.org/?probe=c4818c1229) | Jan 16, 2024 |
| Lenovo        | Yoga 6 13ABR8 83B2          | Convertible | [80798361e5](https://linux-hardware.org/?probe=80798361e5) | Jan 12, 2024 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [9e8a81f355](https://linux-hardware.org/?probe=9e8a81f355) | Jan 10, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [376c519812](https://linux-hardware.org/?probe=376c519812) | Jan 09, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [13523b8324](https://linux-hardware.org/?probe=13523b8324) | Jan 07, 2024 |
| Toshiba       | Satellite C850-C5K          | Notebook    | [55c4519a60](https://linux-hardware.org/?probe=55c4519a60) | Jan 05, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [8ade7f9a3b](https://linux-hardware.org/?probe=8ade7f9a3b) | Jan 04, 2024 |
| Apple         | MacBookPro8,2               | Notebook    | [34fcef3266](https://linux-hardware.org/?probe=34fcef3266) | Dec 31, 2023 |
| HP            | ProBook 6460b               | Notebook    | [45038d4599](https://linux-hardware.org/?probe=45038d4599) | Dec 30, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [d82dad2793](https://linux-hardware.org/?probe=d82dad2793) | Dec 29, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [a4d9a001ff](https://linux-hardware.org/?probe=a4d9a001ff) | Dec 29, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [a353ad122c](https://linux-hardware.org/?probe=a353ad122c) | Dec 28, 2023 |
| HP            | ProBook 6460b               | Notebook    | [4a6a6b9b9d](https://linux-hardware.org/?probe=4a6a6b9b9d) | Dec 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ef5699b685](https://linux-hardware.org/?probe=ef5699b685) | Dec 24, 2023 |
| Dell          | System XPS L702X            | Notebook    | [d69355a342](https://linux-hardware.org/?probe=d69355a342) | Dec 23, 2023 |
| Dell          | 0KWVT8 A03                  | Desktop     | [82a8bc3c6e](https://linux-hardware.org/?probe=82a8bc3c6e) | Dec 21, 2023 |
| ASUSTek       | X541UJ                      | Notebook    | [4aeb75b734](https://linux-hardware.org/?probe=4aeb75b734) | Dec 17, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [b212e62ef7](https://linux-hardware.org/?probe=b212e62ef7) | Dec 17, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [812cd1effd](https://linux-hardware.org/?probe=812cd1effd) | Dec 16, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [314b3b98d7](https://linux-hardware.org/?probe=314b3b98d7) | Dec 16, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [8fc6a74916](https://linux-hardware.org/?probe=8fc6a74916) | Dec 15, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [885e6000e2](https://linux-hardware.org/?probe=885e6000e2) | Dec 12, 2023 |
| ASUSTek       | X550VB                      | Notebook    | [cfc8172838](https://linux-hardware.org/?probe=cfc8172838) | Dec 11, 2023 |
| HP            | ProBook 4535s               | Notebook    | [9005c587a8](https://linux-hardware.org/?probe=9005c587a8) | Dec 10, 2023 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [d31e9bc5eb](https://linux-hardware.org/?probe=d31e9bc5eb) | Dec 10, 2023 |
| HONOR         | HYM-WXX                     | Notebook    | [b008f53987](https://linux-hardware.org/?probe=b008f53987) | Dec 08, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [f87c61387d](https://linux-hardware.org/?probe=f87c61387d) | Dec 06, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [4d14243cb9](https://linux-hardware.org/?probe=4d14243cb9) | Dec 05, 2023 |
| ASUSTek       | X550VC                      | Notebook    | [376ffad1f1](https://linux-hardware.org/?probe=376ffad1f1) | Dec 04, 2023 |
| Lenovo        | ThinkPad T480s 20L7001SM... | Notebook    | [da99e083aa](https://linux-hardware.org/?probe=da99e083aa) | Dec 02, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [deba3c2073](https://linux-hardware.org/?probe=deba3c2073) | Nov 30, 2023 |
| Dell          | 0PGMR1 A00                  | All in one  | [aaca525c1a](https://linux-hardware.org/?probe=aaca525c1a) | Nov 28, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [184a3ca616](https://linux-hardware.org/?probe=184a3ca616) | Nov 28, 2023 |
| MSI           | H61M-P31/W8                 | Desktop     | [b74cd41faf](https://linux-hardware.org/?probe=b74cd41faf) | Nov 26, 2023 |
| Gigabyte      | B550M S2H                   | Desktop     | [7084bb6ef8](https://linux-hardware.org/?probe=7084bb6ef8) | Nov 26, 2023 |
| HP            | ProBook 6460b               | Notebook    | [d489496b9f](https://linux-hardware.org/?probe=d489496b9f) | Nov 26, 2023 |
| Biostar       | H61MLV2                     | Desktop     | [1e2b4c3878](https://linux-hardware.org/?probe=1e2b4c3878) | Nov 26, 2023 |
| Unknown       | Unknown                     | Notebook    | [2b84a63677](https://linux-hardware.org/?probe=2b84a63677) | Nov 26, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [1bb4c56d2b](https://linux-hardware.org/?probe=1bb4c56d2b) | Nov 24, 2023 |
| HP            | ProBook 6460b               | Notebook    | [0d13c42c84](https://linux-hardware.org/?probe=0d13c42c84) | Nov 21, 2023 |
| Valve         | Jupiter                     | Notebook    | [93c68a0d33](https://linux-hardware.org/?probe=93c68a0d33) | Nov 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [743037d313](https://linux-hardware.org/?probe=743037d313) | Nov 18, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [cd775f0d29](https://linux-hardware.org/?probe=cd775f0d29) | Nov 18, 2023 |
| Gigabyte      | P85-D3                      | Desktop     | [a6742c43a4](https://linux-hardware.org/?probe=a6742c43a4) | Nov 16, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [6461e4f7af](https://linux-hardware.org/?probe=6461e4f7af) | Nov 16, 2023 |
| HP            | ProBook 6460b               | Notebook    | [b0795caa4c](https://linux-hardware.org/?probe=b0795caa4c) | Nov 15, 2023 |
| HP            | ProBook 6570b               | Notebook    | [06cd45bab5](https://linux-hardware.org/?probe=06cd45bab5) | Nov 15, 2023 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [1cffd5036c](https://linux-hardware.org/?probe=1cffd5036c) | Nov 14, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [4d8ebb0232](https://linux-hardware.org/?probe=4d8ebb0232) | Nov 13, 2023 |
| HONOR         | NBR-WAX9                    | Notebook    | [c648b2a80e](https://linux-hardware.org/?probe=c648b2a80e) | Nov 13, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [c34342b820](https://linux-hardware.org/?probe=c34342b820) | Nov 10, 2023 |
| Chuwi         | GemiBook                    | Notebook    | [5fb8105768](https://linux-hardware.org/?probe=5fb8105768) | Nov 10, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [d0570de821](https://linux-hardware.org/?probe=d0570de821) | Nov 06, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [29f3c0c25f](https://linux-hardware.org/?probe=29f3c0c25f) | Nov 06, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [685b1b18eb](https://linux-hardware.org/?probe=685b1b18eb) | Nov 01, 2023 |
| Khadas        | VIM3                        | Soc         | [701bf2eba1](https://linux-hardware.org/?probe=701bf2eba1) | Oct 31, 2023 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [c35ab1031d](https://linux-hardware.org/?probe=c35ab1031d) | Oct 30, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [856d9c4a75](https://linux-hardware.org/?probe=856d9c4a75) | Oct 28, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [265d52a042](https://linux-hardware.org/?probe=265d52a042) | Oct 28, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [ee5373bbe1](https://linux-hardware.org/?probe=ee5373bbe1) | Oct 28, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [e8432e79c8](https://linux-hardware.org/?probe=e8432e79c8) | Oct 26, 2023 |
| Haier         | U1520SD                     | Notebook    | [3de6c48f15](https://linux-hardware.org/?probe=3de6c48f15) | Oct 26, 2023 |
| Haier         | U1520SD                     | Notebook    | [25229c3d32](https://linux-hardware.org/?probe=25229c3d32) | Oct 25, 2023 |
| Gigabyte      | AERO 17 XE5                 | Notebook    | [47d1cb500e](https://linux-hardware.org/?probe=47d1cb500e) | Oct 25, 2023 |
| ASUSTek       | Zenbook UX3402ZA            | Notebook    | [f321493adb](https://linux-hardware.org/?probe=f321493adb) | Oct 25, 2023 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [a3a2c0b74b](https://linux-hardware.org/?probe=a3a2c0b74b) | Oct 25, 2023 |
| Timi          | TM1701                      | Notebook    | [13801c83a2](https://linux-hardware.org/?probe=13801c83a2) | Oct 25, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [bd850cfed3](https://linux-hardware.org/?probe=bd850cfed3) | Oct 24, 2023 |
| Dell          | Latitude D830               | Notebook    | [53cbc541d2](https://linux-hardware.org/?probe=53cbc541d2) | Oct 20, 2023 |
| Lenovo        | IdeaPad 330S-15IKB GTX10... | Notebook    | [36c49585ba](https://linux-hardware.org/?probe=36c49585ba) | Oct 20, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [b11aafb048](https://linux-hardware.org/?probe=b11aafb048) | Oct 20, 2023 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [6827d26220](https://linux-hardware.org/?probe=6827d26220) | Oct 17, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [70c2d315e0](https://linux-hardware.org/?probe=70c2d315e0) | Oct 16, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [cf096a11b6](https://linux-hardware.org/?probe=cf096a11b6) | Oct 12, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [908a750a93](https://linux-hardware.org/?probe=908a750a93) | Oct 10, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [10b2d6465f](https://linux-hardware.org/?probe=10b2d6465f) | Oct 10, 2023 |
| HP            | ProBook 450 G7              | Notebook    | [01bfe733f2](https://linux-hardware.org/?probe=01bfe733f2) | Oct 10, 2023 |
| HP            | 650                         | Notebook    | [1339361633](https://linux-hardware.org/?probe=1339361633) | Oct 09, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [c237b78f41](https://linux-hardware.org/?probe=c237b78f41) | Oct 08, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [76449d7977](https://linux-hardware.org/?probe=76449d7977) | Oct 06, 2023 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [1a20748a43](https://linux-hardware.org/?probe=1a20748a43) | Oct 06, 2023 |
| HP            | EliteBook 1050 G1           | Notebook    | [d5d3dd5136](https://linux-hardware.org/?probe=d5d3dd5136) | Oct 05, 2023 |
| Biostar       | H510MHP                     | Desktop     | [f562c8f7d7](https://linux-hardware.org/?probe=f562c8f7d7) | Oct 05, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [46e4809bfe](https://linux-hardware.org/?probe=46e4809bfe) | Oct 04, 2023 |
| ASRock        | B365 Pro4                   | Desktop     | [8e9fff1e35](https://linux-hardware.org/?probe=8e9fff1e35) | Oct 04, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [db7fa034a7](https://linux-hardware.org/?probe=db7fa034a7) | Oct 03, 2023 |
| HP            | 650                         | Notebook    | [f652e189f9](https://linux-hardware.org/?probe=f652e189f9) | Oct 03, 2023 |
| MSI           | 760GM-P33                   | Desktop     | [5967be8309](https://linux-hardware.org/?probe=5967be8309) | Oct 03, 2023 |
| HP            | Compaq 610                  | Notebook    | [9570db13af](https://linux-hardware.org/?probe=9570db13af) | Oct 01, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [55b44bb456](https://linux-hardware.org/?probe=55b44bb456) | Sep 29, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [4375a551e1](https://linux-hardware.org/?probe=4375a551e1) | Sep 25, 2023 |
| Google        | Eve                         | Convertible | [b3c890ec7a](https://linux-hardware.org/?probe=b3c890ec7a) | Sep 24, 2023 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [57d5f67adf](https://linux-hardware.org/?probe=57d5f67adf) | Sep 24, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [72940bf53e](https://linux-hardware.org/?probe=72940bf53e) | Sep 24, 2023 |
| Google        | Eve                         | Convertible | [eccabb6bc2](https://linux-hardware.org/?probe=eccabb6bc2) | Sep 24, 2023 |
| Olimex        | A20-OLinuXino-LIME2         | Soc         | [b2c0e79757](https://linux-hardware.org/?probe=b2c0e79757) | Sep 22, 2023 |
| MSI           | 760GM-P33                   | Desktop     | [6dfb722e45](https://linux-hardware.org/?probe=6dfb722e45) | Sep 22, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [2e715ca7b2](https://linux-hardware.org/?probe=2e715ca7b2) | Sep 22, 2023 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [63bebc9690](https://linux-hardware.org/?probe=63bebc9690) | Sep 20, 2023 |
| ASUSTek       | K72Dr                       | Notebook    | [46edd6eb72](https://linux-hardware.org/?probe=46edd6eb72) | Sep 15, 2023 |
| ASUSTek       | X502CA                      | Notebook    | [8d0117a5f3](https://linux-hardware.org/?probe=8d0117a5f3) | Sep 13, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [418eee8ea7](https://linux-hardware.org/?probe=418eee8ea7) | Sep 13, 2023 |
| MSI           | G31TM-P21                   | Desktop     | [cdeced49b1](https://linux-hardware.org/?probe=cdeced49b1) | Sep 12, 2023 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [f588051436](https://linux-hardware.org/?probe=f588051436) | Sep 11, 2023 |
| MSI           | Stealth GS77 12UGS          | Notebook    | [c83c0f03aa](https://linux-hardware.org/?probe=c83c0f03aa) | Sep 11, 2023 |
| Dell          | Latitude 3410               | Notebook    | [8717619604](https://linux-hardware.org/?probe=8717619604) | Sep 11, 2023 |
| ECS           | A960M-M3                    | Desktop     | [70ee5683a4](https://linux-hardware.org/?probe=70ee5683a4) | Sep 11, 2023 |
| Dell          | Latitude 3410               | Notebook    | [c1c98adb51](https://linux-hardware.org/?probe=c1c98adb51) | Sep 10, 2023 |
| HP            | ProBook 470 G3              | Notebook    | [f096164a16](https://linux-hardware.org/?probe=f096164a16) | Sep 08, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [855f5edce0](https://linux-hardware.org/?probe=855f5edce0) | Sep 08, 2023 |
| ASUSTek       | P8H61/USB3                  | Desktop     | [ecf1a70c5d](https://linux-hardware.org/?probe=ecf1a70c5d) | Sep 08, 2023 |
| ASRock        | H510M-HDV/M.2               | Desktop     | [63dae39236](https://linux-hardware.org/?probe=63dae39236) | Sep 08, 2023 |
| ASRock        | H510M-HDV/M.2               | Desktop     | [3fb594ab96](https://linux-hardware.org/?probe=3fb594ab96) | Sep 07, 2023 |
| Acer          | Aspire V5-531               | Notebook    | [f2df6b2c70](https://linux-hardware.org/?probe=f2df6b2c70) | Sep 07, 2023 |
| Acer          | Aspire V5-531               | Notebook    | [e39cb4e3e6](https://linux-hardware.org/?probe=e39cb4e3e6) | Sep 07, 2023 |
| Acer          | Aspire V5-531               | Notebook    | [63fd300645](https://linux-hardware.org/?probe=63fd300645) | Sep 07, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [1756563167](https://linux-hardware.org/?probe=1756563167) | Sep 06, 2023 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [783815f79f](https://linux-hardware.org/?probe=783815f79f) | Sep 06, 2023 |
| ASUSTek       | X502CA                      | Notebook    | [d630819b59](https://linux-hardware.org/?probe=d630819b59) | Sep 05, 2023 |
| Gigabyte      | P55M-UD4                    | Desktop     | [d04a4aef90](https://linux-hardware.org/?probe=d04a4aef90) | Sep 03, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [e04761c470](https://linux-hardware.org/?probe=e04761c470) | Sep 03, 2023 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [d714ef63c2](https://linux-hardware.org/?probe=d714ef63c2) | Sep 03, 2023 |
| ASRock        | H570 Steel Legend           | Desktop     | [192d8ebfa3](https://linux-hardware.org/?probe=192d8ebfa3) | Sep 02, 2023 |
| HP            | ProBook 470 G3              | Notebook    | [f6996b2905](https://linux-hardware.org/?probe=f6996b2905) | Sep 02, 2023 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [3080550241](https://linux-hardware.org/?probe=3080550241) | Sep 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [4e753f77c7](https://linux-hardware.org/?probe=4e753f77c7) | Sep 01, 2023 |
| ASUSTek       | X502CA                      | Notebook    | [04492867e2](https://linux-hardware.org/?probe=04492867e2) | Aug 31, 2023 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [e3eb4b9ef5](https://linux-hardware.org/?probe=e3eb4b9ef5) | Aug 31, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [f8906dfb9c](https://linux-hardware.org/?probe=f8906dfb9c) | Aug 28, 2023 |
| ASRock        | B450M-HDV                   | Desktop     | [8ed8031a41](https://linux-hardware.org/?probe=8ed8031a41) | Aug 28, 2023 |
| ASRock        | B450M-HDV                   | Desktop     | [3d2effa8c5](https://linux-hardware.org/?probe=3d2effa8c5) | Aug 27, 2023 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [c326205a9b](https://linux-hardware.org/?probe=c326205a9b) | Aug 27, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [864a9d9f37](https://linux-hardware.org/?probe=864a9d9f37) | Aug 27, 2023 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [1538d66b38](https://linux-hardware.org/?probe=1538d66b38) | Aug 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [1a9c135840](https://linux-hardware.org/?probe=1a9c135840) | Aug 24, 2023 |
| ASUSTek       | P8H61/USB3                  | Desktop     | [149cb27e46](https://linux-hardware.org/?probe=149cb27e46) | Aug 18, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [dd9b3b469e](https://linux-hardware.org/?probe=dd9b3b469e) | Aug 15, 2023 |
| MSI           | 760GM-P33                   | Desktop     | [878209b83a](https://linux-hardware.org/?probe=878209b83a) | Aug 13, 2023 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [41831db130](https://linux-hardware.org/?probe=41831db130) | Aug 13, 2023 |
| HONOR         | HYM-WXX                     | Notebook    | [6f5e2be121](https://linux-hardware.org/?probe=6f5e2be121) | Aug 08, 2023 |
| HUAWEI        | KPRC-WX0                    | Notebook    | [f84c568d4b](https://linux-hardware.org/?probe=f84c568d4b) | Aug 07, 2023 |
| HP            | ProBook 450 G5              | Notebook    | [0482630783](https://linux-hardware.org/?probe=0482630783) | Aug 05, 2023 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [2a54f1c8ce](https://linux-hardware.org/?probe=2a54f1c8ce) | Aug 04, 2023 |
| Samsung       | 305E4Z/305E5Z/305E7Z        | Notebook    | [a9232da3e4](https://linux-hardware.org/?probe=a9232da3e4) | Jul 31, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [095890a440](https://linux-hardware.org/?probe=095890a440) | Jul 31, 2023 |
| ASUSTek       | GL503VD                     | Notebook    | [4c3516813b](https://linux-hardware.org/?probe=4c3516813b) | Jul 28, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [792e9db762](https://linux-hardware.org/?probe=792e9db762) | Jul 27, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [44647ce47e](https://linux-hardware.org/?probe=44647ce47e) | Jul 26, 2023 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [cf57b5785a](https://linux-hardware.org/?probe=cf57b5785a) | Jul 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ca354dd42d](https://linux-hardware.org/?probe=ca354dd42d) | Jul 23, 2023 |
| HP            | ProBook 4545s               | Notebook    | [cf43675118](https://linux-hardware.org/?probe=cf43675118) | Jul 20, 2023 |
| Unknown       | Unknown                     | Notebook    | [7e6c1d1018](https://linux-hardware.org/?probe=7e6c1d1018) | Jul 19, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [a646f5d0fb](https://linux-hardware.org/?probe=a646f5d0fb) | Jul 19, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [6623b71de2](https://linux-hardware.org/?probe=6623b71de2) | Jul 19, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [ab43e6b8ef](https://linux-hardware.org/?probe=ab43e6b8ef) | Jul 16, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [6b52cef555](https://linux-hardware.org/?probe=6b52cef555) | Jul 16, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [584f2a2ac4](https://linux-hardware.org/?probe=584f2a2ac4) | Jul 13, 2023 |
| MSI           | G31TM-P21                   | Desktop     | [6456f7b16f](https://linux-hardware.org/?probe=6456f7b16f) | Jul 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e9e376fb10](https://linux-hardware.org/?probe=e9e376fb10) | Jul 09, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [33a8b4ab02](https://linux-hardware.org/?probe=33a8b4ab02) | Jul 08, 2023 |
| Valve         | Jupiter                     | Notebook    | [dfb0bd07f1](https://linux-hardware.org/?probe=dfb0bd07f1) | Jul 05, 2023 |
| Lenovo        | IdeaPad 3 17ALC6 82KV       | Notebook    | [d33df8d1a0](https://linux-hardware.org/?probe=d33df8d1a0) | Jul 03, 2023 |
| ASUSTek       | ROG STRIX Z490-G GAMING     | Desktop     | [5b11b41272](https://linux-hardware.org/?probe=5b11b41272) | Jul 02, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [1e4c2cf905](https://linux-hardware.org/?probe=1e4c2cf905) | Jun 30, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [a33602b335](https://linux-hardware.org/?probe=a33602b335) | Jun 29, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [37239831de](https://linux-hardware.org/?probe=37239831de) | Jun 24, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [b4c9b0d1f7](https://linux-hardware.org/?probe=b4c9b0d1f7) | Jun 24, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [a5f281a10e](https://linux-hardware.org/?probe=a5f281a10e) | Jun 23, 2023 |
| HP            | 255 G1                      | Notebook    | [f09174c096](https://linux-hardware.org/?probe=f09174c096) | Jun 21, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [e26b3e6d58](https://linux-hardware.org/?probe=e26b3e6d58) | Jun 21, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [0b6bb0a043](https://linux-hardware.org/?probe=0b6bb0a043) | Jun 21, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [948225d98e](https://linux-hardware.org/?probe=948225d98e) | Jun 18, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [50626f77d7](https://linux-hardware.org/?probe=50626f77d7) | Jun 18, 2023 |
| ASUSTek       | X551CAP                     | Notebook    | [9066d9bad2](https://linux-hardware.org/?probe=9066d9bad2) | Jun 17, 2023 |
| Sony          | SVF1521L1RB                 | Notebook    | [b0dfbb64d0](https://linux-hardware.org/?probe=b0dfbb64d0) | Jun 17, 2023 |
| Gigabyte      | GA-MA770-US3                | Desktop     | [c7460aff4f](https://linux-hardware.org/?probe=c7460aff4f) | Jun 16, 2023 |
| Dell          | Inspiron 15-3573            | Notebook    | [129574e8dc](https://linux-hardware.org/?probe=129574e8dc) | Jun 14, 2023 |
| HP            | 255 G1                      | Notebook    | [a8c4597ccd](https://linux-hardware.org/?probe=a8c4597ccd) | Jun 14, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [f578df0eb9](https://linux-hardware.org/?probe=f578df0eb9) | Jun 13, 2023 |
| Gigabyte      | GA-MA770-US3                | Desktop     | [704cc1c02b](https://linux-hardware.org/?probe=704cc1c02b) | Jun 10, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [c8ca6e8787](https://linux-hardware.org/?probe=c8ca6e8787) | Jun 05, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [320e5bee32](https://linux-hardware.org/?probe=320e5bee32) | Jun 04, 2023 |
| ASUSTek       | P8H61/USB3                  | Desktop     | [d93dbf6db3](https://linux-hardware.org/?probe=d93dbf6db3) | Jun 01, 2023 |
| ASUSTek       | P8H61/USB3                  | Desktop     | [16c7ca187a](https://linux-hardware.org/?probe=16c7ca187a) | Jun 01, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [1e23f3e627](https://linux-hardware.org/?probe=1e23f3e627) | May 28, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [960ddf4eaf](https://linux-hardware.org/?probe=960ddf4eaf) | May 28, 2023 |
| Toshiba       | Satellite C850-C5K          | Notebook    | [481789fa1e](https://linux-hardware.org/?probe=481789fa1e) | May 28, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [5162ff793e](https://linux-hardware.org/?probe=5162ff793e) | May 27, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [8962578738](https://linux-hardware.org/?probe=8962578738) | May 26, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [eb644c96f3](https://linux-hardware.org/?probe=eb644c96f3) | May 23, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [5762961675](https://linux-hardware.org/?probe=5762961675) | May 23, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [85f2338e54](https://linux-hardware.org/?probe=85f2338e54) | May 22, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [94c7ddea69](https://linux-hardware.org/?probe=94c7ddea69) | May 21, 2023 |
| ASRock        | H61M-HVGS                   | Desktop     | [653f6e9a8e](https://linux-hardware.org/?probe=653f6e9a8e) | May 20, 2023 |
| Gigabyte      | B550M S2H                   | Desktop     | [04dac52364](https://linux-hardware.org/?probe=04dac52364) | May 19, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [c795e3e6ac](https://linux-hardware.org/?probe=c795e3e6ac) | May 18, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [b3eaf738e4](https://linux-hardware.org/?probe=b3eaf738e4) | May 18, 2023 |
| MSI           | GE72 7RE                    | Notebook    | [15a31e188f](https://linux-hardware.org/?probe=15a31e188f) | May 18, 2023 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [058907d9d3](https://linux-hardware.org/?probe=058907d9d3) | May 18, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [6e519b78e9](https://linux-hardware.org/?probe=6e519b78e9) | May 17, 2023 |
| Intel         | SHARKBAY                    | Desktop     | [03b576ccc8](https://linux-hardware.org/?probe=03b576ccc8) | May 16, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [5a28a0c505](https://linux-hardware.org/?probe=5a28a0c505) | May 15, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [3de097b441](https://linux-hardware.org/?probe=3de097b441) | May 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [9201edcfb8](https://linux-hardware.org/?probe=9201edcfb8) | May 12, 2023 |
| ASUSTek       | P5B-VM SE                   | Desktop     | [bd1c748eed](https://linux-hardware.org/?probe=bd1c748eed) | May 12, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [32b3c782ff](https://linux-hardware.org/?probe=32b3c782ff) | May 11, 2023 |
| Dell          | 0Y958C A00                  | Desktop     | [fb1b987ad5](https://linux-hardware.org/?probe=fb1b987ad5) | May 10, 2023 |
| Gigabyte      | GA-MA770-US3                | Desktop     | [169b0a5bc0](https://linux-hardware.org/?probe=169b0a5bc0) | May 07, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [fe4b074a5c](https://linux-hardware.org/?probe=fe4b074a5c) | May 06, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [e0357a19f3](https://linux-hardware.org/?probe=e0357a19f3) | May 05, 2023 |
| Acer          | Swift SF114-32              | Notebook    | [19a489c33e](https://linux-hardware.org/?probe=19a489c33e) | May 03, 2023 |
| Gigabyte      | B75M-D2V                    | Desktop     | [5a21b5acb8](https://linux-hardware.org/?probe=5a21b5acb8) | May 02, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [fcd7a6a42b](https://linux-hardware.org/?probe=fcd7a6a42b) | Apr 30, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [c36b7b72de](https://linux-hardware.org/?probe=c36b7b72de) | Apr 29, 2023 |
| HP            | Compaq Presario CQ70        | Notebook    | [b4055572ee](https://linux-hardware.org/?probe=b4055572ee) | Apr 28, 2023 |
| ASUSTek       | K53BR                       | Notebook    | [27a8681404](https://linux-hardware.org/?probe=27a8681404) | Apr 28, 2023 |
| ASRock        | H510M-HDV/M.2               | Desktop     | [c11c9964fa](https://linux-hardware.org/?probe=c11c9964fa) | Apr 27, 2023 |
| HP            | ProBook x360 435 G8 Note... | Convertible | [8bca3fa04b](https://linux-hardware.org/?probe=8bca3fa04b) | Apr 25, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [699adff825](https://linux-hardware.org/?probe=699adff825) | Apr 24, 2023 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [59ad89854c](https://linux-hardware.org/?probe=59ad89854c) | Apr 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [ce5e9aad85](https://linux-hardware.org/?probe=ce5e9aad85) | Apr 22, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [94bd5fe556](https://linux-hardware.org/?probe=94bd5fe556) | Apr 21, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [05321d1ddd](https://linux-hardware.org/?probe=05321d1ddd) | Apr 20, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [50c44b15eb](https://linux-hardware.org/?probe=50c44b15eb) | Apr 20, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [9cb44b75f5](https://linux-hardware.org/?probe=9cb44b75f5) | Apr 20, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [9f5fa03bfd](https://linux-hardware.org/?probe=9f5fa03bfd) | Apr 19, 2023 |
| Lenovo        | G780 20138                  | Notebook    | [32360109fa](https://linux-hardware.org/?probe=32360109fa) | Apr 19, 2023 |
| Samsung       | NC210/NC110                 | Notebook    | [f87a34e474](https://linux-hardware.org/?probe=f87a34e474) | Apr 19, 2023 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [84dbb8ae74](https://linux-hardware.org/?probe=84dbb8ae74) | Apr 19, 2023 |
| Samsung       | NC210/NC110                 | Notebook    | [9cacd6f238](https://linux-hardware.org/?probe=9cacd6f238) | Apr 19, 2023 |
| TECNO         | MEGABOOK T1                 | Notebook    | [733d7d5584](https://linux-hardware.org/?probe=733d7d5584) | Apr 18, 2023 |
| ASUSTek       | X75VCP                      | Notebook    | [a02f8565dd](https://linux-hardware.org/?probe=a02f8565dd) | Apr 14, 2023 |
| ASUSTek       | X75VCP                      | Notebook    | [5ecb1bb650](https://linux-hardware.org/?probe=5ecb1bb650) | Apr 13, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [60f7db51fa](https://linux-hardware.org/?probe=60f7db51fa) | Apr 13, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [e9708d65e9](https://linux-hardware.org/?probe=e9708d65e9) | Apr 13, 2023 |
| Fujitsu       | LIFEBOOK U745               | Notebook    | [82bfc450e9](https://linux-hardware.org/?probe=82bfc450e9) | Apr 12, 2023 |
| Dell          | Inspiron 15-3552            | Notebook    | [5c23d1d7f7](https://linux-hardware.org/?probe=5c23d1d7f7) | Apr 08, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [be2a3d30f2](https://linux-hardware.org/?probe=be2a3d30f2) | Apr 08, 2023 |
| ASRock        | N68C-GS4 FX                 | Desktop     | [71c25d2dce](https://linux-hardware.org/?probe=71c25d2dce) | Apr 07, 2023 |
| MSI           | X79A-GD45 Plus              | Desktop     | [ca3f0771ce](https://linux-hardware.org/?probe=ca3f0771ce) | Apr 05, 2023 |
| ASUSTek       | P5G41T-M LX2/GB/LPT         | Desktop     | [24ac3864d2](https://linux-hardware.org/?probe=24ac3864d2) | Apr 04, 2023 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [1789a17694](https://linux-hardware.org/?probe=1789a17694) | Apr 03, 2023 |
| Gigabyte      | B360M H                     | Desktop     | [cc5feeb3eb](https://linux-hardware.org/?probe=cc5feeb3eb) | Apr 03, 2023 |
| Biostar       | B365MHC                     | Desktop     | [95107f0e65](https://linux-hardware.org/?probe=95107f0e65) | Apr 02, 2023 |
| Apple         | MacBookAir4,2               | Notebook    | [6dafdf20a5](https://linux-hardware.org/?probe=6dafdf20a5) | Apr 02, 2023 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [f811a203a0](https://linux-hardware.org/?probe=f811a203a0) | Apr 02, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [f278e6aad0](https://linux-hardware.org/?probe=f278e6aad0) | Apr 01, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [b56e2a41ed](https://linux-hardware.org/?probe=b56e2a41ed) | Mar 31, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [3399c2f210](https://linux-hardware.org/?probe=3399c2f210) | Mar 31, 2023 |
| Toshiba       | Satellite C850-C5K          | Notebook    | [8fc7451def](https://linux-hardware.org/?probe=8fc7451def) | Mar 30, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [51f6d77f50](https://linux-hardware.org/?probe=51f6d77f50) | Mar 30, 2023 |
| Gigabyte      | GA-A75-UD4H                 | Desktop     | [e5433e75fb](https://linux-hardware.org/?probe=e5433e75fb) | Mar 29, 2023 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [06ad8e8099](https://linux-hardware.org/?probe=06ad8e8099) | Mar 29, 2023 |
| EPoX Compu... | nForce3 DDR: 8KDA7I Seri... | Desktop     | [38e3c2378c](https://linux-hardware.org/?probe=38e3c2378c) | Mar 29, 2023 |
| Dell          | System XPS L702X            | Notebook    | [2c8aed8334](https://linux-hardware.org/?probe=2c8aed8334) | Mar 29, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [77e01c9b12](https://linux-hardware.org/?probe=77e01c9b12) | Mar 29, 2023 |
| HP            | Notebook                    | Notebook    | [f18d14ac70](https://linux-hardware.org/?probe=f18d14ac70) | Mar 28, 2023 |
| HP            | 250 G1                      | Notebook    | [a19b3136b7](https://linux-hardware.org/?probe=a19b3136b7) | Mar 26, 2023 |
| Lenovo        | 3000 G530 4151/200          | Notebook    | [4c0751aa89](https://linux-hardware.org/?probe=4c0751aa89) | Mar 26, 2023 |
| HP            | Pavilion dv7                | Notebook    | [6ae381093b](https://linux-hardware.org/?probe=6ae381093b) | Mar 26, 2023 |
| MSI           | X79A-GD45 Plus              | Desktop     | [0a5446e862](https://linux-hardware.org/?probe=0a5446e862) | Mar 26, 2023 |
| Getac         | B300-H                      | Notebook    | [28a9b0b0c7](https://linux-hardware.org/?probe=28a9b0b0c7) | Mar 25, 2023 |
| HP            | ProBook 450 G5              | Notebook    | [c4b7067187](https://linux-hardware.org/?probe=c4b7067187) | Mar 24, 2023 |
| Iskratel, ... | IN6011AX                    | Desktop     | [037350830e](https://linux-hardware.org/?probe=037350830e) | Mar 23, 2023 |
| ASRock        | H61M-HVGS                   | Desktop     | [8023b22765](https://linux-hardware.org/?probe=8023b22765) | Mar 23, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [ea18262536](https://linux-hardware.org/?probe=ea18262536) | Mar 22, 2023 |
| ASRock        | H61M-HVGS                   | Desktop     | [5e9cf8fb44](https://linux-hardware.org/?probe=5e9cf8fb44) | Mar 22, 2023 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [7d8950b25b](https://linux-hardware.org/?probe=7d8950b25b) | Mar 21, 2023 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [c58012d73d](https://linux-hardware.org/?probe=c58012d73d) | Mar 21, 2023 |
| HP            | Pavilion dv6                | Notebook    | [43940eb778](https://linux-hardware.org/?probe=43940eb778) | Mar 20, 2023 |
| HP            | Pavilion dv7                | Notebook    | [d42628a0e9](https://linux-hardware.org/?probe=d42628a0e9) | Mar 19, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [5033dda127](https://linux-hardware.org/?probe=5033dda127) | Mar 19, 2023 |
| ASUSTek       | X555LB                      | Notebook    | [a00be2eabe](https://linux-hardware.org/?probe=a00be2eabe) | Mar 17, 2023 |
| HP            | Pavilion dv6                | Notebook    | [b5746d500d](https://linux-hardware.org/?probe=b5746d500d) | Mar 13, 2023 |
| Sony          | VPCEB3S1R                   | Notebook    | [0e89d9279d](https://linux-hardware.org/?probe=0e89d9279d) | Mar 12, 2023 |
| Sony          | VPCEB3S1R                   | Notebook    | [8541575b10](https://linux-hardware.org/?probe=8541575b10) | Mar 12, 2023 |
| Intel         | JSL MRD                     | Desktop     | [28832d0a36](https://linux-hardware.org/?probe=28832d0a36) | Mar 11, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [249f986099](https://linux-hardware.org/?probe=249f986099) | Mar 09, 2023 |
| HP            | Compaq 610                  | Notebook    | [3f5ffc0582](https://linux-hardware.org/?probe=3f5ffc0582) | Mar 08, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [48dc89b146](https://linux-hardware.org/?probe=48dc89b146) | Mar 07, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [546d7b3f27](https://linux-hardware.org/?probe=546d7b3f27) | Mar 07, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [3fb642aac7](https://linux-hardware.org/?probe=3fb642aac7) | Mar 06, 2023 |
| Acer          | Aspire 5739G                | Notebook    | [efd6fd1985](https://linux-hardware.org/?probe=efd6fd1985) | Mar 06, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [e682158c7f](https://linux-hardware.org/?probe=e682158c7f) | Mar 06, 2023 |
| Gigabyte      | B450M S2H V2                | Desktop     | [a2242be67c](https://linux-hardware.org/?probe=a2242be67c) | Mar 05, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [268e27cc20](https://linux-hardware.org/?probe=268e27cc20) | Mar 04, 2023 |
| Notebook      | NS5x_NS7xPU                 | Notebook    | [55ca2f6ac5](https://linux-hardware.org/?probe=55ca2f6ac5) | Mar 03, 2023 |
| Lenovo        | G550 20023                  | Notebook    | [e8325b5ff1](https://linux-hardware.org/?probe=e8325b5ff1) | Mar 03, 2023 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [9cd0a2ea25](https://linux-hardware.org/?probe=9cd0a2ea25) | Mar 01, 2023 |
| ASUSTek       | UX31A                       | Notebook    | [56654a2659](https://linux-hardware.org/?probe=56654a2659) | Feb 27, 2023 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [630c0e41b1](https://linux-hardware.org/?probe=630c0e41b1) | Feb 25, 2023 |
| Toshiba       | Satellite L300              | Notebook    | [c1b163bee0](https://linux-hardware.org/?probe=c1b163bee0) | Feb 25, 2023 |
| Toshiba       | Satellite L300              | Notebook    | [76e5b62eec](https://linux-hardware.org/?probe=76e5b62eec) | Feb 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c85bd630f0](https://linux-hardware.org/?probe=c85bd630f0) | Feb 25, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [08d9bfbb41](https://linux-hardware.org/?probe=08d9bfbb41) | Feb 24, 2023 |
| Samsung       | RV413/RV513                 | Notebook    | [5b524ddbb0](https://linux-hardware.org/?probe=5b524ddbb0) | Feb 23, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [bb2bef71e0](https://linux-hardware.org/?probe=bb2bef71e0) | Feb 23, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [9b00bf7704](https://linux-hardware.org/?probe=9b00bf7704) | Feb 22, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [dc6a6f7872](https://linux-hardware.org/?probe=dc6a6f7872) | Feb 21, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [788044d53c](https://linux-hardware.org/?probe=788044d53c) | Feb 20, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [d8abf7361b](https://linux-hardware.org/?probe=d8abf7361b) | Feb 20, 2023 |
| Partner       | S1-J1900                    | Desktop     | [0dd4327553](https://linux-hardware.org/?probe=0dd4327553) | Feb 19, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [faa600d8e5](https://linux-hardware.org/?probe=faa600d8e5) | Feb 19, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [dfa8cae135](https://linux-hardware.org/?probe=dfa8cae135) | Feb 17, 2023 |
| ASUSTek       | X540YA                      | Notebook    | [3faff8d320](https://linux-hardware.org/?probe=3faff8d320) | Feb 17, 2023 |
| ASUSTek       | P5GD1 PRO                   | Desktop     | [043021ca86](https://linux-hardware.org/?probe=043021ca86) | Feb 15, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [44e18a0f72](https://linux-hardware.org/?probe=44e18a0f72) | Feb 15, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [92a9452070](https://linux-hardware.org/?probe=92a9452070) | Feb 15, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [6569b3d50d](https://linux-hardware.org/?probe=6569b3d50d) | Feb 14, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [0da8e9ac4c](https://linux-hardware.org/?probe=0da8e9ac4c) | Feb 14, 2023 |
| Intel         | NUC7i3BNB J22859-316        | Mini pc     | [fc5fbe9d48](https://linux-hardware.org/?probe=fc5fbe9d48) | Feb 13, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [59c1fdfad6](https://linux-hardware.org/?probe=59c1fdfad6) | Feb 12, 2023 |
| HP            | Compaq Presario CQ70        | Notebook    | [5644272d9e](https://linux-hardware.org/?probe=5644272d9e) | Feb 09, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [1746b40d04](https://linux-hardware.org/?probe=1746b40d04) | Feb 09, 2023 |
| Acer          | Aspire E5-572G              | Notebook    | [f44e9ce856](https://linux-hardware.org/?probe=f44e9ce856) | Feb 08, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [87b269febc](https://linux-hardware.org/?probe=87b269febc) | Feb 08, 2023 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | Notebook    | [a1549a7701](https://linux-hardware.org/?probe=a1549a7701) | Feb 07, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [c3909421c3](https://linux-hardware.org/?probe=c3909421c3) | Feb 07, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [f3ec6a2ed1](https://linux-hardware.org/?probe=f3ec6a2ed1) | Feb 06, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [4de96841bf](https://linux-hardware.org/?probe=4de96841bf) | Feb 03, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [9dcc7bb41d](https://linux-hardware.org/?probe=9dcc7bb41d) | Feb 03, 2023 |
| Intel         | SKYBAY                      | Desktop     | [7f8e95e496](https://linux-hardware.org/?probe=7f8e95e496) | Feb 02, 2023 |
| Intel         | SKYBAY                      | Desktop     | [a75cb78ad9](https://linux-hardware.org/?probe=a75cb78ad9) | Feb 02, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [142f5fcb2d](https://linux-hardware.org/?probe=142f5fcb2d) | Feb 01, 2023 |
| ASUSTek       | Z170M-E D3                  | Desktop     | [2b466d1b19](https://linux-hardware.org/?probe=2b466d1b19) | Jan 29, 2023 |
| Dell          | Inspiron 3581               | Notebook    | [8c8db10ac2](https://linux-hardware.org/?probe=8c8db10ac2) | Jan 28, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [6f94175d8c](https://linux-hardware.org/?probe=6f94175d8c) | Jan 28, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [add8440e16](https://linux-hardware.org/?probe=add8440e16) | Jan 27, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [f4e06ff0b2](https://linux-hardware.org/?probe=f4e06ff0b2) | Jan 25, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [bf21a44322](https://linux-hardware.org/?probe=bf21a44322) | Jan 23, 2023 |
| Samsung       | N148P/N208P/N218P/NB28P     | Notebook    | [f665dc3839](https://linux-hardware.org/?probe=f665dc3839) | Jan 23, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [023f1e3cdc](https://linux-hardware.org/?probe=023f1e3cdc) | Jan 23, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [04d36be1ec](https://linux-hardware.org/?probe=04d36be1ec) | Jan 20, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [6f91cb09e7](https://linux-hardware.org/?probe=6f91cb09e7) | Jan 18, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [b6e4100bc6](https://linux-hardware.org/?probe=b6e4100bc6) | Jan 17, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [d0a00b398c](https://linux-hardware.org/?probe=d0a00b398c) | Jan 16, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [3f24b17bd8](https://linux-hardware.org/?probe=3f24b17bd8) | Jan 16, 2023 |
| Lenovo        | ThinkPad T440s 20AQ0069G... | Notebook    | [cb2e9f2623](https://linux-hardware.org/?probe=cb2e9f2623) | Jan 16, 2023 |
| ASUSTek       | UX305CA                     | Notebook    | [b831308d6c](https://linux-hardware.org/?probe=b831308d6c) | Jan 16, 2023 |
| Dell          | Inspiron 15-3552            | Notebook    | [6fc2ac2b48](https://linux-hardware.org/?probe=6fc2ac2b48) | Jan 14, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [d10834c7df](https://linux-hardware.org/?probe=d10834c7df) | Jan 14, 2023 |
| Lenovo        | IdeaPad Gaming 3 16IAH7 ... | Notebook    | [7c116ff037](https://linux-hardware.org/?probe=7c116ff037) | Jan 13, 2023 |
| Lenovo        | IdeaPad Gaming 3 16IAH7 ... | Notebook    | [4606ff1dab](https://linux-hardware.org/?probe=4606ff1dab) | Jan 11, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [fdb726b276](https://linux-hardware.org/?probe=fdb726b276) | Jan 11, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [18654d5f58](https://linux-hardware.org/?probe=18654d5f58) | Jan 10, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [9f368d248b](https://linux-hardware.org/?probe=9f368d248b) | Jan 10, 2023 |
| Gigabyte      | 990XA-UD3                   | Desktop     | [43e346516e](https://linux-hardware.org/?probe=43e346516e) | Jan 09, 2023 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [d30caadc06](https://linux-hardware.org/?probe=d30caadc06) | Jan 09, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [325952460c](https://linux-hardware.org/?probe=325952460c) | Jan 08, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [da3dc83a74](https://linux-hardware.org/?probe=da3dc83a74) | Jan 07, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [ac63fca6cb](https://linux-hardware.org/?probe=ac63fca6cb) | Jan 07, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [fc7a1958c4](https://linux-hardware.org/?probe=fc7a1958c4) | Jan 07, 2023 |
| Gigabyte      | 990XA-UD3                   | Desktop     | [d23fb14f2e](https://linux-hardware.org/?probe=d23fb14f2e) | Jan 07, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [684653e302](https://linux-hardware.org/?probe=684653e302) | Jan 06, 2023 |
| MSI           | MS-7519                     | Desktop     | [3239304aa0](https://linux-hardware.org/?probe=3239304aa0) | Jan 03, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [7b9bc5bc99](https://linux-hardware.org/?probe=7b9bc5bc99) | Jan 02, 2023 |
| Unknown       | Intel X79                   | Desktop     | [f26c05e261](https://linux-hardware.org/?probe=f26c05e261) | Dec 31, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [cc1d0776d5](https://linux-hardware.org/?probe=cc1d0776d5) | Dec 30, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [614187020c](https://linux-hardware.org/?probe=614187020c) | Dec 29, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [6f0f984312](https://linux-hardware.org/?probe=6f0f984312) | Dec 29, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [d196b92cff](https://linux-hardware.org/?probe=d196b92cff) | Dec 27, 2022 |
| ASRock        | Brazos                      | Desktop     | [f5183b395b](https://linux-hardware.org/?probe=f5183b395b) | Dec 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [beb602dcf6](https://linux-hardware.org/?probe=beb602dcf6) | Dec 23, 2022 |
| Toshiba       | Satellite C850-C5K          | Notebook    | [a67d24c9f9](https://linux-hardware.org/?probe=a67d24c9f9) | Dec 23, 2022 |
| LTD Delovo... | EVE 14 C414 ES4060EW        | Notebook    | [9f1751d2e5](https://linux-hardware.org/?probe=9f1751d2e5) | Dec 22, 2022 |
| Pegatron      | A17                         | Notebook    | [f40a055eac](https://linux-hardware.org/?probe=f40a055eac) | Dec 21, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | Notebook    | [bdb2887598](https://linux-hardware.org/?probe=bdb2887598) | Dec 20, 2022 |
| ASRock        | X570 Pro4                   | Desktop     | [09fc64653e](https://linux-hardware.org/?probe=09fc64653e) | Dec 17, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [0d07341d58](https://linux-hardware.org/?probe=0d07341d58) | Dec 15, 2022 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [077f863ca3](https://linux-hardware.org/?probe=077f863ca3) | Dec 15, 2022 |
| HP            | ProBook 445 G7              | Notebook    | [b34265fdbe](https://linux-hardware.org/?probe=b34265fdbe) | Dec 14, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [becb2e6bbc](https://linux-hardware.org/?probe=becb2e6bbc) | Dec 12, 2022 |
| Biostar       | A520MH                      | Desktop     | [e1eff55b96](https://linux-hardware.org/?probe=e1eff55b96) | Dec 12, 2022 |
| HP            | ProBook x360 435 G8 Note... | Convertible | [a096df53ed](https://linux-hardware.org/?probe=a096df53ed) | Dec 12, 2022 |
| Biostar       | A520MH                      | Desktop     | [2c6278e478](https://linux-hardware.org/?probe=2c6278e478) | Dec 11, 2022 |
| ASUSTek       | Z9PA-D8 Series              | Server      | [fcd4a2d840](https://linux-hardware.org/?probe=fcd4a2d840) | Dec 11, 2022 |
| Gigabyte      | M61SME-S2                   | Desktop     | [e2932e425c](https://linux-hardware.org/?probe=e2932e425c) | Dec 11, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [b463c25c4d](https://linux-hardware.org/?probe=b463c25c4d) | Dec 11, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [1c80b48ea0](https://linux-hardware.org/?probe=1c80b48ea0) | Dec 11, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [ad6dc99c8a](https://linux-hardware.org/?probe=ad6dc99c8a) | Dec 10, 2022 |
| ASUSTek       | P8Z77-V LE PLUS             | Desktop     | [eafc4dffd4](https://linux-hardware.org/?probe=eafc4dffd4) | Dec 07, 2022 |
| HP            | 550                         | Notebook    | [1090513329](https://linux-hardware.org/?probe=1090513329) | Dec 06, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [1a1f2b375d](https://linux-hardware.org/?probe=1a1f2b375d) | Dec 05, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [d6829bfb6d](https://linux-hardware.org/?probe=d6829bfb6d) | Dec 04, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [c2ee22631f](https://linux-hardware.org/?probe=c2ee22631f) | Dec 03, 2022 |
| HP            | Pavilion g6                 | Notebook    | [c3f0c49c7c](https://linux-hardware.org/?probe=c3f0c49c7c) | Dec 02, 2022 |
| HP            | Pavilion g6                 | Notebook    | [cb93839085](https://linux-hardware.org/?probe=cb93839085) | Dec 01, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [2de79b83d5](https://linux-hardware.org/?probe=2de79b83d5) | Nov 28, 2022 |
| ASUSTek       | K70AB                       | Notebook    | [8b7e3c4b9e](https://linux-hardware.org/?probe=8b7e3c4b9e) | Nov 26, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [1c7b4c3780](https://linux-hardware.org/?probe=1c7b4c3780) | Nov 21, 2022 |
| HASEE Comp... | V1x0PNPx                    | Notebook    | [e75868724e](https://linux-hardware.org/?probe=e75868724e) | Nov 19, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [3f043b96c0](https://linux-hardware.org/?probe=3f043b96c0) | Nov 19, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [450ca9f243](https://linux-hardware.org/?probe=450ca9f243) | Nov 19, 2022 |
| Acer          | Aspire ES1-331              | Notebook    | [32e06647dd](https://linux-hardware.org/?probe=32e06647dd) | Nov 19, 2022 |
| Timi          | Xiaomi Book Pro 16 2022     | Notebook    | [08db92bff6](https://linux-hardware.org/?probe=08db92bff6) | Nov 17, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [288b53c471](https://linux-hardware.org/?probe=288b53c471) | Nov 16, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [23ec67e81b](https://linux-hardware.org/?probe=23ec67e81b) | Nov 16, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [b64a32327f](https://linux-hardware.org/?probe=b64a32327f) | Nov 11, 2022 |
| ASUSTek       | UX31A                       | Notebook    | [e9bc780ce8](https://linux-hardware.org/?probe=e9bc780ce8) | Nov 09, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [423a8f624c](https://linux-hardware.org/?probe=423a8f624c) | Nov 08, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [f236aa0a8b](https://linux-hardware.org/?probe=f236aa0a8b) | Nov 08, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [09c253d548](https://linux-hardware.org/?probe=09c253d548) | Nov 07, 2022 |
| Chuwi         | GemiBook                    | Notebook    | [9d1fda5ecb](https://linux-hardware.org/?probe=9d1fda5ecb) | Nov 06, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [3f80a8a4c4](https://linux-hardware.org/?probe=3f80a8a4c4) | Nov 06, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3cb1f34e2a](https://linux-hardware.org/?probe=3cb1f34e2a) | Nov 04, 2022 |
| ASUSTek       | K501LB                      | Notebook    | [e28cd8cfbf](https://linux-hardware.org/?probe=e28cd8cfbf) | Nov 03, 2022 |
| Unknown       | Unknown                     | Notebook    | [77bdbb310f](https://linux-hardware.org/?probe=77bdbb310f) | Oct 31, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [4b5140c9f3](https://linux-hardware.org/?probe=4b5140c9f3) | Oct 31, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3f69e984d1](https://linux-hardware.org/?probe=3f69e984d1) | Oct 30, 2022 |
| ASUSTek       | K501LB                      | Notebook    | [25003181f1](https://linux-hardware.org/?probe=25003181f1) | Oct 27, 2022 |
| ASUSTek       | K501LB                      | Notebook    | [2481764903](https://linux-hardware.org/?probe=2481764903) | Oct 27, 2022 |
| HP            | Compaq 610                  | Notebook    | [5adc7e0aba](https://linux-hardware.org/?probe=5adc7e0aba) | Oct 26, 2022 |
| HP            | Compaq 610                  | Notebook    | [9a584886fe](https://linux-hardware.org/?probe=9a584886fe) | Oct 23, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [46b9d8c126](https://linux-hardware.org/?probe=46b9d8c126) | Oct 19, 2022 |
| Acer          | Aspire E1-531               | Notebook    | [527c4e0728](https://linux-hardware.org/?probe=527c4e0728) | Oct 17, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [8b1714d48d](https://linux-hardware.org/?probe=8b1714d48d) | Oct 17, 2022 |
| Acer          | Aspire E1-531               | Notebook    | [834248c556](https://linux-hardware.org/?probe=834248c556) | Oct 16, 2022 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [b36220c65b](https://linux-hardware.org/?probe=b36220c65b) | Oct 13, 2022 |
| ASUSTek       | X751LD                      | Notebook    | [230969c119](https://linux-hardware.org/?probe=230969c119) | Oct 12, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [6e83c73646](https://linux-hardware.org/?probe=6e83c73646) | Oct 11, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [14b0f43bd5](https://linux-hardware.org/?probe=14b0f43bd5) | Oct 11, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [d6e11d36a8](https://linux-hardware.org/?probe=d6e11d36a8) | Oct 10, 2022 |
| ASUSTek       | T101MT                      | Notebook    | [d0fc7c3dae](https://linux-hardware.org/?probe=d0fc7c3dae) | Oct 04, 2022 |
| Lenovo        | ThinkPad E14 20RA001HRT     | Notebook    | [1427143cf0](https://linux-hardware.org/?probe=1427143cf0) | Oct 03, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [99df624686](https://linux-hardware.org/?probe=99df624686) | Oct 03, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [4a8d27ad0f](https://linux-hardware.org/?probe=4a8d27ad0f) | Oct 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [dfea1c9f70](https://linux-hardware.org/?probe=dfea1c9f70) | Sep 29, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [25e3064dd2](https://linux-hardware.org/?probe=25e3064dd2) | Sep 29, 2022 |
| HP            | ProBook 450 G2              | Notebook    | [2935c5bedd](https://linux-hardware.org/?probe=2935c5bedd) | Sep 27, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [254a78c371](https://linux-hardware.org/?probe=254a78c371) | Sep 26, 2022 |
| HP            | Pavilion dv4000 (PX306UA... | Notebook    | [372160583e](https://linux-hardware.org/?probe=372160583e) | Sep 22, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [a861ca9999](https://linux-hardware.org/?probe=a861ca9999) | Sep 19, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [8f6b96ba44](https://linux-hardware.org/?probe=8f6b96ba44) | Sep 19, 2022 |
| Lenovo        | B580 20144                  | Notebook    | [093692b5ab](https://linux-hardware.org/?probe=093692b5ab) | Sep 19, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [467d4c60c0](https://linux-hardware.org/?probe=467d4c60c0) | Sep 16, 2022 |
| ASUSTek       | X550MD                      | Notebook    | [69cce160a1](https://linux-hardware.org/?probe=69cce160a1) | Sep 16, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [a856637b19](https://linux-hardware.org/?probe=a856637b19) | Sep 15, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [cb17ac9b4e](https://linux-hardware.org/?probe=cb17ac9b4e) | Sep 05, 2022 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [8b8ba6c7f9](https://linux-hardware.org/?probe=8b8ba6c7f9) | Sep 05, 2022 |
| Toshiba       | Satellite C850-C5K          | Notebook    | [51dbca1f4d](https://linux-hardware.org/?probe=51dbca1f4d) | Sep 03, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [d927e47d1f](https://linux-hardware.org/?probe=d927e47d1f) | Aug 30, 2022 |
| Acer          | Aspire E1-571G              | Notebook    | [414795a69b](https://linux-hardware.org/?probe=414795a69b) | Aug 29, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [d9d75bc1f0](https://linux-hardware.org/?probe=d9d75bc1f0) | Aug 29, 2022 |
| Gigabyte      | M61SME-S2                   | Desktop     | [2ee74a388d](https://linux-hardware.org/?probe=2ee74a388d) | Aug 25, 2022 |
| HP            | Compaq 610                  | Notebook    | [538b6ae6f8](https://linux-hardware.org/?probe=538b6ae6f8) | Aug 24, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [efc85efba2](https://linux-hardware.org/?probe=efc85efba2) | Aug 23, 2022 |
| ASRock        | N68-VGS3 FX                 | Desktop     | [1d2367ccf7](https://linux-hardware.org/?probe=1d2367ccf7) | Aug 23, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [79d380d4af](https://linux-hardware.org/?probe=79d380d4af) | Aug 21, 2022 |
| Acer          | Aspire 7750ZG               | Notebook    | [e0d514dd08](https://linux-hardware.org/?probe=e0d514dd08) | Aug 21, 2022 |
| Lenovo        | Z710 20250                  | Notebook    | [8c7e567f41](https://linux-hardware.org/?probe=8c7e567f41) | Aug 21, 2022 |
| Acer          | Aspire E1-531               | Notebook    | [1292b2297f](https://linux-hardware.org/?probe=1292b2297f) | Aug 21, 2022 |
| HP            | Compaq 610                  | Notebook    | [2b90520f8f](https://linux-hardware.org/?probe=2b90520f8f) | Aug 18, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [3f685da542](https://linux-hardware.org/?probe=3f685da542) | Aug 17, 2022 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [3decfcd64a](https://linux-hardware.org/?probe=3decfcd64a) | Aug 14, 2022 |
| Huanan        | X99-BD4 V1.33               | Desktop     | [a250b39eec](https://linux-hardware.org/?probe=a250b39eec) | Aug 13, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [f41308ccdc](https://linux-hardware.org/?probe=f41308ccdc) | Aug 12, 2022 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [b73567b27b](https://linux-hardware.org/?probe=b73567b27b) | Aug 09, 2022 |
| Sony          | SVF1521L1RW                 | Notebook    | [c5f143f93d](https://linux-hardware.org/?probe=c5f143f93d) | Aug 09, 2022 |
| MSI           | Katana GF76 11UC            | Notebook    | [4b4e4d693e](https://linux-hardware.org/?probe=4b4e4d693e) | Aug 06, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [4caa777a81](https://linux-hardware.org/?probe=4caa777a81) | Aug 04, 2022 |
| ASUSTek       | X541UV                      | Notebook    | [feb8312a2c](https://linux-hardware.org/?probe=feb8312a2c) | Aug 04, 2022 |
| HONOR         | NBR-WAX9                    | Notebook    | [e9fcbc7798](https://linux-hardware.org/?probe=e9fcbc7798) | Aug 01, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [fc1b36d062](https://linux-hardware.org/?probe=fc1b36d062) | Jul 31, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [97f6892c6c](https://linux-hardware.org/?probe=97f6892c6c) | Jul 30, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [c8562d4bac](https://linux-hardware.org/?probe=c8562d4bac) | Jul 27, 2022 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [e899f43a3f](https://linux-hardware.org/?probe=e899f43a3f) | Jul 27, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [90b6fd9754](https://linux-hardware.org/?probe=90b6fd9754) | Jul 27, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [1af666a847](https://linux-hardware.org/?probe=1af666a847) | Jul 27, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [4e757278be](https://linux-hardware.org/?probe=4e757278be) | Jul 24, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [1ee2492f24](https://linux-hardware.org/?probe=1ee2492f24) | Jul 23, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [2d2a17094e](https://linux-hardware.org/?probe=2d2a17094e) | Jul 23, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [5670dc3033](https://linux-hardware.org/?probe=5670dc3033) | Jul 22, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [7142849ed0](https://linux-hardware.org/?probe=7142849ed0) | Jul 17, 2022 |
| Fujitsu       | AMILO Pi 3560               | Notebook    | [aed2d10046](https://linux-hardware.org/?probe=aed2d10046) | Jul 15, 2022 |
| Lenovo        | ThinkPad T480 20L6S0EK00    | Notebook    | [dd43fd4b04](https://linux-hardware.org/?probe=dd43fd4b04) | Jul 15, 2022 |
| Lenovo        | ThinkPad T480 20L6S0EK00    | Notebook    | [9ca58ddce1](https://linux-hardware.org/?probe=9ca58ddce1) | Jul 15, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [e5638d3552](https://linux-hardware.org/?probe=e5638d3552) | Jul 15, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [c81bc160f7](https://linux-hardware.org/?probe=c81bc160f7) | Jul 13, 2022 |
| ASRock        | B550M-HDV                   | Desktop     | [3f20ad2267](https://linux-hardware.org/?probe=3f20ad2267) | Jul 11, 2022 |
| ASRock        | B550M-HDV                   | Desktop     | [b7adccb849](https://linux-hardware.org/?probe=b7adccb849) | Jul 09, 2022 |
| Samsung       | 535U3C                      | Notebook    | [80b2b79e75](https://linux-hardware.org/?probe=80b2b79e75) | Jul 09, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [15a618f993](https://linux-hardware.org/?probe=15a618f993) | Jul 08, 2022 |
| ASUSTek       | K501LB                      | Notebook    | [2ef855cc9c](https://linux-hardware.org/?probe=2ef855cc9c) | Jul 07, 2022 |
| HP            | Compaq 610                  | Notebook    | [62287cff21](https://linux-hardware.org/?probe=62287cff21) | Jul 06, 2022 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [26cbd669e4](https://linux-hardware.org/?probe=26cbd669e4) | Jul 05, 2022 |
| HONOR         | NBR-WAX9                    | Notebook    | [2fb330049e](https://linux-hardware.org/?probe=2fb330049e) | Jul 04, 2022 |
| ASRock        | H61M-HVGS                   | Desktop     | [2b31833bfe](https://linux-hardware.org/?probe=2b31833bfe) | Jul 02, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [06d4d79742](https://linux-hardware.org/?probe=06d4d79742) | Jul 01, 2022 |
| Biostar       | TA790GX 128M                | Desktop     | [c7021e0b8c](https://linux-hardware.org/?probe=c7021e0b8c) | Jul 01, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [5acbf09f01](https://linux-hardware.org/?probe=5acbf09f01) | Jun 29, 2022 |
| Prestigio     | Multipad Visconte V         | Notebook    | [fd38a70070](https://linux-hardware.org/?probe=fd38a70070) | Jun 29, 2022 |
| HONOR         | NBR-WAX9                    | Notebook    | [8cb88942e3](https://linux-hardware.org/?probe=8cb88942e3) | Jun 28, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [3417dd6a9a](https://linux-hardware.org/?probe=3417dd6a9a) | Jun 28, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [e52ad13385](https://linux-hardware.org/?probe=e52ad13385) | Jun 25, 2022 |
| Getac         | B300-H                      | Notebook    | [ff8382e269](https://linux-hardware.org/?probe=ff8382e269) | Jun 24, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [0647ff3774](https://linux-hardware.org/?probe=0647ff3774) | Jun 24, 2022 |
| Getac         | B300-H                      | Notebook    | [d0b0703736](https://linux-hardware.org/?probe=d0b0703736) | Jun 23, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [6dd752fab5](https://linux-hardware.org/?probe=6dd752fab5) | Jun 23, 2022 |
| Dell          | 0PGMR1 A00                  | All in one  | [bf057e65d8](https://linux-hardware.org/?probe=bf057e65d8) | Jun 22, 2022 |
| Fujitsu       | LIFEBOOK U745               | Notebook    | [0fffb61902](https://linux-hardware.org/?probe=0fffb61902) | Jun 22, 2022 |
| HP            | Notebook                    | Notebook    | [76d300309e](https://linux-hardware.org/?probe=76d300309e) | Jun 21, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [17b77e3069](https://linux-hardware.org/?probe=17b77e3069) | Jun 17, 2022 |
| Acer          | Extensa 5220                | Notebook    | [dd0d362582](https://linux-hardware.org/?probe=dd0d362582) | Jun 15, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [701de0d7ad](https://linux-hardware.org/?probe=701de0d7ad) | Jun 15, 2022 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [d381bbec9f](https://linux-hardware.org/?probe=d381bbec9f) | Jun 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | Notebook    | [8e7a43f724](https://linux-hardware.org/?probe=8e7a43f724) | Jun 13, 2022 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [fd45495f2a](https://linux-hardware.org/?probe=fd45495f2a) | Jun 12, 2022 |
| HP            | Notebook                    | Notebook    | [5c18b71eb1](https://linux-hardware.org/?probe=5c18b71eb1) | Jun 10, 2022 |
| Sony          | SVE1713Y1RB                 | Notebook    | [4a1bc35dda](https://linux-hardware.org/?probe=4a1bc35dda) | Jun 09, 2022 |
| Acer          | Aspire A315-56              | Notebook    | [595e4c8656](https://linux-hardware.org/?probe=595e4c8656) | Jun 09, 2022 |
| Acer          | Aspire A315-56              | Notebook    | [0ee020dd5a](https://linux-hardware.org/?probe=0ee020dd5a) | Jun 09, 2022 |
| Acer          | Swift SF314-59              | Notebook    | [e057e3b6d8](https://linux-hardware.org/?probe=e057e3b6d8) | Jun 07, 2022 |
| HP            | Mini 110-4100               | Notebook    | [62932d62d5](https://linux-hardware.org/?probe=62932d62d5) | Jun 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [0c1909c43b](https://linux-hardware.org/?probe=0c1909c43b) | Jun 03, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3aa4194ab3](https://linux-hardware.org/?probe=3aa4194ab3) | Jun 02, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [88d5e21b42](https://linux-hardware.org/?probe=88d5e21b42) | Jun 01, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [50927f5cae](https://linux-hardware.org/?probe=50927f5cae) | May 30, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [ee508ca972](https://linux-hardware.org/?probe=ee508ca972) | May 28, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [77989d3d20](https://linux-hardware.org/?probe=77989d3d20) | May 28, 2022 |
| Lenovo        | IdeaPad Z580                | Notebook    | [4b1c87e746](https://linux-hardware.org/?probe=4b1c87e746) | May 26, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [dd317d92a3](https://linux-hardware.org/?probe=dd317d92a3) | May 25, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [af256d7649](https://linux-hardware.org/?probe=af256d7649) | May 24, 2022 |
| HP            | Pavilion 17                 | Notebook    | [d2dbdbd444](https://linux-hardware.org/?probe=d2dbdbd444) | May 22, 2022 |
| ECS           | IC780M-A2                   | Desktop     | [135f0a4328](https://linux-hardware.org/?probe=135f0a4328) | May 21, 2022 |
| MSI           | MS-7309                     | Desktop     | [9093ca0773](https://linux-hardware.org/?probe=9093ca0773) | May 20, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [9e7bf270db](https://linux-hardware.org/?probe=9e7bf270db) | May 17, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [934bd75010](https://linux-hardware.org/?probe=934bd75010) | May 16, 2022 |
| ASUSTek       | M51Sr                       | Notebook    | [ebcb6315c9](https://linux-hardware.org/?probe=ebcb6315c9) | May 16, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [ec4bd74f0b](https://linux-hardware.org/?probe=ec4bd74f0b) | May 13, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [a53ce6039b](https://linux-hardware.org/?probe=a53ce6039b) | May 12, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [46481247b1](https://linux-hardware.org/?probe=46481247b1) | May 12, 2022 |
| Gigabyte      | Z87P-D3                     | Desktop     | [2a916e3eb5](https://linux-hardware.org/?probe=2a916e3eb5) | May 09, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [fbe61c70ff](https://linux-hardware.org/?probe=fbe61c70ff) | May 09, 2022 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | Notebook    | [edefb39601](https://linux-hardware.org/?probe=edefb39601) | May 08, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [76e67361ea](https://linux-hardware.org/?probe=76e67361ea) | May 08, 2022 |
| ASRock        | N68-GS4 FX                  | Desktop     | [8926d96550](https://linux-hardware.org/?probe=8926d96550) | May 07, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [7c8dbdcffc](https://linux-hardware.org/?probe=7c8dbdcffc) | May 05, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [8fbc520a1b](https://linux-hardware.org/?probe=8fbc520a1b) | May 03, 2022 |
| Lenovo        | G710 20252                  | Notebook    | [9390db3498](https://linux-hardware.org/?probe=9390db3498) | May 01, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [7fb6e94bab](https://linux-hardware.org/?probe=7fb6e94bab) | Apr 27, 2022 |
| Sony          | SVF1521L1RB                 | Notebook    | [ff5ff260a0](https://linux-hardware.org/?probe=ff5ff260a0) | Apr 26, 2022 |
| ASUSTek       | ROG Maximus XI CODE         | Desktop     | [8cca49b0ee](https://linux-hardware.org/?probe=8cca49b0ee) | Apr 25, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [18a941a40d](https://linux-hardware.org/?probe=18a941a40d) | Apr 19, 2022 |
| Sony          | SVF1521L1RB                 | Notebook    | [1bfd1d7042](https://linux-hardware.org/?probe=1bfd1d7042) | Apr 18, 2022 |
| Sony          | SVF1521L1RB                 | Notebook    | [e2034a7617](https://linux-hardware.org/?probe=e2034a7617) | Apr 17, 2022 |
| HP            | Notebook                    | Notebook    | [966668f0c0](https://linux-hardware.org/?probe=966668f0c0) | Apr 17, 2022 |
| Sony          | SVF1521L1RB                 | Notebook    | [ab464ae6a9](https://linux-hardware.org/?probe=ab464ae6a9) | Apr 15, 2022 |
| Acer          | Aspire 5739G                | Notebook    | [46b7178535](https://linux-hardware.org/?probe=46b7178535) | Apr 14, 2022 |
| Gigabyte      | Z270P-D3-CF                 | Desktop     | [155e5c0ef5](https://linux-hardware.org/?probe=155e5c0ef5) | Apr 14, 2022 |
| Gigabyte      | B75M-D2V                    | Desktop     | [07de6c8eb6](https://linux-hardware.org/?probe=07de6c8eb6) | Apr 12, 2022 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [6273f8eefb](https://linux-hardware.org/?probe=6273f8eefb) | Apr 12, 2022 |
| ASRock        | B450M Pro4-F                | Desktop     | [1dff7e3c31](https://linux-hardware.org/?probe=1dff7e3c31) | Apr 11, 2022 |
| ASRock        | N68-VGS3 FX                 | Desktop     | [292cc244de](https://linux-hardware.org/?probe=292cc244de) | Apr 11, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [8a1cecc21c](https://linux-hardware.org/?probe=8a1cecc21c) | Apr 11, 2022 |
| ASRock        | B560M Steel Legend          | Desktop     | [90a9483531](https://linux-hardware.org/?probe=90a9483531) | Apr 10, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [6099079c27](https://linux-hardware.org/?probe=6099079c27) | Apr 09, 2022 |
| Gigabyte      | Z87P-D3                     | Desktop     | [9ea9a7e8ef](https://linux-hardware.org/?probe=9ea9a7e8ef) | Apr 09, 2022 |
| Acer          | Aspire A315-56              | Notebook    | [a096b22b37](https://linux-hardware.org/?probe=a096b22b37) | Apr 09, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [993ad2218a](https://linux-hardware.org/?probe=993ad2218a) | Apr 07, 2022 |
| Acer          | Swift SF314-59              | Notebook    | [bcbdedc21a](https://linux-hardware.org/?probe=bcbdedc21a) | Apr 07, 2022 |
| ASUSTek       | X541NC                      | Notebook    | [a7af7e79fd](https://linux-hardware.org/?probe=a7af7e79fd) | Apr 06, 2022 |
| Acer          | Swift SF314-59              | Notebook    | [6d2f9e0fce](https://linux-hardware.org/?probe=6d2f9e0fce) | Apr 05, 2022 |
| HP            | ProBook 455 G1              | Notebook    | [2b9c6b4b05](https://linux-hardware.org/?probe=2b9c6b4b05) | Apr 02, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [29b8b7110c](https://linux-hardware.org/?probe=29b8b7110c) | Apr 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [2d741207c5](https://linux-hardware.org/?probe=2d741207c5) | Mar 30, 2022 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [50780eda28](https://linux-hardware.org/?probe=50780eda28) | Mar 30, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [026a52c3bf](https://linux-hardware.org/?probe=026a52c3bf) | Mar 27, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [c7d6879a86](https://linux-hardware.org/?probe=c7d6879a86) | Mar 26, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [803a20d0cb](https://linux-hardware.org/?probe=803a20d0cb) | Mar 25, 2022 |
| HP            | Pavilion dv3500             | Notebook    | [ef7133f14a](https://linux-hardware.org/?probe=ef7133f14a) | Mar 25, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [b7679b78be](https://linux-hardware.org/?probe=b7679b78be) | Mar 25, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [49853bb240](https://linux-hardware.org/?probe=49853bb240) | Mar 25, 2022 |
| HP            | Pavilion dv3500             | Notebook    | [06883f214a](https://linux-hardware.org/?probe=06883f214a) | Mar 25, 2022 |
| HP            | ProBook 455 G1              | Notebook    | [9e554de092](https://linux-hardware.org/?probe=9e554de092) | Mar 24, 2022 |
| Gigabyte      | B450M S2H V2                | Desktop     | [a8e8d6dd5e](https://linux-hardware.org/?probe=a8e8d6dd5e) | Mar 22, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [378bbcd029](https://linux-hardware.org/?probe=378bbcd029) | Mar 22, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [6ede510a1b](https://linux-hardware.org/?probe=6ede510a1b) | Mar 22, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5505        | Notebook    | [db687b8693](https://linux-hardware.org/?probe=db687b8693) | Mar 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [770f279722](https://linux-hardware.org/?probe=770f279722) | Mar 13, 2022 |
| ASRock        | FM2A55M-VG3                 | Desktop     | [96683b7f45](https://linux-hardware.org/?probe=96683b7f45) | Mar 12, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [517ef58b87](https://linux-hardware.org/?probe=517ef58b87) | Mar 11, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [69fd2b147f](https://linux-hardware.org/?probe=69fd2b147f) | Mar 11, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [55ce4f1460](https://linux-hardware.org/?probe=55ce4f1460) | Mar 11, 2022 |
| Toshiba       | Satellite C650              | Notebook    | [73d930be97](https://linux-hardware.org/?probe=73d930be97) | Mar 10, 2022 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [a6fc7b9f12](https://linux-hardware.org/?probe=a6fc7b9f12) | Mar 10, 2022 |
| Intel         | D945GCLF2 AAE46416-101      | Desktop     | [800bc08dbd](https://linux-hardware.org/?probe=800bc08dbd) | Mar 09, 2022 |
| HP            | Mini 110-4100               | Notebook    | [2c1bf1951f](https://linux-hardware.org/?probe=2c1bf1951f) | Mar 07, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [aebf1eb00c](https://linux-hardware.org/?probe=aebf1eb00c) | Mar 07, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [18486d2474](https://linux-hardware.org/?probe=18486d2474) | Mar 06, 2022 |
| MSI           | Katana GF76 11UC            | Notebook    | [949d0886a1](https://linux-hardware.org/?probe=949d0886a1) | Mar 06, 2022 |
| MSI           | Katana GF76 11UC            | Notebook    | [f5241bc829](https://linux-hardware.org/?probe=f5241bc829) | Mar 05, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [da3962a1da](https://linux-hardware.org/?probe=da3962a1da) | Mar 03, 2022 |
| HP            | 635                         | Notebook    | [0d571de480](https://linux-hardware.org/?probe=0d571de480) | Mar 03, 2022 |
| ASRock        | N68C-GS FX                  | Desktop     | [bdba90c583](https://linux-hardware.org/?probe=bdba90c583) | Mar 03, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [d2e96e523e](https://linux-hardware.org/?probe=d2e96e523e) | Mar 03, 2022 |
| MSI           | Katana GF76 11UC            | Notebook    | [880490eb1e](https://linux-hardware.org/?probe=880490eb1e) | Mar 01, 2022 |
| MSI           | Katana GF76 11UC            | Notebook    | [79cc0b97a4](https://linux-hardware.org/?probe=79cc0b97a4) | Feb 28, 2022 |
| MSI           | Katana GF76 11UC            | Notebook    | [74bc866ab2](https://linux-hardware.org/?probe=74bc866ab2) | Feb 27, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [7ce556e43a](https://linux-hardware.org/?probe=7ce556e43a) | Feb 26, 2022 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [39389b9ddf](https://linux-hardware.org/?probe=39389b9ddf) | Feb 26, 2022 |
| ASUSTek       | ZenBook UX434IQ_UM433IQ     | Notebook    | [013e049a4d](https://linux-hardware.org/?probe=013e049a4d) | Feb 24, 2022 |
| ASUSTek       | ZenBook UX434IQ_UM433IQ     | Notebook    | [885239a137](https://linux-hardware.org/?probe=885239a137) | Feb 24, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [34e4b434b4](https://linux-hardware.org/?probe=34e4b434b4) | Feb 20, 2022 |
| Sony          | VPCF119FX                   | Notebook    | [1e8448b824](https://linux-hardware.org/?probe=1e8448b824) | Feb 15, 2022 |
| ASUSTek       | K50C                        | Notebook    | [01079b722b](https://linux-hardware.org/?probe=01079b722b) | Feb 11, 2022 |
| ASUSTek       | K50C                        | Notebook    | [8bb8c751f8](https://linux-hardware.org/?probe=8bb8c751f8) | Feb 11, 2022 |
| ASRock        | N68-VGS3 FX                 | Desktop     | [601f46e5a4](https://linux-hardware.org/?probe=601f46e5a4) | Feb 09, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [7966e303e6](https://linux-hardware.org/?probe=7966e303e6) | Feb 07, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [a32dfea06a](https://linux-hardware.org/?probe=a32dfea06a) | Feb 07, 2022 |
| ASRock        | B560M Steel Legend          | Desktop     | [e2a7b380d8](https://linux-hardware.org/?probe=e2a7b380d8) | Feb 06, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [d7796dd19f](https://linux-hardware.org/?probe=d7796dd19f) | Feb 05, 2022 |
| Lenovo        | V580c 20160                 | Notebook    | [8b9e72e0ed](https://linux-hardware.org/?probe=8b9e72e0ed) | Feb 03, 2022 |
| Gigabyte      | M61SME-S2                   | Desktop     | [ce0fa6ccd3](https://linux-hardware.org/?probe=ce0fa6ccd3) | Feb 03, 2022 |
| MSI           | B150M PRO-VH                | Desktop     | [583a1313c8](https://linux-hardware.org/?probe=583a1313c8) | Feb 01, 2022 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [0bcf18e1fc](https://linux-hardware.org/?probe=0bcf18e1fc) | Feb 01, 2022 |
| HP            | Compaq 8710w (GC124EA#AC... | Notebook    | [b21e187792](https://linux-hardware.org/?probe=b21e187792) | Jan 29, 2022 |
| Lenovo        | Yoga 730-13IWL 81JR         | Convertible | [ed633ddd09](https://linux-hardware.org/?probe=ed633ddd09) | Jan 29, 2022 |
| Lenovo        | Yoga 730-13IWL 81JR         | Convertible | [607ade73d0](https://linux-hardware.org/?probe=607ade73d0) | Jan 29, 2022 |
| ASUSTek       | M2A74-AM SE                 | Desktop     | [1a2d6520d3](https://linux-hardware.org/?probe=1a2d6520d3) | Jan 29, 2022 |
| MSI           | H87M-E35                    | Desktop     | [0cfdd2b772](https://linux-hardware.org/?probe=0cfdd2b772) | Jan 28, 2022 |
| HP            | Presario CQ57               | Notebook    | [6a8428a112](https://linux-hardware.org/?probe=6a8428a112) | Jan 27, 2022 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [abed2f64a1](https://linux-hardware.org/?probe=abed2f64a1) | Jan 26, 2022 |
| Acer          | Aspire F5-572G              | Notebook    | [7dbefa64bc](https://linux-hardware.org/?probe=7dbefa64bc) | Jan 23, 2022 |
| Kllisre       | X79 V1.2                    | Desktop     | [84bd3ccecf](https://linux-hardware.org/?probe=84bd3ccecf) | Jan 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [e00760f649](https://linux-hardware.org/?probe=e00760f649) | Jan 21, 2022 |
| MSI           | B150M PRO-VH                | Desktop     | [de22d479a4](https://linux-hardware.org/?probe=de22d479a4) | Jan 20, 2022 |
| Quanta        | TW8/SW8/DW8 TBD             | Notebook    | [8b2f4ffccd](https://linux-hardware.org/?probe=8b2f4ffccd) | Jan 16, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [291a3e234b](https://linux-hardware.org/?probe=291a3e234b) | Jan 14, 2022 |
| ASUSTek       | X550CA                      | Notebook    | [8f9c010abb](https://linux-hardware.org/?probe=8f9c010abb) | Jan 10, 2022 |
| Kllisre       | X79 V1.2                    | Desktop     | [239547a419](https://linux-hardware.org/?probe=239547a419) | Jan 09, 2022 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [0ea3f1d6fa](https://linux-hardware.org/?probe=0ea3f1d6fa) | Jan 08, 2022 |
| Dell          | G7 7700                     | Notebook    | [f02bcbdcfe](https://linux-hardware.org/?probe=f02bcbdcfe) | Jan 06, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [527c2f975b](https://linux-hardware.org/?probe=527c2f975b) | Jan 05, 2022 |
| MSI           | GF63 Thin 9SCSR             | Notebook    | [21f2a5e1b9](https://linux-hardware.org/?probe=21f2a5e1b9) | Jan 05, 2022 |
| ASRock        | AB350M Pro4                 | Desktop     | [2886b84cc0](https://linux-hardware.org/?probe=2886b84cc0) | Jan 04, 2022 |
| Timi          | TM1613                      | Notebook    | [6761bd1e12](https://linux-hardware.org/?probe=6761bd1e12) | Jan 04, 2022 |
| MSI           | GT75 Titan 8RG              | Notebook    | [77e24243cf](https://linux-hardware.org/?probe=77e24243cf) | Jan 02, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [5d9026b1c0](https://linux-hardware.org/?probe=5d9026b1c0) | Jan 01, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3bfe8cb49e](https://linux-hardware.org/?probe=3bfe8cb49e) | Jan 01, 2022 |
| Lenovo        | V580c 20160                 | Notebook    | [9f9fe096db](https://linux-hardware.org/?probe=9f9fe096db) | Dec 30, 2021 |
| MSI           | MS-7922                     | Desktop     | [d0837f687b](https://linux-hardware.org/?probe=d0837f687b) | Dec 27, 2021 |
| Lenovo        | ThinkPad E15 20RD003KRT     | Notebook    | [62e3c3073b](https://linux-hardware.org/?probe=62e3c3073b) | Dec 26, 2021 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [29b9cc77f1](https://linux-hardware.org/?probe=29b9cc77f1) | Dec 21, 2021 |
| Gigabyte      | M61SME-S2                   | Desktop     | [be9f6cac13](https://linux-hardware.org/?probe=be9f6cac13) | Dec 20, 2021 |
| ASUSTek       | X540UA                      | Notebook    | [4d399918f0](https://linux-hardware.org/?probe=4d399918f0) | Dec 20, 2021 |
| HONOR         | BMH-WCX9                    | Notebook    | [46395a1450](https://linux-hardware.org/?probe=46395a1450) | Dec 19, 2021 |
| MSI           | A320M PRO-VD PLUS           | Desktop     | [7f0853c09e](https://linux-hardware.org/?probe=7f0853c09e) | Dec 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [0642db16f6](https://linux-hardware.org/?probe=0642db16f6) | Dec 19, 2021 |
| MSI           | GL63 9SC                    | Notebook    | [ed637c5d15](https://linux-hardware.org/?probe=ed637c5d15) | Dec 16, 2021 |
| Fujitsu       | LIFEBOOK NH532              | Notebook    | [84be255271](https://linux-hardware.org/?probe=84be255271) | Dec 15, 2021 |
| HP            | ProBook 450 G4              | Notebook    | [0573beab82](https://linux-hardware.org/?probe=0573beab82) | Dec 15, 2021 |
| BenQ          | Joybook R56                 | Notebook    | [e05d04b5ec](https://linux-hardware.org/?probe=e05d04b5ec) | Dec 13, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [3616fc5b0e](https://linux-hardware.org/?probe=3616fc5b0e) | Dec 12, 2021 |
| Quanta        | TW8/SW8/DW8 TBD             | Notebook    | [43f645de28](https://linux-hardware.org/?probe=43f645de28) | Dec 11, 2021 |
| Gigabyte      | B450M S2H                   | Desktop     | [a2e037ba0e](https://linux-hardware.org/?probe=a2e037ba0e) | Dec 09, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f9ada169fd](https://linux-hardware.org/?probe=f9ada169fd) | Dec 09, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7d39826b60](https://linux-hardware.org/?probe=7d39826b60) | Dec 09, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [610d56a10a](https://linux-hardware.org/?probe=610d56a10a) | Dec 08, 2021 |
| HP            | Pavilion TS 11              | Notebook    | [3c415780c5](https://linux-hardware.org/?probe=3c415780c5) | Dec 06, 2021 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [7304efa5d7](https://linux-hardware.org/?probe=7304efa5d7) | Dec 01, 2021 |
| LG Electro... | R510                        | Notebook    | [13f4496897](https://linux-hardware.org/?probe=13f4496897) | Nov 28, 2021 |
| Dell          | 0PGMR1 A00                  | All in one  | [00c297540d](https://linux-hardware.org/?probe=00c297540d) | Nov 27, 2021 |
| ASUSTek       | P5B-VM SE                   | Desktop     | [0162ece16f](https://linux-hardware.org/?probe=0162ece16f) | Nov 25, 2021 |
| ASUSTek       | 1000HE                      | Notebook    | [5923c0d7e3](https://linux-hardware.org/?probe=5923c0d7e3) | Nov 25, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [c420169ce7](https://linux-hardware.org/?probe=c420169ce7) | Nov 25, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b9e2d78f66](https://linux-hardware.org/?probe=b9e2d78f66) | Nov 23, 2021 |
| Lenovo        | ThinkPad T470p 20J7S06Q0... | Notebook    | [6eca4a1be2](https://linux-hardware.org/?probe=6eca4a1be2) | Nov 22, 2021 |
| Lenovo        | ThinkPad T470p 20J7S06Q0... | Notebook    | [6c92c6ecbb](https://linux-hardware.org/?probe=6c92c6ecbb) | Nov 22, 2021 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | Notebook    | [f13b0fb2b9](https://linux-hardware.org/?probe=f13b0fb2b9) | Nov 22, 2021 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [53e26c9677](https://linux-hardware.org/?probe=53e26c9677) | Nov 22, 2021 |
| HP            | EliteBook 850 G6            | Notebook    | [488cdb831c](https://linux-hardware.org/?probe=488cdb831c) | Nov 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [1784f93056](https://linux-hardware.org/?probe=1784f93056) | Nov 18, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [ec73e73572](https://linux-hardware.org/?probe=ec73e73572) | Nov 16, 2021 |
| Fujitsu       | D3034-A1 S26361-D3034-A1... | Server      | [8cf8f98a53](https://linux-hardware.org/?probe=8cf8f98a53) | Nov 15, 2021 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | Notebook    | [ea6139e86c](https://linux-hardware.org/?probe=ea6139e86c) | Nov 15, 2021 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | Notebook    | [90e882710c](https://linux-hardware.org/?probe=90e882710c) | Nov 15, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | Notebook    | [688e4047ce](https://linux-hardware.org/?probe=688e4047ce) | Nov 11, 2021 |
| ASUSTek       | UX31A                       | Notebook    | [696ee320dd](https://linux-hardware.org/?probe=696ee320dd) | Nov 11, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [039315b907](https://linux-hardware.org/?probe=039315b907) | Nov 10, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [e290db920f](https://linux-hardware.org/?probe=e290db920f) | Nov 08, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [3533adc65b](https://linux-hardware.org/?probe=3533adc65b) | Nov 07, 2021 |
| HP            | ProBook 455 G1              | Notebook    | [44a11d66ac](https://linux-hardware.org/?probe=44a11d66ac) | Nov 06, 2021 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [c04f0fcb02](https://linux-hardware.org/?probe=c04f0fcb02) | Nov 06, 2021 |
| ASRock        | B365 Pro4                   | Desktop     | [5010ca9e9a](https://linux-hardware.org/?probe=5010ca9e9a) | Nov 06, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [04d4fca603](https://linux-hardware.org/?probe=04d4fca603) | Nov 04, 2021 |
| ASUSTek       | V241EA                      | All in one  | [ffb4ed2207](https://linux-hardware.org/?probe=ffb4ed2207) | Nov 02, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [0233ae7054](https://linux-hardware.org/?probe=0233ae7054) | Oct 31, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [2ba5ae42bb](https://linux-hardware.org/?probe=2ba5ae42bb) | Oct 31, 2021 |
| Dell          | 0PGMR1 A00                  | All in one  | [04c5f1689d](https://linux-hardware.org/?probe=04c5f1689d) | Oct 27, 2021 |
| ASRock        | N68C-S UCC                  | Desktop     | [0f23350175](https://linux-hardware.org/?probe=0f23350175) | Oct 27, 2021 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [a56c0a6b4d](https://linux-hardware.org/?probe=a56c0a6b4d) | Oct 26, 2021 |
| Samsung       | R508                        | Notebook    | [89842bec44](https://linux-hardware.org/?probe=89842bec44) | Oct 25, 2021 |
| HP            | Notebook                    | Notebook    | [1963a09646](https://linux-hardware.org/?probe=1963a09646) | Oct 24, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [4bc3faf49f](https://linux-hardware.org/?probe=4bc3faf49f) | Oct 24, 2021 |
| ASRock        | B365 Pro4                   | Desktop     | [8061e7314a](https://linux-hardware.org/?probe=8061e7314a) | Oct 23, 2021 |
| HP            | 86F0 11000                  | All in one  | [75738404ae](https://linux-hardware.org/?probe=75738404ae) | Oct 21, 2021 |
| ASUSTek       | K53BR                       | Notebook    | [af980dc491](https://linux-hardware.org/?probe=af980dc491) | Oct 21, 2021 |
| Lenovo        | ThinkPad T490 20N2000KRT    | Notebook    | [55daad7a3a](https://linux-hardware.org/?probe=55daad7a3a) | Oct 17, 2021 |
| Lenovo        | S10-3                       | Notebook    | [1f4f861804](https://linux-hardware.org/?probe=1f4f861804) | Oct 17, 2021 |
| Lenovo        | S10-3                       | Notebook    | [acb07e4c72](https://linux-hardware.org/?probe=acb07e4c72) | Oct 16, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [f874da9f03](https://linux-hardware.org/?probe=f874da9f03) | Oct 12, 2021 |
| ASRock        | J3455B-ITX                  | Desktop     | [9fd17a6579](https://linux-hardware.org/?probe=9fd17a6579) | Oct 09, 2021 |
| ASRock        | J3455B-ITX                  | Desktop     | [9b4b3c9f77](https://linux-hardware.org/?probe=9b4b3c9f77) | Oct 09, 2021 |
| Gigabyte      | Z87P-D3                     | Desktop     | [b99c6d022e](https://linux-hardware.org/?probe=b99c6d022e) | Oct 05, 2021 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [0d6bbd5c75](https://linux-hardware.org/?probe=0d6bbd5c75) | Oct 05, 2021 |
| Acer          | Aspire A515-44G             | Notebook    | [264badf289](https://linux-hardware.org/?probe=264badf289) | Oct 01, 2021 |
| HP            | Pavilion dv4000 (PX306UA... | Notebook    | [fdc2b74a29](https://linux-hardware.org/?probe=fdc2b74a29) | Oct 01, 2021 |
| Lenovo        | ThinkPad T480s 20L8SB9Y0... | Notebook    | [75356ac5ee](https://linux-hardware.org/?probe=75356ac5ee) | Oct 01, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [e5838666c2](https://linux-hardware.org/?probe=e5838666c2) | Oct 01, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [b69288527f](https://linux-hardware.org/?probe=b69288527f) | Oct 01, 2021 |
| Intel         | H61M-S1                     | Desktop     | [ba0b4c102b](https://linux-hardware.org/?probe=ba0b4c102b) | Sep 30, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [b6f5c877d4](https://linux-hardware.org/?probe=b6f5c877d4) | Sep 29, 2021 |
| HP            | 86F0 11000                  | All in one  | [d94d1dcab2](https://linux-hardware.org/?probe=d94d1dcab2) | Sep 29, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [e8c44e9282](https://linux-hardware.org/?probe=e8c44e9282) | Sep 26, 2021 |
| ASRock        | N68C-GS FX                  | Desktop     | [bea6762fb6](https://linux-hardware.org/?probe=bea6762fb6) | Sep 26, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [49a6459ecf](https://linux-hardware.org/?probe=49a6459ecf) | Sep 23, 2021 |
| HONOR         | HLYL-WXX9                   | Notebook    | [f21200b164](https://linux-hardware.org/?probe=f21200b164) | Sep 23, 2021 |
| Gigabyte      | Z87P-D3                     | Desktop     | [80b6244981](https://linux-hardware.org/?probe=80b6244981) | Sep 21, 2021 |
| ASRock        | B365 Pro4                   | Desktop     | [bc0974da01](https://linux-hardware.org/?probe=bc0974da01) | Sep 19, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [d80cdfb094](https://linux-hardware.org/?probe=d80cdfb094) | Sep 19, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [9cf1061bcb](https://linux-hardware.org/?probe=9cf1061bcb) | Sep 19, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [84678f812f](https://linux-hardware.org/?probe=84678f812f) | Sep 18, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [f8bb575441](https://linux-hardware.org/?probe=f8bb575441) | Sep 16, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5505        | Notebook    | [a64387b07d](https://linux-hardware.org/?probe=a64387b07d) | Sep 15, 2021 |
| ASUSTek       | K50IJ                       | Notebook    | [01cd639b37](https://linux-hardware.org/?probe=01cd639b37) | Sep 11, 2021 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [04e9d9ef11](https://linux-hardware.org/?probe=04e9d9ef11) | Sep 10, 2021 |
| HP            | ProBook 4515s               | Notebook    | [f421481ba4](https://linux-hardware.org/?probe=f421481ba4) | Sep 09, 2021 |
| HP            | ProBook 4515s               | Notebook    | [308aea486b](https://linux-hardware.org/?probe=308aea486b) | Sep 09, 2021 |
| ASUSTek       | G71V                        | Notebook    | [7904b934a4](https://linux-hardware.org/?probe=7904b934a4) | Sep 09, 2021 |
| Samsung       | 305E4Z/305E5Z/305E7Z        | Notebook    | [248b63572e](https://linux-hardware.org/?probe=248b63572e) | Sep 08, 2021 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [07db84c018](https://linux-hardware.org/?probe=07db84c018) | Sep 07, 2021 |
| Samsung       | R508                        | Notebook    | [9e358e751b](https://linux-hardware.org/?probe=9e358e751b) | Sep 06, 2021 |
| HP            | Compaq 610                  | Notebook    | [a8792baad7](https://linux-hardware.org/?probe=a8792baad7) | Sep 03, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Belarus/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| ROSA R10                     | 123       | 8.62%   |
| ROSA R11                     | 107       | 7.5%    |
| ROSA R8.1                    | 81        | 5.68%   |
| Ubuntu 20.04                 | 64        | 4.48%   |
| ROSA R9                      | 49        | 3.43%   |
| ROSA R11.1                   | 49        | 3.43%   |
| Ubuntu 22.04                 | 40        | 2.8%    |
| Ubuntu 18.04                 | 40        | 2.8%    |
| ROSA R8                      | 38        | 2.66%   |
| Arch Rolling                 | 33        | 2.31%   |
| ROSA 12.4                    | 32        | 2.24%   |
| ROSA 12.2                    | 31        | 2.17%   |
| OpenMandriva 4.2             | 24        | 1.68%   |
| Fedora 38                    | 22        | 1.54%   |
| ROSA 12.3                    | 21        | 1.47%   |
| Manjaro                      | 21        | 1.47%   |
| Debian 12                    | 21        | 1.47%   |
| Fedora 39                    | 17        | 1.19%   |
| Debian 11                    | 17        | 1.19%   |
| ROSA 12.5.1                  | 16        | 1.12%   |
| Fedora 40                    | 16        | 1.12%   |
| Fedora 36                    | 15        | 1.05%   |
| OpenMandriva 4.3             | 13        | 0.91%   |
| Linux Mint 19.3              | 13        | 0.91%   |
| Linux Mint 20.3              | 12        | 0.84%   |
| KDE neon 20.04               | 12        | 0.84%   |
| Fedora 35                    | 12        | 0.84%   |
| openSUSE Tumbleweed-XXXXXXXX | 11        | 0.77%   |
| Linux Mint 21.1              | 11        | 0.77%   |
| Arch                         | 11        | 0.77%   |
| Fedora 34                    | 10        | 0.7%    |
| Ubuntu 24.04                 | 9         | 0.63%   |
| Kubuntu 20.04                | 9         | 0.63%   |
| Fedora 37                    | 9         | 0.63%   |
| OpenMandriva 23.03           | 8         | 0.56%   |
| Ubuntu 22.10                 | 7         | 0.49%   |
| OpenMandriva 24.07           | 7         | 0.49%   |
| OpenMandriva 23.08           | 7         | 0.49%   |
| Linux Mint 21.2              | 7         | 0.49%   |
| Linux Mint 21.3              | 6         | 0.42%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| ROSA          | 463       | 37.4%   |
| Ubuntu        | 180       | 14.54%  |
| Fedora        | 86        | 6.95%   |
| Linux Mint    | 79        | 6.38%   |
| OpenMandriva  | 69        | 5.57%   |
| Manjaro       | 53        | 4.28%   |
| Debian        | 48        | 3.88%   |
| Arch          | 43        | 3.47%   |
| Endless       | 38        | 3.07%   |
| KDE neon      | 18        | 1.45%   |
| Kubuntu       | 17        | 1.37%   |
| Xubuntu       | 14        | 1.13%   |
| openSUSE      | 13        | 1.05%   |
| Gentoo        | 11        | 0.89%   |
| Pop!_OS       | 10        | 0.81%   |
| Elementary    | 9         | 0.73%   |
| LMDE          | 8         | 0.65%   |
| ALT Linux     | 8         | 0.65%   |
| Kali          | 7         | 0.57%   |
| Zorin         | 5         | 0.4%    |
| MX            | 4         | 0.32%   |
| Lubuntu       | 4         | 0.32%   |
| ArcoLinux     | 4         | 0.32%   |
| Ubuntu MATE   | 3         | 0.24%   |
| SteamOS       | 3         | 0.24%   |
| PostmarketOS  | 3         | 0.24%   |
| Clear Linux   | 3         | 0.24%   |
| CentOS        | 3         | 0.24%   |
| BlackPanther  | 3         | 0.24%   |
| Ubuntu Unity  | 2         | 0.16%   |
| Nobara        | 2         | 0.16%   |
| NixOS         | 2         | 0.16%   |
| EndeavourOS   | 2         | 0.16%   |
| Deepin        | 2         | 0.16%   |
| CachyOS       | 2         | 0.16%   |
| Artix         | 2         | 0.16%   |
| Xero          | 1         | 0.08%   |
| Void Linux    | 1         | 0.08%   |
| Ubuntu Budgie | 1         | 0.08%   |
| Trisquel      | 1         | 0.08%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Computers | Percent |
|-------------------------------------|-----------|---------|
| 4.9.60-nrj-desktop-1rosa-x86_64     | 59        | 3.67%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 43        | 2.68%   |
| 4.9.20-nrj-desktop-1rosa-x86_64     | 39        | 2.43%   |
| 5.10.74-generic-2rosa2021.1-x86_64  | 32        | 1.99%   |
| 4.9.124-nrj-desktop-1rosa-x86_64    | 27        | 1.68%   |
| 5.10.14-desktop-1omv4002            | 23        | 1.43%   |
| 4.1.34-nrj-desktop-2rosa-x86_64     | 20        | 1.25%   |
| 4.9.155-nrj-desktop-1rosa-x86_64    | 19        | 1.18%   |
| 4.9.76-nrj-desktop-1rosa-x86_64     | 18        | 1.12%   |
| 5.4.83-generic-2rosa-x86_64         | 16        | 1%      |
| 4.1.38-nrj-desktop-2rosa-x86_64     | 16        | 1%      |
| 4.15.0-desktop-45.1rosa-i586        | 15        | 0.93%   |
| 6.1.20-generic-2rosa2021.1-x86_64   | 14        | 0.87%   |
| 5.4.0-42-generic                    | 13        | 0.81%   |
| 4.9.9-nrj-desktop-1rosa-x86_64      | 13        | 0.81%   |
| 5.16.7-desktop-1omv4003             | 12        | 0.75%   |
| 4.15.0-desktop-68.5rosa-x86_64      | 12        | 0.75%   |
| 5.15.75-generic-1rosa2021.1-x86_64  | 11        | 0.68%   |
| 5.15.0-56-generic                   | 11        | 0.68%   |
| 4.9.60-nrj-desktop-1rosa-i586       | 11        | 0.68%   |
| 4.9.41-nrj-desktop-1rosa-x86_64     | 10        | 0.62%   |
| 4.9.20-nrj-desktop-1rosa-i586       | 10        | 0.62%   |
| 4.9.9-nrj-desktop-1rosa-i586        | 9         | 0.56%   |
| 6.6.47-generic-1rosa2021.1-x86_64   | 8         | 0.5%    |
| 5.4.32-generic-2rosa-x86_64         | 8         | 0.5%    |
| 4.15.0-desktop-47.2rosa-x86_64      | 8         | 0.5%    |
| 6.4.11-desktop-1omv2390             | 7         | 0.44%   |
| 6.1.58-generic-1rosa2021.1-x86_64   | 7         | 0.44%   |
| 5.15.79-generic-1rosa2021.1-x86_64  | 7         | 0.44%   |
| 4.9.95-nrj-desktop-2rosa-x86_64     | 7         | 0.44%   |
| 4.9.155-nrj-laptop-1rosa-x86_64     | 7         | 0.44%   |
| 4.15.0-desktop-60.7rosa-x86_64      | 7         | 0.44%   |
| 4.15.0-desktop-122.124.1rosa-x86_64 | 7         | 0.44%   |
| 6.2.6-desktop-1omv2390              | 6         | 0.37%   |
| 6.2.0-26-generic                    | 6         | 0.37%   |
| 5.9.16-1-MANJARO                    | 6         | 0.37%   |
| 5.8.0-14-generic                    | 6         | 0.37%   |
| 4.9.124-nrj-desktop-1rosa-i586      | 6         | 0.37%   |
| 4.9.111-nrj-desktop-2rosa-x86_64    | 6         | 0.37%   |
| 4.1.34-nrj-desktop-2rosa-i586       | 6         | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.15.0  | 141       | 9.09%   |
| 5.4.0   | 83        | 5.35%   |
| 4.9.60  | 70        | 4.51%   |
| 5.15.0  | 49        | 3.16%   |
| 4.9.20  | 49        | 3.16%   |
| 4.9.124 | 33        | 2.13%   |
| 5.10.74 | 32        | 2.06%   |
| 5.8.0   | 31        | 2%      |
| 5.10.0  | 27        | 1.74%   |
| 4.9.155 | 27        | 1.74%   |
| 4.1.38  | 27        | 1.74%   |
| 4.1.34  | 26        | 1.68%   |
| 5.11.0  | 25        | 1.61%   |
| 5.10.14 | 23        | 1.48%   |
| 5.0.0   | 23        | 1.48%   |
| 6.5.0   | 22        | 1.42%   |
| 6.1.0   | 22        | 1.42%   |
| 4.9.9   | 22        | 1.42%   |
| 4.9.76  | 22        | 1.42%   |
| 5.13.0  | 21        | 1.35%   |
| 5.4.83  | 20        | 1.29%   |
| 5.3.0   | 20        | 1.29%   |
| 5.19.0  | 20        | 1.29%   |
| 6.2.0   | 18        | 1.16%   |
| 6.8.0   | 16        | 1.03%   |
| 6.1.20  | 14        | 0.9%    |
| 4.9.41  | 14        | 0.9%    |
| 4.18.0  | 13        | 0.84%   |
| 5.16.7  | 12        | 0.77%   |
| 5.15.75 | 12        | 0.77%   |
| 5.4.32  | 9         | 0.58%   |
| 4.19.0  | 9         | 0.58%   |
| 4.13.0  | 9         | 0.58%   |
| 6.6.47  | 8         | 0.52%   |
| 6.4.11  | 8         | 0.52%   |
| 5.9.16  | 8         | 0.52%   |
| 4.9.95  | 8         | 0.52%   |
| 6.6.27  | 7         | 0.45%   |
| 6.1.58  | 7         | 0.45%   |
| 5.15.79 | 7         | 0.45%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.9     | 216       | 15.06%  |
| 4.15    | 141       | 9.83%   |
| 5.4     | 128       | 8.93%   |
| 5.10    | 103       | 7.18%   |
| 5.15    | 97        | 6.76%   |
| 6.1     | 65        | 4.53%   |
| 4.1     | 56        | 3.91%   |
| 6.6     | 43        | 3%      |
| 6.2     | 40        | 2.79%   |
| 6.5     | 39        | 2.72%   |
| 5.8     | 39        | 2.72%   |
| 5.11    | 35        | 2.44%   |
| 5.19    | 30        | 2.09%   |
| 5.13    | 30        | 2.09%   |
| 6.8     | 29        | 2.02%   |
| 5.3     | 29        | 2.02%   |
| 5.0     | 24        | 1.67%   |
| 6.4     | 21        | 1.46%   |
| 6.11    | 20        | 1.39%   |
| 5.9     | 19        | 1.32%   |
| 5.16    | 19        | 1.32%   |
| 6.7     | 18        | 1.26%   |
| 6.10    | 16        | 1.12%   |
| 4.18    | 16        | 1.12%   |
| 6.0     | 15        | 1.05%   |
| 4.19    | 15        | 1.05%   |
| 5.18    | 14        | 0.98%   |
| 5.14    | 13        | 0.91%   |
| 6.9     | 12        | 0.84%   |
| 5.6     | 11        | 0.77%   |
| 5.17    | 10        | 0.7%    |
| 6.3     | 9         | 0.63%   |
| 4.13    | 9         | 0.63%   |
| 5.12    | 8         | 0.56%   |
| 4.8     | 7         | 0.49%   |
| 6.12    | 6         | 0.42%   |
| 4.4     | 6         | 0.42%   |
| 5.7     | 5         | 0.35%   |
| 4.14    | 5         | 0.35%   |
| 5.5     | 4         | 0.28%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1087      | 91.73%  |
| i686    | 92        | 7.76%   |
| aarch64 | 4         | 0.34%   |
| armv7l  | 2         | 0.17%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 333       | 25.98%  |
| KDE5            | 313       | 24.41%  |
| KDE4            | 281       | 21.92%  |
| Unknown         | 98        | 7.64%   |
| XFCE            | 65        | 5.07%   |
| X-Cinnamon      | 54        | 4.21%   |
| LXQt            | 32        | 2.5%    |
| KDE6            | 22        | 1.72%   |
| MATE            | 21        | 1.64%   |
| KDE             | 18        | 1.4%    |
| Cinnamon        | 11        | 0.86%   |
| Pantheon        | 8         | 0.62%   |
| LXDE            | 6         | 0.47%   |
| Unity           | 2         | 0.16%   |
| Phosh:GNOME     | 2         | 0.16%   |
| i3              | 2         | 0.16%   |
| Deepin          | 2         | 0.16%   |
| bspwm           | 2         | 0.16%   |
| Trinity         | 1         | 0.08%   |
| sway            | 1         | 0.08%   |
| Openbox         | 1         | 0.08%   |
| none+xmonad     | 1         | 0.08%   |
| Hyprland        | 1         | 0.08%   |
| GNOME Flashback | 1         | 0.08%   |
| Endless:GNOME   | 1         | 0.08%   |
| DDE             | 1         | 0.08%   |
| chadwm          | 1         | 0.08%   |
| Budgie          | 1         | 0.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 897       | 73.16%  |
| Wayland | 267       | 21.78%  |
| Unknown | 47        | 3.83%   |
| Tty     | 14        | 1.14%   |
| Web     | 1         | 0.08%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 331       | 26.06%  |
| Unknown | 314       | 24.72%  |
| KDM     | 282       | 22.2%   |
| GDM     | 144       | 11.34%  |
| LightDM | 87        | 6.85%   |
| GDM3    | 79        | 6.22%   |
| TDM     | 29        | 2.28%   |
| MDM     | 2         | 0.16%   |
| SLiM    | 1         | 0.08%   |
| GREETD  | 1         | 0.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| ru_RU       | 474       | 38.79%  |
| Unknown     | 419       | 34.29%  |
| en_US       | 257       | 21.03%  |
| C           | 20        | 1.64%   |
| be_BY       | 18        | 1.47%   |
| en_GB       | 12        | 0.98%   |
| ru_RU.UTF_8 | 6         | 0.49%   |
| ru_UA       | 4         | 0.33%   |
| ru_BY       | 4         | 0.33%   |
| cv_RU       | 2         | 0.16%   |
| zh_CN       | 1         | 0.08%   |
| fr_FR       | 1         | 0.08%   |
| en_US.UTS-8 | 1         | 0.08%   |
| en_IN       | 1         | 0.08%   |
| en_CA       | 1         | 0.08%   |
| C.utf-8     | 1         | 0.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 669       | 55.15%  |
| EFI  | 544       | 44.85%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 775       | 61.65%  |
| Unknown | 243       | 19.33%  |
| Btrfs   | 126       | 10.02%  |
| Overlay | 74        | 5.89%   |
| Tmpfs   | 20        | 1.59%   |
| Xfs     | 6         | 0.48%   |
| F2fs    | 4         | 0.32%   |
| Ext3    | 4         | 0.32%   |
| Zfs     | 2         | 0.16%   |
| Ext2    | 2         | 0.16%   |
| SAMSUNG | 1         | 0.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 477       | 37.98%  |
| Unknown | 402       | 32.01%  |
| MBR     | 377       | 30.02%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1040      | 85.25%  |
| Yes       | 180       | 14.75%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 811       | 65.72%  |
| Yes       | 423       | 34.28%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 263       | 22.46%  |
| Lenovo              | 163       | 13.92%  |
| Hewlett-Packard     | 148       | 12.64%  |
| Gigabyte Technology | 112       | 9.56%   |
| Acer                | 84        | 7.17%   |
| ASRock              | 83        | 7.09%   |
| MSI                 | 64        | 5.47%   |
| Dell                | 50        | 4.27%   |
| Samsung Electronics | 37        | 3.16%   |
| Biostar             | 17        | 1.45%   |
| Intel               | 16        | 1.37%   |
| Timi                | 11        | 0.94%   |
| Toshiba             | 10        | 0.85%   |
| HONOR               | 10        | 0.85%   |
| Unknown             | 10        | 0.85%   |
| Apple               | 8         | 0.68%   |
| Sony                | 7         | 0.6%    |
| HUAWEI              | 6         | 0.51%   |
| XIAOMI              | 5         | 0.43%   |
| Prestigio           | 5         | 0.43%   |
| Packard Bell        | 5         | 0.43%   |
| Fujitsu             | 4         | 0.34%   |
| ECS                 | 4         | 0.34%   |
| Valve               | 3         | 0.26%   |
| Fujitsu Siemens     | 3         | 0.26%   |
| TECNO               | 2         | 0.17%   |
| Nvidia              | 2         | 0.17%   |
| EPoX Computer       | 2         | 0.17%   |
| Chuwi               | 2         | 0.17%   |
| BenQ                | 2         | 0.17%   |
| ZOTAC               | 1         | 0.09%   |
| ViewSonic           | 1         | 0.09%   |
| VIA Technologies    | 1         | 0.09%   |
| Techvision          | 1         | 0.09%   |
| SYS                 | 1         | 0.09%   |
| Supermicro          | 1         | 0.09%   |
| Quanta              | 1         | 0.09%   |
| Pegatron            | 1         | 0.09%   |
| Partner             | 1         | 0.09%   |
| Olimex              | 1         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Unknown                                 | 12        | 1.02%   |
| Lenovo G50-30 80G0                      | 8         | 0.68%   |
| HP Notebook                             | 6         | 0.51%   |
| Gigabyte 970A-DS3P                      | 6         | 0.51%   |
| Timi TM1701                             | 5         | 0.43%   |
| ASRock N68C-GS FX                       | 5         | 0.43%   |
| Acer Extensa 5220                       | 5         | 0.43%   |
| Samsung RV413/RV513                     | 4         | 0.34%   |
| MSI MS-7369                             | 4         | 0.34%   |
| Lenovo IdeaPad 320-15IAP 80XR           | 4         | 0.34%   |
| HONOR NBR-WAX9                          | 4         | 0.34%   |
| HP ProBook 455 G1                       | 4         | 0.34%   |
| HP ProBook 450 G5                       | 4         | 0.34%   |
| HP Pavilion g6                          | 4         | 0.34%   |
| HP Pavilion 15                          | 4         | 0.34%   |
| HP Laptop 15s-eq2xxx                    | 4         | 0.34%   |
| ASUS X540NV                             | 4         | 0.34%   |
| ASUS P8H77-V                            | 4         | 0.34%   |
| ASUS All Series                         | 4         | 0.34%   |
| ASRock N68-VS3 UCC                      | 4         | 0.34%   |
| Acer Aspire E1-571G                     | 4         | 0.34%   |
| MSI MS-7309                             | 3         | 0.26%   |
| Lenovo IdeaPad Z570 HuronRiver Platform | 3         | 0.26%   |
| Lenovo IdeaPad S340-15IWL 81N8          | 3         | 0.26%   |
| Lenovo IdeaPad 520-15IKB 81BF           | 3         | 0.26%   |
| Lenovo IdeaPad 3 15IML05 81WB           | 3         | 0.26%   |
| Lenovo IdeaPad 100-15IBY 80MJ           | 3         | 0.26%   |
| Lenovo G580 20150                       | 3         | 0.26%   |
| Lenovo G570 20079                       | 3         | 0.26%   |
| Lenovo G500 20236                       | 3         | 0.26%   |
| Lenovo B590 20206                       | 3         | 0.26%   |
| Lenovo B50-30 20382                     | 3         | 0.26%   |
| HP Victus by Laptop 16-e0xxx            | 3         | 0.26%   |
| HP ProBook 6570b                        | 3         | 0.26%   |
| HP Pavilion dv6                         | 3         | 0.26%   |
| HP 635                                  | 3         | 0.26%   |
| Gigabyte M61SME-S2                      | 3         | 0.26%   |
| Gigabyte H81M-S2H                       | 3         | 0.26%   |
| Gigabyte GA-MA74GM-S2H                  | 3         | 0.26%   |
| Gigabyte GA-780T-D3L                    | 3         | 0.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Acer Aspire        | 55        | 4.7%    |
| Lenovo IdeaPad     | 53        | 4.53%   |
| HP ProBook         | 42        | 3.59%   |
| Lenovo ThinkPad    | 36        | 3.07%   |
| ASUS VivoBook      | 34        | 2.9%    |
| HP Pavilion        | 32        | 2.73%   |
| Dell Inspiron      | 29        | 2.48%   |
| ASUS ROG           | 14        | 1.2%    |
| Acer Extensa       | 14        | 1.2%    |
| HP Laptop          | 13        | 1.11%   |
| ASUS PRIME         | 13        | 1.11%   |
| ASUS ZenBook       | 12        | 1.02%   |
| Unknown            | 12        | 1.02%   |
| ASUS ASUS          | 10        | 0.85%   |
| HP EliteBook       | 9         | 0.77%   |
| Toshiba Satellite  | 8         | 0.68%   |
| Lenovo Legion      | 8         | 0.68%   |
| Lenovo G50-30      | 8         | 0.68%   |
| ASUS TUF           | 8         | 0.68%   |
| HP Compaq          | 7         | 0.6%    |
| Gigabyte B450M     | 7         | 0.6%    |
| Lenovo ThinkBook   | 6         | 0.51%   |
| HP Notebook        | 6         | 0.51%   |
| Gigabyte 970A-DS3P | 6         | 0.51%   |
| Timi TM1701        | 5         | 0.43%   |
| Lenovo G580        | 5         | 0.43%   |
| HP 250             | 5         | 0.43%   |
| Dell XPS           | 5         | 0.43%   |
| Dell Vostro        | 5         | 0.43%   |
| ASUS P8H77-V       | 5         | 0.43%   |
| ASRock N68C-GS     | 5         | 0.43%   |
| ASRock N68-VS3     | 5         | 0.43%   |
| Samsung RV413      | 4         | 0.34%   |
| MSI MS-7369        | 4         | 0.34%   |
| Lenovo Yoga        | 4         | 0.34%   |
| Lenovo B590        | 4         | 0.34%   |
| HONOR NBR-WAX9     | 4         | 0.34%   |
| HP Victus          | 4         | 0.34%   |
| HP 255             | 4         | 0.34%   |
| Gigabyte Z390      | 4         | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 119       | 10.16%  |
| 2013    | 106       | 9.05%   |
| 2011    | 104       | 8.88%   |
| 2018    | 102       | 8.71%   |
| 2020    | 76        | 6.49%   |
| 2017    | 73        | 6.23%   |
| 2010    | 66        | 5.64%   |
| 2021    | 62        | 5.29%   |
| 2014    | 59        | 5.04%   |
| 2019    | 58        | 4.95%   |
| 2009    | 58        | 4.95%   |
| 2007    | 52        | 4.44%   |
| 2022    | 50        | 4.27%   |
| 2015    | 48        | 4.1%    |
| 2008    | 45        | 3.84%   |
| 2016    | 36        | 3.07%   |
| 2006    | 21        | 1.79%   |
| 2023    | 16        | 1.37%   |
| 2005    | 7         | 0.6%    |
| 2024    | 6         | 0.51%   |
| Unknown | 6         | 0.51%   |
| 2003    | 1         | 0.09%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 739       | 63.11%  |
| Desktop        | 395       | 33.73%  |
| Convertible    | 10        | 0.85%   |
| All in one     | 9         | 0.77%   |
| System on chip | 5         | 0.43%   |
| Mini pc        | 5         | 0.43%   |
| Tablet         | 4         | 0.34%   |
| Server         | 3         | 0.26%   |
| Phone          | 1         | 0.09%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1123      | 95.41%  |
| Enabled  | 54        | 4.59%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1170      | 99.91%  |
| Yes  | 1         | 0.09%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 297       | 24.55%  |
| 4.01-8.0    | 270       | 22.31%  |
| 8.01-16.0   | 206       | 17.02%  |
| 16.01-24.0  | 188       | 15.54%  |
| 1.01-2.0    | 93        | 7.69%   |
| 32.01-64.0  | 70        | 5.79%   |
| 2.01-3.0    | 46        | 3.8%    |
| 0.51-1.0    | 22        | 1.82%   |
| 24.01-32.0  | 10        | 0.83%   |
| 64.01-256.0 | 7         | 0.58%   |
| 0.01-0.5    | 1         | 0.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 439       | 32.21%  |
| 0.51-1.0   | 279       | 20.47%  |
| 2.01-3.0   | 257       | 18.86%  |
| 4.01-8.0   | 174       | 12.77%  |
| 3.01-4.0   | 140       | 10.27%  |
| 8.01-16.0  | 39        | 2.86%   |
| 0.01-0.5   | 25        | 1.83%   |
| 16.01-24.0 | 6         | 0.44%   |
| 24.01-32.0 | 2         | 0.15%   |
| 32.01-64.0 | 1         | 0.07%   |
| Unknown    | 1         | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 773       | 63.26%  |
| 2      | 313       | 25.61%  |
| 3      | 89        | 7.28%   |
| 4      | 24        | 1.96%   |
| 5      | 13        | 1.06%   |
| 0      | 6         | 0.49%   |
| 9      | 2         | 0.16%   |
| 8      | 1         | 0.08%   |
| 6      | 1         | 0.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 729       | 61.47%  |
| Yes       | 457       | 38.53%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1006      | 85.84%  |
| No        | 166       | 14.16%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 878       | 74.47%  |
| No        | 301       | 25.53%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 679       | 57.06%  |
| No        | 511       | 42.94%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Belarus | 1171      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Computers | Percent |
|--------------|-----------|---------|
| Minsk        | 577       | 44.62%  |
| Vitebsk      | 123       | 9.51%   |
| Gomel        | 118       | 9.13%   |
| Mogilev      | 73        | 5.65%   |
| Brest        | 69        | 5.34%   |
| Hrodna       | 66        | 5.1%    |
| Babruysk     | 24        | 1.86%   |
| Orsha        | 19        | 1.47%   |
| Polatsk      | 17        | 1.31%   |
| Borisov      | 15        | 1.16%   |
| Mazyr        | 11        | 0.85%   |
| Baranovichi  | 11        | 0.85%   |
| Lida         | 9         | 0.7%    |
| Zhodzina     | 7         | 0.54%   |
| Zhlobin      | 7         | 0.54%   |
| Slutsk       | 7         | 0.54%   |
| Navapolatsk  | 7         | 0.54%   |
| Bogushevichi | 7         | 0.54%   |
| Pinsk        | 6         | 0.46%   |
| Vawkavysk    | 5         | 0.39%   |
| Salihorsk    | 5         | 0.39%   |
| Klyetsk      | 5         | 0.39%   |
| Drahichyn    | 5         | 0.39%   |
| Smalyavichy  | 4         | 0.31%   |
| Pastavy      | 4         | 0.31%   |
| Syanno       | 3         | 0.23%   |
| Slonim       | 3         | 0.23%   |
| Rahachow     | 3         | 0.23%   |
| Ivanava      | 3         | 0.23%   |
| Fedorovka    | 3         | 0.23%   |
| Fanipol      | 3         | 0.23%   |
| Dubovka      | 3         | 0.23%   |
| Baran'       | 3         | 0.23%   |
| Aleksandrovo | 3         | 0.23%   |
| Svyetlahorsk | 2         | 0.15%   |
| Snitovo      | 2         | 0.15%   |
| Rechytsa     | 2         | 0.15%   |
| Pruzhany     | 2         | 0.15%   |
| Ogorodniki   | 2         | 0.15%   |
| Navahrudak   | 2         | 0.15%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 251       | 414    | 15.07%  |
| Seagate                     | 246       | 399    | 14.77%  |
| Samsung Electronics         | 228       | 334    | 13.69%  |
| Toshiba                     | 161       | 260    | 9.66%   |
| Kingston                    | 111       | 157    | 6.66%   |
| Hitachi                     | 96        | 130    | 5.76%   |
| HGST                        | 58        | 95     | 3.48%   |
| SK hynix                    | 44        | 53     | 2.64%   |
| Intel                       | 38        | 85     | 2.28%   |
| Crucial                     | 37        | 46     | 2.22%   |
| Sandisk                     | 36        | 47     | 2.16%   |
| Unknown                     | 34        | 44     | 2.04%   |
| Micron Technology           | 28        | 35     | 1.68%   |
| Patriot                     | 23        | 32     | 1.38%   |
| Netac                       | 15        | 19     | 0.9%    |
| Gigabyte Technology         | 15        | 19     | 0.9%    |
| KingSpec                    | 14        | 25     | 0.84%   |
| A-DATA Technology           | 14        | 17     | 0.84%   |
| OCZ                         | 13        | 15     | 0.78%   |
| SPCC                        | 12        | 18     | 0.72%   |
| Fujitsu                     | 12        | 19     | 0.72%   |
| KIOXIA                      | 11        | 41     | 0.66%   |
| Transcend                   | 10        | 12     | 0.6%    |
| GOODRAM                     | 10        | 11     | 0.6%    |
| China                       | 10        | 13     | 0.6%    |
| APACER                      | 10        | 13     | 0.6%    |
| Silicon Motion              | 9         | 10     | 0.54%   |
| Plextor                     | 6         | 7      | 0.36%   |
| Phison Electronics          | 6         | 9      | 0.36%   |
| Kingston Technology Company | 6         | 6      | 0.36%   |
| Maxtor                      | 5         | 5      | 0.3%    |
| KingDian                    | 4         | 6      | 0.24%   |
| JMicron Technology          | 4         | 4      | 0.24%   |
| Apple                       | 4         | 4      | 0.24%   |
| XrayDisk                    | 3         | 3      | 0.18%   |
| XPG                         | 3         | 3      | 0.18%   |
| Smartbuy                    | 3         | 4      | 0.18%   |
| Phison                      | 3         | 3      | 0.18%   |
| Lenovo                      | 3         | 6      | 0.18%   |
| External                    | 3         | 4      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB                            | 28        | 1.55%   |
| Toshiba DT01ACA050 500GB                            | 23        | 1.28%   |
| Kingston SA400S37120G 120GB SSD                     | 23        | 1.28%   |
| Seagate ST1000LM035-1RK172 1TB                      | 22        | 1.22%   |
| Toshiba DT01ACA100 1TB                              | 20        | 1.11%   |
| Seagate ST500LT012-1DG142 500GB                     | 19        | 1.05%   |
| Samsung SSD 860 EVO 500GB                           | 18        | 1%      |
| Samsung SSD 860 EVO 250GB                           | 18        | 1%      |
| Toshiba DT01ACA200 2TB                              | 14        | 0.78%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 14        | 0.78%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 14        | 0.78%   |
| Kingston SA400S37240G 240GB SSD                     | 14        | 0.78%   |
| HGST HTS545050A7E680 500GB                          | 12        | 0.67%   |
| Crucial CT120BX500SSD1 120GB                        | 11        | 0.61%   |
| Seagate ST9320325AS 320GB                           | 10        | 0.56%   |
| Seagate ST500DM002-1BD142 500GB                     | 10        | 0.56%   |
| Samsung SSD 850 EVO 250GB                           | 10        | 0.56%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 9         | 0.5%    |
| Toshiba MQ04ABF100 1TB                              | 9         | 0.5%    |
| Toshiba MQ01ABD100 1TB                              | 9         | 0.5%    |
| Seagate ST2000DM008-2FR102 2TB                      | 9         | 0.5%    |
| Samsung NVMe SSD Drive 256GB                        | 9         | 0.5%    |
| Hitachi HTS543232A7A384 320GB                       | 9         | 0.5%    |
| HGST HTS721010A9E630 1TB                            | 9         | 0.5%    |
| Toshiba MQ01ABD032 320GB                            | 8         | 0.44%   |
| Toshiba HDWD110 1TB                                 | 8         | 0.44%   |
| SK hynix NVMe SSD Drive 512GB                       | 8         | 0.44%   |
| WDC WD10EZRZ-00HTKB0 1TB                            | 7         | 0.39%   |
| Seagate ST9500325AS 500GB                           | 7         | 0.39%   |
| Kingston SUV400S37120G 120GB SSD                    | 7         | 0.39%   |
| Intel SSDPEKNU512GZ 512GB                           | 7         | 0.39%   |
| Hitachi HTS545050B9A300 500GB                       | 7         | 0.39%   |
| HGST HTS541010A9E680 1TB                            | 7         | 0.39%   |
| Gigabyte GP-GSTFS31120GNTD 120GB                    | 7         | 0.39%   |
| Unknown MMC Card  32GB                              | 6         | 0.33%   |
| Toshiba MQ01ABD075 752GB                            | 6         | 0.33%   |
| Seagate ST9250315AS 250GB                           | 6         | 0.33%   |
| Samsung SSD 850 EVO 500GB                           | 6         | 0.33%   |
| Patriot Burst 120GB SSD                             | 6         | 0.33%   |
| OCZ VERTEX4 128GB SSD                               | 6         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 245       | 397    | 28.52%  |
| WDC                 | 227       | 353    | 26.43%  |
| Toshiba             | 150       | 242    | 17.46%  |
| Hitachi             | 96        | 130    | 11.18%  |
| HGST                | 58        | 95     | 6.75%   |
| Samsung Electronics | 51        | 79     | 5.94%   |
| Fujitsu             | 12        | 19     | 1.4%    |
| Maxtor              | 5         | 5      | 0.58%   |
| JMicron Technology  | 4         | 4      | 0.47%   |
| External            | 3         | 4      | 0.35%   |
| WD MediaMax         | 2         | 2      | 0.23%   |
| TO Exter            | 2         | 3      | 0.23%   |
| Unknown             | 1         | 1      | 0.12%   |
| SINTECHI            | 1         | 1      | 0.12%   |
| SAGE                | 1         | 1      | 0.12%   |
| Apple               | 1         | 1      | 0.12%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 90        | 131    | 19.74%  |
| Kingston            | 84        | 121    | 18.42%  |
| Crucial             | 35        | 44     | 7.68%   |
| Patriot             | 20        | 29     | 4.39%   |
| WDC                 | 16        | 42     | 3.51%   |
| SanDisk             | 16        | 25     | 3.51%   |
| KingSpec            | 14        | 25     | 3.07%   |
| OCZ                 | 13        | 15     | 2.85%   |
| Gigabyte Technology | 12        | 16     | 2.63%   |
| SPCC                | 11        | 17     | 2.41%   |
| Netac               | 11        | 14     | 2.41%   |
| Intel               | 11        | 13     | 2.41%   |
| Transcend           | 10        | 12     | 2.19%   |
| China               | 10        | 13     | 2.19%   |
| Apacer              | 10        | 13     | 2.19%   |
| A-DATA Technology   | 10        | 12     | 2.19%   |
| GOODRAM             | 9         | 10     | 1.97%   |
| SK hynix            | 8         | 11     | 1.75%   |
| Plextor             | 6         | 7      | 1.32%   |
| Toshiba             | 4         | 4      | 0.88%   |
| KingDian            | 4         | 6      | 0.88%   |
| XrayDisk            | 3         | 3      | 0.66%   |
| Unknown             | 3         | 3      | 0.66%   |
| Smartbuy            | 3         | 4      | 0.66%   |
| Team                | 2         | 2      | 0.44%   |
| Seagate             | 2         | 2      | 0.44%   |
| PNY                 | 2         | 6      | 0.44%   |
| Micron Technology   | 2         | 2      | 0.44%   |
| LITEONIT            | 2         | 2      | 0.44%   |
| Lexar               | 2         | 2      | 0.44%   |
| Corsair             | 2         | 8      | 0.44%   |
| Azerty              | 2         | 2      | 0.44%   |
| AMD                 | 2         | 2      | 0.44%   |
| AGI                 | 2         | 4      | 0.44%   |
| Acer                | 2         | 5      | 0.44%   |
| Zheino              | 1         | 2      | 0.22%   |
| USB3.0              | 1         | 1      | 0.22%   |
| Union Memory        | 1         | 1      | 0.22%   |
| T-FORCE             | 1         | 1      | 0.22%   |
| OSCOO               | 1         | 1      | 0.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 746       | 1337   | 49.6%   |
| SSD     | 408       | 656    | 27.13%  |
| NVMe    | 312       | 482    | 20.74%  |
| MMC     | 32        | 44     | 2.13%   |
| Unknown | 6         | 6      | 0.4%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 924       | 1966   | 71.35%  |
| NVMe | 312       | 481    | 24.09%  |
| MMC  | 32        | 44     | 2.47%   |
| SAS  | 27        | 34     | 2.08%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 754       | 1298   | 65.34%  |
| 0.51-1.0   | 304       | 487    | 26.34%  |
| 1.01-2.0   | 61        | 136    | 5.29%   |
| 2.01-3.0   | 11        | 23     | 0.95%   |
| 3.01-4.0   | 10        | 13     | 0.87%   |
| 4.01-10.0  | 10        | 31     | 0.87%   |
| 10.01-20.0 | 4         | 5      | 0.35%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 328       | 25%     |
| 251-500        | 304       | 23.17%  |
| 501-1000       | 179       | 13.64%  |
| 1-20           | 135       | 10.29%  |
| 51-100         | 115       | 8.77%   |
| 1001-2000      | 92        | 7.01%   |
| 21-50          | 78        | 5.95%   |
| More than 3000 | 31        | 2.36%   |
| Unknown        | 31        | 2.36%   |
| 2001-3000      | 19        | 1.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 577       | 42.96%  |
| 21-50          | 212       | 15.79%  |
| 101-250        | 157       | 11.69%  |
| 51-100         | 142       | 10.57%  |
| 251-500        | 108       | 8.04%   |
| 501-1000       | 68        | 5.06%   |
| Unknown        | 31        | 2.31%   |
| 1001-2000      | 27        | 2.01%   |
| More than 3000 | 10        | 0.74%   |
| 2001-3000      | 10        | 0.74%   |
| 0              | 1         | 0.07%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB    | 8         | 10     | 2.69%   |
| Seagate ST9320325AS 320GB          | 7         | 8      | 2.36%   |
| HGST HTS545050A7E680 500GB         | 7         | 9      | 2.36%   |
| Toshiba DT01ACA100 1TB             | 6         | 7      | 2.02%   |
| Toshiba MQ01ABF050 500GB           | 5         | 6      | 1.68%   |
| Seagate ST9500325AS 500GB          | 5         | 7      | 1.68%   |
| Seagate ST9250315AS 250GB          | 4         | 4      | 1.35%   |
| Seagate ST500LT012-9WS142 500GB    | 4         | 4      | 1.35%   |
| Seagate ST500DM002-1BD142 500GB    | 4         | 11     | 1.35%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 4         | 5      | 1.35%   |
| Hitachi HTS545050B9A300 500GB      | 4         | 5      | 1.35%   |
| Hitachi HDS721010CLA330 1TB        | 4         | 6      | 1.35%   |
| Hitachi HDP725050GLA360 500GB      | 4         | 8      | 1.35%   |
| WDC WD20EARS-00MVWB0 2TB           | 3         | 6      | 1.01%   |
| WDC WD10JPVX-22JC3T0 1TB           | 3         | 3      | 1.01%   |
| Toshiba MQ01ABD032 320GB           | 3         | 3      | 1.01%   |
| Toshiba DT01ACA200 2TB             | 3         | 5      | 1.01%   |
| Seagate ST9500420AS 500GB          | 3         | 3      | 1.01%   |
| Samsung Electronics HD160JJ 160GB  | 3         | 3      | 1.01%   |
| Hitachi HTS547575A9E384 752GB      | 3         | 3      | 1.01%   |
| Hitachi HTS545032B9A300 320GB      | 3         | 3      | 1.01%   |
| Hitachi HTS543232A7A384 320GB      | 3         | 4      | 1.01%   |
| HGST HTS545050A7E380 500GB         | 3         | 3      | 1.01%   |
| WDC WD5000AAKS-00A7B0 500GB        | 2         | 2      | 0.67%   |
| WDC WD3200BPVT-35ZEST0 320GB       | 2         | 6      | 0.67%   |
| WDC WD3200BEKT-60F3T1 320GB        | 2         | 2      | 0.67%   |
| WDC WD30EFRX-68EUZN0 3TB           | 2         | 3      | 0.67%   |
| Toshiba MK3259GSXP 320GB           | 2         | 3      | 0.67%   |
| Seagate STM3500418AS 500GB         | 2         | 2      | 0.67%   |
| Seagate ST9120822AS 120GB          | 2         | 3      | 0.67%   |
| Seagate ST3500320AS 500GB          | 2         | 3      | 0.67%   |
| Seagate ST340016A 40GB             | 2         | 3      | 0.67%   |
| Seagate ST3250820AS 250GB          | 2         | 2      | 0.67%   |
| Seagate ST3160812A 160GB           | 2         | 4      | 0.67%   |
| Seagate ST2000DM001-1CH164 2TB     | 2         | 2      | 0.67%   |
| Samsung Electronics SP0802N 80GB   | 2         | 2      | 0.67%   |
| Samsung Electronics HD161HJ 160GB  | 2         | 3      | 0.67%   |
| Samsung Electronics HD103SJ 1TB    | 2         | 2      | 0.67%   |
| OCZ VERTEX460A 120GB SSD           | 2         | 3      | 0.67%   |
| OCZ VERTEX4 128GB SSD              | 2         | 2      | 0.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 71        | 96     | 24.57%  |
| WDC                 | 62        | 79     | 21.45%  |
| Hitachi             | 52        | 69     | 17.99%  |
| Toshiba             | 27        | 36     | 9.34%   |
| Samsung Electronics | 22        | 32     | 7.61%   |
| HGST                | 15        | 17     | 5.19%   |
| OCZ                 | 6         | 7      | 2.08%   |
| Kingston            | 6         | 6      | 2.08%   |
| Fujitsu             | 6         | 8      | 2.08%   |
| SK hynix            | 3         | 4      | 1.04%   |
| Maxtor              | 3         | 3      | 1.04%   |
| Crucial             | 3         | 3      | 1.04%   |
| WD MediaMax         | 2         | 2      | 0.69%   |
| SanDisk             | 1         | 1      | 0.35%   |
| PNY                 | 1         | 4      | 0.35%   |
| OCZ-VERTEX3         | 1         | 3      | 0.35%   |
| Micron Technology   | 1         | 1      | 0.35%   |
| LITEONIT            | 1         | 1      | 0.35%   |
| KingSpec            | 1         | 6      | 0.35%   |
| Intel               | 1         | 1      | 0.35%   |
| Corsair             | 1         | 4      | 0.35%   |
| Apacer              | 1         | 1      | 0.35%   |
| A-DATA Technology   | 1         | 1      | 0.35%   |
| Unknown             | 1         | 1      | 0.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 71        | 96     | 27.52%  |
| WDC                 | 62        | 79     | 24.03%  |
| Hitachi             | 52        | 69     | 20.16%  |
| Toshiba             | 27        | 36     | 10.47%  |
| Samsung Electronics | 20        | 30     | 7.75%   |
| HGST                | 15        | 17     | 5.81%   |
| Fujitsu             | 6         | 8      | 2.33%   |
| Maxtor              | 3         | 3      | 1.16%   |
| WD MediaMax         | 2         | 2      | 0.78%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 237       | 340    | 88.43%  |
| SSD  | 28        | 43     | 10.45%  |
| NVMe | 3         | 3      | 1.12%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD5000BPVT-80HXZT3 500GB        | 1         | 1      | 10%     |
| WDC WD3200BEVT-22ZCT0 320GB         | 1         | 1      | 10%     |
| Seagate ST500LT012-1DG142 500GB     | 1         | 1      | 10%     |
| Seagate ST320LM001 HN-M320MBB 320GB | 1         | 1      | 10%     |
| Samsung Electronics SP0802N 80GB    | 1         | 1      | 10%     |
| Samsung Electronics HM500JI 500GB   | 1         | 1      | 10%     |
| Samsung Electronics HD252HJ 250GB   | 1         | 1      | 10%     |
| Maxtor STM380211AS 80GB             | 1         | 1      | 10%     |
| Hitachi HTS545050A7E380 500GB       | 1         | 1      | 10%     |
| HGST HTS545050B7E660 500GB          | 1         | 1      | 10%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 30%     |
| WDC                 | 2         | 2      | 20%     |
| Seagate             | 2         | 2      | 20%     |
| Maxtor              | 1         | 1      | 10%     |
| Hitachi             | 1         | 1      | 10%     |
| HGST                | 1         | 1      | 10%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 694       | 1428   | 51.41%  |
| Detected | 381       | 701    | 28.22%  |
| Malfunc  | 265       | 386    | 19.63%  |
| Failed   | 10        | 10     | 0.74%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 743       | 52.58%  |
| AMD                                     | 252       | 17.83%  |
| Samsung Electronics                     | 98        | 6.94%   |
| Nvidia                                  | 55        | 3.89%   |
| SK hynix                                | 35        | 2.48%   |
| SanDisk                                 | 33        | 2.34%   |
| Kingston Technology Company             | 33        | 2.34%   |
| Micron Technology                       | 27        | 1.91%   |
| JMicron Technology                      | 21        | 1.49%   |
| Phison Electronics                      | 14        | 0.99%   |
| Silicon Motion                          | 13        | 0.92%   |
| ASMedia Technology                      | 12        | 0.85%   |
| Marvell Technology Group                | 11        | 0.78%   |
| KIOXIA                                  | 11        | 0.78%   |
| Toshiba America Info Systems            | 10        | 0.71%   |
| VIA Technologies                        | 7         | 0.5%    |
| Netac Technology                        | 5         | 0.35%   |
| Silicon Integrated Systems [SiS]        | 4         | 0.28%   |
| Realtek Semiconductor                   | 3         | 0.21%   |
| Lenovo                                  | 3         | 0.21%   |
| ADATA Technology                        | 3         | 0.21%   |
| Yangtze Memory Technologies             | 2         | 0.14%   |
| Shenzhen Unionmemory Information System | 2         | 0.14%   |
| Shenzhen Longsys Electronics            | 2         | 0.14%   |
| MAXIO Technology (Hangzhou)             | 2         | 0.14%   |
| Broadcom / LSI                          | 2         | 0.14%   |
| Apple                                   | 2         | 0.14%   |
| Synopsys                                | 1         | 0.07%   |
| Solid State Storage Technology          | 1         | 0.07%   |
| Silicon Image                           | 1         | 0.07%   |
| O2 Micro                                | 1         | 0.07%   |
| Micron/Crucial Technology               | 1         | 0.07%   |
| Integrated Technology Express           | 1         | 0.07%   |
| Hosin Global Electronics                | 1         | 0.07%   |
| Biwin Storage Technology                | 1         | 0.07%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 129       | 7.6%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 77        | 4.53%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 54        | 3.18%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 51        | 3%      |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 50        | 2.94%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 43        | 2.53%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 39        | 2.3%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 39        | 2.3%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 36        | 2.12%   |
| Nvidia MCP61 SATA Controller                                                            | 35        | 2.06%   |
| Nvidia MCP61 IDE                                                                        | 35        | 2.06%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 33        | 1.94%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 33        | 1.94%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 29        | 1.71%   |
| AMD 400 Series Chipset SATA Controller                                                  | 29        | 1.71%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 28        | 1.65%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 26        | 1.53%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 23        | 1.35%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 22        | 1.3%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 20        | 1.18%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 20        | 1.18%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 19        | 1.12%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 18        | 1.06%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 18        | 1.06%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 16        | 0.94%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 15        | 0.88%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 15        | 0.88%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 15        | 0.88%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 15        | 0.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 15        | 0.88%   |
| Intel SSD 660P Series                                                                   | 14        | 0.82%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 14        | 0.82%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 13        | 0.77%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 13        | 0.77%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 13        | 0.77%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 13        | 0.77%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 13        | 0.77%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 13        | 0.77%   |
| AMD FCH IDE Controller                                                                  | 13        | 0.77%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 12        | 0.71%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 848       | 57.49%  |
| NVMe | 313       | 21.22%  |
| IDE  | 256       | 17.36%  |
| RAID | 57        | 3.86%   |
| SCSI | 1         | 0.07%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 810       | 69.17%  |
| AMD    | 355       | 30.32%  |
| ARM    | 6         | 0.51%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 17        | 1.44%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 16        | 1.36%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 12        | 1.02%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 12        | 1.02%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 10        | 0.85%   |
| AMD E-450 APU with Radeon HD Graphics         | 10        | 0.85%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 9         | 0.76%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 9         | 0.76%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 8         | 0.68%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 8         | 0.68%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 8         | 0.68%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 8         | 0.68%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 8         | 0.68%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 7         | 0.59%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 7         | 0.59%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 7         | 0.59%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 7         | 0.59%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 7         | 0.59%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 7         | 0.59%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 7         | 0.59%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 6         | 0.51%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 6         | 0.51%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 6         | 0.51%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 6         | 0.51%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 6         | 0.51%   |
| Intel Atom CPU N455 @ 1.66GHz                 | 6         | 0.51%   |
| AMD Ryzen 5 3600 6-Core Processor             | 6         | 0.51%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 6         | 0.51%   |
| AMD Athlon II X2 245 Processor                | 6         | 0.51%   |
| AMD Athlon II X2 240 Processor                | 6         | 0.51%   |
| AMD Athlon 64 X2 Dual Core Processor 5600+    | 6         | 0.51%   |
| AMD A4-4300M APU with Radeon HD Graphics      | 6         | 0.51%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 5         | 0.42%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 5         | 0.42%   |
| Intel Pentium CPU N3700 @ 1.60GHz             | 5         | 0.42%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 5         | 0.42%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 5         | 0.42%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 5         | 0.42%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 5         | 0.42%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 5         | 0.42%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 185       | 15.73%  |
| Intel Core i7           | 124       | 10.54%  |
| Intel Celeron           | 95        | 8.08%   |
| Intel Core i3           | 90        | 7.65%   |
| Other                   | 81        | 6.89%   |
| AMD Ryzen 5             | 71        | 6.04%   |
| Intel Pentium           | 68        | 5.78%   |
| Intel Core 2 Duo        | 49        | 4.17%   |
| AMD Ryzen 7             | 44        | 3.74%   |
| Intel Atom              | 39        | 3.32%   |
| AMD FX                  | 25        | 2.13%   |
| AMD Athlon 64 X2        | 25        | 2.13%   |
| AMD Athlon II X2        | 24        | 2.04%   |
| Intel Pentium Dual-Core | 17        | 1.45%   |
| AMD Ryzen 3             | 17        | 1.45%   |
| Intel Xeon              | 16        | 1.36%   |
| AMD A4                  | 14        | 1.19%   |
| AMD E                   | 13        | 1.11%   |
| AMD A6                  | 12        | 1.02%   |
| AMD Athlon II X3        | 11        | 0.94%   |
| AMD Phenom II X4        | 10        | 0.85%   |
| AMD A10                 | 10        | 0.85%   |
| AMD E1                  | 9         | 0.77%   |
| AMD A8                  | 9         | 0.77%   |
| Intel Pentium Dual      | 8         | 0.68%   |
| Intel Pentium Silver    | 7         | 0.6%    |
| Intel Genuine           | 7         | 0.6%    |
| Intel Core i9           | 7         | 0.6%    |
| AMD Athlon              | 7         | 0.6%    |
| Intel Pentium 4         | 5         | 0.43%   |
| Intel Celeron Dual-Core | 5         | 0.43%   |
| AMD Athlon X4           | 5         | 0.43%   |
| AMD Athlon II X4        | 5         | 0.43%   |
| AMD Athlon II           | 5         | 0.43%   |
| Intel Core 2            | 4         | 0.34%   |
| AMD Turion II           | 4         | 0.34%   |
| AMD E2                  | 4         | 0.34%   |
| Intel Core 2 Solo       | 3         | 0.26%   |
| Intel Core 2 Quad       | 3         | 0.26%   |
| AMD Ryzen 9             | 3         | 0.26%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 541       | 45.58%  |
| 4       | 329       | 27.72%  |
| 6       | 100       | 8.42%   |
| 8       | 70        | 5.9%    |
| 1       | 57        | 4.8%    |
| Unknown | 37        | 3.12%   |
| 3       | 19        | 1.6%    |
| 10      | 13        | 1.1%    |
| 12      | 11        | 0.93%   |
| 14      | 8         | 0.67%   |
| 24      | 1         | 0.08%   |
| 16      | 1         | 0.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1166      | 99.57%  |
| 2       | 3         | 0.26%   |
| Unknown | 2         | 0.17%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 641       | 53.87%  |
| 1       | 512       | 43.03%  |
| Unknown | 37        | 3.11%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1134      | 96.68%  |
| Unknown        | 22        | 1.88%   |
| 32-bit         | 17        | 1.45%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 319       | 25.96%  |
| 0x206a7    | 76        | 6.18%   |
| 0x306a9    | 65        | 5.29%   |
| 0x1067a    | 48        | 3.91%   |
| 0x010000c8 | 41        | 3.34%   |
| 0x306c3    | 38        | 3.09%   |
| 0x806ea    | 27        | 2.2%    |
| 0x806c1    | 24        | 1.95%   |
| 0x30678    | 23        | 1.87%   |
| 0x906ea    | 22        | 1.79%   |
| 0x06001119 | 19        | 1.55%   |
| 0x806ec    | 18        | 1.46%   |
| 0x40651    | 18        | 1.46%   |
| 0x106ca    | 17        | 1.38%   |
| 0x6fd      | 16        | 1.3%    |
| 0x406e3    | 16        | 1.3%    |
| 0x906e9    | 14        | 1.14%   |
| 0x05000119 | 14        | 1.14%   |
| 0x010000c7 | 13        | 1.06%   |
| 0x506e3    | 12        | 0.98%   |
| 0x506c9    | 12        | 0.98%   |
| 0x306d4    | 12        | 0.98%   |
| 0x0a50000c | 12        | 0.98%   |
| 0x806e9    | 11        | 0.9%    |
| 0x706a1    | 10        | 0.81%   |
| 0x10676    | 10        | 0.81%   |
| 0x08608103 | 10        | 0.81%   |
| 0x08108102 | 10        | 0.81%   |
| 0x06000852 | 10        | 0.81%   |
| 0x10661    | 9         | 0.73%   |
| 0x0800820d | 9         | 0.73%   |
| 0x406c4    | 8         | 0.65%   |
| 0x20652    | 8         | 0.65%   |
| 0x106c2    | 8         | 0.65%   |
| 0x08600106 | 8         | 0.65%   |
| 0x08600104 | 8         | 0.65%   |
| 0x03000027 | 8         | 0.65%   |
| 0x706e5    | 7         | 0.57%   |
| 0x6fb      | 7         | 0.57%   |
| 0x406c3    | 7         | 0.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KabyLake          | 153       | 13%     |
| IvyBridge         | 89        | 7.56%   |
| SandyBridge       | 88        | 7.48%   |
| K10               | 72        | 6.12%   |
| Haswell           | 72        | 6.12%   |
| Penryn            | 68        | 5.78%   |
| Unknown           | 58        | 4.93%   |
| Core              | 45        | 3.82%   |
| Silvermont        | 43        | 3.65%   |
| Piledriver        | 43        | 3.65%   |
| Skylake           | 37        | 3.14%   |
| Zen 3             | 33        | 2.8%    |
| K8 Hammer         | 32        | 2.72%   |
| Zen+              | 31        | 2.63%   |
| TigerLake         | 31        | 2.63%   |
| Bonnell           | 31        | 2.63%   |
| Zen 2             | 29        | 2.46%   |
| Zen               | 22        | 1.87%   |
| Alderlake Hybrid  | 21        | 1.78%   |
| Goldmont plus     | 18        | 1.53%   |
| Bobcat            | 18        | 1.53%   |
| Westmere          | 17        | 1.44%   |
| IceLake           | 17        | 1.44%   |
| Goldmont          | 15        | 1.27%   |
| Broadwell         | 14        | 1.19%   |
| CometLake         | 13        | 1.1%    |
| K10 Llano         | 11        | 0.93%   |
| Excavator         | 10        | 0.85%   |
| NetBurst          | 7         | 0.59%   |
| Puma              | 6         | 0.51%   |
| Nehalem           | 6         | 0.51%   |
| Jaguar            | 6         | 0.51%   |
| P6                | 5         | 0.42%   |
| Bulldozer         | 5         | 0.42%   |
| Tremont           | 4         | 0.34%   |
| Steamroller       | 4         | 0.34%   |
| Meteorlake Hybrid | 2         | 0.17%   |
| K8 & K10 hybrid   | 1         | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 633       | 43.81%  |
| Nvidia                           | 474       | 32.8%   |
| AMD                              | 331       | 22.91%  |
| Silicon Integrated Systems [SiS] | 3         | 0.21%   |
| ASPEED Technology                | 2         | 0.14%   |
| Matrox Electronics Systems       | 1         | 0.07%   |
| ATI Technologies                 | 1         | 0.07%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 69        | 4.55%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 58        | 3.83%   |
| Intel UHD Graphics 620                                                                   | 33        | 2.18%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 27        | 1.78%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 27        | 1.78%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 26        | 1.72%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 26        | 1.72%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 21        | 1.39%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 20        | 1.32%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 18        | 1.19%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 18        | 1.19%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 18        | 1.19%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 17        | 1.12%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 17        | 1.12%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 16        | 1.06%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 16        | 1.06%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 16        | 1.06%   |
| Intel HD Graphics 630                                                                    | 15        | 0.99%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 15        | 0.99%   |
| AMD Lucienne                                                                             | 15        | 0.99%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 14        | 0.92%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 14        | 0.92%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 14        | 0.92%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 14        | 0.92%   |
| Nvidia GP108M [GeForce MX150]                                                            | 13        | 0.86%   |
| Intel HD Graphics 620                                                                    | 13        | 0.86%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 13        | 0.86%   |
| Nvidia G92 [GeForce 9800 GT]                                                             | 12        | 0.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 12        | 0.79%   |
| Intel HD Graphics 5500                                                                   | 12        | 0.79%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 12        | 0.79%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 12        | 0.79%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 12        | 0.79%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 11        | 0.73%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 10        | 0.66%   |
| Intel HD Graphics 500                                                                    | 10        | 0.66%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 10        | 0.66%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 9         | 0.59%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 9         | 0.59%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 9         | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 386       | 32.8%   |
| 1 x Nvidia      | 252       | 21.41%  |
| 1 x AMD         | 226       | 19.2%   |
| Intel + Nvidia  | 194       | 16.48%  |
| Intel + AMD     | 46        | 3.91%   |
| 2 x AMD         | 35        | 2.97%   |
| AMD + Nvidia    | 24        | 2.04%   |
| Other           | 6         | 0.51%   |
| 1 x SiS         | 3         | 0.25%   |
| 2 x Nvidia      | 1         | 0.08%   |
| 2 x Intel       | 1         | 0.08%   |
| Nvidia + ASPEED | 1         | 0.08%   |
| 1 x Matrox      | 1         | 0.08%   |
| 1 x ASPEED      | 1         | 0.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 939       | 77.73%  |
| Proprietary | 208       | 17.22%  |
| Unknown     | 61        | 5.05%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 487       | 39.69%  |
| 1.01-2.0   | 261       | 21.27%  |
| 0.01-0.5   | 248       | 20.21%  |
| 0.51-1.0   | 110       | 8.96%   |
| 3.01-4.0   | 71        | 5.79%   |
| 7.01-8.0   | 21        | 1.71%   |
| 5.01-6.0   | 17        | 1.39%   |
| 8.01-16.0  | 6         | 0.49%   |
| 2.01-3.0   | 5         | 0.41%   |
| 4.01-5.0   | 1         | 0.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 192       | 15.67%  |
| AU Optronics            | 157       | 12.82%  |
| Goldstar                | 123       | 10.04%  |
| BOE                     | 118       | 9.63%   |
| Chimei Innolux          | 103       | 8.41%   |
| LG Display              | 101       | 8.24%   |
| Chi Mei Optoelectronics | 53        | 4.33%   |
| Philips                 | 51        | 4.16%   |
| Dell                    | 43        | 3.51%   |
| BenQ                    | 30        | 2.45%   |
| AOC                     | 30        | 2.45%   |
| ViewSonic               | 20        | 1.63%   |
| PANDA                   | 20        | 1.63%   |
| Hewlett-Packard         | 15        | 1.22%   |
| Acer                    | 14        | 1.14%   |
| Lenovo                  | 13        | 1.06%   |
| Unknown                 | 10        | 0.82%   |
| LG Philips              | 10        | 0.82%   |
| Ancor Communications    | 10        | 0.82%   |
| HannStar                | 9         | 0.73%   |
| CPT                     | 9         | 0.73%   |
| Apple                   | 9         | 0.73%   |
| NEC Computers           | 8         | 0.65%   |
| Sony                    | 7         | 0.57%   |
| Sharp                   | 7         | 0.57%   |
| Iiyama                  | 7         | 0.57%   |
| LG Electronics          | 6         | 0.49%   |
| CSO                     | 4         | 0.33%   |
| XYK                     | 3         | 0.24%   |
| Valve                   | 3         | 0.24%   |
| TMX                     | 3         | 0.24%   |
| Gigabyte Technology     | 3         | 0.24%   |
| ASUSTek Computer        | 3         | 0.24%   |
| Plain Tree Systems      | 2         | 0.16%   |
| Mi                      | 2         | 0.16%   |
| LGD                     | 2         | 0.16%   |
| ___                     | 1         | 0.08%   |
| Toshiba                 | 1         | 0.08%   |
| TMA                     | 1         | 0.08%   |
| STD                     | 1         | 0.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 16        | 1.28%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 13        | 1.04%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 12        | 0.96%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 12        | 0.96%   |
| Goldstar L192WS GSM4B32 1440x900 410x256mm 19.0-inch                     | 8         | 0.64%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 8         | 0.64%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 8         | 0.64%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 350x190mm 15.7-inch | 7         | 0.56%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 7         | 0.56%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                | 6         | 0.48%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch     | 6         | 0.48%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 6         | 0.48%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 6         | 0.48%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 6         | 0.48%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 6         | 0.48%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 6         | 0.48%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 6         | 0.48%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 6         | 0.48%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 6         | 0.48%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 6         | 0.48%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 5         | 0.4%    |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 5         | 0.4%    |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 5         | 0.4%    |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                     | 5         | 0.4%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 5         | 0.4%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 5         | 0.4%    |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                    | 5         | 0.4%    |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 5         | 0.4%    |
| AU Optronics LCD Monitor AUO47EC 1366x768 344x193mm 15.5-inch            | 5         | 0.4%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 5         | 0.4%    |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 5         | 0.4%    |
| AOC 24G2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                       | 5         | 0.4%    |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch     | 4         | 0.32%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 4         | 0.32%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch              | 4         | 0.32%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch              | 4         | 0.32%   |
| Goldstar W1942 GSM4B6F 1440x900 408x255mm 18.9-inch                      | 4         | 0.32%   |
| Goldstar L1919S GSM4AF2 1280x1024 376x301mm 19.0-inch                    | 4         | 0.32%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch                | 4         | 0.32%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 4         | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 487       | 40.82%  |
| 1366x768 (WXGA)    | 282       | 23.64%  |
| 1280x1024 (SXGA)   | 63        | 5.28%   |
| 1600x900 (HD+)     | 55        | 4.61%   |
| 3840x2160 (4K)     | 46        | 3.86%   |
| 2560x1440 (QHD)    | 38        | 3.19%   |
| 1440x900 (WXGA+)   | 37        | 3.1%    |
| 1680x1050 (WSXGA+) | 33        | 2.77%   |
| 1280x800 (WXGA)    | 28        | 2.35%   |
| 1024x600           | 20        | 1.68%   |
| 1920x1200 (WUXGA)  | 17        | 1.42%   |
| 2560x1600          | 13        | 1.09%   |
| 2560x1080          | 10        | 0.84%   |
| 2880x1800          | 8         | 0.67%   |
| 2288x1287          | 6         | 0.5%    |
| 1360x768           | 5         | 0.42%   |
| 1024x768 (XGA)     | 5         | 0.42%   |
| 3440x1440          | 4         | 0.34%   |
| Unknown            | 4         | 0.34%   |
| 800x1280           | 3         | 0.25%   |
| 3200x2000          | 3         | 0.25%   |
| 1600x1200          | 3         | 0.25%   |
| 3840x2400          | 2         | 0.17%   |
| 3072x1920          | 2         | 0.17%   |
| 2880x1620          | 2         | 0.17%   |
| 2160x1440          | 2         | 0.17%   |
| 1152x864           | 2         | 0.17%   |
| 4480x1200          | 1         | 0.08%   |
| 3840x1080          | 1         | 0.08%   |
| 3200x1080          | 1         | 0.08%   |
| 2736x1824          | 1         | 0.08%   |
| 2400x1600          | 1         | 0.08%   |
| 2240x1400          | 1         | 0.08%   |
| 2048x1536          | 1         | 0.08%   |
| 2048x1152          | 1         | 0.08%   |
| 1920x540           | 1         | 0.08%   |
| 1920x1440          | 1         | 0.08%   |
| 1680x945           | 1         | 0.08%   |
| 1400x1050          | 1         | 0.08%   |
| 1280x960           | 1         | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 462       | 37.59%  |
| 17      | 97        | 7.89%   |
| 23      | 80        | 6.51%   |
| 21      | 80        | 6.51%   |
| 24      | 62        | 5.04%   |
| 13      | 62        | 5.04%   |
| 19      | 59        | 4.8%    |
| 14      | 52        | 4.23%   |
| 27      | 42        | 3.42%   |
| 31      | 28        | 2.28%   |
| Unknown | 28        | 2.28%   |
| 16      | 27        | 2.2%    |
| 18      | 26        | 2.12%   |
| 22      | 21        | 1.71%   |
| 10      | 20        | 1.63%   |
| 20      | 18        | 1.46%   |
| 34      | 13        | 1.06%   |
| 142     | 6         | 0.49%   |
| 11      | 6         | 0.49%   |
| 72      | 5         | 0.41%   |
| 54      | 5         | 0.41%   |
| 40      | 5         | 0.41%   |
| 12      | 5         | 0.41%   |
| 46      | 4         | 0.33%   |
| 7       | 3         | 0.24%   |
| 84      | 2         | 0.16%   |
| 52      | 2         | 0.16%   |
| 32      | 2         | 0.16%   |
| 8       | 2         | 0.16%   |
| 55      | 1         | 0.08%   |
| 42      | 1         | 0.08%   |
| 26      | 1         | 0.08%   |
| 25      | 1         | 0.08%   |
| 9       | 1         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 586       | 48.39%  |
| 501-600        | 170       | 14.04%  |
| 401-500        | 164       | 13.54%  |
| 351-400        | 117       | 9.66%   |
| 201-300        | 62        | 5.12%   |
| 601-700        | 32        | 2.64%   |
| Unknown        | 28        | 2.31%   |
| 701-800        | 15        | 1.24%   |
| 1001-1500      | 12        | 0.99%   |
| 1501-2000      | 7         | 0.58%   |
| More than 2000 | 6         | 0.5%    |
| 801-900        | 5         | 0.41%   |
| 101-200        | 3         | 0.25%   |
| 1-100          | 3         | 0.25%   |
| 901-1000       | 1         | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 873       | 76.05%  |
| 16/10   | 143       | 12.46%  |
| 5/4     | 61        | 5.31%   |
| Unknown | 26        | 2.26%   |
| 4/3     | 15        | 1.31%   |
| 21/9    | 13        | 1.13%   |
| 3/2     | 7         | 0.61%   |
| 1.00    | 6         | 0.52%   |
| 0.67    | 2         | 0.17%   |
| 0.62    | 2         | 0.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 466       | 38.2%   |
| 201-250        | 199       | 16.31%  |
| 151-200        | 96        | 7.87%   |
| 81-90          | 85        | 6.97%   |
| 121-130        | 55        | 4.51%   |
| 141-150        | 49        | 4.02%   |
| 351-500        | 43        | 3.52%   |
| 301-350        | 43        | 3.52%   |
| Unknown        | 28        | 2.3%    |
| 71-80          | 27        | 2.21%   |
| 251-300        | 22        | 1.8%    |
| More than 1000 | 21        | 1.72%   |
| 41-50          | 21        | 1.72%   |
| 111-120        | 21        | 1.72%   |
| 131-140        | 15        | 1.23%   |
| 501-1000       | 10        | 0.82%   |
| 51-60          | 6         | 0.49%   |
| 61-70          | 5         | 0.41%   |
| 1-40           | 5         | 0.41%   |
| 91-100         | 3         | 0.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 406       | 34.18%  |
| 101-120       | 362       | 30.47%  |
| 121-160       | 293       | 24.66%  |
| 161-240       | 49        | 4.12%   |
| 1-50          | 28        | 2.36%   |
| Unknown       | 28        | 2.36%   |
| More than 240 | 22        | 1.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1016      | 85.02%  |
| 2     | 122       | 10.21%  |
| 0     | 47        | 3.93%   |
| 3     | 10        | 0.84%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 713       | 40.81%  |
| Intel                                  | 336       | 19.23%  |
| Qualcomm Atheros                       | 290       | 16.6%   |
| Broadcom                               | 114       | 6.53%   |
| Nvidia                                 | 42        | 2.4%    |
| Marvell Technology Group               | 33        | 1.89%   |
| MediaTek                               | 32        | 1.83%   |
| Ralink                                 | 26        | 1.49%   |
| Ralink Technology                      | 24        | 1.37%   |
| TP-Link                                | 23        | 1.32%   |
| Broadcom Limited                       | 21        | 1.2%    |
| D-Link                                 | 10        | 0.57%   |
| Huawei Technologies                    | 9         | 0.52%   |
| Qualcomm                               | 7         | 0.4%    |
| Xiaomi                                 | 5         | 0.29%   |
| VIA Technologies                       | 5         | 0.29%   |
| Qualcomm Atheros Communications        | 4         | 0.23%   |
| JMicron Technology                     | 4         | 0.23%   |
| Hewlett-Packard                        | 4         | 0.23%   |
| D-Link System                          | 4         | 0.23%   |
| Sundance Technology Inc / IC Plus      | 3         | 0.17%   |
| Sierra Wireless                        | 3         | 0.17%   |
| Samsung Electronics                    | 3         | 0.17%   |
| Fibocom                                | 3         | 0.17%   |
| Attansic Technology                    | 3         | 0.17%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.11%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.11%   |
| Mercucys                               | 2         | 0.11%   |
| IMC Networks                           | 2         | 0.11%   |
| ASIX Electronics                       | 2         | 0.11%   |
| Aquantia                               | 2         | 0.11%   |
| Texas Instruments                      | 1         | 0.06%   |
| STMicroelectronics                     | 1         | 0.06%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.06%   |
| QinHeng Electronics                    | 1         | 0.06%   |
| Philips (or NXP)                       | 1         | 0.06%   |
| Motorola PCS                           | 1         | 0.06%   |
| Microsoft                              | 1         | 0.06%   |
| Lenovo                                 | 1         | 0.06%   |
| HTC (High Tech Computer)               | 1         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 511       | 25.68%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 117       | 5.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 57        | 2.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 46        | 2.31%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 43        | 2.16%   |
| Intel Wireless 8265 / 8275                                              | 42        | 2.11%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 33        | 1.66%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 29        | 1.46%   |
| Nvidia MCP61 Ethernet                                                   | 28        | 1.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 26        | 1.31%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 23        | 1.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 23        | 1.16%   |
| Intel Wi-Fi 6 AX200                                                     | 23        | 1.16%   |
| Broadcom BCM43142 802.11b/g/n                                           | 23        | 1.16%   |
| Intel Wi-Fi 6 AX201                                                     | 22        | 1.11%   |
| Ralink MT7601U Wireless Adapter                                         | 18        | 0.9%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 18        | 0.9%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 17        | 0.85%   |
| Intel Wireless 7265                                                     | 17        | 0.85%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 16        | 0.8%    |
| Realtek RTL8125 2.5GbE Controller                                       | 15        | 0.75%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 15        | 0.75%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 15        | 0.75%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 14        | 0.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 14        | 0.7%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 13        | 0.65%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 12        | 0.6%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 12        | 0.6%    |
| Intel Wireless 7260                                                     | 12        | 0.6%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 12        | 0.6%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 11        | 0.55%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 11        | 0.55%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 11        | 0.55%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 10        | 0.5%    |
| Intel I211 Gigabit Network Connection                                   | 10        | 0.5%    |
| Intel Ethernet Connection (2) I219-V                                    | 10        | 0.5%    |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 10        | 0.5%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 9         | 0.45%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 8         | 0.4%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 8         | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 288       | 31.3%   |
| Qualcomm Atheros                | 230       | 25%     |
| Realtek Semiconductor           | 167       | 18.15%  |
| Broadcom                        | 85        | 9.24%   |
| MediaTek                        | 29        | 3.15%   |
| Ralink                          | 26        | 2.83%   |
| Ralink Technology               | 24        | 2.61%   |
| TP-Link                         | 20        | 2.17%   |
| Broadcom Limited                | 14        | 1.52%   |
| D-Link                          | 10        | 1.09%   |
| Qualcomm                        | 5         | 0.54%   |
| Qualcomm Atheros Communications | 4         | 0.43%   |
| Sierra Wireless                 | 3         | 0.33%   |
| Hewlett-Packard                 | 3         | 0.33%   |
| Fibocom                         | 3         | 0.33%   |
| Mercucys                        | 2         | 0.22%   |
| IMC Networks                    | 2         | 0.22%   |
| Texas Instruments               | 1         | 0.11%   |
| Philips (or NXP)                | 1         | 0.11%   |
| Microsoft                       | 1         | 0.11%   |
| Marvell Technology Group        | 1         | 0.11%   |
| D-Link System                   | 1         | 0.11%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 57        | 6.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 46        | 4.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 43        | 4.65%   |
| Intel Wireless 8265 / 8275                                              | 42        | 4.55%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 33        | 3.57%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 29        | 3.14%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 26        | 2.81%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 23        | 2.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 23        | 2.49%   |
| Intel Wi-Fi 6 AX200                                                     | 23        | 2.49%   |
| Broadcom BCM43142 802.11b/g/n                                           | 23        | 2.49%   |
| Intel Wi-Fi 6 AX201                                                     | 22        | 2.38%   |
| Ralink MT7601U Wireless Adapter                                         | 18        | 1.95%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 18        | 1.95%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 17        | 1.84%   |
| Intel Wireless 7265                                                     | 17        | 1.84%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 16        | 1.73%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 15        | 1.62%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 14        | 1.52%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 13        | 1.41%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 12        | 1.3%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 12        | 1.3%    |
| Intel Wireless 7260                                                     | 12        | 1.3%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 11        | 1.19%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 10        | 1.08%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 9         | 0.97%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 8         | 0.87%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 8         | 0.87%   |
| Intel Wireless 8260                                                     | 8         | 0.87%   |
| Intel Wireless 3165                                                     | 8         | 0.87%   |
| Intel WiFi Link 5100                                                    | 8         | 0.87%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 7         | 0.76%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 7         | 0.76%   |
| Intel Raptor Lake PCH CNVi WiFi                                         | 7         | 0.76%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 7         | 0.76%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 6         | 0.65%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 6         | 0.65%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 5         | 0.54%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 5         | 0.54%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 5         | 0.54%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 665       | 63.82%  |
| Intel                                  | 105       | 10.08%  |
| Qualcomm Atheros                       | 94        | 9.02%   |
| Broadcom                               | 43        | 4.13%   |
| Nvidia                                 | 42        | 4.03%   |
| Marvell Technology Group               | 32        | 3.07%   |
| Broadcom Limited                       | 7         | 0.67%   |
| Huawei Technologies                    | 6         | 0.58%   |
| Xiaomi                                 | 5         | 0.48%   |
| VIA Technologies                       | 5         | 0.48%   |
| JMicron Technology                     | 4         | 0.38%   |
| TP-Link                                | 3         | 0.29%   |
| Sundance Technology Inc / IC Plus      | 3         | 0.29%   |
| MediaTek                               | 3         | 0.29%   |
| D-Link System                          | 3         | 0.29%   |
| Attansic Technology                    | 3         | 0.29%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.19%   |
| Samsung Electronics                    | 2         | 0.19%   |
| Qualcomm                               | 2         | 0.19%   |
| ASIX Electronics                       | 2         | 0.19%   |
| Aquantia                               | 2         | 0.19%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.1%    |
| Sony Ericsson Mobile Communications AB | 1         | 0.1%    |
| Motorola PCS                           | 1         | 0.1%    |
| Lenovo                                 | 1         | 0.1%    |
| HTC (High Tech Computer)               | 1         | 0.1%    |
| HMD Global                             | 1         | 0.1%    |
| Davicom Semiconductor                  | 1         | 0.1%    |
| Apple                                  | 1         | 0.1%    |
| Unknown                                | 1         | 0.1%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 511       | 48.39%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 117       | 11.08%  |
| Nvidia MCP61 Ethernet                                                          | 28        | 2.65%   |
| Realtek RTL8125 2.5GbE Controller                                              | 15        | 1.42%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 15        | 1.42%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 14        | 1.33%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 12        | 1.14%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 11        | 1.04%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 11        | 1.04%   |
| Intel I211 Gigabit Network Connection                                          | 10        | 0.95%   |
| Intel Ethernet Connection (2) I219-V                                           | 10        | 0.95%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 8         | 0.76%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 8         | 0.76%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 8         | 0.76%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 8         | 0.76%   |
| Intel 82579V Gigabit Network Connection                                        | 8         | 0.76%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 6         | 0.57%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 6         | 0.57%   |
| Intel Ethernet Connection (4) I219-V                                           | 6         | 0.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 6         | 0.57%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 6         | 0.57%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 6         | 0.57%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 5         | 0.47%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                  | 5         | 0.47%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 5         | 0.47%   |
| Intel Ethernet Controller I225-V                                               | 5         | 0.47%   |
| Intel Ethernet Connection (6) I219-V                                           | 5         | 0.47%   |
| Huawei FOA-LX9                                                                 | 5         | 0.47%   |
| VIA VT6105/VT6106S [Rhine-III]                                                 | 4         | 0.38%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 4         | 0.38%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 4         | 0.38%   |
| Nvidia MCP65 Ethernet                                                          | 4         | 0.38%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 4         | 0.38%   |
| Intel Ethernet Connection (7) I219-V                                           | 4         | 0.38%   |
| Intel Ethernet Connection (23) I219-V                                          | 4         | 0.38%   |
| Intel Ethernet Connection (14) I219-V                                          | 4         | 0.38%   |
| Intel 82566MM Gigabit Network Connection                                       | 4         | 0.38%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 4         | 0.38%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 4         | 0.38%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY     | 3         | 0.28%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1004      | 53.07%  |
| WiFi     | 878       | 46.41%  |
| Modem    | 10        | 0.53%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 735       | 60.34%  |
| Ethernet | 483       | 39.66%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 664       | 56.56%  |
| 1     | 482       | 41.06%  |
| 0     | 18        | 1.53%   |
| 3     | 8         | 0.68%   |
| 4     | 2         | 0.17%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1156      | 98.05%  |
| Yes  | 23        | 1.95%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 240       | 34.88%  |
| Realtek Semiconductor           | 91        | 13.23%  |
| Qualcomm Atheros Communications | 73        | 10.61%  |
| IMC Networks                    | 56        | 8.14%   |
| Broadcom                        | 37        | 5.38%   |
| Foxconn / Hon Hai               | 33        | 4.8%    |
| Lite-On Technology              | 31        | 4.51%   |
| Cambridge Silicon Radio         | 31        | 4.51%   |
| ASUSTek Computer                | 17        | 2.47%   |
| Ralink                          | 16        | 2.33%   |
| Foxconn International           | 12        | 1.74%   |
| Hewlett-Packard                 | 9         | 1.31%   |
| Toshiba                         | 7         | 1.02%   |
| Apple                           | 6         | 0.87%   |
| MediaTek                        | 5         | 0.73%   |
| Realtek                         | 3         | 0.44%   |
| Ralink Technology               | 3         | 0.44%   |
| Dell                            | 3         | 0.44%   |
| Taiyo Yuden                     | 2         | 0.29%   |
| Qcom                            | 2         | 0.29%   |
| Integrated System Solution      | 2         | 0.29%   |
| USI                             | 1         | 0.15%   |
| TP-Link                         | 1         | 0.15%   |
| Opticis                         | 1         | 0.15%   |
| Micro Star International        | 1         | 0.15%   |
| Marvell Semiconductor           | 1         | 0.15%   |
| Chicony Electronics             | 1         | 0.15%   |
| Alps Electric                   | 1         | 0.15%   |
| Actions                         | 1         | 0.15%   |
| Unknown                         | 1         | 0.15%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 91        | 13.19%  |
| Realtek Bluetooth Radio                             | 63        | 9.13%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 51        | 7.39%   |
| Intel AX201 Bluetooth                               | 45        | 6.52%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 31        | 4.49%   |
| Qualcomm Atheros  Bluetooth Device                  | 22        | 3.19%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 22        | 3.19%   |
| Intel AX200 Bluetooth                               | 22        | 3.19%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 17        | 2.46%   |
| IMC Networks Wireless_Device                        | 17        | 2.46%   |
| Ralink RT3290 Bluetooth                             | 16        | 2.32%   |
| Realtek  Bluetooth 4.2 Adapter                      | 14        | 2.03%   |
| IMC Networks Bluetooth Radio                        | 14        | 2.03%   |
| Foxconn International BCM43142A0 Bluetooth module   | 12        | 1.74%   |
| Foxconn / Hon Hai Bluetooth Device                  | 12        | 1.74%   |
| Lite-On Bluetooth Device                            | 11        | 1.59%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 10        | 1.45%   |
| Intel AX211 Bluetooth                               | 9         | 1.3%    |
| IMC Networks Bluetooth Device                       | 9         | 1.3%    |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 8         | 1.16%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 7         | 1.01%   |
| Lite-On Atheros AR3012 Bluetooth                    | 7         | 1.01%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 7         | 1.01%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 7         | 1.01%   |
| Broadcom BCM2070 Bluetooth Device                   | 7         | 1.01%   |
| Realtek RTL8723B Bluetooth                          | 6         | 0.87%   |
| Qualcomm Atheros Bluetooth                          | 6         | 0.87%   |
| HP Broadcom 2070 Bluetooth Combo                    | 5         | 0.72%   |
| Realtek RTL8821A Bluetooth                          | 4         | 0.58%   |
| MediaTek Wireless_Device                            | 4         | 0.58%   |
| Intel Wireless-AC 3168 Bluetooth                    | 4         | 0.58%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 4         | 0.58%   |
| Foxconn / Hon Hai Wireless_Device                   | 4         | 0.58%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 4         | 0.58%   |
| Broadcom BCM2045 Bluetooth                          | 4         | 0.58%   |
| ASUS BT-270 Bluetooth Adapter                       | 4         | 0.58%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 4         | 0.58%   |
| Apple Bluetooth Host Controller                     | 4         | 0.58%   |
| Toshiba RT Bluetooth Radio                          | 3         | 0.43%   |
| Realtek 802.11ac WLAN Adapter                       | 3         | 0.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 786       | 50.51%  |
| AMD                              | 352       | 22.62%  |
| Nvidia                           | 296       | 19.02%  |
| C-Media Electronics              | 20        | 1.29%   |
| Logitech                         | 13        | 0.84%   |
| Creative Labs                    | 12        | 0.77%   |
| JMTek                            | 10        | 0.64%   |
| Texas Instruments                | 8         | 0.51%   |
| Silicon Integrated Systems [SiS] | 4         | 0.26%   |
| Generalplus Technology           | 4         | 0.26%   |
| GN Netcom                        | 3         | 0.19%   |
| Conexant Systems                 | 3         | 0.19%   |
| Tenx Technology                  | 2         | 0.13%   |
| SteelSeries ApS                  | 2         | 0.13%   |
| Razer USA                        | 2         | 0.13%   |
| Micro Star International         | 2         | 0.13%   |
| M-Audio                          | 2         | 0.13%   |
| Kingston Technology              | 2         | 0.13%   |
| GYROCOM C&C                      | 2         | 0.13%   |
| ESS Technology                   | 2         | 0.13%   |
| ASUSTek Computer                 | 2         | 0.13%   |
| Apple                            | 2         | 0.13%   |
| Yealink Network Technology       | 1         | 0.06%   |
| Yamaha                           | 1         | 0.06%   |
| VIA Technologies                 | 1         | 0.06%   |
| Synaptics                        | 1         | 0.06%   |
| Samson Technologies              | 1         | 0.06%   |
| ROCCAT                           | 1         | 0.06%   |
| Realtek Semiconductor            | 1         | 0.06%   |
| Plantronics                      | 1         | 0.06%   |
| Pixart Imaging                   | 1         | 0.06%   |
| NXP Semiconductors               | 1         | 0.06%   |
| Nordic Semiconductor ASA         | 1         | 0.06%   |
| Jieli Technology                 | 1         | 0.06%   |
| JBL                              | 1         | 0.06%   |
| iCreate Technologies             | 1         | 0.06%   |
| Huawei Technologies              | 1         | 0.06%   |
| Focusrite-Novation               | 1         | 0.06%   |
| FIFINE Microphones               | 1         | 0.06%   |
| Edifier Technology               | 1         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 107       | 5.77%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 103       | 5.55%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 92        | 4.96%   |
| Intel Sunrise Point-LP HD Audio                                            | 69        | 3.72%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 66        | 3.56%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 57        | 3.07%   |
| AMD FCH Azalia Controller                                                  | 55        | 2.96%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 52        | 2.8%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 43        | 2.32%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 40        | 2.16%   |
| Nvidia MCP61 High Definition Audio                                         | 34        | 1.83%   |
| Intel Cannon Lake PCH cAVS                                                 | 33        | 1.78%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 33        | 1.78%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 31        | 1.67%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 31        | 1.67%   |
| Nvidia GF108 High Definition Audio Controller                              | 27        | 1.45%   |
| Intel Haswell-ULT HD Audio Controller                                      | 27        | 1.45%   |
| Intel 8 Series HD Audio Controller                                         | 27        | 1.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 25        | 1.35%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 25        | 1.35%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 22        | 1.19%   |
| Nvidia GP107GL High Definition Audio Controller                            | 21        | 1.13%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 21        | 1.13%   |
| Intel Comet Lake PCH-LP cAVS                                               | 20        | 1.08%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 19        | 1.02%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 19        | 1.02%   |
| AMD Trinity HDMI Audio Controller                                          | 19        | 1.02%   |
| Nvidia High Definition Audio Controller                                    | 18        | 0.97%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 18        | 0.97%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 18        | 0.97%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 17        | 0.92%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 15        | 0.81%   |
| AMD Starship/Matisse HD Audio Controller                                   | 15        | 0.81%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 15        | 0.81%   |
| AMD Kabini HDMI/DP Audio                                                   | 15        | 0.81%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 14        | 0.75%   |
| AMD Wrestler HDMI Audio                                                    | 14        | 0.75%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 14        | 0.75%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 13        | 0.7%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 13        | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Unknown               | 202       | 19.2%   |
| Samsung Electronics   | 201       | 19.11%  |
| SK hynix              | 162       | 15.4%   |
| Kingston              | 132       | 12.55%  |
| Micron Technology     | 81        | 7.7%    |
| Crucial               | 66        | 6.27%   |
| Elpida                | 27        | 2.57%   |
| Ramaxel Technology    | 18        | 1.71%   |
| Patriot               | 17        | 1.62%   |
| G.Skill               | 17        | 1.62%   |
| Nanya Technology      | 16        | 1.52%   |
| A-DATA Technology     | 14        | 1.33%   |
| Corsair               | 11        | 1.05%   |
| Transcend             | 9         | 0.86%   |
| Silicon Power         | 8         | 0.76%   |
| ASint Technology      | 8         | 0.76%   |
| GOODRAM               | 7         | 0.67%   |
| Team                  | 6         | 0.57%   |
| Unknown               | 6         | 0.57%   |
| GeIL                  | 5         | 0.48%   |
| Apacer                | 5         | 0.48%   |
| 48spaces              | 4         | 0.38%   |
| Unknown (ABCD)        | 3         | 0.29%   |
| SHARETRONIC           | 3         | 0.29%   |
| Netac                 | 3         | 0.29%   |
| Kingmax               | 3         | 0.29%   |
| Unknown (89F7)        | 2         | 0.19%   |
| TakeMS                | 2         | 0.19%   |
| Qumo                  | 2         | 0.19%   |
| Kllisre               | 2         | 0.19%   |
| AMD                   | 2         | 0.19%   |
| Wilk Elektronik       | 1         | 0.1%    |
| Wilk                  | 1         | 0.1%    |
| Qimonda               | 1         | 0.1%    |
| PNY                   | 1         | 0.1%    |
| Kingmax Semiconductor | 1         | 0.1%    |
| HMD                   | 1         | 0.1%    |
| Goldkey               | 1         | 0.1%    |
| Golden Empire         | 1         | 0.1%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s   | 14        | 1.22%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s    | 11        | 0.96%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s    | 11        | 0.96%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s    | 9         | 0.78%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s    | 8         | 0.7%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s    | 8         | 0.7%    |
| Unknown RAM Module 2048MB DIMM 800MT/s                   | 7         | 0.61%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s    | 7         | 0.61%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                  | 6         | 0.52%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s            | 6         | 0.52%   |
| Unknown RAM Module 2048MB DIMM SDRAM                     | 6         | 0.52%   |
| Unknown RAM Module 1024MB DIMM SDRAM                     | 6         | 0.52%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 6         | 0.52%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s    | 6         | 0.52%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s | 6         | 0.52%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s    | 6         | 0.52%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s    | 6         | 0.52%   |
| Kingston RAM ACR16D3LS1NGG/4G 4GB SODIMM DDR3 1600MT/s   | 6         | 0.52%   |
| Unknown                                                  | 6         | 0.52%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s               | 5         | 0.43%   |
| Unknown RAM Module 2GB DIMM 800MT/s                      | 5         | 0.43%   |
| Unknown RAM Module 2048MB DIMM DDR2                      | 5         | 0.43%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s            | 5         | 0.43%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s   | 5         | 0.43%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 5         | 0.43%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s   | 5         | 0.43%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s   | 5         | 0.43%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s   | 5         | 0.43%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s    | 5         | 0.43%   |
| Samsung RAM M4 70T5663EH3-CF7 2GB SODIMM DDR2 975MT/s    | 5         | 0.43%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                     | 4         | 0.35%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s             | 4         | 0.35%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s            | 4         | 0.35%   |
| Unknown RAM Module 2048MB SODIMM DDR2                    | 4         | 0.35%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                   | 4         | 0.35%   |
| Unknown RAM Module 1024MB DIMM DDR2                      | 4         | 0.35%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                   | 4         | 0.35%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s   | 4         | 0.35%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s   | 4         | 0.35%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s   | 4         | 0.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 351       | 39%     |
| DDR4    | 281       | 31.22%  |
| DDR2    | 81        | 9%      |
| Unknown | 77        | 8.56%   |
| SDRAM   | 54        | 6%      |
| LPDDR4  | 17        | 1.89%   |
| DDR5    | 14        | 1.56%   |
| LPDDR5  | 10        | 1.11%   |
| DDR     | 9         | 1%      |
| DRAM    | 4         | 0.44%   |
| LPDDR3  | 2         | 0.22%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 537       | 60.68%  |
| DIMM         | 315       | 35.59%  |
| Row Of Chips | 33        | 3.73%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 337       | 32.72%  |
| 8192  | 248       | 24.08%  |
| 2048  | 235       | 22.82%  |
| 16384 | 108       | 10.49%  |
| 1024  | 71        | 6.89%   |
| 32768 | 14        | 1.36%   |
| 512   | 14        | 1.36%   |
| 256   | 2         | 0.19%   |
| 16    | 1         | 0.1%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 236       | 24.06%  |
| 3200    | 115       | 11.72%  |
| 2667    | 86        | 8.77%   |
| 1333    | 71        | 7.24%   |
| 2400    | 63        | 6.42%   |
| 800     | 48        | 4.89%   |
| Unknown | 48        | 4.89%   |
| 667     | 45        | 4.59%   |
| 1334    | 43        | 4.38%   |
| 2133    | 19        | 1.94%   |
| 4199    | 16        | 1.63%   |
| 3600    | 14        | 1.43%   |
| 1066    | 14        | 1.43%   |
| 533     | 13        | 1.33%   |
| 1067    | 12        | 1.22%   |
| 400     | 12        | 1.22%   |
| 3266    | 11        | 1.12%   |
| 1867    | 10        | 1.02%   |
| 4800    | 9         | 0.92%   |
| 2048    | 9         | 0.92%   |
| 1866    | 8         | 0.82%   |
| 6400    | 7         | 0.71%   |
| 3466    | 7         | 0.71%   |
| 333     | 7         | 0.71%   |
| 4267    | 5         | 0.51%   |
| 5600    | 4         | 0.41%   |
| 3733    | 4         | 0.41%   |
| 2666    | 4         | 0.41%   |
| 4266    | 3         | 0.31%   |
| 3800    | 3         | 0.31%   |
| 3400    | 3         | 0.31%   |
| 49926   | 2         | 0.2%    |
| 8533    | 2         | 0.2%    |
| 8400    | 2         | 0.2%    |
| 3000    | 2         | 0.2%    |
| 1800    | 2         | 0.2%    |
| 1639    | 2         | 0.2%    |
| 266     | 2         | 0.2%    |
| 65535   | 1         | 0.1%    |
| 7500    | 1         | 0.1%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Canon                 | 8         | 28.57%  |
| Hewlett-Packard       | 7         | 25%     |
| Seiko Epson           | 5         | 17.86%  |
| Samsung Electronics   | 3         | 10.71%  |
| Ricoh                 | 1         | 3.57%   |
| QinHeng Electronics   | 1         | 3.57%   |
| Pantum                | 1         | 3.57%   |
| Lexmark International | 1         | 3.57%   |
| Kyocera               | 1         | 3.57%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Canon LBP6030/6030B/6018L         | 2         | 6.9%    |
| Canon CAPT USB Device             | 2         | 6.9%    |
| Seiko Epson M100 Series           | 1         | 3.45%   |
| Seiko Epson L805 Series           | 1         | 3.45%   |
| Seiko Epson L365 Series           | 1         | 3.45%   |
| Seiko Epson L360 Series           | 1         | 3.45%   |
| Seiko Epson ET-1810 Series        | 1         | 3.45%   |
| Samsung SCX-4300 Series           | 1         | 3.45%   |
| Samsung SCX-4200 series           | 1         | 3.45%   |
| Samsung Laser Printer             | 1         | 3.45%   |
| Ricoh SP 213SUw                   | 1         | 3.45%   |
| QinHeng CH340S                    | 1         | 3.45%   |
| Pantum M6500W-series              | 1         | 3.45%   |
| Lexmark International Z35 Printer | 1         | 3.45%   |
| Kyocera FS-1125MFP                | 1         | 3.45%   |
| HP LaserJet P2055 series          | 1         | 3.45%   |
| HP LaserJet P1006                 | 1         | 3.45%   |
| HP LaserJet P1005                 | 1         | 3.45%   |
| HP LaserJet 1300                  | 1         | 3.45%   |
| HP LaserJet 1010                  | 1         | 3.45%   |
| HP DeskJet F2100 Printer series   | 1         | 3.45%   |
| HP DeskJet 840c                   | 1         | 3.45%   |
| Canon MF4410                      | 1         | 3.45%   |
| Canon MF4010 series               | 1         | 3.45%   |
| Canon MF3010                      | 1         | 3.45%   |
| Canon LBP2900                     | 1         | 3.45%   |
| Canon G1000 series                | 1         | 3.45%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 4         | 57.14%  |
| Ultima Electronics | 1         | 14.29%  |
| Seiko Epson        | 1         | 14.29%  |
| Mustek Systems     | 1         | 14.29%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1         | 14.29%  |
| Seiko Epson Stylus Photo RX500/510                                                    | 1         | 14.29%  |
| Mustek Systems BearPaw 2448 TA Pro                                                    | 1         | 14.29%  |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 1         | 14.29%  |
| Canon CanoScan LiDE 600F                                                              | 1         | 14.29%  |
| Canon CanoScan LiDE 60                                                                | 1         | 14.29%  |
| Canon CanoScan LIDE 25                                                                | 1         | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 163       | 20.9%   |
| IMC Networks                           | 113       | 14.49%  |
| Quanta                                 | 44        | 5.64%   |
| Realtek Semiconductor                  | 43        | 5.51%   |
| Bison Electronics                      | 41        | 5.26%   |
| Logitech                               | 39        | 5%      |
| Sunplus Innovation Technology          | 35        | 4.49%   |
| Suyin                                  | 32        | 4.1%    |
| Microdia                               | 29        | 3.72%   |
| Cheng Uei Precision Industry (Foxlink) | 28        | 3.59%   |
| Syntek                                 | 27        | 3.46%   |
| Z-Star Microelectronics                | 25        | 3.21%   |
| Silicon Motion                         | 23        | 2.95%   |
| Lite-On Technology                     | 22        | 2.82%   |
| Acer                                   | 13        | 1.67%   |
| Alcor Micro                            | 12        | 1.54%   |
| Luxvisions Innotech Limited            | 11        | 1.41%   |
| Apple                                  | 11        | 1.41%   |
| Sonix Technology                       | 7         | 0.9%    |
| SunplusIT                              | 5         | 0.64%   |
| Samsung Electronics                    | 4         | 0.51%   |
| Primax Electronics                     | 4         | 0.51%   |
| Microsoft                              | 4         | 0.51%   |
| lihappe8                               | 3         | 0.38%   |
| Lenovo                                 | 3         | 0.38%   |
| Importek                               | 3         | 0.38%   |
| DigiTech                               | 3         | 0.38%   |
| Cubeternet                             | 3         | 0.38%   |
| Aveo Technology                        | 3         | 0.38%   |
| Shinetech                              | 2         | 0.26%   |
| Shine-optics                           | 2         | 0.26%   |
| Ricoh                                  | 2         | 0.26%   |
| Razer USA                              | 2         | 0.26%   |
| Intel                                  | 2         | 0.26%   |
| Arkmicro Technologies                  | 2         | 0.26%   |
| YGTek                                  | 1         | 0.13%   |
| Y Media                                | 1         | 0.13%   |
| ShineOptics                            | 1         | 0.13%   |
| Pixart Imaging                         | 1         | 0.13%   |
| Nokia Mobile Phones                    | 1         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                                         | 31        | 3.96%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 22        | 2.81%   |
| Logitech Webcam C270                                                       | 17        | 2.17%   |
| Chicony Integrated Camera                                                  | 17        | 2.17%   |
| IMC Networks Integrated Camera                                             | 16        | 2.05%   |
| Realtek Integrated_Webcam_HD                                               | 13        | 1.66%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 13        | 1.66%   |
| Syntek Integrated Camera                                                   | 12        | 1.53%   |
| Chicony HD WebCam                                                          | 12        | 1.53%   |
| Chicony Lenovo EasyCamera                                                  | 11        | 1.41%   |
| Bison Lenovo EasyCamera                                                    | 11        | 1.41%   |
| Sunplus HD WebCam                                                          | 10        | 1.28%   |
| Bison Lenovo Integrated Webcam                                             | 10        | 1.28%   |
| IMC Networks USB2.0 UVC HD Webcam                                          | 9         | 1.15%   |
| Syntek EasyCamera                                                          | 7         | 0.9%    |
| Quanta HP HD Camera                                                        | 7         | 0.9%    |
| Microdia Camera                                                            | 7         | 0.9%    |
| IMC Networks Integrated Webcam                                             | 7         | 0.9%    |
| Chicony USB2.0 HD UVC WebCam                                               | 7         | 0.9%    |
| Chicony HP HD Camera                                                       | 7         | 0.9%    |
| Chicony EasyCamera                                                         | 7         | 0.9%    |
| Syntek Lenovo EasyCamera                                                   | 6         | 0.77%   |
| Sunplus Integrated_Webcam_HD                                               | 6         | 0.77%   |
| Silicon Motion WebCam SC-0311139N                                          | 6         | 0.77%   |
| Microdia Integrated_Webcam_HD                                              | 6         | 0.77%   |
| Logitech Webcam C310                                                       | 6         | 0.77%   |
| Lite-On Integrated Camera                                                  | 6         | 0.77%   |
| IMC Networks UVC VGA Webcam                                                | 6         | 0.77%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 6         | 0.77%   |
| Bison Integrated Camera                                                    | 6         | 0.77%   |
| Z-Star Venus USB2.0 Camera                                                 | 5         | 0.64%   |
| Z-Star A4 TECH USB2.0 PC Camera J                                          | 5         | 0.64%   |
| Suyin HP TrueVision HD                                                     | 5         | 0.64%   |
| Quanta HP TrueVision HD Camera                                             | 5         | 0.64%   |
| Quanta HD Webcam                                                           | 5         | 0.64%   |
| Lite-On HP HD Camera                                                       | 5         | 0.64%   |
| IMC Networks HD Camera                                                     | 5         | 0.64%   |
| Chicony Integrated HP HD Webcam                                            | 5         | 0.64%   |
| Chicony HP Wide Vision HD Camera                                           | 5         | 0.64%   |
| Chicony HP TrueVision HD Camera                                            | 5         | 0.64%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 23        | 25.27%  |
| Shenzhen Goodix Technology         | 19        | 20.88%  |
| Synaptics                          | 18        | 19.78%  |
| Elan Microelectronics              | 14        | 15.38%  |
| AuthenTec                          | 6         | 6.59%   |
| STMicroelectronics                 | 3         | 3.3%    |
| Realtek USB2.0 Finger Print Bridge | 3         | 3.3%    |
| Upek                               | 2         | 2.2%    |
| LighTuning Technology              | 2         | 2.2%    |
| Focal-systems.Corp                 | 1         | 1.1%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 11        | 12.09%  |
| Elan ELAN:Fingerprint                                                      | 9         | 9.89%   |
| Shenzhen Goodix Fingerprint Reader                                         | 7         | 7.69%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 5         | 5.49%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 4.4%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 4.4%    |
| Elan ELAN:ARM-M4                                                           | 4         | 4.4%    |
| Validity Sensors Fingerprint scanner                                       | 3         | 3.3%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 3.3%    |
| STMicroelectronics Fingerprint Reader                                      | 3         | 3.3%    |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 3.3%    |
| Validity Sensors VFS491                                                    | 2         | 2.2%    |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 2.2%    |
| Validity Sensors Synaptics WBDI                                            | 2         | 2.2%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 2.2%    |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 2.2%    |
| Synaptics  WBDI                                                            | 2         | 2.2%    |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 2         | 2.2%    |
| Synaptics Fingerprint reader [HP G6]                                       | 2         | 2.2%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 2.2%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.1%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 1.1%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 1.1%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 1.1%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.1%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 1.1%    |
| Synaptics UWP WBDI                                                         | 1         | 1.1%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 1.1%    |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.1%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 1.1%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 1.1%    |
| Focal-systems.Corp FT9201Fingerprint.Ì                                  | 1         | 1.1%    |
| Elan WBF Fingerprint Sensor                                                | 1         | 1.1%    |
| AuthenTec Fingerprint Sensor                                               | 1         | 1.1%    |
| AuthenTec AES2810                                                          | 1         | 1.1%    |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 1.1%    |
| AuthenTec AES1600                                                          | 1         | 1.1%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 10        | 47.62%  |
| Lenovo                | 5         | 23.81%  |
| Upek                  | 2         | 9.52%   |
| Broadcom              | 2         | 9.52%   |
| O2 Micro              | 1         | 4.76%   |
| Advanced Card Systems | 1         | 4.76%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 10        | 47.62%  |
| Lenovo Integrated Smart Card Reader                                          | 5         | 23.81%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 9.52%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 4.76%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 4.76%   |
| Broadcom 58200                                                               | 1         | 4.76%   |
| Advanced Card Systems ACR39U                                                 | 1         | 4.76%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 897       | 74.07%  |
| 1     | 256       | 21.14%  |
| 2     | 50        | 4.13%   |
| 3     | 7         | 0.58%   |
| 4     | 1         | 0.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 142       | 40.23%  |
| Fingerprint reader       | 89        | 25.21%  |
| Net/wireless             | 27        | 7.65%   |
| Multimedia controller    | 20        | 5.67%   |
| Bluetooth                | 20        | 5.67%   |
| Chipcard                 | 16        | 4.53%   |
| Communication controller | 14        | 3.97%   |
| Camera                   | 12        | 3.4%    |
| Storage                  | 4         | 1.13%   |
| Sound                    | 3         | 0.85%   |
| Card reader              | 2         | 0.57%   |
| Unassigned class         | 1         | 0.28%   |
| Net/ethernet             | 1         | 0.28%   |
| Modem                    | 1         | 0.28%   |
| Flash memory             | 1         | 0.28%   |

