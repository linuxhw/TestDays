Fedora 37 - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Fedora 37.

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

Total: 1204

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HUAWEI        | CREM-WXX9                   | [22d51a725f](https://linux-hardware.org/?probe=22d51a725f) | Feb 28, 2023 |
| Dell          | Latitude E7270              | [2718026d03](https://linux-hardware.org/?probe=2718026d03) | Feb 28, 2023 |
| TECNO         | MEGABOOK T1                 | [3b70c27ca4](https://linux-hardware.org/?probe=3b70c27ca4) | Feb 28, 2023 |
| HUAWEI        | MRC-WX0                     | [e2776f99bf](https://linux-hardware.org/?probe=e2776f99bf) | Feb 28, 2023 |
| HP            | ProBook 635 Aero G8 Note... | [93ee76f198](https://linux-hardware.org/?probe=93ee76f198) | Feb 28, 2023 |
| Acer          | Aspire A315-59              | [9a897f5d7c](https://linux-hardware.org/?probe=9a897f5d7c) | Feb 28, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | [b5a4a1809f](https://linux-hardware.org/?probe=b5a4a1809f) | Feb 28, 2023 |
| TECNO         | MEGABOOK T1                 | [3d003c6d17](https://linux-hardware.org/?probe=3d003c6d17) | Feb 28, 2023 |
| ASUSTek       | ROG Strix G712LW_G712LW     | [ed67c567d2](https://linux-hardware.org/?probe=ed67c567d2) | Feb 28, 2023 |
| Standard      | Unknown                     | [63732ac2da](https://linux-hardware.org/?probe=63732ac2da) | Feb 28, 2023 |
| Dell          | Precision 5570              | [7e8d7c37cb](https://linux-hardware.org/?probe=7e8d7c37cb) | Feb 28, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [c829e9e0b8](https://linux-hardware.org/?probe=c829e9e0b8) | Feb 27, 2023 |
| HP            | EliteBook Folio 9470m       | [45403acec9](https://linux-hardware.org/?probe=45403acec9) | Feb 27, 2023 |
| HUAWEI        | MACHR-WX9                   | [b1ef7c7ea1](https://linux-hardware.org/?probe=b1ef7c7ea1) | Feb 27, 2023 |
| Apple         | MacBookAir6,1               | [1c1dc86eb1](https://linux-hardware.org/?probe=1c1dc86eb1) | Feb 27, 2023 |
| HP            | EliteBook 845 14 inch G9... | [ed251c6cfe](https://linux-hardware.org/?probe=ed251c6cfe) | Feb 27, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [dd5ce2c6db](https://linux-hardware.org/?probe=dd5ce2c6db) | Feb 27, 2023 |
| Toshiba       | Satellite P870              | [6d9216b866](https://linux-hardware.org/?probe=6d9216b866) | Feb 27, 2023 |
| Dell          | Inspiron 15 3511            | [4c96506f38](https://linux-hardware.org/?probe=4c96506f38) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [d7e55bb97e](https://linux-hardware.org/?probe=d7e55bb97e) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [091e4e3188](https://linux-hardware.org/?probe=091e4e3188) | Feb 27, 2023 |
| Apple         | MacBookAir6,1               | [058ecdce01](https://linux-hardware.org/?probe=058ecdce01) | Feb 27, 2023 |
| Lenovo        | ThinkPad X395 20NL0006US    | [9030fac261](https://linux-hardware.org/?probe=9030fac261) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [fe8735a027](https://linux-hardware.org/?probe=fe8735a027) | Feb 26, 2023 |
| HP            | Notebook                    | [ab0dddc914](https://linux-hardware.org/?probe=ab0dddc914) | Feb 26, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [6b712e555f](https://linux-hardware.org/?probe=6b712e555f) | Feb 26, 2023 |
| Dell          | Vostro 3578                 | [da6968c8ac](https://linux-hardware.org/?probe=da6968c8ac) | Feb 26, 2023 |
| Samsung       | 370E4K                      | [7b769eb33e](https://linux-hardware.org/?probe=7b769eb33e) | Feb 26, 2023 |
| HUAWEI        | CREM-WXX9                   | [c026a25fb2](https://linux-hardware.org/?probe=c026a25fb2) | Feb 26, 2023 |
| HP            | 250 G6 Notebook PC          | [af6a897a26](https://linux-hardware.org/?probe=af6a897a26) | Feb 26, 2023 |
| Timi          | TM1612                      | [eb4a3f330e](https://linux-hardware.org/?probe=eb4a3f330e) | Feb 26, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [d3b6621252](https://linux-hardware.org/?probe=d3b6621252) | Feb 26, 2023 |
| Acer          | Nitro AN515-52              | [f589c3687b](https://linux-hardware.org/?probe=f589c3687b) | Feb 26, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [d610badec8](https://linux-hardware.org/?probe=d610badec8) | Feb 26, 2023 |
| Lenovo        | ThinkPad T61 6464A13        | [e981803528](https://linux-hardware.org/?probe=e981803528) | Feb 26, 2023 |
| Standard      | Unknown                     | [9d002e0593](https://linux-hardware.org/?probe=9d002e0593) | Feb 26, 2023 |
| Lenovo        | Legion 5 82B5               | [8db23a7237](https://linux-hardware.org/?probe=8db23a7237) | Feb 25, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [bd2c3ecd74](https://linux-hardware.org/?probe=bd2c3ecd74) | Feb 25, 2023 |
| Lenovo        | ThinkPad T480 20L5S03600    | [5c9736ab0c](https://linux-hardware.org/?probe=5c9736ab0c) | Feb 25, 2023 |
| Dell          | Vostro 14-5459              | [1f96898a48](https://linux-hardware.org/?probe=1f96898a48) | Feb 25, 2023 |
| Dell          | Latitude E6420              | [7ae4fe9340](https://linux-hardware.org/?probe=7ae4fe9340) | Feb 25, 2023 |
| Dell          | Latitude 5511               | [4402838fb3](https://linux-hardware.org/?probe=4402838fb3) | Feb 25, 2023 |
| Google        | Voxel                       | [ce917fe8ec](https://linux-hardware.org/?probe=ce917fe8ec) | Feb 25, 2023 |
| Google        | Voxel                       | [93ea143f69](https://linux-hardware.org/?probe=93ea143f69) | Feb 25, 2023 |
| Dell          | Inspiron 5759               | [be0b15660e](https://linux-hardware.org/?probe=be0b15660e) | Feb 25, 2023 |
| HUAWEI        | MACH-WX9                    | [52924074db](https://linux-hardware.org/?probe=52924074db) | Feb 25, 2023 |
| Dell          | Precision 5520              | [c41014658b](https://linux-hardware.org/?probe=c41014658b) | Feb 25, 2023 |
| Dell          | System XPS L321X            | [4de5ba1c80](https://linux-hardware.org/?probe=4de5ba1c80) | Feb 25, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [1c1e5c991f](https://linux-hardware.org/?probe=1c1e5c991f) | Feb 25, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [9cbbaaf012](https://linux-hardware.org/?probe=9cbbaaf012) | Feb 24, 2023 |
| Chuwi         | GemiBook Pro                | [f8f1005d73](https://linux-hardware.org/?probe=f8f1005d73) | Feb 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [787270bc9e](https://linux-hardware.org/?probe=787270bc9e) | Feb 24, 2023 |
| Lenovo        | Yoga Pro 14s IAH7 82TK      | [ade006d016](https://linux-hardware.org/?probe=ade006d016) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [2bbce041f5](https://linux-hardware.org/?probe=2bbce041f5) | Feb 24, 2023 |
| MSI           | MS-7A32                     | [2312252934](https://linux-hardware.org/?probe=2312252934) | Feb 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [f7063f868f](https://linux-hardware.org/?probe=f7063f868f) | Feb 24, 2023 |
| HP            | 245 G8 Notebook PC          | [7686bcd76d](https://linux-hardware.org/?probe=7686bcd76d) | Feb 24, 2023 |
| Dell          | Inspiron 13-7359            | [7858955f02](https://linux-hardware.org/?probe=7858955f02) | Feb 24, 2023 |
| Toshiba       | Satellite L515              | [969c2042b9](https://linux-hardware.org/?probe=969c2042b9) | Feb 24, 2023 |
| Dell          | G5 5587                     | [1f43871064](https://linux-hardware.org/?probe=1f43871064) | Feb 24, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [f92ac89547](https://linux-hardware.org/?probe=f92ac89547) | Feb 23, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [4b0436b55d](https://linux-hardware.org/?probe=4b0436b55d) | Feb 23, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [a4c4313238](https://linux-hardware.org/?probe=a4c4313238) | Feb 23, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | [bb2bef71e0](https://linux-hardware.org/?probe=bb2bef71e0) | Feb 23, 2023 |
| Lenovo        | ThinkPad X230 2325CS6       | [ed9501bbcb](https://linux-hardware.org/?probe=ed9501bbcb) | Feb 23, 2023 |
| Dell          | Inspiron 13-7359            | [39d95063c3](https://linux-hardware.org/?probe=39d95063c3) | Feb 23, 2023 |
| ASUSTek       | K56CA                       | [d8475e4c48](https://linux-hardware.org/?probe=d8475e4c48) | Feb 23, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [e23562af05](https://linux-hardware.org/?probe=e23562af05) | Feb 23, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [becb5b0ba1](https://linux-hardware.org/?probe=becb5b0ba1) | Feb 22, 2023 |
| CyberPower... | Tracer IV GM5MQ8W           | [284e8a4fb1](https://linux-hardware.org/?probe=284e8a4fb1) | Feb 22, 2023 |
| Dell          | Latitude E5570              | [338538c1c9](https://linux-hardware.org/?probe=338538c1c9) | Feb 22, 2023 |
| Gigabyte      | G5 KD                       | [65c50530c8](https://linux-hardware.org/?probe=65c50530c8) | Feb 22, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [7d3442e2a7](https://linux-hardware.org/?probe=7d3442e2a7) | Feb 22, 2023 |
| Alienware     | x14                         | [0b32a33625](https://linux-hardware.org/?probe=0b32a33625) | Feb 22, 2023 |
| Alienware     | x14                         | [04094754b6](https://linux-hardware.org/?probe=04094754b6) | Feb 22, 2023 |
| HP            | Notebook                    | [f6d3ba25ba](https://linux-hardware.org/?probe=f6d3ba25ba) | Feb 22, 2023 |
| Samsung       | 767XCL                      | [3fb09fb626](https://linux-hardware.org/?probe=3fb09fb626) | Feb 22, 2023 |
| Dell          | Latitude 5491               | [fd68ba9595](https://linux-hardware.org/?probe=fd68ba9595) | Feb 21, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [a459216464](https://linux-hardware.org/?probe=a459216464) | Feb 21, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [7ead9488ae](https://linux-hardware.org/?probe=7ead9488ae) | Feb 21, 2023 |
| Apple         | MacBookAir6,1               | [b9117f0c6f](https://linux-hardware.org/?probe=b9117f0c6f) | Feb 21, 2023 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | [c0733771d5](https://linux-hardware.org/?probe=c0733771d5) | Feb 21, 2023 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | [039bb422e0](https://linux-hardware.org/?probe=039bb422e0) | Feb 21, 2023 |
| Acer          | Aspire SW3-013              | [f0111df214](https://linux-hardware.org/?probe=f0111df214) | Feb 21, 2023 |
| Alienware     | 15 R2                       | [96aa09ae59](https://linux-hardware.org/?probe=96aa09ae59) | Feb 21, 2023 |
| HP            | EliteBook 2540p             | [bf037f7503](https://linux-hardware.org/?probe=bf037f7503) | Feb 21, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [d1f67d5e08](https://linux-hardware.org/?probe=d1f67d5e08) | Feb 21, 2023 |
| Acer          | Nitro AN515-52              | [9989903f85](https://linux-hardware.org/?probe=9989903f85) | Feb 21, 2023 |
| Dell          | XPS 13 7390                 | [2b329d108f](https://linux-hardware.org/?probe=2b329d108f) | Feb 21, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [53737369e8](https://linux-hardware.org/?probe=53737369e8) | Feb 21, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [b8c4b41baf](https://linux-hardware.org/?probe=b8c4b41baf) | Feb 21, 2023 |
| Dell          | XPS 13 7390                 | [a3ed8101b1](https://linux-hardware.org/?probe=a3ed8101b1) | Feb 20, 2023 |
| MSI           | Modern 15 A5M               | [f6c80ff7a9](https://linux-hardware.org/?probe=f6c80ff7a9) | Feb 20, 2023 |
| Fujitsu       | LIFEBOOK E559               | [5e4c3607c7](https://linux-hardware.org/?probe=5e4c3607c7) | Feb 20, 2023 |
| Fujitsu       | LIFEBOOK A357               | [a813f73ea2](https://linux-hardware.org/?probe=a813f73ea2) | Feb 20, 2023 |
| MSI           | Bravo 15 B5ED               | [a0b7f1b5f8](https://linux-hardware.org/?probe=a0b7f1b5f8) | Feb 20, 2023 |
| Lenovo        | ThinkPad T530 239265U       | [9f60ca6bf5](https://linux-hardware.org/?probe=9f60ca6bf5) | Feb 20, 2023 |
| Dell          | XPS 13 7390                 | [542077cc42](https://linux-hardware.org/?probe=542077cc42) | Feb 20, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [057dcdc86b](https://linux-hardware.org/?probe=057dcdc86b) | Feb 20, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | [d8abf7361b](https://linux-hardware.org/?probe=d8abf7361b) | Feb 20, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [89eb85b36f](https://linux-hardware.org/?probe=89eb85b36f) | Feb 19, 2023 |
| Chuwi         | HeroBook Air                | [c669fff700](https://linux-hardware.org/?probe=c669fff700) | Feb 19, 2023 |
| Acer          | Predator PH315-52           | [7432db815e](https://linux-hardware.org/?probe=7432db815e) | Feb 19, 2023 |
| Acer          | Predator PH315-52           | [aaee9da394](https://linux-hardware.org/?probe=aaee9da394) | Feb 19, 2023 |
| ASUSTek       | ROG Strix G733ZW_G733ZW     | [72f074b930](https://linux-hardware.org/?probe=72f074b930) | Feb 19, 2023 |
| Dell          | Latitude E6430              | [23c0ff9281](https://linux-hardware.org/?probe=23c0ff9281) | Feb 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [b1d168b6ce](https://linux-hardware.org/?probe=b1d168b6ce) | Feb 19, 2023 |
| Dell          | Latitude E6430              | [d97087b55f](https://linux-hardware.org/?probe=d97087b55f) | Feb 19, 2023 |
| Lenovo        | ThinkPad E555 20DH000TUK    | [b2d5c9de8b](https://linux-hardware.org/?probe=b2d5c9de8b) | Feb 19, 2023 |
| Standard      | Unknown                     | [149bdc4e40](https://linux-hardware.org/?probe=149bdc4e40) | Feb 19, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [9b0ecbd3c7](https://linux-hardware.org/?probe=9b0ecbd3c7) | Feb 19, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | [ee24b75c39](https://linux-hardware.org/?probe=ee24b75c39) | Feb 19, 2023 |
| Dell          | Precision M4500             | [b0d8bf3c56](https://linux-hardware.org/?probe=b0d8bf3c56) | Feb 19, 2023 |
| Apple         | MacBookAir6,1               | [5cade7cfc3](https://linux-hardware.org/?probe=5cade7cfc3) | Feb 19, 2023 |
| Google        | Kled                        | [788d726509](https://linux-hardware.org/?probe=788d726509) | Feb 18, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [9b53b2b842](https://linux-hardware.org/?probe=9b53b2b842) | Feb 18, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [cdfcc639d3](https://linux-hardware.org/?probe=cdfcc639d3) | Feb 18, 2023 |
| Lenovo        | ThinkPad T530 2429F27       | [b835147a32](https://linux-hardware.org/?probe=b835147a32) | Feb 18, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | [fb2cbe3576](https://linux-hardware.org/?probe=fb2cbe3576) | Feb 18, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [a424b3aa47](https://linux-hardware.org/?probe=a424b3aa47) | Feb 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [e7988c5ab6](https://linux-hardware.org/?probe=e7988c5ab6) | Feb 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | [6d2b283e83](https://linux-hardware.org/?probe=6d2b283e83) | Feb 18, 2023 |
| Dell          | Precision 5560              | [24e5de4a3d](https://linux-hardware.org/?probe=24e5de4a3d) | Feb 18, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [c4a1fe4a4f](https://linux-hardware.org/?probe=c4a1fe4a4f) | Feb 17, 2023 |
| Lenovo        | ThinkPad T490 20N2001YUS    | [53ef9ffad8](https://linux-hardware.org/?probe=53ef9ffad8) | Feb 17, 2023 |
| Dell          | Latitude 5491               | [8a3298cdff](https://linux-hardware.org/?probe=8a3298cdff) | Feb 17, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [e4483255db](https://linux-hardware.org/?probe=e4483255db) | Feb 17, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [09aefeb3d6](https://linux-hardware.org/?probe=09aefeb3d6) | Feb 17, 2023 |
| Dell          | Inspiron 5566               | [502adcba49](https://linux-hardware.org/?probe=502adcba49) | Feb 17, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | [cc44156b99](https://linux-hardware.org/?probe=cc44156b99) | Feb 17, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | [bc234d0b32](https://linux-hardware.org/?probe=bc234d0b32) | Feb 17, 2023 |
| HP            | ENVY Laptop 17-ch2xxx       | [c1abb80cb1](https://linux-hardware.org/?probe=c1abb80cb1) | Feb 17, 2023 |
| Lenovo        | ZIWB2                       | [8ade075157](https://linux-hardware.org/?probe=8ade075157) | Feb 16, 2023 |
| HP            | 245 G8 Notebook PC          | [c48e458030](https://linux-hardware.org/?probe=c48e458030) | Feb 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [4657fc266d](https://linux-hardware.org/?probe=4657fc266d) | Feb 16, 2023 |
| Acer          | Swift SF314-511             | [71778cedf9](https://linux-hardware.org/?probe=71778cedf9) | Feb 16, 2023 |
| Samsung       | 940XFG                      | [56f236f8ab](https://linux-hardware.org/?probe=56f236f8ab) | Feb 16, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [ddc2c7ec7a](https://linux-hardware.org/?probe=ddc2c7ec7a) | Feb 16, 2023 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | [5a3b0950b3](https://linux-hardware.org/?probe=5a3b0950b3) | Feb 16, 2023 |
| Lenovo        | Y50-70 20378                | [09301690c5](https://linux-hardware.org/?probe=09301690c5) | Feb 15, 2023 |
| HP            | Notebook                    | [9fe647f9a1](https://linux-hardware.org/?probe=9fe647f9a1) | Feb 15, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [36f57d56f8](https://linux-hardware.org/?probe=36f57d56f8) | Feb 15, 2023 |
| HP            | Notebook                    | [c4516fb37a](https://linux-hardware.org/?probe=c4516fb37a) | Feb 15, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [7fd55795a0](https://linux-hardware.org/?probe=7fd55795a0) | Feb 15, 2023 |
| Lenovo        | ThinkPad P50 20EQS64N09     | [72fad631b7](https://linux-hardware.org/?probe=72fad631b7) | Feb 15, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [70885f1dfd](https://linux-hardware.org/?probe=70885f1dfd) | Feb 15, 2023 |
| HP            | Laptop 15s-eq2xxx           | [92a9452070](https://linux-hardware.org/?probe=92a9452070) | Feb 15, 2023 |
| Dell          | Inspiron 7375               | [3916d619ed](https://linux-hardware.org/?probe=3916d619ed) | Feb 15, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [1ca19c3d1d](https://linux-hardware.org/?probe=1ca19c3d1d) | Feb 14, 2023 |
| ASUSTek       | UL30A                       | [90114a4fe4](https://linux-hardware.org/?probe=90114a4fe4) | Feb 14, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [390686f5f6](https://linux-hardware.org/?probe=390686f5f6) | Feb 14, 2023 |
| HP            | ProBook 440 G7              | [bc4811db07](https://linux-hardware.org/?probe=bc4811db07) | Feb 14, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [cbcadcf80a](https://linux-hardware.org/?probe=cbcadcf80a) | Feb 14, 2023 |
| Dell          | Latitude E7270              | [03199b7612](https://linux-hardware.org/?probe=03199b7612) | Feb 14, 2023 |
| Lenovo        | IdeaPad 520S-14IKB 81BL     | [008d06fbf8](https://linux-hardware.org/?probe=008d06fbf8) | Feb 14, 2023 |
| Timi          | Xiaomi NoteBook Pro         | [561e1a6160](https://linux-hardware.org/?probe=561e1a6160) | Feb 14, 2023 |
| Dell          | Latitude 7430               | [82dcb0a8a2](https://linux-hardware.org/?probe=82dcb0a8a2) | Feb 14, 2023 |
| Dell          | G3 3579                     | [35c8b69b8c](https://linux-hardware.org/?probe=35c8b69b8c) | Feb 14, 2023 |
| HP            | EliteBook 840 G5            | [2f78b0c253](https://linux-hardware.org/?probe=2f78b0c253) | Feb 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [ac71e5b8ef](https://linux-hardware.org/?probe=ac71e5b8ef) | Feb 14, 2023 |
| Dell          | Inspiron 14 5420            | [45862fde09](https://linux-hardware.org/?probe=45862fde09) | Feb 13, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [1f0e965483](https://linux-hardware.org/?probe=1f0e965483) | Feb 13, 2023 |
| Dell          | Inspiron 14 5420            | [8153aeb3fb](https://linux-hardware.org/?probe=8153aeb3fb) | Feb 13, 2023 |
| Dell          | XPS 15 9560                 | [01319ac289](https://linux-hardware.org/?probe=01319ac289) | Feb 13, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [f701208fd4](https://linux-hardware.org/?probe=f701208fd4) | Feb 13, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [3b7765dfcc](https://linux-hardware.org/?probe=3b7765dfcc) | Feb 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [6add161dbe](https://linux-hardware.org/?probe=6add161dbe) | Feb 13, 2023 |
| Dell          | Latitude 5511               | [161095d97a](https://linux-hardware.org/?probe=161095d97a) | Feb 13, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | [7e90fe56d1](https://linux-hardware.org/?probe=7e90fe56d1) | Feb 13, 2023 |
| MSI           | Raider GE77HX 12UHS         | [abd464b0d3](https://linux-hardware.org/?probe=abd464b0d3) | Feb 13, 2023 |
| HP            | ProBook 445 G7              | [7fdcffc633](https://linux-hardware.org/?probe=7fdcffc633) | Feb 13, 2023 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | [0560a363b8](https://linux-hardware.org/?probe=0560a363b8) | Feb 12, 2023 |
| Dell          | Venue 10 Pro 5055           | [7afcfff799](https://linux-hardware.org/?probe=7afcfff799) | Feb 12, 2023 |
| Acer          | Aspire A715-74G             | [cdd913ae48](https://linux-hardware.org/?probe=cdd913ae48) | Feb 12, 2023 |
| Dell          | Latitude E6420              | [6ffa1ea310](https://linux-hardware.org/?probe=6ffa1ea310) | Feb 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [04cfa15383](https://linux-hardware.org/?probe=04cfa15383) | Feb 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [3c8717baf4](https://linux-hardware.org/?probe=3c8717baf4) | Feb 12, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [8f74caf33e](https://linux-hardware.org/?probe=8f74caf33e) | Feb 12, 2023 |
| HP            | EliteBook 840 G5            | [b569293b7b](https://linux-hardware.org/?probe=b569293b7b) | Feb 12, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [a4b4558244](https://linux-hardware.org/?probe=a4b4558244) | Feb 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [1e3ceef5e6](https://linux-hardware.org/?probe=1e3ceef5e6) | Feb 12, 2023 |
| HP            | Notebook                    | [729f2b5250](https://linux-hardware.org/?probe=729f2b5250) | Feb 12, 2023 |
| HP            | Notebook                    | [155c8fa16e](https://linux-hardware.org/?probe=155c8fa16e) | Feb 12, 2023 |
| ASUSTek       | X510UAR                     | [365b6606cd](https://linux-hardware.org/?probe=365b6606cd) | Feb 12, 2023 |
| HUAWEI        | NBD-WXX9                    | [c8caa92db3](https://linux-hardware.org/?probe=c8caa92db3) | Feb 11, 2023 |
| Lenovo        | IdeaPad S540-15IWL          | [321710ca2d](https://linux-hardware.org/?probe=321710ca2d) | Feb 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [40116058d1](https://linux-hardware.org/?probe=40116058d1) | Feb 11, 2023 |
| HONOR         | BBR-WAX9                    | [de54b14304](https://linux-hardware.org/?probe=de54b14304) | Feb 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [8e00bdf032](https://linux-hardware.org/?probe=8e00bdf032) | Feb 11, 2023 |
| Dell          | Vostro 15 3515              | [22d5eabee5](https://linux-hardware.org/?probe=22d5eabee5) | Feb 11, 2023 |
| HP            | Pavilion Power Laptop 15... | [2beb0c0b30](https://linux-hardware.org/?probe=2beb0c0b30) | Feb 11, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [a1133b56be](https://linux-hardware.org/?probe=a1133b56be) | Feb 11, 2023 |
| ASUSTek       | G75VW                       | [e2eeee26af](https://linux-hardware.org/?probe=e2eeee26af) | Feb 11, 2023 |
| Acer          | Aspire A315-23              | [f56c83d6dd](https://linux-hardware.org/?probe=f56c83d6dd) | Feb 11, 2023 |
| Dell          | Latitude E7270              | [c684709755](https://linux-hardware.org/?probe=c684709755) | Feb 11, 2023 |
| Acer          | TravelMate 7730             | [a9a9e21b5a](https://linux-hardware.org/?probe=a9a9e21b5a) | Feb 10, 2023 |
| Dell          | Inspiron 7559               | [956a602343](https://linux-hardware.org/?probe=956a602343) | Feb 10, 2023 |
| ASUSTek       | ROG Strix G733QR_G733QR     | [da12318597](https://linux-hardware.org/?probe=da12318597) | Feb 10, 2023 |
| Dell          | XPS 13 9310                 | [0461c55b4a](https://linux-hardware.org/?probe=0461c55b4a) | Feb 10, 2023 |
| MSI           | Raider GE77HX 12UHS         | [d77cac7fb6](https://linux-hardware.org/?probe=d77cac7fb6) | Feb 10, 2023 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | [9b8563ab53](https://linux-hardware.org/?probe=9b8563ab53) | Feb 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [3f4b71a601](https://linux-hardware.org/?probe=3f4b71a601) | Feb 09, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [25e4994344](https://linux-hardware.org/?probe=25e4994344) | Feb 09, 2023 |
| Lenovo        | ThinkPad T590 20N5S4R800    | [6a55f84594](https://linux-hardware.org/?probe=6a55f84594) | Feb 09, 2023 |
| HP            | EliteBook 8460p             | [91de8b5956](https://linux-hardware.org/?probe=91de8b5956) | Feb 09, 2023 |
| Monster       | TULPAR T7 V5.x              | [edc2a0bc35](https://linux-hardware.org/?probe=edc2a0bc35) | Feb 09, 2023 |
| Monster       | TULPAR T7 V5.x              | [8d1a082e35](https://linux-hardware.org/?probe=8d1a082e35) | Feb 09, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [8d2e488f38](https://linux-hardware.org/?probe=8d2e488f38) | Feb 09, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [467c3e9149](https://linux-hardware.org/?probe=467c3e9149) | Feb 09, 2023 |
| HP            | 2000                        | [f76b7389d7](https://linux-hardware.org/?probe=f76b7389d7) | Feb 09, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [81a3a141ba](https://linux-hardware.org/?probe=81a3a141ba) | Feb 08, 2023 |
| Acer          | Aspire A315-59              | [78d55087bb](https://linux-hardware.org/?probe=78d55087bb) | Feb 08, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C7C... | [26fb33ec6c](https://linux-hardware.org/?probe=26fb33ec6c) | Feb 08, 2023 |
| Dell          | Latitude 3570               | [dc460632ef](https://linux-hardware.org/?probe=dc460632ef) | Feb 08, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [bc2ea675c8](https://linux-hardware.org/?probe=bc2ea675c8) | Feb 08, 2023 |
| ASUSTek       | X510UAR                     | [0b2a31bed4](https://linux-hardware.org/?probe=0b2a31bed4) | Feb 08, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS1... | [9bf97a14cf](https://linux-hardware.org/?probe=9bf97a14cf) | Feb 08, 2023 |
| ASUSTek       | X510UAR                     | [b440353d20](https://linux-hardware.org/?probe=b440353d20) | Feb 08, 2023 |
| Google        | Delbin                      | [268fbe9849](https://linux-hardware.org/?probe=268fbe9849) | Feb 08, 2023 |
| Google        | Delbin                      | [1afd4fec8d](https://linux-hardware.org/?probe=1afd4fec8d) | Feb 08, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS1... | [5e5ec021d0](https://linux-hardware.org/?probe=5e5ec021d0) | Feb 08, 2023 |
| Apple         | MacBookPro10,1              | [fd61c4416f](https://linux-hardware.org/?probe=fd61c4416f) | Feb 08, 2023 |
| HP            | Pavilion 17                 | [9bd81582a4](https://linux-hardware.org/?probe=9bd81582a4) | Feb 07, 2023 |
| HP            | Pavilion 17                 | [45eb87271b](https://linux-hardware.org/?probe=45eb87271b) | Feb 07, 2023 |
| TUXEDO        | InfinityBook S 14 Gen6      | [9e019a0396](https://linux-hardware.org/?probe=9e019a0396) | Feb 07, 2023 |
| MSI           | Modern 14 B11MOU            | [325806b7cc](https://linux-hardware.org/?probe=325806b7cc) | Feb 07, 2023 |
| MSI           | Modern 14 B11MOU            | [870a2912c9](https://linux-hardware.org/?probe=870a2912c9) | Feb 07, 2023 |
| HUAWEI        | MACH-WX9                    | [263101d492](https://linux-hardware.org/?probe=263101d492) | Feb 07, 2023 |
| Dell          | Latitude 5330               | [30cd96be4d](https://linux-hardware.org/?probe=30cd96be4d) | Feb 07, 2023 |
| Timi          | TM1613                      | [503133b0db](https://linux-hardware.org/?probe=503133b0db) | Feb 07, 2023 |
| Samsung       | 900X5N                      | [91793918de](https://linux-hardware.org/?probe=91793918de) | Feb 07, 2023 |
| HP            | Laptop 15-bw0xx             | [da8dac3c03](https://linux-hardware.org/?probe=da8dac3c03) | Feb 07, 2023 |
| Google        | Kefka                       | [5f290f685b](https://linux-hardware.org/?probe=5f290f685b) | Feb 06, 2023 |
| Dell          | Latitude 5490               | [95de125f35](https://linux-hardware.org/?probe=95de125f35) | Feb 06, 2023 |
| ASUSTek       | P453UA                      | [476ff28577](https://linux-hardware.org/?probe=476ff28577) | Feb 06, 2023 |
| MSI           | Stealth 15M B12UE           | [44de7ac1aa](https://linux-hardware.org/?probe=44de7ac1aa) | Feb 06, 2023 |
| ASUSTek       | G73Sw                       | [42e7c32817](https://linux-hardware.org/?probe=42e7c32817) | Feb 06, 2023 |
| Dell          | Inspiron 5749               | [2fbf439175](https://linux-hardware.org/?probe=2fbf439175) | Feb 06, 2023 |
| HONOR         | NMH-WCX9                    | [1f2418bafb](https://linux-hardware.org/?probe=1f2418bafb) | Feb 06, 2023 |
| Toshiba       | Satellite L50-B             | [fe59cbe322](https://linux-hardware.org/?probe=fe59cbe322) | Feb 06, 2023 |
| HP            | 2000                        | [5e672192b6](https://linux-hardware.org/?probe=5e672192b6) | Feb 06, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [f3ec6a2ed1](https://linux-hardware.org/?probe=f3ec6a2ed1) | Feb 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [da270fa237](https://linux-hardware.org/?probe=da270fa237) | Feb 05, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [de72d92ada](https://linux-hardware.org/?probe=de72d92ada) | Feb 05, 2023 |
| HUAWEI        | KLVL-WXX9                   | [c222b31f37](https://linux-hardware.org/?probe=c222b31f37) | Feb 05, 2023 |
| Google        | Kefka                       | [59e3f92752](https://linux-hardware.org/?probe=59e3f92752) | Feb 05, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | [a0fea9707e](https://linux-hardware.org/?probe=a0fea9707e) | Feb 05, 2023 |
| ASUSTek       | X556UV                      | [ae90dba4ca](https://linux-hardware.org/?probe=ae90dba4ca) | Feb 04, 2023 |
| Dell          | Inspiron 3593               | [2e87d3f607](https://linux-hardware.org/?probe=2e87d3f607) | Feb 04, 2023 |
| Dell          | Vostro 15 3515              | [c4c5c0888a](https://linux-hardware.org/?probe=c4c5c0888a) | Feb 04, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | [8771985f5b](https://linux-hardware.org/?probe=8771985f5b) | Feb 04, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | [9592836c3b](https://linux-hardware.org/?probe=9592836c3b) | Feb 04, 2023 |
| Dell          | XPS 15 9550                 | [200495d065](https://linux-hardware.org/?probe=200495d065) | Feb 04, 2023 |
| ASUSTek       | X200CA                      | [38cdc2564e](https://linux-hardware.org/?probe=38cdc2564e) | Feb 04, 2023 |
| HP            | Laptop 17-ak0xx             | [2ec4deba0b](https://linux-hardware.org/?probe=2ec4deba0b) | Feb 04, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [cfaa43cc81](https://linux-hardware.org/?probe=cfaa43cc81) | Feb 04, 2023 |
| ASUSTek       | X200CA                      | [8c2a91c204](https://linux-hardware.org/?probe=8c2a91c204) | Feb 04, 2023 |
| SiComputer    | Nauta 01C                   | [1579a837f7](https://linux-hardware.org/?probe=1579a837f7) | Feb 04, 2023 |
| HUAWEI        | CREM-WXX9                   | [43a0910ff6](https://linux-hardware.org/?probe=43a0910ff6) | Feb 04, 2023 |
| Lenovo        | ThinkPad P72 20MB0005GE     | [6322972a9c](https://linux-hardware.org/?probe=6322972a9c) | Feb 04, 2023 |
| MSI           | Stealth 15M B12UE           | [c0434c976e](https://linux-hardware.org/?probe=c0434c976e) | Feb 04, 2023 |
| HP            | ZBook Power 15.6 inch G9... | [1e38d08821](https://linux-hardware.org/?probe=1e38d08821) | Feb 03, 2023 |
| Dell          | Latitude 5530               | [dd0a933124](https://linux-hardware.org/?probe=dd0a933124) | Feb 03, 2023 |
| Dynabook      | PORTEGE X30L-K              | [af43366b45](https://linux-hardware.org/?probe=af43366b45) | Feb 03, 2023 |
| Acer          | Aspire 5750G                | [fa1e255519](https://linux-hardware.org/?probe=fa1e255519) | Feb 03, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [d7fff6982b](https://linux-hardware.org/?probe=d7fff6982b) | Feb 03, 2023 |
| Acer          | Aspire 5750G                | [ada6dd2b76](https://linux-hardware.org/?probe=ada6dd2b76) | Feb 03, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [a1073e64f7](https://linux-hardware.org/?probe=a1073e64f7) | Feb 03, 2023 |
| Dell          | Latitude E6430              | [10b3b0cfbb](https://linux-hardware.org/?probe=10b3b0cfbb) | Feb 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [9c5cfbc1a1](https://linux-hardware.org/?probe=9c5cfbc1a1) | Feb 03, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [b660fd4859](https://linux-hardware.org/?probe=b660fd4859) | Feb 03, 2023 |
| ASUSTek       | UL30A                       | [11885376b2](https://linux-hardware.org/?probe=11885376b2) | Feb 03, 2023 |
| HP            | ProBook 440 G7              | [f9a4f80656](https://linux-hardware.org/?probe=f9a4f80656) | Feb 03, 2023 |
| ASUSTek       | G751JT                      | [2085089213](https://linux-hardware.org/?probe=2085089213) | Feb 03, 2023 |
| HUAWEI        | CREM-WXX9                   | [f794d33e76](https://linux-hardware.org/?probe=f794d33e76) | Feb 02, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [8c9b8348a4](https://linux-hardware.org/?probe=8c9b8348a4) | Feb 02, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [bd19e14a45](https://linux-hardware.org/?probe=bd19e14a45) | Feb 02, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [e49b22de8a](https://linux-hardware.org/?probe=e49b22de8a) | Feb 02, 2023 |
| Acer          | Aspire F5-573G              | [ba43497e32](https://linux-hardware.org/?probe=ba43497e32) | Feb 02, 2023 |
| Acer          | Aspire A715-42G             | [a169951063](https://linux-hardware.org/?probe=a169951063) | Feb 02, 2023 |
| HP            | EliteBook 840 G2            | [7dd8dceb80](https://linux-hardware.org/?probe=7dd8dceb80) | Feb 02, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [27c816b62a](https://linux-hardware.org/?probe=27c816b62a) | Feb 02, 2023 |
| HP            | EliteBook 840 G2            | [3339c49f38](https://linux-hardware.org/?probe=3339c49f38) | Feb 02, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [1c6ed7ede6](https://linux-hardware.org/?probe=1c6ed7ede6) | Feb 02, 2023 |
| ASUSTek       | ZenBook UX425JA_UX425JA     | [367646ee16](https://linux-hardware.org/?probe=367646ee16) | Feb 02, 2023 |
| Lenovo        | ZIWB2                       | [b7ff6b4dd5](https://linux-hardware.org/?probe=b7ff6b4dd5) | Feb 02, 2023 |
| ASUSTek       | K54L                        | [8568b17267](https://linux-hardware.org/?probe=8568b17267) | Feb 02, 2023 |
| Acer          | Aspire A715-42G             | [45890fca78](https://linux-hardware.org/?probe=45890fca78) | Feb 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [159a453649](https://linux-hardware.org/?probe=159a453649) | Feb 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [0538afb301](https://linux-hardware.org/?probe=0538afb301) | Feb 02, 2023 |
| Dell          | XPS 15 9510                 | [78ea388883](https://linux-hardware.org/?probe=78ea388883) | Feb 02, 2023 |
| Dell          | Latitude E6430              | [55c398146b](https://linux-hardware.org/?probe=55c398146b) | Feb 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | [8bc290ef67](https://linux-hardware.org/?probe=8bc290ef67) | Feb 01, 2023 |
| MSI           | Modern 14 B11MOU            | [542173e9a2](https://linux-hardware.org/?probe=542173e9a2) | Feb 01, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [ab31f6153e](https://linux-hardware.org/?probe=ab31f6153e) | Feb 01, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [22abfb4a79](https://linux-hardware.org/?probe=22abfb4a79) | Feb 01, 2023 |
| Lenovo        | ThinkPad A485 20MVS0U500    | [b398a8e8e6](https://linux-hardware.org/?probe=b398a8e8e6) | Feb 01, 2023 |
| ASUSTek       | N552VW                      | [1ebeeec517](https://linux-hardware.org/?probe=1ebeeec517) | Feb 01, 2023 |
| Dell          | Inspiron 7501               | [426493e8a5](https://linux-hardware.org/?probe=426493e8a5) | Feb 01, 2023 |
| HP            | Laptop 14-dq4xxx            | [c102edf6a0](https://linux-hardware.org/?probe=c102edf6a0) | Feb 01, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [6b9dc508e1](https://linux-hardware.org/?probe=6b9dc508e1) | Feb 01, 2023 |
| Dell          | Inspiron 5748               | [7ee6505f8d](https://linux-hardware.org/?probe=7ee6505f8d) | Feb 01, 2023 |
| ASUSTek       | Zenbook UX8402ZA_UX8402Z... | [1d212c67b2](https://linux-hardware.org/?probe=1d212c67b2) | Jan 31, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [70310e25d1](https://linux-hardware.org/?probe=70310e25d1) | Jan 31, 2023 |
| HUAWEI        | HN-WX9X                     | [4b8ddf5d09](https://linux-hardware.org/?probe=4b8ddf5d09) | Jan 31, 2023 |
| Dell          | Inspiron 5748               | [ecbd4ac8b6](https://linux-hardware.org/?probe=ecbd4ac8b6) | Jan 31, 2023 |
| Lenovo        | ThinkPad T530 2429F27       | [85ac6a588d](https://linux-hardware.org/?probe=85ac6a588d) | Jan 31, 2023 |
| ASUSTek       | Zenbook UX8402ZA_UX8402Z... | [4dcc88b215](https://linux-hardware.org/?probe=4dcc88b215) | Jan 31, 2023 |
| TUXEDO        | Stellaris Intel Gen4        | [2df9f60f2e](https://linux-hardware.org/?probe=2df9f60f2e) | Jan 31, 2023 |
| Acer          | Predator PH315-52           | [b1c77eb9c7](https://linux-hardware.org/?probe=b1c77eb9c7) | Jan 31, 2023 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | [a64ae29757](https://linux-hardware.org/?probe=a64ae29757) | Jan 31, 2023 |
| Samsung       | 550XCJ/550XCR               | [75fad3daf3](https://linux-hardware.org/?probe=75fad3daf3) | Jan 31, 2023 |
| Dell          | XPS 15 9570                 | [ee60c1c921](https://linux-hardware.org/?probe=ee60c1c921) | Jan 31, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | [87904d9d06](https://linux-hardware.org/?probe=87904d9d06) | Jan 31, 2023 |
| Dell          | Vostro 15 3515              | [357d14774f](https://linux-hardware.org/?probe=357d14774f) | Jan 30, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603ZX... | [7442c84b55](https://linux-hardware.org/?probe=7442c84b55) | Jan 30, 2023 |
| Dell          | Latitude 7480               | [f3a84b494f](https://linux-hardware.org/?probe=f3a84b494f) | Jan 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1ecef01472](https://linux-hardware.org/?probe=1ecef01472) | Jan 30, 2023 |
| HP            | Pavilion 15                 | [6ceccb3d73](https://linux-hardware.org/?probe=6ceccb3d73) | Jan 30, 2023 |
| Lenovo        | ThinkPad T430 2347G4U       | [5802e6b9b9](https://linux-hardware.org/?probe=5802e6b9b9) | Jan 30, 2023 |
| Dell          | XPS 15 9570                 | [1d06f2715a](https://linux-hardware.org/?probe=1d06f2715a) | Jan 30, 2023 |
| Dell          | Vostro 7620                 | [b6d43b8741](https://linux-hardware.org/?probe=b6d43b8741) | Jan 29, 2023 |
| HP            | Laptop 14-cm0xxx            | [9b93652159](https://linux-hardware.org/?probe=9b93652159) | Jan 29, 2023 |
| Acer          | Aspire V5-573G              | [e253d5b49b](https://linux-hardware.org/?probe=e253d5b49b) | Jan 29, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [32d5472e21](https://linux-hardware.org/?probe=32d5472e21) | Jan 29, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [dd07a46c6a](https://linux-hardware.org/?probe=dd07a46c6a) | Jan 29, 2023 |
| TECNO         | MEGABOOK T1                 | [db0e6c89b4](https://linux-hardware.org/?probe=db0e6c89b4) | Jan 29, 2023 |
| Razer         | Blade 15 (2022) - RZ09-0... | [41d33a9029](https://linux-hardware.org/?probe=41d33a9029) | Jan 29, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [086e08a04b](https://linux-hardware.org/?probe=086e08a04b) | Jan 29, 2023 |
| Dell          | XPS 13 7390                 | [60c03ee1f7](https://linux-hardware.org/?probe=60c03ee1f7) | Jan 29, 2023 |
| HP            | EliteBook 840 G1            | [30549ebd3a](https://linux-hardware.org/?probe=30549ebd3a) | Jan 28, 2023 |
| HP            | Laptop 15-da2xxx            | [8384a02b4b](https://linux-hardware.org/?probe=8384a02b4b) | Jan 28, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [53015adc9d](https://linux-hardware.org/?probe=53015adc9d) | Jan 28, 2023 |
| HP            | ENVY Laptop 17-cg0xxx       | [ed1ce46901](https://linux-hardware.org/?probe=ed1ce46901) | Jan 28, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [844e4e4b2a](https://linux-hardware.org/?probe=844e4e4b2a) | Jan 28, 2023 |
| HP            | ENVY Laptop 17-cg0xxx       | [ab3f84f96b](https://linux-hardware.org/?probe=ab3f84f96b) | Jan 28, 2023 |
| Apple         | MacBookPro11,4              | [8a5423443a](https://linux-hardware.org/?probe=8a5423443a) | Jan 28, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [7e6cf30d81](https://linux-hardware.org/?probe=7e6cf30d81) | Jan 28, 2023 |
| Timi          | A35S                        | [b6611f9b22](https://linux-hardware.org/?probe=b6611f9b22) | Jan 28, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [4a82904f14](https://linux-hardware.org/?probe=4a82904f14) | Jan 28, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [fb7b1bdaf5](https://linux-hardware.org/?probe=fb7b1bdaf5) | Jan 27, 2023 |
| Lenovo        | ThinkPad T450s 20BWS23W0... | [41c82dbadb](https://linux-hardware.org/?probe=41c82dbadb) | Jan 27, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [a69331d2ea](https://linux-hardware.org/?probe=a69331d2ea) | Jan 27, 2023 |
| Acer          | Swift SF314-511             | [c47b08d2a9](https://linux-hardware.org/?probe=c47b08d2a9) | Jan 27, 2023 |
| HONOR         | BMH-WCX9                    | [882bb3b505](https://linux-hardware.org/?probe=882bb3b505) | Jan 27, 2023 |
| MECHREVO      | Code10-7CC6U                | [86e769b2a3](https://linux-hardware.org/?probe=86e769b2a3) | Jan 27, 2023 |
| Dell          | Precision 3550              | [4c42615cef](https://linux-hardware.org/?probe=4c42615cef) | Jan 27, 2023 |
| HUAWEI        | BOHB-WAX9                   | [00e21c8359](https://linux-hardware.org/?probe=00e21c8359) | Jan 27, 2023 |
| Dynabook      | TECRA A50-J                 | [a2ad3f4eb3](https://linux-hardware.org/?probe=a2ad3f4eb3) | Jan 27, 2023 |
| Dynabook      | TECRA A50-J                 | [3921b100b4](https://linux-hardware.org/?probe=3921b100b4) | Jan 27, 2023 |
| ASUSTek       | X550VX                      | [37d2157b37](https://linux-hardware.org/?probe=37d2157b37) | Jan 26, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | [9dfc820ceb](https://linux-hardware.org/?probe=9dfc820ceb) | Jan 26, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | [0168a5cae2](https://linux-hardware.org/?probe=0168a5cae2) | Jan 26, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [4024f7c3bd](https://linux-hardware.org/?probe=4024f7c3bd) | Jan 26, 2023 |
| ASUSTek       | K55VD                       | [b2b19ec3f1](https://linux-hardware.org/?probe=b2b19ec3f1) | Jan 26, 2023 |
| Acer          | Swift SF314-511             | [9c04ff43a3](https://linux-hardware.org/?probe=9c04ff43a3) | Jan 26, 2023 |
| Lenovo        | ThinkPad T495 20NKS01Y00    | [a1dfc58700](https://linux-hardware.org/?probe=a1dfc58700) | Jan 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [303593899d](https://linux-hardware.org/?probe=303593899d) | Jan 26, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HM... | [26f64a2ad0](https://linux-hardware.org/?probe=26f64a2ad0) | Jan 26, 2023 |
| Multilaser    | PC150                       | [1c4ace00d1](https://linux-hardware.org/?probe=1c4ace00d1) | Jan 26, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 D... | [d2a46bd14a](https://linux-hardware.org/?probe=d2a46bd14a) | Jan 26, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | [8725d530e5](https://linux-hardware.org/?probe=8725d530e5) | Jan 26, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [ea142e4848](https://linux-hardware.org/?probe=ea142e4848) | Jan 25, 2023 |
| HP            | EliteBook 2540p             | [f03240c746](https://linux-hardware.org/?probe=f03240c746) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [af63cfc79a](https://linux-hardware.org/?probe=af63cfc79a) | Jan 25, 2023 |
| Clevo         | M815P                       | [cfc5f6689f](https://linux-hardware.org/?probe=cfc5f6689f) | Jan 25, 2023 |
| MSI           | GL63 8RC                    | [138e8de541](https://linux-hardware.org/?probe=138e8de541) | Jan 25, 2023 |
| Acer          | Aspire A315-59              | [33292253d0](https://linux-hardware.org/?probe=33292253d0) | Jan 25, 2023 |
| HP            | ZBook Power 15.6 inch G9... | [dd2f21ab84](https://linux-hardware.org/?probe=dd2f21ab84) | Jan 25, 2023 |
| Dynabook      | TECRA A50-J                 | [2f24f18672](https://linux-hardware.org/?probe=2f24f18672) | Jan 25, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [993ba3e73b](https://linux-hardware.org/?probe=993ba3e73b) | Jan 25, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [aa6488b6b8](https://linux-hardware.org/?probe=aa6488b6b8) | Jan 25, 2023 |
| Fujitsu Si... | AMILO Notebook Xa 3530      | [e8384494a3](https://linux-hardware.org/?probe=e8384494a3) | Jan 25, 2023 |
| Dell          | Inspiron 5402               | [d8df4aafe8](https://linux-hardware.org/?probe=d8df4aafe8) | Jan 25, 2023 |
| Dell          | Inspiron 5468               | [3e59c1f38b](https://linux-hardware.org/?probe=3e59c1f38b) | Jan 25, 2023 |
| Acer          | Nitro AN515-42              | [cb02367642](https://linux-hardware.org/?probe=cb02367642) | Jan 25, 2023 |
| Dell          | Latitude 5420               | [cd6dc3695e](https://linux-hardware.org/?probe=cd6dc3695e) | Jan 24, 2023 |
| Dell          | Latitude 5520               | [662284824b](https://linux-hardware.org/?probe=662284824b) | Jan 24, 2023 |
| HP            | ProBook 6570b               | [841250ba59](https://linux-hardware.org/?probe=841250ba59) | Jan 24, 2023 |
| Dell          | Latitude E6410              | [854634fb32](https://linux-hardware.org/?probe=854634fb32) | Jan 24, 2023 |
| Dell          | Latitude E6410              | [a5edbef8d2](https://linux-hardware.org/?probe=a5edbef8d2) | Jan 24, 2023 |
| Lenovo        | ThinkPad T500 2082BPG       | [08a30fd24c](https://linux-hardware.org/?probe=08a30fd24c) | Jan 24, 2023 |
| Lenovo        | ThinkPad E15 20RD0011RT     | [3fb25133ec](https://linux-hardware.org/?probe=3fb25133ec) | Jan 24, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [c2226035ce](https://linux-hardware.org/?probe=c2226035ce) | Jan 24, 2023 |
| Google        | Treeya                      | [27a381272a](https://linux-hardware.org/?probe=27a381272a) | Jan 24, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [a227de29c5](https://linux-hardware.org/?probe=a227de29c5) | Jan 24, 2023 |
| Dell          | Precision 3551              | [1338d3df20](https://linux-hardware.org/?probe=1338d3df20) | Jan 23, 2023 |
| HP            | ProBook 430 G8 Notebook ... | [335275777a](https://linux-hardware.org/?probe=335275777a) | Jan 23, 2023 |
| Dell          | Latitude 7490               | [e40bb2f01f](https://linux-hardware.org/?probe=e40bb2f01f) | Jan 23, 2023 |
| Dell          | Latitude 7490               | [31789ae630](https://linux-hardware.org/?probe=31789ae630) | Jan 23, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [091effd2ac](https://linux-hardware.org/?probe=091effd2ac) | Jan 23, 2023 |
| Apple         | MacBookPro9,1               | [0a597ba033](https://linux-hardware.org/?probe=0a597ba033) | Jan 23, 2023 |
| Lenovo        | Erazer Z500 20226           | [6e7a21c6d5](https://linux-hardware.org/?probe=6e7a21c6d5) | Jan 23, 2023 |
| Lenovo        | Erazer Z500 20226           | [7d6077c27c](https://linux-hardware.org/?probe=7d6077c27c) | Jan 23, 2023 |
| Apple         | MacBookPro9,1               | [90884b19a9](https://linux-hardware.org/?probe=90884b19a9) | Jan 23, 2023 |
| Lenovo        | ThinkPad P50 20EQS12Q3M     | [e46b5a8b46](https://linux-hardware.org/?probe=e46b5a8b46) | Jan 23, 2023 |
| Dell          | Latitude E6500              | [ba7c36fe15](https://linux-hardware.org/?probe=ba7c36fe15) | Jan 23, 2023 |
| Dynabook      | TECRA A50-J                 | [689fe06d4d](https://linux-hardware.org/?probe=689fe06d4d) | Jan 23, 2023 |
| Dynabook      | TECRA A50-J                 | [92690b43cd](https://linux-hardware.org/?probe=92690b43cd) | Jan 23, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [d03b7c0a68](https://linux-hardware.org/?probe=d03b7c0a68) | Jan 22, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [07005e3e32](https://linux-hardware.org/?probe=07005e3e32) | Jan 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | [d999192dbf](https://linux-hardware.org/?probe=d999192dbf) | Jan 22, 2023 |
| HP            | EliteBook 820 G3            | [3edd4ab0dc](https://linux-hardware.org/?probe=3edd4ab0dc) | Jan 22, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [523d0331a1](https://linux-hardware.org/?probe=523d0331a1) | Jan 21, 2023 |
| HP            | Victus by Gaming Laptop ... | [0aa98390a7](https://linux-hardware.org/?probe=0aa98390a7) | Jan 21, 2023 |
| Acer          | Predator G9-591             | [0544a1b07c](https://linux-hardware.org/?probe=0544a1b07c) | Jan 21, 2023 |
| Dell          | XPS 9315                    | [9dfb19b7c1](https://linux-hardware.org/?probe=9dfb19b7c1) | Jan 21, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [e8a0c0066b](https://linux-hardware.org/?probe=e8a0c0066b) | Jan 21, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [adeb24c41e](https://linux-hardware.org/?probe=adeb24c41e) | Jan 21, 2023 |
| Dell          | G5 5587                     | [96ca22c550](https://linux-hardware.org/?probe=96ca22c550) | Jan 21, 2023 |
| Dell          | G5 5587                     | [a070a8ba69](https://linux-hardware.org/?probe=a070a8ba69) | Jan 21, 2023 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [c228c064b7](https://linux-hardware.org/?probe=c228c064b7) | Jan 20, 2023 |
| Dell          | Venue 8 Pro 5830            | [4f815d5b4f](https://linux-hardware.org/?probe=4f815d5b4f) | Jan 20, 2023 |
| Acer          | Aspire A315-42G             | [ed4c536efa](https://linux-hardware.org/?probe=ed4c536efa) | Jan 20, 2023 |
| Lenovo        | ThinkPad T490 20N3S0E000    | [d324a863a5](https://linux-hardware.org/?probe=d324a863a5) | Jan 20, 2023 |
| Acer          | Aspire A515-45              | [9d5faff505](https://linux-hardware.org/?probe=9d5faff505) | Jan 20, 2023 |
| MSI           | GS66 Stealth 10UE           | [d5a2a6aaa8](https://linux-hardware.org/?probe=d5a2a6aaa8) | Jan 19, 2023 |
| SLIMBOOK      | TITAN                       | [15c0522754](https://linux-hardware.org/?probe=15c0522754) | Jan 19, 2023 |
| SLIMBOOK      | TITAN                       | [e81652a68c](https://linux-hardware.org/?probe=e81652a68c) | Jan 19, 2023 |
| Dell          | Precision 3551              | [4ff5a0ab8d](https://linux-hardware.org/?probe=4ff5a0ab8d) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [0f079e1dc7](https://linux-hardware.org/?probe=0f079e1dc7) | Jan 19, 2023 |
| Acer          | Aspire A315-23              | [90049e4bb7](https://linux-hardware.org/?probe=90049e4bb7) | Jan 19, 2023 |
| Acer          | Nitro AN515-42              | [d6a24ede85](https://linux-hardware.org/?probe=d6a24ede85) | Jan 19, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [6a47296f0c](https://linux-hardware.org/?probe=6a47296f0c) | Jan 19, 2023 |
| Dell          | Latitude 3410               | [187aebc2cd](https://linux-hardware.org/?probe=187aebc2cd) | Jan 19, 2023 |
| Intel Clie... | LAPRC510                    | [6d570a1aee](https://linux-hardware.org/?probe=6d570a1aee) | Jan 19, 2023 |
| ASUSTek       | X455LF                      | [9995b86c04](https://linux-hardware.org/?probe=9995b86c04) | Jan 18, 2023 |
| HP            | Victus by Gaming Laptop ... | [533d99e2f1](https://linux-hardware.org/?probe=533d99e2f1) | Jan 18, 2023 |
| Lenovo        | ThinkPad E15 20RD0011RT     | [d27ca45841](https://linux-hardware.org/?probe=d27ca45841) | Jan 18, 2023 |
| Dell          | Precision 3561              | [9528d74be6](https://linux-hardware.org/?probe=9528d74be6) | Jan 18, 2023 |
| Dell          | Precision 3561              | [5f23addbde](https://linux-hardware.org/?probe=5f23addbde) | Jan 18, 2023 |
| Acer          | Swift SFX14-41G             | [1b916fe30d](https://linux-hardware.org/?probe=1b916fe30d) | Jan 18, 2023 |
| Lenovo        | Yoga 500-14IHW 80N5         | [e233e8d6d2](https://linux-hardware.org/?probe=e233e8d6d2) | Jan 18, 2023 |
| Acer          | Nitro AN515-54              | [4a997fa99d](https://linux-hardware.org/?probe=4a997fa99d) | Jan 17, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [a81a940d33](https://linux-hardware.org/?probe=a81a940d33) | Jan 17, 2023 |
| HP            | Laptop 17-ca0xxx            | [a8fbe01fc5](https://linux-hardware.org/?probe=a8fbe01fc5) | Jan 17, 2023 |
| Acer          | Aspire A315-59              | [469c40ec75](https://linux-hardware.org/?probe=469c40ec75) | Jan 17, 2023 |
| Timi          | Xiaomi NoteBook Pro         | [681de2b0c1](https://linux-hardware.org/?probe=681de2b0c1) | Jan 17, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [7b36d7e8eb](https://linux-hardware.org/?probe=7b36d7e8eb) | Jan 17, 2023 |
| Timi          | Xiaomi NoteBook Pro         | [f1ee502754](https://linux-hardware.org/?probe=f1ee502754) | Jan 17, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [0d91852ebf](https://linux-hardware.org/?probe=0d91852ebf) | Jan 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c16356f056](https://linux-hardware.org/?probe=c16356f056) | Jan 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [70b8007dcc](https://linux-hardware.org/?probe=70b8007dcc) | Jan 17, 2023 |
| Acer          | Aspire AV14-51              | [596219796d](https://linux-hardware.org/?probe=596219796d) | Jan 17, 2023 |
| HUAWEI        | BOHB-WAX9                   | [b39c4fc9b7](https://linux-hardware.org/?probe=b39c4fc9b7) | Jan 16, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | [1c81e8c322](https://linux-hardware.org/?probe=1c81e8c322) | Jan 16, 2023 |
| Dell          | Inspiron 11 - 3147          | [af542a44ad](https://linux-hardware.org/?probe=af542a44ad) | Jan 16, 2023 |
| PC Special... | Recoil II RTX               | [33850c8810](https://linux-hardware.org/?probe=33850c8810) | Jan 16, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [b53dd87f87](https://linux-hardware.org/?probe=b53dd87f87) | Jan 16, 2023 |
| Schenker      | XMG CORE 15 (M22)           | [6c2b631f12](https://linux-hardware.org/?probe=6c2b631f12) | Jan 16, 2023 |
| HP            | 15                          | [ae082994e2](https://linux-hardware.org/?probe=ae082994e2) | Jan 16, 2023 |
| Acer          | Nitro AN515-46              | [1de96d005a](https://linux-hardware.org/?probe=1de96d005a) | Jan 16, 2023 |
| Acer          | Nitro AN515-46              | [f0eab1c81a](https://linux-hardware.org/?probe=f0eab1c81a) | Jan 16, 2023 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [e1aa5d3186](https://linux-hardware.org/?probe=e1aa5d3186) | Jan 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [1a51848ffb](https://linux-hardware.org/?probe=1a51848ffb) | Jan 16, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [b36eb94e80](https://linux-hardware.org/?probe=b36eb94e80) | Jan 16, 2023 |
| HP            | 255 G6 Notebook PC          | [4d2e9f3ee4](https://linux-hardware.org/?probe=4d2e9f3ee4) | Jan 16, 2023 |
| Lenovo        | ThinkPad T440s 20AQ0069G... | [cb2e9f2623](https://linux-hardware.org/?probe=cb2e9f2623) | Jan 16, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [a38eb750aa](https://linux-hardware.org/?probe=a38eb750aa) | Jan 16, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [9ac2f0ab83](https://linux-hardware.org/?probe=9ac2f0ab83) | Jan 15, 2023 |
| HP            | EliteBook 840 G2            | [4850c49a4a](https://linux-hardware.org/?probe=4850c49a4a) | Jan 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [448ae92dc8](https://linux-hardware.org/?probe=448ae92dc8) | Jan 15, 2023 |
| HP            | EliteBook 840 G2            | [972e3e026a](https://linux-hardware.org/?probe=972e3e026a) | Jan 15, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [57d99b139f](https://linux-hardware.org/?probe=57d99b139f) | Jan 15, 2023 |
| Acer          | Aspire A515-43              | [cefbe7ee6e](https://linux-hardware.org/?probe=cefbe7ee6e) | Jan 15, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [fcc6481e2a](https://linux-hardware.org/?probe=fcc6481e2a) | Jan 15, 2023 |
| HP            | Pavilion Laptop 14-bk0xx    | [ebe90b5052](https://linux-hardware.org/?probe=ebe90b5052) | Jan 15, 2023 |
| Dell          | Inspiron N5110              | [20625ce99d](https://linux-hardware.org/?probe=20625ce99d) | Jan 14, 2023 |
| Olivetti      | Olibook P55-431W850-8G50... | [fe5c9c2425](https://linux-hardware.org/?probe=fe5c9c2425) | Jan 14, 2023 |
| Olivetti      | Olibook P55-431W850-8G50... | [649546bc61](https://linux-hardware.org/?probe=649546bc61) | Jan 14, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [86fff559f5](https://linux-hardware.org/?probe=86fff559f5) | Jan 14, 2023 |
| HP            | Pavilion Laptop 14-bk0xx    | [bcbf941284](https://linux-hardware.org/?probe=bcbf941284) | Jan 14, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [efffe2d61b](https://linux-hardware.org/?probe=efffe2d61b) | Jan 14, 2023 |
| MSI           | PS63 Modern 8RC             | [e55e0d9d0a](https://linux-hardware.org/?probe=e55e0d9d0a) | Jan 14, 2023 |
| HP            | ZBook 15 G4                 | [3325b8ab60](https://linux-hardware.org/?probe=3325b8ab60) | Jan 14, 2023 |
| System76      | Oryx Pro                    | [f706b667bb](https://linux-hardware.org/?probe=f706b667bb) | Jan 14, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [5047da7461](https://linux-hardware.org/?probe=5047da7461) | Jan 14, 2023 |
| Acer          | Swift SF314-43              | [e292f699eb](https://linux-hardware.org/?probe=e292f699eb) | Jan 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [9096450d56](https://linux-hardware.org/?probe=9096450d56) | Jan 14, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [bbf1dabe59](https://linux-hardware.org/?probe=bbf1dabe59) | Jan 14, 2023 |
| Dell          | Latitude 7430               | [9caa5939ef](https://linux-hardware.org/?probe=9caa5939ef) | Jan 13, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [61c432b134](https://linux-hardware.org/?probe=61c432b134) | Jan 13, 2023 |
| Acer          | Nitro AN515-44              | [b2c96e31d9](https://linux-hardware.org/?probe=b2c96e31d9) | Jan 13, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [810b2daeef](https://linux-hardware.org/?probe=810b2daeef) | Jan 13, 2023 |
| Toshiba       | Satellite L855D             | [0606d04520](https://linux-hardware.org/?probe=0606d04520) | Jan 13, 2023 |
| Dell          | Inspiron 5721               | [b9435f9f7d](https://linux-hardware.org/?probe=b9435f9f7d) | Jan 13, 2023 |
| Acer          | Predator PH315-52           | [c6a710b940](https://linux-hardware.org/?probe=c6a710b940) | Jan 13, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [64c403ce6d](https://linux-hardware.org/?probe=64c403ce6d) | Jan 13, 2023 |
| Lenovo        | ThinkPad T495s 20QKS2R40... | [28d821da5f](https://linux-hardware.org/?probe=28d821da5f) | Jan 13, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [f9d244586a](https://linux-hardware.org/?probe=f9d244586a) | Jan 13, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [05899ebb86](https://linux-hardware.org/?probe=05899ebb86) | Jan 13, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [033a92981f](https://linux-hardware.org/?probe=033a92981f) | Jan 13, 2023 |
| Acer          | Predator PT515-51           | [150f12dceb](https://linux-hardware.org/?probe=150f12dceb) | Jan 12, 2023 |
| Dell          | G15 5520                    | [1aeaf74f9a](https://linux-hardware.org/?probe=1aeaf74f9a) | Jan 12, 2023 |
| HP            | ProBook 450 G6              | [f675188c46](https://linux-hardware.org/?probe=f675188c46) | Jan 12, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [e9783891d1](https://linux-hardware.org/?probe=e9783891d1) | Jan 12, 2023 |
| Acer          | Nitro AN517-42              | [c8440739f9](https://linux-hardware.org/?probe=c8440739f9) | Jan 12, 2023 |
| Dell          | Latitude E5550              | [0b14eb18d9](https://linux-hardware.org/?probe=0b14eb18d9) | Jan 12, 2023 |
| Lenovo        | ThinkPad T430 2349W1C       | [1f310a8a2e](https://linux-hardware.org/?probe=1f310a8a2e) | Jan 12, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [fad743f278](https://linux-hardware.org/?probe=fad743f278) | Jan 12, 2023 |
| HUAWEI        | KLVL-WXXW                   | [1270cfda4e](https://linux-hardware.org/?probe=1270cfda4e) | Jan 11, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [8c1eb7fc02](https://linux-hardware.org/?probe=8c1eb7fc02) | Jan 11, 2023 |
| Dell          | Latitude E5550              | [5e76d378f9](https://linux-hardware.org/?probe=5e76d378f9) | Jan 11, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [ec0f3564ed](https://linux-hardware.org/?probe=ec0f3564ed) | Jan 11, 2023 |
| Acer          | Aspire A315-59              | [a436e3e89f](https://linux-hardware.org/?probe=a436e3e89f) | Jan 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [c79ad1fc10](https://linux-hardware.org/?probe=c79ad1fc10) | Jan 11, 2023 |
| Acer          | Predator G9-591             | [aa9794813e](https://linux-hardware.org/?probe=aa9794813e) | Jan 11, 2023 |
| Dell          | Latitude E7440              | [bfdc9dfc63](https://linux-hardware.org/?probe=bfdc9dfc63) | Jan 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [25090a9dcb](https://linux-hardware.org/?probe=25090a9dcb) | Jan 11, 2023 |
| MSI           | Modern 14 B4MW              | [815ee96451](https://linux-hardware.org/?probe=815ee96451) | Jan 11, 2023 |
| HP            | Pavilion Laptop 13-bb0xx... | [790736a10e](https://linux-hardware.org/?probe=790736a10e) | Jan 11, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [fdb726b276](https://linux-hardware.org/?probe=fdb726b276) | Jan 11, 2023 |
| Infinix       | INBOOK X2                   | [11aac46bdc](https://linux-hardware.org/?probe=11aac46bdc) | Jan 10, 2023 |
| ASUSTek       | X510UAR                     | [dc3e0fffe7](https://linux-hardware.org/?probe=dc3e0fffe7) | Jan 10, 2023 |
| ASUSTek       | X510UAR                     | [53d6bec0e8](https://linux-hardware.org/?probe=53d6bec0e8) | Jan 10, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [62ddf88d2d](https://linux-hardware.org/?probe=62ddf88d2d) | Jan 10, 2023 |
| Lenovo        | ThinkPad T590 20N5S4R800    | [51d6d75e64](https://linux-hardware.org/?probe=51d6d75e64) | Jan 10, 2023 |
| ASUSTek       | FX503VD                     | [c3a958527e](https://linux-hardware.org/?probe=c3a958527e) | Jan 10, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [37b5b1648e](https://linux-hardware.org/?probe=37b5b1648e) | Jan 10, 2023 |
| Lenovo        | ThinkPad P53 20QNS00X00     | [e16ef8937b](https://linux-hardware.org/?probe=e16ef8937b) | Jan 09, 2023 |
| Alienware     | m15 Ryzen Ed. R5            | [ef83299ad4](https://linux-hardware.org/?probe=ef83299ad4) | Jan 09, 2023 |
| Chuwi         | GemiBook                    | [918dc5f283](https://linux-hardware.org/?probe=918dc5f283) | Jan 09, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [ad39556257](https://linux-hardware.org/?probe=ad39556257) | Jan 09, 2023 |
| HP            | EliteBook 850 G4            | [e6cb9446f5](https://linux-hardware.org/?probe=e6cb9446f5) | Jan 09, 2023 |
| HP            | Laptop 15-da1xxx            | [2fa89881b4](https://linux-hardware.org/?probe=2fa89881b4) | Jan 09, 2023 |
| Dell          | XPS 15 9520                 | [2e13f150e6](https://linux-hardware.org/?probe=2e13f150e6) | Jan 09, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [6e756926b8](https://linux-hardware.org/?probe=6e756926b8) | Jan 09, 2023 |
| Apple         | MacBookPro11,1              | [92a4be502c](https://linux-hardware.org/?probe=92a4be502c) | Jan 09, 2023 |
| Acer          | Iconia W700                 | [bcfec36896](https://linux-hardware.org/?probe=bcfec36896) | Jan 09, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HM... | [8be13470fb](https://linux-hardware.org/?probe=8be13470fb) | Jan 09, 2023 |
| Lenovo        | IdeaPad 720-15IKB 81AG      | [8c76c72880](https://linux-hardware.org/?probe=8c76c72880) | Jan 08, 2023 |
| HP            | ProBook 6465b               | [336f10e70b](https://linux-hardware.org/?probe=336f10e70b) | Jan 08, 2023 |
| ASUSTek       | X541UVK                     | [50e9caee7f](https://linux-hardware.org/?probe=50e9caee7f) | Jan 08, 2023 |
| Lenovo        | V330-15IKB 81AX             | [1ca4c751d8](https://linux-hardware.org/?probe=1ca4c751d8) | Jan 08, 2023 |
| Framework     | Laptop                      | [0c13e3ab8d](https://linux-hardware.org/?probe=0c13e3ab8d) | Jan 08, 2023 |
| Acer          | Aspire A315-41              | [b4ed141fd3](https://linux-hardware.org/?probe=b4ed141fd3) | Jan 08, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CR... | [ff783dac11](https://linux-hardware.org/?probe=ff783dac11) | Jan 08, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D4C... | [d2e10cee5b](https://linux-hardware.org/?probe=d2e10cee5b) | Jan 08, 2023 |
| Dell          | Latitude 3450               | [e4e8bee1cb](https://linux-hardware.org/?probe=e4e8bee1cb) | Jan 08, 2023 |
| HP            | EliteBook 745 G5            | [b732d98167](https://linux-hardware.org/?probe=b732d98167) | Jan 08, 2023 |
| Acer          | Aspire A715-42G             | [206359e4ad](https://linux-hardware.org/?probe=206359e4ad) | Jan 08, 2023 |
| ASUSTek       | ROG Strix G512LI_G512LI     | [f75fea559f](https://linux-hardware.org/?probe=f75fea559f) | Jan 08, 2023 |
| Acer          | Aspire A715-42G             | [eed9db8255](https://linux-hardware.org/?probe=eed9db8255) | Jan 08, 2023 |
| Lenovo        | ThinkPad P53 20QNS00X00     | [6290949f56](https://linux-hardware.org/?probe=6290949f56) | Jan 08, 2023 |
| Dell          | Vostro 15-3568              | [a6c731c83b](https://linux-hardware.org/?probe=a6c731c83b) | Jan 08, 2023 |
| Dell          | Inspiron 5567               | [a43647cad6](https://linux-hardware.org/?probe=a43647cad6) | Jan 08, 2023 |
| Acer          | Predator PT515-51           | [a33d9c5a74](https://linux-hardware.org/?probe=a33d9c5a74) | Jan 07, 2023 |
| HP            | EliteBook 850 G6            | [595e6fa89a](https://linux-hardware.org/?probe=595e6fa89a) | Jan 07, 2023 |
| Dell          | XPS 15 9510                 | [f0a688060c](https://linux-hardware.org/?probe=f0a688060c) | Jan 07, 2023 |
| Lenovo        | ThinkPad T530 2392CTO       | [8c1cf48875](https://linux-hardware.org/?probe=8c1cf48875) | Jan 07, 2023 |
| Framework     | Laptop                      | [cfabfdec3c](https://linux-hardware.org/?probe=cfabfdec3c) | Jan 07, 2023 |
| System76      | Lemur Pro                   | [36156d9aa7](https://linux-hardware.org/?probe=36156d9aa7) | Jan 07, 2023 |
| Dell          | Inspiron 13 5320            | [0007a36030](https://linux-hardware.org/?probe=0007a36030) | Jan 07, 2023 |
| HP            | EliteBook 840 G3            | [667330c83f](https://linux-hardware.org/?probe=667330c83f) | Jan 07, 2023 |
| HP            | ZBook Studio G5             | [dfd35ce9ca](https://linux-hardware.org/?probe=dfd35ce9ca) | Jan 07, 2023 |
| Alienware     | m15 Ryzen Ed. R5            | [bf4c8770e7](https://linux-hardware.org/?probe=bf4c8770e7) | Jan 07, 2023 |
| Dell          | Inspiron 7577               | [ff95fa094b](https://linux-hardware.org/?probe=ff95fa094b) | Jan 06, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [1fc8d104f7](https://linux-hardware.org/?probe=1fc8d104f7) | Jan 06, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [0a6589c07d](https://linux-hardware.org/?probe=0a6589c07d) | Jan 06, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [ab29e81efd](https://linux-hardware.org/?probe=ab29e81efd) | Jan 06, 2023 |
| HP            | Laptop 15s-eq2xxx           | [684653e302](https://linux-hardware.org/?probe=684653e302) | Jan 06, 2023 |
| Acer          | Aspire A515-47              | [896288776d](https://linux-hardware.org/?probe=896288776d) | Jan 06, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [9946b25232](https://linux-hardware.org/?probe=9946b25232) | Jan 06, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [fd5120fea6](https://linux-hardware.org/?probe=fd5120fea6) | Jan 06, 2023 |
| Lenovo        | ThinkPad T430 2349KB4       | [4546ecbe85](https://linux-hardware.org/?probe=4546ecbe85) | Jan 06, 2023 |
| Chuwi         | HeroBook Air                | [58434d2c3c](https://linux-hardware.org/?probe=58434d2c3c) | Jan 06, 2023 |
| Dell          | XPS 15 9520                 | [ec6743fa1b](https://linux-hardware.org/?probe=ec6743fa1b) | Jan 06, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [c84d3b6b03](https://linux-hardware.org/?probe=c84d3b6b03) | Jan 06, 2023 |
| Dell          | G15 5525                    | [2c61cbc942](https://linux-hardware.org/?probe=2c61cbc942) | Jan 06, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [cddb2a7b81](https://linux-hardware.org/?probe=cddb2a7b81) | Jan 06, 2023 |
| Lenovo        | Z50-75 80EC                 | [7fe70dc4c8](https://linux-hardware.org/?probe=7fe70dc4c8) | Jan 06, 2023 |
| Apple         | MacBookPro12,1              | [0cca8fbbb6](https://linux-hardware.org/?probe=0cca8fbbb6) | Jan 05, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [c47405aaf4](https://linux-hardware.org/?probe=c47405aaf4) | Jan 05, 2023 |
| Lenovo        | ThinkPad X220 4290KJ6       | [8296e61afd](https://linux-hardware.org/?probe=8296e61afd) | Jan 05, 2023 |
| Acer          | Predator PT515-51           | [77651b16db](https://linux-hardware.org/?probe=77651b16db) | Jan 05, 2023 |
| Lenovo        | ThinkPad T460 20FMS49100    | [28af5637ef](https://linux-hardware.org/?probe=28af5637ef) | Jan 05, 2023 |
| Lenovo        | ThinkPad T460 20FMS49100    | [4605f322cb](https://linux-hardware.org/?probe=4605f322cb) | Jan 05, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [31f9cd0972](https://linux-hardware.org/?probe=31f9cd0972) | Jan 05, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [a2ec6616aa](https://linux-hardware.org/?probe=a2ec6616aa) | Jan 05, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [8ac0b43549](https://linux-hardware.org/?probe=8ac0b43549) | Jan 05, 2023 |
| MSI           | Modern 14 B4MW              | [b7855a84cf](https://linux-hardware.org/?probe=b7855a84cf) | Jan 05, 2023 |
| HP            | EliteBook 840 G5 NOTEBOO... | [343d0f4c48](https://linux-hardware.org/?probe=343d0f4c48) | Jan 04, 2023 |
| ASUSTek       | X510UAR                     | [39f45e87d1](https://linux-hardware.org/?probe=39f45e87d1) | Jan 04, 2023 |
| ASUSTek       | X510UAR                     | [2f4bb5b17d](https://linux-hardware.org/?probe=2f4bb5b17d) | Jan 04, 2023 |
| Chuwi         | GemiBook Pro                | [272d23ec5d](https://linux-hardware.org/?probe=272d23ec5d) | Jan 04, 2023 |
| HP            | EliteBook 840 G3            | [76f2ef98b9](https://linux-hardware.org/?probe=76f2ef98b9) | Jan 04, 2023 |
| Acer          | Swift SF314-43              | [50d8f0c1cb](https://linux-hardware.org/?probe=50d8f0c1cb) | Jan 04, 2023 |
| HP            | Notebook                    | [679c0bfbe8](https://linux-hardware.org/?probe=679c0bfbe8) | Jan 04, 2023 |
| HP            | EliteBook 845 14 inch G9... | [26826e3c23](https://linux-hardware.org/?probe=26826e3c23) | Jan 04, 2023 |
| HP            | ZBook 15 G3                 | [6a38362bbe](https://linux-hardware.org/?probe=6a38362bbe) | Jan 04, 2023 |
| Unknown       | Unknown                     | [b363093f89](https://linux-hardware.org/?probe=b363093f89) | Jan 04, 2023 |
| Acer          | Nitro AN515-45              | [5741654cdc](https://linux-hardware.org/?probe=5741654cdc) | Jan 04, 2023 |
| MSI           | Modern 14 B11MOU            | [036ae164e8](https://linux-hardware.org/?probe=036ae164e8) | Jan 04, 2023 |
| Clevo         | M815P                       | [7f1503c5e6](https://linux-hardware.org/?probe=7f1503c5e6) | Jan 03, 2023 |
| MSI           | Katana GF66 11SC            | [d788f444ff](https://linux-hardware.org/?probe=d788f444ff) | Jan 03, 2023 |
| HP            | ProBook 6570b               | [875054c6d7](https://linux-hardware.org/?probe=875054c6d7) | Jan 03, 2023 |
| ASUSTek       | X453MA                      | [1584b0616c](https://linux-hardware.org/?probe=1584b0616c) | Jan 03, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [40af3a30ca](https://linux-hardware.org/?probe=40af3a30ca) | Jan 03, 2023 |
| Lenovo        | ThinkPad T590 20N5S2NC1V    | [c621679405](https://linux-hardware.org/?probe=c621679405) | Jan 03, 2023 |
| HP            | 240 G8 Notebook PC          | [a316608c78](https://linux-hardware.org/?probe=a316608c78) | Jan 03, 2023 |
| MSI           | Katana GF66 11SC            | [5a078a161f](https://linux-hardware.org/?probe=5a078a161f) | Jan 03, 2023 |
| Toshiba       | Satellite C50-A             | [9b02393248](https://linux-hardware.org/?probe=9b02393248) | Jan 02, 2023 |
| HP            | Notebook                    | [530e6cfeb9](https://linux-hardware.org/?probe=530e6cfeb9) | Jan 02, 2023 |
| Clevo         | M815P                       | [034cecc238](https://linux-hardware.org/?probe=034cecc238) | Jan 02, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [daeb060f32](https://linux-hardware.org/?probe=daeb060f32) | Jan 02, 2023 |
| Acer          | Aspire A315-31              | [4a79c65764](https://linux-hardware.org/?probe=4a79c65764) | Jan 02, 2023 |
| ASUSTek       | X756UXK                     | [f0bc632c50](https://linux-hardware.org/?probe=f0bc632c50) | Jan 02, 2023 |
| Dell          | Latitude 7410               | [acb8ce902e](https://linux-hardware.org/?probe=acb8ce902e) | Jan 01, 2023 |
| Acer          | Aspire A315-59              | [f84116ec07](https://linux-hardware.org/?probe=f84116ec07) | Jan 01, 2023 |
| Fujitsu       | LIFEBOOK U749               | [c09072c09f](https://linux-hardware.org/?probe=c09072c09f) | Jan 01, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [f438866c0d](https://linux-hardware.org/?probe=f438866c0d) | Jan 01, 2023 |
| Lenovo        | ThinkPad X270 20K60018GE    | [a92939c1f5](https://linux-hardware.org/?probe=a92939c1f5) | Jan 01, 2023 |
| Lenovo        | ThinkPad X390 20Q00051GE    | [5b3d1b750d](https://linux-hardware.org/?probe=5b3d1b750d) | Dec 31, 2022 |
| Valve         | Jupiter                     | [c0fb48bccb](https://linux-hardware.org/?probe=c0fb48bccb) | Dec 31, 2022 |
| System76      | Oryx Pro                    | [0d65e57758](https://linux-hardware.org/?probe=0d65e57758) | Dec 31, 2022 |
| Lenovo        | ThinkPad X390 20Q00051GE    | [775096be09](https://linux-hardware.org/?probe=775096be09) | Dec 31, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [322cf5484d](https://linux-hardware.org/?probe=322cf5484d) | Dec 31, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [5fbe1632b0](https://linux-hardware.org/?probe=5fbe1632b0) | Dec 31, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [5a479fed95](https://linux-hardware.org/?probe=5a479fed95) | Dec 31, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [591d985e85](https://linux-hardware.org/?probe=591d985e85) | Dec 31, 2022 |
| HP            | Pavilion dv6700             | [4b3b106bee](https://linux-hardware.org/?probe=4b3b106bee) | Dec 30, 2022 |
| MACHENIKE     | MACHCREATOR-16              | [f7ed4a6609](https://linux-hardware.org/?probe=f7ed4a6609) | Dec 30, 2022 |
| Dell          | Inspiron 3421               | [d2cd50a2a6](https://linux-hardware.org/?probe=d2cd50a2a6) | Dec 30, 2022 |
| Timi          | A35S                        | [c62c9ae956](https://linux-hardware.org/?probe=c62c9ae956) | Dec 30, 2022 |
| Dell          | Inspiron 3421               | [ae7d821823](https://linux-hardware.org/?probe=ae7d821823) | Dec 30, 2022 |
| Dell          | XPS 15 9520                 | [19b4bfd852](https://linux-hardware.org/?probe=19b4bfd852) | Dec 30, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [68b3b51892](https://linux-hardware.org/?probe=68b3b51892) | Dec 30, 2022 |
| MSI           | GP72MVR 7RFX                | [cefedef93c](https://linux-hardware.org/?probe=cefedef93c) | Dec 30, 2022 |
| MSI           | Stealth GS66 12UGS          | [da812c8fa2](https://linux-hardware.org/?probe=da812c8fa2) | Dec 30, 2022 |
| Lenovo        | Z70-80 80FG                 | [16419f6991](https://linux-hardware.org/?probe=16419f6991) | Dec 30, 2022 |
| Lenovo        | Z70-80 80FG                 | [4386242be1](https://linux-hardware.org/?probe=4386242be1) | Dec 30, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [770c5eee84](https://linux-hardware.org/?probe=770c5eee84) | Dec 30, 2022 |
| Dell          | XPS 15 9570                 | [cc31efb32d](https://linux-hardware.org/?probe=cc31efb32d) | Dec 30, 2022 |
| Dell          | Inspiron N4050              | [b34f09894d](https://linux-hardware.org/?probe=b34f09894d) | Dec 29, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [ed5315b768](https://linux-hardware.org/?probe=ed5315b768) | Dec 29, 2022 |
| MACHENIKE     | MACHCREATOR-16              | [3c627bc707](https://linux-hardware.org/?probe=3c627bc707) | Dec 29, 2022 |
| MACHENIKE     | MACHCREATOR-16              | [b246257695](https://linux-hardware.org/?probe=b246257695) | Dec 29, 2022 |
| HP            | Stream Notebook PC 13       | [2154a332b0](https://linux-hardware.org/?probe=2154a332b0) | Dec 29, 2022 |
| HP            | ZBook Fury 16 G9 Mobile ... | [6c67e1435e](https://linux-hardware.org/?probe=6c67e1435e) | Dec 29, 2022 |
| Lenovo        | ThinkPad T480 20L5001DUS    | [51bb19bbf2](https://linux-hardware.org/?probe=51bb19bbf2) | Dec 29, 2022 |
| Lenovo        | ThinkPad T15 Gen 1 20S7S... | [74f8dcfbb4](https://linux-hardware.org/?probe=74f8dcfbb4) | Dec 29, 2022 |
| Schenker      | VISION 16 Pro (L22)         | [bbd6e1daf5](https://linux-hardware.org/?probe=bbd6e1daf5) | Dec 29, 2022 |
| Acer          | Predator PH315-53           | [d5d0e740c1](https://linux-hardware.org/?probe=d5d0e740c1) | Dec 29, 2022 |
| Schenker      | VISION 16 Pro (L22)         | [2412713729](https://linux-hardware.org/?probe=2412713729) | Dec 29, 2022 |
| Dell          | G5 5590                     | [58bd69f40b](https://linux-hardware.org/?probe=58bd69f40b) | Dec 28, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [8901206dd0](https://linux-hardware.org/?probe=8901206dd0) | Dec 28, 2022 |
| Dell          | Inspiron 5458               | [269d455191](https://linux-hardware.org/?probe=269d455191) | Dec 28, 2022 |
| HP            | ProBook 440 14 inch G9 N... | [e23c23e61f](https://linux-hardware.org/?probe=e23c23e61f) | Dec 28, 2022 |
| HP            | ProBook 440 14 inch G9 N... | [5c4856e5c8](https://linux-hardware.org/?probe=5c4856e5c8) | Dec 28, 2022 |
| Lenovo        | IdeaPad L3 15ITL6 82HL      | [0852995abb](https://linux-hardware.org/?probe=0852995abb) | Dec 28, 2022 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | [e12c24fd74](https://linux-hardware.org/?probe=e12c24fd74) | Dec 28, 2022 |
| Google        | Voxel                       | [430244f188](https://linux-hardware.org/?probe=430244f188) | Dec 28, 2022 |
| HP            | ProBook 440 G6              | [6240bc3677](https://linux-hardware.org/?probe=6240bc3677) | Dec 28, 2022 |
| HP            | ProBook 440 G6              | [f5689c6edc](https://linux-hardware.org/?probe=f5689c6edc) | Dec 28, 2022 |
| Dell          | Inspiron 16 5625            | [dbc2d2fc6f](https://linux-hardware.org/?probe=dbc2d2fc6f) | Dec 28, 2022 |
| HUAWEI        | HLYL-WXX9                   | [790b3dcdde](https://linux-hardware.org/?probe=790b3dcdde) | Dec 28, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [ad33bb0d6f](https://linux-hardware.org/?probe=ad33bb0d6f) | Dec 28, 2022 |
| HP            | G62                         | [05ad917600](https://linux-hardware.org/?probe=05ad917600) | Dec 28, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [d1f63174e4](https://linux-hardware.org/?probe=d1f63174e4) | Dec 28, 2022 |
| HUAWEI        | BOM-WXX9                    | [826a683b58](https://linux-hardware.org/?probe=826a683b58) | Dec 28, 2022 |
| ASUSTek       | ROG Strix G513QE_G513QE     | [00a92c3818](https://linux-hardware.org/?probe=00a92c3818) | Dec 28, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [6eaa690ff2](https://linux-hardware.org/?probe=6eaa690ff2) | Dec 28, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [538bf2bb33](https://linux-hardware.org/?probe=538bf2bb33) | Dec 28, 2022 |
| MSI           | GL63 8RC                    | [0b973e252f](https://linux-hardware.org/?probe=0b973e252f) | Dec 27, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [d579ff34ee](https://linux-hardware.org/?probe=d579ff34ee) | Dec 27, 2022 |
| Dell          | Inspiron 15 3525            | [64a70af984](https://linux-hardware.org/?probe=64a70af984) | Dec 27, 2022 |
| HP            | Laptop 15-dy5xxx            | [d7daff3ed1](https://linux-hardware.org/?probe=d7daff3ed1) | Dec 27, 2022 |
| Timi          | RedmiBook 15                | [cf38b14bc5](https://linux-hardware.org/?probe=cf38b14bc5) | Dec 27, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [e41c8ca4ee](https://linux-hardware.org/?probe=e41c8ca4ee) | Dec 27, 2022 |
| Dell          | Latitude E7440              | [f2c052dde9](https://linux-hardware.org/?probe=f2c052dde9) | Dec 27, 2022 |
| Dell          | Inspiron 15-3567            | [2f5381fa26](https://linux-hardware.org/?probe=2f5381fa26) | Dec 26, 2022 |
| HP            | ProBook 450 G7              | [dfedb566ff](https://linux-hardware.org/?probe=dfedb566ff) | Dec 26, 2022 |
| Lenovo        | G510 20238                  | [812d6eb07e](https://linux-hardware.org/?probe=812d6eb07e) | Dec 26, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [c7babe827f](https://linux-hardware.org/?probe=c7babe827f) | Dec 26, 2022 |
| Dell          | Inspiron 3521               | [9d544fbcd4](https://linux-hardware.org/?probe=9d544fbcd4) | Dec 26, 2022 |
| Dell          | Inspiron 5458               | [4e393c7334](https://linux-hardware.org/?probe=4e393c7334) | Dec 26, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [ce352bf1b1](https://linux-hardware.org/?probe=ce352bf1b1) | Dec 26, 2022 |
| Acer          | Aspire A515-51              | [e763dd5dfe](https://linux-hardware.org/?probe=e763dd5dfe) | Dec 26, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [62869e3d8c](https://linux-hardware.org/?probe=62869e3d8c) | Dec 26, 2022 |
| Dell          | Inspiron 5759               | [d1938219e9](https://linux-hardware.org/?probe=d1938219e9) | Dec 26, 2022 |
| Dell          | Latitude 5580               | [72c0e42aeb](https://linux-hardware.org/?probe=72c0e42aeb) | Dec 26, 2022 |
| Acer          | Aspire A315-59              | [6625ce058f](https://linux-hardware.org/?probe=6625ce058f) | Dec 25, 2022 |
| HP            | ProBook 6465b               | [d0f5218f72](https://linux-hardware.org/?probe=d0f5218f72) | Dec 25, 2022 |
| ASUSTek       | K55VD                       | [52df2ba00b](https://linux-hardware.org/?probe=52df2ba00b) | Dec 25, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | [5aa14f474e](https://linux-hardware.org/?probe=5aa14f474e) | Dec 25, 2022 |
| MSI           | Modern 14 B4MW              | [e9dbd838ec](https://linux-hardware.org/?probe=e9dbd838ec) | Dec 25, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [fa7183c982](https://linux-hardware.org/?probe=fa7183c982) | Dec 25, 2022 |
| Dell          | XPS 15 9510                 | [6c809c224c](https://linux-hardware.org/?probe=6c809c224c) | Dec 24, 2022 |
| Dell          | Latitude 5510               | [68e4810231](https://linux-hardware.org/?probe=68e4810231) | Dec 24, 2022 |
| HUAWEI        | CREM-WXX9                   | [a48a2f6362](https://linux-hardware.org/?probe=a48a2f6362) | Dec 24, 2022 |
| HP            | Pavilion g6                 | [71d7947da6](https://linux-hardware.org/?probe=71d7947da6) | Dec 24, 2022 |
| MSI           | Stealth 15M B12UE           | [a8e294154b](https://linux-hardware.org/?probe=a8e294154b) | Dec 24, 2022 |
| Lenovo        | ThinkPad T470s 20HGS0AY0... | [28e67f37bc](https://linux-hardware.org/?probe=28e67f37bc) | Dec 24, 2022 |
| Acer          | Aspire A514-54              | [ea57f4aa3a](https://linux-hardware.org/?probe=ea57f4aa3a) | Dec 24, 2022 |
| Dell          | Latitude 5420               | [201e81d0ed](https://linux-hardware.org/?probe=201e81d0ed) | Dec 23, 2022 |
| Dell          | Latitude 5420               | [9fd9875465](https://linux-hardware.org/?probe=9fd9875465) | Dec 23, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [f114731a78](https://linux-hardware.org/?probe=f114731a78) | Dec 23, 2022 |
| ASUSTek       | X750JN                      | [d933b1a80b](https://linux-hardware.org/?probe=d933b1a80b) | Dec 23, 2022 |
| Jooyon Tec... | J6BF                        | [dabe200abe](https://linux-hardware.org/?probe=dabe200abe) | Dec 23, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B3302CEA... | [756390ae0c](https://linux-hardware.org/?probe=756390ae0c) | Dec 23, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B3302CEA... | [c2dd56664a](https://linux-hardware.org/?probe=c2dd56664a) | Dec 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [627186e9e8](https://linux-hardware.org/?probe=627186e9e8) | Dec 23, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [fe159bf4ca](https://linux-hardware.org/?probe=fe159bf4ca) | Dec 23, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [77e30fee83](https://linux-hardware.org/?probe=77e30fee83) | Dec 23, 2022 |
| Acer          | Aspire A515-57G             | [a208b5598e](https://linux-hardware.org/?probe=a208b5598e) | Dec 22, 2022 |
| Acer          | Aspire A515-57G             | [cccd3d01d7](https://linux-hardware.org/?probe=cccd3d01d7) | Dec 22, 2022 |
| Acer          | Aspire V5-571               | [b4de144f3e](https://linux-hardware.org/?probe=b4de144f3e) | Dec 22, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [2505eabeaf](https://linux-hardware.org/?probe=2505eabeaf) | Dec 22, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [677cb5b0b3](https://linux-hardware.org/?probe=677cb5b0b3) | Dec 22, 2022 |
| MSI           | Stealth 15M B12UE           | [65d1cc61ba](https://linux-hardware.org/?probe=65d1cc61ba) | Dec 22, 2022 |
| Lenovo        | XiaoXinPro 16ACH 2021 82... | [2b25ab8790](https://linux-hardware.org/?probe=2b25ab8790) | Dec 22, 2022 |
| GPD           | P3 MAX                      | [9069ed5580](https://linux-hardware.org/?probe=9069ed5580) | Dec 22, 2022 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [6db25ba5ca](https://linux-hardware.org/?probe=6db25ba5ca) | Dec 22, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [fb60e7984c](https://linux-hardware.org/?probe=fb60e7984c) | Dec 21, 2022 |
| ASUSTek       | X450CA                      | [5b793f14ff](https://linux-hardware.org/?probe=5b793f14ff) | Dec 21, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [721bc5f662](https://linux-hardware.org/?probe=721bc5f662) | Dec 21, 2022 |
| MSI           | Stealth 15M B12UE           | [6f7a27c8c5](https://linux-hardware.org/?probe=6f7a27c8c5) | Dec 21, 2022 |
| Apple         | MacBookPro9,2               | [5bc62fc208](https://linux-hardware.org/?probe=5bc62fc208) | Dec 21, 2022 |
| MSI           | Stealth 15M B12UE           | [ce6c271622](https://linux-hardware.org/?probe=ce6c271622) | Dec 21, 2022 |
| HP            | Stream Notebook PC 13       | [9c88ffc394](https://linux-hardware.org/?probe=9c88ffc394) | Dec 21, 2022 |
| Positivo B... | VJFE41F11X-XXXXXX           | [77c9275988](https://linux-hardware.org/?probe=77c9275988) | Dec 21, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | [ec20f98178](https://linux-hardware.org/?probe=ec20f98178) | Dec 21, 2022 |
| Dell          | Latitude 5520               | [203652b6dd](https://linux-hardware.org/?probe=203652b6dd) | Dec 21, 2022 |
| Lenovo        | ThinkPad E15 20RD0011RT     | [1f1c718c61](https://linux-hardware.org/?probe=1f1c718c61) | Dec 21, 2022 |
| Timi          | Mi NoteBook Pro             | [b5bbb4f410](https://linux-hardware.org/?probe=b5bbb4f410) | Dec 21, 2022 |
| MSI           | Modern 14 B4MW              | [2d446beedf](https://linux-hardware.org/?probe=2d446beedf) | Dec 21, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d9db7be046](https://linux-hardware.org/?probe=d9db7be046) | Dec 21, 2022 |
| Dell          | Latitude 3420               | [99d501d768](https://linux-hardware.org/?probe=99d501d768) | Dec 20, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [89b8982148](https://linux-hardware.org/?probe=89b8982148) | Dec 20, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [082a1fb19e](https://linux-hardware.org/?probe=082a1fb19e) | Dec 20, 2022 |
| Positivo B... | VJFE41F11X-XXXXXX           | [383b0f3311](https://linux-hardware.org/?probe=383b0f3311) | Dec 20, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [0d59e38c20](https://linux-hardware.org/?probe=0d59e38c20) | Dec 20, 2022 |
| HP            | ZBook 15                    | [a3bf671d64](https://linux-hardware.org/?probe=a3bf671d64) | Dec 20, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [af14f0c425](https://linux-hardware.org/?probe=af14f0c425) | Dec 20, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [e7393fd2b7](https://linux-hardware.org/?probe=e7393fd2b7) | Dec 20, 2022 |
| Dell          | Vostro 5620                 | [005d388376](https://linux-hardware.org/?probe=005d388376) | Dec 20, 2022 |
| Lenovo        | ThinkPad E15 20RD0011RT     | [bbfea042cd](https://linux-hardware.org/?probe=bbfea042cd) | Dec 20, 2022 |
| HP            | Pavilion dv6                | [8b0f82599c](https://linux-hardware.org/?probe=8b0f82599c) | Dec 20, 2022 |
| ASUSTek       | Zenbook UX5400EA_UX5400E... | [011d3e746d](https://linux-hardware.org/?probe=011d3e746d) | Dec 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [b30bf77d27](https://linux-hardware.org/?probe=b30bf77d27) | Dec 19, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [c67b4d2b31](https://linux-hardware.org/?probe=c67b4d2b31) | Dec 19, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [9f5a91c628](https://linux-hardware.org/?probe=9f5a91c628) | Dec 19, 2022 |
| Sony          | SVE15133CNB                 | [a2bee3bb3f](https://linux-hardware.org/?probe=a2bee3bb3f) | Dec 19, 2022 |
| ASUSTek       | X556UJ                      | [256957850d](https://linux-hardware.org/?probe=256957850d) | Dec 19, 2022 |
| MSI           | GE63 Raider RGB 8RF         | [a85193c482](https://linux-hardware.org/?probe=a85193c482) | Dec 19, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [714d2a6dea](https://linux-hardware.org/?probe=714d2a6dea) | Dec 19, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [ab3b4786ea](https://linux-hardware.org/?probe=ab3b4786ea) | Dec 19, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [856515e522](https://linux-hardware.org/?probe=856515e522) | Dec 19, 2022 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [a5a207a46d](https://linux-hardware.org/?probe=a5a207a46d) | Dec 19, 2022 |
| MSI           | PS42 8RB                    | [42422af633](https://linux-hardware.org/?probe=42422af633) | Dec 19, 2022 |
| Acer          | Swift SF114-32              | [757b666913](https://linux-hardware.org/?probe=757b666913) | Dec 18, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [23b255ed61](https://linux-hardware.org/?probe=23b255ed61) | Dec 18, 2022 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | [86c9426d80](https://linux-hardware.org/?probe=86c9426d80) | Dec 18, 2022 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | [05fcf7302f](https://linux-hardware.org/?probe=05fcf7302f) | Dec 18, 2022 |
| Acer          | Aspire A315-31              | [e391c56a47](https://linux-hardware.org/?probe=e391c56a47) | Dec 18, 2022 |
| Lenovo        | ThinkPad W550s 20E2000PG... | [938c10075a](https://linux-hardware.org/?probe=938c10075a) | Dec 18, 2022 |
| HP            | Laptop 15-da0xxx            | [b712a7bd77](https://linux-hardware.org/?probe=b712a7bd77) | Dec 18, 2022 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [56e75d70fa](https://linux-hardware.org/?probe=56e75d70fa) | Dec 18, 2022 |
| HP            | ProBook 450 G7              | [ad9bf6b390](https://linux-hardware.org/?probe=ad9bf6b390) | Dec 17, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [c9cc617e08](https://linux-hardware.org/?probe=c9cc617e08) | Dec 17, 2022 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [f047451b08](https://linux-hardware.org/?probe=f047451b08) | Dec 17, 2022 |
| Sony          | SVE15133CNB                 | [acca7c4697](https://linux-hardware.org/?probe=acca7c4697) | Dec 17, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [49969f1b81](https://linux-hardware.org/?probe=49969f1b81) | Dec 17, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [df49d0114f](https://linux-hardware.org/?probe=df49d0114f) | Dec 17, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [c94cd1a926](https://linux-hardware.org/?probe=c94cd1a926) | Dec 17, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [a481e4a590](https://linux-hardware.org/?probe=a481e4a590) | Dec 17, 2022 |
| GPD           | P2 MAX                      | [de5983ec37](https://linux-hardware.org/?probe=de5983ec37) | Dec 17, 2022 |
| ASUSTek       | X45C                        | [80377ba23f](https://linux-hardware.org/?probe=80377ba23f) | Dec 17, 2022 |
| HP            | Pavilion Laptop 14-ce1xx... | [8d631bb590](https://linux-hardware.org/?probe=8d631bb590) | Dec 17, 2022 |
| Dell          | Inspiron 3583               | [5629961182](https://linux-hardware.org/?probe=5629961182) | Dec 17, 2022 |
| HP            | ProBook 440 14 inch G9 N... | [5ab1c3b848](https://linux-hardware.org/?probe=5ab1c3b848) | Dec 17, 2022 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [645e7245d4](https://linux-hardware.org/?probe=645e7245d4) | Dec 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | [2ba98da01d](https://linux-hardware.org/?probe=2ba98da01d) | Dec 16, 2022 |
| HUAWEI        | KLVL-WXX9                   | [a767e0fbf0](https://linux-hardware.org/?probe=a767e0fbf0) | Dec 16, 2022 |
| HP            | Laptop 14-cm0xxx            | [a5bdc5f3c9](https://linux-hardware.org/?probe=a5bdc5f3c9) | Dec 16, 2022 |
| Dell          | Vostro 5590                 | [3735674d3f](https://linux-hardware.org/?probe=3735674d3f) | Dec 16, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [7c678e18cd](https://linux-hardware.org/?probe=7c678e18cd) | Dec 16, 2022 |
| Dell          | Inspiron 5566               | [ccfc358303](https://linux-hardware.org/?probe=ccfc358303) | Dec 16, 2022 |
| ASUSTek       | X550LD                      | [2960bdb195](https://linux-hardware.org/?probe=2960bdb195) | Dec 16, 2022 |
| Lenovo        | ThinkPad W530 243858U       | [9dc4fb1abb](https://linux-hardware.org/?probe=9dc4fb1abb) | Dec 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [955de558cb](https://linux-hardware.org/?probe=955de558cb) | Dec 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [e1d8403247](https://linux-hardware.org/?probe=e1d8403247) | Dec 16, 2022 |
| Dell          | XPS 13 9380                 | [719f489e01](https://linux-hardware.org/?probe=719f489e01) | Dec 15, 2022 |
| Dell          | Inspiron 7501               | [1749ece1b3](https://linux-hardware.org/?probe=1749ece1b3) | Dec 15, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [b8cc280665](https://linux-hardware.org/?probe=b8cc280665) | Dec 15, 2022 |
| HUAWEI        | KLVL-WXXW                   | [1dd0f2a71f](https://linux-hardware.org/?probe=1dd0f2a71f) | Dec 15, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [85c38f0af3](https://linux-hardware.org/?probe=85c38f0af3) | Dec 15, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | [06d690e9fe](https://linux-hardware.org/?probe=06d690e9fe) | Dec 15, 2022 |
| HP            | ProBook 440 14 inch G9 N... | [1380e253a5](https://linux-hardware.org/?probe=1380e253a5) | Dec 14, 2022 |
| Samsung       | 750XDA                      | [0120054e9f](https://linux-hardware.org/?probe=0120054e9f) | Dec 14, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | [fe7f585504](https://linux-hardware.org/?probe=fe7f585504) | Dec 14, 2022 |
| Dell          | Inspiron 3583               | [70992b154e](https://linux-hardware.org/?probe=70992b154e) | Dec 14, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [b2d808ab85](https://linux-hardware.org/?probe=b2d808ab85) | Dec 14, 2022 |
| Lenovo        | ThinkPad T480s 20L8S4GU0... | [bed7f6d44e](https://linux-hardware.org/?probe=bed7f6d44e) | Dec 14, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [95aca2679a](https://linux-hardware.org/?probe=95aca2679a) | Dec 14, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [44484456f8](https://linux-hardware.org/?probe=44484456f8) | Dec 14, 2022 |
| HP            | Laptop 14-fq1xxx            | [2da9ae7906](https://linux-hardware.org/?probe=2da9ae7906) | Dec 14, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [034b34f6d6](https://linux-hardware.org/?probe=034b34f6d6) | Dec 13, 2022 |
| Pegatron      | C17A                        | [adde308568](https://linux-hardware.org/?probe=adde308568) | Dec 13, 2022 |
| HP            | Laptop 14-fq1xxx            | [ed92313ebc](https://linux-hardware.org/?probe=ed92313ebc) | Dec 13, 2022 |
| HP            | ProBook 440 G7              | [ca2ba2d622](https://linux-hardware.org/?probe=ca2ba2d622) | Dec 13, 2022 |
| Toshiba       | TECRA A10                   | [760bda2b7d](https://linux-hardware.org/?probe=760bda2b7d) | Dec 13, 2022 |
| Acer          | Predator G9-591             | [838b0e0f8c](https://linux-hardware.org/?probe=838b0e0f8c) | Dec 13, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | [63cbf5d0e9](https://linux-hardware.org/?probe=63cbf5d0e9) | Dec 13, 2022 |
| MSI           | Modern 14 B4MW              | [8489ca12d8](https://linux-hardware.org/?probe=8489ca12d8) | Dec 13, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [3eb157838e](https://linux-hardware.org/?probe=3eb157838e) | Dec 13, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | [3c5a5379a4](https://linux-hardware.org/?probe=3c5a5379a4) | Dec 13, 2022 |
| Dell          | Inspiron 13-5368            | [952dd9d819](https://linux-hardware.org/?probe=952dd9d819) | Dec 13, 2022 |
| Lenovo        | ThinkPad T480s 20L8002WM... | [d742af8997](https://linux-hardware.org/?probe=d742af8997) | Dec 13, 2022 |
| HUAWEI        | KLVL-WXX9                   | [469a37f1e4](https://linux-hardware.org/?probe=469a37f1e4) | Dec 12, 2022 |
| Dell          | Inspiron 7380               | [29d4feb456](https://linux-hardware.org/?probe=29d4feb456) | Dec 12, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [fd0700b7ae](https://linux-hardware.org/?probe=fd0700b7ae) | Dec 12, 2022 |
| HP            | ProBook 6570b               | [a6b67497a1](https://linux-hardware.org/?probe=a6b67497a1) | Dec 12, 2022 |
| HUAWEI        | KLVL-WXX9                   | [bdddbb7807](https://linux-hardware.org/?probe=bdddbb7807) | Dec 12, 2022 |
| ASUSTek       | K55VD                       | [f74382c966](https://linux-hardware.org/?probe=f74382c966) | Dec 12, 2022 |
| Lenovo        | ThinkPad T590 20N5S4R800    | [9fb659eea3](https://linux-hardware.org/?probe=9fb659eea3) | Dec 12, 2022 |
| MSI           | GE63 Raider RGB 8RF         | [b311865418](https://linux-hardware.org/?probe=b311865418) | Dec 12, 2022 |
| MSI           | Modern 14 B11MOU            | [9739ffdf34](https://linux-hardware.org/?probe=9739ffdf34) | Dec 12, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | [257e692fa4](https://linux-hardware.org/?probe=257e692fa4) | Dec 11, 2022 |
| Toshiba       | Satellite A300              | [211e44e5d2](https://linux-hardware.org/?probe=211e44e5d2) | Dec 11, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [50e8243e50](https://linux-hardware.org/?probe=50e8243e50) | Dec 11, 2022 |
| Acer          | Aspire E5-576G              | [9cc371883c](https://linux-hardware.org/?probe=9cc371883c) | Dec 11, 2022 |
| ASUSTek       | X75VD                       | [5cdd66c849](https://linux-hardware.org/?probe=5cdd66c849) | Dec 11, 2022 |
| ASUSTek       | X75VD                       | [624ea43f9d](https://linux-hardware.org/?probe=624ea43f9d) | Dec 11, 2022 |
| Notebook      | WA50SRQ                     | [da74211ac6](https://linux-hardware.org/?probe=da74211ac6) | Dec 11, 2022 |
| HP            | Pavilion g6                 | [b5662e5fec](https://linux-hardware.org/?probe=b5662e5fec) | Dec 11, 2022 |
| Dell          | Latitude E7240              | [591f0ad589](https://linux-hardware.org/?probe=591f0ad589) | Dec 11, 2022 |
| MSI           | Prestige 15 A11SCX          | [5941b1aed7](https://linux-hardware.org/?probe=5941b1aed7) | Dec 10, 2022 |
| MSI           | Prestige 15 A11SCX          | [ab1334fca2](https://linux-hardware.org/?probe=ab1334fca2) | Dec 10, 2022 |
| Dell          | XPS 17 9700                 | [0426545e91](https://linux-hardware.org/?probe=0426545e91) | Dec 10, 2022 |
| Acer          | Predator PH315-52           | [e80dfca4a8](https://linux-hardware.org/?probe=e80dfca4a8) | Dec 10, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [25d5b5623b](https://linux-hardware.org/?probe=25d5b5623b) | Dec 10, 2022 |
| Acer          | Predator PH315-52           | [72f0e70b26](https://linux-hardware.org/?probe=72f0e70b26) | Dec 10, 2022 |
| Pegatron      | C17A                        | [2437a88730](https://linux-hardware.org/?probe=2437a88730) | Dec 09, 2022 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | [b524e6fd67](https://linux-hardware.org/?probe=b524e6fd67) | Dec 09, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [ad09795330](https://linux-hardware.org/?probe=ad09795330) | Dec 09, 2022 |
| Schenker      | VIA 15                      | [25883b06a1](https://linux-hardware.org/?probe=25883b06a1) | Dec 09, 2022 |
| MSI           | Modern 15 A11MU             | [e5ba0c8749](https://linux-hardware.org/?probe=e5ba0c8749) | Dec 09, 2022 |
| HP            | 245 G8 Notebook PC          | [c291bac936](https://linux-hardware.org/?probe=c291bac936) | Dec 09, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [5250630bdd](https://linux-hardware.org/?probe=5250630bdd) | Dec 09, 2022 |
| Acer          | Aspire E1-572G              | [2dabd7cf91](https://linux-hardware.org/?probe=2dabd7cf91) | Dec 09, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [1595cc246a](https://linux-hardware.org/?probe=1595cc246a) | Dec 09, 2022 |
| HP            | Laptop 15-db0xxx            | [b0de030271](https://linux-hardware.org/?probe=b0de030271) | Dec 09, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [94c151e95d](https://linux-hardware.org/?probe=94c151e95d) | Dec 09, 2022 |
| HP            | Pavilion dv5                | [cdd08235ff](https://linux-hardware.org/?probe=cdd08235ff) | Dec 09, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | [182678a056](https://linux-hardware.org/?probe=182678a056) | Dec 08, 2022 |
| Acer          | Aspire E1-572G              | [df78e85dfe](https://linux-hardware.org/?probe=df78e85dfe) | Dec 08, 2022 |
| HP            | ProBook 640 G1              | [c3bf44d032](https://linux-hardware.org/?probe=c3bf44d032) | Dec 08, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [9122edaf0a](https://linux-hardware.org/?probe=9122edaf0a) | Dec 08, 2022 |
| HUAWEI        | MACH-WX9                    | [5ed19862a7](https://linux-hardware.org/?probe=5ed19862a7) | Dec 08, 2022 |
| Dell          | Inspiron 5566               | [dcf5539e74](https://linux-hardware.org/?probe=dcf5539e74) | Dec 08, 2022 |
| Lenovo        | V14 G2 ITL 82NM             | [00995baaae](https://linux-hardware.org/?probe=00995baaae) | Dec 07, 2022 |
| HP            | EliteBook 820 G1            | [59118a0638](https://linux-hardware.org/?probe=59118a0638) | Dec 07, 2022 |
| Dell          | XPS 13 9350                 | [9779817777](https://linux-hardware.org/?probe=9779817777) | Dec 07, 2022 |
| Lenovo        | ThinkPad T460 20FN002JUS    | [efe4d93e2d](https://linux-hardware.org/?probe=efe4d93e2d) | Dec 07, 2022 |
| Acer          | Aspire E5-571               | [d5d013b642](https://linux-hardware.org/?probe=d5d013b642) | Dec 07, 2022 |
| HP            | EliteBook 820 G1            | [a214979767](https://linux-hardware.org/?probe=a214979767) | Dec 07, 2022 |
| Dell          | Latitude E6420              | [e87ced9ea4](https://linux-hardware.org/?probe=e87ced9ea4) | Dec 06, 2022 |
| Dell          | Latitude E6420              | [17c9263444](https://linux-hardware.org/?probe=17c9263444) | Dec 06, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [a3b78e7093](https://linux-hardware.org/?probe=a3b78e7093) | Dec 06, 2022 |
| Acer          | Predator G9-591             | [6e8fe2e030](https://linux-hardware.org/?probe=6e8fe2e030) | Dec 06, 2022 |
| Acer          | Aspire E5-571               | [e9d00a798c](https://linux-hardware.org/?probe=e9d00a798c) | Dec 06, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [2f14f32399](https://linux-hardware.org/?probe=2f14f32399) | Dec 06, 2022 |
| BANGHO        | BES T5                      | [db1db74a86](https://linux-hardware.org/?probe=db1db74a86) | Dec 06, 2022 |
| HP            | Laptop 14-fq1xxx            | [4f93d8895e](https://linux-hardware.org/?probe=4f93d8895e) | Dec 06, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [12e33b1925](https://linux-hardware.org/?probe=12e33b1925) | Dec 06, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [36985fd47e](https://linux-hardware.org/?probe=36985fd47e) | Dec 05, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [a6763bdd89](https://linux-hardware.org/?probe=a6763bdd89) | Dec 05, 2022 |
| Dell          | XPS 13 9343                 | [476763a913](https://linux-hardware.org/?probe=476763a913) | Dec 05, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c22a748043](https://linux-hardware.org/?probe=c22a748043) | Dec 05, 2022 |
| Dell          | Latitude 7490               | [e75a902d11](https://linux-hardware.org/?probe=e75a902d11) | Dec 05, 2022 |
| ASUSTek       | X510UNR                     | [b85ac74a3f](https://linux-hardware.org/?probe=b85ac74a3f) | Dec 05, 2022 |
| MSI           | Modern 14 B4MW              | [03c0b9e50d](https://linux-hardware.org/?probe=03c0b9e50d) | Dec 05, 2022 |
| HP            | Pavilion Laptop 15-eg2xx... | [9b87c97ed5](https://linux-hardware.org/?probe=9b87c97ed5) | Dec 05, 2022 |
| HP            | Pavilion Laptop 15-eg2xx... | [fe17634e66](https://linux-hardware.org/?probe=fe17634e66) | Dec 05, 2022 |
| Dell          | Inspiron 13-7378            | [b628250da9](https://linux-hardware.org/?probe=b628250da9) | Dec 04, 2022 |
| MSI           | GE72 6QD                    | [257a807435](https://linux-hardware.org/?probe=257a807435) | Dec 04, 2022 |
| Sony          | SVE15133CNB                 | [16f43f11a1](https://linux-hardware.org/?probe=16f43f11a1) | Dec 04, 2022 |
| Dell          | Inspiron 5459               | [9b714617c8](https://linux-hardware.org/?probe=9b714617c8) | Dec 04, 2022 |
| Apple         | MacBookPro8,1               | [29fa28c3f1](https://linux-hardware.org/?probe=29fa28c3f1) | Dec 04, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [076685806a](https://linux-hardware.org/?probe=076685806a) | Dec 04, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [fb96bd56ad](https://linux-hardware.org/?probe=fb96bd56ad) | Dec 04, 2022 |
| Dell          | Inspiron 5566               | [fb9c1854a2](https://linux-hardware.org/?probe=fb9c1854a2) | Dec 04, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [937053920b](https://linux-hardware.org/?probe=937053920b) | Dec 04, 2022 |
| Acer          | Aspire A515-45              | [48d98f5da4](https://linux-hardware.org/?probe=48d98f5da4) | Dec 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [f93dd5ad2d](https://linux-hardware.org/?probe=f93dd5ad2d) | Dec 03, 2022 |
| Apple         | MacBookPro9,2               | [eadd4cd3e1](https://linux-hardware.org/?probe=eadd4cd3e1) | Dec 03, 2022 |
| Pegatron      | A15W8                       | [f33c1aea21](https://linux-hardware.org/?probe=f33c1aea21) | Dec 03, 2022 |
| HP            | Laptop 15s-fr2xxx           | [623e794238](https://linux-hardware.org/?probe=623e794238) | Dec 03, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [c00aab388c](https://linux-hardware.org/?probe=c00aab388c) | Dec 03, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [037216f966](https://linux-hardware.org/?probe=037216f966) | Dec 03, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [1c27bd3d06](https://linux-hardware.org/?probe=1c27bd3d06) | Dec 03, 2022 |
| MSI           | Modern 14 B4MW              | [6890b98eeb](https://linux-hardware.org/?probe=6890b98eeb) | Dec 03, 2022 |
| Dell          | Inspiron 5567               | [d64c6bc6f4](https://linux-hardware.org/?probe=d64c6bc6f4) | Dec 03, 2022 |
| Dell          | Inspiron 5567               | [a9f812a233](https://linux-hardware.org/?probe=a9f812a233) | Dec 03, 2022 |
| Acer          | Aspire A715-51G             | [65aa3f7e69](https://linux-hardware.org/?probe=65aa3f7e69) | Dec 03, 2022 |
| HUAWEI        | MACHC-WAX9                  | [958e17ffc9](https://linux-hardware.org/?probe=958e17ffc9) | Dec 03, 2022 |
| Toshiba       | Satellite C50D-A-138        | [ccda846d5e](https://linux-hardware.org/?probe=ccda846d5e) | Dec 03, 2022 |
| Dell          | XPS 13 9350                 | [38c002d686](https://linux-hardware.org/?probe=38c002d686) | Dec 02, 2022 |
| Google        | Lick                        | [a03c415d36](https://linux-hardware.org/?probe=a03c415d36) | Dec 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [dc80fd6907](https://linux-hardware.org/?probe=dc80fd6907) | Dec 02, 2022 |
| HP            | ProBook 6570b               | [be8f757095](https://linux-hardware.org/?probe=be8f757095) | Dec 02, 2022 |
| HP            | ProBook 6570b               | [1e40d6a94b](https://linux-hardware.org/?probe=1e40d6a94b) | Dec 02, 2022 |
| HP            | Pavilion Laptop 14-bk0xx    | [57c3eeaf3d](https://linux-hardware.org/?probe=57c3eeaf3d) | Dec 02, 2022 |
| Acer          | Aspire A515-45              | [495abda40a](https://linux-hardware.org/?probe=495abda40a) | Dec 02, 2022 |
| Sony          | VPCEB1M1E                   | [7ea8161a05](https://linux-hardware.org/?probe=7ea8161a05) | Dec 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [2397eee427](https://linux-hardware.org/?probe=2397eee427) | Dec 01, 2022 |
| Google        | Kasumi                      | [d67591d35c](https://linux-hardware.org/?probe=d67591d35c) | Dec 01, 2022 |
| Acer          | Iconia W4-820               | [cf25eeba85](https://linux-hardware.org/?probe=cf25eeba85) | Dec 01, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [4ab89a8ad2](https://linux-hardware.org/?probe=4ab89a8ad2) | Dec 01, 2022 |
| Dell          | Latitude E5450              | [305bf364f6](https://linux-hardware.org/?probe=305bf364f6) | Dec 01, 2022 |
| ASUSTek       | Zephyrus M GU502GV_GU502... | [de34f148b9](https://linux-hardware.org/?probe=de34f148b9) | Dec 01, 2022 |
| Dell          | Latitude E5450              | [2b934a729c](https://linux-hardware.org/?probe=2b934a729c) | Dec 01, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [946e66e35e](https://linux-hardware.org/?probe=946e66e35e) | Dec 01, 2022 |
| HUAWEI        | MACH-WX9                    | [a37f48c68a](https://linux-hardware.org/?probe=a37f48c68a) | Dec 01, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [2cf7f9ab67](https://linux-hardware.org/?probe=2cf7f9ab67) | Dec 01, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [0128a48982](https://linux-hardware.org/?probe=0128a48982) | Dec 01, 2022 |
| HP            | ProBook 440 G7              | [a54a325001](https://linux-hardware.org/?probe=a54a325001) | Dec 01, 2022 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [f0ee9f78bd](https://linux-hardware.org/?probe=f0ee9f78bd) | Dec 01, 2022 |
| ASUSTek       | K55VD                       | [149d517fa5](https://linux-hardware.org/?probe=149d517fa5) | Dec 01, 2022 |
| HUAWEI        | CREM-WXX9                   | [2436f4cf5e](https://linux-hardware.org/?probe=2436f4cf5e) | Nov 30, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [3e67e44d23](https://linux-hardware.org/?probe=3e67e44d23) | Nov 30, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS5... | [2df1670891](https://linux-hardware.org/?probe=2df1670891) | Nov 30, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [944ace565b](https://linux-hardware.org/?probe=944ace565b) | Nov 30, 2022 |
| HP            | Notebook                    | [afac08b852](https://linux-hardware.org/?probe=afac08b852) | Nov 30, 2022 |
| Dell          | Inspiron 3580               | [6bc2705d99](https://linux-hardware.org/?probe=6bc2705d99) | Nov 30, 2022 |
| HP            | Laptop 15s-fq4xxx           | [19b00c186f](https://linux-hardware.org/?probe=19b00c186f) | Nov 30, 2022 |
| HP            | Laptop 15s-fq4xxx           | [18ec3bc77e](https://linux-hardware.org/?probe=18ec3bc77e) | Nov 30, 2022 |
| Lenovo        | ThinkPad T480 20L6S01Q3K    | [9fd6308179](https://linux-hardware.org/?probe=9fd6308179) | Nov 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [38c4009dba](https://linux-hardware.org/?probe=38c4009dba) | Nov 30, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [4a49152177](https://linux-hardware.org/?probe=4a49152177) | Nov 29, 2022 |
| Lenovo        | ThinkPad E550 20DF004RGE    | [a06fd97ee3](https://linux-hardware.org/?probe=a06fd97ee3) | Nov 29, 2022 |
| ASUSTek       | X756UXK                     | [a8fde1c59a](https://linux-hardware.org/?probe=a8fde1c59a) | Nov 29, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [9216162e85](https://linux-hardware.org/?probe=9216162e85) | Nov 29, 2022 |
| Dell          | Latitude D620               | [9f6317405c](https://linux-hardware.org/?probe=9f6317405c) | Nov 29, 2022 |
| HP            | ZBook Power G7 Mobile Wo... | [bb023e130b](https://linux-hardware.org/?probe=bb023e130b) | Nov 29, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [fd821a4b54](https://linux-hardware.org/?probe=fd821a4b54) | Nov 29, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [39e771bd92](https://linux-hardware.org/?probe=39e771bd92) | Nov 28, 2022 |
| Dell          | Latitude 7480               | [409c2f27c8](https://linux-hardware.org/?probe=409c2f27c8) | Nov 28, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [e1495dc120](https://linux-hardware.org/?probe=e1495dc120) | Nov 28, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [901fa6e871](https://linux-hardware.org/?probe=901fa6e871) | Nov 28, 2022 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [ea6f1fc82e](https://linux-hardware.org/?probe=ea6f1fc82e) | Nov 28, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IV... | [86f58e68b6](https://linux-hardware.org/?probe=86f58e68b6) | Nov 28, 2022 |
| Acer          | Nitro AN517-54              | [a9b90b8910](https://linux-hardware.org/?probe=a9b90b8910) | Nov 27, 2022 |
| Unknown       | Unknown                     | [4f73de3788](https://linux-hardware.org/?probe=4f73de3788) | Nov 27, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [415a8f0d8b](https://linux-hardware.org/?probe=415a8f0d8b) | Nov 27, 2022 |
| Acer          | Nitro AN517-54              | [445583d2bb](https://linux-hardware.org/?probe=445583d2bb) | Nov 27, 2022 |
| HP            | Laptop 15-da1xxx            | [8c4cae32db](https://linux-hardware.org/?probe=8c4cae32db) | Nov 27, 2022 |
| HP            | Laptop 15s-eq2xxx           | [bdc1a14cd4](https://linux-hardware.org/?probe=bdc1a14cd4) | Nov 27, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [26083dd909](https://linux-hardware.org/?probe=26083dd909) | Nov 27, 2022 |
| ASUSTek       | N53Jf                       | [e4dc6e5cd9](https://linux-hardware.org/?probe=e4dc6e5cd9) | Nov 27, 2022 |
| AVITA         | NS14A6                      | [b9cc8fe757](https://linux-hardware.org/?probe=b9cc8fe757) | Nov 27, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0XX0... | [f91c391079](https://linux-hardware.org/?probe=f91c391079) | Nov 26, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [dc561bb107](https://linux-hardware.org/?probe=dc561bb107) | Nov 26, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [336d829333](https://linux-hardware.org/?probe=336d829333) | Nov 26, 2022 |
| HP            | EliteBook 830 G5            | [bda395e731](https://linux-hardware.org/?probe=bda395e731) | Nov 26, 2022 |
| HP            | EliteBook 830 G5            | [0138561b29](https://linux-hardware.org/?probe=0138561b29) | Nov 26, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [74fcf5cb22](https://linux-hardware.org/?probe=74fcf5cb22) | Nov 26, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [a4dbfc0da9](https://linux-hardware.org/?probe=a4dbfc0da9) | Nov 26, 2022 |
| MACHENIKE     | MACHCREATOR-16              | [15d49eb71a](https://linux-hardware.org/?probe=15d49eb71a) | Nov 26, 2022 |
| Apple         | MacBookPro15,2              | [446ef54cb5](https://linux-hardware.org/?probe=446ef54cb5) | Nov 26, 2022 |
| Apple         | MacBookAir8,1               | [6656b4e315](https://linux-hardware.org/?probe=6656b4e315) | Nov 26, 2022 |
| MSI           | Modern 14 B5M               | [bf3c55e13b](https://linux-hardware.org/?probe=bf3c55e13b) | Nov 26, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [ab6ce548bc](https://linux-hardware.org/?probe=ab6ce548bc) | Nov 26, 2022 |
| Lenovo        | B51-80 80LM                 | [848b6ab7b3](https://linux-hardware.org/?probe=848b6ab7b3) | Nov 26, 2022 |
| Lenovo        | B51-80 80LM                 | [c34893c661](https://linux-hardware.org/?probe=c34893c661) | Nov 26, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [83a97530e1](https://linux-hardware.org/?probe=83a97530e1) | Nov 26, 2022 |
| Google        | Glimmer                     | [8ad30368c9](https://linux-hardware.org/?probe=8ad30368c9) | Nov 26, 2022 |
| GPD           | G1621-02                    | [f0e9e8442c](https://linux-hardware.org/?probe=f0e9e8442c) | Nov 26, 2022 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [d845cbb51d](https://linux-hardware.org/?probe=d845cbb51d) | Nov 26, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [18130ae317](https://linux-hardware.org/?probe=18130ae317) | Nov 25, 2022 |
| Sony          | SVE15133CNB                 | [376fc86892](https://linux-hardware.org/?probe=376fc86892) | Nov 25, 2022 |
| Sony          | SVE15133CNB                 | [f46e1bc341](https://linux-hardware.org/?probe=f46e1bc341) | Nov 25, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [4261949a3e](https://linux-hardware.org/?probe=4261949a3e) | Nov 25, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [8acafcf4ab](https://linux-hardware.org/?probe=8acafcf4ab) | Nov 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | [682993f58f](https://linux-hardware.org/?probe=682993f58f) | Nov 25, 2022 |
| HP            | Laptop 14-dq1xxx            | [1e6fa19cc3](https://linux-hardware.org/?probe=1e6fa19cc3) | Nov 25, 2022 |
| Acer          | Nitro AN515-54              | [9226b4c616](https://linux-hardware.org/?probe=9226b4c616) | Nov 24, 2022 |
| MSI           | Summit E16Flip A12UCT       | [95f653bddb](https://linux-hardware.org/?probe=95f653bddb) | Nov 24, 2022 |
| MSI           | Summit E16Flip A12UCT       | [a4a2b60b09](https://linux-hardware.org/?probe=a4a2b60b09) | Nov 24, 2022 |
| Dell          | Inspiron 5370               | [469b2c3fd4](https://linux-hardware.org/?probe=469b2c3fd4) | Nov 24, 2022 |
| Toshiba       | Satellite S55-A             | [5466c61736](https://linux-hardware.org/?probe=5466c61736) | Nov 24, 2022 |
| ASUSTek       | Q550LF                      | [713f7b2c74](https://linux-hardware.org/?probe=713f7b2c74) | Nov 24, 2022 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [1c65fff6e7](https://linux-hardware.org/?probe=1c65fff6e7) | Nov 24, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [d84bc82678](https://linux-hardware.org/?probe=d84bc82678) | Nov 23, 2022 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [5b18e83e0d](https://linux-hardware.org/?probe=5b18e83e0d) | Nov 23, 2022 |
| Lenovo        | IdeaPad 520S-14IKB 80X2     | [57dfd88985](https://linux-hardware.org/?probe=57dfd88985) | Nov 23, 2022 |
| HP            | Laptop 15-da0xxx            | [fa989478ad](https://linux-hardware.org/?probe=fa989478ad) | Nov 23, 2022 |
| HP            | Laptop 15-dw3xxx            | [fbf991818d](https://linux-hardware.org/?probe=fbf991818d) | Nov 23, 2022 |
| Apple         | MacBookPro9,2               | [3e176f0c26](https://linux-hardware.org/?probe=3e176f0c26) | Nov 22, 2022 |
| Acer          | Extensa 4220                | [af778b2ec9](https://linux-hardware.org/?probe=af778b2ec9) | Nov 22, 2022 |
| Acer          | Extensa 4220                | [04187e0d6e](https://linux-hardware.org/?probe=04187e0d6e) | Nov 22, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [923ccf8b76](https://linux-hardware.org/?probe=923ccf8b76) | Nov 22, 2022 |
| HP            | ProBook 430 G8 Notebook ... | [8a773e7358](https://linux-hardware.org/?probe=8a773e7358) | Nov 22, 2022 |
| Lenovo        | ThinkPad P53 20QNS00X00     | [d49ca08585](https://linux-hardware.org/?probe=d49ca08585) | Nov 22, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [d48ad61c01](https://linux-hardware.org/?probe=d48ad61c01) | Nov 22, 2022 |
| Acer          | Aspire A515-45              | [0dcdb72cd6](https://linux-hardware.org/?probe=0dcdb72cd6) | Nov 22, 2022 |
| Acer          | Predator PH315-55           | [f411f75743](https://linux-hardware.org/?probe=f411f75743) | Nov 22, 2022 |
| HP            | Laptop 15-da0xxx            | [aef0888523](https://linux-hardware.org/?probe=aef0888523) | Nov 21, 2022 |
| ASUSTek       | X541NA                      | [8c624c76fa](https://linux-hardware.org/?probe=8c624c76fa) | Nov 21, 2022 |
| Acer          | Aspire A315-51              | [bcff111ecd](https://linux-hardware.org/?probe=bcff111ecd) | Nov 21, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora_37/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Notebooks | Percent |
|-----------------------------|-----------|---------|
| 6.0.15-300.fc37.x86_64      | 75        | 7.96%   |
| 6.0.7-301.fc37.x86_64       | 64        | 6.79%   |
| 6.1.7-200.fc37.x86_64       | 55        | 5.84%   |
| 6.0.8-300.fc37.x86_64       | 54        | 5.73%   |
| 6.0.9-300.fc37.x86_64       | 51        | 5.41%   |
| 6.0.12-300.fc37.x86_64      | 51        | 5.41%   |
| 6.1.8-200.fc37.x86_64       | 41        | 4.35%   |
| 6.1.11-200.fc37.x86_64      | 40        | 4.25%   |
| 6.1.9-200.fc37.x86_64       | 39        | 4.14%   |
| 6.1.6-200.fc37.x86_64       | 36        | 3.82%   |
| 6.0.11-300.fc37.x86_64      | 35        | 3.72%   |
| 6.0.10-300.fc37.x86_64      | 35        | 3.72%   |
| 6.1.10-200.fc37.x86_64      | 34        | 3.61%   |
| 6.1.13-200.fc37.x86_64      | 32        | 3.4%    |
| 6.0.18-300.fc37.x86_64      | 31        | 3.29%   |
| 6.0.16-300.fc37.x86_64      | 31        | 3.29%   |
| 5.19.16-301.fc37.x86_64     | 25        | 2.65%   |
| 6.1.5-200.fc37.x86_64       | 21        | 2.23%   |
| 6.0.17-300.fc37.x86_64      | 18        | 1.91%   |
| 6.0.14-300.fc37.x86_64      | 17        | 1.8%    |
| 6.0.13-300.fc37.x86_64      | 16        | 1.7%    |
| 6.1.12-200.fc37.x86_64      | 15        | 1.59%   |
| 5.19.8-300.fc37.x86_64      | 10        | 1.06%   |
| 5.19.7-300.fc37.x86_64      | 9         | 0.96%   |
| 5.19.13-300.fc37.x86_64     | 9         | 0.96%   |
| 5.19.14-300.fc37.x86_64     | 7         | 0.74%   |
| 6.0.6-300.fc37.x86_64       | 6         | 0.64%   |
| 5.19.15-301.fc37.x86_64     | 6         | 0.64%   |
| 5.19.11-300.fc37.x86_64     | 6         | 0.64%   |
| 5.19.10-300.fc37.x86_64     | 6         | 0.64%   |
| 5.19.9-300.fc37.x86_64      | 5         | 0.53%   |
| 5.19.12-300.fc37.x86_64     | 4         | 0.42%   |
| 6.0.5-300.fc37.x86_64       | 3         | 0.32%   |
| 5.19.16-300.fc37.x86_64     | 3         | 0.32%   |
| 6.0.9-300.mbp.fc37.x86_64   | 2         | 0.21%   |
| 6.0.8-xm1.0.fc37.x86_64     | 2         | 0.21%   |
| 6.0.2-xm1.0.fc37.x86_64     | 2         | 0.21%   |
| 5.19.15-300.fc37.x86_64     | 2         | 0.21%   |
| 5.18.0-0.rc2.23.fc37.x86_64 | 2         | 0.21%   |
| 5.17.5-300.fc36.x86_64      | 2         | 0.21%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.0.15  | 77        | 8.17%   |
| 6.0.7   | 64        | 6.79%   |
| 6.0.8   | 58        | 6.16%   |
| 6.0.9   | 57        | 6.05%   |
| 6.1.7   | 55        | 5.84%   |
| 6.0.12  | 51        | 5.41%   |
| 6.1.8   | 42        | 4.46%   |
| 6.1.11  | 41        | 4.35%   |
| 6.1.9   | 40        | 4.25%   |
| 6.1.6   | 36        | 3.82%   |
| 6.1.10  | 36        | 3.82%   |
| 6.0.10  | 36        | 3.82%   |
| 6.0.11  | 35        | 3.72%   |
| 6.1.13  | 32        | 3.4%    |
| 6.0.18  | 31        | 3.29%   |
| 6.0.16  | 31        | 3.29%   |
| 5.19.16 | 29        | 3.08%   |
| 6.1.5   | 21        | 2.23%   |
| 6.0.17  | 18        | 1.91%   |
| 6.0.14  | 17        | 1.8%    |
| 6.1.12  | 16        | 1.7%    |
| 6.0.13  | 16        | 1.7%    |
| 5.19.8  | 10        | 1.06%   |
| 5.19.7  | 9         | 0.96%   |
| 5.19.13 | 9         | 0.96%   |
| 5.19.15 | 8         | 0.85%   |
| 6.1.0   | 7         | 0.74%   |
| 5.19.14 | 7         | 0.74%   |
| 5.19.10 | 7         | 0.74%   |
| 6.0.6   | 6         | 0.64%   |
| 5.19.12 | 6         | 0.64%   |
| 5.19.11 | 6         | 0.64%   |
| 5.19.9  | 5         | 0.53%   |
| 6.2.0   | 3         | 0.32%   |
| 6.0.5   | 3         | 0.32%   |
| 5.19.0  | 3         | 0.32%   |
| 6.1.1   | 2         | 0.21%   |
| 6.0.2   | 2         | 0.21%   |
| 5.18.0  | 2         | 0.21%   |
| 5.17.5  | 2         | 0.21%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.0     | 475       | 52.72%  |
| 6.1     | 319       | 35.41%  |
| 5.19    | 97        | 10.77%  |
| 6.2     | 3         | 0.33%   |
| 5.18    | 2         | 0.22%   |
| 5.17    | 2         | 0.22%   |
| 5.15    | 2         | 0.22%   |
| 5.10    | 1         | 0.11%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 864       | 99.88%  |
| aarch64 | 1         | 0.12%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 651       | 74.74%  |
| KDE5          | 144       | 16.53%  |
| Unknown       | 19        | 2.18%   |
| XFCE          | 14        | 1.61%   |
| X-Cinnamon    | 11        | 1.26%   |
| i3            | 9         | 1.03%   |
| MATE          | 7         | 0.8%    |
| Cinnamon      | 4         | 0.46%   |
| LXDE          | 3         | 0.34%   |
| sway          | 2         | 0.23%   |
| KDE           | 2         | 0.23%   |
| xmonad        | 1         | 0.11%   |
| qtile         | 1         | 0.11%   |
| LXQt          | 1         | 0.11%   |
| GNOME-Classic | 1         | 0.11%   |
| GNOME Classic | 1         | 0.11%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 673       | 77.09%  |
| X11     | 186       | 21.31%  |
| Unknown | 11        | 1.26%   |
| Tty     | 3         | 0.34%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 436       | 49.83%  |
| GDM     | 316       | 36.11%  |
| SDDM    | 73        | 8.34%   |
| LightDM | 47        | 5.37%   |
| LXDM    | 2         | 0.23%   |
| GREETD  | 1         | 0.11%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 458       | 52.76%  |
| ru_RU   | 61        | 7.03%   |
| en_GB   | 54        | 6.22%   |
| pt_BR   | 35        | 4.03%   |
| de_DE   | 34        | 3.92%   |
| fr_FR   | 29        | 3.34%   |
| it_IT   | 22        | 2.53%   |
| en_IN   | 17        | 1.96%   |
| en_AU   | 14        | 1.61%   |
| pl_PL   | 13        | 1.5%    |
| en_CA   | 12        | 1.38%   |
| es_ES   | 11        | 1.27%   |
| es_MX   | 8         | 0.92%   |
| es_CL   | 8         | 0.92%   |
| zh_CN   | 7         | 0.81%   |
| tr_TR   | 6         | 0.69%   |
| C       | 6         | 0.69%   |
| es_AR   | 5         | 0.58%   |
| de_AT   | 5         | 0.58%   |
| zh_TW   | 4         | 0.46%   |
| en_ZA   | 4         | 0.46%   |
| Unknown | 4         | 0.46%   |
| hu_HU   | 3         | 0.35%   |
| es_CO   | 3         | 0.35%   |
| en_PH   | 3         | 0.35%   |
| en_IE   | 3         | 0.35%   |
| nl_NL   | 2         | 0.23%   |
| fr_CA   | 2         | 0.23%   |
| fi_FI   | 2         | 0.23%   |
| es_VE   | 2         | 0.23%   |
| en_IL   | 2         | 0.23%   |
| en_DK   | 2         | 0.23%   |
| de_CH   | 2         | 0.23%   |
| ca_ES   | 2         | 0.23%   |
| uk_UA   | 1         | 0.12%   |
| sv_SE   | 1         | 0.12%   |
| sk_SK   | 1         | 0.12%   |
| ro_RO   | 1         | 0.12%   |
| pt_PT   | 1         | 0.12%   |
| nb_NO   | 1         | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 756       | 87.3%   |
| BIOS | 110       | 12.7%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 723       | 83.39%  |
| Ext4    | 131       | 15.11%  |
| Xfs     | 8         | 0.92%   |
| Overlay | 5         | 0.58%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 429       | 49.31%  |
| Unknown | 420       | 48.28%  |
| MBR     | 21        | 2.41%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 793       | 91.15%  |
| Yes       | 77        | 8.85%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 700       | 80.83%  |
| Yes       | 166       | 19.17%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo                | 246       | 28.44%  |
| Dell                  | 136       | 15.72%  |
| Hewlett-Packard       | 126       | 14.57%  |
| ASUSTek Computer      | 108       | 12.49%  |
| Acer                  | 64        | 7.4%    |
| HUAWEI                | 29        | 3.35%   |
| MSI                   | 24        | 2.77%   |
| Apple                 | 15        | 1.73%   |
| Timi                  | 12        | 1.39%   |
| Google                | 10        | 1.16%   |
| Toshiba               | 9         | 1.04%   |
| Samsung Electronics   | 9         | 1.04%   |
| TUXEDO                | 7         | 0.81%   |
| GPD                   | 5         | 0.58%   |
| Schenker              | 4         | 0.46%   |
| Alienware             | 4         | 0.46%   |
| System76              | 3         | 0.35%   |
| HONOR                 | 3         | 0.35%   |
| Fujitsu               | 3         | 0.35%   |
| Framework             | 3         | 0.35%   |
| Chuwi                 | 3         | 0.35%   |
| TECNO                 | 2         | 0.23%   |
| Standard              | 2         | 0.23%   |
| Sony                  | 2         | 0.23%   |
| SLIMBOOK              | 2         | 0.23%   |
| Pegatron              | 2         | 0.23%   |
| Notebook              | 2         | 0.23%   |
| MACHENIKE             | 2         | 0.23%   |
| Dynabook              | 2         | 0.23%   |
| Unknown               | 2         | 0.23%   |
| Valve                 | 1         | 0.12%   |
| UNOWHY                | 1         | 0.12%   |
| SiComputer            | 1         | 0.12%   |
| Razer                 | 1         | 0.12%   |
| Positivo Bahia - VAIO | 1         | 0.12%   |
| PC Specialist         | 1         | 0.12%   |
| Olivetti              | 1         | 0.12%   |
| Multilaser            | 1         | 0.12%   |
| Monster               | 1         | 0.12%   |
| MECHREVO              | 1         | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Dell XPS 13 7390                            | 5         | 0.58%   |
| Unknown                                     | 5         | 0.58%   |
| Lenovo ThinkBook 15 G3 ACL 21A4             | 4         | 0.46%   |
| Lenovo IdeaPad 330-15IKB 81DE               | 4         | 0.46%   |
| HUAWEI MACH-WX9                             | 4         | 0.46%   |
| HUAWEI CREM-WXX9                            | 4         | 0.46%   |
| HP OMEN by Laptop 16-c0xxx                  | 4         | 0.46%   |
| HP Notebook                                 | 4         | 0.46%   |
| Dell Inspiron 5566                          | 4         | 0.46%   |
| ASUS VivoBook_ASUSLaptop X515EA_X515EA      | 4         | 0.46%   |
| MSI Modern 14 B11MOU                        | 3         | 0.35%   |
| Lenovo Legion 5 15ACH6H 82JU                | 3         | 0.35%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK       | 3         | 0.35%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5            | 3         | 0.35%   |
| HUAWEI KLVL-WXX9                            | 3         | 0.35%   |
| HP ProBook 440 G7                           | 3         | 0.35%   |
| GPD G1619-04                                | 3         | 0.35%   |
| Dell XPS 15 9570                            | 3         | 0.35%   |
| Dell XPS 15 9520                            | 3         | 0.35%   |
| Dell XPS 15 9510                            | 3         | 0.35%   |
| Dell Latitude E7270                         | 3         | 0.35%   |
| Dell Latitude 7490                          | 3         | 0.35%   |
| Dell Latitude 7480                          | 3         | 0.35%   |
| Dell Latitude 5420                          | 3         | 0.35%   |
| ASUS VivoBook_ASUSLaptop M5402RA_M5402RA    | 3         | 0.35%   |
| Apple MacBookPro9,2                         | 3         | 0.35%   |
| Acer Predator PH315-52                      | 3         | 0.35%   |
| Acer Aspire A515-45                         | 3         | 0.35%   |
| Acer Aspire A315-59                         | 3         | 0.35%   |
| Timi Xiaomi NoteBook Pro                    | 2         | 0.23%   |
| Timi A35S                                   | 2         | 0.23%   |
| TECNO MEGABOOK T1                           | 2         | 0.23%   |
| MSI Stealth GS66 12UGS                      | 2         | 0.23%   |
| MACHENIKE MACHCREATOR-16                    | 2         | 0.23%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWCTO1WW  | 2         | 0.23%   |
| Lenovo ThinkPad X1 Carbon Gen 10 21CBCTO1WW | 2         | 0.23%   |
| Lenovo ThinkPad T14s Gen 1 20T1S39D0Y       | 2         | 0.23%   |
| Lenovo ThinkBook 16p Gen 2 20YM             | 2         | 0.23%   |
| Lenovo ThinkBook 15 G2 ITL 20VE             | 2         | 0.23%   |
| Lenovo ThinkBook 15 G2 ARE 20VG             | 2         | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 140       | 16.18%  |
| Lenovo IdeaPad      | 52        | 6.01%   |
| Dell Latitude       | 44        | 5.09%   |
| Dell Inspiron       | 41        | 4.74%   |
| Acer Aspire         | 34        | 3.93%   |
| ASUS VivoBook       | 33        | 3.82%   |
| HP EliteBook        | 25        | 2.89%   |
| Dell XPS            | 25        | 2.89%   |
| HP Pavilion         | 24        | 2.77%   |
| HP Laptop           | 23        | 2.66%   |
| Lenovo ThinkBook    | 22        | 2.54%   |
| HP ProBook          | 17        | 1.97%   |
| ASUS ROG            | 15        | 1.73%   |
| ASUS ASUS           | 15        | 1.73%   |
| Lenovo Legion       | 13        | 1.5%    |
| Acer Nitro          | 13        | 1.5%    |
| ASUS Zenbook        | 11        | 1.27%   |
| HP ZBook            | 9         | 1.04%   |
| Toshiba Satellite   | 8         | 0.92%   |
| Dell Vostro         | 8         | 0.92%   |
| Dell Precision      | 8         | 0.92%   |
| MSI Modern          | 7         | 0.81%   |
| Lenovo Yoga         | 7         | 0.81%   |
| HP OMEN             | 7         | 0.81%   |
| Acer Predator       | 7         | 0.81%   |
| HP ENVY             | 5         | 0.58%   |
| Acer Swift          | 5         | 0.58%   |
| Unknown             | 5         | 0.58%   |
| HUAWEI MACH-WX9     | 4         | 0.46%   |
| HUAWEI CREM-WXX9    | 4         | 0.46%   |
| HP Notebook         | 4         | 0.46%   |
| Apple MacBookPro9   | 4         | 0.46%   |
| TUXEDO InfinityBook | 3         | 0.35%   |
| Timi Xiaomi         | 3         | 0.35%   |
| MSI Stealth         | 3         | 0.35%   |
| HUAWEI KLVL-WXX9    | 3         | 0.35%   |
| HP Victus           | 3         | 0.35%   |
| GPD G1619-04        | 3         | 0.35%   |
| Fujitsu LIFEBOOK    | 3         | 0.35%   |
| Framework Laptop    | 3         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 174       | 20.12%  |
| 2022    | 139       | 16.07%  |
| 2020    | 130       | 15.03%  |
| 2019    | 84        | 9.71%   |
| 2018    | 83        | 9.6%    |
| 2017    | 55        | 6.36%   |
| 2016    | 40        | 4.62%   |
| 2013    | 33        | 3.82%   |
| 2012    | 33        | 3.82%   |
| 2015    | 29        | 3.35%   |
| 2014    | 20        | 2.31%   |
| 2011    | 15        | 1.73%   |
| 2010    | 10        | 1.16%   |
| 2008    | 9         | 1.04%   |
| 2023    | 4         | 0.46%   |
| 2009    | 3         | 0.35%   |
| 2007    | 2         | 0.23%   |
| 2006    | 1         | 0.12%   |
| Unknown | 1         | 0.12%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 865       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 617       | 70.84%  |
| Enabled  | 254       | 29.16%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 854       | 98.73%  |
| Yes  | 11        | 1.27%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 234       | 26.99%  |
| 16.01-24.0  | 206       | 23.76%  |
| 8.01-16.0   | 193       | 22.26%  |
| 32.01-64.0  | 111       | 12.8%   |
| 3.01-4.0    | 66        | 7.61%   |
| 24.01-32.0  | 22        | 2.54%   |
| 64.01-256.0 | 22        | 2.54%   |
| 1.01-2.0    | 11        | 1.27%   |
| 2.01-3.0    | 2         | 0.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 314       | 34.35%  |
| 2.01-3.0   | 216       | 23.63%  |
| 3.01-4.0   | 211       | 23.09%  |
| 8.01-16.0  | 76        | 8.32%   |
| 1.01-2.0   | 75        | 8.21%   |
| 16.01-24.0 | 11        | 1.2%    |
| 0.51-1.0   | 8         | 0.88%   |
| 32.01-64.0 | 2         | 0.22%   |
| 24.01-32.0 | 1         | 0.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 646       | 74.42%  |
| 2      | 196       | 22.58%  |
| 3      | 16        | 1.84%   |
| 4      | 5         | 0.58%   |
| 0      | 5         | 0.58%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 749       | 86.49%  |
| Yes       | 117       | 13.51%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 584       | 67.51%  |
| No        | 281       | 32.49%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 843       | 97.34%  |
| No        | 23        | 2.66%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 757       | 87.21%  |
| No        | 111       | 12.79%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 124       | 14.29%  |
| Russia       | 77        | 8.87%   |
| Germany      | 66        | 7.6%    |
| Brazil       | 51        | 5.88%   |
| Italy        | 47        | 5.41%   |
| India        | 43        | 4.95%   |
| France       | 35        | 4.03%   |
| Poland       | 30        | 3.46%   |
| Canada       | 28        | 3.23%   |
| Turkey       | 20        | 2.3%    |
| Spain        | 20        | 2.3%    |
| UK           | 19        | 2.19%   |
| Australia    | 19        | 2.19%   |
| Netherlands  | 16        | 1.84%   |
| Austria      | 16        | 1.84%   |
| Mexico       | 14        | 1.61%   |
| Taiwan       | 10        | 1.15%   |
| Switzerland  | 10        | 1.15%   |
| Sweden       | 10        | 1.15%   |
| Czechia      | 9         | 1.04%   |
| Indonesia    | 8         | 0.92%   |
| Hungary      | 8         | 0.92%   |
| Chile        | 8         | 0.92%   |
| Argentina    | 8         | 0.92%   |
| Israel       | 7         | 0.81%   |
| Serbia       | 6         | 0.69%   |
| Belgium      | 6         | 0.69%   |
| Thailand     | 5         | 0.58%   |
| Slovakia     | 5         | 0.58%   |
| Romania      | 5         | 0.58%   |
| Portugal     | 5         | 0.58%   |
| Norway       | 5         | 0.58%   |
| Hong Kong    | 5         | 0.58%   |
| Finland      | 5         | 0.58%   |
| Ukraine      | 4         | 0.46%   |
| South Africa | 4         | 0.46%   |
| Philippines  | 4         | 0.46%   |
| Peru         | 4         | 0.46%   |
| Japan        | 4         | 0.46%   |
| Ireland      | 4         | 0.46%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 21        | 2.35%   |
| Vienna            | 10        | 1.12%   |
| Madrid            | 10        | 1.12%   |
| St Petersburg     | 9         | 1.01%   |
| Istanbul          | 8         | 0.9%    |
| Berlin            | 8         | 0.9%    |
| Sao Paulo         | 7         | 0.78%   |
| Warsaw            | 6         | 0.67%   |
| Milan             | 6         | 0.67%   |
| Frankfurt am Main | 6         | 0.67%   |
| Brisbane          | 6         | 0.67%   |
| Santiago          | 5         | 0.56%   |
| Montreal          | 5         | 0.56%   |
| Melbourne         | 5         | 0.56%   |
| London            | 5         | 0.56%   |
| Izmir             | 5         | 0.56%   |
| Amsterdam         | 5         | 0.56%   |
| Zurich            | 4         | 0.45%   |
| Sydney            | 4         | 0.45%   |
| Pune              | 4         | 0.45%   |
| Paris             | 4         | 0.45%   |
| New Taipei        | 4         | 0.45%   |
| Miami             | 4         | 0.45%   |
| Jakarta           | 4         | 0.45%   |
| Gdansk            | 4         | 0.45%   |
| Curitiba          | 4         | 0.45%   |
| Central           | 4         | 0.45%   |
| Cape Town         | 4         | 0.45%   |
| Budapest          | 4         | 0.45%   |
| Bengaluru         | 4         | 0.45%   |
| Bangkok           | 4         | 0.45%   |
| Zapopan           | 3         | 0.34%   |
| Yerevan           | 3         | 0.34%   |
| Wroclaw           | 3         | 0.34%   |
| Tbilisi           | 3         | 0.34%   |
| San Jose          | 3         | 0.34%   |
| Saint Paul        | 3         | 0.34%   |
| Prague            | 3         | 0.34%   |
| Porto Alegre      | 3         | 0.34%   |
| Portland          | 3         | 0.34%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 247       | 295    | 23.11%  |
| Sandisk                        | 92        | 104    | 8.61%   |
| WDC                            | 89        | 98     | 8.33%   |
| SK hynix                       | 79        | 86     | 7.39%   |
| Micron Technology              | 56        | 64     | 5.24%   |
| Toshiba                        | 55        | 58     | 5.14%   |
| Kingston                       | 52        | 58     | 4.86%   |
| Seagate                        | 48        | 52     | 4.49%   |
| Intel                          | 46        | 52     | 4.3%    |
| Unknown                        | 39        | 46     | 3.65%   |
| Crucial                        | 39        | 41     | 3.65%   |
| KIOXIA                         | 30        | 35     | 2.81%   |
| HGST                           | 14        | 16     | 1.31%   |
| Apple                          | 12        | 18     | 1.12%   |
| A-DATA Technology              | 11        | 12     | 1.03%   |
| LITEON                         | 9         | 9      | 0.84%   |
| Micron/Crucial Technology      | 8         | 9      | 0.75%   |
| Phison Electronics             | 7         | 8      | 0.65%   |
| Kingston Technology Company    | 7         | 7      | 0.65%   |
| Hitachi                        | 7         | 7      | 0.65%   |
| China                          | 7         | 8      | 0.65%   |
| ADATA Technology               | 7         | 8      | 0.65%   |
| PNY                            | 6         | 6      | 0.56%   |
| Unknown                        | 6         | 7      | 0.56%   |
| UMIS                           | 5         | 5      | 0.47%   |
| SPCC                           | 4         | 4      | 0.37%   |
| Phison                         | 4         | 4      | 0.37%   |
| Lexar                          | 4         | 4      | 0.37%   |
| HS-SSD-E100                    | 4         | 4      | 0.37%   |
| FORESEE                        | 4         | 4      | 0.37%   |
| YMTC                           | 3         | 3      | 0.28%   |
| XPG                            | 3         | 3      | 0.28%   |
| Silicon Motion                 | 3         | 3      | 0.28%   |
| Realtek Semiconductor          | 3         | 3      | 0.28%   |
| Netac                          | 3         | 5      | 0.28%   |
| Lenovo                         | 3         | 3      | 0.28%   |
| Intenso                        | 3         | 4      | 0.28%   |
| Apacer                         | 3         | 4      | 0.28%   |
| Solid State Storage Technology | 2         | 2      | 0.19%   |
| Solid State Storage            | 2         | 2      | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB  | 41        | 3.73%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 960GB | 22        | 2%      |
| Toshiba MQ04ABF100 1TB                               | 15        | 1.36%   |
| Seagate ST1000LM035-1RK172 1TB                       | 15        | 1.36%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB     | 15        | 1.36%   |
| Kingston SA400S37240G 240GB SSD                      | 12        | 1.09%   |
| Intel SSDPEKNU512GZ 512GB                            | 12        | 1.09%   |
| Crucial CT240BX500SSD1 240GB                         | 11        | 1%      |
| Sandisk WD Blue SN550 NVMe SSD 1TB                   | 10        | 0.91%   |
| Unknown MMC Card  32GB                               | 9         | 0.82%   |
| Samsung MZALQ512HBLU-00BL2 512GB                     | 9         | 0.82%   |
| SK hynix BC501 NVMe Solid State Drive 512GB          | 7         | 0.64%   |
| Samsung SSD 980 PRO 1TB                              | 7         | 0.64%   |
| KIOXIA KBG40ZNV512G 512GB                            | 7         | 0.64%   |
| HGST HTS721010A9E630 1TB                             | 7         | 0.64%   |
| Crucial CT1000MX500SSD1 1TB                          | 7         | 0.64%   |
| Unknown MMC Card  64GB                               | 6         | 0.55%   |
| Toshiba XG6 NVMe SSD Controller 512GB                | 6         | 0.55%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 256GB      | 6         | 0.55%   |
| Micron 2210_MTFDHBA512QFD 512GB                      | 6         | 0.55%   |
| Unknown                                              | 6         | 0.55%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                     | 5         | 0.45%   |
| WDC WD10SPZX-21Z10T0 1TB                             | 5         | 0.45%   |
| SK hynix SKHynix_HFS512GDE9X081N 512GB               | 5         | 0.45%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 5         | 0.45%   |
| Sandisk WD Black SN850 500GB                         | 5         | 0.45%   |
| SanDisk NVMe SSD Drive 1TB                           | 5         | 0.45%   |
| Samsung SSD 980 1TB                                  | 5         | 0.45%   |
| Samsung SSD 870 EVO 500GB                            | 5         | 0.45%   |
| Samsung SSD 860 EVO 500GB                            | 5         | 0.45%   |
| Samsung SSD 860 EVO 250GB                            | 5         | 0.45%   |
| Samsung MZVLQ512HBLU-00B00 512GB                     | 5         | 0.45%   |
| Samsung MZVLQ512HALU-000H1 512GB                     | 5         | 0.45%   |
| Samsung MZVL21T0HCLR-00B00 1TB                       | 5         | 0.45%   |
| Samsung MZALQ512HALU-000L2 512GB                     | 5         | 0.45%   |
| Intel SSD 660P Series 1024GB                         | 5         | 0.45%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                     | 4         | 0.36%   |
| Toshiba MQ01ABD100 1TB                               | 4         | 0.36%   |
| SK hynix HFM256GD3JX016N 256GB                       | 4         | 0.36%   |
| Seagate ST500LT012-1DG142 500GB                      | 4         | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 47        | 51     | 32.87%  |
| Toshiba  | 34        | 34     | 23.78%  |
| WDC      | 33        | 36     | 23.08%  |
| HGST     | 14        | 16     | 9.79%   |
| Hitachi  | 7         | 7      | 4.9%    |
| Unknown  | 3         | 4      | 2.1%    |
| SABRENT  | 2         | 2      | 1.4%    |
| Intenso  | 1         | 1      | 0.7%    |
| HGST HTS | 1         | 1      | 0.7%    |
| External | 1         | 1      | 0.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 54        | 61     | 21.34%  |
| Kingston            | 31        | 33     | 12.25%  |
| Crucial             | 31        | 33     | 12.25%  |
| SanDisk             | 21        | 23     | 8.3%    |
| WDC                 | 19        | 20     | 7.51%   |
| Micron Technology   | 12        | 12     | 4.74%   |
| SK hynix            | 11        | 11     | 4.35%   |
| Apple               | 8         | 9      | 3.16%   |
| LITEON              | 7         | 7      | 2.77%   |
| China               | 7         | 8      | 2.77%   |
| PNY                 | 6         | 6      | 2.37%   |
| Toshiba             | 5         | 5      | 1.98%   |
| SPCC                | 3         | 3      | 1.19%   |
| Lexar               | 3         | 3      | 1.19%   |
| Intenso             | 3         | 3      | 1.19%   |
| Intel               | 3         | 3      | 1.19%   |
| Apacer              | 3         | 4      | 1.19%   |
| A-DATA Technology   | 3         | 3      | 1.19%   |
| Netac               | 2         | 3      | 0.79%   |
| Gigabyte Technology | 2         | 3      | 0.79%   |
| FORESEE             | 2         | 2      | 0.79%   |
| Unknown             | 2         | 2      | 0.79%   |
| XrayDisk            | 1         | 1      | 0.4%    |
| Teclast             | 1         | 2      | 0.4%    |
| Team                | 1         | 2      | 0.4%    |
| Ramaxel Technology  | 1         | 1      | 0.4%    |
| Patriot             | 1         | 1      | 0.4%    |
| OCZ                 | 1         | 1      | 0.4%    |
| MidasForce          | 1         | 1      | 0.4%    |
| LITEONIT            | 1         | 1      | 0.4%    |
| JAMESDONKEY         | 1         | 1      | 0.4%    |
| HS-SSD-C100         | 1         | 1      | 0.4%    |
| GOODRAM             | 1         | 2      | 0.4%    |
| G521N               | 1         | 1      | 0.4%    |
| ExeGate             | 1         | 1      | 0.4%    |
| Eluktro             | 1         | 1      | 0.4%    |
| Dahua               | 1         | 2      | 0.4%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 577       | 720    | 56.9%   |
| SSD     | 243       | 276    | 23.96%  |
| HDD     | 139       | 153    | 13.71%  |
| MMC     | 40        | 46     | 3.94%   |
| Unknown | 15        | 15     | 1.48%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 576       | 718    | 58.66%  |
| SATA | 338       | 416    | 34.42%  |
| MMC  | 40        | 46     | 4.07%   |
| SAS  | 28        | 30     | 2.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 238       | 279    | 62.96%  |
| 0.51-1.0   | 126       | 135    | 33.33%  |
| 1.01-2.0   | 10        | 11     | 2.65%   |
| 3.01-4.0   | 2         | 2      | 0.53%   |
| 4.01-10.0  | 2         | 2      | 0.53%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 501-1000       | 205       | 23.38%  |
| 251-500        | 190       | 21.66%  |
| 1-20           | 121       | 13.8%   |
| 1001-2000      | 107       | 12.2%   |
| 101-250        | 101       | 11.52%  |
| Unknown        | 83        | 9.46%   |
| More than 3000 | 21        | 2.39%   |
| 51-100         | 18        | 2.05%   |
| 21-50          | 16        | 1.82%   |
| 2001-3000      | 15        | 1.71%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 267       | 29.73%  |
| 21-50          | 147       | 16.37%  |
| 101-250        | 136       | 15.14%  |
| 51-100         | 108       | 12.03%  |
| 251-500        | 84        | 9.35%   |
| Unknown        | 83        | 9.24%   |
| 501-1000       | 54        | 6.01%   |
| 1001-2000      | 15        | 1.67%   |
| More than 3000 | 2         | 0.22%   |
| 2001-3000      | 2         | 0.22%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 1         | 1      | 4.17%   |
| WDC WD5000LPVX-22V0TT0 500GB                        | 1         | 1      | 4.17%   |
| WDC WD10JPVX-60JC3T1 1TB                            | 1         | 1      | 4.17%   |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 4.17%   |
| Toshiba MK5061GSY 500GB                             | 1         | 1      | 4.17%   |
| Toshiba MK3265GSX 320GB                             | 1         | 1      | 4.17%   |
| Toshiba MK1237GSX 120GB                             | 1         | 1      | 4.17%   |
| SK hynix HFS128G39TND-N210A 128GB SSD               | 1         | 1      | 4.17%   |
| Seagate ST9500325AS 500GB                           | 1         | 1      | 4.17%   |
| Seagate ST9320325AS 320GB                           | 1         | 1      | 4.17%   |
| Seagate ST500LT012-1DG142 500GB                     | 1         | 1      | 4.17%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 1         | 1      | 4.17%   |
| Seagate ST500LM000-SSHD-8GB                         | 1         | 1      | 4.17%   |
| Seagate ST4000LM024-2AN17V 4TB                      | 1         | 1      | 4.17%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 1      | 4.17%   |
| Samsung Electronics SSD 980 1TB                     | 1         | 1      | 4.17%   |
| Samsung Electronics SSD 870 EVO 500GB               | 1         | 2      | 4.17%   |
| Samsung Electronics PM9A1 NVMe 1024GB               | 1         | 1      | 4.17%   |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1      | 4.17%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD      | 1         | 1      | 4.17%   |
| HGST HTS721010A9E630 1TB                            | 1         | 1      | 4.17%   |
| HGST HTS541075A9E680 752GB                          | 1         | 1      | 4.17%   |
| HGST HTS 545050A7E680 500GB                         | 1         | 1      | 4.17%   |
| Unknown                                             | 1         | 1      | 4.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 7      | 29.17%  |
| Toshiba             | 4         | 4      | 16.67%  |
| WDC                 | 3         | 3      | 12.5%   |
| Samsung Electronics | 3         | 4      | 12.5%   |
| Micron Technology   | 2         | 2      | 8.33%   |
| HGST                | 2         | 2      | 8.33%   |
| SK hynix            | 1         | 1      | 4.17%   |
| HGST HTS            | 1         | 1      | 4.17%   |
| Unknown             | 1         | 1      | 4.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 7         | 7      | 43.75%  |
| Toshiba  | 4         | 4      | 25%     |
| WDC      | 2         | 2      | 12.5%   |
| HGST     | 2         | 2      | 12.5%   |
| HGST HTS | 1         | 1      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 16        | 16     | 66.67%  |
| SSD  | 6         | 7      | 25%     |
| NVMe | 2         | 2      | 8.33%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 980 1TB                  | 1         | 1      | 50%     |
| Samsung Electronics MZNTY128HDHP-00000 128GB SSD | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 489       | 689    | 53.91%  |
| Works    | 392       | 494    | 43.22%  |
| Malfunc  | 24        | 25     | 2.65%   |
| Failed   | 2         | 2      | 0.22%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 470       | 40.38%  |
| Samsung Electronics            | 201       | 17.27%  |
| AMD                            | 110       | 9.45%   |
| SanDisk                        | 109       | 9.36%   |
| SK hynix                       | 68        | 5.84%   |
| Micron Technology              | 45        | 3.87%   |
| Kingston Technology Company    | 28        | 2.41%   |
| KIOXIA                         | 27        | 2.32%   |
| Toshiba America Info Systems   | 22        | 1.89%   |
| ADATA Technology               | 15        | 1.29%   |
| Micron/Crucial Technology      | 14        | 1.2%    |
| Phison Electronics             | 12        | 1.03%   |
| Union Memory (Shenzhen)        | 7         | 0.6%    |
| Solid State Storage Technology | 5         | 0.43%   |
| Realtek Semiconductor          | 5         | 0.43%   |
| Yangtze Memory Technologies    | 4         | 0.34%   |
| Silicon Motion                 | 4         | 0.34%   |
| Lite-On Technology             | 4         | 0.34%   |
| Shenzhen Longsys Electronics   | 3         | 0.26%   |
| Lenovo                         | 3         | 0.26%   |
| Apple                          | 3         | 0.26%   |
| Biwin Storage Technology       | 2         | 0.17%   |
| Netac Technology               | 1         | 0.09%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.09%   |
| Marvell Technology Group       | 1         | 0.09%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 107       | 8.78%   |
| Intel Volume Management Device NVMe RAID Controller                            | 77        | 6.32%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 72        | 5.91%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 71        | 5.82%   |
| Samsung NVMe SSD Controller 980                                                | 64        | 5.25%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 55        | 4.51%   |
| Micron Non-Volatile memory controller                                          | 45        | 3.69%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 42        | 3.45%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 42        | 3.45%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 35        | 2.87%   |
| SanDisk Non-Volatile memory controller                                         | 29        | 2.38%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 29        | 2.38%   |
| Intel Tiger Lake-LP SATA Controller                                            | 27        | 2.21%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 24        | 1.97%   |
| Intel Non-Volatile memory controller                                           | 23        | 1.89%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 22        | 1.8%    |
| Intel Comet Lake SATA AHCI Controller                                          | 19        | 1.56%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 18        | 1.48%   |
| Kingston Company Company Non-Volatile memory controller                        | 16        | 1.31%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 16        | 1.31%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 15        | 1.23%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 14        | 1.15%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 13        | 1.07%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 13        | 1.07%   |
| KIOXIA Non-Volatile memory controller                                          | 12        | 0.98%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 12        | 0.98%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 11        | 0.9%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 10        | 0.82%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 10        | 0.82%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 10        | 0.82%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 9         | 0.74%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 9         | 0.74%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 9         | 0.74%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 8         | 0.66%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 8         | 0.66%   |
| Intel SSD 660P Series                                                          | 8         | 0.66%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 8         | 0.66%   |
| SK hynix Non-Volatile memory controller                                        | 7         | 0.57%   |
| SanDisk WD Blue SN570 NVMe SSD                                                 | 7         | 0.57%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 7         | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 575       | 49.36%  |
| SATA | 464       | 39.83%  |
| RAID | 121       | 10.39%  |
| IDE  | 5         | 0.43%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 633       | 73.18%  |
| AMD     | 231       | 26.71%  |
| Unknown | 1         | 0.12%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 33        | 3.82%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 22        | 2.54%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 22        | 2.54%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 17        | 1.97%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 17        | 1.97%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 17        | 1.97%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 15        | 1.73%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 14        | 1.62%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 13        | 1.5%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 13        | 1.5%    |
| Intel 12th Gen Core i7-12700H                 | 13        | 1.5%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 12        | 1.39%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 12        | 1.39%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 12        | 1.39%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 11        | 1.27%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 11        | 1.27%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 11        | 1.27%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 11        | 1.27%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 10        | 1.16%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 10        | 1.16%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 10        | 1.16%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 9         | 1.04%   |
| Intel 12th Gen Core i9-12900H                 | 9         | 1.04%   |
| Intel 12th Gen Core i5-1240P                  | 9         | 1.04%   |
| Intel 12th Gen Core i5-1235U                  | 9         | 1.04%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 9         | 1.04%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 8         | 0.92%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 8         | 0.92%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 8         | 0.92%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 8         | 0.92%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 7         | 0.81%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 7         | 0.81%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 7         | 0.81%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 7         | 0.81%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 6         | 0.69%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 6         | 0.69%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 6         | 0.69%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 6         | 0.69%   |
| Intel 12th Gen Core i7-1255U                  | 6         | 0.69%   |
| Intel 12th Gen Core i5-12500H                 | 6         | 0.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5                        | 187       | 21.62%  |
| Other                                | 184       | 21.27%  |
| Intel Core i7                        | 164       | 18.96%  |
| AMD Ryzen 7                          | 79        | 9.13%   |
| AMD Ryzen 5                          | 70        | 8.09%   |
| Intel Core i3                        | 40        | 4.62%   |
| Intel Celeron                        | 21        | 2.43%   |
| AMD Ryzen 7 PRO                      | 19        | 2.2%    |
| AMD Ryzen 9                          | 17        | 1.97%   |
| AMD Ryzen 3                          | 14        | 1.62%   |
| AMD Ryzen 5 PRO                      | 13        | 1.5%    |
| Intel Core 2 Duo                     | 10        | 1.16%   |
| Intel Pentium                        | 7         | 0.81%   |
| Intel Core i9                        | 6         | 0.69%   |
| Intel Atom                           | 6         | 0.69%   |
| AMD A6                               | 5         | 0.58%   |
| AMD A4                               | 5         | 0.58%   |
| Intel Pentium Silver                 | 3         | 0.35%   |
| Intel Pentium Dual-Core              | 2         | 0.23%   |
| Intel Core m3                        | 2         | 0.23%   |
| AMD A8                               | 2         | 0.23%   |
| AMD A12                              | 2         | 0.23%   |
| Intel Genuine                        | 1         | 0.12%   |
| Intel Core m5                        | 1         | 0.12%   |
| Intel Core 2                         | 1         | 0.12%   |
| AMD Turion X2 Ultra Dual-Core Mobile | 1         | 0.12%   |
| AMD E1                               | 1         | 0.12%   |
| AMD E                                | 1         | 0.12%   |
| AMD A10                              | 1         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 310       | 35.84%  |
| 2      | 239       | 27.63%  |
| 8      | 136       | 15.72%  |
| 6      | 106       | 12.25%  |
| 14     | 27        | 3.12%   |
| 12     | 23        | 2.66%   |
| 10     | 19        | 2.2%    |
| 16     | 2         | 0.23%   |
| 1      | 2         | 0.23%   |
| 5      | 1         | 0.12%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 865       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 782       | 90.3%   |
| 1      | 84        | 9.7%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 864       | 99.88%  |
| 64-bit         | 1         | 0.12%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806c1    | 72        | 8.27%   |
| 0x806ec    | 55        | 6.31%   |
| 0x906a3    | 51        | 5.86%   |
| 0x0a50000c | 51        | 5.86%   |
| Unknown    | 48        | 5.51%   |
| 0x806ea    | 47        | 5.4%    |
| 0x306a9    | 38        | 4.36%   |
| 0x906ea    | 33        | 3.79%   |
| 0x406e3    | 33        | 3.79%   |
| 0x806e9    | 27        | 3.1%    |
| 0xa0652    | 25        | 2.87%   |
| 0x08600106 | 25        | 2.87%   |
| 0x08608103 | 23        | 2.64%   |
| 0x806d1    | 21        | 2.41%   |
| 0x306d4    | 21        | 2.41%   |
| 0x906a4    | 20        | 2.3%    |
| 0x40651    | 18        | 2.07%   |
| 0x0a404102 | 18        | 2.07%   |
| 0x08108109 | 18        | 2.07%   |
| 0x206a7    | 17        | 1.95%   |
| 0x506e3    | 14        | 1.61%   |
| 0x706e5    | 13        | 1.49%   |
| 0x08600104 | 13        | 1.49%   |
| 0x906e9    | 12        | 1.38%   |
| 0x306c3    | 11        | 1.26%   |
| 0x0a404101 | 10        | 1.15%   |
| 0x806c2    | 9         | 1.03%   |
| 0x706a8    | 9         | 1.03%   |
| 0x1067a    | 8         | 0.92%   |
| 0x0a50000d | 8         | 0.92%   |
| 0x806eb    | 7         | 0.8%    |
| 0x08608102 | 7         | 0.8%    |
| 0x0810100b | 7         | 0.8%    |
| 0x30678    | 6         | 0.69%   |
| 0x06006705 | 6         | 0.69%   |
| 0x08108102 | 5         | 0.57%   |
| 0x506c9    | 4         | 0.46%   |
| 0x20655    | 4         | 0.46%   |
| 0xa0660    | 3         | 0.34%   |
| 0x906ed    | 3         | 0.34%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 198       | 22.89%  |
| TigerLake        | 85        | 9.83%   |
| Alderlake Hybrid | 73        | 8.44%   |
| Zen 3            | 68        | 7.86%   |
| Unknown          | 67        | 7.75%   |
| Skylake          | 48        | 5.55%   |
| Zen 2            | 45        | 5.2%    |
| IvyBridge        | 39        | 4.51%   |
| IceLake          | 36        | 4.16%   |
| Haswell          | 31        | 3.58%   |
| CometLake        | 28        | 3.24%   |
| Zen+             | 24        | 2.77%   |
| Broadwell        | 21        | 2.43%   |
| SandyBridge      | 17        | 1.97%   |
| Zen              | 14        | 1.62%   |
| Silvermont       | 13        | 1.5%    |
| Penryn           | 10        | 1.16%   |
| Goldmont plus    | 10        | 1.16%   |
| Excavator        | 9         | 1.04%   |
| Westmere         | 7         | 0.81%   |
| Goldmont         | 4         | 0.46%   |
| Core             | 4         | 0.46%   |
| Tremont          | 3         | 0.35%   |
| Steamroller      | 2         | 0.23%   |
| Jaguar           | 2         | 0.23%   |
| Puma             | 1         | 0.12%   |
| Piledriver       | 1         | 0.12%   |
| Nehalem          | 1         | 0.12%   |
| K8 & K10 hybrid  | 1         | 0.12%   |
| K10 Llano        | 1         | 0.12%   |
| Bonnell          | 1         | 0.12%   |
| Bobcat           | 1         | 0.12%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 609       | 53.05%  |
| Nvidia | 284       | 24.74%  |
| AMD    | 255       | 22.21%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 74        | 6.32%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 54        | 4.62%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 48        | 4.1%    |
| Intel UHD Graphics 620                                                                | 44        | 3.76%   |
| AMD Renoir                                                                            | 44        | 3.76%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 37        | 3.16%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 35        | 2.99%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 35        | 2.99%   |
| Intel HD Graphics 620                                                                 | 33        | 2.82%   |
| AMD Lucienne                                                                          | 33        | 2.82%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 31        | 2.65%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 30        | 2.56%   |
| AMD Rembrandt [Radeon 680M]                                                           | 28        | 2.39%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 25        | 2.14%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 24        | 2.05%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 24        | 2.05%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 20        | 1.71%   |
| Intel HD Graphics 5500                                                                | 19        | 1.62%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 18        | 1.54%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 17        | 1.45%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                           | 16        | 1.37%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 15        | 1.28%   |
| Nvidia GP108M [GeForce MX150]                                                         | 14        | 1.2%    |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 13        | 1.11%   |
| Intel HD Graphics 630                                                                 | 13        | 1.11%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                      | 13        | 1.11%   |
| AMD Barcelo                                                                           | 13        | 1.11%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 12        | 1.03%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                               | 11        | 0.94%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                            | 11        | 0.94%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 11        | 0.94%   |
| Intel HD Graphics 530                                                                 | 11        | 0.94%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                             | 10        | 0.85%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 10        | 0.85%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 9         | 0.77%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 9         | 0.77%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 8         | 0.68%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 8         | 0.68%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                            | 7         | 0.6%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                              | 7         | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 366       | 42.31%  |
| Intel + Nvidia     | 217       | 25.09%  |
| 1 x AMD            | 176       | 20.35%  |
| AMD + Nvidia       | 42        | 4.86%   |
| 1 x Nvidia         | 22        | 2.54%   |
| Intel + AMD        | 20        | 2.31%   |
| 2 x AMD            | 17        | 1.97%   |
| 2 x Intel          | 3         | 0.35%   |
| Other              | 1         | 0.12%   |
| Intel + 2 x Nvidia | 1         | 0.12%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 700       | 80.55%  |
| Proprietary | 151       | 17.38%  |
| Unknown     | 18        | 2.07%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 526       | 60.32%  |
| 0.01-0.5   | 123       | 14.11%  |
| 1.01-2.0   | 88        | 10.09%  |
| 3.01-4.0   | 62        | 7.11%   |
| 0.51-1.0   | 41        | 4.7%    |
| 5.01-6.0   | 18        | 2.06%   |
| 7.01-8.0   | 8         | 0.92%   |
| 2.01-3.0   | 4         | 0.46%   |
| 8.01-16.0  | 2         | 0.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 198       | 19.04%  |
| AU Optronics            | 186       | 17.88%  |
| Chimei Innolux          | 151       | 14.52%  |
| LG Display              | 115       | 11.06%  |
| Samsung Electronics     | 62        | 5.96%   |
| Dell                    | 31        | 2.98%   |
| Sharp                   | 30        | 2.88%   |
| Goldstar                | 26        | 2.5%    |
| CSO                     | 25        | 2.4%    |
| PANDA                   | 22        | 2.12%   |
| Lenovo                  | 18        | 1.73%   |
| AOC                     | 16        | 1.54%   |
| Hewlett-Packard         | 14        | 1.35%   |
| Apple                   | 14        | 1.35%   |
| Acer                    | 14        | 1.35%   |
| InfoVision              | 12        | 1.15%   |
| BenQ                    | 11        | 1.06%   |
| ViewSonic               | 8         | 0.77%   |
| ASUSTek Computer        | 8         | 0.77%   |
| Philips                 | 7         | 0.67%   |
| JDI                     | 7         | 0.67%   |
| Chi Mei Optoelectronics | 6         | 0.58%   |
| Toshiba                 | 4         | 0.38%   |
| TMX                     | 4         | 0.38%   |
| Mi                      | 4         | 0.38%   |
| Sony                    | 3         | 0.29%   |
| Vestel Elektronik       | 2         | 0.19%   |
| Tianma XM               | 2         | 0.19%   |
| Panasonic               | 2         | 0.19%   |
| NCS                     | 2         | 0.19%   |
| MSI                     | 2         | 0.19%   |
| LG Philips              | 2         | 0.19%   |
| Iiyama                  | 2         | 0.19%   |
| HUAWEI                  | 2         | 0.19%   |
| Gigabyte Technology     | 2         | 0.19%   |
| Ancor Communications    | 2         | 0.19%   |
| Vizio                   | 1         | 0.1%    |
| Valve                   | 1         | 0.1%    |
| Sceptre Tech            | 1         | 0.1%    |
| Pixio                   | 1         | 0.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 13        | 1.24%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 13        | 1.24%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 13        | 1.24%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 10        | 0.95%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 10        | 0.95%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 9         | 0.86%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 8         | 0.76%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 8         | 0.76%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 6         | 0.57%   |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch      | 6         | 0.57%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 6         | 0.57%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 6         | 0.57%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 5         | 0.48%   |
| Samsung Electronics LCD Monitor SDC416D 2880x1800 312x195mm 14.5-inch | 5         | 0.48%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 5         | 0.48%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 5         | 0.48%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                 | 5         | 0.48%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch        | 5         | 0.48%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch        | 5         | 0.48%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 5         | 0.48%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch          | 4         | 0.38%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 4         | 0.38%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 4         | 0.38%   |
| JDI LCD Monitor JDI422A 3000x2000 293x196mm 13.9-inch                 | 4         | 0.38%   |
| CSO LCD Monitor CSO160A 2560x1600 345x215mm 16.0-inch                 | 4         | 0.38%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 4         | 0.38%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch      | 4         | 0.38%   |
| BOE LCD Monitor BOE092F 2520x1680 338x226mm 16.0-inch                 | 4         | 0.38%   |
| BOE LCD Monitor BOE08D5 1920x1080 344x194mm 15.5-inch                 | 4         | 0.38%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                 | 4         | 0.38%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 4         | 0.38%   |
| AU Optronics LCD Monitor AUOA08B 1920x1080 344x193mm 15.5-inch        | 4         | 0.38%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch        | 4         | 0.38%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch        | 4         | 0.38%   |
| Toshiba ScreenXpert TSB8888 1080x2160                                 | 3         | 0.29%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch               | 3         | 0.29%   |
| Mi Monitor XMI3446 3440x1440 797x334mm 34.0-inch                      | 3         | 0.29%   |
| LG Display LCD Monitor LGD06B3 1920x1200 336x210mm 15.6-inch          | 3         | 0.29%   |
| LG Display LCD Monitor LGD068D 1920x1080 309x174mm 14.0-inch          | 3         | 0.29%   |
| LG Display LCD Monitor LGD05D0 1920x1080 344x194mm 15.5-inch          | 3         | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 514       | 53.21%  |
| 1366x768 (WXGA)    | 135       | 13.98%  |
| 3840x2160 (4K)     | 50        | 5.18%   |
| 2560x1440 (QHD)    | 44        | 4.55%   |
| 2560x1600          | 38        | 3.93%   |
| 1920x1200 (WUXGA)  | 38        | 3.93%   |
| 1600x900 (HD+)     | 29        | 3%      |
| 2880x1800          | 22        | 2.28%   |
| 3440x1440          | 12        | 1.24%   |
| 1280x800 (WXGA)    | 9         | 0.93%   |
| 3840x2400          | 7         | 0.72%   |
| 2560x1080          | 7         | 0.72%   |
| 2160x1440          | 7         | 0.72%   |
| 3000x2000          | 6         | 0.62%   |
| 1280x1024 (SXGA)   | 6         | 0.62%   |
| 2256x1504          | 5         | 0.52%   |
| 3456x2160          | 4         | 0.41%   |
| 2520x1680          | 4         | 0.41%   |
| 1440x900 (WXGA+)   | 4         | 0.41%   |
| 1680x1050 (WSXGA+) | 3         | 0.31%   |
| 1360x768           | 3         | 0.31%   |
| 3840x1080          | 2         | 0.21%   |
| 3200x2000          | 2         | 0.21%   |
| 3072x1920          | 2         | 0.21%   |
| 2240x1400          | 2         | 0.21%   |
| 2160x1350          | 2         | 0.21%   |
| 1024x768 (XGA)     | 2         | 0.21%   |
| 800x1280           | 1         | 0.1%    |
| 3200x1800 (QHD+)   | 1         | 0.1%    |
| 2880x864           | 1         | 0.1%    |
| 2880x1620          | 1         | 0.1%    |
| 2304x1440          | 1         | 0.1%    |
| 1920x540           | 1         | 0.1%    |
| 1024x600           | 1         | 0.1%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 409       | 39.1%   |
| 13      | 161       | 15.39%  |
| 14      | 153       | 14.63%  |
| 27      | 52        | 4.97%   |
| 17      | 45        | 4.3%    |
| 16      | 39        | 3.73%   |
| 24      | 37        | 3.54%   |
| 23      | 27        | 2.58%   |
| 12      | 19        | 1.82%   |
| 34      | 15        | 1.43%   |
| 21      | 15        | 1.43%   |
| 31      | 12        | 1.15%   |
| 11      | 9         | 0.86%   |
| 40      | 6         | 0.57%   |
| 18      | 6         | 0.57%   |
| Unknown | 5         | 0.48%   |
| 20      | 4         | 0.38%   |
| 19      | 4         | 0.38%   |
| 84      | 3         | 0.29%   |
| 72      | 3         | 0.29%   |
| 32      | 3         | 0.29%   |
| 26      | 3         | 0.29%   |
| 48      | 2         | 0.19%   |
| 29      | 2         | 0.19%   |
| 28      | 2         | 0.19%   |
| 25      | 2         | 0.19%   |
| 69      | 1         | 0.1%    |
| 54      | 1         | 0.1%    |
| 47      | 1         | 0.1%    |
| 39      | 1         | 0.1%    |
| 38      | 1         | 0.1%    |
| 35      | 1         | 0.1%    |
| 10      | 1         | 0.1%    |
| 7       | 1         | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 670       | 64.86%  |
| 201-300     | 106       | 10.26%  |
| 501-600     | 105       | 10.16%  |
| 351-400     | 59        | 5.71%   |
| 401-500     | 27        | 2.61%   |
| 601-700     | 22        | 2.13%   |
| 701-800     | 18        | 1.74%   |
| 801-900     | 8         | 0.77%   |
| 1501-2000   | 7         | 0.68%   |
| Unknown     | 5         | 0.48%   |
| 1001-1500   | 4         | 0.39%   |
| 901-1000    | 1         | 0.1%    |
| 1-100       | 1         | 0.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 713       | 79.4%   |
| 16/10   | 128       | 14.25%  |
| 3/2     | 23        | 2.56%   |
| 21/9    | 18        | 2%      |
| 4/3     | 8         | 0.89%   |
| 5/4     | 3         | 0.33%   |
| 32/9    | 2         | 0.22%   |
| 3.33    | 1         | 0.11%   |
| 0.67    | 1         | 0.11%   |
| Unknown | 1         | 0.11%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 411       | 39.33%  |
| 81-90          | 251       | 24.02%  |
| 201-250        | 61        | 5.84%   |
| 71-80          | 59        | 5.65%   |
| 301-350        | 55        | 5.26%   |
| 121-130        | 41        | 3.92%   |
| 111-120        | 35        | 3.35%   |
| 351-500        | 34        | 3.25%   |
| 61-70          | 16        | 1.53%   |
| 151-200        | 16        | 1.53%   |
| 251-300        | 14        | 1.34%   |
| 501-1000       | 11        | 1.05%   |
| 51-60          | 9         | 0.86%   |
| 91-100         | 9         | 0.86%   |
| More than 1000 | 8         | 0.77%   |
| 141-150        | 5         | 0.48%   |
| Unknown        | 5         | 0.48%   |
| 131-140        | 3         | 0.29%   |
| 41-50          | 1         | 0.1%    |
| 1-40           | 1         | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 487       | 47.79%  |
| 101-120       | 168       | 16.49%  |
| 51-100        | 147       | 14.43%  |
| 161-240       | 146       | 14.33%  |
| More than 240 | 61        | 5.99%   |
| 1-50          | 5         | 0.49%   |
| Unknown       | 5         | 0.49%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 667       | 75.8%   |
| 2     | 174       | 19.77%  |
| 0     | 20        | 2.27%   |
| 3     | 14        | 1.59%   |
| 4     | 4         | 0.45%   |
| 5     | 1         | 0.11%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 530       | 41.57%  |
| Realtek Semiconductor                  | 437       | 34.27%  |
| Qualcomm Atheros                       | 119       | 9.33%   |
| MediaTek                               | 59        | 4.63%   |
| Broadcom                               | 35        | 2.75%   |
| Qualcomm                               | 12        | 0.94%   |
| Lenovo                                 | 10        | 0.78%   |
| Broadcom Limited                       | 7         | 0.55%   |
| Sierra Wireless                        | 6         | 0.47%   |
| ASIX Electronics                       | 6         | 0.47%   |
| Xiaomi                                 | 5         | 0.39%   |
| TP-Link                                | 5         | 0.39%   |
| Samsung Electronics                    | 4         | 0.31%   |
| Hewlett-Packard                        | 4         | 0.31%   |
| Dell                                   | 4         | 0.31%   |
| ASUSTek Computer                       | 4         | 0.31%   |
| Ralink Technology                      | 3         | 0.24%   |
| Ralink                                 | 3         | 0.24%   |
| Google                                 | 3         | 0.24%   |
| Ericsson Business Mobile Networks      | 3         | 0.24%   |
| DisplayLink                            | 3         | 0.24%   |
| Marvell Technology Group               | 2         | 0.16%   |
| Fibocom                                | 2         | 0.16%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.08%   |
| Microsoft                              | 1         | 0.08%   |
| Linksys                                | 1         | 0.08%   |
| JMicron Technology                     | 1         | 0.08%   |
| Huawei Technologies                    | 1         | 0.08%   |
| D-Link System                          | 1         | 0.08%   |
| D-Link                                 | 1         | 0.08%   |
| Aquantia                               | 1         | 0.08%   |
| Apple                                  | 1         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 260       | 17.09%  |
| Intel Wi-Fi 6 AX201                                               | 70        | 4.6%    |
| Intel Wi-Fi 6 AX200                                               | 65        | 4.27%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 61        | 4.01%   |
| Intel Wireless 8265 / 8275                                        | 47        | 3.09%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 46        | 3.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 45        | 2.96%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 41        | 2.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 38        | 2.5%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 30        | 1.97%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 29        | 1.91%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 25        | 1.64%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 23        | 1.51%   |
| Intel Wireless 8260                                               | 23        | 1.51%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 22        | 1.45%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 22        | 1.45%   |
| Intel Ethernet Connection (4) I219-LM                             | 22        | 1.45%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 21        | 1.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 21        | 1.38%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 20        | 1.31%   |
| Intel Wireless 7265                                               | 19        | 1.25%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 18        | 1.18%   |
| Intel Wireless 7260                                               | 17        | 1.12%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 16        | 1.05%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 14        | 0.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 13        | 0.85%   |
| Realtek RTL8125 2.5GbE Controller                                 | 12        | 0.79%   |
| Realtek Realtek Network controller                                | 12        | 0.79%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 12        | 0.79%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 12        | 0.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 11        | 0.72%   |
| Intel Ethernet Connection I219-LM                                 | 10        | 0.66%   |
| Intel Ethernet Connection (16) I219-V                             | 10        | 0.66%   |
| Intel Ethernet Connection (13) I219-V                             | 10        | 0.66%   |
| Intel Centrino Ultimate-N 6300                                    | 10        | 0.66%   |
| Qualcomm QCNFA765 Wireless Network Adapter                        | 9         | 0.59%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 9         | 0.59%   |
| Intel Ethernet Connection I218-LM                                 | 9         | 0.59%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 8         | 0.53%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 7         | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 521       | 59.34%  |
| Realtek Semiconductor             | 138       | 15.72%  |
| Qualcomm Atheros                  | 100       | 11.39%  |
| MediaTek                          | 42        | 4.78%   |
| Broadcom                          | 28        | 3.19%   |
| Qualcomm                          | 10        | 1.14%   |
| Broadcom Limited                  | 7         | 0.8%    |
| Sierra Wireless                   | 6         | 0.68%   |
| TP-Link                           | 4         | 0.46%   |
| Dell                              | 4         | 0.46%   |
| ASUSTek Computer                  | 4         | 0.46%   |
| Ralink Technology                 | 3         | 0.34%   |
| Ralink                            | 3         | 0.34%   |
| Hewlett-Packard                   | 2         | 0.23%   |
| Fibocom                           | 2         | 0.23%   |
| Linksys                           | 1         | 0.11%   |
| Ericsson Business Mobile Networks | 1         | 0.11%   |
| D-Link System                     | 1         | 0.11%   |
| D-Link                            | 1         | 0.11%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                            | 70        | 7.97%   |
| Intel Wi-Fi 6 AX200                                            | 65        | 7.4%    |
| Intel Alder Lake-P PCH CNVi WiFi                               | 61        | 6.95%   |
| Intel Wireless 8265 / 8275                                     | 47        | 5.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 45        | 5.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 30        | 3.42%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 29        | 3.3%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 25        | 2.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 25        | 2.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 23        | 2.62%   |
| Intel Wireless 8260                                            | 23        | 2.62%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 22        | 2.51%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 22        | 2.51%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 21        | 2.39%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 21        | 2.39%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 20        | 2.28%   |
| Intel Wireless 7265                                            | 19        | 2.16%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 18        | 2.05%   |
| Intel Wireless 7260                                            | 17        | 1.94%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 14        | 1.59%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 13        | 1.48%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 12        | 1.37%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 12        | 1.37%   |
| Realtek Realtek Network controller                             | 11        | 1.25%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 11        | 1.25%   |
| Intel Centrino Ultimate-N 6300                                 | 10        | 1.14%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 9         | 1.03%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 9         | 1.03%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 7         | 0.8%    |
| Intel Wireless-AC 9260                                         | 7         | 0.8%    |
| Intel Wireless 3160                                            | 7         | 0.8%    |
| Intel Wireless 3165                                            | 6         | 0.68%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 6         | 0.68%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 6         | 0.68%   |
| Broadcom BCM43142 802.11b/g/n                                  | 6         | 0.68%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 5         | 0.57%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 4         | 0.46%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 4         | 0.46%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 4         | 0.46%   |
| MediaTek WLAN controller                                       | 4         | 0.46%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 369       | 58.66%  |
| Intel                                  | 162       | 25.76%  |
| Qualcomm Atheros                       | 25        | 3.97%   |
| MediaTek                               | 17        | 2.7%    |
| Broadcom                               | 14        | 2.23%   |
| Lenovo                                 | 10        | 1.59%   |
| ASIX Electronics                       | 6         | 0.95%   |
| Xiaomi                                 | 5         | 0.79%   |
| Samsung Electronics                    | 4         | 0.64%   |
| Google                                 | 3         | 0.48%   |
| DisplayLink                            | 3         | 0.48%   |
| Qualcomm                               | 2         | 0.32%   |
| Marvell Technology Group               | 2         | 0.32%   |
| TP-Link                                | 1         | 0.16%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.16%   |
| Microsoft                              | 1         | 0.16%   |
| JMicron Technology                     | 1         | 0.16%   |
| Hewlett-Packard                        | 1         | 0.16%   |
| Aquantia                               | 1         | 0.16%   |
| Apple                                  | 1         | 0.16%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 260       | 40.82%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 46        | 7.22%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 38        | 5.97%   |
| Intel Ethernet Connection (4) I219-LM                             | 22        | 3.45%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 16        | 2.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 16        | 2.51%   |
| Realtek RTL8125 2.5GbE Controller                                 | 12        | 1.88%   |
| Intel Ethernet Connection I219-LM                                 | 10        | 1.57%   |
| Intel Ethernet Connection (16) I219-V                             | 10        | 1.57%   |
| Intel Ethernet Connection (13) I219-V                             | 10        | 1.57%   |
| Intel Ethernet Connection I218-LM                                 | 9         | 1.41%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 8         | 1.26%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 7         | 1.1%    |
| Lenovo ThinkPad TBT 3 Dock                                        | 6         | 0.94%   |
| Intel Ethernet Connection (6) I219-LM                             | 6         | 0.94%   |
| Intel Ethernet Connection (4) I219-V                              | 6         | 0.94%   |
| Intel Ethernet Connection (3) I218-LM                             | 6         | 0.94%   |
| Intel Ethernet Connection (10) I219-V                             | 6         | 0.94%   |
| ASIX AX88179 Gigabit Ethernet                                     | 6         | 0.94%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 5         | 0.78%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 5         | 0.78%   |
| Realtek Killer E3000 2.5GbE Controller                            | 5         | 0.78%   |
| Intel Ethernet Connection I219-V                                  | 5         | 0.78%   |
| Intel Ethernet Connection (2) I219-LM                             | 5         | 0.78%   |
| Intel Ethernet Connection (11) I219-LM                            | 5         | 0.78%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 5         | 0.78%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 4         | 0.63%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 4         | 0.63%   |
| Lenovo USB-C Dock Ethernet                                        | 4         | 0.63%   |
| Intel Ethernet Connection (10) I219-LM                            | 4         | 0.63%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 0.63%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 3         | 0.47%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 0.47%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.47%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 0.47%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 0.47%   |
| Intel Ethernet Connection (13) I219-LM                            | 3         | 0.47%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 3         | 0.47%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 3         | 0.47%   |
| Qualcomm Redmi 9T                                                 | 2         | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 843       | 58.83%  |
| Ethernet | 584       | 40.75%  |
| Modem    | 4         | 0.28%   |
| Unknown  | 2         | 0.14%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 746       | 81.53%  |
| Ethernet | 169       | 18.47%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 521       | 60.16%  |
| 1     | 324       | 37.41%  |
| 3     | 13        | 1.5%    |
| 0     | 8         | 0.92%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 636       | 72.94%  |
| Yes  | 236       | 27.06%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 456       | 60%     |
| Realtek Semiconductor           | 87        | 11.45%  |
| Qualcomm Atheros Communications | 50        | 6.58%   |
| IMC Networks                    | 37        | 4.87%   |
| Foxconn / Hon Hai               | 35        | 4.61%   |
| Lite-On Technology              | 32        | 4.21%   |
| Broadcom                        | 17        | 2.24%   |
| Realtek                         | 14        | 1.84%   |
| Apple                           | 12        | 1.58%   |
| USI                             | 3         | 0.39%   |
| Opticis                         | 3         | 0.39%   |
| MediaTek                        | 3         | 0.39%   |
| Dell                            | 3         | 0.39%   |
| Toshiba                         | 2         | 0.26%   |
| Hewlett-Packard                 | 2         | 0.26%   |
| Ralink                          | 1         | 0.13%   |
| Corsair                         | 1         | 0.13%   |
| Cambridge Silicon Radio         | 1         | 0.13%   |
| ASUSTek Computer                | 1         | 0.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                          | 123       | 16.18%  |
| Intel Bluetooth wireless interface             | 107       | 14.08%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 75        | 9.87%   |
| Realtek Bluetooth Radio                        | 71        | 9.34%   |
| Intel AX200 Bluetooth                          | 63        | 8.29%   |
| Intel Bluetooth Device                         | 43        | 5.66%   |
| Qualcomm Atheros  Bluetooth Device             | 32        | 4.21%   |
| Foxconn / Hon Hai Wireless_Device              | 27        | 3.55%   |
| Intel AX210 Bluetooth                          | 22        | 2.89%   |
| IMC Networks Wireless_Device                   | 18        | 2.37%   |
| Realtek 802.11ac WLAN Adapter                  | 14        | 1.84%   |
| Lite-On Bluetooth Device                       | 11        | 1.45%   |
| Intel Wireless-AC 3168 Bluetooth               | 11        | 1.45%   |
| Realtek  Bluetooth 4.2 Adapter                 | 10        | 1.32%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0         | 10        | 1.32%   |
| IMC Networks Bluetooth Radio                   | 9         | 1.18%   |
| Lite-On Wireless_Device                        | 8         | 1.05%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth     | 8         | 1.05%   |
| IMC Networks Bluetooth Device                  | 7         | 0.92%   |
| Apple Bluetooth Host Controller                | 7         | 0.92%   |
| Intel Wireless-AC 9260 Bluetooth Adapter       | 6         | 0.79%   |
| Foxconn / Hon Hai Bluetooth Device             | 6         | 0.79%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]     | 6         | 0.79%   |
| Intel Centrino Bluetooth Wireless Transceiver  | 5         | 0.66%   |
| Apple Bluetooth USB Host Controller            | 5         | 0.66%   |
| USI Bluetooth Device                           | 3         | 0.39%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0          | 3         | 0.39%   |
| Qualcomm Atheros AR3011 Bluetooth              | 3         | 0.39%   |
| Opticis Bluetooth Radio                        | 3         | 0.39%   |
| MediaTek Wireless_Device                       | 3         | 0.39%   |
| Lite-On Bluetooth Radio                        | 3         | 0.39%   |
| Broadcom BCM43142 Bluetooth 4.0                | 3         | 0.39%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter        | 2         | 0.26%   |
| Realtek RTL8821A Bluetooth                     | 2         | 0.26%   |
| Realtek RTL8723B Bluetooth                     | 2         | 0.26%   |
| Lite-On Atheros AR3012 Bluetooth               | 2         | 0.26%   |
| Dell DW375 Bluetooth Module                    | 2         | 0.26%   |
| Broadcom HP Portable Bumble Bee                | 2         | 0.26%   |
| Toshiba Integrated Bluetooth HCI               | 1         | 0.13%   |
| Toshiba Bluetooth Device                       | 1         | 0.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 627       | 56.28%  |
| AMD                                  | 235       | 21.1%   |
| Nvidia                               | 153       | 13.73%  |
| Lenovo                               | 13        | 1.17%   |
| Logitech                             | 10        | 0.9%    |
| C-Media Electronics                  | 10        | 0.9%    |
| Plantronics                          | 7         | 0.63%   |
| Realtek Semiconductor                | 5         | 0.45%   |
| GN Netcom                            | 5         | 0.45%   |
| Kingston Technology                  | 4         | 0.36%   |
| Hewlett-Packard                      | 4         | 0.36%   |
| Razer USA                            | 3         | 0.27%   |
| Creative Technology                  | 3         | 0.27%   |
| Corsair                              | 3         | 0.27%   |
| Blue Microphones                     | 3         | 0.27%   |
| SteelSeries ApS                      | 2         | 0.18%   |
| Samsung Electronics                  | 2         | 0.18%   |
| RODE Microphones                     | 2         | 0.18%   |
| Focusrite-Novation                   | 2         | 0.18%   |
| ASUSTek Computer                     | 2         | 0.18%   |
| Asahi Kasei Microsystems             | 2         | 0.18%   |
| Apple                                | 2         | 0.18%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.09%   |
| Samson Technologies                  | 1         | 0.09%   |
| Power Delivery                       | 1         | 0.09%   |
| No brand                             | 1         | 0.09%   |
| Microsoft                            | 1         | 0.09%   |
| Microchip Technology                 | 1         | 0.09%   |
| Micro Star International             | 1         | 0.09%   |
| JMTek                                | 1         | 0.09%   |
| Huawei Technologies                  | 1         | 0.09%   |
| Google                               | 1         | 0.09%   |
| Generalplus Technology               | 1         | 0.09%   |
| Dell                                 | 1         | 0.09%   |
| Conexant Systems                     | 1         | 0.09%   |
| Cambridge Silicon Radio              | 1         | 0.09%   |
| Alesis                               | 1         | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 205       | 14.95%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 127       | 9.26%   |
| Intel Sunrise Point-LP HD Audio                                            | 114       | 8.32%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 84        | 6.13%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 72        | 5.25%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 43        | 3.14%   |
| Intel Comet Lake PCH-LP cAVS                                               | 38        | 2.77%   |
| Intel Cannon Lake PCH cAVS                                                 | 38        | 2.77%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 36        | 2.63%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 32        | 2.33%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 27        | 1.97%   |
| Intel Comet Lake PCH cAVS                                                  | 25        | 1.82%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 24        | 1.75%   |
| Nvidia GA106 High Definition Audio Controller                              | 23        | 1.68%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 21        | 1.53%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 21        | 1.53%   |
| Intel Broadwell-U Audio Controller                                         | 21        | 1.53%   |
| Intel Haswell-ULT HD Audio Controller                                      | 18        | 1.31%   |
| Intel 8 Series HD Audio Controller                                         | 18        | 1.31%   |
| Nvidia GP107GL High Definition Audio Controller                            | 17        | 1.24%   |
| Nvidia Audio device                                                        | 17        | 1.24%   |
| Nvidia TU106 High Definition Audio Controller                              | 16        | 1.17%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 15        | 1.09%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 14        | 1.02%   |
| Intel CM238 HD Audio Controller                                            | 13        | 0.95%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 13        | 0.95%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 13        | 0.95%   |
| Nvidia GA104 High Definition Audio Controller                              | 11        | 0.8%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 10        | 0.73%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 10        | 0.73%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 9         | 0.66%   |
| Nvidia GF108 High Definition Audio Controller                              | 8         | 0.58%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 8         | 0.58%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 8         | 0.58%   |
| AMD High Definition Audio Controller                                       | 7         | 0.51%   |
| AMD FCH Azalia Controller                                                  | 7         | 0.51%   |
| Nvidia GK107 HDMI Audio Controller                                         | 6         | 0.44%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                               | 6         | 0.44%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 6         | 0.44%   |
| Realtek Semiconductor USB Audio                                            | 5         | 0.36%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 163       | 30.58%  |
| SK hynix            | 124       | 23.26%  |
| Micron Technology   | 83        | 15.57%  |
| Kingston            | 31        | 5.82%   |
| Crucial             | 28        | 5.25%   |
| Unknown             | 15        | 2.81%   |
| A-DATA Technology   | 14        | 2.63%   |
| Ramaxel Technology  | 9         | 1.69%   |
| Unknown             | 9         | 1.69%   |
| Corsair             | 8         | 1.5%    |
| Team                | 7         | 1.31%   |
| G.Skill             | 5         | 0.94%   |
| Elpida              | 5         | 0.94%   |
| Unknown (ABCD)      | 3         | 0.56%   |
| Smart               | 3         | 0.56%   |
| Transcend           | 2         | 0.38%   |
| PUSKILL             | 2         | 0.38%   |
| Patriot             | 2         | 0.38%   |
| Goldkey             | 2         | 0.38%   |
| Avant               | 2         | 0.38%   |
| Wilk                | 1         | 0.19%   |
| V-Color             | 1         | 0.19%   |
| Unknown (0x0B5E)    | 1         | 0.19%   |
| Timetec             | 1         | 0.19%   |
| Teikon              | 1         | 0.19%   |
| Smart Brazil        | 1         | 0.19%   |
| Qumo                | 1         | 0.19%   |
| Nanya Technology    | 1         | 0.19%   |
| Miron               | 1         | 0.19%   |
| Lexar Co Limited    | 1         | 0.19%   |
| Lexar               | 1         | 0.19%   |
| Kllisre             | 1         | 0.19%   |
| High Bridge         | 1         | 0.19%   |
| Hewlett-Packard     | 1         | 0.19%   |
| ASint Technology    | 1         | 0.19%   |
| 4ea5                | 1         | 0.19%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 14        | 2.48%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 1.77%   |
| Unknown                                                          | 9         | 1.6%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 1.42%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 1.42%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 8         | 1.42%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 7         | 1.24%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 7         | 1.24%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 1.06%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 6         | 1.06%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 6         | 1.06%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 6         | 1.06%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 5         | 0.89%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 0.71%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 4         | 0.71%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 4         | 0.71%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 4         | 0.71%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 0.71%   |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s         | 4         | 0.71%   |
| Micron RAM MT62F2G32D8DR-031 WT 8GB SODIMM LPDDR5 6400MT/s       | 4         | 0.71%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 4         | 0.71%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 4         | 0.71%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 0.53%   |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s            | 3         | 0.53%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 3         | 0.53%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.53%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.53%   |
| SK hynix RAM HMCG66MEBSA092N 8GB SODIMM DDR5 4800MT/s            | 3         | 0.53%   |
| SK hynix RAM HMAB2GS6CMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 3         | 0.53%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 3         | 0.53%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s        | 3         | 0.53%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.53%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.53%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 4GB Row Of Chips LPDDR5 6400MT/s | 3         | 0.53%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s       | 3         | 0.53%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 3         | 0.53%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 3         | 0.53%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 3         | 0.53%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 3         | 0.53%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 0.53%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 281       | 62.58%  |
| DDR3   | 64        | 14.25%  |
| LPDDR4 | 30        | 6.68%   |
| LPDDR5 | 29        | 6.46%   |
| LPDDR3 | 21        | 4.68%   |
| DDR5   | 18        | 4.01%   |
| DDR2   | 5         | 1.11%   |
| SDRAM  | 1         | 0.22%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 363       | 79.26%  |
| Row Of Chips | 88        | 19.21%  |
| Unknown      | 3         | 0.66%   |
| DIMM         | 2         | 0.44%   |
| Chip         | 2         | 0.44%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 239       | 49.48%  |
| 4096  | 97        | 20.08%  |
| 16384 | 86        | 17.81%  |
| 2048  | 31        | 6.42%   |
| 32768 | 27        | 5.59%   |
| 1024  | 3         | 0.62%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 168       | 34.93%  |
| 2667    | 94        | 19.54%  |
| 1600    | 52        | 10.81%  |
| 2400    | 31        | 6.44%   |
| 2133    | 30        | 6.24%   |
| 6400    | 28        | 5.82%   |
| 4800    | 18        | 3.74%   |
| 4267    | 12        | 2.49%   |
| 4266    | 10        | 2.08%   |
| 1867    | 8         | 1.66%   |
| 1333    | 8         | 1.66%   |
| 3266    | 5         | 1.04%   |
| 8400    | 2         | 0.42%   |
| 3733    | 2         | 0.42%   |
| 1334    | 2         | 0.42%   |
| 933     | 2         | 0.42%   |
| 800     | 2         | 0.42%   |
| 667     | 2         | 0.42%   |
| Unknown | 2         | 0.42%   |
| 2933    | 1         | 0.21%   |
| 2048    | 1         | 0.21%   |
| 1066    | 1         | 0.21%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| MiiiW              | 1         | 33.33%  |
| Hewlett-Packard    | 1         | 33.33%  |
| Brother Industries | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| MiiiW MW USB Receiver    | 1         | 33.33%  |
| HP Officejet 2620 series | 1         | 33.33%  |
| Brother DCP-1600         | 1         | 33.33%  |

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


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 208       | 25.68%  |
| IMC Networks                           | 116       | 14.32%  |
| Quanta                                 | 78        | 9.63%   |
| Microdia                               | 74        | 9.14%   |
| Acer                                   | 66        | 8.15%   |
| Realtek Semiconductor                  | 42        | 5.19%   |
| Sunplus Innovation Technology          | 37        | 4.57%   |
| Cheng Uei Precision Industry (Foxlink) | 30        | 3.7%    |
| Luxvisions Innotech Limited            | 27        | 3.33%   |
| Syntek                                 | 23        | 2.84%   |
| Logitech                               | 17        | 2.1%    |
| Lite-On Technology                     | 17        | 2.1%    |
| Sonix Technology                       | 13        | 1.6%    |
| Apple                                  | 10        | 1.23%   |
| Silicon Motion                         | 8         | 0.99%   |
| Suyin                                  | 6         | 0.74%   |
| SunplusIT                              | 4         | 0.49%   |
| Alcor Micro                            | 4         | 0.49%   |
| Tripath Technology                     | 3         | 0.37%   |
| Microsoft                              | 2         | 0.25%   |
| MacroSilicon                           | 2         | 0.25%   |
| Lenovo                                 | 2         | 0.25%   |
| Importek                               | 2         | 0.25%   |
| icSpring                               | 2         | 0.25%   |
| Generalplus Technology                 | 2         | 0.25%   |
| WaveRider Communications               | 1         | 0.12%   |
| USB Camera CS                          | 1         | 0.12%   |
| Samsung Electronics                    | 1         | 0.12%   |
| Ricoh                                  | 1         | 0.12%   |
| Primax Electronics                     | 1         | 0.12%   |
| Novatek Microelectronics               | 1         | 0.12%   |
| kingcome                               | 1         | 0.12%   |
| Jieli Technology                       | 1         | 0.12%   |
| Hewlett-Packard                        | 1         | 0.12%   |
| Goodong Industry                       | 1         | 0.12%   |
| DLEQNA19IFK6G2                         | 1         | 0.12%   |
| Bison Electronics                      | 1         | 0.12%   |
| AVerMedia Technologies                 | 1         | 0.12%   |
| ARC International                      | 1         | 0.12%   |
| A4Tech                                 | 1         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 75        | 9.19%   |
| Microdia Integrated_Webcam_HD                        | 47        | 5.76%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 38        | 4.66%   |
| IMC Networks Integrated Camera                       | 33        | 4.04%   |
| Acer Integrated Camera                               | 27        | 3.31%   |
| Realtek Integrated_Webcam_HD                         | 24        | 2.94%   |
| Chicony HD Webcam                                    | 20        | 2.45%   |
| Quanta HD User Facing                                | 17        | 2.08%   |
| Syntek Integrated Camera                             | 15        | 1.84%   |
| Sunplus Integrated_Webcam_HD                         | 12        | 1.47%   |
| Quanta HP HD Camera                                  | 12        | 1.47%   |
| IMC Networks HD Camera                               | 12        | 1.47%   |
| Quanta HP Wide Vision HD Camera                      | 11        | 1.35%   |
| Chicony Integrated Camera (1280x720@30)              | 10        | 1.23%   |
| Sonix USB2.0 HD UVC WebCam                           | 9         | 1.1%    |
| Lite-On Integrated Camera                            | 9         | 1.1%    |
| Chicony HP TrueVision HD Camera                      | 9         | 1.1%    |
| Microdia Integrated_Webcam_FHD                       | 8         | 0.98%   |
| Luxvisions Innotech Limited Integrated RGB Camera    | 8         | 0.98%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 8         | 0.98%   |
| Chicony HD User Facing                               | 8         | 0.98%   |
| Acer HD Webcam                                       | 8         | 0.98%   |
| Quanta HP TrueVision HD Camera                       | 7         | 0.86%   |
| Chicony USB2.0 VGA UVC WebCam                        | 7         | 0.86%   |
| Chicony USB2.0 Camera                                | 7         | 0.86%   |
| Chicony HP HD Camera                                 | 7         | 0.86%   |
| Chicony EasyCamera                                   | 7         | 0.86%   |
| Quanta HD Webcam                                     | 6         | 0.74%   |
| Luxvisions Innotech Limited Integrated Camera        | 6         | 0.74%   |
| Chicony HP Wide Vision HD Camera                     | 6         | 0.74%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera     | 6         | 0.74%   |
| Quanta VGA WebCam                                    | 5         | 0.61%   |
| Quanta ACER HD User Facing                           | 5         | 0.61%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 5         | 0.61%   |
| Lite-On HP HD Camera                                 | 5         | 0.61%   |
| IMC Networks ov9734_azurewave_camera                 | 5         | 0.61%   |
| Chicony ACER HD User Facing                          | 5         | 0.61%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera  | 5         | 0.61%   |
| Apple FaceTime HD Camera                             | 5         | 0.61%   |
| Syntek EasyCamera                                    | 4         | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 77        | 39.9%   |
| Shenzhen Goodix Technology         | 45        | 23.32%  |
| Validity Sensors                   | 40        | 20.73%  |
| Elan Microelectronics              | 17        | 8.81%   |
| LighTuning Technology              | 5         | 2.59%   |
| AuthenTec                          | 3         | 1.55%   |
| Upek                               | 2         | 1.04%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 1.04%   |
| STMicroelectronics                 | 1         | 0.52%   |
| Samsung Electronics                | 1         | 0.52%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 37        | 19.17%  |
| Shenzhen Goodix  FingerPrint Device                                        | 37        | 19.17%  |
| Unknown                                                                    | 19        | 9.84%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 13        | 6.74%   |
| Elan ELAN:ARM-M4                                                           | 10        | 5.18%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 9         | 4.66%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 7         | 3.63%   |
| Validity Sensors Synaptics WBDI                                            | 7         | 3.63%   |
| Elan ELAN:Fingerprint                                                      | 7         | 3.63%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 2.59%   |
| Synaptics  WBDI                                                            | 5         | 2.59%   |
| Shenzhen Goodix Fingerprint Reader                                         | 5         | 2.59%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 2.07%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 1.55%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 1.55%   |
| Validity Sensors VFS491                                                    | 2         | 1.04%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 1.04%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 1.04%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 1.04%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 1.04%   |
| AuthenTec AES1600                                                          | 2         | 1.04%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.52%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.52%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.52%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.52%   |
| Synaptics WBDI Device                                                      | 1         | 0.52%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 0.52%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.52%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.52%   |
| Samsung Fingerprint Device                                                 | 1         | 0.52%   |
| AuthenTec AES2810                                                          | 1         | 0.52%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 33        | 42.31%  |
| Alcor Micro           | 33        | 42.31%  |
| Upek                  | 6         | 7.69%   |
| Lenovo                | 3         | 3.85%   |
| Yubico.com            | 1         | 1.28%   |
| O2 Micro              | 1         | 1.28%   |
| Gemalto (was Gemplus) | 1         | 1.28%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 33        | 42.31%  |
| Broadcom 58200                                                               | 13        | 16.67%  |
| Broadcom 5880                                                                | 11        | 14.1%   |
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 8.97%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 6         | 7.69%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 3.85%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 2.56%   |
| Yubico.com Yubikey 4 U2F+CCID                                                | 1         | 1.28%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.28%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.28%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 503       | 57.35%  |
| 1     | 315       | 35.92%  |
| 2     | 49        | 5.59%   |
| 5     | 3         | 0.34%   |
| 3     | 3         | 0.34%   |
| 7     | 2         | 0.23%   |
| 4     | 2         | 0.23%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 191       | 43.02%  |
| Graphics card            | 110       | 24.77%  |
| Multimedia controller    | 49        | 11.04%  |
| Camera                   | 24        | 5.41%   |
| Net/wireless             | 22        | 4.95%   |
| Chipcard                 | 17        | 3.83%   |
| Card reader              | 8         | 1.8%    |
| Sound                    | 6         | 1.35%   |
| Bluetooth                | 6         | 1.35%   |
| Storage                  | 3         | 0.68%   |
| Net/ethernet             | 3         | 0.68%   |
| Communication controller | 3         | 0.68%   |
| Network                  | 1         | 0.23%   |
| Firewire controller      | 1         | 0.23%   |

