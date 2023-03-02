Fedora - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Fedora.

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

Total: 8876

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
| Acer          | TravelMate P633-V           | [b4841d9589](https://linux-hardware.org/?probe=b4841d9589) | Feb 26, 2023 |
| Lenovo        | ThinkPad T61 6464A13        | [e981803528](https://linux-hardware.org/?probe=e981803528) | Feb 26, 2023 |
| Standard      | Unknown                     | [9d002e0593](https://linux-hardware.org/?probe=9d002e0593) | Feb 26, 2023 |
| Lenovo        | Legion 5 82B5               | [8db23a7237](https://linux-hardware.org/?probe=8db23a7237) | Feb 25, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [bd2c3ecd74](https://linux-hardware.org/?probe=bd2c3ecd74) | Feb 25, 2023 |
| Lenovo        | ThinkPad T480 20L5S03600    | [5c9736ab0c](https://linux-hardware.org/?probe=5c9736ab0c) | Feb 25, 2023 |
| Dell          | Vostro 14-5459              | [1f96898a48](https://linux-hardware.org/?probe=1f96898a48) | Feb 25, 2023 |
| Dell          | Latitude E6420              | [7ae4fe9340](https://linux-hardware.org/?probe=7ae4fe9340) | Feb 25, 2023 |
| Acer          | TravelMate P633-V           | [fd426b6c71](https://linux-hardware.org/?probe=fd426b6c71) | Feb 25, 2023 |
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
| HP            | EliteBook 840 G6            | [ea6777bf2d](https://linux-hardware.org/?probe=ea6777bf2d) | Feb 23, 2023 |
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
| ASUSTek       | VivoBook_ASUSLaptop S540... | [159244d1a4](https://linux-hardware.org/?probe=159244d1a4) | Feb 15, 2023 |
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
| HP            | Pavilion Gaming Laptop 1... | [a3b0220b10](https://linux-hardware.org/?probe=a3b0220b10) | Feb 14, 2023 |
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
| MACHENIKE     | MACHCREATOR-16              | [cde8e637d2](https://linux-hardware.org/?probe=cde8e637d2) | Feb 12, 2023 |
| MACHENIKE     | MACHCREATOR-16              | [a3ac4db738](https://linux-hardware.org/?probe=a3ac4db738) | Feb 12, 2023 |
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
| Dell          | XPS 15 9500                 | [11222774d3](https://linux-hardware.org/?probe=11222774d3) | Feb 10, 2023 |
| Acer          | TravelMate 7730             | [a9a9e21b5a](https://linux-hardware.org/?probe=a9a9e21b5a) | Feb 10, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [a64bb02ece](https://linux-hardware.org/?probe=a64bb02ece) | Feb 10, 2023 |
| Dell          | Inspiron 7559               | [956a602343](https://linux-hardware.org/?probe=956a602343) | Feb 10, 2023 |
| ASUSTek       | ROG Strix G733QR_G733QR     | [da12318597](https://linux-hardware.org/?probe=da12318597) | Feb 10, 2023 |
| Dell          | XPS 13 9310                 | [0461c55b4a](https://linux-hardware.org/?probe=0461c55b4a) | Feb 10, 2023 |
| MSI           | Raider GE77HX 12UHS         | [d77cac7fb6](https://linux-hardware.org/?probe=d77cac7fb6) | Feb 10, 2023 |
| Apple         | MacBookPro11,3              | [b0ffb00d43](https://linux-hardware.org/?probe=b0ffb00d43) | Feb 10, 2023 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | [9b8563ab53](https://linux-hardware.org/?probe=9b8563ab53) | Feb 10, 2023 |
| Acer          | Swift SF314-54              | [8d92b8e7c5](https://linux-hardware.org/?probe=8d92b8e7c5) | Feb 09, 2023 |
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
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f268d3da5e](https://linux-hardware.org/?probe=f268d3da5e) | Feb 08, 2023 |
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
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [69b76f313e](https://linux-hardware.org/?probe=69b76f313e) | Feb 05, 2023 |
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
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [0b73c3afe8](https://linux-hardware.org/?probe=0b73c3afe8) | Feb 03, 2023 |
| Dell          | Latitude 5530               | [dd0a933124](https://linux-hardware.org/?probe=dd0a933124) | Feb 03, 2023 |
| Dynabook      | PORTEGE X30L-K              | [af43366b45](https://linux-hardware.org/?probe=af43366b45) | Feb 03, 2023 |
| Acer          | Aspire 5750G                | [fa1e255519](https://linux-hardware.org/?probe=fa1e255519) | Feb 03, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [d7fff6982b](https://linux-hardware.org/?probe=d7fff6982b) | Feb 03, 2023 |
| Acer          | Aspire 5750G                | [ada6dd2b76](https://linux-hardware.org/?probe=ada6dd2b76) | Feb 03, 2023 |
| MACHENIKE     | MACHCREATOR-16              | [4608209d2d](https://linux-hardware.org/?probe=4608209d2d) | Feb 03, 2023 |
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
| MACHENIKE     | MACHCREATOR-16              | [81e773eade](https://linux-hardware.org/?probe=81e773eade) | Feb 02, 2023 |
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
| MACHENIKE     | MACHCREATOR-16              | [c44c077d1e](https://linux-hardware.org/?probe=c44c077d1e) | Jan 30, 2023 |
| Dell          | Vostro 15 3515              | [357d14774f](https://linux-hardware.org/?probe=357d14774f) | Jan 30, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603ZX... | [7442c84b55](https://linux-hardware.org/?probe=7442c84b55) | Jan 30, 2023 |
| Dell          | Latitude 7480               | [f3a84b494f](https://linux-hardware.org/?probe=f3a84b494f) | Jan 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1ecef01472](https://linux-hardware.org/?probe=1ecef01472) | Jan 30, 2023 |
| HP            | Pavilion 15                 | [6ceccb3d73](https://linux-hardware.org/?probe=6ceccb3d73) | Jan 30, 2023 |
| Lenovo        | ThinkPad T430 2347G4U       | [5802e6b9b9](https://linux-hardware.org/?probe=5802e6b9b9) | Jan 30, 2023 |
| Dell          | XPS 15 9570                 | [1d06f2715a](https://linux-hardware.org/?probe=1d06f2715a) | Jan 30, 2023 |
| Dell          | Vostro 7620                 | [b6d43b8741](https://linux-hardware.org/?probe=b6d43b8741) | Jan 29, 2023 |
| MACHENIKE     | MACHCREATOR-16              | [e3d7c03a2e](https://linux-hardware.org/?probe=e3d7c03a2e) | Jan 29, 2023 |
| Lenovo        | 3000 N200 0769BAG           | [f8f410eb2a](https://linux-hardware.org/?probe=f8f410eb2a) | Jan 29, 2023 |
| HP            | Laptop 14-cm0xxx            | [9b93652159](https://linux-hardware.org/?probe=9b93652159) | Jan 29, 2023 |
| Acer          | Aspire V5-573G              | [e253d5b49b](https://linux-hardware.org/?probe=e253d5b49b) | Jan 29, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [32d5472e21](https://linux-hardware.org/?probe=32d5472e21) | Jan 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [47246aa8b5](https://linux-hardware.org/?probe=47246aa8b5) | Jan 29, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [dd07a46c6a](https://linux-hardware.org/?probe=dd07a46c6a) | Jan 29, 2023 |
| TECNO         | MEGABOOK T1                 | [db0e6c89b4](https://linux-hardware.org/?probe=db0e6c89b4) | Jan 29, 2023 |
| Lenovo        | IdeaPad S340-14IML 81N9     | [58e620077b](https://linux-hardware.org/?probe=58e620077b) | Jan 29, 2023 |
| Razer         | Blade 15 (2022) - RZ09-0... | [41d33a9029](https://linux-hardware.org/?probe=41d33a9029) | Jan 29, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [086e08a04b](https://linux-hardware.org/?probe=086e08a04b) | Jan 29, 2023 |
| Acer          | Aspire 5733                 | [da753d74a1](https://linux-hardware.org/?probe=da753d74a1) | Jan 29, 2023 |
| Dell          | XPS 13 7390                 | [60c03ee1f7](https://linux-hardware.org/?probe=60c03ee1f7) | Jan 29, 2023 |
| HP            | EliteBook 840 G1            | [30549ebd3a](https://linux-hardware.org/?probe=30549ebd3a) | Jan 28, 2023 |
| HP            | Laptop 15-da2xxx            | [8384a02b4b](https://linux-hardware.org/?probe=8384a02b4b) | Jan 28, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [53015adc9d](https://linux-hardware.org/?probe=53015adc9d) | Jan 28, 2023 |
| HUAWEI        | MACH-WX9                    | [5b00f79b72](https://linux-hardware.org/?probe=5b00f79b72) | Jan 28, 2023 |
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
| Dell          | XPS 15 7590                 | [4ecf66ddd9](https://linux-hardware.org/?probe=4ecf66ddd9) | Jan 27, 2023 |
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
| Dell          | Latitude 7480               | [3cb61c5b71](https://linux-hardware.org/?probe=3cb61c5b71) | Jan 26, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HM... | [26f64a2ad0](https://linux-hardware.org/?probe=26f64a2ad0) | Jan 26, 2023 |
| GPU Compan... | GWTN156-11                  | [e7f1ea09b5](https://linux-hardware.org/?probe=e7f1ea09b5) | Jan 26, 2023 |
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
| Dell          | Latitude 3420               | [d2a8b9657a](https://linux-hardware.org/?probe=d2a8b9657a) | Jan 23, 2023 |
| Dell          | Latitude 7490               | [e40bb2f01f](https://linux-hardware.org/?probe=e40bb2f01f) | Jan 23, 2023 |
| Dell          | Latitude 7490               | [31789ae630](https://linux-hardware.org/?probe=31789ae630) | Jan 23, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [091effd2ac](https://linux-hardware.org/?probe=091effd2ac) | Jan 23, 2023 |
| Apple         | MacBookPro9,1               | [0a597ba033](https://linux-hardware.org/?probe=0a597ba033) | Jan 23, 2023 |
| MACHENIKE     | MACHCREATOR-16              | [7b3107564a](https://linux-hardware.org/?probe=7b3107564a) | Jan 23, 2023 |
| Lenovo        | Erazer Z500 20226           | [6e7a21c6d5](https://linux-hardware.org/?probe=6e7a21c6d5) | Jan 23, 2023 |
| MACHENIKE     | MACHCREATOR-16              | [6b370a283e](https://linux-hardware.org/?probe=6b370a283e) | Jan 23, 2023 |
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
| Positivo B... | VJFE43F11X-XXXXXX           | [138a9b3b0c](https://linux-hardware.org/?probe=138a9b3b0c) | Jan 20, 2023 |
| Dell          | Venue 8 Pro 5830            | [4f815d5b4f](https://linux-hardware.org/?probe=4f815d5b4f) | Jan 20, 2023 |
| Acer          | Aspire A315-42G             | [ed4c536efa](https://linux-hardware.org/?probe=ed4c536efa) | Jan 20, 2023 |
| Lenovo        | ThinkPad T490 20N3S0E000    | [d324a863a5](https://linux-hardware.org/?probe=d324a863a5) | Jan 20, 2023 |
| ASUSTek       | ZenBook UX434IQ_UM433IQ     | [17b4a2466c](https://linux-hardware.org/?probe=17b4a2466c) | Jan 20, 2023 |
| Acer          | Aspire A515-45              | [9d5faff505](https://linux-hardware.org/?probe=9d5faff505) | Jan 20, 2023 |
| MSI           | GS66 Stealth 10UE           | [d5a2a6aaa8](https://linux-hardware.org/?probe=d5a2a6aaa8) | Jan 19, 2023 |
| Positivo B... | VJFE43F11X-XXXXXX           | [cc9e6f8862](https://linux-hardware.org/?probe=cc9e6f8862) | Jan 19, 2023 |
| SLIMBOOK      | TITAN                       | [15c0522754](https://linux-hardware.org/?probe=15c0522754) | Jan 19, 2023 |
| SLIMBOOK      | TITAN                       | [e81652a68c](https://linux-hardware.org/?probe=e81652a68c) | Jan 19, 2023 |
| Dell          | Precision 3551              | [4ff5a0ab8d](https://linux-hardware.org/?probe=4ff5a0ab8d) | Jan 19, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [440ff298e7](https://linux-hardware.org/?probe=440ff298e7) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [0f079e1dc7](https://linux-hardware.org/?probe=0f079e1dc7) | Jan 19, 2023 |
| Acer          | Aspire A315-23              | [90049e4bb7](https://linux-hardware.org/?probe=90049e4bb7) | Jan 19, 2023 |
| Acer          | Nitro AN515-42              | [d6a24ede85](https://linux-hardware.org/?probe=d6a24ede85) | Jan 19, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [6a47296f0c](https://linux-hardware.org/?probe=6a47296f0c) | Jan 19, 2023 |
| Dell          | Latitude 3410               | [187aebc2cd](https://linux-hardware.org/?probe=187aebc2cd) | Jan 19, 2023 |
| Intel Clie... | LAPRC510                    | [6d570a1aee](https://linux-hardware.org/?probe=6d570a1aee) | Jan 19, 2023 |
| HP            | ENVY Laptop 17-ce0xxx       | [1a0f3869dd](https://linux-hardware.org/?probe=1a0f3869dd) | Jan 18, 2023 |
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
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [aa6ca0d358](https://linux-hardware.org/?probe=aa6ca0d358) | Jan 17, 2023 |
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
| ASUSTek       | VivoBook_ASUSLaptop X515... | [8fb168e741](https://linux-hardware.org/?probe=8fb168e741) | Jan 16, 2023 |
| Lenovo        | ThinkPad T460s 20FAS5QW0... | [dd953776aa](https://linux-hardware.org/?probe=dd953776aa) | Jan 16, 2023 |
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
| HP            | Pavilion dv6                | [60f339781c](https://linux-hardware.org/?probe=60f339781c) | Jan 14, 2023 |
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
| Acer          | Nitro AN515-54              | [ea080033f1](https://linux-hardware.org/?probe=ea080033f1) | Jan 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [9096450d56](https://linux-hardware.org/?probe=9096450d56) | Jan 14, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [bbf1dabe59](https://linux-hardware.org/?probe=bbf1dabe59) | Jan 14, 2023 |
| Dell          | Latitude 7430               | [9caa5939ef](https://linux-hardware.org/?probe=9caa5939ef) | Jan 13, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [61c432b134](https://linux-hardware.org/?probe=61c432b134) | Jan 13, 2023 |
| Apple         | MacBookPro11,3              | [c94f291c81](https://linux-hardware.org/?probe=c94f291c81) | Jan 13, 2023 |
| Acer          | Nitro AN515-44              | [b2c96e31d9](https://linux-hardware.org/?probe=b2c96e31d9) | Jan 13, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [810b2daeef](https://linux-hardware.org/?probe=810b2daeef) | Jan 13, 2023 |
| Toshiba       | Satellite L855D             | [0606d04520](https://linux-hardware.org/?probe=0606d04520) | Jan 13, 2023 |
| Dell          | Inspiron 5721               | [b9435f9f7d](https://linux-hardware.org/?probe=b9435f9f7d) | Jan 13, 2023 |
| Acer          | Predator PH315-52           | [c6a710b940](https://linux-hardware.org/?probe=c6a710b940) | Jan 13, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [64c403ce6d](https://linux-hardware.org/?probe=64c403ce6d) | Jan 13, 2023 |
| Lenovo        | ThinkPad T495s 20QKS2R40... | [28d821da5f](https://linux-hardware.org/?probe=28d821da5f) | Jan 13, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [f9d244586a](https://linux-hardware.org/?probe=f9d244586a) | Jan 13, 2023 |
| Lenovo        | ThinkPad T495s 20QKS2R40... | [e78a057172](https://linux-hardware.org/?probe=e78a057172) | Jan 13, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [05899ebb86](https://linux-hardware.org/?probe=05899ebb86) | Jan 13, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [033a92981f](https://linux-hardware.org/?probe=033a92981f) | Jan 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [4236e82f21](https://linux-hardware.org/?probe=4236e82f21) | Jan 13, 2023 |
| Acer          | Predator PT515-51           | [150f12dceb](https://linux-hardware.org/?probe=150f12dceb) | Jan 12, 2023 |
| Dell          | G15 5520                    | [1aeaf74f9a](https://linux-hardware.org/?probe=1aeaf74f9a) | Jan 12, 2023 |
| HP            | ProBook 450 G6              | [f675188c46](https://linux-hardware.org/?probe=f675188c46) | Jan 12, 2023 |
| Lenovo        | ThinkPad T430 2347B85       | [01fce134df](https://linux-hardware.org/?probe=01fce134df) | Jan 12, 2023 |
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
| HP            | ProBook 4520s               | [8e1eba4ad4](https://linux-hardware.org/?probe=8e1eba4ad4) | Jan 09, 2023 |
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
| HP            | ZBook Fury 15 G7 Mobile ... | [2b8c216e1a](https://linux-hardware.org/?probe=2b8c216e1a) | Jan 08, 2023 |
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
| HP            | 240 G8                      | [efc7e61483](https://linux-hardware.org/?probe=efc7e61483) | Jan 06, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [cddb2a7b81](https://linux-hardware.org/?probe=cddb2a7b81) | Jan 06, 2023 |
| Lenovo        | Z50-75 80EC                 | [7fe70dc4c8](https://linux-hardware.org/?probe=7fe70dc4c8) | Jan 06, 2023 |
| Apple         | MacBookPro12,1              | [0cca8fbbb6](https://linux-hardware.org/?probe=0cca8fbbb6) | Jan 05, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [c47405aaf4](https://linux-hardware.org/?probe=c47405aaf4) | Jan 05, 2023 |
| Lenovo        | ThinkPad X220 4290KJ6       | [8296e61afd](https://linux-hardware.org/?probe=8296e61afd) | Jan 05, 2023 |
| Acer          | Predator PT515-51           | [77651b16db](https://linux-hardware.org/?probe=77651b16db) | Jan 05, 2023 |
| Lenovo        | ThinkPad T460 20FMS49100    | [28af5637ef](https://linux-hardware.org/?probe=28af5637ef) | Jan 05, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [1d25f1df44](https://linux-hardware.org/?probe=1d25f1df44) | Jan 05, 2023 |
| Lenovo        | ThinkPad T460 20FMS49100    | [4605f322cb](https://linux-hardware.org/?probe=4605f322cb) | Jan 05, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [31f9cd0972](https://linux-hardware.org/?probe=31f9cd0972) | Jan 05, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [a2ec6616aa](https://linux-hardware.org/?probe=a2ec6616aa) | Jan 05, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [8ac0b43549](https://linux-hardware.org/?probe=8ac0b43549) | Jan 05, 2023 |
| MSI           | Modern 14 B4MW              | [b7855a84cf](https://linux-hardware.org/?probe=b7855a84cf) | Jan 05, 2023 |
| Lenovo        | ThinkPad T460s 20FAS5QW0... | [4853686d6c](https://linux-hardware.org/?probe=4853686d6c) | Jan 05, 2023 |
| HP            | EliteBook 840 G5 NOTEBOO... | [343d0f4c48](https://linux-hardware.org/?probe=343d0f4c48) | Jan 04, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [e06b51ae0a](https://linux-hardware.org/?probe=e06b51ae0a) | Jan 04, 2023 |
| ASUSTek       | X510UAR                     | [39f45e87d1](https://linux-hardware.org/?probe=39f45e87d1) | Jan 04, 2023 |
| ASUSTek       | X510UAR                     | [2f4bb5b17d](https://linux-hardware.org/?probe=2f4bb5b17d) | Jan 04, 2023 |
| Chuwi         | GemiBook Pro                | [272d23ec5d](https://linux-hardware.org/?probe=272d23ec5d) | Jan 04, 2023 |
| HP            | EliteBook 840 G3            | [76f2ef98b9](https://linux-hardware.org/?probe=76f2ef98b9) | Jan 04, 2023 |
| Acer          | Swift SF314-43              | [50d8f0c1cb](https://linux-hardware.org/?probe=50d8f0c1cb) | Jan 04, 2023 |
| HP            | Notebook                    | [679c0bfbe8](https://linux-hardware.org/?probe=679c0bfbe8) | Jan 04, 2023 |
| HP            | EliteBook 845 14 inch G9... | [26826e3c23](https://linux-hardware.org/?probe=26826e3c23) | Jan 04, 2023 |
| Dell          | XPS 15 9550                 | [72f8edfe5b](https://linux-hardware.org/?probe=72f8edfe5b) | Jan 04, 2023 |
| HP            | ZBook 15 G3                 | [6a38362bbe](https://linux-hardware.org/?probe=6a38362bbe) | Jan 04, 2023 |
| Unknown       | Unknown                     | [b363093f89](https://linux-hardware.org/?probe=b363093f89) | Jan 04, 2023 |
| Acer          | Nitro AN515-45              | [5741654cdc](https://linux-hardware.org/?probe=5741654cdc) | Jan 04, 2023 |
| MSI           | Modern 14 B11MOU            | [036ae164e8](https://linux-hardware.org/?probe=036ae164e8) | Jan 04, 2023 |
| Toshiba       | Satellite C75D-B            | [d5380976a2](https://linux-hardware.org/?probe=d5380976a2) | Jan 03, 2023 |
| Clevo         | M815P                       | [7f1503c5e6](https://linux-hardware.org/?probe=7f1503c5e6) | Jan 03, 2023 |
| MSI           | Katana GF66 11SC            | [d788f444ff](https://linux-hardware.org/?probe=d788f444ff) | Jan 03, 2023 |
| HP            | ProBook 6570b               | [875054c6d7](https://linux-hardware.org/?probe=875054c6d7) | Jan 03, 2023 |
| ASUSTek       | X453MA                      | [1584b0616c](https://linux-hardware.org/?probe=1584b0616c) | Jan 03, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [40af3a30ca](https://linux-hardware.org/?probe=40af3a30ca) | Jan 03, 2023 |
| Lenovo        | ThinkPad T590 20N5S2NC1V    | [c621679405](https://linux-hardware.org/?probe=c621679405) | Jan 03, 2023 |
| HP            | 240 G8 Notebook PC          | [a316608c78](https://linux-hardware.org/?probe=a316608c78) | Jan 03, 2023 |
| Lenovo        | ThinkPad T460s 20FAS5QW0... | [373efc41b0](https://linux-hardware.org/?probe=373efc41b0) | Jan 03, 2023 |
| MSI           | Katana GF66 11SC            | [5a078a161f](https://linux-hardware.org/?probe=5a078a161f) | Jan 03, 2023 |
| Lenovo        | ThinkPad T530 24296FG       | [303cb1bd6f](https://linux-hardware.org/?probe=303cb1bd6f) | Jan 02, 2023 |
| Toshiba       | Satellite C50-A             | [9b02393248](https://linux-hardware.org/?probe=9b02393248) | Jan 02, 2023 |
| HP            | Notebook                    | [530e6cfeb9](https://linux-hardware.org/?probe=530e6cfeb9) | Jan 02, 2023 |
| Clevo         | M815P                       | [034cecc238](https://linux-hardware.org/?probe=034cecc238) | Jan 02, 2023 |
| HP            | ZBook 15 G3                 | [7ef67aea7b](https://linux-hardware.org/?probe=7ef67aea7b) | Jan 02, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [daeb060f32](https://linux-hardware.org/?probe=daeb060f32) | Jan 02, 2023 |
| Acer          | Aspire A315-31              | [4a79c65764](https://linux-hardware.org/?probe=4a79c65764) | Jan 02, 2023 |
| ASUSTek       | X756UXK                     | [f0bc632c50](https://linux-hardware.org/?probe=f0bc632c50) | Jan 02, 2023 |
| Dell          | Latitude 7410               | [acb8ce902e](https://linux-hardware.org/?probe=acb8ce902e) | Jan 01, 2023 |
| Dell          | Inspiron 5580               | [c6a044c898](https://linux-hardware.org/?probe=c6a044c898) | Jan 01, 2023 |
| Acer          | Aspire A315-59              | [f84116ec07](https://linux-hardware.org/?probe=f84116ec07) | Jan 01, 2023 |
| Dell          | Latitude E7240              | [ca82922df4](https://linux-hardware.org/?probe=ca82922df4) | Jan 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [5a95ae3186](https://linux-hardware.org/?probe=5a95ae3186) | Jan 01, 2023 |
| Fujitsu       | LIFEBOOK U749               | [c09072c09f](https://linux-hardware.org/?probe=c09072c09f) | Jan 01, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [f438866c0d](https://linux-hardware.org/?probe=f438866c0d) | Jan 01, 2023 |
| Acer          | Aspire 4750                 | [f871c26332](https://linux-hardware.org/?probe=f871c26332) | Jan 01, 2023 |
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
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | [1c46a3fdd3](https://linux-hardware.org/?probe=1c46a3fdd3) | Dec 29, 2022 |
| MSI           | Modern 15 A5M               | [1e7182cb70](https://linux-hardware.org/?probe=1e7182cb70) | Dec 29, 2022 |
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
| ASUSTek       | ROG Strix G513QY_G513QY     | [cedce58f23](https://linux-hardware.org/?probe=cedce58f23) | Dec 27, 2022 |
| Dell          | Inspiron 15 3525            | [64a70af984](https://linux-hardware.org/?probe=64a70af984) | Dec 27, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [0e063e5fd5](https://linux-hardware.org/?probe=0e063e5fd5) | Dec 27, 2022 |
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
| MSI           | GT60                        | [3917ca13e3](https://linux-hardware.org/?probe=3917ca13e3) | Dec 26, 2022 |
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
| Samsung       | 550XBE/350XBE               | [4ea620705d](https://linux-hardware.org/?probe=4ea620705d) | Dec 24, 2022 |
| Toshiba       | Satellite C75D-B            | [04282775ba](https://linux-hardware.org/?probe=04282775ba) | Dec 24, 2022 |
| Dell          | Latitude 5420               | [201e81d0ed](https://linux-hardware.org/?probe=201e81d0ed) | Dec 23, 2022 |
| Dell          | Latitude 5420               | [9fd9875465](https://linux-hardware.org/?probe=9fd9875465) | Dec 23, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [f114731a78](https://linux-hardware.org/?probe=f114731a78) | Dec 23, 2022 |
| ASUSTek       | X750JN                      | [d933b1a80b](https://linux-hardware.org/?probe=d933b1a80b) | Dec 23, 2022 |
| Toshiba       | Satellite C850-C5K          | [a67d24c9f9](https://linux-hardware.org/?probe=a67d24c9f9) | Dec 23, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [6b2cd55178](https://linux-hardware.org/?probe=6b2cd55178) | Dec 23, 2022 |
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
| Acer          | Aspire A315-54              | [c603811f9a](https://linux-hardware.org/?probe=c603811f9a) | Dec 22, 2022 |
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
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [47ac3ac319](https://linux-hardware.org/?probe=47ac3ac319) | Dec 21, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | [ec20f98178](https://linux-hardware.org/?probe=ec20f98178) | Dec 21, 2022 |
| Dell          | Latitude 5520               | [203652b6dd](https://linux-hardware.org/?probe=203652b6dd) | Dec 21, 2022 |
| Lenovo        | ThinkPad E15 20RD0011RT     | [1f1c718c61](https://linux-hardware.org/?probe=1f1c718c61) | Dec 21, 2022 |
| Timi          | Mi NoteBook Pro             | [b5bbb4f410](https://linux-hardware.org/?probe=b5bbb4f410) | Dec 21, 2022 |
| MSI           | Modern 14 B4MW              | [2d446beedf](https://linux-hardware.org/?probe=2d446beedf) | Dec 21, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d9db7be046](https://linux-hardware.org/?probe=d9db7be046) | Dec 21, 2022 |
| Dell          | Latitude 5521               | [6fcbfd9271](https://linux-hardware.org/?probe=6fcbfd9271) | Dec 21, 2022 |
| Dell          | Latitude 3420               | [99d501d768](https://linux-hardware.org/?probe=99d501d768) | Dec 20, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [89b8982148](https://linux-hardware.org/?probe=89b8982148) | Dec 20, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [082a1fb19e](https://linux-hardware.org/?probe=082a1fb19e) | Dec 20, 2022 |
| Positivo B... | VJFE41F11X-XXXXXX           | [383b0f3311](https://linux-hardware.org/?probe=383b0f3311) | Dec 20, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [0d59e38c20](https://linux-hardware.org/?probe=0d59e38c20) | Dec 20, 2022 |
| HP            | ZBook 15                    | [a3bf671d64](https://linux-hardware.org/?probe=a3bf671d64) | Dec 20, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [af14f0c425](https://linux-hardware.org/?probe=af14f0c425) | Dec 20, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [e7393fd2b7](https://linux-hardware.org/?probe=e7393fd2b7) | Dec 20, 2022 |
| Dell          | Vostro 5620                 | [005d388376](https://linux-hardware.org/?probe=005d388376) | Dec 20, 2022 |
| Acer          | Aspire A515-52              | [b052f8434a](https://linux-hardware.org/?probe=b052f8434a) | Dec 20, 2022 |
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
| MSI           | GL63 8RC                    | [6a5bc85513](https://linux-hardware.org/?probe=6a5bc85513) | Dec 18, 2022 |
| Acer          | Swift SF114-32              | [757b666913](https://linux-hardware.org/?probe=757b666913) | Dec 18, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [23b255ed61](https://linux-hardware.org/?probe=23b255ed61) | Dec 18, 2022 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | [86c9426d80](https://linux-hardware.org/?probe=86c9426d80) | Dec 18, 2022 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | [05fcf7302f](https://linux-hardware.org/?probe=05fcf7302f) | Dec 18, 2022 |
| Acer          | Aspire A315-31              | [e391c56a47](https://linux-hardware.org/?probe=e391c56a47) | Dec 18, 2022 |
| Lenovo        | ThinkPad W550s 20E2000PG... | [938c10075a](https://linux-hardware.org/?probe=938c10075a) | Dec 18, 2022 |
| HP            | Laptop 15-da0xxx            | [b712a7bd77](https://linux-hardware.org/?probe=b712a7bd77) | Dec 18, 2022 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [56e75d70fa](https://linux-hardware.org/?probe=56e75d70fa) | Dec 18, 2022 |
| HP            | ProBook 450 G7              | [ad9bf6b390](https://linux-hardware.org/?probe=ad9bf6b390) | Dec 17, 2022 |
| Dell          | Inspiron 7720               | [0a7621cb40](https://linux-hardware.org/?probe=0a7621cb40) | Dec 17, 2022 |
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
| Dell          | XPS 15 9570                 | [ce6ac8ec7f](https://linux-hardware.org/?probe=ce6ac8ec7f) | Dec 16, 2022 |
| Dell          | XPS 13 9380                 | [719f489e01](https://linux-hardware.org/?probe=719f489e01) | Dec 15, 2022 |
| Dell          | Inspiron 7501               | [1749ece1b3](https://linux-hardware.org/?probe=1749ece1b3) | Dec 15, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [b8cc280665](https://linux-hardware.org/?probe=b8cc280665) | Dec 15, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [5e8318b8b8](https://linux-hardware.org/?probe=5e8318b8b8) | Dec 15, 2022 |
| HUAWEI        | KLVL-WXXW                   | [1dd0f2a71f](https://linux-hardware.org/?probe=1dd0f2a71f) | Dec 15, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [d5c9abda1e](https://linux-hardware.org/?probe=d5c9abda1e) | Dec 15, 2022 |
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
| HUAWEI        | NBLK-WAX9X                  | [5ea80edee8](https://linux-hardware.org/?probe=5ea80edee8) | Dec 14, 2022 |
| HP            | Laptop 14-fq1xxx            | [2da9ae7906](https://linux-hardware.org/?probe=2da9ae7906) | Dec 14, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [034b34f6d6](https://linux-hardware.org/?probe=034b34f6d6) | Dec 13, 2022 |
| Pegatron      | C17A                        | [adde308568](https://linux-hardware.org/?probe=adde308568) | Dec 13, 2022 |
| HP            | Laptop 14-fq1xxx            | [ed92313ebc](https://linux-hardware.org/?probe=ed92313ebc) | Dec 13, 2022 |
| HP            | ProBook 440 G7              | [ca2ba2d622](https://linux-hardware.org/?probe=ca2ba2d622) | Dec 13, 2022 |
| Toshiba       | TECRA A10                   | [760bda2b7d](https://linux-hardware.org/?probe=760bda2b7d) | Dec 13, 2022 |
| Acer          | Predator G9-591             | [838b0e0f8c](https://linux-hardware.org/?probe=838b0e0f8c) | Dec 13, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [6fc042d213](https://linux-hardware.org/?probe=6fc042d213) | Dec 13, 2022 |
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
| Dell          | XPS 15 9570                 | [b7b1ed9d8b](https://linux-hardware.org/?probe=b7b1ed9d8b) | Dec 12, 2022 |
| ASUSTek       | K55VD                       | [f74382c966](https://linux-hardware.org/?probe=f74382c966) | Dec 12, 2022 |
| Lenovo        | ThinkPad T590 20N5S4R800    | [9fb659eea3](https://linux-hardware.org/?probe=9fb659eea3) | Dec 12, 2022 |
| MSI           | GE63 Raider RGB 8RF         | [b311865418](https://linux-hardware.org/?probe=b311865418) | Dec 12, 2022 |
| MSI           | Modern 14 B11MOU            | [9739ffdf34](https://linux-hardware.org/?probe=9739ffdf34) | Dec 12, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | [257e692fa4](https://linux-hardware.org/?probe=257e692fa4) | Dec 11, 2022 |
| Toshiba       | Satellite A300              | [211e44e5d2](https://linux-hardware.org/?probe=211e44e5d2) | Dec 11, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [50e8243e50](https://linux-hardware.org/?probe=50e8243e50) | Dec 11, 2022 |
| Acer          | Aspire E5-576G              | [9cc371883c](https://linux-hardware.org/?probe=9cc371883c) | Dec 11, 2022 |
| Samsung       | 930X5J/910S5J/940X5J        | [deb721084b](https://linux-hardware.org/?probe=deb721084b) | Dec 11, 2022 |
| ASUSTek       | X75VD                       | [5cdd66c849](https://linux-hardware.org/?probe=5cdd66c849) | Dec 11, 2022 |
| ASUSTek       | X75VD                       | [624ea43f9d](https://linux-hardware.org/?probe=624ea43f9d) | Dec 11, 2022 |
| Notebook      | WA50SRQ                     | [da74211ac6](https://linux-hardware.org/?probe=da74211ac6) | Dec 11, 2022 |
| HP            | Pavilion g6                 | [b5662e5fec](https://linux-hardware.org/?probe=b5662e5fec) | Dec 11, 2022 |
| Dell          | Latitude E7240              | [591f0ad589](https://linux-hardware.org/?probe=591f0ad589) | Dec 11, 2022 |
| MSI           | Prestige 15 A11SCX          | [5941b1aed7](https://linux-hardware.org/?probe=5941b1aed7) | Dec 10, 2022 |
| MSI           | Prestige 15 A11SCX          | [ab1334fca2](https://linux-hardware.org/?probe=ab1334fca2) | Dec 10, 2022 |
| Dell          | G5 5505                     | [60053b5d4b](https://linux-hardware.org/?probe=60053b5d4b) | Dec 10, 2022 |
| Dell          | XPS 17 9700                 | [0426545e91](https://linux-hardware.org/?probe=0426545e91) | Dec 10, 2022 |
| Acer          | Predator PH315-52           | [e80dfca4a8](https://linux-hardware.org/?probe=e80dfca4a8) | Dec 10, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [25d5b5623b](https://linux-hardware.org/?probe=25d5b5623b) | Dec 10, 2022 |
| Acer          | Predator PH315-52           | [72f0e70b26](https://linux-hardware.org/?probe=72f0e70b26) | Dec 10, 2022 |
| Lenovo        | ThinkPad T480s 20L8S2N80... | [ad87e1559a](https://linux-hardware.org/?probe=ad87e1559a) | Dec 09, 2022 |
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
| Lenovo        | ThinkPad T520 4243CJ2       | [93e5e0ca9b](https://linux-hardware.org/?probe=93e5e0ca9b) | Dec 08, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | [182678a056](https://linux-hardware.org/?probe=182678a056) | Dec 08, 2022 |
| Acer          | Aspire E1-572G              | [df78e85dfe](https://linux-hardware.org/?probe=df78e85dfe) | Dec 08, 2022 |
| HP            | ProBook 640 G1              | [c3bf44d032](https://linux-hardware.org/?probe=c3bf44d032) | Dec 08, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [9122edaf0a](https://linux-hardware.org/?probe=9122edaf0a) | Dec 08, 2022 |
| HUAWEI        | MACH-WX9                    | [5ed19862a7](https://linux-hardware.org/?probe=5ed19862a7) | Dec 08, 2022 |
| HP            | Laptop 14-dk1xxx            | [1c73b61db3](https://linux-hardware.org/?probe=1c73b61db3) | Dec 08, 2022 |
| Dell          | Inspiron 5566               | [dcf5539e74](https://linux-hardware.org/?probe=dcf5539e74) | Dec 08, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [091e12e551](https://linux-hardware.org/?probe=091e12e551) | Dec 08, 2022 |
| Lenovo        | V14 G2 ITL 82NM             | [00995baaae](https://linux-hardware.org/?probe=00995baaae) | Dec 07, 2022 |
| HP            | EliteBook 820 G1            | [59118a0638](https://linux-hardware.org/?probe=59118a0638) | Dec 07, 2022 |
| Dell          | XPS 13 9350                 | [9779817777](https://linux-hardware.org/?probe=9779817777) | Dec 07, 2022 |
| Lenovo        | ThinkPad T460 20FN002JUS    | [efe4d93e2d](https://linux-hardware.org/?probe=efe4d93e2d) | Dec 07, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [82d49749a2](https://linux-hardware.org/?probe=82d49749a2) | Dec 07, 2022 |
| Acer          | Aspire E5-571               | [d5d013b642](https://linux-hardware.org/?probe=d5d013b642) | Dec 07, 2022 |
| HP            | Laptop 14-dk1xxx            | [3e50ee3f94](https://linux-hardware.org/?probe=3e50ee3f94) | Dec 07, 2022 |
| HP            | EliteBook 820 G1            | [a214979767](https://linux-hardware.org/?probe=a214979767) | Dec 07, 2022 |
| Dell          | Latitude E6420              | [e87ced9ea4](https://linux-hardware.org/?probe=e87ced9ea4) | Dec 06, 2022 |
| Dell          | Latitude E6420              | [17c9263444](https://linux-hardware.org/?probe=17c9263444) | Dec 06, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [a3b78e7093](https://linux-hardware.org/?probe=a3b78e7093) | Dec 06, 2022 |
| Acer          | Predator G9-591             | [6e8fe2e030](https://linux-hardware.org/?probe=6e8fe2e030) | Dec 06, 2022 |
| Acer          | Aspire E5-571               | [e9d00a798c](https://linux-hardware.org/?probe=e9d00a798c) | Dec 06, 2022 |
| HP            | Laptop 17-ak0xx             | [9fb5c9d094](https://linux-hardware.org/?probe=9fb5c9d094) | Dec 06, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [2f14f32399](https://linux-hardware.org/?probe=2f14f32399) | Dec 06, 2022 |
| BANGHO        | BES T5                      | [db1db74a86](https://linux-hardware.org/?probe=db1db74a86) | Dec 06, 2022 |
| HP            | Laptop 14-fq1xxx            | [4f93d8895e](https://linux-hardware.org/?probe=4f93d8895e) | Dec 06, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [12e33b1925](https://linux-hardware.org/?probe=12e33b1925) | Dec 06, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [36985fd47e](https://linux-hardware.org/?probe=36985fd47e) | Dec 05, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [a6763bdd89](https://linux-hardware.org/?probe=a6763bdd89) | Dec 05, 2022 |
| Dell          | Latitude 7490               | [7377ad6d99](https://linux-hardware.org/?probe=7377ad6d99) | Dec 05, 2022 |
| Dell          | XPS 13 9343                 | [476763a913](https://linux-hardware.org/?probe=476763a913) | Dec 05, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c22a748043](https://linux-hardware.org/?probe=c22a748043) | Dec 05, 2022 |
| Dell          | Latitude 7490               | [e75a902d11](https://linux-hardware.org/?probe=e75a902d11) | Dec 05, 2022 |
| ASUSTek       | X510UNR                     | [b85ac74a3f](https://linux-hardware.org/?probe=b85ac74a3f) | Dec 05, 2022 |
| MSI           | Modern 14 B4MW              | [03c0b9e50d](https://linux-hardware.org/?probe=03c0b9e50d) | Dec 05, 2022 |
| Lenovo        | ThinkPad neo 14 21DN0009... | [80c8d84387](https://linux-hardware.org/?probe=80c8d84387) | Dec 05, 2022 |
| HP            | 245 G7                      | [57ed16df1f](https://linux-hardware.org/?probe=57ed16df1f) | Dec 05, 2022 |
| HP            | Pavilion Laptop 15-eg2xx... | [9b87c97ed5](https://linux-hardware.org/?probe=9b87c97ed5) | Dec 05, 2022 |
| HP            | Pavilion Laptop 15-eg2xx... | [fe17634e66](https://linux-hardware.org/?probe=fe17634e66) | Dec 05, 2022 |
| HP            | ProBook 440 14 inch G9 N... | [41a365e56e](https://linux-hardware.org/?probe=41a365e56e) | Dec 04, 2022 |
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
| HP            | Pavilion Laptop 15-eh1xx... | [3807efd1f4](https://linux-hardware.org/?probe=3807efd1f4) | Dec 03, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [c00aab388c](https://linux-hardware.org/?probe=c00aab388c) | Dec 03, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [037216f966](https://linux-hardware.org/?probe=037216f966) | Dec 03, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [1c27bd3d06](https://linux-hardware.org/?probe=1c27bd3d06) | Dec 03, 2022 |
| MSI           | Modern 14 B4MW              | [6890b98eeb](https://linux-hardware.org/?probe=6890b98eeb) | Dec 03, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | [77651c30c5](https://linux-hardware.org/?probe=77651c30c5) | Dec 03, 2022 |
| Dell          | Inspiron 5567               | [d64c6bc6f4](https://linux-hardware.org/?probe=d64c6bc6f4) | Dec 03, 2022 |
| Dell          | Inspiron 5567               | [a9f812a233](https://linux-hardware.org/?probe=a9f812a233) | Dec 03, 2022 |
| Acer          | Aspire A715-51G             | [65aa3f7e69](https://linux-hardware.org/?probe=65aa3f7e69) | Dec 03, 2022 |
| HUAWEI        | MACHC-WAX9                  | [958e17ffc9](https://linux-hardware.org/?probe=958e17ffc9) | Dec 03, 2022 |
| Toshiba       | Satellite C50D-A-138        | [ccda846d5e](https://linux-hardware.org/?probe=ccda846d5e) | Dec 03, 2022 |
| HP            | Laptop 14-dk1xxx            | [38d691df3b](https://linux-hardware.org/?probe=38d691df3b) | Dec 03, 2022 |
| Acer          | Nitro AN515-44              | [56a2d42adc](https://linux-hardware.org/?probe=56a2d42adc) | Dec 02, 2022 |
| Dell          | XPS 13 9350                 | [38c002d686](https://linux-hardware.org/?probe=38c002d686) | Dec 02, 2022 |
| Google        | Lick                        | [a03c415d36](https://linux-hardware.org/?probe=a03c415d36) | Dec 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [dc80fd6907](https://linux-hardware.org/?probe=dc80fd6907) | Dec 02, 2022 |
| Dell          | Inspiron 16 5625            | [6e1523c2e8](https://linux-hardware.org/?probe=6e1523c2e8) | Dec 02, 2022 |
| HP            | ProBook 6570b               | [be8f757095](https://linux-hardware.org/?probe=be8f757095) | Dec 02, 2022 |
| HP            | ProBook 6570b               | [1e40d6a94b](https://linux-hardware.org/?probe=1e40d6a94b) | Dec 02, 2022 |
| HP            | Pavilion Laptop 14-bk0xx    | [57c3eeaf3d](https://linux-hardware.org/?probe=57c3eeaf3d) | Dec 02, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| Fedora 36 | 1203      | 18.9%   |
| Fedora 35 | 960       | 15.08%  |
| Fedora 34 | 929       | 14.6%   |
| Fedora 37 | 865       | 13.59%  |
| Fedora 33 | 853       | 13.4%   |
| Fedora 32 | 746       | 11.72%  |
| Fedora 31 | 503       | 7.9%    |
| Fedora 30 | 162       | 2.55%   |
| Fedora 29 | 90        | 1.41%   |
| Fedora 28 | 22        | 0.35%   |
| Fedora 38 | 11        | 0.17%   |
| Fedora 27 | 8         | 0.13%   |
| Fedora 24 | 4         | 0.06%   |
| Fedora 21 | 4         | 0.06%   |
| Fedora 39 | 2         | 0.03%   |
| Fedora 25 | 2         | 0.03%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Fedora | 5706      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 5.17.5-300.fc36.x86_64  | 111       | 1.56%   |
| 5.16.18-200.fc35.x86_64 | 92        | 1.29%   |
| 5.9.16-200.fc33.x86_64  | 90        | 1.27%   |
| 5.11.12-300.fc34.x86_64 | 76        | 1.07%   |
| 6.0.15-300.fc37.x86_64  | 75        | 1.06%   |
| 6.0.5-200.fc36.x86_64   | 69        | 0.97%   |
| 5.14.10-300.fc35.x86_64 | 69        | 0.97%   |
| 6.0.7-301.fc37.x86_64   | 64        | 0.9%    |
| 5.8.16-300.fc33.x86_64  | 64        | 0.9%    |
| 5.18.13-200.fc36.x86_64 | 61        | 0.86%   |
| 5.8.15-301.fc33.x86_64  | 60        | 0.84%   |
| 5.8.4-200.fc32.x86_64   | 57        | 0.8%    |
| 6.1.7-200.fc37.x86_64   | 55        | 0.77%   |
| 6.0.8-300.fc37.x86_64   | 54        | 0.76%   |
| 5.13.12-200.fc34.x86_64 | 54        | 0.76%   |
| 6.0.9-300.fc37.x86_64   | 51        | 0.72%   |
| 6.0.12-300.fc37.x86_64  | 51        | 0.72%   |
| 5.18.11-200.fc36.x86_64 | 50        | 0.7%    |
| 5.19.16-200.fc36.x86_64 | 47        | 0.66%   |
| 5.8.18-300.fc33.x86_64  | 46        | 0.65%   |
| 5.17.11-300.fc36.x86_64 | 46        | 0.65%   |
| 5.14.16-301.fc35.x86_64 | 46        | 0.65%   |
| 5.9.8-200.fc33.x86_64   | 45        | 0.63%   |
| 5.18.16-200.fc36.x86_64 | 45        | 0.63%   |
| 5.16.16-200.fc35.x86_64 | 44        | 0.62%   |
| 5.17.6-300.fc36.x86_64  | 43        | 0.61%   |
| 5.19.9-200.fc36.x86_64  | 42        | 0.59%   |
| 5.15.6-200.fc35.x86_64  | 42        | 0.59%   |
| 6.1.8-200.fc37.x86_64   | 41        | 0.58%   |
| 5.16.12-200.fc35.x86_64 | 41        | 0.58%   |
| 5.10.19-200.fc33.x86_64 | 41        | 0.58%   |
| 6.1.11-200.fc37.x86_64  | 40        | 0.56%   |
| 5.9.11-200.fc33.x86_64  | 40        | 0.56%   |
| 6.1.9-200.fc37.x86_64   | 39        | 0.55%   |
| 5.3.16-300.fc31.x86_64  | 39        | 0.55%   |
| 5.18.17-200.fc36.x86_64 | 39        | 0.55%   |
| 5.12.13-300.fc34.x86_64 | 39        | 0.55%   |
| 5.7.8-200.fc32.x86_64   | 38        | 0.53%   |
| 5.19.8-200.fc36.x86_64  | 38        | 0.53%   |
| 5.18.5-200.fc36.x86_64  | 38        | 0.53%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.17.5  | 145       | 2.04%   |
| 5.9.16  | 96        | 1.35%   |
| 5.16.18 | 95        | 1.34%   |
| 5.8.15  | 87        | 1.23%   |
| 6.0.15  | 85        | 1.2%    |
| 5.11.12 | 83        | 1.17%   |
| 5.8.16  | 81        | 1.14%   |
| 5.14.10 | 78        | 1.1%    |
| 6.0.5   | 75        | 1.06%   |
| 5.19.16 | 75        | 1.06%   |
| 6.0.7   | 74        | 1.04%   |
| 6.0.9   | 66        | 0.93%   |
| 5.11.11 | 66        | 0.93%   |
| 5.18.13 | 65        | 0.92%   |
| 6.0.8   | 64        | 0.9%    |
| 5.8.18  | 64        | 0.9%    |
| 6.1.7   | 59        | 0.83%   |
| 6.0.12  | 58        | 0.82%   |
| 5.8.4   | 57        | 0.8%    |
| 5.13.12 | 57        | 0.8%    |
| 5.14.18 | 55        | 0.77%   |
| 5.18.11 | 53        | 0.75%   |
| 5.14.16 | 52        | 0.73%   |
| 5.9.8   | 51        | 0.72%   |
| 5.19.8  | 50        | 0.7%    |
| 5.17.11 | 50        | 0.7%    |
| 5.15.6  | 50        | 0.7%    |
| 5.19.9  | 49        | 0.69%   |
| 5.18.16 | 48        | 0.68%   |
| 5.17.6  | 47        | 0.66%   |
| 5.16.16 | 47        | 0.66%   |
| 5.16.12 | 46        | 0.65%   |
| 6.0.10  | 45        | 0.63%   |
| 5.10.19 | 45        | 0.63%   |
| 6.1.8   | 44        | 0.62%   |
| 5.6.6   | 44        | 0.62%   |
| 5.18.5  | 44        | 0.62%   |
| 5.9.11  | 43        | 0.61%   |
| 5.15.12 | 43        | 0.61%   |
| 6.1.9   | 42        | 0.59%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.0     | 609       | 8.97%   |
| 5.17    | 504       | 7.42%   |
| 5.8     | 464       | 6.84%   |
| 5.11    | 448       | 6.6%    |
| 5.19    | 446       | 6.57%   |
| 5.18    | 409       | 6.03%   |
| 5.14    | 391       | 5.76%   |
| 5.16    | 384       | 5.66%   |
| 6.1     | 332       | 4.89%   |
| 5.15    | 310       | 4.57%   |
| 5.9     | 304       | 4.48%   |
| 5.13    | 303       | 4.46%   |
| 5.10    | 292       | 4.3%    |
| 5.6     | 286       | 4.21%   |
| 5.12    | 282       | 4.15%   |
| 5.7     | 221       | 3.26%   |
| 5.3     | 194       | 2.86%   |
| 5.5     | 183       | 2.7%    |
| 5.4     | 168       | 2.47%   |
| 5.0     | 61        | 0.9%    |
| 5.2     | 47        | 0.69%   |
| 5.1     | 43        | 0.63%   |
| 4.19    | 30        | 0.44%   |
| 4.18    | 27        | 0.4%    |
| 4.20    | 18        | 0.27%   |
| 6.2     | 11        | 0.16%   |
| 4.16    | 3         | 0.04%   |
| 4.15    | 3         | 0.04%   |
| 4.11    | 3         | 0.04%   |
| 4.1     | 3         | 0.04%   |
| 4.8     | 2         | 0.03%   |
| 4.17    | 2         | 0.03%   |
| 4.5     | 1         | 0.01%   |
| 4.14    | 1         | 0.01%   |
| 4.10    | 1         | 0.01%   |
| 3.17    | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 5697      | 99.82%  |
| i686    | 5         | 0.09%   |
| aarch64 | 4         | 0.07%   |
| Unknown | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 4309      | 73.37%  |
| KDE5            | 630       | 10.73%  |
| Unknown         | 302       | 5.14%   |
| KDE             | 136       | 2.32%   |
| XFCE            | 122       | 2.08%   |
| X-Cinnamon      | 83        | 1.41%   |
| MATE            | 79        | 1.35%   |
| Cinnamon        | 68        | 1.16%   |
| i3              | 30        | 0.51%   |
| LXQt            | 21        | 0.36%   |
| GNOME Classic   | 21        | 0.36%   |
| LXDE            | 16        | 0.27%   |
| sway            | 13        | 0.22%   |
| Deepin          | 12        | 0.2%    |
| Pantheon        | 4         | 0.07%   |
| awesome         | 4         | 0.07%   |
| openbox         | 3         | 0.05%   |
| KDE4            | 3         | 0.05%   |
| GNOME Flashback | 3         | 0.05%   |
| fluxbox         | 3         | 0.05%   |
| Budgie          | 3         | 0.05%   |
| bspwm           | 2         | 0.03%   |
| xmonad          | 1         | 0.02%   |
| xinit-compat    | 1         | 0.02%   |
| qtile           | 1         | 0.02%   |
| KDE:old         | 1         | 0.02%   |
| GNOME-Classic   | 1         | 0.02%   |
| DWM             | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 3791      | 63.95%  |
| X11     | 1900      | 32.05%  |
| Unknown | 195       | 3.29%   |
| Tty     | 42        | 0.71%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 2933      | 49.96%  |
| GDM     | 2201      | 37.49%  |
| SDDM    | 407       | 6.93%   |
| LightDM | 218       | 3.71%   |
| TDM     | 87        | 1.48%   |
| XDM     | 10        | 0.17%   |
| KDM     | 8         | 0.14%   |
| LXDM    | 5         | 0.09%   |
| Ly      | 1         | 0.02%   |
| GREETD  | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 2962      | 50.93%  |
| en_GB   | 386       | 6.64%   |
| Unknown | 366       | 6.29%   |
| pt_BR   | 272       | 4.68%   |
| ru_RU   | 261       | 4.49%   |
| de_DE   | 197       | 3.39%   |
| fr_FR   | 173       | 2.97%   |
| it_IT   | 156       | 2.68%   |
| pl_PL   | 98        | 1.69%   |
| es_ES   | 86        | 1.48%   |
| en_CA   | 83        | 1.43%   |
| en_AU   | 75        | 1.29%   |
| en_IN   | 71        | 1.22%   |
| es_MX   | 52        | 0.89%   |
| cs_CZ   | 38        | 0.65%   |
| es_CL   | 32        | 0.55%   |
| es_AR   | 30        | 0.52%   |
| tr_TR   | 28        | 0.48%   |
| zh_CN   | 26        | 0.45%   |
| nl_NL   | 24        | 0.41%   |
| de_AT   | 21        | 0.36%   |
| pt_PT   | 20        | 0.34%   |
| en_NZ   | 20        | 0.34%   |
| C       | 20        | 0.34%   |
| sv_SE   | 19        | 0.33%   |
| es_CO   | 18        | 0.31%   |
| hu_HU   | 17        | 0.29%   |
| en_DK   | 16        | 0.28%   |
| en_IE   | 15        | 0.26%   |
| en_ZA   | 13        | 0.22%   |
| fr_CA   | 12        | 0.21%   |
| fi_FI   | 12        | 0.21%   |
| ru_UA   | 11        | 0.19%   |
| fr_BE   | 10        | 0.17%   |
| de_CH   | 10        | 0.17%   |
| nb_NO   | 9         | 0.15%   |
| uk_UA   | 8         | 0.14%   |
| sk_SK   | 8         | 0.14%   |
| da_DK   | 8         | 0.14%   |
| zh_TW   | 7         | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 4593      | 79.39%  |
| BIOS | 1192      | 20.61%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type                | Notebooks | Percent |
|---------------------|-----------|---------|
| Btrfs               | 3358      | 57.35%  |
| Ext4                | 2139      | 36.53%  |
| Unknown             | 195       | 3.33%   |
| Xfs                 | 144       | 2.46%   |
| Overlay             | 11        | 0.19%   |
| F2fs                | 3         | 0.05%   |
| Zfs                 | 2         | 0.03%   |
| Fuse.fuse-overlayfs | 2         | 0.03%   |
| Ext3                | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 2920      | 50%     |
| GPT     | 2538      | 43.46%  |
| MBR     | 382       | 6.54%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 5244      | 90.77%  |
| Yes       | 533       | 9.23%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 4697      | 81.29%  |
| Yes       | 1081      | 18.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 1715      | 30.06%  |
| Dell                   | 1050      | 18.4%   |
| Hewlett-Packard        | 840       | 14.72%  |
| ASUSTek Computer       | 566       | 9.92%   |
| Acer                   | 381       | 6.68%   |
| Apple                  | 146       | 2.56%   |
| MSI                    | 127       | 2.23%   |
| HUAWEI                 | 108       | 1.89%   |
| Toshiba                | 82        | 1.44%   |
| Samsung Electronics    | 76        | 1.33%   |
| Sony                   | 47        | 0.82%   |
| Notebook               | 45        | 0.79%   |
| Timi                   | 39        | 0.68%   |
| Framework              | 29        | 0.51%   |
| Unknown                | 29        | 0.51%   |
| Alienware              | 24        | 0.42%   |
| Fujitsu                | 23        | 0.4%    |
| Positivo               | 22        | 0.39%   |
| Google                 | 22        | 0.39%   |
| TUXEDO                 | 17        | 0.3%    |
| System76               | 17        | 0.3%    |
| LG Electronics         | 16        | 0.28%   |
| Razer                  | 15        | 0.26%   |
| Chuwi                  | 11        | 0.19%   |
| Gigabyte Technology    | 10        | 0.18%   |
| Avell High Performance | 9         | 0.16%   |
| PC Specialist          | 8         | 0.14%   |
| SLIMBOOK               | 7         | 0.12%   |
| Schenker               | 7         | 0.12%   |
| Panasonic              | 7         | 0.12%   |
| HONOR                  | 7         | 0.12%   |
| GPU Company            | 7         | 0.12%   |
| GPD                    | 7         | 0.12%   |
| Fujitsu Siemens        | 7         | 0.12%   |
| Packard Bell           | 6         | 0.11%   |
| Standard               | 5         | 0.09%   |
| Hampoo                 | 5         | 0.09%   |
| Gateway                | 5         | 0.09%   |
| eMachines              | 5         | 0.09%   |
| Clevo                  | 5         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 49        | 0.86%   |
| HP Notebook                                | 29        | 0.51%   |
| Dell XPS 15 9570                           | 25        | 0.44%   |
| Framework Laptop                           | 23        | 0.4%    |
| Dell XPS 15 7590                           | 22        | 0.39%   |
| Dell XPS 13 9370                           | 21        | 0.37%   |
| Dell Latitude 7490                         | 21        | 0.37%   |
| Dell XPS 15 9560                           | 19        | 0.33%   |
| Dell XPS 13 9360                           | 19        | 0.33%   |
| HP EliteBook 840 G6                        | 18        | 0.32%   |
| Dell XPS 13 7390                           | 18        | 0.32%   |
| HP Pavilion dv6                            | 17        | 0.3%    |
| Dell XPS 15 9550                           | 16        | 0.28%   |
| HP Pavilion 15                             | 15        | 0.26%   |
| Dell XPS 15 9500                           | 15        | 0.26%   |
| Dell XPS 13 9310                           | 15        | 0.26%   |
| Dell Latitude E7450                        | 15        | 0.26%   |
| Lenovo ThinkPad X1 Carbon Gen 8 20U9CTO1WW | 13        | 0.23%   |
| Lenovo ThinkBook 15 G2 ITL 20VE            | 13        | 0.23%   |
| HP Laptop 15-da0xxx                        | 13        | 0.23%   |
| Dell XPS 13 9300                           | 13        | 0.23%   |
| Dell Latitude E6420                        | 13        | 0.23%   |
| Dell Latitude 5480                         | 13        | 0.23%   |
| Dell Inspiron 15 7000 Gaming               | 13        | 0.23%   |
| Apple MacBookPro12,1                       | 13        | 0.23%   |
| Lenovo IdeaPad 5 15ARE05 81YQ              | 12        | 0.21%   |
| HUAWEI KLVL-WXX9                           | 12        | 0.21%   |
| HP Pavilion Notebook                       | 12        | 0.21%   |
| HP EliteBook 840 G3                        | 12        | 0.21%   |
| Dell Latitude E7440                        | 12        | 0.21%   |
| Dell Inspiron 5570                         | 12        | 0.21%   |
| HUAWEI NBLK-WAX9X                          | 11        | 0.19%   |
| Apple MacBookPro9,2                        | 11        | 0.19%   |
| Acer Aspire E5-573G                        | 11        | 0.19%   |
| HUAWEI MACH-WX9                            | 10        | 0.18%   |
| HP Pavilion dv7                            | 10        | 0.18%   |
| Dell XPS 15 9510                           | 10        | 0.18%   |
| Dell XPS 13 9380                           | 10        | 0.18%   |
| Dell XPS 13 9350                           | 10        | 0.18%   |
| Dell Latitude E6520                        | 10        | 0.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 1052      | 18.44%  |
| Lenovo IdeaPad     | 346       | 6.06%   |
| Dell Latitude      | 307       | 5.38%   |
| Dell Inspiron      | 298       | 5.22%   |
| Dell XPS           | 246       | 4.31%   |
| Acer Aspire        | 244       | 4.28%   |
| HP Pavilion        | 178       | 3.12%   |
| HP EliteBook       | 166       | 2.91%   |
| HP ProBook         | 133       | 2.33%   |
| HP Laptop          | 118       | 2.07%   |
| ASUS VivoBook      | 107       | 1.88%   |
| ASUS ROG           | 86        | 1.51%   |
| Dell Precision     | 85        | 1.49%   |
| Toshiba Satellite  | 70        | 1.23%   |
| Lenovo Legion      | 65        | 1.14%   |
| Lenovo ThinkBook   | 62        | 1.09%   |
| Dell Vostro        | 52        | 0.91%   |
| Lenovo Yoga        | 49        | 0.86%   |
| HP ZBook           | 49        | 0.86%   |
| Acer Nitro         | 49        | 0.86%   |
| Unknown            | 49        | 0.86%   |
| ASUS ASUS          | 45        | 0.79%   |
| ASUS ZenBook       | 44        | 0.77%   |
| Acer Swift         | 39        | 0.68%   |
| HP ENVY            | 36        | 0.63%   |
| Apple MacBookPro11 | 30        | 0.53%   |
| HP Notebook        | 29        | 0.51%   |
| Framework Laptop   | 29        | 0.51%   |
| HP OMEN            | 27        | 0.47%   |
| ASUS TUF           | 26        | 0.46%   |
| MSI Modern         | 20        | 0.35%   |
| Fujitsu LIFEBOOK   | 19        | 0.33%   |
| Dell G5            | 19        | 0.33%   |
| Acer Predator      | 18        | 0.32%   |
| Razer Blade        | 14        | 0.25%   |
| Apple MacBookPro9  | 14        | 0.25%   |
| Dell G3            | 13        | 0.23%   |
| Apple MacBookPro12 | 13        | 0.23%   |
| HUAWEI KLVL-WXX9   | 12        | 0.21%   |
| HP 250             | 12        | 0.21%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 784       | 13.74%  |
| 2019    | 765       | 13.41%  |
| 2018    | 630       | 11.04%  |
| 2021    | 629       | 11.02%  |
| 2017    | 456       | 7.99%   |
| 2015    | 372       | 6.52%   |
| 2016    | 354       | 6.2%    |
| 2012    | 331       | 5.8%    |
| 2013    | 327       | 5.73%   |
| 2014    | 266       | 4.66%   |
| 2011    | 259       | 4.54%   |
| 2022    | 227       | 3.98%   |
| 2010    | 133       | 2.33%   |
| 2008    | 82        | 1.44%   |
| 2009    | 62        | 1.09%   |
| 2007    | 15        | 0.26%   |
| 2006    | 5         | 0.09%   |
| 2023    | 4         | 0.07%   |
| Unknown | 4         | 0.07%   |
| 2003    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 5706      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 4617      | 79.58%  |
| Enabled  | 1185      | 20.42%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 5669      | 99.35%  |
| Yes  | 37        | 0.65%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1716      | 29.63%  |
| 16.01-24.0  | 1394      | 24.07%  |
| 8.01-16.0   | 1143      | 19.74%  |
| 32.01-64.0  | 629       | 10.86%  |
| 3.01-4.0    | 570       | 9.84%   |
| 1.01-2.0    | 107       | 1.85%   |
| 24.01-32.0  | 98        | 1.69%   |
| 64.01-256.0 | 98        | 1.69%   |
| 2.01-3.0    | 24        | 0.41%   |
| 0.51-1.0    | 10        | 0.17%   |
| Unknown     | 2         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 1812      | 28.19%  |
| 4.01-8.0   | 1744      | 27.13%  |
| 3.01-4.0   | 1390      | 21.62%  |
| 1.01-2.0   | 879       | 13.67%  |
| 8.01-16.0  | 460       | 7.16%   |
| 0.51-1.0   | 68        | 1.06%   |
| 16.01-24.0 | 53        | 0.82%   |
| 24.01-32.0 | 10        | 0.16%   |
| 32.01-64.0 | 7         | 0.11%   |
| 0.01-0.5   | 3         | 0.05%   |
| Unknown    | 2         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 4185      | 72.07%  |
| 2      | 1386      | 23.87%  |
| 3      | 165       | 2.84%   |
| 0      | 34        | 0.59%   |
| 4      | 26        | 0.45%   |
| 5      | 6         | 0.1%    |
| 6      | 5         | 0.09%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 4504      | 78.54%  |
| Yes       | 1231      | 21.46%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4273      | 74.48%  |
| No        | 1464      | 25.52%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 5560      | 97.36%  |
| No        | 151       | 2.64%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4783      | 82.82%  |
| No        | 992       | 17.18%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 982       | 17.03%  |
| Brazil      | 421       | 7.3%    |
| Germany     | 391       | 6.78%   |
| Russia      | 373       | 6.47%   |
| Italy       | 270       | 4.68%   |
| France      | 238       | 4.13%   |
| India       | 223       | 3.87%   |
| UK          | 195       | 3.38%   |
| Poland      | 175       | 3.03%   |
| Netherlands | 164       | 2.84%   |
| Canada      | 161       | 2.79%   |
| Spain       | 137       | 2.38%   |
| Mexico      | 100       | 1.73%   |
| Czechia     | 100       | 1.73%   |
| Australia   | 94        | 1.63%   |
| Turkey      | 91        | 1.58%   |
| Austria     | 78        | 1.35%   |
| Sweden      | 75        | 1.3%    |
| Switzerland | 62        | 1.08%   |
| Ukraine     | 59        | 1.02%   |
| Argentina   | 57        | 0.99%   |
| Portugal    | 55        | 0.95%   |
| Romania     | 53        | 0.92%   |
| Belgium     | 52        | 0.9%    |
| Indonesia   | 51        | 0.88%   |
| Norway      | 50        | 0.87%   |
| Finland     | 49        | 0.85%   |
| Hungary     | 46        | 0.8%    |
| Chile       | 44        | 0.76%   |
| Denmark     | 40        | 0.69%   |
| China       | 37        | 0.64%   |
| Iran        | 34        | 0.59%   |
| Colombia    | 33        | 0.57%   |
| Greece      | 31        | 0.54%   |
| Bulgaria    | 30        | 0.52%   |
| Slovakia    | 29        | 0.5%    |
| Israel      | 28        | 0.49%   |
| Belarus     | 27        | 0.47%   |
| New Zealand | 25        | 0.43%   |
| Japan       | 24        | 0.42%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 125       | 2.03%   |
| Sao Paulo         | 59        | 0.96%   |
| St Petersburg     | 52        | 0.85%   |
| Vienna            | 50        | 0.81%   |
| Paris             | 45        | 0.73%   |
| Amsterdam         | 43        | 0.7%    |
| Istanbul          | 42        | 0.68%   |
| Berlin            | 42        | 0.68%   |
| Warsaw            | 41        | 0.67%   |
| Prague            | 41        | 0.67%   |
| Milan             | 41        | 0.67%   |
| Madrid            | 35        | 0.57%   |
| Oslo              | 30        | 0.49%   |
| Munich            | 30        | 0.49%   |
| Bengaluru         | 29        | 0.47%   |
| Sydney            | 28        | 0.46%   |
| Helsinki          | 28        | 0.46%   |
| Mexico City       | 27        | 0.44%   |
| Melbourne         | 25        | 0.41%   |
| Kyiv              | 23        | 0.37%   |
| Frankfurt am Main | 23        | 0.37%   |
| Budapest          | 23        | 0.37%   |
| Bucharest         | 23        | 0.37%   |
| Zurich            | 22        | 0.36%   |
| Rio de Janeiro    | 22        | 0.36%   |
| Brisbane          | 22        | 0.36%   |
| Tehran            | 20        | 0.33%   |
| Hamburg           | 20        | 0.33%   |
| Santiago          | 19        | 0.31%   |
| Montreal          | 19        | 0.31%   |
| Lisbon            | 19        | 0.31%   |
| Jakarta           | 19        | 0.31%   |
| Chicago           | 19        | 0.31%   |
| Sofia             | 18        | 0.29%   |
| Singapore         | 18        | 0.29%   |
| Rome              | 18        | 0.29%   |
| Portland          | 18        | 0.29%   |
| Delft             | 18        | 0.29%   |
| Brno              | 18        | 0.29%   |
| Brasília         | 18        | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 1528      | 2213   | 21.1%   |
| WDC                       | 749       | 949    | 10.34%  |
| Seagate                   | 560       | 739    | 7.73%   |
| Toshiba                   | 513       | 635    | 7.08%   |
| SanDisk                   | 511       | 668    | 7.06%   |
| SK hynix                  | 432       | 534    | 5.97%   |
| Unknown                   | 377       | 494    | 5.21%   |
| Kingston                  | 348       | 429    | 4.81%   |
| Intel                     | 310       | 435    | 4.28%   |
| Crucial                   | 225       | 289    | 3.11%   |
| Micron Technology         | 222       | 290    | 3.07%   |
| HGST                      | 150       | 214    | 2.07%   |
| A-DATA Technology         | 109       | 126    | 1.51%   |
| KIOXIA                    | 106       | 146    | 1.46%   |
| Apple                     | 85        | 106    | 1.17%   |
| Hitachi                   | 77        | 89     | 1.06%   |
| LITEON                    | 72        | 77     | 0.99%   |
| Phison                    | 52        | 57     | 0.72%   |
| China                     | 45        | 51     | 0.62%   |
| Silicon Motion            | 38        | 54     | 0.52%   |
| Transcend                 | 35        | 52     | 0.48%   |
| PNY                       | 33        | 43     | 0.46%   |
| SPCC                      | 30        | 38     | 0.41%   |
| LITEONIT                  | 25        | 31     | 0.35%   |
| ADATA Technology          | 22        | 23     | 0.3%    |
| Lenovo                    | 21        | 24     | 0.29%   |
| Micron/Crucial Technology | 19        | 21     | 0.26%   |
| Corsair                   | 19        | 24     | 0.26%   |
| XPG                       | 18        | 27     | 0.25%   |
| Unknown                   | 18        | 21     | 0.25%   |
| Patriot                   | 17        | 22     | 0.23%   |
| Realtek Semiconductor     | 16        | 21     | 0.22%   |
| UMIS                      | 15        | 18     | 0.21%   |
| Phison Electronics        | 15        | 16     | 0.21%   |
| OCZ                       | 15        | 17     | 0.21%   |
| Team                      | 14        | 17     | 0.19%   |
| JMicron Technology        | 14        | 16     | 0.19%   |
| Intenso                   | 13        | 16     | 0.18%   |
| Gigabyte Technology       | 13        | 15     | 0.18%   |
| Lite-On                   | 12        | 18     | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                       | 118       | 1.55%   |
| Samsung NVMe SSD Drive 512GB                         | 113       | 1.49%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB               | 83        | 1.09%   |
| SanDisk NVMe SSD Drive 512GB                         | 77        | 1.01%   |
| Kingston SA400S37240G 240GB SSD                      | 68        | 0.89%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 67        | 0.88%   |
| HGST HTS721010A9E630 1TB                             | 66        | 0.87%   |
| Toshiba MQ04ABF100 1TB                               | 62        | 0.82%   |
| Unknown MMC Card  32GB                               | 60        | 0.79%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB  | 60        | 0.79%   |
| Toshiba MQ01ABD100 1TB                               | 53        | 0.7%    |
| Samsung SSD 860 EVO 500GB                            | 53        | 0.7%    |
| SK hynix NVMe SSD Drive 512GB                        | 51        | 0.67%   |
| Samsung NVMe SSD Drive 1024GB                        | 51        | 0.67%   |
| Unknown MMC Card  64GB                               | 49        | 0.64%   |
| SanDisk NVMe SSD Drive 256GB                         | 46        | 0.61%   |
| Intel NVMe SSD Drive 512GB                           | 46        | 0.61%   |
| Samsung NVMe SSD Drive 1TB                           | 43        | 0.57%   |
| Kingston SA400S37480G 480GB SSD                      | 41        | 0.54%   |
| Samsung SSD 850 EVO 250GB                            | 40        | 0.53%   |
| Toshiba NVMe SSD Drive 512GB                         | 38        | 0.5%    |
| Samsung SSD 850 EVO 500GB                            | 38        | 0.5%    |
| Unknown MMC Card  128GB                              | 34        | 0.45%   |
| Toshiba NVMe SSD Drive 256GB                         | 33        | 0.43%   |
| Seagate ST500LT012-1DG142 500GB                      | 33        | 0.43%   |
| Samsung NVMe SSD Drive 500GB                         | 33        | 0.43%   |
| Samsung SSD 860 EVO 250GB                            | 32        | 0.42%   |
| Crucial CT240BX500SSD1 240GB                         | 32        | 0.42%   |
| Seagate Expansion 1TB                                | 31        | 0.41%   |
| Samsung SSD 860 EVO 1TB                              | 31        | 0.41%   |
| SK hynix NVMe SSD Drive 256GB                        | 30        | 0.39%   |
| WDC WD10SPZX-21Z10T0 1TB                             | 29        | 0.38%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 960GB | 29        | 0.38%   |
| Crucial CT1000MX500SSD1 1TB                          | 29        | 0.38%   |
| Samsung SSD 970 EVO Plus 1TB                         | 28        | 0.37%   |
| HGST HTS541010A9E680 1TB                             | 28        | 0.37%   |
| Samsung MZVLB512HBJQ-000L7 512GB                     | 26        | 0.34%   |
| WDC WD10SPZX-24Z10 1TB                               | 25        | 0.33%   |
| Samsung MZVLB1T0HBLR-000L7 1TB                       | 25        | 0.33%   |
| Crucial CT500MX500SSD1 500GB                         | 25        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 541       | 710    | 36.9%   |
| WDC                 | 376       | 484    | 25.65%  |
| Toshiba             | 242       | 292    | 16.51%  |
| HGST                | 150       | 214    | 10.23%  |
| Hitachi             | 77        | 89     | 5.25%   |
| Unknown             | 20        | 28     | 1.36%   |
| Samsung Electronics | 13        | 16     | 0.89%   |
| Fujitsu             | 10        | 10     | 0.68%   |
| SABRENT             | 9         | 9      | 0.61%   |
| JMicron Technology  | 8         | 10     | 0.55%   |
| Apple               | 7         | 8      | 0.48%   |
| USB3.0              | 2         | 2      | 0.14%   |
| LIO-ORG             | 2         | 8      | 0.14%   |
| HGST HTS            | 2         | 2      | 0.14%   |
| External            | 2         | 2      | 0.14%   |
| Phison              | 1         | 2      | 0.07%   |
| LaCie               | 1         | 2      | 0.07%   |
| Intenso             | 1         | 1      | 0.07%   |
| IB-AC703            | 1         | 1      | 0.07%   |
| ASMT                | 1         | 1      | 0.07%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 574       | 825    | 25.35%  |
| Kingston            | 250       | 307    | 11.04%  |
| SanDisk             | 241       | 336    | 10.64%  |
| Crucial             | 199       | 262    | 8.79%   |
| WDC                 | 118       | 154    | 5.21%   |
| Intel               | 87        | 137    | 3.84%   |
| Micron Technology   | 76        | 94     | 3.36%   |
| A-DATA Technology   | 71        | 84     | 3.14%   |
| SK hynix            | 62        | 76     | 2.74%   |
| Apple               | 58        | 65     | 2.56%   |
| LITEON              | 57        | 62     | 2.52%   |
| Toshiba             | 47        | 60     | 2.08%   |
| China               | 44        | 50     | 1.94%   |
| PNY                 | 32        | 41     | 1.41%   |
| Transcend           | 30        | 43     | 1.33%   |
| LITEONIT            | 25        | 31     | 1.1%    |
| SPCC                | 24        | 32     | 1.06%   |
| Patriot             | 15        | 19     | 0.66%   |
| OCZ                 | 14        | 16     | 0.62%   |
| Intenso             | 12        | 14     | 0.53%   |
| Corsair             | 12        | 14     | 0.53%   |
| KingSpec            | 11        | 12     | 0.49%   |
| Gigabyte Technology | 11        | 13     | 0.49%   |
| GOODRAM             | 10        | 14     | 0.44%   |
| Team                | 9         | 12     | 0.4%    |
| Seagate             | 9         | 9      | 0.4%    |
| Netac               | 9         | 11     | 0.4%    |
| Lexar               | 8         | 16     | 0.35%   |
| Apacer              | 8         | 9      | 0.35%   |
| Unknown             | 6         | 6      | 0.27%   |
| Hewlett-Packard     | 6         | 6      | 0.27%   |
| Plextor             | 5         | 6      | 0.22%   |
| FORESEE             | 5         | 5      | 0.22%   |
| TO Exter            | 4         | 4      | 0.18%   |
| Mushkin             | 4         | 11     | 0.18%   |
| Dogfish             | 4         | 4      | 0.18%   |
| BIWIN               | 4         | 5      | 0.18%   |
| Unknown             | 4         | 5      | 0.18%   |
| Vaseky              | 3         | 4      | 0.13%   |
| Teclast             | 3         | 4      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 2898      | 4057   | 42.34%  |
| SSD     | 2098      | 2990   | 30.65%  |
| HDD     | 1413      | 1891   | 20.64%  |
| MMC     | 352       | 471    | 5.14%   |
| Unknown | 84        | 94     | 1.23%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3065      | 4672   | 46.8%   |
| NVMe | 2897      | 4051   | 44.24%  |
| MMC  | 352       | 471    | 5.37%   |
| SAS  | 235       | 309    | 3.59%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2174      | 3074   | 62.04%  |
| 0.51-1.0   | 1184      | 1589   | 33.79%  |
| 1.01-2.0   | 122       | 193    | 3.48%   |
| 4.01-10.0  | 18        | 18     | 0.51%   |
| 3.01-4.0   | 4         | 4      | 0.11%   |
| 2.01-3.0   | 1         | 1      | 0.03%   |
| 0          | 1         | 2      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 1328      | 22.17%  |
| 501-1000       | 1254      | 20.93%  |
| 101-250        | 1134      | 18.93%  |
| 1-20           | 637       | 10.63%  |
| 1001-2000      | 610       | 10.18%  |
| Unknown        | 423       | 7.06%   |
| 51-100         | 244       | 4.07%   |
| 21-50          | 137       | 2.29%   |
| More than 3000 | 113       | 1.89%   |
| 2001-3000      | 110       | 1.84%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1844      | 29.32%  |
| 21-50          | 1110      | 17.65%  |
| 101-250        | 1008      | 16.03%  |
| 51-100         | 840       | 13.35%  |
| 251-500        | 590       | 9.38%   |
| Unknown        | 423       | 6.72%   |
| 501-1000       | 338       | 5.37%   |
| 1001-2000      | 106       | 1.69%   |
| More than 3000 | 17        | 0.27%   |
| 2001-3000      | 13        | 0.21%   |
| 0              | 1         | 0.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB                | 10        | 10     | 3.76%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 9         | 19     | 3.38%   |
| Seagate ST1000LM035-1RK172 1TB                 | 7         | 7      | 2.63%   |
| Toshiba MQ01ABD100 1TB                         | 6         | 6      | 2.26%   |
| Seagate ST9500325AS 500GB                      | 6         | 8      | 2.26%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 6         | 6      | 2.26%   |
| HGST HTS545050A7E680 500GB                     | 6         | 6      | 2.26%   |
| HGST HTS541010A9E680 1TB                       | 6         | 6      | 2.26%   |
| HGST HTS721010A9E630 1TB                       | 5         | 7      | 1.88%   |
| Toshiba MQ01ABD075 752GB                       | 4         | 4      | 1.5%    |
| Hitachi HTS547575A9E384 752GB                  | 4         | 6      | 1.5%    |
| Seagate ST9320325AS 320GB                      | 3         | 3      | 1.13%   |
| Seagate ST500LM021-1KJ152 500GB                | 3         | 4      | 1.13%   |
| Samsung Electronics SSD 870 EVO 500GB          | 3         | 6      | 1.13%   |
| Hitachi HTS545050B9A300 500GB                  | 3         | 3      | 1.13%   |
| Crucial CT1000P1SSD8 1TB                       | 3         | 3      | 1.13%   |
| WDC WD10SPZX-24Z10 1TB                         | 2         | 2      | 0.75%   |
| Toshiba MQ01ACF050 500GB                       | 2         | 2      | 0.75%   |
| Toshiba MQ01ABD050V 500GB                      | 2         | 2      | 0.75%   |
| Toshiba MK5061GSY 500GB                        | 2         | 2      | 0.75%   |
| Toshiba MK3275GSX 320GB                        | 2         | 3      | 0.75%   |
| SPCC Solid State Disk 256GB                    | 2         | 2      | 0.75%   |
| SK hynix SC308 SATA 128GB SSD                  | 2         | 2      | 0.75%   |
| SK hynix HFS256G39TND-N210A 256GB SSD          | 2         | 2      | 0.75%   |
| SK hynix HFS128G39TND-N210A 128GB SSD          | 2         | 2      | 0.75%   |
| Seagate ST9500420AS 500GB                      | 2         | 3      | 0.75%   |
| Seagate ST500LM012 HN-M500MBB 500GB            | 2         | 2      | 0.75%   |
| Seagate ST500LM000-SSHD-8GB                    | 2         | 3      | 0.75%   |
| Seagate ST1000LM014-1EJ164 1TB                 | 2         | 2      | 0.75%   |
| SanDisk SSD PLUS 240GB                         | 2         | 2      | 0.75%   |
| SanDisk SD6PP4M-256G-1006 256GB SSD            | 2         | 2      | 0.75%   |
| LITEON CV8-8E128-HP 128GB SSD                  | 2         | 2      | 0.75%   |
| Kingston SV300S37A480G 480GB SSD               | 2         | 2      | 0.75%   |
| Intel SSDSC2BF180A5L 180GB                     | 2         | 2      | 0.75%   |
| Hitachi HTS545032B9A300 320GB                  | 2         | 2      | 0.75%   |
| Hitachi HTS545025B9SA02 250GB                  | 2         | 3      | 0.75%   |
| HGST HTS725050A7E630 500GB                     | 2         | 2      | 0.75%   |
| HGST HTS541075A9E680 752GB                     | 2         | 2      | 0.75%   |
| Fujitsu MHY2120BH 120GB                        | 2         | 2      | 0.75%   |
| Crucial CT1050MX300SSD1 1050GB                 | 2         | 8      | 0.75%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 57        | 74     | 21.51%  |
| Toshiba             | 28        | 29     | 10.57%  |
| WDC                 | 27        | 30     | 10.19%  |
| HGST                | 23        | 25     | 8.68%   |
| Samsung Electronics | 22        | 27     | 8.3%    |
| Hitachi             | 19        | 22     | 7.17%   |
| Micron Technology   | 12        | 15     | 4.53%   |
| Intel               | 12        | 23     | 4.53%   |
| SK hynix            | 11        | 12     | 4.15%   |
| SanDisk             | 10        | 12     | 3.77%   |
| Crucial             | 10        | 16     | 3.77%   |
| Kingston            | 6         | 6      | 2.26%   |
| A-DATA Technology   | 5         | 5      | 1.89%   |
| LITEON              | 4         | 4      | 1.51%   |
| Fujitsu             | 3         | 3      | 1.13%   |
| SPCC                | 2         | 2      | 0.75%   |
| LITEONIT            | 2         | 3      | 0.75%   |
| walram              | 1         | 1      | 0.38%   |
| Union Memory        | 1         | 1      | 0.38%   |
| Teclast             | 1         | 1      | 0.38%   |
| SSD                 | 1         | 1      | 0.38%   |
| PNY                 | 1         | 1      | 0.38%   |
| Plextor             | 1         | 1      | 0.38%   |
| Origin              | 1         | 1      | 0.38%   |
| OCZ-VERTEX3         | 1         | 1      | 0.38%   |
| Lenovo              | 1         | 2      | 0.38%   |
| HGST HTS            | 1         | 1      | 0.38%   |
| China               | 1         | 1      | 0.38%   |
| Unknown             | 1         | 1      | 0.38%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 57        | 74     | 35.85%  |
| Toshiba             | 27        | 28     | 16.98%  |
| WDC                 | 26        | 29     | 16.35%  |
| HGST                | 23        | 25     | 14.47%  |
| Hitachi             | 19        | 22     | 11.95%  |
| Samsung Electronics | 3         | 3      | 1.89%   |
| Fujitsu             | 3         | 3      | 1.89%   |
| HGST HTS            | 1         | 1      | 0.63%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 158       | 185    | 60.08%  |
| SSD  | 85        | 113    | 32.32%  |
| NVMe | 20        | 23     | 7.6%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC PC SN520 SDAPMUW-512G-1001 512GB             | 1         | 1      | 14.29%  |
| Toshiba THNSN5512GPUK NVMe 512GB                 | 1         | 1      | 14.29%  |
| Seagate ST1000LM035-1RK172 1TB                   | 1         | 1      | 14.29%  |
| Samsung Electronics SSD 980 500GB                | 1         | 1      | 14.29%  |
| Samsung Electronics SSD 980 1TB                  | 1         | 1      | 14.29%  |
| Samsung Electronics MZNTY128HDHP-00000 128GB SSD | 1         | 1      | 14.29%  |
| HGST HTS721010A9E630 1TB                         | 1         | 1      | 14.29%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 42.86%  |
| WDC                 | 1         | 1      | 14.29%  |
| Toshiba             | 1         | 1      | 14.29%  |
| Seagate             | 1         | 1      | 14.29%  |
| HGST                | 1         | 1      | 14.29%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 3242      | 5415   | 52.84%  |
| Works    | 2630      | 3760   | 42.86%  |
| Malfunc  | 257       | 321    | 4.19%   |
| Failed   | 7         | 7      | 0.11%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 3570      | 50.25%  |
| Samsung Electronics                     | 1022      | 14.38%  |
| AMD                                     | 601       | 8.46%   |
| SanDisk                                 | 509       | 7.16%   |
| SK hynix                                | 356       | 5.01%   |
| Toshiba America Info Systems            | 228       | 3.21%   |
| Micron Technology                       | 148       | 2.08%   |
| KIOXIA                                  | 109       | 1.53%   |
| Kingston Technology Company             | 107       | 1.51%   |
| Phison Electronics                      | 77        | 1.08%   |
| ADATA Technology                        | 70        | 0.99%   |
| Silicon Motion                          | 54        | 0.76%   |
| Micron/Crucial Technology               | 43        | 0.61%   |
| Union Memory (Shenzhen)                 | 29        | 0.41%   |
| Lite-On Technology                      | 28        | 0.39%   |
| Realtek Semiconductor                   | 23        | 0.32%   |
| Nvidia                                  | 23        | 0.32%   |
| Solid State Storage Technology          | 22        | 0.31%   |
| Lenovo                                  | 21        | 0.3%    |
| Apple                                   | 17        | 0.24%   |
| Seagate Technology                      | 9         | 0.13%   |
| Yangtze Memory Technologies             | 7         | 0.1%    |
| Marvell Technology Group                | 6         | 0.08%   |
| Shenzhen Longsys Electronics            | 5         | 0.07%   |
| JMicron Technology                      | 4         | 0.06%   |
| Biwin Storage Technology                | 3         | 0.04%   |
| Silicon Integrated Systems [SiS]        | 2         | 0.03%   |
| ULi Electronics                         | 1         | 0.01%   |
| Transcend                               | 1         | 0.01%   |
| Shenzhen Unionmemory Information System | 1         | 0.01%   |
| OCZ Technology Group                    | 1         | 0.01%   |
| Netac Technology                        | 1         | 0.01%   |
| MAXIO Technology (Hangzhou)             | 1         | 0.01%   |
| Lite-On IT Corp. / Plextor              | 1         | 0.01%   |
| INNOGRIT                                | 1         | 0.01%   |
| Enmotus                                 | 1         | 0.01%   |
| Beijing Starblaze Technology            | 1         | 0.01%   |
| ASMedia Technology                      | 1         | 0.01%   |
| Unknown                                 | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 589       | 7.94%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 570       | 7.68%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 530       | 7.14%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 354       | 4.77%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 353       | 4.76%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 232       | 3.13%   |
| Intel Volume Management Device NVMe RAID Controller                            | 221       | 2.98%   |
| Samsung NVMe SSD Controller 980                                                | 213       | 2.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 212       | 2.86%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 198       | 2.67%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 175       | 2.36%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 164       | 2.21%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 152       | 2.05%   |
| Micron Non-Volatile memory controller                                          | 148       | 1.99%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 145       | 1.95%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 128       | 1.72%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 124       | 1.67%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 102       | 1.37%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 98        | 1.32%   |
| Intel Comet Lake SATA AHCI Controller                                          | 97        | 1.31%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 96        | 1.29%   |
| Intel Tiger Lake-LP SATA Controller                                            | 95        | 1.28%   |
| SanDisk Non-Volatile memory controller                                         | 90        | 1.21%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 88        | 1.19%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 84        | 1.13%   |
| Intel SSD 660P Series                                                          | 82        | 1.1%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 68        | 0.92%   |
| SK hynix Non-Volatile memory controller                                        | 65        | 0.88%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 64        | 0.86%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 62        | 0.84%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 62        | 0.84%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 61        | 0.82%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 60        | 0.81%   |
| Intel Non-Volatile memory controller                                           | 57        | 0.77%   |
| SK hynix BC511                                                                 | 54        | 0.73%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 54        | 0.73%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 53        | 0.71%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 50        | 0.67%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 49        | 0.66%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 49        | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 3575      | 49.91%  |
| NVMe | 2903      | 40.53%  |
| RAID | 587       | 8.19%   |
| IDE  | 98        | 1.37%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 4629      | 81.13%  |
| AMD     | 1072      | 18.79%  |
| ARM     | 3         | 0.05%   |
| Unknown | 2         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 150       | 2.63%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 128       | 2.24%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 123       | 2.16%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 119       | 2.09%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 106       | 1.86%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 100       | 1.75%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 99        | 1.73%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 97        | 1.7%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 97        | 1.7%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 96        | 1.68%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 89        | 1.56%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 86        | 1.51%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 86        | 1.51%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 81        | 1.42%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 81        | 1.42%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 70        | 1.23%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 64        | 1.12%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 62        | 1.09%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 59        | 1.03%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 58        | 1.02%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 57        | 1%      |
| Intel Core i5-2520M CPU @ 2.50GHz             | 57        | 1%      |
| AMD Ryzen 5 5500U with Radeon Graphics        | 57        | 1%      |
| Intel Core i5-6300U CPU @ 2.40GHz             | 50        | 0.88%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 48        | 0.84%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 47        | 0.82%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 44        | 0.77%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 44        | 0.77%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 42        | 0.74%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 41        | 0.72%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 39        | 0.68%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 38        | 0.67%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 38        | 0.67%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 36        | 0.63%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 36        | 0.63%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 36        | 0.63%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 35        | 0.61%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 33        | 0.58%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 33        | 0.58%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 33        | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 1765      | 30.93%  |
| Intel Core i5                  | 1460      | 25.59%  |
| Other                          | 554       | 9.71%   |
| Intel Core i3                  | 346       | 6.06%   |
| AMD Ryzen 5                    | 330       | 5.78%   |
| AMD Ryzen 7                    | 309       | 5.42%   |
| Intel Celeron                  | 131       | 2.3%    |
| Intel Core 2 Duo               | 94        | 1.65%   |
| Intel Atom                     | 87        | 1.52%   |
| AMD Ryzen 7 PRO                | 78        | 1.37%   |
| AMD Ryzen 9                    | 76        | 1.33%   |
| Intel Pentium                  | 68        | 1.19%   |
| Intel Core i9                  | 54        | 0.95%   |
| AMD Ryzen 3                    | 46        | 0.81%   |
| AMD Ryzen 5 PRO                | 44        | 0.77%   |
| AMD A6                         | 34        | 0.6%    |
| AMD A10                        | 28        | 0.49%   |
| AMD A8                         | 24        | 0.42%   |
| Intel Pentium Silver           | 20        | 0.35%   |
| AMD A4                         | 20        | 0.35%   |
| Intel Xeon                     | 14        | 0.25%   |
| Intel Pentium Dual-Core        | 14        | 0.25%   |
| AMD E1                         | 11        | 0.19%   |
| AMD Athlon                     | 9         | 0.16%   |
| AMD A12                        | 9         | 0.16%   |
| AMD E                          | 8         | 0.14%   |
| Intel Core m3                  | 7         | 0.12%   |
| Intel Pentium Dual             | 6         | 0.11%   |
| Intel Genuine                  | 6         | 0.11%   |
| Intel Core m5                  | 6         | 0.11%   |
| Intel Core M                   | 5         | 0.09%   |
| Intel Core m7                  | 4         | 0.07%   |
| AMD PRO A10                    | 4         | 0.07%   |
| AMD Phenom II                  | 4         | 0.07%   |
| AMD E2                         | 4         | 0.07%   |
| AMD Turion X2 Dual-Core Mobile | 3         | 0.05%   |
| AMD Athlon II                  | 3         | 0.05%   |
| Intel Core 2                   | 2         | 0.04%   |
| Intel Celeron Dual-Core        | 2         | 0.04%   |
| AMD Turion 64 X2 Mobile        | 2         | 0.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 4       | 2352      | 41.21%  |
| 2       | 2129      | 37.3%   |
| 6       | 563       | 9.86%   |
| 8       | 525       | 9.2%    |
| 14      | 46        | 0.81%   |
| 12      | 40        | 0.7%    |
| 10      | 26        | 0.46%   |
| 1       | 20        | 0.35%   |
| 16      | 3         | 0.05%   |
| 3       | 2         | 0.04%   |
| 5       | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 5705      | 99.96%  |
| 2       | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 5004      | 87.56%  |
| 1       | 710       | 12.42%  |
| Unknown | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 5569      | 97.24%  |
| Unknown        | 151       | 2.64%   |
| 32-bit         | 4         | 0.07%   |
| 64-bit         | 3         | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806ec    | 387       | 6.66%   |
| 0x806ea    | 370       | 6.37%   |
| 0x306a9    | 351       | 6.04%   |
| Unknown    | 340       | 5.86%   |
| 0x806c1    | 325       | 5.6%    |
| 0x206a7    | 273       | 4.7%    |
| 0x906ea    | 265       | 4.56%   |
| 0x806e9    | 264       | 4.55%   |
| 0x406e3    | 263       | 4.53%   |
| 0x40651    | 218       | 3.75%   |
| 0x306d4    | 208       | 3.58%   |
| 0x306c3    | 165       | 2.84%   |
| 0xa0652    | 157       | 2.7%    |
| 0x0a50000c | 153       | 2.63%   |
| 0x08600106 | 117       | 2.01%   |
| 0x906e9    | 116       | 2%      |
| 0x506e3    | 109       | 1.88%   |
| 0x08108102 | 107       | 1.84%   |
| 0x706e5    | 101       | 1.74%   |
| 0x08108109 | 101       | 1.74%   |
| 0x906a3    | 81        | 1.39%   |
| 0x20655    | 81        | 1.39%   |
| 0x806eb    | 73        | 1.26%   |
| 0x30678    | 69        | 1.19%   |
| 0x1067a    | 69        | 1.19%   |
| 0x08608103 | 69        | 1.19%   |
| 0x08600104 | 69        | 1.19%   |
| 0x806d1    | 57        | 0.98%   |
| 0x906ed    | 55        | 0.95%   |
| 0x08600103 | 48        | 0.83%   |
| 0x406c4    | 39        | 0.67%   |
| 0x706a8    | 34        | 0.59%   |
| 0x0810100b | 34        | 0.59%   |
| 0x406c3    | 30        | 0.52%   |
| 0x0a404102 | 30        | 0.52%   |
| 0x506c9    | 28        | 0.48%   |
| 0x20652    | 27        | 0.46%   |
| 0x08608102 | 27        | 0.46%   |
| 0x10676    | 26        | 0.45%   |
| 0x0a404101 | 26        | 0.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 1621      | 28.39%  |
| Haswell          | 424       | 7.43%   |
| Skylake          | 394       | 6.9%    |
| IvyBridge        | 363       | 6.36%   |
| TigerLake        | 361       | 6.32%   |
| SandyBridge      | 283       | 4.96%   |
| Zen 2            | 273       | 4.78%   |
| Zen+             | 216       | 3.78%   |
| Broadwell        | 210       | 3.68%   |
| Zen 3            | 186       | 3.26%   |
| CometLake        | 177       | 3.1%    |
| Unknown          | 173       | 3.03%   |
| IceLake          | 166       | 2.91%   |
| Silvermont       | 151       | 2.64%   |
| Westmere         | 113       | 1.98%   |
| Alderlake Hybrid | 110       | 1.93%   |
| Penryn           | 98        | 1.72%   |
| Zen              | 65        | 1.14%   |
| Goldmont plus    | 58        | 1.02%   |
| Excavator        | 54        | 0.95%   |
| Puma             | 29        | 0.51%   |
| Goldmont         | 29        | 0.51%   |
| Core             | 26        | 0.46%   |
| Piledriver       | 23        | 0.4%    |
| Jaguar           | 19        | 0.33%   |
| Nehalem          | 17        | 0.3%    |
| Bobcat           | 15        | 0.26%   |
| Tremont          | 11        | 0.19%   |
| K10              | 10        | 0.18%   |
| K10 Llano        | 9         | 0.16%   |
| Steamroller      | 7         | 0.12%   |
| K8 & K10 hybrid  | 5         | 0.09%   |
| Bonnell          | 5         | 0.09%   |
| K8 Hammer        | 4         | 0.07%   |
| P6               | 3         | 0.05%   |
| NetBurst         | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 4361      | 57.79%  |
| Nvidia                           | 1823      | 24.16%  |
| AMD                              | 1361      | 18.04%  |
| Silicon Integrated Systems [SiS] | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 384       | 5%      |
| Intel 3rd Gen Core processor Graphics Controller                                         | 336       | 4.37%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 330       | 4.3%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 286       | 3.72%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 265       | 3.45%   |
| Intel HD Graphics 620                                                                    | 265       | 3.45%   |
| AMD Renoir                                                                               | 265       | 3.45%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 249       | 3.24%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 240       | 3.12%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 221       | 2.88%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 217       | 2.82%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 213       | 2.77%   |
| Intel HD Graphics 5500                                                                   | 184       | 2.39%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 166       | 2.16%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 160       | 2.08%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 148       | 1.93%   |
| Intel HD Graphics 630                                                                    | 109       | 1.42%   |
| Intel HD Graphics 530                                                                    | 99        | 1.29%   |
| AMD Lucienne                                                                             | 99        | 1.29%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 90        | 1.17%   |
| Intel Core Processor Integrated Graphics Controller                                      | 87        | 1.13%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 83        | 1.08%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 82        | 1.07%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 81        | 1.05%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 78        | 1.02%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 78        | 1.02%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 75        | 0.98%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 69        | 0.9%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 67        | 0.87%   |
| Nvidia GP108M [GeForce MX150]                                                            | 65        | 0.85%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 59        | 0.77%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 57        | 0.74%   |
| AMD Rembrandt [Radeon 680M]                                                              | 57        | 0.74%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 53        | 0.69%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 53        | 0.69%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 51        | 0.66%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 46        | 0.6%    |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 44        | 0.57%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 44        | 0.57%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 43        | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 2711      | 47.35%  |
| Intel + Nvidia     | 1414      | 24.7%   |
| 1 x AMD            | 841       | 14.69%  |
| Intel + AMD        | 231       | 4.03%   |
| 1 x Nvidia         | 223       | 3.9%    |
| AMD + Nvidia       | 185       | 3.23%   |
| 2 x AMD            | 104       | 1.82%   |
| Other              | 7         | 0.12%   |
| 2 x Intel          | 4         | 0.07%   |
| 2 x Nvidia         | 2         | 0.03%   |
| Intel + 2 x Nvidia | 2         | 0.03%   |
| 1 x SiS            | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 4896      | 84.81%  |
| Proprietary | 802       | 13.89%  |
| Unknown     | 75        | 1.3%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 3555      | 61.09%  |
| 1.01-2.0   | 795       | 13.66%  |
| 0.01-0.5   | 595       | 10.23%  |
| 3.01-4.0   | 380       | 6.53%   |
| 0.51-1.0   | 313       | 5.38%   |
| 5.01-6.0   | 73        | 1.25%   |
| 7.01-8.0   | 69        | 1.19%   |
| 2.01-3.0   | 23        | 0.4%    |
| 8.01-16.0  | 16        | 0.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 1259      | 17.75%  |
| BOE                     | 1011      | 14.26%  |
| LG Display              | 950       | 13.4%   |
| Chimei Innolux          | 937       | 13.21%  |
| Samsung Electronics     | 549       | 7.74%   |
| Dell                    | 338       | 4.77%   |
| Sharp                   | 309       | 4.36%   |
| Goldstar                | 222       | 3.13%   |
| Lenovo                  | 149       | 2.1%    |
| Apple                   | 145       | 2.04%   |
| PANDA                   | 132       | 1.86%   |
| Hewlett-Packard         | 120       | 1.69%   |
| Acer                    | 79        | 1.11%   |
| CSO                     | 78        | 1.1%    |
| BenQ                    | 77        | 1.09%   |
| Philips                 | 75        | 1.06%   |
| Chi Mei Optoelectronics | 73        | 1.03%   |
| AOC                     | 73        | 1.03%   |
| InfoVision              | 62        | 0.87%   |
| Ancor Communications    | 55        | 0.78%   |
| ViewSonic               | 32        | 0.45%   |
| Iiyama                  | 31        | 0.44%   |
| TMX                     | 25        | 0.35%   |
| ASUSTek Computer        | 25        | 0.35%   |
| Panasonic               | 19        | 0.27%   |
| JDI                     | 19        | 0.27%   |
| Sony                    | 18        | 0.25%   |
| Toshiba                 | 14        | 0.2%    |
| Sceptre Tech            | 10        | 0.14%   |
| MSI                     | 10        | 0.14%   |
| LG Philips              | 9         | 0.13%   |
| CPT                     | 9         | 0.13%   |
| HannStar                | 8         | 0.11%   |
| Eizo                    | 8         | 0.11%   |
| Vizio                   | 7         | 0.1%    |
| Vestel Elektronik       | 6         | 0.08%   |
| NEC Computers           | 6         | 0.08%   |
| Gigabyte Technology     | 6         | 0.08%   |
| Fujitsu Siemens         | 6         | 0.08%   |
| Tianma XM               | 5         | 0.07%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 62        | 0.86%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 51        | 0.71%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 49        | 0.68%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 45        | 0.62%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 42        | 0.58%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 38        | 0.53%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch        | 38        | 0.53%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch        | 37        | 0.51%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 34        | 0.47%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 33        | 0.46%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 32        | 0.44%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 32        | 0.44%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 31        | 0.43%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 30        | 0.42%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 28        | 0.39%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch  | 27        | 0.37%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 25        | 0.35%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 25        | 0.35%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 24        | 0.33%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch              | 24        | 0.33%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 23        | 0.32%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 22        | 0.31%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 22        | 0.31%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch        | 22        | 0.31%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 21        | 0.29%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 21        | 0.29%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 21        | 0.29%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch        | 21        | 0.29%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch        | 21        | 0.29%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 20        | 0.28%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 20        | 0.28%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 19        | 0.26%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 19        | 0.26%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 19        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 19        | 0.26%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                 | 19        | 0.26%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                 | 18        | 0.25%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 18        | 0.25%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 17        | 0.24%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 17        | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 3320      | 51.15%  |
| 1366x768 (WXGA)    | 1284      | 19.78%  |
| 3840x2160 (4K)     | 383       | 5.9%    |
| 2560x1440 (QHD)    | 273       | 4.21%   |
| 1600x900 (HD+)     | 233       | 3.59%   |
| 1920x1200 (WUXGA)  | 186       | 2.87%   |
| 2560x1600          | 111       | 1.71%   |
| 1280x800 (WXGA)    | 94        | 1.45%   |
| 2880x1800          | 80        | 1.23%   |
| 2560x1080          | 64        | 0.99%   |
| 1440x900 (WXGA+)   | 57        | 0.88%   |
| 3440x1440          | 52        | 0.8%    |
| 3840x2400          | 41        | 0.63%   |
| 1680x1050 (WSXGA+) | 38        | 0.59%   |
| 2160x1440          | 37        | 0.57%   |
| 1280x1024 (SXGA)   | 33        | 0.51%   |
| 3200x1800 (QHD+)   | 31        | 0.48%   |
| 2256x1504          | 31        | 0.48%   |
| 3000x2000          | 18        | 0.28%   |
| 1360x768           | 18        | 0.28%   |
| 3456x2160          | 9         | 0.14%   |
| 3200x2000          | 9         | 0.14%   |
| 2240x1400          | 9         | 0.14%   |
| 3072x1920          | 8         | 0.12%   |
| 2520x1680          | 7         | 0.11%   |
| 2160x1350          | 6         | 0.09%   |
| 3840x1600          | 5         | 0.08%   |
| 3840x1080          | 5         | 0.08%   |
| 1920x540           | 5         | 0.08%   |
| 1920x1280          | 5         | 0.08%   |
| 1024x768 (XGA)     | 5         | 0.08%   |
| 1024x600           | 5         | 0.08%   |
| Unknown            | 3         | 0.05%   |
| 2880x1920          | 2         | 0.03%   |
| 2736x1824          | 2         | 0.03%   |
| 1920x515           | 2         | 0.03%   |
| 1680x945           | 2         | 0.03%   |
| 1600x1200          | 2         | 0.03%   |
| 9360x2160          | 1         | 0.02%   |
| 800x1280           | 1         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 2636      | 37.13%  |
| 13      | 1154      | 16.26%  |
| 14      | 993       | 13.99%  |
| 17      | 360       | 5.07%   |
| 27      | 348       | 4.9%    |
| 24      | 326       | 4.59%   |
| 23      | 233       | 3.28%   |
| 12      | 187       | 2.63%   |
| 21      | 163       | 2.3%    |
| 34      | 100       | 1.41%   |
| 16      | 89        | 1.25%   |
| 31      | 74        | 1.04%   |
| 18      | 66        | 0.93%   |
| 11      | 63        | 0.89%   |
| 19      | 35        | 0.49%   |
| 20      | 33        | 0.46%   |
| 22      | 26        | 0.37%   |
| Unknown | 24        | 0.34%   |
| 25      | 21        | 0.3%    |
| 40      | 20        | 0.28%   |
| 84      | 17        | 0.24%   |
| 32      | 15        | 0.21%   |
| 29      | 12        | 0.17%   |
| 35      | 11        | 0.15%   |
| 26      | 11        | 0.15%   |
| 10      | 11        | 0.15%   |
| 72      | 8         | 0.11%   |
| 54      | 8         | 0.11%   |
| 48      | 6         | 0.08%   |
| 37      | 6         | 0.08%   |
| 28      | 6         | 0.08%   |
| 39      | 5         | 0.07%   |
| 57      | 3         | 0.04%   |
| 33      | 3         | 0.04%   |
| 74      | 2         | 0.03%   |
| 69      | 2         | 0.03%   |
| 63      | 2         | 0.03%   |
| 58      | 2         | 0.03%   |
| 52      | 2         | 0.03%   |
| 47      | 2         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 4265      | 60.76%  |
| 501-600     | 837       | 11.92%  |
| 201-300     | 797       | 11.35%  |
| 351-400     | 435       | 6.2%    |
| 401-500     | 304       | 4.33%   |
| 601-700     | 129       | 1.84%   |
| 701-800     | 118       | 1.68%   |
| 801-900     | 44        | 0.63%   |
| 1001-1500   | 30        | 0.43%   |
| 1501-2000   | 29        | 0.41%   |
| Unknown     | 24        | 0.34%   |
| 901-1000    | 5         | 0.07%   |
| 101-200     | 1         | 0.01%   |
| 1-100       | 1         | 0.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 4993      | 83.61%  |
| 16/10   | 669       | 11.2%   |
| 21/9    | 122       | 2.04%   |
| 3/2     | 113       | 1.89%   |
| 5/4     | 31        | 0.52%   |
| 4/3     | 15        | 0.25%   |
| Unknown | 10        | 0.17%   |
| 32/9    | 9         | 0.15%   |
| 6/5     | 2         | 0.03%   |
| 3.88    | 1         | 0.02%   |
| 3.73    | 1         | 0.02%   |
| 3.40    | 1         | 0.02%   |
| 3.33    | 1         | 0.02%   |
| 0.89    | 1         | 0.02%   |
| 0.67    | 1         | 0.02%   |
| 0.62    | 1         | 0.02%   |
| 0.56    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 2640      | 37.27%  |
| 81-90          | 1708      | 24.11%  |
| 201-250        | 591       | 8.34%   |
| 71-80          | 432       | 6.1%    |
| 301-350        | 358       | 5.05%   |
| 121-130        | 328       | 4.63%   |
| 351-500        | 214       | 3.02%   |
| 61-70          | 179       | 2.53%   |
| 251-300        | 136       | 1.92%   |
| 151-200        | 105       | 1.48%   |
| 111-120        | 81        | 1.14%   |
| 141-150        | 69        | 0.97%   |
| 51-60          | 64        | 0.9%    |
| More than 1000 | 50        | 0.71%   |
| 501-1000       | 47        | 0.66%   |
| 131-140        | 27        | 0.38%   |
| Unknown        | 24        | 0.34%   |
| 91-100         | 16        | 0.23%   |
| 41-50          | 11        | 0.16%   |
| 1-40           | 3         | 0.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 3134      | 45.37%  |
| 101-120       | 1523      | 22.05%  |
| 51-100        | 1097      | 15.88%  |
| 161-240       | 720       | 10.42%  |
| More than 240 | 370       | 5.36%   |
| 1-50          | 40        | 0.58%   |
| Unknown       | 24        | 0.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 4324      | 73.13%  |
| 2     | 1288      | 21.78%  |
| 3     | 166       | 2.81%   |
| 0     | 119       | 2.01%   |
| 4     | 14        | 0.24%   |
| 5     | 2         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 3494      | 40.32%  |
| Realtek Semiconductor             | 2814      | 32.47%  |
| Qualcomm Atheros                  | 1025      | 11.83%  |
| Broadcom                          | 364       | 4.2%    |
| MediaTek                          | 170       | 1.96%   |
| Broadcom Limited                  | 85        | 0.98%   |
| Lenovo                            | 79        | 0.91%   |
| Sierra Wireless                   | 57        | 0.66%   |
| TP-Link                           | 55        | 0.63%   |
| ASIX Electronics                  | 53        | 0.61%   |
| Ralink                            | 39        | 0.45%   |
| Dell                              | 37        | 0.43%   |
| DisplayLink                       | 35        | 0.4%    |
| Qualcomm                          | 33        | 0.38%   |
| Marvell Technology Group          | 33        | 0.38%   |
| Ericsson Business Mobile Networks | 28        | 0.32%   |
| Ralink Technology                 | 27        | 0.31%   |
| Hewlett-Packard                   | 24        | 0.28%   |
| Samsung Electronics               | 21        | 0.24%   |
| Nvidia                            | 17        | 0.2%    |
| Huawei Technologies               | 16        | 0.18%   |
| Xiaomi                            | 15        | 0.17%   |
| ASUSTek Computer                  | 14        | 0.16%   |
| Apple                             | 13        | 0.15%   |
| Fibocom                           | 11        | 0.13%   |
| Google                            | 10        | 0.12%   |
| JMicron Technology                | 9         | 0.1%    |
| NetGear                           | 8         | 0.09%   |
| Qualcomm Atheros Communications   | 6         | 0.07%   |
| Linksys                           | 6         | 0.07%   |
| D-Link                            | 6         | 0.07%   |
| T & A Mobile Phones               | 5         | 0.06%   |
| D-Link System                     | 5         | 0.06%   |
| OPPO                              | 4         | 0.05%   |
| OnePlus Technology (Shenzhen)     | 4         | 0.05%   |
| Motorola PCS                      | 4         | 0.05%   |
| Microsoft                         | 4         | 0.05%   |
| Edimax Technology                 | 4         | 0.05%   |
| Cypress Semiconductor             | 3         | 0.03%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1771      | 16.74%  |
| Intel Wi-Fi 6 AX200                                               | 431       | 4.07%   |
| Intel Wireless 8265 / 8275                                        | 380       | 3.59%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 377       | 3.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 314       | 2.97%   |
| Intel Wi-Fi 6 AX201                                               | 272       | 2.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 243       | 2.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 226       | 2.14%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 222       | 2.1%    |
| Intel Wireless 8260                                               | 216       | 2.04%   |
| Intel Wireless 7260                                               | 196       | 1.85%   |
| Intel Wireless 7265                                               | 184       | 1.74%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 172       | 1.63%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 169       | 1.6%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 165       | 1.56%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 155       | 1.46%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 154       | 1.46%   |
| Intel Ethernet Connection (4) I219-LM                             | 138       | 1.3%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 138       | 1.3%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 137       | 1.29%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 135       | 1.28%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 134       | 1.27%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 121       | 1.14%   |
| Intel Wireless 3165                                               | 101       | 0.95%   |
| Intel Ethernet Connection I219-LM                                 | 89        | 0.84%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 89        | 0.84%   |
| Intel Wireless-AC 9260                                            | 88        | 0.83%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 85        | 0.8%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 84        | 0.79%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 84        | 0.79%   |
| Intel Ethernet Connection (4) I219-V                              | 83        | 0.78%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 75        | 0.71%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 73        | 0.69%   |
| Intel Ethernet Connection I218-LM                                 | 72        | 0.68%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 69        | 0.65%   |
| Intel Centrino Ultimate-N 6300                                    | 69        | 0.65%   |
| Intel Wireless 3160                                               | 64        | 0.6%    |
| Intel Ethernet Connection (6) I219-V                              | 64        | 0.6%    |
| Intel Ethernet Connection (3) I218-LM                             | 60        | 0.57%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 60        | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 3405      | 58.34%  |
| Qualcomm Atheros                  | 899       | 15.4%   |
| Realtek Semiconductor             | 760       | 13.02%  |
| Broadcom                          | 295       | 5.05%   |
| MediaTek                          | 122       | 2.09%   |
| Broadcom Limited                  | 64        | 1.1%    |
| Sierra Wireless                   | 57        | 0.98%   |
| TP-Link                           | 39        | 0.67%   |
| Ralink                            | 39        | 0.67%   |
| Dell                              | 28        | 0.48%   |
| Ralink Technology                 | 27        | 0.46%   |
| Qualcomm                          | 25        | 0.43%   |
| ASUSTek Computer                  | 13        | 0.22%   |
| Fibocom                           | 11        | 0.19%   |
| Ericsson Business Mobile Networks | 8         | 0.14%   |
| NetGear                           | 7         | 0.12%   |
| Qualcomm Atheros Communications   | 6         | 0.1%    |
| Hewlett-Packard                   | 6         | 0.1%    |
| Linksys                           | 5         | 0.09%   |
| D-Link System                     | 5         | 0.09%   |
| Edimax Technology                 | 4         | 0.07%   |
| Microsoft                         | 3         | 0.05%   |
| D-Link                            | 3         | 0.05%   |
| Belkin Components                 | 2         | 0.03%   |
| TRENDnet                          | 1         | 0.02%   |
| Quectel Wireless Solutions        | 1         | 0.02%   |
| IMC Networks                      | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 431       | 7.35%   |
| Intel Wireless 8265 / 8275                                     | 380       | 6.48%   |
| Intel Wi-Fi 6 AX201                                            | 272       | 4.64%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 243       | 4.14%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 222       | 3.78%   |
| Intel Wireless 8260                                            | 216       | 3.68%   |
| Intel Wireless 7260                                            | 196       | 3.34%   |
| Intel Wireless 7265                                            | 184       | 3.14%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 172       | 2.93%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 169       | 2.88%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 165       | 2.81%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 155       | 2.64%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 154       | 2.62%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 138       | 2.35%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 137       | 2.34%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 135       | 2.3%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 134       | 2.28%   |
| Intel Wireless 3165                                            | 101       | 1.72%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 89        | 1.52%   |
| Intel Wireless-AC 9260                                         | 88        | 1.5%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 85        | 1.45%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 84        | 1.43%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 84        | 1.43%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 79        | 1.35%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 75        | 1.28%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 73        | 1.24%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 69        | 1.18%   |
| Intel Centrino Ultimate-N 6300                                 | 69        | 1.18%   |
| Intel Wireless 3160                                            | 64        | 1.09%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 60        | 1.02%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 56        | 0.95%   |
| Broadcom BCM43142 802.11b/g/n                                  | 54        | 0.92%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 43        | 0.73%   |
| Intel Centrino Advanced-N 6235                                 | 41        | 0.7%    |
| Intel Tiger Lake PCH CNVi WiFi                                 | 40        | 0.68%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 34        | 0.58%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 32        | 0.55%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 29        | 0.49%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 29        | 0.49%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 28        | 0.48%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2508      | 54.89%  |
| Intel                                  | 1302      | 28.5%   |
| Qualcomm Atheros                       | 216       | 4.73%   |
| Broadcom                               | 119       | 2.6%    |
| Lenovo                                 | 78        | 1.71%   |
| ASIX Electronics                       | 53        | 1.16%   |
| MediaTek                               | 48        | 1.05%   |
| DisplayLink                            | 35        | 0.77%   |
| Marvell Technology Group               | 33        | 0.72%   |
| Samsung Electronics                    | 21        | 0.46%   |
| Broadcom Limited                       | 21        | 0.46%   |
| TP-Link                                | 18        | 0.39%   |
| Nvidia                                 | 17        | 0.37%   |
| Xiaomi                                 | 15        | 0.33%   |
| Apple                                  | 13        | 0.28%   |
| Google                                 | 10        | 0.22%   |
| JMicron Technology                     | 9         | 0.2%    |
| Qualcomm                               | 8         | 0.18%   |
| Huawei Technologies                    | 8         | 0.18%   |
| Hewlett-Packard                        | 6         | 0.13%   |
| OPPO                                   | 4         | 0.09%   |
| OnePlus Technology (Shenzhen)          | 3         | 0.07%   |
| D-Link                                 | 3         | 0.07%   |
| Cypress Semiconductor                  | 3         | 0.07%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.04%   |
| ICS Advent                             | 2         | 0.04%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.02%   |
| vivo                                   | 1         | 0.02%   |
| T & A Mobile Phones                    | 1         | 0.02%   |
| Spreadtrum Communications              | 1         | 0.02%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.02%   |
| Novatel Wireless                       | 1         | 0.02%   |
| NetGear                                | 1         | 0.02%   |
| Motorola PCS                           | 1         | 0.02%   |
| Microsoft                              | 1         | 0.02%   |
| Linksys                                | 1         | 0.02%   |
| LG Electronics                         | 1         | 0.02%   |
| HMD Global                             | 1         | 0.02%   |
| ASUSTek Computer                       | 1         | 0.02%   |
| Aquantia                               | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1771      | 38.16%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 377       | 8.12%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 314       | 6.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 226       | 4.87%   |
| Intel Ethernet Connection (4) I219-LM                             | 138       | 2.97%   |
| Intel Ethernet Connection I219-LM                                 | 89        | 1.92%   |
| Intel Ethernet Connection (4) I219-V                              | 83        | 1.79%   |
| Intel Ethernet Connection I218-LM                                 | 72        | 1.55%   |
| Intel Ethernet Connection (6) I219-V                              | 64        | 1.38%   |
| Intel Ethernet Connection (3) I218-LM                             | 60        | 1.29%   |
| Intel Ethernet Connection I217-LM                                 | 55        | 1.19%   |
| Intel Ethernet Connection (7) I219-LM                             | 53        | 1.14%   |
| Intel Ethernet Connection (10) I219-V                             | 52        | 1.12%   |
| Intel Ethernet Connection (6) I219-LM                             | 49        | 1.06%   |
| ASIX AX88179 Gigabit Ethernet                                     | 48        | 1.03%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 42        | 0.9%    |
| Intel 82577LM Gigabit Network Connection                          | 39        | 0.84%   |
| Intel Ethernet Connection (2) I219-LM                             | 37        | 0.8%    |
| Intel Ethernet Connection I219-V                                  | 35        | 0.75%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 34        | 0.73%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 31        | 0.67%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 30        | 0.65%   |
| Intel Ethernet Connection (13) I219-V                             | 30        | 0.65%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 29        | 0.62%   |
| Realtek RTL8125 2.5GbE Controller                                 | 28        | 0.6%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 27        | 0.58%   |
| Intel Ethernet Connection (7) I219-V                              | 26        | 0.56%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 24        | 0.52%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 24        | 0.52%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 24        | 0.52%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 22        | 0.47%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 22        | 0.47%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 21        | 0.45%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 19        | 0.41%   |
| Intel Ethernet Connection I217-V                                  | 18        | 0.39%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 16        | 0.34%   |
| Lenovo ThinkPad TBT3 LAN                                          | 16        | 0.34%   |
| Intel Ethernet Connection (10) I219-LM                            | 16        | 0.34%   |
| Intel 82567LM Gigabit Network Connection                          | 16        | 0.34%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 15        | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 5562      | 56.16%  |
| Ethernet | 4270      | 43.11%  |
| Modem    | 60        | 0.61%   |
| Unknown  | 12        | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 4851      | 79.54%  |
| Ethernet | 1246      | 20.43%  |
| Modem    | 2         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 3835      | 67.13%  |
| 1     | 1703      | 29.81%  |
| 0     | 105       | 1.84%   |
| 3     | 70        | 1.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Notebooks | Percent |
|---------|-----------|---------|
| No      | 4804      | 82.54%  |
| Yes     | 1013      | 17.41%  |
| Unknown | 3         | 0.05%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2807      | 58.18%  |
| Realtek Semiconductor           | 452       | 9.37%   |
| Qualcomm Atheros Communications | 447       | 9.26%   |
| IMC Networks                    | 201       | 4.17%   |
| Broadcom                        | 195       | 4.04%   |
| Lite-On Technology              | 183       | 3.79%   |
| Foxconn / Hon Hai               | 164       | 3.4%    |
| Apple                           | 120       | 2.49%   |
| Realtek                         | 54        | 1.12%   |
| Cambridge Silicon Radio         | 39        | 0.81%   |
| Dell                            | 36        | 0.75%   |
| Ralink                          | 27        | 0.56%   |
| Hewlett-Packard                 | 25        | 0.52%   |
| Toshiba                         | 20        | 0.41%   |
| ASUSTek Computer                | 15        | 0.31%   |
| Foxconn International           | 9         | 0.19%   |
| Opticis                         | 5         | 0.1%    |
| MediaTek                        | 5         | 0.1%    |
| USI                             | 4         | 0.08%   |
| Ralink Technology               | 4         | 0.08%   |
| Alps Electric                   | 3         | 0.06%   |
| Unknown                         | 2         | 0.04%   |
| Qcom                            | 2         | 0.04%   |
| Chicony Electronics             | 2         | 0.04%   |
| Taiyo Yuden                     | 1         | 0.02%   |
| Micro Star International        | 1         | 0.02%   |
| Corsair                         | 1         | 0.02%   |
| Askey Computer                  | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 1053      | 21.81%  |
| Intel AX201 Bluetooth                               | 549       | 11.37%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 436       | 9.03%   |
| Intel AX200 Bluetooth                               | 420       | 8.7%    |
| Realtek Bluetooth Radio                             | 265       | 5.49%   |
| Qualcomm Atheros  Bluetooth Device                  | 259       | 5.36%   |
| Realtek  Bluetooth 4.2 Adapter                      | 109       | 2.26%   |
| Apple Bluetooth Host Controller                     | 87        | 1.8%    |
| Intel AX210 Bluetooth                               | 83        | 1.72%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 77        | 1.59%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 76        | 1.57%   |
| IMC Networks Wireless_Device                        | 70        | 1.45%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 67        | 1.39%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 66        | 1.37%   |
| Intel Bluetooth Device                              | 66        | 1.37%   |
| Foxconn / Hon Hai Wireless_Device                   | 61        | 1.26%   |
| IMC Networks Bluetooth Radio                        | 60        | 1.24%   |
| Foxconn / Hon Hai Bluetooth Device                  | 59        | 1.22%   |
| Realtek 802.11ac WLAN Adapter                       | 50        | 1.04%   |
| Lite-On Bluetooth Device                            | 47        | 0.97%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 46        | 0.95%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 43        | 0.89%   |
| Intel Wireless-AC 3168 Bluetooth                    | 41        | 0.85%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 40        | 0.83%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 39        | 0.81%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 34        | 0.7%    |
| Broadcom BCM2045B (BDC-2.1)                         | 34        | 0.7%    |
| IMC Networks Bluetooth Device                       | 31        | 0.64%   |
| Ralink RT3290 Bluetooth                             | 27        | 0.56%   |
| Lite-On Atheros AR3012 Bluetooth                    | 23        | 0.48%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 23        | 0.48%   |
| Realtek RTL8723B Bluetooth                          | 22        | 0.46%   |
| Apple Bluetooth USB Host Controller                 | 22        | 0.46%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 19        | 0.39%   |
| HP Broadcom 2070 Bluetooth Combo                    | 19        | 0.39%   |
| Lite-On Wireless_Device                             | 18        | 0.37%   |
| Dell DW375 Bluetooth Module                         | 18        | 0.37%   |
| Dell BCM20702A0 Bluetooth Module                    | 15        | 0.31%   |
| Realtek RTL8821A Bluetooth                          | 14        | 0.29%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 13        | 0.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 4514      | 61.47%  |
| AMD                         | 1150      | 15.66%  |
| Nvidia                      | 968       | 13.18%  |
| Lenovo                      | 93        | 1.27%   |
| C-Media Electronics         | 73        | 0.99%   |
| Realtek Semiconductor       | 71        | 0.97%   |
| GN Netcom                   | 51        | 0.69%   |
| Logitech                    | 47        | 0.64%   |
| Plantronics                 | 36        | 0.49%   |
| Hewlett-Packard             | 26        | 0.35%   |
| JMTek                       | 19        | 0.26%   |
| Texas Instruments           | 15        | 0.2%    |
| Kingston Technology         | 15        | 0.2%    |
| Creative Technology         | 15        | 0.2%    |
| SteelSeries ApS             | 13        | 0.18%   |
| Corsair                     | 12        | 0.16%   |
| Razer USA                   | 11        | 0.15%   |
| DSEA A/S                    | 11        | 0.15%   |
| Apple                       | 11        | 0.15%   |
| Sony                        | 9         | 0.12%   |
| Generalplus Technology      | 9         | 0.12%   |
| Blue Microphones            | 9         | 0.12%   |
| Samson Technologies         | 8         | 0.11%   |
| RODE Microphones            | 8         | 0.11%   |
| Dell                        | 7         | 0.1%    |
| Conexant Systems            | 7         | 0.1%    |
| XMOS                        | 6         | 0.08%   |
| Microsoft                   | 6         | 0.08%   |
| Focusrite-Novation          | 6         | 0.08%   |
| CMX Systems                 | 6         | 0.08%   |
| SAVITECH                    | 5         | 0.07%   |
| Samsung Electronics         | 5         | 0.07%   |
| No brand                    | 5         | 0.07%   |
| ASUSTek Computer            | 5         | 0.07%   |
| Tenx Technology             | 4         | 0.05%   |
| PreSonus Audio Electronics  | 4         | 0.05%   |
| GYROCOM C&C                 | 4         | 0.05%   |
| FiiO Electronics Technology | 4         | 0.05%   |
| Cambridge Silicon Radio     | 4         | 0.05%   |
| M-Audio                     | 3         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 950       | 10.62%  |
| AMD Family 17h/19h HD Audio Controller                                     | 864       | 9.66%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 471       | 5.27%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 400       | 4.47%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 360       | 4.03%   |
| Intel Cannon Lake PCH cAVS                                                 | 329       | 3.68%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 270       | 3.02%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 260       | 2.91%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 246       | 2.75%   |
| Intel Comet Lake PCH-LP cAVS                                               | 230       | 2.57%   |
| Intel Haswell-ULT HD Audio Controller                                      | 224       | 2.5%    |
| Intel 8 Series HD Audio Controller                                         | 224       | 2.5%    |
| Intel Broadwell-U Audio Controller                                         | 210       | 2.35%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 208       | 2.33%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 200       | 2.24%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 161       | 1.8%    |
| Intel Comet Lake PCH cAVS                                                  | 160       | 1.79%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 146       | 1.63%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 129       | 1.44%   |
| Intel CM238 HD Audio Controller                                            | 128       | 1.43%   |
| Nvidia GP107GL High Definition Audio Controller                            | 127       | 1.42%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 115       | 1.29%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 111       | 1.24%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 107       | 1.2%    |
| AMD FCH Azalia Controller                                                  | 95        | 1.06%   |
| Nvidia TU106 High Definition Audio Controller                              | 77        | 0.86%   |
| AMD Kabini HDMI/DP Audio                                                   | 77        | 0.86%   |
| Nvidia GA106 High Definition Audio Controller                              | 74        | 0.83%   |
| Realtek Semiconductor USB Audio                                            | 70        | 0.78%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 68        | 0.76%   |
| Nvidia GF108 High Definition Audio Controller                              | 63        | 0.7%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 59        | 0.66%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 58        | 0.65%   |
| Nvidia GK107 HDMI Audio Controller                                         | 57        | 0.64%   |
| Nvidia TU116 High Definition Audio Controller                              | 52        | 0.58%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 52        | 0.58%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 51        | 0.57%   |
| Nvidia GA104 High Definition Audio Controller                              | 44        | 0.49%   |
| Nvidia GP106 High Definition Audio Controller                              | 43        | 0.48%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 39        | 0.44%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1072      | 29.53%  |
| SK hynix            | 817       | 22.51%  |
| Micron Technology   | 520       | 14.33%  |
| Kingston            | 310       | 8.54%   |
| Crucial             | 199       | 5.48%   |
| Unknown             | 185       | 5.1%    |
| Ramaxel Technology  | 88        | 2.42%   |
| A-DATA Technology   | 84        | 2.31%   |
| Corsair             | 53        | 1.46%   |
| Elpida              | 33        | 0.91%   |
| Smart               | 28        | 0.77%   |
| Unknown (ABCD)      | 24        | 0.66%   |
| G.Skill             | 23        | 0.63%   |
| Team                | 22        | 0.61%   |
| Nanya Technology    | 18        | 0.5%    |
| Patriot             | 17        | 0.47%   |
| Unknown             | 17        | 0.47%   |
| Smart Brazil        | 11        | 0.3%    |
| Teikon              | 10        | 0.28%   |
| Transcend           | 9         | 0.25%   |
| GOODRAM             | 9         | 0.25%   |
| Avant               | 8         | 0.22%   |
| Goldkey             | 5         | 0.14%   |
| Silicon Power       | 4         | 0.11%   |
| Apacer              | 4         | 0.11%   |
| PUSKILL             | 3         | 0.08%   |
| OnBoard             | 3         | 0.08%   |
| Kllisre             | 3         | 0.08%   |
| CSX                 | 3         | 0.08%   |
| Timetec             | 2         | 0.06%   |
| SHARETRONIC         | 2         | 0.06%   |
| Sesame              | 2         | 0.06%   |
| RZX                 | 2         | 0.06%   |
| Qimonda             | 2         | 0.06%   |
| PNY                 | 2         | 0.06%   |
| Memox               | 2         | 0.06%   |
| Lexar               | 2         | 0.06%   |
| ChangXin Memory     | 2         | 0.06%   |
| ASint Technology    | 2         | 0.06%   |
| Wilk                | 1         | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 67        | 1.75%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 66        | 1.73%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 50        | 1.31%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 48        | 1.25%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 33        | 0.86%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 29        | 0.76%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 29        | 0.76%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 28        | 0.73%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 28        | 0.73%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 28        | 0.73%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 28        | 0.73%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 28        | 0.73%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 27        | 0.71%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 26        | 0.68%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 25        | 0.65%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 25        | 0.65%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 25        | 0.65%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 24        | 0.63%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 24        | 0.63%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 24        | 0.63%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 23        | 0.6%    |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 23        | 0.6%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 22        | 0.58%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 22        | 0.58%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 22        | 0.58%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 21        | 0.55%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 21        | 0.55%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 21        | 0.55%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 20        | 0.52%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 20        | 0.52%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 20        | 0.52%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 20        | 0.52%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 19        | 0.5%    |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 19        | 0.5%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 19        | 0.5%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 19        | 0.5%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 18        | 0.47%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 18        | 0.47%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 18        | 0.47%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 18        | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 1746      | 57.68%  |
| DDR3    | 796       | 26.3%   |
| LPDDR3  | 177       | 5.85%   |
| LPDDR4  | 160       | 5.29%   |
| LPDDR5  | 42        | 1.39%   |
| DDR2    | 39        | 1.29%   |
| DDR5    | 33        | 1.09%   |
| SDRAM   | 17        | 0.56%   |
| Unknown | 13        | 0.43%   |
| DDR     | 3         | 0.1%    |
| DRAM    | 1         | 0.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 2603      | 84.35%  |
| Row Of Chips | 408       | 13.22%  |
| Chip         | 45        | 1.46%   |
| DIMM         | 18        | 0.58%   |
| Unknown      | 12        | 0.39%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 1414      | 42.9%   |
| 4096  | 882       | 26.76%  |
| 16384 | 603       | 18.29%  |
| 2048  | 242       | 7.34%   |
| 32768 | 113       | 3.43%   |
| 1024  | 38        | 1.15%   |
| 3072  | 2         | 0.06%   |
| 512   | 1         | 0.03%   |
| 64    | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 801       | 24.51%  |
| 3200    | 717       | 21.94%  |
| 1600    | 582       | 17.81%  |
| 2400    | 266       | 8.14%   |
| 2133    | 234       | 7.16%   |
| 1333    | 100       | 3.06%   |
| 1334    | 92        | 2.82%   |
| 4267    | 76        | 2.33%   |
| 1867    | 70        | 2.14%   |
| 3266    | 50        | 1.53%   |
| 6400    | 42        | 1.29%   |
| 4800    | 38        | 1.16%   |
| 1067    | 33        | 1.01%   |
| Unknown | 27        | 0.83%   |
| 8400    | 24        | 0.73%   |
| 667     | 24        | 0.73%   |
| 4266    | 23        | 0.7%    |
| 4199    | 14        | 0.43%   |
| 1066    | 14        | 0.43%   |
| 3733    | 12        | 0.37%   |
| 800     | 11        | 0.34%   |
| 2933    | 3         | 0.09%   |
| 975     | 3         | 0.09%   |
| 933     | 2         | 0.06%   |
| 533     | 2         | 0.06%   |
| 3400    | 1         | 0.03%   |
| 2800    | 1         | 0.03%   |
| 2048    | 1         | 0.03%   |
| 1866    | 1         | 0.03%   |
| 1639    | 1         | 0.03%   |
| 1200    | 1         | 0.03%   |
| 333     | 1         | 0.03%   |
| 133     | 1         | 0.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 9         | 25%     |
| Canon               | 8         | 22.22%  |
| Samsung Electronics | 6         | 16.67%  |
| Brother Industries  | 4         | 11.11%  |
| Seiko Epson         | 3         | 8.33%   |
| Prolific Technology | 2         | 5.56%   |
| Ricoh               | 1         | 2.78%   |
| Pantum              | 1         | 2.78%   |
| NXP Semiconductors  | 1         | 2.78%   |
| MiiiW               | 1         | 2.78%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port        | 2         | 5.56%   |
| Seiko Epson WF-2830 Series           | 1         | 2.78%   |
| Seiko Epson L200 Series              | 1         | 2.78%   |
| Seiko Epson ET-2710 Series           | 1         | 2.78%   |
| Samsung SCX-4200 series              | 1         | 2.78%   |
| Samsung SCX-3200 Series              | 1         | 2.78%   |
| Samsung ML-331x Series Laser Printer | 1         | 2.78%   |
| Samsung M2070 Series                 | 1         | 2.78%   |
| Samsung CLX-6260 Series              | 1         | 2.78%   |
| Samsung C43x Series                  | 1         | 2.78%   |
| Ricoh SP 212SUw                      | 1         | 2.78%   |
| Pantum P2500W series                 | 1         | 2.78%   |
| NXP Semiconductors Printer-80        | 1         | 2.78%   |
| MiiiW MW USB Receiver                | 1         | 2.78%   |
| HP Photosmart B010 series            | 1         | 2.78%   |
| HP Officejet 2620 series             | 1         | 2.78%   |
| HP LaserJet 400 colorMFP M475dw      | 1         | 2.78%   |
| HP ENVY Pro 6400 series              | 1         | 2.78%   |
| HP ENVY 4500 series                  | 1         | 2.78%   |
| HP Deskjet 3510 series               | 1         | 2.78%   |
| HP Deskjet 3050A                     | 1         | 2.78%   |
| HP DeskJet 2300 series               | 1         | 2.78%   |
| HP DeskJet 2130 series               | 1         | 2.78%   |
| Canon TR8500 series                  | 1         | 2.78%   |
| Canon TR150 series                   | 1         | 2.78%   |
| Canon PIXMA MG3600 Series            | 1         | 2.78%   |
| Canon PIXMA MG3500 Series            | 1         | 2.78%   |
| Canon PIXMA MG3000 series            | 1         | 2.78%   |
| Canon MF3110                         | 1         | 2.78%   |
| Canon MF220 Series                   | 1         | 2.78%   |
| Canon iP7200 series                  | 1         | 2.78%   |
| Brother Printer                      | 1         | 2.78%   |
| Brother HL-5250DN Printer            | 1         | 2.78%   |
| Brother DCP-T220                     | 1         | 2.78%   |
| Brother DCP-1600                     | 1         | 2.78%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 6         | 60%     |
| Seiko Epson     | 3         | 30%     |
| Hewlett-Packard | 1         | 10%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20          | 2         | 20%     |
| Canon CanoScan LiDE 220                     | 2         | 20%     |
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1         | 10%     |
| Seiko Epson GT-X770 [Perfection V500]       | 1         | 10%     |
| Seiko Epson ES-D400 [GT-S80]                | 1         | 10%     |
| HP Scanjet 300                              | 1         | 10%     |
| Canon CanoScan N650U/N656U                  | 1         | 10%     |
| Canon CanoScan LiDE 210                     | 1         | 10%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1332      | 24.79%  |
| IMC Networks                           | 651       | 12.11%  |
| Acer                                   | 490       | 9.12%   |
| Microdia                               | 485       | 9.02%   |
| Realtek Semiconductor                  | 470       | 8.75%   |
| Quanta                                 | 304       | 5.66%   |
| Sunplus Innovation Technology          | 287       | 5.34%   |
| Cheng Uei Precision Industry (Foxlink) | 219       | 4.08%   |
| Lite-On Technology                     | 161       | 3%      |
| Syntek                                 | 146       | 2.72%   |
| Logitech                               | 125       | 2.33%   |
| Apple                                  | 110       | 2.05%   |
| Suyin                                  | 88        | 1.64%   |
| Luxvisions Innotech Limited            | 82        | 1.53%   |
| Silicon Motion                         | 66        | 1.23%   |
| Alcor Micro                            | 38        | 0.71%   |
| Samsung Electronics                    | 36        | 0.67%   |
| Ricoh                                  | 32        | 0.6%    |
| Sonix Technology                       | 22        | 0.41%   |
| Lenovo                                 | 20        | 0.37%   |
| Primax Electronics                     | 19        | 0.35%   |
| Microsoft                              | 15        | 0.28%   |
| Importek                               | 14        | 0.26%   |
| Z-Star Microelectronics                | 11        | 0.2%    |
| SunplusIT                              | 10        | 0.19%   |
| Generalplus Technology                 | 9         | 0.17%   |
| DLEQNA19IFK6G2                         | 9         | 0.17%   |
| icSpring                               | 8         | 0.15%   |
| Bison Electronics                      | 8         | 0.15%   |
| ARC International                      | 8         | 0.15%   |
| KYE Systems (Mouse Systems)            | 6         | 0.11%   |
| ALi                                    | 6         | 0.11%   |
| Pixart Imaging                         | 5         | 0.09%   |
| MacroSilicon                           | 5         | 0.09%   |
| Intel                                  | 5         | 0.09%   |
| WaveRider Communications               | 4         | 0.07%   |
| Unknown                                | 4         | 0.07%   |
| Tripath Technology                     | 3         | 0.06%   |
| Tobii Technology AB                    | 3         | 0.06%   |
| Razer USA                              | 3         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 461       | 8.5%    |
| Microdia Integrated_Webcam_HD                                              | 284       | 5.24%   |
| IMC Networks Integrated Camera                                             | 261       | 4.81%   |
| Realtek Integrated_Webcam_HD                                               | 211       | 3.89%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 164       | 3.02%   |
| Acer Integrated Camera                                                     | 148       | 2.73%   |
| Chicony HD Webcam                                                          | 140       | 2.58%   |
| Sunplus Integrated_Webcam_HD                                               | 125       | 2.3%    |
| Syntek Integrated Camera                                                   | 94        | 1.73%   |
| Chicony Integrated Camera (1280x720@30)                                    | 78        | 1.44%   |
| Lite-On Integrated Camera                                                  | 76        | 1.4%    |
| Quanta HD User Facing                                                      | 67        | 1.24%   |
| Chicony HP HD Camera                                                       | 56        | 1.03%   |
| Acer SunplusIT Integrated Camera                                           | 53        | 0.98%   |
| Acer Lenovo EasyCamera                                                     | 53        | 0.98%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 50        | 0.92%   |
| Quanta HP TrueVision HD Camera                                             | 49        | 0.9%    |
| Acer HD Webcam                                                             | 42        | 0.77%   |
| Microdia Integrated Webcam                                                 | 41        | 0.76%   |
| Chicony USB2.0 Camera                                                      | 40        | 0.74%   |
| Quanta HD Webcam                                                           | 38        | 0.7%    |
| Quanta HP HD Camera                                                        | 37        | 0.68%   |
| Lite-On HP HD Camera                                                       | 37        | 0.68%   |
| Samsung Galaxy A5 (MTP)                                                    | 36        | 0.66%   |
| Realtek Integrated Webcam                                                  | 33        | 0.61%   |
| Chicony HP Wide Vision HD Camera                                           | 33        | 0.61%   |
| Chicony HP TrueVision HD Camera                                            | 33        | 0.61%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 33        | 0.61%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 33        | 0.61%   |
| IMC Networks HD Camera                                                     | 32        | 0.59%   |
| Sunplus HD WebCam                                                          | 31        | 0.57%   |
| Realtek Integrated Webcam HD                                               | 31        | 0.57%   |
| Logitech HD Pro Webcam C920                                                | 31        | 0.57%   |
| Acer BisonCam, NB Pro                                                      | 31        | 0.57%   |
| Realtek USB Camera                                                         | 30        | 0.55%   |
| Apple Built-in iSight                                                      | 30        | 0.55%   |
| Chicony HD User Facing                                                     | 29        | 0.53%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 29        | 0.53%   |
| Microdia Integrated Webcam HD                                              | 28        | 0.52%   |
| Chicony USB2.0 HD UVC WebCam                                               | 28        | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 506       | 36.09%  |
| Validity Sensors                   | 438       | 31.24%  |
| Shenzhen Goodix Technology         | 226       | 16.12%  |
| Elan Microelectronics              | 82        | 5.85%   |
| Upek                               | 54        | 3.85%   |
| LighTuning Technology              | 49        | 3.5%    |
| AuthenTec                          | 30        | 2.14%   |
| Samsung Electronics                | 6         | 0.43%   |
| STMicroelectronics                 | 4         | 0.29%   |
| Focal-systems.Corp                 | 4         | 0.29%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.14%   |
| Dell                               | 1         | 0.07%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 247       | 17.61%  |
| Shenzhen Goodix  FingerPrint Device                                        | 133       | 9.48%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 98        | 6.99%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 88        | 6.27%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 84        | 5.99%   |
| Unknown                                                                    | 69        | 4.92%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 52        | 3.71%   |
| Elan ELAN:Fingerprint                                                      | 52        | 3.71%   |
| Shenzhen Goodix FingerPrint                                                | 50        | 3.56%   |
| Validity Sensors Synaptics WBDI                                            | 46        | 3.28%   |
| Shenzhen Goodix Fingerprint Reader                                         | 43        | 3.06%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 40        | 2.85%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 39        | 2.78%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 35        | 2.49%   |
| Elan ELAN:ARM-M4                                                           | 29        | 2.07%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 27        | 1.92%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 26        | 1.85%   |
| Validity Sensors VFS491                                                    | 24        | 1.71%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 22        | 1.57%   |
| Synaptics  WBDI                                                            | 21        | 1.5%    |
| Validity Sensors Fingerprint scanner                                       | 17        | 1.21%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 17        | 1.21%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 17        | 1.21%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 14        | 1%      |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 13        | 0.93%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 12        | 0.86%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 11        | 0.78%   |
| AuthenTec Fingerprint Sensor                                               | 8         | 0.57%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 6         | 0.43%   |
| Synaptics WBDI Device                                                      | 6         | 0.43%   |
| AuthenTec AES2810                                                          | 6         | 0.43%   |
| Validity Sensors VFS Fingerprint sensor                                    | 5         | 0.36%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 0.36%   |
| STMicroelectronics Fingerprint Reader                                      | 4         | 0.29%   |
| Samsung Fingerprint Device                                                 | 4         | 0.29%   |
| LighTuning Fingerprint Reader                                              | 4         | 0.29%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 4         | 0.29%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 4         | 0.29%   |
| AuthenTec AES1600                                                          | 4         | 0.29%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.21%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Alcor Micro                | 226       | 42.09%  |
| Broadcom                   | 211       | 39.29%  |
| Upek                       | 36        | 6.7%    |
| Lenovo                     | 30        | 5.59%   |
| O2 Micro                   | 11        | 2.05%   |
| Gemalto (was Gemplus)      | 5         | 0.93%   |
| SCM Microsystems           | 3         | 0.56%   |
| OmniKey                    | 3         | 0.56%   |
| Aladdin Knowledge Systems  | 3         | 0.56%   |
| Yubico.com                 | 2         | 0.37%   |
| Realtek Semiconductor      | 2         | 0.37%   |
| Reiner SCT Kartensysteme   | 1         | 0.19%   |
| Hewlett-Packard            | 1         | 0.19%   |
| Chicony Electronics        | 1         | 0.19%   |
| Athena Smartcard Solutions | 1         | 0.19%   |
| Advanced Card Systems      | 1         | 0.19%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 225       | 41.9%   |
| Broadcom 5880                                                                | 70        | 13.04%  |
| Broadcom BCM5880 Secure Applications Processor                               | 52        | 9.68%   |
| Broadcom 58200                                                               | 52        | 9.68%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 36        | 6.7%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 35        | 6.52%   |
| Lenovo Integrated Smart Card Reader                                          | 29        | 5.4%    |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 9         | 1.68%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 4         | 0.74%   |
| Aladdin Knowledge Systems Token JC                                           | 3         | 0.56%   |
| Yubico.com Yubikey 4 U2F+CCID                                                | 2         | 0.37%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 0.37%   |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 0.37%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.37%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.19%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 0.19%   |
| SCM Microsystems CLOUD 2900 R Smart Card Reader                              | 1         | 0.19%   |
| Reiner SCT Kartensysteme tanJack USB                                         | 1         | 0.19%   |
| OmniKey CardMan 4321                                                         | 1         | 0.19%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.19%   |
| OmniKey CardMan 1021                                                         | 1         | 0.19%   |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.19%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.19%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.19%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.19%   |
| Athena Smartcard Solutions ASEDrive CCID                                     | 1         | 0.19%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.19%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.19%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 3421      | 58.11%  |
| 1     | 2029      | 34.47%  |
| 2     | 374       | 6.35%   |
| 3     | 45        | 0.76%   |
| 4     | 7         | 0.12%   |
| 5     | 5         | 0.08%   |
| 6     | 3         | 0.05%   |
| 7     | 2         | 0.03%   |
| 8     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 1388      | 48.21%  |
| Graphics card            | 520       | 18.06%  |
| Multimedia controller    | 257       | 8.93%   |
| Net/wireless             | 192       | 6.67%   |
| Chipcard                 | 191       | 6.63%   |
| Camera                   | 111       | 3.86%   |
| Bluetooth                | 58        | 2.01%   |
| Storage                  | 44        | 1.53%   |
| Card reader              | 40        | 1.39%   |
| Sound                    | 17        | 0.59%   |
| Net/ethernet             | 17        | 0.59%   |
| Communication controller | 16        | 0.56%   |
| Network                  | 15        | 0.52%   |
| Modem                    | 8         | 0.28%   |
| Flash memory             | 2         | 0.07%   |
| Video                    | 1         | 0.03%   |
| Firewire controller      | 1         | 0.03%   |
| Dvb card                 | 1         | 0.03%   |

