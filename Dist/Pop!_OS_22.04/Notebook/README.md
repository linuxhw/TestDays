Pop!_OS 22.04 - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for Pop!_OS 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 2765

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | ProBook 440 G4              | [810959ffa7](https://linux-hardware.org/?probe=810959ffa7) | Oct 01, 2023 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [6c314cd812](https://linux-hardware.org/?probe=6c314cd812) | Oct 01, 2023 |
| Lenovo        | IdeaPad Y700-15ACZ 80NY     | [12d98aba86](https://linux-hardware.org/?probe=12d98aba86) | Oct 01, 2023 |
| HP            | Dragonfly 13.5 inch G4 N... | [8fabc36e1c](https://linux-hardware.org/?probe=8fabc36e1c) | Oct 01, 2023 |
| Apple         | MacBookPro7,1               | [c69ebf2472](https://linux-hardware.org/?probe=c69ebf2472) | Oct 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [59dcd18330](https://linux-hardware.org/?probe=59dcd18330) | Sep 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [a6d0762090](https://linux-hardware.org/?probe=a6d0762090) | Sep 30, 2023 |
| HP            | Pro Tablet 608 G1           | [14fcb9ce4b](https://linux-hardware.org/?probe=14fcb9ce4b) | Sep 30, 2023 |
| HP            | Pro Tablet 608 G1           | [ab84386c83](https://linux-hardware.org/?probe=ab84386c83) | Sep 30, 2023 |
| Positivo      | C14CR01                     | [11b171838d](https://linux-hardware.org/?probe=11b171838d) | Sep 29, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [55b44bb456](https://linux-hardware.org/?probe=55b44bb456) | Sep 29, 2023 |
| System76      | Darter Pro                  | [d8b78103d5](https://linux-hardware.org/?probe=d8b78103d5) | Sep 29, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | [fb1c2503cf](https://linux-hardware.org/?probe=fb1c2503cf) | Sep 29, 2023 |
| Acer          | Aspire E5-575G              | [109490039d](https://linux-hardware.org/?probe=109490039d) | Sep 29, 2023 |
| MSI           | Cyborg 15 A12VF             | [960cd34617](https://linux-hardware.org/?probe=960cd34617) | Sep 29, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [e23bfd302c](https://linux-hardware.org/?probe=e23bfd302c) | Sep 28, 2023 |
| Toshiba       | Satellite P775              | [7269165fd9](https://linux-hardware.org/?probe=7269165fd9) | Sep 28, 2023 |
| Apple         | MacBookAir6,2               | [b0c2b630a6](https://linux-hardware.org/?probe=b0c2b630a6) | Sep 28, 2023 |
| System76      | Oryx Pro                    | [f06316545d](https://linux-hardware.org/?probe=f06316545d) | Sep 28, 2023 |
| Acer          | Aspire VN7-791G             | [0cfe515d00](https://linux-hardware.org/?probe=0cfe515d00) | Sep 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [7c13a64c8a](https://linux-hardware.org/?probe=7c13a64c8a) | Sep 27, 2023 |
| Dell          | Latitude 5480               | [8dd1695b2c](https://linux-hardware.org/?probe=8dd1695b2c) | Sep 27, 2023 |
| System76      | Lemur Pro                   | [6013ab7f8a](https://linux-hardware.org/?probe=6013ab7f8a) | Sep 27, 2023 |
| Dell          | Latitude E7440              | [9e117fe599](https://linux-hardware.org/?probe=9e117fe599) | Sep 27, 2023 |
| HONOR         | NBR-WAX9                    | [68556b1e09](https://linux-hardware.org/?probe=68556b1e09) | Sep 27, 2023 |
| HONOR         | NBR-WAX9                    | [056de6b9b3](https://linux-hardware.org/?probe=056de6b9b3) | Sep 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [d9665a6ffd](https://linux-hardware.org/?probe=d9665a6ffd) | Sep 27, 2023 |
| Apple         | MacBookAir7,2               | [f9f08875e1](https://linux-hardware.org/?probe=f9f08875e1) | Sep 26, 2023 |
| MSI           | Summit E13FlipEvo A12MT     | [5fa9f0dde2](https://linux-hardware.org/?probe=5fa9f0dde2) | Sep 26, 2023 |
| HUAWEI        | NbDE-WXX9                   | [b3990570ee](https://linux-hardware.org/?probe=b3990570ee) | Sep 25, 2023 |
| HP            | 250 G4                      | [6e475cbb1f](https://linux-hardware.org/?probe=6e475cbb1f) | Sep 25, 2023 |
| HP            | 250 G4                      | [9543354fea](https://linux-hardware.org/?probe=9543354fea) | Sep 25, 2023 |
| Acer          | Swift SFX14-41G             | [ae755aa7e3](https://linux-hardware.org/?probe=ae755aa7e3) | Sep 25, 2023 |
| HP            | OMEN by Gaming Laptop 16... | [cb2b1325cc](https://linux-hardware.org/?probe=cb2b1325cc) | Sep 25, 2023 |
| MSI           | Cyborg 15 A12VF             | [f934062b23](https://linux-hardware.org/?probe=f934062b23) | Sep 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [7d18eb441e](https://linux-hardware.org/?probe=7d18eb441e) | Sep 24, 2023 |
| Fujitsu       | LIFEBOOK A557               | [e66c8c9ca7](https://linux-hardware.org/?probe=e66c8c9ca7) | Sep 24, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [dfe5d4faaa](https://linux-hardware.org/?probe=dfe5d4faaa) | Sep 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [8318fdeb5b](https://linux-hardware.org/?probe=8318fdeb5b) | Sep 24, 2023 |
| Dell          | System XPS L502X            | [22d93fe76c](https://linux-hardware.org/?probe=22d93fe76c) | Sep 24, 2023 |
| MSI           | Cyborg 15 A12VF             | [7aa2ea2853](https://linux-hardware.org/?probe=7aa2ea2853) | Sep 24, 2023 |
| Dell          | System XPS L502X            | [a1d4f683c1](https://linux-hardware.org/?probe=a1d4f683c1) | Sep 24, 2023 |
| Acer          | Swift SFX14-41G             | [7980181fcb](https://linux-hardware.org/?probe=7980181fcb) | Sep 24, 2023 |
| Dell          | XPS 15 9520                 | [b358b656c6](https://linux-hardware.org/?probe=b358b656c6) | Sep 24, 2023 |
| Toshiba       | TECRA X40-E                 | [280f949acc](https://linux-hardware.org/?probe=280f949acc) | Sep 24, 2023 |
| HP            | 250 G4                      | [5290896e7d](https://linux-hardware.org/?probe=5290896e7d) | Sep 23, 2023 |
| System76      | Gazelle                     | [2e31a65d58](https://linux-hardware.org/?probe=2e31a65d58) | Sep 23, 2023 |
| HP            | Laptop 15-db1xxx            | [8b16720f22](https://linux-hardware.org/?probe=8b16720f22) | Sep 23, 2023 |
| Dell          | Vostro 5481                 | [c416e12adb](https://linux-hardware.org/?probe=c416e12adb) | Sep 22, 2023 |
| ASUSTek       | ROG Strix G814JZ_G814JZ     | [2a6c2ef738](https://linux-hardware.org/?probe=2a6c2ef738) | Sep 22, 2023 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | [726a5f4cf5](https://linux-hardware.org/?probe=726a5f4cf5) | Sep 22, 2023 |
| HUAWEI        | KPL-W0X                     | [3154e03d3f](https://linux-hardware.org/?probe=3154e03d3f) | Sep 22, 2023 |
| HP            | Laptop 15-db1xxx            | [504ed03ead](https://linux-hardware.org/?probe=504ed03ead) | Sep 22, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [1d9ae81bf1](https://linux-hardware.org/?probe=1d9ae81bf1) | Sep 22, 2023 |
| Notebook      | NH50_70RH                   | [57070abf3c](https://linux-hardware.org/?probe=57070abf3c) | Sep 21, 2023 |
| System76      | Darter Pro                  | [3266f46a3b](https://linux-hardware.org/?probe=3266f46a3b) | Sep 20, 2023 |
| Dell          | Precision 5680              | [a75a75f080](https://linux-hardware.org/?probe=a75a75f080) | Sep 20, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [a97463154d](https://linux-hardware.org/?probe=a97463154d) | Sep 20, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [cbc4ec2df0](https://linux-hardware.org/?probe=cbc4ec2df0) | Sep 20, 2023 |
| Apple         | MacBookPro8,1               | [43edd5f49f](https://linux-hardware.org/?probe=43edd5f49f) | Sep 20, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [a8b35a2b8f](https://linux-hardware.org/?probe=a8b35a2b8f) | Sep 19, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [8adb5c3a12](https://linux-hardware.org/?probe=8adb5c3a12) | Sep 19, 2023 |
| Framework     | Laptop                      | [f379873c4b](https://linux-hardware.org/?probe=f379873c4b) | Sep 19, 2023 |
| HP            | Pavilion 15                 | [eb15fe383c](https://linux-hardware.org/?probe=eb15fe383c) | Sep 18, 2023 |
| HP            | Pavilion 15                 | [fb86634643](https://linux-hardware.org/?probe=fb86634643) | Sep 18, 2023 |
| HP            | Dev One Notebook PC         | [2606a8d1c1](https://linux-hardware.org/?probe=2606a8d1c1) | Sep 17, 2023 |
| HONOR         | BMH-WCX9                    | [96a8945a17](https://linux-hardware.org/?probe=96a8945a17) | Sep 17, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [797e19424f](https://linux-hardware.org/?probe=797e19424f) | Sep 16, 2023 |
| Notebook      | NV4XMB,ME,MZ                | [35bc7480cb](https://linux-hardware.org/?probe=35bc7480cb) | Sep 15, 2023 |
| Unknown       | Unknown                     | [ae1fde8210](https://linux-hardware.org/?probe=ae1fde8210) | Sep 15, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | [98dbf213e7](https://linux-hardware.org/?probe=98dbf213e7) | Sep 15, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [5150bae6bd](https://linux-hardware.org/?probe=5150bae6bd) | Sep 15, 2023 |
| HP            | OMEN by Gaming Laptop 16... | [175e57d54f](https://linux-hardware.org/?probe=175e57d54f) | Sep 15, 2023 |
| Digibras      | CL341                       | [a358f5d40c](https://linux-hardware.org/?probe=a358f5d40c) | Sep 15, 2023 |
| Lenovo        | Slim Pro 9 14IRP8 83BV      | [bc86928972](https://linux-hardware.org/?probe=bc86928972) | Sep 15, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | [4f6e19f508](https://linux-hardware.org/?probe=4f6e19f508) | Sep 14, 2023 |
| ASUSTek       | X556URK                     | [0996de9eac](https://linux-hardware.org/?probe=0996de9eac) | Sep 14, 2023 |
| Dell          | Latitude 7440               | [cd8e3aa6ed](https://linux-hardware.org/?probe=cd8e3aa6ed) | Sep 14, 2023 |
| realme        | RMNBXXXX                    | [7f93463d6a](https://linux-hardware.org/?probe=7f93463d6a) | Sep 14, 2023 |
| realme        | RMNBXXXX                    | [a635ea5599](https://linux-hardware.org/?probe=a635ea5599) | Sep 14, 2023 |
| Toshiba       | Satellite L735              | [fee724f874](https://linux-hardware.org/?probe=fee724f874) | Sep 14, 2023 |
| System76      | Pangolin                    | [c3803d0977](https://linux-hardware.org/?probe=c3803d0977) | Sep 13, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | [ef5a6433f3](https://linux-hardware.org/?probe=ef5a6433f3) | Sep 13, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | [df7945af41](https://linux-hardware.org/?probe=df7945af41) | Sep 13, 2023 |
| Apple         | MacBookPro9,2               | [c159157024](https://linux-hardware.org/?probe=c159157024) | Sep 13, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [03e666ab42](https://linux-hardware.org/?probe=03e666ab42) | Sep 12, 2023 |
| MSI           | Stealth 15M B12UE           | [9a23215875](https://linux-hardware.org/?probe=9a23215875) | Sep 11, 2023 |
| Schenker      | XMG NEO (TGL/M21)           | [8f9ada75e9](https://linux-hardware.org/?probe=8f9ada75e9) | Sep 11, 2023 |
| Dell          | Latitude E7250              | [44983ff513](https://linux-hardware.org/?probe=44983ff513) | Sep 11, 2023 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | [1b2d76894b](https://linux-hardware.org/?probe=1b2d76894b) | Sep 10, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [a9caf49f0e](https://linux-hardware.org/?probe=a9caf49f0e) | Sep 09, 2023 |
| Lenovo        | V720-14 80Y1                | [ec869beffd](https://linux-hardware.org/?probe=ec869beffd) | Sep 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [5fc227a0e8](https://linux-hardware.org/?probe=5fc227a0e8) | Sep 08, 2023 |
| Dell          | Vostro 5502                 | [a131efa36e](https://linux-hardware.org/?probe=a131efa36e) | Sep 08, 2023 |
| HP            | Laptop 14-dk0xxx            | [57b82728d8](https://linux-hardware.org/?probe=57b82728d8) | Sep 08, 2023 |
| HP            | EliteBook 745 G5            | [05d61b5c23](https://linux-hardware.org/?probe=05d61b5c23) | Sep 08, 2023 |
| MSI           | P65 Creator 8RD             | [3eab920cfc](https://linux-hardware.org/?probe=3eab920cfc) | Sep 07, 2023 |
| HP            | Laptop 15-dy2xxx            | [eae373ebd4](https://linux-hardware.org/?probe=eae373ebd4) | Sep 07, 2023 |
| MSI           | Alpha 15 A3DDK              | [9a87dfb80b](https://linux-hardware.org/?probe=9a87dfb80b) | Sep 07, 2023 |
| HP            | EliteBook 8760w             | [d061b57b29](https://linux-hardware.org/?probe=d061b57b29) | Sep 07, 2023 |
| Alienware     | m15 R7                      | [9e6b80bbf2](https://linux-hardware.org/?probe=9e6b80bbf2) | Sep 07, 2023 |
| Apple         | MacBookPro11,3              | [bfdd099826](https://linux-hardware.org/?probe=bfdd099826) | Sep 06, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [0692b6f878](https://linux-hardware.org/?probe=0692b6f878) | Sep 06, 2023 |
| Acer          | Swift SFX14-41G             | [611bb4fe1a](https://linux-hardware.org/?probe=611bb4fe1a) | Sep 06, 2023 |
| Acer          | Swift SFX14-41G             | [38f9d1abd9](https://linux-hardware.org/?probe=38f9d1abd9) | Sep 05, 2023 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | [27575898fe](https://linux-hardware.org/?probe=27575898fe) | Sep 05, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [dda5b7f9c9](https://linux-hardware.org/?probe=dda5b7f9c9) | Sep 05, 2023 |
| Dell          | Inspiron 14 5420            | [70d0d79f77](https://linux-hardware.org/?probe=70d0d79f77) | Sep 05, 2023 |
| Apple         | MacBookPro10,1              | [11c016fb1b](https://linux-hardware.org/?probe=11c016fb1b) | Sep 05, 2023 |
| Dell          | Latitude E5430 non-vPro     | [ee1a881e82](https://linux-hardware.org/?probe=ee1a881e82) | Sep 04, 2023 |
| System76      | Lemur Pro                   | [9ea11da090](https://linux-hardware.org/?probe=9ea11da090) | Sep 04, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | [68e90ee0cb](https://linux-hardware.org/?probe=68e90ee0cb) | Sep 04, 2023 |
| ASUSTek       | K53E                        | [5604fe515d](https://linux-hardware.org/?probe=5604fe515d) | Sep 04, 2023 |
| Dell          | XPS 17 9700                 | [e758c8955e](https://linux-hardware.org/?probe=e758c8955e) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [2ddf0c5c61](https://linux-hardware.org/?probe=2ddf0c5c61) | Sep 03, 2023 |
| HP            | 240 G8 Notebook PC          | [092ae0b34d](https://linux-hardware.org/?probe=092ae0b34d) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | [f2f5e496f1](https://linux-hardware.org/?probe=f2f5e496f1) | Sep 02, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | [515e1f4bce](https://linux-hardware.org/?probe=515e1f4bce) | Sep 02, 2023 |
| Apple         | MacBookAir3,2               | [5ee8cbf433](https://linux-hardware.org/?probe=5ee8cbf433) | Sep 02, 2023 |
| Schenker      | VIA 15 Pro                  | [4a31ab4d2b](https://linux-hardware.org/?probe=4a31ab4d2b) | Sep 02, 2023 |
| Apple         | MacBookAir6,2               | [da8d60051c](https://linux-hardware.org/?probe=da8d60051c) | Sep 02, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | [87e1726495](https://linux-hardware.org/?probe=87e1726495) | Sep 01, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | [e73e853358](https://linux-hardware.org/?probe=e73e853358) | Sep 01, 2023 |
| ASUSTek       | N550JV                      | [b2effdc956](https://linux-hardware.org/?probe=b2effdc956) | Sep 01, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [2433535726](https://linux-hardware.org/?probe=2433535726) | Sep 01, 2023 |
| Dell          | Inspiron 5558               | [77c6379594](https://linux-hardware.org/?probe=77c6379594) | Sep 01, 2023 |
| Acer          | Swift SFX14-41G             | [67f553625a](https://linux-hardware.org/?probe=67f553625a) | Sep 01, 2023 |
| Dell          | Latitude E7470              | [0580f1c293](https://linux-hardware.org/?probe=0580f1c293) | Sep 01, 2023 |
| Lenovo        | ThinkPad T450 20BUS0B000    | [1213d3bf46](https://linux-hardware.org/?probe=1213d3bf46) | Aug 31, 2023 |
| Acer          | Aspire E5-551G              | [628d865373](https://linux-hardware.org/?probe=628d865373) | Aug 31, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [3b890e064f](https://linux-hardware.org/?probe=3b890e064f) | Aug 31, 2023 |
| Acer          | Nitro AN515-55              | [6c5da44516](https://linux-hardware.org/?probe=6c5da44516) | Aug 31, 2023 |
| Google        | Kefka                       | [284517c2b3](https://linux-hardware.org/?probe=284517c2b3) | Aug 31, 2023 |
| Lenovo        | ThinkPad W520 427637U       | [5f995c7c48](https://linux-hardware.org/?probe=5f995c7c48) | Aug 30, 2023 |
| Apple         | MacBookPro5,5               | [641243c308](https://linux-hardware.org/?probe=641243c308) | Aug 30, 2023 |
| Lenovo        | G50-80 80E5                 | [5ba6fd6ca3](https://linux-hardware.org/?probe=5ba6fd6ca3) | Aug 30, 2023 |
| Google        | Kefka                       | [a018ae3fb5](https://linux-hardware.org/?probe=a018ae3fb5) | Aug 30, 2023 |
| Acer          | Aspire E5-571               | [500ef94276](https://linux-hardware.org/?probe=500ef94276) | Aug 29, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [90a72df8ef](https://linux-hardware.org/?probe=90a72df8ef) | Aug 29, 2023 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [4904c007c7](https://linux-hardware.org/?probe=4904c007c7) | Aug 29, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [ba9dd7a62d](https://linux-hardware.org/?probe=ba9dd7a62d) | Aug 29, 2023 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [f1b8efb723](https://linux-hardware.org/?probe=f1b8efb723) | Aug 29, 2023 |
| ASUSTek       | ROG Strix G634JZ_G634JZ     | [481b37b0fc](https://linux-hardware.org/?probe=481b37b0fc) | Aug 29, 2023 |
| Dell          | Latitude 5330               | [7e63575d10](https://linux-hardware.org/?probe=7e63575d10) | Aug 29, 2023 |
| Lenovo        | ThinkPad T430s 2356CU8      | [2f669d797f](https://linux-hardware.org/?probe=2f669d797f) | Aug 29, 2023 |
| Lenovo        | ThinkPad T430s 2356CU8      | [39f2feeed5](https://linux-hardware.org/?probe=39f2feeed5) | Aug 29, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHC... | [de65d63e10](https://linux-hardware.org/?probe=de65d63e10) | Aug 28, 2023 |
| Lenovo        | Legion 5 15IMH 82CF         | [4d8ac47399](https://linux-hardware.org/?probe=4d8ac47399) | Aug 28, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHC... | [dc9a79314c](https://linux-hardware.org/?probe=dc9a79314c) | Aug 28, 2023 |
| Dell          | XPS 15 7590                 | [ef97f75590](https://linux-hardware.org/?probe=ef97f75590) | Aug 28, 2023 |
| Dell          | Precision 5510              | [c6d08d9c28](https://linux-hardware.org/?probe=c6d08d9c28) | Aug 27, 2023 |
| HP            | EliteBook 865 16 inch G9... | [b07775a194](https://linux-hardware.org/?probe=b07775a194) | Aug 27, 2023 |
| HP            | 250 G7 Notebook PC          | [c4be1d7e95](https://linux-hardware.org/?probe=c4be1d7e95) | Aug 27, 2023 |
| Lenovo        | ThinkPad T460 20FMS05K05    | [747e8d4f6a](https://linux-hardware.org/?probe=747e8d4f6a) | Aug 27, 2023 |
| Dell          | Precision M4600             | [b7fca4d2f9](https://linux-hardware.org/?probe=b7fca4d2f9) | Aug 27, 2023 |
| Apple         | MacBookPro8,2               | [9e0b5b0b7e](https://linux-hardware.org/?probe=9e0b5b0b7e) | Aug 26, 2023 |
| Dell          | Precision M6800             | [6aa5f8e441](https://linux-hardware.org/?probe=6aa5f8e441) | Aug 26, 2023 |
| HP            | ProBook 4730s               | [32f610b810](https://linux-hardware.org/?probe=32f610b810) | Aug 26, 2023 |
| Google        | Kasumi                      | [9af5f77257](https://linux-hardware.org/?probe=9af5f77257) | Aug 25, 2023 |
| System76      | Gazelle                     | [b3fb438915](https://linux-hardware.org/?probe=b3fb438915) | Aug 25, 2023 |
| MSI           | GE60 2OC\2OD\2OE            | [e2e304c9eb](https://linux-hardware.org/?probe=e2e304c9eb) | Aug 25, 2023 |
| HP            | EliteBook 865 16 inch G9... | [34fc2a5f83](https://linux-hardware.org/?probe=34fc2a5f83) | Aug 24, 2023 |
| Dell          | Latitude E7240              | [cb61859037](https://linux-hardware.org/?probe=cb61859037) | Aug 24, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [6cf9db7da7](https://linux-hardware.org/?probe=6cf9db7da7) | Aug 24, 2023 |
| Dell          | Latitude 7430               | [7daf0301c5](https://linux-hardware.org/?probe=7daf0301c5) | Aug 24, 2023 |
| Toshiba       | Satellite L655              | [18df557333](https://linux-hardware.org/?probe=18df557333) | Aug 24, 2023 |
| HP            | Pavilion Notebook           | [b0ca2ee250](https://linux-hardware.org/?probe=b0ca2ee250) | Aug 23, 2023 |
| MSI           | GE60 2OC\2OD\2OE            | [50f079ae44](https://linux-hardware.org/?probe=50f079ae44) | Aug 23, 2023 |
| Dell          | XPS 13 9310                 | [6f0e38b5e8](https://linux-hardware.org/?probe=6f0e38b5e8) | Aug 23, 2023 |
| Samsung       | 750TDA                      | [7b1ec96afa](https://linux-hardware.org/?probe=7b1ec96afa) | Aug 23, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | [4cd19df49e](https://linux-hardware.org/?probe=4cd19df49e) | Aug 23, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2RV0... | [e8d2c8e1d5](https://linux-hardware.org/?probe=e8d2c8e1d5) | Aug 22, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | [fdd24243bf](https://linux-hardware.org/?probe=fdd24243bf) | Aug 22, 2023 |
| Acer          | Aspire A715-75G             | [54794fb9e8](https://linux-hardware.org/?probe=54794fb9e8) | Aug 22, 2023 |
| HP            | ProBook 4730s               | [5b4d88bc67](https://linux-hardware.org/?probe=5b4d88bc67) | Aug 21, 2023 |
| Samsung       | 270E5G/270E5U               | [930d312c36](https://linux-hardware.org/?probe=930d312c36) | Aug 21, 2023 |
| Samsung       | 270E5G/270E5U               | [2bc8c24081](https://linux-hardware.org/?probe=2bc8c24081) | Aug 21, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [b66d308d42](https://linux-hardware.org/?probe=b66d308d42) | Aug 21, 2023 |
| MSI           | Modern 15 A5M               | [f9742049fc](https://linux-hardware.org/?probe=f9742049fc) | Aug 20, 2023 |
| System76      | Oryx Pro                    | [b7e0bd11e5](https://linux-hardware.org/?probe=b7e0bd11e5) | Aug 20, 2023 |
| Dell          | Precision 5520              | [42587aac96](https://linux-hardware.org/?probe=42587aac96) | Aug 20, 2023 |
| Dell          | Precision 5520              | [bec735d800](https://linux-hardware.org/?probe=bec735d800) | Aug 20, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QR    | [5d063a6e59](https://linux-hardware.org/?probe=5d063a6e59) | Aug 19, 2023 |
| Lenovo        | B490 377224P                | [0e516ea22b](https://linux-hardware.org/?probe=0e516ea22b) | Aug 19, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | [a1ab007f7f](https://linux-hardware.org/?probe=a1ab007f7f) | Aug 18, 2023 |
| ASUSTek       | U38N                        | [0e0f709353](https://linux-hardware.org/?probe=0e0f709353) | Aug 17, 2023 |
| HP            | EliteBook 850 G3            | [a6a7224d63](https://linux-hardware.org/?probe=a6a7224d63) | Aug 17, 2023 |
| Dell          | XPS 13 9310                 | [680fae2274](https://linux-hardware.org/?probe=680fae2274) | Aug 17, 2023 |
| ASUSTek       | Vivobook Go E1404FA_E140... | [43fd1aad67](https://linux-hardware.org/?probe=43fd1aad67) | Aug 17, 2023 |
| System76      | Lemur Pro                   | [af3b387574](https://linux-hardware.org/?probe=af3b387574) | Aug 16, 2023 |
| Acer          | Aspire 5750                 | [ec4afb1917](https://linux-hardware.org/?probe=ec4afb1917) | Aug 16, 2023 |
| A-DATA Tec... | XENIA 14                    | [59faf4a458](https://linux-hardware.org/?probe=59faf4a458) | Aug 15, 2023 |
| A-DATA Tec... | XENIA 14                    | [537cce8a8e](https://linux-hardware.org/?probe=537cce8a8e) | Aug 15, 2023 |
| HP            | Laptop 15s-eq2xxx           | [c2cfa9bd7a](https://linux-hardware.org/?probe=c2cfa9bd7a) | Aug 15, 2023 |
| Apple         | MacBookAir6,2               | [431ac1b880](https://linux-hardware.org/?probe=431ac1b880) | Aug 15, 2023 |
| Dell          | XPS 15 9570                 | [ce22773504](https://linux-hardware.org/?probe=ce22773504) | Aug 15, 2023 |
| System76      | Galago Pro                  | [54348f9c55](https://linux-hardware.org/?probe=54348f9c55) | Aug 14, 2023 |
| Apple         | MacBookPro9,2               | [61ff7ac5f1](https://linux-hardware.org/?probe=61ff7ac5f1) | Aug 14, 2023 |
| Apple         | MacBookPro16,1              | [18b513f5f0](https://linux-hardware.org/?probe=18b513f5f0) | Aug 14, 2023 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | [1f27d0f994](https://linux-hardware.org/?probe=1f27d0f994) | Aug 14, 2023 |
| HP            | ProBook 4540s               | [84dbf6b759](https://linux-hardware.org/?probe=84dbf6b759) | Aug 13, 2023 |
| Dell          | Inspiron 3542               | [ae586a02aa](https://linux-hardware.org/?probe=ae586a02aa) | Aug 13, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [823e276406](https://linux-hardware.org/?probe=823e276406) | Aug 13, 2023 |
| GPU Compan... | GWNR71517                   | [a38cee5cc9](https://linux-hardware.org/?probe=a38cee5cc9) | Aug 12, 2023 |
| Acer          | Aspire ES1-520              | [a47415983e](https://linux-hardware.org/?probe=a47415983e) | Aug 12, 2023 |
| Lenovo        | ThinkPad L13 20R3CTO1WW     | [6ac135c81c](https://linux-hardware.org/?probe=6ac135c81c) | Aug 12, 2023 |
| ASUSTek       | K53TK                       | [db9f130ade](https://linux-hardware.org/?probe=db9f130ade) | Aug 12, 2023 |
| Dell          | G7 7588                     | [48faf46c2c](https://linux-hardware.org/?probe=48faf46c2c) | Aug 12, 2023 |
| Lenovo        | Yoga Pro 9 14IRP8 83BU      | [f46a14b981](https://linux-hardware.org/?probe=f46a14b981) | Aug 12, 2023 |
| HP            | EliteBook 820 G3            | [544810db31](https://linux-hardware.org/?probe=544810db31) | Aug 12, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [0d45e9e048](https://linux-hardware.org/?probe=0d45e9e048) | Aug 12, 2023 |
| Dell          | Precision M4600             | [f97367efac](https://linux-hardware.org/?probe=f97367efac) | Aug 11, 2023 |
| Lenovo        | IdeaPad 310-15IAP 80TT      | [361e073b5c](https://linux-hardware.org/?probe=361e073b5c) | Aug 11, 2023 |
| Acer          | Nitro AN715-51              | [ea972c8686](https://linux-hardware.org/?probe=ea972c8686) | Aug 11, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [e22f71b79d](https://linux-hardware.org/?probe=e22f71b79d) | Aug 11, 2023 |
| ASUSTek       | X751LD                      | [e98d8d116d](https://linux-hardware.org/?probe=e98d8d116d) | Aug 10, 2023 |
| Apple         | MacBookAir5,2               | [7f91d6f9d8](https://linux-hardware.org/?probe=7f91d6f9d8) | Aug 10, 2023 |
| Acer          | Nitro AN517-55              | [b77ff095f8](https://linux-hardware.org/?probe=b77ff095f8) | Aug 09, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [6415840d5b](https://linux-hardware.org/?probe=6415840d5b) | Aug 09, 2023 |
| HP            | ProBook 4330s               | [5c854bed9f](https://linux-hardware.org/?probe=5c854bed9f) | Aug 09, 2023 |
| HP            | ProBook 4330s               | [d23ce497d2](https://linux-hardware.org/?probe=d23ce497d2) | Aug 09, 2023 |
| System76      | Darter Pro                  | [5162d61c01](https://linux-hardware.org/?probe=5162d61c01) | Aug 09, 2023 |
| MSI           | Cyborg 15 A12VF             | [b041192310](https://linux-hardware.org/?probe=b041192310) | Aug 09, 2023 |
| Alienware     | 14                          | [192b13997d](https://linux-hardware.org/?probe=192b13997d) | Aug 09, 2023 |
| HP            | Victus by 15.6 inch Gami... | [67f88ab571](https://linux-hardware.org/?probe=67f88ab571) | Aug 08, 2023 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | [afa081b440](https://linux-hardware.org/?probe=afa081b440) | Aug 08, 2023 |
| Acer          | Ferrari One 200             | [be688aa584](https://linux-hardware.org/?probe=be688aa584) | Aug 08, 2023 |
| Apple         | MacBookPro10,1              | [00b169d241](https://linux-hardware.org/?probe=00b169d241) | Aug 08, 2023 |
| Apple         | MacBookPro11,3              | [c415fd317b](https://linux-hardware.org/?probe=c415fd317b) | Aug 08, 2023 |
| Apple         | MacBookPro10,1              | [5e0c7f7bfc](https://linux-hardware.org/?probe=5e0c7f7bfc) | Aug 08, 2023 |
| Acer          | Aspire A715-75G             | [57f1225daf](https://linux-hardware.org/?probe=57f1225daf) | Aug 08, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [088a8fad47](https://linux-hardware.org/?probe=088a8fad47) | Aug 08, 2023 |
| System76      | Oryx Pro                    | [c5b97761d3](https://linux-hardware.org/?probe=c5b97761d3) | Aug 07, 2023 |
| MSI           | Cyborg 15 A12VF             | [5fe9a17769](https://linux-hardware.org/?probe=5fe9a17769) | Aug 07, 2023 |
| MSI           | GP72 7RDX                   | [43eb53850c](https://linux-hardware.org/?probe=43eb53850c) | Aug 06, 2023 |
| Clevo         | W150HRM                     | [1ddcfcbecc](https://linux-hardware.org/?probe=1ddcfcbecc) | Aug 06, 2023 |
| Apple         | MacBookPro9,2               | [16936ef482](https://linux-hardware.org/?probe=16936ef482) | Aug 06, 2023 |
| MSI           | GP72 7RDX                   | [6d2bc8aa9e](https://linux-hardware.org/?probe=6d2bc8aa9e) | Aug 06, 2023 |
| Timi          | RedmiBook Pro 15S           | [576241bbd4](https://linux-hardware.org/?probe=576241bbd4) | Aug 06, 2023 |
| Notebook      | 1745                        | [3561a5dbbe](https://linux-hardware.org/?probe=3561a5dbbe) | Aug 06, 2023 |
| HP            | Pavilion dm4                | [521b8518ed](https://linux-hardware.org/?probe=521b8518ed) | Aug 06, 2023 |
| Dell          | Latitude 5430               | [f63444b0be](https://linux-hardware.org/?probe=f63444b0be) | Aug 05, 2023 |
| Apple         | MacBookPro11,2              | [32f8bbeff7](https://linux-hardware.org/?probe=32f8bbeff7) | Aug 05, 2023 |
| MSI           | Modern 15 A5M               | [a4a6f81455](https://linux-hardware.org/?probe=a4a6f81455) | Aug 05, 2023 |
| MSI           | Modern 15 A5M               | [ef010c9d51](https://linux-hardware.org/?probe=ef010c9d51) | Aug 05, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [7d17fc9ff6](https://linux-hardware.org/?probe=7d17fc9ff6) | Aug 05, 2023 |
| Lenovo        | V15 G3 ABA 82TV             | [0147060507](https://linux-hardware.org/?probe=0147060507) | Aug 04, 2023 |
| HP            | ProBook 650 G1              | [286cc8b0dd](https://linux-hardware.org/?probe=286cc8b0dd) | Aug 04, 2023 |
| Lenovo        | ThinkPad W541 20EGS0GY0R    | [4d618e08b3](https://linux-hardware.org/?probe=4d618e08b3) | Aug 03, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D6C... | [a97312771e](https://linux-hardware.org/?probe=a97312771e) | Aug 03, 2023 |
| Dell          | XPS 13 9370                 | [cf49ff3004](https://linux-hardware.org/?probe=cf49ff3004) | Aug 03, 2023 |
| Dell          | Latitude E7240              | [ec5ec88e59](https://linux-hardware.org/?probe=ec5ec88e59) | Aug 02, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [99ccd043cb](https://linux-hardware.org/?probe=99ccd043cb) | Aug 02, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [d4e267a214](https://linux-hardware.org/?probe=d4e267a214) | Aug 02, 2023 |
| HP            | ProBook 650 G4              | [d041df173b](https://linux-hardware.org/?probe=d041df173b) | Aug 02, 2023 |
| Apple         | MacBookPro11,3              | [1eb6fd9620](https://linux-hardware.org/?probe=1eb6fd9620) | Aug 02, 2023 |
| Apple         | MacBookPro7,1               | [0a3c5e5c4d](https://linux-hardware.org/?probe=0a3c5e5c4d) | Aug 02, 2023 |
| Apple         | MacBookPro7,1               | [9f852ea211](https://linux-hardware.org/?probe=9f852ea211) | Aug 02, 2023 |
| ASUSTek       | GL502VSK                    | [0ed7feaa05](https://linux-hardware.org/?probe=0ed7feaa05) | Aug 01, 2023 |
| Lenovo        | Legion 5 15ARH7 82RE        | [e1a79e094e](https://linux-hardware.org/?probe=e1a79e094e) | Aug 01, 2023 |
| Dell          | Inspiron 5567               | [d252fa93be](https://linux-hardware.org/?probe=d252fa93be) | Aug 01, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [9fbfc590ad](https://linux-hardware.org/?probe=9fbfc590ad) | Aug 01, 2023 |
| Dell          | Latitude 3500               | [df5211a816](https://linux-hardware.org/?probe=df5211a816) | Aug 01, 2023 |
| Dell          | Latitude 5490               | [e24a9f877c](https://linux-hardware.org/?probe=e24a9f877c) | Aug 01, 2023 |
| System76      | Lemur Pro                   | [1ba844bc69](https://linux-hardware.org/?probe=1ba844bc69) | Aug 01, 2023 |
| System76      | Lemur Pro                   | [e019d33faf](https://linux-hardware.org/?probe=e019d33faf) | Aug 01, 2023 |
| MSI           | Katana GF66 12UC            | [d590bcd619](https://linux-hardware.org/?probe=d590bcd619) | Jul 31, 2023 |
| ASUSTek       | K95VM                       | [1ec08c4cf9](https://linux-hardware.org/?probe=1ec08c4cf9) | Jul 30, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [60cfcb00e9](https://linux-hardware.org/?probe=60cfcb00e9) | Jul 30, 2023 |
| Dell          | Latitude E7440              | [7509a5f756](https://linux-hardware.org/?probe=7509a5f756) | Jul 30, 2023 |
| System76      | Darter Pro                  | [0220d19f38](https://linux-hardware.org/?probe=0220d19f38) | Jul 30, 2023 |
| Dell          | Latitude E7240              | [b794bcdde6](https://linux-hardware.org/?probe=b794bcdde6) | Jul 29, 2023 |
| HP            | Pavilion 11 x360 PC         | [d693783e7a](https://linux-hardware.org/?probe=d693783e7a) | Jul 29, 2023 |
| Unknown       | Unknown                     | [73836c0a75](https://linux-hardware.org/?probe=73836c0a75) | Jul 29, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [59f0eb6b57](https://linux-hardware.org/?probe=59f0eb6b57) | Jul 28, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [cb2f78abf0](https://linux-hardware.org/?probe=cb2f78abf0) | Jul 28, 2023 |
| Dell          | Precision 3550              | [0ecac77f90](https://linux-hardware.org/?probe=0ecac77f90) | Jul 28, 2023 |
| Dell          | Precision 3550              | [95ae018833](https://linux-hardware.org/?probe=95ae018833) | Jul 28, 2023 |
| System76      | Oryx Pro                    | [0ad8c1d8a7](https://linux-hardware.org/?probe=0ad8c1d8a7) | Jul 28, 2023 |
| Acer          | Aspire A315-42G             | [0e3aa83494](https://linux-hardware.org/?probe=0e3aa83494) | Jul 28, 2023 |
| HP            | EliteBook 840 G3            | [5a1f6f3395](https://linux-hardware.org/?probe=5a1f6f3395) | Jul 27, 2023 |
| Dell          | G15 5520                    | [7a5b503737](https://linux-hardware.org/?probe=7a5b503737) | Jul 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [4152e1f98e](https://linux-hardware.org/?probe=4152e1f98e) | Jul 27, 2023 |
| Dell          | Latitude E7440              | [619c6e4b99](https://linux-hardware.org/?probe=619c6e4b99) | Jul 27, 2023 |
| Samsung       | 300E5M/300E5L               | [23b23d59aa](https://linux-hardware.org/?probe=23b23d59aa) | Jul 27, 2023 |
| HP            | Dev One Notebook PC         | [b54bb52258](https://linux-hardware.org/?probe=b54bb52258) | Jul 27, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [9920824f1f](https://linux-hardware.org/?probe=9920824f1f) | Jul 27, 2023 |
| Acer          | Nitro AN515-55              | [00e9bb8973](https://linux-hardware.org/?probe=00e9bb8973) | Jul 26, 2023 |
| Dell          | Inspiron 5548               | [22b2519a90](https://linux-hardware.org/?probe=22b2519a90) | Jul 26, 2023 |
| Acer          | Aspire A515-56              | [7e0e30c1cf](https://linux-hardware.org/?probe=7e0e30c1cf) | Jul 26, 2023 |
| Dell          | Inspiron 5548               | [b583a1fbee](https://linux-hardware.org/?probe=b583a1fbee) | Jul 26, 2023 |
| Dell          | Inspiron 5548               | [3d3696e8fa](https://linux-hardware.org/?probe=3d3696e8fa) | Jul 25, 2023 |
| HP            | Laptop 14-bs0xx             | [e074ee90be](https://linux-hardware.org/?probe=e074ee90be) | Jul 25, 2023 |
| MSI           | GF63 Thin 10SCXR            | [b34b7fa5fb](https://linux-hardware.org/?probe=b34b7fa5fb) | Jul 25, 2023 |
| Dell          | Inspiron 5490               | [25f155c61a](https://linux-hardware.org/?probe=25f155c61a) | Jul 24, 2023 |
| Dell          | Inspiron 5490               | [6b80b41fee](https://linux-hardware.org/?probe=6b80b41fee) | Jul 24, 2023 |
| Dell          | XPS 15 7590                 | [fa64a82283](https://linux-hardware.org/?probe=fa64a82283) | Jul 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [88cfdb061d](https://linux-hardware.org/?probe=88cfdb061d) | Jul 24, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [61c84247e6](https://linux-hardware.org/?probe=61c84247e6) | Jul 24, 2023 |
| Apple         | MacBookAir4,2               | [e220379405](https://linux-hardware.org/?probe=e220379405) | Jul 24, 2023 |
| ASUSTek       | ROG Strix G533ZW_G533ZW     | [53bab7ac5e](https://linux-hardware.org/?probe=53bab7ac5e) | Jul 24, 2023 |
| Apple         | MacBookPro5,5               | [b2b0895194](https://linux-hardware.org/?probe=b2b0895194) | Jul 24, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [3d8ec4447b](https://linux-hardware.org/?probe=3d8ec4447b) | Jul 24, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [fe2ff0c21f](https://linux-hardware.org/?probe=fe2ff0c21f) | Jul 23, 2023 |
| Apple         | MacBookPro8,1               | [2cd0946aba](https://linux-hardware.org/?probe=2cd0946aba) | Jul 23, 2023 |
| Sony          | SVF1521A6EW                 | [3c39100c6f](https://linux-hardware.org/?probe=3c39100c6f) | Jul 23, 2023 |
| PC Special... | Standard                    | [992aec5bb8](https://linux-hardware.org/?probe=992aec5bb8) | Jul 23, 2023 |
| HP            | ZBook Studio G3             | [bcfc5b64f4](https://linux-hardware.org/?probe=bcfc5b64f4) | Jul 23, 2023 |
| Google        | Snappy                      | [a3e6774e43](https://linux-hardware.org/?probe=a3e6774e43) | Jul 23, 2023 |
| Dell          | Latitude 3500               | [0755576e96](https://linux-hardware.org/?probe=0755576e96) | Jul 22, 2023 |
| Dell          | Latitude E6430s             | [8e74e2a524](https://linux-hardware.org/?probe=8e74e2a524) | Jul 22, 2023 |
| Dell          | Vostro 3560                 | [05acc63d53](https://linux-hardware.org/?probe=05acc63d53) | Jul 22, 2023 |
| Dell          | Latitude 5410               | [82217114b4](https://linux-hardware.org/?probe=82217114b4) | Jul 21, 2023 |
| Dell          | Latitude 5520               | [070380568b](https://linux-hardware.org/?probe=070380568b) | Jul 21, 2023 |
| Dell          | Precision 7530              | [0d2e753768](https://linux-hardware.org/?probe=0d2e753768) | Jul 20, 2023 |
| Acer          | Aspire A515-52              | [243f0a8cab](https://linux-hardware.org/?probe=243f0a8cab) | Jul 20, 2023 |
| Acer          | Aspire A515-52              | [f310abe0bb](https://linux-hardware.org/?probe=f310abe0bb) | Jul 20, 2023 |
| HP            | Pavilion Plus Laptop 14-... | [937715a75f](https://linux-hardware.org/?probe=937715a75f) | Jul 20, 2023 |
| Dell          | Latitude E5270              | [9ea13fdc27](https://linux-hardware.org/?probe=9ea13fdc27) | Jul 20, 2023 |
| HP            | Laptop 15-da0xxx            | [6e17b916ee](https://linux-hardware.org/?probe=6e17b916ee) | Jul 20, 2023 |
| Acer          | Extensa 5635ZG              | [337f0cec05](https://linux-hardware.org/?probe=337f0cec05) | Jul 20, 2023 |
| Toshiba       | Satellite L750              | [662f89dcc3](https://linux-hardware.org/?probe=662f89dcc3) | Jul 20, 2023 |
| Dell          | XPS 13 9360                 | [ac1a8eea0e](https://linux-hardware.org/?probe=ac1a8eea0e) | Jul 19, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [35944db669](https://linux-hardware.org/?probe=35944db669) | Jul 19, 2023 |
| Schenker      | XMG NEO (CML/E20)           | [9f99e57705](https://linux-hardware.org/?probe=9f99e57705) | Jul 19, 2023 |
| ASUSTek       | K53E                        | [7fddec038e](https://linux-hardware.org/?probe=7fddec038e) | Jul 19, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [8cb16d19aa](https://linux-hardware.org/?probe=8cb16d19aa) | Jul 19, 2023 |
| Notebook      | NH5x_7xDPx                  | [098f2f58c7](https://linux-hardware.org/?probe=098f2f58c7) | Jul 18, 2023 |
| Apple         | MacBookPro16,1              | [dd5d384a71](https://linux-hardware.org/?probe=dd5d384a71) | Jul 18, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | [f5dc246f7c](https://linux-hardware.org/?probe=f5dc246f7c) | Jul 18, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | [abec03689c](https://linux-hardware.org/?probe=abec03689c) | Jul 18, 2023 |
| ASRock        | Z77 Performance             | [585aaad9ad](https://linux-hardware.org/?probe=585aaad9ad) | Jul 18, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [1cffa4bad9](https://linux-hardware.org/?probe=1cffa4bad9) | Jul 18, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [cdaad6fa25](https://linux-hardware.org/?probe=cdaad6fa25) | Jul 18, 2023 |
| HP            | 635                         | [500e11147e](https://linux-hardware.org/?probe=500e11147e) | Jul 18, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [1426cda0a7](https://linux-hardware.org/?probe=1426cda0a7) | Jul 17, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [c7a062709f](https://linux-hardware.org/?probe=c7a062709f) | Jul 17, 2023 |
| HUAWEI        | KLVC-WXX9                   | [0427f16143](https://linux-hardware.org/?probe=0427f16143) | Jul 17, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [0bbd5c68bb](https://linux-hardware.org/?probe=0bbd5c68bb) | Jul 17, 2023 |
| Dell          | Precision M6800             | [8ddd80db6c](https://linux-hardware.org/?probe=8ddd80db6c) | Jul 17, 2023 |
| Lenovo        | ThinkPad X390 20Q1S67S00    | [be43004463](https://linux-hardware.org/?probe=be43004463) | Jul 17, 2023 |
| System76      | Serval WS                   | [a916a92726](https://linux-hardware.org/?probe=a916a92726) | Jul 17, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [55a5100039](https://linux-hardware.org/?probe=55a5100039) | Jul 16, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [ad8f031cb2](https://linux-hardware.org/?probe=ad8f031cb2) | Jul 16, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [51128412d5](https://linux-hardware.org/?probe=51128412d5) | Jul 16, 2023 |
| Lenovo        | Legion Slim 7 16IRH8 82Y... | [437209972c](https://linux-hardware.org/?probe=437209972c) | Jul 15, 2023 |
| Lenovo        | ThinkPad T480 20L5S1S000    | [91dbb2c969](https://linux-hardware.org/?probe=91dbb2c969) | Jul 15, 2023 |
| Dell          | G15 5510                    | [28b7a732f2](https://linux-hardware.org/?probe=28b7a732f2) | Jul 15, 2023 |
| System76      | Pangolin                    | [486df7ead2](https://linux-hardware.org/?probe=486df7ead2) | Jul 14, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [0498e27f41](https://linux-hardware.org/?probe=0498e27f41) | Jul 14, 2023 |
| HP            | ENVY 15                     | [5cfb9d33bd](https://linux-hardware.org/?probe=5cfb9d33bd) | Jul 14, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [21fc63e4dd](https://linux-hardware.org/?probe=21fc63e4dd) | Jul 14, 2023 |
| MSI           | GF63 Thin 10SC              | [d017610254](https://linux-hardware.org/?probe=d017610254) | Jul 14, 2023 |
| Lenovo        | Legion 7 16ITHg6 82K6       | [e53c63af42](https://linux-hardware.org/?probe=e53c63af42) | Jul 14, 2023 |
| Lenovo        | ThinkPad T530 23943J8       | [fb022ada73](https://linux-hardware.org/?probe=fb022ada73) | Jul 14, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [e84bf83ac1](https://linux-hardware.org/?probe=e84bf83ac1) | Jul 13, 2023 |
| HP            | Compaq CQ58                 | [78977dd4de](https://linux-hardware.org/?probe=78977dd4de) | Jul 13, 2023 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [7ef2028b06](https://linux-hardware.org/?probe=7ef2028b06) | Jul 13, 2023 |
| Acer          | Aspire E5-576G              | [0856b48ae7](https://linux-hardware.org/?probe=0856b48ae7) | Jul 13, 2023 |
| Acer          | Swift SF314-42              | [c82bb58705](https://linux-hardware.org/?probe=c82bb58705) | Jul 13, 2023 |
| Lenovo        | ThinkPad P53s 20N6001UUS    | [5a675551df](https://linux-hardware.org/?probe=5a675551df) | Jul 13, 2023 |
| Dell          | G3 3590                     | [089bfa3da7](https://linux-hardware.org/?probe=089bfa3da7) | Jul 13, 2023 |
| Apple         | MacBookPro8,1               | [d4910e3f43](https://linux-hardware.org/?probe=d4910e3f43) | Jul 13, 2023 |
| Acer          | Swift SF314-42              | [7a9624e7cc](https://linux-hardware.org/?probe=7a9624e7cc) | Jul 12, 2023 |
| Acer          | Swift SF314-58G             | [795625662c](https://linux-hardware.org/?probe=795625662c) | Jul 12, 2023 |
| Acer          | Swift SF314-58G             | [c01b74af46](https://linux-hardware.org/?probe=c01b74af46) | Jul 12, 2023 |
| Timi          | Xiaomi NoteBook Pro         | [618c0c975b](https://linux-hardware.org/?probe=618c0c975b) | Jul 12, 2023 |
| HP            | Laptop 17-cp0xxx            | [801537f1d4](https://linux-hardware.org/?probe=801537f1d4) | Jul 12, 2023 |
| Apple         | MacBookPro6,2               | [20e2180dc1](https://linux-hardware.org/?probe=20e2180dc1) | Jul 12, 2023 |
| MSI           | Cyborg 15 A12VF             | [2c4a8d9d63](https://linux-hardware.org/?probe=2c4a8d9d63) | Jul 12, 2023 |
| Lenovo        | ThinkPad T470s 20HGS01A0... | [54e51170a1](https://linux-hardware.org/?probe=54e51170a1) | Jul 11, 2023 |
| Apple         | MacBookAir3,2               | [cbfc272e87](https://linux-hardware.org/?probe=cbfc272e87) | Jul 11, 2023 |
| HP            | EliteBook 850 G6            | [556ef4473f](https://linux-hardware.org/?probe=556ef4473f) | Jul 11, 2023 |
| HP            | EliteBook 840 G6            | [a61e80c022](https://linux-hardware.org/?probe=a61e80c022) | Jul 11, 2023 |
| Apple         | MacBookAir7,2               | [1453f984c9](https://linux-hardware.org/?probe=1453f984c9) | Jul 11, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [5a7dbc5d7c](https://linux-hardware.org/?probe=5a7dbc5d7c) | Jul 10, 2023 |
| Apple         | MacBookPro6,2               | [293ddc3253](https://linux-hardware.org/?probe=293ddc3253) | Jul 10, 2023 |
| Notebook      | NP5x_NP6x_NP7xRNJ_RNH       | [7663e77bff](https://linux-hardware.org/?probe=7663e77bff) | Jul 09, 2023 |
| Notebook      | P7xxTM1                     | [81c163ed4a](https://linux-hardware.org/?probe=81c163ed4a) | Jul 09, 2023 |
| HP            | Laptop 14s-fq0xxx           | [92feea0533](https://linux-hardware.org/?probe=92feea0533) | Jul 08, 2023 |
| HP            | Laptop 14s-fq0xxx           | [2287c62944](https://linux-hardware.org/?probe=2287c62944) | Jul 08, 2023 |
| Toshiba       | IS 1413G                    | [cf96aafbc0](https://linux-hardware.org/?probe=cf96aafbc0) | Jul 08, 2023 |
| Apple         | MacBookPro11,1              | [1f88a40c05](https://linux-hardware.org/?probe=1f88a40c05) | Jul 08, 2023 |
| Apple         | MacBookPro11,1              | [e1f22afb69](https://linux-hardware.org/?probe=e1f22afb69) | Jul 08, 2023 |
| MSI           | Cyborg 15 A12VF             | [a34d0d8290](https://linux-hardware.org/?probe=a34d0d8290) | Jul 08, 2023 |
| Dell          | Inspiron 5565               | [d1df053096](https://linux-hardware.org/?probe=d1df053096) | Jul 08, 2023 |
| Acer          | Nitro AN515-57              | [12e3f9ecc7](https://linux-hardware.org/?probe=12e3f9ecc7) | Jul 07, 2023 |
| ASUSTek       | N55SL                       | [1223d8b536](https://linux-hardware.org/?probe=1223d8b536) | Jul 07, 2023 |
| MSI           | GS66 Stealth 10SE           | [e689bf355c](https://linux-hardware.org/?probe=e689bf355c) | Jul 07, 2023 |
| Panasonic     | FZ55-1                      | [4d12f02737](https://linux-hardware.org/?probe=4d12f02737) | Jul 07, 2023 |
| Dell          | Inspiron 3501               | [e657049abf](https://linux-hardware.org/?probe=e657049abf) | Jul 06, 2023 |
| Toshiba       | IS 1413G                    | [f2a99b72dc](https://linux-hardware.org/?probe=f2a99b72dc) | Jul 06, 2023 |
| Acer          | Predator PT515-51           | [9971e8a3da](https://linux-hardware.org/?probe=9971e8a3da) | Jul 05, 2023 |
| HP            | Laptop 15-da0xxx            | [f634e3942a](https://linux-hardware.org/?probe=f634e3942a) | Jul 05, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | [46e6f4b081](https://linux-hardware.org/?probe=46e6f4b081) | Jul 05, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | [6bf093ef61](https://linux-hardware.org/?probe=6bf093ef61) | Jul 05, 2023 |
| Dell          | XPS 17 9720                 | [a99946b8f0](https://linux-hardware.org/?probe=a99946b8f0) | Jul 04, 2023 |
| HP            | OMEN by Laptop 17-cb1xxx    | [dbf87e0eec](https://linux-hardware.org/?probe=dbf87e0eec) | Jul 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [09dffdde54](https://linux-hardware.org/?probe=09dffdde54) | Jul 04, 2023 |
| MSI           | Cyborg 15 A12VF             | [156f923a72](https://linux-hardware.org/?probe=156f923a72) | Jul 04, 2023 |
| Acer          | Aspire E1-470G              | [db4125a1c5](https://linux-hardware.org/?probe=db4125a1c5) | Jul 04, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [dda9b242fd](https://linux-hardware.org/?probe=dda9b242fd) | Jul 03, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [e8ff92b585](https://linux-hardware.org/?probe=e8ff92b585) | Jul 03, 2023 |
| Acer          | Aspire A515-52              | [3861c91dd4](https://linux-hardware.org/?probe=3861c91dd4) | Jul 02, 2023 |
| Acer          | Aspire A515-52              | [ab8898b9f3](https://linux-hardware.org/?probe=ab8898b9f3) | Jul 02, 2023 |
| Apple         | MacBookPro12,1              | [f89bdd4374](https://linux-hardware.org/?probe=f89bdd4374) | Jul 02, 2023 |
| Dell          | Precision 7510              | [46b90e25b0](https://linux-hardware.org/?probe=46b90e25b0) | Jul 02, 2023 |
| MSI           | GT72VR 6RD                  | [ea6887d031](https://linux-hardware.org/?probe=ea6887d031) | Jul 01, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [6ee8b4e949](https://linux-hardware.org/?probe=6ee8b4e949) | Jul 01, 2023 |
| Dell          | Latitude 3500               | [8293ebc591](https://linux-hardware.org/?probe=8293ebc591) | Jul 01, 2023 |
| Toshiba       | IS 1413G                    | [b95a7c049a](https://linux-hardware.org/?probe=b95a7c049a) | Jun 30, 2023 |
| Teclast       | F7 Plus                     | [cebd3b027c](https://linux-hardware.org/?probe=cebd3b027c) | Jun 30, 2023 |
| Dell          | XPS 13 9370                 | [ec4bf131f5](https://linux-hardware.org/?probe=ec4bf131f5) | Jun 30, 2023 |
| Positivo      | Mobile                      | [fdaaf6915b](https://linux-hardware.org/?probe=fdaaf6915b) | Jun 30, 2023 |
| MSI           | GS65 Stealth 9SD            | [568380fd59](https://linux-hardware.org/?probe=568380fd59) | Jun 30, 2023 |
| MSI           | GS65 Stealth 9SD            | [54013b2dfd](https://linux-hardware.org/?probe=54013b2dfd) | Jun 30, 2023 |
| Positivo      | H14CU02                     | [d50e6fbbdc](https://linux-hardware.org/?probe=d50e6fbbdc) | Jun 29, 2023 |
| ASRock        | Z77 Performance             | [a678dc9605](https://linux-hardware.org/?probe=a678dc9605) | Jun 29, 2023 |
| MSI           | Vector GP76 12UH            | [b7035d78a6](https://linux-hardware.org/?probe=b7035d78a6) | Jun 29, 2023 |
| MSI           | GE70 2PL                    | [e5354b6cb4](https://linux-hardware.org/?probe=e5354b6cb4) | Jun 28, 2023 |
| Acer          | Aspire A315-21              | [4bf524cd80](https://linux-hardware.org/?probe=4bf524cd80) | Jun 27, 2023 |
| Acer          | Aspire E1-571               | [894f8583ea](https://linux-hardware.org/?probe=894f8583ea) | Jun 27, 2023 |
| Dell          | Vostro 15 3510              | [adb3a3de68](https://linux-hardware.org/?probe=adb3a3de68) | Jun 27, 2023 |
| Dell          | Precision M6800             | [b0fe737883](https://linux-hardware.org/?probe=b0fe737883) | Jun 27, 2023 |
| Toshiba       | IS 1413G                    | [882bd512a2](https://linux-hardware.org/?probe=882bd512a2) | Jun 27, 2023 |
| ASUSTek       | X550JX                      | [80770014b8](https://linux-hardware.org/?probe=80770014b8) | Jun 27, 2023 |
| Dell          | Inspiron 3583               | [e1e76b3d77](https://linux-hardware.org/?probe=e1e76b3d77) | Jun 27, 2023 |
| HUAWEI        | KLVL-WXXW                   | [5454a08ba6](https://linux-hardware.org/?probe=5454a08ba6) | Jun 26, 2023 |
| Lenovo        | ThinkPad P53 20QQS34C04     | [3019d7a733](https://linux-hardware.org/?probe=3019d7a733) | Jun 26, 2023 |
| Apple         | MacBookAir6,1               | [6b44c8513d](https://linux-hardware.org/?probe=6b44c8513d) | Jun 26, 2023 |
| Dell          | Precision M6800             | [4e6c5423b1](https://linux-hardware.org/?probe=4e6c5423b1) | Jun 25, 2023 |
| Dell          | Precision M6800             | [feb0adfd99](https://linux-hardware.org/?probe=feb0adfd99) | Jun 25, 2023 |
| HP            | Notebook                    | [ea00ce6c5b](https://linux-hardware.org/?probe=ea00ce6c5b) | Jun 25, 2023 |
| Sony          | VPCEA23FB                   | [b9a835920f](https://linux-hardware.org/?probe=b9a835920f) | Jun 25, 2023 |
| Sony          | VPCEA23FB                   | [c462c4c75e](https://linux-hardware.org/?probe=c462c4c75e) | Jun 25, 2023 |
| HP            | ENVY NOTEBOOK PC            | [8bd62ffdf1](https://linux-hardware.org/?probe=8bd62ffdf1) | Jun 25, 2023 |
| Acer          | Swift SF314-512             | [12f361cd8c](https://linux-hardware.org/?probe=12f361cd8c) | Jun 24, 2023 |
| System76      | Oryx Pro                    | [eaa4d8e105](https://linux-hardware.org/?probe=eaa4d8e105) | Jun 24, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [737204f453](https://linux-hardware.org/?probe=737204f453) | Jun 24, 2023 |
| MSI           | Cyborg 15 A12VF             | [703e12843e](https://linux-hardware.org/?probe=703e12843e) | Jun 23, 2023 |
| HP            | Laptop 15-dw2xxx            | [7f41e23d3a](https://linux-hardware.org/?probe=7f41e23d3a) | Jun 23, 2023 |
| HP            | Laptop 15-dw2xxx            | [79ec1a7b3f](https://linux-hardware.org/?probe=79ec1a7b3f) | Jun 23, 2023 |
| Dell          | XPS 15 9500                 | [36dc72c683](https://linux-hardware.org/?probe=36dc72c683) | Jun 23, 2023 |
| ASUSTek       | X751LD                      | [c7be73b6ca](https://linux-hardware.org/?probe=c7be73b6ca) | Jun 23, 2023 |
| ASUSTek       | X751LD                      | [346bbb0b47](https://linux-hardware.org/?probe=346bbb0b47) | Jun 23, 2023 |
| MSI           | Alpha 15 A3DDK              | [410b20161b](https://linux-hardware.org/?probe=410b20161b) | Jun 23, 2023 |
| Dell          | Inspiron 3501               | [e8db86e014](https://linux-hardware.org/?probe=e8db86e014) | Jun 22, 2023 |
| ASUSTek       | X551MA                      | [5b2b7d4a7f](https://linux-hardware.org/?probe=5b2b7d4a7f) | Jun 22, 2023 |
| Dell          | Inspiron 3583               | [170d1f4f0b](https://linux-hardware.org/?probe=170d1f4f0b) | Jun 22, 2023 |
| HP            | Notebook                    | [35b8a2a187](https://linux-hardware.org/?probe=35b8a2a187) | Jun 22, 2023 |
| Lenovo        | B5400 80B6QB0               | [6885fc56aa](https://linux-hardware.org/?probe=6885fc56aa) | Jun 22, 2023 |
| Dell          | Inspiron 5567               | [8634954b1c](https://linux-hardware.org/?probe=8634954b1c) | Jun 22, 2023 |
| Acer          | Aspire A515-52              | [43ee82258d](https://linux-hardware.org/?probe=43ee82258d) | Jun 21, 2023 |
| Dell          | System Inspiron N4110       | [ebaceedccf](https://linux-hardware.org/?probe=ebaceedccf) | Jun 21, 2023 |
| Lenovo        | ThinkPad T480 20L6S3H102    | [4a8bd602ff](https://linux-hardware.org/?probe=4a8bd602ff) | Jun 21, 2023 |
| Dell          | System Inspiron N4110       | [a168f45822](https://linux-hardware.org/?probe=a168f45822) | Jun 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [b255195205](https://linux-hardware.org/?probe=b255195205) | Jun 21, 2023 |
| Acer          | Aspire A515-52              | [b2d464d2bc](https://linux-hardware.org/?probe=b2d464d2bc) | Jun 21, 2023 |
| Toshiba       | IS 1413G                    | [14296e98e7](https://linux-hardware.org/?probe=14296e98e7) | Jun 21, 2023 |
| Dell          | Latitude E7240              | [f8b3fce80b](https://linux-hardware.org/?probe=f8b3fce80b) | Jun 21, 2023 |
| HP            | Pavilion Laptop 15t-eg00... | [383aed9129](https://linux-hardware.org/?probe=383aed9129) | Jun 20, 2023 |
| HP            | Pavilion Laptop 15t-eg00... | [3996492e80](https://linux-hardware.org/?probe=3996492e80) | Jun 20, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | [1c9456fd1d](https://linux-hardware.org/?probe=1c9456fd1d) | Jun 20, 2023 |
| System76      | Lemur Pro                   | [5074769fee](https://linux-hardware.org/?probe=5074769fee) | Jun 19, 2023 |
| Dell          | Latitude 7430               | [84f66041f9](https://linux-hardware.org/?probe=84f66041f9) | Jun 19, 2023 |
| MSI           | Bravo 15 B5DD               | [5a89024be5](https://linux-hardware.org/?probe=5a89024be5) | Jun 19, 2023 |
| Dell          | XPS 15 9510                 | [347c5ce944](https://linux-hardware.org/?probe=347c5ce944) | Jun 19, 2023 |
| HP            | Laptop 15-dy2xxx            | [0699537327](https://linux-hardware.org/?probe=0699537327) | Jun 19, 2023 |
| MSI           | Raider GE66 12UGS           | [73b20b76a3](https://linux-hardware.org/?probe=73b20b76a3) | Jun 19, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [f93c91b6d9](https://linux-hardware.org/?probe=f93c91b6d9) | Jun 18, 2023 |
| Acer          | Aspire 5750G                | [4f35e25c20](https://linux-hardware.org/?probe=4f35e25c20) | Jun 18, 2023 |
| Lenovo        | Flex 2-15 20405             | [ae0a1a134a](https://linux-hardware.org/?probe=ae0a1a134a) | Jun 18, 2023 |
| HONOR         | BRN-FXX                     | [d3671dca6a](https://linux-hardware.org/?probe=d3671dca6a) | Jun 18, 2023 |
| Avell High... | A70 HYB                     | [10eb079da8](https://linux-hardware.org/?probe=10eb079da8) | Jun 17, 2023 |
| ASUSTek       | ASUSPRO P5440UF             | [cf08c655b9](https://linux-hardware.org/?probe=cf08c655b9) | Jun 17, 2023 |
| Acer          | Aspire 4752                 | [441eb3fe51](https://linux-hardware.org/?probe=441eb3fe51) | Jun 17, 2023 |
| ASUSTek       | ASUSPRO P5440UF             | [272d8de237](https://linux-hardware.org/?probe=272d8de237) | Jun 16, 2023 |
| HP            | Laptop 14-bp0xx             | [fd6b492010](https://linux-hardware.org/?probe=fd6b492010) | Jun 16, 2023 |
| HP            | Pavilion dv6                | [55c83ec890](https://linux-hardware.org/?probe=55c83ec890) | Jun 15, 2023 |
| Dell          | Vostro 3420                 | [c1b8b07db0](https://linux-hardware.org/?probe=c1b8b07db0) | Jun 15, 2023 |
| System76      | Gazelle                     | [79c4236cdd](https://linux-hardware.org/?probe=79c4236cdd) | Jun 15, 2023 |
| HP            | Laptop 14-dk0xxx            | [1e6fdd560b](https://linux-hardware.org/?probe=1e6fdd560b) | Jun 14, 2023 |
| Lenovo        | ThinkPad P53s 20N6001UUS    | [667f0a20c1](https://linux-hardware.org/?probe=667f0a20c1) | Jun 14, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [17c4d68066](https://linux-hardware.org/?probe=17c4d68066) | Jun 14, 2023 |
| System76      | Gazelle                     | [117f199b15](https://linux-hardware.org/?probe=117f199b15) | Jun 14, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [d7c90a9c25](https://linux-hardware.org/?probe=d7c90a9c25) | Jun 13, 2023 |
| Acer          | Swift SFX14-51G             | [c17f7d87b3](https://linux-hardware.org/?probe=c17f7d87b3) | Jun 13, 2023 |
| Dell          | Vostro 5470                 | [b5294ee338](https://linux-hardware.org/?probe=b5294ee338) | Jun 13, 2023 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | [fff5e11f1c](https://linux-hardware.org/?probe=fff5e11f1c) | Jun 13, 2023 |
| TUXEDO        | Unknown                     | [d730799661](https://linux-hardware.org/?probe=d730799661) | Jun 12, 2023 |
| Dell          | Latitude E7470              | [1253de4554](https://linux-hardware.org/?probe=1253de4554) | Jun 12, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81G3      | [c09c4a0f69](https://linux-hardware.org/?probe=c09c4a0f69) | Jun 12, 2023 |
| Toshiba       | Satellite P55t-B            | [efc0f87778](https://linux-hardware.org/?probe=efc0f87778) | Jun 11, 2023 |
| HP            | Stream Laptop 11-ah0XX      | [a3e566ad38](https://linux-hardware.org/?probe=a3e566ad38) | Jun 11, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | [fd388e00c3](https://linux-hardware.org/?probe=fd388e00c3) | Jun 10, 2023 |
| Samsung       | 550XCJ/550XCR               | [d8dac01c79](https://linux-hardware.org/?probe=d8dac01c79) | Jun 10, 2023 |
| Lenovo        | ThinkPad T540p 20BFS4P80... | [4160d59c4f](https://linux-hardware.org/?probe=4160d59c4f) | Jun 10, 2023 |
| Acer          | Aspire 7750                 | [b0daafa057](https://linux-hardware.org/?probe=b0daafa057) | Jun 09, 2023 |
| Dell          | Latitude E7240              | [e21cc2151b](https://linux-hardware.org/?probe=e21cc2151b) | Jun 08, 2023 |
| Dell          | Latitude E6420              | [d408418ddd](https://linux-hardware.org/?probe=d408418ddd) | Jun 08, 2023 |
| Acer          | Aspire A515-45              | [975246674d](https://linux-hardware.org/?probe=975246674d) | Jun 08, 2023 |
| Acer          | Aspire A515-45              | [348173e172](https://linux-hardware.org/?probe=348173e172) | Jun 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [e355aa21b5](https://linux-hardware.org/?probe=e355aa21b5) | Jun 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [c5a1a47343](https://linux-hardware.org/?probe=c5a1a47343) | Jun 08, 2023 |
| HP            | Pavilion dv7                | [896e71aaaf](https://linux-hardware.org/?probe=896e71aaaf) | Jun 08, 2023 |
| Machcreato... | 14                          | [d889b02b13](https://linux-hardware.org/?probe=d889b02b13) | Jun 07, 2023 |
| Toshiba       | IS 1413G                    | [cc023db7a9](https://linux-hardware.org/?probe=cc023db7a9) | Jun 07, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [ee9c6252ae](https://linux-hardware.org/?probe=ee9c6252ae) | Jun 07, 2023 |
| Fujitsu       | LIFEBOOK E5512A             | [7381bd00f3](https://linux-hardware.org/?probe=7381bd00f3) | Jun 07, 2023 |
| Dell          | Latitude E6420              | [620ca905d2](https://linux-hardware.org/?probe=620ca905d2) | Jun 07, 2023 |
| Machcreato... | 14                          | [f0a27a9f97](https://linux-hardware.org/?probe=f0a27a9f97) | Jun 06, 2023 |
| Lenovo        | ThinkPad T480s 20L8S3JE0... | [2834fee64f](https://linux-hardware.org/?probe=2834fee64f) | Jun 06, 2023 |
| HP            | Laptop 14-cf2xxx            | [e6bf4ead0a](https://linux-hardware.org/?probe=e6bf4ead0a) | Jun 06, 2023 |
| Lenovo        | ThinkPad W520 427637U       | [1bec07891b](https://linux-hardware.org/?probe=1bec07891b) | Jun 05, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [841eeea3f9](https://linux-hardware.org/?probe=841eeea3f9) | Jun 05, 2023 |
| Apple         | MacBookAir4,2               | [afc9f50009](https://linux-hardware.org/?probe=afc9f50009) | Jun 05, 2023 |
| Apple         | MacBook5,1                  | [804abce033](https://linux-hardware.org/?probe=804abce033) | Jun 05, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [f53388e7df](https://linux-hardware.org/?probe=f53388e7df) | Jun 05, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [6c151a9750](https://linux-hardware.org/?probe=6c151a9750) | Jun 05, 2023 |
| HP            | 15 Notebook PC              | [7c76016c9d](https://linux-hardware.org/?probe=7c76016c9d) | Jun 05, 2023 |
| Lenovo        | ThinkPad T540p 20BFS4P80... | [5dd18339de](https://linux-hardware.org/?probe=5dd18339de) | Jun 05, 2023 |
| Dell          | Inspiron 5437               | [d805b4ec1f](https://linux-hardware.org/?probe=d805b4ec1f) | Jun 03, 2023 |
| Dell          | Inspiron 7472               | [53b9d0dfa6](https://linux-hardware.org/?probe=53b9d0dfa6) | Jun 03, 2023 |
| Dell          | XPS 17 9720                 | [71c4a65aae](https://linux-hardware.org/?probe=71c4a65aae) | Jun 03, 2023 |
| System76      | Oryx Pro                    | [b3b398ba61](https://linux-hardware.org/?probe=b3b398ba61) | Jun 03, 2023 |
| MSI           | Prestige 16 A12UD           | [b13e4f0242](https://linux-hardware.org/?probe=b13e4f0242) | Jun 02, 2023 |
| Acer          | Predator PH517-51           | [1de529b11c](https://linux-hardware.org/?probe=1de529b11c) | Jun 01, 2023 |
| HUAWEI        | CREM-WXX9                   | [c33f531350](https://linux-hardware.org/?probe=c33f531350) | Jun 01, 2023 |
| System76      | Adder WS                    | [5cfa553a01](https://linux-hardware.org/?probe=5cfa553a01) | May 31, 2023 |
| Toshiba       | IS 1413G                    | [d950f8b732](https://linux-hardware.org/?probe=d950f8b732) | May 31, 2023 |
| Acer          | Predator PH517-51           | [cc24e32ab1](https://linux-hardware.org/?probe=cc24e32ab1) | May 30, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [907448944d](https://linux-hardware.org/?probe=907448944d) | May 30, 2023 |
| Lenovo        | ThinkPad T440p 20ANCTO1W... | [83f869ee2a](https://linux-hardware.org/?probe=83f869ee2a) | May 30, 2023 |
| Lenovo        | ThinkPad T440p 20ANCTO1W... | [23af21bb34](https://linux-hardware.org/?probe=23af21bb34) | May 30, 2023 |
| Toshiba       | Satellite P755              | [5dc8f46db5](https://linux-hardware.org/?probe=5dc8f46db5) | May 29, 2023 |
| Avell High... | A70 MOB                     | [70e4c12911](https://linux-hardware.org/?probe=70e4c12911) | May 29, 2023 |
| Dell          | XPS 15 9510                 | [bcad978a06](https://linux-hardware.org/?probe=bcad978a06) | May 29, 2023 |
| Dell          | XPS 15 9510                 | [331bbabc0e](https://linux-hardware.org/?probe=331bbabc0e) | May 29, 2023 |
| Apple         | MacBookAir5,1               | [4fc496bcc4](https://linux-hardware.org/?probe=4fc496bcc4) | May 29, 2023 |
| Lenovo        | ThinkPad T500 2056Y4R       | [dbd22d38bd](https://linux-hardware.org/?probe=dbd22d38bd) | May 28, 2023 |
| System76      | Adder WS                    | [d6de84e0c6](https://linux-hardware.org/?probe=d6de84e0c6) | May 28, 2023 |
| System76      | Adder WS                    | [5624c5b0e8](https://linux-hardware.org/?probe=5624c5b0e8) | May 28, 2023 |
| System76      | Adder WS                    | [2522fb534f](https://linux-hardware.org/?probe=2522fb534f) | May 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [1fde8a9c8c](https://linux-hardware.org/?probe=1fde8a9c8c) | May 28, 2023 |
| Lenovo        | ThinkPad T440p 20AWS1420... | [7faaacfcaf](https://linux-hardware.org/?probe=7faaacfcaf) | May 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | [6b71e36a41](https://linux-hardware.org/?probe=6b71e36a41) | May 28, 2023 |
| Lenovo        | Yoga 700-11ISK 80QE         | [149dfccfe7](https://linux-hardware.org/?probe=149dfccfe7) | May 27, 2023 |
| Google        | Kohaku                      | [2b46417afd](https://linux-hardware.org/?probe=2b46417afd) | May 27, 2023 |
| Dell          | Inspiron 7520               | [07b70ac9e5](https://linux-hardware.org/?probe=07b70ac9e5) | May 27, 2023 |
| System76      | Galago Pro                  | [51cc594a01](https://linux-hardware.org/?probe=51cc594a01) | May 27, 2023 |
| Apple         | MacBookPro15,1              | [8d5c73bd4d](https://linux-hardware.org/?probe=8d5c73bd4d) | May 27, 2023 |
| Dell          | XPS 15 9570                 | [e74ee1390f](https://linux-hardware.org/?probe=e74ee1390f) | May 26, 2023 |
| ASUSTek       | X555LN                      | [8f16767017](https://linux-hardware.org/?probe=8f16767017) | May 26, 2023 |
| Dell          | XPS 15 9570                 | [ac75726738](https://linux-hardware.org/?probe=ac75726738) | May 26, 2023 |
| HP            | ZBook 17 G6                 | [177d184559](https://linux-hardware.org/?probe=177d184559) | May 26, 2023 |
| HP            | ZBook 17 G6                 | [56a8a0e368](https://linux-hardware.org/?probe=56a8a0e368) | May 26, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [a12e26f683](https://linux-hardware.org/?probe=a12e26f683) | May 26, 2023 |
| Dell          | Inspiron 7520               | [6d237fdf95](https://linux-hardware.org/?probe=6d237fdf95) | May 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [72f5c85f7f](https://linux-hardware.org/?probe=72f5c85f7f) | May 26, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [925f0e5016](https://linux-hardware.org/?probe=925f0e5016) | May 26, 2023 |
| ASUSTek       | X502CA                      | [7b19816353](https://linux-hardware.org/?probe=7b19816353) | May 25, 2023 |
| MSI           | Alpha 15 A3DDK              | [722e709153](https://linux-hardware.org/?probe=722e709153) | May 25, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [fcecd714d6](https://linux-hardware.org/?probe=fcecd714d6) | May 25, 2023 |
| Apple         | MacBookPro6,1               | [c8eb2c32b3](https://linux-hardware.org/?probe=c8eb2c32b3) | May 25, 2023 |
| Lenovo        | ThinkPad W540 20BHS0BD02    | [b6318da458](https://linux-hardware.org/?probe=b6318da458) | May 25, 2023 |
| Lenovo        | IdeaPad Y560                | [a8b595f03c](https://linux-hardware.org/?probe=a8b595f03c) | May 24, 2023 |
| HP            | Laptop PC 15-e3000          | [b3f6af4f8c](https://linux-hardware.org/?probe=b3f6af4f8c) | May 24, 2023 |
| Dell          | Precision 5470              | [e0a145106b](https://linux-hardware.org/?probe=e0a145106b) | May 24, 2023 |
| HP            | Laptop PC 15-e3000          | [29c9a90dc9](https://linux-hardware.org/?probe=29c9a90dc9) | May 24, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [a38171543f](https://linux-hardware.org/?probe=a38171543f) | May 24, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [8e5402cb16](https://linux-hardware.org/?probe=8e5402cb16) | May 24, 2023 |
| Dell          | G15 5511                    | [3876065a3e](https://linux-hardware.org/?probe=3876065a3e) | May 24, 2023 |
| HP            | 250 G8 Notebook PC          | [b7d26b3293](https://linux-hardware.org/?probe=b7d26b3293) | May 24, 2023 |
| HP            | 250 G8 Notebook PC          | [e3a554c09d](https://linux-hardware.org/?probe=e3a554c09d) | May 24, 2023 |
| Apple         | MacBookPro6,1               | [a8da820b95](https://linux-hardware.org/?probe=a8da820b95) | May 24, 2023 |
| HP            | Spectre Pro x360 G1         | [90df3b7bfa](https://linux-hardware.org/?probe=90df3b7bfa) | May 23, 2023 |
| HP            | Spectre Pro x360 G1         | [0f0ad128aa](https://linux-hardware.org/?probe=0f0ad128aa) | May 23, 2023 |
| Lenovo        | ThinkPad E595 20NFS0TH00    | [c843de4a39](https://linux-hardware.org/?probe=c843de4a39) | May 23, 2023 |
| HUAWEI        | BOHB-WAX9                   | [da701ce37f](https://linux-hardware.org/?probe=da701ce37f) | May 23, 2023 |
| HP            | Laptop 14-dq0xxx            | [77ccb1431b](https://linux-hardware.org/?probe=77ccb1431b) | May 23, 2023 |
| Lenovo        | Unknown                     | [144302ab2c](https://linux-hardware.org/?probe=144302ab2c) | May 23, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [b0fac119c2](https://linux-hardware.org/?probe=b0fac119c2) | May 22, 2023 |
| ASUSTek       | X550CC                      | [8226c82b49](https://linux-hardware.org/?probe=8226c82b49) | May 21, 2023 |
| ASUSTek       | X550CC                      | [6a8e6201be](https://linux-hardware.org/?probe=6a8e6201be) | May 21, 2023 |
| Lenovo        | Unknown                     | [1288108e10](https://linux-hardware.org/?probe=1288108e10) | May 21, 2023 |
| Lenovo        | ThinkPad T440p              | [b6c59c331b](https://linux-hardware.org/?probe=b6c59c331b) | May 21, 2023 |
| Apple         | MacBookPro5,3               | [0df526f042](https://linux-hardware.org/?probe=0df526f042) | May 21, 2023 |
| Dell          | G15 5511                    | [ad4c2a0521](https://linux-hardware.org/?probe=ad4c2a0521) | May 21, 2023 |
| HP            | EliteBook 840 G5            | [399ea93745](https://linux-hardware.org/?probe=399ea93745) | May 21, 2023 |
| Toshiba       | Satellite L855D             | [5be0280c53](https://linux-hardware.org/?probe=5be0280c53) | May 21, 2023 |
| HP            | EliteBook 820 G2            | [23fb35880e](https://linux-hardware.org/?probe=23fb35880e) | May 21, 2023 |
| HP            | EliteBook 820 G2            | [d52da23326](https://linux-hardware.org/?probe=d52da23326) | May 21, 2023 |
| Acer          | Aspire E5-575               | [fb1832d859](https://linux-hardware.org/?probe=fb1832d859) | May 20, 2023 |
| Toshiba       | IS 1413G                    | [4c5dce3a01](https://linux-hardware.org/?probe=4c5dce3a01) | May 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [51f87ac309](https://linux-hardware.org/?probe=51f87ac309) | May 20, 2023 |
| HP            | Pavilion dv6                | [51e808c93a](https://linux-hardware.org/?probe=51e808c93a) | May 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [42e009b3c5](https://linux-hardware.org/?probe=42e009b3c5) | May 19, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [2cde0cc93d](https://linux-hardware.org/?probe=2cde0cc93d) | May 19, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [4a9869b7a6](https://linux-hardware.org/?probe=4a9869b7a6) | May 19, 2023 |
| Apple         | MacBookAir7,2               | [337509e694](https://linux-hardware.org/?probe=337509e694) | May 19, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [d51c5680e8](https://linux-hardware.org/?probe=d51c5680e8) | May 19, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [08df098150](https://linux-hardware.org/?probe=08df098150) | May 18, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [a74f787d52](https://linux-hardware.org/?probe=a74f787d52) | May 18, 2023 |
| Acer          | Swift SFX14-51G             | [644878287e](https://linux-hardware.org/?probe=644878287e) | May 18, 2023 |
| Reliance C... | R141TL5                     | [a21525c003](https://linux-hardware.org/?probe=a21525c003) | May 18, 2023 |
| Dell          | Inspiron 5559               | [620177b4fa](https://linux-hardware.org/?probe=620177b4fa) | May 17, 2023 |
| Lenovo        | ThinkPad X260 20F6CTO1WW    | [a35e6c0b2d](https://linux-hardware.org/?probe=a35e6c0b2d) | May 17, 2023 |
| Dell          | Inspiron 14 5408            | [c1853f7df2](https://linux-hardware.org/?probe=c1853f7df2) | May 17, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [dd1e6376c2](https://linux-hardware.org/?probe=dd1e6376c2) | May 17, 2023 |
| Google        | Blorb                       | [7537bc5890](https://linux-hardware.org/?probe=7537bc5890) | May 17, 2023 |
| Apple         | MacBookAir7,2               | [add6bcd4f7](https://linux-hardware.org/?probe=add6bcd4f7) | May 16, 2023 |
| Apple         | MacBookAir7,2               | [2616bd6b98](https://linux-hardware.org/?probe=2616bd6b98) | May 16, 2023 |
| HP            | Pavilion dv6                | [fd5291d10e](https://linux-hardware.org/?probe=fd5291d10e) | May 15, 2023 |
| HP            | OMEN by Laptop 17-cb0xxx    | [2192ceeebd](https://linux-hardware.org/?probe=2192ceeebd) | May 15, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [a7c2953571](https://linux-hardware.org/?probe=a7c2953571) | May 15, 2023 |
| Lenovo        | ThinkPad X230 23301E0       | [681e1f8c61](https://linux-hardware.org/?probe=681e1f8c61) | May 15, 2023 |
| ASUSTek       | X541UJ                      | [9be042ca8a](https://linux-hardware.org/?probe=9be042ca8a) | May 14, 2023 |
| Dell          | Inspiron 3583               | [3d3bfc28a6](https://linux-hardware.org/?probe=3d3bfc28a6) | May 14, 2023 |
| HP            | Victus by Gaming Laptop ... | [c74505560b](https://linux-hardware.org/?probe=c74505560b) | May 14, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [f67b1d428b](https://linux-hardware.org/?probe=f67b1d428b) | May 14, 2023 |
| Toshiba       | TECRA R850                  | [e48ff4432d](https://linux-hardware.org/?probe=e48ff4432d) | May 14, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [effc7c876e](https://linux-hardware.org/?probe=effc7c876e) | May 14, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | [d26275a2de](https://linux-hardware.org/?probe=d26275a2de) | May 14, 2023 |
| HP            | Pavilion dv6                | [e20ba378ac](https://linux-hardware.org/?probe=e20ba378ac) | May 13, 2023 |
| Dell          | G7 7700                     | [6568ba5b4d](https://linux-hardware.org/?probe=6568ba5b4d) | May 13, 2023 |
| Gigabyte      | P34V7                       | [90e6e5d5d9](https://linux-hardware.org/?probe=90e6e5d5d9) | May 13, 2023 |
| System76      | Galago Pro                  | [a30efb5622](https://linux-hardware.org/?probe=a30efb5622) | May 13, 2023 |
| Lenovo        | ThinkPad X230 23301E0       | [9a5e07f865](https://linux-hardware.org/?probe=9a5e07f865) | May 13, 2023 |
| Dell          | Precision 3571              | [9a20dccb42](https://linux-hardware.org/?probe=9a20dccb42) | May 13, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [69a20b9c03](https://linux-hardware.org/?probe=69a20b9c03) | May 13, 2023 |
| System76      | Gazelle                     | [bd4e912b20](https://linux-hardware.org/?probe=bd4e912b20) | May 12, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [7dd8e30770](https://linux-hardware.org/?probe=7dd8e30770) | May 12, 2023 |
| Lenovo        | ThinkPad T590 20N4002WGE    | [6caedd8a7b](https://linux-hardware.org/?probe=6caedd8a7b) | May 12, 2023 |
| ASUSTek       | ZenBook UX431FN             | [ee40bf2168](https://linux-hardware.org/?probe=ee40bf2168) | May 12, 2023 |
| System76      | Gazelle                     | [83ef9e6d2d](https://linux-hardware.org/?probe=83ef9e6d2d) | May 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [729a4181de](https://linux-hardware.org/?probe=729a4181de) | May 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [3010c8760e](https://linux-hardware.org/?probe=3010c8760e) | May 12, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HM... | [f54531cd16](https://linux-hardware.org/?probe=f54531cd16) | May 11, 2023 |
| MSI           | Stealth 16Studio A13VG      | [7c232216fd](https://linux-hardware.org/?probe=7c232216fd) | May 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [a7155be531](https://linux-hardware.org/?probe=a7155be531) | May 11, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | [f46fe8b9ee](https://linux-hardware.org/?probe=f46fe8b9ee) | May 11, 2023 |
| Dell          | Inspiron 5566               | [e1e22ae448](https://linux-hardware.org/?probe=e1e22ae448) | May 10, 2023 |
| Acer          | Aspire VN7-591G             | [1fe1a8fcd2](https://linux-hardware.org/?probe=1fe1a8fcd2) | May 09, 2023 |
| MSI           | GL65 Leopard 10SCSR         | [4d9a7df494](https://linux-hardware.org/?probe=4d9a7df494) | May 09, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [28e1a5c2e9](https://linux-hardware.org/?probe=28e1a5c2e9) | May 09, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [fed7278850](https://linux-hardware.org/?probe=fed7278850) | May 09, 2023 |
| Lenovo        | ThinkPad T410 2522AA6       | [82755e3688](https://linux-hardware.org/?probe=82755e3688) | May 08, 2023 |
| Acer          | Aspire A715-72G             | [da1c6920b6](https://linux-hardware.org/?probe=da1c6920b6) | May 08, 2023 |
| Alienware     | Area-51m R2 A00             | [3cc417c9d9](https://linux-hardware.org/?probe=3cc417c9d9) | May 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [6bc581f37c](https://linux-hardware.org/?probe=6bc581f37c) | May 08, 2023 |
| HP            | Pavilion dv6                | [978d2165ac](https://linux-hardware.org/?probe=978d2165ac) | May 07, 2023 |
| Lenovo        | ThinkPad X260 20F6CTO1WW    | [e81eb02947](https://linux-hardware.org/?probe=e81eb02947) | May 07, 2023 |
| Notebook      | N141CU                      | [535b4ca746](https://linux-hardware.org/?probe=535b4ca746) | May 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [619dc53d25](https://linux-hardware.org/?probe=619dc53d25) | May 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [078d3ae45f](https://linux-hardware.org/?probe=078d3ae45f) | May 06, 2023 |
| Notebook      | P15SM                       | [dcea4ec037](https://linux-hardware.org/?probe=dcea4ec037) | May 06, 2023 |
| Packard Be... | EasyNote LM85               | [d37b9e6687](https://linux-hardware.org/?probe=d37b9e6687) | May 06, 2023 |
| Lenovo        | ThinkPad T580 20L9001HUS    | [4bad3ee37e](https://linux-hardware.org/?probe=4bad3ee37e) | May 06, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [fbe46d0c6e](https://linux-hardware.org/?probe=fbe46d0c6e) | May 05, 2023 |
| Dell          | XPS 15 9510                 | [fbd91068d3](https://linux-hardware.org/?probe=fbd91068d3) | May 05, 2023 |
| Positivo      | N4350                       | [ec0df546f9](https://linux-hardware.org/?probe=ec0df546f9) | May 05, 2023 |
| ASUSTek       | ZenBook UX431FN             | [3194ab7fa2](https://linux-hardware.org/?probe=3194ab7fa2) | May 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [eaf28f6af4](https://linux-hardware.org/?probe=eaf28f6af4) | May 05, 2023 |
| Toshiba       | TECRA R850                  | [bb41171733](https://linux-hardware.org/?probe=bb41171733) | May 05, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | [139c809251](https://linux-hardware.org/?probe=139c809251) | May 04, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [5022c3993a](https://linux-hardware.org/?probe=5022c3993a) | May 04, 2023 |
| Dell          | Latitude 7370               | [6beab237df](https://linux-hardware.org/?probe=6beab237df) | May 04, 2023 |
| Dell          | XPS 15 9510                 | [2ab4f57ff6](https://linux-hardware.org/?probe=2ab4f57ff6) | May 04, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [0767486bb6](https://linux-hardware.org/?probe=0767486bb6) | May 04, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [3c6e20e260](https://linux-hardware.org/?probe=3c6e20e260) | May 04, 2023 |
| HP            | Unknown                     | [311e275897](https://linux-hardware.org/?probe=311e275897) | May 04, 2023 |
| MSI           | GV62 7RE                    | [1b048994c9](https://linux-hardware.org/?probe=1b048994c9) | May 04, 2023 |
| System76      | Oryx Pro                    | [cae9fadc38](https://linux-hardware.org/?probe=cae9fadc38) | May 04, 2023 |
| Lenovo        | Yoga 300-11IBY 80M0         | [a4a894bb7a](https://linux-hardware.org/?probe=a4a894bb7a) | May 03, 2023 |
| HP            | Unknown                     | [122c1783c0](https://linux-hardware.org/?probe=122c1783c0) | May 03, 2023 |
| American M... | XA133PR110                  | [4c02a6f8da](https://linux-hardware.org/?probe=4c02a6f8da) | May 03, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | [6cb7429ec6](https://linux-hardware.org/?probe=6cb7429ec6) | May 02, 2023 |
| Lenovo        | ThinkPad T420 4180AP3       | [9322206a7d](https://linux-hardware.org/?probe=9322206a7d) | May 02, 2023 |
| Toshiba       | PORTEGE Z30-A               | [ccc620956f](https://linux-hardware.org/?probe=ccc620956f) | May 02, 2023 |
| System76      | Oryx Pro                    | [8bd4f39eaa](https://linux-hardware.org/?probe=8bd4f39eaa) | May 02, 2023 |
| Lenovo        | ThinkPad W541 20EGS0B010    | [3f87bce0eb](https://linux-hardware.org/?probe=3f87bce0eb) | May 01, 2023 |
| System76      | Gazelle                     | [8a8de3e027](https://linux-hardware.org/?probe=8a8de3e027) | May 01, 2023 |
| HP            | EliteBook 830 G5            | [1979bde291](https://linux-hardware.org/?probe=1979bde291) | May 01, 2023 |
| HUAWEI        | HVY-WXX9                    | [3c82fea068](https://linux-hardware.org/?probe=3c82fea068) | May 01, 2023 |
| Dell          | Precision 5530              | [c8878b0f0f](https://linux-hardware.org/?probe=c8878b0f0f) | May 01, 2023 |
| Lenovo        | ThinkPad P52s 20LCS1H100    | [34b877bcb5](https://linux-hardware.org/?probe=34b877bcb5) | May 01, 2023 |
| ASUSTek       | X455LJ                      | [4e252eab9f](https://linux-hardware.org/?probe=4e252eab9f) | May 01, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [9df1b688c0](https://linux-hardware.org/?probe=9df1b688c0) | Apr 30, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [875ae124a1](https://linux-hardware.org/?probe=875ae124a1) | Apr 30, 2023 |
| Dell          | Latitude E6430              | [4c20239367](https://linux-hardware.org/?probe=4c20239367) | Apr 30, 2023 |
| Apple         | MacBookPro11,3              | [3feeeb3341](https://linux-hardware.org/?probe=3feeeb3341) | Apr 29, 2023 |
| Apple         | MacBookPro11,3              | [8e0692ebe3](https://linux-hardware.org/?probe=8e0692ebe3) | Apr 29, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [af0c1ea83c](https://linux-hardware.org/?probe=af0c1ea83c) | Apr 29, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [7c8c5a4668](https://linux-hardware.org/?probe=7c8c5a4668) | Apr 29, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [9b560392f5](https://linux-hardware.org/?probe=9b560392f5) | Apr 29, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ARH7 8... | [39644ab1d4](https://linux-hardware.org/?probe=39644ab1d4) | Apr 28, 2023 |
| Lenovo        | ThinkPad T450 20BUS0B000    | [a2cbf65767](https://linux-hardware.org/?probe=a2cbf65767) | Apr 28, 2023 |
| HP            | ENVY 15                     | [d870c486c7](https://linux-hardware.org/?probe=d870c486c7) | Apr 27, 2023 |
| Toshiba       | IS 1413G                    | [f96c9382bd](https://linux-hardware.org/?probe=f96c9382bd) | Apr 27, 2023 |
| Dell          | Latitude D520               | [a643e2e424](https://linux-hardware.org/?probe=a643e2e424) | Apr 27, 2023 |
| Toshiba       | IS 1413G                    | [a24f74af8e](https://linux-hardware.org/?probe=a24f74af8e) | Apr 26, 2023 |
| Lenovo        | ThinkPad L570 20J80021MD    | [26e9a466cd](https://linux-hardware.org/?probe=26e9a466cd) | Apr 26, 2023 |
| System76      | Gazelle                     | [ca2e23db8d](https://linux-hardware.org/?probe=ca2e23db8d) | Apr 25, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [f797b7112c](https://linux-hardware.org/?probe=f797b7112c) | Apr 25, 2023 |
| HP            | ENVY 15                     | [3539894e49](https://linux-hardware.org/?probe=3539894e49) | Apr 25, 2023 |
| Acer          | E5-551G-871W                | [2730a30d89](https://linux-hardware.org/?probe=2730a30d89) | Apr 25, 2023 |
| Lenovo        | V14-IIL 82C4                | [42a0a6d5e4](https://linux-hardware.org/?probe=42a0a6d5e4) | Apr 25, 2023 |
| Lenovo        | V14-IIL 82C4                | [7ab59d4ba9](https://linux-hardware.org/?probe=7ab59d4ba9) | Apr 25, 2023 |
| HP            | Laptop 15-ef1xxx            | [05d2b26ee6](https://linux-hardware.org/?probe=05d2b26ee6) | Apr 25, 2023 |
| HP            | Laptop 15-ef1xxx            | [0ef0676073](https://linux-hardware.org/?probe=0ef0676073) | Apr 25, 2023 |
| HP            | ENVY 15                     | [39d32b035a](https://linux-hardware.org/?probe=39d32b035a) | Apr 25, 2023 |
| Apple         | MacBookPro8,1               | [2f1eb3e6ee](https://linux-hardware.org/?probe=2f1eb3e6ee) | Apr 24, 2023 |
| Alienware     | 13 R2                       | [ee7a023f6d](https://linux-hardware.org/?probe=ee7a023f6d) | Apr 24, 2023 |
| Lenovo        | ThinkPad T480 20L50003GE    | [1259bb0006](https://linux-hardware.org/?probe=1259bb0006) | Apr 24, 2023 |
| Alienware     | 13 R3                       | [f04b34f41d](https://linux-hardware.org/?probe=f04b34f41d) | Apr 23, 2023 |
| ASUSTek       | X551MA                      | [44ca7e29c0](https://linux-hardware.org/?probe=44ca7e29c0) | Apr 23, 2023 |
| Dell          | Inspiron 7737               | [50b75a71d3](https://linux-hardware.org/?probe=50b75a71d3) | Apr 23, 2023 |
| HP            | ZBook 15                    | [c7ae51efcd](https://linux-hardware.org/?probe=c7ae51efcd) | Apr 22, 2023 |
| Dell          | Inspiron 5567               | [f639b8e21a](https://linux-hardware.org/?probe=f639b8e21a) | Apr 22, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [1c76d0f5a4](https://linux-hardware.org/?probe=1c76d0f5a4) | Apr 22, 2023 |
| Lenovo        | Legion S7 15IMH5 82BC       | [332fdb5298](https://linux-hardware.org/?probe=332fdb5298) | Apr 22, 2023 |
| Dell          | XPS 13 9350                 | [1ed1930799](https://linux-hardware.org/?probe=1ed1930799) | Apr 21, 2023 |
| GPU Compan... | GWTC116-2                   | [8f7df56d73](https://linux-hardware.org/?probe=8f7df56d73) | Apr 21, 2023 |
| HP            | ProBook 640 G1              | [b5022d8a2f](https://linux-hardware.org/?probe=b5022d8a2f) | Apr 21, 2023 |
| Dell          | Precision M6600             | [e71bf9e7bb](https://linux-hardware.org/?probe=e71bf9e7bb) | Apr 20, 2023 |
| Lenovo        | ThinkPad X220 4291WF5       | [4c78af0e05](https://linux-hardware.org/?probe=4c78af0e05) | Apr 20, 2023 |
| Dell          | XPS 13 9343                 | [573d482e45](https://linux-hardware.org/?probe=573d482e45) | Apr 20, 2023 |
| HP            | Compaq 6510b (KE131ET#AK... | [f9415c65e9](https://linux-hardware.org/?probe=f9415c65e9) | Apr 20, 2023 |
| Dell          | Inspiron 17 7000 Series ... | [6222d9b2b0](https://linux-hardware.org/?probe=6222d9b2b0) | Apr 19, 2023 |
| HP            | Compaq 6510b (KE131ET#AK... | [fc27cf4b3e](https://linux-hardware.org/?probe=fc27cf4b3e) | Apr 19, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [0187ac7a0c](https://linux-hardware.org/?probe=0187ac7a0c) | Apr 19, 2023 |
| Lenovo        | ThinkPad T480s 20L8S6S30... | [9241adf5fb](https://linux-hardware.org/?probe=9241adf5fb) | Apr 19, 2023 |
| American M... | XA133PR110                  | [5c634b7029](https://linux-hardware.org/?probe=5c634b7029) | Apr 19, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | [0f058078c9](https://linux-hardware.org/?probe=0f058078c9) | Apr 19, 2023 |
| HP            | EliteBook 8460p             | [33b92210c7](https://linux-hardware.org/?probe=33b92210c7) | Apr 19, 2023 |
| HP            | EliteBook 8460p             | [fe26aeffdd](https://linux-hardware.org/?probe=fe26aeffdd) | Apr 19, 2023 |
| ASUSTek       | X541UJ                      | [1aa63436a5](https://linux-hardware.org/?probe=1aa63436a5) | Apr 19, 2023 |
| Acer          | Aspire AV15-52              | [e1044f40e2](https://linux-hardware.org/?probe=e1044f40e2) | Apr 18, 2023 |
| Acer          | Aspire E5-575               | [58b159ef8f](https://linux-hardware.org/?probe=58b159ef8f) | Apr 18, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | [c35c104c5e](https://linux-hardware.org/?probe=c35c104c5e) | Apr 18, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | [14df620b0a](https://linux-hardware.org/?probe=14df620b0a) | Apr 18, 2023 |
| Lenovo        | Y50-70 20378                | [af6c719754](https://linux-hardware.org/?probe=af6c719754) | Apr 18, 2023 |
| Dell          | Inspiron 7559               | [9c66c608f3](https://linux-hardware.org/?probe=9c66c608f3) | Apr 18, 2023 |
| Lenovo        | ThinkPad T480 20L50003GE    | [e779a9606f](https://linux-hardware.org/?probe=e779a9606f) | Apr 18, 2023 |
| Apple         | MacBookPro12,1              | [f045e3f800](https://linux-hardware.org/?probe=f045e3f800) | Apr 18, 2023 |
| Gigabyte      | G5 GE                       | [f1baab4be4](https://linux-hardware.org/?probe=f1baab4be4) | Apr 17, 2023 |
| MSI           | PS42 Modern 8RC             | [459a84f65e](https://linux-hardware.org/?probe=459a84f65e) | Apr 17, 2023 |
| American M... | XA133PR110                  | [08b47e43a7](https://linux-hardware.org/?probe=08b47e43a7) | Apr 17, 2023 |
| Toshiba       | Satellite E45-B             | [ec0bb6bfc6](https://linux-hardware.org/?probe=ec0bb6bfc6) | Apr 17, 2023 |
| Lenovo        | Legion 7 16IAX7 82TD        | [8f0188b2a1](https://linux-hardware.org/?probe=8f0188b2a1) | Apr 17, 2023 |
| Dell          | Inspiron 3541               | [dd409790ad](https://linux-hardware.org/?probe=dd409790ad) | Apr 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [55325c372c](https://linux-hardware.org/?probe=55325c372c) | Apr 17, 2023 |
| HP            | ENVY 17                     | [ba2c1aae76](https://linux-hardware.org/?probe=ba2c1aae76) | Apr 17, 2023 |
| HP            | Dev One Notebook PC         | [5e3f0907fa](https://linux-hardware.org/?probe=5e3f0907fa) | Apr 16, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [beac478abb](https://linux-hardware.org/?probe=beac478abb) | Apr 16, 2023 |
| Dell          | XPS 13 9310                 | [3a7d52ef90](https://linux-hardware.org/?probe=3a7d52ef90) | Apr 16, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [6b126883e9](https://linux-hardware.org/?probe=6b126883e9) | Apr 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [9ac7ca1a63](https://linux-hardware.org/?probe=9ac7ca1a63) | Apr 16, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [762ad80f82](https://linux-hardware.org/?probe=762ad80f82) | Apr 16, 2023 |
| Dell          | Inspiron 1525               | [3b20856ccc](https://linux-hardware.org/?probe=3b20856ccc) | Apr 16, 2023 |
| Acer          | Swift SFX14-41G             | [a0f08c4442](https://linux-hardware.org/?probe=a0f08c4442) | Apr 16, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [f7ce1b2ab5](https://linux-hardware.org/?probe=f7ce1b2ab5) | Apr 15, 2023 |
| Medion        | E15415                      | [fb905ef988](https://linux-hardware.org/?probe=fb905ef988) | Apr 15, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [1d253a4901](https://linux-hardware.org/?probe=1d253a4901) | Apr 15, 2023 |
| HP            | ZBook Firefly 15.6 inch ... | [f45051411c](https://linux-hardware.org/?probe=f45051411c) | Apr 15, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [aedbc43074](https://linux-hardware.org/?probe=aedbc43074) | Apr 15, 2023 |
| HP            | Pavilion g6                 | [a918284993](https://linux-hardware.org/?probe=a918284993) | Apr 15, 2023 |
| Dell          | XPS 15 9560                 | [5ab7cc057f](https://linux-hardware.org/?probe=5ab7cc057f) | Apr 14, 2023 |
| Dell          | Precision 5550              | [1546772c9f](https://linux-hardware.org/?probe=1546772c9f) | Apr 14, 2023 |
| Dell          | Latitude E5440              | [a827218c2e](https://linux-hardware.org/?probe=a827218c2e) | Apr 14, 2023 |
| ASUSTek       | X551MA                      | [871fd53afd](https://linux-hardware.org/?probe=871fd53afd) | Apr 14, 2023 |
| HP            | Laptop 15z-fc000            | [df47336192](https://linux-hardware.org/?probe=df47336192) | Apr 14, 2023 |
| HP            | Notebook                    | [79541411b2](https://linux-hardware.org/?probe=79541411b2) | Apr 14, 2023 |
| Toshiba       | IS 1413G                    | [f57cf8ddf4](https://linux-hardware.org/?probe=f57cf8ddf4) | Apr 13, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [5a86b52121](https://linux-hardware.org/?probe=5a86b52121) | Apr 13, 2023 |
| System76      | Pangolin                    | [1750f20c8d](https://linux-hardware.org/?probe=1750f20c8d) | Apr 12, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | [1f12146974](https://linux-hardware.org/?probe=1f12146974) | Apr 12, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | [9aadb88a2d](https://linux-hardware.org/?probe=9aadb88a2d) | Apr 12, 2023 |
| Apple         | MacBookPro8,1               | [94372e3520](https://linux-hardware.org/?probe=94372e3520) | Apr 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [0120f0db62](https://linux-hardware.org/?probe=0120f0db62) | Apr 12, 2023 |
| Dell          | G3 3579                     | [24d10a8497](https://linux-hardware.org/?probe=24d10a8497) | Apr 12, 2023 |
| Timi          | TM1707                      | [0e015e68ec](https://linux-hardware.org/?probe=0e015e68ec) | Apr 12, 2023 |
| Timi          | TM1707                      | [b611ba24ed](https://linux-hardware.org/?probe=b611ba24ed) | Apr 12, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [87059322b0](https://linux-hardware.org/?probe=87059322b0) | Apr 11, 2023 |
| Samsung       | 760XDA                      | [bdc1648c05](https://linux-hardware.org/?probe=bdc1648c05) | Apr 11, 2023 |
| Dell          | Latitude 5590               | [f8f0f0125f](https://linux-hardware.org/?probe=f8f0f0125f) | Apr 11, 2023 |
| MSI           | GF63 Thin 9RCX              | [c48286f8a2](https://linux-hardware.org/?probe=c48286f8a2) | Apr 10, 2023 |
| Apple         | MacBookPro11,4              | [85a39124f3](https://linux-hardware.org/?probe=85a39124f3) | Apr 09, 2023 |
| Apple         | MacBookPro12,1              | [0844c71fd0](https://linux-hardware.org/?probe=0844c71fd0) | Apr 07, 2023 |
| System76      | Oryx Pro                    | [a221f4f9d4](https://linux-hardware.org/?probe=a221f4f9d4) | Apr 06, 2023 |
| HP            | ProBook 640 G1              | [769d886cc9](https://linux-hardware.org/?probe=769d886cc9) | Apr 05, 2023 |
| HP            | ProBook 640 G1              | [de7d3ba0c0](https://linux-hardware.org/?probe=de7d3ba0c0) | Apr 05, 2023 |
| Razer         | Blade                       | [351fe907cb](https://linux-hardware.org/?probe=351fe907cb) | Apr 05, 2023 |
| Apple         | MacBookPro12,1              | [c77ef60bcc](https://linux-hardware.org/?probe=c77ef60bcc) | Apr 05, 2023 |
| HP            | Laptop 14-dq0xxx            | [ba87782532](https://linux-hardware.org/?probe=ba87782532) | Apr 05, 2023 |
| Lenovo        | Edge 15 80K9                | [911d261c1b](https://linux-hardware.org/?probe=911d261c1b) | Apr 05, 2023 |
| ASUSTek       | N76VZ                       | [d87006e429](https://linux-hardware.org/?probe=d87006e429) | Apr 05, 2023 |
| Samsung       | RC530/RC730                 | [3f886e678f](https://linux-hardware.org/?probe=3f886e678f) | Apr 05, 2023 |
| Samsung       | RC530/RC730                 | [43e4869357](https://linux-hardware.org/?probe=43e4869357) | Apr 05, 2023 |
| Lenovo        | ThinkBook 15-IML 20RW       | [58f5904dec](https://linux-hardware.org/?probe=58f5904dec) | Apr 04, 2023 |
| Dell          | Inspiron 7375               | [0d8465f75c](https://linux-hardware.org/?probe=0d8465f75c) | Apr 04, 2023 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [d56565f374](https://linux-hardware.org/?probe=d56565f374) | Apr 04, 2023 |
| Dell          | XPS 15 9500                 | [84f877fde3](https://linux-hardware.org/?probe=84f877fde3) | Apr 04, 2023 |
| ASUSTek       | E201NA                      | [098fb721f8](https://linux-hardware.org/?probe=098fb721f8) | Apr 04, 2023 |
| Acer          | Swift SF314-43              | [a964b0aa55](https://linux-hardware.org/?probe=a964b0aa55) | Apr 04, 2023 |
| Razer         | Blade Stealth               | [2cf4a53eb5](https://linux-hardware.org/?probe=2cf4a53eb5) | Apr 04, 2023 |
| Dell          | Latitude E7240              | [fce3da8380](https://linux-hardware.org/?probe=fce3da8380) | Apr 04, 2023 |
| Unknown       | Unknown                     | [190b5364e1](https://linux-hardware.org/?probe=190b5364e1) | Apr 03, 2023 |
| Unknown       | Unknown                     | [a6a766a40a](https://linux-hardware.org/?probe=a6a766a40a) | Apr 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [9880810adc](https://linux-hardware.org/?probe=9880810adc) | Apr 03, 2023 |
| MSI           | GV62 7RE                    | [5d441311f4](https://linux-hardware.org/?probe=5d441311f4) | Apr 03, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [777f7d0fc4](https://linux-hardware.org/?probe=777f7d0fc4) | Apr 03, 2023 |
| MSI           | GL63 8RC                    | [8c90ec7da1](https://linux-hardware.org/?probe=8c90ec7da1) | Apr 03, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [f013c5ca48](https://linux-hardware.org/?probe=f013c5ca48) | Apr 03, 2023 |
| Apple         | MacBookPro12,1              | [edb2f4188e](https://linux-hardware.org/?probe=edb2f4188e) | Apr 03, 2023 |
| HP            | 650                         | [bcb4e8d60a](https://linux-hardware.org/?probe=bcb4e8d60a) | Apr 03, 2023 |
| Lenovo        | ThinkPad T470 20HES0FA03    | [7274c8222b](https://linux-hardware.org/?probe=7274c8222b) | Apr 02, 2023 |
| Lenovo        | ThinkPad T460p 20FXS08N0... | [ffcf174547](https://linux-hardware.org/?probe=ffcf174547) | Apr 02, 2023 |
| Apple         | MacBook3,1                  | [44f31f3094](https://linux-hardware.org/?probe=44f31f3094) | Apr 02, 2023 |
| System76      | Kudu                        | [2baafe374c](https://linux-hardware.org/?probe=2baafe374c) | Apr 02, 2023 |
| Toshiba       | IS 1413G                    | [76a94d8c87](https://linux-hardware.org/?probe=76a94d8c87) | Apr 02, 2023 |
| Sony          | VPCSC1AFM                   | [854b8bfa02](https://linux-hardware.org/?probe=854b8bfa02) | Apr 01, 2023 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | [51c7ed9156](https://linux-hardware.org/?probe=51c7ed9156) | Apr 01, 2023 |
| Lenovo        | Slim 7 16ARH7 82UX          | [cca7093e15](https://linux-hardware.org/?probe=cca7093e15) | Apr 01, 2023 |
| Lenovo        | IdeaPad U310                | [6add75e18c](https://linux-hardware.org/?probe=6add75e18c) | Apr 01, 2023 |
| Toshiba       | Satellite L45-B             | [6d4878cdbf](https://linux-hardware.org/?probe=6d4878cdbf) | Apr 01, 2023 |
| HP            | 240 G6 Notebook PC          | [44e093df31](https://linux-hardware.org/?probe=44e093df31) | Apr 01, 2023 |
| System76      | Lemur Pro                   | [5d57a3397e](https://linux-hardware.org/?probe=5d57a3397e) | Mar 31, 2023 |
| ASUSTek       | X751LD                      | [2ef82331de](https://linux-hardware.org/?probe=2ef82331de) | Mar 31, 2023 |
| Acer          | Aspire A515-56              | [bf846cebb9](https://linux-hardware.org/?probe=bf846cebb9) | Mar 30, 2023 |
| Acer          | Nitro AN515-58              | [27befad01f](https://linux-hardware.org/?probe=27befad01f) | Mar 30, 2023 |
| Apple         | MacBookPro12,1              | [21515b7373](https://linux-hardware.org/?probe=21515b7373) | Mar 30, 2023 |
| Apple         | MacBookPro12,1              | [080e22fdb2](https://linux-hardware.org/?probe=080e22fdb2) | Mar 30, 2023 |
| Toshiba       | IS 1413G                    | [13f35137bd](https://linux-hardware.org/?probe=13f35137bd) | Mar 30, 2023 |
| Multilaser    | MLSH1H LINUX                | [7ee1845d96](https://linux-hardware.org/?probe=7ee1845d96) | Mar 30, 2023 |
| Multilaser    | MLSH1H LINUX                | [bb80f561a2](https://linux-hardware.org/?probe=bb80f561a2) | Mar 30, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [854490056d](https://linux-hardware.org/?probe=854490056d) | Mar 29, 2023 |
| HP            | ZBook 15 G5                 | [059358e49b](https://linux-hardware.org/?probe=059358e49b) | Mar 29, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [af48722867](https://linux-hardware.org/?probe=af48722867) | Mar 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [0667374075](https://linux-hardware.org/?probe=0667374075) | Mar 28, 2023 |
| Acer          | Nitro AN515-45              | [0aabfe954d](https://linux-hardware.org/?probe=0aabfe954d) | Mar 28, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [7939320fa4](https://linux-hardware.org/?probe=7939320fa4) | Mar 28, 2023 |
| Positivo      | Mobile                      | [60fd382fbf](https://linux-hardware.org/?probe=60fd382fbf) | Mar 28, 2023 |
| Positivo      | Mobile                      | [b08c430903](https://linux-hardware.org/?probe=b08c430903) | Mar 28, 2023 |
| Razer         | Blade                       | [ffa791eb4a](https://linux-hardware.org/?probe=ffa791eb4a) | Mar 28, 2023 |
| ASUSTek       | X751LD                      | [61382d0bd8](https://linux-hardware.org/?probe=61382d0bd8) | Mar 28, 2023 |
| Dell          | Inspiron 15-3567            | [d2b4780094](https://linux-hardware.org/?probe=d2b4780094) | Mar 28, 2023 |
| Toshiba       | IS 1413G                    | [635309aff4](https://linux-hardware.org/?probe=635309aff4) | Mar 28, 2023 |
| Lenovo        | ThinkPad P50 20EQS0T400     | [5b4466c085](https://linux-hardware.org/?probe=5b4466c085) | Mar 28, 2023 |
| Lenovo        | ThinkPad T420 4180AP3       | [8ddee342c9](https://linux-hardware.org/?probe=8ddee342c9) | Mar 28, 2023 |
| Dell          | XPS 15 9570                 | [5be538736f](https://linux-hardware.org/?probe=5be538736f) | Mar 27, 2023 |
| Toshiba       | Satellite C55-C             | [d7ec0eb4b1](https://linux-hardware.org/?probe=d7ec0eb4b1) | Mar 27, 2023 |
| Apple         | MacBook5,1                  | [a5c200217f](https://linux-hardware.org/?probe=a5c200217f) | Mar 26, 2023 |
| MSI           | GL63 8RC                    | [935b78c3da](https://linux-hardware.org/?probe=935b78c3da) | Mar 26, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [537fc6af0e](https://linux-hardware.org/?probe=537fc6af0e) | Mar 26, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [55c29cec29](https://linux-hardware.org/?probe=55c29cec29) | Mar 26, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [905078c7b9](https://linux-hardware.org/?probe=905078c7b9) | Mar 26, 2023 |
| Dell          | Latitude E7240              | [3d91b46fda](https://linux-hardware.org/?probe=3d91b46fda) | Mar 26, 2023 |
| Dell          | XPS 13 9370                 | [3f3967267f](https://linux-hardware.org/?probe=3f3967267f) | Mar 26, 2023 |
| Lenovo        | Y50-70 20378                | [61897b32de](https://linux-hardware.org/?probe=61897b32de) | Mar 25, 2023 |
| HP            | Spectre Laptop 13-af0xx     | [6fdc683220](https://linux-hardware.org/?probe=6fdc683220) | Mar 25, 2023 |
| MSI           | Katana GF66 12UG            | [9e03ac14c0](https://linux-hardware.org/?probe=9e03ac14c0) | Mar 25, 2023 |
| Apple         | MacBookPro11,3              | [21c3ce9508](https://linux-hardware.org/?probe=21c3ce9508) | Mar 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [ac415822b8](https://linux-hardware.org/?probe=ac415822b8) | Mar 24, 2023 |
| HP            | Laptop 15-db0xxx            | [ad0e5c0483](https://linux-hardware.org/?probe=ad0e5c0483) | Mar 24, 2023 |
| Dell          | Latitude 5420               | [e6afbbee47](https://linux-hardware.org/?probe=e6afbbee47) | Mar 24, 2023 |
| HP            | EliteBook 8460p             | [f78f58795c](https://linux-hardware.org/?probe=f78f58795c) | Mar 24, 2023 |
| Alienware     | 17 R4                       | [3c456dc309](https://linux-hardware.org/?probe=3c456dc309) | Mar 24, 2023 |
| GPU Compan... | GWTN141-10                  | [9007c1d23f](https://linux-hardware.org/?probe=9007c1d23f) | Mar 24, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [f8f47e3220](https://linux-hardware.org/?probe=f8f47e3220) | Mar 23, 2023 |
| Dell          | Precision 7710              | [25a4797475](https://linux-hardware.org/?probe=25a4797475) | Mar 23, 2023 |
| Toshiba       | IS 1413G                    | [3a75d7fb8d](https://linux-hardware.org/?probe=3a75d7fb8d) | Mar 23, 2023 |
| HP            | ProBook 440 G8 Notebook ... | [aba9609828](https://linux-hardware.org/?probe=aba9609828) | Mar 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [f6580b20d3](https://linux-hardware.org/?probe=f6580b20d3) | Mar 22, 2023 |
| Apple         | MacBook5,1                  | [bc6e3fa274](https://linux-hardware.org/?probe=bc6e3fa274) | Mar 22, 2023 |
| Apple         | MacBookAir7,2               | [627590f38c](https://linux-hardware.org/?probe=627590f38c) | Mar 22, 2023 |
| Lenovo        | ThinkPad Twist 33472HU      | [a49ece0e6c](https://linux-hardware.org/?probe=a49ece0e6c) | Mar 22, 2023 |
| Lenovo        | ThinkPad Twist 33472HU      | [315f2256c6](https://linux-hardware.org/?probe=315f2256c6) | Mar 22, 2023 |
| Apple         | MacBookPro8,1               | [b616377b13](https://linux-hardware.org/?probe=b616377b13) | Mar 22, 2023 |
| Apple         | MacBookPro12,1              | [aff8d829e0](https://linux-hardware.org/?probe=aff8d829e0) | Mar 22, 2023 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [99fe9f96c6](https://linux-hardware.org/?probe=99fe9f96c6) | Mar 22, 2023 |
| Apple         | MacBookPro12,1              | [af60ed4cde](https://linux-hardware.org/?probe=af60ed4cde) | Mar 22, 2023 |
| Apple         | MacBookAir7,2               | [3b3376e72c](https://linux-hardware.org/?probe=3b3376e72c) | Mar 21, 2023 |
| HUAWEI        | KPL-W0X                     | [afc1ff125b](https://linux-hardware.org/?probe=afc1ff125b) | Mar 21, 2023 |
| Lenovo        | ThinkPad T420 4180AP3       | [3c100c55be](https://linux-hardware.org/?probe=3c100c55be) | Mar 21, 2023 |
| Lenovo        | ThinkPad T420 4180AP3       | [039724e2c2](https://linux-hardware.org/?probe=039724e2c2) | Mar 21, 2023 |
| Dell          | G15 5511                    | [6d71997e08](https://linux-hardware.org/?probe=6d71997e08) | Mar 21, 2023 |
| Dell          | XPS L421X                   | [fd54af9534](https://linux-hardware.org/?probe=fd54af9534) | Mar 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [afe8ca841c](https://linux-hardware.org/?probe=afe8ca841c) | Mar 21, 2023 |
| Acer          | Aspire 5349                 | [c0f5810e5c](https://linux-hardware.org/?probe=c0f5810e5c) | Mar 21, 2023 |
| MSI           | Prestige 14Evo A11M         | [cac8d6b991](https://linux-hardware.org/?probe=cac8d6b991) | Mar 21, 2023 |
| HP            | Dev One Notebook PC         | [d6ff521952](https://linux-hardware.org/?probe=d6ff521952) | Mar 21, 2023 |
| Acer          | Nitro AN517-55              | [d6393f5710](https://linux-hardware.org/?probe=d6393f5710) | Mar 21, 2023 |
| HP            | Dev One Notebook PC         | [404c84b0ea](https://linux-hardware.org/?probe=404c84b0ea) | Mar 21, 2023 |
| Acer          | Nitro AN517-55              | [edf722e245](https://linux-hardware.org/?probe=edf722e245) | Mar 21, 2023 |
| Gigabyte      | A320M-S2H-CF                | [2ff2eab844](https://linux-hardware.org/?probe=2ff2eab844) | Mar 21, 2023 |
| ASUSTek       | G74Sx                       | [d2b90b7d2f](https://linux-hardware.org/?probe=d2b90b7d2f) | Mar 21, 2023 |
| HP            | ZBook Power 15.6 inch G9... | [2ef051fd19](https://linux-hardware.org/?probe=2ef051fd19) | Mar 20, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [48de9eb9e3](https://linux-hardware.org/?probe=48de9eb9e3) | Mar 20, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [afcac034a9](https://linux-hardware.org/?probe=afcac034a9) | Mar 20, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | [d08f174747](https://linux-hardware.org/?probe=d08f174747) | Mar 20, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [c9b4e3cf00](https://linux-hardware.org/?probe=c9b4e3cf00) | Mar 20, 2023 |
| Dell          | Latitude 5590               | [49922a3223](https://linux-hardware.org/?probe=49922a3223) | Mar 19, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [55dc5e3ef4](https://linux-hardware.org/?probe=55dc5e3ef4) | Mar 19, 2023 |
| MSI           | PS42 8M                     | [aad18852f4](https://linux-hardware.org/?probe=aad18852f4) | Mar 19, 2023 |
| ASUSTek       | G74Sx                       | [f7f92408dc](https://linux-hardware.org/?probe=f7f92408dc) | Mar 19, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [6b6ceb1a1a](https://linux-hardware.org/?probe=6b6ceb1a1a) | Mar 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [e3410282c5](https://linux-hardware.org/?probe=e3410282c5) | Mar 19, 2023 |
| ASUSTek       | S551LB                      | [7d4485326f](https://linux-hardware.org/?probe=7d4485326f) | Mar 18, 2023 |
| GPU Compan... | GWTN141-10                  | [ff8db61ccf](https://linux-hardware.org/?probe=ff8db61ccf) | Mar 18, 2023 |
| ASUSTek       | X540LJ                      | [4eab8887fa](https://linux-hardware.org/?probe=4eab8887fa) | Mar 18, 2023 |
| ASUSTek       | X540LJ                      | [b3bf824f3a](https://linux-hardware.org/?probe=b3bf824f3a) | Mar 18, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [dd296a8801](https://linux-hardware.org/?probe=dd296a8801) | Mar 18, 2023 |
| Lenovo        | ThinkPad T480 20L6S11N00    | [60d80937ea](https://linux-hardware.org/?probe=60d80937ea) | Mar 18, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [91ae5652cc](https://linux-hardware.org/?probe=91ae5652cc) | Mar 18, 2023 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [274f959cfc](https://linux-hardware.org/?probe=274f959cfc) | Mar 17, 2023 |
| Dell          | Latitude E7240              | [cbcae7df75](https://linux-hardware.org/?probe=cbcae7df75) | Mar 17, 2023 |
| Positivo      | N1250                       | [e5ee22876a](https://linux-hardware.org/?probe=e5ee22876a) | Mar 17, 2023 |
| HP            | ProBook 4530s               | [f0abd32fe4](https://linux-hardware.org/?probe=f0abd32fe4) | Mar 17, 2023 |
| Lenovo        | G40-80 80JE                 | [a7a6cc1ab5](https://linux-hardware.org/?probe=a7a6cc1ab5) | Mar 17, 2023 |
| Lenovo        | G40-80 80JE                 | [204994be7f](https://linux-hardware.org/?probe=204994be7f) | Mar 17, 2023 |
| TUXEDO        | Pulse 14 Gen1               | [525b267c31](https://linux-hardware.org/?probe=525b267c31) | Mar 17, 2023 |
| Toshiba       | Satellite Pro C50-A-1E2     | [a1adc8641d](https://linux-hardware.org/?probe=a1adc8641d) | Mar 17, 2023 |
| Toshiba       | Satellite Pro C50-A-1E2     | [a0eea87e02](https://linux-hardware.org/?probe=a0eea87e02) | Mar 17, 2023 |
| Unknown       | Unknown                     | [3eb0bf05b4](https://linux-hardware.org/?probe=3eb0bf05b4) | Mar 17, 2023 |
| Lenovo        | ThinkPad T460s 20FAS0RP0... | [f901058202](https://linux-hardware.org/?probe=f901058202) | Mar 16, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [d6f5cd9505](https://linux-hardware.org/?probe=d6f5cd9505) | Mar 16, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81FN      | [5f48c46d68](https://linux-hardware.org/?probe=5f48c46d68) | Mar 16, 2023 |
| HP            | Laptop 15s-eq1xxx           | [59a304e790](https://linux-hardware.org/?probe=59a304e790) | Mar 15, 2023 |
| Acer          | Aspire A715-42G             | [8bdae79f7a](https://linux-hardware.org/?probe=8bdae79f7a) | Mar 15, 2023 |
| Lenovo        | ThinkPad T440p 20AWS19P0... | [6a2d338526](https://linux-hardware.org/?probe=6a2d338526) | Mar 15, 2023 |
| Razer         | Blade Stealth 13 (Early ... | [eb1d71edb4](https://linux-hardware.org/?probe=eb1d71edb4) | Mar 15, 2023 |
| HCL Infosy... | HCL ME LAPTOP               | [af254fca4d](https://linux-hardware.org/?probe=af254fca4d) | Mar 15, 2023 |
| SAGER         | X8100                       | [90aaefeb9e](https://linux-hardware.org/?probe=90aaefeb9e) | Mar 15, 2023 |
| System76      | Pangolin                    | [4f39796131](https://linux-hardware.org/?probe=4f39796131) | Mar 15, 2023 |
| Dell          | Latitude E7240              | [d4ed345a47](https://linux-hardware.org/?probe=d4ed345a47) | Mar 14, 2023 |
| Lenovo        | ThinkPad T450s 20BWS14G0... | [1161c07721](https://linux-hardware.org/?probe=1161c07721) | Mar 14, 2023 |
| Sony          | VPCZ12V9R                   | [28be5f7f2b](https://linux-hardware.org/?probe=28be5f7f2b) | Mar 14, 2023 |
| Dell          | Latitude E7240              | [4a7d442938](https://linux-hardware.org/?probe=4a7d442938) | Mar 14, 2023 |
| HP            | EliteBook 8560w             | [44d9ce8acb](https://linux-hardware.org/?probe=44d9ce8acb) | Mar 14, 2023 |
| HP            | EliteBook 8560w             | [986fe8c418](https://linux-hardware.org/?probe=986fe8c418) | Mar 14, 2023 |
| Fujitsu       | LIFEBOOK E5512A             | [ae9f2da5a4](https://linux-hardware.org/?probe=ae9f2da5a4) | Mar 14, 2023 |
| HP            | EliteBook 840 G6            | [874706952d](https://linux-hardware.org/?probe=874706952d) | Mar 14, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | [de22b8a7e6](https://linux-hardware.org/?probe=de22b8a7e6) | Mar 14, 2023 |
| Dell          | Inspiron 7348               | [7459d24035](https://linux-hardware.org/?probe=7459d24035) | Mar 13, 2023 |
| Toshiba       | IS 1413G                    | [b93a4bdcbb](https://linux-hardware.org/?probe=b93a4bdcbb) | Mar 13, 2023 |
| Acer          | Aspire 4530                 | [84f4733a96](https://linux-hardware.org/?probe=84f4733a96) | Mar 13, 2023 |
| Acer          | Nitro AN515-58              | [7f2ecd927d](https://linux-hardware.org/?probe=7f2ecd927d) | Mar 13, 2023 |
| Apple         | MacBookPro15,1              | [663f73a08e](https://linux-hardware.org/?probe=663f73a08e) | Mar 13, 2023 |
| Apple         | MacBookPro15,1              | [5d1a30091e](https://linux-hardware.org/?probe=5d1a30091e) | Mar 13, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [a826b1cd32](https://linux-hardware.org/?probe=a826b1cd32) | Mar 13, 2023 |
| Lenovo        | ThinkPad T480s 20L8S7AS0... | [87ef2f6efb](https://linux-hardware.org/?probe=87ef2f6efb) | Mar 12, 2023 |
| HUAWEI        | NBM-WXX9                    | [27b710cd68](https://linux-hardware.org/?probe=27b710cd68) | Mar 12, 2023 |
| Google        | Kefka                       | [4a54e34e44](https://linux-hardware.org/?probe=4a54e34e44) | Mar 12, 2023 |
| ASUSTek       | ZenBook UX434IQ_Q407IQ      | [7090114437](https://linux-hardware.org/?probe=7090114437) | Mar 12, 2023 |
| Dell          | Inspiron 5452               | [2c8ca0e296](https://linux-hardware.org/?probe=2c8ca0e296) | Mar 12, 2023 |
| Positivo B... | VJFE41F11X-XXXXXX           | [99f410d801](https://linux-hardware.org/?probe=99f410d801) | Mar 11, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | [e101a1c94c](https://linux-hardware.org/?probe=e101a1c94c) | Mar 11, 2023 |
| HONOR         | NMH-WCX9                    | [d8cf10f11d](https://linux-hardware.org/?probe=d8cf10f11d) | Mar 11, 2023 |
| HP            | ZBook 17                    | [a775bc33c5](https://linux-hardware.org/?probe=a775bc33c5) | Mar 11, 2023 |
| Maibenben     | P748                        | [a44d1bb8e4](https://linux-hardware.org/?probe=a44d1bb8e4) | Mar 11, 2023 |
| Toshiba       | IS 1413G                    | [39cc207ce7](https://linux-hardware.org/?probe=39cc207ce7) | Mar 11, 2023 |
| Lenovo        | ThinkPad L440 20ASS0ET00    | [2ac6dfff4f](https://linux-hardware.org/?probe=2ac6dfff4f) | Mar 11, 2023 |
| GPD           | G1619-04                    | [302ff30130](https://linux-hardware.org/?probe=302ff30130) | Mar 11, 2023 |
| GPD           | G1619-04                    | [d8f5b9eec9](https://linux-hardware.org/?probe=d8f5b9eec9) | Mar 11, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [96f4bd0a52](https://linux-hardware.org/?probe=96f4bd0a52) | Mar 10, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [969ab4279f](https://linux-hardware.org/?probe=969ab4279f) | Mar 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [c44f0eab3e](https://linux-hardware.org/?probe=c44f0eab3e) | Mar 10, 2023 |
| Lenovo        | ThinkPad T440p 20AWS19P0... | [44867c946f](https://linux-hardware.org/?probe=44867c946f) | Mar 10, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [50dd87563b](https://linux-hardware.org/?probe=50dd87563b) | Mar 10, 2023 |
| Samsung       | R430/R480/R440              | [cdb2525b51](https://linux-hardware.org/?probe=cdb2525b51) | Mar 10, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [410a5a70f3](https://linux-hardware.org/?probe=410a5a70f3) | Mar 10, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [eac4ae85a4](https://linux-hardware.org/?probe=eac4ae85a4) | Mar 10, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | [baffc24bef](https://linux-hardware.org/?probe=baffc24bef) | Mar 10, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [187761b57d](https://linux-hardware.org/?probe=187761b57d) | Mar 09, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [4e1196658a](https://linux-hardware.org/?probe=4e1196658a) | Mar 09, 2023 |
| HP            | ENVY Notebook               | [8a063efa19](https://linux-hardware.org/?probe=8a063efa19) | Mar 09, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [a8d1bd3e81](https://linux-hardware.org/?probe=a8d1bd3e81) | Mar 09, 2023 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | [7805fe229d](https://linux-hardware.org/?probe=7805fe229d) | Mar 08, 2023 |
| Razer         | Blade 15 Advanced Model ... | [46fa9eab7d](https://linux-hardware.org/?probe=46fa9eab7d) | Mar 08, 2023 |
| Google        | Bobba                       | [01d8f57c7e](https://linux-hardware.org/?probe=01d8f57c7e) | Mar 08, 2023 |
| Lenovo        | IdeaPad U310                | [f666446ecb](https://linux-hardware.org/?probe=f666446ecb) | Mar 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [3ff5ff8f2d](https://linux-hardware.org/?probe=3ff5ff8f2d) | Mar 07, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [3b02985778](https://linux-hardware.org/?probe=3b02985778) | Mar 07, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [e6e0d7226d](https://linux-hardware.org/?probe=e6e0d7226d) | Mar 07, 2023 |
| HP            | Dev One Notebook PC         | [4a698cb3eb](https://linux-hardware.org/?probe=4a698cb3eb) | Mar 07, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [8a6c736217](https://linux-hardware.org/?probe=8a6c736217) | Mar 07, 2023 |
| Toshiba       | IS 1413G                    | [12954ccbdb](https://linux-hardware.org/?probe=12954ccbdb) | Mar 07, 2023 |
| Google        | Lillipup                    | [b924f92de8](https://linux-hardware.org/?probe=b924f92de8) | Mar 07, 2023 |
| HP            | Dev One Notebook PC         | [5a03b7e11e](https://linux-hardware.org/?probe=5a03b7e11e) | Mar 07, 2023 |
| Apple         | MacBookPro8,1               | [bef545e821](https://linux-hardware.org/?probe=bef545e821) | Mar 07, 2023 |
| Dell          | Inspiron 16 7610            | [625691c490](https://linux-hardware.org/?probe=625691c490) | Mar 06, 2023 |
| Dell          | Inspiron 16 7610            | [66b4f88fb7](https://linux-hardware.org/?probe=66b4f88fb7) | Mar 06, 2023 |
| HP            | 3115m                       | [87abd0ac9d](https://linux-hardware.org/?probe=87abd0ac9d) | Mar 06, 2023 |
| Dell          | G7 7588                     | [a50e6bef64](https://linux-hardware.org/?probe=a50e6bef64) | Mar 06, 2023 |
| HUAWEI        | KPL-W0X                     | [76ebbe553f](https://linux-hardware.org/?probe=76ebbe553f) | Mar 06, 2023 |
| Apple         | MacBookAir7,2               | [ae4d8e9128](https://linux-hardware.org/?probe=ae4d8e9128) | Mar 06, 2023 |
| MSI           | Vector GP76 12UHSO          | [e82fbd8c0a](https://linux-hardware.org/?probe=e82fbd8c0a) | Mar 06, 2023 |
| Acer          | Swift SFX14-41G             | [baff849073](https://linux-hardware.org/?probe=baff849073) | Mar 05, 2023 |
| HP            | ProBook 450 G1              | [a6c8ba1040](https://linux-hardware.org/?probe=a6c8ba1040) | Mar 05, 2023 |
| Apple         | MacBookAir7,2               | [fef18d1795](https://linux-hardware.org/?probe=fef18d1795) | Mar 05, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Pop!_OS_22.04/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 6.2.6-76060206-generic   | 463       | 21.56%  |
| 5.19.0-76051900-generic  | 273       | 12.72%  |
| 6.0.12-76060006-generic  | 265       | 12.34%  |
| 5.17.5-76051705-generic  | 231       | 10.76%  |
| 6.4.6-76060406-generic   | 163       | 7.59%   |
| 6.0.6-76060006-generic   | 162       | 7.55%   |
| 5.18.10-76051810-generic | 118       | 5.5%    |
| 5.17.15-76051715-generic | 104       | 4.84%   |
| 6.2.0-76060200-generic   | 76        | 3.54%   |
| 5.16.19-76051619-generic | 73        | 3.4%    |
| 6.0.2-76060002-generic   | 59        | 2.75%   |
| 6.1.11-76060111-generic  | 54        | 2.52%   |
| 6.0.3-76060003-generic   | 24        | 1.12%   |
| 5.19.16-76051916-generic | 21        | 0.98%   |
| 6.4.0-060400-generic     | 2         | 0.09%   |
| 6.3.7-060307-generic     | 2         | 0.09%   |
| 6.2.11-060211-generic    | 2         | 0.09%   |
| 6.1.0-1006-oem           | 2         | 0.09%   |
| 5.17.5-051705-generic    | 2         | 0.09%   |
| 5.16.15-76051615-generic | 2         | 0.09%   |
| 6.5.5-x64v3-xanmod1      | 1         | 0.05%   |
| 6.5.0-rc2                | 1         | 0.05%   |
| 6.4.5-x64v2-xanmod1      | 1         | 0.05%   |
| 6.4.3-060403-generic     | 1         | 0.05%   |
| 6.4.12-2-liquorix-amd64  | 1         | 0.05%   |
| 6.3.9-x64v3-xanmod1      | 1         | 0.05%   |
| 6.3.9-060309-generic     | 1         | 0.05%   |
| 6.3.4-060304-generic     | 1         | 0.05%   |
| 6.3.2-060302-generic     | 1         | 0.05%   |
| 6.3.0-060300-generic     | 1         | 0.05%   |
| 6.2.9-1-liquorix-amd64   | 1         | 0.05%   |
| 6.2.6-060206-generic     | 1         | 0.05%   |
| 6.2.16-060216-generic    | 1         | 0.05%   |
| 6.2.10-060210-generic    | 1         | 0.05%   |
| 6.2.1-060201-generic     | 1         | 0.05%   |
| 6.1.9-x64v1-xanmod1      | 1         | 0.05%   |
| 6.1.9-060109-generic     | 1         | 0.05%   |
| 6.1.8-060108-generic     | 1         | 0.05%   |
| 6.1.7-060107-generic     | 1         | 0.05%   |
| 6.1.18-x64v2-xanmod1     | 1         | 0.05%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2.6   | 464       | 21.62%  |
| 5.19.0  | 276       | 12.86%  |
| 6.0.12  | 265       | 12.35%  |
| 5.17.5  | 234       | 10.9%   |
| 6.4.6   | 163       | 7.6%    |
| 6.0.6   | 162       | 7.55%   |
| 5.18.10 | 118       | 5.5%    |
| 5.17.15 | 104       | 4.85%   |
| 6.2.0   | 76        | 3.54%   |
| 5.16.19 | 73        | 3.4%    |
| 6.0.2   | 60        | 2.8%    |
| 6.1.11  | 54        | 2.52%   |
| 6.0.3   | 24        | 1.12%   |
| 5.19.16 | 21        | 0.98%   |
| 6.4.0   | 2         | 0.09%   |
| 6.3.9   | 2         | 0.09%   |
| 6.3.7   | 2         | 0.09%   |
| 6.2.11  | 2         | 0.09%   |
| 6.1.9   | 2         | 0.09%   |
| 6.1.0   | 2         | 0.09%   |
| 6.0.9   | 2         | 0.09%   |
| 6.0.0   | 2         | 0.09%   |
| 5.17.0  | 2         | 0.09%   |
| 5.16.15 | 2         | 0.09%   |
| 5.15.0  | 2         | 0.09%   |
| 6.5.5   | 1         | 0.05%   |
| 6.5.0   | 1         | 0.05%   |
| 6.4.5   | 1         | 0.05%   |
| 6.4.3   | 1         | 0.05%   |
| 6.4.12  | 1         | 0.05%   |
| 6.3.4   | 1         | 0.05%   |
| 6.3.2   | 1         | 0.05%   |
| 6.3.0   | 1         | 0.05%   |
| 6.2.9   | 1         | 0.05%   |
| 6.2.16  | 1         | 0.05%   |
| 6.2.10  | 1         | 0.05%   |
| 6.2.1   | 1         | 0.05%   |
| 6.1.8   | 1         | 0.05%   |
| 6.1.7   | 1         | 0.05%   |
| 6.1.18  | 1         | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2     | 541       | 25.6%   |
| 6.0     | 497       | 23.52%  |
| 5.17    | 337       | 15.95%  |
| 5.19    | 299       | 14.15%  |
| 6.4     | 167       | 7.9%    |
| 5.18    | 122       | 5.77%   |
| 5.16    | 76        | 3.6%    |
| 6.1     | 61        | 2.89%   |
| 6.3     | 7         | 0.33%   |
| 5.15    | 4         | 0.19%   |
| 6.5     | 2         | 0.09%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 1951      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 1898      | 97.13%  |
| KDE5            | 17        | 0.87%   |
| Unknown         | 17        | 0.87%   |
| X-Cinnamon      | 6         | 0.31%   |
| Unity           | 4         | 0.2%    |
| GNOME Flashback | 4         | 0.2%    |
| MATE            | 2         | 0.1%    |
| LXQt            | 2         | 0.1%    |
| XFCE            | 1         | 0.05%   |
| i3              | 1         | 0.05%   |
| Cinnamon        | 1         | 0.05%   |
| awesome         | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 1852      | 94.44%  |
| Wayland | 95        | 4.84%   |
| Unknown | 11        | 0.56%   |
| Tty     | 3         | 0.15%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1392      | 70.7%   |
| GDM3    | 568       | 28.85%  |
| GDM     | 5         | 0.25%   |
| SDDM    | 3         | 0.15%   |
| LightDM | 1         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 1176      | 59.97%  |
| en_GB   | 127       | 6.48%   |
| pt_BR   | 113       | 5.76%   |
| de_DE   | 78        | 3.98%   |
| C       | 52        | 2.65%   |
| it_IT   | 45        | 2.29%   |
| en_AU   | 38        | 1.94%   |
| fr_FR   | 35        | 1.78%   |
| es_ES   | 32        | 1.63%   |
| ru_RU   | 25        | 1.27%   |
| en_CA   | 24        | 1.22%   |
| pl_PL   | 20        | 1.02%   |
| Unknown | 16        | 0.82%   |
| nb_NO   | 15        | 0.76%   |
| pt_PT   | 13        | 0.66%   |
| sv_SE   | 11        | 0.56%   |
| en_NZ   | 11        | 0.56%   |
| en_IE   | 10        | 0.51%   |
| es_MX   | 9         | 0.46%   |
| en_IN   | 9         | 0.46%   |
| nl_NL   | 8         | 0.41%   |
| fi_FI   | 8         | 0.41%   |
| tr_TR   | 7         | 0.36%   |
| de_CH   | 7         | 0.36%   |
| en_ZA   | 6         | 0.31%   |
| fr_CA   | 5         | 0.25%   |
| es_CL   | 5         | 0.25%   |
| es_AR   | 5         | 0.25%   |
| cs_CZ   | 5         | 0.25%   |
| es_CO   | 4         | 0.2%    |
| en_DK   | 4         | 0.2%    |
| da_DK   | 4         | 0.2%    |
| de_AT   | 3         | 0.15%   |
| fr_CH   | 2         | 0.1%    |
| fr_BE   | 2         | 0.1%    |
| en_SG   | 2         | 0.1%    |
| en_PH   | 2         | 0.1%    |
| en_IL   | 2         | 0.1%    |
| en_AG   | 2         | 0.1%    |
| zh_CN   | 1         | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 1410      | 71.65%  |
| EFI  | 558       | 28.35%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 1853      | 94.64%  |
| Btrfs   | 66        | 3.37%   |
| Overlay | 33        | 1.69%   |
| Xfs     | 5         | 0.26%   |
| Zfs     | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1376      | 69.88%  |
| GPT     | 559       | 28.39%  |
| MBR     | 34        | 1.73%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1902      | 97.29%  |
| Yes       | 53        | 2.71%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1765      | 90.1%   |
| Yes       | 194       | 9.9%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 394       | 20.19%  |
| Dell                   | 316       | 16.2%   |
| Hewlett-Packard        | 274       | 14.04%  |
| ASUSTek Computer       | 242       | 12.4%   |
| Apple                  | 139       | 7.12%   |
| Acer                   | 139       | 7.12%   |
| MSI                    | 70        | 3.59%   |
| System76               | 67        | 3.43%   |
| Toshiba                | 38        | 1.95%   |
| Samsung Electronics    | 31        | 1.59%   |
| HUAWEI                 | 28        | 1.44%   |
| Google                 | 17        | 0.87%   |
| Alienware              | 15        | 0.77%   |
| Notebook               | 14        | 0.72%   |
| Fujitsu                | 11        | 0.56%   |
| Sony                   | 10        | 0.51%   |
| GPU Company            | 10        | 0.51%   |
| Razer                  | 9         | 0.46%   |
| Gigabyte Technology    | 9         | 0.46%   |
| Timi                   | 8         | 0.41%   |
| Positivo               | 8         | 0.41%   |
| Framework              | 8         | 0.41%   |
| HONOR                  | 7         | 0.36%   |
| Unknown                | 7         | 0.36%   |
| Avell High Performance | 6         | 0.31%   |
| TUXEDO                 | 4         | 0.21%   |
| Schenker               | 4         | 0.21%   |
| PC Specialist          | 4         | 0.21%   |
| Clevo                  | 4         | 0.21%   |
| Medion                 | 3         | 0.15%   |
| LG Electronics         | 3         | 0.15%   |
| GPD                    | 3         | 0.15%   |
| Valve                  | 2         | 0.1%    |
| Panasonic              | 2         | 0.1%    |
| Packard Bell           | 2         | 0.1%    |
| OriginPC               | 2         | 0.1%    |
| ASRock                 | 2         | 0.1%    |
| A-DATA Technology      | 2         | 0.1%    |
| Wortmann AG            | 1         | 0.05%   |
| VANT                   | 1         | 0.05%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| System76 Oryx Pro                   | 18        | 0.92%   |
| System76 Lemur Pro                  | 14        | 0.72%   |
| Unknown                             | 14        | 0.72%   |
| Apple MacBookAir7,2                 | 13        | 0.67%   |
| System76 Gazelle                    | 12        | 0.62%   |
| Apple MacBookPro12,1                | 12        | 0.62%   |
| HP Dev One Notebook PC              | 10        | 0.51%   |
| Apple MacBookPro9,2                 | 10        | 0.51%   |
| Apple MacBookPro11,3                | 9         | 0.46%   |
| Apple MacBookAir6,2                 | 9         | 0.46%   |
| Apple MacBookPro8,1                 | 8         | 0.41%   |
| System76 Galago Pro                 | 7         | 0.36%   |
| Dell XPS 15 9520                    | 7         | 0.36%   |
| Apple MacBookPro7,1                 | 7         | 0.36%   |
| System76 Darter Pro                 | 6         | 0.31%   |
| Lenovo IdeaPad S145-15API 81V7      | 6         | 0.31%   |
| HP Pavilion 15                      | 6         | 0.31%   |
| HP Notebook                         | 6         | 0.31%   |
| Dell XPS 15 9570                    | 6         | 0.31%   |
| Dell XPS 13 9310                    | 6         | 0.31%   |
| Dell Latitude E7240                 | 6         | 0.31%   |
| Acer Aspire A515-45                 | 6         | 0.31%   |
| System76 Pangolin                   | 5         | 0.26%   |
| Lenovo Legion 5 15ACH6H 82JU        | 5         | 0.26%   |
| Lenovo IdeaPad 5 Pro 16ARH7 82SN    | 5         | 0.26%   |
| Lenovo IdeaPad 330-15IKB 81DE       | 5         | 0.26%   |
| Lenovo IdeaPad 3 15ALC6 82MF        | 5         | 0.26%   |
| Framework Laptop                    | 5         | 0.26%   |
| Dell XPS 15 7590                    | 5         | 0.26%   |
| Dell XPS 13 9360                    | 5         | 0.26%   |
| Apple MacBookPro10,1                | 5         | 0.26%   |
| Apple MacBook5,1                    | 5         | 0.26%   |
| Lenovo Legion 5 15ARH05H 82B1       | 4         | 0.21%   |
| Lenovo IdeaPad Gaming 3 15IAH7 82S9 | 4         | 0.21%   |
| Lenovo IdeaPad 330-15IKB 81FE       | 4         | 0.21%   |
| HP Victus by Laptop 16-e0xxx        | 4         | 0.21%   |
| HP Pavilion Notebook                | 4         | 0.21%   |
| HP Pavilion Gaming Laptop 15-ec0xxx | 4         | 0.21%   |
| HP Pavilion dv6                     | 4         | 0.21%   |
| HP Pavilion Aero Laptop 13-be0xxx   | 4         | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 178       | 9.12%   |
| Lenovo IdeaPad     | 103       | 5.28%   |
| Acer Aspire        | 86        | 4.41%   |
| Dell Inspiron      | 84        | 4.31%   |
| Dell Latitude      | 78        | 4%      |
| Dell XPS           | 66        | 3.38%   |
| HP Pavilion        | 54        | 2.77%   |
| ASUS VivoBook      | 50        | 2.56%   |
| ASUS ROG           | 47        | 2.41%   |
| HP Laptop          | 45        | 2.31%   |
| HP EliteBook       | 45        | 2.31%   |
| Lenovo Legion      | 44        | 2.26%   |
| Dell Precision     | 35        | 1.79%   |
| Toshiba Satellite  | 32        | 1.64%   |
| HP ProBook         | 31        | 1.59%   |
| ASUS ASUS          | 29        | 1.49%   |
| Acer Swift         | 22        | 1.13%   |
| ASUS Zenbook       | 20        | 1.03%   |
| HP ZBook           | 19        | 0.97%   |
| Dell Vostro        | 19        | 0.97%   |
| Apple MacBookPro11 | 19        | 0.97%   |
| System76 Oryx      | 18        | 0.92%   |
| Acer Nitro         | 18        | 0.92%   |
| System76 Lemur     | 14        | 0.72%   |
| HP OMEN            | 14        | 0.72%   |
| Unknown            | 14        | 0.72%   |
| Lenovo ThinkBook   | 13        | 0.67%   |
| HP ENVY            | 13        | 0.67%   |
| Apple MacBookAir7  | 13        | 0.67%   |
| System76 Gazelle   | 12        | 0.62%   |
| Apple MacBookPro12 | 12        | 0.62%   |
| Lenovo Yoga        | 11        | 0.56%   |
| Dell G15           | 11        | 0.56%   |
| Apple MacBookPro9  | 11        | 0.56%   |
| Apple MacBookPro8  | 11        | 0.56%   |
| HP Dev             | 10        | 0.51%   |
| Apple MacBookPro5  | 10        | 0.51%   |
| Apple MacBookAir6  | 10        | 0.51%   |
| Razer Blade        | 9         | 0.46%   |
| Fujitsu LIFEBOOK   | 9         | 0.46%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 308       | 15.79%  |
| 2022    | 231       | 11.84%  |
| 2020    | 216       | 11.07%  |
| 2019    | 171       | 8.76%   |
| 2018    | 162       | 8.3%    |
| 2013    | 126       | 6.46%   |
| 2015    | 106       | 5.43%   |
| 2012    | 104       | 5.33%   |
| 2016    | 101       | 5.18%   |
| 2011    | 95        | 4.87%   |
| 2017    | 89        | 4.56%   |
| 2014    | 77        | 3.95%   |
| 2010    | 51        | 2.61%   |
| 2009    | 45        | 2.31%   |
| 2023    | 42        | 2.15%   |
| 2008    | 20        | 1.03%   |
| 2007    | 5         | 0.26%   |
| 2006    | 1         | 0.05%   |
| Unknown | 1         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1951      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1951      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1883      | 96.51%  |
| Yes  | 68        | 3.49%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 552       | 28.09%  |
| 16.01-24.0  | 472       | 24.02%  |
| 8.01-16.0   | 378       | 19.24%  |
| 3.01-4.0    | 231       | 11.76%  |
| 32.01-64.0  | 226       | 11.5%   |
| 64.01-256.0 | 52        | 2.65%   |
| 24.01-32.0  | 40        | 2.04%   |
| 1.01-2.0    | 8         | 0.41%   |
| 2.01-3.0    | 6         | 0.31%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 660       | 31.4%   |
| 2.01-3.0   | 589       | 28.02%  |
| 3.01-4.0   | 451       | 21.46%  |
| 1.01-2.0   | 186       | 8.85%   |
| 8.01-16.0  | 178       | 8.47%   |
| 16.01-24.0 | 29        | 1.38%   |
| 24.01-32.0 | 7         | 0.33%   |
| 0.51-1.0   | 2         | 0.1%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1436      | 72.78%  |
| 2      | 457       | 23.16%  |
| 3      | 65        | 3.29%   |
| 0      | 8         | 0.41%   |
| 4      | 5         | 0.25%   |
| 7      | 1         | 0.05%   |
| 5      | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1532      | 78.4%   |
| Yes       | 422       | 21.6%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1472      | 74.99%  |
| No        | 491       | 25.01%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1928      | 98.82%  |
| No        | 23        | 1.18%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1677      | 85.56%  |
| No        | 283       | 14.44%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 535       | 27.28%  |
| Brazil       | 167       | 8.52%   |
| Germany      | 119       | 6.07%   |
| UK           | 84        | 4.28%   |
| Italy        | 79        | 4.03%   |
| India        | 75        | 3.82%   |
| Canada       | 67        | 3.42%   |
| France       | 51        | 2.6%    |
| Australia    | 51        | 2.6%    |
| Russia       | 43        | 2.19%   |
| Spain        | 39        | 1.99%   |
| Netherlands  | 38        | 1.94%   |
| Poland       | 32        | 1.63%   |
| Norway       | 29        | 1.48%   |
| Sweden       | 28        | 1.43%   |
| Mexico       | 28        | 1.43%   |
| Portugal     | 27        | 1.38%   |
| Turkey       | 25        | 1.27%   |
| New Zealand  | 19        | 0.97%   |
| Czechia      | 19        | 0.97%   |
| Philippines  | 18        | 0.92%   |
| Indonesia    | 18        | 0.92%   |
| Switzerland  | 16        | 0.82%   |
| Romania      | 16        | 0.82%   |
| Denmark      | 16        | 0.82%   |
| Argentina    | 16        | 0.82%   |
| Finland      | 15        | 0.76%   |
| Serbia       | 14        | 0.71%   |
| Greece       | 13        | 0.66%   |
| Chile        | 13        | 0.66%   |
| Thailand     | 11        | 0.56%   |
| Belgium      | 11        | 0.56%   |
| Austria      | 11        | 0.56%   |
| South Africa | 10        | 0.51%   |
| Bulgaria     | 10        | 0.51%   |
| Ireland      | 9         | 0.46%   |
| Hungary      | 9         | 0.46%   |
| Malaysia     | 8         | 0.41%   |
| Colombia     | 8         | 0.41%   |
| Vietnam      | 7         | 0.36%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Sao Paulo      | 18        | 0.89%   |
| Oslo           | 17        | 0.84%   |
| Brisbane       | 16        | 0.79%   |
| Milan          | 15        | 0.74%   |
| Melbourne      | 15        | 0.74%   |
| Istanbul       | 14        | 0.69%   |
| Warsaw         | 13        | 0.64%   |
| Bengaluru      | 13        | 0.64%   |
| Moscow         | 12        | 0.59%   |
| Helsinki       | 12        | 0.59%   |
| Berlin         | 12        | 0.59%   |
| Sydney         | 10        | 0.49%   |
| Rio de Janeiro | 10        | 0.49%   |
| Madrid         | 10        | 0.49%   |
| Auckland       | 10        | 0.49%   |
| Seattle        | 9         | 0.44%   |
| New York       | 9         | 0.44%   |
| Munich         | 9         | 0.44%   |
| Lisbon         | 9         | 0.44%   |
| Denver         | 9         | 0.44%   |
| Chicago        | 9         | 0.44%   |
| Belgrade       | 9         | 0.44%   |
| Vienna         | 8         | 0.39%   |
| Rome           | 8         | 0.39%   |
| Prague         | 8         | 0.39%   |
| Paris          | 8         | 0.39%   |
| Mumbai         | 8         | 0.39%   |
| London         | 8         | 0.39%   |
| St Petersburg  | 7         | 0.35%   |
| Sofia          | 7         | 0.35%   |
| Singapore      | 7         | 0.35%   |
| Los Angeles    | 7         | 0.35%   |
| Hamburg        | 7         | 0.35%   |
| Dallas         | 7         | 0.35%   |
| Calgary        | 7         | 0.35%   |
| Bucharest      | 7         | 0.35%   |
| Zurich         | 6         | 0.3%    |
| Stockholm      | 6         | 0.3%    |
| San Jose       | 6         | 0.3%    |
| San Antonio    | 6         | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 463       | 609    | 18.75%  |
| WDC                            | 215       | 243    | 8.71%   |
| SanDisk                        | 210       | 261    | 8.51%   |
| Seagate                        | 164       | 189    | 6.64%   |
| SK hynix                       | 151       | 170    | 6.12%   |
| Toshiba                        | 132       | 154    | 5.35%   |
| Kingston                       | 128       | 144    | 5.18%   |
| Micron Technology              | 106       | 122    | 4.29%   |
| Intel                          | 90        | 104    | 3.65%   |
| Unknown                        | 88        | 105    | 3.56%   |
| Crucial                        | 80        | 90     | 3.24%   |
| Apple                          | 77        | 84     | 3.12%   |
| HGST                           | 52        | 58     | 2.11%   |
| KIOXIA                         | 41        | 44     | 1.66%   |
| Micron/Crucial Technology      | 29        | 36     | 1.17%   |
| Hitachi                        | 28        | 32     | 1.13%   |
| A-DATA Technology              | 27        | 32     | 1.09%   |
| Phison                         | 25        | 27     | 1.01%   |
| China                          | 25        | 31     | 1.01%   |
| PNY                            | 22        | 29     | 0.89%   |
| Phison Electronics             | 19        | 21     | 0.77%   |
| Kingston Technology Company    | 18        | 19     | 0.73%   |
| Silicon Motion                 | 16        | 19     | 0.65%   |
| Unknown                        | 13        | 17     | 0.53%   |
| Intenso                        | 12        | 16     | 0.49%   |
| LITEONIT                       | 11        | 18     | 0.45%   |
| Netac                          | 10        | 10     | 0.41%   |
| LITEON                         | 10        | 11     | 0.41%   |
| KingSpec                       | 10        | 11     | 0.41%   |
| Union Memory (Shenzhen)        | 9         | 11     | 0.36%   |
| SPCC                           | 8         | 8      | 0.32%   |
| Solid State Storage Technology | 8         | 8      | 0.32%   |
| Solid State Storage            | 8         | 9      | 0.32%   |
| ADATA Technology               | 8         | 8      | 0.32%   |
| Transcend                      | 7         | 8      | 0.28%   |
| Team                           | 7         | 7      | 0.28%   |
| SSSTC                          | 5         | 5      | 0.2%    |
| Patriot                        | 5         | 6      | 0.2%    |
| JMicron Technology             | 5         | 6      | 0.2%    |
| MAXIO Technology (Hangzhou)    | 4         | 4      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 53        | 2.06%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 33        | 1.28%   |
| Kingston SA400S37240G 240GB SSD                     | 33        | 1.28%   |
| Seagate ST1000LM035-1RK172 1TB                      | 30        | 1.16%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 500GB | 20        | 0.78%   |
| SanDisk NVMe SSD Drive 1TB                          | 19        | 0.74%   |
| HGST HTS721010A9E630 1TB                            | 18        | 0.7%    |
| Apple SSD SM0128G 121GB                             | 18        | 0.7%    |
| Toshiba MQ04ABF100 1TB                              | 17        | 0.66%   |
| Samsung NVMe SSD Drive 512GB                        | 17        | 0.66%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                 | 17        | 0.66%   |
| Intel SSD 660P Series 1024GB                        | 17        | 0.66%   |
| Crucial CT240BX500SSD1 240GB                        | 17        | 0.66%   |
| Unknown MMC Card  64GB                              | 16        | 0.62%   |
| Unknown MMC Card  32GB                              | 16        | 0.62%   |
| Toshiba MQ01ABD100 1TB                              | 16        | 0.62%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB                | 15        | 0.58%   |
| Kingston SA400S37480G 480GB SSD                     | 15        | 0.58%   |
| SK hynix NVMe SSD Drive 512GB                       | 14        | 0.54%   |
| Unknown                                             | 13        | 0.5%    |
| Unknown MMC Card  128GB                             | 12        | 0.47%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 12        | 0.47%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB    | 12        | 0.47%   |
| Intel SSDPEKNU512GZ 512GB                           | 12        | 0.47%   |
| WDC WD10SPZX-24Z10 1TB                              | 11        | 0.43%   |
| SanDisk NVMe SSD Drive 512GB                        | 11        | 0.43%   |
| Kingston SA400S37120G 120GB SSD                     | 11        | 0.43%   |
| Seagate ST1000LM049-2GH172 1TB                      | 10        | 0.39%   |
| SanDisk NVMe SSD Drive 256GB                        | 10        | 0.39%   |
| Samsung SSD 860 EVO 500GB                           | 10        | 0.39%   |
| Samsung SSD 850 EVO 500GB                           | 10        | 0.39%   |
| Samsung NVMe SSD Drive 1TB                          | 10        | 0.39%   |
| Unknown MMC Card  16GB                              | 9         | 0.35%   |
| SK hynix NVMe SSD Drive 1024GB                      | 9         | 0.35%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 256GB     | 9         | 0.35%   |
| Sandisk WD Black SN850 1TB                          | 9         | 0.35%   |
| Samsung SSD 970 EVO Plus 1TB                        | 9         | 0.35%   |
| Samsung SSD 870 EVO 500GB                           | 9         | 0.35%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 9         | 0.35%   |
| Samsung NVMe SSD Drive 500GB                        | 9         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 159       | 184    | 34.87%  |
| WDC                 | 110       | 127    | 24.12%  |
| Toshiba             | 79        | 90     | 17.32%  |
| HGST                | 52        | 58     | 11.4%   |
| Hitachi             | 28        | 32     | 6.14%   |
| Unknown             | 7         | 7      | 1.54%   |
| Samsung Electronics | 6         | 6      | 1.32%   |
| Fujitsu             | 4         | 4      | 0.88%   |
| Apple               | 3         | 4      | 0.66%   |
| Intenso             | 2         | 5      | 0.44%   |
| USB3.0              | 1         | 1      | 0.22%   |
| StoreJet            | 1         | 1      | 0.22%   |
| SABRENT             | 1         | 2      | 0.22%   |
| HGST HDN            | 1         | 1      | 0.22%   |
| External            | 1         | 1      | 0.22%   |
| Asm                 | 1         | 1      | 0.22%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 144       | 185    | 19.33%  |
| Kingston            | 94        | 103    | 12.62%  |
| SanDisk             | 74        | 92     | 9.93%   |
| Crucial             | 71        | 81     | 9.53%   |
| Apple               | 62        | 67     | 8.32%   |
| WDC                 | 42        | 48     | 5.64%   |
| China               | 25        | 31     | 3.36%   |
| SK hynix            | 20        | 21     | 2.68%   |
| PNY                 | 20        | 27     | 2.68%   |
| Micron Technology   | 20        | 23     | 2.68%   |
| Toshiba             | 16        | 16     | 2.15%   |
| LITEONIT            | 11        | 18     | 1.48%   |
| Intel               | 11        | 12     | 1.48%   |
| A-DATA Technology   | 11        | 13     | 1.48%   |
| KingSpec            | 10        | 11     | 1.34%   |
| LITEON              | 9         | 10     | 1.21%   |
| Netac               | 7         | 7      | 0.94%   |
| Intenso             | 7         | 7      | 0.94%   |
| Transcend           | 6         | 7      | 0.81%   |
| SPCC                | 6         | 6      | 0.81%   |
| Patriot             | 4         | 5      | 0.54%   |
| JMicron Technology  | 4         | 5      | 0.54%   |
| Apacer              | 4         | 8      | 0.54%   |
| MyDigitalSSD        | 3         | 3      | 0.4%    |
| Hewlett-Packard     | 3         | 3      | 0.4%    |
| Dogfish             | 3         | 3      | 0.4%    |
| Teclast             | 2         | 2      | 0.27%   |
| Team                | 2         | 2      | 0.27%   |
| PHD 3.0             | 2         | 2      | 0.27%   |
| KingDian            | 2         | 2      | 0.27%   |
| Inland              | 2         | 2      | 0.27%   |
| GOODRAM             | 2         | 2      | 0.27%   |
| Fanxiang            | 2         | 2      | 0.27%   |
| Unknown             | 2         | 2      | 0.27%   |
| Wibtek              | 1         | 1      | 0.13%   |
| W800S               | 1         | 1      | 0.13%   |
| TwinMOS             | 1         | 1      | 0.13%   |
| TrekStor            | 1         | 1      | 0.13%   |
| Teutons             | 1         | 1      | 0.13%   |
| TEAM TM8            | 1         | 1      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 1036      | 1379   | 45.36%  |
| SSD     | 688       | 872    | 30.12%  |
| HDD     | 439       | 524    | 19.22%  |
| MMC     | 84        | 98     | 3.68%   |
| Unknown | 37        | 53     | 1.62%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 1033      | 1375   | 46.74%  |
| SATA | 1004      | 1333   | 45.43%  |
| SAS  | 89        | 120    | 4.03%   |
| MMC  | 84        | 98     | 3.8%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 712       | 918    | 63.63%  |
| 0.51-1.0   | 364       | 417    | 32.53%  |
| 1.01-2.0   | 33        | 42     | 2.95%   |
| 3.01-4.0   | 4         | 4      | 0.36%   |
| 4.01-10.0  | 4         | 10     | 0.36%   |
| 2.01-3.0   | 2         | 5      | 0.18%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 627       | 31.32%  |
| 251-500        | 590       | 29.47%  |
| 501-1000       | 419       | 20.93%  |
| 1001-2000      | 132       | 6.59%   |
| 51-100         | 69        | 3.45%   |
| 1-20           | 46        | 2.3%    |
| 2001-3000      | 39        | 1.95%   |
| More than 3000 | 35        | 1.75%   |
| 21-50          | 29        | 1.45%   |
| Unknown        | 16        | 0.8%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 650       | 31.28%  |
| 21-50          | 502       | 24.16%  |
| 101-250        | 313       | 15.06%  |
| 51-100         | 286       | 13.76%  |
| 251-500        | 185       | 8.9%    |
| 501-1000       | 87        | 4.19%   |
| 1001-2000      | 23        | 1.11%   |
| Unknown        | 16        | 0.77%   |
| More than 3000 | 10        | 0.48%   |
| 2001-3000      | 6         | 0.29%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| SK hynix PC711 HFS001TDE9X073N 1TB                  | 3         | 3      | 6.52%   |
| Seagate ST1000LX015-1U7172 1TB                      | 2         | 2      | 4.35%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 2         | 2      | 4.35%   |
| HGST HTS725050A7E630 500GB                          | 2         | 3      | 4.35%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD                    | 1         | 1      | 2.17%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1         | 1      | 2.17%   |
| WDC WDS100T2B0B-00YS70 1TB SSD                      | 1         | 1      | 2.17%   |
| WDC WD5000LPVX-22V0TT0 500GB                        | 1         | 1      | 2.17%   |
| WDC WD3200BEKX-75B7WT0 320GB                        | 1         | 1      | 2.17%   |
| WDC WD3200BEKT-60PVMT0 320GB                        | 1         | 1      | 2.17%   |
| WDC WD10SPZX-22Z10T0 1TB                            | 1         | 1      | 2.17%   |
| WDC WD10JPVX-60JC3T1 1TB                            | 1         | 1      | 2.17%   |
| WDC WD10JPVX-60JC3T0 1TB                            | 1         | 1      | 2.17%   |
| WDC PC SN520 SDAPMUW-128G-1001 128GB                | 1         | 1      | 2.17%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD            | 1         | 1      | 2.17%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD            | 1         | 1      | 2.17%   |
| Toshiba MQ04ABF100 1TB                              | 1         | 1      | 2.17%   |
| Toshiba MQ01ACF050 500GB                            | 1         | 1      | 2.17%   |
| Toshiba MK7559GSXP 752GB                            | 1         | 1      | 2.17%   |
| Toshiba MK3252GSX 320GB                             | 1         | 1      | 2.17%   |
| Team TM8FP4004T 4TB                                 | 1         | 1      | 2.17%   |
| SK hynix PC711 HFS512GDE9X073N 512GB                | 1         | 1      | 2.17%   |
| SK hynix HFS512G39TND-N210A 512GB SSD               | 1         | 1      | 2.17%   |
| SK hynix HFS128G39TND-N210A 128GB SSD               | 1         | 1      | 2.17%   |
| SK hynix BC501 NVMe Solid State Drive 512GB         | 1         | 1      | 2.17%   |
| Seagate ST9320325AS 320GB                           | 1         | 1      | 2.17%   |
| Seagate ST500LT012-9WS142 500GB                     | 1         | 1      | 2.17%   |
| Seagate ST500LM030-2E717D 500GB                     | 1         | 1      | 2.17%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1      | 2.17%   |
| Samsung Electronics SSD 870 EVO 500GB               | 1         | 1      | 2.17%   |
| Samsung Electronics SSD 850 EVO 500GB               | 1         | 1      | 2.17%   |
| Micron Technology MTFDDAK256MAY-1AH1ZABHA 256GB SSD | 1         | 1      | 2.17%   |
| Lexar 1TB SSD                                       | 1         | 1      | 2.17%   |
| Leven JAJS600M256C 256GB                            | 1         | 1      | 2.17%   |
| Kingston SUV400S37240G 240GB SSD                    | 1         | 1      | 2.17%   |
| Intel SSDPEKKF512G7L 512GB                          | 1         | 1      | 2.17%   |
| Hitachi HTS545050A7E380 500GB                       | 1         | 3      | 2.17%   |
| HGST HTS721010A9E630 1TB                            | 1         | 1      | 2.17%   |
| HGST HTS545050A7E680 500GB                          | 1         | 1      | 2.17%   |
| HGST HTS541075A9E680 752GB                          | 1         | 1      | 2.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 10        | 10     | 21.74%  |
| Seagate             | 8         | 8      | 17.39%  |
| SK hynix            | 7         | 7      | 15.22%  |
| Toshiba             | 6         | 6      | 13.04%  |
| HGST                | 5         | 6      | 10.87%  |
| Samsung Electronics | 2         | 2      | 4.35%   |
| Team                | 1         | 1      | 2.17%   |
| Micron Technology   | 1         | 1      | 2.17%   |
| Lexar               | 1         | 1      | 2.17%   |
| Leven               | 1         | 1      | 2.17%   |
| Kingston            | 1         | 1      | 2.17%   |
| Intel               | 1         | 1      | 2.17%   |
| Hitachi             | 1         | 3      | 2.17%   |
| A-DATA Technology   | 1         | 1      | 2.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 8         | 8      | 33.33%  |
| WDC     | 6         | 6      | 25%     |
| HGST    | 5         | 6      | 20.83%  |
| Toshiba | 4         | 4      | 16.67%  |
| Hitachi | 1         | 3      | 4.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 24        | 27     | 52.17%  |
| SSD  | 12        | 12     | 26.09%  |
| NVMe | 10        | 10     | 21.74%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Samsung Electronics HM321HI 320GB | 1         | 1      | 50%     |
| Intenso JAJP600M1TB               | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 50%     |
| Intenso             | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1437      | 2138   | 69.96%  |
| Works    | 569       | 737    | 27.7%   |
| Malfunc  | 46        | 49     | 2.24%   |
| Failed   | 2         | 2      | 0.1%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 1153      | 45.63%  |
| Samsung Electronics            | 364       | 14.4%   |
| AMD                            | 234       | 9.26%   |
| SanDisk                        | 190       | 7.52%   |
| SK hynix                       | 131       | 5.18%   |
| Micron Technology              | 85        | 3.36%   |
| Kingston Technology Company    | 51        | 2.02%   |
| Phison Electronics             | 48        | 1.9%    |
| Toshiba America Info Systems   | 41        | 1.62%   |
| KIOXIA                         | 39        | 1.54%   |
| Micron/Crucial Technology      | 36        | 1.42%   |
| Nvidia                         | 32        | 1.27%   |
| ADATA Technology               | 24        | 0.95%   |
| Silicon Motion                 | 22        | 0.87%   |
| Solid State Storage Technology | 21        | 0.83%   |
| Apple                          | 12        | 0.47%   |
| Union Memory (Shenzhen)        | 11        | 0.44%   |
| Marvell Technology Group       | 9         | 0.36%   |
| Shenzhen Longsys Electronics   | 7         | 0.28%   |
| Realtek Semiconductor          | 4         | 0.16%   |
| MAXIO Technology (Hangzhou)    | 4         | 0.16%   |
| Seagate Technology             | 2         | 0.08%   |
| INNOGRIT                       | 2         | 0.08%   |
| Yangtze Memory Technologies    | 1         | 0.04%   |
| Transcend                      | 1         | 0.04%   |
| O2 Micro                       | 1         | 0.04%   |
| Netac Technology               | 1         | 0.04%   |
| Lite-On Technology             | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 225       | 8.52%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 141       | 5.34%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 129       | 4.88%   |
| Intel Volume Management Device NVMe RAID Controller                            | 110       | 4.16%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 99        | 3.75%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 94        | 3.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 93        | 3.52%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 75        | 2.84%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 69        | 2.61%   |
| Samsung NVMe SSD Controller 980                                                | 69        | 2.61%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 65        | 2.46%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 59        | 2.23%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 55        | 2.08%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 51        | 1.93%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 45        | 1.7%    |
| Intel SSD 660P Series                                                          | 36        | 1.36%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 35        | 1.32%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 34        | 1.29%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 32        | 1.21%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 32        | 1.21%   |
| Intel Comet Lake SATA AHCI Controller                                          | 31        | 1.17%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 29        | 1.1%    |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 28        | 1.06%   |
| Intel Tiger Lake-LP SATA Controller                                            | 28        | 1.06%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 28        | 1.06%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 27        | 1.02%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 27        | 1.02%   |
| Phison E12 NVMe Controller                                                     | 24        | 0.91%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 24        | 0.91%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 24        | 0.91%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 24        | 0.91%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 22        | 0.83%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 21        | 0.79%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 20        | 0.76%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 20        | 0.76%   |
| Nvidia MCP79 AHCI Controller                                                   | 18        | 0.68%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 18        | 0.68%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 17        | 0.64%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 17        | 0.64%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 16        | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1206      | 48.3%   |
| NVMe | 1028      | 41.17%  |
| RAID | 222       | 8.89%   |
| IDE  | 41        | 1.64%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 1504      | 77.09%  |
| AMD    | 447       | 22.91%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 42        | 2.15%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 39        | 2%      |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 38        | 1.95%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 35        | 1.79%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 33        | 1.69%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 31        | 1.59%   |
| Intel 12th Gen Core i7-12700H                 | 31        | 1.59%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 30        | 1.54%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 27        | 1.38%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 26        | 1.33%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 26        | 1.33%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 24        | 1.23%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 24        | 1.23%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 23        | 1.18%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 22        | 1.13%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 21        | 1.08%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 20        | 1.02%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 20        | 1.02%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 18        | 0.92%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 18        | 0.92%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 17        | 0.87%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 17        | 0.87%   |
| AMD Ryzen 7 PRO 5850U with Radeon Graphics    | 17        | 0.87%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 16        | 0.82%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 16        | 0.82%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 15        | 0.77%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 15        | 0.77%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 15        | 0.77%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 14        | 0.72%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 14        | 0.72%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 14        | 0.72%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 14        | 0.72%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 12        | 0.61%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 12        | 0.61%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 12        | 0.61%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 12        | 0.61%   |
| Intel 12th Gen Core i7-1260P                  | 12        | 0.61%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 12        | 0.61%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 11        | 0.56%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 11        | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 484       | 24.81%  |
| Intel Core i5           | 430       | 22.04%  |
| Other                   | 319       | 16.35%  |
| AMD Ryzen 7             | 152       | 7.79%   |
| AMD Ryzen 5             | 126       | 6.46%   |
| Intel Core i3           | 103       | 5.28%   |
| Intel Celeron           | 62        | 3.18%   |
| Intel Core 2 Duo        | 56        | 2.87%   |
| AMD Ryzen 9             | 35        | 1.79%   |
| AMD Ryzen 7 PRO         | 27        | 1.38%   |
| AMD Ryzen 3             | 19        | 0.97%   |
| Intel Pentium           | 18        | 0.92%   |
| AMD A8                  | 16        | 0.82%   |
| AMD A10                 | 13        | 0.67%   |
| Intel Core i9           | 12        | 0.62%   |
| AMD A6                  | 12        | 0.62%   |
| Intel Pentium Dual-Core | 7         | 0.36%   |
| AMD Ryzen 5 PRO         | 7         | 0.36%   |
| Intel Xeon              | 5         | 0.26%   |
| Intel Pentium Silver    | 5         | 0.26%   |
| AMD A4                  | 5         | 0.26%   |
| AMD E1                  | 4         | 0.21%   |
| AMD Athlon              | 4         | 0.21%   |
| AMD E                   | 3         | 0.15%   |
| AMD Athlon X2           | 3         | 0.15%   |
| Intel Genuine           | 2         | 0.1%    |
| Intel Core m5           | 2         | 0.1%    |
| Intel Core M            | 2         | 0.1%    |
| Intel Core 2            | 2         | 0.1%    |
| Intel Atom              | 2         | 0.1%    |
| AMD Ryzen 3 PRO         | 2         | 0.1%    |
| AMD Phenom II           | 2         | 0.1%    |
| AMD FX                  | 2         | 0.1%    |
| AMD E2                  | 2         | 0.1%    |
| Intel Pentium Gold      | 1         | 0.05%   |
| Intel Core m3           | 1         | 0.05%   |
| Intel Core 2 Quad       | 1         | 0.05%   |
| AMD Turion II           | 1         | 0.05%   |
| AMD Turion 64 X2 Mobile | 1         | 0.05%   |
| AMD A12                 | 1         | 0.05%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 682       | 34.96%  |
| 4      | 651       | 33.37%  |
| 8      | 268       | 13.74%  |
| 6      | 213       | 10.92%  |
| 14     | 60        | 3.08%   |
| 12     | 31        | 1.59%   |
| 10     | 25        | 1.28%   |
| 16     | 9         | 0.46%   |
| 1      | 6         | 0.31%   |
| 24     | 5         | 0.26%   |
| 3      | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1951      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1703      | 87.2%   |
| 1      | 250       | 12.8%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1951      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1526      | 77.11%  |
| 0x0a50000c | 38        | 1.92%   |
| 0x806c1    | 36        | 1.82%   |
| 0x906a3    | 23        | 1.16%   |
| 0x806d1    | 23        | 1.16%   |
| 0xa0652    | 20        | 1.01%   |
| 0x806ea    | 20        | 1.01%   |
| 0x806ec    | 19        | 0.96%   |
| 0x906ea    | 17        | 0.86%   |
| 0x08608103 | 17        | 0.86%   |
| 0x08600106 | 17        | 0.86%   |
| 0x306a9    | 16        | 0.81%   |
| 0x0a404102 | 14        | 0.71%   |
| 0x406e3    | 13        | 0.66%   |
| 0x0a404101 | 13        | 0.66%   |
| 0x806e9    | 11        | 0.56%   |
| 0x40651    | 11        | 0.56%   |
| 0x0a50000d | 10        | 0.51%   |
| 0x08600104 | 10        | 0.51%   |
| 0x08108109 | 10        | 0.51%   |
| 0x906a4    | 8         | 0.4%    |
| 0x306d4    | 8         | 0.4%    |
| 0x206a7    | 8         | 0.4%    |
| 0x1067a    | 8         | 0.4%    |
| 0x906e9    | 7         | 0.35%   |
| 0x706e5    | 7         | 0.35%   |
| 0x506e3    | 7         | 0.35%   |
| 0x306c3    | 7         | 0.35%   |
| 0x806eb    | 5         | 0.25%   |
| 0x08600103 | 5         | 0.25%   |
| 0x08108102 | 5         | 0.25%   |
| 0x706a8    | 4         | 0.2%    |
| 0x906c0    | 3         | 0.15%   |
| 0x806c2    | 3         | 0.15%   |
| 0x08608102 | 3         | 0.15%   |
| 0xa0660    | 2         | 0.1%    |
| 0x906ed    | 2         | 0.1%    |
| 0x0a601203 | 2         | 0.1%    |
| 0x0810100b | 2         | 0.1%    |
| 0x07030106 | 2         | 0.1%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 375       | 19.18%  |
| Unknown          | 215       | 11%     |
| Haswell          | 158       | 8.08%   |
| TigerLake        | 123       | 6.29%   |
| SandyBridge      | 116       | 5.93%   |
| Zen 3            | 114       | 5.83%   |
| IvyBridge        | 97        | 4.96%   |
| Skylake          | 91        | 4.65%   |
| Broadwell        | 83        | 4.25%   |
| CometLake        | 73        | 3.73%   |
| Zen+             | 68        | 3.48%   |
| Zen 2            | 66        | 3.38%   |
| Alderlake Hybrid | 62        | 3.17%   |
| Penryn           | 60        | 3.07%   |
| IceLake          | 52        | 2.66%   |
| Westmere         | 40        | 2.05%   |
| Goldmont plus    | 31        | 1.59%   |
| Silvermont       | 24        | 1.23%   |
| Excavator        | 19        | 0.97%   |
| Zen              | 16        | 0.82%   |
| Puma             | 16        | 0.82%   |
| Piledriver       | 13        | 0.66%   |
| Core             | 8         | 0.41%   |
| K10 Llano        | 6         | 0.31%   |
| Goldmont         | 5         | 0.26%   |
| Steamroller      | 4         | 0.2%    |
| Bobcat           | 4         | 0.2%    |
| Tremont          | 3         | 0.15%   |
| Nehalem          | 3         | 0.15%   |
| K8 Hammer        | 3         | 0.15%   |
| K10              | 3         | 0.15%   |
| Jaguar           | 3         | 0.15%   |
| K8 & K10 hybrid  | 1         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 1380      | 52.85%  |
| Nvidia | 704       | 26.96%  |
| AMD    | 527       | 20.18%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 115       | 4.31%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 104       | 3.9%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 94        | 3.53%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 91        | 3.41%   |
| Intel UHD Graphics 620                                                                | 86        | 3.23%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 83        | 3.11%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 82        | 3.08%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 74        | 2.78%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 67        | 2.51%   |
| AMD Renoir                                                                            | 65        | 2.44%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 59        | 2.21%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 59        | 2.21%   |
| Intel HD Graphics 620                                                                 | 56        | 2.1%    |
| Intel HD Graphics 5500                                                                | 56        | 2.1%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 56        | 2.1%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 52        | 1.95%   |
| AMD Lucienne                                                                          | 52        | 1.95%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 50        | 1.88%   |
| AMD Rembrandt [Radeon 680M]                                                           | 47        | 1.76%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 45        | 1.69%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                            | 43        | 1.61%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 43        | 1.61%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 36        | 1.35%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 35        | 1.31%   |
| Intel Core Processor Integrated Graphics Controller                                   | 33        | 1.24%   |
| Intel HD Graphics 630                                                                 | 30        | 1.13%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 28        | 1.05%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 24        | 0.9%    |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                       | 22        | 0.83%   |
| Intel HD Graphics 530                                                                 | 22        | 0.83%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                            | 21        | 0.79%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 21        | 0.79%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                               | 19        | 0.71%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                           | 19        | 0.71%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 19        | 0.71%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 18        | 0.68%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 18        | 0.68%   |
| Nvidia TU117M                                                                         | 17        | 0.64%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 16        | 0.6%    |
| Nvidia C79 [GeForce 9400M]                                                            | 15        | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 856       | 43.67%  |
| Intel + Nvidia     | 455       | 23.21%  |
| 1 x AMD            | 297       | 15.15%  |
| AMD + Nvidia       | 130       | 6.63%   |
| 1 x Nvidia         | 111       | 5.66%   |
| Intel + AMD        | 63        | 3.21%   |
| 2 x AMD            | 38        | 1.94%   |
| 2 x Nvidia         | 4         | 0.2%    |
| Other              | 3         | 0.15%   |
| Intel + 2 x Nvidia | 2         | 0.1%    |
| 2 x Intel          | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1388      | 70.67%  |
| Proprietary | 550       | 28%     |
| Unknown     | 26        | 1.32%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1707      | 86.69%  |
| 0.01-0.5   | 92        | 4.67%   |
| 1.01-2.0   | 50        | 2.54%   |
| 3.01-4.0   | 38        | 1.93%   |
| 5.01-6.0   | 29        | 1.47%   |
| 7.01-8.0   | 28        | 1.42%   |
| 0.51-1.0   | 16        | 0.81%   |
| 8.01-16.0  | 6         | 0.3%    |
| 2.01-3.0   | 3         | 0.15%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 418       | 18.13%  |
| BOE                     | 357       | 15.49%  |
| Chimei Innolux          | 336       | 14.58%  |
| LG Display              | 274       | 11.89%  |
| Samsung Electronics     | 174       | 7.55%   |
| Apple                   | 115       | 4.99%   |
| Dell                    | 79        | 3.43%   |
| Sharp                   | 76        | 3.3%    |
| Goldstar                | 67        | 2.91%   |
| PANDA                   | 57        | 2.47%   |
| Lenovo                  | 34        | 1.48%   |
| InfoVision              | 27        | 1.17%   |
| CSO                     | 25        | 1.08%   |
| Chi Mei Optoelectronics | 25        | 1.08%   |
| Acer                    | 25        | 1.08%   |
| Hewlett-Packard         | 22        | 0.95%   |
| AOC                     | 19        | 0.82%   |
| ASUSTek Computer        | 18        | 0.78%   |
| Philips                 | 17        | 0.74%   |
| BenQ                    | 13        | 0.56%   |
| Ancor Communications    | 13        | 0.56%   |
| TMX                     | 9         | 0.39%   |
| ViewSonic               | 7         | 0.3%    |
| Iiyama                  | 7         | 0.3%    |
| MSI                     | 6         | 0.26%   |
| Panasonic               | 5         | 0.22%   |
| NEC Computers           | 5         | 0.22%   |
| Vestel Elektronik       | 4         | 0.17%   |
| Sony                    | 4         | 0.17%   |
| HKC                     | 4         | 0.17%   |
| Vizio                   | 3         | 0.13%   |
| TCL                     | 3         | 0.13%   |
| RTK                     | 3         | 0.13%   |
| JDI                     | 3         | 0.13%   |
| HUAWEI                  | 3         | 0.13%   |
| Hitachi                 | 3         | 0.13%   |
| Unknown                 | 2         | 0.09%   |
| Toshiba                 | 2         | 0.09%   |
| Sceptre Tech            | 2         | 0.09%   |
| IBM                     | 2         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 23        | 0.99%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 21        | 0.9%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 20        | 0.86%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 20        | 0.86%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 19        | 0.82%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 16        | 0.69%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 13        | 0.56%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 12        | 0.52%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                  | 12        | 0.52%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 11        | 0.47%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 10        | 0.43%   |
| InfoVision LCD Monitor IVO8C78 1920x1080 309x174mm 14.0-inch          | 10        | 0.43%   |
| Chimei Innolux LCD Monitor CMN1408 1920x1080 309x173mm 13.9-inch      | 10        | 0.43%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 10        | 0.43%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 9         | 0.39%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 9         | 0.39%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 8         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 8         | 0.34%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch         | 8         | 0.34%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                  | 8         | 0.34%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 7         | 0.3%    |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 7         | 0.3%    |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                 | 7         | 0.3%    |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 7         | 0.3%    |
| BOE LCD Monitor BOE08DF 1920x1080 344x194mm 15.5-inch                 | 7         | 0.3%    |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch        | 7         | 0.3%    |
| AU Optronics LCD Monitor AUO80ED 1920x1080 344x193mm 15.5-inch        | 7         | 0.3%    |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 7         | 0.3%    |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch        | 7         | 0.3%    |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch        | 7         | 0.3%    |
| Apple Color LCD APPA01B 1440x900 286x179mm 13.3-inch                  | 7         | 0.3%    |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                  | 7         | 0.3%    |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 6         | 0.26%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 6         | 0.26%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch          | 6         | 0.26%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                 | 6         | 0.26%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 340x190mm 15.3-inch         | 6         | 0.26%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch        | 6         | 0.26%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 6         | 0.26%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 6         | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1050      | 48.61%  |
| 1366x768 (WXGA)    | 446       | 20.65%  |
| 3840x2160 (4K)     | 103       | 4.77%   |
| 2560x1440 (QHD)    | 94        | 4.35%   |
| 1600x900 (HD+)     | 68        | 3.15%   |
| 1920x1200 (WUXGA)  | 64        | 2.96%   |
| 2560x1600          | 58        | 2.69%   |
| 2880x1800          | 42        | 1.94%   |
| 1280x800 (WXGA)    | 42        | 1.94%   |
| 1440x900 (WXGA+)   | 41        | 1.9%    |
| 3440x1440          | 18        | 0.83%   |
| 2560x1080          | 18        | 0.83%   |
| 3840x2400          | 16        | 0.74%   |
| 3072x1920          | 10        | 0.46%   |
| 1680x1050 (WSXGA+) | 10        | 0.46%   |
| 1280x1024 (SXGA)   | 9         | 0.42%   |
| 2160x1440          | 8         | 0.37%   |
| 3200x1800 (QHD+)   | 7         | 0.32%   |
| 2256x1504          | 7         | 0.32%   |
| 1360x768           | 6         | 0.28%   |
| 3200x2000          | 5         | 0.23%   |
| 3456x2160          | 4         | 0.19%   |
| 3840x1100          | 3         | 0.14%   |
| 3840x1080          | 3         | 0.14%   |
| 2240x1400          | 3         | 0.14%   |
| 1920x540           | 3         | 0.14%   |
| 1920x1280          | 3         | 0.14%   |
| 800x1280           | 2         | 0.09%   |
| 3000x2000          | 2         | 0.09%   |
| 2304x1440          | 2         | 0.09%   |
| 1280x720 (HD)      | 2         | 0.09%   |
| 3840x1200          | 1         | 0.05%   |
| 3120x2080          | 1         | 0.05%   |
| 2880x1620          | 1         | 0.05%   |
| 2560x1700          | 1         | 0.05%   |
| 2520x1680          | 1         | 0.05%   |
| 1920x515           | 1         | 0.05%   |
| 1600x2560          | 1         | 0.05%   |
| 1600x1200          | 1         | 0.05%   |
| 1400x1050          | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 923       | 40.1%   |
| 13      | 379       | 16.46%  |
| 14      | 267       | 11.6%   |
| 17      | 150       | 6.52%   |
| 27      | 88        | 3.82%   |
| 24      | 76        | 3.3%    |
| 16      | 66        | 2.87%   |
| 23      | 54        | 2.35%   |
| 12      | 44        | 1.91%   |
| 21      | 39        | 1.69%   |
| 34      | 32        | 1.39%   |
| 31      | 32        | 1.39%   |
| 11      | 28        | 1.22%   |
| 19      | 15        | 0.65%   |
| 32      | 12        | 0.52%   |
| 18      | 12        | 0.52%   |
| Unknown | 11        | 0.48%   |
| 84      | 10        | 0.43%   |
| 40      | 10        | 0.43%   |
| 22      | 8         | 0.35%   |
| 72      | 5         | 0.22%   |
| 35      | 5         | 0.22%   |
| 20      | 5         | 0.22%   |
| 48      | 4         | 0.17%   |
| 54      | 3         | 0.13%   |
| 29      | 3         | 0.13%   |
| 28      | 3         | 0.13%   |
| 49      | 2         | 0.09%   |
| 33      | 2         | 0.09%   |
| 26      | 2         | 0.09%   |
| 25      | 2         | 0.09%   |
| 74      | 1         | 0.04%   |
| 60      | 1         | 0.04%   |
| 57      | 1         | 0.04%   |
| 47      | 1         | 0.04%   |
| 46      | 1         | 0.04%   |
| 43      | 1         | 0.04%   |
| 37      | 1         | 0.04%   |
| 8       | 1         | 0.04%   |
| 7       | 1         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 1419      | 62.26%  |
| 201-300     | 266       | 11.67%  |
| 501-600     | 196       | 8.6%    |
| 351-400     | 174       | 7.63%   |
| 401-500     | 70        | 3.07%   |
| 601-700     | 49        | 2.15%   |
| 701-800     | 46        | 2.02%   |
| 801-900     | 16        | 0.7%    |
| 1501-2000   | 16        | 0.7%    |
| 1001-1500   | 13        | 0.57%   |
| Unknown     | 11        | 0.48%   |
| 1-100       | 2         | 0.09%   |
| 101-200     | 1         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1630      | 80.53%  |
| 16/10   | 301       | 14.87%  |
| 21/9    | 39        | 1.93%   |
| 3/2     | 26        | 1.28%   |
| 5/4     | 10        | 0.49%   |
| 32/9    | 4         | 0.2%    |
| 3.40    | 3         | 0.15%   |
| Unknown | 3         | 0.15%   |
| 4/3     | 2         | 0.1%    |
| 6/5     | 1         | 0.05%   |
| 3.73    | 1         | 0.05%   |
| 3.20    | 1         | 0.05%   |
| 0.67    | 1         | 0.05%   |
| 0.63    | 1         | 0.05%   |
| 0.56    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 923       | 40.15%  |
| 81-90          | 507       | 22.05%  |
| 201-250        | 147       | 6.39%   |
| 121-130        | 135       | 5.87%   |
| 71-80          | 128       | 5.57%   |
| 301-350        | 90        | 3.91%   |
| 351-500        | 85        | 3.7%    |
| 111-120        | 64        | 2.78%   |
| 61-70          | 42        | 1.83%   |
| 51-60          | 31        | 1.35%   |
| 151-200        | 31        | 1.35%   |
| More than 1000 | 24        | 1.04%   |
| 251-300        | 22        | 0.96%   |
| 501-1000       | 17        | 0.74%   |
| 141-150        | 15        | 0.65%   |
| 131-140        | 13        | 0.57%   |
| 91-100         | 11        | 0.48%   |
| Unknown        | 11        | 0.48%   |
| 1-40           | 3         | 0.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1041      | 46.16%  |
| 101-120       | 542       | 24.04%  |
| 51-100        | 294       | 13.04%  |
| 161-240       | 240       | 10.64%  |
| More than 240 | 105       | 4.66%   |
| 1-50          | 22        | 0.98%   |
| Unknown       | 11        | 0.49%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1539      | 77.69%  |
| 2     | 340       | 17.16%  |
| 3     | 55        | 2.78%   |
| 0     | 44        | 2.22%   |
| 4     | 3         | 0.15%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1064      | 34.62%  |
| Intel                             | 1031      | 33.55%  |
| Qualcomm Atheros                  | 341       | 11.1%   |
| Broadcom                          | 185       | 6.02%   |
| MediaTek                          | 108       | 3.51%   |
| Broadcom Limited                  | 68        | 2.21%   |
| ASIX Electronics                  | 33        | 1.07%   |
| Samsung Electronics               | 19        | 0.62%   |
| Nvidia                            | 19        | 0.62%   |
| TP-Link                           | 17        | 0.55%   |
| Ralink                            | 17        | 0.55%   |
| Marvell Technology Group          | 17        | 0.55%   |
| DisplayLink                       | 15        | 0.49%   |
| Dell                              | 15        | 0.49%   |
| Xiaomi                            | 13        | 0.42%   |
| Qualcomm                          | 12        | 0.39%   |
| Ralink Technology                 | 10        | 0.33%   |
| Lenovo                            | 9         | 0.29%   |
| Sierra Wireless                   | 8         | 0.26%   |
| JMicron Technology                | 8         | 0.26%   |
| Hewlett-Packard                   | 7         | 0.23%   |
| OPPO Electronics                  | 6         | 0.2%    |
| OnePlus Technology (Shenzhen)     | 5         | 0.16%   |
| NetGear                           | 4         | 0.13%   |
| Motorola PCS                      | 4         | 0.13%   |
| Ericsson Business Mobile Networks | 4         | 0.13%   |
| ASUSTek Computer                  | 4         | 0.13%   |
| Huawei Technologies               | 3         | 0.1%    |
| Google                            | 3         | 0.1%    |
| Fibocom                           | 3         | 0.1%    |
| Edimax Technology                 | 3         | 0.1%    |
| Qualcomm Atheros Communications   | 2         | 0.07%   |
| Linksys                           | 2         | 0.07%   |
| D-Link                            | 2         | 0.07%   |
| Arduino SA                        | 2         | 0.07%   |
| Apple                             | 2         | 0.07%   |
| ZyDAS                             | 1         | 0.03%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.03%   |
| U-Blox                            | 1         | 0.03%   |
| Shenzhen Goodix Technology        | 1         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 659       | 18.11%  |
| Intel Wi-Fi 6 AX200                                               | 122       | 3.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 111       | 3.05%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 104       | 2.86%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 95        | 2.61%   |
| Intel Wireless 8265 / 8275                                        | 93        | 2.56%   |
| Intel Wi-Fi 6 AX201                                               | 93        | 2.56%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 65        | 1.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 64        | 1.76%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 63        | 1.73%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 62        | 1.7%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 59        | 1.62%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 57        | 1.57%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 56        | 1.54%   |
| Intel Wireless 7265                                               | 49        | 1.35%   |
| Intel Wireless 8260                                               | 48        | 1.32%   |
| Intel Wireless 7260                                               | 48        | 1.32%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 46        | 1.26%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 44        | 1.21%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 41        | 1.13%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 39        | 1.07%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 36        | 0.99%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 33        | 0.91%   |
| Intel Ethernet Connection (4) I219-LM                             | 33        | 0.91%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 32        | 0.88%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 31        | 0.85%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 31        | 0.85%   |
| Realtek RTL8125 2.5GbE Controller                                 | 30        | 0.82%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 30        | 0.82%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 28        | 0.77%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 28        | 0.77%   |
| ASIX AX88179 Gigabit Ethernet                                     | 28        | 0.77%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 26        | 0.71%   |
| Intel Ethernet Connection I217-LM                                 | 25        | 0.69%   |
| Broadcom BCM43142 802.11b/g/n                                     | 24        | 0.66%   |
| Intel Ethernet Connection I219-LM                                 | 23        | 0.63%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 23        | 0.63%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 23        | 0.63%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 22        | 0.6%    |
| Intel Wireless-AC 9260                                            | 20        | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1000      | 49.12%  |
| Realtek Semiconductor                 | 318       | 15.62%  |
| Qualcomm Atheros                      | 293       | 14.39%  |
| Broadcom                              | 159       | 7.81%   |
| MediaTek                              | 107       | 5.26%   |
| Broadcom Limited                      | 59        | 2.9%    |
| Ralink                                | 17        | 0.83%   |
| TP-Link                               | 14        | 0.69%   |
| Dell                                  | 13        | 0.64%   |
| Qualcomm                              | 11        | 0.54%   |
| Ralink Technology                     | 10        | 0.49%   |
| Sierra Wireless                       | 8         | 0.39%   |
| NetGear                               | 4         | 0.2%    |
| Hewlett-Packard                       | 4         | 0.2%    |
| Fibocom                               | 3         | 0.15%   |
| Edimax Technology                     | 3         | 0.15%   |
| ASUSTek Computer                      | 3         | 0.15%   |
| Qualcomm Atheros Communications       | 2         | 0.1%    |
| Linksys                               | 2         | 0.1%    |
| D-Link                                | 2         | 0.1%    |
| ZyDAS                                 | 1         | 0.05%   |
| Arduino SA                            | 1         | 0.05%   |
| Accton Technology                     | 1         | 0.05%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 122       | 5.96%   |
| Intel Wireless 8265 / 8275                                     | 93        | 4.54%   |
| Intel Wi-Fi 6 AX201                                            | 93        | 4.54%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 93        | 4.54%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 65        | 3.18%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 64        | 3.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 63        | 3.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 62        | 3.03%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 59        | 2.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 57        | 2.78%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 56        | 2.74%   |
| Intel Wireless 7265                                            | 49        | 2.39%   |
| Intel Wireless 8260                                            | 48        | 2.34%   |
| Intel Wireless 7260                                            | 48        | 2.34%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 44        | 2.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 41        | 2%      |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 39        | 1.91%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 36        | 1.76%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 33        | 1.61%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 32        | 1.56%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 31        | 1.51%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 31        | 1.51%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 30        | 1.47%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 28        | 1.37%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 28        | 1.37%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 26        | 1.27%   |
| Broadcom BCM43142 802.11b/g/n                                  | 24        | 1.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 23        | 1.12%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 23        | 1.12%   |
| Intel Wireless-AC 9260                                         | 20        | 0.98%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 16        | 0.78%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 16        | 0.78%   |
| Intel Centrino Ultimate-N 6300                                 | 16        | 0.78%   |
| Intel Centrino Advanced-N 6235                                 | 16        | 0.78%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 15        | 0.73%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 14        | 0.68%   |
| Realtek 802.11ac NIC                                           | 14        | 0.68%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 14        | 0.68%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 14        | 0.68%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 13        | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 923       | 59.51%  |
| Intel                         | 308       | 19.86%  |
| Qualcomm Atheros              | 83        | 5.35%   |
| Broadcom                      | 65        | 4.19%   |
| ASIX Electronics              | 33        | 2.13%   |
| Samsung Electronics           | 19        | 1.23%   |
| Nvidia                        | 19        | 1.23%   |
| Marvell Technology Group      | 17        | 1.1%    |
| DisplayLink                   | 15        | 0.97%   |
| Xiaomi                        | 13        | 0.84%   |
| Lenovo                        | 9         | 0.58%   |
| Broadcom Limited              | 9         | 0.58%   |
| JMicron Technology            | 8         | 0.52%   |
| OPPO Electronics              | 6         | 0.39%   |
| OnePlus Technology (Shenzhen) | 5         | 0.32%   |
| TP-Link                       | 3         | 0.19%   |
| Motorola PCS                  | 3         | 0.19%   |
| Google                        | 3         | 0.19%   |
| Huawei Technologies           | 2         | 0.13%   |
| Hewlett-Packard               | 2         | 0.13%   |
| Apple                         | 2         | 0.13%   |
| ZTE WCDMA Technologies MSM    | 1         | 0.06%   |
| Qualcomm                      | 1         | 0.06%   |
| ICS Advent                    | 1         | 0.06%   |
| ASUSTek Computer              | 1         | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 659       | 41.84%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 111       | 7.05%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 104       | 6.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 46        | 2.92%   |
| Intel Ethernet Connection (4) I219-LM                             | 33        | 2.1%    |
| Realtek RTL8125 2.5GbE Controller                                 | 30        | 1.9%    |
| ASIX AX88179 Gigabit Ethernet                                     | 28        | 1.78%   |
| Intel Ethernet Connection I217-LM                                 | 25        | 1.59%   |
| Intel Ethernet Connection I219-LM                                 | 23        | 1.46%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 22        | 1.4%    |
| Intel Ethernet Connection (3) I218-LM                             | 18        | 1.14%   |
| Nvidia MCP79 Ethernet                                             | 17        | 1.08%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 16        | 1.02%   |
| Intel Ethernet Connection I218-LM                                 | 15        | 0.95%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 14        | 0.89%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 14        | 0.89%   |
| Intel Ethernet Connection (4) I219-V                              | 14        | 0.89%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 13        | 0.83%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 12        | 0.76%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 11        | 0.7%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 10        | 0.63%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 10        | 0.63%   |
| Intel Ethernet Connection (13) I219-V                             | 10        | 0.63%   |
| Intel Ethernet Connection (2) I219-LM                             | 9         | 0.57%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 8         | 0.51%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 8         | 0.51%   |
| Intel Ethernet Connection (7) I219-LM                             | 8         | 0.51%   |
| Intel Ethernet Connection (16) I219-V                             | 8         | 0.51%   |
| Intel 82567LM Gigabit Network Connection                          | 8         | 0.51%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 8         | 0.51%   |
| Realtek Killer E3000 2.5GbE Controller                            | 7         | 0.44%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 7         | 0.44%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 7         | 0.44%   |
| Intel Ethernet Connection (6) I219-V                              | 7         | 0.44%   |
| Intel Ethernet Connection (6) I219-LM                             | 7         | 0.44%   |
| Intel Ethernet Connection (16) I219-LM                            | 7         | 0.44%   |
| Intel 82577LM Gigabit Network Connection                          | 7         | 0.44%   |
| DisplayLink Dell Universal Dock D6000                             | 7         | 0.44%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 7         | 0.44%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 6         | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1929      | 56.59%  |
| Ethernet | 1464      | 42.95%  |
| Modem    | 12        | 0.35%   |
| Unknown  | 4         | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1645      | 79.78%  |
| Ethernet | 417       | 20.22%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1310      | 67.15%  |
| 1     | 612       | 31.37%  |
| 0     | 19        | 0.97%   |
| 3     | 10        | 0.51%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1386      | 70.32%  |
| Yes  | 585       | 29.68%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 886       | 52.58%  |
| Realtek Semiconductor           | 172       | 10.21%  |
| Qualcomm Atheros Communications | 141       | 8.37%   |
| Apple                           | 119       | 7.06%   |
| IMC Networks                    | 98        | 5.82%   |
| Foxconn / Hon Hai               | 75        | 4.45%   |
| Lite-On Technology              | 61        | 3.62%   |
| Broadcom                        | 42        | 2.49%   |
| Dell                            | 15        | 0.89%   |
| Realtek                         | 13        | 0.77%   |
| Toshiba                         | 11        | 0.65%   |
| Cambridge Silicon Radio         | 10        | 0.59%   |
| Hewlett-Packard                 | 8         | 0.47%   |
| Ralink                          | 6         | 0.36%   |
| MediaTek                        | 6         | 0.36%   |
| Opticis                         | 3         | 0.18%   |
| Foxconn International           | 3         | 0.18%   |
| TP-Link                         | 2         | 0.12%   |
| Taiyo Yuden                     | 2         | 0.12%   |
| Smart Modular Technologies      | 2         | 0.12%   |
| Ralink Technology               | 2         | 0.12%   |
| Fujitsu                         | 2         | 0.12%   |
| ASUSTek Computer                | 2         | 0.12%   |
| USI                             | 1         | 0.06%   |
| Micro Star International        | 1         | 0.06%   |
| Integrated System Solution      | 1         | 0.06%   |
| Actions                         | 1         | 0.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 257       | 15.24%  |
| Intel AX201 Bluetooth                               | 221       | 13.11%  |
| Realtek Bluetooth Radio                             | 121       | 7.18%   |
| Intel AX200 Bluetooth                               | 119       | 7.06%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 113       | 6.7%    |
| Intel Bluetooth Device                              | 81        | 4.8%    |
| Qualcomm Atheros  Bluetooth Device                  | 78        | 4.63%   |
| Apple Bluetooth Host Controller                     | 67        | 3.97%   |
| IMC Networks Wireless_Device                        | 41        | 2.43%   |
| Apple Bluetooth USB Host Controller                 | 41        | 2.43%   |
| Realtek  Bluetooth 4.2 Adapter                      | 37        | 2.19%   |
| Intel AX210 Bluetooth                               | 30        | 1.78%   |
| IMC Networks Bluetooth Radio                        | 23        | 1.36%   |
| Foxconn / Hon Hai Bluetooth Device                  | 22        | 1.3%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 21        | 1.25%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 20        | 1.19%   |
| Foxconn / Hon Hai Wireless_Device                   | 20        | 1.19%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 17        | 1.01%   |
| IMC Networks Bluetooth Device                       | 17        | 1.01%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 16        | 0.95%   |
| Lite-On Wireless_Device                             | 15        | 0.89%   |
| Intel Wireless-AC 3168 Bluetooth                    | 14        | 0.83%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 14        | 0.83%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 14        | 0.83%   |
| Realtek Bluetooth Radio                             | 13        | 0.77%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 13        | 0.77%   |
| Lite-On Bluetooth Device                            | 11        | 0.65%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 10        | 0.59%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 10        | 0.59%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 9         | 0.53%   |
| Lite-On Atheros AR3012 Bluetooth                    | 9         | 0.53%   |
| Broadcom BCM2045B (BDC-2.1)                         | 8         | 0.47%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 7         | 0.42%   |
| Lite-On Bluetooth Radio                             | 7         | 0.42%   |
| Ralink RT3290 Bluetooth                             | 6         | 0.36%   |
| MediaTek Wireless_Device                            | 6         | 0.36%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 6         | 0.36%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 6         | 0.36%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 5         | 0.3%    |
| IMC Networks Bluetooth USB Host Controller          | 5         | 0.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 1467      | 56.42%  |
| AMD                                             | 478       | 18.38%  |
| Nvidia                                          | 457       | 17.58%  |
| C-Media Electronics                             | 20        | 0.77%   |
| Logitech                                        | 19        | 0.73%   |
| Lenovo                                          | 13        | 0.5%    |
| GN Netcom                                       | 13        | 0.5%    |
| Kingston Technology                             | 12        | 0.46%   |
| Generalplus Technology                          | 12        | 0.46%   |
| Realtek Semiconductor                           | 10        | 0.38%   |
| JMTek                                           | 9         | 0.35%   |
| Apple                                           | 9         | 0.35%   |
| Sony                                            | 8         | 0.31%   |
| Hewlett-Packard                                 | 8         | 0.31%   |
| Texas Instruments                               | 7         | 0.27%   |
| SteelSeries ApS                                 | 5         | 0.19%   |
| Plantronics                                     | 5         | 0.19%   |
| Focusrite-Novation                              | 5         | 0.19%   |
| Razer USA                                       | 4         | 0.15%   |
| Corsair                                         | 4         | 0.15%   |
| ASUSTek Computer                                | 4         | 0.15%   |
| Turtle Beach                                    | 2         | 0.08%   |
| Sennheiser Communications                       | 2         | 0.08%   |
| FiiO Electronics Technology                     | 2         | 0.08%   |
| DSEA A/S                                        | 2         | 0.08%   |
| Yamaha                                          | 1         | 0.04%   |
| Thesycon Systemsoftware & Consulting            | 1         | 0.04%   |
| TerraTec Electronic                             | 1         | 0.04%   |
| Samsung Electronics                             | 1         | 0.04%   |
| Samson Technologies                             | 1         | 0.04%   |
| Reloop                                          | 1         | 0.04%   |
| Pioneer DJ                                      | 1         | 0.04%   |
| Nordic Semiconductor ASA                        | 1         | 0.04%   |
| No brand                                        | 1         | 0.04%   |
| Midiplus                                        | 1         | 0.04%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.04%   |
| iConnectivity                                   | 1         | 0.04%   |
| GYROCOM C&C                                     | 1         | 0.04%   |
| Goldvish                                        | 1         | 0.04%   |
| Evolution Electronics                           | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 360       | 11.23%  |
| Intel Sunrise Point-LP HD Audio                                            | 211       | 6.58%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 188       | 5.86%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 123       | 3.84%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 112       | 3.49%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 111       | 3.46%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 102       | 3.18%   |
| Intel Cannon Lake PCH cAVS                                                 | 93        | 2.9%    |
| Intel Broadwell-U Audio Controller                                         | 83        | 2.59%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 83        | 2.59%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 82        | 2.56%   |
| Intel Haswell-ULT HD Audio Controller                                      | 75        | 2.34%   |
| Intel 8 Series HD Audio Controller                                         | 74        | 2.31%   |
| Nvidia Audio device                                                        | 71        | 2.21%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 71        | 2.21%   |
| Intel Comet Lake PCH cAVS                                                  | 66        | 2.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 57        | 1.78%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 56        | 1.75%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 56        | 1.75%   |
| Nvidia GA106 High Definition Audio Controller                              | 53        | 1.65%   |
| Intel Comet Lake PCH-LP cAVS                                               | 50        | 1.56%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 48        | 1.5%    |
| Nvidia GA104 High Definition Audio Controller                              | 47        | 1.47%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 47        | 1.47%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 43        | 1.34%   |
| AMD FCH Azalia Controller                                                  | 43        | 1.34%   |
| Nvidia TU106 High Definition Audio Controller                              | 38        | 1.19%   |
| Intel CM238 HD Audio Controller                                            | 37        | 1.15%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 31        | 0.97%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 28        | 0.87%   |
| AMD Kabini HDMI/DP Audio                                                   | 27        | 0.84%   |
| Nvidia TU116 High Definition Audio Controller                              | 25        | 0.78%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 25        | 0.78%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 22        | 0.69%   |
| Nvidia GP107GL High Definition Audio Controller                            | 21        | 0.66%   |
| Nvidia GP106 High Definition Audio Controller                              | 21        | 0.66%   |
| Nvidia GK107 HDMI Audio Controller                                         | 20        | 0.62%   |
| Nvidia MCP79 High Definition Audio                                         | 19        | 0.59%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 18        | 0.56%   |
| Nvidia GP104 High Definition Audio Controller                              | 14        | 0.44%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 225       | 30%     |
| SK hynix                                | 176       | 23.47%  |
| Micron Technology                       | 119       | 15.87%  |
| Kingston                                | 47        | 6.27%   |
| Crucial                                 | 40        | 5.33%   |
| Unknown                                 | 16        | 2.13%   |
| A-DATA Technology                       | 13        | 1.73%   |
| Smart                                   | 12        | 1.6%    |
| Unknown                                 | 11        | 1.47%   |
| Ramaxel Technology                      | 9         | 1.2%    |
| Neo Forza                               | 9         | 1.2%    |
| Goldkey                                 | 9         | 1.2%    |
| Corsair                                 | 9         | 1.2%    |
| G.Skill                                 | 7         | 0.93%   |
| Elpida                                  | 7         | 0.93%   |
| Team                                    | 6         | 0.8%    |
| Unknown (ABCD)                          | 5         | 0.67%   |
| PNY                                     | 4         | 0.53%   |
| Nanya Technology                        | 3         | 0.4%    |
| GSkill                                  | 3         | 0.4%    |
| Transcend                               | 2         | 0.27%   |
| Teikon                                  | 2         | 0.27%   |
| Smart Brazil                            | 2         | 0.27%   |
| Gold Key                                | 2         | 0.27%   |
| ChangXin Memory                         | 2         | 0.27%   |
| Avant                                   | 2         | 0.27%   |
| Unknown (8A02)                          | 1         | 0.13%   |
| Unknown (09B6)                          | 1         | 0.13%   |
| Unknown (09A4)                          | 1         | 0.13%   |
| Timetec                                 | 1         | 0.13%   |
| Silicon Power Computer & Communications | 1         | 0.13%   |
| Kllisre                                 | 1         | 0.13%   |
| CSX                                     | 1         | 0.13%   |
| Apacer                                  | 1         | 0.13%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 21        | 2.69%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 16        | 2.05%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 14        | 1.79%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 13        | 1.66%   |
| Unknown                                                          | 11        | 1.41%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 10        | 1.28%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 9         | 1.15%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 8         | 1.02%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 8         | 1.02%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 7         | 0.9%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 7         | 0.9%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 7         | 0.9%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 7         | 0.9%    |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 7         | 0.9%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 7         | 0.9%    |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 7         | 0.9%    |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s           | 6         | 0.77%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 6         | 0.77%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.77%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.77%   |
| Micron RAM MT62F1G32D4DR-031 WT 4GB Row Of Chips LPDDR5 6400MT/s | 6         | 0.77%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 6         | 0.77%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 6         | 0.77%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 5         | 0.64%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 5         | 0.64%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.64%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.64%   |
| SK hynix RAM HMA851S6CJR6N-VK 4096MB SODIMM DDR4 2667MT/s        | 5         | 0.64%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 5         | 0.64%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 5         | 0.64%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 5         | 0.64%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 5         | 0.64%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 5         | 0.64%   |
| Goldkey RAM GKE800SO102408-2666A 8GB SODIMM DDR4 2667MT/s        | 5         | 0.64%   |
| SK hynix RAM HMCG78MEBSA095N 16GB SODIMM DDR5 4800MT/s           | 4         | 0.51%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 0.51%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 4         | 0.51%   |
| Samsung RAM Module 4GB SODIMM DDR3 1867MT/s                      | 4         | 0.51%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                     | 4         | 0.51%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.51%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 394       | 61.76%  |
| DDR3   | 103       | 16.14%  |
| DDR5   | 44        | 6.9%    |
| LPDDR4 | 39        | 6.11%   |
| LPDDR5 | 30        | 4.7%    |
| LPDDR3 | 21        | 3.29%   |
| SDRAM  | 4         | 0.63%   |
| DDR2   | 3         | 0.47%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 545       | 83.59%  |
| Row Of Chips | 100       | 15.34%  |
| Chip         | 4         | 0.61%   |
| Unknown      | 2         | 0.31%   |
| DIMM         | 1         | 0.15%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 320       | 46.51%  |
| 4096  | 148       | 21.51%  |
| 16384 | 144       | 20.93%  |
| 32768 | 40        | 5.81%   |
| 2048  | 32        | 4.65%   |
| 1024  | 4         | 0.58%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 223       | 32.6%   |
| 2667  | 144       | 21.05%  |
| 1600  | 76        | 11.11%  |
| 4800  | 41        | 5.99%   |
| 2400  | 41        | 5.99%   |
| 2133  | 32        | 4.68%   |
| 6400  | 30        | 4.39%   |
| 4267  | 21        | 3.07%   |
| 1867  | 12        | 1.75%   |
| 1334  | 10        | 1.46%   |
| 8400  | 8         | 1.17%   |
| 3266  | 7         | 1.02%   |
| 1333  | 7         | 1.02%   |
| 4266  | 6         | 0.88%   |
| 1067  | 6         | 0.88%   |
| 3733  | 4         | 0.58%   |
| 800   | 3         | 0.44%   |
| 5600  | 2         | 0.29%   |
| 4199  | 2         | 0.29%   |
| 2933  | 2         | 0.29%   |
| 2048  | 2         | 0.29%   |
| 5200  | 1         | 0.15%   |
| 3000  | 1         | 0.15%   |
| 1200  | 1         | 0.15%   |
| 1066  | 1         | 0.15%   |
| 666   | 1         | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 3         | 30%     |
| Canon               | 3         | 30%     |
| Xerox               | 1         | 10%     |
| Samsung Electronics | 1         | 10%     |
| ICS Advent          | 1         | 10%     |
| Brother Industries  | 1         | 10%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Canon PIXMA MX920 Series        | 2         | 20%     |
| Xerox B215                      | 1         | 10%     |
| Samsung M2020 Series            | 1         | 10%     |
| ICS Advent Parallel Adapter     | 1         | 10%     |
| HP OfficeJet 3830 series        | 1         | 10%     |
| HP Ink Tank Wireless 410 series | 1         | 10%     |
| HP Color LaserJet CP2025dn      | 1         | 10%     |
| Canon E400 series               | 1         | 10%     |
| Brother HL-L2370DW series       | 1         | 10%     |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 386       | 21.69%  |
| IMC Networks                           | 194       | 10.9%   |
| Microdia                               | 174       | 9.78%   |
| Realtek Semiconductor                  | 139       | 7.81%   |
| Bison Electronics                      | 118       | 6.63%   |
| Quanta                                 | 113       | 6.35%   |
| Sunplus Innovation Technology          | 87        | 4.89%   |
| Acer                                   | 87        | 4.89%   |
| Apple                                  | 86        | 4.83%   |
| Luxvisions Innotech Limited            | 53        | 2.98%   |
| Cheng Uei Precision Industry (Foxlink) | 53        | 2.98%   |
| Syntek                                 | 40        | 2.25%   |
| Lite-On Technology                     | 37        | 2.08%   |
| Suyin                                  | 28        | 1.57%   |
| Sonix Technology                       | 24        | 1.35%   |
| Logitech                               | 24        | 1.35%   |
| Silicon Motion                         | 20        | 1.12%   |
| SunplusIT                              | 14        | 0.79%   |
| Samsung Electronics                    | 11        | 0.62%   |
| Alcor Micro                            | 11        | 0.62%   |
| Z-Star Microelectronics                | 7         | 0.39%   |
| Ricoh                                  | 6         | 0.34%   |
| Microsoft                              | 6         | 0.34%   |
| Razer USA                              | 5         | 0.28%   |
| Lenovo                                 | 4         | 0.22%   |
| Generalplus Technology                 | 4         | 0.22%   |
| Tobii Technology AB                    | 3         | 0.17%   |
| Primax Electronics                     | 3         | 0.17%   |
| Importek                               | 3         | 0.17%   |
| icSpring                               | 3         | 0.17%   |
| HRY                                    | 3         | 0.17%   |
| Colorado                               | 3         | 0.17%   |
| ALi                                    | 3         | 0.17%   |
| Intel                                  | 2         | 0.11%   |
| AVerMedia Technologies                 | 2         | 0.11%   |
| Y Media                                | 1         | 0.06%   |
| Trust                                  | 1         | 0.06%   |
| Tripath Technology                     | 1         | 0.06%   |
| ShineTech                              | 1         | 0.06%   |
| ShineOptics                            | 1         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                       | 93        | 5.2%    |
| Chicony Integrated Camera                           | 87        | 4.87%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 73        | 4.08%   |
| Realtek Integrated_Webcam_HD                        | 59        | 3.3%    |
| IMC Networks Integrated Camera                      | 46        | 2.57%   |
| Acer BisonCam,NB Pro                                | 41        | 2.29%   |
| Chicony HD WebCam                                   | 38        | 2.13%   |
| Syntek Integrated Camera                            | 31        | 1.73%   |
| Chicony USB2.0 Camera                               | 31        | 1.73%   |
| Bison Integrated Camera                             | 31        | 1.73%   |
| Sunplus Integrated_Webcam_HD                        | 30        | 1.68%   |
| Bison HD Webcam                                     | 30        | 1.68%   |
| Quanta HD User Facing                               | 27        | 1.51%   |
| Apple Built-in iSight                               | 27        | 1.51%   |
| Apple FaceTime HD Camera                            | 23        | 1.29%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                  | 20        | 1.12%   |
| Sonix USB2.0 HD UVC WebCam                          | 18        | 1.01%   |
| Chicony HP HD Camera                                | 18        | 1.01%   |
| Chicony HD User Facing                              | 18        | 1.01%   |
| Quanta HP HD Camera                                 | 17        | 0.95%   |
| Quanta HP TrueVision HD Camera                      | 16        | 0.89%   |
| Bison SunplusIT Integrated Camera                   | 16        | 0.89%   |
| Microdia Integrated Webcam                          | 15        | 0.84%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 15        | 0.84%   |
| Lite-On Integrated Camera                           | 14        | 0.78%   |
| Chicony USB2.0 VGA UVC WebCam                       | 14        | 0.78%   |
| Realtek Integrated Webcam                           | 13        | 0.73%   |
| Chicony HP TrueVision HD Camera                     | 13        | 0.73%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 12        | 0.67%   |
| Luxvisions Innotech Limited HP HD Camera            | 12        | 0.67%   |
| Chicony USB 2.0 Camera                              | 12        | 0.67%   |
| Chicony Integrated Camera (1280x720@30)             | 12        | 0.67%   |
| Samsung Galaxy series, misc. (MTP mode)             | 11        | 0.62%   |
| Chicony Integrated IR Camera                        | 11        | 0.62%   |
| Microdia Integrated Webcam HD                       | 10        | 0.56%   |
| Apple FaceTime HD Camera (Built-in)                 | 10        | 0.56%   |
| Realtek USB Camera                                  | 9         | 0.5%    |
| Quanta HP Wide Vision HD Camera                     | 9         | 0.5%    |
| Microdia USB 2.0 Camera                             | 9         | 0.5%    |
| Microdia Integrated_Webcam_FHD                      | 9         | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 117       | 34.51%  |
| Validity Sensors                   | 94        | 27.73%  |
| Shenzhen Goodix Technology         | 62        | 18.29%  |
| Elan Microelectronics              | 19        | 5.6%    |
| Upek                               | 14        | 4.13%   |
| LighTuning Technology              | 12        | 3.54%   |
| AuthenTec                          | 8         | 2.36%   |
| Realtek USB2.0 Finger Print Bridge | 5         | 1.47%   |
| Focal-systems.Corp                 | 5         | 1.47%   |
| HOLTEK                             | 3         | 0.88%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 33        | 9.73%   |
| Shenzhen Goodix  Fingerprint Device                                        | 33        | 9.73%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 23        | 6.78%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 22        | 6.49%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 17        | 5.01%   |
| Shenzhen Goodix FingerPrint                                                | 16        | 4.72%   |
| Shenzhen Goodix Fingerprint Reader                                         | 13        | 3.83%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 11        | 3.24%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 10        | 2.95%   |
| Elan ELAN:ARM-M4                                                           | 10        | 2.95%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 9         | 2.65%   |
| Synaptics WBDI Device                                                      | 9         | 2.65%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 8         | 2.36%   |
| Elan ELAN:Fingerprint                                                      | 8         | 2.36%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 7         | 2.06%   |
| Validity Sensors Synaptics WBDI                                            | 7         | 2.06%   |
| Validity Sensors Fingerprint scanner                                       | 7         | 2.06%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 1.77%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 6         | 1.77%   |
| Synaptics Fingerprint reader [HP G6]                                       | 6         | 1.77%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 5         | 1.47%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 1.47%   |
| Synaptics UWP WBDI Device                                                  | 5         | 1.47%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 5         | 1.47%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 5         | 1.47%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 5         | 1.47%   |
| Unknown                                                                    | 5         | 1.47%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 1.18%   |
| Synaptics UWP WBDI                                                         | 4         | 1.18%   |
| Synaptics  WBDI                                                            | 4         | 1.18%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 4         | 1.18%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 1.18%   |
| Validity Sensors VFS491                                                    | 3         | 0.88%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.88%   |
| Upek TCS5B Fingerprint sensor                                              | 3         | 0.88%   |
| HOLTEK FocalTech Fingerprint Device                                        | 3         | 0.88%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 0.88%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 0.59%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 0.59%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.29%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 65        | 54.62%  |
| Alcor Micro           | 35        | 29.41%  |
| O2 Micro              | 7         | 5.88%   |
| Lenovo                | 5         | 4.2%    |
| Upek                  | 4         | 3.36%   |
| OmniKey               | 1         | 0.84%   |
| Gemalto (was Gemplus) | 1         | 0.84%   |
| Clay Logic            | 1         | 0.84%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 35        | 29.41%  |
| Broadcom 58200                                                               | 21        | 17.65%  |
| Broadcom 5880                                                                | 18        | 15.13%  |
| Broadcom BCM5880 Secure Applications Processor                               | 16        | 13.45%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 10        | 8.4%    |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 6         | 5.04%   |
| Lenovo Integrated Smart Card Reader                                          | 5         | 4.2%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 3.36%   |
| OmniKey CardMan 4321                                                         | 1         | 0.84%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.84%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.84%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.84%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1177      | 59.29%  |
| 1     | 638       | 32.14%  |
| 2     | 145       | 7.3%    |
| 3     | 22        | 1.11%   |
| 4     | 2         | 0.1%    |
| 6     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 327       | 33.61%  |
| Multimedia controller    | 156       | 16.03%  |
| Graphics card            | 114       | 11.72%  |
| Chipcard                 | 112       | 11.51%  |
| Net/wireless             | 101       | 10.38%  |
| Bluetooth                | 53        | 5.45%   |
| Camera                   | 42        | 4.32%   |
| Sound                    | 16        | 1.64%   |
| Storage                  | 9         | 0.92%   |
| Network                  | 9         | 0.92%   |
| Net/ethernet             | 9         | 0.92%   |
| Communication controller | 8         | 0.82%   |
| Modem                    | 7         | 0.72%   |
| Card reader              | 7         | 0.72%   |
| Storage/ide              | 2         | 0.21%   |
| Storage/nvme             | 1         | 0.1%    |

