Debian - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Debian.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 11742

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | VivoBook S13 X330FN_S330... | [50ff12c678](https://linux-hardware.org/?probe=50ff12c678) | Jan 06, 2025 |
| Lenovo        | V15-ADA 82C7                | [c5c9a457aa](https://linux-hardware.org/?probe=c5c9a457aa) | Jan 06, 2025 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [928b89625a](https://linux-hardware.org/?probe=928b89625a) | Jan 06, 2025 |
| HP            | Presario CQ57               | [970ab9cc5f](https://linux-hardware.org/?probe=970ab9cc5f) | Jan 06, 2025 |
| Positivo B... | VJFE59F11X-B1011H           | [eeea3c518d](https://linux-hardware.org/?probe=eeea3c518d) | Jan 06, 2025 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [d195e02226](https://linux-hardware.org/?probe=d195e02226) | Jan 06, 2025 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [58b338f268](https://linux-hardware.org/?probe=58b338f268) | Jan 06, 2025 |
| Lenovo        | ThinkPad E475 20H40006US    | [69908d16ca](https://linux-hardware.org/?probe=69908d16ca) | Jan 06, 2025 |
| Acer          | AOD257                      | [48ac1f7a96](https://linux-hardware.org/?probe=48ac1f7a96) | Jan 06, 2025 |
| Lenovo        | ThinkPad E475 20H40006US    | [78b9a699ff](https://linux-hardware.org/?probe=78b9a699ff) | Jan 05, 2025 |
| Lenovo        | ThinkPad T490s 20NYS60C0... | [795bfc1246](https://linux-hardware.org/?probe=795bfc1246) | Jan 05, 2025 |
| MSI           | GE60 0NC\0ND                | [423eca6c8c](https://linux-hardware.org/?probe=423eca6c8c) | Jan 05, 2025 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [a40f8a9531](https://linux-hardware.org/?probe=a40f8a9531) | Jan 05, 2025 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [8d1fc60351](https://linux-hardware.org/?probe=8d1fc60351) | Jan 05, 2025 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [8e4aafe314](https://linux-hardware.org/?probe=8e4aafe314) | Jan 05, 2025 |
| HP            | Presario CQ57               | [8c1782d787](https://linux-hardware.org/?probe=8c1782d787) | Jan 05, 2025 |
| GITSTAR       | GDC-1461                    | [08243d6a0b](https://linux-hardware.org/?probe=08243d6a0b) | Jan 05, 2025 |
| Lenovo        | ThinkPad T480 20L5S1S000    | [c35541e56b](https://linux-hardware.org/?probe=c35541e56b) | Jan 05, 2025 |
| Lenovo        | ThinkPad T14 Gen 5 21MCC... | [6e4f05f56f](https://linux-hardware.org/?probe=6e4f05f56f) | Jan 05, 2025 |
| UNOWHY        | Y13G113S4EI                 | [8d772f9e5a](https://linux-hardware.org/?probe=8d772f9e5a) | Jan 05, 2025 |
| Lenovo        | ThinkPad T460 20FMS0EP00    | [438781676d](https://linux-hardware.org/?probe=438781676d) | Jan 04, 2025 |
| TongFang      | GM5HG0A                     | [7613e29f5b](https://linux-hardware.org/?probe=7613e29f5b) | Jan 04, 2025 |
| TongFang      | GM5HG0A                     | [dd74d3e454](https://linux-hardware.org/?probe=dd74d3e454) | Jan 04, 2025 |
| Lenovo        | ThinkPad T560 20FH001RUS    | [00bb35dd31](https://linux-hardware.org/?probe=00bb35dd31) | Jan 04, 2025 |
| HP            | Pavilion Laptop 15-eh1xx... | [24988d9cd8](https://linux-hardware.org/?probe=24988d9cd8) | Jan 04, 2025 |
| Apple         | MacBookPro14,3              | [f0fd4c6916](https://linux-hardware.org/?probe=f0fd4c6916) | Jan 04, 2025 |
| Lenovo        | ThinkPad E475 20H40006US    | [1f287326ed](https://linux-hardware.org/?probe=1f287326ed) | Jan 04, 2025 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [976937be1b](https://linux-hardware.org/?probe=976937be1b) | Jan 04, 2025 |
| Apple         | MacBookPro14,3              | [bb8ec4a124](https://linux-hardware.org/?probe=bb8ec4a124) | Jan 04, 2025 |
| Lenovo        | ThinkPad E475 20H40006US    | [74d7973a3d](https://linux-hardware.org/?probe=74d7973a3d) | Jan 03, 2025 |
| Dell          | Vostro 3520                 | [77b90abaf0](https://linux-hardware.org/?probe=77b90abaf0) | Jan 03, 2025 |
| Samsung       | 940XGK                      | [71e577e3c1](https://linux-hardware.org/?probe=71e577e3c1) | Jan 03, 2025 |
| ASUSTek       | U56E                        | [e777c929c0](https://linux-hardware.org/?probe=e777c929c0) | Jan 03, 2025 |
| ASUSTek       | ASUS Vivobook S 14 M5406... | [c1bc9188a7](https://linux-hardware.org/?probe=c1bc9188a7) | Jan 03, 2025 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [5bf46c517c](https://linux-hardware.org/?probe=5bf46c517c) | Jan 03, 2025 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [763d34b165](https://linux-hardware.org/?probe=763d34b165) | Jan 03, 2025 |
| Samsung       | RC530/RC730                 | [e7b266b86e](https://linux-hardware.org/?probe=e7b266b86e) | Jan 03, 2025 |
| Acer          | Aspire 5741G                | [3785e1f57b](https://linux-hardware.org/?probe=3785e1f57b) | Jan 03, 2025 |
| Dell          | Inspiron 14 5425            | [573be124f2](https://linux-hardware.org/?probe=573be124f2) | Jan 03, 2025 |
| Google        | Dragonair                   | [69b034d6b7](https://linux-hardware.org/?probe=69b034d6b7) | Jan 03, 2025 |
| Lenovo        | Yoga Slim 7 14IMH9 83CV     | [efa06f4775](https://linux-hardware.org/?probe=efa06f4775) | Jan 03, 2025 |
| Google        | Chell                       | [165f302be9](https://linux-hardware.org/?probe=165f302be9) | Jan 03, 2025 |
| Dell          | Inspiron 5405               | [e6c57490c8](https://linux-hardware.org/?probe=e6c57490c8) | Jan 02, 2025 |
| ASUSTek       | Vivobook Go E1404FA_E140... | [d65b464077](https://linux-hardware.org/?probe=d65b464077) | Jan 02, 2025 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [d086aef8fc](https://linux-hardware.org/?probe=d086aef8fc) | Jan 02, 2025 |
| HP            | ENVY Laptop 13-ah0xxx       | [2bf35e6afa](https://linux-hardware.org/?probe=2bf35e6afa) | Jan 02, 2025 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | [419e7b4071](https://linux-hardware.org/?probe=419e7b4071) | Jan 02, 2025 |
| Dell          | Precision 5530              | [5913ba1fdc](https://linux-hardware.org/?probe=5913ba1fdc) | Jan 02, 2025 |
| Google        | Ekko                        | [865ffecf0e](https://linux-hardware.org/?probe=865ffecf0e) | Jan 02, 2025 |
| Google        | Ekko                        | [54fbbe0cfb](https://linux-hardware.org/?probe=54fbbe0cfb) | Jan 01, 2025 |
| GITSTAR       | GDC-1461                    | [e2fee21ed2](https://linux-hardware.org/?probe=e2fee21ed2) | Jan 01, 2025 |
| Dell          | XPS 9315                    | [1620c81455](https://linux-hardware.org/?probe=1620c81455) | Jan 01, 2025 |
| Dell          | Precision 5530              | [64afde2c05](https://linux-hardware.org/?probe=64afde2c05) | Jan 01, 2025 |
| HP            | Laptop 15s-du1xxx           | [5029ac1a06](https://linux-hardware.org/?probe=5029ac1a06) | Jan 01, 2025 |
| Dell          | Latitude 5480               | [d4da596a26](https://linux-hardware.org/?probe=d4da596a26) | Jan 01, 2025 |
| HP            | EliteBook 830 G5            | [8382fe388f](https://linux-hardware.org/?probe=8382fe388f) | Dec 31, 2024 |
| HP            | EliteBook 830 G5            | [a61a178741](https://linux-hardware.org/?probe=a61a178741) | Dec 31, 2024 |
| HP            | ProBook 440 G2              | [8f1c0b45da](https://linux-hardware.org/?probe=8f1c0b45da) | Dec 31, 2024 |
| HP            | ProBook 440 G2              | [98d64b84a8](https://linux-hardware.org/?probe=98d64b84a8) | Dec 31, 2024 |
| Acer          | Nitro AN515-51              | [3555e1e029](https://linux-hardware.org/?probe=3555e1e029) | Dec 31, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [994b1d92c5](https://linux-hardware.org/?probe=994b1d92c5) | Dec 30, 2024 |
| Dell          | XPS 17 9730                 | [216ff4e7eb](https://linux-hardware.org/?probe=216ff4e7eb) | Dec 30, 2024 |
| Packard Be... | EasyNote_MX45               | [e696c77b8f](https://linux-hardware.org/?probe=e696c77b8f) | Dec 30, 2024 |
| Dell          | Precision 5530              | [b9cd482095](https://linux-hardware.org/?probe=b9cd482095) | Dec 30, 2024 |
| Lenovo        | ThinkPad T430 2349TFK       | [976885ff78](https://linux-hardware.org/?probe=976885ff78) | Dec 30, 2024 |
| HP            | EliteBook 660 16 inch G1... | [97a21cd2b9](https://linux-hardware.org/?probe=97a21cd2b9) | Dec 30, 2024 |
| Apple         | MacBookPro9,2               | [3cda74dca1](https://linux-hardware.org/?probe=3cda74dca1) | Dec 29, 2024 |
| HP            | 255 G7 Notebook PC          | [c4f95fe88f](https://linux-hardware.org/?probe=c4f95fe88f) | Dec 29, 2024 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [61fe1222c2](https://linux-hardware.org/?probe=61fe1222c2) | Dec 29, 2024 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [0ce672d09f](https://linux-hardware.org/?probe=0ce672d09f) | Dec 29, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [dc70a933c3](https://linux-hardware.org/?probe=dc70a933c3) | Dec 29, 2024 |
| Packard Be... | EasyNote_MX45               | [8ef7bf6e6d](https://linux-hardware.org/?probe=8ef7bf6e6d) | Dec 29, 2024 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [4122ae81a0](https://linux-hardware.org/?probe=4122ae81a0) | Dec 29, 2024 |
| Lenovo        | LOQ 16APH8 82XU             | [1a6aebd2e4](https://linux-hardware.org/?probe=1a6aebd2e4) | Dec 29, 2024 |
| ASUSTek       | Zenbook UX3402ZA            | [be06529f29](https://linux-hardware.org/?probe=be06529f29) | Dec 28, 2024 |
| MSI           | MS-16F1                     | [9906c1fa28](https://linux-hardware.org/?probe=9906c1fa28) | Dec 28, 2024 |
| Acer          | Aspire A315-54K             | [9d416da92a](https://linux-hardware.org/?probe=9d416da92a) | Dec 28, 2024 |
| Fujitsu Si... | ESPRIMO Mobile V5555        | [e443699b8d](https://linux-hardware.org/?probe=e443699b8d) | Dec 28, 2024 |
| Lenovo        | ThinkBook 16 G6 IRL 21KH    | [caa200d745](https://linux-hardware.org/?probe=caa200d745) | Dec 28, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [2831363437](https://linux-hardware.org/?probe=2831363437) | Dec 28, 2024 |
| Alienware     | M17xR3                      | [2363abbe5c](https://linux-hardware.org/?probe=2363abbe5c) | Dec 28, 2024 |
| HP            | Compaq Mini 311-1100        | [bb10d0f283](https://linux-hardware.org/?probe=bb10d0f283) | Dec 28, 2024 |
| HP            | EliteBook Revolve 810 G3    | [e75ee3d7ac](https://linux-hardware.org/?probe=e75ee3d7ac) | Dec 28, 2024 |
| Lenovo        | ThinkPad P1 20MES1V800      | [1241156e04](https://linux-hardware.org/?probe=1241156e04) | Dec 27, 2024 |
| Dell          | Venue 11 Pro 7140           | [a91398af2a](https://linux-hardware.org/?probe=a91398af2a) | Dec 27, 2024 |
| Dell          | XPS L701X                   | [6cd016a478](https://linux-hardware.org/?probe=6cd016a478) | Dec 27, 2024 |
| HP            | 15 TouchSmart               | [dbea1582fb](https://linux-hardware.org/?probe=dbea1582fb) | Dec 27, 2024 |
| Acer          | Swift SF314-511             | [f0e61d80d6](https://linux-hardware.org/?probe=f0e61d80d6) | Dec 27, 2024 |
| Lenovo        | ThinkPad P1 20MES1V800      | [0bd80b0050](https://linux-hardware.org/?probe=0bd80b0050) | Dec 27, 2024 |
| Dell          | Precision 7520              | [ad770a5b2a](https://linux-hardware.org/?probe=ad770a5b2a) | Dec 27, 2024 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [9f0e63713d](https://linux-hardware.org/?probe=9f0e63713d) | Dec 27, 2024 |
| Lenovo        | ThinkPad T490 20N3S64400    | [86b8ea0471](https://linux-hardware.org/?probe=86b8ea0471) | Dec 27, 2024 |
| GITSTAR       | GDC-1461                    | [5d52d6cbb3](https://linux-hardware.org/?probe=5d52d6cbb3) | Dec 27, 2024 |
| Shanghai Z... | ZXE CRB                     | [b1723d54f1](https://linux-hardware.org/?probe=b1723d54f1) | Dec 27, 2024 |
| Shanghai Z... | ZXE CRB                     | [b991e63212](https://linux-hardware.org/?probe=b991e63212) | Dec 27, 2024 |
| Shanghai Z... | ZXE CRB                     | [6d28566eaf](https://linux-hardware.org/?probe=6d28566eaf) | Dec 27, 2024 |
| Shanghai Z... | ZXE CRB                     | [af6004637f](https://linux-hardware.org/?probe=af6004637f) | Dec 27, 2024 |
| GITSTAR       | GDC-1461                    | [d3d0e4ef66](https://linux-hardware.org/?probe=d3d0e4ef66) | Dec 27, 2024 |
| Morshow       | CB01 V100                   | [0f58cef0a2](https://linux-hardware.org/?probe=0f58cef0a2) | Dec 27, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [ae31e6ad1c](https://linux-hardware.org/?probe=ae31e6ad1c) | Dec 26, 2024 |
| Acer          | Aspire ES1-311              | [d4cf291b46](https://linux-hardware.org/?probe=d4cf291b46) | Dec 26, 2024 |
| ASUSTek       | G53SW                       | [89009e0426](https://linux-hardware.org/?probe=89009e0426) | Dec 26, 2024 |
| Shuttle       | NC03U                       | [7262526f1a](https://linux-hardware.org/?probe=7262526f1a) | Dec 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [4c2cba015f](https://linux-hardware.org/?probe=4c2cba015f) | Dec 26, 2024 |
| HP            | EliteBook 8460p             | [0916dd5986](https://linux-hardware.org/?probe=0916dd5986) | Dec 25, 2024 |
| Lenovo        | V15 G3 ABA 82TV             | [75b2764000](https://linux-hardware.org/?probe=75b2764000) | Dec 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [fcb6f7fe6c](https://linux-hardware.org/?probe=fcb6f7fe6c) | Dec 25, 2024 |
| Samsung       | 750XGK                      | [178e559f24](https://linux-hardware.org/?probe=178e559f24) | Dec 25, 2024 |
| HP            | ENVY m7                     | [1eae0d7a3f](https://linux-hardware.org/?probe=1eae0d7a3f) | Dec 25, 2024 |
| Unknown       | Unknown                     | [e3c37d254f](https://linux-hardware.org/?probe=e3c37d254f) | Dec 25, 2024 |
| Lenovo        | ThinkPad P53 20QQS5WG00     | [8afcf6a4e5](https://linux-hardware.org/?probe=8afcf6a4e5) | Dec 25, 2024 |
| Dell          | Latitude 7480               | [faa26e30d0](https://linux-hardware.org/?probe=faa26e30d0) | Dec 24, 2024 |
| ASUSTek       | Vivobook Go E1404FA_E140... | [b67b195148](https://linux-hardware.org/?probe=b67b195148) | Dec 24, 2024 |
| HP            | Pavilion dv6                | [db20c486f1](https://linux-hardware.org/?probe=db20c486f1) | Dec 24, 2024 |
| Schenker      | XMG Mobile A507 VE          | [883657a313](https://linux-hardware.org/?probe=883657a313) | Dec 24, 2024 |
| Dell          | XPS 13 9300                 | [496f49c231](https://linux-hardware.org/?probe=496f49c231) | Dec 24, 2024 |
| Google        | Lava                        | [8e4deea274](https://linux-hardware.org/?probe=8e4deea274) | Dec 24, 2024 |
| ASUSTek       | VivoBook S13 X330FN_S330... | [b9714a1c2f](https://linux-hardware.org/?probe=b9714a1c2f) | Dec 23, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [e871f1fdc6](https://linux-hardware.org/?probe=e871f1fdc6) | Dec 23, 2024 |
| ECT           | Unknown                     | [1bcbfee6c4](https://linux-hardware.org/?probe=1bcbfee6c4) | Dec 23, 2024 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [20dc00eb37](https://linux-hardware.org/?probe=20dc00eb37) | Dec 23, 2024 |
| Dell          | Latitude E6440              | [d5e7ca3b8f](https://linux-hardware.org/?probe=d5e7ca3b8f) | Dec 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [8690e3274f](https://linux-hardware.org/?probe=8690e3274f) | Dec 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [5a779ffa7e](https://linux-hardware.org/?probe=5a779ffa7e) | Dec 23, 2024 |
| Fujitsu Si... | ESPRIMO Mobile V5555        | [0a16cb4410](https://linux-hardware.org/?probe=0a16cb4410) | Dec 22, 2024 |
| Lenovo        | ThinkPad L390 20NR001HPG    | [30c7fd95ce](https://linux-hardware.org/?probe=30c7fd95ce) | Dec 22, 2024 |
| Lenovo        | ThinkPad T440s 20ARA000A... | [606caa4eb0](https://linux-hardware.org/?probe=606caa4eb0) | Dec 22, 2024 |
| Lenovo        | ThinkPad T440s 20ARA000A... | [813d572708](https://linux-hardware.org/?probe=813d572708) | Dec 22, 2024 |
| HP            | EliteBook 855 G7 Noteboo... | [b10a15562d](https://linux-hardware.org/?probe=b10a15562d) | Dec 22, 2024 |
| Gigabyte      | P55V5                       | [5a6d2df08d](https://linux-hardware.org/?probe=5a6d2df08d) | Dec 22, 2024 |
| Lenovo        | IdeaPad U330 Touch 20268    | [480ee6fe0c](https://linux-hardware.org/?probe=480ee6fe0c) | Dec 22, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [532c54f7ee](https://linux-hardware.org/?probe=532c54f7ee) | Dec 22, 2024 |
| Lenovo        | ThinkPad S2 Gen 6 20VMA0... | [df6fdd6e8a](https://linux-hardware.org/?probe=df6fdd6e8a) | Dec 22, 2024 |
| Dell          | Precision 3591              | [e1c2dd2dce](https://linux-hardware.org/?probe=e1c2dd2dce) | Dec 21, 2024 |
| HP            | Notebook                    | [0382c42708](https://linux-hardware.org/?probe=0382c42708) | Dec 21, 2024 |
| Dell          | Latitude 7490               | [31661d6299](https://linux-hardware.org/?probe=31661d6299) | Dec 21, 2024 |
| Lenovo        | ThinkPad S2 Gen 6 20VMA0... | [17282fe4c7](https://linux-hardware.org/?probe=17282fe4c7) | Dec 21, 2024 |
| HONOR         | BRN-GXXXA                   | [807540b5a6](https://linux-hardware.org/?probe=807540b5a6) | Dec 21, 2024 |
| HP            | EliteBook 840 G6            | [fdcfe34b78](https://linux-hardware.org/?probe=fdcfe34b78) | Dec 21, 2024 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [b458c0587b](https://linux-hardware.org/?probe=b458c0587b) | Dec 21, 2024 |
| Lenovo        | ThinkPad T490 20N3S2XL00    | [dd701f3856](https://linux-hardware.org/?probe=dd701f3856) | Dec 20, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [8145f1c8c7](https://linux-hardware.org/?probe=8145f1c8c7) | Dec 20, 2024 |
| HP            | InsydeH2O EFI BIOS          | [11d54a43ed](https://linux-hardware.org/?probe=11d54a43ed) | Dec 20, 2024 |
| Notebook      | P375SM                      | [d888f7c54b](https://linux-hardware.org/?probe=d888f7c54b) | Dec 20, 2024 |
| Dell          | Latitude 5480               | [2e3bc581e6](https://linux-hardware.org/?probe=2e3bc581e6) | Dec 19, 2024 |
| Dell          | Latitude E6410              | [b51666dd6f](https://linux-hardware.org/?probe=b51666dd6f) | Dec 19, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [ec99b76d7b](https://linux-hardware.org/?probe=ec99b76d7b) | Dec 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [35a79619d9](https://linux-hardware.org/?probe=35a79619d9) | Dec 19, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [c10492aedf](https://linux-hardware.org/?probe=c10492aedf) | Dec 19, 2024 |
| Dell          | XPS 13 9360                 | [ec5391814e](https://linux-hardware.org/?probe=ec5391814e) | Dec 19, 2024 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | [98eb4dd31b](https://linux-hardware.org/?probe=98eb4dd31b) | Dec 18, 2024 |
| Positivo      | R516256AI-15                | [9a731a05a6](https://linux-hardware.org/?probe=9a731a05a6) | Dec 18, 2024 |
| Acer          | Aspire 5560                 | [8765d80e65](https://linux-hardware.org/?probe=8765d80e65) | Dec 18, 2024 |
| Positivo      | R516256AI-15                | [19cb460e74](https://linux-hardware.org/?probe=19cb460e74) | Dec 18, 2024 |
| Dell          | Precision M4800             | [8973087d8d](https://linux-hardware.org/?probe=8973087d8d) | Dec 17, 2024 |
| Lenovo        | ThinkPad T14 Gen 5 21MCC... | [e33e8e4bbb](https://linux-hardware.org/?probe=e33e8e4bbb) | Dec 17, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [357c54b699](https://linux-hardware.org/?probe=357c54b699) | Dec 17, 2024 |
| Lenovo        | ThinkPad Z13 Gen 2 21JVC... | [9499feb64f](https://linux-hardware.org/?probe=9499feb64f) | Dec 17, 2024 |
| MSI           | Modern 15 A5M               | [9fd4e2660e](https://linux-hardware.org/?probe=9fd4e2660e) | Dec 17, 2024 |
| Acer          | Nitro AN515-51              | [3bf6da80b5](https://linux-hardware.org/?probe=3bf6da80b5) | Dec 17, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [e82cfdaf8f](https://linux-hardware.org/?probe=e82cfdaf8f) | Dec 17, 2024 |
| HP            | Notebook                    | [cd9bb8bac9](https://linux-hardware.org/?probe=cd9bb8bac9) | Dec 17, 2024 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [97f04be17e](https://linux-hardware.org/?probe=97f04be17e) | Dec 17, 2024 |
| Framework     | Laptop                      | [a1025297cf](https://linux-hardware.org/?probe=a1025297cf) | Dec 17, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [dcaa5a0395](https://linux-hardware.org/?probe=dcaa5a0395) | Dec 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [305afea5b8](https://linux-hardware.org/?probe=305afea5b8) | Dec 17, 2024 |
| ASUSTek       | K42JY                       | [35095b2b4c](https://linux-hardware.org/?probe=35095b2b4c) | Dec 16, 2024 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [f27e2a89ad](https://linux-hardware.org/?probe=f27e2a89ad) | Dec 16, 2024 |
| Dell          | Inspiron N5010              | [2642d419b6](https://linux-hardware.org/?probe=2642d419b6) | Dec 16, 2024 |
| Apple         | MacBookAir5,1               | [f5f9cdb828](https://linux-hardware.org/?probe=f5f9cdb828) | Dec 16, 2024 |
| Toshiba       | Satellite S70-B             | [384c0e568a](https://linux-hardware.org/?probe=384c0e568a) | Dec 16, 2024 |
| Apple         | MacBook6,1                  | [69c0a3cfea](https://linux-hardware.org/?probe=69c0a3cfea) | Dec 16, 2024 |
| Acer          | Swift SF314-71              | [a9466608b7](https://linux-hardware.org/?probe=a9466608b7) | Dec 15, 2024 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [d5184c7a52](https://linux-hardware.org/?probe=d5184c7a52) | Dec 15, 2024 |
| Lenovo        | ThinkPad Edge E530c 3366... | [e73050a450](https://linux-hardware.org/?probe=e73050a450) | Dec 15, 2024 |
| Acer          | Aspire 5733                 | [edc4741bd8](https://linux-hardware.org/?probe=edc4741bd8) | Dec 15, 2024 |
| Acer          | Aspire 5733                 | [b7af1c256d](https://linux-hardware.org/?probe=b7af1c256d) | Dec 15, 2024 |
| Dell          | XPS 13 9370                 | [e6d3cb85c1](https://linux-hardware.org/?probe=e6d3cb85c1) | Dec 15, 2024 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | [eb47c05bbb](https://linux-hardware.org/?probe=eb47c05bbb) | Dec 15, 2024 |
| HP            | Laptop 14-dq0xxx            | [be39b7b958](https://linux-hardware.org/?probe=be39b7b958) | Dec 15, 2024 |
| HP            | Laptop 14-dq0xxx            | [039c1af4f6](https://linux-hardware.org/?probe=039c1af4f6) | Dec 15, 2024 |
| HP            | Pavilion 17                 | [4cea084a27](https://linux-hardware.org/?probe=4cea084a27) | Dec 15, 2024 |
| Sony          | VPCYB15AG                   | [2b66b4ead4](https://linux-hardware.org/?probe=2b66b4ead4) | Dec 14, 2024 |
| Lenovo        | ThinkPad T470 20HD0001MB    | [8858dce58d](https://linux-hardware.org/?probe=8858dce58d) | Dec 14, 2024 |
| HP            | EliteBook 745 G3            | [7384d01ae6](https://linux-hardware.org/?probe=7384d01ae6) | Dec 14, 2024 |
| Dell          | Latitude E7470              | [34f407dadd](https://linux-hardware.org/?probe=34f407dadd) | Dec 13, 2024 |
| Lenovo        | ThinkBook 14 G6 ABP 21KJ    | [7b878d7d0b](https://linux-hardware.org/?probe=7b878d7d0b) | Dec 13, 2024 |
| HP            | Pavilion 17                 | [419cf21120](https://linux-hardware.org/?probe=419cf21120) | Dec 13, 2024 |
| Dell          | Inspiron 15 3520            | [c6c434f6db](https://linux-hardware.org/?probe=c6c434f6db) | Dec 13, 2024 |
| Dell          | Inspiron 15 3520            | [a9a0bade6e](https://linux-hardware.org/?probe=a9a0bade6e) | Dec 13, 2024 |
| Dell          | Inspiron 15 3520            | [157197d70c](https://linux-hardware.org/?probe=157197d70c) | Dec 13, 2024 |
| Dell          | Precision M4800             | [c5e65a893a](https://linux-hardware.org/?probe=c5e65a893a) | Dec 13, 2024 |
| HP            | 255 15.6 inch G10           | [e23abcfd28](https://linux-hardware.org/?probe=e23abcfd28) | Dec 12, 2024 |
| Lenovo        | ThinkPad T470 20HD0001MB    | [e975663b16](https://linux-hardware.org/?probe=e975663b16) | Dec 12, 2024 |
| Notebook      | W65_W67RZ1                  | [2d537d4d2f](https://linux-hardware.org/?probe=2d537d4d2f) | Dec 12, 2024 |
| Google        | Droid                       | [406e167688](https://linux-hardware.org/?probe=406e167688) | Dec 12, 2024 |
| MSI           | Katana A15 AI B8VF          | [fa1981cbf6](https://linux-hardware.org/?probe=fa1981cbf6) | Dec 11, 2024 |
| Lenovo        | ThinkPad X260 VB6R77903H    | [90c5c9954f](https://linux-hardware.org/?probe=90c5c9954f) | Dec 11, 2024 |
| Lenovo        | ThinkPad T410 2537P94       | [ef3410fac6](https://linux-hardware.org/?probe=ef3410fac6) | Dec 11, 2024 |
| Dell          | XPS 13 9350                 | [8eaebb2950](https://linux-hardware.org/?probe=8eaebb2950) | Dec 11, 2024 |
| HP            | 250 G3                      | [5ed55512ed](https://linux-hardware.org/?probe=5ed55512ed) | Dec 11, 2024 |
| TUXEDO        | InfinityBook Pro AMD Gen... | [1a2e3700f4](https://linux-hardware.org/?probe=1a2e3700f4) | Dec 11, 2024 |
| Google        | Gnawty                      | [834d30e2c7](https://linux-hardware.org/?probe=834d30e2c7) | Dec 11, 2024 |
| TUXEDO        | InfinityBook Pro AMD Gen... | [f730a13e27](https://linux-hardware.org/?probe=f730a13e27) | Dec 11, 2024 |
| Samsung       | 940XFG                      | [dc618b8f3c](https://linux-hardware.org/?probe=dc618b8f3c) | Dec 10, 2024 |
| Dell          | Latitude E6440              | [8a2677fae6](https://linux-hardware.org/?probe=8a2677fae6) | Dec 10, 2024 |
| Lenovo        | Yoga 3 14 80JH              | [c74f5d3654](https://linux-hardware.org/?probe=c74f5d3654) | Dec 10, 2024 |
| Lenovo        | ThinkPad E14 Gen 6 21M4C... | [791f38ca0c](https://linux-hardware.org/?probe=791f38ca0c) | Dec 10, 2024 |
| Lenovo        | IdeaPad 3 15IML05 81WR      | [2e6e73a4d5](https://linux-hardware.org/?probe=2e6e73a4d5) | Dec 10, 2024 |
| HP            | ProBook 640 G1              | [9a57299146](https://linux-hardware.org/?probe=9a57299146) | Dec 09, 2024 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | [80b7eef13a](https://linux-hardware.org/?probe=80b7eef13a) | Dec 09, 2024 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [c39a789b7c](https://linux-hardware.org/?probe=c39a789b7c) | Dec 09, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [f2663b158a](https://linux-hardware.org/?probe=f2663b158a) | Dec 09, 2024 |
| Intel Clie... | LAPQC71D                    | [74b3b9a1aa](https://linux-hardware.org/?probe=74b3b9a1aa) | Dec 09, 2024 |
| Lenovo        | ThinkPad T430 2349NZ4       | [67f174c3f1](https://linux-hardware.org/?probe=67f174c3f1) | Dec 09, 2024 |
| Dell          | Inspiron 5579               | [5fc44cfb4a](https://linux-hardware.org/?probe=5fc44cfb4a) | Dec 09, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [814ce2b076](https://linux-hardware.org/?probe=814ce2b076) | Dec 09, 2024 |
| HP            | Laptop 14-bp0xx             | [012068b3e1](https://linux-hardware.org/?probe=012068b3e1) | Dec 09, 2024 |
| UMAX          | VisionBook 14WRx            | [03c3fb91c0](https://linux-hardware.org/?probe=03c3fb91c0) | Dec 08, 2024 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [db6679efb6](https://linux-hardware.org/?probe=db6679efb6) | Dec 08, 2024 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | [d1af1da978](https://linux-hardware.org/?probe=d1af1da978) | Dec 08, 2024 |
| ASUSTek       | UX305FA                     | [294aae36e4](https://linux-hardware.org/?probe=294aae36e4) | Dec 08, 2024 |
| Google        | Gnawty                      | [b58d8f8569](https://linux-hardware.org/?probe=b58d8f8569) | Dec 08, 2024 |
| HP            | EliteBook 850 G4            | [eda32d0dac](https://linux-hardware.org/?probe=eda32d0dac) | Dec 08, 2024 |
| Acer          | Aspire A317-54              | [bdb1888389](https://linux-hardware.org/?probe=bdb1888389) | Dec 07, 2024 |
| HP            | Laptop 15s-fq5xxx           | [6ddbeb42be](https://linux-hardware.org/?probe=6ddbeb42be) | Dec 07, 2024 |
| Notebook      | NJx0AU                      | [013002ebef](https://linux-hardware.org/?probe=013002ebef) | Dec 07, 2024 |
| Acer          | Aspire ES1-512              | [21750c8987](https://linux-hardware.org/?probe=21750c8987) | Dec 07, 2024 |
| Lenovo        | ThinkPad T590 20N4001NUS    | [1f07a8a914](https://linux-hardware.org/?probe=1f07a8a914) | Dec 07, 2024 |
| Dell          | Latitude 5480               | [0dd91cf54a](https://linux-hardware.org/?probe=0dd91cf54a) | Dec 06, 2024 |
| HP            | 255 15.6 inch G10           | [917eafba30](https://linux-hardware.org/?probe=917eafba30) | Dec 06, 2024 |
| Acer          | Aspire V3-771               | [44298e427a](https://linux-hardware.org/?probe=44298e427a) | Dec 06, 2024 |
| Acer          | Aspire V3-771               | [75d53f2ee5](https://linux-hardware.org/?probe=75d53f2ee5) | Dec 06, 2024 |
| Acer          | Aspire 7750G                | [2cc45674a3](https://linux-hardware.org/?probe=2cc45674a3) | Dec 06, 2024 |
| Acer          | Aspire 7750G                | [aa8102d5b9](https://linux-hardware.org/?probe=aa8102d5b9) | Dec 06, 2024 |
| Dell          | Latitude 7480               | [2a52b171cb](https://linux-hardware.org/?probe=2a52b171cb) | Dec 06, 2024 |
| Positivo      | R516256AI-15                | [5e090ab777](https://linux-hardware.org/?probe=5e090ab777) | Dec 05, 2024 |
| Lenovo        | Yoga 3 14 80JH              | [b3d252047c](https://linux-hardware.org/?probe=b3d252047c) | Dec 05, 2024 |
| Lenovo        | ThinkPad P51 20HJS0AQ2S     | [2a7842f21f](https://linux-hardware.org/?probe=2a7842f21f) | Dec 05, 2024 |
| Packard Be... | EasyNote TE11HC             | [323d54f24b](https://linux-hardware.org/?probe=323d54f24b) | Dec 05, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [d1cf3d5b2b](https://linux-hardware.org/?probe=d1cf3d5b2b) | Dec 05, 2024 |
| Lenovo        | ThinkPad E475 20H40006US    | [4865b7e85e](https://linux-hardware.org/?probe=4865b7e85e) | Dec 05, 2024 |
| Lenovo        | ThinkPad T440p 20AWS0WP0... | [1b667db1d3](https://linux-hardware.org/?probe=1b667db1d3) | Dec 04, 2024 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [41f2901c17](https://linux-hardware.org/?probe=41f2901c17) | Dec 04, 2024 |
| Lenovo        | ThinkPad T440p 20AWS0WP0... | [4b2d509faa](https://linux-hardware.org/?probe=4b2d509faa) | Dec 04, 2024 |
| HP            | EliteBook 645 14 inch G1... | [4b12beb5b9](https://linux-hardware.org/?probe=4b12beb5b9) | Dec 04, 2024 |
| HP            | EliteBook 640 14 inch G1... | [8379915764](https://linux-hardware.org/?probe=8379915764) | Dec 04, 2024 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [c0d3064f9e](https://linux-hardware.org/?probe=c0d3064f9e) | Dec 04, 2024 |
| Sony          | VGN-FW51ZF_H                | [946eceac16](https://linux-hardware.org/?probe=946eceac16) | Dec 04, 2024 |
| ASUSTek       | N56VZ                       | [db563e09d2](https://linux-hardware.org/?probe=db563e09d2) | Dec 04, 2024 |
| Dell          | Latitude E7470              | [3d27c262dc](https://linux-hardware.org/?probe=3d27c262dc) | Dec 04, 2024 |
| Lenovo        | IdeaPad Slim 3 15AMN8 82... | [3635d82d65](https://linux-hardware.org/?probe=3635d82d65) | Dec 03, 2024 |
| MSI           | Modern 14 C5M               | [029d800852](https://linux-hardware.org/?probe=029d800852) | Dec 03, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [09c386afe5](https://linux-hardware.org/?probe=09c386afe5) | Dec 03, 2024 |
| HP            | EliteBook 845 14 inch G1... | [76d2be874d](https://linux-hardware.org/?probe=76d2be874d) | Dec 03, 2024 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [60c03e4401](https://linux-hardware.org/?probe=60c03e4401) | Dec 03, 2024 |
| eMachines     | E627                        | [76f066dc32](https://linux-hardware.org/?probe=76f066dc32) | Dec 03, 2024 |
| Notebook      | N13_N140ZU                  | [5a52d28de3](https://linux-hardware.org/?probe=5a52d28de3) | Dec 03, 2024 |
| Dell          | Latitude 3320               | [30a781125e](https://linux-hardware.org/?probe=30a781125e) | Dec 02, 2024 |
| Dell          | Latitude 3320               | [3319f8b2dc](https://linux-hardware.org/?probe=3319f8b2dc) | Dec 02, 2024 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [81278bd985](https://linux-hardware.org/?probe=81278bd985) | Dec 02, 2024 |
| Lenovo        | ThinkPad X230 23252EG       | [25092e7391](https://linux-hardware.org/?probe=25092e7391) | Dec 02, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [e4edce6c98](https://linux-hardware.org/?probe=e4edce6c98) | Dec 02, 2024 |
| Dell          | Inspiron 7501               | [8403bcdf72](https://linux-hardware.org/?probe=8403bcdf72) | Dec 02, 2024 |
| Dell          | Inspiron 7501               | [5c2e3ea839](https://linux-hardware.org/?probe=5c2e3ea839) | Dec 01, 2024 |
| ASUSTek       | K53SC                       | [60a52cbc6f](https://linux-hardware.org/?probe=60a52cbc6f) | Dec 01, 2024 |
| HP            | ProBook 445 14 inch G10 ... | [573df92343](https://linux-hardware.org/?probe=573df92343) | Dec 01, 2024 |
| Acer          | Aspire V3-371               | [cfe5b2b181](https://linux-hardware.org/?probe=cfe5b2b181) | Dec 01, 2024 |
| Schenker      | XMG Mobile A507 VE          | [77becf1ea3](https://linux-hardware.org/?probe=77becf1ea3) | Dec 01, 2024 |
| Clevo         | W35_37ET                    | [8c4d3d1caa](https://linux-hardware.org/?probe=8c4d3d1caa) | Nov 30, 2024 |
| Clevo         | W35_37ET                    | [4b7ce97c36](https://linux-hardware.org/?probe=4b7ce97c36) | Nov 30, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [f67fc451ae](https://linux-hardware.org/?probe=f67fc451ae) | Nov 30, 2024 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [4465a33023](https://linux-hardware.org/?probe=4465a33023) | Nov 30, 2024 |
| Unknown       | Unknown                     | [fb7e8912ab](https://linux-hardware.org/?probe=fb7e8912ab) | Nov 30, 2024 |
| MSI           | Modern 14 B11MOU            | [2a16433223](https://linux-hardware.org/?probe=2a16433223) | Nov 30, 2024 |
| TUXEDO        | Aura 15 Gen2                | [c10c58db56](https://linux-hardware.org/?probe=c10c58db56) | Nov 29, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [7b31095891](https://linux-hardware.org/?probe=7b31095891) | Nov 29, 2024 |
| Lenovo        | ThinkBook 14 G7 IML 21MR    | [301419675c](https://linux-hardware.org/?probe=301419675c) | Nov 29, 2024 |
| Google        | Volmar                      | [e5e4fff585](https://linux-hardware.org/?probe=e5e4fff585) | Nov 29, 2024 |
| Acer          | Swift SF315-41G             | [4ceee24a7a](https://linux-hardware.org/?probe=4ceee24a7a) | Nov 29, 2024 |
| Lenovo        | ThinkPad E595 20NF0000GE    | [44bc0008b2](https://linux-hardware.org/?probe=44bc0008b2) | Nov 28, 2024 |
| HP            | ProBook 645 G1              | [111e54d3ef](https://linux-hardware.org/?probe=111e54d3ef) | Nov 28, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | [0e80cc35d3](https://linux-hardware.org/?probe=0e80cc35d3) | Nov 28, 2024 |
| Acer          | Swift SF314-43              | [82fcdbb537](https://linux-hardware.org/?probe=82fcdbb537) | Nov 28, 2024 |
| Lenovo        | IdeaPad Slim 3 15ABR8 82... | [fa44240612](https://linux-hardware.org/?probe=fa44240612) | Nov 28, 2024 |
| Acer          | Aspire 3830T                | [60fd51eaff](https://linux-hardware.org/?probe=60fd51eaff) | Nov 28, 2024 |
| KVADRA        | NAU LE14U                   | [ca3a711a9a](https://linux-hardware.org/?probe=ca3a711a9a) | Nov 28, 2024 |
| ASUSTek       | Zenbook UX3402ZA            | [75d97803ac](https://linux-hardware.org/?probe=75d97803ac) | Nov 28, 2024 |
| Dell          | System XPS L702X            | [482528c7df](https://linux-hardware.org/?probe=482528c7df) | Nov 27, 2024 |
| Acer          | Swift SF315-41G             | [40cb81624b](https://linux-hardware.org/?probe=40cb81624b) | Nov 27, 2024 |
| Lenovo        | IdeaPad Slim 5 14AHP9 83... | [f2e869dbea](https://linux-hardware.org/?probe=f2e869dbea) | Nov 27, 2024 |
| Lenovo        | ThinkPad P14s Gen 5 AMD ... | [c8d5a11077](https://linux-hardware.org/?probe=c8d5a11077) | Nov 27, 2024 |
| Dell          | XPS 9320                    | [eade833b62](https://linux-hardware.org/?probe=eade833b62) | Nov 27, 2024 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [2c2ce4feac](https://linux-hardware.org/?probe=2c2ce4feac) | Nov 27, 2024 |
| Apple         | MacBookAir5,2               | [42abdaa358](https://linux-hardware.org/?probe=42abdaa358) | Nov 26, 2024 |
| Apple         | MacBookAir5,2               | [9877a9ef9d](https://linux-hardware.org/?probe=9877a9ef9d) | Nov 26, 2024 |
| Lenovo        | ThinkPad W500 4061B77       | [d1f2cd5f87](https://linux-hardware.org/?probe=d1f2cd5f87) | Nov 26, 2024 |
| Dell          | XPS 13 9360                 | [e5a87738a7](https://linux-hardware.org/?probe=e5a87738a7) | Nov 26, 2024 |
| HP            | EliteBook 840 G8 Noteboo... | [e367e88086](https://linux-hardware.org/?probe=e367e88086) | Nov 26, 2024 |
| Lenovo        | ThinkPad T450s 20BWS0H90... | [0758306c94](https://linux-hardware.org/?probe=0758306c94) | Nov 26, 2024 |
| Lenovo        | G570 20079                  | [46c212744a](https://linux-hardware.org/?probe=46c212744a) | Nov 26, 2024 |
| MSI           | Modern 14 B11MOU            | [7eb7ffe050](https://linux-hardware.org/?probe=7eb7ffe050) | Nov 26, 2024 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [45fd5080cc](https://linux-hardware.org/?probe=45fd5080cc) | Nov 26, 2024 |
| Unknown       | Unknown                     | [9e6f40d79b](https://linux-hardware.org/?probe=9e6f40d79b) | Nov 26, 2024 |
| Unknown       | Unknown                     | [e8125c2d97](https://linux-hardware.org/?probe=e8125c2d97) | Nov 26, 2024 |
| Dell          | Latitude E6520              | [47301f32db](https://linux-hardware.org/?probe=47301f32db) | Nov 26, 2024 |
| Dell          | Latitude E6520              | [ab38b0cf4c](https://linux-hardware.org/?probe=ab38b0cf4c) | Nov 26, 2024 |
| HP            | EliteBook 8560w             | [5c651293f0](https://linux-hardware.org/?probe=5c651293f0) | Nov 25, 2024 |
| Dell          | Latitude 5480               | [ccc8af5d1c](https://linux-hardware.org/?probe=ccc8af5d1c) | Nov 25, 2024 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [0fcbbf148b](https://linux-hardware.org/?probe=0fcbbf148b) | Nov 25, 2024 |
| Lenovo        | ThinkPad P53 20QQS5WG00     | [1fcd89b3c9](https://linux-hardware.org/?probe=1fcd89b3c9) | Nov 24, 2024 |
| ASUSTek       | N751JK                      | [76172e8cf6](https://linux-hardware.org/?probe=76172e8cf6) | Nov 24, 2024 |
| HP            | Laptop 15s-eq2xxx           | [d8be9ca50f](https://linux-hardware.org/?probe=d8be9ca50f) | Nov 24, 2024 |
| HP            | 255 15.6 inch G10           | [96f5e9c69f](https://linux-hardware.org/?probe=96f5e9c69f) | Nov 24, 2024 |
| Alienware     | 17 R3                       | [d6363a7652](https://linux-hardware.org/?probe=d6363a7652) | Nov 24, 2024 |
| Acer          | Aspire 3830T                | [50275fc28d](https://linux-hardware.org/?probe=50275fc28d) | Nov 24, 2024 |
| Acer          | Swift SF114-32              | [388ad0b976](https://linux-hardware.org/?probe=388ad0b976) | Nov 24, 2024 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [c235d800ea](https://linux-hardware.org/?probe=c235d800ea) | Nov 24, 2024 |
| HP            | Pavilion dv6500             | [0ce3102aaa](https://linux-hardware.org/?probe=0ce3102aaa) | Nov 24, 2024 |
| Lenovo        | ThinkPad E14 Gen 5 21JRS... | [5f86dccde5](https://linux-hardware.org/?probe=5f86dccde5) | Nov 24, 2024 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [6b4cedb8e0](https://linux-hardware.org/?probe=6b4cedb8e0) | Nov 24, 2024 |
| Lenovo        | ThinkPad X220 4290DK6       | [b3e7b7af43](https://linux-hardware.org/?probe=b3e7b7af43) | Nov 24, 2024 |
| Lenovo        | IdeaPad Slim 3 15AMN8 82... | [3736516c3b](https://linux-hardware.org/?probe=3736516c3b) | Nov 24, 2024 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [abd518a26a](https://linux-hardware.org/?probe=abd518a26a) | Nov 23, 2024 |
| Sony          | SVF1521E6EW                 | [3f90ff5914](https://linux-hardware.org/?probe=3f90ff5914) | Nov 23, 2024 |
| Sony          | SVF1521E6EW                 | [1b39708b5e](https://linux-hardware.org/?probe=1b39708b5e) | Nov 23, 2024 |
| Lenovo        | ThinkPad T14 Gen 4 21HDC... | [54831941d8](https://linux-hardware.org/?probe=54831941d8) | Nov 23, 2024 |
| Dell          | XPS 13 9360                 | [e4e708ffe9](https://linux-hardware.org/?probe=e4e708ffe9) | Nov 23, 2024 |
| Dell          | Latitude 5480               | [17715d8391](https://linux-hardware.org/?probe=17715d8391) | Nov 23, 2024 |
| Unknown       | Unknown                     | [848fad443d](https://linux-hardware.org/?probe=848fad443d) | Nov 23, 2024 |
| Unknown       | Unknown                     | [7f0bff7add](https://linux-hardware.org/?probe=7f0bff7add) | Nov 23, 2024 |
| HP            | Laptop 17-cn2xxx            | [24ac88f462](https://linux-hardware.org/?probe=24ac88f462) | Nov 23, 2024 |
| Digma         | Pro Magnus M DN16R9-ADXW... | [4084fffbdf](https://linux-hardware.org/?probe=4084fffbdf) | Nov 23, 2024 |
| HUAWEI        | KLVL-WXXW                   | [efdc073a5e](https://linux-hardware.org/?probe=efdc073a5e) | Nov 22, 2024 |
| HP            | Compaq 6820s                | [3980eb67c5](https://linux-hardware.org/?probe=3980eb67c5) | Nov 22, 2024 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [79dfcb127b](https://linux-hardware.org/?probe=79dfcb127b) | Nov 22, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | [c5a23e5058](https://linux-hardware.org/?probe=c5a23e5058) | Nov 21, 2024 |
| Lenovo        | ThinkPad Z13 Gen 2 21JVC... | [f0502de57e](https://linux-hardware.org/?probe=f0502de57e) | Nov 21, 2024 |
| Unknown       | Apple MacBook Air (M1, 2... | [a3dab07d59](https://linux-hardware.org/?probe=a3dab07d59) | Nov 21, 2024 |
| HP            | 250 G7 Notebook PC          | [6be5b2a8ec](https://linux-hardware.org/?probe=6be5b2a8ec) | Nov 21, 2024 |
| Google        | Reks                        | [14fec8c05b](https://linux-hardware.org/?probe=14fec8c05b) | Nov 21, 2024 |
| ASUSTek       | X205TA                      | [6d88dc8bcf](https://linux-hardware.org/?probe=6d88dc8bcf) | Nov 21, 2024 |
| MSI           | CX61 0NC/CX61 0ND/CX61 0... | [9a1eff8250](https://linux-hardware.org/?probe=9a1eff8250) | Nov 21, 2024 |
| Lenovo        | V15-ADA 82C7                | [16ef607aec](https://linux-hardware.org/?probe=16ef607aec) | Nov 21, 2024 |
| ASUSTek       | K55A                        | [a201300a29](https://linux-hardware.org/?probe=a201300a29) | Nov 21, 2024 |
| HP            | Laptop 15s-fq5xxx           | [f62f6ec257](https://linux-hardware.org/?probe=f62f6ec257) | Nov 21, 2024 |
| ASUSTek       | X751MD                      | [10f66dd3e4](https://linux-hardware.org/?probe=10f66dd3e4) | Nov 20, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [65b049cc4d](https://linux-hardware.org/?probe=65b049cc4d) | Nov 20, 2024 |
| Acer          | Aspire A317-54              | [63b1cd668f](https://linux-hardware.org/?probe=63b1cd668f) | Nov 20, 2024 |
| HP            | ProBook 640 G1              | [387415a6b7](https://linux-hardware.org/?probe=387415a6b7) | Nov 20, 2024 |
| Acer          | Aspire A317-54              | [31ed3fd69e](https://linux-hardware.org/?probe=31ed3fd69e) | Nov 20, 2024 |
| HONOR         | BRN-GXXXA                   | [225ca8921e](https://linux-hardware.org/?probe=225ca8921e) | Nov 20, 2024 |
| Schenker      | XMG EVO (M24)               | [6a2af97f00](https://linux-hardware.org/?probe=6a2af97f00) | Nov 20, 2024 |
| HP            | Pavilion dv7                | [bad29ac9c4](https://linux-hardware.org/?probe=bad29ac9c4) | Nov 20, 2024 |
| Schenker      | XMG EVO (M24)               | [4ad58fcdc5](https://linux-hardware.org/?probe=4ad58fcdc5) | Nov 20, 2024 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [dd120b3848](https://linux-hardware.org/?probe=dd120b3848) | Nov 20, 2024 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [a13d39cf07](https://linux-hardware.org/?probe=a13d39cf07) | Nov 20, 2024 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | [50e8894feb](https://linux-hardware.org/?probe=50e8894feb) | Nov 19, 2024 |
| HP            | 250 G1                      | [f3e587f360](https://linux-hardware.org/?probe=f3e587f360) | Nov 19, 2024 |
| Acer          | Aspire A315-44P             | [062a1972b9](https://linux-hardware.org/?probe=062a1972b9) | Nov 19, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [4546b30b47](https://linux-hardware.org/?probe=4546b30b47) | Nov 19, 2024 |
| MECHREVO      | WUJIE14XA                   | [6167ad1533](https://linux-hardware.org/?probe=6167ad1533) | Nov 19, 2024 |
| Unknown       | Unknown                     | [1e1c1f6c27](https://linux-hardware.org/?probe=1e1c1f6c27) | Nov 19, 2024 |
| HP            | 240 G8                      | [ac602e0e2e](https://linux-hardware.org/?probe=ac602e0e2e) | Nov 19, 2024 |
| Alcor Digi... | Snugbook N1431              | [404711d5c8](https://linux-hardware.org/?probe=404711d5c8) | Nov 19, 2024 |
| Lenovo        | ThinkPad E475 20H40006US    | [3d86b93c50](https://linux-hardware.org/?probe=3d86b93c50) | Nov 19, 2024 |
| Dell          | Latitude 5420               | [add3d1e8e3](https://linux-hardware.org/?probe=add3d1e8e3) | Nov 18, 2024 |
| Dell          | System Inspiron N4110       | [9337d58c59](https://linux-hardware.org/?probe=9337d58c59) | Nov 18, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [c3b63fd37e](https://linux-hardware.org/?probe=c3b63fd37e) | Nov 18, 2024 |
| Lenovo        | V15-IIL 82C5                | [21251f534d](https://linux-hardware.org/?probe=21251f534d) | Nov 18, 2024 |
| HP            | ProBook 650 G8 Notebook ... | [b127afd574](https://linux-hardware.org/?probe=b127afd574) | Nov 18, 2024 |
| ASUSTek       | X55VD                       | [fb12478a49](https://linux-hardware.org/?probe=fb12478a49) | Nov 18, 2024 |
| HP            | Notebook                    | [9ec4cde8a4](https://linux-hardware.org/?probe=9ec4cde8a4) | Nov 18, 2024 |
| HP            | Pavilion Notebook           | [e07129b7d0](https://linux-hardware.org/?probe=e07129b7d0) | Nov 18, 2024 |
| Lenovo        | ThinkPad 20NMS0C900         | [4966e097ee](https://linux-hardware.org/?probe=4966e097ee) | Nov 17, 2024 |
| Lenovo        | ThinkPad 20NMS0C900         | [f32f6badec](https://linux-hardware.org/?probe=f32f6badec) | Nov 17, 2024 |
| Lenovo        | Legion 7 16IRX9 83FD        | [d3c3b4b1a7](https://linux-hardware.org/?probe=d3c3b4b1a7) | Nov 17, 2024 |
| Lenovo        | Legion 7 16IRX9 83FD        | [840968c712](https://linux-hardware.org/?probe=840968c712) | Nov 17, 2024 |
| Dell          | Precision 5680              | [99d9b32657](https://linux-hardware.org/?probe=99d9b32657) | Nov 17, 2024 |
| MSI           | GT83 Titan 8RF              | [ec6a819838](https://linux-hardware.org/?probe=ec6a819838) | Nov 17, 2024 |
| Dell          | Precision 3591              | [801c1e1581](https://linux-hardware.org/?probe=801c1e1581) | Nov 17, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [f2c1099cb7](https://linux-hardware.org/?probe=f2c1099cb7) | Nov 17, 2024 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | [3a1c81c5c8](https://linux-hardware.org/?probe=3a1c81c5c8) | Nov 17, 2024 |
| Lenovo        | ThinkPad Edge 030255U       | [66c0e08a15](https://linux-hardware.org/?probe=66c0e08a15) | Nov 17, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [446eddf59a](https://linux-hardware.org/?probe=446eddf59a) | Nov 17, 2024 |
| HP            | EliteBook Revolve 810 G3    | [935cd6a885](https://linux-hardware.org/?probe=935cd6a885) | Nov 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [8859e2ff8e](https://linux-hardware.org/?probe=8859e2ff8e) | Nov 17, 2024 |
| Lenovo        | ThinkPad T400 6474AW6       | [eff842aac2](https://linux-hardware.org/?probe=eff842aac2) | Nov 16, 2024 |
| Dell          | Inspiron N5110              | [53e5c4a853](https://linux-hardware.org/?probe=53e5c4a853) | Nov 16, 2024 |
| Apple         | MacBookPro2,2               | [37e593aa38](https://linux-hardware.org/?probe=37e593aa38) | Nov 16, 2024 |
| Gigabyte      | P55V5                       | [e9fe9007e0](https://linux-hardware.org/?probe=e9fe9007e0) | Nov 16, 2024 |
| Gigabyte      | P55V5                       | [4ff2bec916](https://linux-hardware.org/?probe=4ff2bec916) | Nov 16, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [c55bb1e04a](https://linux-hardware.org/?probe=c55bb1e04a) | Nov 16, 2024 |
| Lenovo        | IdeaPad S540-13ITL 82H1     | [ae1583866f](https://linux-hardware.org/?probe=ae1583866f) | Nov 16, 2024 |
| HP            | ProBook 640 G1              | [74c5cd4f11](https://linux-hardware.org/?probe=74c5cd4f11) | Nov 16, 2024 |
| HP            | Notebook                    | [b7f9f0a23d](https://linux-hardware.org/?probe=b7f9f0a23d) | Nov 16, 2024 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | [ee3c65e37e](https://linux-hardware.org/?probe=ee3c65e37e) | Nov 16, 2024 |
| Lenovo        | G50-30 80G0                 | [070edd2e48](https://linux-hardware.org/?probe=070edd2e48) | Nov 16, 2024 |
| Lenovo        | ThinkPad T420 418062U       | [ebd683559d](https://linux-hardware.org/?probe=ebd683559d) | Nov 16, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [3e09dbf345](https://linux-hardware.org/?probe=3e09dbf345) | Nov 15, 2024 |
| Apple         | MacBookPro8,1               | [ec16e8a559](https://linux-hardware.org/?probe=ec16e8a559) | Nov 15, 2024 |
| Apple         | MacBookPro8,1               | [2be62b0b65](https://linux-hardware.org/?probe=2be62b0b65) | Nov 15, 2024 |
| Lenovo        | IdeaPad Gaming3 15ARH05D... | [ee4d99aac5](https://linux-hardware.org/?probe=ee4d99aac5) | Nov 15, 2024 |
| Dell          | Latitude 5580               | [23ae65a443](https://linux-hardware.org/?probe=23ae65a443) | Nov 15, 2024 |
| MSI           | U-100 Ver.001               | [24522fda07](https://linux-hardware.org/?probe=24522fda07) | Nov 15, 2024 |
| MSI           | Prestige 15 A12UC           | [b1feb7756d](https://linux-hardware.org/?probe=b1feb7756d) | Nov 15, 2024 |
| Lenovo        | ThinkPad X220 4286CTO       | [48685c2f0f](https://linux-hardware.org/?probe=48685c2f0f) | Nov 15, 2024 |
| HP            | 255 15.6 inch G10           | [9dbc6684d7](https://linux-hardware.org/?probe=9dbc6684d7) | Nov 15, 2024 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | [0db94ed770](https://linux-hardware.org/?probe=0db94ed770) | Nov 14, 2024 |
| Dell          | Latitude 7480               | [d7a47d8576](https://linux-hardware.org/?probe=d7a47d8576) | Nov 14, 2024 |
| Dell          | Precision 5690              | [d1160c82f8](https://linux-hardware.org/?probe=d1160c82f8) | Nov 14, 2024 |
| Apple         | MacBookPro11,2              | [64db2efecb](https://linux-hardware.org/?probe=64db2efecb) | Nov 14, 2024 |
| Apple         | MacBookPro2,2               | [e15a7c3ce8](https://linux-hardware.org/?probe=e15a7c3ce8) | Nov 14, 2024 |
| Valve         | Galileo                     | [87a1e5b7a3](https://linux-hardware.org/?probe=87a1e5b7a3) | Nov 14, 2024 |
| Dell          | Precision 5540              | [6db2b1cbad](https://linux-hardware.org/?probe=6db2b1cbad) | Nov 14, 2024 |
| Dell          | Latitude 7400               | [44e1fbf742](https://linux-hardware.org/?probe=44e1fbf742) | Nov 14, 2024 |
| Dell          | Latitude 7390               | [caea874a2f](https://linux-hardware.org/?probe=caea874a2f) | Nov 14, 2024 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [f0ce419267](https://linux-hardware.org/?probe=f0ce419267) | Nov 13, 2024 |
| Dell          | Latitude D630               | [e5a395e42a](https://linux-hardware.org/?probe=e5a395e42a) | Nov 13, 2024 |
| Samsung       | R710                        | [981d2ccf1d](https://linux-hardware.org/?probe=981d2ccf1d) | Nov 13, 2024 |
| Lenovo        | V330-14IKB 81B0             | [f6ebfc4fcb](https://linux-hardware.org/?probe=f6ebfc4fcb) | Nov 13, 2024 |
| Samsung       | RV410/RV510/S3510/E3510     | [dc0261731f](https://linux-hardware.org/?probe=dc0261731f) | Nov 13, 2024 |
| Sony          | SVE1513G1EB                 | [71f5a2a25f](https://linux-hardware.org/?probe=71f5a2a25f) | Nov 13, 2024 |
| Insyde        | LEBOOK IV                   | [1eb4dca9ea](https://linux-hardware.org/?probe=1eb4dca9ea) | Nov 13, 2024 |
| Lenovo        | ThinkPad P16s Gen 3 21KS... | [21e9dab6ea](https://linux-hardware.org/?probe=21e9dab6ea) | Nov 13, 2024 |
| Lenovo        | ThinkPad P16s Gen 3 21KS... | [03f6531c9e](https://linux-hardware.org/?probe=03f6531c9e) | Nov 13, 2024 |
| HP            | ProBook 640 G8 Notebook ... | [10250cdc16](https://linux-hardware.org/?probe=10250cdc16) | Nov 12, 2024 |
| Dell          | Latitude 7400               | [e0b2bc0e77](https://linux-hardware.org/?probe=e0b2bc0e77) | Nov 12, 2024 |
| Fujitsu       | LIFEBOOK A530               | [3f35643c04](https://linux-hardware.org/?probe=3f35643c04) | Nov 12, 2024 |
| Lenovo        | V17 G4 IRU 83A2             | [22aeb27e01](https://linux-hardware.org/?probe=22aeb27e01) | Nov 12, 2024 |
| Dell          | Inspiron 5447               | [bf1b6ee49f](https://linux-hardware.org/?probe=bf1b6ee49f) | Nov 12, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [d3d7f3e562](https://linux-hardware.org/?probe=d3d7f3e562) | Nov 12, 2024 |
| Lenovo        | ThinkPad X270 20HMS24F00    | [190463db3c](https://linux-hardware.org/?probe=190463db3c) | Nov 12, 2024 |
| HUAWEI        | BOM-WXX9                    | [0331c59ba2](https://linux-hardware.org/?probe=0331c59ba2) | Nov 12, 2024 |
| ASUSTek       | ZenBook S UX391UA           | [8913deb8fe](https://linux-hardware.org/?probe=8913deb8fe) | Nov 12, 2024 |
| MECHREVO      | WUJIE14XA                   | [96ed82ccbf](https://linux-hardware.org/?probe=96ed82ccbf) | Nov 12, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [59877579f0](https://linux-hardware.org/?probe=59877579f0) | Nov 12, 2024 |
| HP            | EliteBook 845 14 inch G1... | [b7086817a8](https://linux-hardware.org/?probe=b7086817a8) | Nov 12, 2024 |
| HP            | EliteBook 845 14 inch G1... | [9739937f81](https://linux-hardware.org/?probe=9739937f81) | Nov 12, 2024 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [2ba55cd21c](https://linux-hardware.org/?probe=2ba55cd21c) | Nov 12, 2024 |
| MECHREVO      | WUJIE14XA                   | [f67868b6d1](https://linux-hardware.org/?probe=f67868b6d1) | Nov 12, 2024 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [dc0dd3a948](https://linux-hardware.org/?probe=dc0dd3a948) | Nov 12, 2024 |
| Sony          | VPCEA3S1E                   | [dc4bf023a2](https://linux-hardware.org/?probe=dc4bf023a2) | Nov 11, 2024 |
| eMachines     | eME730                      | [babe1a68da](https://linux-hardware.org/?probe=babe1a68da) | Nov 11, 2024 |
| Dell          | Latitude 3320               | [6c4f16362a](https://linux-hardware.org/?probe=6c4f16362a) | Nov 11, 2024 |
| Dell          | Latitude 3320               | [e324978b3a](https://linux-hardware.org/?probe=e324978b3a) | Nov 11, 2024 |
| Dell          | Precision 5490              | [600d254cf5](https://linux-hardware.org/?probe=600d254cf5) | Nov 11, 2024 |
| Toshiba       | TECRA M9                    | [c9bf77d72b](https://linux-hardware.org/?probe=c9bf77d72b) | Nov 11, 2024 |
| Lenovo        | ThinkPad T480s 20L8S7232... | [3a310b25cc](https://linux-hardware.org/?probe=3a310b25cc) | Nov 11, 2024 |
| Lenovo        | IdeaPad Slim 3 15AMN8 82... | [24efeeab44](https://linux-hardware.org/?probe=24efeeab44) | Nov 11, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [a94e54ceca](https://linux-hardware.org/?probe=a94e54ceca) | Nov 11, 2024 |
| Sony          | SVE1713S1EW                 | [c88f369732](https://linux-hardware.org/?probe=c88f369732) | Nov 11, 2024 |
| Win elemen... | M8S                         | [3b972b3f72](https://linux-hardware.org/?probe=3b972b3f72) | Nov 11, 2024 |
| Sony          | SVE1713S1EW                 | [08cbff8480](https://linux-hardware.org/?probe=08cbff8480) | Nov 11, 2024 |
| Toshiba       | WT8-A                       | [e99f4125d4](https://linux-hardware.org/?probe=e99f4125d4) | Nov 10, 2024 |
| Lenovo        | V15 G3 IAP 82TT             | [7695a66d9d](https://linux-hardware.org/?probe=7695a66d9d) | Nov 10, 2024 |
| Dixonsxp      | Crestline & ICH8M Chipse... | [dc7ab7548b](https://linux-hardware.org/?probe=dc7ab7548b) | Nov 10, 2024 |
| Medion        | P6402 MD60800               | [53a167ff43](https://linux-hardware.org/?probe=53a167ff43) | Nov 10, 2024 |
| Dell          | XPS 15 9530                 | [5667c491cd](https://linux-hardware.org/?probe=5667c491cd) | Nov 10, 2024 |
| Lenovo        | ThinkPad E560 20EV002FUS    | [db8bceb3f0](https://linux-hardware.org/?probe=db8bceb3f0) | Nov 10, 2024 |
| Dell          | Latitude 5420               | [4bdc982517](https://linux-hardware.org/?probe=4bdc982517) | Nov 10, 2024 |
| Lenovo        | ThinkPad E560 20EV002FUS    | [cb531f1729](https://linux-hardware.org/?probe=cb531f1729) | Nov 10, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [6b7ec53237](https://linux-hardware.org/?probe=6b7ec53237) | Nov 10, 2024 |
| Dell          | Inspiron 5720               | [5c8bf7fb22](https://linux-hardware.org/?probe=5c8bf7fb22) | Nov 09, 2024 |
| HP            | EliteBook 8440p             | [1ff0179575](https://linux-hardware.org/?probe=1ff0179575) | Nov 09, 2024 |
| HP            | 250 G7 Notebook PC          | [fdac2e572a](https://linux-hardware.org/?probe=fdac2e572a) | Nov 09, 2024 |
| Lenovo        | ThinkPad X230 23243MU       | [b9aa89f4af](https://linux-hardware.org/?probe=b9aa89f4af) | Nov 09, 2024 |
| HP            | 250 G7 Notebook PC          | [0ce79c7374](https://linux-hardware.org/?probe=0ce79c7374) | Nov 08, 2024 |
| Dell          | Latitude 7450               | [88f08a3dff](https://linux-hardware.org/?probe=88f08a3dff) | Nov 08, 2024 |
| HP            | ZBook Power 15.6 inch G8... | [b31a365b52](https://linux-hardware.org/?probe=b31a365b52) | Nov 08, 2024 |
| Dell          | Inspiron 5505               | [e44d7f2f25](https://linux-hardware.org/?probe=e44d7f2f25) | Nov 08, 2024 |
| Dell          | Precision 5690              | [3e9c005bc1](https://linux-hardware.org/?probe=3e9c005bc1) | Nov 08, 2024 |
| Medion        | E15410                      | [bbbb268c4a](https://linux-hardware.org/?probe=bbbb268c4a) | Nov 07, 2024 |
| MSI           | Thin GF63 12UCX             | [20bee02e0a](https://linux-hardware.org/?probe=20bee02e0a) | Nov 07, 2024 |
| ASUSTek       | Zenbook UX3402ZA            | [362f80e77f](https://linux-hardware.org/?probe=362f80e77f) | Nov 06, 2024 |
| Lenovo        | Unknown                     | [18084edb88](https://linux-hardware.org/?probe=18084edb88) | Nov 06, 2024 |
| Google        | Reks                        | [812c11b90a](https://linux-hardware.org/?probe=812c11b90a) | Nov 06, 2024 |
| HUAWEI        | BOD-WXX9                    | [5d7f9f6298](https://linux-hardware.org/?probe=5d7f9f6298) | Nov 06, 2024 |
| Timi          | Xiaomi Book Pro 14 2022     | [cee54323a9](https://linux-hardware.org/?probe=cee54323a9) | Nov 06, 2024 |
| ASUSTek       | N56VZ                       | [b9d0972185](https://linux-hardware.org/?probe=b9d0972185) | Nov 05, 2024 |
| Dell          | Precision 5570              | [064f2e0ac6](https://linux-hardware.org/?probe=064f2e0ac6) | Nov 05, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [a3816ce6d3](https://linux-hardware.org/?probe=a3816ce6d3) | Nov 04, 2024 |
| HP            | EliteBook 8560w             | [dcd30fd3d0](https://linux-hardware.org/?probe=dcd30fd3d0) | Nov 04, 2024 |
| HP            | Pavilion Notebook           | [3ff032130b](https://linux-hardware.org/?probe=3ff032130b) | Nov 04, 2024 |
| Lenovo        | ThinkPad T490 20N3S8C701    | [b1a80e99a2](https://linux-hardware.org/?probe=b1a80e99a2) | Nov 04, 2024 |
| PC Special... | 14 Fusion IV                | [1ef6e14285](https://linux-hardware.org/?probe=1ef6e14285) | Nov 04, 2024 |
| HP            | ProBook 450 G4              | [bbe42e4f22](https://linux-hardware.org/?probe=bbe42e4f22) | Nov 04, 2024 |
| Apple         | MacBookAir6,1               | [cd233d88fd](https://linux-hardware.org/?probe=cd233d88fd) | Nov 04, 2024 |
| HP            | Pavilion dv6500             | [116231ed5e](https://linux-hardware.org/?probe=116231ed5e) | Nov 03, 2024 |
| HP            | Notebook                    | [2430b14aee](https://linux-hardware.org/?probe=2430b14aee) | Nov 03, 2024 |
| HP            | ProBook 640 G1              | [2b9ef3af3d](https://linux-hardware.org/?probe=2b9ef3af3d) | Nov 03, 2024 |
| Notebook      | NS50_70MU                   | [f2c76bba4c](https://linux-hardware.org/?probe=f2c76bba4c) | Nov 03, 2024 |
| Lenovo        | ThinkPad P51 20HH0016GE     | [c23460e039](https://linux-hardware.org/?probe=c23460e039) | Nov 03, 2024 |
| HP            | Pavilion Notebook           | [70e9b1322c](https://linux-hardware.org/?probe=70e9b1322c) | Nov 03, 2024 |
| HP            | Pavilion Laptop 15-cs3xx... | [4b20824a61](https://linux-hardware.org/?probe=4b20824a61) | Nov 02, 2024 |
| Insyde        | GeminiLake                  | [df7e9af6a4](https://linux-hardware.org/?probe=df7e9af6a4) | Nov 02, 2024 |
| Lenovo        | G570 20079                  | [5e6d8de626](https://linux-hardware.org/?probe=5e6d8de626) | Nov 02, 2024 |
| Google        | Lillipup                    | [edf52b9f3c](https://linux-hardware.org/?probe=edf52b9f3c) | Nov 01, 2024 |
| HP            | Pavilion Laptop 15-eg2xx... | [d85745f586](https://linux-hardware.org/?probe=d85745f586) | Nov 01, 2024 |
| HP            | EliteBook 2570p             | [7f904ff9f5](https://linux-hardware.org/?probe=7f904ff9f5) | Nov 01, 2024 |
| Lenovo        | ThinkPad E490 20N8000RFR    | [8ea6d50c56](https://linux-hardware.org/?probe=8ea6d50c56) | Nov 01, 2024 |
| Lenovo        | IdeaPad Y700-14ISK 80NU     | [fe49c1b15d](https://linux-hardware.org/?probe=fe49c1b15d) | Nov 01, 2024 |
| Lenovo        | IdeaPad Y700-14ISK 80NU     | [7ea533c0eb](https://linux-hardware.org/?probe=7ea533c0eb) | Nov 01, 2024 |
| Lenovo        | V145-15AST 81MT             | [6153084187](https://linux-hardware.org/?probe=6153084187) | Nov 01, 2024 |
| Dell          | XPS 15 7590                 | [597318b1e3](https://linux-hardware.org/?probe=597318b1e3) | Nov 01, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [54bedc23d6](https://linux-hardware.org/?probe=54bedc23d6) | Oct 31, 2024 |
| HP            | Pavilion Notebook           | [41cef70a32](https://linux-hardware.org/?probe=41cef70a32) | Oct 31, 2024 |
| Lenovo        | ThinkPad P53 20QQS5WG00     | [a80fc08b83](https://linux-hardware.org/?probe=a80fc08b83) | Oct 31, 2024 |
| Toshiba       | Satellite P200              | [b36b178807](https://linux-hardware.org/?probe=b36b178807) | Oct 31, 2024 |
| Dell          | Latitude E5500              | [f93b362839](https://linux-hardware.org/?probe=f93b362839) | Oct 31, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a8f6d80fe9](https://linux-hardware.org/?probe=a8f6d80fe9) | Oct 31, 2024 |
| HP            | Laptop 15s-fq5xxx           | [71ff049fdd](https://linux-hardware.org/?probe=71ff049fdd) | Oct 31, 2024 |
| HP            | EliteBook 2760p             | [fbc84b0559](https://linux-hardware.org/?probe=fbc84b0559) | Oct 31, 2024 |
| HP            | ENVY 14                     | [27e74d0815](https://linux-hardware.org/?probe=27e74d0815) | Oct 30, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | [83b6747c5a](https://linux-hardware.org/?probe=83b6747c5a) | Oct 30, 2024 |
| Dell          | Latitude 5410               | [7e4f2bc66a](https://linux-hardware.org/?probe=7e4f2bc66a) | Oct 30, 2024 |
| Dell          | Latitude 5410               | [4fdba8edb7](https://linux-hardware.org/?probe=4fdba8edb7) | Oct 30, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [3b039374f1](https://linux-hardware.org/?probe=3b039374f1) | Oct 30, 2024 |
| HP            | EliteBook 2760p             | [3482c8190d](https://linux-hardware.org/?probe=3482c8190d) | Oct 30, 2024 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | [0672cada99](https://linux-hardware.org/?probe=0672cada99) | Oct 30, 2024 |
| Dell          | Precision 5540              | [cabab07d6f](https://linux-hardware.org/?probe=cabab07d6f) | Oct 30, 2024 |
| Acer          | Nitro AN515-52              | [009c07413d](https://linux-hardware.org/?probe=009c07413d) | Oct 29, 2024 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [a2143e92d7](https://linux-hardware.org/?probe=a2143e92d7) | Oct 29, 2024 |
| Dell          | XPS 15 9510                 | [b8edc748d7](https://linux-hardware.org/?probe=b8edc748d7) | Oct 29, 2024 |
| Dell          | Latitude 7520               | [25268ed392](https://linux-hardware.org/?probe=25268ed392) | Oct 29, 2024 |
| Lenovo        | Yoga Pro 7 14APH8 82Y8      | [b6011566de](https://linux-hardware.org/?probe=b6011566de) | Oct 29, 2024 |
| HUAWEI        | KPRC-WX0                    | [3b8dd1a9b7](https://linux-hardware.org/?probe=3b8dd1a9b7) | Oct 29, 2024 |
| Dell          | Precision 3540              | [86d0b2944a](https://linux-hardware.org/?probe=86d0b2944a) | Oct 29, 2024 |
| Lenovo        | ThinkPad X220 Tablet 429... | [dca92ab806](https://linux-hardware.org/?probe=dca92ab806) | Oct 29, 2024 |
| HP            | Laptop 14-ep0xxx            | [3154b599fb](https://linux-hardware.org/?probe=3154b599fb) | Oct 28, 2024 |
| UNOWHY        | Y13G010S4EI                 | [d2bca198d0](https://linux-hardware.org/?probe=d2bca198d0) | Oct 28, 2024 |
| AMI           | Intel                       | [87b4824155](https://linux-hardware.org/?probe=87b4824155) | Oct 28, 2024 |
| Unknown       | X133                        | [4db82cec58](https://linux-hardware.org/?probe=4db82cec58) | Oct 28, 2024 |
| Unknown       | X133                        | [254e65834e](https://linux-hardware.org/?probe=254e65834e) | Oct 28, 2024 |
| Samsung       | N150P                       | [ee76fc27fa](https://linux-hardware.org/?probe=ee76fc27fa) | Oct 28, 2024 |
| Dell          | Vostro 5590                 | [0d894e3104](https://linux-hardware.org/?probe=0d894e3104) | Oct 28, 2024 |
| UNOWHY        | Y13G010S4EI                 | [1868b677e5](https://linux-hardware.org/?probe=1868b677e5) | Oct 28, 2024 |
| Dell          | XPS 13 9360                 | [4ba9fced76](https://linux-hardware.org/?probe=4ba9fced76) | Oct 28, 2024 |
| Lenovo        | IdeaPad Slim 5 14IAH8 83... | [a4c9ad2ad8](https://linux-hardware.org/?probe=a4c9ad2ad8) | Oct 27, 2024 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [9e1a54505c](https://linux-hardware.org/?probe=9e1a54505c) | Oct 27, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [73518c75af](https://linux-hardware.org/?probe=73518c75af) | Oct 27, 2024 |
| Lenovo        | ThinkPad Z16 Gen 1 21D4S... | [8d76cc4bca](https://linux-hardware.org/?probe=8d76cc4bca) | Oct 27, 2024 |
| ASUSTek       | 1011CX                      | [afd499d960](https://linux-hardware.org/?probe=afd499d960) | Oct 27, 2024 |
| HP            | Pavilion Laptop 15-cs3xx... | [c2761a98de](https://linux-hardware.org/?probe=c2761a98de) | Oct 27, 2024 |
| HP            | EliteBook 835 G8 Noteboo... | [ef44303a0a](https://linux-hardware.org/?probe=ef44303a0a) | Oct 27, 2024 |
| Dell          | Latitude 7490               | [6e6ac56fcc](https://linux-hardware.org/?probe=6e6ac56fcc) | Oct 27, 2024 |
| Lenovo        | ThinkPad T450 20AUQWER09    | [121126e862](https://linux-hardware.org/?probe=121126e862) | Oct 27, 2024 |
| Lenovo        | ThinkPad T450 20AUQWER09    | [15aea43010](https://linux-hardware.org/?probe=15aea43010) | Oct 27, 2024 |
| HP            | Compaq 6710b (GJ679LA#AB... | [09df69c2c4](https://linux-hardware.org/?probe=09df69c2c4) | Oct 27, 2024 |
| Toshiba       | Satellite L845              | [7e634d4ee6](https://linux-hardware.org/?probe=7e634d4ee6) | Oct 27, 2024 |
| HP            | EliteBook 845 G8 Noteboo... | [cb6f1609b1](https://linux-hardware.org/?probe=cb6f1609b1) | Oct 27, 2024 |
| Google        | Treeya                      | [bd2d5d31a6](https://linux-hardware.org/?probe=bd2d5d31a6) | Oct 27, 2024 |
| Acer          | Aspire A515-57              | [17d9cf69ee](https://linux-hardware.org/?probe=17d9cf69ee) | Oct 27, 2024 |
| Lenovo        | IdeaPad 3 15IML05 81WR      | [2a3b19fb54](https://linux-hardware.org/?probe=2a3b19fb54) | Oct 27, 2024 |
| Dell          | Latitude D630               | [b9cef5931a](https://linux-hardware.org/?probe=b9cef5931a) | Oct 26, 2024 |
| Dell          | Latitude D630               | [43b41071a9](https://linux-hardware.org/?probe=43b41071a9) | Oct 26, 2024 |
| HP            | ProBook 650 G8 Notebook ... | [95f5649f6f](https://linux-hardware.org/?probe=95f5649f6f) | Oct 26, 2024 |
| HP            | Stream Laptop 11-ah0XX      | [1d427542ad](https://linux-hardware.org/?probe=1d427542ad) | Oct 26, 2024 |
| Medion        | Unknown                     | [edbbb5e94d](https://linux-hardware.org/?probe=edbbb5e94d) | Oct 26, 2024 |
| HP            | EliteBook 835 G8 Noteboo... | [063b01b970](https://linux-hardware.org/?probe=063b01b970) | Oct 26, 2024 |
| ASUSTek       | A6Rp                        | [823b17b704](https://linux-hardware.org/?probe=823b17b704) | Oct 26, 2024 |
| Lenovo        | ThinkPad T480 20L6SA5Q1E    | [b36104396e](https://linux-hardware.org/?probe=b36104396e) | Oct 26, 2024 |
| ASUSTek       | N56VZ                       | [5a2ccfc817](https://linux-hardware.org/?probe=5a2ccfc817) | Oct 25, 2024 |
| HP            | EliteBook 640 14 inch G1... | [986a8ed166](https://linux-hardware.org/?probe=986a8ed166) | Oct 25, 2024 |
| Dell          | Precision 3540              | [f54b002b34](https://linux-hardware.org/?probe=f54b002b34) | Oct 25, 2024 |
| HP            | Laptop 17-bs0xx             | [6fcdd70dc4](https://linux-hardware.org/?probe=6fcdd70dc4) | Oct 25, 2024 |
| Dell          | Latitude E6430              | [e6713be055](https://linux-hardware.org/?probe=e6713be055) | Oct 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [d46929135e](https://linux-hardware.org/?probe=d46929135e) | Oct 25, 2024 |
| HP            | ProBook 445 G8 Notebook ... | [5a786be98f](https://linux-hardware.org/?probe=5a786be98f) | Oct 25, 2024 |
| Lenovo        | ThinkPad T420 4180W1A       | [be3dad4c6d](https://linux-hardware.org/?probe=be3dad4c6d) | Oct 25, 2024 |
| Sony          | VGN-NW26M                   | [b7d8f997e5](https://linux-hardware.org/?probe=b7d8f997e5) | Oct 25, 2024 |
| HP            | ZBook 15 G6                 | [bc909e1b57](https://linux-hardware.org/?probe=bc909e1b57) | Oct 25, 2024 |
| HP            | ProBook 445 G8 Notebook ... | [6ddbc76ba2](https://linux-hardware.org/?probe=6ddbc76ba2) | Oct 25, 2024 |
| Acer          | Aspire A315-44P             | [e0ef97f425](https://linux-hardware.org/?probe=e0ef97f425) | Oct 24, 2024 |
| HP            | Laptop 15-dy2xxx            | [b98436c123](https://linux-hardware.org/?probe=b98436c123) | Oct 24, 2024 |
| Dell          | Precision 7670              | [eff40613bf](https://linux-hardware.org/?probe=eff40613bf) | Oct 24, 2024 |
| Lenovo        | ThinkPad E16 Gen 2 21MA0... | [9e6cf7eb75](https://linux-hardware.org/?probe=9e6cf7eb75) | Oct 24, 2024 |
| Samsung       | R430/R480/R440              | [eeba7bd721](https://linux-hardware.org/?probe=eeba7bd721) | Oct 24, 2024 |
| Lenovo        | IdeaPad 3 15IML05 81WR      | [b94a077a9c](https://linux-hardware.org/?probe=b94a077a9c) | Oct 24, 2024 |
| Lenovo        | ThinkPad E14 Gen 6 21M70... | [14f06670e6](https://linux-hardware.org/?probe=14f06670e6) | Oct 23, 2024 |
| AMI           | Cherry Trail CR             | [8ec7b24398](https://linux-hardware.org/?probe=8ec7b24398) | Oct 23, 2024 |
| HP            | 250 G8 Notebook PC          | [338df85e2c](https://linux-hardware.org/?probe=338df85e2c) | Oct 23, 2024 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [ca0d12638d](https://linux-hardware.org/?probe=ca0d12638d) | Oct 23, 2024 |
| Dell          | Latitude 5440               | [e312fca55b](https://linux-hardware.org/?probe=e312fca55b) | Oct 23, 2024 |
| HONOR         | BRN-GXXXA                   | [c8f365af9e](https://linux-hardware.org/?probe=c8f365af9e) | Oct 23, 2024 |
| HP            | Victus by Gaming Laptop ... | [975b858e28](https://linux-hardware.org/?probe=975b858e28) | Oct 23, 2024 |
| Toshiba       | Satellite NB10-A            | [22b28cedab](https://linux-hardware.org/?probe=22b28cedab) | Oct 23, 2024 |
| HP            | Laptop 14-fq1xxx            | [3a135ae6af](https://linux-hardware.org/?probe=3a135ae6af) | Oct 23, 2024 |
| eMachines     | E725                        | [602b2cd5d8](https://linux-hardware.org/?probe=602b2cd5d8) | Oct 23, 2024 |
| Lenovo        | ThinkPad X220 Tablet 429... | [7bdbf89412](https://linux-hardware.org/?probe=7bdbf89412) | Oct 22, 2024 |
| Lenovo        | ThinkPad X61s 766929G       | [c1214c8fa7](https://linux-hardware.org/?probe=c1214c8fa7) | Oct 22, 2024 |
| Lenovo        | ThinkPad P1 Gen 6 21FWS9... | [4dad6a065d](https://linux-hardware.org/?probe=4dad6a065d) | Oct 22, 2024 |
| HP            | ProBook 4525s               | [1d0a0e4c65](https://linux-hardware.org/?probe=1d0a0e4c65) | Oct 22, 2024 |
| Lenovo        | ThinkPad T440 20B7A1BRBR    | [e6b3d99057](https://linux-hardware.org/?probe=e6b3d99057) | Oct 22, 2024 |
| Dell          | G16 7630                    | [602255e1da](https://linux-hardware.org/?probe=602255e1da) | Oct 22, 2024 |
| Lenovo        | ThinkPad T450s 20BWS0H90... | [b643d36fae](https://linux-hardware.org/?probe=b643d36fae) | Oct 22, 2024 |
| Lenovo        | ThinkPad T440 20B7A1BRBR    | [ca303af007](https://linux-hardware.org/?probe=ca303af007) | Oct 22, 2024 |
| ASUSTek       | N61Vg                       | [751bf5f70d](https://linux-hardware.org/?probe=751bf5f70d) | Oct 21, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [ba78d31b05](https://linux-hardware.org/?probe=ba78d31b05) | Oct 21, 2024 |
| Lenovo        | G460 20041                  | [6907ee1cc1](https://linux-hardware.org/?probe=6907ee1cc1) | Oct 21, 2024 |
| HP            | EliteBook 8460p             | [5bb585061d](https://linux-hardware.org/?probe=5bb585061d) | Oct 21, 2024 |
| ASUSTek       | P552SA                      | [242e7447ec](https://linux-hardware.org/?probe=242e7447ec) | Oct 21, 2024 |
| ASUSTek       | P552SA                      | [d65871e3a5](https://linux-hardware.org/?probe=d65871e3a5) | Oct 21, 2024 |
| Toshiba       | Satellite NB10-A            | [21513242cc](https://linux-hardware.org/?probe=21513242cc) | Oct 21, 2024 |
| ASUSTek       | PU301LA                     | [60b48fa00a](https://linux-hardware.org/?probe=60b48fa00a) | Oct 21, 2024 |
| Dell          | Precision 5690              | [54bd34e286](https://linux-hardware.org/?probe=54bd34e286) | Oct 21, 2024 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | [bfdf835138](https://linux-hardware.org/?probe=bfdf835138) | Oct 20, 2024 |
| Toshiba       | QOSMIO X75-A                | [90eddc4513](https://linux-hardware.org/?probe=90eddc4513) | Oct 20, 2024 |
| Toshiba       | QOSMIO X75-A                | [7bbaac259d](https://linux-hardware.org/?probe=7bbaac259d) | Oct 20, 2024 |
| Juno Compu... | junotab3                    | [bac69c0b67](https://linux-hardware.org/?probe=bac69c0b67) | Oct 20, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [1224637f0c](https://linux-hardware.org/?probe=1224637f0c) | Oct 20, 2024 |
| HP            | ProBook 440 14 inch G9 N... | [8f4ed9b69e](https://linux-hardware.org/?probe=8f4ed9b69e) | Oct 20, 2024 |
| Apple         | MacBookPro11,3              | [651628a4fc](https://linux-hardware.org/?probe=651628a4fc) | Oct 20, 2024 |
| Acer          | Aspire E5-521               | [f086192ce5](https://linux-hardware.org/?probe=f086192ce5) | Oct 20, 2024 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [62bb51fb46](https://linux-hardware.org/?probe=62bb51fb46) | Oct 19, 2024 |
| HP            | Spectre 13 Ultrabook        | [e3b33f0ba6](https://linux-hardware.org/?probe=e3b33f0ba6) | Oct 19, 2024 |
| ASUSTek       | ZenBook Pro Duo UX582ZM_... | [b5647e2bbb](https://linux-hardware.org/?probe=b5647e2bbb) | Oct 19, 2024 |
| HP            | Victus by Gaming Laptop ... | [7bb5bca5d0](https://linux-hardware.org/?probe=7bb5bca5d0) | Oct 19, 2024 |
| HP            | Pavilion g6                 | [a6a9d7daa7](https://linux-hardware.org/?probe=a6a9d7daa7) | Oct 19, 2024 |
| HP            | Pavilion g6                 | [e00c3b3199](https://linux-hardware.org/?probe=e00c3b3199) | Oct 19, 2024 |
| MSI           | Modern 14 A10M              | [90642cf1fa](https://linux-hardware.org/?probe=90642cf1fa) | Oct 19, 2024 |
| ASUSTek       | ASUS Vivobook S 14 M5406... | [209877ae34](https://linux-hardware.org/?probe=209877ae34) | Oct 19, 2024 |
| Lenovo        | ThinkPad T480s 20L8002VM... | [fee3d99904](https://linux-hardware.org/?probe=fee3d99904) | Oct 19, 2024 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [2c5dd173ae](https://linux-hardware.org/?probe=2c5dd173ae) | Oct 18, 2024 |
| Juno Compu... | junotab3                    | [e051aec192](https://linux-hardware.org/?probe=e051aec192) | Oct 18, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [d01b3d0dd1](https://linux-hardware.org/?probe=d01b3d0dd1) | Oct 18, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [4b2dfe2b19](https://linux-hardware.org/?probe=4b2dfe2b19) | Oct 18, 2024 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [7ec1a67395](https://linux-hardware.org/?probe=7ec1a67395) | Oct 18, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [c21bf61be4](https://linux-hardware.org/?probe=c21bf61be4) | Oct 18, 2024 |
| Acer          | Nitro AN515-55              | [5212832bd3](https://linux-hardware.org/?probe=5212832bd3) | Oct 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [5db9f3ef63](https://linux-hardware.org/?probe=5db9f3ef63) | Oct 17, 2024 |
| HP            | Compaq 6910p                | [2d33276514](https://linux-hardware.org/?probe=2d33276514) | Oct 17, 2024 |
| Dell          | Vostro 5568                 | [ee0b0344d6](https://linux-hardware.org/?probe=ee0b0344d6) | Oct 17, 2024 |
| Dell          | Latitude E6520              | [aff7fc0640](https://linux-hardware.org/?probe=aff7fc0640) | Oct 16, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [2dffd335d3](https://linux-hardware.org/?probe=2dffd335d3) | Oct 16, 2024 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [be67857435](https://linux-hardware.org/?probe=be67857435) | Oct 16, 2024 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [4ef504c41a](https://linux-hardware.org/?probe=4ef504c41a) | Oct 16, 2024 |
| Acer          | Aspire A515-45              | [23f0f1620b](https://linux-hardware.org/?probe=23f0f1620b) | Oct 16, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [01049738d1](https://linux-hardware.org/?probe=01049738d1) | Oct 15, 2024 |
| Apple         | MacBookAir6,1               | [afbb43d9ac](https://linux-hardware.org/?probe=afbb43d9ac) | Oct 15, 2024 |
| Dell          | Precision 3480              | [5b0959581e](https://linux-hardware.org/?probe=5b0959581e) | Oct 15, 2024 |
| ASUSTek       | ROG Strix G513RW_G513RW     | [e9c8a9f007](https://linux-hardware.org/?probe=e9c8a9f007) | Oct 15, 2024 |
| HP            | ProBook 450 G4              | [e519e7e92e](https://linux-hardware.org/?probe=e519e7e92e) | Oct 15, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | [c18d3d6e61](https://linux-hardware.org/?probe=c18d3d6e61) | Oct 15, 2024 |
| Dell          | Latitude 7280               | [6ca6f77d16](https://linux-hardware.org/?probe=6ca6f77d16) | Oct 15, 2024 |
| Dell          | Inspiron 15 3525            | [f04084f8c7](https://linux-hardware.org/?probe=f04084f8c7) | Oct 15, 2024 |
| HP            | Pavilion dv6500             | [b2277e71e1](https://linux-hardware.org/?probe=b2277e71e1) | Oct 14, 2024 |
| Dell          | Precision 5570              | [91acfd36a9](https://linux-hardware.org/?probe=91acfd36a9) | Oct 14, 2024 |
| Dell          | Precision 5570              | [59646d280c](https://linux-hardware.org/?probe=59646d280c) | Oct 14, 2024 |
| SLIMBOOK      | Unknown                     | [a45b75d9ec](https://linux-hardware.org/?probe=a45b75d9ec) | Oct 14, 2024 |
| ASUSTek       | X555LAB                     | [1c071d0507](https://linux-hardware.org/?probe=1c071d0507) | Oct 14, 2024 |
| Lenovo        | ThinkPad L390 20NRCTO1WW    | [4ba4d1d00c](https://linux-hardware.org/?probe=4ba4d1d00c) | Oct 14, 2024 |
| Lenovo        | ThinkPad T480 20L6S63U0U    | [e3e28f31f3](https://linux-hardware.org/?probe=e3e28f31f3) | Oct 14, 2024 |
| Lenovo        | LOQ 15IAX9 83GS             | [083d1aadd9](https://linux-hardware.org/?probe=083d1aadd9) | Oct 14, 2024 |
| Lenovo        | ThinkPad X390 20Q0S1FS00    | [a8debb3ea7](https://linux-hardware.org/?probe=a8debb3ea7) | Oct 14, 2024 |
| Lenovo        | LOQ 15IAX9 83GS             | [6a71048e50](https://linux-hardware.org/?probe=6a71048e50) | Oct 14, 2024 |
| AMD           | Brazos Platform             | [9dd03dc5dc](https://linux-hardware.org/?probe=9dd03dc5dc) | Oct 14, 2024 |
| ASUSTek       | ROG Strix G731GT_G731GT     | [06da3c14ff](https://linux-hardware.org/?probe=06da3c14ff) | Oct 14, 2024 |
| HP            | Laptop 17-cp3xxx            | [163ce83800](https://linux-hardware.org/?probe=163ce83800) | Oct 14, 2024 |
| Google        | Pantheon                    | [355a4514ce](https://linux-hardware.org/?probe=355a4514ce) | Oct 13, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [f773930c3a](https://linux-hardware.org/?probe=f773930c3a) | Oct 13, 2024 |
| Dell          | Latitude E6420              | [62acf0960f](https://linux-hardware.org/?probe=62acf0960f) | Oct 13, 2024 |
| Lenovo        | ThinkPad P16v Gen 1 21FC... | [7e183d610e](https://linux-hardware.org/?probe=7e183d610e) | Oct 13, 2024 |
| Insyde        | BayTrail                    | [ce5ccd96a1](https://linux-hardware.org/?probe=ce5ccd96a1) | Oct 13, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [14c88c6e79](https://linux-hardware.org/?probe=14c88c6e79) | Oct 13, 2024 |
| Chuwi         | CoreBook X                  | [1cdcd982f9](https://linux-hardware.org/?probe=1cdcd982f9) | Oct 13, 2024 |
| Lenovo        | ThinkPad T480 20L6S01Q0G    | [c30839caf4](https://linux-hardware.org/?probe=c30839caf4) | Oct 13, 2024 |
| Dell          | Latitude 7440               | [3e318704cb](https://linux-hardware.org/?probe=3e318704cb) | Oct 13, 2024 |
| Apple         | MacBookPro9,2               | [9323762ea0](https://linux-hardware.org/?probe=9323762ea0) | Oct 12, 2024 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [10e167a65f](https://linux-hardware.org/?probe=10e167a65f) | Oct 12, 2024 |
| Acer          | Aspire A315-44P             | [a6d453856a](https://linux-hardware.org/?probe=a6d453856a) | Oct 12, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [e6ff967588](https://linux-hardware.org/?probe=e6ff967588) | Oct 12, 2024 |
| HP            | OMEN by Laptop              | [9b27a597c9](https://linux-hardware.org/?probe=9b27a597c9) | Oct 12, 2024 |
| Dell          | Latitude 7490               | [5059be1beb](https://linux-hardware.org/?probe=5059be1beb) | Oct 12, 2024 |
| Dell          | Latitude 7280               | [09d4456853](https://linux-hardware.org/?probe=09d4456853) | Oct 12, 2024 |
| Dell          | Latitude 7280               | [2a735e592d](https://linux-hardware.org/?probe=2a735e592d) | Oct 12, 2024 |
| Apple         | MacBookPro9,1               | [c1c3732888](https://linux-hardware.org/?probe=c1c3732888) | Oct 12, 2024 |
| ASUSTek       | X551MA                      | [a99a06d185](https://linux-hardware.org/?probe=a99a06d185) | Oct 11, 2024 |
| Lenovo        | ThinkPad T510 4384GEG       | [eac630d431](https://linux-hardware.org/?probe=eac630d431) | Oct 11, 2024 |
| Lenovo        | ThinkPad T560 20FHCTO1WW    | [41bb4f025e](https://linux-hardware.org/?probe=41bb4f025e) | Oct 11, 2024 |
| HP            | 250 G7 Notebook PC          | [6c9c0f7683](https://linux-hardware.org/?probe=6c9c0f7683) | Oct 11, 2024 |
| HP            | 250 G7 Notebook PC          | [9d7205990c](https://linux-hardware.org/?probe=9d7205990c) | Oct 11, 2024 |
| Acer          | Aspire A515-56              | [a61df1d187](https://linux-hardware.org/?probe=a61df1d187) | Oct 11, 2024 |
| Lenovo        | Y520-15IKBN 80WK            | [dcf7dcbdc0](https://linux-hardware.org/?probe=dcf7dcbdc0) | Oct 11, 2024 |
| Acer          | Swift SF314-71              | [ff07bbbe5a](https://linux-hardware.org/?probe=ff07bbbe5a) | Oct 11, 2024 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [7476a679e5](https://linux-hardware.org/?probe=7476a679e5) | Oct 11, 2024 |
| Positivo      | A14CR6A                     | [0ec3226457](https://linux-hardware.org/?probe=0ec3226457) | Oct 11, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [8dd84b85fa](https://linux-hardware.org/?probe=8dd84b85fa) | Oct 10, 2024 |
| Dell          | Venue 8 Pro 5855            | [b436017b69](https://linux-hardware.org/?probe=b436017b69) | Oct 10, 2024 |
| Lenovo        | ThinkPad X240 20AMS22S00    | [a38f5e8565](https://linux-hardware.org/?probe=a38f5e8565) | Oct 10, 2024 |
| ASUSTek       | T100TA                      | [27cc9eff0c](https://linux-hardware.org/?probe=27cc9eff0c) | Oct 09, 2024 |
| VALE          | Notebook Evolution i5-11... | [bdc3ddf356](https://linux-hardware.org/?probe=bdc3ddf356) | Oct 09, 2024 |
| Google        | Stout                       | [35f4d5648d](https://linux-hardware.org/?probe=35f4d5648d) | Oct 09, 2024 |
| HP            | ZBook Firefly 14 inch G9... | [4fdb20cf2c](https://linux-hardware.org/?probe=4fdb20cf2c) | Oct 09, 2024 |
| Google        | Rabbid                      | [f861d7621f](https://linux-hardware.org/?probe=f861d7621f) | Oct 09, 2024 |
| Google        | Rabbid                      | [cc84f208e7](https://linux-hardware.org/?probe=cc84f208e7) | Oct 09, 2024 |
| Insyde        | BayTrail                    | [af802807b9](https://linux-hardware.org/?probe=af802807b9) | Oct 09, 2024 |
| Google        | Fleex                       | [f810d0e9a8](https://linux-hardware.org/?probe=f810d0e9a8) | Oct 08, 2024 |
| Apple         | MacBook5,2                  | [8fe95ce85d](https://linux-hardware.org/?probe=8fe95ce85d) | Oct 08, 2024 |
| Apple         | MacBook2,1                  | [53f9a6a3cf](https://linux-hardware.org/?probe=53f9a6a3cf) | Oct 08, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [4d336c2fd3](https://linux-hardware.org/?probe=4d336c2fd3) | Oct 08, 2024 |
| Dell          | Latitude 7430               | [0cc092545d](https://linux-hardware.org/?probe=0cc092545d) | Oct 08, 2024 |
| Dell          | Latitude 5530               | [7bf43022c5](https://linux-hardware.org/?probe=7bf43022c5) | Oct 08, 2024 |
| Apple         | MacBook7,1                  | [5c04542f5e](https://linux-hardware.org/?probe=5c04542f5e) | Oct 08, 2024 |
| HUAWEI        | BOD-WXX9                    | [8d6d48ae28](https://linux-hardware.org/?probe=8d6d48ae28) | Oct 08, 2024 |
| Acer          | Predator PT516-51s          | [86cb6e091c](https://linux-hardware.org/?probe=86cb6e091c) | Oct 08, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [b9166248c4](https://linux-hardware.org/?probe=b9166248c4) | Oct 08, 2024 |
| Dell          | XPS 13 9360                 | [c92ed4f5e9](https://linux-hardware.org/?probe=c92ed4f5e9) | Oct 07, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [64d275f237](https://linux-hardware.org/?probe=64d275f237) | Oct 07, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [86f0b268b4](https://linux-hardware.org/?probe=86f0b268b4) | Oct 07, 2024 |
| Polaroid      | MP1464PR001                 | [3abfe5c9f6](https://linux-hardware.org/?probe=3abfe5c9f6) | Oct 07, 2024 |
| Intel         | Calistoga & ICH7M Chipse... | [ec8d81044e](https://linux-hardware.org/?probe=ec8d81044e) | Oct 07, 2024 |
| Lenovo        | ThinkPad E450c 20EHA003C... | [05857518a1](https://linux-hardware.org/?probe=05857518a1) | Oct 07, 2024 |
| Samsung       | RC530/RC730                 | [6b0bed93f7](https://linux-hardware.org/?probe=6b0bed93f7) | Oct 07, 2024 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [87da8f0384](https://linux-hardware.org/?probe=87da8f0384) | Oct 06, 2024 |
| ASUSTek       | TUF Gaming FA506IV_TUF56... | [28d0dc2377](https://linux-hardware.org/?probe=28d0dc2377) | Oct 06, 2024 |
| Dell          | Latitude 5420               | [984b4c62dc](https://linux-hardware.org/?probe=984b4c62dc) | Oct 06, 2024 |
| Acer          | Aspire A515-57              | [eb92b3b8a2](https://linux-hardware.org/?probe=eb92b3b8a2) | Oct 06, 2024 |
| HP            | ZBook Firefly 16 inch G1... | [b630765989](https://linux-hardware.org/?probe=b630765989) | Oct 06, 2024 |
| Lenovo        | ThinkPad L15 Gen 3 21C3C... | [424ab9063e](https://linux-hardware.org/?probe=424ab9063e) | Oct 06, 2024 |
| Dell          | Vostro 5470                 | [983e045a8a](https://linux-hardware.org/?probe=983e045a8a) | Oct 06, 2024 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [ad76a5fb72](https://linux-hardware.org/?probe=ad76a5fb72) | Oct 06, 2024 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [c183bc0fcb](https://linux-hardware.org/?probe=c183bc0fcb) | Oct 05, 2024 |
| Dell          | Vostro 3520                 | [3d655882bb](https://linux-hardware.org/?probe=3d655882bb) | Oct 05, 2024 |
| Dell          | Precision 7540              | [46bfb92493](https://linux-hardware.org/?probe=46bfb92493) | Oct 05, 2024 |
| Lenovo        | G580 20150                  | [21162c92b4](https://linux-hardware.org/?probe=21162c92b4) | Oct 05, 2024 |
| HP            | Pavilion g4                 | [f4e0ac0658](https://linux-hardware.org/?probe=f4e0ac0658) | Oct 05, 2024 |
| HP            | Pavilion g4                 | [934cf2a99b](https://linux-hardware.org/?probe=934cf2a99b) | Oct 05, 2024 |
| HUAWEI        | BOHK-WAX9X                  | [e13f29974f](https://linux-hardware.org/?probe=e13f29974f) | Oct 05, 2024 |
| HP            | Laptop 17-bs0xx             | [169a158b0b](https://linux-hardware.org/?probe=169a158b0b) | Oct 05, 2024 |
| HP            | Pavilion Notebook           | [ffec3065c0](https://linux-hardware.org/?probe=ffec3065c0) | Oct 04, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAN8 82... | [fc9f9260f9](https://linux-hardware.org/?probe=fc9f9260f9) | Oct 04, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [c1d8d998c2](https://linux-hardware.org/?probe=c1d8d998c2) | Oct 04, 2024 |
| HP            | EliteBook 660 16 inch G1... | [97b155f222](https://linux-hardware.org/?probe=97b155f222) | Oct 04, 2024 |
| ASUSTek       | X551MA                      | [31d45e02da](https://linux-hardware.org/?probe=31d45e02da) | Oct 04, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [4084c5c4b5](https://linux-hardware.org/?probe=4084c5c4b5) | Oct 03, 2024 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [aef086fad5](https://linux-hardware.org/?probe=aef086fad5) | Oct 03, 2024 |
| Dell          | Latitude E6400              | [6fb4a249bd](https://linux-hardware.org/?probe=6fb4a249bd) | Oct 03, 2024 |
| Lenovo        | IdeaPad S540-15IWL D 81N... | [50fb26a910](https://linux-hardware.org/?probe=50fb26a910) | Oct 02, 2024 |
| Unknown       | Unknown                     | [2c97aeecd7](https://linux-hardware.org/?probe=2c97aeecd7) | Oct 02, 2024 |
| Apple         | MacBook5,2                  | [fbbc5b4ae5](https://linux-hardware.org/?probe=fbbc5b4ae5) | Oct 02, 2024 |
| HP            | OMEN by Laptop              | [6332ae90ac](https://linux-hardware.org/?probe=6332ae90ac) | Oct 02, 2024 |
| HP            | OMEN by Laptop              | [62c9265ff3](https://linux-hardware.org/?probe=62c9265ff3) | Oct 02, 2024 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [90b6d6089f](https://linux-hardware.org/?probe=90b6d6089f) | Oct 02, 2024 |
| HP            | EliteBook 850 G5            | [fb275667e9](https://linux-hardware.org/?probe=fb275667e9) | Oct 01, 2024 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [2a1d682889](https://linux-hardware.org/?probe=2a1d682889) | Oct 01, 2024 |
| Dell          | Latitude E7240              | [19b6586031](https://linux-hardware.org/?probe=19b6586031) | Oct 01, 2024 |
| Dell          | XPS 13 9360                 | [98867f14a8](https://linux-hardware.org/?probe=98867f14a8) | Oct 01, 2024 |
| Apple         | MacBook5,2                  | [b5ea0baf07](https://linux-hardware.org/?probe=b5ea0baf07) | Sep 30, 2024 |
| HP            | G60                         | [c4e7fe598d](https://linux-hardware.org/?probe=c4e7fe598d) | Sep 30, 2024 |
| Apple         | MacBook5,2                  | [c17d6f00ac](https://linux-hardware.org/?probe=c17d6f00ac) | Sep 30, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [03f6086944](https://linux-hardware.org/?probe=03f6086944) | Sep 30, 2024 |
| HP            | EliteBook 860 16 inch G1... | [ce12c2ab86](https://linux-hardware.org/?probe=ce12c2ab86) | Sep 30, 2024 |
| Acer          | Aspire A315-44P             | [99406631a5](https://linux-hardware.org/?probe=99406631a5) | Sep 30, 2024 |
| Acer          | Aspire 7741                 | [88aadffbb1](https://linux-hardware.org/?probe=88aadffbb1) | Sep 30, 2024 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [a4acb21d64](https://linux-hardware.org/?probe=a4acb21d64) | Sep 30, 2024 |
| Dell          | Latitude 7420               | [bdec0be003](https://linux-hardware.org/?probe=bdec0be003) | Sep 30, 2024 |
| Acer          | Aspire A515-57              | [619261162f](https://linux-hardware.org/?probe=619261162f) | Sep 29, 2024 |
| Dell          | Latitude 3420               | [d7672fb8f4](https://linux-hardware.org/?probe=d7672fb8f4) | Sep 29, 2024 |
| MSI           | Katana GF76 11UC            | [550c429265](https://linux-hardware.org/?probe=550c429265) | Sep 29, 2024 |
| Gigabyte      | P55V5                       | [de51bd9d80](https://linux-hardware.org/?probe=de51bd9d80) | Sep 29, 2024 |
| Lenovo        | ThinkPad L14 Gen 2 20X2S... | [cc04538bf0](https://linux-hardware.org/?probe=cc04538bf0) | Sep 29, 2024 |
| Unknown       | Unknown                     | [2165e3e7ca](https://linux-hardware.org/?probe=2165e3e7ca) | Sep 29, 2024 |
| Dell          | Inspiron 5437               | [75905f4f04](https://linux-hardware.org/?probe=75905f4f04) | Sep 29, 2024 |
| Lenovo        | IdeaPad Slim 5 16AHP9 83... | [c5322b9a31](https://linux-hardware.org/?probe=c5322b9a31) | Sep 29, 2024 |
| HP            | Laptop 15s-eq2xxx           | [a79dcec2fd](https://linux-hardware.org/?probe=a79dcec2fd) | Sep 29, 2024 |
| Acer          | Swift SF314-54              | [f68cbf046f](https://linux-hardware.org/?probe=f68cbf046f) | Sep 28, 2024 |
| Acer          | Swift SF314-54              | [72d85702bc](https://linux-hardware.org/?probe=72d85702bc) | Sep 28, 2024 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | [7efd1669e4](https://linux-hardware.org/?probe=7efd1669e4) | Sep 28, 2024 |
| HP            | ProBook 650 G1              | [d010c9c143](https://linux-hardware.org/?probe=d010c9c143) | Sep 28, 2024 |
| HP            | Pavilion dv6500             | [7eccfe4395](https://linux-hardware.org/?probe=7eccfe4395) | Sep 28, 2024 |
| Lenovo        | ThinkPad T560 20FHS0CJ00    | [a54fe38abb](https://linux-hardware.org/?probe=a54fe38abb) | Sep 28, 2024 |
| HP            | Pavilion dv7                | [c9109396d9](https://linux-hardware.org/?probe=c9109396d9) | Sep 28, 2024 |
| HP            | Pavilion dv7                | [37fec6e919](https://linux-hardware.org/?probe=37fec6e919) | Sep 28, 2024 |
| Positivo      | Q4128C-S                    | [d956dcf37e](https://linux-hardware.org/?probe=d956dcf37e) | Sep 28, 2024 |
| Positivo      | Q4128C-S                    | [9b234e2aa4](https://linux-hardware.org/?probe=9b234e2aa4) | Sep 28, 2024 |
| Intel         | Calistoga & ICH7M Chipse... | [e45282ff55](https://linux-hardware.org/?probe=e45282ff55) | Sep 27, 2024 |
| Insyde        | i101c                       | [7dd9fb58f1](https://linux-hardware.org/?probe=7dd9fb58f1) | Sep 27, 2024 |
| Insyde        | CherryTrail                 | [fe0ba34dbe](https://linux-hardware.org/?probe=fe0ba34dbe) | Sep 27, 2024 |
| HP            | Victus by Gaming Laptop ... | [cbcbf6fb45](https://linux-hardware.org/?probe=cbcbf6fb45) | Sep 27, 2024 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | [cdc779f468](https://linux-hardware.org/?probe=cdc779f468) | Sep 27, 2024 |
| Apple         | MacBook5,2                  | [ba2c64cf36](https://linux-hardware.org/?probe=ba2c64cf36) | Sep 27, 2024 |
| HP            | Laptop 15-fd0xxx            | [d267d17389](https://linux-hardware.org/?probe=d267d17389) | Sep 27, 2024 |
| HP            | EliteBook 845 14 inch G1... | [fbc141b7ff](https://linux-hardware.org/?probe=fbc141b7ff) | Sep 27, 2024 |
| Polaroid      | MP1464PR001                 | [10cbba3b2d](https://linux-hardware.org/?probe=10cbba3b2d) | Sep 27, 2024 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | [4961dd2254](https://linux-hardware.org/?probe=4961dd2254) | Sep 27, 2024 |
| ASUSTek       | ProArt Studiobook H7604J... | [4cd5114101](https://linux-hardware.org/?probe=4cd5114101) | Sep 26, 2024 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [a48a57eec3](https://linux-hardware.org/?probe=a48a57eec3) | Sep 26, 2024 |
| Lenovo        | ThinkPad W530 24412S6       | [1d40d13b37](https://linux-hardware.org/?probe=1d40d13b37) | Sep 26, 2024 |
| Dell          | Latitude 7430               | [7c5b40a58e](https://linux-hardware.org/?probe=7c5b40a58e) | Sep 26, 2024 |
| Lenovo        | ThinkPad E490 20N8000RFR    | [c45671a7d1](https://linux-hardware.org/?probe=c45671a7d1) | Sep 25, 2024 |
| HP            | Pavilion dv7                | [13f04d7403](https://linux-hardware.org/?probe=13f04d7403) | Sep 25, 2024 |
| Dell          | Latitude E7450              | [70bcbcd63f](https://linux-hardware.org/?probe=70bcbcd63f) | Sep 25, 2024 |
| Lenovo        | ThinkPad P15v Gen 3 21EM... | [8e78623c20](https://linux-hardware.org/?probe=8e78623c20) | Sep 25, 2024 |
| Lenovo        | Legion Slim 7 16IRH8 82Y... | [67d57f09da](https://linux-hardware.org/?probe=67d57f09da) | Sep 25, 2024 |
| Sony          | VGN-FW31J                   | [4abb461451](https://linux-hardware.org/?probe=4abb461451) | Sep 25, 2024 |
| Google        | Shyvana                     | [2c38317d9f](https://linux-hardware.org/?probe=2c38317d9f) | Sep 25, 2024 |
| Lenovo        | ThinkPad T480s 20L8S2330... | [6109441a72](https://linux-hardware.org/?probe=6109441a72) | Sep 25, 2024 |
| HP            | Victus by Laptop 16-d0xx... | [a92e602f4a](https://linux-hardware.org/?probe=a92e602f4a) | Sep 24, 2024 |
| Lenovo        | ThinkPad T14s Gen 4 21F9... | [22d916eb1f](https://linux-hardware.org/?probe=22d916eb1f) | Sep 24, 2024 |
| Dell          | Inspiron 5405               | [2bef67a454](https://linux-hardware.org/?probe=2bef67a454) | Sep 24, 2024 |
| Lenovo        | ThinkPad T480s 20L8S2330... | [2e5db39f9a](https://linux-hardware.org/?probe=2e5db39f9a) | Sep 24, 2024 |
| HP            | Pavilion Aero Laptop 13-... | [ab0a67408a](https://linux-hardware.org/?probe=ab0a67408a) | Sep 24, 2024 |
| Lenovo        | ThinkPad T480s 20L8002UM... | [fb843f4c9e](https://linux-hardware.org/?probe=fb843f4c9e) | Sep 23, 2024 |
| Dell          | Inspiron 3785               | [5626eef08a](https://linux-hardware.org/?probe=5626eef08a) | Sep 23, 2024 |
| Lenovo        | ThinkPad T440 20B7004AUS    | [f0dbfd7410](https://linux-hardware.org/?probe=f0dbfd7410) | Sep 23, 2024 |
| Acer          | Extensa 215-55              | [2d1f251fc7](https://linux-hardware.org/?probe=2d1f251fc7) | Sep 22, 2024 |
| Lenovo        | ThinkPad P14s Gen 5 AMD ... | [c8b757063d](https://linux-hardware.org/?probe=c8b757063d) | Sep 22, 2024 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [2d0b6a9144](https://linux-hardware.org/?probe=2d0b6a9144) | Sep 22, 2024 |
| Lenovo        | ThinkPad T470s 20HGS6Y80... | [cfb3db9849](https://linux-hardware.org/?probe=cfb3db9849) | Sep 22, 2024 |
| Valve         | Jupiter                     | [4e9b4fe86b](https://linux-hardware.org/?probe=4e9b4fe86b) | Sep 22, 2024 |
| Dell          | Precision 3540              | [dedc845956](https://linux-hardware.org/?probe=dedc845956) | Sep 22, 2024 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | [91c64d17ea](https://linux-hardware.org/?probe=91c64d17ea) | Sep 22, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [0d9d2bad43](https://linux-hardware.org/?probe=0d9d2bad43) | Sep 22, 2024 |
| HP            | EliteBook 840 G6            | [3051525bf1](https://linux-hardware.org/?probe=3051525bf1) | Sep 22, 2024 |
| ASUSTek       | Zenbook UM6702RC_RM6702R... | [5c9631490c](https://linux-hardware.org/?probe=5c9631490c) | Sep 22, 2024 |
| Acer          | AOA110                      | [ff0ad14af9](https://linux-hardware.org/?probe=ff0ad14af9) | Sep 22, 2024 |
| Dell          | Latitude 7290               | [7310d2504b](https://linux-hardware.org/?probe=7310d2504b) | Sep 22, 2024 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [5ebe2c925c](https://linux-hardware.org/?probe=5ebe2c925c) | Sep 21, 2024 |
| GPD           | G1621-02                    | [64bdd36dae](https://linux-hardware.org/?probe=64bdd36dae) | Sep 21, 2024 |
| Lenovo        | V15 G4 IRU 83A1             | [179751794f](https://linux-hardware.org/?probe=179751794f) | Sep 21, 2024 |
| HP            | Compaq 6510b (KE131ET#AB... | [fe08e4fc9e](https://linux-hardware.org/?probe=fe08e4fc9e) | Sep 21, 2024 |
| Lenovo        | Yoga 300-11IBY 80M0         | [566f0612c9](https://linux-hardware.org/?probe=566f0612c9) | Sep 21, 2024 |
| Gigabyte      | AORUS 15 XE4                | [0ab6f0a659](https://linux-hardware.org/?probe=0ab6f0a659) | Sep 21, 2024 |
| Dell          | Latitude 3420               | [91dbcf2851](https://linux-hardware.org/?probe=91dbcf2851) | Sep 21, 2024 |
| Intel         | Shark Bay Client platfor... | [3139ca4949](https://linux-hardware.org/?probe=3139ca4949) | Sep 21, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [e5d1a767ad](https://linux-hardware.org/?probe=e5d1a767ad) | Sep 21, 2024 |
| HP            | EliteBook 8470p             | [f71728ea0e](https://linux-hardware.org/?probe=f71728ea0e) | Sep 20, 2024 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [62e1a9a394](https://linux-hardware.org/?probe=62e1a9a394) | Sep 20, 2024 |
| Lenovo        | Unknown                     | [fb2e9dc537](https://linux-hardware.org/?probe=fb2e9dc537) | Sep 20, 2024 |
| Acer          | Aspire ES1-533              | [238267b887](https://linux-hardware.org/?probe=238267b887) | Sep 20, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [666811b8d7](https://linux-hardware.org/?probe=666811b8d7) | Sep 20, 2024 |
| ASUSTek       | 1000                        | [4ba77b632f](https://linux-hardware.org/?probe=4ba77b632f) | Sep 20, 2024 |
| Unknown       | Unknown                     | [f13d634470](https://linux-hardware.org/?probe=f13d634470) | Sep 20, 2024 |
| System76      | Lemur Pro                   | [492c20ac54](https://linux-hardware.org/?probe=492c20ac54) | Sep 20, 2024 |
| HP            | G60                         | [918e4c12c2](https://linux-hardware.org/?probe=918e4c12c2) | Sep 20, 2024 |
| ASUSTek       | K75VJ                       | [0d79ca1d3e](https://linux-hardware.org/?probe=0d79ca1d3e) | Sep 19, 2024 |
| HP            | EliteBook 840 14 inch G1... | [6ceca74333](https://linux-hardware.org/?probe=6ceca74333) | Sep 19, 2024 |
| Lenovo        | ThinkPad T480s 20L8S7232... | [17b7e775d5](https://linux-hardware.org/?probe=17b7e775d5) | Sep 19, 2024 |
| Samsung       | R540/SA41/E452              | [483174975b](https://linux-hardware.org/?probe=483174975b) | Sep 19, 2024 |
| Samsung       | R540/SA41/E452              | [12c0c1345f](https://linux-hardware.org/?probe=12c0c1345f) | Sep 19, 2024 |
| Dell          | Vostro 5402                 | [7ee496edf8](https://linux-hardware.org/?probe=7ee496edf8) | Sep 19, 2024 |
| Google        | Bobba                       | [679d38c680](https://linux-hardware.org/?probe=679d38c680) | Sep 19, 2024 |
| ASUSTek       | N61Vg                       | [456f9b3749](https://linux-hardware.org/?probe=456f9b3749) | Sep 19, 2024 |
| HP            | Laptop 14-cf1xxx            | [feaafc6a77](https://linux-hardware.org/?probe=feaafc6a77) | Sep 19, 2024 |
| HP            | Notebook                    | [38974c0ba6](https://linux-hardware.org/?probe=38974c0ba6) | Sep 18, 2024 |
| Dell          | Precision 3551              | [c201795f7c](https://linux-hardware.org/?probe=c201795f7c) | Sep 18, 2024 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | [f70500ed8e](https://linux-hardware.org/?probe=f70500ed8e) | Sep 18, 2024 |
| LG Electro... | 15Z90Q-GA76K                | [15ed518141](https://linux-hardware.org/?probe=15ed518141) | Sep 18, 2024 |
| Google        | Eldrid                      | [bc59e673eb](https://linux-hardware.org/?probe=bc59e673eb) | Sep 18, 2024 |
| HP            | ProBook 470 G4              | [283d65a8a9](https://linux-hardware.org/?probe=283d65a8a9) | Sep 18, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [9184f51a66](https://linux-hardware.org/?probe=9184f51a66) | Sep 18, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [f6b6091065](https://linux-hardware.org/?probe=f6b6091065) | Sep 18, 2024 |
| Dell          | Precision 5550              | [d90098bef5](https://linux-hardware.org/?probe=d90098bef5) | Sep 18, 2024 |
| Fujitsu       | LIFEBOOK U7510              | [70ddb226a2](https://linux-hardware.org/?probe=70ddb226a2) | Sep 18, 2024 |
| Dell          | System XPS 15Z              | [4596b76ac8](https://linux-hardware.org/?probe=4596b76ac8) | Sep 17, 2024 |
| ASUSTek       | TUF Gaming FX705DY_FX705... | [e5ab781986](https://linux-hardware.org/?probe=e5ab781986) | Sep 17, 2024 |
| HP            | Victus by Gaming Laptop ... | [1b4a966af7](https://linux-hardware.org/?probe=1b4a966af7) | Sep 16, 2024 |
| Lenovo        | V15 G2 ITL 82KB             | [f67ca87ce0](https://linux-hardware.org/?probe=f67ca87ce0) | Sep 16, 2024 |
| Dell          | Latitude 5440               | [0118c98393](https://linux-hardware.org/?probe=0118c98393) | Sep 16, 2024 |
| HP            | ProBook 440 G7              | [a65967b04a](https://linux-hardware.org/?probe=a65967b04a) | Sep 16, 2024 |
| HP            | Victus by Gaming Laptop ... | [a7987665ba](https://linux-hardware.org/?probe=a7987665ba) | Sep 16, 2024 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | [91e8f921fb](https://linux-hardware.org/?probe=91e8f921fb) | Sep 16, 2024 |
| Packard Be... | EasyNote LJ65               | [89b681de9c](https://linux-hardware.org/?probe=89b681de9c) | Sep 15, 2024 |
| Lenovo        | Legion 5 17ARH05H 82GN      | [ca053a2d24](https://linux-hardware.org/?probe=ca053a2d24) | Sep 15, 2024 |
| ASUSTek       | X550LC                      | [470155ee76](https://linux-hardware.org/?probe=470155ee76) | Sep 15, 2024 |
| Apple         | MacBook5,2                  | [87d210b0ee](https://linux-hardware.org/?probe=87d210b0ee) | Sep 15, 2024 |
| Apple         | MacBookPro5,3               | [fcb97b94c1](https://linux-hardware.org/?probe=fcb97b94c1) | Sep 14, 2024 |
| Dell          | Inspiron 3521               | [4dff294dbf](https://linux-hardware.org/?probe=4dff294dbf) | Sep 14, 2024 |
| Dell          | Inspiron 14 Plus 7430       | [554f3d4550](https://linux-hardware.org/?probe=554f3d4550) | Sep 14, 2024 |
| Dell          | Inspiron 14 Plus 7430       | [43db33b847](https://linux-hardware.org/?probe=43db33b847) | Sep 14, 2024 |
| HP            | EliteBook 840 G6            | [3e89958a33](https://linux-hardware.org/?probe=3e89958a33) | Sep 14, 2024 |
| Dell          | Vostro 5391                 | [76f0d14eba](https://linux-hardware.org/?probe=76f0d14eba) | Sep 14, 2024 |
| Google        | Lindar                      | [54bae3abd7](https://linux-hardware.org/?probe=54bae3abd7) | Sep 14, 2024 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [797d319058](https://linux-hardware.org/?probe=797d319058) | Sep 14, 2024 |
| Lenovo        | ThinkPad E450c 20EHA003C... | [221cf509e7](https://linux-hardware.org/?probe=221cf509e7) | Sep 14, 2024 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [2200373513](https://linux-hardware.org/?probe=2200373513) | Sep 14, 2024 |
| Dell          | Latitude E6540              | [1181675540](https://linux-hardware.org/?probe=1181675540) | Sep 14, 2024 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [34178a7238](https://linux-hardware.org/?probe=34178a7238) | Sep 14, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [b4aeae98a7](https://linux-hardware.org/?probe=b4aeae98a7) | Sep 14, 2024 |
| Dell          | Vostro 5391                 | [6e1469cdc7](https://linux-hardware.org/?probe=6e1469cdc7) | Sep 13, 2024 |
| Samsung       | R519/R719                   | [9fc5931563](https://linux-hardware.org/?probe=9fc5931563) | Sep 13, 2024 |
| Apple         | MacBook5,2                  | [d9bf7bf88a](https://linux-hardware.org/?probe=d9bf7bf88a) | Sep 13, 2024 |
| MSI           | Vector GP77 13VG            | [0ed7fec538](https://linux-hardware.org/?probe=0ed7fec538) | Sep 13, 2024 |
| ASUSTek       | K53SC                       | [0cf34f63c5](https://linux-hardware.org/?probe=0cf34f63c5) | Sep 13, 2024 |
| Acer          | Aspire A515-45              | [5d44025135](https://linux-hardware.org/?probe=5d44025135) | Sep 13, 2024 |
| Lenovo        | ThinkBook 16 G6 IRL 21KH    | [59d0bd0a62](https://linux-hardware.org/?probe=59d0bd0a62) | Sep 13, 2024 |
| Dell          | Latitude E7470              | [c844701a60](https://linux-hardware.org/?probe=c844701a60) | Sep 13, 2024 |
| Dell          | XPS 13 9360                 | [3272898048](https://linux-hardware.org/?probe=3272898048) | Sep 13, 2024 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | [089454045f](https://linux-hardware.org/?probe=089454045f) | Sep 12, 2024 |
| Dell          | XPS 15 9550                 | [266c779453](https://linux-hardware.org/?probe=266c779453) | Sep 12, 2024 |
| Acer          | Aspire 7740                 | [ca477b674b](https://linux-hardware.org/?probe=ca477b674b) | Sep 12, 2024 |
| Dell          | Inspiron 3521               | [e1e9fecf7c](https://linux-hardware.org/?probe=e1e9fecf7c) | Sep 12, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [c5e4efc43c](https://linux-hardware.org/?probe=c5e4efc43c) | Sep 12, 2024 |
| Lenovo        | ThinkBook 15 G5 ABP 21JF    | [9eb6ba53d9](https://linux-hardware.org/?probe=9eb6ba53d9) | Sep 12, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [eed963830f](https://linux-hardware.org/?probe=eed963830f) | Sep 12, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | [5fd39b626d](https://linux-hardware.org/?probe=5fd39b626d) | Sep 12, 2024 |
| Lenovo        | ThinkPad T460 20FMS10H00    | [81f2f6298a](https://linux-hardware.org/?probe=81f2f6298a) | Sep 12, 2024 |
| HP            | EliteBook 840 G5            | [abdf739930](https://linux-hardware.org/?probe=abdf739930) | Sep 12, 2024 |
| Lenovo        | ThinkPad T430 2347FF9       | [0e9f60231f](https://linux-hardware.org/?probe=0e9f60231f) | Sep 11, 2024 |
| Acer          | Aspire M5-481PT             | [acd68500b8](https://linux-hardware.org/?probe=acd68500b8) | Sep 11, 2024 |
| HP            | EliteBook 850 G4            | [b2ee876695](https://linux-hardware.org/?probe=b2ee876695) | Sep 11, 2024 |
| Acer          | Nitro ANV15-51              | [3496cc9987](https://linux-hardware.org/?probe=3496cc9987) | Sep 11, 2024 |
| ASUSTek       | K53SC                       | [e6267e83c6](https://linux-hardware.org/?probe=e6267e83c6) | Sep 11, 2024 |
| Dell          | Latitude 7390               | [738fbe7846](https://linux-hardware.org/?probe=738fbe7846) | Sep 11, 2024 |
| HP            | Pavilion dv6500             | [5766b47503](https://linux-hardware.org/?probe=5766b47503) | Sep 11, 2024 |
| Lenovo        | ThinkPad X240 20AMS22S00    | [d1a470a092](https://linux-hardware.org/?probe=d1a470a092) | Sep 11, 2024 |
| HP            | OMEN by Gaming Laptop 16... | [c904fcc486](https://linux-hardware.org/?probe=c904fcc486) | Sep 11, 2024 |
| MTECHE        | MTL1732J                    | [adb2356cf9](https://linux-hardware.org/?probe=adb2356cf9) | Sep 11, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [7244b83192](https://linux-hardware.org/?probe=7244b83192) | Sep 11, 2024 |
| Dell          | Latitude E6430s             | [4c5951a6ab](https://linux-hardware.org/?probe=4c5951a6ab) | Sep 11, 2024 |
| HP            | Laptop 17z-ca300            | [04d1bcbe7c](https://linux-hardware.org/?probe=04d1bcbe7c) | Sep 10, 2024 |
| Notebook      | NS5x_NS7xAU                 | [d8c7bfeb10](https://linux-hardware.org/?probe=d8c7bfeb10) | Sep 10, 2024 |
| IBM           | 26478EG                     | [a3857f6354](https://linux-hardware.org/?probe=a3857f6354) | Sep 10, 2024 |
| HP            | ZBook Fury 16 G10 Mobile... | [7c0d7e1242](https://linux-hardware.org/?probe=7c0d7e1242) | Sep 09, 2024 |
| HP            | Laptop 15s-eq2xxx           | [dc90d7b0f6](https://linux-hardware.org/?probe=dc90d7b0f6) | Sep 09, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [160a67618d](https://linux-hardware.org/?probe=160a67618d) | Sep 09, 2024 |
| Lenovo        | ThinkPad T440p 20AN0069U... | [df5f91f326](https://linux-hardware.org/?probe=df5f91f326) | Sep 09, 2024 |
| Lenovo        | ThinkPad E475 20H40006US    | [d39935d094](https://linux-hardware.org/?probe=d39935d094) | Sep 09, 2024 |
| Lenovo        | ThinkPad E475 20H40006US    | [5857717431](https://linux-hardware.org/?probe=5857717431) | Sep 09, 2024 |
| Google        | Lindar                      | [45089c96cd](https://linux-hardware.org/?probe=45089c96cd) | Sep 09, 2024 |
| Fujitsu       | LIFEBOOK U7311              | [2565533bd4](https://linux-hardware.org/?probe=2565533bd4) | Sep 09, 2024 |
| Acer          | Aspire A515-57              | [654a0c2e82](https://linux-hardware.org/?probe=654a0c2e82) | Sep 09, 2024 |
| Dell          | Vostro 5590                 | [ed8fe0784a](https://linux-hardware.org/?probe=ed8fe0784a) | Sep 08, 2024 |
| Razer         | Blade                       | [660d84cc87](https://linux-hardware.org/?probe=660d84cc87) | Sep 08, 2024 |
| Lenovo        | ThinkPad T410 253722G       | [851485830a](https://linux-hardware.org/?probe=851485830a) | Sep 08, 2024 |
| HP            | EliteBook 8760w             | [78169bfe9b](https://linux-hardware.org/?probe=78169bfe9b) | Sep 08, 2024 |
| Acer          | Aspire A317-54              | [f33771c54d](https://linux-hardware.org/?probe=f33771c54d) | Sep 08, 2024 |
| Acer          | Predator PT516-51s          | [5e00825e4e](https://linux-hardware.org/?probe=5e00825e4e) | Sep 08, 2024 |
| Acer          | Predator PT315-53           | [2d1010c782](https://linux-hardware.org/?probe=2d1010c782) | Sep 07, 2024 |
| Panasonic     | CFSV7-3                     | [7fa115f9fd](https://linux-hardware.org/?probe=7fa115f9fd) | Sep 07, 2024 |
| Apple         | MacBookPro6,2               | [d4cd8c1692](https://linux-hardware.org/?probe=d4cd8c1692) | Sep 07, 2024 |
| HP            | 15                          | [404518b1f0](https://linux-hardware.org/?probe=404518b1f0) | Sep 07, 2024 |
| Acer          | Aspire 5738                 | [7a3a65b876](https://linux-hardware.org/?probe=7a3a65b876) | Sep 07, 2024 |
| Lenovo        | ThinkPad E450c 20EHA003C... | [c3005e1e45](https://linux-hardware.org/?probe=c3005e1e45) | Sep 07, 2024 |
| HP            | Laptop 14-cf2xxx            | [061f60691b](https://linux-hardware.org/?probe=061f60691b) | Sep 07, 2024 |
| Lenovo        | ThinkPad E475 20H40006US    | [8139963bf1](https://linux-hardware.org/?probe=8139963bf1) | Sep 06, 2024 |
| Acer          | One S1002                   | [42601193da](https://linux-hardware.org/?probe=42601193da) | Sep 06, 2024 |
| Lenovo        | ThinkPad E475 20H40006US    | [dca2937fb6](https://linux-hardware.org/?probe=dca2937fb6) | Sep 06, 2024 |
| Lenovo        | ThinkPad E475 20H40006US    | [c871ccce44](https://linux-hardware.org/?probe=c871ccce44) | Sep 06, 2024 |
| Acer          | One S1002                   | [1730c8b423](https://linux-hardware.org/?probe=1730c8b423) | Sep 06, 2024 |
| ASUSTek       | VivoBook E14 E402YA_F402... | [f5b06832d9](https://linux-hardware.org/?probe=f5b06832d9) | Sep 06, 2024 |
| Dell          | System XPS L502X            | [7d1efcbe6a](https://linux-hardware.org/?probe=7d1efcbe6a) | Sep 06, 2024 |
| ASUSTek       | U36JC                       | [64f2aff020](https://linux-hardware.org/?probe=64f2aff020) | Sep 06, 2024 |
| Dell          | Latitude 3320               | [a26cf3b06d](https://linux-hardware.org/?probe=a26cf3b06d) | Sep 06, 2024 |
| Dell          | Latitude 3320               | [04212c382d](https://linux-hardware.org/?probe=04212c382d) | Sep 06, 2024 |
| Framework     | Laptop (13th Gen Intel C... | [a345eebd60](https://linux-hardware.org/?probe=a345eebd60) | Sep 06, 2024 |
| Dell          | Latitude E5470              | [4580734bcf](https://linux-hardware.org/?probe=4580734bcf) | Sep 05, 2024 |
| Acer          | Aspire A315-21G             | [b256d13f30](https://linux-hardware.org/?probe=b256d13f30) | Sep 05, 2024 |
| HP            | 15                          | [ff910fe111](https://linux-hardware.org/?probe=ff910fe111) | Sep 05, 2024 |
| HP            | 250 G8 Notebook PC          | [cc6fc2d1c3](https://linux-hardware.org/?probe=cc6fc2d1c3) | Sep 05, 2024 |
| Lenovo        | ThinkPad E450c 20EHA003C... | [5946bf2573](https://linux-hardware.org/?probe=5946bf2573) | Sep 05, 2024 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [150c9fd680](https://linux-hardware.org/?probe=150c9fd680) | Sep 05, 2024 |
| Clevo         | W760T/M740T/M760T           | [b7eb6ccaf2](https://linux-hardware.org/?probe=b7eb6ccaf2) | Sep 05, 2024 |
| HONOR         | NMH-WDX9                    | [055cbc7ddb](https://linux-hardware.org/?probe=055cbc7ddb) | Sep 04, 2024 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | [ae2092a033](https://linux-hardware.org/?probe=ae2092a033) | Sep 04, 2024 |
| ASUSTek       | UL30VT                      | [8b417dda95](https://linux-hardware.org/?probe=8b417dda95) | Sep 04, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [55e160f953](https://linux-hardware.org/?probe=55e160f953) | Sep 04, 2024 |
| HP            | EliteBook 755 G5            | [d941c3b3c9](https://linux-hardware.org/?probe=d941c3b3c9) | Sep 04, 2024 |
| Lenovo        | ThinkPad E475 20H40006US    | [4ab435eafa](https://linux-hardware.org/?probe=4ab435eafa) | Sep 04, 2024 |
| ASUSTek       | 1215N                       | [876da15409](https://linux-hardware.org/?probe=876da15409) | Sep 04, 2024 |
| Dell          | XPS 13 9360                 | [a4c61bfe8a](https://linux-hardware.org/?probe=a4c61bfe8a) | Sep 04, 2024 |
| Acer          | Aspire 5738                 | [39a33bafc0](https://linux-hardware.org/?probe=39a33bafc0) | Sep 03, 2024 |
| Lenovo        | ThinkPad E475 20H40006US    | [6bc4d69eb9](https://linux-hardware.org/?probe=6bc4d69eb9) | Sep 03, 2024 |
| Lenovo        | ThinkPad X230 2325Z7D       | [d396ee5c80](https://linux-hardware.org/?probe=d396ee5c80) | Sep 03, 2024 |
| Unknown       | Unknown                     | [5fa73d7a62](https://linux-hardware.org/?probe=5fa73d7a62) | Sep 03, 2024 |
| HP            | Pavilion dm3                | [9f6753fde0](https://linux-hardware.org/?probe=9f6753fde0) | Sep 03, 2024 |
| Lenovo        | LOQ 15IAX9 83GS             | [ae94cd873c](https://linux-hardware.org/?probe=ae94cd873c) | Sep 03, 2024 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | [1eeee26d36](https://linux-hardware.org/?probe=1eeee26d36) | Sep 03, 2024 |
| Google        | Pantheon                    | [0722a36dd5](https://linux-hardware.org/?probe=0722a36dd5) | Sep 03, 2024 |
| Clevo         | P170HMx                     | [adcf23d4b1](https://linux-hardware.org/?probe=adcf23d4b1) | Sep 03, 2024 |
| Dell          | Latitude 5290 2-in-1        | [cb9c80a2e1](https://linux-hardware.org/?probe=cb9c80a2e1) | Sep 02, 2024 |
| HP            | Compaq 510                  | [9d6336524c](https://linux-hardware.org/?probe=9d6336524c) | Sep 02, 2024 |
| Samsung       | 960XFH                      | [f6d935ecdc](https://linux-hardware.org/?probe=f6d935ecdc) | Sep 02, 2024 |
| Maibenben     | Perfectum Series            | [fb22dd8a11](https://linux-hardware.org/?probe=fb22dd8a11) | Sep 02, 2024 |
| Acer          | Extensa 215-55              | [fe50fe409e](https://linux-hardware.org/?probe=fe50fe409e) | Sep 02, 2024 |
| Positivo      | C8240AI-15                  | [cf5df4af8e](https://linux-hardware.org/?probe=cf5df4af8e) | Sep 02, 2024 |
| HP            | Notebook                    | [a269ef9f94](https://linux-hardware.org/?probe=a269ef9f94) | Sep 02, 2024 |
| Sony          | VGN-FW21M                   | [05588e0fcb](https://linux-hardware.org/?probe=05588e0fcb) | Sep 01, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M370... | [de174cd167](https://linux-hardware.org/?probe=de174cd167) | Sep 01, 2024 |
| Acer          | Predator PT315-53           | [636347c33f](https://linux-hardware.org/?probe=636347c33f) | Sep 01, 2024 |
| HP            | OMEN by Laptop 17-cb1xxx    | [89cc968d14](https://linux-hardware.org/?probe=89cc968d14) | Sep 01, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [2ee8616173](https://linux-hardware.org/?probe=2ee8616173) | Sep 01, 2024 |
| Dell          | Latitude E6420              | [2fd546015b](https://linux-hardware.org/?probe=2fd546015b) | Sep 01, 2024 |
| Dell          | Inspiron 3501               | [4764c1393a](https://linux-hardware.org/?probe=4764c1393a) | Aug 31, 2024 |
| Google        | Pantheon                    | [38b69e0944](https://linux-hardware.org/?probe=38b69e0944) | Aug 31, 2024 |
| HP            | Notebook                    | [ac2eaa0e44](https://linux-hardware.org/?probe=ac2eaa0e44) | Aug 31, 2024 |
| Acer          | Aspire A315-24PT            | [f9815d1b5b](https://linux-hardware.org/?probe=f9815d1b5b) | Aug 31, 2024 |
| Acer          | Aspire A315-41G             | [71e96b0436](https://linux-hardware.org/?probe=71e96b0436) | Aug 31, 2024 |
| HP            | Laptop 15s-fq3xxx           | [836d39ff5a](https://linux-hardware.org/?probe=836d39ff5a) | Aug 31, 2024 |
| Dell          | Latitude 5400               | [40b51b4f2a](https://linux-hardware.org/?probe=40b51b4f2a) | Aug 30, 2024 |
| Lenovo        | ThinkPad X220 4286CTO       | [c8db468f99](https://linux-hardware.org/?probe=c8db468f99) | Aug 30, 2024 |
| HP            | Laptop 15-dy2xxx            | [a81fe9ffe5](https://linux-hardware.org/?probe=a81fe9ffe5) | Aug 30, 2024 |
| HP            | Laptop 15-rb0xx             | [491800a55e](https://linux-hardware.org/?probe=491800a55e) | Aug 30, 2024 |
| HP            | Stream Notebook             | [a43fc69119](https://linux-hardware.org/?probe=a43fc69119) | Aug 30, 2024 |
| NOBLEX        | SF20BA                      | [b296b03019](https://linux-hardware.org/?probe=b296b03019) | Aug 30, 2024 |
| ECS           | MB45II7                     | [6f49af5e02](https://linux-hardware.org/?probe=6f49af5e02) | Aug 30, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [ef1ecc15b9](https://linux-hardware.org/?probe=ef1ecc15b9) | Aug 30, 2024 |
| Google        | Delbin                      | [867ab5e440](https://linux-hardware.org/?probe=867ab5e440) | Aug 29, 2024 |
| ASUSTek       | Vivobook Go E1404GAB_E14... | [5a3dac80c0](https://linux-hardware.org/?probe=5a3dac80c0) | Aug 29, 2024 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [b50d13ed69](https://linux-hardware.org/?probe=b50d13ed69) | Aug 29, 2024 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Debian 11                       | 3539      | 41.7%   |
| Debian 12                       | 2882      | 33.96%  |
| Debian 10                       | 867       | 10.22%  |
| Debian                          | 477       | 5.62%   |
| Debian Testing                  | 357       | 4.21%   |
| Debian 9                        | 147       | 1.73%   |
| Debian Unstable                 | 128       | 1.51%   |
| Debian 11-updates               | 27        | 0.32%   |
| Debian Testing/unstable         | 25        | 0.29%   |
| Debian 8                        | 11        | 0.13%   |
| Debian 23                       | 10        | 0.12%   |
| Debian Sid                      | 5         | 0.06%   |
| Debian 22                       | 3         | 0.04%   |
| Debian 6                        | 2         | 0.02%   |
| Debian Testing-proposed-updates | 1         | 0.01%   |
| Debian N/a                      | 1         | 0.01%   |
| Debian 99                       | 1         | 0.01%   |
| Debian 24                       | 1         | 0.01%   |
| Debian 2024                     | 1         | 0.01%   |
| Debian 12-updates               | 1         | 0.01%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Debian | 8079      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version         | Notebooks | Percent |
|-----------------|-----------|---------|
| 5.10.0-8-amd64  | 586       | 6.23%   |
| 5.10.0-10-amd64 | 492       | 5.23%   |
| 6.1.0-13-amd64  | 318       | 3.38%   |
| 6.1.0-18-amd64  | 309       | 3.28%   |
| 5.10.0-20-amd64 | 250       | 2.66%   |
| 5.10.0-21-amd64 | 238       | 2.53%   |
| 6.1.0-10-amd64  | 181       | 1.92%   |
| 5.10.0-18-amd64 | 181       | 1.92%   |
| 6.1.0-21-amd64  | 179       | 1.9%    |
| 6.1.0-9-amd64   | 176       | 1.87%   |
| 6.1.0-23-amd64  | 176       | 1.87%   |
| 5.10.0-9-amd64  | 174       | 1.85%   |
| 5.10.0-7-amd64  | 171       | 1.82%   |
| 5.10.0-16-amd64 | 168       | 1.79%   |
| 6.1.0-17-amd64  | 164       | 1.74%   |
| 5.10.0-19-amd64 | 162       | 1.72%   |
| 5.10.0-13-amd64 | 151       | 1.6%    |
| 6.1.0-25-amd64  | 144       | 1.53%   |
| 6.1.0-26-amd64  | 125       | 1.33%   |
| 6.1.0-12-amd64  | 125       | 1.33%   |
| 6.1.0-28-amd64  | 117       | 1.24%   |
| 5.10.0-23-amd64 | 113       | 1.2%    |
| 6.1.0-22-amd64  | 110       | 1.17%   |
| 6.1.0-11-amd64  | 109       | 1.16%   |
| 5.10.0-11-amd64 | 104       | 1.11%   |
| 6.1.0-16-amd64  | 91        | 0.97%   |
| 6.1.0-27-amd64  | 87        | 0.92%   |
| 4.19.0-9-amd64  | 85        | 0.9%    |
| 4.19.0-6-amd64  | 82        | 0.87%   |
| 5.10.0-14-amd64 | 80        | 0.85%   |
| 6.1.0-4-amd64   | 74        | 0.79%   |
| 5.10.0-17-amd64 | 73        | 0.78%   |
| 6.1.0-20-amd64  | 71        | 0.75%   |
| 4.19.0-13-amd64 | 69        | 0.73%   |
| 4.19.0-8-amd64  | 68        | 0.72%   |
| 5.10.0-15-amd64 | 62        | 0.66%   |
| 6.1.0-15-amd64  | 56        | 0.6%    |
| 6.1.0-7-amd64   | 53        | 0.56%   |
| 4.19.0-16-amd64 | 53        | 0.56%   |
| 4.19.0-10-amd64 | 52        | 0.55%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 3303      | 37.71%  |
| 6.1.0   | 2644      | 30.18%  |
| 4.19.0  | 662       | 7.56%   |
| 6.0.0   | 152       | 1.74%   |
| 4.9.0   | 120       | 1.37%   |
| 6.5.0   | 119       | 1.36%   |
| 5.18.0  | 111       | 1.27%   |
| 5.15.0  | 92        | 1.05%   |
| 5.9.0   | 74        | 0.84%   |
| 5.16.0  | 72        | 0.82%   |
| 5.19.0  | 70        | 0.8%    |
| 5.4.0   | 65        | 0.74%   |
| 5.7.0   | 59        | 0.67%   |
| 5.8.0   | 56        | 0.64%   |
| 5.14.0  | 53        | 0.61%   |
| 6.4.0   | 47        | 0.54%   |
| 5.6.0   | 45        | 0.51%   |
| 6.6.15  | 41        | 0.47%   |
| 5.17.0  | 40        | 0.46%   |
| 6.7.12  | 39        | 0.45%   |
| 6.10.11 | 38        | 0.43%   |
| 6.6.13  | 32        | 0.37%   |
| 6.3.0   | 31        | 0.35%   |
| 6.10.6  | 29        | 0.33%   |
| 5.10.10 | 28        | 0.32%   |
| 6.8.12  | 27        | 0.31%   |
| 6.9.7   | 25        | 0.29%   |
| 6.11.5  | 24        | 0.27%   |
| 5.3.0   | 19        | 0.22%   |
| 6.12.6  | 17        | 0.19%   |
| 5.5.0   | 16        | 0.18%   |
| 6.11.10 | 14        | 0.16%   |
| 6.8.4   | 12        | 0.14%   |
| 6.2.16  | 12        | 0.14%   |
| 5.2.0   | 12        | 0.14%   |
| 4.18.0  | 12        | 0.14%   |
| 6.11.2  | 11        | 0.13%   |
| 6.10.9  | 11        | 0.13%   |
| 6.8.9   | 10        | 0.11%   |
| 6.7.9   | 10        | 0.11%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 3366      | 38.57%  |
| 6.1     | 2668      | 30.57%  |
| 4.19    | 668       | 7.65%   |
| 6.0     | 160       | 1.83%   |
| 6.5     | 136       | 1.56%   |
| 5.15    | 124       | 1.42%   |
| 4.9     | 123       | 1.41%   |
| 6.6     | 117       | 1.34%   |
| 5.18    | 116       | 1.33%   |
| 6.10    | 94        | 1.08%   |
| 5.9     | 80        | 0.92%   |
| 6.11    | 79        | 0.91%   |
| 5.4     | 77        | 0.88%   |
| 5.19    | 76        | 0.87%   |
| 5.16    | 76        | 0.87%   |
| 6.9     | 65        | 0.74%   |
| 6.7     | 65        | 0.74%   |
| 6.8     | 62        | 0.71%   |
| 5.7     | 62        | 0.71%   |
| 6.4     | 61        | 0.7%    |
| 5.8     | 61        | 0.7%    |
| 5.14    | 58        | 0.66%   |
| 5.6     | 49        | 0.56%   |
| 5.17    | 49        | 0.56%   |
| 6.3     | 39        | 0.45%   |
| 6.12    | 30        | 0.34%   |
| 5.3     | 24        | 0.27%   |
| 6.2     | 20        | 0.23%   |
| 5.5     | 19        | 0.22%   |
| 5.2     | 18        | 0.21%   |
| 5.13    | 13        | 0.15%   |
| 4.18    | 12        | 0.14%   |
| 5.12    | 9         | 0.1%    |
| 5.11    | 9         | 0.1%    |
| 3.16    | 9         | 0.1%    |
| 6       | 7         | 0.08%   |
| 3.10    | 4         | 0.05%   |
| 5.1     | 3         | 0.03%   |
| 5.0     | 3         | 0.03%   |
| 6.13    | 2         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 7769      | 96.13%  |
| i686    | 287       | 3.55%   |
| aarch64 | 13        | 0.16%   |
| armv7l  | 11        | 0.14%   |
| riscv64 | 1         | 0.01%   |
| i586    | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| GNOME             | 2514      | 30.24%  |
| Unknown           | 1467      | 17.64%  |
| KDE5              | 1427      | 17.16%  |
| XFCE              | 1116      | 13.42%  |
| MATE              | 348       | 4.19%   |
| X-Cinnamon        | 337       | 4.05%   |
| LXDE              | 241       | 2.9%    |
| Cinnamon          | 185       | 2.23%   |
| i3                | 140       | 1.68%   |
| LXQt              | 131       | 1.58%   |
| KDE               | 129       | 1.55%   |
| GNOME Flashback   | 50        | 0.6%    |
| lightdm-xsession  | 33        | 0.4%    |
| Budgie            | 24        | 0.29%   |
| GNOME Classic     | 23        | 0.28%   |
| trinity           | 22        | 0.26%   |
| Openbox           | 22        | 0.26%   |
| sway              | 11        | 0.13%   |
| KDE6              | 8         | 0.1%    |
| Hyprland          | 7         | 0.08%   |
| awesome           | 7         | 0.08%   |
| fluxbox           | 6         | 0.07%   |
| Enlightenment     | 6         | 0.07%   |
| DWM               | 6         | 0.07%   |
| BunsenLabs        | 6         | 0.07%   |
| bspwm             | 6         | 0.07%   |
| ICEWM             | 5         | 0.06%   |
| x-session-manager | 4         | 0.05%   |
| GNUstep           | 4         | 0.05%   |
| Unity             | 3         | 0.04%   |
| Deepin            | 3         | 0.04%   |
| Cutefish          | 3         | 0.04%   |
| xmonad            | 2         | 0.02%   |
| WindowMaker       | 2         | 0.02%   |
| Phosh:GNOME       | 2         | 0.02%   |
| mwm               | 2         | 0.02%   |
| KDE4              | 2         | 0.02%   |
| default           | 2         | 0.02%   |
| wmaker-common     | 1         | 0.01%   |
| TOS:GNOME         | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| X11         | 4464      | 53.83%  |
| Wayland     | 2344      | 28.26%  |
| Unknown     | 1128      | 13.6%   |
| Tty         | 351       | 4.23%   |
| Unspecified | 4         | 0.05%   |
| Web         | 2         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Unknown       | 2908      | 34.98%  |
| LightDM       | 1540      | 18.52%  |
| GDM3          | 1188      | 14.29%  |
| SDDM          | 1185      | 14.25%  |
| GDM           | 1063      | 12.79%  |
| TDM           | 312       | 3.75%   |
| NODM          | 35        | 0.42%   |
| XDM           | 27        | 0.32%   |
| SLiM          | 18        | 0.22%   |
| LXDM          | 15        | 0.18%   |
| KDM           | 8         | 0.1%    |
| Ly            | 5         | 0.06%   |
| GREETD        | 5         | 0.06%   |
| WDM           | 3         | 0.04%   |
| SU            | 1         | 0.01%   |
| DARKDM_ON_TTY | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 2868      | 34.88%  |
| Unknown | 1117      | 13.58%  |
| de_DE   | 548       | 6.66%   |
| ru_RU   | 491       | 5.97%   |
| fr_FR   | 485       | 5.9%    |
| en_GB   | 419       | 5.1%    |
| pt_BR   | 264       | 3.21%   |
| it_IT   | 233       | 2.83%   |
| es_ES   | 233       | 2.83%   |
| pl_PL   | 154       | 1.87%   |
| en_CA   | 116       | 1.41%   |
| C       | 102       | 1.24%   |
| en_IN   | 83        | 1.01%   |
| es_MX   | 82        | 1%      |
| en_AU   | 77        | 0.94%   |
| zh_CN   | 68        | 0.83%   |
| es_AR   | 64        | 0.78%   |
| en_IE   | 47        | 0.57%   |
| hu_HU   | 44        | 0.54%   |
| es_CL   | 43        | 0.52%   |
| de_CH   | 37        | 0.45%   |
| sv_SE   | 36        | 0.44%   |
| cs_CZ   | 35        | 0.43%   |
| nl_NL   | 32        | 0.39%   |
| tr_TR   | 29        | 0.35%   |
| pt_PT   | 29        | 0.35%   |
| es_CO   | 28        | 0.34%   |
| de_AT   | 25        | 0.3%    |
| fi_FI   | 24        | 0.29%   |
| es_VE   | 24        | 0.29%   |
| en_NZ   | 23        | 0.28%   |
| ca_ES   | 19        | 0.23%   |
| en_ZA   | 18        | 0.22%   |
| fr_BE   | 17        | 0.21%   |
| ja_JP   | 16        | 0.19%   |
| en_SG   | 15        | 0.18%   |
| da_DK   | 14        | 0.17%   |
| sk_SK   | 13        | 0.16%   |
| ko_KR   | 13        | 0.16%   |
| fr_CH   | 13        | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 5005      | 61.25%  |
| BIOS | 3166      | 38.75%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 6178      | 75.83%  |
| Overlay | 1323      | 16.24%  |
| Btrfs   | 306       | 3.76%   |
| Tmpfs   | 91        | 1.12%   |
| Unknown | 80        | 0.98%   |
| Xfs     | 69        | 0.85%   |
| Rootfs  | 34        | 0.42%   |
| Zfs     | 32        | 0.39%   |
| Ext2    | 16        | 0.2%    |
| Ext3    | 9         | 0.11%   |
| Aufs    | 5         | 0.06%   |
| F2fs    | 3         | 0.04%   |
| Jfs     | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 5089      | 61.93%  |
| Unknown | 1682      | 20.47%  |
| MBR     | 1446      | 17.6%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 6998      | 85.31%  |
| Yes       | 1205      | 14.69%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 6107      | 74.63%  |
| Yes       | 2076      | 25.37%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo                | 1894      | 23.44%  |
| Hewlett-Packard       | 1290      | 15.97%  |
| Dell                  | 1135      | 14.05%  |
| ASUSTek Computer      | 772       | 9.56%   |
| Apple                 | 737       | 9.12%   |
| Acer                  | 563       | 6.97%   |
| Google                | 260       | 3.22%   |
| MSI                   | 152       | 1.88%   |
| Toshiba               | 132       | 1.63%   |
| Samsung Electronics   | 121       | 1.5%    |
| HUAWEI                | 79        | 0.98%   |
| Unknown               | 74        | 0.92%   |
| Sony                  | 72        | 0.89%   |
| Aquarius              | 48        | 0.59%   |
| Fujitsu               | 44        | 0.54%   |
| Notebook              | 40        | 0.5%    |
| Alienware             | 28        | 0.35%   |
| Medion                | 27        | 0.33%   |
| Packard Bell          | 25        | 0.31%   |
| Positivo              | 23        | 0.28%   |
| Panasonic             | 23        | 0.28%   |
| Framework             | 23        | 0.28%   |
| TUXEDO                | 22        | 0.27%   |
| Timi                  | 21        | 0.26%   |
| HONOR                 | 21        | 0.26%   |
| Intel                 | 19        | 0.24%   |
| IBM                   | 18        | 0.22%   |
| Clevo                 | 17        | 0.21%   |
| LG Electronics        | 15        | 0.19%   |
| Gigabyte Technology   | 13        | 0.16%   |
| Fujitsu Siemens       | 13        | 0.16%   |
| eMachines             | 12        | 0.15%   |
| Razer                 | 11        | 0.14%   |
| Schenker              | 10        | 0.12%   |
| Chuwi                 | 10        | 0.12%   |
| Positivo Bahia - VAIO | 9         | 0.11%   |
| Insyde                | 9         | 0.11%   |
| SLIMBOOK              | 8         | 0.1%    |
| PC Specialist         | 8         | 0.1%    |
| GPU Company           | 8         | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Apple MacBook5,2                      | 357       | 4.42%   |
| Unknown                               | 101       | 1.25%   |
| Apple MacBookAir7,2                   | 85        | 1.05%   |
| Apple MacBookAir7,1                   | 78        | 0.97%   |
| Google Enguarde                       | 74        | 0.92%   |
| Apple MacBook2,1                      | 59        | 0.73%   |
| Google Reks                           | 48        | 0.59%   |
| Aquarius NS585                        | 48        | 0.59%   |
| HP Notebook                           | 40        | 0.5%    |
| Lenovo ThinkPad E475 20H40006US       | 25        | 0.31%   |
| Google Terra                          | 24        | 0.3%    |
| Apple MacBook4,1                      | 24        | 0.3%    |
| HP Pavilion g6                        | 23        | 0.28%   |
| Google Stout                          | 19        | 0.24%   |
| Dell Latitude E7440                   | 18        | 0.22%   |
| Dell Latitude 7480                    | 18        | 0.22%   |
| HP EliteBook 840 G6                   | 17        | 0.21%   |
| Acer Aspire A315-23                   | 17        | 0.21%   |
| Lenovo ThinkPad 13 2nd Gen 20J10046US | 16        | 0.2%    |
| HP Pavilion Notebook                  | 16        | 0.2%    |
| HP Pavilion dv6                       | 16        | 0.2%    |
| HP Laptop 15-db0xxx                   | 16        | 0.2%    |
| HP EliteBook 840 G3                   | 16        | 0.2%    |
| Dell Latitude E6420                   | 16        | 0.2%    |
| Dell Latitude 7490                    | 16        | 0.2%    |
| Dell Latitude E6430                   | 15        | 0.19%   |
| ASUS 1005HA                           | 15        | 0.19%   |
| HP EliteBook 8460p                    | 14        | 0.17%   |
| HP 250 G7 Notebook PC                 | 14        | 0.17%   |
| Dell Latitude E6400                   | 14        | 0.17%   |
| Dell Latitude 5420                    | 14        | 0.17%   |
| HP Pavilion dv7                       | 13        | 0.16%   |
| Dell XPS 13 9370                      | 13        | 0.16%   |
| Acer Aspire A515-56                   | 13        | 0.16%   |
| HP Laptop 15s-eq2xxx                  | 12        | 0.15%   |
| HP 255 G8 Notebook PC                 | 12        | 0.15%   |
| HP 15                                 | 12        | 0.15%   |
| Dell Latitude E7450                   | 12        | 0.15%   |
| Dell Inspiron 15-3567                 | 12        | 0.15%   |
| HP Pavilion g4                        | 11        | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 1204      | 14.9%   |
| Dell Latitude     | 439       | 5.43%   |
| Acer Aspire       | 363       | 4.49%   |
| Apple MacBook5    | 359       | 4.44%   |
| Lenovo IdeaPad    | 343       | 4.25%   |
| Dell Inspiron     | 294       | 3.64%   |
| HP EliteBook      | 274       | 3.39%   |
| HP Pavilion       | 206       | 2.55%   |
| HP ProBook        | 177       | 2.19%   |
| HP Laptop         | 175       | 2.17%   |
| ASUS VivoBook     | 169       | 2.09%   |
| Apple MacBookAir7 | 163       | 2.02%   |
| Dell XPS          | 133       | 1.65%   |
| Dell Precision    | 111       | 1.37%   |
| Toshiba Satellite | 101       | 1.25%   |
| Unknown           | 101       | 1.25%   |
| Dell Vostro       | 97        | 1.2%    |
| Google Enguarde   | 74        | 0.92%   |
| ASUS ASUS         | 68        | 0.84%   |
| HP Compaq         | 64        | 0.79%   |
| ASUS ZenBook      | 59        | 0.73%   |
| Apple MacBook2    | 59        | 0.73%   |
| Lenovo Legion     | 58        | 0.72%   |
| HP ZBook          | 57        | 0.71%   |
| Lenovo ThinkBook  | 49        | 0.61%   |
| Google Reks       | 48        | 0.59%   |
| Aquarius NS585    | 48        | 0.59%   |
| Acer Swift        | 47        | 0.58%   |
| Acer Nitro        | 46        | 0.57%   |
| HP 250            | 45        | 0.56%   |
| ASUS ROG          | 45        | 0.56%   |
| HP Notebook       | 40        | 0.5%    |
| Fujitsu LIFEBOOK  | 38        | 0.47%   |
| Acer TravelMate   | 38        | 0.47%   |
| Lenovo Yoga       | 34        | 0.42%   |
| HP ENVY           | 32        | 0.4%    |
| HP 255            | 31        | 0.38%   |
| HP OMEN           | 29        | 0.36%   |
| Google Terra      | 24        | 0.3%    |
| Apple MacBook4    | 24        | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 752       | 9.31%   |
| 2019    | 703       | 8.7%    |
| 2020    | 684       | 8.47%   |
| 2009    | 561       | 6.94%   |
| 2018    | 508       | 6.29%   |
| 2022    | 490       | 6.07%   |
| 2012    | 480       | 5.94%   |
| 2011    | 464       | 5.74%   |
| 2017    | 460       | 5.69%   |
| 2013    | 428       | 5.3%    |
| 2015    | 390       | 4.83%   |
| 2023    | 371       | 4.59%   |
| 2016    | 370       | 4.58%   |
| 2014    | 356       | 4.41%   |
| 2010    | 280       | 3.47%   |
| 2008    | 279       | 3.45%   |
| 2007    | 257       | 3.18%   |
| 2024    | 109       | 1.35%   |
| 2006    | 49        | 0.61%   |
| 2005    | 32        | 0.4%    |
| Unknown | 28        | 0.35%   |
| 2004    | 14        | 0.17%   |
| 2003    | 11        | 0.14%   |
| 2002    | 2         | 0.02%   |
| 2001    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 8079      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 7391      | 90.89%  |
| Enabled  | 741       | 9.11%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 7798      | 96.51%  |
| Yes  | 282       | 3.49%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 2124      | 25.98%  |
| 3.01-4.0    | 1451      | 17.75%  |
| 16.01-24.0  | 1429      | 17.48%  |
| 8.01-16.0   | 1331      | 16.28%  |
| 1.01-2.0    | 670       | 8.19%   |
| 32.01-64.0  | 619       | 7.57%   |
| 2.01-3.0    | 154       | 1.88%   |
| 24.01-32.0  | 140       | 1.71%   |
| 64.01-256.0 | 138       | 1.69%   |
| 0.51-1.0    | 93        | 1.14%   |
| 0.01-0.5    | 25        | 0.31%   |
| Unknown     | 2         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 2887      | 33.01%  |
| 2.01-3.0   | 1957      | 22.38%  |
| 4.01-8.0   | 1390      | 15.89%  |
| 3.01-4.0   | 1167      | 13.34%  |
| 0.51-1.0   | 713       | 8.15%   |
| 8.01-16.0  | 376       | 4.3%    |
| 0.01-0.5   | 183       | 2.09%   |
| 16.01-24.0 | 47        | 0.54%   |
| 24.01-32.0 | 12        | 0.14%   |
| Unknown    | 7         | 0.08%   |
| 32.01-64.0 | 6         | 0.07%   |
| 0          | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 6306      | 76.76%  |
| 2      | 1609      | 19.59%  |
| 3      | 201       | 2.45%   |
| 0      | 55        | 0.67%   |
| 4      | 35        | 0.43%   |
| 5      | 6         | 0.07%   |
| 7      | 2         | 0.02%   |
| 6      | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 5675      | 69.96%  |
| Yes       | 2437      | 30.04%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 6437      | 79.31%  |
| No        | 1679      | 20.69%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 7845      | 96.98%  |
| No        | 244       | 3.02%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 6575      | 80.81%  |
| No        | 1561      | 19.19%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 1766      | 21.72%  |
| Germany     | 796       | 9.79%   |
| France      | 613       | 7.54%   |
| Russia      | 593       | 7.29%   |
| Brazil      | 388       | 4.77%   |
| Italy       | 346       | 4.25%   |
| Spain       | 337       | 4.14%   |
| Poland      | 238       | 2.93%   |
| UK          | 205       | 2.52%   |
| Canada      | 201       | 2.47%   |
| Netherlands | 146       | 1.8%    |
| Mexico      | 123       | 1.51%   |
| India       | 123       | 1.51%   |
| Switzerland | 112       | 1.38%   |
| Sweden      | 107       | 1.32%   |
| China       | 97        | 1.19%   |
| Argentina   | 94        | 1.16%   |
| Australia   | 87        | 1.07%   |
| Turkey      | 86        | 1.06%   |
| Belgium     | 81        | 1%      |
| Portugal    | 71        | 0.87%   |
| Czechia     | 71        | 0.87%   |
| Hungary     | 69        | 0.85%   |
| Ukraine     | 68        | 0.84%   |
| Austria     | 68        | 0.84%   |
| Greece      | 60        | 0.74%   |
| Romania     | 57        | 0.7%    |
| Chile       | 55        | 0.68%   |
| Finland     | 54        | 0.66%   |
| Colombia    | 53        | 0.65%   |
| Norway      | 51        | 0.63%   |
| Indonesia   | 47        | 0.58%   |
| Ireland     | 39        | 0.48%   |
| Venezuela   | 30        | 0.37%   |
| New Zealand | 30        | 0.37%   |
| Japan       | 30        | 0.37%   |
| Denmark     | 29        | 0.36%   |
| Bulgaria    | 25        | 0.31%   |
| Belarus     | 25        | 0.31%   |
| Thailand    | 24        | 0.3%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Bangor            | 703       | 8.15%   |
| Dover-Foxcroft    | 229       | 2.66%   |
| Voronezh          | 184       | 2.13%   |
| Moscow            | 124       | 1.44%   |
| Paris             | 95        | 1.1%    |
| Berlin            | 84        | 0.97%   |
| St Petersburg     | 64        | 0.74%   |
| Madrid            | 64        | 0.74%   |
| Milan             | 56        | 0.65%   |
| Sao Paulo         | 55        | 0.64%   |
| Warsaw            | 53        | 0.61%   |
| Amsterdam         | 49        | 0.57%   |
| Vienna            | 46        | 0.53%   |
| Seville           | 45        | 0.52%   |
| Munich            | 42        | 0.49%   |
| Hamburg           | 40        | 0.46%   |
| Roubaix           | 39        | 0.45%   |
| Prague            | 37        | 0.43%   |
| Frankfurt am Main | 34        | 0.39%   |
| Barcelona         | 34        | 0.39%   |
| Athens            | 34        | 0.39%   |
| Budapest          | 33        | 0.38%   |
| Dublin            | 31        | 0.36%   |
| London            | 30        | 0.35%   |
| Istanbul          | 30        | 0.35%   |
| Toronto           | 29        | 0.34%   |
| Zurich            | 27        | 0.31%   |
| Rome              | 27        | 0.31%   |
| Brasília         | 26        | 0.3%    |
| Sydney            | 25        | 0.29%   |
| Mexico City       | 25        | 0.29%   |
| Helsinki          | 25        | 0.29%   |
| Santiago          | 23        | 0.27%   |
| Lisbon            | 23        | 0.27%   |
| Stockholm         | 22        | 0.26%   |
| Perm              | 22        | 0.26%   |
| Cologne           | 22        | 0.26%   |
| Bogotá           | 22        | 0.26%   |
| Leipzig           | 21        | 0.24%   |
| Belo Horizonte    | 21        | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 1573      | 2038   | 15.98%  |
| WDC                         | 995       | 1230   | 10.11%  |
| Seagate                     | 776       | 927    | 7.88%   |
| Toshiba                     | 648       | 735    | 6.58%   |
| Unknown                     | 626       | 804    | 6.36%   |
| SanDisk                     | 579       | 712    | 5.88%   |
| Kingston                    | 509       | 673    | 5.17%   |
| SK hynix                    | 446       | 585    | 4.53%   |
| Crucial                     | 368       | 448    | 3.74%   |
| Micron Technology           | 310       | 340    | 3.15%   |
| Fujitsu                     | 303       | 318    | 3.08%   |
| Intel                       | 257       | 334    | 2.61%   |
| Apple                       | 231       | 308    | 2.35%   |
| Hitachi                     | 228       | 268    | 2.32%   |
| A-DATA Technology           | 188       | 352    | 1.91%   |
| HGST                        | 181       | 210    | 1.84%   |
| KIOXIA                      | 135       | 160    | 1.37%   |
| Unknown                     | 86        | 102    | 0.87%   |
| China                       | 81        | 93     | 0.82%   |
| Phison                      | 52        | 62     | 0.53%   |
| Transcend                   | 49        | 62     | 0.5%    |
| Intenso                     | 49        | 61     | 0.5%    |
| LITEON                      | 47        | 57     | 0.48%   |
| Silicon Motion              | 42        | 49     | 0.43%   |
| PNY                         | 41        | 54     | 0.42%   |
| SPCC                        | 39        | 51     | 0.4%    |
| SSSTC                       | 38        | 40     | 0.39%   |
| Patriot                     | 36        | 39     | 0.37%   |
| JMicron Technology          | 35        | 37     | 0.36%   |
| Kingston Technology Company | 34        | 37     | 0.35%   |
| Team                        | 32        | 36     | 0.33%   |
| Lexar                       | 32        | 34     | 0.33%   |
| Micron/Crucial Technology   | 27        | 29     | 0.27%   |
| Netac                       | 26        | 34     | 0.26%   |
| LITEONIT                    | 26        | 31     | 0.26%   |
| Phison Electronics          | 25        | 33     | 0.25%   |
| GOODRAM                     | 24        | 27     | 0.24%   |
| UMIS                        | 22        | 28     | 0.22%   |
| ADATA Technology            | 21        | 22     | 0.21%   |
| SABRENT                     | 20        | 21     | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB                      | 240       | 2.37%   |
| Seagate ST1000LM035-1RK172 1TB                      | 99        | 0.98%   |
| Kingston SA400S37240G 240GB SSD                     | 92        | 0.91%   |
| Unknown                                             | 86        | 0.85%   |
| Apple SSD SM0128G 121GB                             | 79        | 0.78%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 77        | 0.76%   |
| Apple SSD AP0128H 121GB                             | 77        | 0.76%   |
| Kingston SA400S37120G 120GB SSD                     | 72        | 0.71%   |
| Toshiba MQ01ABD100 1TB                              | 63        | 0.62%   |
| Unknown MMC Card  32GB                              | 60        | 0.59%   |
| Toshiba MQ04ABF100 1TB                              | 58        | 0.57%   |
| HGST HTS721010A9E630 1TB                            | 58        | 0.57%   |
| Kingston SA400S37480G 480GB SSD                     | 57        | 0.56%   |
| Toshiba MQ01ABF050 500GB                            | 56        | 0.55%   |
| SanDisk NVMe SSD Drive 512GB                        | 55        | 0.54%   |
| Crucial CT500MX500SSD1 500GB                        | 53        | 0.52%   |
| Toshiba MK1655GSXF 160GB                            | 52        | 0.51%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 50        | 0.49%   |
| A-DATA SU800 512GB SSD                              | 50        | 0.49%   |
| SanDisk NVMe SSD Drive 1TB                          | 48        | 0.47%   |
| Samsung SSD 860 EVO 500GB                           | 45        | 0.44%   |
| Samsung SSD 850 EVO 250GB                           | 44        | 0.43%   |
| Toshiba MK1653GSX 160GB                             | 43        | 0.42%   |
| Seagate ST500LT012-1DG142 500GB                     | 43        | 0.42%   |
| Samsung SSD 970 EVO Plus 1TB                        | 42        | 0.41%   |
| Unknown MMC Card  64GB                              | 39        | 0.38%   |
| Unknown AGND3R  16GB                                | 39        | 0.38%   |
| Samsung SSD 860 EVO 250GB                           | 37        | 0.36%   |
| Crucial CT1000MX500SSD1 1TB                         | 37        | 0.36%   |
| Seagate ST9500325AS 500GB                           | 36        | 0.36%   |
| Samsung SSD 860 EVO 1TB                             | 36        | 0.36%   |
| Unknown HAG2e  16GB                                 | 35        | 0.35%   |
| Samsung SSD 980 1TB                                 | 35        | 0.35%   |
| Seagate ST1000LM048-2E7172 1TB                      | 32        | 0.32%   |
| Crucial CT240BX500SSD1 240GB                        | 32        | 0.32%   |
| Samsung SSD 850 EVO 500GB                           | 31        | 0.31%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 29        | 0.29%   |
| Kingston SV300S37A120G 120GB SSD                    | 29        | 0.29%   |
| Samsung SSD 870 EVO 500GB                           | 28        | 0.28%   |
| HGST HTS725050A7E630 500GB                          | 28        | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 750       | 895    | 28.45%  |
| WDC                 | 552       | 641    | 20.94%  |
| Toshiba             | 455       | 510    | 17.26%  |
| Fujitsu             | 303       | 318    | 11.49%  |
| Hitachi             | 228       | 268    | 8.65%   |
| HGST                | 181       | 210    | 6.87%   |
| Samsung Electronics | 51        | 53     | 1.93%   |
| Unknown             | 22        | 26     | 0.83%   |
| SABRENT             | 19        | 20     | 0.72%   |
| JMicron Technology  | 18        | 18     | 0.68%   |
| ASMT                | 12        | 20     | 0.46%   |
| IBM/Hitachi         | 7         | 9      | 0.27%   |
| TO Exter            | 5         | 6      | 0.19%   |
| Intenso             | 5         | 6      | 0.19%   |
| Apple               | 4         | 5      | 0.15%   |
| LaCie               | 3         | 3      | 0.11%   |
| Unknown             | 3         | 3      | 0.11%   |
| SILICONMOTION       | 2         | 2      | 0.08%   |
| External            | 2         | 2      | 0.08%   |
| ASMedia             | 2         | 2      | 0.08%   |
| WALRAM              | 1         | 1      | 0.04%   |
| USB                 | 1         | 2      | 0.04%   |
| Unknown (CF)        | 1         | 1      | 0.04%   |
| SYMTEC              | 1         | 1      | 0.04%   |
| STEC                | 1         | 1      | 0.04%   |
| Space ke            | 1         | 1      | 0.04%   |
| SAGE                | 1         | 1      | 0.04%   |
| QNAP                | 1         | 2      | 0.04%   |
| Maxone              | 1         | 1      | 0.04%   |
| IBM                 | 1         | 1      | 0.04%   |
| Hewlett-Packard     | 1         | 1      | 0.04%   |
| FC-1307             | 1         | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 626       | 796    | 20.38%  |
| Kingston            | 380       | 521    | 12.37%  |
| SanDisk             | 306       | 396    | 9.96%   |
| Crucial             | 301       | 371    | 9.8%    |
| A-DATA Technology   | 133       | 280    | 4.33%   |
| WDC                 | 132       | 167    | 4.3%    |
| Apple               | 129       | 148    | 4.2%    |
| SK hynix            | 81        | 94     | 2.64%   |
| Micron Technology   | 81        | 90     | 2.64%   |
| China               | 80        | 91     | 2.6%    |
| Intel               | 65        | 71     | 2.12%   |
| Toshiba             | 50        | 56     | 1.63%   |
| Transcend           | 43        | 53     | 1.4%    |
| LITEON              | 40        | 47     | 1.3%    |
| Intenso             | 39        | 49     | 1.27%   |
| PNY                 | 35        | 47     | 1.14%   |
| Patriot             | 32        | 35     | 1.04%   |
| SPCC                | 29        | 40     | 0.94%   |
| LITEONIT            | 26        | 31     | 0.85%   |
| Team                | 24        | 28     | 0.78%   |
| Netac               | 23        | 31     | 0.75%   |
| GOODRAM             | 19        | 22     | 0.62%   |
| Unknown             | 18        | 18     | 0.59%   |
| Lexar               | 17        | 18     | 0.55%   |
| OCZ                 | 14        | 16     | 0.46%   |
| KingSpec            | 13        | 13     | 0.42%   |
| KIOXIA-EXCERIA      | 11        | 12     | 0.36%   |
| Hewlett-Packard     | 11        | 14     | 0.36%   |
| Plextor             | 10        | 10     | 0.33%   |
| Dogfish             | 10        | 13     | 0.33%   |
| Apacer              | 10        | 10     | 0.33%   |
| LDLC                | 9         | 9      | 0.29%   |
| Emtec               | 9         | 9      | 0.29%   |
| Seagate             | 8         | 8      | 0.26%   |
| KingDian            | 8         | 8      | 0.26%   |
| Corsair             | 8         | 9      | 0.26%   |
| Verbatim            | 7         | 7      | 0.23%   |
| Gigabyte Technology | 7         | 8      | 0.23%   |
| BHT                 | 7         | 7      | 0.23%   |
| AMD                 | 7         | 9      | 0.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 3155      | 4259   | 33.71%  |
| SSD     | 2860      | 3922   | 30.56%  |
| HDD     | 2556      | 3031   | 27.31%  |
| MMC     | 679       | 873    | 7.25%   |
| Unknown | 110       | 125    | 1.18%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 4842      | 6674   | 53.82%  |
| NVMe | 3148      | 4233   | 34.99%  |
| MMC  | 679       | 873    | 7.55%   |
| SAS  | 328       | 430    | 3.65%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 3749      | 4828   | 70.17%  |
| 0.51-1.0   | 1361      | 1824   | 25.47%  |
| 1.01-2.0   | 180       | 236    | 3.37%   |
| 4.01-10.0  | 25        | 31     | 0.47%   |
| 3.01-4.0   | 23        | 28     | 0.43%   |
| 2.01-3.0   | 3         | 4      | 0.06%   |
| 10.01-20.0 | 1         | 1      | 0.02%   |
| 0          | 1         | 1      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 2367      | 28.14%  |
| 251-500        | 1982      | 23.56%  |
| 501-1000       | 1214      | 14.43%  |
| Unknown        | 890       | 10.58%  |
| 51-100         | 528       | 6.28%   |
| 1-20           | 465       | 5.53%   |
| 1001-2000      | 451       | 5.36%   |
| 21-50          | 298       | 3.54%   |
| More than 3000 | 110       | 1.31%   |
| 2001-3000      | 106       | 1.26%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 3233      | 37.12%  |
| 21-50          | 1220      | 14.01%  |
| 101-250        | 1143      | 13.12%  |
| 51-100         | 979       | 11.24%  |
| Unknown        | 890       | 10.22%  |
| 251-500        | 657       | 7.54%   |
| 501-1000       | 361       | 4.15%   |
| 1001-2000      | 148       | 1.7%    |
| 2001-3000      | 34        | 0.39%   |
| More than 3000 | 29        | 0.33%   |
| 0              | 15        | 0.17%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB                      | 25        | 25     | 3.37%   |
| Seagate ST9500325AS 500GB                           | 15        | 15     | 2.02%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 13        | 15     | 1.75%   |
| Toshiba MQ01ABD100 1TB                              | 11        | 12     | 1.48%   |
| Hitachi HTS543216L9SA02 160GB                       | 11        | 11     | 1.48%   |
| Seagate ST500LT012-9WS142 500GB                     | 10        | 11     | 1.35%   |
| HGST HTS725050A7E630 500GB                          | 10        | 12     | 1.35%   |
| Toshiba MK1653GSX 160GB                             | 9         | 9      | 1.21%   |
| SK hynix PC711 HFS512GDE9X073N 512GB                | 9         | 12     | 1.21%   |
| Seagate ST9320325AS 320GB                           | 9         | 10     | 1.21%   |
| Seagate ST1000LM035-1RK172 1TB                      | 9         | 10     | 1.21%   |
| Toshiba MQ01ABF050 500GB                            | 8         | 8      | 1.08%   |
| Toshiba MK1655GSXF 160GB                            | 8         | 9      | 1.08%   |
| Seagate ST9500420AS 500GB                           | 8         | 9      | 1.08%   |
| Seagate ST500LM021-1KJ152 500GB                     | 8         | 8      | 1.08%   |
| HGST HTS541010A9E680 1TB                            | 8         | 8      | 1.08%   |
| Seagate ST500LT012-1DG142 500GB                     | 7         | 7      | 0.94%   |
| Hitachi HTS545050B9A300 500GB                       | 7         | 7      | 0.94%   |
| Seagate ST320LT007-9ZV142 320GB                     | 6         | 8      | 0.81%   |
| Kingston SV300S37A120G 120GB SSD                    | 6         | 6      | 0.81%   |
| HGST HTS721010A9E630 1TB                            | 6         | 8      | 0.81%   |
| HGST HTS545050A7E680 500GB                          | 6         | 7      | 0.81%   |
| Toshiba MQ04ABF100 1TB                              | 5         | 5      | 0.67%   |
| SK hynix BC711 HFM512GD3JX013N 512GB                | 5         | 5      | 0.67%   |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB SSD | 5         | 5      | 0.67%   |
| Hitachi HTS547575A9E384 752GB                       | 5         | 5      | 0.67%   |
| Hitachi HTS543232A7A384 320GB                       | 5         | 5      | 0.67%   |
| Hitachi HTS542512K9SA00 120GB                       | 5         | 6      | 0.67%   |
| WDC WD1600BUDT-63DPZY0 160GB                        | 4         | 4      | 0.54%   |
| Toshiba MQ01ACF050 500GB                            | 4         | 4      | 0.54%   |
| SK hynix HFS256G39TND-N210A 256GB SSD               | 4         | 4      | 0.54%   |
| SK hynix HFS128G39TND-N210A 128GB SSD               | 4         | 4      | 0.54%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 4         | 4      | 0.54%   |
| Seagate ST500LM000-SSHD-8GB                         | 4         | 4      | 0.54%   |
| Samsung Electronics SSD 870 EVO 500GB               | 4         | 4      | 0.54%   |
| Kingston SA400S37240G 240GB SSD                     | 4         | 4      | 0.54%   |
| Kingston SA400S37120G 120GB SSD                     | 4         | 6      | 0.54%   |
| Hitachi HTS545032B9A300 320GB                       | 4         | 7      | 0.54%   |
| Hitachi HTS543216L9A300 160GB                       | 4         | 5      | 0.54%   |
| Hitachi HTS542516K9SA00 160GB                       | 4         | 4      | 0.54%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 151       | 166    | 20.41%  |
| Hitachi             | 97        | 109    | 13.11%  |
| Toshiba             | 82        | 86     | 11.08%  |
| WDC                 | 73        | 79     | 9.86%   |
| HGST                | 47        | 52     | 6.35%   |
| Samsung Electronics | 45        | 51     | 6.08%   |
| SK hynix            | 41        | 48     | 5.54%   |
| Fujitsu             | 40        | 42     | 5.41%   |
| Kingston            | 24        | 26     | 3.24%   |
| Intel               | 23        | 24     | 3.11%   |
| SanDisk             | 21        | 24     | 2.84%   |
| Micron Technology   | 18        | 20     | 2.43%   |
| Crucial             | 14        | 16     | 1.89%   |
| A-DATA Technology   | 11        | 13     | 1.49%   |
| Apple               | 6         | 7      | 0.81%   |
| SSSTC               | 5         | 5      | 0.68%   |
| LITEON              | 5         | 5      | 0.68%   |
| Unknown             | 4         | 4      | 0.54%   |
| LITEONIT            | 3         | 4      | 0.41%   |
| IBM/Hitachi         | 3         | 3      | 0.41%   |
| Lenovo              | 2         | 2      | 0.27%   |
| KingSpec            | 2         | 2      | 0.27%   |
| Kimtigo             | 2         | 2      | 0.27%   |
| JMicron Technology  | 2         | 2      | 0.27%   |
| Dogfish             | 2         | 2      | 0.27%   |
| Corsair             | 2         | 2      | 0.27%   |
| China               | 2         | 2      | 0.27%   |
| Transcend           | 1         | 1      | 0.14%   |
| Team                | 1         | 1      | 0.14%   |
| ShiJi               | 1         | 7      | 0.14%   |
| Plextor             | 1         | 1      | 0.14%   |
| Phison              | 1         | 1      | 0.14%   |
| OCZ                 | 1         | 1      | 0.14%   |
| KLEVV               | 1         | 1      | 0.14%   |
| KingDian            | 1         | 1      | 0.14%   |
| IBM                 | 1         | 1      | 0.14%   |
| HECTRON             | 1         | 1      | 0.14%   |
| GOODRAM             | 1         | 1      | 0.14%   |
| GLOWAY              | 1         | 1      | 0.14%   |
| DGM                 | 1         | 1      | 0.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 151       | 166    | 29.72%  |
| Hitachi             | 97        | 109    | 19.09%  |
| Toshiba             | 81        | 85     | 15.94%  |
| WDC                 | 68        | 74     | 13.39%  |
| HGST                | 47        | 52     | 9.25%   |
| Fujitsu             | 40        | 42     | 7.87%   |
| Samsung Electronics | 18        | 18     | 3.54%   |
| IBM/Hitachi         | 3         | 3      | 0.59%   |
| JMicron Technology  | 1         | 1      | 0.2%    |
| IBM                 | 1         | 1      | 0.2%    |
| Apple               | 1         | 2      | 0.2%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 503       | 553    | 68.44%  |
| SSD     | 187       | 205    | 25.44%  |
| NVMe    | 44        | 58     | 5.99%   |
| Unknown | 1         | 1      | 0.14%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                           | Notebooks | Drives | Percent |
|-------------------------------------------------|-----------|--------|---------|
| Crucial CT500P2SSD8 500GB                       | 2         | 2      | 16.67%  |
| WDC WD5000BEVT-35A0RT0 500GB                    | 1         | 1      | 8.33%   |
| Toshiba MQ04ABF100 1TB                          | 1         | 1      | 8.33%   |
| Toshiba MK6465GSX 640GB                         | 1         | 1      | 8.33%   |
| Toshiba MK3276GSXN 320GB                        | 1         | 1      | 8.33%   |
| Seagate ST500LT012-1DG142 500GB                 | 1         | 1      | 8.33%   |
| Seagate ST500LM000-1EJ162 500GB                 | 1         | 1      | 8.33%   |
| Samsung Electronics MZVLB512HAJQ-000H1 512GB    | 1         | 1      | 8.33%   |
| Samsung Electronics MZMPC032HBCD-000H1 32GB SSD | 1         | 1      | 8.33%   |
| Hitachi HTS545050A7E380 500GB                   | 1         | 2      | 8.33%   |
| HGST HTS721010A9E630 1TB                        | 1         | 1      | 8.33%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 3         | 3      | 25%     |
| Seagate             | 2         | 2      | 16.67%  |
| Samsung Electronics | 2         | 2      | 16.67%  |
| Crucial             | 2         | 2      | 16.67%  |
| WDC                 | 1         | 1      | 8.33%   |
| Hitachi             | 1         | 2      | 8.33%   |
| HGST                | 1         | 1      | 8.33%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 5351      | 7445   | 61.6%   |
| Detected | 2592      | 3934   | 29.84%  |
| Malfunc  | 730       | 817    | 8.4%    |
| Failed   | 12        | 13     | 0.14%   |
| Limited  | 1         | 1      | 0.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 4803      | 51.77%  |
| Samsung Electronics                     | 1020      | 10.99%  |
| AMD                                     | 766       | 8.26%   |
| SanDisk                                 | 559       | 6.03%   |
| Nvidia                                  | 405       | 4.37%   |
| SK hynix                                | 348       | 3.75%   |
| Micron Technology                       | 235       | 2.53%   |
| Kingston Technology Company             | 160       | 1.72%   |
| Toshiba America Info Systems            | 158       | 1.7%    |
| KIOXIA                                  | 131       | 1.41%   |
| Phison Electronics                      | 103       | 1.11%   |
| Apple                                   | 91        | 0.98%   |
| Micron/Crucial Technology               | 89        | 0.96%   |
| ADATA Technology                        | 77        | 0.83%   |
| Silicon Motion                          | 65        | 0.7%    |
| Solid State Storage Technology          | 47        | 0.51%   |
| Union Memory (Shenzhen)                 | 33        | 0.36%   |
| MAXIO Technology (Hangzhou)             | 29        | 0.31%   |
| Shenzhen Longsys Electronics            | 21        | 0.23%   |
| Realtek Semiconductor                   | 18        | 0.19%   |
| Silicon Integrated Systems [SiS]        | 17        | 0.18%   |
| Yangtze Memory Technologies             | 11        | 0.12%   |
| Solidigm                                | 11        | 0.12%   |
| Marvell Technology Group                | 9         | 0.1%    |
| Lite-On Technology                      | 9         | 0.1%    |
| Lenovo                                  | 9         | 0.1%    |
| Biwin Storage Technology                | 7         | 0.08%   |
| Seagate Technology                      | 6         | 0.06%   |
| VIA Technologies                        | 5         | 0.05%   |
| INNOGRIT                                | 5         | 0.05%   |
| Shenzhen Unionmemory Information System | 4         | 0.04%   |
| ASMedia Technology                      | 4         | 0.04%   |
| ULi Electronics                         | 3         | 0.03%   |
| Transcend                               | 3         | 0.03%   |
| Silicon Image                           | 3         | 0.03%   |
| Jiangsu Huacun Elec.                    | 3         | 0.03%   |
| Hosin Global Electronics                | 3         | 0.03%   |
| Zhaoxin                                 | 2         | 0.02%   |
| JMicron Technology                      | 2         | 0.02%   |
| Unknown                                 | 2         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 665       | 6.72%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 597       | 6.03%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 519       | 5.24%   |
| Nvidia MCP79 AHCI Controller                                                   | 377       | 3.81%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 362       | 3.66%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 360       | 3.64%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 335       | 3.38%   |
| Intel Volume Management Device NVMe RAID Controller                            | 305       | 3.08%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 233       | 2.35%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 231       | 2.33%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 182       | 1.84%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 177       | 1.79%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 171       | 1.73%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 168       | 1.7%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 139       | 1.4%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 134       | 1.35%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 131       | 1.32%   |
| Intel Tiger Lake-LP SATA Controller                                            | 130       | 1.31%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 126       | 1.27%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 125       | 1.26%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 116       | 1.17%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 113       | 1.14%   |
| Intel Comet Lake SATA AHCI Controller                                          | 109       | 1.1%    |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 103       | 1.04%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 101       | 1.02%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 98        | 0.99%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 94        | 0.95%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 93        | 0.94%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 86        | 0.87%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 84        | 0.85%   |
| Apple S1X NVMe Controller                                                      | 79        | 0.8%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 78        | 0.79%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 73        | 0.74%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 72        | 0.73%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 71        | 0.72%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 68        | 0.69%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 67        | 0.68%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 65        | 0.66%   |
| Intel SSD 660P Series                                                          | 65        | 0.66%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 64        | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 5129      | 53.68%  |
| NVMe | 3143      | 32.9%   |
| RAID | 748       | 7.83%   |
| IDE  | 533       | 5.58%   |
| SCSI | 1         | 0.01%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 6694      | 82.83%  |
| AMD          | 1354      | 16.75%  |
| ARM          | 18        | 0.22%   |
| CentaurHauls | 8         | 0.1%    |
| Unknown      | 8         | 0.1%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU P7450 @ 2.13GHz          | 359       | 4.44%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 163       | 2.01%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 151       | 1.87%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 112       | 1.38%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 108       | 1.33%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 106       | 1.31%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 102       | 1.26%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 102       | 1.26%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 100       | 1.24%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 97        | 1.2%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 95        | 1.17%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 89        | 1.1%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 87        | 1.08%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 85        | 1.05%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 82        | 1.01%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 75        | 0.93%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 72        | 0.89%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 70        | 0.86%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 69        | 0.85%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 66        | 0.82%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 65        | 0.8%    |
| Intel Core 2 CPU T7200 @ 2.00GHz              | 64        | 0.79%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 58        | 0.72%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 58        | 0.72%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 57        | 0.7%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 55        | 0.68%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 55        | 0.68%   |
| Intel 12th Gen Core i5-1235U                  | 54        | 0.67%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 53        | 0.65%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 50        | 0.62%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 50        | 0.62%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 48        | 0.59%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 48        | 0.59%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 48        | 0.59%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 48        | 0.59%   |
| Intel 12th Gen Core i7-12700H                 | 48        | 0.59%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 46        | 0.57%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 46        | 0.57%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 43        | 0.53%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 41        | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1859      | 22.98%  |
| Intel Core i7           | 1424      | 17.6%   |
| Other                   | 1008      | 12.46%  |
| Intel Core 2 Duo        | 648       | 8.01%   |
| Intel Celeron           | 569       | 7.03%   |
| Intel Core i3           | 514       | 6.35%   |
| AMD Ryzen 5             | 369       | 4.56%   |
| AMD Ryzen 7             | 308       | 3.81%   |
| Intel Atom              | 215       | 2.66%   |
| Intel Pentium           | 140       | 1.73%   |
| AMD Ryzen 7 PRO         | 103       | 1.27%   |
| Intel Core 2            | 83        | 1.03%   |
| AMD Ryzen 3             | 56        | 0.69%   |
| AMD A6                  | 56        | 0.69%   |
| Intel Pentium Dual-Core | 51        | 0.63%   |
| AMD Ryzen 9             | 51        | 0.63%   |
| AMD Ryzen 5 PRO         | 43        | 0.53%   |
| Intel Pentium M         | 41        | 0.51%   |
| Intel Genuine           | 39        | 0.48%   |
| AMD A4                  | 38        | 0.47%   |
| Intel Core              | 35        | 0.43%   |
| AMD A8                  | 33        | 0.41%   |
| Intel Pentium Dual      | 29        | 0.36%   |
| AMD E                   | 28        | 0.35%   |
| AMD E2                  | 27        | 0.33%   |
| Intel Pentium Silver    | 25        | 0.31%   |
| AMD E1                  | 24        | 0.3%    |
| AMD A10                 | 21        | 0.26%   |
| Intel Core i9           | 18        | 0.22%   |
| Intel Celeron M         | 18        | 0.22%   |
| AMD PRO A10             | 14        | 0.17%   |
| Intel Xeon              | 13        | 0.16%   |
| Intel Core m3           | 12        | 0.15%   |
| AMD Turion 64 X2 Mobile | 11        | 0.14%   |
| AMD Athlon II           | 11        | 0.14%   |
| AMD Athlon              | 11        | 0.14%   |
| Intel Pentium 4         | 9         | 0.11%   |
| Intel Core Duo          | 9         | 0.11%   |
| AMD C-50                | 8         | 0.1%    |
| AMD A12                 | 8         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 4003      | 49.48%  |
| 4       | 2347      | 29.01%  |
| 8       | 530       | 6.55%   |
| 6       | 519       | 6.42%   |
| 1       | 258       | 3.19%   |
| 10      | 168       | 2.08%   |
| 14      | 119       | 1.47%   |
| 12      | 92        | 1.14%   |
| 16      | 38        | 0.47%   |
| 24      | 11        | 0.14%   |
| 5       | 2         | 0.02%   |
| 20      | 1         | 0.01%   |
| 3       | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 8074      | 99.94%  |
| 2       | 4         | 0.05%   |
| Unknown | 1         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 5730      | 70.81%  |
| 1       | 2360      | 29.16%  |
| 4       | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 7836      | 96.97%  |
| 32-bit         | 164       | 2.03%   |
| Unknown        | 74        | 0.92%   |
| 64-bit         | 7         | 0.09%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2364      | 28.46%  |
| 0x1067a    | 507       | 6.1%    |
| 0x306a9    | 343       | 4.13%   |
| 0x206a7    | 313       | 3.77%   |
| 0x306d4    | 303       | 3.65%   |
| 0x806c1    | 287       | 3.45%   |
| 0x806ec    | 272       | 3.27%   |
| 0x806ea    | 200       | 2.41%   |
| 0x406e3    | 195       | 2.35%   |
| 0x40651    | 191       | 2.3%    |
| 0x806e9    | 185       | 2.23%   |
| 0x30678    | 149       | 1.79%   |
| 0x306c3    | 134       | 1.61%   |
| 0x406c4    | 128       | 1.54%   |
| 0x906a3    | 112       | 1.35%   |
| 0x20655    | 108       | 1.3%    |
| 0x906ea    | 107       | 1.29%   |
| 0x08108109 | 97        | 1.17%   |
| 0xa0652    | 93        | 1.12%   |
| 0x0a50000c | 93        | 1.12%   |
| 0x906a4    | 92        | 1.11%   |
| 0x08608103 | 90        | 1.08%   |
| 0x08600106 | 78        | 0.94%   |
| 0x706a8    | 70        | 0.84%   |
| 0x6f6      | 69        | 0.83%   |
| 0x706e5    | 68        | 0.82%   |
| 0x10676    | 63        | 0.76%   |
| 0x08108102 | 61        | 0.73%   |
| 0x6fd      | 60        | 0.72%   |
| 0x506e3    | 55        | 0.66%   |
| 0x0a50000d | 54        | 0.65%   |
| 0x806eb    | 52        | 0.63%   |
| 0x106ca    | 52        | 0.63%   |
| 0x506c9    | 51        | 0.61%   |
| 0x806d1    | 50        | 0.6%    |
| 0x906e9    | 49        | 0.59%   |
| 0x906eb    | 48        | 0.58%   |
| 0x06006705 | 47        | 0.57%   |
| 0xb06a2    | 45        | 0.54%   |
| 0x106c2    | 44        | 0.53%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KabyLake          | 1402      | 17.29%  |
| Penryn            | 639       | 7.88%   |
| Unknown           | 533       | 6.57%   |
| IvyBridge         | 500       | 6.17%   |
| Haswell           | 472       | 5.82%   |
| SandyBridge       | 456       | 5.62%   |
| TigerLake         | 406       | 5.01%   |
| Skylake           | 384       | 4.74%   |
| Silvermont        | 377       | 4.65%   |
| Broadwell         | 367       | 4.53%   |
| Alderlake Hybrid  | 320       | 3.95%   |
| Zen 3             | 226       | 2.79%   |
| Westmere          | 208       | 2.57%   |
| Core              | 208       | 2.57%   |
| Zen+              | 193       | 2.38%   |
| Zen 2             | 171       | 2.11%   |
| IceLake           | 143       | 1.76%   |
| CometLake         | 139       | 1.71%   |
| Goldmont plus     | 134       | 1.65%   |
| Excavator         | 134       | 1.65%   |
| Bonnell           | 130       | 1.6%    |
| P6                | 97        | 1.2%    |
| Goldmont          | 70        | 0.86%   |
| Bobcat            | 62        | 0.76%   |
| Zen               | 53        | 0.65%   |
| Puma              | 49        | 0.6%    |
| Jaguar            | 33        | 0.41%   |
| K8 Hammer         | 27        | 0.33%   |
| Piledriver        | 26        | 0.32%   |
| Tremont           | 25        | 0.31%   |
| K10 Llano         | 21        | 0.26%   |
| K10               | 21        | 0.26%   |
| Nehalem           | 19        | 0.23%   |
| Meteorlake Hybrid | 17        | 0.21%   |
| NetBurst          | 14        | 0.17%   |
| K8 & K10 hybrid   | 14        | 0.17%   |
| Gracemont         | 11        | 0.14%   |
| Steamroller       | 7         | 0.09%   |
| Lunarlake Hybrid  | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 5892      | 60.15%  |
| Nvidia                           | 2134      | 21.78%  |
| AMD                              | 1745      | 17.81%  |
| Silicon Integrated Systems [SiS] | 11        | 0.11%   |
| Zhaoxin                          | 7         | 0.07%   |
| VIA Technologies                 | 3         | 0.03%   |
| S3 Graphics                      | 3         | 0.03%   |
| Neomagic                         | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 472       | 4.64%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 412       | 4.05%   |
| Nvidia C79 [GeForce 9400M G]                                                             | 357       | 3.51%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 353       | 3.47%   |
| Intel UHD Graphics 620                                                                   | 313       | 3.08%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 267       | 2.63%   |
| Intel HD Graphics 620                                                                    | 261       | 2.57%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 261       | 2.57%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 237       | 2.33%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 205       | 2.02%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 201       | 1.98%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 190       | 1.87%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 186       | 1.83%   |
| Intel HD Graphics 5500                                                                   | 179       | 1.76%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 178       | 1.75%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 171       | 1.68%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 166       | 1.63%   |
| Intel HD Graphics 6000                                                                   | 164       | 1.61%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 154       | 1.52%   |
| Intel Core Processor Integrated Graphics Controller                                      | 153       | 1.51%   |
| AMD Lucienne                                                                             | 151       | 1.49%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 149       | 1.47%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 149       | 1.47%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 118       | 1.16%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 114       | 1.12%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 110       | 1.08%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 108       | 1.06%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 104       | 1.02%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 103       | 1.01%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 102       | 1%      |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 102       | 1%      |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 79        | 0.78%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 75        | 0.74%   |
| Intel HD Graphics 630                                                                    | 74        | 0.73%   |
| Intel HD Graphics 530                                                                    | 72        | 0.71%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 69        | 0.68%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 69        | 0.68%   |
| AMD Barcelo                                                                              | 68        | 0.67%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 65        | 0.64%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 65        | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| 1 x Intel              | 4249      | 52.46%  |
| Intel + Nvidia         | 1315      | 16.23%  |
| 1 x AMD                | 1235      | 15.25%  |
| 1 x Nvidia             | 648       | 8%      |
| Intel + AMD            | 245       | 3.02%   |
| AMD + Nvidia           | 168       | 2.07%   |
| 2 x AMD                | 97        | 1.2%    |
| 2 x Intel              | 68        | 0.84%   |
| Other                  | 42        | 0.52%   |
| 1 x SiS                | 11        | 0.14%   |
| 1 x Zhaoxin            | 7         | 0.09%   |
| 2 x Nvidia             | 4         | 0.05%   |
| 1 x VIA                | 3         | 0.04%   |
| 1 x S3 Graphics        | 3         | 0.04%   |
| 2 x Intel + 1 x Nvidia | 2         | 0.02%   |
| Intel + 2 x Nvidia     | 2         | 0.02%   |
| 1 x Neomagic           | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 7073      | 86.45%  |
| Proprietary | 622       | 7.6%    |
| Unknown     | 487       | 5.95%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 5979      | 72.97%  |
| 0.01-0.5       | 1090      | 13.3%   |
| 1.01-2.0       | 452       | 5.52%   |
| 3.01-4.0       | 269       | 3.28%   |
| 0.51-1.0       | 262       | 3.2%    |
| 5.01-6.0       | 72        | 0.88%   |
| 7.01-8.0       | 49        | 0.6%    |
| 2.01-3.0       | 13        | 0.16%   |
| 8.01-16.0      | 5         | 0.06%   |
| More than 64.0 | 1         | 0.01%   |
| 16.01-24.0     | 1         | 0.01%   |
| 0              | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 1641      | 18.52%  |
| BOE                     | 1265      | 14.28%  |
| Chimei Innolux          | 1101      | 12.43%  |
| LG Display              | 1006      | 11.35%  |
| Samsung Electronics     | 781       | 8.81%   |
| Apple                   | 733       | 8.27%   |
| Dell                    | 238       | 2.69%   |
| Lenovo                  | 197       | 2.22%   |
| Sharp                   | 185       | 2.09%   |
| Goldstar                | 171       | 1.93%   |
| InfoVision              | 152       | 1.72%   |
| Chi Mei Optoelectronics | 135       | 1.52%   |
| PANDA                   | 112       | 1.26%   |
| Hewlett-Packard         | 99        | 1.12%   |
| Philips                 | 85        | 0.96%   |
| BenQ                    | 82        | 0.93%   |
| AOC                     | 75        | 0.85%   |
| CSO                     | 73        | 0.82%   |
| LG Philips              | 62        | 0.7%    |
| Acer                    | 61        | 0.69%   |
| Iiyama                  | 51        | 0.58%   |
| HannStar                | 50        | 0.56%   |
| Ancor Communications    | 45        | 0.51%   |
| ASUSTek Computer        | 30        | 0.34%   |
| ViewSonic               | 29        | 0.33%   |
| Unknown                 | 28        | 0.32%   |
| Sony                    | 25        | 0.28%   |
| Eizo                    | 21        | 0.24%   |
| CPT                     | 19        | 0.21%   |
| MSI                     | 15        | 0.17%   |
| Quanta Display          | 13        | 0.15%   |
| Panasonic               | 13        | 0.15%   |
| NEC Computers           | 11        | 0.12%   |
| Unknown                 | 9         | 0.1%    |
| Toshiba                 | 8         | 0.09%   |
| TMX                     | 8         | 0.09%   |
| Pixio                   | 8         | 0.09%   |
| InnoLux Display         | 8         | 0.09%   |
| LGD                     | 7         | 0.08%   |
| Vizio                   | 6         | 0.07%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9C5B 1280x800 286x179mm 13.3-inch                 | 211       | 2.35%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch               | 194       | 2.16%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 75        | 0.84%   |
| BOE LCD Monitor BOE0609 1366x768 256x144mm 11.6-inch                 | 71        | 0.79%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 57        | 0.64%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch        | 53        | 0.59%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch        | 48        | 0.54%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                 | 48        | 0.54%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 44        | 0.49%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 43        | 0.48%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch      | 42        | 0.47%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                 | 42        | 0.47%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                 | 42        | 0.47%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 39        | 0.44%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 38        | 0.42%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch       | 35        | 0.39%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                 | 35        | 0.39%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 34        | 0.38%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 33        | 0.37%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch | 31        | 0.35%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch            | 30        | 0.33%   |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                 | 30        | 0.33%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 29        | 0.32%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch        | 29        | 0.32%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 27        | 0.3%    |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                | 25        | 0.28%   |
| InfoVision LCD Monitor IVO0489 1366x768 256x144mm 11.6-inch          | 24        | 0.27%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch       | 24        | 0.27%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 24        | 0.27%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 23        | 0.26%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch       | 23        | 0.26%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch       | 23        | 0.26%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch       | 23        | 0.26%   |
| Apple Color LCD APP9C5C 1280x800 286x179mm 13.3-inch                 | 23        | 0.26%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 22        | 0.25%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 22        | 0.25%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 22        | 0.25%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 21        | 0.23%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 21        | 0.23%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch       | 21        | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 3400      | 40.72%  |
| 1366x768 (WXGA)    | 2125      | 25.45%  |
| 1280x800 (WXGA)    | 677       | 8.11%   |
| 1600x900 (HD+)     | 330       | 3.95%   |
| 1920x1200 (WUXGA)  | 320       | 3.83%   |
| 3840x2160 (4K)     | 277       | 3.32%   |
| 2560x1440 (QHD)    | 215       | 2.57%   |
| 1440x900 (WXGA+)   | 209       | 2.5%    |
| 2560x1600          | 112       | 1.34%   |
| 1024x600           | 94        | 1.13%   |
| 2880x1800          | 77        | 0.92%   |
| 1680x1050 (WSXGA+) | 54        | 0.65%   |
| 3840x2400          | 49        | 0.59%   |
| 1280x1024 (SXGA)   | 48        | 0.57%   |
| 3440x1440          | 41        | 0.49%   |
| 2560x1080          | 40        | 0.48%   |
| 1360x768           | 25        | 0.3%    |
| 1024x768 (XGA)     | 23        | 0.28%   |
| 2288x1287          | 22        | 0.26%   |
| 2256x1504          | 21        | 0.25%   |
| 2160x1440          | 20        | 0.24%   |
| 3200x1800 (QHD+)   | 18        | 0.22%   |
| Unknown            | 14        | 0.17%   |
| 3200x2000          | 12        | 0.14%   |
| 1600x1200          | 12        | 0.14%   |
| 1400x1050          | 9         | 0.11%   |
| 3840x1080          | 8         | 0.1%    |
| 2240x1400          | 7         | 0.08%   |
| 1920x540           | 7         | 0.08%   |
| 800x1280           | 6         | 0.07%   |
| 3456x2160          | 6         | 0.07%   |
| 3072x1920          | 6         | 0.07%   |
| 3840x1100          | 5         | 0.06%   |
| 2880x1920          | 5         | 0.06%   |
| 2880x1620          | 5         | 0.06%   |
| 1280x720 (HD)      | 5         | 0.06%   |
| 3840x1600          | 4         | 0.05%   |
| 2520x1680          | 4         | 0.05%   |
| 2304x1440          | 4         | 0.05%   |
| 1920x1280          | 4         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 2880      | 32.54%  |
| 13      | 1693      | 19.13%  |
| 14      | 1219      | 13.77%  |
| 17      | 490       | 5.54%   |
| 11      | 404       | 4.56%   |
| 24      | 311       | 3.51%   |
| 12      | 296       | 3.34%   |
| 27      | 270       | 3.05%   |
| 23      | 207       | 2.34%   |
| 16      | 195       | 2.2%    |
| 21      | 154       | 1.74%   |
| 31      | 97        | 1.1%    |
| 10      | 95        | 1.07%   |
| 18      | 75        | 0.85%   |
| Unknown | 73        | 0.82%   |
| 34      | 64        | 0.72%   |
| 19      | 54        | 0.61%   |
| 22      | 28        | 0.32%   |
| 25      | 24        | 0.27%   |
| 20      | 23        | 0.26%   |
| 142     | 22        | 0.25%   |
| 40      | 17        | 0.19%   |
| 32      | 15        | 0.17%   |
| 72      | 14        | 0.16%   |
| 54      | 14        | 0.16%   |
| 84      | 12        | 0.14%   |
| 28      | 12        | 0.14%   |
| 8       | 11        | 0.12%   |
| 29      | 10        | 0.11%   |
| 46      | 8         | 0.09%   |
| 48      | 6         | 0.07%   |
| 26      | 6         | 0.07%   |
| 49      | 5         | 0.06%   |
| 33      | 5         | 0.06%   |
| 7       | 5         | 0.06%   |
| 65      | 4         | 0.05%   |
| 37      | 4         | 0.05%   |
| 58      | 3         | 0.03%   |
| 52      | 3         | 0.03%   |
| 43      | 3         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 4854      | 55.3%   |
| 201-300        | 1831      | 20.86%  |
| 501-600        | 748       | 8.52%   |
| 351-400        | 591       | 6.73%   |
| 401-500        | 301       | 3.43%   |
| 601-700        | 144       | 1.64%   |
| 701-800        | 85        | 0.97%   |
| Unknown        | 73        | 0.83%   |
| 1001-1500      | 51        | 0.58%   |
| 1501-2000      | 30        | 0.34%   |
| 801-900        | 25        | 0.28%   |
| More than 2000 | 22        | 0.25%   |
| 101-200        | 12        | 0.14%   |
| 1-100          | 6         | 0.07%   |
| 901-1000       | 5         | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 6037      | 76.42%  |
| 16/10   | 1509      | 19.1%   |
| 21/9    | 77        | 0.97%   |
| 3/2     | 75        | 0.95%   |
| 4/3     | 50        | 0.63%   |
| 5/4     | 49        | 0.62%   |
| Unknown | 48        | 0.61%   |
| 1.00    | 22        | 0.28%   |
| 32/9    | 7         | 0.09%   |
| 2.65    | 7         | 0.09%   |
| 3.40    | 5         | 0.06%   |
| 0.67    | 4         | 0.05%   |
| 3.20    | 3         | 0.04%   |
| 1.96    | 2         | 0.03%   |
| 6/5     | 1         | 0.01%   |
| 3.73    | 1         | 0.01%   |
| 0.62    | 1         | 0.01%   |
| 0.58    | 1         | 0.01%   |
| 0.56    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 2880      | 32.62%  |
| 81-90          | 2430      | 27.52%  |
| 201-250        | 537       | 6.08%   |
| 71-80          | 464       | 5.26%   |
| 51-60          | 409       | 4.63%   |
| 121-130        | 403       | 4.56%   |
| 61-70          | 287       | 3.25%   |
| 301-350        | 274       | 3.1%    |
| 351-500        | 195       | 2.21%   |
| 111-120        | 173       | 1.96%   |
| 251-300        | 143       | 1.62%   |
| 151-200        | 115       | 1.3%    |
| 41-50          | 95        | 1.08%   |
| 141-150        | 93        | 1.05%   |
| More than 1000 | 84        | 0.95%   |
| Unknown        | 73        | 0.83%   |
| 131-140        | 70        | 0.79%   |
| 501-1000       | 46        | 0.52%   |
| 91-100         | 40        | 0.45%   |
| 1-40           | 18        | 0.2%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 3759      | 43.34%  |
| 101-120       | 2574      | 29.68%  |
| 51-100        | 1235      | 14.24%  |
| 161-240       | 713       | 8.22%   |
| More than 240 | 224       | 2.58%   |
| 1-50          | 95        | 1.1%    |
| Unknown       | 73        | 0.84%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 6460      | 78.23%  |
| 2     | 1199      | 14.52%  |
| 0     | 445       | 5.39%   |
| 3     | 147       | 1.78%   |
| 4     | 5         | 0.06%   |
| 5     | 2         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 4188      | 32.54%  |
| Realtek Semiconductor             | 3721      | 28.91%  |
| Qualcomm Atheros                  | 1500      | 11.65%  |
| Broadcom                          | 1022      | 7.94%   |
| Nvidia                            | 399       | 3.1%    |
| Broadcom Limited                  | 331       | 2.57%   |
| MediaTek                          | 323       | 2.51%   |
| Marvell Technology Group          | 198       | 1.54%   |
| ASIX Electronics                  | 115       | 0.89%   |
| TP-Link                           | 88        | 0.68%   |
| Ralink                            | 88        | 0.68%   |
| Qualcomm                          | 78        | 0.61%   |
| Samsung Electronics               | 67        | 0.52%   |
| Sierra Wireless                   | 57        | 0.44%   |
| Lenovo                            | 54        | 0.42%   |
| Dell                              | 54        | 0.42%   |
| Xiaomi                            | 52        | 0.4%    |
| Ericsson Business Mobile Networks | 48        | 0.37%   |
| Ralink Technology                 | 47        | 0.37%   |
| JMicron Technology                | 41        | 0.32%   |
| Hewlett-Packard                   | 36        | 0.28%   |
| DisplayLink                       | 36        | 0.28%   |
| Fibocom                           | 26        | 0.2%    |
| Huawei Technologies               | 23        | 0.18%   |
| Silicon Integrated Systems [SiS]  | 16        | 0.12%   |
| NetGear                           | 16        | 0.12%   |
| OPPO Electronics                  | 14        | 0.11%   |
| Google                            | 14        | 0.11%   |
| Qualcomm Atheros Communications   | 13        | 0.1%    |
| Motorola PCS                      | 12        | 0.09%   |
| Attansic Technology               | 12        | 0.09%   |
| Cypress Semiconductor             | 11        | 0.09%   |
| ASUSTek Computer                  | 11        | 0.09%   |
| D-Link                            | 9         | 0.07%   |
| Microchip Technology              | 8         | 0.06%   |
| ICS Advent                        | 8         | 0.06%   |
| U-Blox                            | 7         | 0.05%   |
| QinHeng Electronics               | 6         | 0.05%   |
| Edimax Technology                 | 6         | 0.05%   |
| Apple                             | 6         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 2192      | 14.22%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 565       | 3.66%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 378       | 2.45%   |
| Nvidia MCP79 Ethernet                                                  | 378       | 2.45%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                 | 378       | 2.45%   |
| Intel Wireless 8265 / 8275                                             | 351       | 2.28%   |
| Intel Wireless 7265                                                    | 304       | 1.97%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 304       | 1.97%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 297       | 1.93%   |
| Intel Wireless 7260                                                    | 294       | 1.91%   |
| Intel Wi-Fi 6 AX201                                                    | 287       | 1.86%   |
| Intel Wi-Fi 6 AX200                                                    | 284       | 1.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 218       | 1.41%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 217       | 1.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 206       | 1.34%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 203       | 1.32%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 192       | 1.25%   |
| Intel Wireless 8260                                                    | 187       | 1.21%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 187       | 1.21%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 184       | 1.19%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 184       | 1.19%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter   | 179       | 1.16%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 165       | 1.07%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 150       | 0.97%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 149       | 0.97%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 148       | 0.96%   |
| Intel Ethernet Connection (4) I219-LM                                  | 147       | 0.95%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 119       | 0.77%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 110       | 0.71%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 107       | 0.69%   |
| Intel Ethernet Connection I219-LM                                      | 103       | 0.67%   |
| Intel Ethernet Connection (4) I219-V                                   | 101       | 0.66%   |
| ASIX AX88179 Gigabit Ethernet                                          | 101       | 0.66%   |
| Intel Wireless 3165                                                    | 100       | 0.65%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 96        | 0.62%   |
| Intel Ethernet Connection I218-LM                                      | 91        | 0.59%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 86        | 0.56%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 85        | 0.55%   |
| Broadcom BCM43142 802.11b/g/n                                          | 81        | 0.53%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 79        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 3943      | 47.88%  |
| Qualcomm Atheros                      | 1311      | 15.92%  |
| Realtek Semiconductor                 | 1105      | 13.42%  |
| Broadcom                              | 852       | 10.34%  |
| MediaTek                              | 282       | 3.42%   |
| Broadcom Limited                      | 269       | 3.27%   |
| Ralink                                | 88        | 1.07%   |
| TP-Link                               | 61        | 0.74%   |
| Qualcomm                              | 60        | 0.73%   |
| Sierra Wireless                       | 57        | 0.69%   |
| Ralink Technology                     | 47        | 0.57%   |
| Dell                                  | 36        | 0.44%   |
| Fibocom                               | 26        | 0.32%   |
| NetGear                               | 16        | 0.19%   |
| Qualcomm Atheros Communications       | 13        | 0.16%   |
| ASUSTek Computer                      | 11        | 0.13%   |
| Hewlett-Packard                       | 9         | 0.11%   |
| D-Link                                | 7         | 0.08%   |
| Edimax Technology                     | 6         | 0.07%   |
| Qualcomm Technologies                 | 4         | 0.05%   |
| Microsoft                             | 4         | 0.05%   |
| Linksys                               | 4         | 0.05%   |
| D-Link System                         | 4         | 0.05%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.04%   |
| Wilocity                              | 2         | 0.02%   |
| Quectel Wireless Solutions            | 2         | 0.02%   |
| Belkin Components                     | 2         | 0.02%   |
| 3Com                                  | 2         | 0.02%   |
| ZyXEL Communications                  | 1         | 0.01%   |
| ZyDAS                                 | 1         | 0.01%   |
| Z-Com                                 | 1         | 0.01%   |
| Winbond Electronics                   | 1         | 0.01%   |
| Wacom                                 | 1         | 0.01%   |
| Samsung Electronics                   | 1         | 0.01%   |
| Ovislink                              | 1         | 0.01%   |
| Marvell Technology Group              | 1         | 0.01%   |
| Cinterion                             | 1         | 0.01%   |
| Accton Technology                     | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 378       | 4.56%   |
| Intel Wireless 8265 / 8275                                                            | 351       | 4.24%   |
| Intel Wireless 7265                                                                   | 304       | 3.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 297       | 3.59%   |
| Intel Wireless 7260                                                                   | 294       | 3.55%   |
| Intel Wi-Fi 6 AX201                                                                   | 287       | 3.46%   |
| Intel Wi-Fi 6 AX200                                                                   | 284       | 3.43%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 218       | 2.63%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                      | 212       | 2.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 206       | 2.49%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 203       | 2.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 192       | 2.32%   |
| Intel Wireless 8260                                                                   | 187       | 2.26%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 187       | 2.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 184       | 2.22%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 184       | 2.22%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter                  | 179       | 2.16%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 165       | 1.99%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 150       | 1.81%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 149       | 1.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 148       | 1.79%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 119       | 1.44%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 110       | 1.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 107       | 1.29%   |
| Intel Wireless 3165                                                                   | 100       | 1.21%   |
| Intel Raptor Lake PCH CNVi WiFi                                                       | 96        | 1.16%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                             | 86        | 1.04%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 85        | 1.03%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 81        | 0.98%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 76        | 0.92%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 74        | 0.89%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                              | 72        | 0.87%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                               | 69        | 0.83%   |
| Intel Centrino Ultimate-N 6300                                                        | 66        | 0.8%    |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 63        | 0.76%   |
| Intel Wireless 3160                                                                   | 62        | 0.75%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 55        | 0.66%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 54        | 0.65%   |
| Qualcomm QCNFA765 Wireless Network Adapter                                            | 54        | 0.65%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 54        | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 3259      | 47.91%  |
| Intel                                  | 1691      | 24.86%  |
| Nvidia                                 | 399       | 5.87%   |
| Qualcomm Atheros                       | 357       | 5.25%   |
| Broadcom                               | 246       | 3.62%   |
| Marvell Technology Group               | 197       | 2.9%    |
| ASIX Electronics                       | 115       | 1.69%   |
| Broadcom Limited                       | 66        | 0.97%   |
| Lenovo                                 | 54        | 0.79%   |
| Xiaomi                                 | 52        | 0.76%   |
| MediaTek                               | 41        | 0.6%    |
| JMicron Technology                     | 41        | 0.6%    |
| Samsung Electronics                    | 36        | 0.53%   |
| DisplayLink                            | 36        | 0.53%   |
| TP-Link                                | 27        | 0.4%    |
| Qualcomm                               | 17        | 0.25%   |
| Silicon Integrated Systems [SiS]       | 16        | 0.24%   |
| Hewlett-Packard                        | 15        | 0.22%   |
| OPPO Electronics                       | 14        | 0.21%   |
| Huawei Technologies                    | 13        | 0.19%   |
| Google                                 | 13        | 0.19%   |
| Motorola PCS                           | 12        | 0.18%   |
| Attansic Technology                    | 12        | 0.18%   |
| Cypress Semiconductor                  | 11        | 0.16%   |
| Microchip Technology                   | 8         | 0.12%   |
| ICS Advent                             | 8         | 0.12%   |
| Apple                                  | 6         | 0.09%   |
| Suzhou Motorcomm Electronic Technology | 5         | 0.07%   |
| Spreadtrum Communications              | 4         | 0.06%   |
| VIA Technologies                       | 3         | 0.04%   |
| QinHeng Electronics                    | 3         | 0.04%   |
| LG Electronics                         | 3         | 0.04%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.03%   |
| National Semiconductor                 | 2         | 0.03%   |
| Davicom Semiconductor                  | 2         | 0.03%   |
| D-Link                                 | 2         | 0.03%   |
| 3DSP                                   | 2         | 0.03%   |
| ULi Electronics                        | 1         | 0.01%   |
| TP-Link Corporation Limited.           | 1         | 0.01%   |
| TOMTOM                                 | 1         | 0.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 2192      | 31.73%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 565       | 8.18%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 378       | 5.47%   |
| Nvidia MCP79 Ethernet                                                  | 378       | 5.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 304       | 4.4%    |
| Intel Ethernet Connection (4) I219-LM                                  | 147       | 2.13%   |
| Intel Ethernet Connection I219-LM                                      | 103       | 1.49%   |
| Intel Ethernet Connection (4) I219-V                                   | 101       | 1.46%   |
| ASIX AX88179 Gigabit Ethernet                                          | 101       | 1.46%   |
| Intel Ethernet Connection I218-LM                                      | 91        | 1.32%   |
| Intel Ethernet Connection (3) I218-LM                                  | 79        | 1.14%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 62        | 0.9%    |
| Intel Ethernet Connection I217-LM                                      | 61        | 0.88%   |
| Intel Ethernet Connection (6) I219-V                                   | 61        | 0.88%   |
| Intel 82577LM Gigabit Network Connection                               | 61        | 0.88%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 59        | 0.85%   |
| Intel 82567LM Gigabit Network Connection                               | 57        | 0.83%   |
| Intel Ethernet Connection I219-V                                       | 55        | 0.8%    |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 51        | 0.74%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 47        | 0.68%   |
| Intel Ethernet Connection (13) I219-V                                  | 47        | 0.68%   |
| Intel Ethernet Connection (6) I219-LM                                  | 43        | 0.62%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 43        | 0.62%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 39        | 0.56%   |
| Realtek RTL8125 2.5GbE Controller                                      | 38        | 0.55%   |
| Intel Ethernet Connection (16) I219-V                                  | 37        | 0.54%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 35        | 0.51%   |
| Intel Ethernet Connection (10) I219-V                                  | 35        | 0.51%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 34        | 0.49%   |
| Realtek Killer E2600 GbE Controller                                    | 34        | 0.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 34        | 0.49%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 30        | 0.43%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 30        | 0.43%   |
| Intel Ethernet Connection (13) I219-LM                                 | 30        | 0.43%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 29        | 0.42%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 29        | 0.42%   |
| Intel Ethernet Connection (7) I219-LM                                  | 29        | 0.42%   |
| Intel 82579V Gigabit Network Connection                                | 27        | 0.39%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 26        | 0.38%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 26        | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 7847      | 54.12%  |
| Ethernet | 6425      | 44.32%  |
| Modem    | 214       | 1.48%   |
| Unknown  | 12        | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 6124      | 71.58%  |
| Ethernet | 2429      | 28.39%  |
| Modem    | 2         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 5698      | 70.4%   |
| 1     | 2194      | 27.11%  |
| 0     | 129       | 1.59%   |
| 3     | 71        | 0.88%   |
| 5     | 1         | 0.01%   |
| 4     | 1         | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 6349      | 77.26%  |
| Yes  | 1869      | 22.74%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 3096      | 46.63%  |
| Apple                           | 714       | 10.75%  |
| Realtek Semiconductor           | 661       | 9.96%   |
| Qualcomm Atheros Communications | 515       | 7.76%   |
| IMC Networks                    | 330       | 4.97%   |
| Broadcom                        | 312       | 4.7%    |
| Foxconn / Hon Hai               | 234       | 3.52%   |
| Lite-On Technology              | 233       | 3.51%   |
| Dell                            | 93        | 1.4%    |
| Hewlett-Packard                 | 85        | 1.28%   |
| Cambridge Silicon Radio         | 67        | 1.01%   |
| Realtek                         | 44        | 0.66%   |
| Toshiba                         | 42        | 0.63%   |
| ASUSTek Computer                | 36        | 0.54%   |
| MediaTek                        | 35        | 0.53%   |
| USI                             | 30        | 0.45%   |
| Ralink                          | 30        | 0.45%   |
| Foxconn International           | 16        | 0.24%   |
| Alps Electric                   | 14        | 0.21%   |
| Ralink Technology               | 10        | 0.15%   |
| TP-Link                         | 5         | 0.08%   |
| Taiyo Yuden                     | 5         | 0.08%   |
| Fujitsu                         | 5         | 0.08%   |
| Edimax Technology               | 4         | 0.06%   |
| Chicony Electronics             | 4         | 0.06%   |
| Opticis                         | 3         | 0.05%   |
| Askey Computer                  | 3         | 0.05%   |
| Micro Star International        | 2         | 0.03%   |
| Corsair                         | 2         | 0.03%   |
| Belkin Components               | 2         | 0.03%   |
| Unknown                         | 1         | 0.02%   |
| Smart Modular Technologies      | 1         | 0.02%   |
| Qcom                            | 1         | 0.02%   |
| Marvell Semiconductor           | 1         | 0.02%   |
| Integrated System Solution      | 1         | 0.02%   |
| Conwise Technology              | 1         | 0.02%   |
| Unknown                         | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 1220      | 18.36%  |
| Intel AX201 Bluetooth                               | 593       | 8.92%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 463       | 6.97%   |
| Realtek Bluetooth Radio                             | 403       | 6.06%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 360       | 5.42%   |
| Qualcomm Atheros  Bluetooth Device                  | 285       | 4.29%   |
| Intel AX200 Bluetooth                               | 273       | 4.11%   |
| Intel AX211 Bluetooth                               | 233       | 3.51%   |
| Apple Bluetooth USB Host Controller                 | 186       | 2.8%    |
| Realtek  Bluetooth 4.2 Adapter                      | 128       | 1.93%   |
| IMC Networks Wireless_Device                        | 124       | 1.87%   |
| IMC Networks Bluetooth Radio                        | 88        | 1.32%   |
| Apple Bluetooth Host Controller                     | 80        | 1.2%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 77        | 1.16%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 76        | 1.14%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 76        | 1.14%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 73        | 1.1%    |
| Intel AX210 Bluetooth                               | 73        | 1.1%    |
| Foxconn / Hon Hai Bluetooth Device                  | 72        | 1.08%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 67        | 1.01%   |
| Realtek 802.11ac WLAN Adapter                       | 63        | 0.95%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 63        | 0.95%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 62        | 0.93%   |
| Broadcom BCM2045B (BDC-2.1)                         | 62        | 0.93%   |
| IMC Networks Bluetooth Device                       | 57        | 0.86%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 55        | 0.83%   |
| Lite-On Bluetooth Device                            | 55        | 0.83%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 51        | 0.77%   |
| Intel Wireless-AC 3168 Bluetooth                    | 49        | 0.74%   |
| Foxconn / Hon Hai Wireless_Device                   | 48        | 0.72%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 47        | 0.71%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 46        | 0.69%   |
| Realtek Bluetooth Radio                             | 44        | 0.66%   |
| HP Broadcom 2070 Bluetooth Combo                    | 43        | 0.65%   |
| Lite-On Wireless_Device                             | 42        | 0.63%   |
| MediaTek Wireless_Device                            | 34        | 0.51%   |
| Lite-On Atheros AR3012 Bluetooth                    | 31        | 0.47%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 31        | 0.47%   |
| USI Bluetooth Device                                | 30        | 0.45%   |
| Ralink RT3290 Bluetooth                             | 30        | 0.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 6180      | 64.56%  |
| AMD                                          | 1475      | 15.41%  |
| Nvidia                                       | 1305      | 13.63%  |
| C-Media Electronics                          | 67        | 0.7%    |
| Lenovo                                       | 59        | 0.62%   |
| Logitech                                     | 54        | 0.56%   |
| Realtek Semiconductor                        | 52        | 0.54%   |
| GN Netcom                                    | 40        | 0.42%   |
| Texas Instruments                            | 32        | 0.33%   |
| Hewlett-Packard                              | 24        | 0.25%   |
| Plantronics                                  | 21        | 0.22%   |
| Generalplus Technology                       | 19        | 0.2%    |
| Silicon Integrated Systems [SiS]             | 17        | 0.18%   |
| JMTek                                        | 15        | 0.16%   |
| ASUSTek Computer                             | 15        | 0.16%   |
| Creative Technology                          | 10        | 0.1%    |
| Zoran Co. Personal Media Division (Nogatech) | 8         | 0.08%   |
| SteelSeries ApS                              | 8         | 0.08%   |
| Kingston Technology                          | 8         | 0.08%   |
| Zhaoxin                                      | 7         | 0.07%   |
| Focusrite-Novation                           | 7         | 0.07%   |
| Dell                                         | 7         | 0.07%   |
| Razer USA                                    | 6         | 0.06%   |
| RODE Microphones                             | 5         | 0.05%   |
| CMX Systems                                  | 5         | 0.05%   |
| VIA Technologies                             | 4         | 0.04%   |
| Fujitsu                                      | 4         | 0.04%   |
| DSEA A/S                                     | 4         | 0.04%   |
| Apple                                        | 4         | 0.04%   |
| Yamaha                                       | 3         | 0.03%   |
| ULi Electronics                              | 3         | 0.03%   |
| Sony                                         | 3         | 0.03%   |
| QinHeng Electronics                          | 3         | 0.03%   |
| Microsoft                                    | 3         | 0.03%   |
| M-Audio                                      | 3         | 0.03%   |
| Jieli Technology                             | 3         | 0.03%   |
| Huawei Technologies                          | 3         | 0.03%   |
| ESS Technology                               | 3         | 0.03%   |
| Conexant Systems                             | 3         | 0.03%   |
| BEHRINGER International                      | 3         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 933       | 8.03%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 910       | 7.83%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 579       | 4.98%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 480       | 4.13%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 403       | 3.47%   |
| Nvidia MCP79 High Definition Audio                                                                | 380       | 3.27%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 376       | 3.24%   |
| Intel Broadwell-U Audio Controller                                                                | 367       | 3.16%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 362       | 3.11%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 267       | 2.3%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 266       | 2.29%   |
| Intel 8 Series HD Audio Controller                                                                | 266       | 2.29%   |
| Intel Cannon Lake PCH cAVS                                                                        | 246       | 2.12%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 244       | 2.1%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 243       | 2.09%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 239       | 2.06%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 225       | 1.94%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 220       | 1.89%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 218       | 1.88%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 204       | 1.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 175       | 1.51%   |
| AMD FCH Azalia Controller                                                                         | 157       | 1.35%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 151       | 1.3%    |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 150       | 1.29%   |
| AMD Kabini HDMI/DP Audio                                                                          | 147       | 1.26%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 143       | 1.23%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 136       | 1.17%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 134       | 1.15%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 129       | 1.11%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 128       | 1.1%    |
| Intel Comet Lake PCH cAVS                                                                         | 127       | 1.09%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 118       | 1.02%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 92        | 0.79%   |
| Intel CM238 HD Audio Controller                                                                   | 85        | 0.73%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 85        | 0.73%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 84        | 0.72%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 80        | 0.69%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 79        | 0.68%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 70        | 0.6%    |
| AMD High Definition Audio Controller                                                              | 69        | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 2080      | 27.28%  |
| SK hynix            | 1934      | 25.37%  |
| Micron Technology   | 971       | 12.74%  |
| Kingston            | 532       | 6.98%   |
| Unknown             | 485       | 6.36%   |
| Crucial             | 379       | 4.97%   |
| Elpida              | 184       | 2.41%   |
| Ramaxel Technology  | 149       | 1.95%   |
| A-DATA Technology   | 143       | 1.88%   |
| Unknown             | 84        | 1.1%    |
| Nanya Technology    | 82        | 1.08%   |
| Corsair             | 77        | 1.01%   |
| Unknown (ABCD)      | 59        | 0.77%   |
| Smart               | 57        | 0.75%   |
| G.Skill             | 44        | 0.58%   |
| GOODRAM             | 30        | 0.39%   |
| Transcend           | 29        | 0.38%   |
| Team                | 29        | 0.38%   |
| 4ea5                | 18        | 0.24%   |
| Teikon              | 14        | 0.18%   |
| Timetec             | 13        | 0.17%   |
| Patriot             | 13        | 0.17%   |
| ff                  | 13        | 0.17%   |
| Silicon Power       | 12        | 0.16%   |
| ASint Technology    | 11        | 0.14%   |
| 48spaces            | 10        | 0.13%   |
| fef5                | 9         | 0.12%   |
| Apacer              | 9         | 0.12%   |
| Smart Brazil        | 8         | 0.1%    |
| Qimonda             | 7         | 0.09%   |
| AMD                 | 6         | 0.08%   |
| PNY                 | 5         | 0.07%   |
| Neo Forza           | 5         | 0.07%   |
| Wilk                | 4         | 0.05%   |
| Lexar Co Limited    | 4         | 0.05%   |
| Goldkey             | 4         | 0.05%   |
| TEXTORM             | 3         | 0.04%   |
| Shenzhen WODPOSIT   | 3         | 0.04%   |
| SHARETRONIC         | 3         | 0.04%   |
| PUSKILL             | 3         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM Module 1GB SODIMM DDR2 800MT/s                      | 266       | 3.32%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 84        | 1.05%   |
| Unknown                                                          | 84        | 1.05%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 81        | 1.01%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 3200MT/s            | 70        | 0.87%   |
| SK hynix RAM Module 1GB SODIMM DDR2 667MT/s                      | 68        | 0.85%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 68        | 0.85%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 66        | 0.82%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 65        | 0.81%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 64        | 0.8%    |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                      | 64        | 0.8%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 62        | 0.77%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 55        | 0.69%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 54        | 0.67%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 54        | 0.67%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 52        | 0.65%   |
| Crucial RAM CT8G4SFRA266.C8FD1 8GB SODIMM DDR4 2667MT/s          | 50        | 0.62%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 49        | 0.61%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 48        | 0.6%    |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 48        | 0.6%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 46        | 0.57%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 46        | 0.57%   |
| Samsung RAM K4E8E324EB-EGCF 2GB LPDDR3 1867MT/s                  | 46        | 0.57%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 45        | 0.56%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 45        | 0.56%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                       | 45        | 0.56%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 44        | 0.55%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 41        | 0.51%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 39        | 0.49%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 37        | 0.46%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 35        | 0.44%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 35        | 0.44%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 34        | 0.42%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 34        | 0.42%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 33        | 0.41%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 33        | 0.41%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 33        | 0.41%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 32        | 0.4%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 32        | 0.4%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 31        | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 2706      | 41.34%  |
| DDR3    | 2017      | 30.81%  |
| DDR2    | 693       | 10.59%  |
| LPDDR4  | 278       | 4.25%   |
| LPDDR3  | 244       | 3.73%   |
| DDR5    | 187       | 2.86%   |
| LPDDR5  | 183       | 2.8%    |
| SDRAM   | 122       | 1.86%   |
| DDR     | 58        | 0.89%   |
| Unknown | 41        | 0.63%   |
| DRAM    | 16        | 0.24%   |
| RAM     | 1         | 0.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| SODIMM          | 5776      | 87.97%  |
| Row Of Chips    | 582       | 8.86%   |
| Unknown         | 135       | 2.06%   |
| Chip            | 48        | 0.73%   |
| DIMM            | 24        | 0.37%   |
| Proprietary Car | 1         | 0.02%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Notebooks | Percent |
|---------|-----------|---------|
| 8192    | 2432      | 34.02%  |
| 4096    | 1779      | 24.88%  |
| 16384   | 992       | 13.88%  |
| 2048    | 977       | 13.67%  |
| 1024    | 649       | 9.08%   |
| 32768   | 229       | 3.2%    |
| 512     | 55        | 0.77%   |
| 256     | 20        | 0.28%   |
| 49152   | 5         | 0.07%   |
| 3072    | 3         | 0.04%   |
| 128     | 2         | 0.03%   |
| 65536   | 1         | 0.01%   |
| 8072    | 1         | 0.01%   |
| 5120    | 1         | 0.01%   |
| 1536    | 1         | 0.01%   |
| 384     | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 1410      | 20.2%   |
| 3200    | 1356      | 19.43%  |
| 2667    | 1105      | 15.83%  |
| 2400    | 450       | 6.45%   |
| 800     | 418       | 5.99%   |
| 2133    | 288       | 4.13%   |
| 1334    | 268       | 3.84%   |
| 667     | 228       | 3.27%   |
| 1333    | 201       | 2.88%   |
| Unknown | 161       | 2.31%   |
| 1867    | 123       | 1.76%   |
| 6400    | 117       | 1.68%   |
| 4800    | 99        | 1.42%   |
| 4267    | 95        | 1.36%   |
| 5600    | 92        | 1.32%   |
| 1067    | 90        | 1.29%   |
| 3266    | 68        | 0.97%   |
| 1066    | 48        | 0.69%   |
| 4199    | 44        | 0.63%   |
| 7500    | 41        | 0.59%   |
| 533     | 35        | 0.5%    |
| 2048    | 33        | 0.47%   |
| 4266    | 30        | 0.43%   |
| 975     | 30        | 0.43%   |
| 8400    | 21        | 0.3%    |
| 3733    | 18        | 0.26%   |
| 1596    | 17        | 0.24%   |
| 400     | 12        | 0.17%   |
| 7467    | 10        | 0.14%   |
| 333     | 10        | 0.14%   |
| 1866    | 9         | 0.13%   |
| 266     | 8         | 0.11%   |
| 2933    | 6         | 0.09%   |
| 2666    | 6         | 0.09%   |
| 8533    | 5         | 0.07%   |
| 5500    | 5         | 0.07%   |
| 1639    | 4         | 0.06%   |
| 933     | 3         | 0.04%   |
| 7400    | 2         | 0.03%   |
| 1776    | 2         | 0.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 22        | 40.74%  |
| Brother Industries    | 8         | 14.81%  |
| Canon                 | 7         | 12.96%  |
| Xerox                 | 4         | 7.41%   |
| Seiko Epson           | 3         | 5.56%   |
| Samsung Electronics   | 3         | 5.56%   |
| Kyocera               | 2         | 3.7%    |
| Xiaomi                | 1         | 1.85%   |
| STMicroelectronics    | 1         | 1.85%   |
| Pantum                | 1         | 1.85%   |
| Lexmark International | 1         | 1.85%   |
| Dymo-CoStar           | 1         | 1.85%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Xerox B205                                                | 4         | 7.14%   |
| HP OfficeJet 4650 series                                  | 2         | 3.57%   |
| HP LaserJet 1022                                          | 2         | 3.57%   |
| HP DeskJet 2700 series                                    | 2         | 3.57%   |
| Canon LiDE 400                                            | 2         | 3.57%   |
| Brother HL-L2340D series                                  | 2         | 3.57%   |
| Xiaomi MiMouse 2                                          | 1         | 1.79%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 1.79%   |
| Seiko Epson Printer                                       | 1         | 1.79%   |
| Seiko Epson L120 Series                                   | 1         | 1.79%   |
| Seiko Epson ET-2600 Series                                | 1         | 1.79%   |
| Samsung SCX-472x Series                                   | 1         | 1.79%   |
| Samsung ML-2010P Mono Laser Printer                       | 1         | 1.79%   |
| Samsung CLX-3300 Series                                   | 1         | 1.79%   |
| Pantum P2500W series                                      | 1         | 1.79%   |
| Lexmark International E260dn                              | 1         | 1.79%   |
| Kyocera FS-1120MFP                                        | 1         | 1.79%   |
| Kyocera ECOSYS P2335d                                     | 1         | 1.79%   |
| HP Printing Support                                       | 1         | 1.79%   |
| HP Officejet 4500 G510g-m                                 | 1         | 1.79%   |
| HP OfficeJet 3830 series                                  | 1         | 1.79%   |
| HP LaserJet P2055 series                                  | 1         | 1.79%   |
| HP LaserJet P1102                                         | 1         | 1.79%   |
| HP LaserJet P1005                                         | 1         | 1.79%   |
| HP LaserJet 1200                                          | 1         | 1.79%   |
| HP LaserJet 1160 series                                   | 1         | 1.79%   |
| HP LaserJet 1150                                          | 1         | 1.79%   |
| HP LaserJet 1020                                          | 1         | 1.79%   |
| HP LaserJet 1018                                          | 1         | 1.79%   |
| HP Ink Tank 110 series                                    | 1         | 1.79%   |
| HP HP LaserJet M14-M17                                    | 1         | 1.79%   |
| HP EWS UPD                                                | 1         | 1.79%   |
| HP DeskJet 2620 All-in-One Printer                        | 1         | 1.79%   |
| HP Deskjet 2540 series                                    | 1         | 1.79%   |
| HP DeskJet 2130 series                                    | 1         | 1.79%   |
| Dymo-CoStar DYMO XTL                                      | 1         | 1.79%   |
| Dymo-CoStar DYMO LabelWriter 4XL                          | 1         | 1.79%   |
| Canon PIXMA MX920 Series                                  | 1         | 1.79%   |
| Canon LBP3010/LBP3018/LBP3050                             | 1         | 1.79%   |
| Canon LBP2900                                             | 1         | 1.79%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Canon              | 9         | 45%     |
| Seiko Epson        | 6         | 30%     |
| Mustek Systems     | 2         | 10%     |
| Ultima Electronics | 1         | 5%      |
| Sagem              | 1         | 5%      |
| Hewlett-Packard    | 1         | 5%      |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 220                                                               | 3         | 15%     |
| Canon CanoScan LiDE 120                                                               | 2         | 10%     |
| Canon CanoScan LiDE 110                                                               | 2         | 10%     |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1         | 5%      |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]                                           | 1         | 5%      |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 1         | 5%      |
| Seiko Epson GT-9800F [Perfection 3200]                                                | 1         | 5%      |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                                         | 1         | 5%      |
| Seiko Epson GT-7700U [Perfection 1240U]                                               | 1         | 5%      |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]                                     | 1         | 5%      |
| Sagem 600dpi USB Scanner                                                              | 1         | 5%      |
| Mustek Systems SNAPSCAN e22                                                           | 1         | 5%      |
| Mustek Systems BearPaw 2400 CU Plus                                                   | 1         | 5%      |
| HP Scanjet 200                                                                        | 1         | 5%      |
| Canon CanoScan LIDE 25                                                                | 1         | 5%      |
| Canon CanoScan LiDE 210                                                               | 1         | 5%      |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1613      | 24.26%  |
| IMC Networks                           | 688       | 10.35%  |
| Bison Electronics                      | 559       | 8.41%   |
| Quanta                                 | 510       | 7.67%   |
| Realtek Semiconductor                  | 509       | 7.65%   |
| Microdia                               | 502       | 7.55%   |
| Sunplus Innovation Technology          | 347       | 5.22%   |
| Cheng Uei Precision Industry (Foxlink) | 214       | 3.22%   |
| Luxvisions Innotech Limited            | 195       | 2.93%   |
| Suyin                                  | 171       | 2.57%   |
| Syntek                                 | 168       | 2.53%   |
| Lite-On Technology                     | 168       | 2.53%   |
| Apple                                  | 125       | 1.88%   |
| Acer                                   | 108       | 1.62%   |
| Logitech                               | 86        | 1.29%   |
| Silicon Motion                         | 83        | 1.25%   |
| Sonix Technology                       | 67        | 1.01%   |
| Alcor Micro                            | 62        | 0.93%   |
| Lenovo                                 | 48        | 0.72%   |
| Ricoh                                  | 47        | 0.71%   |
| Z-Star Microelectronics                | 31        | 0.47%   |
| Samsung Electronics                    | 26        | 0.39%   |
| ShineTech                              | 23        | 0.35%   |
| Primax Electronics                     | 23        | 0.35%   |
| SunplusIT                              | 22        | 0.33%   |
| icSpring                               | 19        | 0.29%   |
| Importek                               | 18        | 0.27%   |
| ALi                                    | 16        | 0.24%   |
| Microsoft                              | 10        | 0.15%   |
| Unknown                                | 10        | 0.15%   |
| Shine-optics                           | 9         | 0.14%   |
| OmniVision Technologies                | 9         | 0.14%   |
| Generalplus Technology                 | 9         | 0.14%   |
| Genesys Logic                          | 8         | 0.12%   |
| Y Media                                | 7         | 0.11%   |
| MacroSilicon                           | 7         | 0.11%   |
| Intel                                  | 6         | 0.09%   |
| GEMBIRD                                | 6         | 0.09%   |
| kingcome                               | 5         | 0.08%   |
| DigiTech                               | 5         | 0.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 447       | 6.68%   |
| Microdia Integrated_Webcam_HD                       | 240       | 3.59%   |
| IMC Networks Integrated Camera                      | 231       | 3.45%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 185       | 2.77%   |
| Realtek Integrated_Webcam_HD                        | 181       | 2.71%   |
| Bison Integrated Camera                             | 171       | 2.56%   |
| Chicony HD WebCam                                   | 120       | 1.79%   |
| Sunplus Integrated_Webcam_HD                        | 112       | 1.67%   |
| Syntek Integrated Camera                            | 109       | 1.63%   |
| Chicony HP HD Camera                                | 104       | 1.55%   |
| Quanta Chromebook HD Camera                         | 103       | 1.54%   |
| Quanta HD User Facing                               | 76        | 1.14%   |
| Bison BisonCam, NB Pro                              | 67        | 1%      |
| Quanta HP TrueVision HD Camera                      | 63        | 0.94%   |
| Lite-On Integrated Camera                           | 63        | 0.94%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 61        | 0.91%   |
| Bison SunplusIT Integrated Camera                   | 58        | 0.87%   |
| Chicony USB2.0 HD UVC WebCam                        | 57        | 0.85%   |
| Chicony Integrated Camera (1280x720@30)             | 56        | 0.84%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 55        | 0.82%   |
| Chicony HP Truevision HD camera                     | 52        | 0.78%   |
| Microdia Integrated Webcam                          | 50        | 0.75%   |
| Quanta HP HD Camera                                 | 48        | 0.72%   |
| Bison HD Webcam                                     | 48        | 0.72%   |
| Lite-On HP HD Camera                                | 47        | 0.7%    |
| Bison Lenovo Integrated Webcam                      | 47        | 0.7%    |
| Chicony HD User Facing                              | 46        | 0.69%   |
| Sonix USB2.0 HD UVC WebCam                          | 45        | 0.67%   |
| Luxvisions Innotech Limited Integrated Camera       | 43        | 0.64%   |
| Sunplus HD WebCam                                   | 42        | 0.63%   |
| Chicony HP Truevision HD                            | 42        | 0.63%   |
| Apple Built-in iSight                               | 37        | 0.55%   |
| Realtek USB Camera                                  | 35        | 0.52%   |
| Realtek Integrated Webcam                           | 35        | 0.52%   |
| Quanta VGA WebCam                                   | 35        | 0.52%   |
| Bison Lenovo EasyCamera                             | 34        | 0.51%   |
| Chicony USB2.0 VGA UVC WebCam                       | 32        | 0.48%   |
| Chicony USB2.0 Camera                               | 32        | 0.48%   |
| Chicony USB 2.0 Camera                              | 32        | 0.48%   |
| Chicony Lenovo EasyCamera                           | 32        | 0.48%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 462       | 34.27%  |
| Validity Sensors                   | 426       | 31.6%   |
| Shenzhen Goodix Technology         | 168       | 12.46%  |
| AuthenTec                          | 75        | 5.56%   |
| Elan Microelectronics              | 74        | 5.49%   |
| Upek                               | 71        | 5.27%   |
| LighTuning Technology              | 35        | 2.6%    |
| STMicroelectronics                 | 22        | 1.63%   |
| Realtek USB2.0 Finger Print Bridge | 6         | 0.45%   |
| Focal-systems.Corp                 | 3         | 0.22%   |
| DigitalPersona                     | 2         | 0.15%   |
| Samsung Electronics                | 1         | 0.07%   |
| Microsoft                          | 1         | 0.07%   |
| HOLTEK                             | 1         | 0.07%   |
| GDMicroelectronics                 | 1         | 0.07%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 187       | 13.87%  |
| Shenzhen Goodix  FingerPrint Device                                        | 110       | 8.16%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 96        | 7.12%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 79        | 5.86%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 72        | 5.34%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 68        | 5.04%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 64        | 4.75%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 40        | 2.97%   |
| Validity Sensors Synaptics WBDI                                            | 39        | 2.89%   |
| Elan ELAN:ARM-M4                                                           | 39        | 2.89%   |
| Shenzhen Goodix Fingerprint Reader                                         | 30        | 2.23%   |
| AuthenTec AES2810                                                          | 30        | 2.23%   |
| Shenzhen Goodix FingerPrint                                                | 28        | 2.08%   |
| Synaptics Fingerprint reader [HP G6]                                       | 27        | 2%      |
| Elan ELAN:Fingerprint                                                      | 27        | 2%      |
| Synaptics UWP WBDI Device                                                  | 25        | 1.85%   |
| Synaptics Prometheus Fingerprint Reader                                    | 25        | 1.85%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 25        | 1.85%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 24        | 1.78%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 23        | 1.71%   |
| Validity Sensors VFS491                                                    | 20        | 1.48%   |
| STMicroelectronics Fingerprint Reader                                      | 20        | 1.48%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 20        | 1.48%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 19        | 1.41%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 19        | 1.41%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 16        | 1.19%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 15        | 1.11%   |
| Validity Sensors Fingerprint scanner                                       | 15        | 1.11%   |
| Validity Sensors VFS Fingerprint sensor                                    | 14        | 1.04%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 12        | 0.89%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 11        | 0.82%   |
| Synaptics  WBDI                                                            | 10        | 0.74%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 9         | 0.67%   |
| Synaptics WBDI                                                             | 8         | 0.59%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 8         | 0.59%   |
| Upek TCS5B Fingerprint sensor                                              | 7         | 0.52%   |
| Elan WBF Fingerprint Sensor                                                | 7         | 0.52%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 0.52%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 6         | 0.45%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 5         | 0.37%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 279       | 40.73%  |
| Alcor Micro               | 253       | 36.93%  |
| Upek                      | 44        | 6.42%   |
| O2 Micro                  | 42        | 6.13%   |
| Lenovo                    | 38        | 5.55%   |
| Yubico.com                | 6         | 0.88%   |
| Gemalto (was Gemplus)     | 5         | 0.73%   |
| SCM Microsystems          | 3         | 0.44%   |
| OmniKey                   | 3         | 0.44%   |
| Clay Logic                | 3         | 0.44%   |
| Advanced Card Systems     | 3         | 0.44%   |
| C3PO                      | 2         | 0.29%   |
| Aladdin Knowledge Systems | 2         | 0.29%   |
| Giesecke & Devrient       | 1         | 0.15%   |
| CHERRY                    | 1         | 0.15%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 250       | 36.5%   |
| Broadcom 58200                                                               | 79        | 11.53%  |
| Broadcom BCM5880 Secure Applications Processor                               | 77        | 11.24%  |
| Broadcom 5880                                                                | 71        | 10.36%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 49        | 7.15%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 44        | 6.42%   |
| Lenovo Integrated Smart Card Reader                                          | 37        | 5.4%    |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 35        | 5.11%   |
| O2 Micro Oz776 SmartCard Reader                                              | 7         | 1.02%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 5         | 0.73%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.44%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 3         | 0.44%   |
| Alcor Micro Watchdata W 1981                                                 | 3         | 0.44%   |
| OmniKey CardMan 4321                                                         | 2         | 0.29%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 0.29%   |
| Clay Logic Nitrokey Start                                                    | 2         | 0.29%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.29%   |
| Advanced Card Systems ACR39U                                                 | 2         | 0.29%   |
| Yubico.com Yubikey 4/5 CCID                                                  | 1         | 0.15%   |
| SCM Microsystems uTrust FIDO2 Security Key                                   | 1         | 0.15%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 0.15%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.15%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.15%   |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.15%   |
| Giesecke & Devrient StarSign CUT S                                           | 1         | 0.15%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.15%   |
| CHERRY SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.15%   |
| C3PO LTC31v2                                                                 | 1         | 0.15%   |
| C3PO KBR36                                                                   | 1         | 0.15%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.15%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 4679      | 56.35%  |
| 1     | 2703      | 32.55%  |
| 2     | 741       | 8.92%   |
| 3     | 140       | 1.69%   |
| 4     | 23        | 0.28%   |
| 5     | 13        | 0.16%   |
| 6     | 5         | 0.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 1335      | 29.37%  |
| Graphics card            | 1226      | 26.97%  |
| Chipcard                 | 619       | 13.62%  |
| Net/wireless             | 453       | 9.97%   |
| Multimedia controller    | 361       | 7.94%   |
| Camera                   | 143       | 3.15%   |
| Bluetooth                | 89        | 1.96%   |
| Card reader              | 70        | 1.54%   |
| Communication controller | 61        | 1.34%   |
| Storage                  | 56        | 1.23%   |
| Sound                    | 43        | 0.95%   |
| Net/ethernet             | 27        | 0.59%   |
| Modem                    | 22        | 0.48%   |
| Network                  | 13        | 0.29%   |
| Flash memory             | 10        | 0.22%   |
| Wireless                 | 4         | 0.09%   |
| Unassigned class         | 4         | 0.09%   |
| Storage/raid             | 4         | 0.09%   |
| Firewire controller      | 2         | 0.04%   |
| Tv card                  | 1         | 0.02%   |
| Storage/ide              | 1         | 0.02%   |
| Dvb card                 | 1         | 0.02%   |

