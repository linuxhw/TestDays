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

Total: 4821

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | ProBook 440 G4              | Notebook    | [810959ffa7](https://linux-hardware.org/?probe=810959ffa7) | Oct 01, 2023 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [6c314cd812](https://linux-hardware.org/?probe=6c314cd812) | Oct 01, 2023 |
| Lenovo        | IdeaPad Y700-15ACZ 80NY     | Notebook    | [12d98aba86](https://linux-hardware.org/?probe=12d98aba86) | Oct 01, 2023 |
| HP            | Dragonfly 13.5 inch G4 N... | Notebook    | [8fabc36e1c](https://linux-hardware.org/?probe=8fabc36e1c) | Oct 01, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [c69ebf2472](https://linux-hardware.org/?probe=c69ebf2472) | Oct 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [59dcd18330](https://linux-hardware.org/?probe=59dcd18330) | Sep 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [a6d0762090](https://linux-hardware.org/?probe=a6d0762090) | Sep 30, 2023 |
| HP            | Pro Tablet 608 G1           | Notebook    | [14fcb9ce4b](https://linux-hardware.org/?probe=14fcb9ce4b) | Sep 30, 2023 |
| HP            | Pro Tablet 608 G1           | Notebook    | [ab84386c83](https://linux-hardware.org/?probe=ab84386c83) | Sep 30, 2023 |
| HP            | 8054                        | Desktop     | [20f337b1e7](https://linux-hardware.org/?probe=20f337b1e7) | Sep 29, 2023 |
| Positivo      | C14CR01                     | Notebook    | [11b171838d](https://linux-hardware.org/?probe=11b171838d) | Sep 29, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [55b44bb456](https://linux-hardware.org/?probe=55b44bb456) | Sep 29, 2023 |
| System76      | Darter Pro                  | Notebook    | [d8b78103d5](https://linux-hardware.org/?probe=d8b78103d5) | Sep 29, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | Notebook    | [fb1c2503cf](https://linux-hardware.org/?probe=fb1c2503cf) | Sep 29, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [109490039d](https://linux-hardware.org/?probe=109490039d) | Sep 29, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [960cd34617](https://linux-hardware.org/?probe=960cd34617) | Sep 29, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | Notebook    | [e23bfd302c](https://linux-hardware.org/?probe=e23bfd302c) | Sep 28, 2023 |
| AZW           | SER V1                      | Desktop     | [10660522cb](https://linux-hardware.org/?probe=10660522cb) | Sep 28, 2023 |
| Toshiba       | Satellite P775              | Notebook    | [7269165fd9](https://linux-hardware.org/?probe=7269165fd9) | Sep 28, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [b0c2b630a6](https://linux-hardware.org/?probe=b0c2b630a6) | Sep 28, 2023 |
| ASRock        | A520M-HDV                   | Desktop     | [d19f334f02](https://linux-hardware.org/?probe=d19f334f02) | Sep 28, 2023 |
| MSI           | PRO Z690-A WIFI             | Desktop     | [2ede90f6eb](https://linux-hardware.org/?probe=2ede90f6eb) | Sep 28, 2023 |
| System76      | Oryx Pro                    | Notebook    | [f06316545d](https://linux-hardware.org/?probe=f06316545d) | Sep 28, 2023 |
| Acer          | Aspire VN7-791G             | Notebook    | [0cfe515d00](https://linux-hardware.org/?probe=0cfe515d00) | Sep 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [7c13a64c8a](https://linux-hardware.org/?probe=7c13a64c8a) | Sep 27, 2023 |
| Dell          | Latitude 5480               | Notebook    | [8dd1695b2c](https://linux-hardware.org/?probe=8dd1695b2c) | Sep 27, 2023 |
| System76      | Lemur Pro                   | Notebook    | [6013ab7f8a](https://linux-hardware.org/?probe=6013ab7f8a) | Sep 27, 2023 |
| Dell          | Latitude E7440              | Notebook    | [9e117fe599](https://linux-hardware.org/?probe=9e117fe599) | Sep 27, 2023 |
| HONOR         | NBR-WAX9                    | Notebook    | [68556b1e09](https://linux-hardware.org/?probe=68556b1e09) | Sep 27, 2023 |
| HONOR         | NBR-WAX9                    | Notebook    | [056de6b9b3](https://linux-hardware.org/?probe=056de6b9b3) | Sep 27, 2023 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [9d86e194aa](https://linux-hardware.org/?probe=9d86e194aa) | Sep 27, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [240ff7b72a](https://linux-hardware.org/?probe=240ff7b72a) | Sep 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [d9665a6ffd](https://linux-hardware.org/?probe=d9665a6ffd) | Sep 27, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [f9f08875e1](https://linux-hardware.org/?probe=f9f08875e1) | Sep 26, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [09a71cddc4](https://linux-hardware.org/?probe=09a71cddc4) | Sep 26, 2023 |
| Lenovo        | Yoga 710-14IKB 80V4         | Convertible | [f11867f0b7](https://linux-hardware.org/?probe=f11867f0b7) | Sep 26, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [5a73611f4d](https://linux-hardware.org/?probe=5a73611f4d) | Sep 26, 2023 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [0a5cc18946](https://linux-hardware.org/?probe=0a5cc18946) | Sep 26, 2023 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [4259a21921](https://linux-hardware.org/?probe=4259a21921) | Sep 26, 2023 |
| MSI           | Summit E13FlipEvo A12MT     | Notebook    | [5fa9f0dde2](https://linux-hardware.org/?probe=5fa9f0dde2) | Sep 26, 2023 |
| Gigabyte      | B760I AORUS PRO DDR4        | Desktop     | [2fe436c443](https://linux-hardware.org/?probe=2fe436c443) | Sep 26, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [a58111d9ae](https://linux-hardware.org/?probe=a58111d9ae) | Sep 25, 2023 |
| HUAWEI        | NbDE-WXX9                   | Notebook    | [b3990570ee](https://linux-hardware.org/?probe=b3990570ee) | Sep 25, 2023 |
| HP            | 250 G4                      | Notebook    | [6e475cbb1f](https://linux-hardware.org/?probe=6e475cbb1f) | Sep 25, 2023 |
| HP            | 250 G4                      | Notebook    | [9543354fea](https://linux-hardware.org/?probe=9543354fea) | Sep 25, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [ae755aa7e3](https://linux-hardware.org/?probe=ae755aa7e3) | Sep 25, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [9de1c7395f](https://linux-hardware.org/?probe=9de1c7395f) | Sep 25, 2023 |
| ASUSTek       | M4A79T Deluxe               | Desktop     | [ac151127e1](https://linux-hardware.org/?probe=ac151127e1) | Sep 25, 2023 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [cb2b1325cc](https://linux-hardware.org/?probe=cb2b1325cc) | Sep 25, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [f934062b23](https://linux-hardware.org/?probe=f934062b23) | Sep 25, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [a7eb798aed](https://linux-hardware.org/?probe=a7eb798aed) | Sep 25, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [ac45698051](https://linux-hardware.org/?probe=ac45698051) | Sep 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [7d18eb441e](https://linux-hardware.org/?probe=7d18eb441e) | Sep 24, 2023 |
| Fujitsu       | LIFEBOOK A557               | Notebook    | [e66c8c9ca7](https://linux-hardware.org/?probe=e66c8c9ca7) | Sep 24, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [dfe5d4faaa](https://linux-hardware.org/?probe=dfe5d4faaa) | Sep 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [8318fdeb5b](https://linux-hardware.org/?probe=8318fdeb5b) | Sep 24, 2023 |
| Dell          | System XPS L502X            | Notebook    | [22d93fe76c](https://linux-hardware.org/?probe=22d93fe76c) | Sep 24, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [7aa2ea2853](https://linux-hardware.org/?probe=7aa2ea2853) | Sep 24, 2023 |
| Dell          | System XPS L502X            | Notebook    | [a1d4f683c1](https://linux-hardware.org/?probe=a1d4f683c1) | Sep 24, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | Desktop     | [3346cccd71](https://linux-hardware.org/?probe=3346cccd71) | Sep 24, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [7980181fcb](https://linux-hardware.org/?probe=7980181fcb) | Sep 24, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [7119229a1b](https://linux-hardware.org/?probe=7119229a1b) | Sep 24, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a3e2e5f3c0](https://linux-hardware.org/?probe=a3e2e5f3c0) | Sep 24, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [b358b656c6](https://linux-hardware.org/?probe=b358b656c6) | Sep 24, 2023 |
| ASUSTek       | PN53-G                      | Mini pc     | [f4a96c9156](https://linux-hardware.org/?probe=f4a96c9156) | Sep 24, 2023 |
| Toshiba       | TECRA X40-E                 | Notebook    | [280f949acc](https://linux-hardware.org/?probe=280f949acc) | Sep 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [9be7572b83](https://linux-hardware.org/?probe=9be7572b83) | Sep 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [b063963175](https://linux-hardware.org/?probe=b063963175) | Sep 23, 2023 |
| HP            | 250 G4                      | Notebook    | [5290896e7d](https://linux-hardware.org/?probe=5290896e7d) | Sep 23, 2023 |
| System76      | Gazelle                     | Notebook    | [2e31a65d58](https://linux-hardware.org/?probe=2e31a65d58) | Sep 23, 2023 |
| MSI           | X399 SLI PLUS               | Desktop     | [1c755bb49f](https://linux-hardware.org/?probe=1c755bb49f) | Sep 23, 2023 |
| ASUSTek       | ROG Maximus Z690 HERO EV... | Desktop     | [32b162a364](https://linux-hardware.org/?probe=32b162a364) | Sep 23, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [6656c28ec7](https://linux-hardware.org/?probe=6656c28ec7) | Sep 23, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [8b16720f22](https://linux-hardware.org/?probe=8b16720f22) | Sep 23, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [9867cb03bb](https://linux-hardware.org/?probe=9867cb03bb) | Sep 23, 2023 |
| Dell          | 0GWHMW A00                  | Desktop     | [d344d1e396](https://linux-hardware.org/?probe=d344d1e396) | Sep 23, 2023 |
| Dell          | Vostro 5481                 | Notebook    | [c416e12adb](https://linux-hardware.org/?probe=c416e12adb) | Sep 22, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [31fc587bda](https://linux-hardware.org/?probe=31fc587bda) | Sep 22, 2023 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [4679088d4e](https://linux-hardware.org/?probe=4679088d4e) | Sep 22, 2023 |
| ASUSTek       | ROG Strix G814JZ_G814JZ     | Notebook    | [2a6c2ef738](https://linux-hardware.org/?probe=2a6c2ef738) | Sep 22, 2023 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | Notebook    | [726a5f4cf5](https://linux-hardware.org/?probe=726a5f4cf5) | Sep 22, 2023 |
| HUAWEI        | KPL-W0X                     | Notebook    | [3154e03d3f](https://linux-hardware.org/?probe=3154e03d3f) | Sep 22, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [504ed03ead](https://linux-hardware.org/?probe=504ed03ead) | Sep 22, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [1d9ae81bf1](https://linux-hardware.org/?probe=1d9ae81bf1) | Sep 22, 2023 |
| Notebook      | NH50_70RH                   | Notebook    | [57070abf3c](https://linux-hardware.org/?probe=57070abf3c) | Sep 21, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [19d1333b4f](https://linux-hardware.org/?probe=19d1333b4f) | Sep 21, 2023 |
| Dell          | 0F6X5P A00                  | Desktop     | [5e45e8b196](https://linux-hardware.org/?probe=5e45e8b196) | Sep 21, 2023 |
| System76      | Darter Pro                  | Notebook    | [3266f46a3b](https://linux-hardware.org/?probe=3266f46a3b) | Sep 20, 2023 |
| Dell          | Precision 5680              | Notebook    | [a75a75f080](https://linux-hardware.org/?probe=a75a75f080) | Sep 20, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [a97463154d](https://linux-hardware.org/?probe=a97463154d) | Sep 20, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [cbc4ec2df0](https://linux-hardware.org/?probe=cbc4ec2df0) | Sep 20, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [43edd5f49f](https://linux-hardware.org/?probe=43edd5f49f) | Sep 20, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [a8b35a2b8f](https://linux-hardware.org/?probe=a8b35a2b8f) | Sep 19, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [8adb5c3a12](https://linux-hardware.org/?probe=8adb5c3a12) | Sep 19, 2023 |
| Framework     | Laptop                      | Notebook    | [f379873c4b](https://linux-hardware.org/?probe=f379873c4b) | Sep 19, 2023 |
| HP            | Pavilion 15                 | Notebook    | [eb15fe383c](https://linux-hardware.org/?probe=eb15fe383c) | Sep 18, 2023 |
| HP            | Pavilion 15                 | Notebook    | [fb86634643](https://linux-hardware.org/?probe=fb86634643) | Sep 18, 2023 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [e1805d26c3](https://linux-hardware.org/?probe=e1805d26c3) | Sep 17, 2023 |
| HP            | Dev One Notebook PC         | Notebook    | [2606a8d1c1](https://linux-hardware.org/?probe=2606a8d1c1) | Sep 17, 2023 |
| HONOR         | BMH-WCX9                    | Notebook    | [96a8945a17](https://linux-hardware.org/?probe=96a8945a17) | Sep 17, 2023 |
| ASRockRack    | Z490D4U-2L2T                | Desktop     | [0d43dbb11d](https://linux-hardware.org/?probe=0d43dbb11d) | Sep 17, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [e0371fc03e](https://linux-hardware.org/?probe=e0371fc03e) | Sep 17, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [43bf92a01b](https://linux-hardware.org/?probe=43bf92a01b) | Sep 17, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [797e19424f](https://linux-hardware.org/?probe=797e19424f) | Sep 16, 2023 |
| Gigabyte      | Z270X-UD5-CF                | Desktop     | [5c77a043ae](https://linux-hardware.org/?probe=5c77a043ae) | Sep 15, 2023 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [35bc7480cb](https://linux-hardware.org/?probe=35bc7480cb) | Sep 15, 2023 |
| Unknown       | Unknown                     | Notebook    | [ae1fde8210](https://linux-hardware.org/?probe=ae1fde8210) | Sep 15, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | Notebook    | [98dbf213e7](https://linux-hardware.org/?probe=98dbf213e7) | Sep 15, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | Notebook    | [5150bae6bd](https://linux-hardware.org/?probe=5150bae6bd) | Sep 15, 2023 |
| ASUSTek       | ROG STRIX B660-A GAMING ... | Desktop     | [efda5ec51a](https://linux-hardware.org/?probe=efda5ec51a) | Sep 15, 2023 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [175e57d54f](https://linux-hardware.org/?probe=175e57d54f) | Sep 15, 2023 |
| Digibras      | CL341                       | Notebook    | [a358f5d40c](https://linux-hardware.org/?probe=a358f5d40c) | Sep 15, 2023 |
| Lenovo        | Slim Pro 9 14IRP8 83BV      | Notebook    | [bc86928972](https://linux-hardware.org/?probe=bc86928972) | Sep 15, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | Notebook    | [4f6e19f508](https://linux-hardware.org/?probe=4f6e19f508) | Sep 14, 2023 |
| ASUSTek       | ROG STRIX B550-XE GAMING... | Desktop     | [ebac37bdbd](https://linux-hardware.org/?probe=ebac37bdbd) | Sep 14, 2023 |
| ASUSTek       | X556URK                     | Notebook    | [0996de9eac](https://linux-hardware.org/?probe=0996de9eac) | Sep 14, 2023 |
| Dell          | Latitude 7440               | Notebook    | [cd8e3aa6ed](https://linux-hardware.org/?probe=cd8e3aa6ed) | Sep 14, 2023 |
| realme        | RMNBXXXX                    | Notebook    | [7f93463d6a](https://linux-hardware.org/?probe=7f93463d6a) | Sep 14, 2023 |
| realme        | RMNBXXXX                    | Notebook    | [a635ea5599](https://linux-hardware.org/?probe=a635ea5599) | Sep 14, 2023 |
| Toshiba       | Satellite L735              | Notebook    | [fee724f874](https://linux-hardware.org/?probe=fee724f874) | Sep 14, 2023 |
| System76      | Pangolin                    | Notebook    | [c3803d0977](https://linux-hardware.org/?probe=c3803d0977) | Sep 13, 2023 |
| ASRock        | X470 Taichi                 | Desktop     | [49aca37979](https://linux-hardware.org/?probe=49aca37979) | Sep 13, 2023 |
| Lenovo        | 3717 NO DPK                 | Desktop     | [13870a17b4](https://linux-hardware.org/?probe=13870a17b4) | Sep 13, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | Notebook    | [ef5a6433f3](https://linux-hardware.org/?probe=ef5a6433f3) | Sep 13, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | Notebook    | [df7945af41](https://linux-hardware.org/?probe=df7945af41) | Sep 13, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [c159157024](https://linux-hardware.org/?probe=c159157024) | Sep 13, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [03e666ab42](https://linux-hardware.org/?probe=03e666ab42) | Sep 12, 2023 |
| Dell          | 0YXT71 A01                  | Desktop     | [36991ac5a6](https://linux-hardware.org/?probe=36991ac5a6) | Sep 11, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [9a23215875](https://linux-hardware.org/?probe=9a23215875) | Sep 11, 2023 |
| Schenker      | XMG NEO (TGL/M21)           | Notebook    | [8f9ada75e9](https://linux-hardware.org/?probe=8f9ada75e9) | Sep 11, 2023 |
| Dell          | Latitude E7250              | Notebook    | [44983ff513](https://linux-hardware.org/?probe=44983ff513) | Sep 11, 2023 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | Notebook    | [1b2d76894b](https://linux-hardware.org/?probe=1b2d76894b) | Sep 10, 2023 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [6fdfbcc425](https://linux-hardware.org/?probe=6fdfbcc425) | Sep 10, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [ca89a07b9e](https://linux-hardware.org/?probe=ca89a07b9e) | Sep 10, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [56bef39b59](https://linux-hardware.org/?probe=56bef39b59) | Sep 10, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | Notebook    | [a9caf49f0e](https://linux-hardware.org/?probe=a9caf49f0e) | Sep 09, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [a812c1659b](https://linux-hardware.org/?probe=a812c1659b) | Sep 09, 2023 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [375f82dc0c](https://linux-hardware.org/?probe=375f82dc0c) | Sep 09, 2023 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [de7d9282cd](https://linux-hardware.org/?probe=de7d9282cd) | Sep 09, 2023 |
| Lenovo        | V720-14 80Y1                | Notebook    | [ec869beffd](https://linux-hardware.org/?probe=ec869beffd) | Sep 09, 2023 |
| MSI           | MAG B560M BAZOOKA           | Desktop     | [c3ba2033e2](https://linux-hardware.org/?probe=c3ba2033e2) | Sep 09, 2023 |
| Gigabyte      | Q87M-MK                     | Desktop     | [1c45c834fe](https://linux-hardware.org/?probe=1c45c834fe) | Sep 09, 2023 |
| HP            | 1495                        | Desktop     | [b56f622d7a](https://linux-hardware.org/?probe=b56f622d7a) | Sep 09, 2023 |
| Apple         | Mac-65CE76090165799A iMa... | All in one  | [8442c861ed](https://linux-hardware.org/?probe=8442c861ed) | Sep 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [5fc227a0e8](https://linux-hardware.org/?probe=5fc227a0e8) | Sep 08, 2023 |
| Dell          | Vostro 5502                 | Notebook    | [a131efa36e](https://linux-hardware.org/?probe=a131efa36e) | Sep 08, 2023 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [bad7c8bf82](https://linux-hardware.org/?probe=bad7c8bf82) | Sep 08, 2023 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [57b82728d8](https://linux-hardware.org/?probe=57b82728d8) | Sep 08, 2023 |
| HP            | EliteBook 745 G5            | Notebook    | [05d61b5c23](https://linux-hardware.org/?probe=05d61b5c23) | Sep 08, 2023 |
| MSI           | P65 Creator 8RD             | Notebook    | [3eab920cfc](https://linux-hardware.org/?probe=3eab920cfc) | Sep 07, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [eae373ebd4](https://linux-hardware.org/?probe=eae373ebd4) | Sep 07, 2023 |
| MSI           | Alpha 15 A3DDK              | Notebook    | [9a87dfb80b](https://linux-hardware.org/?probe=9a87dfb80b) | Sep 07, 2023 |
| HP            | EliteBook 8760w             | Notebook    | [d061b57b29](https://linux-hardware.org/?probe=d061b57b29) | Sep 07, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [3221a3e5dd](https://linux-hardware.org/?probe=3221a3e5dd) | Sep 07, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [13bae1c4e9](https://linux-hardware.org/?probe=13bae1c4e9) | Sep 07, 2023 |
| Alienware     | m15 R7                      | Notebook    | [9e6b80bbf2](https://linux-hardware.org/?probe=9e6b80bbf2) | Sep 07, 2023 |
| Dell          | 0WN7Y6 A02                  | Desktop     | [aaf64e4624](https://linux-hardware.org/?probe=aaf64e4624) | Sep 07, 2023 |
| Biostar       | A58MD                       | Desktop     | [40f078fcfc](https://linux-hardware.org/?probe=40f078fcfc) | Sep 06, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [bfdd099826](https://linux-hardware.org/?probe=bfdd099826) | Sep 06, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [0692b6f878](https://linux-hardware.org/?probe=0692b6f878) | Sep 06, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [611bb4fe1a](https://linux-hardware.org/?probe=611bb4fe1a) | Sep 06, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [38f9d1abd9](https://linux-hardware.org/?probe=38f9d1abd9) | Sep 05, 2023 |
| MSI           | H310M PRO-VH PLUS           | Desktop     | [56f00eec4a](https://linux-hardware.org/?probe=56f00eec4a) | Sep 05, 2023 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | Notebook    | [27575898fe](https://linux-hardware.org/?probe=27575898fe) | Sep 05, 2023 |
| ZOTAC         | ZBOX-ECM73070C/53060C       | Mini pc     | [613e4acc75](https://linux-hardware.org/?probe=613e4acc75) | Sep 05, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [dda5b7f9c9](https://linux-hardware.org/?probe=dda5b7f9c9) | Sep 05, 2023 |
| Dell          | Inspiron 14 5420            | Notebook    | [70d0d79f77](https://linux-hardware.org/?probe=70d0d79f77) | Sep 05, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [a33ec74b50](https://linux-hardware.org/?probe=a33ec74b50) | Sep 05, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [d5cd8916d0](https://linux-hardware.org/?probe=d5cd8916d0) | Sep 05, 2023 |
| Gigabyte      | Z590 AORUS MASTER           | Desktop     | [40785211e9](https://linux-hardware.org/?probe=40785211e9) | Sep 05, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [11c016fb1b](https://linux-hardware.org/?probe=11c016fb1b) | Sep 05, 2023 |
| ASUSTek       | ROG STRIX B460-H GAMING     | Desktop     | [865ce7b55b](https://linux-hardware.org/?probe=865ce7b55b) | Sep 04, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [ee1a881e82](https://linux-hardware.org/?probe=ee1a881e82) | Sep 04, 2023 |
| System76      | Lemur Pro                   | Notebook    | [9ea11da090](https://linux-hardware.org/?probe=9ea11da090) | Sep 04, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | Notebook    | [68e90ee0cb](https://linux-hardware.org/?probe=68e90ee0cb) | Sep 04, 2023 |
| ASUSTek       | K53E                        | Notebook    | [5604fe515d](https://linux-hardware.org/?probe=5604fe515d) | Sep 04, 2023 |
| Dell          | XPS 17 9700                 | Notebook    | [e758c8955e](https://linux-hardware.org/?probe=e758c8955e) | Sep 03, 2023 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [a30ea8885d](https://linux-hardware.org/?probe=a30ea8885d) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [2ddf0c5c61](https://linux-hardware.org/?probe=2ddf0c5c61) | Sep 03, 2023 |
| HP            | 240 G8 Notebook PC          | Notebook    | [092ae0b34d](https://linux-hardware.org/?probe=092ae0b34d) | Sep 03, 2023 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [e9faf4759d](https://linux-hardware.org/?probe=e9faf4759d) | Sep 03, 2023 |
| Gigabyte      | Z97X-SLI-CF                 | Desktop     | [ffc201e884](https://linux-hardware.org/?probe=ffc201e884) | Sep 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [f2f5e496f1](https://linux-hardware.org/?probe=f2f5e496f1) | Sep 02, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [515e1f4bce](https://linux-hardware.org/?probe=515e1f4bce) | Sep 02, 2023 |
| Apple         | MacBookAir3,2               | Notebook    | [5ee8cbf433](https://linux-hardware.org/?probe=5ee8cbf433) | Sep 02, 2023 |
| Schenker      | VIA 15 Pro                  | Notebook    | [4a31ab4d2b](https://linux-hardware.org/?probe=4a31ab4d2b) | Sep 02, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [1c82c8d8b5](https://linux-hardware.org/?probe=1c82c8d8b5) | Sep 02, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [b4907a6220](https://linux-hardware.org/?probe=b4907a6220) | Sep 02, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [da8d60051c](https://linux-hardware.org/?probe=da8d60051c) | Sep 02, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [87e1726495](https://linux-hardware.org/?probe=87e1726495) | Sep 01, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [e73e853358](https://linux-hardware.org/?probe=e73e853358) | Sep 01, 2023 |
| MSI           | A320M-A PRO M2              | Desktop     | [6745b7e37d](https://linux-hardware.org/?probe=6745b7e37d) | Sep 01, 2023 |
| Gigabyte      | Z370 AORUS Gaming 7         | Desktop     | [6ddc9b767d](https://linux-hardware.org/?probe=6ddc9b767d) | Sep 01, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [76b83d4e93](https://linux-hardware.org/?probe=76b83d4e93) | Sep 01, 2023 |
| System76      | Thelio thelio-r3            | Desktop     | [d0cdea5d23](https://linux-hardware.org/?probe=d0cdea5d23) | Sep 01, 2023 |
| ASUSTek       | N550JV                      | Notebook    | [b2effdc956](https://linux-hardware.org/?probe=b2effdc956) | Sep 01, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [2433535726](https://linux-hardware.org/?probe=2433535726) | Sep 01, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [77c6379594](https://linux-hardware.org/?probe=77c6379594) | Sep 01, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [67f553625a](https://linux-hardware.org/?probe=67f553625a) | Sep 01, 2023 |
| Dell          | Latitude E7470              | Notebook    | [0580f1c293](https://linux-hardware.org/?probe=0580f1c293) | Sep 01, 2023 |
| Lenovo        | ThinkPad T450 20BUS0B000    | Notebook    | [1213d3bf46](https://linux-hardware.org/?probe=1213d3bf46) | Aug 31, 2023 |
| Acer          | Aspire E5-551G              | Notebook    | [628d865373](https://linux-hardware.org/?probe=628d865373) | Aug 31, 2023 |
| Gigabyte      | H97-HD3                     | Desktop     | [ba11958a48](https://linux-hardware.org/?probe=ba11958a48) | Aug 31, 2023 |
| Gigabyte      | H97-HD3                     | Desktop     | [158ed240bf](https://linux-hardware.org/?probe=158ed240bf) | Aug 31, 2023 |
| ASRock        | Q1900B-ITX                  | Desktop     | [875427cd72](https://linux-hardware.org/?probe=875427cd72) | Aug 31, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [3b890e064f](https://linux-hardware.org/?probe=3b890e064f) | Aug 31, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [6c5da44516](https://linux-hardware.org/?probe=6c5da44516) | Aug 31, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [085b3d4330](https://linux-hardware.org/?probe=085b3d4330) | Aug 31, 2023 |
| Google        | Kefka                       | Notebook    | [284517c2b3](https://linux-hardware.org/?probe=284517c2b3) | Aug 31, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [98b18bb67a](https://linux-hardware.org/?probe=98b18bb67a) | Aug 31, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [45f86c066d](https://linux-hardware.org/?probe=45f86c066d) | Aug 30, 2023 |
| Lenovo        | ThinkPad W520 427637U       | Notebook    | [5f995c7c48](https://linux-hardware.org/?probe=5f995c7c48) | Aug 30, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [84f61e2225](https://linux-hardware.org/?probe=84f61e2225) | Aug 30, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [641243c308](https://linux-hardware.org/?probe=641243c308) | Aug 30, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [5ba6fd6ca3](https://linux-hardware.org/?probe=5ba6fd6ca3) | Aug 30, 2023 |
| Google        | Kefka                       | Notebook    | [a018ae3fb5](https://linux-hardware.org/?probe=a018ae3fb5) | Aug 30, 2023 |
| Acer          | Aspire E5-571               | Notebook    | [500ef94276](https://linux-hardware.org/?probe=500ef94276) | Aug 29, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [90a72df8ef](https://linux-hardware.org/?probe=90a72df8ef) | Aug 29, 2023 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | Notebook    | [4904c007c7](https://linux-hardware.org/?probe=4904c007c7) | Aug 29, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [ba9dd7a62d](https://linux-hardware.org/?probe=ba9dd7a62d) | Aug 29, 2023 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [f1b8efb723](https://linux-hardware.org/?probe=f1b8efb723) | Aug 29, 2023 |
| ASUSTek       | ROG Strix G634JZ_G634JZ     | Notebook    | [481b37b0fc](https://linux-hardware.org/?probe=481b37b0fc) | Aug 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [ebebe5ddf7](https://linux-hardware.org/?probe=ebebe5ddf7) | Aug 29, 2023 |
| Dell          | Latitude 5330               | Notebook    | [7e63575d10](https://linux-hardware.org/?probe=7e63575d10) | Aug 29, 2023 |
| ASUSTek       | ROG STRIX B660-A GAMING ... | Desktop     | [0be67de1c9](https://linux-hardware.org/?probe=0be67de1c9) | Aug 29, 2023 |
| Lenovo        | ThinkPad T430s 2356CU8      | Notebook    | [2f669d797f](https://linux-hardware.org/?probe=2f669d797f) | Aug 29, 2023 |
| Lenovo        | ThinkPad T430s 2356CU8      | Notebook    | [39f2feeed5](https://linux-hardware.org/?probe=39f2feeed5) | Aug 29, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [4cdf174574](https://linux-hardware.org/?probe=4cdf174574) | Aug 29, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [6d2186fdd9](https://linux-hardware.org/?probe=6d2186fdd9) | Aug 28, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHC... | Notebook    | [de65d63e10](https://linux-hardware.org/?probe=de65d63e10) | Aug 28, 2023 |
| Lenovo        | Legion 5 15IMH 82CF         | Notebook    | [4d8ac47399](https://linux-hardware.org/?probe=4d8ac47399) | Aug 28, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHC... | Notebook    | [dc9a79314c](https://linux-hardware.org/?probe=dc9a79314c) | Aug 28, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [ef97f75590](https://linux-hardware.org/?probe=ef97f75590) | Aug 28, 2023 |
| Dell          | Precision 5510              | Notebook    | [c6d08d9c28](https://linux-hardware.org/?probe=c6d08d9c28) | Aug 27, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [b07775a194](https://linux-hardware.org/?probe=b07775a194) | Aug 27, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [c4be1d7e95](https://linux-hardware.org/?probe=c4be1d7e95) | Aug 27, 2023 |
| Lenovo        | ThinkPad T460 20FMS05K05    | Notebook    | [747e8d4f6a](https://linux-hardware.org/?probe=747e8d4f6a) | Aug 27, 2023 |
| Dell          | Precision M4600             | Notebook    | [b7fca4d2f9](https://linux-hardware.org/?probe=b7fca4d2f9) | Aug 27, 2023 |
| Unknown       | V00                         | Mini pc     | [b63adaac28](https://linux-hardware.org/?probe=b63adaac28) | Aug 27, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [9e0b5b0b7e](https://linux-hardware.org/?probe=9e0b5b0b7e) | Aug 26, 2023 |
| Dell          | Precision M6800             | Notebook    | [6aa5f8e441](https://linux-hardware.org/?probe=6aa5f8e441) | Aug 26, 2023 |
| Dell          | 0VRWRC A00                  | Desktop     | [e3a47f55c9](https://linux-hardware.org/?probe=e3a47f55c9) | Aug 26, 2023 |
| MSI           | PRO Z790-A WIFI             | Desktop     | [f3874bf2fc](https://linux-hardware.org/?probe=f3874bf2fc) | Aug 26, 2023 |
| HP            | ProBook 4730s               | Notebook    | [32f610b810](https://linux-hardware.org/?probe=32f610b810) | Aug 26, 2023 |
| Google        | Kasumi                      | Notebook    | [9af5f77257](https://linux-hardware.org/?probe=9af5f77257) | Aug 25, 2023 |
| System76      | Gazelle                     | Notebook    | [b3fb438915](https://linux-hardware.org/?probe=b3fb438915) | Aug 25, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [8d952e28e1](https://linux-hardware.org/?probe=8d952e28e1) | Aug 25, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [51d4eefbc9](https://linux-hardware.org/?probe=51d4eefbc9) | Aug 25, 2023 |
| System76      | Thelio Major thelio-majo... | Desktop     | [e5caa63b77](https://linux-hardware.org/?probe=e5caa63b77) | Aug 25, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [958521d2be](https://linux-hardware.org/?probe=958521d2be) | Aug 25, 2023 |
| MSI           | GE60 2OC\2OD\2OE            | Notebook    | [e2e304c9eb](https://linux-hardware.org/?probe=e2e304c9eb) | Aug 25, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [254f8aee40](https://linux-hardware.org/?probe=254f8aee40) | Aug 25, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [6f72852248](https://linux-hardware.org/?probe=6f72852248) | Aug 25, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [acc5fdd0f3](https://linux-hardware.org/?probe=acc5fdd0f3) | Aug 25, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [34fc2a5f83](https://linux-hardware.org/?probe=34fc2a5f83) | Aug 24, 2023 |
| Dell          | Latitude E7240              | Notebook    | [cb61859037](https://linux-hardware.org/?probe=cb61859037) | Aug 24, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [c0bf920a5b](https://linux-hardware.org/?probe=c0bf920a5b) | Aug 24, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [6cf9db7da7](https://linux-hardware.org/?probe=6cf9db7da7) | Aug 24, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [40660610aa](https://linux-hardware.org/?probe=40660610aa) | Aug 24, 2023 |
| Dell          | Latitude 7430               | Notebook    | [7daf0301c5](https://linux-hardware.org/?probe=7daf0301c5) | Aug 24, 2023 |
| Toshiba       | Satellite L655              | Notebook    | [18df557333](https://linux-hardware.org/?probe=18df557333) | Aug 24, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [82be53cac0](https://linux-hardware.org/?probe=82be53cac0) | Aug 23, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [2970428ad3](https://linux-hardware.org/?probe=2970428ad3) | Aug 23, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [5abce3a991](https://linux-hardware.org/?probe=5abce3a991) | Aug 23, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [b0ca2ee250](https://linux-hardware.org/?probe=b0ca2ee250) | Aug 23, 2023 |
| MSI           | GE60 2OC\2OD\2OE            | Notebook    | [50f079ae44](https://linux-hardware.org/?probe=50f079ae44) | Aug 23, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [6f0e38b5e8](https://linux-hardware.org/?probe=6f0e38b5e8) | Aug 23, 2023 |
| HP            | 18E7                        | Desktop     | [a78496c36e](https://linux-hardware.org/?probe=a78496c36e) | Aug 23, 2023 |
| Samsung       | 750TDA                      | Notebook    | [7b1ec96afa](https://linux-hardware.org/?probe=7b1ec96afa) | Aug 23, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | Notebook    | [4cd19df49e](https://linux-hardware.org/?probe=4cd19df49e) | Aug 23, 2023 |
| Gigabyte      | B550 VISION D-P             | Desktop     | [145d800029](https://linux-hardware.org/?probe=145d800029) | Aug 23, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2RV0... | Notebook    | [e8d2c8e1d5](https://linux-hardware.org/?probe=e8d2c8e1d5) | Aug 22, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | Notebook    | [fdd24243bf](https://linux-hardware.org/?probe=fdd24243bf) | Aug 22, 2023 |
| Acer          | Aspire A715-75G             | Notebook    | [54794fb9e8](https://linux-hardware.org/?probe=54794fb9e8) | Aug 22, 2023 |
| Supermicro    | X12SPA-TF                   | Server      | [b0d65c559f](https://linux-hardware.org/?probe=b0d65c559f) | Aug 22, 2023 |
| ASUSTek       | P7P55-M                     | Desktop     | [0f5028d5fc](https://linux-hardware.org/?probe=0f5028d5fc) | Aug 22, 2023 |
| Dell          | 07JJ74 A01                  | Server      | [d86049c586](https://linux-hardware.org/?probe=d86049c586) | Aug 21, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [be53b5931f](https://linux-hardware.org/?probe=be53b5931f) | Aug 21, 2023 |
| HP            | ProBook 4730s               | Notebook    | [5b4d88bc67](https://linux-hardware.org/?probe=5b4d88bc67) | Aug 21, 2023 |
| AZW           | GTR V02                     | Desktop     | [d699113f95](https://linux-hardware.org/?probe=d699113f95) | Aug 21, 2023 |
| Samsung       | 270E5G/270E5U               | Notebook    | [930d312c36](https://linux-hardware.org/?probe=930d312c36) | Aug 21, 2023 |
| Samsung       | 270E5G/270E5U               | Notebook    | [2bc8c24081](https://linux-hardware.org/?probe=2bc8c24081) | Aug 21, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [b66d308d42](https://linux-hardware.org/?probe=b66d308d42) | Aug 21, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [f9742049fc](https://linux-hardware.org/?probe=f9742049fc) | Aug 20, 2023 |
| ASUSTek       | ROG Flow Z13 GZ301ZE_GZ3... | Tablet      | [83b6cab3cd](https://linux-hardware.org/?probe=83b6cab3cd) | Aug 20, 2023 |
| System76      | Oryx Pro                    | Notebook    | [b7e0bd11e5](https://linux-hardware.org/?probe=b7e0bd11e5) | Aug 20, 2023 |
| Dell          | Precision 5520              | Notebook    | [42587aac96](https://linux-hardware.org/?probe=42587aac96) | Aug 20, 2023 |
| Dell          | Precision 5520              | Notebook    | [bec735d800](https://linux-hardware.org/?probe=bec735d800) | Aug 20, 2023 |
| NZXT          | N7 B550                     | Desktop     | [1f105eadd8](https://linux-hardware.org/?probe=1f105eadd8) | Aug 20, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [31861c8357](https://linux-hardware.org/?probe=31861c8357) | Aug 20, 2023 |
| Gigabyte      | Z270X-UD5-CF                | Desktop     | [04df52e837](https://linux-hardware.org/?probe=04df52e837) | Aug 20, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QR    | Notebook    | [5d063a6e59](https://linux-hardware.org/?probe=5d063a6e59) | Aug 19, 2023 |
| Lenovo        | B490 377224P                | Notebook    | [0e516ea22b](https://linux-hardware.org/?probe=0e516ea22b) | Aug 19, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [63d06430e4](https://linux-hardware.org/?probe=63d06430e4) | Aug 18, 2023 |
| HP            | 0266                        | Desktop     | [636546711d](https://linux-hardware.org/?probe=636546711d) | Aug 18, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [70eda3a12d](https://linux-hardware.org/?probe=70eda3a12d) | Aug 18, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [a77f908bb5](https://linux-hardware.org/?probe=a77f908bb5) | Aug 18, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [a1ab007f7f](https://linux-hardware.org/?probe=a1ab007f7f) | Aug 18, 2023 |
| ASUSTek       | P8Z77-I DELUXE              | Desktop     | [53c4af621d](https://linux-hardware.org/?probe=53c4af621d) | Aug 18, 2023 |
| ASUSTek       | U38N                        | Notebook    | [0e0f709353](https://linux-hardware.org/?probe=0e0f709353) | Aug 17, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [a6a7224d63](https://linux-hardware.org/?probe=a6a7224d63) | Aug 17, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [680fae2274](https://linux-hardware.org/?probe=680fae2274) | Aug 17, 2023 |
| HP            | 2AF7                        | Desktop     | [4e55d08586](https://linux-hardware.org/?probe=4e55d08586) | Aug 17, 2023 |
| ASUSTek       | Vivobook Go E1404FA_E140... | Notebook    | [43fd1aad67](https://linux-hardware.org/?probe=43fd1aad67) | Aug 17, 2023 |
| MSI           | Z87-GD65 GAMING             | Desktop     | [7c09135f98](https://linux-hardware.org/?probe=7c09135f98) | Aug 17, 2023 |
| System76      | Lemur Pro                   | Notebook    | [af3b387574](https://linux-hardware.org/?probe=af3b387574) | Aug 16, 2023 |
| HP            | Elite Dragonfly             | Convertible | [7419fe990e](https://linux-hardware.org/?probe=7419fe990e) | Aug 16, 2023 |
| Acer          | Aspire 5750                 | Notebook    | [ec4afb1917](https://linux-hardware.org/?probe=ec4afb1917) | Aug 16, 2023 |
| A-DATA Tec... | XENIA 14                    | Notebook    | [59faf4a458](https://linux-hardware.org/?probe=59faf4a458) | Aug 15, 2023 |
| A-DATA Tec... | XENIA 14                    | Notebook    | [537cce8a8e](https://linux-hardware.org/?probe=537cce8a8e) | Aug 15, 2023 |
| Positivo      | POS-RIQ470EN 11190998       | Desktop     | [1eec60309a](https://linux-hardware.org/?probe=1eec60309a) | Aug 15, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [c2cfa9bd7a](https://linux-hardware.org/?probe=c2cfa9bd7a) | Aug 15, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [0927025cfc](https://linux-hardware.org/?probe=0927025cfc) | Aug 15, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [431ac1b880](https://linux-hardware.org/?probe=431ac1b880) | Aug 15, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [ce22773504](https://linux-hardware.org/?probe=ce22773504) | Aug 15, 2023 |
| Intel         | B75A                        | Desktop     | [c081fb2ca8](https://linux-hardware.org/?probe=c081fb2ca8) | Aug 15, 2023 |
| System76      | Galago Pro                  | Notebook    | [54348f9c55](https://linux-hardware.org/?probe=54348f9c55) | Aug 14, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [61ff7ac5f1](https://linux-hardware.org/?probe=61ff7ac5f1) | Aug 14, 2023 |
| Apple         | MacBookPro16,1              | Notebook    | [18b513f5f0](https://linux-hardware.org/?probe=18b513f5f0) | Aug 14, 2023 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | Notebook    | [1f27d0f994](https://linux-hardware.org/?probe=1f27d0f994) | Aug 14, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [0b194349eb](https://linux-hardware.org/?probe=0b194349eb) | Aug 14, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | Desktop     | [9a8e4bc08d](https://linux-hardware.org/?probe=9a8e4bc08d) | Aug 14, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [302fb03dce](https://linux-hardware.org/?probe=302fb03dce) | Aug 13, 2023 |
| HP            | ProBook 4540s               | Notebook    | [84dbf6b759](https://linux-hardware.org/?probe=84dbf6b759) | Aug 13, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [2c2aca991d](https://linux-hardware.org/?probe=2c2aca991d) | Aug 13, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [ee66d3a81c](https://linux-hardware.org/?probe=ee66d3a81c) | Aug 13, 2023 |
| MSI           | X99A GODLIKE GAMING         | Desktop     | [b87f112952](https://linux-hardware.org/?probe=b87f112952) | Aug 13, 2023 |
| Alienware     | 0K9TKY A00                  | Desktop     | [edf714498f](https://linux-hardware.org/?probe=edf714498f) | Aug 13, 2023 |
| Alienware     | 0K9TKY A00                  | Desktop     | [213d229837](https://linux-hardware.org/?probe=213d229837) | Aug 13, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [ae586a02aa](https://linux-hardware.org/?probe=ae586a02aa) | Aug 13, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [823e276406](https://linux-hardware.org/?probe=823e276406) | Aug 13, 2023 |
| GPU Compan... | GWNR71517                   | Notebook    | [a38cee5cc9](https://linux-hardware.org/?probe=a38cee5cc9) | Aug 12, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [eb83156c5f](https://linux-hardware.org/?probe=eb83156c5f) | Aug 12, 2023 |
| Intel         | B75A                        | Desktop     | [91f9e56ace](https://linux-hardware.org/?probe=91f9e56ace) | Aug 12, 2023 |
| Acer          | Aspire ES1-520              | Notebook    | [a47415983e](https://linux-hardware.org/?probe=a47415983e) | Aug 12, 2023 |
| Lenovo        | ThinkPad L13 20R3CTO1WW     | Notebook    | [6ac135c81c](https://linux-hardware.org/?probe=6ac135c81c) | Aug 12, 2023 |
| ASUSTek       | K53TK                       | Notebook    | [db9f130ade](https://linux-hardware.org/?probe=db9f130ade) | Aug 12, 2023 |
| Dell          | G7 7588                     | Notebook    | [48faf46c2c](https://linux-hardware.org/?probe=48faf46c2c) | Aug 12, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [2832e701f2](https://linux-hardware.org/?probe=2832e701f2) | Aug 12, 2023 |
| Lenovo        | Yoga Pro 9 14IRP8 83BU      | Notebook    | [f46a14b981](https://linux-hardware.org/?probe=f46a14b981) | Aug 12, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [2c92ed92eb](https://linux-hardware.org/?probe=2c92ed92eb) | Aug 12, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [544810db31](https://linux-hardware.org/?probe=544810db31) | Aug 12, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [580fda2e6b](https://linux-hardware.org/?probe=580fda2e6b) | Aug 12, 2023 |
| MSI           | A55M-E33                    | Desktop     | [7d538db764](https://linux-hardware.org/?probe=7d538db764) | Aug 12, 2023 |
| MSI           | A55M-E33                    | Desktop     | [9e64865fbc](https://linux-hardware.org/?probe=9e64865fbc) | Aug 12, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [0d45e9e048](https://linux-hardware.org/?probe=0d45e9e048) | Aug 12, 2023 |
| Dell          | Precision M4600             | Notebook    | [f97367efac](https://linux-hardware.org/?probe=f97367efac) | Aug 11, 2023 |
| Lenovo        | IdeaPad 310-15IAP 80TT      | Notebook    | [361e073b5c](https://linux-hardware.org/?probe=361e073b5c) | Aug 11, 2023 |
| Gigabyte      | Z790 GAMING X AX            | Desktop     | [a6d2358585](https://linux-hardware.org/?probe=a6d2358585) | Aug 11, 2023 |
| Acer          | Nitro AN715-51              | Notebook    | [ea972c8686](https://linux-hardware.org/?probe=ea972c8686) | Aug 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [cf0d6729b4](https://linux-hardware.org/?probe=cf0d6729b4) | Aug 11, 2023 |
| ASRock        | B650M-HDV/M.2               | Desktop     | [ffd395aee0](https://linux-hardware.org/?probe=ffd395aee0) | Aug 11, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [e22f71b79d](https://linux-hardware.org/?probe=e22f71b79d) | Aug 11, 2023 |
| ASUSTek       | X751LD                      | Notebook    | [e98d8d116d](https://linux-hardware.org/?probe=e98d8d116d) | Aug 10, 2023 |
| Gigabyte      | H410M S2 V2                 | Desktop     | [d4c5a12d06](https://linux-hardware.org/?probe=d4c5a12d06) | Aug 10, 2023 |
| HP            | 2AF9                        | Desktop     | [b31b796804](https://linux-hardware.org/?probe=b31b796804) | Aug 10, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [7f91d6f9d8](https://linux-hardware.org/?probe=7f91d6f9d8) | Aug 10, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [739bc450b8](https://linux-hardware.org/?probe=739bc450b8) | Aug 09, 2023 |
| Acer          | Nitro AN517-55              | Notebook    | [b77ff095f8](https://linux-hardware.org/?probe=b77ff095f8) | Aug 09, 2023 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [b1a8fc0704](https://linux-hardware.org/?probe=b1a8fc0704) | Aug 09, 2023 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [920797388b](https://linux-hardware.org/?probe=920797388b) | Aug 09, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | Notebook    | [6415840d5b](https://linux-hardware.org/?probe=6415840d5b) | Aug 09, 2023 |
| HP            | ProBook 4330s               | Notebook    | [5c854bed9f](https://linux-hardware.org/?probe=5c854bed9f) | Aug 09, 2023 |
| HP            | ProBook 4330s               | Notebook    | [d23ce497d2](https://linux-hardware.org/?probe=d23ce497d2) | Aug 09, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [13b739e83a](https://linux-hardware.org/?probe=13b739e83a) | Aug 09, 2023 |
| System76      | Darter Pro                  | Notebook    | [5162d61c01](https://linux-hardware.org/?probe=5162d61c01) | Aug 09, 2023 |
| NZXT          | N7 Z590                     | Desktop     | [3831033bdc](https://linux-hardware.org/?probe=3831033bdc) | Aug 09, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [b041192310](https://linux-hardware.org/?probe=b041192310) | Aug 09, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [c4ac4952a4](https://linux-hardware.org/?probe=c4ac4952a4) | Aug 09, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [62a5817462](https://linux-hardware.org/?probe=62a5817462) | Aug 09, 2023 |
| Alienware     | 14                          | Notebook    | [192b13997d](https://linux-hardware.org/?probe=192b13997d) | Aug 09, 2023 |
| HP            | Victus by 15.6 inch Gami... | Notebook    | [67f88ab571](https://linux-hardware.org/?probe=67f88ab571) | Aug 08, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [6abad99081](https://linux-hardware.org/?probe=6abad99081) | Aug 08, 2023 |
| Dell          | Inspiron 5482               | Convertible | [7e2aa092cf](https://linux-hardware.org/?probe=7e2aa092cf) | Aug 08, 2023 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | Notebook    | [afa081b440](https://linux-hardware.org/?probe=afa081b440) | Aug 08, 2023 |
| Acer          | Ferrari One 200             | Notebook    | [be688aa584](https://linux-hardware.org/?probe=be688aa584) | Aug 08, 2023 |
| ASUSTek       | P5Q                         | Desktop     | [f485bf4b6e](https://linux-hardware.org/?probe=f485bf4b6e) | Aug 08, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [00b169d241](https://linux-hardware.org/?probe=00b169d241) | Aug 08, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [c415fd317b](https://linux-hardware.org/?probe=c415fd317b) | Aug 08, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [5e0c7f7bfc](https://linux-hardware.org/?probe=5e0c7f7bfc) | Aug 08, 2023 |
| Acer          | Aspire A715-75G             | Notebook    | [57f1225daf](https://linux-hardware.org/?probe=57f1225daf) | Aug 08, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [58208c1f16](https://linux-hardware.org/?probe=58208c1f16) | Aug 08, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | Notebook    | [088a8fad47](https://linux-hardware.org/?probe=088a8fad47) | Aug 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [45fe14954d](https://linux-hardware.org/?probe=45fe14954d) | Aug 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [d1bca9ae8b](https://linux-hardware.org/?probe=d1bca9ae8b) | Aug 07, 2023 |
| System76      | Oryx Pro                    | Notebook    | [c5b97761d3](https://linux-hardware.org/?probe=c5b97761d3) | Aug 07, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [5fe9a17769](https://linux-hardware.org/?probe=5fe9a17769) | Aug 07, 2023 |
| MSI           | GP72 7RDX                   | Notebook    | [43eb53850c](https://linux-hardware.org/?probe=43eb53850c) | Aug 06, 2023 |
| Clevo         | W150HRM                     | Notebook    | [1ddcfcbecc](https://linux-hardware.org/?probe=1ddcfcbecc) | Aug 06, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [16936ef482](https://linux-hardware.org/?probe=16936ef482) | Aug 06, 2023 |
| Dell          | Inspiron 5482               | Convertible | [9c910c0949](https://linux-hardware.org/?probe=9c910c0949) | Aug 06, 2023 |
| MSI           | GP72 7RDX                   | Notebook    | [6d2bc8aa9e](https://linux-hardware.org/?probe=6d2bc8aa9e) | Aug 06, 2023 |
| Fujitsu       | D3128-A1 S26361-D3128-A1    | Desktop     | [ac2bdfc67b](https://linux-hardware.org/?probe=ac2bdfc67b) | Aug 06, 2023 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [576241bbd4](https://linux-hardware.org/?probe=576241bbd4) | Aug 06, 2023 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [93917e587f](https://linux-hardware.org/?probe=93917e587f) | Aug 06, 2023 |
| Notebook      | 1745                        | Notebook    | [3561a5dbbe](https://linux-hardware.org/?probe=3561a5dbbe) | Aug 06, 2023 |
| HP            | Pavilion dm4                | Notebook    | [521b8518ed](https://linux-hardware.org/?probe=521b8518ed) | Aug 06, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [9a45c9f834](https://linux-hardware.org/?probe=9a45c9f834) | Aug 05, 2023 |
| Dell          | Latitude 5430               | Notebook    | [f63444b0be](https://linux-hardware.org/?probe=f63444b0be) | Aug 05, 2023 |
| Lenovo        | 3178 SDK0J40700 WIN 3258... | Desktop     | [4e0084cd74](https://linux-hardware.org/?probe=4e0084cd74) | Aug 05, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [32f8bbeff7](https://linux-hardware.org/?probe=32f8bbeff7) | Aug 05, 2023 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [3cfd827251](https://linux-hardware.org/?probe=3cfd827251) | Aug 05, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [a4a6f81455](https://linux-hardware.org/?probe=a4a6f81455) | Aug 05, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [ef010c9d51](https://linux-hardware.org/?probe=ef010c9d51) | Aug 05, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | Notebook    | [7d17fc9ff6](https://linux-hardware.org/?probe=7d17fc9ff6) | Aug 05, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [5746742389](https://linux-hardware.org/?probe=5746742389) | Aug 04, 2023 |
| ASRock        | X370 Taichi                 | Desktop     | [af453d6ef1](https://linux-hardware.org/?probe=af453d6ef1) | Aug 04, 2023 |
| Lenovo        | V15 G3 ABA 82TV             | Notebook    | [0147060507](https://linux-hardware.org/?probe=0147060507) | Aug 04, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [92ef92268a](https://linux-hardware.org/?probe=92ef92268a) | Aug 04, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [ca1a97268c](https://linux-hardware.org/?probe=ca1a97268c) | Aug 04, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [286cc8b0dd](https://linux-hardware.org/?probe=286cc8b0dd) | Aug 04, 2023 |
| Dell          | 0KWVT8 A03                  | Desktop     | [6ec952b536](https://linux-hardware.org/?probe=6ec952b536) | Aug 04, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [983329d56b](https://linux-hardware.org/?probe=983329d56b) | Aug 03, 2023 |
| Lenovo        | ThinkPad W541 20EGS0GY0R    | Notebook    | [4d618e08b3](https://linux-hardware.org/?probe=4d618e08b3) | Aug 03, 2023 |
| JHZD          | X830                        | Desktop     | [7de7f6bb75](https://linux-hardware.org/?probe=7de7f6bb75) | Aug 03, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D6C... | Notebook    | [a97312771e](https://linux-hardware.org/?probe=a97312771e) | Aug 03, 2023 |
| JHZD          | X830                        | Desktop     | [4fed3648c0](https://linux-hardware.org/?probe=4fed3648c0) | Aug 03, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [cf49ff3004](https://linux-hardware.org/?probe=cf49ff3004) | Aug 03, 2023 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [2254be2ae2](https://linux-hardware.org/?probe=2254be2ae2) | Aug 03, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [1a9566fa0a](https://linux-hardware.org/?probe=1a9566fa0a) | Aug 03, 2023 |
| Dell          | Latitude E7240              | Notebook    | [ec5ec88e59](https://linux-hardware.org/?probe=ec5ec88e59) | Aug 02, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [99ccd043cb](https://linux-hardware.org/?probe=99ccd043cb) | Aug 02, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [d4e267a214](https://linux-hardware.org/?probe=d4e267a214) | Aug 02, 2023 |
| HP            | ProBook 650 G4              | Notebook    | [d041df173b](https://linux-hardware.org/?probe=d041df173b) | Aug 02, 2023 |
| Dell          | 07PR60 A00                  | Desktop     | [590695e09f](https://linux-hardware.org/?probe=590695e09f) | Aug 02, 2023 |
| HP            | 8054                        | Desktop     | [f53df18325](https://linux-hardware.org/?probe=f53df18325) | Aug 02, 2023 |
| Dell          | Inspiron 7706 2n1           | Convertible | [542578b4cf](https://linux-hardware.org/?probe=542578b4cf) | Aug 02, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [1eb6fd9620](https://linux-hardware.org/?probe=1eb6fd9620) | Aug 02, 2023 |
| HP            | 8309                        | Desktop     | [6cb1cfc925](https://linux-hardware.org/?probe=6cb1cfc925) | Aug 02, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [0a3c5e5c4d](https://linux-hardware.org/?probe=0a3c5e5c4d) | Aug 02, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [9f852ea211](https://linux-hardware.org/?probe=9f852ea211) | Aug 02, 2023 |
| ASUSTek       | GL502VSK                    | Notebook    | [0ed7feaa05](https://linux-hardware.org/?probe=0ed7feaa05) | Aug 01, 2023 |
| Lenovo        | Legion 5 15ARH7 82RE        | Notebook    | [e1a79e094e](https://linux-hardware.org/?probe=e1a79e094e) | Aug 01, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [d252fa93be](https://linux-hardware.org/?probe=d252fa93be) | Aug 01, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [9fbfc590ad](https://linux-hardware.org/?probe=9fbfc590ad) | Aug 01, 2023 |
| Dell          | Latitude 3500               | Notebook    | [df5211a816](https://linux-hardware.org/?probe=df5211a816) | Aug 01, 2023 |
| MSI           | X399 GAMING PRO CARBON A... | Desktop     | [41d4bd6cfe](https://linux-hardware.org/?probe=41d4bd6cfe) | Aug 01, 2023 |
| MSI           | X399 GAMING PRO CARBON A... | Desktop     | [3a655f04e1](https://linux-hardware.org/?probe=3a655f04e1) | Aug 01, 2023 |
| Dell          | Latitude 5490               | Notebook    | [e24a9f877c](https://linux-hardware.org/?probe=e24a9f877c) | Aug 01, 2023 |
| Apple         | Mac-F2218FC8                | All in one  | [1e13eec6e4](https://linux-hardware.org/?probe=1e13eec6e4) | Aug 01, 2023 |
| System76      | Lemur Pro                   | Notebook    | [1ba844bc69](https://linux-hardware.org/?probe=1ba844bc69) | Aug 01, 2023 |
| System76      | Lemur Pro                   | Notebook    | [e019d33faf](https://linux-hardware.org/?probe=e019d33faf) | Aug 01, 2023 |
| ASRock        | B450M/ac                    | Desktop     | [82be4b3dfb](https://linux-hardware.org/?probe=82be4b3dfb) | Aug 01, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [1c44863a1c](https://linux-hardware.org/?probe=1c44863a1c) | Jul 31, 2023 |
| MSI           | Katana GF66 12UC            | Notebook    | [d590bcd619](https://linux-hardware.org/?probe=d590bcd619) | Jul 31, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [030f8afe2d](https://linux-hardware.org/?probe=030f8afe2d) | Jul 31, 2023 |
| ASUSTek       | Z87-K                       | Desktop     | [ed53779d9a](https://linux-hardware.org/?probe=ed53779d9a) | Jul 31, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [d1d59592c3](https://linux-hardware.org/?probe=d1d59592c3) | Jul 30, 2023 |
| ASUSTek       | K95VM                       | Notebook    | [1ec08c4cf9](https://linux-hardware.org/?probe=1ec08c4cf9) | Jul 30, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [60cfcb00e9](https://linux-hardware.org/?probe=60cfcb00e9) | Jul 30, 2023 |
| ASUSTek       | Z170-PRO                    | Desktop     | [ac4682042f](https://linux-hardware.org/?probe=ac4682042f) | Jul 30, 2023 |
| Dell          | Latitude E7440              | Notebook    | [7509a5f756](https://linux-hardware.org/?probe=7509a5f756) | Jul 30, 2023 |
| MSI           | MAG B760M MORTAR WIFI       | Desktop     | [44937ea360](https://linux-hardware.org/?probe=44937ea360) | Jul 30, 2023 |
| System76      | Darter Pro                  | Notebook    | [0220d19f38](https://linux-hardware.org/?probe=0220d19f38) | Jul 30, 2023 |
| Dell          | Latitude E7240              | Notebook    | [b794bcdde6](https://linux-hardware.org/?probe=b794bcdde6) | Jul 29, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [96b197dffc](https://linux-hardware.org/?probe=96b197dffc) | Jul 29, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [d693783e7a](https://linux-hardware.org/?probe=d693783e7a) | Jul 29, 2023 |
| Unknown       | Unknown                     | Notebook    | [73836c0a75](https://linux-hardware.org/?probe=73836c0a75) | Jul 29, 2023 |
| HP            | 3646h                       | Desktop     | [e00952810b](https://linux-hardware.org/?probe=e00952810b) | Jul 29, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [59f0eb6b57](https://linux-hardware.org/?probe=59f0eb6b57) | Jul 28, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [bc88e3dbae](https://linux-hardware.org/?probe=bc88e3dbae) | Jul 28, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [cb2f78abf0](https://linux-hardware.org/?probe=cb2f78abf0) | Jul 28, 2023 |
| ASRock        | X670E PG Lightning          | Desktop     | [b5fec7d5ff](https://linux-hardware.org/?probe=b5fec7d5ff) | Jul 28, 2023 |
| Dell          | Precision 3550              | Notebook    | [0ecac77f90](https://linux-hardware.org/?probe=0ecac77f90) | Jul 28, 2023 |
| Dell          | Precision 3550              | Notebook    | [95ae018833](https://linux-hardware.org/?probe=95ae018833) | Jul 28, 2023 |
| System76      | Oryx Pro                    | Notebook    | [0ad8c1d8a7](https://linux-hardware.org/?probe=0ad8c1d8a7) | Jul 28, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [f4941e530b](https://linux-hardware.org/?probe=f4941e530b) | Jul 28, 2023 |
| Acer          | Aspire A315-42G             | Notebook    | [0e3aa83494](https://linux-hardware.org/?probe=0e3aa83494) | Jul 28, 2023 |
| System76      | Thelio Mira thelio-mira-... | Desktop     | [785fb534be](https://linux-hardware.org/?probe=785fb534be) | Jul 27, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [aac37c9ed6](https://linux-hardware.org/?probe=aac37c9ed6) | Jul 27, 2023 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [fba35d8a25](https://linux-hardware.org/?probe=fba35d8a25) | Jul 27, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [5a1f6f3395](https://linux-hardware.org/?probe=5a1f6f3395) | Jul 27, 2023 |
| Dell          | G15 5520                    | Notebook    | [7a5b503737](https://linux-hardware.org/?probe=7a5b503737) | Jul 27, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [0be5bf84c6](https://linux-hardware.org/?probe=0be5bf84c6) | Jul 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [4152e1f98e](https://linux-hardware.org/?probe=4152e1f98e) | Jul 27, 2023 |
| Dell          | Latitude E7440              | Notebook    | [619c6e4b99](https://linux-hardware.org/?probe=619c6e4b99) | Jul 27, 2023 |
| Gigabyte      | A320M-S2H-CF SE1            | Desktop     | [b9bba11373](https://linux-hardware.org/?probe=b9bba11373) | Jul 27, 2023 |
| Samsung       | 300E5M/300E5L               | Notebook    | [23b23d59aa](https://linux-hardware.org/?probe=23b23d59aa) | Jul 27, 2023 |
| Gigabyte      | B550 VISION D-P             | Desktop     | [2c300ff820](https://linux-hardware.org/?probe=2c300ff820) | Jul 27, 2023 |
| HP            | Dev One Notebook PC         | Notebook    | [b54bb52258](https://linux-hardware.org/?probe=b54bb52258) | Jul 27, 2023 |
| Dell          | 07PR60 A00                  | Desktop     | [67ef05bdd5](https://linux-hardware.org/?probe=67ef05bdd5) | Jul 27, 2023 |
| Intel         | H81                         | Desktop     | [6fa9f0cd2d](https://linux-hardware.org/?probe=6fa9f0cd2d) | Jul 27, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [65b9117b13](https://linux-hardware.org/?probe=65b9117b13) | Jul 27, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | Notebook    | [9920824f1f](https://linux-hardware.org/?probe=9920824f1f) | Jul 27, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [247f6d8816](https://linux-hardware.org/?probe=247f6d8816) | Jul 27, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [00e9bb8973](https://linux-hardware.org/?probe=00e9bb8973) | Jul 26, 2023 |
| Dell          | Inspiron 5548               | Notebook    | [22b2519a90](https://linux-hardware.org/?probe=22b2519a90) | Jul 26, 2023 |
| Dell          | 0YXG0N A00                  | Desktop     | [fb365f50a0](https://linux-hardware.org/?probe=fb365f50a0) | Jul 26, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [7e0e30c1cf](https://linux-hardware.org/?probe=7e0e30c1cf) | Jul 26, 2023 |
| Dell          | Inspiron 5548               | Notebook    | [b583a1fbee](https://linux-hardware.org/?probe=b583a1fbee) | Jul 26, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [c950e4d2f9](https://linux-hardware.org/?probe=c950e4d2f9) | Jul 25, 2023 |
| Dell          | Inspiron 5548               | Notebook    | [3d3696e8fa](https://linux-hardware.org/?probe=3d3696e8fa) | Jul 25, 2023 |
| HP            | Laptop 14-bs0xx             | Notebook    | [e074ee90be](https://linux-hardware.org/?probe=e074ee90be) | Jul 25, 2023 |
| MSI           | GF63 Thin 10SCXR            | Notebook    | [b34b7fa5fb](https://linux-hardware.org/?probe=b34b7fa5fb) | Jul 25, 2023 |
| Dell          | Inspiron 5490               | Notebook    | [25f155c61a](https://linux-hardware.org/?probe=25f155c61a) | Jul 24, 2023 |
| Dell          | Inspiron 5490               | Notebook    | [6b80b41fee](https://linux-hardware.org/?probe=6b80b41fee) | Jul 24, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [fa64a82283](https://linux-hardware.org/?probe=fa64a82283) | Jul 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | Notebook    | [88cfdb061d](https://linux-hardware.org/?probe=88cfdb061d) | Jul 24, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | Notebook    | [61c84247e6](https://linux-hardware.org/?probe=61c84247e6) | Jul 24, 2023 |
| Apple         | MacBookAir4,2               | Notebook    | [e220379405](https://linux-hardware.org/?probe=e220379405) | Jul 24, 2023 |
| ASUSTek       | ROG Strix G533ZW_G533ZW     | Notebook    | [53bab7ac5e](https://linux-hardware.org/?probe=53bab7ac5e) | Jul 24, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [b2b0895194](https://linux-hardware.org/?probe=b2b0895194) | Jul 24, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [3d8ec4447b](https://linux-hardware.org/?probe=3d8ec4447b) | Jul 24, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | Notebook    | [fe2ff0c21f](https://linux-hardware.org/?probe=fe2ff0c21f) | Jul 23, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [2cd0946aba](https://linux-hardware.org/?probe=2cd0946aba) | Jul 23, 2023 |
| Sony          | SVF1521A6EW                 | Notebook    | [3c39100c6f](https://linux-hardware.org/?probe=3c39100c6f) | Jul 23, 2023 |
| PC Special... | Standard                    | Notebook    | [992aec5bb8](https://linux-hardware.org/?probe=992aec5bb8) | Jul 23, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [50cf88ae28](https://linux-hardware.org/?probe=50cf88ae28) | Jul 23, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [bf4dff1328](https://linux-hardware.org/?probe=bf4dff1328) | Jul 23, 2023 |
| HP            | ZBook Studio G3             | Notebook    | [bcfc5b64f4](https://linux-hardware.org/?probe=bcfc5b64f4) | Jul 23, 2023 |
| Google        | Snappy                      | Notebook    | [a3e6774e43](https://linux-hardware.org/?probe=a3e6774e43) | Jul 23, 2023 |
| Lenovo        | IdeaPadFlex 5 14IAU7 82R... | Convertible | [c78a2441ee](https://linux-hardware.org/?probe=c78a2441ee) | Jul 23, 2023 |
| Dell          | Latitude 3500               | Notebook    | [0755576e96](https://linux-hardware.org/?probe=0755576e96) | Jul 22, 2023 |
| Dell          | Latitude E6430s             | Notebook    | [8e74e2a524](https://linux-hardware.org/?probe=8e74e2a524) | Jul 22, 2023 |
| MSI           | Boston                      | Desktop     | [d71010f2a7](https://linux-hardware.org/?probe=d71010f2a7) | Jul 22, 2023 |
| Dell          | Vostro 3560                 | Notebook    | [05acc63d53](https://linux-hardware.org/?probe=05acc63d53) | Jul 22, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [46283ad18b](https://linux-hardware.org/?probe=46283ad18b) | Jul 22, 2023 |
| MSI           | Z97 PC Mate                 | Desktop     | [f4cddb5e86](https://linux-hardware.org/?probe=f4cddb5e86) | Jul 22, 2023 |
| HP            | 829A                        | Mini pc     | [f768f29747](https://linux-hardware.org/?probe=f768f29747) | Jul 22, 2023 |
| Dell          | Latitude 5410               | Notebook    | [82217114b4](https://linux-hardware.org/?probe=82217114b4) | Jul 21, 2023 |
| Intel         | X99H                        | Desktop     | [474e78b162](https://linux-hardware.org/?probe=474e78b162) | Jul 21, 2023 |
| Dell          | Latitude 5520               | Notebook    | [070380568b](https://linux-hardware.org/?probe=070380568b) | Jul 21, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS        | Desktop     | [c3994db136](https://linux-hardware.org/?probe=c3994db136) | Jul 21, 2023 |
| MSI           | Z370-A PRO                  | Desktop     | [9a1d731109](https://linux-hardware.org/?probe=9a1d731109) | Jul 21, 2023 |
| Dell          | Precision 7530              | Notebook    | [0d2e753768](https://linux-hardware.org/?probe=0d2e753768) | Jul 20, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [d23dfad700](https://linux-hardware.org/?probe=d23dfad700) | Jul 20, 2023 |
| Acer          | Aspire A515-52              | Notebook    | [243f0a8cab](https://linux-hardware.org/?probe=243f0a8cab) | Jul 20, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [ebb1eed757](https://linux-hardware.org/?probe=ebb1eed757) | Jul 20, 2023 |
| Acer          | Aspire A515-52              | Notebook    | [f310abe0bb](https://linux-hardware.org/?probe=f310abe0bb) | Jul 20, 2023 |
| HP            | Pavilion Plus Laptop 14-... | Notebook    | [937715a75f](https://linux-hardware.org/?probe=937715a75f) | Jul 20, 2023 |
| Dell          | Latitude E5270              | Notebook    | [9ea13fdc27](https://linux-hardware.org/?probe=9ea13fdc27) | Jul 20, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [6e17b916ee](https://linux-hardware.org/?probe=6e17b916ee) | Jul 20, 2023 |
| Acer          | Extensa 5635ZG              | Notebook    | [337f0cec05](https://linux-hardware.org/?probe=337f0cec05) | Jul 20, 2023 |
| Toshiba       | Satellite L750              | Notebook    | [662f89dcc3](https://linux-hardware.org/?probe=662f89dcc3) | Jul 20, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [ac1a8eea0e](https://linux-hardware.org/?probe=ac1a8eea0e) | Jul 19, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [35944db669](https://linux-hardware.org/?probe=35944db669) | Jul 19, 2023 |
| ASUSTek       | Z97-A                       | Desktop     | [fe36d4fde0](https://linux-hardware.org/?probe=fe36d4fde0) | Jul 19, 2023 |
| Schenker      | XMG NEO (CML/E20)           | Notebook    | [9f99e57705](https://linux-hardware.org/?probe=9f99e57705) | Jul 19, 2023 |
| ASUSTek       | K53E                        | Notebook    | [7fddec038e](https://linux-hardware.org/?probe=7fddec038e) | Jul 19, 2023 |
| Dell          | Latitude 7275               | Tablet      | [fdeba04a06](https://linux-hardware.org/?probe=fdeba04a06) | Jul 19, 2023 |
| ASUSTek       | ROG ZENITH EXTREME ALPHA    | Desktop     | [1dc0977942](https://linux-hardware.org/?probe=1dc0977942) | Jul 19, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [8cb16d19aa](https://linux-hardware.org/?probe=8cb16d19aa) | Jul 19, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [1f57cb78e8](https://linux-hardware.org/?probe=1f57cb78e8) | Jul 18, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d3413475e2](https://linux-hardware.org/?probe=d3413475e2) | Jul 18, 2023 |
| Notebook      | NH5x_7xDPx                  | Notebook    | [098f2f58c7](https://linux-hardware.org/?probe=098f2f58c7) | Jul 18, 2023 |
| Apple         | MacBookPro16,1              | Notebook    | [dd5d384a71](https://linux-hardware.org/?probe=dd5d384a71) | Jul 18, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | Notebook    | [f5dc246f7c](https://linux-hardware.org/?probe=f5dc246f7c) | Jul 18, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | Notebook    | [abec03689c](https://linux-hardware.org/?probe=abec03689c) | Jul 18, 2023 |
| Microsoft     | Surface Pro 6               | Tablet      | [9a9670d446](https://linux-hardware.org/?probe=9a9670d446) | Jul 18, 2023 |
| ASUSTek       | PN51-E1                     | Mini pc     | [37a65534a3](https://linux-hardware.org/?probe=37a65534a3) | Jul 18, 2023 |
| ASRock        | Z77 Performance             | Notebook    | [585aaad9ad](https://linux-hardware.org/?probe=585aaad9ad) | Jul 18, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [1cffa4bad9](https://linux-hardware.org/?probe=1cffa4bad9) | Jul 18, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [cdaad6fa25](https://linux-hardware.org/?probe=cdaad6fa25) | Jul 18, 2023 |
| HP            | 635                         | Notebook    | [500e11147e](https://linux-hardware.org/?probe=500e11147e) | Jul 18, 2023 |
| Gigabyte      | B760M DS3H AX DDR4          | Desktop     | [199e0d2e12](https://linux-hardware.org/?probe=199e0d2e12) | Jul 18, 2023 |
| Gigabyte      | A320M-S2H-CF SE1            | Desktop     | [69f0859638](https://linux-hardware.org/?probe=69f0859638) | Jul 18, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [1426cda0a7](https://linux-hardware.org/?probe=1426cda0a7) | Jul 17, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [c7a062709f](https://linux-hardware.org/?probe=c7a062709f) | Jul 17, 2023 |
| HUAWEI        | KLVC-WXX9                   | Notebook    | [0427f16143](https://linux-hardware.org/?probe=0427f16143) | Jul 17, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | Notebook    | [0bbd5c68bb](https://linux-hardware.org/?probe=0bbd5c68bb) | Jul 17, 2023 |
| Dell          | Precision M6800             | Notebook    | [8ddd80db6c](https://linux-hardware.org/?probe=8ddd80db6c) | Jul 17, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [25737bce66](https://linux-hardware.org/?probe=25737bce66) | Jul 17, 2023 |
| Lenovo        | ThinkPad X390 20Q1S67S00    | Notebook    | [be43004463](https://linux-hardware.org/?probe=be43004463) | Jul 17, 2023 |
| System76      | Serval WS                   | Notebook    | [a916a92726](https://linux-hardware.org/?probe=a916a92726) | Jul 17, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | Notebook    | [55a5100039](https://linux-hardware.org/?probe=55a5100039) | Jul 16, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | Notebook    | [ad8f031cb2](https://linux-hardware.org/?probe=ad8f031cb2) | Jul 16, 2023 |
| MSI           | MAG B550M MORTAR            | Desktop     | [83175318ff](https://linux-hardware.org/?probe=83175318ff) | Jul 16, 2023 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [71e33b92ad](https://linux-hardware.org/?probe=71e33b92ad) | Jul 16, 2023 |
| Alienware     | 0XJKKD A01                  | Desktop     | [b47699e30d](https://linux-hardware.org/?probe=b47699e30d) | Jul 16, 2023 |
| MSI           | B550M-A PRO                 | Desktop     | [0063ae1936](https://linux-hardware.org/?probe=0063ae1936) | Jul 16, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [51128412d5](https://linux-hardware.org/?probe=51128412d5) | Jul 16, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [e984f2562d](https://linux-hardware.org/?probe=e984f2562d) | Jul 16, 2023 |
| Lenovo        | Legion Slim 7 16IRH8 82Y... | Notebook    | [437209972c](https://linux-hardware.org/?probe=437209972c) | Jul 15, 2023 |
| Lenovo        | ThinkPad T480 20L5S1S000    | Notebook    | [91dbb2c969](https://linux-hardware.org/?probe=91dbb2c969) | Jul 15, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [32b56b85c4](https://linux-hardware.org/?probe=32b56b85c4) | Jul 15, 2023 |
| Dell          | G15 5510                    | Notebook    | [28b7a732f2](https://linux-hardware.org/?probe=28b7a732f2) | Jul 15, 2023 |
| System76      | Pangolin                    | Notebook    | [486df7ead2](https://linux-hardware.org/?probe=486df7ead2) | Jul 14, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B3402FEA... | Convertible | [4be00d26b2](https://linux-hardware.org/?probe=4be00d26b2) | Jul 14, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [0498e27f41](https://linux-hardware.org/?probe=0498e27f41) | Jul 14, 2023 |
| HP            | ENVY 15                     | Notebook    | [5cfb9d33bd](https://linux-hardware.org/?probe=5cfb9d33bd) | Jul 14, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [21fc63e4dd](https://linux-hardware.org/?probe=21fc63e4dd) | Jul 14, 2023 |
| MSI           | GF63 Thin 10SC              | Notebook    | [d017610254](https://linux-hardware.org/?probe=d017610254) | Jul 14, 2023 |
| Lenovo        | Legion 7 16ITHg6 82K6       | Notebook    | [e53c63af42](https://linux-hardware.org/?probe=e53c63af42) | Jul 14, 2023 |
| MSI           | PRO Z790-A WIFI             | Desktop     | [c1dba9e7b8](https://linux-hardware.org/?probe=c1dba9e7b8) | Jul 14, 2023 |
| Lenovo        | ThinkPad T530 23943J8       | Notebook    | [fb022ada73](https://linux-hardware.org/?probe=fb022ada73) | Jul 14, 2023 |
| HP            | 0B40h                       | Desktop     | [b452ab2c8d](https://linux-hardware.org/?probe=b452ab2c8d) | Jul 14, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [2afe11b7e4](https://linux-hardware.org/?probe=2afe11b7e4) | Jul 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e84bf83ac1](https://linux-hardware.org/?probe=e84bf83ac1) | Jul 13, 2023 |
| HP            | Compaq CQ58                 | Notebook    | [78977dd4de](https://linux-hardware.org/?probe=78977dd4de) | Jul 13, 2023 |
| Lenovo        | IdeaPadFlex 5 14IAU7 82R... | Convertible | [080a9244cf](https://linux-hardware.org/?probe=080a9244cf) | Jul 13, 2023 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [7ef2028b06](https://linux-hardware.org/?probe=7ef2028b06) | Jul 13, 2023 |
| Acer          | Aspire E5-576G              | Notebook    | [0856b48ae7](https://linux-hardware.org/?probe=0856b48ae7) | Jul 13, 2023 |
| Acer          | Swift SF314-42              | Notebook    | [c82bb58705](https://linux-hardware.org/?probe=c82bb58705) | Jul 13, 2023 |
| Lenovo        | ThinkPad P53s 20N6001UUS    | Notebook    | [5a675551df](https://linux-hardware.org/?probe=5a675551df) | Jul 13, 2023 |
| Dell          | G3 3590                     | Notebook    | [089bfa3da7](https://linux-hardware.org/?probe=089bfa3da7) | Jul 13, 2023 |
| HP            | 0AA8h                       | Desktop     | [297e7364cb](https://linux-hardware.org/?probe=297e7364cb) | Jul 13, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [d4910e3f43](https://linux-hardware.org/?probe=d4910e3f43) | Jul 13, 2023 |
| Acer          | Swift SF314-42              | Notebook    | [7a9624e7cc](https://linux-hardware.org/?probe=7a9624e7cc) | Jul 12, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [2f5bf1f247](https://linux-hardware.org/?probe=2f5bf1f247) | Jul 12, 2023 |
| Acer          | Swift SF314-58G             | Notebook    | [795625662c](https://linux-hardware.org/?probe=795625662c) | Jul 12, 2023 |
| Acer          | Swift SF314-58G             | Notebook    | [c01b74af46](https://linux-hardware.org/?probe=c01b74af46) | Jul 12, 2023 |
| HP            | 0AA8h                       | Desktop     | [db16057ca8](https://linux-hardware.org/?probe=db16057ca8) | Jul 12, 2023 |
| Timi          | Xiaomi NoteBook Pro         | Notebook    | [618c0c975b](https://linux-hardware.org/?probe=618c0c975b) | Jul 12, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [801537f1d4](https://linux-hardware.org/?probe=801537f1d4) | Jul 12, 2023 |
| ASUSTek       | Z87-K                       | Desktop     | [a95cc808e9](https://linux-hardware.org/?probe=a95cc808e9) | Jul 12, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [20e2180dc1](https://linux-hardware.org/?probe=20e2180dc1) | Jul 12, 2023 |
| ASUSTek       | Z87-K                       | Desktop     | [d962460a5e](https://linux-hardware.org/?probe=d962460a5e) | Jul 12, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [2c4a8d9d63](https://linux-hardware.org/?probe=2c4a8d9d63) | Jul 12, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [d08295d5f4](https://linux-hardware.org/?probe=d08295d5f4) | Jul 12, 2023 |
| Lenovo        | ThinkPad T470s 20HGS01A0... | Notebook    | [54e51170a1](https://linux-hardware.org/?probe=54e51170a1) | Jul 11, 2023 |
| Apple         | MacBookAir3,2               | Notebook    | [cbfc272e87](https://linux-hardware.org/?probe=cbfc272e87) | Jul 11, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [2239b2744d](https://linux-hardware.org/?probe=2239b2744d) | Jul 11, 2023 |
| HP            | EliteBook 850 G6            | Notebook    | [556ef4473f](https://linux-hardware.org/?probe=556ef4473f) | Jul 11, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [a61e80c022](https://linux-hardware.org/?probe=a61e80c022) | Jul 11, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [1453f984c9](https://linux-hardware.org/?probe=1453f984c9) | Jul 11, 2023 |
| MSI           | MAG B650M MORTAR WIFI       | Desktop     | [ee2dc6ac7b](https://linux-hardware.org/?probe=ee2dc6ac7b) | Jul 11, 2023 |
| Biostar       | A960D+V2                    | Desktop     | [e6bfab517b](https://linux-hardware.org/?probe=e6bfab517b) | Jul 10, 2023 |
| Positivo      | POS-MIH61CF POSITIVO        | Desktop     | [02113d0b75](https://linux-hardware.org/?probe=02113d0b75) | Jul 10, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [b581326f50](https://linux-hardware.org/?probe=b581326f50) | Jul 10, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [5a7dbc5d7c](https://linux-hardware.org/?probe=5a7dbc5d7c) | Jul 10, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [293ddc3253](https://linux-hardware.org/?probe=293ddc3253) | Jul 10, 2023 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [a4650f89f7](https://linux-hardware.org/?probe=a4650f89f7) | Jul 10, 2023 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [3937b5d17a](https://linux-hardware.org/?probe=3937b5d17a) | Jul 09, 2023 |
| Notebook      | NP5x_NP6x_NP7xRNJ_RNH       | Notebook    | [7663e77bff](https://linux-hardware.org/?probe=7663e77bff) | Jul 09, 2023 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [0aea3d9721](https://linux-hardware.org/?probe=0aea3d9721) | Jul 09, 2023 |
| Notebook      | P7xxTM1                     | Notebook    | [81c163ed4a](https://linux-hardware.org/?probe=81c163ed4a) | Jul 09, 2023 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [92feea0533](https://linux-hardware.org/?probe=92feea0533) | Jul 08, 2023 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [2287c62944](https://linux-hardware.org/?probe=2287c62944) | Jul 08, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [cf96aafbc0](https://linux-hardware.org/?probe=cf96aafbc0) | Jul 08, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [1f88a40c05](https://linux-hardware.org/?probe=1f88a40c05) | Jul 08, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [e1f22afb69](https://linux-hardware.org/?probe=e1f22afb69) | Jul 08, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [a34d0d8290](https://linux-hardware.org/?probe=a34d0d8290) | Jul 08, 2023 |
| Dell          | Inspiron 5565               | Notebook    | [d1df053096](https://linux-hardware.org/?probe=d1df053096) | Jul 08, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [12e3f9ecc7](https://linux-hardware.org/?probe=12e3f9ecc7) | Jul 07, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [4e0acb57f9](https://linux-hardware.org/?probe=4e0acb57f9) | Jul 07, 2023 |
| HP            | 8918                        | Desktop     | [af366ea249](https://linux-hardware.org/?probe=af366ea249) | Jul 07, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [cae21c5121](https://linux-hardware.org/?probe=cae21c5121) | Jul 07, 2023 |
| ASUSTek       | N55SL                       | Notebook    | [1223d8b536](https://linux-hardware.org/?probe=1223d8b536) | Jul 07, 2023 |
| MSI           | GS66 Stealth 10SE           | Notebook    | [e689bf355c](https://linux-hardware.org/?probe=e689bf355c) | Jul 07, 2023 |
| Panasonic     | FZ55-1                      | Notebook    | [4d12f02737](https://linux-hardware.org/?probe=4d12f02737) | Jul 07, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [80164b7a44](https://linux-hardware.org/?probe=80164b7a44) | Jul 07, 2023 |
| ASUSTek       | PRIME X299-DELUXE II        | Desktop     | [d122a1cedc](https://linux-hardware.org/?probe=d122a1cedc) | Jul 07, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [e657049abf](https://linux-hardware.org/?probe=e657049abf) | Jul 06, 2023 |
| ASUSTek       | ROG Flow X16 GV601RM_GV6... | Convertible | [b5157e26b1](https://linux-hardware.org/?probe=b5157e26b1) | Jul 06, 2023 |
| MACHINIST     | E5 MR9A PRO MAX V1.1        | Desktop     | [88649252eb](https://linux-hardware.org/?probe=88649252eb) | Jul 06, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [f2a99b72dc](https://linux-hardware.org/?probe=f2a99b72dc) | Jul 06, 2023 |
| MSI           | Z97 PC Mate                 | Desktop     | [495b6e6e4a](https://linux-hardware.org/?probe=495b6e6e4a) | Jul 06, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [5ddd2d6cf0](https://linux-hardware.org/?probe=5ddd2d6cf0) | Jul 05, 2023 |
| Acer          | Predator PT515-51           | Notebook    | [9971e8a3da](https://linux-hardware.org/?probe=9971e8a3da) | Jul 05, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [f634e3942a](https://linux-hardware.org/?probe=f634e3942a) | Jul 05, 2023 |
| MSI           | B350 GAMING PLUS            | Desktop     | [8115e08748](https://linux-hardware.org/?probe=8115e08748) | Jul 05, 2023 |
| MSI           | Z97 PC Mate                 | Desktop     | [0d9ce2b3d2](https://linux-hardware.org/?probe=0d9ce2b3d2) | Jul 05, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | Notebook    | [46e6f4b081](https://linux-hardware.org/?probe=46e6f4b081) | Jul 05, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | Notebook    | [6bf093ef61](https://linux-hardware.org/?probe=6bf093ef61) | Jul 05, 2023 |
| Unknown       | 1.31                        | Desktop     | [d34eb9e5d4](https://linux-hardware.org/?probe=d34eb9e5d4) | Jul 05, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [e2706e4472](https://linux-hardware.org/?probe=e2706e4472) | Jul 05, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [6013dcdf1e](https://linux-hardware.org/?probe=6013dcdf1e) | Jul 04, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [bc423a1cb9](https://linux-hardware.org/?probe=bc423a1cb9) | Jul 04, 2023 |
| Dell          | XPS 17 9720                 | Notebook    | [a99946b8f0](https://linux-hardware.org/?probe=a99946b8f0) | Jul 04, 2023 |
| HP            | OMEN by Laptop 17-cb1xxx    | Notebook    | [dbf87e0eec](https://linux-hardware.org/?probe=dbf87e0eec) | Jul 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [09dffdde54](https://linux-hardware.org/?probe=09dffdde54) | Jul 04, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [156f923a72](https://linux-hardware.org/?probe=156f923a72) | Jul 04, 2023 |
| Acer          | Aspire E1-470G              | Notebook    | [db4125a1c5](https://linux-hardware.org/?probe=db4125a1c5) | Jul 04, 2023 |
| Intel         | NUC10i5FNB K61361-303       | Mini pc     | [1c527ab64f](https://linux-hardware.org/?probe=1c527ab64f) | Jul 04, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [dda9b242fd](https://linux-hardware.org/?probe=dda9b242fd) | Jul 03, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [baec2d3618](https://linux-hardware.org/?probe=baec2d3618) | Jul 03, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [a44e9e946f](https://linux-hardware.org/?probe=a44e9e946f) | Jul 03, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [cc5348e995](https://linux-hardware.org/?probe=cc5348e995) | Jul 03, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [b8ff99b486](https://linux-hardware.org/?probe=b8ff99b486) | Jul 03, 2023 |
| ASRock        | B450M/ac                    | Desktop     | [1f5703db9b](https://linux-hardware.org/?probe=1f5703db9b) | Jul 03, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | Notebook    | [e8ff92b585](https://linux-hardware.org/?probe=e8ff92b585) | Jul 03, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [73015ee7be](https://linux-hardware.org/?probe=73015ee7be) | Jul 02, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [6db9b5e42a](https://linux-hardware.org/?probe=6db9b5e42a) | Jul 02, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [73d4fb6c33](https://linux-hardware.org/?probe=73d4fb6c33) | Jul 02, 2023 |
| Dell          | 02GDWG A00                  | Desktop     | [228db73d17](https://linux-hardware.org/?probe=228db73d17) | Jul 02, 2023 |
| Acer          | Aspire A515-52              | Notebook    | [3861c91dd4](https://linux-hardware.org/?probe=3861c91dd4) | Jul 02, 2023 |
| Acer          | Aspire A515-52              | Notebook    | [ab8898b9f3](https://linux-hardware.org/?probe=ab8898b9f3) | Jul 02, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [f89bdd4374](https://linux-hardware.org/?probe=f89bdd4374) | Jul 02, 2023 |
| Dell          | Precision 7510              | Notebook    | [46b90e25b0](https://linux-hardware.org/?probe=46b90e25b0) | Jul 02, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [38e6f08816](https://linux-hardware.org/?probe=38e6f08816) | Jul 02, 2023 |
| MSI           | GT72VR 6RD                  | Notebook    | [ea6887d031](https://linux-hardware.org/?probe=ea6887d031) | Jul 01, 2023 |
| Dell          | 05XGC8 A00                  | Desktop     | [7797ece08f](https://linux-hardware.org/?probe=7797ece08f) | Jul 01, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [6ee8b4e949](https://linux-hardware.org/?probe=6ee8b4e949) | Jul 01, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [18b6484d81](https://linux-hardware.org/?probe=18b6484d81) | Jul 01, 2023 |
| Dell          | Latitude 3500               | Notebook    | [8293ebc591](https://linux-hardware.org/?probe=8293ebc591) | Jul 01, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [a70ec8bdf1](https://linux-hardware.org/?probe=a70ec8bdf1) | Jul 01, 2023 |
| Acer          | Spin SP314-54N              | Convertible | [446ce08df0](https://linux-hardware.org/?probe=446ce08df0) | Jun 30, 2023 |
| Gigabyte      | B550 UD AC                  | Desktop     | [7d7d37522c](https://linux-hardware.org/?probe=7d7d37522c) | Jun 30, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [b95a7c049a](https://linux-hardware.org/?probe=b95a7c049a) | Jun 30, 2023 |
| Teclast       | F7 Plus                     | Notebook    | [cebd3b027c](https://linux-hardware.org/?probe=cebd3b027c) | Jun 30, 2023 |
| Gigabyte      | H170-HD3-CF                 | Desktop     | [59d1be1c5d](https://linux-hardware.org/?probe=59d1be1c5d) | Jun 30, 2023 |
| Samsung       | DT1234567890 SAMSUNG_SW_... | Desktop     | [878e617ba4](https://linux-hardware.org/?probe=878e617ba4) | Jun 30, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [ec4bf131f5](https://linux-hardware.org/?probe=ec4bf131f5) | Jun 30, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [cdb77bf9b6](https://linux-hardware.org/?probe=cdb77bf9b6) | Jun 30, 2023 |
| Dell          | 0M6C7G A00                  | Desktop     | [d7dfcc4a38](https://linux-hardware.org/?probe=d7dfcc4a38) | Jun 30, 2023 |
| Positivo      | Mobile                      | Notebook    | [fdaaf6915b](https://linux-hardware.org/?probe=fdaaf6915b) | Jun 30, 2023 |
| MSI           | GS65 Stealth 9SD            | Notebook    | [568380fd59](https://linux-hardware.org/?probe=568380fd59) | Jun 30, 2023 |
| MSI           | GS65 Stealth 9SD            | Notebook    | [54013b2dfd](https://linux-hardware.org/?probe=54013b2dfd) | Jun 30, 2023 |
| Positivo      | H14CU02                     | Notebook    | [d50e6fbbdc](https://linux-hardware.org/?probe=d50e6fbbdc) | Jun 29, 2023 |
| ASRock        | Z77 Performance             | Notebook    | [a678dc9605](https://linux-hardware.org/?probe=a678dc9605) | Jun 29, 2023 |
| MSI           | Vector GP76 12UH            | Notebook    | [b7035d78a6](https://linux-hardware.org/?probe=b7035d78a6) | Jun 29, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [323464eebb](https://linux-hardware.org/?probe=323464eebb) | Jun 28, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [b1b4052442](https://linux-hardware.org/?probe=b1b4052442) | Jun 28, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [4054ebeac8](https://linux-hardware.org/?probe=4054ebeac8) | Jun 28, 2023 |
| MSI           | GE70 2PL                    | Notebook    | [e5354b6cb4](https://linux-hardware.org/?probe=e5354b6cb4) | Jun 28, 2023 |
| Dell          | 0F6X5P A00                  | Desktop     | [cad43414b4](https://linux-hardware.org/?probe=cad43414b4) | Jun 27, 2023 |
| Acer          | Aspire A315-21              | Notebook    | [4bf524cd80](https://linux-hardware.org/?probe=4bf524cd80) | Jun 27, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [894f8583ea](https://linux-hardware.org/?probe=894f8583ea) | Jun 27, 2023 |
| Dell          | Vostro 15 3510              | Notebook    | [adb3a3de68](https://linux-hardware.org/?probe=adb3a3de68) | Jun 27, 2023 |
| Dell          | 0427JK A00                  | Desktop     | [0dda4e26da](https://linux-hardware.org/?probe=0dda4e26da) | Jun 27, 2023 |
| Dell          | Precision M6800             | Notebook    | [b0fe737883](https://linux-hardware.org/?probe=b0fe737883) | Jun 27, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [882bd512a2](https://linux-hardware.org/?probe=882bd512a2) | Jun 27, 2023 |
| ASRock        | X370 Gaming-ITX/ac          | Desktop     | [975e5164c6](https://linux-hardware.org/?probe=975e5164c6) | Jun 27, 2023 |
| ASUSTek       | X550JX                      | Notebook    | [80770014b8](https://linux-hardware.org/?probe=80770014b8) | Jun 27, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [e1e76b3d77](https://linux-hardware.org/?probe=e1e76b3d77) | Jun 27, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [5454a08ba6](https://linux-hardware.org/?probe=5454a08ba6) | Jun 26, 2023 |
| Lenovo        | ThinkPad P53 20QQS34C04     | Notebook    | [3019d7a733](https://linux-hardware.org/?probe=3019d7a733) | Jun 26, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [6b44c8513d](https://linux-hardware.org/?probe=6b44c8513d) | Jun 26, 2023 |
| Dell          | Precision M6800             | Notebook    | [4e6c5423b1](https://linux-hardware.org/?probe=4e6c5423b1) | Jun 25, 2023 |
| Dell          | Precision M6800             | Notebook    | [feb0adfd99](https://linux-hardware.org/?probe=feb0adfd99) | Jun 25, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [1bd3b2b912](https://linux-hardware.org/?probe=1bd3b2b912) | Jun 25, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [d436c6bcdf](https://linux-hardware.org/?probe=d436c6bcdf) | Jun 25, 2023 |
| HP            | Notebook                    | Notebook    | [ea00ce6c5b](https://linux-hardware.org/?probe=ea00ce6c5b) | Jun 25, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | Desktop     | [3907252056](https://linux-hardware.org/?probe=3907252056) | Jun 25, 2023 |
| MSI           | B450M MORTAR                | Desktop     | [9888e54285](https://linux-hardware.org/?probe=9888e54285) | Jun 25, 2023 |
| Biostar       | H81MHV3 5.0                 | Desktop     | [0f95f72b43](https://linux-hardware.org/?probe=0f95f72b43) | Jun 25, 2023 |
| Sony          | VPCEA23FB                   | Notebook    | [b9a835920f](https://linux-hardware.org/?probe=b9a835920f) | Jun 25, 2023 |
| Sony          | VPCEA23FB                   | Notebook    | [c462c4c75e](https://linux-hardware.org/?probe=c462c4c75e) | Jun 25, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [b4ab698b09](https://linux-hardware.org/?probe=b4ab698b09) | Jun 25, 2023 |
| HP            | ENVY NOTEBOOK PC            | Notebook    | [8bd62ffdf1](https://linux-hardware.org/?probe=8bd62ffdf1) | Jun 25, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [210d09c5dd](https://linux-hardware.org/?probe=210d09c5dd) | Jun 24, 2023 |
| Acer          | Swift SF314-512             | Notebook    | [12f361cd8c](https://linux-hardware.org/?probe=12f361cd8c) | Jun 24, 2023 |
| System76      | Oryx Pro                    | Notebook    | [eaa4d8e105](https://linux-hardware.org/?probe=eaa4d8e105) | Jun 24, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [737204f453](https://linux-hardware.org/?probe=737204f453) | Jun 24, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [7f13c620bf](https://linux-hardware.org/?probe=7f13c620bf) | Jun 23, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [703e12843e](https://linux-hardware.org/?probe=703e12843e) | Jun 23, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [700914c136](https://linux-hardware.org/?probe=700914c136) | Jun 23, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [70954bb61e](https://linux-hardware.org/?probe=70954bb61e) | Jun 23, 2023 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [7f41e23d3a](https://linux-hardware.org/?probe=7f41e23d3a) | Jun 23, 2023 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [79ec1a7b3f](https://linux-hardware.org/?probe=79ec1a7b3f) | Jun 23, 2023 |
| MSI           | H77MA-G43                   | Desktop     | [510d2844bd](https://linux-hardware.org/?probe=510d2844bd) | Jun 23, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [36dc72c683](https://linux-hardware.org/?probe=36dc72c683) | Jun 23, 2023 |
| ASUSTek       | X751LD                      | Notebook    | [c7be73b6ca](https://linux-hardware.org/?probe=c7be73b6ca) | Jun 23, 2023 |
| ASUSTek       | X751LD                      | Notebook    | [346bbb0b47](https://linux-hardware.org/?probe=346bbb0b47) | Jun 23, 2023 |
| MSI           | Alpha 15 A3DDK              | Notebook    | [410b20161b](https://linux-hardware.org/?probe=410b20161b) | Jun 23, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [e8db86e014](https://linux-hardware.org/?probe=e8db86e014) | Jun 22, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [6e68a59ffb](https://linux-hardware.org/?probe=6e68a59ffb) | Jun 22, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [41a5a93ebb](https://linux-hardware.org/?probe=41a5a93ebb) | Jun 22, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [082d9a4988](https://linux-hardware.org/?probe=082d9a4988) | Jun 22, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [5b2b7d4a7f](https://linux-hardware.org/?probe=5b2b7d4a7f) | Jun 22, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [170d1f4f0b](https://linux-hardware.org/?probe=170d1f4f0b) | Jun 22, 2023 |
| HP            | Notebook                    | Notebook    | [35b8a2a187](https://linux-hardware.org/?probe=35b8a2a187) | Jun 22, 2023 |
| ASUSTek       | P8H61-M LE R2.0             | Desktop     | [3c27e4a91d](https://linux-hardware.org/?probe=3c27e4a91d) | Jun 22, 2023 |
| Acidanther... | Mac-77EB7D7DAF985301 iMa... | All in one  | [1b2f8eb529](https://linux-hardware.org/?probe=1b2f8eb529) | Jun 22, 2023 |
| Lenovo        | B5400 80B6QB0               | Notebook    | [6885fc56aa](https://linux-hardware.org/?probe=6885fc56aa) | Jun 22, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [f7c2ec659b](https://linux-hardware.org/?probe=f7c2ec659b) | Jun 22, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [8634954b1c](https://linux-hardware.org/?probe=8634954b1c) | Jun 22, 2023 |
| Acer          | Aspire A515-52              | Notebook    | [43ee82258d](https://linux-hardware.org/?probe=43ee82258d) | Jun 21, 2023 |
| Intel         | H55                         | Desktop     | [545c7e42b3](https://linux-hardware.org/?probe=545c7e42b3) | Jun 21, 2023 |
| HP            | 89B5 A                      | Desktop     | [01e8a85a35](https://linux-hardware.org/?probe=01e8a85a35) | Jun 21, 2023 |
| Dell          | System Inspiron N4110       | Notebook    | [ebaceedccf](https://linux-hardware.org/?probe=ebaceedccf) | Jun 21, 2023 |
| Lenovo        | ThinkPad T480 20L6S3H102    | Notebook    | [4a8bd602ff](https://linux-hardware.org/?probe=4a8bd602ff) | Jun 21, 2023 |
| Dell          | System Inspiron N4110       | Notebook    | [a168f45822](https://linux-hardware.org/?probe=a168f45822) | Jun 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [b255195205](https://linux-hardware.org/?probe=b255195205) | Jun 21, 2023 |
| Acer          | Aspire A515-52              | Notebook    | [b2d464d2bc](https://linux-hardware.org/?probe=b2d464d2bc) | Jun 21, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [14296e98e7](https://linux-hardware.org/?probe=14296e98e7) | Jun 21, 2023 |
| Dell          | Latitude E7240              | Notebook    | [f8b3fce80b](https://linux-hardware.org/?probe=f8b3fce80b) | Jun 21, 2023 |
| HP            | Pavilion Laptop 15t-eg00... | Notebook    | [383aed9129](https://linux-hardware.org/?probe=383aed9129) | Jun 20, 2023 |
| HP            | Pavilion Laptop 15t-eg00... | Notebook    | [3996492e80](https://linux-hardware.org/?probe=3996492e80) | Jun 20, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | Notebook    | [1c9456fd1d](https://linux-hardware.org/?probe=1c9456fd1d) | Jun 20, 2023 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [ec5318fcd1](https://linux-hardware.org/?probe=ec5318fcd1) | Jun 20, 2023 |
| Lenovo        | ThinkCentre M90p 5498R97    | Desktop     | [4a18635ad7](https://linux-hardware.org/?probe=4a18635ad7) | Jun 20, 2023 |
| Dell          | 0X9M3X A01                  | Desktop     | [1d14950f1e](https://linux-hardware.org/?probe=1d14950f1e) | Jun 20, 2023 |
| Dell          | 0X9M3X A01                  | Desktop     | [46baecef13](https://linux-hardware.org/?probe=46baecef13) | Jun 20, 2023 |
| BESSTAR Te... | HM90                        | Desktop     | [796769b68a](https://linux-hardware.org/?probe=796769b68a) | Jun 20, 2023 |
| Lenovo        | ThinkCentre M90p 5498R97    | Desktop     | [d2550efee5](https://linux-hardware.org/?probe=d2550efee5) | Jun 19, 2023 |
| System76      | Lemur Pro                   | Notebook    | [5074769fee](https://linux-hardware.org/?probe=5074769fee) | Jun 19, 2023 |
| Dell          | Latitude 7430               | Notebook    | [84f66041f9](https://linux-hardware.org/?probe=84f66041f9) | Jun 19, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [5a89024be5](https://linux-hardware.org/?probe=5a89024be5) | Jun 19, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [347c5ce944](https://linux-hardware.org/?probe=347c5ce944) | Jun 19, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [0699537327](https://linux-hardware.org/?probe=0699537327) | Jun 19, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [26d77cd5be](https://linux-hardware.org/?probe=26d77cd5be) | Jun 19, 2023 |
| HP            | 829A                        | Mini pc     | [0ca8c646bb](https://linux-hardware.org/?probe=0ca8c646bb) | Jun 19, 2023 |
| MSI           | Raider GE66 12UGS           | Notebook    | [73b20b76a3](https://linux-hardware.org/?probe=73b20b76a3) | Jun 19, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [f93c91b6d9](https://linux-hardware.org/?probe=f93c91b6d9) | Jun 18, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [4f35e25c20](https://linux-hardware.org/?probe=4f35e25c20) | Jun 18, 2023 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [fcbe9b509b](https://linux-hardware.org/?probe=fcbe9b509b) | Jun 18, 2023 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [ae0a1a134a](https://linux-hardware.org/?probe=ae0a1a134a) | Jun 18, 2023 |
| HP            | 8949 11                     | Desktop     | [bd6b95fc23](https://linux-hardware.org/?probe=bd6b95fc23) | Jun 18, 2023 |
| Biostar       | A320MH                      | Desktop     | [0c38427f58](https://linux-hardware.org/?probe=0c38427f58) | Jun 18, 2023 |
| Gigabyte      | Z170-Gaming K3-CF           | Desktop     | [6e40a39112](https://linux-hardware.org/?probe=6e40a39112) | Jun 18, 2023 |
| Gigabyte      | Z690 AORUS PRO              | Desktop     | [e9dd574827](https://linux-hardware.org/?probe=e9dd574827) | Jun 18, 2023 |
| ASRock        | Z77 Extreme4                | Desktop     | [c45aea7474](https://linux-hardware.org/?probe=c45aea7474) | Jun 18, 2023 |
| BESSTAR Te... | B550                        | Desktop     | [6c2811bbf5](https://linux-hardware.org/?probe=6c2811bbf5) | Jun 18, 2023 |
| HONOR         | BRN-FXX                     | Notebook    | [d3671dca6a](https://linux-hardware.org/?probe=d3671dca6a) | Jun 18, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [c2f10ad55c](https://linux-hardware.org/?probe=c2f10ad55c) | Jun 17, 2023 |
| Avell High... | A70 HYB                     | Notebook    | [10eb079da8](https://linux-hardware.org/?probe=10eb079da8) | Jun 17, 2023 |
| ASUSTek       | ASUSPRO P5440UF             | Notebook    | [cf08c655b9](https://linux-hardware.org/?probe=cf08c655b9) | Jun 17, 2023 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [2b3a058830](https://linux-hardware.org/?probe=2b3a058830) | Jun 17, 2023 |
| Acer          | Aspire 4752                 | Notebook    | [441eb3fe51](https://linux-hardware.org/?probe=441eb3fe51) | Jun 17, 2023 |
| MSI           | H67MA-E35                   | Desktop     | [8b37f91738](https://linux-hardware.org/?probe=8b37f91738) | Jun 16, 2023 |
| ASUSTek       | ASUSPRO P5440UF             | Notebook    | [272d8de237](https://linux-hardware.org/?probe=272d8de237) | Jun 16, 2023 |
| Dell          | Inspiron 5481               | Convertible | [4e24ca3b12](https://linux-hardware.org/?probe=4e24ca3b12) | Jun 16, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [da12f0d8e3](https://linux-hardware.org/?probe=da12f0d8e3) | Jun 16, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [989287c8b1](https://linux-hardware.org/?probe=989287c8b1) | Jun 16, 2023 |
| HP            | Laptop 14-bp0xx             | Notebook    | [fd6b492010](https://linux-hardware.org/?probe=fd6b492010) | Jun 16, 2023 |
| HP            | Pavilion dv6                | Notebook    | [55c83ec890](https://linux-hardware.org/?probe=55c83ec890) | Jun 15, 2023 |
| Dell          | Vostro 3420                 | Notebook    | [c1b8b07db0](https://linux-hardware.org/?probe=c1b8b07db0) | Jun 15, 2023 |
| System76      | Gazelle                     | Notebook    | [79c4236cdd](https://linux-hardware.org/?probe=79c4236cdd) | Jun 15, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [1bcfd50d08](https://linux-hardware.org/?probe=1bcfd50d08) | Jun 15, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [04b5148080](https://linux-hardware.org/?probe=04b5148080) | Jun 15, 2023 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [1e6fdd560b](https://linux-hardware.org/?probe=1e6fdd560b) | Jun 14, 2023 |
| ZOTAC         | ZBOX-AD04                   | Mini pc     | [c7c537bd79](https://linux-hardware.org/?probe=c7c537bd79) | Jun 14, 2023 |
| ZOTAC         | ZBOX-AD04                   | Mini pc     | [42e6a44062](https://linux-hardware.org/?probe=42e6a44062) | Jun 14, 2023 |
| Lenovo        | ThinkPad P53s 20N6001UUS    | Notebook    | [667f0a20c1](https://linux-hardware.org/?probe=667f0a20c1) | Jun 14, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [17c4d68066](https://linux-hardware.org/?probe=17c4d68066) | Jun 14, 2023 |
| System76      | Gazelle                     | Notebook    | [117f199b15](https://linux-hardware.org/?probe=117f199b15) | Jun 14, 2023 |
| ATOPNUC       | MA90                        | Mini pc     | [384ee8b42e](https://linux-hardware.org/?probe=384ee8b42e) | Jun 13, 2023 |
| ASUSTek       | Zenbook UN5401RA UN5401R... | Convertible | [ad75eab286](https://linux-hardware.org/?probe=ad75eab286) | Jun 13, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [d7c90a9c25](https://linux-hardware.org/?probe=d7c90a9c25) | Jun 13, 2023 |
| Acer          | Swift SFX14-51G             | Notebook    | [c17f7d87b3](https://linux-hardware.org/?probe=c17f7d87b3) | Jun 13, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [b3303b8ed6](https://linux-hardware.org/?probe=b3303b8ed6) | Jun 13, 2023 |
| Dell          | Vostro 5470                 | Notebook    | [b5294ee338](https://linux-hardware.org/?probe=b5294ee338) | Jun 13, 2023 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [5281ad2271](https://linux-hardware.org/?probe=5281ad2271) | Jun 13, 2023 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | Notebook    | [fff5e11f1c](https://linux-hardware.org/?probe=fff5e11f1c) | Jun 13, 2023 |
| TUXEDO        | Unknown                     | Notebook    | [d730799661](https://linux-hardware.org/?probe=d730799661) | Jun 12, 2023 |
| ASRock        | Z690 Steel Legend WiFi 6... | Desktop     | [0190531869](https://linux-hardware.org/?probe=0190531869) | Jun 12, 2023 |
| ASRock        | Z690 Steel Legend WiFi 6... | Desktop     | [648161a6ff](https://linux-hardware.org/?probe=648161a6ff) | Jun 12, 2023 |
| ASUSTek       | Zenbook UP6502ZD_Q539ZD     | Convertible | [e2cd0602f8](https://linux-hardware.org/?probe=e2cd0602f8) | Jun 12, 2023 |
| Pegatron      | NARRA5                      | Desktop     | [3e7cbbb991](https://linux-hardware.org/?probe=3e7cbbb991) | Jun 12, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [fd51db661f](https://linux-hardware.org/?probe=fd51db661f) | Jun 12, 2023 |
| Dell          | Latitude E7470              | Notebook    | [1253de4554](https://linux-hardware.org/?probe=1253de4554) | Jun 12, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [1f4d0ebdc1](https://linux-hardware.org/?probe=1f4d0ebdc1) | Jun 12, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81G3      | Notebook    | [c09c4a0f69](https://linux-hardware.org/?probe=c09c4a0f69) | Jun 12, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [a9bb4cfb62](https://linux-hardware.org/?probe=a9bb4cfb62) | Jun 12, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [9c0f9bf219](https://linux-hardware.org/?probe=9c0f9bf219) | Jun 12, 2023 |
| Toshiba       | Satellite P55t-B            | Notebook    | [efc0f87778](https://linux-hardware.org/?probe=efc0f87778) | Jun 11, 2023 |
| BESSTAR Te... | B550                        | Desktop     | [b74cc9dfff](https://linux-hardware.org/?probe=b74cc9dfff) | Jun 11, 2023 |
| Pegatron      | NARRA5                      | Desktop     | [609c2921d3](https://linux-hardware.org/?probe=609c2921d3) | Jun 11, 2023 |
| HP            | Stream Laptop 11-ah0XX      | Notebook    | [a3e566ad38](https://linux-hardware.org/?probe=a3e566ad38) | Jun 11, 2023 |
| BESSTAR Te... | HM90                        | Desktop     | [86c52dcc7a](https://linux-hardware.org/?probe=86c52dcc7a) | Jun 11, 2023 |
| HP            | 89B5 A                      | Desktop     | [7bf638dc35](https://linux-hardware.org/?probe=7bf638dc35) | Jun 10, 2023 |
| MSI           | X99A GODLIKE GAMING         | Desktop     | [19511501c7](https://linux-hardware.org/?probe=19511501c7) | Jun 10, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | Notebook    | [fd388e00c3](https://linux-hardware.org/?probe=fd388e00c3) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [6c8e1de1cf](https://linux-hardware.org/?probe=6c8e1de1cf) | Jun 10, 2023 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [d8dac01c79](https://linux-hardware.org/?probe=d8dac01c79) | Jun 10, 2023 |
| HP            | 8949 11                     | Desktop     | [f5e1f4b6c9](https://linux-hardware.org/?probe=f5e1f4b6c9) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [cac24c37e5](https://linux-hardware.org/?probe=cac24c37e5) | Jun 10, 2023 |
| Lenovo        | ThinkPad T540p 20BFS4P80... | Notebook    | [4160d59c4f](https://linux-hardware.org/?probe=4160d59c4f) | Jun 10, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [280baa2765](https://linux-hardware.org/?probe=280baa2765) | Jun 09, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [0f42ca8c95](https://linux-hardware.org/?probe=0f42ca8c95) | Jun 09, 2023 |
| ASUSTek       | PRIME A520M-A II            | Desktop     | [176b4ca0bb](https://linux-hardware.org/?probe=176b4ca0bb) | Jun 09, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [50b022f065](https://linux-hardware.org/?probe=50b022f065) | Jun 09, 2023 |
| Acer          | Aspire 7750                 | Notebook    | [b0daafa057](https://linux-hardware.org/?probe=b0daafa057) | Jun 09, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [1189f6696f](https://linux-hardware.org/?probe=1189f6696f) | Jun 09, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [1256480fca](https://linux-hardware.org/?probe=1256480fca) | Jun 09, 2023 |
| ASUSTek       | M4A785G-HTPC                | Desktop     | [76304dfb4a](https://linux-hardware.org/?probe=76304dfb4a) | Jun 09, 2023 |
| AZW           | SEi                         | Desktop     | [2b085e7ed2](https://linux-hardware.org/?probe=2b085e7ed2) | Jun 09, 2023 |
| Dell          | Latitude E7240              | Notebook    | [e21cc2151b](https://linux-hardware.org/?probe=e21cc2151b) | Jun 08, 2023 |
| Dell          | Latitude E6420              | Notebook    | [d408418ddd](https://linux-hardware.org/?probe=d408418ddd) | Jun 08, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [975246674d](https://linux-hardware.org/?probe=975246674d) | Jun 08, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [348173e172](https://linux-hardware.org/?probe=348173e172) | Jun 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [e355aa21b5](https://linux-hardware.org/?probe=e355aa21b5) | Jun 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [c5a1a47343](https://linux-hardware.org/?probe=c5a1a47343) | Jun 08, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [35c7fcb130](https://linux-hardware.org/?probe=35c7fcb130) | Jun 08, 2023 |
| HP            | Pavilion dv7                | Notebook    | [896e71aaaf](https://linux-hardware.org/?probe=896e71aaaf) | Jun 08, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [e127b4c2f4](https://linux-hardware.org/?probe=e127b4c2f4) | Jun 08, 2023 |
| Gigabyte      | M68M-S2P                    | Desktop     | [ee2b6b0279](https://linux-hardware.org/?probe=ee2b6b0279) | Jun 08, 2023 |
| MSI           | PRO B550M-VC WIFI           | Desktop     | [70c409a2b8](https://linux-hardware.org/?probe=70c409a2b8) | Jun 08, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [540fc1c58d](https://linux-hardware.org/?probe=540fc1c58d) | Jun 07, 2023 |
| Machcreato... | 14                          | Notebook    | [d889b02b13](https://linux-hardware.org/?probe=d889b02b13) | Jun 07, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [276844abe2](https://linux-hardware.org/?probe=276844abe2) | Jun 07, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [cc023db7a9](https://linux-hardware.org/?probe=cc023db7a9) | Jun 07, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | Notebook    | [ee9c6252ae](https://linux-hardware.org/?probe=ee9c6252ae) | Jun 07, 2023 |
| Fujitsu       | LIFEBOOK E5512A             | Notebook    | [7381bd00f3](https://linux-hardware.org/?probe=7381bd00f3) | Jun 07, 2023 |
| System76      | Thelio Mira thelio-mira-... | Desktop     | [d7d155d89d](https://linux-hardware.org/?probe=d7d155d89d) | Jun 07, 2023 |
| Dell          | Latitude E6420              | Notebook    | [620ca905d2](https://linux-hardware.org/?probe=620ca905d2) | Jun 07, 2023 |
| Dell          | Latitude 7200 2-in-1        | Tablet      | [4d60f57084](https://linux-hardware.org/?probe=4d60f57084) | Jun 07, 2023 |
| Machcreato... | 14                          | Notebook    | [f0a27a9f97](https://linux-hardware.org/?probe=f0a27a9f97) | Jun 06, 2023 |
| Lenovo        | ThinkPad T480s 20L8S3JE0... | Notebook    | [2834fee64f](https://linux-hardware.org/?probe=2834fee64f) | Jun 06, 2023 |
| HP            | Laptop 14-cf2xxx            | Notebook    | [e6bf4ead0a](https://linux-hardware.org/?probe=e6bf4ead0a) | Jun 06, 2023 |
| Lenovo        | ThinkPad W520 427637U       | Notebook    | [1bec07891b](https://linux-hardware.org/?probe=1bec07891b) | Jun 05, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [841eeea3f9](https://linux-hardware.org/?probe=841eeea3f9) | Jun 05, 2023 |
| Apple         | MacBookAir4,2               | Notebook    | [afc9f50009](https://linux-hardware.org/?probe=afc9f50009) | Jun 05, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [804abce033](https://linux-hardware.org/?probe=804abce033) | Jun 05, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [f53388e7df](https://linux-hardware.org/?probe=f53388e7df) | Jun 05, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [6c151a9750](https://linux-hardware.org/?probe=6c151a9750) | Jun 05, 2023 |
| HP            | 15 Notebook PC              | Notebook    | [7c76016c9d](https://linux-hardware.org/?probe=7c76016c9d) | Jun 05, 2023 |
| Lenovo        | ThinkPad T540p 20BFS4P80... | Notebook    | [5dd18339de](https://linux-hardware.org/?probe=5dd18339de) | Jun 05, 2023 |
| ASUSTek       | ROG Flow X16 GV601RM_GV6... | Convertible | [5a2d788a64](https://linux-hardware.org/?probe=5a2d788a64) | Jun 05, 2023 |
| HP            | 8949 11                     | Desktop     | [06bca18276](https://linux-hardware.org/?probe=06bca18276) | Jun 04, 2023 |
| ASUSTek       | M4N72-E                     | Desktop     | [51d39945ec](https://linux-hardware.org/?probe=51d39945ec) | Jun 04, 2023 |
| MSI           | A55M-E33                    | Desktop     | [336b7f877d](https://linux-hardware.org/?probe=336b7f877d) | Jun 04, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [aafda7cf63](https://linux-hardware.org/?probe=aafda7cf63) | Jun 04, 2023 |
| Dell          | Inspiron 5437               | Notebook    | [d805b4ec1f](https://linux-hardware.org/?probe=d805b4ec1f) | Jun 03, 2023 |
| Foxconn       | A74ML-K                     | Desktop     | [7a4f7e239b](https://linux-hardware.org/?probe=7a4f7e239b) | Jun 03, 2023 |
| HP            | 8949 11                     | Desktop     | [f06749002f](https://linux-hardware.org/?probe=f06749002f) | Jun 03, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [5c280bbd6c](https://linux-hardware.org/?probe=5c280bbd6c) | Jun 03, 2023 |
| MSI           | B150M MORTAR                | Desktop     | [3fc6303165](https://linux-hardware.org/?probe=3fc6303165) | Jun 03, 2023 |
| MSI           | B450M BAZOOKA V2            | Desktop     | [e0008bd879](https://linux-hardware.org/?probe=e0008bd879) | Jun 03, 2023 |
| MSI           | B450M BAZOOKA V2            | Desktop     | [979df15914](https://linux-hardware.org/?probe=979df15914) | Jun 03, 2023 |
| Dell          | Inspiron 7472               | Notebook    | [53b9d0dfa6](https://linux-hardware.org/?probe=53b9d0dfa6) | Jun 03, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [9966a3f6d1](https://linux-hardware.org/?probe=9966a3f6d1) | Jun 03, 2023 |
| Dell          | XPS 17 9720                 | Notebook    | [71c4a65aae](https://linux-hardware.org/?probe=71c4a65aae) | Jun 03, 2023 |
| System76      | Oryx Pro                    | Notebook    | [b3b398ba61](https://linux-hardware.org/?probe=b3b398ba61) | Jun 03, 2023 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [2354c37832](https://linux-hardware.org/?probe=2354c37832) | Jun 02, 2023 |
| MSI           | Prestige 16 A12UD           | Notebook    | [b13e4f0242](https://linux-hardware.org/?probe=b13e4f0242) | Jun 02, 2023 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [b86be4f1de](https://linux-hardware.org/?probe=b86be4f1de) | Jun 02, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [a8f8239e40](https://linux-hardware.org/?probe=a8f8239e40) | Jun 02, 2023 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [7f2c514dff](https://linux-hardware.org/?probe=7f2c514dff) | Jun 02, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [ded9a8f554](https://linux-hardware.org/?probe=ded9a8f554) | Jun 02, 2023 |
| Acer          | Predator PH517-51           | Notebook    | [1de529b11c](https://linux-hardware.org/?probe=1de529b11c) | Jun 01, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [df7287f2c8](https://linux-hardware.org/?probe=df7287f2c8) | Jun 01, 2023 |
| HP            | 212A                        | Desktop     | [a0e56b03e2](https://linux-hardware.org/?probe=a0e56b03e2) | Jun 01, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [c33f531350](https://linux-hardware.org/?probe=c33f531350) | Jun 01, 2023 |
| System76      | Adder WS                    | Notebook    | [5cfa553a01](https://linux-hardware.org/?probe=5cfa553a01) | May 31, 2023 |
| MSI           | B350M BAZOOKA               | Desktop     | [a494d94087](https://linux-hardware.org/?probe=a494d94087) | May 31, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [16f1d67220](https://linux-hardware.org/?probe=16f1d67220) | May 31, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [d950f8b732](https://linux-hardware.org/?probe=d950f8b732) | May 31, 2023 |
| Acer          | Predator PH517-51           | Notebook    | [cc24e32ab1](https://linux-hardware.org/?probe=cc24e32ab1) | May 30, 2023 |
| MSI           | B350M PRO-VD PLUS           | Desktop     | [ca4e5a8f82](https://linux-hardware.org/?probe=ca4e5a8f82) | May 30, 2023 |
| BESSTAR Te... | HM90                        | Desktop     | [cb78f83d80](https://linux-hardware.org/?probe=cb78f83d80) | May 30, 2023 |
| Lenovo        | 3098 SDK0E50510 WIN         | Desktop     | [2334995ee9](https://linux-hardware.org/?probe=2334995ee9) | May 30, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [4f41d4f16f](https://linux-hardware.org/?probe=4f41d4f16f) | May 30, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [907448944d](https://linux-hardware.org/?probe=907448944d) | May 30, 2023 |
| AZW           | GTR V01                     | Mini pc     | [9144d0218a](https://linux-hardware.org/?probe=9144d0218a) | May 30, 2023 |
| ASUSTek       | F2A85-M                     | Desktop     | [1793fc9d72](https://linux-hardware.org/?probe=1793fc9d72) | May 30, 2023 |
| Lenovo        | ThinkPad T440p 20ANCTO1W... | Notebook    | [83f869ee2a](https://linux-hardware.org/?probe=83f869ee2a) | May 30, 2023 |
| Lenovo        | ThinkPad T440p 20ANCTO1W... | Notebook    | [23af21bb34](https://linux-hardware.org/?probe=23af21bb34) | May 30, 2023 |
| ASUSTek       | F2A85-M                     | Desktop     | [94fda2dea0](https://linux-hardware.org/?probe=94fda2dea0) | May 30, 2023 |
| Toshiba       | Satellite P755              | Notebook    | [5dc8f46db5](https://linux-hardware.org/?probe=5dc8f46db5) | May 29, 2023 |
| ASUSTek       | M5A97                       | Desktop     | [650fb21fd0](https://linux-hardware.org/?probe=650fb21fd0) | May 29, 2023 |
| Avell High... | A70 MOB                     | Notebook    | [70e4c12911](https://linux-hardware.org/?probe=70e4c12911) | May 29, 2023 |
| Dell          | 0NM64V A01                  | Desktop     | [a109a924f0](https://linux-hardware.org/?probe=a109a924f0) | May 29, 2023 |
| ASUSTek       | TUF Gaming H770-PRO WIFI    | Desktop     | [6729d5ffa7](https://linux-hardware.org/?probe=6729d5ffa7) | May 29, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [bcad978a06](https://linux-hardware.org/?probe=bcad978a06) | May 29, 2023 |
| ASRock        | H110M-DVS R3.0              | Desktop     | [505b123692](https://linux-hardware.org/?probe=505b123692) | May 29, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [331bbabc0e](https://linux-hardware.org/?probe=331bbabc0e) | May 29, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [8b1445b47c](https://linux-hardware.org/?probe=8b1445b47c) | May 29, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [06318d2354](https://linux-hardware.org/?probe=06318d2354) | May 29, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [c24eb2f7dd](https://linux-hardware.org/?probe=c24eb2f7dd) | May 29, 2023 |
| Apple         | MacBookAir5,1               | Notebook    | [4fc496bcc4](https://linux-hardware.org/?probe=4fc496bcc4) | May 29, 2023 |
| Lenovo        | ThinkPad T500 2056Y4R       | Notebook    | [dbd22d38bd](https://linux-hardware.org/?probe=dbd22d38bd) | May 28, 2023 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [2f1017a58e](https://linux-hardware.org/?probe=2f1017a58e) | May 28, 2023 |
| System76      | Adder WS                    | Notebook    | [d6de84e0c6](https://linux-hardware.org/?probe=d6de84e0c6) | May 28, 2023 |
| System76      | Adder WS                    | Notebook    | [5624c5b0e8](https://linux-hardware.org/?probe=5624c5b0e8) | May 28, 2023 |
| System76      | Adder WS                    | Notebook    | [2522fb534f](https://linux-hardware.org/?probe=2522fb534f) | May 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [1fde8a9c8c](https://linux-hardware.org/?probe=1fde8a9c8c) | May 28, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [439a2f1c9e](https://linux-hardware.org/?probe=439a2f1c9e) | May 28, 2023 |
| Lenovo        | ThinkPad T440p 20AWS1420... | Notebook    | [7faaacfcaf](https://linux-hardware.org/?probe=7faaacfcaf) | May 28, 2023 |
| AZW           | EQ                          | Desktop     | [8e6c18ebbb](https://linux-hardware.org/?probe=8e6c18ebbb) | May 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | Notebook    | [6b71e36a41](https://linux-hardware.org/?probe=6b71e36a41) | May 28, 2023 |
| AZW           | EQ                          | Desktop     | [98e5ea581c](https://linux-hardware.org/?probe=98e5ea581c) | May 28, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [46460561e1](https://linux-hardware.org/?probe=46460561e1) | May 27, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [b2672eb1db](https://linux-hardware.org/?probe=b2672eb1db) | May 27, 2023 |
| Lenovo        | Yoga 700-11ISK 80QE         | Notebook    | [149dfccfe7](https://linux-hardware.org/?probe=149dfccfe7) | May 27, 2023 |
| Google        | Kohaku                      | Notebook    | [2b46417afd](https://linux-hardware.org/?probe=2b46417afd) | May 27, 2023 |
| Dell          | Inspiron 7520               | Notebook    | [07b70ac9e5](https://linux-hardware.org/?probe=07b70ac9e5) | May 27, 2023 |
| System76      | Galago Pro                  | Notebook    | [51cc594a01](https://linux-hardware.org/?probe=51cc594a01) | May 27, 2023 |
| Apple         | MacBookPro15,1              | Notebook    | [8d5c73bd4d](https://linux-hardware.org/?probe=8d5c73bd4d) | May 27, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [ea5ba11b48](https://linux-hardware.org/?probe=ea5ba11b48) | May 27, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [e74ee1390f](https://linux-hardware.org/?probe=e74ee1390f) | May 26, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [ce5179659e](https://linux-hardware.org/?probe=ce5179659e) | May 26, 2023 |
| ASUSTek       | X555LN                      | Notebook    | [8f16767017](https://linux-hardware.org/?probe=8f16767017) | May 26, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [ac75726738](https://linux-hardware.org/?probe=ac75726738) | May 26, 2023 |
| HP            | ZBook 17 G6                 | Notebook    | [177d184559](https://linux-hardware.org/?probe=177d184559) | May 26, 2023 |
| HP            | ZBook 17 G6                 | Notebook    | [56a8a0e368](https://linux-hardware.org/?probe=56a8a0e368) | May 26, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [c3af0f3242](https://linux-hardware.org/?probe=c3af0f3242) | May 26, 2023 |
| ASUSTek       | TUF X299 MARK 1             | Desktop     | [9b2b467879](https://linux-hardware.org/?probe=9b2b467879) | May 26, 2023 |
| HP            | 0AA4h                       | Desktop     | [41ec821e77](https://linux-hardware.org/?probe=41ec821e77) | May 26, 2023 |
| ASRock        | 990FX Extreme4              | Desktop     | [8c61dd5381](https://linux-hardware.org/?probe=8c61dd5381) | May 26, 2023 |
| ASUSTek       | G20AJ                       | Desktop     | [92223e639f](https://linux-hardware.org/?probe=92223e639f) | May 26, 2023 |
| ASUSTek       | G20AJ                       | Desktop     | [9a58438669](https://linux-hardware.org/?probe=9a58438669) | May 26, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [a12e26f683](https://linux-hardware.org/?probe=a12e26f683) | May 26, 2023 |
| Dell          | Inspiron 7520               | Notebook    | [6d237fdf95](https://linux-hardware.org/?probe=6d237fdf95) | May 26, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [248bd35ba0](https://linux-hardware.org/?probe=248bd35ba0) | May 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [72f5c85f7f](https://linux-hardware.org/?probe=72f5c85f7f) | May 26, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [925f0e5016](https://linux-hardware.org/?probe=925f0e5016) | May 26, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [486d6ac497](https://linux-hardware.org/?probe=486d6ac497) | May 25, 2023 |
| ASUSTek       | X502CA                      | Notebook    | [7b19816353](https://linux-hardware.org/?probe=7b19816353) | May 25, 2023 |
| MSI           | Alpha 15 A3DDK              | Notebook    | [722e709153](https://linux-hardware.org/?probe=722e709153) | May 25, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [fcecd714d6](https://linux-hardware.org/?probe=fcecd714d6) | May 25, 2023 |
| Apple         | MacBookPro6,1               | Notebook    | [c8eb2c32b3](https://linux-hardware.org/?probe=c8eb2c32b3) | May 25, 2023 |
| Lenovo        | ThinkPad W540 20BHS0BD02    | Notebook    | [b6318da458](https://linux-hardware.org/?probe=b6318da458) | May 25, 2023 |
| Lenovo        | IdeaPad Y560                | Notebook    | [a8b595f03c](https://linux-hardware.org/?probe=a8b595f03c) | May 24, 2023 |
| HP            | Laptop PC 15-e3000          | Notebook    | [b3f6af4f8c](https://linux-hardware.org/?probe=b3f6af4f8c) | May 24, 2023 |
| Dell          | Precision 5470              | Notebook    | [e0a145106b](https://linux-hardware.org/?probe=e0a145106b) | May 24, 2023 |
| HP            | Laptop PC 15-e3000          | Notebook    | [29c9a90dc9](https://linux-hardware.org/?probe=29c9a90dc9) | May 24, 2023 |
| ASUSTek       | P8H67-M                     | Desktop     | [41755306e6](https://linux-hardware.org/?probe=41755306e6) | May 24, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [a38171543f](https://linux-hardware.org/?probe=a38171543f) | May 24, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [8e5402cb16](https://linux-hardware.org/?probe=8e5402cb16) | May 24, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [31ea0c4ab8](https://linux-hardware.org/?probe=31ea0c4ab8) | May 24, 2023 |
| Dell          | G15 5511                    | Notebook    | [3876065a3e](https://linux-hardware.org/?probe=3876065a3e) | May 24, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [b7d26b3293](https://linux-hardware.org/?probe=b7d26b3293) | May 24, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [e3a554c09d](https://linux-hardware.org/?probe=e3a554c09d) | May 24, 2023 |
| Apple         | MacBookPro6,1               | Notebook    | [a8da820b95](https://linux-hardware.org/?probe=a8da820b95) | May 24, 2023 |
| Lenovo        | Yoga 920-13IKB 80Y7         | Convertible | [f339d13a59](https://linux-hardware.org/?probe=f339d13a59) | May 24, 2023 |
| HP            | 212A                        | Desktop     | [87b3c9809f](https://linux-hardware.org/?probe=87b3c9809f) | May 23, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | Desktop     | [8604115d8b](https://linux-hardware.org/?probe=8604115d8b) | May 23, 2023 |
| HP            | Spectre Pro x360 G1         | Notebook    | [90df3b7bfa](https://linux-hardware.org/?probe=90df3b7bfa) | May 23, 2023 |
| HP            | Spectre Pro x360 G1         | Notebook    | [0f0ad128aa](https://linux-hardware.org/?probe=0f0ad128aa) | May 23, 2023 |

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
| 6.2.6-76060206-generic   | 825       | 22.08%  |
| 6.0.12-76060006-generic  | 475       | 12.71%  |
| 5.19.0-76051900-generic  | 447       | 11.96%  |
| 5.17.5-76051705-generic  | 417       | 11.16%  |
| 6.0.6-76060006-generic   | 300       | 8.03%   |
| 6.4.6-76060406-generic   | 257       | 6.88%   |
| 5.18.10-76051810-generic | 207       | 5.54%   |
| 5.17.15-76051715-generic | 185       | 4.95%   |
| 5.16.19-76051619-generic | 122       | 3.27%   |
| 6.2.0-76060200-generic   | 121       | 3.24%   |
| 6.0.2-76060002-generic   | 92        | 2.46%   |
| 6.1.11-76060111-generic  | 90        | 2.41%   |
| 5.19.16-76051916-generic | 43        | 1.15%   |
| 6.0.3-76060003-generic   | 40        | 1.07%   |
| 6.3.7-060307-generic     | 5         | 0.13%   |
| 6.3.4-060304-generic     | 3         | 0.08%   |
| 6.1.0-1006-oem           | 3         | 0.08%   |
| 5.16.15-76051615-generic | 3         | 0.08%   |
| 6.4.0-060400-generic     | 2         | 0.05%   |
| 6.2.11-060211-generic    | 2         | 0.05%   |
| 6.1.8-060108-generic     | 2         | 0.05%   |
| 6.1.0-x64v1-xanmod1      | 2         | 0.05%   |
| 6.0.9-060009-generic     | 2         | 0.05%   |
| 6.0.2-x64v1-xanmod1      | 2         | 0.05%   |
| 5.19.12-xanmod1          | 2         | 0.05%   |
| 5.17.7-051707-generic    | 2         | 0.05%   |
| 5.17.5-051705-generic    | 2         | 0.05%   |
| 6.5.5-x64v3-xanmod1      | 1         | 0.03%   |
| 6.5.0-rc2                | 1         | 0.03%   |
| 6.4.8-x64v3-xanmod1      | 1         | 0.03%   |
| 6.4.7-surface            | 1         | 0.03%   |
| 6.4.5-x64v2-xanmod1      | 1         | 0.03%   |
| 6.4.3-060403-generic     | 1         | 0.03%   |
| 6.4.2-surface            | 1         | 0.03%   |
| 6.4.12-2-liquorix-amd64  | 1         | 0.03%   |
| 6.3.9-x64v3-xanmod1      | 1         | 0.03%   |
| 6.3.9-060309-generic     | 1         | 0.03%   |
| 6.3.8-x64v1-xanmod1      | 1         | 0.03%   |
| 6.3.8-1-liquorix-amd64   | 1         | 0.03%   |
| 6.3.5-x64v1-xanmod1      | 1         | 0.03%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2.6   | 826       | 22.12%  |
| 6.0.12  | 476       | 12.74%  |
| 5.19.0  | 451       | 12.07%  |
| 5.17.5  | 420       | 11.24%  |
| 6.0.6   | 301       | 8.06%   |
| 6.4.6   | 257       | 6.88%   |
| 5.18.10 | 207       | 5.54%   |
| 5.17.15 | 185       | 4.95%   |
| 5.16.19 | 122       | 3.27%   |
| 6.2.0   | 121       | 3.24%   |
| 6.0.2   | 95        | 2.54%   |
| 6.1.11  | 91        | 2.44%   |
| 5.19.16 | 43        | 1.15%   |
| 6.0.3   | 40        | 1.07%   |
| 6.1.0   | 6         | 0.16%   |
| 5.15.0  | 6         | 0.16%   |
| 6.3.7   | 5         | 0.13%   |
| 6.3.4   | 4         | 0.11%   |
| 6.1.8   | 3         | 0.08%   |
| 6.0.9   | 3         | 0.08%   |
| 5.16.15 | 3         | 0.08%   |
| 6.4.0   | 2         | 0.05%   |
| 6.3.9   | 2         | 0.05%   |
| 6.3.8   | 2         | 0.05%   |
| 6.3.1   | 2         | 0.05%   |
| 6.2.9   | 2         | 0.05%   |
| 6.2.2   | 2         | 0.05%   |
| 6.2.11  | 2         | 0.05%   |
| 6.1.9   | 2         | 0.05%   |
| 6.1.12  | 2         | 0.05%   |
| 6.0.0   | 2         | 0.05%   |
| 5.19.12 | 2         | 0.05%   |
| 5.18.0  | 2         | 0.05%   |
| 5.17.7  | 2         | 0.05%   |
| 5.17.0  | 2         | 0.05%   |
| 6.5.5   | 1         | 0.03%   |
| 6.5.0   | 1         | 0.03%   |
| 6.4.8   | 1         | 0.03%   |
| 6.4.7   | 1         | 0.03%   |
| 6.4.5   | 1         | 0.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2     | 946       | 25.75%  |
| 6.0     | 891       | 24.25%  |
| 5.17    | 601       | 16.36%  |
| 5.19    | 496       | 13.5%   |
| 6.4     | 264       | 7.19%   |
| 5.18    | 213       | 5.8%    |
| 5.16    | 126       | 3.43%   |
| 6.1     | 108       | 2.94%   |
| 6.3     | 17        | 0.46%   |
| 5.15    | 9         | 0.24%   |
| 6.5     | 2         | 0.05%   |
| 5.4     | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 3364      | 99.88%  |
| aarch64 | 4         | 0.12%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 3271      | 96.8%   |
| KDE5            | 45        | 1.33%   |
| Unknown         | 23        | 0.68%   |
| X-Cinnamon      | 14        | 0.41%   |
| GNOME Flashback | 7         | 0.21%   |
| Unity           | 4         | 0.12%   |
| LXQt            | 4         | 0.12%   |
| Cinnamon        | 3         | 0.09%   |
| XFCE            | 2         | 0.06%   |
| MATE            | 2         | 0.06%   |
| i3              | 2         | 0.06%   |
| UKUI            | 1         | 0.03%   |
| awesome         | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 3220      | 95.01%  |
| Wayland | 148       | 4.37%   |
| Unknown | 16        | 0.47%   |
| Tty     | 5         | 0.15%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2530      | 74.59%  |
| GDM3    | 842       | 24.82%  |
| SDDM    | 10        | 0.29%   |
| GDM     | 8         | 0.24%   |
| LightDM | 2         | 0.06%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 2029      | 59.76%  |
| en_GB   | 224       | 6.6%    |
| pt_BR   | 183       | 5.39%   |
| de_DE   | 152       | 4.48%   |
| C       | 106       | 3.12%   |
| en_AU   | 76        | 2.24%   |
| it_IT   | 66        | 1.94%   |
| en_CA   | 64        | 1.89%   |
| fr_FR   | 61        | 1.8%    |
| es_ES   | 44        | 1.3%    |
| ru_RU   | 37        | 1.09%   |
| pl_PL   | 35        | 1.03%   |
| Unknown | 22        | 0.65%   |
| sv_SE   | 19        | 0.56%   |
| nb_NO   | 19        | 0.56%   |
| pt_PT   | 17        | 0.5%    |
| nl_NL   | 16        | 0.47%   |
| fi_FI   | 16        | 0.47%   |
| en_IN   | 14        | 0.41%   |
| es_CL   | 13        | 0.38%   |
| es_MX   | 12        | 0.35%   |
| en_IE   | 12        | 0.35%   |
| en_NZ   | 11        | 0.32%   |
| ja_JP   | 10        | 0.29%   |
| fr_CA   | 10        | 0.29%   |
| de_CH   | 10        | 0.29%   |
| da_DK   | 10        | 0.29%   |
| es_AR   | 9         | 0.27%   |
| en_DK   | 9         | 0.27%   |
| de_AT   | 9         | 0.27%   |
| tr_TR   | 8         | 0.24%   |
| en_ZA   | 8         | 0.24%   |
| cs_CZ   | 7         | 0.21%   |
| fr_CH   | 4         | 0.12%   |
| fr_BE   | 4         | 0.12%   |
| es_CO   | 4         | 0.12%   |
| ro_RO   | 3         | 0.09%   |
| en_IL   | 3         | 0.09%   |
| zh_TW   | 2         | 0.06%   |
| zh_CN   | 2         | 0.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2573      | 75.88%  |
| EFI  | 818       | 24.12%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 3199      | 94.64%  |
| Btrfs   | 98        | 2.9%    |
| Overlay | 68        | 2.01%   |
| Xfs     | 10        | 0.3%    |
| Zfs     | 3         | 0.09%   |
| Tmpfs   | 1         | 0.03%   |
| Unknown | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2510      | 74%     |
| GPT     | 828       | 24.41%  |
| MBR     | 54        | 1.59%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3269      | 96.77%  |
| Yes       | 109       | 3.23%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3039      | 89.94%  |
| Yes       | 340       | 10.06%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 602       | 17.87%  |
| Lenovo                  | 478       | 14.19%  |
| Dell                    | 419       | 12.44%  |
| Hewlett-Packard         | 388       | 11.52%  |
| MSI                     | 248       | 7.36%   |
| Gigabyte Technology     | 215       | 6.38%   |
| Apple                   | 187       | 5.55%   |
| Acer                    | 153       | 4.54%   |
| ASRock                  | 101       | 3%      |
| System76                | 79        | 2.35%   |
| Intel                   | 41        | 1.22%   |
| Toshiba                 | 38        | 1.13%   |
| Samsung Electronics     | 36        | 1.07%   |
| HUAWEI                  | 29        | 0.86%   |
| Alienware               | 24        | 0.71%   |
| Microsoft               | 20        | 0.59%   |
| Unknown                 | 20        | 0.59%   |
| Fujitsu                 | 19        | 0.56%   |
| Google                  | 17        | 0.5%    |
| Notebook                | 14        | 0.42%   |
| Positivo                | 12        | 0.36%   |
| AZW                     | 12        | 0.36%   |
| Sony                    | 11        | 0.33%   |
| GPU Company             | 10        | 0.3%    |
| BESSTAR Tech            | 10        | 0.3%    |
| Razer                   | 9         | 0.27%   |
| Timi                    | 8         | 0.24%   |
| Framework               | 8         | 0.24%   |
| HONOR                   | 7         | 0.21%   |
| Supermicro              | 6         | 0.18%   |
| MACHINIST               | 6         | 0.18%   |
| Avell High Performance  | 6         | 0.18%   |
| Pegatron                | 5         | 0.15%   |
| Foxconn                 | 5         | 0.15%   |
| Biostar                 | 5         | 0.15%   |
| ZOTAC                   | 4         | 0.12%   |
| TUXEDO                  | 4         | 0.12%   |
| Schenker                | 4         | 0.12%   |
| Raspberry Pi Foundation | 4         | 0.12%   |
| PC Specialist           | 4         | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Unknown                        | 27        | 0.8%    |
| ASUS All Series                | 22        | 0.65%   |
| System76 Oryx Pro              | 18        | 0.53%   |
| ASUS ROG STRIX B550-F GAMING   | 15        | 0.45%   |
| System76 Lemur Pro             | 14        | 0.42%   |
| Apple MacBookAir7,2            | 13        | 0.39%   |
| System76 Gazelle               | 12        | 0.36%   |
| Apple MacBookPro12,1           | 12        | 0.36%   |
| HP Dev One Notebook PC         | 10        | 0.3%    |
| ASUS ROG STRIX B550-I GAMING   | 10        | 0.3%    |
| ASUS ROG STRIX B450-F GAMING   | 10        | 0.3%    |
| Apple MacBookPro9,2            | 10        | 0.3%    |
| Gigabyte X570 AORUS ELITE      | 9         | 0.27%   |
| Apple MacBookPro11,3           | 9         | 0.27%   |
| Apple MacBookAir6,2            | 9         | 0.27%   |
| ASUS TUF Gaming X570-PLUS      | 8         | 0.24%   |
| ASUS TUF Gaming B550-PLUS      | 8         | 0.24%   |
| Apple MacBookPro8,1            | 8         | 0.24%   |
| System76 Galago Pro            | 7         | 0.21%   |
| MSI MS-7C91                    | 7         | 0.21%   |
| MSI MS-7B86                    | 7         | 0.21%   |
| Gigabyte B450 AORUS M          | 7         | 0.21%   |
| Dell XPS 15 9520               | 7         | 0.21%   |
| Apple MacBookPro7,1            | 7         | 0.21%   |
| System76 Thelio                | 6         | 0.18%   |
| System76 Darter Pro            | 6         | 0.18%   |
| MSI MS-7A38                    | 6         | 0.18%   |
| MSI MS-7A34                    | 6         | 0.18%   |
| Lenovo IdeaPad S145-15API 81V7 | 6         | 0.18%   |
| HP Pavilion 15                 | 6         | 0.18%   |
| HP Notebook                    | 6         | 0.18%   |
| Gigabyte B550M DS3H            | 6         | 0.18%   |
| Gigabyte A320M-S2H             | 6         | 0.18%   |
| Dell XPS 15 9570               | 6         | 0.18%   |
| Dell XPS 13 9310               | 6         | 0.18%   |
| Dell Latitude E7240            | 6         | 0.18%   |
| ASUS TUF Gaming B550M-PLUS     | 6         | 0.18%   |
| ASUS PRIME B550M-A             | 6         | 0.18%   |
| Acer Aspire A515-45            | 6         | 0.18%   |
| System76 Pangolin              | 5         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 185       | 5.49%   |
| ASUS ROG           | 163       | 4.84%   |
| Lenovo IdeaPad     | 108       | 3.21%   |
| Dell Inspiron      | 106       | 3.15%   |
| Acer Aspire        | 93        | 2.76%   |
| Dell Latitude      | 87        | 2.58%   |
| Dell XPS           | 74        | 2.2%    |
| HP Pavilion        | 65        | 1.93%   |
| ASUS TUF           | 59        | 1.75%   |
| ASUS PRIME         | 56        | 1.66%   |
| Dell Precision     | 54        | 1.6%    |
| ASUS VivoBook      | 54        | 1.6%    |
| HP EliteBook       | 49        | 1.45%   |
| Lenovo Legion      | 45        | 1.34%   |
| HP Laptop          | 45        | 1.34%   |
| Dell OptiPlex      | 37        | 1.1%    |
| Lenovo Yoga        | 33        | 0.98%   |
| Toshiba Satellite  | 32        | 0.95%   |
| HP ProBook         | 32        | 0.95%   |
| ASUS ASUS          | 31        | 0.92%   |
| HP ENVY            | 30        | 0.89%   |
| Unknown            | 27        | 0.8%    |
| ASUS ZenBook       | 26        | 0.77%   |
| Lenovo ThinkCentre | 24        | 0.71%   |
| HP Compaq          | 22        | 0.65%   |
| Gigabyte X570      | 22        | 0.65%   |
| ASUS All           | 22        | 0.65%   |
| Acer Swift         | 22        | 0.65%   |
| Dell Vostro        | 21        | 0.62%   |
| Microsoft Surface  | 20        | 0.59%   |
| HP ZBook           | 20        | 0.59%   |
| HP OMEN            | 20        | 0.59%   |
| Acer Nitro         | 20        | 0.59%   |
| Apple MacBookPro11 | 19        | 0.56%   |
| System76 Oryx      | 18        | 0.53%   |
| Gigabyte B450      | 18        | 0.53%   |
| System76 Lemur     | 14        | 0.42%   |
| HP EliteDesk       | 14        | 0.42%   |
| Lenovo ThinkBook   | 13        | 0.39%   |
| Gigabyte B550      | 13        | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 460       | 13.66%  |
| 2020    | 425       | 12.62%  |
| 2022    | 380       | 11.28%  |
| 2018    | 319       | 9.47%   |
| 2019    | 316       | 9.38%   |
| 2013    | 196       | 5.82%   |
| 2012    | 179       | 5.31%   |
| 2017    | 173       | 5.14%   |
| 2015    | 168       | 4.99%   |
| 2014    | 154       | 4.57%   |
| 2011    | 154       | 4.57%   |
| 2016    | 153       | 4.54%   |
| 2010    | 93        | 2.76%   |
| 2009    | 80        | 2.38%   |
| 2023    | 61        | 1.81%   |
| 2008    | 34        | 1.01%   |
| 2007    | 14        | 0.42%   |
| Unknown | 6         | 0.18%   |
| 2006    | 2         | 0.06%   |
| 2005    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1951      | 57.93%  |
| Desktop        | 1149      | 34.12%  |
| Convertible    | 114       | 3.38%   |
| Mini pc        | 61        | 1.81%   |
| All in one     | 46        | 1.37%   |
| Tablet         | 32        | 0.95%   |
| Server         | 10        | 0.3%    |
| System on chip | 5         | 0.15%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 3367      | 99.94%  |
| Enabled  | 2         | 0.06%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3300      | 97.98%  |
| Yes  | 68        | 2.02%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 897       | 26.37%  |
| 4.01-8.0        | 735       | 21.6%   |
| 8.01-16.0       | 613       | 18.02%  |
| 32.01-64.0      | 573       | 16.84%  |
| 3.01-4.0        | 295       | 8.67%   |
| 64.01-256.0     | 182       | 5.35%   |
| 24.01-32.0      | 86        | 2.53%   |
| 1.01-2.0        | 10        | 0.29%   |
| 2.01-3.0        | 8         | 0.24%   |
| More than 256.0 | 3         | 0.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1201      | 32.8%   |
| 2.01-3.0    | 926       | 25.29%  |
| 3.01-4.0    | 800       | 21.85%  |
| 8.01-16.0   | 364       | 9.94%   |
| 1.01-2.0    | 297       | 8.11%   |
| 16.01-24.0  | 47        | 1.28%   |
| 24.01-32.0  | 14        | 0.38%   |
| 32.01-64.0  | 8         | 0.22%   |
| 0.51-1.0    | 3         | 0.08%   |
| 64.01-256.0 | 2         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1997      | 58.26%  |
| 2      | 873       | 25.47%  |
| 3      | 291       | 8.49%   |
| 4      | 130       | 3.79%   |
| 5      | 66        | 1.93%   |
| 6      | 28        | 0.82%   |
| 7      | 16        | 0.47%   |
| 0      | 15        | 0.44%   |
| 8      | 4         | 0.12%   |
| 9      | 3         | 0.09%   |
| 10     | 2         | 0.06%   |
| 26     | 1         | 0.03%   |
| 19     | 1         | 0.03%   |
| 11     | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2606      | 77.21%  |
| Yes       | 769       | 22.79%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2760      | 81.51%  |
| No        | 626       | 18.49%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2832      | 83.91%  |
| No        | 543       | 16.09%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2442      | 72.1%   |
| No        | 945       | 27.9%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 1068      | 31.53%  |
| Brazil       | 258       | 7.62%   |
| Germany      | 229       | 6.76%   |
| UK           | 153       | 4.52%   |
| Canada       | 148       | 4.37%   |
| Italy        | 121       | 3.57%   |
| Australia    | 106       | 3.13%   |
| India        | 89        | 2.63%   |
| France       | 86        | 2.54%   |
| Netherlands  | 68        | 2.01%   |
| Russia       | 62        | 1.83%   |
| Poland       | 57        | 1.68%   |
| Spain        | 53        | 1.56%   |
| Sweden       | 49        | 1.45%   |
| Mexico       | 44        | 1.3%    |
| Norway       | 43        | 1.27%   |
| Portugal     | 37        | 1.09%   |
| Finland      | 36        | 1.06%   |
| Austria      | 30        | 0.89%   |
| Turkey       | 28        | 0.83%   |
| Switzerland  | 28        | 0.83%   |
| Denmark      | 27        | 0.8%    |
| Greece       | 26        | 0.77%   |
| Indonesia    | 24        | 0.71%   |
| Chile        | 24        | 0.71%   |
| Romania      | 23        | 0.68%   |
| New Zealand  | 23        | 0.68%   |
| Czechia      | 23        | 0.68%   |
| Argentina    | 23        | 0.68%   |
| Philippines  | 22        | 0.65%   |
| Japan        | 22        | 0.65%   |
| Belgium      | 21        | 0.62%   |
| Serbia       | 18        | 0.53%   |
| Hungary      | 18        | 0.53%   |
| South Africa | 17        | 0.5%    |
| Ireland      | 17        | 0.5%    |
| Thailand     | 14        | 0.41%   |
| Malaysia     | 14        | 0.41%   |
| Bulgaria     | 13        | 0.38%   |
| Slovakia     | 10        | 0.3%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Sao Paulo      | 27        | 0.77%   |
| Melbourne      | 25        | 0.71%   |
| Sydney         | 24        | 0.68%   |
| Milan          | 23        | 0.65%   |
| Helsinki       | 23        | 0.65%   |
| Brisbane       | 23        | 0.65%   |
| Berlin         | 22        | 0.63%   |
| Seattle        | 21        | 0.6%    |
| Rio de Janeiro | 20        | 0.57%   |
| Vienna         | 19        | 0.54%   |
| Oslo           | 19        | 0.54%   |
| Moscow         | 17        | 0.48%   |
| Istanbul       | 16        | 0.45%   |
| Madrid         | 15        | 0.43%   |
| Chicago        | 15        | 0.43%   |
| Bengaluru      | 15        | 0.43%   |
| Warsaw         | 14        | 0.4%    |
| Denver         | 14        | 0.4%    |
| Rome           | 13        | 0.37%   |
| Lisbon         | 13        | 0.37%   |
| Hamburg        | 13        | 0.37%   |
| Belgrade       | 13        | 0.37%   |
| Zurich         | 12        | 0.34%   |
| New York       | 12        | 0.34%   |
| London         | 12        | 0.34%   |
| Edmonton       | 12        | 0.34%   |
| Dallas         | 12        | 0.34%   |
| Toronto        | 11        | 0.31%   |
| San Antonio    | 11        | 0.31%   |
| Paris          | 11        | 0.31%   |
| Munich         | 11        | 0.31%   |
| Auckland       | 11        | 0.31%   |
| Amsterdam      | 11        | 0.31%   |
| Singapore      | 10        | 0.28%   |
| Prague         | 10        | 0.28%   |
| Portland       | 10        | 0.28%   |
| Montreal       | 10        | 0.28%   |
| Dublin         | 10        | 0.28%   |
| Calgary        | 10        | 0.28%   |
| Stockholm      | 9         | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 979       | 1424   | 19.05%  |
| WDC                         | 555       | 757    | 10.8%   |
| Seagate                     | 533       | 741    | 10.37%  |
| Sandisk                     | 396       | 508    | 7.71%   |
| Kingston                    | 267       | 318    | 5.2%    |
| Toshiba                     | 236       | 281    | 4.59%   |
| Crucial                     | 222       | 299    | 4.32%   |
| SK hynix                    | 195       | 228    | 3.8%    |
| Intel                       | 144       | 186    | 2.8%    |
| Unknown                     | 133       | 174    | 2.59%   |
| Micron Technology           | 128       | 153    | 2.49%   |
| Apple                       | 104       | 118    | 2.02%   |
| Hitachi                     | 76        | 114    | 1.48%   |
| Phison Electronics          | 75        | 104    | 1.46%   |
| A-DATA Technology           | 73        | 81     | 1.42%   |
| Micron/Crucial Technology   | 70        | 91     | 1.36%   |
| HGST                        | 69        | 80     | 1.34%   |
| KIOXIA                      | 54        | 60     | 1.05%   |
| Phison                      | 52        | 63     | 1.01%   |
| China                       | 51        | 68     | 0.99%   |
| PNY                         | 50        | 64     | 0.97%   |
| Silicon Motion              | 44        | 55     | 0.86%   |
| Kingston Technology Company | 41        | 46     | 0.8%    |
| SPCC                        | 29        | 39     | 0.56%   |
| Netac                       | 23        | 24     | 0.45%   |
| Unknown                     | 23        | 27     | 0.45%   |
| Intenso                     | 22        | 31     | 0.43%   |
| ADATA Technology            | 20        | 22     | 0.39%   |
| Team                        | 18        | 23     | 0.35%   |
| Realtek Semiconductor       | 16        | 16     | 0.31%   |
| Patriot                     | 16        | 19     | 0.31%   |
| JMicron Technology          | 16        | 26     | 0.31%   |
| LITEON                      | 15        | 18     | 0.29%   |
| OCZ                         | 14        | 19     | 0.27%   |
| LITEONIT                    | 14        | 23     | 0.27%   |
| KingSpec                    | 14        | 15     | 0.27%   |
| Transcend                   | 13        | 16     | 0.25%   |
| XPG                         | 12        | 14     | 0.23%   |
| Lexar                       | 11        | 14     | 0.21%   |
| Union Memory (Shenzhen)     | 10        | 12     | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB   | 124       | 2.19%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB    | 75        | 1.32%   |
| Kingston SA400S37240G 240GB SSD                       | 63        | 1.11%   |
| SanDisk NVMe SSD Drive 1TB                            | 41        | 0.72%   |
| Samsung SSD 860 EVO 1TB                               | 40        | 0.71%   |
| Samsung SSD 850 EVO 250GB                             | 39        | 0.69%   |
| Seagate ST1000LM035-1RK172 1TB                        | 37        | 0.65%   |
| Samsung SSD 850 EVO 500GB                             | 36        | 0.64%   |
| Samsung NVMe SSD Drive 1TB                            | 36        | 0.64%   |
| Seagate ST2000DM008-2FR102 2TB                        | 35        | 0.62%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                   | 35        | 0.62%   |
| Samsung SSD 860 EVO 500GB                             | 34        | 0.6%    |
| Kingston SA400S37480G 480GB SSD                       | 34        | 0.6%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963 500GB   | 33        | 0.58%   |
| Crucial CT1000MX500SSD1 1TB                           | 33        | 0.58%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB                  | 31        | 0.55%   |
| Phison E12 NVMe Controller 2TB                        | 31        | 0.55%   |
| Kingston SA400S37120G 120GB SSD                       | 31        | 0.55%   |
| Seagate ST1000DM010-2EP102 1TB                        | 29        | 0.51%   |
| Samsung NVMe SSD Drive 500GB                          | 29        | 0.51%   |
| Crucial CT240BX500SSD1 240GB                          | 28        | 0.49%   |
| Samsung SSD 980 1TB                                   | 25        | 0.44%   |
| Crucial CT500MX500SSD1 500GB                          | 25        | 0.44%   |
| Unknown                                               | 23        | 0.41%   |
| Unknown MMC Card  64GB                                | 22        | 0.39%   |
| Toshiba MQ01ABD100 1TB                                | 22        | 0.39%   |
| Samsung NVMe SSD Drive 512GB                          | 22        | 0.39%   |
| Intel SSD 660P Series 1024GB                          | 22        | 0.39%   |
| Seagate ST4000DM004-2CV104 4TB                        | 21        | 0.37%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB      | 21        | 0.37%   |
| Seagate ST500DM002-1BD142 500GB                       | 20        | 0.35%   |
| Samsung SSD 970 EVO Plus 1TB                          | 20        | 0.35%   |
| Samsung NVMe SSD Drive 2TB                            | 20        | 0.35%   |
| HGST HTS721010A9E630 1TB                              | 20        | 0.35%   |
| Crucial CT1000BX500SSD1 1TB                           | 20        | 0.35%   |
| Toshiba MQ04ABF100 1TB                                | 19        | 0.34%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 512GB | 19        | 0.34%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 19        | 0.34%   |
| Seagate ST1000DM003-1ER162 1TB                        | 19        | 0.34%   |
| Seagate Expansion 1TB                                 | 19        | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 514       | 705    | 38.97%  |
| WDC                 | 387       | 544    | 29.34%  |
| Toshiba             | 165       | 194    | 12.51%  |
| Hitachi             | 76        | 114    | 5.76%   |
| HGST                | 69        | 80     | 5.23%   |
| Samsung Electronics | 36        | 45     | 2.73%   |
| Apple               | 22        | 25     | 1.67%   |
| Unknown             | 19        | 23     | 1.44%   |
| SABRENT             | 7         | 11     | 0.53%   |
| Fujitsu             | 6         | 9      | 0.45%   |
| Maxtor              | 3         | 3      | 0.23%   |
| JMicron Technology  | 2         | 9      | 0.15%   |
| Intenso             | 2         | 5      | 0.15%   |
| WD MediaMax         | 1         | 1      | 0.08%   |
| USB3.0              | 1         | 1      | 0.08%   |
| StoreJet            | 1         | 1      | 0.08%   |
| RSH-339             | 1         | 1      | 0.08%   |
| LaCie               | 1         | 2      | 0.08%   |
| HGST HDN            | 1         | 1      | 0.08%   |
| External            | 1         | 1      | 0.08%   |
| ASMT                | 1         | 1      | 0.08%   |
| ASMedia             | 1         | 1      | 0.08%   |
| Asm                 | 1         | 1      | 0.08%   |
| Unknown             | 1         | 1      | 0.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 390       | 552    | 23.19%  |
| Kingston            | 203       | 237    | 12.07%  |
| Crucial             | 195       | 260    | 11.59%  |
| SanDisk             | 144       | 176    | 8.56%   |
| WDC                 | 99        | 117    | 5.89%   |
| Apple               | 69        | 75     | 4.1%    |
| A-DATA Technology   | 51        | 56     | 3.03%   |
| China               | 50        | 67     | 2.97%   |
| PNY                 | 48        | 62     | 2.85%   |
| Intel               | 32        | 42     | 1.9%    |
| SK hynix            | 30        | 35     | 1.78%   |
| Micron Technology   | 28        | 31     | 1.66%   |
| SPCC                | 23        | 27     | 1.37%   |
| Toshiba             | 20        | 20     | 1.19%   |
| Netac               | 19        | 20     | 1.13%   |
| Patriot             | 15        | 18     | 0.89%   |
| OCZ                 | 14        | 19     | 0.83%   |
| LITEONIT            | 14        | 23     | 0.83%   |
| KingSpec            | 14        | 15     | 0.83%   |
| Intenso             | 14        | 19     | 0.83%   |
| LITEON              | 13        | 16     | 0.77%   |
| Transcend           | 12        | 15     | 0.71%   |
| Team                | 11        | 15     | 0.65%   |
| JMicron Technology  | 10        | 11     | 0.59%   |
| Apacer              | 9         | 14     | 0.54%   |
| Hewlett-Packard     | 8         | 11     | 0.48%   |
| Lexar               | 7         | 9      | 0.42%   |
| GOODRAM             | 6         | 6      | 0.36%   |
| Seagate             | 5         | 6      | 0.3%    |
| KingDian            | 5         | 10     | 0.3%    |
| Gigabyte Technology | 5         | 5      | 0.3%    |
| Verbatim            | 4         | 8      | 0.24%   |
| Mushkin             | 4         | 6      | 0.24%   |
| Fanxiang            | 4         | 4      | 0.24%   |
| Dogfish             | 4         | 4      | 0.24%   |
| Corsair             | 4         | 6      | 0.24%   |
| Unknown             | 4         | 4      | 0.24%   |
| TO Exter            | 3         | 3      | 0.18%   |
| OWC                 | 3         | 3      | 0.18%   |
| MyDigitalSSD        | 3         | 3      | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 1770      | 2567   | 39.06%  |
| SSD     | 1449      | 2128   | 31.98%  |
| HDD     | 1111      | 1779   | 24.52%  |
| MMC     | 109       | 128    | 2.41%   |
| Unknown | 92        | 154    | 2.03%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2065      | 3710   | 49.66%  |
| NVMe | 1765      | 2557   | 42.45%  |
| SAS  | 219       | 361    | 5.27%   |
| MMC  | 109       | 128    | 2.62%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1420      | 2054   | 52.13%  |
| 0.51-1.0   | 864       | 1168   | 31.72%  |
| 1.01-2.0   | 251       | 359    | 9.21%   |
| 3.01-4.0   | 82        | 133    | 3.01%   |
| 4.01-10.0  | 63        | 119    | 2.31%   |
| 2.01-3.0   | 36        | 59     | 1.32%   |
| 10.01-20.0 | 8         | 15     | 0.29%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 947       | 27.19%  |
| 251-500        | 876       | 25.15%  |
| 501-1000       | 741       | 21.27%  |
| 1001-2000      | 329       | 9.45%   |
| More than 3000 | 194       | 5.57%   |
| 2001-3000      | 128       | 3.67%   |
| 51-100         | 109       | 3.13%   |
| 1-20           | 85        | 2.44%   |
| 21-50          | 50        | 1.44%   |
| Unknown        | 24        | 0.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1037      | 28.63%  |
| 21-50          | 798       | 22.03%  |
| 101-250        | 541       | 14.94%  |
| 51-100         | 453       | 12.51%  |
| 251-500        | 343       | 9.47%   |
| 501-1000       | 201       | 5.55%   |
| 1001-2000      | 112       | 3.09%   |
| More than 3000 | 72        | 1.99%   |
| 2001-3000      | 41        | 1.13%   |
| Unknown        | 24        | 0.66%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                       | Computers | Drives | Percent |
|---------------------------------------------|-----------|--------|---------|
| SK hynix PC711 HFS001TDE9X073N 1TB          | 3         | 3      | 3.09%   |
| HGST HTS725050A7E630 500GB                  | 3         | 4      | 3.09%   |
| WDC WD10JPVX-60JC3T0 1TB                    | 2         | 2      | 2.06%   |
| Seagate ST3250310AS 250GB                   | 2         | 4      | 2.06%   |
| Seagate ST1000LX015-1U7172 1TB              | 2         | 2      | 2.06%   |
| Seagate ST1000LM024 HN-M101MBB 1TB          | 2         | 2      | 2.06%   |
| Samsung Electronics SSD 850 EVO 250GB       | 2         | 2      | 2.06%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD            | 1         | 1      | 1.03%   |
| WDC WDS240G2G0A-00JH30 240GB SSD            | 1         | 1      | 1.03%   |
| WDC WDS100T2B0B-00YS70 1TB SSD              | 1         | 1      | 1.03%   |
| WDC WD60EFRX-68L0BN1 6TB                    | 1         | 1      | 1.03%   |
| WDC WD5001AALS-00J7B1 500GB                 | 1         | 1      | 1.03%   |
| WDC WD5000LPVX-22V0TT0 500GB                | 1         | 1      | 1.03%   |
| WDC WD5000AADS-00S9B0 500GB                 | 1         | 1      | 1.03%   |
| WDC WD3200BEKX-75B7WT0 320GB                | 1         | 1      | 1.03%   |
| WDC WD3200BEKT-60PVMT0 320GB                | 1         | 1      | 1.03%   |
| WDC WD20EFRX-68AX9N0 2TB                    | 1         | 6      | 1.03%   |
| WDC WD15EADS-00P8B0 1TB                     | 1         | 1      | 1.03%   |
| WDC WD10SPZX-22Z10T0 1TB                    | 1         | 1      | 1.03%   |
| WDC WD10JPVX-60JC3T1 1TB                    | 1         | 1      | 1.03%   |
| WDC WD10EZEX-60WN4A0 1TB                    | 1         | 1      | 1.03%   |
| WDC WD10EARS-00MVWB0 1TB                    | 1         | 1      | 1.03%   |
| WDC WD1002FAEX-00Z3A0 1TB                   | 1         | 1      | 1.03%   |
| WDC WD1001FALS-00E8B0 1TB                   | 1         | 1      | 1.03%   |
| WDC PC SN520 SDAPMUW-128G-1001 128GB        | 1         | 1      | 1.03%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD    | 1         | 1      | 1.03%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD    | 1         | 1      | 1.03%   |
| Toshiba MQ04ABF100 1TB                      | 1         | 1      | 1.03%   |
| Toshiba MQ01ACF050 500GB                    | 1         | 1      | 1.03%   |
| Toshiba MK7559GSXP 752GB                    | 1         | 1      | 1.03%   |
| Toshiba MK3252GSX 320GB                     | 1         | 1      | 1.03%   |
| Toshiba MK1655GSX 160GB                     | 1         | 1      | 1.03%   |
| Team TM8FP4004T 4TB                         | 1         | 1      | 1.03%   |
| Team T253X1120G 120GB SSD                   | 1         | 1      | 1.03%   |
| SK hynix PC711 HFS512GDE9X073N 512GB        | 1         | 1      | 1.03%   |
| SK hynix HFS512G39TND-N210A 512GB SSD       | 1         | 1      | 1.03%   |
| SK hynix HFS128G39TND-N210A 128GB SSD       | 1         | 1      | 1.03%   |
| SK hynix BC501 NVMe Solid State Drive 512GB | 1         | 1      | 1.03%   |
| Seagate STM3500418AS 500GB                  | 1         | 1      | 1.03%   |
| Seagate ST9320325AS 320GB                   | 1         | 1      | 1.03%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 20        | 25     | 21.28%  |
| Seagate             | 19        | 23     | 20.21%  |
| Samsung Electronics | 10        | 11     | 10.64%  |
| Toshiba             | 7         | 7      | 7.45%   |
| SK hynix            | 7         | 7      | 7.45%   |
| HGST                | 7         | 8      | 7.45%   |
| Kingston            | 3         | 4      | 3.19%   |
| Intel               | 3         | 3      | 3.19%   |
| Hitachi             | 3         | 5      | 3.19%   |
| Team                | 2         | 2      | 2.13%   |
| Micron Technology   | 2         | 4      | 2.13%   |
| Crucial             | 2         | 2      | 2.13%   |
| A-DATA Technology   | 2         | 2      | 2.13%   |
| SanDisk             | 1         | 1      | 1.06%   |
| SABRENT             | 1         | 1      | 1.06%   |
| Plextor             | 1         | 1      | 1.06%   |
| Lexar               | 1         | 1      | 1.06%   |
| Leven               | 1         | 1      | 1.06%   |
| China               | 1         | 1      | 1.06%   |
| BAITITON            | 1         | 1      | 1.06%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 23     | 35.85%  |
| WDC                 | 16        | 21     | 30.19%  |
| HGST                | 7         | 8      | 13.21%  |
| Toshiba             | 5         | 5      | 9.43%   |
| Hitachi             | 3         | 5      | 5.66%   |
| Samsung Electronics | 2         | 2      | 3.77%   |
| SABRENT             | 1         | 1      | 1.89%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 51        | 65     | 55.43%  |
| SSD  | 27        | 29     | 29.35%  |
| NVMe | 14        | 16     | 15.22%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 1         | 1      | 25%     |
| Samsung Electronics HM321HI 320GB | 1         | 1      | 25%     |
| KingDian S400 120GB               | 1         | 2      | 25%     |
| Intenso JAJP600M1TB               | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1         | 1      | 25%     |
| Samsung Electronics | 1         | 1      | 25%     |
| KingDian            | 1         | 2      | 25%     |
| Intenso             | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2604      | 5252   | 73.1%   |
| Works    | 864       | 1389   | 24.26%  |
| Malfunc  | 90        | 110    | 2.53%   |
| Failed   | 4         | 5      | 0.11%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 1876      | 38.72%  |
| AMD                            | 830       | 17.13%  |
| Samsung Electronics            | 679       | 14.01%  |
| SanDisk                        | 329       | 6.79%   |
| SK hynix                       | 166       | 3.43%   |
| Phison Electronics             | 135       | 2.79%   |
| Kingston Technology Company    | 104       | 2.15%   |
| Micron Technology              | 100       | 2.06%   |
| Micron/Crucial Technology      | 97        | 2%      |
| ASMedia Technology             | 71        | 1.47%   |
| Toshiba America Info Systems   | 57        | 1.18%   |
| Silicon Motion                 | 53        | 1.09%   |
| KIOXIA                         | 53        | 1.09%   |
| Nvidia                         | 48        | 0.99%   |
| ADATA Technology               | 44        | 0.91%   |
| Marvell Technology Group       | 35        | 0.72%   |
| Realtek Semiconductor          | 25        | 0.52%   |
| Solid State Storage Technology | 24        | 0.5%    |
| JMicron Technology             | 17        | 0.35%   |
| Union Memory (Shenzhen)        | 16        | 0.33%   |
| Apple                          | 14        | 0.29%   |
| Seagate Technology             | 12        | 0.25%   |
| Shenzhen Longsys Electronics   | 8         | 0.17%   |
| MAXIO Technology (Hangzhou)    | 8         | 0.17%   |
| Broadcom / LSI                 | 8         | 0.17%   |
| LSI Logic / Symbios Logic      | 6         | 0.12%   |
| Lite-On Technology             | 5         | 0.1%    |
| INNOGRIT                       | 5         | 0.1%    |
| VIA Technologies               | 3         | 0.06%   |
| Solidigm                       | 3         | 0.06%   |
| Netac Technology               | 3         | 0.06%   |
| Hewlett-Packard                | 3         | 0.06%   |
| Silicon Image                  | 2         | 0.04%   |
| Yangtze Memory Technologies    | 1         | 0.02%   |
| Western Digital                | 1         | 0.02%   |
| Transcend                      | 1         | 0.02%   |
| O2 Micro                       | 1         | 0.02%   |
| Biwin Storage Technology       | 1         | 0.02%   |
| Adaptec                        | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 590       | 11.04%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 294       | 5.5%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 148       | 2.77%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 146       | 2.73%   |
| Intel Volume Management Device NVMe RAID Controller                            | 142       | 2.66%   |
| AMD 500 Series Chipset SATA Controller                                         | 141       | 2.64%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 133       | 2.49%   |
| Samsung NVMe SSD Controller 980                                                | 127       | 2.38%   |
| AMD 400 Series Chipset SATA Controller                                         | 118       | 2.21%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 106       | 1.98%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 99        | 1.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 94        | 1.76%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 85        | 1.59%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 73        | 1.37%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 67        | 1.25%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 66        | 1.23%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 65        | 1.22%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 64        | 1.2%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 60        | 1.12%   |
| Phison E12 NVMe Controller                                                     | 60        | 1.12%   |
| Intel Comet Lake SATA AHCI Controller                                          | 58        | 1.09%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 55        | 1.03%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 53        | 0.99%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 53        | 0.99%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 51        | 0.95%   |
| Intel SSD 660P Series                                                          | 50        | 0.94%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 46        | 0.86%   |
| Intel SATA Controller [RAID mode]                                              | 44        | 0.82%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 42        | 0.79%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 42        | 0.79%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 41        | 0.77%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 40        | 0.75%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 37        | 0.69%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 36        | 0.67%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 35        | 0.65%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 34        | 0.64%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 32        | 0.6%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 32        | 0.6%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 32        | 0.6%    |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 31        | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2376      | 50.81%  |
| NVMe | 1757      | 37.57%  |
| RAID | 336       | 7.19%   |
| IDE  | 191       | 4.08%   |
| SAS  | 15        | 0.32%   |
| SCSI | 1         | 0.02%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 2281      | 67.73%  |
| AMD    | 1083      | 32.16%  |
| ARM    | 4         | 0.12%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 50        | 1.48%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 47        | 1.39%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 40        | 1.19%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 39        | 1.16%   |
| AMD Ryzen 5 3600 6-Core Processor             | 38        | 1.13%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 36        | 1.07%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 35        | 1.04%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 35        | 1.04%   |
| Intel 12th Gen Core i7-12700H                 | 34        | 1.01%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 31        | 0.92%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 30        | 0.89%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 30        | 0.89%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 29        | 0.86%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 29        | 0.86%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 29        | 0.86%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 29        | 0.86%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 27        | 0.8%    |
| AMD Ryzen 5 5600G with Radeon Graphics        | 27        | 0.8%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 26        | 0.77%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 26        | 0.77%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 26        | 0.77%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 25        | 0.74%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 25        | 0.74%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 24        | 0.71%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 23        | 0.68%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 23        | 0.68%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 22        | 0.65%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 21        | 0.62%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 20        | 0.59%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 20        | 0.59%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 17        | 0.5%    |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 17        | 0.5%    |
| AMD Ryzen 7 PRO 5850U with Radeon Graphics    | 17        | 0.5%    |
| AMD Ryzen 7 2700X Eight-Core Processor        | 17        | 0.5%    |
| Intel Core i7-6700K CPU @ 4.00GHz             | 16        | 0.47%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 16        | 0.47%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 16        | 0.47%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 16        | 0.47%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 16        | 0.47%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 15        | 0.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 710       | 21.05%  |
| Intel Core i5           | 648       | 19.21%  |
| Other                   | 429       | 12.72%  |
| AMD Ryzen 7             | 340       | 10.08%  |
| AMD Ryzen 5             | 339       | 10.05%  |
| Intel Core i3           | 158       | 4.68%   |
| AMD Ryzen 9             | 139       | 4.12%   |
| Intel Celeron           | 83        | 2.46%   |
| Intel Core 2 Duo        | 78        | 2.31%   |
| Intel Xeon              | 68        | 2.02%   |
| AMD FX                  | 41        | 1.22%   |
| AMD Ryzen 3             | 36        | 1.07%   |
| Intel Pentium           | 31        | 0.92%   |
| Intel Core i9           | 30        | 0.89%   |
| AMD Ryzen 7 PRO         | 27        | 0.8%    |
| AMD A8                  | 22        | 0.65%   |
| AMD A10                 | 18        | 0.53%   |
| AMD A6                  | 14        | 0.42%   |
| AMD Ryzen Threadripper  | 12        | 0.36%   |
| Intel Pentium Dual-Core | 10        | 0.3%    |
| Intel Core 2 Quad       | 10        | 0.3%    |
| AMD Ryzen 5 PRO         | 10        | 0.3%    |
| AMD A4                  | 10        | 0.3%    |
| Intel Pentium Silver    | 9         | 0.27%   |
| AMD Athlon              | 8         | 0.24%   |
| Intel Pentium Gold      | 7         | 0.21%   |
| AMD Athlon II X2        | 7         | 0.21%   |
| Intel Atom              | 6         | 0.18%   |
| AMD Phenom II X4        | 6         | 0.18%   |
| AMD Athlon II X4        | 6         | 0.18%   |
| Intel Core m5           | 5         | 0.15%   |
| Intel Core 2            | 4         | 0.12%   |
| AMD Ryzen 3 PRO         | 4         | 0.12%   |
| AMD Phenom II X6        | 4         | 0.12%   |
| AMD E1                  | 4         | 0.12%   |
| AMD E                   | 4         | 0.12%   |
| Intel Pentium D         | 3         | 0.09%   |
| AMD Phenom              | 3         | 0.09%   |
| AMD Athlon X4           | 3         | 0.09%   |
| AMD Athlon X2           | 3         | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 1143      | 33.89%  |
| 2       | 858       | 25.44%  |
| 8       | 516       | 15.3%   |
| 6       | 490       | 14.53%  |
| 12      | 107       | 3.17%   |
| 16      | 81        | 2.4%    |
| 14      | 70        | 2.08%   |
| 10      | 55        | 1.63%   |
| 3       | 17        | 0.5%    |
| 1       | 15        | 0.44%   |
| 24      | 11        | 0.33%   |
| Unknown | 4         | 0.12%   |
| 32      | 2         | 0.06%   |
| 64      | 1         | 0.03%   |
| 40      | 1         | 0.03%   |
| 36      | 1         | 0.03%   |
| 18      | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3346      | 99.35%  |
| 2       | 18        | 0.53%   |
| Unknown | 4         | 0.12%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2775      | 82.32%  |
| 1       | 592       | 17.56%  |
| Unknown | 4         | 0.12%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3365      | 99.91%  |
| 64-bit         | 3         | 0.09%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2717      | 79.51%  |
| 0x806c1    | 50        | 1.46%   |
| 0x0a50000c | 43        | 1.26%   |
| 0x806ec    | 26        | 0.76%   |
| 0x906a3    | 24        | 0.7%    |
| 0x806ea    | 24        | 0.7%    |
| 0x806d1    | 24        | 0.7%    |
| 0x08701021 | 24        | 0.7%    |
| 0x08600106 | 23        | 0.67%   |
| 0x306a9    | 22        | 0.64%   |
| 0x08608103 | 22        | 0.64%   |
| 0x906ea    | 21        | 0.61%   |
| 0xa0652    | 20        | 0.59%   |
| 0x0a50000d | 17        | 0.5%    |
| 0x0a404102 | 17        | 0.5%    |
| 0x0a404101 | 16        | 0.47%   |
| 0x0a601203 | 15        | 0.44%   |
| 0x08108109 | 15        | 0.44%   |
| 0x506e3    | 14        | 0.41%   |
| 0x406e3    | 14        | 0.41%   |
| 0x206a7    | 14        | 0.41%   |
| 0x0a201016 | 14        | 0.41%   |
| 0x806e9    | 13        | 0.38%   |
| 0x306c3    | 13        | 0.38%   |
| 0x0800820d | 13        | 0.38%   |
| 0x906a4    | 12        | 0.35%   |
| 0x40651    | 12        | 0.35%   |
| 0x906e9    | 11        | 0.32%   |
| 0x08600104 | 10        | 0.29%   |
| 0x306d4    | 9         | 0.26%   |
| 0x706e5    | 8         | 0.23%   |
| 0x1067a    | 8         | 0.23%   |
| 0x706a8    | 7         | 0.2%    |
| 0x0a20120a | 7         | 0.2%    |
| 0x08600103 | 6         | 0.18%   |
| 0x906ec    | 5         | 0.15%   |
| 0x90672    | 5         | 0.15%   |
| 0x806eb    | 5         | 0.15%   |
| 0x0a201205 | 5         | 0.15%   |
| 0x08701013 | 5         | 0.15%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 528       | 15.64%  |
| Unknown          | 355       | 10.52%  |
| Zen 3            | 320       | 9.48%   |
| Haswell          | 298       | 8.83%   |
| Zen 2            | 202       | 5.98%   |
| SandyBridge      | 179       | 5.3%    |
| Skylake          | 168       | 4.98%   |
| IvyBridge        | 166       | 4.92%   |
| TigerLake        | 148       | 4.38%   |
| Zen+             | 141       | 4.18%   |
| CometLake        | 110       | 3.26%   |
| Broadwell        | 96        | 2.84%   |
| Penryn           | 89        | 2.64%   |
| Alderlake Hybrid | 82        | 2.43%   |
| Zen              | 72        | 2.13%   |
| Icelake          | 62        | 1.84%   |
| Westmere         | 57        | 1.69%   |
| Piledriver       | 57        | 1.69%   |
| Goldmont plus    | 40        | 1.18%   |
| Silvermont       | 32        | 0.95%   |
| K10              | 31        | 0.92%   |
| Nehalem          | 28        | 0.83%   |
| Excavator        | 25        | 0.74%   |
| Core             | 19        | 0.56%   |
| Puma             | 16        | 0.47%   |
| Steamroller      | 14        | 0.41%   |
| Goldmont         | 9         | 0.27%   |
| K10 Llano        | 7         | 0.21%   |
| Jaguar           | 5         | 0.15%   |
| Bobcat           | 5         | 0.15%   |
| Tremont          | 4         | 0.12%   |
| K8 Hammer        | 4         | 0.12%   |
| NetBurst         | 3         | 0.09%   |
| Bulldozer        | 3         | 0.09%   |
| K8 & K10 hybrid  | 1         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 1759      | 42.25%  |
| Nvidia                     | 1346      | 32.33%  |
| AMD                        | 1053      | 25.29%  |
| Matrox Electronics Systems | 4         | 0.1%    |
| ASPEED Technology          | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 134       | 3.14%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 130       | 3.05%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 128       | 3%      |
| Intel UHD Graphics 620                                                      | 98        | 2.3%    |
| Intel 3rd Gen Core processor Graphics Controller                            | 95        | 2.23%   |
| Intel Alder Lake-P Integrated Graphics Controller                           | 89        | 2.09%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 88        | 2.06%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 84        | 1.97%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 83        | 1.95%   |
| AMD Renoir                                                                  | 81        | 1.9%    |
| AMD Lucienne                                                                | 69        | 1.62%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 68        | 1.59%   |
| Intel HD Graphics 620                                                       | 65        | 1.52%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 62        | 1.45%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 60        | 1.41%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 59        | 1.38%   |
| AMD Rembrandt [Radeon 680M]                                                 | 59        | 1.38%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 58        | 1.36%   |
| Intel HD Graphics 5500                                                      | 57        | 1.34%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 56        | 1.31%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 53        | 1.24%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 50        | 1.17%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                  | 46        | 1.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 46        | 1.08%   |
| Intel HD Graphics 530                                                       | 42        | 0.98%   |
| Intel HD Graphics 630                                                       | 38        | 0.89%   |
| AMD Raphael                                                                 | 37        | 0.87%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 36        | 0.84%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 36        | 0.84%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 36        | 0.84%   |
| Intel Core Processor Integrated Graphics Controller                         | 36        | 0.84%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 34        | 0.8%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 32        | 0.75%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 31        | 0.73%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 28        | 0.66%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 27        | 0.63%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 27        | 0.63%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 25        | 0.59%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                 | 25        | 0.59%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 24        | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| 1 x Intel            | 1143      | 33.68%  |
| 1 x AMD              | 751       | 22.13%  |
| 1 x Nvidia           | 671       | 19.77%  |
| Intel + Nvidia       | 493       | 14.53%  |
| AMD + Nvidia         | 162       | 4.77%   |
| Intel + AMD          | 74        | 2.18%   |
| 2 x AMD              | 68        | 2%      |
| 2 x Nvidia           | 13        | 0.38%   |
| Other                | 8         | 0.24%   |
| 1 x Matrox           | 4         | 0.12%   |
| Intel + 2 x Nvidia   | 3         | 0.09%   |
| 2 x Intel            | 1         | 0.03%   |
| 2 x AMD + 1 x Nvidia | 1         | 0.03%   |
| Nvidia + ASPEED      | 1         | 0.03%   |
| AMD + 2 x Nvidia     | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2230      | 65.61%  |
| Proprietary | 1087      | 31.98%  |
| Unknown     | 82        | 2.41%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2759      | 80.72%  |
| 7.01-8.0   | 130       | 3.8%    |
| 0.01-0.5   | 120       | 3.51%   |
| 1.01-2.0   | 116       | 3.39%   |
| 3.01-4.0   | 98        | 2.87%   |
| 5.01-6.0   | 75        | 2.19%   |
| 8.01-16.0  | 68        | 1.99%   |
| 0.51-1.0   | 28        | 0.82%   |
| 2.01-3.0   | 14        | 0.41%   |
| 16.01-24.0 | 9         | 0.26%   |
| 32.01-64.0 | 1         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 452       | 11.61%  |
| Samsung Electronics     | 421       | 10.81%  |
| BOE                     | 381       | 9.78%   |
| Chimei Innolux          | 356       | 9.14%   |
| LG Display              | 300       | 7.7%    |
| Goldstar                | 251       | 6.45%   |
| Dell                    | 235       | 6.03%   |
| Apple                   | 143       | 3.67%   |
| Acer                    | 130       | 3.34%   |
| Hewlett-Packard         | 115       | 2.95%   |
| AOC                     | 101       | 2.59%   |
| Sharp                   | 96        | 2.47%   |
| ASUSTek Computer        | 83        | 2.13%   |
| BenQ                    | 71        | 1.82%   |
| Ancor Communications    | 71        | 1.82%   |
| Lenovo                  | 62        | 1.59%   |
| PANDA                   | 57        | 1.46%   |
| Philips                 | 53        | 1.36%   |
| InfoVision              | 33        | 0.85%   |
| MSI                     | 31        | 0.8%    |
| Iiyama                  | 31        | 0.8%    |
| CSO                     | 25        | 0.64%   |
| Chi Mei Optoelectronics | 25        | 0.64%   |
| ViewSonic               | 24        | 0.62%   |
| Gigabyte Technology     | 19        | 0.49%   |
| Sceptre Tech            | 18        | 0.46%   |
| Sony                    | 17        | 0.44%   |
| NEC Computers           | 17        | 0.44%   |
| Panasonic               | 14        | 0.36%   |
| Vizio                   | 12        | 0.31%   |
| Toshiba                 | 9         | 0.23%   |
| TMX                     | 9         | 0.23%   |
| Vestel Elektronik       | 8         | 0.21%   |
| Unknown                 | 8         | 0.21%   |
| HKC                     | 8         | 0.21%   |
| Insignia                | 6         | 0.15%   |
| Hitachi                 | 6         | 0.15%   |
| Eizo                    | 6         | 0.15%   |
| RTK                     | 5         | 0.13%   |
| Pioneer                 | 5         | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 24        | 0.6%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 23        | 0.57%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 21        | 0.52%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 21        | 0.52%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 19        | 0.47%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 18        | 0.45%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 17        | 0.42%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 16        | 0.4%    |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 13        | 0.32%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 12        | 0.3%    |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                  | 12        | 0.3%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 11        | 0.27%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 10        | 0.25%   |
| InfoVision LCD Monitor IVO8C78 1920x1080 309x174mm 14.0-inch          | 10        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 10        | 0.25%   |
| Chimei Innolux LCD Monitor CMN1408 1920x1080 309x173mm 13.9-inch      | 10        | 0.25%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 10        | 0.25%   |
| AOC 27B2 AOC2702 1920x1080 598x336mm 27.0-inch                        | 10        | 0.25%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 9         | 0.22%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 9         | 0.22%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 9         | 0.22%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch    | 8         | 0.2%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 8         | 0.2%    |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 8         | 0.2%    |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 8         | 0.2%    |
| Dell P2317H DEL40F4 1920x1080 509x286mm 23.0-inch                     | 8         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 8         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 8         | 0.2%    |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch         | 8         | 0.2%    |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                  | 8         | 0.2%    |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch     | 7         | 0.17%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 7         | 0.17%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 7         | 0.17%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x173mm 12.3-inch          | 7         | 0.17%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 7         | 0.17%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 7         | 0.17%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 7         | 0.17%   |
| Chimei Innolux LCD Monitor CMN1512 1920x1080 344x193mm 15.5-inch      | 7         | 0.17%   |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                 | 7         | 0.17%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 7         | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1738      | 47.07%  |
| 1366x768 (WXGA)    | 493       | 13.35%  |
| 3840x2160 (4K)     | 338       | 9.15%   |
| 2560x1440 (QHD)    | 264       | 7.15%   |
| 1920x1200 (WUXGA)  | 107       | 2.9%    |
| 1600x900 (HD+)     | 94        | 2.55%   |
| 3440x1440          | 83        | 2.25%   |
| 2560x1080          | 67        | 1.81%   |
| 2560x1600          | 65        | 1.76%   |
| 1440x900 (WXGA+)   | 61        | 1.65%   |
| 1680x1050 (WSXGA+) | 51        | 1.38%   |
| 2880x1800          | 48        | 1.3%    |
| 1280x1024 (SXGA)   | 44        | 1.19%   |
| 1280x800 (WXGA)    | 43        | 1.16%   |
| 3840x1080          | 22        | 0.6%    |
| 1360x768           | 20        | 0.54%   |
| 3840x2400          | 17        | 0.46%   |
| 1920x540           | 13        | 0.35%   |
| 2160x1440          | 12        | 0.33%   |
| 3072x1920          | 10        | 0.27%   |
| 2736x1824          | 9         | 0.24%   |
| 2256x1504          | 9         | 0.24%   |
| 3840x1600          | 8         | 0.22%   |
| Unknown            | 8         | 0.22%   |
| 3200x1800 (QHD+)   | 7         | 0.19%   |
| 1920x1280          | 7         | 0.19%   |
| 1024x768 (XGA)     | 6         | 0.16%   |
| 3200x2000          | 5         | 0.14%   |
| 1600x1200          | 5         | 0.14%   |
| 3456x2160          | 4         | 0.11%   |
| 1280x720 (HD)      | 4         | 0.11%   |
| 3840x1100          | 3         | 0.08%   |
| 3000x2000          | 3         | 0.08%   |
| 2240x1400          | 3         | 0.08%   |
| 800x1280           | 2         | 0.05%   |
| 4480x1440          | 2         | 0.05%   |
| 2880x1620          | 2         | 0.05%   |
| 2304x1440          | 2         | 0.05%   |
| 5120x1440          | 1         | 0.03%   |
| 3840x1200          | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 972       | 24.94%  |
| 13      | 431       | 11.06%  |
| 27      | 366       | 9.39%   |
| 14      | 303       | 7.77%   |
| 24      | 301       | 7.72%   |
| 23      | 212       | 5.44%   |
| 17      | 178       | 4.57%   |
| 21      | 162       | 4.16%   |
| 31      | 158       | 4.05%   |
| 34      | 132       | 3.39%   |
| 16      | 69        | 1.77%   |
| 12      | 63        | 1.62%   |
| 19      | 58        | 1.49%   |
| Unknown | 57        | 1.46%   |
| 84      | 41        | 1.05%   |
| 32      | 40        | 1.03%   |
| 18      | 39        | 1%      |
| 22      | 37        | 0.95%   |
| 20      | 32        | 0.82%   |
| 11      | 28        | 0.72%   |
| 72      | 26        | 0.67%   |
| 48      | 22        | 0.56%   |
| 40      | 19        | 0.49%   |
| 28      | 18        | 0.46%   |
| 54      | 16        | 0.41%   |
| 26      | 12        | 0.31%   |
| 37      | 11        | 0.28%   |
| 25      | 11        | 0.28%   |
| 35      | 9         | 0.23%   |
| 29      | 9         | 0.23%   |
| 65      | 7         | 0.18%   |
| 33      | 7         | 0.18%   |
| 52      | 6         | 0.15%   |
| 49      | 6         | 0.15%   |
| 46      | 5         | 0.13%   |
| 36      | 4         | 0.1%    |
| 74      | 3         | 0.08%   |
| 57      | 3         | 0.08%   |
| 44      | 3         | 0.08%   |
| 42      | 3         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 1540      | 40.5%   |
| 501-600     | 788       | 20.73%  |
| 201-300     | 323       | 8.5%    |
| 401-500     | 294       | 7.73%   |
| 601-700     | 224       | 5.89%   |
| 351-400     | 200       | 5.26%   |
| 701-800     | 178       | 4.68%   |
| 1501-2000   | 75        | 1.97%   |
| 1001-1500   | 71        | 1.87%   |
| Unknown     | 57        | 1.5%    |
| 801-900     | 44        | 1.16%   |
| 901-1000    | 5         | 0.13%   |
| 1-100       | 2         | 0.05%   |
| 101-200     | 1         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2686      | 77.79%  |
| 16/10   | 441       | 12.77%  |
| 21/9    | 159       | 4.6%    |
| 5/4     | 46        | 1.33%   |
| 3/2     | 42        | 1.22%   |
| 32/9    | 26        | 0.75%   |
| Unknown | 25        | 0.72%   |
| 4/3     | 18        | 0.52%   |
| 3.40    | 3         | 0.09%   |
| 6/5     | 2         | 0.06%   |
| 3.73    | 1         | 0.03%   |
| 3.20    | 1         | 0.03%   |
| 0.67    | 1         | 0.03%   |
| 0.63    | 1         | 0.03%   |
| 0.56    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 971       | 25.2%   |
| 81-90          | 561       | 14.56%  |
| 201-250        | 552       | 14.33%  |
| 301-350        | 380       | 9.86%   |
| 351-500        | 354       | 9.19%   |
| 71-80          | 173       | 4.49%   |
| 121-130        | 141       | 3.66%   |
| 151-200        | 131       | 3.4%    |
| More than 1000 | 114       | 2.96%   |
| 251-300        | 109       | 2.83%   |
| 501-1000       | 71        | 1.84%   |
| 111-120        | 67        | 1.74%   |
| 141-150        | 62        | 1.61%   |
| Unknown        | 57        | 1.48%   |
| 61-70          | 50        | 1.3%    |
| 51-60          | 31        | 0.8%    |
| 131-140        | 14        | 0.36%   |
| 91-100         | 12        | 0.31%   |
| 1-40           | 3         | 0.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 1192      | 32.01%  |
| 51-100        | 1088      | 29.22%  |
| 101-120       | 843       | 22.64%  |
| 161-240       | 330       | 8.86%   |
| More than 240 | 129       | 3.46%   |
| 1-50          | 85        | 2.28%   |
| Unknown       | 57        | 1.53%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 2601      | 75.92%  |
| 2     | 617       | 18.01%  |
| 0     | 105       | 3.06%   |
| 3     | 95        | 2.77%   |
| 4     | 7         | 0.2%    |
| 6     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1820      | 35.39%  |
| Intel                             | 1765      | 34.32%  |
| Qualcomm Atheros                  | 463       | 9%      |
| Broadcom                          | 279       | 5.42%   |
| MediaTek                          | 177       | 3.44%   |
| Broadcom Limited                  | 80        | 1.56%   |
| TP-Link                           | 54        | 1.05%   |
| ASIX Electronics                  | 43        | 0.84%   |
| Marvell Technology Group          | 39        | 0.76%   |
| Nvidia                            | 33        | 0.64%   |
| Samsung Electronics               | 32        | 0.62%   |
| Ralink Technology                 | 32        | 0.62%   |
| Ralink                            | 29        | 0.56%   |
| NetGear                           | 22        | 0.43%   |
| Xiaomi                            | 20        | 0.39%   |
| DisplayLink                       | 19        | 0.37%   |
| Aquantia                          | 18        | 0.35%   |
| Dell                              | 16        | 0.31%   |
| Qualcomm                          | 14        | 0.27%   |
| Microsoft                         | 13        | 0.25%   |
| InterBiometrics                   | 12        | 0.23%   |
| Sierra Wireless                   | 11        | 0.21%   |
| Lenovo                            | 11        | 0.21%   |
| Google                            | 11        | 0.21%   |
| Linksys                           | 9         | 0.17%   |
| D-Link                            | 9         | 0.17%   |
| OPPO Electronics                  | 8         | 0.16%   |
| JMicron Technology                | 8         | 0.16%   |
| ASUSTek Computer                  | 8         | 0.16%   |
| Qualcomm Atheros Communications   | 7         | 0.14%   |
| Hewlett-Packard                   | 7         | 0.14%   |
| D-Link System                     | 7         | 0.14%   |
| OnePlus Technology (Shenzhen)     | 6         | 0.12%   |
| Huawei Technologies               | 6         | 0.12%   |
| Motorola PCS                      | 4         | 0.08%   |
| Mellanox Technologies             | 4         | 0.08%   |
| Ericsson Business Mobile Networks | 4         | 0.08%   |
| Edimax Technology                 | 4         | 0.08%   |
| Fibocom                           | 3         | 0.06%   |
| Apple                             | 3         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1157      | 19.01%  |
| Intel Wi-Fi 6 AX200                                               | 269       | 4.42%   |
| Realtek RTL8125 2.5GbE Controller                                 | 179       | 2.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 138       | 2.27%   |
| Intel I211 Gigabit Network Connection                             | 134       | 2.2%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 123       | 2.02%   |
| Intel Wireless 8265 / 8275                                        | 118       | 1.94%   |
| Intel Wi-Fi 6 AX201                                               | 117       | 1.92%   |
| Intel Ethernet Controller I225-V                                  | 114       | 1.87%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 106       | 1.74%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 83        | 1.36%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 79        | 1.3%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 78        | 1.28%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 74        | 1.22%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 74        | 1.22%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 66        | 1.08%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 66        | 1.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 65        | 1.07%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 65        | 1.07%   |
| Intel Wireless 7265                                               | 62        | 1.02%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 61        | 1%      |
| Intel Ethernet Connection I217-LM                                 | 57        | 0.94%   |
| Intel Wireless 8260                                               | 56        | 0.92%   |
| Intel Wireless 7260                                               | 55        | 0.9%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 53        | 0.87%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 53        | 0.87%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 52        | 0.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 50        | 0.82%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 48        | 0.79%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 47        | 0.77%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 43        | 0.71%   |
| Intel Ethernet Connection (2) I219-V                              | 41        | 0.67%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 39        | 0.64%   |
| Intel Wireless-AC 9260                                            | 39        | 0.64%   |
| Realtek 802.11ac NIC                                              | 38        | 0.62%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 36        | 0.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 36        | 0.59%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 36        | 0.59%   |
| Intel Ethernet Connection (4) I219-LM                             | 34        | 0.56%   |
| ASIX AX88179 Gigabit Ethernet                                     | 34        | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1439      | 48.13%  |
| Realtek Semiconductor                 | 463       | 15.48%  |
| Qualcomm Atheros                      | 370       | 12.37%  |
| Broadcom                              | 220       | 7.36%   |
| MediaTek                              | 176       | 5.89%   |
| Broadcom Limited                      | 68        | 2.27%   |
| TP-Link                               | 46        | 1.54%   |
| Ralink Technology                     | 32        | 1.07%   |
| Ralink                                | 29        | 0.97%   |
| NetGear                               | 22        | 0.74%   |
| Marvell Technology Group              | 14        | 0.47%   |
| Dell                                  | 14        | 0.47%   |
| Microsoft                             | 13        | 0.43%   |
| Qualcomm                              | 12        | 0.4%    |
| Sierra Wireless                       | 11        | 0.37%   |
| Linksys                               | 9         | 0.3%    |
| D-Link                                | 8         | 0.27%   |
| Qualcomm Atheros Communications       | 7         | 0.23%   |
| ASUSTek Computer                      | 7         | 0.23%   |
| D-Link System                         | 6         | 0.2%    |
| Hewlett-Packard                       | 4         | 0.13%   |
| Edimax Technology                     | 4         | 0.13%   |
| Fibocom                               | 3         | 0.1%    |
| Belkin Components                     | 2         | 0.07%   |
| Accton Technology                     | 2         | 0.07%   |
| ZyDAS                                 | 1         | 0.03%   |
| Wacom                                 | 1         | 0.03%   |
| Sitecom Europe                        | 1         | 0.03%   |
| Micro Star International              | 1         | 0.03%   |
| IMC Networks                          | 1         | 0.03%   |
| Gemtek                                | 1         | 0.03%   |
| AVM                                   | 1         | 0.03%   |
| Arduino SA                            | 1         | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 269       | 8.94%   |
| Intel Wireless 8265 / 8275                                     | 118       | 3.92%   |
| Intel Wi-Fi 6 AX201                                            | 117       | 3.89%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 104       | 3.46%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 79        | 2.62%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 78        | 2.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 74        | 2.46%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 74        | 2.46%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 66        | 2.19%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 66        | 2.19%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 65        | 2.16%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 65        | 2.16%   |
| Intel Wireless 7265                                            | 62        | 2.06%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 61        | 2.03%   |
| Intel Wireless 8260                                            | 56        | 1.86%   |
| Intel Wireless 7260                                            | 55        | 1.83%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 53        | 1.76%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 53        | 1.76%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 52        | 1.73%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 50        | 1.66%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 48        | 1.59%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 47        | 1.56%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 43        | 1.43%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 39        | 1.3%    |
| Intel Wireless-AC 9260                                         | 39        | 1.3%    |
| Realtek 802.11ac NIC                                           | 38        | 1.26%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 36        | 1.2%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 36        | 1.2%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 36        | 1.2%    |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 33        | 1.1%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 29        | 0.96%   |
| Broadcom BCM43142 802.11b/g/n                                  | 26        | 0.86%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 25        | 0.83%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 25        | 0.83%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 24        | 0.8%    |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 23        | 0.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 23        | 0.76%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 22        | 0.73%   |
| Intel Wireless 3165                                            | 22        | 0.73%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 18        | 0.6%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 1611      | 54.37%  |
| Intel                         | 821       | 27.71%  |
| Qualcomm Atheros              | 133       | 4.49%   |
| Broadcom                      | 118       | 3.98%   |
| ASIX Electronics              | 43        | 1.45%   |
| Nvidia                        | 33        | 1.11%   |
| Samsung Electronics           | 32        | 1.08%   |
| Marvell Technology Group      | 25        | 0.84%   |
| Xiaomi                        | 20        | 0.67%   |
| DisplayLink                   | 19        | 0.64%   |
| Aquantia                      | 18        | 0.61%   |
| Broadcom Limited              | 12        | 0.4%    |
| Lenovo                        | 11        | 0.37%   |
| Google                        | 11        | 0.37%   |
| TP-Link                       | 8         | 0.27%   |
| OPPO Electronics              | 8         | 0.27%   |
| JMicron Technology            | 8         | 0.27%   |
| OnePlus Technology (Shenzhen) | 5         | 0.17%   |
| Huawei Technologies           | 5         | 0.17%   |
| Motorola PCS                  | 3         | 0.1%    |
| Mellanox Technologies         | 3         | 0.1%    |
| Qualcomm                      | 2         | 0.07%   |
| ICS Advent                    | 2         | 0.07%   |
| Hewlett-Packard               | 2         | 0.07%   |
| Apple                         | 2         | 0.07%   |
| ZTE WCDMA Technologies MSM    | 1         | 0.03%   |
| VIA Technologies              | 1         | 0.03%   |
| T & A Mobile Phones           | 1         | 0.03%   |
| Insyde Software               | 1         | 0.03%   |
| D-Link System                 | 1         | 0.03%   |
| D-Link                        | 1         | 0.03%   |
| ASUSTek Computer              | 1         | 0.03%   |
| American Megatrends           | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1157      | 38.11%  |
| Realtek RTL8125 2.5GbE Controller                                 | 179       | 5.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 138       | 4.55%   |
| Intel I211 Gigabit Network Connection                             | 134       | 4.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 123       | 4.05%   |
| Intel Ethernet Controller I225-V                                  | 114       | 3.75%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 83        | 2.73%   |
| Intel Ethernet Connection I217-LM                                 | 57        | 1.88%   |
| Intel Ethernet Connection (2) I219-V                              | 41        | 1.35%   |
| Intel Ethernet Connection (4) I219-LM                             | 34        | 1.12%   |
| ASIX AX88179 Gigabit Ethernet                                     | 34        | 1.12%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 30        | 0.99%   |
| Intel Ethernet Connection (7) I219-V                              | 25        | 0.82%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 24        | 0.79%   |
| Intel Ethernet Connection I219-LM                                 | 24        | 0.79%   |
| Nvidia MCP79 Ethernet                                             | 23        | 0.76%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 23        | 0.76%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 22        | 0.72%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 21        | 0.69%   |
| Intel Ethernet Connection (2) I219-LM                             | 21        | 0.69%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 20        | 0.66%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 20        | 0.66%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 18        | 0.59%   |
| Intel Ethernet Connection I217-V                                  | 18        | 0.59%   |
| Intel Ethernet Connection (3) I218-LM                             | 18        | 0.59%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 16        | 0.53%   |
| Intel Ethernet Connection (4) I219-V                              | 16        | 0.53%   |
| Intel Ethernet Connection (2) I218-V                              | 16        | 0.53%   |
| Intel I210 Gigabit Network Connection                             | 15        | 0.49%   |
| Intel Ethernet Connection I218-LM                                 | 15        | 0.49%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 14        | 0.46%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 12        | 0.4%    |
| Realtek Killer E3000 2.5GbE Controller                            | 12        | 0.4%    |
| Intel Ethernet Connection (7) I219-LM                             | 12        | 0.4%    |
| Intel Ethernet Connection (6) I219-V                              | 12        | 0.4%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 11        | 0.36%   |
| Intel Ethernet Connection (13) I219-V                             | 11        | 0.36%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 10        | 0.33%   |
| Intel 82579V Gigabit Network Connection                           | 10        | 0.33%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 9         | 0.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2835      | 50.37%  |
| Ethernet | 2752      | 48.9%   |
| Modem    | 29        | 0.52%   |
| Unknown  | 12        | 0.21%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2211      | 61.88%  |
| Ethernet | 1362      | 38.12%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1890      | 56.03%  |
| 1     | 1341      | 39.76%  |
| 3     | 96        | 2.85%   |
| 0     | 36        | 1.07%   |
| 4     | 8         | 0.24%   |
| 5     | 2         | 0.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2373      | 69.55%  |
| Yes  | 1039      | 30.45%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1288      | 52.27%  |
| Realtek Semiconductor           | 235       | 9.54%   |
| Apple                           | 172       | 6.98%   |
| Qualcomm Atheros Communications | 167       | 6.78%   |
| IMC Networks                    | 110       | 4.46%   |
| Foxconn / Hon Hai               | 94        | 3.81%   |
| Cambridge Silicon Radio         | 94        | 3.81%   |
| Lite-On Technology              | 65        | 2.64%   |
| Broadcom                        | 52        | 2.11%   |
| MediaTek                        | 43        | 1.75%   |
| ASUSTek Computer                | 28        | 1.14%   |
| Dell                            | 15        | 0.61%   |
| Realtek                         | 14        | 0.57%   |
| Marvell Semiconductor           | 14        | 0.57%   |
| TP-Link                         | 11        | 0.45%   |
| Toshiba                         | 11        | 0.45%   |
| Hewlett-Packard                 | 8         | 0.32%   |
| Ralink                          | 6         | 0.24%   |
| Dynex                           | 6         | 0.24%   |
| Actions                         | 4         | 0.16%   |
| Opticis                         | 3         | 0.12%   |
| Micro Star International        | 3         | 0.12%   |
| Integrated System Solution      | 3         | 0.12%   |
| Foxconn International           | 3         | 0.12%   |
| Taiyo Yuden                     | 2         | 0.08%   |
| Smart Modular Technologies      | 2         | 0.08%   |
| Ralink Technology               | 2         | 0.08%   |
| Fujitsu                         | 2         | 0.08%   |
| Edimax Technology               | 2         | 0.08%   |
| USI                             | 1         | 0.04%   |
| SINO WEALTH                     | 1         | 0.04%   |
| Logitech                        | 1         | 0.04%   |
| HTC (High Tech Computer)        | 1         | 0.04%   |
| Belkin Components               | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 311       | 12.61%  |
| Intel AX201 Bluetooth                               | 294       | 11.92%  |
| Intel AX200 Bluetooth                               | 253       | 10.26%  |
| Realtek Bluetooth Radio                             | 169       | 6.85%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 147       | 5.96%   |
| Intel Bluetooth Device                              | 103       | 4.18%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 94        | 3.81%   |
| Qualcomm Atheros  Bluetooth Device                  | 92        | 3.73%   |
| Apple Bluetooth Host Controller                     | 88        | 3.57%   |
| Intel AX210 Bluetooth                               | 59        | 2.39%   |
| Intel Wireless-AC 3168 Bluetooth                    | 50        | 2.03%   |
| Apple Bluetooth USB Host Controller                 | 50        | 2.03%   |
| Realtek  Bluetooth 4.2 Adapter                      | 49        | 1.99%   |
| IMC Networks Wireless_Device                        | 48        | 1.95%   |
| MediaTek Wireless_Device                            | 43        | 1.74%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 35        | 1.42%   |
| Foxconn / Hon Hai Wireless_Device                   | 31        | 1.26%   |
| Foxconn / Hon Hai Bluetooth Device                  | 26        | 1.05%   |
| IMC Networks Bluetooth Radio                        | 25        | 1.01%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 23        | 0.93%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 23        | 0.93%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 23        | 0.93%   |
| IMC Networks Bluetooth Device                       | 20        | 0.81%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 18        | 0.73%   |
| Lite-On Wireless_Device                             | 15        | 0.61%   |
| Realtek Bluetooth Radio                             | 14        | 0.57%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 14        | 0.57%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 14        | 0.57%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 13        | 0.53%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 13        | 0.53%   |
| Lite-On Bluetooth Device                            | 12        | 0.49%   |
| TP-Link UB5A Adapter                                | 11        | 0.45%   |
| Marvell Bluetooth and Wireless LAN Composite        | 11        | 0.45%   |
| Apple Bluetooth HCI                                 | 11        | 0.45%   |
| Lite-On Bluetooth Radio                             | 10        | 0.41%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 9         | 0.36%   |
| Lite-On Atheros AR3012 Bluetooth                    | 9         | 0.36%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 9         | 0.36%   |
| ASUS ASUS USB-BT500                                 | 9         | 0.36%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 8         | 0.32%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 2210      | 42.08%  |
| AMD                                  | 1237      | 23.55%  |
| Nvidia                               | 1077      | 20.51%  |
| C-Media Electronics                  | 89        | 1.69%   |
| Logitech                             | 60        | 1.14%   |
| Kingston Technology                  | 40        | 0.76%   |
| Razer USA                            | 29        | 0.55%   |
| Focusrite-Novation                   | 29        | 0.55%   |
| JMTek                                | 28        | 0.53%   |
| ASUSTek Computer                     | 28        | 0.53%   |
| Generalplus Technology               | 25        | 0.48%   |
| Creative Labs                        | 23        | 0.44%   |
| SteelSeries ApS                      | 22        | 0.42%   |
| Micro Star International             | 22        | 0.42%   |
| GN Netcom                            | 20        | 0.38%   |
| Lenovo                               | 18        | 0.34%   |
| Texas Instruments                    | 17        | 0.32%   |
| Corsair                              | 16        | 0.3%    |
| Realtek Semiconductor                | 15        | 0.29%   |
| Creative Technology                  | 13        | 0.25%   |
| Sony                                 | 12        | 0.23%   |
| Apple                                | 12        | 0.23%   |
| Hewlett-Packard                      | 10        | 0.19%   |
| Blue Microphones                     | 10        | 0.19%   |
| Plantronics                          | 9         | 0.17%   |
| DSEA A/S                             | 8         | 0.15%   |
| FiiO Electronics Technology          | 5         | 0.1%    |
| DCMT Technology                      | 5         | 0.1%    |
| Astro Gaming                         | 5         | 0.1%    |
| Trust                                | 4         | 0.08%   |
| Thesycon Systemsoftware & Consulting | 4         | 0.08%   |
| Tenx Technology                      | 4         | 0.08%   |
| Medeli Electronics                   | 4         | 0.08%   |
| Mackie Designs                       | 4         | 0.08%   |
| M-Audio                              | 4         | 0.08%   |
| Giga-Byte Technology                 | 4         | 0.08%   |
| BEHRINGER International              | 4         | 0.08%   |
| Antlion Audio                        | 4         | 0.08%   |
| Yamaha                               | 3         | 0.06%   |
| Valve Software                       | 3         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 541       | 8.51%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 288       | 4.53%   |
| AMD Starship/Matisse HD Audio Controller                                   | 253       | 3.98%   |
| Intel Sunrise Point-LP HD Audio                                            | 247       | 3.89%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 173       | 2.72%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 166       | 2.61%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 159       | 2.5%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 148       | 2.33%   |
| Intel Cannon Lake PCH cAVS                                                 | 134       | 2.11%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 124       | 1.95%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 115       | 1.81%   |
| Nvidia GA104 High Definition Audio Controller                              | 114       | 1.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 109       | 1.71%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 105       | 1.65%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 92        | 1.45%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 89        | 1.4%    |
| Intel Broadwell-U Audio Controller                                         | 88        | 1.38%   |
| Nvidia GA106 High Definition Audio Controller                              | 87        | 1.37%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 86        | 1.35%   |
| Intel Haswell-ULT HD Audio Controller                                      | 84        | 1.32%   |
| Intel Comet Lake PCH cAVS                                                  | 84        | 1.32%   |
| Intel 8 Series HD Audio Controller                                         | 83        | 1.31%   |
| Nvidia Audio device                                                        | 81        | 1.27%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 80        | 1.26%   |
| Nvidia TU116 High Definition Audio Controller                              | 73        | 1.15%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 72        | 1.13%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 68        | 1.07%   |
| Intel Comet Lake PCH-LP cAVS                                               | 68        | 1.07%   |
| Nvidia TU106 High Definition Audio Controller                              | 67        | 1.05%   |
| Nvidia GP107GL High Definition Audio Controller                            | 67        | 1.05%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 66        | 1.04%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 66        | 1.04%   |
| AMD FCH Azalia Controller                                                  | 64        | 1.01%   |
| Nvidia GP106 High Definition Audio Controller                              | 63        | 0.99%   |
| Nvidia GP104 High Definition Audio Controller                              | 63        | 0.99%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 63        | 0.99%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 59        | 0.93%   |
| Intel 200 Series PCH HD Audio                                              | 58        | 0.91%   |
| Nvidia TU104 HD Audio Controller                                           | 47        | 0.74%   |
| Nvidia GA102 High Definition Audio Controller                              | 47        | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 268       | 24.66%  |
| SK hynix                                | 209       | 19.23%  |
| Micron Technology                       | 145       | 13.34%  |
| Kingston                                | 92        | 8.46%   |
| Corsair                                 | 76        | 6.99%   |
| Crucial                                 | 65        | 5.98%   |
| G.Skill                                 | 49        | 4.51%   |
| Unknown                                 | 26        | 2.39%   |
| Team                                    | 23        | 2.12%   |
| A-DATA Technology                       | 21        | 1.93%   |
| Smart                                   | 13        | 1.2%    |
| Unknown                                 | 13        | 1.2%    |
| Neo Forza                               | 10        | 0.92%   |
| Elpida                                  | 10        | 0.92%   |
| Unknown (ABCD)                          | 9         | 0.83%   |
| Ramaxel Technology                      | 9         | 0.83%   |
| Goldkey                                 | 9         | 0.83%   |
| PNY                                     | 4         | 0.37%   |
| Nanya Technology                        | 4         | 0.37%   |
| Teikon                                  | 3         | 0.28%   |
| GSkill                                  | 3         | 0.28%   |
| Avant                                   | 3         | 0.28%   |
| Transcend                               | 2         | 0.18%   |
| Smart Brazil                            | 2         | 0.18%   |
| Patriot                                 | 2         | 0.18%   |
| Gold Key                                | 2         | 0.18%   |
| ChangXin Memory                         | 2         | 0.18%   |
| Apacer                                  | 2         | 0.18%   |
| Unknown (8A02)                          | 1         | 0.09%   |
| Unknown (09B6)                          | 1         | 0.09%   |
| Unknown (09A4)                          | 1         | 0.09%   |
| Timetec                                 | 1         | 0.09%   |
| Silicon Power Computer & Communications | 1         | 0.09%   |
| Patriot Memory (PDP Systems)            | 1         | 0.09%   |
| Patriot Memory                          | 1         | 0.09%   |
| Kllisre                                 | 1         | 0.09%   |
| GeIL                                    | 1         | 0.09%   |
| CSX                                     | 1         | 0.09%   |
| Asgard                                  | 1         | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 23        | 2.03%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 17        | 1.5%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 15        | 1.32%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 14        | 1.23%   |
| Unknown                                                          | 13        | 1.15%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 11        | 0.97%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 11        | 0.97%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 10        | 0.88%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 9         | 0.79%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 8         | 0.7%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 8         | 0.7%    |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 8         | 0.7%    |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 8         | 0.7%    |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 8         | 0.7%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 7         | 0.62%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 7         | 0.62%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 7         | 0.62%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 7         | 0.62%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 7         | 0.62%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 0.62%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 7         | 0.62%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 0.62%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s               | 6         | 0.53%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 6         | 0.53%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.53%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s           | 6         | 0.53%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 6         | 0.53%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 6         | 0.53%   |
| Micron RAM MT62F1G32D4DR-031 WT 4GB Row Of Chips LPDDR5 6400MT/s | 6         | 0.53%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 6         | 0.53%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 6         | 0.53%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 6         | 0.53%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 5         | 0.44%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.44%   |
| SK hynix RAM HMA851S6CJR6N-VK 4096MB SODIMM DDR4 2667MT/s        | 5         | 0.44%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 5         | 0.44%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 0.44%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.44%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 5         | 0.44%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 5         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 610       | 64.21%  |
| DDR3    | 145       | 15.26%  |
| DDR5    | 65        | 6.84%   |
| LPDDR4  | 55        | 5.79%   |
| LPDDR5  | 36        | 3.79%   |
| LPDDR3  | 24        | 2.53%   |
| DDR2    | 8         | 0.84%   |
| SDRAM   | 4         | 0.42%   |
| Unknown | 3         | 0.32%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 609       | 63.11%  |
| DIMM         | 220       | 22.8%   |
| Row Of Chips | 129       | 13.37%  |
| Chip         | 5         | 0.52%   |
| Unknown      | 2         | 0.21%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 459       | 45.09%  |
| 16384 | 234       | 22.99%  |
| 4096  | 201       | 19.74%  |
| 32768 | 78        | 7.66%   |
| 2048  | 42        | 4.13%   |
| 1024  | 4         | 0.39%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 285       | 28.08%  |
| 2667  | 169       | 16.65%  |
| 1600  | 111       | 10.94%  |
| 2400  | 60        | 5.91%   |
| 4800  | 49        | 4.83%   |
| 3600  | 44        | 4.33%   |
| 2133  | 39        | 3.84%   |
| 6400  | 38        | 3.74%   |
| 4267  | 32        | 3.15%   |
| 1867  | 15        | 1.48%   |
| 3733  | 14        | 1.38%   |
| 1333  | 14        | 1.38%   |
| 3800  | 13        | 1.28%   |
| 3266  | 11        | 1.08%   |
| 1334  | 10        | 0.99%   |
| 8400  | 8         | 0.79%   |
| 3533  | 8         | 0.79%   |
| 1067  | 7         | 0.69%   |
| 800   | 7         | 0.69%   |
| 6000  | 6         | 0.59%   |
| 4266  | 6         | 0.59%   |
| 3000  | 6         | 0.59%   |
| 2933  | 6         | 0.59%   |
| 3534  | 5         | 0.49%   |
| 3400  | 5         | 0.49%   |
| 5600  | 3         | 0.3%    |
| 5200  | 3         | 0.3%    |
| 3866  | 3         | 0.3%    |
| 2800  | 3         | 0.3%    |
| 2666  | 3         | 0.3%    |
| 1866  | 3         | 0.3%    |
| 4199  | 2         | 0.2%    |
| 4000  | 2         | 0.2%    |
| 3666  | 2         | 0.2%    |
| 3466  | 2         | 0.2%    |
| 3333  | 2         | 0.2%    |
| 3100  | 2         | 0.2%    |
| 2048  | 2         | 0.2%    |
| 667   | 2         | 0.2%    |
| 6800  | 1         | 0.1%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 17        | 31.48%  |
| Canon               | 9         | 16.67%  |
| Brother Industries  | 9         | 16.67%  |
| Samsung Electronics | 7         | 12.96%  |
| Seiko Epson         | 4         | 7.41%   |
| STMicroelectronics  | 2         | 3.7%    |
| Xerox               | 1         | 1.85%   |
| QinHeng Electronics | 1         | 1.85%   |
| Prolific Technology | 1         | 1.85%   |
| ICS Advent          | 1         | 1.85%   |
| Dymo-CoStar         | 1         | 1.85%   |
| Dell                | 1         | 1.85%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Brother HL-2130 series                                    | 3         | 5.45%   |
| Seiko Epson WF-4830 Series                                | 2         | 3.64%   |
| HP ENVY Pro 6400 series                                   | 2         | 3.64%   |
| Canon PIXMA MX920 Series                                  | 2         | 3.64%   |
| Xerox B215                                                | 1         | 1.82%   |
| STMicroelectronics USB Printer P                          | 1         | 1.82%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 1.82%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]              | 1         | 1.82%   |
| Seiko Epson ET-2800 Series                                | 1         | 1.82%   |
| Samsung SCX-4500 Laser Printer                            | 1         | 1.82%   |
| Samsung SCX-3400 Series                                   | 1         | 1.82%   |
| Samsung ML-216x Series Laser Printer                      | 1         | 1.82%   |
| Samsung ML-191x/ML-252x Laser Printer                     | 1         | 1.82%   |
| Samsung M2070 Series                                      | 1         | 1.82%   |
| Samsung M2020 Series                                      | 1         | 1.82%   |
| Samsung C460 Series                                       | 1         | 1.82%   |
| QinHeng CH340S                                            | 1         | 1.82%   |
| Prolific PL2305 Parallel Port                             | 1         | 1.82%   |
| ICS Advent Parallel Adapter                               | 1         | 1.82%   |
| HP PSC-1315/PSC-1317                                      | 1         | 1.82%   |
| HP OfficeJet Pro 9010 series                              | 1         | 1.82%   |
| HP OfficeJet 3830 series                                  | 1         | 1.82%   |
| HP LaserJet Professional P1102w                           | 1         | 1.82%   |
| HP LaserJet Professional P 1102w                          | 1         | 1.82%   |
| HP LaserJet Pro M201dw                                    | 1         | 1.82%   |
| HP LaserJet P2035                                         | 1         | 1.82%   |
| HP LaserJet M203-M206                                     | 1         | 1.82%   |
| HP LaserJet 3050                                          | 1         | 1.82%   |
| HP LaserJet 1010                                          | 1         | 1.82%   |
| HP Ink Tank Wireless 410 series                           | 1         | 1.82%   |
| HP Ink Tank 110 series                                    | 1         | 1.82%   |
| HP ENVY 5000 series                                       | 1         | 1.82%   |
| HP DeskJet 2600 series                                    | 1         | 1.82%   |
| HP Color LaserJet CP2025dn                                | 1         | 1.82%   |
| Dymo-CoStar DYMO LabelWriter 4XL                          | 1         | 1.82%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                    | 1         | 1.82%   |
| Dell Laser Printer 1720                                   | 1         | 1.82%   |
| Canon TS9100 series                                       | 1         | 1.82%   |
| Canon TR8500 series                                       | 1         | 1.82%   |
| Canon TR4700 series                                       | 1         | 1.82%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 4         | 44.44%  |
| Seiko Epson     | 3         | 33.33%  |
| Mustek Systems  | 1         | 11.11%  |
| Hewlett-Packard | 1         | 11.11%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]             | 1         | 11.11%  |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1         | 11.11%  |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]       | 1         | 11.11%  |
| Mustek Systems ScanExpress 1200 UB                      | 1         | 11.11%  |
| HP ScanJet 82x0C                                        | 1         | 11.11%  |
| Canon CanoScan N650U/N656U                              | 1         | 11.11%  |
| Canon CanoScan LiDE 60                                  | 1         | 11.11%  |
| Canon CanoScan LiDE 200                                 | 1         | 11.11%  |
| Canon CanoScan 9000F Mark II                            | 1         | 11.11%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 416       | 18.7%   |
| IMC Networks                           | 217       | 9.75%   |
| Microdia                               | 209       | 9.39%   |
| Realtek Semiconductor                  | 155       | 6.97%   |
| Logitech                               | 136       | 6.11%   |
| Apple                                  | 133       | 5.98%   |
| Bison Electronics                      | 124       | 5.57%   |
| Quanta                                 | 123       | 5.53%   |
| Sunplus Innovation Technology          | 107       | 4.81%   |
| Acer                                   | 88        | 3.96%   |
| Luxvisions Innotech Limited            | 61        | 2.74%   |
| Cheng Uei Precision Industry (Foxlink) | 57        | 2.56%   |
| Syntek                                 | 49        | 2.2%    |
| Lite-On Technology                     | 40        | 1.8%    |
| Suyin                                  | 28        | 1.26%   |
| Microsoft                              | 27        | 1.21%   |
| Sonix Technology                       | 25        | 1.12%   |
| Silicon Motion                         | 20        | 0.9%    |
| Samsung Electronics                    | 19        | 0.85%   |
| SunplusIT                              | 16        | 0.72%   |
| Razer USA                              | 12        | 0.54%   |
| Alcor Micro                            | 11        | 0.49%   |
| Z-Star Microelectronics                | 9         | 0.4%    |
| Generalplus Technology                 | 9         | 0.4%    |
| Creative Technology                    | 7         | 0.31%   |
| Ricoh                                  | 6         | 0.27%   |
| Jieli Technology                       | 6         | 0.27%   |
| ARC International                      | 6         | 0.27%   |
| MacroSilicon                           | 5         | 0.22%   |
| Lenovo                                 | 5         | 0.22%   |
| LG Electronics                         | 4         | 0.18%   |
| icSpring                               | 4         | 0.18%   |
| Cubeternet                             | 4         | 0.18%   |
| AVerMedia Technologies                 | 4         | 0.18%   |
| Trust                                  | 3         | 0.13%   |
| Tobii Technology AB                    | 3         | 0.13%   |
| SN0002                                 | 3         | 0.13%   |
| Primax Electronics                     | 3         | 0.13%   |
| Importek                               | 3         | 0.13%   |
| HRY                                    | 3         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                       | 96        | 4.27%   |
| Chicony Integrated Camera                           | 92        | 4.09%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 86        | 3.83%   |
| Realtek Integrated_Webcam_HD                        | 67        | 2.98%   |
| IMC Networks Integrated Camera                      | 51        | 2.27%   |
| Acer BisonCam,NB Pro                                | 41        | 1.82%   |
| Chicony HD WebCam                                   | 40        | 1.78%   |
| Syntek Integrated Camera                            | 38        | 1.69%   |
| Apple Built-in iSight                               | 37        | 1.65%   |
| Bison Integrated Camera                             | 35        | 1.56%   |
| Sunplus Integrated_Webcam_HD                        | 34        | 1.51%   |
| Logitech HD Pro Webcam C920                         | 34        | 1.51%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                  | 34        | 1.51%   |
| Apple FaceTime HD Camera (Built-in)                 | 34        | 1.51%   |
| Logitech Webcam C270                                | 31        | 1.38%   |
| Chicony USB2.0 Camera                               | 31        | 1.38%   |
| Bison HD Webcam                                     | 30        | 1.33%   |
| Quanta HD User Facing                               | 27        | 1.2%    |
| Apple FaceTime HD Camera                            | 23        | 1.02%   |
| Chicony HP HD Camera                                | 21        | 0.93%   |
| Quanta HP HD Camera                                 | 20        | 0.89%   |
| Sonix USB2.0 HD UVC WebCam                          | 19        | 0.85%   |
| Samsung Galaxy series, misc. (MTP mode)             | 19        | 0.85%   |
| Chicony HD User Facing                              | 19        | 0.85%   |
| Quanta HP TrueVision HD Camera                      | 16        | 0.71%   |
| Bison SunplusIT Integrated Camera                   | 16        | 0.71%   |
| Microdia Webcam Vitade AF                           | 15        | 0.67%   |
| Microdia USB 2.0 Camera                             | 15        | 0.67%   |
| Microdia Integrated Webcam                          | 15        | 0.67%   |
| Lite-On Integrated Camera                           | 15        | 0.67%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 15        | 0.67%   |
| Chicony USB2.0 VGA UVC WebCam                       | 14        | 0.62%   |
| Realtek Integrated Webcam                           | 13        | 0.58%   |
| Luxvisions Innotech Limited HP HD Camera            | 13        | 0.58%   |
| Chicony Integrated Camera (1280x720@30)             | 13        | 0.58%   |
| Chicony HP TrueVision HD Camera                     | 13        | 0.58%   |
| Quanta HP Wide Vision HD Camera                     | 12        | 0.53%   |
| Microdia Integrated_Webcam_FHD                      | 12        | 0.53%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 12        | 0.53%   |
| Logitech C922 Pro Stream Webcam                     | 12        | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 141       | 35.34%  |
| Validity Sensors                   | 102       | 25.56%  |
| Shenzhen Goodix Technology         | 79        | 19.8%   |
| Elan Microelectronics              | 25        | 6.27%   |
| LighTuning Technology              | 15        | 3.76%   |
| Upek                               | 14        | 3.51%   |
| AuthenTec                          | 8         | 2.01%   |
| Realtek USB2.0 Finger Print Bridge | 5         | 1.25%   |
| Focal-systems.Corp                 | 5         | 1.25%   |
| HOLTEK                             | 3         | 0.75%   |
| Samsung Electronics                | 1         | 0.25%   |
| DigitalPersona                     | 1         | 0.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 34        | 8.52%   |
| Shenzhen Goodix  Fingerprint Device                                        | 34        | 8.52%   |
| Shenzhen Goodix Fingerprint Reader                                         | 29        | 7.27%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 23        | 5.76%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 22        | 5.51%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 17        | 4.26%   |
| Shenzhen Goodix FingerPrint                                                | 16        | 4.01%   |
| Elan ELAN:ARM-M4                                                           | 14        | 3.51%   |
| Synaptics UWP WBDI                                                         | 13        | 3.26%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 11        | 2.76%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 10        | 2.51%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 9         | 2.26%   |
| Synaptics WBDI Device                                                      | 9         | 2.26%   |
| Elan ELAN:Fingerprint                                                      | 9         | 2.26%   |
| Validity Sensors Synaptics WBDI                                            | 8         | 2.01%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 8         | 2.01%   |
| Synaptics  WBDI                                                            | 8         | 2.01%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 8         | 2.01%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 7         | 1.75%   |
| Validity Sensors Fingerprint scanner                                       | 7         | 1.75%   |
| Synaptics WBDI                                                             | 7         | 1.75%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 1.5%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 6         | 1.5%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 6         | 1.5%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 6         | 1.5%    |
| Synaptics Fingerprint reader [HP G6]                                       | 6         | 1.5%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 1.25%   |
| Synaptics UWP WBDI Device                                                  | 5         | 1.25%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 5         | 1.25%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 5         | 1.25%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 5         | 1.25%   |
| Unknown                                                                    | 5         | 1.25%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 1%      |
| Validity Sensors VFS491                                                    | 3         | 0.75%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.75%   |
| Upek TCS5B Fingerprint sensor                                              | 3         | 0.75%   |
| LighTuning Fingerprint Sensor                                              | 3         | 0.75%   |
| HOLTEK FocalTech Fingerprint Device                                        | 3         | 0.75%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 0.75%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 0.5%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 67        | 52.34%  |
| Alcor Micro           | 39        | 30.47%  |
| O2 Micro              | 7         | 5.47%   |
| Lenovo                | 5         | 3.91%   |
| Upek                  | 4         | 3.13%   |
| OmniKey               | 2         | 1.56%   |
| SCM Microsystems      | 1         | 0.78%   |
| Gemalto (was Gemplus) | 1         | 0.78%   |
| Clay Logic            | 1         | 0.78%   |
| Advanced Card Systems | 1         | 0.78%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 38        | 29.69%  |
| Broadcom 58200                                                               | 23        | 17.97%  |
| Broadcom 5880                                                                | 18        | 14.06%  |
| Broadcom BCM5880 Secure Applications Processor                               | 16        | 12.5%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 10        | 7.81%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 6         | 4.69%   |
| Lenovo Integrated Smart Card Reader                                          | 5         | 3.91%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 3.13%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.78%   |
| OmniKey CardMan 4321                                                         | 1         | 0.78%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.78%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.78%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.78%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.78%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.78%   |
| Advanced Card Systems ACR1252 Dual Reader                                    | 1         | 0.78%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2303      | 67.18%  |
| 1     | 911       | 26.58%  |
| 2     | 180       | 5.25%   |
| 3     | 29        | 0.85%   |
| 4     | 3         | 0.09%   |
| 6     | 1         | 0.03%   |
| 5     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 387       | 29.12%  |
| Net/wireless             | 189       | 14.22%  |
| Graphics card            | 188       | 14.15%  |
| Multimedia controller    | 187       | 14.07%  |
| Chipcard                 | 121       | 9.1%    |
| Bluetooth                | 75        | 5.64%   |
| Camera                   | 47        | 3.54%   |
| Sound                    | 27        | 2.03%   |
| Unassigned class         | 23        | 1.73%   |
| Communication controller | 19        | 1.43%   |
| Net/ethernet             | 17        | 1.28%   |
| Network                  | 12        | 0.9%    |
| Storage                  | 9         | 0.68%   |
| Card reader              | 8         | 0.6%    |
| Modem                    | 7         | 0.53%   |
| Storage/raid             | 4         | 0.3%    |
| Storage/ide              | 4         | 0.3%    |
| Storage/nvme             | 3         | 0.23%   |
| Wireless                 | 1         | 0.08%   |
| Firewire controller      | 1         | 0.08%   |

