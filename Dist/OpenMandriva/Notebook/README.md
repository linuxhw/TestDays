OpenMandriva - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------

A project to collect tested hardware configurations for OpenMandriva.

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

Total: 8643

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron 3542               | [c7753ffa8e](https://linux-hardware.org/?probe=c7753ffa8e) | Feb 02, 2024 |
| Dell          | Latitude 7390               | [2386e8641f](https://linux-hardware.org/?probe=2386e8641f) | Feb 02, 2024 |
| Dell          | Inspiron 3442               | [ca29fa6852](https://linux-hardware.org/?probe=ca29fa6852) | Feb 02, 2024 |
| Dell          | Latitude 7400               | [ad51cec5ea](https://linux-hardware.org/?probe=ad51cec5ea) | Feb 02, 2024 |
| PC Special... | GK5CQ7Z                     | [d7632585fc](https://linux-hardware.org/?probe=d7632585fc) | Feb 02, 2024 |
| HP            | Laptop 17-cp0xxx            | [601c3c2cc4](https://linux-hardware.org/?probe=601c3c2cc4) | Feb 02, 2024 |
| Toshiba       | Satellite L50D-B            | [49e28cce05](https://linux-hardware.org/?probe=49e28cce05) | Feb 02, 2024 |
| Lenovo        | ThinkPad T580 20LAS3NJ0T    | [17e848cdcf](https://linux-hardware.org/?probe=17e848cdcf) | Feb 02, 2024 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [589322c92f](https://linux-hardware.org/?probe=589322c92f) | Feb 01, 2024 |
| ASUSTek       | UL80VT                      | [865619250b](https://linux-hardware.org/?probe=865619250b) | Feb 01, 2024 |
| ASUSTek       | X540YA                      | [4e8d90738d](https://linux-hardware.org/?probe=4e8d90738d) | Jan 31, 2024 |
| HP            | EliteBook 8440p             | [e8c221770b](https://linux-hardware.org/?probe=e8c221770b) | Jan 31, 2024 |
| Lenovo        | LOQ 15IRH8 82XV             | [33490eaaf1](https://linux-hardware.org/?probe=33490eaaf1) | Jan 31, 2024 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [3bba660f51](https://linux-hardware.org/?probe=3bba660f51) | Jan 31, 2024 |
| HUAWEI        | BOM-WXX9                    | [44970ca2bb](https://linux-hardware.org/?probe=44970ca2bb) | Jan 31, 2024 |
| Unknown       | X133                        | [a2fcc244e8](https://linux-hardware.org/?probe=a2fcc244e8) | Jan 31, 2024 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | [f37bfd54e7](https://linux-hardware.org/?probe=f37bfd54e7) | Jan 31, 2024 |
| Evolute       | B14HM21                     | [c5a911ad90](https://linux-hardware.org/?probe=c5a911ad90) | Jan 31, 2024 |
| Dell          | Inspiron N4050              | [9126475882](https://linux-hardware.org/?probe=9126475882) | Jan 31, 2024 |
| Packard Be... | EasyNote ENLG71BM           | [ab713b894e](https://linux-hardware.org/?probe=ab713b894e) | Jan 31, 2024 |
| HP            | G72                         | [24758020db](https://linux-hardware.org/?probe=24758020db) | Jan 31, 2024 |
| HP            | Presario C700               | [d309190dbb](https://linux-hardware.org/?probe=d309190dbb) | Jan 30, 2024 |
| MSI           | Bravo 15 B5DD               | [a989f7aa10](https://linux-hardware.org/?probe=a989f7aa10) | Jan 30, 2024 |
| HP            | Pavilion dv7                | [7899a3498e](https://linux-hardware.org/?probe=7899a3498e) | Jan 30, 2024 |
| HP            | 15 Notebook PC              | [fd6be31d9d](https://linux-hardware.org/?probe=fd6be31d9d) | Jan 30, 2024 |
| LG Electro... | E500-SP13G                  | [24499c2111](https://linux-hardware.org/?probe=24499c2111) | Jan 30, 2024 |
| Acer          | Nitro AN515-42              | [9e4c4acd0d](https://linux-hardware.org/?probe=9e4c4acd0d) | Jan 30, 2024 |
| HP            | EliteBook 8460p             | [9fd5ed9142](https://linux-hardware.org/?probe=9fd5ed9142) | Jan 30, 2024 |
| Toshiba       | Portable PC                 | [5c293a3c24](https://linux-hardware.org/?probe=5c293a3c24) | Jan 30, 2024 |
| Sony          | VPCF12A4E                   | [66fb5f96a0](https://linux-hardware.org/?probe=66fb5f96a0) | Jan 30, 2024 |
| Dell          | Latitude E6530              | [9aee5be7bf](https://linux-hardware.org/?probe=9aee5be7bf) | Jan 30, 2024 |
| HP            | 250 G7 Notebook PC          | [9dab8601c1](https://linux-hardware.org/?probe=9dab8601c1) | Jan 29, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [fbf917dbe4](https://linux-hardware.org/?probe=fbf917dbe4) | Jan 29, 2024 |
| Toshiba       | dynabook Satellite B552/... | [9c1f52e62f](https://linux-hardware.org/?probe=9c1f52e62f) | Jan 29, 2024 |
| Lenovo        | G510 20238                  | [12cf7dfeeb](https://linux-hardware.org/?probe=12cf7dfeeb) | Jan 29, 2024 |
| Compaq        | Presario CQ-21              | [b947b6f2b8](https://linux-hardware.org/?probe=b947b6f2b8) | Jan 29, 2024 |
| ARCELIK       | GNB 1150 B1 N2 V1.0         | [eb35406b7e](https://linux-hardware.org/?probe=eb35406b7e) | Jan 29, 2024 |
| Dell          | Latitude E7450              | [bfa71d26f4](https://linux-hardware.org/?probe=bfa71d26f4) | Jan 29, 2024 |
| Acer          | Aspire 5720Z                | [2353edc7dd](https://linux-hardware.org/?probe=2353edc7dd) | Jan 29, 2024 |
| HP            | Pavilion Laptop 15t-eg00... | [fd0435f25b](https://linux-hardware.org/?probe=fd0435f25b) | Jan 29, 2024 |
| Acer          | Aspire 5750                 | [f05ba6ae6f](https://linux-hardware.org/?probe=f05ba6ae6f) | Jan 29, 2024 |
| Positivo      | SF37405                     | [5955478d22](https://linux-hardware.org/?probe=5955478d22) | Jan 28, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [f20816d81d](https://linux-hardware.org/?probe=f20816d81d) | Jan 28, 2024 |
| Acer          | Aspire V5-471PG             | [621c9286da](https://linux-hardware.org/?probe=621c9286da) | Jan 28, 2024 |
| eMachines     | eME732ZG                    | [50446e8377](https://linux-hardware.org/?probe=50446e8377) | Jan 28, 2024 |
| Dell          | Latitude 3510               | [0be0a86c59](https://linux-hardware.org/?probe=0be0a86c59) | Jan 28, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [2f6021e243](https://linux-hardware.org/?probe=2f6021e243) | Jan 28, 2024 |
| Lenovo        | B51-80 80LM                 | [71d2badad4](https://linux-hardware.org/?probe=71d2badad4) | Jan 27, 2024 |
| HP            | 350 G2                      | [ad55cbfa8a](https://linux-hardware.org/?probe=ad55cbfa8a) | Jan 27, 2024 |
| Dell          | Inspiron N7010              | [21ed3bec20](https://linux-hardware.org/?probe=21ed3bec20) | Jan 27, 2024 |
| ASUSTek       | K53SJ                       | [e8479e3860](https://linux-hardware.org/?probe=e8479e3860) | Jan 27, 2024 |
| ASUSTek       | ROG Zephyrus M16 GU604VI... | [dd39831e6f](https://linux-hardware.org/?probe=dd39831e6f) | Jan 27, 2024 |
| Dell          | Inspiron 5555               | [2d1142a7c1](https://linux-hardware.org/?probe=2d1142a7c1) | Jan 27, 2024 |
| Fujitsu Si... | LIFEBOOK S6410              | [e5e3cbdd02](https://linux-hardware.org/?probe=e5e3cbdd02) | Jan 26, 2024 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [01dd8556d5](https://linux-hardware.org/?probe=01dd8556d5) | Jan 26, 2024 |
| HP            | ProBook 455 G2              | [f8d011e007](https://linux-hardware.org/?probe=f8d011e007) | Jan 25, 2024 |
| Acer          | Aspire ES1-531              | [7faffb7f83](https://linux-hardware.org/?probe=7faffb7f83) | Jan 25, 2024 |
| HP            | Compaq 6730s                | [caa48b80fb](https://linux-hardware.org/?probe=caa48b80fb) | Jan 25, 2024 |
| Acer          | Aspire 5820TG               | [d36d7405c8](https://linux-hardware.org/?probe=d36d7405c8) | Jan 25, 2024 |
| ASUSTek       | X540NA                      | [de84955a53](https://linux-hardware.org/?probe=de84955a53) | Jan 25, 2024 |
| Acer          | Aspire ES1-572              | [10d96173cd](https://linux-hardware.org/?probe=10d96173cd) | Jan 25, 2024 |
| HP            | ProBook 445 G8 Notebook ... | [057c708875](https://linux-hardware.org/?probe=057c708875) | Jan 24, 2024 |
| HP            | EliteBook 840 G3            | [eceea6fa49](https://linux-hardware.org/?probe=eceea6fa49) | Jan 24, 2024 |
| eMachines     | eME732Z                     | [fe3d184f11](https://linux-hardware.org/?probe=fe3d184f11) | Jan 24, 2024 |
| HP            | EliteBook 2570p             | [34093d035a](https://linux-hardware.org/?probe=34093d035a) | Jan 24, 2024 |
| Toshiba       | Satellite C650              | [2fa418e377](https://linux-hardware.org/?probe=2fa418e377) | Jan 24, 2024 |
| Dell          | Inspiron 14-3452            | [0ed9a65fc4](https://linux-hardware.org/?probe=0ed9a65fc4) | Jan 23, 2024 |
| Apple         | MacBookPro4,1               | [4c99b7a6ff](https://linux-hardware.org/?probe=4c99b7a6ff) | Jan 23, 2024 |
| HP            | Stream Laptop 14-ax0XX      | [16c6b944fb](https://linux-hardware.org/?probe=16c6b944fb) | Jan 23, 2024 |
| HP            | Compaq CQ45                 | [4ab36cf29f](https://linux-hardware.org/?probe=4ab36cf29f) | Jan 23, 2024 |
| Positivo      | Mobile                      | [d1ca90b4f5](https://linux-hardware.org/?probe=d1ca90b4f5) | Jan 23, 2024 |
| Dell          | Latitude E5540              | [2e1716a6aa](https://linux-hardware.org/?probe=2e1716a6aa) | Jan 22, 2024 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [a19e1e70ac](https://linux-hardware.org/?probe=a19e1e70ac) | Jan 22, 2024 |
| Lenovo        | ThinkPad T430 2347A81       | [7209687602](https://linux-hardware.org/?probe=7209687602) | Jan 22, 2024 |
| Lenovo        | ThinkPad T490 20N3S5GM00    | [1562510db8](https://linux-hardware.org/?probe=1562510db8) | Jan 22, 2024 |
| ASUSTek       | S400CA                      | [87f5dfadc9](https://linux-hardware.org/?probe=87f5dfadc9) | Jan 22, 2024 |
| Hampoo        | I2W6_AP135 Reserved         | [fe5025efdd](https://linux-hardware.org/?probe=fe5025efdd) | Jan 21, 2024 |
| Lenovo        | ThinkPad X220 Tablet 429... | [8621eed350](https://linux-hardware.org/?probe=8621eed350) | Jan 21, 2024 |
| HP            | ProBook 450 G5              | [ea8cc27b1a](https://linux-hardware.org/?probe=ea8cc27b1a) | Jan 21, 2024 |
| Fujitsu       | LIFEBOOK A555/G             | [f87640231d](https://linux-hardware.org/?probe=f87640231d) | Jan 21, 2024 |
| Samsung       | X420/X520                   | [9dae8bd2c2](https://linux-hardware.org/?probe=9dae8bd2c2) | Jan 21, 2024 |
| HP            | EliteBook 8770w             | [6b53fccf5d](https://linux-hardware.org/?probe=6b53fccf5d) | Jan 21, 2024 |
| Lenovo        | ThinkPad T400 6474W7T       | [fa80320d7c](https://linux-hardware.org/?probe=fa80320d7c) | Jan 21, 2024 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | [e8a23ca7a0](https://linux-hardware.org/?probe=e8a23ca7a0) | Jan 20, 2024 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [af044c261f](https://linux-hardware.org/?probe=af044c261f) | Jan 20, 2024 |
| Acer          | Aspire 1810T                | [068454b849](https://linux-hardware.org/?probe=068454b849) | Jan 20, 2024 |
| HP            | ProBook 430 G3              | [ed36d7cd8f](https://linux-hardware.org/?probe=ed36d7cd8f) | Jan 20, 2024 |
| HP            | Presario CQ43               | [ad1175a3a8](https://linux-hardware.org/?probe=ad1175a3a8) | Jan 20, 2024 |
| Apple         | MacBookPro3,1               | [057f8b6477](https://linux-hardware.org/?probe=057f8b6477) | Jan 20, 2024 |
| Dell          | Latitude E6420              | [b0d535026a](https://linux-hardware.org/?probe=b0d535026a) | Jan 19, 2024 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | [9d2dbd96a5](https://linux-hardware.org/?probe=9d2dbd96a5) | Jan 19, 2024 |
| Unknown       | Unknown                     | [8be7dd2df4](https://linux-hardware.org/?probe=8be7dd2df4) | Jan 19, 2024 |
| Google        | Garg                        | [b0e91d1473](https://linux-hardware.org/?probe=b0e91d1473) | Jan 19, 2024 |
| Google        | Garg                        | [2c85d92017](https://linux-hardware.org/?probe=2c85d92017) | Jan 19, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [e4d77bb448](https://linux-hardware.org/?probe=e4d77bb448) | Jan 19, 2024 |
| Lenovo        | 100e 2nd Gen 81M8           | [a4aa40979a](https://linux-hardware.org/?probe=a4aa40979a) | Jan 18, 2024 |
| Google        | Garg                        | [69f2601b2d](https://linux-hardware.org/?probe=69f2601b2d) | Jan 18, 2024 |
| Acer          | Aspire E1-531G              | [2c64046f89](https://linux-hardware.org/?probe=2c64046f89) | Jan 17, 2024 |
| HP            | Laptop 15-dw3xxx            | [77766f1cc1](https://linux-hardware.org/?probe=77766f1cc1) | Jan 17, 2024 |
| Lenovo        | ThinkPad X230 2330A17       | [589c4362a6](https://linux-hardware.org/?probe=589c4362a6) | Jan 16, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [f73401456d](https://linux-hardware.org/?probe=f73401456d) | Jan 16, 2024 |
| ASUSTek       | X555LAB                     | [a5e1ffbe3f](https://linux-hardware.org/?probe=a5e1ffbe3f) | Jan 15, 2024 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | [22802134b7](https://linux-hardware.org/?probe=22802134b7) | Jan 15, 2024 |
| Lenovo        | Yoga 300-11IBR 80M1         | [8bbf7916f3](https://linux-hardware.org/?probe=8bbf7916f3) | Jan 15, 2024 |
| Acer          | TravelMate 5335             | [fcdb840b24](https://linux-hardware.org/?probe=fcdb840b24) | Jan 15, 2024 |
| Dell          | XPS 15 9510                 | [55cbe62073](https://linux-hardware.org/?probe=55cbe62073) | Jan 15, 2024 |
| Lenovo        | ThinkPad T450s 20BWS05V0... | [fffdee8af3](https://linux-hardware.org/?probe=fffdee8af3) | Jan 15, 2024 |
| HP            | Laptop 15-db0xxx            | [cb2cda915a](https://linux-hardware.org/?probe=cb2cda915a) | Jan 15, 2024 |
| Dell          | Latitude E4310              | [a11f178faf](https://linux-hardware.org/?probe=a11f178faf) | Jan 14, 2024 |
| Lenovo        | G780 20138                  | [de9b5d4fe7](https://linux-hardware.org/?probe=de9b5d4fe7) | Jan 14, 2024 |
| Lenovo        | ThinkPad P15v Gen 1 20TR... | [3382b10d32](https://linux-hardware.org/?probe=3382b10d32) | Jan 14, 2024 |
| HP            | EliteBook 840 G2            | [33b3e5d03d](https://linux-hardware.org/?probe=33b3e5d03d) | Jan 14, 2024 |
| Samsung       | 300E5M/300E5L               | [23fdab96e1](https://linux-hardware.org/?probe=23fdab96e1) | Jan 13, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [f35fb9dd1c](https://linux-hardware.org/?probe=f35fb9dd1c) | Jan 13, 2024 |
| TUXEDO        | Book BM15 Gen10             | [dcb4b6ab6a](https://linux-hardware.org/?probe=dcb4b6ab6a) | Jan 13, 2024 |
| ASUSTek       | X756UXK                     | [16c3f8c205](https://linux-hardware.org/?probe=16c3f8c205) | Jan 13, 2024 |
| GPU Compan... | GWNR71517                   | [be58d576de](https://linux-hardware.org/?probe=be58d576de) | Jan 13, 2024 |
| Acer          | Aspire A315-31              | [22135f150d](https://linux-hardware.org/?probe=22135f150d) | Jan 12, 2024 |
| Lenovo        | ThinkPad L570 20J9S0KG00    | [6d03ee96b8](https://linux-hardware.org/?probe=6d03ee96b8) | Jan 12, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [272249651d](https://linux-hardware.org/?probe=272249651d) | Jan 11, 2024 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [02b9ba51a9](https://linux-hardware.org/?probe=02b9ba51a9) | Jan 11, 2024 |
| Dell          | Vostro 3401                 | [cd47812859](https://linux-hardware.org/?probe=cd47812859) | Jan 11, 2024 |
| Dell          | Inspiron 11-3168            | [f7763a1298](https://linux-hardware.org/?probe=f7763a1298) | Jan 10, 2024 |
| Lenovo        | IdeaPad Pro 5 14APH8 83A... | [47ca371fcb](https://linux-hardware.org/?probe=47ca371fcb) | Jan 10, 2024 |
| Lenovo        | ThinkPad T480 20L6S6KF00    | [5e3205ab0e](https://linux-hardware.org/?probe=5e3205ab0e) | Jan 10, 2024 |
| MSI           | GF63 Thin 10SC              | [d30a326b47](https://linux-hardware.org/?probe=d30a326b47) | Jan 10, 2024 |
| GPU Compan... | GWNR71517                   | [11b2e02998](https://linux-hardware.org/?probe=11b2e02998) | Jan 10, 2024 |
| Toshiba       | Satellite C660              | [34eaf45d7f](https://linux-hardware.org/?probe=34eaf45d7f) | Jan 09, 2024 |
| Acer          | Aspire E5-571               | [a9f2a0569a](https://linux-hardware.org/?probe=a9f2a0569a) | Jan 09, 2024 |
| Dell          | Inspiron 15 3515            | [1ca72e6562](https://linux-hardware.org/?probe=1ca72e6562) | Jan 09, 2024 |
| HP            | EliteBook 8560w             | [9ecce1ef57](https://linux-hardware.org/?probe=9ecce1ef57) | Jan 09, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [6921991670](https://linux-hardware.org/?probe=6921991670) | Jan 09, 2024 |
| Sony          | VGN-FZ31Z                   | [3df7d503da](https://linux-hardware.org/?probe=3df7d503da) | Jan 09, 2024 |
| Razer         | Book 13 - RZ09-0357         | [91bd06ba56](https://linux-hardware.org/?probe=91bd06ba56) | Jan 09, 2024 |
| HP            | Notebook                    | [ae9cfe9cc7](https://linux-hardware.org/?probe=ae9cfe9cc7) | Jan 09, 2024 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | [b0ac8e8208](https://linux-hardware.org/?probe=b0ac8e8208) | Jan 09, 2024 |
| HP            | 2000                        | [d23f668910](https://linux-hardware.org/?probe=d23f668910) | Jan 09, 2024 |
| Sony          | SVF1521A6EW                 | [37c4dd98f1](https://linux-hardware.org/?probe=37c4dd98f1) | Jan 09, 2024 |
| HP            | Compaq 610                  | [da1dd5ace4](https://linux-hardware.org/?probe=da1dd5ace4) | Jan 08, 2024 |
| LG Electro... | 15Z90RT-K.AD7AA1            | [be4ff0f44a](https://linux-hardware.org/?probe=be4ff0f44a) | Jan 08, 2024 |
| Dell          | Inspiron 3576               | [ff3dc4d39e](https://linux-hardware.org/?probe=ff3dc4d39e) | Jan 08, 2024 |
| Lenovo        | G710 20252                  | [ec645bc6c5](https://linux-hardware.org/?probe=ec645bc6c5) | Jan 08, 2024 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | [9d534bf283](https://linux-hardware.org/?probe=9d534bf283) | Jan 07, 2024 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [770f12c749](https://linux-hardware.org/?probe=770f12c749) | Jan 07, 2024 |
| Lenovo        | G50-70 20351                | [5f77e74f4c](https://linux-hardware.org/?probe=5f77e74f4c) | Jan 07, 2024 |
| HP            | 635                         | [29632bb08b](https://linux-hardware.org/?probe=29632bb08b) | Jan 07, 2024 |
| Lenovo        | ThinkPad T60 1951YCQ        | [b449df298d](https://linux-hardware.org/?probe=b449df298d) | Jan 07, 2024 |
| HP            | 250 G3                      | [259acacdb3](https://linux-hardware.org/?probe=259acacdb3) | Jan 06, 2024 |
| Acer          | Aspire 5830TG               | [9af8a1dfdb](https://linux-hardware.org/?probe=9af8a1dfdb) | Jan 06, 2024 |
| Dell          | Inspiron 5567               | [9e7374b8ef](https://linux-hardware.org/?probe=9e7374b8ef) | Jan 06, 2024 |
| Dell          | Inspiron 5515               | [6ff66dee9c](https://linux-hardware.org/?probe=6ff66dee9c) | Jan 06, 2024 |
| Toshiba       | Satellite L55D-B            | [e0358ccedc](https://linux-hardware.org/?probe=e0358ccedc) | Jan 06, 2024 |
| Acer          | Aspire ES1-572              | [6de42f8573](https://linux-hardware.org/?probe=6de42f8573) | Jan 06, 2024 |
| HP            | Compaq 6730s                | [1ad2b54c9d](https://linux-hardware.org/?probe=1ad2b54c9d) | Jan 05, 2024 |
| ASUSTek       | UL80VT                      | [7780af9eb5](https://linux-hardware.org/?probe=7780af9eb5) | Jan 05, 2024 |
| HP            | Stream 11 Pro G4 EE         | [1cfbb2a459](https://linux-hardware.org/?probe=1cfbb2a459) | Jan 05, 2024 |
| HP            | ENVY Notebook               | [8a2c65e297](https://linux-hardware.org/?probe=8a2c65e297) | Jan 05, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [0f339e4df3](https://linux-hardware.org/?probe=0f339e4df3) | Jan 05, 2024 |
| HP            | Pavilion 10 TS              | [cd7638b3d6](https://linux-hardware.org/?probe=cd7638b3d6) | Jan 05, 2024 |
| Dell          | Venue 11 Pro 5130           | [4b4853f647](https://linux-hardware.org/?probe=4b4853f647) | Jan 05, 2024 |
| Dell          | Latitude 7390               | [1e8c287eaa](https://linux-hardware.org/?probe=1e8c287eaa) | Jan 04, 2024 |
| Lenovo        | IdeaPad S540-15IWL 81NE     | [65ef79e8a1](https://linux-hardware.org/?probe=65ef79e8a1) | Jan 04, 2024 |
| HP            | ProBook 430 G2              | [2e71050736](https://linux-hardware.org/?probe=2e71050736) | Jan 04, 2024 |
| HP            | Presario CQ45               | [8a0a9f1dc0](https://linux-hardware.org/?probe=8a0a9f1dc0) | Jan 04, 2024 |
| Samsung       | RV411/RV511/E3511/S3511/... | [3557687358](https://linux-hardware.org/?probe=3557687358) | Jan 04, 2024 |
| Lenovo        | ThinkPad T480 20L5000BMX    | [23c30ee5a3](https://linux-hardware.org/?probe=23c30ee5a3) | Jan 03, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | [1755330be9](https://linux-hardware.org/?probe=1755330be9) | Jan 03, 2024 |
| Acer          | Extensa 5230                | [2c36e88ef4](https://linux-hardware.org/?probe=2c36e88ef4) | Jan 03, 2024 |
| HP            | Victus by Laptop 16-d0xx... | [442c8e3a83](https://linux-hardware.org/?probe=442c8e3a83) | Jan 03, 2024 |
| Lenovo        | B580 20144                  | [f062a8fd3a](https://linux-hardware.org/?probe=f062a8fd3a) | Jan 03, 2024 |
| Dell          | Precision 7710              | [a2b5f2de51](https://linux-hardware.org/?probe=a2b5f2de51) | Jan 02, 2024 |
| Acer          | Extensa 2540                | [0dd0c273c1](https://linux-hardware.org/?probe=0dd0c273c1) | Jan 02, 2024 |
| MSI           | Modern 14 B4MW              | [f1f1b527ce](https://linux-hardware.org/?probe=f1f1b527ce) | Jan 02, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [01650ef12d](https://linux-hardware.org/?probe=01650ef12d) | Jan 02, 2024 |
| Dell          | Inspiron 13-5368            | [811a112c63](https://linux-hardware.org/?probe=811a112c63) | Jan 02, 2024 |
| Gateway       | M-6307                      | [0936f4a650](https://linux-hardware.org/?probe=0936f4a650) | Jan 01, 2024 |
| Apple         | MacBookAir9,1               | [5a511e238e](https://linux-hardware.org/?probe=5a511e238e) | Jan 01, 2024 |
| ASUSTek       | X751LA                      | [089bb5bca9](https://linux-hardware.org/?probe=089bb5bca9) | Jan 01, 2024 |
| Dell          | Latitude E6220              | [11568cda87](https://linux-hardware.org/?probe=11568cda87) | Dec 31, 2023 |
| Dell          | Latitude E6500              | [8d7d1376fd](https://linux-hardware.org/?probe=8d7d1376fd) | Dec 31, 2023 |
| ASUSTek       | K53SC                       | [1f2ddea9fa](https://linux-hardware.org/?probe=1f2ddea9fa) | Dec 31, 2023 |
| Info Quest... | GTN1402 4-64                | [c363bd26ad](https://linux-hardware.org/?probe=c363bd26ad) | Dec 31, 2023 |
| Toshiba       | Satellite Pro C660          | [c3736ea548](https://linux-hardware.org/?probe=c3736ea548) | Dec 31, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [a4596b8ae1](https://linux-hardware.org/?probe=a4596b8ae1) | Dec 31, 2023 |
| Dell          | Latitude 7490               | [455ad2a6f1](https://linux-hardware.org/?probe=455ad2a6f1) | Dec 31, 2023 |
| Lenovo        | ThinkPad T430 2349SVA       | [1a897f9fbd](https://linux-hardware.org/?probe=1a897f9fbd) | Dec 31, 2023 |
| HP            | Pavilion g6                 | [6adc1110b8](https://linux-hardware.org/?probe=6adc1110b8) | Dec 30, 2023 |
| Apple         | MacBookAir9,1               | [25fea8aab5](https://linux-hardware.org/?probe=25fea8aab5) | Dec 30, 2023 |
| HP            | Compaq 610                  | [d0849e0580](https://linux-hardware.org/?probe=d0849e0580) | Dec 30, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [96662ed691](https://linux-hardware.org/?probe=96662ed691) | Dec 30, 2023 |
| Lenovo        | B560                        | [1f8cf50933](https://linux-hardware.org/?probe=1f8cf50933) | Dec 29, 2023 |
| Lenovo        | Yoga 2 11 20332             | [04bb236111](https://linux-hardware.org/?probe=04bb236111) | Dec 29, 2023 |
| HP            | Laptop 15-da0xxx            | [4e00c088e8](https://linux-hardware.org/?probe=4e00c088e8) | Dec 29, 2023 |
| Dell          | Precision M6400             | [7ea3fcf3ed](https://linux-hardware.org/?probe=7ea3fcf3ed) | Dec 29, 2023 |
| HP            | Pavilion dv6                | [9992f9523e](https://linux-hardware.org/?probe=9992f9523e) | Dec 29, 2023 |
| Notebook      | NS5x_NS7xAU                 | [d520b97118](https://linux-hardware.org/?probe=d520b97118) | Dec 29, 2023 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | [a86830ecd2](https://linux-hardware.org/?probe=a86830ecd2) | Dec 28, 2023 |
| Acer          | Swift SF314-56              | [d230832e06](https://linux-hardware.org/?probe=d230832e06) | Dec 28, 2023 |
| ASUSTek       | X750JB                      | [3c2f9bd15e](https://linux-hardware.org/?probe=3c2f9bd15e) | Dec 28, 2023 |
| Toshiba       | dynabook Satellite B552/... | [544ae58a40](https://linux-hardware.org/?probe=544ae58a40) | Dec 27, 2023 |
| Apple         | MacBookAir9,1               | [13a55dee9a](https://linux-hardware.org/?probe=13a55dee9a) | Dec 27, 2023 |
| Acer          | Aspire 5736Z                | [36f131247e](https://linux-hardware.org/?probe=36f131247e) | Dec 27, 2023 |
| Alienware     | 15 R4                       | [b0bc2ccb53](https://linux-hardware.org/?probe=b0bc2ccb53) | Dec 27, 2023 |
| Dell          | Inspiron 15 3515            | [6369debba7](https://linux-hardware.org/?probe=6369debba7) | Dec 26, 2023 |
| Kiano         | Elegance 14.2               | [9c32017999](https://linux-hardware.org/?probe=9c32017999) | Dec 26, 2023 |
| Lenovo        | ThinkPad P50 20EQS1MY00     | [a49698d49d](https://linux-hardware.org/?probe=a49698d49d) | Dec 26, 2023 |
| Lenovo        | ThinkPad T61 7663DL1        | [b01632df81](https://linux-hardware.org/?probe=b01632df81) | Dec 26, 2023 |
| HP            | Victus by Gaming Laptop ... | [081217d505](https://linux-hardware.org/?probe=081217d505) | Dec 26, 2023 |
| HP            | 15 Notebook PC              | [0b603c74cf](https://linux-hardware.org/?probe=0b603c74cf) | Dec 26, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [53e2517636](https://linux-hardware.org/?probe=53e2517636) | Dec 26, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [6233bad3b5](https://linux-hardware.org/?probe=6233bad3b5) | Dec 25, 2023 |
| Notebook      | P95_HR                      | [d7283146d3](https://linux-hardware.org/?probe=d7283146d3) | Dec 25, 2023 |
| Razer         | Blade Pro 17 (2019)         | [25b1af1536](https://linux-hardware.org/?probe=25b1af1536) | Dec 25, 2023 |
| ASUSTek       | K50AF                       | [88415099d0](https://linux-hardware.org/?probe=88415099d0) | Dec 25, 2023 |
| Lenovo        | ThinkPad T400 6474AV5       | [b98f0a2c09](https://linux-hardware.org/?probe=b98f0a2c09) | Dec 24, 2023 |
| Dell          | Inspiron 3521               | [a109a64bdd](https://linux-hardware.org/?probe=a109a64bdd) | Dec 24, 2023 |
| HP            | EliteBook 2530p             | [996611fcab](https://linux-hardware.org/?probe=996611fcab) | Dec 23, 2023 |
| Acer          | Extensa 2519                | [29bc812d6d](https://linux-hardware.org/?probe=29bc812d6d) | Dec 23, 2023 |
| Alienware     | m15 R7 AMD                  | [9d80128f05](https://linux-hardware.org/?probe=9d80128f05) | Dec 23, 2023 |
| ASUSTek       | X441BA                      | [04e5c55b92](https://linux-hardware.org/?probe=04e5c55b92) | Dec 23, 2023 |
| ASUSTek       | UL80VT                      | [5b04b67d44](https://linux-hardware.org/?probe=5b04b67d44) | Dec 23, 2023 |
| Lenovo        | G50-30 80G0                 | [45b0f5ae9a](https://linux-hardware.org/?probe=45b0f5ae9a) | Dec 23, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | [201d4ed37f](https://linux-hardware.org/?probe=201d4ed37f) | Dec 23, 2023 |
| HP            | EliteBook 840 G5            | [6406b552c4](https://linux-hardware.org/?probe=6406b552c4) | Dec 23, 2023 |
| Acer          | Aspire A515-45              | [acab7c340a](https://linux-hardware.org/?probe=acab7c340a) | Dec 22, 2023 |
| Dell          | Studio 1737                 | [a157d70ea2](https://linux-hardware.org/?probe=a157d70ea2) | Dec 22, 2023 |
| ASUSTek       | K50AF                       | [367c28d17a](https://linux-hardware.org/?probe=367c28d17a) | Dec 22, 2023 |
| Acer          | One 14 Z2-493               | [11215309a3](https://linux-hardware.org/?probe=11215309a3) | Dec 22, 2023 |
| Google        | Garg                        | [05bbd9f9f8](https://linux-hardware.org/?probe=05bbd9f9f8) | Dec 22, 2023 |
| Dell          | Latitude E6400              | [6e6d4fec11](https://linux-hardware.org/?probe=6e6d4fec11) | Dec 21, 2023 |
| Dell          | System Vostro 3750          | [aa1fb5d9a6](https://linux-hardware.org/?probe=aa1fb5d9a6) | Dec 21, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [030e411799](https://linux-hardware.org/?probe=030e411799) | Dec 21, 2023 |
| Google        | Garg                        | [fb4804bee9](https://linux-hardware.org/?probe=fb4804bee9) | Dec 21, 2023 |
| Google        | Garg                        | [d2558e0746](https://linux-hardware.org/?probe=d2558e0746) | Dec 21, 2023 |
| Dell          | Latitude E6320              | [a1e4b48d85](https://linux-hardware.org/?probe=a1e4b48d85) | Dec 20, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [664d34d04d](https://linux-hardware.org/?probe=664d34d04d) | Dec 20, 2023 |
| Lenovo        | ThinkPad T480 20L6S01W00    | [c38a7a8ad4](https://linux-hardware.org/?probe=c38a7a8ad4) | Dec 20, 2023 |
| Lenovo        | ThinkPad T420 4236DA4       | [1188c1619d](https://linux-hardware.org/?probe=1188c1619d) | Dec 20, 2023 |
| Google        | Garg                        | [0f05d3580a](https://linux-hardware.org/?probe=0f05d3580a) | Dec 20, 2023 |
| Dell          | Latitude E5510              | [e1edf60996](https://linux-hardware.org/?probe=e1edf60996) | Dec 20, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | [e3dded7dc3](https://linux-hardware.org/?probe=e3dded7dc3) | Dec 20, 2023 |
| Dell          | Latitude E6400              | [67d4d37a04](https://linux-hardware.org/?probe=67d4d37a04) | Dec 20, 2023 |
| Dell          | Inspiron 1750               | [508bf60ff7](https://linux-hardware.org/?probe=508bf60ff7) | Dec 20, 2023 |
| Medion        | E15415                      | [03ee2b7f5e](https://linux-hardware.org/?probe=03ee2b7f5e) | Dec 19, 2023 |
| Lenovo        | ThinkPad T590 20N5S44300    | [5a90e712d1](https://linux-hardware.org/?probe=5a90e712d1) | Dec 19, 2023 |
| Fujitsu       | FMVNF70W                    | [cbeca4d4e8](https://linux-hardware.org/?probe=cbeca4d4e8) | Dec 19, 2023 |
| ASUSTek       | 1011PX                      | [6046941a0a](https://linux-hardware.org/?probe=6046941a0a) | Dec 18, 2023 |
| Dell          | Inspiron 1545               | [fc8665de21](https://linux-hardware.org/?probe=fc8665de21) | Dec 18, 2023 |
| ASUSTek       | X550EA                      | [a874ac5799](https://linux-hardware.org/?probe=a874ac5799) | Dec 18, 2023 |
| Dell          | Precision 7530              | [6de510283f](https://linux-hardware.org/?probe=6de510283f) | Dec 18, 2023 |
| Samsung       | RV409/RV509/RV709           | [7f55b490b8](https://linux-hardware.org/?probe=7f55b490b8) | Dec 18, 2023 |
| ASUSTek       | K84L                        | [3e0ea1ca0a](https://linux-hardware.org/?probe=3e0ea1ca0a) | Dec 17, 2023 |
| Apple         | MacBookAir9,1               | [73f451cbe0](https://linux-hardware.org/?probe=73f451cbe0) | Dec 17, 2023 |
| ASUSTek       | K53SC                       | [4424929359](https://linux-hardware.org/?probe=4424929359) | Dec 17, 2023 |
| HP            | Pavilion 15                 | [8ea538629f](https://linux-hardware.org/?probe=8ea538629f) | Dec 17, 2023 |
| Fujitsu       | LIFEBOOK U727               | [dceda9b2a1](https://linux-hardware.org/?probe=dceda9b2a1) | Dec 17, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [ead7baed80](https://linux-hardware.org/?probe=ead7baed80) | Dec 17, 2023 |
| ASUSTek       | S550CB                      | [20c9c415c9](https://linux-hardware.org/?probe=20c9c415c9) | Dec 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [ae7d12ef06](https://linux-hardware.org/?probe=ae7d12ef06) | Dec 17, 2023 |
| Dell          | Latitude 5400               | [9ae128faf4](https://linux-hardware.org/?probe=9ae128faf4) | Dec 16, 2023 |
| ASUSTek       | K61IC                       | [1442626988](https://linux-hardware.org/?probe=1442626988) | Dec 16, 2023 |
| Dell          | Inspiron 15-3567            | [3907c9bfa3](https://linux-hardware.org/?probe=3907c9bfa3) | Dec 16, 2023 |
| Lenovo        | ThinkPad T430 2349QM6       | [398d3beb97](https://linux-hardware.org/?probe=398d3beb97) | Dec 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [d34cfca6c8](https://linux-hardware.org/?probe=d34cfca6c8) | Dec 16, 2023 |
| MSI           | Modern 15 B5M               | [893ff177b3](https://linux-hardware.org/?probe=893ff177b3) | Dec 16, 2023 |
| AWOW          | Unknown                     | [7061726896](https://linux-hardware.org/?probe=7061726896) | Dec 16, 2023 |
| Lenovo        | ThinkPad X260 20F5A0XWJP    | [7aede5c549](https://linux-hardware.org/?probe=7aede5c549) | Dec 16, 2023 |
| AZW           | GT-R                        | [205436106b](https://linux-hardware.org/?probe=205436106b) | Dec 16, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [49e930f611](https://linux-hardware.org/?probe=49e930f611) | Dec 16, 2023 |
| Dell          | Latitude E6430              | [4a12bf0db8](https://linux-hardware.org/?probe=4a12bf0db8) | Dec 16, 2023 |
| Toshiba       | T20                         | [5bb395790c](https://linux-hardware.org/?probe=5bb395790c) | Dec 16, 2023 |
| Dell          | Precision 7510              | [c70e7da2e8](https://linux-hardware.org/?probe=c70e7da2e8) | Dec 16, 2023 |
| ASUSTek       | K50AF                       | [2d4a3c6859](https://linux-hardware.org/?probe=2d4a3c6859) | Dec 16, 2023 |
| Dell          | Latitude E7240              | [8fc0b7d8ea](https://linux-hardware.org/?probe=8fc0b7d8ea) | Dec 16, 2023 |
| Dell          | Latitude E5410              | [ee4251c01c](https://linux-hardware.org/?probe=ee4251c01c) | Dec 15, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [09be79a2d5](https://linux-hardware.org/?probe=09be79a2d5) | Dec 15, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [e03062f53d](https://linux-hardware.org/?probe=e03062f53d) | Dec 15, 2023 |
| Toshiba       | Satellite C70D-A            | [88b5dab876](https://linux-hardware.org/?probe=88b5dab876) | Dec 15, 2023 |
| Lenovo        | ThinkPad L330 34701V0       | [d418989434](https://linux-hardware.org/?probe=d418989434) | Dec 15, 2023 |
| Dell          | Inspiron 1525               | [b9daaa5978](https://linux-hardware.org/?probe=b9daaa5978) | Dec 15, 2023 |
| MSI           | GT70 2OC/2OD                | [22910f80b0](https://linux-hardware.org/?probe=22910f80b0) | Dec 14, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [51e42890da](https://linux-hardware.org/?probe=51e42890da) | Dec 14, 2023 |
| Medion        | E16401                      | [0c81bbcb2b](https://linux-hardware.org/?probe=0c81bbcb2b) | Dec 14, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | [8374878f6a](https://linux-hardware.org/?probe=8374878f6a) | Dec 14, 2023 |
| GPD           | G1619-04                    | [27dd6e79da](https://linux-hardware.org/?probe=27dd6e79da) | Dec 14, 2023 |
| Acer          | Nitro AN517-54              | [c16cb0947e](https://linux-hardware.org/?probe=c16cb0947e) | Dec 14, 2023 |
| HP            | Laptop 17-by4xxx            | [bb89121e0c](https://linux-hardware.org/?probe=bb89121e0c) | Dec 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [9227c29b16](https://linux-hardware.org/?probe=9227c29b16) | Dec 14, 2023 |
| Dell          | Latitude 5590               | [c52c1d4f2e](https://linux-hardware.org/?probe=c52c1d4f2e) | Dec 14, 2023 |
| Acer          | Aspire A315-22              | [e1deaf47e9](https://linux-hardware.org/?probe=e1deaf47e9) | Dec 14, 2023 |
| ASUSTek       | X550CA                      | [fe7ad66674](https://linux-hardware.org/?probe=fe7ad66674) | Dec 13, 2023 |
| Packard Be... | EasyNote LM85               | [18a9f48bee](https://linux-hardware.org/?probe=18a9f48bee) | Dec 13, 2023 |
| HP            | Pavilion dv6500             | [cdde8c0b3f](https://linux-hardware.org/?probe=cdde8c0b3f) | Dec 13, 2023 |
| HP            | Laptop 17-by4xxx            | [0c728e7b27](https://linux-hardware.org/?probe=0c728e7b27) | Dec 13, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [bd8707be32](https://linux-hardware.org/?probe=bd8707be32) | Dec 13, 2023 |
| Lenovo        | LOQ 15IRH8 82XV             | [ab468a9a14](https://linux-hardware.org/?probe=ab468a9a14) | Dec 13, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [5ec5788395](https://linux-hardware.org/?probe=5ec5788395) | Dec 13, 2023 |
| ASUSTek       | X55C                        | [13f3dbcb5f](https://linux-hardware.org/?probe=13f3dbcb5f) | Dec 13, 2023 |
| Dell          | Latitude E5470              | [cc7982deb0](https://linux-hardware.org/?probe=cc7982deb0) | Dec 13, 2023 |
| ASUSTek       | K50AF                       | [00e0b6dc86](https://linux-hardware.org/?probe=00e0b6dc86) | Dec 13, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [cc4a45597c](https://linux-hardware.org/?probe=cc4a45597c) | Dec 13, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [6407db19a5](https://linux-hardware.org/?probe=6407db19a5) | Dec 13, 2023 |
| Dell          | Inspiron 1501               | [c4103f9e5c](https://linux-hardware.org/?probe=c4103f9e5c) | Dec 13, 2023 |
| Fujitsu       | LIFEBOOK S792               | [811be0cce0](https://linux-hardware.org/?probe=811be0cce0) | Dec 13, 2023 |
| Acer          | Aspire 7740                 | [2122676b51](https://linux-hardware.org/?probe=2122676b51) | Dec 13, 2023 |
| MSI           | MS-16Y1                     | [41ce29bec7](https://linux-hardware.org/?probe=41ce29bec7) | Dec 12, 2023 |
| HP            | Laptop 15s-eq2xxx           | [8151ecbeef](https://linux-hardware.org/?probe=8151ecbeef) | Dec 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [4cffef33b7](https://linux-hardware.org/?probe=4cffef33b7) | Dec 12, 2023 |
| Sony          | SVE1713A1EW                 | [64b473222e](https://linux-hardware.org/?probe=64b473222e) | Dec 12, 2023 |
| HP            | Laptop 15s-eq0xxx           | [56e614b2fe](https://linux-hardware.org/?probe=56e614b2fe) | Dec 12, 2023 |
| Acer          | Aspire A517-51G             | [8396e4fdc5](https://linux-hardware.org/?probe=8396e4fdc5) | Dec 12, 2023 |
| Acer          | TravelMate 5720             | [27cbfe44c9](https://linux-hardware.org/?probe=27cbfe44c9) | Dec 12, 2023 |
| Dell          | Latitude E6320              | [dbacdcadba](https://linux-hardware.org/?probe=dbacdcadba) | Dec 12, 2023 |
| Acer          | Aspire E5-576               | [72fc5247a6](https://linux-hardware.org/?probe=72fc5247a6) | Dec 12, 2023 |
| HP            | EliteBook 840 G5            | [ee8ea2b093](https://linux-hardware.org/?probe=ee8ea2b093) | Dec 11, 2023 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | [6b350f2aaf](https://linux-hardware.org/?probe=6b350f2aaf) | Dec 11, 2023 |
| MouseCompu... | H116K                       | [0d2d3680f0](https://linux-hardware.org/?probe=0d2d3680f0) | Dec 11, 2023 |
| Lenovo        | B50-10 80QR                 | [f44fe4ce19](https://linux-hardware.org/?probe=f44fe4ce19) | Dec 11, 2023 |
| HP            | ProBook 450 G3              | [06651b08d9](https://linux-hardware.org/?probe=06651b08d9) | Dec 11, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [b9fbad0653](https://linux-hardware.org/?probe=b9fbad0653) | Dec 11, 2023 |
| HP            | Pavilion Sleekbook 15       | [baec95bb2f](https://linux-hardware.org/?probe=baec95bb2f) | Dec 11, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [9b5ac1a49b](https://linux-hardware.org/?probe=9b5ac1a49b) | Dec 11, 2023 |
| Acer          | Aspire E5-571G              | [30c8f1f622](https://linux-hardware.org/?probe=30c8f1f622) | Dec 11, 2023 |
| ASUSTek       | K54L                        | [a50a95f076](https://linux-hardware.org/?probe=a50a95f076) | Dec 11, 2023 |
| HP            | Presario CQ58               | [b23d694ab4](https://linux-hardware.org/?probe=b23d694ab4) | Dec 11, 2023 |
| Dell          | Latitude 5590               | [ebdbfc1740](https://linux-hardware.org/?probe=ebdbfc1740) | Dec 11, 2023 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | [be5332c927](https://linux-hardware.org/?probe=be5332c927) | Dec 11, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X1S... | [371f238337](https://linux-hardware.org/?probe=371f238337) | Dec 11, 2023 |
| Acer          | Aspire ES1-512              | [40438b3cd0](https://linux-hardware.org/?probe=40438b3cd0) | Dec 11, 2023 |
| HP            | ProBook 650 G2              | [96ea36be06](https://linux-hardware.org/?probe=96ea36be06) | Dec 10, 2023 |
| Acer          | Aspire 5750                 | [bedb502b74](https://linux-hardware.org/?probe=bedb502b74) | Dec 10, 2023 |
| Lenovo        | ThinkPad T410 2522V3S       | [7a6c259421](https://linux-hardware.org/?probe=7a6c259421) | Dec 10, 2023 |
| HP            | Laptop 14-bs0xx             | [f096c75cf9](https://linux-hardware.org/?probe=f096c75cf9) | Dec 10, 2023 |
| HP            | Notebook                    | [19c87ca6c5](https://linux-hardware.org/?probe=19c87ca6c5) | Dec 10, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | [1709e5c519](https://linux-hardware.org/?probe=1709e5c519) | Dec 10, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [9ae1729415](https://linux-hardware.org/?probe=9ae1729415) | Dec 10, 2023 |
| HP            | Laptop 15-da0xxx            | [a086fa3ad5](https://linux-hardware.org/?probe=a086fa3ad5) | Dec 10, 2023 |
| HP            | Laptop 15-bw0xx             | [69ebcd04b9](https://linux-hardware.org/?probe=69ebcd04b9) | Dec 10, 2023 |
| MSI           | Katana GF66 11UE            | [451c5731ae](https://linux-hardware.org/?probe=451c5731ae) | Dec 09, 2023 |
| HP            | G61                         | [ce104b5b73](https://linux-hardware.org/?probe=ce104b5b73) | Dec 09, 2023 |
| ASUSTek       | 1215B                       | [65223dfc53](https://linux-hardware.org/?probe=65223dfc53) | Dec 09, 2023 |
| Lenovo        | IdeaPad S145-15API 81UT     | [0d57f82fc5](https://linux-hardware.org/?probe=0d57f82fc5) | Dec 09, 2023 |
| HP            | Victus by Laptop 16-e1xx... | [9b973fc192](https://linux-hardware.org/?probe=9b973fc192) | Dec 08, 2023 |
| Dell          | Latitude 7490               | [13759c617a](https://linux-hardware.org/?probe=13759c617a) | Dec 08, 2023 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | [edabe3eb37](https://linux-hardware.org/?probe=edabe3eb37) | Dec 08, 2023 |
| MSI           | Modern 15 B12M              | [da95a095fa](https://linux-hardware.org/?probe=da95a095fa) | Dec 08, 2023 |
| HP            | ZBook 15v G5                | [96133249d0](https://linux-hardware.org/?probe=96133249d0) | Dec 08, 2023 |
| Adreamer      | Mybook PN1308P              | [e2dba2aff0](https://linux-hardware.org/?probe=e2dba2aff0) | Dec 08, 2023 |
| Fujitsu       | LIFEBOOK E744               | [2b97f06319](https://linux-hardware.org/?probe=2b97f06319) | Dec 07, 2023 |
| Lenovo        | ThinkPad T430 23498Y3       | [5382654b9b](https://linux-hardware.org/?probe=5382654b9b) | Dec 07, 2023 |
| Lenovo        | ThinkPad T440 20B7S0N10F    | [350da642e5](https://linux-hardware.org/?probe=350da642e5) | Dec 07, 2023 |
| Acer          | Aspire 7730G                | [c98f96bcc1](https://linux-hardware.org/?probe=c98f96bcc1) | Dec 07, 2023 |
| Dell          | Precision 3550              | [da173d0ccc](https://linux-hardware.org/?probe=da173d0ccc) | Dec 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [18d69df8d2](https://linux-hardware.org/?probe=18d69df8d2) | Dec 07, 2023 |
| HP            | ProBook 650 G1              | [52c0a2e6fa](https://linux-hardware.org/?probe=52c0a2e6fa) | Dec 07, 2023 |
| Acer          | TravelMate P645-S           | [e44f06b326](https://linux-hardware.org/?probe=e44f06b326) | Dec 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [3fce748548](https://linux-hardware.org/?probe=3fce748548) | Dec 06, 2023 |
| HP            | EliteBook 840 G1            | [923f26e8d8](https://linux-hardware.org/?probe=923f26e8d8) | Dec 06, 2023 |
| Dell          | Latitude 7350               | [3fb5b65dba](https://linux-hardware.org/?probe=3fb5b65dba) | Dec 06, 2023 |
| Lenovo        | Z51-70 80K6                 | [2894d2f78d](https://linux-hardware.org/?probe=2894d2f78d) | Dec 06, 2023 |
| Packard Be... | DOT S                       | [131c38200b](https://linux-hardware.org/?probe=131c38200b) | Dec 06, 2023 |
| Dell          | Latitude E7440              | [6b3c7ea2b5](https://linux-hardware.org/?probe=6b3c7ea2b5) | Dec 06, 2023 |
| Lenovo        | ThinkPad SL500 274678G      | [3cfa60a8bb](https://linux-hardware.org/?probe=3cfa60a8bb) | Dec 06, 2023 |
| Dell          | Latitude 3330               | [843751ec33](https://linux-hardware.org/?probe=843751ec33) | Dec 06, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [b62b670195](https://linux-hardware.org/?probe=b62b670195) | Dec 06, 2023 |
| Dell          | Latitude E5430 non-vPro     | [ee3494fa57](https://linux-hardware.org/?probe=ee3494fa57) | Dec 06, 2023 |
| Samsung       | R580/R590                   | [89f285aacc](https://linux-hardware.org/?probe=89f285aacc) | Dec 05, 2023 |
| ASUSTek       | N76VZ                       | [3d8844bc98](https://linux-hardware.org/?probe=3d8844bc98) | Dec 05, 2023 |
| HP            | ProBook 4540s               | [99c14e0650](https://linux-hardware.org/?probe=99c14e0650) | Dec 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [ac0fd4af39](https://linux-hardware.org/?probe=ac0fd4af39) | Dec 05, 2023 |
| Lenovo        | ThinkPad E15 20RD003KMH     | [d54efc5833](https://linux-hardware.org/?probe=d54efc5833) | Dec 05, 2023 |
| Apple         | MacBookPro11,3              | [b886333167](https://linux-hardware.org/?probe=b886333167) | Dec 05, 2023 |
| ASUSTek       | K53U                        | [b76cef4836](https://linux-hardware.org/?probe=b76cef4836) | Dec 05, 2023 |
| HP            | 15                          | [561269f586](https://linux-hardware.org/?probe=561269f586) | Dec 05, 2023 |
| Alurin        | Go Notebook                 | [197598d3dd](https://linux-hardware.org/?probe=197598d3dd) | Dec 05, 2023 |
| Toshiba       | Satellite L750              | [667c6d4e98](https://linux-hardware.org/?probe=667c6d4e98) | Dec 05, 2023 |
| Lenovo        | ThinkPad X230 23066RC       | [ef45ef93ac](https://linux-hardware.org/?probe=ef45ef93ac) | Dec 05, 2023 |
| Lenovo        | ThinkPad X390 20Q1S1WB00    | [ab1ae6521e](https://linux-hardware.org/?probe=ab1ae6521e) | Dec 05, 2023 |
| Acer          | TravelMate B311-31          | [9611377d0c](https://linux-hardware.org/?probe=9611377d0c) | Dec 05, 2023 |
| HP            | Laptop 15-dy2xxx            | [729837dc5c](https://linux-hardware.org/?probe=729837dc5c) | Dec 05, 2023 |
| Lenovo        | ThinkPad T480 20L6S3ED18    | [03866b12cd](https://linux-hardware.org/?probe=03866b12cd) | Dec 04, 2023 |
| HP            | Notebook                    | [4f0e8aad8c](https://linux-hardware.org/?probe=4f0e8aad8c) | Dec 04, 2023 |
| HP            | Compaq 6730b (NA373UC#AB... | [7e0d2ebaaf](https://linux-hardware.org/?probe=7e0d2ebaaf) | Dec 04, 2023 |
| ASUSTek       | X555LJ                      | [bd98f1df4c](https://linux-hardware.org/?probe=bd98f1df4c) | Dec 04, 2023 |
| HP            | ProBook 650 G1              | [b4b71ada44](https://linux-hardware.org/?probe=b4b71ada44) | Dec 04, 2023 |
| HP            | Pavilion 15                 | [15b5925773](https://linux-hardware.org/?probe=15b5925773) | Dec 04, 2023 |
| Lenovo        | V110-15IAP 80TG             | [ff40966f37](https://linux-hardware.org/?probe=ff40966f37) | Dec 04, 2023 |
| HP            | ProBook 4330s               | [48a060af86](https://linux-hardware.org/?probe=48a060af86) | Dec 04, 2023 |
| Lenovo        | ThinkPad L460 20FVS07C00    | [fd5a4dbeb9](https://linux-hardware.org/?probe=fd5a4dbeb9) | Dec 04, 2023 |
| Dell          | Inspiron MM061              | [0f629c5ee8](https://linux-hardware.org/?probe=0f629c5ee8) | Dec 04, 2023 |
| Samsung       | 550XDA                      | [b5bfe47576](https://linux-hardware.org/?probe=b5bfe47576) | Dec 04, 2023 |
| Lenovo        | B50-50 80S2                 | [6150907e1e](https://linux-hardware.org/?probe=6150907e1e) | Dec 04, 2023 |
| Dell          | XPS 13 9360                 | [73fa5936a1](https://linux-hardware.org/?probe=73fa5936a1) | Dec 04, 2023 |
| HP            | OMEN by Laptop 16-b1xxx     | [9acc9cef23](https://linux-hardware.org/?probe=9acc9cef23) | Dec 04, 2023 |
| Toshiba       | Satellite A300              | [5817017508](https://linux-hardware.org/?probe=5817017508) | Dec 04, 2023 |
| Dell          | XPS 13 9350                 | [aec9f3cb3c](https://linux-hardware.org/?probe=aec9f3cb3c) | Dec 04, 2023 |
| Lenovo        | G40-30 80FY                 | [219f784b96](https://linux-hardware.org/?probe=219f784b96) | Dec 04, 2023 |
| Toshiba       | Satellite C855D             | [84e97d4578](https://linux-hardware.org/?probe=84e97d4578) | Dec 04, 2023 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [218e5c18f3](https://linux-hardware.org/?probe=218e5c18f3) | Dec 04, 2023 |
| HP            | ProBook 450 G0              | [80f6017066](https://linux-hardware.org/?probe=80f6017066) | Dec 04, 2023 |
| ASUSTek       | 1215N                       | [49eeb946c5](https://linux-hardware.org/?probe=49eeb946c5) | Dec 03, 2023 |
| HP            | ProBook 640 G1              | [287093ae53](https://linux-hardware.org/?probe=287093ae53) | Dec 03, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [9e1d0f5fdc](https://linux-hardware.org/?probe=9e1d0f5fdc) | Dec 03, 2023 |
| Dell          | Latitude D630               | [84a1008ee2](https://linux-hardware.org/?probe=84a1008ee2) | Dec 03, 2023 |
| ASUSTek       | K53SJ                       | [50979ecbd2](https://linux-hardware.org/?probe=50979ecbd2) | Dec 03, 2023 |
| Dell          | Latitude E6410              | [bae67b7a50](https://linux-hardware.org/?probe=bae67b7a50) | Dec 03, 2023 |
| HP            | EliteBook 2540p             | [3819853378](https://linux-hardware.org/?probe=3819853378) | Dec 03, 2023 |
| HP            | Laptop 15-ra0xx             | [5726a3acac](https://linux-hardware.org/?probe=5726a3acac) | Dec 03, 2023 |
| Dell          | System Inspiron N7110       | [f0df20f63f](https://linux-hardware.org/?probe=f0df20f63f) | Dec 03, 2023 |
| Gateway       | M-6812M                     | [008f6448dc](https://linux-hardware.org/?probe=008f6448dc) | Dec 03, 2023 |
| Packard Be... | EasyNote LS11HR             | [c3d34dfe3a](https://linux-hardware.org/?probe=c3d34dfe3a) | Dec 03, 2023 |
| HP            | ENVY m6                     | [3a3cde32ab](https://linux-hardware.org/?probe=3a3cde32ab) | Dec 03, 2023 |
| HP            | Laptop 17-by0xxx            | [d27ace68bb](https://linux-hardware.org/?probe=d27ace68bb) | Dec 03, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [e7c23bf6d5](https://linux-hardware.org/?probe=e7c23bf6d5) | Dec 03, 2023 |
| Medion        | E6214                       | [f5e38ac376](https://linux-hardware.org/?probe=f5e38ac376) | Dec 03, 2023 |
| HP            | ZBook 15 G2                 | [f60bc8a984](https://linux-hardware.org/?probe=f60bc8a984) | Dec 03, 2023 |
| Dell          | Inspiron 3542               | [793b594721](https://linux-hardware.org/?probe=793b594721) | Dec 03, 2023 |
| Acer          | Aspire 8951G                | [f98b449dba](https://linux-hardware.org/?probe=f98b449dba) | Dec 03, 2023 |
| Dell          | Inspiron 13-5378            | [0beeed51bc](https://linux-hardware.org/?probe=0beeed51bc) | Dec 03, 2023 |
| Lenovo        | ThinkPad T530 2429F37       | [7db847c98e](https://linux-hardware.org/?probe=7db847c98e) | Dec 03, 2023 |
| Packard Be... | EasyNote_MX52-B-702NCD      | [738fd6b777](https://linux-hardware.org/?probe=738fd6b777) | Dec 03, 2023 |
| Alienware     | 18                          | [e2dc3b99fc](https://linux-hardware.org/?probe=e2dc3b99fc) | Dec 02, 2023 |
| Sony          | SVP13215PLS                 | [6c360dc427](https://linux-hardware.org/?probe=6c360dc427) | Dec 02, 2023 |
| ASUSTek       | X550LD                      | [d6118da294](https://linux-hardware.org/?probe=d6118da294) | Dec 02, 2023 |
| Apple         | MacBookPro5,5               | [53e38cd006](https://linux-hardware.org/?probe=53e38cd006) | Dec 02, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [13816c1292](https://linux-hardware.org/?probe=13816c1292) | Dec 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [9d3a34c3da](https://linux-hardware.org/?probe=9d3a34c3da) | Dec 02, 2023 |
| ASUSTek       | F3E                         | [26a960dd12](https://linux-hardware.org/?probe=26a960dd12) | Dec 02, 2023 |
| Dell          | Precision 5520              | [aa1a1feefc](https://linux-hardware.org/?probe=aa1a1feefc) | Dec 02, 2023 |
| Dell          | Latitude E6510              | [0c49353fa5](https://linux-hardware.org/?probe=0c49353fa5) | Dec 02, 2023 |
| MSI           | Modern 14 B5M               | [c22637e524](https://linux-hardware.org/?probe=c22637e524) | Dec 02, 2023 |
| Toshiba       | Satellite C650D             | [704507bfd5](https://linux-hardware.org/?probe=704507bfd5) | Dec 02, 2023 |
| Dell          | Inspiron 7720               | [ec97e6b200](https://linux-hardware.org/?probe=ec97e6b200) | Dec 02, 2023 |
| ASUSTek       | S551LN                      | [1c843db61c](https://linux-hardware.org/?probe=1c843db61c) | Dec 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | [7ddcba051c](https://linux-hardware.org/?probe=7ddcba051c) | Dec 02, 2023 |
| Acer          | Aspire V3-772               | [622055b29a](https://linux-hardware.org/?probe=622055b29a) | Dec 02, 2023 |
| HP            | Pavilion g7                 | [5c596e9e4f](https://linux-hardware.org/?probe=5c596e9e4f) | Dec 02, 2023 |
| ASUSTek       | X441NA                      | [9a4c0266e8](https://linux-hardware.org/?probe=9a4c0266e8) | Dec 02, 2023 |
| Sony          | VJS153C11N                  | [eb8f061cb3](https://linux-hardware.org/?probe=eb8f061cb3) | Dec 02, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [f73d3f92cf](https://linux-hardware.org/?probe=f73d3f92cf) | Dec 02, 2023 |
| HP            | Compaq 6910p (GY174UP#AB... | [54f08c139f](https://linux-hardware.org/?probe=54f08c139f) | Dec 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [58a0ae4fcc](https://linux-hardware.org/?probe=58a0ae4fcc) | Dec 02, 2023 |
| Sony          | VPCS13S9E                   | [0cd7cfa9de](https://linux-hardware.org/?probe=0cd7cfa9de) | Dec 02, 2023 |
| Lenovo        | G585                        | [a62a35b461](https://linux-hardware.org/?probe=a62a35b461) | Dec 01, 2023 |
| HP            | Pavilion dv7                | [dc015f1023](https://linux-hardware.org/?probe=dc015f1023) | Dec 01, 2023 |
| Clevo         | W251ESQ/W270ESQ             | [8572803f38](https://linux-hardware.org/?probe=8572803f38) | Dec 01, 2023 |
| HP            | 240 G7                      | [ad50ca6a6e](https://linux-hardware.org/?probe=ad50ca6a6e) | Dec 01, 2023 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | [32a0e568cc](https://linux-hardware.org/?probe=32a0e568cc) | Dec 01, 2023 |
| Dell          | Inspiron 3558               | [6b97c68c9f](https://linux-hardware.org/?probe=6b97c68c9f) | Dec 01, 2023 |
| HP            | EliteBook 6930p             | [0fefa1b40e](https://linux-hardware.org/?probe=0fefa1b40e) | Dec 01, 2023 |
| Acer          | Aspire A317-51K             | [aa5652abe0](https://linux-hardware.org/?probe=aa5652abe0) | Dec 01, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [7eb86d01c5](https://linux-hardware.org/?probe=7eb86d01c5) | Dec 01, 2023 |
| Dell          | Inspiron 1545               | [7fbbf18938](https://linux-hardware.org/?probe=7fbbf18938) | Dec 01, 2023 |
| Lenovo        | ThinkPad T480s 20L7002CU... | [679acd4c7a](https://linux-hardware.org/?probe=679acd4c7a) | Dec 01, 2023 |
| Packard Be... | EasyNote LJ75               | [0f21e6cb39](https://linux-hardware.org/?probe=0f21e6cb39) | Dec 01, 2023 |
| Google        | Fleex                       | [4baac33893](https://linux-hardware.org/?probe=4baac33893) | Dec 01, 2023 |
| Samsung       | R530/R730                   | [cdda254219](https://linux-hardware.org/?probe=cdda254219) | Dec 01, 2023 |
| Lenovo        | ThinkPad T430 2349AK2       | [53a55a0da2](https://linux-hardware.org/?probe=53a55a0da2) | Dec 01, 2023 |
| Acer          | Aspire 5732Z                | [f79a825fcd](https://linux-hardware.org/?probe=f79a825fcd) | Dec 01, 2023 |
| Dell          | Latitude E5410              | [074e7de8d8](https://linux-hardware.org/?probe=074e7de8d8) | Dec 01, 2023 |
| Acer          | Aspire A114-31              | [1eb938404f](https://linux-hardware.org/?probe=1eb938404f) | Dec 01, 2023 |
| Multilaser    | PC31X                       | [1f63edb2f9](https://linux-hardware.org/?probe=1f63edb2f9) | Dec 01, 2023 |
| Acer          | Aspire E5-773G              | [9ca60df165](https://linux-hardware.org/?probe=9ca60df165) | Dec 01, 2023 |
| Dell          | Inspiron 13-5368            | [ab8935b499](https://linux-hardware.org/?probe=ab8935b499) | Dec 01, 2023 |
| HP            | Laptop 14-ck0xxx            | [40a0a394cc](https://linux-hardware.org/?probe=40a0a394cc) | Dec 01, 2023 |
| Dell          | Inspiron 5558               | [49c6f0b57f](https://linux-hardware.org/?probe=49c6f0b57f) | Dec 01, 2023 |
| Apple         | MacBookPro8,1               | [ad16e37b50](https://linux-hardware.org/?probe=ad16e37b50) | Dec 01, 2023 |
| Dell          | Latitude E6440              | [4459a634ca](https://linux-hardware.org/?probe=4459a634ca) | Dec 01, 2023 |
| Acer          | Aspire 5750G                | [327582fb65](https://linux-hardware.org/?probe=327582fb65) | Dec 01, 2023 |
| Toshiba       | Satellite L755              | [511b79d4dc](https://linux-hardware.org/?probe=511b79d4dc) | Nov 30, 2023 |
| ASUSTek       | ASUS EXPERTBOOK L1500CDA... | [8524905e3f](https://linux-hardware.org/?probe=8524905e3f) | Nov 30, 2023 |
| Dell          | Inspiron 15 3515            | [162854d649](https://linux-hardware.org/?probe=162854d649) | Nov 30, 2023 |
| Apple         | MacBookPro12,1              | [d956dae97a](https://linux-hardware.org/?probe=d956dae97a) | Nov 30, 2023 |
| Acer          | Aspire V5-591G              | [fcb901f377](https://linux-hardware.org/?probe=fcb901f377) | Nov 30, 2023 |
| Acer          | Aspire A315-35              | [dad806dd8b](https://linux-hardware.org/?probe=dad806dd8b) | Nov 30, 2023 |
| Toshiba       | dynabook T552/36HR          | [1e3171aa0a](https://linux-hardware.org/?probe=1e3171aa0a) | Nov 30, 2023 |
| HP            | Compaq CQ58                 | [d50dd381c3](https://linux-hardware.org/?probe=d50dd381c3) | Nov 30, 2023 |
| Toshiba       | Satellite C660              | [03de11e5b3](https://linux-hardware.org/?probe=03de11e5b3) | Nov 30, 2023 |
| Dell          | Latitude E6420              | [12b36e0bb9](https://linux-hardware.org/?probe=12b36e0bb9) | Nov 30, 2023 |
| Toshiba       | Satellite C850-19D          | [cd9dbac72b](https://linux-hardware.org/?probe=cd9dbac72b) | Nov 30, 2023 |
| HP            | Laptop 15-bs1xx             | [e8f82bc03f](https://linux-hardware.org/?probe=e8f82bc03f) | Nov 29, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [b682c56733](https://linux-hardware.org/?probe=b682c56733) | Nov 29, 2023 |
| Teclast       | F15S                        | [34392dd87e](https://linux-hardware.org/?probe=34392dd87e) | Nov 29, 2023 |
| eMachines     | eME440                      | [a622dddd66](https://linux-hardware.org/?probe=a622dddd66) | Nov 29, 2023 |
| HUAWEI        | NbDE-WXX9                   | [8fc5d22e76](https://linux-hardware.org/?probe=8fc5d22e76) | Nov 29, 2023 |
| HP            | 250 G7 Notebook PC          | [395fbd2b48](https://linux-hardware.org/?probe=395fbd2b48) | Nov 29, 2023 |
| ASUSTek       | GL702VM                     | [0f104614aa](https://linux-hardware.org/?probe=0f104614aa) | Nov 29, 2023 |
| HP            | Laptop 17-by3xxx            | [63860f689c](https://linux-hardware.org/?probe=63860f689c) | Nov 29, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [685ce27fae](https://linux-hardware.org/?probe=685ce27fae) | Nov 29, 2023 |
| TUXEDO        | Book BA1510                 | [0c59322d62](https://linux-hardware.org/?probe=0c59322d62) | Nov 29, 2023 |
| Lenovo        | ThinkPad W530 24412S6       | [35077333e3](https://linux-hardware.org/?probe=35077333e3) | Nov 29, 2023 |
| HP            | Laptop 14s-fq0xxx           | [cc31cdf621](https://linux-hardware.org/?probe=cc31cdf621) | Nov 29, 2023 |
| HUAWEI        | RLEF-XX                     | [9b8fabda07](https://linux-hardware.org/?probe=9b8fabda07) | Nov 29, 2023 |
| Acer          | TravelMate P614-51-G2       | [17c4552f25](https://linux-hardware.org/?probe=17c4552f25) | Nov 29, 2023 |
| Lenovo        | ThinkPad W530 244723G       | [30e3d22482](https://linux-hardware.org/?probe=30e3d22482) | Nov 29, 2023 |
| Lenovo        | ThinkPad X201 3323BSG       | [e0ad13d1e8](https://linux-hardware.org/?probe=e0ad13d1e8) | Nov 29, 2023 |
| Fujitsu       | FMVNS6HE                    | [df459431eb](https://linux-hardware.org/?probe=df459431eb) | Nov 29, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [066daf7cac](https://linux-hardware.org/?probe=066daf7cac) | Nov 29, 2023 |
| LG Electro... | 17Z90Q-K.AAC7U1             | [6af16f3cbb](https://linux-hardware.org/?probe=6af16f3cbb) | Nov 29, 2023 |
| ASUSTek       | X550CA                      | [8ed2e1621c](https://linux-hardware.org/?probe=8ed2e1621c) | Nov 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [7ca8c7adc5](https://linux-hardware.org/?probe=7ca8c7adc5) | Nov 29, 2023 |
| ASUSTek       | GL703VM                     | [262f681abe](https://linux-hardware.org/?probe=262f681abe) | Nov 29, 2023 |
| HP            | Compaq 6730s                | [ff2ae39e03](https://linux-hardware.org/?probe=ff2ae39e03) | Nov 29, 2023 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | [4948ddc4be](https://linux-hardware.org/?probe=4948ddc4be) | Nov 29, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | [16dda5c039](https://linux-hardware.org/?probe=16dda5c039) | Nov 29, 2023 |
| Lenovo        | ThinkPad R500 27148UG       | [546c56f7bb](https://linux-hardware.org/?probe=546c56f7bb) | Nov 28, 2023 |
| Fujitsu       | LIFEBOOK S762               | [a7b0f7fe30](https://linux-hardware.org/?probe=a7b0f7fe30) | Nov 28, 2023 |
| HP            | Compaq 610                  | [f0022a2c56](https://linux-hardware.org/?probe=f0022a2c56) | Nov 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [577a8fa908](https://linux-hardware.org/?probe=577a8fa908) | Nov 28, 2023 |
| Dell          | Inspiron 15 3515            | [20007eacdb](https://linux-hardware.org/?probe=20007eacdb) | Nov 28, 2023 |
| Dell          | Inspiron 15 3515            | [e41d34ea1c](https://linux-hardware.org/?probe=e41d34ea1c) | Nov 28, 2023 |
| Sony          | VPCEL1E1E                   | [9c88ceb0b0](https://linux-hardware.org/?probe=9c88ceb0b0) | Nov 28, 2023 |
| HP            | Laptop 15-bs0xx             | [beba27b952](https://linux-hardware.org/?probe=beba27b952) | Nov 28, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [11d4048dc9](https://linux-hardware.org/?probe=11d4048dc9) | Nov 28, 2023 |
| HP            | EliteBook 2170p             | [fe332ae4ef](https://linux-hardware.org/?probe=fe332ae4ef) | Nov 28, 2023 |
| Dell          | System Inspiron N7110       | [83375f1b7a](https://linux-hardware.org/?probe=83375f1b7a) | Nov 28, 2023 |
| Dell          | Latitude E5430 non-vPro     | [34f3153910](https://linux-hardware.org/?probe=34f3153910) | Nov 28, 2023 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [8c1777b379](https://linux-hardware.org/?probe=8c1777b379) | Nov 28, 2023 |
| HP            | Laptop 15-db1xxx            | [52a0c464fe](https://linux-hardware.org/?probe=52a0c464fe) | Nov 28, 2023 |
| MSI           | GE60 0NC\0ND                | [f1285ee8a7](https://linux-hardware.org/?probe=f1285ee8a7) | Nov 28, 2023 |
| Samsung       | RV413/RV513                 | [42fb4ae911](https://linux-hardware.org/?probe=42fb4ae911) | Nov 28, 2023 |
| Lenovo        | Unknown                     | [0324aeaf06](https://linux-hardware.org/?probe=0324aeaf06) | Nov 28, 2023 |
| Acer          | Aspire E5-521G              | [d639f77bd9](https://linux-hardware.org/?probe=d639f77bd9) | Nov 28, 2023 |
| Lenovo        | ThinkPad T540p 20BFS31F0... | [8db080dffe](https://linux-hardware.org/?probe=8db080dffe) | Nov 28, 2023 |
| Acer          | Aspire A315-57G             | [10678fbceb](https://linux-hardware.org/?probe=10678fbceb) | Nov 28, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [8c82a1d8c3](https://linux-hardware.org/?probe=8c82a1d8c3) | Nov 28, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | [160556d559](https://linux-hardware.org/?probe=160556d559) | Nov 28, 2023 |
| Google        | Fleex                       | [0f905372c0](https://linux-hardware.org/?probe=0f905372c0) | Nov 28, 2023 |
| HP            | Laptop 15-dy2xxx            | [c56c2fcff2](https://linux-hardware.org/?probe=c56c2fcff2) | Nov 28, 2023 |
| HUAWEI        | MACH-WX9                    | [a09dd535a7](https://linux-hardware.org/?probe=a09dd535a7) | Nov 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon 34603... | [edb57fe6c8](https://linux-hardware.org/?probe=edb57fe6c8) | Nov 28, 2023 |
| HP            | Pavilion Notebook           | [39dd843280](https://linux-hardware.org/?probe=39dd843280) | Nov 28, 2023 |
| Lenovo        | Legion Y9000P IAH7H 82RF    | [b3bea8127f](https://linux-hardware.org/?probe=b3bea8127f) | Nov 27, 2023 |
| Samsung       | RV411/RV511/E3511/S3511     | [36ecf595ab](https://linux-hardware.org/?probe=36ecf595ab) | Nov 27, 2023 |
| Acer          | Aspire 5740                 | [bad53e91fc](https://linux-hardware.org/?probe=bad53e91fc) | Nov 27, 2023 |
| HP            | Pavilion g7                 | [10f5b71d45](https://linux-hardware.org/?probe=10f5b71d45) | Nov 27, 2023 |
| Apple         | MacBookPro10,1              | [3982dc173a](https://linux-hardware.org/?probe=3982dc173a) | Nov 27, 2023 |
| Machcreato... | 14X                         | [25e406809e](https://linux-hardware.org/?probe=25e406809e) | Nov 27, 2023 |
| Clevo         | M720R                       | [cf202bc2be](https://linux-hardware.org/?probe=cf202bc2be) | Nov 27, 2023 |
| ASUSTek       | K73SD                       | [cd71879827](https://linux-hardware.org/?probe=cd71879827) | Nov 27, 2023 |
| Timi          | TM1701                      | [dfb21da820](https://linux-hardware.org/?probe=dfb21da820) | Nov 27, 2023 |
| Dynabook      | Satellite Pro C50-H-11G     | [438812dbd7](https://linux-hardware.org/?probe=438812dbd7) | Nov 27, 2023 |
| Dell          | Latitude 3350               | [395158b705](https://linux-hardware.org/?probe=395158b705) | Nov 27, 2023 |
| Dell          | Precision 7670              | [450a8674d6](https://linux-hardware.org/?probe=450a8674d6) | Nov 27, 2023 |
| MSI           | CR620                       | [336d403e1b](https://linux-hardware.org/?probe=336d403e1b) | Nov 27, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | [d36366cac6](https://linux-hardware.org/?probe=d36366cac6) | Nov 27, 2023 |
| Dell          | Inspiron 1012               | [ffe483f5fd](https://linux-hardware.org/?probe=ffe483f5fd) | Nov 27, 2023 |
| Dell          | Latitude E7470              | [7b07507b58](https://linux-hardware.org/?probe=7b07507b58) | Nov 27, 2023 |
| HP            | Laptop 17-cp0xxx            | [63ddfa6f43](https://linux-hardware.org/?probe=63ddfa6f43) | Nov 27, 2023 |
| Dell          | Precision M4500             | [044aca6d38](https://linux-hardware.org/?probe=044aca6d38) | Nov 27, 2023 |
| HP            | 250 G6 Notebook PC          | [936970029f](https://linux-hardware.org/?probe=936970029f) | Nov 27, 2023 |
| Dell          | Latitude 13                 | [bf50df43fa](https://linux-hardware.org/?probe=bf50df43fa) | Nov 27, 2023 |
| ASUSTek       | X540SC                      | [5a56e0886b](https://linux-hardware.org/?probe=5a56e0886b) | Nov 27, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [02f1616520](https://linux-hardware.org/?probe=02f1616520) | Nov 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [0ddcbc9eb9](https://linux-hardware.org/?probe=0ddcbc9eb9) | Nov 27, 2023 |
| Lenovo        | ThinkPad X250 20CLS0RK00    | [96642d7e8e](https://linux-hardware.org/?probe=96642d7e8e) | Nov 27, 2023 |
| Acer          | Aspire V3-771               | [7563ed582c](https://linux-hardware.org/?probe=7563ed582c) | Nov 27, 2023 |
| HP            | ProBook 430 G2              | [ebdc85d7a5](https://linux-hardware.org/?probe=ebdc85d7a5) | Nov 27, 2023 |
| Samsung       | 910S3L/911S3L               | [5356e7f33b](https://linux-hardware.org/?probe=5356e7f33b) | Nov 27, 2023 |
| Lenovo        | ThinkPad T520 4242AU2       | [71ffabfcb1](https://linux-hardware.org/?probe=71ffabfcb1) | Nov 27, 2023 |
| Acer          | Aspire A515-46              | [c3618a788c](https://linux-hardware.org/?probe=c3618a788c) | Nov 27, 2023 |
| Lenovo        | V340-17IWL 81RG             | [c2a7190ba8](https://linux-hardware.org/?probe=c2a7190ba8) | Nov 27, 2023 |
| SLIMBOOK      | PROX-AMD5                   | [be532e0503](https://linux-hardware.org/?probe=be532e0503) | Nov 27, 2023 |
| Packard Be... | EasyNote LJ75               | [ec3c8ef712](https://linux-hardware.org/?probe=ec3c8ef712) | Nov 26, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [cb6d17a69a](https://linux-hardware.org/?probe=cb6d17a69a) | Nov 26, 2023 |
| ASUSTek       | K52JB                       | [c314753a7c](https://linux-hardware.org/?probe=c314753a7c) | Nov 26, 2023 |
| HP            | 630                         | [cd7a4c040d](https://linux-hardware.org/?probe=cd7a4c040d) | Nov 26, 2023 |
| HP            | Pavilion dv7                | [940ce7b8ed](https://linux-hardware.org/?probe=940ce7b8ed) | Nov 26, 2023 |
| HP            | Compaq Presario CQ60        | [acd145c278](https://linux-hardware.org/?probe=acd145c278) | Nov 26, 2023 |
| Dell          | XPS 13 9300                 | [68ba1c0162](https://linux-hardware.org/?probe=68ba1c0162) | Nov 26, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [e552669069](https://linux-hardware.org/?probe=e552669069) | Nov 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [fdb42ffac6](https://linux-hardware.org/?probe=fdb42ffac6) | Nov 26, 2023 |
| HP            | ZBook 17 G2                 | [da3ac19523](https://linux-hardware.org/?probe=da3ac19523) | Nov 26, 2023 |
| ASUSTek       | ROG Strix G733ZW_G733ZW     | [21bc20e802](https://linux-hardware.org/?probe=21bc20e802) | Nov 26, 2023 |
| Philco        | 14H                         | [f4256fe390](https://linux-hardware.org/?probe=f4256fe390) | Nov 26, 2023 |
| Acer          | Aspire E5-774G              | [c9d2305459](https://linux-hardware.org/?probe=c9d2305459) | Nov 26, 2023 |
| Acer          | Swift SF514-56T             | [687fc34fd5](https://linux-hardware.org/?probe=687fc34fd5) | Nov 26, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [435a764eeb](https://linux-hardware.org/?probe=435a764eeb) | Nov 26, 2023 |
| Packard Be... | DOT S                       | [c42837d646](https://linux-hardware.org/?probe=c42837d646) | Nov 26, 2023 |
| HUAWEI        | CREM-WXX9                   | [ab6a5cd935](https://linux-hardware.org/?probe=ab6a5cd935) | Nov 26, 2023 |
| Dell          | Inspiron 5770               | [c35b932f41](https://linux-hardware.org/?probe=c35b932f41) | Nov 26, 2023 |
| Lenovo        | G580 20157                  | [f03f814b9c](https://linux-hardware.org/?probe=f03f814b9c) | Nov 26, 2023 |
| Lenovo        | G50-45 80E3                 | [6f475bfe64](https://linux-hardware.org/?probe=6f475bfe64) | Nov 26, 2023 |
| Dell          | Inspiron 3593               | [557aba57b5](https://linux-hardware.org/?probe=557aba57b5) | Nov 26, 2023 |
| Lenovo        | ThinkPad T15p Gen 1 20TM... | [c333f48b93](https://linux-hardware.org/?probe=c333f48b93) | Nov 26, 2023 |
| Chuwi         | GemiBook Plus               | [6316398e5b](https://linux-hardware.org/?probe=6316398e5b) | Nov 26, 2023 |
| ASUSTek       | X75VC                       | [be2ff8350a](https://linux-hardware.org/?probe=be2ff8350a) | Nov 26, 2023 |
| Lenovo        | ThinkPad Edge E325 12973... | [0f165c67ac](https://linux-hardware.org/?probe=0f165c67ac) | Nov 26, 2023 |
| HP            | EliteBook 8570p             | [f31c8412d9](https://linux-hardware.org/?probe=f31c8412d9) | Nov 26, 2023 |
| HP            | 255 G8 Notebook PC          | [f889c15ce7](https://linux-hardware.org/?probe=f889c15ce7) | Nov 26, 2023 |
| HP            | Pavilion dv6                | [2f757867e7](https://linux-hardware.org/?probe=2f757867e7) | Nov 26, 2023 |
| Acer          | Predator PH315-53           | [8139afea1a](https://linux-hardware.org/?probe=8139afea1a) | Nov 26, 2023 |
| Acer          | Aspire S5-371               | [d3efa32b61](https://linux-hardware.org/?probe=d3efa32b61) | Nov 26, 2023 |
| HP            | Laptop 14-dk1xxx            | [eb3634e98f](https://linux-hardware.org/?probe=eb3634e98f) | Nov 26, 2023 |
| Dell          | Precision 7520              | [26c0a80c45](https://linux-hardware.org/?probe=26c0a80c45) | Nov 26, 2023 |
| Unknown       | Unknown                     | [2b84a63677](https://linux-hardware.org/?probe=2b84a63677) | Nov 26, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [43e183bc2b](https://linux-hardware.org/?probe=43e183bc2b) | Nov 26, 2023 |
| Toshiba       | Satellite L855              | [420c85d7b3](https://linux-hardware.org/?probe=420c85d7b3) | Nov 26, 2023 |
| Lenovo        | IdeaPad Y580                | [c17c868d52](https://linux-hardware.org/?probe=c17c868d52) | Nov 26, 2023 |
| Acer          | Aspire S3-391               | [ee4eefb0d4](https://linux-hardware.org/?probe=ee4eefb0d4) | Nov 26, 2023 |
| Lenovo        | ThinkPad T450 20BUS20301    | [4d8f1df3d2](https://linux-hardware.org/?probe=4d8f1df3d2) | Nov 26, 2023 |
| MSI           | Stealth GS77 12UE           | [92c0eb2e6b](https://linux-hardware.org/?probe=92c0eb2e6b) | Nov 26, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [721fac0123](https://linux-hardware.org/?probe=721fac0123) | Nov 26, 2023 |
| Lenovo        | ThinkPad T490 20N3S4VV00    | [1106c092a2](https://linux-hardware.org/?probe=1106c092a2) | Nov 26, 2023 |
| Lenovo        | ThinkPad T440p 20AN0069U... | [79c8961819](https://linux-hardware.org/?probe=79c8961819) | Nov 26, 2023 |
| Dell          | Latitude 12 Rugged Table... | [012c390a1c](https://linux-hardware.org/?probe=012c390a1c) | Nov 26, 2023 |
| Toshiba       | Satellite L55t-A            | [b037dccb20](https://linux-hardware.org/?probe=b037dccb20) | Nov 25, 2023 |
| Lenovo        | ThinkPad X201 3680WFQ       | [3b6eaf2c6e](https://linux-hardware.org/?probe=3b6eaf2c6e) | Nov 25, 2023 |
| Dell          | Precision M6700             | [1817097d25](https://linux-hardware.org/?probe=1817097d25) | Nov 25, 2023 |
| Dell          | Latitude 5511               | [254abd404f](https://linux-hardware.org/?probe=254abd404f) | Nov 25, 2023 |
| Lenovo        | ThinkPad T420 4236Q23       | [3bfbdef979](https://linux-hardware.org/?probe=3bfbdef979) | Nov 25, 2023 |
| HP            | ProBook 5330m               | [74e3bacd14](https://linux-hardware.org/?probe=74e3bacd14) | Nov 25, 2023 |
| Acer          | Aspire A515-52G             | [5b0ff6d81a](https://linux-hardware.org/?probe=5b0ff6d81a) | Nov 25, 2023 |
| Alienware     | x14                         | [af501023a5](https://linux-hardware.org/?probe=af501023a5) | Nov 25, 2023 |
| Packard Be... | EasyNote TS11HR             | [cf23a5df5b](https://linux-hardware.org/?probe=cf23a5df5b) | Nov 25, 2023 |
| Dell          | Latitude E5540              | [29c4fc6485](https://linux-hardware.org/?probe=29c4fc6485) | Nov 25, 2023 |
| Lenovo        | Yoga 7 14ARP8 82YM          | [534d53e480](https://linux-hardware.org/?probe=534d53e480) | Nov 25, 2023 |
| HP            | Laptop 15z-ef3xxx           | [278b62313d](https://linux-hardware.org/?probe=278b62313d) | Nov 25, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [0c42791b33](https://linux-hardware.org/?probe=0c42791b33) | Nov 25, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [26cfb9b66d](https://linux-hardware.org/?probe=26cfb9b66d) | Nov 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [7478563980](https://linux-hardware.org/?probe=7478563980) | Nov 23, 2023 |
| HUAWEI        | KLVF-XX                     | [279b1557ed](https://linux-hardware.org/?probe=279b1557ed) | Nov 23, 2023 |
| Dell          | Latitude E6430              | [a7befe7f1b](https://linux-hardware.org/?probe=a7befe7f1b) | Nov 23, 2023 |
| ASUSTek       | UL80VT                      | [21f0f94735](https://linux-hardware.org/?probe=21f0f94735) | Nov 22, 2023 |
| Medion        | E14412                      | [3ba8cc6090](https://linux-hardware.org/?probe=3ba8cc6090) | Nov 22, 2023 |
| Lenovo        | G70-80 80FF                 | [c3acaa0cd4](https://linux-hardware.org/?probe=c3acaa0cd4) | Nov 22, 2023 |
| Fujitsu Si... | AMILO Pi 3625               | [e93688d366](https://linux-hardware.org/?probe=e93688d366) | Nov 22, 2023 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [2d0d992e3e](https://linux-hardware.org/?probe=2d0d992e3e) | Nov 22, 2023 |
| Lenovo        | ThinkPad T420 4180KHU       | [cb4a42ed82](https://linux-hardware.org/?probe=cb4a42ed82) | Nov 22, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | [af6326319c](https://linux-hardware.org/?probe=af6326319c) | Nov 21, 2023 |
| Lenovo        | ThinkPad T550 20CJS02E00    | [00e8b77882](https://linux-hardware.org/?probe=00e8b77882) | Nov 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [28af744237](https://linux-hardware.org/?probe=28af744237) | Nov 21, 2023 |
| Dell          | Vostro 15 5501              | [ebb962a4ff](https://linux-hardware.org/?probe=ebb962a4ff) | Nov 21, 2023 |
| Dell          | Latitude E6430              | [442654cab6](https://linux-hardware.org/?probe=442654cab6) | Nov 21, 2023 |
| Dell          | Latitude E6230              | [467d45ff38](https://linux-hardware.org/?probe=467d45ff38) | Nov 20, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [753bbb0ad2](https://linux-hardware.org/?probe=753bbb0ad2) | Nov 20, 2023 |
| Fujitsu       | LIFEBOOK S710               | [a0453d2f05](https://linux-hardware.org/?probe=a0453d2f05) | Nov 20, 2023 |
| Lenovo        | IdeaPad Y470 20090          | [ae2a0fceac](https://linux-hardware.org/?probe=ae2a0fceac) | Nov 20, 2023 |
| Acer          | Nitro AN515-51              | [ec5c91510c](https://linux-hardware.org/?probe=ec5c91510c) | Nov 20, 2023 |
| Acer          | Aspire 7535                 | [8316560129](https://linux-hardware.org/?probe=8316560129) | Nov 20, 2023 |
| Dell          | Latitude E5440              | [467d68239e](https://linux-hardware.org/?probe=467d68239e) | Nov 20, 2023 |
| HP            | EliteBook 8540p             | [35c40648e5](https://linux-hardware.org/?probe=35c40648e5) | Nov 20, 2023 |
| Digibras      | NH4CU53                     | [25fff3f773](https://linux-hardware.org/?probe=25fff3f773) | Nov 20, 2023 |
| Lenovo        | ThinkPad X230 23301H3       | [53976ca7f1](https://linux-hardware.org/?probe=53976ca7f1) | Nov 20, 2023 |
| HP            | EliteBook 840 G1            | [f2462919d4](https://linux-hardware.org/?probe=f2462919d4) | Nov 19, 2023 |
| Dell          | Vostro 1310                 | [bd82e2c035](https://linux-hardware.org/?probe=bd82e2c035) | Nov 19, 2023 |
| HP            | Pavilion g6                 | [5c6de74207](https://linux-hardware.org/?probe=5c6de74207) | Nov 19, 2023 |
| Juana Mans... | SF20GM7                     | [82c49fc608](https://linux-hardware.org/?probe=82c49fc608) | Nov 19, 2023 |
| ASUSTek       | G750JX                      | [94ad738290](https://linux-hardware.org/?probe=94ad738290) | Nov 18, 2023 |
| HP            | Compaq 6510b (GR680ET)      | [4d849ef131](https://linux-hardware.org/?probe=4d849ef131) | Nov 18, 2023 |
| Acer          | Aspire ES1-711              | [b7e85345bc](https://linux-hardware.org/?probe=b7e85345bc) | Nov 18, 2023 |
| Toshiba       | Satellite L300D             | [87222a31f3](https://linux-hardware.org/?probe=87222a31f3) | Nov 18, 2023 |
| Lenovo        | Unknown                     | [616a6584a4](https://linux-hardware.org/?probe=616a6584a4) | Nov 18, 2023 |
| AMI           | Intel                       | [d590688338](https://linux-hardware.org/?probe=d590688338) | Nov 18, 2023 |
| Dell          | Latitude 3189               | [915f8dc0af](https://linux-hardware.org/?probe=915f8dc0af) | Nov 18, 2023 |
| ASUSTek       | X540YA                      | [ffdc6b121c](https://linux-hardware.org/?probe=ffdc6b121c) | Nov 17, 2023 |
| Lenovo        | ThinkPad X201 3680DE3       | [38290dc3e7](https://linux-hardware.org/?probe=38290dc3e7) | Nov 17, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [fb9543ab29](https://linux-hardware.org/?probe=fb9543ab29) | Nov 17, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [029e25867a](https://linux-hardware.org/?probe=029e25867a) | Nov 17, 2023 |
| HP            | Laptop 15-ef3xxx            | [e20df9a48a](https://linux-hardware.org/?probe=e20df9a48a) | Nov 17, 2023 |
| Lenovo        | ThinkPad P52s 20LB0026US    | [bdee77c684](https://linux-hardware.org/?probe=bdee77c684) | Nov 17, 2023 |
| Sony          | VPCEB1J8E                   | [961e0e701d](https://linux-hardware.org/?probe=961e0e701d) | Nov 17, 2023 |
| ASUSTek       | M50Vn                       | [9c35898e36](https://linux-hardware.org/?probe=9c35898e36) | Nov 16, 2023 |
| HP            | Laptop 15-bs0xx             | [6d71a63b67](https://linux-hardware.org/?probe=6d71a63b67) | Nov 16, 2023 |
| ASUSTek       | TUF Gaming FX505GM_FX505... | [47427f60c0](https://linux-hardware.org/?probe=47427f60c0) | Nov 16, 2023 |
| ASUSTek       | X551MA                      | [96c7dc6aa1](https://linux-hardware.org/?probe=96c7dc6aa1) | Nov 16, 2023 |
| Samsung       | R430/R480/R440              | [0c90ddcfcf](https://linux-hardware.org/?probe=0c90ddcfcf) | Nov 15, 2023 |
| Apple         | MacBookAir3,1               | [e2eb5cacb7](https://linux-hardware.org/?probe=e2eb5cacb7) | Nov 15, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [d4c7bc8dc8](https://linux-hardware.org/?probe=d4c7bc8dc8) | Nov 15, 2023 |
| HP            | ENVY m7 Notebook            | [9246faa417](https://linux-hardware.org/?probe=9246faa417) | Nov 15, 2023 |
| Alienware     | 18                          | [129d60c7cc](https://linux-hardware.org/?probe=129d60c7cc) | Nov 15, 2023 |
| Acer          | TravelMate B118-M           | [25b9244c80](https://linux-hardware.org/?probe=25b9244c80) | Nov 15, 2023 |
| LG Electro... | 14Z90RS-K.AAW7U1            | [2921cb3437](https://linux-hardware.org/?probe=2921cb3437) | Nov 14, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAS... | [2521cc716f](https://linux-hardware.org/?probe=2521cc716f) | Nov 14, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAS... | [556cb2f633](https://linux-hardware.org/?probe=556cb2f633) | Nov 14, 2023 |
| HUAWEI        | NBD-WXX9                    | [3f2f4fcf8a](https://linux-hardware.org/?probe=3f2f4fcf8a) | Nov 13, 2023 |
| HP            | Pavilion g6                 | [8e95b24f18](https://linux-hardware.org/?probe=8e95b24f18) | Nov 13, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [613acc55d8](https://linux-hardware.org/?probe=613acc55d8) | Nov 13, 2023 |
| ASUSTek       | K45VM                       | [f307d97867](https://linux-hardware.org/?probe=f307d97867) | Nov 13, 2023 |
| Dell          | Latitude E7440              | [407afcc9d2](https://linux-hardware.org/?probe=407afcc9d2) | Nov 12, 2023 |
| Acer          | Aspire E5-573               | [c1b89d8187](https://linux-hardware.org/?probe=c1b89d8187) | Nov 12, 2023 |
| ASUSTek       | X540SAA                     | [1c5e9077a8](https://linux-hardware.org/?probe=1c5e9077a8) | Nov 12, 2023 |
| HP            | EliteBook 8440p             | [f3be98d9fc](https://linux-hardware.org/?probe=f3be98d9fc) | Nov 12, 2023 |
| Acer          | Aspire E5-511               | [689f2bca5b](https://linux-hardware.org/?probe=689f2bca5b) | Nov 11, 2023 |
| Acer          | Aspire 5715Z                | [532b575898](https://linux-hardware.org/?probe=532b575898) | Nov 11, 2023 |
| Philco        | 14H                         | [01ddcfeb9e](https://linux-hardware.org/?probe=01ddcfeb9e) | Nov 11, 2023 |
| Dynabook      | Satellite Pro C40-G-109     | [32a21ea7ad](https://linux-hardware.org/?probe=32a21ea7ad) | Nov 10, 2023 |
| ALLDOCUBE     | i1405C                      | [8f63b8af98](https://linux-hardware.org/?probe=8f63b8af98) | Nov 10, 2023 |
| Unknown       | Unknown                     | [820a8f3b76](https://linux-hardware.org/?probe=820a8f3b76) | Nov 10, 2023 |
| Lenovo        | IdeaPad 300-15IBR 80M3      | [1e2c26c06a](https://linux-hardware.org/?probe=1e2c26c06a) | Nov 09, 2023 |
| Exo           | Intel powered classmate ... | [135b2008b7](https://linux-hardware.org/?probe=135b2008b7) | Nov 09, 2023 |
| HP            | Compaq Presario CQ70        | [1c495f3402](https://linux-hardware.org/?probe=1c495f3402) | Nov 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [58e4e6690a](https://linux-hardware.org/?probe=58e4e6690a) | Nov 08, 2023 |
| HP            | ProBook 6470b               | [5b5177e5ed](https://linux-hardware.org/?probe=5b5177e5ed) | Nov 08, 2023 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [4b18a13143](https://linux-hardware.org/?probe=4b18a13143) | Nov 08, 2023 |
| HP            | Notebook                    | [e18c5aca5b](https://linux-hardware.org/?probe=e18c5aca5b) | Nov 07, 2023 |
| ASUSTek       | UL80VT                      | [25fe802d18](https://linux-hardware.org/?probe=25fe802d18) | Nov 06, 2023 |
| Acer          | Aspire ES1-512              | [4b43ed314b](https://linux-hardware.org/?probe=4b43ed314b) | Nov 06, 2023 |
| ASUSTek       | X751MA                      | [d5e1758d4e](https://linux-hardware.org/?probe=d5e1758d4e) | Nov 06, 2023 |
| Toshiba       | Satellite C855-10N          | [7afd607141](https://linux-hardware.org/?probe=7afd607141) | Nov 06, 2023 |
| HP            | 255 G7 Notebook PC          | [216faa6f5d](https://linux-hardware.org/?probe=216faa6f5d) | Nov 06, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [37d32a1fd5](https://linux-hardware.org/?probe=37d32a1fd5) | Nov 06, 2023 |
| Dell          | Inspiron 15-3567            | [b42102e397](https://linux-hardware.org/?probe=b42102e397) | Nov 06, 2023 |
| GPU Compan... | GWNR71517                   | [7676ff267d](https://linux-hardware.org/?probe=7676ff267d) | Nov 06, 2023 |
| Dell          | Latitude E6410              | [b6ac4a50b7](https://linux-hardware.org/?probe=b6ac4a50b7) | Nov 06, 2023 |
| HP            | ProBook 640 G1              | [1cc495d15b](https://linux-hardware.org/?probe=1cc495d15b) | Nov 05, 2023 |
| HP            | Compaq 6710b                | [7a0b2fd29b](https://linux-hardware.org/?probe=7a0b2fd29b) | Nov 05, 2023 |
| Apple         | MacBookPro9,2               | [1801a9c841](https://linux-hardware.org/?probe=1801a9c841) | Nov 05, 2023 |
| HP            | ProBook 4330s               | [b22a07c92b](https://linux-hardware.org/?probe=b22a07c92b) | Nov 05, 2023 |
| Lenovo        | ThinkPad T470 20HD0000BM    | [3e379ff6e8](https://linux-hardware.org/?probe=3e379ff6e8) | Nov 04, 2023 |
| HP            | Pavilion 11 x360 PC         | [399dda92eb](https://linux-hardware.org/?probe=399dda92eb) | Nov 04, 2023 |
| Lenovo        | ThinkPad T460 20FMS3YT01    | [89b8df73c1](https://linux-hardware.org/?probe=89b8df73c1) | Nov 04, 2023 |
| Acer          | Aspire E5-573G              | [c74051abb7](https://linux-hardware.org/?probe=c74051abb7) | Nov 04, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [b0487db7bf](https://linux-hardware.org/?probe=b0487db7bf) | Nov 04, 2023 |
| Acidanther... | MacBookPro15,2              | [ae60650070](https://linux-hardware.org/?probe=ae60650070) | Nov 04, 2023 |
| MSI           | MS-1759                     | [2dd46c2a71](https://linux-hardware.org/?probe=2dd46c2a71) | Nov 04, 2023 |
| Dell          | Latitude E7450              | [e7effc42ed](https://linux-hardware.org/?probe=e7effc42ed) | Nov 04, 2023 |
| Dell          | Latitude E5450              | [1f23c5fd7c](https://linux-hardware.org/?probe=1f23c5fd7c) | Nov 04, 2023 |
| Toshiba       | TECRA W50-A                 | [ad6c61de24](https://linux-hardware.org/?probe=ad6c61de24) | Nov 04, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [d2a9171090](https://linux-hardware.org/?probe=d2a9171090) | Nov 04, 2023 |
| Lenovo        | ThinkPad X220 4293A25       | [95a5125a73](https://linux-hardware.org/?probe=95a5125a73) | Nov 03, 2023 |
| HP            | EliteBook 6930p             | [300c72bf93](https://linux-hardware.org/?probe=300c72bf93) | Nov 03, 2023 |
| Dell          | Latitude 3420               | [9211e0f588](https://linux-hardware.org/?probe=9211e0f588) | Nov 03, 2023 |
| Unknown       | Unknown                     | [d27cd12013](https://linux-hardware.org/?probe=d27cd12013) | Nov 03, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [6c0dc28b9f](https://linux-hardware.org/?probe=6c0dc28b9f) | Nov 03, 2023 |
| ASUSTek       | X550VQ                      | [b6d6ff10aa](https://linux-hardware.org/?probe=b6d6ff10aa) | Nov 03, 2023 |
| Toshiba       | Satellite C650              | [6844fc4fcf](https://linux-hardware.org/?probe=6844fc4fcf) | Nov 03, 2023 |
| HP            | ProBook 6450b               | [a63f28d2be](https://linux-hardware.org/?probe=a63f28d2be) | Nov 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X411... | [8ac5fd2789](https://linux-hardware.org/?probe=8ac5fd2789) | Nov 02, 2023 |
| Intel         | powered classmate PC        | [122f9662f5](https://linux-hardware.org/?probe=122f9662f5) | Nov 02, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e5b852ff3e](https://linux-hardware.org/?probe=e5b852ff3e) | Nov 02, 2023 |
| Google        | Falco                       | [0ea6d932bf](https://linux-hardware.org/?probe=0ea6d932bf) | Nov 01, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [11c06a97d7](https://linux-hardware.org/?probe=11c06a97d7) | Nov 01, 2023 |
| Lenovo        | ThinkPad E560 20EVA02SSP    | [165be504bf](https://linux-hardware.org/?probe=165be504bf) | Nov 01, 2023 |
| Lenovo        | ThinkPad T430 23493V2       | [0d5b87b380](https://linux-hardware.org/?probe=0d5b87b380) | Nov 01, 2023 |
| Dell          | Inspiron 13-5368            | [6d00cda16c](https://linux-hardware.org/?probe=6d00cda16c) | Nov 01, 2023 |
| Framework     | Laptop                      | [eb0a6abacc](https://linux-hardware.org/?probe=eb0a6abacc) | Nov 01, 2023 |
| Dell          | Inspiron 3542               | [87ec116ea6](https://linux-hardware.org/?probe=87ec116ea6) | Nov 01, 2023 |
| Acer          | Predator PH18-71            | [a0393f21c9](https://linux-hardware.org/?probe=a0393f21c9) | Nov 01, 2023 |
| HP            | EliteBook 840 G3            | [a09d649781](https://linux-hardware.org/?probe=a09d649781) | Nov 01, 2023 |
| Acer          | Aspire E5-576G              | [c0626d553b](https://linux-hardware.org/?probe=c0626d553b) | Oct 30, 2023 |
| Dell          | Latitude 7480               | [fcae1c21f4](https://linux-hardware.org/?probe=fcae1c21f4) | Oct 30, 2023 |
| ASUSTek       | X555LD                      | [2c79650ee2](https://linux-hardware.org/?probe=2c79650ee2) | Oct 29, 2023 |
| Samsung       | RC410/RC510/RC710           | [3cc0feaa4e](https://linux-hardware.org/?probe=3cc0feaa4e) | Oct 29, 2023 |
| Acer          | AOD270                      | [83c4a5920f](https://linux-hardware.org/?probe=83c4a5920f) | Oct 29, 2023 |
| Lenovo        | ThinkPad T460 20FMS5E018    | [98c446abbd](https://linux-hardware.org/?probe=98c446abbd) | Oct 29, 2023 |
| Dell          | XPS 15 9570                 | [17de10e607](https://linux-hardware.org/?probe=17de10e607) | Oct 29, 2023 |
| HP            | Laptop 15-da0xxx            | [39d06d7acf](https://linux-hardware.org/?probe=39d06d7acf) | Oct 28, 2023 |
| Dell          | Inspiron MM061              | [7545369484](https://linux-hardware.org/?probe=7545369484) | Oct 28, 2023 |
| HP            | Pavilion g6                 | [ecc6e8d906](https://linux-hardware.org/?probe=ecc6e8d906) | Oct 28, 2023 |
| Samsung       | 370E4K                      | [78ec3e796a](https://linux-hardware.org/?probe=78ec3e796a) | Oct 28, 2023 |
| HP            | Laptop 15s-fq0xxx           | [e3154e94cf](https://linux-hardware.org/?probe=e3154e94cf) | Oct 28, 2023 |
| ASUSTek       | X101                        | [dab1a6368d](https://linux-hardware.org/?probe=dab1a6368d) | Oct 27, 2023 |
| Fujitsu       | LIFEBOOK S792               | [5eaa7922e7](https://linux-hardware.org/?probe=5eaa7922e7) | Oct 27, 2023 |
| Dell          | Precision M6800             | [e8fd7cce51](https://linux-hardware.org/?probe=e8fd7cce51) | Oct 27, 2023 |
| Toshiba       | dynabook T350/56ARK         | [802dacc8cc](https://linux-hardware.org/?probe=802dacc8cc) | Oct 27, 2023 |
| MSI           | GL73 8RD                    | [62d3ea64dd](https://linux-hardware.org/?probe=62d3ea64dd) | Oct 27, 2023 |
| Dell          | Inspiron 5737               | [6ed0863a43](https://linux-hardware.org/?probe=6ed0863a43) | Oct 27, 2023 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | [3a2901251b](https://linux-hardware.org/?probe=3a2901251b) | Oct 27, 2023 |
| Dell          | Inspiron 1525               | [0a0a08dd5f](https://linux-hardware.org/?probe=0a0a08dd5f) | Oct 26, 2023 |
| Apple         | MacBookPro6,2               | [af9b5b05e9](https://linux-hardware.org/?probe=af9b5b05e9) | Oct 26, 2023 |
| Apple         | MacBookPro7,1               | [cb27a04bd5](https://linux-hardware.org/?probe=cb27a04bd5) | Oct 26, 2023 |
| HP            | Pavilion g6                 | [00e978bda2](https://linux-hardware.org/?probe=00e978bda2) | Oct 26, 2023 |
| HP            | 650                         | [0625bd022d](https://linux-hardware.org/?probe=0625bd022d) | Oct 26, 2023 |
| SLIMBOOK      | EXECUTIVE-14                | [39250155c4](https://linux-hardware.org/?probe=39250155c4) | Oct 26, 2023 |
| Toshiba       | Satellite C670D-126         | [b117860daf](https://linux-hardware.org/?probe=b117860daf) | Oct 25, 2023 |
| NEC Comput... | PC-VJ22LFWZHSRF             | [b229c83a28](https://linux-hardware.org/?probe=b229c83a28) | Oct 25, 2023 |
| ASUSTek       | X551CAP                     | [bff9909d9b](https://linux-hardware.org/?probe=bff9909d9b) | Oct 24, 2023 |
| HP            | Laptop 17-by2xxx            | [9f728690ee](https://linux-hardware.org/?probe=9f728690ee) | Oct 24, 2023 |
| HP            | EliteBook 8770w             | [50cab103c8](https://linux-hardware.org/?probe=50cab103c8) | Oct 24, 2023 |
| ASUSTek       | UX303LB                     | [1fdfa51ddc](https://linux-hardware.org/?probe=1fdfa51ddc) | Oct 24, 2023 |
| Lenovo        | G580 2189                   | [18dc8e53d9](https://linux-hardware.org/?probe=18dc8e53d9) | Oct 24, 2023 |
| Dell          | Inspiron 15 3511            | [8d2894b3d1](https://linux-hardware.org/?probe=8d2894b3d1) | Oct 24, 2023 |
| HP            | ProBook 450 G6              | [17c7c26cd0](https://linux-hardware.org/?probe=17c7c26cd0) | Oct 24, 2023 |
| LG Electro... | 17ZT90P-G.AX33U1            | [0d53262cff](https://linux-hardware.org/?probe=0d53262cff) | Oct 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [dc730f5631](https://linux-hardware.org/?probe=dc730f5631) | Oct 23, 2023 |
| Dell          | Inspiron 11 - 3147          | [7be979fc66](https://linux-hardware.org/?probe=7be979fc66) | Oct 23, 2023 |
| Samsung       | RF511/RF411/RF711           | [6a62fa5cb6](https://linux-hardware.org/?probe=6a62fa5cb6) | Oct 23, 2023 |
| Toshiba       | Satellite P55W-C            | [60911595dc](https://linux-hardware.org/?probe=60911595dc) | Oct 23, 2023 |
| Lenovo        | Unknown                     | [21cf9c327a](https://linux-hardware.org/?probe=21cf9c327a) | Oct 22, 2023 |
| ASUSTek       | UL80VT                      | [7991ecc4ee](https://linux-hardware.org/?probe=7991ecc4ee) | Oct 22, 2023 |
| Dell          | System Vostro 3750          | [33345af29b](https://linux-hardware.org/?probe=33345af29b) | Oct 22, 2023 |
| ASUSTek       | X550LA                      | [10e4a414fd](https://linux-hardware.org/?probe=10e4a414fd) | Oct 22, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [a02e93f0a5](https://linux-hardware.org/?probe=a02e93f0a5) | Oct 21, 2023 |
| Sony          | VGN-FZ21M                   | [ba7c93bcd4](https://linux-hardware.org/?probe=ba7c93bcd4) | Oct 21, 2023 |
| Acer          | Aspire 5742                 | [f30dc155bd](https://linux-hardware.org/?probe=f30dc155bd) | Oct 21, 2023 |
| Lenovo        | IdeaPad S145-15IGM 81WT     | [ad7ca8e192](https://linux-hardware.org/?probe=ad7ca8e192) | Oct 21, 2023 |
| HP            | Laptop 15s-eq1xxx           | [5795100325](https://linux-hardware.org/?probe=5795100325) | Oct 21, 2023 |
| Gateway       | NV55C                       | [bb0eb9e5dd](https://linux-hardware.org/?probe=bb0eb9e5dd) | Oct 21, 2023 |
| Acer          | Aspire A315-23              | [d3b1d639f5](https://linux-hardware.org/?probe=d3b1d639f5) | Oct 21, 2023 |
| HP            | Pavilion dm1                | [74c8fce8f0](https://linux-hardware.org/?probe=74c8fce8f0) | Oct 21, 2023 |
| Lenovo        | G510 20238                  | [d6bd0eda6d](https://linux-hardware.org/?probe=d6bd0eda6d) | Oct 21, 2023 |
| HP            | TouchSmart tm2              | [a79b82edd3](https://linux-hardware.org/?probe=a79b82edd3) | Oct 21, 2023 |
| Compaq        | 434                         | [094bba21f8](https://linux-hardware.org/?probe=094bba21f8) | Oct 21, 2023 |
| Lenovo        | IdeaPad 330-17AST 81D7      | [314c39b6d1](https://linux-hardware.org/?probe=314c39b6d1) | Oct 21, 2023 |
| Dell          | Inspiron 5559               | [83811b2a84](https://linux-hardware.org/?probe=83811b2a84) | Oct 21, 2023 |
| Toshiba       | Satellite A660              | [a5e343d353](https://linux-hardware.org/?probe=a5e343d353) | Oct 21, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [1ff62f5fd7](https://linux-hardware.org/?probe=1ff62f5fd7) | Oct 21, 2023 |
| Dell          | G15 5510                    | [5e7232a684](https://linux-hardware.org/?probe=5e7232a684) | Oct 21, 2023 |
| Samsung       | R530/R730/P590              | [6a774fbae7](https://linux-hardware.org/?probe=6a774fbae7) | Oct 21, 2023 |
| Lenovo        | ThinkPad X201 3680V5T       | [b30e261022](https://linux-hardware.org/?probe=b30e261022) | Oct 20, 2023 |
| HP            | Compaq 15                   | [992044ca80](https://linux-hardware.org/?probe=992044ca80) | Oct 20, 2023 |
| ASUSTek       | S400CA                      | [1c0c1df851](https://linux-hardware.org/?probe=1c0c1df851) | Oct 20, 2023 |
| Lenovo        | ThinkPad L540 20AUA044FR    | [70d42f0667](https://linux-hardware.org/?probe=70d42f0667) | Oct 20, 2023 |
| Toshiba       | dynabook R732/H             | [4852b6da95](https://linux-hardware.org/?probe=4852b6da95) | Oct 20, 2023 |
| Lenovo        | G505s 20255                 | [71bfa98c37](https://linux-hardware.org/?probe=71bfa98c37) | Oct 20, 2023 |
| Acer          | Aspire A114-33              | [34ffce7f83](https://linux-hardware.org/?probe=34ffce7f83) | Oct 20, 2023 |
| Lenovo        | Y50-70 20378                | [2593407253](https://linux-hardware.org/?probe=2593407253) | Oct 20, 2023 |
| Toshiba       | Satellite P50t-B-118        | [5237c0866e](https://linux-hardware.org/?probe=5237c0866e) | Oct 19, 2023 |
| Acer          | AOD270                      | [b8c4966af7](https://linux-hardware.org/?probe=b8c4966af7) | Oct 19, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [b8ee9cff90](https://linux-hardware.org/?probe=b8ee9cff90) | Oct 19, 2023 |
| Dell          | Vostro 3560                 | [aa95d1c178](https://linux-hardware.org/?probe=aa95d1c178) | Oct 19, 2023 |
| HP            | TouchSmart tm2              | [f72f6a43b5](https://linux-hardware.org/?probe=f72f6a43b5) | Oct 19, 2023 |
| ASUSTek       | X542UR                      | [72390695fd](https://linux-hardware.org/?probe=72390695fd) | Oct 19, 2023 |
| ASUSTek       | X540LJ                      | [a0c126c4ce](https://linux-hardware.org/?probe=a0c126c4ce) | Oct 19, 2023 |
| Dell          | Inspiron 5547               | [3dc947b334](https://linux-hardware.org/?probe=3dc947b334) | Oct 19, 2023 |
| HP            | EliteBook 8570p             | [5cea3b7124](https://linux-hardware.org/?probe=5cea3b7124) | Oct 18, 2023 |
| Dell          | Latitude E6320              | [91e5128fd5](https://linux-hardware.org/?probe=91e5128fd5) | Oct 18, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [d8ab8a8fc8](https://linux-hardware.org/?probe=d8ab8a8fc8) | Oct 18, 2023 |
| HP            | OMEN Laptop 15-ek0xxx       | [501f7abc3b](https://linux-hardware.org/?probe=501f7abc3b) | Oct 18, 2023 |
| Unknown       | Unknown                     | [e1751f1726](https://linux-hardware.org/?probe=e1751f1726) | Oct 17, 2023 |
| HP            | EliteBook 830 G6            | [c9ab502087](https://linux-hardware.org/?probe=c9ab502087) | Oct 17, 2023 |
| Lenovo        | Yoga 7 14ARP8 82YM          | [7e446027c0](https://linux-hardware.org/?probe=7e446027c0) | Oct 17, 2023 |
| HP            | Pavilion Notebook           | [5981bba0dd](https://linux-hardware.org/?probe=5981bba0dd) | Oct 17, 2023 |
| HP            | Laptop 15s-eq2xxx           | [7b5cf8abfc](https://linux-hardware.org/?probe=7b5cf8abfc) | Oct 17, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [f3bd5c6632](https://linux-hardware.org/?probe=f3bd5c6632) | Oct 17, 2023 |
| Dell          | Vostro 1510                 | [cf920dcf20](https://linux-hardware.org/?probe=cf920dcf20) | Oct 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [9f9777f778](https://linux-hardware.org/?probe=9f9777f778) | Oct 17, 2023 |
| HP            | Folio 13 - 2000             | [c541a1603c](https://linux-hardware.org/?probe=c541a1603c) | Oct 17, 2023 |
| ASUSTek       | N61Jv                       | [cb8a1ca22a](https://linux-hardware.org/?probe=cb8a1ca22a) | Oct 17, 2023 |
| HP            | EliteBook 2760p             | [3d62b547f3](https://linux-hardware.org/?probe=3d62b547f3) | Oct 16, 2023 |
| HP            | 2000                        | [c2669ff6cb](https://linux-hardware.org/?probe=c2669ff6cb) | Oct 16, 2023 |
| HP            | 630                         | [db6efff83b](https://linux-hardware.org/?probe=db6efff83b) | Oct 16, 2023 |
| Dell          | Inspiron 1545               | [03670e3e53](https://linux-hardware.org/?probe=03670e3e53) | Oct 16, 2023 |
| Lenovo        | ThinkPad R61 8935AC7        | [fc4f024a54](https://linux-hardware.org/?probe=fc4f024a54) | Oct 16, 2023 |
| Dell          | Latitude E5470              | [0c6b7d2953](https://linux-hardware.org/?probe=0c6b7d2953) | Oct 16, 2023 |
| Sony          | VPCEF2S1E                   | [e4be1dd0e0](https://linux-hardware.org/?probe=e4be1dd0e0) | Oct 16, 2023 |
| MSI           | GT70 0NC/GT70 0NC           | [24e93d9411](https://linux-hardware.org/?probe=24e93d9411) | Oct 15, 2023 |
| Toshiba       | Satellite L655              | [9bda720e30](https://linux-hardware.org/?probe=9bda720e30) | Oct 15, 2023 |
| Dell          | Inspiron 3576               | [28b33e764d](https://linux-hardware.org/?probe=28b33e764d) | Oct 15, 2023 |
| Samsung       | 550XCJ/550XCR               | [579dc4dabc](https://linux-hardware.org/?probe=579dc4dabc) | Oct 15, 2023 |
| HP            | Unknown                     | [cae9b0ba31](https://linux-hardware.org/?probe=cae9b0ba31) | Oct 14, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [36327d381a](https://linux-hardware.org/?probe=36327d381a) | Oct 14, 2023 |
| Valve         | Jupiter                     | [94366b8682](https://linux-hardware.org/?probe=94366b8682) | Oct 14, 2023 |
| Dell          | Precision 7720              | [574a292adb](https://linux-hardware.org/?probe=574a292adb) | Oct 14, 2023 |
| Lenovo        | ThinkPad T400 64757D7       | [b374e214af](https://linux-hardware.org/?probe=b374e214af) | Oct 13, 2023 |
| Notebook      | NJ50_70CU                   | [885120121b](https://linux-hardware.org/?probe=885120121b) | Oct 13, 2023 |
| Lenovo        | ThinkPad T61 7661WQQ        | [d14e3ec320](https://linux-hardware.org/?probe=d14e3ec320) | Oct 13, 2023 |
| Fujitsu       | FMVNS7HE                    | [2408a69be7](https://linux-hardware.org/?probe=2408a69be7) | Oct 13, 2023 |
| Acer          | Aspire A515-45              | [f5e57e4558](https://linux-hardware.org/?probe=f5e57e4558) | Oct 13, 2023 |
| Toshiba       | Satellite L755              | [04b09d7164](https://linux-hardware.org/?probe=04b09d7164) | Oct 12, 2023 |
| Dell          | XPS 13 9360                 | [d227c42e18](https://linux-hardware.org/?probe=d227c42e18) | Oct 12, 2023 |
| HP            | 14                          | [e207fce0d4](https://linux-hardware.org/?probe=e207fce0d4) | Oct 12, 2023 |
| Lenovo        | IdeaPad P500 20210          | [ba316cb723](https://linux-hardware.org/?probe=ba316cb723) | Oct 12, 2023 |
| Dell          | Latitude E6430              | [802b70a3c0](https://linux-hardware.org/?probe=802b70a3c0) | Oct 11, 2023 |
| Lenovo        | ThinkPad T530 23594LU       | [b18b8f45a4](https://linux-hardware.org/?probe=b18b8f45a4) | Oct 11, 2023 |
| Toshiba       | Satellite C870-D7K          | [150f57bc3d](https://linux-hardware.org/?probe=150f57bc3d) | Oct 11, 2023 |
| MSI           | GL75 9SE                    | [bffc7bdfe6](https://linux-hardware.org/?probe=bffc7bdfe6) | Oct 11, 2023 |
| Acer          | Aspire A317-53              | [cfcd99cc4f](https://linux-hardware.org/?probe=cfcd99cc4f) | Oct 10, 2023 |
| Dell          | Latitude E6440              | [7471faa299](https://linux-hardware.org/?probe=7471faa299) | Oct 10, 2023 |
| Dell          | Inspiron 3521               | [290872884b](https://linux-hardware.org/?probe=290872884b) | Oct 10, 2023 |
| Toshiba       | Satellite A665              | [b80211d14f](https://linux-hardware.org/?probe=b80211d14f) | Oct 10, 2023 |
| Medion        | E11201                      | [25afe8c1be](https://linux-hardware.org/?probe=25afe8c1be) | Oct 09, 2023 |
| HP            | 15 TS                       | [a57405a3be](https://linux-hardware.org/?probe=a57405a3be) | Oct 09, 2023 |
| Dell          | Latitude E5440              | [a039ff25ef](https://linux-hardware.org/?probe=a039ff25ef) | Oct 08, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [c237b78f41](https://linux-hardware.org/?probe=c237b78f41) | Oct 08, 2023 |
| Lenovo        | G580 20150                  | [fa47449843](https://linux-hardware.org/?probe=fa47449843) | Oct 08, 2023 |
| HP            | Laptop 15-dw0xxx            | [c6da0d1963](https://linux-hardware.org/?probe=c6da0d1963) | Oct 08, 2023 |
| Acer          | Aspire ES1-572              | [ac5943ef0c](https://linux-hardware.org/?probe=ac5943ef0c) | Oct 08, 2023 |
| Lenovo        | IdeaPad 310 Touch-15IKB ... | [0f32aa1d9d](https://linux-hardware.org/?probe=0f32aa1d9d) | Oct 08, 2023 |
| HUAWEI        | HLYL-WXX9                   | [89674f77b2](https://linux-hardware.org/?probe=89674f77b2) | Oct 07, 2023 |
| Lenovo        | ThinkPad T480s 20L8S3EJ0... | [f39067b962](https://linux-hardware.org/?probe=f39067b962) | Oct 07, 2023 |
| Dell          | Precision M2800             | [75b0ab2562](https://linux-hardware.org/?probe=75b0ab2562) | Oct 07, 2023 |
| Toshiba       | Satellite A305D             | [d2fc1d1762](https://linux-hardware.org/?probe=d2fc1d1762) | Oct 07, 2023 |
| HP            | Compaq Presario C768        | [7b364bd566](https://linux-hardware.org/?probe=7b364bd566) | Oct 07, 2023 |
| Acer          | Aspire E1-571G              | [205a84adc9](https://linux-hardware.org/?probe=205a84adc9) | Oct 07, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [3b423be827](https://linux-hardware.org/?probe=3b423be827) | Oct 06, 2023 |
| Thomson       | WWN15I5-8BK1T               | [10ca155743](https://linux-hardware.org/?probe=10ca155743) | Oct 06, 2023 |
| HP            | Laptop 15s-fq3xxx           | [3cbdc1eb94](https://linux-hardware.org/?probe=3cbdc1eb94) | Oct 06, 2023 |
| Apple         | MacBookPro12,1              | [e627afd34e](https://linux-hardware.org/?probe=e627afd34e) | Oct 05, 2023 |
| HP            | ProBook 6450b               | [f597cfe9d1](https://linux-hardware.org/?probe=f597cfe9d1) | Oct 05, 2023 |
| HP            | ENVY Laptop 16-h0xxx        | [1729f3bfbe](https://linux-hardware.org/?probe=1729f3bfbe) | Oct 05, 2023 |
| HP            | EliteBook 8460p             | [ce99edd92c](https://linux-hardware.org/?probe=ce99edd92c) | Oct 05, 2023 |
| Lenovo        | B50-80 80LT                 | [74b54d0f3f](https://linux-hardware.org/?probe=74b54d0f3f) | Oct 05, 2023 |
| Apple         | MacBookPro13,3              | [171a2ad768](https://linux-hardware.org/?probe=171a2ad768) | Oct 04, 2023 |
| HP            | Pavilion Notebook           | [59c0b6ce9c](https://linux-hardware.org/?probe=59c0b6ce9c) | Oct 04, 2023 |
| Apple         | MacBookPro8,2               | [4749aba038](https://linux-hardware.org/?probe=4749aba038) | Oct 04, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [f10db8b926](https://linux-hardware.org/?probe=f10db8b926) | Oct 04, 2023 |
| Dell          | Latitude E6410              | [0b58de80dd](https://linux-hardware.org/?probe=0b58de80dd) | Oct 04, 2023 |
| ASUSTek       | UL80VT                      | [fc4a10d945](https://linux-hardware.org/?probe=fc4a10d945) | Oct 04, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [c40f80d33a](https://linux-hardware.org/?probe=c40f80d33a) | Oct 03, 2023 |
| MSI           | CR620                       | [be490381a9](https://linux-hardware.org/?probe=be490381a9) | Oct 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [3657d65cec](https://linux-hardware.org/?probe=3657d65cec) | Oct 03, 2023 |
| ASUSTek       | X550CL                      | [fc47e59598](https://linux-hardware.org/?probe=fc47e59598) | Oct 02, 2023 |
| Dell          | Inspiron 13-5368            | [b7463e19f8](https://linux-hardware.org/?probe=b7463e19f8) | Oct 02, 2023 |
| HP            | Pavilion g6                 | [7fadaa78cd](https://linux-hardware.org/?probe=7fadaa78cd) | Oct 02, 2023 |
| Apple         | MacBookAir6,2               | [25d2225829](https://linux-hardware.org/?probe=25d2225829) | Oct 02, 2023 |
| Acer          | Nitro AN515-55              | [9bebc42b46](https://linux-hardware.org/?probe=9bebc42b46) | Oct 02, 2023 |
| Lenovo        | G500 20236                  | [fcef55efdf](https://linux-hardware.org/?probe=fcef55efdf) | Oct 01, 2023 |
| Toshiba       | Satellite L775              | [c659fe6fba](https://linux-hardware.org/?probe=c659fe6fba) | Oct 01, 2023 |
| Acer          | Aspire V3-772               | [6e0e08c45e](https://linux-hardware.org/?probe=6e0e08c45e) | Oct 01, 2023 |
| HP            | Laptop 17-cn0xxx            | [aa4b869750](https://linux-hardware.org/?probe=aa4b869750) | Oct 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [2127748080](https://linux-hardware.org/?probe=2127748080) | Oct 01, 2023 |
| Acer          | Aspire A315-58              | [bbab99a4f7](https://linux-hardware.org/?probe=bbab99a4f7) | Sep 30, 2023 |
| Medion        | Deputy P40                  | [7e0fc5b52d](https://linux-hardware.org/?probe=7e0fc5b52d) | Sep 30, 2023 |
| Lenovo        | ThinkPad L530 24783R8       | [eda040f456](https://linux-hardware.org/?probe=eda040f456) | Sep 30, 2023 |
| Acer          | Aspire 5560                 | [252d19e4f5](https://linux-hardware.org/?probe=252d19e4f5) | Sep 30, 2023 |
| Toshiba       | Satellite L500              | [9c1b258088](https://linux-hardware.org/?probe=9c1b258088) | Sep 30, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [2edc7ab56b](https://linux-hardware.org/?probe=2edc7ab56b) | Sep 30, 2023 |
| Toshiba       | Satellite C845D             | [92651c9e51](https://linux-hardware.org/?probe=92651c9e51) | Sep 30, 2023 |
| Lenovo        | 300s-15ARR 81FB             | [4f7e627fd2](https://linux-hardware.org/?probe=4f7e627fd2) | Sep 30, 2023 |
| Lenovo        | Z50-70 20354                | [eb33abdaae](https://linux-hardware.org/?probe=eb33abdaae) | Sep 29, 2023 |
| ASUSTek       | UX31E                       | [1b6440f722](https://linux-hardware.org/?probe=1b6440f722) | Sep 29, 2023 |
| HP            | ENVY TS Sleekbook 4         | [545098d0d2](https://linux-hardware.org/?probe=545098d0d2) | Sep 29, 2023 |
| OEGStone      | C4100/C5100                 | [0c27e50b14](https://linux-hardware.org/?probe=0c27e50b14) | Sep 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [6348992a72](https://linux-hardware.org/?probe=6348992a72) | Sep 29, 2023 |
| Dell          | Inspiron 5570               | [7975260826](https://linux-hardware.org/?probe=7975260826) | Sep 29, 2023 |
| SKIKK         | Sindri 14                   | [9766c80aa9](https://linux-hardware.org/?probe=9766c80aa9) | Sep 29, 2023 |
| Dell          | Inspiron 3542               | [b7faf1054b](https://linux-hardware.org/?probe=b7faf1054b) | Sep 29, 2023 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [902918fb1d](https://linux-hardware.org/?probe=902918fb1d) | Sep 29, 2023 |
| HP            | EliteBook 2760p             | [e9d026d0df](https://linux-hardware.org/?probe=e9d026d0df) | Sep 29, 2023 |
| HP            | Compaq Presario CQ70        | [8913bbd459](https://linux-hardware.org/?probe=8913bbd459) | Sep 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [fb4cde69b8](https://linux-hardware.org/?probe=fb4cde69b8) | Sep 28, 2023 |
| HP            | Laptop 17-bs0xx             | [85548f2790](https://linux-hardware.org/?probe=85548f2790) | Sep 28, 2023 |
| HP            | ElitePad 1000 G2            | [9c4b30a15c](https://linux-hardware.org/?probe=9c4b30a15c) | Sep 27, 2023 |
| Toshiba       | Satellite A200              | [6bdac98313](https://linux-hardware.org/?probe=6bdac98313) | Sep 27, 2023 |
| HP            | ElitePad 1000 G2            | [ee4b3f2b76](https://linux-hardware.org/?probe=ee4b3f2b76) | Sep 26, 2023 |
| LG Electro... | 13U70Q-G.AA75B              | [f38b79055b](https://linux-hardware.org/?probe=f38b79055b) | Sep 26, 2023 |
| Samsung       | R519/R719                   | [15ae7c9603](https://linux-hardware.org/?probe=15ae7c9603) | Sep 26, 2023 |
| Lenovo        | ThinkPad T460 20FMS0RN1S    | [598d621f0d](https://linux-hardware.org/?probe=598d621f0d) | Sep 26, 2023 |
| HP            | EliteBook 840 G3            | [897f671915](https://linux-hardware.org/?probe=897f671915) | Sep 25, 2023 |
| ASUSTek       | UL80VT                      | [1d3c36ccf4](https://linux-hardware.org/?probe=1d3c36ccf4) | Sep 25, 2023 |
| Dell          | Vostro 1000                 | [38499a1a0f](https://linux-hardware.org/?probe=38499a1a0f) | Sep 25, 2023 |
| Toshiba       | Satellite C50-B             | [92a5c3605c](https://linux-hardware.org/?probe=92a5c3605c) | Sep 25, 2023 |
| Toshiba       | dynabook Satellite B350/... | [2b241af774](https://linux-hardware.org/?probe=2b241af774) | Sep 25, 2023 |
| HP            | Laptop 17-cn0xxx            | [10ec627bad](https://linux-hardware.org/?probe=10ec627bad) | Sep 25, 2023 |
| Acer          | Aspire F5-573G              | [a2f6814940](https://linux-hardware.org/?probe=a2f6814940) | Sep 25, 2023 |
| Acer          | Aspire E5-571               | [e74a87d3f4](https://linux-hardware.org/?probe=e74a87d3f4) | Sep 25, 2023 |
| Acer          | Nitro AN515-51              | [6d6d719f30](https://linux-hardware.org/?probe=6d6d719f30) | Sep 25, 2023 |
| HP            | ElitePad 1000 G2            | [5cfbe2e7e0](https://linux-hardware.org/?probe=5cfbe2e7e0) | Sep 24, 2023 |
| Acer          | Aspire 7730G                | [e21c91c34c](https://linux-hardware.org/?probe=e21c91c34c) | Sep 24, 2023 |
| Toshiba       | Satellite L45-B             | [e998b320d8](https://linux-hardware.org/?probe=e998b320d8) | Sep 24, 2023 |
| Lenovo        | G580 20150                  | [f55e42a884](https://linux-hardware.org/?probe=f55e42a884) | Sep 24, 2023 |
| Toshiba       | Satellite S50t-B            | [a574ee83ff](https://linux-hardware.org/?probe=a574ee83ff) | Sep 24, 2023 |
| Dell          | System Vostro 3750          | [3b050c2582](https://linux-hardware.org/?probe=3b050c2582) | Sep 24, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [ff891ca545](https://linux-hardware.org/?probe=ff891ca545) | Sep 24, 2023 |
| Acer          | Aspire 5734Z                | [d5219dbfbe](https://linux-hardware.org/?probe=d5219dbfbe) | Sep 24, 2023 |
| Unknown       | Unknown                     | [940b1d1eeb](https://linux-hardware.org/?probe=940b1d1eeb) | Sep 23, 2023 |
| HP            | Dev One Notebook PC         | [1cc979900b](https://linux-hardware.org/?probe=1cc979900b) | Sep 23, 2023 |
| Acer          | Aspire 5732Z                | [c86094eac8](https://linux-hardware.org/?probe=c86094eac8) | Sep 23, 2023 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | [683cbd037a](https://linux-hardware.org/?probe=683cbd037a) | Sep 23, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [13a9f1d65a](https://linux-hardware.org/?probe=13a9f1d65a) | Sep 23, 2023 |
| HP            | Laptop 15-dw1xxx            | [be4a46768b](https://linux-hardware.org/?probe=be4a46768b) | Sep 23, 2023 |
| HP            | EliteBook 840 G6            | [10cd0244af](https://linux-hardware.org/?probe=10cd0244af) | Sep 23, 2023 |
| Samsung       | 935XDB                      | [a0672b9726](https://linux-hardware.org/?probe=a0672b9726) | Sep 23, 2023 |
| ASUSTek       | X750JB                      | [b9db8f6f02](https://linux-hardware.org/?probe=b9db8f6f02) | Sep 23, 2023 |
| HP            | ProBook 4515s               | [0b755bf978](https://linux-hardware.org/?probe=0b755bf978) | Sep 22, 2023 |
| LG Electro... | 16Z90P-K.AAS9U1             | [5e60864354](https://linux-hardware.org/?probe=5e60864354) | Sep 22, 2023 |
| Acer          | Aspire A515-47              | [2676f29c41](https://linux-hardware.org/?probe=2676f29c41) | Sep 22, 2023 |
| Dell          | Latitude E7440              | [53e90ca355](https://linux-hardware.org/?probe=53e90ca355) | Sep 22, 2023 |
| Apple         | MacBookPro12,1              | [b8b562cc39](https://linux-hardware.org/?probe=b8b562cc39) | Sep 22, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [57c3bb43f5](https://linux-hardware.org/?probe=57c3bb43f5) | Sep 22, 2023 |
| HP            | Pavilion g6                 | [c5833405a5](https://linux-hardware.org/?probe=c5833405a5) | Sep 22, 2023 |
| HP            | EliteBook 840 G5            | [03d461d3af](https://linux-hardware.org/?probe=03d461d3af) | Sep 22, 2023 |
| Acer          | Aspire VN7-571G             | [0314ce541e](https://linux-hardware.org/?probe=0314ce541e) | Sep 22, 2023 |
| Acer          | Nitro AN515-57              | [05c9cbc8e5](https://linux-hardware.org/?probe=05c9cbc8e5) | Sep 22, 2023 |
| Acer          | Extensa 5635ZG              | [925fed495b](https://linux-hardware.org/?probe=925fed495b) | Sep 21, 2023 |
| Lenovo        | ThinkPad X220 4286BB2       | [a3b217a707](https://linux-hardware.org/?probe=a3b217a707) | Sep 21, 2023 |
| Acer          | Aspire A114-33              | [4b581786a8](https://linux-hardware.org/?probe=4b581786a8) | Sep 21, 2023 |
| Acer          | Aspire F5-571               | [21bcc4a506](https://linux-hardware.org/?probe=21bcc4a506) | Sep 21, 2023 |
| ASUSTek       | TP550LAB                    | [3e07304aa5](https://linux-hardware.org/?probe=3e07304aa5) | Sep 20, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [5a74bb7dde](https://linux-hardware.org/?probe=5a74bb7dde) | Sep 20, 2023 |
| HP            | EliteBook 845 14 inch G9... | [35d24c31cf](https://linux-hardware.org/?probe=35d24c31cf) | Sep 20, 2023 |
| Dell          | Latitude 3540               | [3f1c99de44](https://linux-hardware.org/?probe=3f1c99de44) | Sep 20, 2023 |
| ASUSTek       | X453MA                      | [8eacbd2f7a](https://linux-hardware.org/?probe=8eacbd2f7a) | Sep 19, 2023 |
| Dell          | Inspiron 3442               | [1f6ca2e4f7](https://linux-hardware.org/?probe=1f6ca2e4f7) | Sep 19, 2023 |
| Acer          | Nitro AN517-52              | [32f2e74fe3](https://linux-hardware.org/?probe=32f2e74fe3) | Sep 19, 2023 |
| Acer          | Aspire A315-22G             | [0c047cb731](https://linux-hardware.org/?probe=0c047cb731) | Sep 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [1180346586](https://linux-hardware.org/?probe=1180346586) | Sep 19, 2023 |
| HP            | EliteBook 8470p             | [a8995def08](https://linux-hardware.org/?probe=a8995def08) | Sep 19, 2023 |
| Lenovo        | ThinkPad X240 20AMA1S702    | [5be3b8fc11](https://linux-hardware.org/?probe=5be3b8fc11) | Sep 19, 2023 |
| Acer          | Aspire 5742                 | [430ed1fe6c](https://linux-hardware.org/?probe=430ed1fe6c) | Sep 19, 2023 |
| HP            | Laptop 15s-eq2xxx           | [53549e3b08](https://linux-hardware.org/?probe=53549e3b08) | Sep 18, 2023 |
| Lenovo        | ThinkPad T440s 20ARS0NF0... | [54aa39a845](https://linux-hardware.org/?probe=54aa39a845) | Sep 18, 2023 |
| Acer          | Swift SF314-42              | [1519801016](https://linux-hardware.org/?probe=1519801016) | Sep 18, 2023 |
| HP            | Notebook                    | [0c80a5c83f](https://linux-hardware.org/?probe=0c80a5c83f) | Sep 18, 2023 |
| MSI           | Modern 14 C11M              | [4c6156df05](https://linux-hardware.org/?probe=4c6156df05) | Sep 18, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [cad09f007e](https://linux-hardware.org/?probe=cad09f007e) | Sep 18, 2023 |
| Schenker      | XMG CORE (M19, GTX 1650)    | [612bda7c21](https://linux-hardware.org/?probe=612bda7c21) | Sep 17, 2023 |
| ASUSTek       | P52F                        | [6be70b4b24](https://linux-hardware.org/?probe=6be70b4b24) | Sep 17, 2023 |
| Lenovo        | ThinkPad L440 20ASEB3       | [20d35c7482](https://linux-hardware.org/?probe=20d35c7482) | Sep 17, 2023 |
| Toshiba       | Satellite Pro R50-B         | [e3a895eaa7](https://linux-hardware.org/?probe=e3a895eaa7) | Sep 17, 2023 |
| Notebook      | NP5x_6x_7x_SNx              | [83be57b9aa](https://linux-hardware.org/?probe=83be57b9aa) | Sep 17, 2023 |
| Dell          | System XPS L502X            | [d3154f94d7](https://linux-hardware.org/?probe=d3154f94d7) | Sep 17, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | [1a5acc2c10](https://linux-hardware.org/?probe=1a5acc2c10) | Sep 17, 2023 |
| NEC Comput... | PC-VK15EBZDG                | [83d74c1e9d](https://linux-hardware.org/?probe=83d74c1e9d) | Sep 17, 2023 |
| ASUSTek       | K52JT                       | [5cf28fa81f](https://linux-hardware.org/?probe=5cf28fa81f) | Sep 16, 2023 |
| HP            | EliteBook 725 G3            | [6086fd0180](https://linux-hardware.org/?probe=6086fd0180) | Sep 16, 2023 |
| Lenovo        | ThinkPad T420 4236B27       | [8cd0ed072f](https://linux-hardware.org/?probe=8cd0ed072f) | Sep 16, 2023 |
| Compaq        | 420                         | [a0ce747ff2](https://linux-hardware.org/?probe=a0ce747ff2) | Sep 16, 2023 |
| HP            | 15                          | [636b9a80a1](https://linux-hardware.org/?probe=636b9a80a1) | Sep 15, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/OpenMandriva/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| OpenMandriva 4.2    | 2223      | 26.45%  |
| OpenMandriva 4.3    | 2182      | 25.96%  |
| OpenMandriva 23.03  | 965       | 11.48%  |
| OpenMandriva 23.01  | 964       | 11.47%  |
| OpenMandriva 23.08  | 731       | 8.7%    |
| OpenMandriva 4.50   | 421       | 5.01%   |
| OpenMandriva 5.0    | 262       | 3.12%   |
| OpenMandriva 4.90   | 168       | 2%      |
| OpenMandriva 23.11  | 91        | 1.08%   |
| OpenMandriva 23.09  | 88        | 1.05%   |
| OpenMandriva 23.07  | 66        | 0.79%   |
| OpenMandriva 23.06  | 61        | 0.73%   |
| OpenMandriva 23.90  | 59        | 0.7%    |
| OpenMandriva 23.10  | 49        | 0.58%   |
| OpenMandriva 22.12  | 32        | 0.38%   |
| OpenMandriva 24.01  | 29        | 0.34%   |
| OpenMandriva 4.1    | 4         | 0.05%   |
| OpenMandriva 22.90  | 4         | 0.05%   |
| OpenMandriva 3.0    | 3         | 0.04%   |
| OpenMandriva 24.90  | 2         | 0.02%   |
| OpenMandriva 22.11  | 1         | 0.01%   |
| OpenMandriva 2014.0 | 1         | 0.01%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| OpenMandriva | 7825      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                       | Notebooks | Percent |
|-------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002      | 2137      | 25.22%  |
| 5.16.7-desktop-1omv4003       | 2044      | 24.12%  |
| 6.2.6-desktop-1omv2390        | 932       | 11%     |
| 6.1.1-desktop-1omv2290        | 891       | 10.51%  |
| 6.4.11-desktop-1omv2390       | 604       | 7.13%   |
| 6.6.2-desktop-1omv2390        | 341       | 4.02%   |
| 5.16.13-desktop-1omv4003      | 153       | 1.81%   |
| 5.12.4-desktop-1omv4050       | 149       | 1.76%   |
| 6.4.8-desktop-2omv2390        | 148       | 1.75%   |
| 5.18.12-desktop-3omv4090      | 133       | 1.57%   |
| 6.3.5-desktop-3omv2390        | 120       | 1.42%   |
| 5.11.12-desktop-1omv4002      | 102       | 1.2%    |
| 5.14.7-desktop-1omv4050       | 83        | 0.98%   |
| 5.19.5-desktop-1omv4090       | 77        | 0.91%   |
| 5.19.12-desktop-2omv4090      | 63        | 0.74%   |
| 6.5.5-desktop-1omv2390        | 62        | 0.73%   |
| 6.1.4-desktop-1omv2301        | 62        | 0.73%   |
| 6.5.0-desktop-1omv2390        | 39        | 0.46%   |
| 6.0.10-desktop-2omv22090      | 34        | 0.4%    |
| 6.5.3-desktop-1omv2390        | 27        | 0.32%   |
| 6.2.2-desktop-1omv2390        | 23        | 0.27%   |
| 5.14.14-desktop-1omv4050      | 19        | 0.22%   |
| 6.6.1-desktop-1omv2390        | 18        | 0.21%   |
| 6.0.2-desktop-1omv4090        | 15        | 0.18%   |
| 5.17.1-desktop-2omv4050       | 15        | 0.18%   |
| 6.5.1-desktop-1omv2390        | 14        | 0.17%   |
| 6.6.0-desktop-1omv2390        | 13        | 0.15%   |
| 5.12.7-desktop-1omv4003       | 11        | 0.13%   |
| 6.2.1-desktop-1omv2390        | 9         | 0.11%   |
| 6.5.2-desktop-1omv2390        | 8         | 0.09%   |
| 6.0.2-desktop-1omv4050        | 6         | 0.07%   |
| 5.19.11-desktop-2omv4090      | 6         | 0.07%   |
| 5.19.1-desktop-1omv4090       | 5         | 0.06%   |
| 5.11.0-desktop-clang-1omv4002 | 5         | 0.06%   |
| 6.4.3-desktop-2omv2390        | 4         | 0.05%   |
| 6.4.0-desktop-0.rc3.1omv2390  | 4         | 0.05%   |
| 6.1.2-desktop-1omv2301        | 4         | 0.05%   |
| 6.4.7-desktop-1omv2390        | 3         | 0.04%   |
| 6.2.8-desktop-1omv2390        | 3         | 0.04%   |
| 6.2.7-desktop-1omv2390        | 3         | 0.04%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.14 | 2137      | 25.22%  |
| 5.16.7  | 2045      | 24.13%  |
| 6.2.6   | 932       | 11%     |
| 6.1.1   | 891       | 10.51%  |
| 6.4.11  | 604       | 7.13%   |
| 6.6.2   | 341       | 4.02%   |
| 5.16.13 | 154       | 1.82%   |
| 5.12.4  | 149       | 1.76%   |
| 6.4.8   | 148       | 1.75%   |
| 5.18.12 | 133       | 1.57%   |
| 6.3.5   | 120       | 1.42%   |
| 5.11.12 | 102       | 1.2%    |
| 5.14.7  | 83        | 0.98%   |
| 5.19.5  | 77        | 0.91%   |
| 6.1.4   | 63        | 0.74%   |
| 5.19.12 | 63        | 0.74%   |
| 6.5.5   | 62        | 0.73%   |
| 6.5.0   | 41        | 0.48%   |
| 6.0.10  | 34        | 0.4%    |
| 6.5.3   | 27        | 0.32%   |
| 6.2.2   | 23        | 0.27%   |
| 6.0.2   | 21        | 0.25%   |
| 5.14.14 | 19        | 0.22%   |
| 6.6.1   | 18        | 0.21%   |
| 5.17.1  | 17        | 0.2%    |
| 6.6.0   | 15        | 0.18%   |
| 6.5.1   | 14        | 0.17%   |
| 5.12.7  | 12        | 0.14%   |
| 6.2.1   | 9         | 0.11%   |
| 6.5.2   | 8         | 0.09%   |
| 5.11.0  | 7         | 0.08%   |
| 5.19.11 | 6         | 0.07%   |
| 5.19.1  | 5         | 0.06%   |
| 6.4.3   | 4         | 0.05%   |
| 6.4.0   | 4         | 0.05%   |
| 6.1.2   | 4         | 0.05%   |
| 5.16.9  | 4         | 0.05%   |
| 6.7.0   | 3         | 0.04%   |
| 6.4.7   | 3         | 0.04%   |
| 6.2.8   | 3         | 0.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.16    | 2175      | 25.78%  |
| 5.10    | 2139      | 25.35%  |
| 6.2     | 974       | 11.54%  |
| 6.1     | 963       | 11.41%  |
| 6.4     | 764       | 9.06%   |
| 6.6     | 377       | 4.47%   |
| 5.12    | 161       | 1.91%   |
| 5.19    | 156       | 1.85%   |
| 6.5     | 152       | 1.8%    |
| 5.18    | 139       | 1.65%   |
| 6.3     | 124       | 1.47%   |
| 5.11    | 113       | 1.34%   |
| 5.14    | 102       | 1.21%   |
| 6.0     | 62        | 0.73%   |
| 5.17    | 17        | 0.2%    |
| 6.7     | 4         | 0.05%   |
| 5.5     | 4         | 0.05%   |
| 5.9     | 2         | 0.02%   |
| 5.15    | 2         | 0.02%   |
| 4.19    | 2         | 0.02%   |
| 5.8     | 1         | 0.01%   |
| 5.13    | 1         | 0.01%   |
| 4.9     | 1         | 0.01%   |
| 4.1     | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 7824      | 99.99%  |
| Unknown | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| KDE5     | 7358      | 92.92%  |
| GNOME    | 305       | 3.85%   |
| LXQt     | 192       | 2.42%   |
| Unknown  | 35        | 0.44%   |
| Cinnamon | 12        | 0.15%   |
| Budgie   | 9         | 0.11%   |
| XFCE     | 6         | 0.08%   |
| KDE4     | 1         | 0.01%   |
| DWM      | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 6641      | 82.27%  |
| Wayland | 1429      | 17.7%   |
| Tty     | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 7562      | 95.89%  |
| GDM     | 305       | 3.87%   |
| LightDM | 15        | 0.19%   |
| Unknown | 3         | 0.04%   |
| KDM     | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 4150      | 51.75%  |
| de_DE   | 592       | 7.38%   |
| fr_FR   | 504       | 6.29%   |
| pl_PL   | 359       | 4.48%   |
| ru_RU   | 343       | 4.28%   |
| pt_BR   | 342       | 4.26%   |
| en_GB   | 256       | 3.19%   |
| it_IT   | 244       | 3.04%   |
| cs_CZ   | 193       | 2.41%   |
| es_ES   | 176       | 2.19%   |
| es_MX   | 93        | 1.16%   |
| es_AR   | 50        | 0.62%   |
| en_CA   | 46        | 0.57%   |
| hu_HU   | 45        | 0.56%   |
| de_AT   | 44        | 0.55%   |
| nl_NL   | 38        | 0.47%   |
| en_IN   | 37        | 0.46%   |
| pt_PT   | 33        | 0.41%   |
| en_AU   | 33        | 0.41%   |
| tr_TR   | 30        | 0.37%   |
| es_CL   | 30        | 0.37%   |
| es_CO   | 28        | 0.35%   |
| fr_BE   | 26        | 0.32%   |
| de_CH   | 24        | 0.3%    |
| nl_BE   | 22        | 0.27%   |
| fr_CA   | 21        | 0.26%   |
| ro_RO   | 20        | 0.25%   |
| fr_CH   | 19        | 0.24%   |
| da_DK   | 19        | 0.24%   |
| es_PE   | 16        | 0.2%    |
| es_VE   | 14        | 0.17%   |
| en_NZ   | 14        | 0.17%   |
| Unknown | 11        | 0.14%   |
| ru_UA   | 10        | 0.12%   |
| nb_NO   | 9         | 0.11%   |
| es_UY   | 9         | 0.11%   |
| ja_JP   | 7         | 0.09%   |
| es_CR   | 7         | 0.09%   |
| en_IE   | 7         | 0.09%   |
| en_AG   | 7         | 0.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 4227      | 53.66%  |
| BIOS | 3651      | 46.34%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Overlay  | 5315      | 65.13%  |
| Ext4     | 2576      | 31.56%  |
| Btrfs    | 179       | 2.19%   |
| Xfs      | 38        | 0.47%   |
| F2fs     | 38        | 0.47%   |
| Ext2     | 7         | 0.09%   |
| Unknown  | 4         | 0.05%   |
| Ext3     | 2         | 0.02%   |
| Reiserfs | 1         | 0.01%   |
| Jfs      | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 5448      | 68.74%  |
| MBR     | 2469      | 31.15%  |
| Unknown | 9         | 0.11%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 4161      | 51.79%  |
| Yes       | 3873      | 48.21%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 4689      | 59.28%  |
| Yes       | 3221      | 40.72%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo                | 1542      | 19.71%  |
| Hewlett-Packard       | 1371      | 17.52%  |
| Dell                  | 1145      | 14.63%  |
| ASUSTek Computer      | 959       | 12.26%  |
| Acer                  | 850       | 10.86%  |
| Toshiba               | 372       | 4.75%   |
| Samsung Electronics   | 178       | 2.27%   |
| Sony                  | 164       | 2.1%    |
| Apple                 | 142       | 1.81%   |
| MSI                   | 128       | 1.64%   |
| Fujitsu               | 101       | 1.29%   |
| Packard Bell          | 68        | 0.87%   |
| Positivo              | 60        | 0.77%   |
| Medion                | 57        | 0.73%   |
| HUAWEI                | 48        | 0.61%   |
| Unknown               | 37        | 0.47%   |
| Notebook              | 35        | 0.45%   |
| eMachines             | 32        | 0.41%   |
| TUXEDO                | 29        | 0.37%   |
| Google                | 29        | 0.37%   |
| Chuwi                 | 29        | 0.37%   |
| Fujitsu Siemens       | 26        | 0.33%   |
| LG Electronics        | 25        | 0.32%   |
| Philco                | 24        | 0.31%   |
| Alienware             | 17        | 0.22%   |
| Gateway               | 16        | 0.2%    |
| Compaq                | 15        | 0.19%   |
| Clevo                 | 14        | 0.18%   |
| NEC Computers         | 12        | 0.15%   |
| Intel                 | 12        | 0.15%   |
| GPU Company           | 12        | 0.15%   |
| Timi                  | 11        | 0.14%   |
| System76              | 11        | 0.14%   |
| Panasonic             | 11        | 0.14%   |
| Gigabyte Technology   | 11        | 0.14%   |
| UMAX                  | 8         | 0.1%    |
| Positivo Bahia - VAIO | 8         | 0.1%    |
| Teclast               | 7         | 0.09%   |
| Wortmann AG           | 6         | 0.08%   |
| PC Specialist         | 6         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| ASUS UX31E                     | 126       | 1.61%   |
| Unknown                        | 80        | 1.02%   |
| HP Notebook                    | 73        | 0.93%   |
| HP Pavilion g6                 | 37        | 0.47%   |
| Dell Inspiron 3451             | 32        | 0.41%   |
| Dell Latitude 3310             | 29        | 0.37%   |
| HP Pavilion dv6                | 28        | 0.36%   |
| Dell Latitude E6430            | 28        | 0.36%   |
| Toshiba dynabook T653/46JR     | 24        | 0.31%   |
| Dell Latitude E6410            | 23        | 0.29%   |
| Sony VGN-FZ31Z                 | 22        | 0.28%   |
| HP Pavilion 15                 | 22        | 0.28%   |
| Dell Latitude E6400            | 21        | 0.27%   |
| Dell Inspiron 15-3567          | 20        | 0.26%   |
| HP 15                          | 19        | 0.24%   |
| Dell Inspiron 1545             | 19        | 0.24%   |
| Lenovo IdeaPad 3 15ADA05 81W1  | 18        | 0.23%   |
| Dell Latitude E6420            | 18        | 0.23%   |
| Positivo Mobile                | 17        | 0.22%   |
| Lenovo IdeaPad S145-15AST 81N3 | 17        | 0.22%   |
| HP Pavilion Notebook           | 17        | 0.22%   |
| Dell Latitude D630             | 17        | 0.22%   |
| Apple MacBookPro9,2            | 17        | 0.22%   |
| Lenovo IdeaPad 1 14ADA05 82GW  | 16        | 0.2%    |
| ASUS S551LN                    | 16        | 0.2%    |
| Apple MacBookPro8,1            | 16        | 0.2%    |
| Dell Latitude E7450            | 15        | 0.19%   |
| Dell Latitude E7440            | 15        | 0.19%   |
| Dell Latitude 7490             | 15        | 0.19%   |
| HP Pavilion dv7                | 14        | 0.18%   |
| HP EliteBook 8440p             | 14        | 0.18%   |
| Dell Latitude E6440            | 14        | 0.18%   |
| Lenovo IdeaPad 330S-15IKB 81F5 | 13        | 0.17%   |
| HP Laptop 15-db0xxx            | 13        | 0.17%   |
| HP EliteBook 840 G3            | 13        | 0.17%   |
| HP Compaq Presario CQ60        | 13        | 0.17%   |
| Dell Latitude E5470            | 13        | 0.17%   |
| Toshiba Satellite C660         | 12        | 0.15%   |
| Lenovo IdeaPad 330-15IKB 81DE  | 12        | 0.15%   |
| HP Laptop 15s-eq2xxx           | 12        | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 659       | 8.42%   |
| Acer Aspire           | 621       | 7.94%   |
| Dell Latitude         | 544       | 6.95%   |
| Lenovo IdeaPad        | 468       | 5.98%   |
| Dell Inspiron         | 359       | 4.59%   |
| Toshiba Satellite     | 287       | 3.67%   |
| HP Pavilion           | 279       | 3.57%   |
| HP Laptop             | 219       | 2.8%    |
| HP EliteBook          | 180       | 2.3%    |
| ASUS VivoBook         | 172       | 2.2%    |
| HP ProBook            | 160       | 2.04%   |
| ASUS UX31E            | 126       | 1.61%   |
| HP Compaq             | 110       | 1.41%   |
| Unknown               | 80        | 1.02%   |
| Fujitsu LIFEBOOK      | 77        | 0.98%   |
| HP Notebook           | 73        | 0.93%   |
| Dell Precision        | 61        | 0.78%   |
| Packard Bell EasyNote | 58        | 0.74%   |
| Dell Vostro           | 56        | 0.72%   |
| Dell XPS              | 53        | 0.68%   |
| Acer Nitro            | 50        | 0.64%   |
| Toshiba dynabook      | 49        | 0.63%   |
| Acer TravelMate       | 45        | 0.58%   |
| Acer Extensa          | 42        | 0.54%   |
| HP 250                | 37        | 0.47%   |
| Lenovo Legion         | 34        | 0.43%   |
| Acer Swift            | 34        | 0.43%   |
| Lenovo Yoga           | 33        | 0.42%   |
| HP 255                | 30        | 0.38%   |
| HP 15                 | 28        | 0.36%   |
| HP Stream             | 27        | 0.35%   |
| HP ENVY               | 26        | 0.33%   |
| Dell Studio           | 25        | 0.32%   |
| ASUS ROG              | 25        | 0.32%   |
| Dell System           | 24        | 0.31%   |
| Sony VGN-FZ31Z        | 22        | 0.28%   |
| ASUS ZenBook          | 22        | 0.28%   |
| HP OMEN               | 21        | 0.27%   |
| HP Presario           | 20        | 0.26%   |
| ASUS TUF              | 20        | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 889       | 11.36%  |
| 2012    | 722       | 9.23%   |
| 2013    | 605       | 7.73%   |
| 2010    | 543       | 6.94%   |
| 2014    | 537       | 6.86%   |
| 2019    | 523       | 6.68%   |
| 2020    | 505       | 6.45%   |
| 2021    | 477       | 6.1%    |
| 2018    | 454       | 5.8%    |
| 2008    | 448       | 5.73%   |
| 2015    | 446       | 5.7%    |
| 2016    | 424       | 5.42%   |
| 2017    | 402       | 5.14%   |
| 2009    | 326       | 4.17%   |
| 2007    | 266       | 3.4%    |
| 2022    | 168       | 2.15%   |
| 2023    | 38        | 0.49%   |
| 2006    | 38        | 0.49%   |
| Unknown | 8         | 0.1%    |
| 2005    | 3         | 0.04%   |
| 2004    | 3         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 7825      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 7825      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 7780      | 99.41%  |
| Yes  | 46        | 0.59%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 2638      | 33.39%  |
| 4.01-8.0    | 2554      | 32.33%  |
| 8.01-16.0   | 1106      | 14%     |
| 16.01-24.0  | 807       | 10.22%  |
| 1.01-2.0    | 336       | 4.25%   |
| 32.01-64.0  | 204       | 2.58%   |
| 2.01-3.0    | 162       | 2.05%   |
| 24.01-32.0  | 41        | 0.52%   |
| 64.01-256.0 | 35        | 0.44%   |
| 0.51-1.0    | 16        | 0.2%    |
| Unknown     | 1         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 6008      | 73.97%  |
| 2.01-3.0  | 1102      | 13.57%  |
| 0.51-1.0  | 743       | 9.15%   |
| 3.01-4.0  | 159       | 1.96%   |
| 0.01-0.5  | 65        | 0.8%    |
| 4.01-8.0  | 40        | 0.49%   |
| 8.01-16.0 | 4         | 0.05%   |
| Unknown   | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 5767      | 72.83%  |
| 2      | 1781      | 22.49%  |
| 3      | 228       | 2.88%   |
| 0      | 111       | 1.4%    |
| 4      | 27        | 0.34%   |
| 5      | 2         | 0.03%   |
| 13     | 1         | 0.01%   |
| 7      | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 4113      | 52.32%  |
| Yes       | 3748      | 47.68%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 6685      | 85.41%  |
| No        | 1142      | 14.59%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 7752      | 99.03%  |
| No        | 76        | 0.97%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 5649      | 71.86%  |
| No        | 2212      | 28.14%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 900       | 11.48%  |
| Germany     | 846       | 10.79%  |
| France      | 575       | 7.33%   |
| Brazil      | 541       | 6.9%    |
| Poland      | 491       | 6.26%   |
| Russia      | 436       | 5.56%   |
| Italy       | 372       | 4.74%   |
| UK          | 280       | 3.57%   |
| Spain       | 248       | 3.16%   |
| Czechia     | 228       | 2.91%   |
| Canada      | 194       | 2.47%   |
| Netherlands | 163       | 2.08%   |
| Mexico      | 146       | 1.86%   |
| Japan       | 140       | 1.79%   |
| India       | 128       | 1.63%   |
| Indonesia   | 99        | 1.26%   |
| Australia   | 92        | 1.17%   |
| Romania     | 89        | 1.13%   |
| Portugal    | 89        | 1.13%   |
| Belgium     | 84        | 1.07%   |
| Finland     | 78        | 0.99%   |
| Hungary     | 77        | 0.98%   |
| Switzerland | 73        | 0.93%   |
| Turkey      | 71        | 0.91%   |
| Argentina   | 67        | 0.85%   |
| Sweden      | 64        | 0.82%   |
| Austria     | 61        | 0.78%   |
| Ukraine     | 58        | 0.74%   |
| Colombia    | 57        | 0.73%   |
| Greece      | 51        | 0.65%   |
| Bulgaria    | 45        | 0.57%   |
| Slovakia    | 44        | 0.56%   |
| Chile       | 44        | 0.56%   |
| China       | 37        | 0.47%   |
| Norway      | 35        | 0.45%   |
| New Zealand | 34        | 0.43%   |
| Serbia      | 33        | 0.42%   |
| Denmark     | 32        | 0.41%   |
| Peru        | 31        | 0.4%    |
| Algeria     | 31        | 0.4%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Prague         | 136       | 1.66%   |
| Warsaw         | 95        | 1.16%   |
| Moscow         | 82        | 1%      |
| Paris          | 75        | 0.92%   |
| Berlin         | 61        | 0.74%   |
| Milan          | 60        | 0.73%   |
| Schagen        | 56        | 0.68%   |
| Krakow         | 53        | 0.65%   |
| Sao Paulo      | 45        | 0.55%   |
| Munich         | 44        | 0.54%   |
| St Petersburg  | 40        | 0.49%   |
| Rome           | 37        | 0.45%   |
| Vienna         | 36        | 0.44%   |
| Rio de Janeiro | 31        | 0.38%   |
| Mexico City    | 31        | 0.38%   |
| Helsinki       | 31        | 0.38%   |
| Madrid         | 28        | 0.34%   |
| Hamburg        | 28        | 0.34%   |
| Sydney         | 26        | 0.32%   |
| Stuttgart      | 25        | 0.31%   |
| Budapest       | 25        | 0.31%   |
| Poznan         | 24        | 0.29%   |
| Bucharest      | 24        | 0.29%   |
| Bengaluru      | 24        | 0.29%   |
| Barcelona      | 24        | 0.29%   |
| Athens         | 24        | 0.29%   |
| Wroclaw        | 23        | 0.28%   |
| Cologne        | 23        | 0.28%   |
| Krasnodar      | 22        | 0.27%   |
| Jakarta        | 22        | 0.27%   |
| Istanbul       | 22        | 0.27%   |
| Funchal        | 22        | 0.27%   |
| Bogotá        | 20        | 0.24%   |
| Melbourne      | 19        | 0.23%   |
| London         | 18        | 0.22%   |
| Lima           | 18        | 0.22%   |
| Buenos Aires   | 18        | 0.22%   |
| Brisbane       | 18        | 0.22%   |
| Belgrade       | 17        | 0.21%   |
| Katowice       | 16        | 0.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1335      | 1478   | 14.09%  |
| Samsung Electronics | 1106      | 1285   | 11.68%  |
| Seagate             | 1092      | 1206   | 11.53%  |
| Toshiba             | 839       | 922    | 8.86%   |
| Kingston            | 560       | 604    | 5.91%   |
| SanDisk             | 522       | 564    | 5.51%   |
| Hitachi             | 425       | 459    | 4.49%   |
| Unknown             | 372       | 406    | 3.93%   |
| Crucial             | 353       | 403    | 3.73%   |
| HGST                | 289       | 317    | 3.05%   |
| SK hynix            | 260       | 288    | 2.74%   |
| Intel               | 181       | 212    | 1.91%   |
| A-DATA Technology   | 166       | 180    | 1.75%   |
| Micron Technology   | 156       | 173    | 1.65%   |
| China               | 114       | 122    | 1.2%    |
| Unknown             | 84        | 90     | 0.89%   |
| GOODRAM             | 77        | 83     | 0.81%   |
| SPCC                | 73        | 78     | 0.77%   |
| Apple               | 73        | 81     | 0.77%   |
| Fujitsu             | 68        | 73     | 0.72%   |
| PNY                 | 67        | 75     | 0.71%   |
| Intenso             | 66        | 72     | 0.7%    |
| JMicron Technology  | 64        | 67     | 0.68%   |
| KIOXIA              | 62        | 67     | 0.65%   |
| LITEON              | 60        | 62     | 0.63%   |
| Transcend           | 50        | 51     | 0.53%   |
| Patriot             | 49        | 53     | 0.52%   |
| Phison              | 44        | 47     | 0.46%   |
| SSSTC               | 32        | 40     | 0.34%   |
| Netac               | 31        | 36     | 0.33%   |
| KingSpec            | 31        | 32     | 0.33%   |
| Silicon Motion      | 29        | 34     | 0.31%   |
| UMIS                | 27        | 29     | 0.29%   |
| LITEONIT            | 26        | 32     | 0.27%   |
| Apacer              | 26        | 26     | 0.27%   |
| Lexar               | 24        | 26     | 0.25%   |
| OCZ                 | 23        | 24     | 0.24%   |
| Gigabyte Technology | 23        | 25     | 0.24%   |
| ASMT                | 23        | 24     | 0.24%   |
| SABRENT             | 21        | 27     | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST500LT012-1DG142 500GB     | 146       | 1.51%   |
| SanDisk SSD U100 256GB              | 126       | 1.3%    |
| Kingston SA400S37240G 240GB SSD     | 120       | 1.24%   |
| Toshiba MQ01ABF050 500GB            | 115       | 1.19%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 115       | 1.19%   |
| Toshiba MQ01ABD100 1TB              | 109       | 1.13%   |
| Seagate ST1000LM035-1RK172 1TB      | 102       | 1.05%   |
| Toshiba MQ04ABF100 1TB              | 92        | 0.95%   |
| Unknown                             | 84        | 0.87%   |
| Seagate ST9500325AS 500GB           | 81        | 0.84%   |
| Kingston SA400S37480G 480GB SSD     | 75        | 0.78%   |
| HGST HTS545050A7E680 500GB          | 63        | 0.65%   |
| HGST HTS721010A9E630 1TB            | 55        | 0.57%   |
| Crucial CT240BX500SSD1 240GB        | 55        | 0.57%   |
| Samsung SSD 860 EVO 500GB           | 54        | 0.56%   |
| Kingston SA400S37120G 120GB SSD     | 53        | 0.55%   |
| HGST HTS541010A9E680 1TB            | 52        | 0.54%   |
| WDC WD10JPVX-22JC3T0 1TB            | 51        | 0.53%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 50        | 0.52%   |
| Toshiba MQ01ABD075 752GB            | 47        | 0.49%   |
| Crucial CT500MX500SSD1 500GB        | 44        | 0.45%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 42        | 0.43%   |
| Unknown SD/MMC/MS PRO 256GB         | 40        | 0.41%   |
| Kingston SV300S37A120G 120GB SSD    | 39        | 0.4%    |
| Seagate ST500LT012-9WS142 500GB     | 36        | 0.37%   |
| Hitachi HTS543232A7A384 320GB       | 35        | 0.36%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 34        | 0.35%   |
| HGST HTS545050A7E380 500GB          | 34        | 0.35%   |
| WDC WD10SPZX-21Z10T0 1TB            | 33        | 0.34%   |
| Seagate ST9320325AS 320GB           | 32        | 0.33%   |
| Samsung SSD 850 EVO 500GB           | 32        | 0.33%   |
| Samsung SSD 850 EVO 250GB           | 32        | 0.33%   |
| JMicron Generic 8GB                 | 32        | 0.33%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 31        | 0.32%   |
| Crucial CT1000MX500SSD1 1TB         | 31        | 0.32%   |
| Toshiba MQ01ABD050 500GB            | 30        | 0.31%   |
| Hitachi HTS547550A9E384 500GB       | 29        | 0.3%    |
| SanDisk DF4032  32GB                | 28        | 0.29%   |
| Crucial CT480BX500SSD1 480GB        | 28        | 0.29%   |
| Crucial CT1000BX500SSD1 1TB         | 28        | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1071      | 1173   | 28.89%  |
| WDC                 | 932       | 1017   | 25.14%  |
| Toshiba             | 718       | 784    | 19.37%  |
| Hitachi             | 425       | 459    | 11.46%  |
| HGST                | 289       | 317    | 7.8%    |
| Samsung Electronics | 76        | 79     | 2.05%   |
| Fujitsu             | 68        | 73     | 1.83%   |
| Unknown             | 40        | 40     | 1.08%   |
| JMicron Technology  | 32        | 33     | 0.86%   |
| Apple               | 15        | 15     | 0.4%    |
| External            | 8         | 8      | 0.22%   |
| TO Exter            | 5         | 5      | 0.13%   |
| SAGE                | 5         | 5      | 0.13%   |
| SSK                 | 3         | 4      | 0.08%   |
| HGST HTS            | 3         | 3      | 0.08%   |
| SABRENT             | 2         | 3      | 0.05%   |
| Intenso             | 2         | 2      | 0.05%   |
| Inateck             | 2         | 2      | 0.05%   |
| Hewlett-Packard     | 2         | 2      | 0.05%   |
| WD MediaMax         | 1         | 1      | 0.03%   |
| StoreJet            | 1         | 1      | 0.03%   |
| QC-FT-D             | 1         | 1      | 0.03%   |
| MARSHAL             | 1         | 1      | 0.03%   |
| Magnetic Data       | 1         | 1      | 0.03%   |
| LaCie               | 1         | 1      | 0.03%   |
| IBM/Hitachi         | 1         | 1      | 0.03%   |
| ASMT                | 1         | 1      | 0.03%   |
| ASMedia             | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 637       | 715    | 17.39%  |
| Kingston            | 453       | 488    | 12.37%  |
| SanDisk             | 429       | 460    | 11.71%  |
| Crucial             | 307       | 346    | 8.38%   |
| WDC                 | 183       | 190    | 5%      |
| A-DATA Technology   | 131       | 140    | 3.58%   |
| China               | 114       | 122    | 3.11%   |
| SK hynix            | 85        | 92     | 2.32%   |
| Micron Technology   | 80        | 90     | 2.18%   |
| GOODRAM             | 75        | 81     | 2.05%   |
| Toshiba             | 74        | 81     | 2.02%   |
| Intel               | 68        | 75     | 1.86%   |
| SPCC                | 64        | 67     | 1.75%   |
| Intenso             | 59        | 64     | 1.61%   |
| PNY                 | 58        | 63     | 1.58%   |
| LITEON              | 55        | 57     | 1.5%    |
| Patriot             | 48        | 52     | 1.31%   |
| Transcend           | 47        | 48     | 1.28%   |
| Apple               | 41        | 43     | 1.12%   |
| Netac               | 29        | 34     | 0.79%   |
| KingSpec            | 29        | 30     | 0.79%   |
| LITEONIT            | 26        | 32     | 0.71%   |
| Apacer              | 24        | 24     | 0.66%   |
| OCZ                 | 23        | 24     | 0.63%   |
| Unknown             | 22        | 22     | 0.6%    |
| ASMT                | 18        | 19     | 0.49%   |
| SABRENT             | 16        | 20     | 0.44%   |
| Lexar               | 16        | 18     | 0.44%   |
| Hewlett-Packard     | 15        | 16     | 0.41%   |
| Verbatim            | 14        | 17     | 0.38%   |
| Gigabyte Technology | 14        | 14     | 0.38%   |
| Seagate             | 13        | 16     | 0.35%   |
| Plextor             | 11        | 11     | 0.3%    |
| KingDian            | 11        | 12     | 0.3%    |
| JMicron Technology  | 11        | 12     | 0.3%    |
| Unknown             | 10        | 10     | 0.27%   |
| Team                | 10        | 10     | 0.27%   |
| Acer                | 10        | 11     | 0.27%   |
| Teclast             | 9         | 9      | 0.25%   |
| Phison              | 9         | 9      | 0.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 3564      | 4033   | 39.66%  |
| SSD     | 3376      | 3978   | 37.57%  |
| NVMe    | 1532      | 1866   | 17.05%  |
| MMC     | 420       | 476    | 4.67%   |
| Unknown | 94        | 99     | 1.05%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 6268      | 7628   | 72.57%  |
| NVMe | 1531      | 1847   | 17.73%  |
| MMC  | 420       | 476    | 4.86%   |
| SAS  | 418       | 501    | 4.84%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 4992      | 5904   | 73.07%  |
| 0.51-1.0   | 1680      | 1926   | 24.59%  |
| 1.01-2.0   | 137       | 154    | 2.01%   |
| 3.01-4.0   | 15        | 17     | 0.22%   |
| 4.01-10.0  | 6         | 8      | 0.09%   |
| 2.01-3.0   | 2         | 2      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 3908      | 47.49%  |
| 101-250        | 1491      | 18.12%  |
| 251-500        | 997       | 12.12%  |
| 501-1000       | 517       | 6.28%   |
| 51-100         | 461       | 5.6%    |
| 21-50          | 373       | 4.53%   |
| Unknown        | 307       | 3.73%   |
| 1001-2000      | 121       | 1.47%   |
| 2001-3000      | 35        | 0.43%   |
| More than 3000 | 19        | 0.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 6803      | 84.36%  |
| 21-50          | 340       | 4.22%   |
| Unknown        | 307       | 3.81%   |
| 51-100         | 215       | 2.67%   |
| 101-250        | 200       | 2.48%   |
| 251-500        | 110       | 1.36%   |
| 501-1000       | 51        | 0.63%   |
| 1001-2000      | 21        | 0.26%   |
| 0              | 12        | 0.15%   |
| More than 3000 | 3         | 0.04%   |
| 2001-3000      | 2         | 0.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| SanDisk SSD U100 256GB              | 126       | 127    | 6.54%   |
| Seagate ST9500325AS 500GB           | 60        | 63     | 3.11%   |
| Seagate ST500LT012-1DG142 500GB     | 47        | 51     | 2.44%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 43        | 50     | 2.23%   |
| HGST HTS545050A7E680 500GB          | 40        | 43     | 2.07%   |
| Seagate ST500LT012-9WS142 500GB     | 34        | 35     | 1.76%   |
| Toshiba MQ01ABD075 752GB            | 33        | 34     | 1.71%   |
| Toshiba MQ01ABF050 500GB            | 32        | 33     | 1.66%   |
| HGST HTS541010A9E680 1TB            | 32        | 34     | 1.66%   |
| Seagate ST9320325AS 320GB           | 27        | 27     | 1.4%    |
| Toshiba MQ01ABD100 1TB              | 26        | 28     | 1.35%   |
| Seagate ST1000LM035-1RK172 1TB      | 22        | 23     | 1.14%   |
| Hitachi HTS543232A7A384 320GB       | 21        | 22     | 1.09%   |
| HGST HTS545050A7E380 500GB          | 20        | 21     | 1.04%   |
| Toshiba MQ01ABD050 500GB            | 19        | 20     | 0.99%   |
| Hitachi HTS545050A7E380 500GB       | 19        | 21     | 0.99%   |
| HGST HTS721010A9E630 1TB            | 17        | 18     | 0.88%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 16        | 18     | 0.83%   |
| Crucial CT240M500SSD1 240GB         | 16        | 17     | 0.83%   |
| Hitachi HTS547550A9E384 500GB       | 14        | 15     | 0.73%   |
| HGST HTS725050A7E630 500GB          | 14        | 14     | 0.73%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 13        | 14     | 0.67%   |
| Kingston SV300S37A120G 120GB SSD    | 13        | 13     | 0.67%   |
| Hitachi HTS547575A9E384 752GB       | 13        | 14     | 0.67%   |
| WDC WD10JPVX-22JC3T0 1TB            | 12        | 12     | 0.62%   |
| Toshiba MK3265GSX 320GB             | 12        | 13     | 0.62%   |
| Seagate ST500LM021-1KJ152 500GB     | 12        | 12     | 0.62%   |
| Seagate ST9500420AS 500GB           | 11        | 11     | 0.57%   |
| Seagate ST9250827AS 250GB           | 11        | 14     | 0.57%   |
| Hitachi HTS547564A9E384 640GB       | 11        | 12     | 0.57%   |
| Hitachi HTS545050B9A300 500GB       | 11        | 14     | 0.57%   |
| HGST HTS541075A9E680 752GB          | 11        | 13     | 0.57%   |
| Hitachi HTS542516K9SA00 160GB       | 10        | 10     | 0.52%   |
| Toshiba MK2555GSX 250GB             | 9         | 9      | 0.47%   |
| Seagate ST9250315AS 250GB           | 9         | 10     | 0.47%   |
| Seagate ST500LM000-1EJ162 500GB     | 9         | 10     | 0.47%   |
| Seagate ST320LT007-9ZV142 320GB     | 9         | 10     | 0.47%   |
| Hitachi HTS545032B9A300 320GB       | 9         | 9      | 0.47%   |
| Toshiba MQ04ABF100 1TB              | 8         | 8      | 0.41%   |
| Seagate ST9250410AS 250GB           | 8         | 9      | 0.41%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 442       | 477    | 23%     |
| Toshiba             | 298       | 315    | 15.5%   |
| WDC                 | 265       | 282    | 13.79%  |
| Hitachi             | 240       | 259    | 12.49%  |
| SanDisk             | 159       | 161    | 8.27%   |
| HGST                | 150       | 161    | 7.8%    |
| Samsung Electronics | 63        | 68     | 3.28%   |
| Kingston            | 42        | 44     | 2.19%   |
| Crucial             | 38        | 40     | 1.98%   |
| SK hynix            | 33        | 35     | 1.72%   |
| Intel               | 25        | 28     | 1.3%    |
| Fujitsu             | 25        | 29     | 1.3%    |
| A-DATA Technology   | 19        | 23     | 0.99%   |
| China               | 16        | 16     | 0.83%   |
| Micron Technology   | 14        | 15     | 0.73%   |
| LITEON              | 8         | 8      | 0.42%   |
| Apple               | 7         | 7      | 0.36%   |
| OCZ                 | 6         | 7      | 0.31%   |
| SPCC                | 5         | 5      | 0.26%   |
| KingSpec            | 5         | 5      | 0.26%   |
| LITEONIT            | 4         | 5      | 0.21%   |
| Transcend           | 3         | 4      | 0.16%   |
| Plextor             | 3         | 3      | 0.16%   |
| Netac               | 3         | 3      | 0.16%   |
| Intenso             | 3         | 4      | 0.16%   |
| Dogfish             | 3         | 3      | 0.16%   |
| Teclast             | 2         | 2      | 0.1%    |
| PNY                 | 2         | 3      | 0.1%    |
| JMicron Technology  | 2         | 2      | 0.1%    |
| Hewlett-Packard     | 2         | 2      | 0.1%    |
| Corsair             | 2         | 3      | 0.1%    |
| ASMT                | 2         | 2      | 0.1%    |
| ASMedia             | 2         | 2      | 0.1%    |
| XrayDisk            | 1         | 1      | 0.05%   |
| Wibtek              | 1         | 1      | 0.05%   |
| Vaseky              | 1         | 1      | 0.05%   |
| USB                 | 1         | 1      | 0.05%   |
| Unknown             | 1         | 1      | 0.05%   |
| Union Memory        | 1         | 1      | 0.05%   |
| Team                | 1         | 1      | 0.05%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 441       | 476    | 30.71%  |
| Toshiba             | 292       | 309    | 20.33%  |
| WDC                 | 242       | 258    | 16.85%  |
| Hitachi             | 240       | 259    | 16.71%  |
| HGST                | 150       | 161    | 10.45%  |
| Samsung Electronics | 40        | 42     | 2.79%   |
| Fujitsu             | 25        | 29     | 1.74%   |
| Apple               | 3         | 3      | 0.21%   |
| Magnetic Data       | 1         | 1      | 0.07%   |
| IBM/Hitachi         | 1         | 1      | 0.07%   |
| ASMedia             | 1         | 1      | 0.07%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1418      | 1540   | 74.59%  |
| SSD     | 456       | 484    | 23.99%  |
| NVMe    | 25        | 28     | 1.32%   |
| Unknown | 2         | 2      | 0.11%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD3200BEVT-11ZCT0 320GB           | 2         | 2      | 4.08%   |
| WDC WD2500BEVS-22UST0 250GB           | 2         | 2      | 4.08%   |
| Toshiba MQ01ABD100 1TB                | 2         | 2      | 4.08%   |
| Hitachi HTS723232A7A364 320GB         | 2         | 2      | 4.08%   |
| Hitachi HTS545050A7E380 500GB         | 2         | 2      | 4.08%   |
| HGST HTS541010A9E680 1TB              | 2         | 2      | 4.08%   |
| Crucial CT500P2SSD8 500GB             | 2         | 2      | 4.08%   |
| WDC WD5000M22K-24Z1LT0-SSHD-16GB      | 1         | 1      | 2.04%   |
| WDC WD5000LPLX-75ZNTT0 500GB          | 1         | 1      | 2.04%   |
| WDC WD5000BPVT-60HXZT1 500GB          | 1         | 1      | 2.04%   |
| WDC WD5000BEVT-22ZAT0 500GB           | 1         | 1      | 2.04%   |
| WDC WD5000BEVT-22A0RT0 500GB          | 1         | 1      | 2.04%   |
| WDC WD3200BUCT-63TWBY0 320GB          | 1         | 1      | 2.04%   |
| WDC WD3200BEKT-60KA9T0 320GB          | 1         | 1      | 2.04%   |
| WDC WD2500BEVT-60ZCT1 250GB           | 1         | 1      | 2.04%   |
| WDC WD2500BEVT-35A23T0 250GB          | 1         | 1      | 2.04%   |
| WDC WD1600BEVT-75A23T0 160GB          | 1         | 1      | 2.04%   |
| WDC WD10JPVX-60JC3T0 1TB              | 1         | 1      | 2.04%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 2.04%   |
| Toshiba MQ01ABD050 500GB              | 1         | 1      | 2.04%   |
| Toshiba MK3265GSXN 320GB              | 1         | 1      | 2.04%   |
| Toshiba MK3261GSYN 320GB              | 1         | 1      | 2.04%   |
| Toshiba MK3259GSXP 320GB              | 1         | 2      | 2.04%   |
| Toshiba MK2575GSX 250GB               | 1         | 1      | 2.04%   |
| Toshiba MK1234GSX 120GB               | 1         | 1      | 2.04%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 1         | 1      | 2.04%   |
| Seagate ST9500420AS 500GB             | 1         | 1      | 2.04%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1         | 1      | 2.04%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1         | 1      | 2.04%   |
| Samsung Electronics SSD PM800 TM 64GB | 1         | 1      | 2.04%   |
| Samsung Electronics HM500JI 500GB     | 1         | 1      | 2.04%   |
| Samsung Electronics HM321HI 320GB     | 1         | 1      | 2.04%   |
| Samsung Electronics HM251JI 250GB     | 1         | 1      | 2.04%   |
| Samsung Electronics HM250HI 250GB     | 1         | 1      | 2.04%   |
| Intel SSDSCKKF256H6 SATA 256GB        | 1         | 1      | 2.04%   |
| Intel SSDSA2BW160G3 160GB             | 1         | 1      | 2.04%   |
| Hitachi HTS545050B9SA00 500GB         | 1         | 1      | 2.04%   |
| Hitachi HTS545032B9A300 320GB         | 1         | 1      | 2.04%   |
| Hitachi HTS545016B9A300 160GB         | 1         | 1      | 2.04%   |
| Hitachi HTS543232A7A384 320GB         | 1         | 1      | 2.04%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 15        | 15     | 30.61%  |
| Toshiba             | 9         | 10     | 18.37%  |
| Hitachi             | 8         | 8      | 16.33%  |
| Samsung Electronics | 5         | 5      | 10.2%   |
| Seagate             | 3         | 3      | 6.12%   |
| HGST                | 3         | 3      | 6.12%   |
| Intel               | 2         | 2      | 4.08%   |
| Crucial             | 2         | 2      | 4.08%   |
| SK hynix            | 1         | 1      | 2.04%   |
| Apple               | 1         | 1      | 2.04%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 5847      | 7380   | 68.21%  |
| Malfunc  | 1880      | 2054   | 21.93%  |
| Detected | 796       | 968    | 9.29%   |
| Failed   | 49        | 50     | 0.57%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 5932      | 68.54%  |
| AMD                                     | 1085      | 12.54%  |
| Samsung Electronics                     | 448       | 5.18%   |
| SanDisk                                 | 284       | 3.28%   |
| SK hynix                                | 160       | 1.85%   |
| Kingston Technology Company             | 116       | 1.34%   |
| Phison Electronics                      | 81        | 0.94%   |
| Micron Technology                       | 78        | 0.9%    |
| Nvidia                                  | 67        | 0.77%   |
| KIOXIA                                  | 65        | 0.75%   |
| Toshiba America Info Systems            | 49        | 0.57%   |
| Silicon Motion                          | 48        | 0.55%   |
| Micron/Crucial Technology               | 46        | 0.53%   |
| Solid State Storage Technology          | 31        | 0.36%   |
| ADATA Technology                        | 31        | 0.36%   |
| Union Memory (Shenzhen)                 | 30        | 0.35%   |
| Realtek Semiconductor                   | 18        | 0.21%   |
| Apple                                   | 13        | 0.15%   |
| Silicon Integrated Systems [SiS]        | 10        | 0.12%   |
| JMicron Technology                      | 10        | 0.12%   |
| MAXIO Technology (Hangzhou)             | 9         | 0.1%    |
| Lenovo                                  | 7         | 0.08%   |
| Shenzhen Longsys Electronics            | 6         | 0.07%   |
| Lite-On Technology                      | 5         | 0.06%   |
| ASMedia Technology                      | 5         | 0.06%   |
| Seagate Technology                      | 4         | 0.05%   |
| Marvell Technology Group                | 4         | 0.05%   |
| Biwin Storage Technology                | 4         | 0.05%   |
| Silicon Image                           | 3         | 0.03%   |
| Yangtze Memory Technologies             | 1         | 0.01%   |
| Transcend                               | 1         | 0.01%   |
| Shenzhen Unionmemory Information System | 1         | 0.01%   |
| Nextorage                               | 1         | 0.01%   |
| Netac Technology                        | 1         | 0.01%   |
| INNOGRIT                                | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 842       | 8.96%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 770       | 8.2%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 653       | 6.95%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 632       | 6.73%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 459       | 4.89%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 429       | 4.57%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 308       | 3.28%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 304       | 3.24%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 277       | 2.95%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 253       | 2.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 241       | 2.57%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 189       | 2.01%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 181       | 1.93%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 174       | 1.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 170       | 1.81%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 162       | 1.72%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 159       | 1.69%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 140       | 1.49%   |
| Intel Volume Management Device NVMe RAID Controller                              | 137       | 1.46%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 112       | 1.19%   |
| Intel Tiger Lake-LP SATA Controller                                              | 103       | 1.1%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 102       | 1.09%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 93        | 0.99%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 91        | 0.97%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 84        | 0.89%   |
| Intel Comet Lake SATA AHCI Controller                                            | 68        | 0.72%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 60        | 0.64%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 60        | 0.64%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 56        | 0.6%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 52        | 0.55%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 51        | 0.54%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 49        | 0.52%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 49        | 0.52%   |
| Intel SSD 660P Series                                                            | 47        | 0.5%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 47        | 0.5%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 46        | 0.49%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 46        | 0.49%   |
| SK hynix BC511 NVMe SSD                                                          | 43        | 0.46%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 39        | 0.42%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 38        | 0.4%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 6288      | 69.31%  |
| NVMe | 1529      | 16.85%  |
| IDE  | 664       | 7.32%   |
| RAID | 591       | 6.51%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 6408      | 81.89%  |
| AMD    | 1417      | 18.11%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-2677M CPU @ 1.80GHz             | 126       | 1.61%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 111       | 1.42%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 99        | 1.26%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 94        | 1.2%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 92        | 1.17%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 88        | 1.12%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 87        | 1.11%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 82        | 1.05%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 80        | 1.02%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 80        | 1.02%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 70        | 0.89%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 70        | 0.89%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 70        | 0.89%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 68        | 0.87%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 66        | 0.84%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 64        | 0.82%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 62        | 0.79%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 62        | 0.79%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 61        | 0.78%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 61        | 0.78%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 60        | 0.77%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 58        | 0.74%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 56        | 0.72%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 55        | 0.7%    |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 54        | 0.69%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 53        | 0.68%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 52        | 0.66%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 52        | 0.66%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 52        | 0.66%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 51        | 0.65%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 48        | 0.61%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 48        | 0.61%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 47        | 0.6%    |
| Intel Core i3-3110M CPU @ 2.40GHz             | 45        | 0.57%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 45        | 0.57%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 42        | 0.54%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 41        | 0.52%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 41        | 0.52%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 41        | 0.52%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 41        | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1912      | 24.42%  |
| Intel Core i7           | 1150      | 14.69%  |
| Intel Core i3           | 927       | 11.84%  |
| Intel Celeron           | 740       | 9.45%   |
| Intel Core 2 Duo        | 579       | 7.4%    |
| Other                   | 374       | 4.78%   |
| Intel Pentium           | 319       | 4.07%   |
| AMD Ryzen 5             | 255       | 3.26%   |
| AMD Ryzen 7             | 193       | 2.47%   |
| Intel Pentium Dual-Core | 127       | 1.62%   |
| AMD A6                  | 104       | 1.33%   |
| AMD Ryzen 3             | 94        | 1.2%    |
| AMD E                   | 85        | 1.09%   |
| Intel Atom              | 79        | 1.01%   |
| AMD E1                  | 77        | 0.98%   |
| Intel Pentium Dual      | 73        | 0.93%   |
| AMD A4                  | 73        | 0.93%   |
| AMD A8                  | 64        | 0.82%   |
| AMD A10                 | 48        | 0.61%   |
| AMD E2                  | 45        | 0.57%   |
| Intel Pentium Silver    | 44        | 0.56%   |
| Intel Genuine           | 43        | 0.55%   |
| AMD Athlon              | 40        | 0.51%   |
| Intel Core 2            | 39        | 0.5%    |
| AMD C-60                | 30        | 0.38%   |
| AMD Ryzen 9             | 27        | 0.34%   |
| Intel Celeron Dual-Core | 26        | 0.33%   |
| AMD Turion 64 X2 Mobile | 19        | 0.24%   |
| AMD Athlon X2           | 16        | 0.2%    |
| AMD Athlon II           | 16        | 0.2%    |
| AMD Ryzen 5 PRO         | 15        | 0.19%   |
| AMD Phenom II           | 14        | 0.18%   |
| AMD A12                 | 12        | 0.15%   |
| AMD Ryzen 7 PRO         | 11        | 0.14%   |
| AMD C-70                | 11        | 0.14%   |
| AMD Athlon II Dual-Core | 10        | 0.13%   |
| Intel Pentium Gold      | 9         | 0.11%   |
| AMD Sempron             | 9         | 0.11%   |
| AMD Athlon 64 X2        | 9         | 0.11%   |
| Intel Core m3           | 8         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 5412      | 69.11%  |
| 4      | 1691      | 21.59%  |
| 6      | 250       | 3.19%   |
| 8      | 229       | 2.92%   |
| 1      | 176       | 2.25%   |
| 14     | 31        | 0.4%    |
| 12     | 18        | 0.23%   |
| 10     | 13        | 0.17%   |
| 3      | 5         | 0.06%   |
| 24     | 3         | 0.04%   |
| 16     | 2         | 0.03%   |
| 5      | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 7825      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 4974      | 63.49%  |
| 1      | 2824      | 36.05%  |
| 4      | 19        | 0.24%   |
| 8      | 14        | 0.18%   |
| 12     | 2         | 0.03%   |
| 16     | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 7822      | 99.96%  |
| Unknown        | 3         | 0.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2111      | 25.93%  |
| 0x206a7    | 720       | 8.85%   |
| 0x306a9    | 533       | 6.55%   |
| 0x1067a    | 348       | 4.28%   |
| 0x20655    | 280       | 3.44%   |
| 0x40651    | 258       | 3.17%   |
| 0x406e3    | 224       | 2.75%   |
| 0x306d4    | 215       | 2.64%   |
| 0x806e9    | 182       | 2.24%   |
| 0x6fd      | 175       | 2.15%   |
| 0x08108109 | 165       | 2.03%   |
| 0x306c3    | 156       | 1.92%   |
| 0x806ea    | 146       | 1.79%   |
| 0x30678    | 142       | 1.74%   |
| 0x806ec    | 128       | 1.57%   |
| 0x10676    | 126       | 1.55%   |
| 0x06006705 | 98        | 1.2%    |
| 0x806c1    | 92        | 1.13%   |
| 0x406c4    | 86        | 1.06%   |
| 0x20652    | 83        | 1.02%   |
| 0x08608103 | 80        | 0.98%   |
| 0x706e5    | 77        | 0.95%   |
| 0x0500010d | 77        | 0.95%   |
| 0x906ea    | 73        | 0.9%    |
| 0x07030105 | 72        | 0.88%   |
| 0x506e3    | 69        | 0.85%   |
| 0x506c9    | 69        | 0.85%   |
| 0x08108102 | 69        | 0.85%   |
| 0x0a50000c | 65        | 0.8%    |
| 0x706a1    | 63        | 0.77%   |
| 0x706a8    | 58        | 0.71%   |
| 0x08600106 | 47        | 0.58%   |
| 0x906e9    | 43        | 0.53%   |
| 0x05000101 | 41        | 0.5%    |
| 0x406c3    | 39        | 0.48%   |
| 0xa0652    | 37        | 0.45%   |
| 0x6fb      | 37        | 0.45%   |
| 0x0700010b | 36        | 0.44%   |
| 0x08200103 | 34        | 0.42%   |
| 0x0600611a | 34        | 0.42%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| SandyBridge      | 884       | 11.29%  |
| KabyLake         | 861       | 11%     |
| IvyBridge        | 692       | 8.84%   |
| Penryn           | 593       | 7.57%   |
| Haswell          | 552       | 7.05%   |
| Westmere         | 478       | 6.1%    |
| Skylake          | 431       | 5.5%    |
| Silvermont       | 372       | 4.75%   |
| Core             | 353       | 4.51%   |
| Broadwell        | 301       | 3.84%   |
| Zen+             | 244       | 3.12%   |
| Goldmont plus    | 190       | 2.43%   |
| TigerLake        | 186       | 2.38%   |
| Bobcat           | 174       | 2.22%   |
| Excavator        | 161       | 2.06%   |
| Unknown          | 159       | 2.03%   |
| IceLake          | 137       | 1.75%   |
| Puma             | 110       | 1.4%    |
| Zen 3            | 106       | 1.35%   |
| Zen 2            | 106       | 1.35%   |
| Goldmont         | 95        | 1.21%   |
| Zen              | 81        | 1.03%   |
| Alderlake Hybrid | 73        | 0.93%   |
| CometLake        | 67        | 0.86%   |
| K10              | 61        | 0.78%   |
| Jaguar           | 61        | 0.78%   |
| Bonnell          | 58        | 0.74%   |
| Piledriver       | 55        | 0.7%    |
| K8 Hammer        | 46        | 0.59%   |
| K10 Llano        | 35        | 0.45%   |
| K8 & K10 hybrid  | 33        | 0.42%   |
| Nehalem          | 29        | 0.37%   |
| Tremont          | 27        | 0.34%   |
| Steamroller      | 15        | 0.19%   |
| Gracemont        | 4         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 5749      | 61.98%  |
| AMD                              | 1882      | 20.29%  |
| Nvidia                           | 1636      | 17.64%  |
| Silicon Integrated Systems [SiS] | 9         | 0.1%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 820       | 8.52%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 647       | 6.72%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 414       | 4.3%    |
| Intel Core Processor Integrated Graphics Controller                                      | 346       | 3.59%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 332       | 3.45%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 290       | 3.01%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 277       | 2.88%   |
| Intel HD Graphics 5500                                                                   | 257       | 2.67%   |
| Intel HD Graphics 620                                                                    | 253       | 2.63%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 208       | 2.16%   |
| Intel UHD Graphics 620                                                                   | 191       | 1.98%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 186       | 1.93%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 186       | 1.93%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 181       | 1.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 164       | 1.7%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 159       | 1.65%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 129       | 1.34%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 116       | 1.2%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 107       | 1.11%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 101       | 1.05%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 100       | 1.04%   |
| AMD Lucienne                                                                             | 96        | 1%      |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 90        | 0.93%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 84        | 0.87%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 82        | 0.85%   |
| Intel HD Graphics 530                                                                    | 81        | 0.84%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 80        | 0.83%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 77        | 0.8%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 75        | 0.78%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 73        | 0.76%   |
| Intel HD Graphics 500                                                                    | 71        | 0.74%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 62        | 0.64%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 55        | 0.57%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 55        | 0.57%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 54        | 0.56%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 53        | 0.55%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 51        | 0.53%   |
| Intel HD Graphics 630                                                                    | 51        | 0.53%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 50        | 0.52%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 45        | 0.47%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| 1 x Intel              | 4169      | 53.05%  |
| 1 x AMD                | 1390      | 17.69%  |
| Intel + Nvidia         | 1100      | 14%     |
| 1 x Nvidia             | 435       | 5.54%   |
| Intel + AMD            | 254       | 3.23%   |
| 2 x Intel              | 253       | 3.22%   |
| 2 x AMD                | 146       | 1.86%   |
| AMD + Nvidia           | 94        | 1.2%    |
| 1 x SiS                | 9         | 0.11%   |
| 2 x Nvidia             | 7         | 0.09%   |
| 2 x Intel + 1 x Nvidia | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 7724      | 98.41%  |
| Unknown     | 78        | 0.99%   |
| Proprietary | 47        | 0.6%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 4596      | 58.5%   |
| 0.01-0.5   | 1254      | 15.96%  |
| 1.01-2.0   | 897       | 11.42%  |
| 0.51-1.0   | 616       | 7.84%   |
| 3.01-4.0   | 315       | 4.01%   |
| 5.01-6.0   | 85        | 1.08%   |
| 7.01-8.0   | 61        | 0.78%   |
| 2.01-3.0   | 25        | 0.32%   |
| 8.01-16.0  | 7         | 0.09%   |
| 16.01-24.0 | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 1697      | 20.87%  |
| LG Display              | 1352      | 16.63%  |
| Chimei Innolux          | 1121      | 13.79%  |
| BOE                     | 1089      | 13.39%  |
| Samsung Electronics     | 949       | 11.67%  |
| Chi Mei Optoelectronics | 292       | 3.59%   |
| Lenovo                  | 198       | 2.43%   |
| CPT                     | 148       | 1.82%   |
| Apple                   | 144       | 1.77%   |
| LG Philips              | 121       | 1.49%   |
| Sharp                   | 102       | 1.25%   |
| PANDA                   | 77        | 0.95%   |
| InfoVision              | 76        | 0.93%   |
| Dell                    | 72        | 0.89%   |
| Goldstar                | 68        | 0.84%   |
| Eizo                    | 61        | 0.75%   |
| Acer                    | 57        | 0.7%    |
| Hewlett-Packard         | 48        | 0.59%   |
| Sony                    | 35        | 0.43%   |
| Philips                 | 32        | 0.39%   |
| AOC                     | 31        | 0.38%   |
| Panasonic               | 24        | 0.3%    |
| CSO                     | 22        | 0.27%   |
| BenQ                    | 21        | 0.26%   |
| HannStar                | 20        | 0.25%   |
| InnoLux Display         | 19        | 0.23%   |
| Toshiba                 | 18        | 0.22%   |
| ASUSTek Computer        | 17        | 0.21%   |
| Ancor Communications    | 15        | 0.18%   |
| Iiyama                  | 14        | 0.17%   |
| ViewSonic               | 13        | 0.16%   |
| Unknown                 | 12        | 0.15%   |
| Quanta Display          | 9         | 0.11%   |
| KDC                     | 9         | 0.11%   |
| HKC                     | 9         | 0.11%   |
| Hitachi                 | 8         | 0.1%    |
| Vizio                   | 6         | 0.07%   |
| STA                     | 6         | 0.07%   |
| Fujitsu Siemens         | 6         | 0.07%   |
| ___                     | 5         | 0.06%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| CPT LCD Monitor COR17DB 1600x900 293x164mm 13.2-inch                     | 126       | 1.54%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 84        | 1.03%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 79        | 0.97%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 75        | 0.92%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 70        | 0.86%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 64        | 0.78%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 63        | 0.77%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 58        | 0.71%   |
| Eizo EV3285 ENC2979 3840x2160 698x393mm 31.5-inch                        | 57        | 0.7%    |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 52        | 0.64%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 44        | 0.54%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 43        | 0.53%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 43        | 0.53%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 42        | 0.51%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 37        | 0.45%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 35        | 0.43%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 35        | 0.43%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 34        | 0.42%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 33        | 0.4%    |
| BOE LCD Monitor BOE0629 1366x768 309x173mm 13.9-inch                     | 32        | 0.39%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 31        | 0.38%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 31        | 0.38%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch            | 30        | 0.37%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 340x190mm 15.3-inch            | 29        | 0.36%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 28        | 0.34%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 27        | 0.33%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 27        | 0.33%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 27        | 0.33%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 26        | 0.32%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 26        | 0.32%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 26        | 0.32%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 25        | 0.31%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 25        | 0.31%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 24        | 0.29%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 24        | 0.29%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 24        | 0.29%   |
| InfoVision LCD Monitor IVO03F4 1366x768 344x193mm 15.5-inch              | 23        | 0.28%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 23        | 0.28%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 23        | 0.28%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch            | 23        | 0.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 3469      | 43.48%  |
| 1920x1080 (FHD)    | 2422      | 30.36%  |
| 1600x900 (HD+)     | 684       | 8.57%   |
| 1280x800 (WXGA)    | 446       | 5.59%   |
| 1440x900 (WXGA+)   | 194       | 2.43%   |
| 3840x2160 (4K)     | 188       | 2.36%   |
| 1920x1200 (WUXGA)  | 99        | 1.24%   |
| 2560x1440 (QHD)    | 80        | 1%      |
| 2560x1600          | 77        | 0.97%   |
| 1680x1050 (WSXGA+) | 59        | 0.74%   |
| 2880x1800          | 30        | 0.38%   |
| 1024x600           | 28        | 0.35%   |
| 3200x1800 (QHD+)   | 23        | 0.29%   |
| 1280x1024 (SXGA)   | 19        | 0.24%   |
| 1920x540           | 17        | 0.21%   |
| 2160x1440          | 16        | 0.2%    |
| 1360x768           | 16        | 0.2%    |
| 1024x768 (XGA)     | 13        | 0.16%   |
| 1680x945           | 11        | 0.14%   |
| 3840x2400          | 10        | 0.13%   |
| 2288x1287          | 10        | 0.13%   |
| 2560x1080          | 9         | 0.11%   |
| 2256x1504          | 8         | 0.1%    |
| 3440x1440          | 7         | 0.09%   |
| 1920x1280          | 6         | 0.08%   |
| 800x1280           | 4         | 0.05%   |
| 1400x1050          | 4         | 0.05%   |
| 3456x2160          | 3         | 0.04%   |
| 2240x1400          | 3         | 0.04%   |
| 1280x720 (HD)      | 3         | 0.04%   |
| 3200x2000          | 2         | 0.03%   |
| 1152x864           | 2         | 0.03%   |
| 3840x1100          | 1         | 0.01%   |
| 3840x1080          | 1         | 0.01%   |
| 3300x2200          | 1         | 0.01%   |
| 3072x1920          | 1         | 0.01%   |
| 3000x2000          | 1         | 0.01%   |
| 2880x1920          | 1         | 0.01%   |
| 2880x1620          | 1         | 0.01%   |
| 2560x1700          | 1         | 0.01%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 3767      | 46.25%  |
| 13      | 1242      | 15.25%  |
| 14      | 960       | 11.79%  |
| 17      | 777       | 9.54%   |
| 12      | 261       | 3.2%    |
| 11      | 190       | 2.33%   |
| 23      | 113       | 1.39%   |
| 31      | 104       | 1.28%   |
| 27      | 102       | 1.25%   |
| 18      | 84        | 1.03%   |
| 24      | 83        | 1.02%   |
| 16      | 80        | 0.98%   |
| 21      | 70        | 0.86%   |
| 10      | 46        | 0.56%   |
| 19      | 36        | 0.44%   |
| 20      | 29        | 0.36%   |
| Unknown | 19        | 0.23%   |
| 84      | 17        | 0.21%   |
| 54      | 17        | 0.21%   |
| 22      | 17        | 0.21%   |
| 26      | 14        | 0.17%   |
| 72      | 13        | 0.16%   |
| 40      | 13        | 0.16%   |
| 34      | 13        | 0.16%   |
| 32      | 13        | 0.16%   |
| 142     | 8         | 0.1%    |
| 65      | 7         | 0.09%   |
| 39      | 5         | 0.06%   |
| 25      | 5         | 0.06%   |
| 52      | 4         | 0.05%   |
| 48      | 4         | 0.05%   |
| 46      | 4         | 0.05%   |
| 7       | 4         | 0.05%   |
| 37      | 3         | 0.04%   |
| 85      | 2         | 0.02%   |
| 74      | 2         | 0.02%   |
| 55      | 2         | 0.02%   |
| 42      | 2         | 0.02%   |
| 36      | 2         | 0.02%   |
| 28      | 2         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 5275      | 64.96%  |
| 201-300        | 1108      | 13.64%  |
| 351-400        | 947       | 11.66%  |
| 501-600        | 291       | 3.58%   |
| 401-500        | 223       | 2.75%   |
| 601-700        | 116       | 1.43%   |
| 1001-1500      | 42        | 0.52%   |
| 1501-2000      | 34        | 0.42%   |
| 701-800        | 29        | 0.36%   |
| 801-900        | 22        | 0.27%   |
| Unknown        | 19        | 0.23%   |
| More than 2000 | 8         | 0.1%    |
| 1-100          | 4         | 0.05%   |
| 901-1000       | 2         | 0.02%   |
| 101-200        | 1         | 0.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 6586      | 86.31%  |
| 16/10   | 903       | 11.83%  |
| 3/2     | 61        | 0.8%    |
| 5/4     | 22        | 0.29%   |
| 4/3     | 22        | 0.29%   |
| 21/9    | 14        | 0.18%   |
| 1.00    | 8         | 0.1%    |
| 32/9    | 5         | 0.07%   |
| 0.67    | 4         | 0.05%   |
| Unknown | 2         | 0.03%   |
| 3.40    | 1         | 0.01%   |
| 1.96    | 1         | 0.01%   |
| 0.63    | 1         | 0.01%   |
| 0.56    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 3768      | 46.28%  |
| 81-90          | 1676      | 20.58%  |
| 121-130        | 647       | 7.95%   |
| 71-80          | 522       | 6.41%   |
| 61-70          | 253       | 3.11%   |
| 201-250        | 240       | 2.95%   |
| 51-60          | 192       | 2.36%   |
| 351-500        | 135       | 1.66%   |
| 131-140        | 129       | 1.58%   |
| 301-350        | 108       | 1.33%   |
| 141-150        | 87        | 1.07%   |
| 151-200        | 84        | 1.03%   |
| More than 1000 | 78        | 0.96%   |
| 111-120        | 58        | 0.71%   |
| 41-50          | 46        | 0.56%   |
| 251-300        | 39        | 0.48%   |
| 501-1000       | 31        | 0.38%   |
| 91-100         | 25        | 0.31%   |
| Unknown        | 19        | 0.23%   |
| 1-40           | 5         | 0.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 3530      | 44.06%  |
| 121-160       | 2735      | 34.14%  |
| 51-100        | 1178      | 14.7%   |
| 161-240       | 390       | 4.87%   |
| More than 240 | 93        | 1.16%   |
| 1-50          | 67        | 0.84%   |
| Unknown       | 19        | 0.24%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 7135      | 90.56%  |
| 2     | 677       | 8.59%   |
| 0     | 53        | 0.67%   |
| 3     | 12        | 0.15%   |
| 4     | 2         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 4200      | 33.2%   |
| Intel                             | 3479      | 27.5%   |
| Qualcomm Atheros                  | 2489      | 19.68%  |
| Broadcom                          | 862       | 6.81%   |
| Broadcom Limited                  | 218       | 1.72%   |
| Marvell Technology Group          | 205       | 1.62%   |
| Samsung Electronics               | 155       | 1.23%   |
| Ralink                            | 148       | 1.17%   |
| MediaTek                          | 121       | 0.96%   |
| JMicron Technology                | 73        | 0.58%   |
| Dell                              | 70        | 0.55%   |
| TP-Link                           | 59        | 0.47%   |
| Huawei Technologies               | 55        | 0.43%   |
| Ericsson Business Mobile Networks | 55        | 0.43%   |
| ASIX Electronics                  | 53        | 0.42%   |
| Ralink Technology                 | 52        | 0.41%   |
| Nvidia                            | 43        | 0.34%   |
| Sierra Wireless                   | 39        | 0.31%   |
| Hewlett-Packard                   | 23        | 0.18%   |
| Xiaomi                            | 18        | 0.14%   |
| Qualcomm Atheros Communications   | 16        | 0.13%   |
| Motorola PCS                      | 16        | 0.13%   |
| DisplayLink                       | 14        | 0.11%   |
| NetGear                           | 13        | 0.1%    |
| D-Link                            | 13        | 0.1%    |
| Silicon Integrated Systems [SiS]  | 10        | 0.08%   |
| Qualcomm                          | 10        | 0.08%   |
| Linksys                           | 10        | 0.08%   |
| OPPO Electronics                  | 9         | 0.07%   |
| Lenovo                            | 8         | 0.06%   |
| D-Link System                     | 8         | 0.06%   |
| ASUSTek Computer                  | 8         | 0.06%   |
| ZTE WCDMA Technologies MSM        | 7         | 0.06%   |
| ICS Advent                        | 7         | 0.06%   |
| Belkin Components                 | 7         | 0.06%   |
| T & A Mobile Phones               | 6         | 0.05%   |
| OnePlus Technology (Shenzhen)     | 6         | 0.05%   |
| Edimax Technology                 | 6         | 0.05%   |
| Attansic Technology               | 6         | 0.05%   |
| Apple                             | 5         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 2324      | 15.38%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 1036      | 6.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 450       | 2.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 436       | 2.89%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 398       | 2.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 375       | 2.48%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 356       | 2.36%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 277       | 1.83%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 257       | 1.7%    |
| Intel Wireless 7265                                                     | 240       | 1.59%   |
| Intel Wireless 8265 / 8275                                              | 206       | 1.36%   |
| Intel Wireless 7260                                                     | 203       | 1.34%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 183       | 1.21%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 183       | 1.21%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 181       | 1.2%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 178       | 1.18%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 170       | 1.13%   |
| Intel Wireless 8260                                                     | 168       | 1.11%   |
| Intel Wi-Fi 6 AX200                                                     | 151       | 1%      |
| Samsung Galaxy series, misc. (tethering mode)                           | 144       | 0.95%   |
| Intel Wireless 3165                                                     | 143       | 0.95%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 136       | 0.9%    |
| Intel Wi-Fi 6 AX201                                                     | 125       | 0.83%   |
| Intel WiFi Link 5100                                                    | 121       | 0.8%    |
| Intel 82577LM Gigabit Network Connection                                | 120       | 0.79%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 119       | 0.79%   |
| Intel Wireless 3160                                                     | 119       | 0.79%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 112       | 0.74%   |
| Intel 82567LM Gigabit Network Connection                                | 104       | 0.69%   |
| Intel Centrino Advanced-N 6200                                          | 102       | 0.68%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 101       | 0.67%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 94        | 0.62%   |
| Intel Centrino Ultimate-N 6300                                          | 93        | 0.62%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 91        | 0.6%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 89        | 0.59%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 86        | 0.57%   |
| Intel Ethernet Connection (3) I218-LM                                   | 83        | 0.55%   |
| Broadcom BCM43142 802.11b/g/n                                           | 83        | 0.55%   |
| Intel Ethernet Connection I218-LM                                       | 82        | 0.54%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 81        | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 3301      | 41.01%  |
| Qualcomm Atheros                      | 2165      | 26.9%   |
| Realtek Semiconductor                 | 1385      | 17.21%  |
| Broadcom                              | 587       | 7.29%   |
| Ralink                                | 148       | 1.84%   |
| MediaTek                              | 106       | 1.32%   |
| Broadcom Limited                      | 101       | 1.25%   |
| Ralink Technology                     | 52        | 0.65%   |
| Sierra Wireless                       | 39        | 0.48%   |
| Dell                                  | 36        | 0.45%   |
| TP-Link                               | 25        | 0.31%   |
| Qualcomm Atheros Communications       | 16        | 0.2%    |
| Ericsson Business Mobile Networks     | 9         | 0.11%   |
| D-Link                                | 9         | 0.11%   |
| NetGear                               | 8         | 0.1%    |
| Linksys                               | 8         | 0.1%    |
| D-Link System                         | 8         | 0.1%    |
| Hewlett-Packard                       | 6         | 0.07%   |
| Edimax Technology                     | 6         | 0.07%   |
| Belkin Components                     | 6         | 0.07%   |
| ASUSTek Computer                      | 6         | 0.07%   |
| Qualcomm                              | 3         | 0.04%   |
| Qcom                                  | 3         | 0.04%   |
| Fibocom                               | 3         | 0.04%   |
| AVM                                   | 3         | 0.04%   |
| PLANEX                                | 2         | 0.02%   |
| ZyXEL Communications                  | 1         | 0.01%   |
| Sitecom Europe                        | 1         | 0.01%   |
| Senao                                 | 1         | 0.01%   |
| Microsoft                             | 1         | 0.01%   |
| Mercucys                              | 1         | 0.01%   |
| Fujitsu Siemens Computers             | 1         | 0.01%   |
| Elecom                                | 1         | 0.01%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 450       | 5.58%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 436       | 5.4%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 398       | 4.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 375       | 4.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 277       | 3.43%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 257       | 3.18%   |
| Intel Wireless 7265                                                     | 240       | 2.97%   |
| Intel Wireless 8265 / 8275                                              | 206       | 2.55%   |
| Intel Wireless 7260                                                     | 203       | 2.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 183       | 2.27%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 183       | 2.27%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 181       | 2.24%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 178       | 2.21%   |
| Intel Wireless 8260                                                     | 168       | 2.08%   |
| Intel Wi-Fi 6 AX200                                                     | 151       | 1.87%   |
| Intel Wireless 3165                                                     | 143       | 1.77%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 136       | 1.69%   |
| Intel Wi-Fi 6 AX201                                                     | 125       | 1.55%   |
| Intel WiFi Link 5100                                                    | 121       | 1.5%    |
| Intel Wireless 3160                                                     | 119       | 1.47%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 112       | 1.39%   |
| Intel Centrino Advanced-N 6200                                          | 102       | 1.26%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 101       | 1.25%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 94        | 1.16%   |
| Intel Centrino Ultimate-N 6300                                          | 93        | 1.15%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 91        | 1.13%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 89        | 1.1%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 86        | 1.07%   |
| Broadcom BCM43142 802.11b/g/n                                           | 83        | 1.03%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 81        | 1%      |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 80        | 0.99%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 79        | 0.98%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 73        | 0.9%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 73        | 0.9%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 71        | 0.88%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 71        | 0.88%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 68        | 0.84%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 64        | 0.79%   |
| Intel Centrino Wireless-N 2230                                          | 64        | 0.79%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 63        | 0.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 3622      | 52.83%  |
| Intel                            | 1318      | 19.22%  |
| Qualcomm Atheros                 | 634       | 9.25%   |
| Broadcom                         | 397       | 5.79%   |
| Marvell Technology Group         | 205       | 2.99%   |
| Samsung Electronics              | 155       | 2.26%   |
| Broadcom Limited                 | 121       | 1.76%   |
| JMicron Technology               | 73        | 1.06%   |
| ASIX Electronics                 | 53        | 0.77%   |
| Huawei Technologies              | 45        | 0.66%   |
| Nvidia                           | 42        | 0.61%   |
| TP-Link                          | 34        | 0.5%    |
| Xiaomi                           | 18        | 0.26%   |
| MediaTek                         | 15        | 0.22%   |
| DisplayLink                      | 14        | 0.2%    |
| Silicon Integrated Systems [SiS] | 10        | 0.15%   |
| OPPO Electronics                 | 9         | 0.13%   |
| Motorola PCS                     | 8         | 0.12%   |
| Lenovo                           | 8         | 0.12%   |
| ZTE WCDMA Technologies MSM       | 7         | 0.1%    |
| Qualcomm                         | 7         | 0.1%    |
| ICS Advent                       | 7         | 0.1%    |
| OnePlus Technology (Shenzhen)    | 6         | 0.09%   |
| Attansic Technology              | 6         | 0.09%   |
| NetGear                          | 5         | 0.07%   |
| Hewlett-Packard                  | 5         | 0.07%   |
| Apple                            | 5         | 0.07%   |
| D-Link                           | 4         | 0.06%   |
| Microchip Technology             | 3         | 0.04%   |
| Google                           | 3         | 0.04%   |
| vivo                             | 2         | 0.03%   |
| T & A Mobile Phones              | 2         | 0.03%   |
| Spreadtrum Communications        | 2         | 0.03%   |
| Linksys                          | 2         | 0.03%   |
| ASUSTek Computer                 | 2         | 0.03%   |
| Sitecom Europe                   | 1         | 0.01%   |
| LG Electronics                   | 1         | 0.01%   |
| HTC (High Tech Computer)         | 1         | 0.01%   |
| HMD Global                       | 1         | 0.01%   |
| Belkin Components                | 1         | 0.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 2324      | 33.68%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 1036      | 15.01%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 356       | 5.16%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 170       | 2.46%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 144       | 2.09%   |
| Intel 82577LM Gigabit Network Connection                                       | 120       | 1.74%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 119       | 1.72%   |
| Intel 82567LM Gigabit Network Connection                                       | 104       | 1.51%   |
| Intel Ethernet Connection (3) I218-LM                                          | 83        | 1.2%    |
| Intel Ethernet Connection I218-LM                                              | 82        | 1.19%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 80        | 1.16%   |
| Intel Ethernet Connection I219-LM                                              | 77        | 1.12%   |
| Intel Ethernet Connection (4) I219-LM                                          | 77        | 1.12%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 70        | 1.01%   |
| Intel Ethernet Connection I217-LM                                              | 67        | 0.97%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 66        | 0.96%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 60        | 0.87%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 58        | 0.84%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 56        | 0.81%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 54        | 0.78%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 52        | 0.75%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 47        | 0.68%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 44        | 0.64%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 42        | 0.61%   |
| Intel 82579V Gigabit Network Connection                                        | 41        | 0.59%   |
| Intel 82566MM Gigabit Network Connection                                       | 40        | 0.58%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 40        | 0.58%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 38        | 0.55%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 38        | 0.55%   |
| Huawei E353/E3131                                                              | 37        | 0.54%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 34        | 0.49%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 34        | 0.49%   |
| Intel Ethernet Connection I219-V                                               | 34        | 0.49%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 34        | 0.49%   |
| Intel Ethernet Connection (4) I219-V                                           | 33        | 0.48%   |
| Realtek Killer E2600 GbE Controller                                            | 32        | 0.46%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 32        | 0.46%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 30        | 0.43%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 29        | 0.42%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 29        | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 7753      | 53.22%  |
| Ethernet | 6679      | 45.84%  |
| Modem    | 114       | 0.78%   |
| Unknown  | 23        | 0.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 5446      | 70.41%  |
| Ethernet | 2288      | 29.58%  |
| Modem    | 1         | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 6112      | 78.07%  |
| 1     | 1599      | 20.42%  |
| 0     | 95        | 1.21%   |
| 3     | 23        | 0.29%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 5591      | 70.35%  |
| Yes  | 2356      | 29.65%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2172      | 38.25%  |
| Realtek Semiconductor           | 675       | 11.89%  |
| Qualcomm Atheros Communications | 668       | 11.76%  |
| Broadcom                        | 407       | 7.17%   |
| Lite-On Technology              | 362       | 6.37%   |
| IMC Networks                    | 304       | 5.35%   |
| Foxconn / Hon Hai               | 254       | 4.47%   |
| Dell                            | 147       | 2.59%   |
| Apple                           | 125       | 2.2%    |
| Toshiba                         | 119       | 2.1%    |
| Hewlett-Packard                 | 118       | 2.08%   |
| Cambridge Silicon Radio         | 73        | 1.29%   |
| Ralink                          | 64        | 1.13%   |
| Realtek                         | 30        | 0.53%   |
| ASUSTek Computer                | 26        | 0.46%   |
| Foxconn International           | 25        | 0.44%   |
| Alps Electric                   | 21        | 0.37%   |
| Ralink Technology               | 14        | 0.25%   |
| Chicony Electronics             | 14        | 0.25%   |
| Askey Computer                  | 13        | 0.23%   |
| MediaTek                        | 8         | 0.14%   |
| Fujitsu                         | 8         | 0.14%   |
| Taiyo Yuden                     | 6         | 0.11%   |
| TP-Link                         | 4         | 0.07%   |
| Micro Star International        | 4         | 0.07%   |
| Unknown                         | 4         | 0.07%   |
| USI                             | 3         | 0.05%   |
| Smart Modular Technologies      | 2         | 0.04%   |
| Edimax Technology               | 2         | 0.04%   |
| Belkin Components               | 2         | 0.04%   |
| SINO WEALTH                     | 1         | 0.02%   |
| Qcom                            | 1         | 0.02%   |
| Opticis                         | 1         | 0.02%   |
| Integrated System Solution      | 1         | 0.02%   |
| D-Link System                   | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 1105      | 19.45%  |
| Realtek Bluetooth Radio                                                             | 457       | 8.05%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 307       | 5.4%    |
| Qualcomm Atheros  Bluetooth Device                                                  | 297       | 5.23%   |
| Intel AX201 Bluetooth                                                               | 241       | 4.24%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 161       | 2.83%   |
| Intel AX200 Bluetooth                                                               | 149       | 2.62%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 129       | 2.27%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 127       | 2.24%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 117       | 2.06%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 112       | 1.97%   |
| IMC Networks Bluetooth Radio                                                        | 107       | 1.88%   |
| Intel Bluetooth Device                                                              | 103       | 1.81%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 96        | 1.69%   |
| IMC Networks Bluetooth Device                                                       | 90        | 1.58%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 87        | 1.53%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 85        | 1.5%    |
| Foxconn / Hon Hai Bluetooth Device                                                  | 77        | 1.36%   |
| Lite-On Bluetooth Device                                                            | 76        | 1.34%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 73        | 1.29%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 70        | 1.23%   |
| Apple Bluetooth Host Controller                                                     | 70        | 1.23%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 69        | 1.21%   |
| Dell DW375 Bluetooth Module                                                         | 67        | 1.18%   |
| Ralink RT3290 Bluetooth                                                             | 64        | 1.13%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 63        | 1.11%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 47        | 0.83%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 46        | 0.81%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 46        | 0.81%   |
| Toshiba Bluetooth Device                                                            | 38        | 0.67%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 38        | 0.67%   |
| Apple Bluetooth USB Host Controller                                                 | 38        | 0.67%   |
| Realtek RTL8723B Bluetooth                                                          | 37        | 0.65%   |
| Intel AX210 Bluetooth                                                               | 37        | 0.65%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 37        | 0.65%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 36        | 0.63%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 35        | 0.62%   |
| Broadcom HP Portable SoftSailing                                                    | 32        | 0.56%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 31        | 0.55%   |
| Realtek Bluetooth Radio                                                             | 30        | 0.53%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 6333      | 70.16%  |
| AMD                                          | 1609      | 17.82%  |
| Nvidia                                       | 896       | 9.93%   |
| C-Media Electronics                          | 27        | 0.3%    |
| Realtek Semiconductor                        | 13        | 0.14%   |
| Logitech                                     | 13        | 0.14%   |
| Generalplus Technology                       | 13        | 0.14%   |
| Apple                                        | 11        | 0.12%   |
| Silicon Integrated Systems [SiS]             | 10        | 0.11%   |
| Creative Technology                          | 9         | 0.1%    |
| Texas Instruments                            | 8         | 0.09%   |
| Lenovo                                       | 8         | 0.09%   |
| JMTek                                        | 8         | 0.09%   |
| GN Netcom                                    | 7         | 0.08%   |
| ASUSTek Computer                             | 6         | 0.07%   |
| Plantronics                                  | 5         | 0.06%   |
| Focusrite-Novation                           | 3         | 0.03%   |
| Corsair                                      | 3         | 0.03%   |
| Conexant Systems                             | 3         | 0.03%   |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 0.02%   |
| Yamaha                                       | 2         | 0.02%   |
| Thesycon Systemsoftware & Consulting         | 2         | 0.02%   |
| Razer USA                                    | 2         | 0.02%   |
| PreSonus Audio Electronics                   | 2         | 0.02%   |
| Nordic Semiconductor ASA                     | 2         | 0.02%   |
| No brand                                     | 2         | 0.02%   |
| M-Audio                                      | 2         | 0.02%   |
| XMOS                                         | 1         | 0.01%   |
| VIA Technologies                             | 1         | 0.01%   |
| TTGK Technology                              | 1         | 0.01%   |
| THX                                          | 1         | 0.01%   |
| TerraTec Electronic                          | 1         | 0.01%   |
| Tenx Technology                              | 1         | 0.01%   |
| TEAC                                         | 1         | 0.01%   |
| Schiit Audio                                 | 1         | 0.01%   |
| SAVITECH                                     | 1         | 0.01%   |
| Samsung Electronics                          | 1         | 0.01%   |
| Samson Technologies                          | 1         | 0.01%   |
| RODE Microphones                             | 1         | 0.01%   |
| Phison Electronics                           | 1         | 0.01%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 866       | 7.79%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 802       | 7.21%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 710       | 6.39%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 653       | 5.87%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 548       | 4.93%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 507       | 4.56%   |
| AMD FCH Azalia Controller                                                                         | 340       | 3.06%   |
| Intel 8 Series HD Audio Controller                                                                | 337       | 3.03%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 334       | 3%      |
| Intel Broadwell-U Audio Controller                                                                | 301       | 2.71%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 301       | 2.71%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 301       | 2.71%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 299       | 2.69%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 260       | 2.34%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 223       | 2.01%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 216       | 1.94%   |
| AMD Kabini HDMI/DP Audio                                                                          | 216       | 1.94%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 202       | 1.82%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 189       | 1.7%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 186       | 1.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 184       | 1.65%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 161       | 1.45%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 158       | 1.42%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 154       | 1.39%   |
| AMD Wrestler HDMI Audio                                                                           | 146       | 1.31%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 121       | 1.09%   |
| AMD High Definition Audio Controller                                                              | 116       | 1.04%   |
| Intel Cannon Lake PCH cAVS                                                                        | 113       | 1.02%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 107       | 0.96%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 104       | 0.94%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 99        | 0.89%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 95        | 0.85%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 93        | 0.84%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 83        | 0.75%   |
| Nvidia High Definition Audio Controller                                                           | 72        | 0.65%   |
| Intel CM238 HD Audio Controller                                                                   | 66        | 0.59%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 63        | 0.57%   |
| Intel Comet Lake PCH cAVS                                                                         | 58        | 0.52%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 56        | 0.5%    |
| AMD Trinity HDMI Audio Controller                                                                 | 55        | 0.49%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 2528      | 26.52%  |
| SK hynix            | 1984      | 20.81%  |
| Micron Technology   | 984       | 10.32%  |
| Kingston            | 828       | 8.69%   |
| Unknown             | 799       | 8.38%   |
| Elpida              | 387       | 4.06%   |
| Crucial             | 307       | 3.22%   |
| Ramaxel Technology  | 244       | 2.56%   |
| A-DATA Technology   | 221       | 2.32%   |
| Nanya Technology    | 204       | 2.14%   |
| Smart               | 150       | 1.57%   |
| Unknown (ABCD)      | 101       | 1.06%   |
| Corsair             | 92        | 0.97%   |
| Unknown             | 62        | 0.65%   |
| G.Skill             | 50        | 0.52%   |
| Teikon              | 39        | 0.41%   |
| Transcend           | 36        | 0.38%   |
| Patriot             | 35        | 0.37%   |
| ASint Technology    | 32        | 0.34%   |
| Team                | 31        | 0.33%   |
| Apacer              | 27        | 0.28%   |
| GOODRAM             | 26        | 0.27%   |
| High Bridge         | 24        | 0.25%   |
| AMD                 | 23        | 0.24%   |
| Toshiba             | 19        | 0.2%    |
| Smart Brazil        | 19        | 0.2%    |
| Qimonda             | 15        | 0.16%   |
| 48spaces            | 14        | 0.15%   |
| PNY                 | 12        | 0.13%   |
| Avant               | 12        | 0.13%   |
| Timetec             | 11        | 0.12%   |
| CSX                 | 11        | 0.12%   |
| Silicon Power       | 10        | 0.1%    |
| SHARETRONIC         | 10        | 0.1%    |
| Neo Forza           | 9         | 0.09%   |
| Multilaser          | 8         | 0.08%   |
| Kingmax             | 8         | 0.08%   |
| V-GeN               | 7         | 0.07%   |
| Goldkey             | 7         | 0.07%   |
| Sesame              | 5         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 174       | 1.7%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 170       | 1.66%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 155       | 1.52%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 152       | 1.49%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 137       | 1.34%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 133       | 1.3%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 131       | 1.28%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 129       | 1.26%   |
| Elpida RAM Module 2GB SODIMM DDR3 1333MT/s                          | 129       | 1.26%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 114       | 1.12%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 92        | 0.9%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 92        | 0.9%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 90        | 0.88%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 88        | 0.86%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s            | 74        | 0.72%   |
| Unknown RAM Module 2GB SODIMM DDR2                                  | 71        | 0.7%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 70        | 0.69%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 69        | 0.68%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 63        | 0.62%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 62        | 0.61%   |
| Unknown                                                             | 62        | 0.61%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s               | 61        | 0.6%    |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR 975MT/s             | 60        | 0.59%   |
| Unknown RAM Module 4GB SODIMM DDR3                                  | 59        | 0.58%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s               | 58        | 0.57%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s               | 57        | 0.56%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 56        | 0.55%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 54        | 0.53%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s               | 53        | 0.52%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 52        | 0.51%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 52        | 0.51%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                          | 51        | 0.5%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 51        | 0.5%    |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 3200MT/s               | 49        | 0.48%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s               | 45        | 0.44%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s               | 45        | 0.44%   |
| Samsung RAM M471B5173BH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 44        | 0.43%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 44        | 0.43%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 40        | 0.39%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 39        | 0.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 3983      | 50.44%  |
| DDR4    | 2334      | 29.56%  |
| DDR2    | 705       | 8.93%   |
| LPDDR4  | 289       | 3.66%   |
| SDRAM   | 276       | 3.49%   |
| Unknown | 94        | 1.19%   |
| LPDDR3  | 80        | 1.01%   |
| DDR5    | 44        | 0.56%   |
| LPDDR5  | 34        | 0.43%   |
| DRAM    | 33        | 0.42%   |
| DDR     | 25        | 0.32%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| SODIMM          | 7352      | 94.04%  |
| Row Of Chips    | 364       | 4.66%   |
| Unknown         | 36        | 0.46%   |
| DIMM            | 34        | 0.43%   |
| Chip            | 31        | 0.4%    |
| Proprietary Car | 1         | 0.01%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 3542      | 39.76%  |
| 8192  | 2452      | 27.53%  |
| 2048  | 1922      | 21.58%  |
| 16384 | 504       | 5.66%   |
| 1024  | 342       | 3.84%   |
| 32768 | 129       | 1.45%   |
| 512   | 16        | 0.18%   |
| 65536 | 1         | 0.01%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 2565      | 29.18%  |
| 2667    | 1125      | 12.8%   |
| 3200    | 874       | 9.94%   |
| 1334    | 797       | 9.07%   |
| 1333    | 589       | 6.7%    |
| 2400    | 548       | 6.24%   |
| 667     | 380       | 4.32%   |
| 1067    | 250       | 2.84%   |
| 2133    | 242       | 2.75%   |
| Unknown | 217       | 2.47%   |
| 800     | 213       | 2.42%   |
| 4199    | 157       | 1.79%   |
| 3266    | 133       | 1.51%   |
| 2048    | 104       | 1.18%   |
| 975     | 97        | 1.1%    |
| 1066    | 88        | 1%      |
| 1867    | 81        | 0.92%   |
| 533     | 60        | 0.68%   |
| 4267    | 57        | 0.65%   |
| 4800    | 40        | 0.46%   |
| 6400    | 29        | 0.33%   |
| 4266    | 28        | 0.32%   |
| 1866    | 22        | 0.25%   |
| 8400    | 20        | 0.23%   |
| 3733    | 16        | 0.18%   |
| 333     | 14        | 0.16%   |
| 1639    | 11        | 0.13%   |
| 2933    | 6         | 0.07%   |
| 5600    | 4         | 0.05%   |
| 3000    | 3         | 0.03%   |
| 400     | 3         | 0.03%   |
| 5500    | 2         | 0.02%   |
| 2267    | 2         | 0.02%   |
| 1776    | 2         | 0.02%   |
| 266     | 2         | 0.02%   |
| 7500    | 1         | 0.01%   |
| 7467    | 1         | 0.01%   |
| 5200    | 1         | 0.01%   |
| 1596    | 1         | 0.01%   |
| 1200    | 1         | 0.01%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 32        | 38.1%   |
| Canon                 | 19        | 22.62%  |
| Brother Industries    | 13        | 15.48%  |
| Samsung Electronics   | 9         | 10.71%  |
| Seiko Epson           | 6         | 7.14%   |
| Xerox                 | 2         | 2.38%   |
| Prolific Technology   | 2         | 2.38%   |
| Lexmark International | 1         | 1.19%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Brother DCP-7055W                       | 4         | 4.71%   |
| Samsung ML-1640 Series Laser Printer    | 3         | 3.53%   |
| HP Deskjet 2050 J510                    | 3         | 3.53%   |
| Prolific PL2305 Parallel Port           | 2         | 2.35%   |
| HP LaserJet 1020                        | 2         | 2.35%   |
| HP ENVY Photo 6200 series               | 2         | 2.35%   |
| HP DeskJet 3630 series                  | 2         | 2.35%   |
| HP DeskJet 2600 series                  | 2         | 2.35%   |
| Canon TR8500 series                     | 2         | 2.35%   |
| Canon PIXMA MG3600 Series               | 2         | 2.35%   |
| Canon PIXMA MG2500 Series               | 2         | 2.35%   |
| Canon LBP2900                           | 2         | 2.35%   |
| Brother DCP-7010                        | 2         | 2.35%   |
| Xerox WorkCentre 6025                   | 1         | 1.18%   |
| Xerox Phaser 6000B                      | 1         | 1.18%   |
| Seiko Epson L360 Series                 | 1         | 1.18%   |
| Seiko Epson L355 Series                 | 1         | 1.18%   |
| Seiko Epson L3150 Series                | 1         | 1.18%   |
| Seiko Epson L310 Series                 | 1         | 1.18%   |
| Seiko Epson L210 Series                 | 1         | 1.18%   |
| Seiko Epson L120 Series                 | 1         | 1.18%   |
| Samsung Xerox Phaser 3117 Laser Printer | 1         | 1.18%   |
| Samsung SCX-3400 Series                 | 1         | 1.18%   |
| Samsung ML-2010P Mono Laser Printer     | 1         | 1.18%   |
| Samsung M2070 Series                    | 1         | 1.18%   |
| Samsung M2020 Series                    | 1         | 1.18%   |
| Samsung CLP-325 Color Laser Printer     | 1         | 1.18%   |
| Lexmark International E360d             | 1         | 1.18%   |
| HP PSC 1400                             | 1         | 1.18%   |
| HP OfficeJet Pro 69                     | 1         | 1.18%   |
| HP OfficeJet 6950                       | 1         | 1.18%   |
| HP OfficeJet 4300                       | 1         | 1.18%   |
| HP LaserJet P1102                       | 1         | 1.18%   |
| HP LaserJet 3055                        | 1         | 1.18%   |
| HP LaserJet 200 colorMFP M275nw         | 1         | 1.18%   |
| HP LaserJet 1018                        | 1         | 1.18%   |
| HP HP LaserJet M14-M17                  | 1         | 1.18%   |
| HP ENVY 6000 series                     | 1         | 1.18%   |
| HP ENVY 4520 series                     | 1         | 1.18%   |
| HP DeskJet Plus 6400 series             | 1         | 1.18%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 5         | 45.45%  |
| Seiko Epson     | 4         | 36.36%  |
| Hewlett-Packard | 2         | 18.18%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                  | 3         | 27.27%  |
| HP ScanJet 5590                                          | 2         | 18.18%  |
| Seiko Epson Scanner                                      | 1         | 9.09%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]      | 1         | 9.09%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 9.09%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]        | 1         | 9.09%   |
| Canon CanoScan N1240U/LiDE 30                            | 1         | 9.09%   |
| Canon CanoScan LiDE 600F                                 | 1         | 9.09%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1810      | 27.32%  |
| IMC Networks                           | 557       | 8.41%   |
| Realtek Semiconductor                  | 556       | 8.39%   |
| Microdia                               | 539       | 8.13%   |
| Suyin                                  | 410       | 6.19%   |
| Bison Electronics                      | 339       | 5.12%   |
| Sunplus Innovation Technology          | 324       | 4.89%   |
| Quanta                                 | 296       | 4.47%   |
| Cheng Uei Precision Industry (Foxlink) | 275       | 4.15%   |
| Syntek                                 | 218       | 3.29%   |
| Acer                                   | 172       | 2.6%    |
| Silicon Motion                         | 139       | 2.1%    |
| Lite-On Technology                     | 128       | 1.93%   |
| Ricoh                                  | 113       | 1.71%   |
| Apple                                  | 112       | 1.69%   |
| Alcor Micro                            | 108       | 1.63%   |
| Luxvisions Innotech Limited            | 72        | 1.09%   |
| Lenovo                                 | 66        | 1%      |
| Importek                               | 58        | 0.88%   |
| ALi                                    | 45        | 0.68%   |
| Primax Electronics                     | 40        | 0.6%    |
| Sonix Technology                       | 30        | 0.45%   |
| Z-Star Microelectronics                | 24        | 0.36%   |
| DigiTech                               | 22        | 0.33%   |
| OmniVision Technologies                | 20        | 0.3%    |
| Logitech                               | 18        | 0.27%   |
| Samsung Electronics                    | 13        | 0.2%    |
| USB Camera                             | 10        | 0.15%   |
| Sunplus Technology                     | 10        | 0.15%   |
| SunplusIT                              | 8         | 0.12%   |
| Intel                                  | 8         | 0.12%   |
| HRY                                    | 8         | 0.12%   |
| Genesys Logic                          | 8         | 0.12%   |
| Y Media                                | 6         | 0.09%   |
| Shenzhen Kingcome Optoelectronic       | 5         | 0.08%   |
| BUFFALO                                | 5         | 0.08%   |
| Tripath Technology                     | 4         | 0.06%   |
| Foxconn / Hon Hai                      | 4         | 0.06%   |
| Cubeternet                             | 4         | 0.06%   |
| Unknown                                | 3         | 0.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 243       | 3.66%   |
| Chicony HD WebCam                                       | 178       | 2.68%   |
| Microdia Integrated_Webcam_HD                           | 155       | 2.34%   |
| Realtek Integrated_Webcam_HD                            | 140       | 2.11%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 121       | 1.82%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 107       | 1.61%   |
| IMC Networks Integrated Camera                          | 97        | 1.46%   |
| Syntek Integrated Camera                                | 96        | 1.45%   |
| Realtek USB Camera                                      | 94        | 1.42%   |
| Sunplus Integrated_Webcam_HD                            | 91        | 1.37%   |
| Microdia Integrated Webcam                              | 91        | 1.37%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 80        | 1.21%   |
| Chicony USB 2.0 Camera                                  | 78        | 1.18%   |
| Chicony VGA Webcam                                      | 75        | 1.13%   |
| Bison Integrated Camera                                 | 74        | 1.12%   |
| Chicony HP TrueVision HD Camera                         | 60        | 0.9%    |
| Sunplus HD WebCam                                       | 59        | 0.89%   |
| Chicony TOSHIBA Web Camera - HD                         | 59        | 0.89%   |
| Chicony Lenovo EasyCamera                               | 58        | 0.87%   |
| Chicony HP Truevision HD                                | 58        | 0.87%   |
| Bison Lenovo EasyCamera                                 | 58        | 0.87%   |
| Chicony USB2.0 HD UVC WebCam                            | 57        | 0.86%   |
| Quanta HD User Facing                                   | 54        | 0.81%   |
| Syntek Lenovo EasyCamera                                | 53        | 0.8%    |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 52        | 0.78%   |
| Chicony FJ Camera                                       | 51        | 0.77%   |
| Chicony USB2.0 VGA UVC WebCam                           | 48        | 0.72%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 47        | 0.71%   |
| Lite-On Integrated Camera                               | 47        | 0.71%   |
| Chicony HD User Facing                                  | 47        | 0.71%   |
| Chicony EasyCamera                                      | 47        | 0.71%   |
| Acer Integrated Camera                                  | 47        | 0.71%   |
| Suyin Integrated_Webcam_HD                              | 44        | 0.66%   |
| Quanta VGA WebCam                                       | 43        | 0.65%   |
| Quanta HP Webcam                                        | 41        | 0.62%   |
| Chicony HP Webcam                                       | 41        | 0.62%   |
| IMC Networks UVC VGA Webcam                             | 40        | 0.6%    |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 40        | 0.6%    |
| Bison Lenovo Integrated Webcam                          | 40        | 0.6%    |
| Apple FaceTime HD Camera                                | 40        | 0.6%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 361       | 39.2%   |
| AuthenTec                          | 139       | 15.09%  |
| Upek                               | 95        | 10.31%  |
| Synaptics                          | 92        | 9.99%   |
| Shenzhen Goodix Technology         | 76        | 8.25%   |
| Elan Microelectronics              | 67        | 7.27%   |
| LighTuning Technology              | 41        | 4.45%   |
| STMicroelectronics                 | 32        | 3.47%   |
| Focal-systems.Corp                 | 10        | 1.09%   |
| Samsung Electronics                | 4         | 0.43%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 0.33%   |
| HOLTEK                             | 1         | 0.11%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 87        | 9.45%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 71        | 7.71%   |
| Shenzhen Goodix  Fingerprint Device                                        | 56        | 6.08%   |
| AuthenTec AES2810                                                          | 54        | 5.86%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 47        | 5.1%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 37        | 4.02%   |
| Validity Sensors VFS491                                                    | 37        | 4.02%   |
| Elan ELAN:Fingerprint                                                      | 37        | 4.02%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 36        | 3.91%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 34        | 3.69%   |
| STMicroelectronics Fingerprint Reader                                      | 32        | 3.47%   |
| Elan ELAN:ARM-M4                                                           | 30        | 3.26%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 26        | 2.82%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 24        | 2.61%   |
| Validity Sensors Synaptics WBDI                                            | 21        | 2.28%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 20        | 2.17%   |
| AuthenTec Fingerprint Sensor                                               | 18        | 1.95%   |
| Validity Sensors Fingerprint scanner                                       | 17        | 1.85%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 17        | 1.85%   |
| AuthenTec AES1600                                                          | 17        | 1.85%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 16        | 1.74%   |
| Shenzhen Goodix Fingerprint Reader                                         | 15        | 1.63%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 14        | 1.52%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 14        | 1.52%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 10        | 1.09%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 10        | 1.09%   |
| LighTuning Fingerprint Reader                                              | 10        | 1.09%   |
| Focal-systems.Corp FT9201Fingerprint.Ì                                  | 10        | 1.09%   |
| Upek TCS5B Fingerprint sensor                                              | 8         | 0.87%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 8         | 0.87%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 8         | 0.87%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 7         | 0.76%   |
| Synaptics UWP WBDI Device                                                  | 7         | 0.76%   |
| Synaptics  WBDI                                                            | 7         | 0.76%   |
| Validity Sensors VFS Fingerprint sensor                                    | 6         | 0.65%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 6         | 0.65%   |
| Synaptics TouchPad                                                         | 5         | 0.54%   |
| Synaptics Fingerprint reader [HP G6]                                       | 5         | 0.54%   |
| Shenzhen Goodix FingerPrint                                                | 5         | 0.54%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 4         | 0.43%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 278       | 52.75%  |
| Alcor Micro           | 87        | 16.51%  |
| O2 Micro              | 65        | 12.33%  |
| Lenovo                | 42        | 7.97%   |
| Upek                  | 40        | 7.59%   |
| SCM Microsystems      | 4         | 0.76%   |
| Gemalto (was Gemplus) | 3         | 0.57%   |
| Yubico.com            | 2         | 0.38%   |
| Realtek Semiconductor | 1         | 0.19%   |
| OmniKey               | 1         | 0.19%   |
| Microchip Technology  | 1         | 0.19%   |
| Hewlett-Packard       | 1         | 0.19%   |
| Cherry                | 1         | 0.19%   |
| Advanced Card Systems | 1         | 0.19%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 135       | 25.62%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 86        | 16.32%  |
| Broadcom 5880                                                                | 66        | 12.52%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 64        | 12.14%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 62        | 11.76%  |
| Lenovo Integrated Smart Card Reader                                          | 42        | 7.97%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 40        | 7.59%   |
| Broadcom 58200                                                               | 14        | 2.66%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 4         | 0.76%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.57%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 0.38%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.19%   |
| OmniKey CardMan 4321                                                         | 1         | 0.19%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.19%   |
| Microchip Technology SMSC USX101x Reader                                     | 1         | 0.19%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.19%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.19%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.19%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.19%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.19%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 5867      | 74.43%  |
| 1     | 1722      | 21.84%  |
| 2     | 274       | 3.48%   |
| 3     | 19        | 0.24%   |
| 6     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 921       | 40.47%  |
| Chipcard                 | 514       | 22.58%  |
| Graphics card            | 364       | 15.99%  |
| Net/wireless             | 130       | 5.71%   |
| Bluetooth                | 100       | 4.39%   |
| Storage                  | 91        | 4%      |
| Multimedia controller    | 61        | 2.68%   |
| Camera                   | 43        | 1.89%   |
| Communication controller | 19        | 0.83%   |
| Sound                    | 11        | 0.48%   |
| Flash memory             | 7         | 0.31%   |
| Network                  | 6         | 0.26%   |
| Net/ethernet             | 4         | 0.18%   |
| Card reader              | 3         | 0.13%   |
| Modem                    | 1         | 0.04%   |
| Dvb card                 | 1         | 0.04%   |

