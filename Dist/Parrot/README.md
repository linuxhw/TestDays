Parrot - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Parrot.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Parrot/Desktop/README.md) and [notebooks](/Dist/Parrot/Notebook/README.md).

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

Total: 955

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | XPS 13 9305                 | Notebook    | [5b06a32fea](https://linux-hardware.org/?probe=5b06a32fea) | Jan 06, 2025 |
| Acer          | Nitro AN515-55              | Notebook    | [87f960a021](https://linux-hardware.org/?probe=87f960a021) | Jan 05, 2025 |
| ASRock        | B550M-HDV                   | Desktop     | [6ce988b582](https://linux-hardware.org/?probe=6ce988b582) | Jan 04, 2025 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [63b427416a](https://linux-hardware.org/?probe=63b427416a) | Jan 02, 2025 |
| Acer          | Aspire A315-510P            | Notebook    | [f3fd803275](https://linux-hardware.org/?probe=f3fd803275) | Jan 01, 2025 |
| Acer          | Aspire A315-510P            | Notebook    | [b079131625](https://linux-hardware.org/?probe=b079131625) | Dec 30, 2024 |
| Acer          | Aspire A315-510P            | Notebook    | [ede893e1e1](https://linux-hardware.org/?probe=ede893e1e1) | Dec 30, 2024 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [f1382538df](https://linux-hardware.org/?probe=f1382538df) | Dec 28, 2024 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [247cc9f886](https://linux-hardware.org/?probe=247cc9f886) | Dec 24, 2024 |
| HP            | ProBook 440 G7              | Notebook    | [205f2940e7](https://linux-hardware.org/?probe=205f2940e7) | Dec 24, 2024 |
| HP            | 0AA8h                       | Desktop     | [5f76cb932b](https://linux-hardware.org/?probe=5f76cb932b) | Dec 23, 2024 |
| HP            | 0AA8h                       | Desktop     | [8a22af001d](https://linux-hardware.org/?probe=8a22af001d) | Dec 23, 2024 |
| ASUSTek       | S400CA                      | Notebook    | [a076c3dca9](https://linux-hardware.org/?probe=a076c3dca9) | Dec 20, 2024 |
| HP            | EliteBook Folio 9480m       | Notebook    | [7d0e5bbe48](https://linux-hardware.org/?probe=7d0e5bbe48) | Dec 14, 2024 |
| HP            | 1587h                       | Desktop     | [0c955e88ce](https://linux-hardware.org/?probe=0c955e88ce) | Dec 13, 2024 |
| HP            | 1587h                       | Desktop     | [85205e402a](https://linux-hardware.org/?probe=85205e402a) | Dec 12, 2024 |
| HP            | Laptop 15-fd0xxx            | Notebook    | [e96ccf6429](https://linux-hardware.org/?probe=e96ccf6429) | Dec 10, 2024 |
| MSI           | Katana GF66 11UE            | Notebook    | [b74e19bf4f](https://linux-hardware.org/?probe=b74e19bf4f) | Dec 10, 2024 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [cb5e7488d1](https://linux-hardware.org/?probe=cb5e7488d1) | Dec 07, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [bd90895fef](https://linux-hardware.org/?probe=bd90895fef) | Dec 07, 2024 |
| ASUSTek       | S400CA                      | Notebook    | [6b626eb981](https://linux-hardware.org/?probe=6b626eb981) | Dec 01, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | Notebook    | [8a363e4242](https://linux-hardware.org/?probe=8a363e4242) | Nov 29, 2024 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [e55906c344](https://linux-hardware.org/?probe=e55906c344) | Nov 28, 2024 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [2ca4532a01](https://linux-hardware.org/?probe=2ca4532a01) | Nov 27, 2024 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [fd5c871a74](https://linux-hardware.org/?probe=fd5c871a74) | Nov 27, 2024 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | Desktop     | [2397b52715](https://linux-hardware.org/?probe=2397b52715) | Nov 27, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [4da22094eb](https://linux-hardware.org/?probe=4da22094eb) | Nov 25, 2024 |
| MSI           | PRO B760-VC WIFI 7 BULK     | Desktop     | [e51990975e](https://linux-hardware.org/?probe=e51990975e) | Nov 25, 2024 |
| Google        | Caroline                    | Notebook    | [3783098457](https://linux-hardware.org/?probe=3783098457) | Nov 23, 2024 |
| Dell          | Latitude 7490               | Notebook    | [47d677a13e](https://linux-hardware.org/?probe=47d677a13e) | Nov 22, 2024 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [d8aeb9e84d](https://linux-hardware.org/?probe=d8aeb9e84d) | Nov 13, 2024 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [aceb94369e](https://linux-hardware.org/?probe=aceb94369e) | Nov 13, 2024 |
| HP            | EliteBook 2560p             | Notebook    | [84d5a17ce2](https://linux-hardware.org/?probe=84d5a17ce2) | Nov 12, 2024 |
| Panasonic     | FZ55-2                      | Notebook    | [72e6f447fd](https://linux-hardware.org/?probe=72e6f447fd) | Nov 09, 2024 |
| MSI           | MPG B550 GAMING CARBON W... | Desktop     | [b31e3a00d3](https://linux-hardware.org/?probe=b31e3a00d3) | Nov 02, 2024 |
| HP            | 250 G7 Notebook PC          | Notebook    | [a3e0d131dc](https://linux-hardware.org/?probe=a3e0d131dc) | Nov 01, 2024 |
| ASUSTek       | H81M-C                      | Desktop     | [f7228f91c2](https://linux-hardware.org/?probe=f7228f91c2) | Nov 01, 2024 |
| Intel         | NUC12WSBi5 M46425-302       | Mini pc     | [ee7b5089e2](https://linux-hardware.org/?probe=ee7b5089e2) | Oct 24, 2024 |
| Unknown       | Unknown                     | Desktop     | [3a8dff97c1](https://linux-hardware.org/?probe=3a8dff97c1) | Oct 23, 2024 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [b1209b5d81](https://linux-hardware.org/?probe=b1209b5d81) | Oct 18, 2024 |
| Lenovo        | ThinkPad X260 20F5A13P00    | Notebook    | [4ac4d50f73](https://linux-hardware.org/?probe=4ac4d50f73) | Oct 17, 2024 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [5a97215ee3](https://linux-hardware.org/?probe=5a97215ee3) | Oct 15, 2024 |
| Dell          | Inspiron 14 7430 2-in-1     | Convertible | [7666cd37c7](https://linux-hardware.org/?probe=7666cd37c7) | Oct 15, 2024 |
| Dell          | Inspiron 14 7430 2-in-1     | Convertible | [4c0992c685](https://linux-hardware.org/?probe=4c0992c685) | Oct 15, 2024 |
| Foxconn       | 2ABF                        | Desktop     | [a154274724](https://linux-hardware.org/?probe=a154274724) | Oct 15, 2024 |
| HP            | Pavilion Laptop 15-cc5xx    | Notebook    | [7cdb58b80e](https://linux-hardware.org/?probe=7cdb58b80e) | Oct 10, 2024 |
| Acer          | Aspire A515-51G             | Notebook    | [020774040e](https://linux-hardware.org/?probe=020774040e) | Oct 10, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [38d2b1b15c](https://linux-hardware.org/?probe=38d2b1b15c) | Oct 05, 2024 |
| Lenovo        | ThinkPad E14 Gen 6 21M70... | Notebook    | [d52e4fc3c0](https://linux-hardware.org/?probe=d52e4fc3c0) | Oct 02, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [cb3a3420ad](https://linux-hardware.org/?probe=cb3a3420ad) | Oct 01, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [a0adceb41d](https://linux-hardware.org/?probe=a0adceb41d) | Sep 26, 2024 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [ba1ef8f0ae](https://linux-hardware.org/?probe=ba1ef8f0ae) | Sep 25, 2024 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [da7400591d](https://linux-hardware.org/?probe=da7400591d) | Sep 25, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [22961f031e](https://linux-hardware.org/?probe=22961f031e) | Sep 24, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [b73138fbf5](https://linux-hardware.org/?probe=b73138fbf5) | Sep 23, 2024 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [ba2f866270](https://linux-hardware.org/?probe=ba2f866270) | Sep 07, 2024 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [08230cbafb](https://linux-hardware.org/?probe=08230cbafb) | Sep 03, 2024 |
| Gigabyte      | B660M AORUS PRO DDR4        | Desktop     | [293134b0b9](https://linux-hardware.org/?probe=293134b0b9) | Sep 03, 2024 |
| Lenovo        | ThinkPad T450s 20BX001EU... | Notebook    | [fd7ece1b23](https://linux-hardware.org/?probe=fd7ece1b23) | Sep 01, 2024 |
| Panasonic     | CF-31-5                     | Notebook    | [3dc2b9bef7](https://linux-hardware.org/?probe=3dc2b9bef7) | Aug 30, 2024 |
| Panasonic     | CF-31-5                     | Notebook    | [15b61b0ba5](https://linux-hardware.org/?probe=15b61b0ba5) | Aug 30, 2024 |
| HP            | ProBook 650 G8 Notebook ... | Notebook    | [faf752e7d5](https://linux-hardware.org/?probe=faf752e7d5) | Aug 27, 2024 |
| HP            | ProBook 650 G8 Notebook ... | Notebook    | [4870c26466](https://linux-hardware.org/?probe=4870c26466) | Aug 27, 2024 |
| HP            | EliteBook 830 G6            | Notebook    | [453f8f7b00](https://linux-hardware.org/?probe=453f8f7b00) | Aug 25, 2024 |
| HP            | EliteBook 830 G6            | Notebook    | [082baba5be](https://linux-hardware.org/?probe=082baba5be) | Aug 25, 2024 |
| Lenovo        | ThinkPad P53 20QNS00X00     | Notebook    | [a10bc8baff](https://linux-hardware.org/?probe=a10bc8baff) | Aug 23, 2024 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [df3aacdfdd](https://linux-hardware.org/?probe=df3aacdfdd) | Aug 22, 2024 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [80db9ffa06](https://linux-hardware.org/?probe=80db9ffa06) | Aug 22, 2024 |
| Dell          | Inspiron 7559               | Notebook    | [1b8c70c653](https://linux-hardware.org/?probe=1b8c70c653) | Aug 18, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [752156b44a](https://linux-hardware.org/?probe=752156b44a) | Aug 16, 2024 |
| Dell          | 0WMJ54 A01                  | Desktop     | [d877099204](https://linux-hardware.org/?probe=d877099204) | Aug 14, 2024 |
| Acer          | Aspire ES1-431              | Notebook    | [7dd0a748d7](https://linux-hardware.org/?probe=7dd0a748d7) | Aug 14, 2024 |
| Gigabyte      | X99-SLI-CF                  | Desktop     | [2b28fed015](https://linux-hardware.org/?probe=2b28fed015) | Aug 06, 2024 |
| Lenovo        | ThinkPad P17 Gen 1 20SQS... | Notebook    | [f01ca35d63](https://linux-hardware.org/?probe=f01ca35d63) | Aug 05, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [22c0d405de](https://linux-hardware.org/?probe=22c0d405de) | Aug 01, 2024 |
| Acer          | Predator PT314-51s          | Notebook    | [8eda2b6d8a](https://linux-hardware.org/?probe=8eda2b6d8a) | Jul 28, 2024 |
| HP            | 250 G7 Notebook PC          | Notebook    | [154385f06a](https://linux-hardware.org/?probe=154385f06a) | Jul 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [224fdf8c28](https://linux-hardware.org/?probe=224fdf8c28) | Jul 23, 2024 |
| HP            | EliteBook 850 G3            | Notebook    | [5a3d8f3ce0](https://linux-hardware.org/?probe=5a3d8f3ce0) | Jul 23, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [34fa837cb3](https://linux-hardware.org/?probe=34fa837cb3) | Jul 18, 2024 |
| Foxconn       | 2AB1 DVT                    | Desktop     | [610048cdd2](https://linux-hardware.org/?probe=610048cdd2) | Jul 16, 2024 |
| Foxconn       | 2AB1 DVT                    | Desktop     | [855e1bd72f](https://linux-hardware.org/?probe=855e1bd72f) | Jul 16, 2024 |
| Lenovo        | IdeaPadFlex 5 15IIL05 81... | Convertible | [5269132576](https://linux-hardware.org/?probe=5269132576) | Jul 15, 2024 |
| Lenovo        | IdeaPadFlex 5 15IIL05 81... | Convertible | [529eaa1393](https://linux-hardware.org/?probe=529eaa1393) | Jul 15, 2024 |
| Dell          | Latitude 5511               | Notebook    | [6094708e32](https://linux-hardware.org/?probe=6094708e32) | Jul 14, 2024 |
| MSI           | Prestige 13 AI Evo A1MG     | Notebook    | [f201feeb20](https://linux-hardware.org/?probe=f201feeb20) | Jul 14, 2024 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [6ad8913d16](https://linux-hardware.org/?probe=6ad8913d16) | Jul 09, 2024 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [4d4543ae64](https://linux-hardware.org/?probe=4d4543ae64) | Jul 09, 2024 |
| HP            | 250 G7 Notebook PC          | Notebook    | [38b439c526](https://linux-hardware.org/?probe=38b439c526) | Jul 06, 2024 |
| Lenovo        | E50-80 80J2                 | Notebook    | [6ef0c878e3](https://linux-hardware.org/?probe=6ef0c878e3) | Jul 06, 2024 |
| Lenovo        | ThinkPad P53 20QNS00X00     | Notebook    | [290e8e87d1](https://linux-hardware.org/?probe=290e8e87d1) | Jun 28, 2024 |
| HC Technol... | HCAR5000-MI                 | Desktop     | [ee1ab4ebe8](https://linux-hardware.org/?probe=ee1ab4ebe8) | Jun 27, 2024 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [7da90462ec](https://linux-hardware.org/?probe=7da90462ec) | Jun 22, 2024 |
| Razer         | Blade 15 (2022) - RZ09-0... | Notebook    | [c22d1433bf](https://linux-hardware.org/?probe=c22d1433bf) | Jun 15, 2024 |
| Orange Pi     | 5                           | Soc         | [b7c66c1d54](https://linux-hardware.org/?probe=b7c66c1d54) | Jun 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [e570948d49](https://linux-hardware.org/?probe=e570948d49) | Jun 10, 2024 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [d5de03918b](https://linux-hardware.org/?probe=d5de03918b) | Jun 05, 2024 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [f41596eb9b](https://linux-hardware.org/?probe=f41596eb9b) | Jun 03, 2024 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [88ea74eb50](https://linux-hardware.org/?probe=88ea74eb50) | Jun 03, 2024 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [93ed456d67](https://linux-hardware.org/?probe=93ed456d67) | Jun 02, 2024 |
| HP            | 18E7                        | Desktop     | [42046a0b95](https://linux-hardware.org/?probe=42046a0b95) | May 27, 2024 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | Notebook    | [3779586782](https://linux-hardware.org/?probe=3779586782) | May 25, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [7642e68170](https://linux-hardware.org/?probe=7642e68170) | May 16, 2024 |
| Lenovo        | ThinkPad T410 2537VXX       | Notebook    | [a5aa605397](https://linux-hardware.org/?probe=a5aa605397) | May 10, 2024 |
| Toshiba       | Satellite E55-A             | Notebook    | [b77667e33a](https://linux-hardware.org/?probe=b77667e33a) | May 08, 2024 |
| HP            | 2000                        | Notebook    | [71d3942f81](https://linux-hardware.org/?probe=71d3942f81) | May 06, 2024 |
| Acer          | Aspire E1-522               | Notebook    | [b1c41ef5a0](https://linux-hardware.org/?probe=b1c41ef5a0) | May 04, 2024 |
| Dell          | Latitude E6430              | Notebook    | [3ea51c9416](https://linux-hardware.org/?probe=3ea51c9416) | May 04, 2024 |
| Dell          | Latitude E6430              | Notebook    | [0e3b2e7c55](https://linux-hardware.org/?probe=0e3b2e7c55) | May 04, 2024 |
| Toshiba       | Satellite E55-A             | Notebook    | [66fc7bf95a](https://linux-hardware.org/?probe=66fc7bf95a) | Apr 30, 2024 |
| Acidanther... | MacBookAir9,1               | Notebook    | [ba60edeb99](https://linux-hardware.org/?probe=ba60edeb99) | Apr 25, 2024 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [8cb1d1d18b](https://linux-hardware.org/?probe=8cb1d1d18b) | Apr 24, 2024 |
| Lenovo        | ThinkPad X1 Tablet Gen 3... | Tablet      | [ae663e3731](https://linux-hardware.org/?probe=ae663e3731) | Apr 24, 2024 |
| MSI           | GL75 9SEK                   | Notebook    | [3d679e4ec2](https://linux-hardware.org/?probe=3d679e4ec2) | Apr 17, 2024 |
| MSI           | GL75 9SEK                   | Notebook    | [b2d528d9b4](https://linux-hardware.org/?probe=b2d528d9b4) | Apr 16, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402XV... | Notebook    | [6291093e82](https://linux-hardware.org/?probe=6291093e82) | Apr 16, 2024 |
| Lenovo        | E41-25 81FS                 | Notebook    | [ee47604b55](https://linux-hardware.org/?probe=ee47604b55) | Apr 13, 2024 |
| HP            | Laptop 14-cf2xxx            | Notebook    | [bc17e5113b](https://linux-hardware.org/?probe=bc17e5113b) | Apr 13, 2024 |
| HP            | Laptop 14-cf2xxx            | Notebook    | [bef6cb8975](https://linux-hardware.org/?probe=bef6cb8975) | Apr 13, 2024 |
| ASUSTek       | H110M-R                     | Desktop     | [473b7a412c](https://linux-hardware.org/?probe=473b7a412c) | Apr 10, 2024 |
| Lenovo        | Z50-70 20354                | Notebook    | [4469cb6e76](https://linux-hardware.org/?probe=4469cb6e76) | Apr 10, 2024 |
| ASUSTek       | H110M-R                     | Desktop     | [d8c6b0c73f](https://linux-hardware.org/?probe=d8c6b0c73f) | Apr 10, 2024 |
| ASUSTek       | ROG Strix G513QR_G513QR     | Notebook    | [2c23a28e81](https://linux-hardware.org/?probe=2c23a28e81) | Apr 08, 2024 |
| Biostar       | H410MH                      | Desktop     | [b8034503cb](https://linux-hardware.org/?probe=b8034503cb) | Apr 04, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [c737a816f3](https://linux-hardware.org/?probe=c737a816f3) | Apr 04, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402XV... | Notebook    | [d0eac00952](https://linux-hardware.org/?probe=d0eac00952) | Apr 02, 2024 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [c498cd96d4](https://linux-hardware.org/?probe=c498cd96d4) | Mar 31, 2024 |
| Razer         | Blade 15 - RZ09-0485        | Notebook    | [24980909b2](https://linux-hardware.org/?probe=24980909b2) | Mar 26, 2024 |
| ASUSTek       | PRIME X570-P                | Desktop     | [8928a51f78](https://linux-hardware.org/?probe=8928a51f78) | Mar 22, 2024 |
| HP            | EliteBook 830 G6            | Notebook    | [955e65cc0f](https://linux-hardware.org/?probe=955e65cc0f) | Mar 22, 2024 |
| HP            | EliteBook 830 G6            | Notebook    | [c5ada253ab](https://linux-hardware.org/?probe=c5ada253ab) | Mar 22, 2024 |
| HP            | EliteBook 830 G6            | Notebook    | [2ab6329c32](https://linux-hardware.org/?probe=2ab6329c32) | Mar 22, 2024 |
| Acer          | Extensa 5230                | Notebook    | [790672cb92](https://linux-hardware.org/?probe=790672cb92) | Mar 22, 2024 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [700d8c6016](https://linux-hardware.org/?probe=700d8c6016) | Mar 18, 2024 |
| Lenovo        | ThinkPad T480 20L6S69X08    | Notebook    | [63c84de71e](https://linux-hardware.org/?probe=63c84de71e) | Mar 15, 2024 |
| Gigabyte      | H81M-DS2                    | Desktop     | [db79be4310](https://linux-hardware.org/?probe=db79be4310) | Mar 09, 2024 |
| Dell          | Latitude 5420 Rugged        | Notebook    | [f9c7c915c9](https://linux-hardware.org/?probe=f9c7c915c9) | Mar 08, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [58e64cec89](https://linux-hardware.org/?probe=58e64cec89) | Mar 06, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [74faba00a3](https://linux-hardware.org/?probe=74faba00a3) | Mar 05, 2024 |
| Lenovo        | ThinkPad T480 20L6S69X08    | Notebook    | [16326b521f](https://linux-hardware.org/?probe=16326b521f) | Mar 01, 2024 |
| MSI           | Z97 GAMING 7                | Desktop     | [be7cf8b3fc](https://linux-hardware.org/?probe=be7cf8b3fc) | Mar 01, 2024 |
| Dell          | XPS 13 9370                 | Notebook    | [086a1782c7](https://linux-hardware.org/?probe=086a1782c7) | Feb 22, 2024 |
| Lenovo        | IdeaPad S145-14API 81UV     | Notebook    | [da65aaff1d](https://linux-hardware.org/?probe=da65aaff1d) | Feb 20, 2024 |
| Samsung       | 750XDA                      | Notebook    | [0aed547d08](https://linux-hardware.org/?probe=0aed547d08) | Feb 18, 2024 |
| HP            | Pavilion dv4                | Notebook    | [20e9de9ad8](https://linux-hardware.org/?probe=20e9de9ad8) | Feb 08, 2024 |
| ASUSTek       | UX430UAR                    | Notebook    | [cc89a20253](https://linux-hardware.org/?probe=cc89a20253) | Feb 04, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [fcabd4a1f4](https://linux-hardware.org/?probe=fcabd4a1f4) | Feb 01, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [b31d7d9323](https://linux-hardware.org/?probe=b31d7d9323) | Feb 01, 2024 |
| Lenovo        | ThinkPad T480s 20L70028U... | Notebook    | [7acd38748f](https://linux-hardware.org/?probe=7acd38748f) | Jan 30, 2024 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [0a1087fdad](https://linux-hardware.org/?probe=0a1087fdad) | Jan 29, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [b7fff52e41](https://linux-hardware.org/?probe=b7fff52e41) | Jan 29, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [7c4514376b](https://linux-hardware.org/?probe=7c4514376b) | Jan 27, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [f1117537a5](https://linux-hardware.org/?probe=f1117537a5) | Jan 27, 2024 |
| Acer          | Aspire A715-51G             | Notebook    | [fad23c2b03](https://linux-hardware.org/?probe=fad23c2b03) | Jan 27, 2024 |
| Dell          | XPS 13 9350                 | Notebook    | [fb1c7c4cab](https://linux-hardware.org/?probe=fb1c7c4cab) | Jan 26, 2024 |
| Lenovo        | ThinkPad T460s 20FAS2JW0... | Notebook    | [59d637113b](https://linux-hardware.org/?probe=59d637113b) | Jan 26, 2024 |
| Acer          | Aspire E1-522               | Notebook    | [a43c97b66c](https://linux-hardware.org/?probe=a43c97b66c) | Jan 26, 2024 |
| HP            | ProBook 455 G4              | Notebook    | [6490d02d72](https://linux-hardware.org/?probe=6490d02d72) | Jan 22, 2024 |
| ASRock        | Z77M                        | Desktop     | [f3bd1cdf2c](https://linux-hardware.org/?probe=f3bd1cdf2c) | Jan 19, 2024 |
| Lenovo        | IdeaPad 1 15IAU7 82QD       | Notebook    | [bb5610a4f5](https://linux-hardware.org/?probe=bb5610a4f5) | Jan 17, 2024 |
| Acer          | Aspire E1-522               | Notebook    | [538c5ee96f](https://linux-hardware.org/?probe=538c5ee96f) | Jan 16, 2024 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [ca8734dc63](https://linux-hardware.org/?probe=ca8734dc63) | Jan 11, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [feaf3edd58](https://linux-hardware.org/?probe=feaf3edd58) | Jan 10, 2024 |
| Acer          | Aspire A715-51G             | Notebook    | [2a3ea77b7a](https://linux-hardware.org/?probe=2a3ea77b7a) | Jan 10, 2024 |
| Lenovo        | ThinkPad T490 20N20023US    | Notebook    | [ce82358c06](https://linux-hardware.org/?probe=ce82358c06) | Jan 04, 2024 |
| Lenovo        | ThinkPad T490 20N20023US    | Notebook    | [ffe96991b4](https://linux-hardware.org/?probe=ffe96991b4) | Jan 04, 2024 |
| HP            | ProBook 450 G5              | Notebook    | [b80a7c9287](https://linux-hardware.org/?probe=b80a7c9287) | Jan 02, 2024 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [1f44330bcf](https://linux-hardware.org/?probe=1f44330bcf) | Dec 31, 2023 |
| Lenovo        | ThinkPad T490 20N3S4PX02    | Notebook    | [0afd47e9fc](https://linux-hardware.org/?probe=0afd47e9fc) | Dec 31, 2023 |
| Google        | Blorb                       | Notebook    | [4e0c068a82](https://linux-hardware.org/?probe=4e0c068a82) | Dec 30, 2023 |
| MSI           | B550 GAMING GEN3            | Desktop     | [02163b04b7](https://linux-hardware.org/?probe=02163b04b7) | Dec 30, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [404320e4d7](https://linux-hardware.org/?probe=404320e4d7) | Dec 28, 2023 |
| HP            | Pavilion g6                 | Notebook    | [62a002d063](https://linux-hardware.org/?probe=62a002d063) | Dec 26, 2023 |
| Apple         | MacBookAir5,1               | Notebook    | [5c7029f981](https://linux-hardware.org/?probe=5c7029f981) | Dec 23, 2023 |
| Lenovo        | IdeaPad 1 11ADA05 82GV      | Notebook    | [980280224f](https://linux-hardware.org/?probe=980280224f) | Dec 18, 2023 |
| Lenovo        | IdeaPad 1 11ADA05 82GV      | Notebook    | [41f03f0699](https://linux-hardware.org/?probe=41f03f0699) | Dec 18, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [72facc22f6](https://linux-hardware.org/?probe=72facc22f6) | Dec 14, 2023 |
| Toshiba       | PORTEGE R930                | Notebook    | [e341599417](https://linux-hardware.org/?probe=e341599417) | Dec 14, 2023 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [d90c13f9c6](https://linux-hardware.org/?probe=d90c13f9c6) | Dec 12, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [baf21dcbce](https://linux-hardware.org/?probe=baf21dcbce) | Dec 06, 2023 |
| ASUSTek       | X540SAA                     | Notebook    | [86295630b8](https://linux-hardware.org/?probe=86295630b8) | Dec 06, 2023 |
| Alienware     | 17 R5                       | Notebook    | [e0fdc679e3](https://linux-hardware.org/?probe=e0fdc679e3) | Dec 04, 2023 |
| Alienware     | 17 R5                       | Notebook    | [1e44992982](https://linux-hardware.org/?probe=1e44992982) | Dec 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [30c19ab13f](https://linux-hardware.org/?probe=30c19ab13f) | Dec 04, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [d416d62cf1](https://linux-hardware.org/?probe=d416d62cf1) | Nov 29, 2023 |
| Acer          | Nitro AN517-55              | Notebook    | [91df918363](https://linux-hardware.org/?probe=91df918363) | Nov 28, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | Notebook    | [a54c387b5f](https://linux-hardware.org/?probe=a54c387b5f) | Nov 27, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [e22c72e9d4](https://linux-hardware.org/?probe=e22c72e9d4) | Nov 26, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [3242361790](https://linux-hardware.org/?probe=3242361790) | Nov 25, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [dfa296fd96](https://linux-hardware.org/?probe=dfa296fd96) | Nov 25, 2023 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [8ad2369936](https://linux-hardware.org/?probe=8ad2369936) | Nov 21, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [a8e951e3b6](https://linux-hardware.org/?probe=a8e951e3b6) | Nov 20, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21B30... | Notebook    | [5685f17122](https://linux-hardware.org/?probe=5685f17122) | Nov 19, 2023 |
| Acer          | TravelMate 5760             | Notebook    | [f90be838c9](https://linux-hardware.org/?probe=f90be838c9) | Nov 18, 2023 |
| Acer          | TravelMate 5760             | Notebook    | [db234d226d](https://linux-hardware.org/?probe=db234d226d) | Nov 18, 2023 |
| Dell          | Latitude E6530              | Notebook    | [f43bd72db4](https://linux-hardware.org/?probe=f43bd72db4) | Nov 16, 2023 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | Notebook    | [20394838bd](https://linux-hardware.org/?probe=20394838bd) | Nov 11, 2023 |
| Gateway       | TBGM01                      | Desktop     | [3ca4695541](https://linux-hardware.org/?probe=3ca4695541) | Nov 07, 2023 |
| Toshiba       | Satellite L50-A-1DL         | Notebook    | [e7b5bfa0b4](https://linux-hardware.org/?probe=e7b5bfa0b4) | Nov 06, 2023 |
| Unknown       | Unknown                     | Notebook    | [2c2d291f54](https://linux-hardware.org/?probe=2c2d291f54) | Nov 05, 2023 |
| Dell          | 0V8WGR A00                  | Desktop     | [9b13411bc8](https://linux-hardware.org/?probe=9b13411bc8) | Nov 05, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [4ce8997d5a](https://linux-hardware.org/?probe=4ce8997d5a) | Nov 05, 2023 |
| MSI           | Prestige 14Evo A12M         | Notebook    | [98e32e98bf](https://linux-hardware.org/?probe=98e32e98bf) | Oct 31, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [be57c0ce22](https://linux-hardware.org/?probe=be57c0ce22) | Oct 29, 2023 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [3c959b9af8](https://linux-hardware.org/?probe=3c959b9af8) | Oct 25, 2023 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [e3540cf969](https://linux-hardware.org/?probe=e3540cf969) | Oct 23, 2023 |
| Google        | Reef                        | Notebook    | [819e00dd76](https://linux-hardware.org/?probe=819e00dd76) | Oct 22, 2023 |
| Acer          | Extensa 215-54              | Notebook    | [4e2a3f7606](https://linux-hardware.org/?probe=4e2a3f7606) | Oct 15, 2023 |
| Acer          | Extensa 215-54              | Notebook    | [94d47a3e29](https://linux-hardware.org/?probe=94d47a3e29) | Oct 15, 2023 |
| HP            | ENVY m6 Notebook            | Notebook    | [fb0b3ea9e7](https://linux-hardware.org/?probe=fb0b3ea9e7) | Oct 12, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [0755ce07a3](https://linux-hardware.org/?probe=0755ce07a3) | Oct 08, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [35081bd0e8](https://linux-hardware.org/?probe=35081bd0e8) | Oct 08, 2023 |
| Lenovo        | Legion 5 15IAH7H 82RB       | Notebook    | [30b0879baa](https://linux-hardware.org/?probe=30b0879baa) | Oct 07, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [ee251b10d4](https://linux-hardware.org/?probe=ee251b10d4) | Oct 07, 2023 |
| Samsung       | 550XBE/350XBE               | Notebook    | [442ef4b7be](https://linux-hardware.org/?probe=442ef4b7be) | Oct 04, 2023 |
| Samsung       | 550XBE/350XBE               | Notebook    | [3185dde146](https://linux-hardware.org/?probe=3185dde146) | Oct 04, 2023 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [a13621c5d3](https://linux-hardware.org/?probe=a13621c5d3) | Oct 04, 2023 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [144cbc70d0](https://linux-hardware.org/?probe=144cbc70d0) | Oct 03, 2023 |
| HP            | ENVY m6 Notebook            | Notebook    | [5ef983c393](https://linux-hardware.org/?probe=5ef983c393) | Oct 01, 2023 |
| HP            | 8619                        | Desktop     | [d631850d2f](https://linux-hardware.org/?probe=d631850d2f) | Sep 28, 2023 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [34e34036d7](https://linux-hardware.org/?probe=34e34036d7) | Sep 27, 2023 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [167d2e893e](https://linux-hardware.org/?probe=167d2e893e) | Sep 27, 2023 |
| HP            | 8714                        | Desktop     | [235d6bd11b](https://linux-hardware.org/?probe=235d6bd11b) | Sep 24, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | Notebook    | [37ecdee3d3](https://linux-hardware.org/?probe=37ecdee3d3) | Sep 24, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | Notebook    | [ecc0e92fb0](https://linux-hardware.org/?probe=ecc0e92fb0) | Sep 24, 2023 |
| ASUSTek       | Maximus V FORMULA           | Desktop     | [e10f21c5c5](https://linux-hardware.org/?probe=e10f21c5c5) | Sep 22, 2023 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [648ac87a81](https://linux-hardware.org/?probe=648ac87a81) | Sep 21, 2023 |
| Shenzhen M... | F7BAA                       | Desktop     | [10d32d6284](https://linux-hardware.org/?probe=10d32d6284) | Sep 17, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [faf0bfe427](https://linux-hardware.org/?probe=faf0bfe427) | Sep 17, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [faa9a71ce1](https://linux-hardware.org/?probe=faa9a71ce1) | Sep 17, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [2f99528572](https://linux-hardware.org/?probe=2f99528572) | Sep 16, 2023 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [6495df6735](https://linux-hardware.org/?probe=6495df6735) | Sep 15, 2023 |
| Acer          | Aspire C20-820              | All in one  | [1b2bdeafca](https://linux-hardware.org/?probe=1b2bdeafca) | Sep 11, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [e59c5b4fda](https://linux-hardware.org/?probe=e59c5b4fda) | Sep 10, 2023 |
| ASUSTek       | S550CB                      | Notebook    | [dbf2770e09](https://linux-hardware.org/?probe=dbf2770e09) | Sep 10, 2023 |
| Toshiba       | Satellite L775D             | Notebook    | [681dab0969](https://linux-hardware.org/?probe=681dab0969) | Sep 09, 2023 |
| ASUSTek       | Maximus V FORMULA           | Desktop     | [694ffed41f](https://linux-hardware.org/?probe=694ffed41f) | Sep 06, 2023 |
| ASUSTek       | Maximus V FORMULA           | Desktop     | [039aa353eb](https://linux-hardware.org/?probe=039aa353eb) | Sep 06, 2023 |
| Dell          | Latitude 7280               | Notebook    | [3cf6ec76b5](https://linux-hardware.org/?probe=3cf6ec76b5) | Sep 05, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [ec33c11aa1](https://linux-hardware.org/?probe=ec33c11aa1) | Aug 31, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [101a39c37a](https://linux-hardware.org/?probe=101a39c37a) | Aug 28, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [da3ab01b3a](https://linux-hardware.org/?probe=da3ab01b3a) | Aug 25, 2023 |
| IP3 Tech      | PCBA-IP3_ACB20015           | Mini pc     | [57f24399d5](https://linux-hardware.org/?probe=57f24399d5) | Aug 22, 2023 |
| IP3 Tech      | PCBA-IP3_ACB20015           | Mini pc     | [a7c7baada2](https://linux-hardware.org/?probe=a7c7baada2) | Aug 22, 2023 |
| IP3 Tech      | PCBA-IP3_ACB20015           | Mini pc     | [8b42955659](https://linux-hardware.org/?probe=8b42955659) | Aug 21, 2023 |
| MSI           | Katana 15 B13VGK            | Notebook    | [e92e058288](https://linux-hardware.org/?probe=e92e058288) | Aug 20, 2023 |
| Pegatron      | 2A94h                       | Desktop     | [e9816ab65b](https://linux-hardware.org/?probe=e9816ab65b) | Aug 19, 2023 |
| MSI           | 3666h                       | Desktop     | [d3f51a2bf0](https://linux-hardware.org/?probe=d3f51a2bf0) | Aug 15, 2023 |
| Dell          | 0100P6 A01                  | Desktop     | [2cf993001c](https://linux-hardware.org/?probe=2cf993001c) | Aug 13, 2023 |
| Lenovo        | IdeaPad Slim 1-11AST-05 ... | Notebook    | [30c7051967](https://linux-hardware.org/?probe=30c7051967) | Aug 11, 2023 |
| MSI           | Summit E14Evo A12M          | Notebook    | [b83d821361](https://linux-hardware.org/?probe=b83d821361) | Aug 11, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3e66a1f712](https://linux-hardware.org/?probe=3e66a1f712) | Aug 10, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [b76b1bf00a](https://linux-hardware.org/?probe=b76b1bf00a) | Aug 08, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [63665fca24](https://linux-hardware.org/?probe=63665fca24) | Aug 08, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | Notebook    | [324819c88d](https://linux-hardware.org/?probe=324819c88d) | Aug 08, 2023 |
| Acer          | Aspire 4810T                | Notebook    | [aaf9cdefc0](https://linux-hardware.org/?probe=aaf9cdefc0) | Aug 07, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [d3999a626a](https://linux-hardware.org/?probe=d3999a626a) | Aug 07, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [1b3c788790](https://linux-hardware.org/?probe=1b3c788790) | Aug 06, 2023 |
| Dell          | Precision 7730              | Notebook    | [1ed1a60e50](https://linux-hardware.org/?probe=1ed1a60e50) | Aug 06, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [48ec623298](https://linux-hardware.org/?probe=48ec623298) | Aug 06, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | Desktop     | [7979e7ce95](https://linux-hardware.org/?probe=7979e7ce95) | Aug 05, 2023 |
| Microsoft     | Surface Laptop 4            | Tablet      | [70c6936cfc](https://linux-hardware.org/?probe=70c6936cfc) | Aug 04, 2023 |
| Dell          | 0RY007                      | Desktop     | [8317045335](https://linux-hardware.org/?probe=8317045335) | Aug 01, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [ad4e7cf4ad](https://linux-hardware.org/?probe=ad4e7cf4ad) | Aug 01, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [36d9df3244](https://linux-hardware.org/?probe=36d9df3244) | Jul 31, 2023 |
| MSI           | Katana 17 B13VFK            | Notebook    | [8bc597da6e](https://linux-hardware.org/?probe=8bc597da6e) | Jul 29, 2023 |
| MSI           | Katana GF66 11UE            | Notebook    | [78e12df29a](https://linux-hardware.org/?probe=78e12df29a) | Jul 28, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [cea811cc5f](https://linux-hardware.org/?probe=cea811cc5f) | Jul 25, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [d047b35269](https://linux-hardware.org/?probe=d047b35269) | Jul 25, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [affdd0a6f9](https://linux-hardware.org/?probe=affdd0a6f9) | Jul 25, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | Notebook    | [af539103c5](https://linux-hardware.org/?probe=af539103c5) | Jul 21, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [58882ecdfe](https://linux-hardware.org/?probe=58882ecdfe) | Jul 20, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [8abec746f7](https://linux-hardware.org/?probe=8abec746f7) | Jul 19, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [3e6412c30b](https://linux-hardware.org/?probe=3e6412c30b) | Jul 19, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [8e533f69a9](https://linux-hardware.org/?probe=8e533f69a9) | Jul 19, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [c4b019ee7f](https://linux-hardware.org/?probe=c4b019ee7f) | Jul 18, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [d7c21e7889](https://linux-hardware.org/?probe=d7c21e7889) | Jul 13, 2023 |
| Acer          | Aspire A515-47              | Notebook    | [10d3da2824](https://linux-hardware.org/?probe=10d3da2824) | Jul 12, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [37bc760339](https://linux-hardware.org/?probe=37bc760339) | Jul 11, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [b5a021ae8a](https://linux-hardware.org/?probe=b5a021ae8a) | Jul 10, 2023 |
| Samsung       | 750XED                      | Notebook    | [412a36c3f1](https://linux-hardware.org/?probe=412a36c3f1) | Jul 08, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [70a6354074](https://linux-hardware.org/?probe=70a6354074) | Jul 05, 2023 |
| Dell          | Latitude 3410               | Notebook    | [da609df435](https://linux-hardware.org/?probe=da609df435) | Jul 03, 2023 |
| HP            | EliteBook 860 16 inch G9... | Notebook    | [4a4b49a909](https://linux-hardware.org/?probe=4a4b49a909) | Jul 03, 2023 |
| MSI           | PRO Z790-P WIFI             | Desktop     | [b4d959d91f](https://linux-hardware.org/?probe=b4d959d91f) | Jul 02, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [12871de62d](https://linux-hardware.org/?probe=12871de62d) | Jun 30, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [ea4a5ccb1a](https://linux-hardware.org/?probe=ea4a5ccb1a) | Jun 29, 2023 |
| Lenovo        | ThinkPad P53 20QNS00X00     | Notebook    | [a4b38b88cc](https://linux-hardware.org/?probe=a4b38b88cc) | Jun 27, 2023 |
| Lenovo        | ThinkPad P53 20QNS00X00     | Notebook    | [e28a0d43ed](https://linux-hardware.org/?probe=e28a0d43ed) | Jun 27, 2023 |
| HP            | ENVY m6 Notebook            | Notebook    | [ee31bf4efe](https://linux-hardware.org/?probe=ee31bf4efe) | Jun 26, 2023 |
| Unknown       | Unknown                     | Notebook    | [9c8513ff31](https://linux-hardware.org/?probe=9c8513ff31) | Jun 25, 2023 |
| HONOR         | BMH-WCX9                    | Notebook    | [f40cb826de](https://linux-hardware.org/?probe=f40cb826de) | Jun 25, 2023 |
| Samsung       | 530XBB                      | Notebook    | [51007aebd3](https://linux-hardware.org/?probe=51007aebd3) | Jun 24, 2023 |
| ASUSTek       | Maximus V FORMULA           | Desktop     | [190d408bc2](https://linux-hardware.org/?probe=190d408bc2) | Jun 23, 2023 |
| ASUSTek       | Maximus V FORMULA           | Desktop     | [fa49028492](https://linux-hardware.org/?probe=fa49028492) | Jun 23, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [3055046330](https://linux-hardware.org/?probe=3055046330) | Jun 20, 2023 |
| Lenovo        | ThinkPad L490 20Q5001YMX    | Notebook    | [c04ebf8de3](https://linux-hardware.org/?probe=c04ebf8de3) | Jun 20, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [2102fc8523](https://linux-hardware.org/?probe=2102fc8523) | Jun 19, 2023 |
| HP            | ENVY m6 Notebook            | Notebook    | [464db6c1df](https://linux-hardware.org/?probe=464db6c1df) | Jun 18, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [11161fa30c](https://linux-hardware.org/?probe=11161fa30c) | Jun 18, 2023 |
| Lenovo        | ThinkPad L520 78595GJ       | Notebook    | [52faa96ad0](https://linux-hardware.org/?probe=52faa96ad0) | Jun 17, 2023 |
| Dell          | Latitude 7430               | Notebook    | [e25ec87b40](https://linux-hardware.org/?probe=e25ec87b40) | Jun 17, 2023 |
| Dell          | Latitude 7430               | Notebook    | [35c6e2b80e](https://linux-hardware.org/?probe=35c6e2b80e) | Jun 17, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [20a66afa75](https://linux-hardware.org/?probe=20a66afa75) | Jun 14, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [3d8862fe69](https://linux-hardware.org/?probe=3d8862fe69) | Jun 13, 2023 |
| HP            | ENVY m6 Notebook            | Notebook    | [dbf4a1d57c](https://linux-hardware.org/?probe=dbf4a1d57c) | Jun 12, 2023 |
| HP            | 339A                        | Desktop     | [d1fa07d03f](https://linux-hardware.org/?probe=d1fa07d03f) | Jun 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [3de2e4c6f9](https://linux-hardware.org/?probe=3de2e4c6f9) | Jun 10, 2023 |
| Onda TLC      | ONDA Oliver                 | Notebook    | [80a06d821b](https://linux-hardware.org/?probe=80a06d821b) | Jun 09, 2023 |
| HP            | ENVY m6 Notebook            | Notebook    | [f72410be27](https://linux-hardware.org/?probe=f72410be27) | Jun 08, 2023 |
| HP            | 339A                        | Desktop     | [f2147ed11b](https://linux-hardware.org/?probe=f2147ed11b) | Jun 05, 2023 |
| HP            | 1495                        | Desktop     | [32cfd162b8](https://linux-hardware.org/?probe=32cfd162b8) | Jun 05, 2023 |
| HP            | 1495                        | Desktop     | [f6c9f689ec](https://linux-hardware.org/?probe=f6c9f689ec) | Jun 05, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [f0e52437a7](https://linux-hardware.org/?probe=f0e52437a7) | Jun 04, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [c359b173f6](https://linux-hardware.org/?probe=c359b173f6) | Jun 04, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [a0efed7ee2](https://linux-hardware.org/?probe=a0efed7ee2) | Jun 04, 2023 |
| ASUSTek       | P8Z68-V                     | Desktop     | [59e64db8de](https://linux-hardware.org/?probe=59e64db8de) | Jun 02, 2023 |
| Acer          | Nitro AN515-42              | Notebook    | [0acaadb3d1](https://linux-hardware.org/?probe=0acaadb3d1) | Jun 01, 2023 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [743741a477](https://linux-hardware.org/?probe=743741a477) | May 31, 2023 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [4c7348e8b3](https://linux-hardware.org/?probe=4c7348e8b3) | May 31, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [15b23b6779](https://linux-hardware.org/?probe=15b23b6779) | May 30, 2023 |
| Lenovo        | ThinkPad X230 2325UYW       | Notebook    | [c2165f9183](https://linux-hardware.org/?probe=c2165f9183) | May 29, 2023 |
| Gigabyte      | H61M-HD2                    | Desktop     | [7c57f43d4a](https://linux-hardware.org/?probe=7c57f43d4a) | May 29, 2023 |
| ASUSTek       | ROG Strix G513QR_G513QR     | Notebook    | [76a373f9dd](https://linux-hardware.org/?probe=76a373f9dd) | May 26, 2023 |
| Dell          | Latitude 7370               | Notebook    | [4c3bfe7a9d](https://linux-hardware.org/?probe=4c3bfe7a9d) | May 26, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [922428b203](https://linux-hardware.org/?probe=922428b203) | May 25, 2023 |
| Dell          | Latitude 7280               | Notebook    | [c9a41b2795](https://linux-hardware.org/?probe=c9a41b2795) | May 24, 2023 |
| Dell          | Latitude 7280               | Notebook    | [215bef2144](https://linux-hardware.org/?probe=215bef2144) | May 23, 2023 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [d2ddb8221f](https://linux-hardware.org/?probe=d2ddb8221f) | May 23, 2023 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [719fbbd5a5](https://linux-hardware.org/?probe=719fbbd5a5) | May 23, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [7a302f637c](https://linux-hardware.org/?probe=7a302f637c) | May 22, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [d0466f101a](https://linux-hardware.org/?probe=d0466f101a) | May 22, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [64b9ba417c](https://linux-hardware.org/?probe=64b9ba417c) | May 19, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [5c07806ab1](https://linux-hardware.org/?probe=5c07806ab1) | May 19, 2023 |
| HP            | ProBook 4540s               | Notebook    | [1ea4f5cce0](https://linux-hardware.org/?probe=1ea4f5cce0) | May 18, 2023 |
| HP            | EliteBook 8760w             | Notebook    | [4b60a3d942](https://linux-hardware.org/?probe=4b60a3d942) | May 15, 2023 |
| Lenovo        | ThinkPad E14 20RA0059VA     | Notebook    | [72280fb1c5](https://linux-hardware.org/?probe=72280fb1c5) | May 14, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [689db5f7b4](https://linux-hardware.org/?probe=689db5f7b4) | May 14, 2023 |
| Dell          | Latitude 7370               | Notebook    | [78654593c7](https://linux-hardware.org/?probe=78654593c7) | May 10, 2023 |
| Acer          | Extensa 215-54              | Notebook    | [c2392e1f40](https://linux-hardware.org/?probe=c2392e1f40) | May 10, 2023 |
| Acer          | Extensa 215-54              | Notebook    | [4dc1934f7b](https://linux-hardware.org/?probe=4dc1934f7b) | May 09, 2023 |
| Dell          | Latitude 7370               | Notebook    | [4ea44288b5](https://linux-hardware.org/?probe=4ea44288b5) | May 08, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [4ad69aea88](https://linux-hardware.org/?probe=4ad69aea88) | May 05, 2023 |
| Dell          | Precision 7720              | Notebook    | [b6c3392263](https://linux-hardware.org/?probe=b6c3392263) | May 05, 2023 |
| HP            | Notebook                    | Notebook    | [a34031954a](https://linux-hardware.org/?probe=a34031954a) | May 05, 2023 |
| ASUSTek       | K42Jc                       | Notebook    | [ba4b9c97f9](https://linux-hardware.org/?probe=ba4b9c97f9) | May 05, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [e9c446ce66](https://linux-hardware.org/?probe=e9c446ce66) | May 03, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | Notebook    | [4fbbf7e453](https://linux-hardware.org/?probe=4fbbf7e453) | May 02, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | Notebook    | [cfe1d4ffab](https://linux-hardware.org/?probe=cfe1d4ffab) | May 02, 2023 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [f3b5a181df](https://linux-hardware.org/?probe=f3b5a181df) | May 02, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [85df1ec917](https://linux-hardware.org/?probe=85df1ec917) | Apr 29, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [9d6905e35d](https://linux-hardware.org/?probe=9d6905e35d) | Apr 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [7ba933a829](https://linux-hardware.org/?probe=7ba933a829) | Apr 28, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [d2ed10f8b1](https://linux-hardware.org/?probe=d2ed10f8b1) | Apr 27, 2023 |
| Dell          | Vostro 1550                 | Notebook    | [d7951530f0](https://linux-hardware.org/?probe=d7951530f0) | Apr 26, 2023 |
| HP            | ProBook 4540s               | Notebook    | [ac831756d0](https://linux-hardware.org/?probe=ac831756d0) | Apr 26, 2023 |
| Dell          | Inspiron 14 5410            | Notebook    | [89017780fa](https://linux-hardware.org/?probe=89017780fa) | Apr 25, 2023 |
| HP            | ProBook 4540s               | Notebook    | [db866a1036](https://linux-hardware.org/?probe=db866a1036) | Apr 24, 2023 |
| ASUSTek       | PRIME X399-A                | Desktop     | [b4861cf35c](https://linux-hardware.org/?probe=b4861cf35c) | Apr 23, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C3C... | Notebook    | [b37a4411c5](https://linux-hardware.org/?probe=b37a4411c5) | Apr 22, 2023 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [0f3f45f8e9](https://linux-hardware.org/?probe=0f3f45f8e9) | Apr 13, 2023 |
| Lenovo        | ThinkPad E460 20ETA05KAU    | Notebook    | [a8090f51bc](https://linux-hardware.org/?probe=a8090f51bc) | Apr 09, 2023 |
| ASUSTek       | ROG Zephyrus M15 GU502LV... | Notebook    | [fc68164465](https://linux-hardware.org/?probe=fc68164465) | Apr 08, 2023 |
| ASUSTek       | ROG Zephyrus M15 GU502LV... | Notebook    | [1dcab8aee7](https://linux-hardware.org/?probe=1dcab8aee7) | Apr 08, 2023 |
| Gigabyte      | AORUS 15P KD                | Notebook    | [0b53411753](https://linux-hardware.org/?probe=0b53411753) | Apr 07, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [04c16989b3](https://linux-hardware.org/?probe=04c16989b3) | Apr 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [b307524661](https://linux-hardware.org/?probe=b307524661) | Apr 06, 2023 |
| Acer          | Extensa 215-54              | Notebook    | [60a8537172](https://linux-hardware.org/?probe=60a8537172) | Apr 05, 2023 |
| MSI           | Z97 GAMING 5                | Desktop     | [2f61bfa5a5](https://linux-hardware.org/?probe=2f61bfa5a5) | Apr 04, 2023 |
| MSI           | Z97 GAMING 5                | Desktop     | [1e81e330e1](https://linux-hardware.org/?probe=1e81e330e1) | Apr 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [7a61d16701](https://linux-hardware.org/?probe=7a61d16701) | Apr 04, 2023 |
| MSI           | 760GM-P33                   | Desktop     | [4145a32920](https://linux-hardware.org/?probe=4145a32920) | Apr 03, 2023 |
| Google        | Lillipup                    | Notebook    | [09292890c9](https://linux-hardware.org/?probe=09292890c9) | Mar 30, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [9edda5f374](https://linux-hardware.org/?probe=9edda5f374) | Mar 28, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [c25f99afed](https://linux-hardware.org/?probe=c25f99afed) | Mar 28, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [0180776452](https://linux-hardware.org/?probe=0180776452) | Mar 26, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [728805785d](https://linux-hardware.org/?probe=728805785d) | Mar 25, 2023 |
| HP            | ZBook Firefly 14 inch G9... | Notebook    | [35030027f5](https://linux-hardware.org/?probe=35030027f5) | Mar 21, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | Notebook    | [0927eb4ba9](https://linux-hardware.org/?probe=0927eb4ba9) | Mar 17, 2023 |
| MSI           | Katana GF66 12UC            | Notebook    | [8307fbf791](https://linux-hardware.org/?probe=8307fbf791) | Mar 14, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [6752797fe9](https://linux-hardware.org/?probe=6752797fe9) | Mar 14, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [2e0019e450](https://linux-hardware.org/?probe=2e0019e450) | Mar 14, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | Notebook    | [b5d8bdc57d](https://linux-hardware.org/?probe=b5d8bdc57d) | Mar 12, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | Notebook    | [4525fa2931](https://linux-hardware.org/?probe=4525fa2931) | Mar 12, 2023 |
| HP            | ZBook Firefly 15.6 inch ... | Notebook    | [47f7858a60](https://linux-hardware.org/?probe=47f7858a60) | Mar 07, 2023 |
| Acer          | Aspire E5-575               | Notebook    | [143b06f2d6](https://linux-hardware.org/?probe=143b06f2d6) | Mar 06, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [fe287f85c8](https://linux-hardware.org/?probe=fe287f85c8) | Mar 05, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [d3bb7ff642](https://linux-hardware.org/?probe=d3bb7ff642) | Mar 05, 2023 |
| HP            | Pavilion 15                 | Notebook    | [3a06e7e211](https://linux-hardware.org/?probe=3a06e7e211) | Mar 05, 2023 |
| ASRock        | B560M-C                     | Desktop     | [a93d64aa2c](https://linux-hardware.org/?probe=a93d64aa2c) | Feb 28, 2023 |
| ASRock        | B560M-C                     | Desktop     | [cbbd0a63d4](https://linux-hardware.org/?probe=cbbd0a63d4) | Feb 28, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [418b5dd7ff](https://linux-hardware.org/?probe=418b5dd7ff) | Feb 27, 2023 |
| Pegatron      | 2ACB                        | Desktop     | [13355a7d07](https://linux-hardware.org/?probe=13355a7d07) | Feb 26, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | Notebook    | [85bc55a850](https://linux-hardware.org/?probe=85bc55a850) | Feb 26, 2023 |
| Lenovo        | ThinkPad X230 23253Z5       | Notebook    | [1237b75ae4](https://linux-hardware.org/?probe=1237b75ae4) | Feb 24, 2023 |
| Dell          | 0C1R19 A02                  | Desktop     | [42ff2c0844](https://linux-hardware.org/?probe=42ff2c0844) | Feb 22, 2023 |
| Dell          | Inspiron 3421               | Notebook    | [fd899aea79](https://linux-hardware.org/?probe=fd899aea79) | Feb 22, 2023 |
| Alienware     | 17 R5                       | Notebook    | [1d234f85b4](https://linux-hardware.org/?probe=1d234f85b4) | Feb 22, 2023 |
| Alienware     | 17 R5                       | Notebook    | [5b6b8eee92](https://linux-hardware.org/?probe=5b6b8eee92) | Feb 22, 2023 |
| ASRock        | B560M-C                     | Desktop     | [0641c704e9](https://linux-hardware.org/?probe=0641c704e9) | Feb 20, 2023 |
| Biostar       | B450MH                      | Desktop     | [963e90387d](https://linux-hardware.org/?probe=963e90387d) | Feb 17, 2023 |
| Google        | Robo360                     | Notebook    | [e7c85b2410](https://linux-hardware.org/?probe=e7c85b2410) | Feb 09, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [bfb29a2d13](https://linux-hardware.org/?probe=bfb29a2d13) | Feb 04, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [725e7248ee](https://linux-hardware.org/?probe=725e7248ee) | Feb 04, 2023 |
| Acer          | Swift SFX14-51G             | Notebook    | [9f67df0760](https://linux-hardware.org/?probe=9f67df0760) | Feb 03, 2023 |
| ASRock        | Z87M Extreme4               | Desktop     | [8821f128c8](https://linux-hardware.org/?probe=8821f128c8) | Feb 03, 2023 |
| Lenovo        | ThinkPad T460 20FMS2J300    | Notebook    | [741b347456](https://linux-hardware.org/?probe=741b347456) | Feb 02, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d800b8a4b9](https://linux-hardware.org/?probe=d800b8a4b9) | Jan 30, 2023 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [15644c39de](https://linux-hardware.org/?probe=15644c39de) | Jan 25, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [91e33f05ed](https://linux-hardware.org/?probe=91e33f05ed) | Jan 24, 2023 |
| Gigabyte      | GA-880GMA-USB3              | Desktop     | [eb10e25652](https://linux-hardware.org/?probe=eb10e25652) | Jan 23, 2023 |
| Gigabyte      | GA-880GMA-USB3              | Desktop     | [6552c7b8b3](https://linux-hardware.org/?probe=6552c7b8b3) | Jan 22, 2023 |
| MSI           | Katana GF66 12UC            | Notebook    | [543136f475](https://linux-hardware.org/?probe=543136f475) | Jan 20, 2023 |
| Gigabyte      | GA-880GMA-USB3              | Desktop     | [64164ef7df](https://linux-hardware.org/?probe=64164ef7df) | Jan 20, 2023 |
| Gigabyte      | GA-880GMA-USB3              | Desktop     | [46befb7112](https://linux-hardware.org/?probe=46befb7112) | Jan 20, 2023 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [4b76c154f3](https://linux-hardware.org/?probe=4b76c154f3) | Jan 20, 2023 |
| Quanta        | TW9/SW9                     | Notebook    | [4a196739f5](https://linux-hardware.org/?probe=4a196739f5) | Jan 18, 2023 |
| Lenovo        | ThinkPad E590 20NB0003AD    | Notebook    | [fe3de007e1](https://linux-hardware.org/?probe=fe3de007e1) | Jan 16, 2023 |
| Intel Clie... | LAPBC510                    | Notebook    | [493f0e9608](https://linux-hardware.org/?probe=493f0e9608) | Jan 13, 2023 |
| Intel Clie... | LAPBC510                    | Notebook    | [ac0b81bf2e](https://linux-hardware.org/?probe=ac0b81bf2e) | Jan 13, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [d8ab62070c](https://linux-hardware.org/?probe=d8ab62070c) | Jan 11, 2023 |
| Dell          | Latitude E6520              | Notebook    | [96679022de](https://linux-hardware.org/?probe=96679022de) | Jan 06, 2023 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [9496d56fab](https://linux-hardware.org/?probe=9496d56fab) | Jan 04, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [3629e42dc4](https://linux-hardware.org/?probe=3629e42dc4) | Jan 04, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [0df48a29e1](https://linux-hardware.org/?probe=0df48a29e1) | Jan 03, 2023 |
| Unknown       | Unknown                     | Notebook    | [1e55cad727](https://linux-hardware.org/?probe=1e55cad727) | Dec 25, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [aaac67afbe](https://linux-hardware.org/?probe=aaac67afbe) | Dec 23, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [5bbf457036](https://linux-hardware.org/?probe=5bbf457036) | Dec 22, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [be01b942ed](https://linux-hardware.org/?probe=be01b942ed) | Dec 22, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [4fc06d2c89](https://linux-hardware.org/?probe=4fc06d2c89) | Dec 22, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [3c22afd21b](https://linux-hardware.org/?probe=3c22afd21b) | Dec 22, 2022 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [d45689035c](https://linux-hardware.org/?probe=d45689035c) | Dec 19, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [7895ac3dc1](https://linux-hardware.org/?probe=7895ac3dc1) | Dec 17, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [30f6db8749](https://linux-hardware.org/?probe=30f6db8749) | Dec 17, 2022 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [a17338c77a](https://linux-hardware.org/?probe=a17338c77a) | Dec 17, 2022 |
| HP            | 3397                        | Desktop     | [33ba62be32](https://linux-hardware.org/?probe=33ba62be32) | Dec 10, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [0e7586e771](https://linux-hardware.org/?probe=0e7586e771) | Dec 06, 2022 |
| Dell          | G3 3500                     | Notebook    | [5b23644904](https://linux-hardware.org/?probe=5b23644904) | Dec 05, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [90db11aeba](https://linux-hardware.org/?probe=90db11aeba) | Dec 04, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [6c74973e99](https://linux-hardware.org/?probe=6c74973e99) | Dec 04, 2022 |
| Intel Clie... | LAPBC510                    | Notebook    | [e903f5edea](https://linux-hardware.org/?probe=e903f5edea) | Dec 02, 2022 |
| MSI           | GT60                        | Notebook    | [07557bed1b](https://linux-hardware.org/?probe=07557bed1b) | Nov 29, 2022 |
| Quanta        | TW9/SW9                     | Notebook    | [5bfeb648aa](https://linux-hardware.org/?probe=5bfeb648aa) | Nov 28, 2022 |
| Quanta        | TW9/SW9                     | Notebook    | [ba75780c3e](https://linux-hardware.org/?probe=ba75780c3e) | Nov 28, 2022 |
| Intel Clie... | LAPBC510                    | Notebook    | [f58ff7b6fa](https://linux-hardware.org/?probe=f58ff7b6fa) | Nov 27, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [d57a12d93c](https://linux-hardware.org/?probe=d57a12d93c) | Nov 20, 2022 |
| ASUSTek       | Z170-DELUXE                 | Desktop     | [7928d11567](https://linux-hardware.org/?probe=7928d11567) | Nov 19, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [3050d57edc](https://linux-hardware.org/?probe=3050d57edc) | Nov 17, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [b152ccfb56](https://linux-hardware.org/?probe=b152ccfb56) | Nov 14, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [104fb805bd](https://linux-hardware.org/?probe=104fb805bd) | Nov 09, 2022 |
| Dell          | 0C1R19 A02                  | Desktop     | [514ae17aa9](https://linux-hardware.org/?probe=514ae17aa9) | Nov 06, 2022 |
| HP            | 89B5 A                      | Desktop     | [1b04604c98](https://linux-hardware.org/?probe=1b04604c98) | Nov 03, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | Notebook    | [a65efa454e](https://linux-hardware.org/?probe=a65efa454e) | Nov 01, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | Notebook    | [3380dfae20](https://linux-hardware.org/?probe=3380dfae20) | Nov 01, 2022 |
| HP            | Victus by Laptop 16-d1xx... | Notebook    | [f141a6cddf](https://linux-hardware.org/?probe=f141a6cddf) | Oct 31, 2022 |
| HP            | Victus by Laptop 16-d1xx... | Notebook    | [b9890126af](https://linux-hardware.org/?probe=b9890126af) | Oct 31, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [9eec3492e9](https://linux-hardware.org/?probe=9eec3492e9) | Oct 30, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [c6a7aeb8ad](https://linux-hardware.org/?probe=c6a7aeb8ad) | Oct 30, 2022 |
| Dell          | Latitude 3350               | Notebook    | [e545da88bf](https://linux-hardware.org/?probe=e545da88bf) | Oct 28, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [5b16264bea](https://linux-hardware.org/?probe=5b16264bea) | Oct 28, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [afd2f21c66](https://linux-hardware.org/?probe=afd2f21c66) | Oct 26, 2022 |
| Acer          | Aspire ES1-111M             | Notebook    | [ebff9e2fa5](https://linux-hardware.org/?probe=ebff9e2fa5) | Oct 25, 2022 |
| Dell          | Latitude E5500              | Notebook    | [10cb5545fd](https://linux-hardware.org/?probe=10cb5545fd) | Oct 24, 2022 |
| Gigabyte      | Z97N-WIFI                   | Desktop     | [dd5c78f136](https://linux-hardware.org/?probe=dd5c78f136) | Oct 24, 2022 |
| Gigabyte      | Z97N-WIFI                   | Desktop     | [10d8d16b6c](https://linux-hardware.org/?probe=10d8d16b6c) | Oct 24, 2022 |
| Dell          | Inspiron 13-7378            | Notebook    | [fbd3c71f34](https://linux-hardware.org/?probe=fbd3c71f34) | Oct 23, 2022 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [7c046d1ba8](https://linux-hardware.org/?probe=7c046d1ba8) | Oct 23, 2022 |
| Gigabyte      | M61SME-S2                   | Desktop     | [6595a0b531](https://linux-hardware.org/?probe=6595a0b531) | Oct 19, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [6a85eb0ff4](https://linux-hardware.org/?probe=6a85eb0ff4) | Oct 14, 2022 |
| ASUSTek       | P6X58D-E                    | Desktop     | [d84fc5ce81](https://linux-hardware.org/?probe=d84fc5ce81) | Oct 13, 2022 |
| ASUSTek       | P6X58D-E                    | Desktop     | [2a896ec4f6](https://linux-hardware.org/?probe=2a896ec4f6) | Oct 13, 2022 |
| Clevo         | W25xHPx                     | Notebook    | [04196b2306](https://linux-hardware.org/?probe=04196b2306) | Oct 13, 2022 |
| Irbis         | NB121                       | Notebook    | [04f312f46b](https://linux-hardware.org/?probe=04f312f46b) | Oct 13, 2022 |
| Irbis         | NB121                       | Notebook    | [ff99468633](https://linux-hardware.org/?probe=ff99468633) | Oct 13, 2022 |
| Toshiba       | Satellite C75D-B            | Notebook    | [7ba818df9e](https://linux-hardware.org/?probe=7ba818df9e) | Oct 11, 2022 |
| Alienware     | m15 R7                      | Notebook    | [79aa2b2dd4](https://linux-hardware.org/?probe=79aa2b2dd4) | Oct 10, 2022 |
| Lenovo        | LEGIONC7 82EH               | Notebook    | [880c4773fd](https://linux-hardware.org/?probe=880c4773fd) | Oct 06, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | Notebook    | [f02e3f9e3b](https://linux-hardware.org/?probe=f02e3f9e3b) | Oct 04, 2022 |
| Lenovo        | ThinkPad E570 20H5009MUS    | Notebook    | [5b3df02ed5](https://linux-hardware.org/?probe=5b3df02ed5) | Oct 03, 2022 |
| HP            | Unknown                     | Notebook    | [0a6433c4fe](https://linux-hardware.org/?probe=0a6433c4fe) | Oct 03, 2022 |
| Lenovo        | ThinkPad E570 20H5009MUS    | Notebook    | [70451644fc](https://linux-hardware.org/?probe=70451644fc) | Oct 03, 2022 |
| BANGHO        | GAMER GM-X 15s              | Notebook    | [d3e2d5452a](https://linux-hardware.org/?probe=d3e2d5452a) | Oct 03, 2022 |
| Gigabyte      | H110M-H DDR3-CF             | Desktop     | [8169fe8dbd](https://linux-hardware.org/?probe=8169fe8dbd) | Oct 01, 2022 |
| HP            | Presario CQ58               | Notebook    | [4bb50cd19d](https://linux-hardware.org/?probe=4bb50cd19d) | Sep 28, 2022 |
| Dell          | Inspiron 16 7620 2-in-1     | Convertible | [7ad1831ce9](https://linux-hardware.org/?probe=7ad1831ce9) | Sep 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | Notebook    | [9616464154](https://linux-hardware.org/?probe=9616464154) | Sep 26, 2022 |
| Dell          | Latitude 3350               | Notebook    | [62c380dcd0](https://linux-hardware.org/?probe=62c380dcd0) | Sep 22, 2022 |
| MSI           | Katana GF66 12UD            | Notebook    | [c0c6c57498](https://linux-hardware.org/?probe=c0c6c57498) | Sep 17, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [5dc824a596](https://linux-hardware.org/?probe=5dc824a596) | Sep 16, 2022 |
| Toshiba       | Satellite C855D             | Notebook    | [bae94a45be](https://linux-hardware.org/?probe=bae94a45be) | Sep 13, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [f8de7730b6](https://linux-hardware.org/?probe=f8de7730b6) | Sep 11, 2022 |
| Dell          | Inspiron 14 5410            | Notebook    | [315af016c7](https://linux-hardware.org/?probe=315af016c7) | Sep 09, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d4e798ff22](https://linux-hardware.org/?probe=d4e798ff22) | Sep 07, 2022 |
| Dell          | Latitude E6400              | Notebook    | [1de889aa64](https://linux-hardware.org/?probe=1de889aa64) | Sep 05, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [b50b1adb0f](https://linux-hardware.org/?probe=b50b1adb0f) | Sep 01, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [1d04855f84](https://linux-hardware.org/?probe=1d04855f84) | Aug 29, 2022 |
| Acer          | Predator PT516-51s          | Notebook    | [5739f0b1a0](https://linux-hardware.org/?probe=5739f0b1a0) | Aug 28, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [7439a7400d](https://linux-hardware.org/?probe=7439a7400d) | Aug 27, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [fa26302bd8](https://linux-hardware.org/?probe=fa26302bd8) | Aug 27, 2022 |
| Gigabyte      | H61M-S2PT                   | Desktop     | [b7e6228017](https://linux-hardware.org/?probe=b7e6228017) | Aug 22, 2022 |
| Acer          | Aspire A517-52              | Notebook    | [b61f6861a6](https://linux-hardware.org/?probe=b61f6861a6) | Aug 21, 2022 |
| Standard      | Unknown                     | Notebook    | [782f229d6c](https://linux-hardware.org/?probe=782f229d6c) | Aug 17, 2022 |
| Panasonic     | CF-31JBGNNDM                | Notebook    | [008621e9e0](https://linux-hardware.org/?probe=008621e9e0) | Aug 14, 2022 |
| Lenovo        | ThinkPad T420 4180MNU       | Notebook    | [437387fdc3](https://linux-hardware.org/?probe=437387fdc3) | Aug 10, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [47608d95ea](https://linux-hardware.org/?probe=47608d95ea) | Aug 10, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [0bd14e553d](https://linux-hardware.org/?probe=0bd14e553d) | Aug 10, 2022 |
| Lenovo        | ThinkPad T420 4180MNU       | Notebook    | [dae7cc7b69](https://linux-hardware.org/?probe=dae7cc7b69) | Aug 08, 2022 |
| Dell          | Inspiron 13-7359            | Notebook    | [1a13c37dce](https://linux-hardware.org/?probe=1a13c37dce) | Aug 08, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [a7e9a050ea](https://linux-hardware.org/?probe=a7e9a050ea) | Aug 02, 2022 |
| HP            | EliteBook 850 G6            | Notebook    | [1dca756b58](https://linux-hardware.org/?probe=1dca756b58) | Jul 31, 2022 |
| Dell          | Latitude E6420              | Notebook    | [a6b2ee6088](https://linux-hardware.org/?probe=a6b2ee6088) | Jul 30, 2022 |
| Gateway       | SX2855                      | Desktop     | [a896e3b0f7](https://linux-hardware.org/?probe=a896e3b0f7) | Jul 30, 2022 |
| HP            | 250 G2                      | Notebook    | [5650fd3dd6](https://linux-hardware.org/?probe=5650fd3dd6) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH532/G21          | Notebook    | [99fd83f85d](https://linux-hardware.org/?probe=99fd83f85d) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH532/G21          | Notebook    | [e64903db3d](https://linux-hardware.org/?probe=e64903db3d) | Jul 28, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [26be63e8a0](https://linux-hardware.org/?probe=26be63e8a0) | Jul 25, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [0bacf44374](https://linux-hardware.org/?probe=0bacf44374) | Jul 23, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [007eeacf86](https://linux-hardware.org/?probe=007eeacf86) | Jul 23, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [8ce974e537](https://linux-hardware.org/?probe=8ce974e537) | Jul 23, 2022 |
| Sony          | VPCSB1C5E                   | Notebook    | [184e5b179e](https://linux-hardware.org/?probe=184e5b179e) | Jul 23, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [4d3cf557ba](https://linux-hardware.org/?probe=4d3cf557ba) | Jul 23, 2022 |
| Lenovo        | Z40-70 80E6                 | Notebook    | [e77b84e593](https://linux-hardware.org/?probe=e77b84e593) | Jul 22, 2022 |
| Acer          | Predator PT516-51s          | Notebook    | [8337c958e2](https://linux-hardware.org/?probe=8337c958e2) | Jul 22, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [90cf247d2d](https://linux-hardware.org/?probe=90cf247d2d) | Jul 20, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [2d31c995c8](https://linux-hardware.org/?probe=2d31c995c8) | Jul 19, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [9e9ca5b39a](https://linux-hardware.org/?probe=9e9ca5b39a) | Jul 19, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [0539efedb2](https://linux-hardware.org/?probe=0539efedb2) | Jul 18, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [2c55e11e85](https://linux-hardware.org/?probe=2c55e11e85) | Jul 18, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [0e0a7a2fbc](https://linux-hardware.org/?probe=0e0a7a2fbc) | Jul 16, 2022 |
| Unknown       | Unknown                     | Notebook    | [a7de2e1421](https://linux-hardware.org/?probe=a7de2e1421) | Jul 14, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [623281f994](https://linux-hardware.org/?probe=623281f994) | Jul 14, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [713bd9f4b0](https://linux-hardware.org/?probe=713bd9f4b0) | Jul 14, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [49e71e9dc1](https://linux-hardware.org/?probe=49e71e9dc1) | Jul 13, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [f6c3c6f86e](https://linux-hardware.org/?probe=f6c3c6f86e) | Jul 12, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [2ffa772ac9](https://linux-hardware.org/?probe=2ffa772ac9) | Jul 10, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [c680f5f212](https://linux-hardware.org/?probe=c680f5f212) | Jul 10, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [fd79c5481a](https://linux-hardware.org/?probe=fd79c5481a) | Jul 09, 2022 |
| Lenovo        | ThinkPad L430 2465C32       | Notebook    | [f088c4ae11](https://linux-hardware.org/?probe=f088c4ae11) | Jul 09, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [48aa7eac9f](https://linux-hardware.org/?probe=48aa7eac9f) | Jul 09, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [8a96de43eb](https://linux-hardware.org/?probe=8a96de43eb) | Jul 08, 2022 |
| Acer          | Predator PT516-51s          | Notebook    | [9309da8b72](https://linux-hardware.org/?probe=9309da8b72) | Jul 05, 2022 |
| HP            | Laptop 15-bs2xx             | Notebook    | [fc35a0726c](https://linux-hardware.org/?probe=fc35a0726c) | Jul 03, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [3ba50e78b9](https://linux-hardware.org/?probe=3ba50e78b9) | Jun 29, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [f33854651b](https://linux-hardware.org/?probe=f33854651b) | Jun 29, 2022 |
| Samsung       | 930QDB                      | Convertible | [e022aed2bc](https://linux-hardware.org/?probe=e022aed2bc) | Jun 28, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [8b55dcfd2d](https://linux-hardware.org/?probe=8b55dcfd2d) | Jun 28, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [d1b8d3ff84](https://linux-hardware.org/?probe=d1b8d3ff84) | Jun 27, 2022 |
| HP            | Pavilion dv6                | Notebook    | [ff3ebff8ff](https://linux-hardware.org/?probe=ff3ebff8ff) | Jun 27, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [6f3036d638](https://linux-hardware.org/?probe=6f3036d638) | Jun 26, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [6348a01f19](https://linux-hardware.org/?probe=6348a01f19) | Jun 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [86c0fc94e6](https://linux-hardware.org/?probe=86c0fc94e6) | Jun 23, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [656a452bc6](https://linux-hardware.org/?probe=656a452bc6) | Jun 21, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [2969400046](https://linux-hardware.org/?probe=2969400046) | Jun 20, 2022 |
| Gigabyte      | H61M-USB3H                  | Desktop     | [6b9dcbd952](https://linux-hardware.org/?probe=6b9dcbd952) | Jun 20, 2022 |
| Toshiba       | Satellite-L845              | Notebook    | [d617282ee0](https://linux-hardware.org/?probe=d617282ee0) | Jun 18, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [4cafd85b65](https://linux-hardware.org/?probe=4cafd85b65) | Jun 15, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [2a3c65eda7](https://linux-hardware.org/?probe=2a3c65eda7) | Jun 10, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [e2efffbd81](https://linux-hardware.org/?probe=e2efffbd81) | Jun 07, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [c509b12c63](https://linux-hardware.org/?probe=c509b12c63) | Jun 07, 2022 |
| Unknown       | TB-4000                     | Desktop     | [c268e7111b](https://linux-hardware.org/?probe=c268e7111b) | Jun 07, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [fd246079ad](https://linux-hardware.org/?probe=fd246079ad) | Jun 04, 2022 |
| HP            | ENVY x360 m6 Convertible    | Convertible | [7e3fc5fe06](https://linux-hardware.org/?probe=7e3fc5fe06) | Jun 02, 2022 |
| HP            | ENVY x360 m6 Convertible    | Convertible | [02ace99875](https://linux-hardware.org/?probe=02ace99875) | Jun 02, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [449fc46111](https://linux-hardware.org/?probe=449fc46111) | Jun 01, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [c4468417e9](https://linux-hardware.org/?probe=c4468417e9) | Jun 01, 2022 |
| Lenovo        | ThinkPad X230 2325N66       | Notebook    | [2061351dbc](https://linux-hardware.org/?probe=2061351dbc) | May 28, 2022 |
| Dell          | Latitude E6540              | Notebook    | [9171fd4d35](https://linux-hardware.org/?probe=9171fd4d35) | May 26, 2022 |
| Dell          | Latitude E6540              | Notebook    | [e7a078f1a1](https://linux-hardware.org/?probe=e7a078f1a1) | May 26, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [dbf37b46f6](https://linux-hardware.org/?probe=dbf37b46f6) | May 25, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [9fcb918138](https://linux-hardware.org/?probe=9fcb918138) | May 25, 2022 |
| Dell          | Latitude 5400               | Notebook    | [fdfa7356be](https://linux-hardware.org/?probe=fdfa7356be) | May 23, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | Notebook    | [aa6aefb86a](https://linux-hardware.org/?probe=aa6aefb86a) | May 21, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [cb4959b996](https://linux-hardware.org/?probe=cb4959b996) | May 21, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [fb7cb376e9](https://linux-hardware.org/?probe=fb7cb376e9) | May 21, 2022 |
| Dell          | Latitude E6410              | Notebook    | [b098a84988](https://linux-hardware.org/?probe=b098a84988) | May 20, 2022 |
| MSI           | G31M3-L V2                  | Desktop     | [29d45c64bb](https://linux-hardware.org/?probe=29d45c64bb) | May 11, 2022 |
| MSI           | GE62 6QE                    | Notebook    | [6a3161d4ee](https://linux-hardware.org/?probe=6a3161d4ee) | May 09, 2022 |
| Timi          | TM1613                      | Notebook    | [114752ffeb](https://linux-hardware.org/?probe=114752ffeb) | May 08, 2022 |
| Timi          | TM1613                      | Notebook    | [b714f7dbd8](https://linux-hardware.org/?probe=b714f7dbd8) | May 08, 2022 |
| HP            | 1495                        | Desktop     | [c845f7b657](https://linux-hardware.org/?probe=c845f7b657) | May 05, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [60a636868c](https://linux-hardware.org/?probe=60a636868c) | Apr 30, 2022 |
| Unknown       | TB-4000                     | Desktop     | [99911022e9](https://linux-hardware.org/?probe=99911022e9) | Apr 26, 2022 |
| ASUSTek       | ROG Strix G733ZX_G733ZX     | Notebook    | [032acaf88c](https://linux-hardware.org/?probe=032acaf88c) | Apr 25, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [56d949b3bb](https://linux-hardware.org/?probe=56d949b3bb) | Apr 23, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [0ee15f97fd](https://linux-hardware.org/?probe=0ee15f97fd) | Apr 23, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [73a8933099](https://linux-hardware.org/?probe=73a8933099) | Apr 22, 2022 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [4d911b0d94](https://linux-hardware.org/?probe=4d911b0d94) | Apr 22, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [9c06485301](https://linux-hardware.org/?probe=9c06485301) | Apr 21, 2022 |
| HP            | 18E7                        | Desktop     | [1b6db66cc1](https://linux-hardware.org/?probe=1b6db66cc1) | Apr 19, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [b68f986aaf](https://linux-hardware.org/?probe=b68f986aaf) | Apr 17, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [93306ff9ee](https://linux-hardware.org/?probe=93306ff9ee) | Apr 17, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [7e03ed9f70](https://linux-hardware.org/?probe=7e03ed9f70) | Apr 13, 2022 |
| Apple         | MacBookPro15,1              | Notebook    | [b9187e8521](https://linux-hardware.org/?probe=b9187e8521) | Apr 13, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [bdccad7bf9](https://linux-hardware.org/?probe=bdccad7bf9) | Apr 12, 2022 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [0832404b40](https://linux-hardware.org/?probe=0832404b40) | Apr 11, 2022 |
| MSI           | B350 TOMAHAWK               | Desktop     | [b1a322fa38](https://linux-hardware.org/?probe=b1a322fa38) | Apr 11, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [b3afe4ff08](https://linux-hardware.org/?probe=b3afe4ff08) | Apr 11, 2022 |
| ASUSTek       | X540SAA                     | Notebook    | [b670324e44](https://linux-hardware.org/?probe=b670324e44) | Apr 10, 2022 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [8cb4405c5f](https://linux-hardware.org/?probe=8cb4405c5f) | Apr 09, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [320ae25dbf](https://linux-hardware.org/?probe=320ae25dbf) | Apr 09, 2022 |
| Toshiba       | Satellite Click 2 L35W-B    | Notebook    | [f992f9305a](https://linux-hardware.org/?probe=f992f9305a) | Apr 07, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [e422a0e166](https://linux-hardware.org/?probe=e422a0e166) | Apr 05, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [b96e97fa2b](https://linux-hardware.org/?probe=b96e97fa2b) | Apr 04, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [401792c28e](https://linux-hardware.org/?probe=401792c28e) | Apr 01, 2022 |
| Alienware     | M14xR1                      | Notebook    | [f3ea3f497c](https://linux-hardware.org/?probe=f3ea3f497c) | Apr 01, 2022 |
| HP            | Notebook                    | Notebook    | [313ca81d16](https://linux-hardware.org/?probe=313ca81d16) | Mar 27, 2022 |
| ECS           | Nettle2                     | Desktop     | [4939d60e6d](https://linux-hardware.org/?probe=4939d60e6d) | Mar 27, 2022 |
| HP            | 18E7                        | Desktop     | [d8d1c3d468](https://linux-hardware.org/?probe=d8d1c3d468) | Mar 26, 2022 |
| ASUSTek       | X540SAA                     | Notebook    | [988b4570ed](https://linux-hardware.org/?probe=988b4570ed) | Mar 24, 2022 |
| Lenovo        | ThinkPad E15 20RD0086UE     | Notebook    | [f26a636b1b](https://linux-hardware.org/?probe=f26a636b1b) | Mar 24, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [72245fe662](https://linux-hardware.org/?probe=72245fe662) | Mar 22, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [85260f6ed1](https://linux-hardware.org/?probe=85260f6ed1) | Mar 20, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [e849ec3916](https://linux-hardware.org/?probe=e849ec3916) | Mar 20, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [b0769dffdd](https://linux-hardware.org/?probe=b0769dffdd) | Mar 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [2c1ca9145b](https://linux-hardware.org/?probe=2c1ca9145b) | Mar 18, 2022 |
| ASUSTek       | H170M-E D3                  | Desktop     | [167928d6e9](https://linux-hardware.org/?probe=167928d6e9) | Mar 17, 2022 |
| Wistron       | JIG31B3                     | Desktop     | [a360eaf501](https://linux-hardware.org/?probe=a360eaf501) | Mar 15, 2022 |
| ASUSTek       | H170M-E D3                  | Desktop     | [937c0097ca](https://linux-hardware.org/?probe=937c0097ca) | Mar 14, 2022 |
| Toshiba       | Satellite L775D             | Notebook    | [3d09dbe623](https://linux-hardware.org/?probe=3d09dbe623) | Mar 14, 2022 |
| Positivo      | Q232A                       | Notebook    | [87c79b8f05](https://linux-hardware.org/?probe=87c79b8f05) | Mar 13, 2022 |
| ASUSTek       | F2A85-M                     | Desktop     | [36d17e4fdb](https://linux-hardware.org/?probe=36d17e4fdb) | Mar 13, 2022 |
| ASUSTek       | F2A85-M                     | Desktop     | [453d0816b3](https://linux-hardware.org/?probe=453d0816b3) | Mar 13, 2022 |
| ASRock        | Z87M Extreme4               | Desktop     | [dba57ee1b3](https://linux-hardware.org/?probe=dba57ee1b3) | Mar 12, 2022 |
| ASUSTek       | X75VC                       | Notebook    | [3973070120](https://linux-hardware.org/?probe=3973070120) | Mar 12, 2022 |
| Jumper        | EZbook                      | Notebook    | [c374bd5058](https://linux-hardware.org/?probe=c374bd5058) | Mar 11, 2022 |
| Apple         | MacBookAir3,1               | Notebook    | [320f9e6841](https://linux-hardware.org/?probe=320f9e6841) | Mar 11, 2022 |
| Metabox       | Edge-Pro NS50MU             | Notebook    | [1371afa6ac](https://linux-hardware.org/?probe=1371afa6ac) | Mar 11, 2022 |
| MSI           | G31M3-L V2                  | Desktop     | [4c15ba6fb9](https://linux-hardware.org/?probe=4c15ba6fb9) | Mar 10, 2022 |
| Apple         | MacBookPro11,4              | Notebook    | [b27d8c8724](https://linux-hardware.org/?probe=b27d8c8724) | Mar 10, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [e77116d171](https://linux-hardware.org/?probe=e77116d171) | Mar 10, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [161eda858b](https://linux-hardware.org/?probe=161eda858b) | Mar 10, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [36bada67c8](https://linux-hardware.org/?probe=36bada67c8) | Mar 08, 2022 |
| Dell          | Latitude XT2                | Notebook    | [ff6a48346f](https://linux-hardware.org/?probe=ff6a48346f) | Mar 07, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [f9c159a911](https://linux-hardware.org/?probe=f9c159a911) | Mar 06, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [ec13383aff](https://linux-hardware.org/?probe=ec13383aff) | Mar 06, 2022 |
| Jumper        | EZbook                      | Notebook    | [09544efb61](https://linux-hardware.org/?probe=09544efb61) | Mar 05, 2022 |
| Apple         | MacBookPro11,4              | Notebook    | [fb03915a3e](https://linux-hardware.org/?probe=fb03915a3e) | Mar 03, 2022 |
| Unknown       | TB-4000                     | Desktop     | [d92c05a18a](https://linux-hardware.org/?probe=d92c05a18a) | Mar 03, 2022 |
| Daewoo Luc... | Solo Top                    | Desktop     | [7f7b20688f](https://linux-hardware.org/?probe=7f7b20688f) | Mar 03, 2022 |
| Jumper        | EZbook                      | Notebook    | [de9a14c4ec](https://linux-hardware.org/?probe=de9a14c4ec) | Mar 02, 2022 |
| Chuwi         | GemiBook                    | Notebook    | [bb9f45273a](https://linux-hardware.org/?probe=bb9f45273a) | Mar 01, 2022 |
| Unknown       | TB-4000                     | Desktop     | [dc43686a5a](https://linux-hardware.org/?probe=dc43686a5a) | Feb 27, 2022 |
| Samsung       | 550P5C/550P7C               | Notebook    | [f14f73025f](https://linux-hardware.org/?probe=f14f73025f) | Feb 27, 2022 |
| Dell          | 0GXM1W A02                  | Desktop     | [044a00e086](https://linux-hardware.org/?probe=044a00e086) | Feb 25, 2022 |
| Toshiba       | Satellite C75D-B            | Notebook    | [952057ee2b](https://linux-hardware.org/?probe=952057ee2b) | Feb 24, 2022 |
| Acer          | Nitro AN517-41              | Notebook    | [47b906a661](https://linux-hardware.org/?probe=47b906a661) | Feb 23, 2022 |
| Chuwi         | GemiBook                    | Notebook    | [25f5f358cb](https://linux-hardware.org/?probe=25f5f358cb) | Feb 17, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [f83ccc9cce](https://linux-hardware.org/?probe=f83ccc9cce) | Feb 15, 2022 |
| Sony          | SVP1321L1EBI                | Notebook    | [b35a3fbfec](https://linux-hardware.org/?probe=b35a3fbfec) | Feb 13, 2022 |
| HP            | ProBook 4535s               | Notebook    | [0d0cd13f8b](https://linux-hardware.org/?probe=0d0cd13f8b) | Feb 12, 2022 |
| ASUSTek       | Benicia                     | Desktop     | [aceee2d932](https://linux-hardware.org/?probe=aceee2d932) | Feb 12, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [0df06bcae3](https://linux-hardware.org/?probe=0df06bcae3) | Feb 11, 2022 |
| HP            | Notebook                    | Notebook    | [1f47143486](https://linux-hardware.org/?probe=1f47143486) | Feb 06, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [9f4f77f51d](https://linux-hardware.org/?probe=9f4f77f51d) | Feb 06, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [b6d5344f4e](https://linux-hardware.org/?probe=b6d5344f4e) | Feb 04, 2022 |
| Unknown       | TB-4000                     | Desktop     | [225e399fc1](https://linux-hardware.org/?probe=225e399fc1) | Feb 03, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [5aa1140ad5](https://linux-hardware.org/?probe=5aa1140ad5) | Feb 02, 2022 |
| Lenovo        | ThinkPad T480 20L6SCYP00    | Notebook    | [d69eb6fc3e](https://linux-hardware.org/?probe=d69eb6fc3e) | Jan 30, 2022 |
| GPU Compan... | GWTN141-10                  | Notebook    | [89835cd678](https://linux-hardware.org/?probe=89835cd678) | Jan 30, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [880cca4c8f](https://linux-hardware.org/?probe=880cca4c8f) | Jan 24, 2022 |
| Microsoft     | Surface Book                | Tablet      | [327a2ec07f](https://linux-hardware.org/?probe=327a2ec07f) | Jan 22, 2022 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [1e5331da8c](https://linux-hardware.org/?probe=1e5331da8c) | Jan 21, 2022 |
| Dell          | Latitude 7480               | Notebook    | [e184163da5](https://linux-hardware.org/?probe=e184163da5) | Jan 19, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [9901f0a14a](https://linux-hardware.org/?probe=9901f0a14a) | Jan 18, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [3837c06ca1](https://linux-hardware.org/?probe=3837c06ca1) | Jan 18, 2022 |
| Dell          | Inspiron 5580               | Notebook    | [a8e7059c51](https://linux-hardware.org/?probe=a8e7059c51) | Jan 17, 2022 |
| Lenovo        | ThinkPad E14 20RA0016GE     | Notebook    | [46eeb2d4b8](https://linux-hardware.org/?probe=46eeb2d4b8) | Jan 14, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [4e45161acc](https://linux-hardware.org/?probe=4e45161acc) | Jan 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [4c04661023](https://linux-hardware.org/?probe=4c04661023) | Jan 12, 2022 |
| Unknown       | Unknown                     | Desktop     | [bccc675fea](https://linux-hardware.org/?probe=bccc675fea) | Jan 08, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [8f4b5410ad](https://linux-hardware.org/?probe=8f4b5410ad) | Jan 06, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [f75ebfbbc8](https://linux-hardware.org/?probe=f75ebfbbc8) | Jan 01, 2022 |
| Dell          | 04YP6J A01                  | Desktop     | [680408ec06](https://linux-hardware.org/?probe=680408ec06) | Jan 01, 2022 |
| Dell          | 04YP6J A01                  | Desktop     | [623d384766](https://linux-hardware.org/?probe=623d384766) | Jan 01, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [4ec2105ead](https://linux-hardware.org/?probe=4ec2105ead) | Jan 01, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [d0c5b453db](https://linux-hardware.org/?probe=d0c5b453db) | Dec 31, 2021 |
| Lenovo        | IdeaPad Y580                | Notebook    | [cbb37b3b6a](https://linux-hardware.org/?probe=cbb37b3b6a) | Dec 20, 2021 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [5c55046f50](https://linux-hardware.org/?probe=5c55046f50) | Dec 13, 2021 |
| Lenovo        | IdeaPad Y580                | Notebook    | [48d92517e3](https://linux-hardware.org/?probe=48d92517e3) | Dec 11, 2021 |
| Dell          | Precision M4600             | Notebook    | [f386251b14](https://linux-hardware.org/?probe=f386251b14) | Nov 30, 2021 |
| Alienware     | m15 R6                      | Notebook    | [487678d2e5](https://linux-hardware.org/?probe=487678d2e5) | Nov 27, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [550ad36300](https://linux-hardware.org/?probe=550ad36300) | Nov 26, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [db67630cee](https://linux-hardware.org/?probe=db67630cee) | Nov 26, 2021 |
| Toxic         | GM7MQ8P                     | Notebook    | [deb5cbd490](https://linux-hardware.org/?probe=deb5cbd490) | Nov 24, 2021 |
| MSI           | Creator Z16 Hiroshi F A1... | Notebook    | [40f615079d](https://linux-hardware.org/?probe=40f615079d) | Nov 23, 2021 |
| HP            | ZBook Firefly 14 G7 Mobi... | Notebook    | [0dc4672364](https://linux-hardware.org/?probe=0dc4672364) | Nov 21, 2021 |
| Alienware     | 0PGRP5 A02                  | Desktop     | [aeacaefd26](https://linux-hardware.org/?probe=aeacaefd26) | Nov 14, 2021 |
| ASRock        | Z87 Killer                  | Desktop     | [0aafc0d981](https://linux-hardware.org/?probe=0aafc0d981) | Nov 13, 2021 |
| Toshiba       | Satellite L655              | Notebook    | [e41f3dd777](https://linux-hardware.org/?probe=e41f3dd777) | Nov 12, 2021 |
| Dell          | Latitude E6410              | Notebook    | [2f9b89dbb4](https://linux-hardware.org/?probe=2f9b89dbb4) | Nov 09, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [6ef3dbe032](https://linux-hardware.org/?probe=6ef3dbe032) | Nov 09, 2021 |
| Dell          | Latitude E6410              | Notebook    | [099708f286](https://linux-hardware.org/?probe=099708f286) | Nov 07, 2021 |
| Acer          | TravelMate 5720             | Notebook    | [8e19effec8](https://linux-hardware.org/?probe=8e19effec8) | Nov 06, 2021 |
| HP            | Pavilion g7                 | Notebook    | [c1b5449516](https://linux-hardware.org/?probe=c1b5449516) | Nov 05, 2021 |
| Acer          | Aspire TC-780               | Desktop     | [f6de1ed637](https://linux-hardware.org/?probe=f6de1ed637) | Nov 04, 2021 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [833500916c](https://linux-hardware.org/?probe=833500916c) | Nov 03, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [37a983c1e7](https://linux-hardware.org/?probe=37a983c1e7) | Oct 26, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [ca3a74943a](https://linux-hardware.org/?probe=ca3a74943a) | Oct 25, 2021 |
| Dell          | Latitude E7450              | Notebook    | [2d94d751ff](https://linux-hardware.org/?probe=2d94d751ff) | Oct 22, 2021 |
| Dell          | Latitude E7450              | Notebook    | [a2b09ead76](https://linux-hardware.org/?probe=a2b09ead76) | Oct 22, 2021 |
| MSI           | GT60 2OC/2OD                | Notebook    | [56c85806e2](https://linux-hardware.org/?probe=56c85806e2) | Oct 20, 2021 |
| HP            | Laptop 15q-dy0xxx           | Notebook    | [aa4c6c2a25](https://linux-hardware.org/?probe=aa4c6c2a25) | Oct 18, 2021 |
| Dell          | Inspiron MM061              | Notebook    | [5b16f69a60](https://linux-hardware.org/?probe=5b16f69a60) | Oct 17, 2021 |
| Dell          | Inspiron MM061              | Notebook    | [caa2855c26](https://linux-hardware.org/?probe=caa2855c26) | Oct 17, 2021 |
| HP            | Pavilion g7                 | Notebook    | [7e80ec4599](https://linux-hardware.org/?probe=7e80ec4599) | Oct 11, 2021 |
| HP            | Pavilion g7                 | Notebook    | [cd8ce3be30](https://linux-hardware.org/?probe=cd8ce3be30) | Oct 10, 2021 |
| HP            | Pavilion g7                 | Notebook    | [dd3f8159e0](https://linux-hardware.org/?probe=dd3f8159e0) | Oct 10, 2021 |
| MSI           | GT60 2OC/2OD                | Notebook    | [79e12d69ec](https://linux-hardware.org/?probe=79e12d69ec) | Oct 08, 2021 |
| Dell          | 0T2HR0 A00                  | Desktop     | [dc55f173fe](https://linux-hardware.org/?probe=dc55f173fe) | Oct 05, 2021 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [7dcd6067ac](https://linux-hardware.org/?probe=7dcd6067ac) | Oct 04, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [d0cd1577c7](https://linux-hardware.org/?probe=d0cd1577c7) | Oct 04, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [fb11994deb](https://linux-hardware.org/?probe=fb11994deb) | Oct 04, 2021 |
| Dell          | Inspiron 7501               | Notebook    | [1d532e72c0](https://linux-hardware.org/?probe=1d532e72c0) | Oct 02, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [b33c31b0cf](https://linux-hardware.org/?probe=b33c31b0cf) | Oct 02, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [eafc16e86f](https://linux-hardware.org/?probe=eafc16e86f) | Sep 24, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [3eac62e012](https://linux-hardware.org/?probe=3eac62e012) | Sep 24, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [b733e7fac1](https://linux-hardware.org/?probe=b733e7fac1) | Sep 23, 2021 |
| Radxa         | ROCK 5B                     | Soc         | [c57bcaa35d](https://linux-hardware.org/?probe=c57bcaa35d) | Sep 19, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [493f8d65cb](https://linux-hardware.org/?probe=493f8d65cb) | Sep 18, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [09b7566e74](https://linux-hardware.org/?probe=09b7566e74) | Sep 14, 2021 |
| Acer          | TravelMate 5720             | Notebook    | [b08ac328d1](https://linux-hardware.org/?probe=b08ac328d1) | Sep 14, 2021 |
| Eluktronic... | MAG-15u                     | Notebook    | [f931222022](https://linux-hardware.org/?probe=f931222022) | Sep 13, 2021 |
| Acer          | Swift SF114-33              | Notebook    | [31bc470f08](https://linux-hardware.org/?probe=31bc470f08) | Sep 11, 2021 |
| Lenovo        | ThinkPad X250 20CL001GZA    | Notebook    | [e732588a09](https://linux-hardware.org/?probe=e732588a09) | Sep 05, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [ede284a3a3](https://linux-hardware.org/?probe=ede284a3a3) | Aug 30, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [03676f1856](https://linux-hardware.org/?probe=03676f1856) | Aug 28, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [41663f4fb2](https://linux-hardware.org/?probe=41663f4fb2) | Aug 26, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [0460f1a29b](https://linux-hardware.org/?probe=0460f1a29b) | Aug 24, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [2ef0cf3a18](https://linux-hardware.org/?probe=2ef0cf3a18) | Aug 16, 2021 |
| Dell          | Inspiron 5593               | Notebook    | [340be8f7fb](https://linux-hardware.org/?probe=340be8f7fb) | Aug 15, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [bd70ed892a](https://linux-hardware.org/?probe=bd70ed892a) | Aug 14, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [b741d2ab2b](https://linux-hardware.org/?probe=b741d2ab2b) | Aug 12, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [3ba02ffef3](https://linux-hardware.org/?probe=3ba02ffef3) | Aug 10, 2021 |
| HP            | Pavilion dv6700             | Notebook    | [8714c1e6ab](https://linux-hardware.org/?probe=8714c1e6ab) | Aug 10, 2021 |
| MSI           | GT60 2OC/2OD                | Notebook    | [5ff69797f3](https://linux-hardware.org/?probe=5ff69797f3) | Aug 09, 2021 |
| ASUSTek       | X75VB                       | Notebook    | [bc26a9b439](https://linux-hardware.org/?probe=bc26a9b439) | Aug 07, 2021 |
| HP            | Pavilion 15                 | Notebook    | [f0f33cb33a](https://linux-hardware.org/?probe=f0f33cb33a) | Aug 06, 2021 |
| Dell          | Latitude E6420              | Notebook    | [9e72687dd4](https://linux-hardware.org/?probe=9e72687dd4) | Aug 05, 2021 |
| Microsoft     | Surface Pro 3               | Tablet      | [57037eb714](https://linux-hardware.org/?probe=57037eb714) | Aug 05, 2021 |
| Microsoft     | Surface Pro 3               | Tablet      | [89852ab731](https://linux-hardware.org/?probe=89852ab731) | Aug 05, 2021 |
| HP            | Pavilion dv7                | Notebook    | [5d8cfc9c95](https://linux-hardware.org/?probe=5d8cfc9c95) | Aug 04, 2021 |
| HP            | Pavilion dv7                | Notebook    | [1d2d7a30f9](https://linux-hardware.org/?probe=1d2d7a30f9) | Aug 04, 2021 |
| ZOTAC         | Unknown                     | Desktop     | [0324aff0a3](https://linux-hardware.org/?probe=0324aff0a3) | Aug 03, 2021 |
| ZOTAC         | Unknown                     | Desktop     | [c1a9e01bd7](https://linux-hardware.org/?probe=c1a9e01bd7) | Aug 03, 2021 |
| ASUSTek       | G74Sx                       | Notebook    | [fb80932ddd](https://linux-hardware.org/?probe=fb80932ddd) | Jul 23, 2021 |
| HP            | 1850                        | Desktop     | [687c780f5c](https://linux-hardware.org/?probe=687c780f5c) | Jul 19, 2021 |
| Dell          | Latitude E7440              | Notebook    | [3a22179f3b](https://linux-hardware.org/?probe=3a22179f3b) | Jul 18, 2021 |
| Dell          | 0T10XW A02                  | Desktop     | [57a4116288](https://linux-hardware.org/?probe=57a4116288) | Jul 17, 2021 |
| ASUSTek       | X450EA                      | Notebook    | [91a0ff32e1](https://linux-hardware.org/?probe=91a0ff32e1) | Jul 06, 2021 |
| ASUSTek       | X450EA                      | Notebook    | [e4dc18ebf9](https://linux-hardware.org/?probe=e4dc18ebf9) | Jul 06, 2021 |
| Dell          | Precision M6400             | Notebook    | [7f2245c976](https://linux-hardware.org/?probe=7f2245c976) | Jun 24, 2021 |
| ASUSTek       | Q524UQ                      | Notebook    | [33d61b2077](https://linux-hardware.org/?probe=33d61b2077) | Jun 17, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [2a633bc008](https://linux-hardware.org/?probe=2a633bc008) | Jun 14, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [e3bb48a049](https://linux-hardware.org/?probe=e3bb48a049) | Jun 14, 2021 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [fa4061e79f](https://linux-hardware.org/?probe=fa4061e79f) | Jun 09, 2021 |
| Gateway       | MP8708                      | Notebook    | [ba382202c2](https://linux-hardware.org/?probe=ba382202c2) | Jun 04, 2021 |
| HP            | ZBook 15 G5                 | Notebook    | [462531aabd](https://linux-hardware.org/?probe=462531aabd) | Jun 03, 2021 |
| ASUSTek       | Q524UQ                      | Notebook    | [b510297404](https://linux-hardware.org/?probe=b510297404) | Jun 03, 2021 |
| Dell          | Inspiron 5558               | Notebook    | [91fdca7228](https://linux-hardware.org/?probe=91fdca7228) | May 31, 2021 |
| HP            | 1850                        | Desktop     | [3bde7e8e11](https://linux-hardware.org/?probe=3bde7e8e11) | May 27, 2021 |
| MSI           | GE73 Raider RGB 8RE         | Notebook    | [5aedb75ad8](https://linux-hardware.org/?probe=5aedb75ad8) | May 21, 2021 |
| Fujitsu       | LIFEBOOK T731               | Notebook    | [1cb3267b57](https://linux-hardware.org/?probe=1cb3267b57) | May 21, 2021 |
| Dell          | Inspiron 5420               | Notebook    | [dc6bc48c4d](https://linux-hardware.org/?probe=dc6bc48c4d) | May 18, 2021 |
| Lenovo        | ThinkPad X260 20F5S5QT00    | Notebook    | [a84514b117](https://linux-hardware.org/?probe=a84514b117) | May 14, 2021 |
| Intel         | NUC8i7HVB J68196-601        | Mini pc     | [d186af4ee3](https://linux-hardware.org/?probe=d186af4ee3) | May 14, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [aa4c3ffed1](https://linux-hardware.org/?probe=aa4c3ffed1) | May 13, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [605367d5d4](https://linux-hardware.org/?probe=605367d5d4) | May 13, 2021 |
| HP            | Pavilion dv4                | Notebook    | [250773011b](https://linux-hardware.org/?probe=250773011b) | May 07, 2021 |
| Dell          | 0C1R19 A02                  | Desktop     | [ff5bb2ee2a](https://linux-hardware.org/?probe=ff5bb2ee2a) | May 03, 2021 |
| HP            | HDX PREMIUM SERIES          | Notebook    | [47374d1b5f](https://linux-hardware.org/?probe=47374d1b5f) | Apr 27, 2021 |
| HP            | HDX PREMIUM SERIES          | Notebook    | [58b0d9473e](https://linux-hardware.org/?probe=58b0d9473e) | Apr 27, 2021 |
| HP            | 8430 1000                   | All in one  | [5c5adcc248](https://linux-hardware.org/?probe=5c5adcc248) | Apr 24, 2021 |
| ASUSTek       | PRIME X399-A                | Desktop     | [4dd4f28ca7](https://linux-hardware.org/?probe=4dd4f28ca7) | Apr 11, 2021 |
| Acer          | Aspire E1-571G              | Notebook    | [ee1ba6ee04](https://linux-hardware.org/?probe=ee1ba6ee04) | Apr 01, 2021 |
| PC Special... | N150CU                      | Notebook    | [39136d47f7](https://linux-hardware.org/?probe=39136d47f7) | Apr 01, 2021 |
| MSI           | GE75 Raider 10SF            | Notebook    | [d15c48b6a1](https://linux-hardware.org/?probe=d15c48b6a1) | Mar 29, 2021 |
| Acer          | Predator PO3-600 V:1.1      | Desktop     | [6ea75bdbb5](https://linux-hardware.org/?probe=6ea75bdbb5) | Mar 26, 2021 |
| Dell          | Inspiron 5420               | Notebook    | [78663f1468](https://linux-hardware.org/?probe=78663f1468) | Mar 25, 2021 |
| MSI           | GE63 Raider RGB 8RE         | Notebook    | [de917105cd](https://linux-hardware.org/?probe=de917105cd) | Mar 22, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [01ab712b94](https://linux-hardware.org/?probe=01ab712b94) | Mar 22, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [67ed2b4e7f](https://linux-hardware.org/?probe=67ed2b4e7f) | Mar 22, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [acda849408](https://linux-hardware.org/?probe=acda849408) | Mar 22, 2021 |
| Wortmann      | TERRA_MOBILE_1542           | Notebook    | [76f7963d8a](https://linux-hardware.org/?probe=76f7963d8a) | Mar 21, 2021 |
| Wortmann      | TERRA_MOBILE_1542           | Notebook    | [12fb4cc711](https://linux-hardware.org/?probe=12fb4cc711) | Mar 21, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [6b26a69326](https://linux-hardware.org/?probe=6b26a69326) | Mar 21, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [a4bf4bb64c](https://linux-hardware.org/?probe=a4bf4bb64c) | Mar 17, 2021 |
| HP            | Pavilion dv6                | Notebook    | [06b3024017](https://linux-hardware.org/?probe=06b3024017) | Mar 14, 2021 |
| Dell          | Inspiron 5420               | Notebook    | [11a466e06d](https://linux-hardware.org/?probe=11a466e06d) | Mar 05, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [89174dda21](https://linux-hardware.org/?probe=89174dda21) | Feb 27, 2021 |
| Dell          | Inspiron 5420               | Notebook    | [489ed0f996](https://linux-hardware.org/?probe=489ed0f996) | Feb 26, 2021 |
| Dell          | Inspiron 5420               | Notebook    | [a357eb71e0](https://linux-hardware.org/?probe=a357eb71e0) | Feb 22, 2021 |
| HP            | 339A                        | Desktop     | [b105e94284](https://linux-hardware.org/?probe=b105e94284) | Feb 20, 2021 |
| HP            | 339A                        | Desktop     | [3dfdd6aa5e](https://linux-hardware.org/?probe=3dfdd6aa5e) | Feb 20, 2021 |
| Lenovo        | IdeaPad 110-14ISK 80UC      | Notebook    | [2cf1bfd6c6](https://linux-hardware.org/?probe=2cf1bfd6c6) | Feb 16, 2021 |
| HP            | Laptop 15-db0xxx            | Notebook    | [c337c59497](https://linux-hardware.org/?probe=c337c59497) | Feb 13, 2021 |
| HP            | ProBook 450 G1              | Notebook    | [284fd25f3e](https://linux-hardware.org/?probe=284fd25f3e) | Feb 11, 2021 |
| MSI           | B250M MORTAR                | Desktop     | [be8a65f362](https://linux-hardware.org/?probe=be8a65f362) | Feb 02, 2021 |
| Dell          | 0CU409                      | Desktop     | [64c8a84081](https://linux-hardware.org/?probe=64c8a84081) | Jan 29, 2021 |
| HP            | ENVY 15                     | Notebook    | [c39474b63f](https://linux-hardware.org/?probe=c39474b63f) | Jan 23, 2021 |
| Positivo B... | VJFE51F11X-B0111H           | Notebook    | [ea1a80dc34](https://linux-hardware.org/?probe=ea1a80dc34) | Jan 21, 2021 |
| Positivo B... | VJFE51F11X-B0111H           | Notebook    | [80dc10f323](https://linux-hardware.org/?probe=80dc10f323) | Jan 21, 2021 |
| Acer          | Aspire X3990                | Desktop     | [a3e9301c7f](https://linux-hardware.org/?probe=a3e9301c7f) | Jan 16, 2021 |
| Acer          | Aspire X3990                | Desktop     | [1660d13b44](https://linux-hardware.org/?probe=1660d13b44) | Jan 12, 2021 |
| HP            | 3047h                       | Desktop     | [8b50e12296](https://linux-hardware.org/?probe=8b50e12296) | Jan 07, 2021 |
| Dell          | Latitude 7390               | Notebook    | [0ef9ffc535](https://linux-hardware.org/?probe=0ef9ffc535) | Dec 27, 2020 |
| Medion        | MS-7621                     | Desktop     | [74c49730d1](https://linux-hardware.org/?probe=74c49730d1) | Dec 27, 2020 |
| Positivo      | POS-PIG43BC                 | Desktop     | [146c7d86bb](https://linux-hardware.org/?probe=146c7d86bb) | Dec 27, 2020 |
| ASUSTek       | X555LAB                     | Notebook    | [ab17ca4eef](https://linux-hardware.org/?probe=ab17ca4eef) | Dec 25, 2020 |
| Lenovo        | ThinkPad T490 20N2S04000    | Notebook    | [4f02aacb6d](https://linux-hardware.org/?probe=4f02aacb6d) | Dec 21, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [33960a08de](https://linux-hardware.org/?probe=33960a08de) | Dec 20, 2020 |
| Toshiba       | Satellite L750              | Notebook    | [748a6b0b09](https://linux-hardware.org/?probe=748a6b0b09) | Dec 16, 2020 |
| Dell          | Latitude E5440              | Notebook    | [7befb8e28b](https://linux-hardware.org/?probe=7befb8e28b) | Nov 29, 2020 |
| Dell          | Latitude E5440              | Notebook    | [3064211887](https://linux-hardware.org/?probe=3064211887) | Nov 28, 2020 |
| Lenovo        | ThinkPad X220 42912XG       | Notebook    | [ce89f09531](https://linux-hardware.org/?probe=ce89f09531) | Nov 26, 2020 |
| HP            | 3047h                       | Desktop     | [b65caab721](https://linux-hardware.org/?probe=b65caab721) | Nov 24, 2020 |
| Acer          | Aspire 5250                 | Notebook    | [11f670b6b1](https://linux-hardware.org/?probe=11f670b6b1) | Nov 23, 2020 |
| HP            | Compaq Presario C700        | Notebook    | [82be91a50a](https://linux-hardware.org/?probe=82be91a50a) | Nov 20, 2020 |
| HP            | Compaq Presario C700        | Notebook    | [f86087eece](https://linux-hardware.org/?probe=f86087eece) | Nov 20, 2020 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [458ab52080](https://linux-hardware.org/?probe=458ab52080) | Nov 17, 2020 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [6608936515](https://linux-hardware.org/?probe=6608936515) | Nov 10, 2020 |
| Foxconn       | 45CMX/45GMX/45CMX-K         | Desktop     | [7918687a8b](https://linux-hardware.org/?probe=7918687a8b) | Nov 07, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [c110de3643](https://linux-hardware.org/?probe=c110de3643) | Oct 31, 2020 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [f95c24897c](https://linux-hardware.org/?probe=f95c24897c) | Oct 30, 2020 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [f7a2b660d8](https://linux-hardware.org/?probe=f7a2b660d8) | Oct 29, 2020 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [c687805b04](https://linux-hardware.org/?probe=c687805b04) | Oct 29, 2020 |
| ASUSTek       | X540YA                      | Notebook    | [501ca10eeb](https://linux-hardware.org/?probe=501ca10eeb) | Oct 25, 2020 |
| ECS           | A740GM-M                    | Desktop     | [423f49affd](https://linux-hardware.org/?probe=423f49affd) | Oct 25, 2020 |
| Dell          | Vostro 3558                 | Notebook    | [8f4f321359](https://linux-hardware.org/?probe=8f4f321359) | Oct 18, 2020 |
| ASUSTek       | TUF Gaming FX705GD          | Notebook    | [8ce3caa35a](https://linux-hardware.org/?probe=8ce3caa35a) | Oct 15, 2020 |
| ASUSTek       | TUF Gaming FX705GD          | Notebook    | [b2d5b6eb69](https://linux-hardware.org/?probe=b2d5b6eb69) | Oct 15, 2020 |
| Lenovo        | ThinkPad T420s 4174W2P      | Notebook    | [c8eacff838](https://linux-hardware.org/?probe=c8eacff838) | Oct 10, 2020 |
| HP            | Pavilion 17                 | Notebook    | [2a0d11caf1](https://linux-hardware.org/?probe=2a0d11caf1) | Oct 09, 2020 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [f06ac6483c](https://linux-hardware.org/?probe=f06ac6483c) | Oct 06, 2020 |
| Razer         | Blade Stealth               | Notebook    | [564265e066](https://linux-hardware.org/?probe=564265e066) | Oct 01, 2020 |
| Acer          | Predator PH317-53           | Notebook    | [16cddb4fce](https://linux-hardware.org/?probe=16cddb4fce) | Sep 29, 2020 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [2bc8fbe372](https://linux-hardware.org/?probe=2bc8fbe372) | Sep 27, 2020 |
| Toshiba       | Satellite L750              | Notebook    | [74a0ca3614](https://linux-hardware.org/?probe=74a0ca3614) | Sep 25, 2020 |
| HP            | EliteBook Folio 9480m       | Notebook    | [bb1615dd63](https://linux-hardware.org/?probe=bb1615dd63) | Sep 24, 2020 |
| System76      | Gazelle                     | Notebook    | [d96d5e60ae](https://linux-hardware.org/?probe=d96d5e60ae) | Sep 20, 2020 |
| Lenovo        | IdeaPadFlex 4-1470 80SA     | Convertible | [4ad16b3038](https://linux-hardware.org/?probe=4ad16b3038) | Sep 20, 2020 |
| Alienware     | 17 R4                       | Notebook    | [d58b082d72](https://linux-hardware.org/?probe=d58b082d72) | Sep 19, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d77bb0aa31](https://linux-hardware.org/?probe=d77bb0aa31) | Sep 18, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [951e2d1aa6](https://linux-hardware.org/?probe=951e2d1aa6) | Sep 18, 2020 |
| Lenovo        | IdeaPadFlex 4-1470 80SA     | Convertible | [f88025bc71](https://linux-hardware.org/?probe=f88025bc71) | Sep 16, 2020 |
| Dell          | Latitude 3400               | Notebook    | [f7d1872e51](https://linux-hardware.org/?probe=f7d1872e51) | Sep 13, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [090d50eec1](https://linux-hardware.org/?probe=090d50eec1) | Sep 12, 2020 |
| Lenovo        | E41-25 81FS                 | Notebook    | [1e512df642](https://linux-hardware.org/?probe=1e512df642) | Sep 12, 2020 |
| Toshiba       | Satellite L750              | Notebook    | [091facc59a](https://linux-hardware.org/?probe=091facc59a) | Sep 12, 2020 |
| Dell          | Latitude 3400               | Notebook    | [825d226ad5](https://linux-hardware.org/?probe=825d226ad5) | Sep 10, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [fc23c05e20](https://linux-hardware.org/?probe=fc23c05e20) | Sep 04, 2020 |
| Lenovo        | ThinkPad X240 20AMS4MH00    | Notebook    | [3e6177e73c](https://linux-hardware.org/?probe=3e6177e73c) | Sep 01, 2020 |
| Gigabyte      | H370M DS3H-CF               | Desktop     | [affb4f7587](https://linux-hardware.org/?probe=affb4f7587) | Aug 29, 2020 |
| Lenovo        | IdeaPadFlex 4-1470 80SA     | Convertible | [c87fcab7c7](https://linux-hardware.org/?probe=c87fcab7c7) | Aug 26, 2020 |
| Lenovo        | IdeaPadFlex 4-1470 80SA     | Convertible | [608ad8477d](https://linux-hardware.org/?probe=608ad8477d) | Aug 22, 2020 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [dbf4ca0908](https://linux-hardware.org/?probe=dbf4ca0908) | Aug 10, 2020 |
| Sony          | VPCCB15FG                   | Notebook    | [4d93dfd9c0](https://linux-hardware.org/?probe=4d93dfd9c0) | Aug 09, 2020 |
| Dell          | System Inspiron N7110       | Notebook    | [c4ba9dc0dc](https://linux-hardware.org/?probe=c4ba9dc0dc) | Aug 05, 2020 |
| HP            | Notebook                    | Notebook    | [989b6b7d5d](https://linux-hardware.org/?probe=989b6b7d5d) | Aug 04, 2020 |
| Acer          | Aspire ES1-111M             | Notebook    | [359a7266e5](https://linux-hardware.org/?probe=359a7266e5) | Aug 03, 2020 |
| Lenovo        | G480 20149                  | Notebook    | [bfffb28472](https://linux-hardware.org/?probe=bfffb28472) | Jul 27, 2020 |
| Lenovo        | G480 20149                  | Notebook    | [53b70e68df](https://linux-hardware.org/?probe=53b70e68df) | Jul 27, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [f032f63f3a](https://linux-hardware.org/?probe=f032f63f3a) | Jul 26, 2020 |
| HP            | Notebook                    | Notebook    | [ee51b68070](https://linux-hardware.org/?probe=ee51b68070) | Jul 23, 2020 |
| HP            | Notebook                    | Notebook    | [87cfa4c37e](https://linux-hardware.org/?probe=87cfa4c37e) | Jul 23, 2020 |
| Dell          | System Inspiron N7110       | Notebook    | [3177a50194](https://linux-hardware.org/?probe=3177a50194) | Jul 22, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [f77f8a2639](https://linux-hardware.org/?probe=f77f8a2639) | Jul 15, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [4afe4f5961](https://linux-hardware.org/?probe=4afe4f5961) | Jul 15, 2020 |
| Acer          | Aspire V5-122P              | Notebook    | [a362dee702](https://linux-hardware.org/?probe=a362dee702) | Jul 10, 2020 |
| Dell          | Latitude 7480               | Notebook    | [aab5a5b50a](https://linux-hardware.org/?probe=aab5a5b50a) | Jul 07, 2020 |
| eMachines     | eME728                      | Notebook    | [3f409bf927](https://linux-hardware.org/?probe=3f409bf927) | Jul 05, 2020 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [3c48dbb383](https://linux-hardware.org/?probe=3c48dbb383) | Jul 05, 2020 |
| Apple         | Mac-F221BEC8                | Desktop     | [1d8d1db67e](https://linux-hardware.org/?probe=1d8d1db67e) | Jul 04, 2020 |
| Dell          | 0D6H9T A00                  | Desktop     | [06e9599063](https://linux-hardware.org/?probe=06e9599063) | Jul 04, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [dda8536e62](https://linux-hardware.org/?probe=dda8536e62) | Jun 11, 2020 |
| Dell          | G7 7790                     | Notebook    | [506d29b806](https://linux-hardware.org/?probe=506d29b806) | Jun 02, 2020 |
| Dell          | G7 7790                     | Notebook    | [0551762cbb](https://linux-hardware.org/?probe=0551762cbb) | Jun 02, 2020 |
| Biostar       | H77MU3                      | Desktop     | [048ffba01b](https://linux-hardware.org/?probe=048ffba01b) | May 24, 2020 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [7c05b67968](https://linux-hardware.org/?probe=7c05b67968) | May 22, 2020 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [fc8bf8a5a6](https://linux-hardware.org/?probe=fc8bf8a5a6) | May 22, 2020 |
| Google        | Celes                       | Notebook    | [d417dd63dd](https://linux-hardware.org/?probe=d417dd63dd) | May 22, 2020 |
| Google        | Celes                       | Notebook    | [88d722fa1b](https://linux-hardware.org/?probe=88d722fa1b) | May 22, 2020 |
| ASUSTek       | X75VB                       | Notebook    | [f41d9b003f](https://linux-hardware.org/?probe=f41d9b003f) | May 22, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [8e55010bac](https://linux-hardware.org/?probe=8e55010bac) | May 22, 2020 |
| Fujitsu       | LIFEBOOK A532               | Notebook    | [96ec25db7c](https://linux-hardware.org/?probe=96ec25db7c) | May 21, 2020 |
| Fujitsu       | LIFEBOOK A532               | Notebook    | [b2ecb833ba](https://linux-hardware.org/?probe=b2ecb833ba) | May 21, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [26293feb91](https://linux-hardware.org/?probe=26293feb91) | May 21, 2020 |
| Dell          | Inspiron MM061              | Notebook    | [a6bb0bfd0b](https://linux-hardware.org/?probe=a6bb0bfd0b) | May 21, 2020 |
| Dell          | 0VYXHD A00                  | Desktop     | [5e5d0a24f3](https://linux-hardware.org/?probe=5e5d0a24f3) | May 15, 2020 |
| ASUSTek       | N56VZ                       | Notebook    | [69ee412460](https://linux-hardware.org/?probe=69ee412460) | May 14, 2020 |
| Dell          | Inspiron MM061              | Notebook    | [0d48c76bfd](https://linux-hardware.org/?probe=0d48c76bfd) | May 11, 2020 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [d64b4a56e0](https://linux-hardware.org/?probe=d64b4a56e0) | May 08, 2020 |
| Dell          | 0VYXHD A00                  | Desktop     | [5a56c30293](https://linux-hardware.org/?probe=5a56c30293) | May 06, 2020 |
| ASUSTek       | X442URR                     | Notebook    | [7595f05acd](https://linux-hardware.org/?probe=7595f05acd) | May 04, 2020 |
| HP            | ProBook 6475b               | Notebook    | [c9ee4e6614](https://linux-hardware.org/?probe=c9ee4e6614) | May 03, 2020 |
| HP            | ProBook 6475b               | Notebook    | [06da2207cd](https://linux-hardware.org/?probe=06da2207cd) | May 02, 2020 |
| HP            | ProBook 6475b               | Notebook    | [b2ff4072ce](https://linux-hardware.org/?probe=b2ff4072ce) | May 02, 2020 |
| Toshiba       | Satellite L300D             | Notebook    | [5a320c4b78](https://linux-hardware.org/?probe=5a320c4b78) | May 02, 2020 |
| Dell          | 05DN3X A00                  | Desktop     | [7424c0caba](https://linux-hardware.org/?probe=7424c0caba) | May 02, 2020 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [3dc6534b5f](https://linux-hardware.org/?probe=3dc6534b5f) | May 01, 2020 |
| Dell          | Latitude E6420              | Notebook    | [ae3ade27d7](https://linux-hardware.org/?probe=ae3ade27d7) | Apr 29, 2020 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [6835f4fe95](https://linux-hardware.org/?probe=6835f4fe95) | Apr 28, 2020 |
| Dell          | Latitude E6420              | Notebook    | [83380135bc](https://linux-hardware.org/?probe=83380135bc) | Apr 27, 2020 |
| Dell          | Latitude E6420              | Notebook    | [12c77f16d5](https://linux-hardware.org/?probe=12c77f16d5) | Apr 27, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [6e636c5fd2](https://linux-hardware.org/?probe=6e636c5fd2) | Apr 27, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [d19700bc2d](https://linux-hardware.org/?probe=d19700bc2d) | Apr 27, 2020 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [72dcfa02ca](https://linux-hardware.org/?probe=72dcfa02ca) | Apr 26, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [37c314650f](https://linux-hardware.org/?probe=37c314650f) | Apr 26, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [9a9b368a7c](https://linux-hardware.org/?probe=9a9b368a7c) | Apr 26, 2020 |
| Dell          | XPS 12-9Q33                 | Notebook    | [f831495ef5](https://linux-hardware.org/?probe=f831495ef5) | Apr 25, 2020 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | Notebook    | [6bf9d537a8](https://linux-hardware.org/?probe=6bf9d537a8) | Apr 21, 2020 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [2dec0ef690](https://linux-hardware.org/?probe=2dec0ef690) | Apr 18, 2020 |
| HP            | Pavilion g6                 | Notebook    | [c54d518ca7](https://linux-hardware.org/?probe=c54d518ca7) | Apr 15, 2020 |
| ASUSTek       | K31CD-K                     | Desktop     | [b4ad316fa2](https://linux-hardware.org/?probe=b4ad316fa2) | Apr 14, 2020 |
| Dell          | 0CU409                      | Desktop     | [661761d2ca](https://linux-hardware.org/?probe=661761d2ca) | Apr 14, 2020 |
| Acer          | Aspire 5250                 | Notebook    | [100d4bacdc](https://linux-hardware.org/?probe=100d4bacdc) | Apr 14, 2020 |
| Dell          | 0CU409                      | Desktop     | [5512733c4a](https://linux-hardware.org/?probe=5512733c4a) | Apr 14, 2020 |
| Gigabyte      | GA-880GM-D2H                | Desktop     | [93da68c7fb](https://linux-hardware.org/?probe=93da68c7fb) | Apr 12, 2020 |
| Dell          | Inspiron 5721               | Notebook    | [23d5dff3bd](https://linux-hardware.org/?probe=23d5dff3bd) | Apr 11, 2020 |
| Dell          | Inspiron 3458               | Notebook    | [d9c91be81b](https://linux-hardware.org/?probe=d9c91be81b) | Apr 06, 2020 |
| Dell          | Inspiron 3458               | Notebook    | [a10080482e](https://linux-hardware.org/?probe=a10080482e) | Apr 05, 2020 |
| Dell          | Inspiron 3458               | Notebook    | [cfb5a6d57c](https://linux-hardware.org/?probe=cfb5a6d57c) | Apr 05, 2020 |
| ASUSTek       | N56VZ                       | Notebook    | [249176d47f](https://linux-hardware.org/?probe=249176d47f) | Apr 01, 2020 |
| Samsung       | RV415/RV515                 | Notebook    | [3b9248b95f](https://linux-hardware.org/?probe=3b9248b95f) | Mar 31, 2020 |
| ASUSTek       | T101HA                      | Tablet      | [224ebfd9b3](https://linux-hardware.org/?probe=224ebfd9b3) | Mar 30, 2020 |
| ASUSTek       | T101HA                      | Tablet      | [79e98a64cf](https://linux-hardware.org/?probe=79e98a64cf) | Mar 30, 2020 |
| Lenovo        | ThinkPad T440s 20ARS01C0... | Notebook    | [aa9f421079](https://linux-hardware.org/?probe=aa9f421079) | Mar 23, 2020 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [cf7e8cd869](https://linux-hardware.org/?probe=cf7e8cd869) | Mar 16, 2020 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [05f8c8eef4](https://linux-hardware.org/?probe=05f8c8eef4) | Feb 29, 2020 |
| HP            | Laptop 17-by0xxx            | Notebook    | [21c7ac4323](https://linux-hardware.org/?probe=21c7ac4323) | Feb 17, 2020 |
| Lenovo        | ThinkPad E14 20RA0016GE     | Notebook    | [dd543cf29b](https://linux-hardware.org/?probe=dd543cf29b) | Feb 09, 2020 |
| Gigabyte      | AX370-Gaming-CF se1         | Desktop     | [2bfc7eae61](https://linux-hardware.org/?probe=2bfc7eae61) | Feb 06, 2020 |
| Gigabyte      | AX370-Gaming-CF se1         | Desktop     | [1e8ccbe5b9](https://linux-hardware.org/?probe=1e8ccbe5b9) | Feb 04, 2020 |
| Notebook      | W510TU                      | Notebook    | [987d9232fe](https://linux-hardware.org/?probe=987d9232fe) | Jan 31, 2020 |
| Notebook      | W510TU                      | Notebook    | [4556eb747b](https://linux-hardware.org/?probe=4556eb747b) | Jan 31, 2020 |
| HP            | EliteBook 8460p             | Notebook    | [8b7c621317](https://linux-hardware.org/?probe=8b7c621317) | Jan 26, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [38658290e2](https://linux-hardware.org/?probe=38658290e2) | Jan 19, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [05e5552eea](https://linux-hardware.org/?probe=05e5552eea) | Jan 19, 2020 |
| HUAWEI        | WRT-WX9                     | Notebook    | [375040e90b](https://linux-hardware.org/?probe=375040e90b) | Jan 05, 2020 |
| Notebook      | W510TU                      | Notebook    | [aa2e59fd60](https://linux-hardware.org/?probe=aa2e59fd60) | Dec 25, 2019 |
| Apple         | MacBookAir7,2               | Notebook    | [1a26d7b485](https://linux-hardware.org/?probe=1a26d7b485) | Dec 21, 2019 |
| Notebook      | W510TU                      | Notebook    | [f2102dfe5b](https://linux-hardware.org/?probe=f2102dfe5b) | Dec 09, 2019 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [51389e5c4a](https://linux-hardware.org/?probe=51389e5c4a) | Dec 07, 2019 |
| Apple         | MacBookAir7,2               | Notebook    | [73a28279bc](https://linux-hardware.org/?probe=73a28279bc) | Dec 05, 2019 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [7bc298d7af](https://linux-hardware.org/?probe=7bc298d7af) | Nov 10, 2019 |
| HP            | 630                         | Notebook    | [687ccfe3b1](https://linux-hardware.org/?probe=687ccfe3b1) | Sep 28, 2019 |
| Acer          | Aspire E5-475               | Notebook    | [3e3fad10fe](https://linux-hardware.org/?probe=3e3fad10fe) | Aug 18, 2019 |
| Gateway       | NE-522                      | Notebook    | [d562b598e5](https://linux-hardware.org/?probe=d562b598e5) | Aug 10, 2019 |
| Lenovo        | Y50-70 Touch 20349          | Notebook    | [c0c73d01ba](https://linux-hardware.org/?probe=c0c73d01ba) | Jun 08, 2019 |
| Apple         | MacBookPro11,4              | Notebook    | [49a28f87b9](https://linux-hardware.org/?probe=49a28f87b9) | May 21, 2019 |
| Acer          | Swift SF314-54              | Notebook    | [89013e65ec](https://linux-hardware.org/?probe=89013e65ec) | Apr 26, 2019 |
| ASUSTek       | X510UQ                      | Notebook    | [74e81c78ab](https://linux-hardware.org/?probe=74e81c78ab) | Feb 16, 2019 |
| ASUSTek       | X510UQ                      | Notebook    | [50fc8650ad](https://linux-hardware.org/?probe=50fc8650ad) | Feb 16, 2019 |
| Dell          | Latitude E7440              | Notebook    | [ce392df9c0](https://linux-hardware.org/?probe=ce392df9c0) | Dec 26, 2018 |
| HP            | Pavilion 15                 | Notebook    | [921bec751d](https://linux-hardware.org/?probe=921bec751d) | Oct 13, 2018 |
| Digma         | CITI E401 ET4007EW          | Notebook    | [597e65c2a4](https://linux-hardware.org/?probe=597e65c2a4) | Jan 07, 2018 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Parrot/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Parrot 5.3   | 120       | 17.02%  |
| Parrot 5.0   | 119       | 16.88%  |
| Parrot 4.11  | 98        | 13.9%   |
| Parrot 5.1   | 74        | 10.5%   |
| Parrot 4.10  | 60        | 8.51%   |
| Parrot 6.2   | 53        | 7.52%   |
| Parrot 6.0   | 50        | 7.09%   |
| Parrot 5.2   | 36        | 5.11%   |
| Parrot 6.1   | 30        | 4.26%   |
| Parrot 4.9   | 23        | 3.26%   |
| Parrot 4.8   | 23        | 3.26%   |
| Parrot 4.7   | 13        | 1.84%   |
| Parrot 4.6   | 2         | 0.28%   |
| Parrot 4.5   | 1         | 0.14%   |
| Parrot 4.4   | 1         | 0.14%   |
| Parrot 4.2.2 | 1         | 0.14%   |
| Parrot 3.10  | 1         | 0.14%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Parrot | 668       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                   | Computers | Percent |
|---------------------------|-----------|---------|
| 6.1.0-1parrot1-amd64      | 119       | 16.69%  |
| 6.5.0-13parrot1-amd64     | 64        | 8.98%   |
| 5.16.0-12parrot1-amd64    | 56        | 7.85%   |
| 5.14.0-9parrot1-amd64     | 54        | 7.57%   |
| 6.0.0-12parrot1-amd64     | 48        | 6.73%   |
| 5.18.0-14parrot1-amd64    | 35        | 4.91%   |
| 5.10.0-6parrot1-amd64     | 35        | 4.91%   |
| 5.7.0-2parrot2-amd64      | 33        | 4.63%   |
| 6.0.0-2parrot1-amd64      | 32        | 4.49%   |
| 6.10.11-amd64             | 31        | 4.35%   |
| 5.5.0-1parrot1-amd64      | 25        | 3.51%   |
| 6.9.7-amd64               | 22        | 3.09%   |
| 5.10.0-8parrot1-amd64     | 18        | 2.52%   |
| 5.18.0-1parrot1-amd64     | 17        | 2.38%   |
| 5.4.0-4parrot1-amd64      | 16        | 2.24%   |
| 5.15.0-15parrot1-amd64    | 11        | 1.54%   |
| 5.14.0-2parrot1-amd64     | 11        | 1.54%   |
| 5.6.0-2parrot1-amd64      | 10        | 1.4%    |
| 5.9.0-2parrot1-amd64      | 9         | 1.26%   |
| 5.8.0-2parrot1-amd64      | 6         | 0.84%   |
| 6.5.0-3parrot1-amd64      | 5         | 0.7%    |
| 5.4.0-2parrot1-amd64      | 5         | 0.7%    |
| 5.10.0-3parrot1-amd64     | 5         | 0.7%    |
| 5.8.0-1parrot1-amd64      | 4         | 0.56%   |
| 5.10.0-5parrot1-amd64     | 4         | 0.56%   |
| 5.4.0-3parrot1-amd64      | 3         | 0.42%   |
| 5.3.0-3parrot3-amd64      | 3         | 0.42%   |
| 5.2.0-2parrot1-amd64      | 3         | 0.42%   |
| 4.19.0-parrot4-28t-amd64  | 3         | 0.42%   |
| 6.0.5-x64v1-xanmod1       | 2         | 0.28%   |
| 5.10.92-v8+               | 2         | 0.28%   |
| 4.18.0-parrot10-amd64     | 2         | 0.28%   |
| 6.6.13+bpo-amd64          | 1         | 0.14%   |
| 6.5.0-kali3-amd64         | 1         | 0.14%   |
| 6.5.0-13parrot1-arm64     | 1         | 0.14%   |
| 6.11.5+bpo-amd64          | 1         | 0.14%   |
| 6.11+parrot-amd64         | 1         | 0.14%   |
| 6.1.27chrultrabook-fixups | 1         | 0.14%   |
| 6.1.0-0.deb11.5-amd64     | 1         | 0.14%   |
| 5.7.0-rc6-galliumos       | 1         | 0.14%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1.0   | 120       | 16.95%  |
| 6.0.0   | 79        | 11.16%  |
| 6.5.0   | 70        | 9.89%   |
| 5.10.0  | 64        | 9.04%   |
| 5.14.0  | 63        | 8.9%    |
| 5.16.0  | 57        | 8.05%   |
| 5.18.0  | 51        | 7.2%    |
| 5.7.0   | 34        | 4.8%    |
| 6.10.11 | 31        | 4.38%   |
| 5.4.0   | 26        | 3.67%   |
| 5.5.0   | 25        | 3.53%   |
| 6.9.7   | 22        | 3.11%   |
| 5.15.0  | 12        | 1.69%   |
| 5.8.0   | 10        | 1.41%   |
| 5.6.0   | 10        | 1.41%   |
| 5.9.0   | 9         | 1.27%   |
| 5.3.0   | 5         | 0.71%   |
| 4.19.0  | 4         | 0.56%   |
| 5.2.0   | 3         | 0.42%   |
| 6.0.5   | 2         | 0.28%   |
| 5.10.92 | 2         | 0.28%   |
| 4.18.0  | 2         | 0.28%   |
| 6.6.13  | 1         | 0.14%   |
| 6.11.5  | 1         | 0.14%   |
| 6.11    | 1         | 0.14%   |
| 6.1.27  | 1         | 0.14%   |
| 5.1.0   | 1         | 0.14%   |
| 4.14.0  | 1         | 0.14%   |
| Unknown | 1         | 0.14%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1     | 121       | 17.09%  |
| 6.0     | 81        | 11.44%  |
| 6.5     | 70        | 9.89%   |
| 5.10    | 66        | 9.32%   |
| 5.14    | 63        | 8.9%    |
| 5.16    | 57        | 8.05%   |
| 5.18    | 51        | 7.2%    |
| 5.7     | 34        | 4.8%    |
| 6.10    | 31        | 4.38%   |
| 5.4     | 26        | 3.67%   |
| 5.5     | 25        | 3.53%   |
| 6.9     | 22        | 3.11%   |
| 5.15    | 12        | 1.69%   |
| 5.8     | 10        | 1.41%   |
| 5.6     | 10        | 1.41%   |
| 5.9     | 9         | 1.27%   |
| 5.3     | 5         | 0.71%   |
| 4.19    | 4         | 0.56%   |
| 5.2     | 3         | 0.42%   |
| 4.18    | 2         | 0.28%   |
| 6.6     | 1         | 0.14%   |
| 6.11    | 1         | 0.14%   |
| 6       | 1         | 0.14%   |
| 5.1     | 1         | 0.14%   |
| 4.14    | 1         | 0.14%   |
| Unknown | 1         | 0.14%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 663       | 99.25%  |
| aarch64 | 3         | 0.45%   |
| i686    | 2         | 0.3%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| MATE            | 517       | 75.81%  |
| KDE5            | 92        | 13.49%  |
| Unknown         | 22        | 3.23%   |
| KDE             | 20        | 2.93%   |
| XFCE            | 15        | 2.2%    |
| GNOME           | 8         | 1.17%   |
| X-Cinnamon      | 3         | 0.44%   |
| LXDE            | 1         | 0.15%   |
| GNOME Flashback | 1         | 0.15%   |
| GNOME Classic   | 1         | 0.15%   |
| Cinnamon        | 1         | 0.15%   |
| bspwm           | 1         | 0.15%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 650       | 97.31%  |
| Wayland | 12        | 1.8%    |
| Tty     | 4         | 0.6%    |
| Unknown | 2         | 0.3%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 373       | 54.61%  |
| Unknown | 207       | 30.31%  |
| TDM     | 71        | 10.4%   |
| SDDM    | 21        | 3.07%   |
| GDM     | 10        | 1.46%   |
| GDM3    | 1         | 0.15%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 371       | 55.29%  |
| en_GB   | 39        | 5.81%   |
| fr_FR   | 30        | 4.47%   |
| es_ES   | 21        | 3.13%   |
| ru_RU   | 19        | 2.83%   |
| de_DE   | 19        | 2.83%   |
| en_IN   | 16        | 2.38%   |
| pt_BR   | 15        | 2.24%   |
| it_IT   | 15        | 2.24%   |
| en_AU   | 15        | 2.24%   |
| Unknown | 15        | 2.24%   |
| pl_PL   | 13        | 1.94%   |
| es_MX   | 11        | 1.64%   |
| en_CA   | 7         | 1.04%   |
| cs_CZ   | 6         | 0.89%   |
| es_CO   | 4         | 0.6%    |
| en_ZA   | 4         | 0.6%    |
| tr_TR   | 3         | 0.45%   |
| es_PE   | 3         | 0.45%   |
| es_AR   | 3         | 0.45%   |
| en_IE   | 3         | 0.45%   |
| C       | 3         | 0.45%   |
| ja_JP   | 2         | 0.3%    |
| id_ID   | 2         | 0.3%    |
| es_US   | 2         | 0.3%    |
| es_CL   | 2         | 0.3%    |
| en_NZ   | 2         | 0.3%    |
| en_NG   | 2         | 0.3%    |
| en_HK   | 2         | 0.3%    |
| en_DK   | 2         | 0.3%    |
| sk_SK   | 1         | 0.15%   |
| ru_UA   | 1         | 0.15%   |
| pt_PT   | 1         | 0.15%   |
| nl_NL   | 1         | 0.15%   |
| nl_BE   | 1         | 0.15%   |
| nb_NO   | 1         | 0.15%   |
| mk_MK   | 1         | 0.15%   |
| lt_LT   | 1         | 0.15%   |
| hr_HR   | 1         | 0.15%   |
| fr_CH   | 1         | 0.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 376       | 55.38%  |
| EFI  | 303       | 44.62%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 516       | 76.44%  |
| Ext4    | 84        | 12.44%  |
| Tmpfs   | 29        | 4.3%    |
| Overlay | 25        | 3.7%    |
| Xfs     | 14        | 2.07%   |
| Unknown | 7         | 1.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 331       | 48.53%  |
| Unknown | 240       | 35.19%  |
| MBR     | 111       | 16.28%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 584       | 86.52%  |
| Yes       | 91        | 13.48%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 436       | 64.69%  |
| Yes       | 238       | 35.31%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo                               | 118       | 17.66%  |
| Hewlett-Packard                      | 117       | 17.51%  |
| ASUSTek Computer                     | 98        | 14.67%  |
| Dell                                 | 85        | 12.72%  |
| MSI                                  | 41        | 6.14%   |
| Acer                                 | 41        | 6.14%   |
| Gigabyte Technology                  | 24        | 3.59%   |
| Apple                                | 22        | 3.29%   |
| Toshiba                              | 12        | 1.8%    |
| Samsung Electronics                  | 9         | 1.35%   |
| ASRock                               | 7         | 1.05%   |
| Unknown                              | 7         | 1.05%   |
| HUAWEI                               | 6         | 0.9%    |
| Google                               | 5         | 0.75%   |
| Foxconn                              | 5         | 0.75%   |
| Alienware                            | 5         | 0.75%   |
| Microsoft                            | 4         | 0.6%    |
| Gateway                              | 4         | 0.6%    |
| Fujitsu                              | 4         | 0.6%    |
| Sony                                 | 3         | 0.45%   |
| Razer                                | 3         | 0.45%   |
| Panasonic                            | 3         | 0.45%   |
| Biostar                              | 3         | 0.45%   |
| Raspberry Pi Foundation              | 2         | 0.3%    |
| Quanta                               | 2         | 0.3%    |
| Positivo                             | 2         | 0.3%    |
| Pegatron                             | 2         | 0.3%    |
| Notebook                             | 2         | 0.3%    |
| Intel                                | 2         | 0.3%    |
| ECS                                  | 2         | 0.3%    |
| ZOTAC                                | 1         | 0.15%   |
| Wortmann AG                          | 1         | 0.15%   |
| Wistron                              | 1         | 0.15%   |
| Toxic                                | 1         | 0.15%   |
| Timi                                 | 1         | 0.15%   |
| System76                             | 1         | 0.15%   |
| Standard                             | 1         | 0.15%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.15%   |
| Radxa                                | 1         | 0.15%   |
| Positivo Bahia - VAIO                | 1         | 0.15%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown                              | 10        | 1.5%    |
| HP Laptop 15-dy2xxx                  | 5         | 0.75%   |
| HP Notebook                          | 4         | 0.6%    |
| MSI Modern 15 A5M                    | 3         | 0.45%   |
| Lenovo IdeaPad 3 15IIL05 81WE        | 3         | 0.45%   |
| HP ProDesk 600 G1 SFF                | 3         | 0.45%   |
| HP Pavilion 15                       | 3         | 0.45%   |
| HP ENVY x360 Convertible 13-bd0xxx   | 3         | 0.45%   |
| HP EliteBook 8470p                   | 3         | 0.45%   |
| HP 250 G7 Notebook PC                | 3         | 0.45%   |
| Dell OptiPlex 3020                   | 3         | 0.45%   |
| Dell Latitude E6420                  | 3         | 0.45%   |
| Dell Inspiron MM061                  | 3         | 0.45%   |
| ASUS M5A78L-M/USB3                   | 3         | 0.45%   |
| Apple MacBookAir7,2                  | 3         | 0.45%   |
| Toshiba Satellite L775D              | 2         | 0.3%    |
| RPi Raspberry Pi 4 Model B Rev 1.5   | 2         | 0.3%    |
| Quanta TW9/SW9                       | 2         | 0.3%    |
| MSI Katana GF66 12UC                 | 2         | 0.3%    |
| MSI Katana GF66 11UE                 | 2         | 0.3%    |
| Microsoft Surface Pro 3              | 2         | 0.3%    |
| Lenovo ThinkPad E15 Gen 3 20YG0041MX | 2         | 0.3%    |
| Lenovo Legion Pro 5 16IRX8 82WK      | 2         | 0.3%    |
| Lenovo E41-25 81FS                   | 2         | 0.3%    |
| HUAWEI HVY-WXX9                      | 2         | 0.3%    |
| HP ProBook 650 G1                    | 2         | 0.3%    |
| HP Pavilion g6                       | 2         | 0.3%    |
| HP Pavilion dv6                      | 2         | 0.3%    |
| HP Pavilion dv4                      | 2         | 0.3%    |
| HP Laptop 17-cn0xxx                  | 2         | 0.3%    |
| HP ENVY x360 2-in-1 Laptop 15-ew0xxx | 2         | 0.3%    |
| HP EliteBook Folio 9480m             | 2         | 0.3%    |
| HP EliteBook 830 G6                  | 2         | 0.3%    |
| HP Compaq 8200 Elite SFF PC          | 2         | 0.3%    |
| Gigabyte AX370-Gaming                | 2         | 0.3%    |
| Foxconn s5710t                       | 2         | 0.3%    |
| Dell XPS 13 9350                     | 2         | 0.3%    |
| Dell OptiPlex 7010                   | 2         | 0.3%    |
| Dell Latitude E7440                  | 2         | 0.3%    |
| Dell Latitude E6410                  | 2         | 0.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 60        | 8.98%   |
| Dell Latitude      | 29        | 4.34%   |
| Lenovo IdeaPad     | 26        | 3.89%   |
| Dell Inspiron      | 26        | 3.89%   |
| Acer Aspire        | 21        | 3.14%   |
| HP Pavilion        | 20        | 2.99%   |
| HP Laptop          | 19        | 2.84%   |
| HP EliteBook       | 18        | 2.69%   |
| HP ProBook         | 11        | 1.65%   |
| HP ENVY            | 11        | 1.65%   |
| Toshiba Satellite  | 10        | 1.5%    |
| Dell OptiPlex      | 10        | 1.5%    |
| ASUS VivoBook      | 10        | 1.5%    |
| ASUS ROG           | 10        | 1.5%    |
| ASUS PRIME         | 10        | 1.5%    |
| Unknown            | 10        | 1.5%    |
| HP Compaq          | 9         | 1.35%   |
| Dell XPS           | 8         | 1.2%    |
| ASUS ASUS          | 8         | 1.2%    |
| Acer Nitro         | 8         | 1.2%    |
| MSI Katana         | 7         | 1.05%   |
| Lenovo Legion      | 6         | 0.9%    |
| HP Victus          | 5         | 0.75%   |
| Microsoft Surface  | 4         | 0.6%    |
| Lenovo Yoga        | 4         | 0.6%    |
| HP ZBook           | 4         | 0.6%    |
| HP ProDesk         | 4         | 0.6%    |
| HP Notebook        | 4         | 0.6%    |
| HP 250             | 4         | 0.6%    |
| Dell Vostro        | 4         | 0.6%    |
| Dell Precision     | 4         | 0.6%    |
| ASUS Zenbook       | 4         | 0.6%    |
| Acer Predator      | 4         | 0.6%    |
| Razer Blade        | 3         | 0.45%   |
| MSI Modern         | 3         | 0.45%   |
| Lenovo IdeaPadFlex | 3         | 0.45%   |
| Fujitsu LIFEBOOK   | 3         | 0.45%   |
| ASUS TUF           | 3         | 0.45%   |
| ASUS M5A78L-M      | 3         | 0.45%   |
| Apple MacBookPro11 | 3         | 0.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 74        | 11.08%  |
| 2019    | 64        | 9.58%   |
| 2020    | 57        | 8.53%   |
| 2011    | 56        | 8.38%   |
| 2012    | 50        | 7.49%   |
| 2018    | 49        | 7.34%   |
| 2022    | 47        | 7.04%   |
| 2013    | 43        | 6.44%   |
| 2017    | 41        | 6.14%   |
| 2016    | 39        | 5.84%   |
| 2014    | 31        | 4.64%   |
| 2015    | 26        | 3.89%   |
| 2010    | 22        | 3.29%   |
| 2023    | 20        | 2.99%   |
| 2008    | 15        | 2.25%   |
| 2007    | 13        | 1.95%   |
| 2009    | 11        | 1.65%   |
| 2024    | 4         | 0.6%    |
| 2006    | 4         | 0.6%    |
| Unknown | 2         | 0.3%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 467       | 69.91%  |
| Desktop        | 157       | 23.5%   |
| Convertible    | 22        | 3.29%   |
| Tablet         | 6         | 0.9%    |
| Mini pc        | 6         | 0.9%    |
| All in one     | 6         | 0.9%    |
| System on chip | 4         | 0.6%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 668       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 663       | 99.25%  |
| Yes  | 5         | 0.75%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 171       | 25.3%   |
| 16.01-24.0  | 160       | 23.67%  |
| 8.01-16.0   | 137       | 20.27%  |
| 3.01-4.0    | 96        | 14.2%   |
| 32.01-64.0  | 66        | 9.76%   |
| 64.01-256.0 | 18        | 2.66%   |
| 1.01-2.0    | 14        | 2.07%   |
| 24.01-32.0  | 11        | 1.63%   |
| 2.01-3.0    | 3         | 0.44%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 240       | 33.76%  |
| 1.01-2.0   | 209       | 29.4%   |
| 4.01-8.0   | 109       | 15.33%  |
| 3.01-4.0   | 106       | 14.91%  |
| 0.51-1.0   | 25        | 3.52%   |
| 8.01-16.0  | 16        | 2.25%   |
| 0.01-0.5   | 3         | 0.42%   |
| 32.01-64.0 | 1         | 0.14%   |
| 24.01-32.0 | 1         | 0.14%   |
| 16.01-24.0 | 1         | 0.14%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 433       | 63.4%   |
| 2      | 184       | 26.94%  |
| 3      | 37        | 5.42%   |
| 4      | 16        | 2.34%   |
| 5      | 6         | 0.88%   |
| 0      | 4         | 0.59%   |
| 6      | 3         | 0.44%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 498       | 74%     |
| Yes       | 175       | 26%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 550       | 81.97%  |
| No        | 121       | 18.03%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 603       | 89.87%  |
| No        | 68        | 10.13%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 479       | 70.96%  |
| No        | 196       | 29.04%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 216       | 32%     |
| Germany      | 39        | 5.78%   |
| France       | 27        | 4%      |
| Spain        | 24        | 3.56%   |
| UK           | 22        | 3.26%   |
| Italy        | 22        | 3.26%   |
| Russia       | 21        | 3.11%   |
| Brazil       | 21        | 3.11%   |
| Netherlands  | 20        | 2.96%   |
| India        | 20        | 2.96%   |
| Mexico       | 18        | 2.67%   |
| Canada       | 17        | 2.52%   |
| Australia    | 13        | 1.93%   |
| Sweden       | 9         | 1.33%   |
| Poland       | 9         | 1.33%   |
| Kenya        | 9         | 1.33%   |
| Czechia      | 8         | 1.19%   |
| Indonesia    | 7         | 1.04%   |
| Peru         | 6         | 0.89%   |
| Egypt        | 6         | 0.89%   |
| Algeria      | 6         | 0.89%   |
| Turkey       | 5         | 0.74%   |
| South Africa | 5         | 0.74%   |
| Denmark      | 5         | 0.74%   |
| Bangladesh   | 5         | 0.74%   |
| Switzerland  | 4         | 0.59%   |
| Portugal     | 4         | 0.59%   |
| Japan        | 4         | 0.59%   |
| Finland      | 4         | 0.59%   |
| Colombia     | 4         | 0.59%   |
| Austria      | 4         | 0.59%   |
| Argentina    | 4         | 0.59%   |
| UAE          | 3         | 0.44%   |
| Pakistan     | 3         | 0.44%   |
| Nepal        | 3         | 0.44%   |
| Namibia      | 3         | 0.44%   |
| Mongolia     | 3         | 0.44%   |
| Ireland      | 3         | 0.44%   |
| Iraq         | 3         | 0.44%   |
| Greece       | 3         | 0.44%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Amsterdam         | 10        | 1.42%   |
| Nairobi           | 8         | 1.14%   |
| Los Angeles       | 8         | 1.14%   |
| Rome              | 7         | 0.99%   |
| Seattle           | 6         | 0.85%   |
| Moscow            | 6         | 0.85%   |
| Houston           | 6         | 0.85%   |
| Dallas            | 6         | 0.85%   |
| Atlanta           | 6         | 0.85%   |
| San Antonio       | 5         | 0.71%   |
| Saint Paul        | 5         | 0.71%   |
| Melbourne         | 5         | 0.71%   |
| Lima              | 5         | 0.71%   |
| Indianapolis      | 5         | 0.71%   |
| Dublin            | 5         | 0.71%   |
| Berlin            | 5         | 0.71%   |
| Barcelona         | 5         | 0.71%   |
| Sydney            | 4         | 0.57%   |
| Prague            | 4         | 0.57%   |
| Paris             | 4         | 0.57%   |
| New York          | 4         | 0.57%   |
| Minneapolis       | 4         | 0.57%   |
| Madrid            | 4         | 0.57%   |
| Lyon              | 4         | 0.57%   |
| London            | 4         | 0.57%   |
| Dhaka             | 4         | 0.57%   |
| Chicago           | 4         | 0.57%   |
| Alexandria        | 4         | 0.57%   |
| Warsaw            | 3         | 0.43%   |
| Vienna            | 3         | 0.43%   |
| Ulan Bator        | 3         | 0.43%   |
| Toronto           | 3         | 0.43%   |
| Stockholm         | 3         | 0.43%   |
| San José         | 3         | 0.43%   |
| Phoenix           | 3         | 0.43%   |
| Pensacola         | 3         | 0.43%   |
| Helsinki          | 3         | 0.43%   |
| Frankfurt am Main | 3         | 0.43%   |
| Eugene            | 3         | 0.43%   |
| Chennai           | 3         | 0.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 146       | 192    | 15.84%  |
| WDC                         | 125       | 159    | 13.56%  |
| Seagate                     | 104       | 136    | 11.28%  |
| Toshiba                     | 90        | 101    | 9.76%   |
| Kingston                    | 49        | 53     | 5.31%   |
| Unknown                     | 48        | 51     | 5.21%   |
| SanDisk                     | 48        | 59     | 5.21%   |
| SK hynix                    | 37        | 44     | 4.01%   |
| Hitachi                     | 30        | 37     | 3.25%   |
| Crucial                     | 26        | 32     | 2.82%   |
| Micron Technology           | 24        | 24     | 2.6%    |
| Intel                       | 20        | 39     | 2.17%   |
| HGST                        | 18        | 21     | 1.95%   |
| A-DATA Technology           | 15        | 15     | 1.63%   |
| Apple                       | 12        | 12     | 1.3%    |
| China                       | 10        | 13     | 1.08%   |
| KIOXIA                      | 9         | 10     | 0.98%   |
| Team                        | 8         | 10     | 0.87%   |
| SPCC                        | 5         | 5      | 0.54%   |
| Silicon Motion              | 5         | 5      | 0.54%   |
| Phison                      | 5         | 5      | 0.54%   |
| PNY                         | 4         | 4      | 0.43%   |
| LITEON                      | 4         | 4      | 0.43%   |
| YMTC                        | 3         | 3      | 0.33%   |
| LITEONIT                    | 3         | 3      | 0.33%   |
| Kingston Technology Company | 3         | 4      | 0.33%   |
| KingFast                    | 3         | 4      | 0.33%   |
| JMicron Technology          | 3         | 3      | 0.33%   |
| Intenso                     | 3         | 4      | 0.33%   |
| Fujitsu                     | 3         | 3      | 0.33%   |
| Corsair                     | 3         | 4      | 0.33%   |
| Unknown                     | 3         | 3      | 0.33%   |
| Netac                       | 2         | 2      | 0.22%   |
| Lexar                       | 2         | 2      | 0.22%   |
| HUAWEI                      | 2         | 2      | 0.22%   |
| GOODRAM                     | 2         | 2      | 0.22%   |
| Fanxiang                    | 2         | 2      | 0.22%   |
| BR                          | 2         | 2      | 0.22%   |
| Apacer                      | 2         | 3      | 0.22%   |
| ADATA Technology            | 2         | 3      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Toshiba MQ04ABF100 1TB                              | 13        | 1.29%   |
| Samsung SSD 860 EVO 500GB                           | 11        | 1.09%   |
| Toshiba MQ01ABF050 500GB                            | 9         | 0.89%   |
| Kingston SA400S37240G 240GB SSD                     | 8         | 0.79%   |
| Unknown SD/MMC/MS PRO 128GB                         | 7         | 0.7%    |
| Toshiba MQ01ABD100 1TB                              | 7         | 0.7%    |
| Toshiba DT01ACA200 2TB                              | 6         | 0.6%    |
| Toshiba DT01ACA100 1TB                              | 6         | 0.6%    |
| Seagate ST2000LM003 HN-M201RAD 2TB                  | 6         | 0.6%    |
| SanDisk NVMe SSD Drive 1TB                          | 6         | 0.6%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 6         | 0.6%    |
| Unknown MMC Card  64GB                              | 5         | 0.5%    |
| Unknown MMC Card  32GB                              | 5         | 0.5%    |
| Toshiba MQ01ABD075 752GB                            | 5         | 0.5%    |
| Seagate ST31000528AS 1TB                            | 5         | 0.5%    |
| Seagate ST1000LM035-1RK172 1TB                      | 5         | 0.5%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 5         | 0.5%    |
| Seagate ST1000DM010-2EP102 1TB                      | 5         | 0.5%    |
| Seagate Expansion 1TB                               | 5         | 0.5%    |
| Samsung SSD 980 1TB                                 | 5         | 0.5%    |
| Samsung SSD 970 EVO Plus 1TB                        | 5         | 0.5%    |
| Samsung SSD 850 EVO 250GB                           | 5         | 0.5%    |
| Kingston SA400S37480G 480GB SSD                     | 5         | 0.5%    |
| Kingston NVMe SSD Drive 512GB                       | 5         | 0.5%    |
| Intel SSDPEKNU512GZ 512GB                           | 5         | 0.5%    |
| Intel HBRPEKNX0202AH 512GB                          | 5         | 0.5%    |
| HGST HTS721010A9E630 1TB                            | 5         | 0.5%    |
| HGST HTS541010A9E680 1TB                            | 5         | 0.5%    |
| Toshiba DT01ACA050 500GB                            | 4         | 0.4%    |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 4         | 0.4%    |
| Seagate ST320LT007-9ZV142 320GB                     | 4         | 0.4%    |
| Seagate ST2000DM008-2FR102 2TB                      | 4         | 0.4%    |
| SanDisk SSD PLUS 1000GB                             | 4         | 0.4%    |
| SanDisk NVMe SSD Drive 256GB                        | 4         | 0.4%    |
| Samsung SSD 980 PRO 1TB                             | 4         | 0.4%    |
| Kingston OM8PCP3512F-AB 512GB                       | 4         | 0.4%    |
| Intel HBRPEKNX0202AHO 32GB                          | 4         | 0.4%    |
| Crucial CT500MX500SSD1 500GB                        | 4         | 0.4%    |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 3         | 0.3%    |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 3         | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 101       | 133    | 29.88%  |
| WDC                 | 85        | 110    | 25.15%  |
| Toshiba             | 74        | 83     | 21.89%  |
| Hitachi             | 30        | 37     | 8.88%   |
| HGST                | 18        | 21     | 5.33%   |
| Samsung Electronics | 13        | 15     | 3.85%   |
| Unknown             | 7         | 8      | 2.07%   |
| JMicron Technology  | 3         | 3      | 0.89%   |
| Apple               | 2         | 2      | 0.59%   |
| TO Exter            | 1         | 1      | 0.3%    |
| Fujitsu             | 1         | 1      | 0.3%    |
| CLOVER              | 1         | 1      | 0.3%    |
| ASMT                | 1         | 1      | 0.3%    |
| ASMedia             | 1         | 1      | 0.3%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 51        | 72     | 20.08%  |
| Kingston            | 29        | 32     | 11.42%  |
| SanDisk             | 22        | 25     | 8.66%   |
| WDC                 | 21        | 23     | 8.27%   |
| Crucial             | 20        | 25     | 7.87%   |
| China               | 10        | 13     | 3.94%   |
| Apple               | 8         | 8      | 3.15%   |
| A-DATA Technology   | 6         | 6      | 2.36%   |
| Toshiba             | 5         | 6      | 1.97%   |
| Team                | 5         | 7      | 1.97%   |
| Micron Technology   | 5         | 5      | 1.97%   |
| SK hynix            | 4         | 4      | 1.57%   |
| PNY                 | 4         | 4      | 1.57%   |
| LITEON              | 4         | 4      | 1.57%   |
| SPCC                | 3         | 3      | 1.18%   |
| Seagate             | 3         | 3      | 1.18%   |
| LITEONIT            | 3         | 3      | 1.18%   |
| KingFast            | 3         | 3      | 1.18%   |
| Intenso             | 3         | 4      | 1.18%   |
| Unknown             | 2         | 2      | 0.79%   |
| Intel               | 2         | 2      | 0.79%   |
| GOODRAM             | 2         | 2      | 0.79%   |
| Fujitsu             | 2         | 2      | 0.79%   |
| Fanxiang            | 2         | 2      | 0.79%   |
| Corsair             | 2         | 3      | 0.79%   |
| BR                  | 2         | 2      | 0.79%   |
| Apacer              | 2         | 3      | 0.79%   |
| Unknown             | 2         | 2      | 0.79%   |
| Zheino              | 1         | 1      | 0.39%   |
| Wdxsky              | 1         | 1      | 0.39%   |
| WALRAM              | 1         | 1      | 0.39%   |
| W800SH              | 1         | 1      | 0.39%   |
| TSA 256G            | 1         | 1      | 0.39%   |
| Transcend           | 1         | 1      | 0.39%   |
| Teclast             | 1         | 1      | 0.39%   |
| SCY                 | 1         | 1      | 0.39%   |
| S3+                 | 1         | 1      | 0.39%   |
| RZX                 | 1         | 1      | 0.39%   |
| Rogueware           | 1         | 1      | 0.39%   |
| PNY USB             | 1         | 1      | 0.39%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 287       | 417    | 34.58%  |
| NVMe    | 270       | 356    | 32.53%  |
| SSD     | 230       | 298    | 27.71%  |
| MMC     | 37        | 42     | 4.46%   |
| Unknown | 6         | 6      | 0.72%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 427       | 676    | 55.03%  |
| NVMe | 270       | 355    | 34.79%  |
| SAS  | 42        | 46     | 5.41%   |
| MMC  | 37        | 42     | 4.77%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 303       | 431    | 56.95%  |
| 0.51-1.0   | 173       | 215    | 32.52%  |
| 1.01-2.0   | 41        | 49     | 7.71%   |
| 3.01-4.0   | 8         | 10     | 1.5%    |
| 2.01-3.0   | 5         | 7      | 0.94%   |
| 10.01-20.0 | 1         | 2      | 0.19%   |
| 4.01-10.0  | 1         | 1      | 0.19%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 164       | 23.8%   |
| 501-1000       | 132       | 19.16%  |
| 101-250        | 130       | 18.87%  |
| 1001-2000      | 80        | 11.61%  |
| Unknown        | 66        | 9.58%   |
| 51-100         | 39        | 5.66%   |
| More than 3000 | 23        | 3.34%   |
| 21-50          | 23        | 3.34%   |
| 1-20           | 20        | 2.9%    |
| 2001-3000      | 12        | 1.74%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 213       | 30.34%  |
| 51-100         | 131       | 18.66%  |
| 1-20           | 99        | 14.1%   |
| 101-250        | 96        | 13.68%  |
| Unknown        | 66        | 9.4%    |
| 251-500        | 56        | 7.98%   |
| 501-1000       | 22        | 3.13%   |
| 1001-2000      | 13        | 1.85%   |
| More than 3000 | 3         | 0.43%   |
| 0              | 2         | 0.28%   |
| 2001-3000      | 1         | 0.14%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Samsung Electronics HM500JI 500GB    | 3         | 3      | 3.41%   |
| Toshiba MQ01ABD100 1TB               | 2         | 2      | 2.27%   |
| Seagate ST1000DM010-2EP102 1TB       | 2         | 2      | 2.27%   |
| SanDisk SD6SF1M128G1022I 128GB SSD   | 2         | 3      | 2.27%   |
| LITEON CV8-8E128-HP 128GB SSD        | 2         | 2      | 2.27%   |
| WDC WD5000AAKS-75V0A0 500GB          | 1         | 1      | 1.14%   |
| WDC WD5000AADS-00S9B0 500GB          | 1         | 1      | 1.14%   |
| WDC WD3200BPVT-00JJ5T0 320GB         | 1         | 1      | 1.14%   |
| WDC WD3200BEKT-75PVMT1 320GB         | 1         | 1      | 1.14%   |
| WDC WD3200AVJS-63B6A0 320GB          | 1         | 1      | 1.14%   |
| WDC WD2500BEVT-22A23T0 250GB         | 1         | 1      | 1.14%   |
| WDC WD2003FZEX-00Z4SA0 2TB           | 1         | 1      | 1.14%   |
| WDC WD10JUCX-63WPNY0 1TB             | 1         | 1      | 1.14%   |
| WDC WD10EZRX-00L4HB0 1TB             | 1         | 1      | 1.14%   |
| WDC WD10EADS-22M2B0 1TB              | 1         | 1      | 1.14%   |
| Toshiba MQ01ABD075 752GB             | 1         | 1      | 1.14%   |
| Toshiba MK6475GSX 640GB              | 1         | 1      | 1.14%   |
| Toshiba MK5059GSXP 500GB             | 1         | 1      | 1.14%   |
| Toshiba MK3265GSXF 320GB             | 1         | 1      | 1.14%   |
| Toshiba MK3261GSYN 320GB             | 1         | 1      | 1.14%   |
| Toshiba HDWD110 1TB                  | 1         | 1      | 1.14%   |
| Toshiba DT01ACA050 500GB             | 1         | 1      | 1.14%   |
| SPCC M.2 PCIe SSD 256GB              | 1         | 1      | 1.14%   |
| SK hynix PC711 HFS256GDE9X073N 256GB | 1         | 1      | 1.14%   |
| SK hynix BC711 HFM512GD3JX013N 512GB | 1         | 1      | 1.14%   |
| Seagate ST9500325AS 500GB            | 1         | 1      | 1.14%   |
| Seagate ST940210AS 40GB              | 1         | 1      | 1.14%   |
| Seagate ST9250410AS 250GB            | 1         | 1      | 1.14%   |
| Seagate ST500NM0011 500GB            | 1         | 1      | 1.14%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 1         | 1      | 1.14%   |
| Seagate ST380215AS 80GB              | 1         | 1      | 1.14%   |
| Seagate ST3802110A 80GB              | 1         | 1      | 1.14%   |
| Seagate ST3500413AS 500GB            | 1         | 1      | 1.14%   |
| Seagate ST3320418AS 320GB            | 1         | 1      | 1.14%   |
| Seagate ST3250824AS 250GB            | 1         | 1      | 1.14%   |
| Seagate ST320LT007-9ZV142 320GB      | 1         | 1      | 1.14%   |
| Seagate ST320LM001 HN-M320MBB 320GB  | 1         | 1      | 1.14%   |
| Seagate ST3160215AS 160GB            | 1         | 1      | 1.14%   |
| Seagate ST31000528AS 1TB             | 1         | 1      | 1.14%   |
| Seagate ST250DM000-1BD141 250GB      | 1         | 1      | 1.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 21     | 20%     |
| WDC                 | 10        | 10     | 11.76%  |
| Toshiba             | 9         | 9      | 10.59%  |
| Samsung Electronics | 9         | 10     | 10.59%  |
| SanDisk             | 8         | 9      | 9.41%   |
| Hitachi             | 8         | 9      | 9.41%   |
| HGST                | 4         | 4      | 4.71%   |
| A-DATA Technology   | 3         | 3      | 3.53%   |
| SK hynix            | 2         | 2      | 2.35%   |
| LITEON              | 2         | 2      | 2.35%   |
| Kingston            | 2         | 3      | 2.35%   |
| SPCC                | 1         | 1      | 1.18%   |
| Plextor             | 1         | 1      | 1.18%   |
| Micron Technology   | 1         | 1      | 1.18%   |
| Intenso             | 1         | 1      | 1.18%   |
| Intel               | 1         | 1      | 1.18%   |
| Hewlett-Packard     | 1         | 1      | 1.18%   |
| Fujitsu             | 1         | 1      | 1.18%   |
| Crucial             | 1         | 1      | 1.18%   |
| CLOVER              | 1         | 1      | 1.18%   |
| China               | 1         | 1      | 1.18%   |
| Unknown             | 1         | 1      | 1.18%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 21     | 29.82%  |
| WDC                 | 10        | 10     | 17.54%  |
| Toshiba             | 9         | 9      | 15.79%  |
| Hitachi             | 8         | 9      | 14.04%  |
| Samsung Electronics | 7         | 7      | 12.28%  |
| HGST                | 4         | 4      | 7.02%   |
| Fujitsu             | 1         | 1      | 1.75%   |
| CLOVER              | 1         | 1      | 1.75%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 51        | 62     | 64.56%  |
| SSD  | 22        | 25     | 27.85%  |
| NVMe | 6         | 6      | 7.59%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                       | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC WD5000AADS-00S9B0 500GB | 1         | 1      | 33.33%  |
| Toshiba MK2565GSXN 250GB    | 1         | 1      | 33.33%  |
| Intenso SSD SATAIII 512GB   | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 33.33%  |
| Toshiba | 1         | 1      | 33.33%  |
| Intenso | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 351       | 483    | 46.43%  |
| Detected | 328       | 540    | 43.39%  |
| Malfunc  | 74        | 93     | 9.79%   |
| Failed   | 3         | 3      | 0.4%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 438       | 52.21%  |
| AMD                            | 101       | 12.04%  |
| Samsung Electronics            | 92        | 10.97%  |
| SanDisk                        | 46        | 5.48%   |
| SK hynix                       | 33        | 3.93%   |
| Kingston Technology Company    | 23        | 2.74%   |
| Micron Technology              | 19        | 2.26%   |
| Toshiba America Info Systems   | 10        | 1.19%   |
| KIOXIA                         | 10        | 1.19%   |
| ADATA Technology               | 9         | 1.07%   |
| Silicon Motion                 | 8         | 0.95%   |
| Nvidia                         | 8         | 0.95%   |
| Phison Electronics             | 7         | 0.83%   |
| Micron/Crucial Technology      | 7         | 0.83%   |
| ASMedia Technology             | 7         | 0.83%   |
| Realtek Semiconductor          | 4         | 0.48%   |
| JMicron Technology             | 4         | 0.48%   |
| Yangtze Memory Technologies    | 3         | 0.36%   |
| Solidigm                       | 2         | 0.24%   |
| Marvell Technology Group       | 2         | 0.24%   |
| VIA Technologies               | 1         | 0.12%   |
| Union Memory (Shenzhen)        | 1         | 0.12%   |
| Solid State Storage Technology | 1         | 0.12%   |
| Shenzhen Longsys Electronics   | 1         | 0.12%   |
| Netac Technology               | 1         | 0.12%   |
| Apple                          | 1         | 0.12%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                  | Computers | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 69        | 7.29%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 49        | 5.17%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 46        | 4.86%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 33        | 3.48%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 30        | 3.17%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 30        | 3.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 24        | 2.53%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                            | 22        | 2.32%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 18        | 1.9%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 17        | 1.8%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 17        | 1.8%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                   | 16        | 1.69%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 15        | 1.58%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 15        | 1.58%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)              | 14        | 1.48%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 14        | 1.48%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 13        | 1.37%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 11        | 1.16%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 11        | 1.16%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 11        | 1.16%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                | 9         | 0.95%   |
| Intel Alder Lake-P SATA AHCI Controller                                                | 9         | 0.95%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 9         | 0.95%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                      | 8         | 0.84%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                     | 8         | 0.84%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                             | 7         | 0.74%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                          | 7         | 0.74%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 7         | 0.74%   |
| Intel SSD 670p Series [Keystone Harbor]                                                | 7         | 0.74%   |
| Intel Optane NVME SSD H10 with Solid State Storage [Teton Glacier]                     | 7         | 0.74%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 7         | 0.74%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]           | 7         | 0.74%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 7         | 0.74%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 7         | 0.74%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 7         | 0.74%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller          | 7         | 0.74%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                          | 7         | 0.74%   |
| AMD 400 Series Chipset SATA Controller                                                 | 7         | 0.74%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                   | 6         | 0.63%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                            | 6         | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 431       | 50.53%  |
| NVMe | 269       | 31.54%  |
| RAID | 86        | 10.08%  |
| IDE  | 67        | 7.85%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 533       | 79.79%  |
| AMD    | 132       | 19.76%  |
| ARM    | 3         | 0.45%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 14        | 2.1%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 13        | 1.95%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 11        | 1.65%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 9         | 1.35%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 9         | 1.35%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 9         | 1.35%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 8         | 1.2%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 7         | 1.05%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 7         | 1.05%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 7         | 1.05%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 6         | 0.9%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 6         | 0.9%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 6         | 0.9%    |
| Intel 11th Gen Core i5-11400H @ 2.70GHz       | 6         | 0.9%    |
| Intel Core i7-6500U CPU @ 2.50GHz             | 5         | 0.75%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 5         | 0.75%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 5         | 0.75%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 5         | 0.75%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 5         | 0.75%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 5         | 0.75%   |
| Intel 12th Gen Core i7-12700H                 | 5         | 0.75%   |
| Intel 12th Gen Core i7-1255U                  | 5         | 0.75%   |
| Intel 12th Gen Core i5-12500H                 | 5         | 0.75%   |
| Intel 12th Gen Core i5-1235U                  | 5         | 0.75%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 5         | 0.75%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 5         | 0.75%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 5         | 0.75%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 5         | 0.75%   |
| AMD FX-6300 Six-Core Processor                | 5         | 0.75%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 0.6%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 4         | 0.6%    |
| Intel Core i5-8365U CPU @ 1.60GHz             | 4         | 0.6%    |
| Intel Core i5-7400 CPU @ 3.00GHz              | 4         | 0.6%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 0.6%    |
| Intel Core i5-4690K CPU @ 3.50GHz             | 4         | 0.6%    |
| Intel Core i5-2430M CPU @ 2.40GHz             | 4         | 0.6%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 4         | 0.6%    |
| Intel Core i5-10300H CPU @ 2.50GHz            | 4         | 0.6%    |
| Intel 12th Gen Core i7-1260P                  | 4         | 0.6%    |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 4         | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 159       | 23.8%   |
| Intel Core i7           | 126       | 18.86%  |
| Other                   | 114       | 17.07%  |
| Intel Core i3           | 52        | 7.78%   |
| AMD Ryzen 7             | 31        | 4.64%   |
| AMD Ryzen 5             | 30        | 4.49%   |
| Intel Celeron           | 25        | 3.74%   |
| Intel Core 2 Duo        | 19        | 2.84%   |
| AMD FX                  | 12        | 1.8%    |
| AMD A6                  | 11        | 1.65%   |
| Intel Pentium           | 9         | 1.35%   |
| AMD Ryzen 3             | 8         | 1.2%    |
| Intel Pentium Dual-Core | 6         | 0.9%    |
| Intel Xeon              | 5         | 0.75%   |
| AMD Ryzen 9             | 5         | 0.75%   |
| AMD A4                  | 5         | 0.75%   |
| Intel Core i9           | 4         | 0.6%    |
| Intel Core 2            | 4         | 0.6%    |
| Intel Pentium Silver    | 3         | 0.45%   |
| Intel Core              | 3         | 0.45%   |
| Intel Atom              | 3         | 0.45%   |
| AMD Phenom II X4        | 3         | 0.45%   |
| AMD E1                  | 3         | 0.45%   |
| Intel Core 2 Quad       | 2         | 0.3%    |
| AMD Ryzen Threadripper  | 2         | 0.3%    |
| AMD Ryzen 5 PRO         | 2         | 0.3%    |
| AMD E                   | 2         | 0.3%    |
| AMD Athlon II X2        | 2         | 0.3%    |
| AMD A8                  | 2         | 0.3%    |
| AMD A10                 | 2         | 0.3%    |
| Intel Pentium Dual      | 1         | 0.15%   |
| Intel Genuine           | 1         | 0.15%   |
| Intel Core m5           | 1         | 0.15%   |
| Intel Core m3           | 1         | 0.15%   |
| Intel Core M            | 1         | 0.15%   |
| Intel Core 2 Extreme    | 1         | 0.15%   |
| AMD Sempron             | 1         | 0.15%   |
| AMD Phenom              | 1         | 0.15%   |
| AMD E2                  | 1         | 0.15%   |
| AMD C-50                | 1         | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 267       | 39.97%  |
| 4      | 223       | 33.38%  |
| 6      | 63        | 9.43%   |
| 8      | 42        | 6.29%   |
| 12     | 21        | 3.14%   |
| 10     | 20        | 2.99%   |
| 14     | 12        | 1.8%    |
| 1      | 8         | 1.2%    |
| 16     | 6         | 0.9%    |
| 3      | 4         | 0.6%    |
| 24     | 2         | 0.3%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 666       | 99.7%   |
| 2      | 2         | 0.3%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 471       | 70.4%   |
| 1      | 197       | 29.45%  |
| 8      | 1         | 0.15%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 663       | 99.25%  |
| Unknown        | 5         | 0.75%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 351       | 51.24%  |
| 0x206a7    | 29        | 4.23%   |
| 0x806c1    | 22        | 3.21%   |
| 0x306a9    | 21        | 3.07%   |
| 0x906a3    | 19        | 2.77%   |
| 0x806ec    | 17        | 2.48%   |
| 0x406e3    | 15        | 2.19%   |
| 0xa0652    | 11        | 1.61%   |
| 0x906ea    | 10        | 1.46%   |
| 0x906a4    | 10        | 1.46%   |
| 0x806e9    | 10        | 1.46%   |
| 0x806ea    | 9         | 1.31%   |
| 0x306c3    | 9         | 1.31%   |
| 0x906e9    | 8         | 1.17%   |
| 0x706a8    | 7         | 1.02%   |
| 0x40651    | 7         | 1.02%   |
| 0x1067a    | 7         | 1.02%   |
| 0x0a50000c | 7         | 1.02%   |
| 0x08108109 | 7         | 1.02%   |
| 0x806d1    | 6         | 0.88%   |
| 0x706e5    | 5         | 0.73%   |
| 0x08608103 | 5         | 0.73%   |
| 0x08600106 | 5         | 0.73%   |
| 0x06006705 | 5         | 0.73%   |
| 0x06000852 | 5         | 0.73%   |
| 0x6f6      | 4         | 0.58%   |
| 0x406c4    | 4         | 0.58%   |
| 0x306d4    | 4         | 0.58%   |
| 0x90672    | 3         | 0.44%   |
| 0x07030105 | 3         | 0.44%   |
| 0x03000027 | 3         | 0.44%   |
| 0x010000c8 | 3         | 0.44%   |
| 0xb06a2    | 2         | 0.29%   |
| 0xb0671    | 2         | 0.29%   |
| 0x906ed    | 2         | 0.29%   |
| 0x806eb    | 2         | 0.29%   |
| 0x806c2    | 2         | 0.29%   |
| 0x706a1    | 2         | 0.29%   |
| 0x6fd      | 2         | 0.29%   |
| 0x506c9    | 2         | 0.29%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KabyLake          | 111       | 16.62%  |
| SandyBridge       | 54        | 8.08%   |
| Haswell           | 50        | 7.49%   |
| Alderlake Hybrid  | 44        | 6.59%   |
| TigerLake         | 41        | 6.14%   |
| IvyBridge         | 41        | 6.14%   |
| Skylake           | 35        | 5.24%   |
| Unknown           | 35        | 5.24%   |
| Penryn            | 25        | 3.74%   |
| CometLake         | 20        | 2.99%   |
| Broadwell         | 20        | 2.99%   |
| Zen+              | 19        | 2.84%   |
| Zen 3             | 19        | 2.84%   |
| Icelake           | 19        | 2.84%   |
| Zen 2             | 17        | 2.54%   |
| Piledriver        | 16        | 2.4%    |
| Silvermont        | 13        | 1.95%   |
| Goldmont plus     | 13        | 1.95%   |
| Core              | 12        | 1.8%    |
| Excavator         | 11        | 1.65%   |
| Zen               | 9         | 1.35%   |
| Westmere          | 8         | 1.2%    |
| K10               | 8         | 1.2%    |
| Nehalem           | 4         | 0.6%    |
| K10 Llano         | 4         | 0.6%    |
| Jaguar            | 4         | 0.6%    |
| Puma              | 3         | 0.45%   |
| Meteorlake Hybrid | 3         | 0.45%   |
| Goldmont          | 3         | 0.45%   |
| Bobcat            | 3         | 0.45%   |
| K8 Hammer         | 2         | 0.3%    |
| Steamroller       | 1         | 0.15%   |
| K8 & K10 hybrid   | 1         | 0.15%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Intel            | 467       | 55.4%   |
| Nvidia           | 216       | 25.62%  |
| AMD              | 159       | 18.86%  |
| ATI Technologies | 1         | 0.12%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 43        | 5.04%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 34        | 3.99%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 31        | 3.63%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 23        | 2.7%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 23        | 2.7%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 22        | 2.58%   |
| Intel UHD Graphics 620                                                                   | 22        | 2.58%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 19        | 2.23%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 16        | 1.88%   |
| Intel HD Graphics 620                                                                    | 15        | 1.76%   |
| Intel HD Graphics 5500                                                                   | 15        | 1.76%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 15        | 1.76%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 15        | 1.76%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 12        | 1.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 11        | 1.29%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 11        | 1.29%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 11        | 1.29%   |
| AMD Lucienne                                                                             | 11        | 1.29%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 10        | 1.17%   |
| Intel HD Graphics 630                                                                    | 10        | 1.17%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 10        | 1.17%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 10        | 1.17%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 10        | 1.17%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 9         | 1.06%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 9         | 1.06%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 0.94%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 8         | 0.94%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 7         | 0.82%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 7         | 0.82%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 0.82%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 0.82%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 7         | 0.82%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 6         | 0.7%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 6         | 0.7%    |
| Nvidia GM108M [GeForce 940MX]                                                            | 6         | 0.7%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 6         | 0.7%    |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 6         | 0.7%    |
| Intel HD Graphics 530                                                                    | 6         | 0.7%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 0.7%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 5         | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 304       | 45.24%  |
| Intel + Nvidia | 126       | 18.75%  |
| 1 x AMD        | 117       | 17.41%  |
| 1 x Nvidia     | 75        | 11.16%  |
| Intel + AMD    | 21        | 3.13%   |
| AMD + Nvidia   | 17        | 2.53%   |
| 2 x AMD        | 5         | 0.74%   |
| Other          | 4         | 0.6%    |
| 2 x Intel      | 2         | 0.3%    |
| 2 x Nvidia     | 1         | 0.15%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 580       | 86.57%  |
| Proprietary | 72        | 10.75%  |
| Unknown     | 18        | 2.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 499       | 73.93%  |
| 1.01-2.0   | 40        | 5.93%   |
| 3.01-4.0   | 35        | 5.19%   |
| 0.01-0.5   | 33        | 4.89%   |
| 0.51-1.0   | 28        | 4.15%   |
| 7.01-8.0   | 18        | 2.67%   |
| 5.01-6.0   | 14        | 2.07%   |
| 8.01-16.0  | 4         | 0.59%   |
| 2.01-3.0   | 3         | 0.44%   |
| 16.01-24.0 | 1         | 0.15%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 108       | 14.73%  |
| BOE                     | 93        | 12.69%  |
| LG Display              | 85        | 11.6%   |
| Samsung Electronics     | 77        | 10.5%   |
| Chimei Innolux          | 77        | 10.5%   |
| Dell                    | 29        | 3.96%   |
| Sharp                   | 20        | 2.73%   |
| Apple                   | 20        | 2.73%   |
| Acer                    | 19        | 2.59%   |
| Hewlett-Packard         | 18        | 2.46%   |
| Goldstar                | 18        | 2.46%   |
| BenQ                    | 13        | 1.77%   |
| Chi Mei Optoelectronics | 12        | 1.64%   |
| PANDA                   | 10        | 1.36%   |
| InfoVision              | 10        | 1.36%   |
| Ancor Communications    | 10        | 1.36%   |
| AOC                     | 9         | 1.23%   |
| Philips                 | 8         | 1.09%   |
| Unknown                 | 7         | 0.95%   |
| ViewSonic               | 6         | 0.82%   |
| Lenovo                  | 6         | 0.82%   |
| Sony                    | 5         | 0.68%   |
| CSO                     | 5         | 0.68%   |
| Vizio                   | 4         | 0.55%   |
| Sceptre Tech            | 4         | 0.55%   |
| Panasonic               | 4         | 0.55%   |
| Iiyama                  | 4         | 0.55%   |
| Toshiba                 | 3         | 0.41%   |
| NEC Computers           | 3         | 0.41%   |
| Eizo                    | 3         | 0.41%   |
| AUS                     | 3         | 0.41%   |
| ___                     | 2         | 0.27%   |
| STD                     | 2         | 0.27%   |
| Insignia                | 2         | 0.27%   |
| ASUSTek Computer        | 2         | 0.27%   |
| Unknown                 | 2         | 0.27%   |
| VOR                     | 1         | 0.14%   |
| VIZ                     | 1         | 0.14%   |
| Unknown (AAA)           | 1         | 0.14%   |
| TMX                     | 1         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 7         | 0.94%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 6         | 0.8%    |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 4         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 4         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 4         | 0.53%   |
| BOE LCD Monitor BOE08A8 1920x1080 344x194mm 15.5-inch                 | 4         | 0.53%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 4         | 0.53%   |
| Sony TV SNYF301 1920x1080                                             | 3         | 0.4%    |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch  | 3         | 0.4%    |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 3         | 0.4%    |
| InfoVision LCD Monitor IVO8584 1920x1080 294x165mm 13.3-inch          | 3         | 0.4%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 3         | 0.4%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 0.4%    |
| BOE LCD Monitor BOE0897 1366x768 344x194mm 15.5-inch                  | 3         | 0.4%    |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                 | 3         | 0.4%    |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch        | 3         | 0.4%    |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch         | 3         | 0.4%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 3         | 0.4%    |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch        | 3         | 0.4%    |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                  | 3         | 0.4%    |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                  | 3         | 0.4%    |
| ___ LCD TV ___9000 1360x768                                           | 2         | 0.27%   |
| Vizio E421VO VIZ0070 1920x1080 930x523mm 42.0-inch                    | 2         | 0.27%   |
| Unknown LCD Monitor XMD Mi TV 1360x768                                | 2         | 0.27%   |
| Toshiba TV TSB0105 1920x1080 708x398mm 32.0-inch                      | 2         | 0.27%   |
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch               | 2         | 0.27%   |
| Samsung Electronics LF27T35 SAM707F 1920x1080 598x337mm 27.0-inch     | 2         | 0.27%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch  | 2         | 0.27%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch  | 2         | 0.27%   |
| Samsung Electronics LCD Monitor SEC3542 2160x1440 254x169mm 12.0-inch | 2         | 0.27%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 2         | 0.27%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch  | 2         | 0.27%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 2         | 0.27%   |
| Samsung Electronics LCD Monitor SAM07BA 1920x1080 480x270mm 21.7-inch | 2         | 0.27%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch     | 2         | 0.27%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch              | 2         | 0.27%   |
| Panasonic TV MEIA08F 1920x540                                         | 2         | 0.27%   |
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch           | 2         | 0.27%   |
| NEC Computers EA243WM NEC6864 1920x1200 519x324mm 24.1-inch           | 2         | 0.27%   |
| NEC Computers EA243WM NEC6863 1920x1200 519x324mm 24.1-inch           | 2         | 0.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 331       | 47.29%  |
| 1366x768 (WXGA)    | 156       | 22.29%  |
| 3840x2160 (4K)     | 31        | 4.43%   |
| 1600x900 (HD+)     | 26        | 3.71%   |
| 1920x1200 (WUXGA)  | 21        | 3%      |
| 1680x1050 (WSXGA+) | 19        | 2.71%   |
| 1280x800 (WXGA)    | 16        | 2.29%   |
| 2560x1440 (QHD)    | 14        | 2%      |
| 1280x1024 (SXGA)   | 14        | 2%      |
| 1440x900 (WXGA+)   | 11        | 1.57%   |
| 2560x1600          | 8         | 1.14%   |
| 1360x768           | 7         | 1%      |
| 2560x1080          | 6         | 0.86%   |
| 3440x1440          | 4         | 0.57%   |
| 2880x1800          | 4         | 0.57%   |
| 2160x1440          | 4         | 0.57%   |
| 1920x540           | 4         | 0.57%   |
| Unknown            | 4         | 0.57%   |
| 3840x2400          | 3         | 0.43%   |
| 3840x1080          | 2         | 0.29%   |
| 3200x1080          | 2         | 0.29%   |
| 1280x720 (HD)      | 2         | 0.29%   |
| 1024x768 (XGA)     | 2         | 0.29%   |
| 5200x1080          | 1         | 0.14%   |
| 3200x1800 (QHD+)   | 1         | 0.14%   |
| 3000x2000          | 1         | 0.14%   |
| 2944x1080          | 1         | 0.14%   |
| 2496x1664          | 1         | 0.14%   |
| 2400x1600          | 1         | 0.14%   |
| 2240x1400          | 1         | 0.14%   |
| 1920x515           | 1         | 0.14%   |
| 1600x1200          | 1         | 0.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 230       | 31.42%  |
| 14      | 84        | 11.48%  |
| 13      | 76        | 10.38%  |
| 17      | 45        | 6.15%   |
| 24      | 39        | 5.33%   |
| 27      | 33        | 4.51%   |
| Unknown | 27        | 3.69%   |
| 21      | 26        | 3.55%   |
| 23      | 22        | 3.01%   |
| 31      | 19        | 2.6%    |
| 12      | 19        | 2.6%    |
| 22      | 14        | 1.91%   |
| 16      | 12        | 1.64%   |
| 11      | 12        | 1.64%   |
| 19      | 11        | 1.5%    |
| 34      | 7         | 0.96%   |
| 72      | 6         | 0.82%   |
| 40      | 6         | 0.82%   |
| 20      | 6         | 0.82%   |
| 84      | 5         | 0.68%   |
| 32      | 5         | 0.68%   |
| 18      | 5         | 0.68%   |
| 54      | 3         | 0.41%   |
| 48      | 2         | 0.27%   |
| 47      | 2         | 0.27%   |
| 46      | 2         | 0.27%   |
| 42      | 2         | 0.27%   |
| 36      | 2         | 0.27%   |
| 29      | 2         | 0.27%   |
| 26      | 2         | 0.27%   |
| 69      | 1         | 0.14%   |
| 58      | 1         | 0.14%   |
| 52      | 1         | 0.14%   |
| 43      | 1         | 0.14%   |
| 41      | 1         | 0.14%   |
| 25      | 1         | 0.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 367       | 50.9%   |
| 501-600     | 87        | 12.07%  |
| 201-300     | 66        | 9.15%   |
| 401-500     | 53        | 7.35%   |
| 351-400     | 51        | 7.07%   |
| Unknown     | 27        | 3.74%   |
| 601-700     | 23        | 3.19%   |
| 701-800     | 14        | 1.94%   |
| 1501-2000   | 12        | 1.66%   |
| 1001-1500   | 11        | 1.53%   |
| 801-900     | 6         | 0.83%   |
| 901-1000    | 4         | 0.55%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 528       | 79.52%  |
| 16/10   | 79        | 11.9%   |
| Unknown | 19        | 2.86%   |
| 5/4     | 11        | 1.66%   |
| 21/9    | 8         | 1.2%    |
| 3/2     | 7         | 1.05%   |
| 4/3     | 6         | 0.9%    |
| 32/9    | 4         | 0.6%    |
| 6/5     | 1         | 0.15%   |
| 3.73    | 1         | 0.15%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 233       | 31.96%  |
| 81-90          | 129       | 17.7%   |
| 201-250        | 80        | 10.97%  |
| 301-350        | 35        | 4.8%    |
| 121-130        | 35        | 4.8%    |
| 71-80          | 32        | 4.39%   |
| 351-500        | 32        | 4.39%   |
| Unknown        | 27        | 3.7%    |
| 151-200        | 25        | 3.43%   |
| More than 1000 | 18        | 2.47%   |
| 61-70          | 18        | 2.47%   |
| 501-1000       | 16        | 2.19%   |
| 251-300        | 13        | 1.78%   |
| 51-60          | 12        | 1.65%   |
| 141-150        | 12        | 1.65%   |
| 111-120        | 9         | 1.23%   |
| 131-140        | 3         | 0.41%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 251       | 35.25%  |
| 101-120       | 178       | 25%     |
| 51-100        | 169       | 23.74%  |
| 161-240       | 51        | 7.16%   |
| Unknown       | 27        | 3.79%   |
| 1-50          | 21        | 2.95%   |
| More than 240 | 15        | 2.11%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 552       | 80.94%  |
| 2     | 101       | 14.81%  |
| 0     | 17        | 2.49%   |
| 3     | 12        | 1.76%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 370       | 33.45%  |
| Intel                                  | 357       | 32.28%  |
| Qualcomm Atheros                       | 102       | 9.22%   |
| Broadcom                               | 49        | 4.43%   |
| MediaTek                               | 27        | 2.44%   |
| Ralink Technology                      | 26        | 2.35%   |
| TP-Link                                | 23        | 2.08%   |
| Samsung Electronics                    | 16        | 1.45%   |
| Broadcom Limited                       | 16        | 1.45%   |
| Ralink                                 | 10        | 0.9%    |
| Xiaomi                                 | 9         | 0.81%   |
| Qualcomm Atheros Communications        | 9         | 0.81%   |
| NetGear                                | 8         | 0.72%   |
| Nvidia                                 | 7         | 0.63%   |
| Huawei Technologies                    | 6         | 0.54%   |
| ASIX Electronics                       | 6         | 0.54%   |
| Marvell Technology Group               | 5         | 0.45%   |
| ASUSTek Computer                       | 5         | 0.45%   |
| Qualcomm                               | 4         | 0.36%   |
| OPPO Electronics                       | 4         | 0.36%   |
| Microsoft                              | 4         | 0.36%   |
| Mercucys                               | 3         | 0.27%   |
| Linksys                                | 3         | 0.27%   |
| Lenovo                                 | 3         | 0.27%   |
| D-Link System                          | 3         | 0.27%   |
| vivo                                   | 2         | 0.18%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.18%   |
| Sierra Wireless                        | 2         | 0.18%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.18%   |
| JMicron Technology                     | 2         | 0.18%   |
| Google                                 | 2         | 0.18%   |
| Ericsson Business Mobile Networks      | 2         | 0.18%   |
| D-Link                                 | 2         | 0.18%   |
| Apple                                  | 2         | 0.18%   |
| ZyXEL Communications                   | 1         | 0.09%   |
| STMicroelectronics                     | 1         | 0.09%   |
| Sagem                                  | 1         | 0.09%   |
| Microchip Technology                   | 1         | 0.09%   |
| ICS Advent                             | 1         | 0.09%   |
| Gemtek                                 | 1         | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 223       | 16.91%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 43        | 3.26%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 32        | 2.43%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 32        | 2.43%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 30        | 2.27%   |
| Intel Wi-Fi 6 AX201                                                    | 28        | 2.12%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 21        | 1.59%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 21        | 1.59%   |
| Intel Wireless 8265 / 8275                                             | 21        | 1.59%   |
| Intel Wi-Fi 6 AX200                                                    | 21        | 1.59%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 20        | 1.52%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 17        | 1.29%   |
| Intel Wireless 7265                                                    | 17        | 1.29%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 16        | 1.21%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 13        | 0.99%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 12        | 0.91%   |
| Intel Wireless 7260                                                    | 12        | 0.91%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 12        | 0.91%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 12        | 0.91%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 11        | 0.83%   |
| Realtek RTL8125 2.5GbE Controller                                      | 10        | 0.76%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 10        | 0.76%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 10        | 0.76%   |
| Intel Wireless 8260                                                    | 10        | 0.76%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 9         | 0.68%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 9         | 0.68%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 9         | 0.68%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 9         | 0.68%   |
| Qualcomm Atheros AR9271 802.11n                                        | 9         | 0.68%   |
| Intel Ethernet Connection (4) I219-LM                                  | 9         | 0.68%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 8         | 0.61%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 8         | 0.61%   |
| Intel I211 Gigabit Network Connection                                  | 8         | 0.61%   |
| Intel Ethernet Controller I225-V                                       | 8         | 0.61%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 7         | 0.53%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                | 7         | 0.53%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 7         | 0.53%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 7         | 0.53%   |
| Realtek 802.11ac NIC                                                   | 7         | 0.53%   |
| Intel Wireless 3165                                                    | 7         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 304       | 43.68%  |
| Realtek Semiconductor           | 129       | 18.53%  |
| Qualcomm Atheros                | 80        | 11.49%  |
| Broadcom                        | 41        | 5.89%   |
| Ralink Technology               | 26        | 3.74%   |
| TP-Link                         | 23        | 3.3%    |
| MediaTek                        | 23        | 3.3%    |
| Broadcom Limited                | 13        | 1.87%   |
| Ralink                          | 10        | 1.44%   |
| Qualcomm Atheros Communications | 9         | 1.29%   |
| NetGear                         | 8         | 1.15%   |
| ASUSTek Computer                | 5         | 0.72%   |
| Microsoft                       | 4         | 0.57%   |
| Mercucys                        | 3         | 0.43%   |
| Marvell Technology Group        | 3         | 0.43%   |
| Linksys                         | 3         | 0.43%   |
| Sierra Wireless                 | 2         | 0.29%   |
| D-Link                          | 2         | 0.29%   |
| ZyXEL Communications            | 1         | 0.14%   |
| Sagem                           | 1         | 0.14%   |
| Qualcomm                        | 1         | 0.14%   |
| Gemtek                          | 1         | 0.14%   |
| Fibocom                         | 1         | 0.14%   |
| Dell                            | 1         | 0.14%   |
| D-Link System                   | 1         | 0.14%   |
| Belkin Components               | 1         | 0.14%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P PCH CNVi WiFi                                     | 30        | 4.27%   |
| Intel Wi-Fi 6 AX201                                                  | 28        | 3.99%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 21        | 2.99%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 21        | 2.99%   |
| Intel Wireless 8265 / 8275                                           | 21        | 2.99%   |
| Intel Wi-Fi 6 AX200                                                  | 21        | 2.99%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 20        | 2.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 17        | 2.42%   |
| Intel Wireless 7265                                                  | 17        | 2.42%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 16        | 2.28%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 13        | 1.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 12        | 1.71%   |
| Intel Wireless 7260                                                  | 12        | 1.71%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 12        | 1.71%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 12        | 1.71%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 11        | 1.57%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 10        | 1.42%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 10        | 1.42%   |
| Intel Wireless 8260                                                  | 10        | 1.42%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 9         | 1.28%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 9         | 1.28%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 9         | 1.28%   |
| Qualcomm Atheros AR9271 802.11n                                      | 9         | 1.28%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 8         | 1.14%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 8         | 1.14%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter              | 7         | 1%      |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 7         | 1%      |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 7         | 1%      |
| Realtek 802.11ac NIC                                                 | 7         | 1%      |
| Intel Wireless 3165                                                  | 7         | 1%      |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 7         | 1%      |
| Intel Tiger Lake PCH CNVi WiFi                                       | 7         | 1%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 7         | 1%      |
| Intel Cannon Lake PCH CNVi WiFi                                      | 7         | 1%      |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 7         | 1%      |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                  | 6         | 0.85%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 6         | 0.85%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 6         | 0.85%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 6         | 0.85%   |
| Broadcom BCM43142 802.11b/g/n                                        | 6         | 0.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 318       | 54.17%  |
| Intel                                  | 150       | 25.55%  |
| Qualcomm Atheros                       | 36        | 6.13%   |
| Broadcom                               | 15        | 2.56%   |
| Xiaomi                                 | 9         | 1.53%   |
| Samsung Electronics                    | 9         | 1.53%   |
| Nvidia                                 | 7         | 1.19%   |
| ASIX Electronics                       | 6         | 1.02%   |
| OPPO Electronics                       | 4         | 0.68%   |
| MediaTek                               | 4         | 0.68%   |
| Qualcomm                               | 3         | 0.51%   |
| Lenovo                                 | 3         | 0.51%   |
| Broadcom Limited                       | 3         | 0.51%   |
| vivo                                   | 2         | 0.34%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.34%   |
| Marvell Technology Group               | 2         | 0.34%   |
| JMicron Technology                     | 2         | 0.34%   |
| Huawei Technologies                    | 2         | 0.34%   |
| Google                                 | 2         | 0.34%   |
| D-Link System                          | 2         | 0.34%   |
| Apple                                  | 2         | 0.34%   |
| ICS Advent                             | 1         | 0.17%   |
| DisplayLink                            | 1         | 0.17%   |
| Davicom Semiconductor                  | 1         | 0.17%   |
| Aquantia                               | 1         | 0.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 223       | 37.23%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 43        | 7.18%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 32        | 5.34%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 30        | 5.01%   |
| Realtek RTL8125 2.5GbE Controller                                      | 10        | 1.67%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 9         | 1.5%    |
| Intel Ethernet Connection (4) I219-LM                                  | 9         | 1.5%    |
| Intel I211 Gigabit Network Connection                                  | 8         | 1.34%   |
| Intel Ethernet Controller I225-V                                       | 8         | 1.34%   |
| Intel Ethernet Connection I218-LM                                      | 7         | 1.17%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 6         | 1%      |
| Realtek Killer E2600 GbE Controller                                    | 6         | 1%      |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 6         | 1%      |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 6         | 1%      |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 6         | 1%      |
| Intel Ethernet Connection (6) I219-V                                   | 6         | 1%      |
| Intel Ethernet Connection (2) I219-V                                   | 6         | 1%      |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 5         | 0.83%   |
| Intel Ethernet Connection I219-LM                                      | 5         | 0.83%   |
| Intel Ethernet Connection I217-V                                       | 5         | 0.83%   |
| Intel 82579V Gigabit Network Connection                                | 5         | 0.83%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 4         | 0.67%   |
| Intel Ethernet Connection I217-LM                                      | 4         | 0.67%   |
| Intel Ethernet Connection (6) I219-LM                                  | 4         | 0.67%   |
| Intel Ethernet Connection (3) I218-LM                                  | 4         | 0.67%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 4         | 0.67%   |
| ASIX AX88179 Gigabit Ethernet                                          | 4         | 0.67%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 3         | 0.5%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 3         | 0.5%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 3         | 0.5%    |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 3         | 0.5%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 3         | 0.5%    |
| Nvidia MCP79 Ethernet                                                  | 3         | 0.5%    |
| Nvidia MCP61 Ethernet                                                  | 3         | 0.5%    |
| Intel Ethernet Connection I219-V                                       | 3         | 0.5%    |
| Intel Ethernet Connection (7) I219-V                                   | 3         | 0.5%    |
| Intel Ethernet Connection (16) I219-V                                  | 3         | 0.5%    |
| Intel Ethernet Connection (11) I219-LM                                 | 3         | 0.5%    |
| Broadcom BCM4401-B0 100Base-TX                                         | 3         | 0.5%    |
| Realtek Killer E3000 2.5GbE Controller                                 | 2         | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 603       | 51.72%  |
| Ethernet | 545       | 46.74%  |
| Modem    | 15        | 1.29%   |
| Unknown  | 3         | 0.26%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 464       | 66.76%  |
| Ethernet | 230       | 33.09%  |
| Unknown  | 1         | 0.14%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 382       | 56.93%  |
| 1     | 262       | 39.05%  |
| 0     | 13        | 1.94%   |
| 3     | 12        | 1.79%   |
| 5     | 1         | 0.15%   |
| 4     | 1         | 0.15%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 514       | 75.81%  |
| Yes     | 163       | 24.04%  |
| Unknown | 1         | 0.15%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 242       | 50%     |
| Realtek Semiconductor           | 53        | 10.95%  |
| Qualcomm Atheros Communications | 42        | 8.68%   |
| IMC Networks                    | 23        | 4.75%   |
| Broadcom                        | 22        | 4.55%   |
| Apple                           | 19        | 3.93%   |
| Foxconn / Hon Hai               | 16        | 3.31%   |
| Cambridge Silicon Radio         | 16        | 3.31%   |
| Lite-On Technology              | 15        | 3.1%    |
| ASUSTek Computer                | 6         | 1.24%   |
| MediaTek                        | 5         | 1.03%   |
| Dell                            | 5         | 1.03%   |
| Toshiba                         | 3         | 0.62%   |
| Realtek                         | 3         | 0.62%   |
| Marvell Semiconductor           | 3         | 0.62%   |
| TP-Link                         | 2         | 0.41%   |
| Ralink                          | 2         | 0.41%   |
| Hewlett-Packard                 | 2         | 0.41%   |
| Dynex                           | 2         | 0.41%   |
| Logitech                        | 1         | 0.21%   |
| Alps Electric                   | 1         | 0.21%   |
| Unknown                         | 1         | 0.21%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 72        | 14.85%  |
| Intel AX201 Bluetooth                               | 70        | 14.43%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 34        | 7.01%   |
| Realtek Bluetooth Radio                             | 33        | 6.8%    |
| Qualcomm Atheros  Bluetooth Device                  | 22        | 4.54%   |
| Intel AX211 Bluetooth                               | 21        | 4.33%   |
| Intel AX200 Bluetooth                               | 19        | 3.92%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 16        | 3.3%    |
| Realtek  Bluetooth 4.2 Adapter                      | 15        | 3.09%   |
| IMC Networks Wireless_Device                        | 9         | 1.86%   |
| Intel Wireless-AC 3168 Bluetooth                    | 7         | 1.44%   |
| Intel AX210 Bluetooth                               | 7         | 1.44%   |
| IMC Networks Bluetooth Device                       | 7         | 1.44%   |
| Apple Bluetooth USB Host Controller                 | 7         | 1.44%   |
| Apple Bluetooth Host Controller                     | 7         | 1.44%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 1.24%   |
| IMC Networks Bluetooth Radio                        | 6         | 1.24%   |
| Foxconn / Hon Hai Bluetooth Device                  | 6         | 1.24%   |
| MediaTek Wireless_Device                            | 5         | 1.03%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 5         | 1.03%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 1.03%   |
| Foxconn / Hon Hai Wireless_Device                   | 4         | 0.82%   |
| Dell DW375 Bluetooth Module                         | 4         | 0.82%   |
| Broadcom HP Portable SoftSailing                    | 4         | 0.82%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 4         | 0.82%   |
| Realtek RTL8821A Bluetooth                          | 3         | 0.62%   |
| Realtek Bluetooth Radio                             | 3         | 0.62%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 0.62%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 3         | 0.62%   |
| Qualcomm Atheros Bluetooth                          | 3         | 0.62%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 0.62%   |
| Lite-On Wireless_Device                             | 3         | 0.62%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 0.62%   |
| Broadcom BCM43142A0 Bluetooth Device                | 3         | 0.62%   |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 0.62%   |
| TP-Link TP-Link Bluetooth USB Adapter               | 2         | 0.41%   |
| Ralink RT3290 Bluetooth                             | 2         | 0.41%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 0.41%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 2         | 0.41%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 2         | 0.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 523       | 59.3%   |
| AMD                      | 156       | 17.69%  |
| Nvidia                   | 153       | 17.35%  |
| C-Media Electronics      | 10        | 1.13%   |
| JMTek                    | 4         | 0.45%   |
| Razer USA                | 3         | 0.34%   |
| GN Netcom                | 3         | 0.34%   |
| Tenx Technology          | 2         | 0.23%   |
| Realtek Semiconductor    | 2         | 0.23%   |
| Logitech                 | 2         | 0.23%   |
| Generalplus Technology   | 2         | 0.23%   |
| Creative Labs            | 2         | 0.23%   |
| Corsair                  | 2         | 0.23%   |
| Yamaha                   | 1         | 0.11%   |
| Texas Instruments        | 1         | 0.11%   |
| SteelSeries ApS          | 1         | 0.11%   |
| Samson Technologies      | 1         | 0.11%   |
| Plantronics              | 1         | 0.11%   |
| Micro Star International | 1         | 0.11%   |
| Lenovo                   | 1         | 0.11%   |
| Kingston Technology      | 1         | 0.11%   |
| GYROCOM C&C              | 1         | 0.11%   |
| Guillemot                | 1         | 0.11%   |
| GS3                      | 1         | 0.11%   |
| fifine Microphones       | 1         | 0.11%   |
| DEXP BK-20               | 1         | 0.11%   |
| Conexant Systems         | 1         | 0.11%   |
| Cambridge Silicon Radio  | 1         | 0.11%   |
| ATI Technologies         | 1         | 0.11%   |
| Apple                    | 1         | 0.11%   |
| Anker                    | 1         | 0.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 64        | 6.08%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 56        | 5.32%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 49        | 4.66%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 46        | 4.37%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 41        | 3.9%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 37        | 3.52%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 33        | 3.14%   |
| Intel Haswell-ULT HD Audio Controller                                      | 23        | 2.19%   |
| Intel 8 Series HD Audio Controller                                         | 23        | 2.19%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 22        | 2.09%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 22        | 2.09%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 22        | 2.09%   |
| Intel Cannon Lake PCH cAVS                                                 | 21        | 2%      |
| AMD SBx00 Azalia (Intel HDA)                                               | 21        | 2%      |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 19        | 1.81%   |
| Intel Broadwell-U Audio Controller                                         | 19        | 1.81%   |
| AMD FCH Azalia Controller                                                  | 18        | 1.71%   |
| Intel Comet Lake PCH cAVS                                                  | 17        | 1.62%   |
| Nvidia GA106 High Definition Audio Controller                              | 16        | 1.52%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 16        | 1.52%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 16        | 1.52%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 14        | 1.33%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 13        | 1.24%   |
| Intel Comet Lake PCH-LP cAVS                                               | 13        | 1.24%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 13        | 1.24%   |
| Nvidia GA104 High Definition Audio Controller                              | 12        | 1.14%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 12        | 1.14%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 11        | 1.05%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 11        | 1.05%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 11        | 1.05%   |
| Nvidia TU106 High Definition Audio Controller                              | 10        | 0.95%   |
| Nvidia GP107GL High Definition Audio Controller                            | 10        | 0.95%   |
| Nvidia GA107 High Definition Audio Controller                              | 10        | 0.95%   |
| AMD Starship/Matisse HD Audio Controller                                   | 10        | 0.95%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 10        | 0.95%   |
| AMD Kabini HDMI/DP Audio                                                   | 9         | 0.86%   |
| Nvidia TU116 High Definition Audio Controller                              | 8         | 0.76%   |
| Intel Alder Lake-S HD Audio Controller                                     | 8         | 0.76%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 8         | 0.76%   |
| AMD High Definition Audio Controller                                       | 8         | 0.76%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 134       | 26.43%  |
| SK hynix            | 81        | 15.98%  |
| Micron Technology   | 74        | 14.6%   |
| Kingston            | 41        | 8.09%   |
| Crucial             | 38        | 7.5%    |
| Unknown             | 29        | 5.72%   |
| Corsair             | 19        | 3.75%   |
| Elpida              | 13        | 2.56%   |
| Ramaxel Technology  | 11        | 2.17%   |
| A-DATA Technology   | 11        | 2.17%   |
| Unknown (ABCD)      | 7         | 1.38%   |
| Team                | 7         | 1.38%   |
| G.Skill             | 7         | 1.38%   |
| Nanya Technology    | 6         | 1.18%   |
| Unknown             | 5         | 0.99%   |
| Smart               | 3         | 0.59%   |
| PNY                 | 3         | 0.59%   |
| Transcend           | 2         | 0.39%   |
| Avant               | 2         | 0.39%   |
| Unifosa             | 1         | 0.2%    |
| Timetec             | 1         | 0.2%    |
| Teikon              | 1         | 0.2%    |
| TBD                 | 1         | 0.2%    |
| Silicon Power       | 1         | 0.2%    |
| Saikano             | 1         | 0.2%    |
| S                   | 1         | 0.2%    |
| Ramos Technology    | 1         | 0.2%    |
| Patriot             | 1         | 0.2%    |
| Lexar Co Limited    | 1         | 0.2%    |
| fef5                | 1         | 0.2%    |
| ChangXin Memory     | 1         | 0.2%    |
| Asgard              | 1         | 0.2%    |
| AMD                 | 1         | 0.2%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 10        | 1.88%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 7         | 1.32%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 1.32%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 1.32%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 1.32%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 6         | 1.13%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 0.94%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 5         | 0.94%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 5         | 0.94%   |
| Unknown                                                          | 5         | 0.94%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.75%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.75%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.75%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 4         | 0.75%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 3         | 0.56%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 3         | 0.56%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.56%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.56%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 0.56%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.56%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 0.56%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 3         | 0.56%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 3         | 0.56%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s           | 3         | 0.56%   |
| Crucial RAM CT8G4SFRA32A.M4FE 8GB SODIMM DDR4 3200MT/s           | 3         | 0.56%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 3         | 0.56%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 3         | 0.56%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 2         | 0.38%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 2         | 0.38%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 2         | 0.38%   |
| Transcend RAM JM1333KSN-4G 4GB SODIMM DDR3 1334MT/s              | 2         | 0.38%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 2         | 0.38%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 2         | 0.38%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s             | 2         | 0.38%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.38%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 2         | 0.38%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 2         | 0.38%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 2667MT/s           | 2         | 0.38%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.38%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 0.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 209       | 48.05%  |
| DDR3    | 132       | 30.34%  |
| LPDDR4  | 27        | 6.21%   |
| LPDDR3  | 15        | 3.45%   |
| DDR5    | 15        | 3.45%   |
| Unknown | 14        | 3.22%   |
| DDR2    | 10        | 2.3%    |
| LPDDR5  | 7         | 1.61%   |
| SDRAM   | 5         | 1.15%   |
| DDR     | 1         | 0.23%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 302       | 70.23%  |
| DIMM         | 79        | 18.37%  |
| Row Of Chips | 43        | 10%     |
| Unknown      | 4         | 0.93%   |
| Chip         | 2         | 0.47%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 192       | 40.08%  |
| 4096  | 122       | 25.47%  |
| 16384 | 83        | 17.33%  |
| 2048  | 43        | 8.98%   |
| 32768 | 24        | 5.01%   |
| 1024  | 15        | 3.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 101       | 21.31%  |
| 1600    | 88        | 18.57%  |
| 2667    | 78        | 16.46%  |
| 2400    | 32        | 6.75%   |
| 2133    | 21        | 4.43%   |
| 1334    | 19        | 4.01%   |
| 1333    | 18        | 3.8%    |
| 4800    | 12        | 2.53%   |
| 1867    | 12        | 2.53%   |
| 3600    | 11        | 2.32%   |
| 4267    | 9         | 1.9%    |
| 6400    | 6         | 1.27%   |
| 5600    | 6         | 1.27%   |
| 1067    | 6         | 1.27%   |
| Unknown | 6         | 1.27%   |
| 1066    | 5         | 1.05%   |
| 1800    | 4         | 0.84%   |
| 800     | 4         | 0.84%   |
| 667     | 4         | 0.84%   |
| 3800    | 3         | 0.63%   |
| 3733    | 3         | 0.63%   |
| 3266    | 3         | 0.63%   |
| 1866    | 3         | 0.63%   |
| 975     | 2         | 0.42%   |
| 12800   | 1         | 0.21%   |
| 8400    | 1         | 0.21%   |
| 7500    | 1         | 0.21%   |
| 6800    | 1         | 0.21%   |
| 4266    | 1         | 0.21%   |
| 4000    | 1         | 0.21%   |
| 3866    | 1         | 0.21%   |
| 3666    | 1         | 0.21%   |
| 3534    | 1         | 0.21%   |
| 3100    | 1         | 0.21%   |
| 3000    | 1         | 0.21%   |
| 2933    | 1         | 0.21%   |
| 2666    | 1         | 0.21%   |
| 2200    | 1         | 0.21%   |
| 2048    | 1         | 0.21%   |
| 1227    | 1         | 0.21%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 2         | 28.57%  |
| Brother Industries  | 2         | 28.57%  |
| Seiko Epson         | 1         | 14.29%  |
| Samsung Electronics | 1         | 14.29%  |
| Dymo-CoStar         | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                        | Computers | Percent |
|------------------------------|-----------|---------|
| Seiko Epson L120 Series      | 1         | 14.29%  |
| Samsung ML-2850 Series       | 1         | 14.29%  |
| HP OfficeJet Pro 7720 series | 1         | 14.29%  |
| HP Deskjet 2050 J510         | 1         | 14.29%  |
| Dymo-CoStar LabelWriter 450  | 1         | 14.29%  |
| Brother HL-1210W series      | 1         | 14.29%  |
| Brother DCP-T300             | 1         | 14.29%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 107       | 22.34%  |
| IMC Networks                           | 50        | 10.44%  |
| Microdia                               | 40        | 8.35%   |
| Bison Electronics                      | 33        | 6.89%   |
| Quanta                                 | 28        | 5.85%   |
| Realtek Semiconductor                  | 26        | 5.43%   |
| Sunplus Innovation Technology          | 23        | 4.8%    |
| Apple                                  | 22        | 4.59%   |
| Luxvisions Innotech Limited            | 16        | 3.34%   |
| Syntek                                 | 15        | 3.13%   |
| Acer                                   | 15        | 3.13%   |
| Cheng Uei Precision Industry (Foxlink) | 14        | 2.92%   |
| Logitech                               | 10        | 2.09%   |
| Lite-On Technology                     | 10        | 2.09%   |
| Suyin                                  | 7         | 1.46%   |
| Sonix Technology                       | 7         | 1.46%   |
| Silicon Motion                         | 6         | 1.25%   |
| Samsung Electronics                    | 6         | 1.25%   |
| Ricoh                                  | 6         | 1.25%   |
| icSpring                               | 4         | 0.84%   |
| Alcor Micro                            | 4         | 0.84%   |
| SunplusIT                              | 3         | 0.63%   |
| Microsoft                              | 3         | 0.63%   |
| Primax Electronics                     | 2         | 0.42%   |
| LG Electronics                         | 2         | 0.42%   |
| Importek                               | 2         | 0.42%   |
| Generalplus Technology                 | 2         | 0.42%   |
| Creative Technology                    | 2         | 0.42%   |
| USB Camera CS                          | 1         | 0.21%   |
| Tobii Technology AB                    | 1         | 0.21%   |
| Teslong Camera                         | 1         | 0.21%   |
| ShineTech                              | 1         | 0.21%   |
| Razer USA                              | 1         | 0.21%   |
| Lenovo                                 | 1         | 0.21%   |
| Jieli Technology                       | 1         | 0.21%   |
| Goertek Electronics                    | 1         | 0.21%   |
| Genesys Logic                          | 1         | 0.21%   |
| GEMBIRD                                | 1         | 0.21%   |
| Canon                                  | 1         | 0.21%   |
| AVerMedia Technologies                 | 1         | 0.21%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 22        | 4.56%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 16        | 3.32%   |
| IMC Networks Integrated Camera                       | 14        | 2.9%    |
| Realtek Integrated_Webcam_HD                         | 11        | 2.28%   |
| Microdia Integrated_Webcam_HD                        | 11        | 2.28%   |
| Bison HD Webcam                                      | 11        | 2.28%   |
| Syntek Integrated Camera                             | 10        | 2.07%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                   | 10        | 2.07%   |
| Chicony HD User Facing                               | 8         | 1.66%   |
| Sunplus Integrated_Webcam_HD                         | 6         | 1.24%   |
| Samsung Galaxy series, misc. (MTP mode)              | 6         | 1.24%   |
| Quanta HD User Facing                                | 6         | 1.24%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 6         | 1.24%   |
| Chicony HP Truevision HD                             | 6         | 1.24%   |
| Chicony HP HD Camera                                 | 6         | 1.24%   |
| Chicony HD Webcam                                    | 6         | 1.24%   |
| Bison Integrated Camera                              | 6         | 1.24%   |
| Quanta HP TrueVision HD Camera                       | 5         | 1.04%   |
| Chicony USB2.0 Camera                                | 5         | 1.04%   |
| Bison SunplusIT Integrated Camera                    | 5         | 1.04%   |
| Apple Built-in iSight                                | 5         | 1.04%   |
| Acer Integrated Camera                               | 5         | 1.04%   |
| Sonix USB2.0 HD UVC WebCam                           | 4         | 0.83%   |
| Realtek Integrated Webcam HD                         | 4         | 0.83%   |
| Quanta HP HD Camera                                  | 4         | 0.83%   |
| Microdia Webcam Vitade AF                            | 4         | 0.83%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 4         | 0.83%   |
| IMC Networks HD Camera                               | 4         | 0.83%   |
| icSpring camera                                      | 4         | 0.83%   |
| Chicony USB2.0 HD UVC WebCam                         | 4         | 0.83%   |
| Chicony Integrated Camera (1280x720@30)              | 4         | 0.83%   |
| Chicony EasyCamera                                   | 4         | 0.83%   |
| Apple FaceTime HD Camera                             | 4         | 0.83%   |
| Syntek Lenovo EasyCamera                             | 3         | 0.62%   |
| Quanta ACER HD User Facing                           | 3         | 0.62%   |
| Microdia USB 2.0 Camera                              | 3         | 0.62%   |
| Microdia PC Microscope camera                        | 3         | 0.62%   |
| Microdia Laptop_Integrated_Webcam_HD                 | 3         | 0.62%   |
| Microdia Integrated_Webcam_FHD                       | 3         | 0.62%   |
| Microdia Integrated Webcam HD                        | 3         | 0.62%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 40        | 40.82%  |
| Validity Sensors           | 29        | 29.59%  |
| Shenzhen Goodix Technology | 11        | 11.22%  |
| Elan Microelectronics      | 7         | 7.14%   |
| Upek                       | 4         | 4.08%   |
| AuthenTec                  | 3         | 3.06%   |
| LighTuning Technology      | 2         | 2.04%   |
| Samsung Electronics        | 1         | 1.02%   |
| HOLTEK                     | 1         | 1.02%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 10        | 10.2%   |
| Shenzhen Goodix  Fingerprint Device                                        | 8         | 8.16%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 6         | 6.12%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 5         | 5.1%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 5.1%    |
| Elan ELAN:Fingerprint                                                      | 5         | 5.1%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 4.08%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 4         | 4.08%   |
| Synaptics WBDI                                                             | 4         | 4.08%   |
| Synaptics UWP WBDI Device                                                  | 4         | 4.08%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 3.06%   |
| Validity Sensors VFS491                                                    | 3         | 3.06%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 3.06%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 3.06%   |
| Synaptics UWP WBDI                                                         | 3         | 3.06%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 3.06%   |
| Synaptics Fingerprint reader [HP G6]                                       | 3         | 3.06%   |
| Synaptics  WBDI                                                            | 2         | 2.04%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 2.04%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 2.04%   |
| Elan ELAN:ARM-M4                                                           | 2         | 2.04%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 2.04%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 1.02%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 1.02%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.02%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 1.02%   |
| Synaptics Prometheus Fingerprint Reader                                    | 1         | 1.02%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.02%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.02%   |
| Samsung Fingerprint Device                                                 | 1         | 1.02%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 1.02%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 1.02%   |
| HOLTEK FocalTech Fingerprint Device                                        | 1         | 1.02%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 1.02%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Broadcom         | 17        | 56.67%  |
| Alcor Micro      | 8         | 26.67%  |
| SCM Microsystems | 2         | 6.67%   |
| Upek             | 1         | 3.33%   |
| OmniKey          | 1         | 3.33%   |
| O2 Micro         | 1         | 3.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 8         | 26.67%  |
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 23.33%  |
| Broadcom 5880                                                                | 6         | 20%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 10%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 3.33%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 3.33%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 3.33%   |
| OmniKey CardMan Smart@Link                                                   | 1         | 3.33%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 3.33%   |
| Broadcom 58200                                                               | 1         | 3.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 423       | 62.11%  |
| 1     | 209       | 30.69%  |
| 2     | 46        | 6.75%   |
| 3     | 2         | 0.29%   |
| 4     | 1         | 0.15%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 98        | 32.89%  |
| Graphics card            | 54        | 18.12%  |
| Net/wireless             | 39        | 13.09%  |
| Chipcard                 | 26        | 8.72%   |
| Multimedia controller    | 25        | 8.39%   |
| Net/ethernet             | 16        | 5.37%   |
| Camera                   | 13        | 4.36%   |
| Storage                  | 6         | 2.01%   |
| Bluetooth                | 5         | 1.68%   |
| Network                  | 4         | 1.34%   |
| Sound                    | 3         | 1.01%   |
| Communication controller | 3         | 1.01%   |
| Dvb card                 | 2         | 0.67%   |
| Unassigned class         | 1         | 0.34%   |
| Storage/raid             | 1         | 0.34%   |
| Modem                    | 1         | 0.34%   |
| Card reader              | 1         | 0.34%   |

