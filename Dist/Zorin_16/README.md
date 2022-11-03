Zorin 16 - Tested Hardware & Statistics
---------------------------------------

A project to collect tested hardware configurations for Zorin 16.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Zorin_16/Desktop/README.md) and [notebooks](/Dist/Zorin_16/Notebook/README.md).

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

Total: 3066

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [6c3a410233](https://linux-hardware.org/?probe=6c3a410233) | Oct 30, 2022 |
| Dell          | Inspiron 5537               | Notebook    | [4cd1e12a5d](https://linux-hardware.org/?probe=4cd1e12a5d) | Oct 30, 2022 |
| Dell          | Inspiron N5050              | Notebook    | [f844544154](https://linux-hardware.org/?probe=f844544154) | Oct 30, 2022 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [97d7d8c2d9](https://linux-hardware.org/?probe=97d7d8c2d9) | Oct 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [ae6fd2de89](https://linux-hardware.org/?probe=ae6fd2de89) | Oct 29, 2022 |
| MSI           | GL72 6QD                    | Notebook    | [2f7c223f5a](https://linux-hardware.org/?probe=2f7c223f5a) | Oct 29, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [068d4ec2e6](https://linux-hardware.org/?probe=068d4ec2e6) | Oct 29, 2022 |
| Acer          | Extensa 5635ZG              | Notebook    | [8c0a7c0aa1](https://linux-hardware.org/?probe=8c0a7c0aa1) | Oct 29, 2022 |
| Dell          | 0T2HR0 A02                  | Desktop     | [e4b1137777](https://linux-hardware.org/?probe=e4b1137777) | Oct 29, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [2c57f9b6a3](https://linux-hardware.org/?probe=2c57f9b6a3) | Oct 29, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [242fa16882](https://linux-hardware.org/?probe=242fa16882) | Oct 29, 2022 |
| ASUSTek       | STRIX X99 GAMING            | Desktop     | [f111078004](https://linux-hardware.org/?probe=f111078004) | Oct 29, 2022 |
| MSI           | B560M PRO                   | Desktop     | [a84dc6f9cb](https://linux-hardware.org/?probe=a84dc6f9cb) | Oct 29, 2022 |
| Dell          | Latitude E6530              | Notebook    | [cdd3b5ce40](https://linux-hardware.org/?probe=cdd3b5ce40) | Oct 28, 2022 |
| HP            | Presario V6000 (RV053UA#... | Notebook    | [ca121e3727](https://linux-hardware.org/?probe=ca121e3727) | Oct 28, 2022 |
| ASUSTek       | STRIX X99 GAMING            | Desktop     | [b683357ec4](https://linux-hardware.org/?probe=b683357ec4) | Oct 28, 2022 |
| HP            | OMEN Notebook PC 15         | Notebook    | [fea0167027](https://linux-hardware.org/?probe=fea0167027) | Oct 28, 2022 |
| Packard Be... | EasyNote MH45               | Notebook    | [b9aa4cc6d5](https://linux-hardware.org/?probe=b9aa4cc6d5) | Oct 27, 2022 |
| Gateway       | SX2851                      | Desktop     | [500b4bb8ec](https://linux-hardware.org/?probe=500b4bb8ec) | Oct 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9986b4ff02](https://linux-hardware.org/?probe=9986b4ff02) | Oct 27, 2022 |
| ASUSTek       | P8H61/USB3                  | Desktop     | [c20c97e43e](https://linux-hardware.org/?probe=c20c97e43e) | Oct 27, 2022 |
| HP            | 829B                        | All in one  | [1f8f75d1c0](https://linux-hardware.org/?probe=1f8f75d1c0) | Oct 27, 2022 |
| MSI           | MS-AE611 100                | All in one  | [7527f4a200](https://linux-hardware.org/?probe=7527f4a200) | Oct 27, 2022 |
| Acer          | Aspire 5720Z                | Notebook    | [fc0b8944bc](https://linux-hardware.org/?probe=fc0b8944bc) | Oct 26, 2022 |
| MSI           | Creator Z16 A11UET          | Notebook    | [58e18764cb](https://linux-hardware.org/?probe=58e18764cb) | Oct 26, 2022 |
| MSI           | Creator Z16 A11UET          | Notebook    | [06274bdff6](https://linux-hardware.org/?probe=06274bdff6) | Oct 26, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [7a0f5285f2](https://linux-hardware.org/?probe=7a0f5285f2) | Oct 26, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [80c2aeb241](https://linux-hardware.org/?probe=80c2aeb241) | Oct 26, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [54f6493d11](https://linux-hardware.org/?probe=54f6493d11) | Oct 26, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [5bc9d4bdc8](https://linux-hardware.org/?probe=5bc9d4bdc8) | Oct 26, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [6b0380ea4c](https://linux-hardware.org/?probe=6b0380ea4c) | Oct 26, 2022 |
| Dell          | Latitude E6510              | Notebook    | [1949f78888](https://linux-hardware.org/?probe=1949f78888) | Oct 26, 2022 |
| ALURIN        | PR1-M146                    | Notebook    | [af492a458f](https://linux-hardware.org/?probe=af492a458f) | Oct 25, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [bb655d6ea7](https://linux-hardware.org/?probe=bb655d6ea7) | Oct 25, 2022 |
| MSI           | MS-AE611 100                | All in one  | [1f6fc12b09](https://linux-hardware.org/?probe=1f6fc12b09) | Oct 25, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [91437ee9a7](https://linux-hardware.org/?probe=91437ee9a7) | Oct 25, 2022 |
| MSI           | GT70 2PE                    | Notebook    | [26d9f8ba04](https://linux-hardware.org/?probe=26d9f8ba04) | Oct 25, 2022 |
| Toshiba       | K201                        | Notebook    | [63a892bae3](https://linux-hardware.org/?probe=63a892bae3) | Oct 25, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [aa82a1f3c9](https://linux-hardware.org/?probe=aa82a1f3c9) | Oct 24, 2022 |
| MSI           | GE62 7RE                    | Notebook    | [bd5b8943f4](https://linux-hardware.org/?probe=bd5b8943f4) | Oct 24, 2022 |
| Samsung       | 305V4A/305V5A/3415VA        | Notebook    | [d8f70347cf](https://linux-hardware.org/?probe=d8f70347cf) | Oct 24, 2022 |
| HP            | Pavilion Sleekbook 15 PC    | Notebook    | [26e7b206ef](https://linux-hardware.org/?probe=26e7b206ef) | Oct 24, 2022 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [e894ec1b8d](https://linux-hardware.org/?probe=e894ec1b8d) | Oct 24, 2022 |
| Lenovo        | G50-45 80MQ                 | Notebook    | [2628815c23](https://linux-hardware.org/?probe=2628815c23) | Oct 24, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [200f2ac48e](https://linux-hardware.org/?probe=200f2ac48e) | Oct 24, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [646b07cc4c](https://linux-hardware.org/?probe=646b07cc4c) | Oct 24, 2022 |
| Alienware     | 18                          | Notebook    | [11e8831b9d](https://linux-hardware.org/?probe=11e8831b9d) | Oct 24, 2022 |
| Alienware     | 18                          | Notebook    | [86eb347494](https://linux-hardware.org/?probe=86eb347494) | Oct 24, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [17adb9ee1e](https://linux-hardware.org/?probe=17adb9ee1e) | Oct 23, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [055a6c2be8](https://linux-hardware.org/?probe=055a6c2be8) | Oct 23, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [cb299f8f1b](https://linux-hardware.org/?probe=cb299f8f1b) | Oct 23, 2022 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [dad9e03a82](https://linux-hardware.org/?probe=dad9e03a82) | Oct 23, 2022 |
| OEM           | G41 775 ICH7 8712           | Desktop     | [1f3d807ceb](https://linux-hardware.org/?probe=1f3d807ceb) | Oct 23, 2022 |
| Dell          | 0JP3NX A01                  | Desktop     | [86365f2c05](https://linux-hardware.org/?probe=86365f2c05) | Oct 23, 2022 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [6a42097b41](https://linux-hardware.org/?probe=6a42097b41) | Oct 23, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [42280c6145](https://linux-hardware.org/?probe=42280c6145) | Oct 23, 2022 |
| AMI           | Unknown                     | Notebook    | [337d94fb96](https://linux-hardware.org/?probe=337d94fb96) | Oct 23, 2022 |
| ASUSTek       | X510UQ                      | Notebook    | [6d976f6f96](https://linux-hardware.org/?probe=6d976f6f96) | Oct 23, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [9035fff7ea](https://linux-hardware.org/?probe=9035fff7ea) | Oct 23, 2022 |
| Dell          | 0200DY A02                  | Desktop     | [8fd4b48b80](https://linux-hardware.org/?probe=8fd4b48b80) | Oct 23, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [3d2171b17e](https://linux-hardware.org/?probe=3d2171b17e) | Oct 23, 2022 |
| Dell          | 0HN7XN A01                  | Desktop     | [4e75c878a3](https://linux-hardware.org/?probe=4e75c878a3) | Oct 22, 2022 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | Notebook    | [a8a9cdfabc](https://linux-hardware.org/?probe=a8a9cdfabc) | Oct 22, 2022 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | Notebook    | [d82378ea41](https://linux-hardware.org/?probe=d82378ea41) | Oct 22, 2022 |
| Acer          | Aspire E5-411               | Notebook    | [f4fa3fce70](https://linux-hardware.org/?probe=f4fa3fce70) | Oct 22, 2022 |
| HP            | EliteBook 755 G5            | Notebook    | [b1550ee8e1](https://linux-hardware.org/?probe=b1550ee8e1) | Oct 22, 2022 |
| OEM           | G41 775 ICH7 8712           | Desktop     | [f43a04f63f](https://linux-hardware.org/?probe=f43a04f63f) | Oct 21, 2022 |
| Dell          | Studio 1558                 | Notebook    | [ac449d0411](https://linux-hardware.org/?probe=ac449d0411) | Oct 21, 2022 |
| HP            | Stream Notebook             | Notebook    | [685271f268](https://linux-hardware.org/?probe=685271f268) | Oct 21, 2022 |
| Acer          | Predator PH517-61           | Notebook    | [e30217884a](https://linux-hardware.org/?probe=e30217884a) | Oct 21, 2022 |
| Gigabyte      | GA-78LMT-S2 sex             | Desktop     | [95ddb7c758](https://linux-hardware.org/?probe=95ddb7c758) | Oct 21, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [31d7e67080](https://linux-hardware.org/?probe=31d7e67080) | Oct 21, 2022 |
| Acer          | Aspire A315-33              | Notebook    | [1358385d49](https://linux-hardware.org/?probe=1358385d49) | Oct 20, 2022 |
| ASUSTek       | T200TAC                     | Notebook    | [0aad9d8ecd](https://linux-hardware.org/?probe=0aad9d8ecd) | Oct 20, 2022 |
| OEM           | G41 775 ICH7 8712           | Desktop     | [354afbd4d8](https://linux-hardware.org/?probe=354afbd4d8) | Oct 20, 2022 |
| ASUSTek       | T101HA                      | Tablet      | [f31749db41](https://linux-hardware.org/?probe=f31749db41) | Oct 20, 2022 |
| ASUSTek       | T101HA                      | Tablet      | [8ae5de2c7d](https://linux-hardware.org/?probe=8ae5de2c7d) | Oct 20, 2022 |
| OEM           | G41 775 ICH7 8712           | Desktop     | [2991e146ce](https://linux-hardware.org/?probe=2991e146ce) | Oct 19, 2022 |
| HP            | G62                         | Notebook    | [721c09b331](https://linux-hardware.org/?probe=721c09b331) | Oct 19, 2022 |
| Microtech     | CoreBook                    | Notebook    | [0592b30e41](https://linux-hardware.org/?probe=0592b30e41) | Oct 19, 2022 |
| Microtech     | CoreBook                    | Notebook    | [536451ed8a](https://linux-hardware.org/?probe=536451ed8a) | Oct 19, 2022 |
| ASRock        | 970 Extreme3                | Desktop     | [23f7ae20e3](https://linux-hardware.org/?probe=23f7ae20e3) | Oct 19, 2022 |
| Dell          | Studio 1458                 | Notebook    | [57b5c85b2a](https://linux-hardware.org/?probe=57b5c85b2a) | Oct 19, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [5d1bb5d8aa](https://linux-hardware.org/?probe=5d1bb5d8aa) | Oct 19, 2022 |
| ASUSTek       | T200TAC                     | Notebook    | [c33c750766](https://linux-hardware.org/?probe=c33c750766) | Oct 18, 2022 |
| Dell          | 0GTK4K A02                  | Desktop     | [f92314f74b](https://linux-hardware.org/?probe=f92314f74b) | Oct 18, 2022 |
| HP            | Notebook                    | Notebook    | [01692e8f30](https://linux-hardware.org/?probe=01692e8f30) | Oct 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ff6d42a3ef](https://linux-hardware.org/?probe=ff6d42a3ef) | Oct 17, 2022 |
| Acer          | Aspire E5-411               | Notebook    | [01979e17ce](https://linux-hardware.org/?probe=01979e17ce) | Oct 17, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [4b0c3a6022](https://linux-hardware.org/?probe=4b0c3a6022) | Oct 17, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [f188526e04](https://linux-hardware.org/?probe=f188526e04) | Oct 17, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [50c44df4fb](https://linux-hardware.org/?probe=50c44df4fb) | Oct 17, 2022 |
| Apple         | MacBookPro5,4               | Notebook    | [bc6696e1d5](https://linux-hardware.org/?probe=bc6696e1d5) | Oct 17, 2022 |
| Toshiba       | Satellite C55-A             | Notebook    | [f93fb31ad5](https://linux-hardware.org/?probe=f93fb31ad5) | Oct 16, 2022 |
| ASUSTek       | H97-PLUS                    | Desktop     | [0c025c3b68](https://linux-hardware.org/?probe=0c025c3b68) | Oct 16, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [c4a0f6af56](https://linux-hardware.org/?probe=c4a0f6af56) | Oct 16, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [cde8c87a3a](https://linux-hardware.org/?probe=cde8c87a3a) | Oct 16, 2022 |
| Dell          | Inspiron 14 5401            | Notebook    | [9c955c6521](https://linux-hardware.org/?probe=9c955c6521) | Oct 16, 2022 |
| Dell          | Inspiron 14 5401            | Notebook    | [5fbc33b9bf](https://linux-hardware.org/?probe=5fbc33b9bf) | Oct 16, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [732c7afd4c](https://linux-hardware.org/?probe=732c7afd4c) | Oct 16, 2022 |
| HP            | 1790                        | Desktop     | [5b9b2357c5](https://linux-hardware.org/?probe=5b9b2357c5) | Oct 16, 2022 |
| Dell          | 0XGMD0 A00                  | All in one  | [e38169d409](https://linux-hardware.org/?probe=e38169d409) | Oct 16, 2022 |
| Intel         | H55                         | Desktop     | [ab27a6c8d9](https://linux-hardware.org/?probe=ab27a6c8d9) | Oct 15, 2022 |
| Google        | Lars                        | Notebook    | [b607a23c77](https://linux-hardware.org/?probe=b607a23c77) | Oct 14, 2022 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [bb7d61198e](https://linux-hardware.org/?probe=bb7d61198e) | Oct 14, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [772645390a](https://linux-hardware.org/?probe=772645390a) | Oct 14, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [7e770fd62b](https://linux-hardware.org/?probe=7e770fd62b) | Oct 14, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | Notebook    | [e4c404552a](https://linux-hardware.org/?probe=e4c404552a) | Oct 13, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [4fe76d84fd](https://linux-hardware.org/?probe=4fe76d84fd) | Oct 13, 2022 |
| HP            | 18E7                        | Desktop     | [98b59ebfce](https://linux-hardware.org/?probe=98b59ebfce) | Oct 13, 2022 |
| HP            | 0AA0h                       | Desktop     | [f4a69ac6f5](https://linux-hardware.org/?probe=f4a69ac6f5) | Oct 13, 2022 |
| Dell          | Vostro 3558                 | Notebook    | [855e0d050c](https://linux-hardware.org/?probe=855e0d050c) | Oct 13, 2022 |
| Dell          | Latitude E6330              | Notebook    | [815d48ffba](https://linux-hardware.org/?probe=815d48ffba) | Oct 12, 2022 |
| HP            | 2AF3                        | Desktop     | [f59df65c18](https://linux-hardware.org/?probe=f59df65c18) | Oct 12, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [e8dd0752ac](https://linux-hardware.org/?probe=e8dd0752ac) | Oct 12, 2022 |
| Unknown       | Unknown                     | Desktop     | [bfd4bad69d](https://linux-hardware.org/?probe=bfd4bad69d) | Oct 11, 2022 |
| Dell          | Latitude E6410              | Notebook    | [9ed4124073](https://linux-hardware.org/?probe=9ed4124073) | Oct 11, 2022 |
| HP            | 304Ah                       | Desktop     | [69f11e2008](https://linux-hardware.org/?probe=69f11e2008) | Oct 11, 2022 |
| TERRA         | TERRAPC                     | Notebook    | [048f3ad5ef](https://linux-hardware.org/?probe=048f3ad5ef) | Oct 11, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [da36ee9925](https://linux-hardware.org/?probe=da36ee9925) | Oct 11, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [5c2dd967f9](https://linux-hardware.org/?probe=5c2dd967f9) | Oct 11, 2022 |
| Alienware     | 0NWN7M A00                  | Desktop     | [a7c3e67810](https://linux-hardware.org/?probe=a7c3e67810) | Oct 10, 2022 |
| Acer          | Aspire A315-33              | Notebook    | [8606cbf7cc](https://linux-hardware.org/?probe=8606cbf7cc) | Oct 10, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [f6e7e1585c](https://linux-hardware.org/?probe=f6e7e1585c) | Oct 10, 2022 |
| Dell          | 0X9M3X A01                  | Desktop     | [b729cadad8](https://linux-hardware.org/?probe=b729cadad8) | Oct 10, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [897321f579](https://linux-hardware.org/?probe=897321f579) | Oct 09, 2022 |
| ASUSTek       | H81M-P                      | Desktop     | [907b7761d0](https://linux-hardware.org/?probe=907b7761d0) | Oct 09, 2022 |
| ASUSTek       | H81M-P                      | Desktop     | [f2d9df375d](https://linux-hardware.org/?probe=f2d9df375d) | Oct 09, 2022 |
| Panasonic     | CF-19-8                     | Notebook    | [439e2c8122](https://linux-hardware.org/?probe=439e2c8122) | Oct 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [fef2c17618](https://linux-hardware.org/?probe=fef2c17618) | Oct 09, 2022 |
| Panasonic     | CF-19-8                     | Notebook    | [bc5820629b](https://linux-hardware.org/?probe=bc5820629b) | Oct 09, 2022 |
| Packard Be... | EasyNote TM82               | Notebook    | [8e3ecfd03d](https://linux-hardware.org/?probe=8e3ecfd03d) | Oct 08, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [d1c01a07a2](https://linux-hardware.org/?probe=d1c01a07a2) | Oct 08, 2022 |
| Acer          | EM61SM/EM61PM               | Desktop     | [58d2cda88f](https://linux-hardware.org/?probe=58d2cda88f) | Oct 08, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [0b225367b8](https://linux-hardware.org/?probe=0b225367b8) | Oct 08, 2022 |
| Dell          | Latitude E6410              | Notebook    | [0b617be9dd](https://linux-hardware.org/?probe=0b617be9dd) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [46b44504df](https://linux-hardware.org/?probe=46b44504df) | Oct 08, 2022 |
| AXDIA Inte... | WINBOOK 13                  | Notebook    | [35638411ee](https://linux-hardware.org/?probe=35638411ee) | Oct 08, 2022 |
| Fujitsu       | LIFEBOOK LH531              | Notebook    | [21a68d8c0e](https://linux-hardware.org/?probe=21a68d8c0e) | Oct 08, 2022 |
| ASUSTek       | CM1630                      | Desktop     | [dc63e03d48](https://linux-hardware.org/?probe=dc63e03d48) | Oct 08, 2022 |
| Gateway       | SX2851                      | Desktop     | [2cc7e399b2](https://linux-hardware.org/?probe=2cc7e399b2) | Oct 08, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [19db5a4e7c](https://linux-hardware.org/?probe=19db5a4e7c) | Oct 07, 2022 |
| TERRA         | TERRAPC                     | Notebook    | [ec9068f7ea](https://linux-hardware.org/?probe=ec9068f7ea) | Oct 07, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [005d2d7671](https://linux-hardware.org/?probe=005d2d7671) | Oct 07, 2022 |
| HP            | 822A                        | Desktop     | [c893a1b314](https://linux-hardware.org/?probe=c893a1b314) | Oct 07, 2022 |
| Apple         | MacBookPro9,1               | Notebook    | [d5a346bdd1](https://linux-hardware.org/?probe=d5a346bdd1) | Oct 07, 2022 |
| Dell          | 0YP696 A00                  | Desktop     | [588d3a6132](https://linux-hardware.org/?probe=588d3a6132) | Oct 07, 2022 |
| HP            | 8265                        | Desktop     | [ddf5f03d86](https://linux-hardware.org/?probe=ddf5f03d86) | Oct 07, 2022 |
| HP            | 843B                        | Desktop     | [5a744e115f](https://linux-hardware.org/?probe=5a744e115f) | Oct 06, 2022 |
| Dell          | Vostro 2520                 | Notebook    | [da789d3a06](https://linux-hardware.org/?probe=da789d3a06) | Oct 06, 2022 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [2e57f97484](https://linux-hardware.org/?probe=2e57f97484) | Oct 06, 2022 |
| Dell          | Latitude E6500              | Notebook    | [84fa5b35ed](https://linux-hardware.org/?probe=84fa5b35ed) | Oct 06, 2022 |
| Acer          | Aspire E1-522               | Notebook    | [769baa3828](https://linux-hardware.org/?probe=769baa3828) | Oct 05, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [397e5be75c](https://linux-hardware.org/?probe=397e5be75c) | Oct 05, 2022 |
| HP            | 2B60 MVB                    | Desktop     | [092e063471](https://linux-hardware.org/?probe=092e063471) | Oct 05, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [5bb972fab4](https://linux-hardware.org/?probe=5bb972fab4) | Oct 05, 2022 |
| Hampoo        | C3W6_AP108_4GB Reserved     | Notebook    | [9b8dc565f9](https://linux-hardware.org/?probe=9b8dc565f9) | Oct 04, 2022 |
| Gigabyte      | AORUS 7 SB                  | Notebook    | [444224d1e0](https://linux-hardware.org/?probe=444224d1e0) | Oct 04, 2022 |
| HP            | ENVY m6                     | Notebook    | [5c828496a7](https://linux-hardware.org/?probe=5c828496a7) | Oct 04, 2022 |
| Google        | Careena                     | Notebook    | [7ac4802a10](https://linux-hardware.org/?probe=7ac4802a10) | Oct 04, 2022 |
| Acer          | Extensa 2530                | Notebook    | [684b31b41d](https://linux-hardware.org/?probe=684b31b41d) | Oct 03, 2022 |
| HP            | ProBook 455 G6              | Notebook    | [acae78b85a](https://linux-hardware.org/?probe=acae78b85a) | Oct 03, 2022 |
| HP            | 3397                        | Desktop     | [eb6f8b5a56](https://linux-hardware.org/?probe=eb6f8b5a56) | Oct 03, 2022 |
| HP            | ProBook 455 G6              | Notebook    | [3697a412bd](https://linux-hardware.org/?probe=3697a412bd) | Oct 03, 2022 |
| ASUSTek       | X756UQ                      | Notebook    | [e17cbbf886](https://linux-hardware.org/?probe=e17cbbf886) | Oct 03, 2022 |
| ASUSTek       | X756UQ                      | Notebook    | [5767aaf6db](https://linux-hardware.org/?probe=5767aaf6db) | Oct 03, 2022 |
| ASUSTek       | P7H55-USB3                  | Desktop     | [9f15eece8f](https://linux-hardware.org/?probe=9f15eece8f) | Oct 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d3bcd51be1](https://linux-hardware.org/?probe=d3bcd51be1) | Oct 03, 2022 |
| ASUSTek       | M3A78-EM                    | Desktop     | [0c58d8b873](https://linux-hardware.org/?probe=0c58d8b873) | Oct 03, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [b8d65ced41](https://linux-hardware.org/?probe=b8d65ced41) | Oct 02, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [b5b057439d](https://linux-hardware.org/?probe=b5b057439d) | Oct 02, 2022 |
| Lenovo        | V570 1066EDG                | Notebook    | [8e2439c590](https://linux-hardware.org/?probe=8e2439c590) | Oct 01, 2022 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [592adc6c9b](https://linux-hardware.org/?probe=592adc6c9b) | Oct 01, 2022 |
| HP            | 843B                        | Desktop     | [b683039e3b](https://linux-hardware.org/?probe=b683039e3b) | Oct 01, 2022 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | Notebook    | [dc7e0ada81](https://linux-hardware.org/?probe=dc7e0ada81) | Oct 01, 2022 |
| Acer          | Aspire 4733Z                | Notebook    | [4be4debbe5](https://linux-hardware.org/?probe=4be4debbe5) | Oct 01, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [f42501fcc3](https://linux-hardware.org/?probe=f42501fcc3) | Oct 01, 2022 |
| Hampoo        | C3W6_AP108_4GB Reserved     | Notebook    | [93d3e41339](https://linux-hardware.org/?probe=93d3e41339) | Oct 01, 2022 |
| Biostar       | B350ET2                     | Desktop     | [d7c5b1ad40](https://linux-hardware.org/?probe=d7c5b1ad40) | Oct 01, 2022 |
| Biostar       | B350ET2                     | Desktop     | [2b7bea0eda](https://linux-hardware.org/?probe=2b7bea0eda) | Sep 30, 2022 |
| Notebook      | NJ50GU                      | Notebook    | [430d3b2873](https://linux-hardware.org/?probe=430d3b2873) | Sep 30, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [1f142c7087](https://linux-hardware.org/?probe=1f142c7087) | Sep 30, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [263313ef38](https://linux-hardware.org/?probe=263313ef38) | Sep 30, 2022 |
| MSI           | Z97 MPOWER                  | Desktop     | [f16a15a5b7](https://linux-hardware.org/?probe=f16a15a5b7) | Sep 30, 2022 |
| Apple         | Mac-F4218EC8 DVT            | All in one  | [1a331f2583](https://linux-hardware.org/?probe=1a331f2583) | Sep 30, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [8c116d30f9](https://linux-hardware.org/?probe=8c116d30f9) | Sep 30, 2022 |
| HP            | Pavilion Laptop 17-ar0xx    | Notebook    | [733654d30d](https://linux-hardware.org/?probe=733654d30d) | Sep 30, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [cc4740fa37](https://linux-hardware.org/?probe=cc4740fa37) | Sep 30, 2022 |
| Notebook      | NJ50_70CU                   | Notebook    | [4914d3ffe1](https://linux-hardware.org/?probe=4914d3ffe1) | Sep 29, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [7bffcb84c2](https://linux-hardware.org/?probe=7bffcb84c2) | Sep 29, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [e3e6ad5c35](https://linux-hardware.org/?probe=e3e6ad5c35) | Sep 29, 2022 |
| Irbis         | NB61 WS001                  | Notebook    | [3fda78e356](https://linux-hardware.org/?probe=3fda78e356) | Sep 29, 2022 |
| HP            | 8055                        | Desktop     | [aa3bd09485](https://linux-hardware.org/?probe=aa3bd09485) | Sep 29, 2022 |
| HP            | Compaq 6730s                | Notebook    | [565b94d7f4](https://linux-hardware.org/?probe=565b94d7f4) | Sep 29, 2022 |
| HP            | 843C                        | Desktop     | [e27595d303](https://linux-hardware.org/?probe=e27595d303) | Sep 29, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [01ebd7e70b](https://linux-hardware.org/?probe=01ebd7e70b) | Sep 29, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [d2c06711d7](https://linux-hardware.org/?probe=d2c06711d7) | Sep 29, 2022 |
| HP            | Compaq 6730s                | Notebook    | [62fc1b721e](https://linux-hardware.org/?probe=62fc1b721e) | Sep 29, 2022 |
| Dell          | Inspiron 3582               | Notebook    | [8cd21b783a](https://linux-hardware.org/?probe=8cd21b783a) | Sep 28, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | Notebook    | [defae2e862](https://linux-hardware.org/?probe=defae2e862) | Sep 28, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [c23649cdd4](https://linux-hardware.org/?probe=c23649cdd4) | Sep 28, 2022 |
| Dell          | Latitude E6520              | Notebook    | [e228fa6546](https://linux-hardware.org/?probe=e228fa6546) | Sep 28, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [3052bded51](https://linux-hardware.org/?probe=3052bded51) | Sep 28, 2022 |
| ASUSTek       | P5K                         | Desktop     | [2d278ddcdf](https://linux-hardware.org/?probe=2d278ddcdf) | Sep 28, 2022 |
| Toshiba       | Satellite L855              | Notebook    | [19e5b180eb](https://linux-hardware.org/?probe=19e5b180eb) | Sep 28, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [f501591d1b](https://linux-hardware.org/?probe=f501591d1b) | Sep 27, 2022 |
| ASUSTek       | B85M-E/BR                   | Desktop     | [5116d1cae9](https://linux-hardware.org/?probe=5116d1cae9) | Sep 27, 2022 |
| Dell          | XPS 8700                    | Desktop     | [19fff8b508](https://linux-hardware.org/?probe=19fff8b508) | Sep 27, 2022 |
| Dell          | 0WN7Y6 A01                  | Desktop     | [356dc77824](https://linux-hardware.org/?probe=356dc77824) | Sep 27, 2022 |
| Dell          | System Inspiron N7110       | Notebook    | [016d5e3146](https://linux-hardware.org/?probe=016d5e3146) | Sep 27, 2022 |
| ASUSTek       | M3A78-EM                    | Desktop     | [34287ac52a](https://linux-hardware.org/?probe=34287ac52a) | Sep 27, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [75d51e6237](https://linux-hardware.org/?probe=75d51e6237) | Sep 26, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [e777d38fbd](https://linux-hardware.org/?probe=e777d38fbd) | Sep 26, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [c45069d56d](https://linux-hardware.org/?probe=c45069d56d) | Sep 26, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [3441e0cac3](https://linux-hardware.org/?probe=3441e0cac3) | Sep 26, 2022 |
| ASUSTek       | X201EP                      | Notebook    | [4e6c202d5d](https://linux-hardware.org/?probe=4e6c202d5d) | Sep 26, 2022 |
| Unknown       | NB-7000                     | Notebook    | [1713526cff](https://linux-hardware.org/?probe=1713526cff) | Sep 25, 2022 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | Notebook    | [28e086b848](https://linux-hardware.org/?probe=28e086b848) | Sep 25, 2022 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | Notebook    | [6a8d9c1d7a](https://linux-hardware.org/?probe=6a8d9c1d7a) | Sep 25, 2022 |
| Gateway       | FMCP7AM                     | Desktop     | [0cb51f3e6f](https://linux-hardware.org/?probe=0cb51f3e6f) | Sep 25, 2022 |
| ASUSTek       | PRO A320M-R WI-FI           | Desktop     | [e760f06cef](https://linux-hardware.org/?probe=e760f06cef) | Sep 25, 2022 |
| Dell          | Inspiron 14-3452            | Notebook    | [bb90844ff6](https://linux-hardware.org/?probe=bb90844ff6) | Sep 25, 2022 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [33a0b663ea](https://linux-hardware.org/?probe=33a0b663ea) | Sep 25, 2022 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [d8a451b3e6](https://linux-hardware.org/?probe=d8a451b3e6) | Sep 25, 2022 |
| Dell          | Inspiron 3185               | Notebook    | [561c02f958](https://linux-hardware.org/?probe=561c02f958) | Sep 25, 2022 |
| ASRock        | QC5000M-ITX/PH              | Desktop     | [571b95c201](https://linux-hardware.org/?probe=571b95c201) | Sep 25, 2022 |
| Acer          | Extensa 5635ZG              | Notebook    | [ade183eadc](https://linux-hardware.org/?probe=ade183eadc) | Sep 24, 2022 |
| HP            | 18E7                        | Desktop     | [71a12280de](https://linux-hardware.org/?probe=71a12280de) | Sep 24, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [fab0eac5a6](https://linux-hardware.org/?probe=fab0eac5a6) | Sep 24, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [dc3a97d467](https://linux-hardware.org/?probe=dc3a97d467) | Sep 23, 2022 |
| HP            | EliteBook Revolve 810 G3    | Notebook    | [77b578f861](https://linux-hardware.org/?probe=77b578f861) | Sep 23, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [9ccc1b86a7](https://linux-hardware.org/?probe=9ccc1b86a7) | Sep 23, 2022 |
| ASRock        | B85M Pro4                   | Desktop     | [cd75d968d7](https://linux-hardware.org/?probe=cd75d968d7) | Sep 23, 2022 |
| Lenovo        | ThinkPad Edge E530 3259C... | Notebook    | [cdaec9c224](https://linux-hardware.org/?probe=cdaec9c224) | Sep 22, 2022 |
| ASUSTek       | P5K                         | Desktop     | [0ddf0a48dd](https://linux-hardware.org/?probe=0ddf0a48dd) | Sep 22, 2022 |
| Pegatron      | 2ACD                        | Desktop     | [d6270f88cc](https://linux-hardware.org/?probe=d6270f88cc) | Sep 22, 2022 |
| HP            | ENVY Notebook               | Notebook    | [1eef25f6d8](https://linux-hardware.org/?probe=1eef25f6d8) | Sep 22, 2022 |
| HP            | ENVY Notebook               | Notebook    | [b95a98e133](https://linux-hardware.org/?probe=b95a98e133) | Sep 22, 2022 |
| HP            | 8055                        | Desktop     | [c72e0ed04b](https://linux-hardware.org/?probe=c72e0ed04b) | Sep 22, 2022 |
| Acer          | Aspire ES1-512              | Notebook    | [00e679e86c](https://linux-hardware.org/?probe=00e679e86c) | Sep 22, 2022 |
| Acer          | Aspire ES1-512              | Notebook    | [318436c7ab](https://linux-hardware.org/?probe=318436c7ab) | Sep 22, 2022 |
| ASUSTek       | 1201PN                      | Notebook    | [3dd4546344](https://linux-hardware.org/?probe=3dd4546344) | Sep 21, 2022 |
| ASUSTek       | 1201PN                      | Notebook    | [080d9c8964](https://linux-hardware.org/?probe=080d9c8964) | Sep 21, 2022 |
| ASUSTek       | Benicia                     | Desktop     | [22bf75699c](https://linux-hardware.org/?probe=22bf75699c) | Sep 21, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [0f81852612](https://linux-hardware.org/?probe=0f81852612) | Sep 21, 2022 |
| Toshiba       | Satellite L855              | Notebook    | [4421e54d32](https://linux-hardware.org/?probe=4421e54d32) | Sep 21, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | Notebook    | [6d0a2986ad](https://linux-hardware.org/?probe=6d0a2986ad) | Sep 21, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | Desktop     | [f49e8d08ef](https://linux-hardware.org/?probe=f49e8d08ef) | Sep 20, 2022 |
| Alienware     | 18                          | Notebook    | [91d0153265](https://linux-hardware.org/?probe=91d0153265) | Sep 20, 2022 |
| Dell          | 0D441T A01                  | Desktop     | [c315329853](https://linux-hardware.org/?probe=c315329853) | Sep 20, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [82b3d89bf9](https://linux-hardware.org/?probe=82b3d89bf9) | Sep 20, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [37dbdb48dd](https://linux-hardware.org/?probe=37dbdb48dd) | Sep 20, 2022 |
| Dell          | G15 5515                    | Notebook    | [f308590417](https://linux-hardware.org/?probe=f308590417) | Sep 20, 2022 |
| Dell          | G15 5515                    | Notebook    | [d6a647ab30](https://linux-hardware.org/?probe=d6a647ab30) | Sep 20, 2022 |
| HP            | Pavilion g7                 | Notebook    | [d51d3d282a](https://linux-hardware.org/?probe=d51d3d282a) | Sep 20, 2022 |
| Samsung       | 950XCJ/951XCJ/950XCR        | Notebook    | [9417681a63](https://linux-hardware.org/?probe=9417681a63) | Sep 19, 2022 |
| Lenovo        | ThinkCentre M71e 3157AE2    | Desktop     | [9022058466](https://linux-hardware.org/?probe=9022058466) | Sep 19, 2022 |
| Dell          | Latitude E6540              | Notebook    | [d3140eaa89](https://linux-hardware.org/?probe=d3140eaa89) | Sep 19, 2022 |
| Alienware     | 18                          | Notebook    | [fda9eabd7e](https://linux-hardware.org/?probe=fda9eabd7e) | Sep 18, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [bceb6698c2](https://linux-hardware.org/?probe=bceb6698c2) | Sep 18, 2022 |
| Microtech     | CoreBook                    | Notebook    | [6b1a53d2c2](https://linux-hardware.org/?probe=6b1a53d2c2) | Sep 18, 2022 |
| HP            | 0AA8h                       | Desktop     | [c79bdb21ed](https://linux-hardware.org/?probe=c79bdb21ed) | Sep 18, 2022 |
| Ematic        | EWT118                      | Notebook    | [41670ebd30](https://linux-hardware.org/?probe=41670ebd30) | Sep 18, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [a5d838868a](https://linux-hardware.org/?probe=a5d838868a) | Sep 18, 2022 |
| Lenovo        | ThinkCentre M58e 7298A76    | Desktop     | [4775ccd67f](https://linux-hardware.org/?probe=4775ccd67f) | Sep 18, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [24534d00db](https://linux-hardware.org/?probe=24534d00db) | Sep 17, 2022 |
| Dell          | Latitude E6510              | Notebook    | [ee09885560](https://linux-hardware.org/?probe=ee09885560) | Sep 16, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [e7bb3017fb](https://linux-hardware.org/?probe=e7bb3017fb) | Sep 16, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [c81727b775](https://linux-hardware.org/?probe=c81727b775) | Sep 16, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | Notebook    | [5620510083](https://linux-hardware.org/?probe=5620510083) | Sep 16, 2022 |
| Dell          | Latitude E4300              | Notebook    | [b3c04d8a81](https://linux-hardware.org/?probe=b3c04d8a81) | Sep 16, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [eeb58ef0f2](https://linux-hardware.org/?probe=eeb58ef0f2) | Sep 15, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [258c624b3b](https://linux-hardware.org/?probe=258c624b3b) | Sep 15, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [875435f3f0](https://linux-hardware.org/?probe=875435f3f0) | Sep 15, 2022 |
| Toshiba       | Satellite C855              | Notebook    | [bd34f35e50](https://linux-hardware.org/?probe=bd34f35e50) | Sep 15, 2022 |
| ASRock        | H61M-DGS                    | Desktop     | [aeac7cfb74](https://linux-hardware.org/?probe=aeac7cfb74) | Sep 14, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [32884ec101](https://linux-hardware.org/?probe=32884ec101) | Sep 14, 2022 |
| Dell          | 0TW904 A01                  | Desktop     | [141188a631](https://linux-hardware.org/?probe=141188a631) | Sep 14, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | Notebook    | [676dbc76db](https://linux-hardware.org/?probe=676dbc76db) | Sep 13, 2022 |
| Gigabyte      | Z77-D3H                     | Desktop     | [b1b929517d](https://linux-hardware.org/?probe=b1b929517d) | Sep 13, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [3c13816886](https://linux-hardware.org/?probe=3c13816886) | Sep 13, 2022 |
| Samsung       | 800G5M/800G5W               | Notebook    | [ad3cd5381f](https://linux-hardware.org/?probe=ad3cd5381f) | Sep 13, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [b404f51fbe](https://linux-hardware.org/?probe=b404f51fbe) | Sep 12, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [ca9a099cf6](https://linux-hardware.org/?probe=ca9a099cf6) | Sep 12, 2022 |
| Samsung       | 600B4B/600B5B               | Notebook    | [25c2b764a6](https://linux-hardware.org/?probe=25c2b764a6) | Sep 12, 2022 |
| Zinox Tech... | x64-Based PC                | Tablet      | [4618d27b09](https://linux-hardware.org/?probe=4618d27b09) | Sep 11, 2022 |
| Dell          | Latitude E7240              | Notebook    | [72a8c650c5](https://linux-hardware.org/?probe=72a8c650c5) | Sep 11, 2022 |
| Lenovo        | SDK0J40700 WIN              | Desktop     | [b8f3a58a03](https://linux-hardware.org/?probe=b8f3a58a03) | Sep 11, 2022 |
| Gigabyte      | G1.Sniper Z97               | Desktop     | [445e54016b](https://linux-hardware.org/?probe=445e54016b) | Sep 11, 2022 |
| Gigabyte      | P64V7                       | Notebook    | [b9d2c998be](https://linux-hardware.org/?probe=b9d2c998be) | Sep 11, 2022 |
| UMAX          | VisionBook N14G Plus        | Notebook    | [6d05deca49](https://linux-hardware.org/?probe=6d05deca49) | Sep 11, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [0701918099](https://linux-hardware.org/?probe=0701918099) | Sep 11, 2022 |
| HP            | 0A54h                       | Desktop     | [2c88c7fd30](https://linux-hardware.org/?probe=2c88c7fd30) | Sep 10, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [e6bf2b7f3f](https://linux-hardware.org/?probe=e6bf2b7f3f) | Sep 10, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | Desktop     | [d13cf99728](https://linux-hardware.org/?probe=d13cf99728) | Sep 10, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [1e43753d7a](https://linux-hardware.org/?probe=1e43753d7a) | Sep 10, 2022 |
| MSI           | 2AE0                        | Desktop     | [a2b046dd4e](https://linux-hardware.org/?probe=a2b046dd4e) | Sep 10, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [c027a7cf99](https://linux-hardware.org/?probe=c027a7cf99) | Sep 10, 2022 |
| HP            | Pavilion dv6700             | Notebook    | [4e96c157b7](https://linux-hardware.org/?probe=4e96c157b7) | Sep 10, 2022 |
| HP            | 3031h                       | Desktop     | [ea434d67b5](https://linux-hardware.org/?probe=ea434d67b5) | Sep 10, 2022 |
| HP            | 3031h                       | Desktop     | [feddf42c9f](https://linux-hardware.org/?probe=feddf42c9f) | Sep 10, 2022 |
| AZW           | Z83-V                       | Notebook    | [70e8dba2ef](https://linux-hardware.org/?probe=70e8dba2ef) | Sep 10, 2022 |
| AZW           | Z83-V                       | Notebook    | [622725ab19](https://linux-hardware.org/?probe=622725ab19) | Sep 10, 2022 |
| Acer          | Aspire 7745G                | Notebook    | [a41158c2cc](https://linux-hardware.org/?probe=a41158c2cc) | Sep 10, 2022 |
| HP            | 0AA8h                       | Desktop     | [4e9a1e883c](https://linux-hardware.org/?probe=4e9a1e883c) | Sep 09, 2022 |
| Toshiba       | Satellite P200              | Notebook    | [c49fec0796](https://linux-hardware.org/?probe=c49fec0796) | Sep 09, 2022 |
| Medion        | Akoya E1318T                | Notebook    | [749a12fd63](https://linux-hardware.org/?probe=749a12fd63) | Sep 09, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [678759289b](https://linux-hardware.org/?probe=678759289b) | Sep 09, 2022 |
| Acer          | Aspire C22-820              | All in one  | [7b21589632](https://linux-hardware.org/?probe=7b21589632) | Sep 09, 2022 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [e11963681c](https://linux-hardware.org/?probe=e11963681c) | Sep 08, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [db80996c7a](https://linux-hardware.org/?probe=db80996c7a) | Sep 08, 2022 |
| HP            | Laptop 17-bs0xx             | Notebook    | [ebf0bfea05](https://linux-hardware.org/?probe=ebf0bfea05) | Sep 08, 2022 |
| Dell          | Latitude E5420              | Notebook    | [b80d26540d](https://linux-hardware.org/?probe=b80d26540d) | Sep 08, 2022 |
| ASUSTek       | UX331UA                     | Notebook    | [e1e0acfdf3](https://linux-hardware.org/?probe=e1e0acfdf3) | Sep 08, 2022 |
| Dell          | Latitude E4300              | Notebook    | [5d3a9edf5d](https://linux-hardware.org/?probe=5d3a9edf5d) | Sep 07, 2022 |
| Lenovo        | MAHOBAY                     | Desktop     | [2619e261d1](https://linux-hardware.org/?probe=2619e261d1) | Sep 07, 2022 |
| Lenovo        | ThinkPad E570 20H50047US    | Notebook    | [70b198055e](https://linux-hardware.org/?probe=70b198055e) | Sep 07, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [dd20f0351c](https://linux-hardware.org/?probe=dd20f0351c) | Sep 06, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [3aca46f88b](https://linux-hardware.org/?probe=3aca46f88b) | Sep 06, 2022 |
| HP            | 15                          | Notebook    | [c02361a2ff](https://linux-hardware.org/?probe=c02361a2ff) | Sep 06, 2022 |
| ASUSTek       | A88X-GAMER                  | Desktop     | [15fe45edd7](https://linux-hardware.org/?probe=15fe45edd7) | Sep 06, 2022 |
| Lenovo        | G400s VILG1                 | Notebook    | [44c27d1083](https://linux-hardware.org/?probe=44c27d1083) | Sep 06, 2022 |
| Lenovo        | G400s VILG1                 | Notebook    | [ec3283d49b](https://linux-hardware.org/?probe=ec3283d49b) | Sep 06, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | Desktop     | [92ff48d462](https://linux-hardware.org/?probe=92ff48d462) | Sep 06, 2022 |
| HP            | 2AF7                        | Desktop     | [9b7ccd5aa0](https://linux-hardware.org/?probe=9b7ccd5aa0) | Sep 06, 2022 |
| HP            | Pavilion g7                 | Notebook    | [5ed29a7629](https://linux-hardware.org/?probe=5ed29a7629) | Sep 05, 2022 |
| Dell          | 0HY9JP A02                  | Desktop     | [7cbf141461](https://linux-hardware.org/?probe=7cbf141461) | Sep 05, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [88c4e0664a](https://linux-hardware.org/?probe=88c4e0664a) | Sep 05, 2022 |
| HP            | G62                         | Notebook    | [a3f84f3bf8](https://linux-hardware.org/?probe=a3f84f3bf8) | Sep 05, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [d0ec4eb9cc](https://linux-hardware.org/?probe=d0ec4eb9cc) | Sep 05, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [e7061e11ff](https://linux-hardware.org/?probe=e7061e11ff) | Sep 04, 2022 |
| Lenovo        | G560 20042                  | Notebook    | [c661e65b46](https://linux-hardware.org/?probe=c661e65b46) | Sep 04, 2022 |
| Lenovo        | G560 20042                  | Notebook    | [ad86775475](https://linux-hardware.org/?probe=ad86775475) | Sep 04, 2022 |
| HP            | Pavilion dv6500             | Notebook    | [eec792ef79](https://linux-hardware.org/?probe=eec792ef79) | Sep 04, 2022 |
| HP            | Pavilion dv6500             | Notebook    | [0751d35153](https://linux-hardware.org/?probe=0751d35153) | Sep 04, 2022 |
| ASRock        | B550M/ac                    | Desktop     | [b8ccaa27ef](https://linux-hardware.org/?probe=b8ccaa27ef) | Sep 04, 2022 |
| HP            | 821D                        | Desktop     | [459bdd177e](https://linux-hardware.org/?probe=459bdd177e) | Sep 03, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [079d33f9b2](https://linux-hardware.org/?probe=079d33f9b2) | Sep 03, 2022 |
| ASUSTek       | P8B75-V                     | Desktop     | [2ae6d7c950](https://linux-hardware.org/?probe=2ae6d7c950) | Sep 03, 2022 |
| HP            | 620                         | Notebook    | [096486e01d](https://linux-hardware.org/?probe=096486e01d) | Sep 03, 2022 |
| Itautec       | Infoway                     | Notebook    | [d207af3252](https://linux-hardware.org/?probe=d207af3252) | Sep 03, 2022 |
| Itautec       | Infoway                     | Notebook    | [737122a0d1](https://linux-hardware.org/?probe=737122a0d1) | Sep 03, 2022 |
| HP            | 87D6 SMVB                   | Desktop     | [e597d54472](https://linux-hardware.org/?probe=e597d54472) | Sep 03, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [c74752a0d2](https://linux-hardware.org/?probe=c74752a0d2) | Sep 02, 2022 |
| MSI           | H97 GAMING 3                | Desktop     | [a5fb8d7651](https://linux-hardware.org/?probe=a5fb8d7651) | Sep 02, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [63e2adf3a9](https://linux-hardware.org/?probe=63e2adf3a9) | Sep 02, 2022 |
| MSI           | MS-B9201                    | Desktop     | [7bbae05d63](https://linux-hardware.org/?probe=7bbae05d63) | Sep 01, 2022 |
| MSI           | MS-B9201                    | Desktop     | [0d04798699](https://linux-hardware.org/?probe=0d04798699) | Sep 01, 2022 |
| Positivo      | C14CR01                     | Notebook    | [ff4d1d45b7](https://linux-hardware.org/?probe=ff4d1d45b7) | Sep 01, 2022 |
| Positivo      | C14CR01                     | Notebook    | [d1fc217886](https://linux-hardware.org/?probe=d1fc217886) | Sep 01, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [2eb780855d](https://linux-hardware.org/?probe=2eb780855d) | Sep 01, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [f4d5b9fc69](https://linux-hardware.org/?probe=f4d5b9fc69) | Aug 31, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [82cda7dfe9](https://linux-hardware.org/?probe=82cda7dfe9) | Aug 31, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [194290f42c](https://linux-hardware.org/?probe=194290f42c) | Aug 31, 2022 |
| MSI           | H410M PRO                   | Desktop     | [e1184c4522](https://linux-hardware.org/?probe=e1184c4522) | Aug 31, 2022 |
| ASUSTek       | Benicia                     | Desktop     | [13454a57f9](https://linux-hardware.org/?probe=13454a57f9) | Aug 31, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [8e2cd928f3](https://linux-hardware.org/?probe=8e2cd928f3) | Aug 31, 2022 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [836644c18b](https://linux-hardware.org/?probe=836644c18b) | Aug 31, 2022 |
| Dell          | 0GXM1W A00                  | Desktop     | [b358b1d32b](https://linux-hardware.org/?probe=b358b1d32b) | Aug 31, 2022 |
| HP            | 2B38                        | Desktop     | [9170225d70](https://linux-hardware.org/?probe=9170225d70) | Aug 30, 2022 |
| JGINYUE       | B85M VH PLUS V1.0           | Desktop     | [8712171422](https://linux-hardware.org/?probe=8712171422) | Aug 30, 2022 |
| Gigabyte      | H61M-D2H-USB3               | Desktop     | [eb74fdbbbc](https://linux-hardware.org/?probe=eb74fdbbbc) | Aug 30, 2022 |
| Dell          | 0R092H                      | Desktop     | [85871600b3](https://linux-hardware.org/?probe=85871600b3) | Aug 30, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [a96a893eac](https://linux-hardware.org/?probe=a96a893eac) | Aug 30, 2022 |
| JGINYUE       | B85M VH PLUS V1.0           | Desktop     | [f065870080](https://linux-hardware.org/?probe=f065870080) | Aug 30, 2022 |
| Acer          | Aspire SW5-271              | Notebook    | [3446f93f1d](https://linux-hardware.org/?probe=3446f93f1d) | Aug 29, 2022 |
| Samsung       | 300E5M/300E5L               | Notebook    | [6f920f9002](https://linux-hardware.org/?probe=6f920f9002) | Aug 29, 2022 |
| Microsoft     | Surface Pro 6               | Tablet      | [be30fd63a0](https://linux-hardware.org/?probe=be30fd63a0) | Aug 29, 2022 |
| Microsoft     | Surface Pro 6               | Tablet      | [135f83007e](https://linux-hardware.org/?probe=135f83007e) | Aug 29, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [45bba02b35](https://linux-hardware.org/?probe=45bba02b35) | Aug 29, 2022 |
| MSI           | B250M PRO-VD                | Desktop     | [d462e3b9d0](https://linux-hardware.org/?probe=d462e3b9d0) | Aug 29, 2022 |
| Dell          | Latitude E5440              | Notebook    | [b0d92d186f](https://linux-hardware.org/?probe=b0d92d186f) | Aug 29, 2022 |
| HP            | EW7-I7D22875GR1             | Notebook    | [307b75624e](https://linux-hardware.org/?probe=307b75624e) | Aug 29, 2022 |
| ASRock        | Z170 Pro4                   | Desktop     | [eaa574481f](https://linux-hardware.org/?probe=eaa574481f) | Aug 29, 2022 |
| Lenovo        | ThinkPad L440 20ASA1V8BP    | Notebook    | [64f71278c7](https://linux-hardware.org/?probe=64f71278c7) | Aug 28, 2022 |
| HP            | 339A                        | Desktop     | [7338bebb05](https://linux-hardware.org/?probe=7338bebb05) | Aug 28, 2022 |
| ASRock        | H61M-DGS                    | Desktop     | [023204fa1f](https://linux-hardware.org/?probe=023204fa1f) | Aug 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [be59676867](https://linux-hardware.org/?probe=be59676867) | Aug 28, 2022 |
| WIPRO         | G31T-M                      | Desktop     | [51cea718eb](https://linux-hardware.org/?probe=51cea718eb) | Aug 28, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [04aec7a28a](https://linux-hardware.org/?probe=04aec7a28a) | Aug 28, 2022 |
| Google        | Butterfly                   | Notebook    | [df8fafaf3b](https://linux-hardware.org/?probe=df8fafaf3b) | Aug 28, 2022 |
| BESSTAR Te... | HM90                        | Desktop     | [134adccc85](https://linux-hardware.org/?probe=134adccc85) | Aug 27, 2022 |
| GHIA          | 2 en 1                      | Tablet      | [5ed07e6854](https://linux-hardware.org/?probe=5ed07e6854) | Aug 27, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [9a05044c38](https://linux-hardware.org/?probe=9a05044c38) | Aug 27, 2022 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [c8eb396b68](https://linux-hardware.org/?probe=c8eb396b68) | Aug 26, 2022 |
| ASUSTek       | ZenBook UX425UG_Q408UG      | Notebook    | [5b80fb349f](https://linux-hardware.org/?probe=5b80fb349f) | Aug 26, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [7c9f388153](https://linux-hardware.org/?probe=7c9f388153) | Aug 26, 2022 |
| Dell          | 0T656F A01                  | Desktop     | [d1bb410d06](https://linux-hardware.org/?probe=d1bb410d06) | Aug 26, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [c6fc39489e](https://linux-hardware.org/?probe=c6fc39489e) | Aug 26, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | Notebook    | [b56c1d75a6](https://linux-hardware.org/?probe=b56c1d75a6) | Aug 25, 2022 |
| Framework     | Laptop                      | Notebook    | [87e09551b3](https://linux-hardware.org/?probe=87e09551b3) | Aug 25, 2022 |
| ASUSTek       | SABERTOOTH Z87              | Desktop     | [02072aee33](https://linux-hardware.org/?probe=02072aee33) | Aug 25, 2022 |
| Gigabyte      | 970-GAMING                  | Desktop     | [dad1ede2be](https://linux-hardware.org/?probe=dad1ede2be) | Aug 25, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [5d03f69f35](https://linux-hardware.org/?probe=5d03f69f35) | Aug 25, 2022 |
| BESSTAR Te... | HM90                        | Desktop     | [8f13ff6ebd](https://linux-hardware.org/?probe=8f13ff6ebd) | Aug 24, 2022 |
| Dell          | Latitude E7240              | Notebook    | [0e15063cb3](https://linux-hardware.org/?probe=0e15063cb3) | Aug 24, 2022 |
| Dell          | Inspiron M5030              | Notebook    | [59eec9a80d](https://linux-hardware.org/?probe=59eec9a80d) | Aug 24, 2022 |
| Framework     | Laptop                      | Notebook    | [3c4bab3769](https://linux-hardware.org/?probe=3c4bab3769) | Aug 24, 2022 |
| Gigabyte      | 970-GAMING                  | Desktop     | [faa79b7d62](https://linux-hardware.org/?probe=faa79b7d62) | Aug 24, 2022 |
| HP            | 2AFB                        | Desktop     | [ea3ce3f8dd](https://linux-hardware.org/?probe=ea3ce3f8dd) | Aug 24, 2022 |
| Toshiba       | Satellite L855              | Notebook    | [73de62c6c7](https://linux-hardware.org/?probe=73de62c6c7) | Aug 24, 2022 |
| ASUSTek       | H81M-A/BR                   | Desktop     | [b9ac5d4051](https://linux-hardware.org/?probe=b9ac5d4051) | Aug 23, 2022 |
| Gigabyte      | H61M-D2H-USB3               | Desktop     | [eae2c82e26](https://linux-hardware.org/?probe=eae2c82e26) | Aug 23, 2022 |
| Dell          | Inspiron M5030              | Notebook    | [a43c618dbb](https://linux-hardware.org/?probe=a43c618dbb) | Aug 23, 2022 |
| HP            | Laptop 14-dq4xxx            | Notebook    | [8171eb84c2](https://linux-hardware.org/?probe=8171eb84c2) | Aug 23, 2022 |
| Alienware     | 15 R4                       | Notebook    | [f53260e0c2](https://linux-hardware.org/?probe=f53260e0c2) | Aug 23, 2022 |
| Dell          | Inspiron 5770               | Notebook    | [49314a1dfe](https://linux-hardware.org/?probe=49314a1dfe) | Aug 23, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | Notebook    | [fc9bb1e6fa](https://linux-hardware.org/?probe=fc9bb1e6fa) | Aug 23, 2022 |
| HP            | 2AF7                        | Desktop     | [fbc1710ad8](https://linux-hardware.org/?probe=fbc1710ad8) | Aug 22, 2022 |
| MSI           | X99S GAMING 7               | Desktop     | [f729654c4a](https://linux-hardware.org/?probe=f729654c4a) | Aug 22, 2022 |
| ASUSTek       | J1800I-C/BR                 | Desktop     | [f2f76737ad](https://linux-hardware.org/?probe=f2f76737ad) | Aug 22, 2022 |
| Samsung       | Galaxy Book 12 LTE          | Tablet      | [e7f6559a38](https://linux-hardware.org/?probe=e7f6559a38) | Aug 21, 2022 |
| Dell          | 0C27VV A03                  | Desktop     | [4e894e1897](https://linux-hardware.org/?probe=4e894e1897) | Aug 21, 2022 |
| ZOTAC         | ZBOX-CI323NANO              | Mini pc     | [a8bf4ad2a0](https://linux-hardware.org/?probe=a8bf4ad2a0) | Aug 21, 2022 |
| Alienware     | 15 R3                       | Notebook    | [109d7cb528](https://linux-hardware.org/?probe=109d7cb528) | Aug 21, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [ced2388c29](https://linux-hardware.org/?probe=ced2388c29) | Aug 21, 2022 |
| Positivo      | C14CU51                     | Notebook    | [288c810d97](https://linux-hardware.org/?probe=288c810d97) | Aug 21, 2022 |
| ASUSTek       | X542BA                      | Notebook    | [7e86736ebc](https://linux-hardware.org/?probe=7e86736ebc) | Aug 21, 2022 |
| Lenovo        | ThinkPad T500 2055A38       | Notebook    | [f37fce9f01](https://linux-hardware.org/?probe=f37fce9f01) | Aug 20, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [4dc3a452d9](https://linux-hardware.org/?probe=4dc3a452d9) | Aug 19, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [f429863c5f](https://linux-hardware.org/?probe=f429863c5f) | Aug 19, 2022 |
| ASUSTek       | ProArt B660-CREATOR D4      | Desktop     | [0b9e6d6ad9](https://linux-hardware.org/?probe=0b9e6d6ad9) | Aug 19, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | Notebook    | [ec1b67985f](https://linux-hardware.org/?probe=ec1b67985f) | Aug 19, 2022 |
| GPU Compan... | GWTN156-11                  | Notebook    | [c22aa4377d](https://linux-hardware.org/?probe=c22aa4377d) | Aug 19, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [6865f5ed0b](https://linux-hardware.org/?probe=6865f5ed0b) | Aug 19, 2022 |
| BESSTAR Te... | UM350                       | Desktop     | [c7bb6b56fb](https://linux-hardware.org/?probe=c7bb6b56fb) | Aug 18, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [e03daeba5f](https://linux-hardware.org/?probe=e03daeba5f) | Aug 18, 2022 |
| MSI           | MS-AE611 100                | All in one  | [336e0dfd12](https://linux-hardware.org/?probe=336e0dfd12) | Aug 18, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [a54395e915](https://linux-hardware.org/?probe=a54395e915) | Aug 18, 2022 |
| MSI           | Creator Z16 Hiroshi F A1... | Notebook    | [e056c24d1d](https://linux-hardware.org/?probe=e056c24d1d) | Aug 18, 2022 |
| HP            | 14                          | Notebook    | [0f2cde73bb](https://linux-hardware.org/?probe=0f2cde73bb) | Aug 17, 2022 |
| ASUSTek       | X756UQ                      | Notebook    | [9b30268acb](https://linux-hardware.org/?probe=9b30268acb) | Aug 17, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [8ea659cd8c](https://linux-hardware.org/?probe=8ea659cd8c) | Aug 17, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [ab3425dd99](https://linux-hardware.org/?probe=ab3425dd99) | Aug 17, 2022 |
| Dell          | Latitude E6420              | Notebook    | [3e7ce84c59](https://linux-hardware.org/?probe=3e7ce84c59) | Aug 17, 2022 |
| ASUSTek       | K54C                        | Notebook    | [e10b52270f](https://linux-hardware.org/?probe=e10b52270f) | Aug 17, 2022 |
| ASUSTek       | PRIME H370-A                | Desktop     | [da477254e7](https://linux-hardware.org/?probe=da477254e7) | Aug 16, 2022 |
| Gigabyte      | M4HM87P-00                  | Desktop     | [5bb7e42eae](https://linux-hardware.org/?probe=5bb7e42eae) | Aug 16, 2022 |
| Lenovo        | G505s 20255                 | Notebook    | [58a439770d](https://linux-hardware.org/?probe=58a439770d) | Aug 15, 2022 |
| Packard Be... | EasyNote TE69KB             | Notebook    | [e80596ea44](https://linux-hardware.org/?probe=e80596ea44) | Aug 15, 2022 |
| ASUSTek       | J1800I-C/BR                 | Desktop     | [01beed2be8](https://linux-hardware.org/?probe=01beed2be8) | Aug 15, 2022 |
| HP            | 339A                        | Desktop     | [c3e5458c9a](https://linux-hardware.org/?probe=c3e5458c9a) | Aug 15, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [5171fd1732](https://linux-hardware.org/?probe=5171fd1732) | Aug 15, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [08fa90340d](https://linux-hardware.org/?probe=08fa90340d) | Aug 14, 2022 |
| MAXSUN        | MS-TZZ A520M                | Desktop     | [aa844d0dce](https://linux-hardware.org/?probe=aa844d0dce) | Aug 14, 2022 |
| Lenovo        | IdeaPad Z580                | Notebook    | [f9d6b2f915](https://linux-hardware.org/?probe=f9d6b2f915) | Aug 14, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2257302110](https://linux-hardware.org/?probe=2257302110) | Aug 14, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [58d97fbc16](https://linux-hardware.org/?probe=58d97fbc16) | Aug 14, 2022 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [0006dc34cf](https://linux-hardware.org/?probe=0006dc34cf) | Aug 14, 2022 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [0c80c167e4](https://linux-hardware.org/?probe=0c80c167e4) | Aug 13, 2022 |
| HP            | EliteBook 6930p             | Notebook    | [7267931d03](https://linux-hardware.org/?probe=7267931d03) | Aug 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [fb405688fe](https://linux-hardware.org/?probe=fb405688fe) | Aug 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [62a1acd85d](https://linux-hardware.org/?probe=62a1acd85d) | Aug 13, 2022 |
| HP            | 240 G7 Notebook PC          | Notebook    | [9321e2df1a](https://linux-hardware.org/?probe=9321e2df1a) | Aug 13, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | Notebook    | [d08cbbc3d8](https://linux-hardware.org/?probe=d08cbbc3d8) | Aug 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [3dcb75072e](https://linux-hardware.org/?probe=3dcb75072e) | Aug 12, 2022 |
| ASUSTek       | A88X-PRO                    | Desktop     | [399f7ec1da](https://linux-hardware.org/?probe=399f7ec1da) | Aug 12, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [b3e408ce95](https://linux-hardware.org/?probe=b3e408ce95) | Aug 12, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [1fe351cfab](https://linux-hardware.org/?probe=1fe351cfab) | Aug 12, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [3d37c741c8](https://linux-hardware.org/?probe=3d37c741c8) | Aug 12, 2022 |
| Notebook      | NJ50GU                      | Notebook    | [59d1efda98](https://linux-hardware.org/?probe=59d1efda98) | Aug 12, 2022 |
| MSI           | Vector GP76 12UH            | Notebook    | [4549b417bf](https://linux-hardware.org/?probe=4549b417bf) | Aug 12, 2022 |
| MSI           | Vector GP76 12UH            | Notebook    | [8bbf4dd310](https://linux-hardware.org/?probe=8bbf4dd310) | Aug 12, 2022 |
| Unknown       | Unknown                     | Notebook    | [ddeddb54bf](https://linux-hardware.org/?probe=ddeddb54bf) | Aug 12, 2022 |
| Unknown       | Unknown                     | Notebook    | [b19949df5a](https://linux-hardware.org/?probe=b19949df5a) | Aug 12, 2022 |
| ASUSTek       | P5GC-MX                     | Desktop     | [346a48750b](https://linux-hardware.org/?probe=346a48750b) | Aug 12, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [dbbd0524d8](https://linux-hardware.org/?probe=dbbd0524d8) | Aug 12, 2022 |
| Google        | Kasumi                      | Notebook    | [0d1ce61572](https://linux-hardware.org/?probe=0d1ce61572) | Aug 11, 2022 |
| Google        | Kasumi                      | Notebook    | [47ebd6bcac](https://linux-hardware.org/?probe=47ebd6bcac) | Aug 11, 2022 |
| ASUSTek       | J1800I-C/BR                 | Desktop     | [41cd4b02f1](https://linux-hardware.org/?probe=41cd4b02f1) | Aug 11, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [687375ec7c](https://linux-hardware.org/?probe=687375ec7c) | Aug 11, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [4e54f20c67](https://linux-hardware.org/?probe=4e54f20c67) | Aug 10, 2022 |
| Samsung       | 600B4B/600B5B               | Notebook    | [889eb9531f](https://linux-hardware.org/?probe=889eb9531f) | Aug 10, 2022 |
| MSI           | MS-AE611 100                | All in one  | [94bcb206d3](https://linux-hardware.org/?probe=94bcb206d3) | Aug 10, 2022 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [af03bf80b5](https://linux-hardware.org/?probe=af03bf80b5) | Aug 10, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [48722889b6](https://linux-hardware.org/?probe=48722889b6) | Aug 10, 2022 |
| HP            | Pro x2 612 G1 Tablet        | Notebook    | [a40ad10b4c](https://linux-hardware.org/?probe=a40ad10b4c) | Aug 10, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | Notebook    | [2f4a79e056](https://linux-hardware.org/?probe=2f4a79e056) | Aug 10, 2022 |
| HP            | Stream Notebook PC 13       | Notebook    | [9071c341a9](https://linux-hardware.org/?probe=9071c341a9) | Aug 10, 2022 |
| Apple         | Mac-42FD25EABCABB274 iMa... | All in one  | [bee60f5725](https://linux-hardware.org/?probe=bee60f5725) | Aug 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [4312639df6](https://linux-hardware.org/?probe=4312639df6) | Aug 09, 2022 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [4c372a442f](https://linux-hardware.org/?probe=4c372a442f) | Aug 09, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | Notebook    | [d1215796fb](https://linux-hardware.org/?probe=d1215796fb) | Aug 08, 2022 |
| HP            | 1589                        | Desktop     | [0519e046d2](https://linux-hardware.org/?probe=0519e046d2) | Aug 08, 2022 |
| Toshiba       | Satellite L655              | Notebook    | [5e3e45b5d5](https://linux-hardware.org/?probe=5e3e45b5d5) | Aug 08, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | Notebook    | [69430d4693](https://linux-hardware.org/?probe=69430d4693) | Aug 08, 2022 |
| HP            | 18E7                        | Desktop     | [7dd119f85e](https://linux-hardware.org/?probe=7dd119f85e) | Aug 08, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [404319dfd4](https://linux-hardware.org/?probe=404319dfd4) | Aug 07, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [7f1e38b57b](https://linux-hardware.org/?probe=7f1e38b57b) | Aug 07, 2022 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [ab0da3a7ec](https://linux-hardware.org/?probe=ab0da3a7ec) | Aug 07, 2022 |
| ASUSTek       | P9X79 LE                    | Desktop     | [f8a36826db](https://linux-hardware.org/?probe=f8a36826db) | Aug 07, 2022 |
| ASUSTek       | ET2701I-W8                  | Desktop     | [5f9c4b50db](https://linux-hardware.org/?probe=5f9c4b50db) | Aug 07, 2022 |
| ASUSTek       | X550JK                      | Notebook    | [a90c14a429](https://linux-hardware.org/?probe=a90c14a429) | Aug 07, 2022 |
| AMI           | Unknown                     | Notebook    | [d40dbd9414](https://linux-hardware.org/?probe=d40dbd9414) | Aug 07, 2022 |
| MSI           | CR620                       | Notebook    | [517b816cd7](https://linux-hardware.org/?probe=517b816cd7) | Aug 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [d19309cb56](https://linux-hardware.org/?probe=d19309cb56) | Aug 06, 2022 |
| MP            | MS-7848                     | Desktop     | [8d4402905d](https://linux-hardware.org/?probe=8d4402905d) | Aug 06, 2022 |
| Lenovo        | ThinkCentre M57 6087YD2     | Desktop     | [9ad2c07771](https://linux-hardware.org/?probe=9ad2c07771) | Aug 06, 2022 |
| Pegatron      | Benicia                     | Desktop     | [d67d37efce](https://linux-hardware.org/?probe=d67d37efce) | Aug 05, 2022 |
| HP            | 339A                        | Desktop     | [53a3b6e834](https://linux-hardware.org/?probe=53a3b6e834) | Aug 05, 2022 |
| HP            | 339A                        | Desktop     | [8883c2cb6c](https://linux-hardware.org/?probe=8883c2cb6c) | Aug 05, 2022 |
| Ematic        | EWT118                      | Notebook    | [a5362d970a](https://linux-hardware.org/?probe=a5362d970a) | Aug 05, 2022 |
| Medion        | E7419 MD60990               | Notebook    | [e1b74852bd](https://linux-hardware.org/?probe=e1b74852bd) | Aug 04, 2022 |
| ASUSTek       | PN51-E1                     | Mini pc     | [d345f9ab52](https://linux-hardware.org/?probe=d345f9ab52) | Aug 04, 2022 |
| Acer          | Peppy                       | Notebook    | [cc1c91fca6](https://linux-hardware.org/?probe=cc1c91fca6) | Aug 04, 2022 |
| Microsoft     | Surface Pro                 | Tablet      | [db66e72de8](https://linux-hardware.org/?probe=db66e72de8) | Aug 04, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [a6f7e6086b](https://linux-hardware.org/?probe=a6f7e6086b) | Aug 03, 2022 |
| LORD ELECT... | GM965 Series                | Desktop     | [b60dce21e7](https://linux-hardware.org/?probe=b60dce21e7) | Aug 03, 2022 |
| Lenovo        | SDK0J40700 WIN              | Desktop     | [299ac7a8ff](https://linux-hardware.org/?probe=299ac7a8ff) | Aug 03, 2022 |
| HP            | 1589                        | Desktop     | [738de77596](https://linux-hardware.org/?probe=738de77596) | Aug 03, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [d1ca5eafe5](https://linux-hardware.org/?probe=d1ca5eafe5) | Aug 03, 2022 |
| Toshiba       | Satellite Pro L670          | Notebook    | [302749341d](https://linux-hardware.org/?probe=302749341d) | Aug 03, 2022 |
| HP            | Notebook                    | Notebook    | [661237e74a](https://linux-hardware.org/?probe=661237e74a) | Aug 03, 2022 |
| MSI           | Boston                      | Desktop     | [32021cecf7](https://linux-hardware.org/?probe=32021cecf7) | Aug 03, 2022 |
| Acer          | Spin SP513-55N              | Convertible | [295df2a1d7](https://linux-hardware.org/?probe=295df2a1d7) | Aug 03, 2022 |
| Dell          | G15 5510                    | Notebook    | [f3406b36e3](https://linux-hardware.org/?probe=f3406b36e3) | Aug 02, 2022 |
| Packard Be... | EasyNote TE69KB             | Notebook    | [968a5f757f](https://linux-hardware.org/?probe=968a5f757f) | Aug 02, 2022 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [ad8af5c718](https://linux-hardware.org/?probe=ad8af5c718) | Aug 02, 2022 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [b4e172e88b](https://linux-hardware.org/?probe=b4e172e88b) | Aug 02, 2022 |
| Toshiba       | Satellite Pro L670          | Notebook    | [e6189ba78c](https://linux-hardware.org/?probe=e6189ba78c) | Aug 02, 2022 |
| Lenovo        | ThinkPad T420 4236VTQ       | Notebook    | [1ea6046182](https://linux-hardware.org/?probe=1ea6046182) | Aug 02, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [aacc138812](https://linux-hardware.org/?probe=aacc138812) | Aug 02, 2022 |
| HP            | Pro x2 612 G1 Tablet        | Notebook    | [b4bee86632](https://linux-hardware.org/?probe=b4bee86632) | Aug 02, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [cc8b9aa8f6](https://linux-hardware.org/?probe=cc8b9aa8f6) | Aug 01, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [405a75cb1d](https://linux-hardware.org/?probe=405a75cb1d) | Aug 01, 2022 |
| HP            | Laptop 14-dq4xxx            | Notebook    | [1e57f77386](https://linux-hardware.org/?probe=1e57f77386) | Aug 01, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [7c68dbe47e](https://linux-hardware.org/?probe=7c68dbe47e) | Aug 01, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [6532751d00](https://linux-hardware.org/?probe=6532751d00) | Aug 01, 2022 |
| Dell          | 0T656F A01                  | Desktop     | [02ae993867](https://linux-hardware.org/?probe=02ae993867) | Jul 31, 2022 |
| ASRock        | Z170 Pro4                   | Desktop     | [e8dba6ab7e](https://linux-hardware.org/?probe=e8dba6ab7e) | Jul 31, 2022 |
| HP            | 82F2                        | Desktop     | [0c2d091c2e](https://linux-hardware.org/?probe=0c2d091c2e) | Jul 31, 2022 |
| HP            | 550                         | Notebook    | [efc4b32963](https://linux-hardware.org/?probe=efc4b32963) | Jul 30, 2022 |
| Supermicro    | C7Q67 V1.01                 | Desktop     | [15508d1eff](https://linux-hardware.org/?probe=15508d1eff) | Jul 30, 2022 |
| Dell          | Latitude E7450              | Notebook    | [894a489a03](https://linux-hardware.org/?probe=894a489a03) | Jul 30, 2022 |
| Lenovo        | SDK0J40700 WIN              | Desktop     | [f50872e350](https://linux-hardware.org/?probe=f50872e350) | Jul 29, 2022 |
| Packard Be... | H57M01                      | Desktop     | [55e1536ab6](https://linux-hardware.org/?probe=55e1536ab6) | Jul 29, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [2bc22894c8](https://linux-hardware.org/?probe=2bc22894c8) | Jul 29, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [4158c1696a](https://linux-hardware.org/?probe=4158c1696a) | Jul 29, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [1a5b34b200](https://linux-hardware.org/?probe=1a5b34b200) | Jul 29, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [ceb521429a](https://linux-hardware.org/?probe=ceb521429a) | Jul 29, 2022 |
| Packard Be... | H57M01                      | Desktop     | [4789405230](https://linux-hardware.org/?probe=4789405230) | Jul 29, 2022 |
| Lenovo        | SDK0J40700 WIN              | Desktop     | [6d95a05ee7](https://linux-hardware.org/?probe=6d95a05ee7) | Jul 28, 2022 |
| ASRock        | Z170 Pro4                   | Desktop     | [73c8bc2ae1](https://linux-hardware.org/?probe=73c8bc2ae1) | Jul 28, 2022 |
| Dell          | System Inspiron N7110       | Notebook    | [d2cbf8528a](https://linux-hardware.org/?probe=d2cbf8528a) | Jul 28, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [b08a0deeff](https://linux-hardware.org/?probe=b08a0deeff) | Jul 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [4bcdc51e89](https://linux-hardware.org/?probe=4bcdc51e89) | Jul 27, 2022 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [e214df8838](https://linux-hardware.org/?probe=e214df8838) | Jul 27, 2022 |
| Dell          | Latitude E7450              | Notebook    | [4a277d4cee](https://linux-hardware.org/?probe=4a277d4cee) | Jul 27, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [f9b0fe48d6](https://linux-hardware.org/?probe=f9b0fe48d6) | Jul 27, 2022 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [cea12b9c9c](https://linux-hardware.org/?probe=cea12b9c9c) | Jul 27, 2022 |
| Sony          | VGN-Z31XN_B                 | Notebook    | [f27c511d04](https://linux-hardware.org/?probe=f27c511d04) | Jul 26, 2022 |
| ASRock        | Z170 Pro4                   | Desktop     | [876c60188f](https://linux-hardware.org/?probe=876c60188f) | Jul 26, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [e33f8c0a93](https://linux-hardware.org/?probe=e33f8c0a93) | Jul 26, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [a059cf305d](https://linux-hardware.org/?probe=a059cf305d) | Jul 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [37ebea2647](https://linux-hardware.org/?probe=37ebea2647) | Jul 25, 2022 |
| Lenovo        | YB1-X91L                    | Convertible | [99c0ca0d0b](https://linux-hardware.org/?probe=99c0ca0d0b) | Jul 25, 2022 |
| Lenovo        | YB1-X91L                    | Convertible | [e39f15a1b5](https://linux-hardware.org/?probe=e39f15a1b5) | Jul 25, 2022 |
| Lenovo        | SDK0J40700 WIN              | Desktop     | [96d6480781](https://linux-hardware.org/?probe=96d6480781) | Jul 25, 2022 |
| ASUSTek       | A88X-PRO                    | Desktop     | [48e39039fc](https://linux-hardware.org/?probe=48e39039fc) | Jul 24, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [ff4dba6b3e](https://linux-hardware.org/?probe=ff4dba6b3e) | Jul 24, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [d06c0db3ce](https://linux-hardware.org/?probe=d06c0db3ce) | Jul 24, 2022 |
| Fujitsu       | D2901-A1 S26361-D2901-A1    | Desktop     | [aa952e11aa](https://linux-hardware.org/?probe=aa952e11aa) | Jul 24, 2022 |
| HP            | Unknown                     | Notebook    | [1e1768ebfa](https://linux-hardware.org/?probe=1e1768ebfa) | Jul 24, 2022 |
| Dell          | 03NVJ6 A03                  | Desktop     | [9c0bb64bd9](https://linux-hardware.org/?probe=9c0bb64bd9) | Jul 24, 2022 |
| ASUSTek       | CROSSHAIR II FORMULA        | Desktop     | [aa2242c51f](https://linux-hardware.org/?probe=aa2242c51f) | Jul 23, 2022 |
| HP            | Stream Notebook             | Notebook    | [8422abef44](https://linux-hardware.org/?probe=8422abef44) | Jul 23, 2022 |
| Gigabyte      | Z97X-SLI-CF                 | Desktop     | [177a181771](https://linux-hardware.org/?probe=177a181771) | Jul 23, 2022 |
| Supermicro    | C7Q67 V1.01                 | Desktop     | [722f3df811](https://linux-hardware.org/?probe=722f3df811) | Jul 23, 2022 |
| Dell          | 0FDY5C A00                  | Desktop     | [f5d81fb635](https://linux-hardware.org/?probe=f5d81fb635) | Jul 23, 2022 |
| Dell          | 0FDY5C A00                  | Desktop     | [83cf5f7085](https://linux-hardware.org/?probe=83cf5f7085) | Jul 23, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [1512e3bf4d](https://linux-hardware.org/?probe=1512e3bf4d) | Jul 22, 2022 |
| Lenovo        | ThinkPad T500 2055A38       | Notebook    | [3b2f2c3bea](https://linux-hardware.org/?probe=3b2f2c3bea) | Jul 22, 2022 |
| Gigabyte      | M68M-S2P                    | Desktop     | [7d4ba4168a](https://linux-hardware.org/?probe=7d4ba4168a) | Jul 22, 2022 |
| HP            | ProBook 4540s               | Notebook    | [a2d1e2fd68](https://linux-hardware.org/?probe=a2d1e2fd68) | Jul 22, 2022 |
| HP            | Compaq 420                  | Notebook    | [913795a620](https://linux-hardware.org/?probe=913795a620) | Jul 21, 2022 |
| ASUSTek       | X550CL                      | Notebook    | [abd0b78e41](https://linux-hardware.org/?probe=abd0b78e41) | Jul 21, 2022 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [84f435a6d0](https://linux-hardware.org/?probe=84f435a6d0) | Jul 21, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [89e0889e94](https://linux-hardware.org/?probe=89e0889e94) | Jul 21, 2022 |
| Dell          | 09KPNV A00                  | Desktop     | [711546ab63](https://linux-hardware.org/?probe=711546ab63) | Jul 21, 2022 |
| Dell          | Inspiron 5520               | Notebook    | [ef41a8c220](https://linux-hardware.org/?probe=ef41a8c220) | Jul 20, 2022 |
| Foxconn       | 2AAF                        | Desktop     | [b97dc9fd47](https://linux-hardware.org/?probe=b97dc9fd47) | Jul 20, 2022 |
| Dell          | Inspiron 3541               | Notebook    | [cb0f9c95d2](https://linux-hardware.org/?probe=cb0f9c95d2) | Jul 20, 2022 |
| Toshiba       | Satellite L655              | Notebook    | [e332607406](https://linux-hardware.org/?probe=e332607406) | Jul 19, 2022 |
| MSI           | B75MA-P45                   | Desktop     | [89af63cf6f](https://linux-hardware.org/?probe=89af63cf6f) | Jul 19, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [b0e3b75c3b](https://linux-hardware.org/?probe=b0e3b75c3b) | Jul 19, 2022 |
| Google        | Butterfly                   | Notebook    | [ed6aa75ba5](https://linux-hardware.org/?probe=ed6aa75ba5) | Jul 19, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [82966b0f63](https://linux-hardware.org/?probe=82966b0f63) | Jul 18, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [4a5f294565](https://linux-hardware.org/?probe=4a5f294565) | Jul 18, 2022 |
| Dell          | Vostro 3559                 | Notebook    | [3770ab3d4c](https://linux-hardware.org/?probe=3770ab3d4c) | Jul 18, 2022 |
| Lenovo        | YB1-X91L                    | Convertible | [c6888145e7](https://linux-hardware.org/?probe=c6888145e7) | Jul 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [ca9e042e30](https://linux-hardware.org/?probe=ca9e042e30) | Jul 18, 2022 |
| Acer          | NC-A315-41G-R88F            | Notebook    | [8ffe1077fd](https://linux-hardware.org/?probe=8ffe1077fd) | Jul 17, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [08446807d6](https://linux-hardware.org/?probe=08446807d6) | Jul 17, 2022 |
| Lenovo        | ThinkPad T500 2055A38       | Notebook    | [e8b9689526](https://linux-hardware.org/?probe=e8b9689526) | Jul 17, 2022 |
| Dell          | 09KPNV A00                  | Desktop     | [c47ecbd03f](https://linux-hardware.org/?probe=c47ecbd03f) | Jul 16, 2022 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [0cf64c41f0](https://linux-hardware.org/?probe=0cf64c41f0) | Jul 16, 2022 |
| Intel         | NUC8BEB J72692-310          | Mini pc     | [84cd652e24](https://linux-hardware.org/?probe=84cd652e24) | Jul 16, 2022 |
| ASUSTek       | X751MA                      | Notebook    | [e8c8c0d6ec](https://linux-hardware.org/?probe=e8c8c0d6ec) | Jul 16, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [e5fed36e22](https://linux-hardware.org/?probe=e5fed36e22) | Jul 15, 2022 |
| Toshiba       | TECRA S11                   | Notebook    | [26ed071525](https://linux-hardware.org/?probe=26ed071525) | Jul 15, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [56bd2a162b](https://linux-hardware.org/?probe=56bd2a162b) | Jul 15, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [ccc3bc2a39](https://linux-hardware.org/?probe=ccc3bc2a39) | Jul 15, 2022 |
| Kogan         | KALAP13S300VA               | Notebook    | [9060455576](https://linux-hardware.org/?probe=9060455576) | Jul 15, 2022 |
| Intel         | X79 V2.72B                  | Desktop     | [f244f6157b](https://linux-hardware.org/?probe=f244f6157b) | Jul 15, 2022 |
| AMI           | Unknown                     | Notebook    | [2d15648f33](https://linux-hardware.org/?probe=2d15648f33) | Jul 14, 2022 |
| Alienware     | x15 R1                      | Notebook    | [95ee5b34a7](https://linux-hardware.org/?probe=95ee5b34a7) | Jul 14, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [ea2c3cd9e9](https://linux-hardware.org/?probe=ea2c3cd9e9) | Jul 14, 2022 |
| HP            | Unknown                     | Notebook    | [aa2aa159c9](https://linux-hardware.org/?probe=aa2aa159c9) | Jul 14, 2022 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [66efd060ca](https://linux-hardware.org/?probe=66efd060ca) | Jul 14, 2022 |
| HP            | ProBook 455 G1              | Notebook    | [a0dd163643](https://linux-hardware.org/?probe=a0dd163643) | Jul 14, 2022 |
| Unknown       | Intel X79                   | Desktop     | [b0bb64b9ea](https://linux-hardware.org/?probe=b0bb64b9ea) | Jul 13, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [09e66aef7e](https://linux-hardware.org/?probe=09e66aef7e) | Jul 13, 2022 |
| Gigabyte      | H87M-D3H                    | Desktop     | [5056c4f640](https://linux-hardware.org/?probe=5056c4f640) | Jul 13, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [e3a3e1cac2](https://linux-hardware.org/?probe=e3a3e1cac2) | Jul 13, 2022 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | Desktop     | [c90a0cbab7](https://linux-hardware.org/?probe=c90a0cbab7) | Jul 13, 2022 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | Desktop     | [87fa08ea59](https://linux-hardware.org/?probe=87fa08ea59) | Jul 13, 2022 |
| Star Labs     | StarBook                    | Notebook    | [fdae1cd2c3](https://linux-hardware.org/?probe=fdae1cd2c3) | Jul 12, 2022 |
| System76      | Thelio thelio-r2            | Desktop     | [2d990d7afe](https://linux-hardware.org/?probe=2d990d7afe) | Jul 12, 2022 |
| HP            | 3398                        | Desktop     | [1b964004d9](https://linux-hardware.org/?probe=1b964004d9) | Jul 12, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [e974774285](https://linux-hardware.org/?probe=e974774285) | Jul 12, 2022 |
| ASUSTek       | V-P8H61E                    | Desktop     | [f8e5b72d1c](https://linux-hardware.org/?probe=f8e5b72d1c) | Jul 12, 2022 |
| Dell          | Inspiron 5520               | Notebook    | [67d1588e47](https://linux-hardware.org/?probe=67d1588e47) | Jul 12, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | Desktop     | [42b248f049](https://linux-hardware.org/?probe=42b248f049) | Jul 11, 2022 |
| ASUSTek       | T101HA                      | Tablet      | [d234e8543d](https://linux-hardware.org/?probe=d234e8543d) | Jul 11, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [bc5945b570](https://linux-hardware.org/?probe=bc5945b570) | Jul 11, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [f25593cec7](https://linux-hardware.org/?probe=f25593cec7) | Jul 11, 2022 |
| Lenovo        | ThinkCentre M91 7516AD1     | Desktop     | [19660ae71a](https://linux-hardware.org/?probe=19660ae71a) | Jul 11, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [6d6b4c9d06](https://linux-hardware.org/?probe=6d6b4c9d06) | Jul 11, 2022 |
| OEM_MB        | NARRA3                      | Desktop     | [845bdfd72c](https://linux-hardware.org/?probe=845bdfd72c) | Jul 11, 2022 |
| ASUSTek       | T101HA                      | Tablet      | [0d90a39160](https://linux-hardware.org/?probe=0d90a39160) | Jul 10, 2022 |
| MSI           | Creator 15 A10SET           | Notebook    | [d90f2aec1b](https://linux-hardware.org/?probe=d90f2aec1b) | Jul 10, 2022 |
| Dell          | 0J3C2F A00                  | Desktop     | [36252f70d6](https://linux-hardware.org/?probe=36252f70d6) | Jul 10, 2022 |
| Dell          | 0J3C2F A00                  | Desktop     | [e3197762a9](https://linux-hardware.org/?probe=e3197762a9) | Jul 10, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [8a02619147](https://linux-hardware.org/?probe=8a02619147) | Jul 10, 2022 |
| eMachines     | E720 V1.06                  | Notebook    | [ec23637bd5](https://linux-hardware.org/?probe=ec23637bd5) | Jul 09, 2022 |
| Packard Be... | EasyNote TE69KB             | Notebook    | [89403f1acb](https://linux-hardware.org/?probe=89403f1acb) | Jul 09, 2022 |
| Pegatron      | Benicia                     | Desktop     | [2360476ad3](https://linux-hardware.org/?probe=2360476ad3) | Jul 09, 2022 |
| Gigabyte      | H110M-A-CF                  | Desktop     | [42335e5c5c](https://linux-hardware.org/?probe=42335e5c5c) | Jul 09, 2022 |
| HP            | Pavilion 15                 | Notebook    | [1fbb699502](https://linux-hardware.org/?probe=1fbb699502) | Jul 09, 2022 |
| Dell          | Latitude 5400               | Notebook    | [46ce7cf7fe](https://linux-hardware.org/?probe=46ce7cf7fe) | Jul 09, 2022 |
| HP            | Pavilion 15                 | Notebook    | [c74f3711f3](https://linux-hardware.org/?probe=c74f3711f3) | Jul 09, 2022 |
| Sony          | VGN-Z31XN_B                 | Notebook    | [e541b7743e](https://linux-hardware.org/?probe=e541b7743e) | Jul 08, 2022 |
| Lenovo        | ThinkPad T400 2768GB4       | Notebook    | [498bb4a509](https://linux-hardware.org/?probe=498bb4a509) | Jul 08, 2022 |
| Acer          | Aspire 5755G                | Notebook    | [37aff6bb24](https://linux-hardware.org/?probe=37aff6bb24) | Jul 08, 2022 |
| HP            | 18E4                        | Desktop     | [bf615fe0ae](https://linux-hardware.org/?probe=bf615fe0ae) | Jul 08, 2022 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [b7ed1ecdf2](https://linux-hardware.org/?probe=b7ed1ecdf2) | Jul 08, 2022 |
| HP            | EliteBook 745 G6            | Notebook    | [159ebeaa5e](https://linux-hardware.org/?probe=159ebeaa5e) | Jul 08, 2022 |
| Lenovo        | ThinkPad T61 6457B5S        | Notebook    | [34e97dae1e](https://linux-hardware.org/?probe=34e97dae1e) | Jul 08, 2022 |
| Gigabyte      | EP45-UD3P                   | Desktop     | [9118f548bb](https://linux-hardware.org/?probe=9118f548bb) | Jul 08, 2022 |
| Acer          | Aspire 5560                 | Notebook    | [e9615585f6](https://linux-hardware.org/?probe=e9615585f6) | Jul 07, 2022 |
| HP            | Mini 110-3100               | Notebook    | [5222f63258](https://linux-hardware.org/?probe=5222f63258) | Jul 06, 2022 |
| Samsung       | 550XDA                      | Notebook    | [74bcded10f](https://linux-hardware.org/?probe=74bcded10f) | Jul 06, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [57fc50a4fb](https://linux-hardware.org/?probe=57fc50a4fb) | Jul 06, 2022 |
| Acer          | Aspire 5755G                | Notebook    | [0dcb64ed5f](https://linux-hardware.org/?probe=0dcb64ed5f) | Jul 06, 2022 |
| Acer          | E91M                        | Desktop     | [4e55aacdd7](https://linux-hardware.org/?probe=4e55aacdd7) | Jul 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [167fe0c2d1](https://linux-hardware.org/?probe=167fe0c2d1) | Jul 06, 2022 |
| MSI           | Boston                      | Desktop     | [3dfcd01115](https://linux-hardware.org/?probe=3dfcd01115) | Jul 06, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [59923a9781](https://linux-hardware.org/?probe=59923a9781) | Jul 06, 2022 |
| Samsung       | 500R5M/500R5W/501R5M        | Notebook    | [17607e5f03](https://linux-hardware.org/?probe=17607e5f03) | Jul 06, 2022 |
| Acer          | Aspire F5-573               | Notebook    | [1ada0ad162](https://linux-hardware.org/?probe=1ada0ad162) | Jul 06, 2022 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [b8e2b7b6bd](https://linux-hardware.org/?probe=b8e2b7b6bd) | Jul 05, 2022 |
| Lenovo        | S21e-20 80M4                | Notebook    | [968f07d190](https://linux-hardware.org/?probe=968f07d190) | Jul 05, 2022 |
| ASUSTek       | X540LJ                      | Notebook    | [5994a314d0](https://linux-hardware.org/?probe=5994a314d0) | Jul 05, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [dc12f11117](https://linux-hardware.org/?probe=dc12f11117) | Jul 05, 2022 |
| Biostar       | P4M90-M7A Ver:1.0           | Desktop     | [0567d5e337](https://linux-hardware.org/?probe=0567d5e337) | Jul 05, 2022 |
| HP            | ProBook 6475b               | Notebook    | [02eab8bd42](https://linux-hardware.org/?probe=02eab8bd42) | Jul 05, 2022 |
| OEM           | G41 775 ICH7 8712           | Desktop     | [4f82c838cb](https://linux-hardware.org/?probe=4f82c838cb) | Jul 04, 2022 |
| Packard Be... | H17HV                       | Notebook    | [8b05e7f955](https://linux-hardware.org/?probe=8b05e7f955) | Jul 04, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [3ab547df65](https://linux-hardware.org/?probe=3ab547df65) | Jul 04, 2022 |
| HP            | Laptop 15s-du2xxx           | Notebook    | [c208a1e955](https://linux-hardware.org/?probe=c208a1e955) | Jul 04, 2022 |
| Deffad        | Unknown                     | Notebook    | [af38c7120e](https://linux-hardware.org/?probe=af38c7120e) | Jul 04, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [e20dba9308](https://linux-hardware.org/?probe=e20dba9308) | Jul 04, 2022 |
| HP            | Laptop 15s-du2xxx           | Notebook    | [65debb520a](https://linux-hardware.org/?probe=65debb520a) | Jul 04, 2022 |
| Intel         | NUC6i7KYB H90766-402        | Mini pc     | [b847a4a45d](https://linux-hardware.org/?probe=b847a4a45d) | Jul 03, 2022 |
| Intel         | NUC6i7KYB H90766-402        | Mini pc     | [0aa196cd0c](https://linux-hardware.org/?probe=0aa196cd0c) | Jul 03, 2022 |
| ASUSTek       | ROG Flow X13 GV301RA_GV3... | Convertible | [c186124284](https://linux-hardware.org/?probe=c186124284) | Jul 03, 2022 |
| ASUSTek       | ROG Flow X13 GV301RA_GV3... | Convertible | [fce4d4547c](https://linux-hardware.org/?probe=fce4d4547c) | Jul 03, 2022 |
| Lenovo        | G40-45 80E1                 | Notebook    | [bce4ceea50](https://linux-hardware.org/?probe=bce4ceea50) | Jul 03, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [eb23a7916c](https://linux-hardware.org/?probe=eb23a7916c) | Jul 03, 2022 |
| Dell          | Inspiron 5520               | Notebook    | [2a4654f61b](https://linux-hardware.org/?probe=2a4654f61b) | Jul 03, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [18acc5233d](https://linux-hardware.org/?probe=18acc5233d) | Jul 03, 2022 |
| HP            | 8350                        | Desktop     | [39a8a75ebe](https://linux-hardware.org/?probe=39a8a75ebe) | Jul 03, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [31a8bd72d6](https://linux-hardware.org/?probe=31a8bd72d6) | Jul 02, 2022 |
| Foxconn       | 2AB1                        | Desktop     | [83a3a5794d](https://linux-hardware.org/?probe=83a3a5794d) | Jul 02, 2022 |
| Foxconn       | 2AB1                        | Desktop     | [7b7c8244af](https://linux-hardware.org/?probe=7b7c8244af) | Jul 02, 2022 |
| ASUSTek       | N61Jq                       | Notebook    | [19b3d15d92](https://linux-hardware.org/?probe=19b3d15d92) | Jul 02, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f54987d748](https://linux-hardware.org/?probe=f54987d748) | Jul 01, 2022 |
| MSI           | CR620                       | Notebook    | [0968b18823](https://linux-hardware.org/?probe=0968b18823) | Jun 30, 2022 |
| Dell          | Latitude 7389               | Convertible | [6cc0f640ed](https://linux-hardware.org/?probe=6cc0f640ed) | Jun 29, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [7d85e08611](https://linux-hardware.org/?probe=7d85e08611) | Jun 29, 2022 |
| Dell          | Inspiron 3531               | Notebook    | [2c8286100d](https://linux-hardware.org/?probe=2c8286100d) | Jun 29, 2022 |
| Gigabyte      | B360M HD3                   | Desktop     | [b35e9f3e5c](https://linux-hardware.org/?probe=b35e9f3e5c) | Jun 28, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [3e451a9d00](https://linux-hardware.org/?probe=3e451a9d00) | Jun 28, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [6e098b9c49](https://linux-hardware.org/?probe=6e098b9c49) | Jun 27, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [740f06d30d](https://linux-hardware.org/?probe=740f06d30d) | Jun 27, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [8cf2281f01](https://linux-hardware.org/?probe=8cf2281f01) | Jun 27, 2022 |
| Dell          | 0U880P A00                  | Desktop     | [e14832f09c](https://linux-hardware.org/?probe=e14832f09c) | Jun 26, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [6262e08c1f](https://linux-hardware.org/?probe=6262e08c1f) | Jun 26, 2022 |
| Pegatron      | IPPSB-DB                    | Desktop     | [a63cdffc5b](https://linux-hardware.org/?probe=a63cdffc5b) | Jun 26, 2022 |
| Acer          | Aspire A515-55G             | Notebook    | [d05c52e40b](https://linux-hardware.org/?probe=d05c52e40b) | Jun 26, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [3dc935ecb1](https://linux-hardware.org/?probe=3dc935ecb1) | Jun 26, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [c78b132d02](https://linux-hardware.org/?probe=c78b132d02) | Jun 26, 2022 |
| ASUSTek       | TUF Gaming X570-PRO WIFI... | Desktop     | [b232a434fd](https://linux-hardware.org/?probe=b232a434fd) | Jun 26, 2022 |
| Google        | Candy                       | Notebook    | [8888e44843](https://linux-hardware.org/?probe=8888e44843) | Jun 25, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [0297d9c8c1](https://linux-hardware.org/?probe=0297d9c8c1) | Jun 25, 2022 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [fbde5d214f](https://linux-hardware.org/?probe=fbde5d214f) | Jun 24, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [26cd390b15](https://linux-hardware.org/?probe=26cd390b15) | Jun 24, 2022 |
| Gigabyte      | EP45-UD3P                   | Desktop     | [05449d9e5c](https://linux-hardware.org/?probe=05449d9e5c) | Jun 24, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [8f8ce01734](https://linux-hardware.org/?probe=8f8ce01734) | Jun 24, 2022 |
| Lenovo        | ThinkPad T420 4236J73       | Notebook    | [088ba8b97c](https://linux-hardware.org/?probe=088ba8b97c) | Jun 23, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [dede0c6694](https://linux-hardware.org/?probe=dede0c6694) | Jun 23, 2022 |
| MSI           | A75A-G35                    | Desktop     | [9e3dd8051c](https://linux-hardware.org/?probe=9e3dd8051c) | Jun 23, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [a24305d670](https://linux-hardware.org/?probe=a24305d670) | Jun 23, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [b21a0caebf](https://linux-hardware.org/?probe=b21a0caebf) | Jun 22, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [ebacc3616d](https://linux-hardware.org/?probe=ebacc3616d) | Jun 22, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [d5d7479c46](https://linux-hardware.org/?probe=d5d7479c46) | Jun 22, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [3e80b4439f](https://linux-hardware.org/?probe=3e80b4439f) | Jun 22, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [ecea2bb4ad](https://linux-hardware.org/?probe=ecea2bb4ad) | Jun 22, 2022 |
| Dell          | Inspiron 5537               | Notebook    | [6b549dfe09](https://linux-hardware.org/?probe=6b549dfe09) | Jun 22, 2022 |
| Intel         | NUC5i3RYB H41000-507        | Mini pc     | [d3feec9910](https://linux-hardware.org/?probe=d3feec9910) | Jun 21, 2022 |
| Lenovo        | ThinkPad P50 20EQS28400     | Notebook    | [3bd256be91](https://linux-hardware.org/?probe=3bd256be91) | Jun 21, 2022 |
| Gigabyte      | EX58-UD3R                   | Desktop     | [4014366c8a](https://linux-hardware.org/?probe=4014366c8a) | Jun 21, 2022 |
| Lenovo        | ThinkPad T430s 23539MU      | Notebook    | [cb159502de](https://linux-hardware.org/?probe=cb159502de) | Jun 21, 2022 |
| Dell          | XPS 12 9Q23                 | Notebook    | [463461920a](https://linux-hardware.org/?probe=463461920a) | Jun 21, 2022 |
| Toshiba       | Satellite C870-1C2          | Notebook    | [421b2e1975](https://linux-hardware.org/?probe=421b2e1975) | Jun 20, 2022 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [0cae0765c9](https://linux-hardware.org/?probe=0cae0765c9) | Jun 20, 2022 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [9c4b7a7742](https://linux-hardware.org/?probe=9c4b7a7742) | Jun 20, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [4a3e29a7c0](https://linux-hardware.org/?probe=4a3e29a7c0) | Jun 20, 2022 |
| AWOW          | NY41                        | Mini pc     | [f420b36754](https://linux-hardware.org/?probe=f420b36754) | Jun 19, 2022 |
| AWOW          | NY41                        | Mini pc     | [e8f74093f9](https://linux-hardware.org/?probe=e8f74093f9) | Jun 19, 2022 |
| Global Dis... | W11651                      | Notebook    | [a28b308f7f](https://linux-hardware.org/?probe=a28b308f7f) | Jun 19, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [82ab434998](https://linux-hardware.org/?probe=82ab434998) | Jun 18, 2022 |
| Lenovo        | SDK0J40700 WIN              | Desktop     | [82be38e941](https://linux-hardware.org/?probe=82be38e941) | Jun 17, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [99eb49831a](https://linux-hardware.org/?probe=99eb49831a) | Jun 17, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [a20ee1d5b6](https://linux-hardware.org/?probe=a20ee1d5b6) | Jun 17, 2022 |
| MSI           | B85M-E45                    | Desktop     | [58c2ff96e3](https://linux-hardware.org/?probe=58c2ff96e3) | Jun 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [85a022001e](https://linux-hardware.org/?probe=85a022001e) | Jun 16, 2022 |
| Dell          | Latitude E6540              | Notebook    | [4806aec13b](https://linux-hardware.org/?probe=4806aec13b) | Jun 16, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [14500170b0](https://linux-hardware.org/?probe=14500170b0) | Jun 16, 2022 |
| Dell          | Inspiron 7500 2n1 Black     | Convertible | [d08495e5aa](https://linux-hardware.org/?probe=d08495e5aa) | Jun 16, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [8932d07801](https://linux-hardware.org/?probe=8932d07801) | Jun 16, 2022 |
| Dell          | 0X501H A02                  | Desktop     | [b9cb2a1e48](https://linux-hardware.org/?probe=b9cb2a1e48) | Jun 15, 2022 |
| Dell          | Precision M4700             | Notebook    | [3d10ec3c17](https://linux-hardware.org/?probe=3d10ec3c17) | Jun 15, 2022 |
| Acer          | Aspire M3970                | Desktop     | [b966120966](https://linux-hardware.org/?probe=b966120966) | Jun 14, 2022 |
| Primux Tec... | Primux_1402F_W10            | Notebook    | [c3cf4149c9](https://linux-hardware.org/?probe=c3cf4149c9) | Jun 14, 2022 |
| Dell          | XPS 12 9Q23                 | Notebook    | [77c4dc4a62](https://linux-hardware.org/?probe=77c4dc4a62) | Jun 14, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [e849fd55ad](https://linux-hardware.org/?probe=e849fd55ad) | Jun 14, 2022 |
| Lenovo        | 3717 SDK0J40709 WIN 3259... | Desktop     | [aa63e13a60](https://linux-hardware.org/?probe=aa63e13a60) | Jun 13, 2022 |
| Positivo      | Q464C                       | Notebook    | [1cb4cb4da1](https://linux-hardware.org/?probe=1cb4cb4da1) | Jun 13, 2022 |
| Lenovo        | 3717 SDK0J40709 WIN 3259... | Desktop     | [ba6786bbe8](https://linux-hardware.org/?probe=ba6786bbe8) | Jun 13, 2022 |
| Positivo      | Q464C                       | Notebook    | [a772cd7eae](https://linux-hardware.org/?probe=a772cd7eae) | Jun 13, 2022 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [428eebd42f](https://linux-hardware.org/?probe=428eebd42f) | Jun 13, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | Notebook    | [9baa7ce30e](https://linux-hardware.org/?probe=9baa7ce30e) | Jun 13, 2022 |
| TrekStor      | Surfbook A13                | Notebook    | [2c8d07851d](https://linux-hardware.org/?probe=2c8d07851d) | Jun 12, 2022 |
| MSI           | MEG Z690 UNIFY              | Desktop     | [4e227cff8b](https://linux-hardware.org/?probe=4e227cff8b) | Jun 12, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [2a772cecf4](https://linux-hardware.org/?probe=2a772cecf4) | Jun 12, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [14b9e721b7](https://linux-hardware.org/?probe=14b9e721b7) | Jun 11, 2022 |
| HP            | Pavilion 17                 | Notebook    | [bed3614b80](https://linux-hardware.org/?probe=bed3614b80) | Jun 11, 2022 |
| Positivo      | C4500D                      | Notebook    | [70dc4735fa](https://linux-hardware.org/?probe=70dc4735fa) | Jun 11, 2022 |
| Acer          | Aspire 5736Z                | Notebook    | [dcaa9a66f4](https://linux-hardware.org/?probe=dcaa9a66f4) | Jun 10, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [828f110a40](https://linux-hardware.org/?probe=828f110a40) | Jun 10, 2022 |
| Dell          | Inspiron 5520               | Notebook    | [d80ec10f91](https://linux-hardware.org/?probe=d80ec10f91) | Jun 09, 2022 |
| Dell          | Inspiron 5520               | Notebook    | [39e10fd449](https://linux-hardware.org/?probe=39e10fd449) | Jun 09, 2022 |
| Dell          | 0XFWHV A00                  | Desktop     | [4102e98034](https://linux-hardware.org/?probe=4102e98034) | Jun 09, 2022 |
| Toshiba       | QOSMIO X770                 | Notebook    | [d11736c26f](https://linux-hardware.org/?probe=d11736c26f) | Jun 09, 2022 |
| Samsung       | 600B4B/600B5B               | Notebook    | [431ccbf84a](https://linux-hardware.org/?probe=431ccbf84a) | Jun 08, 2022 |
| Toshiba       | Satellite A200              | Notebook    | [9719a84d3e](https://linux-hardware.org/?probe=9719a84d3e) | Jun 08, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [9651975542](https://linux-hardware.org/?probe=9651975542) | Jun 07, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [b43b02cdeb](https://linux-hardware.org/?probe=b43b02cdeb) | Jun 07, 2022 |
| HP            | Laptop 14-dq0xxx            | Notebook    | [39cfb21bae](https://linux-hardware.org/?probe=39cfb21bae) | Jun 07, 2022 |
| Lenovo        | ThinkPad T540p 20BF0038G... | Notebook    | [e7d830048d](https://linux-hardware.org/?probe=e7d830048d) | Jun 06, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [81fad50492](https://linux-hardware.org/?probe=81fad50492) | Jun 06, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [902546cb45](https://linux-hardware.org/?probe=902546cb45) | Jun 06, 2022 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [94d4930070](https://linux-hardware.org/?probe=94d4930070) | Jun 06, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [2e08398c9a](https://linux-hardware.org/?probe=2e08398c9a) | Jun 06, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [8edffcde03](https://linux-hardware.org/?probe=8edffcde03) | Jun 06, 2022 |
| ASUSTek       | TUF Z270 MARK 2             | Desktop     | [e993e32a56](https://linux-hardware.org/?probe=e993e32a56) | Jun 06, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | Notebook    | [96ed2caf25](https://linux-hardware.org/?probe=96ed2caf25) | Jun 06, 2022 |
| Lenovo        | Yoga710-14ISK 80TY          | Notebook    | [116abb675e](https://linux-hardware.org/?probe=116abb675e) | Jun 06, 2022 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [4af3ead1a7](https://linux-hardware.org/?probe=4af3ead1a7) | Jun 06, 2022 |
| Dell          | Latitude E6430              | Notebook    | [0ebbfb5b74](https://linux-hardware.org/?probe=0ebbfb5b74) | Jun 05, 2022 |
| HP            | ProBook 450 G3              | Notebook    | [654b62a3bb](https://linux-hardware.org/?probe=654b62a3bb) | Jun 05, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [07808a7cbf](https://linux-hardware.org/?probe=07808a7cbf) | Jun 05, 2022 |
| Acer          | Aspire C22-820              | All in one  | [32cb850c67](https://linux-hardware.org/?probe=32cb850c67) | Jun 05, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [63467c4755](https://linux-hardware.org/?probe=63467c4755) | Jun 05, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [8577975269](https://linux-hardware.org/?probe=8577975269) | Jun 05, 2022 |
| Biostar       | A68N-2100K                  | Desktop     | [480a4c12b1](https://linux-hardware.org/?probe=480a4c12b1) | Jun 05, 2022 |
| HP            | Pavilion dv6                | Notebook    | [8e20121256](https://linux-hardware.org/?probe=8e20121256) | Jun 04, 2022 |
| Acer          | Aspire C22-820              | All in one  | [682fb84b70](https://linux-hardware.org/?probe=682fb84b70) | Jun 04, 2022 |
| ASRock        | 970 Extreme3                | Desktop     | [d5648a1a95](https://linux-hardware.org/?probe=d5648a1a95) | Jun 04, 2022 |
| MSI           | B85M-G43                    | Desktop     | [097b308b60](https://linux-hardware.org/?probe=097b308b60) | Jun 04, 2022 |
| Dell          | Inspiron 15-5578            | Notebook    | [d88547de78](https://linux-hardware.org/?probe=d88547de78) | Jun 04, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [9404638832](https://linux-hardware.org/?probe=9404638832) | Jun 03, 2022 |
| HP            | ZBook Studio G7 Mobile W... | Notebook    | [894d121f66](https://linux-hardware.org/?probe=894d121f66) | Jun 03, 2022 |
| BESSTAR Te... | TL50                        | Desktop     | [0455aba8a3](https://linux-hardware.org/?probe=0455aba8a3) | Jun 03, 2022 |
| HP            | 3029h                       | Desktop     | [d536fb8e36](https://linux-hardware.org/?probe=d536fb8e36) | Jun 03, 2022 |
| Ematic        | EWT935DK                    | Notebook    | [13c5b6c48c](https://linux-hardware.org/?probe=13c5b6c48c) | Jun 03, 2022 |
| Medion        | WIM2180                     | Notebook    | [0548ef61b7](https://linux-hardware.org/?probe=0548ef61b7) | Jun 03, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [caf55e4146](https://linux-hardware.org/?probe=caf55e4146) | Jun 03, 2022 |
| Medion        | WIM2180                     | Notebook    | [b645a2fa42](https://linux-hardware.org/?probe=b645a2fa42) | Jun 03, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [61b90c102c](https://linux-hardware.org/?probe=61b90c102c) | Jun 03, 2022 |
| ASUSTek       | P5E-VM DO                   | Desktop     | [935c03cd63](https://linux-hardware.org/?probe=935c03cd63) | Jun 03, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [ec87718c8c](https://linux-hardware.org/?probe=ec87718c8c) | Jun 02, 2022 |
| Lenovo        | G780 2182                   | Notebook    | [878e602f7d](https://linux-hardware.org/?probe=878e602f7d) | Jun 02, 2022 |
| Lenovo        | ThinkPad P50 20EQS28400     | Notebook    | [71e59838a5](https://linux-hardware.org/?probe=71e59838a5) | Jun 02, 2022 |
| Lenovo        | ThinkPad P50 20EQS28400     | Notebook    | [702f836250](https://linux-hardware.org/?probe=702f836250) | Jun 02, 2022 |
| Biostar       | A78MD                       | Desktop     | [206b04b6d8](https://linux-hardware.org/?probe=206b04b6d8) | Jun 02, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [5eff529610](https://linux-hardware.org/?probe=5eff529610) | Jun 02, 2022 |
| ASUSTek       | P5QL-ASUS-SE                | Desktop     | [5c9f7b1ab9](https://linux-hardware.org/?probe=5c9f7b1ab9) | Jun 02, 2022 |
| ASUSTek       | P5QL-ASUS-SE                | Desktop     | [0e1e2765fc](https://linux-hardware.org/?probe=0e1e2765fc) | Jun 01, 2022 |
| Intel         | NUC7i3DNB J57625-512        | Mini pc     | [8b67a50c5e](https://linux-hardware.org/?probe=8b67a50c5e) | Jun 01, 2022 |
| Biostar       | A78MD                       | Desktop     | [49ea0bd0e4](https://linux-hardware.org/?probe=49ea0bd0e4) | Jun 01, 2022 |
| ZOTAC         | ZBOX-ECM73070C/53060C       | Mini pc     | [01a41f9d99](https://linux-hardware.org/?probe=01a41f9d99) | Jun 01, 2022 |
| Dell          | Inspiron 15-5578            | Notebook    | [7c1c1fa1ce](https://linux-hardware.org/?probe=7c1c1fa1ce) | Jun 01, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [12cfa4cdb2](https://linux-hardware.org/?probe=12cfa4cdb2) | Jun 01, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [24fb23a450](https://linux-hardware.org/?probe=24fb23a450) | May 31, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [951bd2ea8d](https://linux-hardware.org/?probe=951bd2ea8d) | May 31, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [a9cca9972f](https://linux-hardware.org/?probe=a9cca9972f) | May 31, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [f05323c723](https://linux-hardware.org/?probe=f05323c723) | May 31, 2022 |
| Dell          | Inspiron 5770               | Notebook    | [02b32c935c](https://linux-hardware.org/?probe=02b32c935c) | May 31, 2022 |
| Positivo      | POS-PIG41BAG                | Desktop     | [7bfeaeb75b](https://linux-hardware.org/?probe=7bfeaeb75b) | May 31, 2022 |
| Positivo      | POS-PIG41BAG                | Desktop     | [3ca7484fcf](https://linux-hardware.org/?probe=3ca7484fcf) | May 31, 2022 |
| ASUSTek       | X450LD                      | Notebook    | [b77a4297da](https://linux-hardware.org/?probe=b77a4297da) | May 31, 2022 |
| Dell          | Inspiron 3541               | Notebook    | [20b5815ca3](https://linux-hardware.org/?probe=20b5815ca3) | May 31, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d078b8d5dd](https://linux-hardware.org/?probe=d078b8d5dd) | May 30, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [1dbf357f4f](https://linux-hardware.org/?probe=1dbf357f4f) | May 30, 2022 |
| Dell          | Latitude E6510              | Notebook    | [4fe104ba1c](https://linux-hardware.org/?probe=4fe104ba1c) | May 30, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [dbf473f0a0](https://linux-hardware.org/?probe=dbf473f0a0) | May 30, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [574439c3c6](https://linux-hardware.org/?probe=574439c3c6) | May 30, 2022 |
| Intel         | NUC5i3RYB H41000-507        | Mini pc     | [5874582cbc](https://linux-hardware.org/?probe=5874582cbc) | May 29, 2022 |
| Intel         | NUC5i3RYB H41000-507        | Mini pc     | [8435958f2a](https://linux-hardware.org/?probe=8435958f2a) | May 29, 2022 |
| HP            | Compaq 6510b (KE135EA#AK... | Notebook    | [28c05654fc](https://linux-hardware.org/?probe=28c05654fc) | May 29, 2022 |
| HP            | EW7-I7D22875GR1             | Notebook    | [e34608096b](https://linux-hardware.org/?probe=e34608096b) | May 29, 2022 |
| ASUSTek       | P7P55D DELUXE               | Desktop     | [ba2d55d308](https://linux-hardware.org/?probe=ba2d55d308) | May 29, 2022 |
| HP            | EW7-I7D22875GR1             | Notebook    | [d21454c335](https://linux-hardware.org/?probe=d21454c335) | May 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [33de40a2e1](https://linux-hardware.org/?probe=33de40a2e1) | May 29, 2022 |
| HP            | Laptop 14-dq0xxx            | Notebook    | [fac9e55ae9](https://linux-hardware.org/?probe=fac9e55ae9) | May 29, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [0bf1fadaa2](https://linux-hardware.org/?probe=0bf1fadaa2) | May 29, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [8895ea240a](https://linux-hardware.org/?probe=8895ea240a) | May 29, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [fa0b4c98df](https://linux-hardware.org/?probe=fa0b4c98df) | May 29, 2022 |
| Dell          | 0HN7XN A01                  | Desktop     | [9ebd09a280](https://linux-hardware.org/?probe=9ebd09a280) | May 29, 2022 |
| Dell          | Latitude 3410               | Notebook    | [b1115f6bbc](https://linux-hardware.org/?probe=b1115f6bbc) | May 28, 2022 |
| Gigabyte      | F2A58M-DS2                  | Desktop     | [3b95da87e9](https://linux-hardware.org/?probe=3b95da87e9) | May 28, 2022 |
| HP            | Laptop 14-dq0xxx            | Notebook    | [7d47123b6c](https://linux-hardware.org/?probe=7d47123b6c) | May 28, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [3302c5de16](https://linux-hardware.org/?probe=3302c5de16) | May 27, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [4e77d22694](https://linux-hardware.org/?probe=4e77d22694) | May 27, 2022 |
| Dell          | Latitude D630               | Notebook    | [0560d4c462](https://linux-hardware.org/?probe=0560d4c462) | May 27, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [9011cf0a9b](https://linux-hardware.org/?probe=9011cf0a9b) | May 27, 2022 |
| ASUSTek       | TUF B365M-PLUS GAMING       | Desktop     | [1137f80fcd](https://linux-hardware.org/?probe=1137f80fcd) | May 27, 2022 |
| ASUSTek       | TUF B365M-PLUS GAMING       | Desktop     | [57dbc86807](https://linux-hardware.org/?probe=57dbc86807) | May 27, 2022 |
| Dell          | Inspiron 5423               | Notebook    | [bd9cd24b2d](https://linux-hardware.org/?probe=bd9cd24b2d) | May 26, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [0d0af584d5](https://linux-hardware.org/?probe=0d0af584d5) | May 26, 2022 |
| Acer          | Aspire E3-112M              | Notebook    | [240ed3197a](https://linux-hardware.org/?probe=240ed3197a) | May 26, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | Notebook    | [ba19793a38](https://linux-hardware.org/?probe=ba19793a38) | May 26, 2022 |
| Lenovo        | ThinkPad T420 4236MBU       | Notebook    | [7a7ef6ced7](https://linux-hardware.org/?probe=7a7ef6ced7) | May 26, 2022 |
| ASUSTek       | H81M-A/BR                   | Desktop     | [5df43d2ecd](https://linux-hardware.org/?probe=5df43d2ecd) | May 26, 2022 |
| HP            | ZHAN 66 Pro A 14 G3         | Notebook    | [9d27d641ca](https://linux-hardware.org/?probe=9d27d641ca) | May 25, 2022 |
| HP            | ZHAN 66 Pro A 14 G3         | Notebook    | [db3577b92d](https://linux-hardware.org/?probe=db3577b92d) | May 25, 2022 |
| Dell          | 088DT1 A01                  | Desktop     | [19d760099e](https://linux-hardware.org/?probe=19d760099e) | May 25, 2022 |
| Lenovo        | ThinkPad X230 2324FV6       | Notebook    | [6386696f31](https://linux-hardware.org/?probe=6386696f31) | May 25, 2022 |
| Dell          | 088DT1 A01                  | Desktop     | [3334efe1e7](https://linux-hardware.org/?probe=3334efe1e7) | May 25, 2022 |
| HP            | ZBook 15 G2                 | Notebook    | [42ebc7f075](https://linux-hardware.org/?probe=42ebc7f075) | May 25, 2022 |
| Intel         | D946GZIS AAD66165-301       | Desktop     | [24c058da74](https://linux-hardware.org/?probe=24c058da74) | May 25, 2022 |
| HP            | EliteBook 8760w             | Notebook    | [b4066f49b0](https://linux-hardware.org/?probe=b4066f49b0) | May 25, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [dd317d92a3](https://linux-hardware.org/?probe=dd317d92a3) | May 25, 2022 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [18427eddde](https://linux-hardware.org/?probe=18427eddde) | May 25, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [0c52032af4](https://linux-hardware.org/?probe=0c52032af4) | May 24, 2022 |
| Lenovo        | ThinkPad P50 20EQS28400     | Notebook    | [a439693491](https://linux-hardware.org/?probe=a439693491) | May 24, 2022 |
| Lenovo        | ThinkPad P50 20EQS28400     | Notebook    | [cca71eec7f](https://linux-hardware.org/?probe=cca71eec7f) | May 24, 2022 |
| Dell          | Venue 8 Pro 5830            | Notebook    | [c07937f5ea](https://linux-hardware.org/?probe=c07937f5ea) | May 24, 2022 |
| ASUSTek       | X201EP                      | Notebook    | [783e306676](https://linux-hardware.org/?probe=783e306676) | May 24, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [d98649058e](https://linux-hardware.org/?probe=d98649058e) | May 24, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [6e45ae9f7c](https://linux-hardware.org/?probe=6e45ae9f7c) | May 24, 2022 |
| HP            | Laptop 15s-du2xxx           | Notebook    | [aeb154944d](https://linux-hardware.org/?probe=aeb154944d) | May 24, 2022 |
| Dell          | Latitude D520               | Notebook    | [55364bfdc0](https://linux-hardware.org/?probe=55364bfdc0) | May 24, 2022 |
| Lenovo        | ThinkPad X301 277418G       | Notebook    | [0d9a530751](https://linux-hardware.org/?probe=0d9a530751) | May 24, 2022 |
| HP            | Laptop 15s-du2xxx           | Notebook    | [bcccd55aab](https://linux-hardware.org/?probe=bcccd55aab) | May 24, 2022 |
| Toshiba       | Satellite L75D-A            | Notebook    | [0a4b6bedbf](https://linux-hardware.org/?probe=0a4b6bedbf) | May 24, 2022 |
| ASUSTek       | X756UQ                      | Notebook    | [e8736821c1](https://linux-hardware.org/?probe=e8736821c1) | May 23, 2022 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [4249d49f41](https://linux-hardware.org/?probe=4249d49f41) | May 22, 2022 |
| Toshiba       | Satellite L10W-C            | Notebook    | [a66d178a46](https://linux-hardware.org/?probe=a66d178a46) | May 21, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [dffc3ea80a](https://linux-hardware.org/?probe=dffc3ea80a) | May 21, 2022 |
| ASUSTek       | Z97-DELUXE                  | Desktop     | [084bacdad3](https://linux-hardware.org/?probe=084bacdad3) | May 21, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [00a44d4f7e](https://linux-hardware.org/?probe=00a44d4f7e) | May 21, 2022 |
| ASUSTek       | K43U                        | Notebook    | [a46669147d](https://linux-hardware.org/?probe=a46669147d) | May 21, 2022 |
| Positivo      | CHT14B                      | Notebook    | [435bbd3b75](https://linux-hardware.org/?probe=435bbd3b75) | May 20, 2022 |
| Samsung       | 930QDB                      | Convertible | [ecaa182549](https://linux-hardware.org/?probe=ecaa182549) | May 20, 2022 |
| MSI           | Z170A GAMING PRO            | Desktop     | [3a9789ed8a](https://linux-hardware.org/?probe=3a9789ed8a) | May 20, 2022 |
| HP            | Laptop 15-bs1xx             | Notebook    | [e2a3654000](https://linux-hardware.org/?probe=e2a3654000) | May 20, 2022 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [4ae1475168](https://linux-hardware.org/?probe=4ae1475168) | May 20, 2022 |
| Lenovo        | ThinkPad L560 20F1001YGE    | Notebook    | [8e5e8ea1ba](https://linux-hardware.org/?probe=8e5e8ea1ba) | May 20, 2022 |
| Medion        | Akoya S6214T                | Notebook    | [b0a0df98e0](https://linux-hardware.org/?probe=b0a0df98e0) | May 20, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [1d5fec86a8](https://linux-hardware.org/?probe=1d5fec86a8) | May 20, 2022 |
| MSI           | 760GM-P21                   | Desktop     | [b6b5e0738c](https://linux-hardware.org/?probe=b6b5e0738c) | May 19, 2022 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [13bc0ce7c5](https://linux-hardware.org/?probe=13bc0ce7c5) | May 19, 2022 |
| ASUSTek       | K43U                        | Notebook    | [2748cd44f0](https://linux-hardware.org/?probe=2748cd44f0) | May 19, 2022 |
| MSI           | B85M-G43                    | Desktop     | [ef33bf347c](https://linux-hardware.org/?probe=ef33bf347c) | May 18, 2022 |
| Foxconn       | 2AAF                        | Desktop     | [dd1193f7ab](https://linux-hardware.org/?probe=dd1193f7ab) | May 18, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [c5cdf9ba52](https://linux-hardware.org/?probe=c5cdf9ba52) | May 18, 2022 |
| HP            | Pavilion g4                 | Notebook    | [dcb7b65b12](https://linux-hardware.org/?probe=dcb7b65b12) | May 18, 2022 |
| Gateway       | NV55C                       | Notebook    | [16404d222a](https://linux-hardware.org/?probe=16404d222a) | May 18, 2022 |
| Gateway       | NV55C                       | Notebook    | [82fcde80bb](https://linux-hardware.org/?probe=82fcde80bb) | May 18, 2022 |
| ASUSTek       | ROG Strix G731GT_G731GT     | Notebook    | [5c20c841d1](https://linux-hardware.org/?probe=5c20c841d1) | May 18, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [2b889fc85b](https://linux-hardware.org/?probe=2b889fc85b) | May 17, 2022 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [d8b886317a](https://linux-hardware.org/?probe=d8b886317a) | May 17, 2022 |
| ASUSTek       | G15DK                       | Desktop     | [1df44e40e2](https://linux-hardware.org/?probe=1df44e40e2) | May 17, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [ecfb1c48d9](https://linux-hardware.org/?probe=ecfb1c48d9) | May 17, 2022 |
| Gigabyte      | M61PME-S2P                  | Desktop     | [7ab57b617f](https://linux-hardware.org/?probe=7ab57b617f) | May 17, 2022 |
| Sony          | VGN-FW51MF_H                | Notebook    | [084402167e](https://linux-hardware.org/?probe=084402167e) | May 17, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [aea8e14bff](https://linux-hardware.org/?probe=aea8e14bff) | May 17, 2022 |
| ASUSTek       | ROG Strix G713IM_G713IM     | Notebook    | [eb1da20105](https://linux-hardware.org/?probe=eb1da20105) | May 17, 2022 |
| Dell          | 0GTK4K A02                  | Desktop     | [fba6de28d9](https://linux-hardware.org/?probe=fba6de28d9) | May 16, 2022 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [ebbd363703](https://linux-hardware.org/?probe=ebbd363703) | May 16, 2022 |
| Intel         | D946GZIS AAD66165-301       | Desktop     | [4555cff448](https://linux-hardware.org/?probe=4555cff448) | May 16, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [7fcd8503ab](https://linux-hardware.org/?probe=7fcd8503ab) | May 16, 2022 |
| HP            | EliteBook 2570p             | Notebook    | [70ba6585e8](https://linux-hardware.org/?probe=70ba6585e8) | May 16, 2022 |
| Unknown       | Unknown                     | Notebook    | [bb968f8b83](https://linux-hardware.org/?probe=bb968f8b83) | May 16, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [b95339f19d](https://linux-hardware.org/?probe=b95339f19d) | May 15, 2022 |
| ASUSTek       | GL552VW                     | Notebook    | [2f26e2ec6e](https://linux-hardware.org/?probe=2f26e2ec6e) | May 15, 2022 |
| ASRock        | A88M-G                      | Desktop     | [81d094b2ec](https://linux-hardware.org/?probe=81d094b2ec) | May 15, 2022 |
| ASRock        | A88M-G                      | Desktop     | [8883591354](https://linux-hardware.org/?probe=8883591354) | May 15, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [0d9d6b919b](https://linux-hardware.org/?probe=0d9d6b919b) | May 15, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [ddadf86375](https://linux-hardware.org/?probe=ddadf86375) | May 15, 2022 |
| ASUSTek       | PRIME H310-PLUS             | Desktop     | [770fbfefd3](https://linux-hardware.org/?probe=770fbfefd3) | May 15, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [c9da66f0e8](https://linux-hardware.org/?probe=c9da66f0e8) | May 15, 2022 |
| Thomson       | NEO14SBK                    | Notebook    | [2ae5fbd212](https://linux-hardware.org/?probe=2ae5fbd212) | May 15, 2022 |
| ASUSTek       | PRIME H310-PLUS             | Desktop     | [8baee6f2e6](https://linux-hardware.org/?probe=8baee6f2e6) | May 14, 2022 |
| MSI           | MPG B560I GAMING EDGE WI... | Desktop     | [08ba1e652c](https://linux-hardware.org/?probe=08ba1e652c) | May 14, 2022 |
| Intel         | S5520HC E26045-457          | Server      | [ce6fe2a9cd](https://linux-hardware.org/?probe=ce6fe2a9cd) | May 14, 2022 |
| ASUSTek       | N80Vb                       | Notebook    | [74cb7e076b](https://linux-hardware.org/?probe=74cb7e076b) | May 13, 2022 |
| Acer          | Aspire E1-522               | Notebook    | [21a4fc80c7](https://linux-hardware.org/?probe=21a4fc80c7) | May 13, 2022 |
| Alienware     | 17                          | Notebook    | [b9be04342c](https://linux-hardware.org/?probe=b9be04342c) | May 13, 2022 |
| HP            | OMEN by Laptop              | Notebook    | [f08cef4e3b](https://linux-hardware.org/?probe=f08cef4e3b) | May 13, 2022 |
| Lenovo        | ThinkPad T61 7661V72        | Notebook    | [3d40fb11e8](https://linux-hardware.org/?probe=3d40fb11e8) | May 13, 2022 |
| HP            | EliteBook x360 1030 G3      | Convertible | [602289ad13](https://linux-hardware.org/?probe=602289ad13) | May 13, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [2695dd828d](https://linux-hardware.org/?probe=2695dd828d) | May 13, 2022 |
| Acer          | Aspire E1-522               | Notebook    | [77fdc036b0](https://linux-hardware.org/?probe=77fdc036b0) | May 13, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [048951833f](https://linux-hardware.org/?probe=048951833f) | May 13, 2022 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [f45bf21321](https://linux-hardware.org/?probe=f45bf21321) | May 12, 2022 |
| Dell          | 0F2A30 A00                  | All in one  | [ae5664a81f](https://linux-hardware.org/?probe=ae5664a81f) | May 12, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [86d60d0227](https://linux-hardware.org/?probe=86d60d0227) | May 12, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [3824ac02d2](https://linux-hardware.org/?probe=3824ac02d2) | May 12, 2022 |
| Pegatron      | 2A99h                       | Desktop     | [6a47713af6](https://linux-hardware.org/?probe=6a47713af6) | May 12, 2022 |
| AOpen         | i67QMx-DV R1.00BC1 55MP6... | Desktop     | [151db99970](https://linux-hardware.org/?probe=151db99970) | May 11, 2022 |
| Acer          | Aspire X3990                | Desktop     | [c6753ff37f](https://linux-hardware.org/?probe=c6753ff37f) | May 11, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [8f62053ddd](https://linux-hardware.org/?probe=8f62053ddd) | May 11, 2022 |
| Dell          | Latitude E6540              | Notebook    | [422c7a9209](https://linux-hardware.org/?probe=422c7a9209) | May 11, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [018c90008f](https://linux-hardware.org/?probe=018c90008f) | May 11, 2022 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [b1d977cd69](https://linux-hardware.org/?probe=b1d977cd69) | May 11, 2022 |
| Gigabyte      | EX58-EXTREME                | Desktop     | [b558000bcc](https://linux-hardware.org/?probe=b558000bcc) | May 10, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [72b102de04](https://linux-hardware.org/?probe=72b102de04) | May 10, 2022 |
| ASUSTek       | X200CA                      | Notebook    | [e041ed14b2](https://linux-hardware.org/?probe=e041ed14b2) | May 10, 2022 |
| Dell          | 0DR845                      | Desktop     | [ab501b0efe](https://linux-hardware.org/?probe=ab501b0efe) | May 10, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [92637583b8](https://linux-hardware.org/?probe=92637583b8) | May 10, 2022 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [838a99f17a](https://linux-hardware.org/?probe=838a99f17a) | May 10, 2022 |
| Gigabyte      | B365M GAMING HD             | Desktop     | [5590d9a0f3](https://linux-hardware.org/?probe=5590d9a0f3) | May 10, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [81cd3de099](https://linux-hardware.org/?probe=81cd3de099) | May 09, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [a5deca63d5](https://linux-hardware.org/?probe=a5deca63d5) | May 09, 2022 |
| Dell          | 0GXM1W A02                  | Desktop     | [1606b44e03](https://linux-hardware.org/?probe=1606b44e03) | May 09, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [42f2a531b5](https://linux-hardware.org/?probe=42f2a531b5) | May 09, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [637a04a2d1](https://linux-hardware.org/?probe=637a04a2d1) | May 09, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [911b8e4c5b](https://linux-hardware.org/?probe=911b8e4c5b) | May 09, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [8e43525285](https://linux-hardware.org/?probe=8e43525285) | May 09, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Zorin_16/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                 | Computers | Percent |
|-------------------------|-----------|---------|
| 5.11.0-38-generic       | 176       | 7.51%   |
| 5.11.0-27-generic       | 154       | 6.57%   |
| 5.15.0-46-generic       | 151       | 6.44%   |
| 5.11.0-40-generic       | 124       | 5.29%   |
| 5.13.0-39-generic       | 120       | 5.12%   |
| 5.13.0-30-generic       | 119       | 5.07%   |
| 5.11.0-41-generic       | 107       | 4.56%   |
| 5.11.0-37-generic       | 107       | 4.56%   |
| 5.11.0-43-generic       | 101       | 4.31%   |
| 5.11.0-34-generic       | 94        | 4.01%   |
| 5.15.0-48-generic       | 91        | 3.88%   |
| 5.13.0-40-generic       | 89        | 3.8%    |
| 5.13.0-44-generic       | 76        | 3.24%   |
| 5.15.0-52-generic       | 75        | 3.2%    |
| 5.13.0-35-generic       | 74        | 3.16%   |
| 5.15.0-41-generic       | 72        | 3.07%   |
| 5.13.0-28-generic       | 71        | 3.03%   |
| 5.13.0-52-generic       | 59        | 2.52%   |
| 5.13.0-27-generic       | 59        | 2.52%   |
| 5.13.0-41-generic       | 54        | 2.3%    |
| 5.13.0-51-generic       | 41        | 1.75%   |
| 5.11.0-36-generic       | 39        | 1.66%   |
| 5.15.0-43-generic       | 38        | 1.62%   |
| 5.11.0-46-generic       | 35        | 1.49%   |
| 5.11.0-44-generic       | 34        | 1.45%   |
| 5.13.0-37-generic       | 29        | 1.24%   |
| 5.13.0-48-generic       | 21        | 0.9%    |
| 5.15.0-50-generic       | 19        | 0.81%   |
| 5.11.0-25-generic       | 16        | 0.68%   |
| 5.8.0-53-generic        | 13        | 0.55%   |
| 5.8.0-50-generic        | 12        | 0.51%   |
| 5.8.0-59-generic        | 9         | 0.38%   |
| 5.8.0-55-generic        | 9         | 0.38%   |
| 5.8.0-49-generic        | 5         | 0.21%   |
| 5.8.0-63-generic        | 4         | 0.17%   |
| 5.13.0-25-generic       | 3         | 0.13%   |
| 5.14.0-1052-oem         | 2         | 0.09%   |
| 6.0.0-060000-generic    | 1         | 0.04%   |
| 5.8.0-45-generic        | 1         | 0.04%   |
| 5.4.180-0504180-generic | 1         | 0.04%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11.0  | 944       | 42.66%  |
| 5.13.0  | 756       | 34.16%  |
| 5.15.0  | 424       | 19.16%  |
| 5.8.0   | 52        | 2.35%   |
| 5.14.0  | 8         | 0.36%   |
| 5.4.0   | 2         | 0.09%   |
| 5.17.5  | 2         | 0.09%   |
| 5.17.1  | 2         | 0.09%   |
| 5.16.0  | 2         | 0.09%   |
| 5.10.0  | 2         | 0.09%   |
| 6.0.0   | 1         | 0.05%   |
| 5.4.180 | 1         | 0.05%   |
| 5.19.9  | 1         | 0.05%   |
| 5.19.6  | 1         | 0.05%   |
| 5.19.2  | 1         | 0.05%   |
| 5.19.14 | 1         | 0.05%   |
| 5.19.12 | 1         | 0.05%   |
| 5.19.1  | 1         | 0.05%   |
| 5.19.0  | 1         | 0.05%   |
| 5.18.6  | 1         | 0.05%   |
| 5.18.15 | 1         | 0.05%   |
| 5.17.9  | 1         | 0.05%   |
| 5.16.5  | 1         | 0.05%   |
| 5.16.14 | 1         | 0.05%   |
| 5.16.12 | 1         | 0.05%   |
| 5.15.49 | 1         | 0.05%   |
| 5.15.24 | 1         | 0.05%   |
| 5.15.13 | 1         | 0.05%   |
| 5.13.18 | 1         | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 944       | 42.66%  |
| 5.13    | 757       | 34.21%  |
| 5.15    | 427       | 19.3%   |
| 5.8     | 52        | 2.35%   |
| 5.14    | 8         | 0.36%   |
| 5.19    | 7         | 0.32%   |
| 5.17    | 5         | 0.23%   |
| 5.16    | 5         | 0.23%   |
| 5.4     | 3         | 0.14%   |
| 5.18    | 2         | 0.09%   |
| 5.10    | 2         | 0.09%   |
| 6.0     | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 2107      | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 1879      | 88.63%  |
| XFCE       | 218       | 10.28%  |
| Unknown    | 13        | 0.61%   |
| X-Cinnamon | 3         | 0.14%   |
| Cinnamon   | 2         | 0.09%   |
| Unity      | 1         | 0.05%   |
| MATE       | 1         | 0.05%   |
| KDE5       | 1         | 0.05%   |
| KDE        | 1         | 0.05%   |
| Budgie     | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 2082      | 98.21%  |
| Wayland | 33        | 1.56%   |
| Unknown | 4         | 0.19%   |
| Tty     | 1         | 0.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1668      | 78.38%  |
| GDM     | 208       | 9.77%   |
| GDM3    | 202       | 9.49%   |
| LightDM | 48        | 2.26%   |
| TDM     | 1         | 0.05%   |
| SDDM    | 1         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 835       | 39.48%  |
| de_DE | 201       | 9.5%    |
| en_GB | 159       | 7.52%   |
| pt_BR | 126       | 5.96%   |
| fr_FR | 65        | 3.07%   |
| es_ES | 59        | 2.79%   |
| en_IN | 57        | 2.7%    |
| it_IT | 55        | 2.6%    |
| en_CA | 55        | 2.6%    |
| pl_PL | 50        | 2.36%   |
| en_AU | 48        | 2.27%   |
| nl_NL | 40        | 1.89%   |
| es_MX | 35        | 1.65%   |
| ru_RU | 29        | 1.37%   |
| en_ZA | 21        | 0.99%   |
| cs_CZ | 21        | 0.99%   |
| pt_PT | 18        | 0.85%   |
| tr_TR | 14        | 0.66%   |
| fr_BE | 13        | 0.61%   |
| es_AR | 13        | 0.61%   |
| en_NZ | 13        | 0.61%   |
| es_CL | 12        | 0.57%   |
| sv_SE | 11        | 0.52%   |
| nl_BE | 10        | 0.47%   |
| hu_HU | 10        | 0.47%   |
| fr_CA | 9         | 0.43%   |
| el_GR | 8         | 0.38%   |
| de_AT | 8         | 0.38%   |
| nb_NO | 7         | 0.33%   |
| es_CO | 7         | 0.33%   |
| fi_FI | 6         | 0.28%   |
| de_CH | 6         | 0.28%   |
| ja_JP | 5         | 0.24%   |
| es_VE | 5         | 0.24%   |
| en_PH | 5         | 0.24%   |
| en_IL | 5         | 0.24%   |
| ar_EG | 5         | 0.24%   |
| sr_RS | 4         | 0.19%   |
| sk_SK | 4         | 0.19%   |
| ru_UA | 4         | 0.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1177      | 55.23%  |
| BIOS | 954       | 44.77%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 1997      | 94.6%   |
| Zfs      | 41        | 1.94%   |
| Overlay  | 32        | 1.52%   |
| Btrfs    | 25        | 1.18%   |
| Xfs      | 6         | 0.28%   |
| Ext3     | 5         | 0.24%   |
| Ext2     | 4         | 0.19%   |
| Reiserfs | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1847      | 87.16%  |
| GPT     | 219       | 10.34%  |
| MBR     | 53        | 2.5%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2061      | 97.63%  |
| Yes       | 50        | 2.37%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1901      | 89.92%  |
| Yes       | 213       | 10.08%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 357       | 16.94%  |
| ASUSTek Computer    | 346       | 16.42%  |
| Dell                | 282       | 13.38%  |
| Lenovo              | 246       | 11.68%  |
| Gigabyte Technology | 129       | 6.12%   |
| Acer                | 108       | 5.13%   |
| MSI                 | 100       | 4.75%   |
| Apple               | 63        | 2.99%   |
| ASRock              | 61        | 2.9%    |
| Toshiba             | 57        | 2.71%   |
| Intel               | 36        | 1.71%   |
| Samsung Electronics | 27        | 1.28%   |
| Unknown             | 20        | 0.95%   |
| Fujitsu             | 16        | 0.76%   |
| Sony                | 15        | 0.71%   |
| Google              | 13        | 0.62%   |
| Packard Bell        | 12        | 0.57%   |
| Biostar             | 12        | 0.57%   |
| Microsoft           | 11        | 0.52%   |
| HUAWEI              | 10        | 0.47%   |
| Foxconn             | 10        | 0.47%   |
| Positivo            | 9         | 0.43%   |
| Alienware           | 9         | 0.43%   |
| Pegatron            | 7         | 0.33%   |
| Medion              | 7         | 0.33%   |
| Chuwi               | 7         | 0.33%   |
| Notebook            | 6         | 0.28%   |
| AMI                 | 6         | 0.28%   |
| Gateway             | 5         | 0.24%   |
| Razer               | 4         | 0.19%   |
| LG Electronics      | 4         | 0.19%   |
| GPU Company         | 4         | 0.19%   |
| Fujitsu Siemens     | 4         | 0.19%   |
| BESSTAR Tech        | 4         | 0.19%   |
| RCA                 | 3         | 0.14%   |
| OEM                 | 3         | 0.14%   |
| Multilaser          | 3         | 0.14%   |
| Jumper              | 3         | 0.14%   |
| Insyde              | 3         | 0.14%   |
| ZOTAC               | 2         | 0.09%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| Unknown                          | 28        | 1.33%   |
| ASUS All Series                  | 22        | 1.04%   |
| HP Notebook                      | 15        | 0.71%   |
| HP Pavilion Notebook             | 11        | 0.52%   |
| Dell OptiPlex 7010               | 8         | 0.38%   |
| HP 15                            | 7         | 0.33%   |
| Dell OptiPlex 790                | 7         | 0.33%   |
| MSI MS-7C02                      | 5         | 0.24%   |
| HP Pavilion 15                   | 5         | 0.24%   |
| Dell OptiPlex 990                | 5         | 0.24%   |
| Dell OptiPlex 780                | 5         | 0.24%   |
| ASUS M5A78L-M/USB3               | 5         | 0.24%   |
| Apple MacBookPro8,1              | 5         | 0.24%   |
| Toshiba Satellite C660           | 4         | 0.19%   |
| Toshiba Satellite C55-C          | 4         | 0.19%   |
| MSI MS-7817                      | 4         | 0.19%   |
| HP ProBook 640 G1                | 4         | 0.19%   |
| HP Pavilion dv7                  | 4         | 0.19%   |
| HP Laptop 15-bw0xx               | 4         | 0.19%   |
| HP Compaq Pro 6300 SFF           | 4         | 0.19%   |
| Gigabyte B450 AORUS M            | 4         | 0.19%   |
| Gigabyte A320M-S2H               | 4         | 0.19%   |
| Dell Precision WorkStation T3500 | 4         | 0.19%   |
| Dell Latitude E7440              | 4         | 0.19%   |
| Dell Inspiron 3542               | 4         | 0.19%   |
| Dell Inspiron 3521               | 4         | 0.19%   |
| Dell Inspiron 15-3567            | 4         | 0.19%   |
| ASUS TUF Gaming X570-PLUS        | 4         | 0.19%   |
| ASRock B450 Pro4                 | 4         | 0.19%   |
| Apple iMac12,1                   | 4         | 0.19%   |
| OEM G41 775 ICH7 8712            | 3         | 0.14%   |
| Microsoft Surface Pro 4          | 3         | 0.14%   |
| Microsoft Surface Pro            | 3         | 0.14%   |
| Lenovo Yoga 3 Pro-1370 80HE      | 3         | 0.14%   |
| Lenovo IdeaPad S340-14API 81NB   | 3         | 0.14%   |
| Lenovo IdeaPad S145-15API 81V7   | 3         | 0.14%   |
| Lenovo IdeaPad Flex-14API 81SS   | 3         | 0.14%   |
| Lenovo IdeaPad 3 15IIL05 81WE    | 3         | 0.14%   |
| Lenovo G500 20236                | 3         | 0.14%   |
| Lenovo G50-70 20351              | 3         | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Dell Inspiron         | 82        | 3.89%   |
| Acer Aspire           | 74        | 3.51%   |
| Lenovo ThinkPad       | 72        | 3.42%   |
| Dell Latitude         | 72        | 3.42%   |
| HP Pavilion           | 71        | 3.37%   |
| Lenovo IdeaPad        | 63        | 2.99%   |
| Dell OptiPlex         | 51        | 2.42%   |
| Toshiba Satellite     | 46        | 2.18%   |
| HP EliteBook          | 35        | 1.66%   |
| HP ProBook            | 32        | 1.52%   |
| ASUS PRIME            | 32        | 1.52%   |
| ASUS ROG              | 31        | 1.47%   |
| HP Compaq             | 30        | 1.42%   |
| Unknown               | 28        | 1.33%   |
| HP Laptop             | 26        | 1.23%   |
| ASUS VivoBook         | 24        | 1.14%   |
| Lenovo ThinkCentre    | 23        | 1.09%   |
| ASUS All              | 22        | 1.04%   |
| HP ENVY               | 21        | 1%      |
| ASUS TUF              | 20        | 0.95%   |
| Dell XPS              | 19        | 0.9%    |
| Dell Vostro           | 18        | 0.85%   |
| Dell Precision        | 18        | 0.85%   |
| HP Notebook           | 15        | 0.71%   |
| Lenovo Yoga           | 13        | 0.62%   |
| Microsoft Surface     | 11        | 0.52%   |
| HP Stream             | 11        | 0.52%   |
| HP OMEN               | 11        | 0.52%   |
| HP EliteDesk          | 11        | 0.52%   |
| Packard Bell EasyNote | 9         | 0.43%   |
| Gigabyte B450         | 9         | 0.43%   |
| ASUS ZenBook          | 9         | 0.43%   |
| HP 15                 | 8         | 0.38%   |
| Fujitsu ESPRIMO       | 8         | 0.38%   |
| ASUS M5A78L-M         | 8         | 0.38%   |
| ASUS ASUS             | 8         | 0.38%   |
| Gigabyte X570         | 7         | 0.33%   |
| Dell Studio           | 7         | 0.33%   |
| ASRock B450           | 7         | 0.33%   |
| Apple MacBookPro8     | 7         | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 193       | 9.16%   |
| 2013    | 185       | 8.78%   |
| 2011    | 185       | 8.78%   |
| 2021    | 172       | 8.16%   |
| 2019    | 171       | 8.12%   |
| 2020    | 167       | 7.93%   |
| 2018    | 166       | 7.88%   |
| 2014    | 150       | 7.12%   |
| 2017    | 122       | 5.79%   |
| 2016    | 122       | 5.79%   |
| 2010    | 122       | 5.79%   |
| 2015    | 97        | 4.6%    |
| 2008    | 93        | 4.41%   |
| 2009    | 73        | 3.46%   |
| 2007    | 54        | 2.56%   |
| 2022    | 15        | 0.71%   |
| 2006    | 14        | 0.66%   |
| 2005    | 4         | 0.19%   |
| Unknown | 2         | 0.09%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 1163      | 55.2%   |
| Desktop     | 780       | 37.02%  |
| Convertible | 48        | 2.28%   |
| All in one  | 48        | 2.28%   |
| Mini pc     | 32        | 1.52%   |
| Tablet      | 31        | 1.47%   |
| Server      | 5         | 0.24%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1870      | 88.04%  |
| Enabled  | 254       | 11.96%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2091      | 99.24%  |
| Yes  | 16        | 0.76%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 560       | 26.44%  |
| 3.01-4.0    | 467       | 22.05%  |
| 8.01-16.0   | 384       | 18.13%  |
| 16.01-24.0  | 352       | 16.62%  |
| 32.01-64.0  | 167       | 7.88%   |
| 1.01-2.0    | 104       | 4.91%   |
| 64.01-256.0 | 36        | 1.7%    |
| 2.01-3.0    | 27        | 1.27%   |
| 24.01-32.0  | 18        | 0.85%   |
| 0.51-1.0    | 3         | 0.14%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 910       | 40.32%  |
| 2.01-3.0   | 739       | 32.74%  |
| 3.01-4.0   | 292       | 12.94%  |
| 4.01-8.0   | 237       | 10.5%   |
| 8.01-16.0  | 35        | 1.55%   |
| 0.51-1.0   | 35        | 1.55%   |
| 16.01-24.0 | 5         | 0.22%   |
| 24.01-32.0 | 3         | 0.13%   |
| 0.01-0.5   | 1         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1332      | 62.01%  |
| 2      | 527       | 24.53%  |
| 3      | 140       | 6.52%   |
| 4      | 63        | 2.93%   |
| 5      | 33        | 1.54%   |
| 6      | 22        | 1.02%   |
| 0      | 13        | 0.61%   |
| 7      | 8         | 0.37%   |
| 8      | 7         | 0.33%   |
| 51     | 1         | 0.05%   |
| 30     | 1         | 0.05%   |
| 11     | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1157      | 54.65%  |
| Yes       | 960       | 45.35%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1786      | 84.56%  |
| No        | 326       | 15.44%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1659      | 78.59%  |
| No        | 452       | 21.41%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1236      | 58.22%  |
| No        | 887       | 41.78%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 505       | 23.9%   |
| Germany      | 216       | 10.22%  |
| UK           | 140       | 6.63%   |
| Brazil       | 139       | 6.58%   |
| Canada       | 74        | 3.5%    |
| Spain        | 67        | 3.17%   |
| Italy        | 61        | 2.89%   |
| France       | 61        | 2.89%   |
| India        | 59        | 2.79%   |
| Netherlands  | 57        | 2.7%    |
| Australia    | 50        | 2.37%   |
| Poland       | 49        | 2.32%   |
| Mexico       | 41        | 1.94%   |
| Belgium      | 30        | 1.42%   |
| Russia       | 29        | 1.37%   |
| South Africa | 26        | 1.23%   |
| Czechia      | 22        | 1.04%   |
| Austria      | 22        | 1.04%   |
| Sweden       | 21        | 0.99%   |
| Turkey       | 20        | 0.95%   |
| Portugal     | 19        | 0.9%    |
| Norway       | 19        | 0.9%    |
| Argentina    | 18        | 0.85%   |
| Switzerland  | 17        | 0.8%    |
| Greece       | 17        | 0.8%    |
| Hungary      | 16        | 0.76%   |
| Romania      | 15        | 0.71%   |
| New Zealand  | 14        | 0.66%   |
| Chile        | 14        | 0.66%   |
| Japan        | 13        | 0.62%   |
| Egypt        | 13        | 0.62%   |
| Denmark      | 13        | 0.62%   |
| Finland      | 10        | 0.47%   |
| Slovenia     | 9         | 0.43%   |
| Malaysia     | 9         | 0.43%   |
| Colombia     | 9         | 0.43%   |
| Serbia       | 8         | 0.38%   |
| Indonesia    | 8         | 0.38%   |
| Bulgaria     | 8         | 0.38%   |
| Ukraine      | 7         | 0.33%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Berlin            | 18        | 0.83%   |
| Athens            | 18        | 0.83%   |
| Munich            | 17        | 0.78%   |
| Sydney            | 13        | 0.6%    |
| Sao Paulo         | 12        | 0.55%   |
| Madrid            | 12        | 0.55%   |
| Vienna            | 11        | 0.51%   |
| Dallas            | 11        | 0.51%   |
| Rome              | 10        | 0.46%   |
| New York          | 10        | 0.46%   |
| Montreal          | 10        | 0.46%   |
| Hamburg           | 9         | 0.42%   |
| Salt Lake City    | 8         | 0.37%   |
| Rio de Janeiro    | 8         | 0.37%   |
| Johannesburg      | 8         | 0.37%   |
| Glasgow           | 8         | 0.37%   |
| Auckland          | 8         | 0.37%   |
| Valencia          | 7         | 0.32%   |
| Mexico City       | 7         | 0.32%   |
| London            | 7         | 0.32%   |
| Istanbul          | 7         | 0.32%   |
| Frankfurt am Main | 7         | 0.32%   |
| Buenos Aires      | 7         | 0.32%   |
| Brisbane          | 7         | 0.32%   |
| Amsterdam         | 7         | 0.32%   |
| Stuttgart         | 6         | 0.28%   |
| Seattle           | 6         | 0.28%   |
| Richmond          | 6         | 0.28%   |
| Prague            | 6         | 0.28%   |
| Perth             | 6         | 0.28%   |
| Paris             | 6         | 0.28%   |
| Moscow            | 6         | 0.28%   |
| Melbourne         | 6         | 0.28%   |
| Denver            | 6         | 0.28%   |
| Delhi             | 6         | 0.28%   |
| Cape Town         | 6         | 0.28%   |
| Bengaluru         | 6         | 0.28%   |
| Austin            | 6         | 0.28%   |
| Adelaide          | 6         | 0.28%   |
| Zagreb            | 5         | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 491       | 683    | 16.43%  |
| Samsung Electronics       | 400       | 579    | 13.38%  |
| WDC                       | 393       | 524    | 13.15%  |
| Toshiba                   | 227       | 294    | 7.59%   |
| SanDisk                   | 183       | 207    | 6.12%   |
| Unknown                   | 168       | 231    | 5.62%   |
| Kingston                  | 168       | 213    | 5.62%   |
| Crucial                   | 114       | 139    | 3.81%   |
| Hitachi                   | 97        | 129    | 3.25%   |
| Intel                     | 57        | 74     | 1.91%   |
| SK hynix                  | 54        | 65     | 1.81%   |
| HGST                      | 49        | 63     | 1.64%   |
| A-DATA Technology         | 44        | 52     | 1.47%   |
| Micron Technology         | 35        | 42     | 1.17%   |
| China                     | 29        | 33     | 0.97%   |
| Phison                    | 27        | 31     | 0.9%    |
| Apple                     | 26        | 29     | 0.87%   |
| Intenso                   | 24        | 26     | 0.8%    |
| PNY                       | 22        | 28     | 0.74%   |
| Silicon Motion            | 19        | 26     | 0.64%   |
| OCZ                       | 15        | 18     | 0.5%    |
| Netac                     | 15        | 16     | 0.5%    |
| KIOXIA                    | 15        | 15     | 0.5%    |
| SPCC                      | 14        | 17     | 0.47%   |
| Patriot                   | 13        | 17     | 0.43%   |
| JMicron Technology        | 13        | 15     | 0.43%   |
| GOODRAM                   | 13        | 14     | 0.43%   |
| Lexar                     | 12        | 12     | 0.4%    |
| LITEON                    | 11        | 13     | 0.37%   |
| Unknown                   | 11        | 12     | 0.37%   |
| Team                      | 10        | 13     | 0.33%   |
| Hewlett-Packard           | 10        | 14     | 0.33%   |
| Transcend                 | 9         | 26     | 0.3%    |
| SABRENT                   | 8         | 9      | 0.27%   |
| Micron/Crucial Technology | 8         | 8      | 0.27%   |
| Gigabyte Technology       | 8         | 10     | 0.27%   |
| Realtek Semiconductor     | 7         | 8      | 0.23%   |
| LITEONIT                  | 7         | 8      | 0.23%   |
| KingSpec                  | 7         | 9      | 0.23%   |
| XPG                       | 6         | 7      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                 | 54        | 1.63%   |
| Unknown MMC Card  64GB                 | 46        | 1.39%   |
| Kingston SA400S37240G 240GB SSD        | 39        | 1.18%   |
| Seagate ST500DM002-1BD142 500GB        | 32        | 0.97%   |
| Samsung SSD 860 EVO 500GB              | 28        | 0.84%   |
| Seagate ST1000LM035-1RK172 1TB         | 27        | 0.81%   |
| Crucial CT240BX500SSD1 240GB           | 27        | 0.81%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 26        | 0.78%   |
| Samsung NVMe SSD Drive 512GB           | 25        | 0.75%   |
| Samsung NVMe SSD Drive 1TB             | 25        | 0.75%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 24        | 0.72%   |
| Unknown MMC Card  128GB                | 23        | 0.69%   |
| Kingston SA400S37480G 480GB SSD        | 23        | 0.69%   |
| Toshiba MQ01ABF050 500GB               | 22        | 0.66%   |
| Toshiba MQ01ABD100 1TB                 | 22        | 0.66%   |
| Seagate ST1000DM010-2EP102 1TB         | 21        | 0.63%   |
| SanDisk NVMe SSD Drive 256GB           | 21        | 0.63%   |
| Samsung NVMe SSD Drive 500GB           | 21        | 0.63%   |
| Kingston SA400S37120G 120GB SSD        | 21        | 0.63%   |
| Unknown SD/MMC/MS PRO 1TB              | 19        | 0.57%   |
| Toshiba MQ04ABF100 1TB                 | 19        | 0.57%   |
| Samsung SSD 850 EVO 250GB              | 18        | 0.54%   |
| Samsung SSD 850 EVO 500GB              | 17        | 0.51%   |
| Crucial CT500MX500SSD1 500GB           | 17        | 0.51%   |
| WDC WD10EZEX-08WN4A0 1TB               | 16        | 0.48%   |
| Seagate Expansion 2TB                  | 16        | 0.48%   |
| SanDisk NVMe SSD Drive 512GB           | 15        | 0.45%   |
| SanDisk NVMe SSD Drive 1TB             | 15        | 0.45%   |
| Seagate ST500LT012-1DG142 500GB        | 14        | 0.42%   |
| Kingston SV300S37A120G 120GB SSD       | 14        | 0.42%   |
| Intel NVMe SSD Drive 512GB             | 14        | 0.42%   |
| Seagate ST3500418AS 500GB              | 13        | 0.39%   |
| Samsung SSD 870 EVO 1TB                | 13        | 0.39%   |
| Seagate ST9500325AS 500GB              | 12        | 0.36%   |
| Seagate ST2000DM008-2FR102 2TB         | 12        | 0.36%   |
| Seagate ST1000DM003-1CH162 1TB         | 12        | 0.36%   |
| Samsung SSD 860 EVO 250GB              | 12        | 0.36%   |
| Samsung SSD 840 EVO 250GB              | 12        | 0.36%   |
| Crucial CT1000MX500SSD1 1TB            | 12        | 0.36%   |
| Unknown MMC Card  16GB                 | 11        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 486       | 666    | 38.6%   |
| WDC                 | 341       | 446    | 27.08%  |
| Toshiba             | 176       | 239    | 13.98%  |
| Hitachi             | 97        | 129    | 7.7%    |
| HGST                | 49        | 63     | 3.89%   |
| Samsung Electronics | 48        | 61     | 3.81%   |
| Unknown             | 19        | 22     | 1.51%   |
| Apple               | 13        | 15     | 1.03%   |
| SABRENT             | 8         | 9      | 0.64%   |
| Maxtor              | 6         | 7      | 0.48%   |
| Fujitsu             | 6         | 7      | 0.48%   |
| USB3.0              | 3         | 4      | 0.24%   |
| Hewlett-Packard     | 3         | 6      | 0.24%   |
| Intenso             | 2         | 2      | 0.16%   |
| KESU                | 1         | 1      | 0.08%   |
| JMicron Technology  | 1         | 1      | 0.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 213       | 293    | 20.46%  |
| Kingston            | 137       | 173    | 13.16%  |
| Crucial             | 110       | 133    | 10.57%  |
| SanDisk             | 105       | 123    | 10.09%  |
| WDC                 | 46        | 57     | 4.42%   |
| A-DATA Technology   | 39        | 47     | 3.75%   |
| China               | 29        | 33     | 2.79%   |
| Toshiba             | 27        | 29     | 2.59%   |
| PNY                 | 22        | 28     | 2.11%   |
| Intel               | 22        | 26     | 2.11%   |
| SK hynix            | 19        | 19     | 1.83%   |
| Micron Technology   | 18        | 21     | 1.73%   |
| Intenso             | 16        | 17     | 1.54%   |
| Netac               | 15        | 16     | 1.44%   |
| OCZ                 | 14        | 17     | 1.34%   |
| SPCC                | 13        | 16     | 1.25%   |
| Patriot             | 13        | 17     | 1.25%   |
| GOODRAM             | 12        | 13     | 1.15%   |
| LITEON              | 11        | 13     | 1.06%   |
| Lexar               | 11        | 11     | 1.06%   |
| Apple               | 11        | 11     | 1.06%   |
| Team                | 10        | 13     | 0.96%   |
| Transcend           | 9         | 26     | 0.86%   |
| LITEONIT            | 7         | 8      | 0.67%   |
| KingSpec            | 7         | 9      | 0.67%   |
| Hewlett-Packard     | 7         | 8      | 0.67%   |
| Gigabyte Technology | 7         | 8      | 0.67%   |
| Leven               | 6         | 7      | 0.58%   |
| Super Talent        | 4         | 5      | 0.38%   |
| FORESEE             | 4         | 4      | 0.38%   |
| ASMT                | 4         | 4      | 0.38%   |
| Apacer              | 4         | 4      | 0.38%   |
| Unknown             | 4         | 5      | 0.38%   |
| Seagate             | 3         | 5      | 0.29%   |
| Plextor             | 3         | 4      | 0.29%   |
| OWC                 | 3         | 3      | 0.29%   |
| Mushkin             | 3         | 3      | 0.29%   |
| KIOXIA-EXCERIA      | 3         | 6      | 0.29%   |
| BHT                 | 3         | 4      | 0.29%   |
| Verbatim            | 2         | 2      | 0.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1070      | 1678   | 39.51%  |
| SSD     | 932       | 1294   | 34.42%  |
| NVMe    | 493       | 650    | 18.21%  |
| MMC     | 155       | 204    | 5.72%   |
| Unknown | 58        | 80     | 2.14%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1687      | 2875   | 68.61%  |
| NVMe | 487       | 641    | 19.8%   |
| MMC  | 155       | 204    | 6.3%    |
| SAS  | 130       | 186    | 5.29%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1241      | 1762   | 59.69%  |
| 0.51-1.0   | 587       | 799    | 28.23%  |
| 1.01-2.0   | 153       | 215    | 7.36%   |
| 3.01-4.0   | 41        | 101    | 1.97%   |
| 4.01-10.0  | 32        | 46     | 1.54%   |
| 2.01-3.0   | 22        | 42     | 1.06%   |
| 10.01-20.0 | 3         | 7      | 0.14%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 685       | 31.61%  |
| 251-500        | 538       | 24.83%  |
| 501-1000       | 332       | 15.32%  |
| 51-100         | 187       | 8.63%   |
| 1001-2000      | 116       | 5.35%   |
| 21-50          | 107       | 4.94%   |
| More than 3000 | 84        | 3.88%   |
| 2001-3000      | 45        | 2.08%   |
| 1-20           | 44        | 2.03%   |
| Unknown        | 29        | 1.34%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 905       | 40.17%  |
| 21-50          | 614       | 27.25%  |
| 51-100         | 250       | 11.1%   |
| 101-250        | 191       | 8.48%   |
| 251-500        | 114       | 5.06%   |
| 501-1000       | 66        | 2.93%   |
| More than 3000 | 43        | 1.91%   |
| 1001-2000      | 30        | 1.33%   |
| Unknown        | 29        | 1.29%   |
| 2001-3000      | 11        | 0.49%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                         | Computers | Drives | Percent |
|-----------------------------------------------|-----------|--------|---------|
| Toshiba MQ02ABD100H 1TB                       | 2         | 2      | 3.92%   |
| Seagate ST9500420AS 500GB                     | 2         | 2      | 3.92%   |
| WDC WD5000LPVX-75V0TT0 500GB                  | 1         | 1      | 1.96%   |
| WDC WD3200AAKS-22B3A0 320GB                   | 1         | 1      | 1.96%   |
| WDC WD3200AAJS-00L7A0 320GB                   | 1         | 1      | 1.96%   |
| WDC WD30EFRX-68EUZN0 3TB                      | 1         | 1      | 1.96%   |
| WDC WD10SPZX-75Z10T2 1TB                      | 1         | 1      | 1.96%   |
| WDC WD10JPVX-22JC3T0 1TB                      | 1         | 1      | 1.96%   |
| WDC WD10JPVT-55A1YT0 1TB                      | 1         | 1      | 1.96%   |
| WDC WD10EZEX-21M2NA0 1TB                      | 1         | 2      | 1.96%   |
| WDC WD10EURX-63FH1Y0 1TB                      | 1         | 1      | 1.96%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD          | 1         | 1      | 1.96%   |
| Toshiba MQ01ABF050 500GB                      | 1         | 1      | 1.96%   |
| Toshiba MQ01ABD100 1TB                        | 1         | 1      | 1.96%   |
| Toshiba MQ01ABD075 752GB                      | 1         | 1      | 1.96%   |
| Toshiba MK8046GSX 80GB                        | 1         | 1      | 1.96%   |
| Toshiba MK3265GSX 320GB                       | 1         | 1      | 1.96%   |
| Toshiba MG03ACA200 2TB                        | 1         | 1      | 1.96%   |
| SK hynix BC711 HFM512GD3JX013N 512GB          | 1         | 1      | 1.96%   |
| Silicon Motion Inland NVMe SSD 256GB          | 1         | 1      | 1.96%   |
| Seagate ST9250315AS 250GB                     | 1         | 1      | 1.96%   |
| Seagate ST9200420ASG 200GB                    | 1         | 1      | 1.96%   |
| Seagate ST500LT012-9WS142 500GB               | 1         | 1      | 1.96%   |
| Seagate ST500LM000-SSHD-8GB                   | 1         | 1      | 1.96%   |
| Seagate ST500DM002-1BD142 500GB               | 1         | 1      | 1.96%   |
| Seagate ST4000DM004-2CV104 4TB                | 1         | 1      | 1.96%   |
| Seagate ST3500514NS 500GB                     | 1         | 1      | 1.96%   |
| Seagate ST3500413AS 500GB                     | 1         | 1      | 1.96%   |
| Seagate ST3320620AS 320GB                     | 1         | 1      | 1.96%   |
| Seagate ST3250318AS 250GB                     | 1         | 1      | 1.96%   |
| Seagate ST320LT012-1DG14C 320GB               | 1         | 1      | 1.96%   |
| Seagate ST2000LM003 HN-M201RAD 2TB            | 1         | 1      | 1.96%   |
| Seagate ST2000DM008-2FR102 2TB                | 1         | 1      | 1.96%   |
| Seagate ST2000DM001-9YN164 2TB                | 1         | 1      | 1.96%   |
| Seagate ST2000DL003-9VT166 2TB                | 1         | 1      | 1.96%   |
| Seagate ST1000LX015-1U7172 1TB                | 1         | 1      | 1.96%   |
| Seagate ST1000LM024 HN-M101MBB 1TB            | 1         | 1      | 1.96%   |
| Samsung Electronics MMCRE64G8MPP-0VA 64GB SSD | 1         | 1      | 1.96%   |
| OCZ VERTEX3 120GB SSD                         | 1         | 1      | 1.96%   |
| Kingston SUV400S37240G 240GB SSD              | 1         | 1      | 1.96%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 18        | 19     | 36%     |
| WDC                 | 9         | 10     | 18%     |
| Toshiba             | 9         | 9      | 18%     |
| Kingston            | 3         | 3      | 6%      |
| HGST                | 3         | 3      | 6%      |
| SK hynix            | 1         | 1      | 2%      |
| Silicon Motion      | 1         | 1      | 2%      |
| Samsung Electronics | 1         | 1      | 2%      |
| OCZ                 | 1         | 1      | 2%      |
| Intel               | 1         | 1      | 2%      |
| Hitachi             | 1         | 1      | 2%      |
| Hewlett-Packard     | 1         | 1      | 2%      |
| A-DATA Technology   | 1         | 1      | 2%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 18        | 19     | 46.15%  |
| WDC     | 9         | 10     | 23.08%  |
| Toshiba | 8         | 8      | 20.51%  |
| HGST    | 3         | 3      | 7.69%   |
| Hitachi | 1         | 1      | 2.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 38        | 41     | 77.55%  |
| SSD  | 8         | 8      | 16.33%  |
| NVMe | 3         | 3      | 6.12%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                          | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate ST2000LX001-1RG174 2TB | 1         | 1      | 50%     |
| SanDisk SSD i100 24GB          | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| SanDisk | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1878      | 3447   | 86.98%  |
| Works    | 231       | 405    | 10.7%   |
| Malfunc  | 48        | 52     | 2.22%   |
| Failed   | 2         | 2      | 0.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1451      | 58.3%   |
| AMD                              | 411       | 16.51%  |
| Samsung Electronics              | 178       | 7.15%   |
| SanDisk                          | 84        | 3.37%   |
| ASMedia Technology               | 37        | 1.49%   |
| Kingston Technology Company      | 34        | 1.37%   |
| SK hynix                         | 33        | 1.33%   |
| Phison Electronics               | 32        | 1.29%   |
| Nvidia                           | 32        | 1.29%   |
| Toshiba America Info Systems     | 23        | 0.92%   |
| JMicron Technology               | 22        | 0.88%   |
| Silicon Motion                   | 21        | 0.84%   |
| Micron Technology                | 18        | 0.72%   |
| Marvell Technology Group         | 18        | 0.72%   |
| KIOXIA                           | 17        | 0.68%   |
| Micron/Crucial Technology        | 12        | 0.48%   |
| ADATA Technology                 | 12        | 0.48%   |
| Silicon Image                    | 8         | 0.32%   |
| Realtek Semiconductor            | 8         | 0.32%   |
| VIA Technologies                 | 7         | 0.28%   |
| Lite-On Technology               | 5         | 0.2%    |
| Seagate Technology               | 4         | 0.16%   |
| Broadcom / LSI                   | 3         | 0.12%   |
| Yangtze Memory Technologies      | 2         | 0.08%   |
| Solid State Storage Technology   | 2         | 0.08%   |
| Silicon Integrated Systems [SiS] | 2         | 0.08%   |
| OCZ Technology Group             | 2         | 0.08%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.08%   |
| LSI Logic / Symbios Logic        | 2         | 0.08%   |
| Apple                            | 2         | 0.08%   |
| Unknown                          | 1         | 0.04%   |
| Union Memory (Shenzhen)          | 1         | 0.04%   |
| Lenovo                           | 1         | 0.04%   |
| Dell                             | 1         | 0.04%   |
| Adaptec                          | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 277       | 9.59%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 119       | 4.12%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 109       | 3.77%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 95        | 3.29%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 81        | 2.8%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 81        | 2.8%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 78        | 2.7%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 61        | 2.11%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 59        | 2.04%   |
| AMD 400 Series Chipset SATA Controller                                                  | 54        | 1.87%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 52        | 1.8%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 49        | 1.7%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 48        | 1.66%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 47        | 1.63%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 46        | 1.59%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 46        | 1.59%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 43        | 1.49%   |
| Intel SATA Controller [RAID mode]                                                       | 42        | 1.45%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 41        | 1.42%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 40        | 1.39%   |
| Samsung NVMe SSD Controller 980                                                         | 37        | 1.28%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 36        | 1.25%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 35        | 1.21%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 34        | 1.18%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 33        | 1.14%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 33        | 1.14%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 30        | 1.04%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 29        | 1%      |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 29        | 1%      |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 27        | 0.93%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 27        | 0.93%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 25        | 0.87%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 23        | 0.8%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 22        | 0.76%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 22        | 0.76%   |
| AMD 500 Series Chipset SATA Controller                                                  | 22        | 0.76%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 21        | 0.73%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 20        | 0.69%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 20        | 0.69%   |
| Micron Non-Volatile memory controller                                                   | 18        | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1580      | 61.45%  |
| NVMe | 489       | 19.02%  |
| IDE  | 302       | 11.75%  |
| RAID | 193       | 7.51%   |
| SAS  | 4         | 0.16%   |
| SCSI | 3         | 0.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 1637      | 77.69%  |
| AMD    | 470       | 22.31%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 33        | 1.57%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 25        | 1.19%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 20        | 0.95%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 18        | 0.85%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 18        | 0.85%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 17        | 0.81%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 17        | 0.81%   |
| AMD Ryzen 5 3600 6-Core Processor             | 17        | 0.81%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 15        | 0.71%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 14        | 0.66%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 14        | 0.66%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 13        | 0.62%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 12        | 0.57%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 12        | 0.57%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 12        | 0.57%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 11        | 0.52%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 11        | 0.52%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 11        | 0.52%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 11        | 0.52%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 11        | 0.52%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 11        | 0.52%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 11        | 0.52%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 11        | 0.52%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 11        | 0.52%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 10        | 0.47%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 10        | 0.47%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 10        | 0.47%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 10        | 0.47%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 10        | 0.47%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 10        | 0.47%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 10        | 0.47%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 10        | 0.47%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 10        | 0.47%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 10        | 0.47%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 10        | 0.47%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 9         | 0.43%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 9         | 0.43%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 9         | 0.43%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 9         | 0.43%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 9         | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 486       | 23.06%  |
| Intel Core i7           | 304       | 14.42%  |
| Intel Core i3           | 219       | 10.39%  |
| Intel Celeron           | 124       | 5.88%   |
| Intel Core 2 Duo        | 109       | 5.17%   |
| AMD Ryzen 5             | 108       | 5.12%   |
| Other                   | 95        | 4.51%   |
| Intel Pentium           | 69        | 3.27%   |
| Intel Atom              | 68        | 3.23%   |
| AMD Ryzen 7             | 66        | 3.13%   |
| Intel Xeon              | 44        | 2.09%   |
| AMD FX                  | 37        | 1.76%   |
| AMD A6                  | 35        | 1.66%   |
| Intel Pentium Dual-Core | 26        | 1.23%   |
| Intel Core 2 Quad       | 25        | 1.19%   |
| AMD A10                 | 23        | 1.09%   |
| AMD Ryzen 9             | 22        | 1.04%   |
| AMD Ryzen 3             | 20        | 0.95%   |
| Intel Pentium Dual      | 19        | 0.9%    |
| AMD A8                  | 19        | 0.9%    |
| AMD A4                  | 19        | 0.9%    |
| AMD E1                  | 12        | 0.57%   |
| Intel Core 2            | 11        | 0.52%   |
| Intel Core i9           | 10        | 0.47%   |
| AMD Phenom II X4        | 9         | 0.43%   |
| AMD Athlon II X2        | 9         | 0.43%   |
| Intel Pentium Silver    | 8         | 0.38%   |
| Intel Pentium Gold      | 7         | 0.33%   |
| AMD Phenom II X6        | 7         | 0.33%   |
| AMD E                   | 7         | 0.33%   |
| AMD Athlon II X4        | 7         | 0.33%   |
| AMD Athlon              | 7         | 0.33%   |
| AMD Athlon 64 X2        | 6         | 0.28%   |
| Intel Core M            | 5         | 0.24%   |
| AMD Turion 64 X2 Mobile | 5         | 0.24%   |
| Intel Pentium 4         | 4         | 0.19%   |
| Intel Core m5           | 4         | 0.19%   |
| AMD Ryzen 7 PRO         | 4         | 0.19%   |
| AMD PRO A10             | 3         | 0.14%   |
| AMD Athlon II X3        | 3         | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 993       | 47.11%  |
| 4      | 778       | 36.91%  |
| 6      | 158       | 7.5%    |
| 8      | 102       | 4.84%   |
| 1      | 27        | 1.28%   |
| 12     | 17        | 0.81%   |
| 3      | 14        | 0.66%   |
| 16     | 10        | 0.47%   |
| 10     | 7         | 0.33%   |
| 40     | 1         | 0.05%   |
| 14     | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 2098      | 99.57%  |
| 2      | 9         | 0.43%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 1259      | 59.75%  |
| 1      | 848       | 40.25%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2107      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306a9    | 176       | 8.24%   |
| 0x206a7    | 172       | 8.06%   |
| Unknown    | 156       | 7.31%   |
| 0x306c3    | 123       | 5.76%   |
| 0x1067a    | 103       | 4.82%   |
| 0x40651    | 68        | 3.19%   |
| 0x806c1    | 55        | 2.58%   |
| 0x20655    | 55        | 2.58%   |
| 0x406c4    | 50        | 2.34%   |
| 0x806e9    | 49        | 2.3%    |
| 0x406e3    | 45        | 2.11%   |
| 0x306d4    | 45        | 2.11%   |
| 0x30678    | 44        | 2.06%   |
| 0x906ea    | 42        | 1.97%   |
| 0x506e3    | 41        | 1.92%   |
| 0x806ea    | 38        | 1.78%   |
| 0x806ec    | 36        | 1.69%   |
| 0x08701021 | 35        | 1.64%   |
| 0x6fd      | 34        | 1.59%   |
| 0x906e9    | 31        | 1.45%   |
| 0x06000852 | 26        | 1.22%   |
| 0x706a8    | 25        | 1.17%   |
| 0x08108109 | 25        | 1.17%   |
| 0x6fb      | 24        | 1.12%   |
| 0x10676    | 24        | 1.12%   |
| 0x20652    | 23        | 1.08%   |
| 0x706e5    | 21        | 0.98%   |
| 0x506c9    | 20        | 0.94%   |
| 0x07030105 | 20        | 0.94%   |
| 0x06001119 | 19        | 0.89%   |
| 0x0a201016 | 18        | 0.84%   |
| 0x0700010f | 18        | 0.84%   |
| 0x406c3    | 17        | 0.8%    |
| 0x010000c8 | 17        | 0.8%    |
| 0x08108102 | 16        | 0.75%   |
| 0x0800820d | 16        | 0.75%   |
| 0x06006705 | 16        | 0.75%   |
| 0x08600106 | 15        | 0.7%    |
| 0xa0653    | 14        | 0.66%   |
| 0xa0652    | 13        | 0.61%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 249       | 11.82%  |
| Haswell          | 211       | 10.01%  |
| SandyBridge      | 188       | 8.92%   |
| IvyBridge        | 186       | 8.83%   |
| Penryn           | 131       | 6.22%   |
| Silvermont       | 119       | 5.65%   |
| Skylake          | 92        | 4.37%   |
| Westmere         | 83        | 3.94%   |
| Core             | 77        | 3.65%   |
| Zen 2            | 76        | 3.61%   |
| TigerLake        | 62        | 2.94%   |
| Zen+             | 61        | 2.9%    |
| Zen 3            | 50        | 2.37%   |
| Piledriver       | 49        | 2.33%   |
| Broadwell        | 48        | 2.28%   |
| K10              | 44        | 2.09%   |
| CometLake        | 42        | 1.99%   |
| Excavator        | 40        | 1.9%    |
| Icelake          | 39        | 1.85%   |
| Goldmont plus    | 35        | 1.66%   |
| Zen              | 29        | 1.38%   |
| Puma             | 29        | 1.38%   |
| Nehalem          | 24        | 1.14%   |
| Goldmont         | 22        | 1.04%   |
| Jaguar           | 21        | 1%      |
| Unknown          | 18        | 0.85%   |
| K8 Hammer        | 16        | 0.76%   |
| Steamroller      | 10        | 0.47%   |
| K10 Llano        | 9         | 0.43%   |
| Bobcat           | 9         | 0.43%   |
| Bulldozer        | 8         | 0.38%   |
| Bonnell          | 8         | 0.38%   |
| NetBurst         | 7         | 0.33%   |
| Alderlake Hybrid | 7         | 0.33%   |
| Tremont          | 4         | 0.19%   |
| K8 & K10 hybrid  | 4         | 0.19%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1265      | 52.4%   |
| Nvidia                           | 604       | 25.02%  |
| AMD                              | 537       | 22.25%  |
| VIA Technologies                 | 3         | 0.12%   |
| Silicon Integrated Systems [SiS] | 2         | 0.08%   |
| Matrox Electronics Systems       | 2         | 0.08%   |
| ASPEED Technology                | 1         | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 144       | 5.83%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 110       | 4.45%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 70        | 2.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 68        | 2.75%   |
| Intel Core Processor Integrated Graphics Controller                                      | 60        | 2.43%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 50        | 2.02%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 47        | 1.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 46        | 1.86%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 42        | 1.7%    |
| Intel HD Graphics 620                                                                    | 42        | 1.7%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 41        | 1.66%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 39        | 1.58%   |
| Intel UHD Graphics 620                                                                   | 37        | 1.5%    |
| Intel HD Graphics 5500                                                                   | 32        | 1.3%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 30        | 1.21%   |
| AMD Renoir                                                                               | 29        | 1.17%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 28        | 1.13%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 28        | 1.13%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 27        | 1.09%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 27        | 1.09%   |
| Intel HD Graphics 630                                                                    | 26        | 1.05%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 23        | 0.93%   |
| Intel HD Graphics 530                                                                    | 23        | 0.93%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 23        | 0.93%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 22        | 0.89%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 21        | 0.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 19        | 0.77%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 19        | 0.77%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 19        | 0.77%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 18        | 0.73%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 18        | 0.73%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 17        | 0.69%   |
| Intel HD Graphics 500                                                                    | 17        | 0.69%   |
| AMD Cezanne                                                                              | 17        | 0.69%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 16        | 0.65%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 16        | 0.65%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 16        | 0.65%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 15        | 0.61%   |
| AMD Lucienne                                                                             | 15        | 0.61%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 14        | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 994       | 46.98%  |
| 1 x AMD        | 439       | 20.75%  |
| 1 x Nvidia     | 384       | 18.15%  |
| Intel + Nvidia | 189       | 8.93%   |
| Intel + AMD    | 50        | 2.36%   |
| 2 x AMD        | 24        | 1.13%   |
| AMD + Nvidia   | 24        | 1.13%   |
| 2 x Nvidia     | 3         | 0.14%   |
| 1 x VIA        | 3         | 0.14%   |
| 1 x SiS        | 2         | 0.09%   |
| 1 x Matrox     | 2         | 0.09%   |
| 2 x Intel      | 1         | 0.05%   |
| 1 x ASPEED     | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1670      | 78.89%  |
| Proprietary | 376       | 17.76%  |
| Unknown     | 71        | 3.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1234      | 57.61%  |
| 0.01-0.5   | 247       | 11.53%  |
| 1.01-2.0   | 220       | 10.27%  |
| 0.51-1.0   | 188       | 8.78%   |
| 3.01-4.0   | 105       | 4.9%    |
| 7.01-8.0   | 69        | 3.22%   |
| 5.01-6.0   | 39        | 1.82%   |
| 8.01-16.0  | 23        | 1.07%   |
| 2.01-3.0   | 13        | 0.61%   |
| 16.01-24.0 | 4         | 0.19%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 287       | 13.29%  |
| AU Optronics            | 244       | 11.3%   |
| LG Display              | 201       | 9.31%   |
| Chimei Innolux          | 197       | 9.12%   |
| BOE                     | 160       | 7.41%   |
| Dell                    | 115       | 5.32%   |
| Goldstar                | 102       | 4.72%   |
| Hewlett-Packard         | 75        | 3.47%   |
| Acer                    | 57        | 2.64%   |
| Philips                 | 54        | 2.5%    |
| Apple                   | 53        | 2.45%   |
| AOC                     | 52        | 2.41%   |
| Chi Mei Optoelectronics | 41        | 1.9%    |
| BenQ                    | 40        | 1.85%   |
| Ancor Communications    | 38        | 1.76%   |
| Lenovo                  | 34        | 1.57%   |
| Sharp                   | 30        | 1.39%   |
| LG Electronics          | 22        | 1.02%   |
| PANDA                   | 19        | 0.88%   |
| Sony                    | 17        | 0.79%   |
| LG Philips              | 16        | 0.74%   |
| Unknown                 | 16        | 0.74%   |
| Vizio                   | 15        | 0.69%   |
| ViewSonic               | 15        | 0.69%   |
| Unknown                 | 15        | 0.69%   |
| Iiyama                  | 13        | 0.6%    |
| ASUSTek Computer        | 12        | 0.56%   |
| Sceptre Tech            | 11        | 0.51%   |
| InfoVision              | 10        | 0.46%   |
| HPN                     | 10        | 0.46%   |
| NEC Computers           | 9         | 0.42%   |
| Fujitsu Siemens         | 9         | 0.42%   |
| HannStar                | 7         | 0.32%   |
| CPT                     | 7         | 0.32%   |
| Toshiba                 | 6         | 0.28%   |
| Panasonic               | 6         | 0.28%   |
| LGD                     | 6         | 0.28%   |
| Eizo                    | 6         | 0.28%   |
| MSI                     | 5         | 0.23%   |
| Microstep               | 5         | 0.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                  | 16        | 0.72%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 15        | 0.68%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 12        | 0.54%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 11        | 0.5%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 10        | 0.45%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 10        | 0.45%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 9         | 0.41%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 9         | 0.41%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch                 | 9         | 0.41%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 9         | 0.41%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 8         | 0.36%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 8         | 0.36%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 7         | 0.32%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 7         | 0.32%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 6         | 0.27%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 6         | 0.27%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 6         | 0.27%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 6         | 0.27%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 6         | 0.27%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 6         | 0.27%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 6         | 0.27%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 309x174mm 14.0-inch     | 5         | 0.23%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 410x230mm 18.5-inch    | 5         | 0.23%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x173mm 12.3-inch             | 5         | 0.23%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 5         | 0.23%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch          | 5         | 0.23%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 5         | 0.23%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 5         | 0.23%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 5         | 0.23%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 5         | 0.23%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 5         | 0.23%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 5         | 0.23%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 5         | 0.23%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 5         | 0.23%   |
| AU Optronics LCD Monitor AUO105C 1366x768 256x144mm 11.6-inch            | 5         | 0.23%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 344x194mm 15.5-inch     | 4         | 0.18%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 4         | 0.18%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch    | 4         | 0.18%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 4         | 0.18%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 4         | 0.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 785       | 37.42%  |
| 1366x768 (WXGA)    | 550       | 26.22%  |
| 1600x900 (HD+)     | 115       | 5.48%   |
| 3840x2160 (4K)     | 111       | 5.29%   |
| 1280x800 (WXGA)    | 61        | 2.91%   |
| 1680x1050 (WSXGA+) | 60        | 2.86%   |
| 1280x1024 (SXGA)   | 53        | 2.53%   |
| 2560x1440 (QHD)    | 51        | 2.43%   |
| 1440x900 (WXGA+)   | 51        | 2.43%   |
| Unknown            | 47        | 2.24%   |
| 1920x1200 (WUXGA)  | 29        | 1.38%   |
| 1360x768           | 26        | 1.24%   |
| 3840x1080          | 17        | 0.81%   |
| 3440x1440          | 15        | 0.71%   |
| 2560x1600          | 13        | 0.62%   |
| 2560x1080          | 13        | 0.62%   |
| 1920x540           | 9         | 0.43%   |
| 2736x1824          | 8         | 0.38%   |
| 2256x1504          | 7         | 0.33%   |
| 3200x1800 (QHD+)   | 6         | 0.29%   |
| 2160x1440          | 6         | 0.29%   |
| 3840x2400          | 5         | 0.24%   |
| 2880x1800          | 4         | 0.19%   |
| 1024x768 (XGA)     | 4         | 0.19%   |
| 5760x1080          | 3         | 0.14%   |
| 4480x1440          | 3         | 0.14%   |
| 3840x1600          | 3         | 0.14%   |
| 1600x1200          | 3         | 0.14%   |
| 1280x720 (HD)      | 3         | 0.14%   |
| 1024x600           | 3         | 0.14%   |
| 5760x2160          | 2         | 0.1%    |
| 3600x1080          | 2         | 0.1%    |
| 3360x1080          | 2         | 0.1%    |
| 3200x1200          | 2         | 0.1%    |
| 3120x1050          | 2         | 0.1%    |
| 2944x1080          | 2         | 0.1%    |
| 1920x515           | 2         | 0.1%    |
| 1920x1280          | 2         | 0.1%    |
| 7680x2160          | 1         | 0.05%   |
| 6400x1440          | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 569       | 26.66%  |
| Unknown | 198       | 9.28%   |
| 13      | 187       | 8.76%   |
| 14      | 149       | 6.98%   |
| 17      | 131       | 6.14%   |
| 27      | 118       | 5.53%   |
| 24      | 109       | 5.11%   |
| 23      | 99        | 4.64%   |
| 21      | 94        | 4.4%    |
| 19      | 57        | 2.67%   |
| 31      | 48        | 2.25%   |
| 18      | 48        | 2.25%   |
| 11      | 48        | 2.25%   |
| 20      | 42        | 1.97%   |
| 22      | 40        | 1.87%   |
| 12      | 40        | 1.87%   |
| 34      | 23        | 1.08%   |
| 84      | 13        | 0.61%   |
| 54      | 13        | 0.61%   |
| 32      | 12        | 0.56%   |
| 40      | 11        | 0.52%   |
| 72      | 8         | 0.37%   |
| 26      | 8         | 0.37%   |
| 25      | 8         | 0.37%   |
| 16      | 8         | 0.37%   |
| 10      | 7         | 0.33%   |
| 52      | 4         | 0.19%   |
| 37      | 4         | 0.19%   |
| 36      | 4         | 0.19%   |
| 65      | 3         | 0.14%   |
| 49      | 3         | 0.14%   |
| 48      | 3         | 0.14%   |
| 33      | 3         | 0.14%   |
| 29      | 3         | 0.14%   |
| 74      | 2         | 0.09%   |
| 64      | 2         | 0.09%   |
| 42      | 2         | 0.09%   |
| 41      | 2         | 0.09%   |
| 35      | 2         | 0.09%   |
| 28      | 2         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 820       | 39.01%  |
| 501-600     | 304       | 14.46%  |
| 401-500     | 251       | 11.94%  |
| Unknown     | 198       | 9.42%   |
| 201-300     | 191       | 9.09%   |
| 351-400     | 150       | 7.14%   |
| 601-700     | 67        | 3.19%   |
| 701-800     | 42        | 2%      |
| 1001-1500   | 31        | 1.47%   |
| 1501-2000   | 25        | 1.19%   |
| 801-900     | 17        | 0.81%   |
| 901-1000    | 5         | 0.24%   |
| 101-200     | 1         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1458      | 73.86%  |
| 16/10   | 213       | 10.79%  |
| Unknown | 180       | 9.12%   |
| 5/4     | 48        | 2.43%   |
| 3/2     | 28        | 1.42%   |
| 21/9    | 28        | 1.42%   |
| 4/3     | 10        | 0.51%   |
| 32/9    | 4         | 0.2%    |
| 6/5     | 2         | 0.1%    |
| 3.73    | 2         | 0.1%    |
| 0.62    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 572       | 26.93%  |
| 201-250        | 276       | 12.99%  |
| 81-90          | 267       | 12.57%  |
| Unknown        | 198       | 9.32%   |
| 151-200        | 134       | 6.31%   |
| 301-350        | 120       | 5.65%   |
| 351-500        | 93        | 4.38%   |
| 121-130        | 91        | 4.28%   |
| 71-80          | 74        | 3.48%   |
| 141-150        | 67        | 3.15%   |
| More than 1000 | 54        | 2.54%   |
| 51-60          | 49        | 2.31%   |
| 251-300        | 43        | 2.02%   |
| 61-70          | 34        | 1.6%    |
| 501-1000       | 25        | 1.18%   |
| 131-140        | 13        | 0.61%   |
| 41-50          | 6         | 0.28%   |
| 111-120        | 5         | 0.24%   |
| 91-100         | 2         | 0.09%   |
| 1-40           | 1         | 0.05%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 629       | 30.39%  |
| 51-100        | 620       | 29.95%  |
| 121-160       | 443       | 21.4%   |
| Unknown       | 198       | 9.57%   |
| 161-240       | 91        | 4.4%    |
| 1-50          | 56        | 2.71%   |
| More than 240 | 33        | 1.59%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1790      | 83.76%  |
| 2     | 257       | 12.03%  |
| 0     | 70        | 3.28%   |
| 3     | 19        | 0.89%   |
| 4     | 1         | 0.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1152      | 35.62%  |
| Intel                             | 885       | 27.37%  |
| Qualcomm Atheros                  | 421       | 13.02%  |
| Broadcom                          | 238       | 7.36%   |
| Broadcom Limited                  | 64        | 1.98%   |
| Ralink Technology                 | 48        | 1.48%   |
| TP-Link                           | 46        | 1.42%   |
| Ralink                            | 44        | 1.36%   |
| Marvell Technology Group          | 36        | 1.11%   |
| Nvidia                            | 28        | 0.87%   |
| MediaTek                          | 23        | 0.71%   |
| Samsung Electronics               | 22        | 0.68%   |
| ASIX Electronics                  | 19        | 0.59%   |
| NetGear                           | 14        | 0.43%   |
| DisplayLink                       | 14        | 0.43%   |
| Xiaomi                            | 13        | 0.4%    |
| Dell                              | 12        | 0.37%   |
| Qualcomm Atheros Communications   | 11        | 0.34%   |
| Huawei Technologies               | 10        | 0.31%   |
| Microsoft                         | 9         | 0.28%   |
| Edimax Technology                 | 9         | 0.28%   |
| D-Link System                     | 9         | 0.28%   |
| D-Link                            | 7         | 0.22%   |
| Hewlett-Packard                   | 6         | 0.19%   |
| ASUSTek Computer                  | 6         | 0.19%   |
| Sierra Wireless                   | 5         | 0.15%   |
| Motorola PCS                      | 5         | 0.15%   |
| JMicron Technology                | 5         | 0.15%   |
| T & A Mobile Phones               | 4         | 0.12%   |
| Qualcomm                          | 4         | 0.12%   |
| OPPO Electronics                  | 4         | 0.12%   |
| Ericsson Business Mobile Networks | 4         | 0.12%   |
| Aquantia                          | 4         | 0.12%   |
| Linksys                           | 3         | 0.09%   |
| ZyDAS                             | 2         | 0.06%   |
| VIA Technologies                  | 2         | 0.06%   |
| U-Blox                            | 2         | 0.06%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.06%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.06%   |
| Lenovo                            | 2         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 726       | 19.3%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 187       | 4.97%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 113       | 3%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 84        | 2.23%   |
| Intel Wi-Fi 6 AX200                                               | 73        | 1.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 61        | 1.62%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 58        | 1.54%   |
| Intel Wireless 7260                                               | 49        | 1.3%    |
| Intel Wireless 7265                                               | 46        | 1.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 44        | 1.17%   |
| Intel Wireless 8265 / 8275                                        | 44        | 1.17%   |
| Broadcom BCM43142 802.11b/g/n                                     | 44        | 1.17%   |
| Intel Wi-Fi 6 AX201                                               | 41        | 1.09%   |
| Realtek RTL8125 2.5GbE Controller                                 | 40        | 1.06%   |
| Intel I211 Gigabit Network Connection                             | 40        | 1.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 39        | 1.04%   |
| Intel Ethernet Connection I217-LM                                 | 38        | 1.01%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 37        | 0.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 37        | 0.98%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 35        | 0.93%   |
| Intel Wireless 8260                                               | 33        | 0.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 32        | 0.85%   |
| Intel Wireless 3165                                               | 32        | 0.85%   |
| Realtek 802.11ac NIC                                              | 30        | 0.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 27        | 0.72%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 25        | 0.66%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 25        | 0.66%   |
| Intel Ethernet Connection (2) I219-V                              | 25        | 0.66%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 23        | 0.61%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 22        | 0.58%   |
| Ralink MT7601U Wireless Adapter                                   | 22        | 0.58%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 22        | 0.58%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 22        | 0.58%   |
| Intel Ethernet Controller I225-V                                  | 21        | 0.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 20        | 0.53%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 19        | 0.51%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 19        | 0.51%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 18        | 0.48%   |
| Intel WiFi Link 5100                                              | 17        | 0.45%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 16        | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 653       | 36.64%  |
| Realtek Semiconductor                 | 332       | 18.63%  |
| Qualcomm Atheros                      | 331       | 18.57%  |
| Broadcom                              | 172       | 9.65%   |
| Ralink Technology                     | 48        | 2.69%   |
| Ralink                                | 44        | 2.47%   |
| Broadcom Limited                      | 41        | 2.3%    |
| TP-Link                               | 39        | 2.19%   |
| MediaTek                              | 19        | 1.07%   |
| NetGear                               | 14        | 0.79%   |
| Qualcomm Atheros Communications       | 11        | 0.62%   |
| Marvell Technology Group              | 9         | 0.51%   |
| Edimax Technology                     | 9         | 0.51%   |
| Microsoft                             | 8         | 0.45%   |
| D-Link System                         | 7         | 0.39%   |
| D-Link                                | 7         | 0.39%   |
| Dell                                  | 6         | 0.34%   |
| Sierra Wireless                       | 5         | 0.28%   |
| ASUSTek Computer                      | 5         | 0.28%   |
| Linksys                               | 3         | 0.17%   |
| ZyDAS                                 | 2         | 0.11%   |
| Gemtek                                | 2         | 0.11%   |
| Fibocom                               | 2         | 0.11%   |
| Belkin Components                     | 2         | 0.11%   |
| AVM                                   | 2         | 0.11%   |
| ZyXEL Communications                  | 1         | 0.06%   |
| Xiaomi                                | 1         | 0.06%   |
| TRENDnet                              | 1         | 0.06%   |
| Samsung Electronics                   | 1         | 0.06%   |
| Qualcomm                              | 1         | 0.06%   |
| Panasonic (Matsushita)                | 1         | 0.06%   |
| Hewlett-Packard                       | 1         | 0.06%   |
| ADMtek                                | 1         | 0.06%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 84        | 4.67%   |
| Intel Wi-Fi 6 AX200                                            | 73        | 4.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 61        | 3.39%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 58        | 3.22%   |
| Intel Wireless 7260                                            | 49        | 2.72%   |
| Intel Wireless 7265                                            | 46        | 2.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 44        | 2.45%   |
| Intel Wireless 8265 / 8275                                     | 44        | 2.45%   |
| Broadcom BCM43142 802.11b/g/n                                  | 44        | 2.45%   |
| Intel Wi-Fi 6 AX201                                            | 41        | 2.28%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 39        | 2.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 37        | 2.06%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 35        | 1.95%   |
| Intel Wireless 8260                                            | 33        | 1.83%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 32        | 1.78%   |
| Intel Wireless 3165                                            | 32        | 1.78%   |
| Realtek 802.11ac NIC                                           | 30        | 1.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 27        | 1.5%    |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 25        | 1.39%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 25        | 1.39%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 23        | 1.28%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 22        | 1.22%   |
| Ralink MT7601U Wireless Adapter                                | 22        | 1.22%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 22        | 1.22%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 20        | 1.11%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 19        | 1.06%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 18        | 1%      |
| Intel WiFi Link 5100                                           | 17        | 0.94%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 16        | 0.89%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 15        | 0.83%   |
| Intel Wireless-AC 9260                                         | 15        | 0.83%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 14        | 0.78%   |
| Intel Centrino Ultimate-N 6300                                 | 14        | 0.78%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 14        | 0.78%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 13        | 0.72%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 12        | 0.67%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 12        | 0.67%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 12        | 0.67%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 12        | 0.67%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 12        | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1009      | 53.33%  |
| Intel                             | 457       | 24.15%  |
| Qualcomm Atheros                  | 125       | 6.61%   |
| Broadcom                          | 96        | 5.07%   |
| Nvidia                            | 28        | 1.48%   |
| Marvell Technology Group          | 27        | 1.43%   |
| Broadcom Limited                  | 25        | 1.32%   |
| Samsung Electronics               | 21        | 1.11%   |
| ASIX Electronics                  | 19        | 1%      |
| DisplayLink                       | 14        | 0.74%   |
| Xiaomi                            | 12        | 0.63%   |
| TP-Link                           | 7         | 0.37%   |
| Huawei Technologies               | 7         | 0.37%   |
| JMicron Technology                | 5         | 0.26%   |
| OPPO Electronics                  | 4         | 0.21%   |
| MediaTek                          | 4         | 0.21%   |
| Aquantia                          | 4         | 0.21%   |
| Qualcomm                          | 3         | 0.16%   |
| Motorola PCS                      | 3         | 0.16%   |
| Hewlett-Packard                   | 3         | 0.16%   |
| VIA Technologies                  | 2         | 0.11%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.11%   |
| HMD Global                        | 2         | 0.11%   |
| Google                            | 2         | 0.11%   |
| D-Link System                     | 2         | 0.11%   |
| Sundance Technology Inc / IC Plus | 1         | 0.05%   |
| Sun Microsystems                  | 1         | 0.05%   |
| Research In Motion                | 1         | 0.05%   |
| OnePlus                           | 1         | 0.05%   |
| Novatel Wireless                  | 1         | 0.05%   |
| Motorola BCS                      | 1         | 0.05%   |
| Lenovo                            | 1         | 0.05%   |
| ICS Advent                        | 1         | 0.05%   |
| ASUSTek Computer                  | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 726       | 37.79%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 187       | 9.73%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 113       | 5.88%   |
| Realtek RTL8125 2.5GbE Controller                                 | 40        | 2.08%   |
| Intel I211 Gigabit Network Connection                             | 40        | 2.08%   |
| Intel Ethernet Connection I217-LM                                 | 38        | 1.98%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 37        | 1.93%   |
| Intel Ethernet Connection (2) I219-V                              | 25        | 1.3%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 22        | 1.15%   |
| Intel Ethernet Controller I225-V                                  | 21        | 1.09%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 19        | 0.99%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 15        | 0.78%   |
| Intel Ethernet Connection I217-V                                  | 15        | 0.78%   |
| Intel 82577LM Gigabit Network Connection                          | 15        | 0.78%   |
| ASIX AX88179 Gigabit Ethernet                                     | 15        | 0.78%   |
| Intel Ethernet Connection I219-LM                                 | 14        | 0.73%   |
| Intel Ethernet Connection I218-LM                                 | 14        | 0.73%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 14        | 0.73%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 13        | 0.68%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 12        | 0.62%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 12        | 0.62%   |
| Intel Ethernet Connection (7) I219-V                              | 12        | 0.62%   |
| Intel 82567LM Gigabit Network Connection                          | 12        | 0.62%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 11        | 0.57%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 11        | 0.57%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 11        | 0.57%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 11        | 0.57%   |
| Nvidia MCP79 Ethernet                                             | 10        | 0.52%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 10        | 0.52%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 9         | 0.47%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 9         | 0.47%   |
| Intel Ethernet Connection (2) I219-LM                             | 9         | 0.47%   |
| Intel Ethernet Connection (2) I218-V                              | 9         | 0.47%   |
| Intel 82579V Gigabit Network Connection                           | 9         | 0.47%   |
| Nvidia MCP61 Ethernet                                             | 8         | 0.42%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 8         | 0.42%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 8         | 0.42%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 7         | 0.36%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 7         | 0.36%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 7         | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1783      | 51.18%  |
| WiFi     | 1661      | 47.68%  |
| Modem    | 29        | 0.83%   |
| Unknown  | 11        | 0.32%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1306      | 59.58%  |
| Ethernet | 882       | 40.24%  |
| Modem    | 2         | 0.09%   |
| Unknown  | 2         | 0.09%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1162      | 55.02%  |
| 1     | 836       | 39.58%  |
| 0     | 72        | 3.41%   |
| 3     | 37        | 1.75%   |
| 5     | 3         | 0.14%   |
| 7     | 1         | 0.05%   |
| 4     | 1         | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1475      | 69.09%  |
| Yes  | 660       | 30.91%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 489       | 39%     |
| Realtek Semiconductor           | 151       | 12.04%  |
| Qualcomm Atheros Communications | 127       | 10.13%  |
| Broadcom                        | 80        | 6.38%   |
| Cambridge Silicon Radio         | 77        | 6.14%   |
| IMC Networks                    | 64        | 5.1%    |
| Apple                           | 59        | 4.7%    |
| Lite-On Technology              | 38        | 3.03%   |
| Foxconn / Hon Hai               | 29        | 2.31%   |
| Dell                            | 25        | 1.99%   |
| ASUSTek Computer                | 25        | 1.99%   |
| Hewlett-Packard                 | 19        | 1.52%   |
| Toshiba                         | 17        | 1.36%   |
| Ralink                          | 11        | 0.88%   |
| Marvell Semiconductor           | 8         | 0.64%   |
| Foxconn International           | 5         | 0.4%    |
| Realtek                         | 4         | 0.32%   |
| MediaTek                        | 4         | 0.32%   |
| Integrated System Solution      | 4         | 0.32%   |
| Dynex                           | 3         | 0.24%   |
| Alps Electric                   | 3         | 0.24%   |
| TP-Link                         | 2         | 0.16%   |
| Askey Computer                  | 2         | 0.16%   |
| Sitecom Europe                  | 1         | 0.08%   |
| National Semiconductor          | 1         | 0.08%   |
| Micro Star International        | 1         | 0.08%   |
| Edimax Technology               | 1         | 0.08%   |
| D-Link System                   | 1         | 0.08%   |
| Chicony Electronics             | 1         | 0.08%   |
| Belkin Components               | 1         | 0.08%   |
| Unknown                         | 1         | 0.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 208       | 16.59%  |
| Realtek Bluetooth Radio                             | 102       | 8.13%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 77        | 6.14%   |
| Intel AX201 Bluetooth                               | 69        | 5.5%    |
| Intel AX200 Bluetooth                               | 63        | 5.02%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 60        | 4.78%   |
| Qualcomm Atheros  Bluetooth Device                  | 55        | 4.39%   |
| Realtek  Bluetooth 4.2 Adapter                      | 33        | 2.63%   |
| IMC Networks Bluetooth Device                       | 27        | 2.15%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 23        | 1.83%   |
| Intel AX210 Bluetooth                               | 23        | 1.83%   |
| Apple Bluetooth Host Controller                     | 22        | 1.75%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 19        | 1.52%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 19        | 1.52%   |
| Intel Wireless-AC 3168 Bluetooth                    | 18        | 1.44%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 17        | 1.36%   |
| IMC Networks Bluetooth Radio                        | 17        | 1.36%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 16        | 1.28%   |
| Apple Bluetooth USB Host Controller                 | 16        | 1.28%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 15        | 1.2%    |
| Lite-On Atheros AR3012 Bluetooth                    | 14        | 1.12%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 13        | 1.04%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 12        | 0.96%   |
| Ralink RT3290 Bluetooth                             | 11        | 0.88%   |
| HP Broadcom 2070 Bluetooth Combo                    | 11        | 0.88%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 10        | 0.8%    |
| Foxconn / Hon Hai Bluetooth Device                  | 10        | 0.8%    |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 10        | 0.8%    |
| Broadcom BCM2045B (BDC-2.1)                         | 9         | 0.72%   |
| Marvell Bluetooth and Wireless LAN Composite        | 8         | 0.64%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 8         | 0.64%   |
| IMC Networks Wireless_Device                        | 8         | 0.64%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 8         | 0.64%   |
| Dell DW375 Bluetooth Module                         | 8         | 0.64%   |
| Apple Bluetooth HCI                                 | 8         | 0.64%   |
| Lite-On Bluetooth Device                            | 7         | 0.56%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 7         | 0.56%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 7         | 0.56%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 7         | 0.56%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 7         | 0.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1546      | 54.75%  |
| AMD                                  | 591       | 20.93%  |
| Nvidia                               | 478       | 16.93%  |
| C-Media Electronics                  | 33        | 1.17%   |
| Creative Labs                        | 15        | 0.53%   |
| Texas Instruments                    | 12        | 0.42%   |
| Logitech                             | 11        | 0.39%   |
| Kingston Technology                  | 9         | 0.32%   |
| JMTek                                | 9         | 0.32%   |
| Realtek Semiconductor                | 8         | 0.28%   |
| Razer USA                            | 7         | 0.25%   |
| GN Netcom                            | 7         | 0.25%   |
| VIA Technologies                     | 6         | 0.21%   |
| SteelSeries ApS                      | 6         | 0.21%   |
| Plantronics                          | 6         | 0.21%   |
| ASUSTek Computer                     | 6         | 0.21%   |
| Generalplus Technology               | 5         | 0.18%   |
| Creative Technology                  | 4         | 0.14%   |
| Focusrite-Novation                   | 3         | 0.11%   |
| DSEA A/S                             | 3         | 0.11%   |
| Corsair                              | 3         | 0.11%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.07%   |
| Tenx Technology                      | 2         | 0.07%   |
| Silicon Integrated Systems [SiS]     | 2         | 0.07%   |
| Samsung Electronics                  | 2         | 0.07%   |
| RODE Microphones                     | 2         | 0.07%   |
| Numark                               | 2         | 0.07%   |
| Micro Star International             | 2         | 0.07%   |
| Lenovo                               | 2         | 0.07%   |
| XMOS                                 | 1         | 0.04%   |
| Valve Software                       | 1         | 0.04%   |
| Swissonic                            | 1         | 0.04%   |
| Sony                                 | 1         | 0.04%   |
| Silicon Labs                         | 1         | 0.04%   |
| Sennheiser Communications            | 1         | 0.04%   |
| SAVITECH                             | 1         | 0.04%   |
| Roland                               | 1         | 0.04%   |
| ROCCAT                               | 1         | 0.04%   |
| Qualcomm                             | 1         | 0.04%   |
| PreSonus Audio Electronics           | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 191       | 5.72%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 175       | 5.24%   |
| Intel Sunrise Point-LP HD Audio                                            | 142       | 4.25%   |
| AMD Family 17h/19h HD Audio Controller                                     | 123       | 3.68%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 119       | 3.56%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 94        | 2.81%   |
| AMD FCH Azalia Controller                                                  | 93        | 2.78%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 84        | 2.51%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 79        | 2.37%   |
| AMD Starship/Matisse HD Audio Controller                                   | 74        | 2.22%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 73        | 2.19%   |
| Intel 8 Series HD Audio Controller                                         | 71        | 2.13%   |
| Intel Haswell-ULT HD Audio Controller                                      | 67        | 2.01%   |
| Intel Cannon Lake PCH cAVS                                                 | 65        | 1.95%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 62        | 1.86%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 60        | 1.8%    |
| AMD Kabini HDMI/DP Audio                                                   | 58        | 1.74%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 55        | 1.65%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 53        | 1.59%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 46        | 1.38%   |
| Intel Broadwell-U Audio Controller                                         | 46        | 1.38%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 45        | 1.35%   |
| Nvidia GF108 High Definition Audio Controller                              | 41        | 1.23%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 40        | 1.2%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 38        | 1.14%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 37        | 1.11%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 36        | 1.08%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 35        | 1.05%   |
| Nvidia GP107GL High Definition Audio Controller                            | 30        | 0.9%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 28        | 0.84%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 28        | 0.84%   |
| Nvidia TU116 High Definition Audio Controller                              | 27        | 0.81%   |
| AMD High Definition Audio Controller                                       | 27        | 0.81%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 27        | 0.81%   |
| Intel 200 Series PCH HD Audio                                              | 26        | 0.78%   |
| Nvidia TU106 High Definition Audio Controller                              | 24        | 0.72%   |
| Nvidia High Definition Audio Controller                                    | 24        | 0.72%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 24        | 0.72%   |
| Nvidia GF119 HDMI Audio Controller                                         | 24        | 0.72%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 24        | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 110       | 25.35%  |
| SK hynix            | 79        | 18.2%   |
| Micron Technology   | 47        | 10.83%  |
| Kingston            | 36        | 8.29%   |
| Unknown             | 34        | 7.83%   |
| Crucial             | 23        | 5.3%    |
| G.Skill             | 16        | 3.69%   |
| Corsair             | 14        | 3.23%   |
| Unknown (ABCD)      | 13        | 3%      |
| A-DATA Technology   | 11        | 2.53%   |
| Team                | 6         | 1.38%   |
| Ramaxel Technology  | 6         | 1.38%   |
| Nanya Technology    | 6         | 1.38%   |
| Elpida              | 5         | 1.15%   |
| Patriot             | 4         | 0.92%   |
| Timetec             | 2         | 0.46%   |
| Qimonda             | 2         | 0.46%   |
| Avant               | 2         | 0.46%   |
| Unknown             | 2         | 0.46%   |
| Wilk                | 1         | 0.23%   |
| Unknown (08B5)      | 1         | 0.23%   |
| Unifosa             | 1         | 0.23%   |
| Transcend           | 1         | 0.23%   |
| Teikon              | 1         | 0.23%   |
| Strontium           | 1         | 0.23%   |
| Smart               | 1         | 0.23%   |
| PUSKILL             | 1         | 0.23%   |
| Netlist             | 1         | 0.23%   |
| Kingmax             | 1         | 0.23%   |
| GSkill              | 1         | 0.23%   |
| Goldkey             | 1         | 0.23%   |
| F7852C80            | 1         | 0.23%   |
| Essencore           | 1         | 0.23%   |
| CSX                 | 1         | 0.23%   |
| Axiom               | 1         | 0.23%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s    | 11        | 2.41%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 8         | 1.75%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 6         | 1.31%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 4         | 0.88%   |
| Samsung RAM UBE3D4AA-MGCR 8GB Row Of Chips LPDDR4 4267MT/s          | 4         | 0.88%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 4         | 0.88%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 4         | 0.88%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 4         | 0.88%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 3         | 0.66%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 3         | 0.66%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 3         | 0.66%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 3         | 0.66%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 3         | 0.66%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s         | 3         | 0.66%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 3         | 0.66%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 3         | 0.66%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 3         | 0.66%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s          | 3         | 0.66%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s              | 3         | 0.66%   |
| Elpida RAM EBJ21UE8BDS0-DJ-F 2GB SODIMM DDR3 1334MT/s               | 3         | 0.66%   |
| Unknown RAM Module 4GB SODIMM DDR3                                  | 2         | 0.44%   |
| Unknown RAM Module 4096MB SODIMM DDR3                               | 2         | 0.44%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                        | 2         | 0.44%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                      | 2         | 0.44%   |
| Unknown (ABCD) RAM 123456789012345678 8GB DIMM DDR4 2400MT/s        | 2         | 0.44%   |
| Team RAM TEAMGROUP-UD4-2666 16384MB DIMM DDR4 3000MT/s              | 2         | 0.44%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2400MT/s                     | 2         | 0.44%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s                | 2         | 0.44%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 2         | 0.44%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.44%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s              | 2         | 0.44%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s             | 2         | 0.44%   |
| SK hynix RAM HMT351U6CFR8C-H9 4096MB DIMM DDR3 1600MT/s             | 2         | 0.44%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.44%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.44%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 2         | 0.44%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 2         | 0.44%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s           | 2         | 0.44%   |
| SK hynix RAM HCNNNCPMBLHR-NEE 2GB Row Of Chips LPDDR4 4267MT/s      | 2         | 0.44%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 2         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 160       | 43.24%  |
| DDR3    | 137       | 37.03%  |
| LPDDR4  | 26        | 7.03%   |
| DDR2    | 15        | 4.05%   |
| LPDDR3  | 14        | 3.78%   |
| SDRAM   | 9         | 2.43%   |
| Unknown | 7         | 1.89%   |
| DDR     | 2         | 0.54%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 222       | 60.33%  |
| DIMM         | 104       | 28.26%  |
| Row Of Chips | 38        | 10.33%  |
| Chip         | 2         | 0.54%   |
| FB-DIMM      | 1         | 0.27%   |
| Unknown      | 1         | 0.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 149       | 36.43%  |
| 8192  | 148       | 36.19%  |
| 2048  | 53        | 12.96%  |
| 16384 | 41        | 10.02%  |
| 1024  | 10        | 2.44%   |
| 32768 | 8         | 1.96%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 88        | 21.62%  |
| 3200    | 60        | 14.74%  |
| 2667    | 57        | 14%     |
| 2400    | 35        | 8.6%    |
| 1333    | 31        | 7.62%   |
| 2133    | 16        | 3.93%   |
| 1334    | 15        | 3.69%   |
| 3600    | 10        | 2.46%   |
| 1867    | 10        | 2.46%   |
| 4267    | 9         | 2.21%   |
| 3266    | 8         | 1.97%   |
| 667     | 8         | 1.97%   |
| 1066    | 7         | 1.72%   |
| 800     | 7         | 1.72%   |
| Unknown | 5         | 1.23%   |
| 1866    | 4         | 0.98%   |
| 1800    | 4         | 0.98%   |
| 8400    | 3         | 0.74%   |
| 3000    | 3         | 0.74%   |
| 2048    | 3         | 0.74%   |
| 4199    | 2         | 0.49%   |
| 3866    | 2         | 0.49%   |
| 3466    | 2         | 0.49%   |
| 3333    | 2         | 0.49%   |
| 2666    | 2         | 0.49%   |
| 975     | 2         | 0.49%   |
| 4266    | 1         | 0.25%   |
| 4000    | 1         | 0.25%   |
| 3800    | 1         | 0.25%   |
| 3666    | 1         | 0.25%   |
| 2933    | 1         | 0.25%   |
| 2800    | 1         | 0.25%   |
| 2200    | 1         | 0.25%   |
| 1400    | 1         | 0.25%   |
| 1067    | 1         | 0.25%   |
| 976     | 1         | 0.25%   |
| 400     | 1         | 0.25%   |
| 333     | 1         | 0.25%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 14        | 29.79%  |
| Canon                 | 10        | 21.28%  |
| Samsung Electronics   | 7         | 14.89%  |
| Brother Industries    | 7         | 14.89%  |
| Seiko Epson           | 6         | 12.77%  |
| Zebra                 | 1         | 2.13%   |
| QinHeng Electronics   | 1         | 2.13%   |
| Lexmark International | 1         | 2.13%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Seiko Epson L3110 Series             | 3         | 6.38%   |
| HP ENVY Photo 6200 series            | 2         | 4.26%   |
| Canon TS3100 series                  | 2         | 4.26%   |
| Zebra ZP 450 Printer                 | 1         | 2.13%   |
| Seiko Epson XP-7100 Series           | 1         | 2.13%   |
| Seiko Epson XP-202 203 206 Series    | 1         | 2.13%   |
| Seiko Epson ET-2820 Series           | 1         | 2.13%   |
| Samsung SCX-483x 5x3x Series         | 1         | 2.13%   |
| Samsung SCX-4200 series              | 1         | 2.13%   |
| Samsung SCX-3400 Series              | 1         | 2.13%   |
| Samsung ML-2950 Series               | 1         | 2.13%   |
| Samsung ML-216x Series Laser Printer | 1         | 2.13%   |
| Samsung M2020 Series                 | 1         | 2.13%   |
| Samsung C460 Series                  | 1         | 2.13%   |
| QinHeng CH340S                       | 1         | 2.13%   |
| Lexmark International 2400 series    | 1         | 2.13%   |
| HP Smart Tank 510 series             | 1         | 2.13%   |
| HP PSC 1100 series                   | 1         | 2.13%   |
| HP OfficeJet Pro 9010 series         | 1         | 2.13%   |
| HP Officejet 6600                    | 1         | 2.13%   |
| HP OfficeJet 4650 series             | 1         | 2.13%   |
| HP LaserJet Professional P1102w      | 1         | 2.13%   |
| HP LaserJet 1200                     | 1         | 2.13%   |
| HP LaserJet 1000                     | 1         | 2.13%   |
| HP ENVY 4520 series                  | 1         | 2.13%   |
| HP DeskJet 2700 series               | 1         | 2.13%   |
| HP DeskJet 2300 series               | 1         | 2.13%   |
| HP DeskJet 1110 series               | 1         | 2.13%   |
| Canon TR4500 series                  | 1         | 2.13%   |
| Canon PIXMA MX320 series             | 1         | 2.13%   |
| Canon PIXMA MG3000 series            | 1         | 2.13%   |
| Canon PIXMA MG2500 Series            | 1         | 2.13%   |
| Canon LiDE 400                       | 1         | 2.13%   |
| Canon iP4200                         | 1         | 2.13%   |
| Canon G3010 series                   | 1         | 2.13%   |
| Canon E410 series                    | 1         | 2.13%   |
| Brother QL-500 label printer         | 1         | 2.13%   |
| Brother MFC-J1010DW                  | 1         | 2.13%   |
| Brother MFC-9140CDN                  | 1         | 2.13%   |
| Brother MFC-1810                     | 1         | 2.13%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 7         | 63.64%  |
| Seiko Epson     | 2         | 18.18%  |
| Hewlett-Packard | 2         | 18.18%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X750 [Perfection 4490 Photo] | 2         | 18.18%  |
| HP ScanJet 2400c                            | 1         | 9.09%   |
| HP PSC 1200                                 | 1         | 9.09%   |
| Canon CanoScan LiDE 90                      | 1         | 9.09%   |
| Canon CanoScan LiDE 60                      | 1         | 9.09%   |
| Canon CanoScan LIDE 25                      | 1         | 9.09%   |
| Canon CanoScan LiDE 110                     | 1         | 9.09%   |
| Canon CanoScan LiDE 100                     | 1         | 9.09%   |
| Canon CanoScan D660U                        | 1         | 9.09%   |
| Canon CanoScan 8800F                        | 1         | 9.09%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 271       | 22.01%  |
| Realtek Semiconductor                  | 108       | 8.77%   |
| Microdia                               | 108       | 8.77%   |
| IMC Networks                           | 94        | 7.64%   |
| Sunplus Innovation Technology          | 70        | 5.69%   |
| Acer                                   | 70        | 5.69%   |
| Cheng Uei Precision Industry (Foxlink) | 59        | 4.79%   |
| Apple                                  | 56        | 4.55%   |
| Quanta                                 | 47        | 3.82%   |
| Logitech                               | 46        | 3.74%   |
| Suyin                                  | 44        | 3.57%   |
| Syntek                                 | 30        | 2.44%   |
| Silicon Motion                         | 20        | 1.62%   |
| Lite-On Technology                     | 19        | 1.54%   |
| Alcor Micro                            | 18        | 1.46%   |
| Ricoh                                  | 16        | 1.3%    |
| Samsung Electronics                    | 13        | 1.06%   |
| Luxvisions Innotech Limited            | 13        | 1.06%   |
| Primax Electronics                     | 10        | 0.81%   |
| Microsoft                              | 10        | 0.81%   |
| ARC International                      | 9         | 0.73%   |
| icSpring                               | 8         | 0.65%   |
| Generalplus Technology                 | 7         | 0.57%   |
| Unknown                                | 6         | 0.49%   |
| Sonix Technology                       | 6         | 0.49%   |
| ALi                                    | 6         | 0.49%   |
| Lenovo                                 | 5         | 0.41%   |
| Importek                               | 5         | 0.41%   |
| Sunplus Technology                     | 4         | 0.32%   |
| GEMBIRD                                | 4         | 0.32%   |
| SunplusIT                              | 3         | 0.24%   |
| Razer USA                              | 3         | 0.24%   |
| Jieli Technology                       | 3         | 0.24%   |
| Huawei Technologies                    | 3         | 0.24%   |
| Genesys Logic                          | 3         | 0.24%   |
| Z-Star Microelectronics                | 2         | 0.16%   |
| Xiongmai                               | 2         | 0.16%   |
| Pixart Imaging                         | 2         | 0.16%   |
| OmniVision Technologies                | 2         | 0.16%   |
| Guillemot                              | 2         | 0.16%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 37        | 2.99%   |
| Microdia Integrated_Webcam_HD                                   | 26        | 2.1%    |
| IMC Networks USB2.0 HD UVC WebCam                               | 24        | 1.94%   |
| Realtek Integrated_Webcam_HD                                    | 23        | 1.86%   |
| Chicony HD Webcam                                               | 22        | 1.78%   |
| Chicony HP Truevision HD                                        | 20        | 1.62%   |
| Apple FaceTime HD Camera (Built-in)                             | 20        | 1.62%   |
| Acer Integrated Camera                                          | 20        | 1.62%   |
| Microdia Integrated Webcam                                      | 18        | 1.46%   |
| Syntek Integrated Camera                                        | 16        | 1.29%   |
| Chicony TOSHIBA Web Camera - HD                                 | 16        | 1.29%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 15        | 1.21%   |
| Apple iPhone 5/5C/5S/6/SE                                       | 14        | 1.13%   |
| Samsung Galaxy series, misc. (MTP mode)                         | 13        | 1.05%   |
| IMC Networks Integrated Camera                                  | 13        | 1.05%   |
| Acer Lenovo EasyCamera                                          | 13        | 1.05%   |
| Realtek USB Camera                                              | 12        | 0.97%   |
| Logitech Webcam C270                                            | 12        | 0.97%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                | 12        | 0.97%   |
| Apple Built-in iSight                                           | 11        | 0.89%   |
| Sunplus Integrated_Webcam_HD                                    | 10        | 0.81%   |
| Sunplus HD WebCam                                               | 10        | 0.81%   |
| Chicony USB2.0 VGA UVC WebCam                                   | 10        | 0.81%   |
| Chicony HP TrueVision HD Camera                                 | 10        | 0.81%   |
| Microdia Webcam Vitade AF                                       | 9         | 0.73%   |
| Chicony Lenovo EasyCamera                                       | 9         | 0.73%   |
| Chicony HP HD Webcam                                            | 9         | 0.73%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 9         | 0.73%   |
| ARC International Camera                                        | 9         | 0.73%   |
| Apple FaceTime HD Camera                                        | 9         | 0.73%   |
| Alcor Micro USB 2.0 WebCamera                                   | 9         | 0.73%   |
| Realtek Integrated Webcam HD                                    | 8         | 0.65%   |
| Realtek Integrated Webcam                                       | 8         | 0.65%   |
| Realtek HP Truevision HD                                        | 8         | 0.65%   |
| Quanta HP Wide Vision HD Camera                                 | 8         | 0.65%   |
| Quanta HP TrueVision HD Camera                                  | 8         | 0.65%   |
| icSpring camera                                                 | 8         | 0.65%   |
| Chicony USB2.0 HD UVC WebCam                                    | 8         | 0.65%   |
| Chicony USB 2.0 Camera                                          | 8         | 0.65%   |
| Chicony HP Wide Vision HD Camera                                | 8         | 0.65%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 77        | 40.96%  |
| Synaptics                  | 24        | 12.77%  |
| Shenzhen Goodix Technology | 23        | 12.23%  |
| AuthenTec                  | 20        | 10.64%  |
| Upek                       | 19        | 10.11%  |
| Elan Microelectronics      | 11        | 5.85%   |
| LighTuning Technology      | 6         | 3.19%   |
| STMicroelectronics         | 5         | 2.66%   |
| Samsung Electronics        | 2         | 1.06%   |
| Focal-systems.Corp         | 1         | 0.53%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 18        | 9.57%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 16        | 8.51%   |
| Shenzhen Goodix  Fingerprint Device                                        | 13        | 6.91%   |
| Unknown                                                                    | 12        | 6.38%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 9         | 4.79%   |
| AuthenTec AES2810                                                          | 9         | 4.79%   |
| Shenzhen Goodix Fingerprint Reader                                         | 8         | 4.26%   |
| Validity Sensors Fingerprint scanner                                       | 7         | 3.72%   |
| Elan ELAN:ARM-M4                                                           | 7         | 3.72%   |
| Validity Sensors VFS491                                                    | 6         | 3.19%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 6         | 3.19%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 3.19%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 5         | 2.66%   |
| STMicroelectronics Fingerprint Reader                                      | 5         | 2.66%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 2.13%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 4         | 2.13%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 2.13%   |
| Elan ELAN:Fingerprint                                                      | 4         | 2.13%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 4         | 2.13%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 3         | 1.6%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 1.6%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 1.6%    |
| Validity Sensors Synaptics WBDI                                            | 3         | 1.6%    |
| Synaptics  WBDI                                                            | 3         | 1.6%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 1.6%    |
| AuthenTec Fingerprint Sensor                                               | 3         | 1.6%    |
| AuthenTec AES1600                                                          | 3         | 1.6%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 1.06%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 1.06%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 1.06%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 1.06%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 2         | 1.06%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.53%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.53%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.53%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.53%   |
| LighTuning EgisTec_ES603                                                   | 1         | 0.53%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.53%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.53%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 44        | 52.38%  |
| Alcor Micro                       | 12        | 14.29%  |
| O2 Micro                          | 6         | 7.14%   |
| Upek                              | 5         | 5.95%   |
| Lenovo                            | 5         | 5.95%   |
| Realtek Semiconductor             | 3         | 3.57%   |
| Yubico.com                        | 2         | 2.38%   |
| Advanced Card Systems             | 2         | 2.38%   |
| VASCO Data Security International | 1         | 1.19%   |
| SCM Microsystems                  | 1         | 1.19%   |
| Reiner SCT Kartensysteme          | 1         | 1.19%   |
| OmniKey                           | 1         | 1.19%   |
| Fujitsu Siemens Computers         | 1         | 1.19%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 17        | 20.24%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 14        | 16.67%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 12        | 14.29%  |
| Broadcom 5880                                                                | 9         | 10.71%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 6         | 7.14%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 5.95%   |
| Lenovo Integrated Smart Card Reader                                          | 5         | 5.95%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 3         | 3.57%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 2.38%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 2.38%   |
| Broadcom 58200                                                               | 2         | 2.38%   |
| VASCO Data Security International DIGIPASS 870                               | 1         | 1.19%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 1.19%   |
| Reiner SCT Kartensysteme cyberJack e-com/pinpad                              | 1         | 1.19%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 1.19%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 1.19%   |
| Advanced Card Systems ACR39U                                                 | 1         | 1.19%   |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 1         | 1.19%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1549      | 72.52%  |
| 1     | 489       | 22.89%  |
| 2     | 90        | 4.21%   |
| 3     | 8         | 0.37%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 183       | 27.03%  |
| Graphics card            | 141       | 20.83%  |
| Net/wireless             | 123       | 18.17%  |
| Multimedia controller    | 75        | 11.08%  |
| Chipcard                 | 75        | 11.08%  |
| Bluetooth                | 14        | 2.07%   |
| Storage                  | 13        | 1.92%   |
| Communication controller | 12        | 1.77%   |
| Sound                    | 6         | 0.89%   |
| Camera                   | 6         | 0.89%   |
| Unassigned class         | 5         | 0.74%   |
| Modem                    | 4         | 0.59%   |
| Storage/ide              | 3         | 0.44%   |
| Net/ethernet             | 3         | 0.44%   |
| Dvb card                 | 3         | 0.44%   |
| Card reader              | 3         | 0.44%   |
| Storage/nvme             | 2         | 0.3%    |
| Network                  | 2         | 0.3%    |
| Flash memory             | 2         | 0.3%    |
| Unclassified device      | 1         | 0.15%   |
| Storage/raid             | 1         | 0.15%   |

