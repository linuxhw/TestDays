OpenMandriva 5.0 - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for OpenMandriva 5.0.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/OpenMandriva_5.0/Desktop/README.md) and [notebooks](/Dist/OpenMandriva_5.0/Notebook/README.md).

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

Total: 559

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Medion        | Z170H4-EA                   | Desktop     | [17c714c6b5](https://linux-hardware.org/?probe=17c714c6b5) | Feb 02, 2024 |
| HP            | 8055                        | Desktop     | [1eec2a37ce](https://linux-hardware.org/?probe=1eec2a37ce) | Feb 02, 2024 |
| Foxconn       | 2ADA                        | Desktop     | [e92639ba10](https://linux-hardware.org/?probe=e92639ba10) | Feb 02, 2024 |
| ASUSTek       | F2A85-M LE                  | Desktop     | [680ba020e2](https://linux-hardware.org/?probe=680ba020e2) | Feb 02, 2024 |
| ASRock        | H77 Pro4-M                  | Desktop     | [794e5341d9](https://linux-hardware.org/?probe=794e5341d9) | Feb 01, 2024 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [9262af6ace](https://linux-hardware.org/?probe=9262af6ace) | Jan 31, 2024 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [011fd25549](https://linux-hardware.org/?probe=011fd25549) | Jan 31, 2024 |
| ASUSTek       | X540YA                      | Notebook    | [4e8d90738d](https://linux-hardware.org/?probe=4e8d90738d) | Jan 31, 2024 |
| Intel         | DH55PJ AAE93812-302         | Desktop     | [acc04ef6ef](https://linux-hardware.org/?probe=acc04ef6ef) | Jan 31, 2024 |
| Biostar       | H610MH                      | Desktop     | [fb0234d450](https://linux-hardware.org/?probe=fb0234d450) | Jan 31, 2024 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [3bba660f51](https://linux-hardware.org/?probe=3bba660f51) | Jan 31, 2024 |
| Biostar       | NF61S-M2A                   | Desktop     | [4b42e5cd37](https://linux-hardware.org/?probe=4b42e5cd37) | Jan 31, 2024 |
| Packard Be... | EasyNote ENLG71BM           | Notebook    | [ab713b894e](https://linux-hardware.org/?probe=ab713b894e) | Jan 31, 2024 |
| MSI           | PRO X670-P WIFI             | Desktop     | [2640847c88](https://linux-hardware.org/?probe=2640847c88) | Jan 31, 2024 |
| Dell          | 0FM586                      | Desktop     | [a66d080473](https://linux-hardware.org/?probe=a66d080473) | Jan 31, 2024 |
| Toshiba       | Portable PC                 | Notebook    | [5c293a3c24](https://linux-hardware.org/?probe=5c293a3c24) | Jan 30, 2024 |
| ARCELIK       | GNB 1150 B1 N2 V1.0         | Notebook    | [eb35406b7e](https://linux-hardware.org/?probe=eb35406b7e) | Jan 29, 2024 |
| Acer          | Aspire 5720Z                | Notebook    | [2353edc7dd](https://linux-hardware.org/?probe=2353edc7dd) | Jan 29, 2024 |
| HP            | Pavilion Laptop 15t-eg00... | Notebook    | [fd0435f25b](https://linux-hardware.org/?probe=fd0435f25b) | Jan 29, 2024 |
| Acer          | Aspire 5750                 | Notebook    | [f05ba6ae6f](https://linux-hardware.org/?probe=f05ba6ae6f) | Jan 29, 2024 |
| Acer          | Aspire V5-471PG             | Notebook    | [621c9286da](https://linux-hardware.org/?probe=621c9286da) | Jan 28, 2024 |
| Dell          | Latitude 3510               | Notebook    | [0be0a86c59](https://linux-hardware.org/?probe=0be0a86c59) | Jan 28, 2024 |
| Acer          | Aspire TC-780               | Desktop     | [00c699c62c](https://linux-hardware.org/?probe=00c699c62c) | Jan 28, 2024 |
| ASRock        | B75M R2.0                   | Desktop     | [7a7e12dca2](https://linux-hardware.org/?probe=7a7e12dca2) | Jan 27, 2024 |
| Gigabyte      | H97-HD3                     | Desktop     | [92984a124e](https://linux-hardware.org/?probe=92984a124e) | Jan 27, 2024 |
| ASUSTek       | ROG Zephyrus M16 GU604VI... | Notebook    | [dd39831e6f](https://linux-hardware.org/?probe=dd39831e6f) | Jan 27, 2024 |
| Gigabyte      | H410M H V3                  | Desktop     | [018db3f12a](https://linux-hardware.org/?probe=018db3f12a) | Jan 26, 2024 |
| Gigabyte      | H470M K                     | Desktop     | [644982a46f](https://linux-hardware.org/?probe=644982a46f) | Jan 26, 2024 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | Notebook    | [01dd8556d5](https://linux-hardware.org/?probe=01dd8556d5) | Jan 26, 2024 |
| Acer          | Aspire ES1-531              | Notebook    | [7faffb7f83](https://linux-hardware.org/?probe=7faffb7f83) | Jan 25, 2024 |
| Gigabyte      | H81M-S1                     | Desktop     | [b727252ca9](https://linux-hardware.org/?probe=b727252ca9) | Jan 25, 2024 |
| HP            | Compaq 6730s                | Notebook    | [caa48b80fb](https://linux-hardware.org/?probe=caa48b80fb) | Jan 25, 2024 |
| Gigabyte      | EG41MF-US2H                 | Desktop     | [882d3605ed](https://linux-hardware.org/?probe=882d3605ed) | Jan 25, 2024 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [066f355824](https://linux-hardware.org/?probe=066f355824) | Jan 25, 2024 |
| Acer          | Aspire ES1-572              | Notebook    | [10d96173cd](https://linux-hardware.org/?probe=10d96173cd) | Jan 25, 2024 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [ea518cb09d](https://linux-hardware.org/?probe=ea518cb09d) | Jan 24, 2024 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [057c708875](https://linux-hardware.org/?probe=057c708875) | Jan 24, 2024 |
| HP            | EliteBook 840 G3            | Notebook    | [eceea6fa49](https://linux-hardware.org/?probe=eceea6fa49) | Jan 24, 2024 |
| eMachines     | eME732Z                     | Notebook    | [fe3d184f11](https://linux-hardware.org/?probe=fe3d184f11) | Jan 24, 2024 |
| Toshiba       | Satellite C650              | Notebook    | [2fa418e377](https://linux-hardware.org/?probe=2fa418e377) | Jan 24, 2024 |
| ASRock        | B650M Pro RS                | Desktop     | [2d706981c5](https://linux-hardware.org/?probe=2d706981c5) | Jan 24, 2024 |
| Pegatron      | Benicia                     | Desktop     | [9a4be691fc](https://linux-hardware.org/?probe=9a4be691fc) | Jan 23, 2024 |
| Apple         | MacBookPro4,1               | Notebook    | [4c99b7a6ff](https://linux-hardware.org/?probe=4c99b7a6ff) | Jan 23, 2024 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [16c6b944fb](https://linux-hardware.org/?probe=16c6b944fb) | Jan 23, 2024 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [f2919e84e4](https://linux-hardware.org/?probe=f2919e84e4) | Jan 22, 2024 |
| Lenovo        | ThinkPad T430 2347A81       | Notebook    | [7209687602](https://linux-hardware.org/?probe=7209687602) | Jan 22, 2024 |
| HP            | ProBook 450 G5              | Notebook    | [ea8cc27b1a](https://linux-hardware.org/?probe=ea8cc27b1a) | Jan 21, 2024 |
| Fujitsu       | LIFEBOOK A555/G             | Notebook    | [f87640231d](https://linux-hardware.org/?probe=f87640231d) | Jan 21, 2024 |
| HP            | 82B4                        | Desktop     | [0eca4196b3](https://linux-hardware.org/?probe=0eca4196b3) | Jan 21, 2024 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [af044c261f](https://linux-hardware.org/?probe=af044c261f) | Jan 20, 2024 |
| Acer          | Aspire 1810T                | Notebook    | [068454b849](https://linux-hardware.org/?probe=068454b849) | Jan 20, 2024 |
| ASRock        | FM2A85X-ITX                 | Desktop     | [30f6aa7ead](https://linux-hardware.org/?probe=30f6aa7ead) | Jan 20, 2024 |
| ASUSTek       | H81M-K                      | Desktop     | [5b51e88413](https://linux-hardware.org/?probe=5b51e88413) | Jan 20, 2024 |
| Apple         | MacBookPro3,1               | Notebook    | [057f8b6477](https://linux-hardware.org/?probe=057f8b6477) | Jan 20, 2024 |
| Dell          | 042P49 A01                  | Desktop     | [e164f495e7](https://linux-hardware.org/?probe=e164f495e7) | Jan 19, 2024 |
| Gigabyte      | B460 AORUS PRO AC           | Desktop     | [276a0b5785](https://linux-hardware.org/?probe=276a0b5785) | Jan 19, 2024 |
| Google        | Garg                        | Notebook    | [b0e91d1473](https://linux-hardware.org/?probe=b0e91d1473) | Jan 19, 2024 |
| HP            | 81B4 01                     | Desktop     | [967d9af55c](https://linux-hardware.org/?probe=967d9af55c) | Jan 19, 2024 |
| Lenovo        | 100e 2nd Gen 81M8           | Notebook    | [a4aa40979a](https://linux-hardware.org/?probe=a4aa40979a) | Jan 18, 2024 |
| Intel         | NUC11PABi7 K90104-305       | Mini pc     | [11f478f041](https://linux-hardware.org/?probe=11f478f041) | Jan 18, 2024 |
| Gigabyte      | H610M K DDR4                | Desktop     | [5c9e5ec7aa](https://linux-hardware.org/?probe=5c9e5ec7aa) | Jan 18, 2024 |
| ASUSTek       | TUF Gaming B460-PLUS        | Desktop     | [344b6767cd](https://linux-hardware.org/?probe=344b6767cd) | Jan 17, 2024 |
| MACHINIST     | E5-RS9 V1.11                | Desktop     | [2b48345368](https://linux-hardware.org/?probe=2b48345368) | Jan 17, 2024 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [3baca805c4](https://linux-hardware.org/?probe=3baca805c4) | Jan 17, 2024 |
| EPoX Compu... | NF6100 + NF410 DDR2: MGF... | Desktop     | [ba08d6e05c](https://linux-hardware.org/?probe=ba08d6e05c) | Jan 17, 2024 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [77766f1cc1](https://linux-hardware.org/?probe=77766f1cc1) | Jan 17, 2024 |
| MSI           | A68HM-E33 V2                | Desktop     | [da97b5c9f5](https://linux-hardware.org/?probe=da97b5c9f5) | Jan 17, 2024 |
| Lenovo        | ThinkPad X230 2330A17       | Notebook    | [589c4362a6](https://linux-hardware.org/?probe=589c4362a6) | Jan 16, 2024 |
| Gigabyte      | EP35-DS3                    | Desktop     | [18f8b43855](https://linux-hardware.org/?probe=18f8b43855) | Jan 16, 2024 |
| ASRock        | Z390 Taichi                 | Desktop     | [84a79a7e97](https://linux-hardware.org/?probe=84a79a7e97) | Jan 16, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [f73401456d](https://linux-hardware.org/?probe=f73401456d) | Jan 16, 2024 |
| ASUSTek       | UN65U                       | Desktop     | [0c9b6c61f2](https://linux-hardware.org/?probe=0c9b6c61f2) | Jan 16, 2024 |
| Gigabyte      | H270M-D3H-CF                | Desktop     | [636ad953ab](https://linux-hardware.org/?probe=636ad953ab) | Jan 16, 2024 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | Notebook    | [22802134b7](https://linux-hardware.org/?probe=22802134b7) | Jan 15, 2024 |
| Dell          | XPS 15 9510                 | Notebook    | [55cbe62073](https://linux-hardware.org/?probe=55cbe62073) | Jan 15, 2024 |
| Lenovo        | ThinkPad T450s 20BWS05V0... | Notebook    | [fffdee8af3](https://linux-hardware.org/?probe=fffdee8af3) | Jan 15, 2024 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [4854968095](https://linux-hardware.org/?probe=4854968095) | Jan 15, 2024 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [122b72e9f2](https://linux-hardware.org/?probe=122b72e9f2) | Jan 15, 2024 |
| HP            | Laptop 15-db0xxx            | Notebook    | [cb2cda915a](https://linux-hardware.org/?probe=cb2cda915a) | Jan 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [f35fb9dd1c](https://linux-hardware.org/?probe=f35fb9dd1c) | Jan 13, 2024 |
| TUXEDO        | Book BM15 Gen10             | Notebook    | [dcb4b6ab6a](https://linux-hardware.org/?probe=dcb4b6ab6a) | Jan 13, 2024 |
| Dell          | 0KC9NP A01                  | Desktop     | [71596d8f5f](https://linux-hardware.org/?probe=71596d8f5f) | Jan 12, 2024 |
| ASRock        | H110M-HDV                   | Desktop     | [5f7f485a15](https://linux-hardware.org/?probe=5f7f485a15) | Jan 12, 2024 |
| Gigabyte      | H310M M.2 x.x               | Desktop     | [f67cc2282f](https://linux-hardware.org/?probe=f67cc2282f) | Jan 12, 2024 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [febf87bf81](https://linux-hardware.org/?probe=febf87bf81) | Jan 11, 2024 |
| Dell          | Vostro 3401                 | Notebook    | [cd47812859](https://linux-hardware.org/?probe=cd47812859) | Jan 11, 2024 |
| GEEKOM        | Mini IT 8                   | Desktop     | [16b759767e](https://linux-hardware.org/?probe=16b759767e) | Jan 11, 2024 |
| Lenovo        | IdeaPad Pro 5 14APH8 83A... | Notebook    | [47ca371fcb](https://linux-hardware.org/?probe=47ca371fcb) | Jan 10, 2024 |
| MSI           | Z87I                        | Desktop     | [35114b37dd](https://linux-hardware.org/?probe=35114b37dd) | Jan 10, 2024 |
| Pegatron      | NARRA3                      | Desktop     | [08c60d9c7a](https://linux-hardware.org/?probe=08c60d9c7a) | Jan 10, 2024 |
| Toshiba       | Satellite C660              | Notebook    | [34eaf45d7f](https://linux-hardware.org/?probe=34eaf45d7f) | Jan 09, 2024 |
| ASUSTek       | P8P67 EVO                   | Desktop     | [d54cf27190](https://linux-hardware.org/?probe=d54cf27190) | Jan 09, 2024 |
| HP            | 2000                        | Notebook    | [d23f668910](https://linux-hardware.org/?probe=d23f668910) | Jan 09, 2024 |
| HP            | Compaq 610                  | Notebook    | [da1dd5ace4](https://linux-hardware.org/?probe=da1dd5ace4) | Jan 08, 2024 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [a100fae6e2](https://linux-hardware.org/?probe=a100fae6e2) | Jan 08, 2024 |
| Gigabyte      | GA-E350N-USB3               | Desktop     | [222f3e6908](https://linux-hardware.org/?probe=222f3e6908) | Jan 08, 2024 |
| ALDO          | C2016-BSWI-D2               | Desktop     | [1e3d4c2e55](https://linux-hardware.org/?probe=1e3d4c2e55) | Jan 08, 2024 |
| Lenovo        | G710 20252                  | Notebook    | [ec645bc6c5](https://linux-hardware.org/?probe=ec645bc6c5) | Jan 08, 2024 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | Notebook    | [9d534bf283](https://linux-hardware.org/?probe=9d534bf283) | Jan 07, 2024 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [770f12c749](https://linux-hardware.org/?probe=770f12c749) | Jan 07, 2024 |
| HP            | 250 G3                      | Notebook    | [259acacdb3](https://linux-hardware.org/?probe=259acacdb3) | Jan 06, 2024 |
| Dell          | Inspiron 5515               | Notebook    | [6ff66dee9c](https://linux-hardware.org/?probe=6ff66dee9c) | Jan 06, 2024 |
| Toshiba       | Satellite L55D-B            | Notebook    | [e0358ccedc](https://linux-hardware.org/?probe=e0358ccedc) | Jan 06, 2024 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [532aed7e45](https://linux-hardware.org/?probe=532aed7e45) | Jan 05, 2024 |
| ASUSTek       | A4320A6420                  | Desktop     | [5df0f2025e](https://linux-hardware.org/?probe=5df0f2025e) | Jan 04, 2024 |
| Acer          | Veriton N4620G              | Desktop     | [f438d41562](https://linux-hardware.org/?probe=f438d41562) | Jan 03, 2024 |
| Acer          | WMCP78M                     | Desktop     | [5e254245ae](https://linux-hardware.org/?probe=5e254245ae) | Jan 03, 2024 |
| Dell          | Precision 7710              | Notebook    | [a2b5f2de51](https://linux-hardware.org/?probe=a2b5f2de51) | Jan 02, 2024 |
| Acer          | Extensa 2540                | Notebook    | [0dd0c273c1](https://linux-hardware.org/?probe=0dd0c273c1) | Jan 02, 2024 |
| MSI           | Modern 14 B4MW              | Notebook    | [f1f1b527ce](https://linux-hardware.org/?probe=f1f1b527ce) | Jan 02, 2024 |
| ASUSTek       | P7P55D                      | Desktop     | [23a30b2497](https://linux-hardware.org/?probe=23a30b2497) | Jan 01, 2024 |
| Apple         | MacBookAir9,1               | Notebook    | [5a511e238e](https://linux-hardware.org/?probe=5a511e238e) | Jan 01, 2024 |
| ASUSTek       | X751LA                      | Notebook    | [089bb5bca9](https://linux-hardware.org/?probe=089bb5bca9) | Jan 01, 2024 |
| Dell          | Latitude E6500              | Notebook    | [8d7d1376fd](https://linux-hardware.org/?probe=8d7d1376fd) | Dec 31, 2023 |
| Info Quest... | GTN1402 4-64                | Notebook    | [c363bd26ad](https://linux-hardware.org/?probe=c363bd26ad) | Dec 31, 2023 |
| HP            | 8054                        | Desktop     | [5389720de6](https://linux-hardware.org/?probe=5389720de6) | Dec 31, 2023 |
| HP            | 339A                        | Desktop     | [f109c46a8a](https://linux-hardware.org/?probe=f109c46a8a) | Dec 31, 2023 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [81e91658c9](https://linux-hardware.org/?probe=81e91658c9) | Dec 30, 2023 |
| HP            | Compaq 610                  | Notebook    | [d0849e0580](https://linux-hardware.org/?probe=d0849e0580) | Dec 30, 2023 |
| Intel         | Thurley                     | Desktop     | [2ad7d27607](https://linux-hardware.org/?probe=2ad7d27607) | Dec 29, 2023 |
| Lenovo        | B560                        | Notebook    | [1f8cf50933](https://linux-hardware.org/?probe=1f8cf50933) | Dec 29, 2023 |
| Lenovo        | Yoga 2 11 20332             | Notebook    | [04bb236111](https://linux-hardware.org/?probe=04bb236111) | Dec 29, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [4e00c088e8](https://linux-hardware.org/?probe=4e00c088e8) | Dec 29, 2023 |
| Notebook      | NS5x_NS7xAU                 | Notebook    | [d520b97118](https://linux-hardware.org/?probe=d520b97118) | Dec 29, 2023 |
| HP            | 3029h                       | Desktop     | [de537af4ba](https://linux-hardware.org/?probe=de537af4ba) | Dec 28, 2023 |
| Dell          | 0DF42J A00                  | Desktop     | [2b8f841667](https://linux-hardware.org/?probe=2b8f841667) | Dec 27, 2023 |
| eMachines     | MCP61PM-GM                  | Desktop     | [08b1aaf187](https://linux-hardware.org/?probe=08b1aaf187) | Dec 27, 2023 |
| Lenovo        | Annapurna CRB NO DPK        | Desktop     | [7d003c702a](https://linux-hardware.org/?probe=7d003c702a) | Dec 27, 2023 |
| ASUSTek       | P5K Premium                 | Desktop     | [b1c8bc2127](https://linux-hardware.org/?probe=b1c8bc2127) | Dec 26, 2023 |
| Medion        | Iron238G                    | All in one  | [702f3f3bc5](https://linux-hardware.org/?probe=702f3f3bc5) | Dec 26, 2023 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [0516914d99](https://linux-hardware.org/?probe=0516914d99) | Dec 26, 2023 |
| Dell          | Inspiron 15 3515            | Notebook    | [6369debba7](https://linux-hardware.org/?probe=6369debba7) | Dec 26, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [0535c48b0a](https://linux-hardware.org/?probe=0535c48b0a) | Dec 26, 2023 |
| Lenovo        | ThinkPad T61 7663DL1        | Notebook    | [b01632df81](https://linux-hardware.org/?probe=b01632df81) | Dec 26, 2023 |
| HP            | 15 Notebook PC              | Notebook    | [0b603c74cf](https://linux-hardware.org/?probe=0b603c74cf) | Dec 26, 2023 |
| HP            | 1495                        | Desktop     | [c8b50e17f9](https://linux-hardware.org/?probe=c8b50e17f9) | Dec 26, 2023 |
| Pegatron      | Eureka3                     | Desktop     | [0dfc8b6795](https://linux-hardware.org/?probe=0dfc8b6795) | Dec 25, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [5775a72a93](https://linux-hardware.org/?probe=5775a72a93) | Dec 25, 2023 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [f85a8a3b68](https://linux-hardware.org/?probe=f85a8a3b68) | Dec 25, 2023 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [d6257b5255](https://linux-hardware.org/?probe=d6257b5255) | Dec 25, 2023 |
| Biostar       | A320MH                      | Desktop     | [0898691249](https://linux-hardware.org/?probe=0898691249) | Dec 24, 2023 |
| Lenovo        | ThinkCentre M81 5049RK4     | Desktop     | [9ea1bc22a1](https://linux-hardware.org/?probe=9ea1bc22a1) | Dec 24, 2023 |
| Intel         | H61                         | Desktop     | [a10f481c10](https://linux-hardware.org/?probe=a10f481c10) | Dec 24, 2023 |
| Acer          | Extensa 2519                | Notebook    | [29bc812d6d](https://linux-hardware.org/?probe=29bc812d6d) | Dec 23, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [ac0b6ab055](https://linux-hardware.org/?probe=ac0b6ab055) | Dec 23, 2023 |
| ASUSTek       | P7P55D-E                    | Desktop     | [dc2914021f](https://linux-hardware.org/?probe=dc2914021f) | Dec 23, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [acab7c340a](https://linux-hardware.org/?probe=acab7c340a) | Dec 22, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [7b3f2a201c](https://linux-hardware.org/?probe=7b3f2a201c) | Dec 22, 2023 |
| Apple         | Mac-CFF7D910A743CAAF iMa... | All in one  | [61154d87f0](https://linux-hardware.org/?probe=61154d87f0) | Dec 22, 2023 |
| Dell          | System Vostro 3750          | Notebook    | [aa1fb5d9a6](https://linux-hardware.org/?probe=aa1fb5d9a6) | Dec 21, 2023 |
| HP            | 18E7                        | Desktop     | [71f34bba13](https://linux-hardware.org/?probe=71f34bba13) | Dec 21, 2023 |
| ASUSTek       | PRIME Z690-P                | Desktop     | [72187eb090](https://linux-hardware.org/?probe=72187eb090) | Dec 21, 2023 |
| Dell          | Latitude E6320              | Notebook    | [a1e4b48d85](https://linux-hardware.org/?probe=a1e4b48d85) | Dec 20, 2023 |
| Lenovo        | ThinkPad T480 20L6S01W00    | Notebook    | [c38a7a8ad4](https://linux-hardware.org/?probe=c38a7a8ad4) | Dec 20, 2023 |
| Intel         | H61                         | Desktop     | [01b739e240](https://linux-hardware.org/?probe=01b739e240) | Dec 20, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [e3dded7dc3](https://linux-hardware.org/?probe=e3dded7dc3) | Dec 20, 2023 |
| Dell          | Inspiron 1750               | Notebook    | [508bf60ff7](https://linux-hardware.org/?probe=508bf60ff7) | Dec 20, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [322b96bdd0](https://linux-hardware.org/?probe=322b96bdd0) | Dec 20, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [fc8665de21](https://linux-hardware.org/?probe=fc8665de21) | Dec 18, 2023 |
| Dell          | Precision 7530              | Notebook    | [6de510283f](https://linux-hardware.org/?probe=6de510283f) | Dec 18, 2023 |
| Gigabyte      | B450 GAMING X               | Desktop     | [28f3e414e2](https://linux-hardware.org/?probe=28f3e414e2) | Dec 17, 2023 |
| MSI           | MS-7255                     | Desktop     | [efdf3ede47](https://linux-hardware.org/?probe=efdf3ede47) | Dec 17, 2023 |
| Apple         | MacBookAir9,1               | Notebook    | [73f451cbe0](https://linux-hardware.org/?probe=73f451cbe0) | Dec 17, 2023 |
| ASUSTek       | K53SC                       | Notebook    | [4424929359](https://linux-hardware.org/?probe=4424929359) | Dec 17, 2023 |
| Dell          | 053CWD A00                  | Desktop     | [6cee8cbfd7](https://linux-hardware.org/?probe=6cee8cbfd7) | Dec 17, 2023 |
| Fujitsu       | LIFEBOOK U727               | Notebook    | [dceda9b2a1](https://linux-hardware.org/?probe=dceda9b2a1) | Dec 17, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [ead7baed80](https://linux-hardware.org/?probe=ead7baed80) | Dec 17, 2023 |
| ASUSTek       | S550CB                      | Notebook    | [20c9c415c9](https://linux-hardware.org/?probe=20c9c415c9) | Dec 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [ae7d12ef06](https://linux-hardware.org/?probe=ae7d12ef06) | Dec 17, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [f306ab4590](https://linux-hardware.org/?probe=f306ab4590) | Dec 17, 2023 |
| ASUSTek       | K61IC                       | Notebook    | [1442626988](https://linux-hardware.org/?probe=1442626988) | Dec 16, 2023 |
| Intel         | H81                         | Desktop     | [9aaa6b2ab6](https://linux-hardware.org/?probe=9aaa6b2ab6) | Dec 16, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [cf61f7b65b](https://linux-hardware.org/?probe=cf61f7b65b) | Dec 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [d34cfca6c8](https://linux-hardware.org/?probe=d34cfca6c8) | Dec 16, 2023 |
| MSI           | Modern 15 B5M               | Notebook    | [893ff177b3](https://linux-hardware.org/?probe=893ff177b3) | Dec 16, 2023 |
| HP            | 8653 A                      | Desktop     | [186fc771e8](https://linux-hardware.org/?probe=186fc771e8) | Dec 16, 2023 |
| AWOW          | Unknown                     | Notebook    | [7061726896](https://linux-hardware.org/?probe=7061726896) | Dec 16, 2023 |
| AZW           | GT-R                        | Notebook    | [205436106b](https://linux-hardware.org/?probe=205436106b) | Dec 16, 2023 |
| Dell          | Precision 7510              | Notebook    | [c70e7da2e8](https://linux-hardware.org/?probe=c70e7da2e8) | Dec 16, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [45900bcfb2](https://linux-hardware.org/?probe=45900bcfb2) | Dec 16, 2023 |
| Dell          | Latitude E5410              | Notebook    | [ee4251c01c](https://linux-hardware.org/?probe=ee4251c01c) | Dec 15, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [e03062f53d](https://linux-hardware.org/?probe=e03062f53d) | Dec 15, 2023 |
| Dell          | 0C27VV A02                  | Desktop     | [94560c4ce8](https://linux-hardware.org/?probe=94560c4ce8) | Dec 15, 2023 |
| Lenovo        | ThinkPad L330 34701V0       | Notebook    | [d418989434](https://linux-hardware.org/?probe=d418989434) | Dec 15, 2023 |
| AZW           | U55                         | Mini pc     | [0824d2f8fd](https://linux-hardware.org/?probe=0824d2f8fd) | Dec 15, 2023 |
| ASUSTek       | M4A78T-E                    | Desktop     | [f34b148b2e](https://linux-hardware.org/?probe=f34b148b2e) | Dec 14, 2023 |
| HP            | 1496                        | Desktop     | [a89ca6e62d](https://linux-hardware.org/?probe=a89ca6e62d) | Dec 14, 2023 |
| Medion        | E16401                      | Notebook    | [0c81bbcb2b](https://linux-hardware.org/?probe=0c81bbcb2b) | Dec 14, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | Notebook    | [8374878f6a](https://linux-hardware.org/?probe=8374878f6a) | Dec 14, 2023 |
| ASUSTek       | P8H61                       | Desktop     | [00f636bb09](https://linux-hardware.org/?probe=00f636bb09) | Dec 14, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [c16cb0947e](https://linux-hardware.org/?probe=c16cb0947e) | Dec 14, 2023 |
| HP            | Laptop 17-by4xxx            | Notebook    | [bb89121e0c](https://linux-hardware.org/?probe=bb89121e0c) | Dec 14, 2023 |
| HP            | 212B                        | Desktop     | [18d100b09c](https://linux-hardware.org/?probe=18d100b09c) | Dec 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [9227c29b16](https://linux-hardware.org/?probe=9227c29b16) | Dec 14, 2023 |
| ASUSTek       | P9X79-E WS                  | Desktop     | [5dd7c998ce](https://linux-hardware.org/?probe=5dd7c998ce) | Dec 14, 2023 |
| HP            | Laptop 17-by4xxx            | Notebook    | [0c728e7b27](https://linux-hardware.org/?probe=0c728e7b27) | Dec 13, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [bd8707be32](https://linux-hardware.org/?probe=bd8707be32) | Dec 13, 2023 |
| HP            | 18E4                        | Desktop     | [1dd0e805dc](https://linux-hardware.org/?probe=1dd0e805dc) | Dec 13, 2023 |
| Dell          | Latitude E5470              | Notebook    | [cc7982deb0](https://linux-hardware.org/?probe=cc7982deb0) | Dec 13, 2023 |
| Dell          | 0R790T A00                  | Desktop     | [8a72b2a4ce](https://linux-hardware.org/?probe=8a72b2a4ce) | Dec 13, 2023 |
| Dell          | Inspiron 1501               | Notebook    | [c4103f9e5c](https://linux-hardware.org/?probe=c4103f9e5c) | Dec 13, 2023 |
| Dell          | 0HN7XN A00                  | Desktop     | [c85fd96dcb](https://linux-hardware.org/?probe=c85fd96dcb) | Dec 13, 2023 |
| Fujitsu       | LIFEBOOK S792               | Notebook    | [811be0cce0](https://linux-hardware.org/?probe=811be0cce0) | Dec 13, 2023 |
| HP            | Stream x360 Convertible ... | Convertible | [edab80a2f1](https://linux-hardware.org/?probe=edab80a2f1) | Dec 12, 2023 |
| Lenovo        | Unknown                     | Desktop     | [d49ddc416f](https://linux-hardware.org/?probe=d49ddc416f) | Dec 12, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [894c4cf9fb](https://linux-hardware.org/?probe=894c4cf9fb) | Dec 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [c9eae3e15f](https://linux-hardware.org/?probe=c9eae3e15f) | Dec 12, 2023 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [2a6159034b](https://linux-hardware.org/?probe=2a6159034b) | Dec 12, 2023 |
| MSI           | H61M-E33                    | Desktop     | [6123a79100](https://linux-hardware.org/?probe=6123a79100) | Dec 12, 2023 |
| Acer          | Aspire E5-576               | Notebook    | [72fc5247a6](https://linux-hardware.org/?probe=72fc5247a6) | Dec 12, 2023 |
| Lenovo        | Unknown                     | Convertible | [ca130417ca](https://linux-hardware.org/?probe=ca130417ca) | Dec 12, 2023 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [a46aa4d97c](https://linux-hardware.org/?probe=a46aa4d97c) | Dec 11, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [0343e0a98e](https://linux-hardware.org/?probe=0343e0a98e) | Dec 11, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [9e23503add](https://linux-hardware.org/?probe=9e23503add) | Dec 11, 2023 |
| Acer          | Aspire E5-571G              | Notebook    | [30c8f1f622](https://linux-hardware.org/?probe=30c8f1f622) | Dec 11, 2023 |
| ASUSTek       | K54L                        | Notebook    | [a50a95f076](https://linux-hardware.org/?probe=a50a95f076) | Dec 11, 2023 |
| Dell          | Latitude 5590               | Notebook    | [ebdbfc1740](https://linux-hardware.org/?probe=ebdbfc1740) | Dec 11, 2023 |
| Acer          | Aspire ES1-512              | Notebook    | [40438b3cd0](https://linux-hardware.org/?probe=40438b3cd0) | Dec 11, 2023 |
| Intel         | DQ57TM AAE70931-402         | Desktop     | [fa57e6edd3](https://linux-hardware.org/?probe=fa57e6edd3) | Dec 10, 2023 |
| HP            | 3032h                       | Desktop     | [ca8902be00](https://linux-hardware.org/?probe=ca8902be00) | Dec 10, 2023 |
| Lenovo        | ThinkPad T410 2522V3S       | Notebook    | [7a6c259421](https://linux-hardware.org/?probe=7a6c259421) | Dec 10, 2023 |
| HP            | Laptop 14-bs0xx             | Notebook    | [f096c75cf9](https://linux-hardware.org/?probe=f096c75cf9) | Dec 10, 2023 |
| MSI           | 970A-G46                    | Desktop     | [86bd084c44](https://linux-hardware.org/?probe=86bd084c44) | Dec 10, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [43b1cafae8](https://linux-hardware.org/?probe=43b1cafae8) | Dec 10, 2023 |
| ASUSTek       | B150M-A/M.2                 | Desktop     | [dd4ad4373b](https://linux-hardware.org/?probe=dd4ad4373b) | Dec 10, 2023 |
| HP            | Notebook                    | Notebook    | [19c87ca6c5](https://linux-hardware.org/?probe=19c87ca6c5) | Dec 10, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | Notebook    | [1709e5c519](https://linux-hardware.org/?probe=1709e5c519) | Dec 10, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [be0d6f2f74](https://linux-hardware.org/?probe=be0d6f2f74) | Dec 10, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [69ebcd04b9](https://linux-hardware.org/?probe=69ebcd04b9) | Dec 10, 2023 |
| MSI           | Katana GF66 11UE            | Notebook    | [451c5731ae](https://linux-hardware.org/?probe=451c5731ae) | Dec 09, 2023 |
| HP            | 8433 11                     | Desktop     | [65bca719f6](https://linux-hardware.org/?probe=65bca719f6) | Dec 09, 2023 |
| HP            | G61                         | Notebook    | [ce104b5b73](https://linux-hardware.org/?probe=ce104b5b73) | Dec 09, 2023 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [0d57f82fc5](https://linux-hardware.org/?probe=0d57f82fc5) | Dec 09, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [d129c3b01f](https://linux-hardware.org/?probe=d129c3b01f) | Dec 09, 2023 |
| Intel         | DH61CR AAG14064-204         | Desktop     | [a319465535](https://linux-hardware.org/?probe=a319465535) | Dec 09, 2023 |
| ASUSTek       | F1A55-M LE R2.0             | Desktop     | [83885aa02c](https://linux-hardware.org/?probe=83885aa02c) | Dec 09, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [4202011d88](https://linux-hardware.org/?probe=4202011d88) | Dec 09, 2023 |
| HP            | Victus by Laptop 16-e1xx... | Notebook    | [9b973fc192](https://linux-hardware.org/?probe=9b973fc192) | Dec 08, 2023 |
| Dell          | Latitude 7490               | Notebook    | [13759c617a](https://linux-hardware.org/?probe=13759c617a) | Dec 08, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [beb5466523](https://linux-hardware.org/?probe=beb5466523) | Dec 08, 2023 |
| Pegatron      | 3580                        | Desktop     | [580355d3da](https://linux-hardware.org/?probe=580355d3da) | Dec 08, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [f26cee0fe0](https://linux-hardware.org/?probe=f26cee0fe0) | Dec 08, 2023 |
| HP            | ZBook 15v G5                | Notebook    | [96133249d0](https://linux-hardware.org/?probe=96133249d0) | Dec 08, 2023 |
| Adreamer      | Mybook PN1308P              | Notebook    | [e2dba2aff0](https://linux-hardware.org/?probe=e2dba2aff0) | Dec 08, 2023 |
| Intel         | DG965SS AAD41678-304        | Desktop     | [186a397074](https://linux-hardware.org/?probe=186a397074) | Dec 08, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [1989264cba](https://linux-hardware.org/?probe=1989264cba) | Dec 08, 2023 |
| Dell          | 0CXTWJ A00                  | All in one  | [e3814da48d](https://linux-hardware.org/?probe=e3814da48d) | Dec 08, 2023 |
| Dell          | 0GM819                      | Desktop     | [5c9ffb0977](https://linux-hardware.org/?probe=5c9ffb0977) | Dec 07, 2023 |
| FIC           | K2MCP61P PCB                | Desktop     | [fe4889cc68](https://linux-hardware.org/?probe=fe4889cc68) | Dec 07, 2023 |
| Lenovo        | ThinkPad T430 23498Y3       | Notebook    | [5382654b9b](https://linux-hardware.org/?probe=5382654b9b) | Dec 07, 2023 |
| Lenovo        | ThinkPad T440 20B7S0N10F    | Notebook    | [350da642e5](https://linux-hardware.org/?probe=350da642e5) | Dec 07, 2023 |
| Dell          | Precision 3550              | Notebook    | [da173d0ccc](https://linux-hardware.org/?probe=da173d0ccc) | Dec 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [18d69df8d2](https://linux-hardware.org/?probe=18d69df8d2) | Dec 07, 2023 |
| AMI           | Intel                       | Desktop     | [d2e7be0ff3](https://linux-hardware.org/?probe=d2e7be0ff3) | Dec 07, 2023 |
| MSI           | B350M BAZOOKA               | Desktop     | [4b67bc0273](https://linux-hardware.org/?probe=4b67bc0273) | Dec 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [3fce748548](https://linux-hardware.org/?probe=3fce748548) | Dec 06, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [923f26e8d8](https://linux-hardware.org/?probe=923f26e8d8) | Dec 06, 2023 |
| Dell          | 0YXT71 A03                  | Desktop     | [a3080a2577](https://linux-hardware.org/?probe=a3080a2577) | Dec 06, 2023 |
| MSI           | MAG X570S TORPEDO MAX       | Desktop     | [0ab3c62102](https://linux-hardware.org/?probe=0ab3c62102) | Dec 06, 2023 |
| Packard Be... | DOT S                       | Notebook    | [131c38200b](https://linux-hardware.org/?probe=131c38200b) | Dec 06, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [9960314986](https://linux-hardware.org/?probe=9960314986) | Dec 06, 2023 |
| Dell          | Latitude E7440              | Notebook    | [6b3c7ea2b5](https://linux-hardware.org/?probe=6b3c7ea2b5) | Dec 06, 2023 |
| Dell          | Latitude 3330               | Notebook    | [843751ec33](https://linux-hardware.org/?probe=843751ec33) | Dec 06, 2023 |
| AMI           | Intel                       | Desktop     | [8649d088c6](https://linux-hardware.org/?probe=8649d088c6) | Dec 06, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [ee3494fa57](https://linux-hardware.org/?probe=ee3494fa57) | Dec 06, 2023 |
| ASUSTek       | N76VZ                       | Notebook    | [3d8844bc98](https://linux-hardware.org/?probe=3d8844bc98) | Dec 05, 2023 |
| ASUSTek       | PRIME B250-PLUS             | Desktop     | [8c397afeca](https://linux-hardware.org/?probe=8c397afeca) | Dec 05, 2023 |
| Lenovo        | ThinkPad E15 20RD003KMH     | Notebook    | [d54efc5833](https://linux-hardware.org/?probe=d54efc5833) | Dec 05, 2023 |
| MSI           | 2A9C                        | Desktop     | [2ae992c0d5](https://linux-hardware.org/?probe=2ae992c0d5) | Dec 05, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [2cc0150e87](https://linux-hardware.org/?probe=2cc0150e87) | Dec 05, 2023 |
| HP            | 15                          | Notebook    | [561269f586](https://linux-hardware.org/?probe=561269f586) | Dec 05, 2023 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [08a2ed40a1](https://linux-hardware.org/?probe=08a2ed40a1) | Dec 05, 2023 |
| Lenovo        | ThinkCentre M81 0267A38     | Desktop     | [a9f041fc10](https://linux-hardware.org/?probe=a9f041fc10) | Dec 05, 2023 |
| Lenovo        | ThinkPad X390 20Q1S1WB00    | Notebook    | [ab1ae6521e](https://linux-hardware.org/?probe=ab1ae6521e) | Dec 05, 2023 |
| Fujitsu       | JIH61Y3                     | Desktop     | [8aa3f5fa84](https://linux-hardware.org/?probe=8aa3f5fa84) | Dec 05, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [729837dc5c](https://linux-hardware.org/?probe=729837dc5c) | Dec 05, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [76f6609343](https://linux-hardware.org/?probe=76f6609343) | Dec 05, 2023 |
| Acer          | Aspire XC-704G              | Desktop     | [44c713b05d](https://linux-hardware.org/?probe=44c713b05d) | Dec 05, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [b4b71ada44](https://linux-hardware.org/?probe=b4b71ada44) | Dec 04, 2023 |
| HP            | Pavilion 15                 | Notebook    | [15b5925773](https://linux-hardware.org/?probe=15b5925773) | Dec 04, 2023 |
| HP            | ProBook 4330s               | Notebook    | [48a060af86](https://linux-hardware.org/?probe=48a060af86) | Dec 04, 2023 |
| Lenovo        | ThinkPad L460 20FVS07C00    | Notebook    | [fd5a4dbeb9](https://linux-hardware.org/?probe=fd5a4dbeb9) | Dec 04, 2023 |
| Lenovo        | B50-50 80S2                 | Notebook    | [6150907e1e](https://linux-hardware.org/?probe=6150907e1e) | Dec 04, 2023 |
| HP            | OMEN by Laptop 16-b1xxx     | Notebook    | [9acc9cef23](https://linux-hardware.org/?probe=9acc9cef23) | Dec 04, 2023 |
| ASUSTek       | ROG STRIX B660-A GAMING ... | Desktop     | [d28a7f3ad6](https://linux-hardware.org/?probe=d28a7f3ad6) | Dec 04, 2023 |
| Toshiba       | Satellite A300              | Notebook    | [5817017508](https://linux-hardware.org/?probe=5817017508) | Dec 04, 2023 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [be471e354a](https://linux-hardware.org/?probe=be471e354a) | Dec 04, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [aec9f3cb3c](https://linux-hardware.org/?probe=aec9f3cb3c) | Dec 04, 2023 |
| Toshiba       | Satellite C855D             | Notebook    | [84e97d4578](https://linux-hardware.org/?probe=84e97d4578) | Dec 04, 2023 |
| ASUSTek       | P5P800-VM                   | Desktop     | [dff0c991af](https://linux-hardware.org/?probe=dff0c991af) | Dec 04, 2023 |
| HP            | 2B0A                        | All in one  | [94d8a9c118](https://linux-hardware.org/?probe=94d8a9c118) | Dec 04, 2023 |
| Lenovo        | 3178 SDK0J40700 WIN 3258... | Desktop     | [e215f304c3](https://linux-hardware.org/?probe=e215f304c3) | Dec 03, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [287093ae53](https://linux-hardware.org/?probe=287093ae53) | Dec 03, 2023 |
| Dell          | Latitude D630               | Notebook    | [84a1008ee2](https://linux-hardware.org/?probe=84a1008ee2) | Dec 03, 2023 |
| ASUSTek       | K53SJ                       | Notebook    | [50979ecbd2](https://linux-hardware.org/?probe=50979ecbd2) | Dec 03, 2023 |
| Dell          | Latitude E6410              | Notebook    | [bae67b7a50](https://linux-hardware.org/?probe=bae67b7a50) | Dec 03, 2023 |
| HP            | 1998                        | Desktop     | [14cb2b69d2](https://linux-hardware.org/?probe=14cb2b69d2) | Dec 03, 2023 |
| Gigabyte      | H77-DS3H                    | Desktop     | [4c97431f16](https://linux-hardware.org/?probe=4c97431f16) | Dec 03, 2023 |
| HP            | ENVY m6                     | Notebook    | [3a3cde32ab](https://linux-hardware.org/?probe=3a3cde32ab) | Dec 03, 2023 |
| Dell          | 03NVJ6 A02                  | Desktop     | [7f9b2fa7e0](https://linux-hardware.org/?probe=7f9b2fa7e0) | Dec 03, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [e7c23bf6d5](https://linux-hardware.org/?probe=e7c23bf6d5) | Dec 03, 2023 |
| Medion        | E6214                       | Notebook    | [f5e38ac376](https://linux-hardware.org/?probe=f5e38ac376) | Dec 03, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [f60bc8a984](https://linux-hardware.org/?probe=f60bc8a984) | Dec 03, 2023 |
| Acer          | Aspire 8951G                | Notebook    | [f98b449dba](https://linux-hardware.org/?probe=f98b449dba) | Dec 03, 2023 |
| Dell          | 0C2XKD A01                  | Desktop     | [e946c07f76](https://linux-hardware.org/?probe=e946c07f76) | Dec 03, 2023 |
| Dell          | Inspiron 13-5378            | Notebook    | [0beeed51bc](https://linux-hardware.org/?probe=0beeed51bc) | Dec 03, 2023 |
| Lenovo        | ThinkPad T530 2429F37       | Notebook    | [7db847c98e](https://linux-hardware.org/?probe=7db847c98e) | Dec 03, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [388cf45c84](https://linux-hardware.org/?probe=388cf45c84) | Dec 03, 2023 |
| Acer          | IPXHW-RL                    | Desktop     | [aa0f30e67f](https://linux-hardware.org/?probe=aa0f30e67f) | Dec 02, 2023 |
| HP            | 8299                        | Desktop     | [fb5b226159](https://linux-hardware.org/?probe=fb5b226159) | Dec 02, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [13816c1292](https://linux-hardware.org/?probe=13816c1292) | Dec 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [9d3a34c3da](https://linux-hardware.org/?probe=9d3a34c3da) | Dec 02, 2023 |
| Dell          | 07N90W A01                  | Desktop     | [53c34cdf7d](https://linux-hardware.org/?probe=53c34cdf7d) | Dec 02, 2023 |
| ASUSTek       | F3E                         | Notebook    | [26a960dd12](https://linux-hardware.org/?probe=26a960dd12) | Dec 02, 2023 |
| Dell          | Precision 5520              | Notebook    | [aa1a1feefc](https://linux-hardware.org/?probe=aa1a1feefc) | Dec 02, 2023 |
| Dell          | Latitude E6510              | Notebook    | [0c49353fa5](https://linux-hardware.org/?probe=0c49353fa5) | Dec 02, 2023 |
| MSI           | Modern 14 B5M               | Notebook    | [c22637e524](https://linux-hardware.org/?probe=c22637e524) | Dec 02, 2023 |
| Toshiba       | Satellite C650D             | Notebook    | [704507bfd5](https://linux-hardware.org/?probe=704507bfd5) | Dec 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | Notebook    | [7ddcba051c](https://linux-hardware.org/?probe=7ddcba051c) | Dec 02, 2023 |
| MSI           | B350 GAMING PLUS            | Desktop     | [883665fb17](https://linux-hardware.org/?probe=883665fb17) | Dec 02, 2023 |
| HP            | Pavilion g7                 | Notebook    | [5c596e9e4f](https://linux-hardware.org/?probe=5c596e9e4f) | Dec 02, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [5ea999f7bc](https://linux-hardware.org/?probe=5ea999f7bc) | Dec 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [58a0ae4fcc](https://linux-hardware.org/?probe=58a0ae4fcc) | Dec 02, 2023 |
| Lenovo        | G585                        | Notebook    | [a62a35b461](https://linux-hardware.org/?probe=a62a35b461) | Dec 01, 2023 |
| HP            | Pavilion dv7                | Notebook    | [dc015f1023](https://linux-hardware.org/?probe=dc015f1023) | Dec 01, 2023 |
| Apple         | Mac-7DF2A3B5E5D671ED iMa... | All in one  | [4e3a656c43](https://linux-hardware.org/?probe=4e3a656c43) | Dec 01, 2023 |
| Gigabyte      | Z690 UD AX DDR4             | Desktop     | [00159f1b41](https://linux-hardware.org/?probe=00159f1b41) | Dec 01, 2023 |
| ASUSTek       | H97M-E                      | Desktop     | [9e60faee5f](https://linux-hardware.org/?probe=9e60faee5f) | Dec 01, 2023 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | Notebook    | [32a0e568cc](https://linux-hardware.org/?probe=32a0e568cc) | Dec 01, 2023 |
| Acer          | Aspire A317-51K             | Notebook    | [aa5652abe0](https://linux-hardware.org/?probe=aa5652abe0) | Dec 01, 2023 |
| Intel         | H61 V1.5                    | Desktop     | [45487af3d7](https://linux-hardware.org/?probe=45487af3d7) | Dec 01, 2023 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [0ae66633bc](https://linux-hardware.org/?probe=0ae66633bc) | Dec 01, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [7eb86d01c5](https://linux-hardware.org/?probe=7eb86d01c5) | Dec 01, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [7fbbf18938](https://linux-hardware.org/?probe=7fbbf18938) | Dec 01, 2023 |
| Lenovo        | ThinkPad T480s 20L7002CU... | Notebook    | [679acd4c7a](https://linux-hardware.org/?probe=679acd4c7a) | Dec 01, 2023 |
| Packard Be... | EasyNote LJ75               | Notebook    | [0f21e6cb39](https://linux-hardware.org/?probe=0f21e6cb39) | Dec 01, 2023 |
| Gigabyte      | B460M D3H                   | Desktop     | [b83f7a31ff](https://linux-hardware.org/?probe=b83f7a31ff) | Dec 01, 2023 |
| Acer          | Aspire 5732Z                | Notebook    | [f79a825fcd](https://linux-hardware.org/?probe=f79a825fcd) | Dec 01, 2023 |
| Dell          | Latitude E5410              | Notebook    | [074e7de8d8](https://linux-hardware.org/?probe=074e7de8d8) | Dec 01, 2023 |
| Acer          | Aspire A114-31              | Notebook    | [1eb938404f](https://linux-hardware.org/?probe=1eb938404f) | Dec 01, 2023 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [40a0a394cc](https://linux-hardware.org/?probe=40a0a394cc) | Dec 01, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [49c6f0b57f](https://linux-hardware.org/?probe=49c6f0b57f) | Dec 01, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [ad16e37b50](https://linux-hardware.org/?probe=ad16e37b50) | Dec 01, 2023 |
| Dell          | Latitude E6440              | Notebook    | [4459a634ca](https://linux-hardware.org/?probe=4459a634ca) | Dec 01, 2023 |
| ASRock        | H310CM-HDV/M.2              | Desktop     | [4b91971e62](https://linux-hardware.org/?probe=4b91971e62) | Dec 01, 2023 |
| Dell          | 014GRG A03                  | Desktop     | [581d6ec42f](https://linux-hardware.org/?probe=581d6ec42f) | Nov 30, 2023 |
| Toshiba       | Satellite L755              | Notebook    | [511b79d4dc](https://linux-hardware.org/?probe=511b79d4dc) | Nov 30, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [aa1896b627](https://linux-hardware.org/?probe=aa1896b627) | Nov 30, 2023 |
| Dell          | Inspiron 15 3515            | Notebook    | [162854d649](https://linux-hardware.org/?probe=162854d649) | Nov 30, 2023 |
| Dell          | 0WK833                      | Desktop     | [f363206bab](https://linux-hardware.org/?probe=f363206bab) | Nov 30, 2023 |
| MSI           | A88X-G45 GAMING             | Desktop     | [c3ad03c61d](https://linux-hardware.org/?probe=c3ad03c61d) | Nov 30, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [5cfd0eb0f5](https://linux-hardware.org/?probe=5cfd0eb0f5) | Nov 30, 2023 |
| Acer          | Aspire V5-591G              | Notebook    | [fcb901f377](https://linux-hardware.org/?probe=fcb901f377) | Nov 30, 2023 |
| Acer          | Aspire A315-35              | Notebook    | [dad806dd8b](https://linux-hardware.org/?probe=dad806dd8b) | Nov 30, 2023 |
| HP            | 843B                        | Desktop     | [5a69492f49](https://linux-hardware.org/?probe=5a69492f49) | Nov 30, 2023 |
| ASRock        | B450 Pro4 R2.0              | Desktop     | [53fc7f6723](https://linux-hardware.org/?probe=53fc7f6723) | Nov 30, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [03de11e5b3](https://linux-hardware.org/?probe=03de11e5b3) | Nov 30, 2023 |
| Acer          | TravelMate Spin B118-G2-... | Convertible | [013c0f7207](https://linux-hardware.org/?probe=013c0f7207) | Nov 30, 2023 |
| ASUSTek       | PRIME B550-PLUS AC-HES      | Desktop     | [4747b76126](https://linux-hardware.org/?probe=4747b76126) | Nov 30, 2023 |
| Toshiba       | Satellite C850-19D          | Notebook    | [cd9dbac72b](https://linux-hardware.org/?probe=cd9dbac72b) | Nov 30, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [01105932ac](https://linux-hardware.org/?probe=01105932ac) | Nov 30, 2023 |
| HP            | Laptop 15-bs1xx             | Notebook    | [e8f82bc03f](https://linux-hardware.org/?probe=e8f82bc03f) | Nov 29, 2023 |
| MSI           | B250M PRO-VD                | Desktop     | [e0dead14ab](https://linux-hardware.org/?probe=e0dead14ab) | Nov 29, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [b682c56733](https://linux-hardware.org/?probe=b682c56733) | Nov 29, 2023 |
| eMachines     | eME440                      | Notebook    | [a622dddd66](https://linux-hardware.org/?probe=a622dddd66) | Nov 29, 2023 |
| Gigabyte      | GA-A55M-DS2                 | Desktop     | [bf1caf0dae](https://linux-hardware.org/?probe=bf1caf0dae) | Nov 29, 2023 |
| Dell          | 03PYWR A00                  | All in one  | [1dbfc80896](https://linux-hardware.org/?probe=1dbfc80896) | Nov 29, 2023 |
| HUAWEI        | NbDE-WXX9                   | Notebook    | [8fc5d22e76](https://linux-hardware.org/?probe=8fc5d22e76) | Nov 29, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [395fbd2b48](https://linux-hardware.org/?probe=395fbd2b48) | Nov 29, 2023 |
| HP            | Laptop 17-by3xxx            | Notebook    | [63860f689c](https://linux-hardware.org/?probe=63860f689c) | Nov 29, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | Notebook    | [685ce27fae](https://linux-hardware.org/?probe=685ce27fae) | Nov 29, 2023 |
| HP            | 8298                        | Desktop     | [f66cb29dd1](https://linux-hardware.org/?probe=f66cb29dd1) | Nov 29, 2023 |
| TUXEDO        | Book BA1510                 | Notebook    | [0c59322d62](https://linux-hardware.org/?probe=0c59322d62) | Nov 29, 2023 |
| Unknown       | N15                         | Desktop     | [a968ec315f](https://linux-hardware.org/?probe=a968ec315f) | Nov 29, 2023 |
| ASRock        | J3355M                      | Desktop     | [a767ff37ed](https://linux-hardware.org/?probe=a767ff37ed) | Nov 29, 2023 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [cd63a4710a](https://linux-hardware.org/?probe=cd63a4710a) | Nov 29, 2023 |
| Lenovo        | 317E SDK0K17763 WIN 1801... | Desktop     | [8bc25c47be](https://linux-hardware.org/?probe=8bc25c47be) | Nov 29, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [655dc71f64](https://linux-hardware.org/?probe=655dc71f64) | Nov 29, 2023 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [cc31cdf621](https://linux-hardware.org/?probe=cc31cdf621) | Nov 29, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [9b8fabda07](https://linux-hardware.org/?probe=9b8fabda07) | Nov 29, 2023 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [a97b3bd106](https://linux-hardware.org/?probe=a97b3bd106) | Nov 29, 2023 |
| Acer          | TravelMate P614-51-G2       | Notebook    | [17c4552f25](https://linux-hardware.org/?probe=17c4552f25) | Nov 29, 2023 |
| HP            | 805D                        | Desktop     | [997f828456](https://linux-hardware.org/?probe=997f828456) | Nov 29, 2023 |
| MSI           | Z170A PC MATE               | Desktop     | [913553eac4](https://linux-hardware.org/?probe=913553eac4) | Nov 29, 2023 |
| Red Hat       | RHEL RHEL-9.2.0 PC          | Desktop     | [c70f79dd89](https://linux-hardware.org/?probe=c70f79dd89) | Nov 29, 2023 |
| Gigabyte      | H310M S2                    | Desktop     | [4cd53ef516](https://linux-hardware.org/?probe=4cd53ef516) | Nov 29, 2023 |
| Lenovo        | ThinkPad X201 3323BSG       | Notebook    | [e0ad13d1e8](https://linux-hardware.org/?probe=e0ad13d1e8) | Nov 29, 2023 |
| Fujitsu       | FMVNS6HE                    | Notebook    | [df459431eb](https://linux-hardware.org/?probe=df459431eb) | Nov 29, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [066daf7cac](https://linux-hardware.org/?probe=066daf7cac) | Nov 29, 2023 |
| LG Electro... | 17Z90Q-K.AAC7U1             | Notebook    | [6af16f3cbb](https://linux-hardware.org/?probe=6af16f3cbb) | Nov 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [7ca8c7adc5](https://linux-hardware.org/?probe=7ca8c7adc5) | Nov 29, 2023 |
| Founder       | Q87H3-AM V:1.0              | Desktop     | [56a7ef0f8a](https://linux-hardware.org/?probe=56a7ef0f8a) | Nov 29, 2023 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | Desktop     | [bd474c263c](https://linux-hardware.org/?probe=bd474c263c) | Nov 29, 2023 |
| HP            | 8648                        | Desktop     | [f6804eecf5](https://linux-hardware.org/?probe=f6804eecf5) | Nov 29, 2023 |
| HP            | Compaq 6730s                | Notebook    | [ff2ae39e03](https://linux-hardware.org/?probe=ff2ae39e03) | Nov 29, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [a94fe27744](https://linux-hardware.org/?probe=a94fe27744) | Nov 28, 2023 |
| MSI           | KA790GX                     | Desktop     | [5bc35f82f6](https://linux-hardware.org/?probe=5bc35f82f6) | Nov 28, 2023 |
| Lenovo        | ThinkPad R500 27148UG       | Notebook    | [546c56f7bb](https://linux-hardware.org/?probe=546c56f7bb) | Nov 28, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [c93b09ccf3](https://linux-hardware.org/?probe=c93b09ccf3) | Nov 28, 2023 |
| Apple         | Mac-7DF2A3B5E5D671ED iMa... | All in one  | [0c21772cb7](https://linux-hardware.org/?probe=0c21772cb7) | Nov 28, 2023 |
| HP            | Compaq 610                  | Notebook    | [f0022a2c56](https://linux-hardware.org/?probe=f0022a2c56) | Nov 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [577a8fa908](https://linux-hardware.org/?probe=577a8fa908) | Nov 28, 2023 |
| Dell          | Inspiron 15 3515            | Notebook    | [20007eacdb](https://linux-hardware.org/?probe=20007eacdb) | Nov 28, 2023 |
| Dell          | Inspiron 15 3515            | Notebook    | [e41d34ea1c](https://linux-hardware.org/?probe=e41d34ea1c) | Nov 28, 2023 |
| Sony          | VPCEL1E1E                   | Notebook    | [9c88ceb0b0](https://linux-hardware.org/?probe=9c88ceb0b0) | Nov 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [b4e8fd1ac2](https://linux-hardware.org/?probe=b4e8fd1ac2) | Nov 28, 2023 |
| Dell          | 0PGMR1 A00                  | All in one  | [aaca525c1a](https://linux-hardware.org/?probe=aaca525c1a) | Nov 28, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [2627da2538](https://linux-hardware.org/?probe=2627da2538) | Nov 28, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [11d4048dc9](https://linux-hardware.org/?probe=11d4048dc9) | Nov 28, 2023 |
| HP            | 304Bh                       | Desktop     | [3cb20d232f](https://linux-hardware.org/?probe=3cb20d232f) | Nov 28, 2023 |
| ECS           | G31T-M9                     | Desktop     | [535a19c400](https://linux-hardware.org/?probe=535a19c400) | Nov 28, 2023 |
| Lenovo        | SDK0F82993 WIN              | Desktop     | [d9bc93a89f](https://linux-hardware.org/?probe=d9bc93a89f) | Nov 28, 2023 |
| Gigabyte      | 945GZM-S2                   | Desktop     | [0a673a3528](https://linux-hardware.org/?probe=0a673a3528) | Nov 28, 2023 |
| Dell          | 0T7D40 A01                  | Desktop     | [6c16a6716b](https://linux-hardware.org/?probe=6c16a6716b) | Nov 28, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [34f3153910](https://linux-hardware.org/?probe=34f3153910) | Nov 28, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [52a0c464fe](https://linux-hardware.org/?probe=52a0c464fe) | Nov 28, 2023 |
| Medion        | MS-7621                     | Desktop     | [18f32a871d](https://linux-hardware.org/?probe=18f32a871d) | Nov 28, 2023 |
| Samsung       | RV413/RV513                 | Notebook    | [42fb4ae911](https://linux-hardware.org/?probe=42fb4ae911) | Nov 28, 2023 |
| Acer          | Aspire E5-521G              | Notebook    | [d639f77bd9](https://linux-hardware.org/?probe=d639f77bd9) | Nov 28, 2023 |
| ASRock        | H81M-DGS R2.0               | Desktop     | [2196f5ec5e](https://linux-hardware.org/?probe=2196f5ec5e) | Nov 28, 2023 |
| Lenovo        | ThinkPad T540p 20BFS31F0... | Notebook    | [8db080dffe](https://linux-hardware.org/?probe=8db080dffe) | Nov 28, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [c056490536](https://linux-hardware.org/?probe=c056490536) | Nov 28, 2023 |
| Acer          | Aspire A315-57G             | Notebook    | [10678fbceb](https://linux-hardware.org/?probe=10678fbceb) | Nov 28, 2023 |
| Google        | Fleex                       | Notebook    | [0f905372c0](https://linux-hardware.org/?probe=0f905372c0) | Nov 28, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [c56c2fcff2](https://linux-hardware.org/?probe=c56c2fcff2) | Nov 28, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [2df2a6f5d8](https://linux-hardware.org/?probe=2df2a6f5d8) | Nov 28, 2023 |
| Dell          | 07KY25 A01                  | Desktop     | [f1905255d0](https://linux-hardware.org/?probe=f1905255d0) | Nov 28, 2023 |
| Dell          | 03NVJ6 A03                  | Desktop     | [2eae8e704b](https://linux-hardware.org/?probe=2eae8e704b) | Nov 28, 2023 |
| HUAWEI        | MACH-WX9                    | Notebook    | [a09dd535a7](https://linux-hardware.org/?probe=a09dd535a7) | Nov 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon 34603... | Notebook    | [edb57fe6c8](https://linux-hardware.org/?probe=edb57fe6c8) | Nov 28, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [39dd843280](https://linux-hardware.org/?probe=39dd843280) | Nov 28, 2023 |
| Lenovo        | Legion Y9000P IAH7H 82RF    | Notebook    | [b3bea8127f](https://linux-hardware.org/?probe=b3bea8127f) | Nov 27, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [3982dc173a](https://linux-hardware.org/?probe=3982dc173a) | Nov 27, 2023 |
| Machcreato... | 14X                         | Notebook    | [25e406809e](https://linux-hardware.org/?probe=25e406809e) | Nov 27, 2023 |
| ASUSTek       | K73SD                       | Notebook    | [cd71879827](https://linux-hardware.org/?probe=cd71879827) | Nov 27, 2023 |
| ZOTAC         | ZBOX-CI527/CI547NANO        | Mini pc     | [79a0fbae44](https://linux-hardware.org/?probe=79a0fbae44) | Nov 27, 2023 |
| Timi          | TM1701                      | Notebook    | [dfb21da820](https://linux-hardware.org/?probe=dfb21da820) | Nov 27, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [d4488776c4](https://linux-hardware.org/?probe=d4488776c4) | Nov 27, 2023 |
| ASUSTek       | CM1435                      | Desktop     | [deceba2322](https://linux-hardware.org/?probe=deceba2322) | Nov 27, 2023 |
| Dell          | Latitude 3350               | Notebook    | [395158b705](https://linux-hardware.org/?probe=395158b705) | Nov 27, 2023 |
| MSI           | CR620                       | Notebook    | [336d403e1b](https://linux-hardware.org/?probe=336d403e1b) | Nov 27, 2023 |
| Dell          | Inspiron 1012               | Notebook    | [ffe483f5fd](https://linux-hardware.org/?probe=ffe483f5fd) | Nov 27, 2023 |
| ASUSTek       | F2A85-M                     | Desktop     | [0c272521ab](https://linux-hardware.org/?probe=0c272521ab) | Nov 27, 2023 |
| Acer          | Veriton X2632G V:1.0        | Desktop     | [0c50fc3c6f](https://linux-hardware.org/?probe=0c50fc3c6f) | Nov 27, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [a82d950345](https://linux-hardware.org/?probe=a82d950345) | Nov 27, 2023 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [d848c8ed0e](https://linux-hardware.org/?probe=d848c8ed0e) | Nov 27, 2023 |
| Intel         | NUC6i3SYB H81132-502        | Mini pc     | [2e92b0d236](https://linux-hardware.org/?probe=2e92b0d236) | Nov 27, 2023 |
| ASRock        | H61M-VG3                    | Desktop     | [8b7f6c2f5f](https://linux-hardware.org/?probe=8b7f6c2f5f) | Nov 27, 2023 |
| AZW           | GTR V01                     | Mini pc     | [36be46a799](https://linux-hardware.org/?probe=36be46a799) | Nov 27, 2023 |
| Foxconn       | H67MP-S/-V/H67MP            | Desktop     | [c5f3edc9d1](https://linux-hardware.org/?probe=c5f3edc9d1) | Nov 27, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [cd7362b85e](https://linux-hardware.org/?probe=cd7362b85e) | Nov 27, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [e83a570bcd](https://linux-hardware.org/?probe=e83a570bcd) | Nov 27, 2023 |
| Dell          | 0F3KHR A00                  | Desktop     | [c744967be3](https://linux-hardware.org/?probe=c744967be3) | Nov 27, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [936970029f](https://linux-hardware.org/?probe=936970029f) | Nov 27, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [ee22e39495](https://linux-hardware.org/?probe=ee22e39495) | Nov 27, 2023 |
| Gigabyte      | B75M-D3V                    | Desktop     | [142a3240d4](https://linux-hardware.org/?probe=142a3240d4) | Nov 27, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [a5016a519f](https://linux-hardware.org/?probe=a5016a519f) | Nov 27, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [121db7e081](https://linux-hardware.org/?probe=121db7e081) | Nov 27, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [02f1616520](https://linux-hardware.org/?probe=02f1616520) | Nov 27, 2023 |
| HP            | 8056                        | Desktop     | [9972a0e20f](https://linux-hardware.org/?probe=9972a0e20f) | Nov 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [0ddcbc9eb9](https://linux-hardware.org/?probe=0ddcbc9eb9) | Nov 27, 2023 |
| HP            | 8184 X4                     | Desktop     | [0813228fc1](https://linux-hardware.org/?probe=0813228fc1) | Nov 27, 2023 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [f3e5b85b92](https://linux-hardware.org/?probe=f3e5b85b92) | Nov 27, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [042a42a235](https://linux-hardware.org/?probe=042a42a235) | Nov 27, 2023 |
| ASUSTek       | PRIME J4005I-C              | Desktop     | [23f26e0c45](https://linux-hardware.org/?probe=23f26e0c45) | Nov 27, 2023 |
| Samsung       | 910S3L/911S3L               | Notebook    | [5356e7f33b](https://linux-hardware.org/?probe=5356e7f33b) | Nov 27, 2023 |
| Lenovo        | ThinkPad T520 4242AU2       | Notebook    | [71ffabfcb1](https://linux-hardware.org/?probe=71ffabfcb1) | Nov 27, 2023 |
| Dell          | 00VTMF A01                  | Desktop     | [bb1a93e07b](https://linux-hardware.org/?probe=bb1a93e07b) | Nov 27, 2023 |
| HP            | 82F2 A01                    | Desktop     | [21ece36869](https://linux-hardware.org/?probe=21ece36869) | Nov 27, 2023 |
| HP            | 2AF7                        | Desktop     | [a366a85d8c](https://linux-hardware.org/?probe=a366a85d8c) | Nov 27, 2023 |
| Lenovo        | V340-17IWL 81RG             | Notebook    | [c2a7190ba8](https://linux-hardware.org/?probe=c2a7190ba8) | Nov 27, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [be532e0503](https://linux-hardware.org/?probe=be532e0503) | Nov 27, 2023 |
| AZW           | MINI S 10                   | Desktop     | [c0fda6103a](https://linux-hardware.org/?probe=c0fda6103a) | Nov 26, 2023 |
| Dell          | 0YP806 A01                  | Desktop     | [078d014e70](https://linux-hardware.org/?probe=078d014e70) | Nov 26, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [c28cfb7cd7](https://linux-hardware.org/?probe=c28cfb7cd7) | Nov 26, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [cb6d17a69a](https://linux-hardware.org/?probe=cb6d17a69a) | Nov 26, 2023 |
| HP            | 8704                        | Desktop     | [594422dbde](https://linux-hardware.org/?probe=594422dbde) | Nov 26, 2023 |
| HP            | 1497                        | Desktop     | [5922e57d93](https://linux-hardware.org/?probe=5922e57d93) | Nov 26, 2023 |
| HP            | Pavilion dv7                | Notebook    | [940ce7b8ed](https://linux-hardware.org/?probe=940ce7b8ed) | Nov 26, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [acd145c278](https://linux-hardware.org/?probe=acd145c278) | Nov 26, 2023 |
| Gigabyte      | P55-US3L                    | Desktop     | [fdb0f32546](https://linux-hardware.org/?probe=fdb0f32546) | Nov 26, 2023 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [f2856297d6](https://linux-hardware.org/?probe=f2856297d6) | Nov 26, 2023 |
| Shenzhen M... | F7BAA                       | Desktop     | [a48bfbc481](https://linux-hardware.org/?probe=a48bfbc481) | Nov 26, 2023 |
| Dell          | 0200DY A02                  | Desktop     | [7d5df62892](https://linux-hardware.org/?probe=7d5df62892) | Nov 26, 2023 |
| Dell          | XPS 13 9300                 | Notebook    | [68ba1c0162](https://linux-hardware.org/?probe=68ba1c0162) | Nov 26, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [e552669069](https://linux-hardware.org/?probe=e552669069) | Nov 26, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [9247159905](https://linux-hardware.org/?probe=9247159905) | Nov 26, 2023 |
| HP            | 0B54h D                     | Desktop     | [0fccef5d79](https://linux-hardware.org/?probe=0fccef5d79) | Nov 26, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [4552c13bb1](https://linux-hardware.org/?probe=4552c13bb1) | Nov 26, 2023 |
| Acer          | Veriton M290                | Desktop     | [30dd8ffe84](https://linux-hardware.org/?probe=30dd8ffe84) | Nov 26, 2023 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [b25d830579](https://linux-hardware.org/?probe=b25d830579) | Nov 26, 2023 |
| ASUSTek       | PN64                        | Mini pc     | [a39cb80b48](https://linux-hardware.org/?probe=a39cb80b48) | Nov 26, 2023 |
| ASRock        | G41M-GS3                    | Desktop     | [0e679ecab4](https://linux-hardware.org/?probe=0e679ecab4) | Nov 26, 2023 |
| Philco        | 14H                         | Notebook    | [f4256fe390](https://linux-hardware.org/?probe=f4256fe390) | Nov 26, 2023 |
| HP            | 8055                        | Desktop     | [88122b7512](https://linux-hardware.org/?probe=88122b7512) | Nov 26, 2023 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | Desktop     | [d384af59f3](https://linux-hardware.org/?probe=d384af59f3) | Nov 26, 2023 |
| Huanan        | X99-BD4 V1.1, NALEX         | Desktop     | [751dbeae2c](https://linux-hardware.org/?probe=751dbeae2c) | Nov 26, 2023 |
| Acer          | Swift SF514-56T             | Notebook    | [687fc34fd5](https://linux-hardware.org/?probe=687fc34fd5) | Nov 26, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [435a764eeb](https://linux-hardware.org/?probe=435a764eeb) | Nov 26, 2023 |
| Dell          | Inspiron 5770               | Notebook    | [c35b932f41](https://linux-hardware.org/?probe=c35b932f41) | Nov 26, 2023 |
| Medion        | MS-7728                     | Desktop     | [1e13c1a36d](https://linux-hardware.org/?probe=1e13c1a36d) | Nov 26, 2023 |
| Red Hat       | RHEL RHEL-9.2.0 PC          | Desktop     | [33dabf03ca](https://linux-hardware.org/?probe=33dabf03ca) | Nov 26, 2023 |
| Lenovo        | G580 20157                  | Notebook    | [f03f814b9c](https://linux-hardware.org/?probe=f03f814b9c) | Nov 26, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [6f475bfe64](https://linux-hardware.org/?probe=6f475bfe64) | Nov 26, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [66dac22b5a](https://linux-hardware.org/?probe=66dac22b5a) | Nov 26, 2023 |
| Intel         | NUC7i3BNB J22859-313        | Mini pc     | [306a30802a](https://linux-hardware.org/?probe=306a30802a) | Nov 26, 2023 |
| HP            | 3397                        | Desktop     | [a846952acf](https://linux-hardware.org/?probe=a846952acf) | Nov 26, 2023 |
| MSI           | H310M PRO-VH PLUS           | Desktop     | [f21d57f728](https://linux-hardware.org/?probe=f21d57f728) | Nov 26, 2023 |
| Lenovo        | ThinkPad T15p Gen 1 20TM... | Notebook    | [c333f48b93](https://linux-hardware.org/?probe=c333f48b93) | Nov 26, 2023 |
| Acer          | Aspire X1920                | Desktop     | [c97acbf5df](https://linux-hardware.org/?probe=c97acbf5df) | Nov 26, 2023 |
| Biostar       | H61MLV2                     | Desktop     | [1e2b4c3878](https://linux-hardware.org/?probe=1e2b4c3878) | Nov 26, 2023 |
| Shenzhen M... | F7BSC                       | Mini pc     | [ea77c54dd3](https://linux-hardware.org/?probe=ea77c54dd3) | Nov 26, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [aa7fb6a279](https://linux-hardware.org/?probe=aa7fb6a279) | Nov 26, 2023 |
| ASUSTek       | A55BM-E                     | Desktop     | [28fe1a1fe1](https://linux-hardware.org/?probe=28fe1a1fe1) | Nov 26, 2023 |
| Chuwi         | GemiBook Plus               | Notebook    | [6316398e5b](https://linux-hardware.org/?probe=6316398e5b) | Nov 26, 2023 |
| ASUSTek       | X75VC                       | Notebook    | [be2ff8350a](https://linux-hardware.org/?probe=be2ff8350a) | Nov 26, 2023 |
| Lenovo        | ThinkPad Edge E325 12973... | Notebook    | [0f165c67ac](https://linux-hardware.org/?probe=0f165c67ac) | Nov 26, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [f31c8412d9](https://linux-hardware.org/?probe=f31c8412d9) | Nov 26, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [f889c15ce7](https://linux-hardware.org/?probe=f889c15ce7) | Nov 26, 2023 |
| Gigabyte      | B560M DS3H AC               | Desktop     | [906f471cf6](https://linux-hardware.org/?probe=906f471cf6) | Nov 26, 2023 |
| HP            | 339A                        | Desktop     | [5cad333081](https://linux-hardware.org/?probe=5cad333081) | Nov 26, 2023 |
| HP            | Pavilion dv6                | Notebook    | [2f757867e7](https://linux-hardware.org/?probe=2f757867e7) | Nov 26, 2023 |
| Acer          | Aspire S5-371               | Notebook    | [d3efa32b61](https://linux-hardware.org/?probe=d3efa32b61) | Nov 26, 2023 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [eb3634e98f](https://linux-hardware.org/?probe=eb3634e98f) | Nov 26, 2023 |
| Dell          | Precision 7520              | Notebook    | [26c0a80c45](https://linux-hardware.org/?probe=26c0a80c45) | Nov 26, 2023 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [4f4c868c9a](https://linux-hardware.org/?probe=4f4c868c9a) | Nov 26, 2023 |
| Unknown       | Unknown                     | Notebook    | [2b84a63677](https://linux-hardware.org/?probe=2b84a63677) | Nov 26, 2023 |
| Lenovo        | IdeaPad Y580                | Notebook    | [c17c868d52](https://linux-hardware.org/?probe=c17c868d52) | Nov 26, 2023 |
| ASUSTek       | PRIME B760M-A D4            | Desktop     | [ef4ad69c79](https://linux-hardware.org/?probe=ef4ad69c79) | Nov 26, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [6cdf6e663e](https://linux-hardware.org/?probe=6cdf6e663e) | Nov 26, 2023 |
| Lenovo        | ThinkPad T450 20BUS20301    | Notebook    | [4d8f1df3d2](https://linux-hardware.org/?probe=4d8f1df3d2) | Nov 26, 2023 |
| Intel         | H61 V124A                   | Desktop     | [eaa125b476](https://linux-hardware.org/?probe=eaa125b476) | Nov 26, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [721fac0123](https://linux-hardware.org/?probe=721fac0123) | Nov 26, 2023 |
| Lenovo        | ThinkPad T440p 20AN0069U... | Notebook    | [79c8961819](https://linux-hardware.org/?probe=79c8961819) | Nov 26, 2023 |
| Gigabyte      | AM1M-S2H                    | Desktop     | [c3bdc08988](https://linux-hardware.org/?probe=c3bdc08988) | Nov 26, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [15da0b054a](https://linux-hardware.org/?probe=15da0b054a) | Nov 26, 2023 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | Desktop     | [1f874b5293](https://linux-hardware.org/?probe=1f874b5293) | Nov 26, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [a3f4bbe816](https://linux-hardware.org/?probe=a3f4bbe816) | Nov 25, 2023 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [5c990c2d29](https://linux-hardware.org/?probe=5c990c2d29) | Nov 25, 2023 |
| Toshiba       | Satellite L55t-A            | Notebook    | [b037dccb20](https://linux-hardware.org/?probe=b037dccb20) | Nov 25, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [af8e097b69](https://linux-hardware.org/?probe=af8e097b69) | Nov 25, 2023 |
| Lenovo        | ThinkPad X201 3680WFQ       | Notebook    | [3b6eaf2c6e](https://linux-hardware.org/?probe=3b6eaf2c6e) | Nov 25, 2023 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [7514ce50b9](https://linux-hardware.org/?probe=7514ce50b9) | Nov 25, 2023 |
| Shenzhen M... | F7BSC                       | Mini pc     | [dcd0e12b1b](https://linux-hardware.org/?probe=dcd0e12b1b) | Nov 25, 2023 |
| Dell          | Precision M6700             | Notebook    | [1817097d25](https://linux-hardware.org/?probe=1817097d25) | Nov 25, 2023 |
| Dell          | Latitude 5511               | Notebook    | [254abd404f](https://linux-hardware.org/?probe=254abd404f) | Nov 25, 2023 |
| ASRock        | H470M-ITX/ac                | Desktop     | [5b558c30c8](https://linux-hardware.org/?probe=5b558c30c8) | Nov 25, 2023 |
| HP            | ProBook 5330m               | Notebook    | [74e3bacd14](https://linux-hardware.org/?probe=74e3bacd14) | Nov 25, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [9c4c337fe9](https://linux-hardware.org/?probe=9c4c337fe9) | Nov 25, 2023 |
| Acer          | Aspire A515-52G             | Notebook    | [5b0ff6d81a](https://linux-hardware.org/?probe=5b0ff6d81a) | Nov 25, 2023 |
| Alienware     | x14                         | Notebook    | [af501023a5](https://linux-hardware.org/?probe=af501023a5) | Nov 25, 2023 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [cf23a5df5b](https://linux-hardware.org/?probe=cf23a5df5b) | Nov 25, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [381486f3da](https://linux-hardware.org/?probe=381486f3da) | Nov 25, 2023 |
| MSI           | PRO B760M-P DDR4            | Desktop     | [462b5c65a7](https://linux-hardware.org/?probe=462b5c65a7) | Nov 25, 2023 |
| HP            | 339A                        | Desktop     | [35c70dde9e](https://linux-hardware.org/?probe=35c70dde9e) | Nov 25, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [fd893be7c7](https://linux-hardware.org/?probe=fd893be7c7) | Nov 25, 2023 |
| Dell          | OptiPlex 745                | Desktop     | [1abbad3f94](https://linux-hardware.org/?probe=1abbad3f94) | Nov 23, 2023 |
| Gigabyte      | B85M-HD3                    | Desktop     | [5992237ea5](https://linux-hardware.org/?probe=5992237ea5) | Nov 15, 2023 |
| MSI           | A520M PRO                   | Desktop     | [b83b272494](https://linux-hardware.org/?probe=b83b272494) | Nov 06, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/OpenMandriva_5.0/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 6.6.2-desktop-1omv2390       | 547       | 98.56%  |
| 6.6.1-desktop-1omv2390       | 5         | 0.9%    |
| 6.7.0-desktop-0.rc2.1omv2390 | 2         | 0.36%   |
| 6.6.0-desktop-1omv2390       | 1         | 0.18%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.6.2   | 547       | 98.56%  |
| 6.6.1   | 5         | 0.9%    |
| 6.7.0   | 2         | 0.36%   |
| 6.6.0   | 1         | 0.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.6     | 553       | 99.64%  |
| 6.7     | 2         | 0.36%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 555       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| KDE5     | 414       | 74.59%  |
| LXQt     | 74        | 13.33%  |
| GNOME    | 64        | 11.53%  |
| Cinnamon | 2         | 0.36%   |
| Unknown  | 1         | 0.18%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 544       | 98.02%  |
| X11     | 10        | 1.8%    |
| Unknown | 1         | 0.18%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| SDDM | 491       | 88.47%  |
| GDM  | 64        | 11.53%  |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 299       | 53.87%  |
| de_DE | 46        | 8.29%   |
| ru_RU | 44        | 7.93%   |
| pl_PL | 34        | 6.13%   |
| it_IT | 22        | 3.96%   |
| fr_FR | 21        | 3.78%   |
| es_ES | 15        | 2.7%    |
| en_GB | 13        | 2.34%   |
| pt_BR | 9         | 1.62%   |
| cs_CZ | 7         | 1.26%   |
| es_AR | 4         | 0.72%   |
| en_CA | 4         | 0.72%   |
| tr_TR | 3         | 0.54%   |
| hu_HU | 3         | 0.54%   |
| es_MX | 3         | 0.54%   |
| en_IN | 3         | 0.54%   |
| UTF-8 | 2         | 0.36%   |
| pt_PT | 2         | 0.36%   |
| ja_JP | 2         | 0.36%   |
| en_NZ | 2         | 0.36%   |
| en_IL | 2         | 0.36%   |
| en_AU | 2         | 0.36%   |
| de_CH | 2         | 0.36%   |
| ro_RO | 1         | 0.18%   |
| nl_NL | 1         | 0.18%   |
| nb_NO | 1         | 0.18%   |
| fr_CA | 1         | 0.18%   |
| fr_BE | 1         | 0.18%   |
| es_VE | 1         | 0.18%   |
| es_DO | 1         | 0.18%   |
| es_CR | 1         | 0.18%   |
| en_NG | 1         | 0.18%   |
| en_HK | 1         | 0.18%   |
| de_AT | 1         | 0.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 340       | 61.26%  |
| BIOS | 215       | 38.74%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Overlay | 331       | 59.64%  |
| Ext4    | 207       | 37.3%   |
| Btrfs   | 12        | 2.16%   |
| Xfs     | 5         | 0.9%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 433       | 78.02%  |
| MBR  | 122       | 21.98%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 313       | 56.4%   |
| No        | 242       | 43.6%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 320       | 57.66%  |
| Yes       | 235       | 42.34%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Hewlett-Packard                      | 92        | 16.58%  |
| ASUSTek Computer                     | 81        | 14.59%  |
| Dell                                 | 75        | 13.51%  |
| Lenovo                               | 68        | 12.25%  |
| Gigabyte Technology                  | 41        | 7.39%   |
| Acer                                 | 35        | 6.31%   |
| MSI                                  | 26        | 4.68%   |
| ASRock                               | 21        | 3.78%   |
| Intel                                | 13        | 2.34%   |
| Apple                                | 12        | 2.16%   |
| Toshiba                              | 11        | 1.98%   |
| Fujitsu                              | 8         | 1.44%   |
| Medion                               | 6         | 1.08%   |
| AZW                                  | 5         | 0.9%    |
| Pegatron                             | 4         | 0.72%   |
| Packard Bell                         | 4         | 0.72%   |
| Biostar                              | 4         | 0.72%   |
| Unknown                              | 4         | 0.72%   |
| TUXEDO                               | 3         | 0.54%   |
| Shenzhen Meigao Electronic Equipment | 3         | 0.54%   |
| HUAWEI                               | 3         | 0.54%   |
| Foxconn                              | 3         | 0.54%   |
| eMachines                            | 3         | 0.54%   |
| Samsung Electronics                  | 2         | 0.36%   |
| Red Hat                              | 2         | 0.36%   |
| AMI                                  | 2         | 0.36%   |
| ZOTAC                                | 1         | 0.18%   |
| Timi                                 | 1         | 0.18%   |
| Sony                                 | 1         | 0.18%   |
| SLIMBOOK                             | 1         | 0.18%   |
| Philco                               | 1         | 0.18%   |
| Notebook                             | 1         | 0.18%   |
| MACHINIST                            | 1         | 0.18%   |
| Machcreator                          | 1         | 0.18%   |
| LG Electronics                       | 1         | 0.18%   |
| Lenovo Product                       | 1         | 0.18%   |
| Info Quest Technologies              | 1         | 0.18%   |
| Huanan                               | 1         | 0.18%   |
| Google                               | 1         | 0.18%   |
| GEEKOM                               | 1         | 0.18%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                              | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Unknown                                           | 7         | 1.26%   |
| Dell OptiPlex 780                                 | 4         | 0.72%   |
| Dell Inspiron 15 3515                             | 4         | 0.72%   |
| ASUS All Series                                   | 4         | 0.72%   |
| HP Compaq 610                                     | 3         | 0.54%   |
| Dell OptiPlex 9020                                | 3         | 0.54%   |
| Toshiba Satellite C660                            | 2         | 0.36%   |
| Shenzhen Meigao Electronic Equipment Venus series | 2         | 0.36%   |
| Red Hat KVM                                       | 2         | 0.36%   |
| MSI MS-7D67                                       | 2         | 0.36%   |
| MSI MS-7721                                       | 2         | 0.36%   |
| Lenovo IdeaPad 330S-15IKB 81F5                    | 2         | 0.36%   |
| Intel H61                                         | 2         | 0.36%   |
| HP Pavilion Gaming Laptop 15-ec0xxx               | 2         | 0.36%   |
| HP Pavilion dv7                                   | 2         | 0.36%   |
| HP Pavilion Desktop 590-p0xxx                     | 2         | 0.36%   |
| HP Laptop 17-by4xxx                               | 2         | 0.36%   |
| HP Laptop 15-dy2xxx                               | 2         | 0.36%   |
| HP EliteDesk 800 G2 DM 35W                        | 2         | 0.36%   |
| HP Compaq Pro 6300 MT                             | 2         | 0.36%   |
| HP Compaq 6730s                                   | 2         | 0.36%   |
| Gigabyte A320M-S2H                                | 2         | 0.36%   |
| Dell OptiPlex 745                                 | 2         | 0.36%   |
| Dell OptiPlex 7040                                | 2         | 0.36%   |
| Dell OptiPlex 7010                                | 2         | 0.36%   |
| Dell OptiPlex 5040                                | 2         | 0.36%   |
| Dell OptiPlex 3020                                | 2         | 0.36%   |
| Dell Latitude E5430 non-vPro                      | 2         | 0.36%   |
| Dell Latitude E5410                               | 2         | 0.36%   |
| Dell Inspiron 1545                                | 2         | 0.36%   |
| ASUS VivoBook_ASUSLaptop X513EA_K513EA            | 2         | 0.36%   |
| ASUS TUF B450M-PLUS GAMING                        | 2         | 0.36%   |
| ASUS PRIME B550M-A                                | 2         | 0.36%   |
| ASUS PRIME A520M-K                                | 2         | 0.36%   |
| ASUS PRIME A320M-K                                | 2         | 0.36%   |
| ASUS P8Z77-V LX                                   | 2         | 0.36%   |
| ASUS M5A97 R2.0                                   | 2         | 0.36%   |
| ASRock FM2A88X Extreme6+                          | 2         | 0.36%   |
| Apple MacBookAir9,1                               | 2         | 0.36%   |
| Apple iMac13,3                                    | 2         | 0.36%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo ThinkPad                            | 29        | 5.23%   |
| Acer Aspire                                | 25        | 4.5%    |
| Dell OptiPlex                              | 24        | 4.32%   |
| Lenovo IdeaPad                             | 18        | 3.24%   |
| Dell Latitude                              | 18        | 3.24%   |
| Dell Inspiron                              | 18        | 3.24%   |
| ASUS PRIME                                 | 17        | 3.06%   |
| HP Compaq                                  | 16        | 2.88%   |
| HP Laptop                                  | 15        | 2.7%    |
| HP Pavilion                                | 14        | 2.52%   |
| Toshiba Satellite                          | 10        | 1.8%    |
| ASUS VivoBook                              | 9         | 1.62%   |
| HP EliteDesk                               | 8         | 1.44%   |
| ASUS ROG                                   | 8         | 1.44%   |
| Dell Precision                             | 7         | 1.26%   |
| Unknown                                    | 7         | 1.26%   |
| HP ProBook                                 | 6         | 1.08%   |
| Lenovo ThinkCentre                         | 4         | 0.72%   |
| Intel H61                                  | 4         | 0.72%   |
| Dell XPS                                   | 4         | 0.72%   |
| ASUS All                                   | 4         | 0.72%   |
| Packard Bell EasyNote                      | 3         | 0.54%   |
| MSI Modern                                 | 3         | 0.54%   |
| HP Stream                                  | 3         | 0.54%   |
| HP ProDesk                                 | 3         | 0.54%   |
| HP EliteBook                               | 3         | 0.54%   |
| HP 250                                     | 3         | 0.54%   |
| Gigabyte B450                              | 3         | 0.54%   |
| Fujitsu LIFEBOOK                           | 3         | 0.54%   |
| Fujitsu ESPRIMO                            | 3         | 0.54%   |
| Dell Vostro                                | 3         | 0.54%   |
| ASUS TUF                                   | 3         | 0.54%   |
| Acer Veriton                               | 3         | 0.54%   |
| TUXEDO Book                                | 2         | 0.36%   |
| Shenzhen Meigao Electronic Equipment Venus | 2         | 0.36%   |
| Red Hat KVM                                | 2         | 0.36%   |
| MSI MS-7D67                                | 2         | 0.36%   |
| MSI MS-7721                                | 2         | 0.36%   |
| Lenovo Yoga                                | 2         | 0.36%   |
| Lenovo Legion                              | 2         | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2012 | 51        | 9.19%   |
| 2021 | 46        | 8.29%   |
| 2020 | 44        | 7.93%   |
| 2018 | 42        | 7.57%   |
| 2013 | 39        | 7.03%   |
| 2011 | 39        | 7.03%   |
| 2017 | 37        | 6.67%   |
| 2015 | 33        | 5.95%   |
| 2022 | 32        | 5.77%   |
| 2014 | 29        | 5.23%   |
| 2010 | 27        | 4.86%   |
| 2009 | 27        | 4.86%   |
| 2016 | 25        | 4.5%    |
| 2019 | 22        | 3.96%   |
| 2023 | 21        | 3.78%   |
| 2008 | 20        | 3.6%    |
| 2007 | 14        | 2.52%   |
| 2006 | 7         | 1.26%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 266       | 47.93%  |
| Notebook    | 262       | 47.21%  |
| All in one  | 12        | 2.16%   |
| Mini pc     | 10        | 1.8%    |
| Convertible | 5         | 0.9%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 555       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 554       | 99.82%  |
| Yes  | 1         | 0.18%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 149       | 26.85%  |
| 16.01-24.0  | 113       | 20.36%  |
| 8.01-16.0   | 109       | 19.64%  |
| 3.01-4.0    | 104       | 18.74%  |
| 32.01-64.0  | 37        | 6.67%   |
| 1.01-2.0    | 20        | 3.6%    |
| 24.01-32.0  | 13        | 2.34%   |
| 2.01-3.0    | 8         | 1.44%   |
| 64.01-256.0 | 1         | 0.18%   |
| 0.51-1.0    | 1         | 0.18%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 360       | 64.86%  |
| 2.01-3.0  | 102       | 18.38%  |
| 0.51-1.0  | 66        | 11.89%  |
| 3.01-4.0  | 14        | 2.52%   |
| 0.01-0.5  | 8         | 1.44%   |
| 4.01-8.0  | 4         | 0.72%   |
| 8.01-16.0 | 1         | 0.18%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 314       | 56.58%  |
| 2      | 153       | 27.57%  |
| 3      | 55        | 9.91%   |
| 4      | 14        | 2.52%   |
| 0      | 8         | 1.44%   |
| 6      | 3         | 0.54%   |
| 5      | 3         | 0.54%   |
| 7      | 2         | 0.36%   |
| 13     | 1         | 0.18%   |
| 9      | 1         | 0.18%   |
| 8      | 1         | 0.18%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 305       | 54.95%  |
| Yes       | 250       | 45.05%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 486       | 87.57%  |
| No        | 69        | 12.43%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 400       | 72.07%  |
| No        | 155       | 27.93%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 307       | 55.32%  |
| No        | 248       | 44.68%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 114       | 20.54%  |
| Germany     | 60        | 10.81%  |
| Russia      | 59        | 10.63%  |
| Poland      | 43        | 7.75%   |
| Italy       | 29        | 5.23%   |
| France      | 22        | 3.96%   |
| Brazil      | 21        | 3.78%   |
| Spain       | 18        | 3.24%   |
| UK          | 16        | 2.88%   |
| Canada      | 14        | 2.52%   |
| Hungary     | 12        | 2.16%   |
| Czechia     | 12        | 2.16%   |
| Turkey      | 9         | 1.62%   |
| Japan       | 9         | 1.62%   |
| Netherlands | 7         | 1.26%   |
| Australia   | 7         | 1.26%   |
| Romania     | 6         | 1.08%   |
| Norway      | 5         | 0.9%    |
| India       | 5         | 0.9%    |
| Greece      | 5         | 0.9%    |
| Thailand    | 4         | 0.72%   |
| Sweden      | 4         | 0.72%   |
| Mexico      | 4         | 0.72%   |
| Israel      | 4         | 0.72%   |
| China       | 4         | 0.72%   |
| Belgium     | 4         | 0.72%   |
| Ukraine     | 3         | 0.54%   |
| Switzerland | 3         | 0.54%   |
| Serbia      | 3         | 0.54%   |
| Indonesia   | 3         | 0.54%   |
| Belarus     | 3         | 0.54%   |
| Argentina   | 3         | 0.54%   |
| Portugal    | 2         | 0.36%   |
| Peru        | 2         | 0.36%   |
| New Zealand | 2         | 0.36%   |
| Malaysia    | 2         | 0.36%   |
| Lithuania   | 2         | 0.36%   |
| Egypt       | 2         | 0.36%   |
| Cyprus      | 2         | 0.36%   |
| Costa Rica  | 2         | 0.36%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Moscow         | 9         | 1.62%   |
| Warsaw         | 6         | 1.08%   |
| Prague         | 6         | 1.08%   |
| Citrus Heights | 6         | 1.08%   |
| St Petersburg  | 5         | 0.9%    |
| Budapest       | 5         | 0.9%    |
| Stuhr          | 4         | 0.72%   |
| Sao Paulo      | 4         | 0.72%   |
| Rome           | 4         | 0.72%   |
| Oliveira       | 4         | 0.72%   |
| Munich         | 4         | 0.72%   |
| Milan          | 4         | 0.72%   |
| Wroclaw        | 3         | 0.54%   |
| Rio de Janeiro | 3         | 0.54%   |
| Poznan         | 3         | 0.54%   |
| Paris          | 3         | 0.54%   |
| Novosibirsk    | 3         | 0.54%   |
| Leipzig        | 3         | 0.54%   |
| Le Grau-du-Roi | 3         | 0.54%   |
| Krasnodar      | 3         | 0.54%   |
| Hemet          | 3         | 0.54%   |
| Glen Burnie    | 3         | 0.54%   |
| Delhi          | 3         | 0.54%   |
| Dallas         | 3         | 0.54%   |
| Bologna        | 3         | 0.54%   |
| Berlin         | 3         | 0.54%   |
| Barnaul        | 3         | 0.54%   |
| Barcelona      | 3         | 0.54%   |
| Wiesloch       | 2         | 0.36%   |
| Voronezh       | 2         | 0.36%   |
| Volgograd      | 2         | 0.36%   |
| Ulyanovsk      | 2         | 0.36%   |
| Uberlingen     | 2         | 0.36%   |
| Tucson         | 2         | 0.36%   |
| Tokyo          | 2         | 0.36%   |
| Tampa          | 2         | 0.36%   |
| Sydney         | 2         | 0.36%   |
| Saratov        | 2         | 0.36%   |
| San José      | 2         | 0.36%   |
| Rossville      | 2         | 0.36%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 128       | 142    | 15.53%  |
| Seagate                     | 86        | 102    | 10.44%  |
| Samsung Electronics         | 83        | 99     | 10.07%  |
| Kingston                    | 65        | 69     | 7.89%   |
| Toshiba                     | 47        | 48     | 5.7%    |
| SanDisk                     | 38        | 40     | 4.61%   |
| Crucial                     | 30        | 32     | 3.64%   |
| Hitachi                     | 28        | 28     | 3.4%    |
| Unknown                     | 23        | 26     | 2.79%   |
| China                       | 18        | 19     | 2.18%   |
| SPCC                        | 17        | 20     | 2.06%   |
| SK hynix                    | 14        | 14     | 1.7%    |
| Micron Technology           | 13        | 15     | 1.58%   |
| Intel                       | 13        | 13     | 1.58%   |
| A-DATA Technology           | 13        | 14     | 1.58%   |
| JMicron Technology          | 12        | 12     | 1.46%   |
| Intenso                     | 11        | 11     | 1.33%   |
| GOODRAM                     | 11        | 11     | 1.33%   |
| HGST                        | 10        | 10     | 1.21%   |
| Unknown                     | 9         | 9      | 1.09%   |
| Apple                       | 7         | 7      | 0.85%   |
| PNY                         | 5         | 6      | 0.61%   |
| HPQ                         | 5         | 5      | 0.61%   |
| Apacer                      | 5         | 5      | 0.61%   |
| Team                        | 4         | 4      | 0.49%   |
| MSI                         | 4         | 4      | 0.49%   |
| Lexar                       | 4         | 4      | 0.49%   |
| Kingston Technology Company | 4         | 4      | 0.49%   |
| UMIS                        | 3         | 3      | 0.36%   |
| SSSTC                       | 3         | 3      | 0.36%   |
| Smartbuy                    | 3         | 3      | 0.36%   |
| Silicon Motion              | 3         | 3      | 0.36%   |
| Phison                      | 3         | 4      | 0.36%   |
| Patriot                     | 3         | 3      | 0.36%   |
| Netac                       | 3         | 3      | 0.36%   |
| LITEON                      | 3         | 3      | 0.36%   |
| Hewlett-Packard             | 3         | 3      | 0.36%   |
| Gigabyte Technology         | 3         | 3      | 0.36%   |
| Fanxiang                    | 3         | 4      | 0.36%   |
| Dogfish                     | 3         | 3      | 0.36%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD  | 12        | 1.37%   |
| SanDisk NVMe SSD Drive 1TB       | 11        | 1.26%   |
| Seagate ST500DM002-1BD142 500GB  | 9         | 1.03%   |
| Kingston SA400S37120G 120GB SSD  | 9         | 1.03%   |
| Unknown                          | 9         | 1.03%   |
| Unknown SD/MMC/MS PRO 256GB      | 8         | 0.91%   |
| Toshiba MQ04ABF100 1TB           | 8         | 0.91%   |
| Toshiba DT01ACA100 1TB           | 8         | 0.91%   |
| JMicron Generic 8GB              | 8         | 0.91%   |
| SPCC Solid State Disk 256GB      | 5         | 0.57%   |
| Kingston SNVS500G 500GB          | 5         | 0.57%   |
| Kingston SA400S37480G 480GB SSD  | 5         | 0.57%   |
| HPQ BF450DASTK 450GB             | 5         | 0.57%   |
| Toshiba HDWD130 3TB              | 4         | 0.46%   |
| SPCC Solid State Disk 512GB      | 4         | 0.46%   |
| Seagate ST500LT012-1DG142 500GB  | 4         | 0.46%   |
| Seagate ST2000DM001-1ER164 2TB   | 4         | 0.46%   |
| Seagate ST1000DM003-1ER162 1TB   | 4         | 0.46%   |
| Samsung SSD 870 QVO 1TB          | 4         | 0.46%   |
| JMicron Tech 250GB               | 4         | 0.46%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 3         | 0.34%   |
| WDC WDS100T3X0C-00SJG0 1TB       | 3         | 0.34%   |
| WDC WD10EZEX-08WN4A0 1TB         | 3         | 0.34%   |
| WDC WD10EZEX-00BBHA0 1TB         | 3         | 0.34%   |
| Unknown NVMe SSD Drive 512GB     | 3         | 0.34%   |
| SPCC M.2 PCIe SSD 512GB          | 3         | 0.34%   |
| Seagate ST9500325AS 500GB        | 3         | 0.34%   |
| Seagate ST2000DM008-2FR102 2TB   | 3         | 0.34%   |
| Seagate ST1000DM010-2EP102 1TB   | 3         | 0.34%   |
| SanDisk NVMe SSD Drive 512GB     | 3         | 0.34%   |
| SanDisk NVMe SSD Drive 500GB     | 3         | 0.34%   |
| Samsung SSD 970 EVO Plus 500GB   | 3         | 0.34%   |
| Samsung SSD 870 EVO 500GB        | 3         | 0.34%   |
| Samsung SSD 860 EVO 250GB        | 3         | 0.34%   |
| Samsung SSD 840 EVO 250GB        | 3         | 0.34%   |
| Samsung SSD 840 EVO 120GB        | 3         | 0.34%   |
| Kingston Company SNV2S1000G 1TB  | 3         | 0.34%   |
| Kingston SUV400S37120G 120GB SSD | 3         | 0.34%   |
| Kingston SNV2S500G 500GB         | 3         | 0.34%   |
| Kingston SKC3000S1024G 1024GB    | 3         | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 98        | 107    | 32.24%  |
| Seagate             | 82        | 98     | 26.97%  |
| Toshiba             | 42        | 43     | 13.82%  |
| Hitachi             | 28        | 28     | 9.21%   |
| HGST                | 10        | 10     | 3.29%   |
| Unknown             | 8         | 8      | 2.63%   |
| JMicron Technology  | 8         | 8      | 2.63%   |
| Samsung Electronics | 7         | 8      | 2.3%    |
| HPQ                 | 5         | 5      | 1.64%   |
| Apple               | 3         | 3      | 0.99%   |
| TO Exter            | 2         | 2      | 0.66%   |
| Intenso             | 2         | 2      | 0.66%   |
| Fujitsu             | 2         | 2      | 0.66%   |
| WD MediaMax         | 1         | 1      | 0.33%   |
| SSK                 | 1         | 1      | 0.33%   |
| Maxtor              | 1         | 1      | 0.33%   |
| KESU                | 1         | 1      | 0.33%   |
| Inateck             | 1         | 1      | 0.33%   |
| External            | 1         | 1      | 0.33%   |
| CIRAGO              | 1         | 1      | 0.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 46        | 52     | 15.18%  |
| Kingston            | 43        | 45     | 14.19%  |
| Crucial             | 20        | 22     | 6.6%    |
| SanDisk             | 19        | 19     | 6.27%   |
| China               | 18        | 19     | 5.94%   |
| WDC                 | 14        | 14     | 4.62%   |
| SPCC                | 14        | 16     | 4.62%   |
| GOODRAM             | 10        | 10     | 3.3%    |
| Intenso             | 8         | 8      | 2.64%   |
| A-DATA Technology   | 8         | 8      | 2.64%   |
| Micron Technology   | 6         | 8      | 1.98%   |
| PNY                 | 5         | 6      | 1.65%   |
| Intel               | 5         | 5      | 1.65%   |
| Apacer              | 5         | 5      | 1.65%   |
| LITEON              | 3         | 3      | 0.99%   |
| Hewlett-Packard     | 3         | 3      | 0.99%   |
| Dogfish             | 3         | 3      | 0.99%   |
| ASMT                | 3         | 3      | 0.99%   |
| Unknown             | 3         | 3      | 0.99%   |
| Verbatim            | 2         | 2      | 0.66%   |
| Transcend           | 2         | 2      | 0.66%   |
| Smartbuy            | 2         | 2      | 0.66%   |
| SK hynix            | 2         | 2      | 0.66%   |
| SABRENT             | 2         | 3      | 0.66%   |
| PNY USB             | 2         | 2      | 0.66%   |
| OCZ                 | 2         | 2      | 0.66%   |
| LITEONIT            | 2         | 2      | 0.66%   |
| KIOXIA-EXCERIA      | 2         | 2      | 0.66%   |
| KingFast            | 2         | 2      | 0.66%   |
| Fanxiang            | 2         | 2      | 0.66%   |
| Dahua               | 2         | 3      | 0.66%   |
| AMD                 | 2         | 2      | 0.66%   |
| XrayDisk            | 1         | 2      | 0.33%   |
| Western             | 1         | 1      | 0.33%   |
| Vaseky              | 1         | 1      | 0.33%   |
| USB3.0              | 1         | 1      | 0.33%   |
| USB                 | 1         | 1      | 0.33%   |
| TwinMOS             | 1         | 1      | 0.33%   |
| TSA                 | 1         | 1      | 0.33%   |
| Toshiba             | 1         | 1      | 0.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 260       | 331    | 36.26%  |
| SSD     | 256       | 323    | 35.7%   |
| NVMe    | 173       | 209    | 24.13%  |
| MMC     | 18        | 22     | 2.51%   |
| Unknown | 10        | 11     | 1.39%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 416       | 592    | 62.37%  |
| NVMe | 171       | 201    | 25.64%  |
| SAS  | 62        | 81     | 9.3%    |
| MMC  | 18        | 22     | 2.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 335       | 432    | 63.45%  |
| 0.51-1.0   | 144       | 162    | 27.27%  |
| 1.01-2.0   | 30        | 38     | 5.68%   |
| 2.01-3.0   | 8         | 8      | 1.52%   |
| 3.01-4.0   | 6         | 9      | 1.14%   |
| 4.01-10.0  | 3         | 3      | 0.57%   |
| 10.01-20.0 | 2         | 2      | 0.38%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 221       | 39.82%  |
| 101-250        | 98        | 17.66%  |
| 251-500        | 70        | 12.61%  |
| Unknown        | 37        | 6.67%   |
| 51-100         | 35        | 6.31%   |
| 21-50          | 34        | 6.13%   |
| 501-1000       | 27        | 4.86%   |
| 1001-2000      | 24        | 4.32%   |
| More than 3000 | 6         | 1.08%   |
| 2001-3000      | 3         | 0.54%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 408       | 73.51%  |
| Unknown        | 37        | 6.67%   |
| 21-50          | 31        | 5.59%   |
| 101-250        | 19        | 3.42%   |
| 51-100         | 19        | 3.42%   |
| 0              | 18        | 3.24%   |
| 251-500        | 12        | 2.16%   |
| 501-1000       | 7         | 1.26%   |
| 2001-3000      | 2         | 0.36%   |
| More than 3000 | 1         | 0.18%   |
| 1001-2000      | 1         | 0.18%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB  | 5         | 5      | 3.94%   |
| Seagate ST9500325AS 500GB        | 3         | 3      | 2.36%   |
| Seagate ST500LT012-1DG142 500GB  | 3         | 3      | 2.36%   |
| Crucial CT275MX300SSD1 275GB     | 3         | 3      | 2.36%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 2         | 2      | 1.57%   |
| Seagate ST320LT007-9ZV142 320GB  | 2         | 2      | 1.57%   |
| Seagate ST2000DM001-1CH164 2TB   | 2         | 3      | 1.57%   |
| Seagate ST1000DM003-1ER162 1TB   | 2         | 2      | 1.57%   |
| Hitachi HTS723232L9A360 320GB    | 2         | 2      | 1.57%   |
| Hitachi HTS545050B9A300 500GB    | 2         | 2      | 1.57%   |
| Hitachi HTS545032B9A300 320GB    | 2         | 2      | 1.57%   |
| Hitachi HDS721010CLA332 1TB      | 2         | 2      | 1.57%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 1         | 1      | 0.79%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 1         | 1      | 0.79%   |
| WDC WDS100T2G0A-00JH30 1TB SSD   | 1         | 1      | 0.79%   |
| WDC WD800JB-32JJC0 80GB          | 1         | 1      | 0.79%   |
| WDC WD6401AALS-00L3B2 640GB      | 1         | 1      | 0.79%   |
| WDC WD5000LPVX-22V0TT0 500GB     | 1         | 1      | 0.79%   |
| WDC WD5000LPCX-24VHAT0 500GB     | 1         | 1      | 0.79%   |
| WDC WD5000AAKX-221CA1 500GB      | 1         | 1      | 0.79%   |
| WDC WD5000AAKX-08U6AA0 500GB     | 1         | 1      | 0.79%   |
| WDC WD5000AAKX-083CA1 500GB      | 1         | 1      | 0.79%   |
| WDC WD5000AAKX-07U6AA1 500GB     | 1         | 1      | 0.79%   |
| WDC WD5000AAKX-00ERMA0 500GB     | 1         | 1      | 0.79%   |
| WDC WD5000AAKX-001CA0 500GB      | 1         | 1      | 0.79%   |
| WDC WD3200BPVT-80JJ5T0 320GB     | 1         | 1      | 0.79%   |
| WDC WD3200BEVT-75A23T0 320GB     | 1         | 1      | 0.79%   |
| WDC WD3200BEKT-08PVMT1 320GB     | 1         | 1      | 0.79%   |
| WDC WD3200AAKS-61L9A0 320GB      | 1         | 1      | 0.79%   |
| WDC WD3200AAJS-56M0A0 320GB      | 1         | 1      | 0.79%   |
| WDC WD2500YS-01SHB1 256GB        | 1         | 1      | 0.79%   |
| WDC WD2500BEVT-60ZCT1 250GB      | 1         | 1      | 0.79%   |
| WDC WD2500BEVT-22ZCT0 250GB      | 1         | 1      | 0.79%   |
| WDC WD2500BEVT-22A23T0 250GB     | 1         | 1      | 0.79%   |
| WDC WD20EFRX-68AX9N0 2TB         | 1         | 1      | 0.79%   |
| WDC WD20EARX-00PASB0 2TB         | 1         | 1      | 0.79%   |
| WDC WD1600BEVT-75A23T0 160GB     | 1         | 1      | 0.79%   |
| WDC WD1600BEKT-60F3T1 160GB      | 1         | 1      | 0.79%   |
| WDC WD1600AAJS-60B4A0 160GB      | 1         | 1      | 0.79%   |
| WDC WD15EARS-00Z5B1 1TB          | 1         | 1      | 0.79%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 34        | 37     | 27.64%  |
| Seagate             | 34        | 36     | 27.64%  |
| Hitachi             | 11        | 11     | 8.94%   |
| Toshiba             | 7         | 7      | 5.69%   |
| Samsung Electronics | 5         | 5      | 4.07%   |
| HGST                | 5         | 5      | 4.07%   |
| Kingston            | 4         | 4      | 3.25%   |
| Crucial             | 3         | 3      | 2.44%   |
| China               | 3         | 3      | 2.44%   |
| SanDisk             | 2         | 2      | 1.63%   |
| A-DATA Technology   | 2         | 2      | 1.63%   |
| WD MediaMax         | 1         | 1      | 0.81%   |
| Transcend           | 1         | 1      | 0.81%   |
| Team                | 1         | 1      | 0.81%   |
| SPCC                | 1         | 1      | 0.81%   |
| OCZ                 | 1         | 1      | 0.81%   |
| Maxtor              | 1         | 1      | 0.81%   |
| LITEONIT            | 1         | 1      | 0.81%   |
| Lexar               | 1         | 1      | 0.81%   |
| JMicron Technology  | 1         | 1      | 0.81%   |
| Intel               | 1         | 1      | 0.81%   |
| Dogfish             | 1         | 1      | 0.81%   |
| Apple               | 1         | 1      | 0.81%   |
| AMD                 | 1         | 1      | 0.81%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 34        | 36     | 35.79%  |
| WDC                 | 30        | 33     | 31.58%  |
| Hitachi             | 11        | 11     | 11.58%  |
| Toshiba             | 7         | 7      | 7.37%   |
| Samsung Electronics | 5         | 5      | 5.26%   |
| HGST                | 5         | 5      | 5.26%   |
| WD MediaMax         | 1         | 1      | 1.05%   |
| Maxtor              | 1         | 1      | 1.05%   |
| Apple               | 1         | 1      | 1.05%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 91        | 100    | 76.47%  |
| SSD     | 24        | 24     | 20.17%  |
| NVMe    | 3         | 3      | 2.52%   |
| Unknown | 1         | 1      | 0.84%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Samsung Electronics HD103SJ 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 458       | 665    | 69.92%  |
| Malfunc  | 115       | 128    | 17.56%  |
| Detected | 81        | 102    | 12.37%  |
| Failed   | 1         | 1      | 0.15%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 376       | 53.11%  |
| AMD                                     | 108       | 15.25%  |
| SanDisk                                 | 36        | 5.08%   |
| Samsung Electronics                     | 34        | 4.8%    |
| Kingston Technology Company             | 27        | 3.81%   |
| Phison Electronics                      | 15        | 2.12%   |
| SK hynix                                | 12        | 1.69%   |
| ASMedia Technology                      | 12        | 1.69%   |
| Nvidia                                  | 10        | 1.41%   |
| Micron/Crucial Technology               | 10        | 1.41%   |
| Silicon Motion                          | 9         | 1.27%   |
| MAXIO Technology (Hangzhou)             | 8         | 1.13%   |
| JMicron Technology                      | 8         | 1.13%   |
| Micron Technology                       | 7         | 0.99%   |
| Marvell Technology Group                | 5         | 0.71%   |
| KIOXIA                                  | 4         | 0.56%   |
| ADATA Technology                        | 4         | 0.56%   |
| Solid State Storage Technology          | 3         | 0.42%   |
| Realtek Semiconductor                   | 3         | 0.42%   |
| Apple                                   | 3         | 0.42%   |
| Union Memory (Shenzhen)                 | 2         | 0.28%   |
| Toshiba America Info Systems            | 2         | 0.28%   |
| Seagate Technology                      | 2         | 0.28%   |
| Broadcom / LSI                          | 2         | 0.28%   |
| VIA Technologies                        | 1         | 0.14%   |
| Silicon Image                           | 1         | 0.14%   |
| Shenzhen Unionmemory Information System | 1         | 0.14%   |
| Shenzhen Longsys Electronics            | 1         | 0.14%   |
| Netac Technology                        | 1         | 0.14%   |
| Adaptec                                 | 1         | 0.14%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 65        | 8.02%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 32        | 3.95%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 29        | 3.58%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 22        | 2.72%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 19        | 2.35%   |
| Intel Volume Management Device NVMe RAID Controller                              | 17        | 2.1%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 17        | 2.1%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 15        | 1.85%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 14        | 1.73%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 14        | 1.73%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 13        | 1.6%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 12        | 1.48%   |
| Intel SATA Controller [RAID mode]                                                | 12        | 1.48%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 12        | 1.48%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 12        | 1.48%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 11        | 1.36%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                    | 11        | 1.36%   |
| AMD 500 Series Chipset SATA Controller                                           | 11        | 1.36%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 10        | 1.23%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 9         | 1.11%   |
| Intel Tiger Lake-LP SATA Controller                                              | 9         | 1.11%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 9         | 1.11%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 9         | 1.11%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 9         | 1.11%   |
| AMD 400 Series Chipset SATA Controller                                           | 9         | 1.11%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 8         | 0.99%   |
| Intel Comet Lake SATA AHCI Controller                                            | 8         | 0.99%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 8         | 0.99%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 8         | 0.99%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 8         | 0.99%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                         | 7         | 0.86%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 7         | 0.86%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 7         | 0.86%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 6         | 0.74%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 6         | 0.74%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 6         | 0.74%   |
| Kingston Company NV1 NVMe SSD SM2263XT (DRAM-less)                               | 6         | 0.74%   |
| JMicron JMB363 SATA/IDE Controller                                               | 6         | 0.74%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 6         | 0.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 6         | 0.74%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 409       | 58.1%   |
| NVMe | 171       | 24.29%  |
| IDE  | 75        | 10.65%  |
| RAID | 48        | 6.82%   |
| SCSI | 1         | 0.14%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 414       | 74.59%  |
| AMD    | 141       | 25.41%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 6         | 1.08%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 6         | 1.08%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 6         | 1.08%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 6         | 1.08%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 5         | 0.9%    |
| Intel Core i5-3337U CPU @ 1.80GHz             | 5         | 0.9%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 5         | 0.9%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 5         | 0.9%    |
| Intel Core i7-8700 CPU @ 3.20GHz              | 4         | 0.72%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 4         | 0.72%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 4         | 0.72%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 0.72%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 0.72%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 4         | 0.72%   |
| Intel Core i3-6100U CPU @ 2.30GHz             | 4         | 0.72%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 4         | 0.72%   |
| Intel 12th Gen Core i5-12500H                 | 4         | 0.72%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 0.72%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 4         | 0.72%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 4         | 0.72%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 0.72%   |
| AMD Ryzen 5 3450U with Radeon Vega Mobile Gfx | 4         | 0.72%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 3         | 0.54%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 3         | 0.54%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 0.54%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 3         | 0.54%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 3         | 0.54%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 0.54%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 0.54%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 3         | 0.54%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 3         | 0.54%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 3         | 0.54%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 3         | 0.54%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 3         | 0.54%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 3         | 0.54%   |
| Intel Core i3-10100 CPU @ 3.60GHz             | 3         | 0.54%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 3         | 0.54%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 3         | 0.54%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 3         | 0.54%   |
| Intel 12th Gen Core i7-12700H                 | 3         | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 117       | 21.08%  |
| Intel Core i3           | 61        | 10.99%  |
| Intel Core i7           | 58        | 10.45%  |
| Other                   | 46        | 8.29%   |
| Intel Celeron           | 40        | 7.21%   |
| AMD Ryzen 5             | 37        | 6.67%   |
| Intel Core 2 Duo        | 22        | 3.96%   |
| Intel Pentium           | 19        | 3.42%   |
| AMD Ryzen 7             | 16        | 2.88%   |
| Intel Xeon              | 11        | 1.98%   |
| Intel Pentium Dual-Core | 11        | 1.98%   |
| AMD Ryzen 9             | 9         | 1.62%   |
| AMD A8                  | 9         | 1.62%   |
| AMD FX                  | 8         | 1.44%   |
| AMD Ryzen 3             | 7         | 1.26%   |
| AMD Athlon              | 7         | 1.26%   |
| AMD A6                  | 7         | 1.26%   |
| AMD E                   | 5         | 0.9%    |
| AMD A10                 | 5         | 0.9%    |
| Intel Pentium Gold      | 4         | 0.72%   |
| Intel Pentium Dual      | 4         | 0.72%   |
| Intel Genuine           | 4         | 0.72%   |
| Intel Core i9           | 4         | 0.72%   |
| Intel Core 2 Quad       | 4         | 0.72%   |
| Intel Atom              | 4         | 0.72%   |
| AMD A4                  | 4         | 0.72%   |
| Intel Pentium Silver    | 3         | 0.54%   |
| AMD Phenom II X4        | 3         | 0.54%   |
| AMD Athlon 64 X2        | 3         | 0.54%   |
| Intel Core 2            | 2         | 0.36%   |
| AMD E2                  | 2         | 0.36%   |
| AMD E1                  | 2         | 0.36%   |
| AMD Athlon II Dual-Core | 2         | 0.36%   |
| AMD Athlon Dual Core    | 2         | 0.36%   |
| Intel Pentium 4         | 1         | 0.18%   |
| Intel Core 2 Solo       | 1         | 0.18%   |
| AMD V140                | 1         | 0.18%   |
| AMD V120                | 1         | 0.18%   |
| AMD Turion 64 X2 Mobile | 1         | 0.18%   |
| AMD Ryzen 7 PRO         | 1         | 0.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 247       | 44.5%   |
| 4      | 194       | 34.95%  |
| 6      | 43        | 7.75%   |
| 8      | 32        | 5.77%   |
| 1      | 11        | 1.98%   |
| 12     | 10        | 1.8%    |
| 10     | 8         | 1.44%   |
| 14     | 6         | 1.08%   |
| 3      | 3         | 0.54%   |
| 16     | 1         | 0.18%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 552       | 99.46%  |
| 6      | 1         | 0.18%   |
| 4      | 1         | 0.18%   |
| 2      | 1         | 0.18%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 329       | 59.28%  |
| 1      | 226       | 40.72%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 555       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 429       | 77.3%   |
| 0x08108109 | 16        | 2.88%   |
| 0x0a50000d | 6         | 1.08%   |
| 0x08608103 | 6         | 1.08%   |
| 0x0a50000c | 5         | 0.9%    |
| 0x06001119 | 5         | 0.9%    |
| 0x0a20120a | 4         | 0.72%   |
| 0x0800820d | 4         | 0.72%   |
| 0x07030105 | 4         | 0.72%   |
| 0x0700010b | 4         | 0.72%   |
| 0x06001116 | 4         | 0.72%   |
| 0x010000b6 | 4         | 0.72%   |
| 0x0a704104 | 3         | 0.54%   |
| 0x0a404102 | 3         | 0.54%   |
| 0x08701030 | 3         | 0.54%   |
| 0x08108102 | 3         | 0.54%   |
| 0x08001138 | 3         | 0.54%   |
| 0x06003106 | 3         | 0.54%   |
| 0x0a601206 | 2         | 0.36%   |
| 0x0a50000f | 2         | 0.36%   |
| 0x08608102 | 2         | 0.36%   |
| 0x08600109 | 2         | 0.36%   |
| 0x0810100b | 2         | 0.36%   |
| 0x07030104 | 2         | 0.36%   |
| 0x06006705 | 2         | 0.36%   |
| 0x06000822 | 2         | 0.36%   |
| 0x06000613 | 2         | 0.36%   |
| 0x0500010d | 2         | 0.36%   |
| 0x05000101 | 2         | 0.36%   |
| 0x05000028 | 2         | 0.36%   |
| 0x03000027 | 2         | 0.36%   |
| 0x0a704103 | 1         | 0.18%   |
| 0x0a601203 | 1         | 0.18%   |
| 0x0a20120e | 1         | 0.18%   |
| 0x08701021 | 1         | 0.18%   |
| 0x08600104 | 1         | 0.18%   |
| 0x08600103 | 1         | 0.18%   |
| 0x08200103 | 1         | 0.18%   |
| 0x08101016 | 1         | 0.18%   |
| 0x08001129 | 1         | 0.18%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 61        | 10.99%  |
| IvyBridge        | 51        | 9.19%   |
| Haswell          | 40        | 7.21%   |
| Skylake          | 35        | 6.31%   |
| Penryn           | 34        | 6.13%   |
| SandyBridge      | 33        | 5.95%   |
| Zen+             | 23        | 4.14%   |
| Alderlake Hybrid | 22        | 3.96%   |
| Westmere         | 20        | 3.6%    |
| Zen 3            | 19        | 3.42%   |
| Unknown          | 19        | 3.42%   |
| Core             | 18        | 3.24%   |
| TigerLake        | 17        | 3.06%   |
| CometLake        | 17        | 3.06%   |
| Silvermont       | 14        | 2.52%   |
| Piledriver       | 12        | 2.16%   |
| K10              | 11        | 1.98%   |
| Icelake          | 11        | 1.98%   |
| Zen              | 10        | 1.8%    |
| Goldmont plus    | 10        | 1.8%    |
| Broadwell        | 9         | 1.62%   |
| Zen 2            | 8         | 1.44%   |
| Puma             | 7         | 1.26%   |
| K8 Hammer        | 7         | 1.26%   |
| Goldmont         | 6         | 1.08%   |
| Bobcat           | 6         | 1.08%   |
| Nehalem          | 5         | 0.9%    |
| Bulldozer        | 5         | 0.9%    |
| Tremont          | 4         | 0.72%   |
| Steamroller      | 4         | 0.72%   |
| K10 Llano        | 4         | 0.72%   |
| Jaguar           | 4         | 0.72%   |
| Excavator        | 3         | 0.54%   |
| Bonnell          | 3         | 0.54%   |
| Gracemont        | 2         | 0.36%   |
| NetBurst         | 1         | 0.18%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 323       | 52.52%  |
| AMD                                  | 145       | 23.58%  |
| Nvidia                               | 142       | 23.09%  |
| Red Hat                              | 2         | 0.33%   |
| NVidia / SGS Thomson (Joint Venture) | 2         | 0.33%   |
| ATI Technologies                     | 1         | 0.16%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 28        | 4.47%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 22        | 3.51%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 21        | 3.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 17        | 2.71%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 17        | 2.71%   |
| Intel HD Graphics 530                                                                    | 16        | 2.55%   |
| Intel UHD Graphics 620                                                                   | 14        | 2.23%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 13        | 2.07%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 12        | 1.91%   |
| Intel Core Processor Integrated Graphics Controller                                      | 12        | 1.91%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 10        | 1.59%   |
| Intel HD Graphics 620                                                                    | 10        | 1.59%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 9         | 1.44%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 9         | 1.44%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 9         | 1.44%   |
| Intel HD Graphics 630                                                                    | 8         | 1.28%   |
| Intel HD Graphics 5500                                                                   | 8         | 1.28%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 1.28%   |
| AMD Lucienne                                                                             | 8         | 1.28%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 8         | 1.28%   |
| Nvidia GT218 [GeForce 210]                                                               | 7         | 1.12%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 7         | 1.12%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 0.96%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 6         | 0.96%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 0.96%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 6         | 0.96%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 5         | 0.8%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 5         | 0.8%    |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 5         | 0.8%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 0.8%    |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 5         | 0.8%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 5         | 0.8%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 4         | 0.64%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 4         | 0.64%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 0.64%   |
| Intel JasperLake [UHD Graphics]                                                          | 4         | 0.64%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 0.64%   |
| Intel HD Graphics 500                                                                    | 4         | 0.64%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4         | 0.64%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 4         | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                                          | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| 1 x Intel                                     | 245       | 44.14%  |
| 1 x AMD                                       | 126       | 22.7%   |
| 1 x Nvidia                                    | 87        | 15.68%  |
| Intel + Nvidia                                | 48        | 8.65%   |
| 2 x Intel                                     | 25        | 4.5%    |
| 2 x AMD                                       | 9         | 1.62%   |
| AMD + Nvidia                                  | 6         | 1.08%   |
| Intel + AMD                                   | 5         | 0.9%    |
| 1 x Red Hat                                   | 2         | 0.36%   |
| 1 x NVidia / SGS Thomson (Joint Venture)      | 1         | 0.18%   |
| Nvidia + NVidia / SGS Thomson (Joint Venture) | 1         | 0.18%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 542       | 97.66%  |
| Proprietary | 7         | 1.26%   |
| Unknown     | 6         | 1.08%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 284       | 51.17%  |
| 1.01-2.0   | 78        | 14.05%  |
| 0.01-0.5   | 68        | 12.25%  |
| 0.51-1.0   | 52        | 9.37%   |
| 3.01-4.0   | 36        | 6.49%   |
| 7.01-8.0   | 11        | 1.98%   |
| 5.01-6.0   | 9         | 1.62%   |
| 8.01-16.0  | 9         | 1.62%   |
| 2.01-3.0   | 7         | 1.26%   |
| 16.01-24.0 | 1         | 0.18%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 73        | 13.04%  |
| Samsung Electronics     | 72        | 12.86%  |
| Chimei Innolux          | 46        | 8.21%   |
| BOE                     | 41        | 7.32%   |
| LG Display              | 39        | 6.96%   |
| Hewlett-Packard         | 33        | 5.89%   |
| Dell                    | 31        | 5.54%   |
| Goldstar                | 30        | 5.36%   |
| Philips                 | 19        | 3.39%   |
| AOC                     | 18        | 3.21%   |
| Lenovo                  | 17        | 3.04%   |
| Acer                    | 17        | 3.04%   |
| Apple                   | 14        | 2.5%    |
| Ancor Communications    | 12        | 2.14%   |
| Sharp                   | 8         | 1.43%   |
| NEC Computers           | 7         | 1.25%   |
| Iiyama                  | 7         | 1.25%   |
| ASUSTek Computer        | 7         | 1.25%   |
| Chi Mei Optoelectronics | 6         | 1.07%   |
| Sony                    | 5         | 0.89%   |
| BenQ                    | 5         | 0.89%   |
| ViewSonic               | 4         | 0.71%   |
| Unknown                 | 3         | 0.54%   |
| LG Philips              | 3         | 0.54%   |
| CSO                     | 3         | 0.54%   |
| ___                     | 2         | 0.36%   |
| TMX                     | 2         | 0.36%   |
| RTK                     | 2         | 0.36%   |
| RHT                     | 2         | 0.36%   |
| PANDA                   | 2         | 0.36%   |
| HannStar                | 2         | 0.36%   |
| GDH                     | 2         | 0.36%   |
| Fujitsu Siemens         | 2         | 0.36%   |
| Denver                  | 2         | 0.36%   |
| XYK                     | 1         | 0.18%   |
| Wacom                   | 1         | 0.18%   |
| Vizio                   | 1         | 0.18%   |
| TFT                     | 1         | 0.18%   |
| Sceptre Tech            | 1         | 0.18%   |
| Pioneer                 | 1         | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 6         | 1.07%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 5         | 0.89%   |
| AOC 27G2G8 AOC2702 1920x1080 598x336mm 27.0-inch                      | 5         | 0.89%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 4         | 0.71%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 4         | 0.71%   |
| Chimei Innolux LCD Monitor CMN15E5 1920x1080 344x193mm 15.5-inch      | 4         | 0.71%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 4         | 0.71%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 4         | 0.71%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 3         | 0.53%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch         | 3         | 0.53%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 3         | 0.53%   |
| Lenovo LEN E2002bA LEN60BB 1600x900 432x240mm 19.5-inch               | 3         | 0.53%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 3         | 0.53%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 3         | 0.53%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 0.53%   |
| Apple iMac APPA012 1920x1080 475x267mm 21.5-inch                      | 3         | 0.53%   |
| Samsung Electronics SMBX2331 SAM076E 1920x1080 509x286mm 23.0-inch    | 2         | 0.36%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch     | 2         | 0.36%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 2         | 0.36%   |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch  | 2         | 0.36%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 2         | 0.36%   |
| RTK LCD Monitor RTK1D1A 1920x1080 1020x570mm 46.0-inch                | 2         | 0.36%   |
| RHT QEMU Monitor RHT1234 2048x1152 325x203mm 15.1-inch                | 2         | 0.36%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 2         | 0.36%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch           | 2         | 0.36%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 2         | 0.36%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch               | 2         | 0.36%   |
| Hewlett-Packard 24yh HPN3504 1920x1080 528x297mm 23.9-inch            | 2         | 0.36%   |
| Goldstar W2252 GSM567D 1680x1050 474x296mm 22.0-inch                  | 2         | 0.36%   |
| Goldstar W2243 GSM56FE 1920x1080 477x268mm 21.5-inch                  | 2         | 0.36%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                   | 2         | 0.36%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch               | 2         | 0.36%   |
| GDH Digital TV GDH0030 1920x540                                       | 2         | 0.36%   |
| Dell P2312H DEL4077 1920x1080 510x287mm 23.0-inch                     | 2         | 0.36%   |
| Dell P2312H DEL4076 1920x1080 510x287mm 23.0-inch                     | 2         | 0.36%   |
| Dell P2219H DELA115 1920x1080 476x267mm 21.5-inch                     | 2         | 0.36%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch       | 2         | 0.36%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 2         | 0.36%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 2         | 0.36%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch       | 2         | 0.36%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 248       | 44.6%   |
| 1366x768 (WXGA)    | 111       | 19.96%  |
| 3840x2160 (4K)     | 36        | 6.47%   |
| 1600x900 (HD+)     | 30        | 5.4%    |
| 1280x1024 (SXGA)   | 22        | 3.96%   |
| 1920x1200 (WUXGA)  | 21        | 3.78%   |
| 2560x1440 (QHD)    | 16        | 2.88%   |
| 1680x1050 (WSXGA+) | 15        | 2.7%    |
| 1280x800 (WXGA)    | 13        | 2.34%   |
| 1440x900 (WXGA+)   | 11        | 1.98%   |
| 2560x1600          | 8         | 1.44%   |
| 2560x1080          | 4         | 0.72%   |
| 1360x768           | 4         | 0.72%   |
| 2880x1800          | 3         | 0.54%   |
| 2048x1152          | 2         | 0.36%   |
| 1920x540           | 2         | 0.36%   |
| 1024x768 (XGA)     | 2         | 0.36%   |
| 1024x600           | 2         | 0.36%   |
| 3840x2400          | 1         | 0.18%   |
| 3440x1440          | 1         | 0.18%   |
| 3200x1800 (QHD+)   | 1         | 0.18%   |
| 3000x2000          | 1         | 0.18%   |
| 2288x1287          | 1         | 0.18%   |
| 1600x1200          | 1         | 0.18%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 140       | 24.91%  |
| 27      | 48        | 8.54%   |
| 24      | 46        | 8.19%   |
| 23      | 45        | 8.01%   |
| 21      | 45        | 8.01%   |
| 13      | 41        | 7.3%    |
| 17      | 34        | 6.05%   |
| 14      | 34        | 6.05%   |
| 19      | 24        | 4.27%   |
| 18      | 12        | 2.14%   |
| 16      | 10        | 1.78%   |
| 22      | 9         | 1.6%    |
| 20      | 8         | 1.42%   |
| Unknown | 8         | 1.42%   |
| 31      | 7         | 1.25%   |
| 11      | 7         | 1.25%   |
| 84      | 6         | 1.07%   |
| 40      | 6         | 1.07%   |
| 72      | 4         | 0.71%   |
| 12      | 4         | 0.71%   |
| 34      | 3         | 0.53%   |
| 52      | 2         | 0.36%   |
| 46      | 2         | 0.36%   |
| 29      | 2         | 0.36%   |
| 28      | 2         | 0.36%   |
| 25      | 2         | 0.36%   |
| 10      | 2         | 0.36%   |
| 142     | 1         | 0.18%   |
| 85      | 1         | 0.18%   |
| 60      | 1         | 0.18%   |
| 49      | 1         | 0.18%   |
| 48      | 1         | 0.18%   |
| 43      | 1         | 0.18%   |
| 41      | 1         | 0.18%   |
| 37      | 1         | 0.18%   |
| 32      | 1         | 0.18%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 205       | 36.61%  |
| 501-600        | 132       | 23.57%  |
| 401-500        | 93        | 16.61%  |
| 351-400        | 45        | 8.04%   |
| 201-300        | 33        | 5.89%   |
| 601-700        | 12        | 2.14%   |
| 1501-2000      | 11        | 1.96%   |
| Unknown        | 8         | 1.43%   |
| 801-900        | 7         | 1.25%   |
| 1001-1500      | 7         | 1.25%   |
| 701-800        | 4         | 0.71%   |
| 901-1000       | 2         | 0.36%   |
| More than 2000 | 1         | 0.18%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 425       | 79.14%  |
| 16/10   | 72        | 13.41%  |
| 5/4     | 20        | 3.72%   |
| 3/2     | 6         | 1.12%   |
| 21/9    | 5         | 0.93%   |
| 4/3     | 4         | 0.74%   |
| 32/9    | 2         | 0.37%   |
| Unknown | 2         | 0.37%   |
| 1.00    | 1         | 0.19%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 140       | 24.91%  |
| 201-250        | 120       | 21.35%  |
| 81-90          | 58        | 10.32%  |
| 301-350        | 50        | 8.9%    |
| 151-200        | 45        | 8.01%   |
| 121-130        | 21        | 3.74%   |
| 141-150        | 20        | 3.56%   |
| 71-80          | 17        | 3.02%   |
| More than 1000 | 16        | 2.85%   |
| 251-300        | 15        | 2.67%   |
| 351-500        | 13        | 2.31%   |
| 501-1000       | 12        | 2.14%   |
| 111-120        | 10        | 1.78%   |
| Unknown        | 8         | 1.42%   |
| 51-60          | 7         | 1.25%   |
| 61-70          | 4         | 0.71%   |
| 131-140        | 4         | 0.71%   |
| 41-50          | 2         | 0.36%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 230       | 41.44%  |
| 101-120       | 164       | 29.55%  |
| 121-160       | 111       | 20%     |
| 161-240       | 24        | 4.32%   |
| 1-50          | 12        | 2.16%   |
| Unknown       | 8         | 1.44%   |
| More than 240 | 6         | 1.08%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 508       | 91.53%  |
| 2     | 32        | 5.77%   |
| 0     | 13        | 2.34%   |
| 3     | 2         | 0.36%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 310       | 38.65%  |
| Intel                           | 239       | 29.8%   |
| Qualcomm Atheros                | 88        | 10.97%  |
| Broadcom                        | 48        | 5.99%   |
| MediaTek                        | 14        | 1.75%   |
| Ralink                          | 13        | 1.62%   |
| Broadcom Limited                | 13        | 1.62%   |
| Ralink Technology               | 10        | 1.25%   |
| Marvell Technology Group        | 10        | 1.25%   |
| TP-Link                         | 9         | 1.12%   |
| ASIX Electronics                | 9         | 1.12%   |
| Nvidia                          | 7         | 0.87%   |
| Xiaomi                          | 4         | 0.5%    |
| NetGear                         | 3         | 0.37%   |
| Belkin Components               | 3         | 0.37%   |
| Huawei Technologies             | 2         | 0.25%   |
| ASUSTek Computer                | 2         | 0.25%   |
| ZyXEL Communications            | 1         | 0.12%   |
| ZTE WCDMA Technologies MSM      | 1         | 0.12%   |
| VIA Technologies                | 1         | 0.12%   |
| Sierra Wireless                 | 1         | 0.12%   |
| Samsung Electronics             | 1         | 0.12%   |
| Qualcomm Atheros Communications | 1         | 0.12%   |
| PLANEX                          | 1         | 0.12%   |
| Padix (Rockfire)                | 1         | 0.12%   |
| Motorola PCS                    | 1         | 0.12%   |
| Microsoft                       | 1         | 0.12%   |
| Interlogix.                     | 1         | 0.12%   |
| IMC Networks                    | 1         | 0.12%   |
| HMD Global                      | 1         | 0.12%   |
| Emtec                           | 1         | 0.12%   |
| Edimax Technology               | 1         | 0.12%   |
| DisplayLink                     | 1         | 0.12%   |
| Dell                            | 1         | 0.12%   |
| 3Com                            | 1         | 0.12%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 226       | 24.35%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 32        | 3.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 25        | 2.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 21        | 2.26%   |
| Intel Ethernet Connection I217-LM                                      | 15        | 1.62%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 14        | 1.51%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 13        | 1.4%    |
| Intel Wireless 8265 / 8275                                             | 13        | 1.4%    |
| Intel Wi-Fi 6 AX201                                                    | 12        | 1.29%   |
| Realtek RTL8125 2.5GbE Controller                                      | 11        | 1.19%   |
| Intel Wireless 7260                                                    | 11        | 1.19%   |
| Intel Wi-Fi 6 AX200                                                    | 11        | 1.19%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 11        | 1.19%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 11        | 1.19%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 10        | 1.08%   |
| Intel Wireless 7265                                                    | 10        | 1.08%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 9         | 0.97%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 8         | 0.86%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 8         | 0.86%   |
| Intel Wireless 8260                                                    | 8         | 0.86%   |
| Intel Wireless 3165                                                    | 8         | 0.86%   |
| Intel Ethernet Connection (2) I219-LM                                  | 8         | 0.86%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 8         | 0.86%   |
| ASIX AX88179 Gigabit Ethernet                                          | 8         | 0.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 7         | 0.75%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 7         | 0.75%   |
| Intel I211 Gigabit Network Connection                                  | 7         | 0.75%   |
| Intel Ethernet Connection (2) I219-V                                   | 7         | 0.75%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 6         | 0.65%   |
| Ralink MT7601U Wireless Adapter                                        | 6         | 0.65%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 6         | 0.65%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 6         | 0.65%   |
| Broadcom BCM43142 802.11b/g/n                                          | 6         | 0.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 5         | 0.54%   |
| Realtek 802.11ac NIC                                                   | 5         | 0.54%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 5         | 0.54%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 5         | 0.54%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                   | 5         | 0.54%   |
| Intel Ethernet Controller I225-V                                       | 5         | 0.54%   |
| Intel Ethernet Connection I219-LM                                      | 5         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 162       | 39.42%  |
| Realtek Semiconductor           | 83        | 20.19%  |
| Qualcomm Atheros                | 65        | 15.82%  |
| Broadcom                        | 32        | 7.79%   |
| Ralink                          | 13        | 3.16%   |
| MediaTek                        | 12        | 2.92%   |
| Ralink Technology               | 10        | 2.43%   |
| TP-Link                         | 9         | 2.19%   |
| Broadcom Limited                | 9         | 2.19%   |
| NetGear                         | 3         | 0.73%   |
| Belkin Components               | 3         | 0.73%   |
| ASUSTek Computer                | 2         | 0.49%   |
| ZyXEL Communications            | 1         | 0.24%   |
| Sierra Wireless                 | 1         | 0.24%   |
| Qualcomm Atheros Communications | 1         | 0.24%   |
| PLANEX                          | 1         | 0.24%   |
| Microsoft                       | 1         | 0.24%   |
| IMC Networks                    | 1         | 0.24%   |
| Edimax Technology               | 1         | 0.24%   |
| Dell                            | 1         | 0.24%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 21        | 5.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 14        | 3.39%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 13        | 3.15%   |
| Intel Wireless 8265 / 8275                                     | 13        | 3.15%   |
| Intel Wi-Fi 6 AX201                                            | 12        | 2.91%   |
| Intel Wireless 7260                                            | 11        | 2.66%   |
| Intel Wi-Fi 6 AX200                                            | 11        | 2.66%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 11        | 2.66%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 11        | 2.66%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 10        | 2.42%   |
| Intel Wireless 7265                                            | 10        | 2.42%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 9         | 2.18%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 8         | 1.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 8         | 1.94%   |
| Intel Wireless 8260                                            | 8         | 1.94%   |
| Intel Wireless 3165                                            | 8         | 1.94%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 8         | 1.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 7         | 1.69%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 6         | 1.45%   |
| Ralink MT7601U Wireless Adapter                                | 6         | 1.45%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 6         | 1.45%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 6         | 1.45%   |
| Broadcom BCM43142 802.11b/g/n                                  | 6         | 1.45%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5         | 1.21%   |
| Realtek 802.11ac NIC                                           | 5         | 1.21%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 5         | 1.21%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 5         | 1.21%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 5         | 1.21%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 4         | 0.97%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 4         | 0.97%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 4         | 0.97%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 4         | 0.97%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 4         | 0.97%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 4         | 0.97%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                         | 4         | 0.97%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 4         | 0.97%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 3         | 0.73%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 3         | 0.73%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 3         | 0.73%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 3         | 0.73%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 277       | 54.96%  |
| Intel                      | 131       | 25.99%  |
| Qualcomm Atheros           | 29        | 5.75%   |
| Broadcom                   | 24        | 4.76%   |
| Marvell Technology Group   | 10        | 1.98%   |
| ASIX Electronics           | 9         | 1.79%   |
| Nvidia                     | 7         | 1.39%   |
| Xiaomi                     | 4         | 0.79%   |
| Broadcom Limited           | 4         | 0.79%   |
| MediaTek                   | 2         | 0.4%    |
| ZTE WCDMA Technologies MSM | 1         | 0.2%    |
| VIA Technologies           | 1         | 0.2%    |
| Samsung Electronics        | 1         | 0.2%    |
| Huawei Technologies        | 1         | 0.2%    |
| HMD Global                 | 1         | 0.2%    |
| DisplayLink                | 1         | 0.2%    |
| 3Com                       | 1         | 0.2%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 226       | 44.49%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 32        | 6.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 25        | 4.92%   |
| Intel Ethernet Connection I217-LM                                      | 15        | 2.95%   |
| Realtek RTL8125 2.5GbE Controller                                      | 11        | 2.17%   |
| Intel Ethernet Connection (2) I219-LM                                  | 8         | 1.57%   |
| ASIX AX88179 Gigabit Ethernet                                          | 8         | 1.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 7         | 1.38%   |
| Intel I211 Gigabit Network Connection                                  | 7         | 1.38%   |
| Intel Ethernet Connection (2) I219-V                                   | 7         | 1.38%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                   | 5         | 0.98%   |
| Intel Ethernet Controller I225-V                                       | 5         | 0.98%   |
| Intel Ethernet Connection I219-LM                                      | 5         | 0.98%   |
| Intel 82577LM Gigabit Network Connection                               | 5         | 0.98%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 5         | 0.98%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 4         | 0.79%   |
| Nvidia MCP61 Ethernet                                                  | 4         | 0.79%   |
| Intel Ethernet Connection (7) I219-V                                   | 4         | 0.79%   |
| Intel Ethernet Connection (5) I219-LM                                  | 4         | 0.79%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 4         | 0.79%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 3         | 0.59%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                             | 3         | 0.59%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 3         | 0.59%   |
| Intel Ethernet Connection I218-LM                                      | 3         | 0.59%   |
| Intel Ethernet Connection (4) I219-V                                   | 3         | 0.59%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 0.59%   |
| Intel Ethernet Connection (11) I219-LM                                 | 3         | 0.59%   |
| Intel 82579V Gigabit Network Connection                                | 3         | 0.59%   |
| Intel 82578DM Gigabit Network Connection                               | 3         | 0.59%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                | 3         | 0.59%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                | 3         | 0.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 2         | 0.39%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2         | 0.39%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 2         | 0.39%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 2         | 0.39%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 2         | 0.39%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 2         | 0.39%   |
| MediaTek File-CD Gadget                                                | 2         | 0.39%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 2         | 0.39%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 2         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 484       | 54.38%  |
| WiFi     | 399       | 44.83%  |
| Unknown  | 5         | 0.56%   |
| Modem    | 2         | 0.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 280       | 51.76%  |
| WiFi     | 261       | 48.24%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 285       | 51.35%  |
| 1     | 254       | 45.77%  |
| 0     | 9         | 1.62%   |
| 3     | 7         | 1.26%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 375       | 67.57%  |
| Yes  | 180       | 32.43%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 132       | 42.72%  |
| Realtek Semiconductor           | 41        | 13.27%  |
| Qualcomm Atheros Communications | 23        | 7.44%   |
| Cambridge Silicon Radio         | 21        | 6.8%    |
| Broadcom                        | 17        | 5.5%    |
| Lite-On Technology              | 11        | 3.56%   |
| IMC Networks                    | 11        | 3.56%   |
| Apple                           | 10        | 3.24%   |
| Foxconn / Hon Hai               | 7         | 2.27%   |
| ASUSTek Computer                | 7         | 2.27%   |
| Dell                            | 6         | 1.94%   |
| Ralink                          | 5         | 1.62%   |
| MediaTek                        | 5         | 1.62%   |
| Hewlett-Packard                 | 5         | 1.62%   |
| Toshiba                         | 3         | 0.97%   |
| Foxconn International           | 2         | 0.65%   |
| TP-Link                         | 1         | 0.32%   |
| Integrated System Solution      | 1         | 0.32%   |
| Belkin Components               | 1         | 0.32%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 49        | 15.86%  |
| Intel AX201 Bluetooth                               | 26        | 8.41%   |
| Realtek Bluetooth Radio                             | 25        | 8.09%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 21        | 6.8%    |
| Qualcomm Atheros  Bluetooth Device                  | 15        | 4.85%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 15        | 4.85%   |
| Realtek  Bluetooth 4.2 Adapter                      | 14        | 4.53%   |
| Intel Wireless-AC 3168 Bluetooth                    | 11        | 3.56%   |
| Intel Bluetooth Device                              | 11        | 3.56%   |
| Intel AX200 Bluetooth                               | 11        | 3.56%   |
| Ralink RT3290 Bluetooth                             | 5         | 1.62%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 5         | 1.62%   |
| MediaTek Wireless_Device                            | 5         | 1.62%   |
| Lite-On Atheros AR3012 Bluetooth                    | 4         | 1.29%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4         | 1.29%   |
| Intel AX210 Bluetooth                               | 4         | 1.29%   |
| IMC Networks Bluetooth Radio                        | 4         | 1.29%   |
| HP Broadcom 2070 Bluetooth Combo                    | 4         | 1.29%   |
| Dell DW375 Bluetooth Module                         | 4         | 1.29%   |
| Apple Bluetooth Host Controller                     | 4         | 1.29%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 0.97%   |
| IMC Networks Wireless_Device                        | 3         | 0.97%   |
| IMC Networks Bluetooth Device                       | 3         | 0.97%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 0.97%   |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 0.97%   |
| Apple Bluetooth USB Host Controller                 | 3         | 0.97%   |
| Realtek RTL8723B Bluetooth                          | 2         | 0.65%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 0.65%   |
| Lite-On Bluetooth Device                            | 2         | 0.65%   |
| Foxconn International BCM43142A0 Bluetooth module   | 2         | 0.65%   |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 0.65%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 0.65%   |
| Dell BCM20702A0 Bluetooth Module                    | 2         | 0.65%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 0.65%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2         | 0.65%   |
| ASUS Bluetooth Radio                                | 2         | 0.65%   |
| ASUS ASUS USB-BT500                                 | 2         | 0.65%   |
| TP-Link UB500 Adapter                               | 1         | 0.32%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.32%   |
| Toshiba Integrated Bluetooth (Taiyo Yuden)          | 1         | 0.32%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 403       | 56.92%  |
| AMD                         | 153       | 21.61%  |
| Nvidia                      | 103       | 14.55%  |
| C-Media Electronics         | 15        | 2.12%   |
| Creative Labs               | 5         | 0.71%   |
| Logitech                    | 3         | 0.42%   |
| Generalplus Technology      | 3         | 0.42%   |
| Apple                       | 3         | 0.42%   |
| Tenx Technology             | 2         | 0.28%   |
| Razer USA                   | 2         | 0.28%   |
| Micro Star International    | 2         | 0.28%   |
| ASUSTek Computer            | 2         | 0.28%   |
| XMOS                        | 1         | 0.14%   |
| VIA Technologies            | 1         | 0.14%   |
| Realtek Semiconductor       | 1         | 0.14%   |
| Nordic Semiconductor ASA    | 1         | 0.14%   |
| Medeli Electronics          | 1         | 0.14%   |
| JMTek                       | 1         | 0.14%   |
| FiiO Electronics Technology | 1         | 0.14%   |
| Ensoniq                     | 1         | 0.14%   |
| Corsair                     | 1         | 0.14%   |
| Cambridge Silicon Radio     | 1         | 0.14%   |
| ATI Technologies            | 1         | 0.14%   |
| Unknown                     | 1         | 0.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 59        | 6.86%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 42        | 4.88%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 41        | 4.77%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 38        | 4.42%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 32        | 3.72%   |
| AMD FCH Azalia Controller                                                                         | 30        | 3.49%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 24        | 2.79%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 24        | 2.79%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 23        | 2.67%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 22        | 2.56%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 22        | 2.56%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 22        | 2.56%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 18        | 2.09%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 17        | 1.98%   |
| Intel 200 Series PCH HD Audio                                                                     | 14        | 1.63%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 13        | 1.51%   |
| Nvidia High Definition Audio Controller                                                           | 12        | 1.4%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 12        | 1.4%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 11        | 1.28%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 11        | 1.28%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 11        | 1.28%   |
| AMD Kabini HDMI/DP Audio                                                                          | 11        | 1.28%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 10        | 1.16%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 10        | 1.16%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 9         | 1.05%   |
| Intel Comet Lake PCH cAVS                                                                         | 9         | 1.05%   |
| Intel Cannon Lake PCH cAVS                                                                        | 9         | 1.05%   |
| Intel Broadwell-U Audio Controller                                                                | 8         | 0.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 8         | 0.93%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 8         | 0.93%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 7         | 0.81%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 7         | 0.81%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 7         | 0.81%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 7         | 0.81%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 6         | 0.7%    |
| Nvidia GK107 HDMI Audio Controller                                                                | 6         | 0.7%    |
| Nvidia GF119 HDMI Audio Controller                                                                | 6         | 0.7%    |
| Nvidia GA106 High Definition Audio Controller                                                     | 6         | 0.7%    |
| Intel Comet Lake PCH-V cAVS                                                                       | 6         | 0.7%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 122       | 18.29%  |
| SK hynix                     | 106       | 15.89%  |
| Kingston                     | 80        | 11.99%  |
| Micron Technology            | 78        | 11.69%  |
| Unknown                      | 57        | 8.55%   |
| Crucial                      | 38        | 5.7%    |
| Nanya Technology             | 21        | 3.15%   |
| G.Skill                      | 21        | 3.15%   |
| A-DATA Technology            | 20        | 3%      |
| Corsair                      | 19        | 2.85%   |
| Elpida                       | 15        | 2.25%   |
| Ramaxel Technology           | 9         | 1.35%   |
| Unknown (ABCD)               | 6         | 0.9%    |
| Team                         | 6         | 0.9%    |
| Patriot                      | 6         | 0.9%    |
| AMD                          | 5         | 0.75%   |
| Unknown                      | 5         | 0.75%   |
| Silicon Power                | 4         | 0.6%    |
| Juhor                        | 4         | 0.6%    |
| GOODRAM                      | 4         | 0.6%    |
| Timetec                      | 3         | 0.45%   |
| Wilk                         | 2         | 0.3%    |
| Transcend                    | 2         | 0.3%    |
| SHARETRONIC                  | 2         | 0.3%    |
| Red Hat                      | 2         | 0.3%    |
| PNY                          | 2         | 0.3%    |
| Patriot Memory (PDP Systems) | 2         | 0.3%    |
| Golden Empire                | 2         | 0.3%    |
| Unknown (89F7)               | 1         | 0.15%   |
| Unknown (268C)               | 1         | 0.15%   |
| Unknown (0x0B5E)             | 1         | 0.15%   |
| Unknown (0x0080)             | 1         | 0.15%   |
| Toshiba                      | 1         | 0.15%   |
| Teclast                      | 1         | 0.15%   |
| TakeMS                       | 1         | 0.15%   |
| Swissbit                     | 1         | 0.15%   |
| Smart                        | 1         | 0.15%   |
| Qimonda                      | 1         | 0.15%   |
| PUSKILL                      | 1         | 0.15%   |
| PSC                          | 1         | 0.15%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 7         | 0.95%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 6         | 0.82%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s            | 6         | 0.82%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 6         | 0.82%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 6         | 0.82%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s                 | 6         | 0.82%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 5         | 0.68%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 5         | 0.68%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 5         | 0.68%   |
| Unknown                                                             | 5         | 0.68%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                         | 4         | 0.54%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s               | 4         | 0.54%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 4         | 0.54%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 4         | 0.54%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 4         | 0.54%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s                | 4         | 0.54%   |
| Juhor RAM JHD2666S1908JG 8GB SODIMM DDR4 2667MT/s                   | 4         | 0.54%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                         | 3         | 0.41%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                           | 3         | 0.41%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                                | 3         | 0.41%   |
| Unknown RAM Module 2GB DIMM SDRAM                                   | 3         | 0.41%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                                | 3         | 0.41%   |
| Unknown RAM Module 1GB DIMM                                         | 3         | 0.41%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s      | 3         | 0.41%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 3         | 0.41%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s                 | 3         | 0.41%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 0.41%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 0.41%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 0.41%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 3         | 0.41%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 3         | 0.41%   |
| SK hynix RAM HMA851U6AFR6N-UH 4GB DIMM DDR4 2400MT/s                | 3         | 0.41%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 3         | 0.41%   |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s                           | 3         | 0.41%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 3         | 0.41%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 3         | 0.41%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s               | 3         | 0.41%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s         | 3         | 0.41%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 3         | 0.41%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s                 | 3         | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 221       | 38.91%  |
| DDR4    | 214       | 37.68%  |
| SDRAM   | 33        | 5.81%   |
| DDR2    | 25        | 4.4%    |
| LPDDR4  | 18        | 3.17%   |
| Unknown | 17        | 2.99%   |
| DDR5    | 15        | 2.64%   |
| LPDDR5  | 9         | 1.58%   |
| DDR     | 8         | 1.41%   |
| LPDDR3  | 4         | 0.7%    |
| RAM     | 2         | 0.35%   |
| DRAM    | 2         | 0.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 274       | 49.64%  |
| DIMM         | 248       | 44.93%  |
| Row Of Chips | 25        | 4.53%   |
| Chip         | 3         | 0.54%   |
| Unknown      | 2         | 0.36%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 229       | 36.88%  |
| 4096  | 188       | 30.27%  |
| 2048  | 106       | 17.07%  |
| 16384 | 59        | 9.5%    |
| 1024  | 25        | 4.03%   |
| 32768 | 11        | 1.77%   |
| 512   | 2         | 0.32%   |
| 12536 | 1         | 0.16%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 146       | 23.36%  |
| 3200    | 75        | 12%     |
| 2667    | 66        | 10.56%  |
| 1333    | 56        | 8.96%   |
| 2400    | 48        | 7.68%   |
| 1334    | 23        | 3.68%   |
| 2133    | 20        | 3.2%    |
| 800     | 20        | 3.2%    |
| 667     | 16        | 2.56%   |
| Unknown | 14        | 2.24%   |
| 2048    | 11        | 1.76%   |
| 6400    | 9         | 1.44%   |
| 4199    | 8         | 1.28%   |
| 3600    | 8         | 1.28%   |
| 3266    | 8         | 1.28%   |
| 2933    | 8         | 1.28%   |
| 1067    | 8         | 1.28%   |
| 4800    | 7         | 1.12%   |
| 3733    | 7         | 1.12%   |
| 2666    | 6         | 0.96%   |
| 4267    | 5         | 0.8%    |
| 1800    | 5         | 0.8%    |
| 1867    | 4         | 0.64%   |
| 6000    | 3         | 0.48%   |
| 5600    | 3         | 0.48%   |
| 3400    | 3         | 0.48%   |
| 3066    | 3         | 0.48%   |
| 1866    | 3         | 0.48%   |
| 1400    | 3         | 0.48%   |
| 5200    | 2         | 0.32%   |
| 3866    | 2         | 0.32%   |
| 2200    | 2         | 0.32%   |
| 1066    | 2         | 0.32%   |
| 975     | 2         | 0.32%   |
| 8400    | 1         | 0.16%   |
| 4533    | 1         | 0.16%   |
| 3534    | 1         | 0.16%   |
| 3533    | 1         | 0.16%   |
| 3500    | 1         | 0.16%   |
| 3466    | 1         | 0.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 4         | 26.67%  |
| Brother Industries  | 4         | 26.67%  |
| Canon               | 3         | 20%     |
| Seiko Epson         | 2         | 13.33%  |
| Samsung Electronics | 1         | 6.67%   |
| Prolific Technology | 1         | 6.67%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| HP LaserJet 1018                | 2         | 13.33%  |
| Canon CanoScan LiDE 300         | 2         | 13.33%  |
| Seiko Epson L3150 Series        | 1         | 6.67%   |
| Seiko Epson ET-2820 Series      | 1         | 6.67%   |
| Samsung M2020 Series            | 1         | 6.67%   |
| Prolific PL2305 Parallel Port   | 1         | 6.67%   |
| HP DeskJet F4200 series         | 1         | 6.67%   |
| HP DeskJet 4670 series          | 1         | 6.67%   |
| Canon PIXMA MG3600 Series       | 1         | 6.67%   |
| Brother MFC-J1010DW             | 1         | 6.67%   |
| Brother HL-2270DW Laser Printer | 1         | 6.67%   |
| Brother HL-2140 series          | 1         | 6.67%   |
| Brother DCP-7010                | 1         | 6.67%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 110 | 2         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 67        | 24.01%  |
| Microdia                               | 20        | 7.17%   |
| IMC Networks                           | 19        | 6.81%   |
| Cheng Uei Precision Industry (Foxlink) | 15        | 5.38%   |
| Bison Electronics                      | 15        | 5.38%   |
| Sunplus Innovation Technology          | 14        | 5.02%   |
| Quanta                                 | 14        | 5.02%   |
| Apple                                  | 14        | 5.02%   |
| Logitech                               | 13        | 4.66%   |
| Realtek Semiconductor                  | 12        | 4.3%    |
| Suyin                                  | 11        | 3.94%   |
| Syntek                                 | 8         | 2.87%   |
| Luxvisions Innotech Limited            | 7         | 2.51%   |
| Lite-On Technology                     | 7         | 2.51%   |
| Acer                                   | 5         | 1.79%   |
| Lenovo                                 | 4         | 1.43%   |
| Importek                               | 4         | 1.43%   |
| Alcor Micro                            | 4         | 1.43%   |
| Sonix Technology                       | 3         | 1.08%   |
| Silicon Motion                         | 2         | 0.72%   |
| Ricoh                                  | 2         | 0.72%   |
| Microsoft                              | 2         | 0.72%   |
| Linux Foundation                       | 2         | 0.72%   |
| BUFFALO                                | 2         | 0.72%   |
| Z-Star Microelectronics                | 1         | 0.36%   |
| USB Camera                             | 1         | 0.36%   |
| Sunplus Technology                     | 1         | 0.36%   |
| Samsung Electronics                    | 1         | 0.36%   |
| OPPO Electronics                       | 1         | 0.36%   |
| Netchip Technology                     | 1         | 0.36%   |
| Genesys Logic                          | 1         | 0.36%   |
| GEMBIRD                                | 1         | 0.36%   |
| eMeet                                  | 1         | 0.36%   |
| Cubeternet                             | 1         | 0.36%   |
| Creative Technology                    | 1         | 0.36%   |
| ALi                                    | 1         | 0.36%   |
| Unknown                                | 1         | 0.36%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                  | 9         | 3.23%   |
| Chicony HD WebCam                                              | 8         | 2.87%   |
| Realtek Integrated_Webcam_HD                                   | 7         | 2.51%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 7         | 2.51%   |
| Chicony VGA Webcam                                             | 7         | 2.51%   |
| Syntek Integrated Camera                                       | 6         | 2.15%   |
| Chicony Integrated Camera                                      | 6         | 2.15%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 6         | 2.15%   |
| Sunplus Integrated_Webcam_HD                                   | 5         | 1.79%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 5         | 1.79%   |
| Bison Integrated Camera                                        | 5         | 1.79%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                             | 5         | 1.79%   |
| Apple FaceTime HD Camera (Built-in)                            | 5         | 1.79%   |
| Microdia Integrated Webcam                                     | 4         | 1.43%   |
| Logitech Webcam C270                                           | 4         | 1.43%   |
| Lite-On Integrated Camera                                      | 4         | 1.43%   |
| IMC Networks Integrated Camera                                 | 4         | 1.43%   |
| Bison Lenovo Integrated Webcam                                 | 4         | 1.43%   |
| Quanta HP Webcam                                               | 3         | 1.08%   |
| Quanta HP TrueVision HD Camera                                 | 3         | 1.08%   |
| Lenovo Integrated Webcam                                       | 3         | 1.08%   |
| Chicony WebCam                                                 | 3         | 1.08%   |
| Chicony HP Webcam                                              | 3         | 1.08%   |
| Chicony HP TrueVision HD Camera                                | 3         | 1.08%   |
| Chicony HD User Facing                                         | 3         | 1.08%   |
| Chicony FJ Camera                                              | 3         | 1.08%   |
| Chicony CNF8243 Webcam                                         | 3         | 1.08%   |
| Apple Built-in iSight                                          | 3         | 1.08%   |
| Suyin HP TrueVision HD                                         | 2         | 0.72%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                       | 2         | 0.72%   |
| Sonix USB2.0 HD UVC WebCam                                     | 2         | 0.72%   |
| Realtek Integrated Webcam                                      | 2         | 0.72%   |
| Quanta HP Wide Vision HD Camera                                | 2         | 0.72%   |
| Microdia Integrated_Webcam_1.3M                                | 2         | 0.72%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 2         | 0.72%   |
| Logitech Webcam C310                                           | 2         | 0.72%   |
| Logitech HD Pro Webcam C920                                    | 2         | 0.72%   |
| Lite-On HP HD Webcam                                           | 2         | 0.72%   |
| Linux Foundation EEM Gadget                                    | 2         | 0.72%   |
| Importek TOSHIBA Web Camera - HD                               | 2         | 0.72%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 9         | 28.13%  |
| Synaptics                          | 5         | 15.63%  |
| Shenzhen Goodix Technology         | 5         | 15.63%  |
| Elan Microelectronics              | 4         | 12.5%   |
| LighTuning Technology              | 3         | 9.38%   |
| STMicroelectronics                 | 2         | 6.25%   |
| AuthenTec                          | 2         | 6.25%   |
| Upek                               | 1         | 3.13%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 3.13%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 9.38%   |
| Shenzhen Goodix  FingerPrint Device                                        | 3         | 9.38%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 2         | 6.25%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 6.25%   |
| LighTuning Fingerprint Reader                                              | 2         | 6.25%   |
| Elan ELAN:Fingerprint                                                      | 2         | 6.25%   |
| Elan ELAN:ARM-M4                                                           | 2         | 6.25%   |
| AuthenTec AES2810                                                          | 2         | 6.25%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 3.13%   |
| Validity Sensors VFS491                                                    | 1         | 3.13%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 3.13%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 3.13%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 3.13%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 3.13%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 3.13%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 3.13%   |
| Synaptics WBDI                                                             | 1         | 3.13%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 3.13%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 3.13%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 3.13%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 3.13%   |
| LighTuning Fingerprint Sensor                                              | 1         | 3.13%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 11        | 57.89%  |
| Upek        | 3         | 15.79%  |
| Lenovo      | 2         | 10.53%  |
| Alcor Micro | 2         | 10.53%  |
| O2 Micro    | 1         | 5.26%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 5880                                                                | 6         | 31.58%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 15.79%  |
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 15.79%  |
| Lenovo Integrated Smart Card Reader                                          | 2         | 10.53%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 10.53%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 5.26%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 5.26%   |
| Broadcom 58200                                                               | 1         | 5.26%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 458       | 82.52%  |
| 1     | 87        | 15.68%  |
| 2     | 10        | 1.8%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 32        | 30.48%  |
| Fingerprint reader       | 32        | 30.48%  |
| Chipcard                 | 18        | 17.14%  |
| Net/wireless             | 7         | 6.67%   |
| Bluetooth                | 5         | 4.76%   |
| Sound                    | 3         | 2.86%   |
| Multimedia controller    | 3         | 2.86%   |
| Unassigned class         | 1         | 0.95%   |
| Network                  | 1         | 0.95%   |
| Net/ethernet             | 1         | 0.95%   |
| Communication controller | 1         | 0.95%   |
| Camera                   | 1         | 0.95%   |

