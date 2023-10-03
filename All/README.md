Linux - Tested Hardware & Statistics
------------------------------------

A project to collect tested hardware configurations for Linux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Desktop/README.md) and [notebooks](/Notebook/README.md).

Distribution-specific reports: [AlmaLinux](/Dist/AlmaLinux), [Alpine](/Dist/Alpine), [ALT_Linux](/Dist/ALT_Linux), [antiX](/Dist/antiX), [Artix](/Dist/Artix), [Chrome_OS](/Dist/Chrome_OS), [Clear_Linux](/Dist/Clear_Linux), [Deepin](/Dist/Deepin), [Devuan](/Dist/Devuan), [EndeavourOS](/Dist/EndeavourOS), [Garuda_Linux](/Dist/Garuda_Linux), [GNOME_OS](/Dist/GNOME_OS), [Kaisen](/Dist/Kaisen), [Mageia](/Dist/Mageia), [Makulu](/Dist/Makulu), [NixOS](/Dist/NixOS), [Nobara](/Dist/Nobara), [Oracle_Linux](/Dist/Oracle_Linux), [Pardus](/Dist/Pardus), [PureOS](/Dist/PureOS), [Q4OS](/Dist/Q4OS), [Reborn_OS](/Dist/Reborn_OS), [Rocky_Linux](/Dist/Rocky_Linux), [Sparky](/Dist/Sparky), [Void_Linux](/Dist/Void_Linux), [Xero](/Dist/Xero).

