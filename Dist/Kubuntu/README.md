Kubuntu - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for Kubuntu.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Kubuntu/Desktop/README.md) and [notebooks](/Dist/Kubuntu/Notebook/README.md).

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

Total: 5113

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Acer          | Aspire A515-57              | Notebook    | [4a1b8f3f21](https://linux-hardware.org/?probe=4a1b8f3f21) | Apr 01, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [89ca656f30](https://linux-hardware.org/?probe=89ca656f30) | Apr 01, 2023 |
| Lenovo        | ThinkCentre M58 9728AHG     | Desktop     | [cb0fa70953](https://linux-hardware.org/?probe=cb0fa70953) | Apr 01, 2023 |
| Gigabyte      | A7 K1                       | Notebook    | [e5e7751054](https://linux-hardware.org/?probe=e5e7751054) | Mar 31, 2023 |
| Chuwi         | CoreBook XPro               | Notebook    | [85ad17d246](https://linux-hardware.org/?probe=85ad17d246) | Mar 31, 2023 |
| Intel         | Whiskey Platform            | Notebook    | [36b9d4d898](https://linux-hardware.org/?probe=36b9d4d898) | Mar 31, 2023 |
| Samsung       | 950QDB                      | Convertible | [09717388fb](https://linux-hardware.org/?probe=09717388fb) | Mar 31, 2023 |
| ASUSTek       | EB1036                      | Desktop     | [955d389e06](https://linux-hardware.org/?probe=955d389e06) | Mar 30, 2023 |
| Dell          | Vostro 15-3568              | Notebook    | [3636f7f999](https://linux-hardware.org/?probe=3636f7f999) | Mar 30, 2023 |
| Motion Com... | J3600                       | Notebook    | [0980fe0a37](https://linux-hardware.org/?probe=0980fe0a37) | Mar 30, 2023 |
| Intel         | Whiskey Platform            | Notebook    | [a96edb2321](https://linux-hardware.org/?probe=a96edb2321) | Mar 30, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [278ed0e013](https://linux-hardware.org/?probe=278ed0e013) | Mar 30, 2023 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [49f246c5e7](https://linux-hardware.org/?probe=49f246c5e7) | Mar 29, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [4f9eed1de2](https://linux-hardware.org/?probe=4f9eed1de2) | Mar 29, 2023 |
| Lenovo        | ThinkPad T480 20L6S3H102    | Notebook    | [cf75eeabd5](https://linux-hardware.org/?probe=cf75eeabd5) | Mar 29, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [b72701d99c](https://linux-hardware.org/?probe=b72701d99c) | Mar 29, 2023 |
| Intel         | DQ67OW AAG28716-309         | Desktop     | [3a82d680e5](https://linux-hardware.org/?probe=3a82d680e5) | Mar 29, 2023 |
| Dell          | 0200DY A01                  | Desktop     | [722b28547b](https://linux-hardware.org/?probe=722b28547b) | Mar 28, 2023 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [548224967e](https://linux-hardware.org/?probe=548224967e) | Mar 28, 2023 |
| HP            | 0AACh                       | Desktop     | [e313c99b98](https://linux-hardware.org/?probe=e313c99b98) | Mar 28, 2023 |
| MSI           | B85-G43                     | Desktop     | [3dac8c76c2](https://linux-hardware.org/?probe=3dac8c76c2) | Mar 28, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [fd1273ed2e](https://linux-hardware.org/?probe=fd1273ed2e) | Mar 28, 2023 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [046b4b7497](https://linux-hardware.org/?probe=046b4b7497) | Mar 28, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [0f38ea375f](https://linux-hardware.org/?probe=0f38ea375f) | Mar 28, 2023 |
| Lenovo        | SHARKBAY SDK0J40709 WIN ... | Desktop     | [22e3e1831c](https://linux-hardware.org/?probe=22e3e1831c) | Mar 28, 2023 |
| HP            | 0AACh                       | Desktop     | [f354a2f03e](https://linux-hardware.org/?probe=f354a2f03e) | Mar 27, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [84092aca44](https://linux-hardware.org/?probe=84092aca44) | Mar 27, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [ccae23c5a7](https://linux-hardware.org/?probe=ccae23c5a7) | Mar 27, 2023 |
| GEO           | GeoFlex 340                 | Convertible | [d18cb08996](https://linux-hardware.org/?probe=d18cb08996) | Mar 26, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [6553d2c85a](https://linux-hardware.org/?probe=6553d2c85a) | Mar 26, 2023 |
| HP            | 1998                        | Desktop     | [346f37956b](https://linux-hardware.org/?probe=346f37956b) | Mar 26, 2023 |
| Lenovo        | ThinkPad SL 2743NSC         | Notebook    | [48d6301eaa](https://linux-hardware.org/?probe=48d6301eaa) | Mar 26, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [ffb310e799](https://linux-hardware.org/?probe=ffb310e799) | Mar 26, 2023 |
| HUAWEI        | KLVDZ-WXX9                  | Notebook    | [369363c3a9](https://linux-hardware.org/?probe=369363c3a9) | Mar 26, 2023 |
| Intel         | NUC5i3RYB H41000-502        | Mini pc     | [fac3426827](https://linux-hardware.org/?probe=fac3426827) | Mar 26, 2023 |
| HUAWEI        | HN-WX9X                     | Notebook    | [cdc4b03fe2](https://linux-hardware.org/?probe=cdc4b03fe2) | Mar 26, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [2246abad85](https://linux-hardware.org/?probe=2246abad85) | Mar 25, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [4262f0e159](https://linux-hardware.org/?probe=4262f0e159) | Mar 25, 2023 |
| MSI           | Z170A PC MATE               | Desktop     | [ad4b4f6a8f](https://linux-hardware.org/?probe=ad4b4f6a8f) | Mar 25, 2023 |
| Intel         | Whiskey Platform            | Notebook    | [e90c029740](https://linux-hardware.org/?probe=e90c029740) | Mar 25, 2023 |
| ASUSTek       | H97-PLUS                    | Desktop     | [30d5652df2](https://linux-hardware.org/?probe=30d5652df2) | Mar 25, 2023 |
| Dell          | Inspiron 7400               | Notebook    | [a0bba69c40](https://linux-hardware.org/?probe=a0bba69c40) | Mar 25, 2023 |
| Dell          | Inspiron 7400               | Notebook    | [98d0daa764](https://linux-hardware.org/?probe=98d0daa764) | Mar 25, 2023 |
| Dell          | Latitude E6420              | Notebook    | [2613e5a6ef](https://linux-hardware.org/?probe=2613e5a6ef) | Mar 25, 2023 |
| ASUSTek       | ROG Maximus XII FORMULA     | Desktop     | [bf5cc186ea](https://linux-hardware.org/?probe=bf5cc186ea) | Mar 25, 2023 |
| ASUSTek       | ROG Maximus XII FORMULA     | Desktop     | [c37a546614](https://linux-hardware.org/?probe=c37a546614) | Mar 25, 2023 |
| Carbon Sys... | Iridium 14                  | Notebook    | [e7f9195a1d](https://linux-hardware.org/?probe=e7f9195a1d) | Mar 25, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [e7b44d994b](https://linux-hardware.org/?probe=e7b44d994b) | Mar 25, 2023 |
| ASUSTek       | ROG Maximus XII FORMULA     | Desktop     | [444375922e](https://linux-hardware.org/?probe=444375922e) | Mar 25, 2023 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [9a8b9b917f](https://linux-hardware.org/?probe=9a8b9b917f) | Mar 24, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [c114580013](https://linux-hardware.org/?probe=c114580013) | Mar 24, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [1f256fa102](https://linux-hardware.org/?probe=1f256fa102) | Mar 24, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [c7ec617422](https://linux-hardware.org/?probe=c7ec617422) | Mar 24, 2023 |
| HONOR         | BBR-WAX9                    | Notebook    | [63fafca0ac](https://linux-hardware.org/?probe=63fafca0ac) | Mar 24, 2023 |
| HONOR         | BBR-WAX9                    | Notebook    | [2d8268e40f](https://linux-hardware.org/?probe=2d8268e40f) | Mar 24, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [c50deee021](https://linux-hardware.org/?probe=c50deee021) | Mar 24, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [4e2b8b9de9](https://linux-hardware.org/?probe=4e2b8b9de9) | Mar 24, 2023 |
| MSI           | B360M BAZOOKA               | Desktop     | [6d1a1f7bd2](https://linux-hardware.org/?probe=6d1a1f7bd2) | Mar 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M560... | Notebook    | [16b93bfe5d](https://linux-hardware.org/?probe=16b93bfe5d) | Mar 24, 2023 |
| Dell          | Latitude 5420               | Notebook    | [42d5b573c4](https://linux-hardware.org/?probe=42d5b573c4) | Mar 24, 2023 |
| Dell          | Latitude E7470              | Notebook    | [ca8a2d9579](https://linux-hardware.org/?probe=ca8a2d9579) | Mar 24, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [9b048b064d](https://linux-hardware.org/?probe=9b048b064d) | Mar 24, 2023 |
| Dell          | 0W13NR A08                  | Server      | [13bd99e4bc](https://linux-hardware.org/?probe=13bd99e4bc) | Mar 23, 2023 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [43113791e9](https://linux-hardware.org/?probe=43113791e9) | Mar 23, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [4077bee378](https://linux-hardware.org/?probe=4077bee378) | Mar 23, 2023 |
| Dell          | Vostro 5620                 | Notebook    | [529a2febf7](https://linux-hardware.org/?probe=529a2febf7) | Mar 23, 2023 |
| Notebook      | NV4xPZ                      | Notebook    | [74d70a3568](https://linux-hardware.org/?probe=74d70a3568) | Mar 23, 2023 |
| Lenovo        | ThinkCentre M58 9728AHG     | Desktop     | [e1cfc1c76d](https://linux-hardware.org/?probe=e1cfc1c76d) | Mar 23, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [84f93bfcf1](https://linux-hardware.org/?probe=84f93bfcf1) | Mar 23, 2023 |
| HP            | ZBook 15 G6                 | Notebook    | [631968d54b](https://linux-hardware.org/?probe=631968d54b) | Mar 23, 2023 |
| HP            | ZBook 15 G6                 | Notebook    | [61dcde6523](https://linux-hardware.org/?probe=61dcde6523) | Mar 22, 2023 |
| Dell          | Latitude E7470              | Notebook    | [9595c39422](https://linux-hardware.org/?probe=9595c39422) | Mar 22, 2023 |
| Sony          | VGN-NW270F                  | Notebook    | [48080babd0](https://linux-hardware.org/?probe=48080babd0) | Mar 22, 2023 |
| MSI           | GE70 2PE                    | Notebook    | [5e68fcc30d](https://linux-hardware.org/?probe=5e68fcc30d) | Mar 22, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | Notebook    | [ae63ffa582](https://linux-hardware.org/?probe=ae63ffa582) | Mar 21, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [2da4187f91](https://linux-hardware.org/?probe=2da4187f91) | Mar 21, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [d9c0447b0d](https://linux-hardware.org/?probe=d9c0447b0d) | Mar 21, 2023 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | Desktop     | [293e9a941a](https://linux-hardware.org/?probe=293e9a941a) | Mar 20, 2023 |
| HP            | ProBook 640 G4              | Notebook    | [2787c4bf42](https://linux-hardware.org/?probe=2787c4bf42) | Mar 20, 2023 |
| Apple         | Mac-FA842E06C61E91C5 iMa... | All in one  | [0cfaf0934d](https://linux-hardware.org/?probe=0cfaf0934d) | Mar 20, 2023 |
| HP            | 21F5                        | Desktop     | [865a85e5bc](https://linux-hardware.org/?probe=865a85e5bc) | Mar 20, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [83fbe3a3d6](https://linux-hardware.org/?probe=83fbe3a3d6) | Mar 20, 2023 |
| Lenovo        | Yoga C740-15IML 81TD        | Convertible | [ede048bc5d](https://linux-hardware.org/?probe=ede048bc5d) | Mar 20, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [a71c5a4629](https://linux-hardware.org/?probe=a71c5a4629) | Mar 19, 2023 |
| Gigabyte      | H170-D3HP-CF                | Desktop     | [619a36ed2f](https://linux-hardware.org/?probe=619a36ed2f) | Mar 19, 2023 |
| Intel         | DH67BL AAG10189-208         | Desktop     | [420f476f82](https://linux-hardware.org/?probe=420f476f82) | Mar 19, 2023 |
| ASUSTek       | T300CHI                     | Notebook    | [371961ad53](https://linux-hardware.org/?probe=371961ad53) | Mar 19, 2023 |
| Acer          | Nitro AN517-41              | Notebook    | [5e5fd3788e](https://linux-hardware.org/?probe=5e5fd3788e) | Mar 19, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [efaf7d4a30](https://linux-hardware.org/?probe=efaf7d4a30) | Mar 18, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [99e92fa4df](https://linux-hardware.org/?probe=99e92fa4df) | Mar 18, 2023 |
| Avell High... | C62 MOB                     | Notebook    | [7eaededaac](https://linux-hardware.org/?probe=7eaededaac) | Mar 18, 2023 |
| MSI           | MPG B460I GAMING EDGE WI... | Desktop     | [8cf99eb521](https://linux-hardware.org/?probe=8cf99eb521) | Mar 18, 2023 |
| Carbon Sys... | Iridium 14                  | Notebook    | [c70e1d7e98](https://linux-hardware.org/?probe=c70e1d7e98) | Mar 18, 2023 |
| HP            | ZBook 15 G6                 | Notebook    | [5a429f93a7](https://linux-hardware.org/?probe=5a429f93a7) | Mar 18, 2023 |
| Acer          | Aspire XC600 v1.0           | Desktop     | [ef3e267972](https://linux-hardware.org/?probe=ef3e267972) | Mar 18, 2023 |
| Clevo         | W340EU                      | Notebook    | [b90ad98b0a](https://linux-hardware.org/?probe=b90ad98b0a) | Mar 18, 2023 |
| HP            | 8266                        | Desktop     | [8bac7f79e8](https://linux-hardware.org/?probe=8bac7f79e8) | Mar 17, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | Notebook    | [786fded1ce](https://linux-hardware.org/?probe=786fded1ce) | Mar 17, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [e0fa4709db](https://linux-hardware.org/?probe=e0fa4709db) | Mar 17, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [3e5167941c](https://linux-hardware.org/?probe=3e5167941c) | Mar 17, 2023 |
| Clevo         | W340EU                      | Notebook    | [240779648a](https://linux-hardware.org/?probe=240779648a) | Mar 17, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [9ca1015389](https://linux-hardware.org/?probe=9ca1015389) | Mar 16, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [1ed7ccd033](https://linux-hardware.org/?probe=1ed7ccd033) | Mar 16, 2023 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [d1edfbc4b3](https://linux-hardware.org/?probe=d1edfbc4b3) | Mar 16, 2023 |
| Acer          | Aspire M3920                | Desktop     | [bb2e9ec8a1](https://linux-hardware.org/?probe=bb2e9ec8a1) | Mar 16, 2023 |
| Dell          | Inspiron 13 5310            | Notebook    | [697914b165](https://linux-hardware.org/?probe=697914b165) | Mar 16, 2023 |
| Lenovo        | ThinkPad X390 20Q0000SMX    | Notebook    | [69f39892c4](https://linux-hardware.org/?probe=69f39892c4) | Mar 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [b20f8089c3](https://linux-hardware.org/?probe=b20f8089c3) | Mar 15, 2023 |
| Dell          | Inspiron 5575               | Notebook    | [0ace5375f4](https://linux-hardware.org/?probe=0ace5375f4) | Mar 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [fbbcc2d2c5](https://linux-hardware.org/?probe=fbbcc2d2c5) | Mar 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [b0b8ac79d9](https://linux-hardware.org/?probe=b0b8ac79d9) | Mar 15, 2023 |
| Lenovo        | ThinkPad X390 20Q0000SMX    | Notebook    | [8fff8ca97d](https://linux-hardware.org/?probe=8fff8ca97d) | Mar 15, 2023 |
| Lenovo        | ThinkPad E480 20KNA01HIG    | Notebook    | [c8054d1090](https://linux-hardware.org/?probe=c8054d1090) | Mar 15, 2023 |
| Supermicro    | X9DRD-C/iT+                 | Desktop     | [57c78aa4db](https://linux-hardware.org/?probe=57c78aa4db) | Mar 15, 2023 |
| Toshiba       | QOSMIO X70-A                | Notebook    | [f85336fbca](https://linux-hardware.org/?probe=f85336fbca) | Mar 15, 2023 |
| HP            | ZBook 15                    | Notebook    | [ebc4b1e01e](https://linux-hardware.org/?probe=ebc4b1e01e) | Mar 14, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [f424a1dc42](https://linux-hardware.org/?probe=f424a1dc42) | Mar 14, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [b5ef4ae548](https://linux-hardware.org/?probe=b5ef4ae548) | Mar 14, 2023 |
| HP            | 2B52                        | Desktop     | [b541e6085e](https://linux-hardware.org/?probe=b541e6085e) | Mar 14, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [783ff991d4](https://linux-hardware.org/?probe=783ff991d4) | Mar 14, 2023 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | Desktop     | [c5a25ab496](https://linux-hardware.org/?probe=c5a25ab496) | Mar 14, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [21fc92246e](https://linux-hardware.org/?probe=21fc92246e) | Mar 13, 2023 |
| MSI           | B85-G43                     | Desktop     | [7e9ce07cb8](https://linux-hardware.org/?probe=7e9ce07cb8) | Mar 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [3c4e911c6d](https://linux-hardware.org/?probe=3c4e911c6d) | Mar 13, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [e79cdeaf10](https://linux-hardware.org/?probe=e79cdeaf10) | Mar 13, 2023 |
| MSI           | B85-G43                     | Desktop     | [9a9a70ade3](https://linux-hardware.org/?probe=9a9a70ade3) | Mar 13, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [007f595264](https://linux-hardware.org/?probe=007f595264) | Mar 13, 2023 |
| Acer          | Aspire A715-74G             | Notebook    | [57000f8a86](https://linux-hardware.org/?probe=57000f8a86) | Mar 13, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [456057e6af](https://linux-hardware.org/?probe=456057e6af) | Mar 13, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [7ee93079fb](https://linux-hardware.org/?probe=7ee93079fb) | Mar 13, 2023 |
| Toshiba       | Satellite L515              | Notebook    | [11116a9517](https://linux-hardware.org/?probe=11116a9517) | Mar 13, 2023 |
| ASUSTek       | K55VJ                       | Notebook    | [6a0673f946](https://linux-hardware.org/?probe=6a0673f946) | Mar 13, 2023 |
| ASRockRack    | ROMED6U-2L2T                | Desktop     | [1af076312d](https://linux-hardware.org/?probe=1af076312d) | Mar 12, 2023 |
| Dell          | Latitude E6420              | Notebook    | [6fe2914b41](https://linux-hardware.org/?probe=6fe2914b41) | Mar 12, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [60bc8c1ef5](https://linux-hardware.org/?probe=60bc8c1ef5) | Mar 12, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [4ee87a1213](https://linux-hardware.org/?probe=4ee87a1213) | Mar 12, 2023 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [77b7a9348b](https://linux-hardware.org/?probe=77b7a9348b) | Mar 12, 2023 |
| ASUSTek       | K55VJ                       | Notebook    | [d550e765ac](https://linux-hardware.org/?probe=d550e765ac) | Mar 12, 2023 |
| Toshiba       | Satellite L515              | Notebook    | [f2ffca7459](https://linux-hardware.org/?probe=f2ffca7459) | Mar 12, 2023 |
| MSI           | MAG B660M BAZOOKA DDR4      | Desktop     | [cb1be19cd3](https://linux-hardware.org/?probe=cb1be19cd3) | Mar 11, 2023 |
| Lenovo        | XiaoXin-15ARE 2020 81YR     | Notebook    | [bcbf6544cd](https://linux-hardware.org/?probe=bcbf6544cd) | Mar 11, 2023 |
| MSI           | B85-G43                     | Desktop     | [47ac638c2e](https://linux-hardware.org/?probe=47ac638c2e) | Mar 11, 2023 |
| Intel         | NUC7i5DNB J57626-509        | Mini pc     | [1b49e21822](https://linux-hardware.org/?probe=1b49e21822) | Mar 11, 2023 |
| HP            | 0AACh                       | Desktop     | [83f0c7df93](https://linux-hardware.org/?probe=83f0c7df93) | Mar 10, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [d039d459d7](https://linux-hardware.org/?probe=d039d459d7) | Mar 10, 2023 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [9f02108ada](https://linux-hardware.org/?probe=9f02108ada) | Mar 09, 2023 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [5a0eb5bfed](https://linux-hardware.org/?probe=5a0eb5bfed) | Mar 09, 2023 |
| ASUSTek       | K55VJ                       | Notebook    | [2750a8a462](https://linux-hardware.org/?probe=2750a8a462) | Mar 09, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [b7fd2dfa30](https://linux-hardware.org/?probe=b7fd2dfa30) | Mar 09, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [f658e58c98](https://linux-hardware.org/?probe=f658e58c98) | Mar 09, 2023 |
| Dell          | Inspiron 15-3565            | Notebook    | [a71845e346](https://linux-hardware.org/?probe=a71845e346) | Mar 09, 2023 |
| ASUSTek       | ZenBook UX463FL_UX463FL     | Convertible | [8fbb4566ac](https://linux-hardware.org/?probe=8fbb4566ac) | Mar 08, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [2b74ad2ed1](https://linux-hardware.org/?probe=2b74ad2ed1) | Mar 08, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [e777d1af00](https://linux-hardware.org/?probe=e777d1af00) | Mar 08, 2023 |
| Maibenben     | JinMai6 series              | Notebook    | [ace44d9872](https://linux-hardware.org/?probe=ace44d9872) | Mar 08, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [fdc9f52c81](https://linux-hardware.org/?probe=fdc9f52c81) | Mar 08, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [7bd6e95116](https://linux-hardware.org/?probe=7bd6e95116) | Mar 08, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [d3cd7ae3e8](https://linux-hardware.org/?probe=d3cd7ae3e8) | Mar 07, 2023 |
| Lenovo        | IdeaPad C340-14IWL 81RL     | Convertible | [9625716631](https://linux-hardware.org/?probe=9625716631) | Mar 07, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [b48c76be97](https://linux-hardware.org/?probe=b48c76be97) | Mar 07, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [22569ee1f4](https://linux-hardware.org/?probe=22569ee1f4) | Mar 07, 2023 |
| HP            | ENVY TS 17                  | Notebook    | [c915d51f5e](https://linux-hardware.org/?probe=c915d51f5e) | Mar 07, 2023 |
| Datto         | 1000                        | Notebook    | [9df2913c36](https://linux-hardware.org/?probe=9df2913c36) | Mar 07, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [2f8d0ff7f5](https://linux-hardware.org/?probe=2f8d0ff7f5) | Mar 06, 2023 |
| ASUSTek       | K52JT                       | Notebook    | [802fe86b5c](https://linux-hardware.org/?probe=802fe86b5c) | Mar 06, 2023 |
| Alienware     | x14                         | Notebook    | [a1665c85ab](https://linux-hardware.org/?probe=a1665c85ab) | Mar 06, 2023 |
| Alienware     | x14                         | Notebook    | [8f12fe3ee5](https://linux-hardware.org/?probe=8f12fe3ee5) | Mar 06, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [ca2ad0edee](https://linux-hardware.org/?probe=ca2ad0edee) | Mar 05, 2023 |
| Lenovo        | Legion 5 17ACH6 82K0        | Notebook    | [6db57d4d9f](https://linux-hardware.org/?probe=6db57d4d9f) | Mar 05, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [28dbdcfbb7](https://linux-hardware.org/?probe=28dbdcfbb7) | Mar 05, 2023 |
| Dell          | Latitude E6420              | Notebook    | [569d016799](https://linux-hardware.org/?probe=569d016799) | Mar 05, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [2311f1da09](https://linux-hardware.org/?probe=2311f1da09) | Mar 05, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [483a11d21e](https://linux-hardware.org/?probe=483a11d21e) | Mar 05, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [8805f0bce5](https://linux-hardware.org/?probe=8805f0bce5) | Mar 05, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [7d43df02db](https://linux-hardware.org/?probe=7d43df02db) | Mar 04, 2023 |
| HP            | 89B5 A                      | Desktop     | [b1f4e34d2d](https://linux-hardware.org/?probe=b1f4e34d2d) | Mar 04, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [63e9a399f8](https://linux-hardware.org/?probe=63e9a399f8) | Mar 04, 2023 |
| Dell          | XPS 17 9700                 | Notebook    | [8a4cc5192e](https://linux-hardware.org/?probe=8a4cc5192e) | Mar 04, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [a7860ee046](https://linux-hardware.org/?probe=a7860ee046) | Mar 04, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [c654c1809d](https://linux-hardware.org/?probe=c654c1809d) | Mar 04, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [5a15c4c2b0](https://linux-hardware.org/?probe=5a15c4c2b0) | Mar 03, 2023 |
| ASUSTek       | P9X79                       | Desktop     | [9a3c215b30](https://linux-hardware.org/?probe=9a3c215b30) | Mar 03, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [fdee05953f](https://linux-hardware.org/?probe=fdee05953f) | Mar 03, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [a5939aa47c](https://linux-hardware.org/?probe=a5939aa47c) | Mar 03, 2023 |
| Dell          | Latitude 5420               | Notebook    | [b763e54ded](https://linux-hardware.org/?probe=b763e54ded) | Mar 03, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [4d68c19c3e](https://linux-hardware.org/?probe=4d68c19c3e) | Mar 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [6c007c983c](https://linux-hardware.org/?probe=6c007c983c) | Mar 02, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [82847b3b1f](https://linux-hardware.org/?probe=82847b3b1f) | Mar 02, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [cc8c299b5d](https://linux-hardware.org/?probe=cc8c299b5d) | Mar 01, 2023 |
| Dell          | 05R2TK A01                  | All in one  | [efa9d9069d](https://linux-hardware.org/?probe=efa9d9069d) | Mar 01, 2023 |
| Pegatron      | SM3330B 0500B               | Desktop     | [7ec6d4d881](https://linux-hardware.org/?probe=7ec6d4d881) | Mar 01, 2023 |
| Gigabyte      | X58A-UD7                    | Desktop     | [727ce4b27e](https://linux-hardware.org/?probe=727ce4b27e) | Mar 01, 2023 |
| Gigabyte      | X58A-UD7                    | Desktop     | [bbc9bc409c](https://linux-hardware.org/?probe=bbc9bc409c) | Mar 01, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [131f94f213](https://linux-hardware.org/?probe=131f94f213) | Mar 01, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [ecfa5f6c27](https://linux-hardware.org/?probe=ecfa5f6c27) | Mar 01, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [8fd450db03](https://linux-hardware.org/?probe=8fd450db03) | Feb 28, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [41439f6b61](https://linux-hardware.org/?probe=41439f6b61) | Feb 28, 2023 |
| Dell          | Latitude 5530               | Notebook    | [f892221e4c](https://linux-hardware.org/?probe=f892221e4c) | Feb 27, 2023 |
| ASRock        | Z790 PG Lightning           | Desktop     | [86c7144757](https://linux-hardware.org/?probe=86c7144757) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [003aa3d3e9](https://linux-hardware.org/?probe=003aa3d3e9) | Feb 27, 2023 |
| HP            | EliteBook 835 G8 Noteboo... | Notebook    | [aa26becbb1](https://linux-hardware.org/?probe=aa26becbb1) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [ad20f98122](https://linux-hardware.org/?probe=ad20f98122) | Feb 27, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [a2af33e0e3](https://linux-hardware.org/?probe=a2af33e0e3) | Feb 27, 2023 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [a5f5bdc903](https://linux-hardware.org/?probe=a5f5bdc903) | Feb 26, 2023 |
| Gigabyte      | B360M HD3                   | Desktop     | [d3821bdbab](https://linux-hardware.org/?probe=d3821bdbab) | Feb 26, 2023 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | Notebook    | [d6e0c6c0ac](https://linux-hardware.org/?probe=d6e0c6c0ac) | Feb 26, 2023 |
| ASRock        | G41C-GS                     | Desktop     | [6a698dda57](https://linux-hardware.org/?probe=6a698dda57) | Feb 26, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [575e6a8c55](https://linux-hardware.org/?probe=575e6a8c55) | Feb 26, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [8bfe7e434d](https://linux-hardware.org/?probe=8bfe7e434d) | Feb 26, 2023 |
| Lenovo        | ThinkPad L430 24663D1       | Notebook    | [b410d220e6](https://linux-hardware.org/?probe=b410d220e6) | Feb 26, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [67b8b5ad09](https://linux-hardware.org/?probe=67b8b5ad09) | Feb 26, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [c872892cfd](https://linux-hardware.org/?probe=c872892cfd) | Feb 26, 2023 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [c6ca9e8499](https://linux-hardware.org/?probe=c6ca9e8499) | Feb 26, 2023 |
| MSI           | A320M PRO-VD PLUS           | Desktop     | [bd6c07d84d](https://linux-hardware.org/?probe=bd6c07d84d) | Feb 26, 2023 |
| HP            | G62                         | Notebook    | [871207750c](https://linux-hardware.org/?probe=871207750c) | Feb 25, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [2943aa6cd7](https://linux-hardware.org/?probe=2943aa6cd7) | Feb 25, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [0b9491b3a0](https://linux-hardware.org/?probe=0b9491b3a0) | Feb 25, 2023 |
| ASRock        | H97 Pro4                    | Desktop     | [f703af2e6b](https://linux-hardware.org/?probe=f703af2e6b) | Feb 25, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [844de888cd](https://linux-hardware.org/?probe=844de888cd) | Feb 25, 2023 |
| System76      | Gazelle                     | Notebook    | [64fcb063eb](https://linux-hardware.org/?probe=64fcb063eb) | Feb 25, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [e7bf168729](https://linux-hardware.org/?probe=e7bf168729) | Feb 25, 2023 |
| Alienware     | m15 R7 AMD                  | Notebook    | [0a44dcc29e](https://linux-hardware.org/?probe=0a44dcc29e) | Feb 24, 2023 |
| Dell          | Latitude 5530               | Notebook    | [8ad26dd8a0](https://linux-hardware.org/?probe=8ad26dd8a0) | Feb 24, 2023 |
| Alienware     | m15 R7 AMD                  | Notebook    | [3ba05d49d8](https://linux-hardware.org/?probe=3ba05d49d8) | Feb 24, 2023 |
| ASRock        | M3A770DE                    | Desktop     | [b025c7a092](https://linux-hardware.org/?probe=b025c7a092) | Feb 24, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [463265c999](https://linux-hardware.org/?probe=463265c999) | Feb 24, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [4aec81f692](https://linux-hardware.org/?probe=4aec81f692) | Feb 24, 2023 |
| MSI           | GE75 Raider 9SE             | Notebook    | [6d0782da8e](https://linux-hardware.org/?probe=6d0782da8e) | Feb 24, 2023 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | Desktop     | [471b84b6d4](https://linux-hardware.org/?probe=471b84b6d4) | Feb 23, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [2f9c2ec647](https://linux-hardware.org/?probe=2f9c2ec647) | Feb 23, 2023 |
| Samsung       | 950QDB                      | Convertible | [2545626207](https://linux-hardware.org/?probe=2545626207) | Feb 23, 2023 |
| Dell          | 0PC5F7 A03                  | Desktop     | [27f07447f7](https://linux-hardware.org/?probe=27f07447f7) | Feb 23, 2023 |
| Shuttle       | FL10J                       | Desktop     | [943316a9c5](https://linux-hardware.org/?probe=943316a9c5) | Feb 22, 2023 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [c81213c25e](https://linux-hardware.org/?probe=c81213c25e) | Feb 22, 2023 |
| Dell          | System Inspiron N7110       | Notebook    | [4a3b8e0755](https://linux-hardware.org/?probe=4a3b8e0755) | Feb 22, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [acb8644ede](https://linux-hardware.org/?probe=acb8644ede) | Feb 21, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [d6ec8781f4](https://linux-hardware.org/?probe=d6ec8781f4) | Feb 21, 2023 |
| MSI           | B85-G43                     | Desktop     | [62273631b2](https://linux-hardware.org/?probe=62273631b2) | Feb 21, 2023 |
| Dell          | 01TN68 A02                  | Desktop     | [ce7bdb1ddf](https://linux-hardware.org/?probe=ce7bdb1ddf) | Feb 21, 2023 |
| Lenovo        | ThinkPad T440p 20AWS3E20... | Notebook    | [012b54b31c](https://linux-hardware.org/?probe=012b54b31c) | Feb 21, 2023 |
| Dell          | Inspiron 7400               | Notebook    | [0d286f12f4](https://linux-hardware.org/?probe=0d286f12f4) | Feb 21, 2023 |
| GPU Compan... | GWTC116-2                   | Notebook    | [5fa20b737f](https://linux-hardware.org/?probe=5fa20b737f) | Feb 21, 2023 |
| ASRock        | 960GC-GS FX                 | Desktop     | [39718b8983](https://linux-hardware.org/?probe=39718b8983) | Feb 20, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [6033e6cb63](https://linux-hardware.org/?probe=6033e6cb63) | Feb 20, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [63de5bef96](https://linux-hardware.org/?probe=63de5bef96) | Feb 20, 2023 |
| Apple         | MacBookAir3,1               | Notebook    | [1e0de945b7](https://linux-hardware.org/?probe=1e0de945b7) | Feb 20, 2023 |
| Gigabyte      | X99-Ultra Gaming-CF         | Desktop     | [031c13ea35](https://linux-hardware.org/?probe=031c13ea35) | Feb 19, 2023 |
| ASUSTek       | H97-PLUS                    | Desktop     | [6824ee9944](https://linux-hardware.org/?probe=6824ee9944) | Feb 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | Notebook    | [7e5327c1ed](https://linux-hardware.org/?probe=7e5327c1ed) | Feb 19, 2023 |
| HP            | ProBook 4730s               | Notebook    | [99232fe32d](https://linux-hardware.org/?probe=99232fe32d) | Feb 19, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [82db23bd7f](https://linux-hardware.org/?probe=82db23bd7f) | Feb 19, 2023 |
| ASUSTek       | X555LJ                      | Notebook    | [93f3ae1f77](https://linux-hardware.org/?probe=93f3ae1f77) | Feb 19, 2023 |
| HP            | Victus by Laptop 16z-e10... | Notebook    | [a48460122c](https://linux-hardware.org/?probe=a48460122c) | Feb 19, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [25c9923614](https://linux-hardware.org/?probe=25c9923614) | Feb 18, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [b3c5c043ea](https://linux-hardware.org/?probe=b3c5c043ea) | Feb 18, 2023 |
| Acer          | Aspire A515-46              | Notebook    | [46a8b61785](https://linux-hardware.org/?probe=46a8b61785) | Feb 18, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [1c1470c8a2](https://linux-hardware.org/?probe=1c1470c8a2) | Feb 18, 2023 |
| Intel         | DP965LT AAD41694-206        | Desktop     | [2744ec3c4a](https://linux-hardware.org/?probe=2744ec3c4a) | Feb 18, 2023 |
| Dell          | Inspiron 14 7420 2-in-1     | Convertible | [7daf230ef2](https://linux-hardware.org/?probe=7daf230ef2) | Feb 18, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [eb64c99981](https://linux-hardware.org/?probe=eb64c99981) | Feb 18, 2023 |
| Dell          | System Inspiron N7110       | Notebook    | [542553dd55](https://linux-hardware.org/?probe=542553dd55) | Feb 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [4baabf8013](https://linux-hardware.org/?probe=4baabf8013) | Feb 18, 2023 |
| Dell          | Precision 7540              | Notebook    | [2a511e3e78](https://linux-hardware.org/?probe=2a511e3e78) | Feb 17, 2023 |
| MSI           | MAG B560 TOMAHAWK WIFI      | Desktop     | [6538791548](https://linux-hardware.org/?probe=6538791548) | Feb 17, 2023 |
| MSI           | MAG B560 TOMAHAWK WIFI      | Desktop     | [2da59271fe](https://linux-hardware.org/?probe=2da59271fe) | Feb 17, 2023 |
| Dell          | 0DF42J A00                  | Desktop     | [e192547cd3](https://linux-hardware.org/?probe=e192547cd3) | Feb 17, 2023 |
| Alienware     | 17 R2                       | Notebook    | [a70da6118b](https://linux-hardware.org/?probe=a70da6118b) | Feb 16, 2023 |
| Dell          | System Inspiron N7110       | Notebook    | [a59b4a2c12](https://linux-hardware.org/?probe=a59b4a2c12) | Feb 16, 2023 |
| ASUSTek       | X75VD                       | Notebook    | [81c64d5916](https://linux-hardware.org/?probe=81c64d5916) | Feb 16, 2023 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | Notebook    | [6f0ca25023](https://linux-hardware.org/?probe=6f0ca25023) | Feb 16, 2023 |
| Lenovo        | ThinkPad L13 20R30006PB     | Notebook    | [aad1f06bb9](https://linux-hardware.org/?probe=aad1f06bb9) | Feb 16, 2023 |
| Acer          | Aspire A717-71G             | Notebook    | [488a80bcda](https://linux-hardware.org/?probe=488a80bcda) | Feb 16, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [a16c82308f](https://linux-hardware.org/?probe=a16c82308f) | Feb 16, 2023 |
| Dell          | 0XPDFK A01                  | Desktop     | [146c38cbdf](https://linux-hardware.org/?probe=146c38cbdf) | Feb 16, 2023 |
| Lenovo        | ThinkPad E14 20RAS1AQ00     | Notebook    | [b534643d92](https://linux-hardware.org/?probe=b534643d92) | Feb 16, 2023 |
| Dell          | G15 5515                    | Notebook    | [17ff15f50e](https://linux-hardware.org/?probe=17ff15f50e) | Feb 16, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [361eb28148](https://linux-hardware.org/?probe=361eb28148) | Feb 16, 2023 |
| Pegatron      | SM3330B 0500B               | Desktop     | [701fdae932](https://linux-hardware.org/?probe=701fdae932) | Feb 16, 2023 |
| Gigabyte      | B760I AORUS PRO DDR4        | Desktop     | [62a320f515](https://linux-hardware.org/?probe=62a320f515) | Feb 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [043e92c2ee](https://linux-hardware.org/?probe=043e92c2ee) | Feb 15, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [b2a1267353](https://linux-hardware.org/?probe=b2a1267353) | Feb 15, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [5d2153f4f2](https://linux-hardware.org/?probe=5d2153f4f2) | Feb 14, 2023 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [05bc165699](https://linux-hardware.org/?probe=05bc165699) | Feb 14, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [832920f31b](https://linux-hardware.org/?probe=832920f31b) | Feb 14, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [e6f972234b](https://linux-hardware.org/?probe=e6f972234b) | Feb 14, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [695abe8c65](https://linux-hardware.org/?probe=695abe8c65) | Feb 14, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [02ae55d12c](https://linux-hardware.org/?probe=02ae55d12c) | Feb 13, 2023 |
| Dell          | Inspiron 7400               | Notebook    | [4cc741a70a](https://linux-hardware.org/?probe=4cc741a70a) | Feb 13, 2023 |
| Acer          | Swift SF314-512             | Notebook    | [08a9c049a1](https://linux-hardware.org/?probe=08a9c049a1) | Feb 13, 2023 |
| MSI           | B450M MORTAR                | Desktop     | [5b93510482](https://linux-hardware.org/?probe=5b93510482) | Feb 13, 2023 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [d517411fc5](https://linux-hardware.org/?probe=d517411fc5) | Feb 13, 2023 |
| HP            | ProBook 6470b               | Notebook    | [e747086309](https://linux-hardware.org/?probe=e747086309) | Feb 13, 2023 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [920b8786c6](https://linux-hardware.org/?probe=920b8786c6) | Feb 13, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [23eec2d2bc](https://linux-hardware.org/?probe=23eec2d2bc) | Feb 13, 2023 |
| Gigabyte      | B560 HD3                    | Desktop     | [067646f7f8](https://linux-hardware.org/?probe=067646f7f8) | Feb 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [50163cfc72](https://linux-hardware.org/?probe=50163cfc72) | Feb 12, 2023 |
| HP            | ProBook 440 G5              | Notebook    | [566c6a5316](https://linux-hardware.org/?probe=566c6a5316) | Feb 12, 2023 |
| HP            | ProBook 440 G5              | Notebook    | [a833fa9a0c](https://linux-hardware.org/?probe=a833fa9a0c) | Feb 12, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [3542104e07](https://linux-hardware.org/?probe=3542104e07) | Feb 12, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [874ccdcf1a](https://linux-hardware.org/?probe=874ccdcf1a) | Feb 12, 2023 |
| MSI           | GE62VR 6RF                  | Notebook    | [89c148a5f9](https://linux-hardware.org/?probe=89c148a5f9) | Feb 12, 2023 |
| Lenovo        | ThinkPad T450 20BV0001US    | Notebook    | [d149fd1ed6](https://linux-hardware.org/?probe=d149fd1ed6) | Feb 12, 2023 |
| HP            | 3397                        | Desktop     | [cc5cdaf09b](https://linux-hardware.org/?probe=cc5cdaf09b) | Feb 12, 2023 |
| Google        | Blooguard                   | Notebook    | [b4cdae3965](https://linux-hardware.org/?probe=b4cdae3965) | Feb 11, 2023 |
| Intel         | NUC12WSBi5 M46425-303       | Mini pc     | [dec32b9b60](https://linux-hardware.org/?probe=dec32b9b60) | Feb 11, 2023 |
| Gigabyte      | GB-BKi5(H)A-7200            | Notebook    | [57ff1b0fe3](https://linux-hardware.org/?probe=57ff1b0fe3) | Feb 11, 2023 |
| HP            | Notebook                    | Notebook    | [94c42af775](https://linux-hardware.org/?probe=94c42af775) | Feb 11, 2023 |
| Lenovo        | ZHAOYANG K4e-ITL 82Q1       | Notebook    | [4ab5181634](https://linux-hardware.org/?probe=4ab5181634) | Feb 11, 2023 |
| HP            | Notebook                    | Notebook    | [e19e0407ec](https://linux-hardware.org/?probe=e19e0407ec) | Feb 11, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [3af9191e4f](https://linux-hardware.org/?probe=3af9191e4f) | Feb 11, 2023 |
| ASUSTek       | ET2400IN-1G                 | All in one  | [c65e5f04d0](https://linux-hardware.org/?probe=c65e5f04d0) | Feb 11, 2023 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [b2c120d8d7](https://linux-hardware.org/?probe=b2c120d8d7) | Feb 11, 2023 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [1942c9f528](https://linux-hardware.org/?probe=1942c9f528) | Feb 11, 2023 |
| HP            | Notebook                    | Notebook    | [4daf49165c](https://linux-hardware.org/?probe=4daf49165c) | Feb 10, 2023 |
| Gigabyte      | B660M GAMING X DDR4         | Desktop     | [845d2e4d52](https://linux-hardware.org/?probe=845d2e4d52) | Feb 10, 2023 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [a19717f948](https://linux-hardware.org/?probe=a19717f948) | Feb 10, 2023 |
| HP            | Laptop 15-da2xxx            | Notebook    | [200150e4e3](https://linux-hardware.org/?probe=200150e4e3) | Feb 10, 2023 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | Desktop     | [f493bc6d9d](https://linux-hardware.org/?probe=f493bc6d9d) | Feb 10, 2023 |
| HP            | 86F0 11000                  | All in one  | [2fab63e976](https://linux-hardware.org/?probe=2fab63e976) | Feb 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | Notebook    | [e3ea6ad8da](https://linux-hardware.org/?probe=e3ea6ad8da) | Feb 10, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [5b22c1a20a](https://linux-hardware.org/?probe=5b22c1a20a) | Feb 09, 2023 |
| MSI           | GS73 Stealth 8RF            | Notebook    | [ccbec1376d](https://linux-hardware.org/?probe=ccbec1376d) | Feb 09, 2023 |
| MSI           | GS73 Stealth 8RF            | Notebook    | [0d5a38a089](https://linux-hardware.org/?probe=0d5a38a089) | Feb 09, 2023 |
| Gigabyte      | B560 HD3                    | Desktop     | [b4fa86401f](https://linux-hardware.org/?probe=b4fa86401f) | Feb 09, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [552d730c6d](https://linux-hardware.org/?probe=552d730c6d) | Feb 09, 2023 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | Notebook    | [b79b2f3f75](https://linux-hardware.org/?probe=b79b2f3f75) | Feb 09, 2023 |
| Dell          | XPS 17 9720                 | Notebook    | [3d1b70c4af](https://linux-hardware.org/?probe=3d1b70c4af) | Feb 08, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [ee5a11ee81](https://linux-hardware.org/?probe=ee5a11ee81) | Feb 08, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [5df3b5ad7e](https://linux-hardware.org/?probe=5df3b5ad7e) | Feb 08, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [518a58b5ca](https://linux-hardware.org/?probe=518a58b5ca) | Feb 08, 2023 |
| Acer          | Swift SF314-512             | Notebook    | [556b064487](https://linux-hardware.org/?probe=556b064487) | Feb 07, 2023 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [be25e0c930](https://linux-hardware.org/?probe=be25e0c930) | Feb 07, 2023 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [d139473252](https://linux-hardware.org/?probe=d139473252) | Feb 07, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [7dcb345b45](https://linux-hardware.org/?probe=7dcb345b45) | Feb 06, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [8c3dd4055e](https://linux-hardware.org/?probe=8c3dd4055e) | Feb 06, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [c454139724](https://linux-hardware.org/?probe=c454139724) | Feb 06, 2023 |
| Gigabyte      | H170-D3HP-CF                | Desktop     | [223378c538](https://linux-hardware.org/?probe=223378c538) | Feb 06, 2023 |
| Lenovo        | ThinkPad T470 20HES3X300    | Notebook    | [6a77ec4c4f](https://linux-hardware.org/?probe=6a77ec4c4f) | Feb 06, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [00006691a6](https://linux-hardware.org/?probe=00006691a6) | Feb 05, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [bb420e8f71](https://linux-hardware.org/?probe=bb420e8f71) | Feb 05, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [ce7bdb0a98](https://linux-hardware.org/?probe=ce7bdb0a98) | Feb 05, 2023 |
| ECS           | H81H3-MV                    | Desktop     | [e60810d8e6](https://linux-hardware.org/?probe=e60810d8e6) | Feb 05, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [5f59acbf0d](https://linux-hardware.org/?probe=5f59acbf0d) | Feb 05, 2023 |
| ONN           | 100002435                   | Tablet      | [35d8a4ce58](https://linux-hardware.org/?probe=35d8a4ce58) | Feb 05, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [c614e44344](https://linux-hardware.org/?probe=c614e44344) | Feb 05, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [ad59fdb4e4](https://linux-hardware.org/?probe=ad59fdb4e4) | Feb 05, 2023 |
| HP            | G60                         | Notebook    | [518195af9f](https://linux-hardware.org/?probe=518195af9f) | Feb 04, 2023 |
| Lenovo        | IdeaPad U310 Touch          | Notebook    | [6fd17687a4](https://linux-hardware.org/?probe=6fd17687a4) | Feb 04, 2023 |
| HP            | 0AACh                       | Desktop     | [86d994993f](https://linux-hardware.org/?probe=86d994993f) | Feb 03, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [27d852788e](https://linux-hardware.org/?probe=27d852788e) | Feb 03, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [2ed6b9969d](https://linux-hardware.org/?probe=2ed6b9969d) | Feb 03, 2023 |
| ASUSTek       | X550JK                      | Notebook    | [c42e4eb249](https://linux-hardware.org/?probe=c42e4eb249) | Feb 03, 2023 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [2aa4452578](https://linux-hardware.org/?probe=2aa4452578) | Feb 02, 2023 |
| Chuwi         | Hi10 Go                     | Notebook    | [a1b6911dc1](https://linux-hardware.org/?probe=a1b6911dc1) | Feb 02, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [a84d546f50](https://linux-hardware.org/?probe=a84d546f50) | Feb 02, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [c91d5b265b](https://linux-hardware.org/?probe=c91d5b265b) | Feb 02, 2023 |
| Lenovo        | ThinkPad T460 20FMS66R00    | Notebook    | [293690383a](https://linux-hardware.org/?probe=293690383a) | Feb 02, 2023 |
| Dell          | Vostro 15-3568              | Notebook    | [caf63a9d0f](https://linux-hardware.org/?probe=caf63a9d0f) | Feb 02, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [690d45db9f](https://linux-hardware.org/?probe=690d45db9f) | Feb 02, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [ef1817a829](https://linux-hardware.org/?probe=ef1817a829) | Feb 02, 2023 |
| Lenovo        | ThinkPad W530 2463A49       | Notebook    | [374c21a672](https://linux-hardware.org/?probe=374c21a672) | Feb 02, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [4b6904f9b1](https://linux-hardware.org/?probe=4b6904f9b1) | Feb 01, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [d186290a3f](https://linux-hardware.org/?probe=d186290a3f) | Feb 01, 2023 |
| Dell          | Precision 7540              | Notebook    | [1d0d197808](https://linux-hardware.org/?probe=1d0d197808) | Feb 01, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [ab92a33bdf](https://linux-hardware.org/?probe=ab92a33bdf) | Feb 01, 2023 |
| HP            | 0AACh                       | Desktop     | [f41abcf7f9](https://linux-hardware.org/?probe=f41abcf7f9) | Feb 01, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [7e78833b8b](https://linux-hardware.org/?probe=7e78833b8b) | Feb 01, 2023 |
| Medion        | E15410                      | Notebook    | [24135c324e](https://linux-hardware.org/?probe=24135c324e) | Jan 31, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [ebbe861495](https://linux-hardware.org/?probe=ebbe861495) | Jan 31, 2023 |
| HP            | Notebook                    | Notebook    | [f352309997](https://linux-hardware.org/?probe=f352309997) | Jan 31, 2023 |
| HP            | 0AACh                       | Desktop     | [32961ffb11](https://linux-hardware.org/?probe=32961ffb11) | Jan 31, 2023 |
| Google        | Lillipup                    | Notebook    | [45f9b8c3cf](https://linux-hardware.org/?probe=45f9b8c3cf) | Jan 31, 2023 |
| Acer          | Aspire AV14-51              | Notebook    | [fa801eea4b](https://linux-hardware.org/?probe=fa801eea4b) | Jan 31, 2023 |
| HP            | 0AACh                       | Desktop     | [94baf3c57c](https://linux-hardware.org/?probe=94baf3c57c) | Jan 31, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [949ea399fb](https://linux-hardware.org/?probe=949ea399fb) | Jan 31, 2023 |
| HP            | 829A                        | Mini pc     | [a6925c200b](https://linux-hardware.org/?probe=a6925c200b) | Jan 31, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [96671141f9](https://linux-hardware.org/?probe=96671141f9) | Jan 30, 2023 |
| MSI           | GS66 Stealth 10SE           | Notebook    | [bf112866e3](https://linux-hardware.org/?probe=bf112866e3) | Jan 30, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [b3c357b53b](https://linux-hardware.org/?probe=b3c357b53b) | Jan 30, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | Notebook    | [942c001b11](https://linux-hardware.org/?probe=942c001b11) | Jan 30, 2023 |
| ASUSTek       | P8P67 DELUXE                | Desktop     | [8f3278e68a](https://linux-hardware.org/?probe=8f3278e68a) | Jan 30, 2023 |
| Acer          | Swift SF114-31              | Notebook    | [9d7f73242e](https://linux-hardware.org/?probe=9d7f73242e) | Jan 30, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | Notebook    | [2f0ffeb3be](https://linux-hardware.org/?probe=2f0ffeb3be) | Jan 29, 2023 |
| Lenovo        | ThinkPad T580 20LA0025MX    | Notebook    | [c5e4274143](https://linux-hardware.org/?probe=c5e4274143) | Jan 29, 2023 |
| Lenovo        | IdeaPad 720S-14IKB 81BD     | Notebook    | [50eb066d41](https://linux-hardware.org/?probe=50eb066d41) | Jan 29, 2023 |
| Acer          | Nitro AN517-41              | Notebook    | [ecb7c49d2e](https://linux-hardware.org/?probe=ecb7c49d2e) | Jan 29, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [175211d52c](https://linux-hardware.org/?probe=175211d52c) | Jan 29, 2023 |
| Lenovo        | NO DPK                      | Desktop     | [0abc762f30](https://linux-hardware.org/?probe=0abc762f30) | Jan 28, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [a011ba3b9e](https://linux-hardware.org/?probe=a011ba3b9e) | Jan 28, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [1a9e67408e](https://linux-hardware.org/?probe=1a9e67408e) | Jan 28, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [f447127e74](https://linux-hardware.org/?probe=f447127e74) | Jan 28, 2023 |
| AZW           | GTR V02                     | Desktop     | [b1b34f10a2](https://linux-hardware.org/?probe=b1b34f10a2) | Jan 28, 2023 |
| MSI           | B560M PRO-VDH               | Desktop     | [cd55d1ec5d](https://linux-hardware.org/?probe=cd55d1ec5d) | Jan 28, 2023 |
| Dell          | Precision 7730              | Notebook    | [058f16ac84](https://linux-hardware.org/?probe=058f16ac84) | Jan 28, 2023 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [fa464af5fb](https://linux-hardware.org/?probe=fa464af5fb) | Jan 27, 2023 |
| Dell          | Inspiron 5593               | Notebook    | [36db3e5d78](https://linux-hardware.org/?probe=36db3e5d78) | Jan 27, 2023 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [b265f91d10](https://linux-hardware.org/?probe=b265f91d10) | Jan 27, 2023 |
| Dell          | 0XPDFK A01                  | Desktop     | [4611591cc9](https://linux-hardware.org/?probe=4611591cc9) | Jan 27, 2023 |
| HP            | 3397                        | Desktop     | [764f737fcf](https://linux-hardware.org/?probe=764f737fcf) | Jan 27, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [32a666b611](https://linux-hardware.org/?probe=32a666b611) | Jan 27, 2023 |
| ASUSTek       | GL503VD                     | Notebook    | [f4095c61ff](https://linux-hardware.org/?probe=f4095c61ff) | Jan 26, 2023 |
| Acer          | Nitro AN517-55              | Notebook    | [7273b8320c](https://linux-hardware.org/?probe=7273b8320c) | Jan 26, 2023 |
| HP            | 3397                        | Desktop     | [10b6614763](https://linux-hardware.org/?probe=10b6614763) | Jan 26, 2023 |
| Acer          | Nitro AN517-55              | Notebook    | [2de4e60fef](https://linux-hardware.org/?probe=2de4e60fef) | Jan 26, 2023 |
| Medion        | E15410                      | Notebook    | [5ba9ffd6a8](https://linux-hardware.org/?probe=5ba9ffd6a8) | Jan 26, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [7403ca2f73](https://linux-hardware.org/?probe=7403ca2f73) | Jan 25, 2023 |
| Lenovo        | ThinkPad L380 20M6S2YE00    | Notebook    | [e6c626133e](https://linux-hardware.org/?probe=e6c626133e) | Jan 25, 2023 |
| TrekStor      | Surfbook A13B               | Notebook    | [4306d9ba1c](https://linux-hardware.org/?probe=4306d9ba1c) | Jan 25, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [b7dea81a92](https://linux-hardware.org/?probe=b7dea81a92) | Jan 25, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [34882391f3](https://linux-hardware.org/?probe=34882391f3) | Jan 25, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [6462d71b74](https://linux-hardware.org/?probe=6462d71b74) | Jan 25, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [18d42efe40](https://linux-hardware.org/?probe=18d42efe40) | Jan 24, 2023 |
| Dell          | 0Y2K8N A00                  | Desktop     | [7f135346af](https://linux-hardware.org/?probe=7f135346af) | Jan 24, 2023 |
| MSI           | MS-B1831                    | Desktop     | [64348a9180](https://linux-hardware.org/?probe=64348a9180) | Jan 24, 2023 |
| Dell          | Latitude 5491               | Notebook    | [37746d7f71](https://linux-hardware.org/?probe=37746d7f71) | Jan 24, 2023 |
| Medion        | E15410                      | Notebook    | [f7e27f2ba9](https://linux-hardware.org/?probe=f7e27f2ba9) | Jan 23, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [b20da22e41](https://linux-hardware.org/?probe=b20da22e41) | Jan 23, 2023 |
| Lenovo        | ThinkPad X260 20F5S28R00    | Notebook    | [4f83721cab](https://linux-hardware.org/?probe=4f83721cab) | Jan 23, 2023 |
| Lenovo        | ThinkPad X260 20F5S28R00    | Notebook    | [9e12a145fd](https://linux-hardware.org/?probe=9e12a145fd) | Jan 23, 2023 |
| HP            | ProBook 6470b               | Notebook    | [3319221b9c](https://linux-hardware.org/?probe=3319221b9c) | Jan 23, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [3951ddfe72](https://linux-hardware.org/?probe=3951ddfe72) | Jan 23, 2023 |
| MSI           | MS-AEC21                    | All in one  | [e541cd3043](https://linux-hardware.org/?probe=e541cd3043) | Jan 23, 2023 |
| MACHENIKE     | MACHCREATOR-16              | Notebook    | [df35617170](https://linux-hardware.org/?probe=df35617170) | Jan 22, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [8d5c313d43](https://linux-hardware.org/?probe=8d5c313d43) | Jan 22, 2023 |
| HP            | ProBook 6570b               | Notebook    | [3bc0488b6d](https://linux-hardware.org/?probe=3bc0488b6d) | Jan 22, 2023 |
| Dell          | Latitude E6430s             | Notebook    | [8f9185a327](https://linux-hardware.org/?probe=8f9185a327) | Jan 22, 2023 |
| Carbon Sys... | Iridium 14                  | Notebook    | [7fcc79f37c](https://linux-hardware.org/?probe=7fcc79f37c) | Jan 22, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [d2b797f3de](https://linux-hardware.org/?probe=d2b797f3de) | Jan 21, 2023 |
| Dell          | Vostro 1014                 | Notebook    | [f7ff3312f2](https://linux-hardware.org/?probe=f7ff3312f2) | Jan 21, 2023 |
| Acer          | TravelMate B118-M           | Notebook    | [029850a46e](https://linux-hardware.org/?probe=029850a46e) | Jan 21, 2023 |
| Dell          | Vostro 1014                 | Notebook    | [724939f0cf](https://linux-hardware.org/?probe=724939f0cf) | Jan 21, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [bfaffed5d2](https://linux-hardware.org/?probe=bfaffed5d2) | Jan 21, 2023 |
| Gigabyte      | X570S AORUS MASTER          | Desktop     | [a6f80e64b2](https://linux-hardware.org/?probe=a6f80e64b2) | Jan 21, 2023 |
| Lenovo        | 3148 SDK0L22692 WIN 3792... | Desktop     | [f66c33020e](https://linux-hardware.org/?probe=f66c33020e) | Jan 21, 2023 |
| MSI           | Prestige 15 A12SC           | Notebook    | [b368e80a36](https://linux-hardware.org/?probe=b368e80a36) | Jan 21, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [29d770594e](https://linux-hardware.org/?probe=29d770594e) | Jan 21, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [0072a47bce](https://linux-hardware.org/?probe=0072a47bce) | Jan 20, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [732a1b992a](https://linux-hardware.org/?probe=732a1b992a) | Jan 20, 2023 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [49f0bb23ea](https://linux-hardware.org/?probe=49f0bb23ea) | Jan 20, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [28b4d041ad](https://linux-hardware.org/?probe=28b4d041ad) | Jan 20, 2023 |
| Dell          | Latitude 5320               | Notebook    | [aaf625ee63](https://linux-hardware.org/?probe=aaf625ee63) | Jan 20, 2023 |
| Sony          | SVE1513B4E                  | Notebook    | [cbd9f98f30](https://linux-hardware.org/?probe=cbd9f98f30) | Jan 20, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [2b7ce5b726](https://linux-hardware.org/?probe=2b7ce5b726) | Jan 20, 2023 |
| Dell          | 03NVJ6 A03                  | Desktop     | [4269f0e624](https://linux-hardware.org/?probe=4269f0e624) | Jan 20, 2023 |
| Dell          | G3 3779                     | Notebook    | [c4c13ca86b](https://linux-hardware.org/?probe=c4c13ca86b) | Jan 19, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [d9e9f47ad4](https://linux-hardware.org/?probe=d9e9f47ad4) | Jan 19, 2023 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [a9d66d6af6](https://linux-hardware.org/?probe=a9d66d6af6) | Jan 18, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [0bc976587f](https://linux-hardware.org/?probe=0bc976587f) | Jan 18, 2023 |
| HP            | Notebook                    | Notebook    | [1c935be3b1](https://linux-hardware.org/?probe=1c935be3b1) | Jan 18, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [3dfd98d007](https://linux-hardware.org/?probe=3dfd98d007) | Jan 17, 2023 |
| ASRock        | Z370 Killer SLI/ac          | Desktop     | [8f20499728](https://linux-hardware.org/?probe=8f20499728) | Jan 17, 2023 |
| Dell          | 0D881F A05                  | Desktop     | [0426ee9130](https://linux-hardware.org/?probe=0426ee9130) | Jan 17, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [dcbf101b59](https://linux-hardware.org/?probe=dcbf101b59) | Jan 17, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [3964c82d71](https://linux-hardware.org/?probe=3964c82d71) | Jan 17, 2023 |
| ASUSTek       | Zenbook UM6702RC_RM6702R... | Notebook    | [21ed6bd75d](https://linux-hardware.org/?probe=21ed6bd75d) | Jan 17, 2023 |
| HP            | Laptop 17-by3xxx            | Notebook    | [542c3d1ef4](https://linux-hardware.org/?probe=542c3d1ef4) | Jan 16, 2023 |
| Gigabyte      | B650M DS3H                  | Desktop     | [8493fa353c](https://linux-hardware.org/?probe=8493fa353c) | Jan 16, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [3f24b17bd8](https://linux-hardware.org/?probe=3f24b17bd8) | Jan 16, 2023 |
| Acer          | Aspire V3-571G              | Notebook    | [3715650f46](https://linux-hardware.org/?probe=3715650f46) | Jan 16, 2023 |
| ASUSTek       | P5K/EPU                     | Desktop     | [c159b4d65b](https://linux-hardware.org/?probe=c159b4d65b) | Jan 16, 2023 |
| Acer          | Swift SF113-31              | Notebook    | [de76cee99a](https://linux-hardware.org/?probe=de76cee99a) | Jan 16, 2023 |
| Dell          | 06D7TR A00                  | Desktop     | [bf8115e391](https://linux-hardware.org/?probe=bf8115e391) | Jan 15, 2023 |
| Dynabook      | Satellite Pro C50-J         | Notebook    | [ba8e771128](https://linux-hardware.org/?probe=ba8e771128) | Jan 15, 2023 |
| Notebook      | W35xSS_370SS                | Notebook    | [2337667e0f](https://linux-hardware.org/?probe=2337667e0f) | Jan 15, 2023 |
| Acer          | Nitro AN515-43              | Notebook    | [4621c0d31b](https://linux-hardware.org/?probe=4621c0d31b) | Jan 15, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [86039b3063](https://linux-hardware.org/?probe=86039b3063) | Jan 15, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [7d0bdd8606](https://linux-hardware.org/?probe=7d0bdd8606) | Jan 15, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [614c167f82](https://linux-hardware.org/?probe=614c167f82) | Jan 15, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [2687f89612](https://linux-hardware.org/?probe=2687f89612) | Jan 14, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [aa35c556bc](https://linux-hardware.org/?probe=aa35c556bc) | Jan 13, 2023 |
| ASUSTek       | Z97-P                       | Desktop     | [709045636c](https://linux-hardware.org/?probe=709045636c) | Jan 13, 2023 |
| MSI           | B350 PC MATE                | Desktop     | [77a4e207cd](https://linux-hardware.org/?probe=77a4e207cd) | Jan 13, 2023 |
| ASUSTek       | G10AJ                       | Desktop     | [e300c19806](https://linux-hardware.org/?probe=e300c19806) | Jan 13, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [c3a30838c3](https://linux-hardware.org/?probe=c3a30838c3) | Jan 13, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [3a97589bc9](https://linux-hardware.org/?probe=3a97589bc9) | Jan 12, 2023 |
| Dell          | 0GXM1W A01                  | Desktop     | [dc468fd3a8](https://linux-hardware.org/?probe=dc468fd3a8) | Jan 12, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [1b1fee733e](https://linux-hardware.org/?probe=1b1fee733e) | Jan 12, 2023 |
| Dell          | Latitude 3420               | Notebook    | [53b3f46e20](https://linux-hardware.org/?probe=53b3f46e20) | Jan 12, 2023 |
| Alienware     | 0H869M A00                  | Desktop     | [6dc1967760](https://linux-hardware.org/?probe=6dc1967760) | Jan 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [ed648f1f72](https://linux-hardware.org/?probe=ed648f1f72) | Jan 12, 2023 |
| Lenovo        | ThinkPad L430 24663D1       | Notebook    | [1987221c12](https://linux-hardware.org/?probe=1987221c12) | Jan 12, 2023 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [6286dbdb0b](https://linux-hardware.org/?probe=6286dbdb0b) | Jan 11, 2023 |
| ASUSTek       | P5K/EPU                     | Desktop     | [c6ffd59fb2](https://linux-hardware.org/?probe=c6ffd59fb2) | Jan 11, 2023 |
| MSI           | Bravo 17 A4DDK              | Notebook    | [ca27b9dd46](https://linux-hardware.org/?probe=ca27b9dd46) | Jan 10, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [c5e0e8163f](https://linux-hardware.org/?probe=c5e0e8163f) | Jan 10, 2023 |
| Google        | Rammus                      | Notebook    | [489d09eaa7](https://linux-hardware.org/?probe=489d09eaa7) | Jan 10, 2023 |
| Gigabyte      | F2A88XM-HD3P                | Desktop     | [8434b565c3](https://linux-hardware.org/?probe=8434b565c3) | Jan 10, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [1a619ff898](https://linux-hardware.org/?probe=1a619ff898) | Jan 10, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [b9df733a47](https://linux-hardware.org/?probe=b9df733a47) | Jan 10, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [75209e7521](https://linux-hardware.org/?probe=75209e7521) | Jan 10, 2023 |
| HP            | ProBook 6570b               | Notebook    | [e5c0ea26d1](https://linux-hardware.org/?probe=e5c0ea26d1) | Jan 09, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [5d3f8e9948](https://linux-hardware.org/?probe=5d3f8e9948) | Jan 09, 2023 |
| ASUSTek       | Zenbook UN5401RA UN5401R... | Convertible | [a43ad3cbf7](https://linux-hardware.org/?probe=a43ad3cbf7) | Jan 09, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [774322328a](https://linux-hardware.org/?probe=774322328a) | Jan 09, 2023 |
| Dell          | Inspiron 5575               | Notebook    | [5bc41d3659](https://linux-hardware.org/?probe=5bc41d3659) | Jan 09, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [d94fa63122](https://linux-hardware.org/?probe=d94fa63122) | Jan 08, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [3b3f695b94](https://linux-hardware.org/?probe=3b3f695b94) | Jan 08, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [eb562a1e24](https://linux-hardware.org/?probe=eb562a1e24) | Jan 08, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [4ebc1e97c5](https://linux-hardware.org/?probe=4ebc1e97c5) | Jan 07, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [86b0308f38](https://linux-hardware.org/?probe=86b0308f38) | Jan 07, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [fc7a1958c4](https://linux-hardware.org/?probe=fc7a1958c4) | Jan 07, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [929ff5acbb](https://linux-hardware.org/?probe=929ff5acbb) | Jan 07, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [1ff445305d](https://linux-hardware.org/?probe=1ff445305d) | Jan 06, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [c7a6fdbf55](https://linux-hardware.org/?probe=c7a6fdbf55) | Jan 06, 2023 |
| MSI           | MEG Z490 UNIFY              | Desktop     | [cb25b352e0](https://linux-hardware.org/?probe=cb25b352e0) | Jan 06, 2023 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [aae608e132](https://linux-hardware.org/?probe=aae608e132) | Jan 06, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [e4f0b0506b](https://linux-hardware.org/?probe=e4f0b0506b) | Jan 06, 2023 |
| Microsoft     | Surface Laptop              | Tablet      | [391d13c7ba](https://linux-hardware.org/?probe=391d13c7ba) | Jan 06, 2023 |
| Lenovo        | Legion 5 17ACH6 82K0        | Notebook    | [9a108faf93](https://linux-hardware.org/?probe=9a108faf93) | Jan 06, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [78ab02a131](https://linux-hardware.org/?probe=78ab02a131) | Jan 05, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [ce4648337e](https://linux-hardware.org/?probe=ce4648337e) | Jan 05, 2023 |
| Dell          | 0WPMFG A00                  | Desktop     | [02a8ab8bdc](https://linux-hardware.org/?probe=02a8ab8bdc) | Jan 05, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [c19db82125](https://linux-hardware.org/?probe=c19db82125) | Jan 05, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [697abed1c0](https://linux-hardware.org/?probe=697abed1c0) | Jan 05, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [efb1372825](https://linux-hardware.org/?probe=efb1372825) | Jan 05, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [1c58ea8841](https://linux-hardware.org/?probe=1c58ea8841) | Jan 05, 2023 |
| Acer          | Swift SF314-71              | Notebook    | [21ebb26df9](https://linux-hardware.org/?probe=21ebb26df9) | Jan 05, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [90cbbe6b1d](https://linux-hardware.org/?probe=90cbbe6b1d) | Jan 04, 2023 |
| HP            | 250 G4 Notebook PC          | Notebook    | [a6d6683371](https://linux-hardware.org/?probe=a6d6683371) | Jan 04, 2023 |
| HP            | 250 G4 Notebook PC          | Notebook    | [08526a890a](https://linux-hardware.org/?probe=08526a890a) | Jan 04, 2023 |
| Dell          | Inspiron 5406 2n1           | Convertible | [e780ec3e2a](https://linux-hardware.org/?probe=e780ec3e2a) | Jan 04, 2023 |
| Notebook      | NP5x_NP6x_NP7xPNK_PNH_PN... | Notebook    | [ace1cd7d4d](https://linux-hardware.org/?probe=ace1cd7d4d) | Jan 04, 2023 |
| Acer          | Aspire M5-583P              | Notebook    | [1182d7305d](https://linux-hardware.org/?probe=1182d7305d) | Jan 04, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [2e047c3ad5](https://linux-hardware.org/?probe=2e047c3ad5) | Jan 04, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [e24802533e](https://linux-hardware.org/?probe=e24802533e) | Jan 03, 2023 |
| Unknown       | Unknown                     | Notebook    | [7a85f424f5](https://linux-hardware.org/?probe=7a85f424f5) | Jan 03, 2023 |
| HUAWEI        | NBLL-WXX9                   | Notebook    | [7e5acbf050](https://linux-hardware.org/?probe=7e5acbf050) | Jan 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [059e72c9a0](https://linux-hardware.org/?probe=059e72c9a0) | Jan 03, 2023 |
| MSI           | Raider GE76 12UGS           | Notebook    | [8552e25872](https://linux-hardware.org/?probe=8552e25872) | Jan 03, 2023 |
| Acer          | Aspire M5-481T              | Notebook    | [2e2e7afb8a](https://linux-hardware.org/?probe=2e2e7afb8a) | Jan 03, 2023 |
| ASUSTek       | G56JR                       | Notebook    | [d8d521b964](https://linux-hardware.org/?probe=d8d521b964) | Jan 03, 2023 |
| Acer          | Aspire M5-481T              | Notebook    | [54bd1d5aae](https://linux-hardware.org/?probe=54bd1d5aae) | Jan 03, 2023 |
| Dell          | Inspiron 5515               | Notebook    | [27a4df28b2](https://linux-hardware.org/?probe=27a4df28b2) | Jan 03, 2023 |
| MSI           | Alpha 17 B5EEK              | Notebook    | [a5881c627c](https://linux-hardware.org/?probe=a5881c627c) | Jan 03, 2023 |
| ASUSTek       | G56JR                       | Notebook    | [ccebb5dd27](https://linux-hardware.org/?probe=ccebb5dd27) | Jan 02, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [54403a8bbf](https://linux-hardware.org/?probe=54403a8bbf) | Jan 02, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [a35156e0c3](https://linux-hardware.org/?probe=a35156e0c3) | Jan 02, 2023 |
| HP            | ENVY TS 15                  | Notebook    | [3140fe0512](https://linux-hardware.org/?probe=3140fe0512) | Jan 02, 2023 |
| MSI           | Prestige 14 A10RAS          | Notebook    | [fc119df9bc](https://linux-hardware.org/?probe=fc119df9bc) | Jan 02, 2023 |
| MSI           | B350 PC MATE                | Desktop     | [20c4d1a764](https://linux-hardware.org/?probe=20c4d1a764) | Jan 02, 2023 |
| ASUSTek       | G10DK                       | Desktop     | [e75694d9a6](https://linux-hardware.org/?probe=e75694d9a6) | Jan 02, 2023 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [0fb41a5066](https://linux-hardware.org/?probe=0fb41a5066) | Jan 02, 2023 |
| Gigabyte      | Z590 UD AC                  | Desktop     | [9346b2e1bc](https://linux-hardware.org/?probe=9346b2e1bc) | Jan 01, 2023 |
| MSI           | Raider GE67HX 12UGS         | Notebook    | [be85c7b42a](https://linux-hardware.org/?probe=be85c7b42a) | Jan 01, 2023 |
| HP            | Laptop 15-da2xxx            | Notebook    | [a96e5b892b](https://linux-hardware.org/?probe=a96e5b892b) | Jan 01, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [a5b2453630](https://linux-hardware.org/?probe=a5b2453630) | Jan 01, 2023 |
| Lenovo        | ThinkPad L430 24663D1       | Notebook    | [8eada9744e](https://linux-hardware.org/?probe=8eada9744e) | Jan 01, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [09d6510700](https://linux-hardware.org/?probe=09d6510700) | Jan 01, 2023 |
| ASUSTek       | G15CF                       | Desktop     | [93e783c74a](https://linux-hardware.org/?probe=93e783c74a) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [2c31fd54e4](https://linux-hardware.org/?probe=2c31fd54e4) | Jan 01, 2023 |
| Acer          | Spin SP513-54N              | Convertible | [0cb6dfa7ce](https://linux-hardware.org/?probe=0cb6dfa7ce) | Dec 31, 2022 |
| Dell          | 0PTTT9 A00                  | Desktop     | [7f2851fcf5](https://linux-hardware.org/?probe=7f2851fcf5) | Dec 31, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [c4eccac7c7](https://linux-hardware.org/?probe=c4eccac7c7) | Dec 31, 2022 |
| MSI           | B360M BAZOOKA               | Desktop     | [ad26afeb83](https://linux-hardware.org/?probe=ad26afeb83) | Dec 31, 2022 |
| HP            | Notebook                    | Notebook    | [d25df9daf4](https://linux-hardware.org/?probe=d25df9daf4) | Dec 31, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [d326e34afc](https://linux-hardware.org/?probe=d326e34afc) | Dec 31, 2022 |
| Acer          | Aspire A315-41              | Notebook    | [9cddb65ac1](https://linux-hardware.org/?probe=9cddb65ac1) | Dec 30, 2022 |
| Radxa         | ROCK 5B                     | Soc         | [d864d2a31b](https://linux-hardware.org/?probe=d864d2a31b) | Dec 30, 2022 |
| Notebook      | P17SM                       | Notebook    | [18605208b6](https://linux-hardware.org/?probe=18605208b6) | Dec 30, 2022 |
| Lenovo        | ThinkPad T470s 20HGS1JN0... | Notebook    | [049bc54496](https://linux-hardware.org/?probe=049bc54496) | Dec 30, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [5e6dc18098](https://linux-hardware.org/?probe=5e6dc18098) | Dec 30, 2022 |
| Apple         | MacBookPro14,3              | Notebook    | [fdd6af96b3](https://linux-hardware.org/?probe=fdd6af96b3) | Dec 30, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [1c7a329282](https://linux-hardware.org/?probe=1c7a329282) | Dec 30, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [816ab16fd0](https://linux-hardware.org/?probe=816ab16fd0) | Dec 30, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [43e6103cd0](https://linux-hardware.org/?probe=43e6103cd0) | Dec 29, 2022 |
| BESSTAR Te... | HM80                        | Desktop     | [9af0f05e7e](https://linux-hardware.org/?probe=9af0f05e7e) | Dec 29, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | Desktop     | [87e8ae1350](https://linux-hardware.org/?probe=87e8ae1350) | Dec 29, 2022 |
| HP            | Victus by Laptop 16-e1xx... | Notebook    | [25183d70e2](https://linux-hardware.org/?probe=25183d70e2) | Dec 29, 2022 |
| Carbon Sys... | Iridium 14                  | Notebook    | [d2275f6785](https://linux-hardware.org/?probe=d2275f6785) | Dec 29, 2022 |
| HP            | 8399                        | Desktop     | [204c8c0a3f](https://linux-hardware.org/?probe=204c8c0a3f) | Dec 29, 2022 |
| Acer          | Aspire X3960                | Desktop     | [f045d61192](https://linux-hardware.org/?probe=f045d61192) | Dec 29, 2022 |
| Acer          | Aspire X3960                | Desktop     | [75e053c90f](https://linux-hardware.org/?probe=75e053c90f) | Dec 29, 2022 |
| Lenovo        | 3130 SDK0J40697 WIN 3305... | Mini pc     | [52b38cee5c](https://linux-hardware.org/?probe=52b38cee5c) | Dec 28, 2022 |
| Pegatron      | 2AB6                        | Desktop     | [742c9ebcca](https://linux-hardware.org/?probe=742c9ebcca) | Dec 28, 2022 |
| Pegatron      | 2AB6                        | Desktop     | [9e95c7e7c7](https://linux-hardware.org/?probe=9e95c7e7c7) | Dec 28, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [f58bb411b8](https://linux-hardware.org/?probe=f58bb411b8) | Dec 28, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [2c2bf7f512](https://linux-hardware.org/?probe=2c2bf7f512) | Dec 28, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [19f962298b](https://linux-hardware.org/?probe=19f962298b) | Dec 28, 2022 |
| HP            | EliteBook 745 G3            | Notebook    | [1ca2f43148](https://linux-hardware.org/?probe=1ca2f43148) | Dec 27, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [3d9a51ce6e](https://linux-hardware.org/?probe=3d9a51ce6e) | Dec 27, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [9d2542cf36](https://linux-hardware.org/?probe=9d2542cf36) | Dec 27, 2022 |
| Dell          | 0PV9DG A01                  | Server      | [7f408923fa](https://linux-hardware.org/?probe=7f408923fa) | Dec 27, 2022 |
| MSI           | GP62 7QF                    | Notebook    | [3db82bd91e](https://linux-hardware.org/?probe=3db82bd91e) | Dec 27, 2022 |
| ASUSTek       | X550VXK                     | Notebook    | [301db79821](https://linux-hardware.org/?probe=301db79821) | Dec 27, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [f2998cdede](https://linux-hardware.org/?probe=f2998cdede) | Dec 27, 2022 |
| Gigabyte      | 970-GAMING                  | Desktop     | [4a2d0b56d6](https://linux-hardware.org/?probe=4a2d0b56d6) | Dec 27, 2022 |
| HP            | Beats 15                    | Notebook    | [d000f23d61](https://linux-hardware.org/?probe=d000f23d61) | Dec 27, 2022 |
| Dell          | Inspiron 5775               | Notebook    | [cfb1c3fcd6](https://linux-hardware.org/?probe=cfb1c3fcd6) | Dec 26, 2022 |
| Notebook      | NP5x_NP6x_NP7xPNK_PNH_PN... | Notebook    | [792a203576](https://linux-hardware.org/?probe=792a203576) | Dec 26, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [227a5cc570](https://linux-hardware.org/?probe=227a5cc570) | Dec 26, 2022 |
| Gigabyte      | 970-GAMING                  | Desktop     | [9df04c213d](https://linux-hardware.org/?probe=9df04c213d) | Dec 26, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [8d9b11c617](https://linux-hardware.org/?probe=8d9b11c617) | Dec 25, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [d66772a936](https://linux-hardware.org/?probe=d66772a936) | Dec 25, 2022 |
| Acer          | Aspire A517-53              | Notebook    | [e440a77fa7](https://linux-hardware.org/?probe=e440a77fa7) | Dec 25, 2022 |
| Gigabyte      | 970-GAMING                  | Desktop     | [ef0c06d132](https://linux-hardware.org/?probe=ef0c06d132) | Dec 25, 2022 |
| Gigabyte      | 970-GAMING                  | Desktop     | [9de3d146ff](https://linux-hardware.org/?probe=9de3d146ff) | Dec 25, 2022 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [3d538213fc](https://linux-hardware.org/?probe=3d538213fc) | Dec 25, 2022 |
| Dell          | Inspiron 7706 2n1           | Convertible | [7bf95eb194](https://linux-hardware.org/?probe=7bf95eb194) | Dec 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [0413176ecc](https://linux-hardware.org/?probe=0413176ecc) | Dec 25, 2022 |
| BESSTAR Te... | HM90                        | Desktop     | [3672c73d5a](https://linux-hardware.org/?probe=3672c73d5a) | Dec 24, 2022 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [7b8e9fe353](https://linux-hardware.org/?probe=7b8e9fe353) | Dec 24, 2022 |
| Dell          | Latitude 5590               | Notebook    | [f7011844b5](https://linux-hardware.org/?probe=f7011844b5) | Dec 24, 2022 |
| Dell          | Latitude 5590               | Notebook    | [3f1acac04f](https://linux-hardware.org/?probe=3f1acac04f) | Dec 24, 2022 |
| Lenovo        | ThinkPad R61 8918DMG        | Notebook    | [d40595761e](https://linux-hardware.org/?probe=d40595761e) | Dec 24, 2022 |
| Dell          | Latitude 5590               | Notebook    | [e439eb94d4](https://linux-hardware.org/?probe=e439eb94d4) | Dec 24, 2022 |
| Dell          | Latitude 5590               | Notebook    | [816056e28e](https://linux-hardware.org/?probe=816056e28e) | Dec 24, 2022 |
| Lenovo        | ThinkPad T510 4313CTO       | Notebook    | [a3db191efa](https://linux-hardware.org/?probe=a3db191efa) | Dec 24, 2022 |
| ASRock        | X570 Steel Legend           | Desktop     | [7b79249b18](https://linux-hardware.org/?probe=7b79249b18) | Dec 23, 2022 |
| Samsung       | 550P5C/550P7C               | Notebook    | [780cc47e7f](https://linux-hardware.org/?probe=780cc47e7f) | Dec 23, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [6b09c2afcf](https://linux-hardware.org/?probe=6b09c2afcf) | Dec 23, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [efc1b154fb](https://linux-hardware.org/?probe=efc1b154fb) | Dec 23, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [f2197bb9ec](https://linux-hardware.org/?probe=f2197bb9ec) | Dec 23, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [841b610817](https://linux-hardware.org/?probe=841b610817) | Dec 23, 2022 |
| ASUSTek       | Q504UAK                     | Convertible | [af0433651a](https://linux-hardware.org/?probe=af0433651a) | Dec 22, 2022 |
| Lenovo        | IdeaPad 700-17ISK 80RV      | Notebook    | [59bf9e85bf](https://linux-hardware.org/?probe=59bf9e85bf) | Dec 22, 2022 |
| HP            | Pavilion dv7                | Notebook    | [5e5eb2c983](https://linux-hardware.org/?probe=5e5eb2c983) | Dec 22, 2022 |
| SGIN          | laptop                      | Notebook    | [33b93cc75b](https://linux-hardware.org/?probe=33b93cc75b) | Dec 22, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [041cd6f9bd](https://linux-hardware.org/?probe=041cd6f9bd) | Dec 22, 2022 |
| Acer          | Aspire A515-47              | Notebook    | [0ec462e927](https://linux-hardware.org/?probe=0ec462e927) | Dec 21, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [dca79c9d6d](https://linux-hardware.org/?probe=dca79c9d6d) | Dec 21, 2022 |
| Notebook      | NL5xRU                      | Notebook    | [c32538c73b](https://linux-hardware.org/?probe=c32538c73b) | Dec 21, 2022 |
| HP            | Sona                        | Notebook    | [85c88dea70](https://linux-hardware.org/?probe=85c88dea70) | Dec 20, 2022 |
| Timi          | TM1701                      | Notebook    | [49f0865503](https://linux-hardware.org/?probe=49f0865503) | Dec 20, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [3d563943d4](https://linux-hardware.org/?probe=3d563943d4) | Dec 20, 2022 |
| MSI           | X470 GAMING PLUS            | Desktop     | [44cdfa03bf](https://linux-hardware.org/?probe=44cdfa03bf) | Dec 19, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [d5d8eaf2b9](https://linux-hardware.org/?probe=d5d8eaf2b9) | Dec 19, 2022 |
| HP            | Laptop 17-by3xxx            | Notebook    | [5bce63e8cb](https://linux-hardware.org/?probe=5bce63e8cb) | Dec 19, 2022 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [a683e4f3c9](https://linux-hardware.org/?probe=a683e4f3c9) | Dec 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [60a56500f1](https://linux-hardware.org/?probe=60a56500f1) | Dec 18, 2022 |
| Dell          | Precision 5540              | Notebook    | [0e2ce6eb28](https://linux-hardware.org/?probe=0e2ce6eb28) | Dec 17, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [1cbc80c6fb](https://linux-hardware.org/?probe=1cbc80c6fb) | Dec 17, 2022 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [db147cf534](https://linux-hardware.org/?probe=db147cf534) | Dec 17, 2022 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [fa2cc2d975](https://linux-hardware.org/?probe=fa2cc2d975) | Dec 17, 2022 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [c2eff145f7](https://linux-hardware.org/?probe=c2eff145f7) | Dec 17, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [fc473cc90f](https://linux-hardware.org/?probe=fc473cc90f) | Dec 17, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [4d39c63e0a](https://linux-hardware.org/?probe=4d39c63e0a) | Dec 17, 2022 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [9b51850f9d](https://linux-hardware.org/?probe=9b51850f9d) | Dec 17, 2022 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [7739bbf37e](https://linux-hardware.org/?probe=7739bbf37e) | Dec 16, 2022 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [645efe8dd2](https://linux-hardware.org/?probe=645efe8dd2) | Dec 16, 2022 |
| Lenovo        | ThinkPad E15 20RD0011MZ     | Notebook    | [86627d739c](https://linux-hardware.org/?probe=86627d739c) | Dec 16, 2022 |
| Lenovo        | ThinkPad E15 20RD0011MZ     | Notebook    | [ee758acf19](https://linux-hardware.org/?probe=ee758acf19) | Dec 16, 2022 |
| Dell          | 084J0R A00                  | Desktop     | [dabf78159d](https://linux-hardware.org/?probe=dabf78159d) | Dec 15, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [a1a11b56d0](https://linux-hardware.org/?probe=a1a11b56d0) | Dec 15, 2022 |
| Lenovo        | ThinkPad T530 24295XU       | Notebook    | [0ebd945403](https://linux-hardware.org/?probe=0ebd945403) | Dec 15, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [89166d1da4](https://linux-hardware.org/?probe=89166d1da4) | Dec 15, 2022 |
| Lenovo        | NOK                         | Desktop     | [01d1b7fdb7](https://linux-hardware.org/?probe=01d1b7fdb7) | Dec 15, 2022 |
| MSI           | A320M PRO-VD/S              | Desktop     | [9e9573c0c5](https://linux-hardware.org/?probe=9e9573c0c5) | Dec 14, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [76c76bdd82](https://linux-hardware.org/?probe=76c76bdd82) | Dec 14, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [1db7d2fa59](https://linux-hardware.org/?probe=1db7d2fa59) | Dec 14, 2022 |
| Lenovo        | ThinkCentre A70 7844H9G     | Desktop     | [aad5a91184](https://linux-hardware.org/?probe=aad5a91184) | Dec 14, 2022 |
| MSI           | A320M PRO-VD/S              | Desktop     | [c428800285](https://linux-hardware.org/?probe=c428800285) | Dec 14, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [d8d72f23e6](https://linux-hardware.org/?probe=d8d72f23e6) | Dec 14, 2022 |
| Apple         | MacBookPro14,2              | Notebook    | [702a622854](https://linux-hardware.org/?probe=702a622854) | Dec 14, 2022 |
| Lenovo        | ThinkPad T61 7665VJM        | Notebook    | [f1ff113e65](https://linux-hardware.org/?probe=f1ff113e65) | Dec 14, 2022 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [5ac5b0aaa8](https://linux-hardware.org/?probe=5ac5b0aaa8) | Dec 14, 2022 |
| Gigabyte      | Z590 UD AC                  | Desktop     | [895bd1b0b2](https://linux-hardware.org/?probe=895bd1b0b2) | Dec 13, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [c18a20ec35](https://linux-hardware.org/?probe=c18a20ec35) | Dec 13, 2022 |
| Acer          | Nitro AN517-54              | Notebook    | [3896296ad1](https://linux-hardware.org/?probe=3896296ad1) | Dec 12, 2022 |
| Dell          | Precision 5510              | Notebook    | [77b7f6dd95](https://linux-hardware.org/?probe=77b7f6dd95) | Dec 12, 2022 |
| ASUSTek       | H170-PRO                    | Desktop     | [0a28fbd557](https://linux-hardware.org/?probe=0a28fbd557) | Dec 12, 2022 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [dfa4685ecc](https://linux-hardware.org/?probe=dfa4685ecc) | Dec 12, 2022 |
| Acer          | Aspire A515-44              | Notebook    | [965817e5f0](https://linux-hardware.org/?probe=965817e5f0) | Dec 11, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [c5220a0b87](https://linux-hardware.org/?probe=c5220a0b87) | Dec 11, 2022 |
| ASUSTek       | ROG Strix G713RM_G713RM     | Notebook    | [48e21506f4](https://linux-hardware.org/?probe=48e21506f4) | Dec 11, 2022 |
| ASRock        | H570 Steel Legend           | Desktop     | [ef9d66faf0](https://linux-hardware.org/?probe=ef9d66faf0) | Dec 11, 2022 |
| HP            | Pavilion g7                 | Notebook    | [94cc8be22c](https://linux-hardware.org/?probe=94cc8be22c) | Dec 11, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [13434876df](https://linux-hardware.org/?probe=13434876df) | Dec 11, 2022 |
| Acer          | Predator PH317-52           | Notebook    | [e3236b49d3](https://linux-hardware.org/?probe=e3236b49d3) | Dec 10, 2022 |
| Dell          | 02YYK5 A00                  | Desktop     | [1168ac14f5](https://linux-hardware.org/?probe=1168ac14f5) | Dec 09, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [d28d2da00b](https://linux-hardware.org/?probe=d28d2da00b) | Dec 09, 2022 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [474cde3412](https://linux-hardware.org/?probe=474cde3412) | Dec 08, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [3892b54ac4](https://linux-hardware.org/?probe=3892b54ac4) | Dec 08, 2022 |
| Microsoft     | Surface Laptop              | Tablet      | [8745419f51](https://linux-hardware.org/?probe=8745419f51) | Dec 08, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | Notebook    | [c66f0c0c8d](https://linux-hardware.org/?probe=c66f0c0c8d) | Dec 08, 2022 |
| Lenovo        | ThinkPad T420 4236PZ0       | Notebook    | [603c3b47a9](https://linux-hardware.org/?probe=603c3b47a9) | Dec 08, 2022 |
| Lenovo        | ThinkSystem SR358FV2 Res... | Server      | [3702b80721](https://linux-hardware.org/?probe=3702b80721) | Dec 07, 2022 |
| AZW           | S3                          | Mini pc     | [3f05394ddc](https://linux-hardware.org/?probe=3f05394ddc) | Dec 07, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [3a9774bdac](https://linux-hardware.org/?probe=3a9774bdac) | Dec 07, 2022 |
| Monster       | TULPAR T7 V21.6             | Notebook    | [1fb4eaf6d4](https://linux-hardware.org/?probe=1fb4eaf6d4) | Dec 06, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [55e56516e5](https://linux-hardware.org/?probe=55e56516e5) | Dec 06, 2022 |
| HP            | Beats 15                    | Notebook    | [5a09b2cb1d](https://linux-hardware.org/?probe=5a09b2cb1d) | Dec 06, 2022 |
| HP            | 550                         | Notebook    | [1090513329](https://linux-hardware.org/?probe=1090513329) | Dec 06, 2022 |
| ASRock        | B660M Pro RS                | Desktop     | [0a1500b793](https://linux-hardware.org/?probe=0a1500b793) | Dec 05, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [eced972f80](https://linux-hardware.org/?probe=eced972f80) | Dec 05, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [d37c93af89](https://linux-hardware.org/?probe=d37c93af89) | Dec 05, 2022 |
| Lenovo        | G700 20251                  | Notebook    | [8d5d04f931](https://linux-hardware.org/?probe=8d5d04f931) | Dec 05, 2022 |
| Lenovo        | G700 20251                  | Notebook    | [4e8f04ce8f](https://linux-hardware.org/?probe=4e8f04ce8f) | Dec 05, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [cb376e265d](https://linux-hardware.org/?probe=cb376e265d) | Dec 05, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [fb233e5dc1](https://linux-hardware.org/?probe=fb233e5dc1) | Dec 05, 2022 |
| Lenovo        | Tilapia CRB                 | Desktop     | [a32aaf0f8c](https://linux-hardware.org/?probe=a32aaf0f8c) | Dec 05, 2022 |
| HP            | EliteBook x360 1040 G5      | Convertible | [02c80899f7](https://linux-hardware.org/?probe=02c80899f7) | Dec 05, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [535444f416](https://linux-hardware.org/?probe=535444f416) | Dec 05, 2022 |
| Monster       | TULPAR T7 V21.6             | Notebook    | [8c2ed08d33](https://linux-hardware.org/?probe=8c2ed08d33) | Dec 04, 2022 |
| Dell          | Vostro 5471                 | Notebook    | [0bad01b327](https://linux-hardware.org/?probe=0bad01b327) | Dec 04, 2022 |
| Acer          | Aspire VN7-572G             | Notebook    | [2147d11bad](https://linux-hardware.org/?probe=2147d11bad) | Dec 04, 2022 |
| Acer          | Aspire VN7-572G             | Notebook    | [5a456d1825](https://linux-hardware.org/?probe=5a456d1825) | Dec 04, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [36ef5b0deb](https://linux-hardware.org/?probe=36ef5b0deb) | Dec 04, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [23f903a61d](https://linux-hardware.org/?probe=23f903a61d) | Dec 03, 2022 |
| HP            | ProBook 430 G2              | Notebook    | [a66be8f003](https://linux-hardware.org/?probe=a66be8f003) | Dec 03, 2022 |
| ASRock        | B75 Pro3-M                  | Desktop     | [db7e5686f3](https://linux-hardware.org/?probe=db7e5686f3) | Dec 03, 2022 |
| Schenker      | XMG APEX (Mid 2021)         | Notebook    | [41824c584f](https://linux-hardware.org/?probe=41824c584f) | Dec 03, 2022 |
| ASUSTek       | PN51-S1                     | Mini pc     | [5b17c3205f](https://linux-hardware.org/?probe=5b17c3205f) | Dec 03, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [dc233f857f](https://linux-hardware.org/?probe=dc233f857f) | Dec 03, 2022 |
| Dell          | Vostro 5481                 | Notebook    | [6c58c07e64](https://linux-hardware.org/?probe=6c58c07e64) | Dec 03, 2022 |
| Dell          | Latitude E6220              | Notebook    | [8c99ad2bde](https://linux-hardware.org/?probe=8c99ad2bde) | Dec 02, 2022 |
| MSI           | Prestige 14 A12UC           | Notebook    | [7d88c55edb](https://linux-hardware.org/?probe=7d88c55edb) | Dec 02, 2022 |
| Google        | Kled                        | Notebook    | [06c52b65d2](https://linux-hardware.org/?probe=06c52b65d2) | Dec 02, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [867e3d70f0](https://linux-hardware.org/?probe=867e3d70f0) | Dec 02, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [1b361e2f17](https://linux-hardware.org/?probe=1b361e2f17) | Dec 02, 2022 |
| Dell          | 084J0R A00                  | Desktop     | [57b5a73c5d](https://linux-hardware.org/?probe=57b5a73c5d) | Dec 01, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [9866b7f07f](https://linux-hardware.org/?probe=9866b7f07f) | Dec 01, 2022 |
| ASUSTek       | P7P55D                      | Desktop     | [0a012accfd](https://linux-hardware.org/?probe=0a012accfd) | Dec 01, 2022 |
| HP            | ProBook 450 G2              | Notebook    | [552ac907a0](https://linux-hardware.org/?probe=552ac907a0) | Dec 01, 2022 |
| System76      | Thelio thelio-r1            | Desktop     | [76343aa234](https://linux-hardware.org/?probe=76343aa234) | Dec 01, 2022 |
| ASRock        | B75M-DGS                    | Desktop     | [ca277bb16c](https://linux-hardware.org/?probe=ca277bb16c) | Nov 30, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [1c30aa7bcd](https://linux-hardware.org/?probe=1c30aa7bcd) | Nov 30, 2022 |
| Haier         | A1420EM                     | Notebook    | [6f18b3c1ce](https://linux-hardware.org/?probe=6f18b3c1ce) | Nov 30, 2022 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [bd1c91dba9](https://linux-hardware.org/?probe=bd1c91dba9) | Nov 30, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [d233ee2114](https://linux-hardware.org/?probe=d233ee2114) | Nov 30, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [3a64631617](https://linux-hardware.org/?probe=3a64631617) | Nov 30, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [fc681f2f42](https://linux-hardware.org/?probe=fc681f2f42) | Nov 30, 2022 |
| MSI           | B560M-A PRO                 | Desktop     | [a92a0830e9](https://linux-hardware.org/?probe=a92a0830e9) | Nov 30, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [12492cb99a](https://linux-hardware.org/?probe=12492cb99a) | Nov 29, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [a2b8deb4e3](https://linux-hardware.org/?probe=a2b8deb4e3) | Nov 29, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [2ecbfd5e39](https://linux-hardware.org/?probe=2ecbfd5e39) | Nov 29, 2022 |
| Dell          | Inspiron 5406 2n1           | Convertible | [92afc95831](https://linux-hardware.org/?probe=92afc95831) | Nov 29, 2022 |
| Razer         | Blade Stealth               | Notebook    | [e182c3c739](https://linux-hardware.org/?probe=e182c3c739) | Nov 29, 2022 |
| Acer          | Nitro AN517-51              | Notebook    | [c20385f7bd](https://linux-hardware.org/?probe=c20385f7bd) | Nov 29, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [8f17b6a915](https://linux-hardware.org/?probe=8f17b6a915) | Nov 29, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [f2c8b52293](https://linux-hardware.org/?probe=f2c8b52293) | Nov 28, 2022 |
| Dell          | G3 3779                     | Notebook    | [3e85396dae](https://linux-hardware.org/?probe=3e85396dae) | Nov 28, 2022 |
| MSI           | Prestige 15 A12SC           | Notebook    | [af2a404105](https://linux-hardware.org/?probe=af2a404105) | Nov 28, 2022 |
| Medion        | TJ4125                      | Desktop     | [a1c7ac96d3](https://linux-hardware.org/?probe=a1c7ac96d3) | Nov 27, 2022 |
| Gigabyte      | RC14UD                      | Notebook    | [37c4b79c24](https://linux-hardware.org/?probe=37c4b79c24) | Nov 27, 2022 |
| Dell          | G3 3779                     | Notebook    | [2def46f37c](https://linux-hardware.org/?probe=2def46f37c) | Nov 27, 2022 |
| Lenovo        | ThinkPad T430 2349DS5       | Notebook    | [f52677ec2e](https://linux-hardware.org/?probe=f52677ec2e) | Nov 27, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B3402FEA... | Convertible | [e3c2051d8f](https://linux-hardware.org/?probe=e3c2051d8f) | Nov 26, 2022 |
| Monster       | TULPAR T7                   | Notebook    | [6634421091](https://linux-hardware.org/?probe=6634421091) | Nov 26, 2022 |
| Dell          | Vostro 5471                 | Notebook    | [7a6ec88b73](https://linux-hardware.org/?probe=7a6ec88b73) | Nov 26, 2022 |
| Dell          | Vostro 5471                 | Notebook    | [b9bbfd7551](https://linux-hardware.org/?probe=b9bbfd7551) | Nov 26, 2022 |
| Toshiba       | Satellite C670D-126         | Notebook    | [6c2fc84bf2](https://linux-hardware.org/?probe=6c2fc84bf2) | Nov 26, 2022 |
| GPU Compan... | GWNR71517                   | Notebook    | [15173435f0](https://linux-hardware.org/?probe=15173435f0) | Nov 26, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | Notebook    | [fa21163ace](https://linux-hardware.org/?probe=fa21163ace) | Nov 26, 2022 |
| GPD           | G1621-02                    | Notebook    | [d6b679024c](https://linux-hardware.org/?probe=d6b679024c) | Nov 26, 2022 |
| Dell          | Latitude E6440              | Notebook    | [348f786878](https://linux-hardware.org/?probe=348f786878) | Nov 26, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [a462983d82](https://linux-hardware.org/?probe=a462983d82) | Nov 25, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [10186425ec](https://linux-hardware.org/?probe=10186425ec) | Nov 25, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [5a7b57dae6](https://linux-hardware.org/?probe=5a7b57dae6) | Nov 25, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [57c8d65b2e](https://linux-hardware.org/?probe=57c8d65b2e) | Nov 25, 2022 |
| ASUSTek       | X510UQ                      | Notebook    | [5972ededc2](https://linux-hardware.org/?probe=5972ededc2) | Nov 24, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [a4512e8a71](https://linux-hardware.org/?probe=a4512e8a71) | Nov 24, 2022 |
| Unknown       | HX90                        | Desktop     | [e1bd045aaa](https://linux-hardware.org/?probe=e1bd045aaa) | Nov 24, 2022 |
| Gigabyte      | H97-HD3                     | Desktop     | [7c2db201dc](https://linux-hardware.org/?probe=7c2db201dc) | Nov 24, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [601fd47da1](https://linux-hardware.org/?probe=601fd47da1) | Nov 24, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [e47ce764e1](https://linux-hardware.org/?probe=e47ce764e1) | Nov 24, 2022 |
| Gigabyte      | Z270-HD3P-CF                | Desktop     | [6d3657ecde](https://linux-hardware.org/?probe=6d3657ecde) | Nov 23, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [26fb968043](https://linux-hardware.org/?probe=26fb968043) | Nov 23, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [f396cc27ff](https://linux-hardware.org/?probe=f396cc27ff) | Nov 23, 2022 |
| AZW           | SEi                         | Desktop     | [deace4a3d6](https://linux-hardware.org/?probe=deace4a3d6) | Nov 23, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [1bed000f1a](https://linux-hardware.org/?probe=1bed000f1a) | Nov 23, 2022 |
| Lenovo        | G40-45 80E1                 | Notebook    | [c50111eb6d](https://linux-hardware.org/?probe=c50111eb6d) | Nov 22, 2022 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [d876db7f78](https://linux-hardware.org/?probe=d876db7f78) | Nov 22, 2022 |
| Dell          | Latitude 5410               | Notebook    | [7fd0b3fca7](https://linux-hardware.org/?probe=7fd0b3fca7) | Nov 21, 2022 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [498c078586](https://linux-hardware.org/?probe=498c078586) | Nov 21, 2022 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [abda5b4aaf](https://linux-hardware.org/?probe=abda5b4aaf) | Nov 21, 2022 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | Notebook    | [326b5bad4c](https://linux-hardware.org/?probe=326b5bad4c) | Nov 21, 2022 |
| Dell          | 0XPDFK A01                  | Desktop     | [1332a048d4](https://linux-hardware.org/?probe=1332a048d4) | Nov 21, 2022 |
| HP            | Unknown                     | Notebook    | [4530507592](https://linux-hardware.org/?probe=4530507592) | Nov 20, 2022 |
| HP            | 845A                        | Desktop     | [330b46ea11](https://linux-hardware.org/?probe=330b46ea11) | Nov 20, 2022 |
| ASUSTek       | M4A88TD-M EVO               | Desktop     | [e4514feafe](https://linux-hardware.org/?probe=e4514feafe) | Nov 20, 2022 |
| Acer          | Aspire ES1-711G             | Notebook    | [8852f94b38](https://linux-hardware.org/?probe=8852f94b38) | Nov 20, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [7a30c89c58](https://linux-hardware.org/?probe=7a30c89c58) | Nov 20, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [87c95f019e](https://linux-hardware.org/?probe=87c95f019e) | Nov 20, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [8a52f497b0](https://linux-hardware.org/?probe=8a52f497b0) | Nov 19, 2022 |
| Acer          | Nitro AN517-51              | Notebook    | [de8506cc0b](https://linux-hardware.org/?probe=de8506cc0b) | Nov 19, 2022 |
| MSI           | Vector GP66 12UGS           | Notebook    | [9aab7e297a](https://linux-hardware.org/?probe=9aab7e297a) | Nov 19, 2022 |
| MSI           | Vector GP66 12UGS           | Notebook    | [e10c2abc9b](https://linux-hardware.org/?probe=e10c2abc9b) | Nov 19, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [a3fde1deaa](https://linux-hardware.org/?probe=a3fde1deaa) | Nov 19, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [36bc4b545f](https://linux-hardware.org/?probe=36bc4b545f) | Nov 19, 2022 |
| Toshiba       | Satellite C670D-126         | Notebook    | [17e464f802](https://linux-hardware.org/?probe=17e464f802) | Nov 19, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [0734f58b03](https://linux-hardware.org/?probe=0734f58b03) | Nov 18, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [53a2707274](https://linux-hardware.org/?probe=53a2707274) | Nov 18, 2022 |
| Dell          | Inspiron 7348               | Notebook    | [6a46a84480](https://linux-hardware.org/?probe=6a46a84480) | Nov 18, 2022 |
| Dell          | 0KWVT8 A02                  | Desktop     | [e1b586a15a](https://linux-hardware.org/?probe=e1b586a15a) | Nov 18, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [f4c6260289](https://linux-hardware.org/?probe=f4c6260289) | Nov 18, 2022 |
| Unknown       | Unknown                     | Desktop     | [554da2ef73](https://linux-hardware.org/?probe=554da2ef73) | Nov 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [6e0f255eeb](https://linux-hardware.org/?probe=6e0f255eeb) | Nov 18, 2022 |
| Dell          | Inspiron 5759               | Notebook    | [8cdba26964](https://linux-hardware.org/?probe=8cdba26964) | Nov 18, 2022 |
| Digma         | EVE 15 C423 ES5069EW        | Notebook    | [57cd27008a](https://linux-hardware.org/?probe=57cd27008a) | Nov 18, 2022 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [dbbfcd826c](https://linux-hardware.org/?probe=dbbfcd826c) | Nov 18, 2022 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [3491c5eef1](https://linux-hardware.org/?probe=3491c5eef1) | Nov 17, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [86026bcc45](https://linux-hardware.org/?probe=86026bcc45) | Nov 17, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [aa5d7dc8a0](https://linux-hardware.org/?probe=aa5d7dc8a0) | Nov 17, 2022 |
| ASRock        | B560M-ITX/ac                | Desktop     | [c8f725f9cd](https://linux-hardware.org/?probe=c8f725f9cd) | Nov 17, 2022 |
| ASUSTek       | TUF Z270 MARK 1             | Desktop     | [dc1aa01b01](https://linux-hardware.org/?probe=dc1aa01b01) | Nov 17, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [df66428cab](https://linux-hardware.org/?probe=df66428cab) | Nov 17, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [dc9ddea189](https://linux-hardware.org/?probe=dc9ddea189) | Nov 17, 2022 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | Notebook    | [cc20cc9828](https://linux-hardware.org/?probe=cc20cc9828) | Nov 16, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [8b63918780](https://linux-hardware.org/?probe=8b63918780) | Nov 16, 2022 |
| HP            | Pavilion 15                 | Notebook    | [fbef42d1dc](https://linux-hardware.org/?probe=fbef42d1dc) | Nov 16, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [facd5aa317](https://linux-hardware.org/?probe=facd5aa317) | Nov 16, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [e7152e6cb3](https://linux-hardware.org/?probe=e7152e6cb3) | Nov 16, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [a30ec58d99](https://linux-hardware.org/?probe=a30ec58d99) | Nov 16, 2022 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [5e42accb39](https://linux-hardware.org/?probe=5e42accb39) | Nov 16, 2022 |
| ASUSTek       | STRIX Z270E GAMING          | Desktop     | [8e4ab9c969](https://linux-hardware.org/?probe=8e4ab9c969) | Nov 16, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [2ff36bc758](https://linux-hardware.org/?probe=2ff36bc758) | Nov 16, 2022 |
| Dell          | Latitude E7250              | Notebook    | [907a7245b4](https://linux-hardware.org/?probe=907a7245b4) | Nov 15, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [12fe5843d1](https://linux-hardware.org/?probe=12fe5843d1) | Nov 15, 2022 |
| Intel         | NUC5i7RYB H73774-102        | Mini pc     | [6f1cef8a17](https://linux-hardware.org/?probe=6f1cef8a17) | Nov 15, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [04a6897f33](https://linux-hardware.org/?probe=04a6897f33) | Nov 15, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [22b0ad0cb0](https://linux-hardware.org/?probe=22b0ad0cb0) | Nov 15, 2022 |
| Acer          | TravelMate P633-M           | Notebook    | [2277ff1866](https://linux-hardware.org/?probe=2277ff1866) | Nov 15, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [ea0093a1f6](https://linux-hardware.org/?probe=ea0093a1f6) | Nov 15, 2022 |
| Gigabyte      | H97-HD3                     | Desktop     | [b99ae215e4](https://linux-hardware.org/?probe=b99ae215e4) | Nov 14, 2022 |
| Gigabyte      | BOLD E3032                  | Desktop     | [9d013ae9aa](https://linux-hardware.org/?probe=9d013ae9aa) | Nov 14, 2022 |
| Dell          | Inspiron 3480               | Notebook    | [699e532a38](https://linux-hardware.org/?probe=699e532a38) | Nov 14, 2022 |
| Dell          | Inspiron 3480               | Notebook    | [3fca000783](https://linux-hardware.org/?probe=3fca000783) | Nov 14, 2022 |
| Dell          | Precision 7510              | Notebook    | [111903e578](https://linux-hardware.org/?probe=111903e578) | Nov 14, 2022 |
| Gigabyte      | B660M GAMING DDR4           | Desktop     | [d22c86a486](https://linux-hardware.org/?probe=d22c86a486) | Nov 14, 2022 |
| HP            | 1495                        | Desktop     | [f588871a3a](https://linux-hardware.org/?probe=f588871a3a) | Nov 14, 2022 |
| HP            | 1495                        | Desktop     | [5086b0aa3e](https://linux-hardware.org/?probe=5086b0aa3e) | Nov 14, 2022 |
| Gigabyte      | GA-MA790FX-DS5              | Desktop     | [63bba2efec](https://linux-hardware.org/?probe=63bba2efec) | Nov 14, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [fa8dcc3eed](https://linux-hardware.org/?probe=fa8dcc3eed) | Nov 13, 2022 |
| ASUSTek       | K53Z                        | Notebook    | [7eb8b08a75](https://linux-hardware.org/?probe=7eb8b08a75) | Nov 13, 2022 |
| Gigabyte      | Z77X-UP7                    | Desktop     | [e0edc946f9](https://linux-hardware.org/?probe=e0edc946f9) | Nov 13, 2022 |
| Supermicro    | X9DAL                       | Desktop     | [56d4bd9f26](https://linux-hardware.org/?probe=56d4bd9f26) | Nov 13, 2022 |
| Lenovo        | ThinkPad T430 2349P25       | Notebook    | [ba76ce6af6](https://linux-hardware.org/?probe=ba76ce6af6) | Nov 13, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [4ddae3c3a0](https://linux-hardware.org/?probe=4ddae3c3a0) | Nov 13, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [733739e049](https://linux-hardware.org/?probe=733739e049) | Nov 12, 2022 |
| Lenovo        | ThinkPad X260 20F5S28R00    | Notebook    | [ac107ff6e8](https://linux-hardware.org/?probe=ac107ff6e8) | Nov 12, 2022 |
| Google        | Celes                       | Notebook    | [4b15e527d5](https://linux-hardware.org/?probe=4b15e527d5) | Nov 12, 2022 |
| Google        | Celes                       | Notebook    | [68323b0e01](https://linux-hardware.org/?probe=68323b0e01) | Nov 12, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [ca336329c8](https://linux-hardware.org/?probe=ca336329c8) | Nov 12, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [311c90573c](https://linux-hardware.org/?probe=311c90573c) | Nov 12, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [1198a061e1](https://linux-hardware.org/?probe=1198a061e1) | Nov 12, 2022 |
| Dell          | 0HY9JP A00                  | Desktop     | [fed46e3161](https://linux-hardware.org/?probe=fed46e3161) | Nov 12, 2022 |
| ASRock        | B75M                        | Desktop     | [7da4910326](https://linux-hardware.org/?probe=7da4910326) | Nov 12, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a8145bf5ce](https://linux-hardware.org/?probe=a8145bf5ce) | Nov 12, 2022 |
| ASUSTek       | PRIME A320I-K               | Desktop     | [c22a4715da](https://linux-hardware.org/?probe=c22a4715da) | Nov 12, 2022 |
| Timi          | TM1703                      | Notebook    | [b59fbfd729](https://linux-hardware.org/?probe=b59fbfd729) | Nov 11, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [518979e264](https://linux-hardware.org/?probe=518979e264) | Nov 11, 2022 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [d020fa04fe](https://linux-hardware.org/?probe=d020fa04fe) | Nov 11, 2022 |
| Intel         | DP965LT AAD41694-206        | Desktop     | [72773d35e0](https://linux-hardware.org/?probe=72773d35e0) | Nov 11, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [a9a0e77be4](https://linux-hardware.org/?probe=a9a0e77be4) | Nov 11, 2022 |
| ASRock        | X99 Extreme4                | Desktop     | [00da120cde](https://linux-hardware.org/?probe=00da120cde) | Nov 11, 2022 |
| Dell          | Latitude 12 Rugged Extre... | Notebook    | [d5b955a7b3](https://linux-hardware.org/?probe=d5b955a7b3) | Nov 11, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [d8adeb01a9](https://linux-hardware.org/?probe=d8adeb01a9) | Nov 10, 2022 |
| Dell          | 0773VG A00                  | Desktop     | [2ffe6c18f7](https://linux-hardware.org/?probe=2ffe6c18f7) | Nov 10, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [45f26463b7](https://linux-hardware.org/?probe=45f26463b7) | Nov 10, 2022 |
| Acer          | Predator PT516-52s          | Notebook    | [b8ebbe76e8](https://linux-hardware.org/?probe=b8ebbe76e8) | Nov 10, 2022 |
| HP            | Pavilion g6                 | Notebook    | [e2a0a47587](https://linux-hardware.org/?probe=e2a0a47587) | Nov 10, 2022 |
| MSI           | GS75 Stealth 10SE           | Notebook    | [a13f6196b6](https://linux-hardware.org/?probe=a13f6196b6) | Nov 10, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [ffa33ab238](https://linux-hardware.org/?probe=ffa33ab238) | Nov 10, 2022 |
| Samsung       | 950QED                      | Convertible | [c68fd01b4c](https://linux-hardware.org/?probe=c68fd01b4c) | Nov 10, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [6531f0596d](https://linux-hardware.org/?probe=6531f0596d) | Nov 10, 2022 |
| VALE          | Notebook Slim S132          | Notebook    | [fc8cf254ad](https://linux-hardware.org/?probe=fc8cf254ad) | Nov 10, 2022 |
| VALE          | Notebook Slim S132          | Notebook    | [720ddf5d0f](https://linux-hardware.org/?probe=720ddf5d0f) | Nov 10, 2022 |
| MSI           | GS75 Stealth 10SE           | Notebook    | [eaed1093a4](https://linux-hardware.org/?probe=eaed1093a4) | Nov 10, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [d7a20bdac6](https://linux-hardware.org/?probe=d7a20bdac6) | Nov 09, 2022 |
| Timi          | TM1701                      | Notebook    | [917ec43bd1](https://linux-hardware.org/?probe=917ec43bd1) | Nov 09, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [de85ac10f6](https://linux-hardware.org/?probe=de85ac10f6) | Nov 09, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [1c51983a67](https://linux-hardware.org/?probe=1c51983a67) | Nov 09, 2022 |
| HP            | Laptop 17-ca2xxx            | Notebook    | [a31e9f30cc](https://linux-hardware.org/?probe=a31e9f30cc) | Nov 09, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [a72c604f03](https://linux-hardware.org/?probe=a72c604f03) | Nov 09, 2022 |
| Dell          | 0PGKWF A02                  | Desktop     | [d123f535c1](https://linux-hardware.org/?probe=d123f535c1) | Nov 09, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | Notebook    | [5d479ec43f](https://linux-hardware.org/?probe=5d479ec43f) | Nov 08, 2022 |
| MSI           | Unknown                     | Notebook    | [76090d77bf](https://linux-hardware.org/?probe=76090d77bf) | Nov 08, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [91355e2bd7](https://linux-hardware.org/?probe=91355e2bd7) | Nov 08, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [5584c6e2d1](https://linux-hardware.org/?probe=5584c6e2d1) | Nov 08, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [8ba7f1aa17](https://linux-hardware.org/?probe=8ba7f1aa17) | Nov 08, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [1a4822b860](https://linux-hardware.org/?probe=1a4822b860) | Nov 08, 2022 |
| Gigabyte      | B550 VISION D-P             | Desktop     | [c08b835f58](https://linux-hardware.org/?probe=c08b835f58) | Nov 07, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [d454a9a1e7](https://linux-hardware.org/?probe=d454a9a1e7) | Nov 07, 2022 |
| HP            | ProBook 5330m               | Notebook    | [7ddff41cb6](https://linux-hardware.org/?probe=7ddff41cb6) | Nov 07, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [16b7880c43](https://linux-hardware.org/?probe=16b7880c43) | Nov 07, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [76d6e74fad](https://linux-hardware.org/?probe=76d6e74fad) | Nov 07, 2022 |
| Dell          | Inspiron 5406 2n1           | Convertible | [a734aa34bf](https://linux-hardware.org/?probe=a734aa34bf) | Nov 07, 2022 |
| Gigabyte      | B660M D3H DDR4              | Desktop     | [64aed4564c](https://linux-hardware.org/?probe=64aed4564c) | Nov 07, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [8ef47e1adb](https://linux-hardware.org/?probe=8ef47e1adb) | Nov 06, 2022 |
| Acer          | Aspire 5750                 | Notebook    | [83a24172bd](https://linux-hardware.org/?probe=83a24172bd) | Nov 06, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [d29197ed66](https://linux-hardware.org/?probe=d29197ed66) | Nov 06, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [317efeba98](https://linux-hardware.org/?probe=317efeba98) | Nov 06, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | Notebook    | [8090894691](https://linux-hardware.org/?probe=8090894691) | Nov 06, 2022 |
| Sony          | VGN-FW21E                   | Notebook    | [8be58df3e0](https://linux-hardware.org/?probe=8be58df3e0) | Nov 06, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [46c9baf82c](https://linux-hardware.org/?probe=46c9baf82c) | Nov 05, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [5783283bd4](https://linux-hardware.org/?probe=5783283bd4) | Nov 05, 2022 |
| HP            | ZBook 15u G6                | Notebook    | [58025a9d04](https://linux-hardware.org/?probe=58025a9d04) | Nov 05, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [e5684c9b19](https://linux-hardware.org/?probe=e5684c9b19) | Nov 05, 2022 |
| HP            | ZBook 15u G6                | Notebook    | [bd1a9c6659](https://linux-hardware.org/?probe=bd1a9c6659) | Nov 05, 2022 |
| HP            | Pavilion 17                 | Notebook    | [9dd715b48e](https://linux-hardware.org/?probe=9dd715b48e) | Nov 05, 2022 |
| Dell          | Latitude 3420               | Notebook    | [f30c035ae6](https://linux-hardware.org/?probe=f30c035ae6) | Nov 05, 2022 |
| PC Special... | PB50_70RF,RD,RC             | Notebook    | [c2e0841c46](https://linux-hardware.org/?probe=c2e0841c46) | Nov 05, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [118a1f505b](https://linux-hardware.org/?probe=118a1f505b) | Nov 04, 2022 |
| Dell          | 0HV8FN A01                  | Desktop     | [e77651313c](https://linux-hardware.org/?probe=e77651313c) | Nov 04, 2022 |
| Dell          | 0HV8FN A01                  | Desktop     | [7a28d76fe6](https://linux-hardware.org/?probe=7a28d76fe6) | Nov 04, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [95729b1578](https://linux-hardware.org/?probe=95729b1578) | Nov 04, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [c4b2b4072b](https://linux-hardware.org/?probe=c4b2b4072b) | Nov 04, 2022 |
| AXIOO         | SlimBook 11                 | Notebook    | [ffc6980bf3](https://linux-hardware.org/?probe=ffc6980bf3) | Nov 03, 2022 |
| AXIOO         | SlimBook 11                 | Notebook    | [a16eac12d2](https://linux-hardware.org/?probe=a16eac12d2) | Nov 03, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [40a3de202d](https://linux-hardware.org/?probe=40a3de202d) | Nov 03, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [db852ba394](https://linux-hardware.org/?probe=db852ba394) | Nov 03, 2022 |
| Dell          | Latitude E6320              | Notebook    | [b66269072e](https://linux-hardware.org/?probe=b66269072e) | Nov 02, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [df76e744d7](https://linux-hardware.org/?probe=df76e744d7) | Nov 02, 2022 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [760c526784](https://linux-hardware.org/?probe=760c526784) | Nov 02, 2022 |
| Dell          | 040DDP A00                  | Desktop     | [fba864b37c](https://linux-hardware.org/?probe=fba864b37c) | Nov 02, 2022 |
| Lenovo        | ThinkPad T440p 20AW000GU... | Notebook    | [b4ff1758e9](https://linux-hardware.org/?probe=b4ff1758e9) | Nov 02, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [e4dfd41fa4](https://linux-hardware.org/?probe=e4dfd41fa4) | Nov 02, 2022 |
| Panasonic     | CF-31WBLEHLM                | Notebook    | [623af75bb3](https://linux-hardware.org/?probe=623af75bb3) | Nov 02, 2022 |
| Panasonic     | CF-31WBLEHLM                | Notebook    | [52e7c62bae](https://linux-hardware.org/?probe=52e7c62bae) | Nov 02, 2022 |
| MSI           | MAG Z390 TOMAHAWK           | Desktop     | [4f1e0d9702](https://linux-hardware.org/?probe=4f1e0d9702) | Nov 02, 2022 |
| MSI           | MAG Z390 TOMAHAWK           | Desktop     | [842320d7b3](https://linux-hardware.org/?probe=842320d7b3) | Nov 02, 2022 |
| Gigabyte      | Z270-HD3P-CF                | Desktop     | [8b8ec08876](https://linux-hardware.org/?probe=8b8ec08876) | Nov 02, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [7b42bc51be](https://linux-hardware.org/?probe=7b42bc51be) | Nov 02, 2022 |
| Notebook      | P65_P67SE                   | Notebook    | [9b99df1e15](https://linux-hardware.org/?probe=9b99df1e15) | Nov 02, 2022 |
| Gigabyte      | H81M-DS2V                   | Desktop     | [caffb9ebd7](https://linux-hardware.org/?probe=caffb9ebd7) | Nov 01, 2022 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [50bd7a7436](https://linux-hardware.org/?probe=50bd7a7436) | Nov 01, 2022 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [50d2f412f0](https://linux-hardware.org/?probe=50d2f412f0) | Nov 01, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | Notebook    | [fefe8e5d04](https://linux-hardware.org/?probe=fefe8e5d04) | Nov 01, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | Notebook    | [df949b6e10](https://linux-hardware.org/?probe=df949b6e10) | Nov 01, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [6d6a8caf61](https://linux-hardware.org/?probe=6d6a8caf61) | Nov 01, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [722ae37952](https://linux-hardware.org/?probe=722ae37952) | Nov 01, 2022 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [77ccdee0fe](https://linux-hardware.org/?probe=77ccdee0fe) | Nov 01, 2022 |
| HP            | Laptop 15-da2xxx            | Notebook    | [ea7591794a](https://linux-hardware.org/?probe=ea7591794a) | Nov 01, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [27b07caa39](https://linux-hardware.org/?probe=27b07caa39) | Oct 31, 2022 |
| ASRock        | B560M Pro4                  | Desktop     | [865aef7529](https://linux-hardware.org/?probe=865aef7529) | Oct 31, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [80f6da5216](https://linux-hardware.org/?probe=80f6da5216) | Oct 31, 2022 |
| ASUSTek       | P7P55D-E PRO                | Desktop     | [1e0daee604](https://linux-hardware.org/?probe=1e0daee604) | Oct 30, 2022 |
| Acer          | Aspire 5732Z                | Notebook    | [df73e0ca67](https://linux-hardware.org/?probe=df73e0ca67) | Oct 30, 2022 |
| Shuttle       | FH61R                       | Desktop     | [26f86947ef](https://linux-hardware.org/?probe=26f86947ef) | Oct 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [4b778e52ee](https://linux-hardware.org/?probe=4b778e52ee) | Oct 30, 2022 |
| ASUSTek       | Zephyrus S GX502GW_GX502... | Notebook    | [c3f344809a](https://linux-hardware.org/?probe=c3f344809a) | Oct 30, 2022 |
| EVGA          | 122-CK-NF68 2               | Desktop     | [91b3144c5c](https://linux-hardware.org/?probe=91b3144c5c) | Oct 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [418b143f46](https://linux-hardware.org/?probe=418b143f46) | Oct 30, 2022 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | Desktop     | [7047610fd9](https://linux-hardware.org/?probe=7047610fd9) | Oct 30, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [293877c614](https://linux-hardware.org/?probe=293877c614) | Oct 29, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [aea626acae](https://linux-hardware.org/?probe=aea626acae) | Oct 29, 2022 |
| Lenovo        | V15-IGL 82C3                | Notebook    | [5bd4292187](https://linux-hardware.org/?probe=5bd4292187) | Oct 29, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [91f0c87afa](https://linux-hardware.org/?probe=91f0c87afa) | Oct 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d7491bf8e7](https://linux-hardware.org/?probe=d7491bf8e7) | Oct 29, 2022 |
| Dell          | 0478VN A00                  | Desktop     | [883100c74f](https://linux-hardware.org/?probe=883100c74f) | Oct 29, 2022 |
| Google        | Kench                       | Desktop     | [faf24fddcd](https://linux-hardware.org/?probe=faf24fddcd) | Oct 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [6bdf703faf](https://linux-hardware.org/?probe=6bdf703faf) | Oct 29, 2022 |
| Dell          | 0478VN A00                  | Desktop     | [629858e96c](https://linux-hardware.org/?probe=629858e96c) | Oct 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [cfa027a9e2](https://linux-hardware.org/?probe=cfa027a9e2) | Oct 28, 2022 |
| ASRock        | H61M-VS                     | Desktop     | [9a48b2a679](https://linux-hardware.org/?probe=9a48b2a679) | Oct 28, 2022 |
| Dell          | Latitude 5521               | Notebook    | [460057b367](https://linux-hardware.org/?probe=460057b367) | Oct 28, 2022 |
| Dell          | 0KRC95 A02                  | Desktop     | [8afc3da46d](https://linux-hardware.org/?probe=8afc3da46d) | Oct 28, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [a2d71fd3ca](https://linux-hardware.org/?probe=a2d71fd3ca) | Oct 28, 2022 |
| HP            | Laptop 15-da2xxx            | Notebook    | [071938b19a](https://linux-hardware.org/?probe=071938b19a) | Oct 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [ac3b0eaf36](https://linux-hardware.org/?probe=ac3b0eaf36) | Oct 28, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [ba5aec702a](https://linux-hardware.org/?probe=ba5aec702a) | Oct 27, 2022 |
| Gigabyte      | Z77X-UP7                    | Desktop     | [c33d6de923](https://linux-hardware.org/?probe=c33d6de923) | Oct 27, 2022 |
| Acer          | Predator PT516-52s          | Notebook    | [c0cebe4cfe](https://linux-hardware.org/?probe=c0cebe4cfe) | Oct 27, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [a5c5f0ec1e](https://linux-hardware.org/?probe=a5c5f0ec1e) | Oct 27, 2022 |
| HP            | Pavilion dv6                | Notebook    | [ed392a140d](https://linux-hardware.org/?probe=ed392a140d) | Oct 27, 2022 |
| HP            | G62                         | Notebook    | [c9ba156401](https://linux-hardware.org/?probe=c9ba156401) | Oct 27, 2022 |
| Dell          | Inspiron 5515               | Notebook    | [74ad4c8c59](https://linux-hardware.org/?probe=74ad4c8c59) | Oct 27, 2022 |
| HP            | 844C                        | Desktop     | [7e994c50c9](https://linux-hardware.org/?probe=7e994c50c9) | Oct 27, 2022 |
| Gigabyte      | AX370M-Gaming 3-CF          | Desktop     | [abe170cf19](https://linux-hardware.org/?probe=abe170cf19) | Oct 27, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [a308f68bce](https://linux-hardware.org/?probe=a308f68bce) | Oct 27, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | Notebook    | [0763832411](https://linux-hardware.org/?probe=0763832411) | Oct 27, 2022 |
| ASUSTek       | M5A78L-M LE                 | Desktop     | [6954f669c5](https://linux-hardware.org/?probe=6954f669c5) | Oct 27, 2022 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | Desktop     | [3acf0ca326](https://linux-hardware.org/?probe=3acf0ca326) | Oct 26, 2022 |
| Notebook      | PD5x_7xPNP_PNR_PNN_PNT      | Notebook    | [93229f0fab](https://linux-hardware.org/?probe=93229f0fab) | Oct 26, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [7910e04e13](https://linux-hardware.org/?probe=7910e04e13) | Oct 25, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [2920658e38](https://linux-hardware.org/?probe=2920658e38) | Oct 25, 2022 |
| Samsung       | 767XCL                      | Notebook    | [17bd1b4506](https://linux-hardware.org/?probe=17bd1b4506) | Oct 25, 2022 |
| HP            | Pavilion g6                 | Notebook    | [448d52b32f](https://linux-hardware.org/?probe=448d52b32f) | Oct 25, 2022 |
| ASUSTek       | N751JK                      | Notebook    | [f6f0ff5048](https://linux-hardware.org/?probe=f6f0ff5048) | Oct 25, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [94fa6196b8](https://linux-hardware.org/?probe=94fa6196b8) | Oct 25, 2022 |
| Acer          | Aspire 5750                 | Notebook    | [20df7ad008](https://linux-hardware.org/?probe=20df7ad008) | Oct 25, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [bd3a8063b3](https://linux-hardware.org/?probe=bd3a8063b3) | Oct 25, 2022 |
| Sony          | VAIO                        | All in one  | [27e76b1c76](https://linux-hardware.org/?probe=27e76b1c76) | Oct 25, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [6a9d81591f](https://linux-hardware.org/?probe=6a9d81591f) | Oct 25, 2022 |
| Dell          | Vostro 15 5501              | Notebook    | [3338297022](https://linux-hardware.org/?probe=3338297022) | Oct 25, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [285e8cd1a5](https://linux-hardware.org/?probe=285e8cd1a5) | Oct 25, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [cfb2e32cea](https://linux-hardware.org/?probe=cfb2e32cea) | Oct 25, 2022 |
| ASUSTek       | PRIME H610M-A D4            | Desktop     | [daa76e4b78](https://linux-hardware.org/?probe=daa76e4b78) | Oct 25, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [fe222419ec](https://linux-hardware.org/?probe=fe222419ec) | Oct 25, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [65c39a9702](https://linux-hardware.org/?probe=65c39a9702) | Oct 24, 2022 |
| HP            | 470 G8 Notebook PC          | Notebook    | [1cae6fb5ac](https://linux-hardware.org/?probe=1cae6fb5ac) | Oct 24, 2022 |
| HP            | 470 G8 Notebook PC          | Notebook    | [4c3e8196af](https://linux-hardware.org/?probe=4c3e8196af) | Oct 24, 2022 |
| Acer          | Nitro AN517-51              | Notebook    | [7fed0ea2a9](https://linux-hardware.org/?probe=7fed0ea2a9) | Oct 24, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [37fc32cacd](https://linux-hardware.org/?probe=37fc32cacd) | Oct 24, 2022 |
| Gigabyte      | B365M D2V                   | Desktop     | [c852b8f3f7](https://linux-hardware.org/?probe=c852b8f3f7) | Oct 24, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [f42213926f](https://linux-hardware.org/?probe=f42213926f) | Oct 24, 2022 |
| ASUSTek       | H97-PLUS                    | Desktop     | [aaf3b72437](https://linux-hardware.org/?probe=aaf3b72437) | Oct 24, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [638c72b105](https://linux-hardware.org/?probe=638c72b105) | Oct 24, 2022 |
| Dell          | 0RW199                      | Desktop     | [dc99b64e62](https://linux-hardware.org/?probe=dc99b64e62) | Oct 24, 2022 |
| Lenovo        | ThinkPad P73 20QRS00100     | Notebook    | [532b112928](https://linux-hardware.org/?probe=532b112928) | Oct 24, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [918b0ef1ab](https://linux-hardware.org/?probe=918b0ef1ab) | Oct 24, 2022 |
| HP            | Laptop 17-by0xxx            | Notebook    | [faedd5a008](https://linux-hardware.org/?probe=faedd5a008) | Oct 24, 2022 |
| MSI           | 760GM-P23                   | Desktop     | [21db3e8ee8](https://linux-hardware.org/?probe=21db3e8ee8) | Oct 23, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [13c917aa38](https://linux-hardware.org/?probe=13c917aa38) | Oct 23, 2022 |
| ASUSTek       | STRIX Z270E GAMING          | Desktop     | [ca0e86eb6b](https://linux-hardware.org/?probe=ca0e86eb6b) | Oct 22, 2022 |
| Dell          | Latitude 7390               | Notebook    | [71f8a9e59b](https://linux-hardware.org/?probe=71f8a9e59b) | Oct 22, 2022 |
| Acer          | Predator PT516-52s          | Notebook    | [ec8dac6fd3](https://linux-hardware.org/?probe=ec8dac6fd3) | Oct 22, 2022 |
| Dell          | Vostro 3560                 | Notebook    | [b438a2ba8f](https://linux-hardware.org/?probe=b438a2ba8f) | Oct 22, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [ddc08ffe48](https://linux-hardware.org/?probe=ddc08ffe48) | Oct 22, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [a8c892608e](https://linux-hardware.org/?probe=a8c892608e) | Oct 21, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [20f991643f](https://linux-hardware.org/?probe=20f991643f) | Oct 21, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Kubuntu/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Kubuntu 20.04   | 1393      | 37.81%  |
| Kubuntu 22.04   | 734       | 19.92%  |
| Kubuntu 22.10   | 277       | 7.52%   |
| Kubuntu 20.10   | 256       | 6.95%   |
| Kubuntu 21.10   | 242       | 6.57%   |
| Kubuntu 21.04   | 214       | 5.81%   |
| Kubuntu 18.04   | 201       | 5.46%   |
| Kubuntu 19.10   | 178       | 4.83%   |
| Kubuntu 11      | 86        | 2.33%   |
| Kubuntu 11.1    | 26        | 0.71%   |
| Kubuntu 19.04   | 22        | 0.6%    |
| Kubuntu 16.04   | 13        | 0.35%   |
| Kubuntu 23.04   | 12        | 0.33%   |
| Kubuntu         | 8         | 0.22%   |
| Kubuntu 18.10   | 7         | 0.19%   |
| Kubuntu 2.0     | 6         | 0.16%   |
| Kubuntu 17.10   | 3         | 0.08%   |
| Kubuntu 17.04   | 2         | 0.05%   |
| Kubuntu 14.04   | 2         | 0.05%   |
| Kubuntu 20.08.3 | 1         | 0.03%   |
| Kubuntu 12.04   | 1         | 0.03%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Kubuntu | 3523      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.4.0-42-generic  | 103       | 2.55%   |
| 5.15.0-52-generic | 84        | 2.08%   |
| 5.15.0-56-generic | 79        | 1.95%   |
| 5.19.0-35-generic | 70        | 1.73%   |
| 5.4.0-52-generic  | 68        | 1.68%   |
| 5.4.0-58-generic  | 59        | 1.46%   |
| 5.4.0-48-generic  | 59        | 1.46%   |
| 5.15.0-48-generic | 58        | 1.43%   |
| 5.15.0-46-generic | 53        | 1.31%   |
| 5.13.0-39-generic | 53        | 1.31%   |
| 5.19.0-23-generic | 52        | 1.29%   |
| 5.4.0-40-generic  | 47        | 1.16%   |
| 5.13.0-28-generic | 44        | 1.09%   |
| 5.19.0-31-generic | 43        | 1.06%   |
| 5.19.0-26-generic | 42        | 1.04%   |
| 5.15.0-58-generic | 41        | 1.01%   |
| 5.15.0-43-generic | 41        | 1.01%   |
| 5.15.0-47-generic | 39        | 0.96%   |
| 5.15.0-41-generic | 39        | 0.96%   |
| 5.11.0-37-generic | 38        | 0.94%   |
| 5.11.0-25-generic | 38        | 0.94%   |
| 5.13.0-30-generic | 37        | 0.92%   |
| 5.4.0-47-generic  | 36        | 0.89%   |
| 5.15.0-53-generic | 36        | 0.89%   |
| 5.4.0-65-generic  | 35        | 0.87%   |
| 5.8.0-48-generic  | 34        | 0.84%   |
| 5.3.0-40-generic  | 34        | 0.84%   |
| 5.4.0-37-generic  | 33        | 0.82%   |
| 5.4.0-29-generic  | 33        | 0.82%   |
| 5.19.0-29-generic | 32        | 0.79%   |
| 5.15.0-60-generic | 32        | 0.79%   |
| 5.13.0-22-generic | 32        | 0.79%   |
| 5.4.0-45-generic  | 30        | 0.74%   |
| 5.8.0-50-generic  | 29        | 0.72%   |
| 5.13.0-35-generic | 29        | 0.72%   |
| 5.8.0-63-generic  | 28        | 0.69%   |
| 5.4.0-54-generic  | 28        | 0.69%   |
| 5.3.0-26-generic  | 28        | 0.69%   |
| 5.13.0-40-generic | 28        | 0.69%   |
| 5.8.0-44-generic  | 27        | 0.67%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 938       | 25.02%  |
| 5.15.0  | 732       | 19.53%  |
| 5.13.0  | 409       | 10.91%  |
| 5.8.0   | 406       | 10.83%  |
| 5.11.0  | 327       | 8.72%   |
| 5.19.0  | 297       | 7.92%   |
| 5.3.0   | 224       | 5.97%   |
| 4.15.0  | 69        | 1.84%   |
| 5.0.0   | 36        | 0.96%   |
| 5.17.0  | 19        | 0.51%   |
| 5.10.0  | 18        | 0.48%   |
| 5.6.0   | 15        | 0.4%    |
| 4.4.0   | 10        | 0.27%   |
| 6.0.0   | 9         | 0.24%   |
| 5.14.0  | 8         | 0.21%   |
| 4.18.0  | 8         | 0.21%   |
| 6.1.0   | 7         | 0.19%   |
| 6.0.9   | 5         | 0.13%   |
| 5.9.0   | 5         | 0.13%   |
| 5.7.0   | 4         | 0.11%   |
| 6.2.0   | 3         | 0.08%   |
| 6.1.5   | 3         | 0.08%   |
| 5.8.18  | 3         | 0.08%   |
| 5.18.4  | 3         | 0.08%   |
| 5.18.10 | 3         | 0.08%   |
| 5.16.0  | 3         | 0.08%   |
| 5.12.8  | 3         | 0.08%   |
| 5.12.0  | 3         | 0.08%   |
| 4.13.0  | 3         | 0.08%   |
| 4.10.0  | 3         | 0.08%   |
| 6.2.5   | 2         | 0.05%   |
| 6.2.2   | 2         | 0.05%   |
| 6.1.9   | 2         | 0.05%   |
| 6.1.8   | 2         | 0.05%   |
| 6.1.12  | 2         | 0.05%   |
| 6.1.11  | 2         | 0.05%   |
| 6.0.7   | 2         | 0.05%   |
| 6.0.6   | 2         | 0.05%   |
| 6.0.1   | 2         | 0.05%   |
| 5.9.16  | 2         | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 945       | 25.25%  |
| 5.15    | 746       | 19.93%  |
| 5.8     | 422       | 11.27%  |
| 5.13    | 419       | 11.19%  |
| 5.11    | 333       | 8.9%    |
| 5.19    | 303       | 8.1%    |
| 5.3     | 227       | 6.06%   |
| 4.15    | 70        | 1.87%   |
| 5.0     | 37        | 0.99%   |
| 5.10    | 30        | 0.8%    |
| 5.17    | 26        | 0.69%   |
| 6.1     | 22        | 0.59%   |
| 6.0     | 21        | 0.56%   |
| 5.6     | 20        | 0.53%   |
| 5.14    | 17        | 0.45%   |
| 5.9     | 13        | 0.35%   |
| 5.12    | 13        | 0.35%   |
| 5.18    | 12        | 0.32%   |
| 5.7     | 11        | 0.29%   |
| 6.2     | 10        | 0.27%   |
| 5.16    | 10        | 0.27%   |
| 4.4     | 10        | 0.27%   |
| 4.18    | 10        | 0.27%   |
| 5.5     | 5         | 0.13%   |
| 4.13    | 3         | 0.08%   |
| 4.10    | 3         | 0.08%   |
| 5.1     | 2         | 0.05%   |
| 4.17    | 1         | 0.03%   |
| 4.12    | 1         | 0.03%   |
| 3.13    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 3505      | 99.49%  |
| i686    | 12        | 0.34%   |
| aarch64 | 5         | 0.14%   |
| riscv64 | 1         | 0.03%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| KDE5       | 2623      | 73.1%   |
| KDE        | 907       | 25.28%  |
| GNOME      | 20        | 0.56%   |
| Cinnamon   | 10        | 0.28%   |
| Budgie     | 8         | 0.22%   |
| MATE       | 6         | 0.17%   |
| XFCE       | 3         | 0.08%   |
| LXQt       | 3         | 0.08%   |
| KDE4       | 3         | 0.08%   |
| X-Cinnamon | 1         | 0.03%   |
| Unity      | 1         | 0.03%   |
| i3         | 1         | 0.03%   |
| GNUstep    | 1         | 0.03%   |
| Unknown    | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 3388      | 95.52%  |
| Wayland | 121       | 3.41%   |
| Tty     | 37        | 1.04%   |
| Web     | 1         | 0.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 2079      | 57.88%  |
| Unknown | 1258      | 35.02%  |
| GDM     | 109       | 3.03%   |
| GDM3    | 66        | 1.84%   |
| LightDM | 56        | 1.56%   |
| TDM     | 21        | 0.58%   |
| SLiM    | 2         | 0.06%   |
| LXDM    | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1491      | 41.91%  |
| de_DE   | 290       | 8.15%   |
| ru_RU   | 184       | 5.17%   |
| fr_FR   | 166       | 4.67%   |
| pt_BR   | 162       | 4.55%   |
| en_GB   | 161       | 4.53%   |
| it_IT   | 151       | 4.24%   |
| en_CA   | 78        | 2.19%   |
| Unknown | 77        | 2.16%   |
| es_ES   | 73        | 2.05%   |
| en_AU   | 69        | 1.94%   |
| pl_PL   | 65        | 1.83%   |
| en_IN   | 65        | 1.83%   |
| C       | 37        | 1.04%   |
| hu_HU   | 28        | 0.79%   |
| es_MX   | 25        | 0.7%    |
| ru_UA   | 23        | 0.65%   |
| nl_NL   | 21        | 0.59%   |
| es_AR   | 21        | 0.59%   |
| en_ZA   | 21        | 0.59%   |
| de_AT   | 20        | 0.56%   |
| cs_CZ   | 20        | 0.56%   |
| en_NZ   | 17        | 0.48%   |
| tr_TR   | 14        | 0.39%   |
| de_CH   | 13        | 0.37%   |
| el_GR   | 11        | 0.31%   |
| zh_CN   | 10        | 0.28%   |
| sv_SE   | 10        | 0.28%   |
| pt_PT   | 10        | 0.28%   |
| es_CO   | 9         | 0.25%   |
| es_CL   | 9         | 0.25%   |
| en_PH   | 9         | 0.25%   |
| en_IL   | 9         | 0.25%   |
| en_IE   | 9         | 0.25%   |
| uk_UA   | 8         | 0.22%   |
| fr_BE   | 8         | 0.22%   |
| es_VE   | 8         | 0.22%   |
| sl_SI   | 7         | 0.2%    |
| nl_BE   | 7         | 0.2%    |
| fr_CH   | 7         | 0.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1976      | 55.18%  |
| BIOS | 1605      | 44.82%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 3238      | 91.29%  |
| Btrfs    | 140       | 3.95%   |
| Overlay  | 88        | 2.48%   |
| Xfs      | 36        | 1.01%   |
| Zfs      | 20        | 0.56%   |
| Unknown  | 12        | 0.34%   |
| Ext3     | 5         | 0.14%   |
| Ext2     | 4         | 0.11%   |
| XXXX     | 1         | 0.03%   |
| Reiserfs | 1         | 0.03%   |
| Jfs      | 1         | 0.03%   |
| ExX4     | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 1755      | 48.94%  |
| Unknown | 1498      | 41.77%  |
| MBR     | 333       | 9.29%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3084      | 86.56%  |
| Yes       | 479       | 13.44%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2176      | 61.04%  |
| Yes       | 1389      | 38.96%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 570       | 16.18%  |
| Lenovo              | 529       | 15.02%  |
| Dell                | 496       | 14.08%  |
| Hewlett-Packard     | 474       | 13.45%  |
| Gigabyte Technology | 287       | 8.15%   |
| MSI                 | 241       | 6.84%   |
| Acer                | 167       | 4.74%   |
| ASRock              | 130       | 3.69%   |
| Apple               | 49        | 1.39%   |
| Samsung Electronics | 42        | 1.19%   |
| Intel               | 41        | 1.16%   |
| HUAWEI              | 38        | 1.08%   |
| Unknown             | 28        | 0.79%   |
| Toshiba             | 25        | 0.71%   |
| Notebook            | 22        | 0.62%   |
| Sony                | 21        | 0.6%    |
| Google              | 20        | 0.57%   |
| TUXEDO              | 19        | 0.54%   |
| Fujitsu             | 18        | 0.51%   |
| Pegatron            | 14        | 0.4%    |
| Timi                | 13        | 0.37%   |
| Alienware           | 13        | 0.37%   |
| Positivo            | 12        | 0.34%   |
| Medion              | 12        | 0.34%   |
| Biostar             | 10        | 0.28%   |
| Foxconn             | 9         | 0.26%   |
| ZOTAC               | 8         | 0.23%   |
| Supermicro          | 8         | 0.23%   |
| Packard Bell        | 8         | 0.23%   |
| Microsoft           | 8         | 0.23%   |
| ECS                 | 8         | 0.23%   |
| Chuwi               | 8         | 0.23%   |
| System76            | 7         | 0.2%    |
| AZW                 | 7         | 0.2%    |
| Shuttle             | 6         | 0.17%   |
| PC Specialist       | 6         | 0.17%   |
| LG Electronics      | 6         | 0.17%   |
| GPU Company         | 6         | 0.17%   |
| Razer               | 5         | 0.14%   |
| Panasonic           | 5         | 0.14%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| ASUS All Series                    | 42        | 1.19%   |
| Unknown                            | 41        | 1.16%   |
| Gigabyte B450M DS3H                | 11        | 0.31%   |
| ASUS ROG STRIX B550-F GAMING       | 11        | 0.31%   |
| HP Notebook                        | 10        | 0.28%   |
| MSI MS-7C37                        | 9         | 0.26%   |
| MSI MS-7B79                        | 9         | 0.26%   |
| HP Pavilion g6                     | 9         | 0.26%   |
| HP Pavilion dv6                    | 9         | 0.26%   |
| Dell XPS 15 9560                   | 9         | 0.26%   |
| Dell OptiPlex 9020                 | 9         | 0.26%   |
| Dell OptiPlex 7010                 | 9         | 0.26%   |
| HUAWEI NBLK-WAX9X                  | 8         | 0.23%   |
| ASUS ROG STRIX X570-E GAMING       | 8         | 0.23%   |
| ASUS PRIME B350-PLUS               | 8         | 0.23%   |
| MSI MS-7C91                        | 7         | 0.2%    |
| HP Pavilion dv7                    | 7         | 0.2%    |
| Gigabyte X570 AORUS MASTER         | 7         | 0.2%    |
| Gigabyte A320M-S2H                 | 7         | 0.2%    |
| Gigabyte 970A-DS3P                 | 7         | 0.2%    |
| Dell XPS 15 9570                   | 7         | 0.2%    |
| ASUS PRIME B450M-A                 | 7         | 0.2%    |
| MSI MS-7A34                        | 6         | 0.17%   |
| MSI MS-7817                        | 6         | 0.17%   |
| MSI MS-7693                        | 6         | 0.17%   |
| HP Pavilion 15                     | 6         | 0.17%   |
| HP EliteBook 840 G5                | 6         | 0.17%   |
| HP EliteBook 840 G3                | 6         | 0.17%   |
| ASUS PRIME A320M-K                 | 6         | 0.17%   |
| MSI MS-7C02                        | 5         | 0.14%   |
| HP ENVY x360 Convertible 13-ay0xxx | 5         | 0.14%   |
| HP EliteBook 840 G6                | 5         | 0.14%   |
| GPU Company GWTC116-2              | 5         | 0.14%   |
| Dell XPS 8700                      | 5         | 0.14%   |
| Dell XPS 15 7590                   | 5         | 0.14%   |
| Dell XPS 13 9310                   | 5         | 0.14%   |
| Dell OptiPlex 780                  | 5         | 0.14%   |
| Dell Latitude E6540                | 5         | 0.14%   |
| Dell Latitude 5480                 | 5         | 0.14%   |
| Dell Inspiron 5570                 | 5         | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 242       | 6.87%   |
| Dell Latitude      | 128       | 3.63%   |
| Dell Inspiron      | 123       | 3.49%   |
| Acer Aspire        | 106       | 3.01%   |
| HP Pavilion        | 97        | 2.75%   |
| Lenovo IdeaPad     | 96        | 2.72%   |
| ASUS ROG           | 80        | 2.27%   |
| ASUS PRIME         | 76        | 2.16%   |
| Dell XPS           | 73        | 2.07%   |
| HP ProBook         | 60        | 1.7%    |
| HP EliteBook       | 57        | 1.62%   |
| HP Laptop          | 52        | 1.48%   |
| Dell Precision     | 52        | 1.48%   |
| Dell OptiPlex      | 52        | 1.48%   |
| ASUS VivoBook      | 44        | 1.25%   |
| ASUS All           | 42        | 1.19%   |
| Unknown            | 41        | 1.16%   |
| ASUS TUF           | 38        | 1.08%   |
| Lenovo ThinkCentre | 32        | 0.91%   |
| Dell Vostro        | 31        | 0.88%   |
| HP ENVY            | 29        | 0.82%   |
| HP Compaq          | 29        | 0.82%   |
| Lenovo Yoga        | 25        | 0.71%   |
| Lenovo Legion      | 23        | 0.65%   |
| Acer Nitro         | 23        | 0.65%   |
| Toshiba Satellite  | 21        | 0.6%    |
| Lenovo ThinkBook   | 21        | 0.6%    |
| ASUS ZenBook       | 20        | 0.57%   |
| Gigabyte B450M     | 19        | 0.54%   |
| ASUS ASUS          | 18        | 0.51%   |
| Gigabyte X570      | 17        | 0.48%   |
| Acer Swift         | 17        | 0.48%   |
| HP ZBook           | 11        | 0.31%   |
| HP Spectre         | 11        | 0.31%   |
| HP EliteDesk       | 11        | 0.31%   |
| Gigabyte B550      | 11        | 0.31%   |
| Gigabyte A320M-S2H | 11        | 0.31%   |
| HP Notebook        | 10        | 0.28%   |
| Gigabyte B450      | 10        | 0.28%   |
| ASUS M5A78L-M      | 10        | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 433       | 12.29%  |
| 2019    | 428       | 12.15%  |
| 2018    | 396       | 11.24%  |
| 2021    | 292       | 8.29%   |
| 2017    | 265       | 7.52%   |
| 2013    | 242       | 6.87%   |
| 2012    | 241       | 6.84%   |
| 2014    | 211       | 5.99%   |
| 2011    | 208       | 5.9%    |
| 2016    | 172       | 4.88%   |
| 2015    | 167       | 4.74%   |
| 2010    | 118       | 3.35%   |
| 2022    | 111       | 3.15%   |
| 2008    | 92        | 2.61%   |
| 2009    | 87        | 2.47%   |
| 2007    | 35        | 0.99%   |
| 2006    | 9         | 0.26%   |
| Unknown | 7         | 0.2%    |
| 2023    | 5         | 0.14%   |
| 2005    | 3         | 0.09%   |
| 2004    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1951      | 55.38%  |
| Desktop        | 1324      | 37.58%  |
| Convertible    | 119       | 3.38%   |
| Mini pc        | 52        | 1.48%   |
| All in one     | 35        | 0.99%   |
| Tablet         | 23        | 0.65%   |
| Server         | 14        | 0.4%    |
| System on chip | 5         | 0.14%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 3240      | 91.34%  |
| Enabled  | 307       | 8.66%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3497      | 99.26%  |
| Yes  | 26        | 0.74%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 923       | 25.98%  |
| 4.01-8.0        | 791       | 22.26%  |
| 8.01-16.0       | 657       | 18.49%  |
| 32.01-64.0      | 480       | 13.51%  |
| 3.01-4.0        | 419       | 11.79%  |
| 64.01-256.0     | 118       | 3.32%   |
| 24.01-32.0      | 90        | 2.53%   |
| 1.01-2.0        | 51        | 1.44%   |
| 2.01-3.0        | 22        | 0.62%   |
| More than 256.0 | 2         | 0.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 2.01-3.0    | 995       | 26.08%  |
| 4.01-8.0    | 890       | 23.33%  |
| 1.01-2.0    | 858       | 22.49%  |
| 3.01-4.0    | 643       | 16.85%  |
| 8.01-16.0   | 272       | 7.13%   |
| 0.51-1.0    | 87        | 2.28%   |
| 16.01-24.0  | 43        | 1.13%   |
| 24.01-32.0  | 12        | 0.31%   |
| 32.01-64.0  | 8         | 0.21%   |
| 0.01-0.5    | 5         | 0.13%   |
| 64.01-256.0 | 1         | 0.03%   |
| Unknown     | 1         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1934      | 53.44%  |
| 2      | 981       | 27.11%  |
| 3      | 331       | 9.15%   |
| 4      | 185       | 5.11%   |
| 5      | 91        | 2.51%   |
| 6      | 41        | 1.13%   |
| 7      | 25        | 0.69%   |
| 0      | 12        | 0.33%   |
| 8      | 6         | 0.17%   |
| 9      | 5         | 0.14%   |
| 10     | 3         | 0.08%   |
| 12     | 2         | 0.06%   |
| 11     | 2         | 0.06%   |
| 13     | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2393      | 67.43%  |
| Yes       | 1156      | 32.57%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2980      | 84.47%  |
| No        | 548       | 15.53%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2740      | 77.4%   |
| No        | 800       | 22.6%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2352      | 66.18%  |
| No        | 1202      | 33.82%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 680       | 19.26%  |
| Germany      | 389       | 11.02%  |
| Russia       | 248       | 7.02%   |
| Brazil       | 209       | 5.92%   |
| France       | 206       | 5.83%   |
| Italy        | 194       | 5.49%   |
| UK           | 149       | 4.22%   |
| Spain        | 105       | 2.97%   |
| Canada       | 91        | 2.58%   |
| Poland       | 90        | 2.55%   |
| Netherlands  | 83        | 2.35%   |
| India        | 67        | 1.9%    |
| Australia    | 67        | 1.9%    |
| Ukraine      | 63        | 1.78%   |
| Mexico       | 46        | 1.3%    |
| Switzerland  | 44        | 1.25%   |
| Hungary      | 44        | 1.25%   |
| Czechia      | 35        | 0.99%   |
| Belgium      | 34        | 0.96%   |
| Argentina    | 33        | 0.93%   |
| Austria      | 32        | 0.91%   |
| Turkey       | 26        | 0.74%   |
| Indonesia    | 26        | 0.74%   |
| Greece       | 24        | 0.68%   |
| South Africa | 23        | 0.65%   |
| Sweden       | 22        | 0.62%   |
| Bulgaria     | 22        | 0.62%   |
| Romania      | 21        | 0.59%   |
| Finland      | 21        | 0.59%   |
| Denmark      | 19        | 0.54%   |
| Slovenia     | 18        | 0.51%   |
| Portugal     | 17        | 0.48%   |
| New Zealand  | 17        | 0.48%   |
| Serbia       | 16        | 0.45%   |
| China        | 16        | 0.45%   |
| Belarus      | 16        | 0.45%   |
| Slovakia     | 15        | 0.42%   |
| Colombia     | 14        | 0.4%    |
| Israel       | 13        | 0.37%   |
| Ireland      | 13        | 0.37%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 68        | 1.84%   |
| Berlin            | 40        | 1.08%   |
| Paris             | 32        | 0.87%   |
| St Petersburg     | 29        | 0.79%   |
| Milan             | 29        | 0.79%   |
| Hamburg           | 26        | 0.7%    |
| Warsaw            | 24        | 0.65%   |
| Rome              | 24        | 0.65%   |
| Sao Paulo         | 22        | 0.6%    |
| Budapest          | 21        | 0.57%   |
| Madrid            | 19        | 0.51%   |
| Sydney            | 18        | 0.49%   |
| Rio de Janeiro    | 18        | 0.49%   |
| Kyiv              | 18        | 0.49%   |
| Cologne           | 18        | 0.49%   |
| Amsterdam         | 18        | 0.49%   |
| Zurich            | 17        | 0.46%   |
| Vienna            | 17        | 0.46%   |
| Munich            | 16        | 0.43%   |
| Melbourne         | 16        | 0.43%   |
| Frankfurt am Main | 15        | 0.41%   |
| Sofia             | 14        | 0.38%   |
| London            | 14        | 0.38%   |
| Dallas            | 14        | 0.38%   |
| Minsk             | 13        | 0.35%   |
| Seattle           | 12        | 0.33%   |
| Prague            | 12        | 0.33%   |
| Novosibirsk       | 12        | 0.33%   |
| Jakarta           | 12        | 0.33%   |
| Montreal          | 11        | 0.3%    |
| Los Angeles       | 11        | 0.3%    |
| Belgrade          | 11        | 0.3%    |
| Athens            | 11        | 0.3%    |
| Wroclaw           | 10        | 0.27%   |
| Miami             | 10        | 0.27%   |
| Auckland          | 10        | 0.27%   |
| San Francisco     | 9         | 0.24%   |
| Phoenix           | 9         | 0.24%   |
| Krakow            | 9         | 0.24%   |
| Dublin            | 9         | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 1000      | 1505   | 17.98%  |
| WDC                       | 826       | 1312   | 14.85%  |
| Seagate                   | 727       | 1087   | 13.07%  |
| Toshiba                   | 333       | 444    | 5.99%   |
| Kingston                  | 327       | 390    | 5.88%   |
| SanDisk                   | 293       | 362    | 5.27%   |
| Crucial                   | 227       | 282    | 4.08%   |
| Unknown                   | 185       | 231    | 3.33%   |
| Intel                     | 171       | 228    | 3.07%   |
| Hitachi                   | 143       | 173    | 2.57%   |
| SK hynix                  | 142       | 172    | 2.55%   |
| HGST                      | 104       | 132    | 1.87%   |
| Micron Technology         | 94        | 104    | 1.69%   |
| A-DATA Technology         | 77        | 84     | 1.38%   |
| Phison                    | 49        | 64     | 0.88%   |
| KIOXIA                    | 48        | 54     | 0.86%   |
| China                     | 40        | 55     | 0.72%   |
| Silicon Motion            | 33        | 38     | 0.59%   |
| Apple                     | 32        | 36     | 0.58%   |
| PNY                       | 30        | 36     | 0.54%   |
| SPCC                      | 29        | 34     | 0.52%   |
| Intenso                   | 29        | 33     | 0.52%   |
| Transcend                 | 28        | 30     | 0.5%    |
| Patriot                   | 27        | 35     | 0.49%   |
| OCZ                       | 24        | 31     | 0.43%   |
| LITEON                    | 23        | 25     | 0.41%   |
| Corsair                   | 23        | 36     | 0.41%   |
| Maxtor                    | 22        | 25     | 0.4%    |
| JMicron Technology        | 18        | 20     | 0.32%   |
| GOODRAM                   | 18        | 33     | 0.32%   |
| Phison Electronics        | 16        | 16     | 0.29%   |
| Micron/Crucial Technology | 16        | 21     | 0.29%   |
| Unknown                   | 16        | 17     | 0.29%   |
| XPG                       | 14        | 15     | 0.25%   |
| SABRENT                   | 14        | 17     | 0.25%   |
| Team                      | 13        | 14     | 0.23%   |
| LITEONIT                  | 13        | 15     | 0.23%   |
| KingSpec                  | 13        | 15     | 0.23%   |
| Gigabyte Technology       | 11        | 12     | 0.2%    |
| Fujitsu                   | 11        | 14     | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB                           | 59        | 0.95%   |
| Kingston SA400S37240G 240GB SSD                     | 55        | 0.88%   |
| Samsung SSD 850 EVO 500GB                           | 48        | 0.77%   |
| Samsung SSD 850 EVO 250GB                           | 47        | 0.75%   |
| Seagate ST1000LM035-1RK172 1TB                      | 40        | 0.64%   |
| Kingston SA400S37480G 480GB SSD                     | 39        | 0.63%   |
| Samsung SSD 860 EVO 1TB                             | 38        | 0.61%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 34        | 0.55%   |
| Samsung NVMe SSD Drive 500GB                        | 33        | 0.53%   |
| Toshiba MQ01ABD100 1TB                              | 31        | 0.5%    |
| Crucial CT1000MX500SSD1 1TB                         | 31        | 0.5%    |
| Samsung NVMe SSD Drive 1TB                          | 30        | 0.48%   |
| HGST HTS721010A9E630 1TB                            | 30        | 0.48%   |
| Unknown MMC Card  32GB                              | 29        | 0.47%   |
| Unknown MMC Card  64GB                              | 28        | 0.45%   |
| Toshiba MQ04ABF100 1TB                              | 28        | 0.45%   |
| Samsung SSD 970 EVO Plus 1TB                        | 28        | 0.45%   |
| Samsung NVMe SSD Drive 512GB                        | 28        | 0.45%   |
| Samsung SSD 970 EVO Plus 500GB                      | 26        | 0.42%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 24        | 0.39%   |
| Seagate ST4000DM004-2CV104 4TB                      | 24        | 0.39%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 24        | 0.39%   |
| Toshiba HDWD110 1TB                                 | 23        | 0.37%   |
| Seagate ST1000DM010-2EP102 1TB                      | 23        | 0.37%   |
| Samsung SSD 860 EVO 250GB                           | 23        | 0.37%   |
| Seagate ST500DM002-1BD142 500GB                     | 22        | 0.35%   |
| Seagate ST1000DM003-1CH162 1TB                      | 21        | 0.34%   |
| Crucial CT500MX500SSD1 500GB                        | 21        | 0.34%   |
| Toshiba DT01ACA100 1TB                              | 20        | 0.32%   |
| Seagate ST2000DM008-2FR102 2TB                      | 20        | 0.32%   |
| Seagate ST2000DM001-1ER164 2TB                      | 20        | 0.32%   |
| Seagate ST1000DM003-1ER162 1TB                      | 20        | 0.32%   |
| Seagate Expansion+ 2TB                              | 19        | 0.3%    |
| SanDisk SSD PLUS 240GB                              | 19        | 0.3%    |
| Kingston SA400S37120G 120GB SSD                     | 19        | 0.3%    |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 18        | 0.29%   |
| Seagate ST500LT012-1DG142 500GB                     | 18        | 0.29%   |
| SanDisk NVMe SSD Drive 512GB                        | 18        | 0.29%   |
| Kingston SUV400S37240G 240GB SSD                    | 18        | 0.29%   |
| Crucial CT240BX500SSD1 240GB                        | 18        | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 708       | 1050   | 35.07%  |
| WDC                 | 628       | 1032   | 31.1%   |
| Toshiba             | 231       | 311    | 11.44%  |
| Hitachi             | 143       | 173    | 7.08%   |
| HGST                | 103       | 131    | 5.1%    |
| Samsung Electronics | 102       | 153    | 5.05%   |
| Unknown             | 21        | 24     | 1.04%   |
| Maxtor              | 21        | 24     | 1.04%   |
| SABRENT             | 14        | 17     | 0.69%   |
| Apple               | 12        | 12     | 0.59%   |
| Fujitsu             | 10        | 13     | 0.5%    |
| ASMT                | 6         | 7      | 0.3%    |
| Hewlett-Packard     | 3         | 5      | 0.15%   |
| USB3.0              | 2         | 2      | 0.1%    |
| SAGE                | 2         | 2      | 0.1%    |
| JMicron Technology  | 2         | 2      | 0.1%    |
| WD MediaMax         | 1         | 1      | 0.05%   |
| USB                 | 1         | 1      | 0.05%   |
| Magnetic Data       | 1         | 2      | 0.05%   |
| LIO-ORG             | 1         | 1      | 0.05%   |
| LaCie               | 1         | 1      | 0.05%   |
| KESU                | 1         | 1      | 0.05%   |
| ipTIME              | 1         | 1      | 0.05%   |
| IET                 | 1         | 1      | 0.05%   |
| HPE                 | 1         | 6      | 0.05%   |
| HGST HTS            | 1         | 1      | 0.05%   |
| ASMedia             | 1         | 1      | 0.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 514       | 714    | 27.14%  |
| Kingston            | 243       | 287    | 12.83%  |
| Crucial             | 191       | 243    | 10.08%  |
| SanDisk             | 185       | 222    | 9.77%   |
| WDC                 | 97        | 125    | 5.12%   |
| Intel               | 55        | 68     | 2.9%    |
| A-DATA Technology   | 52        | 58     | 2.75%   |
| China               | 39        | 54     | 2.06%   |
| Toshiba             | 33        | 48     | 1.74%   |
| Micron Technology   | 33        | 36     | 1.74%   |
| Patriot             | 27        | 35     | 1.43%   |
| PNY                 | 26        | 32     | 1.37%   |
| SK hynix            | 25        | 27     | 1.32%   |
| Intenso             | 25        | 28     | 1.32%   |
| OCZ                 | 24        | 31     | 1.27%   |
| SPCC                | 23        | 27     | 1.21%   |
| Transcend           | 22        | 22     | 1.16%   |
| LITEON              | 18        | 19     | 0.95%   |
| GOODRAM             | 18        | 33     | 0.95%   |
| LITEONIT            | 13        | 15     | 0.69%   |
| KingSpec            | 13        | 15     | 0.69%   |
| Corsair             | 13        | 24     | 0.69%   |
| Team                | 12        | 12     | 0.63%   |
| Apple               | 12        | 12     | 0.63%   |
| Apacer              | 11        | 16     | 0.58%   |
| Mushkin             | 8         | 9      | 0.42%   |
| JMicron Technology  | 8         | 9      | 0.42%   |
| Verbatim            | 6         | 8      | 0.32%   |
| Plextor             | 6         | 7      | 0.32%   |
| Netac               | 6         | 7      | 0.32%   |
| Lexar               | 6         | 7      | 0.32%   |
| Emtec               | 6         | 6      | 0.32%   |
| Dogfish             | 6         | 6      | 0.32%   |
| Seagate             | 5         | 10     | 0.26%   |
| Unknown             | 4         | 4      | 0.21%   |
| KingDian            | 4         | 5      | 0.21%   |
| Gigabyte Technology | 4         | 4      | 0.21%   |
| Drevo               | 4         | 5      | 0.21%   |
| Unknown             | 4         | 4      | 0.21%   |
| Zheino              | 3         | 5      | 0.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 1624      | 2408   | 33.05%  |
| HDD     | 1622      | 2975   | 33.01%  |
| NVMe    | 1425      | 1920   | 29%     |
| MMC     | 163       | 202    | 3.32%   |
| Unknown | 80        | 112    | 1.63%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2496      | 5190   | 58.09%  |
| NVMe | 1422      | 1910   | 33.09%  |
| SAS  | 216       | 315    | 5.03%   |
| MMC  | 163       | 202    | 3.79%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1755      | 2755   | 50.45%  |
| 0.51-1.0   | 1077      | 1603   | 30.96%  |
| 1.01-2.0   | 366       | 553    | 10.52%  |
| 3.01-4.0   | 121       | 218    | 3.48%   |
| 2.01-3.0   | 79        | 113    | 2.27%   |
| 4.01-10.0  | 72        | 125    | 2.07%   |
| 10.01-20.0 | 9         | 16     | 0.26%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 890       | 24.36%  |
| 251-500        | 879       | 24.06%  |
| 501-1000       | 673       | 18.42%  |
| 1001-2000      | 383       | 10.48%  |
| More than 3000 | 279       | 7.64%   |
| 51-100         | 185       | 5.06%   |
| 2001-3000      | 164       | 4.49%   |
| 1-20           | 99        | 2.71%   |
| 21-50          | 86        | 2.35%   |
| Unknown        | 16        | 0.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 854       | 22.69%  |
| 101-250        | 651       | 17.3%   |
| 21-50          | 588       | 15.63%  |
| 51-100         | 497       | 13.21%  |
| 251-500        | 441       | 11.72%  |
| 501-1000       | 330       | 8.77%   |
| 1001-2000      | 191       | 5.08%   |
| More than 3000 | 132       | 3.51%   |
| 2001-3000      | 63        | 1.67%   |
| Unknown        | 16        | 0.43%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| HGST HTS721010A9E630 1TB             | 6         | 7      | 1.52%   |
| Seagate ST500DM002-1BD142 500GB      | 5         | 5      | 1.26%   |
| Seagate ST31000524AS 1TB             | 5         | 6      | 1.26%   |
| Seagate ST1000LM035-1RK172 1TB       | 5         | 5      | 1.26%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 5         | 11     | 1.26%   |
| Seagate ST500LT012-9WS142 500GB      | 4         | 4      | 1.01%   |
| Seagate ST1000DM003-1CH162 1TB       | 4         | 9      | 1.01%   |
| Crucial CT525MX300SSD1 528GB         | 4         | 4      | 1.01%   |
| Crucial CT1050MX300SSD1 1TB          | 4         | 4      | 1.01%   |
| WDC WD5000AAKS-00V1A0 500GB          | 3         | 4      | 0.76%   |
| Toshiba MQ04ABF100 1TB               | 3         | 3      | 0.76%   |
| Toshiba MQ01ABD100 1TB               | 3         | 5      | 0.76%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 3         | 3      | 0.76%   |
| Seagate ST31000528AS 1TB             | 3         | 3      | 0.76%   |
| Seagate ST1000LM048-2E7172 1TB       | 3         | 3      | 0.76%   |
| Kingston SV300S37A120G 120GB SSD     | 3         | 3      | 0.76%   |
| Hitachi HTS547564A9E384 640GB        | 3         | 3      | 0.76%   |
| HGST HTS545050A7E680 500GB           | 3         | 3      | 0.76%   |
| WDC WD5000AAKS-00A7B0 500GB          | 2         | 2      | 0.51%   |
| WDC WD40EZRZ-00GXCB0 4TB             | 2         | 2      | 0.51%   |
| WDC WD3200JD-22KLB0 320GB            | 2         | 2      | 0.51%   |
| WDC WD30EZRX-00MMMB0 3TB             | 2         | 2      | 0.51%   |
| WDC WD20EFRX-68EUZN0 2TB             | 2         | 4      | 0.51%   |
| WDC WD20EARX-00PASB0 2TB             | 2         | 2      | 0.51%   |
| WDC WD15EARS-00Z5B1 1TB              | 2         | 2      | 0.51%   |
| WDC WD10EZEX-08WN4A0 1TB             | 2         | 2      | 0.51%   |
| WDC WD10EARS-00MVWB0 1TB             | 2         | 4      | 0.51%   |
| WDC WD10EADS-00L5B1 1TB              | 2         | 2      | 0.51%   |
| WDC WD1001FALS-40U9B0 1TB            | 2         | 2      | 0.51%   |
| Toshiba MK1652GSX 160GB              | 2         | 2      | 0.51%   |
| Toshiba HDWD110 1TB                  | 2         | 2      | 0.51%   |
| SK hynix SC401 SATA 512GB SSD        | 2         | 2      | 0.51%   |
| SK hynix BC711 HFM512GD3JX013N 512GB | 2         | 2      | 0.51%   |
| Seagate ST9500325AS 500GB            | 2         | 2      | 0.51%   |
| Seagate ST9250315AS 250GB            | 2         | 3      | 0.51%   |
| Seagate ST500LT012-1DG142 500GB      | 2         | 2      | 0.51%   |
| Seagate ST500LM000-1EJ162 500GB      | 2         | 2      | 0.51%   |
| Seagate ST3500418AS 500GB            | 2         | 2      | 0.51%   |
| Seagate ST32000542AS 2TB             | 2         | 2      | 0.51%   |
| Seagate ST3160827AS 160GB            | 2         | 3      | 0.51%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 87        | 111    | 22.77%  |
| WDC                 | 84        | 106    | 21.99%  |
| Samsung Electronics | 36        | 43     | 9.42%   |
| Toshiba             | 31        | 36     | 8.12%   |
| Hitachi             | 25        | 25     | 6.54%   |
| Crucial             | 20        | 24     | 5.24%   |
| SanDisk             | 14        | 15     | 3.66%   |
| HGST                | 14        | 15     | 3.66%   |
| Intel               | 12        | 15     | 3.14%   |
| Kingston            | 10        | 10     | 2.62%   |
| SK hynix            | 9         | 9      | 2.36%   |
| A-DATA Technology   | 6         | 6      | 1.57%   |
| Micron Technology   | 5         | 5      | 1.31%   |
| Maxtor              | 4         | 5      | 1.05%   |
| OCZ                 | 3         | 3      | 0.79%   |
| Apple               | 3         | 3      | 0.79%   |
| LITEONIT            | 2         | 2      | 0.52%   |
| Fujitsu             | 2         | 2      | 0.52%   |
| Zheino              | 1         | 2      | 0.26%   |
| XPG                 | 1         | 1      | 0.26%   |
| VISIPRO             | 1         | 1      | 0.26%   |
| VENO                | 1         | 1      | 0.26%   |
| tecmiyo             | 1         | 3      | 0.26%   |
| T-FORCE             | 1         | 1      | 0.26%   |
| SPCC                | 1         | 1      | 0.26%   |
| R580                | 1         | 1      | 0.26%   |
| Neo                 | 1         | 1      | 0.26%   |
| Mushkin             | 1         | 1      | 0.26%   |
| Intenso             | 1         | 1      | 0.26%   |
| Drevo               | 1         | 1      | 0.26%   |
| BAITITON            | 1         | 3      | 0.26%   |
| ASMT                | 1         | 1      | 0.26%   |
| ASENNO              | 1         | 1      | 0.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 87        | 111    | 33.21%  |
| WDC                 | 82        | 104    | 31.3%   |
| Toshiba             | 27        | 32     | 10.31%  |
| Hitachi             | 25        | 25     | 9.54%   |
| Samsung Electronics | 17        | 23     | 6.49%   |
| HGST                | 14        | 15     | 5.34%   |
| Maxtor              | 4         | 5      | 1.53%   |
| Apple               | 3         | 3      | 1.15%   |
| Fujitsu             | 2         | 2      | 0.76%   |
| ASMT                | 1         | 1      | 0.38%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 239       | 321    | 66.95%  |
| SSD  | 98        | 114    | 27.45%  |
| NVMe | 20        | 20     | 5.6%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB         | 1         | 1      | 16.67%  |
| Samsung Electronics HD502IJ 500GB | 1         | 1      | 16.67%  |
| OCZ VERTEX460A 480GB SSD          | 1         | 1      | 16.67%  |
| Intel SSDSC2KB960G8 960GB         | 1         | 1      | 16.67%  |
| Hitachi HTS547550A9E384 500GB     | 1         | 1      | 16.67%  |
| Acer SSD FA100 256GB              | 1         | 1      | 16.67%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1         | 1      | 16.67%  |
| Samsung Electronics | 1         | 1      | 16.67%  |
| OCZ                 | 1         | 1      | 16.67%  |
| Intel               | 1         | 1      | 16.67%  |
| Hitachi             | 1         | 1      | 16.67%  |
| Acer                | 1         | 1      | 16.67%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1818      | 3193   | 45.86%  |
| Detected | 1793      | 3963   | 45.23%  |
| Malfunc  | 348       | 455    | 8.78%   |
| Failed   | 5         | 6      | 0.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2248      | 47.75%  |
| AMD                              | 802       | 17.03%  |
| Samsung Electronics              | 472       | 10.03%  |
| SanDisk                          | 236       | 5.01%   |
| SK hynix                         | 116       | 2.46%   |
| Kingston Technology Company      | 95        | 2.02%   |
| Phison Electronics               | 83        | 1.76%   |
| Toshiba America Info Systems     | 79        | 1.68%   |
| ASMedia Technology               | 78        | 1.66%   |
| Micron Technology                | 61        | 1.3%    |
| Micron/Crucial Technology        | 52        | 1.1%    |
| Silicon Motion                   | 47        | 1%      |
| JMicron Technology               | 47        | 1%      |
| KIOXIA                           | 45        | 0.96%   |
| Marvell Technology Group         | 41        | 0.87%   |
| ADATA Technology                 | 39        | 0.83%   |
| Nvidia                           | 35        | 0.74%   |
| Realtek Semiconductor            | 21        | 0.45%   |
| Solid State Storage Technology   | 15        | 0.32%   |
| Union Memory (Shenzhen)          | 12        | 0.25%   |
| Broadcom / LSI                   | 12        | 0.25%   |
| Lite-On Technology               | 10        | 0.21%   |
| LSI Logic / Symbios Logic        | 9         | 0.19%   |
| Silicon Image                    | 8         | 0.17%   |
| VIA Technologies                 | 7         | 0.15%   |
| Apple                            | 6         | 0.13%   |
| Seagate Technology               | 5         | 0.11%   |
| Lenovo                           | 4         | 0.08%   |
| INNOGRIT                         | 3         | 0.06%   |
| Yangtze Memory Technologies      | 2         | 0.04%   |
| Silicon Integrated Systems [SiS] | 2         | 0.04%   |
| Shenzhen Longsys Electronics     | 2         | 0.04%   |
| Netac Technology                 | 2         | 0.04%   |
| Integrated Technology Express    | 2         | 0.04%   |
| Adaptec                          | 2         | 0.04%   |
| Zhaoxin                          | 1         | 0.02%   |
| Promise Technology               | 1         | 0.02%   |
| OCZ Technology Group             | 1         | 0.02%   |
| O2 Micro                         | 1         | 0.02%   |
| Hewlett-Packard                  | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 571       | 10.67%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 279       | 5.21%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 192       | 3.59%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 175       | 3.27%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 151       | 2.82%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 142       | 2.65%   |
| AMD 400 Series Chipset SATA Controller                                         | 116       | 2.17%   |
| Intel Volume Management Device NVMe RAID Controller                            | 105       | 1.96%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 94        | 1.76%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 90        | 1.68%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 85        | 1.59%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 83        | 1.55%   |
| Samsung NVMe SSD Controller 980                                                | 80        | 1.49%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 79        | 1.48%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 74        | 1.38%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 71        | 1.33%   |
| AMD 500 Series Chipset SATA Controller                                         | 71        | 1.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 70        | 1.31%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 69        | 1.29%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 63        | 1.18%   |
| Micron NVMe Storage Controller                                                 | 61        | 1.14%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 60        | 1.12%   |
| Intel SSD 660P Series                                                          | 59        | 1.1%    |
| Intel Comet Lake SATA AHCI Controller                                          | 56        | 1.05%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 55        | 1.03%   |
| Intel SATA Controller [RAID mode]                                              | 55        | 1.03%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 55        | 1.03%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 51        | 0.95%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 50        | 0.93%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 49        | 0.92%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 45        | 0.84%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 43        | 0.8%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 42        | 0.78%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 42        | 0.78%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 41        | 0.77%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 41        | 0.77%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 39        | 0.73%   |
| AMD FCH SATA Controller D                                                      | 39        | 0.73%   |
| AMD 300 Series Chipset SATA Controller                                         | 39        | 0.73%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 38        | 0.71%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2604      | 55.19%  |
| NVMe | 1419      | 30.08%  |
| RAID | 357       | 7.57%   |
| IDE  | 319       | 6.76%   |
| SAS  | 12        | 0.25%   |
| SCSI | 7         | 0.15%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor        | Computers | Percent |
|---------------|-----------|---------|
| Intel         | 2534      | 71.93%  |
| AMD           | 982       | 27.87%  |
| ARM           | 3         | 0.09%   |
| sifive,u74-mc | 1         | 0.03%   |
| QUALCOMM      | 1         | 0.03%   |
| Phytium       | 1         | 0.03%   |
| CentaurHauls  | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 57        | 1.61%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 47        | 1.33%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 45        | 1.27%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 39        | 1.1%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 38        | 1.08%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 38        | 1.08%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 37        | 1.05%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 37        | 1.05%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 37        | 1.05%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 37        | 1.05%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 37        | 1.05%   |
| AMD Ryzen 5 3600 6-Core Processor             | 36        | 1.02%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 33        | 0.93%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 32        | 0.91%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 31        | 0.88%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 30        | 0.85%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 28        | 0.79%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 28        | 0.79%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 26        | 0.74%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 25        | 0.71%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 25        | 0.71%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 23        | 0.65%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 22        | 0.62%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 21        | 0.59%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 21        | 0.59%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 20        | 0.57%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 19        | 0.54%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 19        | 0.54%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 18        | 0.51%   |
| AMD FX-8350 Eight-Core Processor              | 18        | 0.51%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 17        | 0.48%   |
| Intel 12th Gen Core i7-12700H                 | 17        | 0.48%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 17        | 0.48%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 17        | 0.48%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 16        | 0.45%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 16        | 0.45%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 16        | 0.45%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 16        | 0.45%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 16        | 0.45%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 15        | 0.42%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 825       | 23.37%  |
| Intel Core i5           | 765       | 21.67%  |
| AMD Ryzen 5             | 277       | 7.85%   |
| Other                   | 261       | 7.39%   |
| AMD Ryzen 7             | 235       | 6.66%   |
| Intel Core i3           | 192       | 5.44%   |
| Intel Celeron           | 122       | 3.46%   |
| Intel Core 2 Duo        | 84        | 2.38%   |
| AMD Ryzen 9             | 83        | 2.35%   |
| Intel Xeon              | 79        | 2.24%   |
| Intel Pentium           | 63        | 1.78%   |
| AMD FX                  | 62        | 1.76%   |
| AMD Ryzen 3             | 41        | 1.16%   |
| Intel Core i9           | 33        | 0.93%   |
| AMD A10                 | 30        | 0.85%   |
| AMD A6                  | 29        | 0.82%   |
| Intel Atom              | 26        | 0.74%   |
| AMD A8                  | 26        | 0.74%   |
| Intel Pentium Dual-Core | 24        | 0.68%   |
| AMD Ryzen 7 PRO         | 23        | 0.65%   |
| Intel Core 2 Quad       | 21        | 0.59%   |
| AMD Phenom II X4        | 21        | 0.59%   |
| Intel Pentium Silver    | 15        | 0.42%   |
| AMD Athlon II X4        | 14        | 0.4%    |
| AMD Ryzen 5 PRO         | 13        | 0.37%   |
| AMD A4                  | 13        | 0.37%   |
| AMD Ryzen Threadripper  | 9         | 0.25%   |
| AMD Athlon              | 9         | 0.25%   |
| Intel Genuine           | 8         | 0.23%   |
| AMD E1                  | 8         | 0.23%   |
| AMD E                   | 8         | 0.23%   |
| AMD Athlon II X2        | 8         | 0.23%   |
| Intel Pentium Dual      | 7         | 0.2%    |
| AMD Athlon 64 X2        | 7         | 0.2%    |
| Intel Core m3           | 6         | 0.17%   |
| AMD Phenom II X6        | 6         | 0.17%   |
| AMD E2                  | 6         | 0.17%   |
| Intel Core 2            | 5         | 0.14%   |
| Intel Celeron Dual-Core | 5         | 0.14%   |
| AMD Sempron             | 5         | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 1418      | 40.18%  |
| 2       | 1107      | 31.37%  |
| 6       | 457       | 12.95%  |
| 8       | 336       | 9.52%   |
| 12      | 70        | 1.98%   |
| 16      | 38        | 1.08%   |
| 1       | 35        | 0.99%   |
| 14      | 24        | 0.68%   |
| 10      | 18        | 0.51%   |
| 3       | 8         | 0.23%   |
| 32      | 4         | 0.11%   |
| 24      | 4         | 0.11%   |
| 20      | 3         | 0.09%   |
| 18      | 2         | 0.06%   |
| Unknown | 2         | 0.06%   |
| 64      | 1         | 0.03%   |
| 36      | 1         | 0.03%   |
| 5       | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3494      | 99.18%  |
| 2       | 24        | 0.68%   |
| 4       | 2         | 0.06%   |
| Unknown | 2         | 0.06%   |
| 3       | 1         | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2657      | 75.27%  |
| 1       | 871       | 24.67%  |
| Unknown | 2         | 0.06%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3518      | 99.86%  |
| 32-bit         | 2         | 0.06%   |
| Unknown        | 2         | 0.06%   |
| 64-bit         | 1         | 0.03%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 921       | 25.4%   |
| 0x306a9    | 171       | 4.72%   |
| 0x306c3    | 157       | 4.33%   |
| 0x206a7    | 154       | 4.25%   |
| 0x906ea    | 121       | 3.34%   |
| 0x806ec    | 105       | 2.9%    |
| 0x806c1    | 99        | 2.73%   |
| 0x806ea    | 93        | 2.56%   |
| 0x40651    | 79        | 2.18%   |
| 0x1067a    | 76        | 2.1%    |
| 0x806e9    | 75        | 2.07%   |
| 0x906e9    | 74        | 2.04%   |
| 0x08701021 | 71        | 1.96%   |
| 0x506e3    | 68        | 1.88%   |
| 0x406e3    | 58        | 1.6%    |
| 0x0a50000c | 50        | 1.38%   |
| 0x08108109 | 50        | 1.38%   |
| 0x0800820d | 45        | 1.24%   |
| 0x306d4    | 44        | 1.21%   |
| 0x08600106 | 43        | 1.19%   |
| 0x08701013 | 38        | 1.05%   |
| 0x06000852 | 38        | 1.05%   |
| 0x08108102 | 36        | 0.99%   |
| 0xa0652    | 34        | 0.94%   |
| 0x706e5    | 34        | 0.94%   |
| 0x906a3    | 33        | 0.91%   |
| 0x806eb    | 32        | 0.88%   |
| 0x906ed    | 29        | 0.8%    |
| 0x20655    | 27        | 0.74%   |
| 0x010000c8 | 27        | 0.74%   |
| 0x706a1    | 26        | 0.72%   |
| 0x08608103 | 23        | 0.63%   |
| 0x706a8    | 22        | 0.61%   |
| 0x406c4    | 22        | 0.61%   |
| 0x08600104 | 20        | 0.55%   |
| 0xa0653    | 19        | 0.52%   |
| 0x10676    | 19        | 0.52%   |
| 0x806d1    | 18        | 0.5%    |
| 0x30678    | 18        | 0.5%    |
| 0x06001119 | 18        | 0.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 685       | 19.39%  |
| Haswell          | 345       | 9.77%   |
| IvyBridge        | 243       | 6.88%   |
| Zen 2            | 235       | 6.65%   |
| SandyBridge      | 208       | 5.89%   |
| Zen+             | 175       | 4.95%   |
| Skylake          | 170       | 4.81%   |
| TigerLake        | 141       | 3.99%   |
| Zen 3            | 138       | 3.91%   |
| Penryn           | 118       | 3.34%   |
| Unknown          | 107       | 3.03%   |
| CometLake        | 94        | 2.66%   |
| Zen              | 85        | 2.41%   |
| Piledriver       | 80        | 2.27%   |
| IceLake          | 73        | 2.07%   |
| Goldmont plus    | 67        | 1.9%    |
| Westmere         | 65        | 1.84%   |
| K10              | 64        | 1.81%   |
| Broadwell        | 62        | 1.76%   |
| Silvermont       | 58        | 1.64%   |
| Core             | 50        | 1.42%   |
| Alderlake Hybrid | 47        | 1.33%   |
| Excavator        | 42        | 1.19%   |
| Nehalem          | 40        | 1.13%   |
| Goldmont         | 21        | 0.59%   |
| Steamroller      | 18        | 0.51%   |
| Puma             | 18        | 0.51%   |
| K10 Llano        | 17        | 0.48%   |
| K8 Hammer        | 14        | 0.4%    |
| Jaguar           | 14        | 0.4%    |
| Bobcat           | 14        | 0.4%    |
| NetBurst         | 7         | 0.2%    |
| Bulldozer        | 7         | 0.2%    |
| Bonnell          | 5         | 0.14%   |
| Tremont          | 2         | 0.06%   |
| K8 & K10 hybrid  | 2         | 0.06%   |
| K6               | 1         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1950      | 45.69%  |
| Nvidia                           | 1296      | 30.37%  |
| AMD                              | 1003      | 23.5%   |
| ASPEED Technology                | 8         | 0.19%   |
| Matrox Electronics Systems       | 7         | 0.16%   |
| ATI Technologies                 | 2         | 0.05%   |
| Zhaoxin                          | 1         | 0.02%   |
| Silicon Integrated Systems [SiS] | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 142       | 3.25%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 136       | 3.11%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 131       | 3%      |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 119       | 2.73%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 110       | 2.52%   |
| AMD Renoir                                                                               | 104       | 2.38%   |
| Intel UHD Graphics 620                                                                   | 103       | 2.36%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 90        | 2.06%   |
| Intel HD Graphics 620                                                                    | 90        | 2.06%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 88        | 2.02%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 80        | 1.83%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 75        | 1.72%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 75        | 1.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 69        | 1.58%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 68        | 1.56%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 67        | 1.53%   |
| Intel HD Graphics 630                                                                    | 57        | 1.31%   |
| Intel HD Graphics 530                                                                    | 53        | 1.21%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 53        | 1.21%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 49        | 1.12%   |
| Intel HD Graphics 5500                                                                   | 49        | 1.12%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 46        | 1.05%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 45        | 1.03%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 39        | 0.89%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 37        | 0.85%   |
| AMD Lucienne                                                                             | 37        | 0.85%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 35        | 0.8%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 33        | 0.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 33        | 0.76%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 30        | 0.69%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 29        | 0.66%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 29        | 0.66%   |
| Intel Core Processor Integrated Graphics Controller                                      | 27        | 0.62%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 25        | 0.57%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 25        | 0.57%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 24        | 0.55%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 23        | 0.53%   |
| Intel Iris Plus Graphics G7                                                              | 23        | 0.53%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 23        | 0.53%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 23        | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1287      | 36.39%  |
| 1 x AMD                  | 779       | 22.02%  |
| 1 x Nvidia               | 674       | 19.06%  |
| Intel + Nvidia           | 530       | 14.98%  |
| Intel + AMD              | 97        | 2.74%   |
| AMD + Nvidia             | 70        | 1.98%   |
| 2 x AMD                  | 58        | 1.64%   |
| 2 x Nvidia               | 14        | 0.4%    |
| Other                    | 7         | 0.2%    |
| Nvidia + ASPEED          | 4         | 0.11%   |
| 1 x ASPEED               | 4         | 0.11%   |
| Nvidia + Matrox          | 3         | 0.08%   |
| 3 x Nvidia               | 2         | 0.06%   |
| 1 x Matrox               | 2         | 0.06%   |
| AMD + Matrox             | 2         | 0.06%   |
| 2 x Intel                | 1         | 0.03%   |
| 1 x Zhaoxin              | 1         | 0.03%   |
| 1 x SiS                  | 1         | 0.03%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2562      | 71.87%  |
| Proprietary | 934       | 26.2%   |
| Unknown     | 69        | 1.94%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1931      | 53.49%  |
| 1.01-2.0   | 423       | 11.72%  |
| 0.01-0.5   | 323       | 8.95%   |
| 3.01-4.0   | 281       | 7.78%   |
| 0.51-1.0   | 267       | 7.4%    |
| 7.01-8.0   | 189       | 5.24%   |
| 5.01-6.0   | 106       | 2.94%   |
| 8.01-16.0  | 46        | 1.27%   |
| 2.01-3.0   | 34        | 0.94%   |
| 16.01-24.0 | 6         | 0.17%   |
| 4.01-5.0   | 3         | 0.08%   |
| 32.01-64.0 | 1         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 522       | 12.58%  |
| AU Optronics            | 444       | 10.7%   |
| BOE                     | 362       | 8.72%   |
| LG Display              | 358       | 8.62%   |
| Chimei Innolux          | 341       | 8.21%   |
| Dell                    | 277       | 6.67%   |
| Goldstar                | 225       | 5.42%   |
| Acer                    | 151       | 3.64%   |
| Hewlett-Packard         | 141       | 3.4%    |
| BenQ                    | 110       | 2.65%   |
| Ancor Communications    | 106       | 2.55%   |
| Sharp                   | 102       | 2.46%   |
| AOC                     | 101       | 2.43%   |
| Philips                 | 99        | 2.38%   |
| Lenovo                  | 59        | 1.42%   |
| ViewSonic               | 54        | 1.3%    |
| ASUSTek Computer        | 51        | 1.23%   |
| Iiyama                  | 48        | 1.16%   |
| Chi Mei Optoelectronics | 42        | 1.01%   |
| PANDA                   | 41        | 0.99%   |
| Apple                   | 40        | 0.96%   |
| LG Electronics          | 30        | 0.72%   |
| InfoVision              | 30        | 0.72%   |
| Unknown                 | 23        | 0.55%   |
| Sony                    | 22        | 0.53%   |
| NEC Computers           | 20        | 0.48%   |
| Panasonic               | 18        | 0.43%   |
| HannStar                | 13        | 0.31%   |
| Sceptre Tech            | 12        | 0.29%   |
| CSO                     | 12        | 0.29%   |
| MSI                     | 11        | 0.26%   |
| Eizo                    | 11        | 0.26%   |
| Toshiba                 | 10        | 0.24%   |
| Medion                  | 10        | 0.24%   |
| Vizio                   | 9         | 0.22%   |
| Idek Iiyama             | 8         | 0.19%   |
| Vestel Elektronik       | 7         | 0.17%   |
| LG Philips              | 6         | 0.14%   |
| HKC                     | 5         | 0.12%   |
| Gigabyte Technology     | 5         | 0.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch         | 20        | 0.46%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 19        | 0.44%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch   | 18        | 0.42%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch         | 18        | 0.42%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 17        | 0.39%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 16        | 0.37%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch       | 16        | 0.37%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch            | 14        | 0.32%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 14        | 0.32%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch       | 12        | 0.28%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch        | 12        | 0.28%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 11        | 0.25%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                  | 11        | 0.25%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch          | 11        | 0.25%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 10        | 0.23%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch       | 10        | 0.23%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch         | 10        | 0.23%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 9         | 0.21%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch           | 9         | 0.21%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 9         | 0.21%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                | 8         | 0.18%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 8         | 0.18%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch           | 8         | 0.18%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch               | 8         | 0.18%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 8         | 0.18%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch        | 8         | 0.18%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch         | 8         | 0.18%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch         | 8         | 0.18%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 7         | 0.16%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch  | 7         | 0.16%   |
| Panasonic VVX16T029D00 MEI96A2 2880x1620 344x193mm 15.5-inch           | 7         | 0.16%   |
| InfoVision LCD Monitor IVO057F 1920x1080 309x174mm 14.0-inch           | 7         | 0.16%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch                | 7         | 0.16%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                  | 7         | 0.16%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch       | 7         | 0.16%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch       | 7         | 0.16%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                  | 7         | 0.16%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                | 6         | 0.14%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                | 6         | 0.14%   |
| Samsung Electronics SyncMaster SAM0587 1920x1200 518x324mm 24.1-inch   | 6         | 0.14%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1894      | 48.39%  |
| 1366x768 (WXGA)    | 562       | 14.36%  |
| 3840x2160 (4K)     | 273       | 6.97%   |
| 2560x1440 (QHD)    | 210       | 5.37%   |
| 1600x900 (HD+)     | 139       | 3.55%   |
| 1920x1200 (WUXGA)  | 121       | 3.09%   |
| 1680x1050 (WSXGA+) | 92        | 2.35%   |
| 1280x1024 (SXGA)   | 82        | 2.1%    |
| Unknown            | 74        | 1.89%   |
| 1440x900 (WXGA+)   | 50        | 1.28%   |
| 3440x1440          | 49        | 1.25%   |
| 2560x1080          | 42        | 1.07%   |
| 1280x800 (WXGA)    | 38        | 0.97%   |
| 3840x1080          | 33        | 0.84%   |
| 1360x768           | 28        | 0.72%   |
| 2560x1600          | 27        | 0.69%   |
| 2880x1800          | 22        | 0.56%   |
| 2160x1440          | 18        | 0.46%   |
| 3840x2400          | 17        | 0.43%   |
| 1600x1200          | 11        | 0.28%   |
| 1024x768 (XGA)     | 11        | 0.28%   |
| 1920x540           | 10        | 0.26%   |
| 3840x1200          | 9         | 0.23%   |
| 3200x1800 (QHD+)   | 7         | 0.18%   |
| 4480x1440          | 6         | 0.15%   |
| 2256x1504          | 6         | 0.15%   |
| 2240x1400          | 6         | 0.15%   |
| 3840x1600          | 5         | 0.13%   |
| 1920x1280          | 5         | 0.13%   |
| 5760x1080          | 4         | 0.1%    |
| 2520x1680          | 4         | 0.1%    |
| 2288x1287          | 4         | 0.1%    |
| 1280x720 (HD)      | 4         | 0.1%    |
| 3600x1080          | 3         | 0.08%   |
| 3456x2160          | 3         | 0.08%   |
| 3200x1080          | 3         | 0.08%   |
| 2736x1824          | 3         | 0.08%   |
| 7680x2160          | 2         | 0.05%   |
| 5760x2160          | 2         | 0.05%   |
| 4480x1080          | 2         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 993       | 24.02%  |
| 27      | 353       | 8.54%   |
| 13      | 345       | 8.35%   |
| 24      | 339       | 8.2%    |
| 14      | 318       | 7.69%   |
| 23      | 298       | 7.21%   |
| 17      | 245       | 5.93%   |
| 21      | 230       | 5.56%   |
| Unknown | 228       | 5.52%   |
| 31      | 93        | 2.25%   |
| 34      | 79        | 1.91%   |
| 19      | 74        | 1.79%   |
| 22      | 59        | 1.43%   |
| 20      | 54        | 1.31%   |
| 12      | 49        | 1.19%   |
| 18      | 47        | 1.14%   |
| 11      | 44        | 1.06%   |
| 16      | 37        | 0.9%    |
| 84      | 26        | 0.63%   |
| 32      | 26        | 0.63%   |
| 25      | 24        | 0.58%   |
| 72      | 20        | 0.48%   |
| 54      | 19        | 0.46%   |
| 40      | 18        | 0.44%   |
| 26      | 12        | 0.29%   |
| 48      | 7         | 0.17%   |
| 47      | 7         | 0.17%   |
| 46      | 7         | 0.17%   |
| 28      | 7         | 0.17%   |
| 42      | 6         | 0.15%   |
| 37      | 6         | 0.15%   |
| 36      | 5         | 0.12%   |
| 10      | 5         | 0.12%   |
| 65      | 4         | 0.1%    |
| 60      | 4         | 0.1%    |
| 52      | 4         | 0.1%    |
| 49      | 4         | 0.1%    |
| 39      | 4         | 0.1%    |
| 142     | 3         | 0.07%   |
| 74      | 3         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1511      | 37.55%  |
| 501-600        | 903       | 22.44%  |
| 401-500        | 412       | 10.24%  |
| 351-400        | 285       | 7.08%   |
| 201-300        | 270       | 6.71%   |
| Unknown        | 228       | 5.67%   |
| 601-700        | 141       | 3.5%    |
| 701-800        | 112       | 2.78%   |
| 1001-1500      | 63        | 1.57%   |
| 1501-2000      | 53        | 1.32%   |
| 801-900        | 32        | 0.8%    |
| 901-1000       | 8         | 0.2%    |
| More than 2000 | 3         | 0.07%   |
| 1-100          | 2         | 0.05%   |
| 101-200        | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2764      | 76.59%  |
| 16/10   | 385       | 10.67%  |
| Unknown | 201       | 5.57%   |
| 21/9    | 90        | 2.49%   |
| 5/4     | 76        | 2.11%   |
| 3/2     | 44        | 1.22%   |
| 4/3     | 27        | 0.75%   |
| 32/9    | 12        | 0.33%   |
| 1.00    | 3         | 0.08%   |
| 6/5     | 2         | 0.06%   |
| 1.96    | 2         | 0.06%   |
| 3.40    | 1         | 0.03%   |
| 0.62    | 1         | 0.03%   |
| 0.56    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 996       | 24.54%  |
| 201-250        | 701       | 17.27%  |
| 81-90          | 514       | 12.66%  |
| 301-350        | 362       | 8.92%   |
| Unknown        | 228       | 5.62%   |
| 351-500        | 206       | 5.08%   |
| 151-200        | 190       | 4.68%   |
| 121-130        | 184       | 4.53%   |
| 71-80          | 155       | 3.82%   |
| 251-300        | 134       | 3.3%    |
| More than 1000 | 95        | 2.34%   |
| 141-150        | 77        | 1.9%    |
| 501-1000       | 65        | 1.6%    |
| 51-60          | 45        | 1.11%   |
| 61-70          | 41        | 1.01%   |
| 111-120        | 27        | 0.67%   |
| 131-140        | 22        | 0.54%   |
| 91-100         | 9         | 0.22%   |
| 41-50          | 5         | 0.12%   |
| 1-40           | 3         | 0.07%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1235      | 31.35%  |
| 121-160       | 1143      | 29.02%  |
| 101-120       | 872       | 22.14%  |
| 161-240       | 250       | 6.35%   |
| Unknown       | 228       | 5.79%   |
| More than 240 | 120       | 3.05%   |
| 1-50          | 91        | 2.31%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 2664      | 74.12%  |
| 2     | 754       | 20.98%  |
| 3     | 91        | 2.53%   |
| 0     | 75        | 2.09%   |
| 4     | 10        | 0.28%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2015      | 37.88%  |
| Intel                             | 1816      | 34.14%  |
| Qualcomm Atheros                  | 542       | 10.19%  |
| Broadcom                          | 224       | 4.21%   |
| MediaTek                          | 89        | 1.67%   |
| TP-Link                           | 62        | 1.17%   |
| Ralink Technology                 | 62        | 1.17%   |
| Ralink                            | 45        | 0.85%   |
| Broadcom Limited                  | 39        | 0.73%   |
| Marvell Technology Group          | 30        | 0.56%   |
| Nvidia                            | 28        | 0.53%   |
| Samsung Electronics               | 24        | 0.45%   |
| ASIX Electronics                  | 23        | 0.43%   |
| Aquantia                          | 20        | 0.38%   |
| Qualcomm Atheros Communications   | 18        | 0.34%   |
| DisplayLink                       | 18        | 0.34%   |
| NetGear                           | 17        | 0.32%   |
| Microsoft                         | 16        | 0.3%    |
| Xiaomi                            | 15        | 0.28%   |
| Huawei Technologies               | 15        | 0.28%   |
| Lenovo                            | 14        | 0.26%   |
| D-Link                            | 14        | 0.26%   |
| Sierra Wireless                   | 13        | 0.24%   |
| Qualcomm                          | 13        | 0.24%   |
| Dell                              | 11        | 0.21%   |
| Ericsson Business Mobile Networks | 10        | 0.19%   |
| Edimax Technology                 | 8         | 0.15%   |
| JMicron Technology                | 7         | 0.13%   |
| ASUSTek Computer                  | 7         | 0.13%   |
| Apple                             | 7         | 0.13%   |
| Linksys                           | 6         | 0.11%   |
| D-Link System                     | 6         | 0.11%   |
| FIBOCOM                           | 5         | 0.09%   |
| Belkin Components                 | 5         | 0.09%   |
| Hewlett-Packard                   | 4         | 0.08%   |
| Google                            | 4         | 0.08%   |
| AVM                               | 4         | 0.08%   |
| Wacom                             | 3         | 0.06%   |
| VIA Technologies                  | 3         | 0.06%   |
| T & A Mobile Phones               | 3         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1394      | 22.41%  |
| Intel Wi-Fi 6 AX200                                               | 213       | 3.42%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 179       | 2.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 125       | 2.01%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 117       | 1.88%   |
| Intel Wireless 8265 / 8275                                        | 112       | 1.8%    |
| Intel I211 Gigabit Network Connection                             | 109       | 1.75%   |
| Realtek RTL8125 2.5GbE Controller                                 | 108       | 1.74%   |
| Intel Wi-Fi 6 AX201                                               | 101       | 1.62%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 92        | 1.48%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 90        | 1.45%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 87        | 1.4%    |
| Intel Wireless 7260                                               | 86        | 1.38%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 78        | 1.25%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 78        | 1.25%   |
| Intel Wireless 7265                                               | 77        | 1.24%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 71        | 1.14%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 67        | 1.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 62        | 1%      |
| Intel Ethernet Connection (2) I219-V                              | 62        | 1%      |
| Intel Wireless 3165                                               | 59        | 0.95%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 56        | 0.9%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 53        | 0.85%   |
| Intel Ethernet Connection I217-LM                                 | 52        | 0.84%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 50        | 0.8%    |
| Intel Wireless-AC 9260                                            | 47        | 0.76%   |
| Intel Wireless 8260                                               | 47        | 0.76%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 47        | 0.76%   |
| Intel Ethernet Controller I225-V                                  | 46        | 0.74%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 42        | 0.68%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 40        | 0.64%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 37        | 0.59%   |
| Intel Ethernet Connection (7) I219-V                              | 35        | 0.56%   |
| Intel Ethernet Connection (7) I219-LM                             | 35        | 0.56%   |
| Intel Ethernet Connection (4) I219-LM                             | 35        | 0.56%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 34        | 0.55%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 33        | 0.53%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 30        | 0.48%   |
| Ralink MT7601U Wireless Adapter                                   | 29        | 0.47%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 29        | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1396      | 48.46%  |
| Realtek Semiconductor                 | 475       | 16.49%  |
| Qualcomm Atheros                      | 423       | 14.68%  |
| Broadcom                              | 148       | 5.14%   |
| MediaTek                              | 85        | 2.95%   |
| Ralink Technology                     | 62        | 2.15%   |
| TP-Link                               | 56        | 1.94%   |
| Ralink                                | 45        | 1.56%   |
| Broadcom Limited                      | 33        | 1.15%   |
| Qualcomm Atheros Communications       | 18        | 0.62%   |
| NetGear                               | 17        | 0.59%   |
| Microsoft                             | 15        | 0.52%   |
| D-Link                                | 14        | 0.49%   |
| Sierra Wireless                       | 13        | 0.45%   |
| Qualcomm                              | 8         | 0.28%   |
| Edimax Technology                     | 8         | 0.28%   |
| ASUSTek Computer                      | 7         | 0.24%   |
| Marvell Technology Group              | 6         | 0.21%   |
| Dell                                  | 6         | 0.21%   |
| Linksys                               | 5         | 0.17%   |
| FIBOCOM                               | 5         | 0.17%   |
| Belkin Components                     | 5         | 0.17%   |
| D-Link System                         | 4         | 0.14%   |
| AVM                                   | 4         | 0.14%   |
| Wacom                                 | 3         | 0.1%    |
| ZyDAS                                 | 2         | 0.07%   |
| Mercucys                              | 2         | 0.07%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.07%   |
| ZyXEL Communications                  | 1         | 0.03%   |
| Wilocity                              | 1         | 0.03%   |
| Texas Instruments                     | 1         | 0.03%   |
| Tenda                                 | 1         | 0.03%   |
| Sitecom Europe                        | 1         | 0.03%   |
| Philips (or NXP)                      | 1         | 0.03%   |
| Micro Star International              | 1         | 0.03%   |
| LG Electronics                        | 1         | 0.03%   |
| IMC Networks                          | 1         | 0.03%   |
| Hewlett-Packard                       | 1         | 0.03%   |
| Guillemot                             | 1         | 0.03%   |
| Gemtek                                | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 213       | 7.34%   |
| Intel Wireless 8265 / 8275                                     | 112       | 3.86%   |
| Intel Wi-Fi 6 AX201                                            | 101       | 3.48%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 92        | 3.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 90        | 3.1%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 87        | 3%      |
| Intel Wireless 7260                                            | 86        | 2.96%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 78        | 2.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 78        | 2.69%   |
| Intel Wireless 7265                                            | 77        | 2.65%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 71        | 2.45%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 67        | 2.31%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 62        | 2.14%   |
| Intel Wireless 3165                                            | 59        | 2.03%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 56        | 1.93%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 53        | 1.83%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 50        | 1.72%   |
| Intel Wireless-AC 9260                                         | 47        | 1.62%   |
| Intel Wireless 8260                                            | 47        | 1.62%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 47        | 1.62%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 42        | 1.45%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 40        | 1.38%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 37        | 1.27%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 34        | 1.17%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 33        | 1.14%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 30        | 1.03%   |
| Ralink MT7601U Wireless Adapter                                | 29        | 1%      |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 29        | 1%      |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 28        | 0.96%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 26        | 0.9%    |
| Intel Wireless 3160                                            | 26        | 0.9%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 25        | 0.86%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 24        | 0.83%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 24        | 0.83%   |
| Realtek 802.11ac NIC                                           | 24        | 0.83%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 22        | 0.76%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 22        | 0.76%   |
| Broadcom BCM43142 802.11b/g/n                                  | 22        | 0.76%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 20        | 0.69%   |
| Intel Centrino Advanced-N 6235                                 | 19        | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1807      | 56.65%  |
| Intel                            | 886       | 27.77%  |
| Qualcomm Atheros                 | 154       | 4.83%   |
| Broadcom                         | 96        | 3.01%   |
| Nvidia                           | 28        | 0.88%   |
| Samsung Electronics              | 24        | 0.75%   |
| Marvell Technology Group         | 24        | 0.75%   |
| ASIX Electronics                 | 23        | 0.72%   |
| Aquantia                         | 20        | 0.63%   |
| DisplayLink                      | 18        | 0.56%   |
| Xiaomi                           | 15        | 0.47%   |
| Lenovo                           | 14        | 0.44%   |
| Huawei Technologies              | 12        | 0.38%   |
| JMicron Technology               | 7         | 0.22%   |
| Broadcom Limited                 | 7         | 0.22%   |
| Apple                            | 7         | 0.22%   |
| TP-Link                          | 6         | 0.19%   |
| Qualcomm                         | 5         | 0.16%   |
| MediaTek                         | 4         | 0.13%   |
| Google                           | 4         | 0.13%   |
| VIA Technologies                 | 3         | 0.09%   |
| T & A Mobile Phones              | 3         | 0.09%   |
| ZTE WCDMA Technologies MSM       | 2         | 0.06%   |
| Silicon Integrated Systems [SiS] | 2         | 0.06%   |
| Motorola PCS                     | 2         | 0.06%   |
| Mellanox Technologies            | 2         | 0.06%   |
| D-Link System                    | 2         | 0.06%   |
| 3Com                             | 2         | 0.06%   |
| QNAP System                      | 1         | 0.03%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.03%   |
| Motorola BCS                     | 1         | 0.03%   |
| Microsoft                        | 1         | 0.03%   |
| Linksys                          | 1         | 0.03%   |
| ICS Advent                       | 1         | 0.03%   |
| HMD Global                       | 1         | 0.03%   |
| Hewlett-Packard                  | 1         | 0.03%   |
| Elecom                           | 1         | 0.03%   |
| Davicom Semiconductor            | 1         | 0.03%   |
| American Megatrends              | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1394      | 42.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 179       | 5.46%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 125       | 3.81%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 117       | 3.57%   |
| Intel I211 Gigabit Network Connection                             | 109       | 3.32%   |
| Realtek RTL8125 2.5GbE Controller                                 | 108       | 3.29%   |
| Intel Ethernet Connection (2) I219-V                              | 62        | 1.89%   |
| Intel Ethernet Connection I217-LM                                 | 52        | 1.59%   |
| Intel Ethernet Controller I225-V                                  | 46        | 1.4%    |
| Intel Ethernet Connection (7) I219-V                              | 35        | 1.07%   |
| Intel Ethernet Connection (7) I219-LM                             | 35        | 1.07%   |
| Intel Ethernet Connection (4) I219-LM                             | 35        | 1.07%   |
| Intel 82579V Gigabit Network Connection                           | 28        | 0.85%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 25        | 0.76%   |
| Intel Ethernet Connection I218-LM                                 | 23        | 0.7%    |
| Intel Ethernet Connection I219-LM                                 | 22        | 0.67%   |
| Intel Ethernet Connection (2) I218-V                              | 22        | 0.67%   |
| ASIX AX88179 Gigabit Ethernet                                     | 22        | 0.67%   |
| Intel I210 Gigabit Network Connection                             | 21        | 0.64%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 20        | 0.61%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 19        | 0.58%   |
| Intel Ethernet Connection I217-V                                  | 19        | 0.58%   |
| Intel Ethernet Connection (6) I219-V                              | 19        | 0.58%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 18        | 0.55%   |
| Intel 82574L Gigabit Network Connection                           | 18        | 0.55%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 17        | 0.52%   |
| Intel Ethernet Connection (2) I219-LM                             | 17        | 0.52%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 17        | 0.52%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 16        | 0.49%   |
| Intel Ethernet Connection (4) I219-V                              | 16        | 0.49%   |
| Intel Ethernet Connection (3) I218-LM                             | 16        | 0.49%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 15        | 0.46%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 15        | 0.46%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 14        | 0.43%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 13        | 0.4%    |
| Intel Ethernet Connection (13) I219-V                             | 13        | 0.4%    |
| Intel Ethernet Connection (10) I219-V                             | 13        | 0.4%    |
| Intel 82577LM Gigabit Network Connection                          | 13        | 0.4%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 13        | 0.4%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 12        | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2976      | 51.72%  |
| WiFi     | 2740      | 47.62%  |
| Modem    | 35        | 0.61%   |
| Unknown  | 3         | 0.05%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2141      | 57.37%  |
| Ethernet | 1590      | 42.6%   |
| Modem    | 1         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1898      | 53.83%  |
| 1     | 1477      | 41.89%  |
| 3     | 81        | 2.3%    |
| 0     | 53        | 1.5%    |
| 4     | 13        | 0.37%   |
| 6     | 3         | 0.09%   |
| 5     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 2914      | 81.62%  |
| Yes     | 655       | 18.35%  |
| Unknown | 1         | 0.03%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1196      | 50.1%   |
| Realtek Semiconductor           | 240       | 10.05%  |
| Qualcomm Atheros Communications | 189       | 7.92%   |
| Cambridge Silicon Radio         | 170       | 7.12%   |
| Broadcom                        | 117       | 4.9%    |
| IMC Networks                    | 96        | 4.02%   |
| Lite-On Technology              | 76        | 3.18%   |
| Foxconn / Hon Hai               | 67        | 2.81%   |
| Apple                           | 42        | 1.76%   |
| ASUSTek Computer                | 39        | 1.63%   |
| Dell                            | 31        | 1.3%    |
| Realtek                         | 27        | 1.13%   |
| Hewlett-Packard                 | 13        | 0.54%   |
| Ralink                          | 11        | 0.46%   |
| Toshiba                         | 10        | 0.42%   |
| MediaTek                        | 10        | 0.42%   |
| Marvell Semiconductor           | 7         | 0.29%   |
| Foxconn International           | 7         | 0.29%   |
| TP-Link                         | 5         | 0.21%   |
| Ralink Technology               | 5         | 0.21%   |
| Edimax Technology               | 4         | 0.17%   |
| Dynex                           | 4         | 0.17%   |
| Alps Electric                   | 4         | 0.17%   |
| Taiyo Yuden                     | 2         | 0.08%   |
| Smart Modular Technologies      | 2         | 0.08%   |
| Micro Star International        | 2         | 0.08%   |
| Integrated System Solution      | 2         | 0.08%   |
| Belkin Components               | 2         | 0.08%   |
| SINO WEALTH                     | 1         | 0.04%   |
| Kensington                      | 1         | 0.04%   |
| D-Link                          | 1         | 0.04%   |
| Creative Technology             | 1         | 0.04%   |
| Corsair                         | 1         | 0.04%   |
| Conwise Technology              | 1         | 0.04%   |
| AboCom Systems                  | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 392       | 16.4%   |
| Intel AX201 Bluetooth                               | 233       | 9.75%   |
| Intel AX200 Bluetooth                               | 207       | 8.66%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 178       | 7.45%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 170       | 7.11%   |
| Realtek Bluetooth Radio                             | 143       | 5.98%   |
| Qualcomm Atheros  Bluetooth Device                  | 99        | 4.14%   |
| Realtek  Bluetooth 4.2 Adapter                      | 71        | 2.97%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 44        | 1.84%   |
| Intel Wireless-AC 3168 Bluetooth                    | 40        | 1.67%   |
| IMC Networks Bluetooth Radio                        | 32        | 1.34%   |
| Intel Bluetooth Device                              | 31        | 1.3%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 30        | 1.26%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 29        | 1.21%   |
| Lite-On Bluetooth Device                            | 28        | 1.17%   |
| Intel AX210 Bluetooth                               | 28        | 1.17%   |
| Foxconn / Hon Hai Wireless_Device                   | 28        | 1.17%   |
| Realtek Bluetooth Radio                             | 27        | 1.13%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 26        | 1.09%   |
| IMC Networks Wireless_Device                        | 25        | 1.05%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 25        | 1.05%   |
| Foxconn / Hon Hai Bluetooth Device                  | 20        | 0.84%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 20        | 0.84%   |
| Apple Bluetooth Host Controller                     | 20        | 0.84%   |
| IMC Networks Bluetooth Device                       | 19        | 0.79%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 18        | 0.75%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 15        | 0.63%   |
| Broadcom BCM2045B (BDC-2.1)                         | 15        | 0.63%   |
| Lite-On Wireless_Device                             | 14        | 0.59%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 13        | 0.54%   |
| Apple Bluetooth USB Host Controller                 | 13        | 0.54%   |
| Realtek RTL8723B Bluetooth                          | 12        | 0.5%    |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 12        | 0.5%    |
| Ralink RT3290 Bluetooth                             | 11        | 0.46%   |
| Dell BCM20702A0 Bluetooth Module                    | 11        | 0.46%   |
| ASUS ASUS USB-BT500                                 | 11        | 0.46%   |
| MediaTek Wireless_Device                            | 10        | 0.42%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 9         | 0.38%   |
| HP Broadcom 2070 Bluetooth Combo                    | 9         | 0.38%   |
| Broadcom HP Portable SoftSailing                    | 9         | 0.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 2467      | 47.61%  |
| AMD                        | 1151      | 22.21%  |
| Nvidia                     | 940       | 18.14%  |
| C-Media Electronics        | 98        | 1.89%   |
| Logitech                   | 37        | 0.71%   |
| Creative Labs              | 35        | 0.68%   |
| GN Netcom                  | 32        | 0.62%   |
| Realtek Semiconductor      | 27        | 0.52%   |
| JMTek                      | 26        | 0.5%    |
| Texas Instruments          | 22        | 0.42%   |
| ASUSTek Computer           | 20        | 0.39%   |
| Generalplus Technology     | 17        | 0.33%   |
| Corsair                    | 17        | 0.33%   |
| Razer USA                  | 16        | 0.31%   |
| Creative Technology        | 16        | 0.31%   |
| Plantronics                | 14        | 0.27%   |
| SteelSeries ApS            | 12        | 0.23%   |
| Lenovo                     | 12        | 0.23%   |
| Focusrite-Novation         | 11        | 0.21%   |
| Kingston Technology        | 10        | 0.19%   |
| Hewlett-Packard            | 10        | 0.19%   |
| Blue Microphones           | 9         | 0.17%   |
| VIA Technologies           | 8         | 0.15%   |
| Tenx Technology            | 8         | 0.15%   |
| Sony                       | 7         | 0.14%   |
| Dell                       | 6         | 0.12%   |
| SAVITECH                   | 5         | 0.1%    |
| Yamaha                     | 4         | 0.08%   |
| PreSonus Audio Electronics | 4         | 0.08%   |
| GYROCOM C&C                | 4         | 0.08%   |
| BEHRINGER International    | 4         | 0.08%   |
| ZOOM                       | 3         | 0.06%   |
| Trust                      | 3         | 0.06%   |
| TerraTec Electronic        | 3         | 0.06%   |
| TEAC                       | 3         | 0.06%   |
| Sennheiser Communications  | 3         | 0.06%   |
| Samson Technologies        | 3         | 0.06%   |
| Roland                     | 3         | 0.06%   |
| RODE Microphones           | 3         | 0.06%   |
| QinHeng Electronics        | 3         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 386       | 6.24%   |
| Intel Sunrise Point-LP HD Audio                                            | 280       | 4.52%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 223       | 3.6%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 198       | 3.2%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 197       | 3.18%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 195       | 3.15%   |
| AMD Starship/Matisse HD Audio Controller                                   | 180       | 2.91%   |
| Intel Cannon Lake PCH cAVS                                                 | 178       | 2.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 156       | 2.52%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 141       | 2.28%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 134       | 2.17%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 119       | 1.92%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 109       | 1.76%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 107       | 1.73%   |
| Nvidia GP107GL High Definition Audio Controller                            | 103       | 1.66%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 96        | 1.55%   |
| AMD FCH Azalia Controller                                                  | 96        | 1.55%   |
| Intel Haswell-ULT HD Audio Controller                                      | 90        | 1.45%   |
| Intel 8 Series HD Audio Controller                                         | 89        | 1.44%   |
| Intel Comet Lake PCH-LP cAVS                                               | 82        | 1.32%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 77        | 1.24%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 75        | 1.21%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 69        | 1.11%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 67        | 1.08%   |
| Intel 200 Series PCH HD Audio                                              | 66        | 1.07%   |
| Intel Comet Lake PCH cAVS                                                  | 64        | 1.03%   |
| Nvidia TU116 High Definition Audio Controller                              | 63        | 1.02%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 61        | 0.99%   |
| Nvidia TU106 High Definition Audio Controller                              | 58        | 0.94%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 58        | 0.94%   |
| Nvidia GP106 High Definition Audio Controller                              | 56        | 0.9%    |
| Intel Broadwell-U Audio Controller                                         | 55        | 0.89%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 54        | 0.87%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 53        | 0.86%   |
| AMD Kabini HDMI/DP Audio                                                   | 48        | 0.78%   |
| Nvidia GP104 High Definition Audio Controller                              | 47        | 0.76%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 47        | 0.76%   |
| Nvidia GF108 High Definition Audio Controller                              | 46        | 0.74%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 46        | 0.74%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 42        | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 577       | 21.87%  |
| SK hynix            | 431       | 16.34%  |
| Kingston            | 339       | 12.85%  |
| Micron Technology   | 261       | 9.89%   |
| Crucial             | 195       | 7.39%   |
| Unknown             | 176       | 6.67%   |
| Corsair             | 162       | 6.14%   |
| G.Skill             | 124       | 4.7%    |
| A-DATA Technology   | 51        | 1.93%   |
| Ramaxel Technology  | 42        | 1.59%   |
| Unknown (ABCD)      | 31        | 1.18%   |
| Elpida              | 31        | 1.18%   |
| Nanya Technology    | 29        | 1.1%    |
| Team                | 21        | 0.8%    |
| Patriot             | 17        | 0.64%   |
| Transcend           | 14        | 0.53%   |
| Smart               | 14        | 0.53%   |
| Unknown             | 14        | 0.53%   |
| GOODRAM             | 8         | 0.3%    |
| AMD                 | 8         | 0.3%    |
| Silicon Power       | 6         | 0.23%   |
| Wilk                | 5         | 0.19%   |
| Smart Brazil        | 5         | 0.19%   |
| Apacer              | 5         | 0.19%   |
| Teikon              | 4         | 0.15%   |
| Avant               | 4         | 0.15%   |
| ASint Technology    | 4         | 0.15%   |
| SHARETRONIC         | 3         | 0.11%   |
| PNY                 | 3         | 0.11%   |
| Goldkey             | 3         | 0.11%   |
| CSX                 | 3         | 0.11%   |
| V-GeN               | 2         | 0.08%   |
| Unifosa             | 2         | 0.08%   |
| Reboto              | 2         | 0.08%   |
| Kllisre             | 2         | 0.08%   |
| Kingmax             | 2         | 0.08%   |
| Imation             | 2         | 0.08%   |
| Hewlett-Packard     | 2         | 0.08%   |
| GLOWAY              | 2         | 0.08%   |
| GeIL                | 2         | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 27        | 0.95%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 26        | 0.92%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 25        | 0.88%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 23        | 0.81%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 23        | 0.81%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 21        | 0.74%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 20        | 0.71%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 17        | 0.6%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 17        | 0.6%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 16        | 0.57%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 16        | 0.57%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 16        | 0.57%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 15        | 0.53%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 15        | 0.53%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 15        | 0.53%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 14        | 0.49%   |
| Unknown                                                          | 14        | 0.49%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 13        | 0.46%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 13        | 0.46%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 13        | 0.46%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 13        | 0.46%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 13        | 0.46%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 12        | 0.42%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 12        | 0.42%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 11        | 0.39%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 11        | 0.39%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 11        | 0.39%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 11        | 0.39%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 11        | 0.39%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 10        | 0.35%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 10        | 0.35%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 10        | 0.35%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 10        | 0.35%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 10        | 0.35%   |
| SK hynix RAM HMA851S6CJR6N-VK 8GB SODIMM DDR4 2667MT/s           | 9         | 0.32%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 9         | 0.32%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s          | 9         | 0.32%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 0.28%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 0.28%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 8         | 0.28%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1305      | 57.62%  |
| DDR3    | 632       | 27.9%   |
| LPDDR4  | 93        | 4.11%   |
| Unknown | 54        | 2.38%   |
| LPDDR3  | 52        | 2.3%    |
| DDR2    | 48        | 2.12%   |
| SDRAM   | 33        | 1.46%   |
| DDR5    | 28        | 1.24%   |
| LPDDR5  | 11        | 0.49%   |
| DDR     | 8         | 0.35%   |
| DRAM    | 1         | 0.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1308      | 57.57%  |
| DIMM         | 775       | 34.11%  |
| Row Of Chips | 165       | 7.26%   |
| Chip         | 12        | 0.53%   |
| Unknown      | 7         | 0.31%   |
| FB-DIMM      | 3         | 0.13%   |
| RIMM         | 2         | 0.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 1076      | 43.58%  |
| 4096  | 617       | 24.99%  |
| 16384 | 452       | 18.31%  |
| 2048  | 209       | 8.46%   |
| 32768 | 84        | 3.4%    |
| 1024  | 28        | 1.13%   |
| 512   | 1         | 0.04%   |
| 256   | 1         | 0.04%   |
| 128   | 1         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 451       | 18.36%  |
| 1600    | 438       | 17.83%  |
| 3200    | 409       | 16.65%  |
| 2400    | 217       | 8.84%   |
| 1333    | 145       | 5.9%    |
| 2133    | 127       | 5.17%   |
| 3600    | 84        | 3.42%   |
| 1334    | 57        | 2.32%   |
| 4267    | 40        | 1.63%   |
| 1867    | 35        | 1.43%   |
| 800     | 32        | 1.3%    |
| 667     | 28        | 1.14%   |
| 3266    | 26        | 1.06%   |
| 2666    | 24        | 0.98%   |
| 4800    | 22        | 0.9%    |
| 3400    | 22        | 0.9%    |
| 3000    | 22        | 0.9%    |
| Unknown | 20        | 0.81%   |
| 3800    | 18        | 0.73%   |
| 3733    | 17        | 0.69%   |
| 2933    | 15        | 0.61%   |
| 1066    | 15        | 0.61%   |
| 1067    | 14        | 0.57%   |
| 3466    | 13        | 0.53%   |
| 8400    | 12        | 0.49%   |
| 6400    | 12        | 0.49%   |
| 3866    | 12        | 0.49%   |
| 1866    | 11        | 0.45%   |
| 4199    | 9         | 0.37%   |
| 4266    | 8         | 0.33%   |
| 2800    | 8         | 0.33%   |
| 3333    | 7         | 0.29%   |
| 400     | 7         | 0.29%   |
| 3666    | 6         | 0.24%   |
| 3066    | 6         | 0.24%   |
| 3151    | 5         | 0.2%    |
| 2048    | 5         | 0.2%    |
| 2000    | 5         | 0.2%    |
| 1800    | 5         | 0.2%    |
| 3534    | 4         | 0.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 47        | 40.87%  |
| Brother Industries     | 24        | 20.87%  |
| Seiko Epson            | 11        | 9.57%   |
| Samsung Electronics    | 11        | 9.57%   |
| Canon                  | 8         | 6.96%   |
| Xerox                  | 2         | 1.74%   |
| Dymo-CoStar            | 2         | 1.74%   |
| Zebra                  | 1         | 0.87%   |
| QinHeng Electronics    | 1         | 0.87%   |
| Prolific Technology    | 1         | 0.87%   |
| Pantum                 | 1         | 0.87%   |
| Panasonic (Matsushita) | 1         | 0.87%   |
| Kyocera                | 1         | 0.87%   |
| ICS Advent             | 1         | 0.87%   |
| Datamax-O'Neil         | 1         | 0.87%   |
| BESTEASY               | 1         | 0.87%   |
| Apple                  | 1         | 0.87%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| HP OfficeJet Pro 8020 series                           | 3         | 2.56%   |
| Seiko Epson L3110 Series                               | 2         | 1.71%   |
| Samsung M2070 Series                                   | 2         | 1.71%   |
| HP OfficeJet Pro 7740 series                           | 2         | 1.71%   |
| HP LaserJet P2015 series                               | 2         | 1.71%   |
| HP LaserJet 1020                                       | 2         | 1.71%   |
| HP LaserJet 1018                                       | 2         | 1.71%   |
| HP ENVY 4500 series                                    | 2         | 1.71%   |
| HP DeskJet 2700 series                                 | 2         | 1.71%   |
| HP DeskJet 2600 series                                 | 2         | 1.71%   |
| Brother HL-L2320D series                               | 2         | 1.71%   |
| Brother HL-2230 series                                 | 2         | 1.71%   |
| Zebra ZTC LP2844-Z-200dpi                              | 1         | 0.85%   |
| Xerox Phaser 6500DN                                    | 1         | 0.85%   |
| Xerox Phaser 3140 and 3155                             | 1         | 0.85%   |
| Seiko Epson XP-3100 Series                             | 1         | 0.85%   |
| Seiko Epson XP-2100 Series                             | 1         | 0.85%   |
| Seiko Epson WF-2530 Series                             | 1         | 0.85%   |
| Seiko Epson Printer                                    | 1         | 0.85%   |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F | 1         | 0.85%   |
| Seiko Epson L220 Series                                | 1         | 0.85%   |
| Seiko Epson L120 Series                                | 1         | 0.85%   |
| Seiko Epson ET-2710 Series                             | 1         | 0.85%   |
| Seiko Epson ET-2700 Series                             | 1         | 0.85%   |
| Samsung Xerox Phaser 3117 Laser Printer                | 1         | 0.85%   |
| Samsung SCX-3200 Series                                | 1         | 0.85%   |
| Samsung ML-2250 Series                                 | 1         | 0.85%   |
| Samsung ML-216x Series Laser Printer                   | 1         | 0.85%   |
| Samsung M262x/M282x Xpress Series Laser Printer        | 1         | 0.85%   |
| Samsung M2020 Series                                   | 1         | 0.85%   |
| Samsung CLX-3180 Series                                | 1         | 0.85%   |
| Samsung CLX-3170 Series                                | 1         | 0.85%   |
| Samsung CLP-360 Series                                 | 1         | 0.85%   |
| QinHeng CH340S                                         | 1         | 0.85%   |
| Prolific PL2305 Parallel Port                          | 1         | 0.85%   |
| Pantum P2200 series                                    | 1         | 0.85%   |
| Panasonic (Matsushita) KX-MB1500RU                     | 1         | 0.85%   |
| Kyocera Mita FS-820                                    | 1         | 0.85%   |
| ICS Advent Parallel Adapter                            | 1         | 0.85%   |
| HP OfficeJet Pro 9010 series                           | 1         | 0.85%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 13        | 50%     |
| Seiko Epson     | 7         | 26.92%  |
| Mustek Systems  | 3         | 11.54%  |
| Hewlett-Packard | 3         | 11.54%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo]             | 3         | 11.54%  |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 2         | 7.69%   |
| Canon CanoScan N670U/N676U/LiDE 20                      | 2         | 7.69%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                  | 2         | 7.69%   |
| Canon CanoScan LiDE 220                                 | 2         | 7.69%   |
| Canon CanoScan LiDE 210                                 | 2         | 7.69%   |
| Canon CanoScan LiDE 110                                 | 2         | 7.69%   |
| Seiko Epson GT-X770 [Perfection V500]                   | 1         | 3.85%   |
| Seiko Epson ES-D200 [GT-S50]                            | 1         | 3.85%   |
| Mustek Systems SNAPSCAN e22                             | 1         | 3.85%   |
| Mustek Systems ScanExpress A3 USB 1200 PRO              | 1         | 3.85%   |
| Mustek Systems BearPaw 1200 CU Plus                     | 1         | 3.85%   |
| HP ScanJet G4010                                        | 1         | 3.85%   |
| HP ScanJet 82x0C                                        | 1         | 3.85%   |
| HP ScanJet 3770                                         | 1         | 3.85%   |
| Canon CanoScan LiDE 60                                  | 1         | 3.85%   |
| Canon CanoScan LIDE 25                                  | 1         | 3.85%   |
| Canon CanoScan LiDE 120                                 | 1         | 3.85%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 438       | 18.61%  |
| IMC Networks                           | 229       | 9.73%   |
| Microdia                               | 214       | 9.09%   |
| Logitech                               | 182       | 7.73%   |
| Realtek Semiconductor                  | 180       | 7.65%   |
| Acer                                   | 167       | 7.1%    |
| Quanta                                 | 130       | 5.52%   |
| Sunplus Innovation Technology          | 122       | 5.18%   |
| Cheng Uei Precision Industry (Foxlink) | 94        | 3.99%   |
| Suyin                                  | 47        | 2%      |
| Syntek                                 | 45        | 1.91%   |
| Silicon Motion                         | 42        | 1.78%   |
| Apple                                  | 41        | 1.74%   |
| Lite-On Technology                     | 40        | 1.7%    |
| Luxvisions Innotech Limited            | 36        | 1.53%   |
| Microsoft                              | 33        | 1.4%    |
| Bison Electronics                      | 28        | 1.19%   |
| Alcor Micro                            | 28        | 1.19%   |
| Samsung Electronics                    | 26        | 1.1%    |
| Ricoh                                  | 16        | 0.68%   |
| Generalplus Technology                 | 14        | 0.59%   |
| Lenovo                                 | 13        | 0.55%   |
| Z-Star Microelectronics                | 12        | 0.51%   |
| Sonix Technology                       | 10        | 0.42%   |
| KYE Systems (Mouse Systems)            | 8         | 0.34%   |
| Genesys Logic                          | 8         | 0.34%   |
| ARC International                      | 8         | 0.34%   |
| Y Media                                | 7         | 0.3%    |
| Huawei Technologies                    | 7         | 0.3%    |
| SunplusIT                              | 6         | 0.25%   |
| Sunplus Technology                     | 6         | 0.25%   |
| MacroSilicon                           | 6         | 0.25%   |
| Cubeternet                             | 6         | 0.25%   |
| Importek                               | 5         | 0.21%   |
| Creative Technology                    | 5         | 0.21%   |
| USB Camera                             | 4         | 0.17%   |
| Razer USA                              | 4         | 0.17%   |
| Intel                                  | 4         | 0.17%   |
| GEMBIRD                                | 4         | 0.17%   |
| ShineTech                              | 3         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 102       | 4.29%   |
| Microdia Integrated_Webcam_HD                                              | 93        | 3.91%   |
| Realtek Integrated_Webcam_HD                                               | 75        | 3.16%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 69        | 2.9%    |
| IMC Networks Integrated Camera                                             | 69        | 2.9%    |
| Sunplus Integrated_Webcam_HD                                               | 53        | 2.23%   |
| Acer Integrated Camera                                                     | 49        | 2.06%   |
| Chicony HD Webcam                                                          | 45        | 1.89%   |
| Logitech HD Pro Webcam C920                                                | 41        | 1.72%   |
| Logitech Webcam C270                                                       | 37        | 1.56%   |
| Syntek Integrated Camera                                                   | 32        | 1.35%   |
| Chicony USB2.0 Camera                                                      | 30        | 1.26%   |
| Chicony HP HD Camera                                                       | 27        | 1.14%   |
| Samsung Galaxy A5 (MTP)                                                    | 25        | 1.05%   |
| Quanta HD User Facing                                                      | 25        | 1.05%   |
| Acer HD Webcam                                                             | 23        | 0.97%   |
| Chicony HD User Facing                                                     | 22        | 0.93%   |
| Acer Lenovo EasyCamera                                                     | 22        | 0.93%   |
| Microdia Integrated Webcam                                                 | 21        | 0.88%   |
| Quanta HP TrueVision HD Camera                                             | 19        | 0.8%    |
| Microdia Webcam Vitade AF                                                  | 19        | 0.8%    |
| Chicony HP Wide Vision HD Camera                                           | 17        | 0.72%   |
| Quanta HP HD Camera                                                        | 16        | 0.67%   |
| Lite-On Integrated Camera                                                  | 16        | 0.67%   |
| Chicony Integrated Camera (1280x720@30)                                    | 16        | 0.67%   |
| Chicony HP Truevision HD                                                   | 16        | 0.67%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 16        | 0.67%   |
| Microsoft LifeCam HD-3000                                                  | 14        | 0.59%   |
| Microdia USB 2.0 Camera                                                    | 14        | 0.59%   |
| Bison Integrated Camera                                                    | 14        | 0.59%   |
| Realtek Integrated Webcam                                                  | 13        | 0.55%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 13        | 0.55%   |
| IMC Networks HD Camera                                                     | 13        | 0.55%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 13        | 0.55%   |
| Acer BisonCam, NB Pro                                                      | 13        | 0.55%   |
| Realtek USB Camera                                                         | 12        | 0.5%    |
| Quanta HP Wide Vision HD Camera                                            | 12        | 0.5%    |
| Quanta HD Webcam                                                           | 12        | 0.5%    |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera            | 12        | 0.5%    |
| Acer BisonCam,NB Pro                                                       | 12        | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 155       | 31.96%  |
| Validity Sensors                   | 124       | 25.57%  |
| Shenzhen Goodix Technology         | 97        | 20%     |
| Elan Microelectronics              | 38        | 7.84%   |
| Upek                               | 21        | 4.33%   |
| AuthenTec                          | 21        | 4.33%   |
| LighTuning Technology              | 18        | 3.71%   |
| STMicroelectronics                 | 6         | 1.24%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.41%   |
| Focal-systems.Corp                 | 2         | 0.41%   |
| DigitalPersona                     | 1         | 0.21%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 54        | 11.13%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 50        | 10.31%  |
| Shenzhen Goodix Fingerprint Reader                                         | 27        | 5.57%   |
| Elan ELAN:Fingerprint                                                      | 22        | 4.54%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 21        | 4.33%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 20        | 4.12%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 19        | 3.92%   |
| Synaptics UWP WBDI                                                         | 19        | 3.92%   |
| Shenzhen Goodix FingerPrint                                                | 16        | 3.3%    |
| Validity Sensors Synaptics WBDI                                            | 15        | 3.09%   |
| Elan ELAN:ARM-M4                                                           | 14        | 2.89%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 13        | 2.68%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 11        | 2.27%   |
| Synaptics  WBDI                                                            | 11        | 2.27%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 11        | 2.27%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 11        | 2.27%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 11        | 2.27%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 10        | 2.06%   |
| Synaptics WBDI                                                             | 10        | 2.06%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 9         | 1.86%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 9         | 1.86%   |
| Validity Sensors Fingerprint scanner                                       | 7         | 1.44%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 7         | 1.44%   |
| AuthenTec AES2810                                                          | 7         | 1.44%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 6         | 1.24%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 6         | 1.24%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 1.24%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 1.03%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 5         | 1.03%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 1.03%   |
| Unknown                                                                    | 5         | 1.03%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 0.82%   |
| Validity Sensors VFS491                                                    | 4         | 0.82%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 0.82%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 0.82%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 3         | 0.62%   |
| Synaptics WBDI Device                                                      | 2         | 0.41%   |
| Synaptics UWP WBDI Device                                                  | 2         | 0.41%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 2         | 0.41%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 0.41%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 86        | 41.95%  |
| Alcor Micro               | 55        | 26.83%  |
| Upek                      | 13        | 6.34%   |
| O2 Micro                  | 8         | 3.9%    |
| Lenovo                    | 7         | 3.41%   |
| Advanced Card Systems     | 6         | 2.93%   |
| SCM Microsystems          | 4         | 1.95%   |
| Yubico.com                | 3         | 1.46%   |
| OmniKey                   | 3         | 1.46%   |
| Gemalto (was Gemplus)     | 3         | 1.46%   |
| Reiner SCT Kartensysteme  | 2         | 0.98%   |
| Realtek Semiconductor     | 2         | 0.98%   |
| Fujitsu Siemens Computers | 2         | 0.98%   |
| Clay Logic                | 2         | 0.98%   |
| BIT4ID                    | 2         | 0.98%   |
| Watchdata                 | 1         | 0.49%   |
| In Focus Systems          | 1         | 0.49%   |
| Giesecke & Devrient       | 1         | 0.49%   |
| Chicony Electronics       | 1         | 0.49%   |
| Aladdin R.D.              | 1         | 0.49%   |
| Aladdin Knowledge Systems | 1         | 0.49%   |
| Aktiv                     | 1         | 0.49%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 53        | 25.85%  |
| Broadcom 5880                                                                | 24        | 11.71%  |
| Broadcom 58200                                                               | 24        | 11.71%  |
| Broadcom BCM5880 Secure Applications Processor                               | 22        | 10.73%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 14        | 6.83%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 13        | 6.34%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 8         | 3.9%    |
| Lenovo Integrated Smart Card Reader                                          | 7         | 3.41%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 4         | 1.95%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 3         | 1.46%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 3         | 1.46%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 2         | 0.98%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 0.98%   |
| OmniKey CardMan 1021                                                         | 2         | 0.98%   |
| Clay Logic Nitrokey Pro                                                      | 2         | 0.98%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.98%   |
| BIT4ID miniLector EVO                                                        | 2         | 0.98%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 0.98%   |
| Advanced Card Systems ACR39U                                                 | 2         | 0.98%   |
| Watchdata USB Key                                                            | 1         | 0.49%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.49%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.49%   |
| Reiner SCT Kartensysteme tanJack USB                                         | 1         | 0.49%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.49%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.49%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.49%   |
| Giesecke & Devrient StarSign CUT                                             | 1         | 0.49%   |
| Fujitsu Siemens Computers Smartcard Reader D323                              | 1         | 0.49%   |
| Fujitsu Siemens Computers Keyboard KB SCR                                    | 1         | 0.49%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.49%   |
| Aladdin R.D. JaCarta                                                         | 1         | 0.49%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.49%   |
| Aktiv Rutoken lite                                                           | 1         | 0.49%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2451      | 68.35%  |
| 1     | 914       | 25.49%  |
| 2     | 184       | 5.13%   |
| 3     | 17        | 0.47%   |
| 4     | 9         | 0.25%   |
| 6     | 4         | 0.11%   |
| 7     | 3         | 0.08%   |
| 5     | 3         | 0.08%   |
| 9     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 476       | 34.72%  |
| Graphics card            | 239       | 17.43%  |
| Chipcard                 | 176       | 12.84%  |
| Net/wireless             | 158       | 11.52%  |
| Camera                   | 59        | 4.3%    |
| Multimedia controller    | 54        | 3.94%   |
| Sound                    | 39        | 2.84%   |
| Bluetooth                | 37        | 2.7%    |
| Communication controller | 34        | 2.48%   |
| Unassigned class         | 31        | 2.26%   |
| Card reader              | 18        | 1.31%   |
| Storage                  | 15        | 1.09%   |
| Net/ethernet             | 10        | 0.73%   |
| Network                  | 8         | 0.58%   |
| Storage/ide              | 5         | 0.36%   |
| Modem                    | 5         | 0.36%   |
| Firewire controller      | 4         | 0.29%   |
| Dvb card                 | 3         | 0.22%   |

