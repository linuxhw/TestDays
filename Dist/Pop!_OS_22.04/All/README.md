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

Total: 3625

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | ENVY x360 Convertible 15... | Convertible | [dc16d81ba0](https://linux-hardware.org/?probe=dc16d81ba0) | May 01, 2023 |
| Fujitsu       | D3223-A1 S26361-D3223-A1    | Desktop     | [9b6f7cea89](https://linux-hardware.org/?probe=9b6f7cea89) | May 01, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [80671ff25c](https://linux-hardware.org/?probe=80671ff25c) | May 01, 2023 |
| Lenovo        | ThinkPad P52s 20LCS1H100    | Notebook    | [34b877bcb5](https://linux-hardware.org/?probe=34b877bcb5) | May 01, 2023 |
| ASUSTek       | X455LJ                      | Notebook    | [4e252eab9f](https://linux-hardware.org/?probe=4e252eab9f) | May 01, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [0d5e9310d3](https://linux-hardware.org/?probe=0d5e9310d3) | Apr 30, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [9df1b688c0](https://linux-hardware.org/?probe=9df1b688c0) | Apr 30, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [875ae124a1](https://linux-hardware.org/?probe=875ae124a1) | Apr 30, 2023 |
| Dell          | Latitude E6430              | Notebook    | [4c20239367](https://linux-hardware.org/?probe=4c20239367) | Apr 30, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [04a7cea7cb](https://linux-hardware.org/?probe=04a7cea7cb) | Apr 29, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | Desktop     | [4ac7cbf111](https://linux-hardware.org/?probe=4ac7cbf111) | Apr 29, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [3feeeb3341](https://linux-hardware.org/?probe=3feeeb3341) | Apr 29, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [8e0692ebe3](https://linux-hardware.org/?probe=8e0692ebe3) | Apr 29, 2023 |
| Gigabyte      | B660 GAMING X DDR4          | Desktop     | [c203c197b7](https://linux-hardware.org/?probe=c203c197b7) | Apr 29, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [af0c1ea83c](https://linux-hardware.org/?probe=af0c1ea83c) | Apr 29, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [7c8c5a4668](https://linux-hardware.org/?probe=7c8c5a4668) | Apr 29, 2023 |
| Intel         | DB75EN AAG39650-303         | Desktop     | [713c422641](https://linux-hardware.org/?probe=713c422641) | Apr 29, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [998427cdcf](https://linux-hardware.org/?probe=998427cdcf) | Apr 29, 2023 |
| HP            | 8054                        | Desktop     | [81a57b4a2f](https://linux-hardware.org/?probe=81a57b4a2f) | Apr 29, 2023 |
| Dell          | Inspiron 7706 2n1           | Convertible | [9a9fdf0dd3](https://linux-hardware.org/?probe=9a9fdf0dd3) | Apr 29, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [9b560392f5](https://linux-hardware.org/?probe=9b560392f5) | Apr 29, 2023 |
| Gigabyte      | H410M H                     | Desktop     | [3ea3271f4a](https://linux-hardware.org/?probe=3ea3271f4a) | Apr 29, 2023 |
| Dell          | 0P4T42 A01                  | All in one  | [323e28fded](https://linux-hardware.org/?probe=323e28fded) | Apr 29, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ARH7 8... | Notebook    | [39644ab1d4](https://linux-hardware.org/?probe=39644ab1d4) | Apr 28, 2023 |
| Lenovo        | ThinkPad T450 20BUS0B000    | Notebook    | [a2cbf65767](https://linux-hardware.org/?probe=a2cbf65767) | Apr 28, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [261c116001](https://linux-hardware.org/?probe=261c116001) | Apr 28, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [266688994a](https://linux-hardware.org/?probe=266688994a) | Apr 28, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [af0663fd52](https://linux-hardware.org/?probe=af0663fd52) | Apr 28, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [f1679a62d0](https://linux-hardware.org/?probe=f1679a62d0) | Apr 28, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [26c158df39](https://linux-hardware.org/?probe=26c158df39) | Apr 28, 2023 |
| HP            | ENVY 15                     | Notebook    | [d870c486c7](https://linux-hardware.org/?probe=d870c486c7) | Apr 27, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [f96c9382bd](https://linux-hardware.org/?probe=f96c9382bd) | Apr 27, 2023 |
| Dell          | Latitude D520               | Notebook    | [a643e2e424](https://linux-hardware.org/?probe=a643e2e424) | Apr 27, 2023 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [4363ca582a](https://linux-hardware.org/?probe=4363ca582a) | Apr 26, 2023 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [f5de49d5b3](https://linux-hardware.org/?probe=f5de49d5b3) | Apr 26, 2023 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | Desktop     | [83453e6960](https://linux-hardware.org/?probe=83453e6960) | Apr 26, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [208a0fc365](https://linux-hardware.org/?probe=208a0fc365) | Apr 26, 2023 |
| Intel         | B75                         | Desktop     | [72a3677ac2](https://linux-hardware.org/?probe=72a3677ac2) | Apr 26, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [d040f4ff16](https://linux-hardware.org/?probe=d040f4ff16) | Apr 26, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [a24f74af8e](https://linux-hardware.org/?probe=a24f74af8e) | Apr 26, 2023 |
| Lenovo        | ThinkPad L570 20J80021MD    | Notebook    | [26e9a466cd](https://linux-hardware.org/?probe=26e9a466cd) | Apr 26, 2023 |
| Intel         | X99H                        | Desktop     | [d0f8c22128](https://linux-hardware.org/?probe=d0f8c22128) | Apr 26, 2023 |
| System76      | Gazelle                     | Notebook    | [ca2e23db8d](https://linux-hardware.org/?probe=ca2e23db8d) | Apr 25, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [f797b7112c](https://linux-hardware.org/?probe=f797b7112c) | Apr 25, 2023 |
| HP            | ENVY 15                     | Notebook    | [3539894e49](https://linux-hardware.org/?probe=3539894e49) | Apr 25, 2023 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [da35752b66](https://linux-hardware.org/?probe=da35752b66) | Apr 25, 2023 |
| ASRock        | Z370 Extreme4               | Desktop     | [0e46ae0751](https://linux-hardware.org/?probe=0e46ae0751) | Apr 25, 2023 |
| Lenovo        | 103D SDK0J40697 WIN 3305... | Desktop     | [f82b3152d0](https://linux-hardware.org/?probe=f82b3152d0) | Apr 25, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [517a694a82](https://linux-hardware.org/?probe=517a694a82) | Apr 25, 2023 |
| Acer          | E5-551G-871W                | Notebook    | [2730a30d89](https://linux-hardware.org/?probe=2730a30d89) | Apr 25, 2023 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [42a0a6d5e4](https://linux-hardware.org/?probe=42a0a6d5e4) | Apr 25, 2023 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [7ab59d4ba9](https://linux-hardware.org/?probe=7ab59d4ba9) | Apr 25, 2023 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [05d2b26ee6](https://linux-hardware.org/?probe=05d2b26ee6) | Apr 25, 2023 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [0ef0676073](https://linux-hardware.org/?probe=0ef0676073) | Apr 25, 2023 |
| HP            | ENVY 15                     | Notebook    | [39d32b035a](https://linux-hardware.org/?probe=39d32b035a) | Apr 25, 2023 |
| ASUSTek       | PRIME H310-PLUS             | Desktop     | [a06d7e1f82](https://linux-hardware.org/?probe=a06d7e1f82) | Apr 25, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [db176db0db](https://linux-hardware.org/?probe=db176db0db) | Apr 25, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [2f1eb3e6ee](https://linux-hardware.org/?probe=2f1eb3e6ee) | Apr 24, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [0d6740c2a8](https://linux-hardware.org/?probe=0d6740c2a8) | Apr 24, 2023 |
| Alienware     | 13 R2                       | Notebook    | [ee7a023f6d](https://linux-hardware.org/?probe=ee7a023f6d) | Apr 24, 2023 |
| G7-2011       | X79                         | Desktop     | [5070a0a7a7](https://linux-hardware.org/?probe=5070a0a7a7) | Apr 24, 2023 |
| ASRock        | A320M Pro4                  | Desktop     | [bfe26862f0](https://linux-hardware.org/?probe=bfe26862f0) | Apr 24, 2023 |
| Lenovo        | ThinkPad T480 20L50003GE    | Notebook    | [1259bb0006](https://linux-hardware.org/?probe=1259bb0006) | Apr 24, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [074135d4f4](https://linux-hardware.org/?probe=074135d4f4) | Apr 24, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [f3c853b789](https://linux-hardware.org/?probe=f3c853b789) | Apr 23, 2023 |
| ASUSTek       | AM1M-A/BR                   | Desktop     | [0b29ee62f9](https://linux-hardware.org/?probe=0b29ee62f9) | Apr 23, 2023 |
| Alienware     | 13 R3                       | Notebook    | [f04b34f41d](https://linux-hardware.org/?probe=f04b34f41d) | Apr 23, 2023 |
| Packard Be... | IPOWER G3610                | Desktop     | [05de2306b0](https://linux-hardware.org/?probe=05de2306b0) | Apr 23, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [44ca7e29c0](https://linux-hardware.org/?probe=44ca7e29c0) | Apr 23, 2023 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [cd11cc0e25](https://linux-hardware.org/?probe=cd11cc0e25) | Apr 23, 2023 |
| Dell          | Inspiron 7737               | Notebook    | [50b75a71d3](https://linux-hardware.org/?probe=50b75a71d3) | Apr 23, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [1b475eaa99](https://linux-hardware.org/?probe=1b475eaa99) | Apr 23, 2023 |
| HP            | ZBook 15                    | Notebook    | [c7ae51efcd](https://linux-hardware.org/?probe=c7ae51efcd) | Apr 22, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [f639b8e21a](https://linux-hardware.org/?probe=f639b8e21a) | Apr 22, 2023 |
| Dell          | 0FDY5C A00                  | Desktop     | [c35628b7c7](https://linux-hardware.org/?probe=c35628b7c7) | Apr 22, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [1c76d0f5a4](https://linux-hardware.org/?probe=1c76d0f5a4) | Apr 22, 2023 |
| Lenovo        | Legion S7 15IMH5 82BC       | Notebook    | [332fdb5298](https://linux-hardware.org/?probe=332fdb5298) | Apr 22, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [1ed1930799](https://linux-hardware.org/?probe=1ed1930799) | Apr 21, 2023 |
| GPU Compan... | GWTC116-2                   | Notebook    | [8f7df56d73](https://linux-hardware.org/?probe=8f7df56d73) | Apr 21, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [7215ce49dd](https://linux-hardware.org/?probe=7215ce49dd) | Apr 21, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [b5022d8a2f](https://linux-hardware.org/?probe=b5022d8a2f) | Apr 21, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [68d07ba405](https://linux-hardware.org/?probe=68d07ba405) | Apr 20, 2023 |
| Dell          | Precision M6600             | Notebook    | [e71bf9e7bb](https://linux-hardware.org/?probe=e71bf9e7bb) | Apr 20, 2023 |
| Lenovo        | ThinkPad X220 4291WF5       | Notebook    | [4c78af0e05](https://linux-hardware.org/?probe=4c78af0e05) | Apr 20, 2023 |
| Dell          | XPS 13 9343                 | Notebook    | [573d482e45](https://linux-hardware.org/?probe=573d482e45) | Apr 20, 2023 |
| HP            | Compaq 6510b (KE131ET#AK... | Notebook    | [f9415c65e9](https://linux-hardware.org/?probe=f9415c65e9) | Apr 20, 2023 |
| Dell          | Inspiron 17 7000 Series ... | Notebook    | [6222d9b2b0](https://linux-hardware.org/?probe=6222d9b2b0) | Apr 19, 2023 |
| MSI           | H110M PRO-D                 | Desktop     | [cc76c44731](https://linux-hardware.org/?probe=cc76c44731) | Apr 19, 2023 |
| HP            | Compaq 6510b (KE131ET#AK... | Notebook    | [fc27cf4b3e](https://linux-hardware.org/?probe=fc27cf4b3e) | Apr 19, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [0187ac7a0c](https://linux-hardware.org/?probe=0187ac7a0c) | Apr 19, 2023 |
| Lenovo        | ThinkPad T480s 20L8S6S30... | Notebook    | [9241adf5fb](https://linux-hardware.org/?probe=9241adf5fb) | Apr 19, 2023 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [1e8a2bbf1d](https://linux-hardware.org/?probe=1e8a2bbf1d) | Apr 19, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [eedaf9f548](https://linux-hardware.org/?probe=eedaf9f548) | Apr 19, 2023 |
| American M... | XA133PR110                  | Notebook    | [5c634b7029](https://linux-hardware.org/?probe=5c634b7029) | Apr 19, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | Notebook    | [0f058078c9](https://linux-hardware.org/?probe=0f058078c9) | Apr 19, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [33b92210c7](https://linux-hardware.org/?probe=33b92210c7) | Apr 19, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [fe26aeffdd](https://linux-hardware.org/?probe=fe26aeffdd) | Apr 19, 2023 |
| ASUSTek       | X541UJ                      | Notebook    | [1aa63436a5](https://linux-hardware.org/?probe=1aa63436a5) | Apr 19, 2023 |
| Acer          | Aspire AV15-52              | Notebook    | [e1044f40e2](https://linux-hardware.org/?probe=e1044f40e2) | Apr 18, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [4abccb30eb](https://linux-hardware.org/?probe=4abccb30eb) | Apr 18, 2023 |
| Samsung       | DT1234567890 SAMSUNG_SW_... | Desktop     | [e84a6f3538](https://linux-hardware.org/?probe=e84a6f3538) | Apr 18, 2023 |
| Acer          | Aspire E5-575               | Notebook    | [58b159ef8f](https://linux-hardware.org/?probe=58b159ef8f) | Apr 18, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | Notebook    | [c35c104c5e](https://linux-hardware.org/?probe=c35c104c5e) | Apr 18, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | Notebook    | [14df620b0a](https://linux-hardware.org/?probe=14df620b0a) | Apr 18, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [af6c719754](https://linux-hardware.org/?probe=af6c719754) | Apr 18, 2023 |
| Dell          | Inspiron 7559               | Notebook    | [9c66c608f3](https://linux-hardware.org/?probe=9c66c608f3) | Apr 18, 2023 |
| Lenovo        | ThinkPad T480 20L50003GE    | Notebook    | [e779a9606f](https://linux-hardware.org/?probe=e779a9606f) | Apr 18, 2023 |
| Dell          | 08WKV3 A00                  | Desktop     | [091f305ccb](https://linux-hardware.org/?probe=091f305ccb) | Apr 18, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [f045e3f800](https://linux-hardware.org/?probe=f045e3f800) | Apr 18, 2023 |
| Gigabyte      | G5 GE                       | Notebook    | [f1baab4be4](https://linux-hardware.org/?probe=f1baab4be4) | Apr 17, 2023 |
| MSI           | PS42 Modern 8RC             | Notebook    | [459a84f65e](https://linux-hardware.org/?probe=459a84f65e) | Apr 17, 2023 |
| American M... | XA133PR110                  | Notebook    | [08b47e43a7](https://linux-hardware.org/?probe=08b47e43a7) | Apr 17, 2023 |
| Toshiba       | Satellite E45-B             | Notebook    | [ec0bb6bfc6](https://linux-hardware.org/?probe=ec0bb6bfc6) | Apr 17, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | Desktop     | [59f6a81039](https://linux-hardware.org/?probe=59f6a81039) | Apr 17, 2023 |
| Lenovo        | Legion 7 16IAX7 82TD        | Notebook    | [8f0188b2a1](https://linux-hardware.org/?probe=8f0188b2a1) | Apr 17, 2023 |
| Dell          | Inspiron 3541               | Notebook    | [dd409790ad](https://linux-hardware.org/?probe=dd409790ad) | Apr 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [55325c372c](https://linux-hardware.org/?probe=55325c372c) | Apr 17, 2023 |
| HP            | ENVY 17                     | Notebook    | [ba2c1aae76](https://linux-hardware.org/?probe=ba2c1aae76) | Apr 17, 2023 |
| HP            | Dev One Notebook PC         | Notebook    | [5e3f0907fa](https://linux-hardware.org/?probe=5e3f0907fa) | Apr 16, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [beac478abb](https://linux-hardware.org/?probe=beac478abb) | Apr 16, 2023 |
| Chuwi         | LarkBox Pro                 | Mini pc     | [9feb6e0d59](https://linux-hardware.org/?probe=9feb6e0d59) | Apr 16, 2023 |
| ASRock        | X670E Pro RS                | Desktop     | [cfc2be8311](https://linux-hardware.org/?probe=cfc2be8311) | Apr 16, 2023 |
| ASRock        | X670E Pro RS                | Desktop     | [be0c962cda](https://linux-hardware.org/?probe=be0c962cda) | Apr 16, 2023 |
| MSI           | MPG B560I GAMING EDGE WI... | Desktop     | [8888f53504](https://linux-hardware.org/?probe=8888f53504) | Apr 16, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [3a7d52ef90](https://linux-hardware.org/?probe=3a7d52ef90) | Apr 16, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [6b126883e9](https://linux-hardware.org/?probe=6b126883e9) | Apr 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [9ac7ca1a63](https://linux-hardware.org/?probe=9ac7ca1a63) | Apr 16, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | Notebook    | [762ad80f82](https://linux-hardware.org/?probe=762ad80f82) | Apr 16, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [3b20856ccc](https://linux-hardware.org/?probe=3b20856ccc) | Apr 16, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [a0f08c4442](https://linux-hardware.org/?probe=a0f08c4442) | Apr 16, 2023 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [da31814636](https://linux-hardware.org/?probe=da31814636) | Apr 15, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [f7ce1b2ab5](https://linux-hardware.org/?probe=f7ce1b2ab5) | Apr 15, 2023 |
| Medion        | E15415                      | Notebook    | [fb905ef988](https://linux-hardware.org/?probe=fb905ef988) | Apr 15, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [1d253a4901](https://linux-hardware.org/?probe=1d253a4901) | Apr 15, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [e405d73576](https://linux-hardware.org/?probe=e405d73576) | Apr 15, 2023 |
| HP            | ZBook Firefly 15.6 inch ... | Notebook    | [f45051411c](https://linux-hardware.org/?probe=f45051411c) | Apr 15, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [aedbc43074](https://linux-hardware.org/?probe=aedbc43074) | Apr 15, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [a9d18f5eaa](https://linux-hardware.org/?probe=a9d18f5eaa) | Apr 15, 2023 |
| HP            | Pavilion g6                 | Notebook    | [a918284993](https://linux-hardware.org/?probe=a918284993) | Apr 15, 2023 |
| Dell          | 0HY9JP A02                  | Desktop     | [25a1ee5a25](https://linux-hardware.org/?probe=25a1ee5a25) | Apr 15, 2023 |
| Biostar       | A960D+V2                    | Desktop     | [da262e3956](https://linux-hardware.org/?probe=da262e3956) | Apr 14, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [c30c14f9b0](https://linux-hardware.org/?probe=c30c14f9b0) | Apr 14, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [5ab7cc057f](https://linux-hardware.org/?probe=5ab7cc057f) | Apr 14, 2023 |
| Dell          | Precision 5550              | Notebook    | [1546772c9f](https://linux-hardware.org/?probe=1546772c9f) | Apr 14, 2023 |
| Dell          | Latitude E5440              | Notebook    | [a827218c2e](https://linux-hardware.org/?probe=a827218c2e) | Apr 14, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [871fd53afd](https://linux-hardware.org/?probe=871fd53afd) | Apr 14, 2023 |
| HP            | Laptop 15z-fc000            | Notebook    | [df47336192](https://linux-hardware.org/?probe=df47336192) | Apr 14, 2023 |
| HP            | Notebook                    | Notebook    | [79541411b2](https://linux-hardware.org/?probe=79541411b2) | Apr 14, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [87b5989939](https://linux-hardware.org/?probe=87b5989939) | Apr 13, 2023 |
| Microsoft     | Surface Laptop 4            | Tablet      | [78ddf23352](https://linux-hardware.org/?probe=78ddf23352) | Apr 13, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [f57cf8ddf4](https://linux-hardware.org/?probe=f57cf8ddf4) | Apr 13, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [106963edf7](https://linux-hardware.org/?probe=106963edf7) | Apr 13, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [5a86b52121](https://linux-hardware.org/?probe=5a86b52121) | Apr 13, 2023 |
| HP            | 8433 11                     | Desktop     | [911f2844c9](https://linux-hardware.org/?probe=911f2844c9) | Apr 13, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [df59296148](https://linux-hardware.org/?probe=df59296148) | Apr 13, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [eb84ecafb4](https://linux-hardware.org/?probe=eb84ecafb4) | Apr 13, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [df185fb277](https://linux-hardware.org/?probe=df185fb277) | Apr 12, 2023 |
| System76      | Pangolin                    | Notebook    | [1750f20c8d](https://linux-hardware.org/?probe=1750f20c8d) | Apr 12, 2023 |
| System76      | Thelio thelio-r3            | Desktop     | [3acd31b3be](https://linux-hardware.org/?probe=3acd31b3be) | Apr 12, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [1f12146974](https://linux-hardware.org/?probe=1f12146974) | Apr 12, 2023 |
| Lenovo        | 3098 SDK0E50510 WIN         | Desktop     | [0d8eb6aa86](https://linux-hardware.org/?probe=0d8eb6aa86) | Apr 12, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [9aadb88a2d](https://linux-hardware.org/?probe=9aadb88a2d) | Apr 12, 2023 |
| System76      | Thelio thelio-r3            | Desktop     | [7a1d69f216](https://linux-hardware.org/?probe=7a1d69f216) | Apr 12, 2023 |
| Gigabyte      | G1.Sniper M3-CF             | Desktop     | [d3ecd3c066](https://linux-hardware.org/?probe=d3ecd3c066) | Apr 12, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [94372e3520](https://linux-hardware.org/?probe=94372e3520) | Apr 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [0120f0db62](https://linux-hardware.org/?probe=0120f0db62) | Apr 12, 2023 |
| ASRock        | X370 Gaming-ITX/ac          | Desktop     | [29ed28536e](https://linux-hardware.org/?probe=29ed28536e) | Apr 12, 2023 |
| Dell          | G3 3579                     | Notebook    | [24d10a8497](https://linux-hardware.org/?probe=24d10a8497) | Apr 12, 2023 |
| Timi          | TM1707                      | Notebook    | [0e015e68ec](https://linux-hardware.org/?probe=0e015e68ec) | Apr 12, 2023 |
| Timi          | TM1707                      | Notebook    | [b611ba24ed](https://linux-hardware.org/?probe=b611ba24ed) | Apr 12, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [4c217a8a03](https://linux-hardware.org/?probe=4c217a8a03) | Apr 11, 2023 |
| BESSTAR Te... | GB1B                        | Mini pc     | [dc66113388](https://linux-hardware.org/?probe=dc66113388) | Apr 11, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [87059322b0](https://linux-hardware.org/?probe=87059322b0) | Apr 11, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [63574c5adf](https://linux-hardware.org/?probe=63574c5adf) | Apr 11, 2023 |
| Gigabyte      | G41MT-S2                    | Desktop     | [73233d1c4c](https://linux-hardware.org/?probe=73233d1c4c) | Apr 11, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [02d670e0db](https://linux-hardware.org/?probe=02d670e0db) | Apr 11, 2023 |
| MSI           | B350 GAMING PLUS            | Desktop     | [df2f924a6e](https://linux-hardware.org/?probe=df2f924a6e) | Apr 11, 2023 |
| Samsung       | 760XDA                      | Notebook    | [bdc1648c05](https://linux-hardware.org/?probe=bdc1648c05) | Apr 11, 2023 |
| Dell          | Latitude 5590               | Notebook    | [f8f0f0125f](https://linux-hardware.org/?probe=f8f0f0125f) | Apr 11, 2023 |
| MSI           | GF63 Thin 9RCX              | Notebook    | [c48286f8a2](https://linux-hardware.org/?probe=c48286f8a2) | Apr 10, 2023 |
| MSI           | H81M-P33                    | Desktop     | [129abe0b90](https://linux-hardware.org/?probe=129abe0b90) | Apr 10, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [85a39124f3](https://linux-hardware.org/?probe=85a39124f3) | Apr 09, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [beeb850c3b](https://linux-hardware.org/?probe=beeb850c3b) | Apr 09, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [0844c71fd0](https://linux-hardware.org/?probe=0844c71fd0) | Apr 07, 2023 |
| System76      | Oryx Pro                    | Notebook    | [a221f4f9d4](https://linux-hardware.org/?probe=a221f4f9d4) | Apr 06, 2023 |
| ASRock        | B650M PG Riptide WiFi       | Desktop     | [8302310eaf](https://linux-hardware.org/?probe=8302310eaf) | Apr 06, 2023 |
| MSI           | MPG B560I GAMING EDGE WI... | Desktop     | [645fe56eb3](https://linux-hardware.org/?probe=645fe56eb3) | Apr 06, 2023 |
| MSI           | MPG B560I GAMING EDGE WI... | Desktop     | [c963121074](https://linux-hardware.org/?probe=c963121074) | Apr 06, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [06d1f0e63f](https://linux-hardware.org/?probe=06d1f0e63f) | Apr 06, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [769d886cc9](https://linux-hardware.org/?probe=769d886cc9) | Apr 05, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [de7d3ba0c0](https://linux-hardware.org/?probe=de7d3ba0c0) | Apr 05, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [d1f4197f52](https://linux-hardware.org/?probe=d1f4197f52) | Apr 05, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [eb35e0beff](https://linux-hardware.org/?probe=eb35e0beff) | Apr 05, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [d89431372f](https://linux-hardware.org/?probe=d89431372f) | Apr 05, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [87b536f504](https://linux-hardware.org/?probe=87b536f504) | Apr 05, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [add0dfc4ca](https://linux-hardware.org/?probe=add0dfc4ca) | Apr 05, 2023 |
| PS            | X570 Pro4                   | Desktop     | [f67323ef28](https://linux-hardware.org/?probe=f67323ef28) | Apr 05, 2023 |
| ASUSTek       | M4A87TD EVO                 | Desktop     | [6f3f9cf977](https://linux-hardware.org/?probe=6f3f9cf977) | Apr 05, 2023 |
| Razer         | Blade                       | Notebook    | [351fe907cb](https://linux-hardware.org/?probe=351fe907cb) | Apr 05, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [fb0dc3cc20](https://linux-hardware.org/?probe=fb0dc3cc20) | Apr 05, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [c77ef60bcc](https://linux-hardware.org/?probe=c77ef60bcc) | Apr 05, 2023 |
| Unknown       | X99-GT                      | Desktop     | [d4b6b3ebe8](https://linux-hardware.org/?probe=d4b6b3ebe8) | Apr 05, 2023 |
| HP            | Laptop 14-dq0xxx            | Notebook    | [ba87782532](https://linux-hardware.org/?probe=ba87782532) | Apr 05, 2023 |
| Lenovo        | Edge 15 80K9                | Notebook    | [911d261c1b](https://linux-hardware.org/?probe=911d261c1b) | Apr 05, 2023 |
| ASUSTek       | N76VZ                       | Notebook    | [d87006e429](https://linux-hardware.org/?probe=d87006e429) | Apr 05, 2023 |
| Samsung       | RC530/RC730                 | Notebook    | [3f886e678f](https://linux-hardware.org/?probe=3f886e678f) | Apr 05, 2023 |
| Samsung       | RC530/RC730                 | Notebook    | [43e4869357](https://linux-hardware.org/?probe=43e4869357) | Apr 05, 2023 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [58f5904dec](https://linux-hardware.org/?probe=58f5904dec) | Apr 04, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [29dc58335f](https://linux-hardware.org/?probe=29dc58335f) | Apr 04, 2023 |
| HP            | 8522 A01                    | Mini pc     | [28b79ea28b](https://linux-hardware.org/?probe=28b79ea28b) | Apr 04, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [7a5ee5da76](https://linux-hardware.org/?probe=7a5ee5da76) | Apr 04, 2023 |
| Dell          | 0DF42J A00                  | Desktop     | [056818267b](https://linux-hardware.org/?probe=056818267b) | Apr 04, 2023 |
| Dell          | Inspiron 7375               | Notebook    | [0d8465f75c](https://linux-hardware.org/?probe=0d8465f75c) | Apr 04, 2023 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [d56565f374](https://linux-hardware.org/?probe=d56565f374) | Apr 04, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [84f877fde3](https://linux-hardware.org/?probe=84f877fde3) | Apr 04, 2023 |
| ASUSTek       | E201NA                      | Notebook    | [098fb721f8](https://linux-hardware.org/?probe=098fb721f8) | Apr 04, 2023 |
| MSI           | H310M PRO-VH PLUS           | Desktop     | [606eb36d59](https://linux-hardware.org/?probe=606eb36d59) | Apr 04, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [a964b0aa55](https://linux-hardware.org/?probe=a964b0aa55) | Apr 04, 2023 |
| Razer         | Blade Stealth               | Notebook    | [2cf4a53eb5](https://linux-hardware.org/?probe=2cf4a53eb5) | Apr 04, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [98a0bf82e1](https://linux-hardware.org/?probe=98a0bf82e1) | Apr 04, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [c621d48717](https://linux-hardware.org/?probe=c621d48717) | Apr 04, 2023 |
| Dell          | Latitude E7240              | Notebook    | [fce3da8380](https://linux-hardware.org/?probe=fce3da8380) | Apr 04, 2023 |
| Unknown       | Unknown                     | Notebook    | [190b5364e1](https://linux-hardware.org/?probe=190b5364e1) | Apr 03, 2023 |
| Unknown       | Unknown                     | Notebook    | [a6a766a40a](https://linux-hardware.org/?probe=a6a766a40a) | Apr 03, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [b65273209b](https://linux-hardware.org/?probe=b65273209b) | Apr 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [9880810adc](https://linux-hardware.org/?probe=9880810adc) | Apr 03, 2023 |
| MSI           | GV62 7RE                    | Notebook    | [5d441311f4](https://linux-hardware.org/?probe=5d441311f4) | Apr 03, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [777f7d0fc4](https://linux-hardware.org/?probe=777f7d0fc4) | Apr 03, 2023 |
| MSI           | GL63 8RC                    | Notebook    | [8c90ec7da1](https://linux-hardware.org/?probe=8c90ec7da1) | Apr 03, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [f013c5ca48](https://linux-hardware.org/?probe=f013c5ca48) | Apr 03, 2023 |
| Dell          | 0KWVT8 A03                  | Desktop     | [1e66b2ab37](https://linux-hardware.org/?probe=1e66b2ab37) | Apr 03, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [edb2f4188e](https://linux-hardware.org/?probe=edb2f4188e) | Apr 03, 2023 |
| HP            | 650                         | Notebook    | [bcb4e8d60a](https://linux-hardware.org/?probe=bcb4e8d60a) | Apr 03, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [daa2099403](https://linux-hardware.org/?probe=daa2099403) | Apr 03, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [0385e01f4d](https://linux-hardware.org/?probe=0385e01f4d) | Apr 02, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [20b1ee364f](https://linux-hardware.org/?probe=20b1ee364f) | Apr 02, 2023 |
| Lenovo        | ThinkPad T470 20HES0FA03    | Notebook    | [7274c8222b](https://linux-hardware.org/?probe=7274c8222b) | Apr 02, 2023 |
| Lenovo        | ThinkPad T460p 20FXS08N0... | Notebook    | [ffcf174547](https://linux-hardware.org/?probe=ffcf174547) | Apr 02, 2023 |
| Apple         | MacBook3,1                  | Notebook    | [44f31f3094](https://linux-hardware.org/?probe=44f31f3094) | Apr 02, 2023 |
| Dell          | 0KWVT8 A03                  | Desktop     | [a700fbd33d](https://linux-hardware.org/?probe=a700fbd33d) | Apr 02, 2023 |
| MSI           | B350 GAMING PRO CARBON      | Desktop     | [0ffb7303f2](https://linux-hardware.org/?probe=0ffb7303f2) | Apr 02, 2023 |
| HP            | 0AA4h                       | Desktop     | [9b84d8c935](https://linux-hardware.org/?probe=9b84d8c935) | Apr 02, 2023 |
| Lenovo        | IdeaPadFlex 5 15IIL05 81... | Convertible | [70fb19c0db](https://linux-hardware.org/?probe=70fb19c0db) | Apr 02, 2023 |
| System76      | Kudu                        | Notebook    | [2baafe374c](https://linux-hardware.org/?probe=2baafe374c) | Apr 02, 2023 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [cf9da855fc](https://linux-hardware.org/?probe=cf9da855fc) | Apr 02, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [76a94d8c87](https://linux-hardware.org/?probe=76a94d8c87) | Apr 02, 2023 |
| Sony          | VPCSC1AFM                   | Notebook    | [854b8bfa02](https://linux-hardware.org/?probe=854b8bfa02) | Apr 01, 2023 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | Notebook    | [51c7ed9156](https://linux-hardware.org/?probe=51c7ed9156) | Apr 01, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [ab9916feea](https://linux-hardware.org/?probe=ab9916feea) | Apr 01, 2023 |
| BESSTAR Te... | HM80                        | Desktop     | [4242425ada](https://linux-hardware.org/?probe=4242425ada) | Apr 01, 2023 |
| BESSTAR Te... | HM80                        | Desktop     | [702890870e](https://linux-hardware.org/?probe=702890870e) | Apr 01, 2023 |
| Lenovo        | Slim 7 16ARH7 82UX          | Notebook    | [cca7093e15](https://linux-hardware.org/?probe=cca7093e15) | Apr 01, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [5dddcdcb25](https://linux-hardware.org/?probe=5dddcdcb25) | Apr 01, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [277d3c7f43](https://linux-hardware.org/?probe=277d3c7f43) | Apr 01, 2023 |
| Dell          | Latitude 7275               | Tablet      | [c118ca04bc](https://linux-hardware.org/?probe=c118ca04bc) | Apr 01, 2023 |
| Lenovo        | IdeaPad U310                | Notebook    | [6add75e18c](https://linux-hardware.org/?probe=6add75e18c) | Apr 01, 2023 |
| Lenovo        | 4030                        | Desktop     | [7a23fd4fb4](https://linux-hardware.org/?probe=7a23fd4fb4) | Apr 01, 2023 |
| Toshiba       | Satellite L45-B             | Notebook    | [6d4878cdbf](https://linux-hardware.org/?probe=6d4878cdbf) | Apr 01, 2023 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [f7c90851ac](https://linux-hardware.org/?probe=f7c90851ac) | Apr 01, 2023 |
| HP            | 240 G6 Notebook PC          | Notebook    | [44e093df31](https://linux-hardware.org/?probe=44e093df31) | Apr 01, 2023 |
| System76      | Lemur Pro                   | Notebook    | [5d57a3397e](https://linux-hardware.org/?probe=5d57a3397e) | Mar 31, 2023 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [fc44ad8c07](https://linux-hardware.org/?probe=fc44ad8c07) | Mar 31, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [6f4a645737](https://linux-hardware.org/?probe=6f4a645737) | Mar 31, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [61e2653466](https://linux-hardware.org/?probe=61e2653466) | Mar 31, 2023 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [11b3a7cdb1](https://linux-hardware.org/?probe=11b3a7cdb1) | Mar 31, 2023 |
| ASUSTek       | X751LD                      | Notebook    | [2ef82331de](https://linux-hardware.org/?probe=2ef82331de) | Mar 31, 2023 |
| Supermicro    | X10SLV                      | Server      | [b61612a8a8](https://linux-hardware.org/?probe=b61612a8a8) | Mar 31, 2023 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | Desktop     | [c346cf16d3](https://linux-hardware.org/?probe=c346cf16d3) | Mar 30, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [bf846cebb9](https://linux-hardware.org/?probe=bf846cebb9) | Mar 30, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [27befad01f](https://linux-hardware.org/?probe=27befad01f) | Mar 30, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [21515b7373](https://linux-hardware.org/?probe=21515b7373) | Mar 30, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [080e22fdb2](https://linux-hardware.org/?probe=080e22fdb2) | Mar 30, 2023 |
| HP            | 0AA4h                       | Desktop     | [97457bb10c](https://linux-hardware.org/?probe=97457bb10c) | Mar 30, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [af4901f141](https://linux-hardware.org/?probe=af4901f141) | Mar 30, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [cec51b833f](https://linux-hardware.org/?probe=cec51b833f) | Mar 30, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [13f35137bd](https://linux-hardware.org/?probe=13f35137bd) | Mar 30, 2023 |
| Foxconn       | 2AB1 DVT                    | Desktop     | [a9e8e4d4b0](https://linux-hardware.org/?probe=a9e8e4d4b0) | Mar 30, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [81dda92e58](https://linux-hardware.org/?probe=81dda92e58) | Mar 30, 2023 |
| Multilaser    | MLSH1H LINUX                | Notebook    | [7ee1845d96](https://linux-hardware.org/?probe=7ee1845d96) | Mar 30, 2023 |
| Multilaser    | MLSH1H LINUX                | Notebook    | [bb80f561a2](https://linux-hardware.org/?probe=bb80f561a2) | Mar 30, 2023 |
| HP            | 8433 11                     | Desktop     | [55f7473ba8](https://linux-hardware.org/?probe=55f7473ba8) | Mar 29, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [854490056d](https://linux-hardware.org/?probe=854490056d) | Mar 29, 2023 |
| HP            | ZBook 15 G5                 | Notebook    | [059358e49b](https://linux-hardware.org/?probe=059358e49b) | Mar 29, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [78046d9b99](https://linux-hardware.org/?probe=78046d9b99) | Mar 29, 2023 |
| HP            | 0AA4h                       | Desktop     | [801f843749](https://linux-hardware.org/?probe=801f843749) | Mar 29, 2023 |
| Win elemen... | M600                        | Desktop     | [7cf2343b6f](https://linux-hardware.org/?probe=7cf2343b6f) | Mar 29, 2023 |
| ASUSTek       | H81M-A/BR                   | Desktop     | [c994f20b64](https://linux-hardware.org/?probe=c994f20b64) | Mar 29, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [af48722867](https://linux-hardware.org/?probe=af48722867) | Mar 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [0667374075](https://linux-hardware.org/?probe=0667374075) | Mar 28, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [0aabfe954d](https://linux-hardware.org/?probe=0aabfe954d) | Mar 28, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [7939320fa4](https://linux-hardware.org/?probe=7939320fa4) | Mar 28, 2023 |
| Positivo      | Mobile                      | Notebook    | [60fd382fbf](https://linux-hardware.org/?probe=60fd382fbf) | Mar 28, 2023 |
| Positivo      | Mobile                      | Notebook    | [b08c430903](https://linux-hardware.org/?probe=b08c430903) | Mar 28, 2023 |
| HP            | 09F0h                       | Desktop     | [540ec71101](https://linux-hardware.org/?probe=540ec71101) | Mar 28, 2023 |
| Razer         | Blade                       | Notebook    | [ffa791eb4a](https://linux-hardware.org/?probe=ffa791eb4a) | Mar 28, 2023 |
| ASUSTek       | X751LD                      | Notebook    | [61382d0bd8](https://linux-hardware.org/?probe=61382d0bd8) | Mar 28, 2023 |
| ASRock        | H510M-HVS                   | Desktop     | [97744fad07](https://linux-hardware.org/?probe=97744fad07) | Mar 28, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [d2b4780094](https://linux-hardware.org/?probe=d2b4780094) | Mar 28, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [635309aff4](https://linux-hardware.org/?probe=635309aff4) | Mar 28, 2023 |
| ASRock        | B650M PG Riptide WiFi       | Desktop     | [f17c95f91b](https://linux-hardware.org/?probe=f17c95f91b) | Mar 28, 2023 |
| ASRock        | B650M PG Riptide WiFi       | Desktop     | [1b67e2c4fd](https://linux-hardware.org/?probe=1b67e2c4fd) | Mar 28, 2023 |
| MSI           | MPG X670E CARBON WIFI       | Desktop     | [cde470cb39](https://linux-hardware.org/?probe=cde470cb39) | Mar 28, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c4bba42d7b](https://linux-hardware.org/?probe=c4bba42d7b) | Mar 28, 2023 |
| Lenovo        | ThinkPad P50 20EQS0T400     | Notebook    | [5b4466c085](https://linux-hardware.org/?probe=5b4466c085) | Mar 28, 2023 |
| Lenovo        | ThinkPad T420 4180AP3       | Notebook    | [8ddee342c9](https://linux-hardware.org/?probe=8ddee342c9) | Mar 28, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [adee3bbdde](https://linux-hardware.org/?probe=adee3bbdde) | Mar 28, 2023 |
| MSI           | B450M BAZOOKA V2            | Desktop     | [f6236c5962](https://linux-hardware.org/?probe=f6236c5962) | Mar 27, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [5be538736f](https://linux-hardware.org/?probe=5be538736f) | Mar 27, 2023 |
| Toshiba       | Satellite C55-C             | Notebook    | [d7ec0eb4b1](https://linux-hardware.org/?probe=d7ec0eb4b1) | Mar 27, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [878fa94b87](https://linux-hardware.org/?probe=878fa94b87) | Mar 26, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [a5c200217f](https://linux-hardware.org/?probe=a5c200217f) | Mar 26, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [8ffc3ea292](https://linux-hardware.org/?probe=8ffc3ea292) | Mar 26, 2023 |
| MSI           | Z490 PLUS                   | Desktop     | [06032b5e04](https://linux-hardware.org/?probe=06032b5e04) | Mar 26, 2023 |
| Lenovo        | CRESCENTBAY SDK0J40677 W... | Desktop     | [479aff4877](https://linux-hardware.org/?probe=479aff4877) | Mar 26, 2023 |
| MSI           | GL63 8RC                    | Notebook    | [935b78c3da](https://linux-hardware.org/?probe=935b78c3da) | Mar 26, 2023 |
| Lenovo        | CRESCENTBAY SDK0J40677 W... | Desktop     | [67ddc813cf](https://linux-hardware.org/?probe=67ddc813cf) | Mar 26, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [537fc6af0e](https://linux-hardware.org/?probe=537fc6af0e) | Mar 26, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [55c29cec29](https://linux-hardware.org/?probe=55c29cec29) | Mar 26, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | Desktop     | [fc01cd79a4](https://linux-hardware.org/?probe=fc01cd79a4) | Mar 26, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [c08caf1dee](https://linux-hardware.org/?probe=c08caf1dee) | Mar 26, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [905078c7b9](https://linux-hardware.org/?probe=905078c7b9) | Mar 26, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [f6f4996c63](https://linux-hardware.org/?probe=f6f4996c63) | Mar 26, 2023 |
| Dell          | Latitude E7240              | Notebook    | [3d91b46fda](https://linux-hardware.org/?probe=3d91b46fda) | Mar 26, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [3f3967267f](https://linux-hardware.org/?probe=3f3967267f) | Mar 26, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [61897b32de](https://linux-hardware.org/?probe=61897b32de) | Mar 25, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [0f7d28bd43](https://linux-hardware.org/?probe=0f7d28bd43) | Mar 25, 2023 |
| HP            | Spectre Laptop 13-af0xx     | Notebook    | [6fdc683220](https://linux-hardware.org/?probe=6fdc683220) | Mar 25, 2023 |
| MSI           | Katana GF66 12UG            | Notebook    | [9e03ac14c0](https://linux-hardware.org/?probe=9e03ac14c0) | Mar 25, 2023 |
| Intel         | NUC10i3FNB K61362-305       | Mini pc     | [26c0bb67b6](https://linux-hardware.org/?probe=26c0bb67b6) | Mar 25, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [811be842de](https://linux-hardware.org/?probe=811be842de) | Mar 25, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [21c3ce9508](https://linux-hardware.org/?probe=21c3ce9508) | Mar 24, 2023 |
| Dell          | 0PC5F7 A01                  | Desktop     | [61550296b7](https://linux-hardware.org/?probe=61550296b7) | Mar 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [ac415822b8](https://linux-hardware.org/?probe=ac415822b8) | Mar 24, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [ad0e5c0483](https://linux-hardware.org/?probe=ad0e5c0483) | Mar 24, 2023 |
| Dell          | Latitude 5420               | Notebook    | [e6afbbee47](https://linux-hardware.org/?probe=e6afbbee47) | Mar 24, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [f78f58795c](https://linux-hardware.org/?probe=f78f58795c) | Mar 24, 2023 |
| HP            | 212B                        | Desktop     | [266912cedd](https://linux-hardware.org/?probe=266912cedd) | Mar 24, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [f5cbf68e6d](https://linux-hardware.org/?probe=f5cbf68e6d) | Mar 24, 2023 |
| Alienware     | 17 R4                       | Notebook    | [3c456dc309](https://linux-hardware.org/?probe=3c456dc309) | Mar 24, 2023 |
| GPU Compan... | GWTN141-10                  | Notebook    | [9007c1d23f](https://linux-hardware.org/?probe=9007c1d23f) | Mar 24, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Notebook    | [f8f47e3220](https://linux-hardware.org/?probe=f8f47e3220) | Mar 23, 2023 |
| Dell          | Precision 7710              | Notebook    | [25a4797475](https://linux-hardware.org/?probe=25a4797475) | Mar 23, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [09fec047e4](https://linux-hardware.org/?probe=09fec047e4) | Mar 23, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [3a75d7fb8d](https://linux-hardware.org/?probe=3a75d7fb8d) | Mar 23, 2023 |
| MSI           | MPG Z590 GAMING FORCE       | Desktop     | [7a3319972e](https://linux-hardware.org/?probe=7a3319972e) | Mar 23, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [c06eaca849](https://linux-hardware.org/?probe=c06eaca849) | Mar 23, 2023 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [aba9609828](https://linux-hardware.org/?probe=aba9609828) | Mar 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [f6580b20d3](https://linux-hardware.org/?probe=f6580b20d3) | Mar 22, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [dab7a6edbc](https://linux-hardware.org/?probe=dab7a6edbc) | Mar 22, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [bc6e3fa274](https://linux-hardware.org/?probe=bc6e3fa274) | Mar 22, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [d458338d97](https://linux-hardware.org/?probe=d458338d97) | Mar 22, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [627590f38c](https://linux-hardware.org/?probe=627590f38c) | Mar 22, 2023 |
| Lenovo        | ThinkPad Twist 33472HU      | Notebook    | [a49ece0e6c](https://linux-hardware.org/?probe=a49ece0e6c) | Mar 22, 2023 |
| Lenovo        | ThinkPad Twist 33472HU      | Notebook    | [315f2256c6](https://linux-hardware.org/?probe=315f2256c6) | Mar 22, 2023 |
| Dell          | 0RK936                      | Desktop     | [af3e7f60cb](https://linux-hardware.org/?probe=af3e7f60cb) | Mar 22, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [b616377b13](https://linux-hardware.org/?probe=b616377b13) | Mar 22, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [aff8d829e0](https://linux-hardware.org/?probe=aff8d829e0) | Mar 22, 2023 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [99fe9f96c6](https://linux-hardware.org/?probe=99fe9f96c6) | Mar 22, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [af60ed4cde](https://linux-hardware.org/?probe=af60ed4cde) | Mar 22, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [3b3376e72c](https://linux-hardware.org/?probe=3b3376e72c) | Mar 21, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [b4c65fead7](https://linux-hardware.org/?probe=b4c65fead7) | Mar 21, 2023 |
| HUAWEI        | KPL-W0X                     | Notebook    | [afc1ff125b](https://linux-hardware.org/?probe=afc1ff125b) | Mar 21, 2023 |
| Lenovo        | ThinkPad T420 4180AP3       | Notebook    | [3c100c55be](https://linux-hardware.org/?probe=3c100c55be) | Mar 21, 2023 |
| Lenovo        | ThinkPad T420 4180AP3       | Notebook    | [039724e2c2](https://linux-hardware.org/?probe=039724e2c2) | Mar 21, 2023 |
| Dell          | G15 5511                    | Notebook    | [6d71997e08](https://linux-hardware.org/?probe=6d71997e08) | Mar 21, 2023 |
| Dell          | XPS L421X                   | Notebook    | [fd54af9534](https://linux-hardware.org/?probe=fd54af9534) | Mar 21, 2023 |
| Dell          | 0RK936                      | Desktop     | [6c2680e4e9](https://linux-hardware.org/?probe=6c2680e4e9) | Mar 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [afe8ca841c](https://linux-hardware.org/?probe=afe8ca841c) | Mar 21, 2023 |
| Acer          | Aspire 5349                 | Notebook    | [c0f5810e5c](https://linux-hardware.org/?probe=c0f5810e5c) | Mar 21, 2023 |
| MSI           | Prestige 14Evo A11M         | Notebook    | [cac8d6b991](https://linux-hardware.org/?probe=cac8d6b991) | Mar 21, 2023 |
| HP            | Dev One Notebook PC         | Notebook    | [d6ff521952](https://linux-hardware.org/?probe=d6ff521952) | Mar 21, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [16253cadcf](https://linux-hardware.org/?probe=16253cadcf) | Mar 21, 2023 |
| Acer          | Nitro AN517-55              | Notebook    | [d6393f5710](https://linux-hardware.org/?probe=d6393f5710) | Mar 21, 2023 |
| HP            | Dev One Notebook PC         | Notebook    | [404c84b0ea](https://linux-hardware.org/?probe=404c84b0ea) | Mar 21, 2023 |
| ASUSTek       | PRIME X670E-PRO WIFI        | Desktop     | [d4e033725b](https://linux-hardware.org/?probe=d4e033725b) | Mar 21, 2023 |
| Acer          | Nitro AN517-55              | Notebook    | [edf722e245](https://linux-hardware.org/?probe=edf722e245) | Mar 21, 2023 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [5ea7504472](https://linux-hardware.org/?probe=5ea7504472) | Mar 21, 2023 |
| Gigabyte      | A320M-S2H-CF                | Notebook    | [2ff2eab844](https://linux-hardware.org/?probe=2ff2eab844) | Mar 21, 2023 |
| ASUSTek       | G74Sx                       | Notebook    | [d2b90b7d2f](https://linux-hardware.org/?probe=d2b90b7d2f) | Mar 21, 2023 |
| HP            | ZBook Power 15.6 inch G9... | Notebook    | [2ef051fd19](https://linux-hardware.org/?probe=2ef051fd19) | Mar 20, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [48de9eb9e3](https://linux-hardware.org/?probe=48de9eb9e3) | Mar 20, 2023 |
| ASUSTek       | PRIME X299-DELUXE II        | Desktop     | [b133c68356](https://linux-hardware.org/?probe=b133c68356) | Mar 20, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [afcac034a9](https://linux-hardware.org/?probe=afcac034a9) | Mar 20, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [d08f174747](https://linux-hardware.org/?probe=d08f174747) | Mar 20, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Notebook    | [c9b4e3cf00](https://linux-hardware.org/?probe=c9b4e3cf00) | Mar 20, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [3fe3c818f7](https://linux-hardware.org/?probe=3fe3c818f7) | Mar 20, 2023 |
| Dell          | Latitude 5590               | Notebook    | [49922a3223](https://linux-hardware.org/?probe=49922a3223) | Mar 19, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [55dc5e3ef4](https://linux-hardware.org/?probe=55dc5e3ef4) | Mar 19, 2023 |
| Intel         | NUC11PHBi7 M26151-404       | Mini pc     | [22290c7abf](https://linux-hardware.org/?probe=22290c7abf) | Mar 19, 2023 |
| Gigabyte      | Z97X-Gaming 7               | Desktop     | [6681949ccc](https://linux-hardware.org/?probe=6681949ccc) | Mar 19, 2023 |
| MSI           | PS42 8M                     | Notebook    | [aad18852f4](https://linux-hardware.org/?probe=aad18852f4) | Mar 19, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [d0079fa594](https://linux-hardware.org/?probe=d0079fa594) | Mar 19, 2023 |
| ASUSTek       | G74Sx                       | Notebook    | [f7f92408dc](https://linux-hardware.org/?probe=f7f92408dc) | Mar 19, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [6b6ceb1a1a](https://linux-hardware.org/?probe=6b6ceb1a1a) | Mar 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [e3410282c5](https://linux-hardware.org/?probe=e3410282c5) | Mar 19, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [c462ccc41a](https://linux-hardware.org/?probe=c462ccc41a) | Mar 19, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [0139691951](https://linux-hardware.org/?probe=0139691951) | Mar 19, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [22e0286a24](https://linux-hardware.org/?probe=22e0286a24) | Mar 19, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [0018c1237d](https://linux-hardware.org/?probe=0018c1237d) | Mar 19, 2023 |
| Dell          | 0WMJ54 A00                  | Desktop     | [bcb1a34cf2](https://linux-hardware.org/?probe=bcb1a34cf2) | Mar 19, 2023 |
| ASUSTek       | S551LB                      | Notebook    | [7d4485326f](https://linux-hardware.org/?probe=7d4485326f) | Mar 18, 2023 |
| GPU Compan... | GWTN141-10                  | Notebook    | [ff8db61ccf](https://linux-hardware.org/?probe=ff8db61ccf) | Mar 18, 2023 |
| ASUSTek       | X540LJ                      | Notebook    | [4eab8887fa](https://linux-hardware.org/?probe=4eab8887fa) | Mar 18, 2023 |
| ASUSTek       | X540LJ                      | Notebook    | [b3bf824f3a](https://linux-hardware.org/?probe=b3bf824f3a) | Mar 18, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Notebook    | [dd296a8801](https://linux-hardware.org/?probe=dd296a8801) | Mar 18, 2023 |
| Lenovo        | ThinkPad T480 20L6S11N00    | Notebook    | [60d80937ea](https://linux-hardware.org/?probe=60d80937ea) | Mar 18, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [dc411c9ce3](https://linux-hardware.org/?probe=dc411c9ce3) | Mar 18, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [91ae5652cc](https://linux-hardware.org/?probe=91ae5652cc) | Mar 18, 2023 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [274f959cfc](https://linux-hardware.org/?probe=274f959cfc) | Mar 17, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [c4bebd7028](https://linux-hardware.org/?probe=c4bebd7028) | Mar 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [2389fcea33](https://linux-hardware.org/?probe=2389fcea33) | Mar 17, 2023 |
| Dell          | Latitude E7240              | Notebook    | [cbcae7df75](https://linux-hardware.org/?probe=cbcae7df75) | Mar 17, 2023 |
| Intel         | X99 V1.x                    | Desktop     | [9b471dcdcf](https://linux-hardware.org/?probe=9b471dcdcf) | Mar 17, 2023 |
| Positivo      | N1250                       | Notebook    | [e5ee22876a](https://linux-hardware.org/?probe=e5ee22876a) | Mar 17, 2023 |
| Gigabyte      | X399 DESIGNARE EX-CF        | Desktop     | [557a99333f](https://linux-hardware.org/?probe=557a99333f) | Mar 17, 2023 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [27356d58d5](https://linux-hardware.org/?probe=27356d58d5) | Mar 17, 2023 |
| HP            | 843F                        | Desktop     | [e444e0d76a](https://linux-hardware.org/?probe=e444e0d76a) | Mar 17, 2023 |
| HP            | ProBook 4530s               | Notebook    | [f0abd32fe4](https://linux-hardware.org/?probe=f0abd32fe4) | Mar 17, 2023 |
| Lenovo        | G40-80 80JE                 | Notebook    | [a7a6cc1ab5](https://linux-hardware.org/?probe=a7a6cc1ab5) | Mar 17, 2023 |
| Lenovo        | G40-80 80JE                 | Notebook    | [204994be7f](https://linux-hardware.org/?probe=204994be7f) | Mar 17, 2023 |
| TUXEDO        | Pulse 14 Gen1               | Notebook    | [525b267c31](https://linux-hardware.org/?probe=525b267c31) | Mar 17, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [b20fcd6878](https://linux-hardware.org/?probe=b20fcd6878) | Mar 17, 2023 |
| Toshiba       | Satellite Pro C50-A-1E2     | Notebook    | [a1adc8641d](https://linux-hardware.org/?probe=a1adc8641d) | Mar 17, 2023 |
| Toshiba       | Satellite Pro C50-A-1E2     | Notebook    | [a0eea87e02](https://linux-hardware.org/?probe=a0eea87e02) | Mar 17, 2023 |
| Unknown       | Unknown                     | Notebook    | [3eb0bf05b4](https://linux-hardware.org/?probe=3eb0bf05b4) | Mar 17, 2023 |
| Lenovo        | ThinkPad T460s 20FAS0RP0... | Notebook    | [f901058202](https://linux-hardware.org/?probe=f901058202) | Mar 16, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [d6f5cd9505](https://linux-hardware.org/?probe=d6f5cd9505) | Mar 16, 2023 |
| Dell          | 02GDWG A00                  | Desktop     | [c81ac4434e](https://linux-hardware.org/?probe=c81ac4434e) | Mar 16, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81FN      | Notebook    | [5f48c46d68](https://linux-hardware.org/?probe=5f48c46d68) | Mar 16, 2023 |
| Microsoft     | Surface Book                | Tablet      | [d5cd9be69a](https://linux-hardware.org/?probe=d5cd9be69a) | Mar 16, 2023 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [67d6333f85](https://linux-hardware.org/?probe=67d6333f85) | Mar 15, 2023 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [59a304e790](https://linux-hardware.org/?probe=59a304e790) | Mar 15, 2023 |
| Acer          | Aspire A715-42G             | Notebook    | [8bdae79f7a](https://linux-hardware.org/?probe=8bdae79f7a) | Mar 15, 2023 |
| Lenovo        | ThinkPad T440p 20AWS19P0... | Notebook    | [6a2d338526](https://linux-hardware.org/?probe=6a2d338526) | Mar 15, 2023 |
| ASUSTek       | Z87-K                       | Desktop     | [fe2d844bfb](https://linux-hardware.org/?probe=fe2d844bfb) | Mar 15, 2023 |
| Razer         | Blade Stealth 13 (Early ... | Notebook    | [eb1d71edb4](https://linux-hardware.org/?probe=eb1d71edb4) | Mar 15, 2023 |
| HCL Infosy... | HCL ME LAPTOP               | Notebook    | [af254fca4d](https://linux-hardware.org/?probe=af254fca4d) | Mar 15, 2023 |
| SAGER         | X8100                       | Notebook    | [90aaefeb9e](https://linux-hardware.org/?probe=90aaefeb9e) | Mar 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [88c4c221af](https://linux-hardware.org/?probe=88c4c221af) | Mar 15, 2023 |
| Huanan        | X99-AD3 GAMING V2.0         | Desktop     | [0586633e29](https://linux-hardware.org/?probe=0586633e29) | Mar 15, 2023 |
| ASUSTek       | PRIME Z790-P WIFI D4        | Desktop     | [e8bbe7a962](https://linux-hardware.org/?probe=e8bbe7a962) | Mar 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [0c74f7b048](https://linux-hardware.org/?probe=0c74f7b048) | Mar 15, 2023 |
| System76      | Pangolin                    | Notebook    | [4f39796131](https://linux-hardware.org/?probe=4f39796131) | Mar 15, 2023 |
| Dell          | Latitude E7240              | Notebook    | [d4ed345a47](https://linux-hardware.org/?probe=d4ed345a47) | Mar 14, 2023 |
| ASRock        | B550 Extreme4               | Desktop     | [9a139b5bad](https://linux-hardware.org/?probe=9a139b5bad) | Mar 14, 2023 |
| Lenovo        | ThinkPad T450s 20BWS14G0... | Notebook    | [1161c07721](https://linux-hardware.org/?probe=1161c07721) | Mar 14, 2023 |
| Sony          | VPCZ12V9R                   | Notebook    | [28be5f7f2b](https://linux-hardware.org/?probe=28be5f7f2b) | Mar 14, 2023 |
| Dell          | Latitude E7240              | Notebook    | [4a7d442938](https://linux-hardware.org/?probe=4a7d442938) | Mar 14, 2023 |
| HP            | EliteBook 8560w             | Notebook    | [44d9ce8acb](https://linux-hardware.org/?probe=44d9ce8acb) | Mar 14, 2023 |
| HP            | EliteBook 8560w             | Notebook    | [986fe8c418](https://linux-hardware.org/?probe=986fe8c418) | Mar 14, 2023 |
| Gigabyte      | X58A-UD7                    | Desktop     | [95248fc9a0](https://linux-hardware.org/?probe=95248fc9a0) | Mar 14, 2023 |
| Dell          | 0RK936                      | Desktop     | [59cbc1f071](https://linux-hardware.org/?probe=59cbc1f071) | Mar 14, 2023 |
| Fujitsu       | LIFEBOOK E5512A             | Notebook    | [ae9f2da5a4](https://linux-hardware.org/?probe=ae9f2da5a4) | Mar 14, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [874706952d](https://linux-hardware.org/?probe=874706952d) | Mar 14, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [de22b8a7e6](https://linux-hardware.org/?probe=de22b8a7e6) | Mar 14, 2023 |
| Dell          | Inspiron 7348               | Notebook    | [7459d24035](https://linux-hardware.org/?probe=7459d24035) | Mar 13, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f5215489c7](https://linux-hardware.org/?probe=f5215489c7) | Mar 13, 2023 |
| ASUSTek       | H97-PRO                     | Desktop     | [b03c056ee1](https://linux-hardware.org/?probe=b03c056ee1) | Mar 13, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [b93a4bdcbb](https://linux-hardware.org/?probe=b93a4bdcbb) | Mar 13, 2023 |
| Acer          | Aspire 4530                 | Notebook    | [84f4733a96](https://linux-hardware.org/?probe=84f4733a96) | Mar 13, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [7f2ecd927d](https://linux-hardware.org/?probe=7f2ecd927d) | Mar 13, 2023 |
| Gateway       | WG43M                       | Desktop     | [c1ab165971](https://linux-hardware.org/?probe=c1ab165971) | Mar 13, 2023 |
| Apple         | MacBookPro15,1              | Notebook    | [663f73a08e](https://linux-hardware.org/?probe=663f73a08e) | Mar 13, 2023 |
| Apple         | MacBookPro15,1              | Notebook    | [5d1a30091e](https://linux-hardware.org/?probe=5d1a30091e) | Mar 13, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [a826b1cd32](https://linux-hardware.org/?probe=a826b1cd32) | Mar 13, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [0e2618e3ea](https://linux-hardware.org/?probe=0e2618e3ea) | Mar 12, 2023 |
| Dell          | 0DFRFW A01                  | Desktop     | [1b8b00dbc5](https://linux-hardware.org/?probe=1b8b00dbc5) | Mar 12, 2023 |
| Lenovo        | ThinkPad T480s 20L8S7AS0... | Notebook    | [87ef2f6efb](https://linux-hardware.org/?probe=87ef2f6efb) | Mar 12, 2023 |
| HP            | ProLiant DL380 G7           | Server      | [9911027e53](https://linux-hardware.org/?probe=9911027e53) | Mar 12, 2023 |
| HUAWEI        | NBM-WXX9                    | Notebook    | [27b710cd68](https://linux-hardware.org/?probe=27b710cd68) | Mar 12, 2023 |
| Google        | Kefka                       | Notebook    | [4a54e34e44](https://linux-hardware.org/?probe=4a54e34e44) | Mar 12, 2023 |
| ASUSTek       | ZenBook UX434IQ_Q407IQ      | Notebook    | [7090114437](https://linux-hardware.org/?probe=7090114437) | Mar 12, 2023 |
| Dell          | Inspiron 5452               | Notebook    | [2c8ca0e296](https://linux-hardware.org/?probe=2c8ca0e296) | Mar 12, 2023 |
| Gigabyte      | Z590I AORUS ULTRA           | Desktop     | [47ea9647d3](https://linux-hardware.org/?probe=47ea9647d3) | Mar 12, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [75fc2c0a15](https://linux-hardware.org/?probe=75fc2c0a15) | Mar 12, 2023 |
| Positivo B... | VJFE41F11X-XXXXXX           | Notebook    | [99f410d801](https://linux-hardware.org/?probe=99f410d801) | Mar 11, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | Notebook    | [e101a1c94c](https://linux-hardware.org/?probe=e101a1c94c) | Mar 11, 2023 |
| Acer          | Aspire X1935                | Desktop     | [6846ecd490](https://linux-hardware.org/?probe=6846ecd490) | Mar 11, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [d8cf10f11d](https://linux-hardware.org/?probe=d8cf10f11d) | Mar 11, 2023 |
| HP            | ZBook 17                    | Notebook    | [a775bc33c5](https://linux-hardware.org/?probe=a775bc33c5) | Mar 11, 2023 |
| Maibenben     | P748                        | Notebook    | [a44d1bb8e4](https://linux-hardware.org/?probe=a44d1bb8e4) | Mar 11, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [39cc207ce7](https://linux-hardware.org/?probe=39cc207ce7) | Mar 11, 2023 |
| Lenovo        | ThinkPad L440 20ASS0ET00    | Notebook    | [2ac6dfff4f](https://linux-hardware.org/?probe=2ac6dfff4f) | Mar 11, 2023 |
| GPD           | G1619-04                    | Notebook    | [302ff30130](https://linux-hardware.org/?probe=302ff30130) | Mar 11, 2023 |
| GPD           | G1619-04                    | Notebook    | [d8f5b9eec9](https://linux-hardware.org/?probe=d8f5b9eec9) | Mar 11, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [8736fd04a8](https://linux-hardware.org/?probe=8736fd04a8) | Mar 11, 2023 |
| Dell          | 0KC9NP A00                  | Desktop     | [873a2bf50c](https://linux-hardware.org/?probe=873a2bf50c) | Mar 11, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [9535f3676b](https://linux-hardware.org/?probe=9535f3676b) | Mar 10, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [fca941c098](https://linux-hardware.org/?probe=fca941c098) | Mar 10, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Notebook    | [96f4bd0a52](https://linux-hardware.org/?probe=96f4bd0a52) | Mar 10, 2023 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [ccba86bda3](https://linux-hardware.org/?probe=ccba86bda3) | Mar 10, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Notebook    | [969ab4279f](https://linux-hardware.org/?probe=969ab4279f) | Mar 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [c44f0eab3e](https://linux-hardware.org/?probe=c44f0eab3e) | Mar 10, 2023 |
| Lenovo        | ThinkPad T440p 20AWS19P0... | Notebook    | [44867c946f](https://linux-hardware.org/?probe=44867c946f) | Mar 10, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [dbdadff4f2](https://linux-hardware.org/?probe=dbdadff4f2) | Mar 10, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [50dd87563b](https://linux-hardware.org/?probe=50dd87563b) | Mar 10, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [e183f14e7e](https://linux-hardware.org/?probe=e183f14e7e) | Mar 10, 2023 |
| Samsung       | R430/R480/R440              | Notebook    | [cdb2525b51](https://linux-hardware.org/?probe=cdb2525b51) | Mar 10, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [410a5a70f3](https://linux-hardware.org/?probe=410a5a70f3) | Mar 10, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | Notebook    | [eac4ae85a4](https://linux-hardware.org/?probe=eac4ae85a4) | Mar 10, 2023 |
| Positivo      | POS-PIQ77CL                 | Desktop     | [789838055a](https://linux-hardware.org/?probe=789838055a) | Mar 10, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [baffc24bef](https://linux-hardware.org/?probe=baffc24bef) | Mar 10, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [214efb1e94](https://linux-hardware.org/?probe=214efb1e94) | Mar 09, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [187761b57d](https://linux-hardware.org/?probe=187761b57d) | Mar 09, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [4e1196658a](https://linux-hardware.org/?probe=4e1196658a) | Mar 09, 2023 |
| HP            | ENVY Notebook               | Notebook    | [8a063efa19](https://linux-hardware.org/?probe=8a063efa19) | Mar 09, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [670e89da85](https://linux-hardware.org/?probe=670e89da85) | Mar 09, 2023 |
| Gigabyte      | H110M-DS2V DDR3-CF          | Desktop     | [d101f34459](https://linux-hardware.org/?probe=d101f34459) | Mar 09, 2023 |
| HP            | ProLiant DL360p Gen8        | Server      | [b483cfbad7](https://linux-hardware.org/?probe=b483cfbad7) | Mar 09, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | Notebook    | [a8d1bd3e81](https://linux-hardware.org/?probe=a8d1bd3e81) | Mar 09, 2023 |
| MSI           | X58 PLATINUM SLI            | Desktop     | [c8875fb17f](https://linux-hardware.org/?probe=c8875fb17f) | Mar 08, 2023 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | Notebook    | [7805fe229d](https://linux-hardware.org/?probe=7805fe229d) | Mar 08, 2023 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [46fa9eab7d](https://linux-hardware.org/?probe=46fa9eab7d) | Mar 08, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [b99222314c](https://linux-hardware.org/?probe=b99222314c) | Mar 08, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [4f64764c75](https://linux-hardware.org/?probe=4f64764c75) | Mar 08, 2023 |
| Dell          | 051FJ8 A02                  | Desktop     | [4c15877e95](https://linux-hardware.org/?probe=4c15877e95) | Mar 08, 2023 |
| Google        | Bobba                       | Notebook    | [01d8f57c7e](https://linux-hardware.org/?probe=01d8f57c7e) | Mar 08, 2023 |
| Dell          | 0KWVT8 A03                  | Desktop     | [6ddf3ecd86](https://linux-hardware.org/?probe=6ddf3ecd86) | Mar 08, 2023 |
| ASRock        | 890GX Extreme3              | Desktop     | [4d59bfb158](https://linux-hardware.org/?probe=4d59bfb158) | Mar 08, 2023 |
| Lenovo        | IdeaPad U310                | Notebook    | [f666446ecb](https://linux-hardware.org/?probe=f666446ecb) | Mar 07, 2023 |
| HP            | 83E9                        | Desktop     | [9a756f9158](https://linux-hardware.org/?probe=9a756f9158) | Mar 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [3ff5ff8f2d](https://linux-hardware.org/?probe=3ff5ff8f2d) | Mar 07, 2023 |
| ASRock        | G41M-GS3                    | Desktop     | [9e11e1f2af](https://linux-hardware.org/?probe=9e11e1f2af) | Mar 07, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | Notebook    | [3b02985778](https://linux-hardware.org/?probe=3b02985778) | Mar 07, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | Notebook    | [e6e0d7226d](https://linux-hardware.org/?probe=e6e0d7226d) | Mar 07, 2023 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [8c709c4723](https://linux-hardware.org/?probe=8c709c4723) | Mar 07, 2023 |
| HP            | Dev One Notebook PC         | Notebook    | [4a698cb3eb](https://linux-hardware.org/?probe=4a698cb3eb) | Mar 07, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [8a6c736217](https://linux-hardware.org/?probe=8a6c736217) | Mar 07, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [12954ccbdb](https://linux-hardware.org/?probe=12954ccbdb) | Mar 07, 2023 |
| Google        | Lillipup                    | Notebook    | [b924f92de8](https://linux-hardware.org/?probe=b924f92de8) | Mar 07, 2023 |
| HP            | Dev One Notebook PC         | Notebook    | [5a03b7e11e](https://linux-hardware.org/?probe=5a03b7e11e) | Mar 07, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [bef545e821](https://linux-hardware.org/?probe=bef545e821) | Mar 07, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [bfc1bf412e](https://linux-hardware.org/?probe=bfc1bf412e) | Mar 06, 2023 |
| Dell          | Inspiron 16 7610            | Notebook    | [625691c490](https://linux-hardware.org/?probe=625691c490) | Mar 06, 2023 |
| Dell          | Inspiron 16 7610            | Notebook    | [66b4f88fb7](https://linux-hardware.org/?probe=66b4f88fb7) | Mar 06, 2023 |
| HP            | EliteBook x360 1040 G8 N... | Convertible | [5656c3015d](https://linux-hardware.org/?probe=5656c3015d) | Mar 06, 2023 |
| HP            | 3115m                       | Notebook    | [87abd0ac9d](https://linux-hardware.org/?probe=87abd0ac9d) | Mar 06, 2023 |
| Dell          | G7 7588                     | Notebook    | [a50e6bef64](https://linux-hardware.org/?probe=a50e6bef64) | Mar 06, 2023 |
| HUAWEI        | KPL-W0X                     | Notebook    | [76ebbe553f](https://linux-hardware.org/?probe=76ebbe553f) | Mar 06, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [ae4d8e9128](https://linux-hardware.org/?probe=ae4d8e9128) | Mar 06, 2023 |
| MSI           | Vector GP76 12UHSO          | Notebook    | [e82fbd8c0a](https://linux-hardware.org/?probe=e82fbd8c0a) | Mar 06, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [da3b20e7c1](https://linux-hardware.org/?probe=da3b20e7c1) | Mar 06, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [baff849073](https://linux-hardware.org/?probe=baff849073) | Mar 05, 2023 |
| HP            | ProBook 450 G1              | Notebook    | [a6c8ba1040](https://linux-hardware.org/?probe=a6c8ba1040) | Mar 05, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [eb3f7a337f](https://linux-hardware.org/?probe=eb3f7a337f) | Mar 05, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [fef18d1795](https://linux-hardware.org/?probe=fef18d1795) | Mar 05, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [779113ef3c](https://linux-hardware.org/?probe=779113ef3c) | Mar 05, 2023 |
| HP            | Pavilion 15                 | Notebook    | [0c4050d1ef](https://linux-hardware.org/?probe=0c4050d1ef) | Mar 05, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | Notebook    | [ff4621a345](https://linux-hardware.org/?probe=ff4621a345) | Mar 05, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [b75483941a](https://linux-hardware.org/?probe=b75483941a) | Mar 05, 2023 |
| Dell          | Latitude 5420               | Notebook    | [ea5ac72a44](https://linux-hardware.org/?probe=ea5ac72a44) | Mar 05, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [a655c49d8b](https://linux-hardware.org/?probe=a655c49d8b) | Mar 05, 2023 |
| HP            | 339A                        | Desktop     | [a2af229dad](https://linux-hardware.org/?probe=a2af229dad) | Mar 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [b73251069c](https://linux-hardware.org/?probe=b73251069c) | Mar 05, 2023 |
| Gigabyte      | Z87X-UD4H-CF                | Desktop     | [efd2d0c074](https://linux-hardware.org/?probe=efd2d0c074) | Mar 05, 2023 |
| HP            | ProBook 450 G1              | Notebook    | [ca5a019457](https://linux-hardware.org/?probe=ca5a019457) | Mar 04, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [ba908d3339](https://linux-hardware.org/?probe=ba908d3339) | Mar 04, 2023 |
| MSI           | B350 GAMING PLUS            | Desktop     | [c3d6a142c0](https://linux-hardware.org/?probe=c3d6a142c0) | Mar 04, 2023 |
| Lenovo        | ThinkPad E490 20N8005JMH    | Notebook    | [26ca476e1a](https://linux-hardware.org/?probe=26ca476e1a) | Mar 04, 2023 |
| Dell          | System XPS L321X            | Notebook    | [24d0d12eca](https://linux-hardware.org/?probe=24d0d12eca) | Mar 04, 2023 |
| Lenovo        | ThinkPad X270 20HN001RUS    | Notebook    | [ccda7b2155](https://linux-hardware.org/?probe=ccda7b2155) | Mar 04, 2023 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [87cdc5bd5a](https://linux-hardware.org/?probe=87cdc5bd5a) | Mar 04, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [ca004eceae](https://linux-hardware.org/?probe=ca004eceae) | Mar 03, 2023 |
| Acer          | Aspire M3970                | Desktop     | [2708d5fa99](https://linux-hardware.org/?probe=2708d5fa99) | Mar 03, 2023 |
| Gigabyte      | AORUS 17 XE4                | Notebook    | [6f6750ee73](https://linux-hardware.org/?probe=6f6750ee73) | Mar 03, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [db92a5f137](https://linux-hardware.org/?probe=db92a5f137) | Mar 03, 2023 |
| ZOTAC         | ZBOX-ECM73070C/53060C       | Mini pc     | [1a24f06457](https://linux-hardware.org/?probe=1a24f06457) | Mar 03, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [9ce5a599cd](https://linux-hardware.org/?probe=9ce5a599cd) | Mar 03, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [141faab02f](https://linux-hardware.org/?probe=141faab02f) | Mar 03, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [c2d6b5218e](https://linux-hardware.org/?probe=c2d6b5218e) | Mar 03, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [840dab3a7c](https://linux-hardware.org/?probe=840dab3a7c) | Mar 03, 2023 |
| Biostar       | H81MHV3 5.0                 | Desktop     | [6ea9159a52](https://linux-hardware.org/?probe=6ea9159a52) | Mar 03, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [8ce5103cac](https://linux-hardware.org/?probe=8ce5103cac) | Mar 03, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS0... | Notebook    | [e73235d592](https://linux-hardware.org/?probe=e73235d592) | Mar 03, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [62c37af17b](https://linux-hardware.org/?probe=62c37af17b) | Mar 03, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [a23a00a71e](https://linux-hardware.org/?probe=a23a00a71e) | Mar 02, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [2c6ad91981](https://linux-hardware.org/?probe=2c6ad91981) | Mar 02, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [f942bae731](https://linux-hardware.org/?probe=f942bae731) | Mar 02, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [7deb9825c2](https://linux-hardware.org/?probe=7deb9825c2) | Mar 02, 2023 |
| ASRockRack    | X570D4U                     | Desktop     | [9c4b25d5dc](https://linux-hardware.org/?probe=9c4b25d5dc) | Mar 02, 2023 |
| Acer          | Swift SF314-54              | Notebook    | [62defb89e3](https://linux-hardware.org/?probe=62defb89e3) | Mar 02, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [4207bf1ee6](https://linux-hardware.org/?probe=4207bf1ee6) | Mar 02, 2023 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [ed4f0e394a](https://linux-hardware.org/?probe=ed4f0e394a) | Mar 02, 2023 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [5b94fc8fa8](https://linux-hardware.org/?probe=5b94fc8fa8) | Mar 02, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [85456379c1](https://linux-hardware.org/?probe=85456379c1) | Mar 02, 2023 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [a79b4ff73c](https://linux-hardware.org/?probe=a79b4ff73c) | Mar 02, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [6126e81a28](https://linux-hardware.org/?probe=6126e81a28) | Mar 01, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [b6930e4615](https://linux-hardware.org/?probe=b6930e4615) | Mar 01, 2023 |
| System76      | Lemur Pro                   | Notebook    | [e7ed83aaf7](https://linux-hardware.org/?probe=e7ed83aaf7) | Mar 01, 2023 |
| HP            | 15                          | Notebook    | [97985ac192](https://linux-hardware.org/?probe=97985ac192) | Mar 01, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [2b007293f7](https://linux-hardware.org/?probe=2b007293f7) | Mar 01, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [9abfe7631c](https://linux-hardware.org/?probe=9abfe7631c) | Mar 01, 2023 |
| ASUSTek       | X751LD                      | Notebook    | [46eecb2678](https://linux-hardware.org/?probe=46eecb2678) | Mar 01, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [bd415a086a](https://linux-hardware.org/?probe=bd415a086a) | Mar 01, 2023 |
| Dell          | Precision 3571              | Notebook    | [40348190de](https://linux-hardware.org/?probe=40348190de) | Mar 01, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [dcaa80ec62](https://linux-hardware.org/?probe=dcaa80ec62) | Mar 01, 2023 |
| Lenovo        | IdeaPad Slim 7 14ITL05 8... | Notebook    | [571d426262](https://linux-hardware.org/?probe=571d426262) | Mar 01, 2023 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | Notebook    | [78ee2e145b](https://linux-hardware.org/?probe=78ee2e145b) | Mar 01, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | Notebook    | [bd4fd4080d](https://linux-hardware.org/?probe=bd4fd4080d) | Mar 01, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | Notebook    | [90d8927f0a](https://linux-hardware.org/?probe=90d8927f0a) | Mar 01, 2023 |
| Gigabyte      | Z77X-UP4 TH                 | Desktop     | [b80cb49656](https://linux-hardware.org/?probe=b80cb49656) | Mar 01, 2023 |
| Gigabyte      | B450 AORUS ELITE V2         | Desktop     | [0e0b3360ba](https://linux-hardware.org/?probe=0e0b3360ba) | Feb 28, 2023 |
| ASUSTek       | Zenbook UX5401ZA_UX5401Z... | Notebook    | [5aad25779a](https://linux-hardware.org/?probe=5aad25779a) | Feb 28, 2023 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | Desktop     | [7f53a53eba](https://linux-hardware.org/?probe=7f53a53eba) | Feb 28, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [6c511739eb](https://linux-hardware.org/?probe=6c511739eb) | Feb 28, 2023 |
| Lenovo        | ThinkPad X270 20HN001RUS    | Notebook    | [ff84200b75](https://linux-hardware.org/?probe=ff84200b75) | Feb 28, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | Notebook    | [88745e1f03](https://linux-hardware.org/?probe=88745e1f03) | Feb 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [357c1abb1d](https://linux-hardware.org/?probe=357c1abb1d) | Feb 27, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [13edc00539](https://linux-hardware.org/?probe=13edc00539) | Feb 27, 2023 |
| AZW           | SER                         | Mini pc     | [f5b64e8716](https://linux-hardware.org/?probe=f5b64e8716) | Feb 27, 2023 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [425567e8f3](https://linux-hardware.org/?probe=425567e8f3) | Feb 27, 2023 |
| Lenovo        | ThinkPad T480s 20L8S7AS0... | Notebook    | [bd62e34a09](https://linux-hardware.org/?probe=bd62e34a09) | Feb 27, 2023 |
| HCL Infosy... | HCL ME LAPTOP               | Notebook    | [82a40f1881](https://linux-hardware.org/?probe=82a40f1881) | Feb 27, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [97e3001416](https://linux-hardware.org/?probe=97e3001416) | Feb 26, 2023 |
| Dell          | 03KWTV A02                  | Desktop     | [8b6eae9fd5](https://linux-hardware.org/?probe=8b6eae9fd5) | Feb 26, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [a3b8430bad](https://linux-hardware.org/?probe=a3b8430bad) | Feb 26, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [fe1c90a3aa](https://linux-hardware.org/?probe=fe1c90a3aa) | Feb 26, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [f081452f55](https://linux-hardware.org/?probe=f081452f55) | Feb 26, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [2a8830034a](https://linux-hardware.org/?probe=2a8830034a) | Feb 26, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [1c93095718](https://linux-hardware.org/?probe=1c93095718) | Feb 26, 2023 |
| Sony          | VPCZ12V9R                   | Notebook    | [3014067c24](https://linux-hardware.org/?probe=3014067c24) | Feb 26, 2023 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [f991f0e9df](https://linux-hardware.org/?probe=f991f0e9df) | Feb 26, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [87647b8c76](https://linux-hardware.org/?probe=87647b8c76) | Feb 26, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [42fe607d11](https://linux-hardware.org/?probe=42fe607d11) | Feb 25, 2023 |
| GPU Compan... | GWTN141-10                  | Notebook    | [1550bec17e](https://linux-hardware.org/?probe=1550bec17e) | Feb 25, 2023 |
| GPU Compan... | GWTN141-10                  | Notebook    | [aa535b0731](https://linux-hardware.org/?probe=aa535b0731) | Feb 25, 2023 |
| Dell          | G7 7588                     | Notebook    | [82f1398a69](https://linux-hardware.org/?probe=82f1398a69) | Feb 25, 2023 |
| Alienware     | 15 R3                       | Notebook    | [72543030d5](https://linux-hardware.org/?probe=72543030d5) | Feb 25, 2023 |
| Lenovo        | IdeaPad 305-15IBD 80NJ      | Notebook    | [42b9d60137](https://linux-hardware.org/?probe=42b9d60137) | Feb 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b5f840e593](https://linux-hardware.org/?probe=b5f840e593) | Feb 25, 2023 |
| System76      | Galago Pro                  | Notebook    | [3e4391562b](https://linux-hardware.org/?probe=3e4391562b) | Feb 25, 2023 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [0a63352761](https://linux-hardware.org/?probe=0a63352761) | Feb 25, 2023 |
| MSI           | PRO Z790-P WIFI DDR4        | Desktop     | [59b7e1da6d](https://linux-hardware.org/?probe=59b7e1da6d) | Feb 25, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [96e6c2c201](https://linux-hardware.org/?probe=96e6c2c201) | Feb 25, 2023 |
| Dell          | Latitude 3310               | Notebook    | [d989647d9d](https://linux-hardware.org/?probe=d989647d9d) | Feb 25, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [517a6211c9](https://linux-hardware.org/?probe=517a6211c9) | Feb 24, 2023 |
| ZOTAC         | MEK1                        | Desktop     | [a61a52d794](https://linux-hardware.org/?probe=a61a52d794) | Feb 24, 2023 |
| HP            | ProBook 450 G1              | Notebook    | [f7c4b009f1](https://linux-hardware.org/?probe=f7c4b009f1) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [297c37ec04](https://linux-hardware.org/?probe=297c37ec04) | Feb 24, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [2f561a23c3](https://linux-hardware.org/?probe=2f561a23c3) | Feb 24, 2023 |
| HP            | 8433 11                     | Desktop     | [881b062090](https://linux-hardware.org/?probe=881b062090) | Feb 24, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [59d0e692ef](https://linux-hardware.org/?probe=59d0e692ef) | Feb 24, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [041c57ebe6](https://linux-hardware.org/?probe=041c57ebe6) | Feb 24, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [f2a29f6d2e](https://linux-hardware.org/?probe=f2a29f6d2e) | Feb 24, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [2913081292](https://linux-hardware.org/?probe=2913081292) | Feb 24, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [c591acd5d6](https://linux-hardware.org/?probe=c591acd5d6) | Feb 24, 2023 |
| Lenovo        | Yoga 6 13ARE05 82FN         | Convertible | [10ffde0986](https://linux-hardware.org/?probe=10ffde0986) | Feb 24, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [27a3c3c4c1](https://linux-hardware.org/?probe=27a3c3c4c1) | Feb 24, 2023 |
| Lenovo        | Yoga 6 13ARE05 82FN         | Convertible | [7ad94e1be6](https://linux-hardware.org/?probe=7ad94e1be6) | Feb 24, 2023 |
| Dell          | Inspiron 5423               | Notebook    | [7cf47f3118](https://linux-hardware.org/?probe=7cf47f3118) | Feb 23, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [00591dc764](https://linux-hardware.org/?probe=00591dc764) | Feb 23, 2023 |
| Lenovo        | ThinkPad T430s 2356CU8      | Notebook    | [bb0d8e868d](https://linux-hardware.org/?probe=bb0d8e868d) | Feb 23, 2023 |
| Toshiba       | Satellite C855-1T5          | Notebook    | [8a96579c89](https://linux-hardware.org/?probe=8a96579c89) | Feb 23, 2023 |
| System76      | Gazelle                     | Notebook    | [609f452af9](https://linux-hardware.org/?probe=609f452af9) | Feb 23, 2023 |
| ONE-NETBOO... | ONE XPLAYER 1002-C          | Notebook    | [33a4731a5e](https://linux-hardware.org/?probe=33a4731a5e) | Feb 23, 2023 |
| Dell          | 0M6C7G A00                  | Desktop     | [8d8af65e26](https://linux-hardware.org/?probe=8d8af65e26) | Feb 23, 2023 |
| Dell          | 0M6C7G A00                  | Desktop     | [f8f5ea8885](https://linux-hardware.org/?probe=f8f5ea8885) | Feb 23, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [205f7c6f50](https://linux-hardware.org/?probe=205f7c6f50) | Feb 23, 2023 |
| Dell          | Latitude E7240              | Notebook    | [7f8278ff44](https://linux-hardware.org/?probe=7f8278ff44) | Feb 23, 2023 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | Notebook    | [34016a67d9](https://linux-hardware.org/?probe=34016a67d9) | Feb 22, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [312937f0d0](https://linux-hardware.org/?probe=312937f0d0) | Feb 22, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [d032f0a547](https://linux-hardware.org/?probe=d032f0a547) | Feb 22, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [ec6ab709e5](https://linux-hardware.org/?probe=ec6ab709e5) | Feb 22, 2023 |
| Lenovo        | 102F SBB0J05441 WIN 3305... | Desktop     | [ea890b85f3](https://linux-hardware.org/?probe=ea890b85f3) | Feb 22, 2023 |
| Gigabyte      | H81M-HD3                    | Desktop     | [d19e079879](https://linux-hardware.org/?probe=d19e079879) | Feb 22, 2023 |
| Lenovo        | ThinkPad T450 20BUS0B000    | Notebook    | [6ab727e8c0](https://linux-hardware.org/?probe=6ab727e8c0) | Feb 22, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [c4eab564b3](https://linux-hardware.org/?probe=c4eab564b3) | Feb 22, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [af2d2bd596](https://linux-hardware.org/?probe=af2d2bd596) | Feb 21, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [41b4e0957f](https://linux-hardware.org/?probe=41b4e0957f) | Feb 21, 2023 |
| ASRock        | B550 Extreme4               | Desktop     | [db2686086b](https://linux-hardware.org/?probe=db2686086b) | Feb 21, 2023 |
| HP            | EliteBook Folio 1040 G2     | Notebook    | [265018acd3](https://linux-hardware.org/?probe=265018acd3) | Feb 21, 2023 |
| Apple         | MacBookPro16,1              | Notebook    | [a5cff07fd8](https://linux-hardware.org/?probe=a5cff07fd8) | Feb 21, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [8c97a04c10](https://linux-hardware.org/?probe=8c97a04c10) | Feb 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [022527aa4c](https://linux-hardware.org/?probe=022527aa4c) | Feb 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [3b1afb00a2](https://linux-hardware.org/?probe=3b1afb00a2) | Feb 21, 2023 |
| Dell          | G15 5525                    | Notebook    | [63bd2ac7b9](https://linux-hardware.org/?probe=63bd2ac7b9) | Feb 21, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [7dd9134373](https://linux-hardware.org/?probe=7dd9134373) | Feb 21, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [fafea002be](https://linux-hardware.org/?probe=fafea002be) | Feb 21, 2023 |
| ASUSTek       | B75M-A                      | Desktop     | [c0c41ca089](https://linux-hardware.org/?probe=c0c41ca089) | Feb 21, 2023 |
| Alienware     | 0NWN7M A00                  | Desktop     | [eef5c2f68f](https://linux-hardware.org/?probe=eef5c2f68f) | Feb 21, 2023 |
| ASUSTek       | B75M-A                      | Desktop     | [2ea45a0d80](https://linux-hardware.org/?probe=2ea45a0d80) | Feb 21, 2023 |
| Acer          | Swift SF114-34              | Notebook    | [e9f5a9d293](https://linux-hardware.org/?probe=e9f5a9d293) | Feb 21, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [5fd759f0ba](https://linux-hardware.org/?probe=5fd759f0ba) | Feb 21, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [edbf6ce468](https://linux-hardware.org/?probe=edbf6ce468) | Feb 20, 2023 |
| Dell          | Precision M4800             | Notebook    | [b8e31b63ce](https://linux-hardware.org/?probe=b8e31b63ce) | Feb 20, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [1862dee971](https://linux-hardware.org/?probe=1862dee971) | Feb 20, 2023 |
| ASRock        | A520M-HVS                   | Desktop     | [cc8628ae2c](https://linux-hardware.org/?probe=cc8628ae2c) | Feb 20, 2023 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [0bc03f3b39](https://linux-hardware.org/?probe=0bc03f3b39) | Feb 20, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [b335ec1cc3](https://linux-hardware.org/?probe=b335ec1cc3) | Feb 20, 2023 |
| HP            | ProBook 450 G1              | Notebook    | [b5e8826f8c](https://linux-hardware.org/?probe=b5e8826f8c) | Feb 20, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [1d62ae4e43](https://linux-hardware.org/?probe=1d62ae4e43) | Feb 20, 2023 |
| Intel         | NUC8i7HNB J68197-502        | Mini pc     | [2f702c3f2f](https://linux-hardware.org/?probe=2f702c3f2f) | Feb 19, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [297b06716d](https://linux-hardware.org/?probe=297b06716d) | Feb 19, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [d4fdbbf1ba](https://linux-hardware.org/?probe=d4fdbbf1ba) | Feb 19, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [a11d164d69](https://linux-hardware.org/?probe=a11d164d69) | Feb 19, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [2011c2060b](https://linux-hardware.org/?probe=2011c2060b) | Feb 19, 2023 |
| ASRock        | H87 Performance             | Desktop     | [a28df01cad](https://linux-hardware.org/?probe=a28df01cad) | Feb 19, 2023 |
| Gigabyte      | Z590I AORUS ULTRA           | Desktop     | [9805ab5764](https://linux-hardware.org/?probe=9805ab5764) | Feb 19, 2023 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [8df8fe9ae8](https://linux-hardware.org/?probe=8df8fe9ae8) | Feb 19, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [813066eda5](https://linux-hardware.org/?probe=813066eda5) | Feb 19, 2023 |
| Lenovo        | 1036 NO DPK                 | Desktop     | [b99541f6ad](https://linux-hardware.org/?probe=b99541f6ad) | Feb 19, 2023 |
| ASUSTek       | ROG Flow X13 GV301RC_GV3... | Convertible | [e87ff10942](https://linux-hardware.org/?probe=e87ff10942) | Feb 18, 2023 |
| HP            | 8437                        | Desktop     | [f8f0f71bf5](https://linux-hardware.org/?probe=f8f0f71bf5) | Feb 18, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [cc0e711862](https://linux-hardware.org/?probe=cc0e711862) | Feb 18, 2023 |
| HP            | 240 G6 Notebook PC          | Notebook    | [fc39dde214](https://linux-hardware.org/?probe=fc39dde214) | Feb 18, 2023 |
| Dell          | Latitude E7240              | Notebook    | [461873da2d](https://linux-hardware.org/?probe=461873da2d) | Feb 18, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [5cc4ff8271](https://linux-hardware.org/?probe=5cc4ff8271) | Feb 18, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [75f9e575b3](https://linux-hardware.org/?probe=75f9e575b3) | Feb 18, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [f120e182a1](https://linux-hardware.org/?probe=f120e182a1) | Feb 17, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [a56a788adf](https://linux-hardware.org/?probe=a56a788adf) | Feb 17, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [7ef47e7131](https://linux-hardware.org/?probe=7ef47e7131) | Feb 17, 2023 |
| HONOR         | NBR-WAX9                    | Notebook    | [b16ea0055d](https://linux-hardware.org/?probe=b16ea0055d) | Feb 17, 2023 |
| Dell          | Latitude E4200              | Notebook    | [18868db8a1](https://linux-hardware.org/?probe=18868db8a1) | Feb 17, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [4101f152f5](https://linux-hardware.org/?probe=4101f152f5) | Feb 17, 2023 |
| ASRock        | B550M-HDV                   | Desktop     | [755006e226](https://linux-hardware.org/?probe=755006e226) | Feb 17, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [91c566ccc9](https://linux-hardware.org/?probe=91c566ccc9) | Feb 16, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [e67f600749](https://linux-hardware.org/?probe=e67f600749) | Feb 16, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C7C... | Notebook    | [2b0904349a](https://linux-hardware.org/?probe=2b0904349a) | Feb 16, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [64c385ee36](https://linux-hardware.org/?probe=64c385ee36) | Feb 16, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [3206e7be82](https://linux-hardware.org/?probe=3206e7be82) | Feb 16, 2023 |
| OriginPC      | Voyager a1600               | Notebook    | [9608c5afd5](https://linux-hardware.org/?probe=9608c5afd5) | Feb 16, 2023 |
| Google        | Blorb                       | Notebook    | [286353731c](https://linux-hardware.org/?probe=286353731c) | Feb 16, 2023 |
| Lenovo        | 3136 SDK0K17763 WIN 1801... | Mini pc     | [01d39bc0ca](https://linux-hardware.org/?probe=01d39bc0ca) | Feb 16, 2023 |
| Lenovo        | ThinkPad T530 2392AQU       | Notebook    | [1b89c43b58](https://linux-hardware.org/?probe=1b89c43b58) | Feb 16, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [684445aeab](https://linux-hardware.org/?probe=684445aeab) | Feb 16, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [5a6d751e4b](https://linux-hardware.org/?probe=5a6d751e4b) | Feb 15, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [c82882e708](https://linux-hardware.org/?probe=c82882e708) | Feb 15, 2023 |
| HP            | EliteBook 850 G2            | Notebook    | [ed0641ce38](https://linux-hardware.org/?probe=ed0641ce38) | Feb 15, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [74a61dff13](https://linux-hardware.org/?probe=74a61dff13) | Feb 15, 2023 |
| Intel         | X99 V1.x                    | Desktop     | [31da77bea8](https://linux-hardware.org/?probe=31da77bea8) | Feb 15, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [c803a7f9e8](https://linux-hardware.org/?probe=c803a7f9e8) | Feb 15, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [3a660768c0](https://linux-hardware.org/?probe=3a660768c0) | Feb 15, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [bdb6e585b0](https://linux-hardware.org/?probe=bdb6e585b0) | Feb 15, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [011e8929fa](https://linux-hardware.org/?probe=011e8929fa) | Feb 15, 2023 |
| Gigabyte      | G41MT-S2                    | Desktop     | [9dfc369401](https://linux-hardware.org/?probe=9dfc369401) | Feb 15, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [1161e39e43](https://linux-hardware.org/?probe=1161e39e43) | Feb 15, 2023 |
| Lenovo        | ThinkPad T450s 20BWS14G0... | Notebook    | [5c4a26ada0](https://linux-hardware.org/?probe=5c4a26ada0) | Feb 14, 2023 |
| Dell          | 07JJ74 A01                  | Server      | [c008b1943f](https://linux-hardware.org/?probe=c008b1943f) | Feb 14, 2023 |
| Gigabyte      | GA-MA770T-UD3P              | Desktop     | [2ca590a85e](https://linux-hardware.org/?probe=2ca590a85e) | Feb 14, 2023 |
| Dell          | Precision M3800             | Notebook    | [98b54858cb](https://linux-hardware.org/?probe=98b54858cb) | Feb 14, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [1028ef9686](https://linux-hardware.org/?probe=1028ef9686) | Feb 14, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [27c2ee6ee0](https://linux-hardware.org/?probe=27c2ee6ee0) | Feb 14, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [826959e69e](https://linux-hardware.org/?probe=826959e69e) | Feb 13, 2023 |
| MSI           | Prestige 14Evo A11M         | Notebook    | [abeebd4312](https://linux-hardware.org/?probe=abeebd4312) | Feb 13, 2023 |
| Sony          | VPCEG27FM                   | Notebook    | [748a67669f](https://linux-hardware.org/?probe=748a67669f) | Feb 13, 2023 |
| Lenovo        | IdeaPad Slim 7 Pro 14IHU... | Notebook    | [a6af7624cd](https://linux-hardware.org/?probe=a6af7624cd) | Feb 13, 2023 |
| Samsung       | 730U3E/740U3E               | Notebook    | [91ac69dfa1](https://linux-hardware.org/?probe=91ac69dfa1) | Feb 13, 2023 |
| Lenovo        | ThinkPad T410 2522G76       | Notebook    | [b15d4051cd](https://linux-hardware.org/?probe=b15d4051cd) | Feb 13, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [d38212ee96](https://linux-hardware.org/?probe=d38212ee96) | Feb 13, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [2314b98760](https://linux-hardware.org/?probe=2314b98760) | Feb 12, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [139b92595a](https://linux-hardware.org/?probe=139b92595a) | Feb 12, 2023 |
| Dell          | 0Y7WYT A00                  | Desktop     | [d94084bbee](https://linux-hardware.org/?probe=d94084bbee) | Feb 12, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [2a6f501cb1](https://linux-hardware.org/?probe=2a6f501cb1) | Feb 12, 2023 |
| Haier         | GG1500A                     | Notebook    | [4c4598157f](https://linux-hardware.org/?probe=4c4598157f) | Feb 12, 2023 |
| Dell          | 08WKV3 A00                  | Desktop     | [89ba42b53e](https://linux-hardware.org/?probe=89ba42b53e) | Feb 12, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [687ecdce15](https://linux-hardware.org/?probe=687ecdce15) | Feb 12, 2023 |
| Dell          | Latitude XT2                | Notebook    | [9b98bf4722](https://linux-hardware.org/?probe=9b98bf4722) | Feb 12, 2023 |
| Dell          | Precision M4700             | Notebook    | [1a44cb5ef9](https://linux-hardware.org/?probe=1a44cb5ef9) | Feb 11, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [fb407bfc13](https://linux-hardware.org/?probe=fb407bfc13) | Feb 11, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [2c1562b21f](https://linux-hardware.org/?probe=2c1562b21f) | Feb 11, 2023 |
| Lenovo        | ThinkPad T470s 20HFCT01W... | Notebook    | [322a9d340e](https://linux-hardware.org/?probe=322a9d340e) | Feb 11, 2023 |
| Acer          | Aspire 5742G                | Notebook    | [1315dbeb6c](https://linux-hardware.org/?probe=1315dbeb6c) | Feb 11, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [2d776f8810](https://linux-hardware.org/?probe=2d776f8810) | Feb 11, 2023 |
| Gigabyte      | X399 AORUS Gaming 7         | Desktop     | [b82ab8816d](https://linux-hardware.org/?probe=b82ab8816d) | Feb 11, 2023 |
| HP            | 18E4                        | Desktop     | [55972b87dd](https://linux-hardware.org/?probe=55972b87dd) | Feb 11, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [ab07f075d8](https://linux-hardware.org/?probe=ab07f075d8) | Feb 11, 2023 |
| Apple         | MacBook8,1                  | Notebook    | [2f1c5b90a8](https://linux-hardware.org/?probe=2f1c5b90a8) | Feb 11, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [24cb179c5a](https://linux-hardware.org/?probe=24cb179c5a) | Feb 11, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [0b14ee6551](https://linux-hardware.org/?probe=0b14ee6551) | Feb 11, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B2502FBA... | Convertible | [dd34aed5d9](https://linux-hardware.org/?probe=dd34aed5d9) | Feb 11, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [c17ac89917](https://linux-hardware.org/?probe=c17ac89917) | Feb 11, 2023 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [181c0e03e2](https://linux-hardware.org/?probe=181c0e03e2) | Feb 10, 2023 |
| MSI           | GF63 Thin 9RCX              | Notebook    | [9cbcfdd748](https://linux-hardware.org/?probe=9cbcfdd748) | Feb 10, 2023 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [cb03f9e72e](https://linux-hardware.org/?probe=cb03f9e72e) | Feb 10, 2023 |
| Dell          | 0Y7WYT A00                  | Desktop     | [e4369afe1e](https://linux-hardware.org/?probe=e4369afe1e) | Feb 10, 2023 |
| ASUSTek       | A55BM-PLUS                  | Desktop     | [7c9763c23f](https://linux-hardware.org/?probe=7c9763c23f) | Feb 10, 2023 |
| Dell          | G15 5520                    | Notebook    | [121b06f3cc](https://linux-hardware.org/?probe=121b06f3cc) | Feb 10, 2023 |
| Samsung       | DeskTop System              | Desktop     | [2437c4afda](https://linux-hardware.org/?probe=2437c4afda) | Feb 10, 2023 |
| Dell          | 0CR1TT A00                  | All in one  | [be588e52b7](https://linux-hardware.org/?probe=be588e52b7) | Feb 09, 2023 |
| Dell          | Venue 11 Pro 7130 MS        | Notebook    | [d0cc5f80fc](https://linux-hardware.org/?probe=d0cc5f80fc) | Feb 09, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [39dbdb0fa9](https://linux-hardware.org/?probe=39dbdb0fa9) | Feb 09, 2023 |
| Lenovo        | ThinkPad T450 20BUA0PNUK    | Notebook    | [8837c33007](https://linux-hardware.org/?probe=8837c33007) | Feb 09, 2023 |
| Biostar       | H81MHV3 5.0                 | Desktop     | [390c8dd03a](https://linux-hardware.org/?probe=390c8dd03a) | Feb 09, 2023 |
| Dell          | Venue 11 Pro 7130 MS        | Notebook    | [74dd2176ff](https://linux-hardware.org/?probe=74dd2176ff) | Feb 09, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [17bf959fd0](https://linux-hardware.org/?probe=17bf959fd0) | Feb 09, 2023 |
| Acer          | Aspire M3970                | Desktop     | [718cc13462](https://linux-hardware.org/?probe=718cc13462) | Feb 09, 2023 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | Notebook    | [93afe9ddeb](https://linux-hardware.org/?probe=93afe9ddeb) | Feb 09, 2023 |
| Dell          | Inspiron 3576               | Notebook    | [a025641dfc](https://linux-hardware.org/?probe=a025641dfc) | Feb 09, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [edc6b0a3af](https://linux-hardware.org/?probe=edc6b0a3af) | Feb 09, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [db7e89340f](https://linux-hardware.org/?probe=db7e89340f) | Feb 09, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [16af8175a4](https://linux-hardware.org/?probe=16af8175a4) | Feb 08, 2023 |
| ASUSTek       | ZenBook UX463FA_UX463FA     | Convertible | [e43aebc69d](https://linux-hardware.org/?probe=e43aebc69d) | Feb 08, 2023 |
| System76      | Lemur Pro                   | Notebook    | [94cf78a9d9](https://linux-hardware.org/?probe=94cf78a9d9) | Feb 08, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [43b52ad56f](https://linux-hardware.org/?probe=43b52ad56f) | Feb 08, 2023 |
| Gigabyte      | B650I AORUS ULTRA           | Desktop     | [1c07b901bb](https://linux-hardware.org/?probe=1c07b901bb) | Feb 08, 2023 |
| HP            | 2129                        | Desktop     | [80920d0d75](https://linux-hardware.org/?probe=80920d0d75) | Feb 08, 2023 |
| Dell          | G15 5520                    | Notebook    | [7f4d36cea1](https://linux-hardware.org/?probe=7f4d36cea1) | Feb 08, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [d8dcaddb54](https://linux-hardware.org/?probe=d8dcaddb54) | Feb 08, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [275ce1a7fc](https://linux-hardware.org/?probe=275ce1a7fc) | Feb 08, 2023 |
| ASRock        | B660 Pro-C/ax               | Desktop     | [31e10f0e68](https://linux-hardware.org/?probe=31e10f0e68) | Feb 07, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [5554154df2](https://linux-hardware.org/?probe=5554154df2) | Feb 07, 2023 |
| Dell          | System XPS L702X            | Notebook    | [cdbc3578d0](https://linux-hardware.org/?probe=cdbc3578d0) | Feb 07, 2023 |
| Alienware     | m15 R7                      | Notebook    | [254ab40fcf](https://linux-hardware.org/?probe=254ab40fcf) | Feb 07, 2023 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [8588a36683](https://linux-hardware.org/?probe=8588a36683) | Feb 07, 2023 |
| Lenovo        | 3743 SDK0T76463 WIN 3422... | Desktop     | [81ece9483e](https://linux-hardware.org/?probe=81ece9483e) | Feb 07, 2023 |
| Gigabyte      | F2A55M-HD2                  | Desktop     | [fe95bfe3d3](https://linux-hardware.org/?probe=fe95bfe3d3) | Feb 07, 2023 |
| Dell          | 0HHV7N A00                  | Desktop     | [e67a1c86b7](https://linux-hardware.org/?probe=e67a1c86b7) | Feb 07, 2023 |
| Gigabyte      | Z170X-UD5-CF                | Desktop     | [03a392d41f](https://linux-hardware.org/?probe=03a392d41f) | Feb 07, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [aef988ae85](https://linux-hardware.org/?probe=aef988ae85) | Feb 07, 2023 |
| Dell          | 02GDWG A00                  | Desktop     | [c0660c15fb](https://linux-hardware.org/?probe=c0660c15fb) | Feb 07, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [f6c24b1ea8](https://linux-hardware.org/?probe=f6c24b1ea8) | Feb 07, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [209a38d937](https://linux-hardware.org/?probe=209a38d937) | Feb 07, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI      | Desktop     | [25fbfe1d66](https://linux-hardware.org/?probe=25fbfe1d66) | Feb 07, 2023 |
| System76      | Thelio thelio-r2            | Desktop     | [4cdf7d2895](https://linux-hardware.org/?probe=4cdf7d2895) | Feb 06, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [50af8c9fe6](https://linux-hardware.org/?probe=50af8c9fe6) | Feb 06, 2023 |
| ASUSTek       | UX430UNR                    | Notebook    | [96d7a1938a](https://linux-hardware.org/?probe=96d7a1938a) | Feb 06, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [42dba6bdb3](https://linux-hardware.org/?probe=42dba6bdb3) | Feb 06, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [a9bfc9669d](https://linux-hardware.org/?probe=a9bfc9669d) | Feb 06, 2023 |
| Acer          | Swift SF114-34              | Notebook    | [28aad1fae5](https://linux-hardware.org/?probe=28aad1fae5) | Feb 06, 2023 |
| ASUSTek       | X751LD                      | Notebook    | [12d5592082](https://linux-hardware.org/?probe=12d5592082) | Feb 06, 2023 |
| Notebook      | NJ50_70CU                   | Notebook    | [c0c9951f8d](https://linux-hardware.org/?probe=c0c9951f8d) | Feb 05, 2023 |
| ASUSTek       | ROG Flow X13 GV301RC_GV3... | Convertible | [2e5b18f7c5](https://linux-hardware.org/?probe=2e5b18f7c5) | Feb 05, 2023 |
| Dell          | Latitude 7380               | Notebook    | [7b9d4ef8b4](https://linux-hardware.org/?probe=7b9d4ef8b4) | Feb 05, 2023 |
| Acer          | Swift SF114-34              | Notebook    | [ea8a0e0617](https://linux-hardware.org/?probe=ea8a0e0617) | Feb 05, 2023 |
| VANT          | MOOVE3-14                   | Notebook    | [5c2bd1284d](https://linux-hardware.org/?probe=5c2bd1284d) | Feb 05, 2023 |
| Alienware     | 17 R5                       | Notebook    | [7f5f8bdb1f](https://linux-hardware.org/?probe=7f5f8bdb1f) | Feb 05, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [6f09d6cd6c](https://linux-hardware.org/?probe=6f09d6cd6c) | Feb 05, 2023 |
| Fujitsu       | LIFEBOOK T902               | Notebook    | [9c92a1772d](https://linux-hardware.org/?probe=9c92a1772d) | Feb 05, 2023 |
| HP            | 8054                        | Desktop     | [c709653825](https://linux-hardware.org/?probe=c709653825) | Feb 05, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d95f28d447](https://linux-hardware.org/?probe=d95f28d447) | Feb 05, 2023 |
| Apple         | MacBookPro5,4               | Notebook    | [a705eb3101](https://linux-hardware.org/?probe=a705eb3101) | Feb 05, 2023 |
| Apple         | MacBookPro5,4               | Notebook    | [7a80b2d6d7](https://linux-hardware.org/?probe=7a80b2d6d7) | Feb 05, 2023 |
| Lenovo        | ThinkPad E580 20KSCTO1WW    | Notebook    | [e5e8537cef](https://linux-hardware.org/?probe=e5e8537cef) | Feb 05, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [0cb9ba3cf9](https://linux-hardware.org/?probe=0cb9ba3cf9) | Feb 05, 2023 |
| ASUSTek       | X751LD                      | Notebook    | [13948b75ae](https://linux-hardware.org/?probe=13948b75ae) | Feb 05, 2023 |
| VANT          | MOOVE3-14                   | Notebook    | [b5ac9ebd7c](https://linux-hardware.org/?probe=b5ac9ebd7c) | Feb 05, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [403785d1ec](https://linux-hardware.org/?probe=403785d1ec) | Feb 05, 2023 |
| HP            | Notebook                    | Notebook    | [0ad701667d](https://linux-hardware.org/?probe=0ad701667d) | Feb 05, 2023 |
| HP            | Notebook                    | Notebook    | [37f601798c](https://linux-hardware.org/?probe=37f601798c) | Feb 05, 2023 |
| Dell          | G15 5515                    | Notebook    | [7418ca82c1](https://linux-hardware.org/?probe=7418ca82c1) | Feb 04, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [fd2b67e6ab](https://linux-hardware.org/?probe=fd2b67e6ab) | Feb 04, 2023 |
| Dell          | Latitude 3520               | Notebook    | [ce594f431c](https://linux-hardware.org/?probe=ce594f431c) | Feb 04, 2023 |
| Dell          | 07JJ74 A01                  | Server      | [db5c0dd7b2](https://linux-hardware.org/?probe=db5c0dd7b2) | Feb 04, 2023 |
| Dell          | 07JJ74 A01                  | Server      | [85ce5298e5](https://linux-hardware.org/?probe=85ce5298e5) | Feb 04, 2023 |
| Acer          | Aspire A515-51G             | Notebook    | [149465f225](https://linux-hardware.org/?probe=149465f225) | Feb 04, 2023 |
| ASUSTek       | PRIME X299-DELUXE II        | Desktop     | [c66fb39891](https://linux-hardware.org/?probe=c66fb39891) | Feb 04, 2023 |
| Gigabyte      | Z170X-UD5-CF                | Desktop     | [cd9d867630](https://linux-hardware.org/?probe=cd9d867630) | Feb 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [448d3800ac](https://linux-hardware.org/?probe=448d3800ac) | Feb 04, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [0f24e9c32c](https://linux-hardware.org/?probe=0f24e9c32c) | Feb 04, 2023 |
| Toshiba       | Satellite C855-233          | Notebook    | [8fc7835588](https://linux-hardware.org/?probe=8fc7835588) | Feb 04, 2023 |
| Lenovo        | ThinkPad P50 20EN0017US     | Notebook    | [43c5ab14ec](https://linux-hardware.org/?probe=43c5ab14ec) | Feb 03, 2023 |
| Dell          | Latitude E7240              | Notebook    | [da54499919](https://linux-hardware.org/?probe=da54499919) | Feb 03, 2023 |
| Haier         | GG1500A                     | Notebook    | [b54ce000d3](https://linux-hardware.org/?probe=b54ce000d3) | Feb 03, 2023 |
| Biostar       | H81MHV3 5.0                 | Desktop     | [084eee2317](https://linux-hardware.org/?probe=084eee2317) | Feb 03, 2023 |
| Star Labs     | StarBook                    | Notebook    | [98ad1bcab4](https://linux-hardware.org/?probe=98ad1bcab4) | Feb 03, 2023 |
| Star Labs     | StarBook                    | Notebook    | [5fe174bdd1](https://linux-hardware.org/?probe=5fe174bdd1) | Feb 03, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [704c6e370c](https://linux-hardware.org/?probe=704c6e370c) | Feb 03, 2023 |
| AZW           | SER                         | Mini pc     | [198a217d13](https://linux-hardware.org/?probe=198a217d13) | Feb 03, 2023 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [8a1c423c67](https://linux-hardware.org/?probe=8a1c423c67) | Feb 03, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [c441c159c1](https://linux-hardware.org/?probe=c441c159c1) | Feb 03, 2023 |
| HP            | 834F                        | Desktop     | [9a4a1839d3](https://linux-hardware.org/?probe=9a4a1839d3) | Feb 02, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [8944f22b68](https://linux-hardware.org/?probe=8944f22b68) | Feb 02, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [0b0eaa5c48](https://linux-hardware.org/?probe=0b0eaa5c48) | Feb 02, 2023 |
| Acer          | Swift SF114-32              | Notebook    | [96b48bebd2](https://linux-hardware.org/?probe=96b48bebd2) | Feb 02, 2023 |
| Dell          | Inspiron 3584               | Notebook    | [4bfcbe7c13](https://linux-hardware.org/?probe=4bfcbe7c13) | Feb 02, 2023 |
| HP            | 872E                        | Mini pc     | [c73d160043](https://linux-hardware.org/?probe=c73d160043) | Feb 02, 2023 |
| Dell          | Precision 3571              | Notebook    | [8ee8f6f768](https://linux-hardware.org/?probe=8ee8f6f768) | Feb 02, 2023 |
| Dell          | Precision 3571              | Notebook    | [9453f26568](https://linux-hardware.org/?probe=9453f26568) | Feb 02, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [2fe2d2d279](https://linux-hardware.org/?probe=2fe2d2d279) | Feb 02, 2023 |
| Dell          | Latitude 7320 Detachable    | Tablet      | [7560429d05](https://linux-hardware.org/?probe=7560429d05) | Feb 02, 2023 |
| MSI           | MPG B560I GAMING EDGE WI... | Desktop     | [6d4ee8a3c6](https://linux-hardware.org/?probe=6d4ee8a3c6) | Feb 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ffabf45521](https://linux-hardware.org/?probe=ffabf45521) | Feb 02, 2023 |
| Apple         | Mac-F2268DC8                | All in one  | [0811d3d2f0](https://linux-hardware.org/?probe=0811d3d2f0) | Feb 02, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [a899b18189](https://linux-hardware.org/?probe=a899b18189) | Feb 02, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | Notebook    | [8db619716a](https://linux-hardware.org/?probe=8db619716a) | Feb 02, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | Notebook    | [7019bd88e0](https://linux-hardware.org/?probe=7019bd88e0) | Feb 01, 2023 |
| HP            | Pavilion 15                 | Notebook    | [946fec8f7d](https://linux-hardware.org/?probe=946fec8f7d) | Feb 01, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [6294616fc6](https://linux-hardware.org/?probe=6294616fc6) | Feb 01, 2023 |
| Apple         | Mac-F2268DC8                | All in one  | [b13dd2d455](https://linux-hardware.org/?probe=b13dd2d455) | Feb 01, 2023 |
| Lenovo        | IdeaPad S530-13IWL 81J7     | Notebook    | [6ed194a014](https://linux-hardware.org/?probe=6ed194a014) | Feb 01, 2023 |
| Timi          | Mi NoteBook Ultra           | Notebook    | [d897ec0114](https://linux-hardware.org/?probe=d897ec0114) | Feb 01, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [c4869ecf2c](https://linux-hardware.org/?probe=c4869ecf2c) | Feb 01, 2023 |
| Acer          | Predator PH517-61           | Notebook    | [b16ddc31d8](https://linux-hardware.org/?probe=b16ddc31d8) | Feb 01, 2023 |
| Dell          | Latitude E7240              | Notebook    | [fe655eca77](https://linux-hardware.org/?probe=fe655eca77) | Jan 31, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [3803fd2405](https://linux-hardware.org/?probe=3803fd2405) | Jan 31, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [db8bdbd72b](https://linux-hardware.org/?probe=db8bdbd72b) | Jan 31, 2023 |
| Dell          | Inspiron 7400               | Notebook    | [a6b124fd34](https://linux-hardware.org/?probe=a6b124fd34) | Jan 31, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [228ab40738](https://linux-hardware.org/?probe=228ab40738) | Jan 31, 2023 |
| HP            | Notebook                    | Notebook    | [82d58b21c4](https://linux-hardware.org/?probe=82d58b21c4) | Jan 31, 2023 |
| HP            | ZBook Studio G3             | Notebook    | [506988f4ba](https://linux-hardware.org/?probe=506988f4ba) | Jan 31, 2023 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [7636aeaacc](https://linux-hardware.org/?probe=7636aeaacc) | Jan 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [84278c514e](https://linux-hardware.org/?probe=84278c514e) | Jan 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [e91278bf3b](https://linux-hardware.org/?probe=e91278bf3b) | Jan 31, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [230b38f8e6](https://linux-hardware.org/?probe=230b38f8e6) | Jan 31, 2023 |
| Acer          | Swift SF114-32              | Notebook    | [82d317899e](https://linux-hardware.org/?probe=82d317899e) | Jan 31, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [6a0af9dbcb](https://linux-hardware.org/?probe=6a0af9dbcb) | Jan 31, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [33ae030343](https://linux-hardware.org/?probe=33ae030343) | Jan 31, 2023 |
| Intel         | NUC6i5SYB H81131-504        | Mini pc     | [d079e3930d](https://linux-hardware.org/?probe=d079e3930d) | Jan 31, 2023 |
| MSI           | PRO Z690-P DDR4             | Desktop     | [a434328de5](https://linux-hardware.org/?probe=a434328de5) | Jan 30, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [2474b4641c](https://linux-hardware.org/?probe=2474b4641c) | Jan 30, 2023 |
| GPU Compan... | GWTN141-10                  | Notebook    | [f012d6d71c](https://linux-hardware.org/?probe=f012d6d71c) | Jan 30, 2023 |
| ASUSTek       | UX310UQK                    | Notebook    | [d4aec33c44](https://linux-hardware.org/?probe=d4aec33c44) | Jan 30, 2023 |
| ASUSTek       | UX310UQK                    | Notebook    | [58e7588538](https://linux-hardware.org/?probe=58e7588538) | Jan 30, 2023 |
| Acer          | Swift SF114-32              | Notebook    | [1228d6d0f7](https://linux-hardware.org/?probe=1228d6d0f7) | Jan 30, 2023 |
| Dell          | G15 5511                    | Notebook    | [36214ba4de](https://linux-hardware.org/?probe=36214ba4de) | Jan 30, 2023 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [a96d93846a](https://linux-hardware.org/?probe=a96d93846a) | Jan 30, 2023 |
| Dell          | Latitude E7240              | Notebook    | [a1f713f6e3](https://linux-hardware.org/?probe=a1f713f6e3) | Jan 30, 2023 |
| Avell High... | B11 MOB                     | Notebook    | [dd9d29ddc7](https://linux-hardware.org/?probe=dd9d29ddc7) | Jan 30, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [3d555e69f7](https://linux-hardware.org/?probe=3d555e69f7) | Jan 30, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [42405a6a0c](https://linux-hardware.org/?probe=42405a6a0c) | Jan 30, 2023 |
| HP            | Pavilion dv6                | Notebook    | [0966ae419c](https://linux-hardware.org/?probe=0966ae419c) | Jan 30, 2023 |
| Intel         | H61                         | Desktop     | [87a72c61f2](https://linux-hardware.org/?probe=87a72c61f2) | Jan 29, 2023 |
| ASUSTek       | X555LD                      | Notebook    | [b70d834fe5](https://linux-hardware.org/?probe=b70d834fe5) | Jan 29, 2023 |
| Gigabyte      | Z690 AORUS PRO              | Desktop     | [b07e189d3c](https://linux-hardware.org/?probe=b07e189d3c) | Jan 29, 2023 |
| Dell          | G15 5515                    | Notebook    | [1be125c3cd](https://linux-hardware.org/?probe=1be125c3cd) | Jan 29, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [6b71ec1a01](https://linux-hardware.org/?probe=6b71ec1a01) | Jan 28, 2023 |
| Gigabyte      | H77M-D3H                    | Desktop     | [a9367f87d4](https://linux-hardware.org/?probe=a9367f87d4) | Jan 28, 2023 |
| ASUSTek       | GA35DX                      | Desktop     | [697b0d8654](https://linux-hardware.org/?probe=697b0d8654) | Jan 28, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [ff3381fe1a](https://linux-hardware.org/?probe=ff3381fe1a) | Jan 28, 2023 |
| ASUSTek       | PRIME B560M-K               | Desktop     | [c74b6b90f0](https://linux-hardware.org/?probe=c74b6b90f0) | Jan 28, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [c6770f3828](https://linux-hardware.org/?probe=c6770f3828) | Jan 28, 2023 |
| HP            | Pavilion dv6500             | Notebook    | [ec9bed5b5d](https://linux-hardware.org/?probe=ec9bed5b5d) | Jan 28, 2023 |
| ASUSTek       | ET2321I                     | Notebook    | [dbb162975e](https://linux-hardware.org/?probe=dbb162975e) | Jan 28, 2023 |
| MSI           | Vector GP76 12UHSO          | Notebook    | [549b690251](https://linux-hardware.org/?probe=549b690251) | Jan 28, 2023 |
| HP            | Pavilion dv6500             | Notebook    | [e225ce26a1](https://linux-hardware.org/?probe=e225ce26a1) | Jan 28, 2023 |
| MSI           | Vector GP76 12UHSO          | Notebook    | [cbbd1d3e3e](https://linux-hardware.org/?probe=cbbd1d3e3e) | Jan 28, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [684b829dbb](https://linux-hardware.org/?probe=684b829dbb) | Jan 28, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [995da6b474](https://linux-hardware.org/?probe=995da6b474) | Jan 27, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ce2955973a](https://linux-hardware.org/?probe=ce2955973a) | Jan 27, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [55d50f6d18](https://linux-hardware.org/?probe=55d50f6d18) | Jan 27, 2023 |
| System76      | Lemur Pro                   | Notebook    | [40c5731c48](https://linux-hardware.org/?probe=40c5731c48) | Jan 27, 2023 |
| HP            | 1495                        | Desktop     | [8c1f7b5fbd](https://linux-hardware.org/?probe=8c1f7b5fbd) | Jan 27, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [c2a36422b4](https://linux-hardware.org/?probe=c2a36422b4) | Jan 27, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [df315d8050](https://linux-hardware.org/?probe=df315d8050) | Jan 27, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [14a0252d88](https://linux-hardware.org/?probe=14a0252d88) | Jan 27, 2023 |
| Clevo         | W150HNM/W170HN              | Notebook    | [63709a14ca](https://linux-hardware.org/?probe=63709a14ca) | Jan 27, 2023 |
| ASUSTek       | G10DK                       | Desktop     | [0b70a364b7](https://linux-hardware.org/?probe=0b70a364b7) | Jan 27, 2023 |
| ASUSTek       | G10DK                       | Desktop     | [a42ba7ef9e](https://linux-hardware.org/?probe=a42ba7ef9e) | Jan 26, 2023 |
| ASUSTek       | P8B75-V                     | Desktop     | [1f8bd6b38e](https://linux-hardware.org/?probe=1f8bd6b38e) | Jan 26, 2023 |
| Dell          | Latitude E7240              | Notebook    | [d88cdedff3](https://linux-hardware.org/?probe=d88cdedff3) | Jan 26, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | Notebook    | [df04ffbd50](https://linux-hardware.org/?probe=df04ffbd50) | Jan 26, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | Notebook    | [b2ffc58bb1](https://linux-hardware.org/?probe=b2ffc58bb1) | Jan 26, 2023 |
| Dell          | G3 3590                     | Notebook    | [8a7e4e4db0](https://linux-hardware.org/?probe=8a7e4e4db0) | Jan 26, 2023 |
| System76      | Lemur Pro                   | Notebook    | [097cd4c9f8](https://linux-hardware.org/?probe=097cd4c9f8) | Jan 26, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [2fe7cc7865](https://linux-hardware.org/?probe=2fe7cc7865) | Jan 25, 2023 |
| Gigabyte      | A5 K1                       | Notebook    | [e0771eb5f6](https://linux-hardware.org/?probe=e0771eb5f6) | Jan 25, 2023 |
| MSI           | B460M PRO-VDH WIFI          | Desktop     | [e32b0f2c79](https://linux-hardware.org/?probe=e32b0f2c79) | Jan 25, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [c7c957ccb3](https://linux-hardware.org/?probe=c7c957ccb3) | Jan 25, 2023 |
| HP            | ProBook 6550b               | Notebook    | [c7983e417c](https://linux-hardware.org/?probe=c7983e417c) | Jan 25, 2023 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [4629dc82aa](https://linux-hardware.org/?probe=4629dc82aa) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [bc56140257](https://linux-hardware.org/?probe=bc56140257) | Jan 25, 2023 |
| Gigabyte      | A5 K1                       | Notebook    | [d5e00555ca](https://linux-hardware.org/?probe=d5e00555ca) | Jan 25, 2023 |
| Dell          | Inspiron 13-7353            | Notebook    | [5ebcba8c52](https://linux-hardware.org/?probe=5ebcba8c52) | Jan 25, 2023 |
| Dell          | Latitude E7240              | Notebook    | [2d488752b6](https://linux-hardware.org/?probe=2d488752b6) | Jan 25, 2023 |
| Dell          | System Inspiron N7110       | Notebook    | [935a295b28](https://linux-hardware.org/?probe=935a295b28) | Jan 25, 2023 |
| ASUSTek       | N551JW                      | Notebook    | [9694a30eff](https://linux-hardware.org/?probe=9694a30eff) | Jan 25, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | Desktop     | [10f149abb7](https://linux-hardware.org/?probe=10f149abb7) | Jan 24, 2023 |
| MeLE          | Rev GMLR1                   | Mini pc     | [1f294d6a67](https://linux-hardware.org/?probe=1f294d6a67) | Jan 24, 2023 |
| Dell          | 02P9X9 A00                  | Server      | [be7339e967](https://linux-hardware.org/?probe=be7339e967) | Jan 24, 2023 |
| Acer          | Aspire M3970                | Desktop     | [c822a510e5](https://linux-hardware.org/?probe=c822a510e5) | Jan 24, 2023 |
| Dell          | Latitude E7240              | Notebook    | [9d44efa2f9](https://linux-hardware.org/?probe=9d44efa2f9) | Jan 24, 2023 |
| Acer          | Swift SFA16-41              | Notebook    | [1c05334105](https://linux-hardware.org/?probe=1c05334105) | Jan 24, 2023 |
| LG Electro... | 17Z90Q-K.AAC7U1             | Notebook    | [73a0023203](https://linux-hardware.org/?probe=73a0023203) | Jan 24, 2023 |
| Google        | Link                        | Notebook    | [5c44e38153](https://linux-hardware.org/?probe=5c44e38153) | Jan 23, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [4f5be0720a](https://linux-hardware.org/?probe=4f5be0720a) | Jan 23, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [c87ce45f84](https://linux-hardware.org/?probe=c87ce45f84) | Jan 23, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | Notebook    | [f6e09cc9fb](https://linux-hardware.org/?probe=f6e09cc9fb) | Jan 23, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | Notebook    | [306e6ae925](https://linux-hardware.org/?probe=306e6ae925) | Jan 23, 2023 |
| ASUSTek       | Rampage II GENE             | Desktop     | [112b5304d9](https://linux-hardware.org/?probe=112b5304d9) | Jan 23, 2023 |
| MACHINIST     | X79 Z9-D7 V2.0              | Desktop     | [9d5d06d342](https://linux-hardware.org/?probe=9d5d06d342) | Jan 23, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [bfb889f5d5](https://linux-hardware.org/?probe=bfb889f5d5) | Jan 23, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [6597dd71bc](https://linux-hardware.org/?probe=6597dd71bc) | Jan 23, 2023 |
| Gigabyte      | G41MT-S2                    | Desktop     | [8f19cbfb31](https://linux-hardware.org/?probe=8f19cbfb31) | Jan 22, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [821e7b4330](https://linux-hardware.org/?probe=821e7b4330) | Jan 22, 2023 |
| Purism        | Librem 15 v3                | Notebook    | [fcb1d44df6](https://linux-hardware.org/?probe=fcb1d44df6) | Jan 22, 2023 |
| MSI           | H81M-E34                    | Desktop     | [c11041ba13](https://linux-hardware.org/?probe=c11041ba13) | Jan 22, 2023 |
| ASUSTek       | H61M-E                      | Desktop     | [eec3fddef5](https://linux-hardware.org/?probe=eec3fddef5) | Jan 22, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [758ea69493](https://linux-hardware.org/?probe=758ea69493) | Jan 22, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [4f65820da4](https://linux-hardware.org/?probe=4f65820da4) | Jan 22, 2023 |
| Dell          | Latitude E5470              | Notebook    | [1a2810f035](https://linux-hardware.org/?probe=1a2810f035) | Jan 22, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [d1b63bbd2d](https://linux-hardware.org/?probe=d1b63bbd2d) | Jan 22, 2023 |
| HP            | Notebook                    | Notebook    | [57bf6826ef](https://linux-hardware.org/?probe=57bf6826ef) | Jan 22, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [01e83b7640](https://linux-hardware.org/?probe=01e83b7640) | Jan 22, 2023 |
| Lenovo        | ThinkPad L380 20M50013UK    | Notebook    | [0729d0a10f](https://linux-hardware.org/?probe=0729d0a10f) | Jan 22, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | Desktop     | [ebab459512](https://linux-hardware.org/?probe=ebab459512) | Jan 22, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [223ab1f016](https://linux-hardware.org/?probe=223ab1f016) | Jan 22, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [70b4ca8de7](https://linux-hardware.org/?probe=70b4ca8de7) | Jan 22, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [9b3b21f5b7](https://linux-hardware.org/?probe=9b3b21f5b7) | Jan 21, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [22d9f43ef5](https://linux-hardware.org/?probe=22d9f43ef5) | Jan 21, 2023 |
| ASUSTek       | G10DK                       | Desktop     | [1a27b660c2](https://linux-hardware.org/?probe=1a27b660c2) | Jan 21, 2023 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [6dd531590e](https://linux-hardware.org/?probe=6dd531590e) | Jan 21, 2023 |
| Razer x La... | TensorBook (late 2021)      | Notebook    | [9062d4274f](https://linux-hardware.org/?probe=9062d4274f) | Jan 21, 2023 |
| Dell          | Latitude 5300               | Notebook    | [e8c4218110](https://linux-hardware.org/?probe=e8c4218110) | Jan 21, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [bd601f83d3](https://linux-hardware.org/?probe=bd601f83d3) | Jan 21, 2023 |
| ASRock        | X99 Professional Gaming ... | Desktop     | [d203633f83](https://linux-hardware.org/?probe=d203633f83) | Jan 21, 2023 |
| Dell          | 0KC9NP A01                  | Desktop     | [ce0ba337df](https://linux-hardware.org/?probe=ce0ba337df) | Jan 21, 2023 |
| ASRock        | X99 Professional Gaming ... | Desktop     | [e47d5b2419](https://linux-hardware.org/?probe=e47d5b2419) | Jan 21, 2023 |
| Lenovo        | ThinkPad T530 23943J8       | Notebook    | [1da6722b35](https://linux-hardware.org/?probe=1da6722b35) | Jan 21, 2023 |
| ASUSTek       | P6T SE                      | Desktop     | [011553878f](https://linux-hardware.org/?probe=011553878f) | Jan 21, 2023 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [b7b8f92df1](https://linux-hardware.org/?probe=b7b8f92df1) | Jan 21, 2023 |
| Dell          | Inspiron 5505               | Notebook    | [9a17165647](https://linux-hardware.org/?probe=9a17165647) | Jan 20, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Pop!_OS_22.04/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 6.0.12-76060006-generic  | 465       | 16.47%  |
| 5.19.0-76051900-generic  | 444       | 15.72%  |
| 5.17.5-76051705-generic  | 413       | 14.62%  |
| 6.0.6-76060006-generic   | 299       | 10.59%  |
| 6.2.6-76060206-generic   | 235       | 8.32%   |
| 5.18.10-76051810-generic | 206       | 7.29%   |
| 5.17.15-76051715-generic | 185       | 6.55%   |
| 5.16.19-76051619-generic | 119       | 4.21%   |
| 6.2.0-76060200-generic   | 116       | 4.11%   |
| 6.1.11-76060111-generic  | 89        | 3.15%   |
| 6.0.2-76060002-generic   | 87        | 3.08%   |
| 5.19.16-76051916-generic | 43        | 1.52%   |
| 6.0.3-76060003-generic   | 39        | 1.38%   |
| 6.1.0-1006-oem           | 3         | 0.11%   |
| 5.16.15-76051615-generic | 3         | 0.11%   |
| 6.2.11-060211-generic    | 2         | 0.07%   |
| 6.1.8-060108-generic     | 2         | 0.07%   |
| 6.1.0-x64v1-xanmod1      | 2         | 0.07%   |
| 6.0.9-060009-generic     | 2         | 0.07%   |
| 6.0.2-x64v1-xanmod1      | 2         | 0.07%   |
| 5.19.12-xanmod1          | 2         | 0.07%   |
| 5.17.7-051707-generic    | 2         | 0.07%   |
| 5.17.5-051705-generic    | 2         | 0.07%   |
| 6.2.9-1-liquorix-amd64   | 1         | 0.04%   |
| 6.2.9-060209-generic     | 1         | 0.04%   |
| 6.2.8-060208-generic     | 1         | 0.04%   |
| 6.2.6-060206-generic     | 1         | 0.04%   |
| 6.2.2-x64v3-xanmod1      | 1         | 0.04%   |
| 6.2.2-surface            | 1         | 0.04%   |
| 6.2.10-060210-generic    | 1         | 0.04%   |
| 6.2.1-060201-generic     | 1         | 0.04%   |
| 6.1.9-x64v1-xanmod1      | 1         | 0.04%   |
| 6.1.9-060109-generic     | 1         | 0.04%   |
| 6.1.8-surface            | 1         | 0.04%   |
| 6.1.7-060107-generic     | 1         | 0.04%   |
| 6.1.2-surface            | 1         | 0.04%   |
| 6.1.18-x64v2-xanmod1     | 1         | 0.04%   |
| 6.1.14-x64v2-xanmod1     | 1         | 0.04%   |
| 6.1.13-x64v3-xanmod1     | 1         | 0.04%   |
| 6.1.12-x64v3-xanmod1     | 1         | 0.04%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.0.12  | 466       | 16.51%  |
| 5.19.0  | 447       | 15.83%  |
| 5.17.5  | 416       | 14.74%  |
| 6.0.6   | 300       | 10.63%  |
| 6.2.6   | 236       | 8.36%   |
| 5.18.10 | 206       | 7.3%    |
| 5.17.15 | 185       | 6.55%   |
| 5.16.19 | 119       | 4.22%   |
| 6.2.0   | 116       | 4.11%   |
| 6.1.11  | 90        | 3.19%   |
| 6.0.2   | 90        | 3.19%   |
| 5.19.16 | 43        | 1.52%   |
| 6.0.3   | 39        | 1.38%   |
| 6.1.0   | 6         | 0.21%   |
| 5.15.0  | 6         | 0.21%   |
| 6.1.8   | 3         | 0.11%   |
| 6.0.9   | 3         | 0.11%   |
| 5.16.15 | 3         | 0.11%   |
| 6.2.9   | 2         | 0.07%   |
| 6.2.2   | 2         | 0.07%   |
| 6.2.11  | 2         | 0.07%   |
| 6.1.9   | 2         | 0.07%   |
| 6.1.12  | 2         | 0.07%   |
| 6.0.0   | 2         | 0.07%   |
| 5.19.12 | 2         | 0.07%   |
| 5.18.0  | 2         | 0.07%   |
| 5.17.7  | 2         | 0.07%   |
| 5.17.0  | 2         | 0.07%   |
| 6.2.8   | 1         | 0.04%   |
| 6.2.10  | 1         | 0.04%   |
| 6.2.1   | 1         | 0.04%   |
| 6.1.7   | 1         | 0.04%   |
| 6.1.2   | 1         | 0.04%   |
| 6.1.18  | 1         | 0.04%   |
| 6.1.14  | 1         | 0.04%   |
| 6.1.13  | 1         | 0.04%   |
| 6.0.8   | 1         | 0.04%   |
| 6.0.7   | 1         | 0.04%   |
| 6.0.10  | 1         | 0.04%   |
| 5.4.210 | 1         | 0.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.0     | 875       | 31.54%  |
| 5.17    | 597       | 21.52%  |
| 5.19    | 492       | 17.74%  |
| 6.2     | 358       | 12.91%  |
| 5.18    | 212       | 7.64%   |
| 5.16    | 123       | 4.43%   |
| 6.1     | 107       | 3.86%   |
| 5.15    | 9         | 0.32%   |
| 5.4     | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 2559      | 99.84%  |
| aarch64 | 4         | 0.16%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 2500      | 97.28%  |
| KDE5            | 36        | 1.4%    |
| Unknown         | 13        | 0.51%   |
| X-Cinnamon      | 9         | 0.35%   |
| LXQt            | 3         | 0.12%   |
| GNOME Flashback | 3         | 0.12%   |
| Unity           | 2         | 0.08%   |
| Cinnamon        | 2         | 0.08%   |
| XFCE            | 1         | 0.04%   |
| MATE            | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 2463      | 95.43%  |
| Wayland | 104       | 4.03%   |
| Unknown | 11        | 0.43%   |
| Tty     | 3         | 0.12%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1957      | 75.82%  |
| GDM3    | 609       | 23.6%   |
| GDM     | 7         | 0.27%   |
| SDDM    | 6         | 0.23%   |
| LightDM | 2         | 0.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1566      | 60.7%   |
| en_GB   | 171       | 6.63%   |
| pt_BR   | 138       | 5.35%   |
| de_DE   | 110       | 4.26%   |
| C       | 75        | 2.91%   |
| it_IT   | 57        | 2.21%   |
| en_AU   | 57        | 2.21%   |
| en_CA   | 48        | 1.86%   |
| fr_FR   | 45        | 1.74%   |
| es_ES   | 28        | 1.09%   |
| pl_PL   | 25        | 0.97%   |
| ru_RU   | 23        | 0.89%   |
| nb_NO   | 17        | 0.66%   |
| sv_SE   | 16        | 0.62%   |
| fi_FI   | 14        | 0.54%   |
| Unknown | 13        | 0.5%    |
| nl_NL   | 12        | 0.47%   |
| es_CL   | 12        | 0.47%   |
| pt_PT   | 11        | 0.43%   |
| en_IE   | 11        | 0.43%   |
| en_IN   | 10        | 0.39%   |
| es_MX   | 8         | 0.31%   |
| en_NZ   | 8         | 0.31%   |
| de_CH   | 8         | 0.31%   |
| fr_CA   | 7         | 0.27%   |
| es_AR   | 7         | 0.27%   |
| en_DK   | 7         | 0.27%   |
| da_DK   | 7         | 0.27%   |
| ja_JP   | 6         | 0.23%   |
| en_ZA   | 6         | 0.23%   |
| de_AT   | 6         | 0.23%   |
| cs_CZ   | 5         | 0.19%   |
| tr_TR   | 4         | 0.16%   |
| es_CO   | 4         | 0.16%   |
| ro_RO   | 3         | 0.12%   |
| fr_CH   | 3         | 0.12%   |
| fr_BE   | 3         | 0.12%   |
| zh_TW   | 2         | 0.08%   |
| nl_BE   | 2         | 0.08%   |
| hu_HU   | 2         | 0.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 1990      | 77.16%  |
| EFI  | 589       | 22.84%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 2428      | 94.51%  |
| Btrfs   | 83        | 3.23%   |
| Overlay | 47        | 1.83%   |
| Xfs     | 8         | 0.31%   |
| Zfs     | 2         | 0.08%   |
| Unknown | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1944      | 75.32%  |
| GPT     | 599       | 23.21%  |
| MBR     | 38        | 1.47%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2497      | 97.05%  |
| Yes       | 76        | 2.95%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2322      | 90.35%  |
| Yes       | 248       | 9.65%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 455       | 17.75%  |
| Lenovo                  | 374       | 14.59%  |
| Dell                    | 326       | 12.72%  |
| Hewlett-Packard         | 287       | 11.2%   |
| MSI                     | 181       | 7.06%   |
| Gigabyte Technology     | 170       | 6.63%   |
| Apple                   | 127       | 4.96%   |
| Acer                    | 118       | 4.6%    |
| ASRock                  | 86        | 3.36%   |
| System76                | 55        | 2.15%   |
| Intel                   | 36        | 1.4%    |
| Samsung Electronics     | 29        | 1.13%   |
| Toshiba                 | 28        | 1.09%   |
| HUAWEI                  | 22        | 0.86%   |
| Alienware               | 19        | 0.74%   |
| Microsoft               | 16        | 0.62%   |
| Fujitsu                 | 15        | 0.59%   |
| Google                  | 13        | 0.51%   |
| Unknown                 | 12        | 0.47%   |
| Sony                    | 9         | 0.35%   |
| Razer                   | 9         | 0.35%   |
| GPU Company             | 9         | 0.35%   |
| Timi                    | 7         | 0.27%   |
| Notebook                | 7         | 0.27%   |
| BESSTAR Tech            | 7         | 0.27%   |
| AZW                     | 7         | 0.27%   |
| Positivo                | 6         | 0.23%   |
| Framework               | 6         | 0.23%   |
| Supermicro              | 5         | 0.2%    |
| MACHINIST               | 5         | 0.2%    |
| HONOR                   | 5         | 0.2%    |
| Avell High Performance  | 5         | 0.2%    |
| TUXEDO                  | 4         | 0.16%   |
| Raspberry Pi Foundation | 4         | 0.16%   |
| Pegatron                | 4         | 0.16%   |
| Medion                  | 4         | 0.16%   |
| Foxconn                 | 4         | 0.16%   |
| PC Specialist           | 3         | 0.12%   |
| LG Electronics          | 3         | 0.12%   |
| GPD                     | 3         | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| ASUS All Series                   | 17        | 0.66%   |
| Unknown                           | 16        | 0.62%   |
| System76 Oryx Pro                 | 13        | 0.51%   |
| System76 Lemur Pro                | 12        | 0.47%   |
| Apple MacBookPro12,1              | 11        | 0.43%   |
| ASUS ROG STRIX B550-F GAMING      | 10        | 0.39%   |
| Gigabyte X570 AORUS ELITE         | 9         | 0.35%   |
| ASUS ROG STRIX B550-I GAMING      | 9         | 0.35%   |
| Apple MacBookAir7,2               | 9         | 0.35%   |
| System76 Gazelle                  | 8         | 0.31%   |
| HP Dev One Notebook PC            | 8         | 0.31%   |
| ASUS TUF Gaming B550-PLUS         | 8         | 0.31%   |
| ASUS ROG STRIX B450-F GAMING      | 8         | 0.31%   |
| Apple MacBookPro9,2               | 8         | 0.31%   |
| ASUS TUF Gaming X570-PLUS         | 7         | 0.27%   |
| Apple MacBookAir6,2               | 7         | 0.27%   |
| System76 Thelio                   | 6         | 0.23%   |
| Lenovo IdeaPad S145-15API 81V7    | 6         | 0.23%   |
| Gigabyte B450 AORUS M             | 6         | 0.23%   |
| Dell XPS 15 9520                  | 6         | 0.23%   |
| ASUS TUF Gaming B550M-PLUS        | 6         | 0.23%   |
| ASUS PRIME B550M-A                | 6         | 0.23%   |
| Apple MacBookPro11,3              | 6         | 0.23%   |
| MSI MS-7D54                       | 5         | 0.2%    |
| MSI MS-7D32                       | 5         | 0.2%    |
| MSI MS-7C91                       | 5         | 0.2%    |
| MSI MS-7B86                       | 5         | 0.2%    |
| MSI MS-7A34                       | 5         | 0.2%    |
| Lenovo Legion 5 15ACH6H 82JU      | 5         | 0.2%    |
| Lenovo IdeaPad 5 Pro 16ARH7 82SN  | 5         | 0.2%    |
| Lenovo IdeaPad 3 15ALC6 82MF      | 5         | 0.2%    |
| HP Pavilion 15                    | 5         | 0.2%    |
| HP Notebook                       | 5         | 0.2%    |
| Gigabyte B550M DS3H               | 5         | 0.2%    |
| Gigabyte B450M DS3H               | 5         | 0.2%    |
| Dell XPS 13 9360                  | 5         | 0.2%    |
| Dell XPS 13 9310                  | 5         | 0.2%    |
| Dell Latitude E7240               | 5         | 0.2%    |
| ASUS ROG CROSSHAIR VIII HERO      | 5         | 0.2%    |
| ASUS ROG CROSSHAIR VIII DARK HERO | 5         | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 142       | 5.54%   |
| ASUS ROG           | 121       | 4.72%   |
| Dell Inspiron      | 86        | 3.36%   |
| Lenovo IdeaPad     | 84        | 3.28%   |
| Acer Aspire        | 71        | 2.77%   |
| Dell Latitude      | 66        | 2.58%   |
| Dell XPS           | 60        | 2.34%   |
| HP Pavilion        | 48        | 1.87%   |
| ASUS PRIME         | 47        | 1.83%   |
| Dell Precision     | 42        | 1.64%   |
| ASUS TUF           | 42        | 1.64%   |
| Lenovo Legion      | 38        | 1.48%   |
| HP EliteBook       | 37        | 1.44%   |
| ASUS VivoBook      | 37        | 1.44%   |
| HP Laptop          | 31        | 1.21%   |
| HP ENVY            | 29        | 1.13%   |
| Toshiba Satellite  | 25        | 0.98%   |
| HP ProBook         | 25        | 0.98%   |
| Dell OptiPlex      | 25        | 0.98%   |
| ASUS ASUS          | 23        | 0.9%    |
| Lenovo Yoga        | 22        | 0.86%   |
| Lenovo ThinkCentre | 20        | 0.78%   |
| ASUS Zenbook       | 20        | 0.78%   |
| Gigabyte X570      | 19        | 0.74%   |
| Acer Swift         | 18        | 0.7%    |
| HP Compaq          | 17        | 0.66%   |
| ASUS All           | 17        | 0.66%   |
| Microsoft Surface  | 16        | 0.62%   |
| HP ZBook           | 16        | 0.62%   |
| Gigabyte B450      | 16        | 0.62%   |
| Acer Nitro         | 16        | 0.62%   |
| Unknown            | 16        | 0.62%   |
| Dell Vostro        | 15        | 0.59%   |
| Apple MacBookPro11 | 15        | 0.59%   |
| System76 Oryx      | 13        | 0.51%   |
| System76 Lemur     | 12        | 0.47%   |
| Lenovo ThinkBook   | 12        | 0.47%   |
| HP OMEN            | 12        | 0.47%   |
| HP EliteDesk       | 11        | 0.43%   |
| Apple MacBookPro12 | 11        | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 376       | 14.67%  |
| 2020    | 347       | 13.54%  |
| 2022    | 256       | 9.99%   |
| 2019    | 251       | 9.79%   |
| 2018    | 246       | 9.6%    |
| 2013    | 146       | 5.7%    |
| 2012    | 140       | 5.46%   |
| 2017    | 135       | 5.27%   |
| 2015    | 125       | 4.88%   |
| 2016    | 124       | 4.84%   |
| 2011    | 111       | 4.33%   |
| 2014    | 110       | 4.29%   |
| 2010    | 75        | 2.93%   |
| 2009    | 62        | 2.42%   |
| 2008    | 29        | 1.13%   |
| 2007    | 13        | 0.51%   |
| 2023    | 8         | 0.31%   |
| Unknown | 6         | 0.23%   |
| 2006    | 2         | 0.08%   |
| 2005    | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1476      | 57.59%  |
| Desktop        | 881       | 34.37%  |
| Convertible    | 95        | 3.71%   |
| Mini pc        | 44        | 1.72%   |
| All in one     | 28        | 1.09%   |
| Tablet         | 25        | 0.98%   |
| Server         | 9         | 0.35%   |
| System on chip | 5         | 0.2%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 2562      | 99.92%  |
| Enabled  | 2         | 0.08%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2515      | 98.13%  |
| Yes  | 48        | 1.87%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 693       | 26.77%  |
| 4.01-8.0        | 575       | 22.21%  |
| 8.01-16.0       | 466       | 18%     |
| 32.01-64.0      | 420       | 16.22%  |
| 3.01-4.0        | 227       | 8.77%   |
| 64.01-256.0     | 130       | 5.02%   |
| 24.01-32.0      | 59        | 2.28%   |
| 2.01-3.0        | 8         | 0.31%   |
| 1.01-2.0        | 8         | 0.31%   |
| More than 256.0 | 3         | 0.12%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 818       | 29.52%  |
| 2.01-3.0    | 800       | 28.87%  |
| 3.01-4.0    | 632       | 22.81%  |
| 1.01-2.0    | 264       | 9.53%   |
| 8.01-16.0   | 210       | 7.58%   |
| 16.01-24.0  | 30        | 1.08%   |
| 24.01-32.0  | 7         | 0.25%   |
| 32.01-64.0  | 6         | 0.22%   |
| 64.01-256.0 | 2         | 0.07%   |
| 0.51-1.0    | 2         | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1499      | 57.74%  |
| 2      | 682       | 26.27%  |
| 3      | 216       | 8.32%   |
| 4      | 96        | 3.7%    |
| 5      | 52        | 2%      |
| 6      | 21        | 0.81%   |
| 7      | 10        | 0.39%   |
| 0      | 10        | 0.39%   |
| 9      | 3         | 0.12%   |
| 10     | 2         | 0.08%   |
| 8      | 2         | 0.08%   |
| 26     | 1         | 0.04%   |
| 19     | 1         | 0.04%   |
| 11     | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1978      | 77.02%  |
| Yes       | 590       | 22.98%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2081      | 80.85%  |
| No        | 493       | 19.15%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2148      | 83.58%  |
| No        | 422       | 16.42%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1852      | 71.84%  |
| No        | 726       | 28.16%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 818       | 31.75%  |
| Brazil       | 187       | 7.26%   |
| Germany      | 172       | 6.68%   |
| UK           | 118       | 4.58%   |
| Canada       | 116       | 4.5%    |
| Italy        | 102       | 3.96%   |
| Australia    | 78        | 3.03%   |
| India        | 69        | 2.68%   |
| France       | 69        | 2.68%   |
| Netherlands  | 48        | 1.86%   |
| Russia       | 41        | 1.59%   |
| Norway       | 40        | 1.55%   |
| Poland       | 39        | 1.51%   |
| Sweden       | 35        | 1.36%   |
| Spain        | 33        | 1.28%   |
| Finland      | 32        | 1.24%   |
| Mexico       | 31        | 1.2%    |
| Portugal     | 27        | 1.05%   |
| Switzerland  | 26        | 1.01%   |
| Greece       | 26        | 1.01%   |
| Chile        | 22        | 0.85%   |
| Austria      | 22        | 0.85%   |
| Belgium      | 19        | 0.74%   |
| Romania      | 18        | 0.7%    |
| Indonesia    | 18        | 0.7%    |
| Argentina    | 18        | 0.7%    |
| Turkey       | 17        | 0.66%   |
| Philippines  | 17        | 0.66%   |
| New Zealand  | 17        | 0.66%   |
| Denmark      | 17        | 0.66%   |
| Hungary      | 16        | 0.62%   |
| Japan        | 15        | 0.58%   |
| Ireland      | 15        | 0.58%   |
| Thailand     | 14        | 0.54%   |
| South Africa | 14        | 0.54%   |
| Czechia      | 13        | 0.5%    |
| Serbia       | 11        | 0.43%   |
| Bulgaria     | 11        | 0.43%   |
| Malaysia     | 10        | 0.39%   |
| Hong Kong    | 9         | 0.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Milan            | 20        | 0.75%   |
| Helsinki         | 20        | 0.75%   |
| Berlin           | 20        | 0.75%   |
| Melbourne        | 18        | 0.68%   |
| Seattle          | 17        | 0.64%   |
| Brisbane         | 17        | 0.64%   |
| Sao Paulo        | 15        | 0.56%   |
| Vienna           | 14        | 0.53%   |
| Sydney           | 14        | 0.53%   |
| Rio de Janeiro   | 14        | 0.53%   |
| London           | 13        | 0.49%   |
| Istanbul         | 13        | 0.49%   |
| Rome             | 12        | 0.45%   |
| Oslo             | 12        | 0.45%   |
| Moscow           | 12        | 0.45%   |
| Chicago          | 12        | 0.45%   |
| Bengaluru        | 12        | 0.45%   |
| Zurich           | 11        | 0.41%   |
| Edmonton         | 10        | 0.38%   |
| Dallas           | 10        | 0.38%   |
| Santiago         | 9         | 0.34%   |
| Paris            | 9         | 0.34%   |
| New York         | 9         | 0.34%   |
| Munich           | 9         | 0.34%   |
| Minneapolis      | 9         | 0.34%   |
| Lisbon           | 9         | 0.34%   |
| Denver           | 9         | 0.34%   |
| Cleveland        | 9         | 0.34%   |
| Belgrade         | 9         | 0.34%   |
| Toronto          | 8         | 0.3%    |
| St Petersburg    | 8         | 0.3%    |
| San Jose         | 8         | 0.3%    |
| Mannheim         | 8         | 0.3%    |
| Madrid           | 8         | 0.3%    |
| Hamburg          | 8         | 0.3%    |
| Colorado Springs | 8         | 0.3%    |
| Calgary          | 8         | 0.3%    |
| Auckland         | 8         | 0.3%    |
| Athens           | 8         | 0.3%    |
| Amsterdam        | 8         | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 763       | 1081   | 19.53%  |
| WDC                         | 442       | 587    | 11.31%  |
| Seagate                     | 415       | 573    | 10.62%  |
| Sandisk                     | 294       | 368    | 7.52%   |
| Kingston                    | 191       | 226    | 4.89%   |
| Toshiba                     | 180       | 208    | 4.61%   |
| Crucial                     | 172       | 232    | 4.4%    |
| SK hynix                    | 148       | 175    | 3.79%   |
| Intel                       | 105       | 136    | 2.69%   |
| Unknown                     | 103       | 135    | 2.64%   |
| Micron Technology           | 90        | 106    | 2.3%    |
| Apple                       | 70        | 80     | 1.79%   |
| Hitachi                     | 61        | 99     | 1.56%   |
| HGST                        | 57        | 64     | 1.46%   |
| A-DATA Technology           | 55        | 60     | 1.41%   |
| Phison Electronics          | 50        | 68     | 1.28%   |
| Micron/Crucial Technology   | 50        | 65     | 1.28%   |
| Phison                      | 48        | 59     | 1.23%   |
| PNY                         | 42        | 55     | 1.07%   |
| Silicon Motion              | 35        | 43     | 0.9%    |
| China                       | 35        | 43     | 0.9%    |
| KIOXIA                      | 33        | 38     | 0.84%   |
| SPCC                        | 23        | 31     | 0.59%   |
| Kingston Technology Company | 23        | 24     | 0.59%   |
| Netac                       | 19        | 19     | 0.49%   |
| Intenso                     | 18        | 22     | 0.46%   |
| Unknown                     | 17        | 19     | 0.44%   |
| LITEON                      | 15        | 18     | 0.38%   |
| Patriot                     | 14        | 17     | 0.36%   |
| ADATA Technology            | 14        | 14     | 0.36%   |
| Realtek Semiconductor       | 13        | 13     | 0.33%   |
| Team                        | 12        | 16     | 0.31%   |
| XPG                         | 11        | 13     | 0.28%   |
| OCZ                         | 11        | 14     | 0.28%   |
| LITEONIT                    | 11        | 17     | 0.28%   |
| KingSpec                    | 11        | 12     | 0.28%   |
| JMicron Technology          | 10        | 19     | 0.26%   |
| Union Memory (Shenzhen)     | 9         | 11     | 0.23%   |
| Lexar                       | 9         | 11     | 0.23%   |
| Hewlett-Packard             | 9         | 12     | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB   | 88        | 2.03%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 48        | 1.11%   |
| Kingston SA400S37240G 240GB SSD                     | 48        | 1.11%   |
| SanDisk NVMe SSD Drive 1TB                          | 36        | 0.83%   |
| Samsung NVMe SSD Drive 1TB                          | 36        | 0.83%   |
| Samsung SSD 860 EVO 1TB                             | 31        | 0.72%   |
| Samsung SSD 850 EVO 500GB                           | 31        | 0.72%   |
| Seagate ST2000DM008-2FR102 2TB                      | 30        | 0.69%   |
| Samsung SSD 850 EVO 250GB                           | 30        | 0.69%   |
| Seagate ST1000LM035-1RK172 970GB                    | 29        | 0.67%   |
| Samsung NVMe SSD Drive 500GB                        | 29        | 0.67%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 500GB | 28        | 0.65%   |
| Sandisk WD Blue SN550 NVMe SSD 1024GB               | 25        | 0.58%   |
| Kingston SA400S37480G 480GB SSD                     | 25        | 0.58%   |
| Crucial CT1000MX500SSD1 1TB                         | 25        | 0.58%   |
| Samsung SSD 860 EVO 500GB                           | 24        | 0.55%   |
| Seagate ST1000DM010-2EP102 1TB                      | 23        | 0.53%   |
| Crucial CT240BX500SSD1 240GB                        | 23        | 0.53%   |
| Samsung NVMe SSD Drive 512GB                        | 22        | 0.51%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                 | 22        | 0.51%   |
| Kingston SA400S37120G 120GB SSD                     | 21        | 0.49%   |
| Samsung NVMe SSD Drive 2TB                          | 20        | 0.46%   |
| Phison E12 NVMe Controller 512GB                    | 20        | 0.46%   |
| Unknown MMC Card  64GB                              | 19        | 0.44%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 19        | 0.44%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB    | 18        | 0.42%   |
| Samsung SSD 980 1TB                                 | 18        | 0.42%   |
| HGST HTS721010A9E630 1TB                            | 18        | 0.42%   |
| Crucial CT500MX500SSD1 500GB                        | 18        | 0.42%   |
| Toshiba MQ01ABD100 1TB                              | 17        | 0.39%   |
| SanDisk NVMe SSD Drive 512GB                        | 17        | 0.39%   |
| Unknown                                             | 17        | 0.39%   |
| Seagate ST500DM002-1BD142 500GB                     | 16        | 0.37%   |
| Seagate ST1000DM003-1ER162 1TB                      | 16        | 0.37%   |
| Seagate Expansion 4TB                               | 16        | 0.37%   |
| Intel SSD 660P Series 512GB                         | 16        | 0.37%   |
| Unknown SD/MMC/MS PRO 249GB                         | 15        | 0.35%   |
| Unknown MMC Card  128GB                             | 15        | 0.35%   |
| SK hynix NVMe SSD Drive 512GB                       | 15        | 0.35%   |
| Seagate ST4000DM004-2CV104 4TB                      | 15        | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 398       | 545    | 37.98%  |
| WDC                 | 323       | 430    | 30.82%  |
| Toshiba             | 120       | 141    | 11.45%  |
| Hitachi             | 61        | 99     | 5.82%   |
| HGST                | 57        | 64     | 5.44%   |
| Samsung Electronics | 29        | 37     | 2.77%   |
| Apple               | 17        | 20     | 1.62%   |
| Unknown             | 16        | 20     | 1.53%   |
| JMicron Technology  | 8         | 15     | 0.76%   |
| Fujitsu             | 5         | 7      | 0.48%   |
| Maxtor              | 3         | 3      | 0.29%   |
| Intenso             | 2         | 4      | 0.19%   |
| ASMT                | 2         | 2      | 0.19%   |
| USB3.0              | 1         | 1      | 0.1%    |
| SABRENT             | 1         | 1      | 0.1%    |
| RSH-339             | 1         | 1      | 0.1%    |
| PHD 3.0             | 1         | 1      | 0.1%    |
| HGST HDN            | 1         | 1      | 0.1%    |
| ASMedia             | 1         | 1      | 0.1%    |
| Asm                 | 1         | 1      | 0.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 305       | 420    | 24.09%  |
| Crucial             | 153       | 203    | 12.09%  |
| Kingston            | 145       | 168    | 11.45%  |
| SanDisk             | 107       | 129    | 8.45%   |
| WDC                 | 74        | 88     | 5.85%   |
| Apple               | 46        | 49     | 3.63%   |
| PNY                 | 41        | 54     | 3.24%   |
| A-DATA Technology   | 38        | 41     | 3%      |
| China               | 34        | 42     | 2.69%   |
| Intel               | 26        | 32     | 2.05%   |
| SK hynix            | 24        | 29     | 1.9%    |
| SPCC                | 18        | 21     | 1.42%   |
| Micron Technology   | 18        | 18     | 1.42%   |
| Toshiba             | 17        | 17     | 1.34%   |
| Netac               | 17        | 17     | 1.34%   |
| Patriot             | 14        | 17     | 1.11%   |
| LITEON              | 13        | 16     | 1.03%   |
| OCZ                 | 11        | 14     | 0.87%   |
| LITEONIT            | 11        | 17     | 0.87%   |
| KingSpec            | 11        | 12     | 0.87%   |
| Intenso             | 11        | 13     | 0.87%   |
| Transcend           | 8         | 10     | 0.63%   |
| Team                | 7         | 10     | 0.55%   |
| Hewlett-Packard     | 7         | 10     | 0.55%   |
| Lexar               | 6         | 7      | 0.47%   |
| GOODRAM             | 5         | 5      | 0.39%   |
| Apacer              | 5         | 9      | 0.39%   |
| Seagate             | 4         | 5      | 0.32%   |
| Mushkin             | 4         | 6      | 0.32%   |
| KingDian            | 4         | 7      | 0.32%   |
| Unknown             | 4         | 4      | 0.32%   |
| MyDigitalSSD        | 3         | 3      | 0.24%   |
| Fanxiang            | 3         | 3      | 0.24%   |
| Dogfish             | 3         | 3      | 0.24%   |
| TrekStor            | 2         | 2      | 0.16%   |
| TO Exter            | 2         | 2      | 0.16%   |
| PNY USB             | 2         | 2      | 0.16%   |
| OWC                 | 2         | 2      | 0.16%   |
| Leven               | 2         | 2      | 0.16%   |
| INTEL SS            | 2         | 4      | 0.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 1320      | 1888   | 38.12%  |
| SSD     | 1096      | 1581   | 31.65%  |
| HDD     | 890       | 1394   | 25.7%   |
| MMC     | 84        | 97     | 2.43%   |
| Unknown | 73        | 119    | 2.11%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1600      | 2825   | 50.38%  |
| NVMe | 1318      | 1873   | 41.5%   |
| SAS  | 174       | 284    | 5.48%   |
| MMC  | 84        | 97     | 2.64%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1085      | 1555   | 51.57%  |
| 0.51-1.0   | 671       | 896    | 31.89%  |
| 1.01-2.0   | 196       | 271    | 9.32%   |
| 3.01-4.0   | 69        | 98     | 3.28%   |
| 4.01-10.0  | 47        | 94     | 2.23%   |
| 2.01-3.0   | 29        | 48     | 1.38%   |
| 10.01-20.0 | 7         | 13     | 0.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 710       | 26.99%  |
| 251-500        | 671       | 25.5%   |
| 501-1000       | 569       | 21.63%  |
| 1001-2000      | 252       | 9.58%   |
| More than 3000 | 137       | 5.21%   |
| 2001-3000      | 95        | 3.61%   |
| 51-100         | 80        | 3.04%   |
| 1-20           | 61        | 2.32%   |
| 21-50          | 40        | 1.52%   |
| Unknown        | 16        | 0.61%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 783       | 28.66%  |
| 21-50          | 604       | 22.11%  |
| 101-250        | 406       | 14.86%  |
| 51-100         | 352       | 12.88%  |
| 251-500        | 260       | 9.52%   |
| 501-1000       | 155       | 5.67%   |
| 1001-2000      | 78        | 2.86%   |
| More than 3000 | 47        | 1.72%   |
| 2001-3000      | 31        | 1.13%   |
| Unknown        | 16        | 0.59%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                       | Computers | Drives | Percent |
|---------------------------------------------|-----------|--------|---------|
| SK hynix PC711 HFS001TDE9X073N 1TB          | 3         | 3      | 4.11%   |
| HGST HTS725050A7E630 500GB                  | 3         | 4      | 4.11%   |
| WDC WD10JPVX-60JC3T0 1TB                    | 2         | 2      | 2.74%   |
| Seagate ST1000LM024 HN-M101MBB 1TB          | 2         | 2      | 2.74%   |
| WDC WDS240G2G0A-00JH30 240GB SSD            | 1         | 1      | 1.37%   |
| WDC WD60EFRX-68L0BN1 6TB                    | 1         | 1      | 1.37%   |
| WDC WD5001AALS-00J7B1 500GB                 | 1         | 1      | 1.37%   |
| WDC WD5000AADS-00S9B0 500GB                 | 1         | 1      | 1.37%   |
| WDC WD3200BEKT-60PVMT0 320GB                | 1         | 1      | 1.37%   |
| WDC WD20EFRX-68AX9N0 2TB                    | 1         | 5      | 1.37%   |
| WDC WD15EADS-00P8B0 1TB                     | 1         | 1      | 1.37%   |
| WDC WD10SPZX-22Z10T0 1TB                    | 1         | 1      | 1.37%   |
| WDC WD10JPVX-60JC3T1 1TB                    | 1         | 1      | 1.37%   |
| WDC WD10EZEX-60WN4A0 1TB                    | 1         | 1      | 1.37%   |
| WDC WD1002FAEX-00Z3A0 1TB                   | 1         | 1      | 1.37%   |
| WDC WD1001FALS-00E8B0 1TB                   | 1         | 1      | 1.37%   |
| WDC PC SN520 SDAPMUW-128G-1001 128GB        | 1         | 1      | 1.37%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD    | 1         | 1      | 1.37%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD    | 1         | 1      | 1.37%   |
| Toshiba MQ04ABF100 1TB                      | 1         | 1      | 1.37%   |
| Toshiba MQ01ACF050 500GB                    | 1         | 1      | 1.37%   |
| Toshiba MK1655GSX 160GB                     | 1         | 1      | 1.37%   |
| Team TM8FP4004T 4TB                         | 1         | 1      | 1.37%   |
| SK hynix HFS512G39TND-N210A 512GB SSD       | 1         | 1      | 1.37%   |
| SK hynix BC501 NVMe Solid State Drive 512GB | 1         | 1      | 1.37%   |
| Seagate STM3500418AS 500GB                  | 1         | 1      | 1.37%   |
| Seagate ST9320325AS 320GB                   | 1         | 1      | 1.37%   |
| Seagate ST6000AS0002-1N917X 6TB             | 1         | 1      | 1.37%   |
| Seagate ST500LM030-2E717D 500GB             | 1         | 1      | 1.37%   |
| Seagate ST5000LM000-2AN170 5TB              | 1         | 1      | 1.37%   |
| Seagate ST320LM001 HN-M320MBB 320GB         | 1         | 1      | 1.37%   |
| Seagate ST2000DM008-2FR102 2TB              | 1         | 1      | 1.37%   |
| Seagate ST2000DM006-2DM164 2TB              | 1         | 1      | 1.37%   |
| Seagate ST2000DM001-1CH164 2TB              | 1         | 1      | 1.37%   |
| Seagate ST1500DL003-9VT16L 1TB              | 1         | 1      | 1.37%   |
| Seagate ST1000LX015-1U7172 1TB              | 1         | 1      | 1.37%   |
| Seagate Expansion Desk 8TB                  | 1         | 1      | 1.37%   |
| Samsung Electronics SSD 870 EVO 500GB       | 1         | 1      | 1.37%   |
| Samsung Electronics SSD 850 PRO 256GB       | 1         | 1      | 1.37%   |
| Samsung Electronics SSD 850 EVO 500GB       | 1         | 1      | 1.37%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 15        | 19     | 21.13%  |
| Seagate             | 12        | 14     | 16.9%   |
| Samsung Electronics | 9         | 9      | 12.68%  |
| HGST                | 6         | 7      | 8.45%   |
| Toshiba             | 5         | 5      | 7.04%   |
| SK hynix            | 5         | 5      | 7.04%   |
| Hitachi             | 3         | 5      | 4.23%   |
| Micron Technology   | 2         | 4      | 2.82%   |
| Kingston            | 2         | 3      | 2.82%   |
| Intel               | 2         | 2      | 2.82%   |
| Crucial             | 2         | 2      | 2.82%   |
| A-DATA Technology   | 2         | 2      | 2.82%   |
| Team                | 1         | 1      | 1.41%   |
| SABRENT             | 1         | 1      | 1.41%   |
| Plextor             | 1         | 1      | 1.41%   |
| Lexar               | 1         | 1      | 1.41%   |
| Leven               | 1         | 1      | 1.41%   |
| BAITITON            | 1         | 1      | 1.41%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 13        | 17     | 33.33%  |
| Seagate             | 12        | 14     | 30.77%  |
| HGST                | 6         | 7      | 15.38%  |
| Toshiba             | 3         | 3      | 7.69%   |
| Hitachi             | 3         | 5      | 7.69%   |
| Samsung Electronics | 2         | 2      | 5.13%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 38        | 48     | 54.29%  |
| SSD  | 19        | 20     | 27.14%  |
| NVMe | 13        | 15     | 18.57%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 1         | 1      | 33.33%  |
| Samsung Electronics HM321HI 320GB | 1         | 1      | 33.33%  |
| KingDian S400 120GB SSD           | 1         | 2      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1         | 1      | 33.33%  |
| Samsung Electronics | 1         | 1      | 33.33%  |
| KingDian            | 1         | 2      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2018      | 3987   | 74.27%  |
| Works    | 629       | 1005   | 23.15%  |
| Malfunc  | 67        | 83     | 2.47%   |
| Failed   | 3         | 4      | 0.11%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 1420      | 38.67%  |
| AMD                            | 657       | 17.89%  |
| Samsung Electronics            | 525       | 14.3%   |
| SanDisk                        | 241       | 6.56%   |
| SK hynix                       | 124       | 3.38%   |
| Phison Electronics             | 106       | 2.89%   |
| Micron Technology              | 72        | 1.96%   |
| Micron/Crucial Technology      | 69        | 1.88%   |
| Kingston Technology Company    | 67        | 1.82%   |
| ASMedia Technology             | 52        | 1.42%   |
| Toshiba America Info Systems   | 46        | 1.25%   |
| Silicon Motion                 | 41        | 1.12%   |
| Nvidia                         | 35        | 0.95%   |
| KIOXIA                         | 33        | 0.9%    |
| ADATA Technology               | 33        | 0.9%    |
| Marvell Technology Group       | 30        | 0.82%   |
| Realtek Semiconductor          | 20        | 0.54%   |
| Solid State Storage Technology | 15        | 0.41%   |
| JMicron Technology             | 14        | 0.38%   |
| Union Memory (Shenzhen)        | 12        | 0.33%   |
| Seagate Technology             | 9         | 0.25%   |
| Apple                          | 9         | 0.25%   |
| Broadcom / LSI                 | 7         | 0.19%   |
| Shenzhen Longsys Electronics   | 6         | 0.16%   |
| LSI Logic / Symbios Logic      | 5         | 0.14%   |
| MAXIO Technology (Hangzhou)    | 4         | 0.11%   |
| Lite-On Technology             | 4         | 0.11%   |
| INNOGRIT                       | 4         | 0.11%   |
| Hewlett-Packard                | 3         | 0.08%   |
| Solidigm                       | 2         | 0.05%   |
| Silicon Image                  | 2         | 0.05%   |
| Yangtze Memory Technologies    | 1         | 0.03%   |
| VIA Technologies               | 1         | 0.03%   |
| O2 Micro                       | 1         | 0.03%   |
| Netac Technology               | 1         | 0.03%   |
| Adaptec                        | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 477       | 11.74%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 230       | 5.66%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 113       | 2.78%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 109       | 2.68%   |
| AMD 500 Series Chipset SATA Controller                                         | 108       | 2.66%   |
| Samsung NVMe SSD Controller 980                                                | 106       | 2.61%   |
| Intel Volume Management Device NVMe RAID Controller                            | 105       | 2.58%   |
| AMD 400 Series Chipset SATA Controller                                         | 99        | 2.44%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 95        | 2.34%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 84        | 2.07%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 77        | 1.9%    |
| Micron NVMe Storage Controller                                                 | 69        | 1.7%    |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 66        | 1.62%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 66        | 1.62%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 61        | 1.5%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 51        | 1.26%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 51        | 1.26%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 50        | 1.23%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 49        | 1.21%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 48        | 1.18%   |
| Phison E12 NVMe Controller                                                     | 46        | 1.13%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 46        | 1.13%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 43        | 1.06%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 42        | 1.03%   |
| Intel SSD 660P Series                                                          | 39        | 0.96%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 38        | 0.94%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 37        | 0.91%   |
| Sandisk Non-Volatile memory controller                                         | 36        | 0.89%   |
| Intel Comet Lake SATA AHCI Controller                                          | 36        | 0.89%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 35        | 0.86%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 33        | 0.81%   |
| Intel SATA Controller [RAID mode]                                              | 32        | 0.79%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 32        | 0.79%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 30        | 0.74%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 30        | 0.74%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 29        | 0.71%   |
| Kingston Company Company Non-Volatile memory controller                        | 28        | 0.69%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 28        | 0.69%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 28        | 0.69%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 27        | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1833      | 51.49%  |
| NVMe | 1313      | 36.88%  |
| RAID | 250       | 7.02%   |
| IDE  | 151       | 4.24%   |
| SAS  | 12        | 0.34%   |
| SCSI | 1         | 0.03%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 1720      | 67.11%  |
| AMD    | 839       | 32.74%  |
| ARM    | 4         | 0.16%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 41        | 1.6%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 38        | 1.48%   |
| AMD Ryzen 5 3600 6-Core Processor             | 34        | 1.32%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 32        | 1.25%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 30        | 1.17%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 29        | 1.13%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 29        | 1.13%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 25        | 0.97%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 25        | 0.97%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 25        | 0.97%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 24        | 0.93%   |
| Intel 12th Gen Core i7-12700H                 | 24        | 0.93%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 23        | 0.9%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 23        | 0.9%    |
| AMD Ryzen 5 5600G with Radeon Graphics        | 23        | 0.9%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 22        | 0.86%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 22        | 0.86%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 21        | 0.82%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 21        | 0.82%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 21        | 0.82%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 20        | 0.78%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 20        | 0.78%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 20        | 0.78%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 18        | 0.7%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 18        | 0.7%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 17        | 0.66%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 17        | 0.66%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 15        | 0.58%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 15        | 0.58%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 15        | 0.58%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 14        | 0.55%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 13        | 0.51%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 13        | 0.51%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 13        | 0.51%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 13        | 0.51%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 13        | 0.51%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 13        | 0.51%   |
| AMD Ryzen 7 PRO 5850U with Radeon Graphics    | 13        | 0.51%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 12        | 0.47%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 12        | 0.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 547       | 21.32%  |
| Intel Core i5           | 485       | 18.9%   |
| Other                   | 309       | 12.04%  |
| AMD Ryzen 5             | 267       | 10.41%  |
| AMD Ryzen 7             | 263       | 10.25%  |
| Intel Core i3           | 118       | 4.6%    |
| AMD Ryzen 9             | 101       | 3.94%   |
| Intel Celeron           | 65        | 2.53%   |
| Intel Core 2 Duo        | 61        | 2.38%   |
| Intel Xeon              | 57        | 2.22%   |
| AMD FX                  | 31        | 1.21%   |
| AMD Ryzen 3             | 27        | 1.05%   |
| Intel Pentium           | 22        | 0.86%   |
| Intel Core i9           | 21        | 0.82%   |
| AMD Ryzen 7 PRO         | 19        | 0.74%   |
| AMD A8                  | 17        | 0.66%   |
| AMD A10                 | 16        | 0.62%   |
| AMD A6                  | 12        | 0.47%   |
| Intel Core 2 Quad       | 9         | 0.35%   |
| AMD Ryzen Threadripper  | 9         | 0.35%   |
| AMD Ryzen 5 PRO         | 9         | 0.35%   |
| AMD Athlon              | 8         | 0.31%   |
| Intel Pentium Silver    | 7         | 0.27%   |
| Intel Pentium Dual-Core | 7         | 0.27%   |
| AMD A4                  | 7         | 0.27%   |
| Intel Pentium Gold      | 6         | 0.23%   |
| Intel Core 2            | 4         | 0.16%   |
| Intel Atom              | 4         | 0.16%   |
| AMD Ryzen 3 PRO         | 4         | 0.16%   |
| AMD Phenom II X4        | 4         | 0.16%   |
| AMD Athlon II X4        | 4         | 0.16%   |
| AMD Athlon II X2        | 4         | 0.16%   |
| Intel Pentium D         | 3         | 0.12%   |
| AMD Phenom II X6        | 3         | 0.12%   |
| AMD Phenom              | 3         | 0.12%   |
| AMD Athlon X4           | 3         | 0.12%   |
| Intel Pentium Dual      | 2         | 0.08%   |
| Intel Genuine           | 2         | 0.08%   |
| Intel Core m5           | 2         | 0.08%   |
| Intel Core M            | 2         | 0.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 878       | 34.22%  |
| 2       | 666       | 25.95%  |
| 8       | 388       | 15.12%  |
| 6       | 383       | 14.93%  |
| 12      | 77        | 3%      |
| 16      | 55        | 2.14%   |
| 14      | 43        | 1.68%   |
| 10      | 37        | 1.44%   |
| 3       | 13        | 0.51%   |
| 1       | 11        | 0.43%   |
| 24      | 5         | 0.19%   |
| Unknown | 4         | 0.16%   |
| 32      | 2         | 0.08%   |
| 64      | 1         | 0.04%   |
| 40      | 1         | 0.04%   |
| 36      | 1         | 0.04%   |
| 18      | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2546      | 99.34%  |
| 2       | 13        | 0.51%   |
| Unknown | 4         | 0.16%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2106      | 82.11%  |
| 1       | 455       | 17.74%  |
| Unknown | 4         | 0.16%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2560      | 99.88%  |
| 64-bit         | 3         | 0.12%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1986      | 76.33%  |
| 0x806c1    | 49        | 1.88%   |
| 0x0a50000c | 37        | 1.42%   |
| 0x806ec    | 26        | 1%      |
| 0x806ea    | 24        | 0.92%   |
| 0x806d1    | 24        | 0.92%   |
| 0x906a3    | 23        | 0.88%   |
| 0x306a9    | 21        | 0.81%   |
| 0x08701021 | 21        | 0.81%   |
| 0x906ea    | 20        | 0.77%   |
| 0xa0652    | 19        | 0.73%   |
| 0x08608103 | 18        | 0.69%   |
| 0x08600106 | 18        | 0.69%   |
| 0x0a404101 | 15        | 0.58%   |
| 0x506e3    | 14        | 0.54%   |
| 0x406e3    | 14        | 0.54%   |
| 0x0a201016 | 14        | 0.54%   |
| 0x206a7    | 13        | 0.5%    |
| 0x08108109 | 13        | 0.5%    |
| 0x906a4    | 12        | 0.46%   |
| 0x806e9    | 12        | 0.46%   |
| 0x40651    | 12        | 0.46%   |
| 0x306c3    | 12        | 0.46%   |
| 0x906e9    | 11        | 0.42%   |
| 0x0800820d | 11        | 0.42%   |
| 0x306d4    | 9         | 0.35%   |
| 0x706e5    | 8         | 0.31%   |
| 0x1067a    | 8         | 0.31%   |
| 0x0a50000d | 8         | 0.31%   |
| 0x0a404102 | 8         | 0.31%   |
| 0x08600104 | 8         | 0.31%   |
| 0x706a8    | 7         | 0.27%   |
| 0x0a601203 | 6         | 0.23%   |
| 0x906ec    | 5         | 0.19%   |
| 0x90672    | 5         | 0.19%   |
| 0x806eb    | 5         | 0.19%   |
| 0x08701013 | 5         | 0.19%   |
| 0x906ed    | 4         | 0.15%   |
| 0x906c0    | 4         | 0.15%   |
| 0x0a201205 | 4         | 0.15%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 401       | 15.61%  |
| Zen 3            | 246       | 9.58%   |
| Unknown          | 243       | 9.46%   |
| Haswell          | 220       | 8.56%   |
| Zen 2            | 170       | 6.62%   |
| SandyBridge      | 132       | 5.14%   |
| IvyBridge        | 128       | 4.98%   |
| Skylake          | 126       | 4.9%    |
| TigerLake        | 120       | 4.67%   |
| Zen+             | 114       | 4.44%   |
| CometLake        | 80        | 3.11%   |
| Broadwell        | 78        | 3.04%   |
| Penryn           | 70        | 2.72%   |
| Zen              | 57        | 2.22%   |
| IceLake          | 50        | 1.95%   |
| Alderlake Hybrid | 48        | 1.87%   |
| Westmere         | 45        | 1.75%   |
| Piledriver       | 44        | 1.71%   |
| Goldmont plus    | 32        | 1.25%   |
| Nehalem          | 26        | 1.01%   |
| Silvermont       | 25        | 0.97%   |
| K10              | 23        | 0.9%    |
| Excavator        | 19        | 0.74%   |
| Core             | 17        | 0.66%   |
| Puma             | 15        | 0.58%   |
| Steamroller      | 12        | 0.47%   |
| K10 Llano        | 6         | 0.23%   |
| Goldmont         | 5         | 0.19%   |
| Tremont          | 3         | 0.12%   |
| NetBurst         | 3         | 0.12%   |
| K8 Hammer        | 3         | 0.12%   |
| Jaguar           | 3         | 0.12%   |
| Bulldozer        | 2         | 0.08%   |
| Bobcat           | 2         | 0.08%   |
| K8 & K10 hybrid  | 1         | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 1327      | 42.19%  |
| Nvidia                     | 1006      | 31.99%  |
| AMD                        | 808       | 25.69%  |
| Matrox Electronics Systems | 4         | 0.13%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 107       | 3.32%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 104       | 3.23%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 93        | 2.88%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 75        | 2.33%   |
| Intel UHD Graphics 620                                                      | 72        | 2.23%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 72        | 2.23%   |
| AMD Renoir                                                                  | 67        | 2.08%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 66        | 2.05%   |
| Intel Alder Lake-P Integrated Graphics Controller                           | 64        | 1.99%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 60        | 1.86%   |
| AMD Lucienne                                                                | 56        | 1.74%   |
| Intel HD Graphics 620                                                       | 52        | 1.61%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 51        | 1.58%   |
| Intel HD Graphics 5500                                                      | 46        | 1.43%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 45        | 1.4%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 44        | 1.36%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 43        | 1.33%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 42        | 1.3%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 41        | 1.27%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 41        | 1.27%   |
| AMD Rembrandt [Radeon 680M]                                                 | 40        | 1.24%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 37        | 1.15%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                  | 34        | 1.05%   |
| Intel HD Graphics 530                                                       | 34        | 1.05%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 32        | 0.99%   |
| Intel HD Graphics 630                                                       | 32        | 0.99%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 29        | 0.9%    |
| Intel Core Processor Integrated Graphics Controller                         | 29        | 0.9%    |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 29        | 0.9%    |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 27        | 0.84%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 26        | 0.81%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 25        | 0.78%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 23        | 0.71%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 23        | 0.71%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 22        | 0.68%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 20        | 0.62%   |
| AMD Raphael                                                                 | 20        | 0.62%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 19        | 0.59%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 19        | 0.59%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 19        | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| 1 x Intel            | 879       | 34.08%  |
| 1 x AMD              | 586       | 22.72%  |
| 1 x Nvidia           | 502       | 19.46%  |
| Intel + Nvidia       | 364       | 14.11%  |
| AMD + Nvidia         | 123       | 4.77%   |
| Intel + AMD          | 50        | 1.94%   |
| 2 x AMD              | 48        | 1.86%   |
| 2 x Nvidia           | 11        | 0.43%   |
| Other                | 7         | 0.27%   |
| 1 x Matrox           | 4         | 0.16%   |
| Intel + 2 x Nvidia   | 3         | 0.12%   |
| 2 x AMD + 1 x Nvidia | 1         | 0.04%   |
| AMD + 2 x Nvidia     | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1707      | 66.01%  |
| Proprietary | 816       | 31.55%  |
| Unknown     | 63        | 2.44%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2088      | 80.22%  |
| 7.01-8.0   | 104       | 4%      |
| 1.01-2.0   | 92        | 3.53%   |
| 0.01-0.5   | 86        | 3.3%    |
| 3.01-4.0   | 75        | 2.88%   |
| 5.01-6.0   | 62        | 2.38%   |
| 8.01-16.0  | 54        | 2.07%   |
| 0.51-1.0   | 23        | 0.88%   |
| 2.01-3.0   | 13        | 0.5%    |
| 16.01-24.0 | 5         | 0.19%   |
| 32.01-64.0 | 1         | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 341       | 11.58%  |
| Samsung Electronics     | 332       | 11.27%  |
| BOE                     | 279       | 9.47%   |
| Chimei Innolux          | 268       | 9.1%    |
| LG Display              | 236       | 8.01%   |
| Goldstar                | 193       | 6.55%   |
| Dell                    | 181       | 6.14%   |
| Apple                   | 98        | 3.33%   |
| Acer                    | 94        | 3.19%   |
| Hewlett-Packard         | 83        | 2.82%   |
| AOC                     | 73        | 2.48%   |
| Sharp                   | 72        | 2.44%   |
| ASUSTek Computer        | 63        | 2.14%   |
| Ancor Communications    | 57        | 1.93%   |
| BenQ                    | 55        | 1.87%   |
| PANDA                   | 48        | 1.63%   |
| Lenovo                  | 48        | 1.63%   |
| Philips                 | 39        | 1.32%   |
| InfoVision              | 26        | 0.88%   |
| MSI                     | 22        | 0.75%   |
| Iiyama                  | 22        | 0.75%   |
| CSO                     | 21        | 0.71%   |
| ViewSonic               | 16        | 0.54%   |
| Sceptre Tech            | 16        | 0.54%   |
| Chi Mei Optoelectronics | 16        | 0.54%   |
| Sony                    | 14        | 0.48%   |
| NEC Computers           | 14        | 0.48%   |
| Gigabyte Technology     | 11        | 0.37%   |
| Vizio                   | 9         | 0.31%   |
| Panasonic               | 9         | 0.31%   |
| Vestel Elektronik       | 7         | 0.24%   |
| Unknown                 | 7         | 0.24%   |
| TMX                     | 7         | 0.24%   |
| Toshiba                 | 6         | 0.2%    |
| Insignia                | 6         | 0.2%    |
| Hitachi                 | 5         | 0.17%   |
| Eizo                    | 5         | 0.17%   |
| Viotek                  | 4         | 0.14%   |
| Valve                   | 4         | 0.14%   |
| Pioneer                 | 4         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch       | 19        | 0.63%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                | 17        | 0.56%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 17        | 0.56%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch         | 17        | 0.56%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 15        | 0.49%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch       | 15        | 0.49%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch        | 12        | 0.4%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 11        | 0.36%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 10        | 0.33%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch         | 10        | 0.33%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch          | 10        | 0.33%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch           | 9         | 0.3%    |
| Chimei Innolux LCD Monitor CMN1408 1920x1080 309x173mm 13.9-inch       | 9         | 0.3%    |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch           | 8         | 0.26%   |
| InfoVision LCD Monitor IVO8C78 1920x1080 309x174mm 14.0-inch           | 8         | 0.26%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 8         | 0.26%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                  | 8         | 0.26%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                   | 8         | 0.26%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 7         | 0.23%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch            | 7         | 0.23%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                | 7         | 0.23%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch       | 7         | 0.23%   |
| BOE LCD Monitor BOE08DF 1920x1080 344x194mm 15.5-inch                  | 7         | 0.23%   |
| BOE LCD Monitor BOE08A8 1920x1080 344x194mm 15.5-inch                  | 7         | 0.23%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch          | 7         | 0.23%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch       | 7         | 0.23%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch    | 6         | 0.2%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 6         | 0.2%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch            | 6         | 0.2%    |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 6         | 0.2%    |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                  | 6         | 0.2%    |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                      | 6         | 0.2%    |
| Dell P2317H DEL40F4 1920x1080 509x286mm 23.0-inch                      | 6         | 0.2%    |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch        | 6         | 0.2%    |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                  | 6         | 0.2%    |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                  | 6         | 0.2%    |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch         | 6         | 0.2%    |
| AU Optronics LCD Monitor AUO80ED 1920x1080 344x193mm 15.5-inch         | 6         | 0.2%    |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch          | 6         | 0.2%    |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch         | 6         | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1336      | 47.82%  |
| 1366x768 (WXGA)    | 375       | 13.42%  |
| 3840x2160 (4K)     | 239       | 8.55%   |
| 2560x1440 (QHD)    | 196       | 7.02%   |
| 1920x1200 (WUXGA)  | 79        | 2.83%   |
| 1600x900 (HD+)     | 75        | 2.68%   |
| 3440x1440          | 63        | 2.25%   |
| 2560x1600          | 51        | 1.83%   |
| 2560x1080          | 51        | 1.83%   |
| 1440x900 (WXGA+)   | 45        | 1.61%   |
| 2880x1800          | 37        | 1.32%   |
| 1280x1024 (SXGA)   | 36        | 1.29%   |
| 1280x800 (WXGA)    | 33        | 1.18%   |
| 1680x1050 (WSXGA+) | 31        | 1.11%   |
| 3840x1080          | 19        | 0.68%   |
| 1360x768           | 14        | 0.5%    |
| 3840x2400          | 11        | 0.39%   |
| 1920x540           | 11        | 0.39%   |
| 2160x1440          | 10        | 0.36%   |
| 2256x1504          | 8         | 0.29%   |
| Unknown            | 8         | 0.29%   |
| 3200x1800 (QHD+)   | 6         | 0.21%   |
| 3840x1600          | 5         | 0.18%   |
| 2736x1824          | 5         | 0.18%   |
| 1600x1200          | 5         | 0.18%   |
| 3456x2160          | 4         | 0.14%   |
| 3200x2000          | 4         | 0.14%   |
| 3072x1920          | 4         | 0.14%   |
| 1920x1280          | 4         | 0.14%   |
| 1024x768 (XGA)     | 4         | 0.14%   |
| 3000x2000          | 3         | 0.11%   |
| 1280x720 (HD)      | 3         | 0.11%   |
| 800x1280           | 2         | 0.07%   |
| 4480x1440          | 2         | 0.07%   |
| 3840x1100          | 2         | 0.07%   |
| 2304x1440          | 2         | 0.07%   |
| 3840x1200          | 1         | 0.04%   |
| 3280x1080          | 1         | 0.04%   |
| 3120x2080          | 1         | 0.04%   |
| 3040x900           | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 741       | 25.09%  |
| 13      | 336       | 11.38%  |
| 27      | 272       | 9.21%   |
| 14      | 226       | 7.65%   |
| 24      | 215       | 7.28%   |
| 23      | 174       | 5.89%   |
| 17      | 135       | 4.57%   |
| 21      | 123       | 4.17%   |
| 31      | 116       | 3.93%   |
| 34      | 104       | 3.52%   |
| 12      | 49        | 1.66%   |
| 19      | 47        | 1.59%   |
| Unknown | 46        | 1.56%   |
| 16      | 43        | 1.46%   |
| 32      | 35        | 1.19%   |
| 84      | 30        | 1.02%   |
| 18      | 28        | 0.95%   |
| 22      | 23        | 0.78%   |
| 72      | 22        | 0.75%   |
| 20      | 21        | 0.71%   |
| 48      | 19        | 0.64%   |
| 11      | 18        | 0.61%   |
| 40      | 15        | 0.51%   |
| 28      | 12        | 0.41%   |
| 25      | 10        | 0.34%   |
| 54      | 9         | 0.3%    |
| 35      | 8         | 0.27%   |
| 26      | 8         | 0.27%   |
| 37      | 7         | 0.24%   |
| 33      | 7         | 0.24%   |
| 49      | 6         | 0.2%    |
| 29      | 6         | 0.2%    |
| 65      | 5         | 0.17%   |
| 47      | 4         | 0.14%   |
| 46      | 4         | 0.14%   |
| 36      | 4         | 0.14%   |
| 74      | 3         | 0.1%    |
| 42      | 3         | 0.1%    |
| 75      | 2         | 0.07%   |
| 60      | 2         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 1167      | 40.49%  |
| 501-600     | 592       | 20.54%  |
| 201-300     | 248       | 8.61%   |
| 401-500     | 217       | 7.53%   |
| 601-700     | 164       | 5.69%   |
| 351-400     | 149       | 5.17%   |
| 701-800     | 145       | 5.03%   |
| 1501-2000   | 59        | 2.05%   |
| 1001-1500   | 54        | 1.87%   |
| Unknown     | 46        | 1.6%    |
| 801-900     | 34        | 1.18%   |
| 901-1000    | 5         | 0.17%   |
| 101-200     | 1         | 0.03%   |
| 1-100       | 1         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2043      | 78.1%   |
| 16/10   | 316       | 12.08%  |
| 21/9    | 121       | 4.63%   |
| 5/4     | 38        | 1.45%   |
| 3/2     | 30        | 1.15%   |
| 32/9    | 23        | 0.88%   |
| Unknown | 21        | 0.8%    |
| 4/3     | 15        | 0.57%   |
| 3.40    | 2         | 0.08%   |
| 6/5     | 1         | 0.04%   |
| 3.73    | 1         | 0.04%   |
| 3.20    | 1         | 0.04%   |
| 0.67    | 1         | 0.04%   |
| 0.63    | 1         | 0.04%   |
| 0.62    | 1         | 0.04%   |
| 0.56    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 742       | 25.42%  |
| 81-90          | 428       | 14.66%  |
| 201-250        | 420       | 14.39%  |
| 301-350        | 281       | 9.63%   |
| 351-500        | 272       | 9.32%   |
| 71-80          | 137       | 4.69%   |
| 121-130        | 107       | 3.67%   |
| 151-200        | 99        | 3.39%   |
| More than 1000 | 84        | 2.88%   |
| 251-300        | 80        | 2.74%   |
| 501-1000       | 61        | 2.09%   |
| 141-150        | 46        | 1.58%   |
| Unknown        | 46        | 1.58%   |
| 61-70          | 39        | 1.34%   |
| 111-120        | 39        | 1.34%   |
| 51-60          | 20        | 0.69%   |
| 131-140        | 9         | 0.31%   |
| 91-100         | 7         | 0.24%   |
| 1-40           | 2         | 0.07%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 897       | 31.82%  |
| 51-100        | 831       | 29.48%  |
| 101-120       | 642       | 22.77%  |
| 161-240       | 239       | 8.48%   |
| More than 240 | 98        | 3.48%   |
| 1-50          | 66        | 2.34%   |
| Unknown       | 46        | 1.63%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1979      | 75.88%  |
| 2     | 469       | 17.98%  |
| 0     | 83        | 3.18%   |
| 3     | 70        | 2.68%   |
| 4     | 6         | 0.23%   |
| 6     | 1         | 0.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1376      | 35.5%   |
| Intel                             | 1356      | 34.98%  |
| Qualcomm Atheros                  | 358       | 9.24%   |
| Broadcom                          | 193       | 4.98%   |
| MediaTek                          | 112       | 2.89%   |
| Broadcom Limited                  | 66        | 1.7%    |
| TP-Link                           | 44        | 1.14%   |
| Marvell Technology Group          | 31        | 0.8%    |
| ASIX Electronics                  | 29        | 0.75%   |
| Nvidia                            | 25        | 0.64%   |
| Ralink Technology                 | 23        | 0.59%   |
| Samsung Electronics               | 22        | 0.57%   |
| Ralink                            | 20        | 0.52%   |
| NetGear                           | 19        | 0.49%   |
| DisplayLink                       | 16        | 0.41%   |
| Xiaomi                            | 15        | 0.39%   |
| Microsoft                         | 11        | 0.28%   |
| Dell                              | 11        | 0.28%   |
| Aquantia                          | 11        | 0.28%   |
| Qualcomm                          | 10        | 0.26%   |
| InterBiometrics                   | 9         | 0.23%   |
| Sierra Wireless                   | 8         | 0.21%   |
| Lenovo                            | 8         | 0.21%   |
| Google                            | 8         | 0.21%   |
| D-Link                            | 8         | 0.21%   |
| D-Link System                     | 7         | 0.18%   |
| OnePlus Technology (Shenzhen)     | 6         | 0.15%   |
| ASUSTek Computer                  | 6         | 0.15%   |
| Qualcomm Atheros Communications   | 5         | 0.13%   |
| OPPO Electronics                  | 5         | 0.13%   |
| JMicron Technology                | 5         | 0.13%   |
| Huawei Technologies               | 5         | 0.13%   |
| Hewlett-Packard                   | 5         | 0.13%   |
| Linksys                           | 4         | 0.1%    |
| Ericsson Business Mobile Networks | 4         | 0.1%    |
| Mellanox Technologies             | 3         | 0.08%   |
| U-Blox                            | 2         | 0.05%   |
| Motorola PCS                      | 2         | 0.05%   |
| Fibocom                           | 2         | 0.05%   |
| Belkin Components                 | 2         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 880       | 19.18%  |
| Intel Wi-Fi 6 AX200                                               | 220       | 4.79%   |
| Realtek RTL8125 2.5GbE Controller                                 | 130       | 2.83%   |
| Intel I211 Gigabit Network Connection                             | 111       | 2.42%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 99        | 2.16%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 96        | 2.09%   |
| Intel Wi-Fi 6 AX201                                               | 94        | 2.05%   |
| Intel Wireless 8265 / 8275                                        | 86        | 1.87%   |
| Intel Ethernet Controller I225-V                                  | 81        | 1.77%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 73        | 1.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 69        | 1.5%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 64        | 1.39%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 61        | 1.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 57        | 1.24%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 55        | 1.2%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 53        | 1.15%   |
| Intel Wireless 7265                                               | 52        | 1.13%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 50        | 1.09%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 49        | 1.07%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 47        | 1.02%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 45        | 0.98%   |
| Intel Wireless 8260                                               | 44        | 0.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 43        | 0.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 40        | 0.87%   |
| Intel Wireless 7260                                               | 39        | 0.85%   |
| Intel Ethernet Connection I217-LM                                 | 38        | 0.83%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 38        | 0.83%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 37        | 0.81%   |
| Intel Wireless-AC 9260                                            | 35        | 0.76%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 31        | 0.68%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 30        | 0.65%   |
| Intel Ethernet Connection (2) I219-V                              | 30        | 0.65%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 30        | 0.65%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 26        | 0.57%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 26        | 0.57%   |
| Intel Ethernet Connection (4) I219-LM                             | 25        | 0.54%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 25        | 0.54%   |
| Realtek 802.11ac NIC                                              | 24        | 0.52%   |
| ASIX AX88179 Gigabit Ethernet                                     | 23        | 0.5%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 22        | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1111      | 49.12%  |
| Realtek Semiconductor                 | 354       | 15.65%  |
| Qualcomm Atheros                      | 289       | 12.78%  |
| Broadcom                              | 152       | 6.72%   |
| MediaTek                              | 111       | 4.91%   |
| Broadcom Limited                      | 54        | 2.39%   |
| TP-Link                               | 37        | 1.64%   |
| Ralink Technology                     | 23        | 1.02%   |
| Ralink                                | 20        | 0.88%   |
| NetGear                               | 19        | 0.84%   |
| Microsoft                             | 11        | 0.49%   |
| Marvell Technology Group              | 10        | 0.44%   |
| Dell                                  | 10        | 0.44%   |
| Qualcomm                              | 9         | 0.4%    |
| Sierra Wireless                       | 7         | 0.31%   |
| D-Link                                | 7         | 0.31%   |
| D-Link System                         | 6         | 0.27%   |
| Qualcomm Atheros Communications       | 5         | 0.22%   |
| ASUSTek Computer                      | 5         | 0.22%   |
| Linksys                               | 4         | 0.18%   |
| Hewlett-Packard                       | 3         | 0.13%   |
| Fibocom                               | 2         | 0.09%   |
| Belkin Components                     | 2         | 0.09%   |
| Accton Technology                     | 2         | 0.09%   |
| ZyDAS                                 | 1         | 0.04%   |
| Sitecom Europe                        | 1         | 0.04%   |
| Micro Star International              | 1         | 0.04%   |
| IMC Networks                          | 1         | 0.04%   |
| Gemtek                                | 1         | 0.04%   |
| Edimax Technology                     | 1         | 0.04%   |
| AVM                                   | 1         | 0.04%   |
| Arduino SA                            | 1         | 0.04%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 220       | 9.65%   |
| Intel Wi-Fi 6 AX201                                            | 94        | 4.12%   |
| Intel Wireless 8265 / 8275                                     | 86        | 3.77%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 73        | 3.2%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 64        | 2.81%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 61        | 2.68%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 57        | 2.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 55        | 2.41%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 53        | 2.33%   |
| Intel Wireless 7265                                            | 52        | 2.28%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 50        | 2.19%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 49        | 2.15%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 47        | 2.06%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 45        | 1.97%   |
| Intel Wireless 8260                                            | 44        | 1.93%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 43        | 1.89%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 40        | 1.76%   |
| Intel Wireless 7260                                            | 39        | 1.71%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 38        | 1.67%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 37        | 1.62%   |
| Intel Wireless-AC 9260                                         | 35        | 1.54%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 31        | 1.36%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 30        | 1.32%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 30        | 1.32%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 26        | 1.14%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 26        | 1.14%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 25        | 1.1%    |
| Realtek 802.11ac NIC                                           | 24        | 1.05%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 22        | 0.97%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 22        | 0.97%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 20        | 0.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 20        | 0.88%   |
| Broadcom BCM43142 802.11b/g/n                                  | 20        | 0.88%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 19        | 0.83%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 19        | 0.83%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 17        | 0.75%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 17        | 0.75%   |
| Intel Wireless 3165                                            | 17        | 0.75%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 16        | 0.7%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 15        | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 1215      | 54.73%  |
| Intel                         | 627       | 28.24%  |
| Qualcomm Atheros              | 100       | 4.5%    |
| Broadcom                      | 78        | 3.51%   |
| ASIX Electronics              | 29        | 1.31%   |
| Nvidia                        | 25        | 1.13%   |
| Marvell Technology Group      | 21        | 0.95%   |
| DisplayLink                   | 16        | 0.72%   |
| Xiaomi                        | 15        | 0.68%   |
| Samsung Electronics           | 13        | 0.59%   |
| Broadcom Limited              | 12        | 0.54%   |
| Aquantia                      | 11        | 0.5%    |
| Lenovo                        | 8         | 0.36%   |
| Google                        | 8         | 0.36%   |
| TP-Link                       | 7         | 0.32%   |
| OPPO Electronics              | 5         | 0.23%   |
| OnePlus Technology (Shenzhen) | 5         | 0.23%   |
| JMicron Technology            | 5         | 0.23%   |
| Huawei Technologies           | 4         | 0.18%   |
| Mellanox Technologies         | 3         | 0.14%   |
| Motorola PCS                  | 2         | 0.09%   |
| Apple                         | 2         | 0.09%   |
| VIA Technologies              | 1         | 0.05%   |
| T & A Mobile Phones           | 1         | 0.05%   |
| Sierra Wireless               | 1         | 0.05%   |
| Qualcomm                      | 1         | 0.05%   |
| Hewlett-Packard               | 1         | 0.05%   |
| D-Link System                 | 1         | 0.05%   |
| D-Link                        | 1         | 0.05%   |
| ASUSTek Computer              | 1         | 0.05%   |
| American Megatrends           | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 880       | 38.77%  |
| Realtek RTL8125 2.5GbE Controller                                 | 130       | 5.73%   |
| Intel I211 Gigabit Network Connection                             | 111       | 4.89%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 99        | 4.36%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 96        | 4.23%   |
| Intel Ethernet Controller I225-V                                  | 81        | 3.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 69        | 3.04%   |
| Intel Ethernet Connection I217-LM                                 | 38        | 1.67%   |
| Intel Ethernet Connection (2) I219-V                              | 30        | 1.32%   |
| Intel Ethernet Connection (4) I219-LM                             | 25        | 1.1%    |
| ASIX AX88179 Gigabit Ethernet                                     | 23        | 1.01%   |
| Intel Ethernet Connection (7) I219-V                              | 22        | 0.97%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 20        | 0.88%   |
| Intel Ethernet Connection (2) I219-LM                             | 19        | 0.84%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 18        | 0.79%   |
| Nvidia MCP79 Ethernet                                             | 17        | 0.75%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 16        | 0.7%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 15        | 0.66%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 15        | 0.66%   |
| Intel Ethernet Connection I219-LM                                 | 15        | 0.66%   |
| Intel Ethernet Connection (3) I218-LM                             | 15        | 0.66%   |
| Intel Ethernet Connection I217-V                                  | 14        | 0.62%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 13        | 0.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 12        | 0.53%   |
| Intel Ethernet Connection (2) I218-V                              | 12        | 0.53%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 11        | 0.48%   |
| Intel Ethernet Connection I218-LM                                 | 11        | 0.48%   |
| Intel Ethernet Connection (4) I219-V                              | 11        | 0.48%   |
| Intel I210 Gigabit Network Connection                             | 10        | 0.44%   |
| Intel Ethernet Connection (7) I219-LM                             | 10        | 0.44%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 10        | 0.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 9         | 0.4%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 9         | 0.4%    |
| Intel Ethernet Connection (13) I219-V                             | 9         | 0.4%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 8         | 0.35%   |
| Intel Ethernet Connection (6) I219-V                              | 8         | 0.35%   |
| Intel Ethernet Connection (16) I219-V                             | 8         | 0.35%   |
| Intel 82579V Gigabit Network Connection                           | 8         | 0.35%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 8         | 0.35%   |
| Intel Ethernet Connection I219-V                                  | 7         | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2149      | 50.4%   |
| Ethernet | 2075      | 48.66%  |
| Modem    | 32        | 0.75%   |
| Unknown  | 8         | 0.19%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1673      | 61.89%  |
| Ethernet | 1029      | 38.07%  |
| Modem    | 1         | 0.04%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1410      | 54.95%  |
| 1     | 1046      | 40.76%  |
| 3     | 73        | 2.84%   |
| 0     | 31        | 1.21%   |
| 4     | 6         | 0.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1799      | 69.46%  |
| Yes  | 791       | 30.54%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 992       | 53.08%  |
| Realtek Semiconductor           | 175       | 9.36%   |
| Qualcomm Atheros Communications | 132       | 7.06%   |
| Apple                           | 116       | 6.21%   |
| IMC Networks                    | 81        | 4.33%   |
| Cambridge Silicon Radio         | 79        | 4.23%   |
| Foxconn / Hon Hai               | 64        | 3.42%   |
| Lite-On Technology              | 50        | 2.68%   |
| Broadcom                        | 46        | 2.46%   |
| ASUSTek Computer                | 23        | 1.23%   |
| MediaTek                        | 21        | 1.12%   |
| Dell                            | 12        | 0.64%   |
| Toshiba                         | 10        | 0.54%   |
| Realtek                         | 10        | 0.54%   |
| Marvell Semiconductor           | 10        | 0.54%   |
| TP-Link                         | 9         | 0.48%   |
| Hewlett-Packard                 | 7         | 0.37%   |
| Dynex                           | 4         | 0.21%   |
| Ralink                          | 3         | 0.16%   |
| Opticis                         | 3         | 0.16%   |
| Micro Star International        | 3         | 0.16%   |
| Foxconn International           | 3         | 0.16%   |
| Taiyo Yuden                     | 2         | 0.11%   |
| Smart Modular Technologies      | 2         | 0.11%   |
| Ralink Technology               | 2         | 0.11%   |
| Fujitsu                         | 2         | 0.11%   |
| Actions                         | 2         | 0.11%   |
| USI                             | 1         | 0.05%   |
| SINO WEALTH                     | 1         | 0.05%   |
| Integrated System Solution      | 1         | 0.05%   |
| HTC (High Tech Computer)        | 1         | 0.05%   |
| Edimax Technology               | 1         | 0.05%   |
| Belkin Components               | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 235       | 12.57%  |
| Intel AX201 Bluetooth                               | 226       | 12.09%  |
| Intel AX200 Bluetooth                               | 208       | 11.12%  |
| Realtek Bluetooth Radio                             | 124       | 6.63%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 115       | 6.15%   |
| Qualcomm Atheros  Bluetooth Device                  | 91        | 4.87%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 79        | 4.22%   |
| Apple Bluetooth Host Controller                     | 62        | 3.32%   |
| Intel Bluetooth Device                              | 58        | 3.1%    |
| Intel AX210 Bluetooth                               | 44        | 2.35%   |
| Intel Wireless-AC 3168 Bluetooth                    | 43        | 2.3%    |
| Realtek  Bluetooth 4.2 Adapter                      | 37        | 1.98%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 33        | 1.76%   |
| Apple Bluetooth USB Host Controller                 | 33        | 1.76%   |
| IMC Networks Wireless_Device                        | 32        | 1.71%   |
| Foxconn / Hon Hai Wireless_Device                   | 25        | 1.34%   |
| MediaTek Wireless_Device                            | 21        | 1.12%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 20        | 1.07%   |
| Foxconn / Hon Hai Bluetooth Device                  | 20        | 1.07%   |
| IMC Networks Bluetooth Radio                        | 18        | 0.96%   |
| IMC Networks Bluetooth Device                       | 18        | 0.96%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 15        | 0.8%    |
| Lite-On Wireless_Device                             | 14        | 0.75%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 11        | 0.59%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 11        | 0.59%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 11        | 0.59%   |
| Apple Bluetooth HCI                                 | 10        | 0.53%   |
| TP-Link UB500 Adapter                               | 9         | 0.48%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 9         | 0.48%   |
| Realtek 802.11ac WLAN Adapter                       | 8         | 0.43%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 8         | 0.43%   |
| Lite-On Bluetooth Radio                             | 8         | 0.43%   |
| Lite-On Bluetooth Device                            | 8         | 0.43%   |
| ASUS ASUS USB-BT500                                 | 8         | 0.43%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 7         | 0.37%   |
| Marvell Bluetooth and Wireless LAN Composite        | 7         | 0.37%   |
| Lite-On Atheros AR3012 Bluetooth                    | 7         | 0.37%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 6         | 0.32%   |
| Broadcom BCM2045B (BDC-2.1)                         | 6         | 0.32%   |
| ASUS Bluetooth Radio                                | 6         | 0.32%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1663      | 42.03%  |
| AMD                                  | 955       | 24.13%  |
| Nvidia                               | 792       | 20.02%  |
| C-Media Electronics                  | 63        | 1.59%   |
| Logitech                             | 42        | 1.06%   |
| Kingston Technology                  | 26        | 0.66%   |
| Razer USA                            | 24        | 0.61%   |
| JMTek                                | 23        | 0.58%   |
| ASUSTek Computer                     | 23        | 0.58%   |
| Focusrite-Novation                   | 22        | 0.56%   |
| Generalplus Technology               | 19        | 0.48%   |
| Micro Star International             | 18        | 0.45%   |
| Creative Labs                        | 16        | 0.4%    |
| Corsair                              | 14        | 0.35%   |
| SteelSeries ApS                      | 13        | 0.33%   |
| GN Netcom                            | 13        | 0.33%   |
| Texas Instruments                    | 12        | 0.3%    |
| Sony                                 | 12        | 0.3%    |
| Realtek Semiconductor                | 12        | 0.3%    |
| Lenovo                               | 10        | 0.25%   |
| Hewlett-Packard                      | 9         | 0.23%   |
| Creative Technology                  | 9         | 0.23%   |
| Blue Microphones                     | 9         | 0.23%   |
| DSEA A/S                             | 8         | 0.2%    |
| Apple                                | 7         | 0.18%   |
| Plantronics                          | 6         | 0.15%   |
| FiiO Electronics Technology          | 5         | 0.13%   |
| Tenx Technology                      | 4         | 0.1%    |
| Mackie Designs                       | 4         | 0.1%    |
| BEHRINGER International              | 4         | 0.1%    |
| Astro Gaming                         | 4         | 0.1%    |
| Antlion Audio                        | 4         | 0.1%    |
| Valve Software                       | 3         | 0.08%   |
| Turtle Beach                         | 3         | 0.08%   |
| Trust                                | 3         | 0.08%   |
| Thesycon Systemsoftware & Consulting | 3         | 0.08%   |
| Samson Technologies                  | 3         | 0.08%   |
| Nordic Semiconductor ASA             | 3         | 0.08%   |
| Medeli Electronics                   | 3         | 0.08%   |
| M-Audio                              | 3         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 406       | 8.45%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 223       | 4.64%   |
| AMD Starship/Matisse HD Audio Controller                                   | 207       | 4.31%   |
| Intel Sunrise Point-LP HD Audio                                            | 185       | 3.85%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 130       | 2.71%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 123       | 2.56%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 120       | 2.5%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 114       | 2.37%   |
| Intel Cannon Lake PCH cAVS                                                 | 103       | 2.14%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 91        | 1.89%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 87        | 1.81%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 85        | 1.77%   |
| Nvidia GA104 High Definition Audio Controller                              | 82        | 1.71%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 76        | 1.58%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 73        | 1.52%   |
| Intel Broadwell-U Audio Controller                                         | 72        | 1.5%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 71        | 1.48%   |
| Intel Haswell-ULT HD Audio Controller                                      | 67        | 1.39%   |
| Intel 8 Series HD Audio Controller                                         | 66        | 1.37%   |
| Nvidia GA106 High Definition Audio Controller                              | 65        | 1.35%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 63        | 1.31%   |
| Intel Comet Lake PCH cAVS                                                  | 62        | 1.29%   |
| Nvidia TU116 High Definition Audio Controller                              | 58        | 1.21%   |
| Nvidia GP107GL High Definition Audio Controller                            | 57        | 1.19%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 57        | 1.19%   |
| Nvidia TU106 High Definition Audio Controller                              | 55        | 1.14%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 54        | 1.12%   |
| Nvidia GP104 High Definition Audio Controller                              | 53        | 1.1%    |
| AMD FCH Azalia Controller                                                  | 52        | 1.08%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 51        | 1.06%   |
| Intel Comet Lake PCH-LP cAVS                                               | 49        | 1.02%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 49        | 1.02%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 48        | 1%      |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 47        | 0.98%   |
| Nvidia GP106 High Definition Audio Controller                              | 45        | 0.94%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 45        | 0.94%   |
| Intel 200 Series PCH HD Audio                                              | 42        | 0.87%   |
| Nvidia Audio device                                                        | 37        | 0.77%   |
| Nvidia TU104 HD Audio Controller                                           | 35        | 0.73%   |
| Intel CM238 HD Audio Controller                                            | 35        | 0.73%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 210       | 26.62%  |
| SK hynix                     | 153       | 19.39%  |
| Micron Technology            | 99        | 12.55%  |
| Kingston                     | 57        | 7.22%   |
| Corsair                      | 52        | 6.59%   |
| Crucial                      | 42        | 5.32%   |
| G.Skill                      | 37        | 4.69%   |
| Unknown                      | 23        | 2.92%   |
| Team                         | 18        | 2.28%   |
| A-DATA Technology            | 16        | 2.03%   |
| Unknown                      | 10        | 1.27%   |
| Unknown (ABCD)               | 8         | 1.01%   |
| Smart                        | 8         | 1.01%   |
| Neo Forza                    | 8         | 1.01%   |
| Goldkey                      | 7         | 0.89%   |
| Ramaxel Technology           | 4         | 0.51%   |
| PNY                          | 4         | 0.51%   |
| Elpida                       | 4         | 0.51%   |
| Nanya Technology             | 3         | 0.38%   |
| GSkill                       | 3         | 0.38%   |
| Avant                        | 3         | 0.38%   |
| Transcend                    | 2         | 0.25%   |
| Teikon                       | 2         | 0.25%   |
| Smart Brazil                 | 2         | 0.25%   |
| Gold Key                     | 2         | 0.25%   |
| Unknown (8A02)               | 1         | 0.13%   |
| Unknown (09B6)               | 1         | 0.13%   |
| Unknown (09A4)               | 1         | 0.13%   |
| Timetec                      | 1         | 0.13%   |
| Patriot Memory (PDP Systems) | 1         | 0.13%   |
| Patriot Memory               | 1         | 0.13%   |
| Patriot                      | 1         | 0.13%   |
| Kllisre                      | 1         | 0.13%   |
| GeIL                         | 1         | 0.13%   |
| CSX                          | 1         | 0.13%   |
| ChangXin Memory              | 1         | 0.13%   |
| Apacer                       | 1         | 0.13%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 14        | 1.7%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 14        | 1.7%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 13        | 1.58%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 11        | 1.34%   |
| Unknown                                                          | 10        | 1.22%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 9         | 1.09%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 8         | 0.97%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 8         | 0.97%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 7         | 0.85%   |
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 8400MT/s        | 7         | 0.85%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 7         | 0.85%   |
| Corsair RAM CMK16GX4M2B3000C15 8192MB DIMM DDR4 3200MT/s         | 7         | 0.85%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 6         | 0.73%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 6         | 0.73%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 6         | 0.73%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 6         | 0.73%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 6         | 0.73%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.73%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 6         | 0.73%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s               | 5         | 0.61%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.61%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.61%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 5         | 0.61%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 0.61%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.61%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.61%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 0.61%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.61%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 5         | 0.61%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 5         | 0.61%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 5         | 0.61%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 5         | 0.61%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 4         | 0.49%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 4         | 0.49%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 4         | 0.49%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                    | 4         | 0.49%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 0.49%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s           | 4         | 0.49%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 4         | 0.49%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 4         | 0.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 461       | 66.71%  |
| DDR3    | 105       | 15.2%   |
| LPDDR4  | 45        | 6.51%   |
| DDR5    | 28        | 4.05%   |
| LPDDR5  | 22        | 3.18%   |
| LPDDR3  | 19        | 2.75%   |
| DDR2    | 5         | 0.72%   |
| SDRAM   | 3         | 0.43%   |
| Unknown | 3         | 0.43%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 437       | 61.99%  |
| DIMM         | 161       | 22.84%  |
| Row Of Chips | 102       | 14.47%  |
| Chip         | 4         | 0.57%   |
| Unknown      | 1         | 0.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 335       | 45.21%  |
| 4096  | 161       | 21.73%  |
| 16384 | 155       | 20.92%  |
| 32768 | 53        | 7.15%   |
| 2048  | 33        | 4.45%   |
| 1024  | 4         | 0.54%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 220       | 29.85%  |
| 2667  | 116       | 15.74%  |
| 1600  | 74        | 10.04%  |
| 2400  | 50        | 6.78%   |
| 3600  | 34        | 4.61%   |
| 2133  | 29        | 3.93%   |
| 4267  | 26        | 3.53%   |
| 6400  | 23        | 3.12%   |
| 4800  | 23        | 3.12%   |
| 1333  | 14        | 1.9%    |
| 1867  | 12        | 1.63%   |
| 3800  | 9         | 1.22%   |
| 3733  | 8         | 1.09%   |
| 3466  | 8         | 1.09%   |
| 3266  | 8         | 1.09%   |
| 8400  | 7         | 0.95%   |
| 1334  | 7         | 0.95%   |
| 3000  | 6         | 0.81%   |
| 2933  | 6         | 0.81%   |
| 1067  | 6         | 0.81%   |
| 4266  | 5         | 0.68%   |
| 3400  | 5         | 0.68%   |
| 800   | 5         | 0.68%   |
| 3866  | 3         | 0.41%   |
| 3534  | 3         | 0.41%   |
| 6000  | 2         | 0.27%   |
| 5200  | 2         | 0.27%   |
| 3666  | 2         | 0.27%   |
| 3333  | 2         | 0.27%   |
| 3100  | 2         | 0.27%   |
| 2800  | 2         | 0.27%   |
| 2666  | 2         | 0.27%   |
| 2048  | 2         | 0.27%   |
| 1866  | 2         | 0.27%   |
| 4400  | 1         | 0.14%   |
| 4199  | 1         | 0.14%   |
| 4000  | 1         | 0.14%   |
| 3500  | 1         | 0.14%   |
| 3066  | 1         | 0.14%   |
| 2733  | 1         | 0.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 13        | 29.55%  |
| Brother Industries  | 9         | 20.45%  |
| Canon               | 8         | 18.18%  |
| Samsung Electronics | 4         | 9.09%   |
| Seiko Epson         | 3         | 6.82%   |
| Xerox               | 1         | 2.27%   |
| STMicroelectronics  | 1         | 2.27%   |
| QinHeng Electronics | 1         | 2.27%   |
| Prolific Technology | 1         | 2.27%   |
| ICS Advent          | 1         | 2.27%   |
| Dymo-CoStar         | 1         | 2.27%   |
| Dell                | 1         | 2.27%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Brother HL-2130 series                                    | 3         | 6.67%   |
| Xerox B215                                                | 1         | 2.22%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 2.22%   |
| Seiko Epson WF-4830 Series                                | 1         | 2.22%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]              | 1         | 2.22%   |
| Seiko Epson ET-2800 Series                                | 1         | 2.22%   |
| Samsung SCX-3400 Series                                   | 1         | 2.22%   |
| Samsung ML-191x/ML-252x Laser Printer                     | 1         | 2.22%   |
| Samsung M2070 Series                                      | 1         | 2.22%   |
| Samsung M2020 Series                                      | 1         | 2.22%   |
| QinHeng CH340S                                            | 1         | 2.22%   |
| Prolific PL2305 Parallel Port                             | 1         | 2.22%   |
| ICS Advent Parallel Adapter                               | 1         | 2.22%   |
| HP PSC-1315/PSC-1317                                      | 1         | 2.22%   |
| HP OfficeJet Pro 9010 series                              | 1         | 2.22%   |
| HP OfficeJet 3830 series                                  | 1         | 2.22%   |
| HP LaserJet Professional P1102w                           | 1         | 2.22%   |
| HP LaserJet P2035                                         | 1         | 2.22%   |
| HP LaserJet 3050                                          | 1         | 2.22%   |
| HP LaserJet 1010                                          | 1         | 2.22%   |
| HP Ink Tank Wireless 410 series                           | 1         | 2.22%   |
| HP Ink Tank 110 series                                    | 1         | 2.22%   |
| HP ENVY Pro 6400 series                                   | 1         | 2.22%   |
| HP ENVY 5000 series                                       | 1         | 2.22%   |
| HP DeskJet 2620 All-in-One Printer                        | 1         | 2.22%   |
| HP Color LaserJet CP2025dn                                | 1         | 2.22%   |
| Dymo-CoStar DYMO LabelWriter 4XL                          | 1         | 2.22%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                    | 1         | 2.22%   |
| Dell Laser Printer 1720                                   | 1         | 2.22%   |
| Canon TS9100 series                                       | 1         | 2.22%   |
| Canon TR8500 series                                       | 1         | 2.22%   |
| Canon TR4700 series                                       | 1         | 2.22%   |
| Canon Pro9000II series                                    | 1         | 2.22%   |
| Canon PIXMA MX920 Series                                  | 1         | 2.22%   |
| Canon PIXMA MP240                                         | 1         | 2.22%   |
| Canon PIXMA MG2500 Series                                 | 1         | 2.22%   |
| Canon E400 series                                         | 1         | 2.22%   |
| Brother MFC-L2700DW                                       | 1         | 2.22%   |
| Brother MFC-5440CN                                        | 1         | 2.22%   |
| Brother HL-L2370DW series                                 | 1         | 2.22%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Canon          | 4         | 80%     |
| Mustek Systems | 1         | 20%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Mustek Systems ScanExpress 1200 UB | 1         | 20%     |
| Canon CanoScan N650U/N656U         | 1         | 20%     |
| Canon CanoScan LiDE 60             | 1         | 20%     |
| Canon CanoScan LiDE 200            | 1         | 20%     |
| Canon CanoScan 9000F Mark II       | 1         | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 320       | 18.96%  |
| IMC Networks                           | 160       | 9.48%   |
| Microdia                               | 158       | 9.36%   |
| Realtek Semiconductor                  | 122       | 7.23%   |
| Logitech                               | 106       | 6.28%   |
| Bison Electronics                      | 94        | 5.57%   |
| Quanta                                 | 93        | 5.51%   |
| Apple                                  | 88        | 5.21%   |
| Sunplus Innovation Technology          | 84        | 4.98%   |
| Acer                                   | 67        | 3.97%   |
| Cheng Uei Precision Industry (Foxlink) | 43        | 2.55%   |
| Luxvisions Innotech Limited            | 41        | 2.43%   |
| Syntek                                 | 40        | 2.37%   |
| Lite-On Technology                     | 29        | 1.72%   |
| Suyin                                  | 25        | 1.48%   |
| Microsoft                              | 24        | 1.42%   |
| Sonix Technology                       | 16        | 0.95%   |
| Samsung Electronics                    | 16        | 0.95%   |
| Silicon Motion                         | 14        | 0.83%   |
| SunplusIT                              | 13        | 0.77%   |
| Razer USA                              | 10        | 0.59%   |
| Generalplus Technology                 | 9         | 0.53%   |
| Z-Star Microelectronics                | 8         | 0.47%   |
| Creative Technology                    | 6         | 0.36%   |
| Ricoh                                  | 5         | 0.3%    |
| MacroSilicon                           | 5         | 0.3%    |
| Jieli Technology                       | 5         | 0.3%    |
| ARC International                      | 5         | 0.3%    |
| Alcor Micro                            | 5         | 0.3%    |
| Sunplus IT                             | 4         | 0.24%   |
| Primax Electronics                     | 4         | 0.24%   |
| LG Electronics                         | 4         | 0.24%   |
| Lenovo                                 | 4         | 0.24%   |
| icSpring                               | 4         | 0.24%   |
| AVerMedia Technologies                 | 4         | 0.24%   |
| Cubeternet                             | 3         | 0.18%   |
| YGTek                                  | 2         | 0.12%   |
| Valve Software                         | 2         | 0.12%   |
| Trust                                  | 2         | 0.12%   |
| Tobii Technology AB                    | 2         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 75        | 4.4%    |
| Microdia Integrated_Webcam_HD            | 71        | 4.16%   |
| IMC Networks USB2.0 HD UVC WebCam        | 60        | 3.52%   |
| Realtek Integrated_Webcam_HD             | 49        | 2.87%   |
| IMC Networks Integrated Camera           | 39        | 2.29%   |
| Chicony HD WebCam                        | 33        | 1.94%   |
| Syntek Integrated Camera                 | 32        | 1.88%   |
| Logitech Webcam C270                     | 27        | 1.58%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X          | 27        | 1.58%   |
| Bison BisonCam,NB Pro                    | 26        | 1.52%   |
| Apple Built-in iSight                    | 26        | 1.52%   |
| Sunplus Integrated_Webcam_HD             | 23        | 1.35%   |
| Chicony USB2.0 Camera                    | 23        | 1.35%   |
| Quanta HD User Facing                    | 21        | 1.23%   |
| Bison HD Webcam                          | 21        | 1.23%   |
| Acer Integrated Camera                   | 20        | 1.17%   |
| Logitech HD Pro Webcam C920              | 18        | 1.06%   |
| Quanta HP HD Camera                      | 17        | 1%      |
| Apple FaceTime HD Camera (Built-in)      | 17        | 1%      |
| Apple FaceTime HD Camera                 | 17        | 1%      |
| Samsung Galaxy series, misc. (MTP mode)  | 16        | 0.94%   |
| Chicony HP HD Camera                     | 16        | 0.94%   |
| Chicony HD User Facing                   | 16        | 0.94%   |
| Bison Integrated Camera                  | 14        | 0.82%   |
| Microdia Integrated Webcam               | 13        | 0.76%   |
| Chicony USB2.0 VGA UVC WebCam            | 13        | 0.76%   |
| Bison SunplusIT Integrated Camera        | 13        | 0.76%   |
| Sonix USB2.0 HD UVC WebCam               | 12        | 0.7%    |
| Realtek Integrated Webcam                | 11        | 0.65%   |
| Microdia USB 2.0 Camera                  | 11        | 0.65%   |
| Luxvisions Innotech Limited HP HD Camera | 11        | 0.65%   |
| Logitech C922 Pro Stream Webcam          | 11        | 0.65%   |
| Lite-On Integrated Camera                | 11        | 0.65%   |
| Chicony Integrated Camera (1280x720@30)  | 11        | 0.65%   |
| Quanta HP TrueVision HD Camera           | 10        | 0.59%   |
| Microdia Webcam Vitade AF                | 10        | 0.59%   |
| Microdia Integrated Webcam HD            | 10        | 0.59%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 10        | 0.59%   |
| Chicony HP Wide Vision HD Camera         | 10        | 0.59%   |
| Chicony HP TrueVision HD Camera          | 10        | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 109       | 35.28%  |
| Validity Sensors                   | 79        | 25.57%  |
| Shenzhen Goodix Technology         | 62        | 20.06%  |
| Elan Microelectronics              | 17        | 5.5%    |
| LighTuning Technology              | 13        | 4.21%   |
| Upek                               | 10        | 3.24%   |
| AuthenTec                          | 7         | 2.27%   |
| Focal-systems.Corp                 | 4         | 1.29%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 0.97%   |
| HOLTEK                             | 3         | 0.97%   |
| Samsung Electronics                | 1         | 0.32%   |
| DigitalPersona                     | 1         | 0.32%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 28        | 9.06%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 27        | 8.74%   |
| Shenzhen Goodix Fingerprint Reader                                         | 20        | 6.47%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 17        | 5.5%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 16        | 5.18%   |
| Shenzhen Goodix FingerPrint                                                | 14        | 4.53%   |
| Synaptics UWP WBDI                                                         | 13        | 4.21%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 12        | 3.88%   |
| Elan ELAN:ARM-M4                                                           | 10        | 3.24%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 9         | 2.91%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 8         | 2.59%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 8         | 2.59%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 7         | 2.27%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 6         | 1.94%   |
| Validity Sensors Fingerprint scanner                                       | 6         | 1.94%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 6         | 1.94%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 6         | 1.94%   |
| Elan ELAN:Fingerprint                                                      | 6         | 1.94%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 5         | 1.62%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 1.62%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 1.62%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 1.62%   |
| Synaptics WBDI Device                                                      | 5         | 1.62%   |
| Synaptics WBDI                                                             | 5         | 1.62%   |
| Synaptics UWP WBDI Device                                                  | 5         | 1.62%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 5         | 1.62%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 1.29%   |
| Synaptics  WBDI                                                            | 4         | 1.29%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 4         | 1.29%   |
| Unknown                                                                    | 4         | 1.29%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 3         | 0.97%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 0.97%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 0.97%   |
| HOLTEK FocalTech Fingerprint Device                                        | 3         | 0.97%   |
| Validity Sensors VFS491                                                    | 2         | 0.65%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.65%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 0.65%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.65%   |
| LighTuning Fingerprint Sensor                                              | 2         | 0.65%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 0.65%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 50        | 49.5%   |
| Alcor Micro           | 31        | 30.69%  |
| O2 Micro              | 6         | 5.94%   |
| Upek                  | 4         | 3.96%   |
| Lenovo                | 4         | 3.96%   |
| OmniKey               | 2         | 1.98%   |
| SCM Microsystems      | 1         | 0.99%   |
| Gemalto (was Gemplus) | 1         | 0.99%   |
| Clay Logic            | 1         | 0.99%   |
| Advanced Card Systems | 1         | 0.99%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 30        | 29.7%   |
| Broadcom 58200                                                               | 15        | 14.85%  |
| Broadcom 5880                                                                | 14        | 13.86%  |
| Broadcom BCM5880 Secure Applications Processor                               | 12        | 11.88%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 9         | 8.91%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 4.95%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 3.96%   |
| Lenovo Integrated Smart Card Reader                                          | 4         | 3.96%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.99%   |
| OmniKey CardMan 4321                                                         | 1         | 0.99%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.99%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.99%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.99%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.99%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.99%   |
| Advanced Card Systems ACR1252 Dual Reader                                    | 1         | 0.99%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1758      | 67.54%  |
| 1     | 687       | 26.39%  |
| 2     | 134       | 5.15%   |
| 3     | 22        | 0.85%   |
| 4     | 2         | 0.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 299       | 30.14%  |
| Multimedia controller    | 144       | 14.52%  |
| Net/wireless             | 141       | 14.21%  |
| Graphics card            | 136       | 13.71%  |
| Chipcard                 | 96        | 9.68%   |
| Bluetooth                | 44        | 4.44%   |
| Camera                   | 33        | 3.33%   |
| Sound                    | 17        | 1.71%   |
| Unassigned class         | 15        | 1.51%   |
| Communication controller | 14        | 1.41%   |
| Net/ethernet             | 13        | 1.31%   |
| Network                  | 10        | 1.01%   |
| Storage                  | 7         | 0.71%   |
| Card reader              | 7         | 0.71%   |
| Modem                    | 5         | 0.5%    |
| Storage/ide              | 4         | 0.4%    |
| Storage/nvme             | 3         | 0.3%    |
| Storage/raid             | 2         | 0.2%    |
| Wireless                 | 1         | 0.1%    |
| Firewire controller      | 1         | 0.1%    |