This report is for real hardware. Report for virtual hardware: [TestDays_VE](https://github.com/linuxhw/TestDays_VE)

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

Total: 337473

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | B450-A PRO MAX              | Desktop     | [546e058777](https://linux-hardware.org/?probe=546e058777) | Oct 01, 2023 |
| MSI           | B350M PRO-VD PLUS           | Desktop     | [a8c796cebf](https://linux-hardware.org/?probe=a8c796cebf) | Oct 01, 2023 |
| AZW           | MINI S 10                   | Desktop     | [13e3a733fd](https://linux-hardware.org/?probe=13e3a733fd) | Oct 01, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [a8f95ea32d](https://linux-hardware.org/?probe=a8f95ea32d) | Oct 01, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [34b8e1853b](https://linux-hardware.org/?probe=34b8e1853b) | Oct 01, 2023 |
| Colorful T... | BATTLE-AX B365M-D V20       | Desktop     | [f8c7c20100](https://linux-hardware.org/?probe=f8c7c20100) | Oct 01, 2023 |
| Dell          | Vostro 3560                 | Notebook    | [9acebbf655](https://linux-hardware.org/?probe=9acebbf655) | Oct 01, 2023 |
| Acer          | Predator G9-793             | Notebook    | [fd305490af](https://linux-hardware.org/?probe=fd305490af) | Oct 01, 2023 |
| HP            | 339A                        | Desktop     | [cd104d3996](https://linux-hardware.org/?probe=cd104d3996) | Oct 01, 2023 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [fa948b8e32](https://linux-hardware.org/?probe=fa948b8e32) | Oct 01, 2023 |
| HP            | 1494                        | Desktop     | [5250e1dc1c](https://linux-hardware.org/?probe=5250e1dc1c) | Oct 01, 2023 |
| Lenovo        | V15 G4 IRU 83A1             | Notebook    | [c71241f73d](https://linux-hardware.org/?probe=c71241f73d) | Oct 01, 2023 |
| Gigabyte      | 970A-D3                     | Desktop     | [9b47949b87](https://linux-hardware.org/?probe=9b47949b87) | Oct 01, 2023 |
| Lenovo        | V15 G4 IRU 83A1             | Notebook    | [b1af5494c8](https://linux-hardware.org/?probe=b1af5494c8) | Oct 01, 2023 |
| Gigabyte      | Z390 UD                     | Desktop     | [e470a4941a](https://linux-hardware.org/?probe=e470a4941a) | Oct 01, 2023 |
| HP            | ProBook 440 G4              | Notebook    | [810959ffa7](https://linux-hardware.org/?probe=810959ffa7) | Oct 01, 2023 |
| Acer          | Aspire SW5-173              | Notebook    | [b990067acf](https://linux-hardware.org/?probe=b990067acf) | Oct 01, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [aeb0b469c8](https://linux-hardware.org/?probe=aeb0b469c8) | Oct 01, 2023 |
| HP            | Victus by Laptop 16-d0xx... | Notebook    | [5ee355215f](https://linux-hardware.org/?probe=5ee355215f) | Oct 01, 2023 |
| Colorful T... | BATTLE-AX B365M-D V20       | Desktop     | [c118982282](https://linux-hardware.org/?probe=c118982282) | Oct 01, 2023 |
| ASUSTek       | G73Jh                       | Notebook    | [0b9b84be03](https://linux-hardware.org/?probe=0b9b84be03) | Oct 01, 2023 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [3709e611a3](https://linux-hardware.org/?probe=3709e611a3) | Oct 01, 2023 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [6c314cd812](https://linux-hardware.org/?probe=6c314cd812) | Oct 01, 2023 |
| HP            | ENVY m6 Notebook            | Notebook    | [5ef983c393](https://linux-hardware.org/?probe=5ef983c393) | Oct 01, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [1df2dc7261](https://linux-hardware.org/?probe=1df2dc7261) | Oct 01, 2023 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | Notebook    | [bb5a34d03f](https://linux-hardware.org/?probe=bb5a34d03f) | Oct 01, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [279922964e](https://linux-hardware.org/?probe=279922964e) | Oct 01, 2023 |
| HP            | 0A50h                       | Desktop     | [e2082963e9](https://linux-hardware.org/?probe=e2082963e9) | Oct 01, 2023 |
| Digma         | EVE 11 C421Y ES1067EW       | Notebook    | [2a54b2d3e1](https://linux-hardware.org/?probe=2a54b2d3e1) | Oct 01, 2023 |
| Toshiba       | Satellite L735              | Notebook    | [c969a72669](https://linux-hardware.org/?probe=c969a72669) | Oct 01, 2023 |
| Acer          | Predator PH16-71            | Notebook    | [a07278dc43](https://linux-hardware.org/?probe=a07278dc43) | Oct 01, 2023 |
| Lenovo        | MAHOBAY                     | Desktop     | [9ced54f630](https://linux-hardware.org/?probe=9ced54f630) | Oct 01, 2023 |
| Lenovo        | IdeaPad Y700-15ACZ 80NY     | Notebook    | [12d98aba86](https://linux-hardware.org/?probe=12d98aba86) | Oct 01, 2023 |
| Dell          | Latitude E6540              | Notebook    | [8fdc000f7e](https://linux-hardware.org/?probe=8fdc000f7e) | Oct 01, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [9d3a95cfd5](https://linux-hardware.org/?probe=9d3a95cfd5) | Oct 01, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [1e825c5574](https://linux-hardware.org/?probe=1e825c5574) | Oct 01, 2023 |
| MSI           | Z370-A PRO                  | Desktop     | [7c1fdcfb70](https://linux-hardware.org/?probe=7c1fdcfb70) | Oct 01, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [38dba6ab76](https://linux-hardware.org/?probe=38dba6ab76) | Oct 01, 2023 |
| OriginPC      | X170KM-G                    | Notebook    | [2a8752667a](https://linux-hardware.org/?probe=2a8752667a) | Oct 01, 2023 |
| Dell          | Latitude 5520               | Notebook    | [024af71640](https://linux-hardware.org/?probe=024af71640) | Oct 01, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [f9be6afb3a](https://linux-hardware.org/?probe=f9be6afb3a) | Oct 01, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [124425b8b3](https://linux-hardware.org/?probe=124425b8b3) | Oct 01, 2023 |
| Google        | Nocturne                    | Tablet      | [966636d4d1](https://linux-hardware.org/?probe=966636d4d1) | Oct 01, 2023 |
| HP            | 18E5                        | Desktop     | [1f3e02bd3e](https://linux-hardware.org/?probe=1f3e02bd3e) | Oct 01, 2023 |
| Google        | Nocturne                    | Tablet      | [5c4cae2a0b](https://linux-hardware.org/?probe=5c4cae2a0b) | Oct 01, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [4fa536be5c](https://linux-hardware.org/?probe=4fa536be5c) | Oct 01, 2023 |
| Lenovo        | Flex 2-15D 20377            | Notebook    | [8f9e71f454](https://linux-hardware.org/?probe=8f9e71f454) | Oct 01, 2023 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [150d5d9afd](https://linux-hardware.org/?probe=150d5d9afd) | Oct 01, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [efc04e4b27](https://linux-hardware.org/?probe=efc04e4b27) | Oct 01, 2023 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [aa4b869750](https://linux-hardware.org/?probe=aa4b869750) | Oct 01, 2023 |
| Acer          | AOA150                      | Notebook    | [969a729098](https://linux-hardware.org/?probe=969a729098) | Oct 01, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [cd4c3fb654](https://linux-hardware.org/?probe=cd4c3fb654) | Oct 01, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [5d6364a866](https://linux-hardware.org/?probe=5d6364a866) | Oct 01, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [53fec3f094](https://linux-hardware.org/?probe=53fec3f094) | Oct 01, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [9115ea465f](https://linux-hardware.org/?probe=9115ea465f) | Oct 01, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [d17d6d2b70](https://linux-hardware.org/?probe=d17d6d2b70) | Oct 01, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [aae60ff071](https://linux-hardware.org/?probe=aae60ff071) | Oct 01, 2023 |
| Dell          | 0MN1TX A02                  | Desktop     | [3f0eee5de0](https://linux-hardware.org/?probe=3f0eee5de0) | Oct 01, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [7eebcdc80b](https://linux-hardware.org/?probe=7eebcdc80b) | Oct 01, 2023 |
| Dell          | 0427JK A00                  | Desktop     | [de3ece96cf](https://linux-hardware.org/?probe=de3ece96cf) | Oct 01, 2023 |
| Apple         | MacBookPro14,3              | Notebook    | [ec90ed2076](https://linux-hardware.org/?probe=ec90ed2076) | Oct 01, 2023 |
| Shenzhen M... | HX90G                       | Desktop     | [a6e9f6c7fc](https://linux-hardware.org/?probe=a6e9f6c7fc) | Oct 01, 2023 |
| Acer          | Predator PH315-51           | Notebook    | [ed5459b320](https://linux-hardware.org/?probe=ed5459b320) | Oct 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [7b44ef8cd1](https://linux-hardware.org/?probe=7b44ef8cd1) | Oct 01, 2023 |
| Dell          | Inspiron 11-3168            | Notebook    | [967817b4f8](https://linux-hardware.org/?probe=967817b4f8) | Oct 01, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [3e13770075](https://linux-hardware.org/?probe=3e13770075) | Oct 01, 2023 |
| HP            | ProBook 440 G4              | Notebook    | [8db3bb5b34](https://linux-hardware.org/?probe=8db3bb5b34) | Oct 01, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [def4633785](https://linux-hardware.org/?probe=def4633785) | Oct 01, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [5d6115a057](https://linux-hardware.org/?probe=5d6115a057) | Oct 01, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c99f28b27d](https://linux-hardware.org/?probe=c99f28b27d) | Oct 01, 2023 |
| Gigabyte      | D525TUD                     | Desktop     | [913e98318d](https://linux-hardware.org/?probe=913e98318d) | Oct 01, 2023 |
| Dell          | Latitude E6540              | Notebook    | [a5de8b78e7](https://linux-hardware.org/?probe=a5de8b78e7) | Oct 01, 2023 |
| HP            | Dragonfly 13.5 inch G4 N... | Notebook    | [8fabc36e1c](https://linux-hardware.org/?probe=8fabc36e1c) | Oct 01, 2023 |
| Gigabyte      | D525TUD                     | Desktop     | [f48a538837](https://linux-hardware.org/?probe=f48a538837) | Oct 01, 2023 |
| Panasonic     | CFSZ5-3                     | Notebook    | [9d0b849593](https://linux-hardware.org/?probe=9d0b849593) | Oct 01, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [9121e2ab8d](https://linux-hardware.org/?probe=9121e2ab8d) | Oct 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [2127748080](https://linux-hardware.org/?probe=2127748080) | Oct 01, 2023 |
| Dell          | G7 7700                     | Notebook    | [62bd529b36](https://linux-hardware.org/?probe=62bd529b36) | Oct 01, 2023 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [98fd6eb7c8](https://linux-hardware.org/?probe=98fd6eb7c8) | Oct 01, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [0166816d1b](https://linux-hardware.org/?probe=0166816d1b) | Oct 01, 2023 |
| Panasonic     | CFSZ5-3                     | Notebook    | [f2c369cb00](https://linux-hardware.org/?probe=f2c369cb00) | Oct 01, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [1448f32279](https://linux-hardware.org/?probe=1448f32279) | Oct 01, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [c69ebf2472](https://linux-hardware.org/?probe=c69ebf2472) | Oct 01, 2023 |
| ASRock        | FM2A55M-VG3+                | Desktop     | [6faa4fd636](https://linux-hardware.org/?probe=6faa4fd636) | Oct 01, 2023 |
| HP            | ProBook 650 G8 Notebook ... | Notebook    | [b02492c1dd](https://linux-hardware.org/?probe=b02492c1dd) | Oct 01, 2023 |
| Dell          | 0X8DXD A00                  | Desktop     | [a44e0088f6](https://linux-hardware.org/?probe=a44e0088f6) | Oct 01, 2023 |
| Toshiba       | Satellite C850-D4K          | Notebook    | [47d93b3030](https://linux-hardware.org/?probe=47d93b3030) | Oct 01, 2023 |
| GPU Compan... | GWTN156-4                   | Notebook    | [fa5491ff0c](https://linux-hardware.org/?probe=fa5491ff0c) | Oct 01, 2023 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [8985b86479](https://linux-hardware.org/?probe=8985b86479) | Oct 01, 2023 |
| Huanan        | X99 F8D V2.2                | Desktop     | [50101ff8ee](https://linux-hardware.org/?probe=50101ff8ee) | Oct 01, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | Notebook    | [4fc3b1e588](https://linux-hardware.org/?probe=4fc3b1e588) | Oct 01, 2023 |
| Dell          | Latitude XT3                | Notebook    | [725ad34185](https://linux-hardware.org/?probe=725ad34185) | Oct 01, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | Notebook    | [b79529501a](https://linux-hardware.org/?probe=b79529501a) | Oct 01, 2023 |
| ASUSTek       | Z170-DELUXE                 | Desktop     | [9e04efc2d9](https://linux-hardware.org/?probe=9e04efc2d9) | Oct 01, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | Notebook    | [01d6d4f3c4](https://linux-hardware.org/?probe=01d6d4f3c4) | Oct 01, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [e0cdb74f25](https://linux-hardware.org/?probe=e0cdb74f25) | Oct 01, 2023 |
| Dell          | 0D24M8 A01                  | Desktop     | [214eb681ad](https://linux-hardware.org/?probe=214eb681ad) | Oct 01, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | Notebook    | [1a9c5d539b](https://linux-hardware.org/?probe=1a9c5d539b) | Oct 01, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [b85781f0d8](https://linux-hardware.org/?probe=b85781f0d8) | Oct 01, 2023 |
| HP            | Pavilion Laptop 15t-eg30... | Notebook    | [ed7bf5aee1](https://linux-hardware.org/?probe=ed7bf5aee1) | Oct 01, 2023 |
| Valve         | Jupiter                     | Notebook    | [c31d1a5288](https://linux-hardware.org/?probe=c31d1a5288) | Oct 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [ef74c51c65](https://linux-hardware.org/?probe=ef74c51c65) | Oct 01, 2023 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | Notebook    | [61a08e5e89](https://linux-hardware.org/?probe=61a08e5e89) | Oct 01, 2023 |
| Dell          | Inspiron N5010              | Notebook    | [fe6b9d4c65](https://linux-hardware.org/?probe=fe6b9d4c65) | Oct 01, 2023 |
| Dell          | Latitude E6420              | Notebook    | [55c45fb7cb](https://linux-hardware.org/?probe=55c45fb7cb) | Oct 01, 2023 |
| Dell          | Latitude E7270              | Notebook    | [bf1def4fc3](https://linux-hardware.org/?probe=bf1def4fc3) | Oct 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [1330485afc](https://linux-hardware.org/?probe=1330485afc) | Oct 01, 2023 |
| HUAWEI        | MateBook X                  | Notebook    | [5479e52948](https://linux-hardware.org/?probe=5479e52948) | Oct 01, 2023 |
| Packard Be... | EasyNote ENLG81BA           | Notebook    | [c10a5eef39](https://linux-hardware.org/?probe=c10a5eef39) | Oct 01, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [1204d2da33](https://linux-hardware.org/?probe=1204d2da33) | Sep 30, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [bbab99a4f7](https://linux-hardware.org/?probe=bbab99a4f7) | Sep 30, 2023 |
| Valve         | Jupiter                     | Notebook    | [d64d0a1997](https://linux-hardware.org/?probe=d64d0a1997) | Sep 30, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [493a83e70a](https://linux-hardware.org/?probe=493a83e70a) | Sep 30, 2023 |
| Acer          | H57M01                      | Desktop     | [77fd0bf30a](https://linux-hardware.org/?probe=77fd0bf30a) | Sep 30, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [0a11dba9ac](https://linux-hardware.org/?probe=0a11dba9ac) | Sep 30, 2023 |
| ASUSTek       | X756UVK                     | Notebook    | [3bc56b23ef](https://linux-hardware.org/?probe=3bc56b23ef) | Sep 30, 2023 |
| Toshiba       | Satellite C870-1C2          | Notebook    | [d9750c9040](https://linux-hardware.org/?probe=d9750c9040) | Sep 30, 2023 |
| HP            | Laptop 17-cn2xxx            | Notebook    | [4a15c84784](https://linux-hardware.org/?probe=4a15c84784) | Sep 30, 2023 |
| NZXT          | N7 B550                     | Desktop     | [53a99b69e6](https://linux-hardware.org/?probe=53a99b69e6) | Sep 30, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | Notebook    | [83d91ea2fe](https://linux-hardware.org/?probe=83d91ea2fe) | Sep 30, 2023 |
| Foxconn       | 2ADA                        | Desktop     | [da117a4e6a](https://linux-hardware.org/?probe=da117a4e6a) | Sep 30, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [a1f20bb140](https://linux-hardware.org/?probe=a1f20bb140) | Sep 30, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | Notebook    | [0fad85dfc9](https://linux-hardware.org/?probe=0fad85dfc9) | Sep 30, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [085fbda5a6](https://linux-hardware.org/?probe=085fbda5a6) | Sep 30, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [30bf4415dc](https://linux-hardware.org/?probe=30bf4415dc) | Sep 30, 2023 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | Notebook    | [1135ddac8e](https://linux-hardware.org/?probe=1135ddac8e) | Sep 30, 2023 |
| Medion        | Deputy P40                  | Notebook    | [7e0fc5b52d](https://linux-hardware.org/?probe=7e0fc5b52d) | Sep 30, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [0b4432877e](https://linux-hardware.org/?probe=0b4432877e) | Sep 30, 2023 |
| Gigabyte      | H61M-S2-B3                  | Desktop     | [447e04bd9d](https://linux-hardware.org/?probe=447e04bd9d) | Sep 30, 2023 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [35830807d4](https://linux-hardware.org/?probe=35830807d4) | Sep 30, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [1449844643](https://linux-hardware.org/?probe=1449844643) | Sep 30, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [7a670fe0ef](https://linux-hardware.org/?probe=7a670fe0ef) | Sep 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [59dcd18330](https://linux-hardware.org/?probe=59dcd18330) | Sep 30, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [e6e1c9bac9](https://linux-hardware.org/?probe=e6e1c9bac9) | Sep 30, 2023 |
| Apple         | MacBookPro5,3               | Notebook    | [0669d0020d](https://linux-hardware.org/?probe=0669d0020d) | Sep 30, 2023 |
| HP            | Compaq nc6320 (EN368UT#A... | Notebook    | [71ba4fd9e9](https://linux-hardware.org/?probe=71ba4fd9e9) | Sep 30, 2023 |
| ASUSTek       | Zenbook UX562UG_UM562UG     | Convertible | [12b00e912f](https://linux-hardware.org/?probe=12b00e912f) | Sep 30, 2023 |
| ASUSTek       | Zenbook UX562UG_UM562UG     | Convertible | [2f6c62d407](https://linux-hardware.org/?probe=2f6c62d407) | Sep 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [a6d0762090](https://linux-hardware.org/?probe=a6d0762090) | Sep 30, 2023 |
| Gigabyte      | Z390 UD                     | Desktop     | [864f9a143f](https://linux-hardware.org/?probe=864f9a143f) | Sep 30, 2023 |
| HP            | EliteBook 745 G3            | Notebook    | [5cae9ddf98](https://linux-hardware.org/?probe=5cae9ddf98) | Sep 30, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [4575deef12](https://linux-hardware.org/?probe=4575deef12) | Sep 30, 2023 |
| HUAWEI        | VLT-WX0                     | Notebook    | [a312a57d16](https://linux-hardware.org/?probe=a312a57d16) | Sep 30, 2023 |
| Fujitsu Si... | AMILO A1650G                | Notebook    | [ec61a60044](https://linux-hardware.org/?probe=ec61a60044) | Sep 30, 2023 |
| ASRock        | A88M-G                      | Desktop     | [a918b08771](https://linux-hardware.org/?probe=a918b08771) | Sep 30, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [9b1cc15d8a](https://linux-hardware.org/?probe=9b1cc15d8a) | Sep 30, 2023 |
| MSI           | Prestige 14H B12UCX         | Notebook    | [b3a006adc7](https://linux-hardware.org/?probe=b3a006adc7) | Sep 30, 2023 |
| Dynabook      | TECRA A50-J                 | Notebook    | [e0927243be](https://linux-hardware.org/?probe=e0927243be) | Sep 30, 2023 |
| Toshiba       | STI 009169                  | Desktop     | [0b76bae8f3](https://linux-hardware.org/?probe=0b76bae8f3) | Sep 30, 2023 |
| Lenovo        | G505s 20255                 | Notebook    | [58a1c6e106](https://linux-hardware.org/?probe=58a1c6e106) | Sep 30, 2023 |
| Lenovo        | ThinkCentre M55p 8811ZD4    | Desktop     | [710dea5f88](https://linux-hardware.org/?probe=710dea5f88) | Sep 30, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [64e8a0bcc2](https://linux-hardware.org/?probe=64e8a0bcc2) | Sep 30, 2023 |
| Unknown       | Unknown                     | Soc         | [8024d770d9](https://linux-hardware.org/?probe=8024d770d9) | Sep 30, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [e2c6027a51](https://linux-hardware.org/?probe=e2c6027a51) | Sep 30, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [48ff113276](https://linux-hardware.org/?probe=48ff113276) | Sep 30, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | Desktop     | [f3d279f91b](https://linux-hardware.org/?probe=f3d279f91b) | Sep 30, 2023 |
| HP            | EliteBook 830 G6            | Notebook    | [154150aa88](https://linux-hardware.org/?probe=154150aa88) | Sep 30, 2023 |
| Juana Mans... | SF20GM7                     | Notebook    | [b2b359c659](https://linux-hardware.org/?probe=b2b359c659) | Sep 30, 2023 |
| ASUSTek       | A55BM-K                     | Desktop     | [532e0b0654](https://linux-hardware.org/?probe=532e0b0654) | Sep 30, 2023 |
| Lenovo        | ThinkPad X200 745536T       | Notebook    | [62740874ab](https://linux-hardware.org/?probe=62740874ab) | Sep 30, 2023 |
| ASRock        | B75 Pro3-M                  | Desktop     | [05c68ef556](https://linux-hardware.org/?probe=05c68ef556) | Sep 30, 2023 |
| ASUSTek       | Z450LA                      | Notebook    | [afa96a084e](https://linux-hardware.org/?probe=afa96a084e) | Sep 30, 2023 |
| Juana Mans... | SF20GM7                     | Notebook    | [b4a58da74c](https://linux-hardware.org/?probe=b4a58da74c) | Sep 30, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [eb46d26ff8](https://linux-hardware.org/?probe=eb46d26ff8) | Sep 30, 2023 |
| ECS           | G31T-M7                     | Desktop     | [0749fa9352](https://linux-hardware.org/?probe=0749fa9352) | Sep 30, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [4a47d466d9](https://linux-hardware.org/?probe=4a47d466d9) | Sep 30, 2023 |
| MSI           | Prestige 15 A10SC           | Notebook    | [6e53cd8a65](https://linux-hardware.org/?probe=6e53cd8a65) | Sep 30, 2023 |
| Valve         | Jupiter                     | Notebook    | [0488b8fd24](https://linux-hardware.org/?probe=0488b8fd24) | Sep 30, 2023 |
| Lenovo        | ThinkPad T440 20B7S1K400    | Notebook    | [fd03530876](https://linux-hardware.org/?probe=fd03530876) | Sep 30, 2023 |
| ASRock        | A320M-DGS                   | Desktop     | [63aafe31f1](https://linux-hardware.org/?probe=63aafe31f1) | Sep 30, 2023 |
| Juana Mans... | SF20GM7                     | Notebook    | [ccb9b4e795](https://linux-hardware.org/?probe=ccb9b4e795) | Sep 30, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [b8aadf6823](https://linux-hardware.org/?probe=b8aadf6823) | Sep 30, 2023 |
| ASUSTek       | F7SR                        | Notebook    | [b895fd8bb2](https://linux-hardware.org/?probe=b895fd8bb2) | Sep 30, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [34e5bf82de](https://linux-hardware.org/?probe=34e5bf82de) | Sep 30, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [8487059659](https://linux-hardware.org/?probe=8487059659) | Sep 30, 2023 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [6074f655ad](https://linux-hardware.org/?probe=6074f655ad) | Sep 30, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [d180995f93](https://linux-hardware.org/?probe=d180995f93) | Sep 30, 2023 |
| ASUSTek       | F7SR                        | Notebook    | [1b7493ae6e](https://linux-hardware.org/?probe=1b7493ae6e) | Sep 30, 2023 |
| Infinix       | INBOOK X3                   | Notebook    | [6b5c2647c2](https://linux-hardware.org/?probe=6b5c2647c2) | Sep 30, 2023 |
| HP            | EliteBook 745 G3            | Notebook    | [700c901144](https://linux-hardware.org/?probe=700c901144) | Sep 30, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [80ac43658d](https://linux-hardware.org/?probe=80ac43658d) | Sep 30, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [c9aca83f04](https://linux-hardware.org/?probe=c9aca83f04) | Sep 30, 2023 |
| Lenovo        | ThinkPad X260 VB6R77903H    | Notebook    | [e7dad368d2](https://linux-hardware.org/?probe=e7dad368d2) | Sep 30, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [951a03d2ad](https://linux-hardware.org/?probe=951a03d2ad) | Sep 30, 2023 |
| Shenzhen M... | F7BSC                       | Desktop     | [79b4f4f30e](https://linux-hardware.org/?probe=79b4f4f30e) | Sep 30, 2023 |
| Acer          | Predator G3610              | Desktop     | [cddfa514ba](https://linux-hardware.org/?probe=cddfa514ba) | Sep 30, 2023 |
| ASUSTek       | F2A85-M PRO                 | Desktop     | [79d4084e18](https://linux-hardware.org/?probe=79d4084e18) | Sep 30, 2023 |
| HP            | Pro Tablet 608 G1           | Notebook    | [14fcb9ce4b](https://linux-hardware.org/?probe=14fcb9ce4b) | Sep 30, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [c8a525522f](https://linux-hardware.org/?probe=c8a525522f) | Sep 30, 2023 |
| MSI           | Prestige 14H B12UCX         | Notebook    | [1c1f35d1c8](https://linux-hardware.org/?probe=1c1f35d1c8) | Sep 30, 2023 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [63c99972d1](https://linux-hardware.org/?probe=63c99972d1) | Sep 30, 2023 |
| HP            | EliteBook 745 G3            | Notebook    | [16f4068970](https://linux-hardware.org/?probe=16f4068970) | Sep 30, 2023 |
| Dell          | Latitude 5410               | Notebook    | [8234abf02b](https://linux-hardware.org/?probe=8234abf02b) | Sep 30, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [6ee0910511](https://linux-hardware.org/?probe=6ee0910511) | Sep 30, 2023 |
| Fujitsu Si... | AMILO Pa 2548               | Notebook    | [ee2d5e25d3](https://linux-hardware.org/?probe=ee2d5e25d3) | Sep 30, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [bee067d5dd](https://linux-hardware.org/?probe=bee067d5dd) | Sep 30, 2023 |
| MSI           | 890FXA-GD70                 | Desktop     | [f9c2509bc6](https://linux-hardware.org/?probe=f9c2509bc6) | Sep 30, 2023 |
| Acer          | Aspire E1-572G              | Notebook    | [f7375967ee](https://linux-hardware.org/?probe=f7375967ee) | Sep 30, 2023 |
| Lenovo        | ThinkPad X260 VB6R77903H    | Notebook    | [de3079ae33](https://linux-hardware.org/?probe=de3079ae33) | Sep 30, 2023 |
| Gigabyte      | G31M-S2L                    | Desktop     | [4f147c1f3a](https://linux-hardware.org/?probe=4f147c1f3a) | Sep 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b3959728d3](https://linux-hardware.org/?probe=b3959728d3) | Sep 30, 2023 |
| Gigabyte      | G31M-S2L                    | Desktop     | [391af7c221](https://linux-hardware.org/?probe=391af7c221) | Sep 30, 2023 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [a7683dc02d](https://linux-hardware.org/?probe=a7683dc02d) | Sep 30, 2023 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [c93af00811](https://linux-hardware.org/?probe=c93af00811) | Sep 30, 2023 |
| Colorful T... | BATTLE-AX B365M-D V20       | Desktop     | [e212af9208](https://linux-hardware.org/?probe=e212af9208) | Sep 30, 2023 |
| Entroware     | Hybris                      | Notebook    | [5b124e9b7f](https://linux-hardware.org/?probe=5b124e9b7f) | Sep 30, 2023 |
| ASUSTek       | P5B-E Plus                  | Desktop     | [78c413cac5](https://linux-hardware.org/?probe=78c413cac5) | Sep 30, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | Desktop     | [02af70281a](https://linux-hardware.org/?probe=02af70281a) | Sep 30, 2023 |
| Acer          | Aspire E5-571G              | Notebook    | [b223d9b4f5](https://linux-hardware.org/?probe=b223d9b4f5) | Sep 30, 2023 |
| Dell          | Latitude 7280               | Notebook    | [dbe9d3e4be](https://linux-hardware.org/?probe=dbe9d3e4be) | Sep 30, 2023 |
| Gigabyte      | P31-ES3G                    | Desktop     | [bee14e504c](https://linux-hardware.org/?probe=bee14e504c) | Sep 30, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [73b5907f17](https://linux-hardware.org/?probe=73b5907f17) | Sep 30, 2023 |
| Fujitsu Si... | AMILO Pro Edition V3405     | Notebook    | [4814760ac1](https://linux-hardware.org/?probe=4814760ac1) | Sep 30, 2023 |
| Toshiba       | PORTEGE R30-D               | Notebook    | [04ef694f1d](https://linux-hardware.org/?probe=04ef694f1d) | Sep 30, 2023 |
| Dell          | 0Y56T3 A01                  | Desktop     | [bfc1d1dd13](https://linux-hardware.org/?probe=bfc1d1dd13) | Sep 30, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [2d1ada9dbe](https://linux-hardware.org/?probe=2d1ada9dbe) | Sep 30, 2023 |
| UNOWHY        | Y13G012S4EI                 | Notebook    | [2b60435562](https://linux-hardware.org/?probe=2b60435562) | Sep 30, 2023 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [d39169bf21](https://linux-hardware.org/?probe=d39169bf21) | Sep 30, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [288f5f8266](https://linux-hardware.org/?probe=288f5f8266) | Sep 30, 2023 |
| Pegatron      | Eureka3                     | Desktop     | [e5c7ff0c70](https://linux-hardware.org/?probe=e5c7ff0c70) | Sep 30, 2023 |
| Metabox       | Prime-X X170KM              | Notebook    | [8ab33a8bd3](https://linux-hardware.org/?probe=8ab33a8bd3) | Sep 30, 2023 |
| ASRock        | 960GM/U3S3 FX               | Desktop     | [e2175cc32b](https://linux-hardware.org/?probe=e2175cc32b) | Sep 30, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [e796baf50f](https://linux-hardware.org/?probe=e796baf50f) | Sep 30, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [a8bea5ed82](https://linux-hardware.org/?probe=a8bea5ed82) | Sep 30, 2023 |
| Dell          | 0YXT71 A02                  | Desktop     | [6bc3385414](https://linux-hardware.org/?probe=6bc3385414) | Sep 30, 2023 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [b2a213cc18](https://linux-hardware.org/?probe=b2a213cc18) | Sep 30, 2023 |
| Gigabyte      | Z87X-UD3H-CF                | Desktop     | [7f47d1f656](https://linux-hardware.org/?probe=7f47d1f656) | Sep 30, 2023 |
| Lenovo        | ThinkPad Edge E530 62722... | Notebook    | [681d3e6c86](https://linux-hardware.org/?probe=681d3e6c86) | Sep 30, 2023 |
| Lenovo        | ThinkPad L530 24783R8       | Notebook    | [eda040f456](https://linux-hardware.org/?probe=eda040f456) | Sep 30, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [bc2e88dd9c](https://linux-hardware.org/?probe=bc2e88dd9c) | Sep 30, 2023 |
| Dell          | 0V8WGR A02                  | Desktop     | [9c9ded765b](https://linux-hardware.org/?probe=9c9ded765b) | Sep 30, 2023 |
| Fujitsu Si... | AMILO Pa 2548               | Notebook    | [a291afc6c3](https://linux-hardware.org/?probe=a291afc6c3) | Sep 30, 2023 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | Notebook    | [58552d0532](https://linux-hardware.org/?probe=58552d0532) | Sep 30, 2023 |
| Microsoft     | Surface Go                  | Tablet      | [eec72cef4a](https://linux-hardware.org/?probe=eec72cef4a) | Sep 30, 2023 |
| MSI           | MPG Z390M GAMING EDGE AC    | Desktop     | [04432690a4](https://linux-hardware.org/?probe=04432690a4) | Sep 30, 2023 |
| Dell          | 0P301D A00                  | Desktop     | [99587baa3d](https://linux-hardware.org/?probe=99587baa3d) | Sep 30, 2023 |
| Medion        | B660M DS3H AX DDR4          | Desktop     | [1dbbeda8cd](https://linux-hardware.org/?probe=1dbbeda8cd) | Sep 30, 2023 |
| Medion        | MS-7667                     | Desktop     | [a91527e825](https://linux-hardware.org/?probe=a91527e825) | Sep 30, 2023 |
| Fanless Mi... | Rev GMLR1                   | Mini pc     | [751b4d268a](https://linux-hardware.org/?probe=751b4d268a) | Sep 30, 2023 |
| Dell          | Latitude 5430               | Notebook    | [eee2a34ff5](https://linux-hardware.org/?probe=eee2a34ff5) | Sep 30, 2023 |
| Medion        | B660M DS3H AX DDR4          | Desktop     | [57a42b9ccf](https://linux-hardware.org/?probe=57a42b9ccf) | Sep 30, 2023 |
| Intel Clie... | LAPBC710                    | Notebook    | [3a29dfa2e3](https://linux-hardware.org/?probe=3a29dfa2e3) | Sep 30, 2023 |
| Acer          | Aspire 5560                 | Notebook    | [252d19e4f5](https://linux-hardware.org/?probe=252d19e4f5) | Sep 30, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1402CBA... | Notebook    | [91873a529a](https://linux-hardware.org/?probe=91873a529a) | Sep 30, 2023 |
| Timi          | Mi NoteBook Ultra           | Notebook    | [1c4b1aa68d](https://linux-hardware.org/?probe=1c4b1aa68d) | Sep 30, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [3421ba07f9](https://linux-hardware.org/?probe=3421ba07f9) | Sep 30, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [480316a0da](https://linux-hardware.org/?probe=480316a0da) | Sep 30, 2023 |
| IX1401        | Unknown                     | Notebook    | [c77c1d010e](https://linux-hardware.org/?probe=c77c1d010e) | Sep 30, 2023 |
| AZW           | MINI S 10                   | Desktop     | [e065b9c701](https://linux-hardware.org/?probe=e065b9c701) | Sep 30, 2023 |
| ASUSTek       | CG8480                      | Desktop     | [dc174e8f73](https://linux-hardware.org/?probe=dc174e8f73) | Sep 30, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [eab41d0848](https://linux-hardware.org/?probe=eab41d0848) | Sep 30, 2023 |
| Valve         | Jupiter                     | Notebook    | [85eac5b7ce](https://linux-hardware.org/?probe=85eac5b7ce) | Sep 30, 2023 |
| Lenovo        | ThinkPad X230 2325KZ5       | Notebook    | [7c10f1a5de](https://linux-hardware.org/?probe=7c10f1a5de) | Sep 30, 2023 |
| HP            | ProBook 645 G1              | Notebook    | [f5f538105c](https://linux-hardware.org/?probe=f5f538105c) | Sep 30, 2023 |
| Dell          | 0Y958C A00                  | Desktop     | [95bf9d14db](https://linux-hardware.org/?probe=95bf9d14db) | Sep 30, 2023 |
| Toshiba       | Satellite L500              | Notebook    | [9c1b258088](https://linux-hardware.org/?probe=9c1b258088) | Sep 30, 2023 |
| Gigabyte      | X399 DESIGNARE EX-CF        | Desktop     | [4835df59b1](https://linux-hardware.org/?probe=4835df59b1) | Sep 30, 2023 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [2a293067f5](https://linux-hardware.org/?probe=2a293067f5) | Sep 30, 2023 |
| HP            | Pro Tablet 608 G1           | Notebook    | [ab84386c83](https://linux-hardware.org/?probe=ab84386c83) | Sep 30, 2023 |
| Toshiba       | QOSMIO X770                 | Notebook    | [c747b27390](https://linux-hardware.org/?probe=c747b27390) | Sep 30, 2023 |
| Gigabyte      | X99-UD3-CF                  | Desktop     | [f1cc7e5a93](https://linux-hardware.org/?probe=f1cc7e5a93) | Sep 30, 2023 |
| Intel         | DG33SXG2 AAD94468-500       | Desktop     | [99fe490330](https://linux-hardware.org/?probe=99fe490330) | Sep 30, 2023 |
| Dell          | Latitude 7390               | Notebook    | [bd6d90d41e](https://linux-hardware.org/?probe=bd6d90d41e) | Sep 30, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [4074a9c221](https://linux-hardware.org/?probe=4074a9c221) | Sep 30, 2023 |
| Lenovo        | ThinkCentre M58e 7514A2U    | Desktop     | [68f162bf42](https://linux-hardware.org/?probe=68f162bf42) | Sep 30, 2023 |
| Timi          | Mi NoteBook Ultra           | Notebook    | [988f015a89](https://linux-hardware.org/?probe=988f015a89) | Sep 30, 2023 |
| Gigabyte      | X99-UD3-CF                  | Desktop     | [51d10770c6](https://linux-hardware.org/?probe=51d10770c6) | Sep 30, 2023 |
| MP            | MS-7848                     | Desktop     | [63d5662351](https://linux-hardware.org/?probe=63d5662351) | Sep 30, 2023 |
| Fujitsu       | D3401-A1 S26361-D3401-A1    | Desktop     | [5d41b45d45](https://linux-hardware.org/?probe=5d41b45d45) | Sep 30, 2023 |
| HP            | Pavilion dv5                | Notebook    | [0b1da8643f](https://linux-hardware.org/?probe=0b1da8643f) | Sep 30, 2023 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | Notebook    | [a343a1c573](https://linux-hardware.org/?probe=a343a1c573) | Sep 30, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [2fc3f16671](https://linux-hardware.org/?probe=2fc3f16671) | Sep 30, 2023 |
| Dell          | Inspiron 15 3525            | Notebook    | [b46d569d14](https://linux-hardware.org/?probe=b46d569d14) | Sep 30, 2023 |
| Dell          | Inspiron 15 3525            | Notebook    | [fb52caaee9](https://linux-hardware.org/?probe=fb52caaee9) | Sep 30, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [e26d1b1ae4](https://linux-hardware.org/?probe=e26d1b1ae4) | Sep 30, 2023 |
| TECNO         | MEGABOOK T1                 | Notebook    | [9bba77e02b](https://linux-hardware.org/?probe=9bba77e02b) | Sep 30, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | Desktop     | [9a749a1c41](https://linux-hardware.org/?probe=9a749a1c41) | Sep 30, 2023 |
| Packard Be... | EasyNote TK85               | Notebook    | [0c62f48dda](https://linux-hardware.org/?probe=0c62f48dda) | Sep 30, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [770e7037d3](https://linux-hardware.org/?probe=770e7037d3) | Sep 30, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | Desktop     | [452cd2622a](https://linux-hardware.org/?probe=452cd2622a) | Sep 30, 2023 |
| HP            | ProBook 6560b               | Notebook    | [904f0eb2cb](https://linux-hardware.org/?probe=904f0eb2cb) | Sep 30, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [89d519a3f5](https://linux-hardware.org/?probe=89d519a3f5) | Sep 30, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [237492c356](https://linux-hardware.org/?probe=237492c356) | Sep 30, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [813b0bcb38](https://linux-hardware.org/?probe=813b0bcb38) | Sep 30, 2023 |
| Lenovo        | ThinkPad T420 4180BV1       | Notebook    | [e81749053b](https://linux-hardware.org/?probe=e81749053b) | Sep 30, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [3d40d7878a](https://linux-hardware.org/?probe=3d40d7878a) | Sep 30, 2023 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [5a507ec4da](https://linux-hardware.org/?probe=5a507ec4da) | Sep 30, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [b3617a1e58](https://linux-hardware.org/?probe=b3617a1e58) | Sep 30, 2023 |
| HP            | 89E9 0100                   | All in one  | [d1d88cad3f](https://linux-hardware.org/?probe=d1d88cad3f) | Sep 30, 2023 |
| HP            | 89E9 0100                   | All in one  | [4fe32a2ec3](https://linux-hardware.org/?probe=4fe32a2ec3) | Sep 30, 2023 |
| Lenovo        | ThinkPad E495 20NES07V00    | Notebook    | [935dc10f6b](https://linux-hardware.org/?probe=935dc10f6b) | Sep 30, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [6ce97609be](https://linux-hardware.org/?probe=6ce97609be) | Sep 30, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [da0e120624](https://linux-hardware.org/?probe=da0e120624) | Sep 30, 2023 |
| Acer          | Aspire SW3-016              | Notebook    | [62c3855aa7](https://linux-hardware.org/?probe=62c3855aa7) | Sep 30, 2023 |
| HP            | Notebook                    | Notebook    | [873004172f](https://linux-hardware.org/?probe=873004172f) | Sep 30, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [ba4aa68077](https://linux-hardware.org/?probe=ba4aa68077) | Sep 30, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [2edc7ab56b](https://linux-hardware.org/?probe=2edc7ab56b) | Sep 30, 2023 |
| Dell          | Latitude 5410               | Notebook    | [d13c5769a3](https://linux-hardware.org/?probe=d13c5769a3) | Sep 30, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [a0e4942d9f](https://linux-hardware.org/?probe=a0e4942d9f) | Sep 30, 2023 |
| Toshiba       | Satellite C845D             | Notebook    | [92651c9e51](https://linux-hardware.org/?probe=92651c9e51) | Sep 30, 2023 |
| Dell          | Vostro 3350                 | Notebook    | [1034a53a9d](https://linux-hardware.org/?probe=1034a53a9d) | Sep 30, 2023 |
| Apple         | MacBookPro5,3               | Notebook    | [d249d5e114](https://linux-hardware.org/?probe=d249d5e114) | Sep 30, 2023 |
| Unknown       | Phitronics N68C-M           | Desktop     | [72b5c903d3](https://linux-hardware.org/?probe=72b5c903d3) | Sep 30, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [a36938e994](https://linux-hardware.org/?probe=a36938e994) | Sep 30, 2023 |
| MSI           | P67A-C43                    | Desktop     | [22492f6d47](https://linux-hardware.org/?probe=22492f6d47) | Sep 30, 2023 |
| Sony          | VPCEG10EL                   | Notebook    | [8271942cc2](https://linux-hardware.org/?probe=8271942cc2) | Sep 30, 2023 |
| Dell          | 0YJPT1 A00                  | Desktop     | [27b01f468d](https://linux-hardware.org/?probe=27b01f468d) | Sep 30, 2023 |
| BANGHO        | MAX G0101                   | Notebook    | [b867aa1824](https://linux-hardware.org/?probe=b867aa1824) | Sep 30, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | Notebook    | [702d68e226](https://linux-hardware.org/?probe=702d68e226) | Sep 30, 2023 |
| Acer          | Aspire A514-53              | Notebook    | [6d8a5b1a13](https://linux-hardware.org/?probe=6d8a5b1a13) | Sep 30, 2023 |
| Alienware     | m15 R4                      | Notebook    | [a67899ed06](https://linux-hardware.org/?probe=a67899ed06) | Sep 30, 2023 |
| Valve         | Jupiter                     | Notebook    | [1ed8509a3d](https://linux-hardware.org/?probe=1ed8509a3d) | Sep 30, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [527c8192a9](https://linux-hardware.org/?probe=527c8192a9) | Sep 30, 2023 |
| HP            | 8055                        | Desktop     | [3ddf31c78e](https://linux-hardware.org/?probe=3ddf31c78e) | Sep 30, 2023 |
| Acer          | Aspire 7741                 | Notebook    | [80d27e2808](https://linux-hardware.org/?probe=80d27e2808) | Sep 30, 2023 |
| Dell          | Inspiron 5521               | Notebook    | [a704dd3c01](https://linux-hardware.org/?probe=a704dd3c01) | Sep 30, 2023 |
| ASRock        | A300M-STX                   | Desktop     | [d8c97108ad](https://linux-hardware.org/?probe=d8c97108ad) | Sep 30, 2023 |
| VALE          | Notebook Classic C140       | Notebook    | [5be7208021](https://linux-hardware.org/?probe=5be7208021) | Sep 30, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [3bec9011bd](https://linux-hardware.org/?probe=3bec9011bd) | Sep 30, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [74bed86ee5](https://linux-hardware.org/?probe=74bed86ee5) | Sep 30, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [5705bf79ad](https://linux-hardware.org/?probe=5705bf79ad) | Sep 30, 2023 |
| Acer          | H57M01                      | Desktop     | [d506730eed](https://linux-hardware.org/?probe=d506730eed) | Sep 30, 2023 |
| Fujitsu       | D3401-A1 S26361-D3401-A1    | Desktop     | [65643e78ef](https://linux-hardware.org/?probe=65643e78ef) | Sep 30, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [202a977fce](https://linux-hardware.org/?probe=202a977fce) | Sep 30, 2023 |
| Google        | Jerry                       | Desktop     | [467be71aaf](https://linux-hardware.org/?probe=467be71aaf) | Sep 30, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6555        | Notebook    | [703170e428](https://linux-hardware.org/?probe=703170e428) | Sep 30, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [3710f99f83](https://linux-hardware.org/?probe=3710f99f83) | Sep 30, 2023 |
| ASRock        | 4Core1600-GLAN              | Desktop     | [aefbc14017](https://linux-hardware.org/?probe=aefbc14017) | Sep 30, 2023 |
| Lenovo        | YB1-X91F                    | Convertible | [36523ad102](https://linux-hardware.org/?probe=36523ad102) | Sep 30, 2023 |
| ASRock        | A300M-STX                   | Desktop     | [bcbf0e5bfd](https://linux-hardware.org/?probe=bcbf0e5bfd) | Sep 30, 2023 |
| HP            | Pavilion dv6                | Notebook    | [e2560d6378](https://linux-hardware.org/?probe=e2560d6378) | Sep 30, 2023 |
| HP            | Notebook                    | Notebook    | [193ec8deb3](https://linux-hardware.org/?probe=193ec8deb3) | Sep 30, 2023 |
| ASRockRack    | Z690D4U-2L2T/G5             | Server      | [cc642b859b](https://linux-hardware.org/?probe=cc642b859b) | Sep 30, 2023 |
| HP            | Dragonfly 13.5 inch G4 N... | Notebook    | [2afa933d2a](https://linux-hardware.org/?probe=2afa933d2a) | Sep 30, 2023 |
| Unknown       | Unknown                     | Notebook    | [56580ba351](https://linux-hardware.org/?probe=56580ba351) | Sep 30, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [c69ab4bc0f](https://linux-hardware.org/?probe=c69ab4bc0f) | Sep 30, 2023 |
| HP            | ZBook Studio G5             | Notebook    | [3f96bd2883](https://linux-hardware.org/?probe=3f96bd2883) | Sep 30, 2023 |
| Lenovo        | 300s-15ARR 81FB             | Notebook    | [4f7e627fd2](https://linux-hardware.org/?probe=4f7e627fd2) | Sep 30, 2023 |
| HP            | Dragonfly 13.5 inch G4 N... | Notebook    | [a7a8e627cb](https://linux-hardware.org/?probe=a7a8e627cb) | Sep 30, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [4a7b1ee936](https://linux-hardware.org/?probe=4a7b1ee936) | Sep 29, 2023 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | Notebook    | [306bc123c4](https://linux-hardware.org/?probe=306bc123c4) | Sep 29, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [186991da49](https://linux-hardware.org/?probe=186991da49) | Sep 29, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [145f7eccd3](https://linux-hardware.org/?probe=145f7eccd3) | Sep 29, 2023 |
| Pegatron      | 2AB6                        | Desktop     | [4bb43a39c1](https://linux-hardware.org/?probe=4bb43a39c1) | Sep 29, 2023 |
| Lenovo        | G770 1037                   | Notebook    | [576bbd3839](https://linux-hardware.org/?probe=576bbd3839) | Sep 29, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [c1a605af33](https://linux-hardware.org/?probe=c1a605af33) | Sep 29, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [4567599161](https://linux-hardware.org/?probe=4567599161) | Sep 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [86d39b72d6](https://linux-hardware.org/?probe=86d39b72d6) | Sep 29, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [a318f83948](https://linux-hardware.org/?probe=a318f83948) | Sep 29, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [3c9f4d4aef](https://linux-hardware.org/?probe=3c9f4d4aef) | Sep 29, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [526458167b](https://linux-hardware.org/?probe=526458167b) | Sep 29, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [a3af35a207](https://linux-hardware.org/?probe=a3af35a207) | Sep 29, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20UGA... | Notebook    | [8c1d3fc469](https://linux-hardware.org/?probe=8c1d3fc469) | Sep 29, 2023 |
| ASUSTek       | P5B                         | Desktop     | [cb521fc290](https://linux-hardware.org/?probe=cb521fc290) | Sep 29, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [dea46b2302](https://linux-hardware.org/?probe=dea46b2302) | Sep 29, 2023 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [4d2f60a496](https://linux-hardware.org/?probe=4d2f60a496) | Sep 29, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [587f9a3ff1](https://linux-hardware.org/?probe=587f9a3ff1) | Sep 29, 2023 |
| Lenovo        | IdeaPad Slim 3 15IRU8 82... | Notebook    | [e9dd0291e0](https://linux-hardware.org/?probe=e9dd0291e0) | Sep 29, 2023 |
| Sony          | VPCEB4J0E                   | Notebook    | [05864978df](https://linux-hardware.org/?probe=05864978df) | Sep 29, 2023 |
| Lenovo        | Z50-70 20354                | Notebook    | [eb33abdaae](https://linux-hardware.org/?probe=eb33abdaae) | Sep 29, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [1b6440f722](https://linux-hardware.org/?probe=1b6440f722) | Sep 29, 2023 |
| Dell          | Latitude 3301               | Notebook    | [3859ed5445](https://linux-hardware.org/?probe=3859ed5445) | Sep 29, 2023 |
| Dell          | 0Y2K8N A01                  | Desktop     | [46ac9f9904](https://linux-hardware.org/?probe=46ac9f9904) | Sep 29, 2023 |
| Lenovo        | 1051F 60073                 | Tablet      | [dd35e37770](https://linux-hardware.org/?probe=dd35e37770) | Sep 29, 2023 |
| Intel         | H61                         | Desktop     | [f6a417439c](https://linux-hardware.org/?probe=f6a417439c) | Sep 29, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [ec1384a424](https://linux-hardware.org/?probe=ec1384a424) | Sep 29, 2023 |
| Razer         | Blade 15 Base Model (Lat... | Notebook    | [95dc405a73](https://linux-hardware.org/?probe=95dc405a73) | Sep 29, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [8ba160ee59](https://linux-hardware.org/?probe=8ba160ee59) | Sep 29, 2023 |
| Acer          | Aspire E1-572G              | Notebook    | [9fe3adb466](https://linux-hardware.org/?probe=9fe3adb466) | Sep 29, 2023 |
| HP            | 8054                        | Desktop     | [20f337b1e7](https://linux-hardware.org/?probe=20f337b1e7) | Sep 29, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [8e039e23f3](https://linux-hardware.org/?probe=8e039e23f3) | Sep 29, 2023 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [60e32143f5](https://linux-hardware.org/?probe=60e32143f5) | Sep 29, 2023 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | Notebook    | [6e7e482b2d](https://linux-hardware.org/?probe=6e7e482b2d) | Sep 29, 2023 |
| Intel         | H61                         | Desktop     | [e7dac2f9ed](https://linux-hardware.org/?probe=e7dac2f9ed) | Sep 29, 2023 |
| Dell          | 0WWR83 A05                  | Server      | [f099698b0e](https://linux-hardware.org/?probe=f099698b0e) | Sep 29, 2023 |
| Foxconn       | 2AB1                        | Desktop     | [28ef0f3fbc](https://linux-hardware.org/?probe=28ef0f3fbc) | Sep 29, 2023 |
| HP            | Laptop 17-cn1xxx            | Notebook    | [051a233121](https://linux-hardware.org/?probe=051a233121) | Sep 29, 2023 |
| Tectoy        | Pense Bem Notebook          | Notebook    | [6a6e6af34c](https://linux-hardware.org/?probe=6a6e6af34c) | Sep 29, 2023 |
| Lenovo        | 1051F 60073                 | Tablet      | [9b9931bd50](https://linux-hardware.org/?probe=9b9931bd50) | Sep 29, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [074ab86d60](https://linux-hardware.org/?probe=074ab86d60) | Sep 29, 2023 |
| ASUSTek       | STRIX Z270E GAMING          | Desktop     | [caa5ce0b99](https://linux-hardware.org/?probe=caa5ce0b99) | Sep 29, 2023 |
| HP            | ENVY TS Sleekbook 4         | Notebook    | [545098d0d2](https://linux-hardware.org/?probe=545098d0d2) | Sep 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [4a6090c2f4](https://linux-hardware.org/?probe=4a6090c2f4) | Sep 29, 2023 |
| ASUSTek       | A5401WRP                    | All in one  | [354c1dc0ba](https://linux-hardware.org/?probe=354c1dc0ba) | Sep 29, 2023 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [17bb772d78](https://linux-hardware.org/?probe=17bb772d78) | Sep 29, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20UGA... | Notebook    | [c38ca27643](https://linux-hardware.org/?probe=c38ca27643) | Sep 29, 2023 |
| 3Logic Gro... | DMB-H510-MCA01              | Desktop     | [7cc521d927](https://linux-hardware.org/?probe=7cc521d927) | Sep 29, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [e51fd2a8e9](https://linux-hardware.org/?probe=e51fd2a8e9) | Sep 29, 2023 |
| 3Logic Gro... | DMB-H510-MCA01              | Desktop     | [b952cdd71d](https://linux-hardware.org/?probe=b952cdd71d) | Sep 29, 2023 |
| Intel         | NUC13ANBi5 M89647-202       | Mini pc     | [e1f22fdce4](https://linux-hardware.org/?probe=e1f22fdce4) | Sep 29, 2023 |
| Acer          | H57M01                      | Desktop     | [ad7b1bf379](https://linux-hardware.org/?probe=ad7b1bf379) | Sep 29, 2023 |
| Lenovo        | 1038 NO DPK                 | Server      | [d74284aa9f](https://linux-hardware.org/?probe=d74284aa9f) | Sep 29, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [cd9628c344](https://linux-hardware.org/?probe=cd9628c344) | Sep 29, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [b34539564f](https://linux-hardware.org/?probe=b34539564f) | Sep 29, 2023 |
| ASRock        | B550M Phantom Gaming 4      | Desktop     | [e0158c541c](https://linux-hardware.org/?probe=e0158c541c) | Sep 29, 2023 |
| Acer          | Nitro N50-610               | Desktop     | [a91f602e4a](https://linux-hardware.org/?probe=a91f602e4a) | Sep 29, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [96e037afc8](https://linux-hardware.org/?probe=96e037afc8) | Sep 29, 2023 |
| eMachines     | eME732Z                     | Notebook    | [ba03824830](https://linux-hardware.org/?probe=ba03824830) | Sep 29, 2023 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [4b5a46a1e2](https://linux-hardware.org/?probe=4b5a46a1e2) | Sep 29, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [b77b45ce58](https://linux-hardware.org/?probe=b77b45ce58) | Sep 29, 2023 |
| Intel         | D33217CK G76541-302         | Desktop     | [d1aab6a8d0](https://linux-hardware.org/?probe=d1aab6a8d0) | Sep 29, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [3473652871](https://linux-hardware.org/?probe=3473652871) | Sep 29, 2023 |
| Dell          | 0804P1 A02                  | Server      | [96b1e41f9c](https://linux-hardware.org/?probe=96b1e41f9c) | Sep 29, 2023 |
| OEGStone      | C4100/C5100                 | Notebook    | [0c27e50b14](https://linux-hardware.org/?probe=0c27e50b14) | Sep 29, 2023 |
| ASUSTek       | T102HA                      | Tablet      | [eb48f40a27](https://linux-hardware.org/?probe=eb48f40a27) | Sep 29, 2023 |
| Lenovo        | IdeaPad Pro 5 16APH8 83A... | Notebook    | [ee6e1996b9](https://linux-hardware.org/?probe=ee6e1996b9) | Sep 29, 2023 |
| Supermicro    | X8DAH                       | Server      | [fdf4a783aa](https://linux-hardware.org/?probe=fdf4a783aa) | Sep 29, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [7b4a0099a9](https://linux-hardware.org/?probe=7b4a0099a9) | Sep 29, 2023 |
| ASRock        | Z490 Phantom Gaming 4       | Desktop     | [6fc3fe7a63](https://linux-hardware.org/?probe=6fc3fe7a63) | Sep 29, 2023 |
| Acer          | Aspire A517-53              | Notebook    | [6023cecfb1](https://linux-hardware.org/?probe=6023cecfb1) | Sep 29, 2023 |
| Acer          | Veriton Z4820G              | All in one  | [5db8dac17e](https://linux-hardware.org/?probe=5db8dac17e) | Sep 29, 2023 |
| HP            | ProBook 450 G1              | Notebook    | [1cbae5b56a](https://linux-hardware.org/?probe=1cbae5b56a) | Sep 29, 2023 |
| HP            | ProLiant DL380p Gen8        | Server      | [9c52136f33](https://linux-hardware.org/?probe=9c52136f33) | Sep 29, 2023 |
| Acer          | Aspire 7745G                | Notebook    | [55ea55a771](https://linux-hardware.org/?probe=55ea55a771) | Sep 29, 2023 |
| ASRock        | H81M-HG4                    | Desktop     | [7f2a420ea3](https://linux-hardware.org/?probe=7f2a420ea3) | Sep 29, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [3e1448c388](https://linux-hardware.org/?probe=3e1448c388) | Sep 29, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [f94587a692](https://linux-hardware.org/?probe=f94587a692) | Sep 29, 2023 |
| Acer          | Aspire A517-53              | Notebook    | [05ff23a1a1](https://linux-hardware.org/?probe=05ff23a1a1) | Sep 29, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [9c2ba935b9](https://linux-hardware.org/?probe=9c2ba935b9) | Sep 29, 2023 |
| Dell          | Latitude 5500               | Notebook    | [ea091dbcf2](https://linux-hardware.org/?probe=ea091dbcf2) | Sep 29, 2023 |
| Lenovo        | ThinkPad X260 20F5S2WY00    | Notebook    | [6a18fb9b21](https://linux-hardware.org/?probe=6a18fb9b21) | Sep 29, 2023 |
| Dell          | 0PRR48 A00                  | Desktop     | [52fd06666a](https://linux-hardware.org/?probe=52fd06666a) | Sep 29, 2023 |
| Lenovo        | G70-70 80HW                 | Notebook    | [4e22db020f](https://linux-hardware.org/?probe=4e22db020f) | Sep 29, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [c7f7de0a3a](https://linux-hardware.org/?probe=c7f7de0a3a) | Sep 29, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [380afb179f](https://linux-hardware.org/?probe=380afb179f) | Sep 29, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [002155539d](https://linux-hardware.org/?probe=002155539d) | Sep 29, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [1395f33f33](https://linux-hardware.org/?probe=1395f33f33) | Sep 29, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [1dc72cc274](https://linux-hardware.org/?probe=1dc72cc274) | Sep 29, 2023 |
| F-PLUS EQU... | FNB-156-P1                  | Notebook    | [cceaaac2d3](https://linux-hardware.org/?probe=cceaaac2d3) | Sep 29, 2023 |
| Intel         | B75                         | Desktop     | [a30fa8031b](https://linux-hardware.org/?probe=a30fa8031b) | Sep 29, 2023 |
| MSI           | B560M PRO                   | Desktop     | [1dc06a927c](https://linux-hardware.org/?probe=1dc06a927c) | Sep 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [6348992a72](https://linux-hardware.org/?probe=6348992a72) | Sep 29, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [7975260826](https://linux-hardware.org/?probe=7975260826) | Sep 29, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [d958b4e16a](https://linux-hardware.org/?probe=d958b4e16a) | Sep 29, 2023 |
| Shenzhen M... | F7BAA                       | Desktop     | [30268d41d2](https://linux-hardware.org/?probe=30268d41d2) | Sep 29, 2023 |
| Dell          | 0J3C2F A00                  | Desktop     | [0536b81a43](https://linux-hardware.org/?probe=0536b81a43) | Sep 29, 2023 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [08fb652352](https://linux-hardware.org/?probe=08fb652352) | Sep 29, 2023 |
| HP            | EliteBook 745 G5            | Notebook    | [b734ec49e2](https://linux-hardware.org/?probe=b734ec49e2) | Sep 29, 2023 |
| MSI           | Z68A-GD65                   | Desktop     | [c0f968740b](https://linux-hardware.org/?probe=c0f968740b) | Sep 29, 2023 |
| MSI           | H97 GAMING 3                | Desktop     | [51f3cd7354](https://linux-hardware.org/?probe=51f3cd7354) | Sep 29, 2023 |
| Dell          | Latitude 7490               | Notebook    | [a22e4e9304](https://linux-hardware.org/?probe=a22e4e9304) | Sep 29, 2023 |
| Dell          | Latitude 5430               | Notebook    | [583aa8cf02](https://linux-hardware.org/?probe=583aa8cf02) | Sep 29, 2023 |
| Intel         | SharkBay Platform           | Notebook    | [2406bf1c0d](https://linux-hardware.org/?probe=2406bf1c0d) | Sep 29, 2023 |
| Dell          | Latitude E6540              | Notebook    | [1478e1265d](https://linux-hardware.org/?probe=1478e1265d) | Sep 29, 2023 |
| Dell          | Latitude E6530              | Notebook    | [5fc5673815](https://linux-hardware.org/?probe=5fc5673815) | Sep 29, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [2d31a3d858](https://linux-hardware.org/?probe=2d31a3d858) | Sep 29, 2023 |
| ASUSTek       | K55VJ                       | Notebook    | [4befa6db63](https://linux-hardware.org/?probe=4befa6db63) | Sep 29, 2023 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [c602f8fba9](https://linux-hardware.org/?probe=c602f8fba9) | Sep 29, 2023 |
| Supermicro    | X9DRW                       | Server      | [122a3dfb58](https://linux-hardware.org/?probe=122a3dfb58) | Sep 29, 2023 |
| Supermicro    | X9DRW                       | Server      | [4d0fad3a9e](https://linux-hardware.org/?probe=4d0fad3a9e) | Sep 29, 2023 |
| Getac         | T800G2                      | Tablet      | [ede8155598](https://linux-hardware.org/?probe=ede8155598) | Sep 29, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [6177caee37](https://linux-hardware.org/?probe=6177caee37) | Sep 29, 2023 |
| Dell          | 0WWR83 A05                  | Server      | [8df85e28d8](https://linux-hardware.org/?probe=8df85e28d8) | Sep 29, 2023 |
| HP            | 1790                        | Desktop     | [b87e9dd9ad](https://linux-hardware.org/?probe=b87e9dd9ad) | Sep 29, 2023 |
| HP            | 1790                        | Desktop     | [89791e7bf0](https://linux-hardware.org/?probe=89791e7bf0) | Sep 29, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [f79a27e406](https://linux-hardware.org/?probe=f79a27e406) | Sep 29, 2023 |
| Alienware     | m16 R1 AMD                  | Notebook    | [710a10efce](https://linux-hardware.org/?probe=710a10efce) | Sep 29, 2023 |
| HP            | ProBook 430 G3              | Notebook    | [5a73271bfd](https://linux-hardware.org/?probe=5a73271bfd) | Sep 29, 2023 |
| HP            | ZBook Studio G5             | Notebook    | [239b5a3fd5](https://linux-hardware.org/?probe=239b5a3fd5) | Sep 29, 2023 |
| HP            | 3398                        | Desktop     | [13aa132a7d](https://linux-hardware.org/?probe=13aa132a7d) | Sep 29, 2023 |
| Alienware     | x15 R1                      | Notebook    | [a34b343fce](https://linux-hardware.org/?probe=a34b343fce) | Sep 29, 2023 |
| Positivo      | C14CR01                     | Notebook    | [11b171838d](https://linux-hardware.org/?probe=11b171838d) | Sep 29, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [725f1e5b25](https://linux-hardware.org/?probe=725f1e5b25) | Sep 29, 2023 |
| SKIKK         | Sindri 14                   | Notebook    | [9766c80aa9](https://linux-hardware.org/?probe=9766c80aa9) | Sep 29, 2023 |
| MSI           | MAG B550M MORTAR            | Desktop     | [ed0e5eee5a](https://linux-hardware.org/?probe=ed0e5eee5a) | Sep 29, 2023 |
| ANGXUN        | X99-DM3 V3.0                | Desktop     | [1a7ed0ba7d](https://linux-hardware.org/?probe=1a7ed0ba7d) | Sep 29, 2023 |
| Gigabyte      | H97-D3H-CF                  | Desktop     | [c0c34400ad](https://linux-hardware.org/?probe=c0c34400ad) | Sep 29, 2023 |
| Dell          | Precision 5480              | Notebook    | [5d157102ea](https://linux-hardware.org/?probe=5d157102ea) | Sep 29, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [6275e5c1d4](https://linux-hardware.org/?probe=6275e5c1d4) | Sep 29, 2023 |
| GEEKOM        | Mini IT 8                   | Desktop     | [fc5d6092da](https://linux-hardware.org/?probe=fc5d6092da) | Sep 29, 2023 |
| Timi          | Xiaomi Book Pro 16 2022     | Notebook    | [7392f9db3b](https://linux-hardware.org/?probe=7392f9db3b) | Sep 29, 2023 |
| Unknown       | TB-5000                     | Desktop     | [9c67baa34f](https://linux-hardware.org/?probe=9c67baa34f) | Sep 29, 2023 |
| Valve         | Jupiter                     | Notebook    | [d065544135](https://linux-hardware.org/?probe=d065544135) | Sep 29, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [16dabb2f6e](https://linux-hardware.org/?probe=16dabb2f6e) | Sep 29, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [55b44bb456](https://linux-hardware.org/?probe=55b44bb456) | Sep 29, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [d0fea1d86b](https://linux-hardware.org/?probe=d0fea1d86b) | Sep 29, 2023 |
| WesternDig... | BBC 0001                    | Desktop     | [b31e10d01b](https://linux-hardware.org/?probe=b31e10d01b) | Sep 29, 2023 |
| MSI           | Prestige 15 A12SC           | Notebook    | [d78d241946](https://linux-hardware.org/?probe=d78d241946) | Sep 29, 2023 |
| WesternDig... | BBC 0001                    | Desktop     | [ba340393f7](https://linux-hardware.org/?probe=ba340393f7) | Sep 29, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [b7faf1054b](https://linux-hardware.org/?probe=b7faf1054b) | Sep 29, 2023 |
| Acer          | Swift SF114-34              | Notebook    | [9d618e345a](https://linux-hardware.org/?probe=9d618e345a) | Sep 29, 2023 |
| MSI           | B560M PRO                   | Desktop     | [ce2f5b7349](https://linux-hardware.org/?probe=ce2f5b7349) | Sep 29, 2023 |
| HP            | 198E                        | Desktop     | [a311728a5f](https://linux-hardware.org/?probe=a311728a5f) | Sep 29, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [e6d8dfa4a1](https://linux-hardware.org/?probe=e6d8dfa4a1) | Sep 29, 2023 |
| HP            | Pavilion dv9000 (GA359UA... | Notebook    | [cea70d5f75](https://linux-hardware.org/?probe=cea70d5f75) | Sep 29, 2023 |
| Lenovo        | ThinkPad T480s 20L8002WM... | Notebook    | [eef8975f1e](https://linux-hardware.org/?probe=eef8975f1e) | Sep 29, 2023 |
| ASUSTek       | ROG STRIX Z790-A GAMING ... | Desktop     | [a5467c367d](https://linux-hardware.org/?probe=a5467c367d) | Sep 29, 2023 |
| Supermicro    | X11DDW-NT                   | Server      | [c7b049f922](https://linux-hardware.org/?probe=c7b049f922) | Sep 29, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [8724efb686](https://linux-hardware.org/?probe=8724efb686) | Sep 29, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [76fc0d8239](https://linux-hardware.org/?probe=76fc0d8239) | Sep 29, 2023 |
| Dell          | Latitude E5450              | Notebook    | [0b77908612](https://linux-hardware.org/?probe=0b77908612) | Sep 29, 2023 |
| System76      | Darter Pro                  | Notebook    | [d8b78103d5](https://linux-hardware.org/?probe=d8b78103d5) | Sep 29, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [0e4e90fac1](https://linux-hardware.org/?probe=0e4e90fac1) | Sep 29, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [7c8b825512](https://linux-hardware.org/?probe=7c8b825512) | Sep 29, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [4aa521a31f](https://linux-hardware.org/?probe=4aa521a31f) | Sep 29, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [b9f67caef4](https://linux-hardware.org/?probe=b9f67caef4) | Sep 29, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [6f07d7c834](https://linux-hardware.org/?probe=6f07d7c834) | Sep 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [5828bffdb6](https://linux-hardware.org/?probe=5828bffdb6) | Sep 29, 2023 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [c822d38335](https://linux-hardware.org/?probe=c822d38335) | Sep 29, 2023 |
| Valve         | Jupiter                     | Notebook    | [c881d3edc2](https://linux-hardware.org/?probe=c881d3edc2) | Sep 29, 2023 |
| Dell          | Inspiron 15-3552            | Notebook    | [8a8f11edae](https://linux-hardware.org/?probe=8a8f11edae) | Sep 29, 2023 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [52648b0b45](https://linux-hardware.org/?probe=52648b0b45) | Sep 29, 2023 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [222c45e72e](https://linux-hardware.org/?probe=222c45e72e) | Sep 29, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [e57cdefe7a](https://linux-hardware.org/?probe=e57cdefe7a) | Sep 29, 2023 |
| Valve         | Jupiter                     | Notebook    | [2f4eb9f823](https://linux-hardware.org/?probe=2f4eb9f823) | Sep 29, 2023 |
| Dell          | Inspiron 7548               | Notebook    | [2c407b4ff5](https://linux-hardware.org/?probe=2c407b4ff5) | Sep 29, 2023 |
| HP            | Stream x360 Convertible ... | Convertible | [427ea0aa4f](https://linux-hardware.org/?probe=427ea0aa4f) | Sep 29, 2023 |
| Dell          | Precision 7710              | Notebook    | [89731f9b0e](https://linux-hardware.org/?probe=89731f9b0e) | Sep 29, 2023 |
| TUXEDO        | Stellaris Intel Gen5        | Notebook    | [6d981e4890](https://linux-hardware.org/?probe=6d981e4890) | Sep 29, 2023 |
| Intel         | H110D4-P1                   | Desktop     | [ccedaaab02](https://linux-hardware.org/?probe=ccedaaab02) | Sep 29, 2023 |
| ASRock        | H510M-HVS R2.0              | Desktop     | [f50b0e51d3](https://linux-hardware.org/?probe=f50b0e51d3) | Sep 29, 2023 |
| Dell          | 03015M A10                  | Server      | [1c089bce6b](https://linux-hardware.org/?probe=1c089bce6b) | Sep 29, 2023 |
| Lenovo        | ThinkPad Yoga 460 20ELS0... | Convertible | [29617a5db5](https://linux-hardware.org/?probe=29617a5db5) | Sep 29, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | Notebook    | [fb1c2503cf](https://linux-hardware.org/?probe=fb1c2503cf) | Sep 29, 2023 |
| Foxconn       | 2ADA                        | Desktop     | [0c29af254c](https://linux-hardware.org/?probe=0c29af254c) | Sep 29, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [2a3e49f18f](https://linux-hardware.org/?probe=2a3e49f18f) | Sep 29, 2023 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [902918fb1d](https://linux-hardware.org/?probe=902918fb1d) | Sep 29, 2023 |
| HP            | EliteBook 2760p             | Notebook    | [e9d026d0df](https://linux-hardware.org/?probe=e9d026d0df) | Sep 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [772e866a05](https://linux-hardware.org/?probe=772e866a05) | Sep 29, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [6d725a3ede](https://linux-hardware.org/?probe=6d725a3ede) | Sep 29, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [109490039d](https://linux-hardware.org/?probe=109490039d) | Sep 29, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [2c2f49b6bf](https://linux-hardware.org/?probe=2c2f49b6bf) | Sep 29, 2023 |
| Lenovo        | ThinkPad E495 20NE0001US    | Notebook    | [a76a94cd2f](https://linux-hardware.org/?probe=a76a94cd2f) | Sep 29, 2023 |
| Lenovo        | ThinkPad X200 745536T       | Notebook    | [618cd9dd90](https://linux-hardware.org/?probe=618cd9dd90) | Sep 29, 2023 |
| Supermicro    | X11DPG-QTA                  | Server      | [80db5bcb0e](https://linux-hardware.org/?probe=80db5bcb0e) | Sep 29, 2023 |
| Dell          | Inspiron 5437               | Notebook    | [c0301c2fbb](https://linux-hardware.org/?probe=c0301c2fbb) | Sep 29, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [713d59f3d0](https://linux-hardware.org/?probe=713d59f3d0) | Sep 29, 2023 |
| HP            | 1589                        | Desktop     | [c42e75cdd8](https://linux-hardware.org/?probe=c42e75cdd8) | Sep 29, 2023 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [6f19668c91](https://linux-hardware.org/?probe=6f19668c91) | Sep 29, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [c434f30a15](https://linux-hardware.org/?probe=c434f30a15) | Sep 29, 2023 |
| Lenovo        | 1031 SBB0J05441 WIN 3305... | Desktop     | [26580dc672](https://linux-hardware.org/?probe=26580dc672) | Sep 29, 2023 |
| Valve         | Jupiter                     | Notebook    | [937f10463d](https://linux-hardware.org/?probe=937f10463d) | Sep 29, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | Notebook    | [ba269d8c4a](https://linux-hardware.org/?probe=ba269d8c4a) | Sep 29, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [9b86a89bf4](https://linux-hardware.org/?probe=9b86a89bf4) | Sep 29, 2023 |
| Casper        | NIRVANA N240                | Notebook    | [fa2c4e6569](https://linux-hardware.org/?probe=fa2c4e6569) | Sep 29, 2023 |
| Radxa         | ROCK Pi 4B                  | Soc         | [fac4bb4863](https://linux-hardware.org/?probe=fac4bb4863) | Sep 29, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [e87fdc15ed](https://linux-hardware.org/?probe=e87fdc15ed) | Sep 29, 2023 |
| Pegatron      | Benicia                     | Desktop     | [840b02e356](https://linux-hardware.org/?probe=840b02e356) | Sep 29, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [96fa5ddfa8](https://linux-hardware.org/?probe=96fa5ddfa8) | Sep 29, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [b1333a2976](https://linux-hardware.org/?probe=b1333a2976) | Sep 29, 2023 |
| Lenovo        | G70-70 80HW                 | Notebook    | [5ef0f97836](https://linux-hardware.org/?probe=5ef0f97836) | Sep 29, 2023 |
| HP            | Stream Laptop 14-ds0xxx     | Notebook    | [bbab7c9f89](https://linux-hardware.org/?probe=bbab7c9f89) | Sep 29, 2023 |
| Dell          | Latitude 5410               | Notebook    | [61ddf0adf6](https://linux-hardware.org/?probe=61ddf0adf6) | Sep 29, 2023 |
| Packard Be... | EasyNote TK36               | Notebook    | [1e8f79c726](https://linux-hardware.org/?probe=1e8f79c726) | Sep 29, 2023 |
| HP            | Stream Laptop 14-ds0xxx     | Notebook    | [4f23a67b82](https://linux-hardware.org/?probe=4f23a67b82) | Sep 29, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [60c04875f1](https://linux-hardware.org/?probe=60c04875f1) | Sep 29, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [0e12b69b96](https://linux-hardware.org/?probe=0e12b69b96) | Sep 29, 2023 |
| ASUSTek       | EB1501P                     | Desktop     | [df48fa7e96](https://linux-hardware.org/?probe=df48fa7e96) | Sep 29, 2023 |
| Positivo      | POS-PIH81DI                 | Desktop     | [0e67f3a0f3](https://linux-hardware.org/?probe=0e67f3a0f3) | Sep 29, 2023 |
| Acer          | Nitro AN515-43              | Notebook    | [e55a394d41](https://linux-hardware.org/?probe=e55a394d41) | Sep 29, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [cce7c03059](https://linux-hardware.org/?probe=cce7c03059) | Sep 29, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [960cd34617](https://linux-hardware.org/?probe=960cd34617) | Sep 29, 2023 |
| HP            | EliteBook x360 1040 G6      | Convertible | [76c2234d3e](https://linux-hardware.org/?probe=76c2234d3e) | Sep 29, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [74ec125e88](https://linux-hardware.org/?probe=74ec125e88) | Sep 29, 2023 |
| Lenovo        | ThinkPad W541 20EGS24J00    | Notebook    | [99fb3ec5e9](https://linux-hardware.org/?probe=99fb3ec5e9) | Sep 29, 2023 |
| HP            | EliteBook x360 1040 G6      | Convertible | [6bb37fb224](https://linux-hardware.org/?probe=6bb37fb224) | Sep 29, 2023 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [d95e370c54](https://linux-hardware.org/?probe=d95e370c54) | Sep 29, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [b6d98e8f23](https://linux-hardware.org/?probe=b6d98e8f23) | Sep 29, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [448463ac0a](https://linux-hardware.org/?probe=448463ac0a) | Sep 29, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [b4fa4a9cff](https://linux-hardware.org/?probe=b4fa4a9cff) | Sep 29, 2023 |
| Lenovo        | ThinkPad T500 22439AG       | Notebook    | [e5a2cd9816](https://linux-hardware.org/?probe=e5a2cd9816) | Sep 29, 2023 |
| ETegro Tec... | ETRS125G4 31S2MMB0040       | Server      | [68bb1e4021](https://linux-hardware.org/?probe=68bb1e4021) | Sep 29, 2023 |
| Supermicro    | X9DRW                       | Server      | [21757c8129](https://linux-hardware.org/?probe=21757c8129) | Sep 29, 2023 |
| Supermicro    | X9DRW                       | Server      | [e60890ee3e](https://linux-hardware.org/?probe=e60890ee3e) | Sep 29, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [ccc715eeb6](https://linux-hardware.org/?probe=ccc715eeb6) | Sep 29, 2023 |
| Lenovo        | ThinkPad T420s 4174PEG      | Notebook    | [cf650bb4af](https://linux-hardware.org/?probe=cf650bb4af) | Sep 29, 2023 |
| ASUSTek       | P8H61-MX USB3               | Desktop     | [5d1175b3f3](https://linux-hardware.org/?probe=5d1175b3f3) | Sep 28, 2023 |
| HP            | EliteBook x360 1040 G6      | Convertible | [50e5cd4da6](https://linux-hardware.org/?probe=50e5cd4da6) | Sep 28, 2023 |
| ASUSTek       | H81M-E                      | Desktop     | [0137140cae](https://linux-hardware.org/?probe=0137140cae) | Sep 28, 2023 |
| Google        | Lindar                      | Notebook    | [f8f947a025](https://linux-hardware.org/?probe=f8f947a025) | Sep 28, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [cc8c6efba3](https://linux-hardware.org/?probe=cc8c6efba3) | Sep 28, 2023 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [da030ed703](https://linux-hardware.org/?probe=da030ed703) | Sep 28, 2023 |
| Toshiba       | Satellite P50-B-117         | Notebook    | [cecfba4e8f](https://linux-hardware.org/?probe=cecfba4e8f) | Sep 28, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [5c38fe5e79](https://linux-hardware.org/?probe=5c38fe5e79) | Sep 28, 2023 |
| Google        | Lindar                      | Notebook    | [9ddbc21f0d](https://linux-hardware.org/?probe=9ddbc21f0d) | Sep 28, 2023 |
| ASUSTek       | K72Jr                       | Notebook    | [9167494336](https://linux-hardware.org/?probe=9167494336) | Sep 28, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [0177e96165](https://linux-hardware.org/?probe=0177e96165) | Sep 28, 2023 |
| ASUSTek       | X505BA                      | Notebook    | [1caa3c5c7e](https://linux-hardware.org/?probe=1caa3c5c7e) | Sep 28, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [6bce0e41d9](https://linux-hardware.org/?probe=6bce0e41d9) | Sep 28, 2023 |
| MSI           | H97M-G43                    | Desktop     | [b74346acb3](https://linux-hardware.org/?probe=b74346acb3) | Sep 28, 2023 |
| Lenovo        | IdeaPad Y530                | Notebook    | [83a6d1b19b](https://linux-hardware.org/?probe=83a6d1b19b) | Sep 28, 2023 |
| Gigabyte      | B150M-D3V-CF                | Desktop     | [75b228c5fb](https://linux-hardware.org/?probe=75b228c5fb) | Sep 28, 2023 |
| Dell          | 0J3C2F A00                  | Desktop     | [451d8ac4ca](https://linux-hardware.org/?probe=451d8ac4ca) | Sep 28, 2023 |
| Valve         | Jupiter                     | Notebook    | [acc0ad7283](https://linux-hardware.org/?probe=acc0ad7283) | Sep 28, 2023 |
| HP            | 8619                        | Desktop     | [d631850d2f](https://linux-hardware.org/?probe=d631850d2f) | Sep 28, 2023 |
| Pegatron      | JESSE                       | Desktop     | [3f6cf71237](https://linux-hardware.org/?probe=3f6cf71237) | Sep 28, 2023 |
| Dell          | Latitude E6420              | Notebook    | [935d96843b](https://linux-hardware.org/?probe=935d96843b) | Sep 28, 2023 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [c608038795](https://linux-hardware.org/?probe=c608038795) | Sep 28, 2023 |
| MSI           | B450M BAZOOKA V2            | Desktop     | [c815d636ce](https://linux-hardware.org/?probe=c815d636ce) | Sep 28, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [7fb0e4c19c](https://linux-hardware.org/?probe=7fb0e4c19c) | Sep 28, 2023 |
| ETegro Tec... | ETRS125G4 31S2MMB0040       | Server      | [3191feb756](https://linux-hardware.org/?probe=3191feb756) | Sep 28, 2023 |
| HP            | 8923 00100                  | All in one  | [31d524cec8](https://linux-hardware.org/?probe=31d524cec8) | Sep 28, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [8f35ffb248](https://linux-hardware.org/?probe=8f35ffb248) | Sep 28, 2023 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | Desktop     | [0577874fd5](https://linux-hardware.org/?probe=0577874fd5) | Sep 28, 2023 |
| HP            | ZBook Studio G3             | Notebook    | [0005d20c0d](https://linux-hardware.org/?probe=0005d20c0d) | Sep 28, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [c93318bf50](https://linux-hardware.org/?probe=c93318bf50) | Sep 28, 2023 |
| Dell          | 0YJPT1 A00                  | Desktop     | [a0a41d401e](https://linux-hardware.org/?probe=a0a41d401e) | Sep 28, 2023 |
| Dell          | 0H19HD A01                  | Server      | [fb5fb07ca9](https://linux-hardware.org/?probe=fb5fb07ca9) | Sep 28, 2023 |
| MSI           | H310M PRO-VD                | Desktop     | [67e14c1b2d](https://linux-hardware.org/?probe=67e14c1b2d) | Sep 28, 2023 |
| HP            | 3397                        | Desktop     | [5c1b3bed0b](https://linux-hardware.org/?probe=5c1b3bed0b) | Sep 28, 2023 |
| Dell          | 0H19HD A01                  | Server      | [643dd60247](https://linux-hardware.org/?probe=643dd60247) | Sep 28, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [a40dc4964e](https://linux-hardware.org/?probe=a40dc4964e) | Sep 28, 2023 |
| HP            | 0AA8h                       | Desktop     | [7c8c8fbb40](https://linux-hardware.org/?probe=7c8c8fbb40) | Sep 28, 2023 |
| Google        | Swanky                      | Notebook    | [599959ccbe](https://linux-hardware.org/?probe=599959ccbe) | Sep 28, 2023 |
| ASUSTek       | P7P55 LX                    | Desktop     | [6e4c4376c5](https://linux-hardware.org/?probe=6e4c4376c5) | Sep 28, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [27d7959e57](https://linux-hardware.org/?probe=27d7959e57) | Sep 28, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | Notebook    | [e23bfd302c](https://linux-hardware.org/?probe=e23bfd302c) | Sep 28, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 14ACN... | Notebook    | [a5e7296c29](https://linux-hardware.org/?probe=a5e7296c29) | Sep 28, 2023 |
| AZW           | SER V1                      | Desktop     | [10660522cb](https://linux-hardware.org/?probe=10660522cb) | Sep 28, 2023 |
| Biostar       | B450MH                      | Desktop     | [e932e22b99](https://linux-hardware.org/?probe=e932e22b99) | Sep 28, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [cb2cbda84d](https://linux-hardware.org/?probe=cb2cbda84d) | Sep 28, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [1d749b29ad](https://linux-hardware.org/?probe=1d749b29ad) | Sep 28, 2023 |
| Gigabyte      | B360M DS3H                  | Desktop     | [1308430981](https://linux-hardware.org/?probe=1308430981) | Sep 28, 2023 |
| Lenovo        | H410                        | Desktop     | [f49a6ce32f](https://linux-hardware.org/?probe=f49a6ce32f) | Sep 28, 2023 |
| Acer          | Aspire 7745G                | Notebook    | [6def421696](https://linux-hardware.org/?probe=6def421696) | Sep 28, 2023 |
| Lenovo        | ThinkPad E490 20N8000SRT    | Notebook    | [274b3b5210](https://linux-hardware.org/?probe=274b3b5210) | Sep 28, 2023 |
| ASUSTek       | Z97-A-USB31                 | Desktop     | [b7e5fb069c](https://linux-hardware.org/?probe=b7e5fb069c) | Sep 28, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [0a51882a60](https://linux-hardware.org/?probe=0a51882a60) | Sep 28, 2023 |
| HP            | ENVY 17                     | Notebook    | [184a826bba](https://linux-hardware.org/?probe=184a826bba) | Sep 28, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [cf0c9cc177](https://linux-hardware.org/?probe=cf0c9cc177) | Sep 28, 2023 |
| Acer          | Aspire E1-570G              | Notebook    | [17584cef15](https://linux-hardware.org/?probe=17584cef15) | Sep 28, 2023 |
| ETegro Tec... | ETRS125G4 31S2MMB0040       | Server      | [a14ff14954](https://linux-hardware.org/?probe=a14ff14954) | Sep 28, 2023 |
| ETegro Tec... | ETRS125G4 31S2MMB0040       | Server      | [cb9984cefb](https://linux-hardware.org/?probe=cb9984cefb) | Sep 28, 2023 |
| ETegro Tec... | ETRS125G4 31S2MMB0040       | Server      | [1cca0d5263](https://linux-hardware.org/?probe=1cca0d5263) | Sep 28, 2023 |
| ETegro Tec... | ETRS125G4 31S2MMB0040       | Server      | [6732e637aa](https://linux-hardware.org/?probe=6732e637aa) | Sep 28, 2023 |
| ETegro Tec... | ETRS125G4 31S2MMB0040       | Server      | [06e76c2108](https://linux-hardware.org/?probe=06e76c2108) | Sep 28, 2023 |
| ETegro Tec... | ETRS125G4 31S2MMB0040       | Server      | [ce41069e7d](https://linux-hardware.org/?probe=ce41069e7d) | Sep 28, 2023 |
| ETegro Tec... | ETRS125G4 31S2MMB0040       | Server      | [d431883e15](https://linux-hardware.org/?probe=d431883e15) | Sep 28, 2023 |
| I-Life Dig... | ZED AIR PRO                 | Notebook    | [7cb30879f6](https://linux-hardware.org/?probe=7cb30879f6) | Sep 28, 2023 |
| Lenovo        | ThinkPad X260 20F60097US    | Notebook    | [607d788fde](https://linux-hardware.org/?probe=607d788fde) | Sep 28, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [96ee1b2b2a](https://linux-hardware.org/?probe=96ee1b2b2a) | Sep 28, 2023 |
| Lenovo        | ThinkPad R60 9461DXG        | Notebook    | [4f74530d68](https://linux-hardware.org/?probe=4f74530d68) | Sep 28, 2023 |
| ETegro Tec... | ETRS125G4 31S2MMB0040       | Server      | [ac05e8b898](https://linux-hardware.org/?probe=ac05e8b898) | Sep 28, 2023 |
| ETegro Tec... | ETRS125G4 31S2MMB0040       | Server      | [eb9e748181](https://linux-hardware.org/?probe=eb9e748181) | Sep 28, 2023 |
| ETegro Tec... | ETRS125G4 31S2MMB0040       | Server      | [1d6887b5f3](https://linux-hardware.org/?probe=1d6887b5f3) | Sep 28, 2023 |
| ASUSTek       | M2N-E SLI                   | Desktop     | [2a5937c5e5](https://linux-hardware.org/?probe=2a5937c5e5) | Sep 28, 2023 |
| Lenovo        | ThinkPad R60 9461DXG        | Notebook    | [5fb1e549ea](https://linux-hardware.org/?probe=5fb1e549ea) | Sep 28, 2023 |
| ETegro Tec... | ETRS125G4 31S2MMB0040       | Server      | [4d27130658](https://linux-hardware.org/?probe=4d27130658) | Sep 28, 2023 |
| ETegro Tec... | ETRS125G4 31S2MMB0040       | Server      | [bb562ae3fe](https://linux-hardware.org/?probe=bb562ae3fe) | Sep 28, 2023 |
| ETegro Tec... | ETRS125G4 31S2MMB0040       | Server      | [c27a8913bf](https://linux-hardware.org/?probe=c27a8913bf) | Sep 28, 2023 |
| Radxa         | ROCK Pi 4B                  | Soc         | [1210322d55](https://linux-hardware.org/?probe=1210322d55) | Sep 28, 2023 |
| ETegro Tec... | ETRS125G4 31S2MMB0040       | Server      | [c00c73fa32](https://linux-hardware.org/?probe=c00c73fa32) | Sep 28, 2023 |
| ETegro Tec... | ETRS125G4 31S2MMB0040       | Server      | [abcb83d7b5](https://linux-hardware.org/?probe=abcb83d7b5) | Sep 28, 2023 |
| Dell          | Precision 3560              | Notebook    | [14af02a240](https://linux-hardware.org/?probe=14af02a240) | Sep 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [995b6fba4d](https://linux-hardware.org/?probe=995b6fba4d) | Sep 28, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [76937ddbce](https://linux-hardware.org/?probe=76937ddbce) | Sep 28, 2023 |
| FriendlyEl... | NanoPC-T6                   | Soc         | [36905cc47d](https://linux-hardware.org/?probe=36905cc47d) | Sep 28, 2023 |
| HP            | Pavilion Laptop 14-ce3xx... | Notebook    | [3ecf3ff165](https://linux-hardware.org/?probe=3ecf3ff165) | Sep 28, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [3746a1b69b](https://linux-hardware.org/?probe=3746a1b69b) | Sep 28, 2023 |
| HP            | Pavilion Laptop 14-ce3xx... | Notebook    | [4c8dbd0780](https://linux-hardware.org/?probe=4c8dbd0780) | Sep 28, 2023 |
| Dell          | 0XC7MM A01                  | Desktop     | [9fdfc5a13f](https://linux-hardware.org/?probe=9fdfc5a13f) | Sep 28, 2023 |
| HP            | 240 G8 Notebook PC          | Notebook    | [af9350dd38](https://linux-hardware.org/?probe=af9350dd38) | Sep 28, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [ce357bee14](https://linux-hardware.org/?probe=ce357bee14) | Sep 28, 2023 |
| Lenovo        | NOK                         | Desktop     | [95ba956749](https://linux-hardware.org/?probe=95ba956749) | Sep 28, 2023 |
| ROMBICA       | myBook Eclipse              | Notebook    | [004e1dc4fd](https://linux-hardware.org/?probe=004e1dc4fd) | Sep 28, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [4cef8be854](https://linux-hardware.org/?probe=4cef8be854) | Sep 28, 2023 |
| Lenovo        | IdeaPad Slim 5 14ABR8 82... | Notebook    | [c61d70bcfa](https://linux-hardware.org/?probe=c61d70bcfa) | Sep 28, 2023 |
| MSI           | GL73 8RE                    | Notebook    | [670f7351b5](https://linux-hardware.org/?probe=670f7351b5) | Sep 28, 2023 |
| Supermicro    | X8DTL                       | Server      | [f068e7e4f8](https://linux-hardware.org/?probe=f068e7e4f8) | Sep 28, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | Notebook    | [38e71e4fe9](https://linux-hardware.org/?probe=38e71e4fe9) | Sep 28, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [dcf11408af](https://linux-hardware.org/?probe=dcf11408af) | Sep 28, 2023 |
| Lenovo        | IdeaPad Slim 5 16ABR8 82... | Notebook    | [1fcc841148](https://linux-hardware.org/?probe=1fcc841148) | Sep 28, 2023 |
| HP            | 843C                        | Desktop     | [4af4a9e798](https://linux-hardware.org/?probe=4af4a9e798) | Sep 28, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [39fd38bc98](https://linux-hardware.org/?probe=39fd38bc98) | Sep 28, 2023 |
| Gigabyte      | EX58-EXTREME                | Desktop     | [4a1a75d0e3](https://linux-hardware.org/?probe=4a1a75d0e3) | Sep 28, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [1492e2178d](https://linux-hardware.org/?probe=1492e2178d) | Sep 28, 2023 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [51272b2713](https://linux-hardware.org/?probe=51272b2713) | Sep 28, 2023 |
| HP            | Laptop 15-fd0xxx            | Notebook    | [0a548c4390](https://linux-hardware.org/?probe=0a548c4390) | Sep 28, 2023 |
| GMKtec        | NucBox3                     | Desktop     | [c99750febd](https://linux-hardware.org/?probe=c99750febd) | Sep 28, 2023 |
| Lenovo        | ThinkPad T510 43142PU       | Notebook    | [30bd29e170](https://linux-hardware.org/?probe=30bd29e170) | Sep 28, 2023 |
| Lenovo        | IdeaPad Slim 5 14ABR8 82... | Notebook    | [be49c167d0](https://linux-hardware.org/?probe=be49c167d0) | Sep 28, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | Notebook    | [f86a0719d7](https://linux-hardware.org/?probe=f86a0719d7) | Sep 28, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81JN     | Notebook    | [747f0d45fe](https://linux-hardware.org/?probe=747f0d45fe) | Sep 28, 2023 |
| ASRock        | A520M Pro4                  | Desktop     | [5a7da2e0de](https://linux-hardware.org/?probe=5a7da2e0de) | Sep 28, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [c8dfaf68d0](https://linux-hardware.org/?probe=c8dfaf68d0) | Sep 28, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [bec979fcd0](https://linux-hardware.org/?probe=bec979fcd0) | Sep 28, 2023 |
| ASUSTek       | UX330CAK                    | Notebook    | [97bb5f9ea1](https://linux-hardware.org/?probe=97bb5f9ea1) | Sep 28, 2023 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [3513d5bcf3](https://linux-hardware.org/?probe=3513d5bcf3) | Sep 28, 2023 |
| F-PLUS EQU... | FNB-156-P1                  | Notebook    | [fb8fd7617c](https://linux-hardware.org/?probe=fb8fd7617c) | Sep 28, 2023 |
| HP            | 2B35                        | Desktop     | [2f63f14724](https://linux-hardware.org/?probe=2f63f14724) | Sep 28, 2023 |
| Gigabyte      | EX58-EXTREME                | Desktop     | [bc2a9ecc6a](https://linux-hardware.org/?probe=bc2a9ecc6a) | Sep 28, 2023 |
| Valve         | Jupiter                     | Notebook    | [39bc0d89fe](https://linux-hardware.org/?probe=39bc0d89fe) | Sep 28, 2023 |
| Valve         | Jupiter                     | Notebook    | [a447ea95b0](https://linux-hardware.org/?probe=a447ea95b0) | Sep 28, 2023 |
| Valve         | Jupiter                     | Notebook    | [b178e71c45](https://linux-hardware.org/?probe=b178e71c45) | Sep 28, 2023 |
| HP            | 1496                        | Desktop     | [3867e7af58](https://linux-hardware.org/?probe=3867e7af58) | Sep 28, 2023 |
| Acer          | Aspire ES1-732              | Notebook    | [f30d62d67b](https://linux-hardware.org/?probe=f30d62d67b) | Sep 28, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [ce3a9f8960](https://linux-hardware.org/?probe=ce3a9f8960) | Sep 28, 2023 |
| ASUSTek       | P8H61-MX USB3               | Desktop     | [31fe0087b8](https://linux-hardware.org/?probe=31fe0087b8) | Sep 28, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [b6316ea4df](https://linux-hardware.org/?probe=b6316ea4df) | Sep 28, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [7cbed3fca6](https://linux-hardware.org/?probe=7cbed3fca6) | Sep 28, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [f75ab187aa](https://linux-hardware.org/?probe=f75ab187aa) | Sep 28, 2023 |
| ASUSTek       | ROG Strix G731GU_GL731GU    | Notebook    | [9e206d1e8b](https://linux-hardware.org/?probe=9e206d1e8b) | Sep 28, 2023 |
| Supermicro    | X8DTU                       | Server      | [d72f782d8c](https://linux-hardware.org/?probe=d72f782d8c) | Sep 28, 2023 |
| Supermicro    | X8DTU                       | Server      | [3d9123e719](https://linux-hardware.org/?probe=3d9123e719) | Sep 28, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [a355202f8a](https://linux-hardware.org/?probe=a355202f8a) | Sep 28, 2023 |
| Packard Be... | DOT S                       | Notebook    | [ccf952e34c](https://linux-hardware.org/?probe=ccf952e34c) | Sep 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [426e8bd9c0](https://linux-hardware.org/?probe=426e8bd9c0) | Sep 28, 2023 |
| Acer          | Aspire 5736Z                | Notebook    | [cfd174dbe0](https://linux-hardware.org/?probe=cfd174dbe0) | Sep 28, 2023 |
| Wistron       | ProLiant ML110 G6           | Desktop     | [4284ef7737](https://linux-hardware.org/?probe=4284ef7737) | Sep 28, 2023 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [7aef46e946](https://linux-hardware.org/?probe=7aef46e946) | Sep 28, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | Desktop     | [62ba806672](https://linux-hardware.org/?probe=62ba806672) | Sep 28, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [3c4c65947a](https://linux-hardware.org/?probe=3c4c65947a) | Sep 28, 2023 |
| Valve         | Jupiter                     | Notebook    | [0948401e7d](https://linux-hardware.org/?probe=0948401e7d) | Sep 28, 2023 |
| ASUSTek       | ROG Strix G731GU_GL731GU    | Notebook    | [8f792e2b5a](https://linux-hardware.org/?probe=8f792e2b5a) | Sep 28, 2023 |
| Lenovo        | ThinkPad X13 Gen 2i 20WK... | Notebook    | [49090587ce](https://linux-hardware.org/?probe=49090587ce) | Sep 28, 2023 |
| HP            | Laptop 15s-fq0xxx           | Notebook    | [4c1a2e1e21](https://linux-hardware.org/?probe=4c1a2e1e21) | Sep 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E3S... | Notebook    | [356b5f053d](https://linux-hardware.org/?probe=356b5f053d) | Sep 28, 2023 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [1509f60079](https://linux-hardware.org/?probe=1509f60079) | Sep 28, 2023 |
| Infinix       | INBOOK X2 GEN11             | Notebook    | [2ac0204275](https://linux-hardware.org/?probe=2ac0204275) | Sep 28, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [0c9b2c687a](https://linux-hardware.org/?probe=0c9b2c687a) | Sep 28, 2023 |
| Wistron       | ProLiant ML110 G6           | Desktop     | [6282804553](https://linux-hardware.org/?probe=6282804553) | Sep 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [78b1c422c7](https://linux-hardware.org/?probe=78b1c422c7) | Sep 28, 2023 |
| Intel         | H61                         | Desktop     | [f41171114f](https://linux-hardware.org/?probe=f41171114f) | Sep 28, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [013801fc61](https://linux-hardware.org/?probe=013801fc61) | Sep 28, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [5b87382fce](https://linux-hardware.org/?probe=5b87382fce) | Sep 28, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [6fc52a277a](https://linux-hardware.org/?probe=6fc52a277a) | Sep 28, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [555dfa4f2e](https://linux-hardware.org/?probe=555dfa4f2e) | Sep 28, 2023 |
| HP            | Compaq Presario CQ70        | Notebook    | [8913bbd459](https://linux-hardware.org/?probe=8913bbd459) | Sep 28, 2023 |
| ICL           | H510SB-TM v2.0              | All in one  | [41193155ed](https://linux-hardware.org/?probe=41193155ed) | Sep 28, 2023 |
| HP            | Notebook                    | Notebook    | [7d55fd8520](https://linux-hardware.org/?probe=7d55fd8520) | Sep 28, 2023 |
| Valve         | Jupiter                     | Notebook    | [8de9bb39df](https://linux-hardware.org/?probe=8de9bb39df) | Sep 28, 2023 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | Notebook    | [64a85b8eb3](https://linux-hardware.org/?probe=64a85b8eb3) | Sep 28, 2023 |
| HP            | ProBook 430 G5              | Notebook    | [9e68b6e2be](https://linux-hardware.org/?probe=9e68b6e2be) | Sep 28, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [1f420db3fd](https://linux-hardware.org/?probe=1f420db3fd) | Sep 28, 2023 |
| HP            | 84F5                        | Mini pc     | [ef936bc0cb](https://linux-hardware.org/?probe=ef936bc0cb) | Sep 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [fb4cde69b8](https://linux-hardware.org/?probe=fb4cde69b8) | Sep 28, 2023 |
| Toshiba       | Satellite P775              | Notebook    | [7269165fd9](https://linux-hardware.org/?probe=7269165fd9) | Sep 28, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [c25eeffab1](https://linux-hardware.org/?probe=c25eeffab1) | Sep 28, 2023 |
| HP            | EliteBook 850 G1            | Notebook    | [35f0e18f04](https://linux-hardware.org/?probe=35f0e18f04) | Sep 28, 2023 |
| Alienware     | x14                         | Notebook    | [048d5f6f2a](https://linux-hardware.org/?probe=048d5f6f2a) | Sep 28, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [f46006f6ce](https://linux-hardware.org/?probe=f46006f6ce) | Sep 28, 2023 |
| ASUSTek       | PRIME B560M-K               | Desktop     | [ee02fff8df](https://linux-hardware.org/?probe=ee02fff8df) | Sep 28, 2023 |
| ASUSTek       | X555LN                      | Notebook    | [773691291a](https://linux-hardware.org/?probe=773691291a) | Sep 28, 2023 |
| ASRock        | B450 Pro4 R2.0              | Desktop     | [82562e75c3](https://linux-hardware.org/?probe=82562e75c3) | Sep 28, 2023 |
| Lenovo        | ThinkServer TS140           | Desktop     | [0e08685628](https://linux-hardware.org/?probe=0e08685628) | Sep 28, 2023 |
| Lenovo        | ThinkPad X250 20CMS0A200    | Notebook    | [54f848d222](https://linux-hardware.org/?probe=54f848d222) | Sep 28, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [001231c730](https://linux-hardware.org/?probe=001231c730) | Sep 28, 2023 |
| HP            | Notebook                    | Notebook    | [49192b29a6](https://linux-hardware.org/?probe=49192b29a6) | Sep 28, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [ea6622fcde](https://linux-hardware.org/?probe=ea6622fcde) | Sep 28, 2023 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | Desktop     | [130796560f](https://linux-hardware.org/?probe=130796560f) | Sep 28, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [a7e3c38a52](https://linux-hardware.org/?probe=a7e3c38a52) | Sep 28, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [eeb582da25](https://linux-hardware.org/?probe=eeb582da25) | Sep 28, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [d53c8ae481](https://linux-hardware.org/?probe=d53c8ae481) | Sep 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [a329c5630e](https://linux-hardware.org/?probe=a329c5630e) | Sep 28, 2023 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [627751c21a](https://linux-hardware.org/?probe=627751c21a) | Sep 28, 2023 |
| Dell          | XPS 17 9700                 | Notebook    | [38196b3712](https://linux-hardware.org/?probe=38196b3712) | Sep 28, 2023 |
| ASUSTek       | P8H77-V                     | Desktop     | [24ff983f95](https://linux-hardware.org/?probe=24ff983f95) | Sep 28, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [1d2bd102c6](https://linux-hardware.org/?probe=1d2bd102c6) | Sep 28, 2023 |
| ASRock        | Z370 Pro4                   | Desktop     | [a70543ae67](https://linux-hardware.org/?probe=a70543ae67) | Sep 28, 2023 |
| HP            | EliteBook 820 G2            | Notebook    | [a32eb9fe02](https://linux-hardware.org/?probe=a32eb9fe02) | Sep 28, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [a1ef1eb6e6](https://linux-hardware.org/?probe=a1ef1eb6e6) | Sep 28, 2023 |
| Apple         | Mac-A369DDC4E67F1C45 iMa... | All in one  | [4fb593dcca](https://linux-hardware.org/?probe=4fb593dcca) | Sep 28, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [e7b135256f](https://linux-hardware.org/?probe=e7b135256f) | Sep 28, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [872af2bc77](https://linux-hardware.org/?probe=872af2bc77) | Sep 28, 2023 |
| GreatWall     | GW-001Y1B-FTF               | All in one  | [7a7a16fc50](https://linux-hardware.org/?probe=7a7a16fc50) | Sep 28, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [3c87964524](https://linux-hardware.org/?probe=3c87964524) | Sep 28, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [5dbe8e1541](https://linux-hardware.org/?probe=5dbe8e1541) | Sep 28, 2023 |
| Valve         | Jupiter                     | Notebook    | [2c1e6c791d](https://linux-hardware.org/?probe=2c1e6c791d) | Sep 28, 2023 |
| eMachines     | E725                        | Notebook    | [2c76723d59](https://linux-hardware.org/?probe=2c76723d59) | Sep 28, 2023 |
| Intel         | NUC12WSBi7 M63355-302       | Mini pc     | [043bac31d2](https://linux-hardware.org/?probe=043bac31d2) | Sep 28, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [b0c2b630a6](https://linux-hardware.org/?probe=b0c2b630a6) | Sep 28, 2023 |
| ASRock        | A520M-HDV                   | Desktop     | [d19f334f02](https://linux-hardware.org/?probe=d19f334f02) | Sep 28, 2023 |
| Packard Be... | EasyNote MH36               | Notebook    | [91fcf40898](https://linux-hardware.org/?probe=91fcf40898) | Sep 28, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | Notebook    | [c717c1ab13](https://linux-hardware.org/?probe=c717c1ab13) | Sep 28, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [92d7b8d41e](https://linux-hardware.org/?probe=92d7b8d41e) | Sep 28, 2023 |
| HP            | 240 G8 Notebook PC          | Notebook    | [d40624877e](https://linux-hardware.org/?probe=d40624877e) | Sep 28, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [1f3c152dc3](https://linux-hardware.org/?probe=1f3c152dc3) | Sep 28, 2023 |
| Gigabyte      | F2A88X-D3H                  | Desktop     | [13e1dcb2be](https://linux-hardware.org/?probe=13e1dcb2be) | Sep 28, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [3a08b7188c](https://linux-hardware.org/?probe=3a08b7188c) | Sep 28, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [3d996f9823](https://linux-hardware.org/?probe=3d996f9823) | Sep 28, 2023 |
| ASUSTek       | X441NA                      | Notebook    | [e44f45e8d6](https://linux-hardware.org/?probe=e44f45e8d6) | Sep 28, 2023 |
| ASUSTek       | ROG Flow X13 GV302XU_GV3... | Convertible | [abf12be6ff](https://linux-hardware.org/?probe=abf12be6ff) | Sep 28, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [e7fb14ee98](https://linux-hardware.org/?probe=e7fb14ee98) | Sep 28, 2023 |
| HP            | 8265                        | Desktop     | [2ae07c2008](https://linux-hardware.org/?probe=2ae07c2008) | Sep 28, 2023 |
| Dell          | Vostro 5470                 | Notebook    | [b6f9976e23](https://linux-hardware.org/?probe=b6f9976e23) | Sep 28, 2023 |
| Dell          | Latitude E5570              | Notebook    | [150f9e624b](https://linux-hardware.org/?probe=150f9e624b) | Sep 28, 2023 |
| Loongson      | LS3A6000-7A2000-1w-EVB-V... | Desktop     | [89d08f5ea8](https://linux-hardware.org/?probe=89d08f5ea8) | Sep 28, 2023 |
| Loongson      | LS3A6000-7A2000-1w-EVB-V... | Desktop     | [576c14796a](https://linux-hardware.org/?probe=576c14796a) | Sep 28, 2023 |
| ASUSTek       | K45VM                       | Notebook    | [6c167e69a4](https://linux-hardware.org/?probe=6c167e69a4) | Sep 28, 2023 |
| Lenovo        | ThinkPad W540 20BG0016US    | Notebook    | [3ee705f2f3](https://linux-hardware.org/?probe=3ee705f2f3) | Sep 28, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [797275028d](https://linux-hardware.org/?probe=797275028d) | Sep 28, 2023 |
| Intel         | X99H                        | Desktop     | [d5390cf599](https://linux-hardware.org/?probe=d5390cf599) | Sep 28, 2023 |
| Lenovo        | ThinkPad W540 20BG0016US    | Notebook    | [2b86c9fac4](https://linux-hardware.org/?probe=2b86c9fac4) | Sep 28, 2023 |
| Shenzhen M... | F7BAA                       | Desktop     | [a59f2cf9f2](https://linux-hardware.org/?probe=a59f2cf9f2) | Sep 28, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [f29316926a](https://linux-hardware.org/?probe=f29316926a) | Sep 28, 2023 |
| MSI           | PRO Z690-A WIFI             | Desktop     | [2ede90f6eb](https://linux-hardware.org/?probe=2ede90f6eb) | Sep 28, 2023 |
| Acer          | Acadia V1.35                | Notebook    | [c2074b2535](https://linux-hardware.org/?probe=c2074b2535) | Sep 28, 2023 |
| Gigabyte      | B560M AORUS PRO AX          | Desktop     | [2e3d19e919](https://linux-hardware.org/?probe=2e3d19e919) | Sep 28, 2023 |
| Lenovo        | ThinkCentre M57 6075Y3W     | Desktop     | [8e39080ed3](https://linux-hardware.org/?probe=8e39080ed3) | Sep 28, 2023 |
| Lenovo        | ThinkPad T495 20NJ000XGE    | Notebook    | [737b3910bb](https://linux-hardware.org/?probe=737b3910bb) | Sep 28, 2023 |
| Lenovo        | ThinkPad T495 20NJ000XGE    | Notebook    | [b064b5b9ca](https://linux-hardware.org/?probe=b064b5b9ca) | Sep 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [58fdd789af](https://linux-hardware.org/?probe=58fdd789af) | Sep 28, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [61980df9bc](https://linux-hardware.org/?probe=61980df9bc) | Sep 28, 2023 |
| HP            | Laptop 17-bs0xx             | Notebook    | [85548f2790](https://linux-hardware.org/?probe=85548f2790) | Sep 28, 2023 |
| ASUSTek       | ROG Strix G814JI_G814JI     | Notebook    | [2a507c567b](https://linux-hardware.org/?probe=2a507c567b) | Sep 28, 2023 |
| Intel         | NUC13ANBi7 M89645-203       | Mini pc     | [d9baf0c41d](https://linux-hardware.org/?probe=d9baf0c41d) | Sep 28, 2023 |
| Pegatron      | IPMSB-H61                   | Desktop     | [d0e64d2ebf](https://linux-hardware.org/?probe=d0e64d2ebf) | Sep 28, 2023 |
| Gigabyte      | P35V3                       | Notebook    | [573f9ea2f5](https://linux-hardware.org/?probe=573f9ea2f5) | Sep 28, 2023 |
| System76      | Oryx Pro                    | Notebook    | [f06316545d](https://linux-hardware.org/?probe=f06316545d) | Sep 28, 2023 |
| Gigabyte      | C1037UN-EU                  | Desktop     | [3a4cc5469a](https://linux-hardware.org/?probe=3a4cc5469a) | Sep 28, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [009a6a1a98](https://linux-hardware.org/?probe=009a6a1a98) | Sep 27, 2023 |
| Gigabyte      | H610M H DDR4                | Desktop     | [c09e747a85](https://linux-hardware.org/?probe=c09e747a85) | Sep 27, 2023 |
| HP            | Notebook                    | Notebook    | [b13debd2fa](https://linux-hardware.org/?probe=b13debd2fa) | Sep 27, 2023 |
| Acer          | Swift SF314-42              | Notebook    | [f436f21240](https://linux-hardware.org/?probe=f436f21240) | Sep 27, 2023 |
| MSI           | Z97-G45 GAMING              | Desktop     | [19c07d0fca](https://linux-hardware.org/?probe=19c07d0fca) | Sep 27, 2023 |
| Dell          | Inspiron 5515               | Notebook    | [5889ba673d](https://linux-hardware.org/?probe=5889ba673d) | Sep 27, 2023 |
| Acer          | Aspire E5-571               | Notebook    | [acd3733ebf](https://linux-hardware.org/?probe=acd3733ebf) | Sep 27, 2023 |
| Gigabyte      | C1037UN-EU                  | Desktop     | [1c2d4da0c6](https://linux-hardware.org/?probe=1c2d4da0c6) | Sep 27, 2023 |
| Gigabyte      | Z390 AORUS MASTER-CF        | Desktop     | [1458dfe403](https://linux-hardware.org/?probe=1458dfe403) | Sep 27, 2023 |
| Zebra Tech... | 10-WLAN-1                   | Notebook    | [9959efdb76](https://linux-hardware.org/?probe=9959efdb76) | Sep 27, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [3cb2bdba37](https://linux-hardware.org/?probe=3cb2bdba37) | Sep 27, 2023 |
| Acer          | Aspire VN7-791G             | Notebook    | [0cfe515d00](https://linux-hardware.org/?probe=0cfe515d00) | Sep 27, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [001d5aa716](https://linux-hardware.org/?probe=001d5aa716) | Sep 27, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [c5c6c5233a](https://linux-hardware.org/?probe=c5c6c5233a) | Sep 27, 2023 |
| Gigabyte      | H610M S2H DDR4              | Desktop     | [9d767beb12](https://linux-hardware.org/?probe=9d767beb12) | Sep 27, 2023 |
| Sony          | VPCEB4J0E                   | Notebook    | [354e2be55e](https://linux-hardware.org/?probe=354e2be55e) | Sep 27, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [47a0a8627c](https://linux-hardware.org/?probe=47a0a8627c) | Sep 27, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [b6acaf4c61](https://linux-hardware.org/?probe=b6acaf4c61) | Sep 27, 2023 |
| HP            | ElitePad 1000 G2            | Notebook    | [a53de5d0bd](https://linux-hardware.org/?probe=a53de5d0bd) | Sep 27, 2023 |
| EUROCOM       | RACER 2.0                   | Notebook    | [4351733d37](https://linux-hardware.org/?probe=4351733d37) | Sep 27, 2023 |
| Positivo      | POS-RIH470EM 11179450       | Desktop     | [cf8e3e73bb](https://linux-hardware.org/?probe=cf8e3e73bb) | Sep 27, 2023 |
| HP            | ElitePad 1000 G2            | Notebook    | [9c4b30a15c](https://linux-hardware.org/?probe=9c4b30a15c) | Sep 27, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [8fb9d5d21f](https://linux-hardware.org/?probe=8fb9d5d21f) | Sep 27, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [13a2717815](https://linux-hardware.org/?probe=13a2717815) | Sep 27, 2023 |
| HP            | ElitePad 1000 G2            | Notebook    | [2668770971](https://linux-hardware.org/?probe=2668770971) | Sep 27, 2023 |
| Fujitsu       | LIFEBOOK E4512              | Notebook    | [08b39b38bd](https://linux-hardware.org/?probe=08b39b38bd) | Sep 27, 2023 |
| MiTAC         | PD10EHI                     | Desktop     | [29716ecb18](https://linux-hardware.org/?probe=29716ecb18) | Sep 27, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [7ed50e5e43](https://linux-hardware.org/?probe=7ed50e5e43) | Sep 27, 2023 |
| Medion        | E3221                       | Convertible | [eaa3a2c9ee](https://linux-hardware.org/?probe=eaa3a2c9ee) | Sep 27, 2023 |
| Acer          | Nitro AN515-42              | Notebook    | [dd4a3f701c](https://linux-hardware.org/?probe=dd4a3f701c) | Sep 27, 2023 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [cfc3a037ed](https://linux-hardware.org/?probe=cfc3a037ed) | Sep 27, 2023 |
| Dell          | Latitude 7490               | Notebook    | [6f5e4547fa](https://linux-hardware.org/?probe=6f5e4547fa) | Sep 27, 2023 |
| Huanan        | X99-BD4 V1.34, NALEX        | Desktop     | [493d23b3f0](https://linux-hardware.org/?probe=493d23b3f0) | Sep 27, 2023 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [a1a8055117](https://linux-hardware.org/?probe=a1a8055117) | Sep 27, 2023 |
| Toshiba       | Satellite L550              | Notebook    | [d93c40647f](https://linux-hardware.org/?probe=d93c40647f) | Sep 27, 2023 |
| MSI           | MPG Z490M GAMING EDGE WI... | Desktop     | [23150c5bd3](https://linux-hardware.org/?probe=23150c5bd3) | Sep 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [a95feaee78](https://linux-hardware.org/?probe=a95feaee78) | Sep 27, 2023 |
| Dell          | G16 7620                    | Notebook    | [cd30e51d53](https://linux-hardware.org/?probe=cd30e51d53) | Sep 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [7c13a64c8a](https://linux-hardware.org/?probe=7c13a64c8a) | Sep 27, 2023 |
| TUXEDO        | Stellaris Intel Gen4        | Notebook    | [0dcef3e6c3](https://linux-hardware.org/?probe=0dcef3e6c3) | Sep 27, 2023 |
| ASUSTek       | P5QD TURBO                  | Desktop     | [9e8a75e698](https://linux-hardware.org/?probe=9e8a75e698) | Sep 27, 2023 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [7943462da1](https://linux-hardware.org/?probe=7943462da1) | Sep 27, 2023 |
| Framework     | Laptop                      | Notebook    | [2a65b0dff2](https://linux-hardware.org/?probe=2a65b0dff2) | Sep 27, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [e15856c8f1](https://linux-hardware.org/?probe=e15856c8f1) | Sep 27, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [7cfa1007ee](https://linux-hardware.org/?probe=7cfa1007ee) | Sep 27, 2023 |
| Dell          | G3 3590                     | Notebook    | [3523165978](https://linux-hardware.org/?probe=3523165978) | Sep 27, 2023 |
| Supermicro    | X8DAH                       | Server      | [ef771077af](https://linux-hardware.org/?probe=ef771077af) | Sep 27, 2023 |
| HP            | 620                         | Notebook    | [1bdfd56638](https://linux-hardware.org/?probe=1bdfd56638) | Sep 27, 2023 |
| Supermicro    | X9DRW                       | Server      | [3dcf1261b5](https://linux-hardware.org/?probe=3dcf1261b5) | Sep 27, 2023 |
| Lenovo        | ThinkPad X240 20AMS1JQ11    | Notebook    | [2b7f074e47](https://linux-hardware.org/?probe=2b7f074e47) | Sep 27, 2023 |
| ETegro Tec... | ETRS125G4 31S2MMB0040       | Server      | [2b1ce7346b](https://linux-hardware.org/?probe=2b1ce7346b) | Sep 27, 2023 |
| Dell          | Latitude E6540              | Notebook    | [7d9885cd7c](https://linux-hardware.org/?probe=7d9885cd7c) | Sep 27, 2023 |
| Dell          | Latitude 5431               | Notebook    | [d9ea685862](https://linux-hardware.org/?probe=d9ea685862) | Sep 27, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [8556633dad](https://linux-hardware.org/?probe=8556633dad) | Sep 27, 2023 |
| Lenovo        | ThinkPad T430 2349S6S       | Notebook    | [e9b81983f2](https://linux-hardware.org/?probe=e9b81983f2) | Sep 27, 2023 |
| HP            | Laptop 17-by0xxx            | Notebook    | [6eefb5fdd2](https://linux-hardware.org/?probe=6eefb5fdd2) | Sep 27, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [b5ce99a949](https://linux-hardware.org/?probe=b5ce99a949) | Sep 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [1317c1f1a9](https://linux-hardware.org/?probe=1317c1f1a9) | Sep 27, 2023 |
| Dell          | Latitude 5480               | Notebook    | [8dd1695b2c](https://linux-hardware.org/?probe=8dd1695b2c) | Sep 27, 2023 |
| System76      | Lemur Pro                   | Notebook    | [6013ab7f8a](https://linux-hardware.org/?probe=6013ab7f8a) | Sep 27, 2023 |
| ASUSTek       | D700MD                      | Desktop     | [91740e63b9](https://linux-hardware.org/?probe=91740e63b9) | Sep 27, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [1a472d3072](https://linux-hardware.org/?probe=1a472d3072) | Sep 27, 2023 |
| Lenovo        | ThinkPad T480 20L6S5M000    | Notebook    | [58ddf5337a](https://linux-hardware.org/?probe=58ddf5337a) | Sep 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [b5dee453a3](https://linux-hardware.org/?probe=b5dee453a3) | Sep 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [8c585051a3](https://linux-hardware.org/?probe=8c585051a3) | Sep 27, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [dd7145f468](https://linux-hardware.org/?probe=dd7145f468) | Sep 27, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [707c612189](https://linux-hardware.org/?probe=707c612189) | Sep 27, 2023 |
| AMI           | Cherry Trail CR             | Notebook    | [41b2d006c1](https://linux-hardware.org/?probe=41b2d006c1) | Sep 27, 2023 |
| Dell          | 0JP3NX A01                  | Desktop     | [d14bc5c139](https://linux-hardware.org/?probe=d14bc5c139) | Sep 27, 2023 |
| MSI           | Z97 PC Mate                 | Desktop     | [15a7321226](https://linux-hardware.org/?probe=15a7321226) | Sep 27, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [7ab6fc6901](https://linux-hardware.org/?probe=7ab6fc6901) | Sep 27, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2G90... | Notebook    | [50c8df3b79](https://linux-hardware.org/?probe=50c8df3b79) | Sep 27, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2G90... | Notebook    | [6cfd6e2b34](https://linux-hardware.org/?probe=6cfd6e2b34) | Sep 27, 2023 |
| Acer          | Predator G3-571             | Notebook    | [f301a514ad](https://linux-hardware.org/?probe=f301a514ad) | Sep 27, 2023 |
| HP            | 8594                        | Desktop     | [374067df48](https://linux-hardware.org/?probe=374067df48) | Sep 27, 2023 |
| Samsung       | 550XDA                      | Notebook    | [ab1fabfe9b](https://linux-hardware.org/?probe=ab1fabfe9b) | Sep 27, 2023 |
| MSI           | Z97 PC Mate                 | Desktop     | [18bf7cff74](https://linux-hardware.org/?probe=18bf7cff74) | Sep 27, 2023 |
| Dell          | Latitude E7440              | Notebook    | [9e117fe599](https://linux-hardware.org/?probe=9e117fe599) | Sep 27, 2023 |
| Dell          | Inspiron N5040              | Notebook    | [c48d158b62](https://linux-hardware.org/?probe=c48d158b62) | Sep 27, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [84ad07c3f9](https://linux-hardware.org/?probe=84ad07c3f9) | Sep 27, 2023 |
| HP            | Dev One Notebook PC         | Notebook    | [61caf9212e](https://linux-hardware.org/?probe=61caf9212e) | Sep 27, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [4ef9eaaaba](https://linux-hardware.org/?probe=4ef9eaaaba) | Sep 27, 2023 |
| HP            | 250 G1                      | Notebook    | [0ec87fea6c](https://linux-hardware.org/?probe=0ec87fea6c) | Sep 27, 2023 |
| AMI           | Cherry Trail CR             | Notebook    | [050c423c6b](https://linux-hardware.org/?probe=050c423c6b) | Sep 27, 2023 |
| Dell          | Latitude 7390               | Notebook    | [93e22b6fc4](https://linux-hardware.org/?probe=93e22b6fc4) | Sep 27, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [593ddb6105](https://linux-hardware.org/?probe=593ddb6105) | Sep 27, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [3fcfddc8e9](https://linux-hardware.org/?probe=3fcfddc8e9) | Sep 27, 2023 |
| Toshiba       | Satellite P50-B-117         | Notebook    | [3931144171](https://linux-hardware.org/?probe=3931144171) | Sep 27, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [e5cd50e4ea](https://linux-hardware.org/?probe=e5cd50e4ea) | Sep 27, 2023 |
| Lenovo        | S10-3c 20074                | Notebook    | [b8adc3cf3e](https://linux-hardware.org/?probe=b8adc3cf3e) | Sep 27, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [546df5b57f](https://linux-hardware.org/?probe=546df5b57f) | Sep 27, 2023 |
| Dell          | Latitude 7390               | Notebook    | [a7bfa2e285](https://linux-hardware.org/?probe=a7bfa2e285) | Sep 27, 2023 |
| Dell          | Latitude 3410               | Notebook    | [7b326dd690](https://linux-hardware.org/?probe=7b326dd690) | Sep 27, 2023 |
| Dell          | Latitude E6530              | Notebook    | [40cdcd2545](https://linux-hardware.org/?probe=40cdcd2545) | Sep 27, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [503570ad7a](https://linux-hardware.org/?probe=503570ad7a) | Sep 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [cb12d6c853](https://linux-hardware.org/?probe=cb12d6c853) | Sep 27, 2023 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | Mini pc     | [5991ea82e7](https://linux-hardware.org/?probe=5991ea82e7) | Sep 27, 2023 |
| Chuwi         | CoreBook X                  | Notebook    | [0c31a47880](https://linux-hardware.org/?probe=0c31a47880) | Sep 27, 2023 |
| HP            | 2ADE                        | Desktop     | [b701a5c589](https://linux-hardware.org/?probe=b701a5c589) | Sep 27, 2023 |
| MSI           | Z77A-S01                    | Desktop     | [277586f152](https://linux-hardware.org/?probe=277586f152) | Sep 27, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [5646b6da22](https://linux-hardware.org/?probe=5646b6da22) | Sep 27, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [f47347fb9b](https://linux-hardware.org/?probe=f47347fb9b) | Sep 27, 2023 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | Notebook    | [cd5d2fae9e](https://linux-hardware.org/?probe=cd5d2fae9e) | Sep 27, 2023 |
| Apple         | MacBookPro15,2              | Notebook    | [1331a57778](https://linux-hardware.org/?probe=1331a57778) | Sep 27, 2023 |
| Dell          | Vostro 3360                 | Notebook    | [812367b788](https://linux-hardware.org/?probe=812367b788) | Sep 27, 2023 |
| Dell          | XPS 17 9700                 | Notebook    | [c341826b7a](https://linux-hardware.org/?probe=c341826b7a) | Sep 27, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [1d8c54163d](https://linux-hardware.org/?probe=1d8c54163d) | Sep 27, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | Desktop     | [41f0f8666c](https://linux-hardware.org/?probe=41f0f8666c) | Sep 27, 2023 |
| Dell          | Precision 5570              | Notebook    | [f00d32a04a](https://linux-hardware.org/?probe=f00d32a04a) | Sep 27, 2023 |
| Lenovo        | YB1-X91F                    | Convertible | [f5fa6cb83d](https://linux-hardware.org/?probe=f5fa6cb83d) | Sep 27, 2023 |
| Toshiba       | Satellite A200              | Notebook    | [6bdac98313](https://linux-hardware.org/?probe=6bdac98313) | Sep 27, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [55c34c64a6](https://linux-hardware.org/?probe=55c34c64a6) | Sep 27, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [6295f7193c](https://linux-hardware.org/?probe=6295f7193c) | Sep 27, 2023 |
| Lenovo        | ThinkPad X200 74591P0       | Notebook    | [9a3f695f09](https://linux-hardware.org/?probe=9a3f695f09) | Sep 27, 2023 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | Notebook    | [0f2958c5a1](https://linux-hardware.org/?probe=0f2958c5a1) | Sep 27, 2023 |
| MSI           | H81M-P33                    | Desktop     | [8b0d086b89](https://linux-hardware.org/?probe=8b0d086b89) | Sep 27, 2023 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [34e34036d7](https://linux-hardware.org/?probe=34e34036d7) | Sep 27, 2023 |
| Acer          | Aspire E1-531               | Notebook    | [6b981869d7](https://linux-hardware.org/?probe=6b981869d7) | Sep 27, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [f1623258a8](https://linux-hardware.org/?probe=f1623258a8) | Sep 27, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [e54490e96a](https://linux-hardware.org/?probe=e54490e96a) | Sep 27, 2023 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [4f0651ccc2](https://linux-hardware.org/?probe=4f0651ccc2) | Sep 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [2bf5f64c14](https://linux-hardware.org/?probe=2bf5f64c14) | Sep 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [fb82c6e942](https://linux-hardware.org/?probe=fb82c6e942) | Sep 27, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [72bb0c5858](https://linux-hardware.org/?probe=72bb0c5858) | Sep 27, 2023 |
| Gigabyte      | H61MA-D3V                   | Desktop     | [a9c8158139](https://linux-hardware.org/?probe=a9c8158139) | Sep 27, 2023 |
| Lenovo        | XiaoXinPro 16 APH8 83AR     | Notebook    | [9ad96a3803](https://linux-hardware.org/?probe=9ad96a3803) | Sep 27, 2023 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [167d2e893e](https://linux-hardware.org/?probe=167d2e893e) | Sep 27, 2023 |
| Lenovo        | ThinkPad W541 20EGS24J00    | Notebook    | [e87c0e3c00](https://linux-hardware.org/?probe=e87c0e3c00) | Sep 27, 2023 |
| HP            | EliteBook x360 1020 G2      | Convertible | [7b6ee612cf](https://linux-hardware.org/?probe=7b6ee612cf) | Sep 27, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [f6c6bfc3fe](https://linux-hardware.org/?probe=f6c6bfc3fe) | Sep 27, 2023 |
| Sony          | VPCEG10EL                   | Notebook    | [7bfbe9b21d](https://linux-hardware.org/?probe=7bfbe9b21d) | Sep 27, 2023 |
| Notebook      | PCx0Dx                      | Notebook    | [53dd8cbd0d](https://linux-hardware.org/?probe=53dd8cbd0d) | Sep 27, 2023 |
| HP            | 1589                        | Desktop     | [1063a6e665](https://linux-hardware.org/?probe=1063a6e665) | Sep 27, 2023 |
| HP            | Stream x360 Convertible ... | Convertible | [d237ab1a11](https://linux-hardware.org/?probe=d237ab1a11) | Sep 27, 2023 |
| Dell          | System XPS L502X            | Notebook    | [06d6fd95d1](https://linux-hardware.org/?probe=06d6fd95d1) | Sep 27, 2023 |
| HONOR         | NBR-WAX9                    | Notebook    | [68556b1e09](https://linux-hardware.org/?probe=68556b1e09) | Sep 27, 2023 |
| MSI           | PRO Z790-A WIFI DDR4        | Desktop     | [74ea1c8adf](https://linux-hardware.org/?probe=74ea1c8adf) | Sep 27, 2023 |
| HONOR         | NBR-WAX9                    | Notebook    | [056de6b9b3](https://linux-hardware.org/?probe=056de6b9b3) | Sep 27, 2023 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [a4d1820df5](https://linux-hardware.org/?probe=a4d1820df5) | Sep 27, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [17f9208e1a](https://linux-hardware.org/?probe=17f9208e1a) | Sep 27, 2023 |
| ASUSTek       | PRO H410M-C                 | Desktop     | [6554d255c3](https://linux-hardware.org/?probe=6554d255c3) | Sep 27, 2023 |
| AAEON         | MIX-H310D1 V1.0             | Desktop     | [7a3b3d3b2d](https://linux-hardware.org/?probe=7a3b3d3b2d) | Sep 27, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [af863ee3d6](https://linux-hardware.org/?probe=af863ee3d6) | Sep 27, 2023 |
| HP            | 3398                        | Desktop     | [fed07fc26f](https://linux-hardware.org/?probe=fed07fc26f) | Sep 27, 2023 |
| HP            | 3398                        | Desktop     | [5f4cd7d05b](https://linux-hardware.org/?probe=5f4cd7d05b) | Sep 27, 2023 |
| Packard Be... | EasyNote TK85               | Notebook    | [79e6dd1302](https://linux-hardware.org/?probe=79e6dd1302) | Sep 27, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [8e70938939](https://linux-hardware.org/?probe=8e70938939) | Sep 27, 2023 |
| HP            | Elite Dragonfly 13.5 inc... | Notebook    | [7941c7c6cc](https://linux-hardware.org/?probe=7941c7c6cc) | Sep 27, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | Notebook    | [fed9f17a22](https://linux-hardware.org/?probe=fed9f17a22) | Sep 27, 2023 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [500909194e](https://linux-hardware.org/?probe=500909194e) | Sep 27, 2023 |
| Acer          | Predator G3-571             | Notebook    | [06b0300670](https://linux-hardware.org/?probe=06b0300670) | Sep 27, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | Notebook    | [0dd1b47aa0](https://linux-hardware.org/?probe=0dd1b47aa0) | Sep 27, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [c25a72c95a](https://linux-hardware.org/?probe=c25a72c95a) | Sep 27, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [f004fa8e32](https://linux-hardware.org/?probe=f004fa8e32) | Sep 27, 2023 |
| Acer          | Aspire E1-531               | Notebook    | [d47b59c89b](https://linux-hardware.org/?probe=d47b59c89b) | Sep 27, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [3646127006](https://linux-hardware.org/?probe=3646127006) | Sep 27, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [b6e832a4d8](https://linux-hardware.org/?probe=b6e832a4d8) | Sep 27, 2023 |
| ASRock        | X370 Gaming X               | Desktop     | [ee8f74ab5e](https://linux-hardware.org/?probe=ee8f74ab5e) | Sep 27, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | Notebook    | [c7ec123b46](https://linux-hardware.org/?probe=c7ec123b46) | Sep 27, 2023 |
| Gigabyte      | B650M K                     | Desktop     | [73da1b7ade](https://linux-hardware.org/?probe=73da1b7ade) | Sep 27, 2023 |
| MSI           | Bravo 15 C7VE               | Notebook    | [844b7f2a1c](https://linux-hardware.org/?probe=844b7f2a1c) | Sep 27, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [1543bac588](https://linux-hardware.org/?probe=1543bac588) | Sep 27, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [054707cbd2](https://linux-hardware.org/?probe=054707cbd2) | Sep 27, 2023 |
| ASUSTek       | N551JW                      | Notebook    | [8c38084e7e](https://linux-hardware.org/?probe=8c38084e7e) | Sep 27, 2023 |
| Toshiba       | dynabook T350/46BW          | Notebook    | [26ffaa1c0f](https://linux-hardware.org/?probe=26ffaa1c0f) | Sep 27, 2023 |
| Lenovo        | ThinkPad E14 20RA0050US     | Notebook    | [097539dde8](https://linux-hardware.org/?probe=097539dde8) | Sep 27, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [0ba9157463](https://linux-hardware.org/?probe=0ba9157463) | Sep 27, 2023 |
| Dell          | Latitude E7450              | Notebook    | [afa1cce666](https://linux-hardware.org/?probe=afa1cce666) | Sep 27, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [b4de4fe266](https://linux-hardware.org/?probe=b4de4fe266) | Sep 27, 2023 |
| Acer          | Aspire A315-53              | Notebook    | [c20a9f8f96](https://linux-hardware.org/?probe=c20a9f8f96) | Sep 27, 2023 |
| Acer          | Aspire one                  | Notebook    | [d040844540](https://linux-hardware.org/?probe=d040844540) | Sep 27, 2023 |
| Intel         | X79F1 V2.0                  | Desktop     | [919b208284](https://linux-hardware.org/?probe=919b208284) | Sep 27, 2023 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [9d86e194aa](https://linux-hardware.org/?probe=9d86e194aa) | Sep 27, 2023 |
| ZOTAC         | NM10                        | Desktop     | [8932b16aa1](https://linux-hardware.org/?probe=8932b16aa1) | Sep 27, 2023 |
| ASUSTek       | N550JV                      | Notebook    | [ac27d821ae](https://linux-hardware.org/?probe=ac27d821ae) | Sep 27, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [e8577ce363](https://linux-hardware.org/?probe=e8577ce363) | Sep 27, 2023 |
| Medion        | E6431 MD60112               | Notebook    | [f1fee9da62](https://linux-hardware.org/?probe=f1fee9da62) | Sep 27, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [a1fa543905](https://linux-hardware.org/?probe=a1fa543905) | Sep 27, 2023 |
| HP            | EliteBook 8770w             | Notebook    | [3286090099](https://linux-hardware.org/?probe=3286090099) | Sep 27, 2023 |
| Gigabyte      | GA-880GM-USB3L              | Desktop     | [f160911c14](https://linux-hardware.org/?probe=f160911c14) | Sep 27, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [cc0d6b9ebb](https://linux-hardware.org/?probe=cc0d6b9ebb) | Sep 27, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [fac9ee2e6e](https://linux-hardware.org/?probe=fac9ee2e6e) | Sep 27, 2023 |
| ASRock        | Z790 Taichi                 | Desktop     | [949be6194e](https://linux-hardware.org/?probe=949be6194e) | Sep 27, 2023 |
| Intel         | X79G V2.x                   | Desktop     | [3d001a09ab](https://linux-hardware.org/?probe=3d001a09ab) | Sep 27, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [c60600b4f0](https://linux-hardware.org/?probe=c60600b4f0) | Sep 27, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [812b06784e](https://linux-hardware.org/?probe=812b06784e) | Sep 27, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [278578e488](https://linux-hardware.org/?probe=278578e488) | Sep 27, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [240ff7b72a](https://linux-hardware.org/?probe=240ff7b72a) | Sep 27, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [0f2a543485](https://linux-hardware.org/?probe=0f2a543485) | Sep 27, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [6f4a404e89](https://linux-hardware.org/?probe=6f4a404e89) | Sep 27, 2023 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [2cdf3dac45](https://linux-hardware.org/?probe=2cdf3dac45) | Sep 27, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [75f65a0438](https://linux-hardware.org/?probe=75f65a0438) | Sep 27, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [2f574aa287](https://linux-hardware.org/?probe=2f574aa287) | Sep 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [d9665a6ffd](https://linux-hardware.org/?probe=d9665a6ffd) | Sep 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [0e32901b18](https://linux-hardware.org/?probe=0e32901b18) | Sep 27, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [4ea2bab759](https://linux-hardware.org/?probe=4ea2bab759) | Sep 27, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [156140f867](https://linux-hardware.org/?probe=156140f867) | Sep 27, 2023 |
| HP            | Notebook                    | Notebook    | [4690fda15e](https://linux-hardware.org/?probe=4690fda15e) | Sep 27, 2023 |
| Dell          | 00F82W A01                  | Desktop     | [ac93742033](https://linux-hardware.org/?probe=ac93742033) | Sep 27, 2023 |
| Google        | Droid                       | Notebook    | [fa5f650f3a](https://linux-hardware.org/?probe=fa5f650f3a) | Sep 26, 2023 |
| YANYU         | H17SL                       | Desktop     | [5966ae64d0](https://linux-hardware.org/?probe=5966ae64d0) | Sep 26, 2023 |

...


System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 25395     | 10.65%  |
| Ubuntu 18.04       | 13146     | 5.51%   |
| Ubuntu 22.04       | 11639     | 4.88%   |
| Debian 11          | 6664      | 2.79%   |
| OpenMandriva 4.2   | 4671      | 1.96%   |
| OpenMandriva 4.3   | 4588      | 1.92%   |
| ROSA R10           | 4390      | 1.84%   |
| ROSA R11           | 4120      | 1.73%   |
| Arch Rolling       | 4081      | 1.71%   |
| ROSA R8            | 3637      | 1.53%   |
| Zorin 16           | 3496      | 1.47%   |
| ROSA R6            | 3496      | 1.47%   |
| Pop!_OS 22.04      | 3368      | 1.41%   |
| ROSA R7            | 3301      | 1.38%   |
| Linux Mint 20.3    | 3139      | 1.32%   |
| Manjaro            | 3003      | 1.26%   |
| Arch               | 2982      | 1.25%   |
| BlackPanther 18.1  | 2895      | 1.21%   |
| KDE neon 20.04     | 2865      | 1.2%    |
| ROSA R8.1          | 2852      | 1.2%    |
| Linux Mint 21.1    | 2654      | 1.11%   |
| ROSA R9            | 2549      | 1.07%   |
| Linux Mint 20.2    | 2417      | 1.01%   |
| Fedora 38          | 2375      | 1%      |
| ROSA R11.1         | 2318      | 0.97%   |
| Linux Mint 20.1    | 2257      | 0.95%   |
| Ubuntu 20.10       | 2225      | 0.93%   |
| Linux Mint 19.3    | 2195      | 0.92%   |
| Fedora 36          | 2138      | 0.9%    |
| Pop!_OS 20.04      | 2129      | 0.89%   |
| Ubuntu 21.10       | 2090      | 0.88%   |
| Ubuntu 19.10       | 2056      | 0.86%   |
| Fedora 37          | 2026      | 0.85%   |
| Linux Mint 20      | 2022      | 0.85%   |
| ArcoLinux Rolling  | 2013      | 0.84%   |
| ROSA 12.2          | 2008      | 0.84%   |
| Xubuntu 20.04      | 1986      | 0.83%   |
| OpenMandriva 23.01 | 1979      | 0.83%   |
| Ubuntu 19.04       | 1903      | 0.8%    |
| OpenMandriva 23.03 | 1893      | 0.79%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 61832     | 27.96%  |
| ROSA          | 26476     | 11.97%  |
| Linux Mint    | 17902     | 8.1%    |
| OpenMandriva  | 14887     | 6.73%   |
| Fedora        | 12612     | 5.7%    |
| Debian        | 10986     | 4.97%   |
| Pop!_OS       | 9611      | 4.35%   |
| Manjaro       | 6986      | 3.16%   |
| Arch          | 6903      | 3.12%   |
| Zorin         | 5316      | 2.4%    |
| Xubuntu       | 4203      | 1.9%    |
| Kubuntu       | 4097      | 1.85%   |
| KDE neon      | 4045      | 1.83%   |
| Endless       | 3476      | 1.57%   |
| BlackPanther  | 3126      | 1.41%   |
| openSUSE      | 2323      | 1.05%   |
| ArcoLinux     | 2185      | 0.99%   |
| Kali          | 1677      | 0.76%   |
| Elementary    | 1636      | 0.74%   |
| Gentoo        | 1554      | 0.7%    |
| Ubuntu MATE   | 1425      | 0.64%   |
| Lubuntu       | 1328      | 0.6%    |
| Ubuntu Unity  | 1159      | 0.52%   |
| SteamOS       | 1113      | 0.5%    |
| EndeavourOS   | 1113      | 0.5%    |
| Clear Linux   | 862       | 0.39%   |
| LMDE          | 849       | 0.38%   |
| CentOS        | 724       | 0.33%   |
| Ubuntu Budgie | 651       | 0.29%   |
| MX            | 651       | 0.29%   |
| Nobara        | 602       | 0.27%   |
| ALT Linux     | 592       | 0.27%   |
| Parrot        | 516       | 0.23%   |
| Garuda Linux  | 509       | 0.23%   |
| Red OS        | 308       | 0.14%   |
| Xero          | 305       | 0.14%   |
| Peppermint    | 301       | 0.14%   |
| Raspbian      | 294       | 0.13%   |
| RHEL          | 286       | 0.13%   |
| LinuxFX       | 227       | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Computers | Percent |
|------------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002           | 4501      | 1.71%   |
| 5.16.7-desktop-1omv4003            | 4298      | 1.64%   |
| 5.4.0-42-generic                   | 3815      | 1.45%   |
| 4.18.16-desktop-1bP                | 2165      | 0.82%   |
| 5.15.0-56-generic                  | 2160      | 0.82%   |
| 4.9.60-nrj-desktop-1rosa-x86_64    | 2054      | 0.78%   |
| 3.14.44-nrj-desktop-2rosa-x86_64   | 1868      | 0.71%   |
| 4.9.20-nrj-desktop-1rosa-x86_64    | 1840      | 0.7%    |
| 6.2.6-desktop-1omv2390             | 1830      | 0.7%    |
| 6.1.1-desktop-1omv2290             | 1813      | 0.69%   |
| 4.15.0-desktop-45.1rosa-x86_64     | 1803      | 0.69%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 1780      | 0.68%   |
| 5.4.0-58-generic                   | 1738      | 0.66%   |
| 4.1.25-nrj-desktop-1rosa-x86_64    | 1602      | 0.61%   |
| 5.4.0-48-generic                   | 1532      | 0.58%   |
| 5.4.0-52-generic                   | 1520      | 0.58%   |
| 5.15.0-58-generic                  | 1508      | 0.57%   |
| 5.15.0-52-generic                  | 1464      | 0.56%   |
| 4.1.15-nrj-desktop-1rosa-x86_64    | 1381      | 0.53%   |
| 5.4.0-26-generic                   | 1340      | 0.51%   |
| 5.15.0-46-generic                  | 1221      | 0.46%   |
| 5.3.0-28-generic                   | 1137      | 0.43%   |
| 5.4.0-29-generic                   | 1125      | 0.43%   |
| 5.4.0-40-generic                   | 1101      | 0.42%   |
| 5.3.0-40-generic                   | 1090      | 0.41%   |
| 5.11.0-27-generic                  | 1074      | 0.41%   |
| 5.15.0-48-generic                  | 1069      | 0.41%   |
| 5.10.0-8-amd64                     | 1010      | 0.38%   |
| 5.3.0-46-generic                   | 998       | 0.38%   |
| 4.1.34-nrj-desktop-2rosa-x86_64    | 972       | 0.37%   |
| 5.19.0-35-generic                  | 950       | 0.36%   |
| 5.4.0-54-generic                   | 948       | 0.36%   |
| 5.4.0-91-generic                   | 945       | 0.36%   |
| 5.8.0-43-generic                   | 939       | 0.36%   |
| 5.11.0-38-generic                  | 928       | 0.35%   |
| 5.11.0-37-generic                  | 927       | 0.35%   |
| 5.4.0-37-generic                   | 923       | 0.35%   |
| 5.4.0-65-generic                   | 914       | 0.35%   |
| 5.4.0-47-generic                   | 884       | 0.34%   |
| 5.15.0-43-generic                  | 884       | 0.34%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 33261     | 13.41%  |
| 5.15.0  | 18557     | 7.48%   |
| 4.15.0  | 14425     | 5.81%   |
| 5.8.0   | 10668     | 4.3%    |
| 5.11.0  | 10315     | 4.16%   |
| 5.13.0  | 9296      | 3.75%   |
| 5.3.0   | 7859      | 3.17%   |
| 5.10.0  | 7393      | 2.98%   |
| 5.19.0  | 6986      | 2.82%   |
| 5.0.0   | 5259      | 2.12%   |
| 5.10.14 | 4553      | 1.84%   |
| 5.16.7  | 4365      | 1.76%   |
| 4.18.0  | 3983      | 1.61%   |
| 6.2.0   | 3389      | 1.37%   |
| 6.2.6   | 2808      | 1.13%   |
| 3.14.44 | 2697      | 1.09%   |
| 4.9.60  | 2596      | 1.05%   |
| 4.9.20  | 2583      | 1.04%   |
| 4.18.16 | 2221      | 0.9%    |
| 6.1.0   | 2206      | 0.89%   |
| 4.1.25  | 2174      | 0.88%   |
| 6.1.1   | 2079      | 0.84%   |
| 4.19.0  | 1984      | 0.8%    |
| 5.10.74 | 1844      | 0.74%   |
| 4.1.15  | 1836      | 0.74%   |
| 4.1.34  | 1350      | 0.54%   |
| 4.1.38  | 1110      | 0.45%   |
| 4.9.9   | 1003      | 0.4%    |
| 4.9.124 | 995       | 0.4%    |
| 5.6.14  | 983       | 0.4%    |
| 6.4.11  | 925       | 0.37%   |
| 5.14.0  | 899       | 0.36%   |
| 5.17.5  | 859       | 0.35%   |
| 6.0.12  | 786       | 0.32%   |
| 6.0.0   | 775       | 0.31%   |
| 4.9.155 | 691       | 0.28%   |
| 4.9.76  | 648       | 0.26%   |
| 4.1.16  | 633       | 0.26%   |
| 4.9.41  | 627       | 0.25%   |
| 4.4.0   | 616       | 0.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 36707     | 15.2%   |
| 5.15    | 24851     | 10.29%  |
| 5.10    | 17883     | 7.4%    |
| 4.15    | 14498     | 6%      |
| 5.8     | 12956     | 5.36%   |
| 5.11    | 12248     | 5.07%   |
| 5.13    | 10944     | 4.53%   |
| 4.9     | 9280      | 3.84%   |
| 5.19    | 9136      | 3.78%   |
| 5.3     | 8873      | 3.67%   |
| 6.2     | 8766      | 3.63%   |
| 6.1     | 8424      | 3.49%   |
| 4.1     | 7577      | 3.14%   |
| 5.16    | 7342      | 3.04%   |
| 4.18    | 6307      | 2.61%   |
| 5.0     | 5578      | 2.31%   |
| 6.0     | 4275      | 1.77%   |
| 6.4     | 3680      | 1.52%   |
| 3.14    | 3554      | 1.47%   |
| 5.17    | 2926      | 1.21%   |
| 5.18    | 2913      | 1.21%   |
| 5.14    | 2809      | 1.16%   |
| 5.6     | 2759      | 1.14%   |
| 4.19    | 2597      | 1.08%   |
| 6.3     | 2593      | 1.07%   |
| 5.9     | 2354      | 0.97%   |
| 5.12    | 1893      | 0.78%   |
| 5.7     | 1639      | 0.68%   |
| 5.5     | 985       | 0.41%   |
| 4.4     | 856       | 0.35%   |
| 6.5     | 789       | 0.33%   |
| 3.10    | 608       | 0.25%   |
| 4.13    | 406       | 0.17%   |
| 5.2     | 400       | 0.17%   |
| 5.1     | 390       | 0.16%   |
| 4.14    | 232       | 0.1%    |
| 4.12    | 188       | 0.08%   |
| 4.16    | 173       | 0.07%   |
| 4.10    | 159       | 0.07%   |
| 4.8     | 139       | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| x86_64      | 201267    | 94.27%  |
| i686        | 10232     | 4.79%   |
| aarch64     | 1437      | 0.67%   |
| armv7l      | 417       | 0.2%    |
| armv8l      | 40        | 0.02%   |
| armv6l      | 39        | 0.02%   |
| riscv64     | 21        | 0.01%   |
| ppc64       | 10        | 0.005%  |
| ppc         | 9         | 0.004%  |
| Unknown     | 7         | 0.003%  |
| i586        | 6         | 0.003%  |
| ppc64le     | 5         | 0.002%  |
| loongarch64 | 5         | 0.002%  |
| e2k         | 5         | 0.002%  |
| mips64      | 3         | 0.001%  |
| mips        | 2         | 0.001%  |
| armv5tel    | 2         | 0.001%  |
| unknow      | 1         | 0.0005% |
| sparc64     | 1         | 0.0005% |
| sh4a        | 1         | 0.0005% |
| s390x       | 1         | 0.0005% |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 85651     | 38.24%  |
| KDE5             | 42715     | 19.07%  |
| Unknown          | 24445     | 10.91%  |
| KDE4             | 18340     | 8.19%   |
| XFCE             | 14262     | 6.37%   |
| X-Cinnamon       | 13396     | 5.98%   |
| MATE             | 5700      | 2.54%   |
| KDE              | 4556      | 2.03%   |
| LXQt             | 2693      | 1.2%    |
| Cinnamon         | 2653      | 1.18%   |
| Pantheon         | 1558      | 0.7%    |
| Unity            | 1186      | 0.53%   |
| LXDE             | 1161      | 0.52%   |
| i3               | 1066      | 0.48%   |
| Budgie           | 1035      | 0.46%   |
| GNOME Flashback  | 537       | 0.24%   |
| Deepin           | 515       | 0.23%   |
| GNOME Classic    | 258       | 0.12%   |
| sway             | 238       | 0.11%   |
| awesome          | 227       | 0.1%    |
| openbox          | 217       | 0.1%    |
| Hyprland         | 172       | 0.08%   |
| GNUstep          | 168       | 0.08%   |
| bspwm            | 149       | 0.07%   |
| lightdm-xsession | 120       | 0.05%   |
| DWM              | 114       | 0.05%   |
| qtile            | 111       | 0.05%   |
| xmonad           | 78        | 0.03%   |
| trinity          | 78        | 0.03%   |
| Enlightenment    | 76        | 0.03%   |
| icewm            | 67        | 0.03%   |
| LeftWM           | 44        | 0.02%   |
| i3-with-shmlog   | 27        | 0.01%   |
| BunsenLabs       | 26        | 0.01%   |
| chadwm           | 22        | 0.01%   |
| fluxbox          | 21        | 0.01%   |
| UKUI             | 20        | 0.01%   |
| herbstluftwm     | 18        | 0.01%   |
| fly              | 16        | 0.01%   |
| Cutefish         | 12        | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 167720    | 76.41%  |
| Wayland     | 34092     | 15.53%  |
| Unknown     | 13310     | 6.06%   |
| Tty         | 4343      | 1.98%   |
| Web         | 29        | 0.01%   |
| Unspecified | 11        | 0.01%   |
| Xcb         | 1         | 0.0005% |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 96467     | 43.28%  |
| SDDM    | 38507     | 17.28%  |
| GDM     | 23061     | 10.35%  |
| GDM3    | 20963     | 9.41%   |
| KDM     | 18472     | 8.29%   |
| LightDM | 18287     | 8.2%    |
| TDM     | 6022      | 2.7%    |
| XDM     | 370       | 0.17%   |
| SLiM    | 233       | 0.1%    |
| LXDM    | 172       | 0.08%   |
| Ly      | 101       | 0.05%   |
| MDM     | 88        | 0.04%   |
| GREETD  | 57        | 0.03%   |
| NODM    | 34        | 0.02%   |
| FLY-DM  | 16        | 0.01%   |
| SLIMSKI | 11        | 0.005%  |
| LY-DM   | 11        | 0.005%  |
| EMPTTY  | 6         | 0.003%  |
| WDM     | 5         | 0.002%  |
| LDM     | 3         | 0.001%  |
| SU      | 2         | 0.001%  |
| XINIT   | 1         | 0.0004% |
| LYNDE   | 1         | 0.0004% |
| CDM     | 1         | 0.0004% |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 74773     | 34.16%  |
| Unknown | 42701     | 19.51%  |
| de_DE   | 14100     | 6.44%   |
| ru_RU   | 13500     | 6.17%   |
| en_GB   | 9241      | 4.22%   |
| pt_BR   | 9000      | 4.11%   |
| fr_FR   | 7836      | 3.58%   |
| it_IT   | 5042      | 2.3%    |
| es_ES   | 4094      | 1.87%   |
| C       | 3474      | 1.59%   |
| en_CA   | 3403      | 1.55%   |
| pl_PL   | 3069      | 1.4%    |
| en_IN   | 2899      | 1.32%   |
| en_AU   | 2593      | 1.18%   |
| es_MX   | 1428      | 0.65%   |
| nl_NL   | 1324      | 0.6%    |
| cs_CZ   | 1175      | 0.54%   |
| es_AR   | 1100      | 0.5%    |
| hu_HU   | 1021      | 0.47%   |
| zh_CN   | 848       | 0.39%   |
| pt_PT   | 787       | 0.36%   |
| de_AT   | 781       | 0.36%   |
| en_ZA   | 747       | 0.34%   |
| tr_TR   | 729       | 0.33%   |
| sv_SE   | 626       | 0.29%   |
| de_CH   | 565       | 0.26%   |
| ja_JP   | 556       | 0.25%   |
| ru_UA   | 527       | 0.24%   |
| es_CL   | 516       | 0.24%   |
| es_CO   | 509       | 0.23%   |
| fi_FI   | 483       | 0.22%   |
| en_NZ   | 478       | 0.22%   |
| en_IE   | 435       | 0.2%    |
| fr_CA   | 432       | 0.2%    |
| fr_BE   | 368       | 0.17%   |
| el_GR   | 367       | 0.17%   |
| ro_RO   | 357       | 0.16%   |
| nl_BE   | 321       | 0.15%   |
| da_DK   | 305       | 0.14%   |
| en_PH   | 290       | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 117559    | 53.9%   |
| EFI  | 100552    | 46.1%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type                | Computers | Percent |
|---------------------|-----------|---------|
| Ext4                | 152082    | 68.98%  |
| Unknown             | 21443     | 9.73%   |
| Overlay             | 18924     | 8.58%   |
| Btrfs               | 18536     | 8.41%   |
| Tmpfs               | 3656      | 1.66%   |
| Xfs                 | 2868      | 1.3%    |
| Zfs                 | 1454      | 0.66%   |
| Ext2                | 504       | 0.23%   |
| Ext3                | 411       | 0.19%   |
| F2fs                | 306       | 0.14%   |
| Aufs                | 79        | 0.04%   |
| Reiserfs            | 52        | 0.02%   |
| Jfs                 | 41        | 0.02%   |
| Rootfs              | 27        | 0.01%   |
| XXXXXXX             | 24        | 0.01%   |
| XXXXX               | 7         | 0.003%  |
| XXX4                | 7         | 0.003%  |
| SAMSUNG             | 6         | 0.003%  |
| Fuse.fuse-overlayfs | 5         | 0.002%  |
| XXXX                | 4         | 0.002%  |
| ExX4                | 3         | 0.001%  |
| XXXfs               | 2         | 0.001%  |
| XXX                 | 2         | 0.001%  |
| Ubifs               | 2         | 0.001%  |
| Ntfs                | 2         | 0.001%  |
| Xtrfs               | 1         | 0.0005% |
| Ufs                 | 1         | 0.0005% |
| SquXshfs            | 1         | 0.0005% |
| SquasXfs            | 1         | 0.0005% |
| OveXlay             | 1         | 0.0005% |
| Nilfs2              | 1         | 0.0005% |
| Nfs                 | 1         | 0.0005% |
| Lvm                 | 1         | 0.0005% |
| Fuse.sshfs          | 1         | 0.0005% |
| Fuse.snapfuse       | 1         | 0.0005% |
| Exfat               | 1         | 0.0005% |
| Bcachefs            | 1         | 0.0005% |
| 2G                  | 1         | 0.0005% |
| 20G                 | 1         | 0.0005% |
| 12G                 | 1         | 0.0005% |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 102804    | 46.69%  |
| GPT     | 78613     | 35.7%   |
| MBR     | 38778     | 17.61%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 185443    | 85.07%  |
| Yes       | 32541     | 14.93%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 154902    | 71.08%  |
| Yes       | 63030     | 28.92%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 37236     | 17.51%  |
| Lenovo                  | 27849     | 13.09%  |
| Hewlett-Packard         | 27278     | 12.82%  |
| Dell                    | 24912     | 11.71%  |
| Gigabyte Technology     | 15295     | 7.19%   |
| Acer                    | 12808     | 6.02%   |
| MSI                     | 12071     | 5.67%   |
| ASRock                  | 7908      | 3.72%   |
| Apple                   | 4946      | 2.33%   |
| Intel                   | 3755      | 1.77%   |
| Toshiba                 | 3382      | 1.59%   |
| Samsung Electronics     | 3051      | 1.43%   |
| Unknown                 | 2096      | 0.99%   |
| Sony                    | 1788      | 0.84%   |
| Fujitsu                 | 1566      | 0.74%   |
| HUAWEI                  | 1208      | 0.57%   |
| Raspberry Pi Foundation | 1188      | 0.56%   |
| Medion                  | 972       | 0.46%   |
| Pegatron                | 935       | 0.44%   |
| Valve                   | 925       | 0.43%   |
| Packard Bell            | 875       | 0.41%   |
| Google                  | 857       | 0.4%    |
| Foxconn                 | 849       | 0.4%    |
| Biostar                 | 830       | 0.39%   |
| ECS                     | 829       | 0.39%   |
| Supermicro              | 804       | 0.38%   |
| Positivo                | 778       | 0.37%   |
| Notebook                | 724       | 0.34%   |
| Microsoft               | 663       | 0.31%   |
| Fujitsu Siemens         | 608       | 0.29%   |
| Alienware               | 540       | 0.25%   |
| eMachines               | 461       | 0.22%   |
| Timi                    | 431       | 0.2%    |
| System76                | 405       | 0.19%   |
| TUXEDO                  | 368       | 0.17%   |
| AMI                     | 356       | 0.17%   |
| AZW                     | 347       | 0.16%   |
| LG Electronics          | 324       | 0.15%   |
| Gateway                 | 322       | 0.15%   |
| Clevo                   | 320       | 0.15%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                      | Computers | Percent |
|---------------------------|-----------|---------|
| Unknown                   | 2814      | 1.32%   |
| ASUS All Series           | 2083      | 0.98%   |
| Valve Jupiter             | 925       | 0.43%   |
| HP Notebook               | 767       | 0.36%   |
| HP Pavilion g6            | 539       | 0.25%   |
| HP Pavilion dv6           | 515       | 0.24%   |
| Dell OptiPlex 7010        | 421       | 0.2%    |
| Apple MacBook5,2          | 383       | 0.18%   |
| ASUS TUF Gaming X570-PLUS | 375       | 0.18%   |
| RPi Raspberry Pi          | 370       | 0.17%   |
| MSI MS-7C37               | 367       | 0.17%   |
| Gigabyte B450M DS3H       | 329       | 0.15%   |
| HP Pavilion 15            | 328       | 0.15%   |
| MSI MS-7C02               | 327       | 0.15%   |
| HP Pavilion dv7           | 323       | 0.15%   |
| ASUS PRIME A320M-K        | 311       | 0.15%   |
| HP Pavilion Notebook      | 304       | 0.14%   |
| Dell OptiPlex 9020        | 297       | 0.14%   |
| MSI MS-7817               | 296       | 0.14%   |
| Gigabyte 970A-DS3P        | 272       | 0.13%   |
| Dell Latitude E6420       | 259       | 0.12%   |
| MSI MS-7B86               | 258       | 0.12%   |
| Apple MacBookPro9,2       | 254       | 0.12%   |
| Dell OptiPlex 780         | 240       | 0.11%   |
| HP 15                     | 239       | 0.11%   |
| Apple MacBookAir7,2       | 238       | 0.11%   |
| Dell OptiPlex 790         | 235       | 0.11%   |
| Dell Latitude E6430       | 231       | 0.11%   |
| ASUS M5A78L-M/USB3        | 231       | 0.11%   |
| MSI MS-7721               | 228       | 0.11%   |
| Dell Latitude E6410       | 225       | 0.11%   |
| ASUS M5A97 R2.0           | 224       | 0.11%   |
| Apple MacBookPro8,1       | 224       | 0.11%   |
| MSI MS-7693               | 223       | 0.1%    |
| MSI MS-7A38               | 215       | 0.1%    |
| MSI MS-7C91               | 212       | 0.1%    |
| Dell OptiPlex 3020        | 212       | 0.1%    |
| Acer Nitro AN515-54       | 212       | 0.1%    |
| ASRock B450M Pro4         | 207       | 0.1%    |
| Dell XPS 15 7590          | 206       | 0.1%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 11695     | 5.5%    |
| Acer Aspire           | 8536      | 4.01%   |
| Dell Inspiron         | 6672      | 3.14%   |
| Dell Latitude         | 6168      | 2.9%    |
| Lenovo IdeaPad        | 5587      | 2.63%   |
| HP Pavilion           | 5134      | 2.41%   |
| Dell OptiPlex         | 3660      | 1.72%   |
| ASUS PRIME            | 3599      | 1.69%   |
| HP EliteBook          | 3236      | 1.52%   |
| ASUS ROG              | 3149      | 1.48%   |
| HP Compaq             | 2891      | 1.36%   |
| Toshiba Satellite     | 2834      | 1.33%   |
| Unknown               | 2814      | 1.32%   |
| Dell XPS              | 2693      | 1.27%   |
| HP ProBook            | 2583      | 1.21%   |
| ASUS VivoBook         | 2582      | 1.21%   |
| HP Laptop             | 2568      | 1.21%   |
| Dell Precision        | 2197      | 1.03%   |
| ASUS All              | 2083      | 0.98%   |
| ASUS TUF              | 1890      | 0.89%   |
| Lenovo ThinkCentre    | 1686      | 0.79%   |
| Dell Vostro           | 1480      | 0.7%    |
| HP ENVY               | 1284      | 0.6%    |
| RPi Raspberry         | 1186      | 0.56%   |
| Lenovo Yoga           | 1106      | 0.52%   |
| Acer Nitro            | 986       | 0.46%   |
| Lenovo Legion         | 943       | 0.44%   |
| Valve Jupiter         | 925       | 0.43%   |
| HP Notebook           | 770       | 0.36%   |
| ASUS ZenBook          | 759       | 0.36%   |
| ASUS M5A78L-M         | 738       | 0.35%   |
| Acer Swift            | 712       | 0.33%   |
| Fujitsu LIFEBOOK      | 680       | 0.32%   |
| Microsoft Surface     | 663       | 0.31%   |
| HP EliteDesk          | 661       | 0.31%   |
| Gigabyte X570         | 641       | 0.3%    |
| HP ZBook              | 615       | 0.29%   |
| Packard Bell EasyNote | 614       | 0.29%   |
| Gigabyte B450M        | 590       | 0.28%   |
| ASUS ASUS             | 579       | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 18446     | 8.67%   |
| 2012    | 18446     | 8.67%   |
| 2019    | 17493     | 8.22%   |
| 2020    | 16547     | 7.78%   |
| 2011    | 16528     | 7.77%   |
| 2013    | 15068     | 7.08%   |
| 2017    | 13179     | 6.2%    |
| 2021    | 12394     | 5.83%   |
| 2014    | 12106     | 5.69%   |
| 2010    | 12049     | 5.66%   |
| 2015    | 10476     | 4.92%   |
| 2016    | 10195     | 4.79%   |
| 2009    | 9918      | 4.66%   |
| 2008    | 9083      | 4.27%   |
| 2022    | 6900      | 3.24%   |
| 2007    | 6326      | 2.97%   |
| 2006    | 2934      | 1.38%   |
| Unknown | 1816      | 0.85%   |
| 2023    | 1165      | 0.55%   |
| 2005    | 1075      | 0.51%   |
| 2004    | 321       | 0.15%   |
| 2003    | 172       | 0.08%   |
| 2002    | 44        | 0.02%   |
| 2001    | 19        | 0.01%   |
| 2000    | 10        | 0.005%  |
| 1999    | 3         | 0.001%  |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 114250    | 53.71%  |
| Desktop        | 83006     | 39.02%  |
| Convertible    | 4577      | 2.15%   |
| Mini pc        | 2841      | 1.34%   |
| All in one     | 2676      | 1.26%   |
| Server         | 1850      | 0.87%   |
| Tablet         | 1692      | 0.8%    |
| System on chip | 1663      | 0.78%   |
| Phone          | 133       | 0.06%   |
| Stick pc       | 16        | 0.01%   |
| Other          | 5         | 0.002%  |
| Firewall       | 4         | 0.002%  |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 199621    | 93.18%  |
| Enabled  | 14610     | 6.82%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 211483    | 99.42%  |
| Yes  | 1238      | 0.58%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 47997     | 22.03%  |
| 3.01-4.0        | 45118     | 20.71%  |
| 16.01-24.0      | 38823     | 17.82%  |
| 8.01-16.0       | 38488     | 17.67%  |
| 32.01-64.0      | 18220     | 8.36%   |
| 1.01-2.0        | 11731     | 5.39%   |
| 64.01-256.0     | 5562      | 2.55%   |
| 2.01-3.0        | 5447      | 2.5%    |
| 24.01-32.0      | 3335      | 1.53%   |
| 0.51-1.0        | 2058      | 0.94%   |
| Unknown         | 435       | 0.2%    |
| More than 256.0 | 391       | 0.18%   |
| 0.01-0.5        | 217       | 0.1%    |
| 0               | 1         | 0.0005% |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 1.01-2.0        | 84521     | 35.31%  |
| 2.01-3.0        | 54000     | 22.56%  |
| 4.01-8.0        | 30165     | 12.6%   |
| 0.51-1.0        | 27721     | 11.58%  |
| 3.01-4.0        | 27149     | 11.34%  |
| 8.01-16.0       | 8483      | 3.54%   |
| 0.01-0.5        | 4423      | 1.85%   |
| 16.01-24.0      | 1288      | 0.54%   |
| Unknown         | 638       | 0.27%   |
| 24.01-32.0      | 468       | 0.2%    |
| 32.01-64.0      | 377       | 0.16%   |
| 64.01-256.0     | 135       | 0.06%   |
| More than 256.0 | 18        | 0.01%   |
| 0               | 10        | 0.004%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 133151    | 60.25%  |
| 2       | 54282     | 24.56%  |
| 3       | 16740     | 7.58%   |
| 4       | 7531      | 3.41%   |
| 5       | 3536      | 1.6%    |
| 0       | 2098      | 0.95%   |
| 6       | 1620      | 0.73%   |
| 7       | 790       | 0.36%   |
| 8       | 392       | 0.18%   |
| 9       | 224       | 0.1%    |
| 10      | 130       | 0.06%   |
| Unknown | 119       | 0.05%   |
| 11      | 104       | 0.05%   |
| 13      | 49        | 0.02%   |
| 12      | 49        | 0.02%   |
| 14      | 29        | 0.01%   |
| 17      | 17        | 0.01%   |
| 16      | 13        | 0.01%   |
| 18      | 11        | 0.005%  |
| 19      | 10        | 0.005%  |
| 15      | 10        | 0.005%  |
| 20      | 8         | 0.004%  |
| 27      | 7         | 0.003%  |
| 21      | 7         | 0.003%  |
| 36      | 6         | 0.003%  |
| 28      | 6         | 0.003%  |
| 25      | 6         | 0.003%  |
| 26      | 5         | 0.002%  |
| 24      | 5         | 0.002%  |
| 23      | 4         | 0.002%  |
| 32      | 3         | 0.001%  |
| 22      | 3         | 0.001%  |
| 97      | 2         | 0.001%  |
| 93      | 2         | 0.001%  |
| 29      | 2         | 0.001%  |
| 209     | 1         | 0.0005% |
| 87      | 1         | 0.0005% |
| 79      | 1         | 0.0005% |
| 71      | 1         | 0.0005% |
| 68      | 1         | 0.0005% |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 125662    | 58.39%  |
| Yes       | 89542     | 41.61%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 185824    | 87.11%  |
| No        | 27494     | 12.89%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 156814    | 73.13%  |
| No        | 57610     | 26.87%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 119367    | 55.32%  |
| No        | 96411     | 44.68%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 34383     | 15.96%  |
| Russia       | 26193     | 12.16%  |
| Germany      | 20141     | 9.35%   |
| Brazil       | 13105     | 6.08%   |
| France       | 9685      | 4.5%    |
| Unknown      | 8148      | 3.78%   |
| UK           | 7755      | 3.6%    |
| Italy        | 7573      | 3.52%   |
| Canada       | 5821      | 2.7%    |
| Spain        | 5501      | 2.55%   |
| Poland       | 5018      | 2.33%   |
| India        | 4536      | 2.11%   |
| Netherlands  | 4107      | 1.91%   |
| Hungary      | 3885      | 1.8%    |
| Australia    | 3372      | 1.57%   |
| Ukraine      | 3227      | 1.5%    |
| Mexico       | 2468      | 1.15%   |
| Switzerland  | 2209      | 1.03%   |
| Sweden       | 2122      | 0.99%   |
| Czechia      | 2103      | 0.98%   |
| Austria      | 1909      | 0.89%   |
| Argentina    | 1891      | 0.88%   |
| Belgium      | 1832      | 0.85%   |
| Turkey       | 1830      | 0.85%   |
| Romania      | 1790      | 0.83%   |
| Portugal     | 1572      | 0.73%   |
| Finland      | 1490      | 0.69%   |
| China        | 1440      | 0.67%   |
| Greece       | 1300      | 0.6%    |
| Indonesia    | 1281      | 0.59%   |
| Japan        | 1252      | 0.58%   |
| South Africa | 1091      | 0.51%   |
| Norway       | 1054      | 0.49%   |
| Colombia     | 1023      | 0.47%   |
| Bulgaria     | 996       | 0.46%   |
| Belarus      | 995       | 0.46%   |
| Denmark      | 961       | 0.45%   |
| Chile        | 947       | 0.44%   |
| Slovakia     | 788       | 0.37%   |
| Serbia       | 756       | 0.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Unknown           | 8195      | 3.55%   |
| Moscow            | 5490      | 2.38%   |
| St Petersburg     | 2266      | 0.98%   |
| Berlin            | 1834      | 0.79%   |
| Sao Paulo         | 1675      | 0.72%   |
| Budapest          | 1534      | 0.66%   |
| Paris             | 1496      | 0.65%   |
| Voronezh          | 1242      | 0.54%   |
| Warsaw            | 1153      | 0.5%    |
| Vienna            | 1120      | 0.48%   |
| Milan             | 1065      | 0.46%   |
| Sydney            | 949       | 0.41%   |
| Madrid            | 924       | 0.4%    |
| Munich            | 920       | 0.4%    |
| Rome              | 893       | 0.39%   |
| Hamburg           | 855       | 0.37%   |
| Novosibirsk       | 828       | 0.36%   |
| Prague            | 824       | 0.36%   |
| Bangor            | 809       | 0.35%   |
| Rio de Janeiro    | 807       | 0.35%   |
| Amsterdam         | 783       | 0.34%   |
| Kyiv              | 772       | 0.33%   |
| Pecherskoye       | 765       | 0.33%   |
| Melbourne         | 759       | 0.33%   |
| Krasnodar         | 721       | 0.31%   |
| Yekaterinburg     | 708       | 0.31%   |
| Istanbul          | 692       | 0.3%    |
| Athens            | 691       | 0.3%    |
| Helsinki          | 689       | 0.3%    |
| Frankfurt am Main | 683       | 0.3%    |
| Zurich            | 634       | 0.27%   |
| Barcelona         | 623       | 0.27%   |
| Toronto           | 594       | 0.26%   |
| Montreal          | 589       | 0.25%   |
| Bengaluru         | 579       | 0.25%   |
| London            | 574       | 0.25%   |
| Bucharest         | 573       | 0.25%   |
| Nizhniy Novgorod  | 533       | 0.23%   |
| Mexico City       | 519       | 0.22%   |
| Samara            | 518       | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 49677     | 78839  | 16.06%  |
| Seagate                     | 48635     | 76716  | 15.72%  |
| Samsung Electronics         | 44586     | 69677  | 14.41%  |
| Toshiba                     | 21004     | 28709  | 6.79%   |
| Kingston                    | 16630     | 22540  | 5.38%   |
| SanDisk                     | 14898     | 20040  | 4.82%   |
| Unknown                     | 12379     | 16906  | 4%      |
| Hitachi                     | 11551     | 15700  | 3.73%   |
| Crucial                     | 9985      | 14081  | 3.23%   |
| Intel                       | 7240      | 10364  | 2.34%   |
| SK hynix                    | 6698      | 8499   | 2.16%   |
| HGST                        | 5939      | 8642   | 1.92%   |
| A-DATA Technology           | 4407      | 5877   | 1.42%   |
| Micron Technology           | 4010      | 5115   | 1.3%    |
| China                       | 2810      | 3668   | 0.91%   |
| Apple                       | 2196      | 2870   | 0.71%   |
| Phison                      | 2109      | 2880   | 0.68%   |
| SPCC                        | 1851      | 2484   | 0.6%    |
| KIOXIA                      | 1787      | 2273   | 0.58%   |
| Fujitsu                     | 1707      | 2089   | 0.55%   |
| PNY                         | 1604      | 2139   | 0.52%   |
| Maxtor                      | 1584      | 2105   | 0.51%   |
| OCZ                         | 1470      | 1937   | 0.48%   |
| Silicon Motion              | 1422      | 1885   | 0.46%   |
| Transcend                   | 1271      | 1631   | 0.41%   |
| Intenso                     | 1263      | 1721   | 0.41%   |
| Patriot                     | 1184      | 1576   | 0.38%   |
| Phison Electronics          | 1179      | 1552   | 0.38%   |
| Micron/Crucial Technology   | 1150      | 1537   | 0.37%   |
| LITEON                      | 1112      | 1354   | 0.36%   |
| Unknown                     | 1058      | 1217   | 0.34%   |
| Corsair                     | 1009      | 1356   | 0.33%   |
| JMicron Technology          | 907       | 1092   | 0.29%   |
| GOODRAM                     | 891       | 1271   | 0.29%   |
| Kingston Technology Company | 839       | 1004   | 0.27%   |
| Apacer                      | 786       | 1009   | 0.25%   |
| Hewlett-Packard             | 691       | 1151   | 0.22%   |
| Plextor                     | 678       | 964    | 0.22%   |
| Team                        | 656       | 858    | 0.21%   |
| LITEONIT                    | 639       | 812    | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 3395      | 0.99%   |
| Seagate ST1000LM035-1RK172 1TB                      | 2542      | 0.74%   |
| Seagate ST500DM002-1BD142 500GB                     | 2498      | 0.73%   |
| Samsung SSD 860 EVO 500GB                           | 2267      | 0.66%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 2212      | 0.65%   |
| Samsung SSD 850 EVO 250GB                           | 2081      | 0.61%   |
| Unknown MMC Card  32GB                              | 2010      | 0.59%   |
| Kingston SA400S37120G 120GB SSD                     | 2008      | 0.59%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 1938      | 0.57%   |
| Toshiba MQ01ABD100 1TB                              | 1921      | 0.56%   |
| Seagate ST1000DM010-2EP102 1TB                      | 1833      | 0.54%   |
| Kingston SA400S37480G 480GB SSD                     | 1750      | 0.51%   |
| Unknown MMC Card  64GB                              | 1670      | 0.49%   |
| Toshiba MQ01ABF050 500GB                            | 1664      | 0.49%   |
| Samsung SSD 850 EVO 500GB                           | 1651      | 0.48%   |
| Seagate ST500LT012-1DG142 500GB                     | 1575      | 0.46%   |
| Toshiba DT01ACA100 1TB                              | 1539      | 0.45%   |
| Kingston SV300S37A120G 120GB SSD                    | 1534      | 0.45%   |
| Seagate ST2000DM008-2FR102 2TB                      | 1357      | 0.4%    |
| Toshiba MQ04ABF100 1TB                              | 1354      | 0.4%    |
| Crucial CT500MX500SSD1 500GB                        | 1354      | 0.4%    |
| Samsung SSD 860 EVO 1TB                             | 1353      | 0.4%    |
| HGST HTS721010A9E630 1TB                            | 1326      | 0.39%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 1317      | 0.38%   |
| Seagate ST9500325AS 500GB                           | 1270      | 0.37%   |
| Samsung SSD 860 EVO 250GB                           | 1256      | 0.37%   |
| Samsung NVMe SSD Drive 512GB                        | 1250      | 0.37%   |
| Crucial CT240BX500SSD1 240GB                        | 1219      | 0.36%   |
| Seagate ST3500418AS 500GB                           | 1206      | 0.35%   |
| Seagate ST1000DM003-1CH162 1TB                      | 1166      | 0.34%   |
| Samsung NVMe SSD Drive 500GB                        | 1157      | 0.34%   |
| Crucial CT1000MX500SSD1 1TB                         | 1147      | 0.34%   |
| Unknown                                             | 1058      | 0.31%   |
| Unknown SD/MMC/MS PRO 128GB                         | 1044      | 0.31%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 1021      | 0.3%    |
| Seagate ST1000DM003-1ER162 1TB                      | 1019      | 0.3%    |
| Samsung NVMe SSD Drive 1TB                          | 1004      | 0.29%   |
| Toshiba DT01ACA050 500GB                            | 1002      | 0.29%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 999       | 0.29%   |
| Unknown MMC Card  128GB                             | 984       | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 47820     | 75053  | 34.68%  |
| WDC                 | 41546     | 65985  | 30.13%  |
| Toshiba             | 16879     | 23024  | 12.24%  |
| Hitachi             | 11546     | 15693  | 8.37%   |
| Samsung Electronics | 6917      | 9882   | 5.02%   |
| HGST                | 5929      | 8485   | 4.3%    |
| Fujitsu             | 1689      | 2057   | 1.22%   |
| Maxtor              | 1526      | 2009   | 1.11%   |
| Unknown             | 1142      | 1585   | 0.83%   |
| Apple               | 662       | 777    | 0.48%   |
| SABRENT             | 379       | 461    | 0.27%   |
| Hewlett-Packard     | 184       | 403    | 0.13%   |
| External            | 146       | 183    | 0.11%   |
| Intenso             | 144       | 202    | 0.1%    |
| ASMT                | 138       | 270    | 0.1%    |
| USB3.0              | 111       | 132    | 0.08%   |
| IBM/Hitachi         | 87        | 102    | 0.06%   |
| JMicron Technology  | 79        | 156    | 0.06%   |
| ExcelStor           | 62        | 74     | 0.04%   |
| SSK                 | 57        | 63     | 0.04%   |
| ASMedia             | 57        | 78     | 0.04%   |
| HGST HTS            | 56        | 68     | 0.04%   |
| WD MediaMax         | 51        | 79     | 0.04%   |
| USB                 | 50        | 60     | 0.04%   |
| LaCie               | 50        | 76     | 0.04%   |
| HPE                 | 34        | 67     | 0.02%   |
| QUANTUM             | 24        | 26     | 0.02%   |
| Unknown             | 24        | 30     | 0.02%   |
| SAGE                | 23        | 30     | 0.02%   |
| KESU                | 23        | 33     | 0.02%   |
| ASMT109x            | 21        | 31     | 0.02%   |
| MARVELL             | 20        | 27     | 0.01%   |
| Maxone              | 19        | 24     | 0.01%   |
| StoreJet            | 17        | 18     | 0.01%   |
| Magnetic Data       | 16        | 18     | 0.01%   |
| Initio              | 16        | 16     | 0.01%   |
| IBM                 | 16        | 22     | 0.01%   |
| Pioneer             | 15        | 25     | 0.01%   |
| Apricorn            | 13        | 16     | 0.01%   |
| RSH-319             | 11        | 12     | 0.01%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 21226     | 31652  | 21.74%  |
| Kingston            | 13811     | 18664  | 14.14%  |
| Crucial             | 9058      | 12811  | 9.28%   |
| SanDisk             | 8893      | 11991  | 9.11%   |
| WDC                 | 5699      | 7663   | 5.84%   |
| A-DATA Technology   | 3559      | 4744   | 3.64%   |
| China               | 2780      | 3628   | 2.85%   |
| Intel               | 2753      | 3853   | 2.82%   |
| Micron Technology   | 1745      | 2300   | 1.79%   |
| SPCC                | 1656      | 2231   | 1.7%    |
| SK hynix            | 1549      | 2022   | 1.59%   |
| Toshiba             | 1546      | 2097   | 1.58%   |
| PNY                 | 1491      | 1996   | 1.53%   |
| OCZ                 | 1455      | 1896   | 1.49%   |
| Transcend           | 1170      | 1492   | 1.2%    |
| Patriot             | 1112      | 1492   | 1.14%   |
| Apple               | 1111      | 1295   | 1.14%   |
| LITEON              | 1009      | 1240   | 1.03%   |
| Intenso             | 949       | 1270   | 0.97%   |
| GOODRAM             | 859       | 1222   | 0.88%   |
| Apacer              | 698       | 901    | 0.71%   |
| Corsair             | 685       | 909    | 0.7%    |
| LITEONIT            | 639       | 812    | 0.65%   |
| Plextor             | 628       | 887    | 0.64%   |
| KingSpec            | 616       | 792    | 0.63%   |
| Team                | 586       | 762    | 0.6%    |
| JMicron Technology  | 517       | 576    | 0.53%   |
| Netac               | 514       | 721    | 0.53%   |
| Gigabyte Technology | 382       | 539    | 0.39%   |
| Hewlett-Packard     | 365       | 510    | 0.37%   |
| Lexar               | 360       | 427    | 0.37%   |
| ASMT                | 342       | 415    | 0.35%   |
| Unknown             | 332       | 379    | 0.34%   |
| Seagate             | 319       | 448    | 0.33%   |
| KingDian            | 299       | 411    | 0.31%   |
| Smartbuy            | 254       | 330    | 0.26%   |
| AMD                 | 224       | 291    | 0.23%   |
| Mushkin             | 212       | 314    | 0.22%   |
| TO Exter            | 196       | 247    | 0.2%    |
| Unknown             | 191       | 229    | 0.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 116528    | 207945 | 42.34%  |
| SSD     | 85088     | 133934 | 30.92%  |
| NVMe    | 58049     | 85853  | 21.09%  |
| MMC     | 11046     | 14848  | 4.01%   |
| Unknown | 4505      | 6539   | 1.64%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 165069    | 329887 | 67.12%  |
| NVMe | 57987     | 85595  | 23.58%  |
| SAS  | 11817     | 18789  | 4.81%   |
| MMC  | 11046     | 14848  | 4.49%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 126801    | 206375 | 60.42%  |
| 0.51-1.0        | 57923     | 88902  | 27.6%   |
| 1.01-2.0        | 13930     | 23297  | 6.64%   |
| 3.01-4.0        | 4264      | 8443   | 2.03%   |
| 4.01-10.0       | 3145      | 7275   | 1.5%    |
| 2.01-3.0        | 3111      | 5699   | 1.48%   |
| 10.01-20.0      | 641       | 1845   | 0.31%   |
| More than 100.0 | 16        | 18     | 0.01%   |
| 0               | 10        | 10     | 0.005%  |
| 20.01-50.0      | 7         | 11     | 0.003%  |
| 50.01-100.0     | 1         | 4      | 0.0005% |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 58395     | 25.37%  |
| 251-500        | 49717     | 21.6%   |
| 501-1000       | 32895     | 14.29%  |
| 1-20           | 19395     | 8.43%   |
| 1001-2000      | 16863     | 7.33%   |
| 51-100         | 16293     | 7.08%   |
| 21-50          | 10682     | 4.64%   |
| More than 3000 | 10168     | 4.42%   |
| Unknown        | 9649      | 4.19%   |
| 2001-3000      | 6119      | 2.66%   |
| 0              | 2         | 0.001%  |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 97726     | 41.14%  |
| 21-50          | 37967     | 15.98%  |
| 101-250        | 26983     | 11.36%  |
| 51-100         | 24593     | 10.35%  |
| 251-500        | 16524     | 6.96%   |
| 501-1000       | 11668     | 4.91%   |
| Unknown        | 9649      | 4.06%   |
| 1001-2000      | 6489      | 2.73%   |
| More than 3000 | 3547      | 1.49%   |
| 2001-3000      | 2327      | 0.98%   |
| 0              | 50        | 0.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 546       | 698    | 1.75%   |
| Seagate ST9500325AS 500GB           | 477       | 607    | 1.53%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 347       | 430    | 1.11%   |
| Seagate ST500LT012-9WS142 500GB     | 330       | 415    | 1.06%   |
| Seagate ST3500418AS 500GB           | 320       | 426    | 1.03%   |
| HGST HTS545050A7E680 500GB          | 265       | 351    | 0.85%   |
| Seagate ST500LT012-1DG142 500GB     | 264       | 314    | 0.85%   |
| Seagate ST9320325AS 320GB           | 242       | 301    | 0.78%   |
| Toshiba MQ01ABD100 1TB              | 212       | 253    | 0.68%   |
| Seagate ST1000LM035-1RK172 1TB      | 201       | 221    | 0.64%   |
| Kingston SV300S37A120G 120GB SSD    | 191       | 218    | 0.61%   |
| Seagate ST9250315AS 250GB           | 182       | 222    | 0.58%   |
| Seagate ST31000528AS 1TB            | 175       | 220    | 0.56%   |
| HGST HTS541010A9E680 1TB            | 175       | 217    | 0.56%   |
| WDC WD5000AAKX-001CA0 500GB         | 167       | 212    | 0.54%   |
| HGST HTS721010A9E630 1TB            | 161       | 192    | 0.52%   |
| Toshiba MQ01ABF050 500GB            | 157       | 202    | 0.5%    |
| Seagate ST3250410AS 250GB           | 153       | 196    | 0.49%   |
| HGST HTS545050A7E380 500GB          | 148       | 205    | 0.47%   |
| Seagate ST3250310AS 250GB           | 147       | 213    | 0.47%   |
| HGST HTS725050A7E630 500GB          | 138       | 173    | 0.44%   |
| Seagate ST1000DM003-1CH162 1TB      | 137       | 186    | 0.44%   |
| Hitachi HTS543232A7A384 320GB       | 137       | 164    | 0.44%   |
| Seagate ST31000524AS 1TB            | 131       | 165    | 0.42%   |
| SanDisk SSD U100 256GB              | 128       | 129    | 0.41%   |
| Seagate ST1000DM003-9YN162 1TB      | 126       | 147    | 0.4%    |
| Toshiba MQ01ABD050 500GB            | 123       | 144    | 0.39%   |
| Seagate ST9500420AS 500GB           | 120       | 150    | 0.38%   |
| Seagate ST320LT020-9YG142 320GB     | 119       | 168    | 0.38%   |
| Hitachi HTS547575A9E384 752GB       | 118       | 149    | 0.38%   |
| Hitachi HTS545050A7E380 500GB       | 116       | 140    | 0.37%   |
| WDC WD10EARS-00Y5B1 1TB             | 115       | 164    | 0.37%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 115       | 135    | 0.37%   |
| Seagate ST3320613AS 320GB           | 112       | 148    | 0.36%   |
| Hitachi HTS545050B9A300 500GB       | 112       | 145    | 0.36%   |
| Toshiba DT01ACA100 1TB              | 107       | 143    | 0.34%   |
| Hitachi HDS721010CLA332 1TB         | 105       | 128    | 0.34%   |
| Hitachi HTS547550A9E384 500GB       | 104       | 141    | 0.33%   |
| Seagate ST3500413AS 500GB           | 103       | 120    | 0.33%   |
| Seagate ST3160815AS 160GB           | 103       | 121    | 0.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8888      | 11873  | 29.59%  |
| WDC                 | 6681      | 9002   | 22.24%  |
| Hitachi             | 3145      | 3995   | 10.47%  |
| Samsung Electronics | 2361      | 3128   | 7.86%   |
| Toshiba             | 2351      | 2896   | 7.83%   |
| HGST                | 1106      | 1421   | 3.68%   |
| Kingston            | 708       | 852    | 2.36%   |
| SanDisk             | 582       | 654    | 1.94%   |
| Maxtor              | 516       | 640    | 1.72%   |
| Intel               | 474       | 630    | 1.58%   |
| Crucial             | 386       | 494    | 1.29%   |
| SK hynix            | 322       | 386    | 1.07%   |
| Fujitsu             | 299       | 353    | 1%      |
| A-DATA Technology   | 288       | 360    | 0.96%   |
| Micron Technology   | 182       | 232    | 0.61%   |
| OCZ                 | 166       | 214    | 0.55%   |
| China               | 131       | 151    | 0.44%   |
| SPCC                | 116       | 137    | 0.39%   |
| Corsair             | 95        | 135    | 0.32%   |
| Apple               | 75        | 84     | 0.25%   |
| LITEON              | 73        | 83     | 0.24%   |
| KingSpec            | 54        | 68     | 0.18%   |
| LITEONIT            | 52        | 66     | 0.17%   |
| Hewlett-Packard     | 50        | 56     | 0.17%   |
| IBM/Hitachi         | 41        | 48     | 0.14%   |
| Netac               | 39        | 42     | 0.13%   |
| Plextor             | 38        | 55     | 0.13%   |
| Kingmax             | 38        | 66     | 0.13%   |
| Intenso             | 38        | 46     | 0.13%   |
| Unknown             | 34        | 38     | 0.11%   |
| Transcend           | 33        | 48     | 0.11%   |
| ASMT                | 33        | 48     | 0.11%   |
| Patriot             | 25        | 28     | 0.08%   |
| Apacer              | 25        | 33     | 0.08%   |
| AMD                 | 23        | 28     | 0.08%   |
| PNY                 | 19        | 31     | 0.06%   |
| Unknown             | 18        | 23     | 0.06%   |
| Mushkin             | 18        | 18     | 0.06%   |
| SSSTC               | 17        | 20     | 0.06%   |
| ExcelStor           | 16        | 18     | 0.05%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8886      | 11869  | 35.97%  |
| WDC                 | 6458      | 8722   | 26.14%  |
| Hitachi             | 3145      | 3995   | 12.73%  |
| Toshiba             | 2279      | 2809   | 9.23%   |
| Samsung Electronics | 1754      | 2341   | 7.1%    |
| HGST                | 1106      | 1421   | 4.48%   |
| Maxtor              | 516       | 640    | 2.09%   |
| Fujitsu             | 299       | 353    | 1.21%   |
| Apple               | 51        | 56     | 0.21%   |
| IBM/Hitachi         | 41        | 48     | 0.17%   |
| Hewlett-Packard     | 29        | 35     | 0.12%   |
| ExcelStor           | 16        | 18     | 0.06%   |
| ASMT                | 15        | 23     | 0.06%   |
| WD MediaMax         | 13        | 18     | 0.05%   |
| IBM                 | 12        | 14     | 0.05%   |
| Unknown             | 10        | 15     | 0.04%   |
| HGST HTS            | 7         | 9      | 0.03%   |
| MARSHAL             | 6         | 7      | 0.02%   |
| ASMedia             | 6         | 9      | 0.02%   |
| USB3.0              | 5         | 6      | 0.02%   |
| QUANTUM             | 5         | 5      | 0.02%   |
| Initio              | 4         | 5      | 0.02%   |
| HPE                 | 4         | 5      | 0.02%   |
| Unknown             | 4         | 5      | 0.02%   |
| MDT                 | 3         | 3      | 0.01%   |
| JMicron Technology  | 3         | 4      | 0.01%   |
| SAGE                | 2         | 2      | 0.01%   |
| SABRENT             | 2         | 2      | 0.01%   |
| Magnetic Data       | 2         | 2      | 0.01%   |
| LaCie               | 2         | 2      | 0.01%   |
| Intenso             | 2         | 2      | 0.01%   |
| USB                 | 1         | 1      | 0.004%  |
| TPH00100500GB       | 1         | 1      | 0.004%  |
| RSH-339             | 1         | 1      | 0.004%  |
| RSH-319             | 1         | 1      | 0.004%  |
| MaxDigital          | 1         | 1      | 0.004%  |
| ICY BOX             | 1         | 2      | 0.004%  |
| IB                  | 1         | 1      | 0.004%  |
| FEASSO              | 1         | 2      | 0.004%  |
| External            | 1         | 1      | 0.004%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 22794     | 32464  | 81.19%  |
| SSD     | 4642      | 5832   | 16.53%  |
| NVMe    | 635       | 804    | 2.26%   |
| Unknown | 5         | 5      | 0.02%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST3500418AS 500GB           | 20        | 24     | 2.47%   |
| Seagate ST31000528AS 1TB            | 18        | 22     | 2.22%   |
| Samsung Electronics HD502HJ 500GB   | 12        | 17     | 1.48%   |
| Hitachi HDS721010DLE630 1TB         | 10        | 19     | 1.23%   |
| Seagate ST500DM002-1BD142 500GB     | 9         | 10     | 1.11%   |
| Samsung Electronics SSD 980 1TB     | 9         | 10     | 1.11%   |
| Samsung Electronics HM321HI 320GB   | 9         | 11     | 1.11%   |
| Seagate ST9500325AS 500GB           | 8         | 10     | 0.99%   |
| Seagate ST9320325AS 320GB           | 8         | 9      | 0.99%   |
| Seagate ST31000524AS 1TB            | 8         | 10     | 0.99%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 8         | 8      | 0.99%   |
| HGST HTS545050A7E680 500GB          | 8         | 8      | 0.99%   |
| Seagate ST500LT012-1DG142 500GB     | 7         | 7      | 0.86%   |
| Seagate ST3250318AS 250GB           | 7         | 11     | 0.86%   |
| Samsung Electronics SSD 980 500GB   | 7         | 8      | 0.86%   |
| Samsung Electronics HD103SJ 1TB     | 7         | 9      | 0.86%   |
| Hitachi HTS545050A7E380 500GB       | 7         | 8      | 0.86%   |
| HGST HTS721010A9E630 1TB            | 7         | 8      | 0.86%   |
| Apple HDD HTS541010A9E662 1TB       | 7         | 7      | 0.86%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 6         | 7      | 0.74%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 6         | 7      | 0.74%   |
| Seagate ST3500412AS 500GB           | 6         | 8      | 0.74%   |
| Samsung Electronics HD502IJ 500GB   | 6         | 6      | 0.74%   |
| Samsung Electronics HD252HJ 250GB   | 6         | 10     | 0.74%   |
| Hitachi HTS547550A9E384 500GB       | 6         | 7      | 0.74%   |
| HGST HTS545050A7E380 500GB          | 6         | 6      | 0.74%   |
| Toshiba MQ01ABD100 1TB              | 5         | 5      | 0.62%   |
| Toshiba MQ01ABD050 500GB            | 5         | 5      | 0.62%   |
| Toshiba MK6465GSX 640GB             | 5         | 7      | 0.62%   |
| Toshiba MK3265GSX 320GB             | 5         | 5      | 0.62%   |
| Toshiba DT01ACA100 1TB              | 5         | 6      | 0.62%   |
| Seagate ST3500410AS 500GB           | 5         | 7      | 0.62%   |
| Seagate ST3320613AS 320GB           | 5         | 6      | 0.62%   |
| Samsung Electronics HD322GJ 320GB   | 5         | 6      | 0.62%   |
| WDC WD5000BEVT-22A0RT0 500GB        | 4         | 10     | 0.49%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 4         | 4      | 0.49%   |
| Toshiba MK5065GSX 500GB             | 4         | 4      | 0.49%   |
| Toshiba DT01ACA050 500GB            | 4         | 4      | 0.49%   |
| Seagate ST9250315AS 250GB           | 4         | 4      | 0.49%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 4         | 4      | 0.49%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor                  | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Seagate                 | 205       | 249    | 25.4%   |
| WDC                     | 193       | 228    | 23.92%  |
| Samsung Electronics     | 151       | 181    | 18.71%  |
| Toshiba                 | 86        | 98     | 10.66%  |
| Hitachi                 | 66        | 79     | 8.18%   |
| HGST                    | 34        | 37     | 4.21%   |
| Maxtor                  | 12        | 12     | 1.49%   |
| Apple                   | 9         | 10     | 1.12%   |
| Intel                   | 7         | 7      | 0.87%   |
| Crucial                 | 6         | 6      | 0.74%   |
| Kingston                | 4         | 4      | 0.5%    |
| Hewlett-Packard         | 4         | 8      | 0.5%    |
| SK hynix                | 2         | 2      | 0.25%   |
| Intenso                 | 2         | 2      | 0.25%   |
| Fujitsu                 | 2         | 2      | 0.25%   |
| A-DATA Technology       | 2         | 2      | 0.25%   |
| Zheino                  | 1         | 1      | 0.12%   |
| Unknown                 | 1         | 1      | 0.12%   |
| Union Memory (Shenzhen) | 1         | 1      | 0.12%   |
| Transcend               | 1         | 1      | 0.12%   |
| TPH00800640GB           | 1         | 1      | 0.12%   |
| SPCC                    | 1         | 1      | 0.12%   |
| SanDisk                 | 1         | 1      | 0.12%   |
| Phison                  | 1         | 1      | 0.12%   |
| Patriot                 | 1         | 2      | 0.12%   |
| OCZ-AGIL                | 1         | 1      | 0.12%   |
| OCZ                     | 1         | 1      | 0.12%   |
| Mushkin                 | 1         | 1      | 0.12%   |
| Micron Technology       | 1         | 1      | 0.12%   |
| LITEON                  | 1         | 2      | 0.12%   |
| KingDian                | 1         | 4      | 0.12%   |
| JMicron Technology      | 1         | 1      | 0.12%   |
| Inland                  | 1         | 1      | 0.12%   |
| IBM-ESXS                | 1         | 2      | 0.12%   |
| GOODRAM                 | 1         | 1      | 0.12%   |
| External                | 1         | 1      | 0.12%   |
| Corsair                 | 1         | 1      | 0.12%   |
| Acer                    | 1         | 1      | 0.12%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 115470    | 235182 | 49.19%  |
| Works    | 91125     | 173865 | 38.82%  |
| Malfunc  | 27316     | 39105  | 11.64%  |
| Failed   | 800       | 955    | 0.34%   |
| Limited  | 9         | 9      | 0.004%  |
| Fixed    | 3         | 3      | 0.001%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 141030    | 53.75%  |
| AMD                              | 41789     | 15.93%  |
| Samsung Electronics              | 20636     | 7.86%   |
| SanDisk                          | 9270      | 3.53%   |
| Nvidia                           | 5123      | 1.95%   |
| SK hynix                         | 4986      | 1.9%    |
| ASMedia Technology               | 4019      | 1.53%   |
| Phison Electronics               | 3972      | 1.51%   |
| Kingston Technology Company      | 3756      | 1.43%   |
| JMicron Technology               | 3513      | 1.34%   |
| Marvell Technology Group         | 3176      | 1.21%   |
| Toshiba America Info Systems     | 2785      | 1.06%   |
| Micron Technology                | 2325      | 0.89%   |
| Micron/Crucial Technology        | 2063      | 0.79%   |
| Silicon Motion                   | 1942      | 0.74%   |
| KIOXIA                           | 1881      | 0.72%   |
| ADATA Technology                 | 1573      | 0.6%    |
| VIA Technologies                 | 1019      | 0.39%   |
| LSI Logic / Symbios Logic        | 788       | 0.3%    |
| Realtek Semiconductor            | 780       | 0.3%    |
| Broadcom / LSI                   | 652       | 0.25%   |
| Silicon Integrated Systems [SiS] | 590       | 0.22%   |
| Union Memory (Shenzhen)          | 516       | 0.2%    |
| Solid State Storage Technology   | 462       | 0.18%   |
| Apple                            | 428       | 0.16%   |
| Silicon Image                    | 369       | 0.14%   |
| Lite-On Technology               | 328       | 0.13%   |
| MAXIO Technology (Hangzhou)      | 322       | 0.12%   |
| Seagate Technology               | 285       | 0.11%   |
| Hewlett-Packard                  | 250       | 0.1%    |
| Adaptec                          | 242       | 0.09%   |
| Shenzhen Longsys Electronics     | 206       | 0.08%   |
| Lenovo                           | 179       | 0.07%   |
| O2 Micro                         | 142       | 0.05%   |
| INNOGRIT                         | 124       | 0.05%   |
| Integrated Technology Express    | 122       | 0.05%   |
| Yangtze Memory Technologies      | 117       | 0.04%   |
| Biwin Storage Technology         | 71        | 0.03%   |
| Netac Technology                 | 66        | 0.03%   |
| OCZ Technology Group             | 44        | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 26573     | 8.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 10366     | 3.34%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 10037     | 3.23%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 9875      | 3.18%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8998      | 2.9%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 7033      | 2.27%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 6951      | 2.24%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5731      | 1.85%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5562      | 1.79%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5556      | 1.79%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5208      | 1.68%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4993      | 1.61%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4728      | 1.52%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4709      | 1.52%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 4577      | 1.47%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 4355      | 1.4%    |
| Samsung NVMe SSD Controller 980                                                         | 3923      | 1.26%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 3810      | 1.23%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3761      | 1.21%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3705      | 1.19%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3665      | 1.18%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3452      | 1.11%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 3349      | 1.08%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 3241      | 1.04%   |
| Intel SATA Controller [RAID mode]                                                       | 2994      | 0.96%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 2941      | 0.95%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 2836      | 0.91%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2781      | 0.9%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2764      | 0.89%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2645      | 0.85%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2627      | 0.85%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2555      | 0.82%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2512      | 0.81%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2458      | 0.79%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2451      | 0.79%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 2398      | 0.77%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 2326      | 0.75%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2165      | 0.7%    |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 2122      | 0.68%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2065      | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 152294    | 57.13%  |
| NVMe | 58389     | 21.9%   |
| IDE  | 37879     | 14.21%  |
| RAID | 16587     | 6.22%   |
| SAS  | 970       | 0.36%   |
| SCSI | 454       | 0.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 158670    | 74.59%  |
| AMD                      | 51992     | 24.44%  |
| ARM                      | 1777      | 0.84%   |
| QUALCOMM                 | 70        | 0.03%   |
| CentaurHauls             | 68        | 0.03%   |
| Unknown                  | 64        | 0.03%   |
| PHYTIUM                  | 23        | 0.01%   |
| sifive,u74-mc            | 11        | 0.01%   |
| HiSilicon                | 6         | 0.003%  |
| Marvell Semiconductor    | 5         | 0.002%  |
| CHRP IBM,8233-E8B        | 5         | 0.002%  |
| Loongson                 | 4         | 0.002%  |
| thead,c906               | 3         | 0.001%  |
| sifive,bullet0           | 3         | 0.001%  |
| PowerNV C1P9S01 REV 1.01 | 3         | 0.001%  |
| PowerBook5,6             | 2         | 0.001%  |
| MIPS                     | 2         | 0.001%  |
| CHRP IBM,9131-52A        | 2         | 0.001%  |
| PowerNV FP5466G2         | 1         | 0.0005% |
| PowerNV C829UAG3         | 1         | 0.0005% |
| PowerMac8,1              | 1         | 0.0005% |
| PowerMac7,2              | 1         | 0.0005% |
| PowerMac3,6              | 1         | 0.0005% |
| PowerMac11,2             | 1         | 0.0005% |
| PowerMac10,2             | 1         | 0.0005% |
| PowerBook6,7             | 1         | 0.0005% |
| PowerBook5,5             | 1         | 0.0005% |
| PowerBook5,4             | 1         | 0.0005% |
| PowerBook3,4             | 1         | 0.0005% |
| MBE8C-PC                 | 1         | 0.0005% |
| IBM/S390                 | 1         | 0.0005% |
| GenuineTMx86             | 1         | 0.0005% |
| FSP-1                    | 1         | 0.0005% |
| Elbrus-MCST              | 1         | 0.0005% |
| E8C/EATX                 | 1         | 0.0005% |
| E8C-SWTX                 | 1         | 0.0005% |
| E8C-mITX                 | 1         | 0.0005% |
| AppliedMicro             | 1         | 0.0005% |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 2076      | 0.97%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1781      | 0.83%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1777      | 0.83%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1755      | 0.82%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1701      | 0.8%    |
| AMD Ryzen 5 3600 6-Core Processor             | 1494      | 0.7%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1410      | 0.66%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1399      | 0.66%   |
| ARM Processor                                 | 1261      | 0.59%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1255      | 0.59%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1255      | 0.59%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1219      | 0.57%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1211      | 0.57%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1202      | 0.56%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1145      | 0.54%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1144      | 0.54%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 1110      | 0.52%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1106      | 0.52%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1089      | 0.51%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 1016      | 0.48%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 1012      | 0.47%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1011      | 0.47%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1001      | 0.47%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 993       | 0.46%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 957       | 0.45%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 925       | 0.43%   |
| AMD Custom APU 0405                           | 925       | 0.43%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 898       | 0.42%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 896       | 0.42%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 829       | 0.39%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 828       | 0.39%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 821       | 0.38%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 817       | 0.38%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 794       | 0.37%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 793       | 0.37%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 791       | 0.37%   |
| AMD FX-8350 Eight-Core Processor              | 766       | 0.36%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 750       | 0.35%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 743       | 0.35%   |
| AMD FX-6300 Six-Core Processor                | 739       | 0.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 43602     | 20.44%  |
| Intel Core i7           | 35214     | 16.51%  |
| Intel Core i3           | 17227     | 8.08%   |
| Other                   | 13474     | 6.32%   |
| AMD Ryzen 5             | 11189     | 5.25%   |
| Intel Celeron           | 11114     | 5.21%   |
| Intel Core 2 Duo        | 10310     | 4.83%   |
| AMD Ryzen 7             | 8516      | 3.99%   |
| Intel Pentium           | 6482      | 3.04%   |
| Intel Xeon              | 5329      | 2.5%    |
| Intel Atom              | 4538      | 2.13%   |
| AMD FX                  | 3638      | 1.71%   |
| Intel Pentium Dual-Core | 3143      | 1.47%   |
| AMD Ryzen 9             | 2894      | 1.36%   |
| AMD Ryzen 3             | 2242      | 1.05%   |
| Intel Core 2 Quad       | 2169      | 1.02%   |
| AMD A6                  | 1865      | 0.87%   |
| AMD A8                  | 1803      | 0.85%   |
| Intel Core 2            | 1555      | 0.73%   |
| AMD A10                 | 1532      | 0.72%   |
| AMD Athlon 64 X2        | 1529      | 0.72%   |
| AMD A4                  | 1492      | 0.7%    |
| Intel Pentium Dual      | 1466      | 0.69%   |
| AMD Athlon II X2        | 1352      | 0.63%   |
| AMD Phenom II X4        | 1262      | 0.59%   |
| Intel Core i9           | 1177      | 0.55%   |
| Intel Pentium 4         | 1021      | 0.48%   |
| AMD E                   | 929       | 0.44%   |
| Intel Genuine           | 857       | 0.4%    |
| AMD Ryzen 7 PRO         | 766       | 0.36%   |
| AMD E1                  | 766       | 0.36%   |
| AMD Athlon              | 761       | 0.36%   |
| Intel Pentium Silver    | 757       | 0.35%   |
| AMD Athlon II X4        | 623       | 0.29%   |
| AMD E2                  | 580       | 0.27%   |
| AMD Ryzen 5 PRO         | 491       | 0.23%   |
| AMD Phenom II X6        | 484       | 0.23%   |
| AMD Ryzen Threadripper  | 479       | 0.22%   |
| Intel Pentium D         | 471       | 0.22%   |
| AMD Sempron             | 400       | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 90336     | 42.23%  |
| 4       | 72663     | 33.97%  |
| 6       | 18710     | 8.75%   |
| 8       | 13671     | 6.39%   |
| 1       | 6812      | 3.18%   |
| 12      | 3140      | 1.47%   |
| Unknown | 2116      | 0.99%   |
| 3       | 1659      | 0.78%   |
| 16      | 1571      | 0.73%   |
| 10      | 1222      | 0.57%   |
| 14      | 926       | 0.43%   |
| 24      | 376       | 0.18%   |
| 32      | 180       | 0.08%   |
| 20      | 171       | 0.08%   |
| 28      | 74        | 0.03%   |
| 18      | 49        | 0.02%   |
| 64      | 46        | 0.02%   |
| 40      | 43        | 0.02%   |
| 48      | 27        | 0.01%   |
| 5       | 27        | 0.01%   |
| 36      | 26        | 0.01%   |
| 44      | 16        | 0.01%   |
| 128     | 15        | 0.01%   |
| 96      | 9         | 0.004%  |
| 22      | 8         | 0.004%  |
| 56      | 7         | 0.003%  |
| 80      | 4         | 0.002%  |
| 52      | 4         | 0.002%  |
| 192     | 3         | 0.001%  |
| 104     | 2         | 0.001%  |
| 26      | 2         | 0.001%  |
| 7       | 2         | 0.001%  |
| 384     | 1         | 0.0005% |
| 120     | 1         | 0.0005% |
| 72      | 1         | 0.0005% |
| 68      | 1         | 0.0005% |
| 15      | 1         | 0.0005% |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 210135    | 98.73%  |
| 2       | 2210      | 1.04%   |
| Unknown | 379       | 0.18%   |
| 4       | 70        | 0.03%   |
| 3       | 34        | 0.02%   |
| 8       | 4         | 0.002%  |
| 0       | 3         | 0.001%  |
| 16      | 2         | 0.001%  |
| 14      | 1         | 0.0005% |
| 6       | 1         | 0.0005% |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 132553    | 61.99%  |
| 1       | 79067     | 36.98%  |
| Unknown | 2116      | 0.99%   |
| 4       | 52        | 0.02%   |
| 8       | 26        | 0.01%   |
| 12      | 6         | 0.003%  |
| 16      | 2         | 0.001%  |
| 6       | 2         | 0.001%  |
| 112     | 1         | 0.0005% |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 205858    | 96.41%  |
| Unknown        | 4854      | 2.27%   |
| 32-bit         | 2450      | 1.15%   |
| 64-bit         | 363       | 0.17%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 53386     | 24.09%  |
| 0x206a7    | 13084     | 5.9%    |
| 0x306a9    | 12294     | 5.55%   |
| 0x1067a    | 8966      | 4.05%   |
| 0x306c3    | 8908      | 4.02%   |
| 0x906ea    | 4909      | 2.22%   |
| 0x806ea    | 4262      | 1.92%   |
| 0x806ec    | 4027      | 1.82%   |
| 0x40651    | 4022      | 1.82%   |
| 0x506e3    | 3819      | 1.72%   |
| 0x20655    | 3737      | 1.69%   |
| 0x806e9    | 3674      | 1.66%   |
| 0x806c1    | 3637      | 1.64%   |
| 0x406e3    | 3561      | 1.61%   |
| 0x906e9    | 3319      | 1.5%    |
| 0x6fd      | 3186      | 1.44%   |
| 0x306d4    | 3182      | 1.44%   |
| 0x010000c8 | 2517      | 1.14%   |
| 0x08701021 | 2389      | 1.08%   |
| 0x10676    | 2291      | 1.03%   |
| 0x30678    | 2259      | 1.02%   |
| 0x08108109 | 2200      | 0.99%   |
| 0x406c4    | 1915      | 0.86%   |
| 0x06001119 | 1839      | 0.83%   |
| 0x0a50000c | 1817      | 0.82%   |
| 0x0800820d | 1697      | 0.77%   |
| 0x06000852 | 1652      | 0.75%   |
| 0x6fb      | 1589      | 0.72%   |
| 0x20652    | 1561      | 0.7%    |
| 0x706e5    | 1397      | 0.63%   |
| 0x08600106 | 1365      | 0.62%   |
| 0xa0652    | 1308      | 0.59%   |
| 0x706a1    | 1248      | 0.56%   |
| 0x08108102 | 1244      | 0.56%   |
| 0x106ca    | 1178      | 0.53%   |
| 0x506c9    | 1177      | 0.53%   |
| 0x106e5    | 1159      | 0.52%   |
| 0x906ed    | 1146      | 0.52%   |
| 0x08701013 | 1107      | 0.5%    |
| 0x806eb    | 1106      | 0.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 30247     | 14.18%  |
| Haswell          | 17527     | 8.21%   |
| SandyBridge      | 16505     | 7.74%   |
| IvyBridge        | 15782     | 7.4%    |
| Penryn           | 13213     | 6.19%   |
| Skylake          | 10411     | 4.88%   |
| Zen 2            | 8193      | 3.84%   |
| Unknown          | 8183      | 3.84%   |
| Core             | 8029      | 3.76%   |
| Westmere         | 7054      | 3.31%   |
| Zen+             | 6676      | 3.13%   |
| Silvermont       | 6596      | 3.09%   |
| K10              | 5797      | 2.72%   |
| Zen 3            | 5728      | 2.68%   |
| TigerLake        | 5163      | 2.42%   |
| Piledriver       | 5146      | 2.41%   |
| Broadwell        | 4589      | 2.15%   |
| CometLake        | 4102      | 1.92%   |
| Zen              | 3944      | 1.85%   |
| IceLake          | 2956      | 1.39%   |
| Goldmont plus    | 2874      | 1.35%   |
| K8 Hammer        | 2840      | 1.33%   |
| Excavator        | 2535      | 1.19%   |
| Alderlake Hybrid | 2430      | 1.14%   |
| Bonnell          | 2354      | 1.1%    |
| Nehalem          | 2178      | 1.02%   |
| NetBurst         | 1831      | 0.86%   |
| Bobcat           | 1800      | 0.84%   |
| Goldmont         | 1573      | 0.74%   |
| Puma             | 1383      | 0.65%   |
| P6               | 1094      | 0.51%   |
| K10 Llano        | 1002      | 0.47%   |
| Jaguar           | 985       | 0.46%   |
| Steamroller      | 968       | 0.45%   |
| Bulldozer        | 748       | 0.35%   |
| Tremont          | 434       | 0.2%    |
| K8 & K10 hybrid  | 395       | 0.19%   |
| K6               | 65        | 0.03%   |
| Gracemont        | 33        | 0.02%   |
| Sapphire Rapids  | 4         | 0.002%  |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 118181    | 47.55%  |
| Nvidia                                       | 70040     | 28.18%  |
| AMD                                          | 57623     | 23.18%  |
| Matrox Electronics Systems                   | 1089      | 0.44%   |
| ASPEED Technology                            | 784       | 0.32%   |
| Silicon Integrated Systems [SiS]             | 369       | 0.15%   |
| VIA Technologies                             | 260       | 0.1%    |
| ATI Technologies                             | 78        | 0.03%   |
| XGI Technology (eXtreme Graphics Innovation) | 34        | 0.01%   |
| S3 Graphics                                  | 25        | 0.01%   |
| Zhaoxin                                      | 16        | 0.01%   |
| Silicon Motion                               | 14        | 0.01%   |
| Huawei Technologies                          | 11        | 0.004%  |
| Loongson Technology                          | 7         | 0.003%  |
| Neomagic                                     | 5         | 0.002%  |
| Red Hat                                      | 3         | 0.001%  |
| Phytium Technology                           | 3         | 0.001%  |
| Trident Microsystems                         | 2         | 0.001%  |
| NVidia / SGS Thomson (Joint Venture)         | 2         | 0.001%  |
| Conexant Systems                             | 2         | 0.001%  |
| Nanjing Ruixinview Technology                | 1         | 0.0004% |
| Moore Threads Technology                     | 1         | 0.0004% |
| Jingjia Microelectronics                     | 1         | 0.0004% |
| Dome Imaging Systems                         | 1         | 0.0004% |
| Cirrus Logic                                 | 1         | 0.0004% |
| Alliance Semiconductor                       | 1         | 0.0004% |
| 3DLabs                                       | 1         | 0.0004% |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 11938     | 4.63%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 8787      | 3.41%   |
| Intel UHD Graphics 620                                                                   | 5028      | 1.95%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5025      | 1.95%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4539      | 1.76%   |
| Intel HD Graphics 620                                                                    | 4265      | 1.65%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4116      | 1.6%    |
| Intel Core Processor Integrated Graphics Controller                                      | 4098      | 1.59%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4091      | 1.59%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3873      | 1.5%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3863      | 1.5%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3586      | 1.39%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3566      | 1.38%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3555      | 1.38%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3492      | 1.35%   |
| AMD Renoir                                                                               | 3264      | 1.27%   |
| Intel HD Graphics 5500                                                                   | 3247      | 1.26%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3071      | 1.19%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3012      | 1.17%   |
| Intel HD Graphics 530                                                                    | 2864      | 1.11%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2808      | 1.09%   |
| Intel HD Graphics 630                                                                    | 2686      | 1.04%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2617      | 1.02%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2300      | 0.89%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2295      | 0.89%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1950      | 0.76%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1950      | 0.76%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1922      | 0.75%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1858      | 0.72%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1818      | 0.71%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1818      | 0.71%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1736      | 0.67%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1669      | 0.65%   |
| AMD Lucienne                                                                             | 1568      | 0.61%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1480      | 0.57%   |
| Nvidia GT218 [GeForce 210]                                                               | 1469      | 0.57%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1432      | 0.56%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1406      | 0.55%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1341      | 0.52%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1334      | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 85125     | 39.63%  |
| 1 x AMD                  | 44986     | 20.95%  |
| 1 x Nvidia               | 41136     | 19.15%  |
| Intel + Nvidia           | 24948     | 11.62%  |
| Intel + AMD              | 5598      | 2.61%   |
| 2 x AMD                  | 3929      | 1.83%   |
| AMD + Nvidia             | 3127      | 1.46%   |
| Other                    | 2131      | 0.99%   |
| 1 x Matrox               | 938       | 0.44%   |
| 1 x ASPEED               | 570       | 0.27%   |
| 2 x Nvidia               | 549       | 0.26%   |
| 2 x Intel                | 438       | 0.2%    |
| 1 x SiS                  | 368       | 0.17%   |
| 1 x VIA                  | 258       | 0.12%   |
| Nvidia + ASPEED          | 153       | 0.07%   |
| Nvidia + Matrox          | 105       | 0.05%   |
| AMD + ASPEED             | 46        | 0.02%   |
| Intel + 2 x Nvidia       | 44        | 0.02%   |
| AMD + Matrox             | 44        | 0.02%   |
| 1 x XGI                  | 25        | 0.01%   |
| Intel + AMD + 1 x Nvidia | 25        | 0.01%   |
| 1 x S3 Graphics          | 22        | 0.01%   |
| 3 x AMD                  | 19        | 0.01%   |
| Intel + 2 x AMD          | 17        | 0.01%   |
| 1 x Zhaoxin              | 15        | 0.01%   |
| 3 x Nvidia               | 12        | 0.01%   |
| 2 x AMD + 1 x Nvidia     | 12        | 0.01%   |
| 1 x Silicon Motion       | 11        | 0.01%   |
| AMD + 2 x Nvidia         | 11        | 0.01%   |
| 2 x Nvidia + 1 x ASPEED  | 10        | 0.005%  |
| 1 x Huawei Technologies  | 10        | 0.005%  |
| Nvidia + XGI             | 5         | 0.002%  |
| 1 x Neomagic             | 5         | 0.002%  |
| 2 x Nvidia + 1 x Matrox  | 4         | 0.002%  |
| 1 x Intel + 3 x Nvidia   | 4         | 0.002%  |
| Intel + ASPEED           | 4         | 0.002%  |
| AMD + XGI                | 4         | 0.002%  |
| 4 x Nvidia               | 3         | 0.001%  |
| 1 x Red Hat              | 3         | 0.001%  |
| 1 x Phytium Technology   | 3         | 0.001%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 171204    | 78.79%  |
| Proprietary | 35180     | 16.19%  |
| Unknown     | 10921     | 5.03%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 115605    | 52.37%  |
| 1.01-2.0       | 30402     | 13.77%  |
| 0.01-0.5       | 28375     | 12.85%  |
| 0.51-1.0       | 17659     | 8%      |
| 3.01-4.0       | 13200     | 5.98%   |
| 7.01-8.0       | 7468      | 3.38%   |
| 5.01-6.0       | 4044      | 1.83%   |
| 8.01-16.0      | 2215      | 1%      |
| 2.01-3.0       | 1369      | 0.62%   |
| 16.01-24.0     | 322       | 0.15%   |
| 4.01-5.0       | 68        | 0.03%   |
| 32.01-64.0     | 11        | 0.005%  |
| 24.01-32.0     | 10        | 0.005%  |
| 0              | 3         | 0.001%  |
| More than 64.0 | 1         | 0.0005% |
| 6.01-7.0       | 1         | 0.0005% |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 30634     | 13.54%  |
| AU Optronics            | 25534     | 11.28%  |
| LG Display              | 19493     | 8.61%   |
| BOE                     | 17004     | 7.51%   |
| Chimei Innolux          | 16879     | 7.46%   |
| Goldstar                | 12881     | 5.69%   |
| Dell                    | 12409     | 5.48%   |
| Acer                    | 8344      | 3.69%   |
| Hewlett-Packard         | 7461      | 3.3%    |
| BenQ                    | 5580      | 2.47%   |
| AOC                     | 5446      | 2.41%   |
| Philips                 | 5164      | 2.28%   |
| Ancor Communications    | 4804      | 2.12%   |
| Apple                   | 4358      | 1.93%   |
| Lenovo                  | 4048      | 1.79%   |
| Chi Mei Optoelectronics | 3955      | 1.75%   |
| Sharp                   | 3563      | 1.57%   |
| ViewSonic               | 2715      | 1.2%    |
| Iiyama                  | 2069      | 0.91%   |
| PANDA                   | 1871      | 0.83%   |
| Sony                    | 1714      | 0.76%   |
| ASUSTek Computer        | 1699      | 0.75%   |
| InfoVision              | 1506      | 0.67%   |
| LG Philips              | 1441      | 0.64%   |
| Unknown                 | 1324      | 0.58%   |
| LG Electronics          | 1217      | 0.54%   |
| HannStar                | 1108      | 0.49%   |
| NEC Computers           | 1036      | 0.46%   |
| Eizo                    | 845       | 0.37%   |
| Fujitsu Siemens         | 743       | 0.33%   |
| Panasonic               | 711       | 0.31%   |
| CPT                     | 689       | 0.3%    |
| Toshiba                 | 673       | 0.3%    |
| Valve                   | 636       | 0.28%   |
| Vizio                   | 626       | 0.28%   |
| MSI                     | 625       | 0.28%   |
| CSO                     | 612       | 0.27%   |
| Sceptre Tech            | 511       | 0.23%   |
| Medion                  | 396       | 0.17%   |
| Vestel Elektronik       | 333       | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 1032      | 0.44%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 982       | 0.42%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 939       | 0.4%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 928       | 0.4%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 865       | 0.37%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 858       | 0.37%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 837       | 0.36%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 750       | 0.32%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 646       | 0.28%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 644       | 0.28%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 643       | 0.27%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 629       | 0.27%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 595       | 0.25%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 519       | 0.22%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 480       | 0.21%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 469       | 0.2%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 451       | 0.19%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 443       | 0.19%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 427       | 0.18%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 422       | 0.18%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 402       | 0.17%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 396       | 0.17%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 393       | 0.17%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 376       | 0.16%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 366       | 0.16%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 365       | 0.16%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 358       | 0.15%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 344       | 0.15%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 343       | 0.15%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 342       | 0.15%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 340       | 0.15%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch       | 331       | 0.14%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 331       | 0.14%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 331       | 0.14%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 330       | 0.14%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 328       | 0.14%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 327       | 0.14%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 321       | 0.14%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 320       | 0.14%   |
| Unknown                                                                  | 312       | 0.13%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 88308     | 40.49%  |
| 1366x768 (WXGA)    | 44417     | 20.37%  |
| 3840x2160 (4K)     | 11785     | 5.4%    |
| 1600x900 (HD+)     | 9756      | 4.47%   |
| 1280x1024 (SXGA)   | 9586      | 4.4%    |
| 2560x1440 (QHD)    | 8500      | 3.9%    |
| 1680x1050 (WSXGA+) | 6328      | 2.9%    |
| 1280x800 (WXGA)    | 6253      | 2.87%   |
| 1440x900 (WXGA+)   | 5926      | 2.72%   |
| 1920x1200 (WUXGA)  | 4874      | 2.23%   |
| Unknown            | 2359      | 1.08%   |
| 1360x768           | 1988      | 0.91%   |
| 2560x1080          | 1915      | 0.88%   |
| 3440x1440          | 1869      | 0.86%   |
| 2560x1600          | 1456      | 0.67%   |
| 1024x600           | 1306      | 0.6%    |
| 1024x768 (XGA)     | 1146      | 0.53%   |
| 3840x1080          | 1022      | 0.47%   |
| 2880x1800          | 808       | 0.37%   |
| 800x1280           | 754       | 0.35%   |
| 1920x540           | 743       | 0.34%   |
| 1600x1200          | 624       | 0.29%   |
| 3840x2400          | 538       | 0.25%   |
| 2160x1440          | 513       | 0.24%   |
| 1280x720 (HD)      | 369       | 0.17%   |
| 3200x1800 (QHD+)   | 345       | 0.16%   |
| 2736x1824          | 308       | 0.14%   |
| 2288x1287          | 261       | 0.12%   |
| 2256x1504          | 204       | 0.09%   |
| 3840x1600          | 178       | 0.08%   |
| 1920x1280          | 171       | 0.08%   |
| 1400x1050          | 168       | 0.08%   |
| 3000x2000          | 160       | 0.07%   |
| 3840x1200          | 128       | 0.06%   |
| 2048x1152          | 122       | 0.06%   |
| 4480x1440          | 116       | 0.05%   |
| 3072x1920          | 109       | 0.05%   |
| 1680x945           | 104       | 0.05%   |
| 1280x960           | 104       | 0.05%   |
| 5760x1080          | 99        | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 57870     | 25.6%   |
| 13      | 19068     | 8.44%   |
| 14      | 15958     | 7.06%   |
| 24      | 14880     | 6.58%   |
| 27      | 14356     | 6.35%   |
| 23      | 14168     | 6.27%   |
| 17      | 14077     | 6.23%   |
| 21      | 13178     | 5.83%   |
| Unknown | 10084     | 4.46%   |
| 19      | 8170      | 3.61%   |
| 18      | 5146      | 2.28%   |
| 31      | 4288      | 1.9%    |
| 20      | 4067      | 1.8%    |
| 22      | 3956      | 1.75%   |
| 12      | 3719      | 1.65%   |
| 34      | 3112      | 1.38%   |
| 11      | 2928      | 1.3%    |
| 10      | 1643      | 0.73%   |
| 16      | 1624      | 0.72%   |
| 84      | 1522      | 0.67%   |
| 72      | 1261      | 0.56%   |
| 32      | 1173      | 0.52%   |
| 40      | 1120      | 0.5%    |
| 54      | 1030      | 0.46%   |
| 25      | 803       | 0.36%   |
| 26      | 651       | 0.29%   |
| 7       | 617       | 0.27%   |
| 28      | 416       | 0.18%   |
| 52      | 410       | 0.18%   |
| 48      | 398       | 0.18%   |
| 46      | 343       | 0.15%   |
| 37      | 300       | 0.13%   |
| 65      | 297       | 0.13%   |
| 29      | 284       | 0.13%   |
| 42      | 278       | 0.12%   |
| 49      | 240       | 0.11%   |
| 33      | 211       | 0.09%   |
| 39      | 188       | 0.08%   |
| 35      | 184       | 0.08%   |
| 142     | 178       | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 86676     | 38.98%  |
| 501-600        | 40480     | 18.21%  |
| 401-500        | 29312     | 13.18%  |
| 201-300        | 18180     | 8.18%   |
| 351-400        | 16492     | 7.42%   |
| Unknown        | 10084     | 4.54%   |
| 601-700        | 6580      | 2.96%   |
| 701-800        | 4671      | 2.1%    |
| 1001-1500      | 3332      | 1.5%    |
| 1501-2000      | 3009      | 1.35%   |
| 801-900        | 1849      | 0.83%   |
| 1-100          | 757       | 0.34%   |
| 901-1000       | 572       | 0.26%   |
| More than 2000 | 192       | 0.09%   |
| 101-200        | 168       | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 151794    | 73.57%  |
| 16/10   | 26199     | 12.7%   |
| 5/4     | 8963      | 4.34%   |
| Unknown | 8450      | 4.1%    |
| 21/9    | 3693      | 1.79%   |
| 4/3     | 2749      | 1.33%   |
| 3/2     | 2319      | 1.12%   |
| 0.67    | 595       | 0.29%   |
| 6/5     | 514       | 0.25%   |
| 32/9    | 476       | 0.23%   |
| 1.00    | 199       | 0.1%    |
| 0.56    | 97        | 0.05%   |
| 1.96    | 70        | 0.03%   |
| 0.62    | 35        | 0.02%   |
| 3.40    | 30        | 0.01%   |
| 0.45    | 30        | 0.01%   |
| 3.20    | 23        | 0.01%   |
| 3.73    | 16        | 0.01%   |
| 2.00    | 15        | 0.01%   |
| 2.65    | 13        | 0.01%   |
| 0.89    | 7         | 0.003%  |
| 0.58    | 7         | 0.003%  |
| 2.12    | 6         | 0.003%  |
| 0.80    | 5         | 0.002%  |
| 11/10   | 4         | 0.002%  |
| 0.75    | 4         | 0.002%  |
| 0.63    | 4         | 0.002%  |
| 3.33    | 2         | 0.001%  |
| 2.01    | 2         | 0.001%  |
| 1.03    | 2         | 0.001%  |
| 0.25    | 2         | 0.001%  |
| 3.88    | 1         | 0.0005% |
| 3.76    | 1         | 0.0005% |
| 2.50    | 1         | 0.0005% |
| 2.21    | 1         | 0.0005% |
| 0.65    | 1         | 0.0005% |
| 0.57    | 1         | 0.0005% |
| 0.31    | 1         | 0.0005% |
| 0.00    | 1         | 0.0005% |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 57318     | 25.59%  |
| 201-250        | 37134     | 16.58%  |
| 81-90          | 27344     | 12.21%  |
| 151-200        | 16184     | 7.22%   |
| 301-350        | 14823     | 6.62%   |
| Unknown        | 10085     | 4.5%    |
| 351-500        | 9266      | 4.14%   |
| 141-150        | 8563      | 3.82%   |
| 121-130        | 8040      | 3.59%   |
| 71-80          | 7718      | 3.45%   |
| More than 1000 | 5752      | 2.57%   |
| 251-300        | 5660      | 2.53%   |
| 61-70          | 3252      | 1.45%   |
| 501-1000       | 3196      | 1.43%   |
| 51-60          | 2999      | 1.34%   |
| 131-140        | 1757      | 0.78%   |
| 111-120        | 1730      | 0.77%   |
| 41-50          | 1612      | 0.72%   |
| 1-40           | 919       | 0.41%   |
| 91-100         | 664       | 0.3%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 75308     | 34.56%  |
| 101-120       | 61111     | 28.04%  |
| 121-160       | 50376     | 23.12%  |
| 161-240       | 11332     | 5.2%    |
| Unknown       | 10085     | 4.63%   |
| 1-50          | 5368      | 2.46%   |
| More than 240 | 4351      | 2%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 174679    | 80.06%  |
| 2     | 29385     | 13.47%  |
| 0     | 10661     | 4.89%   |
| 3     | 3158      | 1.45%   |
| 4     | 275       | 0.13%   |
| 5     | 20        | 0.01%   |
| 6     | 9         | 0.004%  |
| 7     | 1         | 0.0005% |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 116959    | 36.46%  |
| Intel                             | 91683     | 28.58%  |
| Qualcomm Atheros                  | 39921     | 12.44%  |
| Broadcom                          | 19088     | 5.95%   |
| Broadcom Limited                  | 4654      | 1.45%   |
| Marvell Technology Group          | 4397      | 1.37%   |
| Ralink Technology                 | 4267      | 1.33%   |
| Nvidia                            | 4218      | 1.31%   |
| Ralink                            | 3628      | 1.13%   |
| MediaTek                          | 3507      | 1.09%   |
| TP-Link                           | 3202      | 1%      |
| Samsung Electronics               | 1565      | 0.49%   |
| ASIX Electronics                  | 1544      | 0.48%   |
| Huawei Technologies               | 1444      | 0.45%   |
| Qualcomm Atheros Communications   | 1241      | 0.39%   |
| Xiaomi                            | 918       | 0.29%   |
| D-Link                            | 876       | 0.27%   |
| NetGear                           | 862       | 0.27%   |
| Dell                              | 799       | 0.25%   |
| ASUSTek Computer                  | 772       | 0.24%   |
| D-Link System                     | 762       | 0.24%   |
| Microsoft                         | 728       | 0.23%   |
| JMicron Technology                | 726       | 0.23%   |
| VIA Technologies                  | 711       | 0.22%   |
| Sierra Wireless                   | 705       | 0.22%   |
| DisplayLink                       | 639       | 0.2%    |
| Lenovo                            | 626       | 0.2%    |
| Ericsson Business Mobile Networks | 605       | 0.19%   |
| Aquantia                          | 559       | 0.17%   |
| Qualcomm                          | 545       | 0.17%   |
| Silicon Integrated Systems [SiS]  | 472       | 0.15%   |
| Hewlett-Packard                   | 471       | 0.15%   |
| Edimax Technology                 | 400       | 0.12%   |
| Linksys                           | 325       | 0.1%    |
| Motorola PCS                      | 299       | 0.09%   |
| Belkin Components                 | 298       | 0.09%   |
| Attansic Technology               | 273       | 0.09%   |
| Microchip Technology              | 267       | 0.08%   |
| ZTE WCDMA Technologies MSM        | 259       | 0.08%   |
| Google                            | 247       | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 79030     | 21.17%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 15325     | 4.1%    |
| Intel Wi-Fi 6 AX200                                                     | 7856      | 2.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 7103      | 1.9%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5550      | 1.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5376      | 1.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5251      | 1.41%   |
| Intel Wireless 8265 / 8275                                              | 5245      | 1.4%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4865      | 1.3%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 4679      | 1.25%   |
| Intel I211 Gigabit Network Connection                                   | 4284      | 1.15%   |
| Intel Wireless 7265                                                     | 4035      | 1.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4011      | 1.07%   |
| Intel Wi-Fi 6 AX201                                                     | 3903      | 1.05%   |
| Intel Wireless 7260                                                     | 3829      | 1.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3752      | 1%      |
| Realtek RTL8125 2.5GbE Controller                                       | 3652      | 0.98%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3067      | 0.82%   |
| Intel Wireless 8260                                                     | 3031      | 0.81%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2876      | 0.77%   |
| Intel Ethernet Connection (2) I219-V                                    | 2863      | 0.77%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2796      | 0.75%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2725      | 0.73%   |
| Intel Ethernet Connection I217-LM                                       | 2662      | 0.71%   |
| Intel Wireless 3165                                                     | 2658      | 0.71%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2479      | 0.66%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2406      | 0.64%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2300      | 0.62%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2293      | 0.61%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 2160      | 0.58%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 1995      | 0.53%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1961      | 0.53%   |
| Intel Ethernet Controller I225-V                                        | 1875      | 0.5%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 1861      | 0.5%    |
| Intel 82579V Gigabit Network Connection                                 | 1858      | 0.5%    |
| Intel Wireless-AC 9260                                                  | 1825      | 0.49%   |
| Ralink MT7601U Wireless Adapter                                         | 1776      | 0.48%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 1674      | 0.45%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1644      | 0.44%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1636      | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 67726     | 40.9%   |
| Qualcomm Atheros                      | 31312     | 18.91%  |
| Realtek Semiconductor                 | 27944     | 16.87%  |
| Broadcom                              | 12652     | 7.64%   |
| Ralink Technology                     | 4267      | 2.58%   |
| Ralink                                | 3626      | 2.19%   |
| MediaTek                              | 3165      | 1.91%   |
| TP-Link                               | 2889      | 1.74%   |
| Broadcom Limited                      | 2782      | 1.68%   |
| Qualcomm Atheros Communications       | 1241      | 0.75%   |
| NetGear                               | 836       | 0.5%    |
| D-Link                                | 817       | 0.49%   |
| ASUSTek Computer                      | 730       | 0.44%   |
| Sierra Wireless                       | 705       | 0.43%   |
| Microsoft                             | 634       | 0.38%   |
| D-Link System                         | 477       | 0.29%   |
| Dell                                  | 464       | 0.28%   |
| Marvell Technology Group              | 457       | 0.28%   |
| Edimax Technology                     | 400       | 0.24%   |
| Linksys                               | 297       | 0.18%   |
| Belkin Components                     | 289       | 0.17%   |
| Qualcomm                              | 272       | 0.16%   |
| Fibocom                               | 168       | 0.1%    |
| IMC Networks                          | 166       | 0.1%    |
| AVM                                   | 149       | 0.09%   |
| Hewlett-Packard                       | 107       | 0.06%   |
| Sitecom Europe                        | 83        | 0.05%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 79        | 0.05%   |
| ZyDAS                                 | 70        | 0.04%   |
| ZyXEL Communications                  | 67        | 0.04%   |
| Gemtek                                | 67        | 0.04%   |
| Mercucys                              | 61        | 0.04%   |
| Micro Star International              | 54        | 0.03%   |
| BUFFALO                               | 50        | 0.03%   |
| Wilocity                              | 40        | 0.02%   |
| Tenda                                 | 36        | 0.02%   |
| TRENDnet                              | 31        | 0.02%   |
| Wacom                                 | 30        | 0.02%   |
| Xiaomi                                | 27        | 0.02%   |
| Accton Technology                     | 25        | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 7856      | 4.71%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5550      | 3.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5376      | 3.22%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5251      | 3.15%   |
| Intel Wireless 8265 / 8275                                              | 5245      | 3.14%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4865      | 2.91%   |
| Intel Wireless 7265                                                     | 4035      | 2.42%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4011      | 2.4%    |
| Intel Wi-Fi 6 AX201                                                     | 3903      | 2.34%   |
| Intel Wireless 7260                                                     | 3829      | 2.29%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3752      | 2.25%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3067      | 1.84%   |
| Intel Wireless 8260                                                     | 3031      | 1.82%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2876      | 1.72%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2796      | 1.68%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2725      | 1.63%   |
| Intel Wireless 3165                                                     | 2658      | 1.59%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2479      | 1.49%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2406      | 1.44%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2300      | 1.38%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2293      | 1.37%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1961      | 1.17%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1861      | 1.12%   |
| Intel Wireless-AC 9260                                                  | 1825      | 1.09%   |
| Ralink MT7601U Wireless Adapter                                         | 1776      | 1.06%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 1648      | 0.99%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1644      | 0.99%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1636      | 0.98%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1631      | 0.98%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1583      | 0.95%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1562      | 0.94%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1552      | 0.93%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1497      | 0.9%    |
| Intel Wireless 3160                                                     | 1490      | 0.89%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1452      | 0.87%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1228      | 0.74%   |
| Realtek 802.11ac NIC                                                    | 1202      | 0.72%   |
| Intel WiFi Link 5100                                                    | 1151      | 0.69%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1135      | 0.68%   |
| Intel Centrino Ultimate-N 6300                                          | 1131      | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 105388    | 53.23%  |
| Intel                             | 47421     | 23.95%  |
| Qualcomm Atheros                  | 12731     | 6.43%   |
| Broadcom                          | 8826      | 4.46%   |
| Nvidia                            | 4208      | 2.13%   |
| Marvell Technology Group          | 3943      | 1.99%   |
| Broadcom Limited                  | 1951      | 0.99%   |
| ASIX Electronics                  | 1544      | 0.78%   |
| Samsung Electronics               | 1534      | 0.77%   |
| Xiaomi                            | 890       | 0.45%   |
| JMicron Technology                | 726       | 0.37%   |
| Huawei Technologies               | 719       | 0.36%   |
| VIA Technologies                  | 690       | 0.35%   |
| DisplayLink                       | 639       | 0.32%   |
| Lenovo                            | 609       | 0.31%   |
| Aquantia                          | 559       | 0.28%   |
| Silicon Integrated Systems [SiS]  | 459       | 0.23%   |
| MediaTek                          | 323       | 0.16%   |
| TP-Link                           | 319       | 0.16%   |
| D-Link System                     | 286       | 0.14%   |
| Attansic Technology               | 273       | 0.14%   |
| Qualcomm                          | 261       | 0.13%   |
| OPPO Electronics                  | 243       | 0.12%   |
| Google                            | 237       | 0.12%   |
| ZTE WCDMA Technologies MSM        | 232       | 0.12%   |
| Motorola PCS                      | 209       | 0.11%   |
| Apple                             | 199       | 0.1%    |
| Microchip Technology              | 193       | 0.1%    |
| Mellanox Technologies             | 170       | 0.09%   |
| ICS Advent                        | 170       | 0.09%   |
| 3Com                              | 138       | 0.07%   |
| Hewlett-Packard                   | 129       | 0.07%   |
| Sundance Technology Inc / IC Plus | 111       | 0.06%   |
| OnePlus Technology (Shenzhen)     | 94        | 0.05%   |
| HTC (High Tech Computer)          | 89        | 0.04%   |
| IBM                               | 86        | 0.04%   |
| Microsoft                         | 85        | 0.04%   |
| T & A Mobile Phones               | 75        | 0.04%   |
| American Megatrends               | 71        | 0.04%   |
| LG Electronics                    | 61        | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 79030     | 39.06%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 15325     | 7.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7103      | 3.51%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4679      | 2.31%   |
| Intel I211 Gigabit Network Connection                             | 4284      | 2.12%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3652      | 1.8%    |
| Intel Ethernet Connection (2) I219-V                              | 2863      | 1.41%   |
| Intel Ethernet Connection I217-LM                                 | 2662      | 1.32%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2160      | 1.07%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1995      | 0.99%   |
| Intel Ethernet Controller I225-V                                  | 1875      | 0.93%   |
| Intel 82579V Gigabit Network Connection                           | 1858      | 0.92%   |
| Nvidia MCP61 Ethernet                                             | 1609      | 0.8%    |
| Intel Ethernet Connection (7) I219-V                              | 1489      | 0.74%   |
| Intel Ethernet Connection (4) I219-LM                             | 1393      | 0.69%   |
| Intel 82577LM Gigabit Network Connection                          | 1307      | 0.65%   |
| Intel Ethernet Connection I219-LM                                 | 1265      | 0.63%   |
| Intel Ethernet Connection (2) I219-LM                             | 1255      | 0.62%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1223      | 0.6%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1196      | 0.59%   |
| Intel Ethernet Connection I218-LM                                 | 1137      | 0.56%   |
| Intel Ethernet Connection I217-V                                  | 1114      | 0.55%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1103      | 0.55%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1090      | 0.54%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1015      | 0.5%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 999       | 0.49%   |
| Nvidia MCP79 Ethernet                                             | 997       | 0.49%   |
| Intel I210 Gigabit Network Connection                             | 989       | 0.49%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 969       | 0.48%   |
| Intel Ethernet Connection (3) I218-LM                             | 962       | 0.48%   |
| Intel Ethernet Connection (4) I219-V                              | 951       | 0.47%   |
| Intel 82574L Gigabit Network Connection                           | 947       | 0.47%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 939       | 0.46%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 925       | 0.46%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 918       | 0.45%   |
| Intel 82567LM Gigabit Network Connection                          | 917       | 0.45%   |
| Intel Ethernet Connection (2) I218-V                              | 891       | 0.44%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 856       | 0.42%   |
| Intel Ethernet Connection (6) I219-V                              | 854       | 0.42%   |
| Intel Ethernet Connection (7) I219-LM                             | 834       | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 185515    | 53.58%  |
| WiFi     | 156646    | 45.24%  |
| Modem    | 3524      | 1.02%   |
| Unknown  | 536       | 0.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 120758    | 54.94%  |
| Ethernet | 98953     | 45.02%  |
| Unknown  | 62        | 0.03%   |
| Modem    | 20        | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 115192    | 53.87%  |
| 1     | 88137     | 41.22%  |
| 0     | 4860      | 2.27%   |
| 3     | 4020      | 1.88%   |
| 4     | 1000      | 0.47%   |
| 6     | 215       | 0.1%    |
| 5     | 211       | 0.1%    |
| 8     | 74        | 0.03%   |
| 7     | 37        | 0.02%   |
| 10    | 22        | 0.01%   |
| 12    | 11        | 0.01%   |
| 9     | 10        | 0.005%  |
| 13    | 4         | 0.002%  |
| 20    | 3         | 0.001%  |
| 18    | 3         | 0.001%  |
| 132   | 2         | 0.001%  |
| 33    | 2         | 0.001%  |
| 17    | 2         | 0.001%  |
| 16    | 2         | 0.001%  |
| 14    | 2         | 0.001%  |
| 11    | 2         | 0.001%  |
| 66    | 1         | 0.0005% |
| 42    | 1         | 0.0005% |
| 32    | 1         | 0.0005% |
| 22    | 1         | 0.0005% |
| 21    | 1         | 0.0005% |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 173300    | 79.4%   |
| Yes     | 36898     | 16.9%   |
| Unknown | 8071      | 3.7%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 53135     | 43.95%  |
| Realtek Semiconductor           | 11691     | 9.67%   |
| Qualcomm Atheros Communications | 10485     | 8.67%   |
| Cambridge Silicon Radio         | 7339      | 6.07%   |
| Broadcom                        | 6696      | 5.54%   |
| IMC Networks                    | 6103      | 5.05%   |
| Lite-On Technology              | 4642      | 3.84%   |
| Apple                           | 4603      | 3.81%   |
| Foxconn / Hon Hai               | 3848      | 3.18%   |
| ASUSTek Computer                | 2268      | 1.88%   |
| Dell                            | 1742      | 1.44%   |
| Hewlett-Packard                 | 1422      | 1.18%   |
| Ralink                          | 1078      | 0.89%   |
| Toshiba                         | 1058      | 0.88%   |
| MediaTek                        | 719       | 0.59%   |
| Realtek                         | 694       | 0.57%   |
| Foxconn International           | 474       | 0.39%   |
| Marvell Semiconductor           | 415       | 0.34%   |
| Alps Electric                   | 356       | 0.29%   |
| TP-Link                         | 269       | 0.22%   |
| Ralink Technology               | 247       | 0.2%    |
| Integrated System Solution      | 200       | 0.17%   |
| Belkin Components               | 122       | 0.1%    |
| Dynex                           | 114       | 0.09%   |
| Askey Computer                  | 112       | 0.09%   |
| Edimax Technology               | 104       | 0.09%   |
| Micro Star International        | 93        | 0.08%   |
| Chicony Electronics             | 93        | 0.08%   |
| USI                             | 89        | 0.07%   |
| Taiyo Yuden                     | 78        | 0.06%   |
| Opticis                         | 65        | 0.05%   |
| Qcom                            | 63        | 0.05%   |
| HTC (High Tech Computer)        | 59        | 0.05%   |
| Smart Modular Technologies      | 48        | 0.04%   |
| Logitech                        | 45        | 0.04%   |
| Conwise Technology              | 37        | 0.03%   |
| Fujitsu                         | 34        | 0.03%   |
| Unknown                         | 32        | 0.03%   |
| Actions                         | 31        | 0.03%   |
| ISSC                            | 29        | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 19752     | 16.32%  |
| Intel AX201 Bluetooth                               | 8751      | 7.23%   |
| Intel AX200 Bluetooth                               | 7488      | 6.19%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 7429      | 6.14%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7338      | 6.06%   |
| Realtek Bluetooth Radio                             | 7232      | 5.97%   |
| Qualcomm Atheros  Bluetooth Device                  | 4658      | 3.85%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2928      | 2.42%   |
| IMC Networks Bluetooth Radio                        | 2631      | 2.17%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2221      | 1.83%   |
| Apple Bluetooth Host Controller                     | 1805      | 1.49%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1799      | 1.49%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1733      | 1.43%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1701      | 1.41%   |
| Intel Bluetooth Device                              | 1652      | 1.36%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1583      | 1.31%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1572      | 1.3%    |
| Intel AX210 Bluetooth                               | 1529      | 1.26%   |
| IMC Networks Bluetooth Device                       | 1384      | 1.14%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1257      | 1.04%   |
| Apple Bluetooth USB Host Controller                 | 1205      | 1%      |
| Lite-On Bluetooth Device                            | 1184      | 0.98%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1091      | 0.9%    |
| Ralink RT3290 Bluetooth                             | 1078      | 0.89%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1028      | 0.85%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 903       | 0.75%   |
| IMC Networks Wireless_Device                        | 894       | 0.74%   |
| Lite-On Atheros AR3012 Bluetooth                    | 877       | 0.72%   |
| Broadcom BCM2045B (BDC-2.1)                         | 866       | 0.72%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 846       | 0.7%    |
| HP Broadcom 2070 Bluetooth Combo                    | 740       | 0.61%   |
| Realtek Bluetooth Radio                             | 694       | 0.57%   |
| MediaTek Wireless_Device                            | 663       | 0.55%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 655       | 0.54%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 634       | 0.52%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 609       | 0.5%    |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 604       | 0.5%    |
| Dell DW375 Bluetooth Module                         | 584       | 0.48%   |
| Realtek RTL8723B Bluetooth                          | 560       | 0.46%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 529       | 0.44%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 150332    | 51.97%  |
| AMD                              | 60865     | 21.04%  |
| Nvidia                           | 49825     | 17.23%  |
| C-Media Electronics              | 4701      | 1.63%   |
| Logitech                         | 2057      | 0.71%   |
| Creative Labs                    | 1984      | 0.69%   |
| Texas Instruments                | 995       | 0.34%   |
| JMTek                            | 916       | 0.32%   |
| Realtek Semiconductor            | 872       | 0.3%    |
| GN Netcom                        | 828       | 0.29%   |
| VIA Technologies                 | 753       | 0.26%   |
| Generalplus Technology           | 733       | 0.25%   |
| Kingston Technology              | 728       | 0.25%   |
| Creative Technology              | 706       | 0.24%   |
| ASUSTek Computer                 | 638       | 0.22%   |
| Lenovo                           | 636       | 0.22%   |
| Plantronics                      | 594       | 0.21%   |
| Silicon Integrated Systems [SiS] | 580       | 0.2%    |
| Focusrite-Novation               | 572       | 0.2%    |
| Razer USA                        | 561       | 0.19%   |
| SteelSeries ApS                  | 514       | 0.18%   |
| Corsair                          | 501       | 0.17%   |
| Blue Microphones                 | 295       | 0.1%    |
| Hewlett-Packard                  | 289       | 0.1%    |
| Apple                            | 286       | 0.1%    |
| Micro Star International         | 248       | 0.09%   |
| Sony                             | 229       | 0.08%   |
| Tenx Technology                  | 219       | 0.08%   |
| BEHRINGER International          | 207       | 0.07%   |
| Samson Technologies              | 205       | 0.07%   |
| Dell                             | 200       | 0.07%   |
| Sennheiser Communications        | 178       | 0.06%   |
| M-Audio                          | 171       | 0.06%   |
| Yamaha                           | 168       | 0.06%   |
| GYROCOM C&C                      | 164       | 0.06%   |
| Microsoft                        | 153       | 0.05%   |
| RODE Microphones                 | 143       | 0.05%   |
| XMOS                             | 141       | 0.05%   |
| DSEA A/S                         | 130       | 0.04%   |
| SAVITECH                         | 121       | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 15629     | 4.57%   |
| AMD Family 17h/19h HD Audio Controller                                     | 15373     | 4.49%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 14890     | 4.35%   |
| Intel Sunrise Point-LP HD Audio                                            | 14747     | 4.31%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 9937      | 2.9%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 9853      | 2.88%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 8584      | 2.51%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 7506      | 2.19%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 7274      | 2.13%   |
| AMD FCH Azalia Controller                                                  | 7244      | 2.12%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 7206      | 2.11%   |
| Intel Cannon Lake PCH cAVS                                                 | 6992      | 2.04%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 6929      | 2.03%   |
| AMD Starship/Matisse HD Audio Controller                                   | 6812      | 1.99%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5581      | 1.63%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5554      | 1.62%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 5155      | 1.51%   |
| Intel 8 Series HD Audio Controller                                         | 5109      | 1.49%   |
| Intel Haswell-ULT HD Audio Controller                                      | 5082      | 1.49%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 4224      | 1.23%   |
| Intel Broadwell-U Audio Controller                                         | 4140      | 1.21%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4024      | 1.18%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4023      | 1.18%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3940      | 1.15%   |
| Intel 200 Series PCH HD Audio                                              | 3748      | 1.1%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3738      | 1.09%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3689      | 1.08%   |
| Nvidia GF108 High Definition Audio Controller                              | 3523      | 1.03%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3402      | 0.99%   |
| AMD Kabini HDMI/DP Audio                                                   | 3177      | 0.93%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3134      | 0.92%   |
| Nvidia High Definition Audio Controller                                    | 3021      | 0.88%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2861      | 0.84%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2745      | 0.8%    |
| Intel Comet Lake PCH cAVS                                                  | 2554      | 0.75%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2542      | 0.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2520      | 0.74%   |
| Nvidia GP106 High Definition Audio Controller                              | 2475      | 0.72%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2468      | 0.72%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2420      | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 28888     | 20.11%  |
| SK hynix            | 23310     | 16.22%  |
| Unknown             | 20065     | 13.97%  |
| Kingston            | 17394     | 12.11%  |
| Micron Technology   | 12181     | 8.48%   |
| Crucial             | 7930      | 5.52%   |
| Corsair             | 6698      | 4.66%   |
| G.Skill             | 4190      | 2.92%   |
| A-DATA Technology   | 2829      | 1.97%   |
| Elpida              | 2564      | 1.78%   |
| Ramaxel Technology  | 2438      | 1.7%    |
| Nanya Technology    | 2061      | 1.43%   |
| Patriot             | 1097      | 0.76%   |
| Unknown (ABCD)      | 1091      | 0.76%   |
| Team                | 938       | 0.65%   |
| Unknown             | 808       | 0.56%   |
| Smart               | 794       | 0.55%   |
| Transcend           | 634       | 0.44%   |
| AMD                 | 567       | 0.39%   |
| GOODRAM             | 562       | 0.39%   |
| Apacer              | 380       | 0.26%   |
| ASint Technology    | 337       | 0.23%   |
| Goldkey             | 286       | 0.2%    |
| Silicon Power       | 261       | 0.18%   |
| Kingmax             | 251       | 0.17%   |
| Teikon              | 211       | 0.15%   |
| Qimonda             | 209       | 0.15%   |
| 48spaces            | 191       | 0.13%   |
| PNY                 | 187       | 0.13%   |
| Avant               | 180       | 0.13%   |
| Unifosa             | 166       | 0.12%   |
| GeIL                | 161       | 0.11%   |
| SHARETRONIC         | 127       | 0.09%   |
| Smart Brazil        | 124       | 0.09%   |
| Foxline             | 119       | 0.08%   |
| Kllisre             | 117       | 0.08%   |
| Qumo                | 115       | 0.08%   |
| Hewlett-Packard     | 115       | 0.08%   |
| CSX                 | 111       | 0.08%   |
| Toshiba             | 108       | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1044      | 0.67%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1031      | 0.66%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 993       | 0.63%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 915       | 0.58%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 907       | 0.58%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 867       | 0.55%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 864       | 0.55%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 860       | 0.55%   |
| Unknown                                                          | 808       | 0.52%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 785       | 0.5%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 710       | 0.45%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 703       | 0.45%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 691       | 0.44%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 641       | 0.41%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 626       | 0.4%    |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 618       | 0.39%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 605       | 0.39%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 594       | 0.38%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 584       | 0.37%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 582       | 0.37%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                           | 574       | 0.37%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                          | 521       | 0.33%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 515       | 0.33%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 510       | 0.33%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 508       | 0.32%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 506       | 0.32%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 505       | 0.32%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 501       | 0.32%   |
| Unknown RAM Module 1024MB DIMM SDRAM                             | 495       | 0.32%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 489       | 0.31%   |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s         | 475       | 0.3%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 472       | 0.3%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 471       | 0.3%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 463       | 0.3%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 460       | 0.29%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 449       | 0.29%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 447       | 0.29%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 438       | 0.28%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 411       | 0.26%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 407       | 0.26%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind            | Computers | Percent |
|-----------------|-----------|---------|
| DDR4            | 48368     | 38.86%  |
| DDR3            | 45497     | 36.55%  |
| DDR2            | 9125      | 7.33%   |
| Unknown         | 5980      | 4.8%    |
| SDRAM           | 5245      | 4.21%   |
| LPDDR4          | 3860      | 3.1%    |
| LPDDR3          | 2423      | 1.95%   |
| DDR             | 1459      | 1.17%   |
| DDR5            | 1374      | 1.1%    |
| LPDDR5          | 692       | 0.56%   |
| DRAM            | 435       | 0.35%   |
| RAM             | 7         | 0.01%   |
| EEPROM          | 7         | 0.01%   |
| DDR2 FB-DIMM    | 4         | 0.003%  |
| Logical non-vol | 3         | 0.002%  |
| SRAM            | 1         | 0.001%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| SODIMM          | 67288     | 54.61%  |
| DIMM            | 48154     | 39.08%  |
| Row Of Chips    | 6653      | 5.4%    |
| Chip            | 511       | 0.41%   |
| Unknown         | 377       | 0.31%   |
| FB-DIMM         | 120       | 0.1%    |
| RIMM            | 99        | 0.08%   |
| Proprietary Car | 4         | 0.003%  |
| DIP             | 1         | 0.001%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 8192    | 44193     | 32.03%  |
| 4096    | 39612     | 28.71%  |
| 2048    | 23998     | 17.39%  |
| 16384   | 15793     | 11.45%  |
| 1024    | 8510      | 6.17%   |
| 32768   | 3914      | 2.84%   |
| 512     | 1460      | 1.06%   |
| 256     | 274       | 0.2%    |
| 65536   | 104       | 0.08%   |
| 1536    | 22        | 0.02%   |
| 128     | 18        | 0.01%   |
| Unknown | 18        | 0.01%   |
| 64      | 8         | 0.01%   |
| 3072    | 7         | 0.01%   |
| 32      | 7         | 0.01%   |
| 16      | 7         | 0.01%   |
| 1       | 7         | 0.01%   |
| 49152   | 6         | 0.004%  |
| 12288   | 6         | 0.004%  |
| 129408  | 4         | 0.003%  |
| 131072  | 3         | 0.002%  |
| 6144    | 3         | 0.002%  |
| 258496  | 1         | 0.001%  |
| 32767   | 1         | 0.001%  |
| 24576   | 1         | 0.001%  |
| 16315   | 1         | 0.001%  |
| 15616   | 1         | 0.001%  |
| 12333   | 1         | 0.001%  |
| 8072    | 1         | 0.001%  |
| 384     | 1         | 0.001%  |
| 232     | 1         | 0.001%  |
| 13      | 1         | 0.001%  |
| 8       | 1         | 0.001%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 28289     | 20.84%  |
| 2667    | 15976     | 11.77%  |
| 3200    | 15737     | 11.6%   |
| 1333    | 11419     | 8.41%   |
| 2400    | 8659      | 6.38%   |
| 2133    | 5804      | 4.28%   |
| 1334    | 5358      | 3.95%   |
| 800     | 5162      | 3.8%    |
| 667     | 4929      | 3.63%   |
| Unknown | 4705      | 3.47%   |
| 3600    | 2938      | 2.16%   |
| 1867    | 2330      | 1.72%   |
| 1067    | 1884      | 1.39%   |
| 4267    | 1430      | 1.05%   |
| 1066    | 1425      | 1.05%   |
| 3266    | 1317      | 0.97%   |
| 4199    | 1077      | 0.79%   |
| 1866    | 1037      | 0.76%   |
| 4800    | 1028      | 0.76%   |
| 533     | 993       | 0.73%   |
| 400     | 844       | 0.62%   |
| 3000    | 838       | 0.62%   |
| 3400    | 790       | 0.58%   |
| 2933    | 778       | 0.57%   |
| 1800    | 778       | 0.57%   |
| 2666    | 752       | 0.55%   |
| 2048    | 743       | 0.55%   |
| 6400    | 737       | 0.54%   |
| 3733    | 663       | 0.49%   |
| 333     | 489       | 0.36%   |
| 975     | 433       | 0.32%   |
| 3800    | 420       | 0.31%   |
| 2800    | 372       | 0.27%   |
| 3533    | 367       | 0.27%   |
| 3466    | 356       | 0.26%   |
| 3866    | 347       | 0.26%   |
| 8400    | 342       | 0.25%   |
| 4266    | 326       | 0.24%   |
| 3666    | 202       | 0.15%   |
| 1639    | 201       | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Hewlett-Packard                 | 2370      | 34.48%  |
| Canon                           | 1196      | 17.4%   |
| Brother Industries              | 1029      | 14.97%  |
| Samsung Electronics             | 811       | 11.8%   |
| Seiko Epson                     | 621       | 9.04%   |
| Xerox                           | 109       | 1.59%   |
| Prolific Technology             | 87        | 1.27%   |
| Lexmark International           | 69        | 1%      |
| Kyocera                         | 69        | 1%      |
| Dymo-CoStar                     | 69        | 1%      |
| Pantum                          | 68        | 0.99%   |
| QinHeng Electronics             | 59        | 0.86%   |
| Ricoh                           | 50        | 0.73%   |
| Panasonic (Matsushita)          | 48        | 0.7%    |
| STMicroelectronics              | 27        | 0.39%   |
| Zebra                           | 26        | 0.38%   |
| Oki Data                        | 20        | 0.29%   |
| Dell                            | 19        | 0.28%   |
| Fuji Xerox                      | 13        | 0.19%   |
| Apple                           | 10        | 0.15%   |
| Konica Minolta                  | 8         | 0.12%   |
| TSC Auto ID Technology          | 6         | 0.09%   |
| MIIIW                           | 6         | 0.09%   |
| Star Micronics                  | 5         | 0.07%   |
| Citizen                         | 5         | 0.07%   |
| Xiaomi                          | 4         | 0.06%   |
| NXP Semiconductors              | 4         | 0.06%   |
| Datamax-O'Neil                  | 4         | 0.06%   |
| Custom Engineering SPA          | 4         | 0.06%   |
| WinChipHead                     | 3         | 0.04%   |
| Sharp                           | 3         | 0.04%   |
| Magic Control Technology        | 3         | 0.04%   |
| ICS Advent                      | 3         | 0.04%   |
| cab Produkttechnik GmbH & Co KG | 3         | 0.04%   |
| BIXOLON                         | 3         | 0.04%   |
| BESTEASY                        | 3         | 0.04%   |
| ATEN International              | 3         | 0.04%   |
| Zhuhai Poskey Technology        | 2         | 0.03%   |
| Toshiba TEC                     | 2         | 0.03%   |
| Seiko Instruments               | 2         | 0.03%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| HP LaserJet 1020                     | 128       | 1.84%   |
| HP LaserJet 1018                     | 93        | 1.33%   |
| Prolific PL2305 Parallel Port        | 87        | 1.25%   |
| Samsung M2020 Series                 | 82        | 1.18%   |
| HP DeskJet 2600 series               | 81        | 1.16%   |
| HP LaserJet P1102                    | 75        | 1.08%   |
| HP DeskJet 2130 series               | 68        | 0.98%   |
| Samsung M2070 Series                 | 67        | 0.96%   |
| Canon PIXMA MG2500 Series            | 66        | 0.95%   |
| Brother Printer                      | 66        | 0.95%   |
| Samsung SCX-4200 series              | 64        | 0.92%   |
| Seiko Epson Printer                  | 61        | 0.88%   |
| QinHeng CH340S                       | 59        | 0.85%   |
| Samsung SCX-3400 Series              | 58        | 0.83%   |
| HP LaserJet P1005                    | 55        | 0.79%   |
| Canon LBP2900                        | 55        | 0.79%   |
| HP ENVY 4520 series                  | 53        | 0.76%   |
| HP DeskJet 2700 series               | 51        | 0.73%   |
| HP Deskjet 2050 J510                 | 46        | 0.66%   |
| Brother HL-2030 Laser Printer        | 46        | 0.66%   |
| HP LaserJet 1010                     | 45        | 0.65%   |
| HP DeskJet 3630 series               | 45        | 0.65%   |
| Samsung ML-1640 Series Laser Printer | 44        | 0.63%   |
| Samsung SCX-3200 Series              | 40        | 0.57%   |
| Canon PIXMA MX920 Series             | 40        | 0.57%   |
| Canon PIXMA MG3600 Series            | 40        | 0.57%   |
| Brother HL-1110 series               | 39        | 0.56%   |
| Samsung ML-216x Series Laser Printer | 36        | 0.52%   |
| Canon LiDE 300                       | 36        | 0.52%   |
| Seiko Epson ET-2710 Series           | 35        | 0.5%    |
| HP Deskjet 2540 series               | 35        | 0.5%    |
| Canon LiDE 400                       | 35        | 0.5%    |
| HP LaserJet 1200                     | 34        | 0.49%   |
| HP Deskjet 1050 J410                 | 34        | 0.49%   |
| Canon MF4410                         | 34        | 0.49%   |
| Canon iP7200 series                  | 34        | 0.49%   |
| HP LaserJet Professional P1102w      | 33        | 0.47%   |
| Panasonic (Matsushita) KX-MB1500RU   | 32        | 0.46%   |
| HP ENVY 5000 series                  | 32        | 0.46%   |
| Canon MF3010                         | 32        | 0.46%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                                         | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Canon                                          | 783       | 51.62%  |
| Seiko Epson                                    | 332       | 21.89%  |
| Hewlett-Packard                                | 201       | 13.25%  |
| Mustek Systems                                 | 88        | 5.8%    |
| Ultima Electronics                             | 29        | 1.91%   |
| Acer Peripherals (now BenQ)                    | 25        | 1.65%   |
| AGFA-Gevaert NV                                | 17        | 1.12%   |
| KYE Systems (Mouse Systems)                    | 10        | 0.66%   |
| Plustek                                        | 9         | 0.59%   |
| Microtek International                         | 4         | 0.26%   |
| Fujitsu                                        | 4         | 0.26%   |
| Visioneer                                      | 2         | 0.13%   |
| UMAX                                           | 2         | 0.13%   |
| Siemens Information and Communication Products | 2         | 0.13%   |
| Canon Electronics                              | 2         | 0.13%   |
| Avision                                        | 2         | 0.13%   |
| Syscan                                         | 1         | 0.07%   |
| Salix Technology                               | 1         | 0.07%   |
| Papillon Systems                               | 1         | 0.07%   |
| Nikon                                          | 1         | 0.07%   |
| Minolta                                        | 1         | 0.07%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                                               | 121       | 7.95%   |
| Canon CanoScan LIDE 25                                                                | 92        | 6.04%   |
| Canon CanoScan LiDE 210                                                               | 84        | 5.52%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 82        | 5.39%   |
| Canon CanoScan LiDE 220                                                               | 69        | 4.53%   |
| Canon CanoScan LiDE 120                                                               | 58        | 3.81%   |
| Canon CanoScan LiDE 100                                                               | 46        | 3.02%   |
| HP ScanJet 2400c                                                                      | 39        | 2.56%   |
| Canon CanoScan N1240U/LiDE 30                                                         | 38        | 2.5%    |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 29        | 1.91%   |
| Canon CanoScan LiDE 60                                                                | 28        | 1.84%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 27        | 1.77%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 26        | 1.71%   |
| Canon CanoScan LiDE 200                                                               | 26        | 1.71%   |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 24        | 1.58%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]                                           | 23        | 1.51%   |
| Mustek Systems BearPaw 1200 CU Plus                                                   | 23        | 1.51%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 21        | 1.38%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                   | 21        | 1.38%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                                | 20        | 1.31%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                                    | 15        | 0.99%   |
| Mustek Systems SNAPSCAN e22                                                           | 15        | 0.99%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                                         | 13        | 0.85%   |
| Seiko Epson GT-7400U [Perfection 1270]                                                | 13        | 0.85%   |
| Canon CanoScan LiDE 90                                                                | 13        | 0.85%   |
| Canon CanoScan LiDE 700F                                                              | 13        | 0.85%   |
| Seiko Epson Scanner                                                                   | 12        | 0.79%   |
| Canon CanoScan N650U/N656U                                                            | 12        | 0.79%   |
| Canon CanoScan 4400F                                                                  | 12        | 0.79%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                                           | 11        | 0.72%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo]                               | 11        | 0.72%   |
| Mustek Systems ScanExpress 1200 UB                                                    | 11        | 0.72%   |
| Seiko Epson GT-F670 [Perfection V200 Photo]                                           | 9         | 0.59%   |
| Mustek Systems BearPaw 2400 CU Plus                                                   | 9         | 0.59%   |
| HP ScanJet 3800c                                                                      | 9         | 0.59%   |
| Canon CanoScan 9000F Mark II                                                          | 9         | 0.59%   |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]                                         | 8         | 0.53%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]                                     | 8         | 0.53%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]                                     | 8         | 0.53%   |
| HP ScanJet 5590                                                                       | 8         | 0.53%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 26560     | 21.42%  |
| IMC Networks                           | 11113     | 8.96%   |
| Microdia                               | 10305     | 8.31%   |
| Realtek Semiconductor                  | 9107      | 7.34%   |
| Logitech                               | 7341      | 5.92%   |
| Sunplus Innovation Technology          | 6372      | 5.14%   |
| Bison Electronics                      | 6317      | 5.09%   |
| Quanta                                 | 5509      | 4.44%   |
| Suyin                                  | 4374      | 3.53%   |
| Cheng Uei Precision Industry (Foxlink) | 4364      | 3.52%   |
| Apple                                  | 3705      | 2.99%   |
| Syntek                                 | 2909      | 2.35%   |
| Acer                                   | 2782      | 2.24%   |
| Lite-On Technology                     | 2305      | 1.86%   |
| Silicon Motion                         | 2223      | 1.79%   |
| Alcor Micro                            | 1793      | 1.45%   |
| Z-Star Microelectronics                | 1545      | 1.25%   |
| Luxvisions Innotech Limited            | 1445      | 1.17%   |
| Microsoft                              | 1358      | 1.1%    |
| Samsung Electronics                    | 1199      | 0.97%   |
| Ricoh                                  | 1112      | 0.9%    |
| Lenovo                                 | 685       | 0.55%   |
| Sonix Technology                       | 550       | 0.44%   |
| ALi                                    | 515       | 0.42%   |
| Importek                               | 465       | 0.37%   |
| Generalplus Technology                 | 449       | 0.36%   |
| KYE Systems (Mouse Systems)            | 359       | 0.29%   |
| GEMBIRD                                | 359       | 0.29%   |
| Primax Electronics                     | 348       | 0.28%   |
| Cubeternet                             | 306       | 0.25%   |
| Creative Technology                    | 306       | 0.25%   |
| SunplusIT                              | 302       | 0.24%   |
| DigiTech                               | 273       | 0.22%   |
| ARC International                      | 257       | 0.21%   |
| OmniVision Technologies                | 237       | 0.19%   |
| Aveo Technology                        | 221       | 0.18%   |
| Pixart Imaging                         | 201       | 0.16%   |
| Arkmicro Technologies                  | 198       | 0.16%   |
| MacroSilicon                           | 194       | 0.16%   |
| icSpring                               | 180       | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Chicony Integrated Camera               | 4648      | 3.72%   |
| Microdia Integrated_Webcam_HD           | 3774      | 3.02%   |
| Realtek Integrated_Webcam_HD            | 2873      | 2.3%    |
| IMC Networks USB2.0 HD UVC WebCam       | 2604      | 2.08%   |
| IMC Networks Integrated Camera          | 2599      | 2.08%   |
| Chicony HD WebCam                       | 2225      | 1.78%   |
| Sunplus Integrated_Webcam_HD            | 1976      | 1.58%   |
| Logitech Webcam C270                    | 1720      | 1.38%   |
| Bison Integrated Camera                 | 1694      | 1.36%   |
| IMC Networks USB2.0 VGA UVC WebCam      | 1671      | 1.34%   |
| Syntek Integrated Camera                | 1447      | 1.16%   |
| Logitech HD Pro Webcam C920             | 1279      | 1.02%   |
| Samsung Galaxy series, misc. (MTP mode) | 1175      | 0.94%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR      | 1089      | 0.87%   |
| Sunplus HD WebCam                       | 1000      | 0.8%    |
| Apple Built-in iSight                   | 966       | 0.77%   |
| Quanta HD User Facing                   | 961       | 0.77%   |
| Chicony HP HD Camera                    | 928       | 0.74%   |
| Chicony USB 2.0 Camera                  | 907       | 0.73%   |
| Microdia Integrated Webcam              | 868       | 0.69%   |
| Chicony HP Truevision HD                | 838       | 0.67%   |
| Chicony USB2.0 HD UVC WebCam            | 832       | 0.67%   |
| Chicony Lenovo EasyCamera               | 826       | 0.66%   |
| Lite-On Integrated Camera               | 810       | 0.65%   |
| Apple FaceTime HD Camera (Built-in)     | 808       | 0.65%   |
| Realtek USB Camera                      | 784       | 0.63%   |
| Chicony USB2.0 VGA UVC WebCam           | 763       | 0.61%   |
| Chicony HD User Facing                  | 757       | 0.61%   |
| Chicony HP TrueVision HD Camera         | 720       | 0.58%   |
| Chicony EasyCamera                      | 705       | 0.56%   |
| Bison HD Webcam                         | 704       | 0.56%   |
| Chicony USB2.0 Camera                   | 698       | 0.56%   |
| Quanta HP TrueVision HD Camera          | 678       | 0.54%   |
| Bison Lenovo EasyCamera                 | 669       | 0.54%   |
| Microdia USB 2.0 Camera                 | 663       | 0.53%   |
| Chicony VGA Webcam                      | 639       | 0.51%   |
| Acer Integrated Camera                  | 622       | 0.5%    |
| Apple FaceTime HD Camera                | 618       | 0.49%   |
| Bison Lenovo Integrated Webcam          | 601       | 0.48%   |
| Chicony HP Wide Vision HD Camera        | 592       | 0.47%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 7146      | 33.94%  |
| Synaptics                          | 5557      | 26.4%   |
| Shenzhen Goodix Technology         | 2923      | 13.88%  |
| AuthenTec                          | 1460      | 6.93%   |
| Elan Microelectronics              | 1207      | 5.73%   |
| Upek                               | 1201      | 5.7%    |
| LighTuning Technology              | 860       | 4.08%   |
| STMicroelectronics                 | 368       | 1.75%   |
| Samsung Electronics                | 85        | 0.4%    |
| Focal-systems.Corp                 | 84        | 0.4%    |
| Realtek USB2.0 Finger Print Bridge | 83        | 0.39%   |
| DigitalPersona                     | 22        | 0.1%    |
| HOLTEK                             | 20        | 0.09%   |
| Microsoft                          | 13        | 0.06%   |
| Dell                               | 9         | 0.04%   |
| Futronic Technology                | 4         | 0.02%   |
| Next Biometrics                    | 3         | 0.01%   |
| Gingytech                          | 3         | 0.01%   |
| GDMicroelectronics                 | 3         | 0.01%   |
| Suprema                            | 2         | 0.01%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1686      | 8.01%   |
| Shenzhen Goodix  FingerPrint Device                                        | 1567      | 7.44%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1511      | 7.18%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1108      | 5.26%   |
| Shenzhen Goodix Fingerprint Reader                                         | 888       | 4.22%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 818       | 3.89%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 749       | 3.56%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 738       | 3.51%   |
| Validity Sensors Synaptics WBDI                                            | 583       | 2.77%   |
| Elan ELAN:Fingerprint                                                      | 544       | 2.58%   |
| Validity Sensors VFS491                                                    | 489       | 2.32%   |
| Validity Sensors Fingerprint scanner                                       | 487       | 2.31%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 471       | 2.24%   |
| Elan ELAN:ARM-M4                                                           | 471       | 2.24%   |
| Shenzhen Goodix FingerPrint                                                | 468       | 2.22%   |
| AuthenTec AES2810                                                          | 456       | 2.17%   |
| Synaptics  WBDI                                                            | 452       | 2.15%   |
| Synaptics UWP WBDI                                                         | 437       | 2.08%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 423       | 2.01%   |
| Synaptics WBDI                                                             | 393       | 1.87%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 378       | 1.8%    |
| STMicroelectronics Fingerprint Reader                                      | 366       | 1.74%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 351       | 1.67%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 349       | 1.66%   |
| Synaptics Fingerprint reader [HP G6]                                       | 336       | 1.6%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 329       | 1.56%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 298       | 1.42%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 289       | 1.37%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 285       | 1.35%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 248       | 1.18%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 246       | 1.17%   |
| AuthenTec AES1600                                                          | 237       | 1.13%   |
| AuthenTec Fingerprint Sensor                                               | 205       | 0.97%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 204       | 0.97%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 177       | 0.84%   |
| Synaptics UWP WBDI Device                                                  | 156       | 0.74%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 147       | 0.7%    |
| LighTuning Fingerprint Reader                                              | 140       | 0.66%   |
| Elan WBF Fingerprint Sensor                                                | 140       | 0.66%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 125       | 0.59%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 3923      | 45%     |
| Alcor Micro                       | 2303      | 26.42%  |
| O2 Micro                          | 648       | 7.43%   |
| Upek                              | 503       | 5.77%   |
| Lenovo                            | 449       | 5.15%   |
| Gemalto (was Gemplus)             | 135       | 1.55%   |
| SCM Microsystems                  | 114       | 1.31%   |
| Advanced Card Systems             | 88        | 1.01%   |
| OmniKey                           | 80        | 0.92%   |
| Realtek Semiconductor             | 59        | 0.68%   |
| Yubico.com                        | 58        | 0.67%   |
| Aladdin Knowledge Systems         | 47        | 0.54%   |
| Clay Logic                        | 32        | 0.37%   |
| Reiner SCT Kartensysteme          | 31        | 0.36%   |
| Cherry                            | 30        | 0.34%   |
| Chicony Electronics               | 25        | 0.29%   |
| VASCO Data Security International | 24        | 0.28%   |
| Aktiv                             | 22        | 0.25%   |
| BIT4ID                            | 21        | 0.24%   |
| Hewlett-Packard                   | 19        | 0.22%   |
| Giesecke & Devrient               | 14        | 0.16%   |
| Fujitsu Siemens Computers         | 14        | 0.16%   |
| Aladdin R.D.                      | 13        | 0.15%   |
| Athena Smartcard Solutions        | 10        | 0.11%   |
| Watchdata                         | 7         | 0.08%   |
| C3PO                              | 6         | 0.07%   |
| Purism, SPC                       | 5         | 0.06%   |
| In Focus Systems                  | 5         | 0.06%   |
| NXP Semiconductors                | 4         | 0.05%   |
| Kobil Systems                     | 4         | 0.05%   |
| Castles Technology                | 4         | 0.05%   |
| Microchip Technology              | 3         | 0.03%   |
| Feitian Technologies              | 3         | 0.03%   |
| Jing-Mold Enterprise              | 2         | 0.02%   |
| Avtor                             | 2         | 0.02%   |
| ST-Ericsson                       | 1         | 0.01%   |
| SpringCard                        | 1         | 0.01%   |
| Precise Biometrics                | 1         | 0.01%   |
| Mako Technologies                 | 1         | 0.01%   |
| MagTek                            | 1         | 0.01%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 2253      | 25.83%  |
| Broadcom BCM5880 Secure Applications Processor                               | 1456      | 16.69%  |
| Broadcom 5880                                                                | 915       | 10.49%  |
| Broadcom 58200                                                               | 790       | 9.06%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 732       | 8.39%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 556       | 6.37%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 503       | 5.77%   |
| Lenovo Integrated Smart Card Reader                                          | 445       | 5.1%    |
| O2 Micro Oz776 SmartCard Reader                                              | 92        | 1.05%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 79        | 0.91%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 59        | 0.68%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 52        | 0.6%    |
| Alcor Micro Watchdata W 1981                                                 | 47        | 0.54%   |
| Aladdin Knowledge Systems Token JC                                           | 47        | 0.54%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 46        | 0.53%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 43        | 0.49%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 41        | 0.47%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 34        | 0.39%   |
| OmniKey CardMan 3021 / 3121                                                  | 26        | 0.3%    |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 25        | 0.29%   |
| Clay Logic Nitrokey Pro                                                      | 23        | 0.26%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 21        | 0.24%   |
| Aktiv Rutoken lite                                                           | 21        | 0.24%   |
| OmniKey CardMan 1021                                                         | 20        | 0.23%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 20        | 0.23%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 19        | 0.22%   |
| Advanced Card Systems ACR122U                                                | 19        | 0.22%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 18        | 0.21%   |
| BIT4ID miniLector EVO                                                        | 18        | 0.21%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 14        | 0.16%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 12        | 0.14%   |
| OmniKey CardMan 4321                                                         | 11        | 0.13%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 11        | 0.13%   |
| Aladdin R.D. JaCarta                                                         | 11        | 0.13%   |
| Athena Smartcard Solutions ASEDrive CCID                                     | 10        | 0.11%   |
| Advanced Card Systems ACR39U                                                 | 10        | 0.11%   |
| VASCO Data Security International DIGIPASS 870                               | 9         | 0.1%    |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 9         | 0.1%    |
| SCM Microsystems SCR331 SmartCard Reader                                     | 9         | 0.1%    |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 9         | 0.1%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 154042    | 70.35%  |
| 1     | 51589     | 23.56%  |
| 2     | 10596     | 4.84%   |
| 3     | 1811      | 0.83%   |
| 4     | 553       | 0.25%   |
| 5     | 201       | 0.09%   |
| 6     | 94        | 0.04%   |
| 7     | 49        | 0.02%   |
| 8     | 26        | 0.01%   |
| 9     | 10        | 0.005%  |
| 10    | 5         | 0.002%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 20794     | 26.71%  |
| Graphics card            | 20156     | 25.89%  |
| Net/wireless             | 9434      | 12.12%  |
| Chipcard                 | 7617      | 9.78%   |
| Multimedia controller    | 4575      | 5.88%   |
| Communication controller | 3450      | 4.43%   |
| Bluetooth                | 2221      | 2.85%   |
| Camera                   | 2102      | 2.7%    |
| Unassigned class         | 1692      | 2.17%   |
| Sound                    | 1241      | 1.59%   |
| Storage                  | 1160      | 1.49%   |
| Net/ethernet             | 763       | 0.98%   |
| Card reader              | 709       | 0.91%   |
| Network                  | 447       | 0.57%   |
| Modem                    | 420       | 0.54%   |
| Flash memory             | 263       | 0.34%   |
| Storage/raid             | 204       | 0.26%   |
| Dvb card                 | 161       | 0.21%   |
| Storage/ide              | 133       | 0.17%   |
| Firewire controller      | 122       | 0.16%   |
| Storage/ata              | 52        | 0.07%   |
| Storage/nvme             | 49        | 0.06%   |
| Tv card                  | 41        | 0.05%   |
| Wireless                 | 24        | 0.03%   |
| Video                    | 17        | 0.02%   |
| Unclassified device      | 16        | 0.02%   |

