Fedora 34 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Fedora 34.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Fedora_34/Desktop/README.md) and [notebooks](/Dist/Fedora_34/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=fedora-34

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

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Intel         | H61                         | Desktop     | [6978cd209f](https://linux-hardware.org/?probe=6978cd209f) | Oct 31, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [0233ae7054](https://linux-hardware.org/?probe=0233ae7054) | Oct 31, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [2ba5ae42bb](https://linux-hardware.org/?probe=2ba5ae42bb) | Oct 31, 2021 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [11cd74e647](https://linux-hardware.org/?probe=11cd74e647) | Oct 31, 2021 |
| Dell          | Latitude 5490               | Notebook    | [3d0fd285b6](https://linux-hardware.org/?probe=3d0fd285b6) | Oct 31, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [31b241368b](https://linux-hardware.org/?probe=31b241368b) | Oct 30, 2021 |
| HP            | ProBook 640 G2              | Notebook    | [d098305f2a](https://linux-hardware.org/?probe=d098305f2a) | Oct 30, 2021 |
| HP            | ProBook 640 G2              | Notebook    | [d99bdece1d](https://linux-hardware.org/?probe=d99bdece1d) | Oct 30, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [ff0bc6375e](https://linux-hardware.org/?probe=ff0bc6375e) | Oct 30, 2021 |
| Gigabyte      | G41MT-D3                    | Desktop     | [e77d7b4b45](https://linux-hardware.org/?probe=e77d7b4b45) | Oct 30, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [1739e3b05d](https://linux-hardware.org/?probe=1739e3b05d) | Oct 30, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [5a56854746](https://linux-hardware.org/?probe=5a56854746) | Oct 30, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [3e8d9f5687](https://linux-hardware.org/?probe=3e8d9f5687) | Oct 30, 2021 |
| Lenovo        | ThinkPad X240 20AMA1Y3UK    | Notebook    | [f802abef07](https://linux-hardware.org/?probe=f802abef07) | Oct 29, 2021 |
| Dell          | Vostro 5568                 | Notebook    | [8894639b19](https://linux-hardware.org/?probe=8894639b19) | Oct 29, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [d1cf1b316e](https://linux-hardware.org/?probe=d1cf1b316e) | Oct 29, 2021 |
| Standard      | Unknown                     | Notebook    | [6b45028e3e](https://linux-hardware.org/?probe=6b45028e3e) | Oct 29, 2021 |
| Standard      | Unknown                     | Notebook    | [1bf7e2da2f](https://linux-hardware.org/?probe=1bf7e2da2f) | Oct 28, 2021 |
| Dell          | Vostro 14-5480              | Notebook    | [5d323af087](https://linux-hardware.org/?probe=5d323af087) | Oct 28, 2021 |
| Lenovo        | ThinkPad Yoga 260 20FD00... | Convertible | [24d1bd52cc](https://linux-hardware.org/?probe=24d1bd52cc) | Oct 28, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [0cdc6e9d84](https://linux-hardware.org/?probe=0cdc6e9d84) | Oct 28, 2021 |
| Lenovo        | ThinkPad T470s 20HGS3AX0... | Notebook    | [f82b6569d1](https://linux-hardware.org/?probe=f82b6569d1) | Oct 27, 2021 |
| Lenovo        | ThinkPad X220 4289A92       | Notebook    | [0a8e84dfad](https://linux-hardware.org/?probe=0a8e84dfad) | Oct 27, 2021 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [d0ae421827](https://linux-hardware.org/?probe=d0ae421827) | Oct 27, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [8512ee02bd](https://linux-hardware.org/?probe=8512ee02bd) | Oct 27, 2021 |
| HP            | 339A                        | Desktop     | [28da82ff00](https://linux-hardware.org/?probe=28da82ff00) | Oct 27, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS0... | Notebook    | [94e0e3f047](https://linux-hardware.org/?probe=94e0e3f047) | Oct 27, 2021 |
| MSI           | A320M GAMING PRO            | Desktop     | [599dfb26a8](https://linux-hardware.org/?probe=599dfb26a8) | Oct 26, 2021 |
| HP            | Pavilion dv6                | Notebook    | [976aa3e9e2](https://linux-hardware.org/?probe=976aa3e9e2) | Oct 26, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [aea3645cbe](https://linux-hardware.org/?probe=aea3645cbe) | Oct 26, 2021 |
| Unknown       | NF-MCP78                    | Desktop     | [50a93243d2](https://linux-hardware.org/?probe=50a93243d2) | Oct 26, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [66fb8f7f78](https://linux-hardware.org/?probe=66fb8f7f78) | Oct 26, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [87abf841b5](https://linux-hardware.org/?probe=87abf841b5) | Oct 26, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [740aaee24e](https://linux-hardware.org/?probe=740aaee24e) | Oct 26, 2021 |
| Dell          | 0GC080                      | Desktop     | [cb7602a2bd](https://linux-hardware.org/?probe=cb7602a2bd) | Oct 26, 2021 |
| HP            | Laptop 15-db1xxx            | Notebook    | [c7be2ff77e](https://linux-hardware.org/?probe=c7be2ff77e) | Oct 26, 2021 |
| Sony          | VPCSA25GX                   | Notebook    | [be4db20b0e](https://linux-hardware.org/?probe=be4db20b0e) | Oct 25, 2021 |
| HP            | ENVY Laptop 17-ce1xxx       | Notebook    | [4453e2c056](https://linux-hardware.org/?probe=4453e2c056) | Oct 25, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [df7b7986f5](https://linux-hardware.org/?probe=df7b7986f5) | Oct 25, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [d9e192761c](https://linux-hardware.org/?probe=d9e192761c) | Oct 25, 2021 |
| Dell          | Inspiron M5010              | Notebook    | [5a8280a663](https://linux-hardware.org/?probe=5a8280a663) | Oct 25, 2021 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [c5fb628a16](https://linux-hardware.org/?probe=c5fb628a16) | Oct 25, 2021 |
| LattePanda    | Alpha                       | Desktop     | [93cea579ca](https://linux-hardware.org/?probe=93cea579ca) | Oct 25, 2021 |
| LattePanda    | Alpha                       | Desktop     | [3f81c1a08a](https://linux-hardware.org/?probe=3f81c1a08a) | Oct 25, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [93ec7f3964](https://linux-hardware.org/?probe=93ec7f3964) | Oct 24, 2021 |
| Dell          | Precision 5510              | Notebook    | [bc0bfcd534](https://linux-hardware.org/?probe=bc0bfcd534) | Oct 24, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [0c3651af28](https://linux-hardware.org/?probe=0c3651af28) | Oct 24, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [632c89a5d9](https://linux-hardware.org/?probe=632c89a5d9) | Oct 24, 2021 |
| Dell          | 01V648 A03                  | Server      | [24358fa4bd](https://linux-hardware.org/?probe=24358fa4bd) | Oct 24, 2021 |
| Apple         | MacBookPro14,3              | Notebook    | [69a5d79a58](https://linux-hardware.org/?probe=69a5d79a58) | Oct 24, 2021 |
| Lenovo        | ThinkPad T410 2522PT3       | Notebook    | [98720c7a44](https://linux-hardware.org/?probe=98720c7a44) | Oct 24, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [4bc3faf49f](https://linux-hardware.org/?probe=4bc3faf49f) | Oct 24, 2021 |
| Apple         | MacBookPro13,1              | Notebook    | [6edc1fa05b](https://linux-hardware.org/?probe=6edc1fa05b) | Oct 24, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [d29ffd3d8a](https://linux-hardware.org/?probe=d29ffd3d8a) | Oct 24, 2021 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [184b909fc0](https://linux-hardware.org/?probe=184b909fc0) | Oct 24, 2021 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [a1b11244e3](https://linux-hardware.org/?probe=a1b11244e3) | Oct 24, 2021 |
| Lenovo        | G550 2958                   | Notebook    | [b9412e1ab2](https://linux-hardware.org/?probe=b9412e1ab2) | Oct 23, 2021 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [0e913d2884](https://linux-hardware.org/?probe=0e913d2884) | Oct 23, 2021 |
| Gigabyte      | B450 AORUS ELITE V2         | Desktop     | [3d4bec1c75](https://linux-hardware.org/?probe=3d4bec1c75) | Oct 23, 2021 |
| HP            | 240 G4 Notebook PC          | Notebook    | [b4cd0bde35](https://linux-hardware.org/?probe=b4cd0bde35) | Oct 23, 2021 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [2b043d7a15](https://linux-hardware.org/?probe=2b043d7a15) | Oct 23, 2021 |
| ASUSTek       | X750JN                      | Notebook    | [c910a27f22](https://linux-hardware.org/?probe=c910a27f22) | Oct 23, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [4200d04ab2](https://linux-hardware.org/?probe=4200d04ab2) | Oct 23, 2021 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [fb31c8d088](https://linux-hardware.org/?probe=fb31c8d088) | Oct 23, 2021 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | Notebook    | [01ca7ca744](https://linux-hardware.org/?probe=01ca7ca744) | Oct 23, 2021 |
| ZOOSTORM      | 7200-9041A                  | Notebook    | [6fe3800dd3](https://linux-hardware.org/?probe=6fe3800dd3) | Oct 22, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [3517455df5](https://linux-hardware.org/?probe=3517455df5) | Oct 22, 2021 |
| Lenovo        | G550 2958                   | Notebook    | [a0ff38d606](https://linux-hardware.org/?probe=a0ff38d606) | Oct 22, 2021 |
| Lenovo        | G50-30 80G0                 | Notebook    | [d89079f54b](https://linux-hardware.org/?probe=d89079f54b) | Oct 22, 2021 |
| Lenovo        | G50-30 80G0                 | Notebook    | [1db82d12bd](https://linux-hardware.org/?probe=1db82d12bd) | Oct 22, 2021 |
| HP            | 8056                        | Desktop     | [3de6337339](https://linux-hardware.org/?probe=3de6337339) | Oct 22, 2021 |
| HP            | Pavilion 15                 | Notebook    | [c7923a133f](https://linux-hardware.org/?probe=c7923a133f) | Oct 22, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [aa16d8147a](https://linux-hardware.org/?probe=aa16d8147a) | Oct 21, 2021 |
| Gigabyte      | Z77-D3H                     | Desktop     | [0205ab4321](https://linux-hardware.org/?probe=0205ab4321) | Oct 21, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [267bee9221](https://linux-hardware.org/?probe=267bee9221) | Oct 21, 2021 |
| Gigabyte      | Z77-D3H                     | Desktop     | [c2d1fcd5bc](https://linux-hardware.org/?probe=c2d1fcd5bc) | Oct 21, 2021 |
| HP            | 2B36                        | Desktop     | [a2743184d7](https://linux-hardware.org/?probe=a2743184d7) | Oct 21, 2021 |
| System76      | Oryx Pro                    | Notebook    | [19e1d08a20](https://linux-hardware.org/?probe=19e1d08a20) | Oct 21, 2021 |
| Dell          | Inspiron 5555               | Notebook    | [c74d7ef85c](https://linux-hardware.org/?probe=c74d7ef85c) | Oct 21, 2021 |
| Dell          | Precision 5510              | Notebook    | [790847d272](https://linux-hardware.org/?probe=790847d272) | Oct 21, 2021 |
| Gigabyte      | B450 AORUS ELITE V2         | Desktop     | [484ff1a750](https://linux-hardware.org/?probe=484ff1a750) | Oct 21, 2021 |
| Gigabyte      | H310M H x.x                 | Desktop     | [419e0c7eb2](https://linux-hardware.org/?probe=419e0c7eb2) | Oct 21, 2021 |
| ASUSTek       | P8Z68-V PRO GEN3            | Desktop     | [f11c125224](https://linux-hardware.org/?probe=f11c125224) | Oct 20, 2021 |
| Gigabyte      | H370M DS3H-CF               | Desktop     | [1c2a383c4f](https://linux-hardware.org/?probe=1c2a383c4f) | Oct 20, 2021 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [2c6cfc5b5a](https://linux-hardware.org/?probe=2c6cfc5b5a) | Oct 20, 2021 |
| Intel         | S5000XVN                    | Server      | [715b40d8b6](https://linux-hardware.org/?probe=715b40d8b6) | Oct 20, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [a46656c6b4](https://linux-hardware.org/?probe=a46656c6b4) | Oct 20, 2021 |
| HP            | ProBook 450 G7              | Notebook    | [a47cdaa2ba](https://linux-hardware.org/?probe=a47cdaa2ba) | Oct 20, 2021 |
| HP            | 250 G1                      | Notebook    | [1336112f11](https://linux-hardware.org/?probe=1336112f11) | Oct 20, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [55f8110d0e](https://linux-hardware.org/?probe=55f8110d0e) | Oct 20, 2021 |
| Lenovo        | ThinkPad T480 20L6S7PE06    | Notebook    | [28857899a2](https://linux-hardware.org/?probe=28857899a2) | Oct 20, 2021 |
| Dell          | 03KWTV A00                  | Desktop     | [d4f071950b](https://linux-hardware.org/?probe=d4f071950b) | Oct 19, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [8a6e0ee275](https://linux-hardware.org/?probe=8a6e0ee275) | Oct 19, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [5bb3c9bc8b](https://linux-hardware.org/?probe=5bb3c9bc8b) | Oct 19, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [c11c89f0d4](https://linux-hardware.org/?probe=c11c89f0d4) | Oct 19, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [bd647ba525](https://linux-hardware.org/?probe=bd647ba525) | Oct 19, 2021 |
| Gigabyte      | H310M H                     | Desktop     | [c8106b6a92](https://linux-hardware.org/?probe=c8106b6a92) | Oct 18, 2021 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [4e6bceb431](https://linux-hardware.org/?probe=4e6bceb431) | Oct 18, 2021 |
| Lenovo        | ThinkCentre M58p 7220A72    | Desktop     | [1a170cd208](https://linux-hardware.org/?probe=1a170cd208) | Oct 18, 2021 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [c2682290f7](https://linux-hardware.org/?probe=c2682290f7) | Oct 18, 2021 |
| Notebook      | NH5x_NH7x_HHx_HJx_HKx       | Notebook    | [9135995c0d](https://linux-hardware.org/?probe=9135995c0d) | Oct 18, 2021 |
| ASRock        | AB350M-HDV                  | Desktop     | [eff4abf74e](https://linux-hardware.org/?probe=eff4abf74e) | Oct 18, 2021 |
| Dell          | Inspiron 5423               | Notebook    | [f31078afd8](https://linux-hardware.org/?probe=f31078afd8) | Oct 18, 2021 |
| Unknown       | Unknown                     | Notebook    | [a6e5e7b6ef](https://linux-hardware.org/?probe=a6e5e7b6ef) | Oct 18, 2021 |
| Toshiba       | Satellite L750              | Notebook    | [f18e793687](https://linux-hardware.org/?probe=f18e793687) | Oct 17, 2021 |
| Apple         | MacBookPro11,2              | Notebook    | [3fd2fe08ce](https://linux-hardware.org/?probe=3fd2fe08ce) | Oct 17, 2021 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [d39f2875f9](https://linux-hardware.org/?probe=d39f2875f9) | Oct 17, 2021 |
| Toshiba       | Satellite L750              | Notebook    | [065ee91163](https://linux-hardware.org/?probe=065ee91163) | Oct 17, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [d8df5c8003](https://linux-hardware.org/?probe=d8df5c8003) | Oct 17, 2021 |
| Unknown       | NF-MCP78                    | Desktop     | [cc2400d4e3](https://linux-hardware.org/?probe=cc2400d4e3) | Oct 17, 2021 |
| ASUSTek       | TUF Z270 MARK 2             | Desktop     | [37523e831d](https://linux-hardware.org/?probe=37523e831d) | Oct 17, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [383e24fcf5](https://linux-hardware.org/?probe=383e24fcf5) | Oct 17, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [61b1e7901a](https://linux-hardware.org/?probe=61b1e7901a) | Oct 17, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [b4c6139d09](https://linux-hardware.org/?probe=b4c6139d09) | Oct 17, 2021 |
| Samsung       | 370E4K                      | Notebook    | [e96252931e](https://linux-hardware.org/?probe=e96252931e) | Oct 17, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [70e96b19b2](https://linux-hardware.org/?probe=70e96b19b2) | Oct 17, 2021 |
| HP            | Elite x2 1012 G1            | Notebook    | [89e5ab8846](https://linux-hardware.org/?probe=89e5ab8846) | Oct 17, 2021 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [7995f5d9f8](https://linux-hardware.org/?probe=7995f5d9f8) | Oct 16, 2021 |
| Lenovo        | ThinkPad T490 20N2005VMX    | Notebook    | [2e44d637e3](https://linux-hardware.org/?probe=2e44d637e3) | Oct 16, 2021 |
| Dell          | Precision 5510              | Notebook    | [abde438309](https://linux-hardware.org/?probe=abde438309) | Oct 16, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [adeb7e2546](https://linux-hardware.org/?probe=adeb7e2546) | Oct 16, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [be5792fc80](https://linux-hardware.org/?probe=be5792fc80) | Oct 16, 2021 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [1bab3da288](https://linux-hardware.org/?probe=1bab3da288) | Oct 16, 2021 |
| LG Electro... | A550-C.BE55P1               | Notebook    | [cac46f39f4](https://linux-hardware.org/?probe=cac46f39f4) | Oct 16, 2021 |
| ASRock        | B550M Pro4                  | Desktop     | [ae854c2ff2](https://linux-hardware.org/?probe=ae854c2ff2) | Oct 16, 2021 |
| HP            | Elite x2 1012 G1            | Notebook    | [ef69897bb6](https://linux-hardware.org/?probe=ef69897bb6) | Oct 16, 2021 |
| Gigabyte      | B365M HD3                   | Desktop     | [26e0d9a3d9](https://linux-hardware.org/?probe=26e0d9a3d9) | Oct 16, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [626699038a](https://linux-hardware.org/?probe=626699038a) | Oct 15, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [2b35e6415a](https://linux-hardware.org/?probe=2b35e6415a) | Oct 15, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [a034c42ddd](https://linux-hardware.org/?probe=a034c42ddd) | Oct 15, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [814eab077b](https://linux-hardware.org/?probe=814eab077b) | Oct 15, 2021 |
| Apple         | MacBookPro5,4               | Notebook    | [b69ea5af99](https://linux-hardware.org/?probe=b69ea5af99) | Oct 15, 2021 |
| Intel         | NUC5i3RYB H41000-506        | Mini pc     | [b949def00e](https://linux-hardware.org/?probe=b949def00e) | Oct 15, 2021 |
| Dell          | Inspiron 5555               | Notebook    | [235ea33a16](https://linux-hardware.org/?probe=235ea33a16) | Oct 15, 2021 |
| Lenovo        | ThinkPad T410 2522PT3       | Notebook    | [b2214c65d5](https://linux-hardware.org/?probe=b2214c65d5) | Oct 15, 2021 |
| HP            | ProBook 640 G1              | Notebook    | [b71d68ded9](https://linux-hardware.org/?probe=b71d68ded9) | Oct 15, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [c8bb97907a](https://linux-hardware.org/?probe=c8bb97907a) | Oct 14, 2021 |
| MSI           | B560M PRO-VDH               | Desktop     | [2a4135bc50](https://linux-hardware.org/?probe=2a4135bc50) | Oct 14, 2021 |
| HP            | EliteBook x360 830 G6       | Convertible | [a2f9ca954a](https://linux-hardware.org/?probe=a2f9ca954a) | Oct 14, 2021 |
| Toshiba       | Satellite C55-A-1NK         | Notebook    | [a67bc74bfd](https://linux-hardware.org/?probe=a67bc74bfd) | Oct 14, 2021 |
| Gigabyte      | H310M H x.x                 | Desktop     | [3fe7cdd0f9](https://linux-hardware.org/?probe=3fe7cdd0f9) | Oct 14, 2021 |
| Lenovo        | ThinkPad E490 20N9CTO1WW    | Notebook    | [69243ba50f](https://linux-hardware.org/?probe=69243ba50f) | Oct 14, 2021 |
| eMachines     | E520 V1.06                  | Notebook    | [97c667e3c0](https://linux-hardware.org/?probe=97c667e3c0) | Oct 14, 2021 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [1d5dc0eb72](https://linux-hardware.org/?probe=1d5dc0eb72) | Oct 14, 2021 |
| Dell          | Latitude 7490               | Notebook    | [790768846e](https://linux-hardware.org/?probe=790768846e) | Oct 14, 2021 |
| ASRock        | 970A-G                      | Desktop     | [be8559f8a6](https://linux-hardware.org/?probe=be8559f8a6) | Oct 14, 2021 |
| Lenovo        | ThinkPad T450 20BU000QLM    | Notebook    | [64b138b3d3](https://linux-hardware.org/?probe=64b138b3d3) | Oct 14, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [10fb804abd](https://linux-hardware.org/?probe=10fb804abd) | Oct 13, 2021 |
| Dell          | G5 5500                     | Notebook    | [1fda01a947](https://linux-hardware.org/?probe=1fda01a947) | Oct 13, 2021 |
| MSI           | A320M BAZOOKA               | Desktop     | [acfde1543b](https://linux-hardware.org/?probe=acfde1543b) | Oct 13, 2021 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [4edbb1b2e6](https://linux-hardware.org/?probe=4edbb1b2e6) | Oct 13, 2021 |
| Lenovo        | ThinkPad P52 20MAS17200     | Notebook    | [c625f457a9](https://linux-hardware.org/?probe=c625f457a9) | Oct 13, 2021 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [11aa15d19c](https://linux-hardware.org/?probe=11aa15d19c) | Oct 13, 2021 |
| ASUSTek       | X555DA                      | Notebook    | [903dc4ef05](https://linux-hardware.org/?probe=903dc4ef05) | Oct 13, 2021 |
| Lenovo        | ThinkPad T410 2522PT3       | Notebook    | [45d7f1dfc1](https://linux-hardware.org/?probe=45d7f1dfc1) | Oct 13, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [749aa3e960](https://linux-hardware.org/?probe=749aa3e960) | Oct 13, 2021 |
| ASUSTek       | K55VD                       | Notebook    | [cce3e9bd74](https://linux-hardware.org/?probe=cce3e9bd74) | Oct 12, 2021 |
| Dell          | Latitude E7270              | Notebook    | [425e5e3667](https://linux-hardware.org/?probe=425e5e3667) | Oct 12, 2021 |
| Gigabyte      | G41MT-D3                    | Desktop     | [42387af777](https://linux-hardware.org/?probe=42387af777) | Oct 12, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [4342f43c87](https://linux-hardware.org/?probe=4342f43c87) | Oct 12, 2021 |
| HP            | 240 G6 Notebook PC          | Notebook    | [87b00b0a80](https://linux-hardware.org/?probe=87b00b0a80) | Oct 12, 2021 |
| HP            | 8056                        | Desktop     | [d308b9ea53](https://linux-hardware.org/?probe=d308b9ea53) | Oct 12, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [d2a7c70779](https://linux-hardware.org/?probe=d2a7c70779) | Oct 12, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [e3683dfc6a](https://linux-hardware.org/?probe=e3683dfc6a) | Oct 12, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [fe78f0e87c](https://linux-hardware.org/?probe=fe78f0e87c) | Oct 12, 2021 |
| Lenovo        | ThinkPad T490 20N2000BPB    | Notebook    | [336bb92842](https://linux-hardware.org/?probe=336bb92842) | Oct 12, 2021 |
| Lenovo        | ThinkPad T490 20N2000BPB    | Notebook    | [83b2311bc4](https://linux-hardware.org/?probe=83b2311bc4) | Oct 12, 2021 |
| theobroma-... | puma_rk3399                 | Soc         | [16d3c3d359](https://linux-hardware.org/?probe=16d3c3d359) | Oct 11, 2021 |
| theobroma-... | puma_rk3399                 | Soc         | [64aa8d06f4](https://linux-hardware.org/?probe=64aa8d06f4) | Oct 11, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [4054b4ec35](https://linux-hardware.org/?probe=4054b4ec35) | Oct 11, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [037a558c7d](https://linux-hardware.org/?probe=037a558c7d) | Oct 11, 2021 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | Notebook    | [90dd918da6](https://linux-hardware.org/?probe=90dd918da6) | Oct 11, 2021 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | Notebook    | [0562199997](https://linux-hardware.org/?probe=0562199997) | Oct 11, 2021 |
| Acer          | Nitro AN515-42              | Notebook    | [cdde4a1230](https://linux-hardware.org/?probe=cdde4a1230) | Oct 11, 2021 |
| Acer          | Predator G3-572             | Notebook    | [c774653cd2](https://linux-hardware.org/?probe=c774653cd2) | Oct 11, 2021 |
| Unknown       | Phitronics G41-M3           | Desktop     | [2b94f6fcca](https://linux-hardware.org/?probe=2b94f6fcca) | Oct 11, 2021 |
| Acer          | Predator G3-572             | Notebook    | [a0d3f7ab22](https://linux-hardware.org/?probe=a0d3f7ab22) | Oct 11, 2021 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [d01c751c63](https://linux-hardware.org/?probe=d01c751c63) | Oct 11, 2021 |
| ASUSTek       | K75VJ                       | Notebook    | [e460d65395](https://linux-hardware.org/?probe=e460d65395) | Oct 10, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | Desktop     | [e2dff5f003](https://linux-hardware.org/?probe=e2dff5f003) | Oct 10, 2021 |
| Teclast       | F7 Plus                     | Notebook    | [6c92e67a11](https://linux-hardware.org/?probe=6c92e67a11) | Oct 10, 2021 |
| Lenovo        | V580c 20160                 | Notebook    | [4425b80e85](https://linux-hardware.org/?probe=4425b80e85) | Oct 10, 2021 |
| Lenovo        | G710 20252                  | Notebook    | [61b036977b](https://linux-hardware.org/?probe=61b036977b) | Oct 10, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | Notebook    | [1984f59bbe](https://linux-hardware.org/?probe=1984f59bbe) | Oct 10, 2021 |
| Dell          | Inspiron 5447               | Notebook    | [689944cbda](https://linux-hardware.org/?probe=689944cbda) | Oct 10, 2021 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [185b72ac58](https://linux-hardware.org/?probe=185b72ac58) | Oct 10, 2021 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [55df2f0eaf](https://linux-hardware.org/?probe=55df2f0eaf) | Oct 10, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [f15bc46048](https://linux-hardware.org/?probe=f15bc46048) | Oct 09, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [230c5862d7](https://linux-hardware.org/?probe=230c5862d7) | Oct 09, 2021 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [719e7db7f5](https://linux-hardware.org/?probe=719e7db7f5) | Oct 09, 2021 |
| Toshiba       | Satellite C855-12R          | Notebook    | [da9ecb71ea](https://linux-hardware.org/?probe=da9ecb71ea) | Oct 09, 2021 |
| Lenovo        | ThinkPad E14 20RA0020AU     | Notebook    | [f8efee6741](https://linux-hardware.org/?probe=f8efee6741) | Oct 09, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [003075ee67](https://linux-hardware.org/?probe=003075ee67) | Oct 09, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [5f85c0951b](https://linux-hardware.org/?probe=5f85c0951b) | Oct 09, 2021 |
| TUXEDO        | Polaris 15 AMD Gen1         | Notebook    | [a631c78255](https://linux-hardware.org/?probe=a631c78255) | Oct 09, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [a96f6b582d](https://linux-hardware.org/?probe=a96f6b582d) | Oct 09, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [5174e188c0](https://linux-hardware.org/?probe=5174e188c0) | Oct 09, 2021 |
| Gigabyte      | G41MT-D3                    | Desktop     | [33895e4ca9](https://linux-hardware.org/?probe=33895e4ca9) | Oct 08, 2021 |
| Dell          | Latitude E7470              | Notebook    | [2b63473d5b](https://linux-hardware.org/?probe=2b63473d5b) | Oct 08, 2021 |
| Huanan        | X99-TF V2.0                 | Desktop     | [21ead32720](https://linux-hardware.org/?probe=21ead32720) | Oct 08, 2021 |
| HP            | 8061                        | Desktop     | [404d0b4b19](https://linux-hardware.org/?probe=404d0b4b19) | Oct 08, 2021 |
| HP            | 250 G1                      | Notebook    | [59b18b163e](https://linux-hardware.org/?probe=59b18b163e) | Oct 08, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [2a56d08aac](https://linux-hardware.org/?probe=2a56d08aac) | Oct 08, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [157ad8cce8](https://linux-hardware.org/?probe=157ad8cce8) | Oct 07, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [645d89bb66](https://linux-hardware.org/?probe=645d89bb66) | Oct 07, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [c9743b06e8](https://linux-hardware.org/?probe=c9743b06e8) | Oct 07, 2021 |
| Unknown       | Unknown                     | Desktop     | [54642e6ee3](https://linux-hardware.org/?probe=54642e6ee3) | Oct 07, 2021 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [470f30ff2e](https://linux-hardware.org/?probe=470f30ff2e) | Oct 07, 2021 |
| Lenovo        | ThinkPad T490s 20NX003NR... | Notebook    | [9ca00402e4](https://linux-hardware.org/?probe=9ca00402e4) | Oct 07, 2021 |
| Unknown       | NF-MCP78                    | Desktop     | [3915f05d09](https://linux-hardware.org/?probe=3915f05d09) | Oct 07, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [b1618af3e5](https://linux-hardware.org/?probe=b1618af3e5) | Oct 07, 2021 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [37b9009c4f](https://linux-hardware.org/?probe=37b9009c4f) | Oct 07, 2021 |
| Unknown       | Unknown                     | Desktop     | [3910c19edf](https://linux-hardware.org/?probe=3910c19edf) | Oct 07, 2021 |
| Lenovo        | IdeaPad FLEX 5-1570 81CA    | Convertible | [a2717638be](https://linux-hardware.org/?probe=a2717638be) | Oct 06, 2021 |
| Dell          | Latitude E6520              | Notebook    | [981a3487da](https://linux-hardware.org/?probe=981a3487da) | Oct 06, 2021 |
| MSI           | Z270M MORTAR                | Desktop     | [65ae5e6153](https://linux-hardware.org/?probe=65ae5e6153) | Oct 06, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [59e95fddfc](https://linux-hardware.org/?probe=59e95fddfc) | Oct 06, 2021 |
| Apple         | MacBookPro11,3              | Notebook    | [f89146e255](https://linux-hardware.org/?probe=f89146e255) | Oct 06, 2021 |
| Apple         | MacBookPro11,3              | Notebook    | [c25cd8207a](https://linux-hardware.org/?probe=c25cd8207a) | Oct 06, 2021 |
| MSI           | MS-9A45 0A                  | Desktop     | [04afb3d9fe](https://linux-hardware.org/?probe=04afb3d9fe) | Oct 06, 2021 |
| Dell          | XPS 13 9305                 | Notebook    | [4be3125675](https://linux-hardware.org/?probe=4be3125675) | Oct 06, 2021 |
| Acer          | Aspire XC-886 V:2.0         | Desktop     | [e9ee820848](https://linux-hardware.org/?probe=e9ee820848) | Oct 06, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [46552d08f3](https://linux-hardware.org/?probe=46552d08f3) | Oct 06, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [1f29f9efba](https://linux-hardware.org/?probe=1f29f9efba) | Oct 06, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [cad5076bd0](https://linux-hardware.org/?probe=cad5076bd0) | Oct 06, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [a689b6a7d5](https://linux-hardware.org/?probe=a689b6a7d5) | Oct 06, 2021 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [16a15c4fc3](https://linux-hardware.org/?probe=16a15c4fc3) | Oct 05, 2021 |
| ASRock        | AD2700-ITX                  | Desktop     | [4b04e2dcda](https://linux-hardware.org/?probe=4b04e2dcda) | Oct 05, 2021 |
| HP            | 21D0                        | Desktop     | [ba6cce80cb](https://linux-hardware.org/?probe=ba6cce80cb) | Oct 05, 2021 |
| MSI           | MS-9A45 0A                  | Desktop     | [658cbe1d32](https://linux-hardware.org/?probe=658cbe1d32) | Oct 05, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [46a61c0976](https://linux-hardware.org/?probe=46a61c0976) | Oct 05, 2021 |
| Lenovo        | ThinkPad T490 20N3S37900    | Notebook    | [d863d4a930](https://linux-hardware.org/?probe=d863d4a930) | Oct 05, 2021 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [109b454a43](https://linux-hardware.org/?probe=109b454a43) | Oct 05, 2021 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [d720268b28](https://linux-hardware.org/?probe=d720268b28) | Oct 05, 2021 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [3be1453b82](https://linux-hardware.org/?probe=3be1453b82) | Oct 05, 2021 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [9c8c59d923](https://linux-hardware.org/?probe=9c8c59d923) | Oct 05, 2021 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [c4eb768046](https://linux-hardware.org/?probe=c4eb768046) | Oct 04, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [1ca6c5085e](https://linux-hardware.org/?probe=1ca6c5085e) | Oct 04, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [9c4f3417d4](https://linux-hardware.org/?probe=9c4f3417d4) | Oct 04, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [3e695d6744](https://linux-hardware.org/?probe=3e695d6744) | Oct 04, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [fb94b38f6d](https://linux-hardware.org/?probe=fb94b38f6d) | Oct 04, 2021 |
| HP            | ProBook 450 G5              | Notebook    | [49aa400f72](https://linux-hardware.org/?probe=49aa400f72) | Oct 04, 2021 |
| Dell          | Latitude 5480               | Notebook    | [91853b0452](https://linux-hardware.org/?probe=91853b0452) | Oct 04, 2021 |
| ASUSTek       | X750JN                      | Notebook    | [842a79b323](https://linux-hardware.org/?probe=842a79b323) | Oct 04, 2021 |
| ASUSTek       | PRIME B250M-PLUS            | Desktop     | [f9ad2204b1](https://linux-hardware.org/?probe=f9ad2204b1) | Oct 03, 2021 |
| Dell          | Precision M6800             | Notebook    | [b85ad62146](https://linux-hardware.org/?probe=b85ad62146) | Oct 03, 2021 |
| Dell          | Precision M6800             | Notebook    | [61a932607b](https://linux-hardware.org/?probe=61a932607b) | Oct 03, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [cbd6e4f12a](https://linux-hardware.org/?probe=cbd6e4f12a) | Oct 03, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [475a384812](https://linux-hardware.org/?probe=475a384812) | Oct 03, 2021 |
| Gigabyte      | G41MT-D3                    | Desktop     | [5add233ca1](https://linux-hardware.org/?probe=5add233ca1) | Oct 03, 2021 |
| Lenovo        | ThinkPad T410 2522PT3       | Notebook    | [7e7e4cf452](https://linux-hardware.org/?probe=7e7e4cf452) | Oct 03, 2021 |
| ASRock        | H97M Pro4                   | Desktop     | [4a45a79a05](https://linux-hardware.org/?probe=4a45a79a05) | Oct 03, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [8ea6adfced](https://linux-hardware.org/?probe=8ea6adfced) | Oct 03, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [618cbe489b](https://linux-hardware.org/?probe=618cbe489b) | Oct 03, 2021 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [58205ac600](https://linux-hardware.org/?probe=58205ac600) | Oct 03, 2021 |
| Lenovo        | ThinkCentre M58p 7220A72    | Desktop     | [f9fce8b13e](https://linux-hardware.org/?probe=f9fce8b13e) | Oct 03, 2021 |
| MSI           | Z270M MORTAR                | Desktop     | [8498a78a16](https://linux-hardware.org/?probe=8498a78a16) | Oct 03, 2021 |
| Lenovo        | IdeaPad FLEX 5-1570 81CA    | Convertible | [7a29b0c9a1](https://linux-hardware.org/?probe=7a29b0c9a1) | Oct 03, 2021 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [00c624b592](https://linux-hardware.org/?probe=00c624b592) | Oct 03, 2021 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [09b4e39973](https://linux-hardware.org/?probe=09b4e39973) | Oct 03, 2021 |
| Gigabyte      | H510M H                     | Desktop     | [991a31ce5a](https://linux-hardware.org/?probe=991a31ce5a) | Oct 02, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [96868e511e](https://linux-hardware.org/?probe=96868e511e) | Oct 02, 2021 |
| Lenovo        | IdeaPad S540-15IWL          | Notebook    | [34fe72eb86](https://linux-hardware.org/?probe=34fe72eb86) | Oct 02, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [3047b3ec7c](https://linux-hardware.org/?probe=3047b3ec7c) | Oct 02, 2021 |
| HP            | ProBook 470 G5              | Notebook    | [fef4cfba03](https://linux-hardware.org/?probe=fef4cfba03) | Oct 02, 2021 |
| Lenovo        | IdeaPad 330S-15IKB D 81F... | Notebook    | [2432bc7806](https://linux-hardware.org/?probe=2432bc7806) | Oct 02, 2021 |
| Lenovo        | ThinkPad T470 20HES0FA02    | Notebook    | [b368193a4e](https://linux-hardware.org/?probe=b368193a4e) | Oct 02, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [76a1cfb6ee](https://linux-hardware.org/?probe=76a1cfb6ee) | Oct 02, 2021 |
| Gigabyte      | G41MT-D3                    | Desktop     | [c449ae29aa](https://linux-hardware.org/?probe=c449ae29aa) | Oct 02, 2021 |
| Acer          | Aspire E5-432               | Notebook    | [2d6ea0cb46](https://linux-hardware.org/?probe=2d6ea0cb46) | Oct 02, 2021 |
| Notebook      | NH5x_NH7xHP                 | Notebook    | [f6fd6bd3dc](https://linux-hardware.org/?probe=f6fd6bd3dc) | Oct 02, 2021 |
| Unknown       | NF-MCP78                    | Desktop     | [177a4d511f](https://linux-hardware.org/?probe=177a4d511f) | Oct 02, 2021 |
| Notebook      | NH5x_NH7xHP                 | Notebook    | [fbcd6bfe42](https://linux-hardware.org/?probe=fbcd6bfe42) | Oct 02, 2021 |
| ASRock        | AD2700-ITX                  | Desktop     | [af8903b4d4](https://linux-hardware.org/?probe=af8903b4d4) | Oct 02, 2021 |
| ASRock        | H97M Pro4                   | Desktop     | [55a744f106](https://linux-hardware.org/?probe=55a744f106) | Oct 02, 2021 |
| Gigabyte      | X79-UP4                     | Desktop     | [349f8dbe53](https://linux-hardware.org/?probe=349f8dbe53) | Oct 01, 2021 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [c3f376b088](https://linux-hardware.org/?probe=c3f376b088) | Oct 01, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [753db07902](https://linux-hardware.org/?probe=753db07902) | Oct 01, 2021 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [f76f23b18b](https://linux-hardware.org/?probe=f76f23b18b) | Oct 01, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [db6fd3f608](https://linux-hardware.org/?probe=db6fd3f608) | Oct 01, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [2b91011d02](https://linux-hardware.org/?probe=2b91011d02) | Oct 01, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [e5838666c2](https://linux-hardware.org/?probe=e5838666c2) | Oct 01, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [b69288527f](https://linux-hardware.org/?probe=b69288527f) | Oct 01, 2021 |
| Lenovo        | ThinkPad T460p 20FWS0A60... | Notebook    | [fbcd17f6bc](https://linux-hardware.org/?probe=fbcd17f6bc) | Oct 01, 2021 |
| ASUSTek       | N501JW                      | Notebook    | [0e37d3409d](https://linux-hardware.org/?probe=0e37d3409d) | Oct 01, 2021 |
| ASUSTek       | X750JN                      | Notebook    | [275b782439](https://linux-hardware.org/?probe=275b782439) | Oct 01, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [c264fff200](https://linux-hardware.org/?probe=c264fff200) | Oct 01, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [31df81c76d](https://linux-hardware.org/?probe=31df81c76d) | Sep 30, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [819ee8affd](https://linux-hardware.org/?probe=819ee8affd) | Sep 30, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [4328d7510a](https://linux-hardware.org/?probe=4328d7510a) | Sep 30, 2021 |
| Lenovo        | ThinkPad T440s 20ARS2V90... | Notebook    | [b64657dafd](https://linux-hardware.org/?probe=b64657dafd) | Sep 30, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [c80d899c5d](https://linux-hardware.org/?probe=c80d899c5d) | Sep 30, 2021 |
| MSI           | MEG X570 UNIFY              | Desktop     | [98852179e1](https://linux-hardware.org/?probe=98852179e1) | Sep 30, 2021 |
| Acer          | Aspire A515-44              | Notebook    | [bce4c19b2e](https://linux-hardware.org/?probe=bce4c19b2e) | Sep 30, 2021 |
| AYADEVICE     | AYA NEO 2021                | Tablet      | [e87776a955](https://linux-hardware.org/?probe=e87776a955) | Sep 30, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [20517ef47c](https://linux-hardware.org/?probe=20517ef47c) | Sep 30, 2021 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [30974235ea](https://linux-hardware.org/?probe=30974235ea) | Sep 29, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [1e96ea621f](https://linux-hardware.org/?probe=1e96ea621f) | Sep 29, 2021 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [a47ae6e7b0](https://linux-hardware.org/?probe=a47ae6e7b0) | Sep 29, 2021 |
| Lenovo        | ThinkPad T460p 20FWS0A60... | Notebook    | [33dd196096](https://linux-hardware.org/?probe=33dd196096) | Sep 29, 2021 |
| Lenovo        | ThinkPad T460p 20FWS0A60... | Notebook    | [27c1d71909](https://linux-hardware.org/?probe=27c1d71909) | Sep 29, 2021 |
| MSI           | GE75 Raider 10SFS           | Notebook    | [a7cf4e7fcf](https://linux-hardware.org/?probe=a7cf4e7fcf) | Sep 29, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [52fe5aa259](https://linux-hardware.org/?probe=52fe5aa259) | Sep 29, 2021 |
| Gigabyte      | GA-MA69GM-S2H               | Desktop     | [b1f14324be](https://linux-hardware.org/?probe=b1f14324be) | Sep 29, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [b184f7a668](https://linux-hardware.org/?probe=b184f7a668) | Sep 29, 2021 |
| Panasonic     | CFSV9-2                     | Notebook    | [05b8edc925](https://linux-hardware.org/?probe=05b8edc925) | Sep 29, 2021 |
| ASUSTek       | SABERTOOTH Z97 MARK 2       | Desktop     | [40295a8f09](https://linux-hardware.org/?probe=40295a8f09) | Sep 29, 2021 |
| Lenovo        | B320-14IKB 81CC             | Notebook    | [a460edd4e8](https://linux-hardware.org/?probe=a460edd4e8) | Sep 29, 2021 |
| HP            | Elite x2 1012 G1            | Notebook    | [e19bf91522](https://linux-hardware.org/?probe=e19bf91522) | Sep 29, 2021 |
| HP            | 1998                        | Desktop     | [bb31e60922](https://linux-hardware.org/?probe=bb31e60922) | Sep 28, 2021 |
| ASRock        | H170M Pro4                  | Desktop     | [062fe3bada](https://linux-hardware.org/?probe=062fe3bada) | Sep 28, 2021 |
| Dell          | Latitude 7490               | Notebook    | [8baaa9f52d](https://linux-hardware.org/?probe=8baaa9f52d) | Sep 28, 2021 |
| Lenovo        | Yoga 510-15ISK 80S8         | Convertible | [56e69db298](https://linux-hardware.org/?probe=56e69db298) | Sep 28, 2021 |
| HP            | ProBook 430 G4              | Notebook    | [fb90b5261c](https://linux-hardware.org/?probe=fb90b5261c) | Sep 28, 2021 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [9682e59e98](https://linux-hardware.org/?probe=9682e59e98) | Sep 28, 2021 |
| Foxconn       | 2ABF                        | Desktop     | [2acf5e4c6d](https://linux-hardware.org/?probe=2acf5e4c6d) | Sep 28, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [37aeabe587](https://linux-hardware.org/?probe=37aeabe587) | Sep 27, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [a451fc441b](https://linux-hardware.org/?probe=a451fc441b) | Sep 27, 2021 |
| HP            | ProBook 430 G4              | Notebook    | [a582479ed0](https://linux-hardware.org/?probe=a582479ed0) | Sep 27, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [643c70dec0](https://linux-hardware.org/?probe=643c70dec0) | Sep 27, 2021 |
| Lenovo        | 318E SDK0J40697 WIN 3305... | Desktop     | [9cd559605c](https://linux-hardware.org/?probe=9cd559605c) | Sep 27, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [0e614dfffe](https://linux-hardware.org/?probe=0e614dfffe) | Sep 27, 2021 |
| Lenovo        | 318E SDK0J40697 WIN 3305... | Desktop     | [68f4ff7431](https://linux-hardware.org/?probe=68f4ff7431) | Sep 27, 2021 |
| HP            | 8053                        | Desktop     | [e74bf378e7](https://linux-hardware.org/?probe=e74bf378e7) | Sep 27, 2021 |
| Timi          | Mi NoteBook Ultra           | Notebook    | [67a48fdc00](https://linux-hardware.org/?probe=67a48fdc00) | Sep 27, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [efcdec7783](https://linux-hardware.org/?probe=efcdec7783) | Sep 27, 2021 |
| Microsoft     | Surface Pro 4               | Tablet      | [534a4fbede](https://linux-hardware.org/?probe=534a4fbede) | Sep 26, 2021 |
| ECS           | H61H2-CM                    | Desktop     | [4571e36b80](https://linux-hardware.org/?probe=4571e36b80) | Sep 26, 2021 |
| PC Special... | N85_N87,HJ,HJ1,HK1          | Notebook    | [c5a7069c64](https://linux-hardware.org/?probe=c5a7069c64) | Sep 26, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [e8c44e9282](https://linux-hardware.org/?probe=e8c44e9282) | Sep 26, 2021 |
| ASUSTek       | H110M-CS/BR                 | Desktop     | [1c65589814](https://linux-hardware.org/?probe=1c65589814) | Sep 26, 2021 |
| HP            | 8056                        | Desktop     | [a87f2d61fc](https://linux-hardware.org/?probe=a87f2d61fc) | Sep 26, 2021 |
| HUAWEI        | NBLL-WXX9                   | Notebook    | [282b0f41f7](https://linux-hardware.org/?probe=282b0f41f7) | Sep 26, 2021 |
| Dell          | Inspiron 5759               | Notebook    | [f76ea2dbe1](https://linux-hardware.org/?probe=f76ea2dbe1) | Sep 26, 2021 |
| Dell          | Inspiron 5759               | Notebook    | [faafe60242](https://linux-hardware.org/?probe=faafe60242) | Sep 26, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [edfae5b796](https://linux-hardware.org/?probe=edfae5b796) | Sep 25, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [9a5e6ea587](https://linux-hardware.org/?probe=9a5e6ea587) | Sep 25, 2021 |
| HP            | ProBook 6465b               | Notebook    | [dbff45c387](https://linux-hardware.org/?probe=dbff45c387) | Sep 25, 2021 |
| Gigabyte      | H81M-S2H                    | Desktop     | [4199c35f38](https://linux-hardware.org/?probe=4199c35f38) | Sep 25, 2021 |
| Apple         | MacBookPro16,2              | Notebook    | [f1c5cf0c43](https://linux-hardware.org/?probe=f1c5cf0c43) | Sep 25, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [08d8affc67](https://linux-hardware.org/?probe=08d8affc67) | Sep 25, 2021 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [d06dd7e0ec](https://linux-hardware.org/?probe=d06dd7e0ec) | Sep 25, 2021 |
| ASUSTek       | GD30CI                      | Desktop     | [9782c6bff5](https://linux-hardware.org/?probe=9782c6bff5) | Sep 25, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [e3cd7dfeba](https://linux-hardware.org/?probe=e3cd7dfeba) | Sep 25, 2021 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [cfe1719efb](https://linux-hardware.org/?probe=cfe1719efb) | Sep 25, 2021 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | Desktop     | [aa7607a2b7](https://linux-hardware.org/?probe=aa7607a2b7) | Sep 24, 2021 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | Desktop     | [6dad1e6449](https://linux-hardware.org/?probe=6dad1e6449) | Sep 24, 2021 |
| Lenovo        | ThinkPad Yoga 260 20FD00... | Convertible | [eccb23bda1](https://linux-hardware.org/?probe=eccb23bda1) | Sep 24, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [38be162f41](https://linux-hardware.org/?probe=38be162f41) | Sep 24, 2021 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [eae170c5e8](https://linux-hardware.org/?probe=eae170c5e8) | Sep 24, 2021 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [c204434fe3](https://linux-hardware.org/?probe=c204434fe3) | Sep 24, 2021 |
| Lenovo        | ThinkCentre M58p 7220A72    | Desktop     | [4688937b63](https://linux-hardware.org/?probe=4688937b63) | Sep 24, 2021 |
| HP            | Notebook                    | Notebook    | [36fd24364d](https://linux-hardware.org/?probe=36fd24364d) | Sep 24, 2021 |
| Dell          | Latitude 3520               | Notebook    | [2fb41f5f08](https://linux-hardware.org/?probe=2fb41f5f08) | Sep 24, 2021 |
| ASUSTek       | H81M-E R2.0                 | Desktop     | [18852b576b](https://linux-hardware.org/?probe=18852b576b) | Sep 24, 2021 |
| HP            | 0B4Ch D                     | Desktop     | [f56bf148bf](https://linux-hardware.org/?probe=f56bf148bf) | Sep 24, 2021 |
| Dell          | Latitude E6440              | Notebook    | [940e015781](https://linux-hardware.org/?probe=940e015781) | Sep 24, 2021 |
| HP            | OMEN by HP Laptop 17-an0... | Notebook    | [fa3f31f773](https://linux-hardware.org/?probe=fa3f31f773) | Sep 24, 2021 |
| Dell          | Latitude E6440              | Notebook    | [3b8c430d4d](https://linux-hardware.org/?probe=3b8c430d4d) | Sep 24, 2021 |
| ASRock        | Z390 Pro4                   | Desktop     | [7ab201b716](https://linux-hardware.org/?probe=7ab201b716) | Sep 24, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [9813ead17b](https://linux-hardware.org/?probe=9813ead17b) | Sep 23, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [49a6459ecf](https://linux-hardware.org/?probe=49a6459ecf) | Sep 23, 2021 |
| Dell          | XPS 15 9560                 | Notebook    | [522cce92e6](https://linux-hardware.org/?probe=522cce92e6) | Sep 23, 2021 |
| Dell          | XPS 15 9560                 | Notebook    | [dd8e898086](https://linux-hardware.org/?probe=dd8e898086) | Sep 23, 2021 |
| MSI           | Z370-A PRO                  | Desktop     | [694fab3776](https://linux-hardware.org/?probe=694fab3776) | Sep 23, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [c4a94c7628](https://linux-hardware.org/?probe=c4a94c7628) | Sep 23, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [f3704d3fee](https://linux-hardware.org/?probe=f3704d3fee) | Sep 23, 2021 |
| Lenovo        | ThinkPad W520 42763JU       | Notebook    | [efc15757fc](https://linux-hardware.org/?probe=efc15757fc) | Sep 23, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [aac09f49b8](https://linux-hardware.org/?probe=aac09f49b8) | Sep 23, 2021 |
| Dell          | Latitude 5480               | Notebook    | [b40498281b](https://linux-hardware.org/?probe=b40498281b) | Sep 23, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [5f88f081a7](https://linux-hardware.org/?probe=5f88f081a7) | Sep 23, 2021 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [7360f8d859](https://linux-hardware.org/?probe=7360f8d859) | Sep 23, 2021 |
| Framework     | Laptop                      | Notebook    | [0948fcfae4](https://linux-hardware.org/?probe=0948fcfae4) | Sep 22, 2021 |
| System76      | Thelio Mira thelio-mira-... | Desktop     | [f6580e7358](https://linux-hardware.org/?probe=f6580e7358) | Sep 22, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [d7ccece3d4](https://linux-hardware.org/?probe=d7ccece3d4) | Sep 22, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [466841a201](https://linux-hardware.org/?probe=466841a201) | Sep 22, 2021 |
| ASUSTek       | X99-S                       | Desktop     | [454c9e999e](https://linux-hardware.org/?probe=454c9e999e) | Sep 22, 2021 |
| HP            | EliteBook 850 G5            | Notebook    | [b6a9870be5](https://linux-hardware.org/?probe=b6a9870be5) | Sep 22, 2021 |
| Notebook      | NH55RGQ                     | Notebook    | [a3dfc7df90](https://linux-hardware.org/?probe=a3dfc7df90) | Sep 22, 2021 |
| Apple         | MacBookPro7,1               | Notebook    | [451b48faab](https://linux-hardware.org/?probe=451b48faab) | Sep 22, 2021 |
| Dell          | XPS 15 9550                 | Notebook    | [6e9f3c8012](https://linux-hardware.org/?probe=6e9f3c8012) | Sep 22, 2021 |
| Dell          | Inspiron 5558               | Notebook    | [85436af47e](https://linux-hardware.org/?probe=85436af47e) | Sep 22, 2021 |
| Dell          | 05XGC8 A01                  | Desktop     | [ea9f525cf5](https://linux-hardware.org/?probe=ea9f525cf5) | Sep 22, 2021 |
| Lenovo        | ThinkPad Yoga 260 20FD00... | Convertible | [85b5f14102](https://linux-hardware.org/?probe=85b5f14102) | Sep 22, 2021 |
| Dell          | Latitude E6440              | Notebook    | [45f88af089](https://linux-hardware.org/?probe=45f88af089) | Sep 22, 2021 |
| Dell          | Latitude E6440              | Notebook    | [28a8dacd93](https://linux-hardware.org/?probe=28a8dacd93) | Sep 22, 2021 |
| Dell          | 0GC080                      | Desktop     | [0297b84b90](https://linux-hardware.org/?probe=0297b84b90) | Sep 22, 2021 |
| Dell          | 0GC080                      | Desktop     | [d66102b7f1](https://linux-hardware.org/?probe=d66102b7f1) | Sep 22, 2021 |
| Lenovo        | ThinkPad T530 2429GG3       | Notebook    | [afe7d6e9b3](https://linux-hardware.org/?probe=afe7d6e9b3) | Sep 21, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [797662a7af](https://linux-hardware.org/?probe=797662a7af) | Sep 21, 2021 |
| Lenovo        | ThinkPad E15 20RES6DF07     | Notebook    | [2f5045ab95](https://linux-hardware.org/?probe=2f5045ab95) | Sep 21, 2021 |
| Acer          | TravelMate P215-53          | Notebook    | [fd67b85b86](https://linux-hardware.org/?probe=fd67b85b86) | Sep 21, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | Desktop     | [50bccc87d3](https://linux-hardware.org/?probe=50bccc87d3) | Sep 21, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | Desktop     | [9f131c2aec](https://linux-hardware.org/?probe=9f131c2aec) | Sep 21, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [12cd034896](https://linux-hardware.org/?probe=12cd034896) | Sep 21, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [1a5fe3b0cf](https://linux-hardware.org/?probe=1a5fe3b0cf) | Sep 20, 2021 |
| MSI           | E3M WORKSTATION V5          | Desktop     | [6924705831](https://linux-hardware.org/?probe=6924705831) | Sep 20, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QTA0... | Notebook    | [9a59e3a4f1](https://linux-hardware.org/?probe=9a59e3a4f1) | Sep 20, 2021 |
| Lenovo        | IdeaPad S540-15IWL          | Notebook    | [39249e7f87](https://linux-hardware.org/?probe=39249e7f87) | Sep 20, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [76f8dfd499](https://linux-hardware.org/?probe=76f8dfd499) | Sep 20, 2021 |
| Unknown       | Unknown                     | Notebook    | [2380a0486d](https://linux-hardware.org/?probe=2380a0486d) | Sep 20, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [abeb038c57](https://linux-hardware.org/?probe=abeb038c57) | Sep 20, 2021 |
| Lenovo        | ThinkPad T460s 20FAS2J70... | Notebook    | [e902d6e1e3](https://linux-hardware.org/?probe=e902d6e1e3) | Sep 20, 2021 |
| ASUSTek       | PRIME X399-A                | Desktop     | [edd8b3c5b2](https://linux-hardware.org/?probe=edd8b3c5b2) | Sep 20, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [9ea3b3a8d4](https://linux-hardware.org/?probe=9ea3b3a8d4) | Sep 19, 2021 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [9748894c7e](https://linux-hardware.org/?probe=9748894c7e) | Sep 19, 2021 |
| Lenovo        | IdeaPad Flex 5 14ARE05 8... | Convertible | [d339553d59](https://linux-hardware.org/?probe=d339553d59) | Sep 19, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [a460a3a6fb](https://linux-hardware.org/?probe=a460a3a6fb) | Sep 19, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [d1ff30effc](https://linux-hardware.org/?probe=d1ff30effc) | Sep 19, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [932f0ed739](https://linux-hardware.org/?probe=932f0ed739) | Sep 19, 2021 |
| ASUSTek       | TP410UAR                    | Convertible | [06e7a51d6a](https://linux-hardware.org/?probe=06e7a51d6a) | Sep 19, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [47dab5ec07](https://linux-hardware.org/?probe=47dab5ec07) | Sep 18, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [2c7e4f944f](https://linux-hardware.org/?probe=2c7e4f944f) | Sep 18, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [a26722252e](https://linux-hardware.org/?probe=a26722252e) | Sep 18, 2021 |
| HP            | 8055                        | Desktop     | [12a1144916](https://linux-hardware.org/?probe=12a1144916) | Sep 18, 2021 |
| HUAWEI        | EUL-WX9                     | Notebook    | [4ab59b64df](https://linux-hardware.org/?probe=4ab59b64df) | Sep 18, 2021 |
| HP            | 8055                        | Desktop     | [0404bcffca](https://linux-hardware.org/?probe=0404bcffca) | Sep 18, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [84678f812f](https://linux-hardware.org/?probe=84678f812f) | Sep 18, 2021 |
| Dell          | Inspiron M5010              | Notebook    | [92906ddd8c](https://linux-hardware.org/?probe=92906ddd8c) | Sep 18, 2021 |
| Dell          | Inspiron M5010              | Notebook    | [4d956d439c](https://linux-hardware.org/?probe=4d956d439c) | Sep 18, 2021 |
| MSI           | E3M WORKSTATION V5          | Desktop     | [d1d3f1ae4b](https://linux-hardware.org/?probe=d1d3f1ae4b) | Sep 18, 2021 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [3656e9b0ae](https://linux-hardware.org/?probe=3656e9b0ae) | Sep 18, 2021 |
| Acer          | Aspire A515-54              | Notebook    | [e44f6e672e](https://linux-hardware.org/?probe=e44f6e672e) | Sep 18, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [079bf76915](https://linux-hardware.org/?probe=079bf76915) | Sep 18, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [44902b132d](https://linux-hardware.org/?probe=44902b132d) | Sep 18, 2021 |
| Lenovo        | ThinkPad T460s 20FAS2J70... | Notebook    | [e45c338f6b](https://linux-hardware.org/?probe=e45c338f6b) | Sep 17, 2021 |
| Timi          | RedmiBook 14                | Notebook    | [ff2803fc31](https://linux-hardware.org/?probe=ff2803fc31) | Sep 17, 2021 |
| HP            | 8056                        | Desktop     | [9431176663](https://linux-hardware.org/?probe=9431176663) | Sep 17, 2021 |
| Lenovo        | ThinkPad T410 2522PT3       | Notebook    | [9b7aa55eba](https://linux-hardware.org/?probe=9b7aa55eba) | Sep 17, 2021 |
| Lenovo        | IdeaPad Flex 5 14ARE05 8... | Convertible | [171d75e4c0](https://linux-hardware.org/?probe=171d75e4c0) | Sep 17, 2021 |
| Lenovo        | IdeaPad Flex 5 14ARE05 8... | Convertible | [47fb03fde8](https://linux-hardware.org/?probe=47fb03fde8) | Sep 17, 2021 |
| Google        | Delbin                      | Notebook    | [d41f57dfff](https://linux-hardware.org/?probe=d41f57dfff) | Sep 17, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | Desktop     | [ceba17a8cc](https://linux-hardware.org/?probe=ceba17a8cc) | Sep 16, 2021 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [e5c9ce5469](https://linux-hardware.org/?probe=e5c9ce5469) | Sep 16, 2021 |
| Lenovo        | ThinkCentre M58p 7220A72    | Desktop     | [4a7b56da33](https://linux-hardware.org/?probe=4a7b56da33) | Sep 16, 2021 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [203e58b1d1](https://linux-hardware.org/?probe=203e58b1d1) | Sep 16, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [fdcc98fb1d](https://linux-hardware.org/?probe=fdcc98fb1d) | Sep 16, 2021 |
| Fujitsu       | LIFEBOOK U747               | Notebook    | [acd19e81c0](https://linux-hardware.org/?probe=acd19e81c0) | Sep 16, 2021 |
| MSI           | B85-G43 GAMING              | Desktop     | [da6e58ed2a](https://linux-hardware.org/?probe=da6e58ed2a) | Sep 16, 2021 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [ad193a0b9c](https://linux-hardware.org/?probe=ad193a0b9c) | Sep 16, 2021 |
| HUAWEI        | MACH-WX9                    | Notebook    | [cfa4f26454](https://linux-hardware.org/?probe=cfa4f26454) | Sep 15, 2021 |
| Samsung       | 700Z3C/700Z5C               | Notebook    | [8307888e2a](https://linux-hardware.org/?probe=8307888e2a) | Sep 15, 2021 |
| HP            | Laptop 15-db1xxx            | Notebook    | [c085ff8d88](https://linux-hardware.org/?probe=c085ff8d88) | Sep 15, 2021 |
| HP            | Laptop 15-db1xxx            | Notebook    | [1298ec614b](https://linux-hardware.org/?probe=1298ec614b) | Sep 15, 2021 |
| Samsung       | Galaxy TabPro S LTE         | Tablet      | [b5a56360d5](https://linux-hardware.org/?probe=b5a56360d5) | Sep 15, 2021 |
| Lenovo        | ThinkPad E490 20N80029GE    | Notebook    | [38c4c119db](https://linux-hardware.org/?probe=38c4c119db) | Sep 15, 2021 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [a92f9c3457](https://linux-hardware.org/?probe=a92f9c3457) | Sep 15, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [38d5ca16e8](https://linux-hardware.org/?probe=38d5ca16e8) | Sep 15, 2021 |
| ASRock        | H170M Pro4                  | Desktop     | [7d604a0a22](https://linux-hardware.org/?probe=7d604a0a22) | Sep 15, 2021 |
| Dell          | Inspiron 5558               | Notebook    | [1cbcb7bda4](https://linux-hardware.org/?probe=1cbcb7bda4) | Sep 15, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [cf1e0581f3](https://linux-hardware.org/?probe=cf1e0581f3) | Sep 15, 2021 |
| Gigabyte      | G41MT-D3                    | Desktop     | [ccacfc0b86](https://linux-hardware.org/?probe=ccacfc0b86) | Sep 15, 2021 |
| ECS           | G41T-M7                     | Desktop     | [42e72694fc](https://linux-hardware.org/?probe=42e72694fc) | Sep 15, 2021 |
| Dell          | 0GC080                      | Desktop     | [e7be152af1](https://linux-hardware.org/?probe=e7be152af1) | Sep 15, 2021 |
| Dell          | Inspiron 5577               | Notebook    | [c4204b06c6](https://linux-hardware.org/?probe=c4204b06c6) | Sep 15, 2021 |
| EVGA          | 111-SS-E172                 | Desktop     | [b9c8f1f9e8](https://linux-hardware.org/?probe=b9c8f1f9e8) | Sep 15, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [c9abf46ddd](https://linux-hardware.org/?probe=c9abf46ddd) | Sep 14, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [badf707f13](https://linux-hardware.org/?probe=badf707f13) | Sep 14, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [785f6c0a11](https://linux-hardware.org/?probe=785f6c0a11) | Sep 14, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [ddf06500d6](https://linux-hardware.org/?probe=ddf06500d6) | Sep 14, 2021 |
| Dell          | XPS 17 9700                 | Notebook    | [a8fa12afdc](https://linux-hardware.org/?probe=a8fa12afdc) | Sep 14, 2021 |
| ASRock        | X570M Pro4                  | Desktop     | [297bbaf6a4](https://linux-hardware.org/?probe=297bbaf6a4) | Sep 14, 2021 |
| Gigabyte      | G41MT-D3                    | Desktop     | [3983c92565](https://linux-hardware.org/?probe=3983c92565) | Sep 14, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14IHU5 8... | Notebook    | [0196b7df4b](https://linux-hardware.org/?probe=0196b7df4b) | Sep 14, 2021 |
| ASUSTek       | X556UR                      | Notebook    | [7441498212](https://linux-hardware.org/?probe=7441498212) | Sep 14, 2021 |
| Lenovo        | ThinkCentre M58p 7220A72    | Desktop     | [8dcc482baf](https://linux-hardware.org/?probe=8dcc482baf) | Sep 14, 2021 |
| Toshiba       | Satellite U940              | Notebook    | [8f227ccc77](https://linux-hardware.org/?probe=8f227ccc77) | Sep 14, 2021 |
| ASUSTek       | ROG STRIX B360-I GAMING     | Desktop     | [e0948f8a85](https://linux-hardware.org/?probe=e0948f8a85) | Sep 14, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TAA... | Notebook    | [ebcb7d7982](https://linux-hardware.org/?probe=ebcb7d7982) | Sep 14, 2021 |
| ASUSTek       | ROG STRIX B360-I GAMING     | Desktop     | [981d2b7173](https://linux-hardware.org/?probe=981d2b7173) | Sep 14, 2021 |
| ASRock        | H170M Pro4                  | Desktop     | [59ab06bdda](https://linux-hardware.org/?probe=59ab06bdda) | Sep 14, 2021 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [0ab25d0365](https://linux-hardware.org/?probe=0ab25d0365) | Sep 14, 2021 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [324d0c6e4d](https://linux-hardware.org/?probe=324d0c6e4d) | Sep 14, 2021 |
| ASUSTek       | ROG STRIX B360-I GAMING     | Desktop     | [1fa62f847b](https://linux-hardware.org/?probe=1fa62f847b) | Sep 14, 2021 |
| Dell          | XPS 17 9700                 | Notebook    | [357f906ac7](https://linux-hardware.org/?probe=357f906ac7) | Sep 14, 2021 |
| Microsoft     | Surface Pro                 | Tablet      | [814c706a03](https://linux-hardware.org/?probe=814c706a03) | Sep 13, 2021 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [5d7ab37245](https://linux-hardware.org/?probe=5d7ab37245) | Sep 13, 2021 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [28ce3a6f8d](https://linux-hardware.org/?probe=28ce3a6f8d) | Sep 13, 2021 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [79242cc1bb](https://linux-hardware.org/?probe=79242cc1bb) | Sep 13, 2021 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [66154dd009](https://linux-hardware.org/?probe=66154dd009) | Sep 13, 2021 |
| RCA           | W101AS23T2                  | Tablet      | [a9124eaa6f](https://linux-hardware.org/?probe=a9124eaa6f) | Sep 13, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [0b058e8bd8](https://linux-hardware.org/?probe=0b058e8bd8) | Sep 13, 2021 |
| RCA           | W101AS23T2                  | Tablet      | [ef4214903a](https://linux-hardware.org/?probe=ef4214903a) | Sep 13, 2021 |
| HP            | OMEN by HP Laptop 17-an0... | Notebook    | [bc67d877ef](https://linux-hardware.org/?probe=bc67d877ef) | Sep 13, 2021 |
| Acer          | Aspire X3470                | Desktop     | [1a3f77423d](https://linux-hardware.org/?probe=1a3f77423d) | Sep 13, 2021 |
| Acer          | Aspire X3470                | Desktop     | [f53f569155](https://linux-hardware.org/?probe=f53f569155) | Sep 13, 2021 |
| Dell          | Inspiron 5459               | Notebook    | [ef87caa5ba](https://linux-hardware.org/?probe=ef87caa5ba) | Sep 12, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [bfe6584c68](https://linux-hardware.org/?probe=bfe6584c68) | Sep 12, 2021 |
| HP            | Pavilion dv7                | Notebook    | [2fd3b811f6](https://linux-hardware.org/?probe=2fd3b811f6) | Sep 12, 2021 |
| HP            | 1587h                       | Desktop     | [5447d2e6c3](https://linux-hardware.org/?probe=5447d2e6c3) | Sep 12, 2021 |
| ASRock        | AD2700-ITX                  | Desktop     | [3f1fade2ca](https://linux-hardware.org/?probe=3f1fade2ca) | Sep 12, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [d467d027ad](https://linux-hardware.org/?probe=d467d027ad) | Sep 12, 2021 |
| Lenovo        | IdeaPad Flex 5 14ARE05 8... | Convertible | [741dc92909](https://linux-hardware.org/?probe=741dc92909) | Sep 12, 2021 |
| RCA           | W101AS23T2                  | Tablet      | [afc37755bd](https://linux-hardware.org/?probe=afc37755bd) | Sep 12, 2021 |
| RCA           | W101AS23T2                  | Tablet      | [03dbbf55f9](https://linux-hardware.org/?probe=03dbbf55f9) | Sep 12, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [e82ca3db5b](https://linux-hardware.org/?probe=e82ca3db5b) | Sep 12, 2021 |
| HP            | Pavilion dv7                | Notebook    | [f58a2f5f40](https://linux-hardware.org/?probe=f58a2f5f40) | Sep 11, 2021 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [d13739db96](https://linux-hardware.org/?probe=d13739db96) | Sep 11, 2021 |
| Dell          | Inspiron 5459               | Notebook    | [feea6f3fec](https://linux-hardware.org/?probe=feea6f3fec) | Sep 11, 2021 |
| Dell          | 0F96C8 A00                  | All in one  | [6c5f2b8c6d](https://linux-hardware.org/?probe=6c5f2b8c6d) | Sep 11, 2021 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [bc6963f758](https://linux-hardware.org/?probe=bc6963f758) | Sep 11, 2021 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [bea54b0e05](https://linux-hardware.org/?probe=bea54b0e05) | Sep 11, 2021 |
| HP            | Notebook                    | Notebook    | [2a564798fd](https://linux-hardware.org/?probe=2a564798fd) | Sep 11, 2021 |
| Intel         | DG41RQ AAE54511-201         | Desktop     | [14957a27ad](https://linux-hardware.org/?probe=14957a27ad) | Sep 11, 2021 |
| Intel         | DG41RQ AAE54511-201         | Desktop     | [f525bfb156](https://linux-hardware.org/?probe=f525bfb156) | Sep 11, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6f8b188411](https://linux-hardware.org/?probe=6f8b188411) | Sep 11, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [0075f29194](https://linux-hardware.org/?probe=0075f29194) | Sep 11, 2021 |
| Metabox       | Alpha-X NH77DC              | Notebook    | [0b6122c2ce](https://linux-hardware.org/?probe=0b6122c2ce) | Sep 10, 2021 |
| Metabox       | Alpha-X NH77DC              | Notebook    | [98364c4883](https://linux-hardware.org/?probe=98364c4883) | Sep 10, 2021 |
| Lenovo        | V580c 20160                 | Notebook    | [773cd5b007](https://linux-hardware.org/?probe=773cd5b007) | Sep 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [58f978a554](https://linux-hardware.org/?probe=58f978a554) | Sep 10, 2021 |
| Lenovo        | IdeaPad S540-13IML 81XA     | Notebook    | [59ce224e2b](https://linux-hardware.org/?probe=59ce224e2b) | Sep 10, 2021 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [04e9d9ef11](https://linux-hardware.org/?probe=04e9d9ef11) | Sep 10, 2021 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [bbfc6ac323](https://linux-hardware.org/?probe=bbfc6ac323) | Sep 10, 2021 |
| Notebook      | PB50_70DFx,DDx              | Notebook    | [183b4447ac](https://linux-hardware.org/?probe=183b4447ac) | Sep 10, 2021 |
| HP            | Pavilion 15                 | Notebook    | [8231cbdcc6](https://linux-hardware.org/?probe=8231cbdcc6) | Sep 10, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [2f73a651d4](https://linux-hardware.org/?probe=2f73a651d4) | Sep 10, 2021 |
| Dell          | Precision 7550              | Notebook    | [42890f7542](https://linux-hardware.org/?probe=42890f7542) | Sep 10, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [74d478552c](https://linux-hardware.org/?probe=74d478552c) | Sep 10, 2021 |
| HP            | Pavilion 15                 | Notebook    | [f719e2f8e0](https://linux-hardware.org/?probe=f719e2f8e0) | Sep 10, 2021 |
| Gigabyte      | TRX40 AORUS MASTER          | Desktop     | [afb539ff26](https://linux-hardware.org/?probe=afb539ff26) | Sep 10, 2021 |
| Dell          | XPS 13 9360                 | Notebook    | [0c899b57ce](https://linux-hardware.org/?probe=0c899b57ce) | Sep 10, 2021 |
| Dell          | Inspiron 14-3452            | Notebook    | [d76d54447a](https://linux-hardware.org/?probe=d76d54447a) | Sep 10, 2021 |
| HUAWEI        | WRTB-WXX9                   | Notebook    | [1570fd5033](https://linux-hardware.org/?probe=1570fd5033) | Sep 09, 2021 |
| Dell          | Precision 7550              | Notebook    | [a4a1a56132](https://linux-hardware.org/?probe=a4a1a56132) | Sep 09, 2021 |
| ASUSTek       | AM1M-A                      | Desktop     | [ab6a989deb](https://linux-hardware.org/?probe=ab6a989deb) | Sep 09, 2021 |
| Gigabyte      | X99-Gaming 5                | Desktop     | [0a8ee7324e](https://linux-hardware.org/?probe=0a8ee7324e) | Sep 09, 2021 |
| ASUSTek       | AM1M-A                      | Desktop     | [bc4f850240](https://linux-hardware.org/?probe=bc4f850240) | Sep 09, 2021 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [7f60ba417d](https://linux-hardware.org/?probe=7f60ba417d) | Sep 09, 2021 |
| Acer          | WG43M                       | Desktop     | [35c29a05ff](https://linux-hardware.org/?probe=35c29a05ff) | Sep 09, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [570aa41791](https://linux-hardware.org/?probe=570aa41791) | Sep 09, 2021 |
| HP            | ZBook 17 G5                 | Notebook    | [92b0b6c126](https://linux-hardware.org/?probe=92b0b6c126) | Sep 09, 2021 |
| Lenovo        | ThinkPad T440s 20AQ006HU... | Notebook    | [b9aae4c16e](https://linux-hardware.org/?probe=b9aae4c16e) | Sep 09, 2021 |
| Acer          | Aspire A715-42G             | Notebook    | [41e7d9f66e](https://linux-hardware.org/?probe=41e7d9f66e) | Sep 09, 2021 |
| ASRock        | Z390 Taichi                 | Desktop     | [8052fb9273](https://linux-hardware.org/?probe=8052fb9273) | Sep 09, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [03aad3f850](https://linux-hardware.org/?probe=03aad3f850) | Sep 09, 2021 |
| Intel         | A133L                       | Notebook    | [5958280b38](https://linux-hardware.org/?probe=5958280b38) | Sep 09, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [15ed5db330](https://linux-hardware.org/?probe=15ed5db330) | Sep 09, 2021 |
| Google        | Delbin                      | Notebook    | [c5e8f37c1b](https://linux-hardware.org/?probe=c5e8f37c1b) | Sep 09, 2021 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [bd88876ddf](https://linux-hardware.org/?probe=bd88876ddf) | Sep 08, 2021 |
| Lenovo        | ThinkPad T550 20CKA00ECD    | Notebook    | [5b385a4866](https://linux-hardware.org/?probe=5b385a4866) | Sep 08, 2021 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [d387648c16](https://linux-hardware.org/?probe=d387648c16) | Sep 08, 2021 |
| Intel         | DG33BU AAD79951-407         | Desktop     | [69bbaa38d9](https://linux-hardware.org/?probe=69bbaa38d9) | Sep 08, 2021 |
| Lenovo        | Yoga 510-15ISK 80S8         | Convertible | [b5f8faae60](https://linux-hardware.org/?probe=b5f8faae60) | Sep 08, 2021 |
| MSI           | Bravo 15 B5DD               | Notebook    | [74bbee7dfb](https://linux-hardware.org/?probe=74bbee7dfb) | Sep 07, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [1585af0565](https://linux-hardware.org/?probe=1585af0565) | Sep 07, 2021 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [b6b99a61a3](https://linux-hardware.org/?probe=b6b99a61a3) | Sep 07, 2021 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [e6b54f6ad3](https://linux-hardware.org/?probe=e6b54f6ad3) | Sep 07, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [b34fb7492d](https://linux-hardware.org/?probe=b34fb7492d) | Sep 07, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [feff42e39c](https://linux-hardware.org/?probe=feff42e39c) | Sep 07, 2021 |
| Acer          | Aspire 7738                 | Notebook    | [ab6b1bb415](https://linux-hardware.org/?probe=ab6b1bb415) | Sep 07, 2021 |
| Lenovo        | ThinkPad X250 20CMCTO1WW    | Notebook    | [409ed1f8a4](https://linux-hardware.org/?probe=409ed1f8a4) | Sep 06, 2021 |
| Apple         | MacBookPro7,1               | Notebook    | [2b6a35c2e2](https://linux-hardware.org/?probe=2b6a35c2e2) | Sep 06, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [dcd49ffb0e](https://linux-hardware.org/?probe=dcd49ffb0e) | Sep 06, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [8275c1d1e8](https://linux-hardware.org/?probe=8275c1d1e8) | Sep 06, 2021 |
| ASRock        | H170M Pro4                  | Desktop     | [a1ef6a3a8b](https://linux-hardware.org/?probe=a1ef6a3a8b) | Sep 06, 2021 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [546843fe50](https://linux-hardware.org/?probe=546843fe50) | Sep 06, 2021 |
| HP            | 2AF7                        | Desktop     | [ea75e63661](https://linux-hardware.org/?probe=ea75e63661) | Sep 06, 2021 |
| Lenovo        | ThinkPad T440p 20AN006NU... | Notebook    | [498e35c473](https://linux-hardware.org/?probe=498e35c473) | Sep 06, 2021 |
| Dell          | Inspiron 5577               | Notebook    | [b60c660326](https://linux-hardware.org/?probe=b60c660326) | Sep 06, 2021 |
| ASUSTek       | G11CD-K                     | Desktop     | [c4364afff6](https://linux-hardware.org/?probe=c4364afff6) | Sep 05, 2021 |
| Lenovo        | ThinkPad P50 20EQS64N1N     | Notebook    | [51637c3908](https://linux-hardware.org/?probe=51637c3908) | Sep 05, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [a8f9c859be](https://linux-hardware.org/?probe=a8f9c859be) | Sep 05, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [3c5b6aa997](https://linux-hardware.org/?probe=3c5b6aa997) | Sep 05, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [38256f8942](https://linux-hardware.org/?probe=38256f8942) | Sep 05, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [734b8a2cfa](https://linux-hardware.org/?probe=734b8a2cfa) | Sep 05, 2021 |
| Gigabyte      | Z370N WIFI-CF               | Desktop     | [cc4ad372df](https://linux-hardware.org/?probe=cc4ad372df) | Sep 05, 2021 |
| Apple         | MacBookPro9,1               | Notebook    | [78f1531e54](https://linux-hardware.org/?probe=78f1531e54) | Sep 05, 2021 |
| Apple         | MacBookPro9,1               | Notebook    | [d306a73462](https://linux-hardware.org/?probe=d306a73462) | Sep 05, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [ffa4f6aef7](https://linux-hardware.org/?probe=ffa4f6aef7) | Sep 05, 2021 |
| PC Special... | N150CU                      | Notebook    | [2fd6f4b53c](https://linux-hardware.org/?probe=2fd6f4b53c) | Sep 05, 2021 |
| ASUSTek       | X555QA                      | Notebook    | [043083e9e8](https://linux-hardware.org/?probe=043083e9e8) | Sep 04, 2021 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [b1bb1e8325](https://linux-hardware.org/?probe=b1bb1e8325) | Sep 04, 2021 |
| Dell          | Inspiron 5558               | Notebook    | [04ee8db8eb](https://linux-hardware.org/?probe=04ee8db8eb) | Sep 04, 2021 |
| HP            | 2AF7                        | Desktop     | [63afb7c7f5](https://linux-hardware.org/?probe=63afb7c7f5) | Sep 04, 2021 |
| Hampoo        | Cherry Trail CR             | Notebook    | [c1a354c2e2](https://linux-hardware.org/?probe=c1a354c2e2) | Sep 03, 2021 |
| HP            | 2B5E                        | Desktop     | [51682d8e81](https://linux-hardware.org/?probe=51682d8e81) | Sep 03, 2021 |
| HP            | 2B5E                        | Desktop     | [9fd111c3eb](https://linux-hardware.org/?probe=9fd111c3eb) | Sep 03, 2021 |
| HP            | ZBook 15 G3                 | Notebook    | [975a9765d5](https://linux-hardware.org/?probe=975a9765d5) | Sep 03, 2021 |
| HP            | ZBook 15 G3                 | Notebook    | [b27580d3b3](https://linux-hardware.org/?probe=b27580d3b3) | Sep 03, 2021 |
| ASUSTek       | K53SV                       | Notebook    | [f617f97f20](https://linux-hardware.org/?probe=f617f97f20) | Sep 03, 2021 |
| HP            | 8056                        | Desktop     | [b9c18a445b](https://linux-hardware.org/?probe=b9c18a445b) | Sep 03, 2021 |
| Lenovo        | ThinkPad X230 23255E4       | Notebook    | [4115bc0195](https://linux-hardware.org/?probe=4115bc0195) | Sep 03, 2021 |
| Dell          | Inspiron 7415 2-in-1        | Convertible | [ba2155b8b9](https://linux-hardware.org/?probe=ba2155b8b9) | Sep 03, 2021 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [c55d1ba8bf](https://linux-hardware.org/?probe=c55d1ba8bf) | Sep 03, 2021 |
| HP            | Spectre Notebook            | Notebook    | [6a3406a77f](https://linux-hardware.org/?probe=6a3406a77f) | Sep 02, 2021 |
| HP            | Spectre Notebook            | Notebook    | [9966ff0b8f](https://linux-hardware.org/?probe=9966ff0b8f) | Sep 02, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [43894b89a7](https://linux-hardware.org/?probe=43894b89a7) | Sep 02, 2021 |
| Lenovo        | ThinkPad T490s 20NX003NR... | Notebook    | [972f2ce955](https://linux-hardware.org/?probe=972f2ce955) | Sep 02, 2021 |
| Dell          | Latitude E5420              | Notebook    | [7cbabbfdf3](https://linux-hardware.org/?probe=7cbabbfdf3) | Sep 02, 2021 |
| Dell          | Latitude 7400               | Notebook    | [a72ba74a3f](https://linux-hardware.org/?probe=a72ba74a3f) | Sep 02, 2021 |
| Dell          | Latitude 5580               | Notebook    | [2d949d7117](https://linux-hardware.org/?probe=2d949d7117) | Sep 02, 2021 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [167e800e3a](https://linux-hardware.org/?probe=167e800e3a) | Sep 02, 2021 |
| ASRock        | P55M Pro                    | Desktop     | [b6408718ee](https://linux-hardware.org/?probe=b6408718ee) | Sep 02, 2021 |
| ASUSTek       | X456UQ                      | Notebook    | [6ce8e44ad3](https://linux-hardware.org/?probe=6ce8e44ad3) | Sep 02, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [724ad5d6a2](https://linux-hardware.org/?probe=724ad5d6a2) | Sep 02, 2021 |
| Positivo      | C41TB                       | Notebook    | [d100e19cde](https://linux-hardware.org/?probe=d100e19cde) | Sep 01, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [5e4bbca202](https://linux-hardware.org/?probe=5e4bbca202) | Sep 01, 2021 |
| ASRock        | X300M-STX                   | Desktop     | [79afad37d2](https://linux-hardware.org/?probe=79afad37d2) | Sep 01, 2021 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [d2f0fba8f9](https://linux-hardware.org/?probe=d2f0fba8f9) | Sep 01, 2021 |
| Dell          | Latitude E7270              | Notebook    | [1bd5f17116](https://linux-hardware.org/?probe=1bd5f17116) | Sep 01, 2021 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [7bb30a79c1](https://linux-hardware.org/?probe=7bb30a79c1) | Sep 01, 2021 |
| Positivo      | C41TB                       | Notebook    | [e904092d0d](https://linux-hardware.org/?probe=e904092d0d) | Sep 01, 2021 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [37c4ed4ed7](https://linux-hardware.org/?probe=37c4ed4ed7) | Sep 01, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [6ce2d4fb15](https://linux-hardware.org/?probe=6ce2d4fb15) | Sep 01, 2021 |
| Gigabyte      | B550M DS3H                  | Desktop     | [20389db1bd](https://linux-hardware.org/?probe=20389db1bd) | Aug 31, 2021 |
| Lenovo        | ThinkPad T490 20N2S13B00    | Notebook    | [504e179093](https://linux-hardware.org/?probe=504e179093) | Aug 31, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [44eda17ebc](https://linux-hardware.org/?probe=44eda17ebc) | Aug 31, 2021 |
| Apple         | MacBookPro12,1              | Notebook    | [79010f7e30](https://linux-hardware.org/?probe=79010f7e30) | Aug 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [35c6eb0703](https://linux-hardware.org/?probe=35c6eb0703) | Aug 31, 2021 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [1f13431849](https://linux-hardware.org/?probe=1f13431849) | Aug 31, 2021 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [3ccd4032a1](https://linux-hardware.org/?probe=3ccd4032a1) | Aug 31, 2021 |
| Dell          | Latitude 7400               | Notebook    | [256ab697f4](https://linux-hardware.org/?probe=256ab697f4) | Aug 31, 2021 |
| HP            | 2AF7                        | Desktop     | [38b5cbf28d](https://linux-hardware.org/?probe=38b5cbf28d) | Aug 31, 2021 |
| ASRock        | H97M Pro4                   | Desktop     | [96d9d18052](https://linux-hardware.org/?probe=96d9d18052) | Aug 31, 2021 |
| ASRock        | H97M Pro4                   | Desktop     | [fb5e0539da](https://linux-hardware.org/?probe=fb5e0539da) | Aug 31, 2021 |
| Dell          | G5 5500                     | Notebook    | [50db6e93f1](https://linux-hardware.org/?probe=50db6e93f1) | Aug 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [05321484a1](https://linux-hardware.org/?probe=05321484a1) | Aug 31, 2021 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [e014d83782](https://linux-hardware.org/?probe=e014d83782) | Aug 31, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [e134361dc2](https://linux-hardware.org/?probe=e134361dc2) | Aug 31, 2021 |
| Lenovo        | B50-30 80ES                 | Notebook    | [3b8f234fa8](https://linux-hardware.org/?probe=3b8f234fa8) | Aug 31, 2021 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [0cdd08839f](https://linux-hardware.org/?probe=0cdd08839f) | Aug 31, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [997ce785b2](https://linux-hardware.org/?probe=997ce785b2) | Aug 31, 2021 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [6f0e81a6d9](https://linux-hardware.org/?probe=6f0e81a6d9) | Aug 31, 2021 |
| HP            | ProBook 440 G3              | Notebook    | [c4b5fdc75f](https://linux-hardware.org/?probe=c4b5fdc75f) | Aug 30, 2021 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [dcc0bda879](https://linux-hardware.org/?probe=dcc0bda879) | Aug 30, 2021 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [e8370d3b93](https://linux-hardware.org/?probe=e8370d3b93) | Aug 30, 2021 |
| Lenovo        | ThinkPad X201 3680CG7       | Notebook    | [9565bae9c3](https://linux-hardware.org/?probe=9565bae9c3) | Aug 30, 2021 |
| Acer          | Aspire E5-573G              | Notebook    | [548bf9f816](https://linux-hardware.org/?probe=548bf9f816) | Aug 30, 2021 |
| HP            | Pavilion Laptop 15z-eh00... | Notebook    | [33233b370e](https://linux-hardware.org/?probe=33233b370e) | Aug 30, 2021 |
| MSI           | Modern 14 B4MW              | Notebook    | [75cbc94a98](https://linux-hardware.org/?probe=75cbc94a98) | Aug 30, 2021 |
| Acer          | Aspire F5-571G              | Notebook    | [d3d0e83199](https://linux-hardware.org/?probe=d3d0e83199) | Aug 30, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [6d630f76dc](https://linux-hardware.org/?probe=6d630f76dc) | Aug 30, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [9a3be042e0](https://linux-hardware.org/?probe=9a3be042e0) | Aug 30, 2021 |
| HP            | 8056                        | Desktop     | [8614fae216](https://linux-hardware.org/?probe=8614fae216) | Aug 30, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [8d862a60c9](https://linux-hardware.org/?probe=8d862a60c9) | Aug 29, 2021 |
| VINGA         | Iron S140                   | Notebook    | [8a48730847](https://linux-hardware.org/?probe=8a48730847) | Aug 29, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [ff35c10221](https://linux-hardware.org/?probe=ff35c10221) | Aug 29, 2021 |
| HP            | 198E                        | Desktop     | [82d1a8a5a7](https://linux-hardware.org/?probe=82d1a8a5a7) | Aug 29, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [e539faacf5](https://linux-hardware.org/?probe=e539faacf5) | Aug 29, 2021 |
| Lenovo        | ThinkPad T450 20BU000QLM    | Notebook    | [fce2351650](https://linux-hardware.org/?probe=fce2351650) | Aug 29, 2021 |
| Gigabyte      | G41MT-D3                    | Desktop     | [d2b4c85e96](https://linux-hardware.org/?probe=d2b4c85e96) | Aug 29, 2021 |
| Toshiba       | Satellite C845D             | Notebook    | [ac992ef3e5](https://linux-hardware.org/?probe=ac992ef3e5) | Aug 29, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [3d54bf05f1](https://linux-hardware.org/?probe=3d54bf05f1) | Aug 28, 2021 |
| MSI           | MEG X570 UNIFY              | Desktop     | [cf5f33a843](https://linux-hardware.org/?probe=cf5f33a843) | Aug 28, 2021 |
| Lenovo        | IdeaPad Flex 5 14ARE05 8... | Convertible | [313b97b58c](https://linux-hardware.org/?probe=313b97b58c) | Aug 28, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [5fd92a80fa](https://linux-hardware.org/?probe=5fd92a80fa) | Aug 28, 2021 |
| Lenovo        | ThinkPad X1 Yoga 4th 20S... | Convertible | [8f10e30326](https://linux-hardware.org/?probe=8f10e30326) | Aug 28, 2021 |
| Lenovo        | Board                       | Desktop     | [ec9c58b54e](https://linux-hardware.org/?probe=ec9c58b54e) | Aug 28, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [4331eedde2](https://linux-hardware.org/?probe=4331eedde2) | Aug 28, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [614ac09d36](https://linux-hardware.org/?probe=614ac09d36) | Aug 28, 2021 |
| Lenovo        | ThinkPad T450 20BU000QLM    | Notebook    | [d8daca96d1](https://linux-hardware.org/?probe=d8daca96d1) | Aug 28, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [ece0ff2fa3](https://linux-hardware.org/?probe=ece0ff2fa3) | Aug 28, 2021 |
| HP            | ProBook 450 G2              | Notebook    | [8228226f9b](https://linux-hardware.org/?probe=8228226f9b) | Aug 28, 2021 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [53d712fdcb](https://linux-hardware.org/?probe=53d712fdcb) | Aug 28, 2021 |
| Dell          | XPS 17 9710                 | Notebook    | [d46f0b24a4](https://linux-hardware.org/?probe=d46f0b24a4) | Aug 28, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [3c31559d95](https://linux-hardware.org/?probe=3c31559d95) | Aug 28, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [7945f91910](https://linux-hardware.org/?probe=7945f91910) | Aug 28, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [830bfb129f](https://linux-hardware.org/?probe=830bfb129f) | Aug 27, 2021 |
| MSI           | MPG B550 GAMING CARBON W... | Desktop     | [f6049274c5](https://linux-hardware.org/?probe=f6049274c5) | Aug 27, 2021 |
| Fujitsu Si... | ESPRIMO Mobile U9200        | Notebook    | [39ae07c4d8](https://linux-hardware.org/?probe=39ae07c4d8) | Aug 27, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [934d0576e0](https://linux-hardware.org/?probe=934d0576e0) | Aug 27, 2021 |
| Lenovo        | IdeaPad Flex 5 14ARE05 8... | Convertible | [c8010f8066](https://linux-hardware.org/?probe=c8010f8066) | Aug 27, 2021 |
| Lenovo        | IdeaPad Flex 5 14ARE05 8... | Convertible | [9b218c7903](https://linux-hardware.org/?probe=9b218c7903) | Aug 27, 2021 |
| MSI           | A320M-A PRO M2              | Desktop     | [fda90307d4](https://linux-hardware.org/?probe=fda90307d4) | Aug 27, 2021 |
| PC Special... | N85_N87,HJ,HJ1,HK1          | Notebook    | [877e0e98a4](https://linux-hardware.org/?probe=877e0e98a4) | Aug 27, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [1e4bb62683](https://linux-hardware.org/?probe=1e4bb62683) | Aug 27, 2021 |
| ASUSTek       | P6T                         | Desktop     | [ad049817af](https://linux-hardware.org/?probe=ad049817af) | Aug 27, 2021 |
| HP            | 8056                        | Desktop     | [e64dab1375](https://linux-hardware.org/?probe=e64dab1375) | Aug 27, 2021 |
| Lenovo        | IdeaPad Flex 5 14ARE05 8... | Convertible | [7e3f5621ba](https://linux-hardware.org/?probe=7e3f5621ba) | Aug 27, 2021 |
| ASUSTek       | TUF GAMING X570-PRO         | Desktop     | [a0ed3c6558](https://linux-hardware.org/?probe=a0ed3c6558) | Aug 27, 2021 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [adde1df1d0](https://linux-hardware.org/?probe=adde1df1d0) | Aug 27, 2021 |
| Dell          | Inspiron 5566               | Notebook    | [21f8762e74](https://linux-hardware.org/?probe=21f8762e74) | Aug 26, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [63104dc43a](https://linux-hardware.org/?probe=63104dc43a) | Aug 26, 2021 |
| Dell          | Inspiron 5566               | Notebook    | [42184613d7](https://linux-hardware.org/?probe=42184613d7) | Aug 26, 2021 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [6e2699cc9e](https://linux-hardware.org/?probe=6e2699cc9e) | Aug 26, 2021 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [89dcb140f5](https://linux-hardware.org/?probe=89dcb140f5) | Aug 26, 2021 |
| Acer          | Aspire 5516                 | Notebook    | [5c779547e8](https://linux-hardware.org/?probe=5c779547e8) | Aug 26, 2021 |
| Maibenben     | S431                        | Notebook    | [6950bbec9b](https://linux-hardware.org/?probe=6950bbec9b) | Aug 26, 2021 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [a663972867](https://linux-hardware.org/?probe=a663972867) | Aug 26, 2021 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [d29deaa58e](https://linux-hardware.org/?probe=d29deaa58e) | Aug 26, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [d97a42e31e](https://linux-hardware.org/?probe=d97a42e31e) | Aug 26, 2021 |
| System76      | Oryx Pro                    | Notebook    | [766916b305](https://linux-hardware.org/?probe=766916b305) | Aug 26, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [2c4c7620cc](https://linux-hardware.org/?probe=2c4c7620cc) | Aug 26, 2021 |
| Gigabyte      | Z87X-D3H-CF                 | Desktop     | [b40ad47903](https://linux-hardware.org/?probe=b40ad47903) | Aug 25, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [48121667a9](https://linux-hardware.org/?probe=48121667a9) | Aug 25, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [3e39cc51a8](https://linux-hardware.org/?probe=3e39cc51a8) | Aug 25, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [74a9538d04](https://linux-hardware.org/?probe=74a9538d04) | Aug 25, 2021 |
| ASUSTek       | X750JN                      | Notebook    | [dcd95a7374](https://linux-hardware.org/?probe=dcd95a7374) | Aug 25, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [11d9254c35](https://linux-hardware.org/?probe=11d9254c35) | Aug 25, 2021 |
| HP            | ProBook 455 G7              | Notebook    | [56da4a55e4](https://linux-hardware.org/?probe=56da4a55e4) | Aug 25, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [778e5aa3ae](https://linux-hardware.org/?probe=778e5aa3ae) | Aug 25, 2021 |
| Acer          | Aspire SW5-012              | Notebook    | [fe8aa54fcd](https://linux-hardware.org/?probe=fe8aa54fcd) | Aug 25, 2021 |
| ASRock        | FM2A55M-VG3+                | Desktop     | [c2e1837665](https://linux-hardware.org/?probe=c2e1837665) | Aug 24, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [15552cf8da](https://linux-hardware.org/?probe=15552cf8da) | Aug 24, 2021 |
| Dell          | 0HH807                      | Desktop     | [fe3659d065](https://linux-hardware.org/?probe=fe3659d065) | Aug 24, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [1ab639abb8](https://linux-hardware.org/?probe=1ab639abb8) | Aug 24, 2021 |
| Lenovo        | ThinkPad X230 2325AN3       | Notebook    | [d6b5ef49af](https://linux-hardware.org/?probe=d6b5ef49af) | Aug 24, 2021 |
| Lenovo        | ThinkPad T470s 20HF0047U... | Notebook    | [900b0ce643](https://linux-hardware.org/?probe=900b0ce643) | Aug 24, 2021 |
| ASRock        | 980DE3/U3S3                 | Desktop     | [e8aadc0af0](https://linux-hardware.org/?probe=e8aadc0af0) | Aug 24, 2021 |
| Dell          | Inspiron 5559               | Notebook    | [bb902b38e1](https://linux-hardware.org/?probe=bb902b38e1) | Aug 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [49aac2eefe](https://linux-hardware.org/?probe=49aac2eefe) | Aug 24, 2021 |
| Sony          | VPCEH16EN                   | Notebook    | [b74cb4b68e](https://linux-hardware.org/?probe=b74cb4b68e) | Aug 24, 2021 |
| HP            | EliteBook 820 G4            | Notebook    | [5d6a3388dc](https://linux-hardware.org/?probe=5d6a3388dc) | Aug 24, 2021 |
| HUAWEI        | MACH-WX9                    | Notebook    | [ffd49f5a01](https://linux-hardware.org/?probe=ffd49f5a01) | Aug 23, 2021 |
| Acer          | Swift SF314-52              | Notebook    | [25ce57f1be](https://linux-hardware.org/?probe=25ce57f1be) | Aug 23, 2021 |
| Acer          | Swift SF314-52              | Notebook    | [cef75c8a5a](https://linux-hardware.org/?probe=cef75c8a5a) | Aug 23, 2021 |
| Biostar       | A68I-450 DELUXE             | Desktop     | [3e0a375af7](https://linux-hardware.org/?probe=3e0a375af7) | Aug 23, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [847e7f4c1a](https://linux-hardware.org/?probe=847e7f4c1a) | Aug 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [42c87d7154](https://linux-hardware.org/?probe=42c87d7154) | Aug 23, 2021 |
| Supermicro    | X10DRi                      | Server      | [c04f902b93](https://linux-hardware.org/?probe=c04f902b93) | Aug 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [b773fc8716](https://linux-hardware.org/?probe=b773fc8716) | Aug 23, 2021 |
| MSI           | E3M WORKSTATION V5          | Desktop     | [fa6adf65a6](https://linux-hardware.org/?probe=fa6adf65a6) | Aug 23, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [014af10464](https://linux-hardware.org/?probe=014af10464) | Aug 23, 2021 |
| HP            | 8056                        | Desktop     | [d604c95726](https://linux-hardware.org/?probe=d604c95726) | Aug 23, 2021 |
| Dell          | 0F3KHR A01                  | Desktop     | [b5bc473971](https://linux-hardware.org/?probe=b5bc473971) | Aug 23, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [e506f7ea95](https://linux-hardware.org/?probe=e506f7ea95) | Aug 23, 2021 |
| HP            | 14                          | Notebook    | [6d84790759](https://linux-hardware.org/?probe=6d84790759) | Aug 23, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [07d9074437](https://linux-hardware.org/?probe=07d9074437) | Aug 23, 2021 |
| HP            | ZBook 15 G6                 | Notebook    | [93ec0ceb52](https://linux-hardware.org/?probe=93ec0ceb52) | Aug 23, 2021 |
| Timi          | A35S                        | Notebook    | [d00b7954e8](https://linux-hardware.org/?probe=d00b7954e8) | Aug 23, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [7928c7e6e6](https://linux-hardware.org/?probe=7928c7e6e6) | Aug 23, 2021 |
| Lenovo        | Yoga 730-15IWL 81JS         | Convertible | [c682421190](https://linux-hardware.org/?probe=c682421190) | Aug 23, 2021 |
| Positivo      | C14CR21                     | Notebook    | [c4ae2acc0b](https://linux-hardware.org/?probe=c4ae2acc0b) | Aug 23, 2021 |
| ASRock        | H170M Pro4                  | Desktop     | [0cd9bde7b4](https://linux-hardware.org/?probe=0cd9bde7b4) | Aug 23, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [7373f6a54d](https://linux-hardware.org/?probe=7373f6a54d) | Aug 22, 2021 |
| Lenovo        | Yoga 730-15IWL 81JS         | Convertible | [1ba570a081](https://linux-hardware.org/?probe=1ba570a081) | Aug 22, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [3d417f197c](https://linux-hardware.org/?probe=3d417f197c) | Aug 22, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [f534340eab](https://linux-hardware.org/?probe=f534340eab) | Aug 22, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [4f6bd2a75e](https://linux-hardware.org/?probe=4f6bd2a75e) | Aug 22, 2021 |
| Lenovo        | IdeaPad FLEX-14API 81SS     | Notebook    | [b6390e7b7d](https://linux-hardware.org/?probe=b6390e7b7d) | Aug 22, 2021 |
| Lenovo        | ThinkPad T460s 20FAS7XT0... | Notebook    | [b2de2ea1ab](https://linux-hardware.org/?probe=b2de2ea1ab) | Aug 22, 2021 |
| Lenovo        | ThinkPad T460s 20FAS7XT0... | Notebook    | [9da6a33d24](https://linux-hardware.org/?probe=9da6a33d24) | Aug 22, 2021 |
| Dell          | XPS 17 9710                 | Notebook    | [2ec395c6ca](https://linux-hardware.org/?probe=2ec395c6ca) | Aug 22, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [f983e2baca](https://linux-hardware.org/?probe=f983e2baca) | Aug 22, 2021 |
| MSI           | GP62MVR 7RFX                | Notebook    | [64a52a91b1](https://linux-hardware.org/?probe=64a52a91b1) | Aug 22, 2021 |
| Acer          | Aspire ES1-572              | Notebook    | [07e3a21f1c](https://linux-hardware.org/?probe=07e3a21f1c) | Aug 22, 2021 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [b2190e55e8](https://linux-hardware.org/?probe=b2190e55e8) | Aug 22, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [7f439ff799](https://linux-hardware.org/?probe=7f439ff799) | Aug 22, 2021 |
| ASUSTek       | Z77-A                       | Desktop     | [971dc3b5c7](https://linux-hardware.org/?probe=971dc3b5c7) | Aug 21, 2021 |
| Unknown       | Unknown                     | Notebook    | [987edc4158](https://linux-hardware.org/?probe=987edc4158) | Aug 21, 2021 |
| Sony          | SVT1122B2EW                 | Notebook    | [7ef0a9c54a](https://linux-hardware.org/?probe=7ef0a9c54a) | Aug 21, 2021 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [a428352ddc](https://linux-hardware.org/?probe=a428352ddc) | Aug 21, 2021 |
| Dell          | XPS 15 9550                 | Notebook    | [1215c27927](https://linux-hardware.org/?probe=1215c27927) | Aug 21, 2021 |
| Dell          | Inspiron 13-7359            | Notebook    | [555a25c577](https://linux-hardware.org/?probe=555a25c577) | Aug 21, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [edc2f605d1](https://linux-hardware.org/?probe=edc2f605d1) | Aug 21, 2021 |
| ASUSTek       | UX303UA                     | Notebook    | [6f88337886](https://linux-hardware.org/?probe=6f88337886) | Aug 21, 2021 |
| Sony          | SVS1511X9RB                 | Notebook    | [5ee85bc3a6](https://linux-hardware.org/?probe=5ee85bc3a6) | Aug 21, 2021 |
| Sony          | SVS1511X9RB                 | Notebook    | [77326cdac5](https://linux-hardware.org/?probe=77326cdac5) | Aug 21, 2021 |
| Dell          | Precision 5550              | Notebook    | [705dbe4068](https://linux-hardware.org/?probe=705dbe4068) | Aug 21, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [112c79071e](https://linux-hardware.org/?probe=112c79071e) | Aug 21, 2021 |
| MSI           | X370 SLI PLUS               | Desktop     | [4a611b712a](https://linux-hardware.org/?probe=4a611b712a) | Aug 21, 2021 |
| HP            | 2AF7                        | Desktop     | [beb4167201](https://linux-hardware.org/?probe=beb4167201) | Aug 21, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [cece1a32de](https://linux-hardware.org/?probe=cece1a32de) | Aug 21, 2021 |
| HP            | EliteBook 820 G4            | Notebook    | [d31c0fcaac](https://linux-hardware.org/?probe=d31c0fcaac) | Aug 21, 2021 |
| Dell          | Latitude 7400               | Notebook    | [61fd9efe24](https://linux-hardware.org/?probe=61fd9efe24) | Aug 21, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [c673203c6b](https://linux-hardware.org/?probe=c673203c6b) | Aug 20, 2021 |
| Dell          | XPS L702X                   | Notebook    | [32448925cb](https://linux-hardware.org/?probe=32448925cb) | Aug 20, 2021 |
| ASUSTek       | AM1M-A                      | Desktop     | [433d420dd4](https://linux-hardware.org/?probe=433d420dd4) | Aug 20, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [6136df7463](https://linux-hardware.org/?probe=6136df7463) | Aug 20, 2021 |
| Dell          | XPS L702X                   | Notebook    | [93f7edad9b](https://linux-hardware.org/?probe=93f7edad9b) | Aug 20, 2021 |
| ASUSTek       | P6T                         | Desktop     | [d0495a4765](https://linux-hardware.org/?probe=d0495a4765) | Aug 20, 2021 |
| HP            | ProBook 450 G6              | Notebook    | [227d87ab66](https://linux-hardware.org/?probe=227d87ab66) | Aug 20, 2021 |
| ASRock        | AD2700-ITX                  | Desktop     | [1d1d8a4620](https://linux-hardware.org/?probe=1d1d8a4620) | Aug 20, 2021 |
| Chuwi         | UBook X                     | Tablet      | [5a15d9b82a](https://linux-hardware.org/?probe=5a15d9b82a) | Aug 20, 2021 |
| Lenovo        | ThinkPad P43s 20RJS1C200    | Notebook    | [3dab4fd1db](https://linux-hardware.org/?probe=3dab4fd1db) | Aug 20, 2021 |
| ASRock        | B450 Steel Legend           | Desktop     | [8fdfffdbac](https://linux-hardware.org/?probe=8fdfffdbac) | Aug 20, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [4b37f6047e](https://linux-hardware.org/?probe=4b37f6047e) | Aug 20, 2021 |
| Gigabyte      | G41MT-D3                    | Desktop     | [e49dbd40b5](https://linux-hardware.org/?probe=e49dbd40b5) | Aug 20, 2021 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [41874518ea](https://linux-hardware.org/?probe=41874518ea) | Aug 20, 2021 |
| AMI           | Cherry Trail CR             | Notebook    | [bf0f2ff4a0](https://linux-hardware.org/?probe=bf0f2ff4a0) | Aug 20, 2021 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [78feb5ae08](https://linux-hardware.org/?probe=78feb5ae08) | Aug 20, 2021 |
| Lenovo        | ThinkPad T580 20LAS5XS00    | Notebook    | [472494a25c](https://linux-hardware.org/?probe=472494a25c) | Aug 20, 2021 |
| BESSTAR Te... | HM80                        | Desktop     | [60fdee03d6](https://linux-hardware.org/?probe=60fdee03d6) | Aug 19, 2021 |
| HP            | 83E9                        | Desktop     | [21b492b0bf](https://linux-hardware.org/?probe=21b492b0bf) | Aug 19, 2021 |
| HP            | 83E9                        | Desktop     | [7cb2c3256a](https://linux-hardware.org/?probe=7cb2c3256a) | Aug 19, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [3eb5c512ad](https://linux-hardware.org/?probe=3eb5c512ad) | Aug 19, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [70e32af3f7](https://linux-hardware.org/?probe=70e32af3f7) | Aug 19, 2021 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [84153c2a8d](https://linux-hardware.org/?probe=84153c2a8d) | Aug 19, 2021 |
| Alienware     | 15 R4                       | Notebook    | [bd2c12701c](https://linux-hardware.org/?probe=bd2c12701c) | Aug 19, 2021 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | Notebook    | [0d33aed04c](https://linux-hardware.org/?probe=0d33aed04c) | Aug 19, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [b9d5b6e9e9](https://linux-hardware.org/?probe=b9d5b6e9e9) | Aug 19, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [5019993be7](https://linux-hardware.org/?probe=5019993be7) | Aug 19, 2021 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [2aed19ac0a](https://linux-hardware.org/?probe=2aed19ac0a) | Aug 19, 2021 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [5c3e90c735](https://linux-hardware.org/?probe=5c3e90c735) | Aug 19, 2021 |
| Notebook      | N150CU                      | Notebook    | [8d2621da6a](https://linux-hardware.org/?probe=8d2621da6a) | Aug 19, 2021 |
| Dell          | XPS 15 9560                 | Notebook    | [07fc61d3ba](https://linux-hardware.org/?probe=07fc61d3ba) | Aug 19, 2021 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [d789709af4](https://linux-hardware.org/?probe=d789709af4) | Aug 19, 2021 |
| Gigabyte      | P55-USB3                    | Desktop     | [5e6a1d1926](https://linux-hardware.org/?probe=5e6a1d1926) | Aug 19, 2021 |
| HP            | 8056                        | Desktop     | [44b754f972](https://linux-hardware.org/?probe=44b754f972) | Aug 19, 2021 |
| Lenovo        | ThinkPad W540 20BHS04T0P    | Notebook    | [24f73e707a](https://linux-hardware.org/?probe=24f73e707a) | Aug 18, 2021 |
| ASUSTek       | AM1M-A                      | Desktop     | [c0653de55c](https://linux-hardware.org/?probe=c0653de55c) | Aug 18, 2021 |
| HP            | EliteBook x360 830 G5       | Convertible | [6c1ab8d85f](https://linux-hardware.org/?probe=6c1ab8d85f) | Aug 18, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [6eaf105bca](https://linux-hardware.org/?probe=6eaf105bca) | Aug 18, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [7731a3a1da](https://linux-hardware.org/?probe=7731a3a1da) | Aug 18, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [64adb81ad2](https://linux-hardware.org/?probe=64adb81ad2) | Aug 18, 2021 |
| Chuwi         | Hi10 X                      | Tablet      | [2e4833ff3b](https://linux-hardware.org/?probe=2e4833ff3b) | Aug 18, 2021 |
| Chuwi         | Hi10 X                      | Tablet      | [366e1c4e64](https://linux-hardware.org/?probe=366e1c4e64) | Aug 18, 2021 |
| HP            | 2AF7                        | Desktop     | [909c6f5c0a](https://linux-hardware.org/?probe=909c6f5c0a) | Aug 18, 2021 |
| ASRock        | X399 Taichi                 | Desktop     | [efead486a3](https://linux-hardware.org/?probe=efead486a3) | Aug 18, 2021 |
| HP            | 82F2 A01                    | Desktop     | [b6847d9605](https://linux-hardware.org/?probe=b6847d9605) | Aug 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [a613776a9c](https://linux-hardware.org/?probe=a613776a9c) | Aug 18, 2021 |
| HP            | Pavilion dv7                | Notebook    | [7d6c08fc9e](https://linux-hardware.org/?probe=7d6c08fc9e) | Aug 17, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [33bfc09a3a](https://linux-hardware.org/?probe=33bfc09a3a) | Aug 17, 2021 |
| ASUSTek       | N56JN                       | Notebook    | [5c3c22a21d](https://linux-hardware.org/?probe=5c3c22a21d) | Aug 17, 2021 |
| ASUSTek       | N56JN                       | Notebook    | [affdbcbf08](https://linux-hardware.org/?probe=affdbcbf08) | Aug 17, 2021 |
| ASRock        | B460M-ITX/ac                | Desktop     | [2eb3e6f3f6](https://linux-hardware.org/?probe=2eb3e6f3f6) | Aug 17, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [28cd688d16](https://linux-hardware.org/?probe=28cd688d16) | Aug 17, 2021 |
| Gigabyte      | G41MT-S2P                   | Desktop     | [63a8a28fd9](https://linux-hardware.org/?probe=63a8a28fd9) | Aug 17, 2021 |
| HP            | 8056                        | Desktop     | [5607e09042](https://linux-hardware.org/?probe=5607e09042) | Aug 17, 2021 |
| Acer          | S7-392                      | Notebook    | [1251d42538](https://linux-hardware.org/?probe=1251d42538) | Aug 17, 2021 |
| Lenovo        | ThinkPad E14 20RA001BUK     | Notebook    | [584785653a](https://linux-hardware.org/?probe=584785653a) | Aug 17, 2021 |
| HP            | EliteBook 840 G6            | Notebook    | [43ee57ed48](https://linux-hardware.org/?probe=43ee57ed48) | Aug 17, 2021 |
| Acer          | Aspire A515-46              | Notebook    | [ad8f403c6d](https://linux-hardware.org/?probe=ad8f403c6d) | Aug 17, 2021 |
| Dell          | Latitude E6510              | Notebook    | [b7071ddea1](https://linux-hardware.org/?probe=b7071ddea1) | Aug 17, 2021 |
| Dell          | 0Y2YM6 A00                  | Desktop     | [4d3d87b641](https://linux-hardware.org/?probe=4d3d87b641) | Aug 17, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [d64c2407ca](https://linux-hardware.org/?probe=d64c2407ca) | Aug 17, 2021 |
| HP            | 15 Notebook PC              | Notebook    | [86101835e0](https://linux-hardware.org/?probe=86101835e0) | Aug 17, 2021 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | Notebook    | [10cec0686e](https://linux-hardware.org/?probe=10cec0686e) | Aug 17, 2021 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [78a3158393](https://linux-hardware.org/?probe=78a3158393) | Aug 16, 2021 |
| Intel         | NUC7i5BNB J31144-305        | Mini pc     | [1c581950df](https://linux-hardware.org/?probe=1c581950df) | Aug 16, 2021 |
| MSI           | MPG Z390I GAMING EDGE AC    | Desktop     | [391c21db23](https://linux-hardware.org/?probe=391c21db23) | Aug 16, 2021 |
| HP            | 198E                        | Desktop     | [d1c56bffb1](https://linux-hardware.org/?probe=d1c56bffb1) | Aug 15, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | Desktop     | [86f9693894](https://linux-hardware.org/?probe=86f9693894) | Aug 15, 2021 |
| HP            | ProBook 470 G5              | Notebook    | [2864cc0f2a](https://linux-hardware.org/?probe=2864cc0f2a) | Aug 15, 2021 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [b29b9f86ab](https://linux-hardware.org/?probe=b29b9f86ab) | Aug 15, 2021 |
| Microsoft     | Surface Pro                 | Tablet      | [31c30e5c1f](https://linux-hardware.org/?probe=31c30e5c1f) | Aug 15, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [419995b0da](https://linux-hardware.org/?probe=419995b0da) | Aug 15, 2021 |
| Dell          | Studio 1747                 | Notebook    | [ba0f2b7d03](https://linux-hardware.org/?probe=ba0f2b7d03) | Aug 15, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [f931b86af5](https://linux-hardware.org/?probe=f931b86af5) | Aug 15, 2021 |
| Lenovo        | ThinkCentre M58p 7220A72    | Desktop     | [cd8825c8d0](https://linux-hardware.org/?probe=cd8825c8d0) | Aug 15, 2021 |
| Lenovo        | ThinkPad T450 20BU000QLM    | Notebook    | [41e2825c3d](https://linux-hardware.org/?probe=41e2825c3d) | Aug 15, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [d34022df3b](https://linux-hardware.org/?probe=d34022df3b) | Aug 15, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [8bf626f6b3](https://linux-hardware.org/?probe=8bf626f6b3) | Aug 15, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [6909a1a841](https://linux-hardware.org/?probe=6909a1a841) | Aug 14, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [b8722b62ff](https://linux-hardware.org/?probe=b8722b62ff) | Aug 14, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [eda5da5e9d](https://linux-hardware.org/?probe=eda5da5e9d) | Aug 14, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [518309e6c8](https://linux-hardware.org/?probe=518309e6c8) | Aug 14, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [7df108445b](https://linux-hardware.org/?probe=7df108445b) | Aug 14, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [9bf7d4afd7](https://linux-hardware.org/?probe=9bf7d4afd7) | Aug 14, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [b656e3aec4](https://linux-hardware.org/?probe=b656e3aec4) | Aug 14, 2021 |
| HP            | ProBook 440 G3              | Notebook    | [e93a65b9cf](https://linux-hardware.org/?probe=e93a65b9cf) | Aug 14, 2021 |
| Framework     | Laptop                      | Notebook    | [bd868e3985](https://linux-hardware.org/?probe=bd868e3985) | Aug 14, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [5f49d58f42](https://linux-hardware.org/?probe=5f49d58f42) | Aug 14, 2021 |
| Dell          | 0NKW6Y A00                  | Desktop     | [7d0c7834be](https://linux-hardware.org/?probe=7d0c7834be) | Aug 14, 2021 |
| Chuwi         | GemiBook                    | Notebook    | [c7d0df9fbb](https://linux-hardware.org/?probe=c7d0df9fbb) | Aug 13, 2021 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [4a9b684e95](https://linux-hardware.org/?probe=4a9b684e95) | Aug 13, 2021 |
| HP            | Pavilion dv7                | Notebook    | [640a5fb2b3](https://linux-hardware.org/?probe=640a5fb2b3) | Aug 13, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [05bfca3339](https://linux-hardware.org/?probe=05bfca3339) | Aug 13, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [32bc94c4e2](https://linux-hardware.org/?probe=32bc94c4e2) | Aug 13, 2021 |
| Intel         | B75                         | Desktop     | [2bac7a8140](https://linux-hardware.org/?probe=2bac7a8140) | Aug 13, 2021 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [07f3a8a2c9](https://linux-hardware.org/?probe=07f3a8a2c9) | Aug 13, 2021 |
| Gigabyte      | Z390 D                      | Desktop     | [8bfd432fba](https://linux-hardware.org/?probe=8bfd432fba) | Aug 13, 2021 |
| Acer          | Aspire V3-772G              | Notebook    | [58d92680bb](https://linux-hardware.org/?probe=58d92680bb) | Aug 13, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [4dc4a0efe0](https://linux-hardware.org/?probe=4dc4a0efe0) | Aug 13, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [6e44d2998d](https://linux-hardware.org/?probe=6e44d2998d) | Aug 13, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [5e9853124d](https://linux-hardware.org/?probe=5e9853124d) | Aug 13, 2021 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [10db213e5d](https://linux-hardware.org/?probe=10db213e5d) | Aug 13, 2021 |
| Gigabyte      | G41MT-D3                    | Desktop     | [13558f63ab](https://linux-hardware.org/?probe=13558f63ab) | Aug 13, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [2aa119abf8](https://linux-hardware.org/?probe=2aa119abf8) | Aug 13, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [f7dabed440](https://linux-hardware.org/?probe=f7dabed440) | Aug 13, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [6f0b883adb](https://linux-hardware.org/?probe=6f0b883adb) | Aug 13, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [5d036af9c0](https://linux-hardware.org/?probe=5d036af9c0) | Aug 13, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [0b46a87be6](https://linux-hardware.org/?probe=0b46a87be6) | Aug 13, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [f8af262ae5](https://linux-hardware.org/?probe=f8af262ae5) | Aug 13, 2021 |
| Lenovo        | IdeaPad Flex 5 14ARE05 8... | Convertible | [f4dd349090](https://linux-hardware.org/?probe=f4dd349090) | Aug 13, 2021 |
| Dell          | 03NVJ6 A01                  | Desktop     | [ef0028e285](https://linux-hardware.org/?probe=ef0028e285) | Aug 12, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [8cc7d05010](https://linux-hardware.org/?probe=8cc7d05010) | Aug 12, 2021 |
| Acer          | Aspire E5-574               | Notebook    | [7fb046bc6a](https://linux-hardware.org/?probe=7fb046bc6a) | Aug 12, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [3ed6340d82](https://linux-hardware.org/?probe=3ed6340d82) | Aug 12, 2021 |
| Lenovo        | IdeaPad 720S-15IKB 81AC     | Notebook    | [adae4a7ada](https://linux-hardware.org/?probe=adae4a7ada) | Aug 12, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [185cff6125](https://linux-hardware.org/?probe=185cff6125) | Aug 12, 2021 |
| ASRock        | FM2A88X-ITX+                | Desktop     | [5f70360eea](https://linux-hardware.org/?probe=5f70360eea) | Aug 12, 2021 |
| Razer         | Blade 15 Mid 2019-Base      | Notebook    | [7b708488a2](https://linux-hardware.org/?probe=7b708488a2) | Aug 12, 2021 |
| ASRock        | FM2A88X-ITX+                | Desktop     | [aeec0ec477](https://linux-hardware.org/?probe=aeec0ec477) | Aug 12, 2021 |
| Acer          | Aspire TC-705               | Desktop     | [bbf5c161d3](https://linux-hardware.org/?probe=bbf5c161d3) | Aug 12, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [3fd838012c](https://linux-hardware.org/?probe=3fd838012c) | Aug 12, 2021 |
| Alienware     | x17 R1                      | Notebook    | [447d4de752](https://linux-hardware.org/?probe=447d4de752) | Aug 12, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [f1eabffafd](https://linux-hardware.org/?probe=f1eabffafd) | Aug 12, 2021 |
| HP            | ProBook 450 G5              | Notebook    | [745332d76b](https://linux-hardware.org/?probe=745332d76b) | Aug 12, 2021 |
| HP            | 8056                        | Desktop     | [afe5072bf8](https://linux-hardware.org/?probe=afe5072bf8) | Aug 12, 2021 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [34848a17dc](https://linux-hardware.org/?probe=34848a17dc) | Aug 12, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [2e9babd6f4](https://linux-hardware.org/?probe=2e9babd6f4) | Aug 11, 2021 |
| HP            | Pavilion 15                 | Notebook    | [4e8387b8e9](https://linux-hardware.org/?probe=4e8387b8e9) | Aug 11, 2021 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [42368b3305](https://linux-hardware.org/?probe=42368b3305) | Aug 10, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [6808748401](https://linux-hardware.org/?probe=6808748401) | Aug 10, 2021 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [7ee6c3801e](https://linux-hardware.org/?probe=7ee6c3801e) | Aug 10, 2021 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [02a92f8ff3](https://linux-hardware.org/?probe=02a92f8ff3) | Aug 10, 2021 |
| HP            | EliteBook 850 G5            | Notebook    | [b106b91bcb](https://linux-hardware.org/?probe=b106b91bcb) | Aug 10, 2021 |
| Dell          | 0KWVT8 A02                  | Desktop     | [d8e685c049](https://linux-hardware.org/?probe=d8e685c049) | Aug 10, 2021 |
| MSI           | B75MA-E33                   | Desktop     | [8a1743cb75](https://linux-hardware.org/?probe=8a1743cb75) | Aug 10, 2021 |
| Dell          | Precision 5530              | Notebook    | [e1f4582882](https://linux-hardware.org/?probe=e1f4582882) | Aug 09, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [dc5848146e](https://linux-hardware.org/?probe=dc5848146e) | Aug 09, 2021 |
| Lenovo        | ThinkPad X250 20CMCTO1WW    | Notebook    | [c3b36c30d8](https://linux-hardware.org/?probe=c3b36c30d8) | Aug 09, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [b1cab0fd9c](https://linux-hardware.org/?probe=b1cab0fd9c) | Aug 09, 2021 |
| Gigabyte      | Z270-HD3P-CF                | Desktop     | [8ad0df4157](https://linux-hardware.org/?probe=8ad0df4157) | Aug 09, 2021 |
| HP            | Pavilion dv7                | Notebook    | [a56935a751](https://linux-hardware.org/?probe=a56935a751) | Aug 09, 2021 |
| Notebook      | NH55RGQ                     | Notebook    | [985e447ff5](https://linux-hardware.org/?probe=985e447ff5) | Aug 09, 2021 |
| ASRock        | AD2700-ITX                  | Desktop     | [fac88c2a70](https://linux-hardware.org/?probe=fac88c2a70) | Aug 09, 2021 |
| HP            | ProBook 6465b               | Notebook    | [8d7f457e6e](https://linux-hardware.org/?probe=8d7f457e6e) | Aug 09, 2021 |
| Sony          | VPCEH36EG                   | Notebook    | [ec709da453](https://linux-hardware.org/?probe=ec709da453) | Aug 09, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [fa2d2aa603](https://linux-hardware.org/?probe=fa2d2aa603) | Aug 09, 2021 |
| ASUSTek       | ZenBook 13 UX331FN_UX331... | Notebook    | [fe9a44853c](https://linux-hardware.org/?probe=fe9a44853c) | Aug 08, 2021 |
| Biostar       | X370GTN                     | Desktop     | [eeff407867](https://linux-hardware.org/?probe=eeff407867) | Aug 08, 2021 |
| ASRock        | B550 Phantom Gaming 4/ac    | Desktop     | [ec3a3d05e5](https://linux-hardware.org/?probe=ec3a3d05e5) | Aug 08, 2021 |
| ASRock        | B550 Phantom Gaming 4/ac    | Desktop     | [795328301d](https://linux-hardware.org/?probe=795328301d) | Aug 08, 2021 |
| Dell          | Inspiron 5502               | Notebook    | [955889f7c8](https://linux-hardware.org/?probe=955889f7c8) | Aug 08, 2021 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [a81ec533a8](https://linux-hardware.org/?probe=a81ec533a8) | Aug 08, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [1a68be3ffe](https://linux-hardware.org/?probe=1a68be3ffe) | Aug 08, 2021 |
| Gigabyte      | G41MT-D3                    | Desktop     | [feacdb6873](https://linux-hardware.org/?probe=feacdb6873) | Aug 08, 2021 |
| HP            | 1998                        | Desktop     | [38acf34efb](https://linux-hardware.org/?probe=38acf34efb) | Aug 08, 2021 |
| MSI           | MAG B560 TORPEDO            | Desktop     | [8e1e7782d9](https://linux-hardware.org/?probe=8e1e7782d9) | Aug 08, 2021 |
| MSI           | MAG B460M MORTAR WIFI       | Desktop     | [f51ff5d22f](https://linux-hardware.org/?probe=f51ff5d22f) | Aug 07, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [5a46a3aa4a](https://linux-hardware.org/?probe=5a46a3aa4a) | Aug 07, 2021 |
| Dell          | Inspiron 5558               | Notebook    | [7b24aa2b0c](https://linux-hardware.org/?probe=7b24aa2b0c) | Aug 07, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [a18e7eaaa9](https://linux-hardware.org/?probe=a18e7eaaa9) | Aug 07, 2021 |
| Dell          | Inspiron 5406 2n1           | Convertible | [d2819f7f94](https://linux-hardware.org/?probe=d2819f7f94) | Aug 07, 2021 |
| MSI           | MAG B560 TORPEDO            | Desktop     | [4d2a5f5d27](https://linux-hardware.org/?probe=4d2a5f5d27) | Aug 07, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [322608eeb3](https://linux-hardware.org/?probe=322608eeb3) | Aug 07, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [2dd10ed83f](https://linux-hardware.org/?probe=2dd10ed83f) | Aug 07, 2021 |
| Toshiba       | TECRA Z50-A                 | Notebook    | [e04191385a](https://linux-hardware.org/?probe=e04191385a) | Aug 07, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [dd86f5be32](https://linux-hardware.org/?probe=dd86f5be32) | Aug 06, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [20b75d980d](https://linux-hardware.org/?probe=20b75d980d) | Aug 06, 2021 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [2f7d7bbb1d](https://linux-hardware.org/?probe=2f7d7bbb1d) | Aug 06, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [6e05bc86aa](https://linux-hardware.org/?probe=6e05bc86aa) | Aug 06, 2021 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [4c87b2ff27](https://linux-hardware.org/?probe=4c87b2ff27) | Aug 06, 2021 |
| Dell          | Inspiron 5323               | Notebook    | [3600f5a7a8](https://linux-hardware.org/?probe=3600f5a7a8) | Aug 06, 2021 |
| Apple         | MacBookPro16,2              | Notebook    | [4c2763b512](https://linux-hardware.org/?probe=4c2763b512) | Aug 06, 2021 |
| Notebook      | Titanium B155 MAX           | Notebook    | [f1fd39abcd](https://linux-hardware.org/?probe=f1fd39abcd) | Aug 06, 2021 |
| Dell          | Inspiron 7572               | Notebook    | [a41678d0ce](https://linux-hardware.org/?probe=a41678d0ce) | Aug 06, 2021 |
| Toshiba       | TECRA Z50-A                 | Notebook    | [6a9e7d18fc](https://linux-hardware.org/?probe=6a9e7d18fc) | Aug 06, 2021 |
| Dell          | Inspiron 7572               | Notebook    | [aea38e48c7](https://linux-hardware.org/?probe=aea38e48c7) | Aug 06, 2021 |
| HP            | 15                          | Notebook    | [24c674140c](https://linux-hardware.org/?probe=24c674140c) | Aug 05, 2021 |
| Notebook      | Titanium B155 MAX           | Notebook    | [2311d7a604](https://linux-hardware.org/?probe=2311d7a604) | Aug 05, 2021 |
| Dell          | Latitude 7410               | Notebook    | [013122833c](https://linux-hardware.org/?probe=013122833c) | Aug 05, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [f74df24802](https://linux-hardware.org/?probe=f74df24802) | Aug 05, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [a5e93c2b7f](https://linux-hardware.org/?probe=a5e93c2b7f) | Aug 05, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [6fe693a80e](https://linux-hardware.org/?probe=6fe693a80e) | Aug 05, 2021 |
| HP            | 8432                        | All in one  | [ab036fdfb9](https://linux-hardware.org/?probe=ab036fdfb9) | Aug 05, 2021 |
| HP            | ProBook 6465b               | Notebook    | [73822c2796](https://linux-hardware.org/?probe=73822c2796) | Aug 05, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [234f1782ff](https://linux-hardware.org/?probe=234f1782ff) | Aug 05, 2021 |
| Fujitsu       | LIFEBOOK A357               | Notebook    | [68af6cccad](https://linux-hardware.org/?probe=68af6cccad) | Aug 05, 2021 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [2fbf46c559](https://linux-hardware.org/?probe=2fbf46c559) | Aug 05, 2021 |
| MSI           | B450-A PRO MAX              | Desktop     | [a096b9bb71](https://linux-hardware.org/?probe=a096b9bb71) | Aug 05, 2021 |
| Acer          | Aspire V5-122P              | Notebook    | [7c04b89c8a](https://linux-hardware.org/?probe=7c04b89c8a) | Aug 04, 2021 |
| HP            | Pavilion dv6                | Notebook    | [87b441ff00](https://linux-hardware.org/?probe=87b441ff00) | Aug 04, 2021 |
| Dell          | Inspiron 5370               | Notebook    | [40360bb1e3](https://linux-hardware.org/?probe=40360bb1e3) | Aug 04, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [2c843a3d35](https://linux-hardware.org/?probe=2c843a3d35) | Aug 04, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [dfb3b0302c](https://linux-hardware.org/?probe=dfb3b0302c) | Aug 04, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [e70f3ab4cd](https://linux-hardware.org/?probe=e70f3ab4cd) | Aug 04, 2021 |
| ASUSTek       | K75DE                       | Notebook    | [139840a80c](https://linux-hardware.org/?probe=139840a80c) | Aug 04, 2021 |
| ASRockRack    | X470D4U                     | Desktop     | [b3ae79f78f](https://linux-hardware.org/?probe=b3ae79f78f) | Aug 04, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [d4f12adb88](https://linux-hardware.org/?probe=d4f12adb88) | Aug 04, 2021 |
| ASRockRack    | X470D4U                     | Desktop     | [a124194272](https://linux-hardware.org/?probe=a124194272) | Aug 04, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [dce96ae07e](https://linux-hardware.org/?probe=dce96ae07e) | Aug 04, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [345ce8fb64](https://linux-hardware.org/?probe=345ce8fb64) | Aug 04, 2021 |
| HP            | 82F2 A01                    | Desktop     | [b6b124c434](https://linux-hardware.org/?probe=b6b124c434) | Aug 03, 2021 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [b1d2bc3821](https://linux-hardware.org/?probe=b1d2bc3821) | Aug 03, 2021 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [f776a4eb93](https://linux-hardware.org/?probe=f776a4eb93) | Aug 03, 2021 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | Notebook    | [bed31de6b8](https://linux-hardware.org/?probe=bed31de6b8) | Aug 03, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [4d3a4d6db1](https://linux-hardware.org/?probe=4d3a4d6db1) | Aug 03, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [3f857761fa](https://linux-hardware.org/?probe=3f857761fa) | Aug 03, 2021 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [ad5bc52a88](https://linux-hardware.org/?probe=ad5bc52a88) | Aug 03, 2021 |
| Gigabyte      | AORUS 15G KB                | Notebook    | [323ac43e6d](https://linux-hardware.org/?probe=323ac43e6d) | Aug 03, 2021 |
| Gigabyte      | AORUS 15G KB                | Notebook    | [5e01ce0d4f](https://linux-hardware.org/?probe=5e01ce0d4f) | Aug 03, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [39919aab55](https://linux-hardware.org/?probe=39919aab55) | Aug 02, 2021 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [cc58c27c6f](https://linux-hardware.org/?probe=cc58c27c6f) | Aug 02, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [847bf89546](https://linux-hardware.org/?probe=847bf89546) | Aug 02, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [47a05531da](https://linux-hardware.org/?probe=47a05531da) | Aug 02, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [6c6c327314](https://linux-hardware.org/?probe=6c6c327314) | Aug 02, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d09a20ffb6](https://linux-hardware.org/?probe=d09a20ffb6) | Aug 02, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | Desktop     | [454fecb7fb](https://linux-hardware.org/?probe=454fecb7fb) | Aug 01, 2021 |
| Lenovo        | ThinkPad Edge E440 20C50... | Notebook    | [ba11bbceb8](https://linux-hardware.org/?probe=ba11bbceb8) | Aug 01, 2021 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [c18e0a53fc](https://linux-hardware.org/?probe=c18e0a53fc) | Aug 01, 2021 |
| HP            | Pavilion dv6                | Notebook    | [ba0a55bf85](https://linux-hardware.org/?probe=ba0a55bf85) | Aug 01, 2021 |
| Acer          | Aspire A515-54G             | Notebook    | [8431041495](https://linux-hardware.org/?probe=8431041495) | Aug 01, 2021 |
| Acer          | Aspire A515-54G             | Notebook    | [8218aa8198](https://linux-hardware.org/?probe=8218aa8198) | Aug 01, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [0d6c963f0e](https://linux-hardware.org/?probe=0d6c963f0e) | Jul 31, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [c0d8e5adf6](https://linux-hardware.org/?probe=c0d8e5adf6) | Jul 31, 2021 |
| ASRock        | B550 Phantom Gaming 4/ac    | Desktop     | [052a6762c4](https://linux-hardware.org/?probe=052a6762c4) | Jul 31, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [e88f8edeb9](https://linux-hardware.org/?probe=e88f8edeb9) | Jul 31, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [e5e3591da2](https://linux-hardware.org/?probe=e5e3591da2) | Jul 31, 2021 |
| ASRock        | X570 Phantom Gaming-ITX/... | Desktop     | [2b00e34271](https://linux-hardware.org/?probe=2b00e34271) | Jul 31, 2021 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [921bde522e](https://linux-hardware.org/?probe=921bde522e) | Jul 31, 2021 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [4a5ead6209](https://linux-hardware.org/?probe=4a5ead6209) | Jul 31, 2021 |
| HONOR         | NBD-WXX9                    | Notebook    | [2b6a0f8576](https://linux-hardware.org/?probe=2b6a0f8576) | Jul 31, 2021 |
| Lenovo        | Legion Y7000P 81LD          | Notebook    | [b92fbcc1fd](https://linux-hardware.org/?probe=b92fbcc1fd) | Jul 31, 2021 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | Notebook    | [07d66d0963](https://linux-hardware.org/?probe=07d66d0963) | Jul 30, 2021 |
| Timi          | A35S                        | Notebook    | [dfd89e45de](https://linux-hardware.org/?probe=dfd89e45de) | Jul 30, 2021 |
| Dell          | Inspiron 5323               | Notebook    | [52700f62dc](https://linux-hardware.org/?probe=52700f62dc) | Jul 30, 2021 |
| ASUSTek       | K46CM                       | Notebook    | [a627b4644e](https://linux-hardware.org/?probe=a627b4644e) | Jul 30, 2021 |
| Lenovo        | ThinkBook 13s G2 ARE 20W... | Notebook    | [23d664d987](https://linux-hardware.org/?probe=23d664d987) | Jul 30, 2021 |
| Lenovo        | ThinkBook 13s G2 ARE 20W... | Notebook    | [95a364c010](https://linux-hardware.org/?probe=95a364c010) | Jul 30, 2021 |
| ASUSTek       | K46CM                       | Notebook    | [ac14ce7f86](https://linux-hardware.org/?probe=ac14ce7f86) | Jul 30, 2021 |
| Lenovo        | ThinkBook 13s G2 ARE 20W... | Notebook    | [a95b853ed8](https://linux-hardware.org/?probe=a95b853ed8) | Jul 30, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [b5a0d25d72](https://linux-hardware.org/?probe=b5a0d25d72) | Jul 30, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [e842eefc11](https://linux-hardware.org/?probe=e842eefc11) | Jul 29, 2021 |
| Acer          | Aspire E5-576               | Notebook    | [11d9b03eca](https://linux-hardware.org/?probe=11d9b03eca) | Jul 29, 2021 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [ae31c59ee8](https://linux-hardware.org/?probe=ae31c59ee8) | Jul 29, 2021 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [20e3d5c8af](https://linux-hardware.org/?probe=20e3d5c8af) | Jul 29, 2021 |
| HP            | EliteBook 850 G6            | Notebook    | [6933a56e5a](https://linux-hardware.org/?probe=6933a56e5a) | Jul 29, 2021 |
| HP            | EliteBook 850 G6            | Notebook    | [c1c1ff83e5](https://linux-hardware.org/?probe=c1c1ff83e5) | Jul 29, 2021 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [6e097e987f](https://linux-hardware.org/?probe=6e097e987f) | Jul 29, 2021 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [8121463c28](https://linux-hardware.org/?probe=8121463c28) | Jul 29, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [21bcfb6822](https://linux-hardware.org/?probe=21bcfb6822) | Jul 29, 2021 |
| HP            | ProBook 445 G7              | Notebook    | [961bafd03a](https://linux-hardware.org/?probe=961bafd03a) | Jul 29, 2021 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [edfea43d47](https://linux-hardware.org/?probe=edfea43d47) | Jul 28, 2021 |
| HP            | EliteBook 850 G6            | Notebook    | [5b6c57fdb2](https://linux-hardware.org/?probe=5b6c57fdb2) | Jul 28, 2021 |
| HP            | EliteBook 850 G6            | Notebook    | [d95d409e75](https://linux-hardware.org/?probe=d95d409e75) | Jul 28, 2021 |
| Lenovo        | Yoga 700-14ISK 80QD         | Notebook    | [cbbc9c0451](https://linux-hardware.org/?probe=cbbc9c0451) | Jul 28, 2021 |
| Dell          | Inspiron 3502               | Notebook    | [9216707eed](https://linux-hardware.org/?probe=9216707eed) | Jul 28, 2021 |
| Acer          | Aspire A517-51G             | Notebook    | [85dececf7f](https://linux-hardware.org/?probe=85dececf7f) | Jul 28, 2021 |
| Acer          | Aspire A517-51G             | Notebook    | [4d811eb752](https://linux-hardware.org/?probe=4d811eb752) | Jul 28, 2021 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [744ab63b06](https://linux-hardware.org/?probe=744ab63b06) | Jul 28, 2021 |
| Timi          | TM1707                      | Notebook    | [69ece09721](https://linux-hardware.org/?probe=69ece09721) | Jul 28, 2021 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [c6239b2672](https://linux-hardware.org/?probe=c6239b2672) | Jul 28, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [88d668c3ab](https://linux-hardware.org/?probe=88d668c3ab) | Jul 27, 2021 |
| Prestigio     | PSB141C03                   | Notebook    | [60fe58fa1b](https://linux-hardware.org/?probe=60fe58fa1b) | Jul 27, 2021 |
| Lenovo        | ThinkPad T590 20N5S72000    | Notebook    | [f82a0e5777](https://linux-hardware.org/?probe=f82a0e5777) | Jul 27, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [fe0953d7db](https://linux-hardware.org/?probe=fe0953d7db) | Jul 27, 2021 |
| Dell          | Vostro 14-3468              | Notebook    | [c222cecae0](https://linux-hardware.org/?probe=c222cecae0) | Jul 27, 2021 |
| ASRock        | X399 Professional Gaming    | Desktop     | [5e769c8137](https://linux-hardware.org/?probe=5e769c8137) | Jul 26, 2021 |
| Gigabyte      | H61N-USB3                   | Desktop     | [25961dfa1f](https://linux-hardware.org/?probe=25961dfa1f) | Jul 26, 2021 |
| Samsung       | 305V4A/305V5A/3415VA        | Notebook    | [79fbd86b2a](https://linux-hardware.org/?probe=79fbd86b2a) | Jul 26, 2021 |
| Dell          | Latitude 7400               | Notebook    | [0ad7b49f7a](https://linux-hardware.org/?probe=0ad7b49f7a) | Jul 26, 2021 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [4f26f93184](https://linux-hardware.org/?probe=4f26f93184) | Jul 26, 2021 |
| Fujitsu       | LIFEBOOK T901               | Notebook    | [a470eeaa37](https://linux-hardware.org/?probe=a470eeaa37) | Jul 26, 2021 |
| Gigabyte      | H97M-DS3P                   | Desktop     | [c5f1df2581](https://linux-hardware.org/?probe=c5f1df2581) | Jul 26, 2021 |
| HP            | 2AF7                        | Desktop     | [a24b46f292](https://linux-hardware.org/?probe=a24b46f292) | Jul 26, 2021 |
| Samsung       | 305V4A/305V5A/3415VA        | Notebook    | [7df57c3e0c](https://linux-hardware.org/?probe=7df57c3e0c) | Jul 25, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [a085cda70b](https://linux-hardware.org/?probe=a085cda70b) | Jul 25, 2021 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [c94593c3bd](https://linux-hardware.org/?probe=c94593c3bd) | Jul 25, 2021 |
| Dell          | Inspiron N4030              | Notebook    | [3f20462c62](https://linux-hardware.org/?probe=3f20462c62) | Jul 25, 2021 |
| HP            | Laptop 15-db1xxx            | Notebook    | [97b8085def](https://linux-hardware.org/?probe=97b8085def) | Jul 25, 2021 |
| Acer          | Aspire A315-42G             | Notebook    | [bfb12f37c8](https://linux-hardware.org/?probe=bfb12f37c8) | Jul 25, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [925ddff018](https://linux-hardware.org/?probe=925ddff018) | Jul 25, 2021 |
| Dell          | Inspiron 5558               | Notebook    | [1cbc95eb56](https://linux-hardware.org/?probe=1cbc95eb56) | Jul 25, 2021 |
| Samsung       | 305V4A/305V5A/3415VA        | Notebook    | [95937e3a67](https://linux-hardware.org/?probe=95937e3a67) | Jul 25, 2021 |
| Acer          | Aspire V5-122P              | Notebook    | [5025f05f95](https://linux-hardware.org/?probe=5025f05f95) | Jul 25, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [7ebac3504c](https://linux-hardware.org/?probe=7ebac3504c) | Jul 25, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [f2f6ae3a0d](https://linux-hardware.org/?probe=f2f6ae3a0d) | Jul 24, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [fef67a0fc3](https://linux-hardware.org/?probe=fef67a0fc3) | Jul 24, 2021 |
| HP            | 250 G1                      | Notebook    | [61d592b754](https://linux-hardware.org/?probe=61d592b754) | Jul 24, 2021 |
| Dell          | Inspiron 5406 2n1           | Convertible | [9f6fa077ca](https://linux-hardware.org/?probe=9f6fa077ca) | Jul 24, 2021 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [b26e588a14](https://linux-hardware.org/?probe=b26e588a14) | Jul 24, 2021 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [f2c2beb7da](https://linux-hardware.org/?probe=f2c2beb7da) | Jul 24, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [4c1fea7f03](https://linux-hardware.org/?probe=4c1fea7f03) | Jul 23, 2021 |
| FUJITSU CL... | LIFEBOOK U7411              | Notebook    | [ad8fb39682](https://linux-hardware.org/?probe=ad8fb39682) | Jul 23, 2021 |
| Timi          | TM1701                      | Notebook    | [2d44d6cccb](https://linux-hardware.org/?probe=2d44d6cccb) | Jul 23, 2021 |
| HP            | EliteBook x360 1020 G2      | Convertible | [bf9a3d1a33](https://linux-hardware.org/?probe=bf9a3d1a33) | Jul 23, 2021 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [00614fd705](https://linux-hardware.org/?probe=00614fd705) | Jul 23, 2021 |
| Unknown       | Unknown                     | Desktop     | [0bf537187a](https://linux-hardware.org/?probe=0bf537187a) | Jul 23, 2021 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [37924533d9](https://linux-hardware.org/?probe=37924533d9) | Jul 23, 2021 |
| Unknown       | Unknown                     | Desktop     | [8681aef84a](https://linux-hardware.org/?probe=8681aef84a) | Jul 23, 2021 |
| Dell          | Vostro 15-3568              | Notebook    | [94aa730eda](https://linux-hardware.org/?probe=94aa730eda) | Jul 23, 2021 |
| Fujitsu       | LIFEBOOK T5010              | Notebook    | [1da124bb23](https://linux-hardware.org/?probe=1da124bb23) | Jul 23, 2021 |
| Lenovo        | Yoga 510-15ISK 80S8         | Convertible | [9a0dbf2630](https://linux-hardware.org/?probe=9a0dbf2630) | Jul 23, 2021 |
| Lenovo        | Yoga Slim 7 15IIL05 82AA    | Notebook    | [5ca74a5c0a](https://linux-hardware.org/?probe=5ca74a5c0a) | Jul 22, 2021 |
| Acer          | WG43M                       | Desktop     | [9efd66b779](https://linux-hardware.org/?probe=9efd66b779) | Jul 22, 2021 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | Notebook    | [ed51414a9d](https://linux-hardware.org/?probe=ed51414a9d) | Jul 22, 2021 |
| Positivo      | C41TB                       | Notebook    | [fa578942bc](https://linux-hardware.org/?probe=fa578942bc) | Jul 22, 2021 |
| Acer          | Aspire V5-122P              | Notebook    | [b788dcfcdb](https://linux-hardware.org/?probe=b788dcfcdb) | Jul 22, 2021 |
| Acer          | Aspire V5-122P              | Notebook    | [76203cb8e7](https://linux-hardware.org/?probe=76203cb8e7) | Jul 22, 2021 |
| Lenovo        | ThinkPad X220 4289A92       | Notebook    | [c985a9874f](https://linux-hardware.org/?probe=c985a9874f) | Jul 22, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3006193ccc](https://linux-hardware.org/?probe=3006193ccc) | Jul 22, 2021 |
| Dell          | 0W0CHX A01                  | Desktop     | [d4f3e21abc](https://linux-hardware.org/?probe=d4f3e21abc) | Jul 22, 2021 |
| Fujitsu       | D2991-A1 S26361-D2991-A1    | Desktop     | [0b87f80aa9](https://linux-hardware.org/?probe=0b87f80aa9) | Jul 22, 2021 |
| Fujitsu       | D2991-A1 S26361-D2991-A1    | Desktop     | [114ecaea11](https://linux-hardware.org/?probe=114ecaea11) | Jul 22, 2021 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [831024faec](https://linux-hardware.org/?probe=831024faec) | Jul 22, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [47b95dd012](https://linux-hardware.org/?probe=47b95dd012) | Jul 21, 2021 |
| Intel         | H81                         | Desktop     | [166b35fa7f](https://linux-hardware.org/?probe=166b35fa7f) | Jul 21, 2021 |
| Dell          | Inspiron 7572               | Notebook    | [0b2a96b6d7](https://linux-hardware.org/?probe=0b2a96b6d7) | Jul 21, 2021 |
| ASRock        | 980DE3/U3S3                 | Desktop     | [437aef57fd](https://linux-hardware.org/?probe=437aef57fd) | Jul 21, 2021 |
| ASRock        | 980DE3/U3S3                 | Desktop     | [9ca97016e0](https://linux-hardware.org/?probe=9ca97016e0) | Jul 21, 2021 |
| Google        | Kindred                     | Notebook    | [19b81352aa](https://linux-hardware.org/?probe=19b81352aa) | Jul 21, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [6ba7627daa](https://linux-hardware.org/?probe=6ba7627daa) | Jul 21, 2021 |
| Gigabyte      | G41M-Combo                  | Desktop     | [785c30284d](https://linux-hardware.org/?probe=785c30284d) | Jul 21, 2021 |
| Fujitsu       | D2991-A1 S26361-D2991-A1    | Desktop     | [4dd5b903b6](https://linux-hardware.org/?probe=4dd5b903b6) | Jul 21, 2021 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | Notebook    | [977c0df343](https://linux-hardware.org/?probe=977c0df343) | Jul 21, 2021 |
| HP            | 83E1                        | Desktop     | [977631dbb5](https://linux-hardware.org/?probe=977631dbb5) | Jul 20, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [bddfad8365](https://linux-hardware.org/?probe=bddfad8365) | Jul 20, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [2dcaee58ab](https://linux-hardware.org/?probe=2dcaee58ab) | Jul 20, 2021 |
| Lenovo        | ThinkPad L580 20LXS4K600    | Notebook    | [fc8ad7a780](https://linux-hardware.org/?probe=fc8ad7a780) | Jul 20, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [87370c4ac2](https://linux-hardware.org/?probe=87370c4ac2) | Jul 20, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b5194fe4e7](https://linux-hardware.org/?probe=b5194fe4e7) | Jul 20, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [ebed27d481](https://linux-hardware.org/?probe=ebed27d481) | Jul 20, 2021 |
| Gigabyte      | H61N-USB3                   | Desktop     | [54677110b4](https://linux-hardware.org/?probe=54677110b4) | Jul 20, 2021 |
| Acer          | Aspire E5-573G              | Notebook    | [d0d9ea99c9](https://linux-hardware.org/?probe=d0d9ea99c9) | Jul 20, 2021 |
| HP            | Laptop 15-bw0xx             | Notebook    | [c8821b395f](https://linux-hardware.org/?probe=c8821b395f) | Jul 19, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [33cd8cd38a](https://linux-hardware.org/?probe=33cd8cd38a) | Jul 19, 2021 |
| ASUSTek       | P8B75-M                     | Desktop     | [ce3ef21b15](https://linux-hardware.org/?probe=ce3ef21b15) | Jul 19, 2021 |
| ASUSTek       | P8B75-M                     | Desktop     | [70e6e81263](https://linux-hardware.org/?probe=70e6e81263) | Jul 19, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [3e9218d801](https://linux-hardware.org/?probe=3e9218d801) | Jul 19, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [23e7b76362](https://linux-hardware.org/?probe=23e7b76362) | Jul 19, 2021 |
| ASUSTek       | P5LD2                       | Desktop     | [9e97498649](https://linux-hardware.org/?probe=9e97498649) | Jul 19, 2021 |
| Lenovo        | IdeaPad S540-15IWL          | Notebook    | [8cee50ac90](https://linux-hardware.org/?probe=8cee50ac90) | Jul 19, 2021 |
| MSI           | Z390-A PRO                  | Desktop     | [811ff5b5d4](https://linux-hardware.org/?probe=811ff5b5d4) | Jul 19, 2021 |
| Dell          | Precision 5510              | Notebook    | [62987d66d1](https://linux-hardware.org/?probe=62987d66d1) | Jul 18, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [e1d4b0e45d](https://linux-hardware.org/?probe=e1d4b0e45d) | Jul 18, 2021 |
| Lenovo        | ThinkPad L580 20LWZ3SMUS    | Notebook    | [0ec8152ed0](https://linux-hardware.org/?probe=0ec8152ed0) | Jul 18, 2021 |
| Gigabyte      | G41M-Combo                  | Desktop     | [5f182f7f80](https://linux-hardware.org/?probe=5f182f7f80) | Jul 18, 2021 |
| HP            | 3646h                       | Desktop     | [b4dd06e5ce](https://linux-hardware.org/?probe=b4dd06e5ce) | Jul 18, 2021 |
| Unknown       | Unknown                     | Notebook    | [944b172397](https://linux-hardware.org/?probe=944b172397) | Jul 18, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [140d166cbb](https://linux-hardware.org/?probe=140d166cbb) | Jul 18, 2021 |
| Dell          | Vostro 3300                 | Notebook    | [67e30e41e8](https://linux-hardware.org/?probe=67e30e41e8) | Jul 17, 2021 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [d51165f3df](https://linux-hardware.org/?probe=d51165f3df) | Jul 17, 2021 |
| Notebook      | L14xMU                      | Notebook    | [90d627350d](https://linux-hardware.org/?probe=90d627350d) | Jul 17, 2021 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [b747ae8605](https://linux-hardware.org/?probe=b747ae8605) | Jul 17, 2021 |
| Lenovo        | IdeaPad Flex 5 14ARE05 8... | Convertible | [f969140705](https://linux-hardware.org/?probe=f969140705) | Jul 17, 2021 |
| Sony          | VPCEB3PGX                   | Notebook    | [d979c2edc1](https://linux-hardware.org/?probe=d979c2edc1) | Jul 17, 2021 |
| Apple         | MacBookPro11,3              | Notebook    | [8384c9bc8b](https://linux-hardware.org/?probe=8384c9bc8b) | Jul 17, 2021 |
| Gigabyte      | M61PME-S2P                  | Desktop     | [02dc77286f](https://linux-hardware.org/?probe=02dc77286f) | Jul 17, 2021 |
| Purism        | Librem 15 v4                | Notebook    | [4d73479f35](https://linux-hardware.org/?probe=4d73479f35) | Jul 16, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [6f6f7c6f5b](https://linux-hardware.org/?probe=6f6f7c6f5b) | Jul 16, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [02c451c80b](https://linux-hardware.org/?probe=02c451c80b) | Jul 16, 2021 |
| Biostar       | X370GTN                     | Desktop     | [22114c765e](https://linux-hardware.org/?probe=22114c765e) | Jul 16, 2021 |
| Unknown       | Unknown                     | Notebook    | [1d1680d9c3](https://linux-hardware.org/?probe=1d1680d9c3) | Jul 16, 2021 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [0f518d6dd3](https://linux-hardware.org/?probe=0f518d6dd3) | Jul 16, 2021 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [3b38895b98](https://linux-hardware.org/?probe=3b38895b98) | Jul 16, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [15a186d484](https://linux-hardware.org/?probe=15a186d484) | Jul 16, 2021 |
| Toshiba       | Satellite L750              | Notebook    | [29781e432b](https://linux-hardware.org/?probe=29781e432b) | Jul 16, 2021 |
| MSI           | Modern 14 A10M              | Notebook    | [3ccfcf4bc7](https://linux-hardware.org/?probe=3ccfcf4bc7) | Jul 16, 2021 |
| Positivo      | CHT12CP                     | Notebook    | [f339240754](https://linux-hardware.org/?probe=f339240754) | Jul 15, 2021 |
| Gigabyte      | B560M AORUS PRO AX          | Desktop     | [38067d7d6d](https://linux-hardware.org/?probe=38067d7d6d) | Jul 15, 2021 |
| Medion        | E15301                      | Notebook    | [20b60d58c9](https://linux-hardware.org/?probe=20b60d58c9) | Jul 15, 2021 |
| HP            | 8056                        | Desktop     | [bff5c3bb8d](https://linux-hardware.org/?probe=bff5c3bb8d) | Jul 15, 2021 |
| ASRock        | 990FX Extreme3              | Desktop     | [0621ec449f](https://linux-hardware.org/?probe=0621ec449f) | Jul 15, 2021 |
| HP            | ZBook 17 G5                 | Notebook    | [5292f36e16](https://linux-hardware.org/?probe=5292f36e16) | Jul 15, 2021 |
| HP            | ZBook 17 G5                 | Notebook    | [3367527048](https://linux-hardware.org/?probe=3367527048) | Jul 15, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [aec09069ed](https://linux-hardware.org/?probe=aec09069ed) | Jul 15, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [23ba122f57](https://linux-hardware.org/?probe=23ba122f57) | Jul 15, 2021 |
| Toshiba       | Satellite P50-C             | Notebook    | [3b8ead252b](https://linux-hardware.org/?probe=3b8ead252b) | Jul 15, 2021 |
| Lenovo        | IdeaPad 15ARE05 81YQ        | Notebook    | [9edec18576](https://linux-hardware.org/?probe=9edec18576) | Jul 15, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [433f44e117](https://linux-hardware.org/?probe=433f44e117) | Jul 14, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [24a13881c1](https://linux-hardware.org/?probe=24a13881c1) | Jul 14, 2021 |
| Lenovo        | ThinkPad 25 20K70004US      | Notebook    | [444232e659](https://linux-hardware.org/?probe=444232e659) | Jul 14, 2021 |
| HP            | ProBook 470 G0              | Notebook    | [0ac8121d51](https://linux-hardware.org/?probe=0ac8121d51) | Jul 14, 2021 |
| Acer          | Aspire E5-573G              | Notebook    | [8294dc2b59](https://linux-hardware.org/?probe=8294dc2b59) | Jul 14, 2021 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | Notebook    | [bad5668fb0](https://linux-hardware.org/?probe=bad5668fb0) | Jul 13, 2021 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [70128f07ea](https://linux-hardware.org/?probe=70128f07ea) | Jul 13, 2021 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [663c98e1f6](https://linux-hardware.org/?probe=663c98e1f6) | Jul 13, 2021 |
| Razer         | Blade 15 Mid 2019-Base      | Notebook    | [197a44190e](https://linux-hardware.org/?probe=197a44190e) | Jul 13, 2021 |
| HP            | 872B                        | Desktop     | [319ce0e306](https://linux-hardware.org/?probe=319ce0e306) | Jul 13, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [c7fad2195c](https://linux-hardware.org/?probe=c7fad2195c) | Jul 13, 2021 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [c632e51628](https://linux-hardware.org/?probe=c632e51628) | Jul 13, 2021 |
| FUJITSU CL... | LIFEBOOK U7411              | Notebook    | [9d1dfce344](https://linux-hardware.org/?probe=9d1dfce344) | Jul 13, 2021 |
| ASRock        | A320M-HD                    | Desktop     | [d3700506ef](https://linux-hardware.org/?probe=d3700506ef) | Jul 13, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [cb44035a70](https://linux-hardware.org/?probe=cb44035a70) | Jul 13, 2021 |
| Dell          | G7 7588                     | Notebook    | [899a0f9ae0](https://linux-hardware.org/?probe=899a0f9ae0) | Jul 12, 2021 |
| Lenovo        | ThinkPad T460s 20FAS0W90... | Notebook    | [d6812debb6](https://linux-hardware.org/?probe=d6812debb6) | Jul 12, 2021 |
| SYWZ          | S200 Series                 | Desktop     | [842ae5d4a3](https://linux-hardware.org/?probe=842ae5d4a3) | Jul 12, 2021 |
| Dell          | Latitude 3570               | Notebook    | [de199e258b](https://linux-hardware.org/?probe=de199e258b) | Jul 12, 2021 |
| Lenovo        | ThinkPad T460s 20FAS0W90... | Notebook    | [e3d1b2dd96](https://linux-hardware.org/?probe=e3d1b2dd96) | Jul 12, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [8f5ed33e46](https://linux-hardware.org/?probe=8f5ed33e46) | Jul 12, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | Desktop     | [6f04de798d](https://linux-hardware.org/?probe=6f04de798d) | Jul 12, 2021 |
| HP            | ProBook 470 G5              | Notebook    | [3bca640897](https://linux-hardware.org/?probe=3bca640897) | Jul 12, 2021 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [1fdcb33dcd](https://linux-hardware.org/?probe=1fdcb33dcd) | Jul 12, 2021 |
| Dell          | 0C2KJT A00                  | Desktop     | [891d514a94](https://linux-hardware.org/?probe=891d514a94) | Jul 12, 2021 |
| Linx          | VISION004                   | Notebook    | [52bb79b8a7](https://linux-hardware.org/?probe=52bb79b8a7) | Jul 12, 2021 |
| Lenovo        | ThinkPad L560 20F10029MC    | Notebook    | [a96e4cc1a5](https://linux-hardware.org/?probe=a96e4cc1a5) | Jul 12, 2021 |
| Lenovo        | ThinkPad P70 20ER0035MH     | Notebook    | [3b7269dbb9](https://linux-hardware.org/?probe=3b7269dbb9) | Jul 12, 2021 |
| MSI           | GF65 Thin 10UE              | Notebook    | [cfd00f1018](https://linux-hardware.org/?probe=cfd00f1018) | Jul 12, 2021 |
| Intel Clie... | LAPBC710                    | Notebook    | [49a2ccdeee](https://linux-hardware.org/?probe=49a2ccdeee) | Jul 12, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | Notebook    | [96f87991b2](https://linux-hardware.org/?probe=96f87991b2) | Jul 12, 2021 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [3427802385](https://linux-hardware.org/?probe=3427802385) | Jul 12, 2021 |
| EVGA          | 111-KS-E272                 | Desktop     | [a97173038d](https://linux-hardware.org/?probe=a97173038d) | Jul 12, 2021 |
| Dell          | XPS 17 9700                 | Notebook    | [592276c98f](https://linux-hardware.org/?probe=592276c98f) | Jul 12, 2021 |
| Acer          | Swift SF515-51T             | Notebook    | [f5ec156890](https://linux-hardware.org/?probe=f5ec156890) | Jul 12, 2021 |
| Dell          | XPS 15 9575                 | Convertible | [9694d7fb43](https://linux-hardware.org/?probe=9694d7fb43) | Jul 12, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | Notebook    | [cd32be6d20](https://linux-hardware.org/?probe=cd32be6d20) | Jul 12, 2021 |
| HP            | EliteBook 840 G6            | Notebook    | [14595ee84e](https://linux-hardware.org/?probe=14595ee84e) | Jul 12, 2021 |
| HP            | EliteBook 840 G6            | Notebook    | [c73776222b](https://linux-hardware.org/?probe=c73776222b) | Jul 11, 2021 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [16799202de](https://linux-hardware.org/?probe=16799202de) | Jul 11, 2021 |
| Lenovo        | IdeaPad S540-15IWL          | Notebook    | [4056165c35](https://linux-hardware.org/?probe=4056165c35) | Jul 11, 2021 |
| Lenovo        | ThinkPad W540 20BHS04B00    | Notebook    | [7601025893](https://linux-hardware.org/?probe=7601025893) | Jul 11, 2021 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [d1c166c13e](https://linux-hardware.org/?probe=d1c166c13e) | Jul 11, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [cdc4222058](https://linux-hardware.org/?probe=cdc4222058) | Jul 11, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [c046880bd3](https://linux-hardware.org/?probe=c046880bd3) | Jul 11, 2021 |
| PC Special... | N85_N87,HJ,HJ1,HK1          | Notebook    | [515b7e11d1](https://linux-hardware.org/?probe=515b7e11d1) | Jul 11, 2021 |
| HASEE Comp... | Computer                    | Notebook    | [641cab4c92](https://linux-hardware.org/?probe=641cab4c92) | Jul 11, 2021 |
| ASUSTek       | X556UR                      | Notebook    | [477a92a37e](https://linux-hardware.org/?probe=477a92a37e) | Jul 11, 2021 |
| Dell          | Latitude E6420              | Notebook    | [fe42f53d85](https://linux-hardware.org/?probe=fe42f53d85) | Jul 11, 2021 |
| Dell          | 0DF42J A00                  | Desktop     | [8a76db0ada](https://linux-hardware.org/?probe=8a76db0ada) | Jul 11, 2021 |
| ASUSTek       | EX-B250-V7                  | Desktop     | [32e09fdf66](https://linux-hardware.org/?probe=32e09fdf66) | Jul 11, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [61ea8363bc](https://linux-hardware.org/?probe=61ea8363bc) | Jul 10, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [223f91e471](https://linux-hardware.org/?probe=223f91e471) | Jul 10, 2021 |
| Timi          | TM1604                      | Notebook    | [496798e57c](https://linux-hardware.org/?probe=496798e57c) | Jul 10, 2021 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [3c18064125](https://linux-hardware.org/?probe=3c18064125) | Jul 10, 2021 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [8cdf123315](https://linux-hardware.org/?probe=8cdf123315) | Jul 10, 2021 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [731361283a](https://linux-hardware.org/?probe=731361283a) | Jul 10, 2021 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [b411603809](https://linux-hardware.org/?probe=b411603809) | Jul 10, 2021 |
| Gigabyte      | G41MT-D3                    | Desktop     | [9a275b8307](https://linux-hardware.org/?probe=9a275b8307) | Jul 10, 2021 |
| Apple         | MacBookPro11,3              | Notebook    | [0394bf80be](https://linux-hardware.org/?probe=0394bf80be) | Jul 10, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [89ed1de959](https://linux-hardware.org/?probe=89ed1de959) | Jul 10, 2021 |
| Dell          | 0VRWRC A00                  | Desktop     | [3ec458e478](https://linux-hardware.org/?probe=3ec458e478) | Jul 10, 2021 |
| Lenovo        | ThinkPad T490 20N3S94A00    | Notebook    | [2c4c458feb](https://linux-hardware.org/?probe=2c4c458feb) | Jul 10, 2021 |
| Gigabyte      | P31-ES3G                    | Desktop     | [09ec64fc0d](https://linux-hardware.org/?probe=09ec64fc0d) | Jul 10, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [f008db5308](https://linux-hardware.org/?probe=f008db5308) | Jul 10, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [e1049532a5](https://linux-hardware.org/?probe=e1049532a5) | Jul 09, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [b059e3bcea](https://linux-hardware.org/?probe=b059e3bcea) | Jul 09, 2021 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | Notebook    | [b4240819e1](https://linux-hardware.org/?probe=b4240819e1) | Jul 09, 2021 |
| HP            | ENVY TS m7                  | Notebook    | [6d939a6434](https://linux-hardware.org/?probe=6d939a6434) | Jul 09, 2021 |
| Dell          | Latitude E6530              | Notebook    | [7df496ffb5](https://linux-hardware.org/?probe=7df496ffb5) | Jul 09, 2021 |
| Dell          | Latitude 7420               | Notebook    | [ebf2372c3b](https://linux-hardware.org/?probe=ebf2372c3b) | Jul 09, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [4f880e87a0](https://linux-hardware.org/?probe=4f880e87a0) | Jul 09, 2021 |
| Lenovo        | ThinkPad T460s 20FAS0W90... | Notebook    | [b1ae6e7111](https://linux-hardware.org/?probe=b1ae6e7111) | Jul 09, 2021 |
| Acer          | One S1003                   | Tablet      | [5b88dd3887](https://linux-hardware.org/?probe=5b88dd3887) | Jul 09, 2021 |
| MSI           | MS-B1711                    | Desktop     | [ad46286aa7](https://linux-hardware.org/?probe=ad46286aa7) | Jul 09, 2021 |
| Dell          | Latitude D530               | Notebook    | [d48cd58890](https://linux-hardware.org/?probe=d48cd58890) | Jul 09, 2021 |
| HP            | 1497                        | Desktop     | [eecafd7c6c](https://linux-hardware.org/?probe=eecafd7c6c) | Jul 09, 2021 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [07e45f519d](https://linux-hardware.org/?probe=07e45f519d) | Jul 09, 2021 |
| ASUSTek       | X556UR                      | Notebook    | [4e555accb1](https://linux-hardware.org/?probe=4e555accb1) | Jul 08, 2021 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [413c28caa0](https://linux-hardware.org/?probe=413c28caa0) | Jul 08, 2021 |
| Dell          | Latitude E6540              | Notebook    | [1b488de7b9](https://linux-hardware.org/?probe=1b488de7b9) | Jul 08, 2021 |
| ASUSTek       | ASUS EXPERTBOOK P2451FB_... | Notebook    | [af389420e2](https://linux-hardware.org/?probe=af389420e2) | Jul 08, 2021 |
| Dell          | Precision M4600             | Notebook    | [388aad414f](https://linux-hardware.org/?probe=388aad414f) | Jul 08, 2021 |
| eMachines     | eME732                      | Notebook    | [50e1042533](https://linux-hardware.org/?probe=50e1042533) | Jul 08, 2021 |
| HP            | 8056                        | Desktop     | [c35a7e4e65](https://linux-hardware.org/?probe=c35a7e4e65) | Jul 08, 2021 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [785027f8f6](https://linux-hardware.org/?probe=785027f8f6) | Jul 08, 2021 |
| Lenovo        | ThinkPad T460s 20FAS0W90... | Notebook    | [bdcc6ae937](https://linux-hardware.org/?probe=bdcc6ae937) | Jul 08, 2021 |
| Lenovo        | ThinkPad X61 7676A12        | Notebook    | [3e43acf8af](https://linux-hardware.org/?probe=3e43acf8af) | Jul 08, 2021 |
| Lenovo        | ThinkPad T590 20N5S2NC1V    | Notebook    | [048e092d2f](https://linux-hardware.org/?probe=048e092d2f) | Jul 08, 2021 |
| Lenovo        | ThinkPad X61 7676A12        | Notebook    | [196e6c6ec4](https://linux-hardware.org/?probe=196e6c6ec4) | Jul 08, 2021 |
| Notebook      | NH55RGQ                     | Notebook    | [553b287a99](https://linux-hardware.org/?probe=553b287a99) | Jul 08, 2021 |
| ASRock        | X399 Phantom Gaming 6       | Desktop     | [d93e096489](https://linux-hardware.org/?probe=d93e096489) | Jul 08, 2021 |
| Fujitsu       | LIFEBOOK U747               | Notebook    | [68be809f45](https://linux-hardware.org/?probe=68be809f45) | Jul 08, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [ba806c9513](https://linux-hardware.org/?probe=ba806c9513) | Jul 08, 2021 |
| Lenovo        | ThinkPad L390 Yoga 20NT0... | Convertible | [bd0b0aa6ab](https://linux-hardware.org/?probe=bd0b0aa6ab) | Jul 08, 2021 |
| Unknown       | DH61BR G32662-203           | Desktop     | [9314761de4](https://linux-hardware.org/?probe=9314761de4) | Jul 08, 2021 |
| Unknown       | DH61BR G32662-203           | Desktop     | [c658575abc](https://linux-hardware.org/?probe=c658575abc) | Jul 08, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [0f7853a74f](https://linux-hardware.org/?probe=0f7853a74f) | Jul 08, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | Desktop     | [f0474e6193](https://linux-hardware.org/?probe=f0474e6193) | Jul 08, 2021 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [25fdba4c4f](https://linux-hardware.org/?probe=25fdba4c4f) | Jul 08, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [47e2b55bb5](https://linux-hardware.org/?probe=47e2b55bb5) | Jul 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [c325080602](https://linux-hardware.org/?probe=c325080602) | Jul 07, 2021 |
| HP            | 8056                        | Desktop     | [f40b845088](https://linux-hardware.org/?probe=f40b845088) | Jul 07, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [cc542d5a92](https://linux-hardware.org/?probe=cc542d5a92) | Jul 07, 2021 |
| Dell          | Vostro 3460                 | Notebook    | [d24bfb0cba](https://linux-hardware.org/?probe=d24bfb0cba) | Jul 07, 2021 |
| HP            | Laptop 17-bs1xx             | Notebook    | [17baeef261](https://linux-hardware.org/?probe=17baeef261) | Jul 07, 2021 |
| Acer          | Aspire E5-574               | Notebook    | [72aa4529ca](https://linux-hardware.org/?probe=72aa4529ca) | Jul 07, 2021 |
| Acer          | Aspire E5-574               | Notebook    | [8360c2bcdc](https://linux-hardware.org/?probe=8360c2bcdc) | Jul 07, 2021 |
| Dell          | Latitude D530               | Notebook    | [21ad721b61](https://linux-hardware.org/?probe=21ad721b61) | Jul 07, 2021 |
| Dell          | Inspiron 5770               | Notebook    | [48d7ad6341](https://linux-hardware.org/?probe=48d7ad6341) | Jul 07, 2021 |
| Lenovo        | ThinkPad X250 20CLS4NUSA    | Notebook    | [2f6b8a2bd6](https://linux-hardware.org/?probe=2f6b8a2bd6) | Jul 07, 2021 |
| Lenovo        | ThinkPad X250 20CLS4NUSA    | Notebook    | [c36dd3d8e6](https://linux-hardware.org/?probe=c36dd3d8e6) | Jul 07, 2021 |
| HP            | ENVY Laptop 15-ep0xxx       | Notebook    | [ec0db39d7a](https://linux-hardware.org/?probe=ec0db39d7a) | Jul 07, 2021 |
| HP            | ENVY Laptop 15-ep0xxx       | Notebook    | [86fdf9dc69](https://linux-hardware.org/?probe=86fdf9dc69) | Jul 07, 2021 |
| Acer          | Aspire 5749                 | Notebook    | [7aa3ecf46d](https://linux-hardware.org/?probe=7aa3ecf46d) | Jul 07, 2021 |
| ASUSTek       | X99-A II                    | Desktop     | [d84c3b80a1](https://linux-hardware.org/?probe=d84c3b80a1) | Jul 07, 2021 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [0ae36379ae](https://linux-hardware.org/?probe=0ae36379ae) | Jul 07, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [a7ffc7e0dd](https://linux-hardware.org/?probe=a7ffc7e0dd) | Jul 07, 2021 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [e3ea65a467](https://linux-hardware.org/?probe=e3ea65a467) | Jul 07, 2021 |
| ASUSTek       | ASUS EXPERTBOOK P2451FB_... | Notebook    | [4831f1aed2](https://linux-hardware.org/?probe=4831f1aed2) | Jul 07, 2021 |
| Gigabyte      | H61N-USB3                   | Desktop     | [4533c4325a](https://linux-hardware.org/?probe=4533c4325a) | Jul 07, 2021 |
| ASUSTek       | X555LA                      | Notebook    | [8c44ea27c9](https://linux-hardware.org/?probe=8c44ea27c9) | Jul 06, 2021 |
| ASUSTek       | X555LA                      | Notebook    | [9974f7325e](https://linux-hardware.org/?probe=9974f7325e) | Jul 06, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [429e94317f](https://linux-hardware.org/?probe=429e94317f) | Jul 06, 2021 |
| Dell          | Inspiron 13-7378            | Notebook    | [2006f747eb](https://linux-hardware.org/?probe=2006f747eb) | Jul 06, 2021 |
| Dell          | 0PC5F7 A02                  | Desktop     | [ea43204b3b](https://linux-hardware.org/?probe=ea43204b3b) | Jul 06, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [04b8667d2e](https://linux-hardware.org/?probe=04b8667d2e) | Jul 06, 2021 |
| Gigabyte      | H61N-USB3                   | Desktop     | [936f2b1169](https://linux-hardware.org/?probe=936f2b1169) | Jul 06, 2021 |
| HP            | EliteBook 2540p             | Notebook    | [5c9b345041](https://linux-hardware.org/?probe=5c9b345041) | Jul 06, 2021 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | Notebook    | [47bac68af2](https://linux-hardware.org/?probe=47bac68af2) | Jul 06, 2021 |
| Lenovo        | ThinkPad E480 20KNS0E200    | Notebook    | [e031e80b6b](https://linux-hardware.org/?probe=e031e80b6b) | Jul 06, 2021 |
| Microsoft     | Surface Book 2              | Tablet      | [53ae472c1d](https://linux-hardware.org/?probe=53ae472c1d) | Jul 06, 2021 |
| ASRock        | AD2700-ITX                  | Desktop     | [9b868b0c9b](https://linux-hardware.org/?probe=9b868b0c9b) | Jul 06, 2021 |
| Lenovo        | 3716 SDK0R32862 WIN 3258... | Desktop     | [5758df25ec](https://linux-hardware.org/?probe=5758df25ec) | Jul 06, 2021 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [85ee7fa5f1](https://linux-hardware.org/?probe=85ee7fa5f1) | Jul 05, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a44525ea2d](https://linux-hardware.org/?probe=a44525ea2d) | Jul 05, 2021 |
| Gigabyte      | G41MT-D3                    | Desktop     | [faa3279fc6](https://linux-hardware.org/?probe=faa3279fc6) | Jul 05, 2021 |
| ASUSTek       | Z87-DELUXE                  | Desktop     | [3aa1e79866](https://linux-hardware.org/?probe=3aa1e79866) | Jul 05, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [70c0bc44a2](https://linux-hardware.org/?probe=70c0bc44a2) | Jul 05, 2021 |
| Apple         | MacBookPro11,2              | Notebook    | [f5c0f2dd2d](https://linux-hardware.org/?probe=f5c0f2dd2d) | Jul 05, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [6fdc284c1a](https://linux-hardware.org/?probe=6fdc284c1a) | Jul 05, 2021 |
| MSI           | B450M BAZOOKA V2            | Desktop     | [efe8014efa](https://linux-hardware.org/?probe=efe8014efa) | Jul 05, 2021 |
| Dell          | Inspiron 7306 2n1           | Convertible | [74a262254d](https://linux-hardware.org/?probe=74a262254d) | Jul 05, 2021 |
| Gigabyte      | H61N-USB3                   | Desktop     | [7fe084720d](https://linux-hardware.org/?probe=7fe084720d) | Jul 05, 2021 |
| Dell          | Inspiron 7306 2n1           | Convertible | [3779d55f6e](https://linux-hardware.org/?probe=3779d55f6e) | Jul 05, 2021 |
| Acer          | Swift SF314-52G             | Notebook    | [ad7dfb7bf6](https://linux-hardware.org/?probe=ad7dfb7bf6) | Jul 05, 2021 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | Notebook    | [3803784209](https://linux-hardware.org/?probe=3803784209) | Jul 05, 2021 |
| Dell          | G3 3579                     | Notebook    | [97c520db01](https://linux-hardware.org/?probe=97c520db01) | Jul 04, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [13f5ecaf06](https://linux-hardware.org/?probe=13f5ecaf06) | Jul 04, 2021 |
| Lenovo        | G50-30 80G0                 | Notebook    | [6f974e427e](https://linux-hardware.org/?probe=6f974e427e) | Jul 04, 2021 |
| Alienware     | 0N4R4N A00                  | Desktop     | [9219336156](https://linux-hardware.org/?probe=9219336156) | Jul 04, 2021 |
| Login Info... | LOG-QAL30                   | Notebook    | [3376c8f541](https://linux-hardware.org/?probe=3376c8f541) | Jul 04, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [be18b0347f](https://linux-hardware.org/?probe=be18b0347f) | Jul 04, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [9e7e50fd74](https://linux-hardware.org/?probe=9e7e50fd74) | Jul 04, 2021 |
| Gigabyte      | GA-990FXA-UD3               | Desktop     | [cb030b0e9f](https://linux-hardware.org/?probe=cb030b0e9f) | Jul 04, 2021 |
| Gigabyte      | H61N-USB3                   | Desktop     | [5b2d86e06f](https://linux-hardware.org/?probe=5b2d86e06f) | Jul 04, 2021 |
| HP            | ProBook 6465b               | Notebook    | [dd03f5f10c](https://linux-hardware.org/?probe=dd03f5f10c) | Jul 04, 2021 |
| HP            | ProBook 6465b               | Notebook    | [27a6794579](https://linux-hardware.org/?probe=27a6794579) | Jul 04, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [de1eb87e32](https://linux-hardware.org/?probe=de1eb87e32) | Jul 04, 2021 |
| HP            | 8056                        | Desktop     | [56f294962a](https://linux-hardware.org/?probe=56f294962a) | Jul 04, 2021 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [e25c41c312](https://linux-hardware.org/?probe=e25c41c312) | Jul 03, 2021 |
| Lenovo        | ThinkPad T460s 20FAS0W90... | Notebook    | [e684bf151e](https://linux-hardware.org/?probe=e684bf151e) | Jul 03, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [8dd431f915](https://linux-hardware.org/?probe=8dd431f915) | Jul 03, 2021 |
| MSI           | MS-B9321                    | Desktop     | [93243d00da](https://linux-hardware.org/?probe=93243d00da) | Jul 03, 2021 |
| Google        | Panther                     | Desktop     | [043feff8fe](https://linux-hardware.org/?probe=043feff8fe) | Jul 03, 2021 |
| ASRock        | J3160DC-ITX                 | Desktop     | [cfd320c331](https://linux-hardware.org/?probe=cfd320c331) | Jul 03, 2021 |
| Chuwi         | LarkBox Pro                 | Desktop     | [0b050f9b1d](https://linux-hardware.org/?probe=0b050f9b1d) | Jul 03, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [0e5e9b16b8](https://linux-hardware.org/?probe=0e5e9b16b8) | Jul 03, 2021 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [5aa1cef5bb](https://linux-hardware.org/?probe=5aa1cef5bb) | Jul 03, 2021 |
| MSI           | PRESTIGE X570 CREATION      | Desktop     | [f61ba12c20](https://linux-hardware.org/?probe=f61ba12c20) | Jul 03, 2021 |
| Apple         | MacBookPro11,5              | Notebook    | [713b8738d7](https://linux-hardware.org/?probe=713b8738d7) | Jul 03, 2021 |
| CompuLab      | Intense-PC                  | Mini pc     | [04d1fd85d9](https://linux-hardware.org/?probe=04d1fd85d9) | Jul 03, 2021 |
| CompuLab      | Intense-PC                  | Mini pc     | [2cfeeb8105](https://linux-hardware.org/?probe=2cfeeb8105) | Jul 03, 2021 |
| Lenovo        | 3716 SDK0R32862 WIN 3258... | Desktop     | [36c64a337b](https://linux-hardware.org/?probe=36c64a337b) | Jul 03, 2021 |
| MSI           | H110M PRO-VD                | Desktop     | [55cdedffc2](https://linux-hardware.org/?probe=55cdedffc2) | Jul 03, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS0... | Notebook    | [aa4b4e2c5e](https://linux-hardware.org/?probe=aa4b4e2c5e) | Jul 03, 2021 |
| HP            | Pavilion x2 Detachable P... | Notebook    | [d917cdea53](https://linux-hardware.org/?probe=d917cdea53) | Jul 02, 2021 |
| HP            | EliteBook x360 1030 G2      | Convertible | [9282890b2e](https://linux-hardware.org/?probe=9282890b2e) | Jul 02, 2021 |
| HP            | ENVY TS m7                  | Notebook    | [e4c275224b](https://linux-hardware.org/?probe=e4c275224b) | Jul 02, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [8f0d98b462](https://linux-hardware.org/?probe=8f0d98b462) | Jul 02, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | Desktop     | [f3ef9d51b3](https://linux-hardware.org/?probe=f3ef9d51b3) | Jul 02, 2021 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [f29842baff](https://linux-hardware.org/?probe=f29842baff) | Jul 02, 2021 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [2c9eb028c4](https://linux-hardware.org/?probe=2c9eb028c4) | Jul 02, 2021 |
| MSI           | MS-B1711                    | Desktop     | [21ec3e7523](https://linux-hardware.org/?probe=21ec3e7523) | Jul 02, 2021 |
| Lenovo        | 30BB SDK0J40705 WIN 3425... | All in one  | [27cd95557e](https://linux-hardware.org/?probe=27cd95557e) | Jul 02, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [51e1bb06dd](https://linux-hardware.org/?probe=51e1bb06dd) | Jul 02, 2021 |
| Lenovo        | ThinkPad X220 42914CG       | Notebook    | [4f886f5775](https://linux-hardware.org/?probe=4f886f5775) | Jul 02, 2021 |
| Unknown       | Unknown                     | Notebook    | [99c56b3bda](https://linux-hardware.org/?probe=99c56b3bda) | Jul 01, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [cca3e863f7](https://linux-hardware.org/?probe=cca3e863f7) | Jul 01, 2021 |
| AMD           | A320IPC VER:1.00            | Desktop     | [f165ce8a70](https://linux-hardware.org/?probe=f165ce8a70) | Jul 01, 2021 |
| Acer          | Aspire 5250                 | Notebook    | [4a9dcc3234](https://linux-hardware.org/?probe=4a9dcc3234) | Jul 01, 2021 |
| Dell          | XPS 13 9343                 | Notebook    | [04e26d7f9d](https://linux-hardware.org/?probe=04e26d7f9d) | Jul 01, 2021 |
| Acer          | Aspire A515-51              | Notebook    | [6ee9cba880](https://linux-hardware.org/?probe=6ee9cba880) | Jul 01, 2021 |
| Acer          | Aspire A515-51              | Notebook    | [c2eb051f8c](https://linux-hardware.org/?probe=c2eb051f8c) | Jul 01, 2021 |
| HP            | 8056                        | Desktop     | [d10cd539f1](https://linux-hardware.org/?probe=d10cd539f1) | Jul 01, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [6b924d8505](https://linux-hardware.org/?probe=6b924d8505) | Jul 01, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [48bef18c1a](https://linux-hardware.org/?probe=48bef18c1a) | Jul 01, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [544a5040ad](https://linux-hardware.org/?probe=544a5040ad) | Jul 01, 2021 |
| Gigabyte      | G41MT-D3                    | Desktop     | [ed64b27c12](https://linux-hardware.org/?probe=ed64b27c12) | Jul 01, 2021 |
| Lenovo        | Yoga 920-13IKB 80Y7         | Convertible | [e2c078e281](https://linux-hardware.org/?probe=e2c078e281) | Jul 01, 2021 |
| Apple         | MacBookPro11,5              | Notebook    | [43d77edd56](https://linux-hardware.org/?probe=43d77edd56) | Jul 01, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [2caf3e1dd5](https://linux-hardware.org/?probe=2caf3e1dd5) | Jun 30, 2021 |
| Apple         | MacBookPro11,5              | Notebook    | [103c0edcbd](https://linux-hardware.org/?probe=103c0edcbd) | Jun 30, 2021 |
| Gigabyte      | H61N-USB3                   | Desktop     | [d6bf3eece4](https://linux-hardware.org/?probe=d6bf3eece4) | Jun 30, 2021 |
| Apple         | MacBookPro5,1               | Notebook    | [47dfbc7a00](https://linux-hardware.org/?probe=47dfbc7a00) | Jun 30, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [a37dd487ac](https://linux-hardware.org/?probe=a37dd487ac) | Jun 30, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [d85a7c67f9](https://linux-hardware.org/?probe=d85a7c67f9) | Jun 30, 2021 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [132edccbe5](https://linux-hardware.org/?probe=132edccbe5) | Jun 30, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [e6cda3b64b](https://linux-hardware.org/?probe=e6cda3b64b) | Jun 30, 2021 |
| Dell          | 08NPPY A00                  | Desktop     | [28dd0487c3](https://linux-hardware.org/?probe=28dd0487c3) | Jun 30, 2021 |
| ASRock        | A320M-HD                    | Desktop     | [ce332204a6](https://linux-hardware.org/?probe=ce332204a6) | Jun 30, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [891b06178e](https://linux-hardware.org/?probe=891b06178e) | Jun 29, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [f38fd14520](https://linux-hardware.org/?probe=f38fd14520) | Jun 29, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [a8268a0c9d](https://linux-hardware.org/?probe=a8268a0c9d) | Jun 29, 2021 |
| Dell          | Latitude E6320              | Notebook    | [dd93a97faf](https://linux-hardware.org/?probe=dd93a97faf) | Jun 29, 2021 |
| Lenovo        | Board                       | Desktop     | [1e1ba598d3](https://linux-hardware.org/?probe=1e1ba598d3) | Jun 29, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [1185271556](https://linux-hardware.org/?probe=1185271556) | Jun 29, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [0369ff2b06](https://linux-hardware.org/?probe=0369ff2b06) | Jun 29, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [353a5052a1](https://linux-hardware.org/?probe=353a5052a1) | Jun 29, 2021 |
| Dell          | G7 7588                     | Notebook    | [c053b00ac1](https://linux-hardware.org/?probe=c053b00ac1) | Jun 29, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [6820c53176](https://linux-hardware.org/?probe=6820c53176) | Jun 29, 2021 |
| eMachines     | eME732                      | Notebook    | [81bbc7fe0f](https://linux-hardware.org/?probe=81bbc7fe0f) | Jun 29, 2021 |
| eMachines     | eME732                      | Notebook    | [1f334d1a64](https://linux-hardware.org/?probe=1f334d1a64) | Jun 29, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X51... | Notebook    | [67e302d5d5](https://linux-hardware.org/?probe=67e302d5d5) | Jun 29, 2021 |
| Dell          | 06D7TR A00                  | Desktop     | [52e029b58e](https://linux-hardware.org/?probe=52e029b58e) | Jun 28, 2021 |
| Acer          | One S1003                   | Tablet      | [db5be6c431](https://linux-hardware.org/?probe=db5be6c431) | Jun 28, 2021 |
| SYWZ          | S200 Series                 | Desktop     | [a848b9e433](https://linux-hardware.org/?probe=a848b9e433) | Jun 28, 2021 |
| Dell          | Vostro 5590                 | Notebook    | [1cc0df9bfd](https://linux-hardware.org/?probe=1cc0df9bfd) | Jun 28, 2021 |
| Dell          | Vostro 5590                 | Notebook    | [0caade1304](https://linux-hardware.org/?probe=0caade1304) | Jun 28, 2021 |
| Lenovo        | ThinkPad T430 2349V4B       | Notebook    | [d6ef1b054b](https://linux-hardware.org/?probe=d6ef1b054b) | Jun 28, 2021 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [3ef8e128d8](https://linux-hardware.org/?probe=3ef8e128d8) | Jun 27, 2021 |
| Acer          | Nitro AN515-52              | Notebook    | [ea190d7d5b](https://linux-hardware.org/?probe=ea190d7d5b) | Jun 27, 2021 |
| Lenovo        | ThinkPad W530 2447AC4       | Notebook    | [42a4d32f82](https://linux-hardware.org/?probe=42a4d32f82) | Jun 27, 2021 |
| Lenovo        | ThinkPad T460p 20FXS1SX0... | Notebook    | [09705e74ac](https://linux-hardware.org/?probe=09705e74ac) | Jun 27, 2021 |
| Positivo      | POS-MI945AA                 | Desktop     | [fd4be0982e](https://linux-hardware.org/?probe=fd4be0982e) | Jun 27, 2021 |
| ASUSTek       | P8H61-M LE/CSM              | Desktop     | [a6b799f108](https://linux-hardware.org/?probe=a6b799f108) | Jun 27, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [62c1b02c31](https://linux-hardware.org/?probe=62c1b02c31) | Jun 27, 2021 |
| Dell          | Latitude E6510              | Notebook    | [554b7b8739](https://linux-hardware.org/?probe=554b7b8739) | Jun 27, 2021 |
| HP            | 8436                        | Desktop     | [617d5e50fd](https://linux-hardware.org/?probe=617d5e50fd) | Jun 27, 2021 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [f479cb95d4](https://linux-hardware.org/?probe=f479cb95d4) | Jun 26, 2021 |
| HP            | Pro x2 612 G1 Tablet        | Notebook    | [4f8ff6b6a4](https://linux-hardware.org/?probe=4f8ff6b6a4) | Jun 26, 2021 |
| Dell          | 08NPPY A00                  | Desktop     | [3c33ace801](https://linux-hardware.org/?probe=3c33ace801) | Jun 26, 2021 |
| Positivo      | CHT14B                      | Notebook    | [4fd6be9b48](https://linux-hardware.org/?probe=4fd6be9b48) | Jun 26, 2021 |
| ASUSTek       | ROG STRIX X299-E GAMING ... | Desktop     | [c1e9364997](https://linux-hardware.org/?probe=c1e9364997) | Jun 26, 2021 |
| Lenovo        | Yoga S740-15IRH 81NX        | Convertible | [5c409fa78e](https://linux-hardware.org/?probe=5c409fa78e) | Jun 26, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [533712977b](https://linux-hardware.org/?probe=533712977b) | Jun 26, 2021 |
| Unknown       | NF-MCP78                    | Desktop     | [39a0c32be8](https://linux-hardware.org/?probe=39a0c32be8) | Jun 26, 2021 |
| HP            | Pavilion dv6                | Notebook    | [44c09f0096](https://linux-hardware.org/?probe=44c09f0096) | Jun 26, 2021 |
| Gigabyte      | G41MT-D3                    | Desktop     | [03a472ae41](https://linux-hardware.org/?probe=03a472ae41) | Jun 26, 2021 |
| ASUSTek       | X510URR                     | Notebook    | [980f6dda35](https://linux-hardware.org/?probe=980f6dda35) | Jun 25, 2021 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [2c4a16ea24](https://linux-hardware.org/?probe=2c4a16ea24) | Jun 25, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [68cd01f446](https://linux-hardware.org/?probe=68cd01f446) | Jun 25, 2021 |
| HP            | 8056                        | Desktop     | [3cce894f08](https://linux-hardware.org/?probe=3cce894f08) | Jun 25, 2021 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [95a80b91fd](https://linux-hardware.org/?probe=95a80b91fd) | Jun 25, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [a6c3875064](https://linux-hardware.org/?probe=a6c3875064) | Jun 25, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [3fabc021d6](https://linux-hardware.org/?probe=3fabc021d6) | Jun 25, 2021 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [02924c7c01](https://linux-hardware.org/?probe=02924c7c01) | Jun 25, 2021 |
| Acer          | Aspire E1-572P              | Notebook    | [b6b916afd7](https://linux-hardware.org/?probe=b6b916afd7) | Jun 25, 2021 |
| ASUSTek       | N551JX                      | Notebook    | [3ef394cafb](https://linux-hardware.org/?probe=3ef394cafb) | Jun 24, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [3b153ae2f9](https://linux-hardware.org/?probe=3b153ae2f9) | Jun 24, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [988fc9a599](https://linux-hardware.org/?probe=988fc9a599) | Jun 24, 2021 |
| Apple         | MacBookPro7,1               | Notebook    | [3853510dae](https://linux-hardware.org/?probe=3853510dae) | Jun 24, 2021 |
| HP            | EliteBook 745 G5            | Notebook    | [5b2fd462f9](https://linux-hardware.org/?probe=5b2fd462f9) | Jun 24, 2021 |
| HP            | OMEN by HP Laptop 15-dc1... | Notebook    | [0a87a16629](https://linux-hardware.org/?probe=0a87a16629) | Jun 24, 2021 |
| HP            | OMEN by HP Laptop 15-dc1... | Notebook    | [f08002593f](https://linux-hardware.org/?probe=f08002593f) | Jun 24, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [f008bcb38f](https://linux-hardware.org/?probe=f008bcb38f) | Jun 24, 2021 |
| MSI           | B350M MORTAR ARCTIC         | Desktop     | [7f19e67108](https://linux-hardware.org/?probe=7f19e67108) | Jun 24, 2021 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [f8a74fc57a](https://linux-hardware.org/?probe=f8a74fc57a) | Jun 24, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [febe8388b9](https://linux-hardware.org/?probe=febe8388b9) | Jun 24, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [b5d17f5b99](https://linux-hardware.org/?probe=b5d17f5b99) | Jun 24, 2021 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [3e700499c7](https://linux-hardware.org/?probe=3e700499c7) | Jun 24, 2021 |
| Lenovo        | ThinkPad W540 20BHS04T0K    | Notebook    | [7f9142fffb](https://linux-hardware.org/?probe=7f9142fffb) | Jun 24, 2021 |
| ASRock        | A320M-HD                    | Desktop     | [121770a05e](https://linux-hardware.org/?probe=121770a05e) | Jun 23, 2021 |
| ASUSTek       | N550JV                      | Notebook    | [1189ce0f29](https://linux-hardware.org/?probe=1189ce0f29) | Jun 23, 2021 |
| Acer          | Nitro AN515-52              | Notebook    | [63d7af3f6c](https://linux-hardware.org/?probe=63d7af3f6c) | Jun 23, 2021 |
| ASUSTek       | N550JV                      | Notebook    | [3d037467a7](https://linux-hardware.org/?probe=3d037467a7) | Jun 23, 2021 |
| MSI           | Z97 GAMING 5                | Desktop     | [8edc5f4d03](https://linux-hardware.org/?probe=8edc5f4d03) | Jun 23, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [2c6ef158c3](https://linux-hardware.org/?probe=2c6ef158c3) | Jun 23, 2021 |
| ASRock        | B550M Steel Legend          | Desktop     | [e1346ace5c](https://linux-hardware.org/?probe=e1346ace5c) | Jun 23, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [89e7443645](https://linux-hardware.org/?probe=89e7443645) | Jun 23, 2021 |
| ASUSTek       | TUF GAMING FX504GD_FX80G... | Notebook    | [9d80703f35](https://linux-hardware.org/?probe=9d80703f35) | Jun 23, 2021 |
| Apple         | MacBookPro7,1               | Notebook    | [458921c45b](https://linux-hardware.org/?probe=458921c45b) | Jun 23, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [e563be02ff](https://linux-hardware.org/?probe=e563be02ff) | Jun 23, 2021 |
| Lenovo        | ThinkPad T580 20LAS3NJ0B    | Notebook    | [3e8ac913f5](https://linux-hardware.org/?probe=3e8ac913f5) | Jun 23, 2021 |
| Gigabyte      | G41MT-D3                    | Desktop     | [c69a0b8125](https://linux-hardware.org/?probe=c69a0b8125) | Jun 23, 2021 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [6dc73fd38c](https://linux-hardware.org/?probe=6dc73fd38c) | Jun 23, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [b9d01c99ff](https://linux-hardware.org/?probe=b9d01c99ff) | Jun 23, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [30717e79a0](https://linux-hardware.org/?probe=30717e79a0) | Jun 22, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [7a6f9e9890](https://linux-hardware.org/?probe=7a6f9e9890) | Jun 22, 2021 |
| Acer          | Aspire 5742                 | Notebook    | [38f25268b8](https://linux-hardware.org/?probe=38f25268b8) | Jun 22, 2021 |
| ASRock        | H77 Pro4-M                  | Desktop     | [643c704c39](https://linux-hardware.org/?probe=643c704c39) | Jun 22, 2021 |
| Lenovo        | 3714 SDK0R32862 WIN 3258... | Desktop     | [b20ad5477a](https://linux-hardware.org/?probe=b20ad5477a) | Jun 22, 2021 |
| HP            | 198E                        | Desktop     | [b614ce2528](https://linux-hardware.org/?probe=b614ce2528) | Jun 22, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [9b71a93aed](https://linux-hardware.org/?probe=9b71a93aed) | Jun 22, 2021 |
| Lenovo        | ThinkPad E595 20NF001PTX    | Notebook    | [6dbda9f5d3](https://linux-hardware.org/?probe=6dbda9f5d3) | Jun 22, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [ca17e02509](https://linux-hardware.org/?probe=ca17e02509) | Jun 22, 2021 |
| Unknown       | NF-MCP78                    | Desktop     | [b9ad532089](https://linux-hardware.org/?probe=b9ad532089) | Jun 22, 2021 |
| Dell          | Inspiron M5010              | Notebook    | [1776eab993](https://linux-hardware.org/?probe=1776eab993) | Jun 22, 2021 |
| ASRock        | H97M Pro4                   | Desktop     | [b57edde05d](https://linux-hardware.org/?probe=b57edde05d) | Jun 22, 2021 |
| Acer          | Nitro AN515-42              | Notebook    | [3fbcc9554f](https://linux-hardware.org/?probe=3fbcc9554f) | Jun 22, 2021 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [fecaaeafe2](https://linux-hardware.org/?probe=fecaaeafe2) | Jun 22, 2021 |
| HP            | ENVY TS m7                  | Notebook    | [8d0a64c8c1](https://linux-hardware.org/?probe=8d0a64c8c1) | Jun 22, 2021 |
| ASUSTek       | X450LA                      | Notebook    | [243cc91799](https://linux-hardware.org/?probe=243cc91799) | Jun 22, 2021 |
| HP            | ProLiant DL380 G6           | Server      | [096d3e62fe](https://linux-hardware.org/?probe=096d3e62fe) | Jun 21, 2021 |
| HP            | ProLiant ML150 G5           | Desktop     | [dd931cb4e6](https://linux-hardware.org/?probe=dd931cb4e6) | Jun 21, 2021 |
| ASRock        | Z97 Extreme4                | Desktop     | [9974950d4a](https://linux-hardware.org/?probe=9974950d4a) | Jun 21, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [8513c961a4](https://linux-hardware.org/?probe=8513c961a4) | Jun 21, 2021 |
| Lenovo        | ThinkPad T410 2522PT3       | Notebook    | [4d638e6ba4](https://linux-hardware.org/?probe=4d638e6ba4) | Jun 21, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [4ac446c37b](https://linux-hardware.org/?probe=4ac446c37b) | Jun 21, 2021 |
| Lenovo        | ThinkPad T460s 20FAS0W90... | Notebook    | [d0164778ea](https://linux-hardware.org/?probe=d0164778ea) | Jun 21, 2021 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [0c1eb0be4f](https://linux-hardware.org/?probe=0c1eb0be4f) | Jun 21, 2021 |
| Lenovo        | Yoga 9 15IMH5 82DE          | Convertible | [235d2d6944](https://linux-hardware.org/?probe=235d2d6944) | Jun 21, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [7499a86ba1](https://linux-hardware.org/?probe=7499a86ba1) | Jun 21, 2021 |
| Lenovo        | ThinkPad E15 20RD0011MZ     | Notebook    | [df96074b07](https://linux-hardware.org/?probe=df96074b07) | Jun 21, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [5af8c6f41c](https://linux-hardware.org/?probe=5af8c6f41c) | Jun 21, 2021 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [5050b7baad](https://linux-hardware.org/?probe=5050b7baad) | Jun 21, 2021 |
| LG Electro... | 17Z90N-R.AAC8U1             | Notebook    | [09434b48cf](https://linux-hardware.org/?probe=09434b48cf) | Jun 21, 2021 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [5b26e5e2c9](https://linux-hardware.org/?probe=5b26e5e2c9) | Jun 20, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [59fa18019a](https://linux-hardware.org/?probe=59fa18019a) | Jun 20, 2021 |
| Acer          | Aspire E5-475G              | Notebook    | [0d6df01751](https://linux-hardware.org/?probe=0d6df01751) | Jun 20, 2021 |
| ASUSTek       | PRIME A320M-E               | Desktop     | [edb0b62fe0](https://linux-hardware.org/?probe=edb0b62fe0) | Jun 19, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [e3e63b4e4c](https://linux-hardware.org/?probe=e3e63b4e4c) | Jun 19, 2021 |
| Gigabyte      | GA-MA785GT-UD3H             | Desktop     | [ed109bbeda](https://linux-hardware.org/?probe=ed109bbeda) | Jun 19, 2021 |
| Dell          | 0F8101                      | Desktop     | [a33d01212c](https://linux-hardware.org/?probe=a33d01212c) | Jun 19, 2021 |
| Apple         | MacBookPro11,5              | Notebook    | [de8b613aef](https://linux-hardware.org/?probe=de8b613aef) | Jun 19, 2021 |
| Apple         | MacBookPro11,5              | Notebook    | [0cdcd68d1e](https://linux-hardware.org/?probe=0cdcd68d1e) | Jun 19, 2021 |
| Medion        | E3223 MD61127               | Convertible | [7c073ecfb9](https://linux-hardware.org/?probe=7c073ecfb9) | Jun 19, 2021 |
| HP            | 255 G4                      | Notebook    | [3a4a67761f](https://linux-hardware.org/?probe=3a4a67761f) | Jun 19, 2021 |
| ASUSTek       | ROG Zephyrus GX550LXS_GX... | Notebook    | [822acd5e9b](https://linux-hardware.org/?probe=822acd5e9b) | Jun 19, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [55d0bea92e](https://linux-hardware.org/?probe=55d0bea92e) | Jun 19, 2021 |
| Acer          | Aspire E1-572               | Notebook    | [5d9f586d72](https://linux-hardware.org/?probe=5d9f586d72) | Jun 19, 2021 |
| Acer          | Predator G3-571             | Notebook    | [1e3a3e9e1b](https://linux-hardware.org/?probe=1e3a3e9e1b) | Jun 19, 2021 |
| HP            | 8056                        | Desktop     | [f1b5c0d45e](https://linux-hardware.org/?probe=f1b5c0d45e) | Jun 18, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3489fe1584](https://linux-hardware.org/?probe=3489fe1584) | Jun 18, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [0fe1eac567](https://linux-hardware.org/?probe=0fe1eac567) | Jun 18, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [0cfbaaded5](https://linux-hardware.org/?probe=0cfbaaded5) | Jun 18, 2021 |
| Gigabyte      | Z270-HD3P-CF                | Desktop     | [8e3aa30f32](https://linux-hardware.org/?probe=8e3aa30f32) | Jun 18, 2021 |
| Lenovo        | ThinkPad T480 20L6S29D07    | Notebook    | [5c87bcb1dc](https://linux-hardware.org/?probe=5c87bcb1dc) | Jun 18, 2021 |
| Dell          | Latitude 5310               | Notebook    | [a38b907625](https://linux-hardware.org/?probe=a38b907625) | Jun 18, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [92d16a4d2d](https://linux-hardware.org/?probe=92d16a4d2d) | Jun 18, 2021 |
| ASRock        | H97 Killer                  | Desktop     | [acc4773b1b](https://linux-hardware.org/?probe=acc4773b1b) | Jun 18, 2021 |
| Lenovo        | ThinkPad E15 20RD0011MZ     | Notebook    | [d7cfb8d16f](https://linux-hardware.org/?probe=d7cfb8d16f) | Jun 18, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [04fa70e3af](https://linux-hardware.org/?probe=04fa70e3af) | Jun 18, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [ecdf88f402](https://linux-hardware.org/?probe=ecdf88f402) | Jun 18, 2021 |
| HP            | Pro x2 612 G1 Tablet        | Notebook    | [05dbeca379](https://linux-hardware.org/?probe=05dbeca379) | Jun 17, 2021 |
| HP            | 81C5 MVB                    | Desktop     | [eb5550cdef](https://linux-hardware.org/?probe=eb5550cdef) | Jun 17, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [419ff5b1e5](https://linux-hardware.org/?probe=419ff5b1e5) | Jun 17, 2021 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [c9cf129666](https://linux-hardware.org/?probe=c9cf129666) | Jun 17, 2021 |
| Dell          | Inspiron 3543               | Notebook    | [4a5c3ed30c](https://linux-hardware.org/?probe=4a5c3ed30c) | Jun 17, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [a078b826cc](https://linux-hardware.org/?probe=a078b826cc) | Jun 17, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [d17aa6436e](https://linux-hardware.org/?probe=d17aa6436e) | Jun 17, 2021 |
| Intel         | MIR1 RVP7                   | Desktop     | [b0a36a3845](https://linux-hardware.org/?probe=b0a36a3845) | Jun 17, 2021 |
| HP            | Pro x2 612 G1 Tablet        | Notebook    | [f685842bb1](https://linux-hardware.org/?probe=f685842bb1) | Jun 16, 2021 |
| ASUSTek       | P5N73-CM                    | Desktop     | [5320c39497](https://linux-hardware.org/?probe=5320c39497) | Jun 16, 2021 |
| ASUSTek       | P5N73-CM                    | Desktop     | [096e520c57](https://linux-hardware.org/?probe=096e520c57) | Jun 16, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [e66e2f9e89](https://linux-hardware.org/?probe=e66e2f9e89) | Jun 16, 2021 |
| ASRock        | Z170 Extreme7+              | Desktop     | [180e2dcad0](https://linux-hardware.org/?probe=180e2dcad0) | Jun 16, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [caee94b554](https://linux-hardware.org/?probe=caee94b554) | Jun 16, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [28d36f1b88](https://linux-hardware.org/?probe=28d36f1b88) | Jun 16, 2021 |
| TrekStor      | Notebook Slim S130          | Notebook    | [312670a9e8](https://linux-hardware.org/?probe=312670a9e8) | Jun 16, 2021 |
| TrekStor      | Notebook Slim S130          | Notebook    | [c5bd6200eb](https://linux-hardware.org/?probe=c5bd6200eb) | Jun 16, 2021 |
| Dell          | Precision 7530              | Notebook    | [3e5d3c4292](https://linux-hardware.org/?probe=3e5d3c4292) | Jun 15, 2021 |
| HP            | Notebook                    | Notebook    | [d8ac22f956](https://linux-hardware.org/?probe=d8ac22f956) | Jun 15, 2021 |
| SLIMBOOK      | PROX15-AMD                  | Notebook    | [790371eae7](https://linux-hardware.org/?probe=790371eae7) | Jun 15, 2021 |
| Positivo      | C41TB                       | Notebook    | [3824885cc3](https://linux-hardware.org/?probe=3824885cc3) | Jun 15, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [28f64a2715](https://linux-hardware.org/?probe=28f64a2715) | Jun 15, 2021 |
| Gigabyte      | G41MT-D3                    | Desktop     | [6d61e60824](https://linux-hardware.org/?probe=6d61e60824) | Jun 15, 2021 |
| Gigabyte      | G41MT-D3                    | Desktop     | [7e4f2022c8](https://linux-hardware.org/?probe=7e4f2022c8) | Jun 15, 2021 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [6cf8aa4053](https://linux-hardware.org/?probe=6cf8aa4053) | Jun 15, 2021 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [9145765cc5](https://linux-hardware.org/?probe=9145765cc5) | Jun 15, 2021 |
| Lenovo        | ThinkCentre M58p 7220A72    | Desktop     | [b30a75edb2](https://linux-hardware.org/?probe=b30a75edb2) | Jun 15, 2021 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [8fa18de364](https://linux-hardware.org/?probe=8fa18de364) | Jun 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [891f747f39](https://linux-hardware.org/?probe=891f747f39) | Jun 15, 2021 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [9d6796ee13](https://linux-hardware.org/?probe=9d6796ee13) | Jun 14, 2021 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [447e508593](https://linux-hardware.org/?probe=447e508593) | Jun 14, 2021 |
| Dell          | Latitude 5285               | Notebook    | [0fad55c520](https://linux-hardware.org/?probe=0fad55c520) | Jun 14, 2021 |
| Dell          | Latitude 5285               | Notebook    | [4d7dfa80fc](https://linux-hardware.org/?probe=4d7dfa80fc) | Jun 14, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [4ecc3eec8f](https://linux-hardware.org/?probe=4ecc3eec8f) | Jun 14, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [a1f4d070a3](https://linux-hardware.org/?probe=a1f4d070a3) | Jun 14, 2021 |
| Dell          | Inspiron 5548               | Notebook    | [11bea838aa](https://linux-hardware.org/?probe=11bea838aa) | Jun 14, 2021 |
| Lenovo        | ThinkPad W520 4282AB9       | Notebook    | [a5d7b02f3f](https://linux-hardware.org/?probe=a5d7b02f3f) | Jun 14, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [692dcceeee](https://linux-hardware.org/?probe=692dcceeee) | Jun 14, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [3b280580e0](https://linux-hardware.org/?probe=3b280580e0) | Jun 14, 2021 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [0c32c6e173](https://linux-hardware.org/?probe=0c32c6e173) | Jun 14, 2021 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [ed5ee6c4fd](https://linux-hardware.org/?probe=ed5ee6c4fd) | Jun 14, 2021 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [2f146aa93d](https://linux-hardware.org/?probe=2f146aa93d) | Jun 14, 2021 |
| Lenovo        | ThinkPad E15 20RD0011RT     | Notebook    | [c995062581](https://linux-hardware.org/?probe=c995062581) | Jun 14, 2021 |
| HP            | Pro x2 612 G1 Tablet        | Notebook    | [696a1c9564](https://linux-hardware.org/?probe=696a1c9564) | Jun 13, 2021 |
| Lenovo        | ThinkCentre M58p 7220A72    | Desktop     | [c89aa8ea82](https://linux-hardware.org/?probe=c89aa8ea82) | Jun 13, 2021 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [b5b8d7a195](https://linux-hardware.org/?probe=b5b8d7a195) | Jun 13, 2021 |
| Notebook      | NH5x_7xDPx                  | Notebook    | [0f4817a280](https://linux-hardware.org/?probe=0f4817a280) | Jun 13, 2021 |
| Acer          | Nitro AN515-42              | Notebook    | [f70d1d9749](https://linux-hardware.org/?probe=f70d1d9749) | Jun 13, 2021 |
| Notebook      | NH5x_7xDPx                  | Notebook    | [1ffaea82ea](https://linux-hardware.org/?probe=1ffaea82ea) | Jun 13, 2021 |
| Intel         | SHARKBAY                    | Desktop     | [2b38485e94](https://linux-hardware.org/?probe=2b38485e94) | Jun 13, 2021 |
| HP            | Laptop 15-db1xxx            | Notebook    | [ab3536f2c6](https://linux-hardware.org/?probe=ab3536f2c6) | Jun 13, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [c2803c157e](https://linux-hardware.org/?probe=c2803c157e) | Jun 13, 2021 |
| ASUSTek       | M2N-E SLI                   | Desktop     | [c1805791ab](https://linux-hardware.org/?probe=c1805791ab) | Jun 13, 2021 |
| LG Electro... | 22V280 FAB1                 | All in one  | [dc2adb8c8b](https://linux-hardware.org/?probe=dc2adb8c8b) | Jun 13, 2021 |
| Notebook      | PB50_70DFx,DDx              | Notebook    | [48d6b0c4de](https://linux-hardware.org/?probe=48d6b0c4de) | Jun 13, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [3f74265d6d](https://linux-hardware.org/?probe=3f74265d6d) | Jun 12, 2021 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [86c9df0816](https://linux-hardware.org/?probe=86c9df0816) | Jun 12, 2021 |
| Samsung       | 700Z3C/700Z5C               | Notebook    | [01e22d19b3](https://linux-hardware.org/?probe=01e22d19b3) | Jun 12, 2021 |
| Gigabyte      | Z97MX-Gaming 5              | Desktop     | [2dcbc551cd](https://linux-hardware.org/?probe=2dcbc551cd) | Jun 12, 2021 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [0a78275a12](https://linux-hardware.org/?probe=0a78275a12) | Jun 12, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [8081e6a752](https://linux-hardware.org/?probe=8081e6a752) | Jun 12, 2021 |
| Dell          | Precision 5510              | Notebook    | [afb07c1b1a](https://linux-hardware.org/?probe=afb07c1b1a) | Jun 12, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [edcaa9a1be](https://linux-hardware.org/?probe=edcaa9a1be) | Jun 12, 2021 |
| Lenovo        | IdeaPad Flex 5 14ARE05 8... | Convertible | [755e53550d](https://linux-hardware.org/?probe=755e53550d) | Jun 12, 2021 |
| Lenovo        | ThinkPad E480 20KN003YUS    | Notebook    | [33d07363b6](https://linux-hardware.org/?probe=33d07363b6) | Jun 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [3641fab1a0](https://linux-hardware.org/?probe=3641fab1a0) | Jun 12, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [b0ded1652a](https://linux-hardware.org/?probe=b0ded1652a) | Jun 12, 2021 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [92f48178fc](https://linux-hardware.org/?probe=92f48178fc) | Jun 12, 2021 |
| Dell          | Inspiron 5555               | Notebook    | [dd9bf62ea7](https://linux-hardware.org/?probe=dd9bf62ea7) | Jun 11, 2021 |
| HP            | Laptop 15-db1xxx            | Notebook    | [b012f183ba](https://linux-hardware.org/?probe=b012f183ba) | Jun 11, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [94d4ada14e](https://linux-hardware.org/?probe=94d4ada14e) | Jun 11, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [7805e2e2a1](https://linux-hardware.org/?probe=7805e2e2a1) | Jun 11, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [2d43d8a465](https://linux-hardware.org/?probe=2d43d8a465) | Jun 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [d4c54270ff](https://linux-hardware.org/?probe=d4c54270ff) | Jun 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [c346ece974](https://linux-hardware.org/?probe=c346ece974) | Jun 11, 2021 |
| HP            | 3397                        | Desktop     | [e171bcda3f](https://linux-hardware.org/?probe=e171bcda3f) | Jun 11, 2021 |
| Dell          | Inspiron 5548               | Notebook    | [9c821bc1eb](https://linux-hardware.org/?probe=9c821bc1eb) | Jun 11, 2021 |
| Gigabyte      | EP41-UD3L                   | Desktop     | [aa273ff14d](https://linux-hardware.org/?probe=aa273ff14d) | Jun 10, 2021 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [405b055ebd](https://linux-hardware.org/?probe=405b055ebd) | Jun 10, 2021 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [cf5a4ceda4](https://linux-hardware.org/?probe=cf5a4ceda4) | Jun 10, 2021 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [43b8801add](https://linux-hardware.org/?probe=43b8801add) | Jun 10, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [5221d99db7](https://linux-hardware.org/?probe=5221d99db7) | Jun 10, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [c51cb3ca6a](https://linux-hardware.org/?probe=c51cb3ca6a) | Jun 10, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [565cd46886](https://linux-hardware.org/?probe=565cd46886) | Jun 10, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [241e4071cc](https://linux-hardware.org/?probe=241e4071cc) | Jun 10, 2021 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [403ab2f377](https://linux-hardware.org/?probe=403ab2f377) | Jun 09, 2021 |
| ASUSTek       | TUF B365M-PLUS GAMING       | Desktop     | [ebca8fe85a](https://linux-hardware.org/?probe=ebca8fe85a) | Jun 09, 2021 |
| HP            | ZBook 17 G2                 | Notebook    | [05a2ecf3ec](https://linux-hardware.org/?probe=05a2ecf3ec) | Jun 09, 2021 |
| ASUSTek       | TUF B365M-PLUS GAMING       | Desktop     | [0023c36bb4](https://linux-hardware.org/?probe=0023c36bb4) | Jun 09, 2021 |
| HP            | Laptop 15-db1xxx            | Notebook    | [d0192aebbf](https://linux-hardware.org/?probe=d0192aebbf) | Jun 09, 2021 |
| Acer          | Aspire 5742                 | Notebook    | [2cbf5797c7](https://linux-hardware.org/?probe=2cbf5797c7) | Jun 09, 2021 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [4134764afd](https://linux-hardware.org/?probe=4134764afd) | Jun 09, 2021 |
| Gigabyte      | Z270-HD3P-CF                | Desktop     | [85ad270405](https://linux-hardware.org/?probe=85ad270405) | Jun 09, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [783d8a89bd](https://linux-hardware.org/?probe=783d8a89bd) | Jun 09, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [91d8938c98](https://linux-hardware.org/?probe=91d8938c98) | Jun 09, 2021 |
| Acer          | Aspire 5742                 | Notebook    | [07bd5e87d7](https://linux-hardware.org/?probe=07bd5e87d7) | Jun 09, 2021 |
| Gigabyte      | G41MT-D3                    | Desktop     | [a1cfc1d335](https://linux-hardware.org/?probe=a1cfc1d335) | Jun 09, 2021 |
| Supermicro    | X9SRA/X9SRA-3               | Server      | [47401d66ce](https://linux-hardware.org/?probe=47401d66ce) | Jun 09, 2021 |
| ASRock        | A300M-STX                   | Desktop     | [d5fbd4c05d](https://linux-hardware.org/?probe=d5fbd4c05d) | Jun 08, 2021 |
| HP            | ZBook Studio G3             | Notebook    | [02463072c4](https://linux-hardware.org/?probe=02463072c4) | Jun 08, 2021 |
| Lenovo        | ThinkPad E560 20EV003WUS    | Notebook    | [fc739d0d64](https://linux-hardware.org/?probe=fc739d0d64) | Jun 08, 2021 |
| Dell          | Inspiron 5548               | Notebook    | [2ac85efa40](https://linux-hardware.org/?probe=2ac85efa40) | Jun 08, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [0604956adc](https://linux-hardware.org/?probe=0604956adc) | Jun 08, 2021 |
| MSI           | Z390-A PRO                  | Desktop     | [8d4983662d](https://linux-hardware.org/?probe=8d4983662d) | Jun 08, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [efff65d826](https://linux-hardware.org/?probe=efff65d826) | Jun 08, 2021 |
| ASUSTek       | N550JV                      | Notebook    | [7973dc9123](https://linux-hardware.org/?probe=7973dc9123) | Jun 08, 2021 |
| HP            | 843C                        | Desktop     | [391865c5a2](https://linux-hardware.org/?probe=391865c5a2) | Jun 08, 2021 |
| Dell          | Inspiron 3583               | Notebook    | [ead95cf972](https://linux-hardware.org/?probe=ead95cf972) | Jun 08, 2021 |
| Acer          | Aspire E5-573G              | Notebook    | [74bfd5efb9](https://linux-hardware.org/?probe=74bfd5efb9) | Jun 08, 2021 |
| Lenovo        | ThinkPad T450s 20BWS1RG0... | Notebook    | [79d386a567](https://linux-hardware.org/?probe=79d386a567) | Jun 08, 2021 |
| HP            | Pavilion 15                 | Notebook    | [8c0f52c64d](https://linux-hardware.org/?probe=8c0f52c64d) | Jun 08, 2021 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [c493d4cdf9](https://linux-hardware.org/?probe=c493d4cdf9) | Jun 07, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [2c66c12e1b](https://linux-hardware.org/?probe=2c66c12e1b) | Jun 07, 2021 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [13eaba8cd2](https://linux-hardware.org/?probe=13eaba8cd2) | Jun 07, 2021 |
| HP            | OMEN by HP Laptop           | Notebook    | [8f4c9482d3](https://linux-hardware.org/?probe=8f4c9482d3) | Jun 07, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [47a618e206](https://linux-hardware.org/?probe=47a618e206) | Jun 07, 2021 |
| Lenovo        | ThinkPad L380 Yoga 20M7S... | Convertible | [6c78870b5b](https://linux-hardware.org/?probe=6c78870b5b) | Jun 07, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [872d0ecc32](https://linux-hardware.org/?probe=872d0ecc32) | Jun 07, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | Desktop     | [521f3e1bde](https://linux-hardware.org/?probe=521f3e1bde) | Jun 07, 2021 |
| HP            | ProBook 470 G5              | Notebook    | [517c800c42](https://linux-hardware.org/?probe=517c800c42) | Jun 07, 2021 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [10cb3b472b](https://linux-hardware.org/?probe=10cb3b472b) | Jun 07, 2021 |
| Lenovo        | ThinkPad X220 4290LT8       | Notebook    | [281446b9b1](https://linux-hardware.org/?probe=281446b9b1) | Jun 07, 2021 |
| Dell          | XPS 13 9300                 | Notebook    | [63f094943a](https://linux-hardware.org/?probe=63f094943a) | Jun 07, 2021 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [c98bcbf189](https://linux-hardware.org/?probe=c98bcbf189) | Jun 07, 2021 |
| HP            | ProBook 450 G5              | Notebook    | [3f5df2365c](https://linux-hardware.org/?probe=3f5df2365c) | Jun 07, 2021 |
| Gateway       | DX4860                      | Desktop     | [bd9a842eec](https://linux-hardware.org/?probe=bd9a842eec) | Jun 07, 2021 |
| Gateway       | DX4860                      | Desktop     | [a26d972766](https://linux-hardware.org/?probe=a26d972766) | Jun 07, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [d5b58807dd](https://linux-hardware.org/?probe=d5b58807dd) | Jun 07, 2021 |
| Dell          | Latitude 7370               | Notebook    | [ddfe1dc0a3](https://linux-hardware.org/?probe=ddfe1dc0a3) | Jun 07, 2021 |
| ASRock        | B560M Steel Legend          | Desktop     | [c87d28e8c0](https://linux-hardware.org/?probe=c87d28e8c0) | Jun 07, 2021 |
| HP            | Pavilion 15                 | Notebook    | [010da56dde](https://linux-hardware.org/?probe=010da56dde) | Jun 06, 2021 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [5541611054](https://linux-hardware.org/?probe=5541611054) | Jun 06, 2021 |
| Acer          | Nitro AN517-52              | Notebook    | [c79b400454](https://linux-hardware.org/?probe=c79b400454) | Jun 06, 2021 |
| HP            | EliteBook x360 1040 G5      | Convertible | [3af4716969](https://linux-hardware.org/?probe=3af4716969) | Jun 06, 2021 |
| ASRock        | H97M Pro4                   | Desktop     | [8ba65755ff](https://linux-hardware.org/?probe=8ba65755ff) | Jun 06, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [7e68daad35](https://linux-hardware.org/?probe=7e68daad35) | Jun 06, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [4d157e0cce](https://linux-hardware.org/?probe=4d157e0cce) | Jun 06, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [ba3e1c4e32](https://linux-hardware.org/?probe=ba3e1c4e32) | Jun 05, 2021 |
| ASUSTek       | T100TA                      | Notebook    | [6bd42268f6](https://linux-hardware.org/?probe=6bd42268f6) | Jun 05, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [d94c194ba5](https://linux-hardware.org/?probe=d94c194ba5) | Jun 05, 2021 |
| Intel         | H61                         | Desktop     | [607d6e5e33](https://linux-hardware.org/?probe=607d6e5e33) | Jun 05, 2021 |
| Intel         | H61                         | Desktop     | [8ed3e75d2d](https://linux-hardware.org/?probe=8ed3e75d2d) | Jun 05, 2021 |
| HP            | 8768 A                      | Desktop     | [f239501901](https://linux-hardware.org/?probe=f239501901) | Jun 05, 2021 |
| Lenovo        | Yoga Slim 7 15ITL05 82AC    | Notebook    | [da76c3ea04](https://linux-hardware.org/?probe=da76c3ea04) | Jun 05, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [25a53bf5a0](https://linux-hardware.org/?probe=25a53bf5a0) | Jun 05, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [4fb050f895](https://linux-hardware.org/?probe=4fb050f895) | Jun 05, 2021 |
| MSI           | A78M-E35                    | Desktop     | [4d4959df32](https://linux-hardware.org/?probe=4d4959df32) | Jun 04, 2021 |
| MSI           | A78M-E35                    | Desktop     | [7dc4db6092](https://linux-hardware.org/?probe=7dc4db6092) | Jun 04, 2021 |
| ASRock        | AB350 Pro4                  | Desktop     | [557557b4eb](https://linux-hardware.org/?probe=557557b4eb) | Jun 04, 2021 |
| Dell          | Latitude E7440              | Notebook    | [32b9a694b3](https://linux-hardware.org/?probe=32b9a694b3) | Jun 04, 2021 |
| HP            | 0AECh D                     | Desktop     | [0a0a487efe](https://linux-hardware.org/?probe=0a0a487efe) | Jun 04, 2021 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [43a9dc51d9](https://linux-hardware.org/?probe=43a9dc51d9) | Jun 04, 2021 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [4023b437d2](https://linux-hardware.org/?probe=4023b437d2) | Jun 04, 2021 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [c8d175865c](https://linux-hardware.org/?probe=c8d175865c) | Jun 04, 2021 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [f3ffbcfa47](https://linux-hardware.org/?probe=f3ffbcfa47) | Jun 04, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [4931426516](https://linux-hardware.org/?probe=4931426516) | Jun 03, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [b967eaa6db](https://linux-hardware.org/?probe=b967eaa6db) | Jun 03, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [1cb5b38d5e](https://linux-hardware.org/?probe=1cb5b38d5e) | Jun 03, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [00119f7ba5](https://linux-hardware.org/?probe=00119f7ba5) | Jun 03, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [221e440b21](https://linux-hardware.org/?probe=221e440b21) | Jun 03, 2021 |
| ASUSTek       | PRIME H310M-D               | Desktop     | [5f98fdcb02](https://linux-hardware.org/?probe=5f98fdcb02) | Jun 03, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f0057c8374](https://linux-hardware.org/?probe=f0057c8374) | Jun 03, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [1c0016dc30](https://linux-hardware.org/?probe=1c0016dc30) | Jun 03, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [0e54cb2214](https://linux-hardware.org/?probe=0e54cb2214) | Jun 03, 2021 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [290d70d292](https://linux-hardware.org/?probe=290d70d292) | Jun 03, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [1cba119582](https://linux-hardware.org/?probe=1cba119582) | Jun 03, 2021 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [ceb72d0ae7](https://linux-hardware.org/?probe=ceb72d0ae7) | Jun 03, 2021 |
| Gigabyte      | G41MT-D3                    | Desktop     | [9bae888d70](https://linux-hardware.org/?probe=9bae888d70) | Jun 03, 2021 |
| Lenovo        | ThinkCentre M58p 7220A72    | Desktop     | [4c17a95dc1](https://linux-hardware.org/?probe=4c17a95dc1) | Jun 03, 2021 |
| Dell          | 0427JK A00                  | Desktop     | [0cde3de43d](https://linux-hardware.org/?probe=0cde3de43d) | Jun 03, 2021 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [dbfeab0bb4](https://linux-hardware.org/?probe=dbfeab0bb4) | Jun 02, 2021 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [1a7c5aee0e](https://linux-hardware.org/?probe=1a7c5aee0e) | Jun 02, 2021 |
| ASUSTek       | M2N-E SLI                   | Desktop     | [203b62c458](https://linux-hardware.org/?probe=203b62c458) | Jun 02, 2021 |
| Acer          | Swift SF315-52G             | Notebook    | [8ed81a9451](https://linux-hardware.org/?probe=8ed81a9451) | Jun 02, 2021 |
| Acer          | Swift SF315-52G             | Notebook    | [5d8e928b43](https://linux-hardware.org/?probe=5d8e928b43) | Jun 02, 2021 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [09a3733791](https://linux-hardware.org/?probe=09a3733791) | Jun 01, 2021 |
| ASUSTek       | N550JV                      | Notebook    | [475195dcd9](https://linux-hardware.org/?probe=475195dcd9) | Jun 01, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [ad37db1da8](https://linux-hardware.org/?probe=ad37db1da8) | Jun 01, 2021 |
| HP            | 240 G4 Notebook PC          | Notebook    | [e47851b0ed](https://linux-hardware.org/?probe=e47851b0ed) | Jun 01, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [f5dafbe2de](https://linux-hardware.org/?probe=f5dafbe2de) | Jun 01, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [90afa2df5b](https://linux-hardware.org/?probe=90afa2df5b) | Jun 01, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [9c3ecf7ae2](https://linux-hardware.org/?probe=9c3ecf7ae2) | Jun 01, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [a6131ffc39](https://linux-hardware.org/?probe=a6131ffc39) | Jun 01, 2021 |
| Acer          | Swift SF314-56              | Notebook    | [1b59a580ea](https://linux-hardware.org/?probe=1b59a580ea) | Jun 01, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [add3cc76ee](https://linux-hardware.org/?probe=add3cc76ee) | Jun 01, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [f7ca87e974](https://linux-hardware.org/?probe=f7ca87e974) | Jun 01, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [5441c2ab6f](https://linux-hardware.org/?probe=5441c2ab6f) | Jun 01, 2021 |
| HP            | 240 G4 Notebook PC          | Notebook    | [0a9b2c114f](https://linux-hardware.org/?probe=0a9b2c114f) | Jun 01, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [b8d0e81636](https://linux-hardware.org/?probe=b8d0e81636) | Jun 01, 2021 |
| Gigabyte      | 990XA-UD3                   | Desktop     | [77fcb9cf4a](https://linux-hardware.org/?probe=77fcb9cf4a) | Jun 01, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [ad3c1fb56a](https://linux-hardware.org/?probe=ad3c1fb56a) | May 31, 2021 |
| Gigabyte      | Z97-HD3                     | Desktop     | [e0277e3530](https://linux-hardware.org/?probe=e0277e3530) | May 31, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [5e75af2ba4](https://linux-hardware.org/?probe=5e75af2ba4) | May 31, 2021 |
| Dell          | 0R849J A00                  | Desktop     | [7a75936b55](https://linux-hardware.org/?probe=7a75936b55) | May 31, 2021 |
| Dell          | 0GXM1W A01                  | Desktop     | [4daf9fdc0d](https://linux-hardware.org/?probe=4daf9fdc0d) | May 31, 2021 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [5125306d59](https://linux-hardware.org/?probe=5125306d59) | May 31, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [af8045a7b3](https://linux-hardware.org/?probe=af8045a7b3) | May 31, 2021 |
| HP            | Notebook                    | Notebook    | [7493540206](https://linux-hardware.org/?probe=7493540206) | May 31, 2021 |
| HP            | Notebook                    | Notebook    | [eaabc0c626](https://linux-hardware.org/?probe=eaabc0c626) | May 31, 2021 |
| Login Info... | LOG-QAL30                   | Notebook    | [4caf31da4e](https://linux-hardware.org/?probe=4caf31da4e) | May 31, 2021 |
| ASUSTek       | K54C                        | Notebook    | [389e1a52a6](https://linux-hardware.org/?probe=389e1a52a6) | May 31, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [9b20a88d5e](https://linux-hardware.org/?probe=9b20a88d5e) | May 31, 2021 |
| Timi          | RedmiBook 14 II             | Notebook    | [8700a7eaed](https://linux-hardware.org/?probe=8700a7eaed) | May 31, 2021 |
| HP            | EliteBook 745 G4            | Notebook    | [c401996108](https://linux-hardware.org/?probe=c401996108) | May 31, 2021 |
| Dell          | Latitude 7490               | Notebook    | [a92377cb2a](https://linux-hardware.org/?probe=a92377cb2a) | May 31, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [65310866eb](https://linux-hardware.org/?probe=65310866eb) | May 31, 2021 |
| ASUSTek       | TUF Gaming FX505DD_TUF50... | Notebook    | [d8a3297ab9](https://linux-hardware.org/?probe=d8a3297ab9) | May 30, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [ff3d2367ee](https://linux-hardware.org/?probe=ff3d2367ee) | May 30, 2021 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [80a31f37f4](https://linux-hardware.org/?probe=80a31f37f4) | May 30, 2021 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [e334fad2cc](https://linux-hardware.org/?probe=e334fad2cc) | May 30, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [5002e43f11](https://linux-hardware.org/?probe=5002e43f11) | May 30, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [0449b14156](https://linux-hardware.org/?probe=0449b14156) | May 30, 2021 |
| HP            | 8056                        | Desktop     | [fc6d4c2e7d](https://linux-hardware.org/?probe=fc6d4c2e7d) | May 30, 2021 |
| Huanan        | X79 VAA1                    | Desktop     | [150afcb2d1](https://linux-hardware.org/?probe=150afcb2d1) | May 30, 2021 |
| ASRock        | FM2A55M-VG3+                | Desktop     | [d9065ac8d1](https://linux-hardware.org/?probe=d9065ac8d1) | May 30, 2021 |
| Lenovo        | ThinkPad X1 Yoga 4th 20S... | Convertible | [32ca60dcea](https://linux-hardware.org/?probe=32ca60dcea) | May 30, 2021 |
| ASUSTek       | X750JN                      | Notebook    | [1f075feb49](https://linux-hardware.org/?probe=1f075feb49) | May 30, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [00c5d17913](https://linux-hardware.org/?probe=00c5d17913) | May 30, 2021 |
| Lenovo        | IdeaPad Flex 5 14ARE05 8... | Convertible | [64a9e43743](https://linux-hardware.org/?probe=64a9e43743) | May 30, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [31a6f21ccd](https://linux-hardware.org/?probe=31a6f21ccd) | May 29, 2021 |
| Dell          | Inspiron 3505               | Notebook    | [1b68ebc549](https://linux-hardware.org/?probe=1b68ebc549) | May 29, 2021 |
| MSI           | PX60 6QE                    | Notebook    | [eca3f4ce76](https://linux-hardware.org/?probe=eca3f4ce76) | May 29, 2021 |
| Samsung       | 700T                        | Notebook    | [374154a439](https://linux-hardware.org/?probe=374154a439) | May 29, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [af407b12e2](https://linux-hardware.org/?probe=af407b12e2) | May 29, 2021 |
| Lenovo        | IdeaPad 720S-14IKB 81BD     | Notebook    | [35941050e8](https://linux-hardware.org/?probe=35941050e8) | May 29, 2021 |
| Dell          | 00V62H A01                  | Desktop     | [73da9f35d4](https://linux-hardware.org/?probe=73da9f35d4) | May 29, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [7a13082af6](https://linux-hardware.org/?probe=7a13082af6) | May 29, 2021 |
| ASUSTek       | A88X-PRO                    | Desktop     | [bdb612797a](https://linux-hardware.org/?probe=bdb612797a) | May 29, 2021 |
| Gigabyte      | H370N WIFI-CF               | Desktop     | [197e319075](https://linux-hardware.org/?probe=197e319075) | May 29, 2021 |
| HUAWEI        | KPR-WX9                     | Notebook    | [9c73a8d7d6](https://linux-hardware.org/?probe=9c73a8d7d6) | May 29, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [06bb083e38](https://linux-hardware.org/?probe=06bb083e38) | May 29, 2021 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | Notebook    | [1268e75895](https://linux-hardware.org/?probe=1268e75895) | May 29, 2021 |
| Acer          | Nitro AN515-56              | Notebook    | [d468019e77](https://linux-hardware.org/?probe=d468019e77) | May 29, 2021 |
| A-DATA Tec... | XENIA159GENI72060           | Notebook    | [eee4dbbb99](https://linux-hardware.org/?probe=eee4dbbb99) | May 28, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [e8440f3a09](https://linux-hardware.org/?probe=e8440f3a09) | May 28, 2021 |
| Intel         | NUC7i5BNB J31144-309        | Mini pc     | [1761317692](https://linux-hardware.org/?probe=1761317692) | May 28, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [168717d052](https://linux-hardware.org/?probe=168717d052) | May 28, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [9e26259821](https://linux-hardware.org/?probe=9e26259821) | May 28, 2021 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [f23de0d726](https://linux-hardware.org/?probe=f23de0d726) | May 28, 2021 |
| Gigabyte      | H61M-S2PH                   | Desktop     | [e88de55691](https://linux-hardware.org/?probe=e88de55691) | May 28, 2021 |
| Dell          | Inspiron 5391               | Notebook    | [6722a1c1a6](https://linux-hardware.org/?probe=6722a1c1a6) | May 28, 2021 |
| Dell          | 00V62H A01                  | Desktop     | [927f339e68](https://linux-hardware.org/?probe=927f339e68) | May 28, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [ebffa34fe2](https://linux-hardware.org/?probe=ebffa34fe2) | May 28, 2021 |
| Lenovo        | Legion 5 15IMH05H 82CF      | Notebook    | [7a7114baf9](https://linux-hardware.org/?probe=7a7114baf9) | May 28, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [ccd56acb24](https://linux-hardware.org/?probe=ccd56acb24) | May 27, 2021 |
| HP            | Pavilion 15                 | Notebook    | [379b83c4c6](https://linux-hardware.org/?probe=379b83c4c6) | May 27, 2021 |
| Dell          | Latitude 7490               | Notebook    | [879fc7a838](https://linux-hardware.org/?probe=879fc7a838) | May 27, 2021 |
| HP            | Laptop 17-bs1xx             | Notebook    | [582d387cec](https://linux-hardware.org/?probe=582d387cec) | May 27, 2021 |
| Gigabyte      | Z170-Gaming K3-CF           | Desktop     | [5474165f7b](https://linux-hardware.org/?probe=5474165f7b) | May 27, 2021 |
| Lenovo        | ThinkPad T450 20BUS0WK03    | Notebook    | [6131e3c22a](https://linux-hardware.org/?probe=6131e3c22a) | May 27, 2021 |
| MSI           | GF63 Thin 9SC               | Notebook    | [95561ae2cf](https://linux-hardware.org/?probe=95561ae2cf) | May 27, 2021 |
| Dell          | Latitude 5480               | Notebook    | [8a2f2558ac](https://linux-hardware.org/?probe=8a2f2558ac) | May 27, 2021 |
| Dell          | Latitude 5480               | Notebook    | [faa9bc7f20](https://linux-hardware.org/?probe=faa9bc7f20) | May 27, 2021 |
| Apple         | MacBookPro11,3              | Notebook    | [07190ac752](https://linux-hardware.org/?probe=07190ac752) | May 27, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [7d0b344759](https://linux-hardware.org/?probe=7d0b344759) | May 27, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [bfb194b61c](https://linux-hardware.org/?probe=bfb194b61c) | May 27, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [ff37a9c00d](https://linux-hardware.org/?probe=ff37a9c00d) | May 27, 2021 |
| Lenovo        | ThinkPad Yoga 370 20JJS1... | Convertible | [9fcfe8bf6a](https://linux-hardware.org/?probe=9fcfe8bf6a) | May 27, 2021 |
| System76      | Oryx Pro                    | Notebook    | [a3d9cae93e](https://linux-hardware.org/?probe=a3d9cae93e) | May 27, 2021 |
| Unknown       | X79                         | Desktop     | [c6dcb137fb](https://linux-hardware.org/?probe=c6dcb137fb) | May 27, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [8e85b5f3cf](https://linux-hardware.org/?probe=8e85b5f3cf) | May 26, 2021 |
| ASRock        | X99 Extreme4                | Desktop     | [6feb0aec47](https://linux-hardware.org/?probe=6feb0aec47) | May 26, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [22f2fd6b39](https://linux-hardware.org/?probe=22f2fd6b39) | May 26, 2021 |
| Lenovo        | G510 20238                  | Notebook    | [7fb630f632](https://linux-hardware.org/?probe=7fb630f632) | May 26, 2021 |
| Lenovo        | ThinkPad E14 20RA001BUK     | Notebook    | [fb9abea0c5](https://linux-hardware.org/?probe=fb9abea0c5) | May 26, 2021 |
| Gigabyte      | Z170-Gaming K3-CF           | Desktop     | [172ab027e5](https://linux-hardware.org/?probe=172ab027e5) | May 26, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [8c36612ff4](https://linux-hardware.org/?probe=8c36612ff4) | May 26, 2021 |
| HP            | 21D0                        | Desktop     | [d6d7cbe7c5](https://linux-hardware.org/?probe=d6d7cbe7c5) | May 26, 2021 |
| HP            | 21D0                        | Desktop     | [68f25edcdd](https://linux-hardware.org/?probe=68f25edcdd) | May 26, 2021 |
| ASUSTek       | SABERTOOTH Z97 MARK 2       | Desktop     | [a6751fcc02](https://linux-hardware.org/?probe=a6751fcc02) | May 26, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [fbf4582983](https://linux-hardware.org/?probe=fbf4582983) | May 25, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [5c2536f2d0](https://linux-hardware.org/?probe=5c2536f2d0) | May 25, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [426b6eecef](https://linux-hardware.org/?probe=426b6eecef) | May 25, 2021 |
| ASRock        | A300M-STX                   | Desktop     | [4e5245a71d](https://linux-hardware.org/?probe=4e5245a71d) | May 25, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [c88a440423](https://linux-hardware.org/?probe=c88a440423) | May 25, 2021 |
| Pine Micro... | Pine64 RockPro64 v2.1       | Soc         | [e14edc9f4c](https://linux-hardware.org/?probe=e14edc9f4c) | May 25, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [3bd27c32fa](https://linux-hardware.org/?probe=3bd27c32fa) | May 25, 2021 |
| Lenovo        | ThinkPad E595 20NF001PTX    | Notebook    | [6cdaad9758](https://linux-hardware.org/?probe=6cdaad9758) | May 25, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [2ffefbd96c](https://linux-hardware.org/?probe=2ffefbd96c) | May 25, 2021 |
| Acer          | Aspire A315-41G             | Notebook    | [8dab17c109](https://linux-hardware.org/?probe=8dab17c109) | May 25, 2021 |
| Gigabyte      | Z170-Gaming K3-CF           | Desktop     | [b07793f86c](https://linux-hardware.org/?probe=b07793f86c) | May 25, 2021 |
| HP            | ZBook Studio G5             | Notebook    | [522583da69](https://linux-hardware.org/?probe=522583da69) | May 25, 2021 |
| ASUSTek       | TP410UAR                    | Convertible | [ce8e9af30d](https://linux-hardware.org/?probe=ce8e9af30d) | May 25, 2021 |
| Gigabyte      | Z97N-Gaming 5               | Desktop     | [b1b61b4aa6](https://linux-hardware.org/?probe=b1b61b4aa6) | May 25, 2021 |
| Intel         | H61                         | Desktop     | [5b5682ab2e](https://linux-hardware.org/?probe=5b5682ab2e) | May 25, 2021 |
| A-DATA Tec... | XENIA159GENI72060           | Notebook    | [e4c4563465](https://linux-hardware.org/?probe=e4c4563465) | May 24, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U30... | Notebook    | [980ef053d1](https://linux-hardware.org/?probe=980ef053d1) | May 24, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [be51fbb033](https://linux-hardware.org/?probe=be51fbb033) | May 24, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [8ffe17b548](https://linux-hardware.org/?probe=8ffe17b548) | May 24, 2021 |
| ASRock        | A300M-STX                   | Desktop     | [cecc5ad69e](https://linux-hardware.org/?probe=cecc5ad69e) | May 24, 2021 |
| NEC Comput... | PC-VK25MXZCB                | Notebook    | [0a1b7b959f](https://linux-hardware.org/?probe=0a1b7b959f) | May 24, 2021 |
| Timi          | RedmiBook 16                | Notebook    | [6ec8bb7df6](https://linux-hardware.org/?probe=6ec8bb7df6) | May 24, 2021 |
| Apple         | MacBookPro11,3              | Notebook    | [4d0c48aa12](https://linux-hardware.org/?probe=4d0c48aa12) | May 24, 2021 |
| Apple         | MacBookPro11,3              | Notebook    | [07a4b88864](https://linux-hardware.org/?probe=07a4b88864) | May 24, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [cf4e1cb0d6](https://linux-hardware.org/?probe=cf4e1cb0d6) | May 24, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [e65ad78e90](https://linux-hardware.org/?probe=e65ad78e90) | May 24, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [55abc8169d](https://linux-hardware.org/?probe=55abc8169d) | May 24, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [fd10e51b1d](https://linux-hardware.org/?probe=fd10e51b1d) | May 24, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [a200c3666a](https://linux-hardware.org/?probe=a200c3666a) | May 23, 2021 |
| HP            | 198E                        | Desktop     | [45fbf9c1d7](https://linux-hardware.org/?probe=45fbf9c1d7) | May 23, 2021 |
| Dell          | Latitude 5480               | Notebook    | [bc9170f4cd](https://linux-hardware.org/?probe=bc9170f4cd) | May 23, 2021 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [93b4f5b14e](https://linux-hardware.org/?probe=93b4f5b14e) | May 22, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [2198e565bf](https://linux-hardware.org/?probe=2198e565bf) | May 22, 2021 |
| Wortmann      | 1220692_1470187             | Notebook    | [8febf0d66c](https://linux-hardware.org/?probe=8febf0d66c) | May 22, 2021 |
| Acer          | Aspire C24-865              | All in one  | [eb23862ded](https://linux-hardware.org/?probe=eb23862ded) | May 22, 2021 |
| Notebook      | NH5x_7xDPx                  | Notebook    | [4a9dd7d6a1](https://linux-hardware.org/?probe=4a9dd7d6a1) | May 22, 2021 |
| Lenovo        | IdeaPad Duet 3 10IGL5 82... | Tablet      | [fd98fd839e](https://linux-hardware.org/?probe=fd98fd839e) | May 22, 2021 |
| HP            | Pavilion dv7                | Notebook    | [f04eba21ce](https://linux-hardware.org/?probe=f04eba21ce) | May 22, 2021 |
| Unknown       | Unknown                     | Desktop     | [ad90a50d8d](https://linux-hardware.org/?probe=ad90a50d8d) | May 22, 2021 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [f367112b19](https://linux-hardware.org/?probe=f367112b19) | May 22, 2021 |
| Unknown       | Unknown                     | Desktop     | [acaa4c3731](https://linux-hardware.org/?probe=acaa4c3731) | May 22, 2021 |
| Lenovo        | ThinkPad E480 20KNS0E200    | Notebook    | [893f642cbb](https://linux-hardware.org/?probe=893f642cbb) | May 22, 2021 |
| Positivo      | CHT14B                      | Notebook    | [4aab647b4f](https://linux-hardware.org/?probe=4aab647b4f) | May 22, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [d5ea76578b](https://linux-hardware.org/?probe=d5ea76578b) | May 22, 2021 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [d3762e2020](https://linux-hardware.org/?probe=d3762e2020) | May 21, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [0ccd96a39e](https://linux-hardware.org/?probe=0ccd96a39e) | May 21, 2021 |
| Hampoo        | Cherry Trail CR Hampoo_r... | Notebook    | [6ca37bdf8b](https://linux-hardware.org/?probe=6ca37bdf8b) | May 21, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [0ab74390ed](https://linux-hardware.org/?probe=0ab74390ed) | May 21, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [0a4bf488d4](https://linux-hardware.org/?probe=0a4bf488d4) | May 21, 2021 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [662203ff7f](https://linux-hardware.org/?probe=662203ff7f) | May 21, 2021 |
| HP            | Notebook                    | Notebook    | [1ce5457d13](https://linux-hardware.org/?probe=1ce5457d13) | May 21, 2021 |
| HP            | Notebook                    | Notebook    | [42756549fb](https://linux-hardware.org/?probe=42756549fb) | May 21, 2021 |
| ASUSTek       | X540YA                      | Notebook    | [c7d85ee10a](https://linux-hardware.org/?probe=c7d85ee10a) | May 21, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [197cbc5a5d](https://linux-hardware.org/?probe=197cbc5a5d) | May 21, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [b17a5c4cd5](https://linux-hardware.org/?probe=b17a5c4cd5) | May 21, 2021 |
| HP            | Pavilion dv7                | Notebook    | [f908acc1ad](https://linux-hardware.org/?probe=f908acc1ad) | May 20, 2021 |
| Apple         | MacBookPro11,5              | Notebook    | [550a3398ee](https://linux-hardware.org/?probe=550a3398ee) | May 20, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [c0b08eec61](https://linux-hardware.org/?probe=c0b08eec61) | May 20, 2021 |
| Lenovo        | ThinkPad P50 20EN0013US     | Notebook    | [88a08a450d](https://linux-hardware.org/?probe=88a08a450d) | May 20, 2021 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [7f2f6d6fc2](https://linux-hardware.org/?probe=7f2f6d6fc2) | May 20, 2021 |
| ASUSTek       | GL502VMK                    | Notebook    | [0d9f5609e7](https://linux-hardware.org/?probe=0d9f5609e7) | May 20, 2021 |
| ASRock        | E3C226D2I                   | Desktop     | [195f9748ad](https://linux-hardware.org/?probe=195f9748ad) | May 20, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [295d74c4f2](https://linux-hardware.org/?probe=295d74c4f2) | May 20, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [a0188a80b1](https://linux-hardware.org/?probe=a0188a80b1) | May 20, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [16725e35f7](https://linux-hardware.org/?probe=16725e35f7) | May 20, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [0a4ef78253](https://linux-hardware.org/?probe=0a4ef78253) | May 20, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [e447290fed](https://linux-hardware.org/?probe=e447290fed) | May 20, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [29f08a2300](https://linux-hardware.org/?probe=29f08a2300) | May 20, 2021 |
| Pine Micro... | Pine64 RockPro64 v2.1       | Soc         | [439e99b79e](https://linux-hardware.org/?probe=439e99b79e) | May 20, 2021 |
| ASUSTek       | ROG STRIX B460-H GAMING     | Desktop     | [7911704f32](https://linux-hardware.org/?probe=7911704f32) | May 19, 2021 |
| Dell          | XPS 15 9550                 | Notebook    | [3366809177](https://linux-hardware.org/?probe=3366809177) | May 19, 2021 |
| Lenovo        | ThinkPad T440p 20AWS2820... | Notebook    | [4ec9eaac2f](https://linux-hardware.org/?probe=4ec9eaac2f) | May 19, 2021 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [666ddeb09c](https://linux-hardware.org/?probe=666ddeb09c) | May 19, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ITL5 8... | Notebook    | [01af2920f0](https://linux-hardware.org/?probe=01af2920f0) | May 19, 2021 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [657fe689d6](https://linux-hardware.org/?probe=657fe689d6) | May 19, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [f2205716bb](https://linux-hardware.org/?probe=f2205716bb) | May 19, 2021 |
| Dell          | Inspiron 7737               | Notebook    | [ed5c16c955](https://linux-hardware.org/?probe=ed5c16c955) | May 19, 2021 |
| SLIMBOOK      | PROX15-AMD                  | Notebook    | [d80f4e83a0](https://linux-hardware.org/?probe=d80f4e83a0) | May 19, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [883f67612b](https://linux-hardware.org/?probe=883f67612b) | May 19, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [c2267f8dd1](https://linux-hardware.org/?probe=c2267f8dd1) | May 19, 2021 |
| Acer          | Nitro AN515-42              | Notebook    | [507cb00cac](https://linux-hardware.org/?probe=507cb00cac) | May 19, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [4a21e62a29](https://linux-hardware.org/?probe=4a21e62a29) | May 19, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [039435162c](https://linux-hardware.org/?probe=039435162c) | May 19, 2021 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [6b27a727be](https://linux-hardware.org/?probe=6b27a727be) | May 19, 2021 |
| Dell          | Inspiron 3421               | Notebook    | [4c5ee61420](https://linux-hardware.org/?probe=4c5ee61420) | May 19, 2021 |
| ASUSTek       | Z97-A                       | Desktop     | [0767c99abb](https://linux-hardware.org/?probe=0767c99abb) | May 19, 2021 |
| Unknown       | X79                         | Desktop     | [718089029d](https://linux-hardware.org/?probe=718089029d) | May 18, 2021 |
| ASUSTek       | X510URR                     | Notebook    | [51577f00b4](https://linux-hardware.org/?probe=51577f00b4) | May 18, 2021 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | Notebook    | [abdc61ad94](https://linux-hardware.org/?probe=abdc61ad94) | May 18, 2021 |
| ASUSTek       | X510URR                     | Notebook    | [e373dac808](https://linux-hardware.org/?probe=e373dac808) | May 18, 2021 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [6e95528aca](https://linux-hardware.org/?probe=6e95528aca) | May 18, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [56baaff907](https://linux-hardware.org/?probe=56baaff907) | May 18, 2021 |
| Samsung       | R580/R590                   | Notebook    | [41ca2c7546](https://linux-hardware.org/?probe=41ca2c7546) | May 18, 2021 |
| Acer          | Aspire A515-52              | Notebook    | [d2e4a69c16](https://linux-hardware.org/?probe=d2e4a69c16) | May 18, 2021 |
| ASUSTek       | PRIME Z370-A II             | Desktop     | [5a5c05e953](https://linux-hardware.org/?probe=5a5c05e953) | May 18, 2021 |
| ASUSTek       | Z77-A                       | Desktop     | [5569c32840](https://linux-hardware.org/?probe=5569c32840) | May 18, 2021 |
| HP            | Spectre Folio Convertibl... | Convertible | [87199d7e85](https://linux-hardware.org/?probe=87199d7e85) | May 18, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [64c121a751](https://linux-hardware.org/?probe=64c121a751) | May 18, 2021 |
| Lenovo        | ThinkPad X250 20CLS1B803    | Notebook    | [ae357880c6](https://linux-hardware.org/?probe=ae357880c6) | May 18, 2021 |
| ASRock        | Z370 Professional Gaming... | Desktop     | [2c915c81d9](https://linux-hardware.org/?probe=2c915c81d9) | May 18, 2021 |
| Dell          | Latitude 7400               | Notebook    | [660659882e](https://linux-hardware.org/?probe=660659882e) | May 17, 2021 |
| Dell          | Latitude 7400               | Notebook    | [4901f6b836](https://linux-hardware.org/?probe=4901f6b836) | May 17, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e32d9effa0](https://linux-hardware.org/?probe=e32d9effa0) | May 17, 2021 |
| Lenovo        | V130-15IKB 81HN             | Notebook    | [3630dfb215](https://linux-hardware.org/?probe=3630dfb215) | May 17, 2021 |
| Lenovo        | IdeaPad Flex 5 14ARE05 8... | Convertible | [5287ceef8d](https://linux-hardware.org/?probe=5287ceef8d) | May 17, 2021 |
| ASUSTek       | ZenBook Q406DA              | Convertible | [824bb881d7](https://linux-hardware.org/?probe=824bb881d7) | May 17, 2021 |
| Dell          | 077RRV A00                  | Desktop     | [c9ed9d5dfa](https://linux-hardware.org/?probe=c9ed9d5dfa) | May 17, 2021 |
| ASRock        | Z270 Pro4                   | Desktop     | [ba92e877c3](https://linux-hardware.org/?probe=ba92e877c3) | May 17, 2021 |
| MSI           | H110I PRO AC                | Desktop     | [17722fe0bf](https://linux-hardware.org/?probe=17722fe0bf) | May 17, 2021 |
| Gigabyte      | Z370N WIFI-CF               | Desktop     | [ca8565e246](https://linux-hardware.org/?probe=ca8565e246) | May 17, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [c98ee08146](https://linux-hardware.org/?probe=c98ee08146) | May 17, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [d8cec0c95b](https://linux-hardware.org/?probe=d8cec0c95b) | May 17, 2021 |
| ASUSTek       | ZenBook Q406DA              | Convertible | [89871a46e7](https://linux-hardware.org/?probe=89871a46e7) | May 17, 2021 |
| Dell          | G5 5590                     | Notebook    | [18621bd612](https://linux-hardware.org/?probe=18621bd612) | May 17, 2021 |
| Dell          | G5 5590                     | Notebook    | [3f55c4844d](https://linux-hardware.org/?probe=3f55c4844d) | May 17, 2021 |
| Dell          | Precision 5540              | Notebook    | [91e4aff19e](https://linux-hardware.org/?probe=91e4aff19e) | May 17, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [42eddedfb8](https://linux-hardware.org/?probe=42eddedfb8) | May 17, 2021 |
| Lenovo        | ThinkPad T440p 20AW009YB... | Notebook    | [1dda6f002e](https://linux-hardware.org/?probe=1dda6f002e) | May 16, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [5da8abe961](https://linux-hardware.org/?probe=5da8abe961) | May 16, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [43bbdc2153](https://linux-hardware.org/?probe=43bbdc2153) | May 16, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [51c5d13230](https://linux-hardware.org/?probe=51c5d13230) | May 16, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [557f952ce8](https://linux-hardware.org/?probe=557f952ce8) | May 16, 2021 |
| Sony          | VPCS12C5E                   | Notebook    | [188765c8f8](https://linux-hardware.org/?probe=188765c8f8) | May 16, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [a035be3ea2](https://linux-hardware.org/?probe=a035be3ea2) | May 16, 2021 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [1579b9c9d7](https://linux-hardware.org/?probe=1579b9c9d7) | May 16, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [15a742842f](https://linux-hardware.org/?probe=15a742842f) | May 16, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [16c877dbfe](https://linux-hardware.org/?probe=16c877dbfe) | May 16, 2021 |
| ASUSTek       | P7P55 LX                    | Desktop     | [35257f4cf0](https://linux-hardware.org/?probe=35257f4cf0) | May 16, 2021 |
| Unknown       | NF-MCP78                    | Desktop     | [4af8e42b5a](https://linux-hardware.org/?probe=4af8e42b5a) | May 16, 2021 |
| ASRock        | FM2A55M-VG3+                | Desktop     | [41e6c088d2](https://linux-hardware.org/?probe=41e6c088d2) | May 16, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | Desktop     | [1d398072e8](https://linux-hardware.org/?probe=1d398072e8) | May 15, 2021 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | Desktop     | [be75687645](https://linux-hardware.org/?probe=be75687645) | May 15, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | Desktop     | [344858ad94](https://linux-hardware.org/?probe=344858ad94) | May 15, 2021 |
| Apple         | MacBookPro14,1              | Notebook    | [620cd76f75](https://linux-hardware.org/?probe=620cd76f75) | May 15, 2021 |
| Lenovo        | IdeaPad 330S-15IKB GTX10... | Notebook    | [0f8a6b3dcf](https://linux-hardware.org/?probe=0f8a6b3dcf) | May 15, 2021 |
| Alienware     | 07HV66 A01                  | Desktop     | [016da6343d](https://linux-hardware.org/?probe=016da6343d) | May 15, 2021 |
| HP            | 15 Notebook PC              | Notebook    | [310752864a](https://linux-hardware.org/?probe=310752864a) | May 15, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [c85191ea3e](https://linux-hardware.org/?probe=c85191ea3e) | May 15, 2021 |
| Dell          | Latitude 5480               | Notebook    | [2c7c1983ac](https://linux-hardware.org/?probe=2c7c1983ac) | May 15, 2021 |
| Intel         | NUC9i9QNB K49243-402        | Mini pc     | [592fa60c7d](https://linux-hardware.org/?probe=592fa60c7d) | May 14, 2021 |
| ASUSTek       | N56VZ                       | Notebook    | [16d1cff353](https://linux-hardware.org/?probe=16d1cff353) | May 14, 2021 |
| MSI           | B560M PRO-VDH WIFI          | Desktop     | [529fdcaf2a](https://linux-hardware.org/?probe=529fdcaf2a) | May 14, 2021 |
| Acer          | Nitro AN515-42              | Notebook    | [ffe39a0c5a](https://linux-hardware.org/?probe=ffe39a0c5a) | May 14, 2021 |
| Unknown       | NF-MCP78                    | Desktop     | [a419bff4a3](https://linux-hardware.org/?probe=a419bff4a3) | May 14, 2021 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [674a800477](https://linux-hardware.org/?probe=674a800477) | May 14, 2021 |
| ASRock        | X570 Creator                | Desktop     | [6ac8300ce8](https://linux-hardware.org/?probe=6ac8300ce8) | May 14, 2021 |
| HP            | ProBook x360 435 G7         | Convertible | [f36ea99568](https://linux-hardware.org/?probe=f36ea99568) | May 14, 2021 |
| HP            | EliteBook 850 G3            | Notebook    | [cb589a4d2c](https://linux-hardware.org/?probe=cb589a4d2c) | May 14, 2021 |
| HP            | EliteBook 850 G3            | Notebook    | [00a23f1149](https://linux-hardware.org/?probe=00a23f1149) | May 14, 2021 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [9907063783](https://linux-hardware.org/?probe=9907063783) | May 14, 2021 |
| Irbis         | TW94                        | Notebook    | [099d5c86c3](https://linux-hardware.org/?probe=099d5c86c3) | May 14, 2021 |
| ASUSTek       | M5A97                       | Desktop     | [3853338a60](https://linux-hardware.org/?probe=3853338a60) | May 14, 2021 |
| HP            | EliteBook 850 G3            | Notebook    | [0885b824f7](https://linux-hardware.org/?probe=0885b824f7) | May 13, 2021 |
| HP            | EliteBook 850 G3            | Notebook    | [231212bfe0](https://linux-hardware.org/?probe=231212bfe0) | May 13, 2021 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [924b420c67](https://linux-hardware.org/?probe=924b420c67) | May 13, 2021 |
| Dell          | Latitude 7490               | Notebook    | [c533165389](https://linux-hardware.org/?probe=c533165389) | May 13, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [91d1b5e802](https://linux-hardware.org/?probe=91d1b5e802) | May 13, 2021 |
| Lenovo        | Yoga 510-14ISK 80S7         | Convertible | [1e4a851ad2](https://linux-hardware.org/?probe=1e4a851ad2) | May 13, 2021 |
| Dell          | 0HD5W2 A01                  | Desktop     | [3d9373090c](https://linux-hardware.org/?probe=3d9373090c) | May 13, 2021 |
| ASUSTek       | Benicia                     | Desktop     | [d8f52bab1c](https://linux-hardware.org/?probe=d8f52bab1c) | May 12, 2021 |
| ASUSTek       | Benicia                     | Desktop     | [a36fa0a3b4](https://linux-hardware.org/?probe=a36fa0a3b4) | May 12, 2021 |
| Lenovo        | ThinkPad T490s 20NYS04V0... | Notebook    | [18da93a841](https://linux-hardware.org/?probe=18da93a841) | May 12, 2021 |
| HP            | ProBook 4530s               | Notebook    | [3d5a77511e](https://linux-hardware.org/?probe=3d5a77511e) | May 12, 2021 |
| Dell          | Inspiron 5555               | Notebook    | [e0a49e12f1](https://linux-hardware.org/?probe=e0a49e12f1) | May 12, 2021 |
| Lenovo        | ThinkPad T460s 20FAS0W90... | Notebook    | [b526eddd71](https://linux-hardware.org/?probe=b526eddd71) | May 12, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [22e9d3f5fd](https://linux-hardware.org/?probe=22e9d3f5fd) | May 12, 2021 |
| ASUSTek       | UX330UAK                    | Notebook    | [0abe5082fe](https://linux-hardware.org/?probe=0abe5082fe) | May 12, 2021 |
| ASUSTek       | UX330UAK                    | Notebook    | [0f72a78d10](https://linux-hardware.org/?probe=0f72a78d10) | May 12, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [eeac0e0535](https://linux-hardware.org/?probe=eeac0e0535) | May 12, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [dc39103e2e](https://linux-hardware.org/?probe=dc39103e2e) | May 12, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [fab7d18783](https://linux-hardware.org/?probe=fab7d18783) | May 12, 2021 |
| ASRock        | FM2A55M-VG3+                | Desktop     | [370eb9dee4](https://linux-hardware.org/?probe=370eb9dee4) | May 12, 2021 |
| ASRock        | FM2A55M-VG3+                | Desktop     | [ada1c4a259](https://linux-hardware.org/?probe=ada1c4a259) | May 12, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [d2951f517e](https://linux-hardware.org/?probe=d2951f517e) | May 12, 2021 |
| MSI           | B350M GAMING PRO            | Desktop     | [565e8ea07c](https://linux-hardware.org/?probe=565e8ea07c) | May 12, 2021 |
| Dell          | Inspiron N5010              | Notebook    | [c4c9a421b7](https://linux-hardware.org/?probe=c4c9a421b7) | May 12, 2021 |
| ASUSTek       | X555LB                      | Notebook    | [10b0865cab](https://linux-hardware.org/?probe=10b0865cab) | May 12, 2021 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [744242646f](https://linux-hardware.org/?probe=744242646f) | May 12, 2021 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [c5e4ff103f](https://linux-hardware.org/?probe=c5e4ff103f) | May 11, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [ad9a7e706d](https://linux-hardware.org/?probe=ad9a7e706d) | May 11, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | Notebook    | [049f443199](https://linux-hardware.org/?probe=049f443199) | May 11, 2021 |
| HP            | EliteBook x360 830 G6       | Convertible | [d862548439](https://linux-hardware.org/?probe=d862548439) | May 11, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [702de808b0](https://linux-hardware.org/?probe=702de808b0) | May 11, 2021 |
| Unknown       | Unknown                     | Notebook    | [6b7557c4d1](https://linux-hardware.org/?probe=6b7557c4d1) | May 11, 2021 |
| Dell          | Latitude E6320              | Notebook    | [3d76e2296e](https://linux-hardware.org/?probe=3d76e2296e) | May 11, 2021 |
| HP            | 15 Notebook PC              | Notebook    | [6afabfb5b3](https://linux-hardware.org/?probe=6afabfb5b3) | May 11, 2021 |
| Lenovo        | ThinkPad X230 2330A17       | Notebook    | [02280704ba](https://linux-hardware.org/?probe=02280704ba) | May 11, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [cff0fbf297](https://linux-hardware.org/?probe=cff0fbf297) | May 11, 2021 |
| Intel         | NUC7i7BNB J31145-310        | Mini pc     | [08a78a5d61](https://linux-hardware.org/?probe=08a78a5d61) | May 11, 2021 |
| HP            | 15 Notebook PC              | Notebook    | [1c1e7aeecf](https://linux-hardware.org/?probe=1c1e7aeecf) | May 11, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [fcc03f3447](https://linux-hardware.org/?probe=fcc03f3447) | May 11, 2021 |
| MSI           | H170A GAMING PRO            | Desktop     | [a7c97c0108](https://linux-hardware.org/?probe=a7c97c0108) | May 10, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [6410919f51](https://linux-hardware.org/?probe=6410919f51) | May 10, 2021 |
| Positivo      | Q4128C-S                    | Notebook    | [15db0dcbec](https://linux-hardware.org/?probe=15db0dcbec) | May 10, 2021 |
| Positivo B... | VJFE53F11X-XXXXXX           | Notebook    | [bb0d6e1883](https://linux-hardware.org/?probe=bb0d6e1883) | May 10, 2021 |
| HP            | Elite x2 1012 G2            | Tablet      | [d6ab5352b8](https://linux-hardware.org/?probe=d6ab5352b8) | May 10, 2021 |
| AZW           | Z83-V                       | Notebook    | [6ca32efbd7](https://linux-hardware.org/?probe=6ca32efbd7) | May 10, 2021 |
| HP            | ProBook 470 G5              | Notebook    | [22781d64e0](https://linux-hardware.org/?probe=22781d64e0) | May 10, 2021 |
| HP            | 1494                        | Desktop     | [26a35b5f46](https://linux-hardware.org/?probe=26a35b5f46) | May 10, 2021 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [b61a1c61d8](https://linux-hardware.org/?probe=b61a1c61d8) | May 10, 2021 |
| ASUSTek       | ROG STRIX X299-E GAMING ... | Desktop     | [a3a6a201cf](https://linux-hardware.org/?probe=a3a6a201cf) | May 10, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [2910a4173e](https://linux-hardware.org/?probe=2910a4173e) | May 10, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c9b4ee21fd](https://linux-hardware.org/?probe=c9b4ee21fd) | May 10, 2021 |
| Lenovo        | ThinkPad T460s 20FAS0W90... | Notebook    | [c4df22f011](https://linux-hardware.org/?probe=c4df22f011) | May 09, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [a1e5c2f4f5](https://linux-hardware.org/?probe=a1e5c2f4f5) | May 09, 2021 |
| HP            | ProBook 470 G5              | Notebook    | [f66084bbd9](https://linux-hardware.org/?probe=f66084bbd9) | May 09, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [816b6507ca](https://linux-hardware.org/?probe=816b6507ca) | May 09, 2021 |
| HP            | 826A A01                    | All in one  | [c60fceaee4](https://linux-hardware.org/?probe=c60fceaee4) | May 09, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [16ae1580d3](https://linux-hardware.org/?probe=16ae1580d3) | May 09, 2021 |
| HP            | EliteBook 840 G6            | Notebook    | [08d59f23ab](https://linux-hardware.org/?probe=08d59f23ab) | May 09, 2021 |
| ASUSTek       | ProArt B550-CREATOR         | Desktop     | [6969c309d4](https://linux-hardware.org/?probe=6969c309d4) | May 09, 2021 |
| Lenovo        | ThinkPad P1 20MD001VUS      | Notebook    | [23c21ceedf](https://linux-hardware.org/?probe=23c21ceedf) | May 08, 2021 |
| Gigabyte      | H310M H                     | Desktop     | [993800d632](https://linux-hardware.org/?probe=993800d632) | May 08, 2021 |
| Gigabyte      | H87-HD3                     | Desktop     | [ef87a640ab](https://linux-hardware.org/?probe=ef87a640ab) | May 08, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [312ad18259](https://linux-hardware.org/?probe=312ad18259) | May 08, 2021 |
| Biostar       | H81MLC                      | Desktop     | [d8da680e51](https://linux-hardware.org/?probe=d8da680e51) | May 08, 2021 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | Notebook    | [75431661e3](https://linux-hardware.org/?probe=75431661e3) | May 08, 2021 |
| HP            | Laptop 15s-du3xxx           | Notebook    | [25f309da06](https://linux-hardware.org/?probe=25f309da06) | May 08, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | Notebook    | [dc95288d50](https://linux-hardware.org/?probe=dc95288d50) | May 08, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [d20858b78f](https://linux-hardware.org/?probe=d20858b78f) | May 08, 2021 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [20fb29a6ae](https://linux-hardware.org/?probe=20fb29a6ae) | May 08, 2021 |
| Lenovo        | ThinkPad P1 20MD001VUS      | Notebook    | [ec32719d86](https://linux-hardware.org/?probe=ec32719d86) | May 08, 2021 |
| Positivo      | C41TB                       | Notebook    | [060b2d882f](https://linux-hardware.org/?probe=060b2d882f) | May 08, 2021 |
| Dell          | Precision M4600             | Notebook    | [9f1f5b7ef7](https://linux-hardware.org/?probe=9f1f5b7ef7) | May 08, 2021 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [d6af9c1156](https://linux-hardware.org/?probe=d6af9c1156) | May 07, 2021 |
| Lenovo        | IdeaPad 310-14ISK 80UG      | Notebook    | [155ecefe3c](https://linux-hardware.org/?probe=155ecefe3c) | May 07, 2021 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [22aa84909b](https://linux-hardware.org/?probe=22aa84909b) | May 07, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [a0c245e667](https://linux-hardware.org/?probe=a0c245e667) | May 07, 2021 |
| Lenovo        | ThinkPad T460s 20FAS0W90... | Notebook    | [f34f4b2b22](https://linux-hardware.org/?probe=f34f4b2b22) | May 07, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [73fd34e4a9](https://linux-hardware.org/?probe=73fd34e4a9) | May 07, 2021 |
| Acer          | Veriton S2660G              | Desktop     | [31f3a2c202](https://linux-hardware.org/?probe=31f3a2c202) | May 07, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [8d372d62b7](https://linux-hardware.org/?probe=8d372d62b7) | May 07, 2021 |
| Dell          | Latitude 5480               | Notebook    | [05ee730b0f](https://linux-hardware.org/?probe=05ee730b0f) | May 07, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [bdd3604cd8](https://linux-hardware.org/?probe=bdd3604cd8) | May 07, 2021 |
| Toshiba       | Satellite Click Mini L9W... | Notebook    | [b6204cb85d](https://linux-hardware.org/?probe=b6204cb85d) | May 07, 2021 |
| HP            | 1497                        | Desktop     | [bd5ee666bd](https://linux-hardware.org/?probe=bd5ee666bd) | May 07, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [353367c079](https://linux-hardware.org/?probe=353367c079) | May 06, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [c5563f5d49](https://linux-hardware.org/?probe=c5563f5d49) | May 06, 2021 |
| HP            | 1497                        | Desktop     | [e52c3c2489](https://linux-hardware.org/?probe=e52c3c2489) | May 06, 2021 |
| HP            | 1791                        | Desktop     | [ad7ad34a9d](https://linux-hardware.org/?probe=ad7ad34a9d) | May 06, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [a34826ba77](https://linux-hardware.org/?probe=a34826ba77) | May 06, 2021 |
| HP            | EliteBook 850 G3            | Notebook    | [85a71e335a](https://linux-hardware.org/?probe=85a71e335a) | May 06, 2021 |
| Lenovo        | Board                       | Desktop     | [239c4bf44d](https://linux-hardware.org/?probe=239c4bf44d) | May 06, 2021 |
| ASUSTek       | P8H61-M LE R2.0             | Desktop     | [b411cc602f](https://linux-hardware.org/?probe=b411cc602f) | May 06, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [91b671b246](https://linux-hardware.org/?probe=91b671b246) | May 06, 2021 |
| Gigabyte      | B75M-D3P                    | Desktop     | [ab4f7cc66d](https://linux-hardware.org/?probe=ab4f7cc66d) | May 06, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [d186bad578](https://linux-hardware.org/?probe=d186bad578) | May 06, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [9036e74d34](https://linux-hardware.org/?probe=9036e74d34) | May 06, 2021 |
| Unknown       | Unknown                     | Notebook    | [50d2466e84](https://linux-hardware.org/?probe=50d2466e84) | May 06, 2021 |
| Dell          | Latitude 5520               | Notebook    | [3d5b6379e3](https://linux-hardware.org/?probe=3d5b6379e3) | May 06, 2021 |
| Unknown       | Unknown                     | Notebook    | [410d40ca5f](https://linux-hardware.org/?probe=410d40ca5f) | May 06, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [06d44f569d](https://linux-hardware.org/?probe=06d44f569d) | May 06, 2021 |
| Acer          | Aspire E5-576               | Notebook    | [58d3bc658d](https://linux-hardware.org/?probe=58d3bc658d) | May 06, 2021 |
| Acer          | Aspire E5-576               | Notebook    | [ee72676e37](https://linux-hardware.org/?probe=ee72676e37) | May 05, 2021 |
| Dell          | Latitude 5480               | Notebook    | [08f77f376e](https://linux-hardware.org/?probe=08f77f376e) | May 05, 2021 |
| Samsung       | R520/R522/R620              | Notebook    | [bf28931c58](https://linux-hardware.org/?probe=bf28931c58) | May 05, 2021 |
| HP            | ProBook 6460b               | Notebook    | [939b480c49](https://linux-hardware.org/?probe=939b480c49) | May 05, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [ce9091f8ae](https://linux-hardware.org/?probe=ce9091f8ae) | May 05, 2021 |
| HP            | G42                         | Notebook    | [4a107897cf](https://linux-hardware.org/?probe=4a107897cf) | May 05, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [9e64212d9f](https://linux-hardware.org/?probe=9e64212d9f) | May 05, 2021 |
| Dell          | Latitude 7400               | Notebook    | [a32714d409](https://linux-hardware.org/?probe=a32714d409) | May 05, 2021 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [05f84c951f](https://linux-hardware.org/?probe=05f84c951f) | May 05, 2021 |
| Dell          | Latitude 7400               | Notebook    | [eb8ca2d9d2](https://linux-hardware.org/?probe=eb8ca2d9d2) | May 05, 2021 |
| Lenovo        | ThinkPad T450s 20BWS0NS0... | Notebook    | [6c0c3b3ea0](https://linux-hardware.org/?probe=6c0c3b3ea0) | May 05, 2021 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [3d5896459f](https://linux-hardware.org/?probe=3d5896459f) | May 05, 2021 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [f813c25e0d](https://linux-hardware.org/?probe=f813c25e0d) | May 05, 2021 |
| ASUSTek       | P5QL-E                      | Desktop     | [1aee0fab6e](https://linux-hardware.org/?probe=1aee0fab6e) | May 05, 2021 |
| Lenovo        | ThinkPad Edge E145 20BC0... | Notebook    | [035481a413](https://linux-hardware.org/?probe=035481a413) | May 05, 2021 |
| Lenovo        | ThinkPad Edge E535 32607... | Notebook    | [b8627e7f6d](https://linux-hardware.org/?probe=b8627e7f6d) | May 05, 2021 |
| Acer          | Aspire V3-574G              | Notebook    | [507422ce0b](https://linux-hardware.org/?probe=507422ce0b) | May 05, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [1fefa80fdd](https://linux-hardware.org/?probe=1fefa80fdd) | May 05, 2021 |
| MSI           | CX61 2PC                    | Notebook    | [e0f172fbd5](https://linux-hardware.org/?probe=e0f172fbd5) | May 05, 2021 |
| ASUSTek       | ZenBook Q406DA              | Convertible | [9af0cba170](https://linux-hardware.org/?probe=9af0cba170) | May 04, 2021 |
| MSI           | P55-GD80                    | Desktop     | [e9002ad1ad](https://linux-hardware.org/?probe=e9002ad1ad) | May 04, 2021 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [2f8ba8af70](https://linux-hardware.org/?probe=2f8ba8af70) | May 04, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [1d8be54bc6](https://linux-hardware.org/?probe=1d8be54bc6) | May 04, 2021 |
| Fujitsu       | LIFEBOOK E780               | Notebook    | [79dc3442b5](https://linux-hardware.org/?probe=79dc3442b5) | May 04, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | Desktop     | [523fba1dd3](https://linux-hardware.org/?probe=523fba1dd3) | May 04, 2021 |
| Lenovo        | ThinkPad X230 2325BP9       | Notebook    | [6d2bb231a4](https://linux-hardware.org/?probe=6d2bb231a4) | May 04, 2021 |
| Lenovo        | ThinkPad X230 2325BP9       | Notebook    | [1ea17840d1](https://linux-hardware.org/?probe=1ea17840d1) | May 04, 2021 |
| ASRock        | H310CM-HDV/M.2              | Desktop     | [af0ec6cab7](https://linux-hardware.org/?probe=af0ec6cab7) | May 04, 2021 |
| MSI           | B350I PRO AC                | Desktop     | [db10576980](https://linux-hardware.org/?probe=db10576980) | May 04, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [aa18447496](https://linux-hardware.org/?probe=aa18447496) | May 03, 2021 |
| HP            | 3561                        | All in one  | [90e0f93e8d](https://linux-hardware.org/?probe=90e0f93e8d) | May 03, 2021 |
| HP            | 3561                        | All in one  | [740d8be804](https://linux-hardware.org/?probe=740d8be804) | May 03, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [e9c4f5a257](https://linux-hardware.org/?probe=e9c4f5a257) | May 03, 2021 |
| Acer          | Nitro AN515-44              | Notebook    | [c118461e82](https://linux-hardware.org/?probe=c118461e82) | May 03, 2021 |
| Dell          | Latitude E5420              | Notebook    | [989dd7d36f](https://linux-hardware.org/?probe=989dd7d36f) | May 03, 2021 |
| HUAWEI        | EUL-WX9                     | Notebook    | [e59bd99fd2](https://linux-hardware.org/?probe=e59bd99fd2) | May 03, 2021 |
| ordissimo     | E17201                      | Notebook    | [ada3ab54e0](https://linux-hardware.org/?probe=ada3ab54e0) | May 03, 2021 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [3ab07ff020](https://linux-hardware.org/?probe=3ab07ff020) | May 03, 2021 |
| Lenovo        | ThinkPad T580 20LAS3NJ0R    | Notebook    | [11c98724d5](https://linux-hardware.org/?probe=11c98724d5) | May 03, 2021 |
| Lenovo        | ThinkPad T580 20LAS3NJ0R    | Notebook    | [6b88e1bda9](https://linux-hardware.org/?probe=6b88e1bda9) | May 03, 2021 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [fec58faf85](https://linux-hardware.org/?probe=fec58faf85) | May 03, 2021 |
| Dell          | Inspiron 3593               | Notebook    | [4ade35b9d9](https://linux-hardware.org/?probe=4ade35b9d9) | May 02, 2021 |
| MSI           | Bravo 15 A4DDR              | Notebook    | [649dbceeff](https://linux-hardware.org/?probe=649dbceeff) | May 02, 2021 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | Desktop     | [74bff35fdd](https://linux-hardware.org/?probe=74bff35fdd) | May 02, 2021 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | Desktop     | [3551a877a0](https://linux-hardware.org/?probe=3551a877a0) | May 02, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [d0660819a7](https://linux-hardware.org/?probe=d0660819a7) | May 02, 2021 |
| Dell          | XPS 15 9550                 | Notebook    | [30b952e127](https://linux-hardware.org/?probe=30b952e127) | May 02, 2021 |
| HP            | 3029h                       | Desktop     | [f0912110eb](https://linux-hardware.org/?probe=f0912110eb) | May 02, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [fe7a0a48f9](https://linux-hardware.org/?probe=fe7a0a48f9) | May 02, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [1707ff6faf](https://linux-hardware.org/?probe=1707ff6faf) | May 02, 2021 |
| ASUSTek       | ROG STRIX Z370-I GAMING     | Desktop     | [1c48dea9a3](https://linux-hardware.org/?probe=1c48dea9a3) | May 02, 2021 |
| Samsung       | R520/R522/R620              | Notebook    | [95581f21a3](https://linux-hardware.org/?probe=95581f21a3) | May 01, 2021 |
| Lenovo        | ThinkPad 10 2nd 20E4S0UD... | Tablet      | [aae6f982a0](https://linux-hardware.org/?probe=aae6f982a0) | May 01, 2021 |
| HP            | Pavilion dv7                | Notebook    | [98693d2a86](https://linux-hardware.org/?probe=98693d2a86) | May 01, 2021 |
| HP            | Pavilion dv7                | Notebook    | [bd65b55f0a](https://linux-hardware.org/?probe=bd65b55f0a) | May 01, 2021 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [89532532bc](https://linux-hardware.org/?probe=89532532bc) | May 01, 2021 |
| MSI           | P55-GD80                    | Desktop     | [2fc3e6dd6a](https://linux-hardware.org/?probe=2fc3e6dd6a) | May 01, 2021 |
| MSI           | P55-GD80                    | Desktop     | [a950a914fc](https://linux-hardware.org/?probe=a950a914fc) | May 01, 2021 |
| HP            | ProBook 4525s               | Notebook    | [809516ad9a](https://linux-hardware.org/?probe=809516ad9a) | May 01, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [285dfaddb2](https://linux-hardware.org/?probe=285dfaddb2) | May 01, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [857022f167](https://linux-hardware.org/?probe=857022f167) | May 01, 2021 |
| Lenovo        | Yoga 510-14IKB 80VB         | Convertible | [59ec21b8d7](https://linux-hardware.org/?probe=59ec21b8d7) | May 01, 2021 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [a6afe0cc34](https://linux-hardware.org/?probe=a6afe0cc34) | May 01, 2021 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | Notebook    | [0790e842a9](https://linux-hardware.org/?probe=0790e842a9) | May 01, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [e019fb0b7a](https://linux-hardware.org/?probe=e019fb0b7a) | May 01, 2021 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [f15da67866](https://linux-hardware.org/?probe=f15da67866) | May 01, 2021 |
| Biostar       | TB350-BTC                   | Desktop     | [905cd6f7b5](https://linux-hardware.org/?probe=905cd6f7b5) | May 01, 2021 |
| HP            | ProBook 430 G5              | Notebook    | [18081fbf4f](https://linux-hardware.org/?probe=18081fbf4f) | May 01, 2021 |
| Apple         | MacBookPro7,1               | Notebook    | [c00cb7a2c9](https://linux-hardware.org/?probe=c00cb7a2c9) | May 01, 2021 |
| MSI           | MPG B550 GAMING CARBON W... | Desktop     | [ef811a6184](https://linux-hardware.org/?probe=ef811a6184) | May 01, 2021 |
| Lenovo        | ThinkPad T460s 20FAS2BN0... | Notebook    | [8e3b1498da](https://linux-hardware.org/?probe=8e3b1498da) | Apr 30, 2021 |
| MSI           | B365M PRO-VDH               | Desktop     | [e0ff71901e](https://linux-hardware.org/?probe=e0ff71901e) | Apr 30, 2021 |
| ASRock        | H81M-HG4 R4.0               | Desktop     | [3fb3ca76ae](https://linux-hardware.org/?probe=3fb3ca76ae) | Apr 30, 2021 |
| HP            | Laptop 15-db0xxx            | Notebook    | [0b1a312f87](https://linux-hardware.org/?probe=0b1a312f87) | Apr 30, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [2c97753280](https://linux-hardware.org/?probe=2c97753280) | Apr 30, 2021 |
| HP            | ProBook 470 G5              | Notebook    | [f37646891f](https://linux-hardware.org/?probe=f37646891f) | Apr 30, 2021 |
| Lenovo        | SDK0J40700 WIN              | Desktop     | [000925bf4b](https://linux-hardware.org/?probe=000925bf4b) | Apr 30, 2021 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [9f2a73a4d2](https://linux-hardware.org/?probe=9f2a73a4d2) | Apr 30, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [179e39ba13](https://linux-hardware.org/?probe=179e39ba13) | Apr 30, 2021 |
| HP            | ProBook 470 G5              | Notebook    | [b9dbe92598](https://linux-hardware.org/?probe=b9dbe92598) | Apr 30, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [916b016881](https://linux-hardware.org/?probe=916b016881) | Apr 30, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [e66999f076](https://linux-hardware.org/?probe=e66999f076) | Apr 30, 2021 |
| Acer          | Aspire F5-571G              | Notebook    | [5bb52c52af](https://linux-hardware.org/?probe=5bb52c52af) | Apr 30, 2021 |
| Notebook      | PB50_70DFx,DDx              | Notebook    | [e0484075af](https://linux-hardware.org/?probe=e0484075af) | Apr 30, 2021 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [3bb19f53e9](https://linux-hardware.org/?probe=3bb19f53e9) | Apr 30, 2021 |
| Dell          | Latitude 5480               | Notebook    | [a9a63b3679](https://linux-hardware.org/?probe=a9a63b3679) | Apr 30, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3401ccaf08](https://linux-hardware.org/?probe=3401ccaf08) | Apr 30, 2021 |
| HP            | 82F2 A01                    | Desktop     | [abecc29894](https://linux-hardware.org/?probe=abecc29894) | Apr 30, 2021 |
| HP            | 82F2 A01                    | Desktop     | [6c0f1f15f5](https://linux-hardware.org/?probe=6c0f1f15f5) | Apr 30, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | Desktop     | [fcfd291a4f](https://linux-hardware.org/?probe=fcfd291a4f) | Apr 30, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [fb11e4cdcc](https://linux-hardware.org/?probe=fb11e4cdcc) | Apr 29, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [be1fac0a5c](https://linux-hardware.org/?probe=be1fac0a5c) | Apr 29, 2021 |
| Gigabyte      | Z87-D3HP-CF                 | Desktop     | [a93721363c](https://linux-hardware.org/?probe=a93721363c) | Apr 29, 2021 |
| Dell          | Inspiron 13-5378            | Notebook    | [e36e444bac](https://linux-hardware.org/?probe=e36e444bac) | Apr 29, 2021 |
| Gigabyte      | B450 AORUS ELITE V2         | Desktop     | [a09dab9f9b](https://linux-hardware.org/?probe=a09dab9f9b) | Apr 29, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [492d410d60](https://linux-hardware.org/?probe=492d410d60) | Apr 29, 2021 |
| Acer          | Aspire V5-571G              | Notebook    | [89cb767ad1](https://linux-hardware.org/?probe=89cb767ad1) | Apr 29, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [ac1ae66d11](https://linux-hardware.org/?probe=ac1ae66d11) | Apr 29, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [880e12969e](https://linux-hardware.org/?probe=880e12969e) | Apr 29, 2021 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [b4ec0e1cfe](https://linux-hardware.org/?probe=b4ec0e1cfe) | Apr 29, 2021 |
| ASUSTek       | G74Sx                       | Notebook    | [73c1eaa647](https://linux-hardware.org/?probe=73c1eaa647) | Apr 29, 2021 |
| MSI           | GF615M-P33                  | Desktop     | [4219571ca8](https://linux-hardware.org/?probe=4219571ca8) | Apr 29, 2021 |
| ASUSTek       | H110M-K                     | Desktop     | [f323b316a2](https://linux-hardware.org/?probe=f323b316a2) | Apr 29, 2021 |
| HP            | EliteBook 850 G5            | Notebook    | [3b2545921f](https://linux-hardware.org/?probe=3b2545921f) | Apr 29, 2021 |
| HP            | ProBook 4525s               | Notebook    | [78228915c0](https://linux-hardware.org/?probe=78228915c0) | Apr 28, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | Desktop     | [2ff23ca44c](https://linux-hardware.org/?probe=2ff23ca44c) | Apr 28, 2021 |
| System76      | Oryx Pro                    | Notebook    | [8c925dbcbe](https://linux-hardware.org/?probe=8c925dbcbe) | Apr 28, 2021 |
| MSI           | B250 PC MATE                | Desktop     | [4feda9bc8e](https://linux-hardware.org/?probe=4feda9bc8e) | Apr 28, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [b73eecf0c5](https://linux-hardware.org/?probe=b73eecf0c5) | Apr 28, 2021 |
| Medion        | Cattle24 1M                 | Desktop     | [2273e237c4](https://linux-hardware.org/?probe=2273e237c4) | Apr 28, 2021 |
| ASUSTek       | ROG ZENITH EXTREME ALPHA    | Desktop     | [69827caaf1](https://linux-hardware.org/?probe=69827caaf1) | Apr 28, 2021 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [190564ec8e](https://linux-hardware.org/?probe=190564ec8e) | Apr 28, 2021 |
| Lenovo        | ThinkPad T460p 20FXS1SX0... | Notebook    | [267f4b13f7](https://linux-hardware.org/?probe=267f4b13f7) | Apr 28, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [f603a8365a](https://linux-hardware.org/?probe=f603a8365a) | Apr 28, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [e259d34a4c](https://linux-hardware.org/?probe=e259d34a4c) | Apr 28, 2021 |
| Dell          | Inspiron 13-5378            | Notebook    | [9edeb6f6ad](https://linux-hardware.org/?probe=9edeb6f6ad) | Apr 28, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [2a73d602a7](https://linux-hardware.org/?probe=2a73d602a7) | Apr 28, 2021 |
| Lenovo        | ThinkPad T430 2347G2P       | Notebook    | [c1fa54ec47](https://linux-hardware.org/?probe=c1fa54ec47) | Apr 28, 2021 |
| Lenovo        | ThinkPad T460p 20FXS1SX0... | Notebook    | [9595aedbc6](https://linux-hardware.org/?probe=9595aedbc6) | Apr 28, 2021 |
| Fujitsu       | LIFEBOOK AH531/GFO          | Notebook    | [ad0dfb309f](https://linux-hardware.org/?probe=ad0dfb309f) | Apr 27, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [97016e3ff3](https://linux-hardware.org/?probe=97016e3ff3) | Apr 27, 2021 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [c1a5d52c30](https://linux-hardware.org/?probe=c1a5d52c30) | Apr 27, 2021 |
| Lenovo        | ThinkPad E495 20NECTO1WW    | Notebook    | [f67c550f8e](https://linux-hardware.org/?probe=f67c550f8e) | Apr 27, 2021 |
| Lenovo        | ThinkPad E495 20NECTO1WW    | Notebook    | [0876a200b7](https://linux-hardware.org/?probe=0876a200b7) | Apr 27, 2021 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [c3cb8df55c](https://linux-hardware.org/?probe=c3cb8df55c) | Apr 26, 2021 |
| Positivo      | C41TB                       | Notebook    | [1d746150af](https://linux-hardware.org/?probe=1d746150af) | Apr 26, 2021 |
| Chuwi         | CoreBook Pro                | Notebook    | [ca84914f1d](https://linux-hardware.org/?probe=ca84914f1d) | Apr 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [e4b338aa1a](https://linux-hardware.org/?probe=e4b338aa1a) | Apr 25, 2021 |
| Positivo      | C41TB                       | Notebook    | [179c326307](https://linux-hardware.org/?probe=179c326307) | Apr 25, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [7a133af461](https://linux-hardware.org/?probe=7a133af461) | Apr 25, 2021 |
| HP            | 246 G7 Notebook PC          | Notebook    | [a1ab7115cf](https://linux-hardware.org/?probe=a1ab7115cf) | Apr 25, 2021 |
| HP            | Stream 7 Tablet             | Tablet      | [b3a1820a41](https://linux-hardware.org/?probe=b3a1820a41) | Apr 25, 2021 |
| ASRock        | H81M-HG4 R4.0               | Desktop     | [4a7617821f](https://linux-hardware.org/?probe=4a7617821f) | Apr 25, 2021 |
| ASRock        | K10N78D                     | Desktop     | [9b0a7f242b](https://linux-hardware.org/?probe=9b0a7f242b) | Apr 24, 2021 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [573385087f](https://linux-hardware.org/?probe=573385087f) | Apr 24, 2021 |
| Dell          | Latitude 5511               | Notebook    | [4884be79b4](https://linux-hardware.org/?probe=4884be79b4) | Apr 24, 2021 |
| Dell          | Latitude 5511               | Notebook    | [f9f9c1acaa](https://linux-hardware.org/?probe=f9f9c1acaa) | Apr 24, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [140e992105](https://linux-hardware.org/?probe=140e992105) | Apr 24, 2021 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [557ef5a2ae](https://linux-hardware.org/?probe=557ef5a2ae) | Apr 23, 2021 |
| MSI           | Z370-A PRO                  | Desktop     | [470be454f6](https://linux-hardware.org/?probe=470be454f6) | Apr 23, 2021 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [4ea82584ae](https://linux-hardware.org/?probe=4ea82584ae) | Apr 23, 2021 |
| Acer          | One S1003                   | Tablet      | [42b52c70c7](https://linux-hardware.org/?probe=42b52c70c7) | Apr 22, 2021 |
| Acer          | One S1003                   | Tablet      | [16d2bb232b](https://linux-hardware.org/?probe=16d2bb232b) | Apr 22, 2021 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [1c206551a3](https://linux-hardware.org/?probe=1c206551a3) | Apr 22, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [fa4b4edcec](https://linux-hardware.org/?probe=fa4b4edcec) | Apr 22, 2021 |
| eMachines     | EMCP73VT-PM                 | Desktop     | [4e2eabe9ea](https://linux-hardware.org/?probe=4e2eabe9ea) | Apr 21, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [926fa9f69a](https://linux-hardware.org/?probe=926fa9f69a) | Apr 21, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [c4f21a1871](https://linux-hardware.org/?probe=c4f21a1871) | Apr 21, 2021 |
| HP            | EliteBook x360 1030 G2      | Convertible | [d384c6f71c](https://linux-hardware.org/?probe=d384c6f71c) | Apr 21, 2021 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [320bab5ee4](https://linux-hardware.org/?probe=320bab5ee4) | Apr 21, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [ba7a3bd259](https://linux-hardware.org/?probe=ba7a3bd259) | Apr 21, 2021 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [7b5da54a3b](https://linux-hardware.org/?probe=7b5da54a3b) | Apr 20, 2021 |
| MSI           | B350M PRO-VDH               | Desktop     | [50704a4b1b](https://linux-hardware.org/?probe=50704a4b1b) | Apr 20, 2021 |
| ASUSTek       | ZenBook UX481FAY_UX481FA    | Notebook    | [0ec748b06e](https://linux-hardware.org/?probe=0ec748b06e) | Apr 20, 2021 |
| ASUSTek       | ZenBook UX481FAY_UX481FA    | Notebook    | [79ae1f5b0c](https://linux-hardware.org/?probe=79ae1f5b0c) | Apr 20, 2021 |
| Acer          | Nitro AN515-42              | Notebook    | [1b6b0bfcef](https://linux-hardware.org/?probe=1b6b0bfcef) | Apr 20, 2021 |
| Acer          | Nitro AN515-42              | Notebook    | [94173730f8](https://linux-hardware.org/?probe=94173730f8) | Apr 20, 2021 |
| Dell          | Inspiron N5010              | Notebook    | [d54729d43d](https://linux-hardware.org/?probe=d54729d43d) | Apr 20, 2021 |
| Connect       | Tablet 9                    | Notebook    | [6d68fde5d8](https://linux-hardware.org/?probe=6d68fde5d8) | Apr 19, 2021 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [3aa509bfc6](https://linux-hardware.org/?probe=3aa509bfc6) | Apr 19, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [4046940d3e](https://linux-hardware.org/?probe=4046940d3e) | Apr 19, 2021 |
| HP            | Pavilion 15                 | Notebook    | [cb55fa7fcd](https://linux-hardware.org/?probe=cb55fa7fcd) | Apr 19, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [41035d03ea](https://linux-hardware.org/?probe=41035d03ea) | Apr 19, 2021 |
| MPMAN         | MPWIN8900CL                 | Notebook    | [3c21016b82](https://linux-hardware.org/?probe=3c21016b82) | Apr 19, 2021 |
| Dell          | Latitude 7410               | Notebook    | [d2a62b6afb](https://linux-hardware.org/?probe=d2a62b6afb) | Apr 19, 2021 |
| ASUSTek       | TUF Gaming FA506IU_FX506... | Notebook    | [9d9c3e89a5](https://linux-hardware.org/?probe=9d9c3e89a5) | Apr 19, 2021 |
| Insyde        | i71c                        | Notebook    | [ec749b6624](https://linux-hardware.org/?probe=ec749b6624) | Apr 18, 2021 |
| ASUSTek       | X550CA                      | Notebook    | [103cc770c2](https://linux-hardware.org/?probe=103cc770c2) | Apr 18, 2021 |
| Irbis         | TW90                        | Tablet      | [129d1bda9e](https://linux-hardware.org/?probe=129d1bda9e) | Apr 18, 2021 |
| HP            | ProBook 470 G5              | Notebook    | [1f0b5b042f](https://linux-hardware.org/?probe=1f0b5b042f) | Apr 18, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [71cec0648d](https://linux-hardware.org/?probe=71cec0648d) | Apr 18, 2021 |
| TrekStor      | SurfTab wintron 7.0 ST70... | Notebook    | [12af9205b0](https://linux-hardware.org/?probe=12af9205b0) | Apr 18, 2021 |
| HP            | ProBook x360 435 G7         | Convertible | [8648cefc80](https://linux-hardware.org/?probe=8648cefc80) | Apr 18, 2021 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [8aab148f59](https://linux-hardware.org/?probe=8aab148f59) | Apr 17, 2021 |
| Teclast       | TbooK 11                    | Notebook    | [29537c9609](https://linux-hardware.org/?probe=29537c9609) | Apr 17, 2021 |
| ASUSTek       | TUF Gaming FA506IU_FX506... | Notebook    | [f35c55ba89](https://linux-hardware.org/?probe=f35c55ba89) | Apr 17, 2021 |
| HP            | ProBook 4525s               | Notebook    | [5fea2f9652](https://linux-hardware.org/?probe=5fea2f9652) | Apr 17, 2021 |
| Lenovo        | IdeaPad Z580                | Notebook    | [757a310b4a](https://linux-hardware.org/?probe=757a310b4a) | Apr 17, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [2fe3493737](https://linux-hardware.org/?probe=2fe3493737) | Apr 17, 2021 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [4dd2eeb695](https://linux-hardware.org/?probe=4dd2eeb695) | Apr 17, 2021 |
| Lenovo        | ThinkPad X230 2325BP9       | Notebook    | [dc8fb53f61](https://linux-hardware.org/?probe=dc8fb53f61) | Apr 17, 2021 |
| Lenovo        | V330-14ARR 81B1             | Notebook    | [d79109ba72](https://linux-hardware.org/?probe=d79109ba72) | Apr 16, 2021 |
| Acer          | Aspire A315-42              | Notebook    | [f8d626eea1](https://linux-hardware.org/?probe=f8d626eea1) | Apr 16, 2021 |
| Dell          | Latitude 5480               | Notebook    | [ff6578cc63](https://linux-hardware.org/?probe=ff6578cc63) | Apr 16, 2021 |
| Shenzhen P... | MOMO7W                      | Notebook    | [763921a4a1](https://linux-hardware.org/?probe=763921a4a1) | Apr 16, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [0691d30eea](https://linux-hardware.org/?probe=0691d30eea) | Apr 16, 2021 |
| Lenovo        | ThinkPad X230 2325BP9       | Notebook    | [6b2b705578](https://linux-hardware.org/?probe=6b2b705578) | Apr 16, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [414dee060e](https://linux-hardware.org/?probe=414dee060e) | Apr 15, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [099a3d1264](https://linux-hardware.org/?probe=099a3d1264) | Apr 15, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [b5dda74089](https://linux-hardware.org/?probe=b5dda74089) | Apr 14, 2021 |
| Lenovo        | IdeaPad Z580                | Notebook    | [3089a9a333](https://linux-hardware.org/?probe=3089a9a333) | Apr 14, 2021 |
| Dell          | Latitude E6520              | Notebook    | [0283ca3671](https://linux-hardware.org/?probe=0283ca3671) | Apr 13, 2021 |
| Acer          | Aspire A315-55G             | Notebook    | [907647d9a2](https://linux-hardware.org/?probe=907647d9a2) | Apr 13, 2021 |
| Dell          | XPS 13 9360                 | Notebook    | [4b5e9623a8](https://linux-hardware.org/?probe=4b5e9623a8) | Apr 13, 2021 |
| Sony          | VPCSC41FM                   | Notebook    | [b04963620c](https://linux-hardware.org/?probe=b04963620c) | Apr 13, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [8a8adf8790](https://linux-hardware.org/?probe=8a8adf8790) | Apr 12, 2021 |
| Dell          | Inspiron N5010              | Notebook    | [e809ca489d](https://linux-hardware.org/?probe=e809ca489d) | Apr 12, 2021 |
| Lenovo        | ThinkPad X270 20HMS27Q00    | Notebook    | [6a307c820d](https://linux-hardware.org/?probe=6a307c820d) | Apr 12, 2021 |
| HP            | ProBook 4525s               | Notebook    | [e6f339fbf7](https://linux-hardware.org/?probe=e6f339fbf7) | Apr 11, 2021 |
| ASRock        | AB350 Pro4                  | Desktop     | [a0686a3f62](https://linux-hardware.org/?probe=a0686a3f62) | Apr 11, 2021 |
| ASRock        | AB350 Pro4                  | Desktop     | [7e77253d59](https://linux-hardware.org/?probe=7e77253d59) | Apr 11, 2021 |
| Acer          | Swift SF314-55G             | Notebook    | [b9ec42b5ff](https://linux-hardware.org/?probe=b9ec42b5ff) | Apr 11, 2021 |
| Lenovo        | ThinkPad E14 20RACTO1WW     | Notebook    | [a1d56d3f37](https://linux-hardware.org/?probe=a1d56d3f37) | Apr 11, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [8cc623fb70](https://linux-hardware.org/?probe=8cc623fb70) | Apr 10, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [5f52a14994](https://linux-hardware.org/?probe=5f52a14994) | Apr 10, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | Desktop     | [722e60e516](https://linux-hardware.org/?probe=722e60e516) | Apr 10, 2021 |
| Lenovo        | ThinkPad E480 20KNS0MC00    | Notebook    | [92079ca9e3](https://linux-hardware.org/?probe=92079ca9e3) | Apr 10, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [8f5d7459d2](https://linux-hardware.org/?probe=8f5d7459d2) | Apr 10, 2021 |
| Standard      | Unknown                     | Notebook    | [2e2b5648ce](https://linux-hardware.org/?probe=2e2b5648ce) | Apr 09, 2021 |
| Notebook      | N8xEJEK                     | Notebook    | [4794a1ad98](https://linux-hardware.org/?probe=4794a1ad98) | Apr 09, 2021 |
| Lenovo        | ThinkPad T440p 20AN0069U... | Notebook    | [006b564b4d](https://linux-hardware.org/?probe=006b564b4d) | Apr 09, 2021 |
| Intel         | NUC10i5FNB K61361-305       | Mini pc     | [261dc7158d](https://linux-hardware.org/?probe=261dc7158d) | Apr 09, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [a4b4d5abd6](https://linux-hardware.org/?probe=a4b4d5abd6) | Apr 09, 2021 |
| Acer          | Nitro AN515-44              | Notebook    | [c9dcfde4e1](https://linux-hardware.org/?probe=c9dcfde4e1) | Apr 09, 2021 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [0b127087c5](https://linux-hardware.org/?probe=0b127087c5) | Apr 09, 2021 |
| Lenovo        | V310-15IKB 80T3             | Notebook    | [6e1542aab7](https://linux-hardware.org/?probe=6e1542aab7) | Apr 09, 2021 |
| ASUSTek       | H110M-K                     | Desktop     | [b2c194ec6f](https://linux-hardware.org/?probe=b2c194ec6f) | Apr 09, 2021 |
| Lenovo        | ThinkPad T490 20N20009MC    | Notebook    | [4e38c1e886](https://linux-hardware.org/?probe=4e38c1e886) | Apr 09, 2021 |
| Lenovo        | ThinkPad T440p 20AWS2820... | Notebook    | [3440af3ade](https://linux-hardware.org/?probe=3440af3ade) | Apr 09, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [81aeaba043](https://linux-hardware.org/?probe=81aeaba043) | Apr 09, 2021 |
| Lenovo        | Board                       | Desktop     | [d27988d8dd](https://linux-hardware.org/?probe=d27988d8dd) | Apr 09, 2021 |
| HP            | EliteBook x360 830 G6       | Convertible | [c568aa9f2c](https://linux-hardware.org/?probe=c568aa9f2c) | Apr 09, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [4c2971804a](https://linux-hardware.org/?probe=4c2971804a) | Apr 09, 2021 |
| Gigabyte      | Z97N-WIFI                   | Desktop     | [6e9360be26](https://linux-hardware.org/?probe=6e9360be26) | Apr 09, 2021 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [f1bdcd63e8](https://linux-hardware.org/?probe=f1bdcd63e8) | Apr 09, 2021 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [7730367108](https://linux-hardware.org/?probe=7730367108) | Apr 08, 2021 |
| Dell          | Inspiron 3581               | Notebook    | [8acf527693](https://linux-hardware.org/?probe=8acf527693) | Apr 08, 2021 |
| Lenovo        | G40-70 80GA                 | Notebook    | [ca5eaa8733](https://linux-hardware.org/?probe=ca5eaa8733) | Apr 08, 2021 |
| Dell          | 0GWHMW A03                  | Desktop     | [a0ff0f4cf3](https://linux-hardware.org/?probe=a0ff0f4cf3) | Apr 08, 2021 |
| Lenovo        | ThinkPad T440p 20AWS2820... | Notebook    | [352aee7525](https://linux-hardware.org/?probe=352aee7525) | Apr 08, 2021 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [b3b901029c](https://linux-hardware.org/?probe=b3b901029c) | Apr 07, 2021 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [2824275b63](https://linux-hardware.org/?probe=2824275b63) | Apr 07, 2021 |
| SUN MICROS... | ASSY,MOTHERBOARD,X4170 5... | Server      | [8f6e544820](https://linux-hardware.org/?probe=8f6e544820) | Apr 07, 2021 |
| ASUSTek       | X556URK                     | Notebook    | [0fe23f914d](https://linux-hardware.org/?probe=0fe23f914d) | Apr 06, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [035de5bc79](https://linux-hardware.org/?probe=035de5bc79) | Apr 06, 2021 |
| Dell          | XPS L502X                   | Notebook    | [fe680d21e1](https://linux-hardware.org/?probe=fe680d21e1) | Apr 06, 2021 |
| Lenovo        | ThinkPad T490 20N20009MC    | Notebook    | [c40cb2c60f](https://linux-hardware.org/?probe=c40cb2c60f) | Apr 06, 2021 |
| Dell          | Inspiron 5580               | Notebook    | [9f4333693a](https://linux-hardware.org/?probe=9f4333693a) | Apr 06, 2021 |
| Lenovo        | ThinkPad T450s 20BX0013G... | Notebook    | [66d90069a1](https://linux-hardware.org/?probe=66d90069a1) | Apr 06, 2021 |
| Lenovo        | ThinkPad T450s 20BX0013G... | Notebook    | [7441379cc7](https://linux-hardware.org/?probe=7441379cc7) | Apr 06, 2021 |
| MSI           | B350M GAMING PRO            | Desktop     | [de5a14a4f3](https://linux-hardware.org/?probe=de5a14a4f3) | Apr 06, 2021 |
| Toshiba       | Satellite L50-C             | Notebook    | [1baa6a6817](https://linux-hardware.org/?probe=1baa6a6817) | Apr 06, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [7490f0847d](https://linux-hardware.org/?probe=7490f0847d) | Apr 05, 2021 |
| ASUSTek       | Z87-DELUXE                  | Desktop     | [e4f7f8688b](https://linux-hardware.org/?probe=e4f7f8688b) | Apr 05, 2021 |
| Gigabyte      | H87-HD3                     | Desktop     | [a78f2d8699](https://linux-hardware.org/?probe=a78f2d8699) | Apr 05, 2021 |
| Gigabyte      | H310M H x.x                 | Desktop     | [ec750c2771](https://linux-hardware.org/?probe=ec750c2771) | Apr 05, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [07b527d603](https://linux-hardware.org/?probe=07b527d603) | Apr 05, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [914388c5c5](https://linux-hardware.org/?probe=914388c5c5) | Apr 05, 2021 |
| Lenovo        | ThinkPad X1 Extreme 20MG... | Notebook    | [1fe5a2530d](https://linux-hardware.org/?probe=1fe5a2530d) | Apr 05, 2021 |
| Dell          | Latitude 7275               | Tablet      | [7a9c92f242](https://linux-hardware.org/?probe=7a9c92f242) | Apr 05, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [ddfa056734](https://linux-hardware.org/?probe=ddfa056734) | Apr 05, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [051017604f](https://linux-hardware.org/?probe=051017604f) | Apr 04, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [f1c3f62a55](https://linux-hardware.org/?probe=f1c3f62a55) | Apr 04, 2021 |
| Unknown       | Unknown                     | Desktop     | [d38419f785](https://linux-hardware.org/?probe=d38419f785) | Apr 04, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [b865e7ccff](https://linux-hardware.org/?probe=b865e7ccff) | Apr 04, 2021 |
| HP            | Elite x2 1012 G1            | Notebook    | [4957115cec](https://linux-hardware.org/?probe=4957115cec) | Apr 04, 2021 |
| MSI           | GS73VR 7RG                  | Notebook    | [394ae3b96f](https://linux-hardware.org/?probe=394ae3b96f) | Apr 04, 2021 |
| Dell          | XPS L502X                   | Notebook    | [134b59c95e](https://linux-hardware.org/?probe=134b59c95e) | Apr 03, 2021 |
| Dell          | XPS L502X                   | Notebook    | [4b1e34e9ed](https://linux-hardware.org/?probe=4b1e34e9ed) | Apr 03, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | Desktop     | [42b83bbd08](https://linux-hardware.org/?probe=42b83bbd08) | Apr 03, 2021 |
| ASUSTek       | UX303UA                     | Notebook    | [fb33764025](https://linux-hardware.org/?probe=fb33764025) | Apr 03, 2021 |
| ASUSTek       | UX303UA                     | Notebook    | [9c8c52cca9](https://linux-hardware.org/?probe=9c8c52cca9) | Apr 03, 2021 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [0984402bad](https://linux-hardware.org/?probe=0984402bad) | Apr 03, 2021 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [eba80415c0](https://linux-hardware.org/?probe=eba80415c0) | Apr 03, 2021 |
| Dell          | Latitude 3570               | Notebook    | [e83eac31ce](https://linux-hardware.org/?probe=e83eac31ce) | Apr 02, 2021 |
| Lenovo        | IdeaPad Z580                | Notebook    | [5af64d1099](https://linux-hardware.org/?probe=5af64d1099) | Apr 02, 2021 |
| Lenovo        | IdeaPad Z580                | Notebook    | [7dc56a24a6](https://linux-hardware.org/?probe=7dc56a24a6) | Apr 02, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | Desktop     | [9e4b82fb49](https://linux-hardware.org/?probe=9e4b82fb49) | Apr 02, 2021 |
| System76      | Oryx Pro                    | Notebook    | [a2d6163aef](https://linux-hardware.org/?probe=a2d6163aef) | Apr 02, 2021 |
| System76      | Oryx Pro                    | Notebook    | [3b33c626bd](https://linux-hardware.org/?probe=3b33c626bd) | Apr 02, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [ea8316fe72](https://linux-hardware.org/?probe=ea8316fe72) | Apr 01, 2021 |
| Gigabyte      | A520M DS3H                  | Desktop     | [6977cb0073](https://linux-hardware.org/?probe=6977cb0073) | Mar 31, 2021 |
| HP            | EliteBook 755 G2            | Notebook    | [12cd60c247](https://linux-hardware.org/?probe=12cd60c247) | Mar 31, 2021 |
| HUAWEI        | KPL-W0X                     | Notebook    | [af3acea363](https://linux-hardware.org/?probe=af3acea363) | Mar 31, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [e6a1ba54cc](https://linux-hardware.org/?probe=e6a1ba54cc) | Mar 30, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [84cc759796](https://linux-hardware.org/?probe=84cc759796) | Mar 30, 2021 |
| ASUSTek       | H61M-E                      | Desktop     | [fcc9dabb3d](https://linux-hardware.org/?probe=fcc9dabb3d) | Mar 30, 2021 |
| ASUSTek       | H61M-E                      | Desktop     | [ed7f2979b9](https://linux-hardware.org/?probe=ed7f2979b9) | Mar 30, 2021 |
| Dell          | G5 5505                     | Notebook    | [466cbb0b8e](https://linux-hardware.org/?probe=466cbb0b8e) | Mar 30, 2021 |
| HP            | ProBook 4525s               | Notebook    | [390e030b1e](https://linux-hardware.org/?probe=390e030b1e) | Mar 29, 2021 |
| Toshiba       | TECRA Z40-A                 | Notebook    | [9b283640c6](https://linux-hardware.org/?probe=9b283640c6) | Mar 29, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [10b6c6cbc0](https://linux-hardware.org/?probe=10b6c6cbc0) | Mar 29, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [a0ef308b2c](https://linux-hardware.org/?probe=a0ef308b2c) | Mar 29, 2021 |
| Alienware     | 0FRTKJ A00                  | Desktop     | [e31c5f36aa](https://linux-hardware.org/?probe=e31c5f36aa) | Mar 28, 2021 |
| MSI           | Z490-A PRO                  | Desktop     | [cf1b5653e8](https://linux-hardware.org/?probe=cf1b5653e8) | Mar 28, 2021 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [56cafec701](https://linux-hardware.org/?probe=56cafec701) | Mar 28, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [b41b0c2610](https://linux-hardware.org/?probe=b41b0c2610) | Mar 28, 2021 |
| Gigabyte      | H87-HD3                     | Desktop     | [0f0ff492d9](https://linux-hardware.org/?probe=0f0ff492d9) | Mar 27, 2021 |
| Gigabyte      | H87-HD3                     | Desktop     | [87cb9f98e5](https://linux-hardware.org/?probe=87cb9f98e5) | Mar 27, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [6bf5c0b770](https://linux-hardware.org/?probe=6bf5c0b770) | Mar 27, 2021 |
| Dell          | Inspiron 5505               | Notebook    | [9b4af8147c](https://linux-hardware.org/?probe=9b4af8147c) | Mar 26, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [0e12cc8e95](https://linux-hardware.org/?probe=0e12cc8e95) | Mar 25, 2021 |
| Lenovo        | ThinkPad T480s 20L7001RP... | Notebook    | [1992bbf887](https://linux-hardware.org/?probe=1992bbf887) | Mar 24, 2021 |
| HP            | ProBook 4525s               | Notebook    | [e4df2fd0b0](https://linux-hardware.org/?probe=e4df2fd0b0) | Mar 24, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [684313d4d9](https://linux-hardware.org/?probe=684313d4d9) | Mar 24, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [a0f771669c](https://linux-hardware.org/?probe=a0f771669c) | Mar 24, 2021 |
| Lenovo        | ThinkPad T420 4236VD9       | Notebook    | [abaf5a9e37](https://linux-hardware.org/?probe=abaf5a9e37) | Mar 24, 2021 |
| ASUSTek       | UX305FA                     | Notebook    | [4a9ff479d0](https://linux-hardware.org/?probe=4a9ff479d0) | Mar 24, 2021 |
| HP            | Pavilion dm4                | Notebook    | [700de148a7](https://linux-hardware.org/?probe=700de148a7) | Mar 24, 2021 |
| Dell          | Precision 5520              | Notebook    | [f95b93d1ca](https://linux-hardware.org/?probe=f95b93d1ca) | Mar 23, 2021 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [01c43fc8b4](https://linux-hardware.org/?probe=01c43fc8b4) | Mar 23, 2021 |
| MSI           | 760GM-P21                   | Desktop     | [91a13be8c4](https://linux-hardware.org/?probe=91a13be8c4) | Mar 17, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [6124e0aa83](https://linux-hardware.org/?probe=6124e0aa83) | Mar 17, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [07cd9eac56](https://linux-hardware.org/?probe=07cd9eac56) | Mar 17, 2021 |
| HP            | ZBook 15 G3                 | Notebook    | [4ab4d49018](https://linux-hardware.org/?probe=4ab4d49018) | Mar 17, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [25c2dd2a64](https://linux-hardware.org/?probe=25c2dd2a64) | Mar 15, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [1deb9edb46](https://linux-hardware.org/?probe=1deb9edb46) | Mar 14, 2021 |
| Toshiba       | Satellite S55t-B            | Notebook    | [cbabe52a7f](https://linux-hardware.org/?probe=cbabe52a7f) | Mar 10, 2021 |
| Dell          | 0GDJXY A00                  | All in one  | [a9270e1284](https://linux-hardware.org/?probe=a9270e1284) | Mar 06, 2021 |
| Dell          | 0GDJXY A00                  | All in one  | [1297bd9914](https://linux-hardware.org/?probe=1297bd9914) | Mar 06, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [4336742334](https://linux-hardware.org/?probe=4336742334) | Mar 04, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [a758fdf9af](https://linux-hardware.org/?probe=a758fdf9af) | Mar 01, 2021 |
| Gigabyte      | Z490 VISION D               | Desktop     | [0ac71fbeba](https://linux-hardware.org/?probe=0ac71fbeba) | Feb 28, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [6b611bf344](https://linux-hardware.org/?probe=6b611bf344) | Feb 26, 2021 |
| ASUSTek       | PRIME B460-PLUS             | Desktop     | [fdc4baf022](https://linux-hardware.org/?probe=fdc4baf022) | Feb 23, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [86f60bbc44](https://linux-hardware.org/?probe=86f60bbc44) | Feb 23, 2021 |
| ASUSTek       | K53SC                       | Notebook    | [24fe67fa00](https://linux-hardware.org/?probe=24fe67fa00) | Jan 29, 2021 |
| ECS           | MCP61M-M3                   | Desktop     | [445f06dbde](https://linux-hardware.org/?probe=445f06dbde) | Jan 29, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [ce19e3ee18](https://linux-hardware.org/?probe=ce19e3ee18) | Dec 24, 2020 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [e133316a3c](https://linux-hardware.org/?probe=e133316a3c) | Nov 28, 2020 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [f1c5e6588a](https://linux-hardware.org/?probe=f1c5e6588a) | Nov 23, 2020 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [a6e7ec5f07](https://linux-hardware.org/?probe=a6e7ec5f07) | Nov 22, 2020 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [e3a5631517](https://linux-hardware.org/?probe=e3a5631517) | Nov 15, 2020 |
| Lenovo        | ThinkPad X140e 20BLS0040... | Notebook    | [ec056bb102](https://linux-hardware.org/?probe=ec056bb102) | Nov 12, 2020 |
| Dell          | G5 5505                     | Notebook    | [5770e00a83](https://linux-hardware.org/?probe=5770e00a83) | Nov 11, 2020 |
| Lenovo        | ThinkPad X140e 20BLS0040... | Notebook    | [541347d1a0](https://linux-hardware.org/?probe=541347d1a0) | Nov 11, 2020 |
| HP            | Unknown                     | Notebook    | [734dd9e30e](https://linux-hardware.org/?probe=734dd9e30e) | Nov 08, 2020 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [f695c35adf](https://linux-hardware.org/?probe=f695c35adf) | Oct 12, 2020 |
| LG Electro... | 17Z90N-V.AA77G              | Notebook    | [eaeb99f180](https://linux-hardware.org/?probe=eaeb99f180) | Sep 06, 2020 |
| Positivo      | POS-PARS760GCD              | Desktop     | [482e549764](https://linux-hardware.org/?probe=482e549764) | Sep 05, 2020 |
| HP            | Notebook                    | Notebook    | [c5d0ec5edb](https://linux-hardware.org/?probe=c5d0ec5edb) | Aug 30, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                                             | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| 5.11.12-300.fc34.x86_64                             | 109       | 6.4%    |
| 5.13.12-200.fc34.x86_64                             | 99        | 5.81%   |
| 5.12.13-300.fc34.x86_64                             | 79        | 4.64%   |
| 5.12.8-300.fc34.x86_64                              | 60        | 3.52%   |
| 5.11.17-300.fc34.x86_64                             | 56        | 3.29%   |
| 5.11.16-300.fc34.x86_64                             | 56        | 3.29%   |
| 5.13.19-200.fc34.x86_64                             | 55        | 3.23%   |
| 5.14.9-200.fc34.x86_64                              | 53        | 3.11%   |
| 5.12.14-300.fc34.x86_64                             | 53        | 3.11%   |
| 5.13.16-200.fc34.x86_64                             | 50        | 2.94%   |
| 5.13.4-200.fc34.x86_64                              | 47        | 2.76%   |
| 5.13.14-200.fc34.x86_64                             | 47        | 2.76%   |
| 5.12.9-300.fc34.x86_64                              | 46        | 2.7%    |
| 5.13.9-200.fc34.x86_64                              | 44        | 2.58%   |
| 5.13.8-200.fc34.x86_64                              | 42        | 2.47%   |
| 5.11.18-300.fc34.x86_64                             | 41        | 2.41%   |
| 5.13.6-200.fc34.x86_64                              | 40        | 2.35%   |
| 5.12.11-300.fc34.x86_64                             | 40        | 2.35%   |
| 5.11.20-300.fc34.x86_64                             | 40        | 2.35%   |
| 5.11.11-300.fc34.x86_64                             | 39        | 2.29%   |
| 5.12.7-300.fc34.x86_64                              | 37        | 2.17%   |
| 5.12.15-300.fc34.x86_64                             | 37        | 2.17%   |
| 5.12.12-300.fc34.x86_64                             | 36        | 2.11%   |
| 5.14.13-200.fc34.x86_64                             | 34        | 2%      |
| 5.14.11-200.fc34.x86_64                             | 33        | 1.94%   |
| 5.13.13-200.fc34.x86_64                             | 32        | 1.88%   |
| 5.13.10-200.fc34.x86_64                             | 32        | 1.88%   |
| 5.12.6-300.fc34.x86_64                              | 28        | 1.64%   |
| 5.12.10-300.fc34.x86_64                             | 28        | 1.64%   |
| 5.11.15-300.fc34.x86_64                             | 25        | 1.47%   |
| 5.11.19-300.fc34.x86_64                             | 22        | 1.29%   |
| 5.13.15-200.fc34.x86_64                             | 20        | 1.17%   |
| 5.11.3-300.fc34.x86_64                              | 18        | 1.06%   |
| 5.13.5-200.fc34.x86_64                              | 17        | 1%      |
| 5.11.21-300.fc34.x86_64                             | 16        | 0.94%   |
| 5.11.10-300.fc34.x86_64                             | 14        | 0.82%   |
| 5.13.7-200.fc34.x86_64                              | 12        | 0.7%    |
| 5.12.5-300.fc34.x86_64                              | 12        | 0.7%    |
| 5.14.12-200.fc34.x86_64                             | 11        | 0.65%   |
| 5.14.10-200.fc34.x86_64                             | 11        | 0.65%   |
| 5.11.14-300.fc34.x86_64                             | 11        | 0.65%   |
| 5.11.13-300.fc34.x86_64                             | 11        | 0.65%   |
| 5.12.17-300.fc34.x86_64                             | 8         | 0.47%   |
| 5.11.8-300.fc34.x86_64                              | 6         | 0.35%   |
| 5.11.21-300.fc34.aarch64                            | 5         | 0.29%   |
| 5.13.1-300.fc34.x86_64                              | 4         | 0.23%   |
| 5.11.9-300.fc34.x86_64                              | 4         | 0.23%   |
| 5.11.0-156.fc34.x86_64                              | 4         | 0.23%   |
| 5.14.14-200.fc34.x86_64                             | 3         | 0.18%   |
| 5.11.7-300.fc34.x86_64                              | 3         | 0.18%   |
| 5.14.3-300.fc34.x86_64                              | 2         | 0.12%   |
| 5.12.2-300.fc34.x86_64                              | 2         | 0.12%   |
| 5.11.6-300.fc34.x86_64                              | 2         | 0.12%   |
| 5.11.2-300.fc34.x86_64                              | 2         | 0.12%   |
| 5.10.0-0.rc3.68.fc34.x86_64                         | 2         | 0.12%   |
| 5.10.0-0.rc1.20201028gited8780e3f2ec.57.fc34.x86_64 | 2         | 0.12%   |
| 5.9.0-0.rc8.20201009git7575fdda569b.32.fc34.x86_64  | 1         | 0.06%   |
| 5.9.0-0.rc3.1.fc34.x86_64                           | 1         | 0.06%   |
| 5.8.0-1.fc33.x86_64                                 | 1         | 0.06%   |
| 5.4.148-300.fc34.x86_64                             | 1         | 0.06%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11.12 | 109       | 6.4%    |
| 5.13.12 | 101       | 5.93%   |
| 5.12.13 | 80        | 4.7%    |
| 5.12.8  | 61        | 3.58%   |
| 5.13.19 | 57        | 3.35%   |
| 5.11.16 | 57        | 3.35%   |
| 5.11.17 | 56        | 3.29%   |
| 5.14.9  | 55        | 3.23%   |
| 5.12.14 | 55        | 3.23%   |
| 5.13.16 | 51        | 2.99%   |
| 5.13.4  | 48        | 2.82%   |
| 5.13.14 | 48        | 2.82%   |
| 5.12.9  | 46        | 2.7%    |
| 5.13.9  | 45        | 2.64%   |
| 5.13.8  | 43        | 2.52%   |
| 5.12.11 | 42        | 2.47%   |
| 5.13.6  | 41        | 2.41%   |
| 5.11.18 | 41        | 2.41%   |
| 5.11.20 | 40        | 2.35%   |
| 5.11.11 | 39        | 2.29%   |
| 5.12.7  | 38        | 2.23%   |
| 5.12.15 | 38        | 2.23%   |
| 5.12.12 | 36        | 2.11%   |
| 5.14.13 | 34        | 2%      |
| 5.14.11 | 33        | 1.94%   |
| 5.13.13 | 32        | 1.88%   |
| 5.13.10 | 32        | 1.88%   |
| 5.12.10 | 30        | 1.76%   |
| 5.12.6  | 29        | 1.7%    |
| 5.11.15 | 25        | 1.47%   |
| 5.11.19 | 23        | 1.35%   |
| 5.11.21 | 21        | 1.23%   |
| 5.13.15 | 20        | 1.17%   |
| 5.11.3  | 18        | 1.06%   |
| 5.13.5  | 17        | 1%      |
| 5.11.10 | 14        | 0.82%   |
| 5.13.7  | 12        | 0.7%    |
| 5.12.5  | 12        | 0.7%    |
| 5.14.12 | 11        | 0.65%   |
| 5.14.10 | 11        | 0.65%   |
| 5.11.14 | 11        | 0.65%   |
| 5.11.13 | 11        | 0.65%   |
| 5.12.17 | 8         | 0.47%   |
| 5.11.0  | 8         | 0.47%   |
| 5.11.8  | 6         | 0.35%   |
| 5.10.0  | 6         | 0.35%   |
| 5.13.1  | 5         | 0.29%   |
| 5.13.0  | 4         | 0.23%   |
| 5.11.9  | 4         | 0.23%   |
| 5.14.14 | 3         | 0.18%   |
| 5.14.0  | 3         | 0.18%   |
| 5.11.7  | 3         | 0.18%   |
| 5.9.0   | 2         | 0.12%   |
| 5.14.3  | 2         | 0.12%   |
| 5.13.11 | 2         | 0.12%   |
| 5.12.3  | 2         | 0.12%   |
| 5.12.2  | 2         | 0.12%   |
| 5.12.0  | 2         | 0.12%   |
| 5.11.6  | 2         | 0.12%   |
| 5.11.2  | 2         | 0.12%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.13    | 505       | 31.72%  |
| 5.11    | 465       | 29.21%  |
| 5.12    | 450       | 28.27%  |
| 5.14    | 155       | 9.74%   |
| 5.10    | 9         | 0.57%   |
| 5.9     | 2         | 0.13%   |
| 5.4     | 2         | 0.13%   |
| 5.8     | 1         | 0.06%   |
| 5.15    | 1         | 0.06%   |
| 5.1     | 1         | 0.06%   |
| 4.14    | 1         | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1430      | 99.17%  |
| aarch64 | 12        | 0.83%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 1146      | 78.49%  |
| KDE5          | 85        | 5.82%   |
| KDE           | 51        | 3.49%   |
| Unknown       | 51        | 3.49%   |
| X-Cinnamon    | 29        | 1.99%   |
| Cinnamon      | 25        | 1.71%   |
| XFCE          | 22        | 1.51%   |
| MATE          | 21        | 1.44%   |
| GNOME Classic | 5         | 0.34%   |
| sway          | 4         | 0.27%   |
| Deepin        | 4         | 0.27%   |
| LXQt          | 3         | 0.21%   |
| i3            | 3         | 0.21%   |
| openbox       | 2         | 0.14%   |
| LXDE          | 2         | 0.14%   |
| qtile         | 1         | 0.07%   |
| Pantheon      | 1         | 0.07%   |
| NsCDE         | 1         | 0.07%   |
| KDE4          | 1         | 0.07%   |
| dwm           | 1         | 0.07%   |
| Budgie        | 1         | 0.07%   |
| awesome       | 1         | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 933       | 62.96%  |
| X11     | 484       | 32.66%  |
| Tty     | 39        | 2.63%   |
| Unknown | 26        | 1.75%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 804       | 54.62%  |
| GDM     | 525       | 35.67%  |
| SDDM    | 67        | 4.55%   |
| LightDM | 40        | 2.72%   |
| TDM     | 31        | 2.11%   |
| KDM     | 3         | 0.2%    |
| XDM     | 1         | 0.07%   |
| SLiM    | 1         | 0.07%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 737       | 50.76%  |
| en_GB   | 124       | 8.54%   |
| pt_BR   | 78        | 5.37%   |
| ru_RU   | 73        | 5.03%   |
| fr_FR   | 57        | 3.93%   |
| de_DE   | 52        | 3.58%   |
| en_CA   | 33        | 2.27%   |
| en_AU   | 30        | 2.07%   |
| it_IT   | 26        | 1.79%   |
| en_IN   | 23        | 1.58%   |
| es_ES   | 22        | 1.52%   |
| pl_PL   | 17        | 1.17%   |
| cs_CZ   | 12        | 0.83%   |
| es_MX   | 11        | 0.76%   |
| es_CL   | 9         | 0.62%   |
| ru_UA   | 8         | 0.55%   |
| en_NZ   | 7         | 0.48%   |
| en_DK   | 7         | 0.48%   |
| Unknown | 7         | 0.48%   |
| nl_NL   | 6         | 0.41%   |
| ja_JP   | 6         | 0.41%   |
| es_CO   | 6         | 0.41%   |
| C       | 6         | 0.41%   |
| pt_PT   | 5         | 0.34%   |
| nl_BE   | 5         | 0.34%   |
| hu_HU   | 5         | 0.34%   |
| fr_CH   | 5         | 0.34%   |
| fi_FI   | 5         | 0.34%   |
| es_AR   | 5         | 0.34%   |
| en_IE   | 5         | 0.34%   |
| tr_TR   | 4         | 0.28%   |
| es_EC   | 4         | 0.28%   |
| en_SG   | 4         | 0.28%   |
| de_AT   | 4         | 0.28%   |
| da_DK   | 3         | 0.21%   |
| ca_ES   | 3         | 0.21%   |
| zh_TW   | 2         | 0.14%   |
| uk_UA   | 2         | 0.14%   |
| sk_SK   | 2         | 0.14%   |
| ko_KR   | 2         | 0.14%   |
| fr_BE   | 2         | 0.14%   |
| es_DO   | 2         | 0.14%   |
| en_ZA   | 2         | 0.14%   |
| en_PH   | 2         | 0.14%   |
| en_IL   | 2         | 0.14%   |
| el_GR   | 2         | 0.14%   |
| zh_CN   | 1         | 0.07%   |
| sv_SE   | 1         | 0.07%   |
| sr_ME   | 1         | 0.07%   |
| ro_RO   | 1         | 0.07%   |
| nb_NO   | 1         | 0.07%   |
| ms_MY   | 1         | 0.07%   |
| hr_HR   | 1         | 0.07%   |
| fr_CA   | 1         | 0.07%   |
| es_VE   | 1         | 0.07%   |
| es_UY   | 1         | 0.07%   |
| es_PE   | 1         | 0.07%   |
| es_PA   | 1         | 0.07%   |
| es_NI   | 1         | 0.07%   |
| es_GT   | 1         | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1096      | 75.74%  |
| BIOS | 351       | 24.26%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type                | Computers | Percent |
|---------------------|-----------|---------|
| Btrfs               | 1023      | 70.7%   |
| Ext4                | 360       | 24.88%  |
| Xfs                 | 56        | 3.87%   |
| Zfs                 | 2         | 0.14%   |
| Fuse.fuse-overlayfs | 2         | 0.14%   |
| Overlay             | 1         | 0.07%   |
| F2fs                | 1         | 0.07%   |
| Ext3                | 1         | 0.07%   |
| Unknown             | 1         | 0.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 781       | 53.38%  |
| GPT     | 569       | 38.89%  |
| MBR     | 113       | 7.72%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1308      | 90.02%  |
| Yes       | 145       | 9.98%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1176      | 80.99%  |
| Yes       | 276       | 19.01%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Lenovo                      | 301       | 20.87%  |
| ASUSTek Computer            | 212       | 14.7%   |
| Hewlett-Packard             | 185       | 12.83%  |
| Dell                        | 184       | 12.76%  |
| Gigabyte Technology         | 106       | 7.35%   |
| MSI                         | 77        | 5.34%   |
| Acer                        | 61        | 4.23%   |
| ASRock                      | 55        | 3.81%   |
| Apple                       | 37        | 2.57%   |
| Intel                       | 19        | 1.32%   |
| Unknown                     | 17        | 1.18%   |
| HUAWEI                      | 13        | 0.9%    |
| Toshiba                     | 12        | 0.83%   |
| Samsung Electronics         | 10        | 0.69%   |
| Fujitsu                     | 10        | 0.69%   |
| Timi                        | 9         | 0.62%   |
| Notebook                    | 9         | 0.62%   |
| Sony                        | 7         | 0.49%   |
| Raspberry Pi Foundation     | 6         | 0.42%   |
| Positivo                    | 6         | 0.42%   |
| Chuwi                       | 5         | 0.35%   |
| Biostar                     | 5         | 0.35%   |
| Alienware                   | 5         | 0.35%   |
| System76                    | 4         | 0.28%   |
| Microsoft                   | 4         | 0.28%   |
| LG Electronics              | 4         | 0.28%   |
| eMachines                   | 4         | 0.28%   |
| TUXEDO                      | 3         | 0.21%   |
| Pine Microsystems           | 3         | 0.21%   |
| Medion                      | 3         | 0.21%   |
| Huanan                      | 3         | 0.21%   |
| ECS                         | 3         | 0.21%   |
| TrekStor                    | 2         | 0.14%   |
| theobroma-systems           | 2         | 0.14%   |
| Teclast                     | 2         | 0.14%   |
| Supermicro                  | 2         | 0.14%   |
| Standard                    | 2         | 0.14%   |
| SLIMBOOK                    | 2         | 0.14%   |
| Razer                       | 2         | 0.14%   |
| PC Specialist               | 2         | 0.14%   |
| Hampoo                      | 2         | 0.14%   |
| Google                      | 2         | 0.14%   |
| Framework                   | 2         | 0.14%   |
| EVGA                        | 2         | 0.14%   |
| AMI                         | 2         | 0.14%   |
| ZOOSTORM                    | 1         | 0.07%   |
| Wortmann AG                 | 1         | 0.07%   |
| VINGA                       | 1         | 0.07%   |
| SYWZ                        | 1         | 0.07%   |
| SUN MICROSYSTEMS            | 1         | 0.07%   |
| Shenzhen PLOYER electronics | 1         | 0.07%   |
| RCA                         | 1         | 0.07%   |
| Purism                      | 1         | 0.07%   |
| Prestigio                   | 1         | 0.07%   |
| Panasonic                   | 1         | 0.07%   |
| ordissimo                   | 1         | 0.07%   |
| NEC Computers               | 1         | 0.07%   |
| MPMAN                       | 1         | 0.07%   |
| Metabox                     | 1         | 0.07%   |
| Maibenben                   | 1         | 0.07%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                                                                     | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                                  | 20        | 1.39%   |
| ASUS All Series                                                                          | 12        | 0.83%   |
| MSI MS-7C37                                                                              | 9         | 0.62%   |
| Lenovo IdeaPad Flex 5 14ARE05 81X2                                                       | 7         | 0.49%   |
| RPi Raspberry Pi 4 Model B                                                               | 6         | 0.42%   |
| ASUS ROG Zephyrus G14 GA401QM_GA401QM                                                    | 6         | 0.42%   |
| HP Pavilion 15                                                                           | 5         | 0.35%   |
| HP Notebook                                                                              | 5         | 0.35%   |
| Dell XPS 15 9500                                                                         | 5         | 0.35%   |
| Dell XPS 15 7590                                                                         | 5         | 0.35%   |
| Dell Latitude 7490                                                                       | 5         | 0.35%   |
| MSI MS-7C02                                                                              | 4         | 0.28%   |
| Lenovo Yoga 9 14ITL5 82BG                                                                | 4         | 0.28%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWCTO1WW                                               | 4         | 0.28%   |
| HP Pavilion dv7                                                                          | 4         | 0.28%   |
| HP ENVY x360 Convertible 13-ay0xxx                                                       | 4         | 0.28%   |
| Gigabyte B450 I AORUS PRO WIFI                                                           | 4         | 0.28%   |
| Dell Latitude 5480                                                                       | 4         | 0.28%   |
| ASUS TUF GAMING X570-PLUS                                                                | 4         | 0.28%   |
| Apple MacBookPro11,5                                                                     | 4         | 0.28%   |
| Apple MacBookPro11,3                                                                     | 4         | 0.28%   |
| System76 Oryx Pro                                                                        | 3         | 0.21%   |
| MSI MS-7C84                                                                              | 3         | 0.21%   |
| MSI MS-7A38                                                                              | 3         | 0.21%   |
| Lenovo IdeaPad S145-15IWL 81S9                                                           | 3         | 0.21%   |
| Lenovo IdeaPad 5 15ARE05 81YQ                                                            | 3         | 0.21%   |
| Intel H61                                                                                | 3         | 0.21%   |
| HP ProBook 450 G5                                                                        | 3         | 0.21%   |
| HP Pavilion dv6                                                                          | 3         | 0.21%   |
| HP Laptop 15s-eq2xxx                                                                     | 3         | 0.21%   |
| HP Laptop 15-da0xxx                                                                      | 3         | 0.21%   |
| HP EliteBook 840 G6                                                                      | 3         | 0.21%   |
| HP Elite x2 1012 G1                                                                      | 3         | 0.21%   |
| Gigabyte B450M DS3H                                                                      | 3         | 0.21%   |
| Gigabyte A320M-S2H                                                                       | 3         | 0.21%   |
| Dell XPS 15 9550                                                                         | 3         | 0.21%   |
| Dell XPS 13 9350                                                                         | 3         | 0.21%   |
| Dell XPS 13 9310                                                                         | 3         | 0.21%   |
| Dell XPS 13 7390                                                                         | 3         | 0.21%   |
| Dell Latitude 7400                                                                       | 3         | 0.21%   |
| Dell Inspiron N5110                                                                      | 3         | 0.21%   |
| ASUS ZenBook UX431DA_UM431DA                                                             | 3         | 0.21%   |
| ASUS TUF GAMING B550M-PLUS                                                               | 3         | 0.21%   |
| ASUS ROG STRIX X570-E GAMING                                                             | 3         | 0.21%   |
| ASUS ROG STRIX B450-F GAMING                                                             | 3         | 0.21%   |
| ASUS ROG CROSSHAIR VII HERO                                                              | 3         | 0.21%   |
| Acer Aspire E5-573G                                                                      | 3         | 0.21%   |
| Toshiba Satellite L750                                                                   | 2         | 0.14%   |
| Timi A35S                                                                                | 2         | 0.14%   |
| theobroma-systems puma_rk3399                                                            | 2         | 0.14%   |
| SLIMBOOK PROX15-AMD                                                                      | 2         | 0.14%   |
| Samsung 355V4C/355V4X/355V5C/355V5X/356V4C/356V4X/356V5C/356V5X/3445VC/3445VX/3545VC/354 | 2         | 0.14%   |
| Positivo CHT14B                                                                          | 2         | 0.14%   |
| Pine Microsystems Pine64 Pinebook Pro                                                    | 2         | 0.14%   |
| MSI MS-7C91                                                                              | 2         | 0.14%   |
| MSI MS-7C35                                                                              | 2         | 0.14%   |
| MSI MS-7B98                                                                              | 2         | 0.14%   |
| MSI MS-7B85                                                                              | 2         | 0.14%   |
| MSI MS-7B48                                                                              | 2         | 0.14%   |
| MSI MS-7A40                                                                              | 2         | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 162       | 11.23%  |
| Lenovo IdeaPad           | 62        | 4.3%    |
| ASUS ROG                 | 50        | 3.47%   |
| Dell Inspiron            | 49        | 3.4%    |
| Dell XPS                 | 45        | 3.12%   |
| Dell Latitude            | 42        | 2.91%   |
| Acer Aspire              | 40        | 2.77%   |
| HP Pavilion              | 33        | 2.29%   |
| Lenovo Yoga              | 31        | 2.15%   |
| HP EliteBook             | 25        | 1.73%   |
| HP ProBook               | 24        | 1.66%   |
| ASUS PRIME               | 21        | 1.46%   |
| Unknown                  | 20        | 1.39%   |
| ASUS TUF                 | 19        | 1.32%   |
| HP Laptop                | 17        | 1.18%   |
| Dell OptiPlex            | 17        | 1.18%   |
| ASUS VivoBook            | 17        | 1.18%   |
| HP ENVY                  | 16        | 1.11%   |
| Gigabyte B450            | 13        | 0.9%    |
| ASUS All                 | 12        | 0.83%   |
| Dell Precision           | 11        | 0.76%   |
| Apple MacBookPro11       | 11        | 0.76%   |
| Toshiba Satellite        | 10        | 0.69%   |
| MSI MS-7C37              | 9         | 0.62%   |
| ASUS ASUS                | 9         | 0.62%   |
| Lenovo Legion            | 8         | 0.55%   |
| HP ZBook                 | 8         | 0.55%   |
| HP EliteDesk             | 8         | 0.55%   |
| Dell Vostro              | 8         | 0.55%   |
| Lenovo ThinkCentre       | 7         | 0.49%   |
| Lenovo ThinkBook         | 7         | 0.49%   |
| HP Compaq                | 7         | 0.49%   |
| Gigabyte X570            | 7         | 0.49%   |
| ASUS ZenBook             | 7         | 0.49%   |
| Acer Nitro               | 7         | 0.49%   |
| RPi Raspberry            | 6         | 0.42%   |
| Fujitsu LIFEBOOK         | 6         | 0.42%   |
| Acer Swift               | 6         | 0.42%   |
| HP Notebook              | 5         | 0.35%   |
| Gigabyte B450M           | 5         | 0.35%   |
| Dell G5                  | 5         | 0.35%   |
| ASUS P8H61-M             | 5         | 0.35%   |
| MSI MS-7C02              | 4         | 0.28%   |
| Microsoft Surface        | 4         | 0.28%   |
| HP Spectre               | 4         | 0.28%   |
| HP ProDesk               | 4         | 0.28%   |
| HP OMEN                  | 4         | 0.28%   |
| HP Elite                 | 4         | 0.28%   |
| Gigabyte H310M           | 4         | 0.28%   |
| Fujitsu ESPRIMO          | 4         | 0.28%   |
| ASRock X570              | 4         | 0.28%   |
| ASRock B450              | 4         | 0.28%   |
| Timi RedmiBook           | 3         | 0.21%   |
| System76 Oryx            | 3         | 0.21%   |
| Pine Microsystems Pine64 | 3         | 0.21%   |
| Notebook NH5x            | 3         | 0.21%   |
| MSI MS-7C84              | 3         | 0.21%   |
| MSI MS-7A38              | 3         | 0.21%   |
| Intel H61                | 3         | 0.21%   |
| Gigabyte Z390            | 3         | 0.21%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 332       | 23.02%  |
| 2020    | 323       | 22.4%   |
| 2019    | 206       | 14.29%  |
| 2018    | 134       | 9.29%   |
| 2016    | 60        | 4.16%   |
| 2015    | 60        | 4.16%   |
| 2017    | 56        | 3.88%   |
| 2013    | 53        | 3.68%   |
| 2012    | 51        | 3.54%   |
| 2014    | 48        | 3.33%   |
| 2011    | 39        | 2.7%    |
| 2010    | 34        | 2.36%   |
| 2009    | 20        | 1.39%   |
| 2008    | 13        | 0.9%    |
| Unknown | 6         | 0.42%   |
| 2006    | 4         | 0.28%   |
| 2007    | 2         | 0.14%   |
| 2005    | 1         | 0.07%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 840       | 58.25%  |
| Desktop        | 471       | 32.66%  |
| Convertible    | 71        | 4.92%   |
| Tablet         | 17        | 1.18%   |
| Mini pc        | 14        | 0.97%   |
| All in one     | 14        | 0.97%   |
| System on chip | 9         | 0.62%   |
| Server         | 6         | 0.42%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1258      | 86.22%  |
| Enabled  | 201       | 13.78%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1437      | 99.65%  |
| Yes  | 5         | 0.35%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 367       | 25.19%  |
| 4.01-8.0    | 358       | 24.57%  |
| 8.01-16.0   | 275       | 18.87%  |
| 32.01-64.0  | 218       | 14.96%  |
| 3.01-4.0    | 120       | 8.24%   |
| 64.01-256.0 | 49        | 3.36%   |
| 24.01-32.0  | 34        | 2.33%   |
| 1.01-2.0    | 24        | 1.65%   |
| 0.51-1.0    | 7         | 0.48%   |
| 2.01-3.0    | 5         | 0.34%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 431       | 27.31%  |
| 4.01-8.0   | 417       | 26.43%  |
| 3.01-4.0   | 316       | 20.03%  |
| 1.01-2.0   | 244       | 15.46%  |
| 8.01-16.0  | 109       | 6.91%   |
| 0.51-1.0   | 38        | 2.41%   |
| 16.01-24.0 | 13        | 0.82%   |
| 24.01-32.0 | 4         | 0.25%   |
| 0.01-0.5   | 4         | 0.25%   |
| 32.01-64.0 | 2         | 0.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 834       | 57.05%  |
| 2      | 365       | 24.97%  |
| 3      | 147       | 10.05%  |
| 4      | 55        | 3.76%   |
| 5      | 27        | 1.85%   |
| 6      | 13        | 0.89%   |
| 8      | 8         | 0.55%   |
| 0      | 7         | 0.48%   |
| 7      | 3         | 0.21%   |
| 12     | 2         | 0.14%   |
| 9      | 1         | 0.07%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1107      | 76.5%   |
| Yes       | 340       | 23.5%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1140      | 78.62%  |
| No        | 310       | 21.38%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1160      | 80.11%  |
| No        | 288       | 19.89%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1023      | 70.45%  |
| No        | 429       | 29.55%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| USA                | 258       | 17.82%  |
| Brazil             | 112       | 7.73%   |
| Germany            | 96        | 6.63%   |
| Russia             | 76        | 5.25%   |
| France             | 70        | 4.83%   |
| India              | 56        | 3.87%   |
| UK                 | 52        | 3.59%   |
| Netherlands        | 51        | 3.52%   |
| Canada             | 47        | 3.25%   |
| Italy              | 39        | 2.69%   |
| Spain              | 38        | 2.62%   |
| Poland             | 34        | 2.35%   |
| Australia          | 33        | 2.28%   |
| Czechia            | 28        | 1.93%   |
| Ukraine            | 26        | 1.8%    |
| Sweden             | 22        | 1.52%   |
| Belgium            | 20        | 1.38%   |
| Switzerland        | 18        | 1.24%   |
| Portugal           | 18        | 1.24%   |
| Austria            | 18        | 1.24%   |
| Turkey             | 16        | 1.1%    |
| Chile              | 16        | 1.1%    |
| Mexico             | 15        | 1.04%   |
| Argentina          | 14        | 0.97%   |
| Romania            | 13        | 0.9%    |
| Norway             | 13        | 0.9%    |
| Denmark            | 13        | 0.9%    |
| Finland            | 12        | 0.83%   |
| Slovakia           | 11        | 0.76%   |
| New Zealand        | 10        | 0.69%   |
| Colombia           | 10        | 0.69%   |
| Belarus            | 10        | 0.69%   |
| Iran               | 9         | 0.62%   |
| Japan              | 8         | 0.55%   |
| Hungary            | 8         | 0.55%   |
| Estonia            | 8         | 0.55%   |
| China              | 8         | 0.55%   |
| Israel             | 7         | 0.48%   |
| Indonesia          | 6         | 0.41%   |
| Greece             | 6         | 0.41%   |
| South Africa       | 5         | 0.35%   |
| Slovenia           | 5         | 0.35%   |
| Serbia             | 5         | 0.35%   |
| Malaysia           | 5         | 0.35%   |
| Ecuador            | 5         | 0.35%   |
| Bulgaria           | 5         | 0.35%   |
| Vietnam            | 4         | 0.28%   |
| South Korea        | 4         | 0.28%   |
| Philippines        | 4         | 0.28%   |
| Ireland            | 4         | 0.28%   |
| Egypt              | 4         | 0.28%   |
| Taiwan             | 3         | 0.21%   |
| Singapore          | 3         | 0.21%   |
| Pakistan           | 3         | 0.21%   |
| Moldova            | 3         | 0.21%   |
| Lithuania          | 3         | 0.21%   |
| Latvia             | 3         | 0.21%   |
| Dominican Republic | 3         | 0.21%   |
| Croatia            | 3         | 0.21%   |
| Venezuela          | 2         | 0.14%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Moscow         | 26        | 1.74%   |
| Sydney         | 19        | 1.27%   |
| Berlin         | 14        | 0.93%   |
| Madrid         | 13        | 0.87%   |
| Vienna         | 11        | 0.73%   |
| Prague         | 11        | 0.73%   |
| Paris          | 10        | 0.67%   |
| Amsterdam      | 10        | 0.67%   |
| The Hague      | 9         | 0.6%    |
| St Petersburg  | 9         | 0.6%    |
| London         | 9         | 0.6%    |
| Kyiv           | 9         | 0.6%    |
| Denver         | 9         | 0.6%    |
| Istanbul       | 8         | 0.53%   |
| Belo Horizonte | 8         | 0.53%   |
| Yekaterinburg  | 7         | 0.47%   |
| Santiago       | 7         | 0.47%   |
| Minsk          | 7         | 0.47%   |
| Milan          | 7         | 0.47%   |
| Bengaluru      | 7         | 0.47%   |
| Melbourne      | 6         | 0.4%    |
| Kharkiv        | 6         | 0.4%    |
| Buenos Aires   | 6         | 0.4%    |
| Brussels       | 6         | 0.4%    |
| Bratislava     | 6         | 0.4%    |
| Apex           | 6         | 0.4%    |
| Toronto        | 5         | 0.33%   |
| Tel Aviv       | 5         | 0.33%   |
| Tehran         | 5         | 0.33%   |
| Tallinn        | 5         | 0.33%   |
| São Paulo     | 5         | 0.33%   |
| Montreal       | 5         | 0.33%   |
| Lodz           | 5         | 0.33%   |
| Lisbon         | 5         | 0.33%   |
| Fortaleza      | 5         | 0.33%   |
| Dallas         | 5         | 0.33%   |
| Budapest       | 5         | 0.33%   |
| Bucharest      | 5         | 0.33%   |
| Auckland       | 5         | 0.33%   |
| Zurich         | 4         | 0.27%   |
| Wroclaw        | 4         | 0.27%   |
| Rio de Janeiro | 4         | 0.27%   |
| Porto Alegre   | 4         | 0.27%   |
| Portland       | 4         | 0.27%   |
| Oslo           | 4         | 0.27%   |
| Kolkata        | 4         | 0.27%   |
| Helsinki       | 4         | 0.27%   |
| Hamburg        | 4         | 0.27%   |
| Feeding Hills  | 4         | 0.27%   |
| Brampton       | 4         | 0.27%   |
| Basel          | 4         | 0.27%   |
| Athens         | 4         | 0.27%   |
| Zagreb         | 3         | 0.2%    |
| Winnipeg       | 3         | 0.2%    |
| Warsaw         | 3         | 0.2%    |
| Vancouver      | 3         | 0.2%    |
| Ufa            | 3         | 0.2%    |
| Sofia          | 3         | 0.2%    |
| Singapore      | 3         | 0.2%    |
| Sharon         | 3         | 0.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 458       | 737    | 21.07%  |
| WDC                       | 284       | 427    | 13.06%  |
| Seagate                   | 249       | 386    | 11.45%  |
| Toshiba                   | 136       | 181    | 6.26%   |
| Kingston                  | 128       | 157    | 5.89%   |
| SanDisk                   | 113       | 131    | 5.2%    |
| Unknown                   | 89        | 122    | 4.09%   |
| Crucial                   | 89        | 126    | 4.09%   |
| SK Hynix                  | 80        | 97     | 3.68%   |
| Intel                     | 73        | 111    | 3.36%   |
| Hitachi                   | 44        | 61     | 2.02%   |
| Micron Technology         | 37        | 50     | 1.7%    |
| A-DATA Technology         | 29        | 33     | 1.33%   |
| HGST                      | 25        | 38     | 1.15%   |
| Apple                     | 24        | 28     | 1.1%    |
| Phison                    | 20        | 26     | 0.92%   |
| KIOXIA                    | 19        | 29     | 0.87%   |
| Corsair                   | 17        | 23     | 0.78%   |
| SPCC                      | 15        | 20     | 0.69%   |
| Silicon Motion            | 14        | 19     | 0.64%   |
| PNY                       | 14        | 19     | 0.64%   |
| XPG                       | 11        | 13     | 0.51%   |
| Transcend                 | 11        | 11     | 0.51%   |
| OCZ                       | 10        | 15     | 0.46%   |
| Micron/Crucial Technology | 10        | 11     | 0.46%   |
| Union Memory              | 9         | 13     | 0.41%   |
| LITEON                    | 9         | 9      | 0.41%   |
| Gigabyte Technology       | 8         | 9      | 0.37%   |
| Patriot                   | 7         | 8      | 0.32%   |
| LITEONIT                  | 7         | 7      | 0.32%   |
| China                     | 7         | 9      | 0.32%   |
| Team                      | 6         | 7      | 0.28%   |
| Realtek Semiconductor     | 6         | 7      | 0.28%   |
| MAXTOR                    | 5         | 6      | 0.23%   |
| Hewlett-Packard           | 5         | 5      | 0.23%   |
| GOODRAM                   | 5         | 5      | 0.23%   |
| Union Memory (Shenzhen)   | 4         | 9      | 0.18%   |
| SABRENT                   | 4         | 4      | 0.18%   |
| Lite-On                   | 4         | 4      | 0.18%   |
| KingFast                  | 4         | 5      | 0.18%   |
| JMicron                   | 4         | 4      | 0.18%   |
| Intenso                   | 4         | 4      | 0.18%   |
| Solid State Storage       | 3         | 3      | 0.14%   |
| Mushkin                   | 3         | 7      | 0.14%   |
| Lexar                     | 3         | 3      | 0.14%   |
| Lenovo                    | 3         | 3      | 0.14%   |
| KingSpec                  | 3         | 7      | 0.14%   |
| ASMT                      | 3         | 3      | 0.14%   |
| Apacer                    | 3         | 4      | 0.14%   |
| Phison Electronics        | 2         | 3      | 0.09%   |
| MaxDigital                | 2         | 2      | 0.09%   |
| DOGFISH                   | 2         | 2      | 0.09%   |
| BIWIN                     | 2         | 2      | 0.09%   |
| Yangtze Memory            | 1         | 1      | 0.05%   |
| XrayDisk                  | 1         | 1      | 0.05%   |
| WDC WDS2                  | 1         | 1      | 0.05%   |
| W800S                     | 1         | 1      | 0.05%   |
| USB3.0                    | 1         | 1      | 0.05%   |
| USB 3.0                   | 1         | 1      | 0.05%   |
| UNIC2                     | 1         | 1      | 0.05%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Samsung PM963 2.5" NVMe PCIe SSD 512GB | 38        | 1.54%   |
| Samsung SSD 860 EVO 500GB              | 31        | 1.25%   |
| Samsung NVMe SSD Drive 500GB           | 30        | 1.21%   |
| Samsung NVMe SSD Drive 1TB             | 30        | 1.21%   |
| Kingston SA400S37240G 240GB SSD        | 27        | 1.09%   |
| Samsung SSD 860 EVO 1TB                | 26        | 1.05%   |
| Samsung NVMe SSD Drive 256GB           | 23        | 0.93%   |
| Seagate ST1000LM035-1RK172 1TB         | 21        | 0.85%   |
| Samsung SSD 850 EVO 250GB              | 19        | 0.77%   |
| Kingston SA400S37480G 480GB SSD        | 18        | 0.73%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 17        | 0.69%   |
| Samsung SSD 850 EVO 500GB              | 17        | 0.69%   |
| Seagate ST2000DM008-2FR102 2TB         | 16        | 0.65%   |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB | 15        | 0.61%   |
| Kingston SA400S37120G 120GB SSD        | 15        | 0.61%   |
| Sandisk NVMe SSD Drive 512GB           | 14        | 0.57%   |
| Samsung NVMe SSD Drive 1024GB          | 14        | 0.57%   |
| Toshiba NVMe SSD Drive 512GB           | 13        | 0.53%   |
| Sandisk NVMe SSD Drive 500GB           | 13        | 0.53%   |
| Samsung SSD 970 EVO Plus 1TB           | 13        | 0.53%   |
| Samsung SSD 860 EVO 250GB              | 13        | 0.53%   |
| Crucial CT500MX500SSD1 500GB           | 13        | 0.53%   |
| Unknown SD/MMC/MS PRO 128GB            | 12        | 0.49%   |
| SK Hynix NVMe SSD Drive 512GB          | 12        | 0.49%   |
| Seagate ST1000DM010-2EP102 1TB         | 12        | 0.49%   |
| Intel NVMe SSD Drive 512GB             | 12        | 0.49%   |
| Unknown MMC Card  32GB                 | 11        | 0.44%   |
| Toshiba DT01ACA100 1TB                 | 11        | 0.44%   |
| Samsung SSD 860 QVO 1TB                | 11        | 0.44%   |
| Crucial CT1000MX500SSD1 1TB            | 11        | 0.44%   |
| Seagate ST500DM002-1BD142 500GB        | 10        | 0.4%    |
| Samsung SSD 970 EVO Plus 500GB         | 10        | 0.4%    |
| Samsung SSD 970 EVO 500GB              | 10        | 0.4%    |
| WDC WD20EZRZ-00Z5HB0 2TB               | 9         | 0.36%   |
| Seagate ST1000LM049-2GH172 1TB         | 9         | 0.36%   |
| Seagate Expansion 1TB                  | 9         | 0.36%   |
| Samsung SSD 980 PRO 1TB                | 9         | 0.36%   |
| Samsung SSD 970 EVO 1TB                | 9         | 0.36%   |
| Unknown MMC Card  64GB                 | 8         | 0.32%   |
| Unknown MMC Card  128GB                | 8         | 0.32%   |
| Toshiba NVMe SSD Drive 256GB           | 8         | 0.32%   |
| Seagate ST4000DM004-2CV104 4TB         | 8         | 0.32%   |
| Sandisk NVMe SSD Drive 256GB           | 8         | 0.32%   |
| Samsung NVMe SSD Drive 2TB             | 8         | 0.32%   |
| Micron/Crucial NVMe SSD Drive 1TB      | 8         | 0.32%   |
| Crucial CT240BX500SSD1 240GB           | 8         | 0.32%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 7         | 0.28%   |
| Toshiba MQ01ABD100 1TB                 | 7         | 0.28%   |
| Toshiba DT01ACA200 2TB                 | 7         | 0.28%   |
| SK Hynix NVMe SSD Drive 256GB          | 7         | 0.28%   |
| Seagate ST3500418AS 500GB              | 7         | 0.28%   |
| Sandisk NVMe SSD Drive 1024GB          | 7         | 0.28%   |
| Samsung SSD 970 EVO Plus 2TB           | 7         | 0.28%   |
| Samsung SSD 840 EVO 250GB              | 7         | 0.28%   |
| Kingston SV300S37A120G 120GB SSD       | 7         | 0.28%   |
| WDC WDS500G2B0B-00YS70 500GB SSD       | 6         | 0.24%   |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 6         | 0.24%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD       | 6         | 0.24%   |
| WDC WDS100T2B0C-00PXH0 1TB             | 6         | 0.24%   |
| WDC WD10SPZX-21Z10T0 1TB               | 6         | 0.24%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 240       | 368    | 38.1%   |
| WDC                 | 193       | 303    | 30.63%  |
| Toshiba             | 67        | 97     | 10.63%  |
| Hitachi             | 44        | 61     | 6.98%   |
| HGST                | 25        | 38     | 3.97%   |
| Samsung Electronics | 22        | 36     | 3.49%   |
| Unknown             | 13        | 14     | 2.06%   |
| Apple               | 5         | 5      | 0.79%   |
| SABRENT             | 4         | 4      | 0.63%   |
| MAXTOR              | 3         | 3      | 0.48%   |
| MaxDigital          | 2         | 2      | 0.32%   |
| JMicron             | 2         | 2      | 0.32%   |
| Hewlett-Packard     | 2         | 2      | 0.32%   |
| USB3.0              | 1         | 1      | 0.16%   |
| USB 3.0             | 1         | 1      | 0.16%   |
| Synology            | 1         | 1      | 0.16%   |
| PHD 3.0             | 1         | 1      | 0.16%   |
| Magnetic Data       | 1         | 1      | 0.16%   |
| Inateck             | 1         | 1      | 0.16%   |
| Fujitsu             | 1         | 1      | 0.16%   |
| ASMT106x            | 1         | 1      | 0.16%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 215       | 323    | 27.67%  |
| Kingston            | 97        | 119    | 12.48%  |
| Crucial             | 78        | 113    | 10.04%  |
| SanDisk             | 62        | 74     | 7.98%   |
| WDC                 | 48        | 58     | 6.18%   |
| Intel               | 27        | 43     | 3.47%   |
| A-DATA Technology   | 24        | 27     | 3.09%   |
| Toshiba             | 22        | 24     | 2.83%   |
| Micron Technology   | 21        | 24     | 2.7%    |
| SK Hynix            | 14        | 15     | 1.8%    |
| PNY                 | 14        | 18     | 1.8%    |
| Apple               | 14        | 16     | 1.8%    |
| SPCC                | 10        | 15     | 1.29%   |
| OCZ                 | 10        | 15     | 1.29%   |
| Transcend           | 8         | 8      | 1.03%   |
| LITEON              | 8         | 8      | 1.03%   |
| Corsair             | 8         | 9      | 1.03%   |
| LITEONIT            | 7         | 7      | 0.9%    |
| China               | 7         | 9      | 0.9%    |
| Team                | 6         | 7      | 0.77%   |
| Patriot             | 6         | 6      | 0.77%   |
| Unknown             | 5         | 5      | 0.64%   |
| GOODRAM             | 5         | 5      | 0.64%   |
| Gigabyte Technology | 5         | 6      | 0.64%   |
| Intenso             | 4         | 4      | 0.51%   |
| Mushkin             | 3         | 7      | 0.39%   |
| Lexar               | 3         | 3      | 0.39%   |
| KingSpec            | 3         | 7      | 0.39%   |
| ASMT                | 3         | 3      | 0.39%   |
| Apacer              | 3         | 4      | 0.39%   |
| Seagate             | 2         | 2      | 0.26%   |
| MAXTOR              | 2         | 3      | 0.26%   |
| Hewlett-Packard     | 2         | 2      | 0.26%   |
| DOGFISH             | 2         | 2      | 0.26%   |
| WDC WDS2            | 1         | 1      | 0.13%   |
| W800S               | 1         | 1      | 0.13%   |
| Union Memory        | 1         | 1      | 0.13%   |
| UNIC2               | 1         | 1      | 0.13%   |
| TEXTORM             | 1         | 1      | 0.13%   |
| TCSUNBOW            | 1         | 1      | 0.13%   |
| Smartbuy            | 1         | 1      | 0.13%   |
| SMART               | 1         | 1      | 0.13%   |
| Radeon              | 1         | 1      | 0.13%   |
| PLEXTOR             | 1         | 2      | 0.13%   |
| OWC                 | 1         | 1      | 0.13%   |
| OCZ-ARC1            | 1         | 1      | 0.13%   |
| NGFF                | 1         | 2      | 0.13%   |
| Netac               | 1         | 1      | 0.13%   |
| MG                  | 1         | 1      | 0.13%   |
| Leven               | 1         | 1      | 0.13%   |
| KLEVV               | 1         | 1      | 0.13%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.13%   |
| KingFast            | 1         | 1      | 0.13%   |
| Indilinx            | 1         | 1      | 0.13%   |
| Hoodisk             | 1         | 2      | 0.13%   |
| GALAX               | 1         | 1      | 0.13%   |
| EMTEC               | 1         | 1      | 0.13%   |
| DREVO               | 1         | 1      | 0.13%   |
| CT1000P1            | 1         | 2      | 0.13%   |
| BRAVEEAGLE          | 1         | 1      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 684       | 1024   | 34.69%  |
| NVMe    | 674       | 975    | 34.18%  |
| HDD     | 516       | 943    | 26.17%  |
| MMC     | 75        | 106    | 3.8%    |
| Unknown | 23        | 29     | 1.17%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 939       | 1896   | 53.08%  |
| NVMe | 674       | 974    | 38.1%   |
| SAS  | 81        | 101    | 4.58%   |
| MMC  | 75        | 106    | 4.24%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 686       | 1080   | 54.14%  |
| 0.51-1.0   | 388       | 585    | 30.62%  |
| 1.01-2.0   | 108       | 154    | 8.52%   |
| 3.01-4.0   | 35        | 57     | 2.76%   |
| 4.01-10.0  | 25        | 55     | 1.97%   |
| 2.01-3.0   | 20        | 25     | 1.58%   |
| 10.01-20.0 | 4         | 10     | 0.32%   |
| 0          | 1         | 1      | 0.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 309       | 20.82%  |
| 251-500        | 270       | 18.19%  |
| 101-250        | 213       | 14.35%  |
| 1001-2000      | 187       | 12.6%   |
| 1-20           | 158       | 10.65%  |
| Unknown        | 121       | 8.15%   |
| More than 3000 | 85        | 5.73%   |
| 2001-3000      | 55        | 3.71%   |
| 51-100         | 55        | 3.71%   |
| 21-50          | 31        | 2.09%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 413       | 27.01%  |
| 21-50          | 233       | 15.24%  |
| 101-250        | 229       | 14.98%  |
| 51-100         | 158       | 10.33%  |
| 251-500        | 154       | 10.07%  |
| 501-1000       | 134       | 8.76%   |
| Unknown        | 121       | 7.91%   |
| 1001-2000      | 52        | 3.4%    |
| More than 3000 | 24        | 1.57%   |
| 2001-3000      | 11        | 0.72%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                     | 3         | 15     | 3.19%   |
| Seagate ST1000LM035-1RK172 1TB                      | 3         | 3      | 3.19%   |
| Intel SSDSC2CT120A3 120GB                           | 3         | 9      | 3.19%   |
| WDC WD1003FBYX-01Y7B1 1TB                           | 2         | 2      | 2.13%   |
| Toshiba DT01ACA200 2TB                              | 2         | 4      | 2.13%   |
| Seagate ST31000524AS 1TB                            | 2         | 2      | 2.13%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 2         | 2      | 2.13%   |
| Kingston SA400S37240G 240GB SSD                     | 2         | 2      | 2.13%   |
| HGST HTS725050A7E630 500GB                          | 2         | 2      | 2.13%   |
| Crucial CT1050MX300SSD1 1TB                         | 2         | 4      | 2.13%   |
| WDC WD60EFAX-68SHWN0 6TB                            | 1         | 1      | 1.06%   |
| WDC WD5000BEVT-22A0RT0 500GB                        | 1         | 1      | 1.06%   |
| WDC WD40PURZ-85AKKY0 4TB                            | 1         | 1      | 1.06%   |
| WDC WD3200BPVT-75ZEST0 320GB                        | 1         | 1      | 1.06%   |
| WDC WD3200BPVT-24JJ5T0 320GB                        | 1         | 1      | 1.06%   |
| WDC WD30EZRX-00AZ6B0 3TB                            | 1         | 1      | 1.06%   |
| WDC WD20EFRX-68AX9N0 2TB                            | 1         | 1      | 1.06%   |
| WDC WD1600AVVS-63L2B0 160GB                         | 1         | 1      | 1.06%   |
| WDC WD15EARS-00Z5B1 1TB                             | 1         | 1      | 1.06%   |
| WDC WD10SPZX-24Z10 1TB                              | 1         | 1      | 1.06%   |
| WDC WD10JPVX-75JC3T0 1TB                            | 1         | 1      | 1.06%   |
| WDC WD10EZEX-60WN4A1 1TB                            | 1         | 1      | 1.06%   |
| WDC WD1002FAEX-00Y9A0 1TB                           | 1         | 1      | 1.06%   |
| Union Memory UMIS RPJTJ128MED1MWX 128GB             | 1         | 1      | 1.06%   |
| Toshiba MQ01ABD100 1TB                              | 1         | 1      | 1.06%   |
| Toshiba MQ01ABD050V 500GB                           | 1         | 1      | 1.06%   |
| SPCC Solid State Disk 256GB                         | 1         | 1      | 1.06%   |
| SK Hynix PC401 NVMe 1TB                             | 1         | 1      | 1.06%   |
| SK Hynix HFS256G39TND-N210A 256GB SSD               | 1         | 1      | 1.06%   |
| Seagate ST9250315AS 250GB                           | 1         | 1      | 1.06%   |
| Seagate ST500LM021-1KJ152 500GB                     | 1         | 1      | 1.06%   |
| Seagate ST500DM002-1SB10A 500GB                     | 1         | 1      | 1.06%   |
| Seagate ST4000DM000-1F2168 4TB                      | 1         | 1      | 1.06%   |
| Seagate ST3500630AS 500GB                           | 1         | 1      | 1.06%   |
| Seagate ST3500418AS 500GB                           | 1         | 2      | 1.06%   |
| Seagate ST31000340NS 1TB                            | 1         | 1      | 1.06%   |
| Seagate ST1000LM049-2GH172 1TB                      | 1         | 2      | 1.06%   |
| Seagate ST1000DX001-1CM162 1TB                      | 1         | 1      | 1.06%   |
| Seagate ST1000DM010-2EP102 1TB                      | 1         | 1      | 1.06%   |
| SanDisk SSD U100 64GB                               | 1         | 1      | 1.06%   |
| SanDisk SSD PLUS 480GB                              | 1         | 1      | 1.06%   |
| SanDisk SSD PLUS 240GB                              | 1         | 1      | 1.06%   |
| SanDisk SDSSDX240GG25 240GB                         | 1         | 1      | 1.06%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD                 | 1         | 1      | 1.06%   |
| Samsung Electronics SSD 970 EVO 1TB                 | 1         | 1      | 1.06%   |
| Samsung Electronics SSD 860 EVO 250GB               | 1         | 1      | 1.06%   |
| Samsung Electronics SP2514N 250GB                   | 1         | 1      | 1.06%   |
| Samsung Electronics SP2004C 200GB                   | 1         | 1      | 1.06%   |
| Samsung Electronics SP1614C 160GB                   | 1         | 1      | 1.06%   |
| Samsung Electronics HM160HI 160GB                   | 1         | 3      | 1.06%   |
| Samsung Electronics HD501LJ 500GB                   | 1         | 8      | 1.06%   |
| Samsung Electronics HD322HJ 320GB                   | 1         | 1      | 1.06%   |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1      | 1.06%   |
| Micron Technology 1100_MTFDDAK256TBN 256GB SSD      | 1         | 1      | 1.06%   |
| LITEONIT LCS-128M6S-HP 128GB SSD                    | 1         | 1      | 1.06%   |
| LITEON LGH-512V2G-11 M.2 2280 512GB SSD             | 1         | 1      | 1.06%   |
| Kingston SV300S37A120G 120GB SSD                    | 1         | 1      | 1.06%   |
| Kingston SUV400S37240G 240GB SSD                    | 1         | 1      | 1.06%   |
| Intel SSDSCKJF180A5L 180GB                          | 1         | 1      | 1.06%   |
| Intel SSDSC2KF480H6L 480GB                          | 1         | 1      | 1.06%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 20        | 34     | 21.28%  |
| WDC                 | 15        | 15     | 15.96%  |
| Samsung Electronics | 8         | 17     | 8.51%   |
| Intel               | 8         | 14     | 8.51%   |
| Hitachi             | 8         | 8      | 8.51%   |
| SanDisk             | 5         | 5      | 5.32%   |
| Crucial             | 5         | 7      | 5.32%   |
| Toshiba             | 4         | 6      | 4.26%   |
| Kingston            | 4         | 4      | 4.26%   |
| HGST                | 4         | 4      | 4.26%   |
| A-DATA Technology   | 3         | 4      | 3.19%   |
| SK Hynix            | 2         | 2      | 2.13%   |
| Micron Technology   | 2         | 2      | 2.13%   |
| Union Memory        | 1         | 1      | 1.06%   |
| SPCC                | 1         | 1      | 1.06%   |
| LITEONIT            | 1         | 1      | 1.06%   |
| LITEON              | 1         | 1      | 1.06%   |
| Hewlett-Packard     | 1         | 1      | 1.06%   |
| Fujitsu             | 1         | 1      | 1.06%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 20        | 34     | 33.9%   |
| WDC                 | 15        | 15     | 25.42%  |
| Hitachi             | 8         | 8      | 13.56%  |
| Samsung Electronics | 6         | 15     | 10.17%  |
| Toshiba             | 4         | 6      | 6.78%   |
| HGST                | 4         | 4      | 6.78%   |
| Hewlett-Packard     | 1         | 1      | 1.69%   |
| Fujitsu             | 1         | 1      | 1.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 56        | 84     | 61.54%  |
| SSD  | 29        | 38     | 31.87%  |
| NVMe | 6         | 6      | 6.59%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| WDC PC SN520 SDAPMUW-512G-1001 512GB | 1         | 1      | 50%     |
| Hitachi HDS721010DLE630 1TB          | 1         | 6      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Hitachi | 1         | 6      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 863       | 1741   | 54.11%  |
| Works    | 642       | 1201   | 40.25%  |
| Malfunc  | 88        | 128    | 5.52%   |
| Failed   | 2         | 7      | 0.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 840       | 43.46%  |
| AMD                            | 313       | 16.19%  |
| Samsung Electronics            | 280       | 14.49%  |
| Sandisk                        | 102       | 5.28%   |
| SK Hynix                       | 60        | 3.1%    |
| Toshiba America Info Systems   | 46        | 2.38%   |
| Phison Electronics             | 37        | 1.91%   |
| ASMedia Technology             | 34        | 1.76%   |
| Kingston Technology Company    | 33        | 1.71%   |
| Micron/Crucial Technology      | 21        | 1.09%   |
| KIOXIA                         | 21        | 1.09%   |
| Silicon Motion                 | 18        | 0.93%   |
| Micron Technology              | 17        | 0.88%   |
| ADATA Technology               | 14        | 0.72%   |
| Union Memory (Shenzhen)        | 13        | 0.67%   |
| Nvidia                         | 12        | 0.62%   |
| Marvell Technology Group       | 10        | 0.52%   |
| JMicron Technology             | 9         | 0.47%   |
| Realtek Semiconductor          | 7         | 0.36%   |
| Broadcom / LSI                 | 6         | 0.31%   |
| Seagate Technology             | 5         | 0.26%   |
| Lite-On Technology             | 5         | 0.26%   |
| LSI Logic / Symbios Logic      | 4         | 0.21%   |
| Apple                          | 4         | 0.21%   |
| Solid State Storage Technology | 3         | 0.16%   |
| Lenovo                         | 3         | 0.16%   |
| Adaptec                        | 3         | 0.16%   |
| VIA Technologies               | 2         | 0.1%    |
| ULi Electronics                | 2         | 0.1%    |
| Silicon Image                  | 2         | 0.1%    |
| Hewlett-Packard                | 2         | 0.1%    |
| Yangtze Memory Technologies    | 1         | 0.05%   |
| Unknown                        | 1         | 0.05%   |
| Shenzhen Longsys Electronics   | 1         | 0.05%   |
| Lite-On IT Corp. / Plextor     | 1         | 0.05%   |
| Enmotus                        | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 248       | 11.61%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 170       | 7.96%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 114       | 5.34%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 57        | 2.67%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 56        | 2.62%   |
| AMD 400 Series Chipset SATA Controller                                         | 53        | 2.48%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 40        | 1.87%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 40        | 1.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 40        | 1.87%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 36        | 1.69%   |
| Samsung NVMe SSD Controller 980                                                | 35        | 1.64%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 33        | 1.54%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 33        | 1.54%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 33        | 1.54%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                     | 32        | 1.5%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 32        | 1.5%    |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                       | 30        | 1.4%    |
| Intel Volume Management Device NVMe RAID Controller                            | 29        | 1.36%   |
| Intel Comet Lake SATA AHCI Controller                                          | 26        | 1.22%   |
| Sandisk WD Blue SN550 NVMe SSD                                                 | 25        | 1.17%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 25        | 1.17%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 24        | 1.12%   |
| Intel SATA Controller [RAID mode]                                              | 23        | 1.08%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 22        | 1.03%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 21        | 0.98%   |
| KIOXIA Non-Volatile memory controller                                          | 21        | 0.98%   |
| Intel SSD 660P Series                                                          | 21        | 0.98%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 21        | 0.98%   |
| Phison E12 NVMe Controller                                                     | 20        | 0.94%   |
| SK Hynix Gold P31 SSD                                                          | 19        | 0.89%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 19        | 0.89%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 19        | 0.89%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 17        | 0.8%    |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 16        | 0.75%   |
| Micron Non-Volatile memory controller                                          | 16        | 0.75%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 16        | 0.75%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 15        | 0.7%    |
| Kingston Company A2000 NVMe SSD                                                | 15        | 0.7%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 15        | 0.7%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 14        | 0.66%   |
| SK Hynix Non-Volatile memory controller                                        | 13        | 0.61%   |
| SK Hynix BC511                                                                 | 13        | 0.61%   |
| Phison E16 PCIe4 NVMe Controller                                               | 13        | 0.61%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 13        | 0.61%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 13        | 0.61%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 13        | 0.61%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 13        | 0.61%   |
| AMD FCH SATA Controller D                                                      | 13        | 0.61%   |
| AMD 300 Series Chipset SATA Controller                                         | 13        | 0.61%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 13        | 0.61%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 12        | 0.56%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 12        | 0.56%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                | 12        | 0.56%   |
| Sandisk Non-Volatile memory controller                                         | 11        | 0.51%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 11        | 0.51%   |
| SK Hynix BC501 NVMe Solid State Drive                                          | 10        | 0.47%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 10        | 0.47%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 10        | 0.47%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 9         | 0.42%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 9         | 0.42%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1013      | 53.46%  |
| NVMe | 671       | 35.41%  |
| RAID | 116       | 6.12%   |
| IDE  | 87        | 4.59%   |
| SCSI | 6         | 0.32%   |
| SAS  | 2         | 0.11%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 1030      | 71.43%  |
| AMD      | 400       | 27.74%  |
| ARM      | 11        | 0.76%   |
| QUALCOMM | 1         | 0.07%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 30        | 2.08%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 23        | 1.59%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 22        | 1.52%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 21        | 1.46%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 19        | 1.32%   |
| AMD Ryzen 5 3600 6-Core Processor             | 19        | 1.32%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 18        | 1.25%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 18        | 1.25%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 17        | 1.18%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 17        | 1.18%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 16        | 1.11%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 16        | 1.11%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 16        | 1.11%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 16        | 1.11%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 14        | 0.97%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 14        | 0.97%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 13        | 0.9%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 13        | 0.9%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 13        | 0.9%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 13        | 0.9%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 12        | 0.83%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 12        | 0.83%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 12        | 0.83%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 11        | 0.76%   |
| ARM Processor                                 | 11        | 0.76%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 11        | 0.76%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 11        | 0.76%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 10        | 0.69%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 10        | 0.69%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 10        | 0.69%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 10        | 0.69%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 10        | 0.69%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 9         | 0.62%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 9         | 0.62%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 9         | 0.62%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 9         | 0.62%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 9         | 0.62%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 8         | 0.55%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 8         | 0.55%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 8         | 0.55%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 8         | 0.55%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 8         | 0.55%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 8         | 0.55%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 8         | 0.55%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 7         | 0.49%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 7         | 0.49%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 7         | 0.49%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 7         | 0.49%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 7         | 0.49%   |
| Intel Atom CPU Z3735G @ 1.33GHz               | 7         | 0.49%   |
| AMD Ryzen 9 5900HS with Radeon Graphics       | 7         | 0.49%   |
| AMD Ryzen 9 3950X 16-Core Processor           | 7         | 0.49%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 7         | 0.49%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 7         | 0.49%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 6         | 0.42%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 6         | 0.42%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 6         | 0.42%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 6         | 0.42%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 6         | 0.42%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 6         | 0.42%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 366       | 25.38%  |
| Intel Core i5           | 332       | 23.02%  |
| AMD Ryzen 5             | 141       | 9.78%   |
| AMD Ryzen 7             | 90        | 6.24%   |
| Other                   | 84        | 5.83%   |
| Intel Core i3           | 76        | 5.27%   |
| AMD Ryzen 9             | 44        | 3.05%   |
| Intel Xeon              | 32        | 2.22%   |
| Intel Atom              | 30        | 2.08%   |
| Intel Celeron           | 26        | 1.8%    |
| Intel Core i9           | 20        | 1.39%   |
| Intel Core 2 Duo        | 20        | 1.39%   |
| AMD Ryzen 3             | 20        | 1.39%   |
| Intel Pentium           | 18        | 1.25%   |
| AMD Ryzen 7 PRO         | 16        | 1.11%   |
| AMD A10                 | 12        | 0.83%   |
| AMD FX                  | 10        | 0.69%   |
| Intel Pentium Silver    | 8         | 0.55%   |
| AMD A8                  | 8         | 0.55%   |
| Intel Core 2 Quad       | 7         | 0.49%   |
| AMD Ryzen Threadripper  | 7         | 0.49%   |
| AMD Ryzen 5 PRO         | 7         | 0.49%   |
| AMD A6                  | 7         | 0.49%   |
| Intel Pentium Dual-Core | 6         | 0.42%   |
| AMD A4                  | 5         | 0.35%   |
| AMD Athlon 64 X2        | 4         | 0.28%   |
| Intel Pentium Dual      | 3         | 0.21%   |
| Intel Core m3           | 3         | 0.21%   |
| AMD Phenom II X2        | 3         | 0.21%   |
| AMD E                   | 3         | 0.21%   |
| AMD Athlon Dual Core    | 3         | 0.21%   |
| Intel Pentium D         | 2         | 0.14%   |
| Intel Core m7           | 2         | 0.14%   |
| Intel Core m5           | 2         | 0.14%   |
| AMD Phenom II X6        | 2         | 0.14%   |
| AMD Phenom II X4        | 2         | 0.14%   |
| AMD E2                  | 2         | 0.14%   |
| AMD Athlon II X2        | 2         | 0.14%   |
| AMD Athlon              | 2         | 0.14%   |
| AMD A12                 | 2         | 0.14%   |
| QUALCOMM AArch64        | 1         | 0.07%   |
| Intel Pentium 4         | 1         | 0.07%   |
| Intel Genuine           | 1         | 0.07%   |
| Intel Core M            | 1         | 0.07%   |
| Intel Core 2            | 1         | 0.07%   |
| Intel Celeron Dual-Core | 1         | 0.07%   |
| AMD Turion II           | 1         | 0.07%   |
| AMD Turion 64 X2 Mobile | 1         | 0.07%   |
| AMD PRO A10             | 1         | 0.07%   |
| AMD E1                  | 1         | 0.07%   |
| AMD Athlon X2           | 1         | 0.07%   |
| AMD Athlon II X4        | 1         | 0.07%   |
| AMD Athlon II           | 1         | 0.07%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 619       | 42.9%   |
| 2      | 405       | 28.07%  |
| 6      | 204       | 14.14%  |
| 8      | 158       | 10.95%  |
| 12     | 25        | 1.73%   |
| 16     | 17        | 1.18%   |
| 1      | 8         | 0.55%   |
| 10     | 3         | 0.21%   |
| 3      | 2         | 0.14%   |
| 32     | 1         | 0.07%   |
| 24     | 1         | 0.07%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 1426      | 98.89%  |
| 2      | 15        | 1.04%   |
| 3      | 1         | 0.07%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 1112      | 76.9%   |
| 1      | 334       | 23.1%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1441      | 99.93%  |
| 64-bit         | 1         | 0.07%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 75        | 5.17%   |
| 0x806ec    | 72        | 4.97%   |
| 0x306c3    | 71        | 4.9%    |
| 0x206a7    | 68        | 4.69%   |
| 0x306a9    | 63        | 4.34%   |
| 0x806c1    | 62        | 4.28%   |
| 0x906ea    | 58        | 4%      |
| 0x806ea    | 58        | 4%      |
| 0x806e9    | 56        | 3.86%   |
| 0x406e3    | 55        | 3.79%   |
| 0x906e9    | 42        | 2.9%    |
| 0x08701021 | 42        | 2.9%    |
| 0x506e3    | 41        | 2.83%   |
| 0x08600106 | 36        | 2.48%   |
| 0x306d4    | 32        | 2.21%   |
| 0xa0652    | 30        | 2.07%   |
| 0x40651    | 28        | 1.93%   |
| 0x1067a    | 27        | 1.86%   |
| 0x0a50000c | 26        | 1.79%   |
| 0x08108109 | 23        | 1.59%   |
| 0x906ed    | 22        | 1.52%   |
| 0x0800820d | 22        | 1.52%   |
| 0x08600104 | 21        | 1.45%   |
| 0x08108102 | 21        | 1.45%   |
| 0x0a201009 | 20        | 1.38%   |
| 0x706e5    | 19        | 1.31%   |
| 0x30678    | 19        | 1.31%   |
| 0x806eb    | 16        | 1.1%    |
| 0x20655    | 16        | 1.1%    |
| 0x08701013 | 15        | 1.03%   |
| 0x08600103 | 13        | 0.9%    |
| 0x706a1    | 12        | 0.83%   |
| 0x406c4    | 12        | 0.83%   |
| 0x0810100b | 11        | 0.76%   |
| 0xa0655    | 10        | 0.69%   |
| 0x106e5    | 10        | 0.69%   |
| 0x406c3    | 9         | 0.62%   |
| 0x40661    | 9         | 0.62%   |
| 0x0a201016 | 9         | 0.62%   |
| 0x08101016 | 8         | 0.55%   |
| 0x08001138 | 8         | 0.55%   |
| 0x08608103 | 7         | 0.48%   |
| 0x806d1    | 6         | 0.41%   |
| 0x706a8    | 6         | 0.41%   |
| 0x08101007 | 6         | 0.41%   |
| 0x08001137 | 6         | 0.41%   |
| 0x07030105 | 6         | 0.41%   |
| 0x906ec    | 5         | 0.34%   |
| 0x6fd      | 5         | 0.34%   |
| 0x306f2    | 5         | 0.34%   |
| 0x08608102 | 5         | 0.34%   |
| 0x08600102 | 5         | 0.34%   |
| 0x06003106 | 5         | 0.34%   |
| 0x010000c8 | 5         | 0.34%   |
| 0xa0671    | 4         | 0.28%   |
| 0xa0653    | 4         | 0.28%   |
| 0x906eb    | 4         | 0.28%   |
| 0x106a5    | 4         | 0.28%   |
| 0x10676    | 4         | 0.28%   |
| 0x0a50000b | 4         | 0.28%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 346       | 23.99%  |
| Zen 2         | 139       | 9.64%   |
| Haswell       | 118       | 8.18%   |
| Skylake       | 100       | 6.93%   |
| SandyBridge   | 73        | 5.06%   |
| Zen+          | 72        | 4.99%   |
| IvyBridge     | 68        | 4.72%   |
| TigerLake     | 62        | 4.3%    |
| Zen 3         | 58        | 4.02%   |
| CometLake     | 48        | 3.33%   |
| Zen           | 45        | 3.12%   |
| Silvermont    | 42        | 2.91%   |
| Broadwell     | 36        | 2.5%    |
| Penryn        | 33        | 2.29%   |
| IceLake       | 31        | 2.15%   |
| Unknown       | 24        | 1.66%   |
| Westmere      | 20        | 1.39%   |
| Goldmont plus | 18        | 1.25%   |
| Nehalem       | 16        | 1.11%   |
| Piledriver    | 15        | 1.04%   |
| K10           | 13        | 0.9%    |
| Core          | 11        | 0.76%   |
| Excavator     | 10        | 0.69%   |
| Puma          | 8         | 0.55%   |
| K8 Hammer     | 8         | 0.55%   |
| Steamroller   | 6         | 0.42%   |
| Jaguar        | 5         | 0.35%   |
| NetBurst      | 4         | 0.28%   |
| K10 Llano     | 4         | 0.28%   |
| Bobcat        | 3         | 0.21%   |
| Goldmont      | 2         | 0.14%   |
| Bulldozer     | 2         | 0.14%   |
| Bonnell       | 2         | 0.14%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 836       | 47.42%  |
| Nvidia                     | 488       | 27.68%  |
| AMD                        | 434       | 24.62%  |
| ASPEED Technology          | 3         | 0.17%   |
| Matrox Electronics Systems | 1         | 0.06%   |
| ATI Technologies           | 1         | 0.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                                               | 80        | 4.45%   |
| Intel UHD Graphics 620                                                                   | 64        | 3.56%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 57        | 3.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 53        | 2.95%   |
| Intel HD Graphics 620                                                                    | 51        | 2.84%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 45        | 2.5%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 44        | 2.45%   |
| AMD Picasso                                                                              | 44        | 2.45%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 44        | 2.45%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 43        | 2.39%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 43        | 2.39%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 40        | 2.22%   |
| Intel HD Graphics 5500                                                                   | 32        | 1.78%   |
| Intel HD Graphics 630                                                                    | 30        | 1.67%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 30        | 1.67%   |
| Intel HD Graphics 530                                                                    | 28        | 1.56%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 28        | 1.56%   |
| AMD Cezanne                                                                              | 27        | 1.5%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 26        | 1.45%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 25        | 1.39%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 23        | 1.28%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 22        | 1.22%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 20        | 1.11%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 20        | 1.11%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 18        | 1%      |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 17        | 0.95%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 15        | 0.83%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 14        | 0.78%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 13        | 0.72%   |
| Intel Core Processor Integrated Graphics Controller                                      | 13        | 0.72%   |
| Nvidia GP108M [GeForce MX150]                                                            | 12        | 0.67%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 12        | 0.67%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 12        | 0.67%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 12        | 0.67%   |
| AMD Lucienne                                                                             | 12        | 0.67%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 11        | 0.61%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 10        | 0.56%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 10        | 0.56%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 10        | 0.56%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 10        | 0.56%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 9         | 0.5%    |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 9         | 0.5%    |
| Intel Iris Plus Graphics G7                                                              | 9         | 0.5%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 9         | 0.5%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 8         | 0.44%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 8         | 0.44%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 8         | 0.44%   |
| Nvidia GM108M [GeForce MX110]                                                            | 8         | 0.44%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 8         | 0.44%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 8         | 0.44%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 7         | 0.39%   |
| Nvidia GT218 [GeForce 210]                                                               | 7         | 0.39%   |
| Nvidia GP108M [GeForce MX250]                                                            | 7         | 0.39%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 7         | 0.39%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 7         | 0.39%   |
| Nvidia GM108M [GeForce 940M]                                                             | 7         | 0.39%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 7         | 0.39%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 7         | 0.39%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 7         | 0.39%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 6         | 0.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 540       | 37.32%  |
| 1 x AMD        | 335       | 23.15%  |
| Intel + Nvidia | 231       | 15.96%  |
| 1 x Nvidia     | 219       | 15.13%  |
| Intel + AMD    | 42        | 2.9%    |
| AMD + Nvidia   | 33        | 2.28%   |
| 2 x AMD        | 22        | 1.52%   |
| Other          | 14        | 0.97%   |
| 2 x Nvidia     | 7         | 0.48%   |
| 1 x ASPEED     | 3         | 0.21%   |
| 1 x Matrox     | 1         | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1190      | 81.56%  |
| Proprietary | 236       | 16.18%  |
| Unknown     | 33        | 2.26%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 744       | 50.65%  |
| 1.01-2.0   | 204       | 13.89%  |
| 0.01-0.5   | 155       | 10.55%  |
| 3.01-4.0   | 117       | 7.96%   |
| 0.51-1.0   | 98        | 6.67%   |
| 7.01-8.0   | 82        | 5.58%   |
| 5.01-6.0   | 37        | 2.52%   |
| 8.01-16.0  | 19        | 1.29%   |
| 2.01-3.0   | 12        | 0.82%   |
| 16.01-24.0 | 1         | 0.07%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 194       | 11.23%  |
| Samsung Electronics     | 170       | 9.84%   |
| LG Display              | 169       | 9.78%   |
| Chimei Innolux          | 163       | 9.43%   |
| BOE                     | 153       | 8.85%   |
| Goldstar                | 127       | 7.35%   |
| Dell                    | 124       | 7.18%   |
| Hewlett-Packard         | 56        | 3.24%   |
| Sharp                   | 53        | 3.07%   |
| Acer                    | 53        | 3.07%   |
| BenQ                    | 50        | 2.89%   |
| Philips                 | 39        | 2.26%   |
| AOC                     | 39        | 2.26%   |
| Ancor Communications    | 34        | 1.97%   |
| Apple                   | 32        | 1.85%   |
| Lenovo                  | 31        | 1.79%   |
| Iiyama                  | 26        | 1.5%    |
| PANDA                   | 25        | 1.45%   |
| CSO                     | 15        | 0.87%   |
| ViewSonic               | 14        | 0.81%   |
| ASUSTek Computer        | 14        | 0.81%   |
| Sony                    | 9         | 0.52%   |
| Sceptre Tech            | 9         | 0.52%   |
| InfoVision              | 9         | 0.52%   |
| Chi Mei Optoelectronics | 9         | 0.52%   |
| ___                     | 5         | 0.29%   |
| Unknown                 | 5         | 0.29%   |
| TMX                     | 5         | 0.29%   |
| MSI                     | 5         | 0.29%   |
| Insignia                | 5         | 0.29%   |
| Vizio                   | 4         | 0.23%   |
| Toshiba                 | 4         | 0.23%   |
| NEC Computers           | 4         | 0.23%   |
| eMachines               | 4         | 0.23%   |
| Pixio                   | 3         | 0.17%   |
| JDI                     | 3         | 0.17%   |
| Fujitsu Siemens         | 3         | 0.17%   |
| Eizo                    | 3         | 0.17%   |
| Vestel Elektronik       | 2         | 0.12%   |
| NEW                     | 2         | 0.12%   |
| Mitsubishi              | 2         | 0.12%   |
| Mi                      | 2         | 0.12%   |
| KTC                     | 2         | 0.12%   |
| HannStar                | 2         | 0.12%   |
| Gigabyte Technology     | 2         | 0.12%   |
| Element                 | 2         | 0.12%   |
| Zoran                   | 1         | 0.06%   |
| Yamaha                  | 1         | 0.06%   |
| WST                     | 1         | 0.06%   |
| VOR                     | 1         | 0.06%   |
| Unknown (XXX)           | 1         | 0.06%   |
| UGD                     | 1         | 0.06%   |
| SKY                     | 1         | 0.06%   |
| SGT                     | 1         | 0.06%   |
| SAC                     | 1         | 0.06%   |
| RZR                     | 1         | 0.06%   |
| RTK                     | 1         | 0.06%   |
| RIS                     | 1         | 0.06%   |
| RGT                     | 1         | 0.06%   |
| QCM                     | 1         | 0.06%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch                      | 13        | 0.73%   |
| Goldstar LG ULTRAWIDE GSM59F1 1920x1080 580x240mm 24.7-inch                           | 12        | 0.67%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch                      | 12        | 0.67%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch                        | 10        | 0.56%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch                        | 9         | 0.5%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                                | 8         | 0.45%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                                     | 7         | 0.39%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 340x190mm 15.3-inch                        | 7         | 0.39%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                               | 6         | 0.34%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch                     | 6         | 0.34%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch                     | 6         | 0.34%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch                           | 6         | 0.34%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                              | 6         | 0.34%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch                        | 6         | 0.34%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                               | 5         | 0.28%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch                  | 5         | 0.28%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch                          | 5         | 0.28%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch                          | 5         | 0.28%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch                          | 5         | 0.28%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                               | 5         | 0.28%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                                 | 5         | 0.28%   |
| Dell P2319H DELD0D7 1920x1080 509x286mm 23.0-inch                                     | 5         | 0.28%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch                      | 5         | 0.28%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch                      | 5         | 0.28%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch                       | 5         | 0.28%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 340x190mm 15.3-inch                      | 5         | 0.28%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch                       | 5         | 0.28%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch                        | 5         | 0.28%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch                               | 4         | 0.22%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                               | 4         | 0.22%   |
| Sceptre Tech E248W-1920 SPT099D 1920x1080 443x249mm 20.0-inch                         | 4         | 0.22%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch                     | 4         | 0.22%   |
| Samsung Electronics Color LCD SDCA029 2160x1440 252x168mm 11.9-inch                   | 4         | 0.22%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                               | 4         | 0.22%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                               | 4         | 0.22%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                               | 4         | 0.22%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch                           | 4         | 0.22%   |
| Goldstar MP59G GSM5B35 1920x1080 480x270mm 21.7-inch                                  | 4         | 0.22%   |
| Goldstar LG FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                             | 4         | 0.22%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 597x336mm 27.0-inch                                | 4         | 0.22%   |
| eMachines E190HQV EMA0212 1280x1024 440x250mm 19.9-inch                               | 4         | 0.22%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                                     | 4         | 0.22%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch                       | 4         | 0.22%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch                      | 4         | 0.22%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch                      | 4         | 0.22%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch                      | 4         | 0.22%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                                 | 4         | 0.22%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                                 | 4         | 0.22%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                                     | 4         | 0.22%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                                     | 4         | 0.22%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch                         | 4         | 0.22%   |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch                        | 4         | 0.22%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch                         | 4         | 0.22%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch                         | 4         | 0.22%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch                         | 4         | 0.22%   |
| Apple Color LCD APPA02E 2880x1800 331x207mm 15.4-inch                                 | 4         | 0.22%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                                      | 4         | 0.22%   |
| AOC 2757M AOC2757 1920x1080 598x336mm 27.0-inch                                       | 4         | 0.22%   |
| ___ Monitor ranges (GTF): 48-62Hz V, 14-68kHz H, max dotclock 150MHz ___9000 1440x900 | 3         | 0.17%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                               | 3         | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 808       | 50.44%  |
| 1366x768 (WXGA)    | 221       | 13.8%   |
| 3840x2160 (4K)     | 127       | 7.93%   |
| 2560x1440 (QHD)    | 113       | 7.05%   |
| 1920x1200 (WUXGA)  | 47        | 2.93%   |
| 1600x900 (HD+)     | 42        | 2.62%   |
| 2560x1080          | 34        | 2.12%   |
| 1280x1024 (SXGA)   | 24        | 1.5%    |
| 1440x900 (WXGA+)   | 22        | 1.37%   |
| 2560x1600          | 18        | 1.12%   |
| 3440x1440          | 17        | 1.06%   |
| 1360x768           | 16        | 1%      |
| 2880x1800          | 15        | 0.94%   |
| 1680x1050 (WSXGA+) | 15        | 0.94%   |
| 1280x800 (WXGA)    | 10        | 0.62%   |
| 3840x1080          | 8         | 0.5%    |
| 3200x1800 (QHD+)   | 8         | 0.5%    |
| 1024x768 (XGA)     | 5         | 0.31%   |
| Unknown            | 5         | 0.31%   |
| 3840x2400          | 4         | 0.25%   |
| 2160x1440          | 4         | 0.25%   |
| 1920x540           | 4         | 0.25%   |
| 1920x1280          | 4         | 0.25%   |
| 3000x2000          | 3         | 0.19%   |
| 2736x1824          | 3         | 0.19%   |
| 2048x1152          | 3         | 0.19%   |
| 1600x1200          | 3         | 0.19%   |
| 3456x2160          | 2         | 0.12%   |
| 2256x1504          | 2         | 0.12%   |
| 2160x1350          | 2         | 0.12%   |
| 800x1280           | 1         | 0.06%   |
| 7680x1440          | 1         | 0.06%   |
| 7120x1080          | 1         | 0.06%   |
| 3840x1600          | 1         | 0.06%   |
| 3840x1100          | 1         | 0.06%   |
| 3240x2160          | 1         | 0.06%   |
| 3200x2000          | 1         | 0.06%   |
| 2288x1287          | 1         | 0.06%   |
| 1920x515           | 1         | 0.06%   |
| 1680x945           | 1         | 0.06%   |
| 1440x2560          | 1         | 0.06%   |
| 1280x960           | 1         | 0.06%   |
| 1280x720 (HD)      | 1         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 445       | 25.77%  |
| 13      | 206       | 11.93%  |
| 27      | 180       | 10.42%  |
| 14      | 151       | 8.74%   |
| 24      | 149       | 8.63%   |
| 23      | 111       | 6.43%   |
| 21      | 93        | 5.39%   |
| 17      | 55        | 3.18%   |
| 34      | 47        | 2.72%   |
| 12      | 36        | 2.08%   |
| 31      | 34        | 1.97%   |
| 19      | 34        | 1.97%   |
| 18      | 32        | 1.85%   |
| Unknown | 19        | 1.1%    |
| 20      | 14        | 0.81%   |
| 72      | 13        | 0.75%   |
| 22      | 13        | 0.75%   |
| 32      | 12        | 0.69%   |
| 25      | 10        | 0.58%   |
| 16      | 10        | 0.58%   |
| 11      | 9         | 0.52%   |
| 48      | 7         | 0.41%   |
| 28      | 6         | 0.35%   |
| 84      | 5         | 0.29%   |
| 54      | 4         | 0.23%   |
| 29      | 4         | 0.23%   |
| 49      | 3         | 0.17%   |
| 40      | 3         | 0.17%   |
| 39      | 3         | 0.17%   |
| 33      | 3         | 0.17%   |
| 46      | 2         | 0.12%   |
| 42      | 2         | 0.12%   |
| 26      | 2         | 0.12%   |
| 74      | 1         | 0.06%   |
| 65      | 1         | 0.06%   |
| 47      | 1         | 0.06%   |
| 43      | 1         | 0.06%   |
| 38      | 1         | 0.06%   |
| 37      | 1         | 0.06%   |
| 36      | 1         | 0.06%   |
| 35      | 1         | 0.06%   |
| 30      | 1         | 0.06%   |
| 8       | 1         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 707       | 42.11%  |
| 501-600     | 394       | 23.47%  |
| 401-500     | 160       | 9.53%   |
| 201-300     | 139       | 8.28%   |
| 351-400     | 84        | 5%      |
| 601-700     | 63        | 3.75%   |
| 701-800     | 62        | 3.69%   |
| 1501-2000   | 19        | 1.13%   |
| Unknown     | 19        | 1.13%   |
| 1001-1500   | 18        | 1.07%   |
| 801-900     | 9         | 0.54%   |
| 901-1000    | 4         | 0.24%   |
| 101-200     | 1         | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1210      | 81.65%  |
| 16/10   | 138       | 9.31%   |
| 21/9    | 53        | 3.58%   |
| 5/4     | 25        | 1.69%   |
| 3/2     | 21        | 1.42%   |
| 4/3     | 11        | 0.74%   |
| Unknown | 10        | 0.67%   |
| 32/9    | 7         | 0.47%   |
| 6/5     | 2         | 0.13%   |
| 0.62    | 2         | 0.13%   |
| 3.88    | 1         | 0.07%   |
| 3.40    | 1         | 0.07%   |
| 1.96    | 1         | 0.07%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 444       | 25.95%  |
| 201-250        | 279       | 16.31%  |
| 81-90          | 267       | 15.6%   |
| 301-350        | 181       | 10.58%  |
| 351-500        | 106       | 6.2%    |
| 71-80          | 89        | 5.2%    |
| 151-200        | 82        | 4.79%   |
| 251-300        | 58        | 3.39%   |
| 121-130        | 46        | 2.69%   |
| 61-70          | 33        | 1.93%   |
| 141-150        | 29        | 1.69%   |
| More than 1000 | 26        | 1.52%   |
| 501-1000       | 22        | 1.29%   |
| Unknown        | 19        | 1.11%   |
| 51-60          | 10        | 0.58%   |
| 111-120        | 7         | 0.41%   |
| 131-140        | 6         | 0.35%   |
| 91-100         | 5         | 0.29%   |
| 1-40           | 2         | 0.12%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 548       | 33.07%  |
| 51-100        | 473       | 28.55%  |
| 101-120       | 387       | 23.36%  |
| 161-240       | 142       | 8.57%   |
| More than 240 | 60        | 3.62%   |
| 1-50          | 28        | 1.69%   |
| Unknown       | 19        | 1.15%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1042      | 71.08%  |
| 2     | 324       | 22.1%   |
| 0     | 54        | 3.68%   |
| 3     | 45        | 3.07%   |
| 4     | 1         | 0.07%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 843       | 39.73%  |
| Realtek Semiconductor             | 741       | 34.92%  |
| Qualcomm Atheros                  | 196       | 9.24%   |
| Broadcom                          | 87        | 4.1%    |
| Broadcom Limited                  | 25        | 1.18%   |
| Ralink Technology                 | 24        | 1.13%   |
| TP-Link                           | 23        | 1.08%   |
| Marvell Technology Group          | 14        | 0.66%   |
| Lenovo                            | 13        | 0.61%   |
| MEDIATEK                          | 11        | 0.52%   |
| DisplayLink                       | 11        | 0.52%   |
| Aquantia                          | 10        | 0.47%   |
| Ralink                            | 9         | 0.42%   |
| Hewlett-Packard                   | 9         | 0.42%   |
| Sierra Wireless                   | 7         | 0.33%   |
| Nvidia                            | 7         | 0.33%   |
| NetGear                           | 5         | 0.24%   |
| Huawei Technologies               | 5         | 0.24%   |
| ASIX Electronics                  | 5         | 0.24%   |
| Apple                             | 5         | 0.24%   |
| Xiaomi                            | 4         | 0.19%   |
| Qualcomm Atheros Communications   | 4         | 0.19%   |
| Qualcomm                          | 4         | 0.19%   |
| Linksys                           | 4         | 0.19%   |
| D-Link System                     | 4         | 0.19%   |
| ASUSTek Computer                  | 4         | 0.19%   |
| Samsung Electronics               | 3         | 0.14%   |
| Motorola PCS                      | 3         | 0.14%   |
| Microsoft                         | 3         | 0.14%   |
| ICS Advent                        | 3         | 0.14%   |
| Ericsson Business Mobile Networks | 3         | 0.14%   |
| Dell                              | 3         | 0.14%   |
| Realtek                           | 2         | 0.09%   |
| Mellanox Technologies             | 2         | 0.09%   |
| InterBiometrics                   | 2         | 0.09%   |
| Google                            | 2         | 0.09%   |
| Fibocom                           | 2         | 0.09%   |
| D-Link                            | 2         | 0.09%   |
| Arduino SA                        | 2         | 0.09%   |
| Wilocity                          | 1         | 0.05%   |
| T & A Mobile Phones               | 1         | 0.05%   |
| Quectel Wireless Solutions        | 1         | 0.05%   |
| OPPO Electronics                  | 1         | 0.05%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.05%   |
| Oculus VR                         | 1         | 0.05%   |
| MosChip Semiconductor             | 1         | 0.05%   |
| MicroPython                       | 1         | 0.05%   |
| Microchip Technology              | 1         | 0.05%   |
| Manta                             | 1         | 0.05%   |
| LG Electronics                    | 1         | 0.05%   |
| JMicron Technology                | 1         | 0.05%   |
| INGENICO                          | 1         | 0.05%   |
| IMC Networks                      | 1         | 0.05%   |
| Adafruit                          | 1         | 0.05%   |
| Accton Technology                 | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 502       | 19.76%  |
| Intel Wi-Fi 6 AX200                                               | 169       | 6.65%   |
| Intel Wireless 8265 / 8275                                        | 73        | 2.87%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 67        | 2.64%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 63        | 2.48%   |
| Intel I211 Gigabit Network Connection                             | 61        | 2.4%    |
| Intel Wi-Fi 6 AX201                                               | 50        | 1.97%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 49        | 1.93%   |
| Intel Wireless 8260                                               | 48        | 1.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 42        | 1.65%   |
| Intel Wireless 7260                                               | 37        | 1.46%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 36        | 1.42%   |
| Realtek RTL8125 2.5GbE Controller                                 | 36        | 1.42%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 36        | 1.42%   |
| Intel Ethernet Connection (2) I219-V                              | 35        | 1.38%   |
| Intel Wireless 7265                                               | 33        | 1.3%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 32        | 1.26%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 29        | 1.14%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 29        | 1.14%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 27        | 1.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 26        | 1.02%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 24        | 0.94%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 24        | 0.94%   |
| Intel Wireless-AC 9260                                            | 23        | 0.91%   |
| Intel Ethernet Connection (4) I219-LM                             | 21        | 0.83%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 20        | 0.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 20        | 0.79%   |
| Intel Ethernet Connection I217-LM                                 | 19        | 0.75%   |
| Intel Wireless 3165                                               | 18        | 0.71%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 18        | 0.71%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 15        | 0.59%   |
| Intel Ethernet Connection (7) I219-V                              | 15        | 0.59%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 14        | 0.55%   |
| Intel Ethernet Connection (4) I219-V                              | 14        | 0.55%   |
| Intel Ethernet Connection (2) I219-LM                             | 13        | 0.51%   |
| Intel Ethernet Connection (10) I219-V                             | 13        | 0.51%   |
| Intel Ethernet Controller I225-V                                  | 12        | 0.47%   |
| Intel Ethernet Connection I219-LM                                 | 12        | 0.47%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 12        | 0.47%   |
| Intel Wireless 3160                                               | 11        | 0.43%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 11        | 0.43%   |
| Intel Ethernet Connection I218-LM                                 | 11        | 0.43%   |
| Intel Ethernet Connection (2) I218-V                              | 11        | 0.43%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 11        | 0.43%   |
| Intel Ethernet Connection (7) I219-LM                             | 10        | 0.39%   |
| Intel Ethernet Connection (6) I219-V                              | 10        | 0.39%   |
| MEDIATEK Network controller                                       | 9         | 0.35%   |
| Intel Ethernet Connection (6) I219-LM                             | 9         | 0.35%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 9         | 0.35%   |
| Broadcom BCM43142 802.11b/g/n                                     | 9         | 0.35%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 8         | 0.31%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 8         | 0.31%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 8         | 0.31%   |
| Intel Ethernet Connection I217-V                                  | 8         | 0.31%   |
| Intel Ethernet Connection (3) I218-LM                             | 8         | 0.31%   |
| Intel 82574L Gigabit Network Connection                           | 8         | 0.31%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 7         | 0.28%   |
| Ralink MT7601U Wireless Adapter                                   | 7         | 0.28%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 7         | 0.28%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 7         | 0.28%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 713       | 58.16%  |
| Realtek Semiconductor           | 171       | 13.95%  |
| Qualcomm Atheros                | 158       | 12.89%  |
| Broadcom                        | 66        | 5.38%   |
| Ralink Technology               | 24        | 1.96%   |
| TP-Link                         | 17        | 1.39%   |
| Broadcom Limited                | 13        | 1.06%   |
| MEDIATEK                        | 10        | 0.82%   |
| Ralink                          | 9         | 0.73%   |
| Sierra Wireless                 | 7         | 0.57%   |
| NetGear                         | 5         | 0.41%   |
| Qualcomm Atheros Communications | 4         | 0.33%   |
| Marvell Technology Group        | 4         | 0.33%   |
| Microsoft                       | 3         | 0.24%   |
| Linksys                         | 3         | 0.24%   |
| ASUSTek Computer                | 3         | 0.24%   |
| Realtek                         | 2         | 0.16%   |
| Qualcomm                        | 2         | 0.16%   |
| Hewlett-Packard                 | 2         | 0.16%   |
| Fibocom                         | 2         | 0.16%   |
| Dell                            | 2         | 0.16%   |
| D-Link System                   | 2         | 0.16%   |
| Xiaomi                          | 1         | 0.08%   |
| Wilocity                        | 1         | 0.08%   |
| Quectel Wireless Solutions      | 1         | 0.08%   |
| IMC Networks                    | 1         | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 169       | 13.73%  |
| Intel Wireless 8265 / 8275                                     | 73        | 5.93%   |
| Intel Wi-Fi 6 AX201                                            | 50        | 4.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 49        | 3.98%   |
| Intel Wireless 8260                                            | 48        | 3.9%    |
| Intel Wireless 7260                                            | 37        | 3.01%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 36        | 2.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 36        | 2.92%   |
| Intel Wireless 7265                                            | 33        | 2.68%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 32        | 2.6%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 29        | 2.36%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 29        | 2.36%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 27        | 2.19%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 26        | 2.11%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 24        | 1.95%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 24        | 1.95%   |
| Intel Wireless-AC 9260                                         | 23        | 1.87%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 20        | 1.62%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 20        | 1.62%   |
| Intel Wireless 3165                                            | 18        | 1.46%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 18        | 1.46%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 15        | 1.22%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 14        | 1.14%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 12        | 0.97%   |
| Intel Wireless 3160                                            | 11        | 0.89%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 11        | 0.89%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 11        | 0.89%   |
| MEDIATEK Network controller                                    | 9         | 0.73%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 9         | 0.73%   |
| Broadcom BCM43142 802.11b/g/n                                  | 9         | 0.73%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 8         | 0.65%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 8         | 0.65%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 8         | 0.65%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 7         | 0.57%   |
| Ralink MT7601U Wireless Adapter                                | 7         | 0.57%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 7         | 0.57%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 7         | 0.57%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 6         | 0.49%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 6         | 0.49%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 6         | 0.49%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 6         | 0.49%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 6         | 0.49%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 6         | 0.49%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 6         | 0.49%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 6         | 0.49%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 6         | 0.49%   |
| Intel Centrino Advanced-N 6235                                 | 6         | 0.49%   |
| Intel Centrino Advanced-N 6200                                 | 6         | 0.49%   |
| Ralink RT5370 Wireless Adapter                                 | 5         | 0.41%   |
| Intel Centrino Wireless-N 2230                                 | 5         | 0.41%   |
| Sierra Wireless EM7345 4G LTE                                  | 4         | 0.32%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 4         | 0.32%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 4         | 0.32%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 4         | 0.32%   |
| Realtek 802.11ac NIC                                           | 4         | 0.32%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 4         | 0.32%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless              | 4         | 0.32%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 4         | 0.32%   |
| Intel Centrino Ultimate-N 6300                                 | 4         | 0.32%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                         | 4         | 0.32%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 667       | 53.66%  |
| Intel                         | 381       | 30.65%  |
| Qualcomm Atheros              | 52        | 4.18%   |
| Broadcom                      | 29        | 2.33%   |
| Lenovo                        | 13        | 1.05%   |
| Broadcom Limited              | 12        | 0.97%   |
| DisplayLink                   | 11        | 0.88%   |
| Marvell Technology Group      | 10        | 0.8%    |
| Aquantia                      | 10        | 0.8%    |
| Nvidia                        | 7         | 0.56%   |
| TP-Link                       | 6         | 0.48%   |
| ASIX Electronics              | 5         | 0.4%    |
| Apple                         | 5         | 0.4%    |
| Xiaomi                        | 3         | 0.24%   |
| Samsung Electronics           | 3         | 0.24%   |
| ICS Advent                    | 3         | 0.24%   |
| Huawei Technologies           | 3         | 0.24%   |
| Hewlett-Packard               | 3         | 0.24%   |
| Qualcomm                      | 2         | 0.16%   |
| Motorola PCS                  | 2         | 0.16%   |
| Mellanox Technologies         | 2         | 0.16%   |
| D-Link System                 | 2         | 0.16%   |
| D-Link                        | 2         | 0.16%   |
| OPPO Electronics              | 1         | 0.08%   |
| OnePlus Technology (Shenzhen) | 1         | 0.08%   |
| MosChip Semiconductor         | 1         | 0.08%   |
| MediaTek                      | 1         | 0.08%   |
| Linksys                       | 1         | 0.08%   |
| LG Electronics                | 1         | 0.08%   |
| JMicron Technology            | 1         | 0.08%   |
| Google                        | 1         | 0.08%   |
| ASUSTek Computer              | 1         | 0.08%   |
| Accton Technology             | 1         | 0.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 502       | 39.01%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 67        | 5.21%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 63        | 4.9%    |
| Intel I211 Gigabit Network Connection                                         | 61        | 4.74%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 42        | 3.26%   |
| Realtek RTL8125 2.5GbE Controller                                             | 36        | 2.8%    |
| Intel Ethernet Connection (2) I219-V                                          | 35        | 2.72%   |
| Intel Ethernet Connection (4) I219-LM                                         | 21        | 1.63%   |
| Intel Ethernet Connection I217-LM                                             | 19        | 1.48%   |
| Intel Ethernet Connection (7) I219-V                                          | 15        | 1.17%   |
| Intel Ethernet Connection (4) I219-V                                          | 14        | 1.09%   |
| Intel Ethernet Connection (2) I219-LM                                         | 13        | 1.01%   |
| Intel Ethernet Connection (10) I219-V                                         | 13        | 1.01%   |
| Intel Ethernet Controller I225-V                                              | 12        | 0.93%   |
| Intel Ethernet Connection I219-LM                                             | 12        | 0.93%   |
| Intel Ethernet Connection I218-LM                                             | 11        | 0.85%   |
| Intel Ethernet Connection (2) I218-V                                          | 11        | 0.85%   |
| Intel Ethernet Connection (7) I219-LM                                         | 10        | 0.78%   |
| Intel Ethernet Connection (6) I219-V                                          | 10        | 0.78%   |
| Intel Ethernet Connection (6) I219-LM                                         | 9         | 0.7%    |
| Intel Ethernet Connection I217-V                                              | 8         | 0.62%   |
| Intel Ethernet Connection (3) I218-LM                                         | 8         | 0.62%   |
| Intel 82574L Gigabit Network Connection                                       | 8         | 0.62%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 7         | 0.54%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 7         | 0.54%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 7         | 0.54%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                             | 7         | 0.54%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                     | 6         | 0.47%   |
| Intel Ethernet Connection I219-V                                              | 6         | 0.47%   |
| Intel 82577LM Gigabit Network Connection                                      | 6         | 0.47%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 6         | 0.47%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]               | 5         | 0.39%   |
| Realtek RTL8152 Fast Ethernet Adapter                                         | 5         | 0.39%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 5         | 0.39%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 5         | 0.39%   |
| Intel I210 Gigabit Network Connection                                         | 5         | 0.39%   |
| Intel 82579V Gigabit Network Connection                                       | 5         | 0.39%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 5         | 0.39%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                             | 5         | 0.39%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 5         | 0.39%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 5         | 0.39%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 4         | 0.31%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                              | 4         | 0.31%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                        | 4         | 0.31%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 4         | 0.31%   |
| Lenovo ThinkPad TBT3 LAN                                                      | 4         | 0.31%   |
| Intel Ethernet Connection (3) I218-V                                          | 4         | 0.31%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 4         | 0.31%   |
| DisplayLink USB-C Hybrid UHD Video Dock                                       | 4         | 0.31%   |
| DisplayLink Dell Universal Dock D6000                                         | 4         | 0.31%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                       | 4         | 0.31%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 4         | 0.31%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 3         | 0.23%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 3         | 0.23%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 3         | 0.23%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                       | 3         | 0.23%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                             | 3         | 0.23%   |
| Lenovo USB-C Dock Ethernet                                                    | 3         | 0.23%   |
| Lenovo ThinkPad TBT 3 Dock                                                    | 3         | 0.23%   |
| Intel Ethernet Connection (13) I219-LM                                        | 3         | 0.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1159      | 49.89%  |
| Ethernet | 1141      | 49.12%  |
| Modem    | 19        | 0.82%   |
| Unknown  | 4         | 0.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1019      | 53.72%  |
| Ethernet | 876       | 46.18%  |
| Modem    | 2         | 0.11%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 773       | 53.42%  |
| 1     | 564       | 38.98%  |
| 3     | 52        | 3.59%   |
| 0     | 46        | 3.18%   |
| 4     | 7         | 0.48%   |
| 5     | 3         | 0.21%   |
| 9     | 1         | 0.07%   |
| 8     | 1         | 0.07%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1108      | 76.2%   |
| Yes  | 346       | 23.8%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 626       | 60.48%  |
| Realtek Semiconductor           | 84        | 8.12%   |
| Qualcomm Atheros Communications | 70        | 6.76%   |
| Cambridge Silicon Radio         | 48        | 4.64%   |
| Broadcom                        | 46        | 4.44%   |
| IMC Networks                    | 41        | 3.96%   |
| Lite-On Technology              | 33        | 3.19%   |
| Apple                           | 32        | 3.09%   |
| ASUSTek Computer                | 13        | 1.26%   |
| Foxconn / Hon Hai               | 9         | 0.87%   |
| Realtek                         | 6         | 0.58%   |
| Dell                            | 6         | 0.58%   |
| Ralink                          | 4         | 0.39%   |
| Marvell Semiconductor           | 4         | 0.39%   |
| Unknown                         | 2         | 0.19%   |
| Toshiba                         | 2         | 0.19%   |
| Hewlett-Packard                 | 2         | 0.19%   |
| MediaTek                        | 1         | 0.1%    |
| Foxconn International           | 1         | 0.1%    |
| Edimax Technology               | 1         | 0.1%    |
| Dynex                           | 1         | 0.1%    |
| D-Link System                   | 1         | 0.1%    |
| Chicony Electronics             | 1         | 0.1%    |
| Askey Computer                  | 1         | 0.1%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                                                               | 160       | 15.46%  |
| Intel Bluetooth Device                                                              | 121       | 11.69%  |
| Intel AX201 Bluetooth                                                               | 111       | 10.72%  |
| Intel Bluetooth wireless interface                                                  | 98        | 9.47%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 75        | 7.25%   |
| Realtek Bluetooth Radio                                                             | 52        | 5.02%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 48        | 4.64%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 40        | 3.86%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 27        | 2.61%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 24        | 2.32%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 23        | 2.22%   |
| Lite-On Bluetooth Device                                                            | 21        | 2.03%   |
| Apple Bluetooth Host Controller                                                     | 19        | 1.84%   |
| IMC Networks Bluetooth Radio                                                        | 14        | 1.35%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 14        | 1.35%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 11        | 1.06%   |
| Intel AX210 Bluetooth                                                               | 11        | 1.06%   |
| IMC Networks Wireless_Device                                                        | 8         | 0.77%   |
| IMC Networks Bluetooth Device                                                       | 8         | 0.77%   |
| Apple Bluetooth USB Host Controller                                                 | 8         | 0.77%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 7         | 0.68%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 7         | 0.68%   |
| Realtek Bluetooth Radio                                                             | 6         | 0.58%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 6         | 0.58%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 5         | 0.48%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 5         | 0.48%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 5         | 0.48%   |
| Ralink RT3290 Bluetooth                                                             | 4         | 0.39%   |
| Marvell Bluetooth and Wireless LAN Composite                                        | 4         | 0.39%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 4         | 0.39%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 4         | 0.39%   |
| Dell DW375 Bluetooth Module                                                         | 4         | 0.39%   |
| Broadcom HP Portable Bumble Bee                                                     | 4         | 0.39%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 4         | 0.39%   |
| Realtek RTL8723B Bluetooth                                                          | 3         | 0.29%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 3         | 0.29%   |
| Lite-On Bluetooth Radio                                                             | 3         | 0.29%   |
| IMC Networks Bluetooth USB Host Controller                                          | 3         | 0.29%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 3         | 0.29%   |
| Broadcom BCM20702A0                                                                 | 3         | 0.29%   |
| ASUS Bluetooth Radio                                                                | 3         | 0.29%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 3         | 0.29%   |
| Unknown Bluetooth Device                                                            | 2         | 0.19%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 2         | 0.19%   |
| Lite-On Atheros Bluetooth                                                           | 2         | 0.19%   |
| IMC Networks Bluetooth                                                              | 2         | 0.19%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 0.19%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 2         | 0.19%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 2         | 0.19%   |
| Broadcom BCM20703A1 Bluetooth 4.1 + LE                                              | 2         | 0.19%   |
| Broadcom BCM2045A0                                                                  | 2         | 0.19%   |
| Broadcom BCM2045 Bluetooth                                                          | 2         | 0.19%   |
| ASUS Bluetooth Device                                                               | 2         | 0.19%   |
| Apple Bluetooth HCI MacBookPro (HID mode)                                           | 2         | 0.19%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.1%    |
| Toshiba Bluetooth Radio                                                             | 1         | 0.1%    |
| Qualcomm Atheros Dell Wireless 1802 Bluetooth 4.0 LE                                | 1         | 0.1%    |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.1%    |
| MediaTek Wireless_Device                                                            | 1         | 0.1%    |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.1%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 985       | 47.49%  |
| AMD                        | 465       | 22.42%  |
| Nvidia                     | 361       | 17.41%  |
| C-Media Electronics        | 40        | 1.93%   |
| Logitech                   | 21        | 1.01%   |
| Lenovo                     | 13        | 0.63%   |
| GN Netcom                  | 13        | 0.63%   |
| Creative Technology        | 12        | 0.58%   |
| Plantronics                | 9         | 0.43%   |
| Kingston Technology        | 9         | 0.43%   |
| Corsair                    | 8         | 0.39%   |
| Blue Microphones           | 8         | 0.39%   |
| Realtek Semiconductor      | 7         | 0.34%   |
| Generalplus Technology     | 7         | 0.34%   |
| SteelSeries ApS            | 6         | 0.29%   |
| RODE Microphones           | 6         | 0.29%   |
| Focusrite-Novation         | 6         | 0.29%   |
| Creative Labs              | 6         | 0.29%   |
| Samson Technologies        | 5         | 0.24%   |
| JMTek                      | 5         | 0.24%   |
| Sennheiser Communications  | 4         | 0.19%   |
| Razer USA                  | 4         | 0.19%   |
| Texas Instruments          | 3         | 0.14%   |
| Tenx Technology            | 3         | 0.14%   |
| Sony                       | 3         | 0.14%   |
| SAVITECH                   | 3         | 0.14%   |
| Microsoft                  | 3         | 0.14%   |
| Hewlett-Packard            | 3         | 0.14%   |
| GYROCOM C&C                | 3         | 0.14%   |
| Dell                       | 3         | 0.14%   |
| Cambridge Silicon Radio    | 3         | 0.14%   |
| ASUSTek Computer           | 3         | 0.14%   |
| ULi Electronics            | 2         | 0.1%    |
| Schiit Audio               | 2         | 0.1%    |
| JBL                        | 2         | 0.1%    |
| EGO SYStems                | 2         | 0.1%    |
| BEHRINGER International    | 2         | 0.1%    |
| Apple                      | 2         | 0.1%    |
| ZOOM                       | 1         | 0.05%   |
| Yamaha                     | 1         | 0.05%   |
| XMOS                       | 1         | 0.05%   |
| Xilinx                     | 1         | 0.05%   |
| VIA Technologies           | 1         | 0.05%   |
| USB MICROPHONE             | 1         | 0.05%   |
| Trust                      | 1         | 0.05%   |
| Thermaltake                | 1         | 0.05%   |
| Signalpath International   | 1         | 0.05%   |
| Shenzhen Riitek Technology | 1         | 0.05%   |
| ROCCAT                     | 1         | 0.05%   |
| Quanta                     | 1         | 0.05%   |
| PreSonus Audio Electronics | 1         | 0.05%   |
| Native Instruments         | 1         | 0.05%   |
| Meridian                   | 1         | 0.05%   |
| Medeli Electronics         | 1         | 0.05%   |
| Mark of the Unicorn        | 1         | 0.05%   |
| iPassion Technology        | 1         | 0.05%   |
| iCreate Technologies       | 1         | 0.05%   |
| Griffin Technology         | 1         | 0.05%   |
| Giga-Byte Technology       | 1         | 0.05%   |
| Fujitsu                    | 1         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 193       | 7.72%   |
| Intel Sunrise Point-LP HD Audio                                            | 176       | 7.04%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 110       | 4.4%    |
| AMD Starship/Matisse HD Audio Controller                                   | 87        | 3.48%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 75        | 3%      |
| Intel Cannon Lake PCH cAVS                                                 | 71        | 2.84%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 66        | 2.64%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 65        | 2.6%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 62        | 2.48%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 62        | 2.48%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 52        | 2.08%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 48        | 1.92%   |
| Intel Comet Lake PCH-LP cAVS                                               | 46        | 1.84%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 45        | 1.8%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 45        | 1.8%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 43        | 1.72%   |
| Nvidia GP107GL High Definition Audio Controller                            | 41        | 1.64%   |
| Intel 200 Series PCH HD Audio                                              | 41        | 1.64%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 34        | 1.36%   |
| Intel Broadwell-U Audio Controller                                         | 34        | 1.36%   |
| Intel Comet Lake PCH cAVS                                                  | 32        | 1.28%   |
| AMD FCH Azalia Controller                                                  | 31        | 1.24%   |
| Intel Haswell-ULT HD Audio Controller                                      | 28        | 1.12%   |
| Intel 8 Series HD Audio Controller                                         | 28        | 1.12%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 28        | 1.12%   |
| Nvidia TU106 High Definition Audio Controller                              | 27        | 1.08%   |
| Nvidia GP106 High Definition Audio Controller                              | 27        | 1.08%   |
| AMD Navi 10 HDMI Audio                                                     | 26        | 1.04%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 25        | 1%      |
| Nvidia TU116 High Definition Audio Controller                              | 23        | 0.92%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 23        | 0.92%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 23        | 0.92%   |
| Nvidia GP104 High Definition Audio Controller                              | 22        | 0.88%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 20        | 0.8%    |
| Intel CM238 HD Audio Controller                                            | 20        | 0.8%    |
| Nvidia Audio device                                                        | 19        | 0.76%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 19        | 0.76%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 19        | 0.76%   |
| AMD Kabini HDMI/DP Audio                                                   | 19        | 0.76%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 18        | 0.72%   |
| Nvidia GF108 High Definition Audio Controller                              | 17        | 0.68%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 16        | 0.64%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 16        | 0.64%   |
| Nvidia TU104 HD Audio Controller                                           | 14        | 0.56%   |
| Nvidia GK107 HDMI Audio Controller                                         | 14        | 0.56%   |
| Nvidia GA104 High Definition Audio Controller                              | 14        | 0.56%   |
| Nvidia High Definition Audio Controller                                    | 13        | 0.52%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 12        | 0.48%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 12        | 0.48%   |
| Nvidia GM204 High Definition Audio Controller                              | 11        | 0.44%   |
| Nvidia GF119 HDMI Audio Controller                                         | 11        | 0.44%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 10        | 0.4%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 9         | 0.36%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 9         | 0.36%   |
| C-Media Electronics 7.1ch Surround Audio Device                            | 9         | 0.36%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 9         | 0.36%   |
| Intel Comet Lake PCH-V Smart Sound Technology Audio Controller             | 8         | 0.32%   |
| Intel Audio device                                                         | 8         | 0.32%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 8         | 0.32%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                               | 7         | 0.28%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 187       | 21.57%  |
| SK Hynix            | 168       | 19.38%  |
| Kingston            | 108       | 12.46%  |
| Micron Technology   | 93        | 10.73%  |
| Unknown             | 66        | 7.61%   |
| Corsair             | 55        | 6.34%   |
| Crucial             | 46        | 5.31%   |
| G.Skill             | 41        | 4.73%   |
| A-DATA Technology   | 19        | 2.19%   |
| Ramaxel Technology  | 13        | 1.5%    |
| Elpida              | 12        | 1.38%   |
| Unknown (ABCD)      | 7         | 0.81%   |
| GOODRAM             | 7         | 0.81%   |
| Teikon              | 6         | 0.69%   |
| Smart               | 6         | 0.69%   |
| Team                | 5         | 0.58%   |
| Nanya Technology    | 4         | 0.46%   |
| Silicon Power       | 3         | 0.35%   |
| Patriot             | 3         | 0.35%   |
| Kllisre             | 3         | 0.35%   |
| Goldkey             | 3         | 0.35%   |
| Avant               | 3         | 0.35%   |
| Transcend           | 2         | 0.23%   |
| pqi                 | 1         | 0.12%   |
| OnBoard             | 1         | 0.12%   |
| KomputerBay         | 1         | 0.12%   |
| Golden Empire       | 1         | 0.12%   |
| Gold Key            | 1         | 0.12%   |
| Essencore           | 1         | 0.12%   |
| Apacer              | 1         | 0.12%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 12        | 1.3%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 12        | 1.3%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 11        | 1.19%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s              | 9         | 0.98%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB Row Of Chips DDR4 3200MT/s      | 8         | 0.87%   |
| SK Hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s             | 7         | 0.76%   |
| SK Hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 7         | 0.76%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 7         | 0.76%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM DDR3 2400MT/s   | 6         | 0.65%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 6         | 0.65%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 6         | 0.65%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 6         | 0.65%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s              | 6         | 0.65%   |
| Micron RAM 53E1G32D2NP-046 2048MB Row Of Chips LPDDR4 4267MT/s      | 6         | 0.65%   |
| Micron RAM 4ATF51264HZ-2G6E1 4096MB SODIMM DDR4 2667MT/s            | 6         | 0.65%   |
| Unknown RAM Module 1GB SODIMM DDR3 1333MT/s                         | 5         | 0.54%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 5         | 0.54%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8192MB SODIMM DDR4 2667MT/s           | 5         | 0.54%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 5         | 0.54%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s              | 5         | 0.54%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s         | 5         | 0.54%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s           | 4         | 0.43%   |
| SK Hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 4         | 0.43%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 4         | 0.43%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                        | 4         | 0.43%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s            | 4         | 0.43%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 2667MT/s               | 4         | 0.43%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 4         | 0.43%   |
| Samsung RAM M471A1K43BB1-CTD 8192MB SODIMM DDR4 2667MT/s            | 4         | 0.43%   |
| Samsung RAM K4UBE3D4AA-MGCL 8192MB Row Of Chips LPDDR4 4267MT/s     | 4         | 0.43%   |
| Micron RAM Module 8GB Chip LPDDR4                                   | 4         | 0.43%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                | 4         | 0.43%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3200MT/s                   | 4         | 0.43%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                         | 3         | 0.33%   |
| Unknown RAM Module 2GB DIMM 667MT/s                                 | 3         | 0.33%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                        | 3         | 0.33%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4096MB SODIMM DDR3 1600MT/s           | 3         | 0.33%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4096MB SODIMM DDR3 1600MT/s           | 3         | 0.33%   |
| SK Hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s             | 3         | 0.33%   |
| SK Hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s        | 3         | 0.33%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s             | 3         | 0.33%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 3         | 0.33%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 3         | 0.33%   |
| Samsung RAM Module 4GB SODIMM DDR4 2133MT/s                         | 3         | 0.33%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 3         | 0.33%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 3         | 0.33%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 3         | 0.33%   |
| Samsung RAM M471A5143EB0-CPB 4096MB SODIMM DDR4 2133MT/s            | 3         | 0.33%   |
| Samsung RAM M471A2K43CB1-CRC 16384MB SODIMM DDR4 2667MT/s           | 3         | 0.33%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s              | 3         | 0.33%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 3         | 0.33%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 3         | 0.33%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 3         | 0.33%   |
| Ramaxel RAM RMSA3300ME78HBF-2666 16384MB SODIMM DDR4 2667MT/s       | 3         | 0.33%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s               | 3         | 0.33%   |
| Micron RAM 4ATF51264HZ-2G3B1 4096MB SODIMM DDR4 2400MT/s            | 3         | 0.33%   |
| Kllisre RAM KRE-D3S1600M/8G 8GB SODIMM DDR3 1600MT/s                | 3         | 0.33%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s                   | 3         | 0.33%   |
| Kingston RAM KHX1600C9D3/4GX 4096MB DIMM DDR3 2400MT/s              | 3         | 0.33%   |
| Kingston RAM KHX1600C10D3/8G 8192MB DIMM 1867MT/s                   | 3         | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 444       | 60.33%  |
| DDR3    | 194       | 26.36%  |
| LPDDR4  | 37        | 5.03%   |
| LPDDR3  | 29        | 3.94%   |
| DDR2    | 14        | 1.9%    |
| Unknown | 10        | 1.36%   |
| SDRAM   | 4         | 0.54%   |
| DDR     | 4         | 0.54%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 437       | 58.89%  |
| DIMM         | 218       | 29.38%  |
| Row Of Chips | 71        | 9.57%   |
| Chip         | 14        | 1.89%   |
| RIMM         | 1         | 0.13%   |
| Unknown      | 1         | 0.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 322       | 40.45%  |
| 4096  | 207       | 26.01%  |
| 16384 | 162       | 20.35%  |
| 2048  | 65        | 8.17%   |
| 32768 | 23        | 2.89%   |
| 1024  | 16        | 2.01%   |
| 512   | 1         | 0.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 173       | 21.6%   |
| 2667    | 139       | 17.35%  |
| 1600    | 134       | 16.73%  |
| 2400    | 65        | 8.11%   |
| 2133    | 54        | 6.74%   |
| 1333    | 34        | 4.24%   |
| 3600    | 20        | 2.5%    |
| 4267    | 19        | 2.37%   |
| 1867    | 19        | 2.37%   |
| 3266    | 15        | 1.87%   |
| Unknown | 15        | 1.87%   |
| 1334    | 14        | 1.75%   |
| 667     | 11        | 1.37%   |
| 1066    | 10        | 1.25%   |
| 3000    | 9         | 1.12%   |
| 1067    | 9         | 1.12%   |
| 2800    | 6         | 0.75%   |
| 800     | 6         | 0.75%   |
| 3800    | 5         | 0.62%   |
| 3733    | 5         | 0.62%   |
| 3400    | 4         | 0.5%    |
| 2933    | 4         | 0.5%    |
| 2666    | 4         | 0.5%    |
| 3466    | 3         | 0.37%   |
| 1866    | 3         | 0.37%   |
| 333     | 3         | 0.37%   |
| 4266    | 2         | 0.25%   |
| 3533    | 2         | 0.25%   |
| 1800    | 2         | 0.25%   |
| 4199    | 1         | 0.12%   |
| 3866    | 1         | 0.12%   |
| 3666    | 1         | 0.12%   |
| 3467    | 1         | 0.12%   |
| 3100    | 1         | 0.12%   |
| 2934    | 1         | 0.12%   |
| 2134    | 1         | 0.12%   |
| 2132    | 1         | 0.12%   |
| 2000    | 1         | 0.12%   |
| 933     | 1         | 0.12%   |
| 533     | 1         | 0.12%   |
| 400     | 1         | 0.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 14        | 40%     |
| Brother Industries  | 7         | 20%     |
| Canon               | 4         | 11.43%  |
| Seiko Epson         | 2         | 5.71%   |
| Xerox               | 1         | 2.86%   |
| Star Micronics      | 1         | 2.86%   |
| Samsung Electronics | 1         | 2.86%   |
| Ricoh               | 1         | 2.86%   |
| Prolific Technology | 1         | 2.86%   |
| Dymo-CoStar         | 1         | 2.86%   |
| Dell                | 1         | 2.86%   |
| Boca Systems        | 1         | 2.86%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| HP OfficeJet 6950                            | 2         | 5.71%   |
| HP DeskJet 2620 All-in-One Printer           | 2         | 5.71%   |
| Xerox Phaser 3010                            | 1         | 2.86%   |
| Star Micronics TUP592 (STR_T-001)            | 1         | 2.86%   |
| Seiko Epson PX-045A Series                   | 1         | 2.86%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1         | 2.86%   |
| Samsung M2070 Series                         | 1         | 2.86%   |
| Ricoh SP 212SUw                              | 1         | 2.86%   |
| Prolific PL2305 Parallel Port                | 1         | 2.86%   |
| HP Officejet 4500 G510g-m                    | 1         | 2.86%   |
| HP Neverstop Laser 100x                      | 1         | 2.86%   |
| HP LaserJet Professional P 1102w             | 1         | 2.86%   |
| HP LaserJet P1006                            | 1         | 2.86%   |
| HP Ink Tank 310 series                       | 1         | 2.86%   |
| HP EWS UPD                                   | 1         | 2.86%   |
| HP ENVY 5000 series                          | 1         | 2.86%   |
| HP DeskJet F4100 Printer series              | 1         | 2.86%   |
| HP Deskjet D2500 series                      | 1         | 2.86%   |
| HP DeskJet 4530 series                       | 1         | 2.86%   |
| Dymo-CoStar DYMO LabelWriter 4XL             | 1         | 2.86%   |
| Dell B1160w Mono Laser Printer               | 1         | 2.86%   |
| Canon TR8500 series                          | 1         | 2.86%   |
| Canon PIXMA MP270 All-In-One Printer         | 1         | 2.86%   |
| Canon PIXMA MG3000 series                    | 1         | 2.86%   |
| Canon LiDE 300                               | 1         | 2.86%   |
| Brother Printer                              | 1         | 2.86%   |
| Brother MFC-9330CDW                          | 1         | 2.86%   |
| Brother MFC-9325CW                           | 1         | 2.86%   |
| Brother HL-L2340D series                     | 1         | 2.86%   |
| Brother HL-1430 Laser Printer                | 1         | 2.86%   |
| Brother DCP-7040                             | 1         | 2.86%   |
| Brother DCP-7030                             | 1         | 2.86%   |
| Boca Systems FGL46 Thermal Printer           | 1         | 2.86%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Seiko Epson     | 4         | 44.44%  |
| Canon           | 4         | 44.44%  |
| Hewlett-Packard | 1         | 11.11%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo]             | 1         | 11.11%  |
| Seiko Epson GT-X770 [Perfection V500]                   | 1         | 11.11%  |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1         | 11.11%  |
| Seiko Epson GT-F670 [Perfection V200 Photo]             | 1         | 11.11%  |
| HP ScanJet G4050                                        | 1         | 11.11%  |
| Canon CanoScan N1240U/LiDE 30                           | 1         | 11.11%  |
| Canon CanoScan LiDE 70                                  | 1         | 11.11%  |
| Canon CanoScan LiDE 220                                 | 1         | 11.11%  |
| Canon CanoScan 4400F                                    | 1         | 11.11%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 224       | 22.47%  |
| IMC Networks                           | 125       | 12.54%  |
| Microdia                               | 83        | 8.32%   |
| Logitech                               | 76        | 7.62%   |
| Acer                                   | 70        | 7.02%   |
| Realtek Semiconductor                  | 62        | 6.22%   |
| Sunplus Innovation Technology          | 53        | 5.32%   |
| Quanta                                 | 44        | 4.41%   |
| Cheng Uei Precision Industry (Foxlink) | 44        | 4.41%   |
| Syntek                                 | 31        | 3.11%   |
| Apple                                  | 27        | 2.71%   |
| Lite-On Technology                     | 26        | 2.61%   |
| Suyin                                  | 19        | 1.91%   |
| Alcor Micro                            | 13        | 1.3%    |
| Microsoft                              | 11        | 1.1%    |
| Silicon Motion                         | 9         | 0.9%    |
| Samsung Electronics                    | 8         | 0.8%    |
| Z-Star Microelectronics                | 5         | 0.5%    |
| webcam vendor                          | 4         | 0.4%    |
| Ricoh                                  | 4         | 0.4%    |
| Luxvisions Innotech Limited            | 4         | 0.4%    |
| Jieli Technology                       | 4         | 0.4%    |
| Lenovo                                 | 3         | 0.3%    |
| KYE Systems (Mouse Systems)            | 3         | 0.3%    |
| AVerMedia Technologies                 | 3         | 0.3%    |
| ARC International                      | 3         | 0.3%    |
| ALi                                    | 3         | 0.3%    |
| YGTek                                  | 2         | 0.2%    |
| WaveRider Communications               | 2         | 0.2%    |
| Unknown                                | 2         | 0.2%    |
| Trust                                  | 2         | 0.2%    |
| Razer USA                              | 2         | 0.2%    |
| Pixart Imaging                         | 2         | 0.2%    |
| Generalplus Technology                 | 2         | 0.2%    |
| Creative Technology                    | 2         | 0.2%    |
| Y Media                                | 1         | 0.1%    |
| Xiaomi                                 | 1         | 0.1%    |
| WN-5693-210616                         | 1         | 0.1%    |
| Sony                                   | 1         | 0.1%    |
| Sonix Technology                       | 1         | 0.1%    |
| OmniVision Technologies                | 1         | 0.1%    |
| Mimaki Engineering                     | 1         | 0.1%    |
| LG Electronics                         | 1         | 0.1%    |
| INOGENI                                | 1         | 0.1%    |
| Importek                               | 1         | 0.1%    |
| Huawei Technologies                    | 1         | 0.1%    |
| Hewlett-Packard                        | 1         | 0.1%    |
| Google                                 | 1         | 0.1%    |
| Gearway Electronics (Dong Guan)        | 1         | 0.1%    |
| Foxconn / Hon Hai                      | 1         | 0.1%    |
| DJKANA1RSF34LM                         | 1         | 0.1%    |
| DigiTech                               | 1         | 0.1%    |
| Denron                                 | 1         | 0.1%    |
| BUFFALO                                | 1         | 0.1%    |
| Alcorlink                              | 1         | 0.1%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 85        | 8.36%   |
| IMC Networks Integrated Camera                                  | 57        | 5.6%    |
| Microdia Integrated_Webcam_HD                                   | 39        | 3.83%   |
| Realtek Integrated_Webcam_HD                                    | 28        | 2.75%   |
| Syntek Integrated Camera                                        | 26        | 2.56%   |
| Logitech Webcam C270                                            | 25        | 2.46%   |
| Sunplus Integrated_Webcam_HD                                    | 24        | 2.36%   |
| Acer Integrated Camera                                          | 24        | 2.36%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 23        | 2.26%   |
| Chicony HD Webcam                                               | 18        | 1.77%   |
| Logitech HD Pro Webcam C920                                     | 15        | 1.47%   |
| Lite-On Integrated Camera                                       | 14        | 1.38%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 14        | 1.38%   |
| Chicony Integrated Camera (1280x720@30)                         | 13        | 1.28%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera             | 12        | 1.18%   |
| Apple iPhone 5/5C/5S/6/SE                                       | 12        | 1.18%   |
| Chicony HP HD Camera                                            | 11        | 1.08%   |
| Chicony USB2.0 Camera                                           | 9         | 0.88%   |
| Acer EasyCamera                                                 | 9         | 0.88%   |
| Samsung Galaxy A5 (MTP)                                         | 8         | 0.79%   |
| Quanta HD User Facing                                           | 8         | 0.79%   |
| Microdia USB 2.0 Camera                                         | 8         | 0.79%   |
| Chicony HP Wide Vision HD Camera                                | 8         | 0.79%   |
| Chicony HP TrueVision HD Camera                                 | 8         | 0.79%   |
| Apple FaceTime HD Camera (Built-in)                             | 8         | 0.79%   |
| Quanta HP TrueVision HD Camera                                  | 7         | 0.69%   |
| Microdia Webcam Vitade AF                                       | 7         | 0.69%   |
| Logitech HD Webcam C525                                         | 7         | 0.69%   |
| Lite-On HP HD Camera                                            | 7         | 0.69%   |
| Quanta HP HD Camera                                             | 6         | 0.59%   |
| Quanta HD Webcam                                                | 6         | 0.59%   |
| Acer SunplusIT Integrated Camera                                | 6         | 0.59%   |
| Acer Lenovo EasyCamera                                          | 6         | 0.59%   |
| Suyin Integrated_Webcam_HD                                      | 5         | 0.49%   |
| Sunplus HD WebCam                                               | 5         | 0.49%   |
| Realtek Lenovo EasyCamera                                       | 5         | 0.49%   |
| Microsoft LifeCam Cinema                                        | 5         | 0.49%   |
| Microdia Integrated Webcam                                      | 5         | 0.49%   |
| IMC Networks USB Camera                                         | 5         | 0.49%   |
| IMC Networks ov9734_azurewave_camera                            | 5         | 0.49%   |
| Chicony USB2.0 HD UVC WebCam                                    | 5         | 0.49%   |
| Chicony FJ Camera                                               | 5         | 0.49%   |
| Apple Built-in iSight                                           | 5         | 0.49%   |
| Alcor Micro USB 2.0 Camera                                      | 5         | 0.49%   |
| Acer BisonCam, NB Pro                                           | 5         | 0.49%   |
| webcam vendor webcam product                                    | 4         | 0.39%   |
| Suyin HP TrueVision HD Integrated Webcam                        | 4         | 0.39%   |
| Sunplus Laptop_Integrated_Webcam_FHD                            | 4         | 0.39%   |
| Realtek Integrated Webcam                                       | 4         | 0.39%   |
| Microdia Integrated Webcam HD                                   | 4         | 0.39%   |
| Logitech Webcam C925e                                           | 4         | 0.39%   |
| Logitech Webcam C310                                            | 4         | 0.39%   |
| Logitech C922 Pro Stream Webcam                                 | 4         | 0.39%   |
| Logitech BRIO                                                   | 4         | 0.39%   |
| Jieli USB PHY 2.0                                               | 4         | 0.39%   |
| Chicony Lenovo Integrated Camera (0.3MP)                        | 4         | 0.39%   |
| Chicony HP HD Webcam                                            | 4         | 0.39%   |
| Chicony HD User Facing                                          | 4         | 0.39%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 4         | 0.39%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera  | 4         | 0.39%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 101       | 39.45%  |
| Validity Sensors           | 81        | 31.64%  |
| Shenzhen Goodix Technology | 41        | 16.02%  |
| Upek                       | 9         | 3.52%   |
| LighTuning Technology      | 9         | 3.52%   |
| Elan Microelectronics      | 9         | 3.52%   |
| AuthenTec                  | 4         | 1.56%   |
| STMicroelectronics         | 1         | 0.39%   |
| Focal-systems.Corp         | 1         | 0.39%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 38        | 14.84%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 23        | 8.98%   |
| Unknown                                                                    | 22        | 8.59%   |
| Shenzhen Goodix  FingerPrint Device                                        | 17        | 6.64%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 14        | 5.47%   |
| Shenzhen Goodix Fingerprint Reader                                         | 14        | 5.47%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 11        | 4.3%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 10        | 3.91%   |
| Shenzhen Goodix FingerPrint                                                | 10        | 3.91%   |
| Elan ELAN:Fingerprint                                                      | 9         | 3.52%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 8         | 3.13%   |
| Synaptics  WBDI                                                            | 8         | 3.13%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 8         | 3.13%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 7         | 2.73%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 7         | 2.73%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 2.34%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 6         | 2.34%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 5         | 1.95%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 1.95%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 4         | 1.56%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 1.17%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 1.17%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 0.78%   |
| Synaptics WBDI Device                                                      | 2         | 0.78%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.39%   |
| Validity Sensors VFS491                                                    | 1         | 0.39%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.39%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.39%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.39%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.39%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.39%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.39%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.39%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.39%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.39%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.39%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 0.39%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.39%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 31        | 36.9%   |
| Alcor Micro           | 30        | 35.71%  |
| Upek                  | 5         | 5.95%   |
| Lenovo                | 5         | 5.95%   |
| O2 Micro              | 4         | 4.76%   |
| Realtek Semiconductor | 2         | 2.38%   |
| OmniKey               | 2         | 2.38%   |
| SCM Microsystems      | 1         | 1.19%   |
| Hewlett-Packard       | 1         | 1.19%   |
| Gemalto (was Gemplus) | 1         | 1.19%   |
| Chicony Electronics   | 1         | 1.19%   |
| Cherry                | 1         | 1.19%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 30        | 35.71%  |
| Broadcom 5880                                                                | 12        | 14.29%  |
| Broadcom 58200                                                               | 9         | 10.71%  |
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 7.14%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 5.95%   |
| Lenovo Integrated Smart Card Reader                                          | 5         | 5.95%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 4.76%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 4         | 4.76%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 2.38%   |
| SCM Microsystems CLOUD 2900 R Smart Card Reader                              | 1         | 1.19%   |
| OmniKey CardMan 4321                                                         | 1         | 1.19%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 1.19%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 1.19%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.19%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 1.19%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 1.19%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1015      | 69.09%  |
| 1     | 401       | 27.3%   |
| 2     | 44        | 3%      |
| 3     | 7         | 0.48%   |
| 4     | 2         | 0.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 254       | 50.1%   |
| Graphics card            | 62        | 12.23%  |
| Multimedia controller    | 57        | 11.24%  |
| Net/wireless             | 56        | 11.05%  |
| Chipcard                 | 12        | 2.37%   |
| Unassigned class         | 10        | 1.97%   |
| Storage                  | 10        | 1.97%   |
| Camera                   | 10        | 1.97%   |
| Communication controller | 8         | 1.58%   |
| Bluetooth                | 7         | 1.38%   |
| Sound                    | 5         | 0.99%   |
| Card reader              | 5         | 0.99%   |
| Network                  | 3         | 0.59%   |
| Net/ethernet             | 3         | 0.59%   |
| Modem                    | 3         | 0.59%   |
| Storage/ata              | 1         | 0.2%    |
| Dvb card                 | 1         | 0.2%    |

