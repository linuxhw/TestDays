Ubuntu 22.04 - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu 22.04.

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

Total: 8441

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | ProBook 650 G8 Notebook ... | [b11a7b69f0](https://linux-hardware.org/?probe=b11a7b69f0) | Sep 07, 2023 |
| Lenovo        | Legion Y7000P IRH8 82YA     | [9ebc45f613](https://linux-hardware.org/?probe=9ebc45f613) | Sep 07, 2023 |
| Apple         | MacBookPro8,1               | [f913de368f](https://linux-hardware.org/?probe=f913de368f) | Sep 07, 2023 |
| ASUSTek       | X453MA                      | [c48759c297](https://linux-hardware.org/?probe=c48759c297) | Sep 07, 2023 |
| Apple         | MacBookPro8,1               | [423b8d7135](https://linux-hardware.org/?probe=423b8d7135) | Sep 07, 2023 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | [0ca7d43ae9](https://linux-hardware.org/?probe=0ca7d43ae9) | Sep 07, 2023 |
| Dell          | Precision M6800             | [b50e95f460](https://linux-hardware.org/?probe=b50e95f460) | Sep 07, 2023 |
| Lenovo        | G565 20071                  | [786aafb0e9](https://linux-hardware.org/?probe=786aafb0e9) | Sep 07, 2023 |
| Dell          | Inspiron 1525               | [6b0747dcb4](https://linux-hardware.org/?probe=6b0747dcb4) | Sep 07, 2023 |
| Dell          | Inspiron 1525               | [56a481c501](https://linux-hardware.org/?probe=56a481c501) | Sep 06, 2023 |
| ASUSTek       | ZenBook Pro Duo UX582LR_... | [b2ba03726a](https://linux-hardware.org/?probe=b2ba03726a) | Sep 06, 2023 |
| realme        | RMNBXXXX                    | [6783f1d181](https://linux-hardware.org/?probe=6783f1d181) | Sep 06, 2023 |
| Apple         | MacBookAir8,2               | [e9e8da1eea](https://linux-hardware.org/?probe=e9e8da1eea) | Sep 06, 2023 |
| Dell          | Latitude E5450              | [1478760d8c](https://linux-hardware.org/?probe=1478760d8c) | Sep 06, 2023 |
| HP            | Pavilion Notebook           | [50777cde40](https://linux-hardware.org/?probe=50777cde40) | Sep 06, 2023 |
| realme        | RMNBXXXX                    | [9370483c5f](https://linux-hardware.org/?probe=9370483c5f) | Sep 06, 2023 |
| Sony          | VGN-AW41MF_H                | [d3a3262a6e](https://linux-hardware.org/?probe=d3a3262a6e) | Sep 06, 2023 |
| Lenovo        | ThinkPad P1 20MD0014UK      | [428c816118](https://linux-hardware.org/?probe=428c816118) | Sep 06, 2023 |
| Dell          | Latitude 3520               | [0fa236983e](https://linux-hardware.org/?probe=0fa236983e) | Sep 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [2505f514b1](https://linux-hardware.org/?probe=2505f514b1) | Sep 06, 2023 |
| TUXEDO        | Unknown                     | [1e6c412d84](https://linux-hardware.org/?probe=1e6c412d84) | Sep 06, 2023 |
| VALE          | Notebook Classic C140       | [c2e792fccf](https://linux-hardware.org/?probe=c2e792fccf) | Sep 06, 2023 |
| VALE          | Notebook Classic C140       | [fb00b74b14](https://linux-hardware.org/?probe=fb00b74b14) | Sep 06, 2023 |
| VALE          | Notebook Classic C140       | [675a9e9b79](https://linux-hardware.org/?probe=675a9e9b79) | Sep 06, 2023 |
| Acer          | Aspire 5733Z                | [bc3d42d633](https://linux-hardware.org/?probe=bc3d42d633) | Sep 06, 2023 |
| Dell          | G3 3500                     | [5da26d2241](https://linux-hardware.org/?probe=5da26d2241) | Sep 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [f50ce96f55](https://linux-hardware.org/?probe=f50ce96f55) | Sep 06, 2023 |
| Sony          | SVE1712C5E                  | [a5c77b2450](https://linux-hardware.org/?probe=a5c77b2450) | Sep 06, 2023 |
| Sony          | SVE1712C5E                  | [f864c8e44a](https://linux-hardware.org/?probe=f864c8e44a) | Sep 05, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [cac93ead6f](https://linux-hardware.org/?probe=cac93ead6f) | Sep 05, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [9d86c0f6e5](https://linux-hardware.org/?probe=9d86c0f6e5) | Sep 05, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [a17f1582d4](https://linux-hardware.org/?probe=a17f1582d4) | Sep 05, 2023 |
| HUAWEI        | BoDE-WXX9                   | [06a65572fe](https://linux-hardware.org/?probe=06a65572fe) | Sep 05, 2023 |
| Gateway       | NE56R                       | [be83386f4d](https://linux-hardware.org/?probe=be83386f4d) | Sep 05, 2023 |
| Dell          | Precision 7740              | [392ca47879](https://linux-hardware.org/?probe=392ca47879) | Sep 05, 2023 |
| HP            | EliteBook 845 14 inch G9... | [30bf3f1f45](https://linux-hardware.org/?probe=30bf3f1f45) | Sep 05, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [5728a3a48b](https://linux-hardware.org/?probe=5728a3a48b) | Sep 05, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [fdecc11aba](https://linux-hardware.org/?probe=fdecc11aba) | Sep 05, 2023 |
| Notebook      | NL5xNU                      | [306dab3d42](https://linux-hardware.org/?probe=306dab3d42) | Sep 05, 2023 |
| Dell          | Precision 7670              | [41bb07b203](https://linux-hardware.org/?probe=41bb07b203) | Sep 05, 2023 |
| Lenovo        | Legion Y7000P IRH8 82YA     | [235e80247e](https://linux-hardware.org/?probe=235e80247e) | Sep 05, 2023 |
| Toshiba       | Satellite L455D             | [1d49ff24ad](https://linux-hardware.org/?probe=1d49ff24ad) | Sep 05, 2023 |
| Apple         | MacBookPro16,3              | [7f61d6c898](https://linux-hardware.org/?probe=7f61d6c898) | Sep 05, 2023 |
| HP            | EliteBook 8470p             | [a658addd87](https://linux-hardware.org/?probe=a658addd87) | Sep 05, 2023 |
| Apple         | MacBookPro16,2              | [b47ac62db2](https://linux-hardware.org/?probe=b47ac62db2) | Sep 05, 2023 |
| HP            | ProBook 6550b               | [5881531377](https://linux-hardware.org/?probe=5881531377) | Sep 05, 2023 |
| HONOR         | BRN-FXX                     | [381e87228c](https://linux-hardware.org/?probe=381e87228c) | Sep 04, 2023 |
| HP            | ZBook 15 G2                 | [18d9c74d60](https://linux-hardware.org/?probe=18d9c74d60) | Sep 04, 2023 |
| HP            | EliteBook 8470p             | [5cb02e099f](https://linux-hardware.org/?probe=5cb02e099f) | Sep 04, 2023 |
| HP            | Pavilion dv9500             | [653fbbb509](https://linux-hardware.org/?probe=653fbbb509) | Sep 04, 2023 |
| TUXEDO        | Pulse 15 Gen2               | [3dd77a8c87](https://linux-hardware.org/?probe=3dd77a8c87) | Sep 04, 2023 |
| Samsung       | 950XED                      | [3d8ba5a34c](https://linux-hardware.org/?probe=3d8ba5a34c) | Sep 04, 2023 |
| Dell          | Vostro 15 5510              | [7223b751c4](https://linux-hardware.org/?probe=7223b751c4) | Sep 04, 2023 |
| Lenovo        | ThinkPad X260 20F5S2WX0R    | [cb338af601](https://linux-hardware.org/?probe=cb338af601) | Sep 04, 2023 |
| ASUSTek       | K73SV                       | [7d3f9fa0e5](https://linux-hardware.org/?probe=7d3f9fa0e5) | Sep 04, 2023 |
| Dell          | Precision 3581              | [739b270d83](https://linux-hardware.org/?probe=739b270d83) | Sep 04, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [5128231fd7](https://linux-hardware.org/?probe=5128231fd7) | Sep 04, 2023 |
| Dynabook      | G83/HS                      | [9db149b715](https://linux-hardware.org/?probe=9db149b715) | Sep 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [ea096b699b](https://linux-hardware.org/?probe=ea096b699b) | Sep 04, 2023 |
| Acer          | Aspire A314-35              | [6edc4e910d](https://linux-hardware.org/?probe=6edc4e910d) | Sep 04, 2023 |
| Acer          | Aspire E1-572               | [5801580f1f](https://linux-hardware.org/?probe=5801580f1f) | Sep 04, 2023 |
| MSI           | Prestige 14Evo A12M         | [68bea64ed6](https://linux-hardware.org/?probe=68bea64ed6) | Sep 04, 2023 |
| HP            | ENVY 14 SPECTRE             | [1f0a26899c](https://linux-hardware.org/?probe=1f0a26899c) | Sep 04, 2023 |
| Samsung       | RV415                       | [dc6aa3101f](https://linux-hardware.org/?probe=dc6aa3101f) | Sep 03, 2023 |
| HP            | 240 G3                      | [24381b91f7](https://linux-hardware.org/?probe=24381b91f7) | Sep 03, 2023 |
| HUAWEI        | BOM-WXX9                    | [6b895a5320](https://linux-hardware.org/?probe=6b895a5320) | Sep 03, 2023 |
| ASUSTek       | ASUSLaptop_Q540VJ           | [39ed316bb6](https://linux-hardware.org/?probe=39ed316bb6) | Sep 03, 2023 |
| IP3 Techno... | ARN59P                      | [493a986305](https://linux-hardware.org/?probe=493a986305) | Sep 03, 2023 |
| Dell          | Latitude E6400              | [88a04ab4b8](https://linux-hardware.org/?probe=88a04ab4b8) | Sep 03, 2023 |
| Dell          | Latitude E6400              | [56cc7d7a27](https://linux-hardware.org/?probe=56cc7d7a27) | Sep 03, 2023 |
| Samsung       | R510/P510                   | [fa457144d5](https://linux-hardware.org/?probe=fa457144d5) | Sep 03, 2023 |
| Dell          | Latitude 5490               | [392d7335ed](https://linux-hardware.org/?probe=392d7335ed) | Sep 03, 2023 |
| Acer          | Swift SF314-42              | [89dcb5988f](https://linux-hardware.org/?probe=89dcb5988f) | Sep 03, 2023 |
| HP            | EliteBook 850 G3            | [0778936f6b](https://linux-hardware.org/?probe=0778936f6b) | Sep 03, 2023 |
| Acer          | Swift SF314-42              | [8552bc9508](https://linux-hardware.org/?probe=8552bc9508) | Sep 03, 2023 |
| Apple         | MacBookPro8,1               | [6cbaac077e](https://linux-hardware.org/?probe=6cbaac077e) | Sep 03, 2023 |
| Unknown       | Unknown                     | [8585671bfb](https://linux-hardware.org/?probe=8585671bfb) | Sep 03, 2023 |
| Unknown       | Unknown                     | [8d7616fae8](https://linux-hardware.org/?probe=8d7616fae8) | Sep 03, 2023 |
| Dell          | XPS 15 9570                 | [9607f36921](https://linux-hardware.org/?probe=9607f36921) | Sep 03, 2023 |
| HP            | Pavilion dv4                | [8d183fb271](https://linux-hardware.org/?probe=8d183fb271) | Sep 03, 2023 |
| Dell          | XPS 15 9570                 | [72c5c271b6](https://linux-hardware.org/?probe=72c5c271b6) | Sep 03, 2023 |
| Apple         | MacBookAir5,1               | [57bb5d91ab](https://linux-hardware.org/?probe=57bb5d91ab) | Sep 03, 2023 |
| Lenovo        | IdeaPad Gaming 3 16ARH7 ... | [13ea608a94](https://linux-hardware.org/?probe=13ea608a94) | Sep 03, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [5f73c55303](https://linux-hardware.org/?probe=5f73c55303) | Sep 03, 2023 |
| Acer          | Aspire E1-572               | [e91fdf4fbe](https://linux-hardware.org/?probe=e91fdf4fbe) | Sep 03, 2023 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [b9c93a8c15](https://linux-hardware.org/?probe=b9c93a8c15) | Sep 03, 2023 |
| VALE          | Notebook Classic C140       | [05b3dfb69a](https://linux-hardware.org/?probe=05b3dfb69a) | Sep 03, 2023 |
| ASUSTek       | X55A                        | [1ba0e59208](https://linux-hardware.org/?probe=1ba0e59208) | Sep 03, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [e04761c470](https://linux-hardware.org/?probe=e04761c470) | Sep 03, 2023 |
| Lenovo        | IdeaPad S540-13IML 81XA     | [246a993eb7](https://linux-hardware.org/?probe=246a993eb7) | Sep 02, 2023 |
| Unknown       | Unknown                     | [c72be678a2](https://linux-hardware.org/?probe=c72be678a2) | Sep 02, 2023 |
| HP            | Laptop 15s-eq3xxx           | [399abaa799](https://linux-hardware.org/?probe=399abaa799) | Sep 02, 2023 |
| Dell          | Latitude 5500               | [77e18d6323](https://linux-hardware.org/?probe=77e18d6323) | Sep 02, 2023 |
| Lenovo        | ThinkPad T520 42435JG       | [aad827567e](https://linux-hardware.org/?probe=aad827567e) | Sep 02, 2023 |
| Lenovo        | V130-15IGM 81HL             | [aa1ec8baed](https://linux-hardware.org/?probe=aa1ec8baed) | Sep 02, 2023 |
| Lenovo        | V130-15IGM 81HL             | [38371fb896](https://linux-hardware.org/?probe=38371fb896) | Sep 02, 2023 |
| Samsung       | 530XBB                      | [30365848c4](https://linux-hardware.org/?probe=30365848c4) | Sep 02, 2023 |
| Dell          | Latitude 7400               | [c98434cc21](https://linux-hardware.org/?probe=c98434cc21) | Sep 02, 2023 |
| Apple         | MacBookPro11,1              | [edca0e0264](https://linux-hardware.org/?probe=edca0e0264) | Sep 02, 2023 |
| Lenovo        | ThinkPad W510 438923U       | [b0648eccac](https://linux-hardware.org/?probe=b0648eccac) | Sep 02, 2023 |
| Sony          | SVE1513I4E                  | [a1009ff0be](https://linux-hardware.org/?probe=a1009ff0be) | Sep 02, 2023 |
| Toshiba       | Satellite C660              | [d3c3b72e39](https://linux-hardware.org/?probe=d3c3b72e39) | Sep 01, 2023 |
| Acer          | Aspire 7740                 | [1ab9e5eddb](https://linux-hardware.org/?probe=1ab9e5eddb) | Sep 01, 2023 |
| Dell          | Inspiron 15 3511            | [d2f04fdc9e](https://linux-hardware.org/?probe=d2f04fdc9e) | Sep 01, 2023 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | [aefedc3b34](https://linux-hardware.org/?probe=aefedc3b34) | Sep 01, 2023 |
| HP            | EliteBook 840 G3            | [929ae155ea](https://linux-hardware.org/?probe=929ae155ea) | Sep 01, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [d4335c9520](https://linux-hardware.org/?probe=d4335c9520) | Sep 01, 2023 |
| Sony          | SVE1513I4E                  | [404c008e41](https://linux-hardware.org/?probe=404c008e41) | Sep 01, 2023 |
| Lenovo        | Legion R9000P2021H 82JQ     | [1e7179e4f0](https://linux-hardware.org/?probe=1e7179e4f0) | Sep 01, 2023 |
| Dell          | Vostro 3550                 | [c9431922ba](https://linux-hardware.org/?probe=c9431922ba) | Sep 01, 2023 |
| Toshiba       | Satellite P55t-C            | [3dd1896d54](https://linux-hardware.org/?probe=3dd1896d54) | Sep 01, 2023 |
| Dell          | Inspiron 5579               | [14fa68270f](https://linux-hardware.org/?probe=14fa68270f) | Sep 01, 2023 |
| Lenovo        | ThinkPad T440p 20AWS1BL0... | [f1e1512fc9](https://linux-hardware.org/?probe=f1e1512fc9) | Sep 01, 2023 |
| HP            | ZBook 15                    | [8a20670725](https://linux-hardware.org/?probe=8a20670725) | Sep 01, 2023 |
| HUAWEI        | MACH-WX9                    | [6f761aa23b](https://linux-hardware.org/?probe=6f761aa23b) | Aug 31, 2023 |
| HP            | EliteBook 840 G2            | [53bcd4ec72](https://linux-hardware.org/?probe=53bcd4ec72) | Aug 31, 2023 |
| HP            | EliteBook 840 G3            | [3411b788bc](https://linux-hardware.org/?probe=3411b788bc) | Aug 31, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [b900fd0bc7](https://linux-hardware.org/?probe=b900fd0bc7) | Aug 31, 2023 |
| HP            | ProBook 4530s               | [09fddaab4d](https://linux-hardware.org/?probe=09fddaab4d) | Aug 31, 2023 |
| Dell          | Latitude 7340               | [d6d1df94f5](https://linux-hardware.org/?probe=d6d1df94f5) | Aug 31, 2023 |
| HUAWEI        | MACHD-WXX9                  | [2e74e88e2f](https://linux-hardware.org/?probe=2e74e88e2f) | Aug 31, 2023 |
| Lenovo        | ThinkPad X220 4290EC5       | [d75bd4dfbd](https://linux-hardware.org/?probe=d75bd4dfbd) | Aug 31, 2023 |
| HP            | 3115m                       | [85325be2ba](https://linux-hardware.org/?probe=85325be2ba) | Aug 31, 2023 |
| Lenovo        | ThinkPad T470s 20HGS0PA0... | [89caf6d252](https://linux-hardware.org/?probe=89caf6d252) | Aug 31, 2023 |
| MSI           | Thin GF63 12VE              | [0615d252af](https://linux-hardware.org/?probe=0615d252af) | Aug 31, 2023 |
| HP            | ProBook 455 15.6 inch G9... | [ae4d140b96](https://linux-hardware.org/?probe=ae4d140b96) | Aug 31, 2023 |
| Apple         | MacBookPro10,1              | [7741e9850b](https://linux-hardware.org/?probe=7741e9850b) | Aug 31, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | [33b5107930](https://linux-hardware.org/?probe=33b5107930) | Aug 31, 2023 |
| Dell          | XPS 15 7590                 | [b423b914f7](https://linux-hardware.org/?probe=b423b914f7) | Aug 30, 2023 |
| Dell          | G15 5530                    | [1027c8fe19](https://linux-hardware.org/?probe=1027c8fe19) | Aug 30, 2023 |
| HUAWEI        | BOM-WXX9                    | [ea587f2b2e](https://linux-hardware.org/?probe=ea587f2b2e) | Aug 30, 2023 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | [0a55847393](https://linux-hardware.org/?probe=0a55847393) | Aug 30, 2023 |
| Toshiba       | Satellite P50-B-113         | [a9f21477c8](https://linux-hardware.org/?probe=a9f21477c8) | Aug 30, 2023 |
| HP            | ZBook 15 G3                 | [d88312e34b](https://linux-hardware.org/?probe=d88312e34b) | Aug 30, 2023 |
| HP            | ZBook 15 G3                 | [7943c070cc](https://linux-hardware.org/?probe=7943c070cc) | Aug 30, 2023 |
| Dell          | Vostro 3550                 | [f120556c56](https://linux-hardware.org/?probe=f120556c56) | Aug 30, 2023 |
| ASUSTek       | ROG Strix G731GT_GL731GT    | [aac7eeec4e](https://linux-hardware.org/?probe=aac7eeec4e) | Aug 30, 2023 |
| HP            | EliteBook 840 G2            | [4f3d3f12a4](https://linux-hardware.org/?probe=4f3d3f12a4) | Aug 30, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [15c048cb00](https://linux-hardware.org/?probe=15c048cb00) | Aug 30, 2023 |
| Sony          | VGN-C15TP_W                 | [591d0b778e](https://linux-hardware.org/?probe=591d0b778e) | Aug 30, 2023 |
| Apple         | MacBookPro9,2               | [76805c8b77](https://linux-hardware.org/?probe=76805c8b77) | Aug 30, 2023 |
| Apple         | MacBookPro9,2               | [cc6b5178f0](https://linux-hardware.org/?probe=cc6b5178f0) | Aug 30, 2023 |
| HUAWEI        | KLVD-WXX9                   | [98262b8471](https://linux-hardware.org/?probe=98262b8471) | Aug 30, 2023 |
| Lenovo        | ThinkPad W541 20EGS0N00H    | [ed94f8b9b9](https://linux-hardware.org/?probe=ed94f8b9b9) | Aug 29, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | [64686e9027](https://linux-hardware.org/?probe=64686e9027) | Aug 29, 2023 |
| HP            | Pavilion g6                 | [b1836fb080](https://linux-hardware.org/?probe=b1836fb080) | Aug 29, 2023 |
| HONOR         | NMH-WCX9                    | [6e4b12a41e](https://linux-hardware.org/?probe=6e4b12a41e) | Aug 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [8c492a4b3d](https://linux-hardware.org/?probe=8c492a4b3d) | Aug 29, 2023 |
| ASUSTek       | X550LD                      | [b866599fbc](https://linux-hardware.org/?probe=b866599fbc) | Aug 29, 2023 |
| HP            | Dragonfly 13.5 inch G4 N... | [9450749b35](https://linux-hardware.org/?probe=9450749b35) | Aug 29, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [bf8f795045](https://linux-hardware.org/?probe=bf8f795045) | Aug 29, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [d6bca74de6](https://linux-hardware.org/?probe=d6bca74de6) | Aug 29, 2023 |
| Apple         | MacBookPro11,3              | [561b652278](https://linux-hardware.org/?probe=561b652278) | Aug 29, 2023 |
| HP            | 255 G2                      | [23bf2dd515](https://linux-hardware.org/?probe=23bf2dd515) | Aug 29, 2023 |
| Acer          | Aspire 5742                 | [9bbb56c640](https://linux-hardware.org/?probe=9bbb56c640) | Aug 29, 2023 |
| Sony          | VPCEA36FX                   | [174aefbf35](https://linux-hardware.org/?probe=174aefbf35) | Aug 29, 2023 |
| HP            | Pavilion Laptop 15t-eg30... | [aa2e067c2d](https://linux-hardware.org/?probe=aa2e067c2d) | Aug 29, 2023 |
| ASUSTek       | X580VD                      | [c8bed4c7e6](https://linux-hardware.org/?probe=c8bed4c7e6) | Aug 29, 2023 |
| Lenovo        | IdeaPad Slim 3 14ABR8 82... | [4fa3f56511](https://linux-hardware.org/?probe=4fa3f56511) | Aug 29, 2023 |
| Lenovo        | IdeaPad Slim 3 14ABR8 82... | [9bf240bf4d](https://linux-hardware.org/?probe=9bf240bf4d) | Aug 29, 2023 |
| HP            | ZBook 14 G2                 | [e56fcd0532](https://linux-hardware.org/?probe=e56fcd0532) | Aug 28, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [87b94b4ea0](https://linux-hardware.org/?probe=87b94b4ea0) | Aug 28, 2023 |
| MSI           | Katana GF66 12UGS           | [ca352a81f4](https://linux-hardware.org/?probe=ca352a81f4) | Aug 28, 2023 |
| HP            | Pavilion g6                 | [8d874b796c](https://linux-hardware.org/?probe=8d874b796c) | Aug 28, 2023 |
| HP            | Pavilion g6                 | [42bade556f](https://linux-hardware.org/?probe=42bade556f) | Aug 28, 2023 |
| ASUSTek       | K401UB                      | [14a7bf0f59](https://linux-hardware.org/?probe=14a7bf0f59) | Aug 28, 2023 |
| Dell          | Latitude E7240              | [1eab9b5f8d](https://linux-hardware.org/?probe=1eab9b5f8d) | Aug 28, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [dfb8d0f76b](https://linux-hardware.org/?probe=dfb8d0f76b) | Aug 28, 2023 |
| HP            | 630                         | [4a94779668](https://linux-hardware.org/?probe=4a94779668) | Aug 28, 2023 |
| Dell          | XPS 15 7590                 | [9abe07288a](https://linux-hardware.org/?probe=9abe07288a) | Aug 28, 2023 |
| Toshiba       | Satellite Pro C70-C         | [eb9fbb104c](https://linux-hardware.org/?probe=eb9fbb104c) | Aug 28, 2023 |
| Apple         | MacBookPro16,2              | [65408b783f](https://linux-hardware.org/?probe=65408b783f) | Aug 28, 2023 |
| HP            | 15 Notebook PC              | [bb75fbb42b](https://linux-hardware.org/?probe=bb75fbb42b) | Aug 28, 2023 |
| HP            | Laptop 15-ef0xxx            | [b948af0216](https://linux-hardware.org/?probe=b948af0216) | Aug 27, 2023 |
| Dell          | Latitude E5470              | [582c495a92](https://linux-hardware.org/?probe=582c495a92) | Aug 27, 2023 |
| Dell          | Latitude E5470              | [63816a7b5f](https://linux-hardware.org/?probe=63816a7b5f) | Aug 27, 2023 |
| Dell          | Inspiron 5590               | [5036ce79f9](https://linux-hardware.org/?probe=5036ce79f9) | Aug 27, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | [9fcb646019](https://linux-hardware.org/?probe=9fcb646019) | Aug 27, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | [9ce11e1efa](https://linux-hardware.org/?probe=9ce11e1efa) | Aug 27, 2023 |
| Dell          | Precision M4700             | [c65acacce9](https://linux-hardware.org/?probe=c65acacce9) | Aug 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [67a80738c9](https://linux-hardware.org/?probe=67a80738c9) | Aug 27, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | [be9aaf7726](https://linux-hardware.org/?probe=be9aaf7726) | Aug 27, 2023 |
| Lenovo        | ThinkPad L14 Gen 4 21H5C... | [96b559d5d6](https://linux-hardware.org/?probe=96b559d5d6) | Aug 27, 2023 |
| Notebook      | NHx0EH_EJ_EK                | [a37b52dfbe](https://linux-hardware.org/?probe=a37b52dfbe) | Aug 27, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [3f7455be45](https://linux-hardware.org/?probe=3f7455be45) | Aug 27, 2023 |
| HUAWEI        | HN-WX9X                     | [d526f12390](https://linux-hardware.org/?probe=d526f12390) | Aug 27, 2023 |
| Dell          | Studio 1737                 | [8e668fe167](https://linux-hardware.org/?probe=8e668fe167) | Aug 27, 2023 |
| Dell          | Latitude 14 Rugged (5404... | [c96c172d03](https://linux-hardware.org/?probe=c96c172d03) | Aug 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [cb258d3cc3](https://linux-hardware.org/?probe=cb258d3cc3) | Aug 27, 2023 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | [173b99bf55](https://linux-hardware.org/?probe=173b99bf55) | Aug 27, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [e165507af8](https://linux-hardware.org/?probe=e165507af8) | Aug 27, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [329d960437](https://linux-hardware.org/?probe=329d960437) | Aug 27, 2023 |
| Dell          | Precision M4700             | [8f4eef8a36](https://linux-hardware.org/?probe=8f4eef8a36) | Aug 27, 2023 |
| Dell          | Latitude 7390               | [8b97344f0a](https://linux-hardware.org/?probe=8b97344f0a) | Aug 27, 2023 |
| Dell          | Inspiron 16 Plus 7620       | [4a3a5eb408](https://linux-hardware.org/?probe=4a3a5eb408) | Aug 27, 2023 |
| Google        | Nautilus                    | [3f96b35cae](https://linux-hardware.org/?probe=3f96b35cae) | Aug 26, 2023 |
| HP            | Laptop 14-em0xxx            | [b59ee89595](https://linux-hardware.org/?probe=b59ee89595) | Aug 26, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [14605463c1](https://linux-hardware.org/?probe=14605463c1) | Aug 26, 2023 |
| Panasonic     | CF53-4                      | [6228d53ef2](https://linux-hardware.org/?probe=6228d53ef2) | Aug 26, 2023 |
| Positivo      | CHT14B                      | [81a8519b9e](https://linux-hardware.org/?probe=81a8519b9e) | Aug 26, 2023 |
| Acer          | Aspire V5-471P              | [fcbacf6769](https://linux-hardware.org/?probe=fcbacf6769) | Aug 26, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [738c091241](https://linux-hardware.org/?probe=738c091241) | Aug 26, 2023 |
| HP            | EliteBook 850 G1            | [4f74cc24e0](https://linux-hardware.org/?probe=4f74cc24e0) | Aug 26, 2023 |
| Acer          | Aspire E1-570               | [6c8db1b4dd](https://linux-hardware.org/?probe=6c8db1b4dd) | Aug 26, 2023 |
| HUAWEI        | KLVL-WXXW                   | [5e7257145a](https://linux-hardware.org/?probe=5e7257145a) | Aug 26, 2023 |
| HP            | Compaq 6710b (GE822PA#AB... | [134d0685ff](https://linux-hardware.org/?probe=134d0685ff) | Aug 26, 2023 |
| HUAWEI        | BOD-WXX9                    | [8f033793a9](https://linux-hardware.org/?probe=8f033793a9) | Aug 26, 2023 |
| HUAWEI        | BOD-WXX9                    | [0e107ac9bb](https://linux-hardware.org/?probe=0e107ac9bb) | Aug 26, 2023 |
| Acer          | Aspire E1-531               | [1a1924897a](https://linux-hardware.org/?probe=1a1924897a) | Aug 26, 2023 |
| Acer          | Aspire A515-56              | [53b787dc90](https://linux-hardware.org/?probe=53b787dc90) | Aug 26, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [0140ea0642](https://linux-hardware.org/?probe=0140ea0642) | Aug 26, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [6496a666d7](https://linux-hardware.org/?probe=6496a666d7) | Aug 26, 2023 |
| Samsung       | 300E5K/300E5Q               | [f0f9f25268](https://linux-hardware.org/?probe=f0f9f25268) | Aug 26, 2023 |
| Samsung       | 300E5K/300E5Q               | [95aa33fc09](https://linux-hardware.org/?probe=95aa33fc09) | Aug 26, 2023 |
| Notebook      | NL4x_NL5xLU                 | [22c5b125e0](https://linux-hardware.org/?probe=22c5b125e0) | Aug 25, 2023 |
| ASUSTek       | K53SD                       | [a8bb2fa11d](https://linux-hardware.org/?probe=a8bb2fa11d) | Aug 25, 2023 |
| HP            | Laptop 15-bs0xx             | [7a522c6b71](https://linux-hardware.org/?probe=7a522c6b71) | Aug 25, 2023 |
| Acer          | Aspire V3-571               | [376d5e8a22](https://linux-hardware.org/?probe=376d5e8a22) | Aug 25, 2023 |
| HUAWEI        | HN-WX9X                     | [95ff13464e](https://linux-hardware.org/?probe=95ff13464e) | Aug 25, 2023 |
| Lenovo        | ThinkPad L580 20LXS1D100    | [f30a161506](https://linux-hardware.org/?probe=f30a161506) | Aug 25, 2023 |
| Dell          | Latitude 5590               | [57e6618c1f](https://linux-hardware.org/?probe=57e6618c1f) | Aug 25, 2023 |
| Dell          | Latitude 5590               | [7e84349262](https://linux-hardware.org/?probe=7e84349262) | Aug 25, 2023 |
| Dell          | Precision 5480              | [c4f1e9b39b](https://linux-hardware.org/?probe=c4f1e9b39b) | Aug 25, 2023 |
| Timi          | A34R                        | [f2998bab84](https://linux-hardware.org/?probe=f2998bab84) | Aug 25, 2023 |
| HP            | Notebook                    | [c3ae6b2ed1](https://linux-hardware.org/?probe=c3ae6b2ed1) | Aug 25, 2023 |
| HP            | Laptop 15s-fq4xxx           | [e2c530b9fd](https://linux-hardware.org/?probe=e2c530b9fd) | Aug 25, 2023 |
| Dell          | XPS 17 9700                 | [93fec269da](https://linux-hardware.org/?probe=93fec269da) | Aug 25, 2023 |
| HP            | Pavilion Laptop 15-cc5xx    | [1bdd23422a](https://linux-hardware.org/?probe=1bdd23422a) | Aug 25, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [bb854d7896](https://linux-hardware.org/?probe=bb854d7896) | Aug 25, 2023 |
| Sony          | VPCCW23FX                   | [e58afa3312](https://linux-hardware.org/?probe=e58afa3312) | Aug 25, 2023 |
| Dell          | XPS 15 9520                 | [16aa1ac3af](https://linux-hardware.org/?probe=16aa1ac3af) | Aug 25, 2023 |
| Dell          | Vostro 5470                 | [2e62ce7973](https://linux-hardware.org/?probe=2e62ce7973) | Aug 25, 2023 |
| Sony          | VGN-C15TP_W                 | [a63433e04d](https://linux-hardware.org/?probe=a63433e04d) | Aug 25, 2023 |
| Lenovo        | ThinkPad W530 2447GW3       | [3438523e90](https://linux-hardware.org/?probe=3438523e90) | Aug 25, 2023 |
| Acer          | Aspire 5742                 | [7d896ad750](https://linux-hardware.org/?probe=7d896ad750) | Aug 24, 2023 |
| Lenovo        | ThinkPad W530 2447GW3       | [72d1d1be0b](https://linux-hardware.org/?probe=72d1d1be0b) | Aug 24, 2023 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [0b3afd5dce](https://linux-hardware.org/?probe=0b3afd5dce) | Aug 24, 2023 |
| Dell          | Inspiron 5770               | [caecc0c140](https://linux-hardware.org/?probe=caecc0c140) | Aug 24, 2023 |
| Dell          | Inspiron 5770               | [0aaf8b7985](https://linux-hardware.org/?probe=0aaf8b7985) | Aug 24, 2023 |
| Dell          | Inspiron 7572               | [84f4498af0](https://linux-hardware.org/?probe=84f4498af0) | Aug 24, 2023 |
| Mediacom      | GTZS                        | [8b40b2b9fc](https://linux-hardware.org/?probe=8b40b2b9fc) | Aug 24, 2023 |
| HP            | ZBook Fury 15 G7 Mobile ... | [a2b21f0903](https://linux-hardware.org/?probe=a2b21f0903) | Aug 24, 2023 |
| Apple         | MacBookAir8,1               | [a1a9178606](https://linux-hardware.org/?probe=a1a9178606) | Aug 24, 2023 |
| HP            | ZBook 14 G2                 | [d3efd68f2f](https://linux-hardware.org/?probe=d3efd68f2f) | Aug 24, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BV0... | [3d7ba31c2a](https://linux-hardware.org/?probe=3d7ba31c2a) | Aug 24, 2023 |
| Dell          | Latitude 3520               | [92ef936c86](https://linux-hardware.org/?probe=92ef936c86) | Aug 24, 2023 |
| Lenovo        | ThinkPad T430 2347DS4       | [cbaaad3882](https://linux-hardware.org/?probe=cbaaad3882) | Aug 24, 2023 |
| ASUSTek       | K73SV                       | [d366a928cc](https://linux-hardware.org/?probe=d366a928cc) | Aug 24, 2023 |
| Lenovo        | Legion Y7000P IRH8 82YA     | [4b21c7c00f](https://linux-hardware.org/?probe=4b21c7c00f) | Aug 24, 2023 |
| HP            | EliteBook 840 G1            | [1bae9647d1](https://linux-hardware.org/?probe=1bae9647d1) | Aug 24, 2023 |
| Dell          | Inspiron 5748               | [ea2d298b05](https://linux-hardware.org/?probe=ea2d298b05) | Aug 24, 2023 |
| Dell          | Precision 5680              | [3ef7298733](https://linux-hardware.org/?probe=3ef7298733) | Aug 24, 2023 |
| Dell          | Precision 3561              | [610fa14d3a](https://linux-hardware.org/?probe=610fa14d3a) | Aug 24, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [5bddf6d37d](https://linux-hardware.org/?probe=5bddf6d37d) | Aug 23, 2023 |
| HUAWEI        | BOM-WXX9                    | [061ecf9479](https://linux-hardware.org/?probe=061ecf9479) | Aug 23, 2023 |
| MSI           | GP72 6QF                    | [3afc91a639](https://linux-hardware.org/?probe=3afc91a639) | Aug 23, 2023 |
| TUXEDO        | Pulse 15 Gen2               | [da78ac9e8e](https://linux-hardware.org/?probe=da78ac9e8e) | Aug 23, 2023 |
| HP            | EliteBook 8440p             | [89e74082d8](https://linux-hardware.org/?probe=89e74082d8) | Aug 23, 2023 |
| HP            | Laptop 17-cp2xxx            | [e2a5a3b1d0](https://linux-hardware.org/?probe=e2a5a3b1d0) | Aug 23, 2023 |
| Dell          | Inspiron 1525               | [6c4e1108c1](https://linux-hardware.org/?probe=6c4e1108c1) | Aug 23, 2023 |
| Acer          | TravelMate 7730G            | [e286f4c997](https://linux-hardware.org/?probe=e286f4c997) | Aug 23, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [df9818b791](https://linux-hardware.org/?probe=df9818b791) | Aug 23, 2023 |
| Yadro Clie... | KVADRA LE15T                | [985b61f2b2](https://linux-hardware.org/?probe=985b61f2b2) | Aug 23, 2023 |
| HP            | Pavilion dm4                | [36ad86af35](https://linux-hardware.org/?probe=36ad86af35) | Aug 22, 2023 |
| HP            | Laptop 17-cp3xxx            | [d5c63b82fb](https://linux-hardware.org/?probe=d5c63b82fb) | Aug 22, 2023 |
| Dell          | XPS 15 9500                 | [23474c1faa](https://linux-hardware.org/?probe=23474c1faa) | Aug 22, 2023 |
| COLORFUL      | X15 XS 22                   | [2e8aa13f76](https://linux-hardware.org/?probe=2e8aa13f76) | Aug 22, 2023 |
| Apple         | MacBookAir6,2               | [ec3c1320fd](https://linux-hardware.org/?probe=ec3c1320fd) | Aug 22, 2023 |
| Acer          | Swift SF314-512             | [fce52ede18](https://linux-hardware.org/?probe=fce52ede18) | Aug 22, 2023 |
| HUAWEI        | BoDE-WXX9                   | [d23fefd908](https://linux-hardware.org/?probe=d23fefd908) | Aug 22, 2023 |
| HUAWEI        | BOD-WXX9                    | [a1d2ccf421](https://linux-hardware.org/?probe=a1d2ccf421) | Aug 22, 2023 |
| Lenovo        | ThinkPad T470s 20HGS09L2... | [55974065ac](https://linux-hardware.org/?probe=55974065ac) | Aug 22, 2023 |
| Acer          | Aspire E1-531               | [ca5348bd31](https://linux-hardware.org/?probe=ca5348bd31) | Aug 22, 2023 |
| Dell          | Precision M4800             | [195210825b](https://linux-hardware.org/?probe=195210825b) | Aug 22, 2023 |
| Lenovo        | ThinkPad E490 20N8001BUS    | [85d80ec89f](https://linux-hardware.org/?probe=85d80ec89f) | Aug 22, 2023 |
| Apple         | MacBookPro11,4              | [11416c14af](https://linux-hardware.org/?probe=11416c14af) | Aug 22, 2023 |
| Dynabook      | Satellite Pro C50-E-11F     | [b8955c7cf1](https://linux-hardware.org/?probe=b8955c7cf1) | Aug 22, 2023 |
| Dell          | Latitude E7270              | [9eaaeb2503](https://linux-hardware.org/?probe=9eaaeb2503) | Aug 22, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [1b985f59a1](https://linux-hardware.org/?probe=1b985f59a1) | Aug 21, 2023 |
| HP            | Pavilion 15                 | [383fdac352](https://linux-hardware.org/?probe=383fdac352) | Aug 21, 2023 |
| HP            | Pavilion dv9500             | [d5cc7639c3](https://linux-hardware.org/?probe=d5cc7639c3) | Aug 21, 2023 |
| Medion        | Akoya P7818                 | [770447675e](https://linux-hardware.org/?probe=770447675e) | Aug 21, 2023 |
| Acer          | TravelMate P215-52G         | [e8673e8d9c](https://linux-hardware.org/?probe=e8673e8d9c) | Aug 21, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [7975d95ea8](https://linux-hardware.org/?probe=7975d95ea8) | Aug 21, 2023 |
| Timi          | TM1703                      | [cf53d04c5f](https://linux-hardware.org/?probe=cf53d04c5f) | Aug 21, 2023 |
| Acer          | Swift SF314-512             | [9cd3fa37a0](https://linux-hardware.org/?probe=9cd3fa37a0) | Aug 21, 2023 |
| Acer          | Aspire 5755G                | [e1a9713e26](https://linux-hardware.org/?probe=e1a9713e26) | Aug 21, 2023 |
| Dell          | Inspiron 16 Plus 7620       | [b15b51b481](https://linux-hardware.org/?probe=b15b51b481) | Aug 21, 2023 |
| Medion        | Akoya THE TOUCH 10          | [c121ae9a76](https://linux-hardware.org/?probe=c121ae9a76) | Aug 21, 2023 |
| Lenovo        | ThinkPad T430 2349UKM       | [ad27162219](https://linux-hardware.org/?probe=ad27162219) | Aug 21, 2023 |
| Dell          | Latitude E7440              | [edae1bc7d3](https://linux-hardware.org/?probe=edae1bc7d3) | Aug 21, 2023 |
| Google        | Shyvana                     | [eb07bd67db](https://linux-hardware.org/?probe=eb07bd67db) | Aug 21, 2023 |
| Acer          | Aspire A515-56              | [4253b4a27e](https://linux-hardware.org/?probe=4253b4a27e) | Aug 21, 2023 |
| HP            | Pavilion Laptop 15-cc5xx    | [d39c6a5d81](https://linux-hardware.org/?probe=d39c6a5d81) | Aug 21, 2023 |
| Lenovo        | ThinkPad X220 42902WU       | [9fd887dc27](https://linux-hardware.org/?probe=9fd887dc27) | Aug 21, 2023 |
| Lenovo        | ThinkPad X230 23243VG       | [be77bad24e](https://linux-hardware.org/?probe=be77bad24e) | Aug 21, 2023 |
| Acer          | Aspire 7750G                | [0bf0d8e338](https://linux-hardware.org/?probe=0bf0d8e338) | Aug 21, 2023 |
| ASUSTek       | ASUSLaptop_Q540VJ           | [3e90075bb2](https://linux-hardware.org/?probe=3e90075bb2) | Aug 20, 2023 |
| Pegatron      | A15                         | [624757036f](https://linux-hardware.org/?probe=624757036f) | Aug 20, 2023 |
| Dell          | Inspiron 15 3520            | [bd2639e592](https://linux-hardware.org/?probe=bd2639e592) | Aug 20, 2023 |
| Apple         | MacBookPro13,3              | [7b2cc4a14c](https://linux-hardware.org/?probe=7b2cc4a14c) | Aug 20, 2023 |
| HP            | 250 G8 Notebook PC          | [41462b9338](https://linux-hardware.org/?probe=41462b9338) | Aug 20, 2023 |
| Lenovo        | Legion R9000P2021H 82JQ     | [30f233a018](https://linux-hardware.org/?probe=30f233a018) | Aug 20, 2023 |
| HP            | Pavilion g6                 | [45830a7769](https://linux-hardware.org/?probe=45830a7769) | Aug 20, 2023 |
| Acer          | Aspire V3-771               | [ccbacb7123](https://linux-hardware.org/?probe=ccbacb7123) | Aug 20, 2023 |
| Dell          | Vostro 15 5510              | [10dca460fd](https://linux-hardware.org/?probe=10dca460fd) | Aug 20, 2023 |
| HP            | Pavilion g6                 | [d4ba2c046d](https://linux-hardware.org/?probe=d4ba2c046d) | Aug 20, 2023 |
| ASUSTek       | ROG Strix G712LU            | [7fd51c6d4d](https://linux-hardware.org/?probe=7fd51c6d4d) | Aug 20, 2023 |
| HUAWEI        | BOD-WXX9                    | [a3dc3ffc3b](https://linux-hardware.org/?probe=a3dc3ffc3b) | Aug 20, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [8838204e5f](https://linux-hardware.org/?probe=8838204e5f) | Aug 20, 2023 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | [681310709d](https://linux-hardware.org/?probe=681310709d) | Aug 19, 2023 |
| HUAWEI        | BOD-WXX9                    | [dc1060bc0d](https://linux-hardware.org/?probe=dc1060bc0d) | Aug 19, 2023 |
| HUAWEI        | BOD-WXX9                    | [74c4c66eba](https://linux-hardware.org/?probe=74c4c66eba) | Aug 19, 2023 |
| ASUSTek       | X510UQ                      | [169472a4fa](https://linux-hardware.org/?probe=169472a4fa) | Aug 19, 2023 |
| Toshiba       | Satellite Pro A50-C         | [ed71bba366](https://linux-hardware.org/?probe=ed71bba366) | Aug 19, 2023 |
| Lenovo        | ThinkPad E470 20H2S0XB00    | [517d8c57d2](https://linux-hardware.org/?probe=517d8c57d2) | Aug 19, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [a665e45380](https://linux-hardware.org/?probe=a665e45380) | Aug 19, 2023 |
| Dell          | Precision 7740              | [e386da5d08](https://linux-hardware.org/?probe=e386da5d08) | Aug 19, 2023 |
| Lenovo        | Legion Y7000P IRH8 82YA     | [70062471e2](https://linux-hardware.org/?probe=70062471e2) | Aug 19, 2023 |
| Dell          | Inspiron 5447               | [07a24f8880](https://linux-hardware.org/?probe=07a24f8880) | Aug 19, 2023 |
| HUAWEI        | BoDE-WXX9                   | [0a747fe196](https://linux-hardware.org/?probe=0a747fe196) | Aug 19, 2023 |
| Acer          | Aspire A715-51G             | [19ecc69fc4](https://linux-hardware.org/?probe=19ecc69fc4) | Aug 19, 2023 |
| HP            | 255 G8 Notebook PC          | [79af5911ee](https://linux-hardware.org/?probe=79af5911ee) | Aug 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [1f1ce97787](https://linux-hardware.org/?probe=1f1ce97787) | Aug 19, 2023 |
| Apple         | MacBookAir6,2               | [d172fc10d8](https://linux-hardware.org/?probe=d172fc10d8) | Aug 19, 2023 |
| Lenovo        | ThinkPad T420 4177Q5U       | [28a17aaa12](https://linux-hardware.org/?probe=28a17aaa12) | Aug 19, 2023 |
| Acer          | Aspire A515-56              | [97a87f1178](https://linux-hardware.org/?probe=97a87f1178) | Aug 19, 2023 |
| Dell          | Latitude E6330              | [7e196f2365](https://linux-hardware.org/?probe=7e196f2365) | Aug 19, 2023 |
| HP            | 2000                        | [650a9a885c](https://linux-hardware.org/?probe=650a9a885c) | Aug 19, 2023 |
| Samsung       | 300E5M/300E5L               | [e625280525](https://linux-hardware.org/?probe=e625280525) | Aug 19, 2023 |
| HUAWEI        | FRD-WX9                     | [678a3a9328](https://linux-hardware.org/?probe=678a3a9328) | Aug 19, 2023 |
| Lenovo        | ThinkPad T450 20BUS5W000    | [cb1eebf517](https://linux-hardware.org/?probe=cb1eebf517) | Aug 19, 2023 |
| Lenovo        | ThinkPad T450 20BUS5W000    | [87d16e9431](https://linux-hardware.org/?probe=87d16e9431) | Aug 19, 2023 |
| HP            | 255 G4 Notebook PC          | [fddebe6ccb](https://linux-hardware.org/?probe=fddebe6ccb) | Aug 19, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [f5751cb101](https://linux-hardware.org/?probe=f5751cb101) | Aug 19, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [800ad97443](https://linux-hardware.org/?probe=800ad97443) | Aug 19, 2023 |
| Toshiba       | Satellite C870-19R          | [f351a7a707](https://linux-hardware.org/?probe=f351a7a707) | Aug 19, 2023 |
| Timi          | RedmiBook Pro 14S           | [323664ecb8](https://linux-hardware.org/?probe=323664ecb8) | Aug 18, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QTCT... | [0c47627604](https://linux-hardware.org/?probe=0c47627604) | Aug 18, 2023 |
| Dell          | Precision M4700             | [50cb31f3c0](https://linux-hardware.org/?probe=50cb31f3c0) | Aug 18, 2023 |
| Dell          | Inspiron 5570               | [ba1391d85a](https://linux-hardware.org/?probe=ba1391d85a) | Aug 18, 2023 |
| Dell          | Latitude 5420               | [6a758f4880](https://linux-hardware.org/?probe=6a758f4880) | Aug 18, 2023 |
| Dell          | Latitude 7300               | [607cb8c677](https://linux-hardware.org/?probe=607cb8c677) | Aug 18, 2023 |
| Infinix       | INBOOK X1 NEO               | [bb08f7158b](https://linux-hardware.org/?probe=bb08f7158b) | Aug 18, 2023 |
| Toshiba       | Satellite C870-19R          | [f906e0ccdb](https://linux-hardware.org/?probe=f906e0ccdb) | Aug 18, 2023 |
| HP            | EliteBook 2540p             | [dc150253e5](https://linux-hardware.org/?probe=dc150253e5) | Aug 18, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [6fb9870620](https://linux-hardware.org/?probe=6fb9870620) | Aug 18, 2023 |
| MSI           | Katana GF76 11UD            | [17bc04111e](https://linux-hardware.org/?probe=17bc04111e) | Aug 17, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [fb2095ddea](https://linux-hardware.org/?probe=fb2095ddea) | Aug 17, 2023 |
| HP            | EliteBook 8540p             | [ab0d47228c](https://linux-hardware.org/?probe=ab0d47228c) | Aug 17, 2023 |
| ASUSTek       | X75VD                       | [b07665aa45](https://linux-hardware.org/?probe=b07665aa45) | Aug 17, 2023 |
| Dell          | Latitude 5420               | [4656cc9656](https://linux-hardware.org/?probe=4656cc9656) | Aug 17, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HM... | [d3eadf71c1](https://linux-hardware.org/?probe=d3eadf71c1) | Aug 17, 2023 |
| Lenovo        | ThinkPad T490 20N3S79M38    | [cb5346a558](https://linux-hardware.org/?probe=cb5346a558) | Aug 17, 2023 |
| Lenovo        | ThinkPad T490 20N3S79M38    | [4bfb2c68ca](https://linux-hardware.org/?probe=4bfb2c68ca) | Aug 17, 2023 |
| MSI           | Cyborg 15 A12VF             | [b80142953c](https://linux-hardware.org/?probe=b80142953c) | Aug 17, 2023 |
| MSI           | Cyborg 15 A12VF             | [1ba4da3bec](https://linux-hardware.org/?probe=1ba4da3bec) | Aug 17, 2023 |
| Schenker      | XMG CORE 15(M20, RTX 206... | [81dcd4b2dd](https://linux-hardware.org/?probe=81dcd4b2dd) | Aug 17, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [dbee57dbed](https://linux-hardware.org/?probe=dbee57dbed) | Aug 17, 2023 |
| Acer          | Aspire E5-571               | [8a924c30e6](https://linux-hardware.org/?probe=8a924c30e6) | Aug 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [145e7ceb96](https://linux-hardware.org/?probe=145e7ceb96) | Aug 16, 2023 |
| HP            | Notebook                    | [dd8c90afbe](https://linux-hardware.org/?probe=dd8c90afbe) | Aug 16, 2023 |
| ASUSTek       | UX331UA                     | [b48511c64c](https://linux-hardware.org/?probe=b48511c64c) | Aug 16, 2023 |
| HP            | Pavilion g7                 | [403fee3152](https://linux-hardware.org/?probe=403fee3152) | Aug 16, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [3a916bde7d](https://linux-hardware.org/?probe=3a916bde7d) | Aug 16, 2023 |
| Toshiba       | Satellite C660              | [8bc67959d1](https://linux-hardware.org/?probe=8bc67959d1) | Aug 16, 2023 |
| Dell          | XPS 9320                    | [f9d12ed2ff](https://linux-hardware.org/?probe=f9d12ed2ff) | Aug 16, 2023 |
| HP            | Pavilion dv6                | [ee8c1f96e8](https://linux-hardware.org/?probe=ee8c1f96e8) | Aug 16, 2023 |
| Dell          | Latitude 7300               | [07c0414596](https://linux-hardware.org/?probe=07c0414596) | Aug 16, 2023 |
| MSI           | Katana GF66 11UC            | [927eacb30f](https://linux-hardware.org/?probe=927eacb30f) | Aug 16, 2023 |
| HP            | Notebook                    | [bc495ab997](https://linux-hardware.org/?probe=bc495ab997) | Aug 16, 2023 |
| HP            | EliteBook 830 G5            | [9dee158ae4](https://linux-hardware.org/?probe=9dee158ae4) | Aug 16, 2023 |
| Dell          | XPS 13 9370                 | [987d48d494](https://linux-hardware.org/?probe=987d48d494) | Aug 16, 2023 |
| Schenker      | XMG CORE 15(M20, RTX 206... | [ca4998e0fe](https://linux-hardware.org/?probe=ca4998e0fe) | Aug 16, 2023 |
| ASUSTek       | ZenBook Pro Duo UX582ZM_... | [b3f31fbc53](https://linux-hardware.org/?probe=b3f31fbc53) | Aug 16, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | [859e36f237](https://linux-hardware.org/?probe=859e36f237) | Aug 16, 2023 |
| Dell          | Precision 5520              | [0516c33229](https://linux-hardware.org/?probe=0516c33229) | Aug 16, 2023 |
| Dell          | Precision 5520              | [b9a35fa791](https://linux-hardware.org/?probe=b9a35fa791) | Aug 16, 2023 |
| Lenovo        | ThinkPad T495s 20QJ001MG... | [3ac30cf2d0](https://linux-hardware.org/?probe=3ac30cf2d0) | Aug 16, 2023 |
| Samsung       | RC530/RC730                 | [f9ce7b0ef5](https://linux-hardware.org/?probe=f9ce7b0ef5) | Aug 15, 2023 |
| Dell          | Latitude 7390               | [1eb393619c](https://linux-hardware.org/?probe=1eb393619c) | Aug 15, 2023 |
| Samsung       | RC530/RC730                 | [86f3ddda0c](https://linux-hardware.org/?probe=86f3ddda0c) | Aug 15, 2023 |
| HP            | Laptop 15-da0xxx            | [9ec3d164a6](https://linux-hardware.org/?probe=9ec3d164a6) | Aug 15, 2023 |
| HP            | Laptop 15-da0xxx            | [7f32d40a19](https://linux-hardware.org/?probe=7f32d40a19) | Aug 15, 2023 |
| HP            | OMEN by Gaming Laptop 16... | [253750d7f8](https://linux-hardware.org/?probe=253750d7f8) | Aug 15, 2023 |
| Lenovo        | IdeaPad 520S-14IKB 81BL     | [a69ad2f7b8](https://linux-hardware.org/?probe=a69ad2f7b8) | Aug 15, 2023 |
| Panasonic     | CF-31BAAAZ2M                | [cb0bd3b9b9](https://linux-hardware.org/?probe=cb0bd3b9b9) | Aug 15, 2023 |
| Sony          | VPCEH3N6E                   | [884688ddbf](https://linux-hardware.org/?probe=884688ddbf) | Aug 15, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BS... | [ac119d72bb](https://linux-hardware.org/?probe=ac119d72bb) | Aug 15, 2023 |
| MSI           | Katana GF76 11UD            | [31beedbfba](https://linux-hardware.org/?probe=31beedbfba) | Aug 15, 2023 |
| Lenovo        | Legion Y740-15IRH 81UF      | [2b0ec42ffb](https://linux-hardware.org/?probe=2b0ec42ffb) | Aug 15, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [dd9b3b469e](https://linux-hardware.org/?probe=dd9b3b469e) | Aug 15, 2023 |
| Lenovo        | Yoga 700-14ISK 80QD         | [71360c6f07](https://linux-hardware.org/?probe=71360c6f07) | Aug 15, 2023 |
| Acer          | Aspire A315-33              | [19221dff96](https://linux-hardware.org/?probe=19221dff96) | Aug 15, 2023 |
| Apple         | MacBookAir6,2               | [18060bdbd7](https://linux-hardware.org/?probe=18060bdbd7) | Aug 14, 2023 |
| Acer          | Aspire A515-57G             | [5a2c741f84](https://linux-hardware.org/?probe=5a2c741f84) | Aug 14, 2023 |
| Dell          | XPS 13 9343                 | [41bbf2a956](https://linux-hardware.org/?probe=41bbf2a956) | Aug 14, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [8a3dc0d427](https://linux-hardware.org/?probe=8a3dc0d427) | Aug 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [c7669273cb](https://linux-hardware.org/?probe=c7669273cb) | Aug 14, 2023 |
| ASUSTek       | TUF Gaming FX705DY_FX705... | [4062060fba](https://linux-hardware.org/?probe=4062060fba) | Aug 14, 2023 |
| Positivo      | N1250                       | [8c1d1f89f7](https://linux-hardware.org/?probe=8c1d1f89f7) | Aug 14, 2023 |
| Positivo      | N1250                       | [17ce4f01a7](https://linux-hardware.org/?probe=17ce4f01a7) | Aug 14, 2023 |
| Dell          | Latitude E5570              | [46b35ff7e0](https://linux-hardware.org/?probe=46b35ff7e0) | Aug 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [15b52f0cde](https://linux-hardware.org/?probe=15b52f0cde) | Aug 14, 2023 |
| Dell          | Inspiron 15-7568            | [f9341607f1](https://linux-hardware.org/?probe=f9341607f1) | Aug 14, 2023 |
| Acer          | Aspire E1-571               | [0afd683e48](https://linux-hardware.org/?probe=0afd683e48) | Aug 13, 2023 |
| Tactus        | GeoBook 110                 | [b6897622f2](https://linux-hardware.org/?probe=b6897622f2) | Aug 13, 2023 |
| Dell          | Latitude E6520              | [4dea72e249](https://linux-hardware.org/?probe=4dea72e249) | Aug 13, 2023 |
| Dell          | Inspiron 3593               | [2b41347ea6](https://linux-hardware.org/?probe=2b41347ea6) | Aug 13, 2023 |
| Dell          | XPS 13 7390                 | [f4e6886bd8](https://linux-hardware.org/?probe=f4e6886bd8) | Aug 13, 2023 |
| HP            | Pavilion Laptop 15-cc5xx    | [49d9838f26](https://linux-hardware.org/?probe=49d9838f26) | Aug 13, 2023 |
| Dell          | Latitude E7450              | [9d787db93a](https://linux-hardware.org/?probe=9d787db93a) | Aug 13, 2023 |
| Allview       | Allbook H                   | [1a8e5e7f8f](https://linux-hardware.org/?probe=1a8e5e7f8f) | Aug 13, 2023 |
| Novatech      | 15.6 nSpire Laptop          | [cd8b4a2836](https://linux-hardware.org/?probe=cd8b4a2836) | Aug 13, 2023 |
| Acer          | Predator G5-793             | [bb25759563](https://linux-hardware.org/?probe=bb25759563) | Aug 13, 2023 |
| Medion        | Akoya THE TOUCH 10          | [488c1edd8d](https://linux-hardware.org/?probe=488c1edd8d) | Aug 13, 2023 |
| MSI           | GF63 Thin 10SC              | [f98e22f722](https://linux-hardware.org/?probe=f98e22f722) | Aug 13, 2023 |
| Acer          | Aspire 7560G                | [a4a5ddf1b0](https://linux-hardware.org/?probe=a4a5ddf1b0) | Aug 13, 2023 |
| MSI           | Katana GF66 11UD            | [e7e9bfd605](https://linux-hardware.org/?probe=e7e9bfd605) | Aug 13, 2023 |
| Lenovo        | V130-15IKB 81HN             | [ca2c61168c](https://linux-hardware.org/?probe=ca2c61168c) | Aug 13, 2023 |
| Lenovo        | IdeaPad 1 14ALC7 82R3       | [0766dc4b96](https://linux-hardware.org/?probe=0766dc4b96) | Aug 13, 2023 |
| Lenovo        | IdeaPad 1 14ALC7 82R3       | [6480e1b649](https://linux-hardware.org/?probe=6480e1b649) | Aug 13, 2023 |
| Dell          | XPS M1530                   | [f2cc56bc67](https://linux-hardware.org/?probe=f2cc56bc67) | Aug 13, 2023 |
| Dell          | Inspiron 5537               | [d978d063e8](https://linux-hardware.org/?probe=d978d063e8) | Aug 13, 2023 |
| HP            | EliteBook 8560w             | [dfdde7225d](https://linux-hardware.org/?probe=dfdde7225d) | Aug 13, 2023 |
| Acer          | Aspire 5750G                | [009242b925](https://linux-hardware.org/?probe=009242b925) | Aug 13, 2023 |
| Acer          | Aspire 7520                 | [7e84fe60a8](https://linux-hardware.org/?probe=7e84fe60a8) | Aug 13, 2023 |
| Lenovo        | G505s 20255                 | [9e0052d329](https://linux-hardware.org/?probe=9e0052d329) | Aug 12, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [bb650e1dd2](https://linux-hardware.org/?probe=bb650e1dd2) | Aug 12, 2023 |
| Lenovo        | ThinkPad T490 20N3S8FN0F    | [cff61d75ae](https://linux-hardware.org/?probe=cff61d75ae) | Aug 12, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | [4ba417ade2](https://linux-hardware.org/?probe=4ba417ade2) | Aug 12, 2023 |
| BANGHO        | BES T5                      | [9631e13d8b](https://linux-hardware.org/?probe=9631e13d8b) | Aug 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [4404dc3287](https://linux-hardware.org/?probe=4404dc3287) | Aug 12, 2023 |
| Alienware     | x16 R1                      | [889b7e32ff](https://linux-hardware.org/?probe=889b7e32ff) | Aug 12, 2023 |
| HP            | ProBook 6560b               | [01c0e5d78c](https://linux-hardware.org/?probe=01c0e5d78c) | Aug 12, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [fb024a9374](https://linux-hardware.org/?probe=fb024a9374) | Aug 12, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [398f85e94a](https://linux-hardware.org/?probe=398f85e94a) | Aug 12, 2023 |
| Toshiba       | Satellite C50D-A-13G        | [e1a3542078](https://linux-hardware.org/?probe=e1a3542078) | Aug 12, 2023 |
| Dell          | G3 3579                     | [09ba53e3c1](https://linux-hardware.org/?probe=09ba53e3c1) | Aug 12, 2023 |
| HP            | Pavilion g7                 | [325b804863](https://linux-hardware.org/?probe=325b804863) | Aug 12, 2023 |
| ASUSTek       | T200TA                      | [24d6504b2c](https://linux-hardware.org/?probe=24d6504b2c) | Aug 12, 2023 |
| HP            | Laptop 15-dy2xxx            | [bc66f59ac5](https://linux-hardware.org/?probe=bc66f59ac5) | Aug 12, 2023 |
| HP            | EliteBook 840 14 inch G1... | [73b7fc1fc9](https://linux-hardware.org/?probe=73b7fc1fc9) | Aug 11, 2023 |
| Acer          | Aspire F5-573G              | [019f3a6d1f](https://linux-hardware.org/?probe=019f3a6d1f) | Aug 11, 2023 |
| Acer          | Extensa 215-55              | [aea9ada5e8](https://linux-hardware.org/?probe=aea9ada5e8) | Aug 11, 2023 |
| Dell          | Latitude E6430              | [79f523548b](https://linux-hardware.org/?probe=79f523548b) | Aug 11, 2023 |
| Dell          | Latitude E6330              | [b3081e041e](https://linux-hardware.org/?probe=b3081e041e) | Aug 11, 2023 |
| Dell          | Latitude E6430              | [fd3c9b15f8](https://linux-hardware.org/?probe=fd3c9b15f8) | Aug 11, 2023 |
| Lenovo        | ThinkPad L520 5017BW5       | [1a9bbdc058](https://linux-hardware.org/?probe=1a9bbdc058) | Aug 11, 2023 |
| Dell          | G15 5520                    | [3bec284af8](https://linux-hardware.org/?probe=3bec284af8) | Aug 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | [a4a009cd79](https://linux-hardware.org/?probe=a4a009cd79) | Aug 11, 2023 |
| Acer          | Extensa 215-55              | [036866525c](https://linux-hardware.org/?probe=036866525c) | Aug 11, 2023 |
| Acer          | Aspire ES1-111M             | [3c7140c389](https://linux-hardware.org/?probe=3c7140c389) | Aug 11, 2023 |
| Intel Clie... | LAPQC71A                    | [c87bff1d43](https://linux-hardware.org/?probe=c87bff1d43) | Aug 11, 2023 |
| Fujitsu       | LIFEBOOK S762               | [1ced8ae4d0](https://linux-hardware.org/?probe=1ced8ae4d0) | Aug 11, 2023 |
| Fujitsu       | LIFEBOOK S762               | [cb0b5cbd5d](https://linux-hardware.org/?probe=cb0b5cbd5d) | Aug 11, 2023 |
| MSI           | Creator Z16 A11UET          | [7883e9a69d](https://linux-hardware.org/?probe=7883e9a69d) | Aug 11, 2023 |
| Lenovo        | B50-70 20384                | [607103b8f5](https://linux-hardware.org/?probe=607103b8f5) | Aug 11, 2023 |
| Google        | Bobba360                    | [128700115a](https://linux-hardware.org/?probe=128700115a) | Aug 10, 2023 |
| Lenovo        | G40-45 80E1                 | [d6f18c79f6](https://linux-hardware.org/?probe=d6f18c79f6) | Aug 10, 2023 |
| HUAWEI        | KLVD-WXX9                   | [19cadaab1b](https://linux-hardware.org/?probe=19cadaab1b) | Aug 10, 2023 |
| Lenovo        | ThinkPad E14 20RA0076US     | [ab98272b50](https://linux-hardware.org/?probe=ab98272b50) | Aug 10, 2023 |
| Gateway       | MD7309U                     | [18dbacfdab](https://linux-hardware.org/?probe=18dbacfdab) | Aug 10, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [9627b6d632](https://linux-hardware.org/?probe=9627b6d632) | Aug 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [ffa9b97bf7](https://linux-hardware.org/?probe=ffa9b97bf7) | Aug 10, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [099d1ac0de](https://linux-hardware.org/?probe=099d1ac0de) | Aug 10, 2023 |
| BANGHO        | MAX L5                      | [4661b7a0f7](https://linux-hardware.org/?probe=4661b7a0f7) | Aug 10, 2023 |
| Avell High... | A70 HYB                     | [9b03ae1cd3](https://linux-hardware.org/?probe=9b03ae1cd3) | Aug 10, 2023 |
| HP            | Pavilion Laptop 14-dv2xx... | [479f066821](https://linux-hardware.org/?probe=479f066821) | Aug 10, 2023 |
| Avell         | A70 ION                     | [b71c176ce3](https://linux-hardware.org/?probe=b71c176ce3) | Aug 10, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [e323e9cd7e](https://linux-hardware.org/?probe=e323e9cd7e) | Aug 10, 2023 |
| Dell          | XPS L421X                   | [ba412a439b](https://linux-hardware.org/?probe=ba412a439b) | Aug 10, 2023 |
| Google        | Kindred                     | [a45439e295](https://linux-hardware.org/?probe=a45439e295) | Aug 10, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | [385c88301b](https://linux-hardware.org/?probe=385c88301b) | Aug 10, 2023 |
| Dell          | Vostro 3501                 | [d606f83745](https://linux-hardware.org/?probe=d606f83745) | Aug 10, 2023 |
| Gateway       | NV57H                       | [826aaf5dd8](https://linux-hardware.org/?probe=826aaf5dd8) | Aug 10, 2023 |
| Lenovo        | ThinkPad E15 20RD0086UE     | [cb8ad3e0fc](https://linux-hardware.org/?probe=cb8ad3e0fc) | Aug 10, 2023 |
| Acer          | Aspire V3-571G              | [6c4354fa1c](https://linux-hardware.org/?probe=6c4354fa1c) | Aug 10, 2023 |
| Siragon       | MN-50                       | [8eafa43cb5](https://linux-hardware.org/?probe=8eafa43cb5) | Aug 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X321... | [204b2fa0a0](https://linux-hardware.org/?probe=204b2fa0a0) | Aug 09, 2023 |
| Lenovo        | V145-15AST 81MT             | [304b175b3c](https://linux-hardware.org/?probe=304b175b3c) | Aug 09, 2023 |
| Toshiba       | Satellite C70D-B            | [ac775a3228](https://linux-hardware.org/?probe=ac775a3228) | Aug 09, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [bf81bbf7b4](https://linux-hardware.org/?probe=bf81bbf7b4) | Aug 09, 2023 |
| Google        | Bobba360                    | [fa4a78b024](https://linux-hardware.org/?probe=fa4a78b024) | Aug 09, 2023 |
| Medion        | Akoya THE TOUCH 10          | [d45603bb4e](https://linux-hardware.org/?probe=d45603bb4e) | Aug 09, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [5bd12768fa](https://linux-hardware.org/?probe=5bd12768fa) | Aug 09, 2023 |
| Toshiba       | Satellite C70D-B            | [e3f3b2fcfb](https://linux-hardware.org/?probe=e3f3b2fcfb) | Aug 09, 2023 |
| HP            | EliteBook 830 G8 Noteboo... | [5e79da69ed](https://linux-hardware.org/?probe=5e79da69ed) | Aug 09, 2023 |
| Dell          | Latitude 5520               | [478f0a6a07](https://linux-hardware.org/?probe=478f0a6a07) | Aug 09, 2023 |
| HP            | EliteBook 830 G8 Noteboo... | [c761edfea1](https://linux-hardware.org/?probe=c761edfea1) | Aug 09, 2023 |
| Dell          | XPS 15 9520                 | [0620b6b11a](https://linux-hardware.org/?probe=0620b6b11a) | Aug 09, 2023 |
| HP            | EliteBook 8470p             | [16acf13ed8](https://linux-hardware.org/?probe=16acf13ed8) | Aug 09, 2023 |
| HP            | EliteBook 2540p             | [2a02492c01](https://linux-hardware.org/?probe=2a02492c01) | Aug 09, 2023 |
| Dell          | Precision 3551              | [a9b776ade0](https://linux-hardware.org/?probe=a9b776ade0) | Aug 09, 2023 |
| HP            | EliteBook 2540p             | [509b979b88](https://linux-hardware.org/?probe=509b979b88) | Aug 09, 2023 |
| HP            | EliteBook 8560w             | [ea34946fbd](https://linux-hardware.org/?probe=ea34946fbd) | Aug 09, 2023 |
| Toshiba       | Satellite C55-C             | [199924c140](https://linux-hardware.org/?probe=199924c140) | Aug 09, 2023 |
| HP            | ENVY Laptop 17-ch0xxx       | [01fe285324](https://linux-hardware.org/?probe=01fe285324) | Aug 09, 2023 |
| Toshiba       | Satellite C55-C             | [324b952d6b](https://linux-hardware.org/?probe=324b952d6b) | Aug 09, 2023 |
| ASUSTek       | N56VJ                       | [d552e1a450](https://linux-hardware.org/?probe=d552e1a450) | Aug 08, 2023 |
| BANGHO        | MAX L5                      | [b21781af81](https://linux-hardware.org/?probe=b21781af81) | Aug 08, 2023 |
| HP            | EliteBook 820 G1            | [62889fd683](https://linux-hardware.org/?probe=62889fd683) | Aug 08, 2023 |
| Lenovo        | ThinkPad P50 20EQS0T800     | [8316628b28](https://linux-hardware.org/?probe=8316628b28) | Aug 08, 2023 |
| Lenovo        | ThinkPad P50 20EQS0T800     | [05d33f11b5](https://linux-hardware.org/?probe=05d33f11b5) | Aug 08, 2023 |
| Notebook      | W65_W67RZ1                  | [ab4b3c8f47](https://linux-hardware.org/?probe=ab4b3c8f47) | Aug 08, 2023 |
| HP            | ZBook 14 G2                 | [c52b1e963f](https://linux-hardware.org/?probe=c52b1e963f) | Aug 08, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [f69459e15a](https://linux-hardware.org/?probe=f69459e15a) | Aug 08, 2023 |
| Dell          | Latitude 7440               | [0cfa45fbd8](https://linux-hardware.org/?probe=0cfa45fbd8) | Aug 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [4148b505d6](https://linux-hardware.org/?probe=4148b505d6) | Aug 08, 2023 |
| Dell          | Latitude 7440               | [e476a3e532](https://linux-hardware.org/?probe=e476a3e532) | Aug 08, 2023 |
| Dell          | Latitude E7450              | [a426887b24](https://linux-hardware.org/?probe=a426887b24) | Aug 08, 2023 |
| HP            | ZBook 14 G2                 | [211978450c](https://linux-hardware.org/?probe=211978450c) | Aug 08, 2023 |
| HP            | ZBook 14 G2                 | [23dd3e572c](https://linux-hardware.org/?probe=23dd3e572c) | Aug 08, 2023 |
| Dell          | Latitude 5540               | [08c875f58b](https://linux-hardware.org/?probe=08c875f58b) | Aug 08, 2023 |
| MSI           | Creator Z16 A11UET          | [ea05388cf5](https://linux-hardware.org/?probe=ea05388cf5) | Aug 08, 2023 |
| Dell          | Inspiron 5402               | [9004ee7aa2](https://linux-hardware.org/?probe=9004ee7aa2) | Aug 08, 2023 |
| Lenovo        | B40-80 80LS                 | [2865a9d402](https://linux-hardware.org/?probe=2865a9d402) | Aug 08, 2023 |
| Lenovo        | Legion 5 15ARH7H 82RD       | [1e2412e487](https://linux-hardware.org/?probe=1e2412e487) | Aug 08, 2023 |
| Dell          | Latitude E6430              | [313d3616c4](https://linux-hardware.org/?probe=313d3616c4) | Aug 08, 2023 |
| Google        | Parrot                      | [a0820a5e0c](https://linux-hardware.org/?probe=a0820a5e0c) | Aug 07, 2023 |
| Google        | Parrot                      | [f03c4efc0b](https://linux-hardware.org/?probe=f03c4efc0b) | Aug 07, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [ce593ff6c7](https://linux-hardware.org/?probe=ce593ff6c7) | Aug 07, 2023 |
| Acer          | Aspire A515-56              | [84b0c88b0a](https://linux-hardware.org/?probe=84b0c88b0a) | Aug 07, 2023 |
| MSI           | GL63 8RC                    | [d91d6193e6](https://linux-hardware.org/?probe=d91d6193e6) | Aug 07, 2023 |
| HP            | Notebook                    | [02ceb78a4f](https://linux-hardware.org/?probe=02ceb78a4f) | Aug 07, 2023 |
| Lenovo        | B40-70 20392                | [ebf45c27f4](https://linux-hardware.org/?probe=ebf45c27f4) | Aug 07, 2023 |
| SGIN          | laptop                      | [d80389ea87](https://linux-hardware.org/?probe=d80389ea87) | Aug 07, 2023 |
| Acer          | Swift SF514-53T             | [30d8fefda4](https://linux-hardware.org/?probe=30d8fefda4) | Aug 07, 2023 |
| Acer          | Swift SF514-53T             | [f1cef350fb](https://linux-hardware.org/?probe=f1cef350fb) | Aug 07, 2023 |
| Lenovo        | ThinkPad E14 Gen 5 21JRS... | [ebcf58253e](https://linux-hardware.org/?probe=ebcf58253e) | Aug 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [a3dd4fadf3](https://linux-hardware.org/?probe=a3dd4fadf3) | Aug 07, 2023 |
| Dell          | XPS 13 9350                 | [fb1aaeae43](https://linux-hardware.org/?probe=fb1aaeae43) | Aug 07, 2023 |
| HP            | Laptop 17-ak0xx             | [67749cdc51](https://linux-hardware.org/?probe=67749cdc51) | Aug 07, 2023 |
| Notebook      | NHxxRZQ                     | [0cd17c8b5c](https://linux-hardware.org/?probe=0cd17c8b5c) | Aug 07, 2023 |
| Fujitsu       | LIFEBOOK A359               | [60a09f6ca3](https://linux-hardware.org/?probe=60a09f6ca3) | Aug 07, 2023 |
| Dell          | XPS 15 9500                 | [309b546405](https://linux-hardware.org/?probe=309b546405) | Aug 07, 2023 |
| HP            | Pavilion 15                 | [227895bca8](https://linux-hardware.org/?probe=227895bca8) | Aug 07, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [0b3bf57b84](https://linux-hardware.org/?probe=0b3bf57b84) | Aug 07, 2023 |
| HP            | ProBook 650 G1              | [b02660749d](https://linux-hardware.org/?probe=b02660749d) | Aug 07, 2023 |
| Lenovo        | B40-80 80LS                 | [bfb069ff41](https://linux-hardware.org/?probe=bfb069ff41) | Aug 07, 2023 |
| HP            | EliteBook 840 G3            | [2e239a5f09](https://linux-hardware.org/?probe=2e239a5f09) | Aug 07, 2023 |
| Lenovo        | ThinkPad T480 20L6S42000    | [3e9ce860b6](https://linux-hardware.org/?probe=3e9ce860b6) | Aug 07, 2023 |
| Acer          | Aspire 4750                 | [8491f5fc3b](https://linux-hardware.org/?probe=8491f5fc3b) | Aug 07, 2023 |
| Apple         | MacBookAir6,1               | [acf60b5aa8](https://linux-hardware.org/?probe=acf60b5aa8) | Aug 06, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [32c2f39f3a](https://linux-hardware.org/?probe=32c2f39f3a) | Aug 06, 2023 |
| Acer          | E1-510                      | [2d6776c4fe](https://linux-hardware.org/?probe=2d6776c4fe) | Aug 06, 2023 |
| Notebook      | NS5x_NS7xPU                 | [d71ac9524e](https://linux-hardware.org/?probe=d71ac9524e) | Aug 06, 2023 |
| Dell          | Latitude 5290 2-in-1        | [62e2743cda](https://linux-hardware.org/?probe=62e2743cda) | Aug 06, 2023 |
| HP            | EliteBook 8540p             | [4709894444](https://linux-hardware.org/?probe=4709894444) | Aug 06, 2023 |
| Dell          | Latitude E5540              | [928c427cbc](https://linux-hardware.org/?probe=928c427cbc) | Aug 06, 2023 |
| ASUSTek       | UX32VD                      | [298a3261a0](https://linux-hardware.org/?probe=298a3261a0) | Aug 06, 2023 |
| Lenovo        | B40-70 20392                | [221f9de00a](https://linux-hardware.org/?probe=221f9de00a) | Aug 06, 2023 |
| HP            | EliteBook 840 G4            | [44d851d327](https://linux-hardware.org/?probe=44d851d327) | Aug 06, 2023 |
| HP            | ZBook Firefly 15.6 inch ... | [a3c7d29211](https://linux-hardware.org/?probe=a3c7d29211) | Aug 06, 2023 |
| HP            | EliteBook 840 G5            | [9688966097](https://linux-hardware.org/?probe=9688966097) | Aug 06, 2023 |
| HP            | Laptop 15-db0xxx            | [51442067d5](https://linux-hardware.org/?probe=51442067d5) | Aug 06, 2023 |
| Chuwi         | GemiBook Pro                | [2726702c6a](https://linux-hardware.org/?probe=2726702c6a) | Aug 06, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | [270c9a3ea0](https://linux-hardware.org/?probe=270c9a3ea0) | Aug 06, 2023 |
| Dell          | Inspiron 7572               | [2509709a1e](https://linux-hardware.org/?probe=2509709a1e) | Aug 06, 2023 |
| HP            | Pavilion TS Sleekbook 15    | [8360dc045f](https://linux-hardware.org/?probe=8360dc045f) | Aug 06, 2023 |
| HP            | Pavilion TS Sleekbook 15    | [cad443cf78](https://linux-hardware.org/?probe=cad443cf78) | Aug 06, 2023 |
| Acer          | Aspire 5750G                | [3b589d53bc](https://linux-hardware.org/?probe=3b589d53bc) | Aug 06, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | [db5a797fc0](https://linux-hardware.org/?probe=db5a797fc0) | Aug 06, 2023 |
| Acer          | Nitro AN515-57              | [dbb09ef76f](https://linux-hardware.org/?probe=dbb09ef76f) | Aug 06, 2023 |
| Acer          | Nitro AN515-57              | [0aa699dc73](https://linux-hardware.org/?probe=0aa699dc73) | Aug 06, 2023 |
| Lenovo        | ThinkPad T430 2342CTO       | [96dae933b5](https://linux-hardware.org/?probe=96dae933b5) | Aug 06, 2023 |
| Dell          | Latitude 7480               | [eeb7f6e8fe](https://linux-hardware.org/?probe=eeb7f6e8fe) | Aug 06, 2023 |
| HP            | Laptop 15-db0xxx            | [5889bc8dc7](https://linux-hardware.org/?probe=5889bc8dc7) | Aug 06, 2023 |
| Acer          | Aspire 5551                 | [4db1866796](https://linux-hardware.org/?probe=4db1866796) | Aug 06, 2023 |
| HP            | EliteBook 8560w             | [b2177d3c55](https://linux-hardware.org/?probe=b2177d3c55) | Aug 06, 2023 |
| HP            | Pavilion Laptop 15-cc5xx    | [8baf99b470](https://linux-hardware.org/?probe=8baf99b470) | Aug 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [c8d1e98a60](https://linux-hardware.org/?probe=c8d1e98a60) | Aug 05, 2023 |
| Dell          | Latitude 5410               | [2838e5d74c](https://linux-hardware.org/?probe=2838e5d74c) | Aug 05, 2023 |
| HP            | 15                          | [77ae1d8e7e](https://linux-hardware.org/?probe=77ae1d8e7e) | Aug 05, 2023 |
| Dell          | Inspiron 15 5510            | [6d78d72399](https://linux-hardware.org/?probe=6d78d72399) | Aug 05, 2023 |
| Toshiba       | Satellite C670D-11P         | [a5c49672d6](https://linux-hardware.org/?probe=a5c49672d6) | Aug 05, 2023 |
| Apple         | MacBookPro14,1              | [d3630fa2ed](https://linux-hardware.org/?probe=d3630fa2ed) | Aug 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | [5f516e849d](https://linux-hardware.org/?probe=5f516e849d) | Aug 05, 2023 |
| Chuwi         | CoreBook XPro               | [776bcc618a](https://linux-hardware.org/?probe=776bcc618a) | Aug 05, 2023 |
| HP            | Notebook                    | [d86cc7b5ba](https://linux-hardware.org/?probe=d86cc7b5ba) | Aug 05, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W5... | [e2dee68ce7](https://linux-hardware.org/?probe=e2dee68ce7) | Aug 05, 2023 |
| ALLDOCUBE     | i1502                       | [1ccf0b8f71](https://linux-hardware.org/?probe=1ccf0b8f71) | Aug 05, 2023 |
| HP            | ProBook 450 G5              | [0482630783](https://linux-hardware.org/?probe=0482630783) | Aug 05, 2023 |
| Dell          | Latitude 5421               | [d01013b679](https://linux-hardware.org/?probe=d01013b679) | Aug 05, 2023 |
| Dell          | Latitude 5421               | [5dfde4e6ac](https://linux-hardware.org/?probe=5dfde4e6ac) | Aug 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [8292d9f518](https://linux-hardware.org/?probe=8292d9f518) | Aug 04, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | [ff55512c0e](https://linux-hardware.org/?probe=ff55512c0e) | Aug 04, 2023 |
| Dell          | Latitude E6420              | [4f67a219dc](https://linux-hardware.org/?probe=4f67a219dc) | Aug 04, 2023 |
| HP            | ProBook 450 G8 Notebook ... | [9eac356b0a](https://linux-hardware.org/?probe=9eac356b0a) | Aug 04, 2023 |
| Acer          | Predator PH315-53           | [6c13f7a1f0](https://linux-hardware.org/?probe=6c13f7a1f0) | Aug 04, 2023 |
| HP            | ZHAN 99 Mobile Workstati... | [b3422c4e37](https://linux-hardware.org/?probe=b3422c4e37) | Aug 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [db2732f0e8](https://linux-hardware.org/?probe=db2732f0e8) | Aug 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [7abc08a315](https://linux-hardware.org/?probe=7abc08a315) | Aug 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [87febc0242](https://linux-hardware.org/?probe=87febc0242) | Aug 04, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [2825bbd67b](https://linux-hardware.org/?probe=2825bbd67b) | Aug 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [d8caf086ad](https://linux-hardware.org/?probe=d8caf086ad) | Aug 04, 2023 |
| Dell          | Vostro 15 3510              | [bd994e4cc6](https://linux-hardware.org/?probe=bd994e4cc6) | Aug 04, 2023 |
| Apple         | MacBookPro8,2               | [44f5a672b7](https://linux-hardware.org/?probe=44f5a672b7) | Aug 04, 2023 |
| Medion        | Erazer X7841 MD99556        | [c9f4247fc1](https://linux-hardware.org/?probe=c9f4247fc1) | Aug 04, 2023 |
| Dell          | Vostro 15 3510              | [ab2f3b8c7b](https://linux-hardware.org/?probe=ab2f3b8c7b) | Aug 04, 2023 |
| Lenovo        | ThinkPad T480s 20L8S84H0... | [d64e9809fa](https://linux-hardware.org/?probe=d64e9809fa) | Aug 04, 2023 |
| Apple         | MacBookPro8,2               | [a8de87477f](https://linux-hardware.org/?probe=a8de87477f) | Aug 04, 2023 |
| Apple         | MacBookPro9,2               | [cf25fc0b62](https://linux-hardware.org/?probe=cf25fc0b62) | Aug 04, 2023 |
| HP            | 255 G3                      | [c8b3db6b0b](https://linux-hardware.org/?probe=c8b3db6b0b) | Aug 03, 2023 |
| HP            | EliteBook Folio G1          | [b9bb38ddd4](https://linux-hardware.org/?probe=b9bb38ddd4) | Aug 03, 2023 |
| Sony          | VGN-NS38E_S                 | [a21051f2a8](https://linux-hardware.org/?probe=a21051f2a8) | Aug 03, 2023 |
| Lenovo        | ThinkPad X280 20KES3D900    | [865dbfa247](https://linux-hardware.org/?probe=865dbfa247) | Aug 03, 2023 |
| Acer          | Aspire 7750G                | [71f5ef03f9](https://linux-hardware.org/?probe=71f5ef03f9) | Aug 03, 2023 |
| Notebook      | NP5x_NP6x_NP7xPNP           | [508c18e563](https://linux-hardware.org/?probe=508c18e563) | Aug 03, 2023 |
| Acer          | Aspire A515-57              | [87c4730d07](https://linux-hardware.org/?probe=87c4730d07) | Aug 03, 2023 |
| GIADA         | Unknown                     | [cd8b23468a](https://linux-hardware.org/?probe=cd8b23468a) | Aug 03, 2023 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [e5be227d11](https://linux-hardware.org/?probe=e5be227d11) | Aug 03, 2023 |
| Dell          | Latitude E6440              | [c00884f2cd](https://linux-hardware.org/?probe=c00884f2cd) | Aug 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [deeafc23f9](https://linux-hardware.org/?probe=deeafc23f9) | Aug 03, 2023 |
| Lenovo        | V510-15IKB 80WQ             | [a3ff56579a](https://linux-hardware.org/?probe=a3ff56579a) | Aug 03, 2023 |
| Notebook      | N9x0TD_TF                   | [033c07e1d3](https://linux-hardware.org/?probe=033c07e1d3) | Aug 03, 2023 |
| Notebook      | N9x0TD_TF                   | [3ab98d3af1](https://linux-hardware.org/?probe=3ab98d3af1) | Aug 03, 2023 |
| Acer          | Aspire ES1-520              | [437e15fae7](https://linux-hardware.org/?probe=437e15fae7) | Aug 03, 2023 |
| MSI           | Prestige 14Evo A12M         | [c9e4b6dd90](https://linux-hardware.org/?probe=c9e4b6dd90) | Aug 03, 2023 |
| HP            | EliteBook 8570p             | [9b2c783e20](https://linux-hardware.org/?probe=9b2c783e20) | Aug 03, 2023 |
| Dell          | Latitude 5440               | [5791d15bc8](https://linux-hardware.org/?probe=5791d15bc8) | Aug 02, 2023 |
| Acer          | Aspire A515-56              | [8b2ffc9837](https://linux-hardware.org/?probe=8b2ffc9837) | Aug 02, 2023 |
| HUAWEI        | HVY-WXX9                    | [906ab3334f](https://linux-hardware.org/?probe=906ab3334f) | Aug 02, 2023 |
| Dell          | Latitude 5540               | [e521b93e2f](https://linux-hardware.org/?probe=e521b93e2f) | Aug 02, 2023 |
| Notebook      | PB50_70RF,RD,RC             | [deb7c70ef0](https://linux-hardware.org/?probe=deb7c70ef0) | Aug 02, 2023 |
| Acer          | Aspire ES1-520              | [1cf260b959](https://linux-hardware.org/?probe=1cf260b959) | Aug 02, 2023 |
| HP            | 255 G8 Notebook PC          | [d0e963d600](https://linux-hardware.org/?probe=d0e963d600) | Aug 02, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [28ff7ce482](https://linux-hardware.org/?probe=28ff7ce482) | Aug 02, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [502969280a](https://linux-hardware.org/?probe=502969280a) | Aug 02, 2023 |
| ASUSTek       | X540NA                      | [c7724d9c7c](https://linux-hardware.org/?probe=c7724d9c7c) | Aug 02, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [34ef2db095](https://linux-hardware.org/?probe=34ef2db095) | Aug 02, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [8767df67f4](https://linux-hardware.org/?probe=8767df67f4) | Aug 02, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [dd11fc89fe](https://linux-hardware.org/?probe=dd11fc89fe) | Aug 02, 2023 |
| Panasonic     | CF-31Q2A731M                | [28a7b62627](https://linux-hardware.org/?probe=28a7b62627) | Aug 02, 2023 |
| Acer          | Aspire E1-572               | [af04d8d764](https://linux-hardware.org/?probe=af04d8d764) | Aug 02, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [74f1782ead](https://linux-hardware.org/?probe=74f1782ead) | Aug 02, 2023 |
| ASUSTek       | UX430UNR                    | [89c8324528](https://linux-hardware.org/?probe=89c8324528) | Aug 01, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [d9db031e65](https://linux-hardware.org/?probe=d9db031e65) | Aug 01, 2023 |
| Dell          | Inspiron 5567               | [6f220fcf23](https://linux-hardware.org/?probe=6f220fcf23) | Aug 01, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [8e7e80c44e](https://linux-hardware.org/?probe=8e7e80c44e) | Aug 01, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [7ed6a80c20](https://linux-hardware.org/?probe=7ed6a80c20) | Aug 01, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [bbf2e1b3b3](https://linux-hardware.org/?probe=bbf2e1b3b3) | Aug 01, 2023 |
| Lenovo        | ThinkPad X250 20CL0007SG    | [f30d61c851](https://linux-hardware.org/?probe=f30d61c851) | Aug 01, 2023 |
| Acer          | Aspire A315-23              | [ef1917aa93](https://linux-hardware.org/?probe=ef1917aa93) | Aug 01, 2023 |
| Acer          | Aspire A315-23              | [9164151f28](https://linux-hardware.org/?probe=9164151f28) | Aug 01, 2023 |
| Toshiba       | Satellite C850-F74T         | [7756db419e](https://linux-hardware.org/?probe=7756db419e) | Aug 01, 2023 |
| Dell          | Inspiron 5567               | [d6c2eae395](https://linux-hardware.org/?probe=d6c2eae395) | Aug 01, 2023 |
| ASUSTek       | X751LA                      | [928a69b9af](https://linux-hardware.org/?probe=928a69b9af) | Aug 01, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [2dcefa3349](https://linux-hardware.org/?probe=2dcefa3349) | Aug 01, 2023 |
| HP            | Pavilion Laptop 15-cc5xx    | [d1af2e2c9f](https://linux-hardware.org/?probe=d1af2e2c9f) | Jul 31, 2023 |
| HP            | 355 G2                      | [db5f6adcd7](https://linux-hardware.org/?probe=db5f6adcd7) | Jul 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [5650f66cd4](https://linux-hardware.org/?probe=5650f66cd4) | Jul 31, 2023 |
| Dell          | Inspiron 7520               | [b87690f890](https://linux-hardware.org/?probe=b87690f890) | Jul 31, 2023 |
| Google        | Woomax                      | [da717e8156](https://linux-hardware.org/?probe=da717e8156) | Jul 31, 2023 |
| VPU Compan... | VWNC71429-S                 | [2a21ab7b53](https://linux-hardware.org/?probe=2a21ab7b53) | Jul 31, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [762d07665a](https://linux-hardware.org/?probe=762d07665a) | Jul 31, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [c42c13e7be](https://linux-hardware.org/?probe=c42c13e7be) | Jul 31, 2023 |
| HP            | Pavilion 17                 | [38fe3ae501](https://linux-hardware.org/?probe=38fe3ae501) | Jul 31, 2023 |
| Lenovo        | ThinkPad L440 20ASS19B03    | [560cd8b4fb](https://linux-hardware.org/?probe=560cd8b4fb) | Jul 31, 2023 |
| Lenovo        | V15-ADA 82C7                | [e3999da810](https://linux-hardware.org/?probe=e3999da810) | Jul 31, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [ad721ddbad](https://linux-hardware.org/?probe=ad721ddbad) | Jul 31, 2023 |
| Medion        | Erazer X7841 MD99556        | [7b9d9dfa25](https://linux-hardware.org/?probe=7b9d9dfa25) | Jul 31, 2023 |
| HP            | ProBook 430 G3              | [a42e1c787e](https://linux-hardware.org/?probe=a42e1c787e) | Jul 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [250fc62328](https://linux-hardware.org/?probe=250fc62328) | Jul 30, 2023 |
| Lenovo        | Legion 5 15IAH7 82RC        | [aea2ba0da6](https://linux-hardware.org/?probe=aea2ba0da6) | Jul 30, 2023 |
| HP            | 355 G2                      | [25362ed5e2](https://linux-hardware.org/?probe=25362ed5e2) | Jul 30, 2023 |
| Lenovo        | Legion 5 15IAH7 82RC        | [4299540699](https://linux-hardware.org/?probe=4299540699) | Jul 30, 2023 |
| BOSGAME       | U56                         | [39d52e51f5](https://linux-hardware.org/?probe=39d52e51f5) | Jul 30, 2023 |
| HONOR         | NBR-WAX9                    | [b69caa0c17](https://linux-hardware.org/?probe=b69caa0c17) | Jul 29, 2023 |
| HONOR         | NBR-WAX9                    | [d7434fdb2a](https://linux-hardware.org/?probe=d7434fdb2a) | Jul 29, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU604VZ... | [928fd8c7cb](https://linux-hardware.org/?probe=928fd8c7cb) | Jul 29, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [74a7a53f6a](https://linux-hardware.org/?probe=74a7a53f6a) | Jul 29, 2023 |
| HP            | Laptop 15-dy2xxx            | [3467c205e1](https://linux-hardware.org/?probe=3467c205e1) | Jul 29, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [5518dab193](https://linux-hardware.org/?probe=5518dab193) | Jul 29, 2023 |
| Dell          | Latitude 7380               | [ec068abcb3](https://linux-hardware.org/?probe=ec068abcb3) | Jul 29, 2023 |
| Dell          | Latitude 7380               | [a5ea12f136](https://linux-hardware.org/?probe=a5ea12f136) | Jul 29, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TES... | [ec5a50d1d8](https://linux-hardware.org/?probe=ec5a50d1d8) | Jul 29, 2023 |
| Lenovo        | ThinkBook 13x G2 IAP 21A... | [bc18b4b7ed](https://linux-hardware.org/?probe=bc18b4b7ed) | Jul 29, 2023 |
| Lenovo        | ThinkBook 13x G2 IAP 21A... | [9b4b9b9d59](https://linux-hardware.org/?probe=9b4b9b9d59) | Jul 29, 2023 |
| Dell          | Inspiron 3501               | [42ca7b346e](https://linux-hardware.org/?probe=42ca7b346e) | Jul 29, 2023 |
| Dell          | Inspiron 3501               | [fdcac9e445](https://linux-hardware.org/?probe=fdcac9e445) | Jul 29, 2023 |
| Lenovo        | G50-45 80E3                 | [002504b8be](https://linux-hardware.org/?probe=002504b8be) | Jul 29, 2023 |
| HP            | 250 G8 Notebook PC          | [502747dd18](https://linux-hardware.org/?probe=502747dd18) | Jul 29, 2023 |
| Dell          | Inspiron 7520               | [7509644961](https://linux-hardware.org/?probe=7509644961) | Jul 28, 2023 |
| Sony          | VGN-NS38E_S                 | [703b459140](https://linux-hardware.org/?probe=703b459140) | Jul 28, 2023 |
| HP            | Laptop 15-fc0xxx            | [30dabbbc28](https://linux-hardware.org/?probe=30dabbbc28) | Jul 28, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [03b716e2bf](https://linux-hardware.org/?probe=03b716e2bf) | Jul 28, 2023 |
| HP            | OMEN by Laptop 17-cb1xxx    | [b24aea2d95](https://linux-hardware.org/?probe=b24aea2d95) | Jul 28, 2023 |
| MECHREVO      | WUJIE 14                    | [e6c48375f0](https://linux-hardware.org/?probe=e6c48375f0) | Jul 28, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [216622d3d0](https://linux-hardware.org/?probe=216622d3d0) | Jul 28, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [96f70f73b1](https://linux-hardware.org/?probe=96f70f73b1) | Jul 28, 2023 |
| MECHREVO      | WUJIE 14                    | [89b0f29570](https://linux-hardware.org/?probe=89b0f29570) | Jul 28, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [61321e569d](https://linux-hardware.org/?probe=61321e569d) | Jul 28, 2023 |
| Apple         | MacBookPro12,1              | [5bc4bf8334](https://linux-hardware.org/?probe=5bc4bf8334) | Jul 28, 2023 |
| Dell          | Latitude 3410               | [449e4c62f3](https://linux-hardware.org/?probe=449e4c62f3) | Jul 28, 2023 |
| Google        | Akemi                       | [b6a327a843](https://linux-hardware.org/?probe=b6a327a843) | Jul 27, 2023 |
| Samsung       | 700T                        | [a6c83540ad](https://linux-hardware.org/?probe=a6c83540ad) | Jul 27, 2023 |
| Dell          | XPS 15 9570                 | [af7b522b57](https://linux-hardware.org/?probe=af7b522b57) | Jul 27, 2023 |
| Dell          | Inspiron 13-5378            | [cd318f6b75](https://linux-hardware.org/?probe=cd318f6b75) | Jul 27, 2023 |
| Apple         | MacBookPro11,5              | [57e295e5cf](https://linux-hardware.org/?probe=57e295e5cf) | Jul 27, 2023 |
| Lenovo        | Z50-70 20354                | [f213363233](https://linux-hardware.org/?probe=f213363233) | Jul 27, 2023 |
| Acer          | Aspire A517-58M             | [c39540fbbc](https://linux-hardware.org/?probe=c39540fbbc) | Jul 27, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CJC... | [d7fa33e7b1](https://linux-hardware.org/?probe=d7fa33e7b1) | Jul 27, 2023 |
| MSI           | GF63 Thin 11UC              | [20fff2edd2](https://linux-hardware.org/?probe=20fff2edd2) | Jul 27, 2023 |
| MSI           | PS63 Modern 8M              | [96e7b96787](https://linux-hardware.org/?probe=96e7b96787) | Jul 27, 2023 |
| Dell          | Latitude 9420               | [03c3ca79c4](https://linux-hardware.org/?probe=03c3ca79c4) | Jul 26, 2023 |
| ASUSTek       | K55DR                       | [47e831a79a](https://linux-hardware.org/?probe=47e831a79a) | Jul 26, 2023 |
| HP            | ENVY Laptop 13-aq0xxx       | [6632226064](https://linux-hardware.org/?probe=6632226064) | Jul 26, 2023 |
| HP            | ProBook 450 G3              | [fef5d6f571](https://linux-hardware.org/?probe=fef5d6f571) | Jul 26, 2023 |
| Chuwi         | GemiBook Pro                | [d626a17105](https://linux-hardware.org/?probe=d626a17105) | Jul 26, 2023 |
| Acer          | Aspire A715-42G             | [a6abe36eef](https://linux-hardware.org/?probe=a6abe36eef) | Jul 26, 2023 |
| Toshiba       | Satellite A135              | [91f5602ed7](https://linux-hardware.org/?probe=91f5602ed7) | Jul 26, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [a060c0999b](https://linux-hardware.org/?probe=a060c0999b) | Jul 26, 2023 |
| Acer          | Aspire A515-57G             | [8a297cb644](https://linux-hardware.org/?probe=8a297cb644) | Jul 26, 2023 |
| Acer          | Aspire A515-45              | [58d8bbebcd](https://linux-hardware.org/?probe=58d8bbebcd) | Jul 26, 2023 |
| Minix         | NEO Z83-4A                  | [3a884d55d3](https://linux-hardware.org/?probe=3a884d55d3) | Jul 26, 2023 |
| Chuwi         | GemiBook Pro                | [01f9930ae2](https://linux-hardware.org/?probe=01f9930ae2) | Jul 26, 2023 |
| HP            | ProBook 640 G2              | [f6400e37f6](https://linux-hardware.org/?probe=f6400e37f6) | Jul 26, 2023 |
| HP            | ProBook 640 G2              | [7814bf14ac](https://linux-hardware.org/?probe=7814bf14ac) | Jul 26, 2023 |
| HP            | Laptop 14s-fq1xxx           | [ee10ac6c06](https://linux-hardware.org/?probe=ee10ac6c06) | Jul 26, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [9878121979](https://linux-hardware.org/?probe=9878121979) | Jul 26, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | [1c52a031c7](https://linux-hardware.org/?probe=1c52a031c7) | Jul 26, 2023 |
| Samsung       | 700T                        | [881cb15d92](https://linux-hardware.org/?probe=881cb15d92) | Jul 25, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [7970e46266](https://linux-hardware.org/?probe=7970e46266) | Jul 25, 2023 |
| ASUSTek       | ROG Strix G731GT_GL731GT    | [df5fa32e56](https://linux-hardware.org/?probe=df5fa32e56) | Jul 25, 2023 |
| Lenovo        | ThinkPad T460 20FMS15W07    | [6a77133959](https://linux-hardware.org/?probe=6a77133959) | Jul 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [f3cc428da8](https://linux-hardware.org/?probe=f3cc428da8) | Jul 25, 2023 |
| Apple         | MacBookPro5,1               | [b5771a9e3f](https://linux-hardware.org/?probe=b5771a9e3f) | Jul 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [6c03bf1d0d](https://linux-hardware.org/?probe=6c03bf1d0d) | Jul 25, 2023 |
| Apple         | MacBookPro8,1               | [86c44eb9f0](https://linux-hardware.org/?probe=86c44eb9f0) | Jul 25, 2023 |
| Dell          | Inspiron 5559               | [08569be07e](https://linux-hardware.org/?probe=08569be07e) | Jul 25, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [f347019f85](https://linux-hardware.org/?probe=f347019f85) | Jul 24, 2023 |
| Lenovo        | ThinkPad T480 20L6S9R600    | [c97957b91a](https://linux-hardware.org/?probe=c97957b91a) | Jul 24, 2023 |
| Lenovo        | ThinkPad T420s 417152U      | [22e09689b0](https://linux-hardware.org/?probe=22e09689b0) | Jul 24, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [295d363d3e](https://linux-hardware.org/?probe=295d363d3e) | Jul 24, 2023 |
| HP            | EliteBook 840 G2            | [598e9ca129](https://linux-hardware.org/?probe=598e9ca129) | Jul 24, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [19aa0d748d](https://linux-hardware.org/?probe=19aa0d748d) | Jul 24, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [f1844a5f28](https://linux-hardware.org/?probe=f1844a5f28) | Jul 24, 2023 |
| Acer          | Nitro AN515-57              | [d4b572d070](https://linux-hardware.org/?probe=d4b572d070) | Jul 24, 2023 |
| Lenovo        | ThinkPad X230 23246V9       | [e7bc7dac48](https://linux-hardware.org/?probe=e7bc7dac48) | Jul 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [8377b87a66](https://linux-hardware.org/?probe=8377b87a66) | Jul 24, 2023 |
| SLIMBOOK      | Executive                   | [2def302827](https://linux-hardware.org/?probe=2def302827) | Jul 24, 2023 |
| SLIMBOOK      | Executive                   | [2f0b072622](https://linux-hardware.org/?probe=2f0b072622) | Jul 24, 2023 |
| Acer          | Nitro AN515-54              | [696b36cfb3](https://linux-hardware.org/?probe=696b36cfb3) | Jul 24, 2023 |
| Lenovo        | E41-25 81FS                 | [d9f18f8f28](https://linux-hardware.org/?probe=d9f18f8f28) | Jul 24, 2023 |
| Lenovo        | ThinkPad T420 4180AQ3       | [823eca937c](https://linux-hardware.org/?probe=823eca937c) | Jul 24, 2023 |
| HP            | Pavilion Laptop 14-ec1xx... | [e822964466](https://linux-hardware.org/?probe=e822964466) | Jul 24, 2023 |
| Dell          | G15 5510                    | [18ceaecd85](https://linux-hardware.org/?probe=18ceaecd85) | Jul 24, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X2S... | [3f4e603493](https://linux-hardware.org/?probe=3f4e603493) | Jul 23, 2023 |
| Dell          | Inspiron 3541               | [0a146a40d9](https://linux-hardware.org/?probe=0a146a40d9) | Jul 23, 2023 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | [6750fae080](https://linux-hardware.org/?probe=6750fae080) | Jul 23, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [de58b924e1](https://linux-hardware.org/?probe=de58b924e1) | Jul 23, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [a61cd014ac](https://linux-hardware.org/?probe=a61cd014ac) | Jul 23, 2023 |
| HP            | ProBook 6570b               | [31ef725f16](https://linux-hardware.org/?probe=31ef725f16) | Jul 23, 2023 |
| HP            | ProBook 6570b               | [62e92dfa4e](https://linux-hardware.org/?probe=62e92dfa4e) | Jul 23, 2023 |
| HUAWEI        | KPRC-WX0                    | [b8c39bfcff](https://linux-hardware.org/?probe=b8c39bfcff) | Jul 23, 2023 |
| GPU Compan... | GWNC21524                   | [10606e6e69](https://linux-hardware.org/?probe=10606e6e69) | Jul 23, 2023 |
| HP            | ProBook 450 G2              | [3466d6ab26](https://linux-hardware.org/?probe=3466d6ab26) | Jul 23, 2023 |
| HP            | ProBook 450 G2              | [94df828438](https://linux-hardware.org/?probe=94df828438) | Jul 22, 2023 |
| HP            | EliteBook 840 G5            | [f371e0efe5](https://linux-hardware.org/?probe=f371e0efe5) | Jul 22, 2023 |
| TUXEDO        | Gemini Gen2                 | [94fe3784a3](https://linux-hardware.org/?probe=94fe3784a3) | Jul 22, 2023 |
| Acer          | Aspire V3-372               | [7223651dee](https://linux-hardware.org/?probe=7223651dee) | Jul 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [cc08425e5b](https://linux-hardware.org/?probe=cc08425e5b) | Jul 22, 2023 |
| Acer          | Extensa 215-31              | [968f0d7741](https://linux-hardware.org/?probe=968f0d7741) | Jul 22, 2023 |
| Acer          | Extensa 215-31              | [e937f82e9d](https://linux-hardware.org/?probe=e937f82e9d) | Jul 22, 2023 |
| HP            | Pavilion Notebook           | [e50470a456](https://linux-hardware.org/?probe=e50470a456) | Jul 22, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [727fd6d08d](https://linux-hardware.org/?probe=727fd6d08d) | Jul 22, 2023 |
| Timi          | Mi NoteBook Horizon Edit... | [72a5dfb7cd](https://linux-hardware.org/?probe=72a5dfb7cd) | Jul 21, 2023 |
| ALLDOCUBE     | i1502                       | [1006fc7673](https://linux-hardware.org/?probe=1006fc7673) | Jul 21, 2023 |
| ASUSTek       | S551LB                      | [edfa5090fc](https://linux-hardware.org/?probe=edfa5090fc) | Jul 21, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [2af4d18efd](https://linux-hardware.org/?probe=2af4d18efd) | Jul 21, 2023 |
| Lenovo        | Z50-70 20354                | [33150ea27b](https://linux-hardware.org/?probe=33150ea27b) | Jul 21, 2023 |
| HUAWEI        | BOD-WXX9                    | [e98c83ea9b](https://linux-hardware.org/?probe=e98c83ea9b) | Jul 21, 2023 |
| HUAWEI        | BOD-WXX9                    | [c0d9daee63](https://linux-hardware.org/?probe=c0d9daee63) | Jul 21, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [49b784f5e2](https://linux-hardware.org/?probe=49b784f5e2) | Jul 21, 2023 |
| Lenovo        | ThinkPad T540p 20BFA06B0... | [15e3320bb0](https://linux-hardware.org/?probe=15e3320bb0) | Jul 21, 2023 |
| Dell          | Latitude E6420              | [35d8d85f3c](https://linux-hardware.org/?probe=35d8d85f3c) | Jul 21, 2023 |
| Apple         | MacBookPro14,3              | [e24c8a224e](https://linux-hardware.org/?probe=e24c8a224e) | Jul 21, 2023 |
| Dell          | Inspiron 5559               | [1cd1874bc1](https://linux-hardware.org/?probe=1cd1874bc1) | Jul 21, 2023 |
| Dell          | Studio 1737                 | [df1ff5b464](https://linux-hardware.org/?probe=df1ff5b464) | Jul 21, 2023 |
| Lenovo        | G50-80 80E5                 | [0f212dfabe](https://linux-hardware.org/?probe=0f212dfabe) | Jul 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [35d1400354](https://linux-hardware.org/?probe=35d1400354) | Jul 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [5c4d93901b](https://linux-hardware.org/?probe=5c4d93901b) | Jul 20, 2023 |
| F-Plus Mob... | FLAPTOP r                   | [de2decf47b](https://linux-hardware.org/?probe=de2decf47b) | Jul 20, 2023 |
| HUAWEI        | BOD-WXX9                    | [10c841c8ae](https://linux-hardware.org/?probe=10c841c8ae) | Jul 20, 2023 |
| Dell          | XPS 15 7590                 | [714d6a38d3](https://linux-hardware.org/?probe=714d6a38d3) | Jul 20, 2023 |
| Fujitsu       | LIFEBOOK E556               | [d02422eb33](https://linux-hardware.org/?probe=d02422eb33) | Jul 20, 2023 |
| F-Plus Mob... | FLAPTOP r                   | [f21f00d216](https://linux-hardware.org/?probe=f21f00d216) | Jul 20, 2023 |
| Timi          | Mi NoteBook Ultra           | [6bb2b5bfb6](https://linux-hardware.org/?probe=6bb2b5bfb6) | Jul 20, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [54eaa7c86b](https://linux-hardware.org/?probe=54eaa7c86b) | Jul 20, 2023 |
| HP            | ProBook 6460b               | [c135a2ae0e](https://linux-hardware.org/?probe=c135a2ae0e) | Jul 20, 2023 |
| Fujitsu       | FMVNA9K3C                   | [64c67e920e](https://linux-hardware.org/?probe=64c67e920e) | Jul 20, 2023 |
| Fujitsu       | FMVNA9K3C                   | [0b0d110403](https://linux-hardware.org/?probe=0b0d110403) | Jul 20, 2023 |
| Toshiba       | Satellite P505              | [67f92fe378](https://linux-hardware.org/?probe=67f92fe378) | Jul 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [fcdb1fdeed](https://linux-hardware.org/?probe=fcdb1fdeed) | Jul 20, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | [fe9e1671cc](https://linux-hardware.org/?probe=fe9e1671cc) | Jul 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [0bd52b9adf](https://linux-hardware.org/?probe=0bd52b9adf) | Jul 20, 2023 |
| Dell          | XPS 15 7590                 | [f7edcc8364](https://linux-hardware.org/?probe=f7edcc8364) | Jul 20, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [fb09f582c5](https://linux-hardware.org/?probe=fb09f582c5) | Jul 20, 2023 |
| Dell          | Latitude E6410              | [2a09336b72](https://linux-hardware.org/?probe=2a09336b72) | Jul 20, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [2fcc9e6028](https://linux-hardware.org/?probe=2fcc9e6028) | Jul 20, 2023 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [0e18492205](https://linux-hardware.org/?probe=0e18492205) | Jul 20, 2023 |
| ASUSTek       | K55A                        | [57730763fa](https://linux-hardware.org/?probe=57730763fa) | Jul 20, 2023 |
| Dell          | Latitude 9420               | [750f80b869](https://linux-hardware.org/?probe=750f80b869) | Jul 19, 2023 |
| Dell          | Latitude 9420               | [a4ba4bfde1](https://linux-hardware.org/?probe=a4ba4bfde1) | Jul 19, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [ec673415b4](https://linux-hardware.org/?probe=ec673415b4) | Jul 19, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [77468bcff7](https://linux-hardware.org/?probe=77468bcff7) | Jul 19, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [eb7b37c1d2](https://linux-hardware.org/?probe=eb7b37c1d2) | Jul 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [ebed32abef](https://linux-hardware.org/?probe=ebed32abef) | Jul 19, 2023 |
| Dell          | Latitude 7440               | [508d0e46e7](https://linux-hardware.org/?probe=508d0e46e7) | Jul 19, 2023 |
| ASUSTek       | X550CL                      | [15f6e3e7e0](https://linux-hardware.org/?probe=15f6e3e7e0) | Jul 19, 2023 |
| Apple         | MacBookAir6,1               | [1e5c6bb3a9](https://linux-hardware.org/?probe=1e5c6bb3a9) | Jul 18, 2023 |
| Positivo      | N4340                       | [fdcc9c264b](https://linux-hardware.org/?probe=fdcc9c264b) | Jul 18, 2023 |
| Positivo      | N4340                       | [1a7db9f33d](https://linux-hardware.org/?probe=1a7db9f33d) | Jul 18, 2023 |
| MSI           | Modern 15 A5M               | [1763ff7356](https://linux-hardware.org/?probe=1763ff7356) | Jul 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [3358d2f649](https://linux-hardware.org/?probe=3358d2f649) | Jul 18, 2023 |
| HP            | ElitePad 1000 G2            | [0878c1fae6](https://linux-hardware.org/?probe=0878c1fae6) | Jul 18, 2023 |
| Acer          | Nitro AN17-41               | [cfd05752a7](https://linux-hardware.org/?probe=cfd05752a7) | Jul 18, 2023 |
| Dell          | Precision 3581              | [68d58784d5](https://linux-hardware.org/?probe=68d58784d5) | Jul 18, 2023 |
| Dell          | Latitude 3590               | [6386a869e5](https://linux-hardware.org/?probe=6386a869e5) | Jul 18, 2023 |
| Lenovo        | Legion Pro 7 16IRX8H 82W... | [efd490f52d](https://linux-hardware.org/?probe=efd490f52d) | Jul 18, 2023 |
| Acer          | Aspire A515-56              | [4df2761b3c](https://linux-hardware.org/?probe=4df2761b3c) | Jul 18, 2023 |
| Toshiba       | TECRA Z50-A                 | [d2b1eef8ac](https://linux-hardware.org/?probe=d2b1eef8ac) | Jul 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X531... | [a8779931a8](https://linux-hardware.org/?probe=a8779931a8) | Jul 18, 2023 |
| Acer          | Swift SF314-512             | [7ca00c03d6](https://linux-hardware.org/?probe=7ca00c03d6) | Jul 18, 2023 |
| Lenovo        | ThinkPad T430 2344BPU       | [d2ffcfdd6b](https://linux-hardware.org/?probe=d2ffcfdd6b) | Jul 18, 2023 |
| Toshiba       | Satellite L850              | [afdd53cd2f](https://linux-hardware.org/?probe=afdd53cd2f) | Jul 18, 2023 |
| Toshiba       | Satellite L850              | [23c31a7c87](https://linux-hardware.org/?probe=23c31a7c87) | Jul 17, 2023 |
| ASUSTek       | G75VW                       | [2bd8f70433](https://linux-hardware.org/?probe=2bd8f70433) | Jul 17, 2023 |
| Dell          | Inspiron 5748               | [94e04f8baf](https://linux-hardware.org/?probe=94e04f8baf) | Jul 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [be44ef471d](https://linux-hardware.org/?probe=be44ef471d) | Jul 17, 2023 |
| Shenzhen P... | MOMO8W_P806                 | [fef8b63a34](https://linux-hardware.org/?probe=fef8b63a34) | Jul 17, 2023 |
| Apple         | MacBookPro8,1               | [27c0999421](https://linux-hardware.org/?probe=27c0999421) | Jul 17, 2023 |
| Dell          | Inspiron 7400               | [793ffb4349](https://linux-hardware.org/?probe=793ffb4349) | Jul 17, 2023 |
| HP            | ProBook 455 15.6 inch G9... | [7f25599ad8](https://linux-hardware.org/?probe=7f25599ad8) | Jul 17, 2023 |
| Dell          | Inspiron 7400               | [5bfc86eb6b](https://linux-hardware.org/?probe=5bfc86eb6b) | Jul 17, 2023 |
| HP            | EliteBook 6930p (NG813UP... | [4c6736fd14](https://linux-hardware.org/?probe=4c6736fd14) | Jul 17, 2023 |
| HP            | EliteBook 6930p (NG813UP... | [33b2f9227b](https://linux-hardware.org/?probe=33b2f9227b) | Jul 17, 2023 |
| HP            | ProBook 455 15.6 inch G9... | [8c94595be0](https://linux-hardware.org/?probe=8c94595be0) | Jul 17, 2023 |
| Olivetti      | Olipad Graphos W811         | [d303fe2826](https://linux-hardware.org/?probe=d303fe2826) | Jul 17, 2023 |
| HP            | Pavilion dv6                | [2abf53d250](https://linux-hardware.org/?probe=2abf53d250) | Jul 17, 2023 |
| Acer          | Swift SF314-71              | [462a41184d](https://linux-hardware.org/?probe=462a41184d) | Jul 17, 2023 |
| HP            | Pavilion 15                 | [86870a7a20](https://linux-hardware.org/?probe=86870a7a20) | Jul 17, 2023 |
| ASUSTek       | X751LA                      | [345fab37ab](https://linux-hardware.org/?probe=345fab37ab) | Jul 17, 2023 |
| Samsung       | RV420/RV520/RV720/E3530/... | [25f8458274](https://linux-hardware.org/?probe=25f8458274) | Jul 17, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [111c0b962d](https://linux-hardware.org/?probe=111c0b962d) | Jul 16, 2023 |
| Apple         | MacBookPro15,4              | [e456628b0c](https://linux-hardware.org/?probe=e456628b0c) | Jul 16, 2023 |
| Apple         | MacBookPro15,4              | [9b86ebabe3](https://linux-hardware.org/?probe=9b86ebabe3) | Jul 16, 2023 |
| Unknown       | Unknown                     | [85d7cb63b8](https://linux-hardware.org/?probe=85d7cb63b8) | Jul 16, 2023 |
| MSI           | GX60 3CC                    | [99566dd038](https://linux-hardware.org/?probe=99566dd038) | Jul 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [9287464155](https://linux-hardware.org/?probe=9287464155) | Jul 16, 2023 |
| HP            | Laptop                      | [c516791822](https://linux-hardware.org/?probe=c516791822) | Jul 15, 2023 |
| Hungaro Fl... | Navon Loop 360              | [b4325e403a](https://linux-hardware.org/?probe=b4325e403a) | Jul 15, 2023 |
| HP            | EliteBook 840 G1            | [420ffaec41](https://linux-hardware.org/?probe=420ffaec41) | Jul 15, 2023 |
| HP            | Pavilion 17                 | [c8775bcc36](https://linux-hardware.org/?probe=c8775bcc36) | Jul 15, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | [7d2f78f0d3](https://linux-hardware.org/?probe=7d2f78f0d3) | Jul 15, 2023 |
| Dell          | Latitude 7290               | [4675215b5f](https://linux-hardware.org/?probe=4675215b5f) | Jul 15, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [f22c6fa671](https://linux-hardware.org/?probe=f22c6fa671) | Jul 15, 2023 |
| Lenovo        | ThinkPad T450 20BUS0S902    | [34329ab49c](https://linux-hardware.org/?probe=34329ab49c) | Jul 15, 2023 |
| BESSTAR Te... | U820                        | [6e79cbdccc](https://linux-hardware.org/?probe=6e79cbdccc) | Jul 15, 2023 |
| BESSTAR Te... | U820                        | [1c9da1be8b](https://linux-hardware.org/?probe=1c9da1be8b) | Jul 15, 2023 |
| Notebook      | NS5x_NS7xPU                 | [41283a1f4e](https://linux-hardware.org/?probe=41283a1f4e) | Jul 15, 2023 |
| BESSTAR Te... | U820                        | [274b5bed12](https://linux-hardware.org/?probe=274b5bed12) | Jul 15, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [48b3d62237](https://linux-hardware.org/?probe=48b3d62237) | Jul 15, 2023 |
| Toshiba       | Satellite Pro L500          | [605c123888](https://linux-hardware.org/?probe=605c123888) | Jul 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [038a62a49f](https://linux-hardware.org/?probe=038a62a49f) | Jul 15, 2023 |
| Notebook      | PCX0DX                      | [4b7f45adc4](https://linux-hardware.org/?probe=4b7f45adc4) | Jul 15, 2023 |
| ASUSTek       | TP500LA                     | [aace85ddbc](https://linux-hardware.org/?probe=aace85ddbc) | Jul 14, 2023 |
| Apple         | MacBookPro6,2               | [990cd83468](https://linux-hardware.org/?probe=990cd83468) | Jul 14, 2023 |
| Apple         | MacBookPro8,1               | [4de092adb7](https://linux-hardware.org/?probe=4de092adb7) | Jul 14, 2023 |
| Apple         | MacBookAir8,1               | [44ea5a1e75](https://linux-hardware.org/?probe=44ea5a1e75) | Jul 14, 2023 |
| Dell          | XPS 13 9300                 | [ca425f6c38](https://linux-hardware.org/?probe=ca425f6c38) | Jul 14, 2023 |
| HP            | Pavilion m6                 | [8566e9607f](https://linux-hardware.org/?probe=8566e9607f) | Jul 14, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | [2f552150c5](https://linux-hardware.org/?probe=2f552150c5) | Jul 14, 2023 |
| HP            | Laptop 17-cp0xxx            | [bb135cf850](https://linux-hardware.org/?probe=bb135cf850) | Jul 14, 2023 |
| HP            | Laptop 17-cp0xxx            | [ded1de1af6](https://linux-hardware.org/?probe=ded1de1af6) | Jul 14, 2023 |
| Lenovo        | ThinkPad T430 23427YU       | [ccdb0e4b0e](https://linux-hardware.org/?probe=ccdb0e4b0e) | Jul 14, 2023 |
| Dell          | Latitude 5290 2-in-1        | [b1665dca99](https://linux-hardware.org/?probe=b1665dca99) | Jul 14, 2023 |
| Apple         | MacBookAir6,1               | [663f63dc47](https://linux-hardware.org/?probe=663f63dc47) | Jul 14, 2023 |
| HP            | 255 G8 Notebook PC          | [584f2a2ac4](https://linux-hardware.org/?probe=584f2a2ac4) | Jul 13, 2023 |
| HUAWEI        | BOHB-WAX9                   | [b72c043646](https://linux-hardware.org/?probe=b72c043646) | Jul 13, 2023 |
| Dell          | Latitude 5501               | [b10b0e72f0](https://linux-hardware.org/?probe=b10b0e72f0) | Jul 13, 2023 |
| Dell          | Precision M4800             | [58f17cf0a4](https://linux-hardware.org/?probe=58f17cf0a4) | Jul 13, 2023 |
| MSI           | GE62 2QD                    | [1a937fa00c](https://linux-hardware.org/?probe=1a937fa00c) | Jul 13, 2023 |
| HP            | Laptop 15-db0xxx            | [301dbaa508](https://linux-hardware.org/?probe=301dbaa508) | Jul 13, 2023 |
| HP            | Notebook                    | [50376757dd](https://linux-hardware.org/?probe=50376757dd) | Jul 13, 2023 |
| Dell          | XPS 13 9343                 | [0ae6ff1386](https://linux-hardware.org/?probe=0ae6ff1386) | Jul 13, 2023 |
| GPU Compan... | GWTC51427                   | [138ef93d27](https://linux-hardware.org/?probe=138ef93d27) | Jul 13, 2023 |
| Toshiba       | Satellite Pro S500          | [b9b5f89f0c](https://linux-hardware.org/?probe=b9b5f89f0c) | Jul 12, 2023 |
| HP            | Notebook                    | [38c068a51a](https://linux-hardware.org/?probe=38c068a51a) | Jul 12, 2023 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [f742573138](https://linux-hardware.org/?probe=f742573138) | Jul 12, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [dd2c7b0c60](https://linux-hardware.org/?probe=dd2c7b0c60) | Jul 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [d7c5b64bcb](https://linux-hardware.org/?probe=d7c5b64bcb) | Jul 12, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XV... | [eedf073788](https://linux-hardware.org/?probe=eedf073788) | Jul 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [b1ceb90106](https://linux-hardware.org/?probe=b1ceb90106) | Jul 12, 2023 |
| HP            | Unknown                     | [6100712075](https://linux-hardware.org/?probe=6100712075) | Jul 12, 2023 |
| HP            | EliteBook Folio 1040 G3     | [95c073864d](https://linux-hardware.org/?probe=95c073864d) | Jul 12, 2023 |
| Timi          | Mi NoteBook Ultra           | [04c4e233af](https://linux-hardware.org/?probe=04c4e233af) | Jul 12, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [9479004a7e](https://linux-hardware.org/?probe=9479004a7e) | Jul 12, 2023 |
| HP            | Pavilion dv3                | [94eeea2364](https://linux-hardware.org/?probe=94eeea2364) | Jul 12, 2023 |
| Dell          | XPS 13 9305                 | [a4f7584ee4](https://linux-hardware.org/?probe=a4f7584ee4) | Jul 12, 2023 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | [151cc29e31](https://linux-hardware.org/?probe=151cc29e31) | Jul 12, 2023 |
| HP            | ProBook 6570b               | [0c933d2dd8](https://linux-hardware.org/?probe=0c933d2dd8) | Jul 12, 2023 |
| HP            | 630                         | [671710637c](https://linux-hardware.org/?probe=671710637c) | Jul 11, 2023 |
| HP            | G62                         | [c202be1723](https://linux-hardware.org/?probe=c202be1723) | Jul 11, 2023 |
| Dell          | Inspiron 7373               | [ae34ac968a](https://linux-hardware.org/?probe=ae34ac968a) | Jul 11, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | [e688a998bc](https://linux-hardware.org/?probe=e688a998bc) | Jul 11, 2023 |
| HP            | Compaq 6730s                | [1c3f1f1005](https://linux-hardware.org/?probe=1c3f1f1005) | Jul 11, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | [11eed5426e](https://linux-hardware.org/?probe=11eed5426e) | Jul 11, 2023 |
| Dell          | Inspiron 7520               | [154a4104b1](https://linux-hardware.org/?probe=154a4104b1) | Jul 11, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [481920c1a6](https://linux-hardware.org/?probe=481920c1a6) | Jul 11, 2023 |
| Dell          | Inspiron 13-5368            | [902469d3db](https://linux-hardware.org/?probe=902469d3db) | Jul 11, 2023 |
| MSI           | Cyborg 15 A12VF             | [e9de99bb41](https://linux-hardware.org/?probe=e9de99bb41) | Jul 11, 2023 |
| HP            | 250 G2                      | [7fd1832150](https://linux-hardware.org/?probe=7fd1832150) | Jul 11, 2023 |
| HP            | 250 G2                      | [738b04c947](https://linux-hardware.org/?probe=738b04c947) | Jul 11, 2023 |
| MSI           | Cyborg 15 A12VF             | [c98fe25d37](https://linux-hardware.org/?probe=c98fe25d37) | Jul 11, 2023 |
| Lenovo        | IdeaPad Slim 3 14AMN8 82... | [f09d4ec214](https://linux-hardware.org/?probe=f09d4ec214) | Jul 11, 2023 |
| Lenovo        | IdeaPad Slim 3 14AMN8 82... | [47c4706927](https://linux-hardware.org/?probe=47c4706927) | Jul 10, 2023 |
| Apple         | MacBookPro9,2               | [3ad7db3176](https://linux-hardware.org/?probe=3ad7db3176) | Jul 10, 2023 |
| HP            | Pavilion - 14-CE2068ST      | [bdf8b67813](https://linux-hardware.org/?probe=bdf8b67813) | Jul 10, 2023 |
| Dell          | Latitude E5430 non-vPro     | [71329b9909](https://linux-hardware.org/?probe=71329b9909) | Jul 10, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | [33c3fbd9ff](https://linux-hardware.org/?probe=33c3fbd9ff) | Jul 10, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [d4ca6c4f81](https://linux-hardware.org/?probe=d4ca6c4f81) | Jul 10, 2023 |
| HUAWEI        | BOD-WXX9                    | [e157c2b1d6](https://linux-hardware.org/?probe=e157c2b1d6) | Jul 10, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [7d5e51d9a8](https://linux-hardware.org/?probe=7d5e51d9a8) | Jul 10, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [4ee2490bde](https://linux-hardware.org/?probe=4ee2490bde) | Jul 10, 2023 |
| Dell          | Latitude 5290 2-in-1        | [93af7b652d](https://linux-hardware.org/?probe=93af7b652d) | Jul 10, 2023 |
| HP            | Notebook                    | [ab3a4d4234](https://linux-hardware.org/?probe=ab3a4d4234) | Jul 10, 2023 |
| Acer          | Aspire A515-43              | [e511abad14](https://linux-hardware.org/?probe=e511abad14) | Jul 09, 2023 |
| Dell          | Inspiron 13-7359            | [0af0ff75dc](https://linux-hardware.org/?probe=0af0ff75dc) | Jul 09, 2023 |
| HP            | ENVY 17                     | [0d1714007f](https://linux-hardware.org/?probe=0d1714007f) | Jul 09, 2023 |
| Dell          | Latitude E6440              | [6265e6109a](https://linux-hardware.org/?probe=6265e6109a) | Jul 09, 2023 |
| Acer          | Aspire A515-51G             | [044dd1e5a7](https://linux-hardware.org/?probe=044dd1e5a7) | Jul 09, 2023 |
| ASUSTek       | X202EP                      | [37c48d7aa1](https://linux-hardware.org/?probe=37c48d7aa1) | Jul 09, 2023 |
| HP            | Compaq Presario CQ60        | [60e671ef49](https://linux-hardware.org/?probe=60e671ef49) | Jul 09, 2023 |
| TR            | ST Plus-KN                  | [3d549b50a3](https://linux-hardware.org/?probe=3d549b50a3) | Jul 09, 2023 |
| MSI           | GL72 6QF                    | [487fd6cc0e](https://linux-hardware.org/?probe=487fd6cc0e) | Jul 09, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | [5ac5b565cd](https://linux-hardware.org/?probe=5ac5b565cd) | Jul 09, 2023 |
| Acer          | Nitro AN17-41               | [3003d5f2d7](https://linux-hardware.org/?probe=3003d5f2d7) | Jul 09, 2023 |
| ASUSTek       | G60VX                       | [3273a8de27](https://linux-hardware.org/?probe=3273a8de27) | Jul 09, 2023 |
| Notebook      | V1x0PNPx                    | [5a37402681](https://linux-hardware.org/?probe=5a37402681) | Jul 09, 2023 |
| HP            | Pavilion g7                 | [5e2cf6a804](https://linux-hardware.org/?probe=5e2cf6a804) | Jul 09, 2023 |
| Dell          | Latitude E6220              | [5e17659f32](https://linux-hardware.org/?probe=5e17659f32) | Jul 09, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [8b54e451a7](https://linux-hardware.org/?probe=8b54e451a7) | Jul 09, 2023 |
| ASUSTek       | X550VC                      | [ecd8f6cdd2](https://linux-hardware.org/?probe=ecd8f6cdd2) | Jul 09, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [c3d30da33f](https://linux-hardware.org/?probe=c3d30da33f) | Jul 09, 2023 |
| ASUSTek       | X550VC                      | [0ea27ea171](https://linux-hardware.org/?probe=0ea27ea171) | Jul 09, 2023 |
| HP            | EliteBook 840 G2            | [9b0de4f244](https://linux-hardware.org/?probe=9b0de4f244) | Jul 09, 2023 |
| HP            | Pavilion Laptop 15-cc5xx    | [627d945f1d](https://linux-hardware.org/?probe=627d945f1d) | Jul 08, 2023 |
| Dell          | Latitude 5290 2-in-1        | [4c71689526](https://linux-hardware.org/?probe=4c71689526) | Jul 08, 2023 |
| Dell          | MXG061                      | [11112370d0](https://linux-hardware.org/?probe=11112370d0) | Jul 08, 2023 |
| MSI           | Katana GF76 11UE            | [05c77752ce](https://linux-hardware.org/?probe=05c77752ce) | Jul 08, 2023 |
| Dell          | MXG061                      | [148c402557](https://linux-hardware.org/?probe=148c402557) | Jul 08, 2023 |
| MSI           | Katana GF76 11UE            | [be128325f8](https://linux-hardware.org/?probe=be128325f8) | Jul 08, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | [43004a5071](https://linux-hardware.org/?probe=43004a5071) | Jul 08, 2023 |
| HP            | 250 G5 Notebook PC          | [030ecef01c](https://linux-hardware.org/?probe=030ecef01c) | Jul 08, 2023 |
| HP            | 250 G5 Notebook PC          | [56683a6866](https://linux-hardware.org/?probe=56683a6866) | Jul 08, 2023 |
| Google        | Swanky                      | [e2987764f8](https://linux-hardware.org/?probe=e2987764f8) | Jul 08, 2023 |
| Dell          | G15 5511                    | [eebe5b09c0](https://linux-hardware.org/?probe=eebe5b09c0) | Jul 08, 2023 |
| Dell          | Latitude E5440              | [9b4a70fe2b](https://linux-hardware.org/?probe=9b4a70fe2b) | Jul 08, 2023 |
| Dell          | Inspiron 1764               | [2776a0f4ae](https://linux-hardware.org/?probe=2776a0f4ae) | Jul 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [28b061f34f](https://linux-hardware.org/?probe=28b061f34f) | Jul 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [63669f1312](https://linux-hardware.org/?probe=63669f1312) | Jul 08, 2023 |
| Dell          | Latitude 3189               | [cdf597586e](https://linux-hardware.org/?probe=cdf597586e) | Jul 08, 2023 |
| Dell          | Latitude 5540               | [1bd623d7b0](https://linux-hardware.org/?probe=1bd623d7b0) | Jul 07, 2023 |
| Sony          | VGN-NS38E_S                 | [eac09b82f8](https://linux-hardware.org/?probe=eac09b82f8) | Jul 07, 2023 |
| Sony          | VGN-NS38E_S                 | [4302a878d3](https://linux-hardware.org/?probe=4302a878d3) | Jul 07, 2023 |
| Dell          | Inspiron 1525               | [5e712f5b0a](https://linux-hardware.org/?probe=5e712f5b0a) | Jul 07, 2023 |
| HP            | EliteBook 830 G8 Noteboo... | [25e1dec3b8](https://linux-hardware.org/?probe=25e1dec3b8) | Jul 07, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [a3fd5e4b9d](https://linux-hardware.org/?probe=a3fd5e4b9d) | Jul 07, 2023 |
| TECNO         | MEGABOOK T1                 | [63737caadb](https://linux-hardware.org/?probe=63737caadb) | Jul 07, 2023 |
| Apple         | MacBookPro16,1              | [f02c3b7b7c](https://linux-hardware.org/?probe=f02c3b7b7c) | Jul 07, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [702534e040](https://linux-hardware.org/?probe=702534e040) | Jul 07, 2023 |
| Lenovo        | ThinkPad T480 20L5000UUS    | [733b12f6a4](https://linux-hardware.org/?probe=733b12f6a4) | Jul 07, 2023 |
| Sony          | VPCSB25FB                   | [fda12b9c70](https://linux-hardware.org/?probe=fda12b9c70) | Jul 07, 2023 |
| HP            | 15                          | [34fee2ada6](https://linux-hardware.org/?probe=34fee2ada6) | Jul 07, 2023 |
| Dell          | Inspiron 5447               | [284afde913](https://linux-hardware.org/?probe=284afde913) | Jul 07, 2023 |
| Dell          | Inspiron 5447               | [22e09bd073](https://linux-hardware.org/?probe=22e09bd073) | Jul 07, 2023 |
| ASUSTek       | K55VJ                       | [cb30ecfbff](https://linux-hardware.org/?probe=cb30ecfbff) | Jul 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X321... | [d4c8c30176](https://linux-hardware.org/?probe=d4c8c30176) | Jul 06, 2023 |
| MECHREVO      | Jiaolong Series MRID6       | [c9ee671981](https://linux-hardware.org/?probe=c9ee671981) | Jul 06, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [681a43f02f](https://linux-hardware.org/?probe=681a43f02f) | Jul 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [f003f0aa32](https://linux-hardware.org/?probe=f003f0aa32) | Jul 06, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [6539d1f91c](https://linux-hardware.org/?probe=6539d1f91c) | Jul 06, 2023 |
| Dell          | Latitude E6420              | [620b3c9397](https://linux-hardware.org/?probe=620b3c9397) | Jul 06, 2023 |
| Acer          | TravelMate P215-53          | [d759c2c726](https://linux-hardware.org/?probe=d759c2c726) | Jul 06, 2023 |
| Medion        | ML-210007                   | [192b83694f](https://linux-hardware.org/?probe=192b83694f) | Jul 06, 2023 |
| Medion        | ML-210007                   | [8bc97d58d2](https://linux-hardware.org/?probe=8bc97d58d2) | Jul 06, 2023 |
| HP            | Laptop 17-bs1xx             | [ec66938fb1](https://linux-hardware.org/?probe=ec66938fb1) | Jul 06, 2023 |
| HP            | Pavilion dv4 2055br         | [d06fc3c63a](https://linux-hardware.org/?probe=d06fc3c63a) | Jul 06, 2023 |
| HP            | ProBook 4540s               | [cccf56865c](https://linux-hardware.org/?probe=cccf56865c) | Jul 06, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [9b01a450b1](https://linux-hardware.org/?probe=9b01a450b1) | Jul 05, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [f603fed65f](https://linux-hardware.org/?probe=f603fed65f) | Jul 05, 2023 |
| HP            | 250 G7 Notebook PC          | [a3d75416d1](https://linux-hardware.org/?probe=a3d75416d1) | Jul 05, 2023 |
| Dell          | Studio 1749                 | [fe1e5d7b8f](https://linux-hardware.org/?probe=fe1e5d7b8f) | Jul 05, 2023 |
| HP            | ProBook 455 15.6 inch G9... | [bedadd4478](https://linux-hardware.org/?probe=bedadd4478) | Jul 05, 2023 |
| Dell          | Latitude 7440               | [2efee1eb6c](https://linux-hardware.org/?probe=2efee1eb6c) | Jul 05, 2023 |
| Acer          | Aspire V5-471G              | [6dd5e93eea](https://linux-hardware.org/?probe=6dd5e93eea) | Jul 05, 2023 |
| Medion        | X782X                       | [7369e18cc2](https://linux-hardware.org/?probe=7369e18cc2) | Jul 05, 2023 |
| Lenovo        | ThinkPad E15 20RD0011UK     | [bb0e10ceef](https://linux-hardware.org/?probe=bb0e10ceef) | Jul 05, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | [d990795943](https://linux-hardware.org/?probe=d990795943) | Jul 05, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Ubuntu_22.04/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.15.0-56-generic | 422       | 6.33%   |
| 5.15.0-52-generic | 374       | 5.61%   |
| 5.15.0-58-generic | 345       | 5.18%   |
| 5.19.0-32-generic | 301       | 4.52%   |
| 5.15.0-48-generic | 292       | 4.38%   |
| 6.2.0-26-generic  | 290       | 4.35%   |
| 5.15.0-43-generic | 290       | 4.35%   |
| 5.19.0-35-generic | 276       | 4.14%   |
| 5.15.0-47-generic | 254       | 3.81%   |
| 5.19.0-41-generic | 238       | 3.57%   |
| 5.15.0-46-generic | 235       | 3.53%   |
| 5.19.0-46-generic | 227       | 3.41%   |
| 5.15.0-53-generic | 211       | 3.17%   |
| 5.19.0-38-generic | 199       | 2.99%   |
| 5.15.0-25-generic | 187       | 2.81%   |
| 5.15.0-27-generic | 175       | 2.63%   |
| 5.15.0-41-generic | 167       | 2.51%   |
| 5.19.0-43-generic | 157       | 2.36%   |
| 5.15.0-40-generic | 156       | 2.34%   |
| 5.15.0-50-generic | 145       | 2.18%   |
| 5.15.0-60-generic | 127       | 1.91%   |
| 5.19.0-45-generic | 113       | 1.7%    |
| 5.15.0-33-generic | 108       | 1.62%   |
| 5.15.0-57-generic | 103       | 1.55%   |
| 5.19.0-40-generic | 89        | 1.34%   |
| 5.19.0-50-generic | 87        | 1.31%   |
| 5.15.0-30-generic | 87        | 1.31%   |
| 5.15.0-39-generic | 74        | 1.11%   |
| 5.19.0-42-generic | 73        | 1.1%    |
| 6.2.0-31-generic  | 60        | 0.9%    |
| 5.15.0-37-generic | 57        | 0.86%   |
| 5.15.0-35-generic | 46        | 0.69%   |
| 6.2.0-32-generic  | 30        | 0.45%   |
| 5.15.0-71-generic | 29        | 0.44%   |
| 5.15.0-67-generic | 24        | 0.36%   |
| 5.15.0-23-generic | 21        | 0.32%   |
| 5.15.0-69-generic | 20        | 0.3%    |
| 5.15.0-76-generic | 18        | 0.27%   |
| 5.15.0-78-generic | 14        | 0.21%   |
| 5.15.0-18-generic | 13        | 0.2%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 3866      | 61.47%  |
| 5.19.0  | 1683      | 26.76%  |
| 6.2.0   | 388       | 6.17%   |
| 5.17.0  | 59        | 0.94%   |
| 5.14.0  | 32        | 0.51%   |
| 6.0.0   | 21        | 0.33%   |
| 6.1.0   | 19        | 0.3%    |
| 5.13.0  | 13        | 0.21%   |
| 5.18.0  | 9         | 0.14%   |
| 6.2.11  | 8         | 0.13%   |
| 6.3.1   | 7         | 0.11%   |
| 5.19.5  | 7         | 0.11%   |
| 5.17.1  | 7         | 0.11%   |
| 6.4.0   | 6         | 0.1%    |
| 6.2.2   | 6         | 0.1%    |
| 6.0.9   | 6         | 0.1%    |
| 6.2.8   | 5         | 0.08%   |
| 5.17.5  | 5         | 0.08%   |
| 6.4.10  | 4         | 0.06%   |
| 6.2.10  | 4         | 0.06%   |
| 6.0.6   | 4         | 0.06%   |
| 5.4.0   | 4         | 0.06%   |
| 5.13.19 | 4         | 0.06%   |
| 6.3.3   | 3         | 0.05%   |
| 6.2.9   | 3         | 0.05%   |
| 6.2.6   | 3         | 0.05%   |
| 6.2.1   | 3         | 0.05%   |
| 6.1.12  | 3         | 0.05%   |
| 5.18.8  | 3         | 0.05%   |
| 5.17.9  | 3         | 0.05%   |
| 5.17.8  | 3         | 0.05%   |
| 5.17.2  | 3         | 0.05%   |
| 5.16.0  | 3         | 0.05%   |
| 6.5.0   | 2         | 0.03%   |
| 6.4.11  | 2         | 0.03%   |
| 6.3.7   | 2         | 0.03%   |
| 6.2.7   | 2         | 0.03%   |
| 6.2.5   | 2         | 0.03%   |
| 6.2.12  | 2         | 0.03%   |
| 6.1.9   | 2         | 0.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 3881      | 61.77%  |
| 5.19    | 1698      | 27.03%  |
| 6.2     | 425       | 6.76%   |
| 5.17    | 87        | 1.38%   |
| 6.0     | 39        | 0.62%   |
| 6.1     | 32        | 0.51%   |
| 5.14    | 32        | 0.51%   |
| 5.18    | 25        | 0.4%    |
| 5.13    | 17        | 0.27%   |
| 6.4     | 16        | 0.25%   |
| 6.3     | 14        | 0.22%   |
| 5.16    | 5         | 0.08%   |
| 5.4     | 4         | 0.06%   |
| 6.5     | 3         | 0.05%   |
| 5.11    | 2         | 0.03%   |
| 6       | 1         | 0.02%   |
| 5.8     | 1         | 0.02%   |
| 5.10    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 6064      | 99.98%  |
| aarch64 | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| GNOME             | 5846      | 96.2%   |
| Unknown           | 118       | 1.94%   |
| X-Cinnamon        | 44        | 0.72%   |
| GNOME Flashback   | 29        | 0.48%   |
| i3                | 11        | 0.18%   |
| GNOME Classic     | 7         | 0.12%   |
| sway              | 5         | 0.08%   |
| Cinnamon          | 4         | 0.07%   |
| awesome           | 3         | 0.05%   |
| Enlightenment     | 2         | 0.03%   |
| dwm               | 2         | 0.03%   |
| Yaru:ubuntu:GNOME | 1         | 0.02%   |
| xsession          | 1         | 0.02%   |
| ratflow           | 1         | 0.02%   |
| Pantheon          | 1         | 0.02%   |
| GNUstep           | 1         | 0.02%   |
| fluxbox           | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 4218      | 68.36%  |
| X11     | 1800      | 29.17%  |
| Unknown | 109       | 1.77%   |
| Tty     | 43        | 0.7%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GDM3    | 5612      | 92.12%  |
| Unknown | 343       | 5.63%   |
| LightDM | 85        | 1.4%    |
| GDM     | 26        | 0.43%   |
| SDDM    | 20        | 0.33%   |
| SLiM    | 5         | 0.08%   |
| XDM     | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 2831      | 46.53%  |
| de_DE   | 458       | 7.53%   |
| fr_FR   | 359       | 5.9%    |
| en_GB   | 292       | 4.8%    |
| pt_BR   | 247       | 4.06%   |
| en_IN   | 231       | 3.8%    |
| it_IT   | 196       | 3.22%   |
| ru_RU   | 174       | 2.86%   |
| es_ES   | 147       | 2.42%   |
| en_CA   | 126       | 2.07%   |
| pl_PL   | 85        | 1.4%    |
| en_AU   | 70        | 1.15%   |
| nl_NL   | 57        | 0.94%   |
| zh_CN   | 54        | 0.89%   |
| es_MX   | 45        | 0.74%   |
| Unknown | 44        | 0.72%   |
| hu_HU   | 43        | 0.71%   |
| en_ZA   | 37        | 0.61%   |
| es_AR   | 36        | 0.59%   |
| C       | 33        | 0.54%   |
| cs_CZ   | 31        | 0.51%   |
| pt_PT   | 29        | 0.48%   |
| tr_TR   | 28        | 0.46%   |
| sv_SE   | 27        | 0.44%   |
| es_CO   | 25        | 0.41%   |
| de_AT   | 23        | 0.38%   |
| en_PH   | 22        | 0.36%   |
| de_CH   | 18        | 0.3%    |
| es_CL   | 17        | 0.28%   |
| en_IL   | 17        | 0.28%   |
| en_NZ   | 16        | 0.26%   |
| da_DK   | 15        | 0.25%   |
| nb_NO   | 14        | 0.23%   |
| ko_KR   | 13        | 0.21%   |
| fr_BE   | 13        | 0.21%   |
| fi_FI   | 13        | 0.21%   |
| ja_JP   | 12        | 0.2%    |
| en_IE   | 12        | 0.2%    |
| ro_RO   | 11        | 0.18%   |
| en_SG   | 11        | 0.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 3344      | 54.5%   |
| EFI  | 2792      | 45.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 5070      | 82.07%  |
| Tmpfs   | 737       | 11.93%  |
| Overlay | 156       | 2.53%   |
| Zfs     | 138       | 2.23%   |
| Btrfs   | 51        | 0.83%   |
| Xfs     | 10        | 0.16%   |
| Ext3    | 8         | 0.13%   |
| Ext2    | 7         | 0.11%   |
| XXX4    | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 4437      | 72.04%  |
| Unknown | 1266      | 20.56%  |
| MBR     | 456       | 7.4%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 5623      | 92.07%  |
| Yes       | 484       | 7.93%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3898      | 63.86%  |
| Yes       | 2206      | 36.14%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 1233      | 20.33%  |
| Hewlett-Packard        | 1122      | 18.5%   |
| Dell                   | 1045      | 17.23%  |
| ASUSTek Computer       | 642       | 10.59%  |
| Acer                   | 473       | 7.8%    |
| Apple                  | 183       | 3.02%   |
| MSI                    | 165       | 2.72%   |
| HUAWEI                 | 151       | 2.49%   |
| Toshiba                | 128       | 2.11%   |
| Samsung Electronics    | 97        | 1.6%    |
| Sony                   | 60        | 0.99%   |
| Notebook               | 54        | 0.89%   |
| Unknown                | 44        | 0.73%   |
| Timi                   | 43        | 0.71%   |
| Google                 | 41        | 0.68%   |
| Fujitsu                | 38        | 0.63%   |
| Alienware              | 34        | 0.56%   |
| Medion                 | 30        | 0.49%   |
| Positivo               | 23        | 0.38%   |
| Packard Bell           | 22        | 0.36%   |
| Chuwi                  | 20        | 0.33%   |
| TUXEDO                 | 19        | 0.31%   |
| LG Electronics         | 19        | 0.31%   |
| HONOR                  | 15        | 0.25%   |
| Gigabyte Technology    | 15        | 0.25%   |
| System76               | 14        | 0.23%   |
| Gateway                | 14        | 0.23%   |
| Avell High Performance | 14        | 0.23%   |
| Razer                  | 12        | 0.2%    |
| Framework              | 12        | 0.2%    |
| Schenker               | 10        | 0.16%   |
| Panasonic              | 10        | 0.16%   |
| Teclast                | 9         | 0.15%   |
| GPU Company            | 9         | 0.15%   |
| AZW                    | 8         | 0.13%   |
| AMI                    | 7         | 0.12%   |
| PC Specialist          | 6         | 0.1%    |
| Monster                | 6         | 0.1%    |
| Jumper                 | 6         | 0.1%    |
| Intel                  | 6         | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Unknown                         | 62        | 1.02%   |
| HP Notebook                     | 29        | 0.48%   |
| Dell Latitude 5420              | 20        | 0.33%   |
| HP Pavilion Notebook            | 18        | 0.3%    |
| HUAWEI BOD-WXX9                 | 17        | 0.28%   |
| HP Pavilion g6                  | 17        | 0.28%   |
| HP Pavilion dv6                 | 17        | 0.28%   |
| Dell XPS 15 9520                | 17        | 0.28%   |
| HUAWEI HVY-WXX9                 | 16        | 0.26%   |
| HUAWEI BOM-WXX9                 | 15        | 0.25%   |
| HP Pavilion dv7                 | 15        | 0.25%   |
| HP Pavilion 15                  | 15        | 0.25%   |
| HP EliteBook 840 G8 Notebook PC | 15        | 0.25%   |
| HP EliteBook 840 G3             | 15        | 0.25%   |
| HP 15                           | 15        | 0.25%   |
| HP EliteBook 840 G5             | 14        | 0.23%   |
| Dell XPS 15 9500                | 14        | 0.23%   |
| HUAWEI NBLB-WAX9N               | 13        | 0.21%   |
| HP EliteBook 8470p              | 13        | 0.21%   |
| Dell XPS 15 7590                | 13        | 0.21%   |
| HUAWEI NBLK-WAX9X               | 12        | 0.2%    |
| HUAWEI BOHB-WAX9                | 12        | 0.2%    |
| HP Pavilion g7                  | 12        | 0.2%    |
| Dell XPS 9320                   | 12        | 0.2%    |
| Dell XPS 15 9570                | 12        | 0.2%    |
| Dell XPS 13 9370                | 12        | 0.2%    |
| Apple MacBookPro9,2             | 12        | 0.2%    |
| Acer Aspire E5-571              | 12        | 0.2%    |
| Lenovo ThinkBook 15 G2 ITL 20VE | 11        | 0.18%   |
| HP Laptop 15-db0xxx             | 11        | 0.18%   |
| Dell XPS 13 9380                | 11        | 0.18%   |
| Dell XPS 13 7390                | 11        | 0.18%   |
| Dell Latitude E6420             | 11        | 0.18%   |
| Dell Latitude 7420              | 11        | 0.18%   |
| Apple MacBookPro8,1             | 11        | 0.18%   |
| Timi TM1701                     | 10        | 0.16%   |
| HUAWEI KLVD-WXX9                | 10        | 0.16%   |
| HP Laptop 15s-eq2xxx            | 10        | 0.16%   |
| HP EliteBook 840 G1             | 10        | 0.16%   |
| Dell Vostro 3500                | 10        | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 612       | 10.09%  |
| Dell Latitude         | 374       | 6.17%   |
| Acer Aspire           | 323       | 5.33%   |
| Lenovo IdeaPad        | 300       | 4.95%   |
| Dell Inspiron         | 259       | 4.27%   |
| HP Pavilion           | 229       | 3.78%   |
| HP EliteBook          | 217       | 3.58%   |
| ASUS VivoBook         | 180       | 2.97%   |
| Dell XPS              | 166       | 2.74%   |
| HP ProBook            | 163       | 2.69%   |
| HP Laptop             | 158       | 2.61%   |
| Toshiba Satellite     | 103       | 1.7%    |
| Dell Precision        | 99        | 1.63%   |
| Dell Vostro           | 80        | 1.32%   |
| Lenovo ThinkBook      | 69        | 1.14%   |
| Lenovo Legion         | 67        | 1.1%    |
| ASUS ROG              | 67        | 1.1%    |
| Unknown               | 62        | 1.02%   |
| ASUS ZenBook          | 61        | 1.01%   |
| HP ZBook              | 56        | 0.92%   |
| Acer Swift            | 49        | 0.81%   |
| ASUS ASUS             | 48        | 0.79%   |
| HP ENVY               | 47        | 0.77%   |
| Acer Nitro            | 41        | 0.68%   |
| Fujitsu LIFEBOOK      | 32        | 0.53%   |
| HP OMEN               | 30        | 0.49%   |
| HP Notebook           | 30        | 0.49%   |
| Dell G15              | 29        | 0.48%   |
| HP 250                | 28        | 0.46%   |
| HP 255                | 27        | 0.45%   |
| Lenovo Yoga           | 22        | 0.36%   |
| Apple MacBookPro8     | 22        | 0.36%   |
| HP 15                 | 21        | 0.35%   |
| Apple MacBookPro11    | 21        | 0.35%   |
| Packard Bell EasyNote | 20        | 0.33%   |
| HP Compaq             | 20        | 0.33%   |
| Acer TravelMate       | 19        | 0.31%   |
| MSI Katana            | 18        | 0.3%    |
| MSI GF63              | 17        | 0.28%   |
| HUAWEI BOD-WXX9       | 17        | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 967       | 15.94%  |
| 2020    | 720       | 11.87%  |
| 2022    | 541       | 8.92%   |
| 2019    | 527       | 8.69%   |
| 2018    | 442       | 7.29%   |
| 2013    | 372       | 6.13%   |
| 2012    | 365       | 6.02%   |
| 2017    | 344       | 5.67%   |
| 2011    | 335       | 5.52%   |
| 2014    | 303       | 5%      |
| 2015    | 279       | 4.6%    |
| 2016    | 272       | 4.48%   |
| 2010    | 231       | 3.81%   |
| 2008    | 122       | 2.01%   |
| 2009    | 108       | 1.78%   |
| 2023    | 78        | 1.29%   |
| 2007    | 37        | 0.61%   |
| 2006    | 16        | 0.26%   |
| Unknown | 6         | 0.1%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 6065      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 5240      | 85.82%  |
| Enabled  | 866       | 14.18%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 6015      | 99.18%  |
| Yes  | 50        | 0.82%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1830      | 30.07%  |
| 16.01-24.0  | 1322      | 21.72%  |
| 8.01-16.0   | 1014      | 16.66%  |
| 3.01-4.0    | 995       | 16.35%  |
| 32.01-64.0  | 556       | 9.14%   |
| 1.01-2.0    | 107       | 1.76%   |
| 64.01-256.0 | 106       | 1.74%   |
| 24.01-32.0  | 99        | 1.63%   |
| 2.01-3.0    | 54        | 0.89%   |
| 0.51-1.0    | 3         | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 2026      | 31.73%  |
| 1.01-2.0   | 1691      | 26.48%  |
| 4.01-8.0   | 1186      | 18.57%  |
| 3.01-4.0   | 1064      | 16.66%  |
| 8.01-16.0  | 321       | 5.03%   |
| 0.51-1.0   | 42        | 0.66%   |
| 16.01-24.0 | 35        | 0.55%   |
| 24.01-32.0 | 12        | 0.19%   |
| 0.01-0.5   | 5         | 0.08%   |
| 32.01-64.0 | 4         | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 4709      | 76.98%  |
| 2      | 1244      | 20.34%  |
| 3      | 106       | 1.73%   |
| 0      | 41        | 0.67%   |
| 4      | 13        | 0.21%   |
| 7      | 2         | 0.03%   |
| 5      | 2         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 4419      | 72.67%  |
| Yes       | 1662      | 27.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4565      | 75.09%  |
| No        | 1514      | 24.91%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 5971      | 98.4%   |
| No        | 97        | 1.6%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 5042      | 82.57%  |
| No        | 1064      | 17.43%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 922       | 15.14%  |
| Germany      | 608       | 9.98%   |
| France       | 439       | 7.21%   |
| Brazil       | 338       | 5.55%   |
| Italy        | 286       | 4.7%    |
| India        | 260       | 4.27%   |
| Russia       | 241       | 3.96%   |
| UK           | 233       | 3.83%   |
| Spain        | 184       | 3.02%   |
| Poland       | 169       | 2.77%   |
| Canada       | 150       | 2.46%   |
| Netherlands  | 144       | 2.36%   |
| Mexico       | 91        | 1.49%   |
| Turkey       | 88        | 1.44%   |
| Sweden       | 79        | 1.3%    |
| Hungary      | 73        | 1.2%    |
| Argentina    | 69        | 1.13%   |
| Australia    | 66        | 1.08%   |
| Portugal     | 62        | 1.02%   |
| Czechia      | 62        | 1.02%   |
| Belgium      | 62        | 1.02%   |
| China        | 60        | 0.99%   |
| Switzerland  | 55        | 0.9%    |
| Austria      | 55        | 0.9%    |
| Romania      | 54        | 0.89%   |
| Indonesia    | 51        | 0.84%   |
| Greece       | 47        | 0.77%   |
| Colombia     | 46        | 0.76%   |
| South Africa | 39        | 0.64%   |
| Denmark      | 37        | 0.61%   |
| Finland      | 36        | 0.59%   |
| Bulgaria     | 36        | 0.59%   |
| Chile        | 34        | 0.56%   |
| Iran         | 33        | 0.54%   |
| Egypt        | 32        | 0.53%   |
| Serbia       | 30        | 0.49%   |
| Pakistan     | 30        | 0.49%   |
| Japan        | 28        | 0.46%   |
| Ireland      | 27        | 0.44%   |
| Vietnam      | 26        | 0.43%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Paris             | 72        | 1.14%   |
| Berlin            | 64        | 1.02%   |
| Moscow            | 63        | 1%      |
| Milan             | 51        | 0.81%   |
| Madrid            | 47        | 0.75%   |
| St Petersburg     | 45        | 0.71%   |
| Warsaw            | 44        | 0.7%    |
| Budapest          | 38        | 0.6%    |
| Rome              | 37        | 0.59%   |
| Sao Paulo         | 36        | 0.57%   |
| Vienna            | 32        | 0.51%   |
| Istanbul          | 31        | 0.49%   |
| Bengaluru         | 30        | 0.48%   |
| Barcelona         | 28        | 0.44%   |
| Munich            | 26        | 0.41%   |
| Hamburg           | 25        | 0.4%    |
| Sydney            | 24        | 0.38%   |
| Rio de Janeiro    | 23        | 0.36%   |
| Prague            | 23        | 0.36%   |
| Athens            | 23        | 0.36%   |
| Amsterdam         | 23        | 0.36%   |
| Toronto           | 22        | 0.35%   |
| Tehran            | 22        | 0.35%   |
| Nairobi           | 22        | 0.35%   |
| London            | 22        | 0.35%   |
| Helsinki          | 21        | 0.33%   |
| Frankfurt am Main | 21        | 0.33%   |
| Belgrade          | 21        | 0.33%   |
| Stockholm         | 20        | 0.32%   |
| Mexico City       | 20        | 0.32%   |
| Los Angeles       | 20        | 0.32%   |
| Dublin            | 20        | 0.32%   |
| Denver            | 20        | 0.32%   |
| Bogotá           | 20        | 0.32%   |
| Singapore         | 19        | 0.3%    |
| New York          | 19        | 0.3%    |
| Cape Town         | 19        | 0.3%    |
| Sofia             | 18        | 0.29%   |
| Santiago          | 18        | 0.29%   |
| Pune              | 18        | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 1275      | 1521   | 17.6%   |
| WDC                         | 709       | 812    | 9.79%   |
| Seagate                     | 577       | 681    | 7.97%   |
| Toshiba                     | 476       | 529    | 6.57%   |
| SanDisk                     | 470       | 555    | 6.49%   |
| SK hynix                    | 394       | 429    | 5.44%   |
| Kingston                    | 363       | 407    | 5.01%   |
| Unknown                     | 339       | 410    | 4.68%   |
| Micron Technology           | 302       | 330    | 4.17%   |
| Intel                       | 273       | 337    | 3.77%   |
| Crucial                     | 220       | 256    | 3.04%   |
| KIOXIA                      | 178       | 197    | 2.46%   |
| HGST                        | 159       | 173    | 2.19%   |
| Hitachi                     | 156       | 191    | 2.15%   |
| Apple                       | 108       | 126    | 1.49%   |
| A-DATA Technology           | 97        | 111    | 1.34%   |
| Phison                      | 72        | 79     | 0.99%   |
| Unknown                     | 63        | 65     | 0.87%   |
| China                       | 55        | 67     | 0.76%   |
| Silicon Motion              | 48        | 56     | 0.66%   |
| LITEON                      | 47        | 51     | 0.65%   |
| Kingston Technology Company | 41        | 46     | 0.57%   |
| SPCC                        | 39        | 45     | 0.54%   |
| Intenso                     | 34        | 43     | 0.47%   |
| Netac                       | 33        | 37     | 0.46%   |
| PNY                         | 29        | 33     | 0.4%    |
| SSSTC                       | 27        | 29     | 0.37%   |
| Phison Electronics          | 27        | 29     | 0.37%   |
| Micron/Crucial Technology   | 27        | 29     | 0.37%   |
| ADATA Technology            | 21        | 25     | 0.29%   |
| Transcend                   | 20        | 23     | 0.28%   |
| Fujitsu                     | 20        | 23     | 0.28%   |
| GOODRAM                     | 19        | 21     | 0.26%   |
| UMIS                        | 17        | 18     | 0.23%   |
| LITEONIT                    | 17        | 24     | 0.23%   |
| JMicron Technology          | 16        | 18     | 0.22%   |
| Gigabyte Technology         | 16        | 17     | 0.22%   |
| Team                        | 15        | 16     | 0.21%   |
| Patriot                     | 14        | 16     | 0.19%   |
| KingSpec                    | 13        | 13     | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                        | 86        | 1.15%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB   | 81        | 1.08%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 67        | 0.9%    |
| Kingston SA400S37240G 240GB SSD                       | 66        | 0.88%   |
| Toshiba MQ04ABF100 1TB                                | 65        | 0.87%   |
| Unknown                                               | 63        | 0.84%   |
| Unknown MMC Card  64GB                                | 62        | 0.83%   |
| Toshiba MQ01ABD100 1TB                                | 62        | 0.83%   |
| Unknown MMC Card  32GB                                | 61        | 0.82%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1024GB | 47        | 0.63%   |
| Intel SSDPEKNU512GZ 512GB                             | 45        | 0.6%    |
| Toshiba MQ01ABF050 500GB                              | 42        | 0.56%   |
| Seagate ST500LT012-1DG142 500GB                       | 42        | 0.56%   |
| Samsung SSD 860 EVO 500GB                             | 39        | 0.52%   |
| HGST HTS721010A9E630 1TB                              | 39        | 0.52%   |
| Samsung NVMe SSD Drive 512GB                          | 38        | 0.51%   |
| Seagate ST9500325AS 500GB                             | 37        | 0.5%    |
| Sandisk WD Blue SN550 NVMe SSD 250GB                  | 37        | 0.5%    |
| Crucial CT500MX500SSD1 500GB                          | 36        | 0.48%   |
| Kingston SA400S37480G 480GB SSD                       | 35        | 0.47%   |
| SanDisk NVMe SSD Drive 512GB                          | 34        | 0.46%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB     | 33        | 0.44%   |
| KIOXIA KBG40ZNS512G NVMe 512GB                        | 33        | 0.44%   |
| Phison 311CD0512GB                                    | 32        | 0.43%   |
| Samsung MZALQ512HALU-000L2 512GB                      | 31        | 0.42%   |
| HGST HTS545050A7E680 500GB                            | 30        | 0.4%    |
| HGST HTS541010A9E680 1TB                              | 30        | 0.4%    |
| KIOXIA KBG40ZNV512G 512GB                             | 29        | 0.39%   |
| Samsung SSD 850 EVO 500GB                             | 28        | 0.37%   |
| Micron 2450_MTFDKBA512TFK 512GB                       | 28        | 0.37%   |
| Intel SSD 660P Series 512GB                           | 28        | 0.37%   |
| Intel SSDPEKNW512G8 512GB                             | 27        | 0.36%   |
| Crucial CT240BX500SSD1 240GB                          | 27        | 0.36%   |
| Unknown MMC Card  128GB                               | 26        | 0.35%   |
| Samsung SSD 980 1TB                                   | 25        | 0.33%   |
| Samsung MZVL21T0HCLR-00B00 1TB                        | 25        | 0.33%   |
| Crucial CT1000MX500SSD1 1TB                           | 25        | 0.33%   |
| SanDisk NVMe SSD Drive 1TB                            | 24        | 0.32%   |
| Kingston SA400S37120G 120GB SSD                       | 24        | 0.32%   |
| WDC WD10JPVX-22JC3T0 1TB                              | 23        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 554       | 651    | 32.42%  |
| WDC                 | 406       | 459    | 23.76%  |
| Toshiba             | 312       | 338    | 18.26%  |
| HGST                | 159       | 173    | 9.3%    |
| Hitachi             | 155       | 190    | 9.07%   |
| Samsung Electronics | 35        | 41     | 2.05%   |
| Unknown             | 26        | 28     | 1.52%   |
| Fujitsu             | 20        | 23     | 1.17%   |
| SABRENT             | 8         | 8      | 0.47%   |
| Apple               | 7         | 7      | 0.41%   |
| ASMT                | 4         | 4      | 0.23%   |
| USB3.0              | 3         | 3      | 0.18%   |
| Intenso             | 3         | 3      | 0.18%   |
| External            | 3         | 9      | 0.18%   |
| USB                 | 2         | 2      | 0.12%   |
| SSK                 | 2         | 2      | 0.12%   |
| SAGE                | 2         | 2      | 0.12%   |
| StoreJet            | 1         | 1      | 0.06%   |
| PHD 3.0             | 1         | 1      | 0.06%   |
| MARSHAL             | 1         | 1      | 0.06%   |
| LaCie               | 1         | 1      | 0.06%   |
| JMicron Technology  | 1         | 1      | 0.06%   |
| Initio              | 1         | 1      | 0.06%   |
| HGST HTS            | 1         | 2      | 0.06%   |
| ASMedia             | 1         | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 422       | 495    | 20.68%  |
| Kingston            | 239       | 273    | 11.71%  |
| SanDisk             | 210       | 257    | 10.29%  |
| Crucial             | 188       | 219    | 9.21%   |
| WDC                 | 118       | 138    | 5.78%   |
| SK hynix            | 67        | 79     | 3.28%   |
| Micron Technology   | 60        | 66     | 2.94%   |
| China               | 53        | 61     | 2.6%    |
| Intel               | 47        | 50     | 2.3%    |
| Apple               | 46        | 50     | 2.25%   |
| A-DATA Technology   | 45        | 48     | 2.2%    |
| LITEON              | 43        | 47     | 2.11%   |
| Toshiba             | 39        | 43     | 1.91%   |
| SPCC                | 37        | 43     | 1.81%   |
| Netac               | 31        | 34     | 1.52%   |
| PNY                 | 26        | 29     | 1.27%   |
| Unknown             | 22        | 22     | 1.08%   |
| Intenso             | 19        | 23     | 0.93%   |
| Transcend           | 18        | 21     | 0.88%   |
| LITEONIT            | 17        | 24     | 0.83%   |
| GOODRAM             | 17        | 19     | 0.83%   |
| Team                | 14        | 14     | 0.69%   |
| Patriot             | 14        | 16     | 0.69%   |
| KingSpec            | 12        | 12     | 0.59%   |
| Gigabyte Technology | 11        | 11     | 0.54%   |
| Lexar               | 9         | 10     | 0.44%   |
| JMicron Technology  | 9         | 9      | 0.44%   |
| Teclast             | 8         | 9      | 0.39%   |
| OCZ                 | 8         | 8      | 0.39%   |
| Hewlett-Packard     | 8         | 15     | 0.39%   |
| Apacer              | 8         | 8      | 0.39%   |
| Seagate             | 7         | 9      | 0.34%   |
| BIWIN               | 7         | 7      | 0.34%   |
| BHT                 | 7         | 9      | 0.34%   |
| Emtec               | 6         | 7      | 0.29%   |
| Corsair             | 6         | 6      | 0.29%   |
| Verbatim            | 5         | 5      | 0.24%   |
| SSSTC               | 4         | 5      | 0.2%    |
| Plextor             | 4         | 4      | 0.2%    |
| Phison              | 4         | 5      | 0.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 2923      | 3501   | 41.97%  |
| SSD     | 1927      | 2355   | 27.67%  |
| HDD     | 1658      | 1952   | 23.81%  |
| MMC     | 343       | 417    | 4.93%   |
| Unknown | 113       | 136    | 1.62%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3239      | 4161   | 48.13%  |
| NVMe | 2919      | 3492   | 43.37%  |
| MMC  | 343       | 417    | 5.1%    |
| SAS  | 229       | 291    | 3.4%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2281      | 2808   | 64.22%  |
| 0.51-1.0   | 1136      | 1337   | 31.98%  |
| 1.01-2.0   | 102       | 122    | 2.87%   |
| 4.01-10.0  | 22        | 25     | 0.62%   |
| 3.01-4.0   | 8         | 8      | 0.23%   |
| 2.01-3.0   | 3         | 7      | 0.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1931      | 31.21%  |
| 251-500        | 1868      | 30.19%  |
| 501-1000       | 1024      | 16.55%  |
| 51-100         | 373       | 6.03%   |
| 1-20           | 295       | 4.77%   |
| 1001-2000      | 272       | 4.4%    |
| 21-50          | 232       | 3.75%   |
| More than 3000 | 75        | 1.21%   |
| 2001-3000      | 62        | 1%      |
| Unknown        | 56        | 0.9%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 2253      | 35.37%  |
| 21-50          | 1447      | 22.72%  |
| 51-100         | 956       | 15.01%  |
| 101-250        | 887       | 13.93%  |
| 251-500        | 443       | 6.96%   |
| 501-1000       | 220       | 3.45%   |
| 1001-2000      | 69        | 1.08%   |
| Unknown        | 56        | 0.88%   |
| More than 3000 | 24        | 0.38%   |
| 2001-3000      | 14        | 0.22%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB        | 9         | 9      | 3.47%   |
| Toshiba MQ01ABD100 1TB                | 6         | 6      | 2.32%   |
| Seagate ST9500325AS 500GB             | 6         | 6      | 2.32%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 6         | 7      | 2.32%   |
| HGST HTS541010A9E680 1TB              | 6         | 6      | 2.32%   |
| SK hynix BC711 HFM512GD3JX013N 512GB  | 5         | 5      | 1.93%   |
| Toshiba MQ04ABF100 1TB                | 4         | 4      | 1.54%   |
| Seagate ST500LT012-9WS142 500GB       | 4         | 4      | 1.54%   |
| Seagate ST500LT012-1DG142 500GB       | 4         | 4      | 1.54%   |
| Seagate ST1000LX015-1U7172 1TB        | 4         | 4      | 1.54%   |
| Seagate ST1000LM014-1EJ164 1TB        | 4         | 5      | 1.54%   |
| WDC WD10JPVX-60JC3T0 1TB              | 3         | 3      | 1.16%   |
| WDC WD10JPCX-24UE4T0 1TB              | 3         | 3      | 1.16%   |
| Seagate ST9320325AS 320GB             | 3         | 3      | 1.16%   |
| Seagate ST1000LM014-SSHD-8GB          | 3         | 3      | 1.16%   |
| Hitachi HTS547550A9E384 500GB         | 3         | 3      | 1.16%   |
| Hitachi HTS545050A7E380 500GB         | 3         | 3      | 1.16%   |
| Hitachi HTS543232A7A384 320GB         | 3         | 3      | 1.16%   |
| HGST HTS725050A7E630 500GB            | 3         | 3      | 1.16%   |
| HGST HTS721010A9E630 1TB              | 3         | 3      | 1.16%   |
| HGST HTS545050A7E680 500GB            | 3         | 3      | 1.16%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 2         | 2      | 0.77%   |
| WDC WD5000LPCX-60VHAT0 500GB          | 2         | 2      | 0.77%   |
| Toshiba MQ01ABD050 500GB              | 2         | 2      | 0.77%   |
| SK hynix HFS512G39TND-N210A 512GB SSD | 2         | 2      | 0.77%   |
| SK hynix HFS256G39TND-N210A 256GB SSD | 2         | 2      | 0.77%   |
| Seagate ST9500420AS 500GB             | 2         | 2      | 0.77%   |
| Seagate ST500LM021-1KJ152 500GB       | 2         | 2      | 0.77%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 2         | 3      | 0.77%   |
| Seagate ST1000LM049-2GH172 1TB        | 2         | 2      | 0.77%   |
| Micron Technology 1100 SATA 256GB SSD | 2         | 2      | 0.77%   |
| Intel SSDSC2BF180A5L 180GB            | 2         | 2      | 0.77%   |
| Hitachi HTS547564A9E384 640GB         | 2         | 2      | 0.77%   |
| HGST HTS541075A9E680 752GB            | 2         | 2      | 0.77%   |
| Crucial CT275MX300SSD4 275GB          | 2         | 2      | 0.77%   |
| WDC WDS480G2G0A-00JH30 480GB SSD      | 1         | 1      | 0.39%   |
| WDC WDS120G2G0A-00JH30 120GB SSD      | 1         | 1      | 0.39%   |
| WDC WD7500BPVT-24HXZT3 752GB          | 1         | 1      | 0.39%   |
| WDC WD7500BPKT-22PK4T0 752GB          | 1         | 1      | 0.39%   |
| WDC WD6000HLHX-01JJPV0 600GB          | 1         | 1      | 0.39%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 59        | 64     | 22.87%  |
| WDC                 | 36        | 38     | 13.95%  |
| Toshiba             | 26        | 27     | 10.08%  |
| SK hynix            | 22        | 22     | 8.53%   |
| Hitachi             | 22        | 23     | 8.53%   |
| HGST                | 20        | 20     | 7.75%   |
| Samsung Electronics | 12        | 12     | 4.65%   |
| SanDisk             | 10        | 11     | 3.88%   |
| Intel               | 10        | 10     | 3.88%   |
| Micron Technology   | 8         | 8      | 3.1%    |
| A-DATA Technology   | 5         | 6      | 1.94%   |
| LITEON              | 4         | 4      | 1.55%   |
| Crucial             | 4         | 4      | 1.55%   |
| Kingston            | 3         | 4      | 1.16%   |
| China               | 2         | 2      | 0.78%   |
| Apple               | 2         | 2      | 0.78%   |
| WALRAM              | 1         | 1      | 0.39%   |
| VISIPRO             | 1         | 1      | 0.39%   |
| tecmiyo             | 1         | 1      | 0.39%   |
| SSSTC               | 1         | 1      | 0.39%   |
| ShiJi               | 1         | 1      | 0.39%   |
| RX7                 | 1         | 1      | 0.39%   |
| Netac               | 1         | 1      | 0.39%   |
| LITEONIT            | 1         | 1      | 0.39%   |
| KingSpec            | 1         | 1      | 0.39%   |
| Intenso             | 1         | 1      | 0.39%   |
| HS-SSD-E100         | 1         | 1      | 0.39%   |
| Fujitsu             | 1         | 1      | 0.39%   |
| Corsair             | 1         | 1      | 0.39%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 59        | 64     | 36.88%  |
| WDC                 | 29        | 31     | 18.13%  |
| Toshiba             | 24        | 25     | 15%     |
| Hitachi             | 22        | 23     | 13.75%  |
| HGST                | 20        | 20     | 12.5%   |
| Samsung Electronics | 4         | 4      | 2.5%    |
| Fujitsu             | 1         | 1      | 0.63%   |
| Apple               | 1         | 1      | 0.63%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 159       | 169    | 61.87%  |
| SSD  | 73        | 75     | 28.4%   |
| NVMe | 25        | 26     | 9.73%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                                            | Notebooks | Drives | Percent |
|------------------------------------------------------------------|-----------|--------|---------|
| WDC WD7500BPVT-22HXZT1 752GB                                     | 1         | 1      | 20%     |
| WDC WD5000BEVT-22A0RT0 500GB                                     | 1         | 1      | 20%     |
| Samsung Electronics NVMe SSD Controller SM961/PM961/SM963 1024GB | 1         | 1      | 20%     |
| HGST HTS721010A9E630 1TB                                         | 1         | 1      | 20%     |
| Crucial M4-CT256M4SSD3 256GB                                     | 1         | 1      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 2      | 40%     |
| Samsung Electronics | 1         | 1      | 20%     |
| HGST                | 1         | 1      | 20%     |
| Crucial             | 1         | 1      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 3563      | 5034   | 56.45%  |
| Works    | 2490      | 3051   | 39.45%  |
| Malfunc  | 253       | 270    | 4.01%   |
| Failed   | 5         | 5      | 0.08%   |
| Fixed    | 1         | 1      | 0.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 3947      | 52.65%  |
| Samsung Electronics                     | 873       | 11.64%  |
| AMD                                     | 642       | 8.56%   |
| SanDisk                                 | 433       | 5.78%   |
| SK hynix                                | 315       | 4.2%    |
| Micron Technology                       | 242       | 3.23%   |
| KIOXIA                                  | 168       | 2.24%   |
| Kingston Technology Company             | 163       | 2.17%   |
| Toshiba America Info Systems            | 139       | 1.85%   |
| Phison Electronics                      | 104       | 1.39%   |
| ADATA Technology                        | 70        | 0.93%   |
| Silicon Motion                          | 66        | 0.88%   |
| Micron/Crucial Technology               | 61        | 0.81%   |
| Apple                                   | 51        | 0.68%   |
| Solid State Storage Technology          | 50        | 0.67%   |
| Nvidia                                  | 37        | 0.49%   |
| Union Memory (Shenzhen)                 | 27        | 0.36%   |
| Marvell Technology Group                | 16        | 0.21%   |
| Yangtze Memory Technologies             | 15        | 0.2%    |
| Shenzhen Longsys Electronics            | 13        | 0.17%   |
| Realtek Semiconductor                   | 10        | 0.13%   |
| Lite-On Technology                      | 9         | 0.12%   |
| Lenovo                                  | 7         | 0.09%   |
| Seagate Technology                      | 6         | 0.08%   |
| MAXIO Technology (Hangzhou)             | 6         | 0.08%   |
| Shenzhen Unionmemory Information System | 4         | 0.05%   |
| ASMedia Technology                      | 4         | 0.05%   |
| Unknown                                 | 4         | 0.05%   |
| Transcend                               | 3         | 0.04%   |
| Biwin Storage Technology                | 3         | 0.04%   |
| Silicon Integrated Systems [SiS]        | 2         | 0.03%   |
| INNOGRIT                                | 2         | 0.03%   |
| Zhaoxin                                 | 1         | 0.01%   |
| Ramaxel Technology(Shenzhen) Limited    | 1         | 0.01%   |
| Netac Technology                        | 1         | 0.01%   |
| JMicron Technology                      | 1         | 0.01%   |
| Jiangsu Huacun Elec.                    | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 569       | 7.18%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 477       | 6.02%   |
| Intel Volume Management Device NVMe RAID Controller                            | 435       | 5.49%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 372       | 4.69%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 342       | 4.32%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 299       | 3.77%   |
| Samsung NVMe SSD Controller 980                                                | 264       | 3.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 251       | 3.17%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 197       | 2.49%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 177       | 2.23%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 158       | 1.99%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 155       | 1.96%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 154       | 1.94%   |
| Intel Tiger Lake-LP SATA Controller                                            | 150       | 1.89%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 143       | 1.8%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 134       | 1.69%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 127       | 1.6%    |
| Intel Comet Lake SATA AHCI Controller                                          | 124       | 1.56%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 108       | 1.36%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 105       | 1.33%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 97        | 1.22%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 97        | 1.22%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 94        | 1.19%   |
| Intel SSD 660P Series                                                          | 79        | 1%      |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 75        | 0.95%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 75        | 0.95%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 68        | 0.86%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 68        | 0.86%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 68        | 0.86%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 67        | 0.85%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 67        | 0.85%   |
| Phison PS5013 E13 NVMe Controller                                              | 63        | 0.8%    |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 63        | 0.8%    |
| Intel Tiger Lake SATA AHCI Controller                                          | 61        | 0.77%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 59        | 0.74%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 59        | 0.74%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 58        | 0.73%   |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 53        | 0.67%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 52        | 0.66%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 51        | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 3811      | 49.51%  |
| NVMe | 2910      | 37.8%   |
| RAID | 800       | 10.39%  |
| IDE  | 177       | 2.3%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 4949      | 81.6%   |
| AMD          | 1114      | 18.37%  |
| Phytium      | 1         | 0.02%   |
| CentaurHauls | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 167       | 2.75%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 156       | 2.57%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 102       | 1.68%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 88        | 1.45%   |
| Intel 12th Gen Core i7-12700H                 | 86        | 1.42%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 81        | 1.34%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 80        | 1.32%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 74        | 1.22%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 71        | 1.17%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 70        | 1.15%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 69        | 1.14%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 69        | 1.14%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 68        | 1.12%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 66        | 1.09%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 65        | 1.07%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 64        | 1.06%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 64        | 1.06%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 62        | 1.02%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 62        | 1.02%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 61        | 1.01%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 53        | 0.87%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 53        | 0.87%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 52        | 0.86%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 52        | 0.86%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 49        | 0.81%   |
| Intel 12th Gen Core i7-1260P                  | 44        | 0.73%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 41        | 0.68%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 39        | 0.64%   |
| Intel 12th Gen Core i7-1255U                  | 39        | 0.64%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 39        | 0.64%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 38        | 0.63%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 38        | 0.63%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 38        | 0.63%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 37        | 0.61%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 35        | 0.58%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 33        | 0.54%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 33        | 0.54%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 32        | 0.53%   |
| Intel 12th Gen Core i5-1235U                  | 32        | 0.53%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 32        | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1405      | 23.17%  |
| Intel Core i7           | 1254      | 20.68%  |
| Other                   | 1071      | 17.66%  |
| Intel Core i3           | 432       | 7.12%   |
| Intel Celeron           | 350       | 5.77%   |
| AMD Ryzen 5             | 319       | 5.26%   |
| AMD Ryzen 7             | 298       | 4.91%   |
| Intel Core 2 Duo        | 150       | 2.47%   |
| Intel Pentium           | 127       | 2.09%   |
| AMD Ryzen 9             | 55        | 0.91%   |
| AMD A6                  | 55        | 0.91%   |
| Intel Atom              | 50        | 0.82%   |
| AMD Ryzen 3             | 50        | 0.82%   |
| AMD Ryzen 7 PRO         | 41        | 0.68%   |
| AMD A8                  | 41        | 0.68%   |
| AMD A4                  | 33        | 0.54%   |
| AMD A10                 | 30        | 0.49%   |
| Intel Pentium Dual-Core | 25        | 0.41%   |
| Intel Core i9           | 24        | 0.4%    |
| AMD E2                  | 24        | 0.4%    |
| Intel Pentium Dual      | 17        | 0.28%   |
| AMD Ryzen 5 PRO         | 17        | 0.28%   |
| AMD Athlon              | 17        | 0.28%   |
| AMD E1                  | 16        | 0.26%   |
| AMD E                   | 15        | 0.25%   |
| Intel Xeon              | 14        | 0.23%   |
| Intel Pentium Silver    | 12        | 0.2%    |
| Intel Core 2            | 11        | 0.18%   |
| AMD Turion 64 X2 Mobile | 9         | 0.15%   |
| Intel Genuine           | 8         | 0.13%   |
| Intel Core M            | 7         | 0.12%   |
| AMD Athlon II           | 7         | 0.12%   |
| Intel Core m3           | 6         | 0.1%    |
| Intel Celeron Dual-Core | 6         | 0.1%    |
| AMD Phenom II           | 6         | 0.1%    |
| AMD Sempron             | 5         | 0.08%   |
| AMD FX                  | 5         | 0.08%   |
| AMD A12                 | 5         | 0.08%   |
| AMD Turion 64 Mobile    | 4         | 0.07%   |
| AMD Athlon X2           | 4         | 0.07%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 2566      | 42.3%   |
| 4      | 2066      | 34.06%  |
| 8      | 516       | 8.51%   |
| 6      | 485       | 8%      |
| 14     | 164       | 2.7%    |
| 12     | 107       | 1.76%   |
| 10     | 100       | 1.65%   |
| 1      | 39        | 0.64%   |
| 16     | 13        | 0.21%   |
| 24     | 4         | 0.07%   |
| 3      | 4         | 0.07%   |
| 5      | 2         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 6065      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 4869      | 80.21%  |
| 1      | 1201      | 19.79%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 6064      | 99.98%  |
| Unknown        | 1         | 0.02%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 3314      | 53.49%  |
| 0x806c1    | 316       | 5.1%    |
| 0x806ec    | 209       | 3.37%   |
| 0x906a3    | 161       | 2.6%    |
| 0x806ea    | 144       | 2.32%   |
| 0x306a9    | 130       | 2.1%    |
| 0x0a50000c | 122       | 1.97%   |
| 0x206a7    | 99        | 1.6%    |
| 0x906ea    | 92        | 1.48%   |
| 0x08608103 | 91        | 1.47%   |
| 0x406e3    | 88        | 1.42%   |
| 0x40651    | 87        | 1.4%    |
| 0xa0652    | 82        | 1.32%   |
| 0x306d4    | 82        | 1.32%   |
| 0x806d1    | 80        | 1.29%   |
| 0x806e9    | 76        | 1.23%   |
| 0x706e5    | 70        | 1.13%   |
| 0x306c3    | 60        | 0.97%   |
| 0x706a8    | 59        | 0.95%   |
| 0x08600106 | 55        | 0.89%   |
| 0x08108109 | 55        | 0.89%   |
| 0x906a4    | 52        | 0.84%   |
| 0x20655    | 40        | 0.65%   |
| 0x906e9    | 33        | 0.53%   |
| 0x806eb    | 29        | 0.47%   |
| 0x506e3    | 27        | 0.44%   |
| 0x1067a    | 27        | 0.44%   |
| 0x30678    | 26        | 0.42%   |
| 0x0a50000d | 25        | 0.4%    |
| 0x08108102 | 24        | 0.39%   |
| 0x906ed    | 23        | 0.37%   |
| 0x506c9    | 22        | 0.36%   |
| 0x0a404102 | 22        | 0.36%   |
| 0x08600104 | 22        | 0.36%   |
| 0x706a1    | 21        | 0.34%   |
| 0x06006705 | 21        | 0.34%   |
| 0x806c2    | 18        | 0.29%   |
| 0x20652    | 14        | 0.23%   |
| 0x06001119 | 13        | 0.21%   |
| 0x6fd      | 12        | 0.19%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 1140      | 18.76%  |
| TigerLake        | 520       | 8.56%   |
| Unknown          | 429       | 7.06%   |
| Haswell          | 416       | 6.85%   |
| IvyBridge        | 380       | 6.25%   |
| SandyBridge      | 346       | 5.69%   |
| Skylake          | 313       | 5.15%   |
| Alderlake Hybrid | 265       | 4.36%   |
| Zen 3            | 239       | 3.93%   |
| Icelake          | 228       | 3.75%   |
| Westmere         | 190       | 3.13%   |
| Broadwell        | 189       | 3.11%   |
| Silvermont       | 166       | 2.73%   |
| Zen+             | 158       | 2.6%    |
| Goldmont plus    | 149       | 2.45%   |
| Penryn           | 148       | 2.44%   |
| CometLake        | 146       | 2.4%    |
| Zen 2            | 142       | 2.34%   |
| Excavator        | 87        | 1.43%   |
| Core             | 76        | 1.25%   |
| Goldmont         | 63        | 1.04%   |
| Puma             | 47        | 0.77%   |
| Piledriver       | 37        | 0.61%   |
| Zen              | 34        | 0.56%   |
| Bobcat           | 34        | 0.56%   |
| K10              | 27        | 0.44%   |
| Jaguar           | 20        | 0.33%   |
| K8 Hammer        | 19        | 0.31%   |
| Nehalem          | 18        | 0.3%    |
| Steamroller      | 14        | 0.23%   |
| K10 Llano        | 14        | 0.23%   |
| K8 & K10 hybrid  | 13        | 0.21%   |
| Tremont          | 8         | 0.13%   |
| Bonnell          | 2         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 4626      | 59.07%  |
| Nvidia                           | 1775      | 22.67%  |
| AMD                              | 1428      | 18.24%  |
| Zhaoxin                          | 1         | 0.01%   |
| Silicon Integrated Systems [SiS] | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 471       | 5.92%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 349       | 4.39%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 321       | 4.04%   |
| Intel UHD Graphics 620                                                                   | 263       | 3.31%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 246       | 3.09%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 226       | 2.84%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 216       | 2.72%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 204       | 2.57%   |
| Intel HD Graphics 620                                                                    | 181       | 2.28%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 176       | 2.21%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 174       | 2.19%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 170       | 2.14%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 165       | 2.07%   |
| AMD Lucienne                                                                             | 162       | 2.04%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 159       | 2%      |
| Intel HD Graphics 5500                                                                   | 157       | 1.97%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 137       | 1.72%   |
| AMD Renoir                                                                               | 134       | 1.68%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 127       | 1.6%    |
| Intel Core Processor Integrated Graphics Controller                                      | 127       | 1.6%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 125       | 1.57%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 119       | 1.5%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 99        | 1.24%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 85        | 1.07%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 84        | 1.06%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 82        | 1.03%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 76        | 0.96%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 73        | 0.92%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 70        | 0.88%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 67        | 0.84%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 59        | 0.74%   |
| Intel HD Graphics 500                                                                    | 56        | 0.7%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 55        | 0.69%   |
| AMD Rembrandt [Radeon 680M]                                                              | 53        | 0.67%   |
| AMD Barcelo                                                                              | 53        | 0.67%   |
| Intel HD Graphics 530                                                                    | 52        | 0.65%   |
| Intel HD Graphics 630                                                                    | 51        | 0.64%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 48        | 0.6%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 48        | 0.6%    |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 46        | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 3029      | 49.91%  |
| Intel + Nvidia | 1361      | 22.43%  |
| 1 x AMD        | 957       | 15.77%  |
| 1 x Nvidia     | 235       | 3.87%   |
| Intel + AMD    | 220       | 3.62%   |
| AMD + Nvidia   | 176       | 2.9%    |
| 2 x AMD        | 74        | 1.22%   |
| Other          | 11        | 0.18%   |
| 2 x Nvidia     | 3         | 0.05%   |
| 2 x Intel      | 1         | 0.02%   |
| 1 x Zhaoxin    | 1         | 0.02%   |
| 1 x SiS        | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 5030      | 82.36%  |
| Proprietary | 965       | 15.8%   |
| Unknown     | 112       | 1.83%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 5010      | 81.96%  |
| 0.01-0.5   | 361       | 5.91%   |
| 1.01-2.0   | 329       | 5.38%   |
| 0.51-1.0   | 172       | 2.81%   |
| 3.01-4.0   | 153       | 2.5%    |
| 5.01-6.0   | 45        | 0.74%   |
| 7.01-8.0   | 28        | 0.46%   |
| 2.01-3.0   | 9         | 0.15%   |
| 8.01-16.0  | 6         | 0.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 1282      | 18.01%  |
| BOE                     | 1202      | 16.89%  |
| Chimei Innolux          | 957       | 13.45%  |
| LG Display              | 890       | 12.51%  |
| Samsung Electronics     | 674       | 9.47%   |
| Dell                    | 219       | 3.08%   |
| Sharp                   | 214       | 3.01%   |
| Apple                   | 181       | 2.54%   |
| Goldstar                | 158       | 2.22%   |
| PANDA                   | 130       | 1.83%   |
| Chi Mei Optoelectronics | 118       | 1.66%   |
| Lenovo                  | 109       | 1.53%   |
| Hewlett-Packard         | 97        | 1.36%   |
| Acer                    | 71        | 1%      |
| InfoVision              | 66        | 0.93%   |
| CSO                     | 63        | 0.89%   |
| AOC                     | 61        | 0.86%   |
| Philips                 | 50        | 0.7%    |
| BenQ                    | 46        | 0.65%   |
| Iiyama                  | 43        | 0.6%    |
| Ancor Communications    | 43        | 0.6%    |
| ASUSTek Computer        | 34        | 0.48%   |
| Sony                    | 33        | 0.46%   |
| ViewSonic               | 27        | 0.38%   |
| TMX                     | 26        | 0.37%   |
| LG Philips              | 26        | 0.37%   |
| Mi                      | 17        | 0.24%   |
| CPT                     | 17        | 0.24%   |
| MSI                     | 14        | 0.2%    |
| Toshiba                 | 13        | 0.18%   |
| Panasonic               | 11        | 0.15%   |
| Vizio                   | 8         | 0.11%   |
| Sceptre Tech            | 8         | 0.11%   |
| Eizo                    | 8         | 0.11%   |
| Vestel Elektronik       | 7         | 0.1%    |
| SLD                     | 7         | 0.1%    |
| KDC                     | 7         | 0.1%    |
| HKC                     | 7         | 0.1%    |
| HannStar                | 7         | 0.1%    |
| Fujitsu Siemens         | 7         | 0.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 55        | 0.76%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 45        | 0.62%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 45        | 0.62%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 40        | 0.55%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 39        | 0.54%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 38        | 0.53%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 35        | 0.49%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 34        | 0.47%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 30        | 0.42%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 30        | 0.42%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 29        | 0.4%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 29        | 0.4%    |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 27        | 0.37%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 25        | 0.35%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 23        | 0.32%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 22        | 0.31%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 22        | 0.31%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                    | 22        | 0.31%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch           | 22        | 0.31%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 21        | 0.29%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                    | 21        | 0.29%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 20        | 0.28%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch    | 19        | 0.26%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                    | 19        | 0.26%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch         | 18        | 0.25%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch         | 18        | 0.25%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 18        | 0.25%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 18        | 0.25%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch    | 17        | 0.24%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 17        | 0.24%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                    | 17        | 0.24%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 17        | 0.24%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 17        | 0.24%   |
| LG Display LCD Monitor LGD06B3 1920x1200 336x210mm 15.6-inch             | 16        | 0.22%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 16        | 0.22%   |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch         | 16        | 0.22%   |
| BOE LCD Monitor BOE097D 1920x1080 344x194mm 15.5-inch                    | 16        | 0.22%   |
| BOE LCD Monitor BOE091D 1920x1080 309x174mm 14.0-inch                    | 16        | 0.22%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 16        | 0.22%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 16        | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 3086      | 46.48%  |
| 1366x768 (WXGA)    | 1631      | 24.57%  |
| 1600x900 (HD+)     | 337       | 5.08%   |
| 3840x2160 (4K)     | 270       | 4.07%   |
| 2560x1440 (QHD)    | 232       | 3.49%   |
| 1920x1200 (WUXGA)  | 187       | 2.82%   |
| 1280x800 (WXGA)    | 149       | 2.24%   |
| 2560x1600          | 140       | 2.11%   |
| 2880x1800          | 89        | 1.34%   |
| 1440x900 (WXGA+)   | 75        | 1.13%   |
| 3840x2400          | 55        | 0.83%   |
| 2560x1080          | 50        | 0.75%   |
| 1680x1050 (WSXGA+) | 50        | 0.75%   |
| 3440x1440          | 46        | 0.69%   |
| 2160x1440          | 35        | 0.53%   |
| 1360x768           | 17        | 0.26%   |
| 1280x1024 (SXGA)   | 17        | 0.26%   |
| 2256x1504          | 14        | 0.21%   |
| 3200x1800 (QHD+)   | 13        | 0.2%    |
| 3200x2000          | 11        | 0.17%   |
| 3840x1080          | 10        | 0.15%   |
| 3000x2000          | 10        | 0.15%   |
| 2520x1680          | 10        | 0.15%   |
| 1920x540           | 10        | 0.15%   |
| 3456x2160          | 9         | 0.14%   |
| 3072x1920          | 9         | 0.14%   |
| 2880x1620          | 9         | 0.14%   |
| 1920x1280          | 7         | 0.11%   |
| 2240x1400          | 6         | 0.09%   |
| 1680x945           | 6         | 0.09%   |
| Unknown            | 6         | 0.09%   |
| 3840x1600          | 4         | 0.06%   |
| 1280x720 (HD)      | 4         | 0.06%   |
| 1024x768 (XGA)     | 4         | 0.06%   |
| 2304x1440          | 3         | 0.05%   |
| 3840x1100          | 2         | 0.03%   |
| 2160x1350          | 2         | 0.03%   |
| 1600x1200          | 2         | 0.03%   |
| 1400x1050          | 2         | 0.03%   |
| 1024x600           | 2         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 2863      | 40.22%  |
| 13      | 1009      | 14.18%  |
| 14      | 911       | 12.8%   |
| 17      | 511       | 7.18%   |
| 27      | 270       | 3.79%   |
| 24      | 252       | 3.54%   |
| 23      | 196       | 2.75%   |
| 16      | 175       | 2.46%   |
| 21      | 154       | 2.16%   |
| 12      | 128       | 1.8%    |
| 11      | 112       | 1.57%   |
| 34      | 84        | 1.18%   |
| 31      | 66        | 0.93%   |
| 18      | 48        | 0.67%   |
| Unknown | 44        | 0.62%   |
| 22      | 30        | 0.42%   |
| 19      | 26        | 0.37%   |
| 40      | 23        | 0.32%   |
| 20      | 23        | 0.32%   |
| 54      | 20        | 0.28%   |
| 84      | 19        | 0.27%   |
| 72      | 18        | 0.25%   |
| 26      | 18        | 0.25%   |
| 10      | 17        | 0.24%   |
| 32      | 13        | 0.18%   |
| 28      | 13        | 0.18%   |
| 25      | 8         | 0.11%   |
| 43      | 6         | 0.08%   |
| 37      | 6         | 0.08%   |
| 29      | 6         | 0.08%   |
| 65      | 5         | 0.07%   |
| 49      | 5         | 0.07%   |
| 48      | 5         | 0.07%   |
| 46      | 5         | 0.07%   |
| 52      | 4         | 0.06%   |
| 38      | 4         | 0.06%   |
| 35      | 4         | 0.06%   |
| 42      | 3         | 0.04%   |
| 74      | 2         | 0.03%   |
| 58      | 2         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 4338      | 61.38%  |
| 201-300     | 772       | 10.92%  |
| 501-600     | 672       | 9.51%   |
| 351-400     | 616       | 8.72%   |
| 401-500     | 273       | 3.86%   |
| 601-700     | 114       | 1.61%   |
| 701-800     | 98        | 1.39%   |
| 1001-1500   | 50        | 0.71%   |
| Unknown     | 44        | 0.62%   |
| 1501-2000   | 40        | 0.57%   |
| 801-900     | 38        | 0.54%   |
| 901-1000    | 9         | 0.13%   |
| 101-200     | 3         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 5141      | 82.81%  |
| 16/10   | 795       | 12.81%  |
| 21/9    | 104       | 1.68%   |
| 3/2     | 93        | 1.5%    |
| Unknown | 22        | 0.35%   |
| 4/3     | 17        | 0.27%   |
| 5/4     | 15        | 0.24%   |
| 32/9    | 9         | 0.14%   |
| 6/5     | 3         | 0.05%   |
| 3.40    | 2         | 0.03%   |
| 0.62    | 2         | 0.03%   |
| 3.73    | 1         | 0.02%   |
| 3.33    | 1         | 0.02%   |
| 3.20    | 1         | 0.02%   |
| 2.12    | 1         | 0.02%   |
| 2.00    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 2867      | 40.36%  |
| 81-90          | 1535      | 21.61%  |
| 201-250        | 509       | 7.17%   |
| 121-130        | 450       | 6.34%   |
| 71-80          | 376       | 5.29%   |
| 301-350        | 288       | 4.05%   |
| 351-500        | 176       | 2.48%   |
| 111-120        | 154       | 2.17%   |
| 61-70          | 120       | 1.69%   |
| 51-60          | 114       | 1.6%    |
| 251-300        | 92        | 1.3%    |
| 151-200        | 86        | 1.21%   |
| More than 1000 | 73        | 1.03%   |
| 131-140        | 58        | 0.82%   |
| 501-1000       | 57        | 0.8%    |
| 141-150        | 52        | 0.73%   |
| Unknown        | 44        | 0.62%   |
| 91-100         | 32        | 0.45%   |
| 41-50          | 18        | 0.25%   |
| 1-40           | 2         | 0.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 3003      | 43.09%  |
| 101-120       | 1887      | 27.08%  |
| 51-100        | 1047      | 15.02%  |
| 161-240       | 665       | 9.54%   |
| More than 240 | 259       | 3.72%   |
| 1-50          | 64        | 0.92%   |
| Unknown       | 44        | 0.63%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 4719      | 76.77%  |
| 2     | 1110      | 18.06%  |
| 0     | 158       | 2.57%   |
| 3     | 147       | 2.39%   |
| 4     | 10        | 0.16%   |
| 5     | 2         | 0.03%   |
| 6     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 3381      | 35.87%  |
| Realtek Semiconductor             | 3216      | 34.11%  |
| Qualcomm Atheros                  | 1084      | 11.5%   |
| Broadcom                          | 531       | 5.63%   |
| MediaTek                          | 258       | 2.74%   |
| Broadcom Limited                  | 124       | 1.32%   |
| ASIX Electronics                  | 81        | 0.86%   |
| Ralink                            | 66        | 0.7%    |
| TP-Link                           | 62        | 0.66%   |
| Marvell Technology Group          | 58        | 0.62%   |
| DisplayLink                       | 51        | 0.54%   |
| Samsung Electronics               | 41        | 0.43%   |
| Dell                              | 38        | 0.4%    |
| Qualcomm                          | 34        | 0.36%   |
| Lenovo                            | 31        | 0.33%   |
| Sierra Wireless                   | 30        | 0.32%   |
| Ralink Technology                 | 30        | 0.32%   |
| Xiaomi                            | 29        | 0.31%   |
| Nvidia                            | 28        | 0.3%    |
| Ericsson Business Mobile Networks | 22        | 0.23%   |
| NetGear                           | 21        | 0.22%   |
| Hewlett-Packard                   | 20        | 0.21%   |
| Apple                             | 17        | 0.18%   |
| JMicron Technology                | 16        | 0.17%   |
| Huawei Technologies               | 15        | 0.16%   |
| OPPO Electronics                  | 13        | 0.14%   |
| Qualcomm Atheros Communications   | 12        | 0.13%   |
| ICS Advent                        | 12        | 0.13%   |
| Google                            | 12        | 0.13%   |
| Motorola PCS                      | 9         | 0.1%    |
| Fibocom                           | 7         | 0.07%   |
| D-Link                            | 7         | 0.07%   |
| Edimax Technology                 | 6         | 0.06%   |
| U-Blox                            | 5         | 0.05%   |
| Arduino SA                        | 5         | 0.05%   |
| Toshiba                           | 4         | 0.04%   |
| Dresden Elektronik                | 3         | 0.03%   |
| D-Link System                     | 3         | 0.03%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.02%   |
| TRENDnet                          | 2         | 0.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1830      | 16.28%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 445       | 3.96%   |
| Intel Wi-Fi 6 AX201                                               | 403       | 3.58%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 305       | 2.71%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 286       | 2.54%   |
| Intel Wireless 8265 / 8275                                        | 272       | 2.42%   |
| Intel Wi-Fi 6 AX200                                               | 263       | 2.34%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 209       | 1.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 209       | 1.86%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 207       | 1.84%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 200       | 1.78%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 174       | 1.55%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 172       | 1.53%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 167       | 1.49%   |
| Intel Wireless 7265                                               | 162       | 1.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 154       | 1.37%   |
| Intel Wireless 7260                                               | 151       | 1.34%   |
| Intel Wireless 8260                                               | 145       | 1.29%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 140       | 1.25%   |
| Intel Ethernet Connection (4) I219-LM                             | 118       | 1.05%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 118       | 1.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 114       | 1.01%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 108       | 0.96%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 97        | 0.86%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 95        | 0.84%   |
| Intel Wireless 3165                                               | 91        | 0.81%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 88        | 0.78%   |
| Intel Ethernet Connection I219-LM                                 | 87        | 0.77%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 86        | 0.76%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 79        | 0.7%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 77        | 0.68%   |
| ASIX AX88179 Gigabit Ethernet                                     | 77        | 0.68%   |
| Broadcom BCM43142 802.11b/g/n                                     | 73        | 0.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 71        | 0.63%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 66        | 0.59%   |
| Realtek RTL8125 2.5GbE Controller                                 | 64        | 0.57%   |
| Intel 82577LM Gigabit Network Connection                          | 63        | 0.56%   |
| Intel Ethernet Connection I218-LM                                 | 61        | 0.54%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 60        | 0.53%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 59        | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 3234      | 51.8%   |
| Realtek Semiconductor             | 1013      | 16.23%  |
| Qualcomm Atheros                  | 928       | 14.86%  |
| Broadcom                          | 426       | 6.82%   |
| MediaTek                          | 248       | 3.97%   |
| Broadcom Limited                  | 85        | 1.36%   |
| Ralink                            | 66        | 1.06%   |
| TP-Link                           | 50        | 0.8%    |
| Sierra Wireless                   | 30        | 0.48%   |
| Ralink Technology                 | 30        | 0.48%   |
| Qualcomm                          | 27        | 0.43%   |
| Dell                              | 25        | 0.4%    |
| NetGear                           | 20        | 0.32%   |
| Qualcomm Atheros Communications   | 12        | 0.19%   |
| Hewlett-Packard                   | 7         | 0.11%   |
| Fibocom                           | 7         | 0.11%   |
| Ericsson Business Mobile Networks | 6         | 0.1%    |
| Edimax Technology                 | 6         | 0.1%    |
| D-Link                            | 6         | 0.1%    |
| D-Link System                     | 3         | 0.05%   |
| TRENDnet                          | 2         | 0.03%   |
| Linksys                           | 2         | 0.03%   |
| U.S. Robotics                     | 1         | 0.02%   |
| Quectel Wireless Solutions        | 1         | 0.02%   |
| Qualcomm Technologies             | 1         | 0.02%   |
| Microsoft                         | 1         | 0.02%   |
| IMC Networks                      | 1         | 0.02%   |
| I-O Data Device                   | 1         | 0.02%   |
| Guillemot                         | 1         | 0.02%   |
| Fujitsu Siemens Computers         | 1         | 0.02%   |
| Belkin Components                 | 1         | 0.02%   |
| AboCom Systems                    | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                            | 403       | 6.41%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 286       | 4.55%   |
| Intel Wireless 8265 / 8275                                     | 272       | 4.32%   |
| Intel Wi-Fi 6 AX200                                            | 263       | 4.18%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 209       | 3.32%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 209       | 3.32%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 207       | 3.29%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 200       | 3.18%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 172       | 2.73%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 167       | 2.66%   |
| Intel Wireless 7265                                            | 162       | 2.58%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 154       | 2.45%   |
| Intel Wireless 7260                                            | 151       | 2.4%    |
| Intel Wireless 8260                                            | 145       | 2.31%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 140       | 2.23%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 118       | 1.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 114       | 1.81%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 108       | 1.72%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 97        | 1.54%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 95        | 1.51%   |
| Intel Wireless 3165                                            | 91        | 1.45%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 88        | 1.4%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 86        | 1.37%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 79        | 1.26%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 77        | 1.22%   |
| Broadcom BCM43142 802.11b/g/n                                  | 73        | 1.16%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 71        | 1.13%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 66        | 1.05%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 60        | 0.95%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 59        | 0.94%   |
| Intel Wireless 3160                                            | 56        | 0.89%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 51        | 0.81%   |
| Intel Centrino Wireless-N 2230                                 | 50        | 0.79%   |
| Intel Wireless-AC 9260                                         | 49        | 0.78%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 48        | 0.76%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 48        | 0.76%   |
| Intel Centrino Advanced-N 6200                                 | 48        | 0.76%   |
| Intel Centrino Ultimate-N 6300                                 | 43        | 0.68%   |
| Realtek 802.11n WLAN Adapter                                   | 42        | 0.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 40        | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2736      | 56.98%  |
| Intel                                  | 1122      | 23.37%  |
| Qualcomm Atheros                       | 261       | 5.44%   |
| Broadcom                               | 188       | 3.92%   |
| ASIX Electronics                       | 81        | 1.69%   |
| Marvell Technology Group               | 58        | 1.21%   |
| DisplayLink                            | 51        | 1.06%   |
| Broadcom Limited                       | 42        | 0.87%   |
| Samsung Electronics                    | 41        | 0.85%   |
| Lenovo                                 | 31        | 0.65%   |
| Xiaomi                                 | 29        | 0.6%    |
| Nvidia                                 | 28        | 0.58%   |
| Apple                                  | 17        | 0.35%   |
| JMicron Technology                     | 16        | 0.33%   |
| OPPO Electronics                       | 13        | 0.27%   |
| TP-Link                                | 12        | 0.25%   |
| ICS Advent                             | 12        | 0.25%   |
| Google                                 | 12        | 0.25%   |
| MediaTek                               | 10        | 0.21%   |
| Huawei Technologies                    | 8         | 0.17%   |
| Qualcomm                               | 7         | 0.15%   |
| Motorola PCS                           | 6         | 0.12%   |
| Hewlett-Packard                        | 4         | 0.08%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.04%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.04%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.04%   |
| HMD Global                             | 2         | 0.04%   |
| Spreadtrum Communications              | 1         | 0.02%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.02%   |
| Research In Motion                     | 1         | 0.02%   |
| NetGear                                | 1         | 0.02%   |
| Netchip Technology                     | 1         | 0.02%   |
| Microchip Technology                   | 1         | 0.02%   |
| LG Electronics                         | 1         | 0.02%   |
| Davicom Semiconductor                  | 1         | 0.02%   |
| D-Link                                 | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1830      | 37.6%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 445       | 9.14%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 305       | 6.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 174       | 3.58%   |
| Intel Ethernet Connection (4) I219-LM                             | 118       | 2.42%   |
| Intel Ethernet Connection I219-LM                                 | 87        | 1.79%   |
| ASIX AX88179 Gigabit Ethernet                                     | 77        | 1.58%   |
| Realtek RTL8125 2.5GbE Controller                                 | 64        | 1.31%   |
| Intel 82577LM Gigabit Network Connection                          | 63        | 1.29%   |
| Intel Ethernet Connection I218-LM                                 | 61        | 1.25%   |
| Intel Ethernet Connection I217-LM                                 | 53        | 1.09%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 49        | 1.01%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 49        | 1.01%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 48        | 0.99%   |
| Intel Ethernet Connection (3) I218-LM                             | 48        | 0.99%   |
| Intel Ethernet Connection (4) I219-V                              | 46        | 0.95%   |
| Realtek Killer E3000 2.5GbE Controller                            | 36        | 0.74%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 34        | 0.7%    |
| Intel Ethernet Connection (7) I219-LM                             | 34        | 0.7%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 34        | 0.7%    |
| Intel Ethernet Connection (6) I219-V                              | 33        | 0.68%   |
| Intel Ethernet Connection (13) I219-LM                            | 32        | 0.66%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 31        | 0.64%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 30        | 0.62%   |
| Intel Ethernet Connection (16) I219-V                             | 28        | 0.58%   |
| Intel Ethernet Connection (6) I219-LM                             | 27        | 0.55%   |
| Intel Ethernet Connection (2) I219-LM                             | 27        | 0.55%   |
| Intel Ethernet Connection (13) I219-V                             | 27        | 0.55%   |
| Intel Ethernet Connection (16) I219-LM                            | 25        | 0.51%   |
| Intel 82579V Gigabit Network Connection                           | 25        | 0.51%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 24        | 0.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 23        | 0.47%   |
| Intel 82567LM Gigabit Network Connection                          | 22        | 0.45%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 21        | 0.43%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 21        | 0.43%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 21        | 0.43%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 20        | 0.41%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 20        | 0.41%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 20        | 0.41%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 20        | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 5973      | 56.3%   |
| Ethernet | 4553      | 42.91%  |
| Modem    | 67        | 0.63%   |
| Unknown  | 17        | 0.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 5065      | 78.82%  |
| Ethernet | 1361      | 21.18%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 4021      | 66.28%  |
| 1     | 1906      | 31.42%  |
| 0     | 102       | 1.68%   |
| 3     | 38        | 0.63%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 4266      | 69.54%  |
| Yes  | 1869      | 30.46%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2744      | 54.09%  |
| Realtek Semiconductor           | 568       | 11.2%   |
| Qualcomm Atheros Communications | 375       | 7.39%   |
| IMC Networks                    | 268       | 5.28%   |
| Foxconn / Hon Hai               | 214       | 4.22%   |
| Lite-On Technology              | 206       | 4.06%   |
| Broadcom                        | 188       | 3.71%   |
| Apple                           | 128       | 2.52%   |
| Dell                            | 69        | 1.36%   |
| Realtek                         | 62        | 1.22%   |
| Hewlett-Packard                 | 48        | 0.95%   |
| Cambridge Silicon Radio         | 44        | 0.87%   |
| Ralink                          | 36        | 0.71%   |
| Toshiba                         | 32        | 0.63%   |
| Alps Electric                   | 14        | 0.28%   |
| ASUSTek Computer                | 13        | 0.26%   |
| MediaTek                        | 12        | 0.24%   |
| Foxconn International           | 11        | 0.22%   |
| Ralink Technology               | 10        | 0.2%    |
| USI                             | 7         | 0.14%   |
| Opticis                         | 5         | 0.1%    |
| Askey Computer                  | 5         | 0.1%    |
| Integrated System Solution      | 2         | 0.04%   |
| TP-Link                         | 1         | 0.02%   |
| Taiyo Yuden                     | 1         | 0.02%   |
| Smart Modular Technologies      | 1         | 0.02%   |
| Roper                           | 1         | 0.02%   |
| Qcom                            | 1         | 0.02%   |
| Mobile Action Technology        | 1         | 0.02%   |
| Micro Star International        | 1         | 0.02%   |
| Fujitsu Siemens Computers       | 1         | 0.02%   |
| Fujitsu                         | 1         | 0.02%   |
| Edimax Technology               | 1         | 0.02%   |
| Dynex                           | 1         | 0.02%   |
| Chicony Electronics             | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 868       | 17.1%   |
| Intel AX201 Bluetooth                               | 743       | 14.63%  |
| Realtek Bluetooth Radio                             | 434       | 8.55%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 372       | 7.33%   |
| Intel Bluetooth Device                              | 277       | 5.46%   |
| Intel AX200 Bluetooth                               | 259       | 5.1%    |
| Qualcomm Atheros  Bluetooth Device                  | 199       | 3.92%   |
| Realtek  Bluetooth 4.2 Adapter                      | 109       | 2.15%   |
| IMC Networks Wireless_Device                        | 109       | 2.15%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 85        | 1.67%   |
| Apple Bluetooth Host Controller                     | 83        | 1.63%   |
| IMC Networks Bluetooth Radio                        | 77        | 1.52%   |
| Intel AX210 Bluetooth                               | 75        | 1.48%   |
| Foxconn / Hon Hai Bluetooth Device                  | 66        | 1.3%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 64        | 1.26%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 59        | 1.16%   |
| Realtek 802.11ac WLAN Adapter                       | 55        | 1.08%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 46        | 0.91%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 45        | 0.89%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 44        | 0.87%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 44        | 0.87%   |
| Lite-On Atheros AR3012 Bluetooth                    | 41        | 0.81%   |
| IMC Networks Bluetooth Device                       | 41        | 0.81%   |
| Lite-On Bluetooth Device                            | 39        | 0.77%   |
| Ralink RT3290 Bluetooth                             | 36        | 0.71%   |
| Lite-On Wireless_Device                             | 36        | 0.71%   |
| Apple Bluetooth USB Host Controller                 | 34        | 0.67%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 31        | 0.61%   |
| HP Broadcom 2070 Bluetooth Combo                    | 31        | 0.61%   |
| Foxconn / Hon Hai Wireless_Device                   | 30        | 0.59%   |
| Broadcom BCM2045B (BDC-2.1)                         | 28        | 0.55%   |
| Dell DW375 Bluetooth Module                         | 26        | 0.51%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 25        | 0.49%   |
| Broadcom HP Portable SoftSailing                    | 24        | 0.47%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 23        | 0.45%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 22        | 0.43%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 18        | 0.35%   |
| Dell BCM20702A0 Bluetooth Module                    | 16        | 0.32%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 16        | 0.32%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 15        | 0.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 4862      | 64.07%  |
| AMD                                          | 1245      | 16.41%  |
| Nvidia                                       | 953       | 12.56%  |
| Logitech                                     | 41        | 0.54%   |
| Realtek Semiconductor                        | 40        | 0.53%   |
| C-Media Electronics                          | 40        | 0.53%   |
| Apple                                        | 39        | 0.51%   |
| Lenovo                                       | 38        | 0.5%    |
| Hewlett-Packard                              | 37        | 0.49%   |
| GN Netcom                                    | 35        | 0.46%   |
| Plantronics                                  | 30        | 0.4%    |
| JMTek                                        | 18        | 0.24%   |
| Generalplus Technology                       | 15        | 0.2%    |
| Corsair                                      | 14        | 0.18%   |
| Texas Instruments                            | 12        | 0.16%   |
| Razer USA                                    | 12        | 0.16%   |
| Kingston Technology                          | 12        | 0.16%   |
| Sennheiser Communications                    | 9         | 0.12%   |
| Creative Technology                          | 9         | 0.12%   |
| SteelSeries ApS                              | 7         | 0.09%   |
| ASUSTek Computer                             | 7         | 0.09%   |
| Sony                                         | 6         | 0.08%   |
| Focusrite-Novation                           | 6         | 0.08%   |
| DCMT Technology                              | 6         | 0.08%   |
| Jieli Technology                             | 5         | 0.07%   |
| RODE Microphones                             | 4         | 0.05%   |
| DSEA A/S                                     | 4         | 0.05%   |
| Conexant Systems                             | 4         | 0.05%   |
| BEHRINGER International                      | 4         | 0.05%   |
| Turtle Beach                                 | 3         | 0.04%   |
| Samsung Electronics                          | 3         | 0.04%   |
| OPPO Electronics                             | 3         | 0.04%   |
| JBL                                          | 3         | 0.04%   |
| Google                                       | 3         | 0.04%   |
| Dell                                         | 3         | 0.04%   |
| CMX Systems                                  | 3         | 0.04%   |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 0.03%   |
| XMOS                                         | 2         | 0.03%   |
| Syntek                                       | 2         | 0.03%   |
| Silicon Integrated Systems [SiS]             | 2         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 752       | 8.25%   |
| Intel Sunrise Point-LP HD Audio                                            | 721       | 7.91%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 520       | 5.7%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 473       | 5.19%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 440       | 4.83%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 344       | 3.77%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 285       | 3.13%   |
| Intel Haswell-ULT HD Audio Controller                                      | 231       | 2.53%   |
| Intel 8 Series HD Audio Controller                                         | 231       | 2.53%   |
| Intel Comet Lake PCH-LP cAVS                                               | 214       | 2.35%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 207       | 2.27%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 192       | 2.11%   |
| Intel Cannon Lake PCH cAVS                                                 | 192       | 2.11%   |
| Intel Broadwell-U Audio Controller                                         | 189       | 2.07%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 188       | 2.06%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 182       | 2%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 178       | 1.95%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 150       | 1.65%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 149       | 1.63%   |
| AMD FCH Azalia Controller                                                  | 147       | 1.61%   |
| Intel Comet Lake PCH cAVS                                                  | 139       | 1.52%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 134       | 1.47%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 130       | 1.43%   |
| Nvidia Audio device                                                        | 128       | 1.4%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 125       | 1.37%   |
| Nvidia GA106 High Definition Audio Controller                              | 117       | 1.28%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 105       | 1.15%   |
| Nvidia GA104 High Definition Audio Controller                              | 87        | 0.95%   |
| AMD Kabini HDMI/DP Audio                                                   | 87        | 0.95%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 85        | 0.93%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 71        | 0.78%   |
| Nvidia GF108 High Definition Audio Controller                              | 68        | 0.75%   |
| Nvidia TU106 High Definition Audio Controller                              | 67        | 0.73%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 67        | 0.73%   |
| AMD High Definition Audio Controller                                       | 67        | 0.73%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 64        | 0.7%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 62        | 0.68%   |
| Intel CM238 HD Audio Controller                                            | 61        | 0.67%   |
| Nvidia GP107GL High Definition Audio Controller                            | 59        | 0.65%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 59        | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 1245      | 31.2%   |
| SK hynix                                | 927       | 23.23%  |
| Micron Technology                       | 572       | 14.33%  |
| Kingston                                | 298       | 7.47%   |
| Crucial                                 | 193       | 4.84%   |
| Unknown                                 | 129       | 3.23%   |
| A-DATA Technology                       | 96        | 2.41%   |
| Ramaxel Technology                      | 78        | 1.95%   |
| Unknown (ABCD)                          | 76        | 1.9%    |
| Nanya Technology                        | 45        | 1.13%   |
| Unknown                                 | 43        | 1.08%   |
| Elpida                                  | 35        | 0.88%   |
| Corsair                                 | 35        | 0.88%   |
| Smart                                   | 28        | 0.7%    |
| G.Skill                                 | 23        | 0.58%   |
| Team                                    | 18        | 0.45%   |
| ChangXin Memory                         | 12        | 0.3%    |
| Smart Brazil                            | 10        | 0.25%   |
| Patriot                                 | 10        | 0.25%   |
| GOODRAM                                 | 10        | 0.25%   |
| Transcend                               | 8         | 0.2%    |
| Goldkey                                 | 6         | 0.15%   |
| Neo Forza                               | 5         | 0.13%   |
| Wilk                                    | 4         | 0.1%    |
| PNY                                     | 4         | 0.1%    |
| ASint Technology                        | 4         | 0.1%    |
| Toshiba                                 | 3         | 0.08%   |
| Teikon                                  | 3         | 0.08%   |
| SHARETRONIC                             | 3         | 0.08%   |
| fef5                                    | 3         | 0.08%   |
| Avant                                   | 3         | 0.08%   |
| Apacer                                  | 3         | 0.08%   |
| AMD                                     | 3         | 0.08%   |
| Unknown (8AD6)                          | 2         | 0.05%   |
| Unknown (768A)                          | 2         | 0.05%   |
| Timetec                                 | 2         | 0.05%   |
| Smart Modular                           | 2         | 0.05%   |
| Silicon Power Computer & Communications | 2         | 0.05%   |
| Silicon Power                           | 2         | 0.05%   |
| Qimonda                                 | 2         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 89        | 2.13%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 72        | 1.72%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 60        | 1.44%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 53        | 1.27%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 43        | 1.03%   |
| Unknown                                                          | 43        | 1.03%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 41        | 0.98%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 40        | 0.96%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 40        | 0.96%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 39        | 0.93%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 38        | 0.91%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 35        | 0.84%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 33        | 0.79%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 31        | 0.74%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 31        | 0.74%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 30        | 0.72%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 29        | 0.69%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 29        | 0.69%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 28        | 0.67%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 28        | 0.67%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 27        | 0.65%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 26        | 0.62%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 24        | 0.57%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 24        | 0.57%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 23        | 0.55%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 23        | 0.55%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 23        | 0.55%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 22        | 0.53%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                     | 22        | 0.53%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 22        | 0.53%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 21        | 0.5%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 21        | 0.5%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 21        | 0.5%    |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 20        | 0.48%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 20        | 0.48%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 20        | 0.48%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 20        | 0.48%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 20        | 0.48%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 20        | 0.48%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 20        | 0.48%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 1911      | 56.21%  |
| DDR3    | 759       | 22.32%  |
| LPDDR4  | 286       | 8.41%   |
| DDR5    | 141       | 4.15%   |
| LPDDR3  | 132       | 3.88%   |
| LPDDR5  | 80        | 2.35%   |
| DDR2    | 48        | 1.41%   |
| SDRAM   | 27        | 0.79%   |
| Unknown | 11        | 0.32%   |
| DDR     | 4         | 0.12%   |
| DRAM    | 1         | 0.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| SODIMM          | 2839      | 82.48%  |
| Row Of Chips    | 543       | 15.78%  |
| Unknown         | 25        | 0.73%   |
| Chip            | 19        | 0.55%   |
| DIMM            | 14        | 0.41%   |
| Proprietary Car | 2         | 0.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size   | Notebooks | Percent |
|--------|-----------|---------|
| 8192   | 1633      | 44.24%  |
| 4096   | 917       | 24.84%  |
| 16384  | 713       | 19.32%  |
| 2048   | 229       | 6.2%    |
| 32768  | 139       | 3.77%   |
| 1024   | 53        | 1.44%   |
| 6144   | 3         | 0.08%   |
| 131072 | 1         | 0.03%   |
| 65536  | 1         | 0.03%   |
| 12288  | 1         | 0.03%   |
| 1536   | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 1077      | 29.79%  |
| 2667    | 707       | 19.56%  |
| 1600    | 566       | 15.66%  |
| 2400    | 262       | 7.25%   |
| 2133    | 183       | 5.06%   |
| 4800    | 139       | 3.85%   |
| 1334    | 113       | 3.13%   |
| 4267    | 112       | 3.1%    |
| 6400    | 83        | 2.3%    |
| 1333    | 73        | 2.02%   |
| 3266    | 41        | 1.13%   |
| 1867    | 35        | 0.97%   |
| 4266    | 29        | 0.8%    |
| 667     | 28        | 0.77%   |
| Unknown | 27        | 0.75%   |
| 1067    | 23        | 0.64%   |
| 3733    | 22        | 0.61%   |
| 4199    | 20        | 0.55%   |
| 1066    | 13        | 0.36%   |
| 8400    | 12        | 0.33%   |
| 800     | 10        | 0.28%   |
| 2048    | 6         | 0.17%   |
| 5600    | 5         | 0.14%   |
| 2933    | 5         | 0.14%   |
| 1866    | 4         | 0.11%   |
| 975     | 3         | 0.08%   |
| 533     | 3         | 0.08%   |
| 1777    | 2         | 0.06%   |
| 333     | 2         | 0.06%   |
| 5500    | 1         | 0.03%   |
| 5200    | 1         | 0.03%   |
| 3000    | 1         | 0.03%   |
| 2800    | 1         | 0.03%   |
| 2666    | 1         | 0.03%   |
| 1800    | 1         | 0.03%   |
| 1639    | 1         | 0.03%   |
| 1330    | 1         | 0.03%   |
| 1200    | 1         | 0.03%   |
| 933     | 1         | 0.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 24        | 38.71%  |
| Canon               | 12        | 19.35%  |
| Brother Industries  | 8         | 12.9%   |
| Seiko Epson         | 6         | 9.68%   |
| Samsung Electronics | 4         | 6.45%   |
| STMicroelectronics  | 2         | 3.23%   |
| Xiaomi              | 1         | 1.61%   |
| Xerox               | 1         | 1.61%   |
| QinHeng Electronics | 1         | 1.61%   |
| Kyocera             | 1         | 1.61%   |
| Dell                | 1         | 1.61%   |
| Unknown             | 1         | 1.61%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP DeskJet 2300 series                                    | 4         | 6.35%   |
| HP DeskJet 2700 series                                    | 3         | 4.76%   |
| HP LaserJet 1020                                          | 2         | 3.17%   |
| Brother DCP-1510                                          | 2         | 3.17%   |
| Xiaomi MiMouse 2                                          | 1         | 1.59%   |
| Xerox Phaser 3260                                         | 1         | 1.59%   |
| STMicroelectronics USB Printer P                          | 1         | 1.59%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 1.59%   |
| Seiko Epson XP-4100 Series                                | 1         | 1.59%   |
| Seiko Epson Stylus NX230/SX235W Series                    | 1         | 1.59%   |
| Seiko Epson L360 Series                                   | 1         | 1.59%   |
| Seiko Epson L3110 Series                                  | 1         | 1.59%   |
| Seiko Epson FX-2190IIN                                    | 1         | 1.59%   |
| Seiko Epson Epson Stylus Photo 1500                       | 1         | 1.59%   |
| Samsung ML-216x Series Laser Printer                      | 1         | 1.59%   |
| Samsung ML-1610 Mono Laser Printer                        | 1         | 1.59%   |
| Samsung M2020 Series                                      | 1         | 1.59%   |
| Samsung C43x Series                                       | 1         | 1.59%   |
| QinHeng CH340S                                            | 1         | 1.59%   |
| Kyocera FS-1116MFP                                        | 1         | 1.59%   |
| HP OfficeJet 5600 (USBHUB)                                | 1         | 1.59%   |
| HP Officejet 4630 series                                  | 1         | 1.59%   |
| HP Officejet 4500 G510n-z                                 | 1         | 1.59%   |
| HP LaserJet P1102                                         | 1         | 1.59%   |
| HP LaserJet M14-M17                                       | 1         | 1.59%   |
| HP LaserJet 4250                                          | 1         | 1.59%   |
| HP LaserJet 400 M401a                                     | 1         | 1.59%   |
| HP LaserJet 1300                                          | 1         | 1.59%   |
| HP LaserJet 1150                                          | 1         | 1.59%   |
| HP LaserJet 1018                                          | 1         | 1.59%   |
| HP Laser 107w                                             | 1         | 1.59%   |
| HP ENVY 6000 series                                       | 1         | 1.59%   |
| HP DeskJet 2600 series                                    | 1         | 1.59%   |
| HP Deskjet 2540 series                                    | 1         | 1.59%   |
| HP Color LaserJet CP1215                                  | 1         | 1.59%   |
| HP color LaserJet 5550                                    | 1         | 1.59%   |
| Dell B1160 Mono Laser Printer                             | 1         | 1.59%   |
| Canon TS6300 series                                       | 1         | 1.59%   |
| Canon SELPHY CP400                                        | 1         | 1.59%   |
| Canon PIXMA MX330                                         | 1         | 1.59%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Canon                       | 4         | 40%     |
| Seiko Epson                 | 2         | 20%     |
| Mustek Systems              | 1         | 10%     |
| KYE Systems (Mouse Systems) | 1         | 10%     |
| Hewlett-Packard             | 1         | 10%     |
| AGFA-Gevaert NV             | 1         | 10%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO] | 1         | 10%     |
| Seiko Epson ES-D200 [GT-S50]                      | 1         | 10%     |
| Mustek Systems BearPaw 2448 CU Pro                | 1         | 10%     |
| KYE Systems (Mouse Systems) ColorPage-SF600       | 1         | 10%     |
| HP OfficeJet 6110                                 | 1         | 10%     |
| Canon CanoScan LIDE 25                            | 1         | 10%     |
| Canon CanoScan LiDE 110                           | 1         | 10%     |
| Canon CanoScan LiDE 100                           | 1         | 10%     |
| Canon CanoScan 4200F                              | 1         | 10%     |
| AGFA-Gevaert NV SnapScan 1212U (?)                | 1         | 10%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1169      | 20.99%  |
| IMC Networks                           | 632       | 11.35%  |
| Microdia                               | 559       | 10.04%  |
| Realtek Semiconductor                  | 435       | 7.81%   |
| Quanta                                 | 382       | 6.86%   |
| Sunplus Innovation Technology          | 365       | 6.55%   |
| Bison Electronics                      | 348       | 6.25%   |
| Cheng Uei Precision Industry (Foxlink) | 234       | 4.2%    |
| Luxvisions Innotech Limited            | 171       | 3.07%   |
| Suyin                                  | 151       | 2.71%   |
| Syntek                                 | 147       | 2.64%   |
| Apple                                  | 129       | 2.32%   |
| Lite-On Technology                     | 126       | 2.26%   |
| Logitech                               | 78        | 1.4%    |
| Acer                                   | 78        | 1.4%    |
| Silicon Motion                         | 64        | 1.15%   |
| Alcor Micro                            | 59        | 1.06%   |
| Sonix Technology                       | 56        | 1.01%   |
| Samsung Electronics                    | 48        | 0.86%   |
| Ricoh                                  | 41        | 0.74%   |
| SunplusIT                              | 37        | 0.66%   |
| icSpring                               | 23        | 0.41%   |
| Lenovo                                 | 22        | 0.39%   |
| Primax Electronics                     | 21        | 0.38%   |
| Importek                               | 21        | 0.38%   |
| Y Media                                | 16        | 0.29%   |
| ALi                                    | 16        | 0.29%   |
| Z-Star Microelectronics                | 13        | 0.23%   |
| Sunplus Technology                     | 9         | 0.16%   |
| Microsoft                              | 8         | 0.14%   |
| OmniVision Technologies                | 7         | 0.13%   |
| Intel                                  | 7         | 0.13%   |
| DigiTech                               | 7         | 0.13%   |
| Unknown                                | 5         | 0.09%   |
| Shenzhen Kingcome Optoelectronic       | 4         | 0.07%   |
| WaveRider Communications               | 3         | 0.05%   |
| USB Camera CS                          | 3         | 0.05%   |
| Unknown (3730304231385031345945)       | 3         | 0.05%   |
| Unknown                                | 3         | 0.05%   |
| ShineTech                              | 3         | 0.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                       | 309       | 5.52%   |
| Chicony Integrated Camera                           | 260       | 4.65%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 185       | 3.31%   |
| IMC Networks Integrated Camera                      | 164       | 2.93%   |
| Realtek Integrated_Webcam_HD                        | 163       | 2.91%   |
| Bison Integrated Camera                             | 119       | 2.13%   |
| Sunplus Integrated_Webcam_HD                        | 107       | 1.91%   |
| Chicony HD WebCam                                   | 98        | 1.75%   |
| Syntek Integrated Camera                            | 97        | 1.73%   |
| Chicony HP HD Camera                                | 74        | 1.32%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 66        | 1.18%   |
| Sunplus HD WebCam                                   | 59        | 1.05%   |
| Quanta HD User Facing                               | 59        | 1.05%   |
| Quanta HP HD Camera                                 | 56        | 1%      |
| IMC Networks HD Camera                              | 52        | 0.93%   |
| Samsung Galaxy series, misc. (MTP mode)             | 48        | 0.86%   |
| Quanta HP TrueVision HD Camera                      | 47        | 0.84%   |
| Bison HD Webcam                                     | 46        | 0.82%   |
| Luxvisions Innotech Limited Integrated Camera       | 44        | 0.79%   |
| Lite-On Integrated Camera                           | 43        | 0.77%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 42        | 0.75%   |
| Chicony USB2.0 Camera                               | 42        | 0.75%   |
| Chicony TOSHIBA Web Camera - HD                     | 41        | 0.73%   |
| Chicony HP TrueVision HD Camera                     | 41        | 0.73%   |
| Chicony HD User Facing                              | 39        | 0.7%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 37        | 0.66%   |
| Quanta HP Wide Vision HD Camera                     | 35        | 0.63%   |
| Microdia Integrated Webcam                          | 35        | 0.63%   |
| Chicony HP Wide Vision HD Camera                    | 35        | 0.63%   |
| Luxvisions Innotech Limited HP HD Camera            | 34        | 0.61%   |
| Chicony HP Truevision HD                            | 34        | 0.61%   |
| Suyin HP Truevision HD                              | 33        | 0.59%   |
| Sonix USB2.0 HD UVC WebCam                          | 33        | 0.59%   |
| Quanta ACER HD User Facing                          | 33        | 0.59%   |
| Apple FaceTime HD Camera                            | 33        | 0.59%   |
| Realtek USB Camera                                  | 32        | 0.57%   |
| IMC Networks ov9734_azurewave_camera                | 32        | 0.57%   |
| Chicony USB2.0 HD UVC WebCam                        | 32        | 0.57%   |
| Bison SunplusIT Integrated Camera                   | 32        | 0.57%   |
| Bison BisonCam,NB Pro                               | 32        | 0.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 383       | 31.04%  |
| Synaptics                          | 330       | 26.74%  |
| Shenzhen Goodix Technology         | 267       | 21.64%  |
| Elan Microelectronics              | 98        | 7.94%   |
| Upek                               | 43        | 3.48%   |
| AuthenTec                          | 40        | 3.24%   |
| LighTuning Technology              | 27        | 2.19%   |
| Realtek USB2.0 Finger Print Bridge | 20        | 1.62%   |
| STMicroelectronics                 | 8         | 0.65%   |
| Samsung Electronics                | 7         | 0.57%   |
| Focal-systems.Corp                 | 5         | 0.41%   |
| HOLTEK                             | 3         | 0.24%   |
| GDMicroelectronics                 | 2         | 0.16%   |
| DigitalPersona                     | 1         | 0.08%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 198       | 16.05%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 105       | 8.51%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 91        | 7.37%   |
| Elan ELAN:ARM-M4                                                           | 60        | 4.86%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 50        | 4.05%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 38        | 3.08%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 36        | 2.92%   |
| Shenzhen Goodix FingerPrint                                                | 36        | 2.92%   |
| Shenzhen Goodix Fingerprint Reader                                         | 33        | 2.67%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 32        | 2.59%   |
| Validity Sensors Synaptics WBDI                                            | 32        | 2.59%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 31        | 2.51%   |
| Elan ELAN:Fingerprint                                                      | 31        | 2.51%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 30        | 2.43%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 27        | 2.19%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 26        | 2.11%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 25        | 2.03%   |
| Validity Sensors VFS491                                                    | 24        | 1.94%   |
| Validity Sensors Fingerprint scanner                                       | 23        | 1.86%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 20        | 1.62%   |
| Synaptics UWP WBDI Device                                                  | 20        | 1.62%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 20        | 1.62%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 18        | 1.46%   |
| Synaptics Fingerprint reader [HP G6]                                       | 18        | 1.46%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 17        | 1.38%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 16        | 1.3%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 16        | 1.3%    |
| AuthenTec Fingerprint Sensor                                               | 16        | 1.3%    |
| Synaptics UWP WBDI                                                         | 13        | 1.05%   |
| Synaptics WBDI                                                             | 12        | 0.97%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 10        | 0.81%   |
| Unknown                                                                    | 10        | 0.81%   |
| STMicroelectronics Fingerprint Reader                                      | 8         | 0.65%   |
| AuthenTec AES2810                                                          | 8         | 0.65%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 8         | 0.65%   |
| Synaptics  WBDI                                                            | 7         | 0.57%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 7         | 0.57%   |
| Elan WBF Fingerprint Sensor                                                | 7         | 0.57%   |
| Validity Sensors VFS Fingerprint sensor                                    | 6         | 0.49%   |
| Upek TCS5B Fingerprint sensor                                              | 5         | 0.41%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 278       | 57.68%  |
| Alcor Micro               | 124       | 25.73%  |
| O2 Micro                  | 22        | 4.56%   |
| Upek                      | 20        | 4.15%   |
| Lenovo                    | 9         | 1.87%   |
| Gemalto (was Gemplus)     | 9         | 1.87%   |
| SCM Microsystems          | 4         | 0.83%   |
| Watchdata                 | 2         | 0.41%   |
| OmniKey                   | 2         | 0.41%   |
| Chicony Electronics       | 2         | 0.41%   |
| Cherry                    | 2         | 0.41%   |
| Aladdin Knowledge Systems | 2         | 0.41%   |
| Reiner SCT Kartensysteme  | 1         | 0.21%   |
| NXP Semiconductors        | 1         | 0.21%   |
| Giesecke & Devrient       | 1         | 0.21%   |
| Fujitsu Siemens Computers | 1         | 0.21%   |
| C3PO                      | 1         | 0.21%   |
| Aktiv                     | 1         | 0.21%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 124       | 25.73%  |
| Broadcom 58200                                                               | 99        | 20.54%  |
| Broadcom BCM5880 Secure Applications Processor                               | 79        | 16.39%  |
| Broadcom 5880                                                                | 65        | 13.49%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 35        | 7.26%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 20        | 4.15%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 20        | 4.15%   |
| Lenovo Integrated Smart Card Reader                                          | 9         | 1.87%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 7         | 1.45%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 3         | 0.62%   |
| Watchdata USB Key                                                            | 2         | 0.41%   |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 0.41%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 2         | 0.41%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 2         | 0.41%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.41%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.21%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.21%   |
| OmniKey CardMan 4321                                                         | 1         | 0.21%   |
| OmniKey CardMan 3121 (HID Technologies)                                      | 1         | 0.21%   |
| NXP Semiconductors PR533                                                     | 1         | 0.21%   |
| Giesecke & Devrient StarSign CUT                                             | 1         | 0.21%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.21%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.21%   |
| Fujitsu Siemens Computers Keyboard KB SCR                                    | 1         | 0.21%   |
| C3PO LTC31v2                                                                 | 1         | 0.21%   |
| Aktiv Rutoken lite                                                           | 1         | 0.21%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 3503      | 57.01%  |
| 1     | 2090      | 34.02%  |
| 2     | 478       | 7.78%   |
| 3     | 58        | 0.94%   |
| 5     | 4         | 0.07%   |
| 4     | 4         | 0.07%   |
| 8     | 2         | 0.03%   |
| 6     | 2         | 0.03%   |
| 10    | 1         | 0.02%   |
| 9     | 1         | 0.02%   |
| 7     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 1208      | 37.24%  |
| Graphics card            | 738       | 22.75%  |
| Chipcard                 | 454       | 14%     |
| Net/wireless             | 269       | 8.29%   |
| Camera                   | 207       | 6.38%   |
| Multimedia controller    | 111       | 3.42%   |
| Bluetooth                | 78        | 2.4%    |
| Sound                    | 49        | 1.51%   |
| Storage                  | 42        | 1.29%   |
| Card reader              | 29        | 0.89%   |
| Net/ethernet             | 20        | 0.62%   |
| Communication controller | 19        | 0.59%   |
| Network                  | 15        | 0.46%   |
| Flash memory             | 3         | 0.09%   |
| Modem                    | 2         | 0.06%   |

