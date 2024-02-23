ROSA - Tested Hardware & Statistics
-----------------------------------

A project to collect tested hardware configurations for ROSA.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/ROSA/Desktop/README.md) and [notebooks](/Dist/ROSA/Notebook/README.md).

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

Total: 44228

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Acer          | P4LJ0                       | Notebook    | [c0a2639732](https://linux-hardware.org/?probe=c0a2639732) | Feb 02, 2024 |
| ASUSTek       | B85M-G                      | Desktop     | [cd9f6ee87d](https://linux-hardware.org/?probe=cd9f6ee87d) | Feb 02, 2024 |
| ASRock        | 970M Pro3                   | Desktop     | [cf54a4b360](https://linux-hardware.org/?probe=cf54a4b360) | Feb 02, 2024 |
| ASUSTek       | PRIME H510M-R               | Desktop     | [4196d911d2](https://linux-hardware.org/?probe=4196d911d2) | Feb 02, 2024 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [f38bbe7c82](https://linux-hardware.org/?probe=f38bbe7c82) | Feb 02, 2024 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [bf840a5308](https://linux-hardware.org/?probe=bf840a5308) | Feb 02, 2024 |
| ASUSTek       | P5K                         | Desktop     | [1414d10ffb](https://linux-hardware.org/?probe=1414d10ffb) | Feb 01, 2024 |
| Acer          | TravelMate B118-M           | Notebook    | [4f53c6a6af](https://linux-hardware.org/?probe=4f53c6a6af) | Feb 01, 2024 |
| Gigabyte      | EP43T-UD3L                  | Desktop     | [934c3f974a](https://linux-hardware.org/?probe=934c3f974a) | Feb 01, 2024 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [5befaf642f](https://linux-hardware.org/?probe=5befaf642f) | Feb 01, 2024 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [729a70888f](https://linux-hardware.org/?probe=729a70888f) | Feb 01, 2024 |
| Samsung       | RV413/RV513/E3413           | Notebook    | [975921919b](https://linux-hardware.org/?probe=975921919b) | Feb 01, 2024 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [bce380880a](https://linux-hardware.org/?probe=bce380880a) | Feb 01, 2024 |
| ASRock        | G41M-VS3                    | Desktop     | [df1c8c0da3](https://linux-hardware.org/?probe=df1c8c0da3) | Feb 01, 2024 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [b00734a23e](https://linux-hardware.org/?probe=b00734a23e) | Feb 01, 2024 |
| MACHCREATO... | E                           | Notebook    | [af231c3cc8](https://linux-hardware.org/?probe=af231c3cc8) | Jan 31, 2024 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [6361608cec](https://linux-hardware.org/?probe=6361608cec) | Jan 31, 2024 |
| ASUSTek       | V221ID                      | All in one  | [1a3791054b](https://linux-hardware.org/?probe=1a3791054b) | Jan 31, 2024 |
| Intel         | SKYBAY                      | Desktop     | [1e706b6589](https://linux-hardware.org/?probe=1e706b6589) | Jan 31, 2024 |
| Acer          | Aspire ES1-531              | Notebook    | [eb59b4c3ac](https://linux-hardware.org/?probe=eb59b4c3ac) | Jan 31, 2024 |
| Intel         | SKYBAY                      | Desktop     | [4420198abc](https://linux-hardware.org/?probe=4420198abc) | Jan 31, 2024 |
| Intel         | SKYBAY                      | Desktop     | [9d6bc7afb3](https://linux-hardware.org/?probe=9d6bc7afb3) | Jan 31, 2024 |
| Dell          | Inspiron MXC061             | Notebook    | [a134206781](https://linux-hardware.org/?probe=a134206781) | Jan 31, 2024 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [556c1ede91](https://linux-hardware.org/?probe=556c1ede91) | Jan 30, 2024 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [39c2f54da6](https://linux-hardware.org/?probe=39c2f54da6) | Jan 30, 2024 |
| ASUSTek       | ASUS EXPERTBOOK L2402CYA... | Notebook    | [7b41a93878](https://linux-hardware.org/?probe=7b41a93878) | Jan 30, 2024 |
| ASUSTek       | P7H55                       | Desktop     | [21853e5c4a](https://linux-hardware.org/?probe=21853e5c4a) | Jan 30, 2024 |
| Fujitsu       | LIFEBOOK AH544              | Notebook    | [7c4ab0f337](https://linux-hardware.org/?probe=7c4ab0f337) | Jan 29, 2024 |
| Intel         | X99 V1.0                    | Desktop     | [dee15911ba](https://linux-hardware.org/?probe=dee15911ba) | Jan 29, 2024 |
| Fujitsu       | LIFEBOOK AH544              | Notebook    | [b7421bfef5](https://linux-hardware.org/?probe=b7421bfef5) | Jan 29, 2024 |
| Lenovo        | 3190 NOK                    | Mini pc     | [df5decae4b](https://linux-hardware.org/?probe=df5decae4b) | Jan 29, 2024 |
| OEM           | PSC621DI-16F 12220113A01... | Server      | [6c1f52bc56](https://linux-hardware.org/?probe=6c1f52bc56) | Jan 29, 2024 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [d0403669b9](https://linux-hardware.org/?probe=d0403669b9) | Jan 29, 2024 |
| ASRock        | AB350M-HDV R3.0             | Desktop     | [7b68f8ca63](https://linux-hardware.org/?probe=7b68f8ca63) | Jan 29, 2024 |
| Lenovo        | G50-30 80G0                 | Notebook    | [94b345e552](https://linux-hardware.org/?probe=94b345e552) | Jan 29, 2024 |
| DEPO Compu... | DPH610S                     | Notebook    | [de6c6c0dc5](https://linux-hardware.org/?probe=de6c6c0dc5) | Jan 29, 2024 |
| eMachines     | Rhine V1.45                 | Notebook    | [6bb4f91b29](https://linux-hardware.org/?probe=6bb4f91b29) | Jan 29, 2024 |
| OEM           | T2DM B                      | Server      | [cbf4342d2c](https://linux-hardware.org/?probe=cbf4342d2c) | Jan 29, 2024 |
| ASRock        | AB350M-HDV R3.0             | Desktop     | [5cc2818fe5](https://linux-hardware.org/?probe=5cc2818fe5) | Jan 29, 2024 |
| HP            | Stream x360 Convertible ... | Convertible | [b19e0e313e](https://linux-hardware.org/?probe=b19e0e313e) | Jan 28, 2024 |
| Acer          | Iconia W701                 | Notebook    | [572a3d7c02](https://linux-hardware.org/?probe=572a3d7c02) | Jan 28, 2024 |
| Intel         | Unknown                     | Desktop     | [24ab2fdfbf](https://linux-hardware.org/?probe=24ab2fdfbf) | Jan 28, 2024 |
| Dell          | 0Y5DDC A00                  | Desktop     | [bad163ed53](https://linux-hardware.org/?probe=bad163ed53) | Jan 28, 2024 |
| ASUSTek       | X540SA                      | Notebook    | [39aef9d411](https://linux-hardware.org/?probe=39aef9d411) | Jan 28, 2024 |
| Sony          | VAIO                        | All in one  | [5a4ca41301](https://linux-hardware.org/?probe=5a4ca41301) | Jan 27, 2024 |
| ASUSTek       | P5K                         | Desktop     | [9cadd6185d](https://linux-hardware.org/?probe=9cadd6185d) | Jan 27, 2024 |
| ASUSTek       | Maximus VII RANGER          | Desktop     | [23059625c1](https://linux-hardware.org/?probe=23059625c1) | Jan 27, 2024 |
| ECS           | A960M-MV                    | Desktop     | [3b0de09ab6](https://linux-hardware.org/?probe=3b0de09ab6) | Jan 27, 2024 |
| MSI           | MS-B1711                    | Desktop     | [8eec6cdde5](https://linux-hardware.org/?probe=8eec6cdde5) | Jan 27, 2024 |
| Gigabyte      | GA-A55M-S2HP                | Desktop     | [2c061938f7](https://linux-hardware.org/?probe=2c061938f7) | Jan 26, 2024 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [0554d57e37](https://linux-hardware.org/?probe=0554d57e37) | Jan 26, 2024 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [70edc53219](https://linux-hardware.org/?probe=70edc53219) | Jan 26, 2024 |
| MSI           | 785G-E53                    | Desktop     | [81ee1ec28d](https://linux-hardware.org/?probe=81ee1ec28d) | Jan 26, 2024 |
| HP            | Pavilion 15                 | Notebook    | [c303f2769d](https://linux-hardware.org/?probe=c303f2769d) | Jan 26, 2024 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [1e983d206c](https://linux-hardware.org/?probe=1e983d206c) | Jan 26, 2024 |
| Intel         | SKYBAY                      | Desktop     | [3d4350c03d](https://linux-hardware.org/?probe=3d4350c03d) | Jan 26, 2024 |
| Unknown       | Unknown                     | Notebook    | [f24b77e03e](https://linux-hardware.org/?probe=f24b77e03e) | Jan 25, 2024 |
| Apple         | MacBookPro4,1               | Notebook    | [8cbf896791](https://linux-hardware.org/?probe=8cbf896791) | Jan 25, 2024 |
| ASUSTek       | N61Vg                       | Notebook    | [ea2d37b9a8](https://linux-hardware.org/?probe=ea2d37b9a8) | Jan 25, 2024 |
| Unknown       | Unknown                     | Notebook    | [f149927f3f](https://linux-hardware.org/?probe=f149927f3f) | Jan 25, 2024 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [d2b6c52d72](https://linux-hardware.org/?probe=d2b6c52d72) | Jan 25, 2024 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [ceebacdeee](https://linux-hardware.org/?probe=ceebacdeee) | Jan 24, 2024 |
| MACHENIKE     | L17                         | Notebook    | [6510b1b157](https://linux-hardware.org/?probe=6510b1b157) | Jan 24, 2024 |
| Acer          | Aspire A515-51G             | Notebook    | [d1fe84630c](https://linux-hardware.org/?probe=d1fe84630c) | Jan 24, 2024 |
| ASUSTek       | V221ID                      | All in one  | [9966113f02](https://linux-hardware.org/?probe=9966113f02) | Jan 24, 2024 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [61635d9262](https://linux-hardware.org/?probe=61635d9262) | Jan 24, 2024 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [10eb215783](https://linux-hardware.org/?probe=10eb215783) | Jan 24, 2024 |
| Infinix       | INBOOK X2                   | Notebook    | [a49adb917b](https://linux-hardware.org/?probe=a49adb917b) | Jan 24, 2024 |
| ASRock        | N68C-GS FX                  | Desktop     | [ed8901f53b](https://linux-hardware.org/?probe=ed8901f53b) | Jan 24, 2024 |
| Acer          | Aspire A717-71G             | Notebook    | [b7fb65f8f0](https://linux-hardware.org/?probe=b7fb65f8f0) | Jan 24, 2024 |
| Toshiba       | Satellite C660              | Notebook    | [b1d19ad191](https://linux-hardware.org/?probe=b1d19ad191) | Jan 23, 2024 |
| HP            | Pavilion g6                 | Notebook    | [ba785cef9c](https://linux-hardware.org/?probe=ba785cef9c) | Jan 23, 2024 |
| Toshiba       | Satellite L40               | Notebook    | [0f0ab308a5](https://linux-hardware.org/?probe=0f0ab308a5) | Jan 23, 2024 |
| Samsung       | R580/R590                   | Notebook    | [832ca89f89](https://linux-hardware.org/?probe=832ca89f89) | Jan 23, 2024 |
| Clevo         | NL41MU2                     | Notebook    | [9ea0222064](https://linux-hardware.org/?probe=9ea0222064) | Jan 23, 2024 |
| Huanan        | X99-BD4 V1.34               | Desktop     | [65794c873c](https://linux-hardware.org/?probe=65794c873c) | Jan 23, 2024 |
| ASUSTek       | S551LN                      | Notebook    | [4bcdfef62c](https://linux-hardware.org/?probe=4bcdfef62c) | Jan 23, 2024 |
| Shuttle       | XS35V3                      | Desktop     | [af36ef4d08](https://linux-hardware.org/?probe=af36ef4d08) | Jan 23, 2024 |
| ASRock        | H110M-DGS R3.0              | Desktop     | [8d264d359b](https://linux-hardware.org/?probe=8d264d359b) | Jan 22, 2024 |
| ASUSTek       | E520                        | Desktop     | [948381dfd1](https://linux-hardware.org/?probe=948381dfd1) | Jan 22, 2024 |
| ASUSTek       | P5QL                        | Desktop     | [300924de5a](https://linux-hardware.org/?probe=300924de5a) | Jan 22, 2024 |
| Acidanther... | MacBookPro16,3              | Notebook    | [ec9ea0d332](https://linux-hardware.org/?probe=ec9ea0d332) | Jan 22, 2024 |
| Acer          | Aspire A315-57G             | Notebook    | [75b94f015e](https://linux-hardware.org/?probe=75b94f015e) | Jan 22, 2024 |
| Intel         | X99                         | Desktop     | [f232e1ea07](https://linux-hardware.org/?probe=f232e1ea07) | Jan 21, 2024 |
| ASRock        | A770DE+                     | Desktop     | [280f9c65c0](https://linux-hardware.org/?probe=280f9c65c0) | Jan 21, 2024 |
| Biostar       | Z690GTA                     | Desktop     | [7beb190026](https://linux-hardware.org/?probe=7beb190026) | Jan 21, 2024 |
| ASUSTek       | P5KPL-AM                    | Desktop     | [98dc47d431](https://linux-hardware.org/?probe=98dc47d431) | Jan 21, 2024 |
| Acer          | Aspire 7551                 | Notebook    | [19efb9c9b1](https://linux-hardware.org/?probe=19efb9c9b1) | Jan 21, 2024 |
| Intel         | D525MW AAE93082-401         | Desktop     | [c1c97f080e](https://linux-hardware.org/?probe=c1c97f080e) | Jan 21, 2024 |
| Huanan        | X99 F8D V2.2                | Desktop     | [5a8ba8fd60](https://linux-hardware.org/?probe=5a8ba8fd60) | Jan 21, 2024 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [f8f9f25c64](https://linux-hardware.org/?probe=f8f9f25c64) | Jan 21, 2024 |
| Gigabyte      | B450 GAMING X               | Desktop     | [28be98f6c6](https://linux-hardware.org/?probe=28be98f6c6) | Jan 21, 2024 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [ac1d5f3aec](https://linux-hardware.org/?probe=ac1d5f3aec) | Jan 21, 2024 |
| ASRock        | B75 Pro3                    | Desktop     | [498caaba05](https://linux-hardware.org/?probe=498caaba05) | Jan 21, 2024 |
| ASRock        | N68C-GS FX                  | Desktop     | [6c88409266](https://linux-hardware.org/?probe=6c88409266) | Jan 21, 2024 |
| Intel         | X99                         | Desktop     | [93a5879bf4](https://linux-hardware.org/?probe=93a5879bf4) | Jan 21, 2024 |
| ECS           | A960M-MV                    | Desktop     | [7762cce94d](https://linux-hardware.org/?probe=7762cce94d) | Jan 21, 2024 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [0dc11cbadf](https://linux-hardware.org/?probe=0dc11cbadf) | Jan 21, 2024 |
| Dell          | 0Y5DDC A00                  | Desktop     | [a73f786be7](https://linux-hardware.org/?probe=a73f786be7) | Jan 20, 2024 |
| ASUSTek       | K50IN                       | Notebook    | [ce48aa2c37](https://linux-hardware.org/?probe=ce48aa2c37) | Jan 20, 2024 |
| ASUSTek       | K53SD                       | Notebook    | [0b62b854c0](https://linux-hardware.org/?probe=0b62b854c0) | Jan 20, 2024 |
| Gigabyte      | H310M S2V                   | Desktop     | [7be62ed879](https://linux-hardware.org/?probe=7be62ed879) | Jan 20, 2024 |
| HIPER Tech... | HIPER WORKBOOK              | Notebook    | [88b6a30668](https://linux-hardware.org/?probe=88b6a30668) | Jan 19, 2024 |
| ASUSTek       | F2A85-V PRO                 | Desktop     | [150d445de6](https://linux-hardware.org/?probe=150d445de6) | Jan 19, 2024 |
| ASUSTek       | F2A85-V PRO                 | Desktop     | [51b2474c14](https://linux-hardware.org/?probe=51b2474c14) | Jan 19, 2024 |
| HIPER Tech... | HIPER WORKBOOK              | Notebook    | [277f1fa594](https://linux-hardware.org/?probe=277f1fa594) | Jan 19, 2024 |
| ASUSTek       | UX303UA                     | Notebook    | [a1e8d78385](https://linux-hardware.org/?probe=a1e8d78385) | Jan 19, 2024 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [d805f83d93](https://linux-hardware.org/?probe=d805f83d93) | Jan 19, 2024 |
| ASUSTek       | PRIME A320M-E               | Desktop     | [979cbe9fe0](https://linux-hardware.org/?probe=979cbe9fe0) | Jan 19, 2024 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [69a5d8296c](https://linux-hardware.org/?probe=69a5d8296c) | Jan 19, 2024 |
| Acer          | Aspire A315-21              | Notebook    | [0e67fe580f](https://linux-hardware.org/?probe=0e67fe580f) | Jan 18, 2024 |
| Lenovo        | ThinkPad L530 2479BG8       | Notebook    | [4c8c134e10](https://linux-hardware.org/?probe=4c8c134e10) | Jan 18, 2024 |
| Unknown       | Unknown                     | Desktop     | [500e9e8fda](https://linux-hardware.org/?probe=500e9e8fda) | Jan 18, 2024 |
| Unknown       | Unknown                     | Desktop     | [17bd249685](https://linux-hardware.org/?probe=17bd249685) | Jan 18, 2024 |
| MSI           | PRO B760M-A WIFI DDR4       | Desktop     | [a115913fe1](https://linux-hardware.org/?probe=a115913fe1) | Jan 18, 2024 |
| MECHREVO      | Jiaolong Series GM5ZG0O     | Notebook    | [4f589be8f4](https://linux-hardware.org/?probe=4f589be8f4) | Jan 18, 2024 |
| MSI           | GE60 2PL                    | Notebook    | [a0eff25dfe](https://linux-hardware.org/?probe=a0eff25dfe) | Jan 17, 2024 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [d274a17024](https://linux-hardware.org/?probe=d274a17024) | Jan 17, 2024 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [9aa4d8799f](https://linux-hardware.org/?probe=9aa4d8799f) | Jan 17, 2024 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [39f5fe6747](https://linux-hardware.org/?probe=39f5fe6747) | Jan 17, 2024 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [b38e6a2298](https://linux-hardware.org/?probe=b38e6a2298) | Jan 17, 2024 |
| HP            | 250 G5 Notebook PC          | Notebook    | [d8e4449d99](https://linux-hardware.org/?probe=d8e4449d99) | Jan 16, 2024 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [ae035d3e35](https://linux-hardware.org/?probe=ae035d3e35) | Jan 16, 2024 |
| Dell          | 0C2KJT A00                  | Desktop     | [ef30ea4bc9](https://linux-hardware.org/?probe=ef30ea4bc9) | Jan 16, 2024 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [17555d4d11](https://linux-hardware.org/?probe=17555d4d11) | Jan 15, 2024 |
| Pegatron      | 2A94h                       | Desktop     | [1bb35b61cf](https://linux-hardware.org/?probe=1bb35b61cf) | Jan 15, 2024 |
| Gigabyte      | M720-US3                    | Desktop     | [3b0d0759b6](https://linux-hardware.org/?probe=3b0d0759b6) | Jan 15, 2024 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [4162a83dbc](https://linux-hardware.org/?probe=4162a83dbc) | Jan 15, 2024 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [f3ba9ee452](https://linux-hardware.org/?probe=f3ba9ee452) | Jan 15, 2024 |
| AZW           | GTR V01                     | Mini pc     | [21c7253861](https://linux-hardware.org/?probe=21c7253861) | Jan 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [e73d1f2078](https://linux-hardware.org/?probe=e73d1f2078) | Jan 15, 2024 |
| Intel         | H81                         | Desktop     | [b0fd4c7628](https://linux-hardware.org/?probe=b0fd4c7628) | Jan 15, 2024 |
| Dell          | 0C2KJT A00                  | Desktop     | [72e5220f30](https://linux-hardware.org/?probe=72e5220f30) | Jan 14, 2024 |
| HP            | ProBook 430 G2              | Notebook    | [0c1f594a26](https://linux-hardware.org/?probe=0c1f594a26) | Jan 14, 2024 |
| Matsushita... | CF-30CTQAZBG                | Notebook    | [18a587bfa8](https://linux-hardware.org/?probe=18a587bfa8) | Jan 14, 2024 |
| MSI           | FX610MX                     | Notebook    | [398e37e98e](https://linux-hardware.org/?probe=398e37e98e) | Jan 14, 2024 |
| ASUSTek       | K50IJ                       | Notebook    | [2626e31d7a](https://linux-hardware.org/?probe=2626e31d7a) | Jan 14, 2024 |
| Acer          | Aspire TC-705               | Desktop     | [52f5e7c5ef](https://linux-hardware.org/?probe=52f5e7c5ef) | Jan 14, 2024 |
| Gigabyte      | H61M-DS2                    | Desktop     | [f75904222c](https://linux-hardware.org/?probe=f75904222c) | Jan 13, 2024 |
| Packard Be... | EasyNote ENTE70BH           | Notebook    | [3b0a0b0f19](https://linux-hardware.org/?probe=3b0a0b0f19) | Jan 13, 2024 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [8035c49f8f](https://linux-hardware.org/?probe=8035c49f8f) | Jan 13, 2024 |
| HP            | ProBook 4330s               | Notebook    | [44ddddb2d1](https://linux-hardware.org/?probe=44ddddb2d1) | Jan 13, 2024 |
| ASRock        | H55M-LE                     | Desktop     | [30ce52798e](https://linux-hardware.org/?probe=30ce52798e) | Jan 13, 2024 |
| Huanan        | X79M-PRO V1.2               | Desktop     | [fbcae0c103](https://linux-hardware.org/?probe=fbcae0c103) | Jan 13, 2024 |
| Intel         | H81                         | Desktop     | [86da5a9776](https://linux-hardware.org/?probe=86da5a9776) | Jan 13, 2024 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [77546f522e](https://linux-hardware.org/?probe=77546f522e) | Jan 13, 2024 |
| MSI           | MS-B0A61                    | Desktop     | [cacdb6e6fe](https://linux-hardware.org/?probe=cacdb6e6fe) | Jan 13, 2024 |
| Acer          | FIH57                       | All in one  | [441ca577ab](https://linux-hardware.org/?probe=441ca577ab) | Jan 13, 2024 |
| HP            | 1825                        | Desktop     | [2e88180c54](https://linux-hardware.org/?probe=2e88180c54) | Jan 13, 2024 |
| Acer          | Aspire E5-532               | Notebook    | [5441361fdd](https://linux-hardware.org/?probe=5441361fdd) | Jan 13, 2024 |
| HP            | EliteBook 840 G4            | Notebook    | [e5073c8346](https://linux-hardware.org/?probe=e5073c8346) | Jan 13, 2024 |
| HP            | Pavilion dv7                | Notebook    | [5b2ddda1cc](https://linux-hardware.org/?probe=5b2ddda1cc) | Jan 13, 2024 |
| Packard Be... | EasyNote ENLG81BA           | Notebook    | [8fce4ff747](https://linux-hardware.org/?probe=8fce4ff747) | Jan 13, 2024 |
| Lenovo        | V15-IGL 82C3                | Notebook    | [c7de9c6d40](https://linux-hardware.org/?probe=c7de9c6d40) | Jan 12, 2024 |
| ASRock        | B760M-HDV/M.2 D4            | Desktop     | [a8d229af9d](https://linux-hardware.org/?probe=a8d229af9d) | Jan 12, 2024 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [15e853a1d1](https://linux-hardware.org/?probe=15e853a1d1) | Jan 12, 2024 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [3d9b7d2d2b](https://linux-hardware.org/?probe=3d9b7d2d2b) | Jan 12, 2024 |
| Intel         | SKYBAY                      | Desktop     | [a5f2ea79e9](https://linux-hardware.org/?probe=a5f2ea79e9) | Jan 12, 2024 |
| Pegatron      | 2AED                        | All in one  | [9443b8fa7b](https://linux-hardware.org/?probe=9443b8fa7b) | Jan 12, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [c317a3afa7](https://linux-hardware.org/?probe=c317a3afa7) | Jan 12, 2024 |
| HP            | ProBook 4330s               | Notebook    | [35ef27eb5a](https://linux-hardware.org/?probe=35ef27eb5a) | Jan 12, 2024 |
| Intel         | DH67CL AAG10212-208         | Desktop     | [9e5c35a6b6](https://linux-hardware.org/?probe=9e5c35a6b6) | Jan 12, 2024 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | Desktop     | [11dd31f3c6](https://linux-hardware.org/?probe=11dd31f3c6) | Jan 12, 2024 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [2e0a03aba1](https://linux-hardware.org/?probe=2e0a03aba1) | Jan 11, 2024 |
| Clevo         | NL41MU2                     | Notebook    | [a1934fd532](https://linux-hardware.org/?probe=a1934fd532) | Jan 11, 2024 |
| Sony          | VGN-NS11ER_S                | Notebook    | [a36cd10d4f](https://linux-hardware.org/?probe=a36cd10d4f) | Jan 11, 2024 |
| HP            | Pavilion 15                 | Notebook    | [f2b6647344](https://linux-hardware.org/?probe=f2b6647344) | Jan 11, 2024 |
| Gigabyte      | H410M H V3                  | Desktop     | [eb21b0dd13](https://linux-hardware.org/?probe=eb21b0dd13) | Jan 11, 2024 |
| ASUSTek       | PN52                        | Mini pc     | [96059ecdcd](https://linux-hardware.org/?probe=96059ecdcd) | Jan 11, 2024 |
| Samsung       | 550P5C/550P7C               | Notebook    | [0153b8d5e8](https://linux-hardware.org/?probe=0153b8d5e8) | Jan 11, 2024 |
| ASUSTek       | PRIME A320M-E               | Desktop     | [2be2d8a769](https://linux-hardware.org/?probe=2be2d8a769) | Jan 11, 2024 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [47a7d3fa7c](https://linux-hardware.org/?probe=47a7d3fa7c) | Jan 10, 2024 |
| ASRock        | H110M-DVS R3.0              | Desktop     | [15f0bd78f4](https://linux-hardware.org/?probe=15f0bd78f4) | Jan 10, 2024 |
| HP            | EliteBook 8440p             | Notebook    | [889462ebed](https://linux-hardware.org/?probe=889462ebed) | Jan 10, 2024 |
| Lenovo        | G70-70 80HW                 | Notebook    | [b3b5cddaa9](https://linux-hardware.org/?probe=b3b5cddaa9) | Jan 10, 2024 |
| ASUSTek       | F3JA                        | Notebook    | [bdf839bb01](https://linux-hardware.org/?probe=bdf839bb01) | Jan 10, 2024 |
| ASUSTek       | K54HR                       | Notebook    | [9bea135bd3](https://linux-hardware.org/?probe=9bea135bd3) | Jan 10, 2024 |
| Lenovo        | ThinkPad E14 20RA001BRT     | Notebook    | [99ac2e5b0c](https://linux-hardware.org/?probe=99ac2e5b0c) | Jan 10, 2024 |
| Gigabyte      | H81M-S1                     | Desktop     | [e152d77865](https://linux-hardware.org/?probe=e152d77865) | Jan 10, 2024 |
| MAINBRD       | OPS62A-SHA                  | Desktop     | [7090d5973d](https://linux-hardware.org/?probe=7090d5973d) | Jan 10, 2024 |
| MACHINIST     | E5-MR9S V1.0                | Desktop     | [7e938e0f91](https://linux-hardware.org/?probe=7e938e0f91) | Jan 10, 2024 |
| Shenzhen M... | F7BFD                       | Desktop     | [ff12a04779](https://linux-hardware.org/?probe=ff12a04779) | Jan 10, 2024 |
| Dell          | System Inspiron N7110       | Notebook    | [4b3ae60a61](https://linux-hardware.org/?probe=4b3ae60a61) | Jan 10, 2024 |
| ASUSTek       | A88XM-A                     | Desktop     | [50b476ac09](https://linux-hardware.org/?probe=50b476ac09) | Jan 09, 2024 |
| HJS           | OPSH110D4                   | Desktop     | [b604539d33](https://linux-hardware.org/?probe=b604539d33) | Jan 09, 2024 |
| ICL           | H510SB-TM v2.0              | All in one  | [f0308ce995](https://linux-hardware.org/?probe=f0308ce995) | Jan 09, 2024 |
| ECS           | H61H2-M12                   | Desktop     | [a5b967dfc4](https://linux-hardware.org/?probe=a5b967dfc4) | Jan 09, 2024 |
| Gigabyte      | GA-A55M-S2HP                | Desktop     | [ca456b55a8](https://linux-hardware.org/?probe=ca456b55a8) | Jan 08, 2024 |
| Samsung       | N145P/N250P/N260P           | Notebook    | [42f3dc5b5b](https://linux-hardware.org/?probe=42f3dc5b5b) | Jan 08, 2024 |
| Packard Be... | EasyNote ENTE70BH           | Notebook    | [686528b2b8](https://linux-hardware.org/?probe=686528b2b8) | Jan 08, 2024 |
| MSI           | Katana GF76 11SC            | Notebook    | [e85c0b091c](https://linux-hardware.org/?probe=e85c0b091c) | Jan 08, 2024 |
| ASUSTek       | M2N-VM HDMI                 | Desktop     | [ea20cecd28](https://linux-hardware.org/?probe=ea20cecd28) | Jan 08, 2024 |
| Lenovo        | B560                        | Notebook    | [900be0c575](https://linux-hardware.org/?probe=900be0c575) | Jan 08, 2024 |
| ASUSTek       | T100TA                      | Notebook    | [6c102638a9](https://linux-hardware.org/?probe=6c102638a9) | Jan 08, 2024 |
| Acer          | Aspire 5520                 | Notebook    | [0a5ec0c310](https://linux-hardware.org/?probe=0a5ec0c310) | Jan 08, 2024 |
| ASUSTek       | X551MA                      | Notebook    | [243ad8414b](https://linux-hardware.org/?probe=243ad8414b) | Jan 08, 2024 |
| Gigabyte      | B450 GAMING X               | Desktop     | [4ee36f49f1](https://linux-hardware.org/?probe=4ee36f49f1) | Jan 07, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [9233f4fdcb](https://linux-hardware.org/?probe=9233f4fdcb) | Jan 07, 2024 |
| Acer          | Aspire 7739ZG               | Notebook    | [62dc64989b](https://linux-hardware.org/?probe=62dc64989b) | Jan 07, 2024 |
| Unknown       | C51PVGM-M                   | Desktop     | [a652ef8499](https://linux-hardware.org/?probe=a652ef8499) | Jan 07, 2024 |
| Gigabyte      | B450M H                     | Desktop     | [1a3c2a5a40](https://linux-hardware.org/?probe=1a3c2a5a40) | Jan 07, 2024 |
| ASUSTek       | A88X-PLUS/USB               | Desktop     | [7eed61fd57](https://linux-hardware.org/?probe=7eed61fd57) | Jan 07, 2024 |
| ASUSTek       | A88X-PLUS/USB               | Desktop     | [69c24e28a0](https://linux-hardware.org/?probe=69c24e28a0) | Jan 07, 2024 |
| ASUSTek       | P7H55-M                     | Desktop     | [36fc37c5b9](https://linux-hardware.org/?probe=36fc37c5b9) | Jan 06, 2024 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [62f182c46e](https://linux-hardware.org/?probe=62f182c46e) | Jan 06, 2024 |
| Unknown       | C51PVGM-M                   | Desktop     | [cfe5df72f8](https://linux-hardware.org/?probe=cfe5df72f8) | Jan 06, 2024 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [3a2e5d320d](https://linux-hardware.org/?probe=3a2e5d320d) | Jan 06, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [3be696b6a2](https://linux-hardware.org/?probe=3be696b6a2) | Jan 06, 2024 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [db402d3717](https://linux-hardware.org/?probe=db402d3717) | Jan 05, 2024 |
| HP            | EliteBook 840 G4            | Notebook    | [2831ef8f2f](https://linux-hardware.org/?probe=2831ef8f2f) | Jan 05, 2024 |
| ASUSTek       | M51Sn                       | Notebook    | [909c38ed4b](https://linux-hardware.org/?probe=909c38ed4b) | Jan 05, 2024 |
| MSI           | A520M-A PRO                 | Desktop     | [73e4418e17](https://linux-hardware.org/?probe=73e4418e17) | Jan 05, 2024 |
| TopStar       | V211 C                      | Desktop     | [d056c50760](https://linux-hardware.org/?probe=d056c50760) | Jan 05, 2024 |
| Clevo         | W760T/M740T/M760T           | Notebook    | [1b63264977](https://linux-hardware.org/?probe=1b63264977) | Jan 05, 2024 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [0350f7e562](https://linux-hardware.org/?probe=0350f7e562) | Jan 05, 2024 |
| MSI           | H110M PRO-VD                | Desktop     | [bd9f1e7d54](https://linux-hardware.org/?probe=bd9f1e7d54) | Jan 05, 2024 |
| Lenovo        | G470 20078                  | Notebook    | [e9f6af483a](https://linux-hardware.org/?probe=e9f6af483a) | Jan 05, 2024 |
| Huanan        | X99-TF GAMING V3.0          | Desktop     | [1d01b72d8c](https://linux-hardware.org/?probe=1d01b72d8c) | Jan 05, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [96f32abb26](https://linux-hardware.org/?probe=96f32abb26) | Jan 05, 2024 |
| HP            | Compaq Presario CQ50        | Notebook    | [593df08bff](https://linux-hardware.org/?probe=593df08bff) | Jan 05, 2024 |
| Clevo         | NL41MU2                     | Notebook    | [c45b51ce3f](https://linux-hardware.org/?probe=c45b51ce3f) | Jan 05, 2024 |
| HP            | Compaq Presario CQ50        | Notebook    | [1b67d7fdc7](https://linux-hardware.org/?probe=1b67d7fdc7) | Jan 04, 2024 |
| Acer          | Aspire ES1-531              | Notebook    | [d690461c92](https://linux-hardware.org/?probe=d690461c92) | Jan 04, 2024 |
| Acer          | Aspire ES1-531              | Notebook    | [cb353673fe](https://linux-hardware.org/?probe=cb353673fe) | Jan 04, 2024 |
| MSI           | H61M-P21                    | Desktop     | [7d4774aa97](https://linux-hardware.org/?probe=7d4774aa97) | Jan 04, 2024 |
| ASUSTek       | K40IN                       | Notebook    | [3652028e43](https://linux-hardware.org/?probe=3652028e43) | Jan 04, 2024 |
| Gigabyte      | B560M DS3H                  | Desktop     | [dbf5b389e1](https://linux-hardware.org/?probe=dbf5b389e1) | Jan 04, 2024 |
| Acer          | Aspire A715-71G             | Notebook    | [47783802e5](https://linux-hardware.org/?probe=47783802e5) | Jan 04, 2024 |
| Dell          | Latitude D630               | Notebook    | [e48315d3aa](https://linux-hardware.org/?probe=e48315d3aa) | Jan 04, 2024 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [aeb9554ba6](https://linux-hardware.org/?probe=aeb9554ba6) | Jan 03, 2024 |
| AZW           | MINI S 10                   | Desktop     | [6f5bb65726](https://linux-hardware.org/?probe=6f5bb65726) | Jan 03, 2024 |
| ASUSTek       | P7H55-M SI                  | Desktop     | [55390181a6](https://linux-hardware.org/?probe=55390181a6) | Jan 03, 2024 |
| Gigabyte      | 8PEMT4                      | Desktop     | [d07fa4ad02](https://linux-hardware.org/?probe=d07fa4ad02) | Jan 03, 2024 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | Notebook    | [9ebfe6bfaf](https://linux-hardware.org/?probe=9ebfe6bfaf) | Jan 03, 2024 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [38b88634a4](https://linux-hardware.org/?probe=38b88634a4) | Jan 03, 2024 |
| ASUSTek       | P7H55-M SI                  | Desktop     | [63538d3917](https://linux-hardware.org/?probe=63538d3917) | Jan 02, 2024 |
| ASUSTek       | P53SJ                       | Notebook    | [166aa26cbf](https://linux-hardware.org/?probe=166aa26cbf) | Jan 02, 2024 |
| ASUSTek       | P53SJ                       | Notebook    | [b4d6eb4321](https://linux-hardware.org/?probe=b4d6eb4321) | Jan 02, 2024 |
| ASUSTek       | M5A78L-M LE/USB3            | Desktop     | [6a8af45aab](https://linux-hardware.org/?probe=6a8af45aab) | Jan 02, 2024 |
| Acer          | AO531h                      | Notebook    | [d53e1252c6](https://linux-hardware.org/?probe=d53e1252c6) | Jan 02, 2024 |
| ASUSTek       | P5LD2                       | Desktop     | [19abe4bb6a](https://linux-hardware.org/?probe=19abe4bb6a) | Jan 02, 2024 |
| 3Q            | 3QLAP-ES1001N-WBN6-MB       | Notebook    | [d0a86ccf9e](https://linux-hardware.org/?probe=d0a86ccf9e) | Jan 02, 2024 |
| ASUSTek       | P5QL                        | Desktop     | [723455abf9](https://linux-hardware.org/?probe=723455abf9) | Jan 02, 2024 |
| ECS           | GLKD-I2                     | Desktop     | [97247e0a90](https://linux-hardware.org/?probe=97247e0a90) | Jan 02, 2024 |
| Gigabyte      | B560M DS3H                  | Desktop     | [4ff670c80b](https://linux-hardware.org/?probe=4ff670c80b) | Jan 02, 2024 |
| Gigabyte      | B560M DS3H                  | Desktop     | [1529597f3c](https://linux-hardware.org/?probe=1529597f3c) | Jan 02, 2024 |
| Chuwi         | HeroBook Pro                | Notebook    | [97c2ff9710](https://linux-hardware.org/?probe=97c2ff9710) | Jan 01, 2024 |
| ASRock        | J3355M                      | Desktop     | [305d025c0f](https://linux-hardware.org/?probe=305d025c0f) | Jan 01, 2024 |
| Sony          | VPCEH3P1R                   | Notebook    | [d5a18ec675](https://linux-hardware.org/?probe=d5a18ec675) | Jan 01, 2024 |
| ASUSTek       | X555LB                      | Notebook    | [6e12fcec56](https://linux-hardware.org/?probe=6e12fcec56) | Jan 01, 2024 |
| Lenovo        | ThinkPad T430 2349SB4       | Notebook    | [06956b900b](https://linux-hardware.org/?probe=06956b900b) | Jan 01, 2024 |
| ASRock        | H97M Pro4                   | Desktop     | [3955acda3d](https://linux-hardware.org/?probe=3955acda3d) | Dec 31, 2023 |
| Acer          | WMCP78M                     | Desktop     | [e2d232fa11](https://linux-hardware.org/?probe=e2d232fa11) | Dec 31, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [c341d04885](https://linux-hardware.org/?probe=c341d04885) | Dec 31, 2023 |
| Acer          | Extensa 5220                | Notebook    | [dd3638713e](https://linux-hardware.org/?probe=dd3638713e) | Dec 31, 2023 |
| ASUSTek       | PRIME B360M-K               | Desktop     | [d333516660](https://linux-hardware.org/?probe=d333516660) | Dec 31, 2023 |
| ASUSTek       | M2N-VM HDMI                 | Desktop     | [3429c969a5](https://linux-hardware.org/?probe=3429c969a5) | Dec 30, 2023 |
| ASUSTek       | M2N-VM HDMI                 | Desktop     | [e90dfa13e1](https://linux-hardware.org/?probe=e90dfa13e1) | Dec 30, 2023 |
| Intel         | ChiefRiver                  | Notebook    | [6fc4ceeaa6](https://linux-hardware.org/?probe=6fc4ceeaa6) | Dec 30, 2023 |
| MSI           | B450M-A PRO MAX II          | Desktop     | [3698a044ca](https://linux-hardware.org/?probe=3698a044ca) | Dec 30, 2023 |
| ASUSTek       | A88XM-A                     | Desktop     | [175ef5b9a8](https://linux-hardware.org/?probe=175ef5b9a8) | Dec 30, 2023 |
| ASRock        | J4125M                      | Desktop     | [59f93c9ec4](https://linux-hardware.org/?probe=59f93c9ec4) | Dec 30, 2023 |
| HP            | 1494                        | Desktop     | [a7618ec01a](https://linux-hardware.org/?probe=a7618ec01a) | Dec 30, 2023 |
| ASUSTek       | K52JB                       | Notebook    | [169f787cff](https://linux-hardware.org/?probe=169f787cff) | Dec 30, 2023 |
| HP            | ProBook 6460b               | Notebook    | [45038d4599](https://linux-hardware.org/?probe=45038d4599) | Dec 30, 2023 |
| Acer          | Aspire A715-75G             | Notebook    | [753b419047](https://linux-hardware.org/?probe=753b419047) | Dec 30, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [d82dad2793](https://linux-hardware.org/?probe=d82dad2793) | Dec 29, 2023 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [d2c1896794](https://linux-hardware.org/?probe=d2c1896794) | Dec 29, 2023 |
| Lenovo        | Annapurna CRB NOK           | Desktop     | [1e5fb94730](https://linux-hardware.org/?probe=1e5fb94730) | Dec 29, 2023 |
| Lenovo        | XiaoXinPro 16 IRH8 83AQ     | Notebook    | [e21e415784](https://linux-hardware.org/?probe=e21e415784) | Dec 29, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [7b33e176ed](https://linux-hardware.org/?probe=7b33e176ed) | Dec 29, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [fdcf9374ad](https://linux-hardware.org/?probe=fdcf9374ad) | Dec 29, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [eee070b636](https://linux-hardware.org/?probe=eee070b636) | Dec 29, 2023 |
| ASRock        | H97M Pro4                   | Desktop     | [6069654b2c](https://linux-hardware.org/?probe=6069654b2c) | Dec 28, 2023 |
| MSI           | 890FXA-GD70                 | Desktop     | [f97a148a6d](https://linux-hardware.org/?probe=f97a148a6d) | Dec 28, 2023 |
| Gigabyte      | GA-MA69G-S3H                | Desktop     | [25eaed96f5](https://linux-hardware.org/?probe=25eaed96f5) | Dec 28, 2023 |
| HIPER Tech... | HIPER WORKBOOK              | Notebook    | [ddca4cca74](https://linux-hardware.org/?probe=ddca4cca74) | Dec 28, 2023 |
| ASUSTek       | PN42                        | Mini pc     | [82596ed00d](https://linux-hardware.org/?probe=82596ed00d) | Dec 28, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [51d90b2126](https://linux-hardware.org/?probe=51d90b2126) | Dec 28, 2023 |
| Lenovo        | ThinkPad L520 5017AD1       | Notebook    | [93cc8d014a](https://linux-hardware.org/?probe=93cc8d014a) | Dec 28, 2023 |
| Toshiba       | Satellite A200              | Notebook    | [081782c544](https://linux-hardware.org/?probe=081782c544) | Dec 28, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [9c498442e0](https://linux-hardware.org/?probe=9c498442e0) | Dec 28, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [274273301c](https://linux-hardware.org/?probe=274273301c) | Dec 28, 2023 |
| Intel         | D410PT AAE76528-404         | Desktop     | [14f9de700a](https://linux-hardware.org/?probe=14f9de700a) | Dec 27, 2023 |
| ASUSTek       | X200LA                      | Notebook    | [e7eb756fbf](https://linux-hardware.org/?probe=e7eb756fbf) | Dec 27, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [6061821ba9](https://linux-hardware.org/?probe=6061821ba9) | Dec 27, 2023 |
| ASUSTek       | M2NPV-VM                    | Desktop     | [98103e5513](https://linux-hardware.org/?probe=98103e5513) | Dec 27, 2023 |
| Lenovo        | ThinkPad T480 20L50007RT    | Notebook    | [17df248bb2](https://linux-hardware.org/?probe=17df248bb2) | Dec 27, 2023 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [1d40495aae](https://linux-hardware.org/?probe=1d40495aae) | Dec 27, 2023 |
| ASUSTek       | F3Ke                        | Notebook    | [22f515ae42](https://linux-hardware.org/?probe=22f515ae42) | Dec 26, 2023 |
| MSI           | MPG B560I GAMING EDGE WI... | Desktop     | [36ca57b5f2](https://linux-hardware.org/?probe=36ca57b5f2) | Dec 26, 2023 |
| HJS           | OPSADLPA07                  | Desktop     | [2a502cf786](https://linux-hardware.org/?probe=2a502cf786) | Dec 26, 2023 |
| ASUSTek       | P5QL                        | Desktop     | [3e67d03984](https://linux-hardware.org/?probe=3e67d03984) | Dec 26, 2023 |
| Sony          | VGC-LT1SR                   | Notebook    | [680780a4de](https://linux-hardware.org/?probe=680780a4de) | Dec 26, 2023 |
| Sony          | VGC-LT1SR                   | Notebook    | [2a7c712f76](https://linux-hardware.org/?probe=2a7c712f76) | Dec 26, 2023 |
| MSI           | GE70 0NC\0ND                | Notebook    | [ffc8a3bf6d](https://linux-hardware.org/?probe=ffc8a3bf6d) | Dec 26, 2023 |
| ASUSTek       | GL553VE                     | Notebook    | [19d431f40e](https://linux-hardware.org/?probe=19d431f40e) | Dec 25, 2023 |
| Lenovo        | B590 20206                  | Notebook    | [c0fb6339e4](https://linux-hardware.org/?probe=c0fb6339e4) | Dec 25, 2023 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [81d482c238](https://linux-hardware.org/?probe=81d482c238) | Dec 25, 2023 |
| HP            | 82FE 11                     | Desktop     | [e9d77b121e](https://linux-hardware.org/?probe=e9d77b121e) | Dec 25, 2023 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [77da0ba60c](https://linux-hardware.org/?probe=77da0ba60c) | Dec 25, 2023 |
| AZW           | T4 PRO                      | Desktop     | [2b34c0a2cc](https://linux-hardware.org/?probe=2b34c0a2cc) | Dec 25, 2023 |
| ASUSTek       | P5LD2                       | Desktop     | [d7be999894](https://linux-hardware.org/?probe=d7be999894) | Dec 25, 2023 |
| Lenovo        | Annapurna CRB NOK           | Desktop     | [2cf0a3c6b7](https://linux-hardware.org/?probe=2cf0a3c6b7) | Dec 25, 2023 |
| Acer          | Aspire E5-571G              | Notebook    | [5004570f44](https://linux-hardware.org/?probe=5004570f44) | Dec 24, 2023 |
| Acer          | Aspire E5-571G              | Notebook    | [b62ffffcdb](https://linux-hardware.org/?probe=b62ffffcdb) | Dec 24, 2023 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [c37ceeb88e](https://linux-hardware.org/?probe=c37ceeb88e) | Dec 24, 2023 |
| ASUSTek       | P5QL                        | Desktop     | [3f5460760f](https://linux-hardware.org/?probe=3f5460760f) | Dec 24, 2023 |
| ASUSTek       | A88XM-A                     | Desktop     | [34a574fc4f](https://linux-hardware.org/?probe=34a574fc4f) | Dec 24, 2023 |
| HP            | ProBook 430 G2              | Notebook    | [e383d83cd9](https://linux-hardware.org/?probe=e383d83cd9) | Dec 24, 2023 |
| MSI           | 770-C45                     | Desktop     | [5aa1ef152a](https://linux-hardware.org/?probe=5aa1ef152a) | Dec 24, 2023 |
| ASUSTek       | P5B-VM SE                   | Desktop     | [7a453f721a](https://linux-hardware.org/?probe=7a453f721a) | Dec 24, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [4629a1dfe0](https://linux-hardware.org/?probe=4629a1dfe0) | Dec 24, 2023 |
| Notebook      | W65_67SJ                    | Notebook    | [8bea89f7c9](https://linux-hardware.org/?probe=8bea89f7c9) | Dec 24, 2023 |
| Notebook      | W65_67SJ                    | Notebook    | [439816e10c](https://linux-hardware.org/?probe=439816e10c) | Dec 24, 2023 |
| MSI           | 770-C45                     | Desktop     | [b627deabe4](https://linux-hardware.org/?probe=b627deabe4) | Dec 24, 2023 |
| Dell          | Latitude E4310              | Notebook    | [0c4f2ab6b3](https://linux-hardware.org/?probe=0c4f2ab6b3) | Dec 23, 2023 |
| MSI           | H110M PRO-D                 | Desktop     | [7a442e82cf](https://linux-hardware.org/?probe=7a442e82cf) | Dec 23, 2023 |
| ASUSTek       | U5A                         | Notebook    | [fd3c48af54](https://linux-hardware.org/?probe=fd3c48af54) | Dec 23, 2023 |
| ASUSTek       | N53SV                       | Notebook    | [5098aee09b](https://linux-hardware.org/?probe=5098aee09b) | Dec 23, 2023 |
| ASUSTek       | N53SV                       | Notebook    | [5ad49bc6d3](https://linux-hardware.org/?probe=5ad49bc6d3) | Dec 23, 2023 |
| ASUSTek       | P5B-VM SE                   | Desktop     | [4640d8f333](https://linux-hardware.org/?probe=4640d8f333) | Dec 23, 2023 |
| MSI           | H110M PRO-D                 | Desktop     | [10257919e4](https://linux-hardware.org/?probe=10257919e4) | Dec 23, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [29bb247885](https://linux-hardware.org/?probe=29bb247885) | Dec 23, 2023 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [a7ad5fb789](https://linux-hardware.org/?probe=a7ad5fb789) | Dec 23, 2023 |
| MSI           | 890FXA-GD70                 | Desktop     | [1093dc8236](https://linux-hardware.org/?probe=1093dc8236) | Dec 23, 2023 |
| Dell          | 0Y5DDC A00                  | Desktop     | [7ab5ac3907](https://linux-hardware.org/?probe=7ab5ac3907) | Dec 23, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [541c5efbf3](https://linux-hardware.org/?probe=541c5efbf3) | Dec 23, 2023 |
| Dell          | System XPS L702X            | Notebook    | [d69355a342](https://linux-hardware.org/?probe=d69355a342) | Dec 23, 2023 |
| Dell          | Inspiron N5050              | Notebook    | [51b49fb205](https://linux-hardware.org/?probe=51b49fb205) | Dec 22, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [ccf505804c](https://linux-hardware.org/?probe=ccf505804c) | Dec 22, 2023 |
| HP            | ProBook 4330s               | Notebook    | [fce67d52c0](https://linux-hardware.org/?probe=fce67d52c0) | Dec 22, 2023 |
| Acer          | Aspire 5920G                | Notebook    | [93945148f3](https://linux-hardware.org/?probe=93945148f3) | Dec 22, 2023 |
| HP            | 1495                        | Desktop     | [475715312b](https://linux-hardware.org/?probe=475715312b) | Dec 22, 2023 |
| ASUSTek       | SABERTOOTH 990FX R3.0       | Desktop     | [a1a6c29257](https://linux-hardware.org/?probe=a1a6c29257) | Dec 22, 2023 |
| ASUSTek       | P7P55D PRO                  | Desktop     | [ce940a8975](https://linux-hardware.org/?probe=ce940a8975) | Dec 22, 2023 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [4bf5538ba0](https://linux-hardware.org/?probe=4bf5538ba0) | Dec 22, 2023 |
| ASUSTek       | X553MA                      | Notebook    | [af944b3278](https://linux-hardware.org/?probe=af944b3278) | Dec 22, 2023 |
| ASUSTek       | X553MA                      | Notebook    | [ccc1d214ce](https://linux-hardware.org/?probe=ccc1d214ce) | Dec 22, 2023 |
| LG Electro... | F1-2A85R                    | Notebook    | [06bdffa7cc](https://linux-hardware.org/?probe=06bdffa7cc) | Dec 21, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [7a1be2ed24](https://linux-hardware.org/?probe=7a1be2ed24) | Dec 21, 2023 |
| Acer          | Aspire ES1-531              | Notebook    | [0bacfb8ebc](https://linux-hardware.org/?probe=0bacfb8ebc) | Dec 21, 2023 |
| Acer          | Aspire ES1-531              | Notebook    | [14e802a51f](https://linux-hardware.org/?probe=14e802a51f) | Dec 21, 2023 |
| ASUSTek       | X540LA                      | Notebook    | [ae9a60ec08](https://linux-hardware.org/?probe=ae9a60ec08) | Dec 21, 2023 |
| INTECH PRO    | H510-M2 v5.0                | Desktop     | [9d99caa058](https://linux-hardware.org/?probe=9d99caa058) | Dec 21, 2023 |
| Intel         | SKYBAY                      | Desktop     | [36f317de81](https://linux-hardware.org/?probe=36f317de81) | Dec 21, 2023 |
| ASUSTek       | K53SM                       | Notebook    | [7af945d0af](https://linux-hardware.org/?probe=7af945d0af) | Dec 21, 2023 |
| ASUSTek       | M2NPV-VM                    | Desktop     | [312d56f544](https://linux-hardware.org/?probe=312d56f544) | Dec 21, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [4294629777](https://linux-hardware.org/?probe=4294629777) | Dec 21, 2023 |
| MSI           | 770-C45                     | Desktop     | [cf5f865e2a](https://linux-hardware.org/?probe=cf5f865e2a) | Dec 21, 2023 |
| Lenovo        | ThinkPad T530 239233G       | Notebook    | [83d94e2acb](https://linux-hardware.org/?probe=83d94e2acb) | Dec 20, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [c983a4857a](https://linux-hardware.org/?probe=c983a4857a) | Dec 20, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [70aa06688c](https://linux-hardware.org/?probe=70aa06688c) | Dec 20, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [cec4f5fa78](https://linux-hardware.org/?probe=cec4f5fa78) | Dec 20, 2023 |
| Intel         | SKYBAY                      | Desktop     | [09a66cdc69](https://linux-hardware.org/?probe=09a66cdc69) | Dec 20, 2023 |
| ASUSTek       | P7P55D PRO                  | Desktop     | [15f5598650](https://linux-hardware.org/?probe=15f5598650) | Dec 20, 2023 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [0e95772674](https://linux-hardware.org/?probe=0e95772674) | Dec 19, 2023 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [f2d2625715](https://linux-hardware.org/?probe=f2d2625715) | Dec 19, 2023 |
| AZW           | MINI S 10                   | Desktop     | [9fd8cc1993](https://linux-hardware.org/?probe=9fd8cc1993) | Dec 19, 2023 |
| Acer          | Nitro AN515-56              | Notebook    | [3fb0406c18](https://linux-hardware.org/?probe=3fb0406c18) | Dec 19, 2023 |
| ASUSTek       | N73Jn                       | Notebook    | [75d7e7434d](https://linux-hardware.org/?probe=75d7e7434d) | Dec 19, 2023 |
| ICL           | H510SB-TM v2.0              | All in one  | [8dde4765f9](https://linux-hardware.org/?probe=8dde4765f9) | Dec 19, 2023 |
| ICL           | H510SB-TM v2.0              | All in one  | [11e4d48e66](https://linux-hardware.org/?probe=11e4d48e66) | Dec 19, 2023 |
| DNS           | V40SI2                      | Notebook    | [cc28f4eaa2](https://linux-hardware.org/?probe=cc28f4eaa2) | Dec 19, 2023 |
| MSI           | B360-A PRO                  | Desktop     | [a19733520c](https://linux-hardware.org/?probe=a19733520c) | Dec 19, 2023 |
| ASUSTek       | N56DP                       | Notebook    | [736ba321d5](https://linux-hardware.org/?probe=736ba321d5) | Dec 18, 2023 |
| Acer          | Aspire E1-522               | Notebook    | [874bdf3d31](https://linux-hardware.org/?probe=874bdf3d31) | Dec 18, 2023 |
| ASUSTek       | STRIX X99 GAMING            | Desktop     | [4becb790c2](https://linux-hardware.org/?probe=4becb790c2) | Dec 18, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [3d0c812852](https://linux-hardware.org/?probe=3d0c812852) | Dec 18, 2023 |
| Acer          | Aspire A114-33              | Notebook    | [0d1dc00e78](https://linux-hardware.org/?probe=0d1dc00e78) | Dec 18, 2023 |
| Toshiba       | Satellite Pro C660          | Notebook    | [8d45441911](https://linux-hardware.org/?probe=8d45441911) | Dec 18, 2023 |
| Maibenben     | MaiBook P series            | Notebook    | [6bd05cc6a1](https://linux-hardware.org/?probe=6bd05cc6a1) | Dec 18, 2023 |
| HP            | Pavilion dv6                | Notebook    | [604417783f](https://linux-hardware.org/?probe=604417783f) | Dec 18, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [31d86d4507](https://linux-hardware.org/?probe=31d86d4507) | Dec 18, 2023 |
| Dell          | Studio 1535                 | Notebook    | [06e18b7a2f](https://linux-hardware.org/?probe=06e18b7a2f) | Dec 18, 2023 |
| ASUSTek       | P5LD2                       | Desktop     | [6b2cff0ab3](https://linux-hardware.org/?probe=6b2cff0ab3) | Dec 18, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [7bf2e8159e](https://linux-hardware.org/?probe=7bf2e8159e) | Dec 18, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [4c190c150c](https://linux-hardware.org/?probe=4c190c150c) | Dec 18, 2023 |
| Fujitsu Si... | LIFEBOOK S6410              | Notebook    | [24edc4b12c](https://linux-hardware.org/?probe=24edc4b12c) | Dec 17, 2023 |
| Dell          | System Inspiron N7110       | Notebook    | [b1f392f5f3](https://linux-hardware.org/?probe=b1f392f5f3) | Dec 17, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [d346ec3767](https://linux-hardware.org/?probe=d346ec3767) | Dec 17, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [0e123e0682](https://linux-hardware.org/?probe=0e123e0682) | Dec 16, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [c67f7d8341](https://linux-hardware.org/?probe=c67f7d8341) | Dec 16, 2023 |
| Lenovo        | B590 20206                  | Notebook    | [b6afc3e929](https://linux-hardware.org/?probe=b6afc3e929) | Dec 16, 2023 |
| Toshiba       | Satellite U300              | Notebook    | [f8f967d0fe](https://linux-hardware.org/?probe=f8f967d0fe) | Dec 16, 2023 |
| AZW           | MINI S 10                   | Desktop     | [c3fcd194a9](https://linux-hardware.org/?probe=c3fcd194a9) | Dec 16, 2023 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [26e619e2e4](https://linux-hardware.org/?probe=26e619e2e4) | Dec 16, 2023 |
| Samsung       | R528/R728                   | Notebook    | [3a61761648](https://linux-hardware.org/?probe=3a61761648) | Dec 16, 2023 |
| AZW           | MINI S 10                   | Desktop     | [eae1cb11b4](https://linux-hardware.org/?probe=eae1cb11b4) | Dec 16, 2023 |
| AZW           | MINI S 10                   | Desktop     | [8d0d99e3ca](https://linux-hardware.org/?probe=8d0d99e3ca) | Dec 15, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [7042699eef](https://linux-hardware.org/?probe=7042699eef) | Dec 15, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [e07df321e3](https://linux-hardware.org/?probe=e07df321e3) | Dec 15, 2023 |
| Sony          | VGN-FW11ER                  | Notebook    | [eead7d1cca](https://linux-hardware.org/?probe=eead7d1cca) | Dec 15, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [35e6b7852f](https://linux-hardware.org/?probe=35e6b7852f) | Dec 14, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [e3a708296c](https://linux-hardware.org/?probe=e3a708296c) | Dec 14, 2023 |
| Dell          | Studio 1535                 | Notebook    | [0fd7468ec1](https://linux-hardware.org/?probe=0fd7468ec1) | Dec 14, 2023 |
| MSI           | G41M-P26                    | Desktop     | [fea030b929](https://linux-hardware.org/?probe=fea030b929) | Dec 14, 2023 |
| HP            | Notebook                    | Notebook    | [ac92e1373d](https://linux-hardware.org/?probe=ac92e1373d) | Dec 14, 2023 |
| Gigabyte      | X38-DQ6                     | Desktop     | [67c13b1f2a](https://linux-hardware.org/?probe=67c13b1f2a) | Dec 14, 2023 |
| ASRock        | Z68 Pro3                    | Desktop     | [0f58876ad4](https://linux-hardware.org/?probe=0f58876ad4) | Dec 14, 2023 |
| Acer          | AO521                       | Notebook    | [e519cc3d02](https://linux-hardware.org/?probe=e519cc3d02) | Dec 14, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [7e77c20625](https://linux-hardware.org/?probe=7e77c20625) | Dec 14, 2023 |
| MSI           | B460M PRO-VDH               | Desktop     | [262206ab21](https://linux-hardware.org/?probe=262206ab21) | Dec 14, 2023 |
| Acer          | AO521                       | Notebook    | [0dd76d9c3a](https://linux-hardware.org/?probe=0dd76d9c3a) | Dec 14, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [f40c7514a6](https://linux-hardware.org/?probe=f40c7514a6) | Dec 14, 2023 |
| HP            | ProBook 6560b               | Notebook    | [e103647ee9](https://linux-hardware.org/?probe=e103647ee9) | Dec 13, 2023 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [004355ae40](https://linux-hardware.org/?probe=004355ae40) | Dec 13, 2023 |
| Intel         | DZ68DB AAG27985-105         | Desktop     | [7df70f0023](https://linux-hardware.org/?probe=7df70f0023) | Dec 13, 2023 |
| ASUSTek       | B85-PLUS                    | Desktop     | [0baafe2f04](https://linux-hardware.org/?probe=0baafe2f04) | Dec 13, 2023 |
| Lenovo        | Annapurna CRB NOK           | Desktop     | [2207f3a9a1](https://linux-hardware.org/?probe=2207f3a9a1) | Dec 12, 2023 |
| ASUSTek       | B75M-PLUS                   | Desktop     | [03dcd079c2](https://linux-hardware.org/?probe=03dcd079c2) | Dec 12, 2023 |
| Digma         | EVE 14 C411                 | Notebook    | [bcd7c864a1](https://linux-hardware.org/?probe=bcd7c864a1) | Dec 12, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [885e6000e2](https://linux-hardware.org/?probe=885e6000e2) | Dec 12, 2023 |
| Lenovo        | ThinkPad Z61t 9441W15       | Notebook    | [af90f6fb00](https://linux-hardware.org/?probe=af90f6fb00) | Dec 11, 2023 |
| ASUSTek       | P7H55                       | Desktop     | [3642e15edd](https://linux-hardware.org/?probe=3642e15edd) | Dec 11, 2023 |
| Acer          | Aspire E1-572G              | Notebook    | [c087547192](https://linux-hardware.org/?probe=c087547192) | Dec 11, 2023 |
| Acer          | Aspire E1-572G              | Notebook    | [5347b71932](https://linux-hardware.org/?probe=5347b71932) | Dec 11, 2023 |
| ASRock        | N68C-GS FX                  | Desktop     | [a23bf3790b](https://linux-hardware.org/?probe=a23bf3790b) | Dec 10, 2023 |
| BESSTAR Te... | HM90                        | Desktop     | [6d805d9e86](https://linux-hardware.org/?probe=6d805d9e86) | Dec 10, 2023 |
| eMachines     | eME728                      | Notebook    | [b89ccf8caf](https://linux-hardware.org/?probe=b89ccf8caf) | Dec 09, 2023 |
| eMachines     | eME728                      | Notebook    | [1c6bed2983](https://linux-hardware.org/?probe=1c6bed2983) | Dec 09, 2023 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [9aa2e36112](https://linux-hardware.org/?probe=9aa2e36112) | Dec 09, 2023 |
| MSI           | Katana GF76 12UC            | Notebook    | [6667f9e88d](https://linux-hardware.org/?probe=6667f9e88d) | Dec 08, 2023 |
| HP            | Compaq 610                  | Notebook    | [6104f16206](https://linux-hardware.org/?probe=6104f16206) | Dec 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [85f36603e0](https://linux-hardware.org/?probe=85f36603e0) | Dec 07, 2023 |
| Lenovo        | K14 Gen 1 21CSS16E00        | Notebook    | [b0d96c9e33](https://linux-hardware.org/?probe=b0d96c9e33) | Dec 07, 2023 |
| Edelweiss     | TF307-MB-S-D                | Soc         | [5dcbeffd70](https://linux-hardware.org/?probe=5dcbeffd70) | Dec 07, 2023 |
| Biostar       | A68MHE                      | Desktop     | [28d5e46d68](https://linux-hardware.org/?probe=28d5e46d68) | Dec 07, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [3939d82727](https://linux-hardware.org/?probe=3939d82727) | Dec 07, 2023 |
| Biostar       | A68MHE                      | Desktop     | [adab01b31b](https://linux-hardware.org/?probe=adab01b31b) | Dec 07, 2023 |
| Gigabyte      | E350N WIN8                  | Desktop     | [b5f6aa3741](https://linux-hardware.org/?probe=b5f6aa3741) | Dec 07, 2023 |
| Acer          | TravelMate B118-M           | Notebook    | [22f8658b94](https://linux-hardware.org/?probe=22f8658b94) | Dec 07, 2023 |
| ASRock        | AB350M-HDV R3.0             | Desktop     | [d5c946c229](https://linux-hardware.org/?probe=d5c946c229) | Dec 06, 2023 |
| HUAWEI        | BoDE-WXX9                   | Notebook    | [290f7cf6b8](https://linux-hardware.org/?probe=290f7cf6b8) | Dec 06, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [6b2fb03fb3](https://linux-hardware.org/?probe=6b2fb03fb3) | Dec 06, 2023 |
| Infinix       | INBOOK X3                   | Notebook    | [51e5d10a85](https://linux-hardware.org/?probe=51e5d10a85) | Dec 06, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [d1acc8db3d](https://linux-hardware.org/?probe=d1acc8db3d) | Dec 06, 2023 |
| Lenovo        | 0x30F617AA NOK              | Desktop     | [c57e8b797a](https://linux-hardware.org/?probe=c57e8b797a) | Dec 06, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [a5c872d21f](https://linux-hardware.org/?probe=a5c872d21f) | Dec 06, 2023 |
| ASUSTek       | P7P55-M                     | Desktop     | [f19bc05960](https://linux-hardware.org/?probe=f19bc05960) | Dec 06, 2023 |
| ASUSTek       | M2NPV-VM                    | Desktop     | [63a226690c](https://linux-hardware.org/?probe=63a226690c) | Dec 06, 2023 |
| Intel         | H81 V2.3                    | Desktop     | [708916ead2](https://linux-hardware.org/?probe=708916ead2) | Dec 05, 2023 |
| MSI           | MS-B1711                    | Desktop     | [8c0247cf89](https://linux-hardware.org/?probe=8c0247cf89) | Dec 05, 2023 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [6152f696ba](https://linux-hardware.org/?probe=6152f696ba) | Dec 05, 2023 |
| ASUSTek       | A88XM-A                     | Desktop     | [e91058f8a8](https://linux-hardware.org/?probe=e91058f8a8) | Dec 05, 2023 |
| Acidanther... | MacBookPro16,3              | Notebook    | [58eeb19907](https://linux-hardware.org/?probe=58eeb19907) | Dec 05, 2023 |
| Acidanther... | MacBookPro16,3              | Notebook    | [5a7b70b8e0](https://linux-hardware.org/?probe=5a7b70b8e0) | Dec 05, 2023 |
| ARDOR GAMI... | V15x_V17xRNx                | Notebook    | [ac9b89a2cd](https://linux-hardware.org/?probe=ac9b89a2cd) | Dec 05, 2023 |
| ASRock        | AD2550B-ITX                 | Desktop     | [6e518f6d21](https://linux-hardware.org/?probe=6e518f6d21) | Dec 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [5e0643e419](https://linux-hardware.org/?probe=5e0643e419) | Dec 04, 2023 |
| Gigabyte      | GA-A55M-DS2                 | Desktop     | [479a8762cb](https://linux-hardware.org/?probe=479a8762cb) | Dec 04, 2023 |
| ASUSTek       | X550VC                      | Notebook    | [376ffad1f1](https://linux-hardware.org/?probe=376ffad1f1) | Dec 04, 2023 |
| Gigabyte      | B660 GAMING X DDR4          | Desktop     | [8825d0fec5](https://linux-hardware.org/?probe=8825d0fec5) | Dec 04, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [fbc45d8077](https://linux-hardware.org/?probe=fbc45d8077) | Dec 04, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [1ea135770e](https://linux-hardware.org/?probe=1ea135770e) | Dec 04, 2023 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [61163dcc3a](https://linux-hardware.org/?probe=61163dcc3a) | Dec 04, 2023 |
| HUAWEI        | BoDE-WXX9                   | Notebook    | [28ae7336e2](https://linux-hardware.org/?probe=28ae7336e2) | Dec 03, 2023 |
| Apple         | MacBookAir3,2               | Notebook    | [f3560f311e](https://linux-hardware.org/?probe=f3560f311e) | Dec 03, 2023 |
| ASUSTek       | P5LD2                       | Desktop     | [427dcf0f2e](https://linux-hardware.org/?probe=427dcf0f2e) | Dec 03, 2023 |
| Gigabyte      | Z97-HD3                     | Desktop     | [e2c26c5e1f](https://linux-hardware.org/?probe=e2c26c5e1f) | Dec 03, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [50b53131f2](https://linux-hardware.org/?probe=50b53131f2) | Dec 03, 2023 |
| Irbis         | NB133                       | Notebook    | [b376d8603a](https://linux-hardware.org/?probe=b376d8603a) | Dec 03, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [a8192548ea](https://linux-hardware.org/?probe=a8192548ea) | Dec 03, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [7dab5dd440](https://linux-hardware.org/?probe=7dab5dd440) | Dec 03, 2023 |
| ASRock        | N68C-S UCC                  | Desktop     | [d42ebb9252](https://linux-hardware.org/?probe=d42ebb9252) | Dec 03, 2023 |
| ASRock        | N68C-S UCC                  | Desktop     | [13d2b9187f](https://linux-hardware.org/?probe=13d2b9187f) | Dec 03, 2023 |
| Gigabyte      | MZBAYAP-00                  | Desktop     | [7fb4476167](https://linux-hardware.org/?probe=7fb4476167) | Dec 02, 2023 |
| ASUSTek       | A8N-SLI Premium             | Desktop     | [79f209d7a3](https://linux-hardware.org/?probe=79f209d7a3) | Dec 02, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [e830e69a5d](https://linux-hardware.org/?probe=e830e69a5d) | Dec 02, 2023 |
| ASUSTek       | X75VCP                      | Notebook    | [c4746fbc7c](https://linux-hardware.org/?probe=c4746fbc7c) | Dec 02, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [786b8aae1c](https://linux-hardware.org/?probe=786b8aae1c) | Dec 02, 2023 |
| Graviton      | N15i-T                      | Notebook    | [45f4b45d76](https://linux-hardware.org/?probe=45f4b45d76) | Dec 02, 2023 |
| Graviton      | N15i-T                      | Notebook    | [2dfff446c0](https://linux-hardware.org/?probe=2dfff446c0) | Dec 02, 2023 |
| HP            | ProBook 450 G5              | Notebook    | [695b186626](https://linux-hardware.org/?probe=695b186626) | Dec 02, 2023 |
| LTD Delovo... | EVE 14 C414 NA9144BXW01     | Notebook    | [ef37f773f0](https://linux-hardware.org/?probe=ef37f773f0) | Dec 02, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [13c49517db](https://linux-hardware.org/?probe=13c49517db) | Dec 02, 2023 |
| Acer          | Aspire A315-21              | Notebook    | [a89238478d](https://linux-hardware.org/?probe=a89238478d) | Dec 01, 2023 |
| OEM           | X79G                        | Desktop     | [febfd97ad1](https://linux-hardware.org/?probe=febfd97ad1) | Dec 01, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [4172cccae3](https://linux-hardware.org/?probe=4172cccae3) | Dec 01, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [aaa13df3bd](https://linux-hardware.org/?probe=aaa13df3bd) | Dec 01, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [444b1864c9](https://linux-hardware.org/?probe=444b1864c9) | Dec 01, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [475b7358ee](https://linux-hardware.org/?probe=475b7358ee) | Dec 01, 2023 |
| MSI           | A68HM-P33 V2                | Desktop     | [b1131b7587](https://linux-hardware.org/?probe=b1131b7587) | Dec 01, 2023 |
| Lenovo        | Annapurna CRB NOK           | Desktop     | [9fe0854829](https://linux-hardware.org/?probe=9fe0854829) | Dec 01, 2023 |
| Huanan        | X99 F8D V2.2                | Desktop     | [acc68bea5c](https://linux-hardware.org/?probe=acc68bea5c) | Nov 30, 2023 |
| Toshiba       | Satellite U300              | Notebook    | [9b42ec691e](https://linux-hardware.org/?probe=9b42ec691e) | Nov 30, 2023 |
| MSI           | 770-C45                     | Desktop     | [59a879c475](https://linux-hardware.org/?probe=59a879c475) | Nov 30, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [97b2117c5e](https://linux-hardware.org/?probe=97b2117c5e) | Nov 30, 2023 |
| ECS           | GLKD-I2                     | Desktop     | [05d3dc06a0](https://linux-hardware.org/?probe=05d3dc06a0) | Nov 30, 2023 |
| ASUSTek       | P5KPL-AM                    | Desktop     | [241a9d1cad](https://linux-hardware.org/?probe=241a9d1cad) | Nov 30, 2023 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [bada3a056e](https://linux-hardware.org/?probe=bada3a056e) | Nov 30, 2023 |
| ASUSTek       | P5LD2                       | Desktop     | [7cc743250b](https://linux-hardware.org/?probe=7cc743250b) | Nov 30, 2023 |
| HP            | Pavilion dv6000 (RY647EA... | Notebook    | [9940416812](https://linux-hardware.org/?probe=9940416812) | Nov 30, 2023 |
| Timi          | TM1703                      | Notebook    | [cc3fe6b22b](https://linux-hardware.org/?probe=cc3fe6b22b) | Nov 30, 2023 |
| MSI           | MS-AE671 100                | All in one  | [38865ac8a4](https://linux-hardware.org/?probe=38865ac8a4) | Nov 29, 2023 |
| Acer          | Aspire XC-1660 V:1.1        | Desktop     | [509ae42a22](https://linux-hardware.org/?probe=509ae42a22) | Nov 29, 2023 |
| Intel         | SKYBAY                      | Desktop     | [5734274ccd](https://linux-hardware.org/?probe=5734274ccd) | Nov 29, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [2d7376da77](https://linux-hardware.org/?probe=2d7376da77) | Nov 29, 2023 |
| Gigabyte      | G5 GE                       | Notebook    | [53343f6e05](https://linux-hardware.org/?probe=53343f6e05) | Nov 29, 2023 |
| ARDOR GAMI... | V15x_V17xRNx                | Notebook    | [b711d78ac1](https://linux-hardware.org/?probe=b711d78ac1) | Nov 29, 2023 |
| Gigabyte      | Z270P-D3-CF                 | Desktop     | [9b31bd67fb](https://linux-hardware.org/?probe=9b31bd67fb) | Nov 29, 2023 |
| MSI           | MS-A6181                    | All in one  | [6a4a33e8ac](https://linux-hardware.org/?probe=6a4a33e8ac) | Nov 29, 2023 |
| Gigabyte      | GA-780T-D3L                 | Desktop     | [b3dee75350](https://linux-hardware.org/?probe=b3dee75350) | Nov 29, 2023 |
| ASRock        | J4125M                      | Desktop     | [9e5951e82e](https://linux-hardware.org/?probe=9e5951e82e) | Nov 29, 2023 |
| MSI           | MS-A6181                    | All in one  | [d170bb0bfc](https://linux-hardware.org/?probe=d170bb0bfc) | Nov 29, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [2f1a80ecf8](https://linux-hardware.org/?probe=2f1a80ecf8) | Nov 28, 2023 |
| Timi          | TM1703                      | Notebook    | [87ad7cf4b2](https://linux-hardware.org/?probe=87ad7cf4b2) | Nov 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [cabab02402](https://linux-hardware.org/?probe=cabab02402) | Nov 28, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [d9993e4ca1](https://linux-hardware.org/?probe=d9993e4ca1) | Nov 28, 2023 |
| ICL           | H510SB-TM v2.0              | All in one  | [ca2ecff9cd](https://linux-hardware.org/?probe=ca2ecff9cd) | Nov 28, 2023 |
| HP            | Notebook                    | Notebook    | [3faeeff15b](https://linux-hardware.org/?probe=3faeeff15b) | Nov 28, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [ebd9b385a7](https://linux-hardware.org/?probe=ebd9b385a7) | Nov 28, 2023 |
| Acer          | Aspire A315-51              | Notebook    | [9d08bad421](https://linux-hardware.org/?probe=9d08bad421) | Nov 28, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [2d9e2ea88b](https://linux-hardware.org/?probe=2d9e2ea88b) | Nov 28, 2023 |
| ICL           | H510SB-TM v2.0              | All in one  | [95ef158cea](https://linux-hardware.org/?probe=95ef158cea) | Nov 27, 2023 |
| ECS           | GLKD-I2                     | Desktop     | [c1f9ed7186](https://linux-hardware.org/?probe=c1f9ed7186) | Nov 27, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [972ddcedb5](https://linux-hardware.org/?probe=972ddcedb5) | Nov 27, 2023 |
| Dell          | Vostro 14 5410              | Notebook    | [d8694cd2f4](https://linux-hardware.org/?probe=d8694cd2f4) | Nov 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [2cd14cbfbd](https://linux-hardware.org/?probe=2cd14cbfbd) | Nov 27, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [462be5c161](https://linux-hardware.org/?probe=462be5c161) | Nov 26, 2023 |
| HONOR         | HYM-WXX                     | Notebook    | [ce9c3cc669](https://linux-hardware.org/?probe=ce9c3cc669) | Nov 26, 2023 |
| Gigabyte      | B550M S2H                   | Desktop     | [7084bb6ef8](https://linux-hardware.org/?probe=7084bb6ef8) | Nov 26, 2023 |
| MSI           | MPG Z790 CARBON WIFI        | Desktop     | [81c2675a1e](https://linux-hardware.org/?probe=81c2675a1e) | Nov 26, 2023 |
| HP            | ProBook 6460b               | Notebook    | [d489496b9f](https://linux-hardware.org/?probe=d489496b9f) | Nov 26, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [77e9934d61](https://linux-hardware.org/?probe=77e9934d61) | Nov 26, 2023 |
| ASUSTek       | A88XM-A                     | Desktop     | [1431a6559b](https://linux-hardware.org/?probe=1431a6559b) | Nov 26, 2023 |
| Acer          | Aspire V5-571G              | Notebook    | [325e8c5f4e](https://linux-hardware.org/?probe=325e8c5f4e) | Nov 26, 2023 |
| Lenovo        | G700 20251                  | Notebook    | [786f74858b](https://linux-hardware.org/?probe=786f74858b) | Nov 26, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [87185da0b7](https://linux-hardware.org/?probe=87185da0b7) | Nov 26, 2023 |
| Alienware     | 18                          | Notebook    | [063cb2cb74](https://linux-hardware.org/?probe=063cb2cb74) | Nov 26, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [bfe4912cfd](https://linux-hardware.org/?probe=bfe4912cfd) | Nov 26, 2023 |
| Dell          | 0Y5DDC A00                  | Desktop     | [db9963f44a](https://linux-hardware.org/?probe=db9963f44a) | Nov 26, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [812406c15d](https://linux-hardware.org/?probe=812406c15d) | Nov 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | Notebook    | [977c83a086](https://linux-hardware.org/?probe=977c83a086) | Nov 25, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [09f8fda895](https://linux-hardware.org/?probe=09f8fda895) | Nov 25, 2023 |
| HP            | Notebook                    | Notebook    | [519d55357d](https://linux-hardware.org/?probe=519d55357d) | Nov 25, 2023 |
| Lenovo        | G505 20240                  | Notebook    | [f0b93fcca9](https://linux-hardware.org/?probe=f0b93fcca9) | Nov 25, 2023 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [59a8bda477](https://linux-hardware.org/?probe=59a8bda477) | Nov 25, 2023 |
| HP            | ProBook 4340s               | Notebook    | [15f28b24ae](https://linux-hardware.org/?probe=15f28b24ae) | Nov 25, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [1fb358fc57](https://linux-hardware.org/?probe=1fb358fc57) | Nov 25, 2023 |
| Acer          | Aspire ES1-522              | Notebook    | [b367ec5e53](https://linux-hardware.org/?probe=b367ec5e53) | Nov 25, 2023 |
| HP            | ENVY 17                     | Notebook    | [d4d314c6cb](https://linux-hardware.org/?probe=d4d314c6cb) | Nov 25, 2023 |
| 3Logic Gro... | Graviton N15i               | Notebook    | [a351a9f906](https://linux-hardware.org/?probe=a351a9f906) | Nov 25, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [3fcbbcc16b](https://linux-hardware.org/?probe=3fcbbcc16b) | Nov 24, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [7186bd00ff](https://linux-hardware.org/?probe=7186bd00ff) | Nov 24, 2023 |
| ASUSTek       | N550JK                      | Notebook    | [637d2ba066](https://linux-hardware.org/?probe=637d2ba066) | Nov 24, 2023 |
| ASUSTek       | N750JV                      | Notebook    | [27e9669d13](https://linux-hardware.org/?probe=27e9669d13) | Nov 24, 2023 |
| ASUSTek       | TUF X299 MARK 2             | Desktop     | [bb8bae6a59](https://linux-hardware.org/?probe=bb8bae6a59) | Nov 24, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [f4f0ebc885](https://linux-hardware.org/?probe=f4f0ebc885) | Nov 23, 2023 |
| Acer          | TravelMate P259-MG          | Notebook    | [9ab55a1799](https://linux-hardware.org/?probe=9ab55a1799) | Nov 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 16ARH7 ... | Notebook    | [2c6adf9db4](https://linux-hardware.org/?probe=2c6adf9db4) | Nov 23, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [bbd1246656](https://linux-hardware.org/?probe=bbd1246656) | Nov 23, 2023 |
| Acer          | TravelMate P259-MG          | Notebook    | [aea9b092e1](https://linux-hardware.org/?probe=aea9b092e1) | Nov 23, 2023 |
| ASUSTek       | ROG Strix G834JY_G834JY     | Notebook    | [26a2d5750f](https://linux-hardware.org/?probe=26a2d5750f) | Nov 23, 2023 |
| ASUSTek       | PRIME H510M-R               | Desktop     | [798ff06944](https://linux-hardware.org/?probe=798ff06944) | Nov 23, 2023 |
| SZMZ          | X99 DUAL Z8                 | Desktop     | [aaa9f78cd9](https://linux-hardware.org/?probe=aaa9f78cd9) | Nov 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 16ARH7 ... | Notebook    | [6a200f511c](https://linux-hardware.org/?probe=6a200f511c) | Nov 23, 2023 |
| Unknown       | X79                         | Desktop     | [e66769bf5c](https://linux-hardware.org/?probe=e66769bf5c) | Nov 23, 2023 |
| Alienware     | m15 R7 AMD                  | Notebook    | [92e9ba0c14](https://linux-hardware.org/?probe=92e9ba0c14) | Nov 23, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [fbce369e50](https://linux-hardware.org/?probe=fbce369e50) | Nov 23, 2023 |
| HP            | 21D0                        | Desktop     | [3e85a284ec](https://linux-hardware.org/?probe=3e85a284ec) | Nov 23, 2023 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [b4f7ce646b](https://linux-hardware.org/?probe=b4f7ce646b) | Nov 22, 2023 |
| HP            | Notebook                    | Notebook    | [efccf1789b](https://linux-hardware.org/?probe=efccf1789b) | Nov 22, 2023 |
| ASUSTek       | G75VX                       | Notebook    | [e433e70a9f](https://linux-hardware.org/?probe=e433e70a9f) | Nov 22, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [5b63e87d07](https://linux-hardware.org/?probe=5b63e87d07) | Nov 22, 2023 |
| Biostar       | B550M-SILVER                | Desktop     | [d2502c76d5](https://linux-hardware.org/?probe=d2502c76d5) | Nov 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [f1a988f291](https://linux-hardware.org/?probe=f1a988f291) | Nov 22, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [9e429c4742](https://linux-hardware.org/?probe=9e429c4742) | Nov 22, 2023 |
| ASUSTek       | PRIME B250M-PLUS            | Desktop     | [aad08ec259](https://linux-hardware.org/?probe=aad08ec259) | Nov 22, 2023 |
| ICL           | H510SB-TM v2.0              | All in one  | [2d06a59c08](https://linux-hardware.org/?probe=2d06a59c08) | Nov 22, 2023 |
| HP            | ProBook 6460b               | Notebook    | [0d13c42c84](https://linux-hardware.org/?probe=0d13c42c84) | Nov 21, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [450e29b3a9](https://linux-hardware.org/?probe=450e29b3a9) | Nov 21, 2023 |
| HP            | Compaq Presario CQ50        | Notebook    | [40a3d73ff2](https://linux-hardware.org/?probe=40a3d73ff2) | Nov 21, 2023 |
| LTD Delovo... | 15Y                         | Notebook    | [8d54474ad0](https://linux-hardware.org/?probe=8d54474ad0) | Nov 21, 2023 |
| ICL           | H510SB-TM v2.0              | All in one  | [8eb1f0e198](https://linux-hardware.org/?probe=8eb1f0e198) | Nov 21, 2023 |
| ICL           | H510SB-TM v2.0              | All in one  | [94a4beb104](https://linux-hardware.org/?probe=94a4beb104) | Nov 21, 2023 |
| ASUSTek       | H110M-D                     | Desktop     | [c871779bc5](https://linux-hardware.org/?probe=c871779bc5) | Nov 21, 2023 |
| ASUSTek       | P5B-Premium                 | Desktop     | [53c5d42789](https://linux-hardware.org/?probe=53c5d42789) | Nov 21, 2023 |
| Huanan        | X99 F8D V2.2                | Desktop     | [793263f898](https://linux-hardware.org/?probe=793263f898) | Nov 21, 2023 |
| Samsung       | G25/G26                     | Notebook    | [75ea3e9d1c](https://linux-hardware.org/?probe=75ea3e9d1c) | Nov 21, 2023 |
| MSI           | H310M PRO-VD                | Desktop     | [aabdcbb08a](https://linux-hardware.org/?probe=aabdcbb08a) | Nov 20, 2023 |
| Gigabyte      | B85M-D3V                    | Desktop     | [5a04938662](https://linux-hardware.org/?probe=5a04938662) | Nov 20, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [746b73efa5](https://linux-hardware.org/?probe=746b73efa5) | Nov 20, 2023 |
| Samsung       | G25/G26                     | Notebook    | [4fa1c48bf4](https://linux-hardware.org/?probe=4fa1c48bf4) | Nov 20, 2023 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [8c04d88a1a](https://linux-hardware.org/?probe=8c04d88a1a) | Nov 20, 2023 |
| MSI           | MS-AE061                    | All in one  | [010c31250c](https://linux-hardware.org/?probe=010c31250c) | Nov 20, 2023 |
| MSI           | MS-AE061                    | All in one  | [7c2f8a8c21](https://linux-hardware.org/?probe=7c2f8a8c21) | Nov 20, 2023 |
| Dell          | Vostro1710                  | Notebook    | [a34c5e67aa](https://linux-hardware.org/?probe=a34c5e67aa) | Nov 19, 2023 |
| Dell          | Inspiron 1521               | Notebook    | [0b0507a1ae](https://linux-hardware.org/?probe=0b0507a1ae) | Nov 19, 2023 |
| Lenovo        | ThinkPad T430 23445PU       | Notebook    | [95684da8bd](https://linux-hardware.org/?probe=95684da8bd) | Nov 19, 2023 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [f12026549d](https://linux-hardware.org/?probe=f12026549d) | Nov 19, 2023 |
| Apple         | Mac-F4218FC8 DVT            | All in one  | [c77946bfc6](https://linux-hardware.org/?probe=c77946bfc6) | Nov 19, 2023 |
| Dell          | Latitude E6230              | Notebook    | [92e65f6bca](https://linux-hardware.org/?probe=92e65f6bca) | Nov 19, 2023 |
| ASUSTek       | K53E                        | Notebook    | [8b2b851183](https://linux-hardware.org/?probe=8b2b851183) | Nov 19, 2023 |
| Lenovo        | 3000 V100 076346G           | Notebook    | [039632f3f3](https://linux-hardware.org/?probe=039632f3f3) | Nov 18, 2023 |
| Lenovo        | B560                        | Notebook    | [05bde0afed](https://linux-hardware.org/?probe=05bde0afed) | Nov 18, 2023 |
| ASRock        | G31M-VS                     | Desktop     | [90703790aa](https://linux-hardware.org/?probe=90703790aa) | Nov 18, 2023 |
| Sony          | VGN-NS11ER_S                | Notebook    | [f295aaa7fd](https://linux-hardware.org/?probe=f295aaa7fd) | Nov 18, 2023 |
| Acer          | Aspire 5334                 | Notebook    | [0dcad1d6e0](https://linux-hardware.org/?probe=0dcad1d6e0) | Nov 18, 2023 |
| Gigabyte      | B760M DS3H DDR4             | Desktop     | [dd65d07da5](https://linux-hardware.org/?probe=dd65d07da5) | Nov 17, 2023 |
| MSI           | MS-B0A91                    | Desktop     | [1fd5a38fea](https://linux-hardware.org/?probe=1fd5a38fea) | Nov 17, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [d4e8f3f548](https://linux-hardware.org/?probe=d4e8f3f548) | Nov 17, 2023 |
| ASUSTek       | X101H                       | Notebook    | [d9e12c16e0](https://linux-hardware.org/?probe=d9e12c16e0) | Nov 17, 2023 |
| MSI           | Katana GF76 12UC            | Notebook    | [0f4df1b67e](https://linux-hardware.org/?probe=0f4df1b67e) | Nov 17, 2023 |
| ASRock        | 760GM-GS3                   | Desktop     | [bc38c966fd](https://linux-hardware.org/?probe=bc38c966fd) | Nov 17, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [39179fa6fd](https://linux-hardware.org/?probe=39179fa6fd) | Nov 17, 2023 |
| ASUSTek       | P6X58D-E                    | Desktop     | [79c73471d5](https://linux-hardware.org/?probe=79c73471d5) | Nov 17, 2023 |
| Gigabyte      | B560 HD3                    | Desktop     | [161d0a2dd8](https://linux-hardware.org/?probe=161d0a2dd8) | Nov 17, 2023 |
| ASUSTek       | ZenBook UX435EG_UX435EG     | Notebook    | [01e59bb98c](https://linux-hardware.org/?probe=01e59bb98c) | Nov 16, 2023 |
| ASUSTek       | 1001PXD                     | Notebook    | [6f92b6aa53](https://linux-hardware.org/?probe=6f92b6aa53) | Nov 16, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2164c33a50](https://linux-hardware.org/?probe=2164c33a50) | Nov 16, 2023 |
| HP            | Mini 110-4100               | Notebook    | [a7aaa77ba5](https://linux-hardware.org/?probe=a7aaa77ba5) | Nov 16, 2023 |
| ICL           | H510SB-TM v2.0              | All in one  | [58c58531b8](https://linux-hardware.org/?probe=58c58531b8) | Nov 16, 2023 |
| ICL           | H510SB-TM v2.0              | All in one  | [338b02b538](https://linux-hardware.org/?probe=338b02b538) | Nov 16, 2023 |
| Gigabyte      | H410M S2H V2                | Desktop     | [821667100c](https://linux-hardware.org/?probe=821667100c) | Nov 16, 2023 |
| ICL           | H510SB-TM v2.0              | All in one  | [34debd5e01](https://linux-hardware.org/?probe=34debd5e01) | Nov 16, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [d5c9e20e7b](https://linux-hardware.org/?probe=d5c9e20e7b) | Nov 15, 2023 |
| HP            | ProBook 6460b               | Notebook    | [b0795caa4c](https://linux-hardware.org/?probe=b0795caa4c) | Nov 15, 2023 |
| Dell          | Inspiron 3521               | Notebook    | [d038cb0c11](https://linux-hardware.org/?probe=d038cb0c11) | Nov 15, 2023 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [7d69c8e446](https://linux-hardware.org/?probe=7d69c8e446) | Nov 15, 2023 |
| Sony          | VPCCA2S1R                   | Notebook    | [f94fcde51d](https://linux-hardware.org/?probe=f94fcde51d) | Nov 15, 2023 |
| HUAWEI        | DRC-WXX                     | Tablet      | [99d2332a15](https://linux-hardware.org/?probe=99d2332a15) | Nov 15, 2023 |
| HUAWEI        | DRC-WXX                     | Tablet      | [1ff313db91](https://linux-hardware.org/?probe=1ff313db91) | Nov 15, 2023 |
| Acer          | Aspire Z3770                | All in one  | [c5751e6ffb](https://linux-hardware.org/?probe=c5751e6ffb) | Nov 15, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [127af8c0e3](https://linux-hardware.org/?probe=127af8c0e3) | Nov 15, 2023 |
| ICL           | H510SB-TM v2.0              | All in one  | [02437f9bc0](https://linux-hardware.org/?probe=02437f9bc0) | Nov 15, 2023 |
| Unknown       | Unknown                     | Notebook    | [8f82e3bd78](https://linux-hardware.org/?probe=8f82e3bd78) | Nov 15, 2023 |
| MSI           | Katana GF76 11UD            | Notebook    | [4f5b6c3898](https://linux-hardware.org/?probe=4f5b6c3898) | Nov 15, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [57e8703df8](https://linux-hardware.org/?probe=57e8703df8) | Nov 14, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [f6f9371495](https://linux-hardware.org/?probe=f6f9371495) | Nov 14, 2023 |
| Gigabyte      | EP43-DS3L                   | Desktop     | [acdeeb756d](https://linux-hardware.org/?probe=acdeeb756d) | Nov 14, 2023 |
| HIPER Tech... | HIPER WORKBOOK              | Notebook    | [8e914770df](https://linux-hardware.org/?probe=8e914770df) | Nov 14, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [fbaed4a09a](https://linux-hardware.org/?probe=fbaed4a09a) | Nov 14, 2023 |
| Intel         | H610-MIX v1.0               | Desktop     | [fef86e593d](https://linux-hardware.org/?probe=fef86e593d) | Nov 14, 2023 |
| INTECH PRO    | H510-M2 v5.0                | Desktop     | [9eb08d648d](https://linux-hardware.org/?probe=9eb08d648d) | Nov 14, 2023 |
| MSI           | MS-AE671 100                | All in one  | [7acd5e8d8c](https://linux-hardware.org/?probe=7acd5e8d8c) | Nov 14, 2023 |
| Unchartevi... | 6540                        | Notebook    | [5353bd2c2c](https://linux-hardware.org/?probe=5353bd2c2c) | Nov 13, 2023 |
| Intel         | X99 V1.0                    | Desktop     | [9f4eb05a5f](https://linux-hardware.org/?probe=9f4eb05a5f) | Nov 13, 2023 |
| HP            | Pavilion dv7                | Notebook    | [b53b5881ea](https://linux-hardware.org/?probe=b53b5881ea) | Nov 13, 2023 |
| ASUSTek       | P8H61                       | Desktop     | [0a801dd4f0](https://linux-hardware.org/?probe=0a801dd4f0) | Nov 13, 2023 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [9290054f05](https://linux-hardware.org/?probe=9290054f05) | Nov 13, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [0e8786e8a9](https://linux-hardware.org/?probe=0e8786e8a9) | Nov 13, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [4d8ebb0232](https://linux-hardware.org/?probe=4d8ebb0232) | Nov 13, 2023 |
| Fujitsu Si... | AMILO Pro Edition V3505     | Notebook    | [47597109a6](https://linux-hardware.org/?probe=47597109a6) | Nov 13, 2023 |
| Samsung       | G25/G26                     | Notebook    | [5fdbe7131c](https://linux-hardware.org/?probe=5fdbe7131c) | Nov 13, 2023 |
| Gigabyte      | B560M DS3H                  | Desktop     | [9a83b08ba1](https://linux-hardware.org/?probe=9a83b08ba1) | Nov 12, 2023 |
| Dell          | Inspiron ME051              | Notebook    | [e0114c60de](https://linux-hardware.org/?probe=e0114c60de) | Nov 12, 2023 |
| Gigabyte      | H410M H V2                  | Desktop     | [56a87ac439](https://linux-hardware.org/?probe=56a87ac439) | Nov 12, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [ab99d222f4](https://linux-hardware.org/?probe=ab99d222f4) | Nov 12, 2023 |
| Toshiba       | Satellite L735              | Notebook    | [a04ec0c5b2](https://linux-hardware.org/?probe=a04ec0c5b2) | Nov 11, 2023 |
| ASUSTek       | M51Tr                       | Notebook    | [d022e223bc](https://linux-hardware.org/?probe=d022e223bc) | Nov 11, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [7b086dcc71](https://linux-hardware.org/?probe=7b086dcc71) | Nov 11, 2023 |
| ASUSTek       | M5A87                       | Desktop     | [40a4f6c6f0](https://linux-hardware.org/?probe=40a4f6c6f0) | Nov 11, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [3d7d7d3e34](https://linux-hardware.org/?probe=3d7d7d3e34) | Nov 11, 2023 |
| Unknown       | Intel X79                   | Desktop     | [42adc3c9ce](https://linux-hardware.org/?probe=42adc3c9ce) | Nov 11, 2023 |
| ASUSTek       | P8H67                       | Desktop     | [6703e993d2](https://linux-hardware.org/?probe=6703e993d2) | Nov 11, 2023 |
| Haier         | U1530EM                     | Notebook    | [ea3804c31f](https://linux-hardware.org/?probe=ea3804c31f) | Nov 11, 2023 |
| AZW           | GTR V01                     | Mini pc     | [1d5d6585e4](https://linux-hardware.org/?probe=1d5d6585e4) | Nov 10, 2023 |
| Gigabyte      | B75M-HD3                    | Desktop     | [57548f89da](https://linux-hardware.org/?probe=57548f89da) | Nov 10, 2023 |
| Intel         | SKYBAY                      | Desktop     | [f5934c1986](https://linux-hardware.org/?probe=f5934c1986) | Nov 10, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [430cbdbe91](https://linux-hardware.org/?probe=430cbdbe91) | Nov 10, 2023 |
| ICL           | H510SB-TM v2.0              | All in one  | [d3cc8838c7](https://linux-hardware.org/?probe=d3cc8838c7) | Nov 10, 2023 |
| ASUSTek       | P5B-Premium                 | Desktop     | [5a031990bf](https://linux-hardware.org/?probe=5a031990bf) | Nov 10, 2023 |
| Intel         | SKYBAY                      | Desktop     | [49d4fabd38](https://linux-hardware.org/?probe=49d4fabd38) | Nov 10, 2023 |
| Fujitsu Si... | AMILO Pro Edition V3505     | Notebook    | [78a7710228](https://linux-hardware.org/?probe=78a7710228) | Nov 10, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [b5d7666605](https://linux-hardware.org/?probe=b5d7666605) | Nov 09, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [2c6f89c817](https://linux-hardware.org/?probe=2c6f89c817) | Nov 09, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [dc3a25ade3](https://linux-hardware.org/?probe=dc3a25ade3) | Nov 09, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [7279b92270](https://linux-hardware.org/?probe=7279b92270) | Nov 09, 2023 |
| HP            | Pavilion g6                 | Notebook    | [1bddfcc66f](https://linux-hardware.org/?probe=1bddfcc66f) | Nov 09, 2023 |
| Aquarius      | NS685U R11                  | Notebook    | [fe2d295af1](https://linux-hardware.org/?probe=fe2d295af1) | Nov 09, 2023 |
| Fujitsu Si... | AMILO Pro Edition V3405     | Notebook    | [429a0b938f](https://linux-hardware.org/?probe=429a0b938f) | Nov 09, 2023 |
| HP            | Pavilion g6                 | Notebook    | [ef6c4056ae](https://linux-hardware.org/?probe=ef6c4056ae) | Nov 09, 2023 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | Desktop     | [c5f2735e94](https://linux-hardware.org/?probe=c5f2735e94) | Nov 08, 2023 |
| Sony          | VPCEL3S1R                   | Notebook    | [00e9149304](https://linux-hardware.org/?probe=00e9149304) | Nov 08, 2023 |
| Dell          | 0M860N A00                  | Desktop     | [9cf0cdf157](https://linux-hardware.org/?probe=9cf0cdf157) | Nov 08, 2023 |
| Acer          | Aspire E1-570G              | Notebook    | [ecbf335e61](https://linux-hardware.org/?probe=ecbf335e61) | Nov 08, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [cf49add8e7](https://linux-hardware.org/?probe=cf49add8e7) | Nov 08, 2023 |
| Unknown       | Unknown                     | Notebook    | [a1be0f3000](https://linux-hardware.org/?probe=a1be0f3000) | Nov 08, 2023 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [8ae8c2d4d9](https://linux-hardware.org/?probe=8ae8c2d4d9) | Nov 08, 2023 |
| AOpen         | i57QMx-HA R1.01 55ADE10A... | Desktop     | [061ce4d9ac](https://linux-hardware.org/?probe=061ce4d9ac) | Nov 08, 2023 |
| Toshiba       | Satellite U300              | Notebook    | [c4701b779e](https://linux-hardware.org/?probe=c4701b779e) | Nov 08, 2023 |
| Gigabyte      | B75M-D3V                    | Desktop     | [a5d6a40643](https://linux-hardware.org/?probe=a5d6a40643) | Nov 08, 2023 |
| ASUSTek       | P7H55                       | Desktop     | [62ecde0340](https://linux-hardware.org/?probe=62ecde0340) | Nov 07, 2023 |
| Acer          | TravelMate P259-MG          | Notebook    | [b9429814ad](https://linux-hardware.org/?probe=b9429814ad) | Nov 07, 2023 |
| HP            | ProBook 450 G1              | Notebook    | [bb1bf92ea5](https://linux-hardware.org/?probe=bb1bf92ea5) | Nov 07, 2023 |
| HP            | ProBook 450 G1              | Notebook    | [bec045a214](https://linux-hardware.org/?probe=bec045a214) | Nov 07, 2023 |
| Acer          | Aspire ES1-531              | Notebook    | [9fd8344477](https://linux-hardware.org/?probe=9fd8344477) | Nov 07, 2023 |
| Gigabyte      | D525TUD                     | Desktop     | [19cffdb377](https://linux-hardware.org/?probe=19cffdb377) | Nov 06, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [55a0738916](https://linux-hardware.org/?probe=55a0738916) | Nov 06, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [738c6220a5](https://linux-hardware.org/?probe=738c6220a5) | Nov 06, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [60ec029256](https://linux-hardware.org/?probe=60ec029256) | Nov 05, 2023 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [2de5f4ef98](https://linux-hardware.org/?probe=2de5f4ef98) | Nov 05, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [436a3dc68e](https://linux-hardware.org/?probe=436a3dc68e) | Nov 05, 2023 |
| ASUSTek       | P5K PRO                     | Desktop     | [7dd5e78310](https://linux-hardware.org/?probe=7dd5e78310) | Nov 05, 2023 |
| HP            | Laptop 17t-by000            | Notebook    | [b23b606118](https://linux-hardware.org/?probe=b23b606118) | Nov 05, 2023 |
| Intel         | DH61DL AAG14066-205         | Desktop     | [be33944c69](https://linux-hardware.org/?probe=be33944c69) | Nov 05, 2023 |
| Acer          | Aspire 5349                 | Notebook    | [b1ca6f597c](https://linux-hardware.org/?probe=b1ca6f597c) | Nov 05, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [f782cf5541](https://linux-hardware.org/?probe=f782cf5541) | Nov 05, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [287ceab4df](https://linux-hardware.org/?probe=287ceab4df) | Nov 05, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [1c9b1632b8](https://linux-hardware.org/?probe=1c9b1632b8) | Nov 05, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [5541e01522](https://linux-hardware.org/?probe=5541e01522) | Nov 05, 2023 |
| Acer          | Aspire 5100                 | Notebook    | [62b63704e9](https://linux-hardware.org/?probe=62b63704e9) | Nov 04, 2023 |
| Pegatron      | IPMIP-H55-GEN               | Desktop     | [f87bf6e0dd](https://linux-hardware.org/?probe=f87bf6e0dd) | Nov 04, 2023 |
| Acer          | Aspire 5100                 | Notebook    | [c4d628cb50](https://linux-hardware.org/?probe=c4d628cb50) | Nov 04, 2023 |
| Intel         | DG33BU AAD79951-407         | Desktop     | [734dafca4e](https://linux-hardware.org/?probe=734dafca4e) | Nov 04, 2023 |
| MSI           | H110M PRO-D                 | Desktop     | [9a7337554c](https://linux-hardware.org/?probe=9a7337554c) | Nov 04, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [157f4d1006](https://linux-hardware.org/?probe=157f4d1006) | Nov 04, 2023 |
| Pegatron      | E60                         | Desktop     | [42e0c4ad61](https://linux-hardware.org/?probe=42e0c4ad61) | Nov 04, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [cda17ca99b](https://linux-hardware.org/?probe=cda17ca99b) | Nov 04, 2023 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [18bafa67dc](https://linux-hardware.org/?probe=18bafa67dc) | Nov 04, 2023 |
| Dell          | Inspiron M5110              | Notebook    | [20e338fb21](https://linux-hardware.org/?probe=20e338fb21) | Nov 04, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [86d2394935](https://linux-hardware.org/?probe=86d2394935) | Nov 03, 2023 |
| ASUSTek       | P5QD TURBO                  | Desktop     | [4a350b6fdb](https://linux-hardware.org/?probe=4a350b6fdb) | Nov 03, 2023 |
| ASRock        | A770DE+                     | Desktop     | [330e203c8a](https://linux-hardware.org/?probe=330e203c8a) | Nov 03, 2023 |
| Intel         | H610-MIX v1.0               | Desktop     | [eeaea55301](https://linux-hardware.org/?probe=eeaea55301) | Nov 03, 2023 |
| MSI           | 760GM-P21                   | Desktop     | [f3b16a05ae](https://linux-hardware.org/?probe=f3b16a05ae) | Nov 03, 2023 |
| Shenzhen M... | F7BFD                       | Desktop     | [f2b8e311c3](https://linux-hardware.org/?probe=f2b8e311c3) | Nov 02, 2023 |
| ASUSTek       | A88XM-E                     | Desktop     | [b828019cc1](https://linux-hardware.org/?probe=b828019cc1) | Nov 02, 2023 |
| Lenovo        | G580                        | Notebook    | [d137c3bc30](https://linux-hardware.org/?probe=d137c3bc30) | Nov 02, 2023 |
| 3Logic Gro... | Graviton N15i               | Notebook    | [555d634638](https://linux-hardware.org/?probe=555d634638) | Nov 02, 2023 |
| KVADRA        | U15W                        | Notebook    | [1c1f562cf5](https://linux-hardware.org/?probe=1c1f562cf5) | Nov 02, 2023 |
| Lenovo        | ThinkPad T430 23493V2       | Notebook    | [6fc33e3528](https://linux-hardware.org/?probe=6fc33e3528) | Nov 02, 2023 |
| MSI           | 760GM-P21                   | Desktop     | [2d08e07e5d](https://linux-hardware.org/?probe=2d08e07e5d) | Nov 02, 2023 |
| Digma         | Pro Fortis M DN15P5-8CXN... | Notebook    | [7bb9e8e743](https://linux-hardware.org/?probe=7bb9e8e743) | Nov 02, 2023 |
| Lenovo        | 30BB SDK0J40697 WIN 3305... | All in one  | [b65465f281](https://linux-hardware.org/?probe=b65465f281) | Nov 02, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [10b531fcd1](https://linux-hardware.org/?probe=10b531fcd1) | Nov 02, 2023 |
| Gigabyte      | 945GCMX-S2                  | Desktop     | [9e43e8bb79](https://linux-hardware.org/?probe=9e43e8bb79) | Nov 01, 2023 |
| ASRock        | N68C-S UCC                  | Desktop     | [cc636af8e3](https://linux-hardware.org/?probe=cc636af8e3) | Nov 01, 2023 |
| ASUSTek       | PRIME B350M-K               | Desktop     | [bc9c6a8334](https://linux-hardware.org/?probe=bc9c6a8334) | Nov 01, 2023 |
| HUAWEI        | DRC-WXX                     | Tablet      | [2764e50f21](https://linux-hardware.org/?probe=2764e50f21) | Nov 01, 2023 |
| ASUSTek       | PN53                        | Mini pc     | [5dfa3730a0](https://linux-hardware.org/?probe=5dfa3730a0) | Nov 01, 2023 |
| MAINBRD       | OPS62A-SHA                  | Desktop     | [41dc7afbc6](https://linux-hardware.org/?probe=41dc7afbc6) | Nov 01, 2023 |
| Samsung       | P29/28/26                   | Notebook    | [15d449da5d](https://linux-hardware.org/?probe=15d449da5d) | Nov 01, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [c962dd6f41](https://linux-hardware.org/?probe=c962dd6f41) | Nov 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [ae244bf378](https://linux-hardware.org/?probe=ae244bf378) | Nov 01, 2023 |
| ANCOMP        | Learnmate A15-501           | Notebook    | [da0c777960](https://linux-hardware.org/?probe=da0c777960) | Nov 01, 2023 |
| HUAWEI        | DRC-WXX                     | Tablet      | [55b168413e](https://linux-hardware.org/?probe=55b168413e) | Nov 01, 2023 |
| Gigabyte      | B760 GAMING X               | Desktop     | [a360fd740f](https://linux-hardware.org/?probe=a360fd740f) | Nov 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [e135ca8165](https://linux-hardware.org/?probe=e135ca8165) | Oct 31, 2023 |
| Gigabyte      | EP43T-UD3L                  | Desktop     | [a3a25165b1](https://linux-hardware.org/?probe=a3a25165b1) | Oct 31, 2023 |
| Acer          | Extensa 215-22              | Notebook    | [5fd05270e7](https://linux-hardware.org/?probe=5fd05270e7) | Oct 31, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [b522c4b372](https://linux-hardware.org/?probe=b522c4b372) | Oct 31, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [54a16261d5](https://linux-hardware.org/?probe=54a16261d5) | Oct 31, 2023 |
| Gigabyte      | Z590 D                      | Desktop     | [d986377165](https://linux-hardware.org/?probe=d986377165) | Oct 31, 2023 |
| ASUSTek       | N61Vn                       | Notebook    | [d8ee34cdbc](https://linux-hardware.org/?probe=d8ee34cdbc) | Oct 30, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [f39cf8f2f8](https://linux-hardware.org/?probe=f39cf8f2f8) | Oct 30, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [c8b24699a5](https://linux-hardware.org/?probe=c8b24699a5) | Oct 30, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [8ddd5fdfba](https://linux-hardware.org/?probe=8ddd5fdfba) | Oct 29, 2023 |
| eMachines     | Rhine V1.45                 | Notebook    | [dc1b87d14a](https://linux-hardware.org/?probe=dc1b87d14a) | Oct 29, 2023 |
| Intel         | H81 V2.3                    | Desktop     | [ad1b4d2589](https://linux-hardware.org/?probe=ad1b4d2589) | Oct 29, 2023 |
| Dell          | 0Y5DDC A00                  | Desktop     | [537823e1ce](https://linux-hardware.org/?probe=537823e1ce) | Oct 29, 2023 |
| Clevo         | W150HRM                     | Notebook    | [ef386d81b5](https://linux-hardware.org/?probe=ef386d81b5) | Oct 29, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [c76c1fe34a](https://linux-hardware.org/?probe=c76c1fe34a) | Oct 29, 2023 |
| ASUSTek       | M5A87                       | Desktop     | [7e4a0870d1](https://linux-hardware.org/?probe=7e4a0870d1) | Oct 29, 2023 |
| Toshiba       | Satellite L755              | Notebook    | [6f0566d95a](https://linux-hardware.org/?probe=6f0566d95a) | Oct 28, 2023 |
| Shenzhen M... | F7BFD                       | Desktop     | [28096584b1](https://linux-hardware.org/?probe=28096584b1) | Oct 28, 2023 |
| MSI           | MS-7235                     | Desktop     | [a20f50ce09](https://linux-hardware.org/?probe=a20f50ce09) | Oct 28, 2023 |
| Gigabyte      | EG41MF-US2H                 | Desktop     | [e79e5c88a2](https://linux-hardware.org/?probe=e79e5c88a2) | Oct 28, 2023 |
| Gigabyte      | EG41MF-US2H                 | Desktop     | [54665c8266](https://linux-hardware.org/?probe=54665c8266) | Oct 28, 2023 |
| Sony          | VPCEB1S1R                   | Notebook    | [bb50d8e6f3](https://linux-hardware.org/?probe=bb50d8e6f3) | Oct 28, 2023 |
| MSI           | A320M GRENADE               | Desktop     | [723b3a152b](https://linux-hardware.org/?probe=723b3a152b) | Oct 28, 2023 |
| HP            | 15                          | Notebook    | [a9e38be5d5](https://linux-hardware.org/?probe=a9e38be5d5) | Oct 27, 2023 |
| ASUSTek       | N56VZ                       | Notebook    | [bfe478311d](https://linux-hardware.org/?probe=bfe478311d) | Oct 26, 2023 |
| ASRock        | G31M-GS                     | Desktop     | [362c4857dd](https://linux-hardware.org/?probe=362c4857dd) | Oct 26, 2023 |
| Timi          | Mi NoteBook Ultra           | Notebook    | [66cfbcd057](https://linux-hardware.org/?probe=66cfbcd057) | Oct 26, 2023 |
| Intel         | X99                         | Desktop     | [c23c2dd478](https://linux-hardware.org/?probe=c23c2dd478) | Oct 26, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [5a0de31e5c](https://linux-hardware.org/?probe=5a0de31e5c) | Oct 26, 2023 |
| HP            | ProBook 4730s               | Notebook    | [935df70e31](https://linux-hardware.org/?probe=935df70e31) | Oct 26, 2023 |
| Toshiba       | Satellite C660D             | Notebook    | [8dc1c1d768](https://linux-hardware.org/?probe=8dc1c1d768) | Oct 26, 2023 |
| ANCOMP        | Learnmate A15-501           | Notebook    | [832eeb008b](https://linux-hardware.org/?probe=832eeb008b) | Oct 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [4631da3dbf](https://linux-hardware.org/?probe=4631da3dbf) | Oct 26, 2023 |
| Intel         | H81                         | Desktop     | [59ac163151](https://linux-hardware.org/?probe=59ac163151) | Oct 26, 2023 |
| Sony          | VGN-SR19VRN                 | Notebook    | [b6137146d6](https://linux-hardware.org/?probe=b6137146d6) | Oct 26, 2023 |
| HP            | Pavilion dv6700             | Notebook    | [4e65db3924](https://linux-hardware.org/?probe=4e65db3924) | Oct 26, 2023 |
| ASUSTek       | G56JR                       | Notebook    | [9dd84ffe04](https://linux-hardware.org/?probe=9dd84ffe04) | Oct 26, 2023 |
| Acer          | Aspire 7520                 | Notebook    | [e5636cc92b](https://linux-hardware.org/?probe=e5636cc92b) | Oct 25, 2023 |
| eMachines     | Rhine V1.45                 | Notebook    | [7b3fd7da03](https://linux-hardware.org/?probe=7b3fd7da03) | Oct 25, 2023 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [7ed95a4707](https://linux-hardware.org/?probe=7ed95a4707) | Oct 25, 2023 |
| Maibenben     | MaiBook P series            | Notebook    | [227638ee70](https://linux-hardware.org/?probe=227638ee70) | Oct 25, 2023 |
| Acer          | Aspire 5541                 | Notebook    | [df4f0f3912](https://linux-hardware.org/?probe=df4f0f3912) | Oct 25, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [b3e80c2dc5](https://linux-hardware.org/?probe=b3e80c2dc5) | Oct 25, 2023 |
| HP            | ProLiant DL380 Gen9         | Server      | [48bdda33c4](https://linux-hardware.org/?probe=48bdda33c4) | Oct 25, 2023 |
| Dell          | Latitude E6220              | Notebook    | [afc941b941](https://linux-hardware.org/?probe=afc941b941) | Oct 25, 2023 |
| Lenovo        | Unknown                     | Notebook    | [1139846802](https://linux-hardware.org/?probe=1139846802) | Oct 25, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [118822d39f](https://linux-hardware.org/?probe=118822d39f) | Oct 25, 2023 |
| HP            | Pavilion dv6700             | Notebook    | [5e143a92d1](https://linux-hardware.org/?probe=5e143a92d1) | Oct 25, 2023 |
| Irbis         | NB264                       | Notebook    | [ac65f72c50](https://linux-hardware.org/?probe=ac65f72c50) | Oct 24, 2023 |
| Lenovo        | ThinkPad L520 5017BK4       | Notebook    | [77037e51b0](https://linux-hardware.org/?probe=77037e51b0) | Oct 24, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [a7463f3745](https://linux-hardware.org/?probe=a7463f3745) | Oct 24, 2023 |
| ASRock        | N68C-GS FX                  | Desktop     | [0c3142b94d](https://linux-hardware.org/?probe=0c3142b94d) | Oct 24, 2023 |
| ASUSTek       | M5A87                       | Desktop     | [273561af88](https://linux-hardware.org/?probe=273561af88) | Oct 24, 2023 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [541d6f63b0](https://linux-hardware.org/?probe=541d6f63b0) | Oct 23, 2023 |
| ASUSTek       | P6X58D-E                    | Desktop     | [6af3baae7b](https://linux-hardware.org/?probe=6af3baae7b) | Oct 23, 2023 |
| MSI           | 770-C45                     | Desktop     | [9b5876d0eb](https://linux-hardware.org/?probe=9b5876d0eb) | Oct 23, 2023 |
| Packard Be... | EasyNote ENLG81BA           | Notebook    | [a9cb75e4fa](https://linux-hardware.org/?probe=a9cb75e4fa) | Oct 23, 2023 |
| ASUSTek       | N73SV                       | Notebook    | [6be1f80f91](https://linux-hardware.org/?probe=6be1f80f91) | Oct 23, 2023 |
| ASRock        | P67 Pro3                    | Desktop     | [93d23ddc07](https://linux-hardware.org/?probe=93d23ddc07) | Oct 23, 2023 |
| Acer          | Aspire 5734Z                | Notebook    | [cf4468ed0d](https://linux-hardware.org/?probe=cf4468ed0d) | Oct 23, 2023 |
| Lenovo        | 0x36C4                      | All in one  | [d801635668](https://linux-hardware.org/?probe=d801635668) | Oct 23, 2023 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [e0cffa70b5](https://linux-hardware.org/?probe=e0cffa70b5) | Oct 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [06d21bfdb4](https://linux-hardware.org/?probe=06d21bfdb4) | Oct 23, 2023 |
| ASUSTek       | P5KPL-SE                    | Desktop     | [2a58496283](https://linux-hardware.org/?probe=2a58496283) | Oct 22, 2023 |
| Samsung       | N100                        | Notebook    | [449f1837f5](https://linux-hardware.org/?probe=449f1837f5) | Oct 22, 2023 |
| Sony          | VGN-NS11ER_S                | Notebook    | [ece59481cb](https://linux-hardware.org/?probe=ece59481cb) | Oct 22, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [102c170156](https://linux-hardware.org/?probe=102c170156) | Oct 22, 2023 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | Desktop     | [7b963d7fff](https://linux-hardware.org/?probe=7b963d7fff) | Oct 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [d1026594ae](https://linux-hardware.org/?probe=d1026594ae) | Oct 21, 2023 |
| Samsung       | R530/R730/P530              | Notebook    | [ba506f75d1](https://linux-hardware.org/?probe=ba506f75d1) | Oct 21, 2023 |
| HP            | Notebook                    | Notebook    | [3bf9870d4a](https://linux-hardware.org/?probe=3bf9870d4a) | Oct 21, 2023 |
| Samsung       | N100                        | Notebook    | [80cf7b4a53](https://linux-hardware.org/?probe=80cf7b4a53) | Oct 21, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [53a0ed7609](https://linux-hardware.org/?probe=53a0ed7609) | Oct 21, 2023 |
| Acer          | Ferrari 3200                | Notebook    | [01ef021946](https://linux-hardware.org/?probe=01ef021946) | Oct 21, 2023 |
| ASRock        | D1800B-ITX                  | Desktop     | [c332512757](https://linux-hardware.org/?probe=c332512757) | Oct 21, 2023 |
| ASRock        | P45DE3                      | Desktop     | [2f9bd57442](https://linux-hardware.org/?probe=2f9bd57442) | Oct 21, 2023 |
| ASRock        | H61M                        | Desktop     | [b58eae7b88](https://linux-hardware.org/?probe=b58eae7b88) | Oct 21, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | Desktop     | [0748fa3430](https://linux-hardware.org/?probe=0748fa3430) | Oct 21, 2023 |
| HUAWEI        | HKD-WXX                     | Notebook    | [73735cfb57](https://linux-hardware.org/?probe=73735cfb57) | Oct 20, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [77ee2b1957](https://linux-hardware.org/?probe=77ee2b1957) | Oct 20, 2023 |
| ASRock        | J3455M                      | Desktop     | [9e627ef04c](https://linux-hardware.org/?probe=9e627ef04c) | Oct 20, 2023 |
| MSI           | 770T-C45                    | Desktop     | [bbe901612f](https://linux-hardware.org/?probe=bbe901612f) | Oct 20, 2023 |
| HP            | Notebook                    | Notebook    | [4d0eddbb92](https://linux-hardware.org/?probe=4d0eddbb92) | Oct 20, 2023 |
| Jumper        | Ezbook X3                   | Notebook    | [54ebd459be](https://linux-hardware.org/?probe=54ebd459be) | Oct 20, 2023 |
| ASUSTek       | F3JA                        | Notebook    | [6a96b7e347](https://linux-hardware.org/?probe=6a96b7e347) | Oct 20, 2023 |
| Lenovo        | ThinkPad T60 1952W2Q        | Notebook    | [4493954de6](https://linux-hardware.org/?probe=4493954de6) | Oct 19, 2023 |
| realme        | RMNBXXXX                    | Notebook    | [55266c03b1](https://linux-hardware.org/?probe=55266c03b1) | Oct 19, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [5936be0473](https://linux-hardware.org/?probe=5936be0473) | Oct 19, 2023 |
| ICL           | H510SB-TM v2.0              | All in one  | [5c6a2470fe](https://linux-hardware.org/?probe=5c6a2470fe) | Oct 19, 2023 |
| Lenovo        | IdeaPad Y550P 20035         | Notebook    | [899b4e9638](https://linux-hardware.org/?probe=899b4e9638) | Oct 19, 2023 |
| Dell          | Inspiron 15-3565            | Notebook    | [d60190dd5f](https://linux-hardware.org/?probe=d60190dd5f) | Oct 19, 2023 |
| ASRock        | J3455M                      | Desktop     | [a65255a6ec](https://linux-hardware.org/?probe=a65255a6ec) | Oct 19, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [5a4436b191](https://linux-hardware.org/?probe=5a4436b191) | Oct 19, 2023 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [e5ecd53787](https://linux-hardware.org/?probe=e5ecd53787) | Oct 19, 2023 |
| Yadro         | YadroB560                   | Desktop     | [d231d3b930](https://linux-hardware.org/?probe=d231d3b930) | Oct 19, 2023 |
| Acer          | TravelMate 4150             | Notebook    | [26bf6dbfcf](https://linux-hardware.org/?probe=26bf6dbfcf) | Oct 18, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [ae0eccc095](https://linux-hardware.org/?probe=ae0eccc095) | Oct 18, 2023 |
| HONOR         | HYM-WXX                     | Notebook    | [84da562e08](https://linux-hardware.org/?probe=84da562e08) | Oct 18, 2023 |
| MSI           | B360M PRO-VD                | Desktop     | [4d1cd49c1c](https://linux-hardware.org/?probe=4d1cd49c1c) | Oct 18, 2023 |
| Acer          | TravelMate 5720             | Notebook    | [8902ce3049](https://linux-hardware.org/?probe=8902ce3049) | Oct 18, 2023 |
| Toshiba       | Satellite A200              | Notebook    | [afc5127b45](https://linux-hardware.org/?probe=afc5127b45) | Oct 18, 2023 |
| ASUSTek       | K53SC                       | Notebook    | [5e5a88b3e2](https://linux-hardware.org/?probe=5e5a88b3e2) | Oct 18, 2023 |
| Gigabyte      | H310M S2 x.x                | Desktop     | [dd1f79a66a](https://linux-hardware.org/?probe=dd1f79a66a) | Oct 18, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [b6bc7ed678](https://linux-hardware.org/?probe=b6bc7ed678) | Oct 17, 2023 |
| QBIC          | BXT-512-7100U               | Desktop     | [e23f579099](https://linux-hardware.org/?probe=e23f579099) | Oct 17, 2023 |
| OpenYard      | RMB-MR91 01000100           | Server      | [00fb2051a8](https://linux-hardware.org/?probe=00fb2051a8) | Oct 17, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [2651ff0eba](https://linux-hardware.org/?probe=2651ff0eba) | Oct 17, 2023 |
| Intel         | H81                         | Desktop     | [317de00832](https://linux-hardware.org/?probe=317de00832) | Oct 17, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [001109b89b](https://linux-hardware.org/?probe=001109b89b) | Oct 17, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [a80532e1a0](https://linux-hardware.org/?probe=a80532e1a0) | Oct 17, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [da3768d9f4](https://linux-hardware.org/?probe=da3768d9f4) | Oct 17, 2023 |
| Gigabyte      | B360M DS3H                  | Desktop     | [cf5190078f](https://linux-hardware.org/?probe=cf5190078f) | Oct 17, 2023 |
| Gigabyte      | B360M DS3H                  | Desktop     | [06e6e5db34](https://linux-hardware.org/?probe=06e6e5db34) | Oct 17, 2023 |
| OEM           | X79G                        | Desktop     | [887a2b8f36](https://linux-hardware.org/?probe=887a2b8f36) | Oct 17, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [3c327fc90c](https://linux-hardware.org/?probe=3c327fc90c) | Oct 16, 2023 |
| HP            | 2820h                       | Desktop     | [73769961eb](https://linux-hardware.org/?probe=73769961eb) | Oct 16, 2023 |
| MSI           | VR610                       | Notebook    | [3cac0bd8c9](https://linux-hardware.org/?probe=3cac0bd8c9) | Oct 16, 2023 |
| Fujitsu Si... | AMILO Pro Edition V3405     | Notebook    | [ba0ead0d37](https://linux-hardware.org/?probe=ba0ead0d37) | Oct 16, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [9e4818431f](https://linux-hardware.org/?probe=9e4818431f) | Oct 16, 2023 |
| Gigabyte      | B450M S2H V2                | Desktop     | [72258458a5](https://linux-hardware.org/?probe=72258458a5) | Oct 16, 2023 |
| MSI           | B360M PRO-VD                | Desktop     | [98deafd70e](https://linux-hardware.org/?probe=98deafd70e) | Oct 15, 2023 |
| MSI           | H110M PRO-D                 | Desktop     | [14ad3343a7](https://linux-hardware.org/?probe=14ad3343a7) | Oct 15, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [6570860ebd](https://linux-hardware.org/?probe=6570860ebd) | Oct 15, 2023 |
| ASUSTek       | P5K PRO                     | Desktop     | [a4c386b42e](https://linux-hardware.org/?probe=a4c386b42e) | Oct 15, 2023 |
| ASUSTek       | P5K PRO                     | Desktop     | [aa244a1f00](https://linux-hardware.org/?probe=aa244a1f00) | Oct 15, 2023 |
| ASUSTek       | N56VV                       | Notebook    | [657664de04](https://linux-hardware.org/?probe=657664de04) | Oct 15, 2023 |
| Acer          | TravelMate B118-M           | Notebook    | [0d185effc4](https://linux-hardware.org/?probe=0d185effc4) | Oct 15, 2023 |
| eMachines     | Rhine V1.43                 | Notebook    | [1ec836f915](https://linux-hardware.org/?probe=1ec836f915) | Oct 15, 2023 |
| MSI           | Katana GF76 12UC            | Notebook    | [28c2984d39](https://linux-hardware.org/?probe=28c2984d39) | Oct 15, 2023 |
| Acer          | Aspire V3-571G              | Notebook    | [5e50c3624b](https://linux-hardware.org/?probe=5e50c3624b) | Oct 15, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [fbf9250075](https://linux-hardware.org/?probe=fbf9250075) | Oct 15, 2023 |
| HP            | Laptop 15-ra0xx             | Notebook    | [7d7ff23b31](https://linux-hardware.org/?probe=7d7ff23b31) | Oct 15, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [60cf13a0ce](https://linux-hardware.org/?probe=60cf13a0ce) | Oct 15, 2023 |
| ASUSTek       | F3Sr                        | Notebook    | [b7568466f9](https://linux-hardware.org/?probe=b7568466f9) | Oct 14, 2023 |
| MSI           | X299 RAIDER                 | Desktop     | [28f37d6590](https://linux-hardware.org/?probe=28f37d6590) | Oct 14, 2023 |
| MSI           | 770-C45                     | Desktop     | [c1e11a6e3d](https://linux-hardware.org/?probe=c1e11a6e3d) | Oct 14, 2023 |
| Gigabyte      | EP43-DS3L                   | Desktop     | [7cc4c9f010](https://linux-hardware.org/?probe=7cc4c9f010) | Oct 14, 2023 |
| MSI           | G31M3-F V2                  | Desktop     | [9a26b22114](https://linux-hardware.org/?probe=9a26b22114) | Oct 14, 2023 |
| Biostar       | H81MHV3 5.0                 | Desktop     | [11b853321a](https://linux-hardware.org/?probe=11b853321a) | Oct 14, 2023 |
| ASUSTek       | F50GX                       | Notebook    | [4665f359b9](https://linux-hardware.org/?probe=4665f359b9) | Oct 14, 2023 |
| HP            | Notebook                    | Notebook    | [20fd24630c](https://linux-hardware.org/?probe=20fd24630c) | Oct 14, 2023 |
| Biostar       | H81MHV3 5.0                 | Desktop     | [9fdaa00358](https://linux-hardware.org/?probe=9fdaa00358) | Oct 13, 2023 |
| Acer          | Aspire A515-52G             | Notebook    | [e347245de9](https://linux-hardware.org/?probe=e347245de9) | Oct 13, 2023 |
| HP            | ProLiant DL380 Gen9         | Server      | [9ea9761b35](https://linux-hardware.org/?probe=9ea9761b35) | Oct 13, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [366bab6858](https://linux-hardware.org/?probe=366bab6858) | Oct 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [05b441657d](https://linux-hardware.org/?probe=05b441657d) | Oct 13, 2023 |
| ASRock        | H55M-LE                     | Desktop     | [db9ce33137](https://linux-hardware.org/?probe=db9ce33137) | Oct 13, 2023 |
| Acer          | TravelMate 3040             | Notebook    | [8fe8316945](https://linux-hardware.org/?probe=8fe8316945) | Oct 13, 2023 |
| Acer          | TravelMate 5744Z            | Notebook    | [38f2a731a5](https://linux-hardware.org/?probe=38f2a731a5) | Oct 13, 2023 |
| Gigabyte      | H55M-USB3                   | Desktop     | [ba758fb431](https://linux-hardware.org/?probe=ba758fb431) | Oct 13, 2023 |
| HP            | 635                         | Notebook    | [a44c783f17](https://linux-hardware.org/?probe=a44c783f17) | Oct 13, 2023 |
| Pegatron      | IPPSB-SDQ/H61               | All in one  | [5ce23926ac](https://linux-hardware.org/?probe=5ce23926ac) | Oct 12, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [683a06d3a1](https://linux-hardware.org/?probe=683a06d3a1) | Oct 12, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [5a954486f1](https://linux-hardware.org/?probe=5a954486f1) | Oct 12, 2023 |
| Intel         | X99 V3.0                    | Desktop     | [10d96ed192](https://linux-hardware.org/?probe=10d96ed192) | Oct 12, 2023 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [f39e659abb](https://linux-hardware.org/?probe=f39e659abb) | Oct 12, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [41ceddf203](https://linux-hardware.org/?probe=41ceddf203) | Oct 12, 2023 |
| ANCOMP        | LAPTOP                      | All in one  | [9508f6f8de](https://linux-hardware.org/?probe=9508f6f8de) | Oct 12, 2023 |
| Intel         | X99 V3.0                    | Desktop     | [e22c1235d0](https://linux-hardware.org/?probe=e22c1235d0) | Oct 12, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [b44ced08df](https://linux-hardware.org/?probe=b44ced08df) | Oct 12, 2023 |
| ANCOMP        | Learnmate A15-501           | Notebook    | [6994a91e07](https://linux-hardware.org/?probe=6994a91e07) | Oct 12, 2023 |
| ANCOMP        | Learnmate A15-501           | Notebook    | [2d6b73a209](https://linux-hardware.org/?probe=2d6b73a209) | Oct 12, 2023 |
| ASUSTek       | STRIX B250F GAMING          | Desktop     | [8d4eefa612](https://linux-hardware.org/?probe=8d4eefa612) | Oct 12, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [9af9d0ea5e](https://linux-hardware.org/?probe=9af9d0ea5e) | Oct 11, 2023 |
| Medion        | MS-7800                     | Desktop     | [806b81f839](https://linux-hardware.org/?probe=806b81f839) | Oct 11, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [d9183a2d23](https://linux-hardware.org/?probe=d9183a2d23) | Oct 11, 2023 |
| Acer          | AOD270                      | Notebook    | [f42863f60d](https://linux-hardware.org/?probe=f42863f60d) | Oct 11, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [56bdc382d5](https://linux-hardware.org/?probe=56bdc382d5) | Oct 10, 2023 |
| HONOR         | HYM-WXX                     | Notebook    | [d8ab8c960a](https://linux-hardware.org/?probe=d8ab8c960a) | Oct 10, 2023 |
| MSI           | 785GM-E51                   | Desktop     | [6034bcda1d](https://linux-hardware.org/?probe=6034bcda1d) | Oct 10, 2023 |
| Lenovo        | ThinkPad T400 6474WPU       | Notebook    | [8c4f0dda0f](https://linux-hardware.org/?probe=8c4f0dda0f) | Oct 10, 2023 |
| ASUSTek       | K40IJ                       | Notebook    | [67ca367ad2](https://linux-hardware.org/?probe=67ca367ad2) | Oct 10, 2023 |
| Gigabyte      | H55M-USB3                   | Desktop     | [9bf81b8cb2](https://linux-hardware.org/?probe=9bf81b8cb2) | Oct 09, 2023 |
| Gigabyte      | GA-8S655FX-L                | Desktop     | [4c81a7a377](https://linux-hardware.org/?probe=4c81a7a377) | Oct 09, 2023 |
| ASUSTek       | M2A-VM                      | Desktop     | [ac2f8ef69c](https://linux-hardware.org/?probe=ac2f8ef69c) | Oct 09, 2023 |
| ASRock        | N68C-GS FX                  | Desktop     | [2da75b7afa](https://linux-hardware.org/?probe=2da75b7afa) | Oct 09, 2023 |
| Acer          | Swift SF114-34              | Notebook    | [1b92216526](https://linux-hardware.org/?probe=1b92216526) | Oct 09, 2023 |
| MSI           | Z87I                        | Desktop     | [6cd843a979](https://linux-hardware.org/?probe=6cd843a979) | Oct 09, 2023 |
| HP            | 650                         | Notebook    | [1339361633](https://linux-hardware.org/?probe=1339361633) | Oct 09, 2023 |
| HP            | ProBook 4545s               | Notebook    | [bc5404508f](https://linux-hardware.org/?probe=bc5404508f) | Oct 09, 2023 |
| Gigabyte      | B450M K-CF                  | Desktop     | [4f495e0c37](https://linux-hardware.org/?probe=4f495e0c37) | Oct 09, 2023 |
| Intel         | SKYBAY                      | Desktop     | [a501059141](https://linux-hardware.org/?probe=a501059141) | Oct 09, 2023 |
| MSI           | U210/U210 Light             | Notebook    | [14ee9aa051](https://linux-hardware.org/?probe=14ee9aa051) | Oct 09, 2023 |
| Lenovo        | ThinkPad X200 7458Y28       | Notebook    | [ad9893f44c](https://linux-hardware.org/?probe=ad9893f44c) | Oct 09, 2023 |
| ASUSTek       | M2A74-AM SE                 | Desktop     | [05c13f10df](https://linux-hardware.org/?probe=05c13f10df) | Oct 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [27022c7042](https://linux-hardware.org/?probe=27022c7042) | Oct 08, 2023 |
| Pegatron      | 2A94h                       | Desktop     | [4c5ce13f3a](https://linux-hardware.org/?probe=4c5ce13f3a) | Oct 08, 2023 |
| ASRock        | N68C-GS FX                  | Desktop     | [67ebeba633](https://linux-hardware.org/?probe=67ebeba633) | Oct 08, 2023 |
| ASRock        | P4i65G                      | Desktop     | [251a845634](https://linux-hardware.org/?probe=251a845634) | Oct 08, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [ef1a8f61be](https://linux-hardware.org/?probe=ef1a8f61be) | Oct 08, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [b8d92e6419](https://linux-hardware.org/?probe=b8d92e6419) | Oct 08, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [0cc35c9eaf](https://linux-hardware.org/?probe=0cc35c9eaf) | Oct 08, 2023 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [8af576f99e](https://linux-hardware.org/?probe=8af576f99e) | Oct 08, 2023 |
| MSI           | X299 RAIDER                 | Desktop     | [ec7eb75235](https://linux-hardware.org/?probe=ec7eb75235) | Oct 08, 2023 |
| MSI           | U210/U210 Light             | Notebook    | [29ff1c90ca](https://linux-hardware.org/?probe=29ff1c90ca) | Oct 08, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [ee2df4d880](https://linux-hardware.org/?probe=ee2df4d880) | Oct 08, 2023 |
| ASUSTek       | N56VZ                       | Notebook    | [1fd7b27414](https://linux-hardware.org/?probe=1fd7b27414) | Oct 07, 2023 |
| ASUSTek       | M5A78L-M LE                 | Desktop     | [c5387f239d](https://linux-hardware.org/?probe=c5387f239d) | Oct 07, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [5b05f29471](https://linux-hardware.org/?probe=5b05f29471) | Oct 07, 2023 |
| ASUSTek       | Leonite2                    | Desktop     | [67f5bc1c0a](https://linux-hardware.org/?probe=67f5bc1c0a) | Oct 07, 2023 |
| Acer          | Aspire A515-52G             | Notebook    | [653d2049d2](https://linux-hardware.org/?probe=653d2049d2) | Oct 07, 2023 |
| Gigabyte      | H97-D3H-CF                  | Desktop     | [6f0b19f927](https://linux-hardware.org/?probe=6f0b19f927) | Oct 07, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [0ad7f99071](https://linux-hardware.org/?probe=0ad7f99071) | Oct 07, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [75ceec744e](https://linux-hardware.org/?probe=75ceec744e) | Oct 07, 2023 |
| HUAWEI        | HKD-WXX                     | Notebook    | [20886a702a](https://linux-hardware.org/?probe=20886a702a) | Oct 07, 2023 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [0b38be8780](https://linux-hardware.org/?probe=0b38be8780) | Oct 06, 2023 |
| HP            | Laptop 15-rb0xx             | Notebook    | [a52cde95dc](https://linux-hardware.org/?probe=a52cde95dc) | Oct 06, 2023 |
| MACHINIST     | E5-V2.82H V1.1              | Desktop     | [2a5bdb0b90](https://linux-hardware.org/?probe=2a5bdb0b90) | Oct 06, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [1f095979f4](https://linux-hardware.org/?probe=1f095979f4) | Oct 06, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [63087df172](https://linux-hardware.org/?probe=63087df172) | Oct 06, 2023 |
| ASUSTek       | G50V                        | Notebook    | [90f92902b1](https://linux-hardware.org/?probe=90f92902b1) | Oct 06, 2023 |
| ANCOMP        | LAPTOP                      | All in one  | [ea795eaab6](https://linux-hardware.org/?probe=ea795eaab6) | Oct 06, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [37d9a6d75f](https://linux-hardware.org/?probe=37d9a6d75f) | Oct 06, 2023 |
| Kraftway      | ACCORD                      | Notebook    | [b8d5508724](https://linux-hardware.org/?probe=b8d5508724) | Oct 06, 2023 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [26a7af1326](https://linux-hardware.org/?probe=26a7af1326) | Oct 06, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [7b88a62033](https://linux-hardware.org/?probe=7b88a62033) | Oct 05, 2023 |
| Intel         | SKYBAY                      | Desktop     | [9f8bbc14f4](https://linux-hardware.org/?probe=9f8bbc14f4) | Oct 05, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [c2fcd9d06e](https://linux-hardware.org/?probe=c2fcd9d06e) | Oct 05, 2023 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [fca602c192](https://linux-hardware.org/?probe=fca602c192) | Oct 05, 2023 |
| Fujitsu Si... | AMILO Pro Edition V3405     | Notebook    | [b566dd24ff](https://linux-hardware.org/?probe=b566dd24ff) | Oct 04, 2023 |
| ASUSTek       | PRIME B365M-C               | Desktop     | [81ab5fe3f3](https://linux-hardware.org/?probe=81ab5fe3f3) | Oct 04, 2023 |
| MSI           | P43 Neo-F                   | Desktop     | [4b19989894](https://linux-hardware.org/?probe=4b19989894) | Oct 04, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6256ecb2a2](https://linux-hardware.org/?probe=6256ecb2a2) | Oct 04, 2023 |
| ASUSTek       | GL703VD                     | Notebook    | [cfa1d9861b](https://linux-hardware.org/?probe=cfa1d9861b) | Oct 04, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [9483230f98](https://linux-hardware.org/?probe=9483230f98) | Oct 04, 2023 |
| ASUSTek       | P5K PRO                     | Desktop     | [2d4ce43693](https://linux-hardware.org/?probe=2d4ce43693) | Oct 04, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [deb34982fa](https://linux-hardware.org/?probe=deb34982fa) | Oct 04, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2acaa4ddbc](https://linux-hardware.org/?probe=2acaa4ddbc) | Oct 04, 2023 |
| MSI           | P43 Neo-F                   | Desktop     | [c4e8261756](https://linux-hardware.org/?probe=c4e8261756) | Oct 04, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [46b3fb73b0](https://linux-hardware.org/?probe=46b3fb73b0) | Oct 04, 2023 |
| ASUSTek       | P5K                         | Desktop     | [83eea396c1](https://linux-hardware.org/?probe=83eea396c1) | Oct 03, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [b451657ad6](https://linux-hardware.org/?probe=b451657ad6) | Oct 03, 2023 |
| Lenovo        | G70-70 80HW                 | Notebook    | [c63d12108b](https://linux-hardware.org/?probe=c63d12108b) | Oct 03, 2023 |
| MSI           | GS43VR 7RE                  | Notebook    | [cf9a5a8be9](https://linux-hardware.org/?probe=cf9a5a8be9) | Oct 03, 2023 |
| Dell          | System Inspiron 17 7000 ... | Notebook    | [4a237f21f8](https://linux-hardware.org/?probe=4a237f21f8) | Oct 03, 2023 |
| Acer          | Aspire VN7-571G             | Notebook    | [0babc8185b](https://linux-hardware.org/?probe=0babc8185b) | Oct 03, 2023 |
| HP            | 650                         | Notebook    | [f652e189f9](https://linux-hardware.org/?probe=f652e189f9) | Oct 03, 2023 |
| HP            | 3031h                       | Desktop     | [a05ac19b87](https://linux-hardware.org/?probe=a05ac19b87) | Oct 03, 2023 |
| ASUSTek       | X551CAP                     | Notebook    | [37d7bd14c7](https://linux-hardware.org/?probe=37d7bd14c7) | Oct 03, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [62e437adf3](https://linux-hardware.org/?probe=62e437adf3) | Oct 03, 2023 |
| MSI           | 760GM-P33                   | Desktop     | [5967be8309](https://linux-hardware.org/?probe=5967be8309) | Oct 03, 2023 |
| ASUSTek       | G50V                        | Notebook    | [a6edae3eff](https://linux-hardware.org/?probe=a6edae3eff) | Oct 03, 2023 |
| HP            | Notebook                    | Notebook    | [02403b0967](https://linux-hardware.org/?probe=02403b0967) | Oct 02, 2023 |
| ASRock        | H110M-DGS R3.0              | Desktop     | [a8d8ab9d2c](https://linux-hardware.org/?probe=a8d8ab9d2c) | Oct 02, 2023 |
| Toshiba       | Satellite A200              | Notebook    | [6a3308fba2](https://linux-hardware.org/?probe=6a3308fba2) | Oct 02, 2023 |
| MSI           | B360M PRO-VD 2019-01-24     | Desktop     | [43062f3c9a](https://linux-hardware.org/?probe=43062f3c9a) | Oct 02, 2023 |
| MSI           | FM2-A55M-E33                | Desktop     | [ed22a192a5](https://linux-hardware.org/?probe=ed22a192a5) | Oct 02, 2023 |
| ASRock        | N68C-GS FX                  | Desktop     | [49d7edb011](https://linux-hardware.org/?probe=49d7edb011) | Oct 02, 2023 |
| MSI           | Katana GF76 12UC            | Notebook    | [3939c14096](https://linux-hardware.org/?probe=3939c14096) | Oct 02, 2023 |
| ASUSTek       | P5K                         | Desktop     | [e8cf25ae85](https://linux-hardware.org/?probe=e8cf25ae85) | Oct 02, 2023 |
| ASUSTek       | P8H61-M LX2 R2.0            | Desktop     | [e1f02a7f4f](https://linux-hardware.org/?probe=e1f02a7f4f) | Oct 02, 2023 |
| MSI           | Z170A TOMAHAWK              | Desktop     | [6f48b6d79c](https://linux-hardware.org/?probe=6f48b6d79c) | Oct 02, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [0aa82776f5](https://linux-hardware.org/?probe=0aa82776f5) | Oct 01, 2023 |
| HP            | Compaq 610                  | Notebook    | [9570db13af](https://linux-hardware.org/?probe=9570db13af) | Oct 01, 2023 |
| Unknown       | X79                         | Desktop     | [64628cc08d](https://linux-hardware.org/?probe=64628cc08d) | Oct 01, 2023 |
| ASUSTek       | T305CA                      | Tablet      | [821fb55f33](https://linux-hardware.org/?probe=821fb55f33) | Oct 01, 2023 |
| MSI           | GE70 0NC/GE70 0ND/GE70K ... | Notebook    | [0939610428](https://linux-hardware.org/?probe=0939610428) | Oct 01, 2023 |
| Dell          | Vostro 3560                 | Notebook    | [9acebbf655](https://linux-hardware.org/?probe=9acebbf655) | Oct 01, 2023 |
| Gigabyte      | 970A-D3                     | Desktop     | [9b47949b87](https://linux-hardware.org/?probe=9b47949b87) | Oct 01, 2023 |
| Digma         | EVE 11 C421Y ES1067EW       | Notebook    | [2a54b2d3e1](https://linux-hardware.org/?probe=2a54b2d3e1) | Oct 01, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [cd4c3fb654](https://linux-hardware.org/?probe=cd4c3fb654) | Oct 01, 2023 |
| Toshiba       | Satellite C850-D4K          | Notebook    | [47d93b3030](https://linux-hardware.org/?probe=47d93b3030) | Oct 01, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/ROSA/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| ROSA R10           | 4390      | 13.41%  |
| ROSA R11           | 4121      | 12.59%  |
| ROSA R8            | 3637      | 11.11%  |
| ROSA R6            | 3496      | 10.68%  |
| ROSA R7            | 3301      | 10.09%  |
| ROSA R8.1          | 2853      | 8.72%   |
| ROSA R9            | 2549      | 7.79%   |
| ROSA R11.1         | 2356      | 7.2%    |
| ROSA 12.2          | 2016      | 6.16%   |
| ROSA 12.4          | 1384      | 4.23%   |
| ROSA 12.3          | 981       | 3%      |
| ROSA R5            | 571       | 1.74%   |
| ROSA 12.1          | 363       | 1.11%   |
| ROSA 12            | 305       | 0.93%   |
| ROSA R4            | 121       | 0.37%   |
| ROSA R3            | 86        | 0.26%   |
| ROSA R12           | 71        | 0.22%   |
| ROSA 13.0          | 23        | 0.07%   |
| ROSA 2019.05       | 21        | 0.06%   |
| ROSA R9-R11        | 16        | 0.05%   |
| ROSA R2            | 16        | 0.05%   |
| ROSA 2012.0        | 12        | 0.04%   |
| ROSA 2021.1        | 9         | 0.03%   |
| ROSA Chrome 2.0    | 7         | 0.02%   |
| ROSA R4-R8         | 4         | 0.01%   |
| ROSA DX 1.0        | 4         | 0.01%   |
| ROSA Nickel 2019.0 | 3         | 0.01%   |
| ROSA DX 2.0        | 2         | 0.01%   |
| ROSA 2019.0        | 2         | 0.01%   |
| ROSA 12f.1         | 2         | 0.01%   |
| ROSA SX 1.0        | 1         | 0.003%  |
| ROSA R1            | 1         | 0.003%  |
| ROSA 1.0           | 1         | 0.003%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| ROSA | 27035     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Computers | Percent |
|-------------------------------------|-----------|---------|
| 4.9.60-nrj-desktop-1rosa-x86_64     | 2054      | 5.81%   |
| 3.14.44-nrj-desktop-2rosa-x86_64    | 1866      | 5.28%   |
| 4.9.20-nrj-desktop-1rosa-x86_64     | 1828      | 5.17%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 1804      | 5.1%    |
| 5.10.74-generic-2rosa2021.1-x86_64  | 1793      | 5.07%   |
| 4.1.25-nrj-desktop-1rosa-x86_64     | 1600      | 4.53%   |
| 4.1.15-nrj-desktop-1rosa-x86_64     | 1381      | 3.91%   |
| 4.1.34-nrj-desktop-2rosa-x86_64     | 971       | 2.75%   |
| 3.14.44-nrj-desktop-2rosa-i586      | 833       | 2.36%   |
| 4.9.124-nrj-desktop-1rosa-x86_64    | 782       | 2.21%   |
| 6.1.20-generic-2rosa2021.1-x86_64   | 702       | 1.99%   |
| 4.9.9-nrj-desktop-1rosa-x86_64      | 697       | 1.97%   |
| 4.1.38-nrj-desktop-2rosa-x86_64     | 647       | 1.83%   |
| 4.1.25-nrj-desktop-1rosa-i586       | 580       | 1.64%   |
| 4.9.60-nrj-desktop-1rosa-i586       | 550       | 1.56%   |
| 4.9.155-nrj-desktop-1rosa-x86_64    | 524       | 1.48%   |
| 4.9.76-nrj-desktop-1rosa-x86_64     | 502       | 1.42%   |
| 4.9.20-nrj-desktop-1rosa-i586       | 491       | 1.39%   |
| 4.1.16-nrj-desktop-1rosa-x86_64     | 463       | 1.31%   |
| 4.15.0-desktop-68.5rosa-x86_64      | 458       | 1.3%    |
| 4.15.0-desktop-45.1rosa-i586        | 456       | 1.29%   |
| 4.1.15-nrj-desktop-1rosa-i586       | 452       | 1.28%   |
| 5.4.32-generic-2rosa-x86_64         | 447       | 1.26%   |
| 4.9.41-nrj-desktop-1rosa-x86_64     | 446       | 1.26%   |
| 4.15.0-desktop-122.124.1rosa-x86_64 | 443       | 1.25%   |
| 5.4.83-generic-2rosa-x86_64         | 411       | 1.16%   |
| 4.1.34-nrj-desktop-2rosa-i586       | 379       | 1.07%   |
| 5.10.118-generic-2rosa2021.1-x86_64 | 365       | 1.03%   |
| 5.15.75-generic-1rosa2021.1-x86_64  | 358       | 1.01%   |
| 4.15.0-desktop-47.2rosa-x86_64      | 340       | 0.96%   |
| 4.15.0-desktop-94.1rosa-x86_64      | 334       | 0.94%   |
| 4.9.9-nrj-desktop-1rosa-i586        | 311       | 0.88%   |
| 6.1.58-generic-1rosa2021.1-x86_64   | 291       | 0.82%   |
| 5.15.79-generic-1rosa2021.1-x86_64  | 282       | 0.8%    |
| 4.1.38-nrj-desktop-2rosa-i586       | 279       | 0.79%   |
| 4.9.95-nrj-desktop-2rosa-x86_64     | 270       | 0.76%   |
| 3.14.53-nrj-desktop-1rosa-x86_64    | 270       | 0.76%   |
| 4.1.22-nrj-desktop-2rosa-x86_64     | 258       | 0.73%   |
| 4.1.33-nrj-desktop-1rosa-x86_64     | 250       | 0.71%   |
| 4.15.0-desktop-60.7rosa-x86_64      | 228       | 0.64%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 4.15.0   | 4430      | 12.76%  |
| 3.14.44  | 2695      | 7.76%   |
| 4.9.60   | 2596      | 7.48%   |
| 4.9.20   | 2318      | 6.68%   |
| 4.1.25   | 2172      | 6.26%   |
| 5.10.74  | 1850      | 5.33%   |
| 4.1.15   | 1832      | 5.28%   |
| 4.1.34   | 1349      | 3.89%   |
| 4.1.38   | 1111      | 3.2%    |
| 4.9.9    | 1002      | 2.89%   |
| 4.9.124  | 974       | 2.81%   |
| 6.1.20   | 712       | 2.05%   |
| 4.9.155  | 694       | 2%      |
| 4.9.76   | 638       | 1.84%   |
| 4.1.16   | 631       | 1.82%   |
| 5.4.32   | 613       | 1.77%   |
| 4.9.41   | 589       | 1.7%    |
| 5.4.83   | 527       | 1.52%   |
| 5.15.75  | 409       | 1.18%   |
| 4.1.19   | 390       | 1.12%   |
| 3.14.53  | 387       | 1.12%   |
| 5.10.118 | 374       | 1.08%   |
| 4.1.22   | 366       | 1.05%   |
| 4.9.95   | 339       | 0.98%   |
| 4.1.33   | 339       | 0.98%   |
| 4.1.13   | 305       | 0.88%   |
| 6.1.58   | 299       | 0.86%   |
| 5.15.79  | 282       | 0.81%   |
| 4.9.111  | 244       | 0.7%    |
| 3.14.25  | 222       | 0.64%   |
| 3.14.33  | 196       | 0.56%   |
| 5.10.71  | 189       | 0.54%   |
| 6.1.38   | 178       | 0.51%   |
| 4.9.87   | 174       | 0.5%    |
| 6.1.46   | 159       | 0.46%   |
| 3.14.39  | 134       | 0.39%   |
| 4.9.14   | 109       | 0.31%   |
| 5.4.40   | 104       | 0.3%    |
| 5.17.11  | 101       | 0.29%   |
| 5.15.103 | 99        | 0.29%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.9     | 8446      | 26.92%  |
| 4.1     | 7557      | 24.09%  |
| 4.15    | 4444      | 14.17%  |
| 3.14    | 3541      | 11.29%  |
| 5.10    | 2448      | 7.8%    |
| 5.4     | 1299      | 4.14%   |
| 6.1     | 1279      | 4.08%   |
| 5.15    | 969       | 3.09%   |
| 4.4     | 150       | 0.48%   |
| 4.13    | 108       | 0.34%   |
| 5.17    | 102       | 0.33%   |
| 3.10    | 101       | 0.32%   |
| 5.18    | 77        | 0.25%   |
| 4.8     | 77        | 0.25%   |
| 6.0     | 60        | 0.19%   |
| 5.0     | 58        | 0.18%   |
| 4.0     | 48        | 0.15%   |
| 4.7     | 47        | 0.15%   |
| 4.6     | 46        | 0.15%   |
| 4.16    | 44        | 0.14%   |
| 4.19    | 41        | 0.13%   |
| 4.18    | 40        | 0.13%   |
| 3.18    | 38        | 0.12%   |
| 4.14    | 32        | 0.1%    |
| 4.3     | 27        | 0.09%   |
| 5.16    | 26        | 0.08%   |
| 4.2     | 26        | 0.08%   |
| 4.5     | 24        | 0.08%   |
| 4.17    | 21        | 0.07%   |
| 4.11    | 17        | 0.05%   |
| 5.5     | 16        | 0.05%   |
| 4.12    | 15        | 0.05%   |
| 3.0     | 14        | 0.04%   |
| 5.3     | 12        | 0.04%   |
| 5.2     | 12        | 0.04%   |
| 6.4     | 9         | 0.03%   |
| 6.3     | 9         | 0.03%   |
| 6.2     | 9         | 0.03%   |
| 4.10    | 9         | 0.03%   |
| 3.17    | 9         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 21452     | 77.55%  |
| i686    | 6202      | 22.42%  |
| aarch64 | 7         | 0.03%   |
| e2k     | 2         | 0.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| KDE4       | 18142     | 62.15%  |
| KDE5       | 7224      | 24.75%  |
| GNOME      | 1850      | 6.34%   |
| LXQt       | 1086      | 3.72%   |
| MATE       | 367       | 1.26%   |
| XFCE       | 235       | 0.81%   |
| LXDE       | 165       | 0.57%   |
| Unknown    | 105       | 0.36%   |
| i3         | 7         | 0.02%   |
| KDE        | 4         | 0.01%   |
| Budgie     | 3         | 0.01%   |
| Cinnamon   | 2         | 0.01%   |
| X-Cinnamon | 1         | 0.003%  |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 23869     | 86.26%  |
| Wayland | 3768      | 13.62%  |
| Tty     | 23        | 0.08%   |
| Unknown | 10        | 0.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| KDM     | 18310     | 63.1%   |
| SDDM    | 7759      | 26.74%  |
| GDM     | 2542      | 8.76%   |
| LightDM | 226       | 0.78%   |
| TDM     | 115       | 0.4%    |
| Unknown | 43        | 0.15%   |
| XDM     | 19        | 0.07%   |
| LXDM    | 1         | 0.003%  |
| LDM     | 1         | 0.003%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 21112     | 75.32%  |
| ru_RU   | 6138      | 21.9%   |
| en_US   | 212       | 0.76%   |
| de_DE   | 91        | 0.32%   |
| pl_PL   | 86        | 0.31%   |
| es_ES   | 57        | 0.2%    |
| pt_BR   | 46        | 0.16%   |
| it_IT   | 45        | 0.16%   |
| en_GB   | 41        | 0.15%   |
| fr_FR   | 40        | 0.14%   |
| ru_UA   | 26        | 0.09%   |
| pt_PT   | 12        | 0.04%   |
| ro_RO   | 10        | 0.04%   |
| es_PE   | 8         | 0.03%   |
| es_MX   | 8         | 0.03%   |
| C       | 7         | 0.02%   |
| tr_TR   | 6         | 0.02%   |
| sk_SK   | 6         | 0.02%   |
| es_CO   | 6         | 0.02%   |
| hu_HU   | 5         | 0.02%   |
| es_AR   | 5         | 0.02%   |
| cs_CZ   | 5         | 0.02%   |
| fr_BE   | 4         | 0.01%   |
| ru_BY   | 3         | 0.01%   |
| en_IN   | 3         | 0.01%   |
| bg_BG   | 3         | 0.01%   |
| ru_KZ   | 2         | 0.01%   |
| nl_NL   | 2         | 0.01%   |
| lv_LV   | 2         | 0.01%   |
| lt_LT   | 2         | 0.01%   |
| hr_HR   | 2         | 0.01%   |
| et_EE   | 2         | 0.01%   |
| es_VE   | 2         | 0.01%   |
| el_GR   | 2         | 0.01%   |
| de_CH   | 2         | 0.01%   |
| da_DK   | 2         | 0.01%   |
| be_BY   | 2         | 0.01%   |
| zh_TW   | 1         | 0.004%  |
| vi_VN   | 1         | 0.004%  |
| tt_RU   | 1         | 0.004%  |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 21091     | 76.27%  |
| EFI  | 6563      | 23.73%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Unknown  | 16470     | 57.43%  |
| Ext4     | 11516     | 40.15%  |
| Btrfs    | 517       | 1.8%    |
| Ext3     | 69        | 0.24%   |
| Xfs      | 24        | 0.08%   |
| Ext2     | 24        | 0.08%   |
| Aufs     | 18        | 0.06%   |
| F2fs     | 16        | 0.06%   |
| Overlay  | 11        | 0.04%   |
| SAMSUNG  | 6         | 0.02%   |
| Reiserfs | 4         | 0.01%   |
| Jfs      | 1         | 0.003%  |
| Exfat    | 1         | 0.003%  |
| 2G       | 1         | 0.003%  |
| 20G      | 1         | 0.003%  |
| 12G      | 1         | 0.003%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| MBR     | 16836     | 57.94%  |
| GPT     | 6995      | 24.07%  |
| Unknown | 5228      | 17.99%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 24737     | 88.54%  |
| Yes       | 3203      | 11.46%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 22297     | 78.8%   |
| Yes       | 5999      | 21.2%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 7181      | 26.56%  |
| Gigabyte Technology | 3172      | 11.73%  |
| Lenovo              | 2324      | 8.6%    |
| Hewlett-Packard     | 2221      | 8.22%   |
| Acer                | 2173      | 8.04%   |
| MSI                 | 1681      | 6.22%   |
| ASRock              | 1501      | 5.55%   |
| Dell                | 1127      | 4.17%   |
| Samsung Electronics | 950       | 3.51%   |
| Toshiba             | 498       | 1.84%   |
| Intel               | 464       | 1.72%   |
| Sony                | 342       | 1.27%   |
| ECS                 | 301       | 1.11%   |
| Packard Bell        | 269       | 1%      |
| Unknown             | 261       | 0.97%   |
| Biostar             | 218       | 0.81%   |
| Pegatron            | 192       | 0.71%   |
| eMachines           | 185       | 0.68%   |
| Foxconn             | 175       | 0.65%   |
| Apple               | 129       | 0.48%   |
| Clevo               | 121       | 0.45%   |
| Fujitsu Siemens     | 117       | 0.43%   |
| Notebook            | 108       | 0.4%    |
| Fujitsu             | 95        | 0.35%   |
| DNS                 | 51        | 0.19%   |
| Huanan              | 45        | 0.17%   |
| Quanta              | 44        | 0.16%   |
| Medion              | 39        | 0.14%   |
| EPoX Computer       | 35        | 0.13%   |
| WinFast             | 33        | 0.12%   |
| DEXP                | 31        | 0.11%   |
| Aquarius            | 31        | 0.11%   |
| AMI                 | 30        | 0.11%   |
| Irbis               | 28        | 0.1%    |
| Digma               | 28        | 0.1%    |
| Supermicro          | 25        | 0.09%   |
| Prestigio           | 25        | 0.09%   |
| HUAWEI              | 25        | 0.09%   |
| IBM                 | 23        | 0.09%   |
| ICL                 | 22        | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| ASUS All Series              | 378       | 1.4%    |
| Unknown                      | 375       | 1.39%   |
| HP Pavilion g6               | 182       | 0.67%   |
| HP Pavilion dv6              | 112       | 0.41%   |
| HP Notebook                  | 85        | 0.31%   |
| ASUS M5A78L-M LX3            | 78        | 0.29%   |
| MSI MS-7817                  | 76        | 0.28%   |
| ASUS M5A97 R2.0              | 71        | 0.26%   |
| Acer Aspire V3-571G          | 70        | 0.26%   |
| Lenovo G570 20079            | 66        | 0.24%   |
| ASRock G31M-S                | 66        | 0.24%   |
| Gigabyte 970A-DS3P           | 63        | 0.23%   |
| ASRock N68C-S UCC            | 61        | 0.23%   |
| MSI MS-7529                  | 59        | 0.22%   |
| Lenovo B590 20206            | 59        | 0.22%   |
| Gigabyte G31M-ES2L           | 57        | 0.21%   |
| ASUS P5K                     | 57        | 0.21%   |
| Gigabyte H61M-S1             | 56        | 0.21%   |
| MSI MS-7592                  | 55        | 0.2%    |
| Packard Bell EasyNote TE11HC | 54        | 0.2%    |
| HP Pavilion dv7              | 53        | 0.2%    |
| Lenovo G50-30 80G0           | 52        | 0.19%   |
| HP Pavilion g7               | 51        | 0.19%   |
| ASUS P8H61-M LX3 R2.0        | 51        | 0.19%   |
| HP Pavilion 15               | 50        | 0.18%   |
| Dell Inspiron N5110          | 50        | 0.18%   |
| ASUS P5KPL-AM                | 50        | 0.18%   |
| Lenovo G500 20236            | 49        | 0.18%   |
| ASUS P5B                     | 49        | 0.18%   |
| MSI MS-7788                  | 46        | 0.17%   |
| MSI MS-7309                  | 46        | 0.17%   |
| ASUS P8Z77-V LX              | 46        | 0.17%   |
| ASUS P5G41T-M LX2/GB         | 46        | 0.17%   |
| ASUS M5A97 LE R2.0           | 46        | 0.17%   |
| Lenovo G50-45 80E3           | 44        | 0.16%   |
| Acer Aspire 5750G            | 44        | 0.16%   |
| Toshiba Satellite C660       | 43        | 0.16%   |
| ASUS P5KPL-AM IN/ROEM/SI     | 43        | 0.16%   |
| ASRock G41M-VS3              | 42        | 0.16%   |
| Acer Aspire 5742G            | 42        | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 1555      | 5.75%   |
| HP Pavilion           | 661       | 2.44%   |
| Lenovo IdeaPad        | 520       | 1.92%   |
| Dell Inspiron         | 512       | 1.89%   |
| Toshiba Satellite     | 452       | 1.67%   |
| Lenovo ThinkPad       | 379       | 1.4%    |
| ASUS All              | 378       | 1.4%    |
| Unknown               | 375       | 1.39%   |
| HP Compaq             | 361       | 1.34%   |
| ASUS PRIME            | 223       | 0.82%   |
| Packard Bell EasyNote | 212       | 0.78%   |
| HP ProBook            | 208       | 0.77%   |
| ASUS M5A78L-M         | 208       | 0.77%   |
| Dell Latitude         | 207       | 0.77%   |
| ASUS P8H61-M          | 197       | 0.73%   |
| Acer Extensa          | 178       | 0.66%   |
| ASUS P5KPL-AM         | 163       | 0.6%    |
| ASUS M5A97            | 159       | 0.59%   |
| Dell OptiPlex         | 148       | 0.55%   |
| ASUS P5K              | 145       | 0.54%   |
| ASUS P8Z77-V          | 134       | 0.5%    |
| HP Laptop             | 128       | 0.47%   |
| ASUS P5G41T-M         | 120       | 0.44%   |
| Dell Vostro           | 114       | 0.42%   |
| ASUS P5Q              | 108       | 0.4%    |
| HP EliteBook          | 104       | 0.38%   |
| Lenovo G580           | 103       | 0.38%   |
| Lenovo B590           | 100       | 0.37%   |
| Acer TravelMate       | 97        | 0.36%   |
| Lenovo ThinkCentre    | 90        | 0.33%   |
| HP Notebook           | 85        | 0.31%   |
| ASUS VivoBook         | 85        | 0.31%   |
| MSI MS-7817           | 76        | 0.28%   |
| ASUS SABERTOOTH       | 71        | 0.26%   |
| Lenovo G570           | 67        | 0.25%   |
| ASRock G31M-S         | 66        | 0.24%   |
| Gigabyte 970A-DS3P    | 64        | 0.24%   |
| ASRock N68C-S         | 63        | 0.23%   |
| HP ENVY               | 60        | 0.22%   |
| ASUS TUF              | 60        | 0.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 3817      | 14.12%  |
| 2011    | 3550      | 13.13%  |
| 2010    | 2825      | 10.45%  |
| 2009    | 2463      | 9.11%   |
| 2013    | 2282      | 8.44%   |
| 2008    | 2167      | 8.02%   |
| 2007    | 1968      | 7.28%   |
| 2014    | 1413      | 5.23%   |
| 2006    | 1160      | 4.29%   |
| 2015    | 1023      | 3.78%   |
| 2016    | 832       | 3.08%   |
| 2018    | 743       | 2.75%   |
| 2017    | 631       | 2.33%   |
| 2005    | 428       | 1.58%   |
| 2019    | 426       | 1.58%   |
| 2021    | 377       | 1.39%   |
| 2020    | 364       | 1.35%   |
| 2022    | 215       | 0.8%    |
| 2004    | 148       | 0.55%   |
| 2003    | 84        | 0.31%   |
| 2023    | 51        | 0.19%   |
| Unknown | 47        | 0.17%   |
| 2002    | 15        | 0.06%   |
| 2001    | 5         | 0.02%   |
| 2000    | 1         | 0.004%  |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 13623     | 50.39%  |
| Notebook       | 12844     | 47.51%  |
| All in one     | 284       | 1.05%   |
| Mini pc        | 131       | 0.48%   |
| Tablet         | 58        | 0.21%   |
| Server         | 51        | 0.19%   |
| Convertible    | 36        | 0.13%   |
| System on chip | 6         | 0.02%   |
| Stick pc       | 2         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 27032     | 99.98%  |
| Enabled  | 6         | 0.02%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 27026     | 99.97%  |
| Yes  | 9         | 0.03%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 9238      | 32.42%  |
| 8.01-16.0       | 4647      | 16.31%  |
| 4.01-8.0        | 4631      | 16.25%  |
| 1.01-2.0        | 3685      | 12.93%  |
| 2.01-3.0        | 2677      | 9.39%   |
| 16.01-24.0      | 1835      | 6.44%   |
| 0.51-1.0        | 763       | 2.68%   |
| 32.01-64.0      | 419       | 1.47%   |
| Unknown         | 380       | 1.33%   |
| 24.01-32.0      | 112       | 0.39%   |
| 64.01-256.0     | 64        | 0.22%   |
| 0.01-0.5        | 38        | 0.13%   |
| More than 256.0 | 7         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.51-1.0   | 13916     | 44.44%  |
| 1.01-2.0   | 12383     | 39.54%  |
| 2.01-3.0   | 2336      | 7.46%   |
| 0.01-0.5   | 1175      | 3.75%   |
| 3.01-4.0   | 594       | 1.9%    |
| Unknown    | 447       | 1.43%   |
| 4.01-8.0   | 413       | 1.32%   |
| 8.01-16.0  | 44        | 0.14%   |
| 16.01-24.0 | 8         | 0.03%   |
| 24.01-32.0 | 1         | 0.003%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 18582     | 64.91%  |
| 2       | 6615      | 23.11%  |
| 3       | 2126      | 7.43%   |
| 4       | 686       | 2.4%    |
| 5       | 255       | 0.89%   |
| 0       | 209       | 0.73%   |
| 6       | 92        | 0.32%   |
| 7       | 26        | 0.09%   |
| 8       | 14        | 0.05%   |
| Unknown | 10        | 0.03%   |
| 9       | 7         | 0.02%   |
| 10      | 2         | 0.01%   |
| 25      | 1         | 0.003%  |
| 19      | 1         | 0.003%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 17573     | 63.41%  |
| No        | 10139     | 36.59%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 26112     | 96.53%  |
| No        | 939       | 3.47%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 16471     | 60.17%  |
| No        | 10905     | 39.83%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 17797     | 64.68%  |
| Yes       | 9718      | 35.32%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Russia      | 15719     | 55.25%  |
| Unknown     | 8003      | 28.13%  |
| Ukraine     | 1115      | 3.92%   |
| Belarus     | 445       | 1.56%   |
| Germany     | 371       | 1.3%    |
| Poland      | 345       | 1.21%   |
| Kazakhstan  | 252       | 0.89%   |
| USA         | 197       | 0.69%   |
| Italy       | 193       | 0.68%   |
| France      | 176       | 0.62%   |
| Brazil      | 136       | 0.48%   |
| Spain       | 112       | 0.39%   |
| UK          | 79        | 0.28%   |
| Canada      | 76        | 0.27%   |
| Moldova     | 69        | 0.24%   |
| Romania     | 67        | 0.24%   |
| Latvia      | 54        | 0.19%   |
| Bulgaria    | 51        | 0.18%   |
| Mexico      | 47        | 0.17%   |
| Serbia      | 43        | 0.15%   |
| Czechia     | 42        | 0.15%   |
| Austria     | 36        | 0.13%   |
| Israel      | 35        | 0.12%   |
| Turkey      | 34        | 0.12%   |
| Estonia     | 34        | 0.12%   |
| Slovakia    | 32        | 0.11%   |
| Lithuania   | 30        | 0.11%   |
| Belgium     | 30        | 0.11%   |
| Australia   | 29        | 0.1%    |
| Netherlands | 28        | 0.1%    |
| Finland     | 28        | 0.1%    |
| Uzbekistan  | 27        | 0.09%   |
| Switzerland | 26        | 0.09%   |
| Colombia    | 25        | 0.09%   |
| India       | 23        | 0.08%   |
| Greece      | 23        | 0.08%   |
| Argentina   | 23        | 0.08%   |
| Hungary     | 22        | 0.08%   |
| Portugal    | 21        | 0.07%   |
| Sweden      | 20        | 0.07%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Unknown          | 8005      | 26.32%  |
| Moscow           | 2688      | 8.84%   |
| St Petersburg    | 1076      | 3.54%   |
| Pecherskoye      | 759       | 2.5%    |
| Novosibirsk      | 546       | 1.8%    |
| Krasnodar        | 494       | 1.62%   |
| Yekaterinburg    | 445       | 1.46%   |
| Samara           | 368       | 1.21%   |
| Nizhniy Novgorod | 351       | 1.15%   |
| Rostov-on-Don    | 311       | 1.02%   |
| Chelyabinsk      | 298       | 0.98%   |
| Perm             | 278       | 0.91%   |
| Voronezh         | 272       | 0.89%   |
| Krasnoyarsk      | 233       | 0.77%   |
| Saratov          | 225       | 0.74%   |
| Omsk             | 191       | 0.63%   |
| Volgograd        | 182       | 0.6%    |
| Kazan’         | 172       | 0.57%   |
| Khabarovsk       | 168       | 0.55%   |
| Minsk            | 161       | 0.53%   |
| Tyumen           | 153       | 0.5%    |
| Barnaul          | 151       | 0.5%    |
| Ufa              | 146       | 0.48%   |
| Stavropol        | 146       | 0.48%   |
| Vladivostok      | 134       | 0.44%   |
| Irkutsk          | 130       | 0.43%   |
| Yaroslavl        | 122       | 0.4%    |
| Kemerovo         | 119       | 0.39%   |
| Kyiv             | 118       | 0.39%   |
| Tula             | 112       | 0.37%   |
| Simferopol       | 107       | 0.35%   |
| Bryansk          | 107       | 0.35%   |
| Orenburg         | 106       | 0.35%   |
| Kaliningrad      | 106       | 0.35%   |
| Novokuznetsk     | 105       | 0.35%   |
| Belgorod         | 103       | 0.34%   |
| Kirov            | 100       | 0.33%   |
| Surgut           | 98        | 0.32%   |
| Tomsk            | 93        | 0.31%   |
| Tolyatti         | 91        | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9221      | 14437  | 24.2%   |
| WDC                 | 8813      | 14154  | 23.13%  |
| Hitachi             | 3043      | 4257   | 7.99%   |
| Samsung Electronics | 3010      | 4514   | 7.9%    |
| Toshiba             | 2953      | 4172   | 7.75%   |
| Kingston            | 1561      | 2170   | 4.1%    |
| HGST                | 934       | 1424   | 2.45%   |
| Unknown             | 862       | 1151   | 2.26%   |
| SanDisk             | 585       | 831    | 1.54%   |
| Maxtor              | 487       | 626    | 1.28%   |
| A-DATA Technology   | 477       | 673    | 1.25%   |
| China               | 441       | 588    | 1.16%   |
| SPCC                | 400       | 581    | 1.05%   |
| OCZ                 | 387       | 521    | 1.02%   |
| Crucial             | 357       | 502    | 0.94%   |
| Intel               | 354       | 544    | 0.93%   |
| Fujitsu             | 321       | 395    | 0.84%   |
| HUAWEI              | 286       | 336    | 0.75%   |
| Plextor             | 270       | 407    | 0.71%   |
| Apacer              | 203       | 281    | 0.53%   |
| Smartbuy            | 185       | 244    | 0.49%   |
| Transcend           | 167       | 233    | 0.44%   |
| SK hynix            | 156       | 223    | 0.41%   |
| KingSpec            | 151       | 202    | 0.4%    |
| AMD                 | 147       | 185    | 0.39%   |
| Corsair             | 138       | 183    | 0.36%   |
| Patriot             | 137       | 177    | 0.36%   |
| GOODRAM             | 137       | 182    | 0.36%   |
| Netac               | 88        | 106    | 0.23%   |
| Micron Technology   | 80        | 103    | 0.21%   |
| TF CARD             | 72        | 94     | 0.19%   |
| Gigabyte Technology | 70        | 92     | 0.18%   |
| KingDian            | 66        | 98     | 0.17%   |
| Silicon Motion      | 58        | 76     | 0.15%   |
| Apple               | 56        | 70     | 0.15%   |
| Unknown             | 56        | 62     | 0.15%   |
| JMicron Technology  | 51        | 53     | 0.13%   |
| Kingmax             | 48        | 100    | 0.13%   |
| ZTE                 | 46        | 53     | 0.12%   |
| XrayDisk            | 46        | 64     | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST500DM002-1BD142 500GB     | 506       | 1.21%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 428       | 1.03%   |
| Seagate ST500LT012-1DG142 500GB     | 393       | 0.94%   |
| Seagate ST9500325AS 500GB           | 353       | 0.85%   |
| Seagate ST3500418AS 500GB           | 345       | 0.83%   |
| Toshiba MQ01ABF050 500GB            | 319       | 0.77%   |
| Toshiba DT01ACA050 500GB            | 295       | 0.71%   |
| Kingston SV300S37A120G 120GB SSD    | 292       | 0.7%    |
| Seagate ST1000DM003-1CH162 1TB      | 290       | 0.7%    |
| Toshiba DT01ACA100 1TB              | 245       | 0.59%   |
| Seagate ST9320325AS 320GB           | 240       | 0.58%   |
| HGST HTS545050A7E680 500GB          | 230       | 0.55%   |
| Kingston SA400S37120G 120GB SSD     | 211       | 0.51%   |
| Unknown xD/SD/M.S.                  | 207       | 0.5%    |
| Seagate ST3250410AS 250GB           | 195       | 0.47%   |
| Seagate ST500LT012-9WS142 500GB     | 192       | 0.46%   |
| Hitachi HTS543232A7A384 320GB       | 189       | 0.45%   |
| Seagate ST1000DM010-2EP102 1TB      | 186       | 0.45%   |
| WDC WD5000AAKX-001CA0 500GB         | 185       | 0.44%   |
| Seagate ST9250315AS 250GB           | 182       | 0.44%   |
| Seagate ST380011A 80GB              | 182       | 0.44%   |
| Seagate ST3160815AS 160GB           | 181       | 0.43%   |
| Kingston SA400S37240G 240GB SSD     | 180       | 0.43%   |
| Toshiba HDWD110 1TB                 | 172       | 0.41%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 168       | 0.4%    |
| Seagate ST3250310AS 250GB           | 168       | 0.4%    |
| Seagate ST31000528AS 1TB            | 166       | 0.4%    |
| Toshiba MQ01ABD100 1TB              | 163       | 0.39%   |
| Seagate ST31000524AS 1TB            | 163       | 0.39%   |
| Seagate ST380815AS 80GB             | 162       | 0.39%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 161       | 0.39%   |
| WDC WD10EZEX-08WN4A0 1TB            | 160       | 0.38%   |
| Seagate ST320LT020-9YG142 320GB     | 153       | 0.37%   |
| Seagate ST1000DM003-1ER162 1TB      | 151       | 0.36%   |
| HGST HTS545050A7E380 500GB          | 150       | 0.36%   |
| Hitachi HTS547550A9E384 500GB       | 141       | 0.34%   |
| HGST HTS541010A9E680 1TB            | 137       | 0.33%   |
| HUAWEI TF CARD Storage 2GB          | 136       | 0.33%   |
| Hitachi HDS721050CLA362 500GB       | 135       | 0.32%   |
| HUAWEI SD Storage 33GB              | 134       | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9193      | 14373  | 33.77%  |
| WDC                 | 8414      | 13379  | 30.91%  |
| Hitachi             | 3043      | 4257   | 11.18%  |
| Toshiba             | 2816      | 3961   | 10.34%  |
| Samsung Electronics | 1767      | 2519   | 6.49%   |
| HGST                | 934       | 1424   | 3.43%   |
| Maxtor              | 483       | 622    | 1.77%   |
| Fujitsu             | 319       | 392    | 1.17%   |
| JMicron Technology  | 42        | 45     | 0.15%   |
| Unknown             | 31        | 48     | 0.11%   |
| IBM/Hitachi         | 31        | 36     | 0.11%   |
| Apple               | 29        | 36     | 0.11%   |
| TO Exter            | 17        | 20     | 0.06%   |
| External            | 14        | 16     | 0.05%   |
| ExcelStor           | 13        | 20     | 0.05%   |
| Hewlett-Packard     | 12        | 23     | 0.04%   |
| WD MediaMax         | 8         | 12     | 0.03%   |
| Quantum             | 6         | 6      | 0.02%   |
| IBM                 | 6         | 9      | 0.02%   |
| ASMT                | 6         | 21     | 0.02%   |
| HGST HTS            | 4         | 4      | 0.01%   |
| Magnetic Data       | 3         | 3      | 0.01%   |
| Intenso             | 3         | 3      | 0.01%   |
| Unknown             | 3         | 3      | 0.01%   |
| StoreJet            | 2         | 2      | 0.01%   |
| MARSHAL             | 2         | 3      | 0.01%   |
| FC-1307             | 2         | 2      | 0.01%   |
| CLOVER              | 2         | 2      | 0.01%   |
| ZALMAN              | 1         | 1      | 0.004%  |
| USB3.0              | 1         | 1      | 0.004%  |
| USB 3.0             | 1         | 1      | 0.004%  |
| Unknown (CF)        | 1         | 1      | 0.004%  |
| TPH01204000GB       | 1         | 1      | 0.004%  |
| TPH00100500GB       | 1         | 1      | 0.004%  |
| Speeding            | 1         | 1      | 0.004%  |
| SILICONMOTION       | 1         | 1      | 0.004%  |
| Silicon             | 1         | 1      | 0.004%  |
| SAGE                | 1         | 1      | 0.004%  |
| OEM                 | 1         | 2      | 0.004%  |
| MR2020              | 1         | 1      | 0.004%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 1441      | 1992   | 17.21%  |
| Samsung Electronics | 989       | 1524   | 11.81%  |
| SanDisk             | 496       | 721    | 5.92%   |
| WDC                 | 449       | 602    | 5.36%   |
| China               | 439       | 586    | 5.24%   |
| A-DATA Technology   | 410       | 558    | 4.9%    |
| OCZ                 | 386       | 520    | 4.61%   |
| SPCC                | 385       | 561    | 4.6%    |
| Crucial             | 343       | 467    | 4.1%    |
| Intel               | 276       | 426    | 3.3%    |
| Plextor             | 261       | 391    | 3.12%   |
| Apacer              | 180       | 247    | 2.15%   |
| Smartbuy            | 178       | 235    | 2.13%   |
| Transcend           | 157       | 213    | 1.88%   |
| KingSpec            | 149       | 200    | 1.78%   |
| Corsair             | 136       | 180    | 1.62%   |
| AMD                 | 136       | 166    | 1.62%   |
| GOODRAM             | 133       | 178    | 1.59%   |
| Patriot             | 126       | 166    | 1.51%   |
| Toshiba             | 121       | 174    | 1.45%   |
| Netac               | 70        | 83     | 0.84%   |
| KingDian            | 65        | 97     | 0.78%   |
| Gigabyte Technology | 50        | 61     | 0.6%    |
| SK hynix            | 49        | 72     | 0.59%   |
| Kingmax             | 48        | 100    | 0.57%   |
| Micron Technology   | 45        | 57     | 0.54%   |
| XrayDisk            | 40        | 58     | 0.48%   |
| Team                | 37        | 46     | 0.44%   |
| Unknown             | 36        | 41     | 0.43%   |
| LITEONIT            | 33        | 50     | 0.39%   |
| KingFast            | 28        | 36     | 0.33%   |
| LITEON              | 27        | 39     | 0.32%   |
| Apple               | 25        | 31     | 0.3%    |
| PNY                 | 24        | 29     | 0.29%   |
| Intenso             | 24        | 33     | 0.29%   |
| OCZ-VERTEX3         | 22        | 34     | 0.26%   |
| Foxline             | 22        | 31     | 0.26%   |
| Hewlett-Packard     | 20        | 28     | 0.24%   |
| Zheino              | 18        | 24     | 0.22%   |
| Qumo                | 17        | 24     | 0.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 22869     | 41259  | 69.45%  |
| SSD     | 7407      | 11750  | 22.49%  |
| NVMe    | 1271      | 1922   | 3.86%   |
| Unknown | 709       | 862    | 2.15%   |
| MMC     | 672       | 916    | 2.04%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 26003     | 52506  | 89.62%  |
| NVMe | 1269      | 1919   | 4.37%   |
| SAS  | 1070      | 1368   | 3.69%   |
| MMC  | 672       | 916    | 2.32%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 22359     | 39062  | 72.7%   |
| 0.51-1.0        | 6923      | 11478  | 22.51%  |
| 1.01-2.0        | 1056      | 1768   | 3.43%   |
| 2.01-3.0        | 217       | 327    | 0.71%   |
| 3.01-4.0        | 131       | 227    | 0.43%   |
| 4.01-10.0       | 59        | 134    | 0.19%   |
| More than 100.0 | 6         | 7      | 0.02%   |
| 10.01-20.0      | 5         | 6      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 7995      | 25.6%   |
| 251-500        | 6887      | 22.05%  |
| 1-20           | 4321      | 13.84%  |
| 51-100         | 3523      | 11.28%  |
| 501-1000       | 3370      | 10.79%  |
| 21-50          | 2660      | 8.52%   |
| 1001-2000      | 1390      | 4.45%   |
| Unknown        | 458       | 1.47%   |
| 2001-3000      | 367       | 1.18%   |
| More than 3000 | 259       | 0.83%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 20069     | 64.37%  |
| 21-50          | 3051      | 9.79%   |
| 101-250        | 2339      | 7.5%    |
| 51-100         | 2034      | 6.52%   |
| 251-500        | 1580      | 5.07%   |
| 501-1000       | 1031      | 3.31%   |
| Unknown        | 458       | 1.47%   |
| 1001-2000      | 428       | 1.37%   |
| 2001-3000      | 99        | 0.32%   |
| More than 3000 | 88        | 0.28%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB          | 257       | 353    | 1.98%   |
| Seagate ST500DM002-1BD142 500GB    | 205       | 269    | 1.58%   |
| Seagate ST500LT012-9WS142 500GB    | 187       | 233    | 1.44%   |
| Seagate ST3500418AS 500GB          | 173       | 238    | 1.33%   |
| Seagate ST9320325AS 320GB          | 142       | 181    | 1.09%   |
| Seagate ST9250315AS 250GB          | 124       | 154    | 0.96%   |
| Seagate ST3250410AS 250GB          | 124       | 159    | 0.96%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 116       | 138    | 0.89%   |
| Seagate ST3250310AS 250GB          | 112       | 170    | 0.86%   |
| Seagate ST500LT012-1DG142 500GB    | 108       | 133    | 0.83%   |
| HGST HTS545050A7E680 500GB         | 105       | 143    | 0.81%   |
| WDC WD5000AAKX-001CA0 500GB        | 100       | 127    | 0.77%   |
| Seagate ST320LT020-9YG142 320GB    | 97        | 136    | 0.75%   |
| Seagate ST3320613AS 320GB          | 83        | 116    | 0.64%   |
| Hitachi HTS543232A7A384 320GB      | 83        | 101    | 0.64%   |
| Seagate ST31000528AS 1TB           | 82        | 110    | 0.63%   |
| HGST HTS545050A7E380 500GB         | 74        | 118    | 0.57%   |
| Seagate ST3160815AS 160GB          | 72        | 85     | 0.55%   |
| Hitachi HTS545025B9A300 250GB      | 69        | 90     | 0.53%   |
| WDC WD5000AADS-00S9B0 500GB        | 67        | 80     | 0.52%   |
| Seagate ST380011A 80GB             | 66        | 75     | 0.51%   |
| Samsung Electronics HD080HJ 80GB   | 66        | 81     | 0.51%   |
| Seagate ST1000DM003-1CH162 1TB     | 65        | 94     | 0.5%    |
| Seagate ST3160811AS 160GB          | 64        | 90     | 0.49%   |
| Seagate ST31000524AS 1TB           | 63        | 91     | 0.49%   |
| Hitachi HTS541612J9SA00 120GB      | 61        | 75     | 0.47%   |
| Seagate ST320LT012-9WS14C 320GB    | 60        | 86     | 0.46%   |
| Hitachi HDS721616PLA380 160GB      | 60        | 78     | 0.46%   |
| Hitachi HTS547550A9E384 500GB      | 58        | 79     | 0.45%   |
| Toshiba MQ01ABD050 500GB           | 57        | 73     | 0.44%   |
| Seagate ST1000DM003-9YN162 1TB     | 56        | 68     | 0.43%   |
| Hitachi HDS721050CLA362 500GB      | 56        | 71     | 0.43%   |
| Seagate ST3250318AS 250GB          | 55        | 75     | 0.42%   |
| Samsung Electronics HD160JJ 160GB  | 55        | 85     | 0.42%   |
| Hitachi HTS545050B9A300 500GB      | 55        | 77     | 0.42%   |
| Hitachi HDP725050GLA360 500GB      | 55        | 73     | 0.42%   |
| Hitachi HTS547575A9E384 752GB      | 54        | 77     | 0.42%   |
| Toshiba MQ01ABF050 500GB           | 53        | 61     | 0.41%   |
| Seagate ST380815AS 80GB            | 52        | 65     | 0.4%    |
| WDC WD3200AAJS-00L7A0 320GB        | 51        | 60     | 0.39%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4228      | 5925   | 34.11%  |
| WDC                 | 2933      | 4095   | 23.66%  |
| Hitachi             | 1652      | 2216   | 13.33%  |
| Samsung Electronics | 957       | 1290   | 7.72%   |
| Toshiba             | 909       | 1205   | 7.33%   |
| HGST                | 312       | 444    | 2.52%   |
| Maxtor              | 286       | 355    | 2.31%   |
| Kingston            | 188       | 230    | 1.52%   |
| Fujitsu             | 135       | 170    | 1.09%   |
| SanDisk             | 84        | 102    | 0.68%   |
| OCZ                 | 75        | 105    | 0.61%   |
| SPCC                | 70        | 88     | 0.56%   |
| Intel               | 67        | 82     | 0.54%   |
| A-DATA Technology   | 55        | 79     | 0.44%   |
| Corsair             | 42        | 52     | 0.34%   |
| China               | 33        | 42     | 0.27%   |
| Kingmax             | 32        | 61     | 0.26%   |
| Crucial             | 31        | 48     | 0.25%   |
| IBM/Hitachi         | 27        | 32     | 0.22%   |
| KingSpec            | 24        | 35     | 0.19%   |
| Plextor             | 20        | 28     | 0.16%   |
| AMD                 | 19        | 23     | 0.15%   |
| SK hynix            | 17        | 22     | 0.14%   |
| Netac               | 13        | 14     | 0.1%    |
| LITEONIT            | 12        | 17     | 0.1%    |
| Transcend           | 9         | 11     | 0.07%   |
| ExcelStor           | 9         | 11     | 0.07%   |
| OCZ-VERTEX3         | 8         | 16     | 0.06%   |
| Unknown             | 8         | 10     | 0.06%   |
| Micron Technology   | 7         | 12     | 0.06%   |
| Apple               | 7         | 8      | 0.06%   |
| Patriot             | 6         | 6      | 0.05%   |
| Apacer              | 6         | 11     | 0.05%   |
| Neo                 | 5         | 8      | 0.04%   |
| Mushkin             | 5         | 5      | 0.04%   |
| IBM                 | 5         | 7      | 0.04%   |
| Hewlett-Packard     | 5         | 6      | 0.04%   |
| Smartbuy            | 4         | 5      | 0.03%   |
| PNY                 | 4         | 7      | 0.03%   |
| KingDian            | 4         | 5      | 0.03%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4228      | 5925   | 37.15%  |
| WDC                 | 2884      | 4023   | 25.34%  |
| Hitachi             | 1652      | 2216   | 14.52%  |
| Samsung Electronics | 917       | 1239   | 8.06%   |
| Toshiba             | 903       | 1199   | 7.93%   |
| HGST                | 312       | 444    | 2.74%   |
| Maxtor              | 286       | 355    | 2.51%   |
| Fujitsu             | 135       | 170    | 1.19%   |
| IBM/Hitachi         | 27        | 32     | 0.24%   |
| ExcelStor           | 9         | 11     | 0.08%   |
| IBM                 | 5         | 7      | 0.04%   |
| Apple               | 5         | 6      | 0.04%   |
| WD MediaMax         | 3         | 5      | 0.03%   |
| Hewlett-Packard     | 3         | 4      | 0.03%   |
| Quantum             | 2         | 2      | 0.02%   |
| MARSHAL             | 2         | 3      | 0.02%   |
| ASMT                | 2         | 4      | 0.02%   |
| TPH00100500GB       | 1         | 1      | 0.01%   |
| Magnetic Data       | 1         | 1      | 0.01%   |
| LaCie               | 1         | 1      | 0.01%   |
| HGST HTS            | 1         | 1      | 0.01%   |
| External            | 1         | 1      | 0.01%   |
| Unknown             | 1         | 1      | 0.01%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10416     | 15651  | 91.21%  |
| SSD  | 976       | 1308   | 8.55%   |
| NVMe | 28        | 36     | 0.25%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST3500418AS 500GB          | 13        | 14     | 3.16%   |
| Seagate ST31000528AS 1TB           | 12        | 14     | 2.91%   |
| Seagate ST9500325AS 500GB          | 7         | 9      | 1.7%    |
| Seagate ST31000524AS 1TB           | 7         | 8      | 1.7%    |
| Samsung Electronics HM321HI 320GB  | 7         | 9      | 1.7%    |
| Hitachi HDS721010DLE630 1TB        | 7         | 9      | 1.7%    |
| HGST HTS545050A7E680 500GB         | 7         | 7      | 1.7%    |
| WDC WD3200BEVT-22ZCT0 320GB        | 6         | 7      | 1.46%   |
| Seagate ST3500412AS 500GB          | 6         | 8      | 1.46%   |
| WDC WD1600BEVT-22ZCT0 160GB        | 5         | 6      | 1.21%   |
| Seagate ST9320325AS 320GB          | 5         | 6      | 1.21%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 5         | 5      | 1.21%   |
| Samsung Electronics HD502HJ 500GB  | 5         | 5      | 1.21%   |
| HGST HTS545050A7E380 500GB         | 5         | 5      | 1.21%   |
| Toshiba MQ01ABD050 500GB           | 4         | 4      | 0.97%   |
| Toshiba MK6465GSX 640GB            | 4         | 6      | 0.97%   |
| Toshiba MK3265GSX 320GB            | 4         | 4      | 0.97%   |
| Seagate ST9250315AS 250GB          | 4         | 4      | 0.97%   |
| Seagate ST500LT012-1DG142 500GB    | 4         | 4      | 0.97%   |
| Seagate ST3500410AS 500GB          | 4         | 5      | 0.97%   |
| Seagate ST31000333AS 1TB           | 4         | 4      | 0.97%   |
| Samsung Electronics SP0411N 40GB   | 4         | 5      | 0.97%   |
| Samsung Electronics HD502IJ 500GB  | 4         | 4      | 0.97%   |
| Samsung Electronics HD322GJ 320GB  | 4         | 5      | 0.97%   |
| Hitachi HTS547550A9E384 500GB      | 4         | 5      | 0.97%   |
| WDC WD5000AAKS-00V1A0 500GB        | 3         | 4      | 0.73%   |
| WDC WD3200BPVT-22JJ5T0 320GB       | 3         | 3      | 0.73%   |
| WDC WD3200AAJS-00L7A0 320GB        | 3         | 4      | 0.73%   |
| WDC WD1600BEVS-22RST0 160GB        | 3         | 4      | 0.73%   |
| WDC WD15EARS-00MVWB0 1TB           | 3         | 6      | 0.73%   |
| Seagate ST3750528AS 752GB          | 3         | 3      | 0.73%   |
| Seagate ST3320613AS 320GB          | 3         | 4      | 0.73%   |
| Seagate ST32000542AS 2TB           | 3         | 5      | 0.73%   |
| Samsung Electronics HM160HI 160GB  | 3         | 3      | 0.73%   |
| Maxtor 6Y080L0 82GB                | 3         | 3      | 0.73%   |
| Hitachi HTS547575A9E384 752GB      | 3         | 3      | 0.73%   |
| Hitachi HTS545050A7E380 500GB      | 3         | 3      | 0.73%   |
| Hitachi HDS721050DLE630 500GB      | 3         | 3      | 0.73%   |
| HGST HTS721010A9E630 1TB           | 3         | 4      | 0.73%   |
| HGST HTS541010A9E680 1TB           | 3         | 4      | 0.73%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 125       | 152    | 30.49%  |
| WDC                 | 105       | 125    | 25.61%  |
| Samsung Electronics | 64        | 73     | 15.61%  |
| Toshiba             | 40        | 46     | 9.76%   |
| Hitachi             | 40        | 44     | 9.76%   |
| HGST                | 20        | 23     | 4.88%   |
| Maxtor              | 10        | 10     | 2.44%   |
| Fujitsu             | 2         | 2      | 0.49%   |
| Apple               | 2         | 3      | 0.49%   |
| Hewlett-Packard     | 1         | 1      | 0.24%   |
| Corsair             | 1         | 1      | 0.24%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 19034     | 35967  | 57.94%  |
| Malfunc  | 11158     | 16995  | 33.96%  |
| Detected | 2255      | 3267   | 6.86%   |
| Failed   | 407       | 480    | 1.24%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 18990     | 62.42%  |
| AMD                              | 5749      | 18.9%   |
| Nvidia                           | 1539      | 5.06%   |
| JMicron Technology               | 1122      | 3.69%   |
| Marvell Technology Group         | 606       | 1.99%   |
| ASMedia Technology               | 386       | 1.27%   |
| VIA Technologies                 | 336       | 1.1%    |
| Samsung Electronics              | 335       | 1.1%    |
| Silicon Integrated Systems [SiS] | 190       | 0.62%   |
| SanDisk                          | 139       | 0.46%   |
| Kingston Technology Company      | 139       | 0.46%   |
| Silicon Motion                   | 130       | 0.43%   |
| Phison Electronics               | 100       | 0.33%   |
| SK hynix                         | 83        | 0.27%   |
| ADATA Technology                 | 72        | 0.24%   |
| Silicon Image                    | 56        | 0.18%   |
| Realtek Semiconductor            | 49        | 0.16%   |
| Integrated Technology Express    | 42        | 0.14%   |
| Micron Technology                | 35        | 0.12%   |
| MAXIO Technology (Hangzhou)      | 31        | 0.1%    |
| KIOXIA                           | 30        | 0.1%    |
| INNOGRIT                         | 28        | 0.09%   |
| Micron/Crucial Technology        | 20        | 0.07%   |
| LSI Logic / Symbios Logic        | 20        | 0.07%   |
| Toshiba America Info Systems     | 18        | 0.06%   |
| Lite-On Technology               | 18        | 0.06%   |
| Netac Technology                 | 17        | 0.06%   |
| ULi Electronics                  | 16        | 0.05%   |
| Solid State Storage Technology   | 15        | 0.05%   |
| Union Memory (Shenzhen)          | 14        | 0.05%   |
| Adaptec                          | 14        | 0.05%   |
| Hewlett-Packard                  | 11        | 0.04%   |
| Shenzhen Longsys Electronics     | 10        | 0.03%   |
| Promise Technology               | 7         | 0.02%   |
| OCZ Technology Group             | 7         | 0.02%   |
| Shenzhen Shichuangyi Electronics | 6         | 0.02%   |
| Lite-On IT Corp. / Plextor       | 6         | 0.02%   |
| Broadcom / LSI                   | 6         | 0.02%   |
| Transcend                        | 3         | 0.01%   |
| Hosin Global Electronics         | 3         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 2226      | 5.48%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2087      | 5.14%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 1835      | 4.52%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1737      | 4.28%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1692      | 4.17%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1533      | 3.77%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 1279      | 3.15%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1208      | 2.97%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 1128      | 2.78%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 877       | 2.16%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 734       | 1.81%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 733       | 1.8%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 731       | 1.8%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 717       | 1.77%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 690       | 1.7%    |
| Nvidia MCP61 SATA Controller                                                            | 668       | 1.64%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 637       | 1.57%   |
| Nvidia MCP61 IDE                                                                        | 623       | 1.53%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 556       | 1.37%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 549       | 1.35%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 511       | 1.26%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 464       | 1.14%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 453       | 1.12%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 434       | 1.07%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 433       | 1.07%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 429       | 1.06%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 407       | 1%      |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 393       | 0.97%   |
| JMicron JMB368 IDE controller                                                           | 386       | 0.95%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 367       | 0.9%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 340       | 0.84%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 332       | 0.82%   |
| AMD SB600 Non-Raid-5 SATA                                                               | 329       | 0.81%   |
| AMD SB600 IDE                                                                           | 326       | 0.8%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 320       | 0.79%   |
| AMD FCH IDE Controller                                                                  | 319       | 0.79%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 313       | 0.77%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 282       | 0.69%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 241       | 0.59%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 240       | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 18764     | 58.75%  |
| IDE  | 11173     | 34.98%  |
| NVMe | 1274      | 3.99%   |
| RAID | 678       | 2.12%   |
| SCSI | 25        | 0.08%   |
| SAS  | 23        | 0.07%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 19910     | 73.64%  |
| AMD          | 7106      | 26.28%  |
| CentaurHauls | 12        | 0.04%   |
| ARM          | 7         | 0.03%   |
| MBE8C-PC     | 1         | 0.004%  |
| E8C-mITX     | 1         | 0.004%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 245       | 0.9%    |
| Intel Core i5-3210M CPU @ 2.50GHz           | 225       | 0.83%   |
| Intel Pentium 4 CPU 3.00GHz                 | 200       | 0.73%   |
| Intel Atom CPU N450 @ 1.66GHz               | 174       | 0.64%   |
| Intel Pentium CPU B960 @ 2.20GHz            | 168       | 0.62%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 162       | 0.59%   |
| AMD Athlon II X2 250 Processor              | 161       | 0.59%   |
| Intel Atom CPU N270 @ 1.60GHz               | 159       | 0.58%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 156       | 0.57%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 155       | 0.57%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 150       | 0.55%   |
| AMD FX-6300 Six-Core Processor              | 148       | 0.54%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 147       | 0.54%   |
| AMD E-450 APU with Radeon HD Graphics       | 142       | 0.52%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 141       | 0.52%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 137       | 0.5%    |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 137       | 0.5%    |
| Intel Core i5-2430M CPU @ 2.40GHz           | 134       | 0.49%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 134       | 0.49%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 132       | 0.48%   |
| Intel Atom CPU N2600 @ 1.60GHz              | 132       | 0.48%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 129       | 0.47%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 126       | 0.46%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 124       | 0.45%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 119       | 0.44%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 116       | 0.43%   |
| Intel Atom CPU N455 @ 1.66GHz               | 116       | 0.43%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 115       | 0.42%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 114       | 0.42%   |
| Intel Pentium CPU 2020M @ 2.40GHz           | 108       | 0.4%    |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 106       | 0.39%   |
| Intel Atom CPU N570 @ 1.66GHz               | 106       | 0.39%   |
| AMD FX-8350 Eight-Core Processor            | 106       | 0.39%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 104       | 0.38%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 100       | 0.37%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 98        | 0.36%   |
| Intel Core i3-2330M CPU @ 2.20GHz           | 93        | 0.34%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 91        | 0.33%   |
| Intel Celeron CPU N3050 @ 1.60GHz           | 87        | 0.32%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 85        | 0.31%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 3896      | 14.32%  |
| Intel Core i3           | 2891      | 10.63%  |
| Intel Core 2 Duo        | 2128      | 7.82%   |
| Intel Celeron           | 2018      | 7.42%   |
| Intel Pentium           | 1813      | 6.66%   |
| Intel Core i7           | 1651      | 6.07%   |
| Intel Atom              | 1237      | 4.55%   |
| Intel Pentium Dual-Core | 873       | 3.21%   |
| AMD FX                  | 755       | 2.78%   |
| AMD Athlon 64 X2        | 734       | 2.7%    |
| AMD Athlon II X2        | 525       | 1.93%   |
| Intel Core 2 Quad       | 489       | 1.8%    |
| Intel Xeon              | 469       | 1.72%   |
| Intel Pentium 4         | 461       | 1.69%   |
| Intel Core 2            | 420       | 1.54%   |
| Intel Pentium Dual      | 413       | 1.52%   |
| AMD Ryzen 5             | 396       | 1.46%   |
| AMD A6                  | 364       | 1.34%   |
| AMD A4                  | 342       | 1.26%   |
| AMD A8                  | 337       | 1.24%   |
| AMD Phenom II X4        | 326       | 1.2%    |
| Other                   | 298       | 1.1%    |
| AMD A10                 | 291       | 1.07%   |
| AMD E                   | 282       | 1.04%   |
| Intel Genuine           | 240       | 0.88%   |
| AMD Athlon II X4        | 221       | 0.81%   |
| AMD E1                  | 183       | 0.67%   |
| AMD Ryzen 7             | 178       | 0.65%   |
| Intel Pentium D         | 173       | 0.64%   |
| AMD Athlon II X3        | 165       | 0.61%   |
| AMD Athlon 64           | 162       | 0.6%    |
| AMD Ryzen 3             | 148       | 0.54%   |
| Intel Celeron M         | 142       | 0.52%   |
| Intel Celeron Dual-Core | 123       | 0.45%   |
| AMD Turion 64 X2 Mobile | 122       | 0.45%   |
| AMD Athlon              | 119       | 0.44%   |
| AMD E2                  | 118       | 0.43%   |
| AMD Phenom              | 117       | 0.43%   |
| AMD Sempron             | 112       | 0.41%   |
| AMD Phenom II           | 105       | 0.39%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 15730     | 56.75%  |
| 4       | 6119      | 22.08%  |
| 1       | 2224      | 8.02%   |
| Unknown | 1870      | 6.75%   |
| 6       | 812       | 2.93%   |
| 3       | 459       | 1.66%   |
| 8       | 361       | 1.3%    |
| 12      | 51        | 0.18%   |
| 10      | 36        | 0.13%   |
| 16      | 18        | 0.06%   |
| 20      | 9         | 0.03%   |
| 14      | 9         | 0.03%   |
| 24      | 8         | 0.03%   |
| 18      | 4         | 0.01%   |
| 192     | 2         | 0.01%   |
| 64      | 2         | 0.01%   |
| 28      | 2         | 0.01%   |
| 120     | 1         | 0.004%  |
| 56      | 1         | 0.004%  |
| 5       | 1         | 0.004%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 26848     | 99.02%  |
| Unknown | 159       | 0.59%   |
| 2       | 99        | 0.37%   |
| 4       | 7         | 0.03%   |
| 8       | 2         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 15356     | 55.42%  |
| 2       | 10483     | 37.83%  |
| Unknown | 1870      | 6.75%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 25481     | 93.36%  |
| 32-bit         | 1005      | 3.68%   |
| Unknown        | 627       | 2.3%    |
| 64-bit         | 179       | 0.66%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x206a7    | 3046      | 10.99%  |
| 0x306a9    | 2490      | 8.98%   |
| 0x1067a    | 2237      | 8.07%   |
| Unknown    | 1822      | 6.57%   |
| 0x306c3    | 1331      | 4.8%    |
| 0x6fd      | 1021      | 3.68%   |
| 0x010000c8 | 945       | 3.41%   |
| 0x20655    | 834       | 3.01%   |
| 0x10676    | 631       | 2.28%   |
| 0x106ca    | 564       | 2.04%   |
| 0x06001119 | 519       | 1.87%   |
| 0x30678    | 468       | 1.69%   |
| 0x40651    | 458       | 1.65%   |
| 0x6fb      | 442       | 1.59%   |
| 0x506e3    | 359       | 1.3%    |
| 0x20652    | 345       | 1.24%   |
| 0x6f6      | 296       | 1.07%   |
| 0x906e9    | 285       | 1.03%   |
| 0x03000027 | 271       | 0.98%   |
| 0x106c2    | 256       | 0.92%   |
| 0x05000119 | 240       | 0.87%   |
| 0x30661    | 234       | 0.84%   |
| 0x10661    | 232       | 0.84%   |
| 0x306d4    | 228       | 0.82%   |
| 0x0600084f | 222       | 0.8%    |
| 0x906ea    | 221       | 0.8%    |
| 0x406c4    | 208       | 0.75%   |
| 0x106e5    | 202       | 0.73%   |
| 0x06000852 | 195       | 0.7%    |
| 0x406e3    | 193       | 0.7%    |
| 0x010000b6 | 187       | 0.67%   |
| 0x07030105 | 173       | 0.62%   |
| 0x406c3    | 171       | 0.62%   |
| 0x6f2      | 167       | 0.6%    |
| 0x010000db | 164       | 0.59%   |
| 0xf41      | 140       | 0.51%   |
| 0x6e8      | 140       | 0.51%   |
| 0x06003106 | 140       | 0.51%   |
| 0x806e9    | 136       | 0.49%   |
| 0xf49      | 134       | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| SandyBridge      | 3127      | 11.48%  |
| Penryn           | 2883      | 10.58%  |
| IvyBridge        | 2561      | 9.4%    |
| Core             | 2358      | 8.66%   |
| K10              | 1906      | 7%      |
| Haswell          | 1881      | 6.91%   |
| Westmere         | 1223      | 4.49%   |
| K8 Hammer        | 1158      | 4.25%   |
| Piledriver       | 1143      | 4.2%    |
| Bonnell          | 998       | 3.66%   |
| KabyLake         | 957       | 3.51%   |
| Silvermont       | 926       | 3.4%    |
| NetBurst         | 821       | 3.01%   |
| Skylake          | 587       | 2.15%   |
| Bobcat           | 488       | 1.79%   |
| Unknown          | 454       | 1.67%   |
| P6               | 358       | 1.31%   |
| K10 Llano        | 334       | 1.23%   |
| Nehalem          | 281       | 1.03%   |
| Broadwell        | 250       | 0.92%   |
| Zen+             | 244       | 0.9%    |
| Zen              | 230       | 0.84%   |
| Puma             | 222       | 0.82%   |
| Excavator        | 207       | 0.76%   |
| Bulldozer        | 196       | 0.72%   |
| Jaguar           | 184       | 0.68%   |
| Zen 2            | 169       | 0.62%   |
| Steamroller      | 160       | 0.59%   |
| CometLake        | 157       | 0.58%   |
| Zen 3            | 146       | 0.54%   |
| Goldmont plus    | 131       | 0.48%   |
| K8 & K10 hybrid  | 123       | 0.45%   |
| Goldmont         | 105       | 0.39%   |
| TigerLake        | 97        | 0.36%   |
| Icelake          | 66        | 0.24%   |
| Alderlake Hybrid | 57        | 0.21%   |
| K6               | 26        | 0.1%    |
| Tremont          | 20        | 0.07%   |
| Gracemont        | 5         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 11832     | 37.92%  |
| Nvidia                           | 11207     | 35.92%  |
| AMD                              | 7983      | 25.59%  |
| Silicon Integrated Systems [SiS] | 62        | 0.2%    |
| VIA Technologies                 | 49        | 0.16%   |
| Matrox Electronics Systems       | 29        | 0.09%   |
| ASPEED Technology                | 22        | 0.07%   |
| ATI Technologies                 | 8         | 0.03%   |
| S3 Graphics                      | 6         | 0.02%   |
| Zhaoxin                          | 1         | 0.003%  |
| Trident Microsystems             | 1         | 0.003%  |
| Huawei Technologies              | 1         | 0.003%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2142      | 6.39%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1442      | 4.3%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 601       | 1.79%   |
| Intel Core Processor Integrated Graphics Controller                                      | 593       | 1.77%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 535       | 1.6%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 533       | 1.59%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 458       | 1.37%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 439       | 1.31%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 398       | 1.19%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 393       | 1.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 386       | 1.15%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 385       | 1.15%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 385       | 1.15%   |
| Nvidia GT218 [GeForce 210]                                                               | 384       | 1.15%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 334       | 1%      |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 297       | 0.89%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 292       | 0.87%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 289       | 0.86%   |
| Nvidia G94 [GeForce 9600 GT]                                                             | 253       | 0.76%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 253       | 0.76%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 245       | 0.73%   |
| Nvidia GK107 [GeForce GTX 650]                                                           | 241       | 0.72%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 235       | 0.7%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 234       | 0.7%    |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 232       | 0.69%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 224       | 0.67%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 223       | 0.67%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 223       | 0.67%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                                        | 222       | 0.66%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 205       | 0.61%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 203       | 0.61%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 198       | 0.59%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 192       | 0.57%   |
| Intel HD Graphics 5500                                                                   | 186       | 0.56%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 185       | 0.55%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 175       | 0.52%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 173       | 0.52%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 173       | 0.52%   |
| Nvidia GF108 [GeForce GT 440]                                                            | 172       | 0.51%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 172       | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                          | Computers | Percent |
|-------------------------------|-----------|---------|
| 1 x Nvidia                    | 8304      | 30.24%  |
| 1 x Intel                     | 8139      | 29.64%  |
| 1 x AMD                       | 6116      | 22.27%  |
| Intel + Nvidia                | 2781      | 10.13%  |
| 2 x AMD                       | 1100      | 4.01%   |
| Intel + AMD                   | 702       | 2.56%   |
| AMD + Nvidia                  | 89        | 0.32%   |
| 1 x SiS                       | 62        | 0.23%   |
| 1 x VIA                       | 49        | 0.18%   |
| 2 x Nvidia                    | 34        | 0.12%   |
| 1 x Matrox                    | 20        | 0.07%   |
| Other                         | 19        | 0.07%   |
| 1 x ASPEED                    | 15        | 0.05%   |
| Nvidia + Matrox               | 9         | 0.03%   |
| 1 x S3 Graphics               | 4         | 0.01%   |
| AMD + ASPEED                  | 4         | 0.01%   |
| 3 x AMD                       | 3         | 0.01%   |
| 3 x Nvidia                    | 2         | 0.01%   |
| Nvidia + ASPEED               | 2         | 0.01%   |
| 2 x AMD + 1 x Nvidia          | 1         | 0.004%  |
| 1 x Zhaoxin                   | 1         | 0.004%  |
| 1 x Trident Microsystems      | 1         | 0.004%  |
| Intel + 2 x Nvidia            | 1         | 0.004%  |
| Intel + 2 x AMD               | 1         | 0.004%  |
| Intel + SiS + 1 x S3 Graphics | 1         | 0.004%  |
| Intel + S3 Graphics           | 1         | 0.004%  |
| Intel + ASPEED                | 1         | 0.004%  |
| 1 x Huawei Technologies       | 1         | 0.004%  |
| AMD + 2 x Nvidia              | 1         | 0.004%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 23043     | 80.9%   |
| Proprietary | 3842      | 13.49%  |
| Unknown     | 1597      | 5.61%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 8563      | 29.67%  |
| 0.01-0.5   | 7531      | 26.09%  |
| Unknown    | 6521      | 22.59%  |
| 0.51-1.0   | 4100      | 14.21%  |
| 3.01-4.0   | 1483      | 5.14%   |
| 7.01-8.0   | 278       | 0.96%   |
| 2.01-3.0   | 165       | 0.57%   |
| 5.01-6.0   | 160       | 0.55%   |
| 8.01-16.0  | 59        | 0.2%    |
| 16.01-24.0 | 1         | 0.003%  |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 5785      | 21.54%  |
| AU Optronics            | 2915      | 10.85%  |
| LG Display              | 2317      | 8.63%   |
| Goldstar                | 2291      | 8.53%   |
| Acer                    | 1593      | 5.93%   |
| Chi Mei Optoelectronics | 1221      | 4.55%   |
| BenQ                    | 1110      | 4.13%   |
| Chimei Innolux          | 1066      | 3.97%   |
| Philips                 | 943       | 3.51%   |
| BOE                     | 771       | 2.87%   |
| ViewSonic               | 655       | 2.44%   |
| Dell                    | 582       | 2.17%   |
| Ancor Communications    | 549       | 2.04%   |
| AOC                     | 512       | 1.91%   |
| Hewlett-Packard         | 455       | 1.69%   |
| LG Philips              | 437       | 1.63%   |
| Lenovo                  | 410       | 1.53%   |
| HannStar                | 328       | 1.22%   |
| NEC Computers           | 319       | 1.19%   |
| Sony                    | 218       | 0.81%   |
| CPT                     | 187       | 0.7%    |
| Iiyama                  | 149       | 0.55%   |
| InfoVision              | 132       | 0.49%   |
| Apple                   | 128       | 0.48%   |
| Toshiba                 | 81        | 0.3%    |
| Plain Tree Systems      | 80        | 0.3%    |
| Envision Peripherals    | 58        | 0.22%   |
| Fujitsu Siemens         | 57        | 0.21%   |
| Unknown                 | 55        | 0.2%    |
| Sharp                   | 55        | 0.2%    |
| InnoLux Display         | 55        | 0.2%    |
| ASUSTek Computer        | 55        | 0.2%    |
| PANDA                   | 53        | 0.2%    |
| Quanta Display          | 51        | 0.19%   |
| Packard Bell            | 50        | 0.19%   |
| ___                     | 45        | 0.17%   |
| Panasonic               | 43        | 0.16%   |
| MiTAC                   | 43        | 0.16%   |
| MStar                   | 31        | 0.12%   |
| Belinea                 | 31        | 0.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 345       | 1.26%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 320       | 1.17%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 253       | 0.92%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 217       | 0.79%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch      | 160       | 0.58%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 139       | 0.51%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 131       | 0.48%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch             | 128       | 0.47%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                 | 123       | 0.45%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 380x300mm 19.1-inch      | 116       | 0.42%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch             | 110       | 0.4%    |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch      | 108       | 0.39%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch             | 107       | 0.39%   |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch             | 102       | 0.37%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch      | 100       | 0.37%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch      | 100       | 0.37%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch  | 97        | 0.35%   |
| Lenovo LCD Monitor LEN40B0 1366x768 345x194mm 15.6-inch                   | 93        | 0.34%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch               | 91        | 0.33%   |
| Samsung Electronics SyncMaster SAM036E 1280x1024 376x301mm 19.0-inch      | 81        | 0.3%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch  | 78        | 0.28%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 340x190mm 15.3-inch             | 78        | 0.28%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 78        | 0.28%   |
| Acer AL1716A ACRAD46 1280x1024 338x270mm 17.0-inch                        | 72        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 71        | 0.26%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch               | 70        | 0.26%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                       | 67        | 0.24%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch               | 66        | 0.24%   |
| InfoVision LCD Monitor IVO03F4 1366x768 344x193mm 15.5-inch               | 63        | 0.23%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch           | 62        | 0.23%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 61        | 0.22%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch             | 61        | 0.22%   |
| HannStar HSD121PHW1 HSD04B6 1366x768 270x150mm 12.2-inch                  | 60        | 0.22%   |
| Goldstar W1942 GSM4B6F 1440x900 408x255mm 18.9-inch                       | 60        | 0.22%   |
| AU Optronics LCD Monitor AUO2174 1280x800 331x207mm 15.4-inch             | 59        | 0.22%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                   | 58        | 0.21%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch             | 58        | 0.21%   |
| Samsung Electronics LCD Monitor SEC4252 1366x768 344x194mm 15.5-inch      | 57        | 0.21%   |
| LG Display LCD Monitor LGD02AC 1366x768 344x194mm 15.5-inch               | 57        | 0.21%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch             | 55        | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 7658      | 28.82%  |
| 1366x768 (WXGA)    | 7378      | 27.77%  |
| 1280x1024 (SXGA)   | 3326      | 12.52%  |
| 1600x900 (HD+)     | 1628      | 6.13%   |
| 1280x800 (WXGA)    | 1345      | 5.06%   |
| 1440x900 (WXGA+)   | 1161      | 4.37%   |
| 1680x1050 (WSXGA+) | 1138      | 4.28%   |
| 1024x600           | 610       | 2.3%    |
| 3840x2160 (4K)     | 391       | 1.47%   |
| 1920x1200 (WUXGA)  | 369       | 1.39%   |
| 1024x768 (XGA)     | 304       | 1.14%   |
| 1360x768           | 297       | 1.12%   |
| 2560x1440 (QHD)    | 266       | 1%      |
| 1600x1200          | 151       | 0.57%   |
| 2560x1080          | 106       | 0.4%    |
| 1920x540           | 71        | 0.27%   |
| 1280x720 (HD)      | 62        | 0.23%   |
| 1400x1050          | 52        | 0.2%    |
| 1152x864           | 39        | 0.15%   |
| 3440x1440          | 30        | 0.11%   |
| 2560x1600          | 28        | 0.11%   |
| 2288x1287          | 24        | 0.09%   |
| 1680x945           | 21        | 0.08%   |
| 2048x1536          | 16        | 0.06%   |
| 2048x1152          | 13        | 0.05%   |
| 1920x1440          | 13        | 0.05%   |
| 1280x960           | 12        | 0.05%   |
| 2160x1440          | 11        | 0.04%   |
| 1280x768           | 9         | 0.03%   |
| 1024x576           | 8         | 0.03%   |
| 2880x1800          | 5         | 0.02%   |
| Unknown            | 5         | 0.02%   |
| 4093x4093          | 3         | 0.01%   |
| 3200x1800 (QHD+)   | 3         | 0.01%   |
| 2880x1920          | 3         | 0.01%   |
| 2736x1824          | 3         | 0.01%   |
| 832x624            | 1         | 0.004%  |
| 640x480            | 1         | 0.004%  |
| 3840x2560          | 1         | 0.004%  |
| 3840x1200          | 1         | 0.004%  |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 8301      | 30.78%  |
| 17      | 2874      | 10.66%  |
| 21      | 2369      | 8.78%   |
| 19      | 2363      | 8.76%   |
| 23      | 1971      | 7.31%   |
| 24      | 1215      | 4.51%   |
| 18      | 1029      | 3.82%   |
| 14      | 930       | 3.45%   |
| 20      | 841       | 3.12%   |
| 27      | 748       | 2.77%   |
| 13      | 733       | 2.72%   |
| 22      | 649       | 2.41%   |
| 10      | 638       | 2.37%   |
| 11      | 334       | 1.24%   |
| 12      | 284       | 1.05%   |
| Unknown | 227       | 0.84%   |
| 31      | 195       | 0.72%   |
| 72      | 136       | 0.5%    |
| 16      | 136       | 0.5%    |
| 54      | 121       | 0.45%   |
| 40      | 121       | 0.45%   |
| 32      | 111       | 0.41%   |
| 34      | 102       | 0.38%   |
| 52      | 66        | 0.24%   |
| 26      | 58        | 0.22%   |
| 84      | 56        | 0.21%   |
| 25      | 54        | 0.2%    |
| 46      | 45        | 0.17%   |
| 8       | 34        | 0.13%   |
| 48      | 30        | 0.11%   |
| 42      | 25        | 0.09%   |
| 43      | 20        | 0.07%   |
| 28      | 17        | 0.06%   |
| 65      | 13        | 0.05%   |
| 29      | 13        | 0.05%   |
| 37      | 12        | 0.04%   |
| 33      | 11        | 0.04%   |
| 55      | 10        | 0.04%   |
| 39      | 7         | 0.03%   |
| 50      | 6         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 10892     | 40.77%  |
| 401-500        | 5628      | 21.07%  |
| 501-600        | 3826      | 14.32%  |
| 351-400        | 3167      | 11.85%  |
| 201-300        | 1720      | 6.44%   |
| 1001-1500      | 318       | 1.19%   |
| 601-700        | 273       | 1.02%   |
| 701-800        | 227       | 0.85%   |
| Unknown        | 227       | 0.85%   |
| 1501-2000      | 199       | 0.74%   |
| 801-900        | 131       | 0.49%   |
| 901-1000       | 61        | 0.23%   |
| 101-200        | 36        | 0.13%   |
| More than 2000 | 10        | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 17768     | 68.09%  |
| 16/10   | 3922      | 15.03%  |
| 5/4     | 3130      | 11.99%  |
| 4/3     | 840       | 3.22%   |
| 3/2     | 195       | 0.75%   |
| 21/9    | 123       | 0.47%   |
| 6/5     | 57        | 0.22%   |
| Unknown | 37        | 0.14%   |
| 32/9    | 13        | 0.05%   |
| 1.00    | 5         | 0.02%   |
| 0.56    | 3         | 0.01%   |
| 2.21    | 1         | 0.004%  |
| 2.00    | 1         | 0.004%  |
| 1.96    | 1         | 0.004%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 8035      | 29.95%  |
| 201-250        | 5316      | 19.81%  |
| 151-200        | 3880      | 14.46%  |
| 141-150        | 2392      | 8.92%   |
| 81-90          | 1256      | 4.68%   |
| 121-130        | 1000      | 3.73%   |
| 301-350        | 796       | 2.97%   |
| 41-50          | 641       | 2.39%   |
| More than 1000 | 471       | 1.76%   |
| 351-500        | 424       | 1.58%   |
| 251-300        | 407       | 1.52%   |
| 71-80          | 358       | 1.33%   |
| 131-140        | 346       | 1.29%   |
| 51-60          | 334       | 1.24%   |
| 61-70          | 256       | 0.95%   |
| 111-120        | 256       | 0.95%   |
| 501-1000       | 256       | 0.95%   |
| Unknown        | 227       | 0.85%   |
| 91-100         | 144       | 0.54%   |
| 1-40           | 36        | 0.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 12847     | 48.95%  |
| 101-120       | 9862      | 37.58%  |
| 121-160       | 2496      | 9.51%   |
| 1-50          | 586       | 2.23%   |
| Unknown       | 227       | 0.86%   |
| 161-240       | 196       | 0.75%   |
| More than 240 | 30        | 0.11%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 25336     | 92%     |
| 2     | 1528      | 5.55%   |
| 0     | 629       | 2.28%   |
| 3     | 47        | 0.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 16661     | 40.22%  |
| Qualcomm Atheros                       | 8205      | 19.81%  |
| Intel                                  | 4963      | 11.98%  |
| Broadcom                               | 2972      | 7.17%   |
| Nvidia                                 | 1263      | 3.05%   |
| Marvell Technology Group               | 1079      | 2.6%    |
| Broadcom Limited                       | 862       | 2.08%   |
| Ralink                                 | 846       | 2.04%   |
| Huawei Technologies                    | 662       | 1.6%    |
| Ralink Technology                      | 633       | 1.53%   |
| VIA Technologies                       | 321       | 0.77%   |
| Qualcomm Atheros Communications        | 242       | 0.58%   |
| D-Link System                          | 212       | 0.51%   |
| TP-Link                                | 208       | 0.5%    |
| D-Link                                 | 194       | 0.47%   |
| MediaTek                               | 183       | 0.44%   |
| JMicron Technology                     | 179       | 0.43%   |
| ASUSTek Computer                       | 168       | 0.41%   |
| Attansic Technology                    | 156       | 0.38%   |
| ZTE WCDMA Technologies MSM             | 137       | 0.33%   |
| Silicon Integrated Systems [SiS]       | 133       | 0.32%   |
| Samsung Electronics                    | 88        | 0.21%   |
| Xiaomi                                 | 84        | 0.2%    |
| Sundance Technology Inc / IC Plus      | 67        | 0.16%   |
| HTC (High Tech Computer)               | 57        | 0.14%   |
| Gemtek                                 | 48        | 0.12%   |
| NetGear                                | 47        | 0.11%   |
| 3Com                                   | 46        | 0.11%   |
| Ericsson Business Mobile Networks      | 39        | 0.09%   |
| Qualcomm                               | 34        | 0.08%   |
| ASIX Electronics                       | 30        | 0.07%   |
| Hewlett-Packard                        | 28        | 0.07%   |
| T & A Mobile Phones                    | 25        | 0.06%   |
| LSI                                    | 22        | 0.05%   |
| IMC Networks                           | 22        | 0.05%   |
| Microsoft                              | 21        | 0.05%   |
| ZyXEL Communications                   | 19        | 0.05%   |
| Sony Ericsson Mobile Communications AB | 19        | 0.05%   |
| Vimtron Electronics                    | 17        | 0.04%   |
| Lenovo                                 | 17        | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 11837     | 25.65%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 2960      | 6.42%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2064      | 4.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1243      | 2.69%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 875       | 1.9%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 875       | 1.9%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 763       | 1.65%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 608       | 1.32%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 608       | 1.32%   |
| Nvidia MCP61 Ethernet                                                   | 591       | 1.28%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 517       | 1.12%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 478       | 1.04%   |
| Broadcom BCM43142 802.11b/g/n                                           | 399       | 0.86%   |
| Huawei Modem/Networkcard                                                | 362       | 0.78%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 335       | 0.73%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 326       | 0.71%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 326       | 0.71%   |
| Ralink MT7601U Wireless Adapter                                         | 316       | 0.68%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 301       | 0.65%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 292       | 0.63%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 291       | 0.63%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 288       | 0.62%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                           | 284       | 0.62%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 283       | 0.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 280       | 0.61%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 274       | 0.59%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 266       | 0.58%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 261       | 0.57%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 252       | 0.55%   |
| Intel 82579V Gigabit Network Connection                                 | 237       | 0.51%   |
| Intel WiFi Link 5100                                                    | 229       | 0.5%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 216       | 0.47%   |
| VIA VT6105/VT6106S [Rhine-III]                                          | 198       | 0.43%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 198       | 0.43%   |
| Qualcomm Atheros AR9271 802.11n                                         | 195       | 0.42%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 187       | 0.41%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 178       | 0.39%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 177       | 0.38%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 176       | 0.38%   |
| Intel Wireless 7260                                                     | 173       | 0.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Qualcomm Atheros                  | 5970      | 35%     |
| Intel                             | 3353      | 19.66%  |
| Realtek Semiconductor             | 2565      | 15.04%  |
| Broadcom                          | 2022      | 11.86%  |
| Ralink                            | 846       | 4.96%   |
| Ralink Technology                 | 633       | 3.71%   |
| Broadcom Limited                  | 394       | 2.31%   |
| Qualcomm Atheros Communications   | 242       | 1.42%   |
| TP-Link                           | 200       | 1.17%   |
| D-Link                            | 186       | 1.09%   |
| ASUSTek Computer                  | 150       | 0.88%   |
| D-Link System                     | 115       | 0.67%   |
| MediaTek                          | 109       | 0.64%   |
| NetGear                           | 46        | 0.27%   |
| IMC Networks                      | 22        | 0.13%   |
| Microsoft                         | 20        | 0.12%   |
| ZyXEL Communications              | 15        | 0.09%   |
| Mercucys                          | 15        | 0.09%   |
| Edimax Technology                 | 14        | 0.08%   |
| Belkin Components                 | 12        | 0.07%   |
| Sierra Wireless                   | 9         | 0.05%   |
| Linksys                           | 9         | 0.05%   |
| Marvell Technology Group          | 8         | 0.05%   |
| Dell                              | 8         | 0.05%   |
| ZyDAS                             | 7         | 0.04%   |
| Micro Star International          | 6         | 0.04%   |
| Hewlett-Packard                   | 6         | 0.04%   |
| Gemtek                            | 6         | 0.04%   |
| Tenda                             | 5         | 0.03%   |
| Sitecom Europe                    | 5         | 0.03%   |
| Sagem                             | 5         | 0.03%   |
| Qualcomm                          | 5         | 0.03%   |
| Xiaomi                            | 4         | 0.02%   |
| TRENDnet                          | 4         | 0.02%   |
| Fujitsu Siemens Computers         | 4         | 0.02%   |
| Ericsson Business Mobile Networks | 4         | 0.02%   |
| Accton Technology                 | 4         | 0.02%   |
| VIA Technologies                  | 3         | 0.02%   |
| Texas Instruments                 | 3         | 0.02%   |
| BUFFALO                           | 3         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2064      | 12.01%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1243      | 7.23%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 875       | 5.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 763       | 4.44%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 608       | 3.54%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 517       | 3.01%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 478       | 2.78%   |
| Broadcom BCM43142 802.11b/g/n                                           | 399       | 2.32%   |
| Ralink MT7601U Wireless Adapter                                         | 316       | 1.84%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 288       | 1.68%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 283       | 1.65%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 274       | 1.59%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 261       | 1.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 252       | 1.47%   |
| Intel WiFi Link 5100                                                    | 229       | 1.33%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 216       | 1.26%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 198       | 1.15%   |
| Qualcomm Atheros AR9271 802.11n                                         | 195       | 1.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 187       | 1.09%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 177       | 1.03%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 176       | 1.02%   |
| Intel Wireless 7260                                                     | 173       | 1.01%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 167       | 0.97%   |
| Intel Centrino Wireless-N 130                                           | 164       | 0.95%   |
| Intel Wireless 7265                                                     | 160       | 0.93%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 146       | 0.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 145       | 0.84%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 142       | 0.83%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 139       | 0.81%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 138       | 0.8%    |
| Ralink RT5370 Wireless Adapter                                          | 137       | 0.8%    |
| Intel Wireless 3165                                                     | 135       | 0.79%   |
| Intel Centrino Wireless-N 2230                                          | 132       | 0.77%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 120       | 0.7%    |
| Intel WiMAX/WiFi Link 5150                                              | 104       | 0.61%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                        | 102       | 0.59%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 99        | 0.58%   |
| Intel Centrino Wireless-N 100                                           | 98        | 0.57%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter             | 93        | 0.54%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 92        | 0.54%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 15906     | 57.31%  |
| Qualcomm Atheros                       | 3395      | 12.23%  |
| Intel                                  | 2433      | 8.77%   |
| Nvidia                                 | 1262      | 4.55%   |
| Broadcom                               | 1247      | 4.49%   |
| Marvell Technology Group               | 1072      | 3.86%   |
| Broadcom Limited                       | 486       | 1.75%   |
| VIA Technologies                       | 310       | 1.12%   |
| JMicron Technology                     | 179       | 0.64%   |
| Huawei Technologies                    | 160       | 0.58%   |
| Attansic Technology                    | 156       | 0.56%   |
| Silicon Integrated Systems [SiS]       | 130       | 0.47%   |
| ZTE WCDMA Technologies MSM             | 126       | 0.45%   |
| D-Link System                          | 98        | 0.35%   |
| Samsung Electronics                    | 84        | 0.3%    |
| Xiaomi                                 | 80        | 0.29%   |
| MediaTek                               | 71        | 0.26%   |
| Sundance Technology Inc / IC Plus      | 67        | 0.24%   |
| HTC (High Tech Computer)               | 57        | 0.21%   |
| 3Com                                   | 46        | 0.17%   |
| Gemtek                                 | 42        | 0.15%   |
| ASIX Electronics                       | 30        | 0.11%   |
| Qualcomm                               | 29        | 0.1%    |
| T & A Mobile Phones                    | 22        | 0.08%   |
| ASUSTek Computer                       | 19        | 0.07%   |
| Vimtron Electronics                    | 17        | 0.06%   |
| Sony Ericsson Mobile Communications AB | 17        | 0.06%   |
| Spreadtrum Communications              | 16        | 0.06%   |
| GCT Semiconductor                      | 16        | 0.06%   |
| Lenovo                                 | 15        | 0.05%   |
| NTmore                                 | 14        | 0.05%   |
| ICS Advent                             | 9         | 0.03%   |
| ULi Electronics                        | 8         | 0.03%   |
| TP-Link                                | 8         | 0.03%   |
| OPPO Electronics                       | 8         | 0.03%   |
| Davicom Semiconductor                  | 8         | 0.03%   |
| D-Link                                 | 8         | 0.03%   |
| Motorola PCS                           | 7         | 0.03%   |
| ADMtek                                 | 7         | 0.03%   |
| LG Electronics                         | 6         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 11837     | 42.1%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2960      | 10.53%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 875       | 3.11%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 608       | 2.16%   |
| Nvidia MCP61 Ethernet                                                  | 591       | 2.1%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 335       | 1.19%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 326       | 1.16%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 326       | 1.16%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 301       | 1.07%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 292       | 1.04%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 291       | 1.04%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 284       | 1.01%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 280       | 1%      |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 266       | 0.95%   |
| Intel 82579V Gigabit Network Connection                                | 237       | 0.84%   |
| VIA VT6105/VT6106S [Rhine-III]                                         | 198       | 0.7%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 178       | 0.63%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 167       | 0.59%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 164       | 0.58%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 162       | 0.58%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 160       | 0.57%   |
| Intel Ethernet Connection (2) I219-V                                   | 159       | 0.57%   |
| Attansic AR8152 v2.0 Fast Ethernet                                     | 156       | 0.55%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 154       | 0.55%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 146       | 0.52%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                 | 138       | 0.49%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                             | 136       | 0.48%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 127       | 0.45%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 124       | 0.44%   |
| Intel WiMAX Connection 2400m                                           | 124       | 0.44%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                             | 119       | 0.42%   |
| Nvidia MCP77 Ethernet                                                  | 119       | 0.42%   |
| Broadcom BCM4401-B0 100Base-TX                                         | 118       | 0.42%   |
| Intel I211 Gigabit Network Connection                                  | 116       | 0.41%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                      | 115       | 0.41%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                | 113       | 0.4%    |
| Nvidia CK804 Ethernet Controller                                       | 112       | 0.4%    |
| VIA VT6102/VT6103 [Rhine-II]                                           | 109       | 0.39%   |
| ZTE WCDMA MSM USB SCSI CD-ROM                                          | 107       | 0.38%   |
| Nvidia MCP51 Ethernet Controller                                       | 106       | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 26093     | 60.15%  |
| WiFi     | 16467     | 37.96%  |
| Modem    | 784       | 1.81%   |
| Unknown  | 33        | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 14523     | 52.59%  |
| WiFi     | 13079     | 47.36%  |
| Unknown  | 9         | 0.03%   |
| Modem    | 4         | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 14589     | 53.62%  |
| 1     | 12060     | 44.32%  |
| 0     | 354       | 1.3%    |
| 3     | 177       | 0.65%   |
| 4     | 22        | 0.08%   |
| 6     | 4         | 0.01%   |
| 33    | 1         | 0.004%  |
| 16    | 1         | 0.004%  |
| 11    | 1         | 0.004%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 20044     | 70.61%  |
| Unknown | 8003      | 28.19%  |
| Yes     | 341       | 1.2%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1586      | 16.12%  |
| Qualcomm Atheros Communications | 1444      | 14.68%  |
| Broadcom                        | 1065      | 10.83%  |
| Realtek Semiconductor           | 936       | 9.51%   |
| Cambridge Silicon Radio         | 807       | 8.2%    |
| IMC Networks                    | 657       | 6.68%   |
| Lite-On Technology              | 625       | 6.35%   |
| Foxconn / Hon Hai               | 613       | 6.23%   |
| ASUSTek Computer                | 432       | 4.39%   |
| Ralink                          | 274       | 2.79%   |
| Toshiba                         | 240       | 2.44%   |
| Hewlett-Packard                 | 239       | 2.43%   |
| Dell                            | 200       | 2.03%   |
| Foxconn International           | 187       | 1.9%    |
| Apple                           | 131       | 1.33%   |
| Alps Electric                   | 78        | 0.79%   |
| Ralink Technology               | 61        | 0.62%   |
| Integrated System Solution      | 57        | 0.58%   |
| MediaTek                        | 41        | 0.42%   |
| Chicony Electronics             | 21        | 0.21%   |
| Micro Star International        | 18        | 0.18%   |
| TP-Link                         | 17        | 0.17%   |
| Taiyo Yuden                     | 17        | 0.17%   |
| Realtek                         | 17        | 0.17%   |
| Askey Computer                  | 12        | 0.12%   |
| USI                             | 10        | 0.1%    |
| Qcom                            | 9         | 0.09%   |
| Roper                           | 8         | 0.08%   |
| Conwise Technology              | 7         | 0.07%   |
| Syntek                          | 4         | 0.04%   |
| Logitech                        | 4         | 0.04%   |
| Samsung Electronics             | 3         | 0.03%   |
| Opticis                         | 3         | 0.03%   |
| Belkin Components               | 3         | 0.03%   |
| Fujitsu                         | 2         | 0.02%   |
| Actions                         | 2         | 0.02%   |
| Smart Modular Technologies      | 1         | 0.01%   |
| Qualcomm Atheros                | 1         | 0.01%   |
| Primax Electronics              | 1         | 0.01%   |
| Marvell Semiconductor           | 1         | 0.01%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 807       | 8.2%    |
| Intel Bluetooth wireless interface                  | 662       | 6.72%   |
| Realtek Bluetooth Radio                             | 569       | 5.78%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 557       | 5.66%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 358       | 3.64%   |
| Ralink RT3290 Bluetooth                             | 274       | 2.78%   |
| Qualcomm Atheros  Bluetooth Device                  | 243       | 2.47%   |
| Intel Bluetooth Device                              | 227       | 2.31%   |
| Foxconn / Hon Hai Bluetooth Device                  | 211       | 2.14%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 207       | 2.1%    |
| Lite-On Atheros AR3012 Bluetooth                    | 205       | 2.08%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 186       | 1.89%   |
| Foxconn International BCM43142A0 Bluetooth module   | 185       | 1.88%   |
| Broadcom BCM2070 Bluetooth Device                   | 163       | 1.66%   |
| Lite-On Bluetooth Device                            | 154       | 1.56%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 154       | 1.56%   |
| Broadcom BCM2045 Bluetooth                          | 153       | 1.55%   |
| Realtek  Bluetooth 4.2 Adapter                      | 143       | 1.45%   |
| IMC Networks Bluetooth Device                       | 142       | 1.44%   |
| Realtek RTL8723B Bluetooth                          | 139       | 1.41%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 129       | 1.31%   |
| Intel AX201 Bluetooth                               | 129       | 1.31%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 119       | 1.21%   |
| HP Broadcom 2070 Bluetooth Combo                    | 109       | 1.11%   |
| Qualcomm Atheros Bluetooth                          | 106       | 1.08%   |
| IMC Networks Bluetooth Radio                        | 106       | 1.08%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter               | 102       | 1.04%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 99        | 1.01%   |
| Toshiba Integrated Bluetooth HCI                    | 96        | 0.98%   |
| Intel Wireless-AC 3168 Bluetooth                    | 96        | 0.98%   |
| Broadcom BCM2045B (BDC-2.1)                         | 95        | 0.96%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 86        | 0.87%   |
| Broadcom HP Portable Valentine                      | 84        | 0.85%   |
| ASUS BT-270 Bluetooth Adapter                       | 80        | 0.81%   |
| Intel AX200 Bluetooth                               | 79        | 0.8%    |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 77        | 0.78%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 76        | 0.77%   |
| ASUS BT-253 Bluetooth Adapter                       | 76        | 0.77%   |
| IMC Networks Bluetooth Module                       | 71        | 0.72%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 70        | 0.71%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 18794     | 51.48%  |
| AMD                                             | 8136      | 22.29%  |
| Nvidia                                          | 7210      | 19.75%  |
| C-Media Electronics                             | 633       | 1.73%   |
| Creative Labs                                   | 476       | 1.3%    |
| VIA Technologies                                | 216       | 0.59%   |
| Silicon Integrated Systems [SiS]                | 186       | 0.51%   |
| Creative Technology                             | 88        | 0.24%   |
| Logitech                                        | 74        | 0.2%    |
| Generalplus Technology                          | 52        | 0.14%   |
| JMTek                                           | 51        | 0.14%   |
| Texas Instruments                               | 47        | 0.13%   |
| Plantronics                                     | 28        | 0.08%   |
| Ensoniq                                         | 25        | 0.07%   |
| ASUSTek Computer                                | 24        | 0.07%   |
| Pixart Imaging                                  | 20        | 0.05%   |
| Tenx Technology                                 | 18        | 0.05%   |
| ULi Electronics                                 | 16        | 0.04%   |
| Razer USA                                       | 16        | 0.04%   |
| Yamaha                                          | 12        | 0.03%   |
| A4Tech                                          | 12        | 0.03%   |
| M-Audio                                         | 11        | 0.03%   |
| Kingston Technology                             | 11        | 0.03%   |
| Shenzhen Rapoo Technology                       | 10        | 0.03%   |
| Aureal Semiconductor                            | 10        | 0.03%   |
| iCreate Technologies                            | 9         | 0.02%   |
| ESS Technology                                  | 9         | 0.02%   |
| Asahi Kasei Microsystems                        | 9         | 0.02%   |
| Zoran Co. Personal Media Division (Nogatech)    | 8         | 0.02%   |
| Yealink Network Technology                      | 8         | 0.02%   |
| XMOS                                            | 8         | 0.02%   |
| Micro Star International                        | 8         | 0.02%   |
| Licensed by Sony Computer Entertainment America | 8         | 0.02%   |
| Guillemot                                       | 8         | 0.02%   |
| ATI Technologies                                | 8         | 0.02%   |
| Samson Technologies                             | 7         | 0.02%   |
| GYROCOM C&C                                     | 7         | 0.02%   |
| GN Netcom                                       | 7         | 0.02%   |
| Focusrite-Novation                              | 7         | 0.02%   |
| Sony                                            | 6         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3233      | 7.67%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2959      | 7.02%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2766      | 6.56%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2753      | 6.53%   |
| AMD FCH Azalia Controller                                                                         | 1638      | 3.89%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1489      | 3.53%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1365      | 3.24%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1177      | 2.79%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 963       | 2.29%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 909       | 2.16%   |
| Nvidia High Definition Audio Controller                                                           | 804       | 1.91%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 717       | 1.7%    |
| Nvidia MCP61 High Definition Audio                                                                | 646       | 1.53%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 613       | 1.45%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 576       | 1.37%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 482       | 1.14%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 475       | 1.13%   |
| AMD Kabini HDMI/DP Audio                                                                          | 469       | 1.11%   |
| Intel 8 Series HD Audio Controller                                                                | 465       | 1.1%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 463       | 1.1%    |
| Nvidia GK107 HDMI Audio Controller                                                                | 462       | 1.1%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 452       | 1.07%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 448       | 1.06%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 440       | 1.04%   |
| AMD Trinity HDMI Audio Controller                                                                 | 414       | 0.98%   |
| AMD Wrestler HDMI Audio                                                                           | 409       | 0.97%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 399       | 0.95%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 371       | 0.88%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 361       | 0.86%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 355       | 0.84%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 322       | 0.76%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 316       | 0.75%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 310       | 0.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 304       | 0.72%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 287       | 0.68%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 259       | 0.61%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 256       | 0.61%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 253       | 0.6%    |
| Intel 200 Series PCH HD Audio                                                                     | 248       | 0.59%   |
| Intel Broadwell-U Audio Controller                                                                | 234       | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Unknown               | 9529      | 31.61%  |
| Samsung Electronics   | 4241      | 14.07%  |
| Kingston              | 4099      | 13.6%   |
| SK hynix              | 3463      | 11.49%  |
| Micron Technology     | 1254      | 4.16%   |
| Crucial               | 1010      | 3.35%   |
| Elpida                | 835       | 2.77%   |
| Nanya Technology      | 762       | 2.53%   |
| Corsair               | 679       | 2.25%   |
| A-DATA Technology     | 560       | 1.86%   |
| Ramaxel Technology    | 547       | 1.81%   |
| AMD                   | 347       | 1.15%   |
| Patriot               | 315       | 1.04%   |
| ASint Technology      | 184       | 0.61%   |
| GOODRAM               | 168       | 0.56%   |
| Goldkey               | 165       | 0.55%   |
| Transcend             | 143       | 0.47%   |
| 48spaces              | 129       | 0.43%   |
| G.Skill               | 120       | 0.4%    |
| Silicon Power         | 112       | 0.37%   |
| Kingmax               | 101       | 0.34%   |
| Apacer                | 98        | 0.33%   |
| Qimonda               | 83        | 0.28%   |
| Unknown               | 81        | 0.27%   |
| SHARETRONIC           | 80        | 0.27%   |
| Qumo                  | 78        | 0.26%   |
| Unifosa               | 74        | 0.25%   |
| Unknown (ABCD)        | 73        | 0.24%   |
| Team                  | 72        | 0.24%   |
| GeIL                  | 66        | 0.22%   |
| Foxline               | 60        | 0.2%    |
| Kllisre               | 54        | 0.18%   |
| Toshiba               | 31        | 0.1%    |
| KETECH                | 31        | 0.1%    |
| Atermiter             | 26        | 0.09%   |
| ACPI Digital          | 23        | 0.08%   |
| Smart                 | 21        | 0.07%   |
| Ramos Technology      | 20        | 0.07%   |
| TakeMS                | 18        | 0.06%   |
| Kingmax Semiconductor | 18        | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                               | 487       | 1.42%   |
| Unknown RAM Module 2048MB DIMM SDRAM                                      | 476       | 1.39%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                                    | 444       | 1.3%    |
| Unknown RAM Module 1024MB DIMM SDRAM                                      | 416       | 1.22%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                                   | 372       | 1.09%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                                   | 352       | 1.03%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 328       | 0.96%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s                               | 325       | 0.95%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                                    | 250       | 0.73%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s                               | 249       | 0.73%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 244       | 0.71%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s                  | 229       | 0.67%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                             | 224       | 0.65%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s                     | 213       | 0.62%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 213       | 0.62%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                               | 207       | 0.6%    |
| Unknown RAM Module 2048MB SODIMM DDR2                                     | 203       | 0.59%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 199       | 0.58%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s                     | 195       | 0.57%   |
| Unknown RAM Module 1024MB SODIMM DDR2                                     | 179       | 0.52%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s                  | 176       | 0.51%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 171       | 0.5%    |
| Unknown RAM Module 1024MB DIMM 667MT/s                                    | 164       | 0.48%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                                    | 162       | 0.47%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                              | 160       | 0.47%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                             | 158       | 0.46%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                                    | 146       | 0.43%   |
| Unknown RAM Module 512MB DIMM SDRAM                                       | 145       | 0.42%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s                    | 141       | 0.41%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s                     | 141       | 0.41%   |
| Unknown RAM Module 1024MB DIMM                                            | 138       | 0.4%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 138       | 0.4%    |
| Unknown RAM Module 4096MB DIMM 1600MT/s                                   | 132       | 0.39%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 132       | 0.39%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s                       | 132       | 0.39%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s                     | 130       | 0.38%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                              | 123       | 0.36%   |
| 48spaces RAM 012345678901234567890123456789012345 2GB SODIMM DDR2 667MT/s | 121       | 0.35%   |
| Unknown RAM Module 4096MB SODIMM DDR3                                     | 120       | 0.35%   |
| Nanya RAM NT2GC64B88B0NS-CG 2048MB SODIMM DDR3 1334MT/s                   | 113       | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 12745     | 48.03%  |
| DDR2    | 4069      | 15.33%  |
| Unknown | 3169      | 11.94%  |
| DDR4    | 2874      | 10.83%  |
| SDRAM   | 2475      | 9.33%   |
| DDR     | 753       | 2.84%   |
| DRAM    | 207       | 0.78%   |
| LPDDR4  | 174       | 0.66%   |
| LPDDR3  | 35        | 0.13%   |
| DDR5    | 24        | 0.09%   |
| LPDDR5  | 6         | 0.02%   |
| EEPROM  | 3         | 0.01%   |
| SRAM    | 1         | 0.004%  |
| RAM     | 1         | 0.004%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 13164     | 50.91%  |
| SODIMM       | 12528     | 48.45%  |
| Row Of Chips | 123       | 0.48%   |
| Chip         | 25        | 0.1%    |
| FB-DIMM      | 11        | 0.04%   |
| Unknown      | 8         | 0.03%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 4096    | 10131     | 32.83%  |
| 2048    | 9997      | 32.4%   |
| 1024    | 4612      | 14.95%  |
| 8192    | 4233      | 13.72%  |
| 512     | 974       | 3.16%   |
| 16384   | 537       | 1.74%   |
| 256     | 199       | 0.64%   |
| 32768   | 143       | 0.46%   |
| Unknown | 10        | 0.03%   |
| 128     | 6         | 0.02%   |
| 32      | 4         | 0.01%   |
| 1536    | 3         | 0.01%   |
| 16      | 3         | 0.01%   |
| 1       | 3         | 0.01%   |
| 65536   | 1         | 0.003%  |
| 32767   | 1         | 0.003%  |
| 12288   | 1         | 0.003%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 7168      | 24.64%  |
| 1333    | 3902      | 13.41%  |
| Unknown | 2629      | 9.04%   |
| 800     | 2388      | 8.21%   |
| 667     | 2298      | 7.9%    |
| 1334    | 2167      | 7.45%   |
| 2667    | 848       | 2.91%   |
| 2400    | 840       | 2.89%   |
| 3200    | 756       | 2.6%    |
| 1067    | 541       | 1.86%   |
| 2133    | 539       | 1.85%   |
| 400     | 525       | 1.8%    |
| 533     | 515       | 1.77%   |
| 4199    | 479       | 1.65%   |
| 1066    | 432       | 1.48%   |
| 1867    | 369       | 1.27%   |
| 333     | 316       | 1.09%   |
| 2048    | 264       | 0.91%   |
| 1866    | 207       | 0.71%   |
| 1800    | 169       | 0.58%   |
| 3600    | 153       | 0.53%   |
| 975     | 133       | 0.46%   |
| 3400    | 109       | 0.37%   |
| 266     | 109       | 0.37%   |
| 3266    | 100       | 0.34%   |
| 2933    | 90        | 0.31%   |
| 1639    | 78        | 0.27%   |
| 2666    | 70        | 0.24%   |
| 3000    | 49        | 0.17%   |
| 66      | 49        | 0.17%   |
| 3466    | 46        | 0.16%   |
| 3733    | 44        | 0.15%   |
| 2000    | 44        | 0.15%   |
| 1648    | 40        | 0.14%   |
| 1400    | 38        | 0.13%   |
| 2800    | 33        | 0.11%   |
| 2134    | 32        | 0.11%   |
| 200     | 32        | 0.11%   |
| 3333    | 30        | 0.1%    |
| 49926   | 26        | 0.09%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Hewlett-Packard                 | 534       | 30.72%  |
| Canon                           | 399       | 22.96%  |
| Samsung Electronics             | 287       | 16.51%  |
| Seiko Epson                     | 171       | 9.84%   |
| Brother Industries              | 114       | 6.56%   |
| Xerox                           | 53        | 3.05%   |
| Panasonic (Matsushita)          | 39        | 2.24%   |
| Pantum                          | 30        | 1.73%   |
| Kyocera                         | 28        | 1.61%   |
| Ricoh                           | 21        | 1.21%   |
| Prolific Technology             | 13        | 0.75%   |
| Lexmark International           | 9         | 0.52%   |
| QinHeng Electronics             | 8         | 0.46%   |
| TSC Auto ID Technology          | 4         | 0.23%   |
| Xiaomi                          | 3         | 0.17%   |
| WinChipHead                     | 3         | 0.17%   |
| STMicroelectronics              | 2         | 0.12%   |
| Sharp                           | 2         | 0.12%   |
| Custom Engineering SPA          | 2         | 0.12%   |
| cab Produkttechnik GmbH & Co KG | 2         | 0.12%   |
| Yurex                           | 1         | 0.06%   |
| Toshiba TEC                     | 1         | 0.06%   |
| Samsung Info. Systems America   | 1         | 0.06%   |
| Oki Data                        | 1         | 0.06%   |
| NXP Semiconductors              | 1         | 0.06%   |
| NCR                             | 1         | 0.06%   |
| Konica Minolta                  | 1         | 0.06%   |
| KODAK                           | 1         | 0.06%   |
| iDPRT                           | 1         | 0.06%   |
| HIPER                           | 1         | 0.06%   |
| Fuji Xerox                      | 1         | 0.06%   |
| Dell                            | 1         | 0.06%   |
| ATEN International              | 1         | 0.06%   |
| Apple                           | 1         | 0.06%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| HP LaserJet 1020                                             | 58        | 3.27%   |
| HP LaserJet 1018                                             | 49        | 2.77%   |
| HP LaserJet P1102                                            | 48        | 2.71%   |
| Samsung SCX-4200 series                                      | 43        | 2.43%   |
| Canon LBP2900                                                | 38        | 2.14%   |
| Seiko Epson Printer                                          | 34        | 1.92%   |
| Samsung SCX-3400 Series                                      | 25        | 1.41%   |
| Panasonic (Matsushita) KX-MB1500RU                           | 25        | 1.41%   |
| HP LaserJet 1010                                             | 25        | 1.41%   |
| Seiko Epson USB2.0 Printer                                   | 24        | 1.35%   |
| Samsung SCX-3200 Series                                      | 24        | 1.35%   |
| HP LaserJet P1005                                            | 24        | 1.35%   |
| Canon MF4410                                                 | 24        | 1.35%   |
| Canon MF3010                                                 | 23        | 1.3%    |
| Seiko Epson L210 Series                                      | 19        | 1.07%   |
| Samsung ML-1640 Series Laser Printer                         | 17        | 0.96%   |
| Canon MF4010 series                                          | 17        | 0.96%   |
| Canon LBP3010/LBP3018/LBP3050                                | 17        | 0.96%   |
| Samsung ML-1210 Printer                                      | 15        | 0.85%   |
| Canon PIXMA MG2500 Series                                    | 15        | 0.85%   |
| Canon LBP810                                                 | 15        | 0.85%   |
| Canon LBP6000                                                | 15        | 0.85%   |
| HP Deskjet 2050 J510                                         | 14        | 0.79%   |
| Canon LaserShot LBP-1120 Printer                             | 14        | 0.79%   |
| Samsung ML-2010P Mono Laser Printer                          | 13        | 0.73%   |
| Samsung M2070 Series                                         | 13        | 0.73%   |
| Prolific PL2305 Parallel Port                                | 13        | 0.73%   |
| Canon LBP6020                                                | 13        | 0.73%   |
| Canon iP7200 series                                          | 13        | 0.73%   |
| Brother HL-2030 Laser Printer                                | 13        | 0.73%   |
| Xerox Phaser 3140 and 3155                                   | 12        | 0.68%   |
| Samsung M2020 Series                                         | 12        | 0.68%   |
| HP LaserJet 1320                                             | 12        | 0.68%   |
| HP LaserJet 1200                                             | 12        | 0.68%   |
| HP DeskJet 2130 series                                       | 12        | 0.68%   |
| Canon MG2400 series                                          | 12        | 0.68%   |
| Brother HL-1110 series                                       | 12        | 0.68%   |
| Brother DCP-7057 scanner/printer                             | 12        | 0.68%   |
| Panasonic (Matsushita) KX-MB2030 Multifunction Laser Printer | 11        | 0.62%   |
| HP LaserJet 1022                                             | 11        | 0.62%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Canon                       | 175       | 36.01%  |
| Seiko Epson                 | 116       | 23.87%  |
| Hewlett-Packard             | 84        | 17.28%  |
| Mustek Systems              | 52        | 10.7%   |
| Acer Peripherals (now BenQ) | 19        | 3.91%   |
| Ultima Electronics          | 18        | 3.7%    |
| KYE Systems (Mouse Systems) | 7         | 1.44%   |
| Fujitsu                     | 4         | 0.82%   |
| Plustek                     | 2         | 0.41%   |
| Microtek International      | 2         | 0.41%   |
| Avision                     | 2         | 0.41%   |
| AGFA-Gevaert NV             | 2         | 0.41%   |
| Visioneer                   | 1         | 0.21%   |
| Papillon Systems            | 1         | 0.21%   |
| Canon Electronics           | 1         | 0.21%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LIDE 25                                                                | 32        | 6.57%   |
| HP ScanJet 2400c                                                                      | 27        | 5.54%   |
| Canon CanoScan LiDE 110                                                               | 27        | 5.54%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 21        | 4.31%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 18        | 3.7%    |
| Mustek Systems BearPaw 1200 CU Plus                                                   | 18        | 3.7%    |
| Canon CanoScan LiDE 120                                                               | 18        | 3.7%    |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 16        | 3.29%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 15        | 3.08%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 14        | 2.87%   |
| Canon CanoScan LiDE 210                                                               | 12        | 2.46%   |
| Canon CanoScan LiDE 60                                                                | 11        | 2.26%   |
| Seiko Epson GT-7400U [Perfection 1270]                                                | 10        | 2.05%   |
| Canon CanoScan LiDE 100                                                               | 10        | 2.05%   |
| Canon CanoScan LiDE 220                                                               | 9         | 1.85%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                                    | 8         | 1.64%   |
| Mustek Systems SNAPSCAN e22                                                           | 8         | 1.64%   |
| Mustek Systems BearPaw 2400 CU Plus                                                   | 8         | 1.64%   |
| Seiko Epson GT-F670 [Perfection V200 Photo]                                           | 7         | 1.44%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                   | 7         | 1.44%   |
| Seiko Epson Perfection 660                                                            | 6         | 1.23%   |
| Canon CanoScan                                                                        | 6         | 1.23%   |
| Mustek Systems BearPaw 2448 TA Plus                                                   | 5         | 1.03%   |
| Acer Peripherals (now BenQ) Benq 5560                                                 | 5         | 1.03%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]                                     | 4         | 0.82%   |
| Mustek Systems BearPaw 2448 CU Pro                                                    | 4         | 0.82%   |
| HP ScanJet 3800c                                                                      | 4         | 0.82%   |
| HP Scanjet 200                                                                        | 4         | 0.82%   |
| Canon CanoScan LiDE 70                                                                | 4         | 0.82%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                                | 4         | 0.82%   |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]                                           | 3         | 0.62%   |
| Mustek Systems BearPaw 2400 TA Plus                                                   | 3         | 0.62%   |
| HP ScanJet G3010                                                                      | 3         | 0.62%   |
| HP ScanJet 3970c                                                                      | 3         | 0.62%   |
| HP ScanJet 3770                                                                       | 3         | 0.62%   |
| HP ScanJet 3500c                                                                      | 3         | 0.62%   |
| HP Scanjet 300                                                                        | 3         | 0.62%   |
| HP ScanJet 2200c                                                                      | 3         | 0.62%   |
| HP PSC 1200                                                                           | 3         | 0.62%   |
| Fujitsu ScanSnap SV600                                                                | 3         | 0.62%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 3117      | 21.43%  |
| Logitech                               | 1121      | 7.71%   |
| Suyin                                  | 972       | 6.68%   |
| IMC Networks                           | 932       | 6.41%   |
| Z-Star Microelectronics                | 866       | 5.95%   |
| Microdia                               | 850       | 5.84%   |
| Realtek Semiconductor                  | 789       | 5.42%   |
| Bison Electronics                      | 673       | 4.63%   |
| Sunplus Innovation Technology          | 615       | 4.23%   |
| Silicon Motion                         | 613       | 4.21%   |
| Acer                                   | 418       | 2.87%   |
| Alcor Micro                            | 388       | 2.67%   |
| Cheng Uei Precision Industry (Foxlink) | 352       | 2.42%   |
| Syntek                                 | 339       | 2.33%   |
| Quanta                                 | 207       | 1.42%   |
| Microsoft                              | 172       | 1.18%   |
| ALi                                    | 170       | 1.17%   |
| Ricoh                                  | 163       | 1.12%   |
| Apple                                  | 152       | 1.05%   |
| KYE Systems (Mouse Systems)            | 130       | 0.89%   |
| DigiTech                               | 128       | 0.88%   |
| Cubeternet                             | 108       | 0.74%   |
| Pixart Imaging                         | 107       | 0.74%   |
| Arkmicro Technologies                  | 106       | 0.73%   |
| Aveo Technology                        | 98        | 0.67%   |
| GEMBIRD                                | 95        | 0.65%   |
| Samsung Electronics                    | 87        | 0.6%    |
| Lite-On Technology                     | 72        | 0.5%    |
| Lenovo                                 | 69        | 0.47%   |
| Importek                               | 54        | 0.37%   |
| Primax Electronics                     | 53        | 0.36%   |
| Creative Technology                    | 44        | 0.3%    |
| Genesys Logic                          | 32        | 0.22%   |
| Luxvisions Innotech Limited            | 28        | 0.19%   |
| OmniVision Technologies                | 26        | 0.18%   |
| Sunplus Technology                     | 24        | 0.17%   |
| Guillemot                              | 22        | 0.15%   |
| Nokia Mobile Phones                    | 21        | 0.14%   |
| Sonix Technology                       | 20        | 0.14%   |
| Image Processor                        | 18        | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Logitech Webcam C270                     | 373       | 2.56%   |
| Chicony HD WebCam                        | 315       | 2.16%   |
| Z-Star Venus USB2.0 Camera               | 291       | 2%      |
| Chicony Lenovo EasyCamera                | 281       | 1.93%   |
| Bison Lenovo Integrated Webcam           | 213       | 1.46%   |
| IMC Networks UVC VGA Webcam              | 212       | 1.46%   |
| Chicony USB 2.0 Camera                   | 207       | 1.42%   |
| Sunplus HD WebCam                        | 205       | 1.41%   |
| Realtek USB Camera                       | 169       | 1.16%   |
| Z-Star A4 TECH USB2.0 PC Camera J        | 168       | 1.15%   |
| Chicony USB2.0 HD UVC WebCam             | 165       | 1.13%   |
| Bison Lenovo EasyCamera                  | 165       | 1.13%   |
| Microdia Camera                          | 156       | 1.07%   |
| Chicony Integrated Camera                | 136       | 0.93%   |
| Acer BisonCam, NB Pro                    | 126       | 0.86%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 123       | 0.84%   |
| Microdia Sonix USB 2.0 Camera            | 122       | 0.84%   |
| Chicony 2.0M UVC Webcam / CNF7129        | 122       | 0.84%   |
| Realtek Lenovo EasyCamera                | 120       | 0.82%   |
| Z-Star A4 TECH USB2.0 PC Camera E        | 119       | 0.82%   |
| Silicon Motion WebCam SC-0311139N        | 116       | 0.8%    |
| Syntek Lenovo EasyCamera                 | 114       | 0.78%   |
| ALi Gateway Webcam                       | 113       | 0.78%   |
| Alcor Micro Asus Integrated Webcam       | 113       | 0.78%   |
| IMC Networks Integrated Webcam           | 110       | 0.76%   |
| DigiTech USB 2.0 PC Camera               | 107       | 0.73%   |
| Chicony USB2.0 VGA UVC WebCam            | 102       | 0.7%    |
| Suyin 1.3M HD WebCam                     | 101       | 0.69%   |
| Sunplus Asus Webcam                      | 99        | 0.68%   |
| Chicony HP Truevision HD                 | 98        | 0.67%   |
| Arkmicro USB2.0 PC CAMERA                | 96        | 0.66%   |
| Chicony HP Webcam                        | 93        | 0.64%   |
| Logitech Webcam C170                     | 92        | 0.63%   |
| Chicony VGA WebCam                       | 91        | 0.62%   |
| Logitech Webcam C310                     | 88        | 0.6%    |
| IMC Networks USB2.0 VGA UVC WebCam       | 88        | 0.6%    |
| Chicony USB2.0 0.3M UVC WebCam           | 87        | 0.6%    |
| Logitech Webcam C210                     | 84        | 0.58%   |
| Samsung Galaxy series, misc. (MTP mode)  | 82        | 0.56%   |
| IMC Networks USB2.0 UVC HD Webcam        | 82        | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 447       | 41.85%  |
| AuthenTec                          | 234       | 21.91%  |
| Upek                               | 159       | 14.89%  |
| STMicroelectronics                 | 78        | 7.3%    |
| LighTuning Technology              | 67        | 6.27%   |
| Shenzhen Goodix Technology         | 32        | 3%      |
| Elan Microelectronics              | 22        | 2.06%   |
| Synaptics                          | 19        | 1.78%   |
| Focal-systems.Corp                 | 5         | 0.47%   |
| Microsoft                          | 2         | 0.19%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.09%   |
| FocalTech                          | 1         | 0.09%   |
| DigitalPersona                     | 1         | 0.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 142       | 13.3%   |
| Validity Sensors Fingerprint scanner                                       | 115       | 10.77%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 89        | 8.33%   |
| STMicroelectronics Fingerprint Reader                                      | 78        | 7.3%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 77        | 7.21%   |
| AuthenTec AES1600                                                          | 66        | 6.18%   |
| AuthenTec AES2810                                                          | 56        | 5.24%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 49        | 4.59%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 42        | 3.93%   |
| LighTuning Fingerprint Reader                                              | 42        | 3.93%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 34        | 3.18%   |
| Validity Sensors VFS491                                                    | 28        | 2.62%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 28        | 2.62%   |
| Shenzhen Goodix  Fingerprint Device                                        | 28        | 2.62%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 24        | 2.25%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 20        | 1.87%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 18        | 1.69%   |
| Upek TCS5B Fingerprint sensor                                              | 17        | 1.59%   |
| Elan ELAN:Fingerprint                                                      | 17        | 1.59%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 12        | 1.12%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 9         | 0.84%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 0.66%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 7         | 0.66%   |
| Validity Sensors VFS Fingerprint sensor                                    | 6         | 0.56%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 6         | 0.56%   |
| Focal-systems.Corp FT9201Fingerprint.Ì                                  | 5         | 0.47%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 0.37%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 0.37%   |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 0.37%   |
| Elan ELAN:ARM-M4                                                           | 4         | 0.37%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 3         | 0.28%   |
| Synaptics  WBDI                                                            | 3         | 0.28%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 0.19%   |
| Synaptics WBDI                                                             | 2         | 0.19%   |
| Synaptics UWP WBDI                                                         | 2         | 0.19%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 0.19%   |
| Microsoft Fingerprint Reader                                               | 2         | 0.19%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.09%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.09%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 1         | 0.09%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Broadcom                                | 105       | 33.12%  |
| O2 Micro                                | 53        | 16.72%  |
| Alcor Micro                             | 37        | 11.67%  |
| Lenovo                                  | 28        | 8.83%   |
| Upek                                    | 27        | 8.52%   |
| Aladdin Knowledge Systems               | 14        | 4.42%   |
| Advanced Card Systems                   | 11        | 3.47%   |
| Aktiv                                   | 9         | 2.84%   |
| OmniKey                                 | 8         | 2.52%   |
| Realtek Semiconductor                   | 5         | 1.58%   |
| Gemalto (was Gemplus)                   | 5         | 1.58%   |
| Athena Smartcard Solutions              | 4         | 1.26%   |
| Aladdin R.D.                            | 3         | 0.95%   |
| Castles Technology                      | 2         | 0.63%   |
| Reiner SCT Kartensysteme                | 1         | 0.32%   |
| In Focus Systems                        | 1         | 0.32%   |
| Future Technology Devices International | 1         | 0.32%   |
| Cherry                                  | 1         | 0.32%   |
| BIFIT                                   | 1         | 0.32%   |
| Avtor                                   | 1         | 0.32%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 70        | 22.08%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 37        | 11.67%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 29        | 9.15%   |
| Lenovo Integrated Smart Card Reader                                          | 28        | 8.83%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 27        | 8.52%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 26        | 8.2%    |
| O2 Micro Oz776 SmartCard Reader                                              | 16        | 5.05%   |
| Aladdin Knowledge Systems Token JC                                           | 14        | 4.42%   |
| Alcor Micro Watchdata W 1981                                                 | 8         | 2.52%   |
| Aktiv Rutoken lite                                                           | 8         | 2.52%   |
| Broadcom 5880                                                                | 7         | 2.21%   |
| OmniKey CardMan 1021                                                         | 6         | 1.89%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 5         | 1.58%   |
| Athena Smartcard Solutions ASEDrive CCID                                     | 4         | 1.26%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 4         | 1.26%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.95%   |
| Aladdin R.D. JaCarta                                                         | 3         | 0.95%   |
| Advanced Card Systems Token USB 64K                                          | 3         | 0.95%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 2         | 0.63%   |
| Castles Technology EZCCID Smart Card Reader                                  | 2         | 0.63%   |
| Broadcom 58200                                                               | 2         | 0.63%   |
| Advanced Card Systems ACR3901U                                               | 2         | 0.63%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.32%   |
| OmniKey CardMan 4321                                                         | 1         | 0.32%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.32%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.32%   |
| Future Technology Devices International Parsec Desktop Reader PR-EH08        | 1         | 0.32%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.32%   |
| BIFIT iBank2Key                                                              | 1         | 0.32%   |
| Avtor SecureToken                                                            | 1         | 0.32%   |
| Aktiv KAZTOKEN                                                               | 1         | 0.32%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.32%   |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 1         | 0.32%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 21935     | 77.96%  |
| 1     | 5172      | 18.38%  |
| 2     | 894       | 3.18%   |
| 3     | 107       | 0.38%   |
| 4     | 23        | 0.08%   |
| 5     | 4         | 0.01%   |
| 9     | 1         | 0.004%  |
| 7     | 1         | 0.004%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 3416      | 50.29%  |
| Fingerprint reader       | 1066      | 15.69%  |
| Net/wireless             | 533       | 7.85%   |
| Bluetooth                | 365       | 5.37%   |
| Chipcard                 | 295       | 4.34%   |
| Communication controller | 247       | 3.64%   |
| Multimedia controller    | 241       | 3.55%   |
| Camera                   | 142       | 2.09%   |
| Storage                  | 130       | 1.91%   |
| Flash memory             | 103       | 1.52%   |
| Unassigned class         | 78        | 1.15%   |
| Sound                    | 36        | 0.53%   |
| Modem                    | 30        | 0.44%   |
| Dvb card                 | 28        | 0.41%   |
| Card reader              | 27        | 0.4%    |
| Net/ethernet             | 19        | 0.28%   |
| Network                  | 13        | 0.19%   |
| Tv card                  | 7         | 0.1%    |
| Storage/raid             | 6         | 0.09%   |
| Video                    | 5         | 0.07%   |
| Storage/ata              | 4         | 0.06%   |
| Wireless                 | 1         | 0.01%   |
| Storage/ide              | 1         | 0.01%   |

