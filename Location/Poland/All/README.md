Linux in Poland - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Poland.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Poland/Desktop/README.md) and [notebooks](/Location/Poland/Notebook/README.md).

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

Total: 8172

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [34b8e1853b](https://linux-hardware.org/?probe=34b8e1853b) | Oct 01, 2023 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [6c314cd812](https://linux-hardware.org/?probe=6c314cd812) | Oct 01, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [f9be6afb3a](https://linux-hardware.org/?probe=f9be6afb3a) | Oct 01, 2023 |
| ASRock        | FM2A55M-VG3+                | Desktop     | [6faa4fd636](https://linux-hardware.org/?probe=6faa4fd636) | Oct 01, 2023 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | Notebook    | [61a08e5e89](https://linux-hardware.org/?probe=61a08e5e89) | Oct 01, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [0a11dba9ac](https://linux-hardware.org/?probe=0a11dba9ac) | Sep 30, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [48ff113276](https://linux-hardware.org/?probe=48ff113276) | Sep 30, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [d180995f93](https://linux-hardware.org/?probe=d180995f93) | Sep 30, 2023 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [63c99972d1](https://linux-hardware.org/?probe=63c99972d1) | Sep 30, 2023 |
| Acer          | Aspire E5-571G              | Notebook    | [b223d9b4f5](https://linux-hardware.org/?probe=b223d9b4f5) | Sep 30, 2023 |
| Dell          | Latitude 5430               | Notebook    | [eee2a34ff5](https://linux-hardware.org/?probe=eee2a34ff5) | Sep 30, 2023 |
| HP            | ProBook 6560b               | Notebook    | [904f0eb2cb](https://linux-hardware.org/?probe=904f0eb2cb) | Sep 30, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [a0e4942d9f](https://linux-hardware.org/?probe=a0e4942d9f) | Sep 30, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | Notebook    | [702d68e226](https://linux-hardware.org/?probe=702d68e226) | Sep 30, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [3bec9011bd](https://linux-hardware.org/?probe=3bec9011bd) | Sep 30, 2023 |
| HP            | Notebook                    | Notebook    | [193ec8deb3](https://linux-hardware.org/?probe=193ec8deb3) | Sep 30, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [8e039e23f3](https://linux-hardware.org/?probe=8e039e23f3) | Sep 29, 2023 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | Notebook    | [6e7e482b2d](https://linux-hardware.org/?probe=6e7e482b2d) | Sep 29, 2023 |
| Intel         | NUC13ANBi5 M89647-202       | Mini pc     | [e1f22fdce4](https://linux-hardware.org/?probe=e1f22fdce4) | Sep 29, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [cd9628c344](https://linux-hardware.org/?probe=cd9628c344) | Sep 29, 2023 |
| HP            | EliteBook 745 G5            | Notebook    | [b734ec49e2](https://linux-hardware.org/?probe=b734ec49e2) | Sep 29, 2023 |
| ASUSTek       | K55VJ                       | Notebook    | [4befa6db63](https://linux-hardware.org/?probe=4befa6db63) | Sep 29, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [0e4e90fac1](https://linux-hardware.org/?probe=0e4e90fac1) | Sep 29, 2023 |
| Lenovo        | IdeaPad Y530                | Notebook    | [83a6d1b19b](https://linux-hardware.org/?probe=83a6d1b19b) | Sep 28, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [1d2bd102c6](https://linux-hardware.org/?probe=1d2bd102c6) | Sep 28, 2023 |
| HP            | 620                         | Notebook    | [1bdfd56638](https://linux-hardware.org/?probe=1bdfd56638) | Sep 27, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [4ef9eaaaba](https://linux-hardware.org/?probe=4ef9eaaaba) | Sep 27, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [5646b6da22](https://linux-hardware.org/?probe=5646b6da22) | Sep 27, 2023 |
| HP            | 1589                        | Desktop     | [1063a6e665](https://linux-hardware.org/?probe=1063a6e665) | Sep 27, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [8e70938939](https://linux-hardware.org/?probe=8e70938939) | Sep 27, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [4f1f07158b](https://linux-hardware.org/?probe=4f1f07158b) | Sep 26, 2023 |
| Google        | Blorb                       | Notebook    | [efa4ad9e2c](https://linux-hardware.org/?probe=efa4ad9e2c) | Sep 26, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [09a71cddc4](https://linux-hardware.org/?probe=09a71cddc4) | Sep 26, 2023 |
| Lenovo        | ThinkPad T590 20N5S31U02    | Notebook    | [d4137582b5](https://linux-hardware.org/?probe=d4137582b5) | Sep 26, 2023 |
| Google        | Phaser360                   | Notebook    | [95686db08c](https://linux-hardware.org/?probe=95686db08c) | Sep 26, 2023 |
| Lenovo        | ThinkPad T590 20N5S31U02    | Notebook    | [aa988ac4df](https://linux-hardware.org/?probe=aa988ac4df) | Sep 26, 2023 |
| Lenovo        | ThinkPad T480s 20L8S77U1... | Notebook    | [4a3185fd78](https://linux-hardware.org/?probe=4a3185fd78) | Sep 26, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [5ab77e3f48](https://linux-hardware.org/?probe=5ab77e3f48) | Sep 26, 2023 |
| Dell          | Latitude 3190               | Notebook    | [8ebd8669f2](https://linux-hardware.org/?probe=8ebd8669f2) | Sep 26, 2023 |
| Dell          | Inspiron 3581               | Notebook    | [11796876dd](https://linux-hardware.org/?probe=11796876dd) | Sep 25, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [32a39c6a01](https://linux-hardware.org/?probe=32a39c6a01) | Sep 25, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [2881d9e4ec](https://linux-hardware.org/?probe=2881d9e4ec) | Sep 25, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [4c68092d28](https://linux-hardware.org/?probe=4c68092d28) | Sep 25, 2023 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [3afc2a0804](https://linux-hardware.org/?probe=3afc2a0804) | Sep 24, 2023 |
| Huanan        | X99-TF V1.1                 | Desktop     | [694b4ab1f2](https://linux-hardware.org/?probe=694b4ab1f2) | Sep 24, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | Notebook    | [408377c3fd](https://linux-hardware.org/?probe=408377c3fd) | Sep 24, 2023 |
| HP            | 3397                        | Desktop     | [cc6f1cc8ba](https://linux-hardware.org/?probe=cc6f1cc8ba) | Sep 24, 2023 |
| Dell          | System Vostro 3750          | Notebook    | [3b050c2582](https://linux-hardware.org/?probe=3b050c2582) | Sep 24, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [ff891ca545](https://linux-hardware.org/?probe=ff891ca545) | Sep 24, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [da4274c691](https://linux-hardware.org/?probe=da4274c691) | Sep 24, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [b3a0648c6e](https://linux-hardware.org/?probe=b3a0648c6e) | Sep 24, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [6b3c3ce703](https://linux-hardware.org/?probe=6b3c3ce703) | Sep 23, 2023 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [5735f79e4f](https://linux-hardware.org/?probe=5735f79e4f) | Sep 23, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [46a99bb50a](https://linux-hardware.org/?probe=46a99bb50a) | Sep 23, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [e2dd7767f0](https://linux-hardware.org/?probe=e2dd7767f0) | Sep 23, 2023 |
| Dell          | Precision M6600             | Notebook    | [1cef385aec](https://linux-hardware.org/?probe=1cef385aec) | Sep 23, 2023 |
| ASUSTek       | P5K                         | Desktop     | [4d67ad50cf](https://linux-hardware.org/?probe=4d67ad50cf) | Sep 22, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [4bf358cd4f](https://linux-hardware.org/?probe=4bf358cd4f) | Sep 22, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [1d9ae81bf1](https://linux-hardware.org/?probe=1d9ae81bf1) | Sep 22, 2023 |
| Dell          | Latitude 5421               | Notebook    | [fd5892945d](https://linux-hardware.org/?probe=fd5892945d) | Sep 21, 2023 |
| Dell          | Latitude 5421               | Notebook    | [50a3d79521](https://linux-hardware.org/?probe=50a3d79521) | Sep 21, 2023 |
| ASUSTek       | X99-A/USB                   | Desktop     | [37990955f8](https://linux-hardware.org/?probe=37990955f8) | Sep 21, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [8e60d0df9c](https://linux-hardware.org/?probe=8e60d0df9c) | Sep 21, 2023 |
| Apple         | Mac-27AD2F918AE68F61 Mac... | Desktop     | [ff9bab7040](https://linux-hardware.org/?probe=ff9bab7040) | Sep 21, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [459e666cd3](https://linux-hardware.org/?probe=459e666cd3) | Sep 21, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [dfb78764ea](https://linux-hardware.org/?probe=dfb78764ea) | Sep 20, 2023 |
| Lenovo        | ThinkPad X270 20HMS0DF00    | Notebook    | [276048d4f4](https://linux-hardware.org/?probe=276048d4f4) | Sep 20, 2023 |
| HP            | ProBook 6560b               | Notebook    | [a7eae64ec7](https://linux-hardware.org/?probe=a7eae64ec7) | Sep 20, 2023 |
| Lenovo        | ThinkPad E580 20KS001RUK    | Notebook    | [9882734ee2](https://linux-hardware.org/?probe=9882734ee2) | Sep 20, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [b66d6be0cf](https://linux-hardware.org/?probe=b66d6be0cf) | Sep 19, 2023 |
| HP            | 3047h                       | Desktop     | [f684816e88](https://linux-hardware.org/?probe=f684816e88) | Sep 19, 2023 |
| ASUSTek       | Maximus IX FORMULA          | Desktop     | [e76f3de142](https://linux-hardware.org/?probe=e76f3de142) | Sep 19, 2023 |
| HP            | EliteBook 735 G6            | Notebook    | [0ad032f320](https://linux-hardware.org/?probe=0ad032f320) | Sep 19, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [0748266b0a](https://linux-hardware.org/?probe=0748266b0a) | Sep 19, 2023 |
| Medion        | MS-7848                     | Desktop     | [acbe0e1821](https://linux-hardware.org/?probe=acbe0e1821) | Sep 19, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [8d1653a141](https://linux-hardware.org/?probe=8d1653a141) | Sep 19, 2023 |
| ASUSTek       | PRIME B460-PLUS             | Desktop     | [1ac41cc2e4](https://linux-hardware.org/?probe=1ac41cc2e4) | Sep 19, 2023 |
| Dell          | Latitude 3190               | Notebook    | [0a698044d8](https://linux-hardware.org/?probe=0a698044d8) | Sep 19, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [5680b32e39](https://linux-hardware.org/?probe=5680b32e39) | Sep 18, 2023 |
| Dell          | 0DY2X0 A01                  | Server      | [2384b2e12c](https://linux-hardware.org/?probe=2384b2e12c) | Sep 18, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [7b51f6f455](https://linux-hardware.org/?probe=7b51f6f455) | Sep 18, 2023 |
| HP            | Notebook                    | Notebook    | [c41430992d](https://linux-hardware.org/?probe=c41430992d) | Sep 18, 2023 |
| Dell          | Latitude 5490               | Notebook    | [94eb709dfc](https://linux-hardware.org/?probe=94eb709dfc) | Sep 18, 2023 |
| Lenovo        | ThinkPad T460 20FN003LMS    | Notebook    | [13de66f73a](https://linux-hardware.org/?probe=13de66f73a) | Sep 17, 2023 |
| Dell          | Latitude E5420              | Notebook    | [56c6b73d62](https://linux-hardware.org/?probe=56c6b73d62) | Sep 17, 2023 |
| Dell          | Latitude E5420              | Notebook    | [5931b51b00](https://linux-hardware.org/?probe=5931b51b00) | Sep 17, 2023 |
| HP            | G72                         | Notebook    | [b77f2ba361](https://linux-hardware.org/?probe=b77f2ba361) | Sep 17, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | Notebook    | [832c9cf416](https://linux-hardware.org/?probe=832c9cf416) | Sep 17, 2023 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [8368825071](https://linux-hardware.org/?probe=8368825071) | Sep 17, 2023 |
| Dell          | Latitude 5421               | Notebook    | [a42c87b953](https://linux-hardware.org/?probe=a42c87b953) | Sep 17, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | Notebook    | [ef3516c115](https://linux-hardware.org/?probe=ef3516c115) | Sep 17, 2023 |
| IGEL Techn... | M330C                       | Notebook    | [ba678c25e1](https://linux-hardware.org/?probe=ba678c25e1) | Sep 17, 2023 |
| IGEL Techn... | M330C                       | Notebook    | [b056244ce9](https://linux-hardware.org/?probe=b056244ce9) | Sep 17, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [8af23c2e56](https://linux-hardware.org/?probe=8af23c2e56) | Sep 17, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [35d0dc4629](https://linux-hardware.org/?probe=35d0dc4629) | Sep 17, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [50bfb485e5](https://linux-hardware.org/?probe=50bfb485e5) | Sep 17, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [d795a474b2](https://linux-hardware.org/?probe=d795a474b2) | Sep 16, 2023 |
| ASUSTek       | PRIME H770-PLUS             | Desktop     | [c58fea9225](https://linux-hardware.org/?probe=c58fea9225) | Sep 16, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [9915642af4](https://linux-hardware.org/?probe=9915642af4) | Sep 16, 2023 |
| Acer          | Predator G3-710             | Desktop     | [aa2ac7f07c](https://linux-hardware.org/?probe=aa2ac7f07c) | Sep 16, 2023 |
| Dell          | Latitude 9420               | Notebook    | [35feb16995](https://linux-hardware.org/?probe=35feb16995) | Sep 15, 2023 |
| HP            | 339A                        | Desktop     | [5808e19d94](https://linux-hardware.org/?probe=5808e19d94) | Sep 15, 2023 |
| Dell          | Latitude 9420               | Notebook    | [da407d0553](https://linux-hardware.org/?probe=da407d0553) | Sep 15, 2023 |
| Gigabyte      | P35-DS3                     | Desktop     | [7cf209e4c1](https://linux-hardware.org/?probe=7cf209e4c1) | Sep 15, 2023 |
| ASUSTek       | A88XM-E                     | Desktop     | [a3d82edc9c](https://linux-hardware.org/?probe=a3d82edc9c) | Sep 15, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [8f1762e098](https://linux-hardware.org/?probe=8f1762e098) | Sep 15, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [d321e5cfc8](https://linux-hardware.org/?probe=d321e5cfc8) | Sep 14, 2023 |
| Acer          | Nitro AN515-42              | Notebook    | [96f4c972a0](https://linux-hardware.org/?probe=96f4c972a0) | Sep 14, 2023 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [c3d0531198](https://linux-hardware.org/?probe=c3d0531198) | Sep 14, 2023 |
| Huanan        | X99-TF V1.1                 | Desktop     | [a5acc6026f](https://linux-hardware.org/?probe=a5acc6026f) | Sep 14, 2023 |
| Toshiba       | Intel H81/Q87 PCH 32        | All in one  | [43275b430f](https://linux-hardware.org/?probe=43275b430f) | Sep 14, 2023 |
| ASUSTek       | P553UJ                      | Notebook    | [3463413300](https://linux-hardware.org/?probe=3463413300) | Sep 14, 2023 |
| Acer          | Veriton N4640G              | Desktop     | [df814b2a84](https://linux-hardware.org/?probe=df814b2a84) | Sep 13, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [a09109e90c](https://linux-hardware.org/?probe=a09109e90c) | Sep 13, 2023 |
| Dell          | 07T4MC A06                  | Desktop     | [393a33da8c](https://linux-hardware.org/?probe=393a33da8c) | Sep 12, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [d4e392a0ad](https://linux-hardware.org/?probe=d4e392a0ad) | Sep 12, 2023 |
| MSI           | Z170A GAMING M9 ACK         | Desktop     | [49cc8ea6d2](https://linux-hardware.org/?probe=49cc8ea6d2) | Sep 12, 2023 |
| Dell          | Latitude E4200              | Notebook    | [ab13ebe930](https://linux-hardware.org/?probe=ab13ebe930) | Sep 12, 2023 |
| Dell          | Latitude 3190               | Notebook    | [a03ec42023](https://linux-hardware.org/?probe=a03ec42023) | Sep 12, 2023 |
| Lenovo        | G565 20071                  | Notebook    | [34149789e7](https://linux-hardware.org/?probe=34149789e7) | Sep 12, 2023 |
| HP            | 620                         | Notebook    | [59577ac122](https://linux-hardware.org/?probe=59577ac122) | Sep 12, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [27b430aa3f](https://linux-hardware.org/?probe=27b430aa3f) | Sep 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [7c32a84014](https://linux-hardware.org/?probe=7c32a84014) | Sep 11, 2023 |
| Dell          | 0HJK12 A03                  | Server      | [b4ec3650ef](https://linux-hardware.org/?probe=b4ec3650ef) | Sep 11, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [3716cce5f9](https://linux-hardware.org/?probe=3716cce5f9) | Sep 11, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [77105eb7da](https://linux-hardware.org/?probe=77105eb7da) | Sep 11, 2023 |
| ASUSTek       | H110M-D                     | Desktop     | [de229ab61f](https://linux-hardware.org/?probe=de229ab61f) | Sep 11, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [a25f4b1c5c](https://linux-hardware.org/?probe=a25f4b1c5c) | Sep 11, 2023 |
| Dell          | Precision 5530              | Notebook    | [7e0e7dca27](https://linux-hardware.org/?probe=7e0e7dca27) | Sep 10, 2023 |
| Dell          | 07T4MC A06                  | Desktop     | [ec26895704](https://linux-hardware.org/?probe=ec26895704) | Sep 10, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [9b4b4d897f](https://linux-hardware.org/?probe=9b4b4d897f) | Sep 10, 2023 |
| LG Electro... | 15Z990-U.AAS5U1             | Notebook    | [61eed61cd5](https://linux-hardware.org/?probe=61eed61cd5) | Sep 10, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [f01636c129](https://linux-hardware.org/?probe=f01636c129) | Sep 09, 2023 |
| Lenovo        | ThinkPad L390 20NSS04400    | Notebook    | [e35abd1445](https://linux-hardware.org/?probe=e35abd1445) | Sep 09, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [dffd28975a](https://linux-hardware.org/?probe=dffd28975a) | Sep 09, 2023 |
| HP            | ProBook 6470b               | Notebook    | [1c8817d025](https://linux-hardware.org/?probe=1c8817d025) | Sep 09, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [23e3266b07](https://linux-hardware.org/?probe=23e3266b07) | Sep 08, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [032db27cfa](https://linux-hardware.org/?probe=032db27cfa) | Sep 08, 2023 |
| Lenovo        | G565 20071                  | Notebook    | [786aafb0e9](https://linux-hardware.org/?probe=786aafb0e9) | Sep 07, 2023 |
| HP            | 1589                        | Desktop     | [550b95765c](https://linux-hardware.org/?probe=550b95765c) | Sep 06, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d3e36fc6ea](https://linux-hardware.org/?probe=d3e36fc6ea) | Sep 05, 2023 |
| Dell          | 0T10XW A00                  | Desktop     | [89f4028960](https://linux-hardware.org/?probe=89f4028960) | Sep 05, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [01ede034b7](https://linux-hardware.org/?probe=01ede034b7) | Sep 05, 2023 |
| Dell          | 0J3C2F A00                  | Desktop     | [1aa546be8c](https://linux-hardware.org/?probe=1aa546be8c) | Sep 05, 2023 |
| MSI           | P55-GD65                    | Desktop     | [2b514a72b1](https://linux-hardware.org/?probe=2b514a72b1) | Sep 05, 2023 |
| Dell          | Precision M4800             | Notebook    | [2e40a27b2e](https://linux-hardware.org/?probe=2e40a27b2e) | Sep 04, 2023 |
| Prestigio     | Smartbook PSB116A           | Notebook    | [d70df77a35](https://linux-hardware.org/?probe=d70df77a35) | Sep 04, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [1d6a4b4279](https://linux-hardware.org/?probe=1d6a4b4279) | Sep 04, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [f51b98f4cd](https://linux-hardware.org/?probe=f51b98f4cd) | Sep 04, 2023 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [2973871c04](https://linux-hardware.org/?probe=2973871c04) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [2a24e7410f](https://linux-hardware.org/?probe=2a24e7410f) | Sep 03, 2023 |
| Gigabyte      | G41M-Combo                  | Desktop     | [26c9b8cc2c](https://linux-hardware.org/?probe=26c9b8cc2c) | Sep 03, 2023 |
| Unknown       | Unknown                     | Notebook    | [8585671bfb](https://linux-hardware.org/?probe=8585671bfb) | Sep 03, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [efd96ce796](https://linux-hardware.org/?probe=efd96ce796) | Sep 03, 2023 |
| Gigabyte      | PH67A-D3-B3                 | Desktop     | [a9fdf4f92b](https://linux-hardware.org/?probe=a9fdf4f92b) | Sep 03, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [dcb8595c51](https://linux-hardware.org/?probe=dcb8595c51) | Sep 03, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [5f73c55303](https://linux-hardware.org/?probe=5f73c55303) | Sep 03, 2023 |
| Lenovo        | ThinkPad X280 20KESAA400    | Notebook    | [461a3a9bc9](https://linux-hardware.org/?probe=461a3a9bc9) | Sep 02, 2023 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | Desktop     | [8533d021f8](https://linux-hardware.org/?probe=8533d021f8) | Sep 02, 2023 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [53b682d960](https://linux-hardware.org/?probe=53b682d960) | Sep 02, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [9f3df2894e](https://linux-hardware.org/?probe=9f3df2894e) | Sep 02, 2023 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [f6a5d73879](https://linux-hardware.org/?probe=f6a5d73879) | Sep 01, 2023 |
| Valve         | Jupiter                     | Notebook    | [fd0297e4e0](https://linux-hardware.org/?probe=fd0297e4e0) | Sep 01, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [678bbd1366](https://linux-hardware.org/?probe=678bbd1366) | Sep 01, 2023 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [d5d9154715](https://linux-hardware.org/?probe=d5d9154715) | Sep 01, 2023 |
| Lenovo        | ThinkPad X301 2774LEG       | Notebook    | [50f297712d](https://linux-hardware.org/?probe=50f297712d) | Sep 01, 2023 |
| HP            | 1589                        | Desktop     | [447cae1b4c](https://linux-hardware.org/?probe=447cae1b4c) | Sep 01, 2023 |
| ASRock        | H97M Pro4                   | Desktop     | [ff1be33f8e](https://linux-hardware.org/?probe=ff1be33f8e) | Sep 01, 2023 |
| Dell          | Inspiron 13-5368            | Notebook    | [e811db37c5](https://linux-hardware.org/?probe=e811db37c5) | Sep 01, 2023 |
| Lenovo        | ThinkPad S5-S540 20B3006... | Notebook    | [e33b222d6c](https://linux-hardware.org/?probe=e33b222d6c) | Sep 01, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [0ac2938640](https://linux-hardware.org/?probe=0ac2938640) | Aug 31, 2023 |
| ASUSTek       | Crosshair V Formula         | Desktop     | [85cb771ac1](https://linux-hardware.org/?probe=85cb771ac1) | Aug 31, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [ca52538b46](https://linux-hardware.org/?probe=ca52538b46) | Aug 31, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [b900fd0bc7](https://linux-hardware.org/?probe=b900fd0bc7) | Aug 31, 2023 |
| HP            | ProBook 4530s               | Notebook    | [09fddaab4d](https://linux-hardware.org/?probe=09fddaab4d) | Aug 31, 2023 |
| Dell          | Latitude 7390               | Notebook    | [a9c1ad1756](https://linux-hardware.org/?probe=a9c1ad1756) | Aug 31, 2023 |
| HP            | ProBook 645 G1              | Notebook    | [ca7a99ecd9](https://linux-hardware.org/?probe=ca7a99ecd9) | Aug 31, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [76f095d7c2](https://linux-hardware.org/?probe=76f095d7c2) | Aug 31, 2023 |
| HP            | 8158 A01                    | Mini pc     | [9be38fb21f](https://linux-hardware.org/?probe=9be38fb21f) | Aug 30, 2023 |
| Dell          | Inspiron 7520               | Notebook    | [f3e3f12f08](https://linux-hardware.org/?probe=f3e3f12f08) | Aug 30, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [3977e85dce](https://linux-hardware.org/?probe=3977e85dce) | Aug 30, 2023 |
| HP            | 3047h                       | Desktop     | [5a35a1ebd1](https://linux-hardware.org/?probe=5a35a1ebd1) | Aug 30, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [a2f37c4111](https://linux-hardware.org/?probe=a2f37c4111) | Aug 30, 2023 |
| Dell          | Latitude 5430               | Notebook    | [477898be1f](https://linux-hardware.org/?probe=477898be1f) | Aug 30, 2023 |
| Lenovo        | ThinkPad T470p 20J60014P... | Notebook    | [7690eb9089](https://linux-hardware.org/?probe=7690eb9089) | Aug 30, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [5ba6fd6ca3](https://linux-hardware.org/?probe=5ba6fd6ca3) | Aug 30, 2023 |
| Dell          | Latitude E6520              | Notebook    | [4918e66ad8](https://linux-hardware.org/?probe=4918e66ad8) | Aug 29, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [567a59e1bc](https://linux-hardware.org/?probe=567a59e1bc) | Aug 29, 2023 |
| Dell          | Latitude 3190               | Notebook    | [6e16da127a](https://linux-hardware.org/?probe=6e16da127a) | Aug 29, 2023 |
| Dell          | Latitude D630               | Notebook    | [d23ff7e118](https://linux-hardware.org/?probe=d23ff7e118) | Aug 29, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [8741a9bb96](https://linux-hardware.org/?probe=8741a9bb96) | Aug 29, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [7efcdba9ef](https://linux-hardware.org/?probe=7efcdba9ef) | Aug 29, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | Notebook    | [7e48b59643](https://linux-hardware.org/?probe=7e48b59643) | Aug 29, 2023 |
| Acer          | Acadia V1.45                | Notebook    | [4bc36b4d27](https://linux-hardware.org/?probe=4bc36b4d27) | Aug 29, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [9071631c6d](https://linux-hardware.org/?probe=9071631c6d) | Aug 28, 2023 |
| ASUSTek       | ZenBook UX362FA_UX362FA     | Convertible | [e09a09d01e](https://linux-hardware.org/?probe=e09a09d01e) | Aug 26, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [e6e9efdb61](https://linux-hardware.org/?probe=e6e9efdb61) | Aug 26, 2023 |
| Dell          | 0JCTF8 A00                  | Desktop     | [af55d05855](https://linux-hardware.org/?probe=af55d05855) | Aug 26, 2023 |
| mPTech        | ARC 11.6 128GB HD           | Notebook    | [4167149587](https://linux-hardware.org/?probe=4167149587) | Aug 26, 2023 |
| Essentiel ... | MS-7848                     | Desktop     | [228bdfda30](https://linux-hardware.org/?probe=228bdfda30) | Aug 26, 2023 |
| Essentiel ... | MS-7848                     | Desktop     | [9ce89a0c87](https://linux-hardware.org/?probe=9ce89a0c87) | Aug 26, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [3ee57cbdbe](https://linux-hardware.org/?probe=3ee57cbdbe) | Aug 26, 2023 |
| Lenovo        | ThinkPad E520 1143CWG       | Notebook    | [66d9a31686](https://linux-hardware.org/?probe=66d9a31686) | Aug 25, 2023 |
| Lenovo        | ThinkPad E560 20EV000UUK    | Notebook    | [01ae0852df](https://linux-hardware.org/?probe=01ae0852df) | Aug 25, 2023 |
| Dell          | Latitude E6400              | Notebook    | [4526151015](https://linux-hardware.org/?probe=4526151015) | Aug 25, 2023 |
| Lenovo        | SKYBAY NOK                  | Desktop     | [38448389ce](https://linux-hardware.org/?probe=38448389ce) | Aug 25, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [bb854d7896](https://linux-hardware.org/?probe=bb854d7896) | Aug 25, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [1f69210d69](https://linux-hardware.org/?probe=1f69210d69) | Aug 25, 2023 |
| Gigabyte      | GA-MA770T-UD3P              | Desktop     | [d1e0d41982](https://linux-hardware.org/?probe=d1e0d41982) | Aug 24, 2023 |
| Dell          | XPS 9320                    | Notebook    | [1ba8e13634](https://linux-hardware.org/?probe=1ba8e13634) | Aug 24, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [e6c72eb614](https://linux-hardware.org/?probe=e6c72eb614) | Aug 24, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [12ac0bf5ed](https://linux-hardware.org/?probe=12ac0bf5ed) | Aug 24, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [097bbaf86a](https://linux-hardware.org/?probe=097bbaf86a) | Aug 24, 2023 |
| Dell          | Latitude 3520               | Notebook    | [92ef936c86](https://linux-hardware.org/?probe=92ef936c86) | Aug 24, 2023 |
| Kiano         | Elegance 14.2               | Notebook    | [71ba491330](https://linux-hardware.org/?probe=71ba491330) | Aug 24, 2023 |
| Gigabyte      | P67A-UD7-B3                 | Desktop     | [912d956729](https://linux-hardware.org/?probe=912d956729) | Aug 24, 2023 |
| ASUSTek       | EX-A320M-GAMING             | Desktop     | [a28ee4ea6b](https://linux-hardware.org/?probe=a28ee4ea6b) | Aug 23, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [26d59e1060](https://linux-hardware.org/?probe=26d59e1060) | Aug 23, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [d10b0c4ca0](https://linux-hardware.org/?probe=d10b0c4ca0) | Aug 23, 2023 |
| HP            | Compaq nc8430 (EM741AV)     | Notebook    | [02d656a746](https://linux-hardware.org/?probe=02d656a746) | Aug 22, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [25d163ad9e](https://linux-hardware.org/?probe=25d163ad9e) | Aug 22, 2023 |
| Dell          | Latitude 3190               | Notebook    | [61ddf042df](https://linux-hardware.org/?probe=61ddf042df) | Aug 22, 2023 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [5a9badb376](https://linux-hardware.org/?probe=5a9badb376) | Aug 22, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c080c15699](https://linux-hardware.org/?probe=c080c15699) | Aug 22, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [a03d5e6451](https://linux-hardware.org/?probe=a03d5e6451) | Aug 21, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [fd5614f8d1](https://linux-hardware.org/?probe=fd5614f8d1) | Aug 21, 2023 |
| Lenovo        | Legion 5 15IAH7 82RC        | Notebook    | [5fa4b8ae13](https://linux-hardware.org/?probe=5fa4b8ae13) | Aug 20, 2023 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [3911bdd51d](https://linux-hardware.org/?probe=3911bdd51d) | Aug 20, 2023 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [1979db3345](https://linux-hardware.org/?probe=1979db3345) | Aug 20, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [d1af143bed](https://linux-hardware.org/?probe=d1af143bed) | Aug 19, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [637bd422c5](https://linux-hardware.org/?probe=637bd422c5) | Aug 19, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [f5751cb101](https://linux-hardware.org/?probe=f5751cb101) | Aug 19, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [800ad97443](https://linux-hardware.org/?probe=800ad97443) | Aug 19, 2023 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [054a5a44ad](https://linux-hardware.org/?probe=054a5a44ad) | Aug 18, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [2173b6b2b0](https://linux-hardware.org/?probe=2173b6b2b0) | Aug 18, 2023 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [d84596d3c1](https://linux-hardware.org/?probe=d84596d3c1) | Aug 18, 2023 |
| ASUSTek       | P8Z68-V PRO GEN3            | Desktop     | [d05585906d](https://linux-hardware.org/?probe=d05585906d) | Aug 18, 2023 |
| Lenovo        | ThinkPad L480 20LTS6S904    | Notebook    | [32ded049ec](https://linux-hardware.org/?probe=32ded049ec) | Aug 17, 2023 |
| Valve         | Jupiter                     | Notebook    | [b2c7c5cb9f](https://linux-hardware.org/?probe=b2c7c5cb9f) | Aug 17, 2023 |
| HP            | Laptop 14-df0xxx            | Notebook    | [7d3c3dc329](https://linux-hardware.org/?probe=7d3c3dc329) | Aug 17, 2023 |
| Lenovo        | Legion 5 15IAH7 82RC        | Notebook    | [75556aed08](https://linux-hardware.org/?probe=75556aed08) | Aug 16, 2023 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [b9134a5ee3](https://linux-hardware.org/?probe=b9134a5ee3) | Aug 16, 2023 |
| Unknown       | Unknown                     | Convertible | [24b989fc80](https://linux-hardware.org/?probe=24b989fc80) | Aug 16, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [f3c603341d](https://linux-hardware.org/?probe=f3c603341d) | Aug 16, 2023 |
| Lenovo        | G505s 20255                 | Notebook    | [2486dc323f](https://linux-hardware.org/?probe=2486dc323f) | Aug 16, 2023 |
| MSI           | PRO H610M-G DDR4            | Desktop     | [bd75f21361](https://linux-hardware.org/?probe=bd75f21361) | Aug 16, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [4906f87d9e](https://linux-hardware.org/?probe=4906f87d9e) | Aug 16, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [abb0a09230](https://linux-hardware.org/?probe=abb0a09230) | Aug 16, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [ef53482168](https://linux-hardware.org/?probe=ef53482168) | Aug 16, 2023 |
| Lenovo        | ThinkPad T470 20HES07J00    | Notebook    | [32ec341753](https://linux-hardware.org/?probe=32ec341753) | Aug 16, 2023 |
| Gigabyte      | RC14UD                      | Notebook    | [51b04bf027](https://linux-hardware.org/?probe=51b04bf027) | Aug 16, 2023 |
| Samsung       | 530U4E/540U4E               | Notebook    | [7189151ffc](https://linux-hardware.org/?probe=7189151ffc) | Aug 15, 2023 |
| MSI           | H310M PRO-VDH               | Desktop     | [fe173bc6ed](https://linux-hardware.org/?probe=fe173bc6ed) | Aug 15, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [ce22773504](https://linux-hardware.org/?probe=ce22773504) | Aug 15, 2023 |
| Lenovo        | G580                        | Notebook    | [ceeee3c405](https://linux-hardware.org/?probe=ceeee3c405) | Aug 15, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [69deac32bd](https://linux-hardware.org/?probe=69deac32bd) | Aug 14, 2023 |
| Lenovo        | Legion 5 15IAH7H 82RB       | Notebook    | [076c807d2d](https://linux-hardware.org/?probe=076c807d2d) | Aug 14, 2023 |
| Samsung       | 530U4E/540U4E               | Notebook    | [6a886e53b9](https://linux-hardware.org/?probe=6a886e53b9) | Aug 14, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [7ff2052c0f](https://linux-hardware.org/?probe=7ff2052c0f) | Aug 14, 2023 |
| Lenovo        | ThinkPad 10 2nd 20E4S0SQ... | Tablet      | [833489f8a8](https://linux-hardware.org/?probe=833489f8a8) | Aug 13, 2023 |
| HP            | Pavilion dv7                | Notebook    | [8af14f1aaa](https://linux-hardware.org/?probe=8af14f1aaa) | Aug 13, 2023 |
| ASUSTek       | GL552VW                     | Notebook    | [1d77ac2450](https://linux-hardware.org/?probe=1d77ac2450) | Aug 13, 2023 |
| Acer          | Predator G5-793             | Notebook    | [bb25759563](https://linux-hardware.org/?probe=bb25759563) | Aug 13, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [84b4b40450](https://linux-hardware.org/?probe=84b4b40450) | Aug 13, 2023 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [25a3921b74](https://linux-hardware.org/?probe=25a3921b74) | Aug 13, 2023 |
| HP            | EliteBook 845 G9            | Notebook    | [cf6dfa50ef](https://linux-hardware.org/?probe=cf6dfa50ef) | Aug 12, 2023 |
| Valve         | Jupiter                     | Notebook    | [b770999baf](https://linux-hardware.org/?probe=b770999baf) | Aug 12, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [b296a33ab3](https://linux-hardware.org/?probe=b296a33ab3) | Aug 12, 2023 |
| ECS           | H61H2-M6                    | Desktop     | [b9b9ef9f84](https://linux-hardware.org/?probe=b9b9ef9f84) | Aug 12, 2023 |
| Apple         | MacBookPro13,3              | Notebook    | [b43e2738d9](https://linux-hardware.org/?probe=b43e2738d9) | Aug 12, 2023 |
| ASUSTek       | GL552VW                     | Notebook    | [6986ca63da](https://linux-hardware.org/?probe=6986ca63da) | Aug 12, 2023 |
| Fujitsu       | FMVA0800C                   | Notebook    | [1dae7b170b](https://linux-hardware.org/?probe=1dae7b170b) | Aug 12, 2023 |
| HP            | Pavilion dv7                | Notebook    | [7e4a63e58c](https://linux-hardware.org/?probe=7e4a63e58c) | Aug 12, 2023 |
| HP            | Pavilion dv7                | Notebook    | [fc48a936d7](https://linux-hardware.org/?probe=fc48a936d7) | Aug 12, 2023 |
| Gigabyte      | Z170N-WIFI-CF               | Desktop     | [2ee88f0ec0](https://linux-hardware.org/?probe=2ee88f0ec0) | Aug 11, 2023 |
| HP            | 83E8                        | Desktop     | [a782638343](https://linux-hardware.org/?probe=a782638343) | Aug 11, 2023 |
| Lenovo        | ThinkPad T430s 2356LPG      | Notebook    | [97dfe9511b](https://linux-hardware.org/?probe=97dfe9511b) | Aug 10, 2023 |
| Google        | Kip                         | Notebook    | [553df8dcdc](https://linux-hardware.org/?probe=553df8dcdc) | Aug 10, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d38ef662d4](https://linux-hardware.org/?probe=d38ef662d4) | Aug 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [78f477986b](https://linux-hardware.org/?probe=78f477986b) | Aug 10, 2023 |
| Dell          | Latitude E6540              | Notebook    | [758d587fbb](https://linux-hardware.org/?probe=758d587fbb) | Aug 10, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [a6eabbbfef](https://linux-hardware.org/?probe=a6eabbbfef) | Aug 09, 2023 |
| HP            | ProBook 450 G6              | Notebook    | [c205f19d5e](https://linux-hardware.org/?probe=c205f19d5e) | Aug 09, 2023 |
| HP            | EliteBook 845 G9            | Notebook    | [1ff8d81e4e](https://linux-hardware.org/?probe=1ff8d81e4e) | Aug 09, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [a5e0e043cb](https://linux-hardware.org/?probe=a5e0e043cb) | Aug 09, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [81411c1db8](https://linux-hardware.org/?probe=81411c1db8) | Aug 08, 2023 |
| Acer          | Aspire 5732Z                | Notebook    | [5a0ee0b4c0](https://linux-hardware.org/?probe=5a0ee0b4c0) | Aug 08, 2023 |
| MSI           | 970A-G43 PLUS               | Desktop     | [133d4b58c9](https://linux-hardware.org/?probe=133d4b58c9) | Aug 08, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [f6b63d9967](https://linux-hardware.org/?probe=f6b63d9967) | Aug 08, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [f2547c0339](https://linux-hardware.org/?probe=f2547c0339) | Aug 08, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [93e4fee7df](https://linux-hardware.org/?probe=93e4fee7df) | Aug 08, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [9094c29548](https://linux-hardware.org/?probe=9094c29548) | Aug 07, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | Desktop     | [25bb416eb3](https://linux-hardware.org/?probe=25bb416eb3) | Aug 07, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [068b8c5a6f](https://linux-hardware.org/?probe=068b8c5a6f) | Aug 07, 2023 |
| Dell          | Vostro 5471                 | Notebook    | [f4beee823e](https://linux-hardware.org/?probe=f4beee823e) | Aug 07, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [beecacb434](https://linux-hardware.org/?probe=beecacb434) | Aug 07, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [08b395f8d6](https://linux-hardware.org/?probe=08b395f8d6) | Aug 07, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [fb8e926bd4](https://linux-hardware.org/?probe=fb8e926bd4) | Aug 07, 2023 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [5a254fe1d6](https://linux-hardware.org/?probe=5a254fe1d6) | Aug 06, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [164e109040](https://linux-hardware.org/?probe=164e109040) | Aug 06, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [270c9a3ea0](https://linux-hardware.org/?probe=270c9a3ea0) | Aug 06, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | Notebook    | [f77c465da0](https://linux-hardware.org/?probe=f77c465da0) | Aug 06, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [db5a797fc0](https://linux-hardware.org/?probe=db5a797fc0) | Aug 06, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [23ecc4a8e5](https://linux-hardware.org/?probe=23ecc4a8e5) | Aug 06, 2023 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [dcd061dff8](https://linux-hardware.org/?probe=dcd061dff8) | Aug 05, 2023 |
| Dell          | 0K6VXP A00                  | Mini pc     | [4f0b615c8e](https://linux-hardware.org/?probe=4f0b615c8e) | Aug 05, 2023 |
| ASUSTek       | ROG Strix G731GU_GL731GU    | Notebook    | [b3c77ee42f](https://linux-hardware.org/?probe=b3c77ee42f) | Aug 05, 2023 |
| Dell          | Latitude 5421               | Notebook    | [d01013b679](https://linux-hardware.org/?probe=d01013b679) | Aug 05, 2023 |
| Dell          | Latitude 5421               | Notebook    | [5dfde4e6ac](https://linux-hardware.org/?probe=5dfde4e6ac) | Aug 05, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [420353bf79](https://linux-hardware.org/?probe=420353bf79) | Aug 04, 2023 |
| Gigabyte      | RC14UD                      | Notebook    | [6ad0758102](https://linux-hardware.org/?probe=6ad0758102) | Aug 04, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [34edcb7dae](https://linux-hardware.org/?probe=34edcb7dae) | Aug 04, 2023 |
| Dell          | Vostro 15 3510              | Notebook    | [bd994e4cc6](https://linux-hardware.org/?probe=bd994e4cc6) | Aug 04, 2023 |
| Dell          | Vostro 15 3510              | Notebook    | [ab2f3b8c7b](https://linux-hardware.org/?probe=ab2f3b8c7b) | Aug 04, 2023 |
| Lenovo        | Gardenia CRB SDK0J40700 ... | All in one  | [9f27152a86](https://linux-hardware.org/?probe=9f27152a86) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [8036065591](https://linux-hardware.org/?probe=8036065591) | Aug 03, 2023 |
| Lenovo        | 3140 SDK0J40697 WIN 3305... | Desktop     | [a61b8168b7](https://linux-hardware.org/?probe=a61b8168b7) | Aug 02, 2023 |
| ECS           | H61H2-M6                    | Desktop     | [12990c5c80](https://linux-hardware.org/?probe=12990c5c80) | Aug 02, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [9be3b9bb83](https://linux-hardware.org/?probe=9be3b9bb83) | Aug 02, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [1acfa69d70](https://linux-hardware.org/?probe=1acfa69d70) | Aug 02, 2023 |
| HP            | 8054                        | Desktop     | [f53df18325](https://linux-hardware.org/?probe=f53df18325) | Aug 02, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [8bc1531bf6](https://linux-hardware.org/?probe=8bc1531bf6) | Aug 02, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [ca00849760](https://linux-hardware.org/?probe=ca00849760) | Aug 02, 2023 |
| Dell          | Inspiron 13-5368            | Notebook    | [695e2dec6b](https://linux-hardware.org/?probe=695e2dec6b) | Aug 02, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [5d63b469f8](https://linux-hardware.org/?probe=5d63b469f8) | Aug 01, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [c2c27c3268](https://linux-hardware.org/?probe=c2c27c3268) | Aug 01, 2023 |
| ECS           | H61H2-M6                    | Desktop     | [836267e5f7](https://linux-hardware.org/?probe=836267e5f7) | Aug 01, 2023 |
| HP            | 82B5                        | All in one  | [e63af4a7b9](https://linux-hardware.org/?probe=e63af4a7b9) | Aug 01, 2023 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | Desktop     | [30389578ca](https://linux-hardware.org/?probe=30389578ca) | Aug 01, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS1... | Convertible | [af6a2cb993](https://linux-hardware.org/?probe=af6a2cb993) | Jul 31, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [3aeae112c3](https://linux-hardware.org/?probe=3aeae112c3) | Jul 31, 2023 |
| ASRock        | FM2A55M-VG3+                | Desktop     | [ce76d8b410](https://linux-hardware.org/?probe=ce76d8b410) | Jul 31, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [762d07665a](https://linux-hardware.org/?probe=762d07665a) | Jul 31, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [cd8671be26](https://linux-hardware.org/?probe=cd8671be26) | Jul 31, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [eb13fb97fb](https://linux-hardware.org/?probe=eb13fb97fb) | Jul 30, 2023 |
| ASUSTek       | E200HA                      | Notebook    | [6ab93e7940](https://linux-hardware.org/?probe=6ab93e7940) | Jul 30, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [60cfcb00e9](https://linux-hardware.org/?probe=60cfcb00e9) | Jul 30, 2023 |
| Intel         | NUC13ANBi5 M89647-202       | Mini pc     | [8e59554b8d](https://linux-hardware.org/?probe=8e59554b8d) | Jul 30, 2023 |
| Google        | Relm                        | Notebook    | [1c8bd1f9dd](https://linux-hardware.org/?probe=1c8bd1f9dd) | Jul 30, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [39bd06bd9b](https://linux-hardware.org/?probe=39bd06bd9b) | Jul 30, 2023 |
| Lenovo        | ThinkPad A285 20MXS0AE00    | Notebook    | [a6ada51a02](https://linux-hardware.org/?probe=a6ada51a02) | Jul 29, 2023 |
| Dell          | Latitude E7240              | Notebook    | [b794bcdde6](https://linux-hardware.org/?probe=b794bcdde6) | Jul 29, 2023 |
| Dell          | Inspiron 7559               | Notebook    | [fad00d6412](https://linux-hardware.org/?probe=fad00d6412) | Jul 29, 2023 |
| ASRock        | AM1H-ITX                    | Desktop     | [24b2f4274d](https://linux-hardware.org/?probe=24b2f4274d) | Jul 29, 2023 |
| ASUSTek       | X555LJ                      | Notebook    | [690e49362b](https://linux-hardware.org/?probe=690e49362b) | Jul 28, 2023 |
| HP            | Pavilion Gaming Laptop      | Notebook    | [b277fcda26](https://linux-hardware.org/?probe=b277fcda26) | Jul 28, 2023 |
| Gigabyte      | EP45T-UD3LR                 | Desktop     | [c2928283bd](https://linux-hardware.org/?probe=c2928283bd) | Jul 28, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [ca9b6e0320](https://linux-hardware.org/?probe=ca9b6e0320) | Jul 28, 2023 |
| Toshiba       | Satellite C50D-A-11G        | Notebook    | [b67508b754](https://linux-hardware.org/?probe=b67508b754) | Jul 27, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [f0bd5c3409](https://linux-hardware.org/?probe=f0bd5c3409) | Jul 27, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [e882db39b8](https://linux-hardware.org/?probe=e882db39b8) | Jul 27, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [e235fb3a23](https://linux-hardware.org/?probe=e235fb3a23) | Jul 26, 2023 |
| Dell          | Latitude 9420               | Notebook    | [03c3ca79c4](https://linux-hardware.org/?probe=03c3ca79c4) | Jul 26, 2023 |
| ASUSTek       | P5G41T-M                    | Desktop     | [355fadbc12](https://linux-hardware.org/?probe=355fadbc12) | Jul 26, 2023 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [863a5cb9da](https://linux-hardware.org/?probe=863a5cb9da) | Jul 26, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [e79fd50f34](https://linux-hardware.org/?probe=e79fd50f34) | Jul 26, 2023 |
| Lenovo        | ThinkCentre M58 3231W2Y     | Desktop     | [72f09cd320](https://linux-hardware.org/?probe=72f09cd320) | Jul 26, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [24f65961ef](https://linux-hardware.org/?probe=24f65961ef) | Jul 26, 2023 |
| ASUSTek       | M5A78L-M LE                 | Desktop     | [3cb7454711](https://linux-hardware.org/?probe=3cb7454711) | Jul 25, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [af0355313e](https://linux-hardware.org/?probe=af0355313e) | Jul 25, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [290a0dd297](https://linux-hardware.org/?probe=290a0dd297) | Jul 25, 2023 |
| Lenovo        | ThinkPad L470 20J5S01S00    | Notebook    | [346055ca33](https://linux-hardware.org/?probe=346055ca33) | Jul 25, 2023 |
| ZOTAC         | ZBOX-BI322                  | Mini pc     | [f595927b7b](https://linux-hardware.org/?probe=f595927b7b) | Jul 25, 2023 |
| HP            | 212B                        | Desktop     | [8e6a290d51](https://linux-hardware.org/?probe=8e6a290d51) | Jul 25, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [5ec24ea9ad](https://linux-hardware.org/?probe=5ec24ea9ad) | Jul 25, 2023 |
| Dell          | Latitude 3190               | Notebook    | [b1730d834d](https://linux-hardware.org/?probe=b1730d834d) | Jul 25, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [9ffd99b082](https://linux-hardware.org/?probe=9ffd99b082) | Jul 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [412bc51f72](https://linux-hardware.org/?probe=412bc51f72) | Jul 24, 2023 |
| HP            | 198E                        | Desktop     | [c2f7b19d13](https://linux-hardware.org/?probe=c2f7b19d13) | Jul 24, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [816a8d70bb](https://linux-hardware.org/?probe=816a8d70bb) | Jul 24, 2023 |
| Timi          | TM1701                      | Notebook    | [eb1246586e](https://linux-hardware.org/?probe=eb1246586e) | Jul 24, 2023 |
| ASUSTek       | F7E                         | Notebook    | [2aef1cc2c4](https://linux-hardware.org/?probe=2aef1cc2c4) | Jul 24, 2023 |
| Timi          | TM1701                      | Notebook    | [17fefbecba](https://linux-hardware.org/?probe=17fefbecba) | Jul 24, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [fbfa8af465](https://linux-hardware.org/?probe=fbfa8af465) | Jul 24, 2023 |
| Acer          | Aspire A715-74G             | Notebook    | [b27862dc34](https://linux-hardware.org/?probe=b27862dc34) | Jul 24, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [9243bb6a08](https://linux-hardware.org/?probe=9243bb6a08) | Jul 24, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [a2fcdf6c36](https://linux-hardware.org/?probe=a2fcdf6c36) | Jul 24, 2023 |
| ASUSTek       | X555LD                      | Notebook    | [732fe69d59](https://linux-hardware.org/?probe=732fe69d59) | Jul 23, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [44958ef86b](https://linux-hardware.org/?probe=44958ef86b) | Jul 23, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [10e8c0d4ad](https://linux-hardware.org/?probe=10e8c0d4ad) | Jul 23, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [b21b29c46e](https://linux-hardware.org/?probe=b21b29c46e) | Jul 23, 2023 |
| Google        | Snappy                      | Notebook    | [a3e6774e43](https://linux-hardware.org/?probe=a3e6774e43) | Jul 23, 2023 |
| Dell          | 0VD92X A00                  | Desktop     | [675e646d05](https://linux-hardware.org/?probe=675e646d05) | Jul 23, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [467cc30f89](https://linux-hardware.org/?probe=467cc30f89) | Jul 22, 2023 |
| ASRock        | B85M                        | Desktop     | [c4f0b0b1fa](https://linux-hardware.org/?probe=c4f0b0b1fa) | Jul 22, 2023 |
| MSI           | PR601/VR603                 | Notebook    | [b982476d84](https://linux-hardware.org/?probe=b982476d84) | Jul 21, 2023 |
| HP            | 3032h                       | Desktop     | [f6a4202b21](https://linux-hardware.org/?probe=f6a4202b21) | Jul 21, 2023 |
| Gigabyte      | H270-HD3-CF                 | Desktop     | [73a56d2df7](https://linux-hardware.org/?probe=73a56d2df7) | Jul 21, 2023 |
| Razer         | Blade 15 Base Model (Mid... | Notebook    | [d2d53e7406](https://linux-hardware.org/?probe=d2d53e7406) | Jul 21, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [fcdb1fdeed](https://linux-hardware.org/?probe=fcdb1fdeed) | Jul 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [0bd52b9adf](https://linux-hardware.org/?probe=0bd52b9adf) | Jul 20, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [26c19ee81f](https://linux-hardware.org/?probe=26c19ee81f) | Jul 19, 2023 |
| Dell          | Latitude 9420               | Notebook    | [750f80b869](https://linux-hardware.org/?probe=750f80b869) | Jul 19, 2023 |
| Dell          | Latitude 9420               | Notebook    | [a4ba4bfde1](https://linux-hardware.org/?probe=a4ba4bfde1) | Jul 19, 2023 |
| Dell          | Latitude E6400              | Notebook    | [7e9ef12f0d](https://linux-hardware.org/?probe=7e9ef12f0d) | Jul 19, 2023 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | Notebook    | [17c6866da9](https://linux-hardware.org/?probe=17c6866da9) | Jul 18, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [8ff38f3782](https://linux-hardware.org/?probe=8ff38f3782) | Jul 18, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [35d510901b](https://linux-hardware.org/?probe=35d510901b) | Jul 18, 2023 |
| Teclast       | F6 Pro                      | Notebook    | [d9f3a038e0](https://linux-hardware.org/?probe=d9f3a038e0) | Jul 17, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20STS... | Notebook    | [18f41b2be6](https://linux-hardware.org/?probe=18f41b2be6) | Jul 17, 2023 |
| Fujitsu       | D3401-A1 S26361-D3401-A1    | Desktop     | [c527cf56ad](https://linux-hardware.org/?probe=c527cf56ad) | Jul 17, 2023 |
| Lenovo        | ThinkPad X240 20AMS07T00    | Notebook    | [0c460a8007](https://linux-hardware.org/?probe=0c460a8007) | Jul 17, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [f4936b2064](https://linux-hardware.org/?probe=f4936b2064) | Jul 17, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [111c0b962d](https://linux-hardware.org/?probe=111c0b962d) | Jul 16, 2023 |
| Dell          | Latitude E6440              | Notebook    | [4e40dc49f3](https://linux-hardware.org/?probe=4e40dc49f3) | Jul 16, 2023 |
| HP            | Pavilion HDX9200            | Notebook    | [d893c8a2d1](https://linux-hardware.org/?probe=d893c8a2d1) | Jul 16, 2023 |
| Dell          | Latitude E6330              | Notebook    | [6adb67344f](https://linux-hardware.org/?probe=6adb67344f) | Jul 15, 2023 |
| Lenovo        | ThinkPad T495 20NKS0T101    | Notebook    | [6154504eac](https://linux-hardware.org/?probe=6154504eac) | Jul 15, 2023 |
| ASUSTek       | 1011PX                      | Notebook    | [d91fe40195](https://linux-hardware.org/?probe=d91fe40195) | Jul 15, 2023 |
| MSI           | GE70 2QD                    | Notebook    | [f8ddf3a3a3](https://linux-hardware.org/?probe=f8ddf3a3a3) | Jul 15, 2023 |
| Lenovo        | ThinkPad X240 20AMS07T00    | Notebook    | [8ce6db48b9](https://linux-hardware.org/?probe=8ce6db48b9) | Jul 15, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [9e829a5538](https://linux-hardware.org/?probe=9e829a5538) | Jul 14, 2023 |
| Lenovo        | ThinkPad T470 20HES0FA03    | Notebook    | [f416cb06c2](https://linux-hardware.org/?probe=f416cb06c2) | Jul 14, 2023 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [f0736c39fe](https://linux-hardware.org/?probe=f0736c39fe) | Jul 13, 2023 |
| Acer          | Aspire E5-576G              | Notebook    | [0856b48ae7](https://linux-hardware.org/?probe=0856b48ae7) | Jul 13, 2023 |
| Dell          | Latitude E6330              | Notebook    | [58ec0684cd](https://linux-hardware.org/?probe=58ec0684cd) | Jul 13, 2023 |
| Toshiba       | Satellite S75-B             | Notebook    | [ee71e28c8f](https://linux-hardware.org/?probe=ee71e28c8f) | Jul 12, 2023 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [b5374c8055](https://linux-hardware.org/?probe=b5374c8055) | Jul 12, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [67ef58f2b3](https://linux-hardware.org/?probe=67ef58f2b3) | Jul 12, 2023 |
| Lenovo        | ThinkPad T470s 20HGS01A0... | Notebook    | [54e51170a1](https://linux-hardware.org/?probe=54e51170a1) | Jul 11, 2023 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | Notebook    | [a78428eb21](https://linux-hardware.org/?probe=a78428eb21) | Jul 11, 2023 |
| Dell          | Inspiron 5748               | Notebook    | [ec95cc29fd](https://linux-hardware.org/?probe=ec95cc29fd) | Jul 11, 2023 |
| Lenovo        | ThinkPad L470 20J5S01S00    | Notebook    | [ef1f607a84](https://linux-hardware.org/?probe=ef1f607a84) | Jul 11, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [97f39991c3](https://linux-hardware.org/?probe=97f39991c3) | Jul 11, 2023 |
| Dell          | 0T7D40 A01                  | Desktop     | [1ed238ea9b](https://linux-hardware.org/?probe=1ed238ea9b) | Jul 11, 2023 |
| ASRock        | H81M                        | Desktop     | [042e2e3b56](https://linux-hardware.org/?probe=042e2e3b56) | Jul 11, 2023 |
| ASRock        | H81M                        | Desktop     | [c4b398d08c](https://linux-hardware.org/?probe=c4b398d08c) | Jul 11, 2023 |
| HP            | 82B5                        | All in one  | [3f1fecd5c3](https://linux-hardware.org/?probe=3f1fecd5c3) | Jul 11, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [ab32a0e447](https://linux-hardware.org/?probe=ab32a0e447) | Jul 11, 2023 |
| Dell          | Latitude 3190               | Notebook    | [f067ca0dbf](https://linux-hardware.org/?probe=f067ca0dbf) | Jul 11, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [8b9677cc2a](https://linux-hardware.org/?probe=8b9677cc2a) | Jul 10, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [acdd4ea952](https://linux-hardware.org/?probe=acdd4ea952) | Jul 10, 2023 |
| Lenovo        | ThinkPad Edge 0578P6G       | Notebook    | [e79fbdad2d](https://linux-hardware.org/?probe=e79fbdad2d) | Jul 10, 2023 |
| Google        | Guado                       | Desktop     | [d14465ad06](https://linux-hardware.org/?probe=d14465ad06) | Jul 10, 2023 |
| Dell          | 09WH54 A00                  | Desktop     | [b118891f3d](https://linux-hardware.org/?probe=b118891f3d) | Jul 10, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [38420a6afe](https://linux-hardware.org/?probe=38420a6afe) | Jul 10, 2023 |
| MSI           | X99A GAMING 9 ACK           | Desktop     | [4a36d070b4](https://linux-hardware.org/?probe=4a36d070b4) | Jul 10, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [73b13fd5eb](https://linux-hardware.org/?probe=73b13fd5eb) | Jul 10, 2023 |
| HP            | 1998                        | Desktop     | [03da98871c](https://linux-hardware.org/?probe=03da98871c) | Jul 10, 2023 |
| HP            | 1998                        | Desktop     | [15e8251d36](https://linux-hardware.org/?probe=15e8251d36) | Jul 10, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [d4ca6c4f81](https://linux-hardware.org/?probe=d4ca6c4f81) | Jul 10, 2023 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [b91bb21dfc](https://linux-hardware.org/?probe=b91bb21dfc) | Jul 10, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [1e6fc6f253](https://linux-hardware.org/?probe=1e6fc6f253) | Jul 10, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [14c6f3f286](https://linux-hardware.org/?probe=14c6f3f286) | Jul 10, 2023 |
| Gigabyte      | GA-78LMT-S2PT               | Desktop     | [6a55de667a](https://linux-hardware.org/?probe=6a55de667a) | Jul 09, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [215d2135b3](https://linux-hardware.org/?probe=215d2135b3) | Jul 09, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [42aaaa0acb](https://linux-hardware.org/?probe=42aaaa0acb) | Jul 09, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [60e671ef49](https://linux-hardware.org/?probe=60e671ef49) | Jul 09, 2023 |
| ASUSTek       | X555LJ                      | Notebook    | [2dfec77944](https://linux-hardware.org/?probe=2dfec77944) | Jul 09, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [b29db59f6a](https://linux-hardware.org/?probe=b29db59f6a) | Jul 09, 2023 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [92feea0533](https://linux-hardware.org/?probe=92feea0533) | Jul 08, 2023 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [2287c62944](https://linux-hardware.org/?probe=2287c62944) | Jul 08, 2023 |
| Dell          | 0KC9NP A01                  | Desktop     | [570f59305c](https://linux-hardware.org/?probe=570f59305c) | Jul 08, 2023 |
| Dell          | 0KC9NP A01                  | Desktop     | [6d62d0cdbf](https://linux-hardware.org/?probe=6d62d0cdbf) | Jul 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [9b8e16f852](https://linux-hardware.org/?probe=9b8e16f852) | Jul 08, 2023 |
| Toshiba       | PORTEGE M700                | Notebook    | [6a67dec7ab](https://linux-hardware.org/?probe=6a67dec7ab) | Jul 08, 2023 |
| Toshiba       | PORTEGE M700                | Notebook    | [b735ddd9a6](https://linux-hardware.org/?probe=b735ddd9a6) | Jul 08, 2023 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | Notebook    | [54ac55c49e](https://linux-hardware.org/?probe=54ac55c49e) | Jul 07, 2023 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | Notebook    | [296474a1b1](https://linux-hardware.org/?probe=296474a1b1) | Jul 07, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [e4bb31a52c](https://linux-hardware.org/?probe=e4bb31a52c) | Jul 07, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [2d342d7a37](https://linux-hardware.org/?probe=2d342d7a37) | Jul 07, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [49c59b6c86](https://linux-hardware.org/?probe=49c59b6c86) | Jul 07, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [df2a737853](https://linux-hardware.org/?probe=df2a737853) | Jul 07, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [9ecae424ad](https://linux-hardware.org/?probe=9ecae424ad) | Jul 07, 2023 |
| Gigabyte      | B85M-HD3                    | Desktop     | [43034103ef](https://linux-hardware.org/?probe=43034103ef) | Jul 06, 2023 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [54611e82ec](https://linux-hardware.org/?probe=54611e82ec) | Jul 06, 2023 |
| Google        | Guado                       | Desktop     | [8bd38f802a](https://linux-hardware.org/?probe=8bd38f802a) | Jul 06, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [23a6105e01](https://linux-hardware.org/?probe=23a6105e01) | Jul 06, 2023 |
| ASRock        | Z370 Killer SLI             | Desktop     | [b7a676e2fc](https://linux-hardware.org/?probe=b7a676e2fc) | Jul 05, 2023 |
| Dell          | Latitude 7420               | Notebook    | [44c51e8365](https://linux-hardware.org/?probe=44c51e8365) | Jul 05, 2023 |
| AAEON         | AEC-6637                    | Notebook    | [53f8e37edc](https://linux-hardware.org/?probe=53f8e37edc) | Jul 05, 2023 |
| AAEON         | AEC-6637                    | Notebook    | [a105861e1d](https://linux-hardware.org/?probe=a105861e1d) | Jul 05, 2023 |
| Dell          | Latitude 7420               | Notebook    | [9eae2c6ad4](https://linux-hardware.org/?probe=9eae2c6ad4) | Jul 05, 2023 |
| Gigabyte      | B660M DS3H DDR4             | Desktop     | [c997aced4e](https://linux-hardware.org/?probe=c997aced4e) | Jul 05, 2023 |
| Gigabyte      | GA-790FXTA-UD5              | Desktop     | [685f105356](https://linux-hardware.org/?probe=685f105356) | Jul 05, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [3e5dc0c313](https://linux-hardware.org/?probe=3e5dc0c313) | Jul 05, 2023 |
| HP            | 339A                        | Desktop     | [8d051ead1c](https://linux-hardware.org/?probe=8d051ead1c) | Jul 05, 2023 |
| ASRock        | Z370 Killer SLI             | Desktop     | [e7c0ca1bfc](https://linux-hardware.org/?probe=e7c0ca1bfc) | Jul 05, 2023 |
| HP            | 550                         | Notebook    | [f788d05211](https://linux-hardware.org/?probe=f788d05211) | Jul 05, 2023 |
| HP            | 650                         | Notebook    | [a3077996ad](https://linux-hardware.org/?probe=a3077996ad) | Jul 05, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [71ab16d717](https://linux-hardware.org/?probe=71ab16d717) | Jul 05, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [1a32b23618](https://linux-hardware.org/?probe=1a32b23618) | Jul 04, 2023 |
| ASRock        | Z170 Extreme4               | Desktop     | [abc4554a51](https://linux-hardware.org/?probe=abc4554a51) | Jul 04, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS1... | Convertible | [2be3b17236](https://linux-hardware.org/?probe=2be3b17236) | Jul 04, 2023 |
| Dell          | Latitude 3190               | Notebook    | [b895b6dced](https://linux-hardware.org/?probe=b895b6dced) | Jul 04, 2023 |
| ASRock        | A320M-HDV R3.0              | Desktop     | [df1fff149d](https://linux-hardware.org/?probe=df1fff149d) | Jul 04, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [22a13c2e16](https://linux-hardware.org/?probe=22a13c2e16) | Jul 03, 2023 |
| Lenovo        | Yoga 900-13ISK 80MK         | Notebook    | [75a8750d34](https://linux-hardware.org/?probe=75a8750d34) | Jul 03, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [f567c6c550](https://linux-hardware.org/?probe=f567c6c550) | Jul 03, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [8bb4af1cb5](https://linux-hardware.org/?probe=8bb4af1cb5) | Jul 03, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [67281face4](https://linux-hardware.org/?probe=67281face4) | Jul 03, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [f928781025](https://linux-hardware.org/?probe=f928781025) | Jul 03, 2023 |
| Acer          | FX58M                       | Desktop     | [44e563ac2a](https://linux-hardware.org/?probe=44e563ac2a) | Jul 02, 2023 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [6e52890194](https://linux-hardware.org/?probe=6e52890194) | Jul 02, 2023 |
| MSI           | MS-B9181                    | Desktop     | [fef890b931](https://linux-hardware.org/?probe=fef890b931) | Jul 02, 2023 |
| Google        | Relm                        | Notebook    | [ef72648bb6](https://linux-hardware.org/?probe=ef72648bb6) | Jul 02, 2023 |
| MSI           | MS-B9181                    | Desktop     | [47b3ce0c58](https://linux-hardware.org/?probe=47b3ce0c58) | Jul 02, 2023 |
| Acer          | FX58M                       | Desktop     | [69f3a5d4fb](https://linux-hardware.org/?probe=69f3a5d4fb) | Jul 02, 2023 |
| Gigabyte      | P55M-UD2                    | Desktop     | [babec703df](https://linux-hardware.org/?probe=babec703df) | Jul 02, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [03879163c2](https://linux-hardware.org/?probe=03879163c2) | Jul 02, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [9e65cd9bd1](https://linux-hardware.org/?probe=9e65cd9bd1) | Jul 02, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [3f2c5d0eb2](https://linux-hardware.org/?probe=3f2c5d0eb2) | Jul 01, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [f923d36676](https://linux-hardware.org/?probe=f923d36676) | Jul 01, 2023 |
| Dell          | Inspiron 7720               | Notebook    | [9d8f40247e](https://linux-hardware.org/?probe=9d8f40247e) | Jul 01, 2023 |
| Packard Be... | EasyNote TSX66HR            | Notebook    | [96253a3da8](https://linux-hardware.org/?probe=96253a3da8) | Jul 01, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [eea1d9623c](https://linux-hardware.org/?probe=eea1d9623c) | Jun 30, 2023 |
| HP            | EliteBook 820 G2            | Notebook    | [c99236ef84](https://linux-hardware.org/?probe=c99236ef84) | Jun 30, 2023 |
| Lenovo        | ThinkPad T430s 23554L7      | Notebook    | [501b0860c8](https://linux-hardware.org/?probe=501b0860c8) | Jun 30, 2023 |
| Dell          | Latitude E6540              | Notebook    | [a526c901ee](https://linux-hardware.org/?probe=a526c901ee) | Jun 30, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [287d7d6f60](https://linux-hardware.org/?probe=287d7d6f60) | Jun 29, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [723de914e2](https://linux-hardware.org/?probe=723de914e2) | Jun 29, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [363067c171](https://linux-hardware.org/?probe=363067c171) | Jun 29, 2023 |
| Medion        | BTDD-TI                     | All in one  | [64b84cf34d](https://linux-hardware.org/?probe=64b84cf34d) | Jun 29, 2023 |
| Gigabyte      | P31-DS3L                    | Desktop     | [0d32728bdf](https://linux-hardware.org/?probe=0d32728bdf) | Jun 28, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [34df27504f](https://linux-hardware.org/?probe=34df27504f) | Jun 28, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [5a82f91882](https://linux-hardware.org/?probe=5a82f91882) | Jun 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | Notebook    | [9d6748ef56](https://linux-hardware.org/?probe=9d6748ef56) | Jun 28, 2023 |
| Toshiba       | TECRA R950                  | Notebook    | [cab34ec3dc](https://linux-hardware.org/?probe=cab34ec3dc) | Jun 28, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [ff919014cd](https://linux-hardware.org/?probe=ff919014cd) | Jun 28, 2023 |
| HP            | 21B4 A01                    | Desktop     | [50656fb7ec](https://linux-hardware.org/?probe=50656fb7ec) | Jun 28, 2023 |
| HP            | 21B4 A01                    | Desktop     | [4d9322819d](https://linux-hardware.org/?probe=4d9322819d) | Jun 28, 2023 |
| ASUSTek       | K54C                        | Notebook    | [4152d1fcff](https://linux-hardware.org/?probe=4152d1fcff) | Jun 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | Notebook    | [64433a8783](https://linux-hardware.org/?probe=64433a8783) | Jun 27, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [1aa332e26f](https://linux-hardware.org/?probe=1aa332e26f) | Jun 27, 2023 |
| Valve         | Jupiter                     | Notebook    | [0817dd25ff](https://linux-hardware.org/?probe=0817dd25ff) | Jun 27, 2023 |
| Dell          | Latitude 3190               | Notebook    | [5f68b5235f](https://linux-hardware.org/?probe=5f68b5235f) | Jun 27, 2023 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [157d424ec0](https://linux-hardware.org/?probe=157d424ec0) | Jun 26, 2023 |
| Toshiba       | TECRA R950                  | Notebook    | [f02bb9a43a](https://linux-hardware.org/?probe=f02bb9a43a) | Jun 26, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [b4fcf1904c](https://linux-hardware.org/?probe=b4fcf1904c) | Jun 26, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [e55023fb8b](https://linux-hardware.org/?probe=e55023fb8b) | Jun 26, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [0b72aec1b9](https://linux-hardware.org/?probe=0b72aec1b9) | Jun 26, 2023 |
| HP            | 255 G5 Notebook PC          | Notebook    | [cad891675f](https://linux-hardware.org/?probe=cad891675f) | Jun 25, 2023 |
| HP            | 21B4 A01                    | Desktop     | [e277fd2772](https://linux-hardware.org/?probe=e277fd2772) | Jun 25, 2023 |
| Biostar       | H81MHV3 5.0                 | Desktop     | [0f95f72b43](https://linux-hardware.org/?probe=0f95f72b43) | Jun 25, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [3c54b7ee02](https://linux-hardware.org/?probe=3c54b7ee02) | Jun 25, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [b4ab698b09](https://linux-hardware.org/?probe=b4ab698b09) | Jun 25, 2023 |
| eMachines     | eME732ZG                    | Notebook    | [4e1d6873ff](https://linux-hardware.org/?probe=4e1d6873ff) | Jun 24, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [0ec7fedf29](https://linux-hardware.org/?probe=0ec7fedf29) | Jun 24, 2023 |
| Packard Be... | EasyNote TK85               | Notebook    | [314e344780](https://linux-hardware.org/?probe=314e344780) | Jun 24, 2023 |
| Intel         | H81                         | Desktop     | [65ad18a4bd](https://linux-hardware.org/?probe=65ad18a4bd) | Jun 24, 2023 |
| Lenovo        | ThinkPad T430 2347BS4       | Notebook    | [a8a9689ea6](https://linux-hardware.org/?probe=a8a9689ea6) | Jun 24, 2023 |
| Lenovo        | ThinkPad L390 20NSS04400    | Notebook    | [feced26491](https://linux-hardware.org/?probe=feced26491) | Jun 23, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [c75670186a](https://linux-hardware.org/?probe=c75670186a) | Jun 23, 2023 |
| MSI           | B360M PRO-VD 2019-01-24     | Desktop     | [a036f44a4c](https://linux-hardware.org/?probe=a036f44a4c) | Jun 22, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [17db397c48](https://linux-hardware.org/?probe=17db397c48) | Jun 22, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [0b8cf1cae7](https://linux-hardware.org/?probe=0b8cf1cae7) | Jun 22, 2023 |
| Medion        | BTDD-TI                     | All in one  | [8845f67824](https://linux-hardware.org/?probe=8845f67824) | Jun 22, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [d4d7534ac3](https://linux-hardware.org/?probe=d4d7534ac3) | Jun 22, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [0f5435c665](https://linux-hardware.org/?probe=0f5435c665) | Jun 22, 2023 |
| Toshiba       | Satellite Pro C70-B         | Notebook    | [f96a1a3552](https://linux-hardware.org/?probe=f96a1a3552) | Jun 21, 2023 |
| Lenovo        | ThinkPad L470 20J5S01S00    | Notebook    | [5de086be7a](https://linux-hardware.org/?probe=5de086be7a) | Jun 21, 2023 |
| Toshiba       | Satellite Pro C70-B         | Notebook    | [52c4c32098](https://linux-hardware.org/?probe=52c4c32098) | Jun 21, 2023 |
| Notebook      | NV4xPZ                      | Notebook    | [873c70b184](https://linux-hardware.org/?probe=873c70b184) | Jun 21, 2023 |
| Gigabyte      | H510M S2H V2                | Desktop     | [d7c44291c1](https://linux-hardware.org/?probe=d7c44291c1) | Jun 20, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [bbfb6ff07f](https://linux-hardware.org/?probe=bbfb6ff07f) | Jun 20, 2023 |
| Lenovo        | B570 HuronRiver Platform    | Notebook    | [b51dda105a](https://linux-hardware.org/?probe=b51dda105a) | Jun 20, 2023 |
| Gigabyte      | H510M S2H V2                | Desktop     | [f2d80b2558](https://linux-hardware.org/?probe=f2d80b2558) | Jun 19, 2023 |
| Toshiba       | Satellite A300              | Notebook    | [f37d67a18d](https://linux-hardware.org/?probe=f37d67a18d) | Jun 19, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [1559b0a68d](https://linux-hardware.org/?probe=1559b0a68d) | Jun 19, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [22d8476417](https://linux-hardware.org/?probe=22d8476417) | Jun 19, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [e2fc6bb607](https://linux-hardware.org/?probe=e2fc6bb607) | Jun 19, 2023 |
| Razer         | Blade Stealth 13 (Early ... | Notebook    | [e3843be450](https://linux-hardware.org/?probe=e3843be450) | Jun 18, 2023 |
| ASRock        | Z87 Extreme4                | Desktop     | [dcd3e79cb1](https://linux-hardware.org/?probe=dcd3e79cb1) | Jun 18, 2023 |
| HP            | Pavilion dv2                | Notebook    | [3f3b0104a4](https://linux-hardware.org/?probe=3f3b0104a4) | Jun 18, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [17c61c0aee](https://linux-hardware.org/?probe=17c61c0aee) | Jun 18, 2023 |
| Gigabyte      | Z170-Gaming K3-CF           | Desktop     | [6e40a39112](https://linux-hardware.org/?probe=6e40a39112) | Jun 18, 2023 |
| HP            | Notebook                    | Notebook    | [60eebb0602](https://linux-hardware.org/?probe=60eebb0602) | Jun 18, 2023 |
| HP            | Pavilion x2 Detachable      | Tablet      | [e01ed6ab42](https://linux-hardware.org/?probe=e01ed6ab42) | Jun 17, 2023 |
| Dell          | Latitude 5420               | Notebook    | [f7c9224ef1](https://linux-hardware.org/?probe=f7c9224ef1) | Jun 17, 2023 |
| Dell          | Latitude 5420               | Notebook    | [f553a4e5e7](https://linux-hardware.org/?probe=f553a4e5e7) | Jun 17, 2023 |
| Dell          | Latitude 9420               | Convertible | [c60ca4bcc4](https://linux-hardware.org/?probe=c60ca4bcc4) | Jun 17, 2023 |
| Dell          | Latitude 9420               | Convertible | [444f324394](https://linux-hardware.org/?probe=444f324394) | Jun 16, 2023 |
| MSI           | B85-G43 GAMING              | Desktop     | [93da970965](https://linux-hardware.org/?probe=93da970965) | Jun 16, 2023 |
| ASRock        | H61M-VG3                    | Desktop     | [858be00df4](https://linux-hardware.org/?probe=858be00df4) | Jun 16, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [0d47dc3760](https://linux-hardware.org/?probe=0d47dc3760) | Jun 16, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [dc48180bc7](https://linux-hardware.org/?probe=dc48180bc7) | Jun 16, 2023 |
| STONE COMP... | NOTCHA-286                  | Notebook    | [9536ebc16b](https://linux-hardware.org/?probe=9536ebc16b) | Jun 16, 2023 |
| Dell          | Latitude E6400              | Notebook    | [7c59595887](https://linux-hardware.org/?probe=7c59595887) | Jun 16, 2023 |
| STONE COMP... | NOTCHA-286                  | Notebook    | [00a14ade70](https://linux-hardware.org/?probe=00a14ade70) | Jun 16, 2023 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [558c031517](https://linux-hardware.org/?probe=558c031517) | Jun 16, 2023 |
| Valve         | Jupiter                     | Notebook    | [29869b2464](https://linux-hardware.org/?probe=29869b2464) | Jun 15, 2023 |
| Valve         | Jupiter                     | Notebook    | [bdd96d41a7](https://linux-hardware.org/?probe=bdd96d41a7) | Jun 15, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [a1c36c44b1](https://linux-hardware.org/?probe=a1c36c44b1) | Jun 15, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [8d88084588](https://linux-hardware.org/?probe=8d88084588) | Jun 15, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [16ad11571a](https://linux-hardware.org/?probe=16ad11571a) | Jun 15, 2023 |
| Lenovo        | ThinkPad T490 20N20032US    | Notebook    | [3df7663e0d](https://linux-hardware.org/?probe=3df7663e0d) | Jun 15, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [c612df2e8c](https://linux-hardware.org/?probe=c612df2e8c) | Jun 15, 2023 |
| ASUSTek       | K52N                        | Notebook    | [eb2ec7cb3d](https://linux-hardware.org/?probe=eb2ec7cb3d) | Jun 15, 2023 |
| ASRock        | B85M                        | Desktop     | [19f8b16937](https://linux-hardware.org/?probe=19f8b16937) | Jun 15, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [8a04ec65f7](https://linux-hardware.org/?probe=8a04ec65f7) | Jun 15, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [7670492b40](https://linux-hardware.org/?probe=7670492b40) | Jun 15, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [dbe7676807](https://linux-hardware.org/?probe=dbe7676807) | Jun 15, 2023 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [7ae654d4e2](https://linux-hardware.org/?probe=7ae654d4e2) | Jun 14, 2023 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [39e2711f1f](https://linux-hardware.org/?probe=39e2711f1f) | Jun 13, 2023 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [2ae3c4aaca](https://linux-hardware.org/?probe=2ae3c4aaca) | Jun 13, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [ad01f2c38d](https://linux-hardware.org/?probe=ad01f2c38d) | Jun 13, 2023 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [1361d3551c](https://linux-hardware.org/?probe=1361d3551c) | Jun 12, 2023 |
| Xunlong       | Orange Pi PC                | Soc         | [2a93adb1f0](https://linux-hardware.org/?probe=2a93adb1f0) | Jun 12, 2023 |
| Dell          | 0TKM9Y A00                  | Mini pc     | [1fad9d3d52](https://linux-hardware.org/?probe=1fad9d3d52) | Jun 12, 2023 |
| Dell          | Latitude 3190               | Notebook    | [2c8d7ef5b6](https://linux-hardware.org/?probe=2c8d7ef5b6) | Jun 12, 2023 |
| MSI           | GE62 6QC                    | Notebook    | [5581a5c589](https://linux-hardware.org/?probe=5581a5c589) | Jun 12, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [2ea9fd5a4a](https://linux-hardware.org/?probe=2ea9fd5a4a) | Jun 12, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [273795ce3d](https://linux-hardware.org/?probe=273795ce3d) | Jun 12, 2023 |
| Google        | Blorb                       | Notebook    | [0083999b8a](https://linux-hardware.org/?probe=0083999b8a) | Jun 12, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [8a9a32ba11](https://linux-hardware.org/?probe=8a9a32ba11) | Jun 12, 2023 |
| Google        | Blorb                       | Notebook    | [516c0548dc](https://linux-hardware.org/?probe=516c0548dc) | Jun 12, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [de08f65c4d](https://linux-hardware.org/?probe=de08f65c4d) | Jun 11, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [b88dfc7e5c](https://linux-hardware.org/?probe=b88dfc7e5c) | Jun 11, 2023 |
| HP            | 3397                        | Desktop     | [9f71c4173c](https://linux-hardware.org/?probe=9f71c4173c) | Jun 11, 2023 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [67867c022f](https://linux-hardware.org/?probe=67867c022f) | Jun 11, 2023 |
| Dell          | Precision 5520              | Notebook    | [bcbd324c4b](https://linux-hardware.org/?probe=bcbd324c4b) | Jun 11, 2023 |
| Dell          | Precision 5520              | Notebook    | [ab408edcbd](https://linux-hardware.org/?probe=ab408edcbd) | Jun 11, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [d6681f05ec](https://linux-hardware.org/?probe=d6681f05ec) | Jun 11, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [0e257c3bd8](https://linux-hardware.org/?probe=0e257c3bd8) | Jun 11, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [bfde2cf63d](https://linux-hardware.org/?probe=bfde2cf63d) | Jun 10, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [7c79725474](https://linux-hardware.org/?probe=7c79725474) | Jun 10, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [5e060b53c2](https://linux-hardware.org/?probe=5e060b53c2) | Jun 10, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [0d548e314b](https://linux-hardware.org/?probe=0d548e314b) | Jun 10, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [2627421665](https://linux-hardware.org/?probe=2627421665) | Jun 09, 2023 |
| HP            | Stream Laptop 14-ds0xxx     | Notebook    | [fb9e2f9fc8](https://linux-hardware.org/?probe=fb9e2f9fc8) | Jun 09, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [92fd36b27a](https://linux-hardware.org/?probe=92fd36b27a) | Jun 09, 2023 |
| Panasonic     | CF-53ASCZGFG                | Notebook    | [39e04925ee](https://linux-hardware.org/?probe=39e04925ee) | Jun 08, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [5d8df77ade](https://linux-hardware.org/?probe=5d8df77ade) | Jun 08, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [c98ac6e82c](https://linux-hardware.org/?probe=c98ac6e82c) | Jun 08, 2023 |
| MSI           | Z87-G43                     | Desktop     | [554f8ea405](https://linux-hardware.org/?probe=554f8ea405) | Jun 08, 2023 |
| ASRock        | H81M-VG4                    | Desktop     | [04d84e44a5](https://linux-hardware.org/?probe=04d84e44a5) | Jun 08, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [7879db73f8](https://linux-hardware.org/?probe=7879db73f8) | Jun 08, 2023 |
| Unknown       | Unknown                     | Soc         | [b23e0f6e09](https://linux-hardware.org/?probe=b23e0f6e09) | Jun 08, 2023 |
| Fujitsu       | CELSIUS H730                | Notebook    | [a1e397f4a7](https://linux-hardware.org/?probe=a1e397f4a7) | Jun 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [c142d83ce5](https://linux-hardware.org/?probe=c142d83ce5) | Jun 07, 2023 |
| Gigabyte      | B250-FinTech-CF             | Desktop     | [022138ad16](https://linux-hardware.org/?probe=022138ad16) | Jun 06, 2023 |
| Toshiba       | Satellite L40               | Notebook    | [16c5f74991](https://linux-hardware.org/?probe=16c5f74991) | Jun 06, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [e56988bf8e](https://linux-hardware.org/?probe=e56988bf8e) | Jun 06, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [50304f8088](https://linux-hardware.org/?probe=50304f8088) | Jun 06, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [fc49284b9f](https://linux-hardware.org/?probe=fc49284b9f) | Jun 06, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [1df787c227](https://linux-hardware.org/?probe=1df787c227) | Jun 05, 2023 |
| Gigabyte      | B250-FinTech-CF             | Desktop     | [e22c496628](https://linux-hardware.org/?probe=e22c496628) | Jun 05, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [83982c1aa9](https://linux-hardware.org/?probe=83982c1aa9) | Jun 05, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [38882f47af](https://linux-hardware.org/?probe=38882f47af) | Jun 05, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [72eb9f0d86](https://linux-hardware.org/?probe=72eb9f0d86) | Jun 05, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [580ae6529e](https://linux-hardware.org/?probe=580ae6529e) | Jun 05, 2023 |
| Dell          | Latitude 3190               | Notebook    | [fa8eba55f0](https://linux-hardware.org/?probe=fa8eba55f0) | Jun 05, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [969354604a](https://linux-hardware.org/?probe=969354604a) | Jun 04, 2023 |
| HP            | 21B4 A01                    | Desktop     | [5d394c52ed](https://linux-hardware.org/?probe=5d394c52ed) | Jun 04, 2023 |
| ASUSTek       | P5G41T-M                    | Desktop     | [8706eff580](https://linux-hardware.org/?probe=8706eff580) | Jun 04, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [7af9263ba9](https://linux-hardware.org/?probe=7af9263ba9) | Jun 04, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [ae24cbf98d](https://linux-hardware.org/?probe=ae24cbf98d) | Jun 04, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [514b3788ed](https://linux-hardware.org/?probe=514b3788ed) | Jun 04, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [e3770a95f6](https://linux-hardware.org/?probe=e3770a95f6) | Jun 04, 2023 |
| Dell          | Latitude D620               | Notebook    | [0e1b7f4320](https://linux-hardware.org/?probe=0e1b7f4320) | Jun 03, 2023 |
| Acer          | Aspire A114-31              | Notebook    | [7a760e7ad6](https://linux-hardware.org/?probe=7a760e7ad6) | Jun 03, 2023 |
| Lenovo        | ThinkPad L490 20Q5002DMH    | Notebook    | [6d42b7647b](https://linux-hardware.org/?probe=6d42b7647b) | Jun 02, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [fa4bd41f4b](https://linux-hardware.org/?probe=fa4bd41f4b) | Jun 02, 2023 |
| ASUSTek       | P8H61                       | Desktop     | [7e9f999121](https://linux-hardware.org/?probe=7e9f999121) | Jun 02, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [1a4437e831](https://linux-hardware.org/?probe=1a4437e831) | Jun 02, 2023 |
| Lenovo        | B50-70 20384                | Notebook    | [5e3a2796a9](https://linux-hardware.org/?probe=5e3a2796a9) | Jun 01, 2023 |
| HP            | EliteBook 820 G2            | Notebook    | [c9409c532d](https://linux-hardware.org/?probe=c9409c532d) | Jun 01, 2023 |
| Toshiba       | Satellite L650              | Notebook    | [63eb6978fa](https://linux-hardware.org/?probe=63eb6978fa) | Jun 01, 2023 |
| HP            | 845A                        | Desktop     | [b68054952b](https://linux-hardware.org/?probe=b68054952b) | Jun 01, 2023 |
| Supermicro    | X8DTU                       | Server      | [2e1d03c7da](https://linux-hardware.org/?probe=2e1d03c7da) | Jun 01, 2023 |
| Lenovo        | B51-80 80LM                 | Notebook    | [69429cb044](https://linux-hardware.org/?probe=69429cb044) | Jun 01, 2023 |
| Unknown       | Unknown                     | Phone       | [bd6f4745f0](https://linux-hardware.org/?probe=bd6f4745f0) | Jun 01, 2023 |
| HP            | 82B5                        | All in one  | [77ecbfa91c](https://linux-hardware.org/?probe=77ecbfa91c) | Jun 01, 2023 |
| ASUSTek       | Z97-P                       | Desktop     | [b819db60d1](https://linux-hardware.org/?probe=b819db60d1) | Jun 01, 2023 |
| Intel         | DB75EN AAG39650-302         | Desktop     | [9872e0cb5c](https://linux-hardware.org/?probe=9872e0cb5c) | May 31, 2023 |
| Inventec      | 0PY33N A01                  | Mini pc     | [01452a68b3](https://linux-hardware.org/?probe=01452a68b3) | May 31, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [46ccbd2d62](https://linux-hardware.org/?probe=46ccbd2d62) | May 31, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [b90cb27f97](https://linux-hardware.org/?probe=b90cb27f97) | May 31, 2023 |
| Gigabyte      | B250-FinTech-CF             | Desktop     | [1903d991a3](https://linux-hardware.org/?probe=1903d991a3) | May 30, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [7fed965224](https://linux-hardware.org/?probe=7fed965224) | May 30, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [3b186c07a2](https://linux-hardware.org/?probe=3b186c07a2) | May 30, 2023 |
| Dell          | 02N3WF A01                  | Desktop     | [c02695ea7d](https://linux-hardware.org/?probe=c02695ea7d) | May 30, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [1df34e179b](https://linux-hardware.org/?probe=1df34e179b) | May 30, 2023 |
| Dell          | 040DDP A01                  | Desktop     | [bce6b61241](https://linux-hardware.org/?probe=bce6b61241) | May 29, 2023 |
| Dell          | Latitude 3190               | Notebook    | [fe4a8422c8](https://linux-hardware.org/?probe=fe4a8422c8) | May 29, 2023 |
| ASRock        | H110M-DVS R3.0              | Desktop     | [505b123692](https://linux-hardware.org/?probe=505b123692) | May 29, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [ca1cea162c](https://linux-hardware.org/?probe=ca1cea162c) | May 29, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [edfe02a7ae](https://linux-hardware.org/?probe=edfe02a7ae) | May 29, 2023 |
| Lenovo        | MIIX 300-10IBY 80NR         | Tablet      | [92b569d076](https://linux-hardware.org/?probe=92b569d076) | May 28, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [4d002c31be](https://linux-hardware.org/?probe=4d002c31be) | May 28, 2023 |
| Dell          | Latitude 7480               | Notebook    | [9eb2396796](https://linux-hardware.org/?probe=9eb2396796) | May 28, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [c51af54d34](https://linux-hardware.org/?probe=c51af54d34) | May 28, 2023 |
| Gateway       | DT55                        | Desktop     | [22d84550c6](https://linux-hardware.org/?probe=22d84550c6) | May 28, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [c2408a1885](https://linux-hardware.org/?probe=c2408a1885) | May 28, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [d06e7ba405](https://linux-hardware.org/?probe=d06e7ba405) | May 28, 2023 |
| HP            | Pavilion x2 Detachable      | Tablet      | [9099d721d2](https://linux-hardware.org/?probe=9099d721d2) | May 27, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [8311d009bd](https://linux-hardware.org/?probe=8311d009bd) | May 27, 2023 |
| Lenovo        | ThinkPad T470 20HES0FA03    | Notebook    | [c8c8087ee8](https://linux-hardware.org/?probe=c8c8087ee8) | May 27, 2023 |
| ASRock        | H81M-VG4                    | Desktop     | [4e7b273239](https://linux-hardware.org/?probe=4e7b273239) | May 27, 2023 |
| ASUSTek       | X555LN                      | Notebook    | [8f16767017](https://linux-hardware.org/?probe=8f16767017) | May 26, 2023 |
| ASUSTek       | A8N-E                       | Desktop     | [2baf5b889b](https://linux-hardware.org/?probe=2baf5b889b) | May 26, 2023 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [a7fbdc21bc](https://linux-hardware.org/?probe=a7fbdc21bc) | May 26, 2023 |
| Dell          | Latitude E5440              | Notebook    | [4a5501c365](https://linux-hardware.org/?probe=4a5501c365) | May 26, 2023 |
| Notebook      | NV4xPZ                      | Notebook    | [750cb90d83](https://linux-hardware.org/?probe=750cb90d83) | May 26, 2023 |
| Acer          | WG43M                       | Desktop     | [9afcfc4a44](https://linux-hardware.org/?probe=9afcfc4a44) | May 26, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [53db1863ab](https://linux-hardware.org/?probe=53db1863ab) | May 25, 2023 |
| ASUSTek       | GL552VW                     | Notebook    | [0466edde83](https://linux-hardware.org/?probe=0466edde83) | May 25, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [d72352c0dc](https://linux-hardware.org/?probe=d72352c0dc) | May 25, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [654aa3909f](https://linux-hardware.org/?probe=654aa3909f) | May 24, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [06333c9c97](https://linux-hardware.org/?probe=06333c9c97) | May 24, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [dd15a8197e](https://linux-hardware.org/?probe=dd15a8197e) | May 24, 2023 |
| Acer          | Aspire E5-571G              | Notebook    | [6531b22151](https://linux-hardware.org/?probe=6531b22151) | May 24, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [ba72bf9d52](https://linux-hardware.org/?probe=ba72bf9d52) | May 24, 2023 |
| Google        | Snappy                      | Notebook    | [8e9ad9e9d3](https://linux-hardware.org/?probe=8e9ad9e9d3) | May 24, 2023 |
| Lenovo        | Unknown                     | Notebook    | [e7148e7a18](https://linux-hardware.org/?probe=e7148e7a18) | May 23, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B3402FEA... | Convertible | [b5e28ef2ab](https://linux-hardware.org/?probe=b5e28ef2ab) | May 23, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [7b6c90320b](https://linux-hardware.org/?probe=7b6c90320b) | May 23, 2023 |
| Gigabyte      | B250-FinTech-CF             | Desktop     | [d8d33293ef](https://linux-hardware.org/?probe=d8d33293ef) | May 23, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [e4f2e7ecb6](https://linux-hardware.org/?probe=e4f2e7ecb6) | May 23, 2023 |
| HP            | 530                         | Notebook    | [70600de142](https://linux-hardware.org/?probe=70600de142) | May 23, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [b7fbda70d3](https://linux-hardware.org/?probe=b7fbda70d3) | May 23, 2023 |
| ASUSTek       | PRIME B760M-A D4            | Desktop     | [6ba02717d9](https://linux-hardware.org/?probe=6ba02717d9) | May 22, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [74a0ea4304](https://linux-hardware.org/?probe=74a0ea4304) | May 22, 2023 |
| MSI           | B360M PRO-VDH               | Desktop     | [93a41eca5e](https://linux-hardware.org/?probe=93a41eca5e) | May 22, 2023 |
| Dell          | Latitude 3190               | Notebook    | [adf9fc9bdb](https://linux-hardware.org/?probe=adf9fc9bdb) | May 22, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [46de86898c](https://linux-hardware.org/?probe=46de86898c) | May 22, 2023 |
| Medion        | BTDD-TI                     | All in one  | [ef28026334](https://linux-hardware.org/?probe=ef28026334) | May 22, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [e7af79968d](https://linux-hardware.org/?probe=e7af79968d) | May 22, 2023 |
| ASUSTek       | K84L                        | Notebook    | [5f14f3b293](https://linux-hardware.org/?probe=5f14f3b293) | May 21, 2023 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [b160fbf41e](https://linux-hardware.org/?probe=b160fbf41e) | May 21, 2023 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [cc90a5ca05](https://linux-hardware.org/?probe=cc90a5ca05) | May 21, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [03b17bc271](https://linux-hardware.org/?probe=03b17bc271) | May 21, 2023 |
| HP            | Unknown                     | Notebook    | [8894bf0f31](https://linux-hardware.org/?probe=8894bf0f31) | May 21, 2023 |
| Gigabyte      | GA-78LMT-S2PT               | Desktop     | [04ea462ce6](https://linux-hardware.org/?probe=04ea462ce6) | May 21, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [2e68f6cae7](https://linux-hardware.org/?probe=2e68f6cae7) | May 21, 2023 |
| Lenovo        | MIIX 300-10IBY 80NR         | Tablet      | [f7d7036598](https://linux-hardware.org/?probe=f7d7036598) | May 21, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [72adb50172](https://linux-hardware.org/?probe=72adb50172) | May 20, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [50e85498e7](https://linux-hardware.org/?probe=50e85498e7) | May 20, 2023 |
| Valve         | Jupiter                     | Notebook    | [cf5c419d13](https://linux-hardware.org/?probe=cf5c419d13) | May 20, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [87e60904b9](https://linux-hardware.org/?probe=87e60904b9) | May 20, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [fc125408b5](https://linux-hardware.org/?probe=fc125408b5) | May 20, 2023 |
| Dell          | 0F3KHR A01                  | Desktop     | [c48ab194c6](https://linux-hardware.org/?probe=c48ab194c6) | May 20, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [5acf485cbf](https://linux-hardware.org/?probe=5acf485cbf) | May 20, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [5a0f8e19ee](https://linux-hardware.org/?probe=5a0f8e19ee) | May 19, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [8c6b9dc52f](https://linux-hardware.org/?probe=8c6b9dc52f) | May 19, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [db9774a799](https://linux-hardware.org/?probe=db9774a799) | May 19, 2023 |
| Gigabyte      | F2A88X-D3H                  | Desktop     | [76bae0c7fb](https://linux-hardware.org/?probe=76bae0c7fb) | May 19, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | Notebook    | [26e8deafbf](https://linux-hardware.org/?probe=26e8deafbf) | May 19, 2023 |
| Intel         | NUC12WSBi7 M46422-304       | Mini pc     | [b63f2ef351](https://linux-hardware.org/?probe=b63f2ef351) | May 18, 2023 |
| Medion        | BTDD-TI                     | All in one  | [cc45e1f2f4](https://linux-hardware.org/?probe=cc45e1f2f4) | May 18, 2023 |
| MSI           | GL75 9SE                    | Notebook    | [7fd4d531c9](https://linux-hardware.org/?probe=7fd4d531c9) | May 18, 2023 |
| ASUSTek       | PRIME Z790-P                | Desktop     | [99d6173179](https://linux-hardware.org/?probe=99d6173179) | May 18, 2023 |
| Dell          | 0GDG8Y A00                  | Desktop     | [bc0a4ba851](https://linux-hardware.org/?probe=bc0a4ba851) | May 18, 2023 |
| Lenovo        | 1030 SDK0J40697 WIN 3305... | Desktop     | [af1e17cc95](https://linux-hardware.org/?probe=af1e17cc95) | May 17, 2023 |
| ASUSTek       | P5G41T-M                    | Desktop     | [89d938fcef](https://linux-hardware.org/?probe=89d938fcef) | May 17, 2023 |
| HP            | EliteBook 820 G2            | Notebook    | [200610da74](https://linux-hardware.org/?probe=200610da74) | May 17, 2023 |
| Google        | Snappy                      | Notebook    | [d13d8adaf4](https://linux-hardware.org/?probe=d13d8adaf4) | May 17, 2023 |
| Intel         | DB75EN AAG39650-302         | Desktop     | [2f6a330442](https://linux-hardware.org/?probe=2f6a330442) | May 17, 2023 |
| Google        | Snappy                      | Notebook    | [0c095bb37a](https://linux-hardware.org/?probe=0c095bb37a) | May 17, 2023 |
| Pegatron      | VIOLET                      | Desktop     | [197ec890d6](https://linux-hardware.org/?probe=197ec890d6) | May 16, 2023 |
| Pegatron      | VIOLET                      | Desktop     | [fa6dc417d4](https://linux-hardware.org/?probe=fa6dc417d4) | May 16, 2023 |
| Foxconn       | P35A01                      | Desktop     | [d3f10a59ba](https://linux-hardware.org/?probe=d3f10a59ba) | May 16, 2023 |
| Intel         | DB75EN AAG39650-302         | Desktop     | [db27da6896](https://linux-hardware.org/?probe=db27da6896) | May 15, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [d4ad39c5d7](https://linux-hardware.org/?probe=d4ad39c5d7) | May 15, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [4a352d010e](https://linux-hardware.org/?probe=4a352d010e) | May 15, 2023 |
| Dell          | Latitude 3190               | Notebook    | [1d867407a6](https://linux-hardware.org/?probe=1d867407a6) | May 15, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [0aa84055bf](https://linux-hardware.org/?probe=0aa84055bf) | May 15, 2023 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [3466945196](https://linux-hardware.org/?probe=3466945196) | May 15, 2023 |
| HP            | 339A                        | Desktop     | [35fdefb4eb](https://linux-hardware.org/?probe=35fdefb4eb) | May 15, 2023 |
| Lenovo        | B590 20206                  | Notebook    | [70b604bc30](https://linux-hardware.org/?probe=70b604bc30) | May 14, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [5f508efff4](https://linux-hardware.org/?probe=5f508efff4) | May 14, 2023 |
| Lenovo        | B50-70 20384                | Notebook    | [1d3db7b456](https://linux-hardware.org/?probe=1d3db7b456) | May 14, 2023 |
| Fujitsu       | CELSIUS H760                | Notebook    | [5e6faf68dd](https://linux-hardware.org/?probe=5e6faf68dd) | May 14, 2023 |
| Lenovo        | B50-70 20384                | Notebook    | [9459f4eae8](https://linux-hardware.org/?probe=9459f4eae8) | May 14, 2023 |
| Lenovo        | ThinkCentre M58 7627AD5     | Desktop     | [e0b4de3daf](https://linux-hardware.org/?probe=e0b4de3daf) | May 14, 2023 |
| Fujitsu       | LIFEBOOK S752               | Notebook    | [97e9f91d90](https://linux-hardware.org/?probe=97e9f91d90) | May 14, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [660bd404a0](https://linux-hardware.org/?probe=660bd404a0) | May 14, 2023 |
| ASUSTek       | K53BR                       | Notebook    | [96a60a2970](https://linux-hardware.org/?probe=96a60a2970) | May 14, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [091a42a1c0](https://linux-hardware.org/?probe=091a42a1c0) | May 14, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [aa5dc9770e](https://linux-hardware.org/?probe=aa5dc9770e) | May 13, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [51c66f0f57](https://linux-hardware.org/?probe=51c66f0f57) | May 13, 2023 |
| Inventec      | D CLASS A02                 | Desktop     | [309a617781](https://linux-hardware.org/?probe=309a617781) | May 13, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [31d034ce6e](https://linux-hardware.org/?probe=31d034ce6e) | May 13, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [55abeba9a3](https://linux-hardware.org/?probe=55abeba9a3) | May 13, 2023 |
| Dell          | 0GWHMW A00                  | Desktop     | [d2dbc10885](https://linux-hardware.org/?probe=d2dbc10885) | May 13, 2023 |
| Gigabyte      | B360M DS3H                  | Desktop     | [82dbe1cdf7](https://linux-hardware.org/?probe=82dbe1cdf7) | May 13, 2023 |
| Fujitsu       | CELSIUS H760                | Notebook    | [7bb1e2b54e](https://linux-hardware.org/?probe=7bb1e2b54e) | May 13, 2023 |
| Toshiba       | Satellite C55-A-1KZ         | Notebook    | [37c165fa30](https://linux-hardware.org/?probe=37c165fa30) | May 13, 2023 |
| Dell          | Precision 3571              | Notebook    | [9a20dccb42](https://linux-hardware.org/?probe=9a20dccb42) | May 13, 2023 |
| GPU Compan... | GWTN156-11                  | Notebook    | [afb2844cb4](https://linux-hardware.org/?probe=afb2844cb4) | May 13, 2023 |
| Dell          | 0NDYHG A01                  | Desktop     | [8fdc05a6ad](https://linux-hardware.org/?probe=8fdc05a6ad) | May 13, 2023 |
| Samsung       | RF510/RF410/RF710           | Notebook    | [4820c25349](https://linux-hardware.org/?probe=4820c25349) | May 12, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [6950584e4c](https://linux-hardware.org/?probe=6950584e4c) | May 12, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [29b8cfc7e6](https://linux-hardware.org/?probe=29b8cfc7e6) | May 12, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [9f88d81e33](https://linux-hardware.org/?probe=9f88d81e33) | May 12, 2023 |
| HP            | ProBook 4535s               | Notebook    | [0d2f9561ce](https://linux-hardware.org/?probe=0d2f9561ce) | May 12, 2023 |
| HP            | 3047h                       | Desktop     | [bb0087d307](https://linux-hardware.org/?probe=bb0087d307) | May 12, 2023 |
| Dell          | Latitude 7390               | Notebook    | [cbd8c5fdbe](https://linux-hardware.org/?probe=cbd8c5fdbe) | May 12, 2023 |
| Dell          | Latitude 7390               | Notebook    | [5677bfdac5](https://linux-hardware.org/?probe=5677bfdac5) | May 12, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | Desktop     | [b9a3dfd029](https://linux-hardware.org/?probe=b9a3dfd029) | May 12, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [39f854e5de](https://linux-hardware.org/?probe=39f854e5de) | May 11, 2023 |
| Toshiba       | Satellite L40               | Notebook    | [9945f20a3a](https://linux-hardware.org/?probe=9945f20a3a) | May 11, 2023 |
| Intel         | DB75EN AAG39650-302         | Desktop     | [e0ebf9fa8a](https://linux-hardware.org/?probe=e0ebf9fa8a) | May 11, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [4ca3ad7158](https://linux-hardware.org/?probe=4ca3ad7158) | May 11, 2023 |
| ASUSTek       | B85-PLUS                    | Desktop     | [9346ce422f](https://linux-hardware.org/?probe=9346ce422f) | May 11, 2023 |
| Valve         | Jupiter                     | Notebook    | [5bfb32e683](https://linux-hardware.org/?probe=5bfb32e683) | May 11, 2023 |
| HP            | EliteBook 745 G3            | Notebook    | [256ad0c4d8](https://linux-hardware.org/?probe=256ad0c4d8) | May 11, 2023 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [7a97d5d5ab](https://linux-hardware.org/?probe=7a97d5d5ab) | May 10, 2023 |
| Lenovo        | ThinkPad L470 20J5S01S00    | Notebook    | [8886b2b825](https://linux-hardware.org/?probe=8886b2b825) | May 10, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [d764690667](https://linux-hardware.org/?probe=d764690667) | May 10, 2023 |
| MSI           | B85-G43                     | Desktop     | [878fbbb243](https://linux-hardware.org/?probe=878fbbb243) | May 09, 2023 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [58000b3a57](https://linux-hardware.org/?probe=58000b3a57) | May 09, 2023 |
| Fujitsu Si... | AMILO Pro Series V3525      | Notebook    | [6272f76b0b](https://linux-hardware.org/?probe=6272f76b0b) | May 09, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [a3e5adab46](https://linux-hardware.org/?probe=a3e5adab46) | May 08, 2023 |
| Fujitsu Si... | AMILO Pro Series V3525      | Notebook    | [e3cc11d5e4](https://linux-hardware.org/?probe=e3cc11d5e4) | May 08, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [afe5236688](https://linux-hardware.org/?probe=afe5236688) | May 08, 2023 |
| Dell          | Latitude 3190               | Notebook    | [fb4df1325b](https://linux-hardware.org/?probe=fb4df1325b) | May 08, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [a8e82695ee](https://linux-hardware.org/?probe=a8e82695ee) | May 08, 2023 |
| Valve         | Jupiter                     | Notebook    | [e6397e7f9f](https://linux-hardware.org/?probe=e6397e7f9f) | May 08, 2023 |
| HP            | 15                          | Notebook    | [162a4b16ae](https://linux-hardware.org/?probe=162a4b16ae) | May 08, 2023 |
| Dell          | Latitude 5520               | Notebook    | [4d8ef45cbc](https://linux-hardware.org/?probe=4d8ef45cbc) | May 07, 2023 |
| Acer          | TravelMate 6592             | Notebook    | [d655aad3c5](https://linux-hardware.org/?probe=d655aad3c5) | May 07, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [c0ade7c98e](https://linux-hardware.org/?probe=c0ade7c98e) | May 07, 2023 |
| Dell          | Latitude 5290               | Notebook    | [255da608b8](https://linux-hardware.org/?probe=255da608b8) | May 07, 2023 |
| ASUSTek       | Zenbook UM6702RC_RM6702R... | Notebook    | [3cf83f50f0](https://linux-hardware.org/?probe=3cf83f50f0) | May 07, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [a1e7385ffa](https://linux-hardware.org/?probe=a1e7385ffa) | May 07, 2023 |
| Gigabyte      | G41M-Combo                  | Desktop     | [077ced1a40](https://linux-hardware.org/?probe=077ced1a40) | May 06, 2023 |
| Fujitsu Si... | D2804-A1 S26361-D2804-A1    | Desktop     | [4278efc4ca](https://linux-hardware.org/?probe=4278efc4ca) | May 06, 2023 |
| Toshiba       | Satellite L300D             | Notebook    | [0e2dfb1c74](https://linux-hardware.org/?probe=0e2dfb1c74) | May 06, 2023 |
| Gigabyte      | GA-MA785GMT-UD2H            | Desktop     | [50fba20da2](https://linux-hardware.org/?probe=50fba20da2) | May 05, 2023 |
| ASUSTek       | K75DE                       | Notebook    | [d99045be1c](https://linux-hardware.org/?probe=d99045be1c) | May 05, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [8774a893d6](https://linux-hardware.org/?probe=8774a893d6) | May 05, 2023 |
| Gigabyte      | Z590 UD AC                  | Desktop     | [b8f920797f](https://linux-hardware.org/?probe=b8f920797f) | May 05, 2023 |
| Dell          | Inspiron 5770               | Notebook    | [c545869ec5](https://linux-hardware.org/?probe=c545869ec5) | May 05, 2023 |
| Gigabyte      | GA-MA790XT-UD4P             | Desktop     | [c9a5bee99d](https://linux-hardware.org/?probe=c9a5bee99d) | May 05, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [6aa9a8317d](https://linux-hardware.org/?probe=6aa9a8317d) | May 04, 2023 |
| HP            | EliteBook x360 1030 G3      | Convertible | [08a19ae7b9](https://linux-hardware.org/?probe=08a19ae7b9) | May 04, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [51ae873492](https://linux-hardware.org/?probe=51ae873492) | May 04, 2023 |
| HP            | EliteBook 8540p             | Notebook    | [11b0a5baa1](https://linux-hardware.org/?probe=11b0a5baa1) | May 04, 2023 |
| Google        | Meep                        | Notebook    | [1e5e0e6673](https://linux-hardware.org/?probe=1e5e0e6673) | May 04, 2023 |
| Dell          | Latitude 5490               | Notebook    | [20c5ad2ee2](https://linux-hardware.org/?probe=20c5ad2ee2) | May 03, 2023 |
| Dell          | Latitude E6410              | Notebook    | [8830853258](https://linux-hardware.org/?probe=8830853258) | May 03, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [91f2551511](https://linux-hardware.org/?probe=91f2551511) | May 03, 2023 |
| Packard Be... | EasyNote TE69BM             | Notebook    | [fc905a42fb](https://linux-hardware.org/?probe=fc905a42fb) | May 03, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [560b69d616](https://linux-hardware.org/?probe=560b69d616) | May 03, 2023 |
| Dell          | 09WH54 A00                  | Desktop     | [0afa4006cd](https://linux-hardware.org/?probe=0afa4006cd) | May 03, 2023 |
| Packard Be... | EasyNote LJ65               | Notebook    | [795672236a](https://linux-hardware.org/?probe=795672236a) | May 02, 2023 |
| Packard Be... | EasyNote LJ65               | Notebook    | [77860cab79](https://linux-hardware.org/?probe=77860cab79) | May 02, 2023 |
| HP            | 1589                        | Desktop     | [c817b08584](https://linux-hardware.org/?probe=c817b08584) | May 02, 2023 |
| HP            | 1589                        | Desktop     | [890241aeb6](https://linux-hardware.org/?probe=890241aeb6) | May 02, 2023 |
| Lenovo        | SHARKBAY NO DPK             | Desktop     | [01bd34ece8](https://linux-hardware.org/?probe=01bd34ece8) | May 01, 2023 |
| Gigabyte      | H110M-DS2-CF                | Desktop     | [211eb49a00](https://linux-hardware.org/?probe=211eb49a00) | May 01, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [15c40bae27](https://linux-hardware.org/?probe=15c40bae27) | May 01, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [a644bc676e](https://linux-hardware.org/?probe=a644bc676e) | May 01, 2023 |
| HP            | Compaq 6910p                | Notebook    | [a697e756f5](https://linux-hardware.org/?probe=a697e756f5) | May 01, 2023 |
| Dell          | Latitude 3190               | Notebook    | [59c654b2ec](https://linux-hardware.org/?probe=59c654b2ec) | May 01, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [c03693e806](https://linux-hardware.org/?probe=c03693e806) | May 01, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [2fcc250a35](https://linux-hardware.org/?probe=2fcc250a35) | May 01, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [93fef964a7](https://linux-hardware.org/?probe=93fef964a7) | Apr 30, 2023 |
| MSI           | B450M PRO-M2                | Desktop     | [b650f0a26e](https://linux-hardware.org/?probe=b650f0a26e) | Apr 30, 2023 |
| Dell          | Latitude XT2                | Notebook    | [3cfd979c60](https://linux-hardware.org/?probe=3cfd979c60) | Apr 30, 2023 |
| Acer          | AO725                       | Notebook    | [03e5f661fb](https://linux-hardware.org/?probe=03e5f661fb) | Apr 30, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [408aa18a63](https://linux-hardware.org/?probe=408aa18a63) | Apr 30, 2023 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [44c60dcec2](https://linux-hardware.org/?probe=44c60dcec2) | Apr 30, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [ff639a78ec](https://linux-hardware.org/?probe=ff639a78ec) | Apr 30, 2023 |
| Dell          | Inspiron MXC061             | Notebook    | [2d1ab773dd](https://linux-hardware.org/?probe=2d1ab773dd) | Apr 30, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [54f8ed91cf](https://linux-hardware.org/?probe=54f8ed91cf) | Apr 30, 2023 |
| ASRock        | Z370 Gaming K6              | Desktop     | [a5ff738639](https://linux-hardware.org/?probe=a5ff738639) | Apr 29, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [7c378d88a2](https://linux-hardware.org/?probe=7c378d88a2) | Apr 29, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [ee996917df](https://linux-hardware.org/?probe=ee996917df) | Apr 29, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [f502c40867](https://linux-hardware.org/?probe=f502c40867) | Apr 29, 2023 |
| Acer          | Aspire V5-552G              | Notebook    | [07c58a5169](https://linux-hardware.org/?probe=07c58a5169) | Apr 29, 2023 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [a8adc86550](https://linux-hardware.org/?probe=a8adc86550) | Apr 28, 2023 |
| Acer          | Aspire VX5-591G             | Notebook    | [2461a8058f](https://linux-hardware.org/?probe=2461a8058f) | Apr 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | Notebook    | [f1290d4846](https://linux-hardware.org/?probe=f1290d4846) | Apr 28, 2023 |
| ASRock        | Z170 Extreme4               | Desktop     | [b2c012c1e2](https://linux-hardware.org/?probe=b2c012c1e2) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [2474e8e580](https://linux-hardware.org/?probe=2474e8e580) | Apr 27, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [adb8f367ea](https://linux-hardware.org/?probe=adb8f367ea) | Apr 27, 2023 |
| HP            | EliteBook 2560p             | Notebook    | [23b5cbfb33](https://linux-hardware.org/?probe=23b5cbfb33) | Apr 27, 2023 |
| Acer          | Aspire 7250                 | Notebook    | [8e8e082e3d](https://linux-hardware.org/?probe=8e8e082e3d) | Apr 26, 2023 |
| Acer          | Aspire 5737Z                | Notebook    | [121eda50b8](https://linux-hardware.org/?probe=121eda50b8) | Apr 26, 2023 |
| ASUSTek       | P5K/EPU                     | Desktop     | [33ef71c7e7](https://linux-hardware.org/?probe=33ef71c7e7) | Apr 26, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [f1f2ad2731](https://linux-hardware.org/?probe=f1f2ad2731) | Apr 26, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [a3065a1b59](https://linux-hardware.org/?probe=a3065a1b59) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d8088982c3](https://linux-hardware.org/?probe=d8088982c3) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [4cffa55fb1](https://linux-hardware.org/?probe=4cffa55fb1) | Apr 26, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [e6380a2186](https://linux-hardware.org/?probe=e6380a2186) | Apr 26, 2023 |
| HP            | Laptop 15                   | Notebook    | [34a2ebf6a1](https://linux-hardware.org/?probe=34a2ebf6a1) | Apr 26, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [872138980a](https://linux-hardware.org/?probe=872138980a) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2122bd37a5](https://linux-hardware.org/?probe=2122bd37a5) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [af7b14d259](https://linux-hardware.org/?probe=af7b14d259) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [7fbd802154](https://linux-hardware.org/?probe=7fbd802154) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ffe6065419](https://linux-hardware.org/?probe=ffe6065419) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [94ddc76aae](https://linux-hardware.org/?probe=94ddc76aae) | Apr 26, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [856de630ec](https://linux-hardware.org/?probe=856de630ec) | Apr 25, 2023 |
| Dell          | Cherry Trail CR A00         | Mini pc     | [f1fb89d0f7](https://linux-hardware.org/?probe=f1fb89d0f7) | Apr 25, 2023 |
| Dell          | 03NVJ6 A02                  | Desktop     | [74a0632f6e](https://linux-hardware.org/?probe=74a0632f6e) | Apr 25, 2023 |
| Lenovo        | ThinkPad X200 7459KM3       | Notebook    | [cbea785e27](https://linux-hardware.org/?probe=cbea785e27) | Apr 25, 2023 |
| Dell          | Latitude E5470              | Notebook    | [3eb401d939](https://linux-hardware.org/?probe=3eb401d939) | Apr 25, 2023 |
| Dell          | Latitude E5470              | Notebook    | [37fabb89aa](https://linux-hardware.org/?probe=37fabb89aa) | Apr 25, 2023 |
| Lenovo        | G700                        | Notebook    | [75ee4cf99d](https://linux-hardware.org/?probe=75ee4cf99d) | Apr 24, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [9649423c20](https://linux-hardware.org/?probe=9649423c20) | Apr 24, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [af486ae4ae](https://linux-hardware.org/?probe=af486ae4ae) | Apr 24, 2023 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [de3ad583ab](https://linux-hardware.org/?probe=de3ad583ab) | Apr 24, 2023 |
| Medion        | X681X                       | Notebook    | [d72837ad07](https://linux-hardware.org/?probe=d72837ad07) | Apr 24, 2023 |
| HP            | EliteBook 650 15.6 inch ... | Notebook    | [78686e5784](https://linux-hardware.org/?probe=78686e5784) | Apr 24, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [76b3daef92](https://linux-hardware.org/?probe=76b3daef92) | Apr 24, 2023 |
| Dell          | Vostro 5402                 | Notebook    | [b6cb9c9140](https://linux-hardware.org/?probe=b6cb9c9140) | Apr 24, 2023 |
| Dell          | Latitude 3190               | Notebook    | [2c21a51932](https://linux-hardware.org/?probe=2c21a51932) | Apr 24, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [7bbac9f9bf](https://linux-hardware.org/?probe=7bbac9f9bf) | Apr 24, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [35c362eb4f](https://linux-hardware.org/?probe=35c362eb4f) | Apr 24, 2023 |
| Samsung       | R510/P510                   | Notebook    | [4b58936ad7](https://linux-hardware.org/?probe=4b58936ad7) | Apr 23, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [f98c5f7d2e](https://linux-hardware.org/?probe=f98c5f7d2e) | Apr 23, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [e959cc70fa](https://linux-hardware.org/?probe=e959cc70fa) | Apr 23, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | Notebook    | [18306b3af6](https://linux-hardware.org/?probe=18306b3af6) | Apr 23, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [652e029529](https://linux-hardware.org/?probe=652e029529) | Apr 23, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [bee909cfcd](https://linux-hardware.org/?probe=bee909cfcd) | Apr 23, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [c101faa12e](https://linux-hardware.org/?probe=c101faa12e) | Apr 23, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [1c439a695b](https://linux-hardware.org/?probe=1c439a695b) | Apr 23, 2023 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [3d51a6183c](https://linux-hardware.org/?probe=3d51a6183c) | Apr 23, 2023 |
| Dell          | Precision 7550              | Notebook    | [31830a82c6](https://linux-hardware.org/?probe=31830a82c6) | Apr 22, 2023 |
| Dell          | Latitude D620               | Notebook    | [7b0c5ec6f2](https://linux-hardware.org/?probe=7b0c5ec6f2) | Apr 22, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [510237facd](https://linux-hardware.org/?probe=510237facd) | Apr 22, 2023 |
| Gigabyte      | AORUS 15P XD                | Notebook    | [22925aa0c9](https://linux-hardware.org/?probe=22925aa0c9) | Apr 22, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [c1139db413](https://linux-hardware.org/?probe=c1139db413) | Apr 22, 2023 |
| MSI           | P55-GD65                    | Desktop     | [90cc53b6dd](https://linux-hardware.org/?probe=90cc53b6dd) | Apr 22, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [3056a65306](https://linux-hardware.org/?probe=3056a65306) | Apr 22, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [51ef82c2fd](https://linux-hardware.org/?probe=51ef82c2fd) | Apr 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [be207ea29f](https://linux-hardware.org/?probe=be207ea29f) | Apr 21, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [87d3a8b29f](https://linux-hardware.org/?probe=87d3a8b29f) | Apr 20, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [b7f138b04c](https://linux-hardware.org/?probe=b7f138b04c) | Apr 20, 2023 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [cde1ecf1c6](https://linux-hardware.org/?probe=cde1ecf1c6) | Apr 20, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [904089ce14](https://linux-hardware.org/?probe=904089ce14) | Apr 20, 2023 |
| Dell          | Precision M6600             | Notebook    | [e71bf9e7bb](https://linux-hardware.org/?probe=e71bf9e7bb) | Apr 20, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [3b07dc847f](https://linux-hardware.org/?probe=3b07dc847f) | Apr 20, 2023 |
| MSI           | Creator Z17 A12UHST         | Notebook    | [1396746fba](https://linux-hardware.org/?probe=1396746fba) | Apr 20, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [b2f977f4a1](https://linux-hardware.org/?probe=b2f977f4a1) | Apr 19, 2023 |
| Acer          | Aspire A715-71G             | Notebook    | [83b48fff59](https://linux-hardware.org/?probe=83b48fff59) | Apr 19, 2023 |
| Dell          | Latitude 7410               | Notebook    | [36e2aea9ea](https://linux-hardware.org/?probe=36e2aea9ea) | Apr 19, 2023 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [09a37b3301](https://linux-hardware.org/?probe=09a37b3301) | Apr 19, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | Notebook    | [1548cc4309](https://linux-hardware.org/?probe=1548cc4309) | Apr 19, 2023 |
| Dell          | Precision M6800             | Notebook    | [b39d3f31df](https://linux-hardware.org/?probe=b39d3f31df) | Apr 18, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [af6c719754](https://linux-hardware.org/?probe=af6c719754) | Apr 18, 2023 |
| Gigabyte      | G5 GE                       | Notebook    | [f1baab4be4](https://linux-hardware.org/?probe=f1baab4be4) | Apr 17, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [a0b6c23c0b](https://linux-hardware.org/?probe=a0b6c23c0b) | Apr 17, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [35ec02005f](https://linux-hardware.org/?probe=35ec02005f) | Apr 17, 2023 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [0244194778](https://linux-hardware.org/?probe=0244194778) | Apr 17, 2023 |
| Acer          | Swift SFA16-41              | Notebook    | [1232f86e3e](https://linux-hardware.org/?probe=1232f86e3e) | Apr 17, 2023 |
| Dell          | Latitude D830               | Notebook    | [3da091adc2](https://linux-hardware.org/?probe=3da091adc2) | Apr 17, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [7ca92cfada](https://linux-hardware.org/?probe=7ca92cfada) | Apr 17, 2023 |
| Lenovo        | ThinkPad T480s 20L8SF1X0... | Notebook    | [d567c29052](https://linux-hardware.org/?probe=d567c29052) | Apr 17, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [c59c5c0cdf](https://linux-hardware.org/?probe=c59c5c0cdf) | Apr 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [391b43ba8c](https://linux-hardware.org/?probe=391b43ba8c) | Apr 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [c8513ddcf3](https://linux-hardware.org/?probe=c8513ddcf3) | Apr 16, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [b74080b280](https://linux-hardware.org/?probe=b74080b280) | Apr 16, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [4fad8fc758](https://linux-hardware.org/?probe=4fad8fc758) | Apr 16, 2023 |
| Dell          | Latitude E6330              | Notebook    | [1a75476b96](https://linux-hardware.org/?probe=1a75476b96) | Apr 16, 2023 |
| Acer          | AO722                       | Notebook    | [af4e100c16](https://linux-hardware.org/?probe=af4e100c16) | Apr 15, 2023 |
| Kiano         | Elegance 14.2               | Notebook    | [34062f30df](https://linux-hardware.org/?probe=34062f30df) | Apr 15, 2023 |
| Acer          | Aspire 5336                 | Notebook    | [7613566248](https://linux-hardware.org/?probe=7613566248) | Apr 15, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [9206720811](https://linux-hardware.org/?probe=9206720811) | Apr 14, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [3c77a2b081](https://linux-hardware.org/?probe=3c77a2b081) | Apr 14, 2023 |
| Valve         | Jupiter                     | Notebook    | [c1558fbc72](https://linux-hardware.org/?probe=c1558fbc72) | Apr 14, 2023 |
| MSI           | B85-G43                     | Desktop     | [0363360efa](https://linux-hardware.org/?probe=0363360efa) | Apr 14, 2023 |
| Lenovo        | Legion 5 15IAH7 82RC        | Notebook    | [9cb53e6d6f](https://linux-hardware.org/?probe=9cb53e6d6f) | Apr 13, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [9341670151](https://linux-hardware.org/?probe=9341670151) | Apr 13, 2023 |
| Lenovo        | ThinkPad X220 4291AY8       | Notebook    | [b2bc70473d](https://linux-hardware.org/?probe=b2bc70473d) | Apr 13, 2023 |
| Dell          | 0GXM1W A00                  | Desktop     | [f96d907026](https://linux-hardware.org/?probe=f96d907026) | Apr 13, 2023 |
| ASUSTek       | A68HM-K                     | Desktop     | [5586a15d29](https://linux-hardware.org/?probe=5586a15d29) | Apr 13, 2023 |
| Fujitsu Si... | AMILO PRO V3515             | Notebook    | [be2d8594c3](https://linux-hardware.org/?probe=be2d8594c3) | Apr 13, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [1d6ace19a5](https://linux-hardware.org/?probe=1d6ace19a5) | Apr 13, 2023 |
| ASRock        | Z170 Extreme4               | Desktop     | [d21971f30f](https://linux-hardware.org/?probe=d21971f30f) | Apr 13, 2023 |
| Dell          | Latitude E6230              | Notebook    | [a7cce7ebde](https://linux-hardware.org/?probe=a7cce7ebde) | Apr 12, 2023 |
| Acer          | WG43M                       | Desktop     | [e22afb229d](https://linux-hardware.org/?probe=e22afb229d) | Apr 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3460C... | Notebook    | [f1999ee14e](https://linux-hardware.org/?probe=f1999ee14e) | Apr 11, 2023 |
| HP            | 8158 A01                    | Mini pc     | [a7d7e5c675](https://linux-hardware.org/?probe=a7d7e5c675) | Apr 11, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [b85f3476ed](https://linux-hardware.org/?probe=b85f3476ed) | Apr 11, 2023 |
| Dell          | Latitude 7390               | Notebook    | [9361f06955](https://linux-hardware.org/?probe=9361f06955) | Apr 11, 2023 |
| Lenovo        | ThinkPad T480 20L5S12H00    | Notebook    | [c550410c5b](https://linux-hardware.org/?probe=c550410c5b) | Apr 11, 2023 |
| HP            | Pavilion dv7                | Notebook    | [000c77d7d5](https://linux-hardware.org/?probe=000c77d7d5) | Apr 10, 2023 |
| HP            | Pavilion dv7                | Notebook    | [08e5108cda](https://linux-hardware.org/?probe=08e5108cda) | Apr 10, 2023 |
| HP            | 3032h                       | Desktop     | [824604840a](https://linux-hardware.org/?probe=824604840a) | Apr 10, 2023 |
| ASRock        | X370 Gaming X               | Desktop     | [d829fac91c](https://linux-hardware.org/?probe=d829fac91c) | Apr 10, 2023 |
| ASRock        | X370 Gaming X               | Desktop     | [bd05976130](https://linux-hardware.org/?probe=bd05976130) | Apr 10, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [001091b5fd](https://linux-hardware.org/?probe=001091b5fd) | Apr 10, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [34f1d57aec](https://linux-hardware.org/?probe=34f1d57aec) | Apr 10, 2023 |
| ASRock        | X370 Gaming X               | Desktop     | [0beaf2366c](https://linux-hardware.org/?probe=0beaf2366c) | Apr 09, 2023 |
| Lenovo        | ThinkPad T450 20BUS0QT04    | Notebook    | [90d7e2bb21](https://linux-hardware.org/?probe=90d7e2bb21) | Apr 09, 2023 |
| Lenovo        | ThinkPad X220 4291LR6       | Notebook    | [ea86227d59](https://linux-hardware.org/?probe=ea86227d59) | Apr 09, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [6b6b2a8633](https://linux-hardware.org/?probe=6b6b2a8633) | Apr 09, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [00489240d2](https://linux-hardware.org/?probe=00489240d2) | Apr 09, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [6f8748297a](https://linux-hardware.org/?probe=6f8748297a) | Apr 09, 2023 |
| Lenovo        | IdeaPad S540-14IWL 81ND     | Notebook    | [869d7607e9](https://linux-hardware.org/?probe=869d7607e9) | Apr 08, 2023 |
| Acer          | Aspire 5336                 | Notebook    | [6e419f3401](https://linux-hardware.org/?probe=6e419f3401) | Apr 08, 2023 |
| Toshiba       | Satellite L750D             | Notebook    | [d510eabb78](https://linux-hardware.org/?probe=d510eabb78) | Apr 08, 2023 |
| Toshiba       | Satellite L750D             | Notebook    | [3c8c0e7455](https://linux-hardware.org/?probe=3c8c0e7455) | Apr 08, 2023 |
| MSI           | MS-B0A21                    | Desktop     | [93db7f66f1](https://linux-hardware.org/?probe=93db7f66f1) | Apr 08, 2023 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [370d1404f2](https://linux-hardware.org/?probe=370d1404f2) | Apr 08, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [b8dd840f5d](https://linux-hardware.org/?probe=b8dd840f5d) | Apr 08, 2023 |
| Samsung       | 400B4C/400B5C/200B4C/200... | Notebook    | [8026ca606e](https://linux-hardware.org/?probe=8026ca606e) | Apr 07, 2023 |
| Dell          | Inspiron 11-3162            | Notebook    | [accdfd2253](https://linux-hardware.org/?probe=accdfd2253) | Apr 07, 2023 |
| Samsung       | 730U3E/740U3E               | Notebook    | [7d4b6838e2](https://linux-hardware.org/?probe=7d4b6838e2) | Apr 07, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [413528fa5a](https://linux-hardware.org/?probe=413528fa5a) | Apr 07, 2023 |
| MSI           | GP76 Leopard 10UE           | Notebook    | [c7b870bb22](https://linux-hardware.org/?probe=c7b870bb22) | Apr 07, 2023 |
| Toshiba       | Satellite C855-12N          | Notebook    | [69e30b2fd8](https://linux-hardware.org/?probe=69e30b2fd8) | Apr 07, 2023 |
| HP            | 620                         | Notebook    | [2e14b2c046](https://linux-hardware.org/?probe=2e14b2c046) | Apr 07, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b6f721687e](https://linux-hardware.org/?probe=b6f721687e) | Apr 06, 2023 |
| HP            | ProBook 4740s               | Notebook    | [14fb51de44](https://linux-hardware.org/?probe=14fb51de44) | Apr 06, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [a71051ab5a](https://linux-hardware.org/?probe=a71051ab5a) | Apr 06, 2023 |
| eMachines     | E720 V1.09                  | Notebook    | [278ca903ac](https://linux-hardware.org/?probe=278ca903ac) | Apr 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [93cb5f66a1](https://linux-hardware.org/?probe=93cb5f66a1) | Apr 06, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Poland/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 593       | 10.44%  |
| OpenMandriva 4.2   | 317       | 5.58%   |
| Ubuntu 18.04       | 281       | 4.95%   |
| Ubuntu 22.04       | 263       | 4.63%   |
| OpenMandriva 4.3   | 231       | 4.07%   |
| Debian 11          | 159       | 2.8%    |
| Arch Rolling       | 143       | 2.52%   |
| ROSA R10           | 98        | 1.73%   |
| OpenMandriva 23.03 | 97        | 1.71%   |
| OpenMandriva 23.01 | 92        | 1.62%   |
| Zorin 16           | 82        | 1.44%   |
| Linux Mint 21.1    | 79        | 1.39%   |
| Manjaro            | 76        | 1.34%   |
| Linux Mint 20.3    | 72        | 1.27%   |
| ROSA R9            | 70        | 1.23%   |
| ROSA R11           | 69        | 1.21%   |
| Arch               | 68        | 1.2%    |
| Linux Mint 20.1    | 66        | 1.16%   |
| Fedora 38          | 66        | 1.16%   |
| Fedora 37          | 66        | 1.16%   |
| ROSA R11.1         | 65        | 1.14%   |
| KDE neon 20.04     | 64        | 1.13%   |
| Fedora 36          | 60        | 1.06%   |
| Ubuntu 20.10       | 57        | 1%      |
| Pop!_OS 22.04      | 57        | 1%      |
| Linux Mint 20.2    | 53        | 0.93%   |
| Ubuntu 21.04       | 50        | 0.88%   |
| Linux Mint 20      | 49        | 0.86%   |
| Linux Mint 19.3    | 49        | 0.86%   |
| Ubuntu 19.10       | 48        | 0.85%   |
| Ubuntu 22.10       | 46        | 0.81%   |
| Ubuntu 21.10       | 44        | 0.77%   |
| Fedora 35          | 43        | 0.76%   |
| ROSA R8            | 42        | 0.74%   |
| Fedora 33          | 41        | 0.72%   |
| Linux Mint 21      | 40        | 0.7%    |
| Debian 10          | 40        | 0.7%    |
| Fedora 34          | 39        | 0.69%   |
| Xubuntu 20.04      | 38        | 0.67%   |
| Fedora 32          | 38        | 0.67%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1387      | 26.49%  |
| OpenMandriva  | 772       | 14.74%  |
| Linux Mint    | 431       | 8.23%   |
| Fedora        | 357       | 6.82%   |
| ROSA          | 336       | 6.42%   |
| Debian        | 261       | 4.98%   |
| Manjaro       | 204       | 3.9%    |
| Arch          | 203       | 3.88%   |
| Pop!_OS       | 154       | 2.94%   |
| Zorin         | 121       | 2.31%   |
| Kubuntu       | 105       | 2.01%   |
| KDE neon      | 94        | 1.8%    |
| Xubuntu       | 80        | 1.53%   |
| openSUSE      | 50        | 0.95%   |
| Kali          | 49        | 0.94%   |
| Gentoo        | 49        | 0.94%   |
| ArcoLinux     | 41        | 0.78%   |
| Lubuntu       | 38        | 0.73%   |
| Endless       | 37        | 0.71%   |
| Elementary    | 35        | 0.67%   |
| LMDE          | 32        | 0.61%   |
| EndeavourOS   | 32        | 0.61%   |
| SteamOS       | 27        | 0.52%   |
| Ubuntu Unity  | 22        | 0.42%   |
| Ubuntu MATE   | 22        | 0.42%   |
| MX            | 21        | 0.4%    |
| Clear Linux   | 21        | 0.4%    |
| Nobara        | 19        | 0.36%   |
| BlackPanther  | 18        | 0.34%   |
| CentOS        | 15        | 0.29%   |
| Garuda Linux  | 14        | 0.27%   |
| Ubuntu Budgie | 13        | 0.25%   |
| Xero          | 12        | 0.23%   |
| Peppermint    | 10        | 0.19%   |
| LinuxFX       | 10        | 0.19%   |
| Raspbian      | 8         | 0.15%   |
| NixOS         | 8         | 0.15%   |
| Linux Lite    | 8         | 0.15%   |
| EuroLinux     | 7         | 0.13%   |
| Parrot        | 6         | 0.11%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002        | 303       | 4.78%   |
| 5.16.7-desktop-1omv4003         | 212       | 3.35%   |
| 6.2.6-desktop-1omv2390          | 93        | 1.47%   |
| 6.1.1-desktop-1omv2290          | 82        | 1.29%   |
| 5.4.0-42-generic                | 78        | 1.23%   |
| 5.15.0-56-generic               | 60        | 0.95%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 54        | 0.85%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 53        | 0.84%   |
| 5.15.0-43-generic               | 41        | 0.65%   |
| 5.4.0-26-generic                | 40        | 0.63%   |
| 5.15.0-58-generic               | 39        | 0.62%   |
| 4.15.0-desktop-45.1rosa-x86_64  | 39        | 0.62%   |
| 5.4.0-52-generic                | 38        | 0.6%    |
| 5.4.0-48-generic                | 36        | 0.57%   |
| 5.15.0-52-generic               | 36        | 0.57%   |
| 5.19.0-35-generic               | 35        | 0.55%   |
| 5.4.0-58-generic                | 33        | 0.52%   |
| 5.4.0-29-generic                | 30        | 0.47%   |
| 5.3.0-46-generic                | 30        | 0.47%   |
| 5.19.0-32-generic               | 29        | 0.46%   |
| 5.4.0-54-generic                | 28        | 0.44%   |
| 5.8.0-43-generic                | 27        | 0.43%   |
| 5.13.0-39-generic               | 27        | 0.43%   |
| 5.11.0-37-generic               | 27        | 0.43%   |
| 5.4.0-40-generic                | 26        | 0.41%   |
| 5.4.0-37-generic                | 25        | 0.39%   |
| 5.15.0-48-generic               | 25        | 0.39%   |
| 4.1.34-nrj-desktop-2rosa-x86_64 | 24        | 0.38%   |
| 5.4.0-66-generic                | 23        | 0.36%   |
| 5.4.0-33-generic                | 23        | 0.36%   |
| 5.13.0-27-generic               | 23        | 0.36%   |
| 5.3.0-42-generic                | 22        | 0.35%   |
| 5.16.13-desktop-1omv4003        | 22        | 0.35%   |
| 5.15.0-60-generic               | 22        | 0.35%   |
| 5.11.0-27-generic               | 22        | 0.35%   |
| 5.0.0-37-generic                | 22        | 0.35%   |
| 5.10.0-21-amd64                 | 21        | 0.33%   |
| 6.4.11-desktop-1omv2390         | 20        | 0.32%   |
| 5.8.0-48-generic                | 20        | 0.32%   |
| 5.4.0-91-generic                | 20        | 0.32%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 770       | 12.89%  |
| 5.15.0  | 446       | 7.47%   |
| 5.10.14 | 305       | 5.11%   |
| 4.15.0  | 287       | 4.81%   |
| 5.11.0  | 223       | 3.73%   |
| 5.8.0   | 222       | 3.72%   |
| 5.16.7  | 215       | 3.6%    |
| 5.13.0  | 204       | 3.42%   |
| 5.10.0  | 169       | 2.83%   |
| 5.19.0  | 168       | 2.81%   |
| 5.3.0   | 166       | 2.78%   |
| 6.2.6   | 115       | 1.93%   |
| 5.0.0   | 101       | 1.69%   |
| 4.18.0  | 91        | 1.52%   |
| 6.1.1   | 84        | 1.41%   |
| 4.9.60  | 66        | 1.11%   |
| 4.9.20  | 62        | 1.04%   |
| 6.2.0   | 60        | 1%      |
| 4.19.0  | 55        | 0.92%   |
| 6.1.0   | 54        | 0.9%    |
| 5.14.0  | 37        | 0.62%   |
| 4.1.34  | 32        | 0.54%   |
| 4.1.38  | 28        | 0.47%   |
| 6.0.0   | 26        | 0.44%   |
| 6.4.11  | 24        | 0.4%    |
| 5.16.13 | 24        | 0.4%    |
| 5.17.5  | 20        | 0.33%   |
| 5.11.12 | 19        | 0.32%   |
| 5.9.0   | 18        | 0.3%    |
| 5.4.32  | 18        | 0.3%    |
| 6.0.12  | 17        | 0.28%   |
| 4.9.76  | 16        | 0.27%   |
| 4.9.155 | 16        | 0.27%   |
| 4.9.124 | 16        | 0.27%   |
| 6.0.7   | 15        | 0.25%   |
| 5.17.0  | 15        | 0.25%   |
| 6.3.5   | 14        | 0.23%   |
| 6.0.8   | 14        | 0.23%   |
| 6.1.12  | 13        | 0.22%   |
| 5.6.0   | 13        | 0.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 871       | 15.04%  |
| 5.15    | 590       | 10.19%  |
| 5.10    | 589       | 10.17%  |
| 5.16    | 309       | 5.34%   |
| 5.11    | 289       | 4.99%   |
| 4.15    | 287       | 4.96%   |
| 5.8     | 280       | 4.84%   |
| 6.2     | 260       | 4.49%   |
| 6.1     | 255       | 4.4%    |
| 5.13    | 235       | 4.06%   |
| 5.19    | 226       | 3.9%    |
| 5.3     | 186       | 3.21%   |
| 4.9     | 184       | 3.18%   |
| 6.0     | 131       | 2.26%   |
| 5.0     | 111       | 1.92%   |
| 4.18    | 103       | 1.78%   |
| 5.14    | 97        | 1.68%   |
| 6.4     | 84        | 1.45%   |
| 5.17    | 79        | 1.36%   |
| 5.9     | 74        | 1.28%   |
| 5.6     | 70        | 1.21%   |
| 5.18    | 70        | 1.21%   |
| 4.19    | 68        | 1.17%   |
| 6.3     | 67        | 1.16%   |
| 4.1     | 63        | 1.09%   |
| 5.12    | 60        | 1.04%   |
| 5.5     | 39        | 0.67%   |
| 5.7     | 35        | 0.6%    |
| 4.4     | 17        | 0.29%   |
| 6.5     | 13        | 0.22%   |
| 5.1     | 8         | 0.14%   |
| 3.10    | 7         | 0.12%   |
| 5.2     | 5         | 0.09%   |
| 4.20    | 4         | 0.07%   |
| 4.16    | 3         | 0.05%   |
| 4.13    | 3         | 0.05%   |
| 4.8     | 2         | 0.03%   |
| 4.7     | 2         | 0.03%   |
| 4.14    | 2         | 0.03%   |
| 4.12    | 2         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 4826      | 96%     |
| i686    | 150       | 2.98%   |
| aarch64 | 26        | 0.52%   |
| armv7l  | 18        | 0.36%   |
| armv8l  | 3         | 0.06%   |
| armv6l  | 2         | 0.04%   |
| ppc64   | 1         | 0.02%   |
| ppc     | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 1900      | 35.83%  |
| KDE5            | 1405      | 26.49%  |
| Unknown         | 500       | 9.43%   |
| XFCE            | 373       | 7.03%   |
| X-Cinnamon      | 303       | 5.71%   |
| KDE4            | 177       | 3.34%   |
| MATE            | 133       | 2.51%   |
| KDE             | 126       | 2.38%   |
| LXQt            | 73        | 1.38%   |
| Cinnamon        | 69        | 1.3%    |
| LXDE            | 50        | 0.94%   |
| i3              | 35        | 0.66%   |
| Pantheon        | 34        | 0.64%   |
| Unity           | 25        | 0.47%   |
| Budgie          | 22        | 0.41%   |
| Deepin          | 16        | 0.3%    |
| GNOME Flashback | 12        | 0.23%   |
| Hyprland        | 7         | 0.13%   |
| GNOME Classic   | 6         | 0.11%   |
| awesome         | 6         | 0.11%   |
| qtile           | 4         | 0.08%   |
| Openbox         | 4         | 0.08%   |
| sway            | 3         | 0.06%   |
| icewm           | 3         | 0.06%   |
| fluxbox         | 3         | 0.06%   |
| DWM             | 3         | 0.06%   |
| trinity         | 2         | 0.04%   |
| xmonad          | 1         | 0.02%   |
| stumpwm         | 1         | 0.02%   |
| ratflow         | 1         | 0.02%   |
| qt5ct           | 1         | 0.02%   |
| jwm             | 1         | 0.02%   |
| GNUstep         | 1         | 0.02%   |
| gnome-xorg      | 1         | 0.02%   |
| Endless:GNOME   | 1         | 0.02%   |
| BunsenLabs      | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 4063      | 78.07%  |
| Wayland     | 790       | 15.18%  |
| Unknown     | 243       | 4.67%   |
| Tty         | 107       | 2.06%   |
| Unspecified | 1         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2113      | 40.06%  |
| SDDM    | 1299      | 24.63%  |
| GDM     | 560       | 10.62%  |
| GDM3    | 470       | 8.91%   |
| LightDM | 465       | 8.82%   |
| KDM     | 187       | 3.55%   |
| TDM     | 152       | 2.88%   |
| XDM     | 11        | 0.21%   |
| Ly      | 4         | 0.08%   |
| SLiM    | 3         | 0.06%   |
| LXDM    | 3         | 0.06%   |
| SLIMSKI | 2         | 0.04%   |
| NODM    | 2         | 0.04%   |
| MDM     | 2         | 0.04%   |
| SU      | 1         | 0.02%   |
| LY-DM   | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| pl_PL       | 2822      | 53.99%  |
| en_US       | 1376      | 26.32%  |
| Unknown     | 651       | 12.45%  |
| en_GB       | 146       | 2.79%   |
| C           | 99        | 1.89%   |
| ru_RU       | 34        | 0.65%   |
| szl_PL      | 12        | 0.23%   |
| de_DE       | 11        | 0.21%   |
| uk_UA       | 9         | 0.17%   |
| ru_UA       | 9         | 0.17%   |
| en_CA       | 8         | 0.15%   |
| en_IE       | 6         | 0.11%   |
| fr_FR       | 5         | 0.1%    |
| POSIX       | 4         | 0.08%   |
| en_DK       | 4         | 0.08%   |
| en_AG       | 4         | 0.08%   |
| it_IT       | 3         | 0.06%   |
| C.UTF8      | 3         | 0.06%   |
| nl_NL       | 2         | 0.04%   |
| hu_HU       | 2         | 0.04%   |
| en_US.utf-8 | 2         | 0.04%   |
| en_IN       | 2         | 0.04%   |
| sv_SE       | 1         | 0.02%   |
| sk_SK       | 1         | 0.02%   |
| pl_PL.UTF8  | 1         | 0.02%   |
| es_ES       | 1         | 0.02%   |
| es_AR       | 1         | 0.02%   |
| en_US.UTF8  | 1         | 0.02%   |
| en_SE       | 1         | 0.02%   |
| en_AU       | 1         | 0.02%   |
| el_GR       | 1         | 0.02%   |
| de_CH       | 1         | 0.02%   |
| be_BY       | 1         | 0.02%   |
| af_ZA       | 1         | 0.02%   |
| aa_DJ       | 1         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2775      | 53.89%  |
| EFI  | 2374      | 46.11%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 3521      | 67.17%  |
| Overlay  | 722       | 13.77%  |
| Btrfs    | 488       | 9.31%   |
| Unknown  | 299       | 5.7%    |
| Xfs      | 73        | 1.39%   |
| Tmpfs    | 61        | 1.16%   |
| Zfs      | 35        | 0.67%   |
| F2fs     | 20        | 0.38%   |
| Ext2     | 7         | 0.13%   |
| Ext3     | 6         | 0.11%   |
| Rootfs   | 3         | 0.06%   |
| Jfs      | 3         | 0.06%   |
| XXXXX    | 1         | 0.02%   |
| SquXshfs | 1         | 0.02%   |
| Bcachefs | 1         | 0.02%   |
| Aufs     | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2317      | 44.46%  |
| GPT     | 2000      | 38.37%  |
| MBR     | 895       | 17.17%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4196      | 81.21%  |
| Yes       | 971       | 18.79%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3380      | 65.78%  |
| Yes       | 1758      | 34.22%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 893       | 17.8%   |
| Dell                    | 796       | 15.86%  |
| ASUSTek Computer        | 762       | 15.19%  |
| Hewlett-Packard         | 619       | 12.34%  |
| Gigabyte Technology     | 433       | 8.63%   |
| MSI                     | 367       | 7.31%   |
| Acer                    | 211       | 4.2%    |
| ASRock                  | 177       | 3.53%   |
| Toshiba                 | 83        | 1.65%   |
| Samsung Electronics     | 82        | 1.63%   |
| Fujitsu                 | 57        | 1.14%   |
| Apple                   | 44        | 0.88%   |
| Sony                    | 37        | 0.74%   |
| Fujitsu Siemens         | 34        | 0.68%   |
| Intel                   | 33        | 0.66%   |
| HUAWEI                  | 33        | 0.66%   |
| Unknown                 | 26        | 0.52%   |
| Raspberry Pi Foundation | 24        | 0.48%   |
| Google                  | 23        | 0.46%   |
| Valve                   | 22        | 0.44%   |
| Packard Bell            | 16        | 0.32%   |
| Medion                  | 16        | 0.32%   |
| Notebook                | 15        | 0.3%    |
| Foxconn                 | 14        | 0.28%   |
| Kiano                   | 12        | 0.24%   |
| eMachines               | 11        | 0.22%   |
| Timi                    | 9         | 0.18%   |
| Inventec                | 9         | 0.18%   |
| AMI                     | 7         | 0.14%   |
| Huanan                  | 6         | 0.12%   |
| ZOTAC                   | 5         | 0.1%    |
| Supermicro              | 5         | 0.1%    |
| mPTech                  | 5         | 0.1%    |
| Kruger&Matz             | 4         | 0.08%   |
| Gateway                 | 4         | 0.08%   |
| ECS                     | 4         | 0.08%   |
| Alienware               | 4         | 0.08%   |
| Xunlong                 | 3         | 0.06%   |
| TUXEDO                  | 3         | 0.06%   |
| Teclast                 | 3         | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 51        | 1.02%   |
| ASUS All Series                     | 34        | 0.68%   |
| Dell Inspiron 3451                  | 31        | 0.62%   |
| Valve Jupiter                       | 22        | 0.44%   |
| Gigabyte B450M DS3H                 | 18        | 0.36%   |
| ASUS SABERTOOTH Z77                 | 18        | 0.36%   |
| MSI MS-7B86                         | 17        | 0.34%   |
| Dell Latitude E6400                 | 17        | 0.34%   |
| MSI MS-7817                         | 16        | 0.32%   |
| Dell OptiPlex 780                   | 15        | 0.3%    |
| Dell Latitude E6540                 | 15        | 0.3%    |
| MSI MS-7C02                         | 13        | 0.26%   |
| Lenovo G50-30 80G0                  | 13        | 0.26%   |
| MSI MS-7C37                         | 12        | 0.24%   |
| HP Pavilion dv7                     | 12        | 0.24%   |
| Dell Latitude 5480                  | 12        | 0.24%   |
| Dell OptiPlex 7010                  | 11        | 0.22%   |
| Dell Latitude E6430                 | 11        | 0.22%   |
| Dell Latitude D630                  | 11        | 0.22%   |
| Dell Latitude 5490                  | 11        | 0.22%   |
| ASUS X555LJ                         | 11        | 0.22%   |
| MSI MS-7B79                         | 10        | 0.2%    |
| Lenovo Legion Y530-15ICH 81FV       | 10        | 0.2%    |
| Lenovo G580 20150                   | 10        | 0.2%    |
| Gigabyte B450 AORUS ELITE           | 10        | 0.2%    |
| MSI MS-7721                         | 9         | 0.18%   |
| HP Notebook                         | 9         | 0.18%   |
| HP 15                               | 9         | 0.18%   |
| Gigabyte B85M-D3H                   | 9         | 0.18%   |
| Dell OptiPlex 755                   | 9         | 0.18%   |
| Dell Latitude E7440                 | 9         | 0.18%   |
| Dell Latitude E6420                 | 9         | 0.18%   |
| Dell Latitude 5420                  | 9         | 0.18%   |
| ASUS TUF Gaming X570-PLUS           | 9         | 0.18%   |
| MSI MS-7A38                         | 8         | 0.16%   |
| MSI MS-7816                         | 8         | 0.16%   |
| Lenovo IdeaPad Y700-15ISK 80NV      | 8         | 0.16%   |
| Lenovo G510 20238                   | 8         | 0.16%   |
| Lenovo G50-80 80E5                  | 8         | 0.16%   |
| HP Pavilion Gaming Laptop 15-ec1xxx | 8         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 370       | 7.37%   |
| Dell Latitude         | 325       | 6.48%   |
| Dell Inspiron         | 161       | 3.21%   |
| Lenovo IdeaPad        | 160       | 3.19%   |
| Acer Aspire           | 125       | 2.49%   |
| HP EliteBook          | 107       | 2.13%   |
| Dell OptiPlex         | 107       | 2.13%   |
| HP Pavilion           | 103       | 2.05%   |
| ASUS PRIME            | 74        | 1.47%   |
| HP ProBook            | 72        | 1.43%   |
| HP Compaq             | 72        | 1.43%   |
| Dell Precision        | 70        | 1.39%   |
| Toshiba Satellite     | 66        | 1.32%   |
| Lenovo Legion         | 61        | 1.22%   |
| ASUS TUF              | 58        | 1.16%   |
| Unknown               | 51        | 1.02%   |
| ASUS ROG              | 49        | 0.98%   |
| Dell Vostro           | 45        | 0.9%    |
| Lenovo ThinkCentre    | 43        | 0.86%   |
| ASUS VivoBook         | 40        | 0.8%    |
| HP Laptop             | 36        | 0.72%   |
| Dell XPS              | 34        | 0.68%   |
| ASUS All              | 34        | 0.68%   |
| ASUS ASUS             | 29        | 0.58%   |
| Gigabyte B450M        | 27        | 0.54%   |
| RPi Raspberry         | 24        | 0.48%   |
| HP EliteDesk          | 23        | 0.46%   |
| Valve Jupiter         | 22        | 0.44%   |
| Fujitsu LIFEBOOK      | 21        | 0.42%   |
| HP 250                | 20        | 0.4%    |
| Fujitsu ESPRIMO       | 20        | 0.4%    |
| ASUS SABERTOOTH       | 20        | 0.4%    |
| Lenovo Yoga           | 19        | 0.38%   |
| MSI MS-7B86           | 17        | 0.34%   |
| HP ZBook              | 17        | 0.34%   |
| Packard Bell EasyNote | 16        | 0.32%   |
| MSI MS-7817           | 16        | 0.32%   |
| Lenovo ThinkBook      | 15        | 0.3%    |
| Gigabyte X570         | 15        | 0.3%    |
| Gigabyte B550         | 15        | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 436       | 8.69%   |
| 2012    | 429       | 8.55%   |
| 2013    | 413       | 8.23%   |
| 2019    | 396       | 7.89%   |
| 2020    | 374       | 7.45%   |
| 2011    | 361       | 7.19%   |
| 2014    | 329       | 6.56%   |
| 2017    | 292       | 5.82%   |
| 2015    | 277       | 5.52%   |
| 2008    | 268       | 5.34%   |
| 2021    | 261       | 5.2%    |
| 2010    | 253       | 5.04%   |
| 2016    | 224       | 4.46%   |
| 2009    | 224       | 4.46%   |
| 2007    | 198       | 3.95%   |
| 2022    | 128       | 2.55%   |
| 2006    | 77        | 1.53%   |
| Unknown | 41        | 0.82%   |
| 2023    | 19        | 0.38%   |
| 2005    | 11        | 0.22%   |
| 2004    | 6         | 0.12%   |
| 2001    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2988      | 59.55%  |
| Desktop        | 1812      | 36.11%  |
| Convertible    | 61        | 1.22%   |
| Mini pc        | 42        | 0.84%   |
| System on chip | 41        | 0.82%   |
| Server         | 28        | 0.56%   |
| All in one     | 21        | 0.42%   |
| Tablet         | 19        | 0.38%   |
| Phone          | 6         | 0.12%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 4749      | 93.97%  |
| Enabled  | 305       | 6.03%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4992      | 99.48%  |
| Yes  | 26        | 0.52%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1059      | 20.65%  |
| 3.01-4.0        | 1057      | 20.61%  |
| 16.01-24.0      | 946       | 18.44%  |
| 8.01-16.0       | 934       | 18.21%  |
| 32.01-64.0      | 544       | 10.61%  |
| 1.01-2.0        | 206       | 4.02%   |
| 2.01-3.0        | 122       | 2.38%   |
| 64.01-256.0     | 121       | 2.36%   |
| 24.01-32.0      | 91        | 1.77%   |
| 0.51-1.0        | 42        | 0.82%   |
| 0.01-0.5        | 4         | 0.08%   |
| More than 256.0 | 3         | 0.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 2062      | 36.08%  |
| 2.01-3.0    | 1247      | 21.82%  |
| 4.01-8.0    | 804       | 14.07%  |
| 3.01-4.0    | 666       | 11.65%  |
| 0.51-1.0    | 502       | 8.78%   |
| 8.01-16.0   | 259       | 4.53%   |
| 0.01-0.5    | 96        | 1.68%   |
| 16.01-24.0  | 53        | 0.93%   |
| 24.01-32.0  | 14        | 0.24%   |
| Unknown     | 5         | 0.09%   |
| 32.01-64.0  | 4         | 0.07%   |
| 64.01-256.0 | 3         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3058      | 58.48%  |
| 2       | 1317      | 25.19%  |
| 3       | 452       | 8.64%   |
| 4       | 178       | 3.4%    |
| 5       | 78        | 1.49%   |
| 0       | 77        | 1.47%   |
| 6       | 33        | 0.63%   |
| 7       | 17        | 0.33%   |
| 8       | 7         | 0.13%   |
| 11      | 3         | 0.06%   |
| 9       | 3         | 0.06%   |
| 10      | 2         | 0.04%   |
| Unknown | 2         | 0.04%   |
| 13      | 1         | 0.02%   |
| 12      | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2924      | 57.47%  |
| Yes       | 2164      | 42.53%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4510      | 89.61%  |
| No        | 523       | 10.39%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3801      | 75.04%  |
| No        | 1264      | 24.96%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2896      | 56.71%  |
| No        | 2211      | 43.29%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Poland  | 5018      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Warsaw                 | 1146      | 20.79%  |
| Krakow                 | 405       | 7.35%   |
| Wroclaw                | 329       | 5.97%   |
| Poznan                 | 277       | 5.03%   |
| Gdansk                 | 182       | 3.3%    |
| Lodz                   | 169       | 3.07%   |
| Katowice               | 147       | 2.67%   |
| Lublin                 | 79        | 1.43%   |
| Gdynia                 | 71        | 1.29%   |
| Szczecin               | 60        | 1.09%   |
| Bialystok              | 52        | 0.94%   |
| Gliwice                | 43        | 0.78%   |
| Częstochowa           | 42        | 0.76%   |
| Torun                  | 39        | 0.71%   |
| Rzeszów               | 39        | 0.71%   |
| Ruda Śląska          | 37        | 0.67%   |
| Bydgoszcz              | 37        | 0.67%   |
| Bytom                  | 35        | 0.63%   |
| Płock                 | 29        | 0.53%   |
| Zabrze                 | 27        | 0.49%   |
| Sosnowiec              | 27        | 0.49%   |
| Kielce                 | 27        | 0.49%   |
| Elblag                 | 27        | 0.49%   |
| Bielsko-Biala          | 25        | 0.45%   |
| Rybnik                 | 24        | 0.44%   |
| Olsztyn                | 23        | 0.42%   |
| Strzyzow               | 21        | 0.38%   |
| Radom                  | 21        | 0.38%   |
| Opole                  | 21        | 0.38%   |
| Chorzów               | 21        | 0.38%   |
| Tarnów                | 20        | 0.36%   |
| Siemianowice Śląskie | 19        | 0.34%   |
| Tychy                  | 18        | 0.33%   |
| Zielona Góra          | 15        | 0.27%   |
| Debica                 | 15        | 0.27%   |
| Cieszyn                | 15        | 0.27%   |
| Piaseczno              | 14        | 0.25%   |
| Legnica                | 14        | 0.25%   |
| Słupsk                | 13        | 0.24%   |
| Jaworzno               | 13        | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 1035      | 1591   | 13.8%   |
| Seagate                   | 1029      | 1595   | 13.72%  |
| WDC                       | 998       | 1544   | 13.3%   |
| GOODRAM                   | 510       | 769    | 6.8%    |
| Toshiba                   | 457       | 683    | 6.09%   |
| Crucial                   | 288       | 475    | 3.84%   |
| Kingston                  | 285       | 406    | 3.8%    |
| A-DATA Technology         | 280       | 380    | 3.73%   |
| Unknown                   | 278       | 411    | 3.71%   |
| SanDisk                   | 273       | 373    | 3.64%   |
| Hitachi                   | 250       | 367    | 3.33%   |
| Intel                     | 185       | 248    | 2.47%   |
| SK hynix                  | 166       | 216    | 2.21%   |
| Micron Technology         | 113       | 147    | 1.51%   |
| HGST                      | 108       | 140    | 1.44%   |
| Patriot                   | 98        | 128    | 1.31%   |
| SPCC                      | 81        | 130    | 1.08%   |
| Plextor                   | 59        | 78     | 0.79%   |
| PNY                       | 56        | 62     | 0.75%   |
| KIOXIA                    | 53        | 59     | 0.71%   |
| XPG                       | 44        | 63     | 0.59%   |
| Phison                    | 42        | 57     | 0.56%   |
| Fujitsu                   | 41        | 45     | 0.55%   |
| Apacer                    | 40        | 63     | 0.53%   |
| Phison Electronics        | 38        | 51     | 0.51%   |
| China                     | 37        | 56     | 0.49%   |
| OCZ                       | 30        | 33     | 0.4%    |
| LITEON                    | 29        | 38     | 0.39%   |
| Silicon Motion            | 28        | 36     | 0.37%   |
| Transcend                 | 26        | 29     | 0.35%   |
| Corsair                   | 26        | 36     | 0.35%   |
| Maxtor                    | 22        | 22     | 0.29%   |
| ADATA Technology          | 22        | 27     | 0.29%   |
| Realtek Semiconductor     | 21        | 33     | 0.28%   |
| Unknown                   | 21        | 24     | 0.28%   |
| KIOXIA-EXCERIA            | 20        | 27     | 0.27%   |
| JMicron Technology        | 20        | 24     | 0.27%   |
| Apple                     | 20        | 24     | 0.27%   |
| Micron/Crucial Technology | 19        | 19     | 0.25%   |
| ASMT                      | 19        | 20     | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Crucial CT500MX500SSD1 500GB                        | 67        | 0.82%   |
| Seagate ST500LT012-1DG142 500GB                     | 65        | 0.79%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 62        | 0.75%   |
| Seagate ST1000LM035-1RK172 1TB                      | 59        | 0.72%   |
| Toshiba HDWD110 1TB                                 | 57        | 0.69%   |
| Samsung SSD 850 EVO 250GB                           | 55        | 0.67%   |
| GOODRAM SSDPR-CX400-256-G2 256GB                    | 53        | 0.64%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 52        | 0.63%   |
| GOODRAM SSD 120GB                                   | 51        | 0.62%   |
| Crucial CT1000MX500SSD1 1TB                         | 46        | 0.56%   |
| Unknown MMC Card  32GB                              | 43        | 0.52%   |
| Samsung SSD 860 EVO 500GB                           | 42        | 0.51%   |
| GOODRAM SSDPR-CX400-512-G2 512GB                    | 41        | 0.5%    |
| Seagate ST500DM002-1BD142 500GB                     | 40        | 0.49%   |
| GOODRAM SSD 240GB                                   | 40        | 0.49%   |
| Kingston SA400S37240G 240GB SSD                     | 39        | 0.47%   |
| GOODRAM SSDPR-CX400-512 512GB                       | 37        | 0.45%   |
| Crucial CT240BX500SSD1 240GB                        | 37        | 0.45%   |
| Unknown MMC Card  64GB                              | 35        | 0.43%   |
| Toshiba MQ01ABD100 1TB                              | 34        | 0.41%   |
| Kingston SV300S37A120G 120GB SSD                    | 34        | 0.41%   |
| Seagate ST1000DM010-2EP102 1TB                      | 33        | 0.4%    |
| Samsung SSD 980 1TB                                 | 33        | 0.4%    |
| Samsung SSD 860 EVO 250GB                           | 33        | 0.4%    |
| Seagate ST9500325AS 500GB                           | 32        | 0.39%   |
| Samsung NVMe SSD Drive 500GB                        | 32        | 0.39%   |
| A-DATA SU800 256GB SSD                              | 32        | 0.39%   |
| Seagate ST3500418AS 500GB                           | 30        | 0.36%   |
| Seagate ST1000DM003-1ER162 1TB                      | 30        | 0.36%   |
| Patriot Burst 120GB SSD                             | 30        | 0.36%   |
| Samsung SSD 980 500GB                               | 28        | 0.34%   |
| Samsung NVMe SSD Drive 512GB                        | 28        | 0.34%   |
| GOODRAM SSDPR-CX400-256 256GB                       | 28        | 0.34%   |
| Seagate Expansion 1TB                               | 27        | 0.33%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 27        | 0.33%   |
| Kingston SA400S37480G 480GB SSD                     | 26        | 0.32%   |
| Intel NVMe SSD Drive 512GB                          | 26        | 0.32%   |
| HGST HTS721010A9E630 1TB                            | 26        | 0.32%   |
| GOODRAM SSDPR-CX400-128 128GB                       | 26        | 0.32%   |
| Toshiba MQ01ABF050 500GB                            | 25        | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1023      | 1585   | 36.08%  |
| WDC                 | 826       | 1303   | 29.14%  |
| Toshiba             | 348       | 548    | 12.28%  |
| Hitachi             | 250       | 367    | 8.82%   |
| Samsung Electronics | 170       | 242    | 6%      |
| HGST                | 108       | 140    | 3.81%   |
| Fujitsu             | 41        | 45     | 1.45%   |
| Maxtor              | 20        | 20     | 0.71%   |
| Unknown             | 10        | 10     | 0.35%   |
| Apple               | 7         | 7      | 0.25%   |
| ASMT                | 5         | 6      | 0.18%   |
| USB3.0              | 3         | 3      | 0.11%   |
| ASMedia             | 3         | 3      | 0.11%   |
| WD MediaMax         | 2         | 3      | 0.07%   |
| SAGE                | 2         | 2      | 0.07%   |
| IBM/Hitachi         | 2         | 2      | 0.07%   |
| Unknown             | 2         | 2      | 0.07%   |
| USB                 | 1         | 1      | 0.04%   |
| Synology            | 1         | 1      | 0.04%   |
| StoreJet            | 1         | 1      | 0.04%   |
| MARVELL             | 1         | 1      | 0.04%   |
| LaCie               | 1         | 2      | 0.04%   |
| JMicron Technology  | 1         | 4      | 0.04%   |
| IB-377U3            | 1         | 6      | 0.04%   |
| HPE                 | 1         | 1      | 0.04%   |
| HGST HTS            | 1         | 1      | 0.04%   |
| Hewlett-Packard     | 1         | 1      | 0.04%   |
| ExcelStor           | 1         | 1      | 0.04%   |
| ASUSTOR             | 1         | 1      | 0.04%   |
| ASMT109x            | 1         | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| GOODRAM             | 496       | 739    | 17.96%  |
| Samsung Electronics | 446       | 637    | 16.15%  |
| Crucial             | 278       | 463    | 10.07%  |
| A-DATA Technology   | 231       | 312    | 8.37%   |
| Kingston            | 200       | 276    | 7.24%   |
| SanDisk             | 178       | 249    | 6.45%   |
| WDC                 | 93        | 112    | 3.37%   |
| Patriot             | 89        | 119    | 3.22%   |
| SPCC                | 73        | 120    | 2.64%   |
| Intel               | 60        | 73     | 2.17%   |
| Micron Technology   | 57        | 72     | 2.06%   |
| Plextor             | 50        | 69     | 1.81%   |
| Toshiba             | 48        | 53     | 1.74%   |
| SK hynix            | 45        | 54     | 1.63%   |
| PNY                 | 43        | 48     | 1.56%   |
| China               | 36        | 55     | 1.3%    |
| Apacer              | 36        | 59     | 1.3%    |
| OCZ                 | 30        | 33     | 1.09%   |
| LITEON              | 29        | 38     | 1.05%   |
| Transcend           | 25        | 28     | 0.91%   |
| LITEONIT            | 16        | 18     | 0.58%   |
| KIOXIA-EXCERIA      | 16        | 21     | 0.58%   |
| ASMT                | 14        | 14     | 0.51%   |
| JMicron Technology  | 13        | 13     | 0.47%   |
| Apple               | 12        | 12     | 0.43%   |
| Corsair             | 11        | 12     | 0.4%    |
| KingSpec            | 9         | 10     | 0.33%   |
| Team                | 8         | 8      | 0.29%   |
| Intenso             | 8         | 13     | 0.29%   |
| Gigabyte Technology | 7         | 8      | 0.25%   |
| POLION              | 5         | 5      | 0.18%   |
| Lexar               | 5         | 5      | 0.18%   |
| BIWIN               | 5         | 5      | 0.18%   |
| Argon               | 4         | 6      | 0.14%   |
| Unknown             | 4         | 4      | 0.14%   |
| WDC WDS2            | 3         | 3      | 0.11%   |
| Phison              | 3         | 3      | 0.11%   |
| PHD 3.0             | 3         | 3      | 0.11%   |
| Kingchuxing         | 3         | 3      | 0.11%   |
| Biostar             | 3         | 3      | 0.11%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2410      | 4310   | 36.31%  |
| SSD     | 2385      | 3855   | 35.93%  |
| NVMe    | 1496      | 2270   | 22.54%  |
| MMC     | 261       | 377    | 3.93%   |
| Unknown | 86        | 124    | 1.3%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3855      | 7949   | 65.76%  |
| NVMe | 1495      | 2262   | 25.5%   |
| MMC  | 261       | 377    | 4.45%   |
| SAS  | 251       | 348    | 4.28%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 3144      | 5202   | 64.37%  |
| 0.51-1.0   | 1280      | 2060   | 26.21%  |
| 1.01-2.0   | 261       | 433    | 5.34%   |
| 3.01-4.0   | 73        | 157    | 1.49%   |
| 2.01-3.0   | 63        | 173    | 1.29%   |
| 4.01-10.0  | 46        | 103    | 0.94%   |
| 10.01-20.0 | 17        | 37     | 0.35%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1494      | 27.32%  |
| 251-500        | 1035      | 18.92%  |
| 1-20           | 666       | 12.18%  |
| 501-1000       | 637       | 11.65%  |
| 51-100         | 456       | 8.34%   |
| 1001-2000      | 378       | 6.91%   |
| 21-50          | 272       | 4.97%   |
| Unknown        | 236       | 4.32%   |
| More than 3000 | 169       | 3.09%   |
| 2001-3000      | 126       | 2.3%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2325      | 41.3%   |
| 21-50          | 828       | 14.71%  |
| 101-250        | 691       | 12.27%  |
| 51-100         | 619       | 10.99%  |
| 251-500        | 356       | 6.32%   |
| 501-1000       | 296       | 5.26%   |
| Unknown        | 236       | 4.19%   |
| 1001-2000      | 164       | 2.91%   |
| 2001-3000      | 59        | 1.05%   |
| More than 3000 | 54        | 0.96%   |
| 0              | 2         | 0.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB            | 14        | 17     | 1.9%    |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 11        | 13     | 1.49%   |
| Seagate ST500LT012-9WS142 500GB      | 10        | 29     | 1.36%   |
| Seagate ST3500418AS 500GB            | 9         | 12     | 1.22%   |
| Seagate ST500LT012-1DG142 500GB      | 8         | 11     | 1.09%   |
| Seagate ST500DM002-1BD142 500GB      | 8         | 8      | 1.09%   |
| Seagate ST1000DM003-9YN162 1TB       | 7         | 7      | 0.95%   |
| SK hynix PC711 HFS512GDE9X073N 512GB | 6         | 7      | 0.82%   |
| HGST HTS545050A7E680 500GB           | 6         | 6      | 0.82%   |
| Toshiba MQ01ABD100 1TB               | 5         | 6      | 0.68%   |
| Kingston SV300S37A120G 120GB SSD     | 5         | 5      | 0.68%   |
| GOODRAM SSD 120GB                    | 5         | 5      | 0.68%   |
| ASMT 2135 18TB                       | 5         | 5      | 0.68%   |
| WDC WD5000BEVT-22ZAT0 500GB          | 4         | 4      | 0.54%   |
| WDC WD10JPVX-22JC3T0 1TB             | 4         | 4      | 0.54%   |
| Seagate ST9500420AS 500GB            | 4         | 4      | 0.54%   |
| Seagate ST9320325AS 320GB            | 4         | 4      | 0.54%   |
| Seagate ST92505610AS 250GB           | 4         | 4      | 0.54%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 4         | 4      | 0.54%   |
| Seagate ST3320613AS 320GB            | 4         | 4      | 0.54%   |
| Seagate ST1000LM014-SSHD-8GB         | 4         | 4      | 0.54%   |
| Seagate ST1000LM014-1EJ164 1TB       | 4         | 5      | 0.54%   |
| Seagate ST1000DX001-1CM162 1TB       | 4         | 7      | 0.54%   |
| Kingston SA400S37480G 480GB SSD      | 4         | 4      | 0.54%   |
| Hitachi HTS543225L9SA00 250GB        | 4         | 4      | 0.54%   |
| Hitachi HTS541612J9SA00 120GB        | 4         | 5      | 0.54%   |
| A-DATA Technology SU800 512GB SSD    | 4         | 4      | 0.54%   |
| WDC WD3200BPVT-80ZEST0 320GB         | 3         | 3      | 0.41%   |
| WDC WD10JFCX-68N6GN0 1TB             | 3         | 4      | 0.41%   |
| Toshiba MK3265GSX 320GB              | 3         | 3      | 0.41%   |
| Toshiba MK1637GSX 160GB              | 3         | 3      | 0.41%   |
| Toshiba MK1246GSX 120GB              | 3         | 3      | 0.41%   |
| Seagate ST980811AS 80GB              | 3         | 3      | 0.41%   |
| Seagate ST9250827AS 250GB            | 3         | 4      | 0.41%   |
| Seagate ST9250410AS 250GB            | 3         | 3      | 0.41%   |
| Seagate ST9250315AS 250GB            | 3         | 3      | 0.41%   |
| Seagate ST9160821AS 160GB            | 3         | 4      | 0.41%   |
| Seagate ST3500320AS 500GB            | 3         | 3      | 0.41%   |
| Seagate ST3500312CS 500GB            | 3         | 3      | 0.41%   |
| Seagate ST3320418AS 320GB            | 3         | 3      | 0.41%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 206       | 274    | 29.1%   |
| WDC                   | 130       | 188    | 18.36%  |
| Hitachi               | 62        | 77     | 8.76%   |
| Samsung Electronics   | 56        | 65     | 7.91%   |
| Toshiba               | 50        | 61     | 7.06%   |
| A-DATA Technology     | 31        | 34     | 4.38%   |
| SanDisk               | 17        | 20     | 2.4%    |
| HGST                  | 17        | 18     | 2.4%    |
| Kingston              | 16        | 16     | 2.26%   |
| SK hynix              | 15        | 16     | 2.12%   |
| Fujitsu               | 10        | 12     | 1.41%   |
| Micron Technology     | 8         | 8      | 1.13%   |
| Intel                 | 8         | 8      | 1.13%   |
| GOODRAM               | 8         | 8      | 1.13%   |
| Crucial               | 7         | 15     | 0.99%   |
| LITEON                | 6         | 6      | 0.85%   |
| ASMT                  | 6         | 7      | 0.85%   |
| Maxtor                | 5         | 5      | 0.71%   |
| China                 | 5         | 6      | 0.71%   |
| SPCC                  | 4         | 4      | 0.56%   |
| LITEONIT              | 4         | 4      | 0.56%   |
| Apacer                | 4         | 7      | 0.56%   |
| Patriot               | 3         | 5      | 0.42%   |
| OCZ                   | 3         | 3      | 0.42%   |
| Hewlett-Packard       | 3         | 3      | 0.42%   |
| ASMedia               | 3         | 3      | 0.42%   |
| SSSTC                 | 2         | 2      | 0.28%   |
| Apple                 | 2         | 2      | 0.28%   |
| XPG                   | 1         | 1      | 0.14%   |
| WDC WDS2              | 1         | 1      | 0.14%   |
| WD MediaMax           | 1         | 2      | 0.14%   |
| SAGE                  | 1         | 1      | 0.14%   |
| RENICE                | 1         | 1      | 0.14%   |
| Realtek Semiconductor | 1         | 1      | 0.14%   |
| POLION                | 1         | 1      | 0.14%   |
| Plextor               | 1         | 1      | 0.14%   |
| Platinet              | 1         | 1      | 0.14%   |
| Lexar                 | 1         | 1      | 0.14%   |
| Lenovo                | 1         | 1      | 0.14%   |
| KingSpec              | 1         | 1      | 0.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 206       | 274    | 39.39%  |
| WDC                 | 127       | 184    | 24.28%  |
| Hitachi             | 62        | 77     | 11.85%  |
| Toshiba             | 47        | 58     | 8.99%   |
| Samsung Electronics | 40        | 46     | 7.65%   |
| HGST                | 17        | 18     | 3.25%   |
| Fujitsu             | 10        | 12     | 1.91%   |
| Maxtor              | 5         | 5      | 0.96%   |
| ASMedia             | 2         | 2      | 0.38%   |
| WD MediaMax         | 1         | 2      | 0.19%   |
| SAGE                | 1         | 1      | 0.19%   |
| JMicron Technology  | 1         | 2      | 0.19%   |
| Hewlett-Packard     | 1         | 1      | 0.19%   |
| ASMT                | 1         | 2      | 0.19%   |
| Apple               | 1         | 1      | 0.19%   |
| Unknown             | 1         | 1      | 0.19%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 485       | 686    | 72.82%  |
| SSD  | 154       | 181    | 23.12%  |
| NVMe | 27        | 30     | 4.05%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD800BEVS-75RST0 80GB         | 1         | 1      | 7.69%   |
| WDC WD3200BEVT-22ZCT0 320GB       | 1         | 1      | 7.69%   |
| WDC WD3200BEKT-75PVMT1 320GB      | 1         | 1      | 7.69%   |
| WDC WD2500BEVS-22UST0 250GB       | 1         | 1      | 7.69%   |
| WDC WD1600AAJS-75M0A0 160GB       | 1         | 1      | 7.69%   |
| Toshiba MK3265GSXN 320GB          | 1         | 1      | 7.69%   |
| Toshiba DT01ACA100 1TB            | 1         | 2      | 7.69%   |
| Seagate ST500DM002-1BC142 500GB   | 1         | 1      | 7.69%   |
| Seagate ST320LT020-9YG142 320GB   | 1         | 1      | 7.69%   |
| Seagate ST31000528AS 1TB          | 1         | 1      | 7.69%   |
| Samsung Electronics HD250HJ 250GB | 1         | 1      | 7.69%   |
| OCZ-AGIL ITY3 64GB SSD            | 1         | 1      | 7.69%   |
| HGST HTS725025A7 250GB            | 1         | 1      | 7.69%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 38.46%  |
| Seagate             | 3         | 3      | 23.08%  |
| Toshiba             | 2         | 3      | 15.38%  |
| Samsung Electronics | 1         | 1      | 7.69%   |
| OCZ-AGIL            | 1         | 1      | 7.69%   |
| HGST                | 1         | 1      | 7.69%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2540      | 5392   | 45.84%  |
| Works    | 2338      | 4633   | 42.19%  |
| Malfunc  | 650       | 897    | 11.73%  |
| Failed   | 13        | 14     | 0.23%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3448      | 54.3%   |
| AMD                              | 924       | 14.55%  |
| Samsung Electronics              | 499       | 7.86%   |
| SanDisk                          | 181       | 2.85%   |
| Phison Electronics               | 130       | 2.05%   |
| SK hynix                         | 117       | 1.84%   |
| ASMedia Technology               | 107       | 1.69%   |
| ADATA Technology                 | 107       | 1.69%   |
| JMicron Technology               | 104       | 1.64%   |
| Kingston Technology Company      | 102       | 1.61%   |
| Nvidia                           | 93        | 1.46%   |
| Toshiba America Info Systems     | 64        | 1.01%   |
| KIOXIA                           | 60        | 0.94%   |
| Micron Technology                | 57        | 0.9%    |
| Silicon Motion                   | 52        | 0.82%   |
| Marvell Technology Group         | 51        | 0.8%    |
| Realtek Semiconductor            | 35        | 0.55%   |
| Lite-On Technology               | 29        | 0.46%   |
| Micron/Crucial Technology        | 28        | 0.44%   |
| VIA Technologies                 | 23        | 0.36%   |
| LSI Logic / Symbios Logic        | 20        | 0.31%   |
| Shenzhen Longsys Electronics     | 18        | 0.28%   |
| Union Memory (Shenzhen)          | 16        | 0.25%   |
| Silicon Integrated Systems [SiS] | 11        | 0.17%   |
| Solid State Storage Technology   | 10        | 0.16%   |
| Lenovo                           | 9         | 0.14%   |
| Hewlett-Packard                  | 9         | 0.14%   |
| Silicon Image                    | 8         | 0.13%   |
| Broadcom / LSI                   | 8         | 0.13%   |
| MAXIO Technology (Hangzhou)      | 6         | 0.09%   |
| INNOGRIT                         | 3         | 0.05%   |
| Apple                            | 3         | 0.05%   |
| Yangtze Memory Technologies      | 2         | 0.03%   |
| ULi Electronics                  | 2         | 0.03%   |
| O2 Micro                         | 2         | 0.03%   |
| Integrated Technology Express    | 2         | 0.03%   |
| Adaptec                          | 2         | 0.03%   |
| Tekram Technology                | 1         | 0.02%   |
| Seagate Technology               | 1         | 0.02%   |
| OCZ Technology Group             | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 611       | 8.18%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 251       | 3.36%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 247       | 3.31%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 244       | 3.27%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 211       | 2.83%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 181       | 2.42%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 174       | 2.33%   |
| AMD 400 Series Chipset SATA Controller                                         | 171       | 2.29%   |
| Samsung NVMe SSD Controller 980                                                | 141       | 1.89%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 141       | 1.89%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 127       | 1.7%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 127       | 1.7%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 115       | 1.54%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 114       | 1.53%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 108       | 1.45%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 107       | 1.43%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 107       | 1.43%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 102       | 1.37%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 100       | 1.34%   |
| Intel Volume Management Device NVMe RAID Controller                            | 94        | 1.26%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 94        | 1.26%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 92        | 1.23%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 86        | 1.15%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 85        | 1.14%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 82        | 1.1%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 82        | 1.1%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 81        | 1.08%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 78        | 1.04%   |
| Intel SSD 660P Series                                                          | 76        | 1.02%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 71        | 0.95%   |
| JMicron JMB363 SATA/IDE Controller                                             | 70        | 0.94%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 70        | 0.94%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 67        | 0.9%    |
| Phison E12 NVMe Controller                                                     | 62        | 0.83%   |
| Intel SATA Controller [RAID mode]                                              | 62        | 0.83%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 62        | 0.83%   |
| AMD 500 Series Chipset SATA Controller                                         | 58        | 0.78%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 51        | 0.68%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 50        | 0.67%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 50        | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 3624      | 56.33%  |
| NVMe | 1504      | 23.38%  |
| IDE  | 891       | 13.85%  |
| RAID | 383       | 5.95%   |
| SAS  | 17        | 0.26%   |
| SCSI | 14        | 0.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 3771      | 75.15%  |
| AMD          | 1194      | 23.79%  |
| ARM          | 45        | 0.9%    |
| QUALCOMM     | 3         | 0.06%   |
| CentaurHauls | 2         | 0.04%   |
| PowerMac11,2 | 1         | 0.02%   |
| PowerBook6,7 | 1         | 0.02%   |
| AppliedMicro | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron CPU N2840 @ 2.16GHz             | 51        | 1.01%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 47        | 0.93%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 46        | 0.91%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 44        | 0.87%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 44        | 0.87%   |
| AMD Ryzen 5 3600 6-Core Processor             | 44        | 0.87%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 41        | 0.81%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 39        | 0.77%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 38        | 0.75%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 36        | 0.71%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 36        | 0.71%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 35        | 0.69%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 33        | 0.65%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 33        | 0.65%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 33        | 0.65%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 32        | 0.63%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 29        | 0.58%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 28        | 0.56%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 28        | 0.56%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 28        | 0.56%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 27        | 0.54%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 27        | 0.54%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 26        | 0.52%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 26        | 0.52%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 25        | 0.5%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 24        | 0.48%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 23        | 0.46%   |
| Intel Core i5-3570K CPU @ 3.40GHz             | 23        | 0.46%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 23        | 0.46%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 23        | 0.46%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 22        | 0.44%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 22        | 0.44%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 22        | 0.44%   |
| ARM Processor                                 | 22        | 0.44%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 22        | 0.44%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 22        | 0.44%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 22        | 0.44%   |
| AMD Custom APU 0405                           | 22        | 0.44%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 21        | 0.42%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 20        | 0.4%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1217      | 24.18%  |
| Intel Core i7           | 768       | 15.26%  |
| Intel Core i3           | 351       | 6.97%   |
| AMD Ryzen 5             | 332       | 6.6%    |
| Intel Core 2 Duo        | 317       | 6.3%    |
| Other                   | 268       | 5.32%   |
| Intel Celeron           | 224       | 4.45%   |
| AMD Ryzen 7             | 211       | 4.19%   |
| Intel Pentium           | 141       | 2.8%    |
| Intel Xeon              | 129       | 2.56%   |
| Intel Atom              | 84        | 1.67%   |
| Intel Pentium Dual-Core | 73        | 1.45%   |
| Intel Core 2 Quad       | 71        | 1.41%   |
| AMD Ryzen 9             | 63        | 1.25%   |
| AMD FX                  | 50        | 0.99%   |
| Intel Core 2            | 42        | 0.83%   |
| AMD Phenom II X4        | 40        | 0.79%   |
| AMD A8                  | 39        | 0.77%   |
| AMD A6                  | 39        | 0.77%   |
| AMD Ryzen 3             | 38        | 0.75%   |
| Intel Pentium Dual      | 33        | 0.66%   |
| AMD Athlon 64 X2        | 33        | 0.66%   |
| AMD A10                 | 33        | 0.66%   |
| AMD Athlon II X2        | 29        | 0.58%   |
| AMD Ryzen 7 PRO         | 20        | 0.4%    |
| AMD A4                  | 20        | 0.4%    |
| AMD Athlon II X4        | 19        | 0.38%   |
| Intel Genuine           | 18        | 0.36%   |
| Intel Core i9           | 17        | 0.34%   |
| AMD E                   | 17        | 0.34%   |
| AMD GX                  | 14        | 0.28%   |
| AMD E1                  | 14        | 0.28%   |
| AMD Ryzen 5 PRO         | 13        | 0.26%   |
| ARM BCM                 | 12        | 0.24%   |
| Intel Celeron M         | 11        | 0.22%   |
| AMD Ryzen Threadripper  | 11        | 0.22%   |
| AMD Athlon              | 11        | 0.22%   |
| AMD Athlon X2           | 9         | 0.18%   |
| Intel Pentium Silver    | 8         | 0.16%   |
| Intel Pentium M         | 8         | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2143      | 42.45%  |
| 4       | 1732      | 34.31%  |
| 6       | 495       | 9.81%   |
| 8       | 310       | 6.14%   |
| 1       | 111       | 2.2%    |
| 12      | 85        | 1.68%   |
| Unknown | 71        | 1.41%   |
| 16      | 26        | 0.52%   |
| 3       | 23        | 0.46%   |
| 10      | 20        | 0.4%    |
| 14      | 17        | 0.34%   |
| 20      | 4         | 0.08%   |
| 32      | 3         | 0.06%   |
| 24      | 2         | 0.04%   |
| 192     | 1         | 0.02%   |
| 64      | 1         | 0.02%   |
| 48      | 1         | 0.02%   |
| 44      | 1         | 0.02%   |
| 18      | 1         | 0.02%   |
| 5       | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 4965      | 98.88%  |
| 2       | 48        | 0.96%   |
| Unknown | 7         | 0.14%   |
| 4       | 1         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 3088      | 61.17%  |
| 1       | 1887      | 37.38%  |
| Unknown | 71        | 1.41%   |
| 8       | 1         | 0.02%   |
| 4       | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4887      | 97.2%   |
| Unknown        | 85        | 1.69%   |
| 32-bit         | 54        | 1.07%   |
| 64-bit         | 2         | 0.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1267      | 24.12%  |
| 0x306a9    | 297       | 5.65%   |
| 0x206a7    | 287       | 5.46%   |
| 0x306c3    | 253       | 4.82%   |
| 0x1067a    | 226       | 4.3%    |
| 0x906ea    | 135       | 2.57%   |
| 0x506e3    | 119       | 2.27%   |
| 0x40651    | 109       | 2.08%   |
| 0x20655    | 93        | 1.77%   |
| 0x806ec    | 92        | 1.75%   |
| 0x906e9    | 90        | 1.71%   |
| 0x6fd      | 90        | 1.71%   |
| 0x30678    | 90        | 1.71%   |
| 0x306d4    | 87        | 1.66%   |
| 0x806c1    | 85        | 1.62%   |
| 0x806ea    | 81        | 1.54%   |
| 0x406e3    | 80        | 1.52%   |
| 0x10676    | 77        | 1.47%   |
| 0x806e9    | 70        | 1.33%   |
| 0x0800820d | 68        | 1.29%   |
| 0x08701021 | 64        | 1.22%   |
| 0x010000c8 | 63        | 1.2%    |
| 0x0a50000c | 58        | 1.1%    |
| 0x6fb      | 46        | 0.88%   |
| 0x06001119 | 44        | 0.84%   |
| 0x08108109 | 40        | 0.76%   |
| 0x08600106 | 39        | 0.74%   |
| 0x20652    | 34        | 0.65%   |
| 0xa0652    | 32        | 0.61%   |
| 0x6f6      | 32        | 0.61%   |
| 0x08108102 | 30        | 0.57%   |
| 0x806eb    | 29        | 0.55%   |
| 0x406c4    | 28        | 0.53%   |
| 0x08701013 | 28        | 0.53%   |
| 0xa0653    | 26        | 0.49%   |
| 0x906ed    | 26        | 0.49%   |
| 0x06000852 | 23        | 0.44%   |
| 0x706e5    | 22        | 0.42%   |
| 0x106e5    | 22        | 0.42%   |
| 0x08001138 | 22        | 0.42%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 701       | 13.93%  |
| Haswell          | 472       | 9.38%   |
| IvyBridge        | 376       | 7.47%   |
| SandyBridge      | 364       | 7.23%   |
| Penryn           | 359       | 7.13%   |
| Skylake          | 270       | 5.36%   |
| Zen 2            | 235       | 4.67%   |
| Core             | 233       | 4.63%   |
| Zen+             | 180       | 3.58%   |
| Silvermont       | 175       | 3.48%   |
| Westmere         | 171       | 3.4%    |
| Unknown          | 168       | 3.34%   |
| Zen 3            | 133       | 2.64%   |
| K10              | 128       | 2.54%   |
| Broadwell        | 127       | 2.52%   |
| TigerLake        | 109       | 2.17%   |
| Zen              | 94        | 1.87%   |
| Piledriver       | 91        | 1.81%   |
| CometLake        | 89        | 1.77%   |
| K8 Hammer        | 65        | 1.29%   |
| Alderlake Hybrid | 55        | 1.09%   |
| IceLake          | 54        | 1.07%   |
| Bobcat           | 46        | 0.91%   |
| Nehalem          | 41        | 0.81%   |
| Goldmont plus    | 38        | 0.75%   |
| Bonnell          | 35        | 0.7%    |
| P6               | 33        | 0.66%   |
| Jaguar           | 28        | 0.56%   |
| Excavator        | 28        | 0.56%   |
| Goldmont         | 25        | 0.5%    |
| Steamroller      | 23        | 0.46%   |
| Puma             | 21        | 0.42%   |
| NetBurst         | 19        | 0.38%   |
| K10 Llano        | 18        | 0.36%   |
| K8 & K10 hybrid  | 16        | 0.32%   |
| Bulldozer        | 12        | 0.24%   |
| Tremont          | 1         | 0.02%   |
| Gracemont        | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2825      | 47.08%  |
| Nvidia                           | 1792      | 29.86%  |
| AMD                              | 1345      | 22.41%  |
| Matrox Electronics Systems       | 17        | 0.28%   |
| ASPEED Technology                | 8         | 0.13%   |
| VIA Technologies                 | 7         | 0.12%   |
| Silicon Integrated Systems [SiS] | 6         | 0.1%    |
| S3 Graphics                      | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 290       | 4.64%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 236       | 3.78%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 137       | 2.19%   |
| Intel UHD Graphics 620                                                                   | 113       | 1.81%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 112       | 1.79%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 112       | 1.79%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 108       | 1.73%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 107       | 1.71%   |
| Intel HD Graphics 5500                                                                   | 104       | 1.67%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 104       | 1.67%   |
| AMD Renoir                                                                               | 104       | 1.67%   |
| Intel HD Graphics 530                                                                    | 102       | 1.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 101       | 1.62%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 101       | 1.62%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 95        | 1.52%   |
| Intel Core Processor Integrated Graphics Controller                                      | 95        | 1.52%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 91        | 1.46%   |
| Intel HD Graphics 620                                                                    | 87        | 1.39%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 86        | 1.38%   |
| Intel HD Graphics 630                                                                    | 76        | 1.22%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 74        | 1.19%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 74        | 1.19%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 70        | 1.12%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 66        | 1.06%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 54        | 0.86%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 54        | 0.86%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 48        | 0.77%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 46        | 0.74%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 45        | 0.72%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 44        | 0.7%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 43        | 0.69%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 43        | 0.69%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 43        | 0.69%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 40        | 0.64%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 38        | 0.61%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 35        | 0.56%   |
| Nvidia GT218 [GeForce 210]                                                               | 32        | 0.51%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 32        | 0.51%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 31        | 0.5%    |
| Nvidia GP108 [GeForce GT 1030]                                                           | 31        | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1926      | 37.97%  |
| 1 x Nvidia               | 1006      | 19.83%  |
| 1 x AMD                  | 981       | 19.34%  |
| Intel + Nvidia           | 667       | 13.15%  |
| Intel + AMD              | 182       | 3.59%   |
| AMD + Nvidia             | 107       | 2.11%   |
| 2 x AMD                  | 76        | 1.5%    |
| Other                    | 56        | 1.1%    |
| 2 x Intel                | 22        | 0.43%   |
| 1 x Matrox               | 17        | 0.34%   |
| 2 x Nvidia               | 8         | 0.16%   |
| 1 x VIA                  | 7         | 0.14%   |
| 1 x SiS                  | 6         | 0.12%   |
| 1 x ASPEED               | 5         | 0.1%    |
| Nvidia + ASPEED          | 3         | 0.06%   |
| 3 x AMD                  | 2         | 0.04%   |
| 1 x S3 Graphics          | 1         | 0.02%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 4016      | 78.41%  |
| Proprietary | 885       | 17.28%  |
| Unknown     | 221       | 4.31%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2677      | 51.37%  |
| 1.01-2.0   | 674       | 12.93%  |
| 0.01-0.5   | 655       | 12.57%  |
| 0.51-1.0   | 450       | 8.64%   |
| 3.01-4.0   | 352       | 6.75%   |
| 7.01-8.0   | 196       | 3.76%   |
| 5.01-6.0   | 130       | 2.49%   |
| 8.01-16.0  | 48        | 0.92%   |
| 2.01-3.0   | 22        | 0.42%   |
| 16.01-24.0 | 6         | 0.12%   |
| 4.01-5.0   | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 778       | 13.96%  |
| AU Optronics            | 646       | 11.59%  |
| LG Display              | 534       | 9.58%   |
| BOE                     | 422       | 7.57%   |
| Chimei Innolux          | 382       | 6.86%   |
| Dell                    | 335       | 6.01%   |
| Goldstar                | 308       | 5.53%   |
| Iiyama                  | 189       | 3.39%   |
| Philips                 | 180       | 3.23%   |
| BenQ                    | 143       | 2.57%   |
| Lenovo                  | 139       | 2.49%   |
| Hewlett-Packard         | 138       | 2.48%   |
| Acer                    | 131       | 2.35%   |
| AOC                     | 117       | 2.1%    |
| Chi Mei Optoelectronics | 113       | 2.03%   |
| Eizo                    | 86        | 1.54%   |
| NEC Computers           | 85        | 1.53%   |
| Ancor Communications    | 69        | 1.24%   |
| Sharp                   | 58        | 1.04%   |
| PANDA                   | 47        | 0.84%   |
| LG Philips              | 46        | 0.83%   |
| Sony                    | 41        | 0.74%   |
| InfoVision              | 37        | 0.66%   |
| Fujitsu Siemens         | 37        | 0.66%   |
| LG Electronics          | 34        | 0.61%   |
| Apple                   | 32        | 0.57%   |
| ASUSTek Computer        | 27        | 0.48%   |
| Unknown                 | 22        | 0.39%   |
| Toshiba                 | 18        | 0.32%   |
| MSI                     | 18        | 0.32%   |
| HannStar                | 18        | 0.32%   |
| Valve                   | 17        | 0.31%   |
| Idek Iiyama             | 17        | 0.31%   |
| CSO                     | 15        | 0.27%   |
| CPT                     | 15        | 0.27%   |
| ViewSonic               | 14        | 0.25%   |
| Panasonic               | 14        | 0.25%   |
| Gateway                 | 14        | 0.25%   |
| Belinea                 | 13        | 0.23%   |
| Mi                      | 10        | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 32        | 0.55%   |
| BOE LCD Monitor BOE0629 1366x768 309x173mm 13.9-inch                     | 31        | 0.53%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 28        | 0.48%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 28        | 0.48%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 26        | 0.45%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 25        | 0.43%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 24        | 0.41%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 21        | 0.36%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch     | 20        | 0.34%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 19        | 0.33%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 19        | 0.33%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                  | 18        | 0.31%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 18        | 0.31%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                  | 17        | 0.29%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 17        | 0.29%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 16        | 0.28%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 15        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 15        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 15        | 0.26%   |
| BOE LCD Monitor BOE06FB 1920x1080 344x194mm 15.5-inch                    | 15        | 0.26%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 15        | 0.26%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 14        | 0.24%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                  | 14        | 0.24%   |
| Philips 273PQPY PHLC096 1920x1080 597x336mm 27.0-inch                    | 14        | 0.24%   |
| AOC 24V2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                       | 14        | 0.24%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 13        | 0.22%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch             | 13        | 0.22%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 13        | 0.22%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 13        | 0.22%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 13        | 0.22%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 13        | 0.22%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 13        | 0.22%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 13        | 0.22%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 12        | 0.21%   |
| Iiyama PL2530H IVM6132 1920x1080 544x303mm 24.5-inch                     | 12        | 0.21%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 12        | 0.21%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 12        | 0.21%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 11        | 0.19%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 11        | 0.19%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 11        | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2252      | 42.8%   |
| 1366x768 (WXGA)    | 892       | 16.95%  |
| 2560x1440 (QHD)    | 249       | 4.73%   |
| 3840x2160 (4K)     | 242       | 4.6%    |
| 1280x1024 (SXGA)   | 232       | 4.41%   |
| 1600x900 (HD+)     | 228       | 4.33%   |
| 1280x800 (WXGA)    | 194       | 3.69%   |
| 1680x1050 (WSXGA+) | 189       | 3.59%   |
| 1920x1200 (WUXGA)  | 182       | 3.46%   |
| 1440x900 (WXGA+)   | 147       | 2.79%   |
| 3440x1440          | 54        | 1.03%   |
| Unknown            | 52        | 0.99%   |
| 2560x1080          | 42        | 0.8%    |
| 2560x1600          | 30        | 0.57%   |
| 1024x600           | 27        | 0.51%   |
| 1360x768           | 23        | 0.44%   |
| 1024x768 (XGA)     | 23        | 0.44%   |
| 1600x1200          | 21        | 0.4%    |
| 800x1280           | 18        | 0.34%   |
| 3840x1080          | 16        | 0.3%    |
| 2160x1440          | 12        | 0.23%   |
| 1920x540           | 12        | 0.23%   |
| 3840x2400          | 11        | 0.21%   |
| 2880x1800          | 10        | 0.19%   |
| 2288x1287          | 8         | 0.15%   |
| 3200x1800 (QHD+)   | 7         | 0.13%   |
| 1280x720 (HD)      | 7         | 0.13%   |
| 2048x1152          | 5         | 0.1%    |
| 1280x768           | 5         | 0.1%    |
| 5120x1440          | 4         | 0.08%   |
| 1680x945           | 4         | 0.08%   |
| 1400x1050          | 4         | 0.08%   |
| 1280x960           | 4         | 0.08%   |
| 3840x1600          | 3         | 0.06%   |
| 3840x1200          | 3         | 0.06%   |
| 3286x1080          | 3         | 0.06%   |
| 3200x2000          | 3         | 0.06%   |
| 3200x1080          | 3         | 0.06%   |
| 5760x1080          | 2         | 0.04%   |
| 4480x1440          | 2         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1500      | 26.98%  |
| 24      | 452       | 8.13%   |
| 13      | 434       | 7.81%   |
| 14      | 394       | 7.09%   |
| 23      | 364       | 6.55%   |
| 17      | 349       | 6.28%   |
| 27      | 342       | 6.15%   |
| 21      | 331       | 5.95%   |
| Unknown | 264       | 4.75%   |
| 19      | 198       | 3.56%   |
| 12      | 113       | 2.03%   |
| 22      | 111       | 2%      |
| 34      | 89        | 1.6%    |
| 18      | 78        | 1.4%    |
| 31      | 67        | 1.21%   |
| 11      | 53        | 0.95%   |
| 20      | 52        | 0.94%   |
| 25      | 35        | 0.63%   |
| 16      | 34        | 0.61%   |
| 10      | 31        | 0.56%   |
| 72      | 30        | 0.54%   |
| 84      | 29        | 0.52%   |
| 32      | 24        | 0.43%   |
| 40      | 23        | 0.41%   |
| 54      | 18        | 0.32%   |
| 7       | 15        | 0.27%   |
| 48      | 14        | 0.25%   |
| 65      | 12        | 0.22%   |
| 28      | 11        | 0.2%    |
| 46      | 10        | 0.18%   |
| 33      | 10        | 0.18%   |
| 43      | 8         | 0.14%   |
| 42      | 8         | 0.14%   |
| 142     | 7         | 0.13%   |
| 26      | 7         | 0.13%   |
| 37      | 5         | 0.09%   |
| 3       | 5         | 0.09%   |
| 49      | 4         | 0.07%   |
| 39      | 4         | 0.07%   |
| 29      | 4         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 2191      | 40.13%  |
| 501-600        | 1104      | 20.22%  |
| 401-500        | 630       | 11.54%  |
| 351-400        | 439       | 8.04%   |
| 201-300        | 390       | 7.14%   |
| Unknown        | 264       | 4.84%   |
| 701-800        | 124       | 2.27%   |
| 601-700        | 108       | 1.98%   |
| 1001-1500      | 71        | 1.3%    |
| 1501-2000      | 60        | 1.1%    |
| 801-900        | 36        | 0.66%   |
| 1-100          | 19        | 0.35%   |
| 901-1000       | 16        | 0.29%   |
| More than 2000 | 7         | 0.13%   |
| 101-200        | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 3564      | 71.32%  |
| 16/10   | 733       | 14.67%  |
| Unknown | 231       | 4.62%   |
| 5/4     | 220       | 4.4%    |
| 21/9    | 96        | 1.92%   |
| 3/2     | 57        | 1.14%   |
| 4/3     | 53        | 1.06%   |
| 0.67    | 15        | 0.3%    |
| 6/5     | 9         | 0.18%   |
| 32/9    | 9         | 0.18%   |
| 1.00    | 7         | 0.14%   |
| 0.56    | 2         | 0.04%   |
| 0.62    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1493      | 27.08%  |
| 201-250        | 972       | 17.63%  |
| 81-90          | 659       | 11.95%  |
| 301-350        | 348       | 6.31%   |
| 151-200        | 327       | 5.93%   |
| Unknown        | 264       | 4.79%   |
| 251-300        | 228       | 4.13%   |
| 121-130        | 205       | 3.72%   |
| 351-500        | 201       | 3.65%   |
| 71-80          | 162       | 2.94%   |
| 141-150        | 157       | 2.85%   |
| More than 1000 | 122       | 2.21%   |
| 61-70          | 108       | 1.96%   |
| 501-1000       | 66        | 1.2%    |
| 51-60          | 53        | 0.96%   |
| 131-140        | 48        | 0.87%   |
| 41-50          | 31        | 0.56%   |
| 111-120        | 28        | 0.51%   |
| 91-100         | 22        | 0.4%    |
| 1-40           | 20        | 0.36%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1844      | 34.44%  |
| 121-160       | 1468      | 27.42%  |
| 101-120       | 1360      | 25.4%   |
| Unknown       | 264       | 4.93%   |
| 161-240       | 229       | 4.28%   |
| 1-50          | 110       | 2.05%   |
| More than 240 | 79        | 1.48%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 4049      | 78.39%  |
| 2     | 774       | 14.99%  |
| 0     | 209       | 4.05%   |
| 3     | 115       | 2.23%   |
| 4     | 16        | 0.31%   |
| 6     | 1         | 0.02%   |
| 5     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2584      | 33.29%  |
| Intel                                  | 2464      | 31.75%  |
| Qualcomm Atheros                       | 918       | 11.83%  |
| Broadcom                               | 442       | 5.7%    |
| Broadcom Limited                       | 128       | 1.65%   |
| TP-Link                                | 119       | 1.53%   |
| Marvell Technology Group               | 93        | 1.2%    |
| Huawei Technologies                    | 88        | 1.13%   |
| Dell                                   | 83        | 1.07%   |
| MediaTek                               | 82        | 1.06%   |
| Ralink                                 | 73        | 0.94%   |
| Ralink Technology                      | 70        | 0.9%    |
| Nvidia                                 | 65        | 0.84%   |
| Qualcomm Atheros Communications        | 55        | 0.71%   |
| Samsung Electronics                    | 42        | 0.54%   |
| Xiaomi                                 | 36        | 0.46%   |
| Microsoft                              | 34        | 0.44%   |
| Ericsson Business Mobile Networks      | 30        | 0.39%   |
| ASUSTek Computer                       | 29        | 0.37%   |
| Hewlett-Packard                        | 24        | 0.31%   |
| ASIX Electronics                       | 21        | 0.27%   |
| Sierra Wireless                        | 19        | 0.24%   |
| JMicron Technology                     | 17        | 0.22%   |
| Lenovo                                 | 16        | 0.21%   |
| NetGear                                | 12        | 0.15%   |
| Edimax Technology                      | 12        | 0.15%   |
| Aquantia                               | 12        | 0.15%   |
| VIA Technologies                       | 11        | 0.14%   |
| Motorola PCS                           | 11        | 0.14%   |
| Fibocom                                | 11        | 0.14%   |
| DisplayLink                            | 10        | 0.13%   |
| Silicon Integrated Systems [SiS]       | 9         | 0.12%   |
| Qualcomm                               | 9         | 0.12%   |
| D-Link                                 | 9         | 0.12%   |
| ZTE WCDMA Technologies MSM             | 8         | 0.1%    |
| OPPO Electronics                       | 6         | 0.08%   |
| Microchip Technology                   | 6         | 0.08%   |
| HTC (High Tech Computer)               | 6         | 0.08%   |
| Texas Instruments                      | 5         | 0.06%   |
| Sony Ericsson Mobile Communications AB | 5         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1863      | 20.49%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 268       | 2.95%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 245       | 2.69%   |
| Intel Wi-Fi 6 AX200                                               | 173       | 1.9%    |
| Intel Wireless 8265 / 8275                                        | 149       | 1.64%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 135       | 1.48%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 122       | 1.34%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 119       | 1.31%   |
| Intel Wireless 7260                                               | 118       | 1.3%    |
| Intel Wireless 8260                                               | 105       | 1.15%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 103       | 1.13%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 100       | 1.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 100       | 1.1%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 94        | 1.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 91        | 1%      |
| Intel Ethernet Connection I217-LM                                 | 86        | 0.95%   |
| Realtek RTL8125 2.5GbE Controller                                 | 85        | 0.93%   |
| Intel Wi-Fi 6 AX201                                               | 85        | 0.93%   |
| Intel Wireless 7265                                               | 84        | 0.92%   |
| Intel I211 Gigabit Network Connection                             | 83        | 0.91%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 83        | 0.91%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 75        | 0.82%   |
| Intel Wireless 3160                                               | 69        | 0.76%   |
| Intel Ethernet Connection (2) I219-V                              | 66        | 0.73%   |
| Intel Wireless 3165                                               | 65        | 0.71%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 63        | 0.69%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 59        | 0.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 58        | 0.64%   |
| Intel 82579V Gigabit Network Connection                           | 58        | 0.64%   |
| Intel 82567LM Gigabit Network Connection                          | 55        | 0.6%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 54        | 0.59%   |
| Intel Ethernet Connection (4) I219-LM                             | 53        | 0.58%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 53        | 0.58%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 52        | 0.57%   |
| Broadcom BCM43142 802.11b/g/n                                     | 52        | 0.57%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 51        | 0.56%   |
| Intel Centrino Ultimate-N 6300                                    | 50        | 0.55%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 48        | 0.53%   |
| Huawei E353/E3131                                                 | 47        | 0.52%   |
| Intel WiFi Link 5100                                              | 46        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1893      | 46.76%  |
| Qualcomm Atheros                | 699       | 17.27%  |
| Realtek Semiconductor           | 527       | 13.02%  |
| Broadcom                        | 265       | 6.55%   |
| TP-Link                         | 114       | 2.82%   |
| MediaTek                        | 78        | 1.93%   |
| Ralink                          | 73        | 1.8%    |
| Ralink Technology               | 70        | 1.73%   |
| Broadcom Limited                | 63        | 1.56%   |
| Qualcomm Atheros Communications | 55        | 1.36%   |
| Dell                            | 52        | 1.28%   |
| Microsoft                       | 33        | 0.82%   |
| ASUSTek Computer                | 29        | 0.72%   |
| Sierra Wireless                 | 19        | 0.47%   |
| Edimax Technology               | 12        | 0.3%    |
| Fibocom                         | 11        | 0.27%   |
| D-Link                          | 9         | 0.22%   |
| NetGear                         | 8         | 0.2%    |
| Qualcomm                        | 6         | 0.15%   |
| Hewlett-Packard                 | 6         | 0.15%   |
| Sagem                           | 4         | 0.1%    |
| D-Link System                   | 3         | 0.07%   |
| Belkin Components               | 3         | 0.07%   |
| ZyXEL Communications            | 2         | 0.05%   |
| ZyDAS                           | 2         | 0.05%   |
| Marvell Technology Group        | 2         | 0.05%   |
| Linksys                         | 2         | 0.05%   |
| Z-Com                           | 1         | 0.02%   |
| Wacom                           | 1         | 0.02%   |
| Tenda                           | 1         | 0.02%   |
| Sweex                           | 1         | 0.02%   |
| Ovislink                        | 1         | 0.02%   |
| IMC Networks                    | 1         | 0.02%   |
| AVM                             | 1         | 0.02%   |
| Accton Technology               | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 173       | 4.26%   |
| Intel Wireless 8265 / 8275                                              | 149       | 3.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 135       | 3.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 122       | 3%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 119       | 2.93%   |
| Intel Wireless 7260                                                     | 118       | 2.91%   |
| Intel Wireless 8260                                                     | 105       | 2.59%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 103       | 2.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 100       | 2.46%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 94        | 2.32%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 91        | 2.24%   |
| Intel Wi-Fi 6 AX201                                                     | 85        | 2.09%   |
| Intel Wireless 7265                                                     | 84        | 2.07%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 83        | 2.04%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 75        | 1.85%   |
| Intel Wireless 3160                                                     | 69        | 1.7%    |
| Intel Wireless 3165                                                     | 65        | 1.6%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 63        | 1.55%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 59        | 1.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 58        | 1.43%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 54        | 1.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 53        | 1.31%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 52        | 1.28%   |
| Broadcom BCM43142 802.11b/g/n                                           | 52        | 1.28%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 51        | 1.26%   |
| Intel Centrino Ultimate-N 6300                                          | 50        | 1.23%   |
| Intel WiFi Link 5100                                                    | 46        | 1.13%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 46        | 1.13%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 44        | 1.08%   |
| Intel Wireless-AC 9260                                                  | 44        | 1.08%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 43        | 1.06%   |
| Qualcomm Atheros AR9271 802.11n                                         | 42        | 1.03%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 41        | 1.01%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 38        | 0.94%   |
| Intel Centrino Advanced-N 6235                                          | 37        | 0.91%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 37        | 0.91%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 34        | 0.84%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 33        | 0.81%   |
| Intel Centrino Advanced-N 6200                                          | 33        | 0.81%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 32        | 0.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2366      | 49.29%  |
| Intel                                  | 1348      | 28.08%  |
| Qualcomm Atheros                       | 322       | 6.71%   |
| Broadcom                               | 219       | 4.56%   |
| Marvell Technology Group               | 92        | 1.92%   |
| Broadcom Limited                       | 66        | 1.38%   |
| Nvidia                                 | 65        | 1.35%   |
| Huawei Technologies                    | 58        | 1.21%   |
| Samsung Electronics                    | 40        | 0.83%   |
| Xiaomi                                 | 35        | 0.73%   |
| ASIX Electronics                       | 21        | 0.44%   |
| JMicron Technology                     | 17        | 0.35%   |
| Lenovo                                 | 16        | 0.33%   |
| Aquantia                               | 12        | 0.25%   |
| VIA Technologies                       | 11        | 0.23%   |
| Motorola PCS                           | 10        | 0.21%   |
| DisplayLink                            | 10        | 0.21%   |
| Silicon Integrated Systems [SiS]       | 9         | 0.19%   |
| ZTE WCDMA Technologies MSM             | 7         | 0.15%   |
| TP-Link                                | 6         | 0.13%   |
| OPPO Electronics                       | 6         | 0.13%   |
| Microchip Technology                   | 6         | 0.13%   |
| HTC (High Tech Computer)               | 6         | 0.13%   |
| Sony Ericsson Mobile Communications AB | 4         | 0.08%   |
| NetGear                                | 4         | 0.08%   |
| ICS Advent                             | 4         | 0.08%   |
| Hewlett-Packard                        | 4         | 0.08%   |
| Attansic Technology                    | 4         | 0.08%   |
| Qualcomm                               | 3         | 0.06%   |
| OnePlus Technology (Shenzhen)          | 3         | 0.06%   |
| MediaTek                               | 3         | 0.06%   |
| Apple                                  | 3         | 0.06%   |
| Research In Motion                     | 2         | 0.04%   |
| QLogic                                 | 2         | 0.04%   |
| NetXen Incorporated                    | 2         | 0.04%   |
| Google                                 | 2         | 0.04%   |
| 3Com                                   | 2         | 0.04%   |
| QinHeng Electronics                    | 1         | 0.02%   |
| Mellanox Technologies                  | 1         | 0.02%   |
| LG Electronics                         | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1863      | 38.21%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 268       | 5.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 245       | 5.02%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 100       | 2.05%   |
| Intel Ethernet Connection I217-LM                                 | 86        | 1.76%   |
| Realtek RTL8125 2.5GbE Controller                                 | 85        | 1.74%   |
| Intel I211 Gigabit Network Connection                             | 83        | 1.7%    |
| Intel Ethernet Connection (2) I219-V                              | 66        | 1.35%   |
| Intel 82579V Gigabit Network Connection                           | 58        | 1.19%   |
| Intel 82567LM Gigabit Network Connection                          | 55        | 1.13%   |
| Intel Ethernet Connection (4) I219-LM                             | 53        | 1.09%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 48        | 0.98%   |
| Huawei E353/E3131                                                 | 47        | 0.96%   |
| Intel Ethernet Connection I218-LM                                 | 46        | 0.94%   |
| Intel 82577LM Gigabit Network Connection                          | 42        | 0.86%   |
| Intel Ethernet Connection (7) I219-V                              | 41        | 0.84%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 40        | 0.82%   |
| Intel Ethernet Connection (2) I219-LM                             | 38        | 0.78%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 37        | 0.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 37        | 0.76%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 36        | 0.74%   |
| Intel Ethernet Connection (7) I219-LM                             | 34        | 0.7%    |
| Intel Ethernet Connection (6) I219-V                              | 32        | 0.66%   |
| Intel Ethernet Connection I219-LM                                 | 31        | 0.64%   |
| Intel Ethernet Connection (3) I218-LM                             | 31        | 0.64%   |
| Nvidia MCP61 Ethernet                                             | 30        | 0.62%   |
| Intel Ethernet Controller I225-V                                  | 28        | 0.57%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 27        | 0.55%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 27        | 0.55%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 26        | 0.53%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 25        | 0.51%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 25        | 0.51%   |
| Intel Ethernet Connection (4) I219-V                              | 25        | 0.51%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 24        | 0.49%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 22        | 0.45%   |
| Intel Ethernet Connection (2) I218-V                              | 22        | 0.45%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 22        | 0.45%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 21        | 0.43%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 21        | 0.43%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 20        | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 4500      | 53.24%  |
| WiFi     | 3800      | 44.96%  |
| Modem    | 136       | 1.61%   |
| Unknown  | 16        | 0.19%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2931      | 57.17%  |
| Ethernet | 2195      | 42.81%  |
| Unknown  | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2940      | 58.31%  |
| 1     | 1897      | 37.62%  |
| 0     | 107       | 2.12%   |
| 3     | 68        | 1.35%   |
| 4     | 15        | 0.3%    |
| 6     | 5         | 0.1%    |
| 5     | 5         | 0.1%    |
| 17    | 1         | 0.02%   |
| 10    | 1         | 0.02%   |
| 9     | 1         | 0.02%   |
| 8     | 1         | 0.02%   |
| 7     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4694      | 92.66%  |
| Yes  | 372       | 7.34%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1344      | 45.85%  |
| Qualcomm Atheros Communications | 260       | 8.87%   |
| Realtek Semiconductor           | 202       | 6.89%   |
| Broadcom                        | 190       | 6.48%   |
| Cambridge Silicon Radio         | 184       | 6.28%   |
| IMC Networks                    | 133       | 4.54%   |
| ASUSTek Computer                | 98        | 3.34%   |
| Dell                            | 89        | 3.04%   |
| Foxconn / Hon Hai               | 86        | 2.93%   |
| Lite-On Technology              | 74        | 2.52%   |
| Hewlett-Packard                 | 62        | 2.12%   |
| Apple                           | 41        | 1.4%    |
| Toshiba                         | 31        | 1.06%   |
| Ralink                          | 21        | 0.72%   |
| Realtek                         | 18        | 0.61%   |
| Foxconn International           | 17        | 0.58%   |
| TP-Link                         | 13        | 0.44%   |
| MediaTek                        | 12        | 0.41%   |
| Alps Electric                   | 8         | 0.27%   |
| Integrated System Solution      | 7         | 0.24%   |
| Chicony Electronics             | 6         | 0.2%    |
| Taiyo Yuden                     | 5         | 0.17%   |
| Edimax Technology               | 5         | 0.17%   |
| Ralink Technology               | 3         | 0.1%    |
| Conwise Technology              | 3         | 0.1%    |
| Unknown                         | 3         | 0.1%    |
| USI                             | 2         | 0.07%   |
| Opticis                         | 2         | 0.07%   |
| Micro Star International        | 2         | 0.07%   |
| Belkin Components               | 2         | 0.07%   |
| Askey Computer                  | 2         | 0.07%   |
| SINO WEALTH                     | 1         | 0.03%   |
| Marvell Semiconductor           | 1         | 0.03%   |
| Logitech                        | 1         | 0.03%   |
| Fujitsu                         | 1         | 0.03%   |
| Creative Technology             | 1         | 0.03%   |
| AboCom Systems                  | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 580       | 19.77%  |
| Intel AX201 Bluetooth                               | 189       | 6.44%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 184       | 6.27%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 172       | 5.86%   |
| Intel AX200 Bluetooth                               | 166       | 5.66%   |
| Realtek Bluetooth Radio                             | 132       | 4.5%    |
| Qualcomm Atheros  Bluetooth Device                  | 111       | 3.78%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 64        | 2.18%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 57        | 1.94%   |
| IMC Networks Bluetooth Radio                        | 57        | 1.94%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 53        | 1.81%   |
| Intel Wireless-AC 3168 Bluetooth                    | 52        | 1.77%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 49        | 1.67%   |
| Realtek  Bluetooth 4.2 Adapter                      | 39        | 1.33%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 39        | 1.33%   |
| Broadcom BCM2045B (BDC-2.1)                         | 39        | 1.33%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 35        | 1.19%   |
| Intel Bluetooth Device                              | 30        | 1.02%   |
| Dell BCM20702A0 Bluetooth Module                    | 29        | 0.99%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 27        | 0.92%   |
| Intel AX210 Bluetooth                               | 26        | 0.89%   |
| IMC Networks Wireless_Device                        | 26        | 0.89%   |
| HP Broadcom 2070 Bluetooth Combo                    | 26        | 0.89%   |
| Dell DW375 Bluetooth Module                         | 25        | 0.85%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 25        | 0.85%   |
| IMC Networks Bluetooth Device                       | 24        | 0.82%   |
| Lite-On Bluetooth Device                            | 23        | 0.78%   |
| Ralink RT3290 Bluetooth                             | 21        | 0.72%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 21        | 0.72%   |
| Realtek RTL8723B Bluetooth                          | 20        | 0.68%   |
| Apple Bluetooth Host Controller                     | 19        | 0.65%   |
| Realtek Bluetooth Radio                             | 18        | 0.61%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 18        | 0.61%   |
| Broadcom BCM2070 Bluetooth Device                   | 18        | 0.61%   |
| Lite-On Atheros AR3012 Bluetooth                    | 17        | 0.58%   |
| Foxconn International BCM43142A0 Bluetooth module   | 17        | 0.58%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 16        | 0.55%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 14        | 0.48%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 14        | 0.48%   |
| Foxconn / Hon Hai Bluetooth Device                  | 14        | 0.48%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 3617      | 52.2%   |
| AMD                                  | 1386      | 20%     |
| Nvidia                               | 1235      | 17.82%  |
| C-Media Electronics                  | 100       | 1.44%   |
| Creative Labs                        | 86        | 1.24%   |
| Creative Technology                  | 50        | 0.72%   |
| Logitech                             | 31        | 0.45%   |
| Realtek Semiconductor                | 26        | 0.38%   |
| JMTek                                | 24        | 0.35%   |
| VIA Technologies                     | 22        | 0.32%   |
| Texas Instruments                    | 20        | 0.29%   |
| Lenovo                               | 19        | 0.27%   |
| SteelSeries ApS                      | 18        | 0.26%   |
| Plantronics                          | 18        | 0.26%   |
| Kingston Technology                  | 16        | 0.23%   |
| GN Netcom                            | 15        | 0.22%   |
| GYROCOM C&C                          | 12        | 0.17%   |
| Generalplus Technology               | 12        | 0.17%   |
| Dell                                 | 12        | 0.17%   |
| Silicon Integrated Systems [SiS]     | 11        | 0.16%   |
| ASUSTek Computer                     | 10        | 0.14%   |
| SAVITECH                             | 9         | 0.13%   |
| Hewlett-Packard                      | 9         | 0.13%   |
| BEHRINGER International              | 8         | 0.12%   |
| Razer USA                            | 7         | 0.1%    |
| Focusrite-Novation                   | 7         | 0.1%    |
| Sony                                 | 6         | 0.09%   |
| Samson Technologies                  | 6         | 0.09%   |
| RODE Microphones                     | 5         | 0.07%   |
| AudioQuest                           | 5         | 0.07%   |
| Valve Software                       | 4         | 0.06%   |
| USB MICROPHONE                       | 4         | 0.06%   |
| Trust                                | 4         | 0.06%   |
| Thesycon Systemsoftware & Consulting | 4         | 0.06%   |
| Micro Star International             | 4         | 0.06%   |
| M-Audio                              | 4         | 0.06%   |
| AOKEO                                | 4         | 0.06%   |
| Sennheiser Communications            | 3         | 0.04%   |
| ROCCAT                               | 3         | 0.04%   |
| PreSonus Audio Electronics           | 3         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 397       | 4.85%   |
| AMD Family 17h/19h HD Audio Controller                                     | 378       | 4.62%   |
| Intel Sunrise Point-LP HD Audio                                            | 315       | 3.85%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 315       | 3.85%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 263       | 3.22%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 227       | 2.78%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 213       | 2.6%    |
| Intel Cannon Lake PCH cAVS                                                 | 199       | 2.43%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 197       | 2.41%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 173       | 2.12%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 170       | 2.08%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 168       | 2.05%   |
| AMD Starship/Matisse HD Audio Controller                                   | 168       | 2.05%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 160       | 1.96%   |
| AMD FCH Azalia Controller                                                  | 158       | 1.93%   |
| Intel 8 Series HD Audio Controller                                         | 143       | 1.75%   |
| Intel Haswell-ULT HD Audio Controller                                      | 141       | 1.72%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 137       | 1.68%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 126       | 1.54%   |
| Nvidia GP107GL High Definition Audio Controller                            | 119       | 1.45%   |
| Intel Broadwell-U Audio Controller                                         | 119       | 1.45%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 119       | 1.45%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 117       | 1.43%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 109       | 1.33%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 108       | 1.32%   |
| Nvidia GF108 High Definition Audio Controller                              | 96        | 1.17%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 92        | 1.12%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 87        | 1.06%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 79        | 0.97%   |
| Nvidia GP106 High Definition Audio Controller                              | 77        | 0.94%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 75        | 0.92%   |
| Intel 200 Series PCH HD Audio                                              | 72        | 0.88%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 69        | 0.84%   |
| Nvidia TU116 High Definition Audio Controller                              | 65        | 0.79%   |
| Intel CM238 HD Audio Controller                                            | 63        | 0.77%   |
| Nvidia High Definition Audio Controller                                    | 58        | 0.71%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 58        | 0.71%   |
| AMD Kabini HDMI/DP Audio                                                   | 58        | 0.71%   |
| Nvidia GP104 High Definition Audio Controller                              | 57        | 0.7%    |
| Intel Comet Lake PCH-LP cAVS                                               | 56        | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 802       | 21.27%  |
| SK hynix                     | 625       | 16.57%  |
| Kingston                     | 495       | 13.13%  |
| Unknown                      | 425       | 11.27%  |
| Micron Technology            | 318       | 8.43%   |
| GOODRAM                      | 234       | 6.21%   |
| Crucial                      | 166       | 4.4%    |
| G.Skill                      | 109       | 2.89%   |
| Corsair                      | 91        | 2.41%   |
| A-DATA Technology            | 79        | 2.09%   |
| Ramaxel Technology           | 71        | 1.88%   |
| Nanya Technology             | 58        | 1.54%   |
| Patriot                      | 56        | 1.49%   |
| Elpida                       | 52        | 1.38%   |
| Unknown                      | 26        | 0.69%   |
| Unknown (ABCD)               | 20        | 0.53%   |
| Wilk                         | 17        | 0.45%   |
| Qimonda                      | 13        | 0.34%   |
| Apacer                       | 12        | 0.32%   |
| Wilk Elektronik              | 10        | 0.27%   |
| GeIL                         | 10        | 0.27%   |
| ASint Technology             | 9         | 0.24%   |
| Silicon Power                | 6         | 0.16%   |
| Patriot Memory (PDP Systems) | 5         | 0.13%   |
| 48spaces                     | 5         | 0.13%   |
| Unifosa                      | 4         | 0.11%   |
| Transcend                    | 4         | 0.11%   |
| Team                         | 4         | 0.11%   |
| fef5                         | 4         | 0.11%   |
| Toshiba                      | 3         | 0.08%   |
| OCZ                          | 3         | 0.08%   |
| SHARETRONIC                  | 2         | 0.05%   |
| PNY                          | 2         | 0.05%   |
| KingFast                     | 2         | 0.05%   |
| ff                           | 2         | 0.05%   |
| AMD                          | 2         | 0.05%   |
| Aeneon                       | 2         | 0.05%   |
| 4ea5                         | 2         | 0.05%   |
| Unknown (8A02)               | 1         | 0.03%   |
| Unknown (768A)               | 1         | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 42        | 1.02%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s            | 37        | 0.9%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 34        | 0.82%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 32        | 0.78%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 31        | 0.75%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 30        | 0.73%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 29        | 0.7%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 29        | 0.7%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 28        | 0.68%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 27        | 0.65%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 26        | 0.63%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 26        | 0.63%   |
| Unknown                                                          | 26        | 0.63%   |
| GOODRAM RAM GR2666S464L19/16G 16GB SODIMM DDR4 2667MT/s          | 25        | 0.61%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 24        | 0.58%   |
| GOODRAM RAM GR3200S464L22/16G 16GB SODIMM DDR4 3200MT/s          | 22        | 0.53%   |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s         | 21        | 0.51%   |
| Kingston RAM 9905403-559.A00LF 8GB DIMM DDR3 1600MT/s            | 19        | 0.46%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                           | 18        | 0.44%   |
| Samsung RAM M471A2K43DB1-CWE 16384MB SODIMM DDR4 3200MT/s        | 17        | 0.41%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s            | 16        | 0.39%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 16        | 0.39%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 16        | 0.39%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 16        | 0.39%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 16        | 0.39%   |
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3266MT/s              | 16        | 0.39%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s            | 16        | 0.39%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 15        | 0.36%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 15        | 0.36%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 15        | 0.36%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 15        | 0.36%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 14        | 0.34%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 14        | 0.34%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 14        | 0.34%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 14        | 0.34%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 14        | 0.34%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s              | 14        | 0.34%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 14        | 0.34%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 13        | 0.32%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 13        | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1281      | 40.13%  |
| DDR3    | 1170      | 36.65%  |
| DDR2    | 242       | 7.58%   |
| Unknown | 152       | 4.76%   |
| SDRAM   | 139       | 4.35%   |
| LPDDR4  | 79        | 2.47%   |
| LPDDR3  | 44        | 1.38%   |
| DDR5    | 32        | 1%      |
| DDR     | 32        | 1%      |
| LPDDR5  | 13        | 0.41%   |
| DRAM    | 8         | 0.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| SODIMM          | 1896      | 60.44%  |
| DIMM            | 1099      | 35.03%  |
| Row Of Chips    | 113       | 3.6%    |
| Unknown         | 13        | 0.41%   |
| Chip            | 12        | 0.38%   |
| RIMM            | 2         | 0.06%   |
| Proprietary Car | 1         | 0.03%   |
| FB-DIMM         | 1         | 0.03%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 8192    | 1123      | 31.88%  |
| 4096    | 959       | 27.22%  |
| 2048    | 584       | 16.58%  |
| 16384   | 497       | 14.11%  |
| 1024    | 208       | 5.9%    |
| 32768   | 114       | 3.24%   |
| 512     | 27        | 0.77%   |
| Unknown | 4         | 0.11%   |
| 131072  | 2         | 0.06%   |
| 1536    | 2         | 0.06%   |
| 256     | 2         | 0.06%   |
| 64      | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 800       | 22.84%  |
| 2667    | 434       | 12.39%  |
| 3200    | 433       | 12.36%  |
| 1333    | 225       | 6.42%   |
| 2400    | 211       | 6.02%   |
| 1334    | 147       | 4.2%    |
| 2133    | 139       | 3.97%   |
| 667     | 133       | 3.8%    |
| 800     | 126       | 3.6%    |
| 3600    | 88        | 2.51%   |
| Unknown | 80        | 2.28%   |
| 1067    | 57        | 1.63%   |
| 4199    | 45        | 1.28%   |
| 1867    | 43        | 1.23%   |
| 3266    | 34        | 0.97%   |
| 533     | 32        | 0.91%   |
| 3000    | 29        | 0.83%   |
| 1066    | 29        | 0.83%   |
| 2048    | 28        | 0.8%    |
| 975     | 27        | 0.77%   |
| 4800    | 26        | 0.74%   |
| 4267    | 23        | 0.66%   |
| 400     | 22        | 0.63%   |
| 1800    | 21        | 0.6%    |
| 1866    | 20        | 0.57%   |
| 3400    | 19        | 0.54%   |
| 2933    | 19        | 0.54%   |
| 3866    | 17        | 0.49%   |
| 3733    | 15        | 0.43%   |
| 6400    | 14        | 0.4%    |
| 2666    | 14        | 0.4%    |
| 8400    | 11        | 0.31%   |
| 3533    | 11        | 0.31%   |
| 3333    | 10        | 0.29%   |
| 333     | 10        | 0.29%   |
| 3800    | 9         | 0.26%   |
| 2866    | 8         | 0.23%   |
| 4266    | 7         | 0.2%    |
| 3933    | 7         | 0.2%    |
| 3466    | 6         | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 52        | 46.02%  |
| Samsung Electronics   | 15        | 13.27%  |
| Brother Industries    | 12        | 10.62%  |
| Canon                 | 10        | 8.85%   |
| Seiko Epson           | 7         | 6.19%   |
| Prolific Technology   | 5         | 4.42%   |
| Lexmark International | 4         | 3.54%   |
| Zebra                 | 3         | 2.65%   |
| Xerox                 | 2         | 1.77%   |
| Minolta               | 1         | 0.88%   |
| MIIIW                 | 1         | 0.88%   |
| Datamax-O'Neil        | 1         | 0.88%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port           | 5         | 4.35%   |
| HP LaserJet 1020                        | 5         | 4.35%   |
| Samsung M2020 Series                    | 3         | 2.61%   |
| HP LaserJet P2015 series                | 3         | 2.61%   |
| HP LaserJet M14-M17                     | 3         | 2.61%   |
| Canon iP7200 series                     | 3         | 2.61%   |
| Seiko Epson AL-M310DN                   | 2         | 1.74%   |
| Samsung SCX-3400 Series                 | 2         | 1.74%   |
| Samsung ML-216x Series Laser Printer    | 2         | 1.74%   |
| Samsung ML-2010P Mono Laser Printer     | 2         | 1.74%   |
| HP LaserJet P1102                       | 2         | 1.74%   |
| HP Deskjet F4500 series                 | 2         | 1.74%   |
| HP DeskJet F4100 Printer series         | 2         | 1.74%   |
| HP Deskjet F2280 series                 | 2         | 1.74%   |
| HP DeskJet 845c                         | 2         | 1.74%   |
| HP DeskJet 840c                         | 2         | 1.74%   |
| HP DeskJet 4530 series                  | 2         | 1.74%   |
| HP DeskJet 3700 series                  | 2         | 1.74%   |
| HP DeskJet 2600 series                  | 2         | 1.74%   |
| HP Deskjet 2540 series                  | 2         | 1.74%   |
| HP Deskjet 1050 J410                    | 2         | 1.74%   |
| Canon MG5600 series                     | 2         | 1.74%   |
| Canon LiDE 400                          | 2         | 1.74%   |
| Brother DCP-J105                        | 2         | 1.74%   |
| Brother DCP-1610W                       | 2         | 1.74%   |
| Zebra ZTC GX420t                        | 1         | 0.87%   |
| Zebra LP2844 Printer                    | 1         | 0.87%   |
| Zebra LP2824                            | 1         | 0.87%   |
| Xerox WorkCentre PE16                   | 1         | 0.87%   |
| Xerox Phaser 6000B                      | 1         | 0.87%   |
| Seiko Epson Stylus NX230/SX235W Series  | 1         | 0.87%   |
| Seiko Epson L405 Series                 | 1         | 0.87%   |
| Seiko Epson L396 Series                 | 1         | 0.87%   |
| Seiko Epson L1110 Series                | 1         | 0.87%   |
| Seiko Epson ET-2710 Series              | 1         | 0.87%   |
| Samsung Xerox Phaser 3117 Laser Printer | 1         | 0.87%   |
| Samsung SCX-6545 Series                 | 1         | 0.87%   |
| Samsung SCX-4300 Series                 | 1         | 0.87%   |
| Samsung SCX-4200 series                 | 1         | 0.87%   |
| Samsung ML-3050/ML-3051 Laser Printer   | 1         | 0.87%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Canon                       | 13        | 61.9%   |
| Seiko Epson                 | 2         | 9.52%   |
| Plustek                     | 2         | 9.52%   |
| Ultima Electronics          | 1         | 4.76%   |
| Mustek Systems              | 1         | 4.76%   |
| Microtek International      | 1         | 4.76%   |
| Acer Peripherals (now BenQ) | 1         | 4.76%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 210                                  | 5         | 23.81%  |
| Canon CanoScan N670U/N676U/LiDE 20                       | 2         | 9.52%   |
| Canon CanoScan LiDE 120                                  | 2         | 9.52%   |
| Canon CanoScan LiDE 110                                  | 2         | 9.52%   |
| Ultima Artec E+ 48U                                      | 1         | 4.76%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]      | 1         | 4.76%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 4.76%   |
| Plustek OpticSlim 1200 Scanner                           | 1         | 4.76%   |
| Plustek OpticPro 1248U Scanner #2                        | 1         | 4.76%   |
| Mustek Systems BearPaw 2448 TA Pro                       | 1         | 4.76%   |
| Microtek International USB1200 Scanner                   | 1         | 4.76%   |
| Canon CanoScan N1240U/LiDE 30                            | 1         | 4.76%   |
| Canon CanoScan LIDE 25                                   | 1         | 4.76%   |
| Acer Peripherals (now BenQ) S2W 3300U/4300U              | 1         | 4.76%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 651       | 22.34%  |
| Microdia                               | 286       | 9.81%   |
| IMC Networks                           | 275       | 9.44%   |
| Realtek Semiconductor                  | 245       | 8.41%   |
| Bison Electronics                      | 158       | 5.42%   |
| Sunplus Innovation Technology          | 147       | 5.04%   |
| Quanta                                 | 132       | 4.53%   |
| Suyin                                  | 117       | 4.02%   |
| Logitech                               | 113       | 3.88%   |
| Cheng Uei Precision Industry (Foxlink) | 93        | 3.19%   |
| Syntek                                 | 86        | 2.95%   |
| Acer                                   | 66        | 2.26%   |
| Lite-On Technology                     | 65        | 2.23%   |
| Silicon Motion                         | 58        | 1.99%   |
| Apple                                  | 41        | 1.41%   |
| Creative Technology                    | 35        | 1.2%    |
| Luxvisions Innotech Limited            | 33        | 1.13%   |
| Ricoh                                  | 32        | 1.1%    |
| Alcor Micro                            | 31        | 1.06%   |
| Lenovo                                 | 28        | 0.96%   |
| Z-Star Microelectronics                | 23        | 0.79%   |
| Samsung Electronics                    | 23        | 0.79%   |
| Microsoft                              | 20        | 0.69%   |
| Sonix Technology                       | 13        | 0.45%   |
| Intel                                  | 11        | 0.38%   |
| DigiTech                               | 11        | 0.38%   |
| Generalplus Technology                 | 9         | 0.31%   |
| ALi                                    | 9         | 0.31%   |
| Primax Electronics                     | 8         | 0.27%   |
| Cubeternet                             | 8         | 0.27%   |
| Hewlett-Packard                        | 7         | 0.24%   |
| Jieli Technology                       | 6         | 0.21%   |
| Importek                               | 5         | 0.17%   |
| Trust                                  | 4         | 0.14%   |
| Sunplus Technology                     | 4         | 0.14%   |
| Razer USA                              | 4         | 0.14%   |
| MacroSilicon                           | 4         | 0.14%   |
| LG Electronics                         | 4         | 0.14%   |
| GEMBIRD                                | 4         | 0.14%   |
| Aveo Technology                        | 4         | 0.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 129       | 4.41%   |
| Microdia Integrated_Webcam_HD            | 91        | 3.11%   |
| Realtek Integrated_Webcam_HD             | 78        | 2.67%   |
| IMC Networks Integrated Camera           | 75        | 2.56%   |
| IMC Networks USB2.0 HD UVC WebCam        | 68        | 2.32%   |
| Sunplus Integrated_Webcam_HD             | 65        | 2.22%   |
| Chicony Lenovo EasyCamera                | 48        | 1.64%   |
| Microdia Integrated Webcam               | 43        | 1.47%   |
| Chicony HD WebCam                        | 40        | 1.37%   |
| Suyin Integrated_Webcam_HD               | 36        | 1.23%   |
| Syntek Integrated Camera                 | 35        | 1.2%    |
| Syntek Lenovo EasyCamera                 | 31        | 1.06%   |
| Bison Integrated Camera                  | 31        | 1.06%   |
| Realtek Lenovo EasyCamera                | 29        | 0.99%   |
| Lite-On Integrated Camera                | 29        | 0.99%   |
| Quanta HP TrueVision HD Camera           | 28        | 0.96%   |
| Logitech Webcam C270                     | 27        | 0.92%   |
| Chicony HP HD Camera                     | 26        | 0.89%   |
| Bison Lenovo EasyCamera                  | 26        | 0.89%   |
| Realtek USB Camera                       | 25        | 0.85%   |
| Acer Lenovo EasyCamera                   | 24        | 0.82%   |
| Chicony USB2.0 HD UVC WebCam             | 23        | 0.79%   |
| Bison Lenovo Integrated Webcam           | 23        | 0.79%   |
| Microdia USB 2.0 Camera                  | 22        | 0.75%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 22        | 0.75%   |
| Samsung Galaxy series, misc. (MTP mode)  | 21        | 0.72%   |
| Bison SunplusIT Integrated Camera        | 21        | 0.72%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 20        | 0.68%   |
| Realtek Integrated Webcam HD             | 20        | 0.68%   |
| Quanta HD User Facing                    | 19        | 0.65%   |
| Microdia Laptop_Integrated_Webcam_HD     | 19        | 0.65%   |
| Acer Integrated Camera                   | 19        | 0.65%   |
| Realtek Integrated Webcam                | 18        | 0.62%   |
| Logitech HD Pro Webcam C920              | 18        | 0.62%   |
| Creative Live! Cam Sync HD [VF0770]      | 18        | 0.62%   |
| Chicony USB2.0 VGA UVC WebCam            | 18        | 0.62%   |
| Chicony Integrated Camera (1280x720@30)  | 18        | 0.62%   |
| IMC Networks Integrated Webcam           | 17        | 0.58%   |
| Chicony USB 2.0 Camera                   | 17        | 0.58%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR       | 17        | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 207       | 36.19%  |
| Synaptics                          | 142       | 24.83%  |
| Shenzhen Goodix Technology         | 72        | 12.59%  |
| AuthenTec                          | 62        | 10.84%  |
| Upek                               | 37        | 6.47%   |
| Elan Microelectronics              | 22        | 3.85%   |
| LighTuning Technology              | 15        | 2.62%   |
| STMicroelectronics                 | 14        | 2.45%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.17%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 45        | 7.87%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 41        | 7.17%   |
| Shenzhen Goodix  FingerPrint Device                                        | 40        | 6.99%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 35        | 6.12%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 29        | 5.07%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 25        | 4.37%   |
| Shenzhen Goodix Fingerprint Reader                                         | 25        | 4.37%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 24        | 4.2%    |
| AuthenTec AES2810                                                          | 24        | 4.2%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 18        | 3.15%   |
| Validity Sensors Synaptics WBDI                                            | 15        | 2.62%   |
| Synaptics Fingerprint reader [HP G6]                                       | 15        | 2.62%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 14        | 2.45%   |
| STMicroelectronics Fingerprint Reader                                      | 14        | 2.45%   |
| Validity Sensors VFS491                                                    | 13        | 2.27%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 13        | 2.27%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 12        | 2.1%    |
| Elan ELAN:Fingerprint                                                      | 12        | 2.1%    |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 11        | 1.92%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 10        | 1.75%   |
| Validity Sensors Fingerprint scanner                                       | 10        | 1.75%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 9         | 1.57%   |
| Synaptics  WBDI                                                            | 9         | 1.57%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 9         | 1.57%   |
| AuthenTec AES1600                                                          | 8         | 1.4%    |
| Shenzhen Goodix FingerPrint                                                | 7         | 1.22%   |
| Elan ELAN:ARM-M4                                                           | 7         | 1.22%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 1.22%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 6         | 1.05%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 6         | 1.05%   |
| Validity Sensors VFS Fingerprint sensor                                    | 5         | 0.87%   |
| Synaptics WBDI                                                             | 5         | 0.87%   |
| Synaptics UWP WBDI                                                         | 5         | 0.87%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 0.87%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 0.7%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 0.7%    |
| LighTuning Fingerprint Reader                                              | 4         | 0.7%    |
| AuthenTec AES2550 Fingerprint Sensor                                       | 4         | 0.7%    |
| Synaptics WBDI Device                                                      | 3         | 0.52%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.35%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 235       | 55.16%  |
| Alcor Micro               | 87        | 20.42%  |
| O2 Micro                  | 45        | 10.56%  |
| Upek                      | 22        | 5.16%   |
| Lenovo                    | 20        | 4.69%   |
| Gemalto (was Gemplus)     | 5         | 1.17%   |
| Advanced Card Systems     | 3         | 0.7%    |
| OmniKey                   | 2         | 0.47%   |
| Clay Logic                | 2         | 0.47%   |
| Cherry                    | 2         | 0.47%   |
| SCM Microsystems          | 1         | 0.23%   |
| Reiner SCT Kartensysteme  | 1         | 0.23%   |
| Aladdin Knowledge Systems | 1         | 0.23%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 84        | 19.72%  |
| Broadcom BCM5880 Secure Applications Processor                               | 73        | 17.14%  |
| Broadcom 58200                                                               | 62        | 14.55%  |
| Broadcom 5880                                                                | 57        | 13.38%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 42        | 9.86%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 38        | 8.92%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 22        | 5.16%   |
| Lenovo Integrated Smart Card Reader                                          | 20        | 4.69%   |
| O2 Micro Oz776 SmartCard Reader                                              | 7         | 1.64%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.7%    |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 0.47%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 2         | 0.47%   |
| Clay Logic Nitrokey Pro                                                      | 2         | 0.47%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 0.47%   |
| Advanced Card Systems ACR39U                                                 | 2         | 0.47%   |
| SCM Microsystems SCR333 SmartCard Reader                                     | 1         | 0.23%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.23%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.23%   |
| Cherry Smart Terminal XX44                                                   | 1         | 0.23%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.23%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.23%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.23%   |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 1         | 0.23%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 3500      | 67.83%  |
| 1     | 1279      | 24.79%  |
| 2     | 323       | 6.26%   |
| 3     | 44        | 0.85%   |
| 4     | 6         | 0.12%   |
| 7     | 3         | 0.06%   |
| 5     | 3         | 0.06%   |
| 6     | 2         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 565       | 27.85%  |
| Graphics card            | 498       | 24.54%  |
| Chipcard                 | 378       | 18.63%  |
| Net/wireless             | 170       | 8.38%   |
| Multimedia controller    | 69        | 3.4%    |
| Communication controller | 57        | 2.81%   |
| Bluetooth                | 56        | 2.76%   |
| Storage                  | 53        | 2.61%   |
| Camera                   | 42        | 2.07%   |
| Unassigned class         | 35        | 1.72%   |
| Sound                    | 24        | 1.18%   |
| Card reader              | 19        | 0.94%   |
| Net/ethernet             | 11        | 0.54%   |
| Modem                    | 11        | 0.54%   |
| Network                  | 10        | 0.49%   |
| Firewire controller      | 8         | 0.39%   |
| Storage/ide              | 6         | 0.3%    |
| Dvb card                 | 6         | 0.3%    |
| Storage/raid             | 4         | 0.2%    |
| Flash memory             | 4         | 0.2%    |
| Wireless                 | 1         | 0.05%   |
| Unclassified device      | 1         | 0.05%   |
| Tv card                  | 1         | 0.05%   |

