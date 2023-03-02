Fedora 37 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Fedora 37.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Fedora_37/Desktop/README.md) and [notebooks](/Dist/Fedora_37/Notebook/README.md).

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

Total: 2008

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HUAWEI        | CREM-WXX9                   | Notebook    | [22d51a725f](https://linux-hardware.org/?probe=22d51a725f) | Feb 28, 2023 |
| Dell          | Latitude E7270              | Notebook    | [2718026d03](https://linux-hardware.org/?probe=2718026d03) | Feb 28, 2023 |
| TECNO         | MEGABOOK T1                 | Notebook    | [3b70c27ca4](https://linux-hardware.org/?probe=3b70c27ca4) | Feb 28, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [48c5c743c9](https://linux-hardware.org/?probe=48c5c743c9) | Feb 28, 2023 |
| ASRock        | H61M-VS                     | Desktop     | [04d5b9593e](https://linux-hardware.org/?probe=04d5b9593e) | Feb 28, 2023 |
| HUAWEI        | MRC-WX0                     | Notebook    | [e2776f99bf](https://linux-hardware.org/?probe=e2776f99bf) | Feb 28, 2023 |
| HP            | ProBook 635 Aero G8 Note... | Notebook    | [93ee76f198](https://linux-hardware.org/?probe=93ee76f198) | Feb 28, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [9a897f5d7c](https://linux-hardware.org/?probe=9a897f5d7c) | Feb 28, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | Notebook    | [b5a4a1809f](https://linux-hardware.org/?probe=b5a4a1809f) | Feb 28, 2023 |
| TECNO         | MEGABOOK T1                 | Notebook    | [3d003c6d17](https://linux-hardware.org/?probe=3d003c6d17) | Feb 28, 2023 |
| ASUSTek       | ROG Strix G712LW_G712LW     | Notebook    | [ed67c567d2](https://linux-hardware.org/?probe=ed67c567d2) | Feb 28, 2023 |
| Standard      | Unknown                     | Notebook    | [63732ac2da](https://linux-hardware.org/?probe=63732ac2da) | Feb 28, 2023 |
| HP            | 158A                        | Desktop     | [64f3590183](https://linux-hardware.org/?probe=64f3590183) | Feb 28, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [1b5fd0df61](https://linux-hardware.org/?probe=1b5fd0df61) | Feb 28, 2023 |
| Dell          | Precision 5570              | Notebook    | [7e8d7c37cb](https://linux-hardware.org/?probe=7e8d7c37cb) | Feb 28, 2023 |
| Fujitsu       | D3224-P1 S26361-D3224-P1    | Desktop     | [53649a9546](https://linux-hardware.org/?probe=53649a9546) | Feb 28, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [c829e9e0b8](https://linux-hardware.org/?probe=c829e9e0b8) | Feb 27, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [45403acec9](https://linux-hardware.org/?probe=45403acec9) | Feb 27, 2023 |
| HUAWEI        | MACHR-WX9                   | Notebook    | [b1ef7c7ea1](https://linux-hardware.org/?probe=b1ef7c7ea1) | Feb 27, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [43602775cd](https://linux-hardware.org/?probe=43602775cd) | Feb 27, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [1c1dc86eb1](https://linux-hardware.org/?probe=1c1dc86eb1) | Feb 27, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [ed251c6cfe](https://linux-hardware.org/?probe=ed251c6cfe) | Feb 27, 2023 |
| ASUSTek       | PRIME Q270M-C               | Desktop     | [3a9683fbb7](https://linux-hardware.org/?probe=3a9683fbb7) | Feb 27, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [dd5ce2c6db](https://linux-hardware.org/?probe=dd5ce2c6db) | Feb 27, 2023 |
| Toshiba       | Satellite P870              | Notebook    | [6d9216b866](https://linux-hardware.org/?probe=6d9216b866) | Feb 27, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [11aeca0c24](https://linux-hardware.org/?probe=11aeca0c24) | Feb 27, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [4c96506f38](https://linux-hardware.org/?probe=4c96506f38) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [d7e55bb97e](https://linux-hardware.org/?probe=d7e55bb97e) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [091e4e3188](https://linux-hardware.org/?probe=091e4e3188) | Feb 27, 2023 |
| Gigabyte      | Z490 VISION D               | Desktop     | [cbea73a793](https://linux-hardware.org/?probe=cbea73a793) | Feb 27, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [058ecdce01](https://linux-hardware.org/?probe=058ecdce01) | Feb 27, 2023 |
| ASUSTek       | ROG Flow X13 GV301RE_GV3... | Convertible | [7f7bdeae7c](https://linux-hardware.org/?probe=7f7bdeae7c) | Feb 27, 2023 |
| Gigabyte      | Z490 VISION D               | Desktop     | [3e9f2feeaa](https://linux-hardware.org/?probe=3e9f2feeaa) | Feb 27, 2023 |
| Gigabyte      | Z170MX-Gaming 5             | Desktop     | [1f0e9197f9](https://linux-hardware.org/?probe=1f0e9197f9) | Feb 26, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [a121d0545a](https://linux-hardware.org/?probe=a121d0545a) | Feb 26, 2023 |
| Lenovo        | ThinkPad X395 20NL0006US    | Notebook    | [9030fac261](https://linux-hardware.org/?probe=9030fac261) | Feb 26, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c56cf68cef](https://linux-hardware.org/?probe=c56cf68cef) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [fe8735a027](https://linux-hardware.org/?probe=fe8735a027) | Feb 26, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [85ed1d43c7](https://linux-hardware.org/?probe=85ed1d43c7) | Feb 26, 2023 |
| HP            | Notebook                    | Notebook    | [ab0dddc914](https://linux-hardware.org/?probe=ab0dddc914) | Feb 26, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [6b712e555f](https://linux-hardware.org/?probe=6b712e555f) | Feb 26, 2023 |
| Dell          | Vostro 3578                 | Notebook    | [da6968c8ac](https://linux-hardware.org/?probe=da6968c8ac) | Feb 26, 2023 |
| Gigabyte      | H510M S2                    | Desktop     | [24ea8468ca](https://linux-hardware.org/?probe=24ea8468ca) | Feb 26, 2023 |
| Samsung       | 370E4K                      | Notebook    | [7b769eb33e](https://linux-hardware.org/?probe=7b769eb33e) | Feb 26, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [c026a25fb2](https://linux-hardware.org/?probe=c026a25fb2) | Feb 26, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [af6a897a26](https://linux-hardware.org/?probe=af6a897a26) | Feb 26, 2023 |
| Timi          | TM1612                      | Notebook    | [eb4a3f330e](https://linux-hardware.org/?probe=eb4a3f330e) | Feb 26, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [d3b6621252](https://linux-hardware.org/?probe=d3b6621252) | Feb 26, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [f589c3687b](https://linux-hardware.org/?probe=f589c3687b) | Feb 26, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [d610badec8](https://linux-hardware.org/?probe=d610badec8) | Feb 26, 2023 |
| Lenovo        | ThinkPad T61 6464A13        | Notebook    | [e981803528](https://linux-hardware.org/?probe=e981803528) | Feb 26, 2023 |
| Standard      | Unknown                     | Notebook    | [9d002e0593](https://linux-hardware.org/?probe=9d002e0593) | Feb 26, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [c204192a4b](https://linux-hardware.org/?probe=c204192a4b) | Feb 26, 2023 |
| Lenovo        | Legion 5 82B5               | Notebook    | [8db23a7237](https://linux-hardware.org/?probe=8db23a7237) | Feb 25, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [bd2c3ecd74](https://linux-hardware.org/?probe=bd2c3ecd74) | Feb 25, 2023 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [d6805fb81b](https://linux-hardware.org/?probe=d6805fb81b) | Feb 25, 2023 |
| Lenovo        | ThinkPad T480 20L5S03600    | Notebook    | [5c9736ab0c](https://linux-hardware.org/?probe=5c9736ab0c) | Feb 25, 2023 |
| Dell          | Vostro 14-5459              | Notebook    | [1f96898a48](https://linux-hardware.org/?probe=1f96898a48) | Feb 25, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [420520e3ab](https://linux-hardware.org/?probe=420520e3ab) | Feb 25, 2023 |
| Dell          | Latitude E6420              | Notebook    | [7ae4fe9340](https://linux-hardware.org/?probe=7ae4fe9340) | Feb 25, 2023 |
| Dell          | Latitude 5511               | Notebook    | [4402838fb3](https://linux-hardware.org/?probe=4402838fb3) | Feb 25, 2023 |
| Google        | Voxel                       | Notebook    | [ce917fe8ec](https://linux-hardware.org/?probe=ce917fe8ec) | Feb 25, 2023 |
| Google        | Voxel                       | Notebook    | [93ea143f69](https://linux-hardware.org/?probe=93ea143f69) | Feb 25, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [be0b15660e](https://linux-hardware.org/?probe=be0b15660e) | Feb 25, 2023 |
| HUAWEI        | MACH-WX9                    | Notebook    | [52924074db](https://linux-hardware.org/?probe=52924074db) | Feb 25, 2023 |
| Dell          | 0W2F8G A01                  | Desktop     | [1d0d54843b](https://linux-hardware.org/?probe=1d0d54843b) | Feb 25, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [87c5af58f5](https://linux-hardware.org/?probe=87c5af58f5) | Feb 25, 2023 |
| Dell          | Precision 5520              | Notebook    | [c41014658b](https://linux-hardware.org/?probe=c41014658b) | Feb 25, 2023 |
| Dell          | System XPS L321X            | Notebook    | [4de5ba1c80](https://linux-hardware.org/?probe=4de5ba1c80) | Feb 25, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [1c1e5c991f](https://linux-hardware.org/?probe=1c1e5c991f) | Feb 25, 2023 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [3575d2e78d](https://linux-hardware.org/?probe=3575d2e78d) | Feb 25, 2023 |
| Gigabyte      | H310M S2 x.x                | Desktop     | [27fa5a62b6](https://linux-hardware.org/?probe=27fa5a62b6) | Feb 24, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [9cbbaaf012](https://linux-hardware.org/?probe=9cbbaaf012) | Feb 24, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [4a0d65f6b5](https://linux-hardware.org/?probe=4a0d65f6b5) | Feb 24, 2023 |
| MSI           | B350M PRO-VDH               | Desktop     | [748d109cb3](https://linux-hardware.org/?probe=748d109cb3) | Feb 24, 2023 |
| HP            | 84EF 01100                  | All in one  | [d69b1aab65](https://linux-hardware.org/?probe=d69b1aab65) | Feb 24, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [f8f1005d73](https://linux-hardware.org/?probe=f8f1005d73) | Feb 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [787270bc9e](https://linux-hardware.org/?probe=787270bc9e) | Feb 24, 2023 |
| Lenovo        | Yoga Pro 14s IAH7 82TK      | Notebook    | [ade006d016](https://linux-hardware.org/?probe=ade006d016) | Feb 24, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | Desktop     | [5d901ddc4e](https://linux-hardware.org/?probe=5d901ddc4e) | Feb 24, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [362c88435e](https://linux-hardware.org/?probe=362c88435e) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [2bbce041f5](https://linux-hardware.org/?probe=2bbce041f5) | Feb 24, 2023 |
| MSI           | MS-7A32                     | Notebook    | [2312252934](https://linux-hardware.org/?probe=2312252934) | Feb 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [f7063f868f](https://linux-hardware.org/?probe=f7063f868f) | Feb 24, 2023 |
| HP            | 245 G8 Notebook PC          | Notebook    | [7686bcd76d](https://linux-hardware.org/?probe=7686bcd76d) | Feb 24, 2023 |
| Dell          | Inspiron 13-7359            | Notebook    | [7858955f02](https://linux-hardware.org/?probe=7858955f02) | Feb 24, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [1fb6ff6899](https://linux-hardware.org/?probe=1fb6ff6899) | Feb 24, 2023 |
| Toshiba       | Satellite L515              | Notebook    | [969c2042b9](https://linux-hardware.org/?probe=969c2042b9) | Feb 24, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [6e57f3a472](https://linux-hardware.org/?probe=6e57f3a472) | Feb 24, 2023 |
| MSI           | Z170A PC MATE               | Desktop     | [5ee58b9271](https://linux-hardware.org/?probe=5ee58b9271) | Feb 24, 2023 |
| Dell          | G5 5587                     | Notebook    | [1f43871064](https://linux-hardware.org/?probe=1f43871064) | Feb 24, 2023 |
| MSI           | Z87M GAMING                 | Desktop     | [0603accd89](https://linux-hardware.org/?probe=0603accd89) | Feb 24, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [acdea94715](https://linux-hardware.org/?probe=acdea94715) | Feb 23, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | Notebook    | [f92ac89547](https://linux-hardware.org/?probe=f92ac89547) | Feb 23, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [4b0436b55d](https://linux-hardware.org/?probe=4b0436b55d) | Feb 23, 2023 |
| Gateway       | SX2185                      | Desktop     | [32ab171e53](https://linux-hardware.org/?probe=32ab171e53) | Feb 23, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [193a97dfb1](https://linux-hardware.org/?probe=193a97dfb1) | Feb 23, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [a4c4313238](https://linux-hardware.org/?probe=a4c4313238) | Feb 23, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [bb2bef71e0](https://linux-hardware.org/?probe=bb2bef71e0) | Feb 23, 2023 |
| Lenovo        | ThinkPad X230 2325CS6       | Notebook    | [ed9501bbcb](https://linux-hardware.org/?probe=ed9501bbcb) | Feb 23, 2023 |
| Dell          | Inspiron 13-7359            | Notebook    | [39d95063c3](https://linux-hardware.org/?probe=39d95063c3) | Feb 23, 2023 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [0f251d6bbf](https://linux-hardware.org/?probe=0f251d6bbf) | Feb 23, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [eade3920d9](https://linux-hardware.org/?probe=eade3920d9) | Feb 23, 2023 |
| ASUSTek       | P5L-MX                      | Desktop     | [cc19e49d3c](https://linux-hardware.org/?probe=cc19e49d3c) | Feb 23, 2023 |
| ASUSTek       | K56CA                       | Notebook    | [d8475e4c48](https://linux-hardware.org/?probe=d8475e4c48) | Feb 23, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [e23562af05](https://linux-hardware.org/?probe=e23562af05) | Feb 23, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [b82d73c832](https://linux-hardware.org/?probe=b82d73c832) | Feb 22, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [becb5b0ba1](https://linux-hardware.org/?probe=becb5b0ba1) | Feb 22, 2023 |
| CyberPower... | Tracer IV GM5MQ8W           | Notebook    | [284e8a4fb1](https://linux-hardware.org/?probe=284e8a4fb1) | Feb 22, 2023 |
| ASUSTek       | P5L-MX                      | Desktop     | [9eb9ca3cfb](https://linux-hardware.org/?probe=9eb9ca3cfb) | Feb 22, 2023 |
| Dell          | Latitude E5570              | Notebook    | [338538c1c9](https://linux-hardware.org/?probe=338538c1c9) | Feb 22, 2023 |
| Gigabyte      | G5 KD                       | Notebook    | [65c50530c8](https://linux-hardware.org/?probe=65c50530c8) | Feb 22, 2023 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [7d3442e2a7](https://linux-hardware.org/?probe=7d3442e2a7) | Feb 22, 2023 |
| Alienware     | x14                         | Notebook    | [0b32a33625](https://linux-hardware.org/?probe=0b32a33625) | Feb 22, 2023 |
| Alienware     | x14                         | Notebook    | [04094754b6](https://linux-hardware.org/?probe=04094754b6) | Feb 22, 2023 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [3e5166108a](https://linux-hardware.org/?probe=3e5166108a) | Feb 22, 2023 |
| Acer          | Veriton N4630G              | Desktop     | [eb6a551e75](https://linux-hardware.org/?probe=eb6a551e75) | Feb 22, 2023 |
| HP            | Notebook                    | Notebook    | [f6d3ba25ba](https://linux-hardware.org/?probe=f6d3ba25ba) | Feb 22, 2023 |
| Samsung       | 767XCL                      | Notebook    | [3fb09fb626](https://linux-hardware.org/?probe=3fb09fb626) | Feb 22, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [aaad317fe4](https://linux-hardware.org/?probe=aaad317fe4) | Feb 22, 2023 |
| Dell          | Latitude 5491               | Notebook    | [fd68ba9595](https://linux-hardware.org/?probe=fd68ba9595) | Feb 21, 2023 |
| ASRockRack    | X470D4U                     | Desktop     | [162a5279bc](https://linux-hardware.org/?probe=162a5279bc) | Feb 21, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [a459216464](https://linux-hardware.org/?probe=a459216464) | Feb 21, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [7ead9488ae](https://linux-hardware.org/?probe=7ead9488ae) | Feb 21, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [b9117f0c6f](https://linux-hardware.org/?probe=b9117f0c6f) | Feb 21, 2023 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | Notebook    | [c0733771d5](https://linux-hardware.org/?probe=c0733771d5) | Feb 21, 2023 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | Notebook    | [039bb422e0](https://linux-hardware.org/?probe=039bb422e0) | Feb 21, 2023 |
| Acer          | Aspire SW3-013              | Notebook    | [f0111df214](https://linux-hardware.org/?probe=f0111df214) | Feb 21, 2023 |
| Alienware     | 15 R2                       | Notebook    | [96aa09ae59](https://linux-hardware.org/?probe=96aa09ae59) | Feb 21, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [bf037f7503](https://linux-hardware.org/?probe=bf037f7503) | Feb 21, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [67ba988b20](https://linux-hardware.org/?probe=67ba988b20) | Feb 21, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [d1f67d5e08](https://linux-hardware.org/?probe=d1f67d5e08) | Feb 21, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [edd5640ca7](https://linux-hardware.org/?probe=edd5640ca7) | Feb 21, 2023 |
| MSI           | H410M PRO-VH                | Desktop     | [669d124e33](https://linux-hardware.org/?probe=669d124e33) | Feb 21, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [9989903f85](https://linux-hardware.org/?probe=9989903f85) | Feb 21, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [2b329d108f](https://linux-hardware.org/?probe=2b329d108f) | Feb 21, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [53737369e8](https://linux-hardware.org/?probe=53737369e8) | Feb 21, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | Notebook    | [b8c4b41baf](https://linux-hardware.org/?probe=b8c4b41baf) | Feb 21, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [a3ed8101b1](https://linux-hardware.org/?probe=a3ed8101b1) | Feb 20, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [f6c80ff7a9](https://linux-hardware.org/?probe=f6c80ff7a9) | Feb 20, 2023 |
| Fujitsu       | LIFEBOOK E559               | Notebook    | [5e4c3607c7](https://linux-hardware.org/?probe=5e4c3607c7) | Feb 20, 2023 |
| Fujitsu       | LIFEBOOK A357               | Notebook    | [a813f73ea2](https://linux-hardware.org/?probe=a813f73ea2) | Feb 20, 2023 |
| MSI           | Bravo 15 B5ED               | Notebook    | [a0b7f1b5f8](https://linux-hardware.org/?probe=a0b7f1b5f8) | Feb 20, 2023 |
| Lenovo        | ThinkPad T530 239265U       | Notebook    | [9f60ca6bf5](https://linux-hardware.org/?probe=9f60ca6bf5) | Feb 20, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [542077cc42](https://linux-hardware.org/?probe=542077cc42) | Feb 20, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [8fd85f724b](https://linux-hardware.org/?probe=8fd85f724b) | Feb 20, 2023 |
| Microsoft     | Surface Go                  | Tablet      | [6f456ca669](https://linux-hardware.org/?probe=6f456ca669) | Feb 20, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [057dcdc86b](https://linux-hardware.org/?probe=057dcdc86b) | Feb 20, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [d8abf7361b](https://linux-hardware.org/?probe=d8abf7361b) | Feb 20, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [89eb85b36f](https://linux-hardware.org/?probe=89eb85b36f) | Feb 19, 2023 |
| Lenovo        | ThinkCentre M58 8910B4U     | Desktop     | [03c8e6d135](https://linux-hardware.org/?probe=03c8e6d135) | Feb 19, 2023 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [422b14d8d7](https://linux-hardware.org/?probe=422b14d8d7) | Feb 19, 2023 |
| Chuwi         | HeroBook Air                | Notebook    | [c669fff700](https://linux-hardware.org/?probe=c669fff700) | Feb 19, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [7432db815e](https://linux-hardware.org/?probe=7432db815e) | Feb 19, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [aaee9da394](https://linux-hardware.org/?probe=aaee9da394) | Feb 19, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [2af589c6e9](https://linux-hardware.org/?probe=2af589c6e9) | Feb 19, 2023 |
| ASRock        | X670E Pro RS                | Desktop     | [906d11e2a3](https://linux-hardware.org/?probe=906d11e2a3) | Feb 19, 2023 |
| GEO           | GeoFlex 340                 | Convertible | [f347582e5c](https://linux-hardware.org/?probe=f347582e5c) | Feb 19, 2023 |
| Samsung       | 930QED                      | Convertible | [f72fed80df](https://linux-hardware.org/?probe=f72fed80df) | Feb 19, 2023 |
| ASUSTek       | ROG Strix G733ZW_G733ZW     | Notebook    | [72f074b930](https://linux-hardware.org/?probe=72f074b930) | Feb 19, 2023 |
| Dell          | Latitude E6430              | Notebook    | [23c0ff9281](https://linux-hardware.org/?probe=23c0ff9281) | Feb 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [b1d168b6ce](https://linux-hardware.org/?probe=b1d168b6ce) | Feb 19, 2023 |
| Dell          | Latitude E6430              | Notebook    | [d97087b55f](https://linux-hardware.org/?probe=d97087b55f) | Feb 19, 2023 |
| Lenovo        | ThinkPad E555 20DH000TUK    | Notebook    | [b2d5c9de8b](https://linux-hardware.org/?probe=b2d5c9de8b) | Feb 19, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [42099690a6](https://linux-hardware.org/?probe=42099690a6) | Feb 19, 2023 |
| Standard      | Unknown                     | Notebook    | [149bdc4e40](https://linux-hardware.org/?probe=149bdc4e40) | Feb 19, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [9b0ecbd3c7](https://linux-hardware.org/?probe=9b0ecbd3c7) | Feb 19, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | Notebook    | [ee24b75c39](https://linux-hardware.org/?probe=ee24b75c39) | Feb 19, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [6eda9f2592](https://linux-hardware.org/?probe=6eda9f2592) | Feb 19, 2023 |
| Dell          | Precision M4500             | Notebook    | [b0d8bf3c56](https://linux-hardware.org/?probe=b0d8bf3c56) | Feb 19, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [5cade7cfc3](https://linux-hardware.org/?probe=5cade7cfc3) | Feb 19, 2023 |
| ASUSTek       | P5Q SE2                     | Desktop     | [37b0d0609f](https://linux-hardware.org/?probe=37b0d0609f) | Feb 18, 2023 |
| Google        | Kled                        | Notebook    | [788d726509](https://linux-hardware.org/?probe=788d726509) | Feb 18, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [9b53b2b842](https://linux-hardware.org/?probe=9b53b2b842) | Feb 18, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [cdfcc639d3](https://linux-hardware.org/?probe=cdfcc639d3) | Feb 18, 2023 |
| Lenovo        | ThinkPad T530 2429F27       | Notebook    | [b835147a32](https://linux-hardware.org/?probe=b835147a32) | Feb 18, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | Notebook    | [fb2cbe3576](https://linux-hardware.org/?probe=fb2cbe3576) | Feb 18, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [a424b3aa47](https://linux-hardware.org/?probe=a424b3aa47) | Feb 18, 2023 |
| ASRock        | H110 Pro BTC+               | Desktop     | [bce117c4dc](https://linux-hardware.org/?probe=bce117c4dc) | Feb 18, 2023 |
| MSI           | Z170A KRAIT GAMING          | Desktop     | [27dcbbe1d7](https://linux-hardware.org/?probe=27dcbbe1d7) | Feb 18, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [831d4806fb](https://linux-hardware.org/?probe=831d4806fb) | Feb 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [e7988c5ab6](https://linux-hardware.org/?probe=e7988c5ab6) | Feb 18, 2023 |
| MSI           | H410M PRO-VH                | Desktop     | [ccc1cbf2fa](https://linux-hardware.org/?probe=ccc1cbf2fa) | Feb 18, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [f14a791491](https://linux-hardware.org/?probe=f14a791491) | Feb 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | Notebook    | [6d2b283e83](https://linux-hardware.org/?probe=6d2b283e83) | Feb 18, 2023 |
| Dell          | Precision 5560              | Notebook    | [24e5de4a3d](https://linux-hardware.org/?probe=24e5de4a3d) | Feb 18, 2023 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | Desktop     | [5fe0f2c1fe](https://linux-hardware.org/?probe=5fe0f2c1fe) | Feb 18, 2023 |
| Samsung       | 730QDA                      | Convertible | [902b86cb84](https://linux-hardware.org/?probe=902b86cb84) | Feb 18, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [c4a1fe4a4f](https://linux-hardware.org/?probe=c4a1fe4a4f) | Feb 17, 2023 |
| Lenovo        | ThinkPad T490 20N2001YUS    | Notebook    | [53ef9ffad8](https://linux-hardware.org/?probe=53ef9ffad8) | Feb 17, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [f9fb638882](https://linux-hardware.org/?probe=f9fb638882) | Feb 17, 2023 |
| Dell          | Latitude 5491               | Notebook    | [8a3298cdff](https://linux-hardware.org/?probe=8a3298cdff) | Feb 17, 2023 |
| ASUSTek       | PRIME Z690M-PLUS D4         | Desktop     | [750c0f6337](https://linux-hardware.org/?probe=750c0f6337) | Feb 17, 2023 |
| Hardkernel    | ODROID-N2                   | Soc         | [9a8138252f](https://linux-hardware.org/?probe=9a8138252f) | Feb 17, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [e4483255db](https://linux-hardware.org/?probe=e4483255db) | Feb 17, 2023 |
| ASRock        | X470 Taichi                 | Desktop     | [71685845fe](https://linux-hardware.org/?probe=71685845fe) | Feb 17, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [8c3926e125](https://linux-hardware.org/?probe=8c3926e125) | Feb 17, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [09aefeb3d6](https://linux-hardware.org/?probe=09aefeb3d6) | Feb 17, 2023 |
| Dell          | Inspiron 5566               | Notebook    | [502adcba49](https://linux-hardware.org/?probe=502adcba49) | Feb 17, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [8e3bad7795](https://linux-hardware.org/?probe=8e3bad7795) | Feb 17, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | Notebook    | [cc44156b99](https://linux-hardware.org/?probe=cc44156b99) | Feb 17, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | Notebook    | [bc234d0b32](https://linux-hardware.org/?probe=bc234d0b32) | Feb 17, 2023 |
| HP            | ENVY Laptop 17-ch2xxx       | Notebook    | [c1abb80cb1](https://linux-hardware.org/?probe=c1abb80cb1) | Feb 17, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [add68ac711](https://linux-hardware.org/?probe=add68ac711) | Feb 16, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [a19a7a2edd](https://linux-hardware.org/?probe=a19a7a2edd) | Feb 16, 2023 |
| Lenovo        | ZIWB2                       | Notebook    | [8ade075157](https://linux-hardware.org/?probe=8ade075157) | Feb 16, 2023 |
| HP            | 245 G8 Notebook PC          | Notebook    | [c48e458030](https://linux-hardware.org/?probe=c48e458030) | Feb 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [4657fc266d](https://linux-hardware.org/?probe=4657fc266d) | Feb 16, 2023 |
| ASUSTek       | EX-H310M-V3 R2.0            | Desktop     | [d42c40dd2e](https://linux-hardware.org/?probe=d42c40dd2e) | Feb 16, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [218e0f7ad6](https://linux-hardware.org/?probe=218e0f7ad6) | Feb 16, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [71778cedf9](https://linux-hardware.org/?probe=71778cedf9) | Feb 16, 2023 |
| Samsung       | 940XFG                      | Notebook    | [56f236f8ab](https://linux-hardware.org/?probe=56f236f8ab) | Feb 16, 2023 |
| Dell          | Latitude 7390 2-in-1        | Convertible | [66dbe64897](https://linux-hardware.org/?probe=66dbe64897) | Feb 16, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [ddc2c7ec7a](https://linux-hardware.org/?probe=ddc2c7ec7a) | Feb 16, 2023 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | Notebook    | [5a3b0950b3](https://linux-hardware.org/?probe=5a3b0950b3) | Feb 16, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [f4e8b0e952](https://linux-hardware.org/?probe=f4e8b0e952) | Feb 16, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [09301690c5](https://linux-hardware.org/?probe=09301690c5) | Feb 15, 2023 |
| ASUSTek       | P8Z77-V PRO/THUNDERBOLT     | Desktop     | [a370fca217](https://linux-hardware.org/?probe=a370fca217) | Feb 15, 2023 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [ca54397755](https://linux-hardware.org/?probe=ca54397755) | Feb 15, 2023 |
| HP            | Notebook                    | Notebook    | [9fe647f9a1](https://linux-hardware.org/?probe=9fe647f9a1) | Feb 15, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [36f57d56f8](https://linux-hardware.org/?probe=36f57d56f8) | Feb 15, 2023 |
| HP            | Notebook                    | Notebook    | [c4516fb37a](https://linux-hardware.org/?probe=c4516fb37a) | Feb 15, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [7fd55795a0](https://linux-hardware.org/?probe=7fd55795a0) | Feb 15, 2023 |
| Lenovo        | ThinkPad P50 20EQS64N09     | Notebook    | [72fad631b7](https://linux-hardware.org/?probe=72fad631b7) | Feb 15, 2023 |
| ASUSTek       | PN53                        | Mini pc     | [73f7fb3f85](https://linux-hardware.org/?probe=73f7fb3f85) | Feb 15, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [70885f1dfd](https://linux-hardware.org/?probe=70885f1dfd) | Feb 15, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [92a9452070](https://linux-hardware.org/?probe=92a9452070) | Feb 15, 2023 |
| MSI           | FM2-A75MA-E35               | Desktop     | [a7f2ca398d](https://linux-hardware.org/?probe=a7f2ca398d) | Feb 15, 2023 |
| Dell          | Inspiron 7375               | Notebook    | [3916d619ed](https://linux-hardware.org/?probe=3916d619ed) | Feb 15, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [1ca19c3d1d](https://linux-hardware.org/?probe=1ca19c3d1d) | Feb 14, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [7d8c3e7e48](https://linux-hardware.org/?probe=7d8c3e7e48) | Feb 14, 2023 |
| ASUSTek       | UL30A                       | Notebook    | [90114a4fe4](https://linux-hardware.org/?probe=90114a4fe4) | Feb 14, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [390686f5f6](https://linux-hardware.org/?probe=390686f5f6) | Feb 14, 2023 |
| HP            | ProBook 440 G7              | Notebook    | [bc4811db07](https://linux-hardware.org/?probe=bc4811db07) | Feb 14, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [cbcadcf80a](https://linux-hardware.org/?probe=cbcadcf80a) | Feb 14, 2023 |
| Dell          | Latitude E7270              | Notebook    | [03199b7612](https://linux-hardware.org/?probe=03199b7612) | Feb 14, 2023 |
| Lenovo        | IdeaPad 520S-14IKB 81BL     | Notebook    | [008d06fbf8](https://linux-hardware.org/?probe=008d06fbf8) | Feb 14, 2023 |
| Timi          | Xiaomi NoteBook Pro         | Notebook    | [561e1a6160](https://linux-hardware.org/?probe=561e1a6160) | Feb 14, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [e718a6af67](https://linux-hardware.org/?probe=e718a6af67) | Feb 14, 2023 |
| Dell          | Latitude 7430               | Notebook    | [82dcb0a8a2](https://linux-hardware.org/?probe=82dcb0a8a2) | Feb 14, 2023 |
| Dell          | G3 3579                     | Notebook    | [35c8b69b8c](https://linux-hardware.org/?probe=35c8b69b8c) | Feb 14, 2023 |
| ASRock        | X370 Gaming X               | Desktop     | [2b9a026876](https://linux-hardware.org/?probe=2b9a026876) | Feb 14, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [2f78b0c253](https://linux-hardware.org/?probe=2f78b0c253) | Feb 14, 2023 |
| HP            | 8714                        | Desktop     | [19a66b5101](https://linux-hardware.org/?probe=19a66b5101) | Feb 14, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [43dff5bee7](https://linux-hardware.org/?probe=43dff5bee7) | Feb 14, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [10c8101c9b](https://linux-hardware.org/?probe=10c8101c9b) | Feb 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [ac71e5b8ef](https://linux-hardware.org/?probe=ac71e5b8ef) | Feb 14, 2023 |
| Dell          | Inspiron 14 5420            | Notebook    | [45862fde09](https://linux-hardware.org/?probe=45862fde09) | Feb 13, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | Notebook    | [1f0e965483](https://linux-hardware.org/?probe=1f0e965483) | Feb 13, 2023 |
| Dell          | Inspiron 14 5420            | Notebook    | [8153aeb3fb](https://linux-hardware.org/?probe=8153aeb3fb) | Feb 13, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [01319ac289](https://linux-hardware.org/?probe=01319ac289) | Feb 13, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [7e81f35584](https://linux-hardware.org/?probe=7e81f35584) | Feb 13, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [f701208fd4](https://linux-hardware.org/?probe=f701208fd4) | Feb 13, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | Notebook    | [3b7765dfcc](https://linux-hardware.org/?probe=3b7765dfcc) | Feb 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [6add161dbe](https://linux-hardware.org/?probe=6add161dbe) | Feb 13, 2023 |
| Dell          | Latitude 5511               | Notebook    | [161095d97a](https://linux-hardware.org/?probe=161095d97a) | Feb 13, 2023 |
| MSI           | X99A SLI PLUS               | Desktop     | [98447ce3dd](https://linux-hardware.org/?probe=98447ce3dd) | Feb 13, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | Notebook    | [7e90fe56d1](https://linux-hardware.org/?probe=7e90fe56d1) | Feb 13, 2023 |
| MSI           | Raider GE77HX 12UHS         | Notebook    | [abd464b0d3](https://linux-hardware.org/?probe=abd464b0d3) | Feb 13, 2023 |
| HP            | ProBook 445 G7              | Notebook    | [7fdcffc633](https://linux-hardware.org/?probe=7fdcffc633) | Feb 13, 2023 |
| Dell          | 0R6PCT A01                  | Desktop     | [4126ed8507](https://linux-hardware.org/?probe=4126ed8507) | Feb 13, 2023 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | Notebook    | [0560a363b8](https://linux-hardware.org/?probe=0560a363b8) | Feb 12, 2023 |
| Dell          | Venue 10 Pro 5055           | Notebook    | [7afcfff799](https://linux-hardware.org/?probe=7afcfff799) | Feb 12, 2023 |
| Pegatron      | 2AB6                        | Desktop     | [65b3bb622e](https://linux-hardware.org/?probe=65b3bb622e) | Feb 12, 2023 |
| Acer          | Aspire A715-74G             | Notebook    | [cdd913ae48](https://linux-hardware.org/?probe=cdd913ae48) | Feb 12, 2023 |
| Dell          | Latitude E6420              | Notebook    | [6ffa1ea310](https://linux-hardware.org/?probe=6ffa1ea310) | Feb 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [04cfa15383](https://linux-hardware.org/?probe=04cfa15383) | Feb 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [3c8717baf4](https://linux-hardware.org/?probe=3c8717baf4) | Feb 12, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [8f74caf33e](https://linux-hardware.org/?probe=8f74caf33e) | Feb 12, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [b569293b7b](https://linux-hardware.org/?probe=b569293b7b) | Feb 12, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [a4b4558244](https://linux-hardware.org/?probe=a4b4558244) | Feb 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [1e3ceef5e6](https://linux-hardware.org/?probe=1e3ceef5e6) | Feb 12, 2023 |
| HP            | Notebook                    | Notebook    | [729f2b5250](https://linux-hardware.org/?probe=729f2b5250) | Feb 12, 2023 |
| HP            | Notebook                    | Notebook    | [155c8fa16e](https://linux-hardware.org/?probe=155c8fa16e) | Feb 12, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [a5469c55ac](https://linux-hardware.org/?probe=a5469c55ac) | Feb 12, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [365b6606cd](https://linux-hardware.org/?probe=365b6606cd) | Feb 12, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [2d63c8d887](https://linux-hardware.org/?probe=2d63c8d887) | Feb 12, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [c8caa92db3](https://linux-hardware.org/?probe=c8caa92db3) | Feb 11, 2023 |
| Lenovo        | IdeaPad S540-15IWL          | Notebook    | [321710ca2d](https://linux-hardware.org/?probe=321710ca2d) | Feb 11, 2023 |
| Pegatron      | 2AB6                        | Desktop     | [1f727ee133](https://linux-hardware.org/?probe=1f727ee133) | Feb 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [40116058d1](https://linux-hardware.org/?probe=40116058d1) | Feb 11, 2023 |
| HONOR         | BBR-WAX9                    | Notebook    | [de54b14304](https://linux-hardware.org/?probe=de54b14304) | Feb 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [8e00bdf032](https://linux-hardware.org/?probe=8e00bdf032) | Feb 11, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [22d5eabee5](https://linux-hardware.org/?probe=22d5eabee5) | Feb 11, 2023 |
| ASUSTek       | Z97-P                       | Desktop     | [004535fd1c](https://linux-hardware.org/?probe=004535fd1c) | Feb 11, 2023 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [2beb0c0b30](https://linux-hardware.org/?probe=2beb0c0b30) | Feb 11, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [a1133b56be](https://linux-hardware.org/?probe=a1133b56be) | Feb 11, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [e2eeee26af](https://linux-hardware.org/?probe=e2eeee26af) | Feb 11, 2023 |
| ASRock        | Z790 Pro RS WiFi            | Desktop     | [c530bf4283](https://linux-hardware.org/?probe=c530bf4283) | Feb 11, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [6474c43d80](https://linux-hardware.org/?probe=6474c43d80) | Feb 11, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [f56c83d6dd](https://linux-hardware.org/?probe=f56c83d6dd) | Feb 11, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [d8a854baec](https://linux-hardware.org/?probe=d8a854baec) | Feb 11, 2023 |
| Dell          | Latitude E7270              | Notebook    | [c684709755](https://linux-hardware.org/?probe=c684709755) | Feb 11, 2023 |
| Acer          | TravelMate 7730             | Notebook    | [a9a9e21b5a](https://linux-hardware.org/?probe=a9a9e21b5a) | Feb 10, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [6c1d31a394](https://linux-hardware.org/?probe=6c1d31a394) | Feb 10, 2023 |
| Dell          | Inspiron 7559               | Notebook    | [956a602343](https://linux-hardware.org/?probe=956a602343) | Feb 10, 2023 |
| ASRock        | A300M-STX                   | Desktop     | [79266ec6c7](https://linux-hardware.org/?probe=79266ec6c7) | Feb 10, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [9a2b8045de](https://linux-hardware.org/?probe=9a2b8045de) | Feb 10, 2023 |
| ASUSTek       | ROG Strix G733QR_G733QR     | Notebook    | [da12318597](https://linux-hardware.org/?probe=da12318597) | Feb 10, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [0461c55b4a](https://linux-hardware.org/?probe=0461c55b4a) | Feb 10, 2023 |
| MSI           | Raider GE77HX 12UHS         | Notebook    | [d77cac7fb6](https://linux-hardware.org/?probe=d77cac7fb6) | Feb 10, 2023 |
| HP            | 8714                        | Desktop     | [3938395f75](https://linux-hardware.org/?probe=3938395f75) | Feb 10, 2023 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | Notebook    | [9b8563ab53](https://linux-hardware.org/?probe=9b8563ab53) | Feb 10, 2023 |
| ASUSTek       | PRIME H410M-K               | Desktop     | [c3a837a320](https://linux-hardware.org/?probe=c3a837a320) | Feb 09, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [70b81f3738](https://linux-hardware.org/?probe=70b81f3738) | Feb 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [3f4b71a601](https://linux-hardware.org/?probe=3f4b71a601) | Feb 09, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [25e4994344](https://linux-hardware.org/?probe=25e4994344) | Feb 09, 2023 |
| Lenovo        | ThinkPad T590 20N5S4R800    | Notebook    | [6a55f84594](https://linux-hardware.org/?probe=6a55f84594) | Feb 09, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [91de8b5956](https://linux-hardware.org/?probe=91de8b5956) | Feb 09, 2023 |
| Monster       | TULPAR T7 V5.x              | Notebook    | [edc2a0bc35](https://linux-hardware.org/?probe=edc2a0bc35) | Feb 09, 2023 |
| Monster       | TULPAR T7 V5.x              | Notebook    | [8d1a082e35](https://linux-hardware.org/?probe=8d1a082e35) | Feb 09, 2023 |
| HP            | 83E4                        | All in one  | [cdefba9e55](https://linux-hardware.org/?probe=cdefba9e55) | Feb 09, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [8d2e488f38](https://linux-hardware.org/?probe=8d2e488f38) | Feb 09, 2023 |
| Intel         | LADPNVMO AAE76523-300       | Desktop     | [6ced92edc7](https://linux-hardware.org/?probe=6ced92edc7) | Feb 09, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [467c3e9149](https://linux-hardware.org/?probe=467c3e9149) | Feb 09, 2023 |
| HP            | 2000                        | Notebook    | [f76b7389d7](https://linux-hardware.org/?probe=f76b7389d7) | Feb 09, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [81a3a141ba](https://linux-hardware.org/?probe=81a3a141ba) | Feb 08, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [78d55087bb](https://linux-hardware.org/?probe=78d55087bb) | Feb 08, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C7C... | Notebook    | [26fb33ec6c](https://linux-hardware.org/?probe=26fb33ec6c) | Feb 08, 2023 |
| Dell          | Latitude 3570               | Notebook    | [dc460632ef](https://linux-hardware.org/?probe=dc460632ef) | Feb 08, 2023 |
| MSI           | H110M PRO-VD PLUS           | Desktop     | [c296dedf74](https://linux-hardware.org/?probe=c296dedf74) | Feb 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [69c30e6f7b](https://linux-hardware.org/?probe=69c30e6f7b) | Feb 08, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [bc2ea675c8](https://linux-hardware.org/?probe=bc2ea675c8) | Feb 08, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [a12cca2eeb](https://linux-hardware.org/?probe=a12cca2eeb) | Feb 08, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [b02b8779fc](https://linux-hardware.org/?probe=b02b8779fc) | Feb 08, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [5c5d5d4304](https://linux-hardware.org/?probe=5c5d5d4304) | Feb 08, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [0b2a31bed4](https://linux-hardware.org/?probe=0b2a31bed4) | Feb 08, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS1... | Notebook    | [9bf97a14cf](https://linux-hardware.org/?probe=9bf97a14cf) | Feb 08, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [b440353d20](https://linux-hardware.org/?probe=b440353d20) | Feb 08, 2023 |
| Google        | Delbin                      | Notebook    | [268fbe9849](https://linux-hardware.org/?probe=268fbe9849) | Feb 08, 2023 |
| Google        | Delbin                      | Notebook    | [1afd4fec8d](https://linux-hardware.org/?probe=1afd4fec8d) | Feb 08, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS1... | Notebook    | [5e5ec021d0](https://linux-hardware.org/?probe=5e5ec021d0) | Feb 08, 2023 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [21910f6687](https://linux-hardware.org/?probe=21910f6687) | Feb 08, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [fd61c4416f](https://linux-hardware.org/?probe=fd61c4416f) | Feb 08, 2023 |
| ASRock        | H81M-HG4 R4.0               | Desktop     | [127269499d](https://linux-hardware.org/?probe=127269499d) | Feb 07, 2023 |
| Lenovo        | ThinkServer TS140           | Desktop     | [1bac17097f](https://linux-hardware.org/?probe=1bac17097f) | Feb 07, 2023 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [ace0ce95b9](https://linux-hardware.org/?probe=ace0ce95b9) | Feb 07, 2023 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [47153e938c](https://linux-hardware.org/?probe=47153e938c) | Feb 07, 2023 |
| BESSTAR Te... | B550                        | Desktop     | [49e414926e](https://linux-hardware.org/?probe=49e414926e) | Feb 07, 2023 |
| HP            | Pavilion 17                 | Notebook    | [9bd81582a4](https://linux-hardware.org/?probe=9bd81582a4) | Feb 07, 2023 |
| HP            | Pavilion 17                 | Notebook    | [45eb87271b](https://linux-hardware.org/?probe=45eb87271b) | Feb 07, 2023 |
| TUXEDO        | InfinityBook S 14 Gen6      | Notebook    | [9e019a0396](https://linux-hardware.org/?probe=9e019a0396) | Feb 07, 2023 |
| MSI           | Modern 14 B11MOU            | Notebook    | [325806b7cc](https://linux-hardware.org/?probe=325806b7cc) | Feb 07, 2023 |
| MSI           | Modern 14 B11MOU            | Notebook    | [870a2912c9](https://linux-hardware.org/?probe=870a2912c9) | Feb 07, 2023 |
| Fujitsu       | LIFEBOOK T938               | Convertible | [83e2f6d1a6](https://linux-hardware.org/?probe=83e2f6d1a6) | Feb 07, 2023 |
| HUAWEI        | MACH-WX9                    | Notebook    | [263101d492](https://linux-hardware.org/?probe=263101d492) | Feb 07, 2023 |
| Dell          | Latitude 5330               | Notebook    | [30cd96be4d](https://linux-hardware.org/?probe=30cd96be4d) | Feb 07, 2023 |
| Timi          | TM1613                      | Notebook    | [503133b0db](https://linux-hardware.org/?probe=503133b0db) | Feb 07, 2023 |
| Samsung       | 900X5N                      | Notebook    | [91793918de](https://linux-hardware.org/?probe=91793918de) | Feb 07, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [e82192ba4c](https://linux-hardware.org/?probe=e82192ba4c) | Feb 07, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [d91fe3e151](https://linux-hardware.org/?probe=d91fe3e151) | Feb 07, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [da8dac3c03](https://linux-hardware.org/?probe=da8dac3c03) | Feb 07, 2023 |
| Google        | Kefka                       | Notebook    | [5f290f685b](https://linux-hardware.org/?probe=5f290f685b) | Feb 06, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [31a56f80dd](https://linux-hardware.org/?probe=31a56f80dd) | Feb 06, 2023 |
| Dell          | Latitude 5490               | Notebook    | [95de125f35](https://linux-hardware.org/?probe=95de125f35) | Feb 06, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [ff01db5c9a](https://linux-hardware.org/?probe=ff01db5c9a) | Feb 06, 2023 |
| ASUSTek       | P453UA                      | Notebook    | [476ff28577](https://linux-hardware.org/?probe=476ff28577) | Feb 06, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [f1e58aba53](https://linux-hardware.org/?probe=f1e58aba53) | Feb 06, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [44de7ac1aa](https://linux-hardware.org/?probe=44de7ac1aa) | Feb 06, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [10cf328828](https://linux-hardware.org/?probe=10cf328828) | Feb 06, 2023 |
| ASUSTek       | G73Sw                       | Notebook    | [42e7c32817](https://linux-hardware.org/?probe=42e7c32817) | Feb 06, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [781dc9da09](https://linux-hardware.org/?probe=781dc9da09) | Feb 06, 2023 |
| Dell          | Inspiron 5749               | Notebook    | [2fbf439175](https://linux-hardware.org/?probe=2fbf439175) | Feb 06, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [1f2418bafb](https://linux-hardware.org/?probe=1f2418bafb) | Feb 06, 2023 |
| Toshiba       | Satellite L50-B             | Notebook    | [fe59cbe322](https://linux-hardware.org/?probe=fe59cbe322) | Feb 06, 2023 |
| Compal        | DIP00                       | Desktop     | [632d4c313a](https://linux-hardware.org/?probe=632d4c313a) | Feb 06, 2023 |
| HP            | 2000                        | Notebook    | [5e672192b6](https://linux-hardware.org/?probe=5e672192b6) | Feb 06, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [f3ec6a2ed1](https://linux-hardware.org/?probe=f3ec6a2ed1) | Feb 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [da270fa237](https://linux-hardware.org/?probe=da270fa237) | Feb 05, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [99d0ce5421](https://linux-hardware.org/?probe=99d0ce5421) | Feb 05, 2023 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [6490f4cb92](https://linux-hardware.org/?probe=6490f4cb92) | Feb 05, 2023 |
| HP            | 1589                        | Desktop     | [1872d63c2b](https://linux-hardware.org/?probe=1872d63c2b) | Feb 05, 2023 |
| HP            | 1589                        | Desktop     | [69c0ab962c](https://linux-hardware.org/?probe=69c0ab962c) | Feb 05, 2023 |
| HP            | EliteBook x360 830 G6       | Convertible | [3801f86839](https://linux-hardware.org/?probe=3801f86839) | Feb 05, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [de72d92ada](https://linux-hardware.org/?probe=de72d92ada) | Feb 05, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [c222b31f37](https://linux-hardware.org/?probe=c222b31f37) | Feb 05, 2023 |
| Google        | Kefka                       | Notebook    | [59e3f92752](https://linux-hardware.org/?probe=59e3f92752) | Feb 05, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | Notebook    | [a0fea9707e](https://linux-hardware.org/?probe=a0fea9707e) | Feb 05, 2023 |
| Intel         | X99                         | Desktop     | [e8790caf8d](https://linux-hardware.org/?probe=e8790caf8d) | Feb 05, 2023 |
| ASUSTek       | X556UV                      | Notebook    | [ae90dba4ca](https://linux-hardware.org/?probe=ae90dba4ca) | Feb 04, 2023 |
| Dell          | Inspiron 3593               | Notebook    | [2e87d3f607](https://linux-hardware.org/?probe=2e87d3f607) | Feb 04, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [944149e350](https://linux-hardware.org/?probe=944149e350) | Feb 04, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [9f5df7e4e0](https://linux-hardware.org/?probe=9f5df7e4e0) | Feb 04, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [c4c5c0888a](https://linux-hardware.org/?probe=c4c5c0888a) | Feb 04, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [8771985f5b](https://linux-hardware.org/?probe=8771985f5b) | Feb 04, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [9592836c3b](https://linux-hardware.org/?probe=9592836c3b) | Feb 04, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [200495d065](https://linux-hardware.org/?probe=200495d065) | Feb 04, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [dc3d1a065f](https://linux-hardware.org/?probe=dc3d1a065f) | Feb 04, 2023 |
| ASUSTek       | X200CA                      | Notebook    | [38cdc2564e](https://linux-hardware.org/?probe=38cdc2564e) | Feb 04, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [3b09c5ed9e](https://linux-hardware.org/?probe=3b09c5ed9e) | Feb 04, 2023 |
| HP            | Laptop 17-ak0xx             | Notebook    | [2ec4deba0b](https://linux-hardware.org/?probe=2ec4deba0b) | Feb 04, 2023 |
| Gigabyte      | Z790 GAMING X AX            | Desktop     | [1c6725b5eb](https://linux-hardware.org/?probe=1c6725b5eb) | Feb 04, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [cfaa43cc81](https://linux-hardware.org/?probe=cfaa43cc81) | Feb 04, 2023 |
| ASUSTek       | X200CA                      | Notebook    | [8c2a91c204](https://linux-hardware.org/?probe=8c2a91c204) | Feb 04, 2023 |
| SiComputer    | Nauta 01C                   | Notebook    | [1579a837f7](https://linux-hardware.org/?probe=1579a837f7) | Feb 04, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [43a0910ff6](https://linux-hardware.org/?probe=43a0910ff6) | Feb 04, 2023 |
| Lenovo        | ThinkPad P72 20MB0005GE     | Notebook    | [6322972a9c](https://linux-hardware.org/?probe=6322972a9c) | Feb 04, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [a17959ea9b](https://linux-hardware.org/?probe=a17959ea9b) | Feb 04, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [3633683d62](https://linux-hardware.org/?probe=3633683d62) | Feb 04, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [c0434c976e](https://linux-hardware.org/?probe=c0434c976e) | Feb 04, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [f2578f11e1](https://linux-hardware.org/?probe=f2578f11e1) | Feb 03, 2023 |
| HP            | ZBook Power 15.6 inch G9... | Notebook    | [1e38d08821](https://linux-hardware.org/?probe=1e38d08821) | Feb 03, 2023 |
| Dell          | Latitude 5530               | Notebook    | [dd0a933124](https://linux-hardware.org/?probe=dd0a933124) | Feb 03, 2023 |
| Dynabook      | PORTEGE X30L-K              | Notebook    | [af43366b45](https://linux-hardware.org/?probe=af43366b45) | Feb 03, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [fa1e255519](https://linux-hardware.org/?probe=fa1e255519) | Feb 03, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [d7fff6982b](https://linux-hardware.org/?probe=d7fff6982b) | Feb 03, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [ada6dd2b76](https://linux-hardware.org/?probe=ada6dd2b76) | Feb 03, 2023 |
| Supermicro    | X11SSH-F                    | Server      | [a65a6e89d1](https://linux-hardware.org/?probe=a65a6e89d1) | Feb 03, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | Notebook    | [a1073e64f7](https://linux-hardware.org/?probe=a1073e64f7) | Feb 03, 2023 |
| Dell          | Latitude E6430              | Notebook    | [10b3b0cfbb](https://linux-hardware.org/?probe=10b3b0cfbb) | Feb 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [9c5cfbc1a1](https://linux-hardware.org/?probe=9c5cfbc1a1) | Feb 03, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [b660fd4859](https://linux-hardware.org/?probe=b660fd4859) | Feb 03, 2023 |
| ASUSTek       | UL30A                       | Notebook    | [11885376b2](https://linux-hardware.org/?probe=11885376b2) | Feb 03, 2023 |
| HP            | ProBook 440 G7              | Notebook    | [f9a4f80656](https://linux-hardware.org/?probe=f9a4f80656) | Feb 03, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [5e9c75d478](https://linux-hardware.org/?probe=5e9c75d478) | Feb 03, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [e680a7484e](https://linux-hardware.org/?probe=e680a7484e) | Feb 03, 2023 |
| HP            | 8714                        | Desktop     | [b8abceccbc](https://linux-hardware.org/?probe=b8abceccbc) | Feb 03, 2023 |
| ASUSTek       | G751JT                      | Notebook    | [2085089213](https://linux-hardware.org/?probe=2085089213) | Feb 03, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [f794d33e76](https://linux-hardware.org/?probe=f794d33e76) | Feb 02, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [8c9b8348a4](https://linux-hardware.org/?probe=8c9b8348a4) | Feb 02, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [bd19e14a45](https://linux-hardware.org/?probe=bd19e14a45) | Feb 02, 2023 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [a7eba3e52d](https://linux-hardware.org/?probe=a7eba3e52d) | Feb 02, 2023 |
| Pegatron      | IPXSB-H61                   | Desktop     | [a694854d87](https://linux-hardware.org/?probe=a694854d87) | Feb 02, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [e49b22de8a](https://linux-hardware.org/?probe=e49b22de8a) | Feb 02, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [ba43497e32](https://linux-hardware.org/?probe=ba43497e32) | Feb 02, 2023 |
| Acer          | Aspire A715-42G             | Notebook    | [a169951063](https://linux-hardware.org/?probe=a169951063) | Feb 02, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [7dd8dceb80](https://linux-hardware.org/?probe=7dd8dceb80) | Feb 02, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [27c816b62a](https://linux-hardware.org/?probe=27c816b62a) | Feb 02, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [3339c49f38](https://linux-hardware.org/?probe=3339c49f38) | Feb 02, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [1c6ed7ede6](https://linux-hardware.org/?probe=1c6ed7ede6) | Feb 02, 2023 |
| ASUSTek       | ZenBook UX425JA_UX425JA     | Notebook    | [367646ee16](https://linux-hardware.org/?probe=367646ee16) | Feb 02, 2023 |
| Acer          | Veriton M2631 V:1.0         | Desktop     | [28e1975b51](https://linux-hardware.org/?probe=28e1975b51) | Feb 02, 2023 |
| Lenovo        | ZIWB2                       | Notebook    | [b7ff6b4dd5](https://linux-hardware.org/?probe=b7ff6b4dd5) | Feb 02, 2023 |
| ASUSTek       | K54L                        | Notebook    | [8568b17267](https://linux-hardware.org/?probe=8568b17267) | Feb 02, 2023 |
| Acer          | Aspire A715-42G             | Notebook    | [45890fca78](https://linux-hardware.org/?probe=45890fca78) | Feb 02, 2023 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [5ee874041a](https://linux-hardware.org/?probe=5ee874041a) | Feb 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [159a453649](https://linux-hardware.org/?probe=159a453649) | Feb 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [0538afb301](https://linux-hardware.org/?probe=0538afb301) | Feb 02, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [78ea388883](https://linux-hardware.org/?probe=78ea388883) | Feb 02, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [9b8d82dfcd](https://linux-hardware.org/?probe=9b8d82dfcd) | Feb 02, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [c7b6222f08](https://linux-hardware.org/?probe=c7b6222f08) | Feb 02, 2023 |
| ASRock        | Z77 Extreme4                | Desktop     | [6598bc47dd](https://linux-hardware.org/?probe=6598bc47dd) | Feb 02, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [15c523ee98](https://linux-hardware.org/?probe=15c523ee98) | Feb 02, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [f2919f7135](https://linux-hardware.org/?probe=f2919f7135) | Feb 01, 2023 |
| Dell          | Latitude E6430              | Notebook    | [55c398146b](https://linux-hardware.org/?probe=55c398146b) | Feb 01, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [28f4fb8e15](https://linux-hardware.org/?probe=28f4fb8e15) | Feb 01, 2023 |
| ASUSTek       | H81M-A/BR                   | Desktop     | [7d271a8235](https://linux-hardware.org/?probe=7d271a8235) | Feb 01, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [d35cf58f46](https://linux-hardware.org/?probe=d35cf58f46) | Feb 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | Notebook    | [8bc290ef67](https://linux-hardware.org/?probe=8bc290ef67) | Feb 01, 2023 |
| MSI           | Modern 14 B11MOU            | Notebook    | [542173e9a2](https://linux-hardware.org/?probe=542173e9a2) | Feb 01, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [ab31f6153e](https://linux-hardware.org/?probe=ab31f6153e) | Feb 01, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [22abfb4a79](https://linux-hardware.org/?probe=22abfb4a79) | Feb 01, 2023 |
| Lenovo        | ThinkPad A485 20MVS0U500    | Notebook    | [b398a8e8e6](https://linux-hardware.org/?probe=b398a8e8e6) | Feb 01, 2023 |
| MSI           | MAG Z590 TORPEDO            | Desktop     | [431a6c7a3a](https://linux-hardware.org/?probe=431a6c7a3a) | Feb 01, 2023 |
| MSI           | Z170A PC MATE               | Desktop     | [ff305089b2](https://linux-hardware.org/?probe=ff305089b2) | Feb 01, 2023 |
| ASUSTek       | N552VW                      | Notebook    | [1ebeeec517](https://linux-hardware.org/?probe=1ebeeec517) | Feb 01, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [ffe1cabad7](https://linux-hardware.org/?probe=ffe1cabad7) | Feb 01, 2023 |
| Dell          | Inspiron 7501               | Notebook    | [426493e8a5](https://linux-hardware.org/?probe=426493e8a5) | Feb 01, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [779b723b67](https://linux-hardware.org/?probe=779b723b67) | Feb 01, 2023 |
| HP            | Laptop 14-dq4xxx            | Notebook    | [c102edf6a0](https://linux-hardware.org/?probe=c102edf6a0) | Feb 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [79c11af9ac](https://linux-hardware.org/?probe=79c11af9ac) | Feb 01, 2023 |
| ASUSTek       | ROG STRIX Z490-A GAMING     | Desktop     | [5f2948351d](https://linux-hardware.org/?probe=5f2948351d) | Feb 01, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [4f8642280f](https://linux-hardware.org/?probe=4f8642280f) | Feb 01, 2023 |
| AZW           | U59                         | Desktop     | [9b73123be3](https://linux-hardware.org/?probe=9b73123be3) | Feb 01, 2023 |
| AZW           | U59                         | Desktop     | [74f028454a](https://linux-hardware.org/?probe=74f028454a) | Feb 01, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [6b9dc508e1](https://linux-hardware.org/?probe=6b9dc508e1) | Feb 01, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [99127d4bed](https://linux-hardware.org/?probe=99127d4bed) | Feb 01, 2023 |
| Dell          | Inspiron 5748               | Notebook    | [7ee6505f8d](https://linux-hardware.org/?probe=7ee6505f8d) | Feb 01, 2023 |
| ASUSTek       | Zenbook UX8402ZA_UX8402Z... | Notebook    | [1d212c67b2](https://linux-hardware.org/?probe=1d212c67b2) | Jan 31, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [70310e25d1](https://linux-hardware.org/?probe=70310e25d1) | Jan 31, 2023 |
| HUAWEI        | HN-WX9X                     | Notebook    | [4b8ddf5d09](https://linux-hardware.org/?probe=4b8ddf5d09) | Jan 31, 2023 |
| Dell          | Inspiron 5748               | Notebook    | [ecbd4ac8b6](https://linux-hardware.org/?probe=ecbd4ac8b6) | Jan 31, 2023 |
| Lenovo        | ThinkPad T530 2429F27       | Notebook    | [85ac6a588d](https://linux-hardware.org/?probe=85ac6a588d) | Jan 31, 2023 |
| Gigabyte      | H97M-D3H                    | Desktop     | [3ccdc4fa2b](https://linux-hardware.org/?probe=3ccdc4fa2b) | Jan 31, 2023 |
| ASUSTek       | Zenbook UX8402ZA_UX8402Z... | Notebook    | [4dcc88b215](https://linux-hardware.org/?probe=4dcc88b215) | Jan 31, 2023 |
| TUXEDO        | Stellaris Intel Gen4        | Notebook    | [2df9f60f2e](https://linux-hardware.org/?probe=2df9f60f2e) | Jan 31, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [b1c77eb9c7](https://linux-hardware.org/?probe=b1c77eb9c7) | Jan 31, 2023 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | Notebook    | [a64ae29757](https://linux-hardware.org/?probe=a64ae29757) | Jan 31, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [318b0a5ecb](https://linux-hardware.org/?probe=318b0a5ecb) | Jan 31, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [a06f4e8595](https://linux-hardware.org/?probe=a06f4e8595) | Jan 31, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [73bc9212a3](https://linux-hardware.org/?probe=73bc9212a3) | Jan 31, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [6e7d6aae31](https://linux-hardware.org/?probe=6e7d6aae31) | Jan 31, 2023 |
| ASRock        | AD2700-ITX                  | Desktop     | [2f14c18867](https://linux-hardware.org/?probe=2f14c18867) | Jan 31, 2023 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [75fad3daf3](https://linux-hardware.org/?probe=75fad3daf3) | Jan 31, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [ee60c1c921](https://linux-hardware.org/?probe=ee60c1c921) | Jan 31, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | Notebook    | [87904d9d06](https://linux-hardware.org/?probe=87904d9d06) | Jan 31, 2023 |
| ASRock        | 890GM Pro3                  | Desktop     | [b2bb32cbbc](https://linux-hardware.org/?probe=b2bb32cbbc) | Jan 31, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [67262a8155](https://linux-hardware.org/?probe=67262a8155) | Jan 30, 2023 |
| Dell          | 0Y2K8N A01                  | Desktop     | [6a4a26884d](https://linux-hardware.org/?probe=6a4a26884d) | Jan 30, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [357d14774f](https://linux-hardware.org/?probe=357d14774f) | Jan 30, 2023 |
| Dell          | 0Y2K8N A01                  | Desktop     | [8e4f1d2ed2](https://linux-hardware.org/?probe=8e4f1d2ed2) | Jan 30, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603ZX... | Notebook    | [7442c84b55](https://linux-hardware.org/?probe=7442c84b55) | Jan 30, 2023 |
| Dell          | Latitude 7480               | Notebook    | [f3a84b494f](https://linux-hardware.org/?probe=f3a84b494f) | Jan 30, 2023 |
| Lenovo        | ThinkPad L380 Yoga 20M8S... | Convertible | [782e38cf06](https://linux-hardware.org/?probe=782e38cf06) | Jan 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [1ecef01472](https://linux-hardware.org/?probe=1ecef01472) | Jan 30, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [8d62c84240](https://linux-hardware.org/?probe=8d62c84240) | Jan 30, 2023 |
| HP            | Pavilion 15                 | Notebook    | [6ceccb3d73](https://linux-hardware.org/?probe=6ceccb3d73) | Jan 30, 2023 |
| Lenovo        | ThinkPad T430 2347G4U       | Notebook    | [5802e6b9b9](https://linux-hardware.org/?probe=5802e6b9b9) | Jan 30, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [585c3c8f85](https://linux-hardware.org/?probe=585c3c8f85) | Jan 30, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [24402e3d42](https://linux-hardware.org/?probe=24402e3d42) | Jan 30, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [1d06f2715a](https://linux-hardware.org/?probe=1d06f2715a) | Jan 30, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [9b6a9a4ab5](https://linux-hardware.org/?probe=9b6a9a4ab5) | Jan 30, 2023 |
| ASRock        | N68-S UCC                   | Desktop     | [e8f09a159a](https://linux-hardware.org/?probe=e8f09a159a) | Jan 29, 2023 |
| Dell          | Vostro 7620                 | Notebook    | [b6d43b8741](https://linux-hardware.org/?probe=b6d43b8741) | Jan 29, 2023 |
| ASUSTek       | GA15DH                      | Desktop     | [767fe59cb7](https://linux-hardware.org/?probe=767fe59cb7) | Jan 29, 2023 |
| Lenovo        | Yoga 7 16IAH7 82UF          | Convertible | [2f9de3e332](https://linux-hardware.org/?probe=2f9de3e332) | Jan 29, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [bdb3c91476](https://linux-hardware.org/?probe=bdb3c91476) | Jan 29, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [9b93652159](https://linux-hardware.org/?probe=9b93652159) | Jan 29, 2023 |
| Acer          | Aspire V5-573G              | Notebook    | [e253d5b49b](https://linux-hardware.org/?probe=e253d5b49b) | Jan 29, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [32d5472e21](https://linux-hardware.org/?probe=32d5472e21) | Jan 29, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [dd07a46c6a](https://linux-hardware.org/?probe=dd07a46c6a) | Jan 29, 2023 |
| TECNO         | MEGABOOK T1                 | Notebook    | [db0e6c89b4](https://linux-hardware.org/?probe=db0e6c89b4) | Jan 29, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [104fb04e91](https://linux-hardware.org/?probe=104fb04e91) | Jan 29, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [ef43edeee5](https://linux-hardware.org/?probe=ef43edeee5) | Jan 29, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [f9a823cb38](https://linux-hardware.org/?probe=f9a823cb38) | Jan 29, 2023 |
| Razer         | Blade 15 (2022) - RZ09-0... | Notebook    | [41d33a9029](https://linux-hardware.org/?probe=41d33a9029) | Jan 29, 2023 |
| ASRock        | X570M Pro4                  | Desktop     | [e72f7f2fb1](https://linux-hardware.org/?probe=e72f7f2fb1) | Jan 29, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [086e08a04b](https://linux-hardware.org/?probe=086e08a04b) | Jan 29, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [60c03ee1f7](https://linux-hardware.org/?probe=60c03ee1f7) | Jan 29, 2023 |
| Acer          | FMP55                       | Desktop     | [d091fbc8d3](https://linux-hardware.org/?probe=d091fbc8d3) | Jan 29, 2023 |
| ASUSTek       | ZenBook Q536FD_Q536FD       | Convertible | [0d1e08db32](https://linux-hardware.org/?probe=0d1e08db32) | Jan 28, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [30549ebd3a](https://linux-hardware.org/?probe=30549ebd3a) | Jan 28, 2023 |
| Dell          | Inspiron 7706 2n1           | Convertible | [f8da74bad3](https://linux-hardware.org/?probe=f8da74bad3) | Jan 28, 2023 |
| HP            | Laptop 15-da2xxx            | Notebook    | [8384a02b4b](https://linux-hardware.org/?probe=8384a02b4b) | Jan 28, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [53015adc9d](https://linux-hardware.org/?probe=53015adc9d) | Jan 28, 2023 |
| HP            | ENVY Laptop 17-cg0xxx       | Notebook    | [ed1ce46901](https://linux-hardware.org/?probe=ed1ce46901) | Jan 28, 2023 |
| Lenovo        | ThinkPad 20FQ005TGE         | Convertible | [a8e34a1084](https://linux-hardware.org/?probe=a8e34a1084) | Jan 28, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [844e4e4b2a](https://linux-hardware.org/?probe=844e4e4b2a) | Jan 28, 2023 |
| HP            | ENVY Laptop 17-cg0xxx       | Notebook    | [ab3f84f96b](https://linux-hardware.org/?probe=ab3f84f96b) | Jan 28, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [8a5423443a](https://linux-hardware.org/?probe=8a5423443a) | Jan 28, 2023 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [7e6cf30d81](https://linux-hardware.org/?probe=7e6cf30d81) | Jan 28, 2023 |
| Timi          | A35S                        | Notebook    | [b6611f9b22](https://linux-hardware.org/?probe=b6611f9b22) | Jan 28, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [4a82904f14](https://linux-hardware.org/?probe=4a82904f14) | Jan 28, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [fb7b1bdaf5](https://linux-hardware.org/?probe=fb7b1bdaf5) | Jan 27, 2023 |
| Lenovo        | ThinkPad T450s 20BWS23W0... | Notebook    | [41c82dbadb](https://linux-hardware.org/?probe=41c82dbadb) | Jan 27, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [d9f9d4bc89](https://linux-hardware.org/?probe=d9f9d4bc89) | Jan 27, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [676f900958](https://linux-hardware.org/?probe=676f900958) | Jan 27, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [e619db262a](https://linux-hardware.org/?probe=e619db262a) | Jan 27, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [a69331d2ea](https://linux-hardware.org/?probe=a69331d2ea) | Jan 27, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [c47b08d2a9](https://linux-hardware.org/?probe=c47b08d2a9) | Jan 27, 2023 |
| HONOR         | BMH-WCX9                    | Notebook    | [882bb3b505](https://linux-hardware.org/?probe=882bb3b505) | Jan 27, 2023 |
| MECHREVO      | Code10-7CC6U                | Notebook    | [86e769b2a3](https://linux-hardware.org/?probe=86e769b2a3) | Jan 27, 2023 |
| Dell          | Precision 3550              | Notebook    | [4c42615cef](https://linux-hardware.org/?probe=4c42615cef) | Jan 27, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [00e21c8359](https://linux-hardware.org/?probe=00e21c8359) | Jan 27, 2023 |
| Dynabook      | TECRA A50-J                 | Notebook    | [a2ad3f4eb3](https://linux-hardware.org/?probe=a2ad3f4eb3) | Jan 27, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [c0ea09ef3c](https://linux-hardware.org/?probe=c0ea09ef3c) | Jan 27, 2023 |
| Chuwi         | LarkBox Pro                 | Mini pc     | [3895a32819](https://linux-hardware.org/?probe=3895a32819) | Jan 27, 2023 |
| BYTENUC       | AZ51                        | Mini pc     | [8be36cd9c0](https://linux-hardware.org/?probe=8be36cd9c0) | Jan 27, 2023 |
| Dynabook      | TECRA A50-J                 | Notebook    | [3921b100b4](https://linux-hardware.org/?probe=3921b100b4) | Jan 27, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [1d79d6f224](https://linux-hardware.org/?probe=1d79d6f224) | Jan 26, 2023 |
| ASUSTek       | X550VX                      | Notebook    | [37d2157b37](https://linux-hardware.org/?probe=37d2157b37) | Jan 26, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | Notebook    | [9dfc820ceb](https://linux-hardware.org/?probe=9dfc820ceb) | Jan 26, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | Notebook    | [0168a5cae2](https://linux-hardware.org/?probe=0168a5cae2) | Jan 26, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [4024f7c3bd](https://linux-hardware.org/?probe=4024f7c3bd) | Jan 26, 2023 |
| ASUSTek       | K55VD                       | Notebook    | [b2b19ec3f1](https://linux-hardware.org/?probe=b2b19ec3f1) | Jan 26, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [9c04ff43a3](https://linux-hardware.org/?probe=9c04ff43a3) | Jan 26, 2023 |
| Lenovo        | ThinkPad T495 20NKS01Y00    | Notebook    | [a1dfc58700](https://linux-hardware.org/?probe=a1dfc58700) | Jan 26, 2023 |
| ASRock        | AD2700-ITX                  | Desktop     | [7b711bee4f](https://linux-hardware.org/?probe=7b711bee4f) | Jan 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [303593899d](https://linux-hardware.org/?probe=303593899d) | Jan 26, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [4213c95d3d](https://linux-hardware.org/?probe=4213c95d3d) | Jan 26, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [b44aa465bc](https://linux-hardware.org/?probe=b44aa465bc) | Jan 26, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HM... | Notebook    | [26f64a2ad0](https://linux-hardware.org/?probe=26f64a2ad0) | Jan 26, 2023 |
| Multilaser    | PC150                       | Notebook    | [1c4ace00d1](https://linux-hardware.org/?probe=1c4ace00d1) | Jan 26, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [415b96672b](https://linux-hardware.org/?probe=415b96672b) | Jan 26, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 D... | Notebook    | [d2a46bd14a](https://linux-hardware.org/?probe=d2a46bd14a) | Jan 26, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [f69047309d](https://linux-hardware.org/?probe=f69047309d) | Jan 26, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [8725d530e5](https://linux-hardware.org/?probe=8725d530e5) | Jan 26, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [ea142e4848](https://linux-hardware.org/?probe=ea142e4848) | Jan 25, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [f03240c746](https://linux-hardware.org/?probe=f03240c746) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [af63cfc79a](https://linux-hardware.org/?probe=af63cfc79a) | Jan 25, 2023 |
| Clevo         | M815P                       | Notebook    | [cfc5f6689f](https://linux-hardware.org/?probe=cfc5f6689f) | Jan 25, 2023 |
| ASUSTek       | ROG STRIX H370-I GAMING     | Desktop     | [decfe6ab97](https://linux-hardware.org/?probe=decfe6ab97) | Jan 25, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [4efa4db490](https://linux-hardware.org/?probe=4efa4db490) | Jan 25, 2023 |
| MSI           | GL63 8RC                    | Notebook    | [138e8de541](https://linux-hardware.org/?probe=138e8de541) | Jan 25, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [33292253d0](https://linux-hardware.org/?probe=33292253d0) | Jan 25, 2023 |
| HP            | ZBook Power 15.6 inch G9... | Notebook    | [dd2f21ab84](https://linux-hardware.org/?probe=dd2f21ab84) | Jan 25, 2023 |
| Dynabook      | TECRA A50-J                 | Notebook    | [2f24f18672](https://linux-hardware.org/?probe=2f24f18672) | Jan 25, 2023 |
| Dell          | 0XFWHV A00                  | Desktop     | [52ee3df163](https://linux-hardware.org/?probe=52ee3df163) | Jan 25, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [993ba3e73b](https://linux-hardware.org/?probe=993ba3e73b) | Jan 25, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [82c3a80b93](https://linux-hardware.org/?probe=82c3a80b93) | Jan 25, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [aa6488b6b8](https://linux-hardware.org/?probe=aa6488b6b8) | Jan 25, 2023 |
| Fujitsu Si... | AMILO Notebook Xa 3530      | Notebook    | [e8384494a3](https://linux-hardware.org/?probe=e8384494a3) | Jan 25, 2023 |
| Dell          | Inspiron 5402               | Notebook    | [d8df4aafe8](https://linux-hardware.org/?probe=d8df4aafe8) | Jan 25, 2023 |
| Dell          | Inspiron 5468               | Notebook    | [3e59c1f38b](https://linux-hardware.org/?probe=3e59c1f38b) | Jan 25, 2023 |
| Acer          | Nitro AN515-42              | Notebook    | [cb02367642](https://linux-hardware.org/?probe=cb02367642) | Jan 25, 2023 |
| Dell          | Latitude 5420               | Notebook    | [cd6dc3695e](https://linux-hardware.org/?probe=cd6dc3695e) | Jan 24, 2023 |
| Dell          | Latitude 5520               | Notebook    | [662284824b](https://linux-hardware.org/?probe=662284824b) | Jan 24, 2023 |
| HP            | ProBook 6570b               | Notebook    | [841250ba59](https://linux-hardware.org/?probe=841250ba59) | Jan 24, 2023 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | Desktop     | [8ac6e901d5](https://linux-hardware.org/?probe=8ac6e901d5) | Jan 24, 2023 |
| Dell          | Latitude E6410              | Notebook    | [854634fb32](https://linux-hardware.org/?probe=854634fb32) | Jan 24, 2023 |
| Dell          | Latitude E6410              | Notebook    | [a5edbef8d2](https://linux-hardware.org/?probe=a5edbef8d2) | Jan 24, 2023 |
| Lenovo        | 36E9 SDK0T08861 WIN 3305... | Desktop     | [82705366d7](https://linux-hardware.org/?probe=82705366d7) | Jan 24, 2023 |
| Lenovo        | ThinkPad T500 2082BPG       | Notebook    | [08a30fd24c](https://linux-hardware.org/?probe=08a30fd24c) | Jan 24, 2023 |
| Lenovo        | ThinkPad E15 20RD0011RT     | Notebook    | [3fb25133ec](https://linux-hardware.org/?probe=3fb25133ec) | Jan 24, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [c2226035ce](https://linux-hardware.org/?probe=c2226035ce) | Jan 24, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [43c26544a9](https://linux-hardware.org/?probe=43c26544a9) | Jan 24, 2023 |
| Google        | Treeya                      | Notebook    | [27a381272a](https://linux-hardware.org/?probe=27a381272a) | Jan 24, 2023 |
| Dell          | 0X30MX A00                  | Desktop     | [c323a1a215](https://linux-hardware.org/?probe=c323a1a215) | Jan 24, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [a227de29c5](https://linux-hardware.org/?probe=a227de29c5) | Jan 24, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [1887a95d31](https://linux-hardware.org/?probe=1887a95d31) | Jan 23, 2023 |
| Dell          | Precision 3551              | Notebook    | [1338d3df20](https://linux-hardware.org/?probe=1338d3df20) | Jan 23, 2023 |
| HP            | ProBook 430 G8 Notebook ... | Notebook    | [335275777a](https://linux-hardware.org/?probe=335275777a) | Jan 23, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [7572089dc3](https://linux-hardware.org/?probe=7572089dc3) | Jan 23, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [2f215e1ce7](https://linux-hardware.org/?probe=2f215e1ce7) | Jan 23, 2023 |
| Dell          | Latitude 7490               | Notebook    | [e40bb2f01f](https://linux-hardware.org/?probe=e40bb2f01f) | Jan 23, 2023 |
| Dell          | Latitude 7490               | Notebook    | [31789ae630](https://linux-hardware.org/?probe=31789ae630) | Jan 23, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [091effd2ac](https://linux-hardware.org/?probe=091effd2ac) | Jan 23, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [0a597ba033](https://linux-hardware.org/?probe=0a597ba033) | Jan 23, 2023 |
| Lenovo        | Erazer Z500 20226           | Notebook    | [6e7a21c6d5](https://linux-hardware.org/?probe=6e7a21c6d5) | Jan 23, 2023 |
| Lenovo        | Erazer Z500 20226           | Notebook    | [7d6077c27c](https://linux-hardware.org/?probe=7d6077c27c) | Jan 23, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [90884b19a9](https://linux-hardware.org/?probe=90884b19a9) | Jan 23, 2023 |
| Lenovo        | ThinkPad P50 20EQS12Q3M     | Notebook    | [e46b5a8b46](https://linux-hardware.org/?probe=e46b5a8b46) | Jan 23, 2023 |
| Dell          | Latitude E6500              | Notebook    | [ba7c36fe15](https://linux-hardware.org/?probe=ba7c36fe15) | Jan 23, 2023 |
| Lenovo        | ThinkPad L13 Yoga 20R500... | Convertible | [7f5181d202](https://linux-hardware.org/?probe=7f5181d202) | Jan 23, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [aa16eaced0](https://linux-hardware.org/?probe=aa16eaced0) | Jan 23, 2023 |
| Dynabook      | TECRA A50-J                 | Notebook    | [689fe06d4d](https://linux-hardware.org/?probe=689fe06d4d) | Jan 23, 2023 |
| Dynabook      | TECRA A50-J                 | Notebook    | [92690b43cd](https://linux-hardware.org/?probe=92690b43cd) | Jan 23, 2023 |
| Dell          | Inspiron 7786               | Convertible | [4a96e070dd](https://linux-hardware.org/?probe=4a96e070dd) | Jan 23, 2023 |
| Microsoft     | Surface 3                   | Tablet      | [00f594a9cf](https://linux-hardware.org/?probe=00f594a9cf) | Jan 23, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [279452d293](https://linux-hardware.org/?probe=279452d293) | Jan 23, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [3a42df71d0](https://linux-hardware.org/?probe=3a42df71d0) | Jan 22, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [d03b7c0a68](https://linux-hardware.org/?probe=d03b7c0a68) | Jan 22, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [07005e3e32](https://linux-hardware.org/?probe=07005e3e32) | Jan 22, 2023 |
| Dell          | 0Y56T3 A00                  | Desktop     | [7078ea91e9](https://linux-hardware.org/?probe=7078ea91e9) | Jan 22, 2023 |
| MSI           | H510M PRO                   | Desktop     | [309f1bc61b](https://linux-hardware.org/?probe=309f1bc61b) | Jan 22, 2023 |
| ECS           | H61H2-MV                    | Desktop     | [92d2b62680](https://linux-hardware.org/?probe=92d2b62680) | Jan 22, 2023 |
| MSI           | B450-A PRO                  | Desktop     | [e9c7c42a8b](https://linux-hardware.org/?probe=e9c7c42a8b) | Jan 22, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [9792de46ad](https://linux-hardware.org/?probe=9792de46ad) | Jan 22, 2023 |
| ECS           | H61H2-MV                    | Desktop     | [292ff62f4c](https://linux-hardware.org/?probe=292ff62f4c) | Jan 22, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [8e037468e4](https://linux-hardware.org/?probe=8e037468e4) | Jan 22, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [b3d64d2496](https://linux-hardware.org/?probe=b3d64d2496) | Jan 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | Notebook    | [d999192dbf](https://linux-hardware.org/?probe=d999192dbf) | Jan 22, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [3edd4ab0dc](https://linux-hardware.org/?probe=3edd4ab0dc) | Jan 22, 2023 |
| ASUSTek       | H61M-A/BR                   | Desktop     | [43aaf27a04](https://linux-hardware.org/?probe=43aaf27a04) | Jan 22, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [523d0331a1](https://linux-hardware.org/?probe=523d0331a1) | Jan 21, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [6856fa4741](https://linux-hardware.org/?probe=6856fa4741) | Jan 21, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [0aa98390a7](https://linux-hardware.org/?probe=0aa98390a7) | Jan 21, 2023 |
| AZW           | GTR V02                     | Desktop     | [3616feeeac](https://linux-hardware.org/?probe=3616feeeac) | Jan 21, 2023 |
| Acer          | Predator G9-591             | Notebook    | [0544a1b07c](https://linux-hardware.org/?probe=0544a1b07c) | Jan 21, 2023 |
| Dell          | XPS 9315                    | Notebook    | [9dfb19b7c1](https://linux-hardware.org/?probe=9dfb19b7c1) | Jan 21, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [e8a0c0066b](https://linux-hardware.org/?probe=e8a0c0066b) | Jan 21, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [adeb24c41e](https://linux-hardware.org/?probe=adeb24c41e) | Jan 21, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [7a067fe264](https://linux-hardware.org/?probe=7a067fe264) | Jan 21, 2023 |
| Lenovo        | ThinkPad X13 Yoga Gen 2 ... | Convertible | [32faa4aac5](https://linux-hardware.org/?probe=32faa4aac5) | Jan 21, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [3eb2d3a903](https://linux-hardware.org/?probe=3eb2d3a903) | Jan 21, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [20c0f69bb7](https://linux-hardware.org/?probe=20c0f69bb7) | Jan 21, 2023 |
| Dell          | G5 5587                     | Notebook    | [96ca22c550](https://linux-hardware.org/?probe=96ca22c550) | Jan 21, 2023 |
| Dell          | G5 5587                     | Notebook    | [a070a8ba69](https://linux-hardware.org/?probe=a070a8ba69) | Jan 21, 2023 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [c228c064b7](https://linux-hardware.org/?probe=c228c064b7) | Jan 20, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [04d36be1ec](https://linux-hardware.org/?probe=04d36be1ec) | Jan 20, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [3432d7c1f5](https://linux-hardware.org/?probe=3432d7c1f5) | Jan 20, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [2f6bd134ae](https://linux-hardware.org/?probe=2f6bd134ae) | Jan 20, 2023 |
| Digma         | CITI 1804 CS1069EW          | Tablet      | [0443e57eca](https://linux-hardware.org/?probe=0443e57eca) | Jan 20, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [5bbd614c0f](https://linux-hardware.org/?probe=5bbd614c0f) | Jan 20, 2023 |
| Dell          | Venue 8 Pro 5830            | Notebook    | [4f815d5b4f](https://linux-hardware.org/?probe=4f815d5b4f) | Jan 20, 2023 |
| Acer          | Aspire A315-42G             | Notebook    | [ed4c536efa](https://linux-hardware.org/?probe=ed4c536efa) | Jan 20, 2023 |
| HP            | 0AECh D                     | Desktop     | [b2ea95f507](https://linux-hardware.org/?probe=b2ea95f507) | Jan 20, 2023 |
| Lenovo        | ThinkPad T490 20N3S0E000    | Notebook    | [d324a863a5](https://linux-hardware.org/?probe=d324a863a5) | Jan 20, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [5f1447f874](https://linux-hardware.org/?probe=5f1447f874) | Jan 20, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [9d5faff505](https://linux-hardware.org/?probe=9d5faff505) | Jan 20, 2023 |
| MSI           | GS66 Stealth 10UE           | Notebook    | [d5a2a6aaa8](https://linux-hardware.org/?probe=d5a2a6aaa8) | Jan 19, 2023 |
| SLIMBOOK      | TITAN                       | Notebook    | [15c0522754](https://linux-hardware.org/?probe=15c0522754) | Jan 19, 2023 |
| SLIMBOOK      | TITAN                       | Notebook    | [e81652a68c](https://linux-hardware.org/?probe=e81652a68c) | Jan 19, 2023 |
| Dell          | Precision 3551              | Notebook    | [4ff5a0ab8d](https://linux-hardware.org/?probe=4ff5a0ab8d) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [0f079e1dc7](https://linux-hardware.org/?probe=0f079e1dc7) | Jan 19, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [90049e4bb7](https://linux-hardware.org/?probe=90049e4bb7) | Jan 19, 2023 |
| Acer          | Nitro AN515-42              | Notebook    | [d6a24ede85](https://linux-hardware.org/?probe=d6a24ede85) | Jan 19, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [6a47296f0c](https://linux-hardware.org/?probe=6a47296f0c) | Jan 19, 2023 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [33b364ed89](https://linux-hardware.org/?probe=33b364ed89) | Jan 19, 2023 |
| Samsung       | DP300A2A-B01RU SEC_SW_RE... | All in one  | [18d76fe11f](https://linux-hardware.org/?probe=18d76fe11f) | Jan 19, 2023 |
| Dell          | Latitude 3410               | Notebook    | [187aebc2cd](https://linux-hardware.org/?probe=187aebc2cd) | Jan 19, 2023 |
| Intel Clie... | LAPRC510                    | Notebook    | [6d570a1aee](https://linux-hardware.org/?probe=6d570a1aee) | Jan 19, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [8303a9c2a0](https://linux-hardware.org/?probe=8303a9c2a0) | Jan 18, 2023 |
| ASUSTek       | X455LF                      | Notebook    | [9995b86c04](https://linux-hardware.org/?probe=9995b86c04) | Jan 18, 2023 |
| Dell          | 0XFRWW A00                  | Desktop     | [2b96d4b6f6](https://linux-hardware.org/?probe=2b96d4b6f6) | Jan 18, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [011b9a41cd](https://linux-hardware.org/?probe=011b9a41cd) | Jan 18, 2023 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [ff6ad7bf11](https://linux-hardware.org/?probe=ff6ad7bf11) | Jan 18, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [533d99e2f1](https://linux-hardware.org/?probe=533d99e2f1) | Jan 18, 2023 |
| Lenovo        | ThinkPad E15 20RD0011RT     | Notebook    | [d27ca45841](https://linux-hardware.org/?probe=d27ca45841) | Jan 18, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [ec05dd5768](https://linux-hardware.org/?probe=ec05dd5768) | Jan 18, 2023 |
| Dell          | 0KRC95 A02                  | Desktop     | [01cf6039d0](https://linux-hardware.org/?probe=01cf6039d0) | Jan 18, 2023 |
| ASRock        | B550 Extreme4               | Desktop     | [e5599ac616](https://linux-hardware.org/?probe=e5599ac616) | Jan 18, 2023 |
| Dell          | Precision 3561              | Notebook    | [9528d74be6](https://linux-hardware.org/?probe=9528d74be6) | Jan 18, 2023 |
| Dell          | Precision 3561              | Notebook    | [5f23addbde](https://linux-hardware.org/?probe=5f23addbde) | Jan 18, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [1b916fe30d](https://linux-hardware.org/?probe=1b916fe30d) | Jan 18, 2023 |
| ASRock        | Z170 Gaming K4              | Desktop     | [44a3d49ef1](https://linux-hardware.org/?probe=44a3d49ef1) | Jan 18, 2023 |
| Lenovo        | Yoga 500-14IHW 80N5         | Notebook    | [e233e8d6d2](https://linux-hardware.org/?probe=e233e8d6d2) | Jan 18, 2023 |
| ASUSTek       | ASUS BR1100FKA BR1100FKA... | Convertible | [4fba90df07](https://linux-hardware.org/?probe=4fba90df07) | Jan 17, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [4a997fa99d](https://linux-hardware.org/?probe=4a997fa99d) | Jan 17, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [a81a940d33](https://linux-hardware.org/?probe=a81a940d33) | Jan 17, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [f050195c33](https://linux-hardware.org/?probe=f050195c33) | Jan 17, 2023 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [a8fbe01fc5](https://linux-hardware.org/?probe=a8fbe01fc5) | Jan 17, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [8e21ef4b91](https://linux-hardware.org/?probe=8e21ef4b91) | Jan 17, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [469c40ec75](https://linux-hardware.org/?probe=469c40ec75) | Jan 17, 2023 |
| Gigabyte      | 990FXA-UD5 R5               | Desktop     | [8753bd8277](https://linux-hardware.org/?probe=8753bd8277) | Jan 17, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [b45cef8a55](https://linux-hardware.org/?probe=b45cef8a55) | Jan 17, 2023 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [3dbc34a913](https://linux-hardware.org/?probe=3dbc34a913) | Jan 17, 2023 |
| Timi          | Xiaomi NoteBook Pro         | Notebook    | [681de2b0c1](https://linux-hardware.org/?probe=681de2b0c1) | Jan 17, 2023 |
| Dynabook      | PORTEGE X30W-K              | Convertible | [5c3d7c049e](https://linux-hardware.org/?probe=5c3d7c049e) | Jan 17, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [16be0552b2](https://linux-hardware.org/?probe=16be0552b2) | Jan 17, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [16c9b323c6](https://linux-hardware.org/?probe=16c9b323c6) | Jan 17, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [7b36d7e8eb](https://linux-hardware.org/?probe=7b36d7e8eb) | Jan 17, 2023 |
| Timi          | Xiaomi NoteBook Pro         | Notebook    | [f1ee502754](https://linux-hardware.org/?probe=f1ee502754) | Jan 17, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [0d91852ebf](https://linux-hardware.org/?probe=0d91852ebf) | Jan 17, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [aeb9ac591c](https://linux-hardware.org/?probe=aeb9ac591c) | Jan 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [c16356f056](https://linux-hardware.org/?probe=c16356f056) | Jan 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [70b8007dcc](https://linux-hardware.org/?probe=70b8007dcc) | Jan 17, 2023 |
| Acer          | Aspire AV14-51              | Notebook    | [596219796d](https://linux-hardware.org/?probe=596219796d) | Jan 17, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [93380bb1f5](https://linux-hardware.org/?probe=93380bb1f5) | Jan 17, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [b39c4fc9b7](https://linux-hardware.org/?probe=b39c4fc9b7) | Jan 16, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | Notebook    | [1c81e8c322](https://linux-hardware.org/?probe=1c81e8c322) | Jan 16, 2023 |
| Dell          | Inspiron 11 - 3147          | Notebook    | [af542a44ad](https://linux-hardware.org/?probe=af542a44ad) | Jan 16, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [d0a00b398c](https://linux-hardware.org/?probe=d0a00b398c) | Jan 16, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [d5843b83af](https://linux-hardware.org/?probe=d5843b83af) | Jan 16, 2023 |
| PC Special... | Recoil II RTX               | Notebook    | [33850c8810](https://linux-hardware.org/?probe=33850c8810) | Jan 16, 2023 |
| Apple         | Mac-F2238AC8                | All in one  | [c06c7eedaf](https://linux-hardware.org/?probe=c06c7eedaf) | Jan 16, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [b53dd87f87](https://linux-hardware.org/?probe=b53dd87f87) | Jan 16, 2023 |
| Schenker      | XMG CORE 15 (M22)           | Notebook    | [6c2b631f12](https://linux-hardware.org/?probe=6c2b631f12) | Jan 16, 2023 |
| Lenovo        | 32E9 SDK0T76461 WIN 3422... | Desktop     | [5480333c5b](https://linux-hardware.org/?probe=5480333c5b) | Jan 16, 2023 |
| Gigabyte      | 990FXA-UD5 R5               | Desktop     | [dd16b56d30](https://linux-hardware.org/?probe=dd16b56d30) | Jan 16, 2023 |
| HP            | 15                          | Notebook    | [ae082994e2](https://linux-hardware.org/?probe=ae082994e2) | Jan 16, 2023 |
| Acer          | Nitro AN515-46              | Notebook    | [1de96d005a](https://linux-hardware.org/?probe=1de96d005a) | Jan 16, 2023 |
| Microsoft     | Surface Go 3                | Tablet      | [3390ce67a2](https://linux-hardware.org/?probe=3390ce67a2) | Jan 16, 2023 |
| Acer          | Nitro AN515-46              | Notebook    | [f0eab1c81a](https://linux-hardware.org/?probe=f0eab1c81a) | Jan 16, 2023 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [e1aa5d3186](https://linux-hardware.org/?probe=e1aa5d3186) | Jan 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [1a51848ffb](https://linux-hardware.org/?probe=1a51848ffb) | Jan 16, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [d24e1142ef](https://linux-hardware.org/?probe=d24e1142ef) | Jan 16, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [b36eb94e80](https://linux-hardware.org/?probe=b36eb94e80) | Jan 16, 2023 |
| Dell          | 0M863N A01                  | Desktop     | [1dff7cb016](https://linux-hardware.org/?probe=1dff7cb016) | Jan 16, 2023 |
| HP            | 255 G6 Notebook PC          | Notebook    | [4d2e9f3ee4](https://linux-hardware.org/?probe=4d2e9f3ee4) | Jan 16, 2023 |
| Lenovo        | ThinkPad T440s 20AQ0069G... | Notebook    | [cb2e9f2623](https://linux-hardware.org/?probe=cb2e9f2623) | Jan 16, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [a38eb750aa](https://linux-hardware.org/?probe=a38eb750aa) | Jan 16, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [9ac2f0ab83](https://linux-hardware.org/?probe=9ac2f0ab83) | Jan 15, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [b68ce1375d](https://linux-hardware.org/?probe=b68ce1375d) | Jan 15, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [4850c49a4a](https://linux-hardware.org/?probe=4850c49a4a) | Jan 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [448ae92dc8](https://linux-hardware.org/?probe=448ae92dc8) | Jan 15, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [978682daa6](https://linux-hardware.org/?probe=978682daa6) | Jan 15, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [972e3e026a](https://linux-hardware.org/?probe=972e3e026a) | Jan 15, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [57d99b139f](https://linux-hardware.org/?probe=57d99b139f) | Jan 15, 2023 |
| Acer          | Aspire A515-43              | Notebook    | [cefbe7ee6e](https://linux-hardware.org/?probe=cefbe7ee6e) | Jan 15, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [fcc6481e2a](https://linux-hardware.org/?probe=fcc6481e2a) | Jan 15, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [a15e06403a](https://linux-hardware.org/?probe=a15e06403a) | Jan 15, 2023 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [983230429d](https://linux-hardware.org/?probe=983230429d) | Jan 15, 2023 |
| HP            | Pavilion Laptop 14-bk0xx    | Notebook    | [ebe90b5052](https://linux-hardware.org/?probe=ebe90b5052) | Jan 15, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [20625ce99d](https://linux-hardware.org/?probe=20625ce99d) | Jan 14, 2023 |
| Olivetti      | Olibook P55-431W850-8G50... | Notebook    | [fe5c9c2425](https://linux-hardware.org/?probe=fe5c9c2425) | Jan 14, 2023 |
| AZW           | GTR V02                     | Desktop     | [074c3ab42f](https://linux-hardware.org/?probe=074c3ab42f) | Jan 14, 2023 |
| Olivetti      | Olibook P55-431W850-8G50... | Notebook    | [649546bc61](https://linux-hardware.org/?probe=649546bc61) | Jan 14, 2023 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [4ef76b2644](https://linux-hardware.org/?probe=4ef76b2644) | Jan 14, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [86fff559f5](https://linux-hardware.org/?probe=86fff559f5) | Jan 14, 2023 |
| HP            | Pavilion Laptop 14-bk0xx    | Notebook    | [bcbf941284](https://linux-hardware.org/?probe=bcbf941284) | Jan 14, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [efffe2d61b](https://linux-hardware.org/?probe=efffe2d61b) | Jan 14, 2023 |
| MSI           | PS63 Modern 8RC             | Notebook    | [e55e0d9d0a](https://linux-hardware.org/?probe=e55e0d9d0a) | Jan 14, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [3325b8ab60](https://linux-hardware.org/?probe=3325b8ab60) | Jan 14, 2023 |
| Dell          | 0W2F8G A01                  | Desktop     | [999fcca032](https://linux-hardware.org/?probe=999fcca032) | Jan 14, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [03f0709b21](https://linux-hardware.org/?probe=03f0709b21) | Jan 14, 2023 |
| System76      | Oryx Pro                    | Notebook    | [f706b667bb](https://linux-hardware.org/?probe=f706b667bb) | Jan 14, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [5047da7461](https://linux-hardware.org/?probe=5047da7461) | Jan 14, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [e292f699eb](https://linux-hardware.org/?probe=e292f699eb) | Jan 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [9096450d56](https://linux-hardware.org/?probe=9096450d56) | Jan 14, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | Notebook    | [bbf1dabe59](https://linux-hardware.org/?probe=bbf1dabe59) | Jan 14, 2023 |
| Lenovo        | 3144 SDK0J40697 WIN 3305... | Mini pc     | [6ae0a203a7](https://linux-hardware.org/?probe=6ae0a203a7) | Jan 13, 2023 |
| Lenovo        | 3144 SDK0J40697 WIN 3305... | Mini pc     | [76ce1a38ba](https://linux-hardware.org/?probe=76ce1a38ba) | Jan 13, 2023 |
| Lenovo        | 3144 SDK0J40697 WIN 3305... | Mini pc     | [0d01d0023b](https://linux-hardware.org/?probe=0d01d0023b) | Jan 13, 2023 |
| Dell          | Latitude 7430               | Notebook    | [9caa5939ef](https://linux-hardware.org/?probe=9caa5939ef) | Jan 13, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [61c432b134](https://linux-hardware.org/?probe=61c432b134) | Jan 13, 2023 |
| ASUSTek       | STRIX B250F GAMING          | Desktop     | [40acaf3525](https://linux-hardware.org/?probe=40acaf3525) | Jan 13, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [c1e0fd9216](https://linux-hardware.org/?probe=c1e0fd9216) | Jan 13, 2023 |
| Supermicro    | X10DRi-LN4+                 | Server      | [f00173e1e2](https://linux-hardware.org/?probe=f00173e1e2) | Jan 13, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [b2c96e31d9](https://linux-hardware.org/?probe=b2c96e31d9) | Jan 13, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [810b2daeef](https://linux-hardware.org/?probe=810b2daeef) | Jan 13, 2023 |
| ASUSTek       | Z87-K                       | Desktop     | [61b7459a43](https://linux-hardware.org/?probe=61b7459a43) | Jan 13, 2023 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [f954b55a5c](https://linux-hardware.org/?probe=f954b55a5c) | Jan 13, 2023 |
| Toshiba       | Satellite L855D             | Notebook    | [0606d04520](https://linux-hardware.org/?probe=0606d04520) | Jan 13, 2023 |
| Dell          | Inspiron 5721               | Notebook    | [b9435f9f7d](https://linux-hardware.org/?probe=b9435f9f7d) | Jan 13, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [c6a710b940](https://linux-hardware.org/?probe=c6a710b940) | Jan 13, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [d4b0530f79](https://linux-hardware.org/?probe=d4b0530f79) | Jan 13, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [64c403ce6d](https://linux-hardware.org/?probe=64c403ce6d) | Jan 13, 2023 |
| Lenovo        | ThinkPad T495s 20QKS2R40... | Notebook    | [28d821da5f](https://linux-hardware.org/?probe=28d821da5f) | Jan 13, 2023 |
| ASUSTek       | H170 PRO GAMING             | Desktop     | [4cf36f7404](https://linux-hardware.org/?probe=4cf36f7404) | Jan 13, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [f9d244586a](https://linux-hardware.org/?probe=f9d244586a) | Jan 13, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [05899ebb86](https://linux-hardware.org/?probe=05899ebb86) | Jan 13, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [033a92981f](https://linux-hardware.org/?probe=033a92981f) | Jan 13, 2023 |
| HP            | 3047h                       | Desktop     | [5eb46c9039](https://linux-hardware.org/?probe=5eb46c9039) | Jan 12, 2023 |
| Acer          | Predator PT515-51           | Notebook    | [150f12dceb](https://linux-hardware.org/?probe=150f12dceb) | Jan 12, 2023 |
| Dell          | G15 5520                    | Notebook    | [1aeaf74f9a](https://linux-hardware.org/?probe=1aeaf74f9a) | Jan 12, 2023 |
| HP            | 3047h                       | Desktop     | [0c035c1a04](https://linux-hardware.org/?probe=0c035c1a04) | Jan 12, 2023 |
| HP            | ProBook 450 G6              | Notebook    | [f675188c46](https://linux-hardware.org/?probe=f675188c46) | Jan 12, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [f38e5f2a4e](https://linux-hardware.org/?probe=f38e5f2a4e) | Jan 12, 2023 |
| ASRock        | X570 Steel Legend           | Desktop     | [600094ae29](https://linux-hardware.org/?probe=600094ae29) | Jan 12, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [ffd5ad6744](https://linux-hardware.org/?probe=ffd5ad6744) | Jan 12, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | Notebook    | [e9783891d1](https://linux-hardware.org/?probe=e9783891d1) | Jan 12, 2023 |
| Acer          | Nitro AN517-42              | Notebook    | [c8440739f9](https://linux-hardware.org/?probe=c8440739f9) | Jan 12, 2023 |
| Samsung       | 950QED                      | Convertible | [0afc7e983a](https://linux-hardware.org/?probe=0afc7e983a) | Jan 12, 2023 |
| Dell          | Latitude E5550              | Notebook    | [0b14eb18d9](https://linux-hardware.org/?probe=0b14eb18d9) | Jan 12, 2023 |
| Samsung       | 950QED                      | Convertible | [9fe5e28749](https://linux-hardware.org/?probe=9fe5e28749) | Jan 12, 2023 |
| Lenovo        | ThinkPad T430 2349W1C       | Notebook    | [1f310a8a2e](https://linux-hardware.org/?probe=1f310a8a2e) | Jan 12, 2023 |
| Unknown       | X79                         | Desktop     | [62bf02da9d](https://linux-hardware.org/?probe=62bf02da9d) | Jan 12, 2023 |
| Unknown       | X79                         | Desktop     | [aed457b56c](https://linux-hardware.org/?probe=aed457b56c) | Jan 12, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [28d13d17ba](https://linux-hardware.org/?probe=28d13d17ba) | Jan 12, 2023 |
| Pegatron      | 2AC3                        | Desktop     | [3cfb7d9e7c](https://linux-hardware.org/?probe=3cfb7d9e7c) | Jan 12, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | Notebook    | [fad743f278](https://linux-hardware.org/?probe=fad743f278) | Jan 12, 2023 |
| ASUSTek       | GA15DH                      | Desktop     | [e480a3bfa3](https://linux-hardware.org/?probe=e480a3bfa3) | Jan 11, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [1270cfda4e](https://linux-hardware.org/?probe=1270cfda4e) | Jan 11, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [8c1eb7fc02](https://linux-hardware.org/?probe=8c1eb7fc02) | Jan 11, 2023 |
| Dell          | Latitude E5550              | Notebook    | [5e76d378f9](https://linux-hardware.org/?probe=5e76d378f9) | Jan 11, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [f84f79fce7](https://linux-hardware.org/?probe=f84f79fce7) | Jan 11, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [ec0f3564ed](https://linux-hardware.org/?probe=ec0f3564ed) | Jan 11, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [a436e3e89f](https://linux-hardware.org/?probe=a436e3e89f) | Jan 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [c79ad1fc10](https://linux-hardware.org/?probe=c79ad1fc10) | Jan 11, 2023 |
| Acer          | Predator G9-591             | Notebook    | [aa9794813e](https://linux-hardware.org/?probe=aa9794813e) | Jan 11, 2023 |
| Dell          | Latitude E7440              | Notebook    | [bfdc9dfc63](https://linux-hardware.org/?probe=bfdc9dfc63) | Jan 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [25090a9dcb](https://linux-hardware.org/?probe=25090a9dcb) | Jan 11, 2023 |
| MSI           | Modern 14 B4MW              | Notebook    | [815ee96451](https://linux-hardware.org/?probe=815ee96451) | Jan 11, 2023 |
| HP            | Pavilion Laptop 13-bb0xx... | Notebook    | [790736a10e](https://linux-hardware.org/?probe=790736a10e) | Jan 11, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [fdb726b276](https://linux-hardware.org/?probe=fdb726b276) | Jan 11, 2023 |
| ASRock        | Z87 Extreme6                | Desktop     | [49e3d87de4](https://linux-hardware.org/?probe=49e3d87de4) | Jan 11, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [18e82e414a](https://linux-hardware.org/?probe=18e82e414a) | Jan 11, 2023 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [a4ab96067d](https://linux-hardware.org/?probe=a4ab96067d) | Jan 10, 2023 |
| Infinix       | INBOOK X2                   | Notebook    | [11aac46bdc](https://linux-hardware.org/?probe=11aac46bdc) | Jan 10, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [dc3e0fffe7](https://linux-hardware.org/?probe=dc3e0fffe7) | Jan 10, 2023 |
| Intel         | NUC8BEB J72688-307          | Mini pc     | [3e54ca06f5](https://linux-hardware.org/?probe=3e54ca06f5) | Jan 10, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [53d6bec0e8](https://linux-hardware.org/?probe=53d6bec0e8) | Jan 10, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | Desktop     | [760cc2eaed](https://linux-hardware.org/?probe=760cc2eaed) | Jan 10, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [62ddf88d2d](https://linux-hardware.org/?probe=62ddf88d2d) | Jan 10, 2023 |
| Lenovo        | YG530-14ARR 81H9            | Convertible | [4af08e8513](https://linux-hardware.org/?probe=4af08e8513) | Jan 10, 2023 |
| Lenovo        | ThinkPad T590 20N5S4R800    | Notebook    | [51d6d75e64](https://linux-hardware.org/?probe=51d6d75e64) | Jan 10, 2023 |
| ASUSTek       | FX503VD                     | Notebook    | [c3a958527e](https://linux-hardware.org/?probe=c3a958527e) | Jan 10, 2023 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | Desktop     | [0a5f45ca97](https://linux-hardware.org/?probe=0a5f45ca97) | Jan 10, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [37b5b1648e](https://linux-hardware.org/?probe=37b5b1648e) | Jan 10, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [b65fef1f25](https://linux-hardware.org/?probe=b65fef1f25) | Jan 10, 2023 |
| Lenovo        | ThinkPad P53 20QNS00X00     | Notebook    | [e16ef8937b](https://linux-hardware.org/?probe=e16ef8937b) | Jan 09, 2023 |
| Alienware     | m15 Ryzen Ed. R5            | Notebook    | [ef83299ad4](https://linux-hardware.org/?probe=ef83299ad4) | Jan 09, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [7c7c8175c0](https://linux-hardware.org/?probe=7c7c8175c0) | Jan 09, 2023 |
| Chuwi         | GemiBook                    | Notebook    | [918dc5f283](https://linux-hardware.org/?probe=918dc5f283) | Jan 09, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [95cfb68187](https://linux-hardware.org/?probe=95cfb68187) | Jan 09, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [ad39556257](https://linux-hardware.org/?probe=ad39556257) | Jan 09, 2023 |
| HP            | EliteBook 850 G4            | Notebook    | [e6cb9446f5](https://linux-hardware.org/?probe=e6cb9446f5) | Jan 09, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [8ec4c19bf3](https://linux-hardware.org/?probe=8ec4c19bf3) | Jan 09, 2023 |
| HP            | Laptop 15-da1xxx            | Notebook    | [2fa89881b4](https://linux-hardware.org/?probe=2fa89881b4) | Jan 09, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [2e13f150e6](https://linux-hardware.org/?probe=2e13f150e6) | Jan 09, 2023 |
| AZW           | GTR V02                     | Desktop     | [b7a911ab61](https://linux-hardware.org/?probe=b7a911ab61) | Jan 09, 2023 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [d30caadc06](https://linux-hardware.org/?probe=d30caadc06) | Jan 09, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [0b2f591376](https://linux-hardware.org/?probe=0b2f591376) | Jan 09, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [6e756926b8](https://linux-hardware.org/?probe=6e756926b8) | Jan 09, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [d7820d12e5](https://linux-hardware.org/?probe=d7820d12e5) | Jan 09, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [92a4be502c](https://linux-hardware.org/?probe=92a4be502c) | Jan 09, 2023 |
| Acer          | Iconia W700                 | Notebook    | [bcfec36896](https://linux-hardware.org/?probe=bcfec36896) | Jan 09, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [6fd945d3cd](https://linux-hardware.org/?probe=6fd945d3cd) | Jan 09, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HM... | Notebook    | [8be13470fb](https://linux-hardware.org/?probe=8be13470fb) | Jan 09, 2023 |
| Lenovo        | IdeaPad 720-15IKB 81AG      | Notebook    | [8c76c72880](https://linux-hardware.org/?probe=8c76c72880) | Jan 08, 2023 |
| HP            | ProBook 6465b               | Notebook    | [336f10e70b](https://linux-hardware.org/?probe=336f10e70b) | Jan 08, 2023 |
| MSI           | MEG X570 ACE                | Desktop     | [853f3c06ce](https://linux-hardware.org/?probe=853f3c06ce) | Jan 08, 2023 |
| ASUSTek       | X541UVK                     | Notebook    | [50e9caee7f](https://linux-hardware.org/?probe=50e9caee7f) | Jan 08, 2023 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [1ca4c751d8](https://linux-hardware.org/?probe=1ca4c751d8) | Jan 08, 2023 |
| Framework     | Laptop                      | Notebook    | [0c13e3ab8d](https://linux-hardware.org/?probe=0c13e3ab8d) | Jan 08, 2023 |
| Acer          | Aspire A315-41              | Notebook    | [b4ed141fd3](https://linux-hardware.org/?probe=b4ed141fd3) | Jan 08, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CR... | Notebook    | [ff783dac11](https://linux-hardware.org/?probe=ff783dac11) | Jan 08, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D4C... | Notebook    | [d2e10cee5b](https://linux-hardware.org/?probe=d2e10cee5b) | Jan 08, 2023 |
| Dell          | Latitude 3450               | Notebook    | [e4e8bee1cb](https://linux-hardware.org/?probe=e4e8bee1cb) | Jan 08, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [d3e35671cd](https://linux-hardware.org/?probe=d3e35671cd) | Jan 08, 2023 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | Desktop     | [afd852d260](https://linux-hardware.org/?probe=afd852d260) | Jan 08, 2023 |
| HP            | EliteBook 745 G5            | Notebook    | [b732d98167](https://linux-hardware.org/?probe=b732d98167) | Jan 08, 2023 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | Desktop     | [5f3e927024](https://linux-hardware.org/?probe=5f3e927024) | Jan 08, 2023 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [e85dcf8a22](https://linux-hardware.org/?probe=e85dcf8a22) | Jan 08, 2023 |
| Acer          | Aspire A715-42G             | Notebook    | [206359e4ad](https://linux-hardware.org/?probe=206359e4ad) | Jan 08, 2023 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [922b7a2305](https://linux-hardware.org/?probe=922b7a2305) | Jan 08, 2023 |
| ASUSTek       | ROG Strix G512LI_G512LI     | Notebook    | [f75fea559f](https://linux-hardware.org/?probe=f75fea559f) | Jan 08, 2023 |
| Acer          | Aspire A715-42G             | Notebook    | [eed9db8255](https://linux-hardware.org/?probe=eed9db8255) | Jan 08, 2023 |
| Lenovo        | ThinkPad P53 20QNS00X00     | Notebook    | [6290949f56](https://linux-hardware.org/?probe=6290949f56) | Jan 08, 2023 |
| Dell          | Vostro 15-3568              | Notebook    | [a6c731c83b](https://linux-hardware.org/?probe=a6c731c83b) | Jan 08, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [b0a36f054e](https://linux-hardware.org/?probe=b0a36f054e) | Jan 08, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [a43647cad6](https://linux-hardware.org/?probe=a43647cad6) | Jan 08, 2023 |
| Acer          | Predator PT515-51           | Notebook    | [a33d9c5a74](https://linux-hardware.org/?probe=a33d9c5a74) | Jan 07, 2023 |
| Dell          | Latitude 9430               | Convertible | [d04e9626cf](https://linux-hardware.org/?probe=d04e9626cf) | Jan 07, 2023 |
| HP            | EliteBook 850 G6            | Notebook    | [595e6fa89a](https://linux-hardware.org/?probe=595e6fa89a) | Jan 07, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [f0a688060c](https://linux-hardware.org/?probe=f0a688060c) | Jan 07, 2023 |
| Lenovo        | ThinkPad T530 2392CTO       | Notebook    | [8c1cf48875](https://linux-hardware.org/?probe=8c1cf48875) | Jan 07, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [34259527c2](https://linux-hardware.org/?probe=34259527c2) | Jan 07, 2023 |
| Framework     | Laptop                      | Notebook    | [cfabfdec3c](https://linux-hardware.org/?probe=cfabfdec3c) | Jan 07, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [df845fe4a9](https://linux-hardware.org/?probe=df845fe4a9) | Jan 07, 2023 |
| System76      | Lemur Pro                   | Notebook    | [36156d9aa7](https://linux-hardware.org/?probe=36156d9aa7) | Jan 07, 2023 |
| Acer          | FMCP7A-ION-LE               | Desktop     | [84a2abec03](https://linux-hardware.org/?probe=84a2abec03) | Jan 07, 2023 |
| Dell          | Inspiron 13 5320            | Notebook    | [0007a36030](https://linux-hardware.org/?probe=0007a36030) | Jan 07, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [667330c83f](https://linux-hardware.org/?probe=667330c83f) | Jan 07, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [82052bbfcb](https://linux-hardware.org/?probe=82052bbfcb) | Jan 07, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [99e2769927](https://linux-hardware.org/?probe=99e2769927) | Jan 07, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [fff1e286b7](https://linux-hardware.org/?probe=fff1e286b7) | Jan 07, 2023 |
| HP            | ZBook Studio G5             | Notebook    | [dfd35ce9ca](https://linux-hardware.org/?probe=dfd35ce9ca) | Jan 07, 2023 |
| Alienware     | m15 Ryzen Ed. R5            | Notebook    | [bf4c8770e7](https://linux-hardware.org/?probe=bf4c8770e7) | Jan 07, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [ff95fa094b](https://linux-hardware.org/?probe=ff95fa094b) | Jan 06, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [1fc8d104f7](https://linux-hardware.org/?probe=1fc8d104f7) | Jan 06, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [0a6589c07d](https://linux-hardware.org/?probe=0a6589c07d) | Jan 06, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [ab29e81efd](https://linux-hardware.org/?probe=ab29e81efd) | Jan 06, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [684653e302](https://linux-hardware.org/?probe=684653e302) | Jan 06, 2023 |
| Acer          | Aspire A515-47              | Notebook    | [896288776d](https://linux-hardware.org/?probe=896288776d) | Jan 06, 2023 |
| Lenovo        | 32E9 SDK0T76461 WIN 3422... | Desktop     | [fcc2d12f0d](https://linux-hardware.org/?probe=fcc2d12f0d) | Jan 06, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [68e299de33](https://linux-hardware.org/?probe=68e299de33) | Jan 06, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [9946b25232](https://linux-hardware.org/?probe=9946b25232) | Jan 06, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [fd5120fea6](https://linux-hardware.org/?probe=fd5120fea6) | Jan 06, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [0b9a54a591](https://linux-hardware.org/?probe=0b9a54a591) | Jan 06, 2023 |
| Lenovo        | ThinkPad T430 2349KB4       | Notebook    | [4546ecbe85](https://linux-hardware.org/?probe=4546ecbe85) | Jan 06, 2023 |
| Chuwi         | HeroBook Air                | Notebook    | [58434d2c3c](https://linux-hardware.org/?probe=58434d2c3c) | Jan 06, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [ec6743fa1b](https://linux-hardware.org/?probe=ec6743fa1b) | Jan 06, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [c84d3b6b03](https://linux-hardware.org/?probe=c84d3b6b03) | Jan 06, 2023 |
| Dell          | G15 5525                    | Notebook    | [2c61cbc942](https://linux-hardware.org/?probe=2c61cbc942) | Jan 06, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [bcc4cba81a](https://linux-hardware.org/?probe=bcc4cba81a) | Jan 06, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [cddb2a7b81](https://linux-hardware.org/?probe=cddb2a7b81) | Jan 06, 2023 |
| Dell          | 02YRK5 A02                  | Desktop     | [e417e45252](https://linux-hardware.org/?probe=e417e45252) | Jan 06, 2023 |
| Dell          | 02YRK5 A02                  | Desktop     | [e7b27ba60c](https://linux-hardware.org/?probe=e7b27ba60c) | Jan 06, 2023 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [7fe70dc4c8](https://linux-hardware.org/?probe=7fe70dc4c8) | Jan 06, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [0cca8fbbb6](https://linux-hardware.org/?probe=0cca8fbbb6) | Jan 05, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [c47405aaf4](https://linux-hardware.org/?probe=c47405aaf4) | Jan 05, 2023 |
| Lenovo        | ThinkPad X220 4290KJ6       | Notebook    | [8296e61afd](https://linux-hardware.org/?probe=8296e61afd) | Jan 05, 2023 |
| Acer          | Predator PT515-51           | Notebook    | [77651b16db](https://linux-hardware.org/?probe=77651b16db) | Jan 05, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [a559464349](https://linux-hardware.org/?probe=a559464349) | Jan 05, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | Desktop     | [0ae0a8d91b](https://linux-hardware.org/?probe=0ae0a8d91b) | Jan 05, 2023 |
| Lenovo        | ThinkPad T460 20FMS49100    | Notebook    | [28af5637ef](https://linux-hardware.org/?probe=28af5637ef) | Jan 05, 2023 |
| Lenovo        | ThinkPad T460 20FMS49100    | Notebook    | [4605f322cb](https://linux-hardware.org/?probe=4605f322cb) | Jan 05, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [31f9cd0972](https://linux-hardware.org/?probe=31f9cd0972) | Jan 05, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | Notebook    | [a2ec6616aa](https://linux-hardware.org/?probe=a2ec6616aa) | Jan 05, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [8ac0b43549](https://linux-hardware.org/?probe=8ac0b43549) | Jan 05, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [24d21ee9f1](https://linux-hardware.org/?probe=24d21ee9f1) | Jan 05, 2023 |
| MSI           | Modern 14 B4MW              | Notebook    | [b7855a84cf](https://linux-hardware.org/?probe=b7855a84cf) | Jan 05, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [1964dbc8e7](https://linux-hardware.org/?probe=1964dbc8e7) | Jan 05, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [d1c9231969](https://linux-hardware.org/?probe=d1c9231969) | Jan 05, 2023 |
| HP            | EliteBook 840 G5 NOTEBOO... | Notebook    | [343d0f4c48](https://linux-hardware.org/?probe=343d0f4c48) | Jan 04, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [39f45e87d1](https://linux-hardware.org/?probe=39f45e87d1) | Jan 04, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [2f4bb5b17d](https://linux-hardware.org/?probe=2f4bb5b17d) | Jan 04, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [272d23ec5d](https://linux-hardware.org/?probe=272d23ec5d) | Jan 04, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [76f2ef98b9](https://linux-hardware.org/?probe=76f2ef98b9) | Jan 04, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [50d8f0c1cb](https://linux-hardware.org/?probe=50d8f0c1cb) | Jan 04, 2023 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [4c54844f40](https://linux-hardware.org/?probe=4c54844f40) | Jan 04, 2023 |
| Positivo      | POS-PIQ57BQA                | Desktop     | [4453ef0d86](https://linux-hardware.org/?probe=4453ef0d86) | Jan 04, 2023 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [5c352967e4](https://linux-hardware.org/?probe=5c352967e4) | Jan 04, 2023 |
| HP            | Notebook                    | Notebook    | [679c0bfbe8](https://linux-hardware.org/?probe=679c0bfbe8) | Jan 04, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [26826e3c23](https://linux-hardware.org/?probe=26826e3c23) | Jan 04, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [0c4e0afd97](https://linux-hardware.org/?probe=0c4e0afd97) | Jan 04, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [6d6e710ac3](https://linux-hardware.org/?probe=6d6e710ac3) | Jan 04, 2023 |
| Lenovo        | ThinkPad X390 Yoga 20NN0... | Convertible | [7f62577241](https://linux-hardware.org/?probe=7f62577241) | Jan 04, 2023 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [583ea447a9](https://linux-hardware.org/?probe=583ea447a9) | Jan 04, 2023 |
| Dell          | 0N4YC8 A00                  | Desktop     | [0968211c5b](https://linux-hardware.org/?probe=0968211c5b) | Jan 04, 2023 |
| Dell          | 0N4YC8 A00                  | Desktop     | [4195800fa5](https://linux-hardware.org/?probe=4195800fa5) | Jan 04, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [6a38362bbe](https://linux-hardware.org/?probe=6a38362bbe) | Jan 04, 2023 |
| Unknown       | Unknown                     | Notebook    | [b363093f89](https://linux-hardware.org/?probe=b363093f89) | Jan 04, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [ad776cdf84](https://linux-hardware.org/?probe=ad776cdf84) | Jan 04, 2023 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [2849ffe456](https://linux-hardware.org/?probe=2849ffe456) | Jan 04, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [5741654cdc](https://linux-hardware.org/?probe=5741654cdc) | Jan 04, 2023 |
| Dell          | 0KRC95 A02                  | Desktop     | [8e30a9a43e](https://linux-hardware.org/?probe=8e30a9a43e) | Jan 04, 2023 |
| MSI           | Modern 14 B11MOU            | Notebook    | [036ae164e8](https://linux-hardware.org/?probe=036ae164e8) | Jan 04, 2023 |
| Positivo      | POS-PIQ57BQA                | Desktop     | [e03b53cc0e](https://linux-hardware.org/?probe=e03b53cc0e) | Jan 04, 2023 |
| Clevo         | M815P                       | Notebook    | [7f1503c5e6](https://linux-hardware.org/?probe=7f1503c5e6) | Jan 03, 2023 |
| MSI           | Katana GF66 11SC            | Notebook    | [d788f444ff](https://linux-hardware.org/?probe=d788f444ff) | Jan 03, 2023 |
| HP            | ProBook 6570b               | Notebook    | [875054c6d7](https://linux-hardware.org/?probe=875054c6d7) | Jan 03, 2023 |
| ASUSTek       | X453MA                      | Notebook    | [1584b0616c](https://linux-hardware.org/?probe=1584b0616c) | Jan 03, 2023 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [496bc9b9cd](https://linux-hardware.org/?probe=496bc9b9cd) | Jan 03, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [abdf0ab0b9](https://linux-hardware.org/?probe=abdf0ab0b9) | Jan 03, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [5c14d6ea96](https://linux-hardware.org/?probe=5c14d6ea96) | Jan 03, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | Notebook    | [40af3a30ca](https://linux-hardware.org/?probe=40af3a30ca) | Jan 03, 2023 |
| Lenovo        | ThinkPad T590 20N5S2NC1V    | Notebook    | [c621679405](https://linux-hardware.org/?probe=c621679405) | Jan 03, 2023 |
| HP            | 240 G8 Notebook PC          | Notebook    | [a316608c78](https://linux-hardware.org/?probe=a316608c78) | Jan 03, 2023 |
| Microsoft     | Surface Laptop Studio       | Tablet      | [084f1cf7cb](https://linux-hardware.org/?probe=084f1cf7cb) | Jan 03, 2023 |
| Positivo      | POS-EIB85CZ                 | Desktop     | [639f5a2bf7](https://linux-hardware.org/?probe=639f5a2bf7) | Jan 03, 2023 |
| MSI           | Katana GF66 11SC            | Notebook    | [5a078a161f](https://linux-hardware.org/?probe=5a078a161f) | Jan 03, 2023 |
| Microsoft     | Surface Laptop Studio       | Tablet      | [ee3dc404e1](https://linux-hardware.org/?probe=ee3dc404e1) | Jan 03, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [f1962e0076](https://linux-hardware.org/?probe=f1962e0076) | Jan 03, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [43ff03b36f](https://linux-hardware.org/?probe=43ff03b36f) | Jan 03, 2023 |
| Dell          | 0KRC95 A02                  | Desktop     | [d7c57c2bae](https://linux-hardware.org/?probe=d7c57c2bae) | Jan 03, 2023 |
| Toshiba       | Satellite C50-A             | Notebook    | [9b02393248](https://linux-hardware.org/?probe=9b02393248) | Jan 02, 2023 |
| PINE64        | Pinebook Pro                | Soc         | [d8cd86db45](https://linux-hardware.org/?probe=d8cd86db45) | Jan 02, 2023 |
| HP            | Notebook                    | Notebook    | [530e6cfeb9](https://linux-hardware.org/?probe=530e6cfeb9) | Jan 02, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [386eb7bc28](https://linux-hardware.org/?probe=386eb7bc28) | Jan 02, 2023 |
| Clevo         | M815P                       | Notebook    | [034cecc238](https://linux-hardware.org/?probe=034cecc238) | Jan 02, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | Desktop     | [7c98c0b00d](https://linux-hardware.org/?probe=7c98c0b00d) | Jan 02, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [daeb060f32](https://linux-hardware.org/?probe=daeb060f32) | Jan 02, 2023 |
| Acer          | Aspire A315-31              | Notebook    | [4a79c65764](https://linux-hardware.org/?probe=4a79c65764) | Jan 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [bbd09c7b2c](https://linux-hardware.org/?probe=bbd09c7b2c) | Jan 02, 2023 |
| ASUSTek       | X756UXK                     | Notebook    | [f0bc632c50](https://linux-hardware.org/?probe=f0bc632c50) | Jan 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [013b1e7816](https://linux-hardware.org/?probe=013b1e7816) | Jan 02, 2023 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [f85aeab3e5](https://linux-hardware.org/?probe=f85aeab3e5) | Jan 02, 2023 |
| ASUSTek       | PRIME B350M-E               | Desktop     | [f39e3e8350](https://linux-hardware.org/?probe=f39e3e8350) | Jan 02, 2023 |
| ASUSTek       | TUF B365M-PLUS GAMING       | Desktop     | [4e900247e4](https://linux-hardware.org/?probe=4e900247e4) | Jan 02, 2023 |
| ASRock        | Z77 Professional            | Desktop     | [bf09b21dc7](https://linux-hardware.org/?probe=bf09b21dc7) | Jan 02, 2023 |
| Dell          | Latitude 7410               | Notebook    | [acb8ce902e](https://linux-hardware.org/?probe=acb8ce902e) | Jan 01, 2023 |
| ASRock        | FM2A88M-HD+ R2.0            | Desktop     | [8e9080dc74](https://linux-hardware.org/?probe=8e9080dc74) | Jan 01, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [c753f769b4](https://linux-hardware.org/?probe=c753f769b4) | Jan 01, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [f84116ec07](https://linux-hardware.org/?probe=f84116ec07) | Jan 01, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [033b62b374](https://linux-hardware.org/?probe=033b62b374) | Jan 01, 2023 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [752fe53b7c](https://linux-hardware.org/?probe=752fe53b7c) | Jan 01, 2023 |
| Intel         | DG41TY AAE47335-300         | Desktop     | [11f3804cb6](https://linux-hardware.org/?probe=11f3804cb6) | Jan 01, 2023 |
| Fujitsu       | LIFEBOOK U749               | Notebook    | [c09072c09f](https://linux-hardware.org/?probe=c09072c09f) | Jan 01, 2023 |
| ASUSTek       | P8Z68-V GEN3                | Desktop     | [3b6d1593c8](https://linux-hardware.org/?probe=3b6d1593c8) | Jan 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [54089a466b](https://linux-hardware.org/?probe=54089a466b) | Jan 01, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [f438866c0d](https://linux-hardware.org/?probe=f438866c0d) | Jan 01, 2023 |
| Lenovo        | ThinkPad X270 20K60018GE    | Notebook    | [a92939c1f5](https://linux-hardware.org/?probe=a92939c1f5) | Jan 01, 2023 |
| Lenovo        | ThinkPad X390 20Q00051GE    | Notebook    | [5b3d1b750d](https://linux-hardware.org/?probe=5b3d1b750d) | Dec 31, 2022 |
| Valve         | Jupiter                     | Notebook    | [c0fb48bccb](https://linux-hardware.org/?probe=c0fb48bccb) | Dec 31, 2022 |
| System76      | Oryx Pro                    | Notebook    | [0d65e57758](https://linux-hardware.org/?probe=0d65e57758) | Dec 31, 2022 |
| Lenovo        | ThinkPad X390 20Q00051GE    | Notebook    | [775096be09](https://linux-hardware.org/?probe=775096be09) | Dec 31, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [322cf5484d](https://linux-hardware.org/?probe=322cf5484d) | Dec 31, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [f16b55ea54](https://linux-hardware.org/?probe=f16b55ea54) | Dec 31, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora_37/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                          | Computers | Percent |
|----------------------------------|-----------|---------|
| 6.0.15-300.fc37.x86_64           | 131       | 8.48%   |
| 6.0.12-300.fc37.x86_64           | 107       | 6.93%   |
| 6.0.7-301.fc37.x86_64            | 102       | 6.6%    |
| 6.0.9-300.fc37.x86_64            | 85        | 5.5%    |
| 6.0.8-300.fc37.x86_64            | 85        | 5.5%    |
| 6.1.7-200.fc37.x86_64            | 77        | 4.98%   |
| 6.0.11-300.fc37.x86_64           | 69        | 4.47%   |
| 6.1.8-200.fc37.x86_64            | 67        | 4.34%   |
| 6.1.9-200.fc37.x86_64            | 64        | 4.14%   |
| 6.1.6-200.fc37.x86_64            | 64        | 4.14%   |
| 6.1.11-200.fc37.x86_64           | 64        | 4.14%   |
| 6.0.10-300.fc37.x86_64           | 62        | 4.01%   |
| 6.0.18-300.fc37.x86_64           | 48        | 3.11%   |
| 6.1.10-200.fc37.x86_64           | 46        | 2.98%   |
| 6.1.13-200.fc37.x86_64           | 43        | 2.78%   |
| 6.0.16-300.fc37.x86_64           | 40        | 2.59%   |
| 5.19.16-301.fc37.x86_64          | 39        | 2.52%   |
| 6.1.5-200.fc37.x86_64            | 35        | 2.27%   |
| 6.0.17-300.fc37.x86_64           | 29        | 1.88%   |
| 6.0.14-300.fc37.x86_64           | 28        | 1.81%   |
| 6.1.12-200.fc37.x86_64           | 24        | 1.55%   |
| 6.0.13-300.fc37.x86_64           | 22        | 1.42%   |
| 5.19.13-300.fc37.x86_64          | 18        | 1.17%   |
| 5.19.8-300.fc37.x86_64           | 15        | 0.97%   |
| 5.19.9-300.fc37.x86_64           | 14        | 0.91%   |
| 5.19.7-300.fc37.x86_64           | 14        | 0.91%   |
| 6.0.6-300.fc37.x86_64            | 9         | 0.58%   |
| 5.19.15-301.fc37.x86_64          | 9         | 0.58%   |
| 5.19.14-300.fc37.x86_64          | 8         | 0.52%   |
| 5.19.12-300.fc37.x86_64          | 7         | 0.45%   |
| 5.19.10-300.fc37.x86_64          | 7         | 0.45%   |
| 6.0.5-300.fc37.x86_64            | 6         | 0.39%   |
| 5.19.16-300.fc37.x86_64          | 6         | 0.39%   |
| 5.19.11-300.fc37.x86_64          | 6         | 0.39%   |
| 5.17.5-300.fc36.x86_64           | 3         | 0.19%   |
| 6.1.2-200.fc37.x86_64            | 2         | 0.13%   |
| 6.1.11-201.fsync.fc37.x86_64     | 2         | 0.13%   |
| 6.1.0-0.rc4.34.inttf.fc37.x86_64 | 2         | 0.13%   |
| 6.0.9-302.rog.fc37.x86_64        | 2         | 0.13%   |
| 6.0.9-300.mbp.fc37.x86_64        | 2         | 0.13%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.0.15  | 134       | 8.67%   |
| 6.0.12  | 109       | 7.06%   |
| 6.0.7   | 104       | 6.73%   |
| 6.0.9   | 92        | 5.95%   |
| 6.0.8   | 89        | 5.76%   |
| 6.1.7   | 77        | 4.98%   |
| 6.0.11  | 70        | 4.53%   |
| 6.1.8   | 69        | 4.47%   |
| 6.1.11  | 68        | 4.4%    |
| 6.1.9   | 65        | 4.21%   |
| 6.0.10  | 65        | 4.21%   |
| 6.1.6   | 64        | 4.14%   |
| 6.1.10  | 48        | 3.11%   |
| 6.0.18  | 48        | 3.11%   |
| 5.19.16 | 47        | 3.04%   |
| 6.1.13  | 43        | 2.78%   |
| 6.0.16  | 42        | 2.72%   |
| 6.1.5   | 36        | 2.33%   |
| 6.0.17  | 30        | 1.94%   |
| 6.0.14  | 28        | 1.81%   |
| 6.1.12  | 26        | 1.68%   |
| 6.0.13  | 23        | 1.49%   |
| 5.19.13 | 19        | 1.23%   |
| 5.19.8  | 16        | 1.04%   |
| 5.19.9  | 14        | 0.91%   |
| 5.19.7  | 14        | 0.91%   |
| 5.19.15 | 11        | 0.71%   |
| 6.1.0   | 9         | 0.58%   |
| 6.0.6   | 9         | 0.58%   |
| 5.19.14 | 9         | 0.58%   |
| 5.19.12 | 9         | 0.58%   |
| 5.19.10 | 9         | 0.58%   |
| 6.0.5   | 7         | 0.45%   |
| 5.19.11 | 6         | 0.39%   |
| 5.19.0  | 5         | 0.32%   |
| 5.18.0  | 4         | 0.26%   |
| 6.2.0   | 3         | 0.19%   |
| 6.0.2   | 3         | 0.19%   |
| 6.0.0   | 3         | 0.19%   |
| 5.17.5  | 3         | 0.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.0     | 814       | 54.93%  |
| 6.1     | 495       | 33.4%   |
| 5.19    | 156       | 10.53%  |
| 5.18    | 5         | 0.34%   |
| 5.17    | 4         | 0.27%   |
| 6.2     | 3         | 0.2%    |
| 5.15    | 2         | 0.13%   |
| 5.8     | 1         | 0.07%   |
| 5.10    | 1         | 0.07%   |
| 5.0     | 1         | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1418      | 99.51%  |
| aarch64 | 7         | 0.49%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| GNOME                        | 1069      | 74.65%  |
| KDE5                         | 237       | 16.55%  |
| Unknown                      | 37        | 2.58%   |
| XFCE                         | 22        | 1.54%   |
| X-Cinnamon                   | 15        | 1.05%   |
| MATE                         | 11        | 0.77%   |
| i3                           | 11        | 0.77%   |
| Cinnamon                     | 10        | 0.7%    |
| LXDE                         | 4         | 0.28%   |
| sway                         | 3         | 0.21%   |
| GNOME Classic                | 3         | 0.21%   |
| LXQt                         | 2         | 0.14%   |
| KDE                          | 2         | 0.14%   |
| xmonad                       | 1         | 0.07%   |
| qtile                        | 1         | 0.07%   |
| Phosh:GNOME                  | 1         | 0.07%   |
| GNOME-Classic                | 1         | 0.07%   |
| bspwm                        | 1         | 0.07%   |
| ${XDG_CURRENT_DESKTOP:-sway} | 1         | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 1053      | 73.23%  |
| X11     | 344       | 23.92%  |
| Unknown | 22        | 1.53%   |
| Tty     | 19        | 1.32%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 753       | 52.44%  |
| GDM     | 484       | 33.7%   |
| SDDM    | 119       | 8.29%   |
| LightDM | 76        | 5.29%   |
| LXDM    | 3         | 0.21%   |
| GREETD  | 1         | 0.07%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 760       | 53.18%  |
| en_GB   | 105       | 7.35%   |
| ru_RU   | 90        | 6.3%    |
| de_DE   | 64        | 4.48%   |
| pt_BR   | 58        | 4.06%   |
| fr_FR   | 44        | 3.08%   |
| it_IT   | 33        | 2.31%   |
| en_CA   | 30        | 2.1%    |
| en_AU   | 29        | 2.03%   |
| pl_PL   | 25        | 1.75%   |
| es_ES   | 21        | 1.47%   |
| en_IN   | 20        | 1.4%    |
| es_MX   | 9         | 0.63%   |
| C       | 9         | 0.63%   |
| es_CL   | 8         | 0.56%   |
| zh_CN   | 7         | 0.49%   |
| tr_TR   | 7         | 0.49%   |
| hu_HU   | 6         | 0.42%   |
| en_IE   | 6         | 0.42%   |
| de_AT   | 6         | 0.42%   |
| cs_CZ   | 6         | 0.42%   |
| fi_FI   | 5         | 0.35%   |
| es_AR   | 5         | 0.35%   |
| Unknown | 5         | 0.35%   |
| zh_TW   | 4         | 0.28%   |
| nl_NL   | 4         | 0.28%   |
| en_ZA   | 4         | 0.28%   |
| en_NZ   | 4         | 0.28%   |
| de_CH   | 4         | 0.28%   |
| sv_SE   | 3         | 0.21%   |
| es_CO   | 3         | 0.21%   |
| en_PH   | 3         | 0.21%   |
| ca_ES   | 3         | 0.21%   |
| vi_VN   | 2         | 0.14%   |
| pt_PT   | 2         | 0.14%   |
| nb_NO   | 2         | 0.14%   |
| ko_KR   | 2         | 0.14%   |
| fr_CA   | 2         | 0.14%   |
| es_VE   | 2         | 0.14%   |
| es_US   | 2         | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1189      | 83.15%  |
| BIOS | 241       | 16.85%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 1162      | 81.43%  |
| Ext4    | 229       | 16.05%  |
| Xfs     | 29        | 2.03%   |
| Overlay | 5         | 0.35%   |
| F2fs    | 2         | 0.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 720       | 50.24%  |
| GPT     | 665       | 46.41%  |
| MBR     | 48        | 3.35%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1282      | 89.53%  |
| Yes       | 150       | 10.47%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1153      | 80.74%  |
| Yes       | 275       | 19.26%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 287       | 20.14%  |
| ASUSTek Computer    | 264       | 18.53%  |
| Dell                | 179       | 12.56%  |
| Hewlett-Packard     | 169       | 11.86%  |
| MSI                 | 91        | 6.39%   |
| Gigabyte Technology | 73        | 5.12%   |
| Acer                | 73        | 5.12%   |
| ASRock              | 45        | 3.16%   |
| HUAWEI              | 31        | 2.18%   |
| Apple               | 21        | 1.47%   |
| Intel               | 17        | 1.19%   |
| Samsung Electronics | 15        | 1.05%   |
| Timi                | 12        | 0.84%   |
| Microsoft           | 10        | 0.7%    |
| Google              | 10        | 0.7%    |
| Toshiba             | 9         | 0.63%   |
| TUXEDO              | 7         | 0.49%   |
| Pegatron            | 5         | 0.35%   |
| GPD                 | 5         | 0.35%   |
| Fujitsu             | 5         | 0.35%   |
| Schenker            | 4         | 0.28%   |
| Chuwi               | 4         | 0.28%   |
| Alienware           | 4         | 0.28%   |
| Unknown             | 4         | 0.28%   |
| System76            | 3         | 0.21%   |
| Positivo            | 3         | 0.21%   |
| HONOR               | 3         | 0.21%   |
| Framework           | 3         | 0.21%   |
| Dynabook            | 3         | 0.21%   |
| AZW                 | 3         | 0.21%   |
| TECNO               | 2         | 0.14%   |
| Supermicro          | 2         | 0.14%   |
| Standard            | 2         | 0.14%   |
| Sony                | 2         | 0.14%   |
| SLIMBOOK            | 2         | 0.14%   |
| PINE64              | 2         | 0.14%   |
| Notebook            | 2         | 0.14%   |
| MACHENIKE           | 2         | 0.14%   |
| LG Electronics      | 2         | 0.14%   |
| Valve               | 1         | 0.07%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| ASUS All Series                        | 13        | 0.91%   |
| Unknown                                | 7         | 0.49%   |
| Dell OptiPlex 7010                     | 6         | 0.42%   |
| Dell XPS 13 7390                       | 5         | 0.35%   |
| MSI MS-7C84                            | 4         | 0.28%   |
| MSI MS-7C37                            | 4         | 0.28%   |
| MSI MS-7C02                            | 4         | 0.28%   |
| MSI MS-7A38                            | 4         | 0.28%   |
| Lenovo ThinkBook 15 G3 ACL 21A4        | 4         | 0.28%   |
| Lenovo IdeaPad 330-15IKB 81DE          | 4         | 0.28%   |
| HUAWEI MACH-WX9                        | 4         | 0.28%   |
| HUAWEI CREM-WXX9                       | 4         | 0.28%   |
| HP OMEN by Laptop 16-c0xxx             | 4         | 0.28%   |
| HP Notebook                            | 4         | 0.28%   |
| Dell Inspiron 5566                     | 4         | 0.28%   |
| ASUS VivoBook_ASUSLaptop X515EA_X515EA | 4         | 0.28%   |
| ASUS TUF Gaming X570-PLUS              | 4         | 0.28%   |
| ASUS TUF Gaming B550M-PLUS             | 4         | 0.28%   |
| ASUS ROG STRIX B450-F GAMING           | 4         | 0.28%   |
| ASUS ProArt Z690-CREATOR WIFI          | 4         | 0.28%   |
| ASUS ProArt X670E-CREATOR WIFI         | 4         | 0.28%   |
| ASUS PRIME B450M-A II                  | 4         | 0.28%   |
| MSI MS-7C56                            | 3         | 0.21%   |
| MSI Modern 14 B11MOU                   | 3         | 0.21%   |
| Lenovo Yoga 9 14IAP7 82LU              | 3         | 0.21%   |
| Lenovo Legion 5 15ACH6H 82JU           | 3         | 0.21%   |
| Lenovo IdeaPadFlex 5 14ARE05 81X2      | 3         | 0.21%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK  | 3         | 0.21%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5       | 3         | 0.21%   |
| Intel NUC8i7BEH                        | 3         | 0.21%   |
| HUAWEI KLVL-WXX9                       | 3         | 0.21%   |
| HP ProBook 440 G7                      | 3         | 0.21%   |
| GPD G1619-04                           | 3         | 0.21%   |
| Gigabyte B550M DS3H                    | 3         | 0.21%   |
| Dell XPS 15 9570                       | 3         | 0.21%   |
| Dell XPS 15 9520                       | 3         | 0.21%   |
| Dell XPS 15 9510                       | 3         | 0.21%   |
| Dell Latitude E7270                    | 3         | 0.21%   |
| Dell Latitude 7490                     | 3         | 0.21%   |
| Dell Latitude 7480                     | 3         | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 153       | 10.74%  |
| Dell Inspiron      | 56        | 3.93%   |
| ASUS ROG           | 54        | 3.79%   |
| Lenovo IdeaPad     | 52        | 3.65%   |
| Dell Latitude      | 48        | 3.37%   |
| ASUS PRIME         | 39        | 2.74%   |
| Acer Aspire        | 39        | 2.74%   |
| ASUS VivoBook      | 33        | 2.32%   |
| HP Pavilion        | 31        | 2.18%   |
| Dell XPS           | 29        | 2.04%   |
| HP EliteBook       | 27        | 1.89%   |
| ASUS TUF           | 24        | 1.68%   |
| Lenovo ThinkBook   | 23        | 1.61%   |
| HP Laptop          | 23        | 1.61%   |
| HP ProBook         | 17        | 1.19%   |
| Lenovo Yoga        | 16        | 1.12%   |
| HP ENVY            | 16        | 1.12%   |
| ASUS Zenbook       | 16        | 1.12%   |
| ASUS ASUS          | 16        | 1.12%   |
| Dell OptiPlex      | 15        | 1.05%   |
| Lenovo Legion      | 14        | 0.98%   |
| Dell Precision     | 13        | 0.91%   |
| ASUS All           | 13        | 0.91%   |
| Acer Nitro         | 13        | 0.91%   |
| Microsoft Surface  | 10        | 0.7%    |
| HP ZBook           | 9         | 0.63%   |
| Toshiba Satellite  | 8         | 0.56%   |
| Dell Vostro        | 8         | 0.56%   |
| ASUS ProArt        | 8         | 0.56%   |
| MSI Modern         | 7         | 0.49%   |
| Lenovo ThinkCentre | 7         | 0.49%   |
| HP OMEN            | 7         | 0.49%   |
| Acer Predator      | 7         | 0.49%   |
| Unknown            | 7         | 0.49%   |
| Lenovo IdeaPadFlex | 5         | 0.35%   |
| HP Spectre         | 5         | 0.35%   |
| Gigabyte X570      | 5         | 0.35%   |
| Gigabyte B550M     | 5         | 0.35%   |
| Gigabyte B550      | 5         | 0.35%   |
| Acer Swift         | 5         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 237       | 16.63%  |
| 2022    | 213       | 14.95%  |
| 2020    | 211       | 14.81%  |
| 2019    | 160       | 11.23%  |
| 2018    | 143       | 10.04%  |
| 2017    | 98        | 6.88%   |
| 2012    | 66        | 4.63%   |
| 2013    | 61        | 4.28%   |
| 2015    | 51        | 3.58%   |
| 2016    | 50        | 3.51%   |
| 2014    | 42        | 2.95%   |
| 2011    | 29        | 2.04%   |
| 2010    | 24        | 1.68%   |
| 2008    | 15        | 1.05%   |
| 2009    | 14        | 0.98%   |
| 2023    | 4         | 0.28%   |
| 2007    | 3         | 0.21%   |
| 2006    | 3         | 0.21%   |
| Unknown | 1         | 0.07%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 865       | 60.7%   |
| Desktop        | 421       | 29.54%  |
| Convertible    | 82        | 5.75%   |
| Mini pc        | 20        | 1.4%    |
| Tablet         | 18        | 1.26%   |
| All in one     | 10        | 0.7%    |
| System on chip | 6         | 0.42%   |
| Server         | 3         | 0.21%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1097      | 76.5%   |
| Enabled  | 337       | 23.5%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1414      | 99.23%  |
| Yes  | 11        | 0.77%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 367       | 25.66%  |
| 4.01-8.0        | 304       | 21.26%  |
| 8.01-16.0       | 282       | 19.72%  |
| 32.01-64.0      | 236       | 16.5%   |
| 3.01-4.0        | 101       | 7.06%   |
| 64.01-256.0     | 68        | 4.76%   |
| 24.01-32.0      | 51        | 3.57%   |
| 1.01-2.0        | 16        | 1.12%   |
| 2.01-3.0        | 3         | 0.21%   |
| More than 256.0 | 2         | 0.14%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 511       | 34.16%  |
| 3.01-4.0   | 336       | 22.46%  |
| 2.01-3.0   | 336       | 22.46%  |
| 8.01-16.0  | 138       | 9.22%   |
| 1.01-2.0   | 133       | 8.89%   |
| 0.51-1.0   | 19        | 1.27%   |
| 16.01-24.0 | 15        | 1%      |
| 32.01-64.0 | 4         | 0.27%   |
| 24.01-32.0 | 2         | 0.13%   |
| 0.01-0.5   | 2         | 0.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 865       | 60.36%  |
| 2      | 349       | 24.35%  |
| 3      | 111       | 7.75%   |
| 4      | 54        | 3.77%   |
| 5      | 21        | 1.47%   |
| 6      | 11        | 0.77%   |
| 0      | 9         | 0.63%   |
| 7      | 5         | 0.35%   |
| 9      | 3         | 0.21%   |
| 8      | 2         | 0.14%   |
| 18     | 1         | 0.07%   |
| 15     | 1         | 0.07%   |
| 12     | 1         | 0.07%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1188      | 83.25%  |
| Yes       | 239       | 16.75%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1058      | 74.19%  |
| No        | 368       | 25.81%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1182      | 82.77%  |
| No        | 246       | 17.23%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1083      | 75.68%  |
| No        | 348       | 24.32%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 265       | 18.52%  |
| Germany     | 117       | 8.18%   |
| Russia      | 108       | 7.55%   |
| Brazil      | 84        | 5.87%   |
| Italy       | 69        | 4.82%   |
| France      | 54        | 3.77%   |
| India       | 48        | 3.35%   |
| Canada      | 48        | 3.35%   |
| Poland      | 47        | 3.28%   |
| UK          | 43        | 3%      |
| Australia   | 37        | 2.59%   |
| Spain       | 34        | 2.38%   |
| Netherlands | 31        | 2.17%   |
| Turkey      | 26        | 1.82%   |
| Austria     | 25        | 1.75%   |
| Sweden      | 22        | 1.54%   |
| Mexico      | 17        | 1.19%   |
| Czechia     | 17        | 1.19%   |
| Switzerland | 16        | 1.12%   |
| Taiwan      | 13        | 0.91%   |
| Hungary     | 13        | 0.91%   |
| Romania     | 12        | 0.84%   |
| Belgium     | 12        | 0.84%   |
| Norway      | 11        | 0.77%   |
| Indonesia   | 11        | 0.77%   |
| Vietnam     | 9         | 0.63%   |
| Thailand    | 9         | 0.63%   |
| Argentina   | 9         | 0.63%   |
| Portugal    | 8         | 0.56%   |
| Israel      | 8         | 0.56%   |
| Greece      | 8         | 0.56%   |
| Finland     | 8         | 0.56%   |
| Chile       | 8         | 0.56%   |
| Serbia      | 7         | 0.49%   |
| Ireland     | 7         | 0.49%   |
| Denmark     | 7         | 0.49%   |
| Slovakia    | 6         | 0.42%   |
| Japan       | 6         | 0.42%   |
| Colombia    | 6         | 0.42%   |
| Ukraine     | 5         | 0.35%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 30        | 2.05%   |
| Sydney            | 14        | 0.96%   |
| Berlin            | 14        | 0.96%   |
| Vienna            | 13        | 0.89%   |
| Warsaw            | 12        | 0.82%   |
| St Petersburg     | 11        | 0.75%   |
| Madrid            | 11        | 0.75%   |
| Sao Paulo         | 10        | 0.68%   |
| London            | 10        | 0.68%   |
| Istanbul          | 10        | 0.68%   |
| Frankfurt am Main | 9         | 0.61%   |
| Milan             | 8         | 0.55%   |
| Budapest          | 8         | 0.55%   |
| New Taipei        | 7         | 0.48%   |
| Montreal          | 7         | 0.48%   |
| Melbourne         | 7         | 0.48%   |
| Amsterdam         | 7         | 0.48%   |
| Prague            | 6         | 0.41%   |
| Portland          | 6         | 0.41%   |
| Izmir             | 6         | 0.41%   |
| Brisbane          | 6         | 0.41%   |
| Bengaluru         | 6         | 0.41%   |
| Atlanta           | 6         | 0.41%   |
| Zurich            | 5         | 0.34%   |
| Yekaterinburg     | 5         | 0.34%   |
| Santiago          | 5         | 0.34%   |
| Riga              | 5         | 0.34%   |
| Porto Alegre      | 5         | 0.34%   |
| Paris             | 5         | 0.34%   |
| Novosibirsk       | 5         | 0.34%   |
| New York          | 5         | 0.34%   |
| Miami             | 5         | 0.34%   |
| Krasnodar         | 5         | 0.34%   |
| Innsbruck         | 5         | 0.34%   |
| Ho Chi Minh City  | 5         | 0.34%   |
| Helsinki          | 5         | 0.34%   |
| Bucharest         | 5         | 0.34%   |
| Bogotá           | 5         | 0.34%   |
| Bangkok           | 5         | 0.34%   |
| Zapopan           | 4         | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 471       | 641    | 22.48%  |
| WDC                         | 231       | 341    | 11.03%  |
| Seagate                     | 188       | 239    | 8.97%   |
| SanDisk                     | 161       | 186    | 7.68%   |
| Kingston                    | 118       | 138    | 5.63%   |
| Toshiba                     | 104       | 121    | 4.96%   |
| SK hynix                    | 96        | 103    | 4.58%   |
| Crucial                     | 88        | 103    | 4.2%    |
| Intel                       | 77        | 92     | 3.68%   |
| Micron Technology           | 63        | 71     | 3.01%   |
| Unknown                     | 61        | 75     | 2.91%   |
| KIOXIA                      | 38        | 43     | 1.81%   |
| Phison Electronics          | 32        | 37     | 1.53%   |
| HGST                        | 25        | 39     | 1.19%   |
| Micron/Crucial Technology   | 21        | 24     | 1%      |
| Hitachi                     | 21        | 25     | 1%      |
| A-DATA Technology           | 21        | 22     | 1%      |
| China                       | 20        | 23     | 0.95%   |
| Apple                       | 14        | 20     | 0.67%   |
| SPCC                        | 10        | 13     | 0.48%   |
| PNY                         | 10        | 10     | 0.48%   |
| LITEON                      | 10        | 10     | 0.48%   |
| Kingston Technology Company | 10        | 10     | 0.48%   |
| Apacer                      | 10        | 13     | 0.48%   |
| ADATA Technology            | 10        | 11     | 0.48%   |
| Silicon Motion              | 8         | 9      | 0.38%   |
| Netac                       | 8         | 11     | 0.38%   |
| Realtek Semiconductor       | 7         | 7      | 0.33%   |
| Corsair                     | 7         | 10     | 0.33%   |
| UMIS                        | 6         | 6      | 0.29%   |
| Lexar                       | 6         | 7      | 0.29%   |
| Unknown                     | 6         | 7      | 0.29%   |
| Transcend                   | 5         | 5      | 0.24%   |
| Phison                      | 5         | 5      | 0.24%   |
| JMicron Technology          | 5         | 8      | 0.24%   |
| Intenso                     | 5         | 6      | 0.24%   |
| HS-SSD-E100                 | 5         | 5      | 0.24%   |
| FORESEE                     | 5         | 5      | 0.24%   |
| XPG                         | 4         | 4      | 0.19%   |
| Lite-On Technology          | 4         | 4      | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB  | 88        | 3.85%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 960GB | 44        | 1.92%   |
| Kingston SA400S37240G 240GB SSD                      | 30        | 1.31%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB     | 20        | 0.87%   |
| Seagate ST2000DM008-2FR102 2TB                       | 19        | 0.83%   |
| Seagate ST1000LM035-1RK172 1TB                       | 18        | 0.79%   |
| Toshiba MQ04ABF100 1TB                               | 17        | 0.74%   |
| Crucial CT1000MX500SSD1 1TB                          | 17        | 0.74%   |
| Samsung SSD 870 EVO 500GB                            | 16        | 0.7%    |
| Crucial CT240BX500SSD1 240GB                         | 16        | 0.7%    |
| Sandisk WD Blue SN550 NVMe SSD 1TB                   | 15        | 0.66%   |
| Samsung SSD 860 EVO 500GB                            | 14        | 0.61%   |
| Samsung SSD 850 EVO 250GB                            | 14        | 0.61%   |
| Phison E12 NVMe Controller 1024GB                    | 14        | 0.61%   |
| Intel SSDPEKNU512GZ 512GB                            | 14        | 0.61%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                  | 13        | 0.57%   |
| Kingston SA400S37120G 120GB SSD                      | 13        | 0.57%   |
| Unknown MMC Card  32GB                               | 12        | 0.52%   |
| Samsung SSD 850 EVO 500GB                            | 12        | 0.52%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 512GB  | 12        | 0.52%   |
| Intel SSD 660P Series 1024GB                         | 12        | 0.52%   |
| Samsung SSD 980 PRO 1TB                              | 11        | 0.48%   |
| Kingston SA400S37480G 480GB SSD                      | 11        | 0.48%   |
| Seagate ST500DM002-1BD142 500GB                      | 10        | 0.44%   |
| Samsung SSD 970 EVO Plus 500GB                       | 10        | 0.44%   |
| Samsung SSD 970 EVO Plus 2TB                         | 10        | 0.44%   |
| Samsung SSD 860 EVO 250GB                            | 10        | 0.44%   |
| Samsung SSD 860 EVO 1TB                              | 10        | 0.44%   |
| HGST HTS721010A9E630 1TB                             | 10        | 0.44%   |
| Unknown MMC Card  64GB                               | 9         | 0.39%   |
| Seagate ST1000DM010-2EP102 1TB                       | 9         | 0.39%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 256GB      | 9         | 0.39%   |
| Samsung SSD 980 1TB                                  | 9         | 0.39%   |
| Samsung MZALQ512HBLU-00BL2 512GB                     | 9         | 0.39%   |
| Phison PS5013 E13 NVMe Controller 500GB              | 9         | 0.39%   |
| WDC WD10EZEX-08WN4A0 1TB                             | 8         | 0.35%   |
| Toshiba XG6 NVMe SSD Controller 512GB                | 8         | 0.35%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 8         | 0.35%   |
| Sandisk WD Black SN850 500GB                         | 8         | 0.35%   |
| Samsung SSD 970 EVO Plus 1TB                         | 8         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 185       | 236    | 38.95%  |
| WDC                 | 151       | 235    | 31.79%  |
| Toshiba             | 67        | 76     | 14.11%  |
| HGST                | 25        | 39     | 5.26%   |
| Hitachi             | 21        | 25     | 4.42%   |
| Samsung Electronics | 9         | 12     | 1.89%   |
| Unknown             | 5         | 6      | 1.05%   |
| SABRENT             | 3         | 3      | 0.63%   |
| USB3.0              | 1         | 1      | 0.21%   |
| Maxtor              | 1         | 1      | 0.21%   |
| JMicron Technology  | 1         | 3      | 0.21%   |
| Intenso             | 1         | 1      | 0.21%   |
| Inateck             | 1         | 1      | 0.21%   |
| HGST HTS            | 1         | 1      | 0.21%   |
| External            | 1         | 1      | 0.21%   |
| ASMT                | 1         | 2      | 0.21%   |
| Apple               | 1         | 1      | 0.21%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 152       | 203    | 25.98%  |
| Kingston            | 81        | 93     | 13.85%  |
| Crucial             | 76        | 89     | 12.99%  |
| SanDisk             | 48        | 52     | 8.21%   |
| WDC                 | 37        | 42     | 6.32%   |
| China               | 20        | 23     | 3.42%   |
| Micron Technology   | 13        | 13     | 2.22%   |
| SK hynix            | 12        | 12     | 2.05%   |
| Intel               | 12        | 14     | 2.05%   |
| PNY                 | 10        | 10     | 1.71%   |
| Toshiba             | 9         | 10     | 1.54%   |
| A-DATA Technology   | 9         | 9      | 1.54%   |
| LITEON              | 8         | 8      | 1.37%   |
| Apple               | 8         | 9      | 1.37%   |
| Apacer              | 8         | 10     | 1.37%   |
| SPCC                | 7         | 9      | 1.2%    |
| Netac               | 6         | 8      | 1.03%   |
| Lexar               | 5         | 6      | 0.85%   |
| Intenso             | 4         | 4      | 0.68%   |
| Transcend           | 3         | 3      | 0.51%   |
| Plextor             | 3         | 3      | 0.51%   |
| Patriot             | 3         | 3      | 0.51%   |
| GOODRAM             | 3         | 5      | 0.51%   |
| Gigabyte Technology | 3         | 4      | 0.51%   |
| Corsair             | 3         | 4      | 0.51%   |
| Unknown             | 2         | 2      | 0.34%   |
| Team                | 2         | 3      | 0.34%   |
| OCZ                 | 2         | 2      | 0.34%   |
| LT                  | 2         | 2      | 0.34%   |
| LITEONIT            | 2         | 2      | 0.34%   |
| KingSpec            | 2         | 2      | 0.34%   |
| FORESEE             | 2         | 2      | 0.34%   |
| Unknown             | 2         | 2      | 0.34%   |
| XSTAR               | 1         | 1      | 0.17%   |
| XrayDisk            | 1         | 1      | 0.17%   |
| WDC WDS             | 1         | 1      | 0.17%   |
| VSP                 | 1         | 1      | 0.17%   |
| Teclast             | 1         | 2      | 0.17%   |
| Super Talent        | 1         | 1      | 0.17%   |
| SCY                 | 1         | 1      | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 916       | 1185   | 47.76%  |
| SSD     | 519       | 692    | 27.06%  |
| HDD     | 398       | 644    | 20.75%  |
| MMC     | 55        | 64     | 2.87%   |
| Unknown | 30        | 34     | 1.56%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 915       | 1181   | 52.23%  |
| SATA | 714       | 1285   | 40.75%  |
| SAS  | 68        | 89     | 3.88%   |
| MMC  | 55        | 64     | 3.14%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 488       | 660    | 50.47%  |
| 0.51-1.0   | 300       | 393    | 31.02%  |
| 1.01-2.0   | 96        | 126    | 9.93%   |
| 3.01-4.0   | 32        | 55     | 3.31%   |
| 4.01-10.0  | 28        | 44     | 2.9%    |
| 2.01-3.0   | 21        | 40     | 2.17%   |
| 10.01-20.0 | 2         | 18     | 0.21%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 307       | 21.26%  |
| 251-500        | 277       | 19.18%  |
| 1001-2000      | 207       | 14.34%  |
| 1-20           | 160       | 11.08%  |
| 101-250        | 152       | 10.53%  |
| Unknown        | 121       | 8.38%   |
| More than 3000 | 104       | 7.2%    |
| 2001-3000      | 62        | 4.29%   |
| 51-100         | 33        | 2.29%   |
| 21-50          | 21        | 1.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 392       | 26.59%  |
| 21-50          | 216       | 14.65%  |
| 101-250        | 210       | 14.25%  |
| 51-100         | 156       | 10.58%  |
| 251-500        | 138       | 9.36%   |
| 501-1000       | 129       | 8.75%   |
| Unknown        | 121       | 8.21%   |
| 1001-2000      | 66        | 4.48%   |
| More than 3000 | 29        | 1.97%   |
| 2001-3000      | 17        | 1.15%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 870 EVO 1TB   | 3         | 3      | 3.23%   |
| Samsung Electronics SSD 870 EVO 500GB | 2         | 3      | 2.15%   |
| Intel SSDSC2CT120A3 120GB             | 2         | 4      | 2.15%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD      | 1         | 1      | 1.08%   |
| WDC WD50EFRX-68MYMN1 5TB              | 1         | 4      | 1.08%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 1         | 1      | 1.08%   |
| WDC WD5000AVVS-63H0B1 500GB           | 1         | 1      | 1.08%   |
| WDC WD5000AAKX-60U6AA0 500GB          | 1         | 1      | 1.08%   |
| WDC WD5000AAKX-603CA0 500GB           | 1         | 1      | 1.08%   |
| WDC WD5000AAKX-00ERMA0 500GB          | 1         | 1      | 1.08%   |
| WDC WD40PURZ-85AKKY0 4TB              | 1         | 1      | 1.08%   |
| WDC WD40EZRZ-00WN9B0 4TB              | 1         | 1      | 1.08%   |
| WDC WD3200BPVT-80JJ5T0 320GB          | 1         | 1      | 1.08%   |
| WDC WD3200AAKS-00V1A0 320GB           | 1         | 1      | 1.08%   |
| WDC WD3200AAKS-00UU3A0 320GB          | 1         | 1      | 1.08%   |
| WDC WD30EFRX-68AX9N0 3TB              | 1         | 1      | 1.08%   |
| WDC WD2500BEVT-80A23T0 250GB          | 1         | 1      | 1.08%   |
| WDC WD20EZRX-22D8PB0 2TB              | 1         | 1      | 1.08%   |
| WDC WD20EZRX-00D8PB0 2TB              | 1         | 1      | 1.08%   |
| WDC WD15EARS-00MVWB0 1TB              | 1         | 1      | 1.08%   |
| WDC WD140EDFZ-11A0VA0 14TB            | 1         | 2      | 1.08%   |
| WDC WD10JPVX-60JC3T1 1TB              | 1         | 1      | 1.08%   |
| WDC WD10EZEX-60WN4A0 1TB              | 1         | 2      | 1.08%   |
| WDC WD10EZEX-08WN4A0 1TB              | 1         | 1      | 1.08%   |
| WDC WD10EZEX-00WN4A0 1TB              | 1         | 1      | 1.08%   |
| WDC WD10EFRX-68FYTN0 1TB              | 1         | 1      | 1.08%   |
| WDC WD1002FAEX-00Y9A0 1TB             | 1         | 1      | 1.08%   |
| Toshiba MQ01ABD075 752GB              | 1         | 1      | 1.08%   |
| Toshiba MK7559GSXP 752GB              | 1         | 1      | 1.08%   |
| Toshiba MK5061GSY 500GB               | 1         | 1      | 1.08%   |
| Toshiba MK3265GSX 320GB               | 1         | 1      | 1.08%   |
| Toshiba MK3263GSX 320GB               | 1         | 1      | 1.08%   |
| Toshiba MK1237GSX 120GB               | 1         | 1      | 1.08%   |
| Toshiba KBG30ZMS512G NVMe 512GB       | 1         | 1      | 1.08%   |
| SPCC SPCCSolidStateDisk 128GB SSD     | 1         | 1      | 1.08%   |
| SK hynix HFS256G39TND-N210A 256GB SSD | 1         | 1      | 1.08%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 1         | 1      | 1.08%   |
| SK hynix BC711 HFM512GD3JX013N 512GB  | 1         | 1      | 1.08%   |
| Seagate ST9500325AS 500GB             | 1         | 1      | 1.08%   |
| Seagate ST9320325AS 320GB             | 1         | 1      | 1.08%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 24        | 29     | 27.27%  |
| WDC                 | 22        | 29     | 25%     |
| Samsung Electronics | 11        | 16     | 12.5%   |
| Toshiba             | 7         | 7      | 7.95%   |
| SK hynix            | 3         | 3      | 3.41%   |
| Intel               | 3         | 5      | 3.41%   |
| Crucial             | 3         | 3      | 3.41%   |
| Micron Technology   | 2         | 2      | 2.27%   |
| HGST                | 2         | 2      | 2.27%   |
| SPCC                | 1         | 1      | 1.14%   |
| SanDisk             | 1         | 1      | 1.14%   |
| Maxtor              | 1         | 1      | 1.14%   |
| Kingston            | 1         | 1      | 1.14%   |
| Hitachi             | 1         | 1      | 1.14%   |
| HGST HTS            | 1         | 1      | 1.14%   |
| Corsair             | 1         | 1      | 1.14%   |
| Apple               | 1         | 1      | 1.14%   |
| AMD                 | 1         | 2      | 1.14%   |
| A-DATA Technology   | 1         | 1      | 1.14%   |
| Unknown             | 1         | 1      | 1.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 24        | 29     | 39.34%  |
| WDC                 | 21        | 28     | 34.43%  |
| Toshiba             | 6         | 6      | 9.84%   |
| Samsung Electronics | 5         | 8      | 8.2%    |
| HGST                | 2         | 2      | 3.28%   |
| Maxtor              | 1         | 1      | 1.64%   |
| Hitachi             | 1         | 1      | 1.64%   |
| HGST HTS            | 1         | 1      | 1.64%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 56        | 76     | 67.47%  |
| SSD  | 22        | 27     | 26.51%  |
| NVMe | 5         | 5      | 6.02%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| SPCC M.2 PCIe SSD 2TB                            | 1         | 1      | 25%     |
| Seagate ST31000528AS 1TB                         | 1         | 1      | 25%     |
| Samsung Electronics SSD 980 1TB                  | 1         | 1      | 25%     |
| Samsung Electronics MZNTY128HDHP-00000 128GB SSD | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 2      | 50%     |
| SPCC                | 1         | 1      | 25%     |
| Seagate             | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 822       | 1491   | 53.55%  |
| Works    | 629       | 1016   | 40.98%  |
| Malfunc  | 80        | 108    | 5.21%   |
| Failed   | 4         | 4      | 0.26%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 753       | 36.77%  |
| Samsung Electronics            | 347       | 16.94%  |
| AMD                            | 305       | 14.89%  |
| SanDisk                        | 166       | 8.11%   |
| SK hynix                       | 84        | 4.1%    |
| Micron Technology              | 51        | 2.49%   |
| Kingston Technology Company    | 50        | 2.44%   |
| Phison Electronics             | 44        | 2.15%   |
| KIOXIA                         | 35        | 1.71%   |
| Toshiba America Info Systems   | 34        | 1.66%   |
| Micron/Crucial Technology      | 31        | 1.51%   |
| ASMedia Technology             | 30        | 1.46%   |
| ADATA Technology               | 22        | 1.07%   |
| Silicon Motion                 | 13        | 0.63%   |
| Marvell Technology Group       | 12        | 0.59%   |
| Realtek Semiconductor          | 10        | 0.49%   |
| Union Memory (Shenzhen)        | 9         | 0.44%   |
| Solid State Storage Technology | 6         | 0.29%   |
| Lite-On Technology             | 6         | 0.29%   |
| Shenzhen Longsys Electronics   | 5         | 0.24%   |
| Yangtze Memory Technologies    | 4         | 0.2%    |
| Lenovo                         | 4         | 0.2%    |
| Nvidia                         | 3         | 0.15%   |
| MAXIO Technology (Hangzhou)    | 3         | 0.15%   |
| JMicron Technology             | 3         | 0.15%   |
| Broadcom / LSI                 | 3         | 0.15%   |
| Biwin Storage Technology       | 3         | 0.15%   |
| Apple                          | 3         | 0.15%   |
| VIA Technologies               | 2         | 0.1%    |
| Netac Technology               | 2         | 0.1%    |
| LSI Logic / Symbios Logic      | 2         | 0.1%    |
| Transcend                      | 1         | 0.05%   |
| Solidigm                       | 1         | 0.05%   |
| Seagate Technology             | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 199       | 8.93%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 151       | 6.78%   |
| Intel Volume Management Device NVMe RAID Controller                            | 98        | 4.4%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 91        | 4.08%   |
| Samsung NVMe SSD Controller 980                                                | 79        | 3.55%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 77        | 3.46%   |
| Micron Non-Volatile memory controller                                          | 51        | 2.29%   |
| Sandisk Non-Volatile memory controller                                         | 48        | 2.15%   |
| AMD 400 Series Chipset SATA Controller                                         | 45        | 2.02%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 44        | 1.97%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 44        | 1.97%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 43        | 1.93%   |
| AMD 500 Series Chipset SATA Controller                                         | 37        | 1.66%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 33        | 1.48%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 32        | 1.44%   |
| Intel Non-Volatile memory controller                                           | 32        | 1.44%   |
| Kingston Company Company Non-Volatile memory controller                        | 30        | 1.35%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 30        | 1.35%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 29        | 1.3%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 29        | 1.3%    |
| Intel Tiger Lake-LP SATA Controller                                            | 27        | 1.21%   |
| Intel Comet Lake SATA AHCI Controller                                          | 26        | 1.17%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 25        | 1.12%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 24        | 1.08%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 22        | 0.99%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 22        | 0.99%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 22        | 0.99%   |
| AMD SATA controller                                                            | 22        | 0.99%   |
| Phison E12 NVMe Controller                                                     | 21        | 0.94%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 21        | 0.94%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 20        | 0.9%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 19        | 0.85%   |
| Intel SSD 660P Series                                                          | 19        | 0.85%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 18        | 0.81%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 18        | 0.81%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 18        | 0.81%   |
| Intel SATA Controller [RAID mode]                                              | 17        | 0.76%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 17        | 0.76%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 16        | 0.72%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 16        | 0.72%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 912       | 45.06%  |
| SATA | 879       | 43.43%  |
| RAID | 169       | 8.35%   |
| IDE  | 56        | 2.77%   |
| SAS  | 7         | 0.35%   |
| SCSI | 1         | 0.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 967       | 67.86%  |
| AMD     | 451       | 31.65%  |
| ARM     | 6         | 0.42%   |
| Unknown | 1         | 0.07%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 41        | 2.88%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 26        | 1.82%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 22        | 1.54%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 20        | 1.4%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 19        | 1.33%   |
| AMD Ryzen 5 3600 6-Core Processor             | 19        | 1.33%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 17        | 1.19%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 17        | 1.19%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 17        | 1.19%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 17        | 1.19%   |
| Intel 12th Gen Core i7-12700H                 | 17        | 1.19%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 17        | 1.19%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 15        | 1.05%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 14        | 0.98%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 14        | 0.98%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 13        | 0.91%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 13        | 0.91%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 12        | 0.84%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 12        | 0.84%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 12        | 0.84%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 11        | 0.77%   |
| Intel 12th Gen Core i7-1260P                  | 11        | 0.77%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 11        | 0.77%   |
| AMD Ryzen 9 7950X 16-Core Processor           | 11        | 0.77%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 11        | 0.77%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 10        | 0.7%    |
| Intel 12th Gen Core i5-1240P                  | 10        | 0.7%    |
| AMD Ryzen 7 5700G with Radeon Graphics        | 10        | 0.7%    |
| AMD Ryzen 5 5600G with Radeon Graphics        | 10        | 0.7%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 9         | 0.63%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 9         | 0.63%   |
| Intel 12th Gen Core i9-12900H                 | 9         | 0.63%   |
| Intel 12th Gen Core i5-1235U                  | 9         | 0.63%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 9         | 0.63%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 9         | 0.63%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 9         | 0.63%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 8         | 0.56%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 8         | 0.56%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 8         | 0.56%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 8         | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i7                        | 268       | 18.81%  |
| Intel Core i5                        | 259       | 18.18%  |
| Other                                | 254       | 17.82%  |
| AMD Ryzen 5                          | 150       | 10.53%  |
| AMD Ryzen 7                          | 137       | 9.61%   |
| Intel Core i3                        | 65        | 4.56%   |
| AMD Ryzen 9                          | 59        | 4.14%   |
| Intel Celeron                        | 30        | 2.11%   |
| Intel Xeon                           | 21        | 1.47%   |
| AMD Ryzen 7 PRO                      | 19        | 1.33%   |
| AMD Ryzen 3                          | 18        | 1.26%   |
| Intel Pentium                        | 16        | 1.12%   |
| Intel Core 2 Duo                     | 14        | 0.98%   |
| AMD Ryzen 5 PRO                      | 14        | 0.98%   |
| Intel Core i9                        | 12        | 0.84%   |
| Intel Atom                           | 12        | 0.84%   |
| AMD FX                               | 10        | 0.7%    |
| AMD A6                               | 8         | 0.56%   |
| AMD A4                               | 7         | 0.49%   |
| Intel Pentium Dual-Core              | 6         | 0.42%   |
| Intel Core 2 Quad                    | 6         | 0.42%   |
| AMD A8                               | 5         | 0.35%   |
| Intel Pentium Silver                 | 4         | 0.28%   |
| AMD A10                              | 4         | 0.28%   |
| AMD Ryzen Threadripper               | 3         | 0.21%   |
| AMD Phenom II X6                     | 3         | 0.21%   |
| Intel Pentium Gold                   | 2         | 0.14%   |
| Intel Genuine                        | 2         | 0.14%   |
| Intel Core m3                        | 2         | 0.14%   |
| AMD Phenom II X4                     | 2         | 0.14%   |
| AMD A12                              | 2         | 0.14%   |
| Intel Pentium Dual                   | 1         | 0.07%   |
| Intel Core m5                        | 1         | 0.07%   |
| Intel Core 2                         | 1         | 0.07%   |
| AMD Turion X2 Ultra Dual-Core Mobile | 1         | 0.07%   |
| AMD Ryzen 3 PRO                      | 1         | 0.07%   |
| AMD PRO A10                          | 1         | 0.07%   |
| AMD Phenom II X2                     | 1         | 0.07%   |
| AMD E1                               | 1         | 0.07%   |
| AMD E                                | 1         | 0.07%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 501       | 35.16%  |
| 2       | 315       | 22.11%  |
| 8       | 222       | 15.58%  |
| 6       | 218       | 15.3%   |
| 12      | 58        | 4.07%   |
| 14      | 33        | 2.32%   |
| 16      | 31        | 2.18%   |
| 10      | 30        | 2.11%   |
| 24      | 4         | 0.28%   |
| 3       | 4         | 0.28%   |
| 1       | 4         | 0.28%   |
| Unknown | 2         | 0.14%   |
| 36      | 1         | 0.07%   |
| 32      | 1         | 0.07%   |
| 5       | 1         | 0.07%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1415      | 99.3%   |
| 2       | 8         | 0.56%   |
| Unknown | 2         | 0.14%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1210      | 84.85%  |
| 1       | 214       | 15.01%  |
| Unknown | 2         | 0.14%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1420      | 99.65%  |
| 64-bit         | 5         | 0.35%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x806c1    | 84        | 5.86%   |
| Unknown    | 75        | 5.23%   |
| 0x306a9    | 68        | 4.74%   |
| 0x906a3    | 64        | 4.46%   |
| 0x806ec    | 62        | 4.32%   |
| 0x0a50000c | 61        | 4.25%   |
| 0x806ea    | 60        | 4.18%   |
| 0x906ea    | 52        | 3.63%   |
| 0x08701021 | 42        | 2.93%   |
| 0x806e9    | 39        | 2.72%   |
| 0x306c3    | 38        | 2.65%   |
| 0x406e3    | 36        | 2.51%   |
| 0x506e3    | 33        | 2.3%    |
| 0x206a7    | 33        | 2.3%    |
| 0x08600106 | 31        | 2.16%   |
| 0xa0652    | 26        | 1.81%   |
| 0x08608103 | 26        | 1.81%   |
| 0x906e9    | 23        | 1.6%    |
| 0x906a4    | 23        | 1.6%    |
| 0x306d4    | 22        | 1.53%   |
| 0x806d1    | 21        | 1.46%   |
| 0x0a404102 | 21        | 1.46%   |
| 0x08108109 | 21        | 1.46%   |
| 0x0a50000d | 20        | 1.39%   |
| 0x90672    | 18        | 1.26%   |
| 0x40651    | 18        | 1.26%   |
| 0x1067a    | 17        | 1.19%   |
| 0x0a601203 | 17        | 1.19%   |
| 0x706e5    | 16        | 1.12%   |
| 0x0a201016 | 16        | 1.12%   |
| 0x806eb    | 15        | 1.05%   |
| 0x906ed    | 14        | 0.98%   |
| 0x0a404101 | 13        | 0.91%   |
| 0x08600104 | 13        | 0.91%   |
| 0x706a8    | 12        | 0.84%   |
| 0x0a20120a | 12        | 0.84%   |
| 0x0810100b | 11        | 0.77%   |
| 0x806c2    | 10        | 0.7%    |
| 0x206d7    | 10        | 0.7%    |
| 0x30678    | 9         | 0.63%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 288       | 20.21%  |
| Zen 3            | 137       | 9.61%   |
| Alderlake Hybrid | 113       | 7.93%   |
| Zen 2            | 106       | 7.44%   |
| Unknown          | 106       | 7.44%   |
| TigerLake        | 101       | 7.09%   |
| Skylake          | 73        | 5.12%   |
| IvyBridge        | 69        | 4.84%   |
| Haswell          | 64        | 4.49%   |
| Icelake          | 45        | 3.16%   |
| CometLake        | 44        | 3.09%   |
| SandyBridge      | 43        | 3.02%   |
| Zen+             | 36        | 2.53%   |
| Zen              | 30        | 2.11%   |
| Broadwell        | 24        | 1.68%   |
| Penryn           | 21        | 1.47%   |
| Silvermont       | 19        | 1.33%   |
| Westmere         | 14        | 0.98%   |
| Goldmont plus    | 14        | 0.98%   |
| Excavator        | 14        | 0.98%   |
| Piledriver       | 13        | 0.91%   |
| Core             | 10        | 0.7%    |
| K10              | 7         | 0.49%   |
| Tremont          | 6         | 0.42%   |
| Goldmont         | 5         | 0.35%   |
| Steamroller      | 4         | 0.28%   |
| Nehalem          | 4         | 0.28%   |
| Jaguar           | 4         | 0.28%   |
| Bonnell          | 4         | 0.28%   |
| K10 Llano        | 2         | 0.14%   |
| Bulldozer        | 2         | 0.14%   |
| Puma             | 1         | 0.07%   |
| K8 & K10 hybrid  | 1         | 0.07%   |
| Bobcat           | 1         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 793       | 45.19%  |
| Nvidia            | 494       | 28.15%  |
| AMD               | 463       | 26.38%  |
| ASPEED Technology | 5         | 0.28%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 88        | 4.88%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 71        | 3.94%   |
| Intel Alder Lake-P Integrated Graphics Controller                         | 61        | 3.39%   |
| Intel UHD Graphics 620                                                    | 54        | 3%      |
| AMD Renoir                                                                | 51        | 2.83%   |
| Intel HD Graphics 620                                                     | 41        | 2.28%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 40        | 2.22%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 40        | 2.22%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 39        | 2.16%   |
| AMD Lucienne                                                              | 36        | 2%      |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 35        | 1.94%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                   | 35        | 1.94%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 34        | 1.89%   |
| AMD Rembrandt [Radeon 680M]                                               | 34        | 1.89%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 27        | 1.5%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 25        | 1.39%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 25        | 1.39%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                | 24        | 1.33%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 23        | 1.28%   |
| AMD Raphael                                                               | 21        | 1.17%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 20        | 1.11%   |
| Intel HD Graphics 630                                                     | 20        | 1.11%   |
| Intel HD Graphics 5500                                                    | 20        | 1.11%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]             | 20        | 1.11%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                               | 19        | 1.05%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 19        | 1.05%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 18        | 1%      |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 17        | 0.94%   |
| Intel HD Graphics 530                                                     | 17        | 0.94%   |
| Nvidia GP108M [GeForce MX150]                                             | 16        | 0.89%   |
| AMD Barcelo                                                               | 16        | 0.89%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 13        | 0.72%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 13        | 0.72%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 12        | 0.67%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 12        | 0.67%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                | 12        | 0.67%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 12        | 0.67%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 12        | 0.67%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                        | 11        | 0.61%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                 | 11        | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 511       | 35.81%  |
| 1 x AMD                 | 351       | 24.6%   |
| Intel + Nvidia          | 239       | 16.75%  |
| 1 x Nvidia              | 192       | 13.45%  |
| AMD + Nvidia            | 55        | 3.85%   |
| 2 x AMD                 | 33        | 2.31%   |
| Intel + AMD             | 23        | 1.61%   |
| 2 x Intel               | 8         | 0.56%   |
| Other                   | 7         | 0.49%   |
| 2 x Nvidia              | 2         | 0.14%   |
| 1 x ASPEED              | 2         | 0.14%   |
| 2 x Nvidia + 1 x ASPEED | 1         | 0.07%   |
| Nvidia + ASPEED         | 1         | 0.07%   |
| Intel + 2 x Nvidia      | 1         | 0.07%   |
| AMD + ASPEED            | 1         | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1114      | 77.85%  |
| Proprietary | 274       | 19.15%  |
| Unknown     | 43        | 3%      |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 754       | 52.32%  |
| 0.01-0.5   | 168       | 11.66%  |
| 1.01-2.0   | 139       | 9.65%   |
| 3.01-4.0   | 105       | 7.29%   |
| 7.01-8.0   | 104       | 7.22%   |
| 0.51-1.0   | 77        | 5.34%   |
| 8.01-16.0  | 42        | 2.91%   |
| 5.01-6.0   | 38        | 2.64%   |
| 2.01-3.0   | 8         | 0.56%   |
| 16.01-24.0 | 6         | 0.42%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 210       | 12.61%  |
| AU Optronics            | 205       | 12.3%   |
| Chimei Innolux          | 162       | 9.72%   |
| Samsung Electronics     | 153       | 9.18%   |
| LG Display              | 130       | 7.8%    |
| Dell                    | 116       | 6.96%   |
| Goldstar                | 89        | 5.34%   |
| Hewlett-Packard         | 54        | 3.24%   |
| Acer                    | 49        | 2.94%   |
| AOC                     | 47        | 2.82%   |
| Sharp                   | 40        | 2.4%    |
| Lenovo                  | 35        | 2.1%    |
| BenQ                    | 35        | 2.1%    |
| Philips                 | 27        | 1.62%   |
| CSO                     | 25        | 1.5%    |
| ASUSTek Computer        | 24        | 1.44%   |
| PANDA                   | 23        | 1.38%   |
| Ancor Communications    | 20        | 1.2%    |
| Apple                   | 17        | 1.02%   |
| InfoVision              | 16        | 0.96%   |
| ViewSonic               | 13        | 0.78%   |
| Iiyama                  | 11        | 0.66%   |
| Gigabyte Technology     | 11        | 0.66%   |
| Sceptre Tech            | 9         | 0.54%   |
| MSI                     | 9         | 0.54%   |
| Mi                      | 9         | 0.54%   |
| Sony                    | 7         | 0.42%   |
| JDI                     | 7         | 0.42%   |
| Panasonic               | 6         | 0.36%   |
| Eizo                    | 6         | 0.36%   |
| Chi Mei Optoelectronics | 6         | 0.36%   |
| Toshiba                 | 5         | 0.3%    |
| NEC Computers           | 5         | 0.3%    |
| Unknown                 | 4         | 0.24%   |
| TMX                     | 4         | 0.24%   |
| Pixio                   | 4         | 0.24%   |
| Vizio                   | 3         | 0.18%   |
| ONN                     | 3         | 0.18%   |
| HUAWEI                  | 3         | 0.18%   |
| HannStar                | 3         | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 14        | 0.81%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 13        | 0.75%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 13        | 0.75%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 10        | 0.58%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 10        | 0.58%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 9         | 0.52%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 8         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 8         | 0.46%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch              | 7         | 0.41%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                      | 7         | 0.41%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 6         | 0.35%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 6         | 0.35%   |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch      | 6         | 0.35%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 6         | 0.35%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 6         | 0.35%   |
| Samsung Electronics LCD Monitor SDC416D 2880x1800 312x195mm 14.5-inch | 5         | 0.29%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 5         | 0.29%   |
| Lenovo LEN L28u-30 LEN65FA 3840x2160 621x341mm 27.9-inch              | 5         | 0.29%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 5         | 0.29%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 5         | 0.29%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 5         | 0.29%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 5         | 0.29%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                 | 5         | 0.29%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch        | 5         | 0.29%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch        | 5         | 0.29%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 5         | 0.29%   |
| AOC 24B2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                    | 5         | 0.29%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 4         | 0.23%   |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                      | 4         | 0.23%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch          | 4         | 0.23%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 4         | 0.23%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 4         | 0.23%   |
| JDI LCD Monitor JDI422A 3000x2000 293x196mm 13.9-inch                 | 4         | 0.23%   |
| Dell U2515H DELD06F 2560x1440 553x311mm 25.0-inch                     | 4         | 0.23%   |
| CSO LCD Monitor CSO160A 2560x1600 345x215mm 16.0-inch                 | 4         | 0.23%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 4         | 0.23%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch      | 4         | 0.23%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch      | 4         | 0.23%   |
| BOE LCD Monitor BOE092F 2520x1680 338x226mm 16.0-inch                 | 4         | 0.23%   |
| BOE LCD Monitor BOE08D5 1920x1080 344x194mm 15.5-inch                 | 4         | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 768       | 49.01%  |
| 1366x768 (WXGA)    | 149       | 9.51%   |
| 3840x2160 (4K)     | 137       | 8.74%   |
| 2560x1440 (QHD)    | 132       | 8.42%   |
| 1920x1200 (WUXGA)  | 54        | 3.45%   |
| 2560x1600          | 45        | 2.87%   |
| 3440x1440          | 43        | 2.74%   |
| 1600x900 (HD+)     | 37        | 2.36%   |
| 2880x1800          | 27        | 1.72%   |
| 1280x1024 (SXGA)   | 23        | 1.47%   |
| 1680x1050 (WSXGA+) | 18        | 1.15%   |
| 2560x1080          | 17        | 1.08%   |
| 1440x900 (WXGA+)   | 12        | 0.77%   |
| 3840x2400          | 9         | 0.57%   |
| 1280x800 (WXGA)    | 9         | 0.57%   |
| 3000x2000          | 7         | 0.45%   |
| 2160x1440          | 7         | 0.45%   |
| 1360x768           | 7         | 0.45%   |
| 3840x1080          | 6         | 0.38%   |
| 2256x1504          | 6         | 0.38%   |
| 3456x2160          | 4         | 0.26%   |
| 2736x1824          | 4         | 0.26%   |
| 2520x1680          | 4         | 0.26%   |
| 2288x1287          | 4         | 0.26%   |
| 1600x1200          | 4         | 0.26%   |
| 3072x1920          | 3         | 0.19%   |
| 1920x1280          | 3         | 0.19%   |
| Unknown            | 3         | 0.19%   |
| 3200x2000          | 2         | 0.13%   |
| 2880x1620          | 2         | 0.13%   |
| 2240x1400          | 2         | 0.13%   |
| 2160x1350          | 2         | 0.13%   |
| 1024x768 (XGA)     | 2         | 0.13%   |
| 800x1280           | 1         | 0.06%   |
| 4160x1440          | 1         | 0.06%   |
| 3840x1600          | 1         | 0.06%   |
| 3200x1800 (QHD+)   | 1         | 0.06%   |
| 3120x1600          | 1         | 0.06%   |
| 2880x864           | 1         | 0.06%   |
| 2560x2880          | 1         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 431       | 25.64%  |
| 13      | 195       | 11.6%   |
| 27      | 174       | 10.35%  |
| 14      | 172       | 10.23%  |
| 24      | 122       | 7.26%   |
| 23      | 88        | 5.23%   |
| 21      | 61        | 3.63%   |
| 31      | 58        | 3.45%   |
| 17      | 52        | 3.09%   |
| 34      | 49        | 2.91%   |
| 16      | 44        | 2.62%   |
| 12      | 24        | 1.43%   |
| 19      | 21        | 1.25%   |
| Unknown | 20        | 1.19%   |
| 20      | 16        | 0.95%   |
| 18      | 16        | 0.95%   |
| 25      | 13        | 0.77%   |
| 32      | 12        | 0.71%   |
| 22      | 12        | 0.71%   |
| 11      | 12        | 0.71%   |
| 40      | 10        | 0.59%   |
| 26      | 10        | 0.59%   |
| 84      | 9         | 0.54%   |
| 72      | 6         | 0.36%   |
| 48      | 6         | 0.36%   |
| 29      | 6         | 0.36%   |
| 28      | 5         | 0.3%    |
| 142     | 4         | 0.24%   |
| 54      | 4         | 0.24%   |
| 10      | 4         | 0.24%   |
| 39      | 3         | 0.18%   |
| 35      | 3         | 0.18%   |
| 52      | 2         | 0.12%   |
| 43      | 2         | 0.12%   |
| 42      | 2         | 0.12%   |
| 38      | 2         | 0.12%   |
| 36      | 2         | 0.12%   |
| 33      | 2         | 0.12%   |
| 69      | 1         | 0.06%   |
| 65      | 1         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 726       | 44.27%  |
| 501-600        | 352       | 21.46%  |
| 201-300        | 144       | 8.78%   |
| 401-500        | 110       | 6.71%   |
| 601-700        | 88        | 5.37%   |
| 351-400        | 75        | 4.57%   |
| 701-800        | 64        | 3.9%    |
| Unknown        | 20        | 1.22%   |
| 801-900        | 18        | 1.1%    |
| 1501-2000      | 16        | 0.98%   |
| 1001-1500      | 15        | 0.91%   |
| 901-1000       | 7         | 0.43%   |
| More than 2000 | 4         | 0.24%   |
| 1-100          | 1         | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1123      | 77.24%  |
| 16/10   | 186       | 12.79%  |
| 21/9    | 57        | 3.92%   |
| 3/2     | 35        | 2.41%   |
| 5/4     | 18        | 1.24%   |
| 4/3     | 13        | 0.89%   |
| Unknown | 10        | 0.69%   |
| 32/9    | 5         | 0.34%   |
| 1.00    | 4         | 0.28%   |
| 3.33    | 1         | 0.07%   |
| 0.89    | 1         | 0.07%   |
| 0.67    | 1         | 0.07%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 433       | 25.88%  |
| 81-90          | 277       | 16.56%  |
| 201-250        | 220       | 13.15%  |
| 301-350        | 181       | 10.82%  |
| 351-500        | 130       | 7.77%   |
| 71-80          | 87        | 5.2%    |
| 151-200        | 63        | 3.77%   |
| 251-300        | 55        | 3.29%   |
| 121-130        | 45        | 2.69%   |
| 111-120        | 40        | 2.39%   |
| More than 1000 | 29        | 1.73%   |
| 501-1000       | 29        | 1.73%   |
| Unknown        | 20        | 1.2%    |
| 61-70          | 19        | 1.14%   |
| 141-150        | 15        | 0.9%    |
| 51-60          | 14        | 0.84%   |
| 91-100         | 10        | 0.6%    |
| 131-140        | 3         | 0.18%   |
| 41-50          | 2         | 0.12%   |
| 1-40           | 1         | 0.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 561       | 34.98%  |
| 51-100        | 406       | 25.31%  |
| 101-120       | 303       | 18.89%  |
| 161-240       | 210       | 13.09%  |
| More than 240 | 79        | 4.93%   |
| 1-50          | 25        | 1.56%   |
| Unknown       | 20        | 1.25%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1066      | 73.82%  |
| 2     | 290       | 20.08%  |
| 0     | 48        | 3.32%   |
| 3     | 33        | 2.29%   |
| 4     | 6         | 0.42%   |
| 5     | 1         | 0.07%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 856       | 41.45%  |
| Realtek Semiconductor                  | 711       | 34.43%  |
| Qualcomm Atheros                       | 150       | 7.26%   |
| MediaTek                               | 96        | 4.65%   |
| Broadcom                               | 61        | 2.95%   |
| TP-Link                                | 22        | 1.07%   |
| Qualcomm                               | 13        | 0.63%   |
| Lenovo                                 | 11        | 0.53%   |
| Aquantia                               | 11        | 0.53%   |
| Ralink Technology                      | 10        | 0.48%   |
| Ralink                                 | 10        | 0.48%   |
| Broadcom Limited                       | 10        | 0.48%   |
| Sierra Wireless                        | 9         | 0.44%   |
| ASIX Electronics                       | 8         | 0.39%   |
| Samsung Electronics                    | 7         | 0.34%   |
| Microsoft                              | 7         | 0.34%   |
| Google                                 | 7         | 0.34%   |
| D-Link                                 | 7         | 0.34%   |
| Xiaomi                                 | 6         | 0.29%   |
| Marvell Technology Group               | 6         | 0.29%   |
| Hewlett-Packard                        | 5         | 0.24%   |
| Dell                                   | 4         | 0.19%   |
| ASUSTek Computer                       | 4         | 0.19%   |
| Fibocom                                | 3         | 0.15%   |
| Ericsson Business Mobile Networks      | 3         | 0.15%   |
| DisplayLink                            | 3         | 0.15%   |
| Nvidia                                 | 2         | 0.1%    |
| Huawei Technologies                    | 2         | 0.1%    |
| Apple                                  | 2         | 0.1%    |
| Sony Ericsson Mobile Communications AB | 1         | 0.05%   |
| Qualcomm Atheros Communications        | 1         | 0.05%   |
| QinHeng Electronics                    | 1         | 0.05%   |
| OPPO                                   | 1         | 0.05%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.05%   |
| NetGear                                | 1         | 0.05%   |
| Motorola PCS                           | 1         | 0.05%   |
| Microchip Technology                   | 1         | 0.05%   |
| Mellanox Technologies                  | 1         | 0.05%   |
| Linksys                                | 1         | 0.05%   |
| JMicron Technology                     | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 446       | 18.31%  |
| Intel Wi-Fi 6 AX200                                               | 114       | 4.68%   |
| Intel Wi-Fi 6 AX201                                               | 84        | 3.45%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 77        | 3.16%   |
| Realtek RTL8125 2.5GbE Controller                                 | 63        | 2.59%   |
| Intel Wireless 8265 / 8275                                        | 63        | 2.59%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 55        | 2.26%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 52        | 2.13%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 51        | 2.09%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 45        | 1.85%   |
| Intel I211 Gigabit Network Connection                             | 41        | 1.68%   |
| Intel Ethernet Controller I225-V                                  | 38        | 1.56%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 37        | 1.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 35        | 1.44%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 34        | 1.4%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 33        | 1.35%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 30        | 1.23%   |
| Intel Wireless 8260                                               | 29        | 1.19%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 29        | 1.19%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 28        | 1.15%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 26        | 1.07%   |
| Intel Ethernet Connection (4) I219-LM                             | 24        | 0.99%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 23        | 0.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 23        | 0.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 23        | 0.94%   |
| Intel Wireless 7265                                               | 23        | 0.94%   |
| Intel Ethernet Connection (2) I219-V                              | 23        | 0.94%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 22        | 0.9%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 21        | 0.86%   |
| Intel Wireless 7260                                               | 19        | 0.78%   |
| Intel Wireless-AC 9260                                            | 18        | 0.74%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 16        | 0.66%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 16        | 0.66%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 15        | 0.62%   |
| Intel Ethernet Connection (7) I219-V                              | 14        | 0.57%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 13        | 0.53%   |
| Intel Ethernet Connection (2) I219-LM                             | 13        | 0.53%   |
| Realtek Realtek Network controller                                | 12        | 0.49%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 12        | 0.49%   |
| Intel Wireless 3165                                               | 11        | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 710       | 57.54%  |
| Realtek Semiconductor             | 183       | 14.83%  |
| Qualcomm Atheros                  | 121       | 9.81%   |
| MediaTek                          | 79        | 6.4%    |
| Broadcom                          | 40        | 3.24%   |
| TP-Link                           | 20        | 1.62%   |
| Ralink Technology                 | 10        | 0.81%   |
| Ralink                            | 10        | 0.81%   |
| Qualcomm                          | 10        | 0.81%   |
| Broadcom Limited                  | 10        | 0.81%   |
| Sierra Wireless                   | 9         | 0.73%   |
| Microsoft                         | 6         | 0.49%   |
| Dell                              | 4         | 0.32%   |
| D-Link                            | 4         | 0.32%   |
| ASUSTek Computer                  | 4         | 0.32%   |
| Marvell Technology Group          | 3         | 0.24%   |
| Fibocom                           | 3         | 0.24%   |
| Hewlett-Packard                   | 2         | 0.16%   |
| Qualcomm Atheros Communications   | 1         | 0.08%   |
| NetGear                           | 1         | 0.08%   |
| Linksys                           | 1         | 0.08%   |
| Ericsson Business Mobile Networks | 1         | 0.08%   |
| D-Link System                     | 1         | 0.08%   |
| AboCom Systems                    | 1         | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 114       | 9.22%   |
| Intel Wi-Fi 6 AX201                                            | 84        | 6.8%    |
| Intel Alder Lake-P PCH CNVi WiFi                               | 77        | 6.23%   |
| Intel Wireless 8265 / 8275                                     | 63        | 5.1%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 55        | 4.45%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 37        | 2.99%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 34        | 2.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 33        | 2.67%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 30        | 2.43%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 29        | 2.35%   |
| Intel Wireless 8260                                            | 29        | 2.35%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 29        | 2.35%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 28        | 2.27%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 26        | 2.1%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 23        | 1.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 23        | 1.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 23        | 1.86%   |
| Intel Wireless 7265                                            | 23        | 1.86%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 22        | 1.78%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 21        | 1.7%    |
| Intel Wireless 7260                                            | 19        | 1.54%   |
| Intel Wireless-AC 9260                                         | 18        | 1.46%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 16        | 1.29%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 16        | 1.29%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 15        | 1.21%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 13        | 1.05%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 12        | 0.97%   |
| Realtek Realtek Network controller                             | 11        | 0.89%   |
| Intel Wireless 3165                                            | 11        | 0.89%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 11        | 0.89%   |
| Intel Centrino Ultimate-N 6300                                 | 10        | 0.81%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 9         | 0.73%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 8         | 0.65%   |
| Intel Wireless 3160                                            | 7         | 0.57%   |
| Broadcom BCM43142 802.11b/g/n                                  | 7         | 0.57%   |
| Sierra Wireless EM7455                                         | 6         | 0.49%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 6         | 0.49%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 6         | 0.49%   |
| Realtek 802.11ac NIC                                           | 6         | 0.49%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 6         | 0.49%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 621       | 53.81%  |
| Intel                                  | 372       | 32.24%  |
| Qualcomm Atheros                       | 36        | 3.12%   |
| Broadcom                               | 30        | 2.6%    |
| MediaTek                               | 17        | 1.47%   |
| Lenovo                                 | 11        | 0.95%   |
| Aquantia                               | 11        | 0.95%   |
| ASIX Electronics                       | 8         | 0.69%   |
| Samsung Electronics                    | 7         | 0.61%   |
| Google                                 | 7         | 0.61%   |
| Xiaomi                                 | 6         | 0.52%   |
| Qualcomm                               | 3         | 0.26%   |
| Marvell Technology Group               | 3         | 0.26%   |
| DisplayLink                            | 3         | 0.26%   |
| D-Link                                 | 3         | 0.26%   |
| TP-Link                                | 2         | 0.17%   |
| Nvidia                                 | 2         | 0.17%   |
| Apple                                  | 2         | 0.17%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.09%   |
| OPPO                                   | 1         | 0.09%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.09%   |
| Motorola PCS                           | 1         | 0.09%   |
| Microsoft                              | 1         | 0.09%   |
| Mellanox Technologies                  | 1         | 0.09%   |
| JMicron Technology                     | 1         | 0.09%   |
| ICS Advent                             | 1         | 0.09%   |
| Hewlett-Packard                        | 1         | 0.09%   |
| American Megatrends                    | 1         | 0.09%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 446       | 37.61%  |
| Realtek RTL8125 2.5GbE Controller                                   | 63        | 5.31%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 52        | 4.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 51        | 4.3%    |
| Intel I211 Gigabit Network Connection                               | 41        | 3.46%   |
| Intel Ethernet Controller I225-V                                    | 38        | 3.2%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 35        | 2.95%   |
| Intel Ethernet Connection (4) I219-LM                               | 24        | 2.02%   |
| Intel Ethernet Connection (2) I219-V                                | 23        | 1.94%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter       | 16        | 1.35%   |
| Intel Ethernet Connection (7) I219-V                                | 14        | 1.18%   |
| Intel Ethernet Connection (2) I219-LM                               | 13        | 1.1%    |
| Intel Ethernet Connection I219-LM                                   | 11        | 0.93%   |
| Intel Ethernet Connection (4) I219-V                                | 11        | 0.93%   |
| Intel Ethernet Connection (10) I219-V                               | 11        | 0.93%   |
| Intel Ethernet Connection (16) I219-V                               | 10        | 0.84%   |
| Intel Ethernet Connection (13) I219-V                               | 10        | 0.84%   |
| Realtek RTL8152 Fast Ethernet Adapter                               | 9         | 0.76%   |
| Intel Ethernet Connection I218-LM                                   | 9         | 0.76%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                    | 8         | 0.67%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller           | 8         | 0.67%   |
| Intel Ethernet Connection (6) I219-V                                | 8         | 0.67%   |
| Intel 82574L Gigabit Network Connection                             | 8         | 0.67%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 8         | 0.67%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 7         | 0.59%   |
| Lenovo ThinkPad TBT 3 Dock                                          | 7         | 0.59%   |
| Intel Ethernet Connection I217-LM                                   | 7         | 0.59%   |
| Intel Ethernet Connection (3) I218-LM                               | 7         | 0.59%   |
| ASIX AX88179 Gigabit Ethernet                                       | 7         | 0.59%   |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 6         | 0.51%   |
| Realtek Killer E3000 2.5GbE Controller                              | 6         | 0.51%   |
| Intel Ethernet Connection I219-V                                    | 6         | 0.51%   |
| Intel Ethernet Connection (7) I219-LM                               | 6         | 0.51%   |
| Intel Ethernet Connection (6) I219-LM                               | 6         | 0.51%   |
| Intel Ethernet Connection (2) I218-V                                | 6         | 0.51%   |
| Intel Ethernet Connection (11) I219-LM                              | 6         | 0.51%   |
| Intel 82579V Gigabit Network Connection                             | 6         | 0.51%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller           | 5         | 0.42%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 5         | 0.42%   |
| Intel I210 Gigabit Network Connection                               | 5         | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1181      | 52.47%  |
| Ethernet | 1056      | 46.91%  |
| Modem    | 10        | 0.44%   |
| Unknown  | 4         | 0.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 976       | 64.89%  |
| Ethernet | 528       | 35.11%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 715       | 50.07%  |
| 1     | 636       | 44.54%  |
| 3     | 49        | 3.43%   |
| 0     | 18        | 1.26%   |
| 4     | 7         | 0.49%   |
| 5     | 2         | 0.14%   |
| 9     | 1         | 0.07%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1035      | 72.18%  |
| Yes  | 399       | 27.82%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 633       | 57.86%  |
| Realtek Semiconductor           | 112       | 10.24%  |
| Qualcomm Atheros Communications | 54        | 4.94%   |
| Foxconn / Hon Hai               | 48        | 4.39%   |
| IMC Networks                    | 47        | 4.3%    |
| Cambridge Silicon Radio         | 42        | 3.84%   |
| Lite-On Technology              | 34        | 3.11%   |
| Broadcom                        | 26        | 2.38%   |
| Apple                           | 19        | 1.74%   |
| MediaTek                        | 17        | 1.55%   |
| TP-Link                         | 14        | 1.28%   |
| Realtek                         | 14        | 1.28%   |
| ASUSTek Computer                | 7         | 0.64%   |
| USI                             | 3         | 0.27%   |
| Opticis                         | 3         | 0.27%   |
| Marvell Semiconductor           | 3         | 0.27%   |
| Dell                            | 3         | 0.27%   |
| Toshiba                         | 2         | 0.18%   |
| Hewlett-Packard                 | 2         | 0.18%   |
| Edimax Technology               | 2         | 0.18%   |
| Belkin Components               | 2         | 0.18%   |
| Unknown                         | 1         | 0.09%   |
| SINO WEALTH                     | 1         | 0.09%   |
| Ralink                          | 1         | 0.09%   |
| Integrated System Solution      | 1         | 0.09%   |
| HTC (High Tech Computer)        | 1         | 0.09%   |
| Dynex                           | 1         | 0.09%   |
| Corsair                         | 1         | 0.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 156       | 14.23%  |
| Intel Bluetooth wireless interface                  | 135       | 12.32%  |
| Intel AX200 Bluetooth                               | 110       | 10.04%  |
| Realtek Bluetooth Radio                             | 92        | 8.39%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 92        | 8.39%   |
| Intel Bluetooth Device                              | 60        | 5.47%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 42        | 3.83%   |
| Foxconn / Hon Hai Wireless_Device                   | 40        | 3.65%   |
| Intel AX210 Bluetooth                               | 37        | 3.38%   |
| Qualcomm Atheros  Bluetooth Device                  | 35        | 3.19%   |
| IMC Networks Wireless_Device                        | 22        | 2.01%   |
| Intel Wireless-AC 3168 Bluetooth                    | 21        | 1.92%   |
| MediaTek Wireless_Device                            | 17        | 1.55%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 16        | 1.46%   |
| TP-Link TPuLink UB500 Adapter                       | 14        | 1.28%   |
| Realtek 802.11ac WLAN Adapter                       | 14        | 1.28%   |
| Realtek  Bluetooth 4.2 Adapter                      | 13        | 1.19%   |
| Lite-On Bluetooth Device                            | 13        | 1.19%   |
| IMC Networks Bluetooth Radio                        | 13        | 1.19%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 10        | 0.91%   |
| Apple Bluetooth USB Host Controller                 | 10        | 0.91%   |
| IMC Networks Bluetooth Device                       | 9         | 0.82%   |
| Lite-On Wireless_Device                             | 8         | 0.73%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 8         | 0.73%   |
| Apple Bluetooth Host Controller                     | 8         | 0.73%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 6         | 0.55%   |
| Foxconn / Hon Hai Bluetooth Device                  | 6         | 0.55%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 6         | 0.55%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 6         | 0.55%   |
| USI Bluetooth Device                                | 3         | 0.27%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 3         | 0.27%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 0.27%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 0.27%   |
| Opticis Bluetooth Radio                             | 3         | 0.27%   |
| Marvell Bluetooth and Wireless LAN Composite        | 3         | 0.27%   |
| Lite-On Bluetooth Radio                             | 3         | 0.27%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 3         | 0.27%   |
| Realtek RTL8821A Bluetooth                          | 2         | 0.18%   |
| Realtek RTL8723B Bluetooth                          | 2         | 0.18%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 0.18%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 946       | 45.03%  |
| AMD                                  | 503       | 23.94%  |
| Nvidia                               | 346       | 16.47%  |
| C-Media Electronics                  | 36        | 1.71%   |
| Logitech                             | 25        | 1.19%   |
| Razer USA                            | 14        | 0.67%   |
| Lenovo                               | 14        | 0.67%   |
| Kingston Technology                  | 12        | 0.57%   |
| ASUSTek Computer                     | 12        | 0.57%   |
| Plantronics                          | 10        | 0.48%   |
| GN Netcom                            | 10        | 0.48%   |
| Creative Labs                        | 10        | 0.48%   |
| SteelSeries ApS                      | 9         | 0.43%   |
| Realtek Semiconductor                | 9         | 0.43%   |
| Generalplus Technology               | 9         | 0.43%   |
| Focusrite-Novation                   | 9         | 0.43%   |
| Corsair                              | 8         | 0.38%   |
| JMTek                                | 7         | 0.33%   |
| Samson Technologies                  | 5         | 0.24%   |
| RODE Microphones                     | 5         | 0.24%   |
| Hewlett-Packard                      | 5         | 0.24%   |
| Creative Technology                  | 5         | 0.24%   |
| Blue Microphones                     | 5         | 0.24%   |
| VIA Technologies                     | 4         | 0.19%   |
| Texas Instruments                    | 4         | 0.19%   |
| Sony                                 | 4         | 0.19%   |
| Micro Star International             | 4         | 0.19%   |
| Dell                                 | 4         | 0.19%   |
| Samsung Electronics                  | 3         | 0.14%   |
| Giga-Byte Technology                 | 3         | 0.14%   |
| Asahi Kasei Microsystems             | 3         | 0.14%   |
| Apple                                | 3         | 0.14%   |
| XMOS                                 | 2         | 0.1%    |
| Trust                                | 2         | 0.1%    |
| Thesycon Systemsoftware & Consulting | 2         | 0.1%    |
| Schiit Audio                         | 2         | 0.1%    |
| PreSonus Audio Electronics           | 2         | 0.1%    |
| Medeli Electronics                   | 2         | 0.1%    |
| LG Electronics                       | 2         | 0.1%    |
| FiiO Electronics Technology          | 2         | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 277       | 10.88%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 165       | 6.48%   |
| Intel Sunrise Point-LP HD Audio                                            | 139       | 5.46%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 100       | 3.93%   |
| AMD Starship/Matisse HD Audio Controller                                   | 95        | 3.73%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 88        | 3.46%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 70        | 2.75%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 64        | 2.51%   |
| Intel Cannon Lake PCH cAVS                                                 | 58        | 2.28%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 54        | 2.12%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 45        | 1.77%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 45        | 1.77%   |
| Intel Comet Lake PCH-LP cAVS                                               | 44        | 1.73%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 36        | 1.41%   |
| Nvidia GA106 High Definition Audio Controller                              | 33        | 1.3%    |
| Intel Comet Lake PCH cAVS                                                  | 33        | 1.3%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 33        | 1.3%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 33        | 1.3%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 32        | 1.26%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 31        | 1.22%   |
| Nvidia GP107GL High Definition Audio Controller                            | 30        | 1.18%   |
| Nvidia GA104 High Definition Audio Controller                              | 28        | 1.1%    |
| Nvidia TU106 High Definition Audio Controller                              | 27        | 1.06%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 26        | 1.02%   |
| Intel 200 Series PCH HD Audio                                              | 26        | 1.02%   |
| Intel Alder Lake-S HD Audio Controller                                     | 24        | 0.94%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 22        | 0.86%   |
| Intel Broadwell-U Audio Controller                                         | 22        | 0.86%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 19        | 0.75%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 19        | 0.75%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 19        | 0.75%   |
| Nvidia Audio device                                                        | 18        | 0.71%   |
| Intel Haswell-ULT HD Audio Controller                                      | 18        | 0.71%   |
| Intel 8 Series HD Audio Controller                                         | 18        | 0.71%   |
| Nvidia TU116 High Definition Audio Controller                              | 17        | 0.67%   |
| Nvidia TU104 HD Audio Controller                                           | 16        | 0.63%   |
| Intel CM238 HD Audio Controller                                            | 16        | 0.63%   |
| AMD FCH Azalia Controller                                                  | 16        | 0.63%   |
| Nvidia GP106 High Definition Audio Controller                              | 15        | 0.59%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 15        | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 201       | 24.51%  |
| SK hynix            | 151       | 18.41%  |
| Micron Technology   | 108       | 13.17%  |
| Kingston            | 82        | 10%     |
| Crucial             | 46        | 5.61%   |
| G.Skill             | 38        | 4.63%   |
| Corsair             | 37        | 4.51%   |
| Unknown             | 29        | 3.54%   |
| A-DATA Technology   | 21        | 2.56%   |
| Unknown             | 16        | 1.95%   |
| Ramaxel Technology  | 13        | 1.59%   |
| Team                | 11        | 1.34%   |
| Patriot             | 6         | 0.73%   |
| Elpida              | 6         | 0.73%   |
| Unknown (ABCD)      | 5         | 0.61%   |
| Smart               | 5         | 0.61%   |
| Nanya Technology    | 5         | 0.61%   |
| Transcend           | 3         | 0.37%   |
| Avant               | 3         | 0.37%   |
| Apacer              | 3         | 0.37%   |
| Unifosa             | 2         | 0.24%   |
| PUSKILL             | 2         | 0.24%   |
| Goldkey             | 2         | 0.24%   |
| Gold Key            | 2         | 0.24%   |
| AMD                 | 2         | 0.24%   |
| Wilk                | 1         | 0.12%   |
| V-Color             | 1         | 0.12%   |
| Unknown (0x0B5E)    | 1         | 0.12%   |
| Timetec             | 1         | 0.12%   |
| Teikon              | 1         | 0.12%   |
| Smart Brazil        | 1         | 0.12%   |
| Silicon Power       | 1         | 0.12%   |
| Qumo                | 1         | 0.12%   |
| Qimonda             | 1         | 0.12%   |
| PNY                 | 1         | 0.12%   |
| Miron               | 1         | 0.12%   |
| Lexar Co Limited    | 1         | 0.12%   |
| Lexar               | 1         | 0.12%   |
| Kllisre             | 1         | 0.12%   |
| Innodisk            | 1         | 0.12%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 16        | 1.84%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 15        | 1.72%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 1.15%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 9         | 1.03%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 0.92%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 0.92%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 8         | 0.92%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 7         | 0.8%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 7         | 0.8%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 7         | 0.8%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 0.69%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 6         | 0.69%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 5         | 0.57%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 5         | 0.57%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 5         | 0.57%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 4         | 0.46%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 0.46%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s        | 4         | 0.46%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 4         | 0.46%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 4GB Row Of Chips LPDDR5 6400MT/s | 4         | 0.46%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 4         | 0.46%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 4         | 0.46%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 4         | 0.46%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.46%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 0.46%   |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s         | 4         | 0.46%   |
| Samsung RAM K3LKBKB@BM-MGCP 2048MB Row Of Chips 6400MT/s         | 4         | 0.46%   |
| Micron RAM MT62F2G32D8DR-031 WT 8GB SODIMM LPDDR5 6400MT/s       | 4         | 0.46%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 4         | 0.46%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s             | 4         | 0.46%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 4         | 0.46%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s              | 4         | 0.46%   |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s            | 3         | 0.34%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 3         | 0.34%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.34%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.34%   |
| SK hynix RAM HMCG66MEBSA092N 8GB SODIMM DDR5 4800MT/s            | 3         | 0.34%   |
| SK hynix RAM HMAB2GS6CMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 3         | 0.34%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 3         | 0.34%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.34%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 419       | 59.52%  |
| DDR3    | 115       | 16.34%  |
| LPDDR4  | 41        | 5.82%   |
| DDR5    | 40        | 5.68%   |
| LPDDR5  | 37        | 5.26%   |
| LPDDR3  | 29        | 4.12%   |
| DDR2    | 14        | 1.99%   |
| Unknown | 6         | 0.85%   |
| SDRAM   | 3         | 0.43%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 408       | 57.38%  |
| DIMM         | 175       | 24.61%  |
| Row Of Chips | 119       | 16.74%  |
| Unknown      | 4         | 0.56%   |
| Chip         | 3         | 0.42%   |
| FB-DIMM      | 2         | 0.28%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 348       | 46.65%  |
| 4096  | 152       | 20.38%  |
| 16384 | 139       | 18.63%  |
| 2048  | 57        | 7.64%   |
| 32768 | 43        | 5.76%   |
| 1024  | 7         | 0.94%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 209       | 27.72%  |
| 2667    | 113       | 14.99%  |
| 1600    | 80        | 10.61%  |
| 2400    | 54        | 7.16%   |
| 2133    | 40        | 5.31%   |
| 6400    | 37        | 4.91%   |
| 4800    | 31        | 4.11%   |
| 1333    | 23        | 3.05%   |
| 3600    | 20        | 2.65%   |
| 4267    | 18        | 2.39%   |
| 1867    | 16        | 2.12%   |
| 4266    | 10        | 1.33%   |
| 3466    | 9         | 1.19%   |
| 800     | 8         | 1.06%   |
| 3266    | 7         | 0.93%   |
| 667     | 7         | 0.93%   |
| 3733    | 6         | 0.8%    |
| 3866    | 5         | 0.66%   |
| 5200    | 4         | 0.53%   |
| 2666    | 4         | 0.53%   |
| 1866    | 4         | 0.53%   |
| 1800    | 4         | 0.53%   |
| 1334    | 4         | 0.53%   |
| 3800    | 3         | 0.4%    |
| 3400    | 3         | 0.4%    |
| 3000    | 3         | 0.4%    |
| 8400    | 2         | 0.27%   |
| 5600    | 2         | 0.27%   |
| 3333    | 2         | 0.27%   |
| 2933    | 2         | 0.27%   |
| 2800    | 2         | 0.27%   |
| 1066    | 2         | 0.27%   |
| 933     | 2         | 0.27%   |
| 533     | 2         | 0.27%   |
| 400     | 2         | 0.27%   |
| Unknown | 2         | 0.27%   |
| 6000    | 1         | 0.13%   |
| 5808    | 1         | 0.13%   |
| 4133    | 1         | 0.13%   |
| 3666    | 1         | 0.13%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 6         | 31.58%  |
| Brother Industries    | 5         | 26.32%  |
| Seiko Epson           | 2         | 10.53%  |
| Samsung Electronics   | 2         | 10.53%  |
| Prolific Technology   | 1         | 5.26%   |
| MiiiW                 | 1         | 5.26%   |
| Lexmark International | 1         | 5.26%   |
| Canon                 | 1         | 5.26%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Seiko Epson Printer           | 1         | 5.26%   |
| Seiko Epson L300 Series       | 1         | 5.26%   |
| Samsung SCX-4300 Series       | 1         | 5.26%   |
| Samsung ML-2855 Series        | 1         | 5.26%   |
| Prolific PL2305 Parallel Port | 1         | 5.26%   |
| MiiiW MW USB Receiver         | 1         | 5.26%   |
| Lexmark International B2236dw | 1         | 5.26%   |
| HP Officejet 2620 series      | 1         | 5.26%   |
| HP LaserJet 1010              | 1         | 5.26%   |
| HP ENVY Photo 7800 series     | 1         | 5.26%   |
| HP DeskJet F300 series        | 1         | 5.26%   |
| HP DeskJet 5650c              | 1         | 5.26%   |
| HP DeskJet 3630 series        | 1         | 5.26%   |
| Canon LiDE 400                | 1         | 5.26%   |
| Brother MFC-7460DN            | 1         | 5.26%   |
| Brother HL-L2350DW series     | 1         | 5.26%   |
| Brother HL-L2300D series      | 1         | 5.26%   |
| Brother DCP-L2510D series     | 1         | 5.26%   |
| Brother DCP-1600              | 1         | 5.26%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Canon       | 2         | 66.67%  |
| Seiko Epson | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Seiko Epson GT-6600U [Perfection 610] | 1         | 33.33%  |
| Canon CanoScan N670U/N676U/LiDE 20    | 1         | 33.33%  |
| Canon CanoScan LiDE 210               | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 234       | 22.78%  |
| IMC Networks                           | 128       | 12.46%  |
| Microdia                               | 97        | 9.44%   |
| Quanta                                 | 81        | 7.89%   |
| Logitech                               | 74        | 7.21%   |
| Acer                                   | 74        | 7.21%   |
| Realtek Semiconductor                  | 51        | 4.97%   |
| Sunplus Innovation Technology          | 43        | 4.19%   |
| Cheng Uei Precision Industry (Foxlink) | 32        | 3.12%   |
| Luxvisions Innotech Limited            | 30        | 2.92%   |
| Syntek                                 | 25        | 2.43%   |
| Apple                                  | 22        | 2.14%   |
| Lite-On Technology                     | 19        | 1.85%   |
| Sonix Technology                       | 15        | 1.46%   |
| Microsoft                              | 12        | 1.17%   |
| Silicon Motion                         | 9         | 0.88%   |
| Suyin                                  | 6         | 0.58%   |
| SunplusIT                              | 6         | 0.58%   |
| Samsung Electronics                    | 6         | 0.58%   |
| Tripath Technology                     | 4         | 0.39%   |
| MacroSilicon                           | 4         | 0.39%   |
| KYE Systems (Mouse Systems)            | 4         | 0.39%   |
| Alcor Micro                            | 4         | 0.39%   |
| Unknown                                | 3         | 0.29%   |
| LG Electronics                         | 3         | 0.29%   |
| WaveRider Communications               | 2         | 0.19%   |
| Trust                                  | 2         | 0.19%   |
| Lenovo                                 | 2         | 0.19%   |
| Importek                               | 2         | 0.19%   |
| icSpring                               | 2         | 0.19%   |
| Hewlett-Packard                        | 2         | 0.19%   |
| Generalplus Technology                 | 2         | 0.19%   |
| AVerMedia Technologies                 | 2         | 0.19%   |
| ARC International                      | 2         | 0.19%   |
| A4Tech                                 | 2         | 0.19%   |
| WCM_USB                                | 1         | 0.1%    |
| USB Camera CS                          | 1         | 0.1%    |
| SN0002                                 | 1         | 0.1%    |
| Smartronix                             | 1         | 0.1%    |
| SJ-180517-N                            | 1         | 0.1%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                         | 82        | 7.92%   |
| Microdia Integrated_Webcam_HD                     | 53        | 5.12%   |
| IMC Networks USB2.0 HD UVC WebCam                 | 44        | 4.25%   |
| IMC Networks Integrated Camera                    | 37        | 3.57%   |
| Acer Integrated Camera                            | 31        | 2.99%   |
| Realtek Integrated_Webcam_HD                      | 30        | 2.9%    |
| Chicony HD Webcam                                 | 22        | 2.12%   |
| Syntek Integrated Camera                          | 17        | 1.64%   |
| Quanta HD User Facing                             | 17        | 1.64%   |
| Logitech HD Pro Webcam C920                       | 14        | 1.35%   |
| Sunplus Integrated_Webcam_HD                      | 12        | 1.16%   |
| Quanta HP HD Camera                               | 12        | 1.16%   |
| IMC Networks HD Camera                            | 12        | 1.16%   |
| Quanta HP Wide Vision HD Camera                   | 11        | 1.06%   |
| Microdia Integrated_Webcam_FHD                    | 11        | 1.06%   |
| Logitech Webcam C270                              | 11        | 1.06%   |
| Chicony Integrated Camera (1280x720@30)           | 11        | 1.06%   |
| Luxvisions Innotech Limited Integrated RGB Camera | 10        | 0.97%   |
| Lite-On Integrated Camera                         | 10        | 0.97%   |
| Apple iPhone 5/5C/5S/6/SE                         | 10        | 0.97%   |
| Sonix USB2.0 HD UVC WebCam                        | 9         | 0.87%   |
| Logitech HD Webcam C525                           | 9         | 0.87%   |
| Chicony HP Wide Vision HD Camera                  | 9         | 0.87%   |
| Chicony HP TrueVision HD Camera                   | 9         | 0.87%   |
| Chicony HP HD Camera                              | 9         | 0.87%   |
| Logitech C922 Pro Stream Webcam                   | 8         | 0.77%   |
| IMC Networks USB2.0 VGA UVC WebCam                | 8         | 0.77%   |
| Chicony HD User Facing                            | 8         | 0.77%   |
| Chicony EasyCamera                                | 8         | 0.77%   |
| Acer HD Webcam                                    | 8         | 0.77%   |
| Quanta HP TrueVision HD Camera                    | 7         | 0.68%   |
| Luxvisions Innotech Limited Integrated Camera     | 7         | 0.68%   |
| Chicony USB2.0 VGA UVC WebCam                     | 7         | 0.68%   |
| Chicony USB2.0 Camera                             | 7         | 0.68%   |
| Samsung Galaxy A5 (MTP)                           | 6         | 0.58%   |
| Quanta HD Webcam                                  | 6         | 0.58%   |
| Microdia Webcam Vitade AF                         | 6         | 0.58%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera  | 6         | 0.58%   |
| Apple FaceTime HD Camera (Built-in)               | 6         | 0.58%   |
| Quanta VGA WebCam                                 | 5         | 0.48%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 96        | 40.85%  |
| Shenzhen Goodix Technology         | 53        | 22.55%  |
| Validity Sensors                   | 48        | 20.43%  |
| Elan Microelectronics              | 19        | 8.09%   |
| LighTuning Technology              | 7         | 2.98%   |
| AuthenTec                          | 4         | 1.7%    |
| Upek                               | 2         | 0.85%   |
| Samsung Electronics                | 2         | 0.85%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.85%   |
| STMicroelectronics                 | 1         | 0.43%   |
| Microsoft                          | 1         | 0.43%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 39        | 16.6%   |
| Shenzhen Goodix  FingerPrint Device                                        | 39        | 16.6%   |
| Unknown                                                                    | 32        | 13.62%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 13        | 5.53%   |
| Shenzhen Goodix Fingerprint Reader                                         | 11        | 4.68%   |
| Validity Sensors Synaptics WBDI                                            | 10        | 4.26%   |
| Elan ELAN:ARM-M4                                                           | 10        | 4.26%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 9         | 3.83%   |
| Synaptics  WBDI                                                            | 8         | 3.4%    |
| Elan ELAN:Fingerprint                                                      | 8         | 3.4%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 7         | 2.98%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 2.13%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 1.7%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 1.28%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 3         | 1.28%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 1.28%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 1.28%   |
| AuthenTec AES1600                                                          | 3         | 1.28%   |
| Validity Sensors VFS491                                                    | 2         | 0.85%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 0.85%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 0.85%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 0.85%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 0.85%   |
| LighTuning Fingerprint Sensor                                              | 2         | 0.85%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 0.85%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.43%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.43%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.43%   |
| Synaptics WBDI Device                                                      | 1         | 0.43%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.43%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.43%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 0.43%   |
| Samsung Fingerprint Device                                                 | 1         | 0.43%   |
| Microsoft Fingerprint Reader                                               | 1         | 0.43%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 1         | 0.43%   |
| AuthenTec AES2810                                                          | 1         | 0.43%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 35        | 42.17%  |
| Alcor Micro           | 35        | 42.17%  |
| Upek                  | 6         | 7.23%   |
| Lenovo                | 3         | 3.61%   |
| Yubico.com            | 1         | 1.2%    |
| O2 Micro              | 1         | 1.2%    |
| Gemalto (was Gemplus) | 1         | 1.2%    |
| Aktiv                 | 1         | 1.2%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 35        | 42.17%  |
| Broadcom 58200                                                               | 14        | 16.87%  |
| Broadcom 5880                                                                | 12        | 14.46%  |
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 8.43%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 6         | 7.23%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 3.61%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 2.41%   |
| Yubico.com Yubikey 4 U2F+CCID                                                | 1         | 1.2%    |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.2%    |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.2%    |
| Aktiv Rutoken lite                                                           | 1         | 1.2%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 951       | 65.9%   |
| 1     | 411       | 28.48%  |
| 2     | 58        | 4.02%   |
| 3     | 10        | 0.69%   |
| 4     | 6         | 0.42%   |
| 5     | 4         | 0.28%   |
| 7     | 2         | 0.14%   |
| 8     | 1         | 0.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 232       | 39.39%  |
| Graphics card            | 142       | 24.11%  |
| Multimedia controller    | 66        | 11.21%  |
| Net/wireless             | 39        | 6.62%   |
| Camera                   | 30        | 5.09%   |
| Chipcard                 | 18        | 3.06%   |
| Sound                    | 17        | 2.89%   |
| Communication controller | 9         | 1.53%   |
| Card reader              | 8         | 1.36%   |
| Bluetooth                | 7         | 1.19%   |
| Unassigned class         | 5         | 0.85%   |
| Net/ethernet             | 5         | 0.85%   |
| Storage/raid             | 3         | 0.51%   |
| Storage                  | 3         | 0.51%   |
| Network                  | 3         | 0.51%   |
| Modem                    | 1         | 0.17%   |
| Firewire controller      | 1         | 0.17%   |

