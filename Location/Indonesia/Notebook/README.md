Linux in Indonesia - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Indonesia.

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

Total: 1283

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Sony          | VGN-CS108D                  | [24bf5bb06c](https://linux-hardware.org/?probe=24bf5bb06c) | Sep 05, 2023 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | [1a1c5e43bc](https://linux-hardware.org/?probe=1a1c5e43bc) | Sep 05, 2023 |
| AXIOO         | Mybook 14E                  | [b6ddb628dc](https://linux-hardware.org/?probe=b6ddb628dc) | Sep 04, 2023 |
| Acer          | Aspire A314-35              | [6edc4e910d](https://linux-hardware.org/?probe=6edc4e910d) | Sep 04, 2023 |
| HP            | EliteBook Revolve 810 G2    | [3f102b35e3](https://linux-hardware.org/?probe=3f102b35e3) | Sep 04, 2023 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | [e27673ed4c](https://linux-hardware.org/?probe=e27673ed4c) | Sep 03, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [959fb04734](https://linux-hardware.org/?probe=959fb04734) | Sep 03, 2023 |
| Sony          | VPCYB15AG                   | [e192029ff0](https://linux-hardware.org/?probe=e192029ff0) | Sep 03, 2023 |
| Acer          | Aspire E5-475G              | [55542f9b89](https://linux-hardware.org/?probe=55542f9b89) | Aug 31, 2023 |
| Dell          | Latitude E6410              | [c2337bbe75](https://linux-hardware.org/?probe=c2337bbe75) | Aug 31, 2023 |
| Acer          | Aspire E5-411G              | [13ec5c53cf](https://linux-hardware.org/?probe=13ec5c53cf) | Aug 31, 2023 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | [5cfa9a748f](https://linux-hardware.org/?probe=5cfa9a748f) | Aug 31, 2023 |
| Dell          | Inspiron 3585               | [02708536f4](https://linux-hardware.org/?probe=02708536f4) | Aug 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [aa10544f35](https://linux-hardware.org/?probe=aa10544f35) | Aug 30, 2023 |
| Fujitsu       | FMVU14003                   | [8da3625e06](https://linux-hardware.org/?probe=8da3625e06) | Aug 27, 2023 |
| Lenovo        | IdeaPad Slim 1-11AST-05 ... | [5b334ec725](https://linux-hardware.org/?probe=5b334ec725) | Aug 27, 2023 |
| Acer          | Aspire E5-411G              | [1986877980](https://linux-hardware.org/?probe=1986877980) | Aug 25, 2023 |
| HP            | Laptop 15-db1xxx            | [2a72d00223](https://linux-hardware.org/?probe=2a72d00223) | Aug 25, 2023 |
| HP            | Victus by Gaming Laptop ... | [f79de96905](https://linux-hardware.org/?probe=f79de96905) | Aug 23, 2023 |
| Lenovo        | IdeaPad 130-14IKB 81H6      | [abae84243d](https://linux-hardware.org/?probe=abae84243d) | Aug 23, 2023 |
| Dell          | Latitude E6410              | [fbaef9218f](https://linux-hardware.org/?probe=fbaef9218f) | Aug 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [8fd1db4fee](https://linux-hardware.org/?probe=8fd1db4fee) | Aug 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [2cbbb89cd4](https://linux-hardware.org/?probe=2cbbb89cd4) | Aug 21, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [c1a5eb75bf](https://linux-hardware.org/?probe=c1a5eb75bf) | Aug 21, 2023 |
| HP            | Victus by Gaming Laptop ... | [c47971e406](https://linux-hardware.org/?probe=c47971e406) | Aug 21, 2023 |
| Lenovo        | ThinkPad T540p 20BFS02S0... | [2f59ec7141](https://linux-hardware.org/?probe=2f59ec7141) | Aug 18, 2023 |
| Infinix       | INBOOK X2 GEN11             | [f368b5bf17](https://linux-hardware.org/?probe=f368b5bf17) | Aug 18, 2023 |
| Toshiba       | Satellite L510              | [f06d068ca0](https://linux-hardware.org/?probe=f06d068ca0) | Aug 16, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | [b7a28997df](https://linux-hardware.org/?probe=b7a28997df) | Aug 15, 2023 |
| Acer          | Swift SF314-71              | [b78f4bf01d](https://linux-hardware.org/?probe=b78f4bf01d) | Aug 15, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20C0A0C... | [c192c37af2](https://linux-hardware.org/?probe=c192c37af2) | Aug 14, 2023 |
| MSI           | Katana GF66 11UD            | [e7e9bfd605](https://linux-hardware.org/?probe=e7e9bfd605) | Aug 13, 2023 |
| Samsung       | 960XFH                      | [b7f35fe8b5](https://linux-hardware.org/?probe=b7f35fe8b5) | Aug 13, 2023 |
| HP            | EliteBook 820 G3            | [544810db31](https://linux-hardware.org/?probe=544810db31) | Aug 12, 2023 |
| Acer          | TravelMate B113             | [5d3d27c8bb](https://linux-hardware.org/?probe=5d3d27c8bb) | Aug 12, 2023 |
| Acer          | One Z1402                   | [9fd6a2d41b](https://linux-hardware.org/?probe=9fd6a2d41b) | Aug 12, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | [fadee3e38d](https://linux-hardware.org/?probe=fadee3e38d) | Aug 11, 2023 |
| Lenovo        | G40-45 80E1                 | [49a3480efb](https://linux-hardware.org/?probe=49a3480efb) | Aug 11, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20C0A0C... | [6de592988e](https://linux-hardware.org/?probe=6de592988e) | Aug 09, 2023 |
| Acer          | Aspire 4752                 | [1c68b4d24a](https://linux-hardware.org/?probe=1c68b4d24a) | Aug 08, 2023 |
| Acer          | Aspire 4750                 | [8491f5fc3b](https://linux-hardware.org/?probe=8491f5fc3b) | Aug 07, 2023 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | [eab0544dc6](https://linux-hardware.org/?probe=eab0544dc6) | Aug 06, 2023 |
| HP            | ProBook 440 G3              | [abb19010d2](https://linux-hardware.org/?probe=abb19010d2) | Aug 05, 2023 |
| Dell          | Latitude E6410              | [ad46549b01](https://linux-hardware.org/?probe=ad46549b01) | Aug 04, 2023 |
| Dell          | Latitude E6410              | [e2364d5aac](https://linux-hardware.org/?probe=e2364d5aac) | Aug 04, 2023 |
| Lenovo        | ThinkPad Edge E330 33542... | [73e1dd94b2](https://linux-hardware.org/?probe=73e1dd94b2) | Aug 02, 2023 |
| Lenovo        | ThinkPad Edge E330 33542... | [a13fd4044e](https://linux-hardware.org/?probe=a13fd4044e) | Aug 01, 2023 |
| ASUSTek       | TUF Gaming FX505DD          | [e965235133](https://linux-hardware.org/?probe=e965235133) | Jul 29, 2023 |
| Acer          | Aspire A315-42              | [3afa5a3034](https://linux-hardware.org/?probe=3afa5a3034) | Jul 27, 2023 |
| HP            | ENVY Laptop 13-aq0xxx       | [6632226064](https://linux-hardware.org/?probe=6632226064) | Jul 26, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [24c092f0b0](https://linux-hardware.org/?probe=24c092f0b0) | Jul 26, 2023 |
| Lenovo        | ThinkPad X230 23246V9       | [e7bc7dac48](https://linux-hardware.org/?probe=e7bc7dac48) | Jul 24, 2023 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [c16c981a88](https://linux-hardware.org/?probe=c16c981a88) | Jul 24, 2023 |
| Fujitsu       | FMVNC4BC4                   | [14249b136a](https://linux-hardware.org/?probe=14249b136a) | Jul 19, 2023 |
| Acer          | Aspire E5-476G              | [74af6477be](https://linux-hardware.org/?probe=74af6477be) | Jul 19, 2023 |
| Lenovo        | IdeaPad 130-14IKB 81H6      | [3649d91857](https://linux-hardware.org/?probe=3649d91857) | Jul 18, 2023 |
| Acer          | Swift SF314-71              | [462a41184d](https://linux-hardware.org/?probe=462a41184d) | Jul 17, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | [94555c5887](https://linux-hardware.org/?probe=94555c5887) | Jul 10, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [de7dbebf49](https://linux-hardware.org/?probe=de7dbebf49) | Jul 10, 2023 |
| Acer          | Aspire 4937                 | [fe9bfd5f77](https://linux-hardware.org/?probe=fe9bfd5f77) | Jul 10, 2023 |
| Acer          | Aspire 4937                 | [d4dadd2e77](https://linux-hardware.org/?probe=d4dadd2e77) | Jul 10, 2023 |
| HP            | ProBook 4420s               | [51e917f03e](https://linux-hardware.org/?probe=51e917f03e) | Jul 09, 2023 |
| Acer          | Aspire 4720Z                | [312486a5b7](https://linux-hardware.org/?probe=312486a5b7) | Jul 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [06b52888f8](https://linux-hardware.org/?probe=06b52888f8) | Jul 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [0048149cd5](https://linux-hardware.org/?probe=0048149cd5) | Jul 08, 2023 |
| Toshiba       | PORTEGE R30-C               | [f07f4d423b](https://linux-hardware.org/?probe=f07f4d423b) | Jul 07, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | [c5fcc4bcf0](https://linux-hardware.org/?probe=c5fcc4bcf0) | Jul 06, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | [f05e91be82](https://linux-hardware.org/?probe=f05e91be82) | Jul 06, 2023 |
| Toshiba       | Satellite C640              | [680f3038da](https://linux-hardware.org/?probe=680f3038da) | Jul 06, 2023 |
| HP            | Laptop 15-fc0xxx            | [a0183085b8](https://linux-hardware.org/?probe=a0183085b8) | Jul 06, 2023 |
| AZW           | Z85                         | [ca44d0b498](https://linux-hardware.org/?probe=ca44d0b498) | Jul 05, 2023 |
| Acer          | Aspire V5-471G              | [6dd5e93eea](https://linux-hardware.org/?probe=6dd5e93eea) | Jul 05, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | [f1ad74f37a](https://linux-hardware.org/?probe=f1ad74f37a) | Jul 05, 2023 |
| Dell          | Latitude E6540              | [17ec85df62](https://linux-hardware.org/?probe=17ec85df62) | Jul 05, 2023 |
| Dell          | Latitude 3410               | [11d9814008](https://linux-hardware.org/?probe=11d9814008) | Jul 02, 2023 |
| ASUSTek       | X201EV                      | [a3fe51bc01](https://linux-hardware.org/?probe=a3fe51bc01) | Jun 30, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [14a983e6d3](https://linux-hardware.org/?probe=14a983e6d3) | Jun 30, 2023 |
| ASUSTek       | X201EV                      | [3cffef17f3](https://linux-hardware.org/?probe=3cffef17f3) | Jun 30, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [5873d04afe](https://linux-hardware.org/?probe=5873d04afe) | Jun 29, 2023 |
| Alurin        | Go Notebook                 | [5f838f5922](https://linux-hardware.org/?probe=5f838f5922) | Jun 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [0c87fda1f9](https://linux-hardware.org/?probe=0c87fda1f9) | Jun 27, 2023 |
| Lenovo        | V14 G2 ALC 82KC             | [40cbc38a69](https://linux-hardware.org/?probe=40cbc38a69) | Jun 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [01a9e10a34](https://linux-hardware.org/?probe=01a9e10a34) | Jun 24, 2023 |
| Toshiba       | PORTEGE Z930                | [0cad0d9955](https://linux-hardware.org/?probe=0cad0d9955) | Jun 22, 2023 |
| Notebook      | P870DM                      | [cd318aa5a4](https://linux-hardware.org/?probe=cd318aa5a4) | Jun 21, 2023 |
| Dell          | G7 7588                     | [946a645897](https://linux-hardware.org/?probe=946a645897) | Jun 20, 2023 |
| Lenovo        | IdeaPad S410p 20296         | [6a6cfb05d6](https://linux-hardware.org/?probe=6a6cfb05d6) | Jun 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [42fd301e8b](https://linux-hardware.org/?probe=42fd301e8b) | Jun 19, 2023 |
| HP            | Laptop 17-ca0xxx            | [5296ca6ae2](https://linux-hardware.org/?probe=5296ca6ae2) | Jun 19, 2023 |
| HP            | Laptop 14s-dk1xxx           | [16bbd0f687](https://linux-hardware.org/?probe=16bbd0f687) | Jun 18, 2023 |
| HP            | Laptop 14-bw0xx             | [f38253d79c](https://linux-hardware.org/?probe=f38253d79c) | Jun 17, 2023 |
| Acer          | Aspire 4752                 | [441eb3fe51](https://linux-hardware.org/?probe=441eb3fe51) | Jun 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [d7e9625e19](https://linux-hardware.org/?probe=d7e9625e19) | Jun 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [eb0ba3c881](https://linux-hardware.org/?probe=eb0ba3c881) | Jun 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [78f12c4671](https://linux-hardware.org/?probe=78f12c4671) | Jun 07, 2023 |
| Acer          | Aspire E5-411G              | [9a69b50d97](https://linux-hardware.org/?probe=9a69b50d97) | Jun 07, 2023 |
| Infinix       | INBook X1 Pro               | [c558de3b74](https://linux-hardware.org/?probe=c558de3b74) | Jun 05, 2023 |
| Infinix       | INBOOK X2                   | [0a82b1aed3](https://linux-hardware.org/?probe=0a82b1aed3) | Jun 05, 2023 |
| Acer          | Swift SF314-511             | [6754a25d1d](https://linux-hardware.org/?probe=6754a25d1d) | Jun 03, 2023 |
| HP            | Laptop 14-bw0xx             | [3958079ad5](https://linux-hardware.org/?probe=3958079ad5) | Jun 03, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | [1034aea990](https://linux-hardware.org/?probe=1034aea990) | Jun 03, 2023 |
| AXIOO         | Mybook-14E                  | [cb04b551d8](https://linux-hardware.org/?probe=cb04b551d8) | May 31, 2023 |
| ASUSTek       | X456URK                     | [6de2588617](https://linux-hardware.org/?probe=6de2588617) | May 29, 2023 |
| ASUSTek       | X456URK                     | [369aa4fc93](https://linux-hardware.org/?probe=369aa4fc93) | May 29, 2023 |
| ASUSTek       | X455LF                      | [b90c1083ca](https://linux-hardware.org/?probe=b90c1083ca) | May 28, 2023 |
| AVITA         | NE14A2                      | [89c5edafbc](https://linux-hardware.org/?probe=89c5edafbc) | May 28, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [db7d7cf31d](https://linux-hardware.org/?probe=db7d7cf31d) | May 26, 2023 |
| Panasonic     | CFSZ5-2                     | [d5b1455382](https://linux-hardware.org/?probe=d5b1455382) | May 25, 2023 |
| HP            | Laptop 14s-cf2xxx           | [e51dec5daf](https://linux-hardware.org/?probe=e51dec5daf) | May 24, 2023 |
| ASUSTek       | Strix 17 GL703GE            | [e752398b87](https://linux-hardware.org/?probe=e752398b87) | May 23, 2023 |
| HP            | Laptop 14s-dk1xxx           | [d9f9d8c907](https://linux-hardware.org/?probe=d9f9d8c907) | May 22, 2023 |
| Lenovo        | ThinkPad X260 20F5S53600    | [cfdb07c9ca](https://linux-hardware.org/?probe=cfdb07c9ca) | May 21, 2023 |
| Lenovo        | ThinkPad X260 20F5S53600    | [379bcdafa9](https://linux-hardware.org/?probe=379bcdafa9) | May 21, 2023 |
| Sony          | VPCSB35FG                   | [81d2592989](https://linux-hardware.org/?probe=81d2592989) | May 20, 2023 |
| Sony          | VPCSB35FG                   | [828fb24994](https://linux-hardware.org/?probe=828fb24994) | May 20, 2023 |
| Acer          | One Z1402                   | [390a684064](https://linux-hardware.org/?probe=390a684064) | May 16, 2023 |
| ASUSTek       | GL502VMK                    | [0b7232826d](https://linux-hardware.org/?probe=0b7232826d) | May 13, 2023 |
| HP            | Laptop 14s-cf0xxx           | [6d0f055f82](https://linux-hardware.org/?probe=6d0f055f82) | May 11, 2023 |
| HP            | Laptop 14s-cf0xxx           | [7f90473be2](https://linux-hardware.org/?probe=7f90473be2) | May 11, 2023 |
| Infinix       | INBook X1                   | [c005323a1a](https://linux-hardware.org/?probe=c005323a1a) | May 11, 2023 |
| Dell          | Inspiron 3505               | [e8f10d5f7e](https://linux-hardware.org/?probe=e8f10d5f7e) | May 09, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [1b0786ec5e](https://linux-hardware.org/?probe=1b0786ec5e) | May 07, 2023 |
| ASUSTek       | K42Jc                       | [ba4b9c97f9](https://linux-hardware.org/?probe=ba4b9c97f9) | May 05, 2023 |
| ASUSTek       | K42Jc                       | [98d7593057](https://linux-hardware.org/?probe=98d7593057) | May 05, 2023 |
| Dell          | Latitude D630               | [0bef13413f](https://linux-hardware.org/?probe=0bef13413f) | May 05, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | [139c809251](https://linux-hardware.org/?probe=139c809251) | May 04, 2023 |
| Dell          | Latitude D630               | [d8ee0e7ca8](https://linux-hardware.org/?probe=d8ee0e7ca8) | May 02, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [9035ec79cd](https://linux-hardware.org/?probe=9035ec79cd) | May 02, 2023 |
| Acer          | Aspire A514-54G             | [adbd990ca2](https://linux-hardware.org/?probe=adbd990ca2) | Apr 29, 2023 |
| Dell          | Latitude D630               | [a3c3e09675](https://linux-hardware.org/?probe=a3c3e09675) | Apr 28, 2023 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [c1616fcd6c](https://linux-hardware.org/?probe=c1616fcd6c) | Apr 28, 2023 |
| Dell          | Latitude D630               | [850df6e76f](https://linux-hardware.org/?probe=850df6e76f) | Apr 26, 2023 |
| AXIOO         | MYBOOK-14 .B001             | [38d6a9b3d2](https://linux-hardware.org/?probe=38d6a9b3d2) | Apr 25, 2023 |
| HP            | Laptop 14-cm0xxx            | [4591d1bf9d](https://linux-hardware.org/?probe=4591d1bf9d) | Apr 24, 2023 |
| Valve         | Jupiter                     | [ff8440808f](https://linux-hardware.org/?probe=ff8440808f) | Apr 22, 2023 |
| Acer          | Swift SF314-511             | [96fd44e94a](https://linux-hardware.org/?probe=96fd44e94a) | Apr 20, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [6cf066b06b](https://linux-hardware.org/?probe=6cf066b06b) | Apr 19, 2023 |
| Acer          | Swift SFX14-41G             | [40ae403838](https://linux-hardware.org/?probe=40ae403838) | Apr 18, 2023 |
| AXIOO         | SlimBook 11                 | [b0c639ab77](https://linux-hardware.org/?probe=b0c639ab77) | Apr 15, 2023 |
| Dell          | Latitude 7300               | [1064b58edb](https://linux-hardware.org/?probe=1064b58edb) | Apr 13, 2023 |
| HP            | Laptop 14s-cf1xxx           | [76c9bf81a6](https://linux-hardware.org/?probe=76c9bf81a6) | Apr 12, 2023 |
| MSI           | Creator 15 A11UE            | [ca70d48c0e](https://linux-hardware.org/?probe=ca70d48c0e) | Apr 11, 2023 |
| HP            | Notebook                    | [584a741058](https://linux-hardware.org/?probe=584a741058) | Apr 08, 2023 |
| ASUSTek       | K46CM                       | [d878fad4d0](https://linux-hardware.org/?probe=d878fad4d0) | Apr 06, 2023 |
| Dell          | Latitude E5430 non-vPro     | [fcfcfdbbe7](https://linux-hardware.org/?probe=fcfcfdbbe7) | Apr 06, 2023 |
| Toshiba       | Satellite L640              | [8009d927db](https://linux-hardware.org/?probe=8009d927db) | Apr 05, 2023 |
| Lenovo        | ThinkPad Edge 0578RZ3       | [d37b6fa47b](https://linux-hardware.org/?probe=d37b6fa47b) | Apr 05, 2023 |
| Timi          | TM1703                      | [54b062157f](https://linux-hardware.org/?probe=54b062157f) | Apr 04, 2023 |
| AXIOO         | MYBOOK-14 .B001             | [edba1216c0](https://linux-hardware.org/?probe=edba1216c0) | Apr 04, 2023 |
| Dell          | Latitude 3410               | [0b29a27e88](https://linux-hardware.org/?probe=0b29a27e88) | Apr 03, 2023 |
| Dell          | Latitude 3410               | [9c8218ebd6](https://linux-hardware.org/?probe=9c8218ebd6) | Apr 03, 2023 |
| Acer          | Swift SFX14-41G             | [e60610d78a](https://linux-hardware.org/?probe=e60610d78a) | Apr 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [45c62cbb5c](https://linux-hardware.org/?probe=45c62cbb5c) | Apr 02, 2023 |
| Acer          | Aspire 4738Z                | [20e13078ef](https://linux-hardware.org/?probe=20e13078ef) | Apr 02, 2023 |
| Acer          | Aspire A515-56              | [a959d79d84](https://linux-hardware.org/?probe=a959d79d84) | Apr 01, 2023 |
| Acer          | Aspire A515-56              | [db53e1a333](https://linux-hardware.org/?probe=db53e1a333) | Apr 01, 2023 |
| HP            | 240 G6 Notebook PC          | [44e093df31](https://linux-hardware.org/?probe=44e093df31) | Apr 01, 2023 |
| Acer          | Aspire A514-53              | [4bb2babc0a](https://linux-hardware.org/?probe=4bb2babc0a) | Mar 31, 2023 |
| MSI           | Bravo 15 B5DD               | [6dac36ba2d](https://linux-hardware.org/?probe=6dac36ba2d) | Mar 28, 2023 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [0e8125dc1f](https://linux-hardware.org/?probe=0e8125dc1f) | Mar 28, 2023 |
| Acer          | Aspire E5-411G              | [4ac3cde372](https://linux-hardware.org/?probe=4ac3cde372) | Mar 27, 2023 |
| ASUSTek       | X555BA                      | [f7d51f3c2f](https://linux-hardware.org/?probe=f7d51f3c2f) | Mar 26, 2023 |
| Acer          | Swift SF314-511             | [55c1b171dd](https://linux-hardware.org/?probe=55c1b171dd) | Mar 25, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [ae09be520b](https://linux-hardware.org/?probe=ae09be520b) | Mar 25, 2023 |
| HP            | Pavilion 11 x360 PC         | [2c3c5a65a5](https://linux-hardware.org/?probe=2c3c5a65a5) | Mar 24, 2023 |
| MSI           | GF63 Thin 11SC              | [a63c9ded60](https://linux-hardware.org/?probe=a63c9ded60) | Mar 22, 2023 |
| MSI           | GF63 Thin 11SC              | [cc5ca6f040](https://linux-hardware.org/?probe=cc5ca6f040) | Mar 22, 2023 |
| Samsung       | RF511/RF411/RF711           | [bff0b1d8a4](https://linux-hardware.org/?probe=bff0b1d8a4) | Mar 20, 2023 |
| ASUSTek       | X540LJ                      | [4eab8887fa](https://linux-hardware.org/?probe=4eab8887fa) | Mar 18, 2023 |
| ASUSTek       | X540LJ                      | [b3bf824f3a](https://linux-hardware.org/?probe=b3bf824f3a) | Mar 18, 2023 |
| Samsung       | RF511/RF411/RF711           | [f3a832587b](https://linux-hardware.org/?probe=f3a832587b) | Mar 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [bc39bd2ce5](https://linux-hardware.org/?probe=bc39bd2ce5) | Mar 17, 2023 |
| Samsung       | RF511/RF411/RF711           | [ecb08b3c5e](https://linux-hardware.org/?probe=ecb08b3c5e) | Mar 17, 2023 |
| Samsung       | RV410/RV510/S3510/E3510     | [063ed79c8f](https://linux-hardware.org/?probe=063ed79c8f) | Mar 15, 2023 |
| Toshiba       | PORTEGE Z30t-C              | [7098d7537b](https://linux-hardware.org/?probe=7098d7537b) | Mar 15, 2023 |
| Lenovo        | G400s 20244                 | [fed6bb2c17](https://linux-hardware.org/?probe=fed6bb2c17) | Mar 13, 2023 |
| Dell          | Latitude E5440              | [fe81dc02b0](https://linux-hardware.org/?probe=fe81dc02b0) | Mar 13, 2023 |
| ASUSTek       | X455LF                      | [cda777dad9](https://linux-hardware.org/?probe=cda777dad9) | Mar 13, 2023 |
| AXIOO         | Mybook 14E                  | [1b6c10d1d8](https://linux-hardware.org/?probe=1b6c10d1d8) | Mar 13, 2023 |
| Lenovo        | ThinkPad T480s 20L8S2AX0... | [d6854dc15a](https://linux-hardware.org/?probe=d6854dc15a) | Mar 12, 2023 |
| Valve         | Jupiter                     | [f4ad14a82a](https://linux-hardware.org/?probe=f4ad14a82a) | Mar 08, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [439ea07bc5](https://linux-hardware.org/?probe=439ea07bc5) | Mar 08, 2023 |
| ADVAN         | 1405                        | [7f96f0214f](https://linux-hardware.org/?probe=7f96f0214f) | Mar 08, 2023 |
| Lenovo        | G40-80 80E4                 | [01dae27177](https://linux-hardware.org/?probe=01dae27177) | Mar 07, 2023 |
| Dell          | G7 7588                     | [a50e6bef64](https://linux-hardware.org/?probe=a50e6bef64) | Mar 06, 2023 |
| Lenovo        | ThinkPad T580 20LAS35M00    | [2cdcded03e](https://linux-hardware.org/?probe=2cdcded03e) | Mar 04, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [fa94a404fa](https://linux-hardware.org/?probe=fa94a404fa) | Mar 04, 2023 |
| Lenovo        | ThinkPad T580 20LAS35M00    | [9857559bb5](https://linux-hardware.org/?probe=9857559bb5) | Mar 03, 2023 |
| Lenovo        | ThinkPad T580 20LAS35M00    | [096c600c1d](https://linux-hardware.org/?probe=096c600c1d) | Mar 03, 2023 |
| Lenovo        | ThinkPad T580 20LAS35M00    | [cd8d61c1b6](https://linux-hardware.org/?probe=cd8d61c1b6) | Mar 03, 2023 |
| Google        | Vorticon                    | [7e9f3425ab](https://linux-hardware.org/?probe=7e9f3425ab) | Mar 03, 2023 |
| Google        | Vorticon                    | [aaa620e932](https://linux-hardware.org/?probe=aaa620e932) | Mar 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [cf806f07cb](https://linux-hardware.org/?probe=cf806f07cb) | Mar 02, 2023 |
| ASUSTek       | E202SA                      | [bccde0c9a5](https://linux-hardware.org/?probe=bccde0c9a5) | Feb 28, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | [169d8ef4a8](https://linux-hardware.org/?probe=169d8ef4a8) | Feb 26, 2023 |
| ASUSTek       | GL553VD                     | [302b65ed41](https://linux-hardware.org/?probe=302b65ed41) | Feb 25, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | [2ea850fc7e](https://linux-hardware.org/?probe=2ea850fc7e) | Feb 24, 2023 |
| Dell          | Inspiron 3476               | [58bff0319e](https://linux-hardware.org/?probe=58bff0319e) | Feb 24, 2023 |
| ASUSTek       | X441UA                      | [cd870fc3d3](https://linux-hardware.org/?probe=cd870fc3d3) | Feb 23, 2023 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [7acab84e04](https://linux-hardware.org/?probe=7acab84e04) | Feb 22, 2023 |
| Lenovo        | ThinkPad T460 20FMS06V00    | [d2aa21118e](https://linux-hardware.org/?probe=d2aa21118e) | Feb 21, 2023 |
| Lenovo        | IdeaPad 110-14AST 80TQ      | [2953555c08](https://linux-hardware.org/?probe=2953555c08) | Feb 19, 2023 |
| Lenovo        | B40-70 20392                | [7197aacb00](https://linux-hardware.org/?probe=7197aacb00) | Feb 16, 2023 |
| Acer          | Swift SF314-511             | [71778cedf9](https://linux-hardware.org/?probe=71778cedf9) | Feb 16, 2023 |
| ASUSTek       | X200MA                      | [b01624da44](https://linux-hardware.org/?probe=b01624da44) | Feb 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [f6e519323b](https://linux-hardware.org/?probe=f6e519323b) | Feb 15, 2023 |
| Acer          | Aspire 4750                 | [ac80c33464](https://linux-hardware.org/?probe=ac80c33464) | Feb 14, 2023 |
| Acer          | Aspire 4732Z                | [abf9d41a29](https://linux-hardware.org/?probe=abf9d41a29) | Feb 14, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [bf015f98c2](https://linux-hardware.org/?probe=bf015f98c2) | Feb 14, 2023 |
| Lenovo        | IdeaPad 110-14AST 80TQ      | [a8a5ef19de](https://linux-hardware.org/?probe=a8a5ef19de) | Feb 13, 2023 |
| HP            | EliteBook 745 G6            | [9fd578a21d](https://linux-hardware.org/?probe=9fd578a21d) | Feb 13, 2023 |
| Lenovo        | IdeaPad 110-14AST 80TQ      | [608ce76690](https://linux-hardware.org/?probe=608ce76690) | Feb 13, 2023 |
| Toshiba       | Satellite L510              | [706759d61d](https://linux-hardware.org/?probe=706759d61d) | Feb 12, 2023 |
| Dell          | Vostro 3400                 | [89365a25ee](https://linux-hardware.org/?probe=89365a25ee) | Feb 12, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | [f8f0fb1a21](https://linux-hardware.org/?probe=f8f0fb1a21) | Feb 11, 2023 |
| Timi          | RedmiBook 15                | [6dffda8f11](https://linux-hardware.org/?probe=6dffda8f11) | Feb 10, 2023 |
| Dell          | Studio XPS 1340             | [4c96fdcf99](https://linux-hardware.org/?probe=4c96fdcf99) | Feb 09, 2023 |
| Lenovo        | IdeaPad 5 14IAL7 82SD       | [86297e5638](https://linux-hardware.org/?probe=86297e5638) | Feb 09, 2023 |
| Toshiba       | Satellite L735              | [99f282862c](https://linux-hardware.org/?probe=99f282862c) | Feb 08, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | [06ffbacba3](https://linux-hardware.org/?probe=06ffbacba3) | Feb 08, 2023 |
| ASUSTek       | X455LF                      | [d60cd149fb](https://linux-hardware.org/?probe=d60cd149fb) | Feb 07, 2023 |
| ASUSTek       | P453UA                      | [476ff28577](https://linux-hardware.org/?probe=476ff28577) | Feb 06, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | [6fcc29607c](https://linux-hardware.org/?probe=6fcc29607c) | Feb 06, 2023 |
| Acer          | Aspire E5-476G              | [3b8e69dd3a](https://linux-hardware.org/?probe=3b8e69dd3a) | Feb 06, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | [cfc187a64c](https://linux-hardware.org/?probe=cfc187a64c) | Feb 05, 2023 |
| Acer          | Swift SFX14-41G             | [5f59acbf0d](https://linux-hardware.org/?probe=5f59acbf0d) | Feb 05, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [74bf135ed9](https://linux-hardware.org/?probe=74bf135ed9) | Jan 31, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [e0c723e305](https://linux-hardware.org/?probe=e0c723e305) | Jan 31, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [0c220851f3](https://linux-hardware.org/?probe=0c220851f3) | Jan 30, 2023 |
| Acer          | Swift SF314-71              | [41c052436a](https://linux-hardware.org/?probe=41c052436a) | Jan 30, 2023 |
| MSI           | Modern 14 A10RB             | [619a49b55d](https://linux-hardware.org/?probe=619a49b55d) | Jan 28, 2023 |
| ASUSTek       | X555LAB                     | [343025f50f](https://linux-hardware.org/?probe=343025f50f) | Jan 28, 2023 |
| Acer          | Swift SF314-511             | [c47b08d2a9](https://linux-hardware.org/?probe=c47b08d2a9) | Jan 27, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | [3b41afb262](https://linux-hardware.org/?probe=3b41afb262) | Jan 27, 2023 |
| HP            | 14                          | [53d080d83a](https://linux-hardware.org/?probe=53d080d83a) | Jan 27, 2023 |
| Dell          | Inspiron 3585               | [b41a540bb4](https://linux-hardware.org/?probe=b41a540bb4) | Jan 27, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | [acf75dbe88](https://linux-hardware.org/?probe=acf75dbe88) | Jan 26, 2023 |
| Acer          | Swift SF314-511             | [9c04ff43a3](https://linux-hardware.org/?probe=9c04ff43a3) | Jan 26, 2023 |
| Acer          | Aspire E1-421               | [16277f992b](https://linux-hardware.org/?probe=16277f992b) | Jan 23, 2023 |
| HP            | EliteBook 745 G3            | [1fda4d1e4a](https://linux-hardware.org/?probe=1fda4d1e4a) | Jan 23, 2023 |
| Acer          | Swift SF314-71              | [9cee6edc8e](https://linux-hardware.org/?probe=9cee6edc8e) | Jan 20, 2023 |
| ASUSTek       | X442URR                     | [6104ee1f65](https://linux-hardware.org/?probe=6104ee1f65) | Jan 20, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [87f11d2b18](https://linux-hardware.org/?probe=87f11d2b18) | Jan 19, 2023 |
| ASUSTek       | X455LF                      | [9995b86c04](https://linux-hardware.org/?probe=9995b86c04) | Jan 18, 2023 |
| Acer          | Aspire E1-421               | [855c9b8e45](https://linux-hardware.org/?probe=855c9b8e45) | Jan 18, 2023 |
| Lenovo        | IdeaPad 3 14ARE05 81W3      | [804fe39b80](https://linux-hardware.org/?probe=804fe39b80) | Jan 16, 2023 |
| Lenovo        | ThinkPad T480 20L50011US    | [6a0a4494d3](https://linux-hardware.org/?probe=6a0a4494d3) | Jan 16, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | [58f2d0e1b4](https://linux-hardware.org/?probe=58f2d0e1b4) | Jan 12, 2023 |
| HP            | Laptop 14-bw0xx             | [0092ec8702](https://linux-hardware.org/?probe=0092ec8702) | Jan 12, 2023 |
| ASUSTek       | X456URK                     | [09c6b0ed0a](https://linux-hardware.org/?probe=09c6b0ed0a) | Jan 12, 2023 |
| Acer          | AO756                       | [e0332e892a](https://linux-hardware.org/?probe=e0332e892a) | Jan 11, 2023 |
| HP            | EliteBook 840 G3            | [5de089f4c0](https://linux-hardware.org/?probe=5de089f4c0) | Jan 08, 2023 |
| HP            | EliteBook 840 G3            | [d47b3555d6](https://linux-hardware.org/?probe=d47b3555d6) | Jan 08, 2023 |
| Dell          | Inspiron N4030              | [efaaf759cb](https://linux-hardware.org/?probe=efaaf759cb) | Jan 08, 2023 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [8056078760](https://linux-hardware.org/?probe=8056078760) | Jan 07, 2023 |
| ASUSTek       | X441NA                      | [e546680389](https://linux-hardware.org/?probe=e546680389) | Jan 07, 2023 |
| ASUSTek       | X441NA                      | [d556eedbbf](https://linux-hardware.org/?probe=d556eedbbf) | Jan 07, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [b8e1b2ec8e](https://linux-hardware.org/?probe=b8e1b2ec8e) | Jan 07, 2023 |
| Acer          | Swift SF314-71              | [7fa69ddddb](https://linux-hardware.org/?probe=7fa69ddddb) | Jan 07, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [8ac0b43549](https://linux-hardware.org/?probe=8ac0b43549) | Jan 05, 2023 |
| Lenovo        | B40-70 20392                | [71c1ae09af](https://linux-hardware.org/?probe=71c1ae09af) | Jan 05, 2023 |
| ASUSTek       | X453MA                      | [1584b0616c](https://linux-hardware.org/?probe=1584b0616c) | Jan 03, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | [86cf09380a](https://linux-hardware.org/?probe=86cf09380a) | Jan 02, 2023 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [d99426e3d5](https://linux-hardware.org/?probe=d99426e3d5) | Jan 01, 2023 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [7e7df16316](https://linux-hardware.org/?probe=7e7df16316) | Jan 01, 2023 |
| Lenovo        | IdeaPad 320-14AST 80XU      | [56e961b0ca](https://linux-hardware.org/?probe=56e961b0ca) | Jan 01, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [9f2441851f](https://linux-hardware.org/?probe=9f2441851f) | Dec 31, 2022 |
| Acer          | TravelMate P214             | [436186d9e5](https://linux-hardware.org/?probe=436186d9e5) | Dec 30, 2022 |
| Lenovo        | ThinkPad X240 20AMS1J60B    | [1d8fcd4a75](https://linux-hardware.org/?probe=1d8fcd4a75) | Dec 30, 2022 |
| ASUSTek       | X540YA                      | [d128cfee28](https://linux-hardware.org/?probe=d128cfee28) | Dec 29, 2022 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [b6413f9cf2](https://linux-hardware.org/?probe=b6413f9cf2) | Dec 28, 2022 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [4ddf1fecb8](https://linux-hardware.org/?probe=4ddf1fecb8) | Dec 28, 2022 |
| Lenovo        | V310-14ISK 80SX             | [a1e4dd02b2](https://linux-hardware.org/?probe=a1e4dd02b2) | Dec 27, 2022 |
| Lenovo        | V310-14ISK 80SX             | [cedf39754e](https://linux-hardware.org/?probe=cedf39754e) | Dec 27, 2022 |
| Lenovo        | IdeaPad S110 20126          | [dd7fd03edd](https://linux-hardware.org/?probe=dd7fd03edd) | Dec 24, 2022 |
| Acer          | Swift SF314-71              | [36d833d9c2](https://linux-hardware.org/?probe=36d833d9c2) | Dec 20, 2022 |
| Acer          | Swift SF314-71              | [c065eec185](https://linux-hardware.org/?probe=c065eec185) | Dec 20, 2022 |
| ASUSTek       | X45C                        | [80377ba23f](https://linux-hardware.org/?probe=80377ba23f) | Dec 17, 2022 |
| MSI           | Modern 14 B4MW              | [19e6ba206d](https://linux-hardware.org/?probe=19e6ba206d) | Dec 16, 2022 |
| Lenovo        | G40-30 80FY                 | [b9184a9ade](https://linux-hardware.org/?probe=b9184a9ade) | Dec 16, 2022 |
| Acer          | EX-215-52                   | [25201732ef](https://linux-hardware.org/?probe=25201732ef) | Dec 14, 2022 |
| Acer          | EX-215-52                   | [4cb72a8770](https://linux-hardware.org/?probe=4cb72a8770) | Dec 14, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [b08795ce45](https://linux-hardware.org/?probe=b08795ce45) | Dec 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [24fefa1408](https://linux-hardware.org/?probe=24fefa1408) | Dec 13, 2022 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [ed087084fb](https://linux-hardware.org/?probe=ed087084fb) | Dec 12, 2022 |
| Lenovo        | G40-30 80FY                 | [1a330e248d](https://linux-hardware.org/?probe=1a330e248d) | Dec 11, 2022 |
| ASUSTek       | T100TA                      | [efd7016171](https://linux-hardware.org/?probe=efd7016171) | Dec 11, 2022 |
| HP            | Laptop 14-bw0xx             | [3f3a7f6841](https://linux-hardware.org/?probe=3f3a7f6841) | Dec 09, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [5250630bdd](https://linux-hardware.org/?probe=5250630bdd) | Dec 09, 2022 |
| Acer          | Unknown                     | [b4eea49cf7](https://linux-hardware.org/?probe=b4eea49cf7) | Dec 09, 2022 |
| Lenovo        | ThinkPad L530 24783R8       | [406c066d36](https://linux-hardware.org/?probe=406c066d36) | Dec 08, 2022 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [c2d30310e8](https://linux-hardware.org/?probe=c2d30310e8) | Dec 06, 2022 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [a978cbc03b](https://linux-hardware.org/?probe=a978cbc03b) | Dec 06, 2022 |
| Acer          | One Z1401                   | [835ad73eff](https://linux-hardware.org/?probe=835ad73eff) | Dec 05, 2022 |
| Toshiba       | dynabook R63/P              | [f51571b62c](https://linux-hardware.org/?probe=f51571b62c) | Dec 04, 2022 |
| MSI           | Modern 14 B4MW              | [897f477f2d](https://linux-hardware.org/?probe=897f477f2d) | Dec 04, 2022 |
| MSI           | Modern 14 B4MW              | [9f512598e2](https://linux-hardware.org/?probe=9f512598e2) | Dec 04, 2022 |
| Dell          | Latitude 3420               | [23e8b890d2](https://linux-hardware.org/?probe=23e8b890d2) | Dec 03, 2022 |
| Lenovo        | B40-70 20392                | [a527c5b6e6](https://linux-hardware.org/?probe=a527c5b6e6) | Dec 01, 2022 |
| ASUSTek       | E203NAH                     | [3d091ea214](https://linux-hardware.org/?probe=3d091ea214) | Nov 30, 2022 |
| Dell          | Latitude E6440              | [0c3dd709dd](https://linux-hardware.org/?probe=0c3dd709dd) | Nov 30, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [4a49152177](https://linux-hardware.org/?probe=4a49152177) | Nov 29, 2022 |
| Lenovo        | V310-14IKB 80T2             | [b7c976ef9c](https://linux-hardware.org/?probe=b7c976ef9c) | Nov 29, 2022 |
| HP            | Laptop 14s-dq5xxx           | [9bb72cb3e8](https://linux-hardware.org/?probe=9bb72cb3e8) | Nov 28, 2022 |
| HP            | Laptop 14s-dq5xxx           | [e5164649e1](https://linux-hardware.org/?probe=e5164649e1) | Nov 27, 2022 |
| Dell          | Inspiron 3521               | [74d291cf07](https://linux-hardware.org/?probe=74d291cf07) | Nov 24, 2022 |
| Dell          | Inspiron 3521               | [4f0d293e99](https://linux-hardware.org/?probe=4f0d293e99) | Nov 24, 2022 |
| Dell          | Latitude E6230              | [28b93e0f7c](https://linux-hardware.org/?probe=28b93e0f7c) | Nov 23, 2022 |
| HP            | Laptop 14-bw0xx             | [5d4e847eef](https://linux-hardware.org/?probe=5d4e847eef) | Nov 23, 2022 |
| Lenovo        | G40-45 80E1                 | [c50111eb6d](https://linux-hardware.org/?probe=c50111eb6d) | Nov 22, 2022 |
| Acer          | Aspire 4736                 | [5f72d40c0e](https://linux-hardware.org/?probe=5f72d40c0e) | Nov 22, 2022 |
| Acer          | Aspire 4736                 | [e6acabebb2](https://linux-hardware.org/?probe=e6acabebb2) | Nov 21, 2022 |
| ASUSTek       | X45C                        | [02a232c4ef](https://linux-hardware.org/?probe=02a232c4ef) | Nov 21, 2022 |
| ASUSTek       | X455YA                      | [70267d756a](https://linux-hardware.org/?probe=70267d756a) | Nov 21, 2022 |
| Dell          | Latitude E6520              | [855dc4dadd](https://linux-hardware.org/?probe=855dc4dadd) | Nov 20, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [95b46d1513](https://linux-hardware.org/?probe=95b46d1513) | Nov 18, 2022 |
| Lenovo        | ThinkPad X201 36809T1       | [aad9f7cbaf](https://linux-hardware.org/?probe=aad9f7cbaf) | Nov 16, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [4c05f821c1](https://linux-hardware.org/?probe=4c05f821c1) | Nov 16, 2022 |
| Acer          | Swift SF314-71              | [c1eca34f9c](https://linux-hardware.org/?probe=c1eca34f9c) | Nov 15, 2022 |
| Intel         | SandyBridge Platform        | [7019c7ba85](https://linux-hardware.org/?probe=7019c7ba85) | Nov 13, 2022 |
| Acer          | AO722                       | [5c51412f98](https://linux-hardware.org/?probe=5c51412f98) | Nov 12, 2022 |
| Lenovo        | IdeaPad S410p 20296         | [77f7b2ff84](https://linux-hardware.org/?probe=77f7b2ff84) | Nov 10, 2022 |
| Lenovo        | ThinkPad P52s 20LB0026US    | [9443a4ceda](https://linux-hardware.org/?probe=9443a4ceda) | Nov 08, 2022 |
| Toshiba       | Satellite L15-B             | [b7a5fabbbd](https://linux-hardware.org/?probe=b7a5fabbbd) | Nov 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [234729e8b5](https://linux-hardware.org/?probe=234729e8b5) | Nov 08, 2022 |
| GPD           | G1619-04                    | [0c0542ac2e](https://linux-hardware.org/?probe=0c0542ac2e) | Nov 07, 2022 |
| MSI           | Modern 14 B5M               | [c2e7afc800](https://linux-hardware.org/?probe=c2e7afc800) | Nov 07, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [82048cfa4a](https://linux-hardware.org/?probe=82048cfa4a) | Nov 06, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [98e419a04d](https://linux-hardware.org/?probe=98e419a04d) | Nov 03, 2022 |
| AXIOO         | SlimBook 11                 | [ffc6980bf3](https://linux-hardware.org/?probe=ffc6980bf3) | Nov 03, 2022 |
| AXIOO         | SlimBook 11                 | [a16eac12d2](https://linux-hardware.org/?probe=a16eac12d2) | Nov 03, 2022 |
| Intel         | SandyBridge Platform        | [88c15d34e4](https://linux-hardware.org/?probe=88c15d34e4) | Nov 03, 2022 |
| Acer          | Aspire A514-55              | [391048b46f](https://linux-hardware.org/?probe=391048b46f) | Nov 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [49d6eb853f](https://linux-hardware.org/?probe=49d6eb853f) | Nov 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [5de7efb403](https://linux-hardware.org/?probe=5de7efb403) | Nov 01, 2022 |
| Acer          | Aspire A514-55              | [142e1c0695](https://linux-hardware.org/?probe=142e1c0695) | Oct 31, 2022 |
| Acer          | Aspire A514-55              | [87f4a137dc](https://linux-hardware.org/?probe=87f4a137dc) | Oct 31, 2022 |
| ASUSTek       | X453MA                      | [da3e45d6c3](https://linux-hardware.org/?probe=da3e45d6c3) | Oct 29, 2022 |
| AXIOO         | Mybook 14H                  | [f8a7c19640](https://linux-hardware.org/?probe=f8a7c19640) | Oct 29, 2022 |
| MSI           | GF63 Thin 11UD              | [0084d271e4](https://linux-hardware.org/?probe=0084d271e4) | Oct 28, 2022 |
| Acer          | Swift SFX14-41G             | [a490ccddeb](https://linux-hardware.org/?probe=a490ccddeb) | Oct 25, 2022 |
| Lenovo        | V310-14IKB 80T2             | [73f18a6fbb](https://linux-hardware.org/?probe=73f18a6fbb) | Oct 24, 2022 |
| ASUSTek       | T100TA                      | [0ceb92e552](https://linux-hardware.org/?probe=0ceb92e552) | Oct 21, 2022 |
| Lenovo        | V310-14IKB 80T2             | [8a0f6b66e6](https://linux-hardware.org/?probe=8a0f6b66e6) | Oct 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [669c715fa8](https://linux-hardware.org/?probe=669c715fa8) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [ddee1b5408](https://linux-hardware.org/?probe=ddee1b5408) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [3b87b259c8](https://linux-hardware.org/?probe=3b87b259c8) | Oct 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [e438393dca](https://linux-hardware.org/?probe=e438393dca) | Oct 19, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [b7a14994b1](https://linux-hardware.org/?probe=b7a14994b1) | Oct 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [d78ecde0a2](https://linux-hardware.org/?probe=d78ecde0a2) | Oct 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [adda30ef79](https://linux-hardware.org/?probe=adda30ef79) | Oct 17, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | [665763812f](https://linux-hardware.org/?probe=665763812f) | Oct 16, 2022 |
| Dell          | Latitude 3490               | [a739a29b72](https://linux-hardware.org/?probe=a739a29b72) | Oct 16, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [babb66e9c9](https://linux-hardware.org/?probe=babb66e9c9) | Oct 16, 2022 |
| Acer          | Aspire A314-22              | [eff5a7242e](https://linux-hardware.org/?probe=eff5a7242e) | Oct 15, 2022 |
| Intel         | SandyBridge Platform        | [3cc3d23297](https://linux-hardware.org/?probe=3cc3d23297) | Oct 14, 2022 |
| ASUSTek       | X455LD                      | [ae520872e3](https://linux-hardware.org/?probe=ae520872e3) | Oct 14, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | [7c6c3783e6](https://linux-hardware.org/?probe=7c6c3783e6) | Oct 14, 2022 |
| Apple         | MacBookPro5,3               | [814a533c23](https://linux-hardware.org/?probe=814a533c23) | Oct 13, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [ce1dbed861](https://linux-hardware.org/?probe=ce1dbed861) | Oct 12, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [46bc0c74c6](https://linux-hardware.org/?probe=46bc0c74c6) | Oct 11, 2022 |
| AXIOO         | Slimbook 13                 | [221b0b500d](https://linux-hardware.org/?probe=221b0b500d) | Oct 09, 2022 |
| Acer          | Aspire 4736                 | [48b8af7bcf](https://linux-hardware.org/?probe=48b8af7bcf) | Oct 04, 2022 |
| HP            | 240 G7 Notebook PC          | [05b4e2117b](https://linux-hardware.org/?probe=05b4e2117b) | Oct 03, 2022 |
| Acer          | Aspire ES1-522              | [b5c516677a](https://linux-hardware.org/?probe=b5c516677a) | Oct 02, 2022 |
| Acer          | Aspire ES1-522              | [86e57e249a](https://linux-hardware.org/?probe=86e57e249a) | Oct 02, 2022 |
| HP            | EliteBook 745 G6            | [ce8e31b40d](https://linux-hardware.org/?probe=ce8e31b40d) | Oct 02, 2022 |
| HP            | Compaq 420                  | [d3e367cedc](https://linux-hardware.org/?probe=d3e367cedc) | Oct 01, 2022 |
| HP            | EliteBook 745 G6            | [25e087916a](https://linux-hardware.org/?probe=25e087916a) | Oct 01, 2022 |
| ASUSTek       | X450EA                      | [345600d392](https://linux-hardware.org/?probe=345600d392) | Sep 29, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [af7b986ff8](https://linux-hardware.org/?probe=af7b986ff8) | Sep 28, 2022 |
| Dell          | Latitude E6540              | [b2abaca929](https://linux-hardware.org/?probe=b2abaca929) | Sep 26, 2022 |
| Acer          | Aspire V5-471               | [66437a2187](https://linux-hardware.org/?probe=66437a2187) | Sep 26, 2022 |
| Acer          | Swift SF314-71              | [3414420bc7](https://linux-hardware.org/?probe=3414420bc7) | Sep 25, 2022 |
| Lenovo        | ThinkPad T430 2349NZ8       | [8f61a903c5](https://linux-hardware.org/?probe=8f61a903c5) | Sep 25, 2022 |
| Lenovo        | IdeaPad Geming 3 15ARH05... | [ab84311fcc](https://linux-hardware.org/?probe=ab84311fcc) | Sep 24, 2022 |
| Lenovo        | IdeaPad Geming 3 15ARH05... | [48a40a2f04](https://linux-hardware.org/?probe=48a40a2f04) | Sep 24, 2022 |
| Acer          | Aspire A314-22              | [31b11c4544](https://linux-hardware.org/?probe=31b11c4544) | Sep 24, 2022 |
| ASUSTek       | X453SA                      | [b879e569d1](https://linux-hardware.org/?probe=b879e569d1) | Sep 24, 2022 |
| ASUSTek       | X450EA                      | [79d9dab7dc](https://linux-hardware.org/?probe=79d9dab7dc) | Sep 24, 2022 |
| HP            | Pavilion 14                 | [277d97cc71](https://linux-hardware.org/?probe=277d97cc71) | Sep 23, 2022 |
| AXIOO         | SlimBook 11                 | [c658e4f48c](https://linux-hardware.org/?probe=c658e4f48c) | Sep 22, 2022 |
| ASUSTek       | X441BA                      | [e542a68ddf](https://linux-hardware.org/?probe=e542a68ddf) | Sep 21, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [64ff44a074](https://linux-hardware.org/?probe=64ff44a074) | Sep 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [f24f78c803](https://linux-hardware.org/?probe=f24f78c803) | Sep 19, 2022 |
| Acer          | Swift SF314-71              | [0c383a03ad](https://linux-hardware.org/?probe=0c383a03ad) | Sep 17, 2022 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | [d39fd89ab8](https://linux-hardware.org/?probe=d39fd89ab8) | Sep 15, 2022 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [26cdf51338](https://linux-hardware.org/?probe=26cdf51338) | Sep 15, 2022 |
| Toshiba       | Satellite C660              | [39b26715f0](https://linux-hardware.org/?probe=39b26715f0) | Sep 14, 2022 |
| Lenovo        | ThinkPad T450s 20BWS0S10... | [0fd5868b54](https://linux-hardware.org/?probe=0fd5868b54) | Sep 14, 2022 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | [aa0553a310](https://linux-hardware.org/?probe=aa0553a310) | Sep 13, 2022 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | [0c3d0800eb](https://linux-hardware.org/?probe=0c3d0800eb) | Sep 12, 2022 |
| ASUSTek       | X455LD                      | [c31dc64978](https://linux-hardware.org/?probe=c31dc64978) | Sep 12, 2022 |
| ASUSTek       | X453SA                      | [1446eda5e9](https://linux-hardware.org/?probe=1446eda5e9) | Sep 12, 2022 |
| Lenovo        | ZHAOYANG E47                | [7f1fab5ff0](https://linux-hardware.org/?probe=7f1fab5ff0) | Sep 11, 2022 |
| Acer          | Aspire E3-112               | [bfa4cc7ddc](https://linux-hardware.org/?probe=bfa4cc7ddc) | Sep 10, 2022 |
| ASUSTek       | X441NA                      | [05b7b3b122](https://linux-hardware.org/?probe=05b7b3b122) | Sep 08, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [983d14d741](https://linux-hardware.org/?probe=983d14d741) | Sep 06, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [c073d9fb9f](https://linux-hardware.org/?probe=c073d9fb9f) | Sep 03, 2022 |
| Toshiba       | Satellite C660              | [448c7a24e2](https://linux-hardware.org/?probe=448c7a24e2) | Sep 02, 2022 |
| ASUSTek       | T100TA                      | [fb4d9c8521](https://linux-hardware.org/?probe=fb4d9c8521) | Sep 02, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | [1fee695aec](https://linux-hardware.org/?probe=1fee695aec) | Sep 01, 2022 |
| Lenovo        | ThinkPad T460 20FMS08U00    | [d7457fd32a](https://linux-hardware.org/?probe=d7457fd32a) | Sep 01, 2022 |
| Lenovo        | IdeaPad S410p 20296         | [dac943f23a](https://linux-hardware.org/?probe=dac943f23a) | Sep 01, 2022 |
| Acer          | Aspire V5-431               | [5ac694007d](https://linux-hardware.org/?probe=5ac694007d) | Sep 01, 2022 |
| Lenovo        | IdeaPad 3 14ARE05 81W3      | [b8c22aafab](https://linux-hardware.org/?probe=b8c22aafab) | Sep 01, 2022 |
| Lenovo        | ThinkPad L512 259756M       | [3990fcfeed](https://linux-hardware.org/?probe=3990fcfeed) | Aug 30, 2022 |
| Infinix       | INBOOK X2                   | [02ae752ba2](https://linux-hardware.org/?probe=02ae752ba2) | Aug 29, 2022 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | [8fac02d016](https://linux-hardware.org/?probe=8fac02d016) | Aug 28, 2022 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | [d281087322](https://linux-hardware.org/?probe=d281087322) | Aug 28, 2022 |
| Dell          | Latitude 7280               | [d214e30b1e](https://linux-hardware.org/?probe=d214e30b1e) | Aug 27, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [9f3be0c9b5](https://linux-hardware.org/?probe=9f3be0c9b5) | Aug 25, 2022 |
| Lenovo        | ThinkPad X200 7458FZ3       | [232835b00b](https://linux-hardware.org/?probe=232835b00b) | Aug 21, 2022 |
| Acer          | One Z1402                   | [d4b5a11843](https://linux-hardware.org/?probe=d4b5a11843) | Aug 18, 2022 |
| Dell          | Inspiron N5010              | [a54395e915](https://linux-hardware.org/?probe=a54395e915) | Aug 18, 2022 |
| ASUSTek       | X453MA                      | [fa2c1b6a14](https://linux-hardware.org/?probe=fa2c1b6a14) | Aug 15, 2022 |
| Acer          | Nitro AN515-43              | [a7d615e104](https://linux-hardware.org/?probe=a7d615e104) | Aug 14, 2022 |
| HP            | 14                          | [92172385ef](https://linux-hardware.org/?probe=92172385ef) | Aug 13, 2022 |
| ASUSTek       | K43E                        | [fc2d9e330c](https://linux-hardware.org/?probe=fc2d9e330c) | Aug 11, 2022 |
| Acer          | Aspire 4732Z                | [73027b2cca](https://linux-hardware.org/?probe=73027b2cca) | Aug 07, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [6880ac8488](https://linux-hardware.org/?probe=6880ac8488) | Aug 06, 2022 |
| ASUSTek       | K43E                        | [373d77aec0](https://linux-hardware.org/?probe=373d77aec0) | Aug 04, 2022 |
| Acer          | Aspire E5-476G              | [9c842ec71c](https://linux-hardware.org/?probe=9c842ec71c) | Aug 03, 2022 |
| HP            | 431                         | [2f6caa3d47](https://linux-hardware.org/?probe=2f6caa3d47) | Aug 02, 2022 |
| HP            | 431                         | [68fa0d3ebc](https://linux-hardware.org/?probe=68fa0d3ebc) | Aug 02, 2022 |
| Lenovo        | ThinkPad X230 23245NJ       | [3c85e43b86](https://linux-hardware.org/?probe=3c85e43b86) | Aug 01, 2022 |
| HP            | 240 G8 Notebook PC          | [f4533284b4](https://linux-hardware.org/?probe=f4533284b4) | Aug 01, 2022 |
| Acer          | Z476                        | [ade85b90c1](https://linux-hardware.org/?probe=ade85b90c1) | Aug 01, 2022 |
| Dell          | Latitude E7250              | [2dd83a16c7](https://linux-hardware.org/?probe=2dd83a16c7) | Aug 01, 2022 |
| Sony          | VPCEA36FG                   | [6c742b6234](https://linux-hardware.org/?probe=6c742b6234) | Jul 30, 2022 |
| ASUSTek       | K43E                        | [f6d8225dd6](https://linux-hardware.org/?probe=f6d8225dd6) | Jul 28, 2022 |
| ASUSTek       | X455LF                      | [8e83c4492a](https://linux-hardware.org/?probe=8e83c4492a) | Jul 27, 2022 |
| Acer          | Aspire 4732Z                | [3d23b4bbdc](https://linux-hardware.org/?probe=3d23b4bbdc) | Jul 27, 2022 |
| ASUSTek       | X450CP                      | [dceda2fe9d](https://linux-hardware.org/?probe=dceda2fe9d) | Jul 27, 2022 |
| Dell          | G3 3579                     | [96fab186c3](https://linux-hardware.org/?probe=96fab186c3) | Jul 24, 2022 |
| ASUSTek       | N56VZ                       | [3813cc04d1](https://linux-hardware.org/?probe=3813cc04d1) | Jul 22, 2022 |
| Lenovo        | ThinkPad X240 20AMS0PB11    | [a6e3ee128e](https://linux-hardware.org/?probe=a6e3ee128e) | Jul 20, 2022 |
| Lenovo        | V310-14ISK 80SX             | [6dcb934555](https://linux-hardware.org/?probe=6dcb934555) | Jul 17, 2022 |
| Acer          | Aspire E5-475G              | [1f7429b29d](https://linux-hardware.org/?probe=1f7429b29d) | Jul 15, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | [54c99c7f2f](https://linux-hardware.org/?probe=54c99c7f2f) | Jul 14, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [cf41c08ea5](https://linux-hardware.org/?probe=cf41c08ea5) | Jul 14, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [d651eb1f7d](https://linux-hardware.org/?probe=d651eb1f7d) | Jul 14, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [b04b2741a0](https://linux-hardware.org/?probe=b04b2741a0) | Jul 14, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [b00361cdbd](https://linux-hardware.org/?probe=b00361cdbd) | Jul 13, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [cde5f69fef](https://linux-hardware.org/?probe=cde5f69fef) | Jul 13, 2022 |
| HP            | Pavilion g4                 | [87a044a9c7](https://linux-hardware.org/?probe=87a044a9c7) | Jul 11, 2022 |
| Dell          | Latitude E6440              | [495237a0b0](https://linux-hardware.org/?probe=495237a0b0) | Jul 09, 2022 |
| Toshiba       | Satellite C640              | [cd8f69d739](https://linux-hardware.org/?probe=cd8f69d739) | Jul 07, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [dcd03a28be](https://linux-hardware.org/?probe=dcd03a28be) | Jul 06, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [0d03afb249](https://linux-hardware.org/?probe=0d03afb249) | Jul 05, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [d2dd306cb4](https://linux-hardware.org/?probe=d2dd306cb4) | Jul 04, 2022 |
| HP            | Laptop 14s-cf2xxx           | [8da2258fea](https://linux-hardware.org/?probe=8da2258fea) | Jul 01, 2022 |
| Lenovo        | ThinkPad L412 0585E86       | [ad82717c98](https://linux-hardware.org/?probe=ad82717c98) | Jul 01, 2022 |
| Acer          | Aspire 4732Z                | [1bf580aa91](https://linux-hardware.org/?probe=1bf580aa91) | Jun 30, 2022 |
| HP            | Laptop 14s-dk0xxx           | [97d88d7e00](https://linux-hardware.org/?probe=97d88d7e00) | Jun 30, 2022 |
| Apple         | MacBookPro12,1              | [3cec3cffbb](https://linux-hardware.org/?probe=3cec3cffbb) | Jun 30, 2022 |
| Apple         | MacBookPro12,1              | [bac4b49e55](https://linux-hardware.org/?probe=bac4b49e55) | Jun 30, 2022 |
| Acer          | Aspire A314-35              | [dfdd48254c](https://linux-hardware.org/?probe=dfdd48254c) | Jun 29, 2022 |
| ASUSTek       | K46CB                       | [3af9df185f](https://linux-hardware.org/?probe=3af9df185f) | Jun 26, 2022 |
| HP            | Pavilion g4                 | [d0c8c06219](https://linux-hardware.org/?probe=d0c8c06219) | Jun 24, 2022 |
| Fujitsu       | FMVS02003                   | [3536a9951f](https://linux-hardware.org/?probe=3536a9951f) | Jun 23, 2022 |
| Dell          | Precision M4500             | [e41b9f3386](https://linux-hardware.org/?probe=e41b9f3386) | Jun 22, 2022 |
| Apple         | MacBookPro14,1              | [e9d8c28a34](https://linux-hardware.org/?probe=e9d8c28a34) | Jun 22, 2022 |
| Acer          | Aspire A315-41              | [00a254b4ff](https://linux-hardware.org/?probe=00a254b4ff) | Jun 21, 2022 |
| Acer          | Aspire A315-41              | [4ca3721cbb](https://linux-hardware.org/?probe=4ca3721cbb) | Jun 20, 2022 |
| ASUSTek       | X450CC                      | [4d5fb8a789](https://linux-hardware.org/?probe=4d5fb8a789) | Jun 20, 2022 |
| ASUSTek       | X450CC                      | [9f7b97f22f](https://linux-hardware.org/?probe=9f7b97f22f) | Jun 20, 2022 |
| Apple         | MacBookPro12,1              | [666e91f182](https://linux-hardware.org/?probe=666e91f182) | Jun 20, 2022 |
| Apple         | MacBookPro12,1              | [5d9f65fbc9](https://linux-hardware.org/?probe=5d9f65fbc9) | Jun 20, 2022 |
| AXIOO         | Mybook 14E                  | [499861f5e9](https://linux-hardware.org/?probe=499861f5e9) | Jun 19, 2022 |
| Dell          | Inspiron 3442               | [b71d801e61](https://linux-hardware.org/?probe=b71d801e61) | Jun 18, 2022 |
| ASUSTek       | K46CB                       | [a6cc4351be](https://linux-hardware.org/?probe=a6cc4351be) | Jun 17, 2022 |
| ASUSTek       | K46CB                       | [fe4f649d9b](https://linux-hardware.org/?probe=fe4f649d9b) | Jun 17, 2022 |
| HP            | Laptop 14s-fq0xxx           | [0a77925edb](https://linux-hardware.org/?probe=0a77925edb) | Jun 10, 2022 |
| Acer          | AO756                       | [008fa33f13](https://linux-hardware.org/?probe=008fa33f13) | Jun 09, 2022 |
| Acer          | Aspire A514-54G             | [a74cd897c5](https://linux-hardware.org/?probe=a74cd897c5) | Jun 09, 2022 |
| MSI           | Prestige 14 A11SC           | [ea39fa65a1](https://linux-hardware.org/?probe=ea39fa65a1) | Jun 09, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [bdb3bbe37f](https://linux-hardware.org/?probe=bdb3bbe37f) | Jun 07, 2022 |
| Lenovo        | Z41-70 80K5                 | [3419d2fd18](https://linux-hardware.org/?probe=3419d2fd18) | Jun 06, 2022 |
| HP            | Pavilion 15                 | [5e4d9a126e](https://linux-hardware.org/?probe=5e4d9a126e) | Jun 05, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [41862e04b8](https://linux-hardware.org/?probe=41862e04b8) | Jun 03, 2022 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | [83cb6d1fe4](https://linux-hardware.org/?probe=83cb6d1fe4) | Jun 01, 2022 |
| Acer          | Aspire A514-54G             | [1019de0d68](https://linux-hardware.org/?probe=1019de0d68) | Jun 01, 2022 |
| ASUSTek       | N550JV                      | [2652284f1a](https://linux-hardware.org/?probe=2652284f1a) | May 31, 2022 |
| Acer          | Aspire 4720Z                | [a1dd5003f5](https://linux-hardware.org/?probe=a1dd5003f5) | May 30, 2022 |
| AXIOO         | NEON HNM MODEL              | [0fbd1cf4af](https://linux-hardware.org/?probe=0fbd1cf4af) | May 30, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [983144763a](https://linux-hardware.org/?probe=983144763a) | May 27, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [ecebcc6033](https://linux-hardware.org/?probe=ecebcc6033) | May 26, 2022 |
| ASUSTek       | GL502VMK                    | [dfca615a89](https://linux-hardware.org/?probe=dfca615a89) | May 25, 2022 |
| Lenovo        | G400 20235                  | [351b94ec15](https://linux-hardware.org/?probe=351b94ec15) | May 25, 2022 |
| HP            | 1000                        | [e83bc1e8fe](https://linux-hardware.org/?probe=e83bc1e8fe) | May 24, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [1b061ef293](https://linux-hardware.org/?probe=1b061ef293) | May 24, 2022 |
| Acer          | Swift SFX14-41G             | [da40fdda29](https://linux-hardware.org/?probe=da40fdda29) | May 22, 2022 |
| ASUSTek       | K43U                        | [a46669147d](https://linux-hardware.org/?probe=a46669147d) | May 21, 2022 |
| MSI           | Modern 14 B11MO             | [c3b01c8c1b](https://linux-hardware.org/?probe=c3b01c8c1b) | May 20, 2022 |
| ASUSTek       | K43U                        | [2748cd44f0](https://linux-hardware.org/?probe=2748cd44f0) | May 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [843a31b222](https://linux-hardware.org/?probe=843a31b222) | May 17, 2022 |
| Apple         | MacBookPro9,2               | [cfba770336](https://linux-hardware.org/?probe=cfba770336) | May 17, 2022 |
| Apple         | MacBookPro9,2               | [c19acfde6f](https://linux-hardware.org/?probe=c19acfde6f) | May 17, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [1661f9e71d](https://linux-hardware.org/?probe=1661f9e71d) | May 16, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [e633129a51](https://linux-hardware.org/?probe=e633129a51) | May 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [ffbf67b890](https://linux-hardware.org/?probe=ffbf67b890) | May 12, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [7aaffeda48](https://linux-hardware.org/?probe=7aaffeda48) | May 12, 2022 |
| MSI           | Modern 14 B5M               | [b207ce7566](https://linux-hardware.org/?probe=b207ce7566) | May 12, 2022 |
| Acer          | Aspire E5-476G              | [98b0999339](https://linux-hardware.org/?probe=98b0999339) | May 12, 2022 |
| Acer          | Aspire E5-476G              | [c4e0e740bb](https://linux-hardware.org/?probe=c4e0e740bb) | May 12, 2022 |
| Acer          | V1.24                       | [186531d4d8](https://linux-hardware.org/?probe=186531d4d8) | May 11, 2022 |
| Sony          | SVS13137PGB                 | [6dd2b49c52](https://linux-hardware.org/?probe=6dd2b49c52) | May 10, 2022 |
| Acer          | Nitro AN515-52              | [5122079c78](https://linux-hardware.org/?probe=5122079c78) | May 10, 2022 |
| Acer          | Swift SF314-41              | [108b57a5a7](https://linux-hardware.org/?probe=108b57a5a7) | May 10, 2022 |
| Acer          | Aspire A514-54G             | [ec1fa8e360](https://linux-hardware.org/?probe=ec1fa8e360) | May 08, 2022 |
| Acer          | Aspire A514-54G             | [b4b52aad69](https://linux-hardware.org/?probe=b4b52aad69) | May 07, 2022 |
| Acer          | Aspire V5-431               | [04db0db85f](https://linux-hardware.org/?probe=04db0db85f) | May 05, 2022 |
| HP            | Pavilion Laptop 14-bf0xx    | [4dcc86a60e](https://linux-hardware.org/?probe=4dcc86a60e) | May 03, 2022 |
| MSI           | Modern 14 B5M               | [04dee023e6](https://linux-hardware.org/?probe=04dee023e6) | May 01, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | [db2efb40d4](https://linux-hardware.org/?probe=db2efb40d4) | May 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [af3efcde26](https://linux-hardware.org/?probe=af3efcde26) | Apr 29, 2022 |
| ASUSTek       | X200MA                      | [f93f8fcb35](https://linux-hardware.org/?probe=f93f8fcb35) | Apr 28, 2022 |
| Dell          | Latitude E6510              | [10d60e00c2](https://linux-hardware.org/?probe=10d60e00c2) | Apr 27, 2022 |
| ASUSTek       | X455LD                      | [9f98b410f6](https://linux-hardware.org/?probe=9f98b410f6) | Apr 26, 2022 |
| Gigabyte      | M912                        | [fd0834889a](https://linux-hardware.org/?probe=fd0834889a) | Apr 25, 2022 |
| ASUSTek       | X450LCP                     | [a2ed4903be](https://linux-hardware.org/?probe=a2ed4903be) | Apr 23, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c90694a42c](https://linux-hardware.org/?probe=c90694a42c) | Apr 23, 2022 |
| Gigabyte      | AERO 15XV8                  | [d52bc41f4c](https://linux-hardware.org/?probe=d52bc41f4c) | Apr 21, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [8273c9ecb4](https://linux-hardware.org/?probe=8273c9ecb4) | Apr 20, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [345734b3fd](https://linux-hardware.org/?probe=345734b3fd) | Apr 07, 2022 |
| Acer          | Aspire 4720Z                | [eb44050489](https://linux-hardware.org/?probe=eb44050489) | Apr 07, 2022 |
| Lenovo        | ThinkPad T450 20BV0001US    | [f72149904c](https://linux-hardware.org/?probe=f72149904c) | Apr 05, 2022 |
| ASUSTek       | X455YA                      | [cf17e2bba2](https://linux-hardware.org/?probe=cf17e2bba2) | Apr 03, 2022 |
| Acer          | Aspire 4720Z                | [c3651e4d3d](https://linux-hardware.org/?probe=c3651e4d3d) | Apr 01, 2022 |
| Dell          | Latitude E6230              | [c45161f6f3](https://linux-hardware.org/?probe=c45161f6f3) | Mar 31, 2022 |
| HP            | Pavilion 14                 | [1b15a2e740](https://linux-hardware.org/?probe=1b15a2e740) | Mar 28, 2022 |
| Infinix       | INBook X1                   | [a06d137316](https://linux-hardware.org/?probe=a06d137316) | Mar 28, 2022 |
| MSI           | GF63 Thin 9SCXR             | [46acaeb2db](https://linux-hardware.org/?probe=46acaeb2db) | Mar 27, 2022 |
| Dell          | Latitude E7240              | [02c34ca310](https://linux-hardware.org/?probe=02c34ca310) | Mar 25, 2022 |
| ASUSTek       | X455YA                      | [b0469d5342](https://linux-hardware.org/?probe=b0469d5342) | Mar 25, 2022 |
| Sony          | VPCSB35FG                   | [79d0465072](https://linux-hardware.org/?probe=79d0465072) | Mar 23, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [3f4f125a64](https://linux-hardware.org/?probe=3f4f125a64) | Mar 23, 2022 |
| Acer          | Aspire 4750                 | [1b7f98b34d](https://linux-hardware.org/?probe=1b7f98b34d) | Mar 23, 2022 |
| ASUSTek       | X456UQK                     | [863693cc0a](https://linux-hardware.org/?probe=863693cc0a) | Mar 23, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [f0047d02ea](https://linux-hardware.org/?probe=f0047d02ea) | Mar 22, 2022 |
| Dell          | Inspiron 13-5368            | [d98411620e](https://linux-hardware.org/?probe=d98411620e) | Mar 21, 2022 |
| ASUSTek       | K46CA                       | [08985cbe9e](https://linux-hardware.org/?probe=08985cbe9e) | Mar 21, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [8793c924fe](https://linux-hardware.org/?probe=8793c924fe) | Mar 19, 2022 |
| Clevo         | W240HU/W250HUQ              | [222cbe9b4e](https://linux-hardware.org/?probe=222cbe9b4e) | Mar 18, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [fa74626a55](https://linux-hardware.org/?probe=fa74626a55) | Mar 16, 2022 |
| Lenovo        | V330-14IKB 81B0             | [06a3e2150b](https://linux-hardware.org/?probe=06a3e2150b) | Mar 16, 2022 |
| Lenovo        | V330-14IKB 81B0             | [73e48f6dc4](https://linux-hardware.org/?probe=73e48f6dc4) | Mar 16, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [8e9c955b47](https://linux-hardware.org/?probe=8e9c955b47) | Mar 15, 2022 |
| ASUSTek       | X441NA                      | [b7cf53ebcc](https://linux-hardware.org/?probe=b7cf53ebcc) | Mar 15, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [c334e9a1f6](https://linux-hardware.org/?probe=c334e9a1f6) | Mar 14, 2022 |
| HP            | Notebook                    | [6ae78b432d](https://linux-hardware.org/?probe=6ae78b432d) | Mar 12, 2022 |
| Dell          | Latitude E7240              | [fed08a1d40](https://linux-hardware.org/?probe=fed08a1d40) | Mar 12, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [e39d0d9111](https://linux-hardware.org/?probe=e39d0d9111) | Mar 11, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [f2a82ddf3b](https://linux-hardware.org/?probe=f2a82ddf3b) | Mar 11, 2022 |
| ASUSTek       | GL553VD                     | [5e43e1dd7b](https://linux-hardware.org/?probe=5e43e1dd7b) | Mar 11, 2022 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [ed4db5233e](https://linux-hardware.org/?probe=ed4db5233e) | Mar 10, 2022 |
| ASUSTek       | X450EA                      | [a7394d72a0](https://linux-hardware.org/?probe=a7394d72a0) | Mar 09, 2022 |
| MSI           | Modern 14 B10MW             | [661d068b83](https://linux-hardware.org/?probe=661d068b83) | Mar 08, 2022 |
| HP            | Pavilion g4                 | [3ff8cf8ed0](https://linux-hardware.org/?probe=3ff8cf8ed0) | Mar 08, 2022 |
| Sony          | VPCSB35FG                   | [b8a266ddc0](https://linux-hardware.org/?probe=b8a266ddc0) | Mar 08, 2022 |
| Lenovo        | ThinkPad X240 20AMS35500    | [af08ab87c5](https://linux-hardware.org/?probe=af08ab87c5) | Mar 07, 2022 |
| Toshiba       | PORTEGE R835                | [67e8021c81](https://linux-hardware.org/?probe=67e8021c81) | Mar 06, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [e7d5945f3d](https://linux-hardware.org/?probe=e7d5945f3d) | Mar 05, 2022 |
| Lenovo        | G40-45 80E1                 | [28f40df81d](https://linux-hardware.org/?probe=28f40df81d) | Mar 04, 2022 |
| ASUSTek       | UL20A                       | [c4efddb6b4](https://linux-hardware.org/?probe=c4efddb6b4) | Mar 02, 2022 |
| Fujitsu       | Unknown                     | [bc81b988ce](https://linux-hardware.org/?probe=bc81b988ce) | Mar 02, 2022 |
| Lenovo        | IdeaPad Z460 20059          | [621999b245](https://linux-hardware.org/?probe=621999b245) | Feb 24, 2022 |
| Dell          | Vostro 5470                 | [5ba37db2b4](https://linux-hardware.org/?probe=5ba37db2b4) | Feb 23, 2022 |
| Dell          | Latitude E7240              | [91cc26a6ac](https://linux-hardware.org/?probe=91cc26a6ac) | Feb 22, 2022 |
| Acer          | Aspire 4720Z                | [eba3609129](https://linux-hardware.org/?probe=eba3609129) | Feb 19, 2022 |
| MSI           | Modern 14 B10MW             | [beb5ff195a](https://linux-hardware.org/?probe=beb5ff195a) | Feb 18, 2022 |
| HP            | Laptop 14-bs0xx             | [2b5b67148b](https://linux-hardware.org/?probe=2b5b67148b) | Feb 18, 2022 |
| Acer          | One Z1402                   | [8746e0e3e7](https://linux-hardware.org/?probe=8746e0e3e7) | Feb 18, 2022 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | [1582806778](https://linux-hardware.org/?probe=1582806778) | Feb 17, 2022 |
| ASUSTek       | X540LA                      | [b2efca795b](https://linux-hardware.org/?probe=b2efca795b) | Feb 17, 2022 |
| Lenovo        | IdeaPad S410p 20296         | [e3dfc424ca](https://linux-hardware.org/?probe=e3dfc424ca) | Feb 16, 2022 |
| Fujitsu       | FMVNA1SE                    | [e2cd0bdcb5](https://linux-hardware.org/?probe=e2cd0bdcb5) | Feb 14, 2022 |
| Toshiba       | Satellite C840              | [cb53c43003](https://linux-hardware.org/?probe=cb53c43003) | Feb 13, 2022 |
| Lenovo        | IdeaPad S205 Brazos         | [402bdafb5f](https://linux-hardware.org/?probe=402bdafb5f) | Feb 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [46d98c991e](https://linux-hardware.org/?probe=46d98c991e) | Feb 12, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [5d4b14e3e0](https://linux-hardware.org/?probe=5d4b14e3e0) | Feb 12, 2022 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [eea0ec2b64](https://linux-hardware.org/?probe=eea0ec2b64) | Feb 12, 2022 |
| Toshiba       | Satellite C800D             | [5cdc03cbdf](https://linux-hardware.org/?probe=5cdc03cbdf) | Feb 10, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [54e246f496](https://linux-hardware.org/?probe=54e246f496) | Feb 09, 2022 |
| Lenovo        | IdeaPad Z460 20059          | [aa037a1c8c](https://linux-hardware.org/?probe=aa037a1c8c) | Feb 09, 2022 |
| Lenovo        | IdeaPad Z460 20059          | [0de3e1022e](https://linux-hardware.org/?probe=0de3e1022e) | Feb 09, 2022 |
| Acer          | Nitro AN515-54              | [8023f7f6d2](https://linux-hardware.org/?probe=8023f7f6d2) | Feb 08, 2022 |
| Acer          | Nitro AN515-54              | [66c6eadf8b](https://linux-hardware.org/?probe=66c6eadf8b) | Feb 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [87954474ed](https://linux-hardware.org/?probe=87954474ed) | Feb 07, 2022 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [5e0e5de165](https://linux-hardware.org/?probe=5e0e5de165) | Feb 07, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [aaceb070e8](https://linux-hardware.org/?probe=aaceb070e8) | Feb 07, 2022 |
| ASUSTek       | X455LD                      | [324512f303](https://linux-hardware.org/?probe=324512f303) | Feb 06, 2022 |
| Lenovo        | ThinkPad W520 427637U       | [f9eb52038d](https://linux-hardware.org/?probe=f9eb52038d) | Feb 01, 2022 |
| Dell          | Inspiron 5480               | [85796c8359](https://linux-hardware.org/?probe=85796c8359) | Jan 28, 2022 |
| Dell          | Inspiron 5480               | [59b6841322](https://linux-hardware.org/?probe=59b6841322) | Jan 28, 2022 |
| Acer          | Aspire E5-571G              | [a29ec0cc55](https://linux-hardware.org/?probe=a29ec0cc55) | Jan 28, 2022 |
| Lenovo        | IdeaPad 320-14AST 80XU      | [774625ff90](https://linux-hardware.org/?probe=774625ff90) | Jan 24, 2022 |
| Lenovo        | IdeaPad 320-14AST 80XU      | [e7c5bda932](https://linux-hardware.org/?probe=e7c5bda932) | Jan 24, 2022 |
| ASUSTek       | X450CP                      | [3f431523c1](https://linux-hardware.org/?probe=3f431523c1) | Jan 22, 2022 |
| Acer          | Swift SF314-43              | [567c5725d5](https://linux-hardware.org/?probe=567c5725d5) | Jan 22, 2022 |
| Sony          | SVE14A15FGB                 | [c35af68d7b](https://linux-hardware.org/?probe=c35af68d7b) | Jan 21, 2022 |
| Acer          | Aspire E5-471               | [a7c6bed4e1](https://linux-hardware.org/?probe=a7c6bed4e1) | Jan 21, 2022 |
| Sony          | SVD13213SGW                 | [ee9e63ab7c](https://linux-hardware.org/?probe=ee9e63ab7c) | Jan 21, 2022 |
| Acer          | Nitro AN515-52              | [e4791d09ec](https://linux-hardware.org/?probe=e4791d09ec) | Jan 20, 2022 |
| Lenovo        | IdeaPad 305-14IBD 80R1      | [f963f78bc6](https://linux-hardware.org/?probe=f963f78bc6) | Jan 20, 2022 |
| MSI           | Modern 14 B5M               | [ae605d8a23](https://linux-hardware.org/?probe=ae605d8a23) | Jan 18, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [c021e3bb40](https://linux-hardware.org/?probe=c021e3bb40) | Jan 18, 2022 |
| Acer          | Aspire E5-471               | [bf81e9a289](https://linux-hardware.org/?probe=bf81e9a289) | Jan 17, 2022 |
| Toshiba       | PORTEGE Z30-A               | [6df479c161](https://linux-hardware.org/?probe=6df479c161) | Jan 16, 2022 |
| Lenovo        | ThinkPad X260 20F5S22K0Z    | [e83aec04ca](https://linux-hardware.org/?probe=e83aec04ca) | Jan 16, 2022 |
| Lenovo        | G400s 20244                 | [9ac1aa04cc](https://linux-hardware.org/?probe=9ac1aa04cc) | Jan 15, 2022 |
| Dell          | Vostro 5581                 | [45f89f3b39](https://linux-hardware.org/?probe=45f89f3b39) | Jan 13, 2022 |
| MSI           | Modern 14 B5M               | [4822adcbc3](https://linux-hardware.org/?probe=4822adcbc3) | Jan 09, 2022 |
| MSI           | GL65 9SC                    | [24c204f7cf](https://linux-hardware.org/?probe=24c204f7cf) | Jan 09, 2022 |
| Dell          | Latitude E7250              | [e586dba516](https://linux-hardware.org/?probe=e586dba516) | Jan 09, 2022 |
| Lenovo        | ThinkPad E14 20RAS0EQ00     | [ea22270511](https://linux-hardware.org/?probe=ea22270511) | Jan 09, 2022 |
| Dell          | Inspiron 5570               | [2268237364](https://linux-hardware.org/?probe=2268237364) | Jan 08, 2022 |
| MSI           | Modern 14 B5M               | [ea82b6b417](https://linux-hardware.org/?probe=ea82b6b417) | Jan 08, 2022 |
| ASUSTek       | N43SL                       | [8468a0ab83](https://linux-hardware.org/?probe=8468a0ab83) | Jan 04, 2022 |
| Lenovo        | U310                        | [47b64f9b71](https://linux-hardware.org/?probe=47b64f9b71) | Jan 04, 2022 |
| ASUSTek       | TP300LD                     | [2048e4ff56](https://linux-hardware.org/?probe=2048e4ff56) | Jan 04, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [954bd9f15e](https://linux-hardware.org/?probe=954bd9f15e) | Jan 03, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [5a0df8b1d8](https://linux-hardware.org/?probe=5a0df8b1d8) | Jan 03, 2022 |
| Acer          | Aspire 4720Z                | [1928762a58](https://linux-hardware.org/?probe=1928762a58) | Jan 02, 2022 |
| Acer          | Aspire E5-471               | [ad8cdd464b](https://linux-hardware.org/?probe=ad8cdd464b) | Jan 01, 2022 |
| ASUSTek       | TP300LD                     | [13e63153f1](https://linux-hardware.org/?probe=13e63153f1) | Dec 31, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | [a9e50f6f42](https://linux-hardware.org/?probe=a9e50f6f42) | Dec 28, 2021 |
| Lenovo        | G40-45 80E1                 | [391b2705c1](https://linux-hardware.org/?probe=391b2705c1) | Dec 25, 2021 |
| HP            | Pavilion 14                 | [b212043e80](https://linux-hardware.org/?probe=b212043e80) | Dec 25, 2021 |
| Lenovo        | IdeaPad 320-14AST 80XU      | [80c8feb8bf](https://linux-hardware.org/?probe=80c8feb8bf) | Dec 25, 2021 |
| Fujitsu       | FMVNA7BEC                   | [5a7719cad2](https://linux-hardware.org/?probe=5a7719cad2) | Dec 23, 2021 |
| Acer          | Aspire E1-471G              | [93b181f3fd](https://linux-hardware.org/?probe=93b181f3fd) | Dec 21, 2021 |
| Dell          | Latitude E5400              | [ea58337ba8](https://linux-hardware.org/?probe=ea58337ba8) | Dec 20, 2021 |
| Toshiba       | Dakar10FW8                  | [937d3de436](https://linux-hardware.org/?probe=937d3de436) | Dec 19, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [1846fa72b5](https://linux-hardware.org/?probe=1846fa72b5) | Dec 12, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [f279fb7b6f](https://linux-hardware.org/?probe=f279fb7b6f) | Dec 09, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [635ec3d5d2](https://linux-hardware.org/?probe=635ec3d5d2) | Dec 09, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [ee7ae7b860](https://linux-hardware.org/?probe=ee7ae7b860) | Dec 06, 2021 |
| ASUSTek       | X200MA                      | [c81483b4db](https://linux-hardware.org/?probe=c81483b4db) | Dec 04, 2021 |
| Samsung       | 700T                        | [efe2d4bd92](https://linux-hardware.org/?probe=efe2d4bd92) | Dec 03, 2021 |
| ASUSTek       | X455LD                      | [8fcb88c027](https://linux-hardware.org/?probe=8fcb88c027) | Nov 30, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [08612b7f88](https://linux-hardware.org/?probe=08612b7f88) | Nov 27, 2021 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [8cffa892b2](https://linux-hardware.org/?probe=8cffa892b2) | Nov 26, 2021 |
| Acer          | Aspire 4732Z                | [7376dc0d58](https://linux-hardware.org/?probe=7376dc0d58) | Nov 25, 2021 |
| Acer          | Aspire 4732Z                | [d020b5f5c5](https://linux-hardware.org/?probe=d020b5f5c5) | Nov 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [a87f01aa8a](https://linux-hardware.org/?probe=a87f01aa8a) | Nov 25, 2021 |
| Acer          | Swift SF514-53T             | [09cc50e9eb](https://linux-hardware.org/?probe=09cc50e9eb) | Nov 23, 2021 |
| ASUSTek       | X455LD                      | [34d8f7fdbb](https://linux-hardware.org/?probe=34d8f7fdbb) | Nov 23, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [945f4c9b1d](https://linux-hardware.org/?probe=945f4c9b1d) | Nov 22, 2021 |
| HP            | ENVY TS 15                  | [ca6e82745c](https://linux-hardware.org/?probe=ca6e82745c) | Nov 22, 2021 |
| ASUSTek       | K45VD                       | [4a655e0c04](https://linux-hardware.org/?probe=4a655e0c04) | Nov 22, 2021 |
| Acer          | Swift SF514-53T             | [dbca729f8c](https://linux-hardware.org/?probe=dbca729f8c) | Nov 20, 2021 |
| Lenovo        | IdeaPad 300-14IBR 80M2      | [34fb650910](https://linux-hardware.org/?probe=34fb650910) | Nov 16, 2021 |
| Dell          | Vostro 3400                 | [f6ba3e3359](https://linux-hardware.org/?probe=f6ba3e3359) | Nov 15, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [3a33eaa4c0](https://linux-hardware.org/?probe=3a33eaa4c0) | Nov 12, 2021 |
| Notebook      | P870DM                      | [7681edf3ee](https://linux-hardware.org/?probe=7681edf3ee) | Nov 12, 2021 |
| HP            | EliteBook 2570p             | [fa2cb4cfff](https://linux-hardware.org/?probe=fa2cb4cfff) | Nov 12, 2021 |
| HP            | EliteBook 2570p             | [53cf9a7e19](https://linux-hardware.org/?probe=53cf9a7e19) | Nov 12, 2021 |
| Acer          | Swift SF514-52T             | [020a93edbc](https://linux-hardware.org/?probe=020a93edbc) | Nov 10, 2021 |
| MSI           | GL62M 7RDX                  | [3538358a06](https://linux-hardware.org/?probe=3538358a06) | Nov 09, 2021 |
| ASUSTek       | X550ZE                      | [b27a794243](https://linux-hardware.org/?probe=b27a794243) | Nov 09, 2021 |
| HP            | Notebook                    | [9334c94844](https://linux-hardware.org/?probe=9334c94844) | Nov 07, 2021 |
| Acer          | Swift SF314-41              | [ef268f8220](https://linux-hardware.org/?probe=ef268f8220) | Nov 07, 2021 |
| Acer          | Swift SF314-56G             | [bf298c7d2d](https://linux-hardware.org/?probe=bf298c7d2d) | Nov 07, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [fe34c12d67](https://linux-hardware.org/?probe=fe34c12d67) | Nov 03, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [3a0bd3fa08](https://linux-hardware.org/?probe=3a0bd3fa08) | Nov 01, 2021 |
| Acer          | Swift SF314-43              | [4881a9a93c](https://linux-hardware.org/?probe=4881a9a93c) | Oct 31, 2021 |
| Lenovo        | G40-45 80E1                 | [0cdc6e9d84](https://linux-hardware.org/?probe=0cdc6e9d84) | Oct 28, 2021 |
| Dell          | Latitude E6440              | [00e8b6e3fd](https://linux-hardware.org/?probe=00e8b6e3fd) | Oct 24, 2021 |
| MSI           | Bravo 15 B5DD               | [afa573d049](https://linux-hardware.org/?probe=afa573d049) | Oct 22, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [78738c3586](https://linux-hardware.org/?probe=78738c3586) | Oct 22, 2021 |
| Dell          | G7 7588                     | [af1479f2fe](https://linux-hardware.org/?probe=af1479f2fe) | Oct 20, 2021 |
| Dell          | G7 7588                     | [0464fb8af6](https://linux-hardware.org/?probe=0464fb8af6) | Oct 20, 2021 |
| Dell          | Inspiron 1440               | [9e9967a3fa](https://linux-hardware.org/?probe=9e9967a3fa) | Oct 17, 2021 |
| Acer          | Aspire 4738Z                | [8962990035](https://linux-hardware.org/?probe=8962990035) | Oct 16, 2021 |
| ASUSTek       | U36SD                       | [c426070626](https://linux-hardware.org/?probe=c426070626) | Oct 12, 2021 |
| ASUSTek       | 1215B                       | [7b3bf2ca14](https://linux-hardware.org/?probe=7b3bf2ca14) | Oct 11, 2021 |
| ASUSTek       | K43SV                       | [6c0858f414](https://linux-hardware.org/?probe=6c0858f414) | Oct 08, 2021 |
| ASUSTek       | K43SV                       | [cff7419d9e](https://linux-hardware.org/?probe=cff7419d9e) | Oct 08, 2021 |
| HP            | Pavilion 14                 | [0c0ee7fe52](https://linux-hardware.org/?probe=0c0ee7fe52) | Oct 05, 2021 |
| Acer          | Aspire 4750                 | [b00fc610cd](https://linux-hardware.org/?probe=b00fc610cd) | Oct 05, 2021 |
| HP            | Laptop 14-bw0xx             | [5856720999](https://linux-hardware.org/?probe=5856720999) | Oct 04, 2021 |
| ASUSTek       | X441BA                      | [ae6206875f](https://linux-hardware.org/?probe=ae6206875f) | Oct 03, 2021 |
| ASUSTek       | X441BA                      | [692a1a1a57](https://linux-hardware.org/?probe=692a1a1a57) | Oct 03, 2021 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [17c2d08e41](https://linux-hardware.org/?probe=17c2d08e41) | Oct 01, 2021 |
| HP            | Laptop 14s-cf3xxx           | [1c4d130d6a](https://linux-hardware.org/?probe=1c4d130d6a) | Oct 01, 2021 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [2b03e34e82](https://linux-hardware.org/?probe=2b03e34e82) | Sep 30, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | [32c58fa2f6](https://linux-hardware.org/?probe=32c58fa2f6) | Sep 30, 2021 |
| HP            | EliteBook 8440p (SH923UC... | [61b646614a](https://linux-hardware.org/?probe=61b646614a) | Sep 30, 2021 |
| HP            | EliteBook 2560p             | [28d13c49b3](https://linux-hardware.org/?probe=28d13c49b3) | Sep 28, 2021 |
| HP            | EliteBook 8440p (SH923UC... | [21ddcdea76](https://linux-hardware.org/?probe=21ddcdea76) | Sep 27, 2021 |
| Acer          | Swift SFX14-41G             | [cb763824f9](https://linux-hardware.org/?probe=cb763824f9) | Sep 25, 2021 |
| Acer          | Aspire 4752                 | [c68b87dd56](https://linux-hardware.org/?probe=c68b87dd56) | Sep 25, 2021 |
| Apple         | MacBook3,1                  | [67212f51d0](https://linux-hardware.org/?probe=67212f51d0) | Sep 25, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [39921c4f34](https://linux-hardware.org/?probe=39921c4f34) | Sep 20, 2021 |
| ASUSTek       | X441SA                      | [f107358f2a](https://linux-hardware.org/?probe=f107358f2a) | Sep 20, 2021 |
| Lenovo        | ThinkBook 14s-IML 20RS      | [f93df3c890](https://linux-hardware.org/?probe=f93df3c890) | Sep 19, 2021 |
| Acer          | Aspire 4752                 | [c5758f5a05](https://linux-hardware.org/?probe=c5758f5a05) | Sep 18, 2021 |
| HP            | OMEN Laptop 15-en1014AX     | [8ff619f5f3](https://linux-hardware.org/?probe=8ff619f5f3) | Sep 17, 2021 |
| HP            | OMEN Laptop 15-en1014AX     | [57dc237470](https://linux-hardware.org/?probe=57dc237470) | Sep 17, 2021 |
| Acer          | Swift SF314-43              | [e5804af7f6](https://linux-hardware.org/?probe=e5804af7f6) | Sep 14, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [e84546c757](https://linux-hardware.org/?probe=e84546c757) | Sep 14, 2021 |
| Acer          | Aspire 4752                 | [2cc8dabf64](https://linux-hardware.org/?probe=2cc8dabf64) | Sep 11, 2021 |
| HP            | Compaq Presario CQ40        | [62284df376](https://linux-hardware.org/?probe=62284df376) | Sep 10, 2021 |
| HP            | Laptop 14s-cf3xxx           | [5b9800e687](https://linux-hardware.org/?probe=5b9800e687) | Sep 06, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [a629879646](https://linux-hardware.org/?probe=a629879646) | Sep 06, 2021 |
| Dell          | XPS 15 7590                 | [82904dfc03](https://linux-hardware.org/?probe=82904dfc03) | Sep 05, 2021 |
| Apple         | MacBook3,1                  | [1473909011](https://linux-hardware.org/?probe=1473909011) | Sep 05, 2021 |
| Acer          | Aspire 4750                 | [f88ba2a8ea](https://linux-hardware.org/?probe=f88ba2a8ea) | Sep 04, 2021 |
| HP            | 14                          | [9f574ea069](https://linux-hardware.org/?probe=9f574ea069) | Sep 04, 2021 |
| Acer          | Aspire V3-371               | [ddd7b7b87f](https://linux-hardware.org/?probe=ddd7b7b87f) | Sep 02, 2021 |
| Acer          | Aspire V3-371               | [16c3c01bcd](https://linux-hardware.org/?probe=16c3c01bcd) | Sep 02, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [0bfcbeeab5](https://linux-hardware.org/?probe=0bfcbeeab5) | Sep 02, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [808ff28683](https://linux-hardware.org/?probe=808ff28683) | Aug 31, 2021 |
| ASUSTek       | GL553VD                     | [d6a7f7807d](https://linux-hardware.org/?probe=d6a7f7807d) | Aug 26, 2021 |
| Acer          | Aspire A315-42              | [6e6129ddbe](https://linux-hardware.org/?probe=6e6129ddbe) | Aug 26, 2021 |
| HP            | ProBook 4430s               | [e764612d91](https://linux-hardware.org/?probe=e764612d91) | Aug 25, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [49aac2eefe](https://linux-hardware.org/?probe=49aac2eefe) | Aug 24, 2021 |
| Acer          | Aspire V3-371               | [d34df8e36e](https://linux-hardware.org/?probe=d34df8e36e) | Aug 23, 2021 |
| Acer          | Aspire 4750                 | [6f5d61dc20](https://linux-hardware.org/?probe=6f5d61dc20) | Aug 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [b57e843f46](https://linux-hardware.org/?probe=b57e843f46) | Aug 22, 2021 |
| Acer          | Swift SF314-41              | [34d2f87751](https://linux-hardware.org/?probe=34d2f87751) | Aug 18, 2021 |
| Fujitsu       | FMVNA6HG                    | [3af7eec32c](https://linux-hardware.org/?probe=3af7eec32c) | Aug 16, 2021 |
| Toshiba       | Satellite R630              | [b2b7f07b7a](https://linux-hardware.org/?probe=b2b7f07b7a) | Aug 12, 2021 |
| HP            | ENVY Notebook               | [f2dea0236d](https://linux-hardware.org/?probe=f2dea0236d) | Aug 11, 2021 |
| HP            | ENVY Notebook               | [ce3be0798b](https://linux-hardware.org/?probe=ce3be0798b) | Aug 11, 2021 |
| Toshiba       | Satellite M100              | [8dff0ec788](https://linux-hardware.org/?probe=8dff0ec788) | Aug 10, 2021 |
| Toshiba       | Satellite M100              | [06e766539d](https://linux-hardware.org/?probe=06e766539d) | Aug 10, 2021 |
| HP            | Laptop 14-bw0xx             | [3d8ebc06f6](https://linux-hardware.org/?probe=3d8ebc06f6) | Aug 10, 2021 |
| HP            | Laptop 14-bw0xx             | [bb3eb06270](https://linux-hardware.org/?probe=bb3eb06270) | Aug 09, 2021 |
| Acer          | Nitro AN515-56              | [867c7e2bb4](https://linux-hardware.org/?probe=867c7e2bb4) | Aug 09, 2021 |
| Lenovo        | G40-45 80E1                 | [a9947e6264](https://linux-hardware.org/?probe=a9947e6264) | Aug 08, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [6d691b88f0](https://linux-hardware.org/?probe=6d691b88f0) | Aug 08, 2021 |
| Acer          | Aspire 4752                 | [16f9fcdeed](https://linux-hardware.org/?probe=16f9fcdeed) | Aug 08, 2021 |
| Acer          | Swift SF314-41              | [4f141cc864](https://linux-hardware.org/?probe=4f141cc864) | Aug 07, 2021 |
| Acer          | Swift SF314-41              | [31e6bda7a8](https://linux-hardware.org/?probe=31e6bda7a8) | Aug 07, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | [f7718b0dfe](https://linux-hardware.org/?probe=f7718b0dfe) | Aug 06, 2021 |
| Lenovo        | G40-45 80E1                 | [346da0d23a](https://linux-hardware.org/?probe=346da0d23a) | Aug 06, 2021 |
| ASUSTek       | X455YA                      | [7ceff8b834](https://linux-hardware.org/?probe=7ceff8b834) | Aug 05, 2021 |
| HP            | Laptop 15s-fq2xxx           | [506b637bd3](https://linux-hardware.org/?probe=506b637bd3) | Aug 05, 2021 |
| Lenovo        | G40-45 80E1                 | [26d0a4788c](https://linux-hardware.org/?probe=26d0a4788c) | Aug 03, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [1a72340ff4](https://linux-hardware.org/?probe=1a72340ff4) | Aug 01, 2021 |
| Lenovo        | G400s 20244                 | [43fe80380d](https://linux-hardware.org/?probe=43fe80380d) | Aug 01, 2021 |
| Lenovo        | ThinkPad T430s 2356CTO      | [f3d9dd3c21](https://linux-hardware.org/?probe=f3d9dd3c21) | Jul 31, 2021 |
| Lenovo        | G40-45 80E1                 | [597f4ff063](https://linux-hardware.org/?probe=597f4ff063) | Jul 29, 2021 |
| Dell          | Inspiron 3458               | [43d4236000](https://linux-hardware.org/?probe=43d4236000) | Jul 27, 2021 |
| Dell          | Vostro 14-3468              | [c222cecae0](https://linux-hardware.org/?probe=c222cecae0) | Jul 27, 2021 |
| Acer          | Swift SF314-43              | [690b0d3adc](https://linux-hardware.org/?probe=690b0d3adc) | Jul 26, 2021 |
| Acer          | Swift SF314-43              | [3c2e8b0074](https://linux-hardware.org/?probe=3c2e8b0074) | Jul 26, 2021 |
| Acer          | Aspire A315-42              | [d59705a499](https://linux-hardware.org/?probe=d59705a499) | Jul 25, 2021 |
| HP            | ProBook 470 G5              | [a778d78c98](https://linux-hardware.org/?probe=a778d78c98) | Jul 25, 2021 |
| Lenovo        | ThinkPad X220 4291G75       | [fc0c3340bd](https://linux-hardware.org/?probe=fc0c3340bd) | Jul 25, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | [c466690f21](https://linux-hardware.org/?probe=c466690f21) | Jul 25, 2021 |
| Toshiba       | PORTEGE M800                | [6de34f58af](https://linux-hardware.org/?probe=6de34f58af) | Jul 25, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | [bfbf5b3302](https://linux-hardware.org/?probe=bfbf5b3302) | Jul 25, 2021 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | [a8970607e0](https://linux-hardware.org/?probe=a8970607e0) | Jul 23, 2021 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [8d72c96d15](https://linux-hardware.org/?probe=8d72c96d15) | Jul 23, 2021 |
| Acer          | Aspire V5-431               | [0616ef50a5](https://linux-hardware.org/?probe=0616ef50a5) | Jul 22, 2021 |
| Apple         | MacBookPro6,2               | [22a976ce11](https://linux-hardware.org/?probe=22a976ce11) | Jul 21, 2021 |
| Lenovo        | G40-45 80E1                 | [c6b76cb1f9](https://linux-hardware.org/?probe=c6b76cb1f9) | Jul 21, 2021 |
| Acer          | Nitro AN515-45              | [714ce6dfc9](https://linux-hardware.org/?probe=714ce6dfc9) | Jul 19, 2021 |
| Acer          | Nitro AN515-45              | [e1d1356c93](https://linux-hardware.org/?probe=e1d1356c93) | Jul 19, 2021 |
| Acer          | Aspire V5-431               | [e0519d6c32](https://linux-hardware.org/?probe=e0519d6c32) | Jul 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [d3561fadd3](https://linux-hardware.org/?probe=d3561fadd3) | Jul 18, 2021 |
| HP            | Laptop 14s-dk0xxx           | [6cc56f596f](https://linux-hardware.org/?probe=6cc56f596f) | Jul 17, 2021 |
| Lenovo        | ThinkPad X250 20CLA200ID    | [28c05ab175](https://linux-hardware.org/?probe=28c05ab175) | Jul 17, 2021 |
| Unknown       | Unknown                     | [1d1680d9c3](https://linux-hardware.org/?probe=1d1680d9c3) | Jul 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [4e75379022](https://linux-hardware.org/?probe=4e75379022) | Jul 16, 2021 |
| Dell          | Latitude E5520              | [9278405254](https://linux-hardware.org/?probe=9278405254) | Jul 13, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | [393ed0c954](https://linux-hardware.org/?probe=393ed0c954) | Jul 12, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | [cd0155712e](https://linux-hardware.org/?probe=cd0155712e) | Jul 10, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | [9727587570](https://linux-hardware.org/?probe=9727587570) | Jul 10, 2021 |
| Lenovo        | ThinkPad X61 7676A12        | [3e43acf8af](https://linux-hardware.org/?probe=3e43acf8af) | Jul 08, 2021 |
| Lenovo        | ThinkPad T430 2349SU6       | [9cd74fc6d1](https://linux-hardware.org/?probe=9cd74fc6d1) | Jul 08, 2021 |
| Lenovo        | ThinkPad X61 7676A12        | [196e6c6ec4](https://linux-hardware.org/?probe=196e6c6ec4) | Jul 08, 2021 |
| ASUSTek       | X450EA                      | [91a0ff32e1](https://linux-hardware.org/?probe=91a0ff32e1) | Jul 06, 2021 |
| ASUSTek       | X450EA                      | [e4dc18ebf9](https://linux-hardware.org/?probe=e4dc18ebf9) | Jul 06, 2021 |
| ASUSTek       | K84L                        | [01c9e0cbe1](https://linux-hardware.org/?probe=01c9e0cbe1) | Jul 03, 2021 |
| Acer          | Aspire A515-45              | [42249c6e47](https://linux-hardware.org/?probe=42249c6e47) | Jul 02, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [c980ba6ae7](https://linux-hardware.org/?probe=c980ba6ae7) | Jul 02, 2021 |
| Acer          | Aspire A315-41              | [67c143c435](https://linux-hardware.org/?probe=67c143c435) | Jul 01, 2021 |
| Dell          | Latitude E5410              | [b047bdb721](https://linux-hardware.org/?probe=b047bdb721) | Jun 25, 2021 |
| Acer          | Aspire 4752                 | [16a063ab28](https://linux-hardware.org/?probe=16a063ab28) | Jun 24, 2021 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [e135f49903](https://linux-hardware.org/?probe=e135f49903) | Jun 20, 2021 |
| Lenovo        | G40-30 80FY                 | [114ba38c36](https://linux-hardware.org/?probe=114ba38c36) | Jun 20, 2021 |
| Acer          | Aspire E5-475G              | [0d6df01751](https://linux-hardware.org/?probe=0d6df01751) | Jun 20, 2021 |
| Lenovo        | G40-30 80FY                 | [0cb7e73af9](https://linux-hardware.org/?probe=0cb7e73af9) | Jun 19, 2021 |
| Acer          | Aspire E5-475G              | [c1c0f815dc](https://linux-hardware.org/?probe=c1c0f815dc) | Jun 15, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [7572d1aea9](https://linux-hardware.org/?probe=7572d1aea9) | Jun 13, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [9551aa9271](https://linux-hardware.org/?probe=9551aa9271) | Jun 06, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [6d45501f90](https://linux-hardware.org/?probe=6d45501f90) | Jun 05, 2021 |
| Lenovo        | IdeaPad 130-14IKB 81H6      | [8af935f813](https://linux-hardware.org/?probe=8af935f813) | Jun 02, 2021 |
| Acer          | Aspire E5-476G              | [ecbaba7315](https://linux-hardware.org/?probe=ecbaba7315) | May 31, 2021 |
| HP            | EliteBook Folio 9470m       | [3e6a2f7b59](https://linux-hardware.org/?probe=3e6a2f7b59) | May 27, 2021 |
| ASUSTek       | K45DR                       | [b86bb4b6c9](https://linux-hardware.org/?probe=b86bb4b6c9) | May 27, 2021 |
| Dell          | Latitude E6410              | [7e35c63842](https://linux-hardware.org/?probe=7e35c63842) | May 26, 2021 |
| Acer          | Aspire 4752                 | [7ca3035a20](https://linux-hardware.org/?probe=7ca3035a20) | May 26, 2021 |
| ASUSTek       | K45DR                       | [583824ad87](https://linux-hardware.org/?probe=583824ad87) | May 21, 2021 |
| ASUSTek       | X550JX                      | [c837a795d7](https://linux-hardware.org/?probe=c837a795d7) | May 19, 2021 |
| Acer          | Okinawa                     | [9579ede8a9](https://linux-hardware.org/?probe=9579ede8a9) | May 19, 2021 |
| Lenovo        | C-Notebook XXXX 3000 G40... | [1ad049bf43](https://linux-hardware.org/?probe=1ad049bf43) | May 17, 2021 |
| Acer          | Aspire 4752                 | [b26958098c](https://linux-hardware.org/?probe=b26958098c) | May 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [9a69a064a2](https://linux-hardware.org/?probe=9a69a064a2) | May 08, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [0d732d9421](https://linux-hardware.org/?probe=0d732d9421) | May 05, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [0beb84ac05](https://linux-hardware.org/?probe=0beb84ac05) | Apr 29, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [2fddce1bd1](https://linux-hardware.org/?probe=2fddce1bd1) | Apr 29, 2021 |
| ASUSTek       | X453SA                      | [e72a666c50](https://linux-hardware.org/?probe=e72a666c50) | Apr 28, 2021 |
| Acer          | Aspire 4750                 | [dcfd3e0bb5](https://linux-hardware.org/?probe=dcfd3e0bb5) | Apr 24, 2021 |
| Acer          | Aspire 4750                 | [5b1db085fc](https://linux-hardware.org/?probe=5b1db085fc) | Apr 24, 2021 |
| Dell          | Latitude 5400               | [a2fb8a380a](https://linux-hardware.org/?probe=a2fb8a380a) | Apr 23, 2021 |
| Dell          | Latitude 5400               | [e4a0edd922](https://linux-hardware.org/?probe=e4a0edd922) | Apr 23, 2021 |
| Acer          | Aspire A514-53              | [2a5c4baa8f](https://linux-hardware.org/?probe=2a5c4baa8f) | Apr 18, 2021 |
| Acer          | Swift SF314-41              | [fde9376452](https://linux-hardware.org/?probe=fde9376452) | Apr 16, 2021 |
| Acer          | Swift SF314-41              | [9f50b41201](https://linux-hardware.org/?probe=9f50b41201) | Apr 16, 2021 |
| ASUSTek       | X441UV                      | [8ee5e69c11](https://linux-hardware.org/?probe=8ee5e69c11) | Apr 16, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | [9a5ad3016a](https://linux-hardware.org/?probe=9a5ad3016a) | Apr 15, 2021 |
| Acer          | Aspire 4752                 | [dbc22d503d](https://linux-hardware.org/?probe=dbc22d503d) | Apr 12, 2021 |
| Acer          | Aspire 4752                 | [c6ef5b093d](https://linux-hardware.org/?probe=c6ef5b093d) | Apr 12, 2021 |
| HP            | EliteBook 840 G1            | [b14a1a07ac](https://linux-hardware.org/?probe=b14a1a07ac) | Apr 11, 2021 |
| Dell          | Inspiron 5570               | [059aa32bb7](https://linux-hardware.org/?probe=059aa32bb7) | Apr 10, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | [4a05cec425](https://linux-hardware.org/?probe=4a05cec425) | Apr 10, 2021 |
| Acer          | Aspire 4741                 | [cf750140a8](https://linux-hardware.org/?probe=cf750140a8) | Apr 10, 2021 |
| Lenovo        | IdeaPad 730S-13IWL 81JB     | [156c9db184](https://linux-hardware.org/?probe=156c9db184) | Apr 10, 2021 |
| Lenovo        | IdeaPad Z410 20292          | [803bcbb44c](https://linux-hardware.org/?probe=803bcbb44c) | Apr 05, 2021 |
| HP            | EliteBook Folio 9470m       | [22fc47b193](https://linux-hardware.org/?probe=22fc47b193) | Apr 05, 2021 |
| HP            | Laptop 15-bw0xx             | [44efde8890](https://linux-hardware.org/?probe=44efde8890) | Apr 05, 2021 |
| HP            | 1000                        | [be995ccb43](https://linux-hardware.org/?probe=be995ccb43) | Apr 04, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [941b588cf9](https://linux-hardware.org/?probe=941b588cf9) | Apr 03, 2021 |
| Acer          | Aspire 4739                 | [19ba24510c](https://linux-hardware.org/?probe=19ba24510c) | Apr 02, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [c41ba66f79](https://linux-hardware.org/?probe=c41ba66f79) | Apr 01, 2021 |
| Lenovo        | V310-14ISK 80SX             | [463bdc0444](https://linux-hardware.org/?probe=463bdc0444) | Apr 01, 2021 |
| ASUSTek       | X550VX                      | [4d95cd31eb](https://linux-hardware.org/?probe=4d95cd31eb) | Mar 27, 2021 |
| Dell          | Latitude 5400               | [5cab0ca67e](https://linux-hardware.org/?probe=5cab0ca67e) | Mar 26, 2021 |
| ASUSTek       | K45VD                       | [74592068ee](https://linux-hardware.org/?probe=74592068ee) | Mar 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [3d99b46431](https://linux-hardware.org/?probe=3d99b46431) | Mar 25, 2021 |
| Lenovo        | V310-14ISK 80SX             | [1ce5b4161e](https://linux-hardware.org/?probe=1ce5b4161e) | Mar 24, 2021 |
| ASUSTek       | X45U                        | [05632e634d](https://linux-hardware.org/?probe=05632e634d) | Mar 23, 2021 |
| Dell          | Vostro 3481                 | [63b8942776](https://linux-hardware.org/?probe=63b8942776) | Mar 12, 2021 |
| ASUSTek       | X441SA                      | [abec8a4c19](https://linux-hardware.org/?probe=abec8a4c19) | Mar 08, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [461b5d7b4b](https://linux-hardware.org/?probe=461b5d7b4b) | Mar 06, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [cb688e237f](https://linux-hardware.org/?probe=cb688e237f) | Mar 06, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [50a76385ba](https://linux-hardware.org/?probe=50a76385ba) | Mar 05, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [68d0129e2d](https://linux-hardware.org/?probe=68d0129e2d) | Mar 05, 2021 |
| Fujitsu       | LIFEBOOK AH544              | [80ce017529](https://linux-hardware.org/?probe=80ce017529) | Mar 04, 2021 |
| ASUSTek       | X442URR                     | [d8e04d832e](https://linux-hardware.org/?probe=d8e04d832e) | Mar 03, 2021 |
| ASUSTek       | UX303UB                     | [c4867a5743](https://linux-hardware.org/?probe=c4867a5743) | Mar 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [a5f08bd719](https://linux-hardware.org/?probe=a5f08bd719) | Mar 01, 2021 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | [d3f1f06d5d](https://linux-hardware.org/?probe=d3f1f06d5d) | Feb 22, 2021 |
| HP            | Notebook                    | [e718153751](https://linux-hardware.org/?probe=e718153751) | Feb 22, 2021 |
| ASUSTek       | K42F                        | [2380c82b48](https://linux-hardware.org/?probe=2380c82b48) | Feb 20, 2021 |
| HP            | Notebook                    | [326de2e4f5](https://linux-hardware.org/?probe=326de2e4f5) | Feb 19, 2021 |
| ASUSTek       | U36SD                       | [981c7e8da7](https://linux-hardware.org/?probe=981c7e8da7) | Feb 19, 2021 |
| Lenovo        | ThinkPad X230 Tablet 343... | [f9abaeb3f9](https://linux-hardware.org/?probe=f9abaeb3f9) | Feb 18, 2021 |
| HP            | Laptop 14-bw0xx             | [1a3e26503a](https://linux-hardware.org/?probe=1a3e26503a) | Feb 17, 2021 |
| Acer          | Aspire E5-471G              | [3b58cbf4e6](https://linux-hardware.org/?probe=3b58cbf4e6) | Feb 17, 2021 |
| Lenovo        | ThinkPad X240 20AMS0PB11    | [5a09ac2a06](https://linux-hardware.org/?probe=5a09ac2a06) | Feb 16, 2021 |
| Lenovo        | ThinkPad X240 20AMS0PB11    | [9805e3bcb5](https://linux-hardware.org/?probe=9805e3bcb5) | Feb 16, 2021 |
| Lenovo        | IdeaPad 110-14ISK 80UC      | [2cf1bfd6c6](https://linux-hardware.org/?probe=2cf1bfd6c6) | Feb 16, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [a0537ad7d5](https://linux-hardware.org/?probe=a0537ad7d5) | Feb 16, 2021 |
| Toshiba       | Satellite C855              | [60adcbc05d](https://linux-hardware.org/?probe=60adcbc05d) | Feb 16, 2021 |
| Timi          | TM1703                      | [4d64e40cca](https://linux-hardware.org/?probe=4d64e40cca) | Feb 14, 2021 |
| HP            | Pavilion Laptop 14-bf0xx    | [309266e981](https://linux-hardware.org/?probe=309266e981) | Feb 13, 2021 |
| ASUSTek       | X456UQK                     | [f0380f099d](https://linux-hardware.org/?probe=f0380f099d) | Feb 12, 2021 |
| ASUSTek       | K43E                        | [1604193c0f](https://linux-hardware.org/?probe=1604193c0f) | Feb 11, 2021 |
| Lenovo        | G50-80 80E5                 | [704dbacb0d](https://linux-hardware.org/?probe=704dbacb0d) | Feb 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [ec95272afa](https://linux-hardware.org/?probe=ec95272afa) | Feb 10, 2021 |
| Lenovo        | ThinkPad X131e 33741E0      | [4c52c9aa29](https://linux-hardware.org/?probe=4c52c9aa29) | Feb 06, 2021 |
| Acer          | NXHATSN00190808A906600      | [2ed3d18f0a](https://linux-hardware.org/?probe=2ed3d18f0a) | Feb 05, 2021 |
| ASUSTek       | N56VM                       | [d56280ec33](https://linux-hardware.org/?probe=d56280ec33) | Feb 05, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [f48cf2f332](https://linux-hardware.org/?probe=f48cf2f332) | Feb 05, 2021 |
| Compal        | PBL10                       | [5cf67578d7](https://linux-hardware.org/?probe=5cf67578d7) | Feb 04, 2021 |
| Compal        | PBL10                       | [a20e9d9588](https://linux-hardware.org/?probe=a20e9d9588) | Feb 04, 2021 |
| ASUSTek       | X442UQ                      | [f79d79fd99](https://linux-hardware.org/?probe=f79d79fd99) | Feb 04, 2021 |
| HP            | ZBook Studio G3             | [6f207e9b7f](https://linux-hardware.org/?probe=6f207e9b7f) | Feb 04, 2021 |
| HP            | EliteBook Folio 9470m       | [15b84d2abc](https://linux-hardware.org/?probe=15b84d2abc) | Feb 04, 2021 |
| ASUSTek       | X442UQ                      | [9b722252fa](https://linux-hardware.org/?probe=9b722252fa) | Feb 04, 2021 |
| HP            | Laptop 14-cm0xxx            | [2365556c9d](https://linux-hardware.org/?probe=2365556c9d) | Jan 31, 2021 |
| ASUSTek       | U36SD                       | [5267c17fbb](https://linux-hardware.org/?probe=5267c17fbb) | Jan 30, 2021 |
| HP            | ZBook 15 G2                 | [cebba8a2a8](https://linux-hardware.org/?probe=cebba8a2a8) | Jan 30, 2021 |
| Lenovo        | ThinkPad X280 20KES7YB00    | [b498c0fcba](https://linux-hardware.org/?probe=b498c0fcba) | Jan 29, 2021 |
| ASUSTek       | U36SD                       | [15288996d1](https://linux-hardware.org/?probe=15288996d1) | Jan 28, 2021 |
| Acer          | Aspire 4752                 | [2e5b64f391](https://linux-hardware.org/?probe=2e5b64f391) | Jan 27, 2021 |
| Acer          | Aspire 4752                 | [f068345e45](https://linux-hardware.org/?probe=f068345e45) | Jan 27, 2021 |
| Acer          | AOD255E                     | [b346230927](https://linux-hardware.org/?probe=b346230927) | Jan 27, 2021 |
| ASUSTek       | N56VM                       | [e6d527734c](https://linux-hardware.org/?probe=e6d527734c) | Jan 27, 2021 |
| Acer          | One Z1402                   | [1b8a4dfe38](https://linux-hardware.org/?probe=1b8a4dfe38) | Jan 26, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [4cacca5cdf](https://linux-hardware.org/?probe=4cacca5cdf) | Jan 25, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [d18f1e2124](https://linux-hardware.org/?probe=d18f1e2124) | Jan 23, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [16b5d3f4ca](https://linux-hardware.org/?probe=16b5d3f4ca) | Jan 23, 2021 |
| Acer          | Swift SF514-52T             | [be049e723f](https://linux-hardware.org/?probe=be049e723f) | Jan 21, 2021 |
| ASUSTek       | N56VM                       | [81c592d723](https://linux-hardware.org/?probe=81c592d723) | Jan 21, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [dc16c8d7a4](https://linux-hardware.org/?probe=dc16c8d7a4) | Jan 19, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [f9b1a75983](https://linux-hardware.org/?probe=f9b1a75983) | Jan 19, 2021 |
| Lenovo        | ThinkPad T480 20L5A02JID    | [0599ce4883](https://linux-hardware.org/?probe=0599ce4883) | Jan 18, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [f34a9b325b](https://linux-hardware.org/?probe=f34a9b325b) | Jan 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [be559d7b11](https://linux-hardware.org/?probe=be559d7b11) | Jan 17, 2021 |
| Lenovo        | IdeaPad Z370                | [728438c7eb](https://linux-hardware.org/?probe=728438c7eb) | Jan 16, 2021 |
| Lenovo        | IdeaPad Z370                | [6e3c415308](https://linux-hardware.org/?probe=6e3c415308) | Jan 16, 2021 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [82728c7a68](https://linux-hardware.org/?probe=82728c7a68) | Jan 15, 2021 |
| Dell          | Vostro 5470                 | [8e785a29dd](https://linux-hardware.org/?probe=8e785a29dd) | Jan 15, 2021 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | [bb99db17ed](https://linux-hardware.org/?probe=bb99db17ed) | Jan 15, 2021 |
| HP            | G42                         | [63dd848e66](https://linux-hardware.org/?probe=63dd848e66) | Jan 14, 2021 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [0cfe91c011](https://linux-hardware.org/?probe=0cfe91c011) | Jan 13, 2021 |
| HP            | ZBook 15 G2                 | [da387b9871](https://linux-hardware.org/?probe=da387b9871) | Jan 09, 2021 |
| ASUSTek       | G750JM                      | [794d86e07e](https://linux-hardware.org/?probe=794d86e07e) | Jan 07, 2021 |
| ASUSTek       | G750JM                      | [a32f193a0d](https://linux-hardware.org/?probe=a32f193a0d) | Jan 07, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [692f320444](https://linux-hardware.org/?probe=692f320444) | Jan 07, 2021 |
| Lenovo        | C-Notebook XXXX 3000 G40... | [8a573087bd](https://linux-hardware.org/?probe=8a573087bd) | Jan 07, 2021 |
| MSI           | Modern 15 A10RBS            | [d4ded10aed](https://linux-hardware.org/?probe=d4ded10aed) | Jan 06, 2021 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [ea36c16e10](https://linux-hardware.org/?probe=ea36c16e10) | Jan 05, 2021 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [89d2d898df](https://linux-hardware.org/?probe=89d2d898df) | Jan 05, 2021 |
| ASUSTek       | K43SD                       | [79f04bb2b4](https://linux-hardware.org/?probe=79f04bb2b4) | Jan 04, 2021 |
| HP            | ZBook 15 G2                 | [6ebc8c1b1c](https://linux-hardware.org/?probe=6ebc8c1b1c) | Jan 03, 2021 |
| ASUSTek       | X455LAB                     | [1c55bbde2e](https://linux-hardware.org/?probe=1c55bbde2e) | Jan 01, 2021 |
| HP            | 1000                        | [981fa79f13](https://linux-hardware.org/?probe=981fa79f13) | Jan 01, 2021 |
| ASUSTek       | X455LAB                     | [8cbb6c5afe](https://linux-hardware.org/?probe=8cbb6c5afe) | Dec 31, 2020 |
| Sole          | Unknown                     | [04bc36aa05](https://linux-hardware.org/?probe=04bc36aa05) | Dec 30, 2020 |
| HP            | ZBook 15 G2                 | [87757ee4f2](https://linux-hardware.org/?probe=87757ee4f2) | Dec 30, 2020 |
| Dell          | Vostro A840                 | [76e7e81662](https://linux-hardware.org/?probe=76e7e81662) | Dec 28, 2020 |
| Lenovo        | ThinkPad T530 24294V4       | [50625b08c9](https://linux-hardware.org/?probe=50625b08c9) | Dec 26, 2020 |
| HP            | EliteBook Folio 9470m       | [5bd5d77342](https://linux-hardware.org/?probe=5bd5d77342) | Dec 24, 2020 |
| Lenovo        | ThinkPad SL400 27439MA      | [a53bf69f31](https://linux-hardware.org/?probe=a53bf69f31) | Dec 24, 2020 |
| Lenovo        | ThinkPad SL400 27439MA      | [7f1872861c](https://linux-hardware.org/?probe=7f1872861c) | Dec 24, 2020 |
| Acer          | Aspire 4738Z                | [26c4af7060](https://linux-hardware.org/?probe=26c4af7060) | Dec 22, 2020 |
| Lenovo        | Yoga Slim 9 14ITL5 82D1     | [be0654391c](https://linux-hardware.org/?probe=be0654391c) | Dec 21, 2020 |
| Phoenix/Si... | M720SR                      | [019e901528](https://linux-hardware.org/?probe=019e901528) | Dec 19, 2020 |
| Lenovo        | C-Notebook XXXX 3000 G40... | [23766674a9](https://linux-hardware.org/?probe=23766674a9) | Dec 18, 2020 |
| ASUSTek       | K55DR                       | [86bca93d29](https://linux-hardware.org/?probe=86bca93d29) | Dec 16, 2020 |
| ASUSTek       | K55DR                       | [300d21973e](https://linux-hardware.org/?probe=300d21973e) | Dec 16, 2020 |
| Lenovo        | IdeaPad 3 14ARE05 81W3      | [667577cb5f](https://linux-hardware.org/?probe=667577cb5f) | Dec 15, 2020 |
| ASUSTek       | 1015BX                      | [5cb5d5f2a8](https://linux-hardware.org/?probe=5cb5d5f2a8) | Dec 15, 2020 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | [406d93673b](https://linux-hardware.org/?probe=406d93673b) | Dec 13, 2020 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | [785196a6d7](https://linux-hardware.org/?probe=785196a6d7) | Dec 13, 2020 |
| Lenovo        | ThinkPad 11e 20DAS15V00     | [8a32a0ec2e](https://linux-hardware.org/?probe=8a32a0ec2e) | Dec 08, 2020 |
| Lenovo        | ThinkPad 11e 20DAS15V00     | [318416a95a](https://linux-hardware.org/?probe=318416a95a) | Dec 08, 2020 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [d4c5036cd3](https://linux-hardware.org/?probe=d4c5036cd3) | Dec 04, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [5f56870146](https://linux-hardware.org/?probe=5f56870146) | Dec 04, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [2a305a9be7](https://linux-hardware.org/?probe=2a305a9be7) | Dec 02, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [cf81aea5fe](https://linux-hardware.org/?probe=cf81aea5fe) | Dec 02, 2020 |
| ASUSTek       | X456URK                     | [be6b2ec83a](https://linux-hardware.org/?probe=be6b2ec83a) | Nov 29, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [7249400d79](https://linux-hardware.org/?probe=7249400d79) | Nov 29, 2020 |
| Lenovo        | IdeaPad Y410P 20216         | [b664b71a15](https://linux-hardware.org/?probe=b664b71a15) | Nov 28, 2020 |
| Lenovo        | IdeaPad 330-14IKB 81G2      | [4be164a8cb](https://linux-hardware.org/?probe=4be164a8cb) | Nov 26, 2020 |
| Acer          | NXHATSN00190808A906600      | [402e6fe81a](https://linux-hardware.org/?probe=402e6fe81a) | Nov 26, 2020 |
| Toshiba       | Satellite L40               | [ffafc05e1f](https://linux-hardware.org/?probe=ffafc05e1f) | Nov 25, 2020 |
| HP            | 14                          | [1a02430025](https://linux-hardware.org/?probe=1a02430025) | Nov 23, 2020 |
| Lenovo        | IdeaPad 330-14IKB 81G2      | [4accc1011e](https://linux-hardware.org/?probe=4accc1011e) | Nov 23, 2020 |
| MSI           | GL65 9SDK                   | [a9b83b75fe](https://linux-hardware.org/?probe=a9b83b75fe) | Nov 22, 2020 |
| Lenovo        | IdeaPad 320-14AST 80XU      | [b17dd2d085](https://linux-hardware.org/?probe=b17dd2d085) | Nov 21, 2020 |
| Lenovo        | IdeaPad 320-14AST 80XU      | [25abf7a587](https://linux-hardware.org/?probe=25abf7a587) | Nov 19, 2020 |
| HP            | 14                          | [548056d4e9](https://linux-hardware.org/?probe=548056d4e9) | Nov 18, 2020 |
| HP            | 14                          | [a08766aff4](https://linux-hardware.org/?probe=a08766aff4) | Nov 18, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [3d65def3ce](https://linux-hardware.org/?probe=3d65def3ce) | Nov 16, 2020 |
| Lenovo        | IdeaPad 320-14AST 80XU      | [82dbd47dff](https://linux-hardware.org/?probe=82dbd47dff) | Nov 15, 2020 |
| Dell          | XPS 13 7390                 | [8844beb362](https://linux-hardware.org/?probe=8844beb362) | Nov 14, 2020 |
| Lenovo        | ThinkPad T410s 2904CGU      | [271f9ac078](https://linux-hardware.org/?probe=271f9ac078) | Nov 14, 2020 |
| Acer          | Aspire V5-132               | [166921ade6](https://linux-hardware.org/?probe=166921ade6) | Nov 13, 2020 |
| Acer          | Aspire E5-421               | [625727a34f](https://linux-hardware.org/?probe=625727a34f) | Nov 12, 2020 |
| Lenovo        | IdeaPad 320-14AST 80XU      | [0b2411ab89](https://linux-hardware.org/?probe=0b2411ab89) | Nov 12, 2020 |
| Lenovo        | G400 20235                  | [e8b5212a0b](https://linux-hardware.org/?probe=e8b5212a0b) | Nov 11, 2020 |
| Acer          | Aspire E5-475G              | [1d195bfc21](https://linux-hardware.org/?probe=1d195bfc21) | Nov 10, 2020 |
| Lenovo        | ThinkPad T430 2342A19       | [579f942204](https://linux-hardware.org/?probe=579f942204) | Nov 09, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [923558f59a](https://linux-hardware.org/?probe=923558f59a) | Nov 08, 2020 |
| ASUSTek       | X453SA                      | [1bb7c5cfe5](https://linux-hardware.org/?probe=1bb7c5cfe5) | Nov 03, 2020 |
| ASUSTek       | X442UQR                     | [98225dbf74](https://linux-hardware.org/?probe=98225dbf74) | Nov 03, 2020 |
| Unknown       | Unknown                     | [4c80913adb](https://linux-hardware.org/?probe=4c80913adb) | Nov 02, 2020 |
| Lenovo        | G40-30 80FY                 | [7bc709a3cd](https://linux-hardware.org/?probe=7bc709a3cd) | Nov 01, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [64b38989db](https://linux-hardware.org/?probe=64b38989db) | Oct 30, 2020 |
| Lenovo        | ThinkPad X230 Tablet 343... | [516ff504f0](https://linux-hardware.org/?probe=516ff504f0) | Oct 29, 2020 |
| Lenovo        | IdeaPad 310-14IKB 80TU      | [45b0065d49](https://linux-hardware.org/?probe=45b0065d49) | Oct 28, 2020 |
| HP            | Notebook                    | [fe4c2b1ca0](https://linux-hardware.org/?probe=fe4c2b1ca0) | Oct 25, 2020 |
| Clevo         | M7x0S                       | [8559d7b074](https://linux-hardware.org/?probe=8559d7b074) | Oct 24, 2020 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [3b60701957](https://linux-hardware.org/?probe=3b60701957) | Oct 23, 2020 |
| Lenovo        | V330-14IKB 81B0             | [0a1f42ff5e](https://linux-hardware.org/?probe=0a1f42ff5e) | Oct 18, 2020 |
| Lenovo        | V330-14IKB 81B0             | [327a983226](https://linux-hardware.org/?probe=327a983226) | Oct 18, 2020 |
| Acer          | Nitro AN515-52              | [ca3d5b9444](https://linux-hardware.org/?probe=ca3d5b9444) | Oct 13, 2020 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [646054c190](https://linux-hardware.org/?probe=646054c190) | Oct 08, 2020 |
| ASUSTek       | X442URR                     | [5e9f9ee314](https://linux-hardware.org/?probe=5e9f9ee314) | Oct 06, 2020 |
| Lenovo        | Yoga 2 Pro 20266            | [57e753215c](https://linux-hardware.org/?probe=57e753215c) | Oct 04, 2020 |
| Lenovo        | IdeaPad Z480                | [36a5cbc73c](https://linux-hardware.org/?probe=36a5cbc73c) | Oct 03, 2020 |
| Lenovo        | IdeaPad Z480                | [f7282459cf](https://linux-hardware.org/?probe=f7282459cf) | Oct 03, 2020 |
| Acer          | NXHATSN00190808A906600      | [ece82b096b](https://linux-hardware.org/?probe=ece82b096b) | Oct 01, 2020 |
| HP            | Pavilion x2 Detachable      | [d4078124eb](https://linux-hardware.org/?probe=d4078124eb) | Sep 30, 2020 |
| ASUSTek       | X450EA                      | [2646942e92](https://linux-hardware.org/?probe=2646942e92) | Sep 30, 2020 |
| HP            | 430                         | [9eef183864](https://linux-hardware.org/?probe=9eef183864) | Sep 27, 2020 |
| Toshiba       | Satellite L730              | [28ff46aa6b](https://linux-hardware.org/?probe=28ff46aa6b) | Sep 25, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [24b078a7f0](https://linux-hardware.org/?probe=24b078a7f0) | Sep 24, 2020 |
| HP            | Laptop 15-bw0xx             | [9067f67190](https://linux-hardware.org/?probe=9067f67190) | Sep 24, 2020 |
| ASUSTek       | X455YA                      | [0959901fca](https://linux-hardware.org/?probe=0959901fca) | Sep 23, 2020 |
| HP            | ENVY Laptop 13-aq1xxx       | [ed83ee1e30](https://linux-hardware.org/?probe=ed83ee1e30) | Sep 22, 2020 |
| Acer          | Aspire ES1-111M             | [4a9dbc9937](https://linux-hardware.org/?probe=4a9dbc9937) | Sep 19, 2020 |
| Acer          | Aspire ES1-111M             | [0e2694227b](https://linux-hardware.org/?probe=0e2694227b) | Sep 19, 2020 |
| Apple         | MacBookPro12,1              | [d766064036](https://linux-hardware.org/?probe=d766064036) | Sep 17, 2020 |
| HP            | 430                         | [bfb152e615](https://linux-hardware.org/?probe=bfb152e615) | Sep 10, 2020 |
| ASUSTek       | GL503VD                     | [820f4da953](https://linux-hardware.org/?probe=820f4da953) | Sep 09, 2020 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | [d545f007f9](https://linux-hardware.org/?probe=d545f007f9) | Sep 05, 2020 |
| Acer          | Nitro AN515-43              | [7e0202ac18](https://linux-hardware.org/?probe=7e0202ac18) | Sep 04, 2020 |
| Acer          | Nitro AN515-43              | [152a400df9](https://linux-hardware.org/?probe=152a400df9) | Sep 04, 2020 |
| Lenovo        | IdeaPad S340-14API 81NB     | [712ec86d11](https://linux-hardware.org/?probe=712ec86d11) | Sep 04, 2020 |
| HP            | Pavilion Gaming Notebook    | [5bcdd6aa5a](https://linux-hardware.org/?probe=5bcdd6aa5a) | Sep 03, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Indonesia/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 105       | 11.05%  |
| Ubuntu 18.04        | 60        | 6.32%   |
| Ubuntu 22.04        | 51        | 5.37%   |
| OpenMandriva 4.3    | 37        | 3.89%   |
| Arch Rolling        | 25        | 2.63%   |
| OpenMandriva 4.2    | 23        | 2.42%   |
| KDE neon 20.04      | 19        | 2%      |
| Fedora 36           | 18        | 1.89%   |
| Arch                | 17        | 1.79%   |
| Pop!_OS 22.04       | 15        | 1.58%   |
| Manjaro             | 15        | 1.58%   |
| Pop!_OS 20.04       | 14        | 1.47%   |
| Zorin 15            | 13        | 1.37%   |
| Elementary 6.1      | 13        | 1.37%   |
| Debian 11           | 13        | 1.37%   |
| Zorin 16            | 12        | 1.26%   |
| Ubuntu 19.10        | 12        | 1.26%   |
| Fedora 37           | 12        | 1.26%   |
| Fedora 35           | 12        | 1.26%   |
| ArcoLinux Rolling   | 12        | 1.26%   |
| Ubuntu 21.10        | 11        | 1.16%   |
| OpenMandriva 23.03  | 11        | 1.16%   |
| Linux Mint 21.1     | 11        | 1.16%   |
| Linux Mint 20.3     | 11        | 1.16%   |
| Fedora 38           | 11        | 1.16%   |
| Xubuntu 20.04       | 9         | 0.95%   |
| OpenMandriva 23.08  | 9         | 0.95%   |
| OpenMandriva 23.01  | 9         | 0.95%   |
| Kubuntu 20.04       | 9         | 0.95%   |
| Linux Mint 19.3     | 8         | 0.84%   |
| Kubuntu 22.04       | 8         | 0.84%   |
| EndeavourOS Rolling | 8         | 0.84%   |
| Debian 10           | 8         | 0.84%   |
| Ubuntu 23.04        | 7         | 0.74%   |
| Ubuntu 21.04        | 7         | 0.74%   |
| Pop!_OS 21.04       | 7         | 0.74%   |
| Linux Mint 20       | 7         | 0.74%   |
| Ubuntu MATE 20.04   | 6         | 0.63%   |
| Ubuntu 19.04        | 6         | 0.63%   |
| Linux Mint 21       | 6         | 0.63%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 256       | 28.54%  |
| OpenMandriva  | 86        | 9.59%   |
| Fedora        | 63        | 7.02%   |
| Linux Mint    | 51        | 5.69%   |
| Arch          | 42        | 4.68%   |
| Pop!_OS       | 41        | 4.57%   |
| Manjaro       | 39        | 4.35%   |
| Elementary    | 29        | 3.23%   |
| Zorin         | 28        | 3.12%   |
| Debian        | 28        | 3.12%   |
| KDE neon      | 25        | 2.79%   |
| Kubuntu       | 23        | 2.56%   |
| Kali          | 22        | 2.45%   |
| Endless       | 20        | 2.23%   |
| Xubuntu       | 19        | 2.12%   |
| Lubuntu       | 13        | 1.45%   |
| ArcoLinux     | 13        | 1.45%   |
| ROSA          | 10        | 1.11%   |
| Ubuntu MATE   | 8         | 0.89%   |
| EndeavourOS   | 8         | 0.89%   |
| openSUSE      | 6         | 0.67%   |
| Ubuntu Unity  | 5         | 0.56%   |
| Parrot        | 5         | 0.56%   |
| LMDE          | 5         | 0.56%   |
| Nobara        | 4         | 0.45%   |
| MX            | 4         | 0.45%   |
| Deepin        | 4         | 0.45%   |
| Artix         | 4         | 0.45%   |
| Ubuntu Budgie | 3         | 0.33%   |
| Gentoo        | 3         | 0.33%   |
| Clear Linux   | 3         | 0.33%   |
| Xero          | 2         | 0.22%   |
| SteamOS       | 2         | 0.22%   |
| Solus         | 2         | 0.22%   |
| Garuda Linux  | 2         | 0.22%   |
| Chrome OS     | 2         | 0.22%   |
| CentOS        | 2         | 0.22%   |
| BlackPanther  | 2         | 0.22%   |
| Void Linux    | 1         | 0.11%   |
| UbuntuDDE     | 1         | 0.11%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 37        | 3.66%   |
| 5.10.14-desktop-1omv4002 | 23        | 2.27%   |
| 5.4.0-42-generic         | 16        | 1.58%   |
| 5.15.0-56-generic        | 13        | 1.29%   |
| 5.4.0-26-generic         | 12        | 1.19%   |
| 5.15.0-41-generic        | 11        | 1.09%   |
| 6.2.6-desktop-1omv2390   | 10        | 0.99%   |
| 6.1.1-desktop-1omv2290   | 9         | 0.89%   |
| 5.4.0-52-generic         | 9         | 0.89%   |
| 5.15.0-46-generic        | 9         | 0.89%   |
| 5.15.0-48-generic        | 8         | 0.79%   |
| 5.0.0-25-generic         | 8         | 0.79%   |
| 4.18.0-15-generic        | 8         | 0.79%   |
| 6.4.11-desktop-1omv2390  | 7         | 0.69%   |
| 5.4.0-58-generic         | 7         | 0.69%   |
| 5.4.0-54-generic         | 7         | 0.69%   |
| 5.15.0-58-generic        | 7         | 0.69%   |
| 5.15.0-47-generic        | 7         | 0.69%   |
| 5.11.0-37-generic        | 7         | 0.69%   |
| 5.8.0-48-generic         | 6         | 0.59%   |
| 5.3.0-46-generic         | 6         | 0.59%   |
| 5.19.0-35-generic        | 6         | 0.59%   |
| 5.15.0-52-generic        | 6         | 0.59%   |
| 5.15.0-43-generic        | 6         | 0.59%   |
| 5.8.0-41-generic         | 5         | 0.49%   |
| 5.4.0-80-generic         | 5         | 0.49%   |
| 5.4.0-45-generic         | 5         | 0.49%   |
| 5.19.0-46-generic        | 5         | 0.49%   |
| 5.15.0-53-generic        | 5         | 0.49%   |
| 5.11.0-7620-generic      | 5         | 0.49%   |
| 5.11.0-40-generic        | 5         | 0.49%   |
| 5.11.0-38-generic        | 5         | 0.49%   |
| 5.11.0-35-generic        | 5         | 0.49%   |
| 5.11.0-27-generic        | 5         | 0.49%   |
| 5.0.0-23-generic         | 5         | 0.49%   |
| 5.4.0-7634-generic       | 4         | 0.4%    |
| 5.4.0-33-generic         | 4         | 0.4%    |
| 5.3.0-26-generic         | 4         | 0.4%    |
| 5.15.0-60-generic        | 4         | 0.4%    |
| 5.13.0-30-generic        | 4         | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 135       | 13.86%  |
| 5.15.0  | 98        | 10.06%  |
| 5.11.0  | 54        | 5.54%   |
| 5.8.0   | 41        | 4.21%   |
| 5.16.7  | 38        | 3.9%    |
| 5.13.0  | 36        | 3.7%    |
| 5.3.0   | 33        | 3.39%   |
| 5.0.0   | 30        | 3.08%   |
| 4.15.0  | 29        | 2.98%   |
| 5.19.0  | 26        | 2.67%   |
| 5.10.14 | 24        | 2.46%   |
| 5.10.0  | 23        | 2.36%   |
| 4.18.0  | 17        | 1.75%   |
| 6.2.0   | 14        | 1.44%   |
| 6.2.6   | 13        | 1.33%   |
| 6.1.0   | 13        | 1.33%   |
| 4.19.0  | 13        | 1.33%   |
| 6.1.1   | 12        | 1.23%   |
| 6.4.11  | 9         | 0.92%   |
| 5.17.5  | 6         | 0.62%   |
| 5.16.0  | 6         | 0.62%   |
| 5.14.0  | 6         | 0.62%   |
| 6.0.12  | 4         | 0.41%   |
| 5.15.12 | 4         | 0.41%   |
| 5.14.16 | 4         | 0.41%   |
| 4.4.0   | 4         | 0.41%   |
| 6.4.8   | 3         | 0.31%   |
| 6.4.10  | 3         | 0.31%   |
| 6.3.5   | 3         | 0.31%   |
| 6.3.3   | 3         | 0.31%   |
| 6.2.9   | 3         | 0.31%   |
| 6.2.8   | 3         | 0.31%   |
| 6.0.9   | 3         | 0.31%   |
| 6.0.0   | 3         | 0.31%   |
| 5.9.11  | 3         | 0.31%   |
| 5.9.1   | 3         | 0.31%   |
| 5.19.16 | 3         | 0.31%   |
| 5.19.15 | 3         | 0.31%   |
| 5.18.0  | 3         | 0.31%   |
| 5.17.6  | 3         | 0.31%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 143       | 14.9%   |
| 5.15    | 119       | 12.4%   |
| 5.10    | 72        | 7.5%    |
| 5.16    | 57        | 5.94%   |
| 5.11    | 57        | 5.94%   |
| 5.8     | 52        | 5.42%   |
| 6.1     | 40        | 4.17%   |
| 5.13    | 40        | 4.17%   |
| 6.2     | 39        | 4.06%   |
| 5.19    | 38        | 3.96%   |
| 5.3     | 35        | 3.65%   |
| 5.0     | 32        | 3.33%   |
| 4.15    | 29        | 3.02%   |
| 6.4     | 22        | 2.29%   |
| 6.0     | 20        | 2.08%   |
| 5.14    | 20        | 2.08%   |
| 4.18    | 20        | 2.08%   |
| 5.17    | 18        | 1.88%   |
| 4.19    | 18        | 1.88%   |
| 6.3     | 15        | 1.56%   |
| 5.18    | 15        | 1.56%   |
| 5.9     | 12        | 1.25%   |
| 4.9     | 8         | 0.83%   |
| 5.6     | 7         | 0.73%   |
| 5.12    | 6         | 0.63%   |
| 5.7     | 5         | 0.52%   |
| 5.5     | 5         | 0.52%   |
| 4.4     | 5         | 0.52%   |
| 5.2     | 2         | 0.21%   |
| 4.13    | 2         | 0.21%   |
| 4.10    | 2         | 0.21%   |
| 4.1     | 2         | 0.21%   |
| 6.5     | 1         | 0.1%    |
| 5       | 1         | 0.1%    |
| 3.16    | 1         | 0.1%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 841       | 97.56%  |
| i686   | 21        | 2.44%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 377       | 41.84%  |
| KDE5            | 173       | 19.2%   |
| Unknown         | 80        | 8.88%   |
| XFCE            | 77        | 8.55%   |
| X-Cinnamon      | 50        | 5.55%   |
| Pantheon        | 28        | 3.11%   |
| MATE            | 21        | 2.33%   |
| KDE             | 18        | 2%      |
| LXQt            | 16        | 1.78%   |
| Cinnamon        | 12        | 1.33%   |
| Budgie          | 6         | 0.67%   |
| Unity           | 5         | 0.55%   |
| Deepin          | 5         | 0.55%   |
| i3              | 4         | 0.44%   |
| sway            | 3         | 0.33%   |
| KDE4            | 3         | 0.33%   |
| Hyprland        | 3         | 0.33%   |
| GNOME Flashback | 3         | 0.33%   |
| DWM             | 3         | 0.33%   |
| qtile           | 2         | 0.22%   |
| ICEWM           | 2         | 0.22%   |
| Cutefish        | 2         | 0.22%   |
| bspwm           | 2         | 0.22%   |
| xmonad          | 1         | 0.11%   |
| openbox         | 1         | 0.11%   |
| LXDE            | 1         | 0.11%   |
| Lubuntu         | 1         | 0.11%   |
| awesomeminimal  | 1         | 0.11%   |
| awesome         | 1         | 0.11%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 670       | 75.37%  |
| Wayland | 159       | 17.89%  |
| Unknown | 54        | 6.07%   |
| Tty     | 6         | 0.67%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 375       | 41.95%  |
| SDDM    | 165       | 18.46%  |
| GDM     | 126       | 14.09%  |
| LightDM | 101       | 11.3%   |
| GDM3    | 91        | 10.18%  |
| TDM     | 29        | 3.24%   |
| KDM     | 3         | 0.34%   |
| SLiM    | 2         | 0.22%   |
| Ly      | 1         | 0.11%   |
| LXDM    | 1         | 0.11%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 708       | 80.73%  |
| Unknown | 77        | 8.78%   |
| id_ID   | 59        | 6.73%   |
| en_GB   | 11        | 1.25%   |
| C       | 10        | 1.14%   |
| en_SG   | 3         | 0.34%   |
| en_AU   | 2         | 0.23%   |
| en_AG   | 2         | 0.23%   |
| jv_ID   | 1         | 0.11%   |
| fr_FR   | 1         | 0.11%   |
| en_IN   | 1         | 0.11%   |
| de_DE   | 1         | 0.11%   |
| de_CH   | 1         | 0.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 521       | 59.14%  |
| BIOS | 360       | 40.86%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 673       | 76.3%   |
| Btrfs   | 90        | 10.2%   |
| Overlay | 64        | 7.26%   |
| Unknown | 25        | 2.83%   |
| Xfs     | 7         | 0.79%   |
| Tmpfs   | 7         | 0.79%   |
| Zfs     | 5         | 0.57%   |
| Ext2    | 5         | 0.57%   |
| F2fs    | 4         | 0.45%   |
| Ext3    | 2         | 0.23%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 394       | 44.67%  |
| GPT     | 373       | 42.29%  |
| MBR     | 115       | 13.04%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 759       | 86.64%  |
| Yes       | 117       | 13.36%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 495       | 56.31%  |
| Yes       | 384       | 43.69%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 215       | 24.94%  |
| ASUSTek Computer    | 187       | 21.69%  |
| Acer                | 130       | 15.08%  |
| Hewlett-Packard     | 129       | 14.97%  |
| Dell                | 68        | 7.89%   |
| Toshiba             | 30        | 3.48%   |
| MSI                 | 21        | 2.44%   |
| AXIOO               | 12        | 1.39%   |
| Apple               | 12        | 1.39%   |
| Sony                | 10        | 1.16%   |
| Fujitsu             | 9         | 1.04%   |
| Samsung Electronics | 5         | 0.58%   |
| Infinix             | 5         | 0.58%   |
| HUAWEI              | 3         | 0.35%   |
| Clevo               | 3         | 0.35%   |
| Timi                | 2         | 0.23%   |
| Panasonic           | 2         | 0.23%   |
| Intel               | 2         | 0.23%   |
| Gigabyte Technology | 2         | 0.23%   |
| Unknown             | 2         | 0.23%   |
| Valve               | 1         | 0.12%   |
| Sole                | 1         | 0.12%   |
| Phoenix/SiS         | 1         | 0.12%   |
| Notebook            | 1         | 0.12%   |
| Hampoo              | 1         | 0.12%   |
| GPD                 | 1         | 0.12%   |
| Google              | 1         | 0.12%   |
| Compal              | 1         | 0.12%   |
| Chuwi               | 1         | 0.12%   |
| AZW                 | 1         | 0.12%   |
| AVITA               | 1         | 0.12%   |
| Alurin              | 1         | 0.12%   |
| ADVAN               | 1         | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Lenovo IdeaPad 330-14AST 81D5           | 11        | 1.28%   |
| Lenovo G40-45 80E1                      | 10        | 1.16%   |
| HP Notebook                             | 9         | 1.04%   |
| HP Pavilion Aero Laptop 13-be0xxx       | 8         | 0.93%   |
| Acer Aspire 4752                        | 8         | 0.93%   |
| Lenovo IdeaPad S340-14API 81NB          | 6         | 0.7%    |
| HP Laptop 14-bw0xx                      | 6         | 0.7%    |
| HP 14                                   | 6         | 0.7%    |
| Acer Aspire 4750                        | 6         | 0.7%    |
| Lenovo G400 20235                       | 5         | 0.58%   |
| HP Pavilion g4                          | 5         | 0.58%   |
| ASUS X455YA                             | 5         | 0.58%   |
| ASUS X455LF                             | 5         | 0.58%   |
| ASUS VivoBook_ASUS Laptop X505ZA_X505ZA | 5         | 0.58%   |
| Apple MacBookPro12,1                    | 5         | 0.58%   |
| Acer Swift SF314-71                     | 5         | 0.58%   |
| Acer One Z1402                          | 5         | 0.58%   |
| Unknown                                 | 5         | 0.58%   |
| Lenovo IdeaPad 320-14AST 80XU           | 4         | 0.46%   |
| Lenovo G40-30 80FY                      | 4         | 0.46%   |
| HP Pavilion 14                          | 4         | 0.46%   |
| HP Laptop 14-cm0xxx                     | 4         | 0.46%   |
| HP Laptop 14-bs0xx                      | 4         | 0.46%   |
| HP 1000                                 | 4         | 0.46%   |
| ASUS X456URK                            | 4         | 0.46%   |
| ASUS X453SA                             | 4         | 0.46%   |
| ASUS X442URR                            | 4         | 0.46%   |
| ASUS X200MA                             | 4         | 0.46%   |
| ASUS GL553VD                            | 4         | 0.46%   |
| Acer Aspire E5-476G                     | 4         | 0.46%   |
| Acer Aspire E5-475G                     | 4         | 0.46%   |
| Lenovo V310-14ISK 80SX                  | 3         | 0.35%   |
| Lenovo ThinkBook 14 G3 ACL 21A2         | 3         | 0.35%   |
| Lenovo IdeaPad 320-14ISK 80XG           | 3         | 0.35%   |
| Lenovo IdeaPad 3 14ARE05 81W3           | 3         | 0.35%   |
| Lenovo IdeaPad 100-14IBD 80RK           | 3         | 0.35%   |
| Lenovo G400s 20244                      | 3         | 0.35%   |
| Dell Latitude E6230                     | 3         | 0.35%   |
| Dell G7 7588                            | 3         | 0.35%   |
| AXIOO Mybook 14E                        | 3         | 0.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo IdeaPad     | 84        | 9.74%   |
| Acer Aspire        | 79        | 9.16%   |
| Lenovo ThinkPad    | 73        | 8.47%   |
| HP Laptop          | 35        | 4.06%   |
| ASUS VivoBook      | 35        | 4.06%   |
| Dell Latitude      | 32        | 3.71%   |
| HP Pavilion        | 31        | 3.6%    |
| Toshiba Satellite  | 20        | 2.32%   |
| Acer Swift         | 19        | 2.2%    |
| Dell Inspiron      | 17        | 1.97%   |
| HP EliteBook       | 15        | 1.74%   |
| Lenovo G40-45      | 10        | 1.16%   |
| Dell Vostro        | 10        | 1.16%   |
| Lenovo ThinkBook   | 9         | 1.04%   |
| HP Notebook        | 9         | 1.04%   |
| Acer Nitro         | 8         | 0.93%   |
| Toshiba PORTEGE    | 7         | 0.81%   |
| HP ProBook         | 7         | 0.81%   |
| ASUS TUF           | 7         | 0.81%   |
| MSI Modern         | 6         | 0.7%    |
| HP 14              | 6         | 0.7%    |
| Acer One           | 6         | 0.7%    |
| Lenovo Yoga        | 5         | 0.58%   |
| Lenovo G400        | 5         | 0.58%   |
| Infinix INBook     | 5         | 0.58%   |
| AXIOO Mybook       | 5         | 0.58%   |
| ASUS X455YA        | 5         | 0.58%   |
| ASUS X455LF        | 5         | 0.58%   |
| ASUS ASUS          | 5         | 0.58%   |
| Apple MacBookPro12 | 5         | 0.58%   |
| Unknown            | 5         | 0.58%   |
| Lenovo Legion      | 4         | 0.46%   |
| Lenovo G40-30      | 4         | 0.46%   |
| HP ENVY            | 4         | 0.46%   |
| HP 1000            | 4         | 0.46%   |
| ASUS ZenBook       | 4         | 0.46%   |
| ASUS X456URK       | 4         | 0.46%   |
| ASUS X453SA        | 4         | 0.46%   |
| ASUS X442URR       | 4         | 0.46%   |
| ASUS X200MA        | 4         | 0.46%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 90        | 10.44%  |
| 2019 | 86        | 9.98%   |
| 2012 | 76        | 8.82%   |
| 2021 | 75        | 8.7%    |
| 2013 | 73        | 8.47%   |
| 2011 | 68        | 7.89%   |
| 2014 | 62        | 7.19%   |
| 2015 | 58        | 6.73%   |
| 2020 | 56        | 6.5%    |
| 2017 | 55        | 6.38%   |
| 2016 | 46        | 5.34%   |
| 2010 | 43        | 4.99%   |
| 2009 | 23        | 2.67%   |
| 2022 | 20        | 2.32%   |
| 2008 | 16        | 1.86%   |
| 2007 | 9         | 1.04%   |
| 2023 | 3         | 0.35%   |
| 2006 | 3         | 0.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 862       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 793       | 90.84%  |
| Enabled  | 80        | 9.16%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 861       | 99.88%  |
| Yes  | 1         | 0.12%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 285       | 32.72%  |
| 3.01-4.0    | 233       | 26.75%  |
| 8.01-16.0   | 143       | 16.42%  |
| 16.01-24.0  | 99        | 11.37%  |
| 1.01-2.0    | 78        | 8.96%   |
| 32.01-64.0  | 11        | 1.26%   |
| 2.01-3.0    | 10        | 1.15%   |
| 24.01-32.0  | 6         | 0.69%   |
| 0.51-1.0    | 5         | 0.57%   |
| 64.01-256.0 | 1         | 0.11%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 337       | 35.62%  |
| 2.01-3.0   | 268       | 28.33%  |
| 3.01-4.0   | 127       | 13.42%  |
| 4.01-8.0   | 125       | 13.21%  |
| 0.51-1.0   | 56        | 5.92%   |
| 8.01-16.0  | 27        | 2.85%   |
| 0.01-0.5   | 4         | 0.42%   |
| 16.01-24.0 | 2         | 0.21%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 622       | 70.84%  |
| 2      | 226       | 25.74%  |
| 3      | 23        | 2.62%   |
| 0      | 4         | 0.46%   |
| 4      | 3         | 0.34%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 556       | 63.98%  |
| Yes       | 313       | 36.02%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 709       | 82.16%  |
| No        | 154       | 17.84%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 848       | 98.26%  |
| No        | 15        | 1.74%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 673       | 77.45%  |
| No        | 196       | 22.55%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Indonesia | 862       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Notebooks | Percent |
|-----------------|-----------|---------|
| Jakarta         | 253       | 26.83%  |
| Surabaya        | 97        | 10.29%  |
| Bandung         | 64        | 6.79%   |
| Yogyakarta      | 34        | 3.61%   |
| Bogor           | 34        | 3.61%   |
| Semarang        | 32        | 3.39%   |
| Bekasi          | 25        | 2.65%   |
| Malang          | 21        | 2.23%   |
| Denpasar        | 21        | 2.23%   |
| Tangerang       | 18        | 1.91%   |
| Medan           | 15        | 1.59%   |
| South Tangerang | 14        | 1.48%   |
| Makassar        | 13        | 1.38%   |
| Sleman          | 11        | 1.17%   |
| Palembang       | 10        | 1.06%   |
| Depok           | 10        | 1.06%   |
| Banjarmasin     | 8         | 0.85%   |
| Tasikmalaya     | 7         | 0.74%   |
| Surakarta       | 7         | 0.74%   |
| Samarinda       | 7         | 0.74%   |
| Blitar          | 7         | 0.74%   |
| Balikpapan      | 7         | 0.74%   |
| Magelang        | 6         | 0.64%   |
| Kudus           | 6         | 0.64%   |
| Brebes          | 6         | 0.64%   |
| Banda Aceh      | 6         | 0.64%   |
| Pontianak       | 5         | 0.53%   |
| Kediri          | 5         | 0.53%   |
| Gresik          | 5         | 0.53%   |
| Demak           | 5         | 0.53%   |
| Cirebon         | 5         | 0.53%   |
| Mataram         | 4         | 0.42%   |
| Jember          | 4         | 0.42%   |
| Jambi City      | 4         | 0.42%   |
| Batam           | 4         | 0.42%   |
| Tegal           | 3         | 0.32%   |
| Sukabumi        | 3         | 0.32%   |
| Sragen          | 3         | 0.32%   |
| Purwokerto      | 3         | 0.32%   |
| Pekan Baru      | 3         | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 174       | 224    | 15.8%   |
| WDC                   | 136       | 161    | 12.35%  |
| Toshiba               | 111       | 123    | 10.08%  |
| Samsung Electronics   | 104       | 141    | 9.45%   |
| HGST                  | 59        | 66     | 5.36%   |
| Hitachi               | 45        | 52     | 4.09%   |
| Unknown               | 38        | 46     | 3.45%   |
| SanDisk               | 36        | 46     | 3.27%   |
| Intel                 | 35        | 53     | 3.18%   |
| Kingston              | 33        | 41     | 3%      |
| SK hynix              | 29        | 34     | 2.63%   |
| V-GeN                 | 26        | 27     | 2.36%   |
| Micron Technology     | 26        | 34     | 2.36%   |
| A-DATA Technology     | 21        | 27     | 1.91%   |
| MidasForce            | 19        | 20     | 1.73%   |
| Unknown               | 13        | 14     | 1.18%   |
| VISIPRO               | 12        | 15     | 1.09%   |
| China                 | 12        | 12     | 1.09%   |
| Fujitsu               | 11        | 12     | 1%      |
| Apacer                | 10        | 10     | 0.91%   |
| Team                  | 9         | 12     | 0.82%   |
| JMicron Technology    | 9         | 10     | 0.82%   |
| Crucial               | 8         | 10     | 0.73%   |
| EYOTA                 | 7         | 8      | 0.64%   |
| Apple                 | 7         | 8      | 0.64%   |
| Patriot               | 6         | 8      | 0.54%   |
| Silicon Motion        | 5         | 6      | 0.45%   |
| RX7                   | 5         | 6      | 0.45%   |
| Phison Electronics    | 5         | 6      | 0.45%   |
| Wellcomm              | 4         | 4      | 0.36%   |
| External              | 4         | 4      | 0.36%   |
| Realtek Semiconductor | 3         | 3      | 0.27%   |
| Pioneer               | 3         | 3      | 0.27%   |
| LITEONIT              | 3         | 4      | 0.27%   |
| LITEON                | 3         | 4      | 0.27%   |
| KIOXIA                | 3         | 3      | 0.27%   |
| FORESEE               | 3         | 3      | 0.27%   |
| Union Memory          | 2         | 2      | 0.18%   |
| UMIS                  | 2         | 3      | 0.18%   |
| Transcend             | 2         | 3      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Seagate ST500LT012-1DG142 500GB    | 40        | 3.53%   |
| Seagate ST1000LM035-1RK172 1TB     | 37        | 3.26%   |
| Toshiba MQ01ABF050 500GB           | 23        | 2.03%   |
| Toshiba MQ04ABF100 1TB             | 21        | 1.85%   |
| Toshiba MQ01ABD100 1TB             | 18        | 1.59%   |
| HGST HTS545050A7E680 500GB         | 17        | 1.5%    |
| Unknown                            | 13        | 1.15%   |
| A-DATA SU650 120GB SSD             | 11        | 0.97%   |
| Seagate ST9500325AS 500GB          | 10        | 0.88%   |
| Hitachi HTS545050A7E380 500GB      | 10        | 0.88%   |
| HGST HTS725050A7E630 500GB         | 10        | 0.88%   |
| Seagate ST500LT012-9WS142 500GB    | 9         | 0.79%   |
| SanDisk NVMe SSD Drive 512GB       | 9         | 0.79%   |
| Intel SSDPEKNW512G8 512GB          | 9         | 0.79%   |
| WDC WD10SPZX-21Z10T0 1TB           | 8         | 0.71%   |
| Hitachi HTS543232A7A384 320GB      | 8         | 0.71%   |
| HGST HTS721010A9E630 1TB           | 8         | 0.71%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 7         | 0.62%   |
| Seagate ST9320325AS 320GB          | 7         | 0.62%   |
| Seagate ST2000LM007-1R8174 2TB     | 7         | 0.62%   |
| Samsung SSD 850 EVO 250GB          | 7         | 0.62%   |
| MidasForce SSD 128GB               | 7         | 0.62%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 6         | 0.53%   |
| WDC WD5000LPVX-80V0TT0 500GB       | 6         | 0.53%   |
| Unknown MMC Card  32GB             | 6         | 0.53%   |
| Seagate ST1000LX015-1U7172 1TB     | 6         | 0.53%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 6         | 0.53%   |
| Kingston SA400S37240G 240GB SSD    | 6         | 0.53%   |
| HGST HTS545050A7E380 500GB         | 6         | 0.53%   |
| HGST HTS541010A9E680 1TB           | 6         | 0.53%   |
| WDC WD10JPCX-24UE4T0 1TB           | 5         | 0.44%   |
| Seagate ST500LM021-1KJ152 500GB    | 5         | 0.44%   |
| Samsung SSD 860 EVO 250GB          | 5         | 0.44%   |
| Micron 2450_MTFDKBA512TFK 512GB    | 5         | 0.44%   |
| JMicron Generic 1TB                | 5         | 0.44%   |
| Intel NVMe SSD Drive 512GB         | 5         | 0.44%   |
| WDC WDS120G2G0A-00JH30 120GB SSD   | 4         | 0.35%   |
| WDC WD5000LPCX-24C6HT0 500GB       | 4         | 0.35%   |
| WDC WD10SPZX-60Z10T0 1TB           | 4         | 0.35%   |
| WDC WD10SPZX-24Z10 1TB             | 4         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 172       | 219    | 34.06%  |
| WDC                 | 103       | 116    | 20.4%   |
| Toshiba             | 96        | 106    | 19.01%  |
| HGST                | 59        | 66     | 11.68%  |
| Hitachi             | 45        | 52     | 8.91%   |
| Fujitsu             | 9         | 9      | 1.78%   |
| Unknown             | 5         | 5      | 0.99%   |
| Samsung Electronics | 4         | 4      | 0.79%   |
| External            | 4         | 4      | 0.79%   |
| Pioneer             | 2         | 2      | 0.4%    |
| USB3.0              | 1         | 1      | 0.2%    |
| SYMTEC              | 1         | 1      | 0.2%    |
| JMicron Technology  | 1         | 1      | 0.2%    |
| HGST HTS            | 1         | 3      | 0.2%    |
| Hewlett-Packard     | 1         | 1      | 0.2%    |
| Apple               | 1         | 1      | 0.2%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 45        | 56     | 15.1%   |
| WDC                 | 19        | 28     | 6.38%   |
| MidasForce          | 19        | 20     | 6.38%   |
| V-GeN               | 18        | 19     | 6.04%   |
| Kingston            | 18        | 19     | 6.04%   |
| A-DATA Technology   | 16        | 21     | 5.37%   |
| SanDisk             | 15        | 23     | 5.03%   |
| China               | 12        | 12     | 4.03%   |
| VISIPRO             | 10        | 13     | 3.36%   |
| Apacer              | 10        | 10     | 3.36%   |
| Unknown             | 9         | 9      | 3.02%   |
| Intel               | 8         | 12     | 2.68%   |
| Team                | 7         | 10     | 2.35%   |
| Crucial             | 7         | 9      | 2.35%   |
| Patriot             | 6         | 8      | 2.01%   |
| EYOTA               | 6         | 6      | 2.01%   |
| Toshiba             | 5         | 6      | 1.68%   |
| JMicron Technology  | 5         | 5      | 1.68%   |
| Apple               | 5         | 5      | 1.68%   |
| Wellcomm            | 4         | 4      | 1.34%   |
| Seagate             | 4         | 4      | 1.34%   |
| Micron Technology   | 4         | 5      | 1.34%   |
| RX7                 | 3         | 4      | 1.01%   |
| LITEONIT            | 3         | 4      | 1.01%   |
| LITEON              | 3         | 4      | 1.01%   |
| Smart               | 2         | 2      | 0.67%   |
| SK hynix            | 2         | 2      | 0.67%   |
| Ramos Technology    | 2         | 4      | 0.67%   |
| Lexar               | 2         | 2      | 0.67%   |
| Kingmax             | 2         | 2      | 0.67%   |
| GALAX               | 2         | 2      | 0.67%   |
| FORESEE             | 2         | 2      | 0.67%   |
| XSTAR               | 1         | 1      | 0.34%   |
| WellcommMaster      | 1         | 1      | 0.34%   |
| Vaseky              | 1         | 2      | 0.34%   |
| Varro               | 1         | 1      | 0.34%   |
| ValueTech           | 1         | 1      | 0.34%   |
| Union Memory        | 1         | 1      | 0.34%   |
| UNIC2               | 1         | 1      | 0.34%   |
| Transcend           | 1         | 1      | 0.34%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 484       | 591    | 45.62%  |
| SSD     | 284       | 356    | 26.77%  |
| NVMe    | 232       | 310    | 21.87%  |
| Unknown | 31        | 37     | 2.92%   |
| MMC     | 30        | 39     | 2.83%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 668       | 947    | 69.22%  |
| NVMe | 232       | 309    | 24.04%  |
| SAS  | 35        | 38     | 3.63%   |
| MMC  | 30        | 39     | 3.11%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 506       | 676    | 69.99%  |
| 0.51-1.0   | 202       | 244    | 27.94%  |
| 1.01-2.0   | 14        | 26     | 1.94%   |
| 3.01-4.0   | 1         | 1      | 0.14%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 266       | 29.39%  |
| 251-500        | 235       | 25.97%  |
| 501-1000       | 103       | 11.38%  |
| 51-100         | 96        | 10.61%  |
| 1-20           | 64        | 7.07%   |
| 1001-2000      | 62        | 6.85%   |
| 21-50          | 56        | 6.19%   |
| Unknown        | 10        | 1.1%    |
| 2001-3000      | 7         | 0.77%   |
| More than 3000 | 6         | 0.66%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 345       | 36.32%  |
| 21-50          | 190       | 20%     |
| 101-250        | 129       | 13.58%  |
| 51-100         | 121       | 12.74%  |
| 251-500        | 88        | 9.26%   |
| 501-1000       | 51        | 5.37%   |
| 1001-2000      | 12        | 1.26%   |
| Unknown        | 10        | 1.05%   |
| 2001-3000      | 3         | 0.32%   |
| More than 3000 | 1         | 0.11%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Notebooks | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| HGST HTS545050A7E680 500GB       | 8         | 9      | 6.9%    |
| Seagate ST500LT012-9WS142 500GB  | 6         | 6      | 5.17%   |
| Seagate ST500LT012-1DG142 500GB  | 6         | 6      | 5.17%   |
| Seagate ST9500325AS 500GB        | 4         | 4      | 3.45%   |
| Toshiba MQ01ABF050 500GB         | 3         | 3      | 2.59%   |
| Toshiba MQ01ABD032 320GB         | 3         | 3      | 2.59%   |
| Seagate ST1000LM035-1RK172 1TB   | 3         | 3      | 2.59%   |
| Hitachi HTS545050A7E380 500GB    | 3         | 3      | 2.59%   |
| HGST HTS725050A7E630 500GB       | 3         | 3      | 2.59%   |
| WDC WD5000LPVX-22V0TT0 500GB     | 2         | 2      | 1.72%   |
| WDC WD3200BEKT-60V5T1 320GB      | 2         | 2      | 1.72%   |
| WDC WD10JPCX-24UE4T0 1TB         | 2         | 3      | 1.72%   |
| Toshiba MQ01ABD050 500GB         | 2         | 2      | 1.72%   |
| Toshiba MK5059GSXP 500GB         | 2         | 2      | 1.72%   |
| Toshiba MK3265GSX 320GB          | 2         | 3      | 1.72%   |
| Seagate ST1000LX015-1U7172 1TB   | 2         | 3      | 1.72%   |
| HGST HTS545050A7E380 500GB       | 2         | 2      | 1.72%   |
| WellcommMaster 128GB SSD         | 1         | 1      | 0.86%   |
| Wellcomm Master 128GB SSD        | 1         | 1      | 0.86%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 1         | 1      | 0.86%   |
| WDC WD5000LPVX-80V0TT0 500GB     | 1         | 1      | 0.86%   |
| WDC WD5000LPVT-22G33T0 500GB     | 1         | 1      | 0.86%   |
| WDC WD5000LPCX-22VHAT0 500GB     | 1         | 1      | 0.86%   |
| WDC WD5000L 500GB                | 1         | 1      | 0.86%   |
| WDC WD5000BPVT-60HXZT3 500GB     | 1         | 1      | 0.86%   |
| WDC WD5000BPVT-08HXZT3 500GB     | 1         | 1      | 0.86%   |
| WDC WD5000BPVT-00HXZT3 500GB     | 1         | 1      | 0.86%   |
| WDC WD10SPZX-24Z10T0 1TB         | 1         | 1      | 0.86%   |
| WDC WD10SPZX-24Z10 1TB           | 1         | 1      | 0.86%   |
| VISIPRO SSD 256GB                | 1         | 3      | 0.86%   |
| ValueTech SSD 256GB              | 1         | 1      | 0.86%   |
| Toshiba MQ04ABF100 1TB           | 1         | 1      | 0.86%   |
| Toshiba MQ01ABD100 1TB           | 1         | 1      | 0.86%   |
| Toshiba MQ01ABD075 752GB         | 1         | 1      | 0.86%   |
| Toshiba MK7575GSX 752GB          | 1         | 2      | 0.86%   |
| Toshiba MK5075GSX 500GB          | 1         | 1      | 0.86%   |
| Toshiba MK3276GSX 320GB          | 1         | 1      | 0.86%   |
| Toshiba MK3275GSX 320GB          | 1         | 1      | 0.86%   |
| Toshiba MK3265GSXN 320GB         | 1         | 1      | 0.86%   |
| Toshiba MK3263GSX 320GB          | 1         | 1      | 0.86%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 28        | 37     | 24.56%  |
| Toshiba             | 21        | 23     | 18.42%  |
| HGST                | 17        | 19     | 14.91%  |
| WDC                 | 16        | 17     | 14.04%  |
| Hitachi             | 12        | 12     | 10.53%  |
| Samsung Electronics | 3         | 4      | 2.63%   |
| SanDisk             | 2         | 2      | 1.75%   |
| Micron Technology   | 2         | 2      | 1.75%   |
| A-DATA Technology   | 2         | 4      | 1.75%   |
| WellcommMaster      | 1         | 1      | 0.88%   |
| Wellcomm            | 1         | 1      | 0.88%   |
| VISIPRO             | 1         | 3      | 0.88%   |
| ValueTech           | 1         | 1      | 0.88%   |
| SK hynix            | 1         | 1      | 0.88%   |
| RX7                 | 1         | 1      | 0.88%   |
| KLEVV               | 1         | 1      | 0.88%   |
| Intel               | 1         | 1      | 0.88%   |
| Crucial             | 1         | 1      | 0.88%   |
| China               | 1         | 1      | 0.88%   |
| Unknown             | 1         | 1      | 0.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 28        | 37     | 29.79%  |
| Toshiba             | 21        | 23     | 22.34%  |
| HGST                | 17        | 19     | 18.09%  |
| WDC                 | 15        | 16     | 15.96%  |
| Hitachi             | 12        | 12     | 12.77%  |
| Samsung Electronics | 1         | 1      | 1.06%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 93        | 108    | 82.3%   |
| SSD  | 17        | 21     | 15.04%  |
| NVMe | 3         | 4      | 2.65%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                         | Notebooks | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| WDC WD5000BPVT-60HXZT1 500GB  | 1         | 1      | 50%     |
| Hitachi HTS545050A7E380 500GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Hitachi | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 451       | 678    | 48.18%  |
| Works    | 374       | 520    | 39.96%  |
| Malfunc  | 109       | 133    | 11.65%  |
| Failed   | 2         | 2      | 0.21%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 602       | 60.08%  |
| AMD                              | 174       | 17.37%  |
| Samsung Electronics              | 62        | 6.19%   |
| SanDisk                          | 36        | 3.59%   |
| SK hynix                         | 26        | 2.59%   |
| Micron Technology                | 22        | 2.2%    |
| Kingston Technology Company      | 16        | 1.6%    |
| Phison Electronics               | 11        | 1.1%    |
| Silicon Motion                   | 9         | 0.9%    |
| Toshiba America Info Systems     | 8         | 0.8%    |
| ADATA Technology                 | 7         | 0.7%    |
| KIOXIA                           | 5         | 0.5%    |
| Union Memory (Shenzhen)          | 4         | 0.4%    |
| Silicon Integrated Systems [SiS] | 4         | 0.4%    |
| Realtek Semiconductor            | 4         | 0.4%    |
| Shenzhen Longsys Electronics     | 3         | 0.3%    |
| Nvidia                           | 2         | 0.2%    |
| Micron/Crucial Technology        | 2         | 0.2%    |
| O2 Micro                         | 1         | 0.1%    |
| MAXIO Technology (Hangzhou)      | 1         | 0.1%    |
| Lenovo                           | 1         | 0.1%    |
| ASMedia Technology               | 1         | 0.1%    |
| Apple                            | 1         | 0.1%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 163       | 15.26%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 79        | 7.4%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 79        | 7.4%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 52        | 4.87%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 46        | 4.31%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 46        | 4.31%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 32        | 3%      |
| Samsung NVMe SSD Controller 980                                                  | 27        | 2.53%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 27        | 2.53%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 21        | 1.97%   |
| Intel Volume Management Device NVMe RAID Controller                              | 20        | 1.87%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 20        | 1.87%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 17        | 1.59%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 17        | 1.59%   |
| Intel SSD 660P Series                                                            | 16        | 1.5%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 15        | 1.4%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 14        | 1.31%   |
| Intel Tiger Lake-LP SATA Controller                                              | 14        | 1.31%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 14        | 1.31%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 12        | 1.12%   |
| Micron 2210 NVMe SSD [Cobain]                                                    | 11        | 1.03%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 11        | 1.03%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 11        | 1.03%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 11        | 1.03%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 9         | 0.84%   |
| SanDisk PC SN520 NVMe SSD                                                        | 9         | 0.84%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 9         | 0.84%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 8         | 0.75%   |
| SK hynix BC511 NVMe SSD                                                          | 8         | 0.75%   |
| Intel Comet Lake SATA AHCI Controller                                            | 8         | 0.75%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 7         | 0.66%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 7         | 0.66%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                      | 7         | 0.66%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 7         | 0.66%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 6         | 0.56%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 6         | 0.56%   |
| Phison PS5013 E13 NVMe Controller                                                | 6         | 0.56%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                    | 6         | 0.56%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 6         | 0.56%   |
| Intel SSD 670p Series [Keystone Harbor]                                          | 6         | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 700       | 67.37%  |
| NVMe | 232       | 22.33%  |
| RAID | 66        | 6.35%   |
| IDE  | 41        | 3.95%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 646       | 74.94%  |
| AMD    | 216       | 25.06%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 17        | 1.97%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 15        | 1.74%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 14        | 1.62%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G  | 14        | 1.62%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 13        | 1.51%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 13        | 1.51%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 13        | 1.51%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 13        | 1.51%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 13        | 1.51%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 13        | 1.51%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 11        | 1.27%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 11        | 1.27%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 10        | 1.16%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 10        | 1.16%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 10        | 1.16%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 10        | 1.16%   |
| AMD Ryzen 5 5600U with Radeon Graphics        | 10        | 1.16%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 10        | 1.16%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G  | 10        | 1.16%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 10        | 1.16%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 9         | 1.04%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 9         | 1.04%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 9         | 1.04%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 9         | 1.04%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 8         | 0.93%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 8         | 0.93%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 8         | 0.93%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 8         | 0.93%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 7         | 0.81%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 7         | 0.81%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 7         | 0.81%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 7         | 0.81%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 7         | 0.81%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 7         | 0.81%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 7         | 0.81%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 6         | 0.7%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 6         | 0.7%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 6         | 0.7%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 6         | 0.7%    |
| Intel Core i5-3230M CPU @ 2.60GHz             | 6         | 0.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 219       | 25.38%  |
| Intel Core i3           | 125       | 14.48%  |
| Intel Core i7           | 110       | 12.75%  |
| Intel Celeron           | 75        | 8.69%   |
| Other                   | 69        | 8%      |
| AMD Ryzen 5             | 52        | 6.03%   |
| Intel Core 2 Duo        | 28        | 3.24%   |
| AMD Ryzen 3             | 26        | 3.01%   |
| AMD A8                  | 22        | 2.55%   |
| AMD Ryzen 7             | 17        | 1.97%   |
| Intel Pentium           | 16        | 1.85%   |
| AMD A4                  | 13        | 1.51%   |
| Intel Atom              | 11        | 1.27%   |
| AMD E1                  | 9         | 1.04%   |
| AMD E                   | 8         | 0.93%   |
| AMD E2                  | 7         | 0.81%   |
| AMD A6                  | 7         | 0.81%   |
| Intel Pentium Dual-Core | 6         | 0.7%    |
| AMD Athlon              | 6         | 0.7%    |
| Intel Pentium Dual      | 5         | 0.58%   |
| Intel Genuine           | 5         | 0.58%   |
| AMD A10                 | 5         | 0.58%   |
| AMD Ryzen 9             | 4         | 0.46%   |
| Intel Core 2            | 3         | 0.35%   |
| AMD FX                  | 3         | 0.35%   |
| AMD C-60                | 3         | 0.35%   |
| Intel Xeon              | 2         | 0.23%   |
| AMD Ryzen 5 PRO         | 2         | 0.23%   |
| AMD A12                 | 2         | 0.23%   |
| AMD Turion 64 Mobile    | 1         | 0.12%   |
| AMD PRO A10             | 1         | 0.12%   |
| AMD C-50                | 1         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 563       | 65.24%  |
| 4      | 208       | 24.1%   |
| 6      | 54        | 6.26%   |
| 8      | 19        | 2.2%    |
| 1      | 9         | 1.04%   |
| 12     | 6         | 0.7%    |
| 14     | 2         | 0.23%   |
| 10     | 2         | 0.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 862       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 610       | 70.77%  |
| 1      | 252       | 29.23%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 848       | 98.38%  |
| Unknown        | 11        | 1.28%   |
| 32-bit         | 3         | 0.35%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 174       | 19.38%  |
| 0x206a7    | 68        | 7.57%   |
| 0x306a9    | 53        | 5.9%    |
| 0x40651    | 41        | 4.57%   |
| 0x306d4    | 34        | 3.79%   |
| 0x806ea    | 28        | 3.12%   |
| 0x06006705 | 27        | 3.01%   |
| 0x406e3    | 25        | 2.78%   |
| 0x806e9    | 24        | 2.67%   |
| 0x806ec    | 23        | 2.56%   |
| 0x20655    | 23        | 2.56%   |
| 0x806c1    | 21        | 2.34%   |
| 0x08108109 | 21        | 2.34%   |
| 0x1067a    | 20        | 2.23%   |
| 0x906ea    | 18        | 2%      |
| 0x806eb    | 15        | 1.67%   |
| 0x0a50000c | 15        | 1.67%   |
| 0x08108102 | 14        | 1.56%   |
| 0x07030105 | 14        | 1.56%   |
| 0x706e5    | 13        | 1.45%   |
| 0x30678    | 13        | 1.45%   |
| 0x6fd      | 11        | 1.22%   |
| 0x306c3    | 11        | 1.22%   |
| 0x08608103 | 10        | 1.11%   |
| 0x706a8    | 9         | 1%      |
| 0x20652    | 9         | 1%      |
| 0x406c4    | 8         | 0.89%   |
| 0x406c3    | 8         | 0.89%   |
| 0x08600104 | 8         | 0.89%   |
| 0x906e9    | 7         | 0.78%   |
| 0x06001119 | 7         | 0.78%   |
| 0x05000119 | 7         | 0.78%   |
| 0x906a3    | 6         | 0.67%   |
| 0x10676    | 6         | 0.67%   |
| 0x0810100b | 6         | 0.67%   |
| 0x0700010f | 6         | 0.67%   |
| 0x03000027 | 6         | 0.67%   |
| 0x506e3    | 5         | 0.56%   |
| 0x06006704 | 5         | 0.56%   |
| 0x0600611a | 5         | 0.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 144       | 16.69%  |
| SandyBridge      | 80        | 9.27%   |
| IvyBridge        | 65        | 7.53%   |
| Haswell          | 62        | 7.18%   |
| Excavator        | 44        | 5.1%    |
| Westmere         | 42        | 4.87%   |
| Broadwell        | 39        | 4.52%   |
| Zen+             | 38        | 4.4%    |
| Silvermont       | 38        | 4.4%    |
| Skylake          | 37        | 4.29%   |
| Penryn           | 28        | 3.24%   |
| TigerLake        | 26        | 3.01%   |
| Puma             | 24        | 2.78%   |
| Unknown          | 22        | 2.55%   |
| Zen 3            | 20        | 2.32%   |
| IceLake          | 19        | 2.2%    |
| Zen 2            | 18        | 2.09%   |
| Core             | 17        | 1.97%   |
| Goldmont plus    | 16        | 1.85%   |
| Bobcat           | 15        | 1.74%   |
| Zen              | 13        | 1.51%   |
| Alderlake Hybrid | 10        | 1.16%   |
| Piledriver       | 8         | 0.93%   |
| Jaguar           | 8         | 0.93%   |
| Goldmont         | 7         | 0.81%   |
| K10 Llano        | 6         | 0.7%    |
| CometLake        | 6         | 0.7%    |
| Bonnell          | 5         | 0.58%   |
| Steamroller      | 2         | 0.23%   |
| P6               | 2         | 0.23%   |
| Tremont          | 1         | 0.12%   |
| K8 Hammer        | 1         | 0.12%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 624       | 55.86%  |
| AMD                              | 267       | 23.9%   |
| Nvidia                           | 221       | 19.79%  |
| Silicon Integrated Systems [SiS] | 4         | 0.36%   |
| Silicon Motion                   | 1         | 0.09%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 77        | 6.56%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 63        | 5.37%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 48        | 4.09%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 39        | 3.32%   |
| Intel Core Processor Integrated Graphics Controller                                      | 36        | 3.07%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 36        | 3.07%   |
| Intel HD Graphics 5500                                                                   | 34        | 2.9%    |
| Intel UHD Graphics 620                                                                   | 32        | 2.73%   |
| Intel HD Graphics 620                                                                    | 31        | 2.64%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 28        | 2.39%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 27        | 2.3%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 24        | 2.04%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 21        | 1.79%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 20        | 1.7%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 20        | 1.7%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 20        | 1.7%    |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 20        | 1.7%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 20        | 1.7%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 19        | 1.62%   |
| AMD Renoir                                                                               | 18        | 1.53%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 17        | 1.45%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 17        | 1.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 17        | 1.45%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 16        | 1.36%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 14        | 1.19%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 14        | 1.19%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 13        | 1.11%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 13        | 1.11%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 13        | 1.11%   |
| AMD Lucienne                                                                             | 13        | 1.11%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 12        | 1.02%   |
| Nvidia GP108M [GeForce MX150]                                                            | 10        | 0.85%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 10        | 0.85%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 9         | 0.77%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 9         | 0.77%   |
| Nvidia GP108M [GeForce MX250]                                                            | 8         | 0.68%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 8         | 0.68%   |
| Intel HD Graphics 630                                                                    | 8         | 0.68%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 8         | 0.68%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 8         | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 394       | 45.44%  |
| Intel + Nvidia     | 185       | 21.34%  |
| 1 x AMD            | 161       | 18.57%  |
| Intel + AMD        | 44        | 5.07%   |
| 2 x AMD            | 36        | 4.15%   |
| AMD + Nvidia       | 26        | 3%      |
| 1 x Nvidia         | 8         | 0.92%   |
| 2 x Intel          | 5         | 0.58%   |
| 1 x SiS            | 4         | 0.46%   |
| 2 x Nvidia         | 2         | 0.23%   |
| Other              | 1         | 0.12%   |
| 1 x Silicon Motion | 1         | 0.12%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 747       | 85.57%  |
| Proprietary | 111       | 12.71%  |
| Unknown     | 15        | 1.72%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 532       | 59.78%  |
| 1.01-2.0   | 148       | 16.63%  |
| 0.01-0.5   | 112       | 12.58%  |
| 0.51-1.0   | 46        | 5.17%   |
| 3.01-4.0   | 40        | 4.49%   |
| 5.01-6.0   | 8         | 0.9%    |
| 7.01-8.0   | 3         | 0.34%   |
| 2.01-3.0   | 1         | 0.11%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 196       | 21.28%  |
| Chimei Innolux          | 177       | 19.22%  |
| BOE                     | 147       | 15.96%  |
| LG Display              | 126       | 13.68%  |
| Samsung Electronics     | 75        | 8.14%   |
| Goldstar                | 34        | 3.69%   |
| Lenovo                  | 19        | 2.06%   |
| PANDA                   | 15        | 1.63%   |
| Sharp                   | 12        | 1.3%    |
| InfoVision              | 12        | 1.3%    |
| Apple                   | 12        | 1.3%    |
| Chi Mei Optoelectronics | 10        | 1.09%   |
| InnoLux Display         | 8         | 0.87%   |
| Dell                    | 6         | 0.65%   |
| Acer                    | 6         | 0.65%   |
| ViewSonic               | 5         | 0.54%   |
| Philips                 | 5         | 0.54%   |
| LG Philips              | 5         | 0.54%   |
| AOC                     | 5         | 0.54%   |
| Toshiba                 | 4         | 0.43%   |
| KDC                     | 4         | 0.43%   |
| CPT                     | 4         | 0.43%   |
| Sony                    | 3         | 0.33%   |
| Quanta Display          | 3         | 0.33%   |
| Hewlett-Packard         | 3         | 0.33%   |
| HannStar                | 3         | 0.33%   |
| Seiko/Epson             | 2         | 0.22%   |
| Panasonic               | 2         | 0.22%   |
| HKC                     | 2         | 0.22%   |
| HJC                     | 2         | 0.22%   |
| BenQ                    | 2         | 0.22%   |
| WST                     | 1         | 0.11%   |
| Valve                   | 1         | 0.11%   |
| TMX                     | 1         | 0.11%   |
| SPC                     | 1         | 0.11%   |
| Mi                      | 1         | 0.11%   |
| JDI                     | 1         | 0.11%   |
| Hitachi                 | 1         | 0.11%   |
| HIC                     | 1         | 0.11%   |
| Gateway                 | 1         | 0.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch       | 20        | 2.16%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch         | 17        | 1.84%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 16        | 1.73%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch       | 16        | 1.73%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 12        | 1.3%    |
| BOE LCD Monitor BOE06BD 1366x768 309x173mm 13.9-inch                  | 11        | 1.19%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                  | 11        | 1.19%   |
| AU Optronics LCD Monitor AUO323C 1366x768 309x173mm 13.9-inch         | 11        | 1.19%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 11        | 1.19%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 10        | 1.08%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch       | 10        | 1.08%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch         | 10        | 1.08%   |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                 | 9         | 0.97%   |
| BOE LCD Monitor BOE0698 1366x768 309x173mm 13.9-inch                  | 9         | 0.97%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 8         | 0.86%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch           | 7         | 0.76%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 7         | 0.76%   |
| Chimei Innolux LCD Monitor CMN1487 1366x768 309x173mm 13.9-inch       | 7         | 0.76%   |
| Chimei Innolux LCD Monitor CMN1480 1366x768 309x174mm 14.0-inch       | 7         | 0.76%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch           | 6         | 0.65%   |
| LG Display LCD Monitor LGD018B 1366x768 309x174mm 14.0-inch           | 6         | 0.65%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 6         | 0.65%   |
| Chimei Innolux LCD Monitor CMN1491 1366x768 309x174mm 14.0-inch       | 6         | 0.65%   |
| BOE LCD Monitor BOE07B5 1366x768 309x173mm 13.9-inch                  | 6         | 0.65%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                  | 6         | 0.65%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 6         | 0.65%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch         | 6         | 0.65%   |
| Samsung Electronics LCD Monitor SEC3050 1366x768 309x174mm 14.0-inch  | 5         | 0.54%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 5         | 0.54%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch           | 5         | 0.54%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                      | 5         | 0.54%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 5         | 0.54%   |
| Chimei Innolux LCD Monitor CMN14A7 1920x1080 308x173mm 13.9-inch      | 5         | 0.54%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                 | 5         | 0.54%   |
| Samsung Electronics LCD Monitor SEC3849 1366x768 309x174mm 14.0-inch  | 4         | 0.43%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 4         | 0.43%   |
| LG Display LCD Monitor LGD06B9 1920x1200 286x179mm 13.3-inch          | 4         | 0.43%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch          | 4         | 0.43%   |
| LG Display LCD Monitor LGD04C0 1366x768 309x174mm 14.0-inch           | 4         | 0.43%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch           | 4         | 0.43%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 485       | 54.8%   |
| 1920x1080 (FHD)   | 271       | 30.62%  |
| 1280x800 (WXGA)   | 25        | 2.82%   |
| 1600x900 (HD+)    | 20        | 2.26%   |
| 3840x2160 (4K)    | 13        | 1.47%   |
| 2560x1440 (QHD)   | 11        | 1.24%   |
| 1920x1200 (WUXGA) | 11        | 1.24%   |
| 1440x900 (WXGA+)  | 10        | 1.13%   |
| 2560x1600         | 9         | 1.02%   |
| 2880x1800         | 7         | 0.79%   |
| 1360x768          | 7         | 0.79%   |
| 1024x600          | 4         | 0.45%   |
| 3840x2400         | 2         | 0.23%   |
| 2560x1080         | 2         | 0.23%   |
| 800x1280          | 1         | 0.11%   |
| 3440x1440         | 1         | 0.11%   |
| 3200x1800 (QHD+)  | 1         | 0.11%   |
| 2966x900          | 1         | 0.11%   |
| 2736x1824         | 1         | 0.11%   |
| 2240x1400         | 1         | 0.11%   |
| 1024x768 (XGA)    | 1         | 0.11%   |
| Unknown           | 1         | 0.11%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 13      | 274       | 29.75%  |
| 14      | 270       | 29.32%  |
| 15      | 183       | 19.87%  |
| 12      | 41        | 4.45%   |
| 11      | 31        | 3.37%   |
| 23      | 29        | 3.15%   |
| 18      | 22        | 2.39%   |
| 21      | 11        | 1.19%   |
| 24      | 9         | 0.98%   |
| 17      | 9         | 0.98%   |
| 19      | 8         | 0.87%   |
| 40      | 6         | 0.65%   |
| 10      | 4         | 0.43%   |
| 34      | 3         | 0.33%   |
| 27      | 3         | 0.33%   |
| 16      | 3         | 0.33%   |
| Unknown | 3         | 0.33%   |
| 48      | 2         | 0.22%   |
| 31      | 2         | 0.22%   |
| 72      | 1         | 0.11%   |
| 60      | 1         | 0.11%   |
| 54      | 1         | 0.11%   |
| 52      | 1         | 0.11%   |
| 26      | 1         | 0.11%   |
| 20      | 1         | 0.11%   |
| 9       | 1         | 0.11%   |
| 7       | 1         | 0.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 664       | 72.65%  |
| 201-300     | 129       | 14.11%  |
| 501-600     | 41        | 4.49%   |
| 401-500     | 41        | 4.49%   |
| 351-400     | 17        | 1.86%   |
| 801-900     | 6         | 0.66%   |
| 1001-1500   | 5         | 0.55%   |
| 701-800     | 3         | 0.33%   |
| 601-700     | 3         | 0.33%   |
| Unknown     | 3         | 0.33%   |
| 1501-2000   | 1         | 0.11%   |
| 1-100       | 1         | 0.11%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 764       | 90.95%  |
| 16/10   | 64        | 7.62%   |
| 3/2     | 3         | 0.36%   |
| 21/9    | 3         | 0.36%   |
| Unknown | 3         | 0.36%   |
| 4/3     | 2         | 0.24%   |
| 0.67    | 1         | 0.12%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 496       | 53.91%  |
| 101-110        | 181       | 19.67%  |
| 201-250        | 49        | 5.33%   |
| 71-80          | 43        | 4.67%   |
| 61-70          | 40        | 4.35%   |
| 51-60          | 31        | 3.37%   |
| 141-150        | 22        | 2.39%   |
| 151-200        | 9         | 0.98%   |
| 121-130        | 7         | 0.76%   |
| More than 1000 | 6         | 0.65%   |
| 501-1000       | 6         | 0.65%   |
| 91-100         | 6         | 0.65%   |
| 351-500        | 5         | 0.54%   |
| 41-50          | 5         | 0.54%   |
| 301-350        | 4         | 0.43%   |
| 111-120        | 4         | 0.43%   |
| Unknown        | 3         | 0.33%   |
| 131-140        | 2         | 0.22%   |
| 1-40           | 1         | 0.11%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 434       | 47.59%  |
| 121-160       | 302       | 33.11%  |
| 51-100        | 100       | 10.96%  |
| 161-240       | 46        | 5.04%   |
| More than 240 | 18        | 1.97%   |
| 1-50          | 9         | 0.99%   |
| Unknown       | 3         | 0.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 765       | 86.73%  |
| 2     | 94        | 10.66%  |
| 0     | 20        | 2.27%   |
| 3     | 3         | 0.34%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 529       | 37.76%  |
| Intel                             | 315       | 22.48%  |
| Qualcomm Atheros                  | 300       | 21.41%  |
| Broadcom                          | 91        | 6.5%    |
| MediaTek                          | 31        | 2.21%   |
| Broadcom Limited                  | 16        | 1.14%   |
| Xiaomi                            | 14        | 1%      |
| Samsung Electronics               | 11        | 0.79%   |
| Ralink Technology                 | 11        | 0.79%   |
| Marvell Technology Group          | 11        | 0.79%   |
| TP-Link                           | 10        | 0.71%   |
| OPPO Electronics                  | 8         | 0.57%   |
| Ralink                            | 7         | 0.5%    |
| Qualcomm Atheros Communications   | 7         | 0.5%    |
| JMicron Technology                | 6         | 0.43%   |
| Huawei Technologies               | 4         | 0.29%   |
| Ericsson Business Mobile Networks | 4         | 0.29%   |
| ASIX Electronics                  | 4         | 0.29%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.21%   |
| Attansic Technology               | 3         | 0.21%   |
| Sierra Wireless                   | 2         | 0.14%   |
| Qualcomm                          | 2         | 0.14%   |
| Nvidia                            | 2         | 0.14%   |
| ICS Advent                        | 2         | 0.14%   |
| Hewlett-Packard                   | 2         | 0.14%   |
| Lenovo                            | 1         | 0.07%   |
| HTC (High Tech Computer)          | 1         | 0.07%   |
| Foxconn / Hon Hai                 | 1         | 0.07%   |
| D-Link                            | 1         | 0.07%   |
| ASUSTek Computer                  | 1         | 0.07%   |
| AboCom Systems                    | 1         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 328       | 19.81%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 115       | 6.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 78        | 4.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 64        | 3.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 51        | 3.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 35        | 2.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 31        | 1.87%   |
| Intel Wireless 8265 / 8275                                        | 30        | 1.81%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 27        | 1.63%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 25        | 1.51%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 23        | 1.39%   |
| Intel Wireless 7265                                               | 23        | 1.39%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 23        | 1.39%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 22        | 1.33%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 21        | 1.27%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 20        | 1.21%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 20        | 1.21%   |
| Intel Wireless 7260                                               | 19        | 1.15%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 18        | 1.09%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 17        | 1.03%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 17        | 1.03%   |
| Broadcom BCM43142 802.11b/g/n                                     | 17        | 1.03%   |
| Intel Wi-Fi 6 AX200                                               | 16        | 0.97%   |
| Intel Wireless 8260                                               | 15        | 0.91%   |
| Intel Wi-Fi 6 AX201                                               | 15        | 0.91%   |
| Intel Ethernet Connection I218-LM                                 | 13        | 0.79%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 13        | 0.79%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 12        | 0.72%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 11        | 0.66%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 11        | 0.66%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 11        | 0.66%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 11        | 0.66%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 11        | 0.66%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 11        | 0.66%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 10        | 0.6%    |
| Intel Ethernet Connection (3) I218-LM                             | 10        | 0.6%    |
| Ralink MT7601U Wireless Adapter                                   | 9         | 0.54%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 9         | 0.54%   |
| Realtek 802.11n WLAN Adapter                                      | 8         | 0.48%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 8         | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 292       | 32.81%  |
| Qualcomm Atheros                  | 273       | 30.67%  |
| Realtek Semiconductor             | 182       | 20.45%  |
| Broadcom                          | 70        | 7.87%   |
| MediaTek                          | 24        | 2.7%    |
| Broadcom Limited                  | 12        | 1.35%   |
| Ralink Technology                 | 11        | 1.24%   |
| TP-Link                           | 7         | 0.79%   |
| Ralink                            | 7         | 0.79%   |
| Qualcomm Atheros Communications   | 7         | 0.79%   |
| Sierra Wireless                   | 2         | 0.22%   |
| Ericsson Business Mobile Networks | 1         | 0.11%   |
| D-Link                            | 1         | 0.11%   |
| AboCom Systems                    | 1         | 0.11%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 78        | 8.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 64        | 7.14%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 51        | 5.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 35        | 3.91%   |
| Intel Wireless 8265 / 8275                                     | 30        | 3.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 27        | 3.01%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 25        | 2.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 23        | 2.57%   |
| Intel Wireless 7265                                            | 23        | 2.57%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 23        | 2.57%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 22        | 2.46%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 21        | 2.34%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 20        | 2.23%   |
| Intel Wireless 7260                                            | 19        | 2.12%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 18        | 2.01%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 17        | 1.9%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 17        | 1.9%    |
| Broadcom BCM43142 802.11b/g/n                                  | 17        | 1.9%    |
| Intel Wi-Fi 6 AX200                                            | 16        | 1.79%   |
| Intel Wireless 8260                                            | 15        | 1.67%   |
| Intel Wi-Fi 6 AX201                                            | 15        | 1.67%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 13        | 1.45%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 11        | 1.23%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 11        | 1.23%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 11        | 1.23%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 11        | 1.23%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 10        | 1.12%   |
| Ralink MT7601U Wireless Adapter                                | 9         | 1%      |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 9         | 1%      |
| Realtek 802.11n WLAN Adapter                                   | 8         | 0.89%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 8         | 0.89%   |
| Intel Wireless 3165                                            | 8         | 0.89%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 8         | 0.89%   |
| Qualcomm Atheros AR9271 802.11n                                | 7         | 0.78%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 6         | 0.67%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 6         | 0.67%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 6         | 0.67%   |
| Intel Centrino Advanced-N 6235                                 | 6         | 0.67%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 6         | 0.67%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 6         | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 457       | 60.77%  |
| Intel                            | 111       | 14.76%  |
| Qualcomm Atheros                 | 64        | 8.51%   |
| Broadcom                         | 31        | 4.12%   |
| Xiaomi                           | 14        | 1.86%   |
| Samsung Electronics              | 11        | 1.46%   |
| Marvell Technology Group         | 11        | 1.46%   |
| OPPO Electronics                 | 8         | 1.06%   |
| MediaTek                         | 7         | 0.93%   |
| JMicron Technology               | 6         | 0.8%    |
| Broadcom Limited                 | 6         | 0.8%    |
| ASIX Electronics                 | 4         | 0.53%   |
| TP-Link                          | 3         | 0.4%    |
| Silicon Integrated Systems [SiS] | 3         | 0.4%    |
| Attansic Technology              | 3         | 0.4%    |
| Qualcomm                         | 2         | 0.27%   |
| Nvidia                           | 2         | 0.27%   |
| ICS Advent                       | 2         | 0.27%   |
| Hewlett-Packard                  | 2         | 0.27%   |
| Lenovo                           | 1         | 0.13%   |
| Huawei Technologies              | 1         | 0.13%   |
| HTC (High Tech Computer)         | 1         | 0.13%   |
| Foxconn / Hon Hai                | 1         | 0.13%   |
| ASUSTek Computer                 | 1         | 0.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 328       | 43.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 115       | 15.25%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 31        | 4.11%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 20        | 2.65%   |
| Intel Ethernet Connection I218-LM                                 | 13        | 1.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 12        | 1.59%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 11        | 1.46%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 11        | 1.46%   |
| Intel Ethernet Connection (3) I218-LM                             | 10        | 1.33%   |
| OPPO OnePlus Nord                                                 | 8         | 1.06%   |
| Intel Ethernet Connection I219-LM                                 | 8         | 1.06%   |
| Intel 82577LM Gigabit Network Connection                          | 8         | 1.06%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 7         | 0.93%   |
| Intel Ethernet Connection (4) I219-LM                             | 7         | 0.93%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 6         | 0.8%    |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 6         | 0.8%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 6         | 0.8%    |
| Intel Ethernet Connection I217-LM                                 | 6         | 0.8%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 5         | 0.66%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 5         | 0.66%   |
| MediaTek moto g22                                                 | 5         | 0.66%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 5         | 0.66%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 4         | 0.53%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 4         | 0.53%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 4         | 0.53%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 4         | 0.53%   |
| Intel Ethernet Connection I219-V                                  | 4         | 0.53%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 0.53%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 4         | 0.53%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 3         | 0.4%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 3         | 0.4%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 0.4%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 0.4%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.4%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 3         | 0.4%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 3         | 0.4%    |
| Intel 82579V Gigabit Network Connection                           | 3         | 0.4%    |
| Intel 82567LM Gigabit Network Connection                          | 3         | 0.4%    |
| Attansic AR8152 v2.0 Fast Ethernet                                | 3         | 0.4%    |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 848       | 54.29%  |
| Ethernet | 708       | 45.33%  |
| Modem    | 6         | 0.38%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 740       | 86.65%  |
| Ethernet | 113       | 13.23%  |
| Modem    | 1         | 0.12%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 659       | 76.27%  |
| 1     | 188       | 21.76%  |
| 0     | 14        | 1.62%   |
| 3     | 3         | 0.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 804       | 91.99%  |
| Yes  | 70        | 8.01%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 223       | 32.94%  |
| Realtek Semiconductor           | 116       | 17.13%  |
| IMC Networks                    | 74        | 10.93%  |
| Qualcomm Atheros Communications | 70        | 10.34%  |
| Lite-On Technology              | 58        | 8.57%   |
| Broadcom                        | 41        | 6.06%   |
| Foxconn / Hon Hai               | 30        | 4.43%   |
| Toshiba                         | 11        | 1.62%   |
| Cambridge Silicon Radio         | 10        | 1.48%   |
| Apple                           | 10        | 1.48%   |
| Dell                            | 8         | 1.18%   |
| Ralink                          | 5         | 0.74%   |
| Hewlett-Packard                 | 5         | 0.74%   |
| Foxconn International           | 4         | 0.59%   |
| Realtek                         | 3         | 0.44%   |
| ASUSTek Computer                | 3         | 0.44%   |
| Micro Star International        | 2         | 0.3%    |
| MediaTek                        | 2         | 0.3%    |
| Chicony Electronics             | 1         | 0.15%   |
| Alps Electric                   | 1         | 0.15%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 91        | 13.44%  |
| Realtek Bluetooth Radio                             | 69        | 10.19%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 60        | 8.86%   |
| IMC Networks Bluetooth Device                       | 45        | 6.65%   |
| Qualcomm Atheros  Bluetooth Device                  | 33        | 4.87%   |
| Realtek  Bluetooth 4.2 Adapter                      | 30        | 4.43%   |
| Intel AX201 Bluetooth                               | 28        | 4.14%   |
| Lite-On Bluetooth Device                            | 21        | 3.1%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 16        | 2.36%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 16        | 2.36%   |
| Intel AX200 Bluetooth                               | 16        | 2.36%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 14        | 2.07%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 11        | 1.62%   |
| Intel Bluetooth Device                              | 11        | 1.62%   |
| Realtek RTL8821A Bluetooth                          | 10        | 1.48%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 10        | 1.48%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 10        | 1.48%   |
| Lite-On Wireless_Device                             | 9         | 1.33%   |
| IMC Networks Bluetooth Radio                        | 9         | 1.33%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 8         | 1.18%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 7         | 1.03%   |
| Lite-On Atheros Bluetooth                           | 6         | 0.89%   |
| Lite-On Atheros AR3012 Bluetooth                    | 6         | 0.89%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 6         | 0.89%   |
| Apple Bluetooth Host Controller                     | 6         | 0.89%   |
| Ralink RT3290 Bluetooth                             | 5         | 0.74%   |
| IMC Networks Wireless_Device                        | 5         | 0.74%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 5         | 0.74%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 5         | 0.74%   |
| Toshiba RT Bluetooth Radio                          | 4         | 0.59%   |
| HP Broadcom 2070 Bluetooth Combo                    | 4         | 0.59%   |
| Foxconn International BCM43142A0 Bluetooth module   | 4         | 0.59%   |
| Foxconn / Hon Hai Bluetooth Device                  | 4         | 0.59%   |
| Broadcom BCM43142A0 Bluetooth Device                | 4         | 0.59%   |
| Broadcom BCM20702A0                                 | 4         | 0.59%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 4         | 0.59%   |
| Toshiba Integrated Bluetooth HCI                    | 3         | 0.44%   |
| Qualcomm Atheros Bluetooth                          | 3         | 0.44%   |
| Intel AX210 Bluetooth                               | 3         | 0.44%   |
| Foxconn / Hon Hai BCM20702A0                        | 3         | 0.44%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 632       | 66.6%   |
| AMD                              | 221       | 23.29%  |
| Nvidia                           | 71        | 7.48%   |
| Silicon Integrated Systems [SiS] | 4         | 0.42%   |
| Samson Technologies              | 3         | 0.32%   |
| JMTek                            | 3         | 0.32%   |
| Generalplus Technology           | 3         | 0.32%   |
| Samsung Electronics              | 2         | 0.21%   |
| C-Media Electronics              | 2         | 0.21%   |
| SAVITECH                         | 1         | 0.11%   |
| Logitech                         | 1         | 0.11%   |
| Jieli Technology                 | 1         | 0.11%   |
| FDUCE PRO AUDIO MADE             | 1         | 0.11%   |
| Cooler Master                    | 1         | 0.11%   |
| Conexant Systems                 | 1         | 0.11%   |
| Barco Display Systems            | 1         | 0.11%   |
| ASUSTek Computer                 | 1         | 0.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 107       | 8.54%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 96        | 7.66%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 84        | 6.7%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 59        | 4.71%   |
| AMD FCH Azalia Controller                                                                         | 54        | 4.31%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 48        | 3.83%   |
| Intel 8 Series HD Audio Controller                                                                | 48        | 3.83%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 46        | 3.67%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 44        | 3.51%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 44        | 3.51%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 42        | 3.35%   |
| AMD Kabini HDMI/DP Audio                                                                          | 40        | 3.19%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 39        | 3.11%   |
| Intel Broadwell-U Audio Controller                                                                | 39        | 3.11%   |
| AMD High Definition Audio Controller                                                              | 36        | 2.87%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 30        | 2.39%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 26        | 2.08%   |
| Intel Cannon Lake PCH cAVS                                                                        | 24        | 1.92%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 22        | 1.76%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 20        | 1.6%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 18        | 1.44%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 16        | 1.28%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 15        | 1.2%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 14        | 1.12%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 14        | 1.12%   |
| AMD Wrestler HDMI Audio                                                                           | 14        | 1.12%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 13        | 1.04%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 12        | 0.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 12        | 0.96%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 11        | 0.88%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 10        | 0.8%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 10        | 0.8%    |
| Intel CM238 HD Audio Controller                                                                   | 9         | 0.72%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 9         | 0.72%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 9         | 0.72%   |
| AMD Trinity HDMI Audio Controller                                                                 | 8         | 0.64%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 7         | 0.56%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 7         | 0.56%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 6         | 0.48%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 6         | 0.48%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 206       | 30.7%   |
| SK hynix            | 133       | 19.82%  |
| Micron Technology   | 80        | 11.92%  |
| Kingston            | 55        | 8.2%    |
| Unknown             | 43        | 6.41%   |
| Corsair             | 22        | 3.28%   |
| Team                | 21        | 3.13%   |
| V-GeN               | 20        | 2.98%   |
| Ramaxel Technology  | 18        | 2.68%   |
| Elpida              | 12        | 1.79%   |
| Nanya Technology    | 11        | 1.64%   |
| Unknown (ABCD)      | 10        | 1.49%   |
| A-DATA Technology   | 8         | 1.19%   |
| Apacer              | 4         | 0.6%    |
| Transcend           | 3         | 0.45%   |
| Unknown             | 3         | 0.45%   |
| Visipro             | 2         | 0.3%    |
| Lexar               | 2         | 0.3%    |
| Crucial             | 2         | 0.3%    |
| ASint Technology    | 2         | 0.3%    |
| A Force             | 2         | 0.3%    |
| Unknown (8A02)      | 1         | 0.15%   |
| Strontium           | 1         | 0.15%   |
| Silicon Power       | 1         | 0.15%   |
| SHARETRONIC         | 1         | 0.15%   |
| Qumo                | 1         | 0.15%   |
| Patriot             | 1         | 0.15%   |
| Kingmax             | 1         | 0.15%   |
| GOODRAM             | 1         | 0.15%   |
| Goldkey             | 1         | 0.15%   |
| Foxline             | 1         | 0.15%   |
| ff                  | 1         | 0.15%   |
| 4ea5                | 1         | 0.15%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 14        | 1.93%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 14        | 1.93%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 12        | 1.66%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 12        | 1.66%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 11        | 1.52%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 10        | 1.38%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 9         | 1.24%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 9         | 1.24%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 8         | 1.1%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 1.1%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 1.1%    |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s            | 8         | 1.1%    |
| Team RAM TEAMGROUP-SD4-2400 8GB SODIMM DDR4 8400MT/s             | 7         | 0.97%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 7         | 0.97%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 7         | 0.97%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 7         | 0.97%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 7         | 0.97%   |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s            | 6         | 0.83%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 0.83%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 0.83%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.83%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 6         | 0.83%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.69%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 0.69%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 5         | 0.69%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.69%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.69%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 5         | 0.69%   |
| Nanya RAM NT2GC64B88G0NS-CG 2GB SODIMM DDR3 1600MT/s             | 5         | 0.69%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 5         | 0.69%   |
| Kingston RAM 9905625-004.A03LF 16GB SODIMM DDR4 3200MT/s         | 5         | 0.69%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.55%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 0.55%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 4         | 0.55%   |
| Samsung RAM M471B5674QH0-YK0 2048MB SODIMM DDR3 1600MT/s         | 4         | 0.55%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 0.55%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s            | 4         | 0.55%   |
| Samsung RAM M471A5143EB1-CRC 4GB SODIMM DDR4 2400MT/s            | 4         | 0.55%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.55%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s             | 4         | 0.55%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 230       | 44.66%  |
| DDR3    | 220       | 42.72%  |
| LPDDR4  | 26        | 5.05%   |
| DDR2    | 14        | 2.72%   |
| SDRAM   | 8         | 1.55%   |
| LPDDR5  | 7         | 1.36%   |
| LPDDR3  | 7         | 1.36%   |
| Unknown | 2         | 0.39%   |
| DRAM    | 1         | 0.19%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 479       | 91.76%  |
| Row Of Chips | 36        | 6.9%    |
| Chip         | 5         | 0.96%   |
| Unknown      | 2         | 0.38%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 245       | 41.18%  |
| 8192  | 204       | 34.29%  |
| 2048  | 81        | 13.61%  |
| 16384 | 42        | 7.06%   |
| 32768 | 12        | 2.02%   |
| 1024  | 10        | 1.68%   |
| 512   | 1         | 0.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 160       | 26.67%  |
| 2667    | 110       | 18.33%  |
| 3200    | 88        | 14.67%  |
| 2400    | 58        | 9.67%   |
| 1334    | 30        | 5%      |
| 2133    | 28        | 4.67%   |
| 1333    | 24        | 4%      |
| 1067    | 16        | 2.67%   |
| 3266    | 14        | 2.33%   |
| Unknown | 9         | 1.5%    |
| 800     | 8         | 1.33%   |
| 8400    | 7         | 1.17%   |
| 4266    | 7         | 1.17%   |
| 6400    | 6         | 1%      |
| 667     | 6         | 1%      |
| 4267    | 5         | 0.83%   |
| 4199    | 5         | 0.83%   |
| 1867    | 5         | 0.83%   |
| 1066    | 3         | 0.5%    |
| 533     | 3         | 0.5%    |
| 2048    | 2         | 0.33%   |
| 5500    | 1         | 0.17%   |
| 3333    | 1         | 0.17%   |
| 1866    | 1         | 0.17%   |
| 1776    | 1         | 0.17%   |
| 975     | 1         | 0.17%   |
| 333     | 1         | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Seiko Epson        | 8         | 57.14%  |
| Canon              | 3         | 21.43%  |
| Brother Industries | 2         | 14.29%  |
| STMicroelectronics | 1         | 7.14%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Seiko Epson L360 Series                 | 2         | 14.29%  |
| Seiko Epson L310 Series                 | 2         | 14.29%  |
| Canon iP2700 series                     | 2         | 14.29%  |
| Brother DCP-T300                        | 2         | 14.29%  |
| STMicroelectronics USB Printing Support | 1         | 7.14%   |
| Seiko Epson L405 Series                 | 1         | 7.14%   |
| Seiko Epson L355 Series                 | 1         | 7.14%   |
| Seiko Epson L3210 Series                | 1         | 7.14%   |
| Seiko Epson L120 Series                 | 1         | 7.14%   |
| Canon CanoScan LiDE 300                 | 1         | 7.14%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Canon CanoScan 4400F | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 217       | 28.22%  |
| IMC Networks                           | 110       | 14.3%   |
| Realtek Semiconductor                  | 68        | 8.84%   |
| Bison Electronics                      | 60        | 7.8%    |
| Sunplus Innovation Technology          | 44        | 5.72%   |
| Quanta                                 | 41        | 5.33%   |
| Syntek                                 | 35        | 4.55%   |
| Cheng Uei Precision Industry (Foxlink) | 34        | 4.42%   |
| Microdia                               | 31        | 4.03%   |
| Alcor Micro                            | 24        | 3.12%   |
| Suyin                                  | 23        | 2.99%   |
| Lite-On Technology                     | 10        | 1.3%    |
| Acer                                   | 10        | 1.3%    |
| Luxvisions Innotech Limited            | 8         | 1.04%   |
| Apple                                  | 8         | 1.04%   |
| Ricoh                                  | 6         | 0.78%   |
| Importek                               | 6         | 0.78%   |
| Silicon Motion                         | 5         | 0.65%   |
| Sonix Technology                       | 4         | 0.52%   |
| Primax Electronics                     | 3         | 0.39%   |
| Lenovo                                 | 3         | 0.39%   |
| Sunplus Technology                     | 2         | 0.26%   |
| Jieli Technology                       | 2         | 0.26%   |
| ALi                                    | 2         | 0.26%   |
| Unknown                                | 2         | 0.26%   |
| Tripath Technology                     | 1         | 0.13%   |
| Pixart Imaging                         | 1         | 0.13%   |
| OPPO Electronics                       | 1         | 0.13%   |
| Omnivision                             | 1         | 0.13%   |
| Logitech                               | 1         | 0.13%   |
| Huawei Technologies                    | 1         | 0.13%   |
| Genesys Logic                          | 1         | 0.13%   |
| GEMBIRD                                | 1         | 0.13%   |
| eMPIA Technology                       | 1         | 0.13%   |
| DigiTech                               | 1         | 0.13%   |
| 2M UVC CAMERA                          | 1         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                               | 34        | 4.41%   |
| Chicony HD WebCam                                               | 32        | 4.15%   |
| Chicony Integrated Camera                                       | 30        | 3.89%   |
| Chicony USB2.0 VGA UVC WebCam                                   | 28        | 3.63%   |
| Syntek Integrated Camera                                        | 21        | 2.72%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 21        | 2.72%   |
| Realtek USB2.0 VGA UVC WebCam                                   | 17        | 2.2%    |
| Chicony USB2.0 HD UVC WebCam                                    | 16        | 2.08%   |
| IMC Networks Integrated Camera                                  | 14        | 1.82%   |
| Bison Lenovo EasyCamera                                         | 14        | 1.82%   |
| Microdia Integrated_Webcam_HD                                   | 13        | 1.69%   |
| Chicony HP TrueVision HD Camera                                 | 13        | 1.69%   |
| IMC Networks Lenovo EasyCamera                                  | 12        | 1.56%   |
| Bison Integrated Camera                                         | 12        | 1.56%   |
| IMC Networks EasyCamera                                         | 11        | 1.43%   |
| Realtek Integrated_Webcam_HD                                    | 10        | 1.3%    |
| Quanta HD User Facing                                           | 10        | 1.3%    |
| Sunplus Asus Webcam                                             | 9         | 1.17%   |
| Chicony Lenovo EasyCamera                                       | 9         | 1.17%   |
| Chicony EasyCamera                                              | 9         | 1.17%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera  | 9         | 1.17%   |
| Syntek EasyCamera                                               | 8         | 1.04%   |
| Realtek USB Camera                                              | 8         | 1.04%   |
| Suyin 1.3M HD WebCam                                            | 7         | 0.91%   |
| Sunplus Integrated_Webcam_HD                                    | 7         | 0.91%   |
| Quanta VGA WebCam                                               | 7         | 0.91%   |
| Quanta HP TrueVision HD Camera                                  | 7         | 0.91%   |
| Microdia Integrated Webcam                                      | 7         | 0.91%   |
| Chicony HP Truevision HD                                        | 7         | 0.91%   |
| Bison HD Webcam                                                 | 7         | 0.91%   |
| Alcor Micro USB 2.0 PC cam                                      | 7         | 0.91%   |
| Alcor Micro Asus Integrated Webcam                              | 7         | 0.91%   |
| Realtek USB2.0 HD UVC WebCam                                    | 6         | 0.78%   |
| Chicony TOSHIBA Web Camera - HD                                 | 6         | 0.78%   |
| Chicony HD User Facing                                          | 6         | 0.78%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                   | 6         | 0.78%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 6         | 0.78%   |
| Bison VGA Webcam                                                | 6         | 0.78%   |
| Bison EasyCamera                                                | 6         | 0.78%   |
| Syntek Lenovo EasyCamera                                        | 5         | 0.65%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 39        | 34.21%  |
| Elan Microelectronics      | 23        | 20.18%  |
| Synaptics                  | 16        | 14.04%  |
| LighTuning Technology      | 11        | 9.65%   |
| Shenzhen Goodix Technology | 10        | 8.77%   |
| AuthenTec                  | 8         | 7.02%   |
| Upek                       | 5         | 4.39%   |
| STMicroelectronics         | 2         | 1.75%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Elan ELAN:ARM-M4                                       | 12        | 10.53%  |
| LighTuning EgisTec Touch Fingerprint Sensor            | 10        | 8.77%   |
| Elan ELAN:Fingerprint                                  | 10        | 8.77%   |
| Validity Sensors VFS495 Fingerprint Reader             | 8         | 7.02%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 8         | 7.02%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 6         | 5.26%   |
| Shenzhen Goodix  FingerPrint Device                    | 6         | 5.26%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 5         | 4.39%   |
| Validity Sensors Swipe Fingerprint Sensor              | 5         | 4.39%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 5         | 4.39%   |
| Validity Sensors VFS Fingerprint sensor                | 4         | 3.51%   |
| Shenzhen Goodix Fingerprint Reader                     | 4         | 3.51%   |
| AuthenTec AES1600                                      | 4         | 3.51%   |
| Validity Sensors VFS471 Fingerprint Reader             | 3         | 2.63%   |
| Synaptics  WBDI                                        | 3         | 2.63%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 2         | 1.75%   |
| Validity Sensors VFS491                                | 2         | 1.75%   |
| Synaptics WBDI Fingerprint Reader USB 086              | 2         | 1.75%   |
| Synaptics UWP WBDI                                     | 2         | 1.75%   |
| STMicroelectronics Fingerprint Reader                  | 2         | 1.75%   |
| AuthenTec AES1660 Fingerprint Sensor                   | 2         | 1.75%   |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 0.88%   |
| Validity Sensors Synaptics WBDI                        | 1         | 0.88%   |
| Synaptics WBDI                                         | 1         | 0.88%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 0.88%   |
| Synaptics Fingerprint reader [HP G6]                   | 1         | 0.88%   |
| LighTuning ES603 Swipe Fingerprint Sensor              | 1         | 0.88%   |
| Elan fingerprint sensor [FeinTech FPS00200]            | 1         | 0.88%   |
| AuthenTec Fingerprint Sensor                           | 1         | 0.88%   |
| AuthenTec AES2810                                      | 1         | 0.88%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 16        | 51.61%  |
| O2 Micro    | 5         | 16.13%  |
| Upek        | 4         | 12.9%   |
| Alcor Micro | 4         | 12.9%   |
| Lenovo      | 2         | 6.45%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 9         | 29.03%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 16.13%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 12.9%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 4         | 12.9%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 12.9%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 6.45%   |
| Broadcom 58200                                                               | 2         | 6.45%   |
| Broadcom 5880                                                                | 1         | 3.23%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 600       | 67.95%  |
| 1     | 221       | 25.03%  |
| 2     | 55        | 6.23%   |
| 3     | 6         | 0.68%   |
| 6     | 1         | 0.11%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 113       | 33.73%  |
| Graphics card            | 87        | 25.97%  |
| Net/wireless             | 35        | 10.45%  |
| Chipcard                 | 29        | 8.66%   |
| Multimedia controller    | 23        | 6.87%   |
| Bluetooth                | 18        | 5.37%   |
| Camera                   | 7         | 2.09%   |
| Communication controller | 6         | 1.79%   |
| Net/ethernet             | 5         | 1.49%   |
| Storage                  | 4         | 1.19%   |
| Sound                    | 2         | 0.6%    |
| Flash memory             | 2         | 0.6%    |
| Card reader              | 2         | 0.6%    |
| Video                    | 1         | 0.3%    |
| Network                  | 1         | 0.3%    |

