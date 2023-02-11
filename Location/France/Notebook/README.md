Linux in France - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in France.

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

Total: 6385

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T400 6473PMG       | [07cba1c44b](https://linux-hardware.org/?probe=07cba1c44b) | Feb 01, 2023 |
| ASUSTek       | S551LN                      | [b7361dbc53](https://linux-hardware.org/?probe=b7361dbc53) | Feb 01, 2023 |
| Dell          | Inspiron 7501               | [426493e8a5](https://linux-hardware.org/?probe=426493e8a5) | Feb 01, 2023 |
| HP            | Notebook                    | [3cea0a0519](https://linux-hardware.org/?probe=3cea0a0519) | Jan 31, 2023 |
| Dell          | G3 3500                     | [4b519ab8a8](https://linux-hardware.org/?probe=4b519ab8a8) | Jan 31, 2023 |
| Acer          | Aspire E5-575G              | [463b7f859f](https://linux-hardware.org/?probe=463b7f859f) | Jan 31, 2023 |
| Dell          | Inspiron 7400               | [a6b124fd34](https://linux-hardware.org/?probe=a6b124fd34) | Jan 31, 2023 |
| HP            | Notebook                    | [82d58b21c4](https://linux-hardware.org/?probe=82d58b21c4) | Jan 31, 2023 |
| Dell          | Latitude 7410               | [fd07971a70](https://linux-hardware.org/?probe=fd07971a70) | Jan 31, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [4a2fcb6bd0](https://linux-hardware.org/?probe=4a2fcb6bd0) | Jan 31, 2023 |
| HUAWEI        | WRTB-WXX9                   | [60967eaaaf](https://linux-hardware.org/?probe=60967eaaaf) | Jan 31, 2023 |
| Lenovo        | ThinkPad T500 2055AZ1       | [1086813401](https://linux-hardware.org/?probe=1086813401) | Jan 30, 2023 |
| Lenovo        | ThinkPad T500 2055AZ1       | [0b43f40c2a](https://linux-hardware.org/?probe=0b43f40c2a) | Jan 30, 2023 |
| Acer          | Aspire E5-575G              | [532f5a8dbe](https://linux-hardware.org/?probe=532f5a8dbe) | Jan 30, 2023 |
| Acer          | Aspire M5-581TG             | [970a402846](https://linux-hardware.org/?probe=970a402846) | Jan 30, 2023 |
| Acer          | Aspire M5-581TG             | [c2d425d254](https://linux-hardware.org/?probe=c2d425d254) | Jan 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1ecef01472](https://linux-hardware.org/?probe=1ecef01472) | Jan 30, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [a5d6a22838](https://linux-hardware.org/?probe=a5d6a22838) | Jan 30, 2023 |
| Dell          | Latitude 7390               | [b154892be4](https://linux-hardware.org/?probe=b154892be4) | Jan 30, 2023 |
| HP            | ENVY Laptop 13-ah1xxx       | [360756b46a](https://linux-hardware.org/?probe=360756b46a) | Jan 30, 2023 |
| HUAWEI        | MACHD-WXX9                  | [cac5b8faa5](https://linux-hardware.org/?probe=cac5b8faa5) | Jan 29, 2023 |
| HP            | ZBook 14 G2                 | [4b1e1bc7e1](https://linux-hardware.org/?probe=4b1e1bc7e1) | Jan 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [47246aa8b5](https://linux-hardware.org/?probe=47246aa8b5) | Jan 29, 2023 |
| MSI           | CR700                       | [35d1ff1eac](https://linux-hardware.org/?probe=35d1ff1eac) | Jan 29, 2023 |
| Intel         | Unknown                     | [f387a4b732](https://linux-hardware.org/?probe=f387a4b732) | Jan 29, 2023 |
| Intel         | Unknown                     | [79aa357327](https://linux-hardware.org/?probe=79aa357327) | Jan 29, 2023 |
| HP            | ProBook 650 G1              | [830394a75e](https://linux-hardware.org/?probe=830394a75e) | Jan 29, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [90644628b4](https://linux-hardware.org/?probe=90644628b4) | Jan 29, 2023 |
| ASUSTek       | X550LB                      | [9590dd2f30](https://linux-hardware.org/?probe=9590dd2f30) | Jan 28, 2023 |
| Dell          | Latitude 7280               | [358f4c431f](https://linux-hardware.org/?probe=358f4c431f) | Jan 28, 2023 |
| Dell          | Latitude 7280               | [903e0489c4](https://linux-hardware.org/?probe=903e0489c4) | Jan 28, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | [c93d5da3f1](https://linux-hardware.org/?probe=c93d5da3f1) | Jan 28, 2023 |
| ASUSTek       | UX410UAR                    | [e9ac16c8ef](https://linux-hardware.org/?probe=e9ac16c8ef) | Jan 28, 2023 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | [57e0449f0f](https://linux-hardware.org/?probe=57e0449f0f) | Jan 28, 2023 |
| Valve         | Jupiter                     | [be17d6fd70](https://linux-hardware.org/?probe=be17d6fd70) | Jan 27, 2023 |
| TUXEDO        | InfinityBook S 15 Gen6      | [f5ebfcecc5](https://linux-hardware.org/?probe=f5ebfcecc5) | Jan 27, 2023 |
| HP            | Laptop 17-cp0xxx            | [e87b8175b1](https://linux-hardware.org/?probe=e87b8175b1) | Jan 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [56cb1ce2a6](https://linux-hardware.org/?probe=56cb1ce2a6) | Jan 27, 2023 |
| ASUSTek       | K73E                        | [66e0036452](https://linux-hardware.org/?probe=66e0036452) | Jan 27, 2023 |
| ASUSTek       | K73E                        | [91f049a01d](https://linux-hardware.org/?probe=91f049a01d) | Jan 27, 2023 |
| Dell          | Latitude E6420              | [a772965137](https://linux-hardware.org/?probe=a772965137) | Jan 27, 2023 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [117d80ff4d](https://linux-hardware.org/?probe=117d80ff4d) | Jan 27, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | [cf42b2f763](https://linux-hardware.org/?probe=cf42b2f763) | Jan 26, 2023 |
| Dell          | Latitude 5420               | [379a2dc9ab](https://linux-hardware.org/?probe=379a2dc9ab) | Jan 26, 2023 |
| Dell          | Latitude 5420               | [eec8ef8ddb](https://linux-hardware.org/?probe=eec8ef8ddb) | Jan 26, 2023 |
| HP            | 625                         | [06c4fa5119](https://linux-hardware.org/?probe=06c4fa5119) | Jan 25, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [7403ca2f73](https://linux-hardware.org/?probe=7403ca2f73) | Jan 25, 2023 |
| ASUSTek       | X510UAR                     | [7996de313e](https://linux-hardware.org/?probe=7996de313e) | Jan 25, 2023 |
| ASUSTek       | X510UAR                     | [3f4e15d14a](https://linux-hardware.org/?probe=3f4e15d14a) | Jan 25, 2023 |
| Toshiba       | Satellite Pro R50-B         | [d08118920b](https://linux-hardware.org/?probe=d08118920b) | Jan 25, 2023 |
| Lenovo        | ThinkPad L380 20M6S2YE00    | [e6c626133e](https://linux-hardware.org/?probe=e6c626133e) | Jan 25, 2023 |
| TrekStor      | Surfbook A13B               | [4306d9ba1c](https://linux-hardware.org/?probe=4306d9ba1c) | Jan 25, 2023 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [148b797f1a](https://linux-hardware.org/?probe=148b797f1a) | Jan 25, 2023 |
| ASUSTek       | X301A1                      | [f9ea8894f0](https://linux-hardware.org/?probe=f9ea8894f0) | Jan 25, 2023 |
| Sony          | VGN-NW21MF_W                | [dd4ac0a026](https://linux-hardware.org/?probe=dd4ac0a026) | Jan 24, 2023 |
| ASUSTek       | X540LJ                      | [41c91fdc7b](https://linux-hardware.org/?probe=41c91fdc7b) | Jan 24, 2023 |
| ASUSTek       | X540LJ                      | [199569e288](https://linux-hardware.org/?probe=199569e288) | Jan 24, 2023 |
| HP            | ProBook 6570b               | [841250ba59](https://linux-hardware.org/?probe=841250ba59) | Jan 24, 2023 |
| HP            | EliteBook 2560p             | [f57750e125](https://linux-hardware.org/?probe=f57750e125) | Jan 24, 2023 |
| Dell          | Precision 3551              | [1338d3df20](https://linux-hardware.org/?probe=1338d3df20) | Jan 23, 2023 |
| MSI           | Stealth GS66 12UH           | [9e79dca70b](https://linux-hardware.org/?probe=9e79dca70b) | Jan 23, 2023 |
| Dell          | Inspiron 7537               | [9181895f24](https://linux-hardware.org/?probe=9181895f24) | Jan 23, 2023 |
| Dell          | Latitude E4310              | [c32e006e62](https://linux-hardware.org/?probe=c32e006e62) | Jan 23, 2023 |
| Dell          | Latitude E4310              | [5045d5e911](https://linux-hardware.org/?probe=5045d5e911) | Jan 23, 2023 |
| Lenovo        | G50-70 20351                | [e0da886a95](https://linux-hardware.org/?probe=e0da886a95) | Jan 23, 2023 |
| ASUSTek       | T300CHI                     | [bc020f2d3e](https://linux-hardware.org/?probe=bc020f2d3e) | Jan 23, 2023 |
| Lenovo        | ThinkPad X200 7458VL3       | [3a91fa2c72](https://linux-hardware.org/?probe=3a91fa2c72) | Jan 23, 2023 |
| MSI           | PX60 6QE                    | [d820232c9c](https://linux-hardware.org/?probe=d820232c9c) | Jan 22, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [bc070879ba](https://linux-hardware.org/?probe=bc070879ba) | Jan 22, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [75f64e4cd4](https://linux-hardware.org/?probe=75f64e4cd4) | Jan 22, 2023 |
| Acer          | Aspire E1-570               | [30b3f2f346](https://linux-hardware.org/?probe=30b3f2f346) | Jan 22, 2023 |
| HP            | ProBook 4330s               | [f96c2452d3](https://linux-hardware.org/?probe=f96c2452d3) | Jan 22, 2023 |
| Lenovo        | ThinkPad P51 20HJS16Q0K     | [00e6c3575f](https://linux-hardware.org/?probe=00e6c3575f) | Jan 22, 2023 |
| Dell          | Latitude E5470              | [1a2810f035](https://linux-hardware.org/?probe=1a2810f035) | Jan 22, 2023 |
| Lenovo        | ThinkPad X260 20F5S4BY00    | [873bf3c874](https://linux-hardware.org/?probe=873bf3c874) | Jan 22, 2023 |
| HP            | 625                         | [838d72399b](https://linux-hardware.org/?probe=838d72399b) | Jan 22, 2023 |
| Dell          | XPS 15 9520                 | [893ebdd842](https://linux-hardware.org/?probe=893ebdd842) | Jan 22, 2023 |
| Lenovo        | ThinkPad E480 20KNCTO1WW    | [68ff3c02cb](https://linux-hardware.org/?probe=68ff3c02cb) | Jan 22, 2023 |
| ASUSTek       | G750JM                      | [8cb76e0d6d](https://linux-hardware.org/?probe=8cb76e0d6d) | Jan 22, 2023 |
| Dell          | G15 5510                    | [7cee6347e3](https://linux-hardware.org/?probe=7cee6347e3) | Jan 22, 2023 |
| MSI           | PS42 Modern 8MO             | [dfb621ce10](https://linux-hardware.org/?probe=dfb621ce10) | Jan 22, 2023 |
| MSI           | PS42 Modern 8MO             | [e1d7b236d3](https://linux-hardware.org/?probe=e1d7b236d3) | Jan 22, 2023 |
| Danew         | Dbook 131                   | [08911c133e](https://linux-hardware.org/?probe=08911c133e) | Jan 22, 2023 |
| Dell          | G3 3500                     | [941c11250c](https://linux-hardware.org/?probe=941c11250c) | Jan 21, 2023 |
| HP            | 625                         | [9a8a243973](https://linux-hardware.org/?probe=9a8a243973) | Jan 21, 2023 |
| Acer          | Aspire E1-570               | [9a0a65b69a](https://linux-hardware.org/?probe=9a0a65b69a) | Jan 21, 2023 |
| ASUSTek       | N751JK                      | [a67a4d078f](https://linux-hardware.org/?probe=a67a4d078f) | Jan 21, 2023 |
| Dell          | G7 7700                     | [427a79e665](https://linux-hardware.org/?probe=427a79e665) | Jan 21, 2023 |
| MSI           | GP75 Leopard 9SD            | [5b41a33a67](https://linux-hardware.org/?probe=5b41a33a67) | Jan 21, 2023 |
| Acer          | Predator PH315-52           | [5e28e4cbdc](https://linux-hardware.org/?probe=5e28e4cbdc) | Jan 21, 2023 |
| Acer          | Aspire 1640                 | [5b271fa3eb](https://linux-hardware.org/?probe=5b271fa3eb) | Jan 21, 2023 |
| Acer          | Aspire 1640                 | [fb70812654](https://linux-hardware.org/?probe=fb70812654) | Jan 21, 2023 |
| HP            | Laptop 15-dw0xxx            | [8de3cfc52e](https://linux-hardware.org/?probe=8de3cfc52e) | Jan 21, 2023 |
| HP            | EliteBook Folio 9480m       | [cf1b67c224](https://linux-hardware.org/?probe=cf1b67c224) | Jan 21, 2023 |
| HP            | EliteBook 840 G3            | [06f6499264](https://linux-hardware.org/?probe=06f6499264) | Jan 21, 2023 |
| MSI           | Katana GF66 12UC            | [543136f475](https://linux-hardware.org/?probe=543136f475) | Jan 20, 2023 |
| MSI           | CR650                       | [3d3a46f5c6](https://linux-hardware.org/?probe=3d3a46f5c6) | Jan 20, 2023 |
| MSI           | CR650                       | [7d3b1f25c4](https://linux-hardware.org/?probe=7d3b1f25c4) | Jan 20, 2023 |
| Dell          | Inspiron 5391               | [050e28c342](https://linux-hardware.org/?probe=050e28c342) | Jan 20, 2023 |
| Dell          | Latitude 7410               | [488f794ad5](https://linux-hardware.org/?probe=488f794ad5) | Jan 20, 2023 |
| Acer          | Aspire A515-57              | [3041b852df](https://linux-hardware.org/?probe=3041b852df) | Jan 20, 2023 |
| Dell          | Inspiron 14 5410            | [beaa2fdddb](https://linux-hardware.org/?probe=beaa2fdddb) | Jan 20, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [ccf1934924](https://linux-hardware.org/?probe=ccf1934924) | Jan 20, 2023 |
| Acer          | Swift SF314-57              | [6a813e0dd0](https://linux-hardware.org/?probe=6a813e0dd0) | Jan 20, 2023 |
| ASUSTek       | ROG Strix G533QS_G533QS     | [105b2daa8e](https://linux-hardware.org/?probe=105b2daa8e) | Jan 20, 2023 |
| Dell          | Precision 3551              | [4ff5a0ab8d](https://linux-hardware.org/?probe=4ff5a0ab8d) | Jan 19, 2023 |
| Apple         | MacBookPro8,1               | [b7f8407c8f](https://linux-hardware.org/?probe=b7f8407c8f) | Jan 19, 2023 |
| Dell          | XPS 15 9500                 | [606ba17221](https://linux-hardware.org/?probe=606ba17221) | Jan 19, 2023 |
| Lenovo        | IdeaPad 320-17AST 80XW      | [ae0457cc50](https://linux-hardware.org/?probe=ae0457cc50) | Jan 19, 2023 |
| Dell          | Latitude E5440              | [b1ac8af8ad](https://linux-hardware.org/?probe=b1ac8af8ad) | Jan 19, 2023 |
| Dell          | Latitude E5440              | [9b6d732a7c](https://linux-hardware.org/?probe=9b6d732a7c) | Jan 19, 2023 |
| Toshiba       | Satellite C70-A             | [ffaa715bdd](https://linux-hardware.org/?probe=ffaa715bdd) | Jan 19, 2023 |
| ASUSTek       | VivoBook E14 E402WAS        | [39f2ca64d4](https://linux-hardware.org/?probe=39f2ca64d4) | Jan 19, 2023 |
| Dell          | Vostro 1720                 | [1d06cb4ad8](https://linux-hardware.org/?probe=1d06cb4ad8) | Jan 18, 2023 |
| ASUSTek       | UX32VD                      | [7851952137](https://linux-hardware.org/?probe=7851952137) | Jan 18, 2023 |
| ASUSTek       | X411UN                      | [fad0f7ce44](https://linux-hardware.org/?probe=fad0f7ce44) | Jan 18, 2023 |
| Apple         | MacBookPro5,5               | [3dba9611d3](https://linux-hardware.org/?probe=3dba9611d3) | Jan 18, 2023 |
| Gigabyte      | P15FV5                      | [5a03ba32c0](https://linux-hardware.org/?probe=5a03ba32c0) | Jan 18, 2023 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | [04d0c02d29](https://linux-hardware.org/?probe=04d0c02d29) | Jan 18, 2023 |
| Dell          | Inspiron 7537               | [95cc108754](https://linux-hardware.org/?probe=95cc108754) | Jan 18, 2023 |
| Packard Be... | EasyNote LE69KB             | [b1caf1d323](https://linux-hardware.org/?probe=b1caf1d323) | Jan 17, 2023 |
| Dell          | Latitude 5500               | [e0ae9cb026](https://linux-hardware.org/?probe=e0ae9cb026) | Jan 17, 2023 |
| Toshiba       | Satellite L655D             | [38b26485d3](https://linux-hardware.org/?probe=38b26485d3) | Jan 17, 2023 |
| Lenovo        | ThinkPad T61 766112G        | [fb772cc0cf](https://linux-hardware.org/?probe=fb772cc0cf) | Jan 17, 2023 |
| Dell          | Latitude E5540              | [e8e30eb563](https://linux-hardware.org/?probe=e8e30eb563) | Jan 17, 2023 |
| Dell          | Vostro 1720                 | [d02dee9ab2](https://linux-hardware.org/?probe=d02dee9ab2) | Jan 17, 2023 |
| Dell          | Inspiron 14 5418            | [e3bfdaa6a4](https://linux-hardware.org/?probe=e3bfdaa6a4) | Jan 17, 2023 |
| Dell          | Latitude 5410               | [c97379d747](https://linux-hardware.org/?probe=c97379d747) | Jan 17, 2023 |
| MSI           | GP70 2OD                    | [7405037963](https://linux-hardware.org/?probe=7405037963) | Jan 17, 2023 |
| HP            | ZBook 14 G2                 | [d501532972](https://linux-hardware.org/?probe=d501532972) | Jan 17, 2023 |
| Toshiba       | Satellite A200              | [68ae2ab1d0](https://linux-hardware.org/?probe=68ae2ab1d0) | Jan 17, 2023 |
| HP            | EliteBook 820 G3            | [4abc3c8796](https://linux-hardware.org/?probe=4abc3c8796) | Jan 17, 2023 |
| Dell          | Studio 1735                 | [96d3df9639](https://linux-hardware.org/?probe=96d3df9639) | Jan 17, 2023 |
| Google        | Lulu                        | [b0e2a5a9b3](https://linux-hardware.org/?probe=b0e2a5a9b3) | Jan 16, 2023 |
| Samsung       | R530/R730/P530              | [e6752958eb](https://linux-hardware.org/?probe=e6752958eb) | Jan 16, 2023 |
| Acer          | Aspire 8942G                | [907b837cec](https://linux-hardware.org/?probe=907b837cec) | Jan 16, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [7100a33e7e](https://linux-hardware.org/?probe=7100a33e7e) | Jan 15, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [9ac2f0ab83](https://linux-hardware.org/?probe=9ac2f0ab83) | Jan 15, 2023 |
| HP            | Compaq 15                   | [ddfd4fd188](https://linux-hardware.org/?probe=ddfd4fd188) | Jan 15, 2023 |
| Dell          | Latitude E6420              | [3594f88292](https://linux-hardware.org/?probe=3594f88292) | Jan 15, 2023 |
| Toshiba       | TECRA A11                   | [3d58fc9423](https://linux-hardware.org/?probe=3d58fc9423) | Jan 15, 2023 |
| HP            | EliteBook 840 G2            | [4850c49a4a](https://linux-hardware.org/?probe=4850c49a4a) | Jan 15, 2023 |
| HP            | EliteBook 840 G2            | [972e3e026a](https://linux-hardware.org/?probe=972e3e026a) | Jan 15, 2023 |
| Acer          | Nitro AN515-44              | [f1e7eba4ca](https://linux-hardware.org/?probe=f1e7eba4ca) | Jan 15, 2023 |
| HP            | ZBook 14 G2                 | [239512c0c1](https://linux-hardware.org/?probe=239512c0c1) | Jan 15, 2023 |
| Acer          | Aspire 7250                 | [bcb2916be8](https://linux-hardware.org/?probe=bcb2916be8) | Jan 15, 2023 |
| HP            | EliteBook 8570w             | [53eb92efda](https://linux-hardware.org/?probe=53eb92efda) | Jan 15, 2023 |
| Dell          | Inspiron 5749               | [445264f815](https://linux-hardware.org/?probe=445264f815) | Jan 15, 2023 |
| Packard Be... | EasyNote ML65               | [e3599cb723](https://linux-hardware.org/?probe=e3599cb723) | Jan 15, 2023 |
| Dell          | Inspiron 5370               | [78b4039791](https://linux-hardware.org/?probe=78b4039791) | Jan 15, 2023 |
| Acer          | Aspire 7551                 | [b3e5df94f4](https://linux-hardware.org/?probe=b3e5df94f4) | Jan 15, 2023 |
| Apple         | MacBookPro9,2               | [2265827caa](https://linux-hardware.org/?probe=2265827caa) | Jan 14, 2023 |
| Lenovo        | G50-45 80E3                 | [ab05084e01](https://linux-hardware.org/?probe=ab05084e01) | Jan 14, 2023 |
| Toshiba       | TECRA A11                   | [758daba5e5](https://linux-hardware.org/?probe=758daba5e5) | Jan 14, 2023 |
| ASUSTek       | K75VM                       | [6cd0e1793b](https://linux-hardware.org/?probe=6cd0e1793b) | Jan 14, 2023 |
| Lenovo        | ThinkPad T420 42363C4       | [089518e186](https://linux-hardware.org/?probe=089518e186) | Jan 14, 2023 |
| Toshiba       | PORTEGE Z30-B               | [4c5c663576](https://linux-hardware.org/?probe=4c5c663576) | Jan 14, 2023 |
| Samsung       | N150/N210/N220              | [5d2c7b7ded](https://linux-hardware.org/?probe=5d2c7b7ded) | Jan 14, 2023 |
| Lenovo        | G500 20236                  | [d92542c9e8](https://linux-hardware.org/?probe=d92542c9e8) | Jan 14, 2023 |
| Lenovo        | ThinkPad L510 2873A17       | [13f5fd23e5](https://linux-hardware.org/?probe=13f5fd23e5) | Jan 14, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | [56c9afafb4](https://linux-hardware.org/?probe=56c9afafb4) | Jan 14, 2023 |
| Acer          | Aspire 5935                 | [40a8c82828](https://linux-hardware.org/?probe=40a8c82828) | Jan 14, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [699d727f84](https://linux-hardware.org/?probe=699d727f84) | Jan 14, 2023 |
| Sony          | SVE1513U1ESI                | [d1c4a0dc83](https://linux-hardware.org/?probe=d1c4a0dc83) | Jan 14, 2023 |
| Lenovo        | ThinkPad X61 Tablet 7767... | [558f3d0d93](https://linux-hardware.org/?probe=558f3d0d93) | Jan 14, 2023 |
| HP            | EliteBook 820 G3            | [3a330d3173](https://linux-hardware.org/?probe=3a330d3173) | Jan 13, 2023 |
| Lenovo        | IdeaPad 330-17IKB 81DK      | [3df12b0c9c](https://linux-hardware.org/?probe=3df12b0c9c) | Jan 13, 2023 |
| HP            | ProBook 4540s               | [9b33dc4291](https://linux-hardware.org/?probe=9b33dc4291) | Jan 13, 2023 |
| Acer          | Nitro AN515-42              | [940dcb54ef](https://linux-hardware.org/?probe=940dcb54ef) | Jan 13, 2023 |
| Dell          | XPS 15 9500                 | [00348d3769](https://linux-hardware.org/?probe=00348d3769) | Jan 13, 2023 |
| ASUSTek       | A7K                         | [5307ba44c0](https://linux-hardware.org/?probe=5307ba44c0) | Jan 13, 2023 |
| ASUSTek       | X751LJ                      | [2cbaf315da](https://linux-hardware.org/?probe=2cbaf315da) | Jan 13, 2023 |
| ASUSTek       | A7K                         | [1303f158ab](https://linux-hardware.org/?probe=1303f158ab) | Jan 13, 2023 |
| Teclast       | F6 Plus                     | [27cd155156](https://linux-hardware.org/?probe=27cd155156) | Jan 13, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [73ca27df51](https://linux-hardware.org/?probe=73ca27df51) | Jan 13, 2023 |
| HP            | Notebook                    | [1baf122d48](https://linux-hardware.org/?probe=1baf122d48) | Jan 13, 2023 |
| Samsung       | RV410/RV510/S3510/E3510     | [22749c467f](https://linux-hardware.org/?probe=22749c467f) | Jan 13, 2023 |
| Notebook      | NJx0MU                      | [b3711a9adc](https://linux-hardware.org/?probe=b3711a9adc) | Jan 13, 2023 |
| Dell          | XPS 13 9380                 | [ece6bd7a3c](https://linux-hardware.org/?probe=ece6bd7a3c) | Jan 13, 2023 |
| TUXEDO        | Book XA15 / XA17 Gen10      | [343813c285](https://linux-hardware.org/?probe=343813c285) | Jan 13, 2023 |
| Dell          | System Vostro 3750          | [91b0444e5e](https://linux-hardware.org/?probe=91b0444e5e) | Jan 12, 2023 |
| HP            | 15                          | [b06a589496](https://linux-hardware.org/?probe=b06a589496) | Jan 12, 2023 |
| Acer          | Swift SF314-54G             | [4272389a24](https://linux-hardware.org/?probe=4272389a24) | Jan 12, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [219ffa8cfd](https://linux-hardware.org/?probe=219ffa8cfd) | Jan 12, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [552d9fd542](https://linux-hardware.org/?probe=552d9fd542) | Jan 12, 2023 |
| Lenovo        | Legion 7 16ITHg6 82K6       | [22bd8d5315](https://linux-hardware.org/?probe=22bd8d5315) | Jan 12, 2023 |
| ASUSTek       | T100HAN                     | [7df180ed97](https://linux-hardware.org/?probe=7df180ed97) | Jan 12, 2023 |
| Lenovo        | ThinkPad R61 8935AC7        | [4128f195f0](https://linux-hardware.org/?probe=4128f195f0) | Jan 11, 2023 |
| ASUSTek       | N751JK                      | [259556fd6f](https://linux-hardware.org/?probe=259556fd6f) | Jan 11, 2023 |
| HP            | Notebook                    | [3ece4717c4](https://linux-hardware.org/?probe=3ece4717c4) | Jan 11, 2023 |
| HP            | EliteBook 640 14 inch G9... | [a3dacf19d0](https://linux-hardware.org/?probe=a3dacf19d0) | Jan 11, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [a2363c6939](https://linux-hardware.org/?probe=a2363c6939) | Jan 11, 2023 |
| ASUSTek       | ZenBook Pro Duo UX582HM_... | [47d808cdc7](https://linux-hardware.org/?probe=47d808cdc7) | Jan 10, 2023 |
| Lenovo        | ThinkPad X270 20HN0015FR    | [e303c543ba](https://linux-hardware.org/?probe=e303c543ba) | Jan 10, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [28df55cca2](https://linux-hardware.org/?probe=28df55cca2) | Jan 10, 2023 |
| HP            | EliteBook 8460p             | [27ab381a1d](https://linux-hardware.org/?probe=27ab381a1d) | Jan 10, 2023 |
| Lenovo        | ThinkPad X201 3680AQ1       | [4a65277a98](https://linux-hardware.org/?probe=4a65277a98) | Jan 10, 2023 |
| HP            | Pavilion Notebook           | [f70bd958b7](https://linux-hardware.org/?probe=f70bd958b7) | Jan 10, 2023 |
| HP            | Pavilion Notebook           | [937414941b](https://linux-hardware.org/?probe=937414941b) | Jan 10, 2023 |
| Acer          | Aspire E5-575G              | [21bfdfce4b](https://linux-hardware.org/?probe=21bfdfce4b) | Jan 10, 2023 |
| Dell          | Inspiron 5502               | [b09655552e](https://linux-hardware.org/?probe=b09655552e) | Jan 09, 2023 |
| ASUSTek       | X301A1                      | [c98ae98676](https://linux-hardware.org/?probe=c98ae98676) | Jan 09, 2023 |
| Thomson       | N14C4WH64                   | [e9050d81df](https://linux-hardware.org/?probe=e9050d81df) | Jan 09, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [e384aea51e](https://linux-hardware.org/?probe=e384aea51e) | Jan 09, 2023 |
| Dell          | Precision 5560              | [cb05d14e97](https://linux-hardware.org/?probe=cb05d14e97) | Jan 09, 2023 |
| ASUSTek       | K50C                        | [266dd917fe](https://linux-hardware.org/?probe=266dd917fe) | Jan 08, 2023 |
| ASUSTek       | S301LA                      | [9745e5ae33](https://linux-hardware.org/?probe=9745e5ae33) | Jan 08, 2023 |
| Dell          | Inspiron 5593               | [7ada807633](https://linux-hardware.org/?probe=7ada807633) | Jan 08, 2023 |
| Framework     | Laptop                      | [0c13e3ab8d](https://linux-hardware.org/?probe=0c13e3ab8d) | Jan 08, 2023 |
| Lenovo        | G505 20240                  | [e8611b7b9b](https://linux-hardware.org/?probe=e8611b7b9b) | Jan 08, 2023 |
| ASUSTek       | N73SV                       | [4cf1c4b702](https://linux-hardware.org/?probe=4cf1c4b702) | Jan 08, 2023 |
| ASUSTek       | G750JX                      | [128fe1567d](https://linux-hardware.org/?probe=128fe1567d) | Jan 08, 2023 |
| MSI           | CR62 6M                     | [942ca0f3b3](https://linux-hardware.org/?probe=942ca0f3b3) | Jan 07, 2023 |
| HP            | Compaq 6910p                | [8ba65cb6b5](https://linux-hardware.org/?probe=8ba65cb6b5) | Jan 07, 2023 |
| Lenovo        | ThinkPad T480s 20L8S2SX1... | [3c35917c78](https://linux-hardware.org/?probe=3c35917c78) | Jan 07, 2023 |
| HP            | Laptop 15-db0xxx            | [ff51bb2dd9](https://linux-hardware.org/?probe=ff51bb2dd9) | Jan 07, 2023 |
| Lenovo        | ThinkPad X220 4291T4Y       | [b1c7c505b2](https://linux-hardware.org/?probe=b1c7c505b2) | Jan 07, 2023 |
| HP            | EliteBook 850 G6            | [595e6fa89a](https://linux-hardware.org/?probe=595e6fa89a) | Jan 07, 2023 |
| Dell          | Latitude E6410              | [f664cab1c4](https://linux-hardware.org/?probe=f664cab1c4) | Jan 07, 2023 |
| Acer          | Aspire E5-772G              | [c840cf9ca5](https://linux-hardware.org/?probe=c840cf9ca5) | Jan 07, 2023 |
| Lenovo        | G505 20240                  | [a2910be7b2](https://linux-hardware.org/?probe=a2910be7b2) | Jan 07, 2023 |
| Lenovo        | ThinkPad T530 2392CTO       | [8c1cf48875](https://linux-hardware.org/?probe=8c1cf48875) | Jan 07, 2023 |
| Framework     | Laptop                      | [cfabfdec3c](https://linux-hardware.org/?probe=cfabfdec3c) | Jan 07, 2023 |
| Toshiba       | Satellite Pro C850-10N      | [8f013ca042](https://linux-hardware.org/?probe=8f013ca042) | Jan 07, 2023 |
| Lenovo        | IdeaPad S300 9803           | [1f31e39066](https://linux-hardware.org/?probe=1f31e39066) | Jan 07, 2023 |
| HP            | ZBook Studio G5             | [dfd35ce9ca](https://linux-hardware.org/?probe=dfd35ce9ca) | Jan 07, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [41e6bde836](https://linux-hardware.org/?probe=41e6bde836) | Jan 06, 2023 |
| Lenovo        | ThinkPad X200s 7469A98      | [475d16af35](https://linux-hardware.org/?probe=475d16af35) | Jan 06, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [659196ed95](https://linux-hardware.org/?probe=659196ed95) | Jan 06, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [cc8d4f6e6d](https://linux-hardware.org/?probe=cc8d4f6e6d) | Jan 06, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [393397e25c](https://linux-hardware.org/?probe=393397e25c) | Jan 06, 2023 |
| Lenovo        | ThinkPad T470s 20HGS36U0... | [cd1fc92879](https://linux-hardware.org/?probe=cd1fc92879) | Jan 06, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [40a6c7370b](https://linux-hardware.org/?probe=40a6c7370b) | Jan 05, 2023 |
| Valve         | Jupiter                     | [aa4288024c](https://linux-hardware.org/?probe=aa4288024c) | Jan 05, 2023 |
| HP            | Notebook                    | [e63dc1a81a](https://linux-hardware.org/?probe=e63dc1a81a) | Jan 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [892ada8934](https://linux-hardware.org/?probe=892ada8934) | Jan 05, 2023 |
| ASUSTek       | F50SV                       | [ae6f64f5df](https://linux-hardware.org/?probe=ae6f64f5df) | Jan 05, 2023 |
| Dell          | Precision 7520              | [10c791a9f5](https://linux-hardware.org/?probe=10c791a9f5) | Jan 05, 2023 |
| HP            | EliteBook 840 Aero G8 No... | [b9f4ca82d2](https://linux-hardware.org/?probe=b9f4ca82d2) | Jan 05, 2023 |
| ASUSTek       | N73SV                       | [4ed6689d7c](https://linux-hardware.org/?probe=4ed6689d7c) | Jan 05, 2023 |
| HP            | ProBook 470 G2              | [1f62ff6417](https://linux-hardware.org/?probe=1f62ff6417) | Jan 04, 2023 |
| UNOWHY        | Y13G011S4EI                 | [1e25e7059a](https://linux-hardware.org/?probe=1e25e7059a) | Jan 04, 2023 |
| ASUSTek       | N73SV                       | [2cba5c99c4](https://linux-hardware.org/?probe=2cba5c99c4) | Jan 04, 2023 |
| HP            | ProBook 6570b               | [875054c6d7](https://linux-hardware.org/?probe=875054c6d7) | Jan 03, 2023 |
| Dell          | Latitude 7410               | [028f9b0434](https://linux-hardware.org/?probe=028f9b0434) | Jan 03, 2023 |
| ASUSTek       | G56JR                       | [d8d521b964](https://linux-hardware.org/?probe=d8d521b964) | Jan 03, 2023 |
| Acer          | Aspire V3-772G              | [fac5053200](https://linux-hardware.org/?probe=fac5053200) | Jan 03, 2023 |
| ASUSTek       | G56JR                       | [ccebb5dd27](https://linux-hardware.org/?probe=ccebb5dd27) | Jan 02, 2023 |
| HP            | Stream Notebook             | [0cacfea12c](https://linux-hardware.org/?probe=0cacfea12c) | Jan 02, 2023 |
| ASUSTek       | T100TA                      | [73a67d66af](https://linux-hardware.org/?probe=73a67d66af) | Jan 02, 2023 |
| HP            | ZBook 15 G3                 | [7ef67aea7b](https://linux-hardware.org/?probe=7ef67aea7b) | Jan 02, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E0D    | [a1f966e5e8](https://linux-hardware.org/?probe=a1f966e5e8) | Jan 02, 2023 |
| ASUSTek       | T100TA                      | [2c33e446d4](https://linux-hardware.org/?probe=2c33e446d4) | Jan 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [1be42c9032](https://linux-hardware.org/?probe=1be42c9032) | Jan 02, 2023 |
| Dell          | System Inspiron N411Z       | [21f279751c](https://linux-hardware.org/?probe=21f279751c) | Jan 01, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [aba076d86d](https://linux-hardware.org/?probe=aba076d86d) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming FX505DT_TUF50... | [f9db70d551](https://linux-hardware.org/?probe=f9db70d551) | Jan 01, 2023 |
| Acer          | Aspire SW3-013              | [44016de6db](https://linux-hardware.org/?probe=44016de6db) | Jan 01, 2023 |
| Lenovo        | ThinkPad T460s 20FAS1E70... | [c13c5e3d0d](https://linux-hardware.org/?probe=c13c5e3d0d) | Jan 01, 2023 |
| ASUSTek       | S551LN                      | [12629ba25d](https://linux-hardware.org/?probe=12629ba25d) | Jan 01, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [f438866c0d](https://linux-hardware.org/?probe=f438866c0d) | Jan 01, 2023 |
| HP            | Pavilion dv6                | [30ec83dbd4](https://linux-hardware.org/?probe=30ec83dbd4) | Dec 31, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [ac397dc318](https://linux-hardware.org/?probe=ac397dc318) | Dec 31, 2022 |
| Acer          | Aspire A514-54              | [5775c77a91](https://linux-hardware.org/?probe=5775c77a91) | Dec 31, 2022 |
| HP            | Laptop 17-cn1xxx            | [dde4bcd574](https://linux-hardware.org/?probe=dde4bcd574) | Dec 30, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [d44828a455](https://linux-hardware.org/?probe=d44828a455) | Dec 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [afa28ba4f3](https://linux-hardware.org/?probe=afa28ba4f3) | Dec 30, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [43f808e1e4](https://linux-hardware.org/?probe=43f808e1e4) | Dec 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [80abf89bc6](https://linux-hardware.org/?probe=80abf89bc6) | Dec 30, 2022 |
| Acer          | Nitro AN515-57              | [b0bfa9530a](https://linux-hardware.org/?probe=b0bfa9530a) | Dec 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [ce66958f69](https://linux-hardware.org/?probe=ce66958f69) | Dec 29, 2022 |
| ASUSTek       | G1                          | [1f8e426f96](https://linux-hardware.org/?probe=1f8e426f96) | Dec 29, 2022 |
| Toshiba       | Satellite C870-13V          | [5ad370d470](https://linux-hardware.org/?probe=5ad370d470) | Dec 29, 2022 |
| Acer          | Aspire 4820TG               | [77721c13c4](https://linux-hardware.org/?probe=77721c13c4) | Dec 29, 2022 |
| ASUSTek       | GL553VD                     | [9c4eab8774](https://linux-hardware.org/?probe=9c4eab8774) | Dec 29, 2022 |
| HP            | Pavilion 17                 | [4a8c3f4014](https://linux-hardware.org/?probe=4a8c3f4014) | Dec 29, 2022 |
| Shenzhen W... | TANK56                      | [4cd3e6c8e4](https://linux-hardware.org/?probe=4cd3e6c8e4) | Dec 29, 2022 |
| Lenovo        | G50-70 20351                | [6ece20ec58](https://linux-hardware.org/?probe=6ece20ec58) | Dec 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [499c91958a](https://linux-hardware.org/?probe=499c91958a) | Dec 29, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [b915fc0d47](https://linux-hardware.org/?probe=b915fc0d47) | Dec 28, 2022 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [74c1f3a4c2](https://linux-hardware.org/?probe=74c1f3a4c2) | Dec 28, 2022 |
| ASUSTek       | X555BP                      | [6ddc84aa0d](https://linux-hardware.org/?probe=6ddc84aa0d) | Dec 28, 2022 |
| Toshiba       | Satellite C55-C             | [2966924363](https://linux-hardware.org/?probe=2966924363) | Dec 28, 2022 |
| Toshiba       | Satellite C55-C             | [f3e27d230f](https://linux-hardware.org/?probe=f3e27d230f) | Dec 28, 2022 |
| Toshiba       | PORTEGE Z30T-A              | [cab72e8a11](https://linux-hardware.org/?probe=cab72e8a11) | Dec 28, 2022 |
| Dell          | G3 3500                     | [78e803b44e](https://linux-hardware.org/?probe=78e803b44e) | Dec 28, 2022 |
| MSI           | GE62 2QC                    | [dbd69d70ac](https://linux-hardware.org/?probe=dbd69d70ac) | Dec 27, 2022 |
| MSI           | GP62 7QF                    | [3db82bd91e](https://linux-hardware.org/?probe=3db82bd91e) | Dec 27, 2022 |
| ASUSTek       | G56JR                       | [3acee33976](https://linux-hardware.org/?probe=3acee33976) | Dec 27, 2022 |
| Acer          | Aspire SW3-013              | [04286c0e93](https://linux-hardware.org/?probe=04286c0e93) | Dec 27, 2022 |
| Dell          | Inspiron 5579               | [6fbb0cbd09](https://linux-hardware.org/?probe=6fbb0cbd09) | Dec 27, 2022 |
| Dell          | Inspiron 5579               | [838cda532a](https://linux-hardware.org/?probe=838cda532a) | Dec 27, 2022 |
| Notebook      | L14xMU                      | [7644bc65e2](https://linux-hardware.org/?probe=7644bc65e2) | Dec 27, 2022 |
| Acer          | Nitro AN515-57              | [8ecb7e11b3](https://linux-hardware.org/?probe=8ecb7e11b3) | Dec 26, 2022 |
| Dell          | Inspiron 1012               | [3dd6b8a416](https://linux-hardware.org/?probe=3dd6b8a416) | Dec 26, 2022 |
| Acer          | Swift SF314-43              | [f7c9b3538e](https://linux-hardware.org/?probe=f7c9b3538e) | Dec 26, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [6703f01cfc](https://linux-hardware.org/?probe=6703f01cfc) | Dec 26, 2022 |
| ASUSTek       | K61IC                       | [4c34b8d5a1](https://linux-hardware.org/?probe=4c34b8d5a1) | Dec 26, 2022 |
| Lenovo        | Legion 5 15IAH7H 82RB       | [e47f890444](https://linux-hardware.org/?probe=e47f890444) | Dec 26, 2022 |
| Lenovo        | Legion 5 15IAH7H 82RB       | [c288ade12d](https://linux-hardware.org/?probe=c288ade12d) | Dec 26, 2022 |
| Lenovo        | ThinkPad X250 20CLS1UB00    | [fc8b2899fa](https://linux-hardware.org/?probe=fc8b2899fa) | Dec 25, 2022 |
| MSI           | CR700                       | [92b97fec48](https://linux-hardware.org/?probe=92b97fec48) | Dec 25, 2022 |
| MSI           | CR700                       | [df25c10894](https://linux-hardware.org/?probe=df25c10894) | Dec 25, 2022 |
| HP            | ProBook 450 G1              | [5497596ef1](https://linux-hardware.org/?probe=5497596ef1) | Dec 25, 2022 |
| HONOR         | BOD-WXX9                    | [894521b876](https://linux-hardware.org/?probe=894521b876) | Dec 25, 2022 |
| HP            | ProBook 450 G1              | [26c346f0ab](https://linux-hardware.org/?probe=26c346f0ab) | Dec 25, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [08af6df0dd](https://linux-hardware.org/?probe=08af6df0dd) | Dec 25, 2022 |
| HP            | ENVY 17                     | [f3458ee7d5](https://linux-hardware.org/?probe=f3458ee7d5) | Dec 25, 2022 |
| HP            | ENVY Notebook               | [16af8b4da3](https://linux-hardware.org/?probe=16af8b4da3) | Dec 25, 2022 |
| Lenovo        | ThinkPad L530 24781P9       | [fd8de03405](https://linux-hardware.org/?probe=fd8de03405) | Dec 25, 2022 |
| Lenovo        | Yoga 2 13 20344             | [9d8bce4c41](https://linux-hardware.org/?probe=9d8bce4c41) | Dec 25, 2022 |
| Lenovo        | ThinkPad X220 4291UUC       | [6307be520e](https://linux-hardware.org/?probe=6307be520e) | Dec 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [a1f4999c28](https://linux-hardware.org/?probe=a1f4999c28) | Dec 25, 2022 |
| Toshiba       | Satellite C650              | [89b85889f9](https://linux-hardware.org/?probe=89b85889f9) | Dec 25, 2022 |
| ASUSTek       | G751JT                      | [16e989ff99](https://linux-hardware.org/?probe=16e989ff99) | Dec 25, 2022 |
| HP            | Laptop 15-bw0xx             | [42221f61fb](https://linux-hardware.org/?probe=42221f61fb) | Dec 25, 2022 |
| Dell          | XPS 15 9510                 | [6c809c224c](https://linux-hardware.org/?probe=6c809c224c) | Dec 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [2b71327126](https://linux-hardware.org/?probe=2b71327126) | Dec 24, 2022 |
| Lenovo        | ThinkPad T470s 20HGS0AY0... | [28e67f37bc](https://linux-hardware.org/?probe=28e67f37bc) | Dec 24, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | [dab48b870c](https://linux-hardware.org/?probe=dab48b870c) | Dec 23, 2022 |
| HP            | Pavilion 17                 | [0adc0d708b](https://linux-hardware.org/?probe=0adc0d708b) | Dec 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [0d1532282f](https://linux-hardware.org/?probe=0d1532282f) | Dec 23, 2022 |
| Acer          | E1-510                      | [463c668d4e](https://linux-hardware.org/?probe=463c668d4e) | Dec 23, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [97749ab6b4](https://linux-hardware.org/?probe=97749ab6b4) | Dec 23, 2022 |
| Acer          | TravelMate 7730             | [8d166266b9](https://linux-hardware.org/?probe=8d166266b9) | Dec 23, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [e2e9b14a43](https://linux-hardware.org/?probe=e2e9b14a43) | Dec 23, 2022 |
| Acer          | Aspire E5-575G              | [bc197d71d8](https://linux-hardware.org/?probe=bc197d71d8) | Dec 23, 2022 |
| Danew         | Dbook 131                   | [25dbe464cd](https://linux-hardware.org/?probe=25dbe464cd) | Dec 23, 2022 |
| HP            | ProBook 440 G7              | [33a03f23cc](https://linux-hardware.org/?probe=33a03f23cc) | Dec 23, 2022 |
| Dell          | Inspiron 1546               | [7812af7998](https://linux-hardware.org/?probe=7812af7998) | Dec 23, 2022 |
| Unknown       | Unknown                     | [f9c4fecaf4](https://linux-hardware.org/?probe=f9c4fecaf4) | Dec 23, 2022 |
| Unknown       | Unknown                     | [3832db2827](https://linux-hardware.org/?probe=3832db2827) | Dec 23, 2022 |
| Lenovo        | IdeaPad 700-17ISK 80RV      | [59bf9e85bf](https://linux-hardware.org/?probe=59bf9e85bf) | Dec 22, 2022 |
| HP            | Pavilion 17                 | [65dcf1eead](https://linux-hardware.org/?probe=65dcf1eead) | Dec 22, 2022 |
| ASUSTek       | X555LF                      | [bed000b293](https://linux-hardware.org/?probe=bed000b293) | Dec 22, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [5bbf457036](https://linux-hardware.org/?probe=5bbf457036) | Dec 22, 2022 |
| ASUSTek       | 1015BXO                     | [7cce9a65ec](https://linux-hardware.org/?probe=7cce9a65ec) | Dec 22, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [be01b942ed](https://linux-hardware.org/?probe=be01b942ed) | Dec 22, 2022 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | [16cae3015a](https://linux-hardware.org/?probe=16cae3015a) | Dec 21, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [28013105ef](https://linux-hardware.org/?probe=28013105ef) | Dec 21, 2022 |
| Lenovo        | IdeaPad S145-15API 81UT     | [6ec5c4fc19](https://linux-hardware.org/?probe=6ec5c4fc19) | Dec 21, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [47ac3ac319](https://linux-hardware.org/?probe=47ac3ac319) | Dec 21, 2022 |
| HP            | Laptop 15s-eq1xxx           | [fd0cb86f82](https://linux-hardware.org/?probe=fd0cb86f82) | Dec 21, 2022 |
| ASUSTek       | VivoBook S14 X411UF         | [894f0ab5df](https://linux-hardware.org/?probe=894f0ab5df) | Dec 21, 2022 |
| Acer          | Aspire 7730ZG               | [bf9325456e](https://linux-hardware.org/?probe=bf9325456e) | Dec 20, 2022 |
| MSI           | GS73VR 7RF                  | [7f37920146](https://linux-hardware.org/?probe=7f37920146) | Dec 20, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [c0f4dfeb74](https://linux-hardware.org/?probe=c0f4dfeb74) | Dec 20, 2022 |
| Timi          | TM1701                      | [49f0865503](https://linux-hardware.org/?probe=49f0865503) | Dec 20, 2022 |
| Acer          | TravelMate 7730             | [8078925015](https://linux-hardware.org/?probe=8078925015) | Dec 20, 2022 |
| LG Electro... | 17Z90P-G.AA56F              | [fa43417151](https://linux-hardware.org/?probe=fa43417151) | Dec 19, 2022 |
| ASUSTek       | S551LN                      | [df4a754b5d](https://linux-hardware.org/?probe=df4a754b5d) | Dec 19, 2022 |
| ASUSTek       | X75VC                       | [a16ed79c3d](https://linux-hardware.org/?probe=a16ed79c3d) | Dec 19, 2022 |
| ASUSTek       | X550MD                      | [16f09c5918](https://linux-hardware.org/?probe=16f09c5918) | Dec 19, 2022 |
| Dell          | Inspiron 7720               | [f29071b4a8](https://linux-hardware.org/?probe=f29071b4a8) | Dec 18, 2022 |
| HP            | ProBook 4720s               | [cd684d5dbe](https://linux-hardware.org/?probe=cd684d5dbe) | Dec 18, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [e0f5a5db4c](https://linux-hardware.org/?probe=e0f5a5db4c) | Dec 18, 2022 |
| HP            | EliteBook 850 G3            | [72eccc0663](https://linux-hardware.org/?probe=72eccc0663) | Dec 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [83887c3224](https://linux-hardware.org/?probe=83887c3224) | Dec 18, 2022 |
| HUAWEI        | BOD-WXX9                    | [7895ac3dc1](https://linux-hardware.org/?probe=7895ac3dc1) | Dec 17, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [f15a27fd5e](https://linux-hardware.org/?probe=f15a27fd5e) | Dec 17, 2022 |
| Acer          | Aspire A317-51K             | [b02c6dccc2](https://linux-hardware.org/?probe=b02c6dccc2) | Dec 17, 2022 |
| HP            | EliteBook Folio 1040 G3     | [278cdcd567](https://linux-hardware.org/?probe=278cdcd567) | Dec 17, 2022 |
| Toshiba       | Satellite C50D-A-12M        | [fa522940dd](https://linux-hardware.org/?probe=fa522940dd) | Dec 17, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [1e2531fdf1](https://linux-hardware.org/?probe=1e2531fdf1) | Dec 17, 2022 |
| Notebook      | W65_67SZ                    | [770c00f7d9](https://linux-hardware.org/?probe=770c00f7d9) | Dec 17, 2022 |
| HP            | Notebook                    | [844d855f78](https://linux-hardware.org/?probe=844d855f78) | Dec 17, 2022 |
| HP            | EliteBook 840 G4            | [25b640f2ed](https://linux-hardware.org/?probe=25b640f2ed) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [db670caadd](https://linux-hardware.org/?probe=db670caadd) | Dec 16, 2022 |
| Dell          | XPS 13 9380                 | [719f489e01](https://linux-hardware.org/?probe=719f489e01) | Dec 15, 2022 |
| Fujitsu       | LIFEBOOK E734               | [ff5206e8e0](https://linux-hardware.org/?probe=ff5206e8e0) | Dec 15, 2022 |
| Dell          | Latitude E6430              | [1da4bd3e02](https://linux-hardware.org/?probe=1da4bd3e02) | Dec 15, 2022 |
| HP            | Presario CQ62               | [fce21eae2c](https://linux-hardware.org/?probe=fce21eae2c) | Dec 15, 2022 |
| Samsung       | RV410/RV510/S3510/E3510     | [31bf14c8d8](https://linux-hardware.org/?probe=31bf14c8d8) | Dec 15, 2022 |
| Toshiba       | Satellite Pro L300          | [6db5b50a6b](https://linux-hardware.org/?probe=6db5b50a6b) | Dec 14, 2022 |
| Apple         | MacBookPro5,4               | [902c809015](https://linux-hardware.org/?probe=902c809015) | Dec 14, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [db7a82e46c](https://linux-hardware.org/?probe=db7a82e46c) | Dec 14, 2022 |
| Toshiba       | PORTEGE R830                | [0d5af64ca4](https://linux-hardware.org/?probe=0d5af64ca4) | Dec 14, 2022 |
| Dell          | Latitude E7450              | [196b96ea5e](https://linux-hardware.org/?probe=196b96ea5e) | Dec 14, 2022 |
| ASUSTek       | X705UAP                     | [8080afc7d4](https://linux-hardware.org/?probe=8080afc7d4) | Dec 13, 2022 |
| Acer          | Nitro AN517-54              | [3896296ad1](https://linux-hardware.org/?probe=3896296ad1) | Dec 12, 2022 |
| Acer          | Aspire A515-56              | [5437de2b1b](https://linux-hardware.org/?probe=5437de2b1b) | Dec 12, 2022 |
| HP            | ProBook 6570b               | [a6b67497a1](https://linux-hardware.org/?probe=a6b67497a1) | Dec 12, 2022 |
| Dell          | XPS 13 9380                 | [665b87269c](https://linux-hardware.org/?probe=665b87269c) | Dec 12, 2022 |
| ASUSTek       | ROG Strix G713RM_G713RM     | [48e21506f4](https://linux-hardware.org/?probe=48e21506f4) | Dec 11, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | [257e692fa4](https://linux-hardware.org/?probe=257e692fa4) | Dec 11, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [f803c32eae](https://linux-hardware.org/?probe=f803c32eae) | Dec 11, 2022 |
| ASUSTek       | X75VD                       | [5cdd66c849](https://linux-hardware.org/?probe=5cdd66c849) | Dec 11, 2022 |
| Lenovo        | IdeaPad 320-17AST 80XW      | [474f4f4c43](https://linux-hardware.org/?probe=474f4f4c43) | Dec 11, 2022 |
| ASUSTek       | X75VD                       | [624ea43f9d](https://linux-hardware.org/?probe=624ea43f9d) | Dec 11, 2022 |
| Dell          | Latitude E7240              | [591f0ad589](https://linux-hardware.org/?probe=591f0ad589) | Dec 11, 2022 |
| ASUSTek       | X751SA                      | [2da53106a0](https://linux-hardware.org/?probe=2da53106a0) | Dec 11, 2022 |
| Alienware     | m17 R2                      | [76a2c6b1ca](https://linux-hardware.org/?probe=76a2c6b1ca) | Dec 11, 2022 |
| ASUSTek       | X751SA                      | [36b3666998](https://linux-hardware.org/?probe=36b3666998) | Dec 10, 2022 |
| Dell          | Latitude E7240              | [e0aca47e1b](https://linux-hardware.org/?probe=e0aca47e1b) | Dec 10, 2022 |
| Acer          | Aspire E5-573G              | [ec1e8e146a](https://linux-hardware.org/?probe=ec1e8e146a) | Dec 10, 2022 |
| HP            | EliteBook 840 G1            | [350102190e](https://linux-hardware.org/?probe=350102190e) | Dec 10, 2022 |
| HP            | EliteBook 840 G1            | [688e981eee](https://linux-hardware.org/?probe=688e981eee) | Dec 10, 2022 |
| Dell          | Precision 5550              | [ad172b99ad](https://linux-hardware.org/?probe=ad172b99ad) | Dec 10, 2022 |
| Dell          | XPS 17 9700                 | [0426545e91](https://linux-hardware.org/?probe=0426545e91) | Dec 10, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [26e2759694](https://linux-hardware.org/?probe=26e2759694) | Dec 10, 2022 |
| Valve         | Jupiter                     | [1e314d59ee](https://linux-hardware.org/?probe=1e314d59ee) | Dec 09, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [91b65d2fa1](https://linux-hardware.org/?probe=91b65d2fa1) | Dec 09, 2022 |
| MSI           | GS73VR 7RF                  | [31aa44b519](https://linux-hardware.org/?probe=31aa44b519) | Dec 09, 2022 |
| Toshiba       | Satellite L500              | [3258bb06ef](https://linux-hardware.org/?probe=3258bb06ef) | Dec 08, 2022 |
| HP            | Pavilion Notebook           | [8cc721f649](https://linux-hardware.org/?probe=8cc721f649) | Dec 08, 2022 |
| Dell          | Precision 7720              | [5e8014cc1b](https://linux-hardware.org/?probe=5e8014cc1b) | Dec 08, 2022 |
| HP            | x360 310 G1 PC              | [297806eac9](https://linux-hardware.org/?probe=297806eac9) | Dec 08, 2022 |
| Lenovo        | ThinkPad T420 4236PZ0       | [603c3b47a9](https://linux-hardware.org/?probe=603c3b47a9) | Dec 08, 2022 |
| ASUSTek       | K55VD                       | [469f0a1d1f](https://linux-hardware.org/?probe=469f0a1d1f) | Dec 07, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | [bf8647ecdc](https://linux-hardware.org/?probe=bf8647ecdc) | Dec 07, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | [dfc7911df2](https://linux-hardware.org/?probe=dfc7911df2) | Dec 07, 2022 |
| HP            | ZBook 15 G6                 | [57a9a5fbf8](https://linux-hardware.org/?probe=57a9a5fbf8) | Dec 07, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [82d49749a2](https://linux-hardware.org/?probe=82d49749a2) | Dec 07, 2022 |
| Dell          | Latitude E6410              | [0c768fd820](https://linux-hardware.org/?probe=0c768fd820) | Dec 07, 2022 |
| BESSTAR Te... | U820                        | [ea466e46b1](https://linux-hardware.org/?probe=ea466e46b1) | Dec 07, 2022 |
| HP            | Compaq 6910p                | [10b301f77e](https://linux-hardware.org/?probe=10b301f77e) | Dec 07, 2022 |
| Dell          | Inspiron 7720               | [180d05d4c1](https://linux-hardware.org/?probe=180d05d4c1) | Dec 06, 2022 |
| Acer          | Aspire E5-772               | [35c8c05d6c](https://linux-hardware.org/?probe=35c8c05d6c) | Dec 06, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | [ebf5cc9d6e](https://linux-hardware.org/?probe=ebf5cc9d6e) | Dec 06, 2022 |
| HP            | ZBook Firefly 14 inch G8... | [fccbb1fcec](https://linux-hardware.org/?probe=fccbb1fcec) | Dec 06, 2022 |
| HP            | EliteBook 2570p             | [fc7d866c16](https://linux-hardware.org/?probe=fc7d866c16) | Dec 06, 2022 |
| Lenovo        | ThinkPad L14 Gen 2a 20X6... | [1f1c509e41](https://linux-hardware.org/?probe=1f1c509e41) | Dec 06, 2022 |
| Lenovo        | ThinkPad T450s 20BWS2KM0... | [792c537a38](https://linux-hardware.org/?probe=792c537a38) | Dec 06, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [eaf904a47a](https://linux-hardware.org/?probe=eaf904a47a) | Dec 06, 2022 |
| ASUSTek       | K70IO                       | [193053a6ef](https://linux-hardware.org/?probe=193053a6ef) | Dec 05, 2022 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | [5b72cdbdb8](https://linux-hardware.org/?probe=5b72cdbdb8) | Dec 05, 2022 |
| Apple         | MacBookPro5,4               | [bd98ec1bcb](https://linux-hardware.org/?probe=bd98ec1bcb) | Dec 05, 2022 |
| Dell          | Inspiron 5502               | [311215d00b](https://linux-hardware.org/?probe=311215d00b) | Dec 05, 2022 |
| Lenovo        | Yoga Slim 9 14ITL5 82D1     | [f90956a720](https://linux-hardware.org/?probe=f90956a720) | Dec 05, 2022 |
| eMachines     | E520 V1.06                  | [0ef424fa9b](https://linux-hardware.org/?probe=0ef424fa9b) | Dec 05, 2022 |
| Dell          | G3 3500                     | [5b23644904](https://linux-hardware.org/?probe=5b23644904) | Dec 05, 2022 |
| Lenovo        | ThinkPad P51 20HJS16Q0K     | [3dfd18754f](https://linux-hardware.org/?probe=3dfd18754f) | Dec 05, 2022 |
| HUAWEI        | BOD-WXX9                    | [3027fc2c2f](https://linux-hardware.org/?probe=3027fc2c2f) | Dec 05, 2022 |
| HUAWEI        | BOD-WXX9                    | [a07d55ca40](https://linux-hardware.org/?probe=a07d55ca40) | Dec 05, 2022 |
| HUAWEI        | CREM-WXX9                   | [535444f416](https://linux-hardware.org/?probe=535444f416) | Dec 05, 2022 |
| HP            | x360 310 G1 PC              | [b15b39727b](https://linux-hardware.org/?probe=b15b39727b) | Dec 04, 2022 |
| Sony          | VPCEL2S1E                   | [0c98b9d570](https://linux-hardware.org/?probe=0c98b9d570) | Dec 04, 2022 |
| HUAWEI        | KLVL-WXX9                   | [7687bdc111](https://linux-hardware.org/?probe=7687bdc111) | Dec 04, 2022 |
| Acer          | Aspire VN7-572G             | [2147d11bad](https://linux-hardware.org/?probe=2147d11bad) | Dec 04, 2022 |
| Acer          | Aspire VN7-572G             | [5a456d1825](https://linux-hardware.org/?probe=5a456d1825) | Dec 04, 2022 |
| ASUSTek       | K53SD                       | [dbaf532969](https://linux-hardware.org/?probe=dbaf532969) | Dec 04, 2022 |
| Dell          | Latitude E5510              | [6027856ab6](https://linux-hardware.org/?probe=6027856ab6) | Dec 03, 2022 |
| HP            | Laptop 15s-fr2xxx           | [623e794238](https://linux-hardware.org/?probe=623e794238) | Dec 03, 2022 |
| Lenovo        | ThinkPad T440p 20AWS17N0... | [716a6802ca](https://linux-hardware.org/?probe=716a6802ca) | Dec 03, 2022 |
| Fujitsu       | CELSIUS H720                | [a7eacb37c5](https://linux-hardware.org/?probe=a7eacb37c5) | Dec 03, 2022 |
| ASUSTek       | K70IO                       | [179ce76921](https://linux-hardware.org/?probe=179ce76921) | Dec 02, 2022 |
| HP            | Stream Notebook             | [dc16cc5c95](https://linux-hardware.org/?probe=dc16cc5c95) | Dec 02, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [78f2f440eb](https://linux-hardware.org/?probe=78f2f440eb) | Dec 02, 2022 |
| Valve         | Jupiter                     | [f54147a5ba](https://linux-hardware.org/?probe=f54147a5ba) | Dec 02, 2022 |
| HP            | EliteBook 865 16 inch G9... | [33b77409e5](https://linux-hardware.org/?probe=33b77409e5) | Dec 02, 2022 |
| HP            | Notebook                    | [c42eef153d](https://linux-hardware.org/?probe=c42eef153d) | Dec 02, 2022 |
| Dell          | Inspiron 16 5625            | [6e1523c2e8](https://linux-hardware.org/?probe=6e1523c2e8) | Dec 02, 2022 |
| Valve         | Jupiter                     | [4f32d4f1c2](https://linux-hardware.org/?probe=4f32d4f1c2) | Dec 02, 2022 |
| HP            | ProBook 6570b               | [be8f757095](https://linux-hardware.org/?probe=be8f757095) | Dec 02, 2022 |
| HP            | ProBook 6570b               | [1e40d6a94b](https://linux-hardware.org/?probe=1e40d6a94b) | Dec 02, 2022 |
| ASUSTek       | ROG Strix G731GU_G731GU     | [38ce706249](https://linux-hardware.org/?probe=38ce706249) | Dec 02, 2022 |
| ASUSTek       | ROG Strix G731GU_G731GU     | [546f2b82c9](https://linux-hardware.org/?probe=546f2b82c9) | Dec 02, 2022 |
| ASUSTek       | ROG Strix G731GU_G731GU     | [000d536e95](https://linux-hardware.org/?probe=000d536e95) | Dec 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [c19e5b9f4b](https://linux-hardware.org/?probe=c19e5b9f4b) | Dec 02, 2022 |
| HP            | 250 G8 Notebook PC          | [ed3886b135](https://linux-hardware.org/?probe=ed3886b135) | Dec 02, 2022 |
| Lenovo        | ThinkPad T61 6463WAP        | [e11baa0e49](https://linux-hardware.org/?probe=e11baa0e49) | Dec 02, 2022 |
| AZW           | SEi                         | [3cd2f7f657](https://linux-hardware.org/?probe=3cd2f7f657) | Dec 01, 2022 |
| Samsung       | R540/R538/SA41/E452         | [afad3c8828](https://linux-hardware.org/?probe=afad3c8828) | Dec 01, 2022 |
| HP            | 250 G7 Notebook PC          | [1002df8858](https://linux-hardware.org/?probe=1002df8858) | Dec 01, 2022 |
| Samsung       | 930XED                      | [38584fa129](https://linux-hardware.org/?probe=38584fa129) | Dec 01, 2022 |
| Dell          | Precision 5540              | [030dbd45f0](https://linux-hardware.org/?probe=030dbd45f0) | Dec 01, 2022 |
| ASUSTek       | S551LN                      | [b21b106fdf](https://linux-hardware.org/?probe=b21b106fdf) | Dec 01, 2022 |
| HP            | EliteBook 840 G3            | [e17d8c1694](https://linux-hardware.org/?probe=e17d8c1694) | Nov 30, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [183243daeb](https://linux-hardware.org/?probe=183243daeb) | Nov 30, 2022 |
| Packard Be... | EasyNote TE69CXP            | [919275eb73](https://linux-hardware.org/?probe=919275eb73) | Nov 30, 2022 |
| HP            | ZBook 15v G5                | [aabc35ae2a](https://linux-hardware.org/?probe=aabc35ae2a) | Nov 30, 2022 |
| ASUSTek       | E403SA                      | [d3a1f181d5](https://linux-hardware.org/?probe=d3a1f181d5) | Nov 30, 2022 |
| Lenovo        | G70-80 80FF                 | [022ce8e2c8](https://linux-hardware.org/?probe=022ce8e2c8) | Nov 29, 2022 |
| HP            | Pavilion 17                 | [431ce9bd18](https://linux-hardware.org/?probe=431ce9bd18) | Nov 29, 2022 |
| Dell          | Latitude E6410              | [d7abefea4b](https://linux-hardware.org/?probe=d7abefea4b) | Nov 29, 2022 |
| Dell          | Latitude E6410              | [bac3e8c250](https://linux-hardware.org/?probe=bac3e8c250) | Nov 29, 2022 |
| Dell          | Latitude 5330               | [b8d907f2e8](https://linux-hardware.org/?probe=b8d907f2e8) | Nov 29, 2022 |
| MSI           | GT60                        | [07557bed1b](https://linux-hardware.org/?probe=07557bed1b) | Nov 29, 2022 |
| Dell          | Inspiron 16 5625            | [50912d5fa9](https://linux-hardware.org/?probe=50912d5fa9) | Nov 29, 2022 |
| HUAWEI        | NBD-WXX9                    | [e9932df850](https://linux-hardware.org/?probe=e9932df850) | Nov 29, 2022 |
| HUAWEI        | NBD-WXX9                    | [179ff76e75](https://linux-hardware.org/?probe=179ff76e75) | Nov 29, 2022 |
| Dell          | Latitude 7490               | [8934413cf0](https://linux-hardware.org/?probe=8934413cf0) | Nov 29, 2022 |
| Dell          | System Vostro 3750          | [ed88e2ae0c](https://linux-hardware.org/?probe=ed88e2ae0c) | Nov 29, 2022 |
| Thomson       | N17V3C8WH512                | [b89cd0328a](https://linux-hardware.org/?probe=b89cd0328a) | Nov 29, 2022 |
| Razer         | Blade Stealth               | [e182c3c739](https://linux-hardware.org/?probe=e182c3c739) | Nov 29, 2022 |
| ASUSTek       | K70IO                       | [f91b4cdb61](https://linux-hardware.org/?probe=f91b4cdb61) | Nov 29, 2022 |
| HP            | EliteBook 8460p             | [ffe997080f](https://linux-hardware.org/?probe=ffe997080f) | Nov 28, 2022 |
| Lenovo        | G50-80 80E5                 | [1387bf11ea](https://linux-hardware.org/?probe=1387bf11ea) | Nov 28, 2022 |
| Dell          | Inspiron 16 5625            | [22da2f8729](https://linux-hardware.org/?probe=22da2f8729) | Nov 28, 2022 |
| ASUSTek       | X756UVK                     | [4745940cf9](https://linux-hardware.org/?probe=4745940cf9) | Nov 28, 2022 |
| ASUSTek       | K70IO                       | [4eabf9a0d4](https://linux-hardware.org/?probe=4eabf9a0d4) | Nov 28, 2022 |
| Lenovo        | ThinkPad T450 20BUS03J00    | [8423f90db0](https://linux-hardware.org/?probe=8423f90db0) | Nov 27, 2022 |
| Dell          | Latitude E6230              | [f3536b80de](https://linux-hardware.org/?probe=f3536b80de) | Nov 27, 2022 |
| Dell          | Latitude E6230              | [dbaae2beb7](https://linux-hardware.org/?probe=dbaae2beb7) | Nov 27, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [2d1a576ee6](https://linux-hardware.org/?probe=2d1a576ee6) | Nov 27, 2022 |
| HP            | Compaq Presario CQ60        | [1f521f98cb](https://linux-hardware.org/?probe=1f521f98cb) | Nov 27, 2022 |
| Dell          | Studio 1558                 | [bc76adb105](https://linux-hardware.org/?probe=bc76adb105) | Nov 27, 2022 |
| Dell          | Studio 1558                 | [43438ab851](https://linux-hardware.org/?probe=43438ab851) | Nov 27, 2022 |
| Jumper        | EZbook                      | [a93aa75e5f](https://linux-hardware.org/?probe=a93aa75e5f) | Nov 27, 2022 |
| Panasonic     | CF-19AHN3BFF                | [a5989143a8](https://linux-hardware.org/?probe=a5989143a8) | Nov 26, 2022 |
| ASUSTek       | 1002HA                      | [15d5eb998d](https://linux-hardware.org/?probe=15d5eb998d) | Nov 26, 2022 |
| Dell          | Latitude 7310               | [46ed677d40](https://linux-hardware.org/?probe=46ed677d40) | Nov 26, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | [694d1d5e96](https://linux-hardware.org/?probe=694d1d5e96) | Nov 26, 2022 |
| MSI           | GL62M 7RDX                  | [1aa67b30d4](https://linux-hardware.org/?probe=1aa67b30d4) | Nov 26, 2022 |
| Dell          | Inspiron MP061              | [d70d7496df](https://linux-hardware.org/?probe=d70d7496df) | Nov 26, 2022 |
| Dell          | Latitude E7240              | [634ebb2a88](https://linux-hardware.org/?probe=634ebb2a88) | Nov 25, 2022 |
| HP            | Pavilion 15                 | [b294971fc6](https://linux-hardware.org/?probe=b294971fc6) | Nov 25, 2022 |
| ASUSTek       | X555YI                      | [2626d57c13](https://linux-hardware.org/?probe=2626d57c13) | Nov 25, 2022 |
| Dell          | Latitude 7310               | [0f9c2a5623](https://linux-hardware.org/?probe=0f9c2a5623) | Nov 25, 2022 |
| Panasonic     | CF-19AHN3BFF                | [bfd184ea5c](https://linux-hardware.org/?probe=bfd184ea5c) | Nov 25, 2022 |
| HP            | ProBook 640 G8 Notebook ... | [ce586530e4](https://linux-hardware.org/?probe=ce586530e4) | Nov 24, 2022 |
| Dell          | Latitude 7310               | [d7448aaff8](https://linux-hardware.org/?probe=d7448aaff8) | Nov 24, 2022 |
| Acer          | Aspire ES1-523              | [333d3583b1](https://linux-hardware.org/?probe=333d3583b1) | Nov 24, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | [4b6212908f](https://linux-hardware.org/?probe=4b6212908f) | Nov 24, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | [69c89370b7](https://linux-hardware.org/?probe=69c89370b7) | Nov 24, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [a4512e8a71](https://linux-hardware.org/?probe=a4512e8a71) | Nov 24, 2022 |
| Dell          | Latitude E6500              | [73d607f9e1](https://linux-hardware.org/?probe=73d607f9e1) | Nov 24, 2022 |
| Dell          | Latitude 7310               | [836fbd119c](https://linux-hardware.org/?probe=836fbd119c) | Nov 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [9e1f0c4898](https://linux-hardware.org/?probe=9e1f0c4898) | Nov 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [ef378a135b](https://linux-hardware.org/?probe=ef378a135b) | Nov 24, 2022 |
| Acer          | Aspire A315-54K             | [12f19e4fbe](https://linux-hardware.org/?probe=12f19e4fbe) | Nov 23, 2022 |
| ASUSTek       | K70IJ                       | [8df764e624](https://linux-hardware.org/?probe=8df764e624) | Nov 23, 2022 |
| MSI           | Modern 14 C12M              | [51088606f5](https://linux-hardware.org/?probe=51088606f5) | Nov 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [f1d8974d71](https://linux-hardware.org/?probe=f1d8974d71) | Nov 23, 2022 |
| Unknown       | Unknown                     | [c119fbb804](https://linux-hardware.org/?probe=c119fbb804) | Nov 22, 2022 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [96205eb8d4](https://linux-hardware.org/?probe=96205eb8d4) | Nov 22, 2022 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [97571585cd](https://linux-hardware.org/?probe=97571585cd) | Nov 22, 2022 |
| Acer          | Aspire A515-57              | [4692ce22fb](https://linux-hardware.org/?probe=4692ce22fb) | Nov 22, 2022 |
| Acer          | Aspire A515-57              | [cb82f6d418](https://linux-hardware.org/?probe=cb82f6d418) | Nov 22, 2022 |
| HP            | ENVY dv6                    | [0d28d09c70](https://linux-hardware.org/?probe=0d28d09c70) | Nov 22, 2022 |
| Dell          | Latitude E6520              | [1801edca03](https://linux-hardware.org/?probe=1801edca03) | Nov 22, 2022 |
| HP            | ProBook 450 G1              | [c8d71bb807](https://linux-hardware.org/?probe=c8d71bb807) | Nov 22, 2022 |
| Timi          | TM1612                      | [abd08d53c7](https://linux-hardware.org/?probe=abd08d53c7) | Nov 22, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [54d3eed278](https://linux-hardware.org/?probe=54d3eed278) | Nov 21, 2022 |
| Dell          | Precision 5510              | [63c0b8aa0c](https://linux-hardware.org/?probe=63c0b8aa0c) | Nov 21, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [c3048ea26d](https://linux-hardware.org/?probe=c3048ea26d) | Nov 21, 2022 |
| HP            | Pavilion Notebook           | [9599fd68a9](https://linux-hardware.org/?probe=9599fd68a9) | Nov 21, 2022 |
| Unknown       | Unknown                     | [5a06cde126](https://linux-hardware.org/?probe=5a06cde126) | Nov 20, 2022 |
| Acer          | Aspire ES1-711G             | [8852f94b38](https://linux-hardware.org/?probe=8852f94b38) | Nov 20, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [eb43c3d5c0](https://linux-hardware.org/?probe=eb43c3d5c0) | Nov 20, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [6a51b20cd4](https://linux-hardware.org/?probe=6a51b20cd4) | Nov 19, 2022 |
| HP            | EliteBook 840 G2            | [6c896ef17e](https://linux-hardware.org/?probe=6c896ef17e) | Nov 19, 2022 |
| HP            | Pavilion g7                 | [fae1d08109](https://linux-hardware.org/?probe=fae1d08109) | Nov 19, 2022 |
| Google        | Rammus                      | [23ed7badd5](https://linux-hardware.org/?probe=23ed7badd5) | Nov 19, 2022 |
| Dell          | Latitude 7410               | [ce222880fe](https://linux-hardware.org/?probe=ce222880fe) | Nov 18, 2022 |
| HP            | EliteBook 840 G3            | [a5151a0db4](https://linux-hardware.org/?probe=a5151a0db4) | Nov 18, 2022 |
| Dell          | Latitude 7300               | [5ff7502b3e](https://linux-hardware.org/?probe=5ff7502b3e) | Nov 18, 2022 |
| Dell          | Latitude 7310               | [525543a3dc](https://linux-hardware.org/?probe=525543a3dc) | Nov 18, 2022 |
| Dell          | Latitude 7300               | [5c7f8f6d8c](https://linux-hardware.org/?probe=5c7f8f6d8c) | Nov 18, 2022 |
| HP            | Pavilion 17                 | [ab34ec642d](https://linux-hardware.org/?probe=ab34ec642d) | Nov 18, 2022 |
| Dynabook      | TECRA A50-J                 | [c0ae8746e0](https://linux-hardware.org/?probe=c0ae8746e0) | Nov 18, 2022 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [94bd888b25](https://linux-hardware.org/?probe=94bd888b25) | Nov 18, 2022 |
| Acer          | Aspire S5-371               | [6274604555](https://linux-hardware.org/?probe=6274604555) | Nov 18, 2022 |
| Acer          | Swift SF314-42              | [12e2119f1c](https://linux-hardware.org/?probe=12e2119f1c) | Nov 18, 2022 |
| Dell          | Latitude 5520               | [72bcc12409](https://linux-hardware.org/?probe=72bcc12409) | Nov 18, 2022 |
| Dell          | Latitude 5490               | [70b8fb5e89](https://linux-hardware.org/?probe=70b8fb5e89) | Nov 18, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [88336d65e7](https://linux-hardware.org/?probe=88336d65e7) | Nov 17, 2022 |
| Dynabook E... | PORTABLECD2021              | [17a064a3c3](https://linux-hardware.org/?probe=17a064a3c3) | Nov 17, 2022 |
| MSI           | Prestige 14 A12SC           | [008c444627](https://linux-hardware.org/?probe=008c444627) | Nov 17, 2022 |
| HP            | EliteBook 840 G3            | [cd753ace10](https://linux-hardware.org/?probe=cd753ace10) | Nov 17, 2022 |
| Apple         | MacBookAir7,2               | [6901439af7](https://linux-hardware.org/?probe=6901439af7) | Nov 17, 2022 |
| HP            | 245 G8 Notebook PC          | [4d4f9a0e10](https://linux-hardware.org/?probe=4d4f9a0e10) | Nov 17, 2022 |
| Dell          | Latitude 7300               | [462f090e8c](https://linux-hardware.org/?probe=462f090e8c) | Nov 17, 2022 |
| Dell          | Latitude 7380               | [c34f569e5a](https://linux-hardware.org/?probe=c34f569e5a) | Nov 17, 2022 |
| Dell          | Latitude 7380               | [ff8bc9f174](https://linux-hardware.org/?probe=ff8bc9f174) | Nov 17, 2022 |
| HP            | ZBook 14 G2                 | [c084bd4b99](https://linux-hardware.org/?probe=c084bd4b99) | Nov 17, 2022 |
| HP            | ZBook 14 G2                 | [e687234452](https://linux-hardware.org/?probe=e687234452) | Nov 17, 2022 |
| Dynabook E... | PORTABLECD2021              | [5d138b93b6](https://linux-hardware.org/?probe=5d138b93b6) | Nov 16, 2022 |
| Dell          | Inspiron 13 5310            | [3c9865d86e](https://linux-hardware.org/?probe=3c9865d86e) | Nov 16, 2022 |
| MSI           | Katana GF76 11UC            | [24ba2f8b12](https://linux-hardware.org/?probe=24ba2f8b12) | Nov 16, 2022 |
| ASUSTek       | T100TA                      | [3d49b98878](https://linux-hardware.org/?probe=3d49b98878) | Nov 16, 2022 |
| HUAWEI        | HLYL-WXX9                   | [f863546b0f](https://linux-hardware.org/?probe=f863546b0f) | Nov 16, 2022 |
| Google        | Rammus                      | [ef0f440314](https://linux-hardware.org/?probe=ef0f440314) | Nov 16, 2022 |
| AMI           | Intel                       | [36327e3aca](https://linux-hardware.org/?probe=36327e3aca) | Nov 16, 2022 |
| HP            | Notebook                    | [d40f2df5a8](https://linux-hardware.org/?probe=d40f2df5a8) | Nov 16, 2022 |
| HP            | 250 G6 Notebook PC          | [439fe62e2e](https://linux-hardware.org/?probe=439fe62e2e) | Nov 15, 2022 |
| LDLC          | SPC-N                       | [acec489419](https://linux-hardware.org/?probe=acec489419) | Nov 15, 2022 |
| HP            | Pavilion 17                 | [de4e2c6446](https://linux-hardware.org/?probe=de4e2c6446) | Nov 15, 2022 |
| Acer          | Aspire E5-722               | [7e26ae7fe8](https://linux-hardware.org/?probe=7e26ae7fe8) | Nov 14, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [298f1bd357](https://linux-hardware.org/?probe=298f1bd357) | Nov 14, 2022 |
| Lenovo        | IdeaPad 320-17AST 80XW      | [d8e3815f50](https://linux-hardware.org/?probe=d8e3815f50) | Nov 14, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [f532c6bdb1](https://linux-hardware.org/?probe=f532c6bdb1) | Nov 13, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [2dddaa52cd](https://linux-hardware.org/?probe=2dddaa52cd) | Nov 13, 2022 |
| Dell          | Vostro 3578                 | [1fa1c16736](https://linux-hardware.org/?probe=1fa1c16736) | Nov 13, 2022 |
| UNOWHY        | Y13G012S4EI                 | [9a214b41ec](https://linux-hardware.org/?probe=9a214b41ec) | Nov 13, 2022 |
| Alienware     | M17xR4                      | [9dbd88c02e](https://linux-hardware.org/?probe=9dbd88c02e) | Nov 13, 2022 |
| UNOWHY        | Y13G012S4EI                 | [51a7b4fca7](https://linux-hardware.org/?probe=51a7b4fca7) | Nov 12, 2022 |
| Lenovo        | Yoga 2 13 20344             | [deb10be02b](https://linux-hardware.org/?probe=deb10be02b) | Nov 12, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [904b7c0e89](https://linux-hardware.org/?probe=904b7c0e89) | Nov 12, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [0e3e3c885a](https://linux-hardware.org/?probe=0e3e3c885a) | Nov 11, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [2421b6c5a4](https://linux-hardware.org/?probe=2421b6c5a4) | Nov 11, 2022 |
| Dell          | Inspiron 3543               | [227f62cdb9](https://linux-hardware.org/?probe=227f62cdb9) | Nov 11, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [332cc61ddc](https://linux-hardware.org/?probe=332cc61ddc) | Nov 11, 2022 |
| SHENZHEN Y... | A8S PRO                     | [354471ab24](https://linux-hardware.org/?probe=354471ab24) | Nov 10, 2022 |
| Lenovo        | ThinkPad T460 20FMS06V00    | [1fa4637d27](https://linux-hardware.org/?probe=1fa4637d27) | Nov 10, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [b9f262d40b](https://linux-hardware.org/?probe=b9f262d40b) | Nov 10, 2022 |
| ASUSTek       | ROG Strix G531GV_G531GV     | [cd4796484a](https://linux-hardware.org/?probe=cd4796484a) | Nov 10, 2022 |
| HP            | EliteBook 840 G5            | [e281a0277b](https://linux-hardware.org/?probe=e281a0277b) | Nov 10, 2022 |
| MSI           | GS75 Stealth 10SE           | [a13f6196b6](https://linux-hardware.org/?probe=a13f6196b6) | Nov 10, 2022 |
| MSI           | GS75 Stealth 10SE           | [eaed1093a4](https://linux-hardware.org/?probe=eaed1093a4) | Nov 10, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [e77f7ce44e](https://linux-hardware.org/?probe=e77f7ce44e) | Nov 09, 2022 |
| Gigabyte      | Sabre 15                    | [1edede0895](https://linux-hardware.org/?probe=1edede0895) | Nov 09, 2022 |
| SHENZHEN Y... | A8S PRO                     | [e6b195843f](https://linux-hardware.org/?probe=e6b195843f) | Nov 09, 2022 |
| Dell          | Precision 5540              | [2d459a448d](https://linux-hardware.org/?probe=2d459a448d) | Nov 09, 2022 |
| Dell          | Latitude 5420               | [2eba4932bf](https://linux-hardware.org/?probe=2eba4932bf) | Nov 09, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [97ed2f1140](https://linux-hardware.org/?probe=97ed2f1140) | Nov 09, 2022 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | [0a1efcf166](https://linux-hardware.org/?probe=0a1efcf166) | Nov 08, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [1cca3aa247](https://linux-hardware.org/?probe=1cca3aa247) | Nov 08, 2022 |
| ASUSTek       | VivoBook E14 E402WAS        | [9fe97ad66f](https://linux-hardware.org/?probe=9fe97ad66f) | Nov 08, 2022 |
| HP            | Laptop 14s-dq2xxx           | [6c277d54f9](https://linux-hardware.org/?probe=6c277d54f9) | Nov 07, 2022 |
| ASUSTek       | K55VD                       | [d8a78ad824](https://linux-hardware.org/?probe=d8a78ad824) | Nov 07, 2022 |
| TUXEDO        | Pulse 15 Gen2               | [f0c2157642](https://linux-hardware.org/?probe=f0c2157642) | Nov 07, 2022 |
| Thomson       | N17V3C8WH512                | [f13487a2f3](https://linux-hardware.org/?probe=f13487a2f3) | Nov 07, 2022 |
| HP            | EliteBook 8470p             | [e94c6ad334](https://linux-hardware.org/?probe=e94c6ad334) | Nov 07, 2022 |
| HP            | Laptop 14s-dq2xxx           | [29fd694ada](https://linux-hardware.org/?probe=29fd694ada) | Nov 07, 2022 |
| Dell          | G3 3500                     | [d3ae8a9d72](https://linux-hardware.org/?probe=d3ae8a9d72) | Nov 07, 2022 |
| Acer          | Nitro AN515-52              | [cbfa344eaa](https://linux-hardware.org/?probe=cbfa344eaa) | Nov 07, 2022 |
| Dell          | Latitude E5540              | [f2420e40cd](https://linux-hardware.org/?probe=f2420e40cd) | Nov 06, 2022 |
| Dell          | Latitude E5540              | [2456786404](https://linux-hardware.org/?probe=2456786404) | Nov 06, 2022 |
| Lenovo        | IdeaPad 320-17AST 80XW      | [08c701b06d](https://linux-hardware.org/?probe=08c701b06d) | Nov 06, 2022 |
| Dell          | Latitude E7470              | [1bd39e96d2](https://linux-hardware.org/?probe=1bd39e96d2) | Nov 06, 2022 |
| HP            | Unknown                     | [fe07901ad1](https://linux-hardware.org/?probe=fe07901ad1) | Nov 06, 2022 |
| HP            | Unknown                     | [495b046a6b](https://linux-hardware.org/?probe=495b046a6b) | Nov 06, 2022 |
| Timi          | Xiaomi Book Pro 16 2022     | [d1bcd9dd18](https://linux-hardware.org/?probe=d1bcd9dd18) | Nov 06, 2022 |
| Timi          | Xiaomi Book Pro 16 2022     | [2c0e88be3e](https://linux-hardware.org/?probe=2c0e88be3e) | Nov 06, 2022 |
| Thomson       | N17V3C8WH512                | [58d6a21b17](https://linux-hardware.org/?probe=58d6a21b17) | Nov 06, 2022 |
| HP            | EliteBook Folio 1040 G1     | [f2d6eec645](https://linux-hardware.org/?probe=f2d6eec645) | Nov 06, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [7e97bace0c](https://linux-hardware.org/?probe=7e97bace0c) | Nov 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E203... | [d793aac21d](https://linux-hardware.org/?probe=d793aac21d) | Nov 06, 2022 |
| Dell          | Latitude E6520              | [9593951427](https://linux-hardware.org/?probe=9593951427) | Nov 06, 2022 |
| Dell          | Latitude E6520              | [53eedbde1f](https://linux-hardware.org/?probe=53eedbde1f) | Nov 06, 2022 |
| Thomson       | NEO14A-4SL128               | [5f6993914c](https://linux-hardware.org/?probe=5f6993914c) | Nov 05, 2022 |
| ASUSTek       | UX303UA                     | [0df719375b](https://linux-hardware.org/?probe=0df719375b) | Nov 05, 2022 |
| ASUSTek       | X756UWK                     | [2d165dd7b0](https://linux-hardware.org/?probe=2d165dd7b0) | Nov 05, 2022 |
| ASUSTek       | UX303UA                     | [751669286c](https://linux-hardware.org/?probe=751669286c) | Nov 05, 2022 |
| ASUSTek       | X756UWK                     | [b89c7882f3](https://linux-hardware.org/?probe=b89c7882f3) | Nov 05, 2022 |
| Lenovo        | ThinkPad E570 20H50078FR    | [156f337a82](https://linux-hardware.org/?probe=156f337a82) | Nov 05, 2022 |
| Lenovo        | ThinkPad X270 20HN0014FR    | [94abd977de](https://linux-hardware.org/?probe=94abd977de) | Nov 04, 2022 |
| ASUSTek       | X556URK                     | [c26a3705d3](https://linux-hardware.org/?probe=c26a3705d3) | Nov 04, 2022 |
| HP            | ProBook 6470b               | [78aa59a89a](https://linux-hardware.org/?probe=78aa59a89a) | Nov 04, 2022 |
| HP            | Laptop 15s-eq1xxx           | [8fdaec6b5a](https://linux-hardware.org/?probe=8fdaec6b5a) | Nov 04, 2022 |
| HUAWEI        | KLVL-WXX9                   | [17bac11f6f](https://linux-hardware.org/?probe=17bac11f6f) | Nov 04, 2022 |
| HP            | 470 G7 Notebook PC          | [ae68dc3b2d](https://linux-hardware.org/?probe=ae68dc3b2d) | Nov 04, 2022 |
| UNOWHY        | Y13G011S4EI                 | [da784a5c82](https://linux-hardware.org/?probe=da784a5c82) | Nov 04, 2022 |
| Notebook      | NL40_50GU                   | [c74ffe668a](https://linux-hardware.org/?probe=c74ffe668a) | Nov 03, 2022 |
| Notebook      | NL40_50GU                   | [b3001401db](https://linux-hardware.org/?probe=b3001401db) | Nov 03, 2022 |
| HP            | ProBook 6470b               | [ea7c42479d](https://linux-hardware.org/?probe=ea7c42479d) | Nov 03, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [7e09b1e9bd](https://linux-hardware.org/?probe=7e09b1e9bd) | Nov 03, 2022 |
| Fujitsu Si... | AMILO Li3710                | [ce4f615c70](https://linux-hardware.org/?probe=ce4f615c70) | Nov 03, 2022 |
| HP            | EliteBook 840 G2            | [a189602082](https://linux-hardware.org/?probe=a189602082) | Nov 03, 2022 |
| Acer          | Swift SF314-57              | [8ab3b70362](https://linux-hardware.org/?probe=8ab3b70362) | Nov 03, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [fe4a007f99](https://linux-hardware.org/?probe=fe4a007f99) | Nov 03, 2022 |
| HP            | EliteBook 8470p             | [d754cc7217](https://linux-hardware.org/?probe=d754cc7217) | Nov 03, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [dfe209bf08](https://linux-hardware.org/?probe=dfe209bf08) | Nov 03, 2022 |
| Dell          | G15 5511                    | [6965880757](https://linux-hardware.org/?probe=6965880757) | Nov 02, 2022 |
| HP            | Laptop 15-db0xxx            | [14184ac3d9](https://linux-hardware.org/?probe=14184ac3d9) | Nov 02, 2022 |
| Toshiba       | Satellite C70D-A            | [7a421ed810](https://linux-hardware.org/?probe=7a421ed810) | Nov 02, 2022 |
| Toshiba       | Satellite C70D-A            | [d82227846b](https://linux-hardware.org/?probe=d82227846b) | Nov 02, 2022 |
| Dell          | G3 3500                     | [c595a16f59](https://linux-hardware.org/?probe=c595a16f59) | Nov 02, 2022 |
| Dell          | Latitude 5420               | [679fbcb14f](https://linux-hardware.org/?probe=679fbcb14f) | Nov 02, 2022 |
| Lenovo        | IdeaPad 320-17AST 80XW      | [9fa0489d64](https://linux-hardware.org/?probe=9fa0489d64) | Nov 01, 2022 |
| Lenovo        | IdeaPad 320-17AST 80XW      | [411a5da53c](https://linux-hardware.org/?probe=411a5da53c) | Nov 01, 2022 |
| Acer          | Swift SF314-42              | [6a0d7d5f39](https://linux-hardware.org/?probe=6a0d7d5f39) | Nov 01, 2022 |
| HP            | Pavilion dv5                | [fb23cec1a6](https://linux-hardware.org/?probe=fb23cec1a6) | Nov 01, 2022 |
| Toshiba       | Satellite C70D-B            | [ccf4e200fb](https://linux-hardware.org/?probe=ccf4e200fb) | Nov 01, 2022 |
| Valve         | Jupiter                     | [cf9998e9b9](https://linux-hardware.org/?probe=cf9998e9b9) | Nov 01, 2022 |
| ASUSTek       | S551LN                      | [67e15a659d](https://linux-hardware.org/?probe=67e15a659d) | Oct 31, 2022 |
| Valve         | Jupiter                     | [9d237f0d30](https://linux-hardware.org/?probe=9d237f0d30) | Oct 31, 2022 |
| Acer          | Swift SF314-54              | [71cf98e6e8](https://linux-hardware.org/?probe=71cf98e6e8) | Oct 31, 2022 |
| HP            | Compaq nc6320 (EV073AV)     | [b73f359ded](https://linux-hardware.org/?probe=b73f359ded) | Oct 31, 2022 |
| Acer          | Extensa 5635Z               | [35ce596e08](https://linux-hardware.org/?probe=35ce596e08) | Oct 31, 2022 |
| Dell          | Latitude E5500              | [c64399793c](https://linux-hardware.org/?probe=c64399793c) | Oct 31, 2022 |
| HP            | Compaq Presario CQ71        | [ea057ea9b9](https://linux-hardware.org/?probe=ea057ea9b9) | Oct 31, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [ce59648f62](https://linux-hardware.org/?probe=ce59648f62) | Oct 31, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [e993af2670](https://linux-hardware.org/?probe=e993af2670) | Oct 31, 2022 |
| Acer          | Aspire E5-573G              | [acfa0d90d6](https://linux-hardware.org/?probe=acfa0d90d6) | Oct 31, 2022 |
| Lenovo        | ThinkPad X270 20HN0014FR    | [d6fc7c48a1](https://linux-hardware.org/?probe=d6fc7c48a1) | Oct 30, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [e8a1f8f6bf](https://linux-hardware.org/?probe=e8a1f8f6bf) | Oct 30, 2022 |
| ASUSTek       | G74Sx                       | [c24c24ab27](https://linux-hardware.org/?probe=c24c24ab27) | Oct 30, 2022 |
| Dell          | XPS L322X                   | [cacebfe41e](https://linux-hardware.org/?probe=cacebfe41e) | Oct 30, 2022 |
| Samsung       | RV410/RV510/S3510/E3510     | [d4552d84d5](https://linux-hardware.org/?probe=d4552d84d5) | Oct 30, 2022 |
| Acer          | Swift SF314-42              | [6873e5b579](https://linux-hardware.org/?probe=6873e5b579) | Oct 30, 2022 |
| Valve         | Jupiter                     | [d4c562a178](https://linux-hardware.org/?probe=d4c562a178) | Oct 30, 2022 |
| Acer          | Swift SF314-42              | [da1b668449](https://linux-hardware.org/?probe=da1b668449) | Oct 30, 2022 |
| ASUSTek       | E200HA                      | [18ca81370b](https://linux-hardware.org/?probe=18ca81370b) | Oct 29, 2022 |
| ASUSTek       | E200HA                      | [0a95698cb6](https://linux-hardware.org/?probe=0a95698cb6) | Oct 29, 2022 |
| HP            | Compaq 615                  | [ae90fa3742](https://linux-hardware.org/?probe=ae90fa3742) | Oct 29, 2022 |
| HP            | OMEN by Laptop              | [610be75cca](https://linux-hardware.org/?probe=610be75cca) | Oct 29, 2022 |
| ASUSTek       | X751NV                      | [9ef2717db0](https://linux-hardware.org/?probe=9ef2717db0) | Oct 29, 2022 |
| IP3 Tech      | AP1                         | [0562a6a46d](https://linux-hardware.org/?probe=0562a6a46d) | Oct 28, 2022 |
| Notebook      | NV4xPZ                      | [86e7370778](https://linux-hardware.org/?probe=86e7370778) | Oct 28, 2022 |
| IP3 Tech      | AP1                         | [2a9c0ff1c5](https://linux-hardware.org/?probe=2a9c0ff1c5) | Oct 28, 2022 |
| Lenovo        | ThinkPad T560 20FHCTO1WW    | [05ff2d32fa](https://linux-hardware.org/?probe=05ff2d32fa) | Oct 28, 2022 |
| Lenovo        | ThinkPad T560 20FHCTO1WW    | [403a99d8b2](https://linux-hardware.org/?probe=403a99d8b2) | Oct 28, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | [0c6a68368c](https://linux-hardware.org/?probe=0c6a68368c) | Oct 27, 2022 |
| ASUSTek       | N501VW                      | [07f7d43f09](https://linux-hardware.org/?probe=07f7d43f09) | Oct 27, 2022 |
| Acer          | Extensa 2509                | [a27b3d38a9](https://linux-hardware.org/?probe=a27b3d38a9) | Oct 27, 2022 |
| Alienware     | m17 R4                      | [14770101cf](https://linux-hardware.org/?probe=14770101cf) | Oct 27, 2022 |
| Acer          | Swift SF314-42              | [8c9d6eb128](https://linux-hardware.org/?probe=8c9d6eb128) | Oct 27, 2022 |
| Dell          | Latitude 5310               | [10b8371dbd](https://linux-hardware.org/?probe=10b8371dbd) | Oct 27, 2022 |
| Acer          | Swift SF314-42              | [6aaeaf667c](https://linux-hardware.org/?probe=6aaeaf667c) | Oct 27, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEP... | [9564d50ef8](https://linux-hardware.org/?probe=9564d50ef8) | Oct 27, 2022 |
| Acer          | Swift SF314-512             | [951c734c1b](https://linux-hardware.org/?probe=951c734c1b) | Oct 27, 2022 |
| Valve         | Jupiter                     | [088235cbff](https://linux-hardware.org/?probe=088235cbff) | Oct 26, 2022 |
| Dell          | Precision 7560              | [c82d6a32a5](https://linux-hardware.org/?probe=c82d6a32a5) | Oct 26, 2022 |
| Dell          | XPS 13 9305                 | [6062baa35c](https://linux-hardware.org/?probe=6062baa35c) | Oct 26, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [34be38a48b](https://linux-hardware.org/?probe=34be38a48b) | Oct 26, 2022 |
| Toshiba       | Satellite C660              | [6b0380ea4c](https://linux-hardware.org/?probe=6b0380ea4c) | Oct 26, 2022 |
| ASUSTek       | GL753VD                     | [08b067d2cf](https://linux-hardware.org/?probe=08b067d2cf) | Oct 25, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [a128f79c0a](https://linux-hardware.org/?probe=a128f79c0a) | Oct 25, 2022 |
| ASUSTek       | VivoBook E14 E402WAS        | [eadb224c05](https://linux-hardware.org/?probe=eadb224c05) | Oct 25, 2022 |
| Dell          | Inspiron 7737               | [727b48a339](https://linux-hardware.org/?probe=727b48a339) | Oct 25, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [8f246bccb1](https://linux-hardware.org/?probe=8f246bccb1) | Oct 25, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [bc5adf7f4b](https://linux-hardware.org/?probe=bc5adf7f4b) | Oct 25, 2022 |
| Valve         | Jupiter                     | [6ed87cbcfb](https://linux-hardware.org/?probe=6ed87cbcfb) | Oct 25, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [ec7f3834d1](https://linux-hardware.org/?probe=ec7f3834d1) | Oct 25, 2022 |
| Toshiba       | Satellite A505              | [41dafcbfb9](https://linux-hardware.org/?probe=41dafcbfb9) | Oct 25, 2022 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [814da05eec](https://linux-hardware.org/?probe=814da05eec) | Oct 25, 2022 |
| Lenovo        | G50-45 80MQ                 | [1c6d041ce2](https://linux-hardware.org/?probe=1c6d041ce2) | Oct 25, 2022 |
| Valve         | Jupiter                     | [fe664e172e](https://linux-hardware.org/?probe=fe664e172e) | Oct 24, 2022 |
| Dell          | Studio 1737                 | [d6e17c05b2](https://linux-hardware.org/?probe=d6e17c05b2) | Oct 24, 2022 |
| Packard Be... | H17HV                       | [2e94cfdd84](https://linux-hardware.org/?probe=2e94cfdd84) | Oct 24, 2022 |
| MSI           | Pulse GL76 12UEK            | [bb06dc4756](https://linux-hardware.org/?probe=bb06dc4756) | Oct 24, 2022 |
| Toshiba       | Satellite C660              | [646b07cc4c](https://linux-hardware.org/?probe=646b07cc4c) | Oct 24, 2022 |
| Packard Be... | EasyNote ENTE70BH           | [2135a5aed7](https://linux-hardware.org/?probe=2135a5aed7) | Oct 23, 2022 |
| Sony          | VGN-SZ3XP_C                 | [72f83141a0](https://linux-hardware.org/?probe=72f83141a0) | Oct 23, 2022 |
| Dell          | Inspiron 5567               | [42280c6145](https://linux-hardware.org/?probe=42280c6145) | Oct 23, 2022 |
| Dell          | Precision 7750              | [dd51bb7ccd](https://linux-hardware.org/?probe=dd51bb7ccd) | Oct 23, 2022 |
| Lenovo        | ThinkPad X240 20AMS01M00    | [2f1c7b7716](https://linux-hardware.org/?probe=2f1c7b7716) | Oct 23, 2022 |
| Dell          | Latitude E6510              | [73cd1082f8](https://linux-hardware.org/?probe=73cd1082f8) | Oct 22, 2022 |
| Dell          | Latitude 5420               | [dd9b95a216](https://linux-hardware.org/?probe=dd9b95a216) | Oct 22, 2022 |
| Acer          | TravelMate P256-M           | [7ca952de68](https://linux-hardware.org/?probe=7ca952de68) | Oct 22, 2022 |
| ASUSTek       | ZenBook UX534FAC_UX534FA    | [928997f65c](https://linux-hardware.org/?probe=928997f65c) | Oct 22, 2022 |
| Dell          | Latitude E6520              | [88af6c857c](https://linux-hardware.org/?probe=88af6c857c) | Oct 22, 2022 |
| Dell          | Latitude E6520              | [246517ceab](https://linux-hardware.org/?probe=246517ceab) | Oct 22, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [57bfd1e0e9](https://linux-hardware.org/?probe=57bfd1e0e9) | Oct 22, 2022 |
| HP            | ProBook 6550b               | [cc300bedc8](https://linux-hardware.org/?probe=cc300bedc8) | Oct 21, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | [a22e54462c](https://linux-hardware.org/?probe=a22e54462c) | Oct 21, 2022 |
| HP            | Stream Notebook             | [685271f268](https://linux-hardware.org/?probe=685271f268) | Oct 21, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [45d7e6a1aa](https://linux-hardware.org/?probe=45d7e6a1aa) | Oct 21, 2022 |
| MAXDATA       | obook2-1                    | [c7e03dae2f](https://linux-hardware.org/?probe=c7e03dae2f) | Oct 21, 2022 |
| Radxa         | ROCK Pi X v1.4              | [133d713246](https://linux-hardware.org/?probe=133d713246) | Oct 21, 2022 |
| Lenovo        | ThinkPad R61 8935AC7        | [94d73589fc](https://linux-hardware.org/?probe=94d73589fc) | Oct 21, 2022 |
| HP            | EliteBook 830 G8 Noteboo... | [47ca27793e](https://linux-hardware.org/?probe=47ca27793e) | Oct 21, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [7acb5493d7](https://linux-hardware.org/?probe=7acb5493d7) | Oct 21, 2022 |
| MAXDATA       | obook2-1                    | [0f73d884ff](https://linux-hardware.org/?probe=0f73d884ff) | Oct 21, 2022 |
| ASUSTek       | G75VW                       | [194959e65e](https://linux-hardware.org/?probe=194959e65e) | Oct 20, 2022 |
| Valve         | Jupiter                     | [ea0d3e9186](https://linux-hardware.org/?probe=ea0d3e9186) | Oct 20, 2022 |
| Gigabyte      | X7X7                        | [f2c35e3917](https://linux-hardware.org/?probe=f2c35e3917) | Oct 20, 2022 |
| HP            | ProBook 6550b               | [176fc347d2](https://linux-hardware.org/?probe=176fc347d2) | Oct 20, 2022 |
| HP            | EliteBook 840 Aero G8 No... | [80738ede80](https://linux-hardware.org/?probe=80738ede80) | Oct 20, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [c8e47b28fe](https://linux-hardware.org/?probe=c8e47b28fe) | Oct 20, 2022 |
| HP            | EliteBook 840 G5            | [ef1acaa7da](https://linux-hardware.org/?probe=ef1acaa7da) | Oct 20, 2022 |
| HP            | EliteBook 840 G5            | [3ec2887574](https://linux-hardware.org/?probe=3ec2887574) | Oct 20, 2022 |
| Dell          | Precision 5510              | [bb7788ce01](https://linux-hardware.org/?probe=bb7788ce01) | Oct 20, 2022 |
| Alienware     | x15 R2                      | [39d9f7988a](https://linux-hardware.org/?probe=39d9f7988a) | Oct 20, 2022 |
| Dell          | Latitude 5420               | [a6ef44d08a](https://linux-hardware.org/?probe=a6ef44d08a) | Oct 20, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [5a8ac06ce5](https://linux-hardware.org/?probe=5a8ac06ce5) | Oct 19, 2022 |
| Dell          | Latitude 7300               | [5674456b5d](https://linux-hardware.org/?probe=5674456b5d) | Oct 19, 2022 |
| HP            | 620                         | [263e2a0ba9](https://linux-hardware.org/?probe=263e2a0ba9) | Oct 19, 2022 |
| Notebook      | NS50_70MU                   | [0f13ae1769](https://linux-hardware.org/?probe=0f13ae1769) | Oct 19, 2022 |
| Notebook      | NS50_70MU                   | [2df95e6892](https://linux-hardware.org/?probe=2df95e6892) | Oct 19, 2022 |
| HP            | 620                         | [ad17206515](https://linux-hardware.org/?probe=ad17206515) | Oct 18, 2022 |
| Dell          | Precision 7750              | [93dcf0527b](https://linux-hardware.org/?probe=93dcf0527b) | Oct 18, 2022 |
| Dell          | Precision 7750              | [d32782f149](https://linux-hardware.org/?probe=d32782f149) | Oct 18, 2022 |
| ASUSTek       | G75VW                       | [5ee12be257](https://linux-hardware.org/?probe=5ee12be257) | Oct 18, 2022 |
| Insyde        | WindTab89                   | [8eb81874bb](https://linux-hardware.org/?probe=8eb81874bb) | Oct 18, 2022 |
| UNOWHY        | Y13G010S4EI                 | [f7f13866aa](https://linux-hardware.org/?probe=f7f13866aa) | Oct 18, 2022 |
| Dell          | Latitude 7300               | [c9bc03da26](https://linux-hardware.org/?probe=c9bc03da26) | Oct 18, 2022 |
| HP            | ZBook 14 G2                 | [fde830d956](https://linux-hardware.org/?probe=fde830d956) | Oct 18, 2022 |
| Sony          | VPCEH3U1E                   | [aff8f19a59](https://linux-hardware.org/?probe=aff8f19a59) | Oct 18, 2022 |
| Sony          | VPCEH3U1E                   | [c33d20c223](https://linux-hardware.org/?probe=c33d20c223) | Oct 18, 2022 |
| HP            | Pavilion dv7                | [bb650e8400](https://linux-hardware.org/?probe=bb650e8400) | Oct 18, 2022 |
| Dell          | Precision 3570              | [90711415f5](https://linux-hardware.org/?probe=90711415f5) | Oct 18, 2022 |
| ASUSTek       | F9S                         | [c8df776935](https://linux-hardware.org/?probe=c8df776935) | Oct 17, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [bbff53957f](https://linux-hardware.org/?probe=bbff53957f) | Oct 17, 2022 |
| Dell          | G3 3500                     | [64698d52bb](https://linux-hardware.org/?probe=64698d52bb) | Oct 17, 2022 |
| Dell          | G3 3500                     | [902fc2d51b](https://linux-hardware.org/?probe=902fc2d51b) | Oct 17, 2022 |
| ASUSTek       | G75VW                       | [10bcc184e7](https://linux-hardware.org/?probe=10bcc184e7) | Oct 17, 2022 |
| UNOWHY        | Y13G010S4EI                 | [fca234fc49](https://linux-hardware.org/?probe=fca234fc49) | Oct 17, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [a4ebad3748](https://linux-hardware.org/?probe=a4ebad3748) | Oct 17, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [9e37b60507](https://linux-hardware.org/?probe=9e37b60507) | Oct 16, 2022 |
| ASUSTek       | G75VW                       | [a88a291921](https://linux-hardware.org/?probe=a88a291921) | Oct 16, 2022 |
| ASUSTek       | M70Vn                       | [e9301bdee2](https://linux-hardware.org/?probe=e9301bdee2) | Oct 16, 2022 |
| Dell          | Latitude 3500               | [d578b45420](https://linux-hardware.org/?probe=d578b45420) | Oct 16, 2022 |
| Dell          | Latitude E5420              | [dcc7463646](https://linux-hardware.org/?probe=dcc7463646) | Oct 16, 2022 |
| HP            | ENVY 17                     | [ab25d54223](https://linux-hardware.org/?probe=ab25d54223) | Oct 16, 2022 |
| UNOWHY        | Y13G011S4EI                 | [c210cda35b](https://linux-hardware.org/?probe=c210cda35b) | Oct 16, 2022 |
| Lenovo        | V145-15AST 81MT             | [d73a82b798](https://linux-hardware.org/?probe=d73a82b798) | Oct 15, 2022 |
| Valve         | Jupiter                     | [7559400f9a](https://linux-hardware.org/?probe=7559400f9a) | Oct 15, 2022 |
| ASUSTek       | X751NV                      | [174ee8f3e7](https://linux-hardware.org/?probe=174ee8f3e7) | Oct 15, 2022 |
| Dell          | Latitude 5400               | [645c7a01da](https://linux-hardware.org/?probe=645c7a01da) | Oct 15, 2022 |
| Acer          | AOD257                      | [41a717913c](https://linux-hardware.org/?probe=41a717913c) | Oct 15, 2022 |
| Acer          | Aspire 7730ZG               | [4796b36078](https://linux-hardware.org/?probe=4796b36078) | Oct 15, 2022 |
| Acer          | Aspire 7740                 | [a68780a6fd](https://linux-hardware.org/?probe=a68780a6fd) | Oct 15, 2022 |
| Lenovo        | ThinkPad L420 78545EG       | [d2c975644c](https://linux-hardware.org/?probe=d2c975644c) | Oct 15, 2022 |
| Lenovo        | ThinkPad T420 4236JY2       | [fd260f87a9](https://linux-hardware.org/?probe=fd260f87a9) | Oct 14, 2022 |
| Dell          | G3 3500                     | [f7cc47bb67](https://linux-hardware.org/?probe=f7cc47bb67) | Oct 13, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [e4c404552a](https://linux-hardware.org/?probe=e4c404552a) | Oct 13, 2022 |
| HP            | EliteBook 840 G1            | [fe9dde997d](https://linux-hardware.org/?probe=fe9dde997d) | Oct 13, 2022 |
| MSI           | GE70 2QE                    | [2825343a52](https://linux-hardware.org/?probe=2825343a52) | Oct 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [d1c1c4adea](https://linux-hardware.org/?probe=d1c1c4adea) | Oct 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 34481... | [adce18affa](https://linux-hardware.org/?probe=adce18affa) | Oct 13, 2022 |
| UNOWHY        | Y13G011S4EI                 | [2be4dc3fc2](https://linux-hardware.org/?probe=2be4dc3fc2) | Oct 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [dfc5a5f754](https://linux-hardware.org/?probe=dfc5a5f754) | Oct 13, 2022 |
| Dell          | Latitude E5550              | [fc1fa79f81](https://linux-hardware.org/?probe=fc1fa79f81) | Oct 13, 2022 |
| Dell          | Inspiron 5759               | [2656af4553](https://linux-hardware.org/?probe=2656af4553) | Oct 13, 2022 |
| HP            | Stream Notebook PC 13       | [173cd34bf9](https://linux-hardware.org/?probe=173cd34bf9) | Oct 12, 2022 |
| ASUSTek       | M70Vn                       | [62cb9744e6](https://linux-hardware.org/?probe=62cb9744e6) | Oct 12, 2022 |
| Thomson       | N14C4WH64                   | [bfc16b9ded](https://linux-hardware.org/?probe=bfc16b9ded) | Oct 12, 2022 |
| ASUSTek       | N53Jg                       | [0b4302ed6c](https://linux-hardware.org/?probe=0b4302ed6c) | Oct 11, 2022 |
| Dell          | Latitude E6410              | [9ed4124073](https://linux-hardware.org/?probe=9ed4124073) | Oct 11, 2022 |
| Acer          | Aspire 7750G                | [e0c71d09bb](https://linux-hardware.org/?probe=e0c71d09bb) | Oct 11, 2022 |
| Acer          | Aspire 7750G                | [4eacf977db](https://linux-hardware.org/?probe=4eacf977db) | Oct 11, 2022 |
| Lenovo        | G50-30 80G0                 | [f96c4889db](https://linux-hardware.org/?probe=f96c4889db) | Oct 10, 2022 |
| Letni         | Z156                        | [994c588906](https://linux-hardware.org/?probe=994c588906) | Oct 10, 2022 |
| Dell          | Latitude 5400               | [ff8eb160c9](https://linux-hardware.org/?probe=ff8eb160c9) | Oct 10, 2022 |
| HP            | Notebook                    | [2fd3bd5ee0](https://linux-hardware.org/?probe=2fd3bd5ee0) | Oct 10, 2022 |
| Alienware     | m15 R7                      | [79aa2b2dd4](https://linux-hardware.org/?probe=79aa2b2dd4) | Oct 10, 2022 |
| Chuwi         | GemiBook Pro                | [02170aab85](https://linux-hardware.org/?probe=02170aab85) | Oct 09, 2022 |
| Notebook      | NLx0MU                      | [900e75392f](https://linux-hardware.org/?probe=900e75392f) | Oct 09, 2022 |
| Dell          | Inspiron 16 7610            | [fddf8f17bd](https://linux-hardware.org/?probe=fddf8f17bd) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | [1b90e3cfa5](https://linux-hardware.org/?probe=1b90e3cfa5) | Oct 08, 2022 |
| Chuwi         | GemiBook Pro                | [1a165faedb](https://linux-hardware.org/?probe=1a165faedb) | Oct 08, 2022 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | [1b720b4302](https://linux-hardware.org/?probe=1b720b4302) | Oct 08, 2022 |
| Dell          | Latitude E6410              | [0b617be9dd](https://linux-hardware.org/?probe=0b617be9dd) | Oct 08, 2022 |
| HP            | EliteBook 840 G3            | [2643af430d](https://linux-hardware.org/?probe=2643af430d) | Oct 08, 2022 |
| HP            | EliteBook 840 G3            | [f8bf937f1e](https://linux-hardware.org/?probe=f8bf937f1e) | Oct 08, 2022 |
| Apple         | MacBookAir6,2               | [9f434d86be](https://linux-hardware.org/?probe=9f434d86be) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | [9bb8f8e33b](https://linux-hardware.org/?probe=9bb8f8e33b) | Oct 07, 2022 |
| Acer          | Swift SF314-51              | [cfc56878f0](https://linux-hardware.org/?probe=cfc56878f0) | Oct 07, 2022 |
| HP            | Laptop 15s-fq2xxx           | [69e60dfe44](https://linux-hardware.org/?probe=69e60dfe44) | Oct 07, 2022 |
| Clevo         | W2xxHSQ                     | [3a05b61e0b](https://linux-hardware.org/?probe=3a05b61e0b) | Oct 07, 2022 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | [e6eac5c882](https://linux-hardware.org/?probe=e6eac5c882) | Oct 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [8901403de4](https://linux-hardware.org/?probe=8901403de4) | Oct 07, 2022 |
| MSI           | Modern 14 A10M              | [ae56e506c3](https://linux-hardware.org/?probe=ae56e506c3) | Oct 06, 2022 |
| Dell          | Latitude 7300               | [3eb18574b3](https://linux-hardware.org/?probe=3eb18574b3) | Oct 06, 2022 |
| ASUSTek       | X550LA                      | [c0c98c2051](https://linux-hardware.org/?probe=c0c98c2051) | Oct 06, 2022 |
| Dell          | Latitude 7480               | [aa3f8d08a6](https://linux-hardware.org/?probe=aa3f8d08a6) | Oct 06, 2022 |
| Toshiba       | Satellite NB10t-A-102       | [0bf17a1e92](https://linux-hardware.org/?probe=0bf17a1e92) | Oct 06, 2022 |
| PC Special... | PCX0DX                      | [35e44699ff](https://linux-hardware.org/?probe=35e44699ff) | Oct 06, 2022 |
| Sony          | VGN-SZ3XP_C                 | [f4fd751216](https://linux-hardware.org/?probe=f4fd751216) | Oct 05, 2022 |
| Dell          | Latitude 7300               | [a57bc6e1a5](https://linux-hardware.org/?probe=a57bc6e1a5) | Oct 05, 2022 |
| HP            | Compaq 15                   | [bba22531ad](https://linux-hardware.org/?probe=bba22531ad) | Oct 05, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [e4df51e64f](https://linux-hardware.org/?probe=e4df51e64f) | Oct 05, 2022 |
| Dell          | XPS 17 9710                 | [7590ca8bff](https://linux-hardware.org/?probe=7590ca8bff) | Oct 05, 2022 |
| Lenovo        | ThinkPad L430 24641J9       | [4f4932300b](https://linux-hardware.org/?probe=4f4932300b) | Oct 05, 2022 |
| HP            | Compaq 15                   | [0f48335990](https://linux-hardware.org/?probe=0f48335990) | Oct 05, 2022 |
| ASUSTek       | UX32VD                      | [0bea9d8673](https://linux-hardware.org/?probe=0bea9d8673) | Oct 05, 2022 |
| ASUSTek       | S551LN                      | [bdb441bda7](https://linux-hardware.org/?probe=bdb441bda7) | Oct 04, 2022 |
| ASUSTek       | S551LN                      | [b56c08cbcf](https://linux-hardware.org/?probe=b56c08cbcf) | Oct 04, 2022 |
| Dell          | Latitude E5430 non-vPro     | [33b42f3ed1](https://linux-hardware.org/?probe=33b42f3ed1) | Oct 04, 2022 |
| HP            | ZBook 14u G6                | [87437a85a7](https://linux-hardware.org/?probe=87437a85a7) | Oct 04, 2022 |
| MSI           | CR61 3M                     | [496910c25b](https://linux-hardware.org/?probe=496910c25b) | Oct 04, 2022 |
| Medion        | E7214                       | [c4ee9367cf](https://linux-hardware.org/?probe=c4ee9367cf) | Oct 04, 2022 |
| Medion        | E7214                       | [e8e78221ca](https://linux-hardware.org/?probe=e8e78221ca) | Oct 04, 2022 |
| Dell          | Latitude E6230              | [a4af37beac](https://linux-hardware.org/?probe=a4af37beac) | Oct 04, 2022 |
| UNOWHY        | Y13G010S4EI                 | [38f5b56e5d](https://linux-hardware.org/?probe=38f5b56e5d) | Oct 04, 2022 |
| Notebook      | W54_55SU1,SUW               | [54083a4f07](https://linux-hardware.org/?probe=54083a4f07) | Oct 04, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [eb1ee8ad1f](https://linux-hardware.org/?probe=eb1ee8ad1f) | Oct 04, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [84fbbaf62c](https://linux-hardware.org/?probe=84fbbaf62c) | Oct 04, 2022 |
| Lenovo        | B590 62743BG                | [8c120b5fea](https://linux-hardware.org/?probe=8c120b5fea) | Oct 03, 2022 |
| Apple         | MacBookPro5,5               | [5a5aada87f](https://linux-hardware.org/?probe=5a5aada87f) | Oct 03, 2022 |
| Dell          | Latitude E6420              | [cc0d33aedb](https://linux-hardware.org/?probe=cc0d33aedb) | Oct 03, 2022 |
| Dell          | Latitude E5430 non-vPro     | [81ac41d8b9](https://linux-hardware.org/?probe=81ac41d8b9) | Oct 03, 2022 |
| HP            | EliteBook 840 G1            | [5bcba21765](https://linux-hardware.org/?probe=5bcba21765) | Oct 03, 2022 |
| Dell          | Latitude 7300               | [d9acb6ec9c](https://linux-hardware.org/?probe=d9acb6ec9c) | Oct 03, 2022 |
| Dell          | Precision 5560              | [168025b691](https://linux-hardware.org/?probe=168025b691) | Oct 03, 2022 |
| Sony          | VPCSB1S1E                   | [b85b92339b](https://linux-hardware.org/?probe=b85b92339b) | Oct 03, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [2f9e023d1e](https://linux-hardware.org/?probe=2f9e023d1e) | Oct 03, 2022 |
| Dell          | Latitude 7490               | [872aafeb50](https://linux-hardware.org/?probe=872aafeb50) | Oct 02, 2022 |
| Dell          | Latitude E6410              | [7f89aefd99](https://linux-hardware.org/?probe=7f89aefd99) | Oct 02, 2022 |
| Lenovo        | ThinkPad R500 27148UG       | [1c968e44cb](https://linux-hardware.org/?probe=1c968e44cb) | Oct 02, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | [80a2948ff1](https://linux-hardware.org/?probe=80a2948ff1) | Oct 02, 2022 |
| Sony          | VGN-SZ3XP_C                 | [6e9671dd1a](https://linux-hardware.org/?probe=6e9671dd1a) | Oct 02, 2022 |
| ASUSTek       | X550JX                      | [43694e5952](https://linux-hardware.org/?probe=43694e5952) | Oct 02, 2022 |
| Acer          | Aspire 7750G                | [ccf9b69093](https://linux-hardware.org/?probe=ccf9b69093) | Oct 02, 2022 |
| Acer          | Aspire 7750G                | [7b89b5d0cf](https://linux-hardware.org/?probe=7b89b5d0cf) | Oct 02, 2022 |
| Dell          | Latitude E6510              | [71b8d3743e](https://linux-hardware.org/?probe=71b8d3743e) | Oct 02, 2022 |
| HP            | ZBook 14 G2                 | [ac14cbda52](https://linux-hardware.org/?probe=ac14cbda52) | Oct 02, 2022 |
| HP            | ZBook 14 G2                 | [d0a30f35b6](https://linux-hardware.org/?probe=d0a30f35b6) | Oct 02, 2022 |
| HP            | ZBook 14 G2                 | [e192869dc8](https://linux-hardware.org/?probe=e192869dc8) | Oct 02, 2022 |
| ASUSTek       | X71Q                        | [830c8ab6d2](https://linux-hardware.org/?probe=830c8ab6d2) | Oct 02, 2022 |
| UNOWHY        | Y13G012S4EI                 | [5c4c517651](https://linux-hardware.org/?probe=5c4c517651) | Oct 02, 2022 |
| HP            | EliteBook 840 G1            | [3f70868547](https://linux-hardware.org/?probe=3f70868547) | Oct 02, 2022 |
| MSI           | CR61 3M                     | [818a721825](https://linux-hardware.org/?probe=818a721825) | Oct 02, 2022 |
| HP            | Pavilion dv7                | [2da8f083a7](https://linux-hardware.org/?probe=2da8f083a7) | Oct 01, 2022 |
| MSI           | GF65 Thin 9SEXR             | [537828a21f](https://linux-hardware.org/?probe=537828a21f) | Oct 01, 2022 |
| UNOWHY        | Y13G012S4EI                 | [014d8c23f8](https://linux-hardware.org/?probe=014d8c23f8) | Oct 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [462f9bbdbe](https://linux-hardware.org/?probe=462f9bbdbe) | Oct 01, 2022 |
| Lenovo        | B70-80 80MR                 | [69aec9e100](https://linux-hardware.org/?probe=69aec9e100) | Oct 01, 2022 |
| Dell          | XPS 13 9300                 | [1fade0f247](https://linux-hardware.org/?probe=1fade0f247) | Oct 01, 2022 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [1cfda531dd](https://linux-hardware.org/?probe=1cfda531dd) | Oct 01, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [24aefc4138](https://linux-hardware.org/?probe=24aefc4138) | Oct 01, 2022 |
| MSI           | Modern 14 A10M              | [571271ed93](https://linux-hardware.org/?probe=571271ed93) | Sep 30, 2022 |
| MSI           | Modern 14 A10M              | [9da1f3fe66](https://linux-hardware.org/?probe=9da1f3fe66) | Sep 30, 2022 |
| Dell          | Inspiron 15 7510            | [263276babe](https://linux-hardware.org/?probe=263276babe) | Sep 30, 2022 |
| HP            | ProBook 6570b               | [d9be946342](https://linux-hardware.org/?probe=d9be946342) | Sep 30, 2022 |
| Toshiba       | Satellite NB10t-A-102       | [5a8032ee05](https://linux-hardware.org/?probe=5a8032ee05) | Sep 30, 2022 |
| Dell          | Inspiron 15 7510            | [86e1da35ba](https://linux-hardware.org/?probe=86e1da35ba) | Sep 30, 2022 |
| Toshiba       | Satellite NB10t-A-102       | [4e9248b1eb](https://linux-hardware.org/?probe=4e9248b1eb) | Sep 30, 2022 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | [786e0c1f5d](https://linux-hardware.org/?probe=786e0c1f5d) | Sep 30, 2022 |
| HUAWEI        | VLT-WX0                     | [1669dae0a6](https://linux-hardware.org/?probe=1669dae0a6) | Sep 30, 2022 |
| Toshiba       | Satellite L670              | [3b3e7965a5](https://linux-hardware.org/?probe=3b3e7965a5) | Sep 29, 2022 |
| HP            | Laptop 14s-fq1xxx           | [3990ec6cb0](https://linux-hardware.org/?probe=3990ec6cb0) | Sep 29, 2022 |
| TUXEDO        | Book_XA1510                 | [f39b64916d](https://linux-hardware.org/?probe=f39b64916d) | Sep 29, 2022 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | [0cbacebb95](https://linux-hardware.org/?probe=0cbacebb95) | Sep 29, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [defae2e862](https://linux-hardware.org/?probe=defae2e862) | Sep 28, 2022 |
| ASUSTek       | TUF Gaming FX505DT_TUF50... | [f758c22d98](https://linux-hardware.org/?probe=f758c22d98) | Sep 28, 2022 |
| ASUSTek       | TUF Gaming FX505DT_TUF50... | [b08fc47990](https://linux-hardware.org/?probe=b08fc47990) | Sep 28, 2022 |
| Dell          | XPS 15 9570                 | [564eb3b439](https://linux-hardware.org/?probe=564eb3b439) | Sep 28, 2022 |
| Dell          | XPS 15 9570                 | [085bd81d5b](https://linux-hardware.org/?probe=085bd81d5b) | Sep 28, 2022 |
| Dell          | Latitude E6540              | [27c854b1a0](https://linux-hardware.org/?probe=27c854b1a0) | Sep 27, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [ec59847e5b](https://linux-hardware.org/?probe=ec59847e5b) | Sep 27, 2022 |
| Dell          | Latitude E5250              | [6116460e52](https://linux-hardware.org/?probe=6116460e52) | Sep 27, 2022 |
| Timi          | TM1604                      | [2ee795db1a](https://linux-hardware.org/?probe=2ee795db1a) | Sep 27, 2022 |
| MSI           | GS73 Stealth 8RF            | [37d9172163](https://linux-hardware.org/?probe=37d9172163) | Sep 26, 2022 |
| ASUSTek       | X580VD                      | [378e1d3133](https://linux-hardware.org/?probe=378e1d3133) | Sep 26, 2022 |
| Packard Be... | EasyNote LS44SB             | [184a0768bd](https://linux-hardware.org/?probe=184a0768bd) | Sep 26, 2022 |
| Insyde        | WindTab89                   | [0073af9597](https://linux-hardware.org/?probe=0073af9597) | Sep 26, 2022 |
| Insyde        | WindTab89                   | [6935ebecaa](https://linux-hardware.org/?probe=6935ebecaa) | Sep 26, 2022 |
| HP            | Spectre Pro x360 G2         | [d9248f7b2e](https://linux-hardware.org/?probe=d9248f7b2e) | Sep 26, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [109d0ef34c](https://linux-hardware.org/?probe=109d0ef34c) | Sep 26, 2022 |
| Acer          | Aspire 3810T                | [de19c5a7e9](https://linux-hardware.org/?probe=de19c5a7e9) | Sep 25, 2022 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | [2d7ce63bce](https://linux-hardware.org/?probe=2d7ce63bce) | Sep 25, 2022 |
| Acer          | Aspire SW5-012              | [ed8f3f7403](https://linux-hardware.org/?probe=ed8f3f7403) | Sep 25, 2022 |
| Packard Be... | EasyNote MH45               | [c312580997](https://linux-hardware.org/?probe=c312580997) | Sep 24, 2022 |
| Unknown       | Unknown                     | [63b1596d63](https://linux-hardware.org/?probe=63b1596d63) | Sep 24, 2022 |
| Dell          | Inspiron 3721               | [7411a700cf](https://linux-hardware.org/?probe=7411a700cf) | Sep 24, 2022 |
| ASUSTek       | G501VW                      | [550d6e5438](https://linux-hardware.org/?probe=550d6e5438) | Sep 24, 2022 |
| HP            | Laptop 17-bs0xx             | [33398b1a21](https://linux-hardware.org/?probe=33398b1a21) | Sep 23, 2022 |
| Acer          | Aspire ES1-732              | [d6ccc5301b](https://linux-hardware.org/?probe=d6ccc5301b) | Sep 23, 2022 |
| Dell          | XPS 9320                    | [959d1406dd](https://linux-hardware.org/?probe=959d1406dd) | Sep 23, 2022 |
| Dell          | Precision 3561              | [78b8d776ed](https://linux-hardware.org/?probe=78b8d776ed) | Sep 23, 2022 |
| Notebook      | NL40_50GU                   | [da07f4c223](https://linux-hardware.org/?probe=da07f4c223) | Sep 23, 2022 |
| Dell          | Inspiron 5537               | [7e3170527c](https://linux-hardware.org/?probe=7e3170527c) | Sep 22, 2022 |
| Dell          | Precision 5540              | [0f09e447ea](https://linux-hardware.org/?probe=0f09e447ea) | Sep 22, 2022 |
| Lenovo        | ThinkPad P51s 20HCS00F00    | [5f0dc19f55](https://linux-hardware.org/?probe=5f0dc19f55) | Sep 22, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [7fc4cdb860](https://linux-hardware.org/?probe=7fc4cdb860) | Sep 22, 2022 |
| ASUSTek       | UX510UXK                    | [baa57d8e16](https://linux-hardware.org/?probe=baa57d8e16) | Sep 21, 2022 |
| Lenovo        | ThinkPad Edge E320 1298A... | [869b076838](https://linux-hardware.org/?probe=869b076838) | Sep 21, 2022 |
| Acer          | Aspire E1-572               | [ba47323a29](https://linux-hardware.org/?probe=ba47323a29) | Sep 21, 2022 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | [f185fff0a3](https://linux-hardware.org/?probe=f185fff0a3) | Sep 21, 2022 |
| Dell          | Precision 7540              | [fb7472fe87](https://linux-hardware.org/?probe=fb7472fe87) | Sep 21, 2022 |
| HP            | Laptop 15-da0xxx            | [e234a2b52a](https://linux-hardware.org/?probe=e234a2b52a) | Sep 21, 2022 |
| HUAWEI        | BOHB-WAX9                   | [982931b71f](https://linux-hardware.org/?probe=982931b71f) | Sep 21, 2022 |
| Dell          | XPS 13 9370                 | [facc4c1755](https://linux-hardware.org/?probe=facc4c1755) | Sep 21, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [98d21fb774](https://linux-hardware.org/?probe=98d21fb774) | Sep 21, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [6d0a2986ad](https://linux-hardware.org/?probe=6d0a2986ad) | Sep 21, 2022 |
| HP            | Laptop 15-da0xxx            | [a454bf3aa7](https://linux-hardware.org/?probe=a454bf3aa7) | Sep 20, 2022 |
| Valve         | Jupiter                     | [3aeb184ce4](https://linux-hardware.org/?probe=3aeb184ce4) | Sep 20, 2022 |
| Lenovo        | ThinkPad T61 7659AB7        | [aa07f9c271](https://linux-hardware.org/?probe=aa07f9c271) | Sep 20, 2022 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [5d42a6abab](https://linux-hardware.org/?probe=5d42a6abab) | Sep 20, 2022 |
| Toshiba       | Satellite L875-11M          | [42f3498e9e](https://linux-hardware.org/?probe=42f3498e9e) | Sep 20, 2022 |
| Lenovo        | ThinkPad T61p 6457A24       | [d98e9a64bd](https://linux-hardware.org/?probe=d98e9a64bd) | Sep 20, 2022 |
| Valve         | Jupiter                     | [83ed33f7e6](https://linux-hardware.org/?probe=83ed33f7e6) | Sep 20, 2022 |
| PC Special... | NS50MU                      | [1843dfbb66](https://linux-hardware.org/?probe=1843dfbb66) | Sep 19, 2022 |
| HP            | Pavilion Laptop 14-ce3xx... | [89894daeb7](https://linux-hardware.org/?probe=89894daeb7) | Sep 19, 2022 |
| Dell          | Precision 7750              | [ced8b5a7b2](https://linux-hardware.org/?probe=ced8b5a7b2) | Sep 19, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [be279328b1](https://linux-hardware.org/?probe=be279328b1) | Sep 19, 2022 |
| HP            | 470 G7 Notebook PC          | [a9f6ad0c32](https://linux-hardware.org/?probe=a9f6ad0c32) | Sep 19, 2022 |
| Lenovo        | ThinkPad X200 7458VL3       | [700ff6630e](https://linux-hardware.org/?probe=700ff6630e) | Sep 18, 2022 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | [b94564300a](https://linux-hardware.org/?probe=b94564300a) | Sep 18, 2022 |
| HP            | Victus by Laptop 16-d0xx... | [aa3908e5fc](https://linux-hardware.org/?probe=aa3908e5fc) | Sep 17, 2022 |
| MSI           | Katana GF66 12UD            | [c0c6c57498](https://linux-hardware.org/?probe=c0c6c57498) | Sep 17, 2022 |
| MSI           | Katana GF66 12UD            | [fde2d03f98](https://linux-hardware.org/?probe=fde2d03f98) | Sep 17, 2022 |
| Dell          | Latitude E5540              | [8e44a11e6c](https://linux-hardware.org/?probe=8e44a11e6c) | Sep 16, 2022 |
| Dell          | Latitude E5540              | [c2d57deba4](https://linux-hardware.org/?probe=c2d57deba4) | Sep 16, 2022 |
| Valve         | Jupiter                     | [47ac328960](https://linux-hardware.org/?probe=47ac328960) | Sep 16, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [7a390e81b1](https://linux-hardware.org/?probe=7a390e81b1) | Sep 16, 2022 |
| HP            | ZBook Firefly 14 inch G9... | [f543e0852f](https://linux-hardware.org/?probe=f543e0852f) | Sep 16, 2022 |
| Lenovo        | ThinkPad T440s 20ARS0CN1... | [2f9eaf5711](https://linux-hardware.org/?probe=2f9eaf5711) | Sep 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [382325db11](https://linux-hardware.org/?probe=382325db11) | Sep 16, 2022 |
| ASUSTek       | X550JK                      | [5c399f4fb0](https://linux-hardware.org/?probe=5c399f4fb0) | Sep 15, 2022 |
| ASUSTek       | X550JK                      | [59df382a23](https://linux-hardware.org/?probe=59df382a23) | Sep 15, 2022 |
| HP            | ENVY Laptop 17-ch0xxx       | [1a1ae1e398](https://linux-hardware.org/?probe=1a1ae1e398) | Sep 15, 2022 |
| Acer          | Aspire A515-51G             | [bc275a0476](https://linux-hardware.org/?probe=bc275a0476) | Sep 15, 2022 |
| ASUSTek       | VivoBook E14 E402WAS        | [84dee7df6c](https://linux-hardware.org/?probe=84dee7df6c) | Sep 15, 2022 |
| Dell          | Precision 3571              | [01f5d7f7f8](https://linux-hardware.org/?probe=01f5d7f7f8) | Sep 15, 2022 |
| HUAWEI        | HVY-WXX9                    | [000eb38ea7](https://linux-hardware.org/?probe=000eb38ea7) | Sep 15, 2022 |
| HP            | OMEN by Laptop              | [282afe0352](https://linux-hardware.org/?probe=282afe0352) | Sep 15, 2022 |
| Fujitsu       | LIFEBOOK A512               | [2d33f80fbd](https://linux-hardware.org/?probe=2d33f80fbd) | Sep 15, 2022 |
| Dell          | Latitude E7470              | [9d15a7c8a2](https://linux-hardware.org/?probe=9d15a7c8a2) | Sep 14, 2022 |
| Dell          | Precision 7550              | [f6a8b38020](https://linux-hardware.org/?probe=f6a8b38020) | Sep 14, 2022 |
| Dell          | Inspiron 15 3520            | [1d74f86789](https://linux-hardware.org/?probe=1d74f86789) | Sep 14, 2022 |
| Dell          | Precision 3571              | [72e1a27ea7](https://linux-hardware.org/?probe=72e1a27ea7) | Sep 14, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [8935b3f204](https://linux-hardware.org/?probe=8935b3f204) | Sep 14, 2022 |
| HP            | Laptop 17-cp0xxx            | [c05d80959b](https://linux-hardware.org/?probe=c05d80959b) | Sep 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [5784c0a7e3](https://linux-hardware.org/?probe=5784c0a7e3) | Sep 14, 2022 |
| Dell          | Precision 7520              | [b83fea6b96](https://linux-hardware.org/?probe=b83fea6b96) | Sep 14, 2022 |
| HP            | Pavilion dv7                | [f94d6a4e8f](https://linux-hardware.org/?probe=f94d6a4e8f) | Sep 14, 2022 |
| Dell          | Latitude E5550              | [90674e3069](https://linux-hardware.org/?probe=90674e3069) | Sep 13, 2022 |
| ASUSTek       | X750JB                      | [dd6137189b](https://linux-hardware.org/?probe=dd6137189b) | Sep 13, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P5440FA_... | [d441c68f40](https://linux-hardware.org/?probe=d441c68f40) | Sep 13, 2022 |
| Samsung       | 950XED                      | [f8a15210f0](https://linux-hardware.org/?probe=f8a15210f0) | Sep 13, 2022 |
| Apple         | MacBookPro5,3               | [3e00c86066](https://linux-hardware.org/?probe=3e00c86066) | Sep 13, 2022 |
| HUAWEI        | HVY-WXX9                    | [999cbe4e8f](https://linux-hardware.org/?probe=999cbe4e8f) | Sep 13, 2022 |
| Apple         | MacBookPro5,3               | [9211f5de76](https://linux-hardware.org/?probe=9211f5de76) | Sep 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [0e6413e94b](https://linux-hardware.org/?probe=0e6413e94b) | Sep 13, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [82b9d1247e](https://linux-hardware.org/?probe=82b9d1247e) | Sep 13, 2022 |
| HP            | 470 G7 Notebook PC          | [f1c4e72e54](https://linux-hardware.org/?probe=f1c4e72e54) | Sep 12, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/France/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 943       | 19.89%  |
| Ubuntu 18.04       | 309       | 6.52%   |
| Ubuntu 22.04       | 240       | 5.06%   |
| OpenMandriva 4.2   | 171       | 3.61%   |
| Debian 11          | 167       | 3.52%   |
| OpenMandriva 4.3   | 134       | 2.83%   |
| Linux Mint 20.3    | 115       | 2.43%   |
| Xubuntu 20.04      | 108       | 2.28%   |
| Arch               | 80        | 1.69%   |
| Ubuntu 21.10       | 70        | 1.48%   |
| Debian 10          | 69        | 1.46%   |
| Linux Mint 20.2    | 63        | 1.33%   |
| Arch Rolling       | 61        | 1.29%   |
| Ubuntu 19.10       | 59        | 1.24%   |
| Ubuntu 21.04       | 56        | 1.18%   |
| Ubuntu 20.10       | 53        | 1.12%   |
| Manjaro            | 51        | 1.08%   |
| Linux Mint 19.3    | 49        | 1.03%   |
| Zorin 16           | 48        | 1.01%   |
| Xubuntu 18.04      | 48        | 1.01%   |
| Fedora 33          | 48        | 1.01%   |
| Fedora 34          | 44        | 0.93%   |
| Linux Mint 20.1    | 43        | 0.91%   |
| OpenMandriva 23.01 | 42        | 0.89%   |
| Kubuntu 20.04      | 41        | 0.86%   |
| Fedora 32          | 40        | 0.84%   |
| Ubuntu 19.04       | 39        | 0.82%   |
| Linux Mint 21      | 39        | 0.82%   |
| Fedora 36          | 38        | 0.8%    |
| Linux Mint 20      | 37        | 0.78%   |
| KDE neon 20.04     | 37        | 0.78%   |
| Pop!_OS 20.04      | 36        | 0.76%   |
| Ubuntu MATE 20.04  | 34        | 0.72%   |
| Fedora 35          | 34        | 0.72%   |
| Pop!_OS 22.04      | 32        | 0.68%   |
| Lubuntu 20.04      | 32        | 0.68%   |
| Pop!_OS 20.10      | 29        | 0.61%   |
| Pop!_OS 21.04      | 28        | 0.59%   |
| Fedora 37          | 28        | 0.59%   |
| Debian Testing     | 28        | 0.59%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1735      | 38.5%   |
| OpenMandriva  | 387       | 8.59%   |
| Linux Mint    | 373       | 8.28%   |
| Debian        | 292       | 6.48%   |
| Fedora        | 231       | 5.13%   |
| Xubuntu       | 193       | 4.28%   |
| Arch          | 139       | 3.08%   |
| Pop!_OS       | 135       | 3%      |
| Manjaro       | 132       | 2.93%   |
| Kubuntu       | 106       | 2.35%   |
| Zorin         | 75        | 1.66%   |
| ROSA          | 73        | 1.62%   |
| Ubuntu MATE   | 61        | 1.35%   |
| Lubuntu       | 55        | 1.22%   |
| KDE neon      | 47        | 1.04%   |
| Endless       | 42        | 0.93%   |
| openSUSE      | 41        | 0.91%   |
| Kali          | 35        | 0.78%   |
| Gentoo        | 31        | 0.69%   |
| Elementary    | 26        | 0.58%   |
| ArcoLinux     | 26        | 0.58%   |
| Ubuntu Budgie | 24        | 0.53%   |
| Ubuntu Unity  | 21        | 0.47%   |
| BlackPanther  | 19        | 0.42%   |
| Parrot        | 18        | 0.4%    |
| EndeavourOS   | 18        | 0.4%    |
| SteamOS       | 17        | 0.38%   |
| LMDE          | 15        | 0.33%   |
| Ubuntu Studio | 11        | 0.24%   |
| CentOS        | 11        | 0.24%   |
| Kaisen        | 9         | 0.2%    |
| NixOS         | 7         | 0.16%   |
| MX            | 7         | 0.16%   |
| Clear Linux   | 7         | 0.16%   |
| Peppermint    | 6         | 0.13%   |
| RHEL          | 5         | 0.11%   |
| Mageia        | 5         | 0.11%   |
| Linux Lite    | 5         | 0.11%   |
| Xero          | 4         | 0.09%   |
| LinuxFX       | 4         | 0.09%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 161       | 3.12%   |
| 5.16.7-desktop-1omv4003  | 129       | 2.5%    |
| 5.4.0-42-generic         | 73        | 1.42%   |
| 5.15.0-56-generic        | 72        | 1.4%    |
| 5.15.0-52-generic        | 52        | 1.01%   |
| 5.11.0-38-generic        | 50        | 0.97%   |
| 5.4.0-58-generic         | 44        | 0.85%   |
| 5.4.0-52-generic         | 44        | 0.85%   |
| 5.15.0-48-generic        | 44        | 0.85%   |
| 5.11.0-27-generic        | 42        | 0.81%   |
| 6.1.1-desktop-1omv2290   | 40        | 0.78%   |
| 5.4.0-26-generic         | 39        | 0.76%   |
| 5.15.0-58-generic        | 38        | 0.74%   |
| 5.4.0-48-generic         | 36        | 0.7%    |
| 5.8.0-50-generic         | 35        | 0.68%   |
| 5.15.0-46-generic        | 35        | 0.68%   |
| 5.11.0-37-generic        | 35        | 0.68%   |
| 5.8.0-43-generic         | 33        | 0.64%   |
| 5.4.0-65-generic         | 33        | 0.64%   |
| 5.8.0-44-generic         | 32        | 0.62%   |
| 5.4.0-91-generic         | 32        | 0.62%   |
| 5.11.0-43-generic        | 32        | 0.62%   |
| 5.4.0-37-generic         | 31        | 0.6%    |
| 5.13.0-30-generic        | 31        | 0.6%    |
| 5.11.0-40-generic        | 31        | 0.6%    |
| 5.13.0-40-generic        | 30        | 0.58%   |
| 5.15.0-47-generic        | 29        | 0.56%   |
| 5.11.0-34-generic        | 29        | 0.56%   |
| 5.8.0-59-generic         | 28        | 0.54%   |
| 5.8.0-48-generic         | 28        | 0.54%   |
| 5.4.0-54-generic         | 27        | 0.52%   |
| 5.15.0-53-generic        | 27        | 0.52%   |
| 5.15.0-43-generic        | 27        | 0.52%   |
| 5.15.0-41-generic        | 27        | 0.52%   |
| 5.13.0-28-generic        | 27        | 0.52%   |
| 5.4.0-31-generic         | 26        | 0.5%    |
| 5.4.0-81-generic         | 25        | 0.48%   |
| 5.13.0-39-generic        | 25        | 0.48%   |
| 5.8.0-55-generic         | 24        | 0.47%   |
| 5.8.0-53-generic         | 24        | 0.47%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 940       | 19.35%  |
| 5.15.0  | 455       | 9.37%   |
| 5.11.0  | 354       | 7.29%   |
| 5.8.0   | 350       | 7.21%   |
| 5.13.0  | 304       | 6.26%   |
| 4.15.0  | 223       | 4.59%   |
| 5.10.0  | 201       | 4.14%   |
| 5.3.0   | 176       | 3.62%   |
| 5.10.14 | 162       | 3.34%   |
| 5.16.7  | 129       | 2.66%   |
| 5.0.0   | 99        | 2.04%   |
| 4.18.0  | 66        | 1.36%   |
| 4.19.0  | 64        | 1.32%   |
| 6.1.1   | 50        | 1.03%   |
| 5.19.0  | 50        | 1.03%   |
| 5.14.0  | 29        | 0.6%    |
| 6.0.0   | 22        | 0.45%   |
| 5.17.5  | 19        | 0.39%   |
| 5.16.0  | 19        | 0.39%   |
| 5.11.12 | 19        | 0.39%   |
| 4.18.16 | 18        | 0.37%   |
| 5.18.12 | 15        | 0.31%   |
| 4.9.20  | 15        | 0.31%   |
| 5.9.0   | 14        | 0.29%   |
| 5.6.0   | 14        | 0.29%   |
| 5.18.0  | 14        | 0.29%   |
| 5.9.11  | 13        | 0.27%   |
| 5.17.0  | 12        | 0.25%   |
| 4.4.0   | 12        | 0.25%   |
| 6.0.9   | 11        | 0.23%   |
| 5.19.12 | 11        | 0.23%   |
| 5.14.9  | 11        | 0.23%   |
| 4.9.0   | 11        | 0.23%   |
| 5.9.16  | 10        | 0.21%   |
| 5.7.0   | 10        | 0.21%   |
| 5.17.1  | 10        | 0.21%   |
| 5.12.4  | 10        | 0.21%   |
| 5.8.18  | 9         | 0.19%   |
| 5.10.74 | 9         | 0.19%   |
| 6.0.6   | 8         | 0.16%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 989       | 20.63%  |
| 5.15    | 561       | 11.7%   |
| 5.10    | 443       | 9.24%   |
| 5.11    | 405       | 8.45%   |
| 5.8     | 391       | 8.15%   |
| 5.13    | 341       | 7.11%   |
| 4.15    | 223       | 4.65%   |
| 5.3     | 201       | 4.19%   |
| 5.16    | 193       | 4.03%   |
| 5.0     | 103       | 2.15%   |
| 5.19    | 101       | 2.11%   |
| 5.14    | 86        | 1.79%   |
| 4.18    | 86        | 1.79%   |
| 6.0     | 80        | 1.67%   |
| 5.9     | 71        | 1.48%   |
| 4.19    | 70        | 1.46%   |
| 6.1     | 65        | 1.36%   |
| 5.18    | 63        | 1.31%   |
| 5.17    | 59        | 1.23%   |
| 5.6     | 50        | 1.04%   |
| 4.9     | 47        | 0.98%   |
| 5.7     | 42        | 0.88%   |
| 5.12    | 38        | 0.79%   |
| 5.5     | 23        | 0.48%   |
| 4.4     | 14        | 0.29%   |
| 4.1     | 11        | 0.23%   |
| 4.14    | 8         | 0.17%   |
| 5.2     | 7         | 0.15%   |
| 4.13    | 5         | 0.1%    |
| 4.12    | 5         | 0.1%    |
| 4.10    | 4         | 0.08%   |
| 3.10    | 3         | 0.06%   |
| 5.1     | 2         | 0.04%   |
| 4.20    | 2         | 0.04%   |
| 4.8     | 1         | 0.02%   |
| 4.17    | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 4278      | 97.32%  |
| i686    | 115       | 2.62%   |
| aarch64 | 2         | 0.05%   |
| Unknown | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| GNOME             | 2130      | 46.78%  |
| KDE5              | 730       | 16.03%  |
| XFCE              | 423       | 9.29%   |
| Unknown           | 412       | 9.05%   |
| X-Cinnamon        | 243       | 5.34%   |
| MATE              | 171       | 3.76%   |
| Cinnamon          | 77        | 1.69%   |
| KDE               | 61        | 1.34%   |
| LXQt              | 58        | 1.27%   |
| i3                | 52        | 1.14%   |
| KDE4              | 50        | 1.1%    |
| Budgie            | 29        | 0.64%   |
| Pantheon          | 26        | 0.57%   |
| Unity             | 22        | 0.48%   |
| LXDE              | 19        | 0.42%   |
| GNOME Flashback   | 15        | 0.33%   |
| Deepin            | 8         | 0.18%   |
| GNOME Classic     | 6         | 0.13%   |
| i3-with-shmlog    | 3         | 0.07%   |
| Trinity           | 2         | 0.04%   |
| sway              | 2         | 0.04%   |
| bspwm             | 2         | 0.04%   |
| awesome           | 2         | 0.04%   |
| Yaru:ubuntu:GNOME | 1         | 0.02%   |
| xmonad            | 1         | 0.02%   |
| wmaker-common     | 1         | 0.02%   |
| qtile             | 1         | 0.02%   |
| openbox           | 1         | 0.02%   |
| Lubuntu           | 1         | 0.02%   |
| lightdm-xsession  | 1         | 0.02%   |
| ICEWM             | 1         | 0.02%   |
| Enlightenment     | 1         | 0.02%   |
| dwm-sc            | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 3579      | 79.08%  |
| Wayland | 667       | 14.74%  |
| Unknown | 213       | 4.71%   |
| Tty     | 67        | 1.48%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1764      | 38.72%  |
| GDM     | 862       | 18.92%  |
| SDDM    | 723       | 15.87%  |
| LightDM | 505       | 11.08%  |
| GDM3    | 455       | 9.99%   |
| TDM     | 182       | 3.99%   |
| KDM     | 48        | 1.05%   |
| XDM     | 9         | 0.2%    |
| SLiM    | 3         | 0.07%   |
| NODM    | 2         | 0.04%   |
| Ly      | 2         | 0.04%   |
| MDM     | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Notebooks | Percent |
|------------|-----------|---------|
| fr_FR      | 3030      | 67.86%  |
| en_US      | 809       | 18.12%  |
| Unknown    | 393       | 8.8%    |
| en_GB      | 76        | 1.7%    |
| C          | 39        | 0.87%   |
| ru_RU      | 13        | 0.29%   |
| pl_PL      | 10        | 0.22%   |
| it_IT      | 10        | 0.22%   |
| de_DE      | 10        | 0.22%   |
| es_ES      | 8         | 0.18%   |
| fr_CH      | 7         | 0.16%   |
| POSIX      | 5         | 0.11%   |
| nl_NL      | 5         | 0.11%   |
| fr_CA      | 5         | 0.11%   |
| fr_BE      | 4         | 0.09%   |
| ru_UA      | 3         | 0.07%   |
| pt_PT      | 3         | 0.07%   |
| pt_BR      | 3         | 0.07%   |
| en_IN      | 3         | 0.07%   |
| en_AU      | 3         | 0.07%   |
| hu_HU      | 2         | 0.04%   |
| en_IE      | 2         | 0.04%   |
| en_CA      | 2         | 0.04%   |
| cs_CZ      | 2         | 0.04%   |
| tr_TR      | 1         | 0.02%   |
| sv_SE      | 1         | 0.02%   |
| sk_SK      | 1         | 0.02%   |
| ro_RO      | 1         | 0.02%   |
| nb_NO      | 1         | 0.02%   |
| fr_LU      | 1         | 0.02%   |
| fr_FR.UTF8 | 1         | 0.02%   |
| es_VE      | 1         | 0.02%   |
| es_UY      | 1         | 0.02%   |
| es_AR      | 1         | 0.02%   |
| en_ZA      | 1         | 0.02%   |
| en_FR      | 1         | 0.02%   |
| en_AG      | 1         | 0.02%   |
| de_CH      | 1         | 0.02%   |
| de_BE      | 1         | 0.02%   |
| de_AT      | 1         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 2539      | 56.69%  |
| BIOS | 1940      | 43.31%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 3622      | 81.12%  |
| Overlay  | 370       | 8.29%   |
| Btrfs    | 282       | 6.32%   |
| Unknown  | 109       | 2.44%   |
| Xfs      | 33        | 0.74%   |
| Zfs      | 21        | 0.47%   |
| F2fs     | 9         | 0.2%    |
| Ext3     | 8         | 0.18%   |
| Ext2     | 8         | 0.18%   |
| Tmpfs    | 1         | 0.02%   |
| Reiserfs | 1         | 0.02%   |
| Jfs      | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 1965      | 43.76%  |
| Unknown | 1927      | 42.92%  |
| MBR     | 598       | 13.32%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3843      | 86.03%  |
| Yes       | 624       | 13.97%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3094      | 69.51%  |
| Yes       | 1357      | 30.49%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell                | 789       | 17.95%  |
| Hewlett-Packard     | 737       | 16.77%  |
| Lenovo              | 730       | 16.61%  |
| ASUSTek Computer    | 716       | 16.29%  |
| Acer                | 326       | 7.42%   |
| MSI                 | 164       | 3.73%   |
| Toshiba             | 146       | 3.32%   |
| Apple               | 92        | 2.09%   |
| Notebook            | 80        | 1.82%   |
| HUAWEI              | 66        | 1.5%    |
| Samsung Electronics | 62        | 1.41%   |
| Packard Bell        | 55        | 1.25%   |
| Sony                | 53        | 1.21%   |
| TUXEDO              | 26        | 0.59%   |
| Timi                | 21        | 0.48%   |
| Clevo               | 20        | 0.46%   |
| Unknown             | 19        | 0.43%   |
| Valve               | 18        | 0.41%   |
| UNOWHY              | 18        | 0.41%   |
| Thomson             | 18        | 0.41%   |
| eMachines           | 18        | 0.41%   |
| Gigabyte Technology | 17        | 0.39%   |
| Fujitsu Siemens     | 15        | 0.34%   |
| Fujitsu             | 15        | 0.34%   |
| Alienware           | 14        | 0.32%   |
| PC Specialist       | 13        | 0.3%    |
| Razer               | 12        | 0.27%   |
| Medion              | 10        | 0.23%   |
| Google              | 10        | 0.23%   |
| Chuwi               | 10        | 0.23%   |
| Teclast             | 9         | 0.2%    |
| Intel               | 7         | 0.16%   |
| BESSTAR Tech        | 5         | 0.11%   |
| Panasonic           | 4         | 0.09%   |
| HONOR               | 4         | 0.09%   |
| AZW                 | 4         | 0.09%   |
| System76            | 3         | 0.07%   |
| SCHNEIDER           | 3         | 0.07%   |
| Schenker            | 3         | 0.07%   |
| NEC Computers       | 3         | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| HP Notebook                     | 36        | 0.82%   |
| Unknown                         | 35        | 0.8%    |
| HP Pavilion dv6                 | 25        | 0.57%   |
| HP Pavilion dv7                 | 22        | 0.5%    |
| HP Pavilion 17                  | 21        | 0.48%   |
| Valve Jupiter                   | 18        | 0.41%   |
| HP Pavilion g7                  | 17        | 0.39%   |
| Dell XPS 13 9310                | 17        | 0.39%   |
| ASUS S551LN                     | 16        | 0.36%   |
| HP Pavilion Notebook            | 15        | 0.34%   |
| Dell XPS 13 9380                | 15        | 0.34%   |
| Dell XPS 13 7390                | 14        | 0.32%   |
| Dell Latitude E6420             | 14        | 0.32%   |
| HP EliteBook 840 G2             | 13        | 0.3%    |
| Dell XPS 15 7590                | 13        | 0.3%    |
| HP EliteBook 840 G3             | 12        | 0.27%   |
| Dell XPS 15 9570                | 12        | 0.27%   |
| Dell Latitude 5420              | 12        | 0.27%   |
| HUAWEI HVY-WXX9                 | 11        | 0.25%   |
| HP ProBook 650 G1               | 11        | 0.25%   |
| HP Pavilion g6                  | 11        | 0.25%   |
| HP Pavilion 15                  | 11        | 0.25%   |
| Lenovo G50-30 80G0              | 10        | 0.23%   |
| HUAWEI NBLK-WAX9X               | 10        | 0.23%   |
| HP OMEN by Laptop               | 10        | 0.23%   |
| Dell XPS 15 9500                | 10        | 0.23%   |
| Dell Latitude E6400             | 10        | 0.23%   |
| Lenovo G50-45 80E3              | 9         | 0.2%    |
| Dell Latitude 7490              | 9         | 0.2%    |
| Dell Latitude 5400              | 9         | 0.2%    |
| Acer Aspire ES1-523             | 9         | 0.2%    |
| UNOWHY Y13G010S4EI              | 8         | 0.18%   |
| HP ProBook 640 G1               | 8         | 0.18%   |
| HP Laptop 15-db0xxx             | 8         | 0.18%   |
| HP EliteBook 840 G8 Notebook PC | 8         | 0.18%   |
| HP EliteBook 840 G1             | 8         | 0.18%   |
| Dell XPS 13 9370                | 8         | 0.18%   |
| Dell Precision 5540             | 8         | 0.18%   |
| Dell Latitude E6520             | 8         | 0.18%   |
| Dell Latitude E6410             | 8         | 0.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 425       | 9.67%   |
| Dell Latitude         | 320       | 7.28%   |
| Acer Aspire           | 223       | 5.07%   |
| HP Pavilion           | 198       | 4.51%   |
| HP EliteBook          | 143       | 3.25%   |
| Dell XPS              | 142       | 3.23%   |
| Lenovo IdeaPad        | 136       | 3.09%   |
| Toshiba Satellite     | 123       | 2.8%    |
| Dell Inspiron         | 119       | 2.71%   |
| HP ProBook            | 117       | 2.66%   |
| Dell Precision        | 110       | 2.5%    |
| ASUS VivoBook         | 100       | 2.28%   |
| HP Laptop             | 63        | 1.43%   |
| Packard Bell EasyNote | 48        | 1.09%   |
| ASUS ZenBook          | 44        | 1%      |
| Acer Swift            | 42        | 0.96%   |
| Dell Vostro           | 37        | 0.84%   |
| HP Notebook           | 36        | 0.82%   |
| Lenovo Legion         | 35        | 0.8%    |
| Unknown               | 35        | 0.8%    |
| HP Compaq             | 34        | 0.77%   |
| ASUS ROG              | 34        | 0.77%   |
| HP ZBook              | 31        | 0.71%   |
| ASUS ASUS             | 22        | 0.5%    |
| Acer Nitro            | 22        | 0.5%    |
| HP ENVY               | 21        | 0.48%   |
| HP OMEN               | 20        | 0.46%   |
| Valve Jupiter         | 18        | 0.41%   |
| ASUS TUF              | 18        | 0.41%   |
| Lenovo ThinkBook      | 17        | 0.39%   |
| Dell G5               | 17        | 0.39%   |
| MSI Modern            | 16        | 0.36%   |
| ASUS S551LN           | 16        | 0.36%   |
| Dell G3               | 15        | 0.34%   |
| Acer TravelMate       | 15        | 0.34%   |
| Lenovo Yoga           | 14        | 0.32%   |
| Fujitsu LIFEBOOK      | 13        | 0.3%    |
| Razer Blade           | 12        | 0.27%   |
| Apple MacBookPro5     | 12        | 0.27%   |
| Toshiba PORTEGE       | 11        | 0.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 469       | 10.67%  |
| 2019    | 454       | 10.33%  |
| 2018    | 393       | 8.94%   |
| 2012    | 330       | 7.51%   |
| 2021    | 316       | 7.19%   |
| 2013    | 308       | 7.01%   |
| 2015    | 294       | 6.69%   |
| 2011    | 286       | 6.51%   |
| 2017    | 254       | 5.78%   |
| 2016    | 236       | 5.37%   |
| 2014    | 227       | 5.16%   |
| 2010    | 220       | 5.01%   |
| 2008    | 200       | 4.55%   |
| 2009    | 163       | 3.71%   |
| 2022    | 97        | 2.21%   |
| 2007    | 93        | 2.12%   |
| 2006    | 31        | 0.71%   |
| 2005    | 15        | 0.34%   |
| Unknown | 4         | 0.09%   |
| 2004    | 3         | 0.07%   |
| 2003    | 1         | 0.02%   |
| 2002    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 4395      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 3913      | 88.31%  |
| Enabled  | 518       | 11.69%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 4380      | 99.64%  |
| Yes  | 16        | 0.36%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1212      | 27.33%  |
| 3.01-4.0    | 1101      | 24.83%  |
| 16.01-24.0  | 780       | 17.59%  |
| 8.01-16.0   | 667       | 15.04%  |
| 32.01-64.0  | 278       | 6.27%   |
| 1.01-2.0    | 191       | 4.31%   |
| 2.01-3.0    | 86        | 1.94%   |
| 64.01-256.0 | 41        | 0.92%   |
| 24.01-32.0  | 37        | 0.83%   |
| 0.51-1.0    | 33        | 0.74%   |
| 0.01-0.5    | 6         | 0.14%   |
| Unknown     | 2         | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1727      | 36.09%  |
| 2.01-3.0   | 1225      | 25.6%   |
| 4.01-8.0   | 663       | 13.86%  |
| 3.01-4.0   | 596       | 12.46%  |
| 0.51-1.0   | 311       | 6.5%    |
| 8.01-16.0  | 194       | 4.05%   |
| 0.01-0.5   | 46        | 0.96%   |
| 16.01-24.0 | 14        | 0.29%   |
| 24.01-32.0 | 6         | 0.13%   |
| Unknown    | 2         | 0.04%   |
| 32.01-64.0 | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3277      | 73.51%  |
| 2      | 1019      | 22.86%  |
| 3      | 100       | 2.24%   |
| 0      | 40        | 0.9%    |
| 4      | 14        | 0.31%   |
| 5      | 5         | 0.11%   |
| 6      | 2         | 0.04%   |
| 7      | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2667      | 60.37%  |
| Yes       | 1751      | 39.63%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3619      | 82.08%  |
| No        | 790       | 17.92%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4318      | 98.14%  |
| No        | 82        | 1.86%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3351      | 75.34%  |
| No        | 1097      | 24.66%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| France  | 4395      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Paris            | 745       | 15.72%  |
| Lyon             | 102       | 2.15%   |
| Toulouse         | 83        | 1.75%   |
| Marseille        | 80        | 1.69%   |
| Nantes           | 60        | 1.27%   |
| Montpellier      | 52        | 1.1%    |
| Lille            | 46        | 0.97%   |
| Bordeaux         | 42        | 0.89%   |
| Strasbourg       | 39        | 0.82%   |
| Rennes           | 39        | 0.82%   |
| Grenoble         | 33        | 0.7%    |
| Clichy-sous-Bois | 28        | 0.59%   |
| Brest            | 28        | 0.59%   |
| Villeurbanne     | 26        | 0.55%   |
| Roubaix          | 26        | 0.55%   |
| Nice             | 24        | 0.51%   |
| Rouen            | 20        | 0.42%   |
| Caen             | 20        | 0.42%   |
| Cergy            | 18        | 0.38%   |
| Toulon           | 16        | 0.34%   |
| Poitiers         | 16        | 0.34%   |
| Nancy            | 16        | 0.34%   |
| Metz             | 16        | 0.34%   |
| La Rochelle      | 16        | 0.34%   |
| Aix-en-Provence  | 16        | 0.34%   |
| Tours            | 15        | 0.32%   |
| Limoges          | 15        | 0.32%   |
| Besançon        | 15        | 0.32%   |
| Saint-Denis      | 14        | 0.3%    |
| Palaiseau        | 14        | 0.3%    |
| Clermont-Ferrand | 14        | 0.3%    |
| Argenteuil       | 14        | 0.3%    |
| Villejuif        | 13        | 0.27%   |
| Versailles       | 13        | 0.27%   |
| Pau              | 13        | 0.27%   |
| Orléans         | 13        | 0.27%   |
| Le Mans          | 13        | 0.27%   |
| Colmar           | 13        | 0.27%   |
| Valenciennes     | 12        | 0.25%   |
| Perpignan        | 12        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 811       | 1093   | 15.05%  |
| WDC                         | 598       | 739    | 11.1%   |
| Seagate                     | 586       | 746    | 10.88%  |
| Toshiba                     | 464       | 580    | 8.61%   |
| SanDisk                     | 333       | 409    | 6.18%   |
| Crucial                     | 326       | 409    | 6.05%   |
| SK hynix                    | 272       | 327    | 5.05%   |
| Unknown                     | 263       | 347    | 4.88%   |
| Kingston                    | 254       | 297    | 4.72%   |
| HGST                        | 235       | 284    | 4.36%   |
| Hitachi                     | 173       | 193    | 3.21%   |
| Micron Technology           | 155       | 181    | 2.88%   |
| Intel                       | 154       | 185    | 2.86%   |
| KIOXIA                      | 73        | 82     | 1.36%   |
| PNY                         | 46        | 49     | 0.85%   |
| Apple                       | 42        | 56     | 0.78%   |
| LDLC                        | 40        | 56     | 0.74%   |
| Fujitsu                     | 38        | 46     | 0.71%   |
| LITEON                      | 34        | 39     | 0.63%   |
| Transcend                   | 32        | 36     | 0.59%   |
| China                       | 27        | 30     | 0.5%    |
| Phison                      | 25        | 27     | 0.46%   |
| JMicron Technology          | 23        | 25     | 0.43%   |
| LITEONIT                    | 21        | 22     | 0.39%   |
| SPCC                        | 20        | 22     | 0.37%   |
| Corsair                     | 17        | 20     | 0.32%   |
| Micron/Crucial Technology   | 15        | 16     | 0.28%   |
| A-DATA Technology           | 14        | 19     | 0.26%   |
| Unknown                     | 13        | 14     | 0.24%   |
| Kingston Technology Company | 11        | 11     | 0.2%    |
| Silicon Motion              | 10        | 12     | 0.19%   |
| BHT                         | 10        | 13     | 0.19%   |
| SSSTC                       | 9         | 12     | 0.17%   |
| Netac                       | 9         | 10     | 0.17%   |
| Lite-On                     | 9         | 13     | 0.17%   |
| KingSpec                    | 8         | 9      | 0.15%   |
| YMTC                        | 7         | 8      | 0.13%   |
| Patriot                     | 7         | 8      | 0.13%   |
| OCZ                         | 7         | 11     | 0.13%   |
| Lenovo                      | 7         | 11     | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| HGST HTS721010A9E630 1TB               | 91        | 1.63%   |
| Seagate ST1000LM035-1RK172 1TB         | 89        | 1.6%    |
| Toshiba MQ01ABD100 1TB                 | 81        | 1.45%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 78        | 1.4%    |
| Crucial CT500MX500SSD1 500GB           | 62        | 1.11%   |
| Crucial CT240BX500SSD1 240GB           | 59        | 1.06%   |
| Unknown MMC Card  32GB                 | 51        | 0.91%   |
| Toshiba MQ04ABF100 1TB                 | 51        | 0.91%   |
| Samsung SSD 860 EVO 500GB              | 49        | 0.88%   |
| HGST HTS541010A9E680 1TB               | 46        | 0.82%   |
| Unknown MMC Card  64GB                 | 39        | 0.7%    |
| Kingston SA400S37240G 240GB SSD        | 38        | 0.68%   |
| SanDisk NVMe SSD Drive 512GB           | 37        | 0.66%   |
| Samsung NVMe SSD Drive 512GB           | 37        | 0.66%   |
| Seagate ST500LT012-1DG142 500GB        | 36        | 0.65%   |
| Seagate ST9500325AS 500GB              | 32        | 0.57%   |
| Seagate ST1000LM048-2E7172 1TB         | 30        | 0.54%   |
| Toshiba MQ01ABF050 500GB               | 27        | 0.48%   |
| KIOXIA KBG40ZNS512G NVMe 512GB         | 27        | 0.48%   |
| WDC WD10JPVX-22JC3T0 1TB               | 26        | 0.47%   |
| HGST HTS725050A7E630 500GB             | 26        | 0.47%   |
| Crucial CT1000MX500SSD1 1TB            | 26        | 0.47%   |
| Toshiba NVMe SSD Drive 512GB           | 25        | 0.45%   |
| Samsung SSD 850 EVO 500GB              | 25        | 0.45%   |
| Samsung SSD 870 QVO 1TB                | 24        | 0.43%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 24        | 0.43%   |
| Intel NVMe SSD Drive 512GB             | 23        | 0.41%   |
| Crucial CT120BX500SSD1 120GB           | 23        | 0.41%   |
| SK hynix NVMe SSD Drive 512GB          | 22        | 0.39%   |
| Seagate ST1000LM049-2GH172 1TB         | 22        | 0.39%   |
| Samsung SSD 860 EVO 1TB                | 22        | 0.39%   |
| Samsung SSD 850 EVO 250GB              | 21        | 0.38%   |
| Crucial CT480BX500SSD1 480GB           | 21        | 0.38%   |
| Samsung NVMe SSD Drive 1TB             | 20        | 0.36%   |
| SanDisk NVMe SSD Drive 256GB           | 19        | 0.34%   |
| Kingston SA400S37480G 480GB SSD        | 19        | 0.34%   |
| Unknown MMC Card  128GB                | 18        | 0.32%   |
| Seagate ST500LM021-1KJ152 500GB        | 18        | 0.32%   |
| Kingston SA400S37120G 120GB SSD        | 18        | 0.32%   |
| Intel SSDPEKNW512G8 512GB              | 18        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 579       | 733    | 31.54%  |
| WDC                 | 406       | 505    | 22.11%  |
| Toshiba             | 320       | 386    | 17.43%  |
| HGST                | 235       | 284    | 12.8%   |
| Hitachi             | 173       | 193    | 9.42%   |
| Samsung Electronics | 37        | 55     | 2.02%   |
| Fujitsu             | 37        | 45     | 2.02%   |
| Unknown             | 11        | 12     | 0.6%    |
| Apple               | 7         | 7      | 0.38%   |
| ASMT                | 6         | 7      | 0.33%   |
| SABRENT             | 5         | 5      | 0.27%   |
| IBM/Hitachi         | 5         | 6      | 0.27%   |
| JMicron Technology  | 3         | 4      | 0.16%   |
| HGST HTS            | 3         | 4      | 0.16%   |
| ASMedia             | 2         | 2      | 0.11%   |
| SILICONMOTION       | 1         | 1      | 0.05%   |
| PHD 3.0             | 1         | 1      | 0.05%   |
| Magnetic Data       | 1         | 1      | 0.05%   |
| LaCie               | 1         | 1      | 0.05%   |
| Intenso             | 1         | 1      | 0.05%   |
| Generic-            | 1         | 1      | 0.05%   |
| APPLE HD            | 1         | 1      | 0.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 395       | 519    | 22.64%  |
| Crucial             | 302       | 383    | 17.31%  |
| SanDisk             | 215       | 264    | 12.32%  |
| Kingston            | 191       | 225    | 10.95%  |
| Micron Technology   | 62        | 82     | 3.55%   |
| SK hynix            | 61        | 75     | 3.5%    |
| WDC                 | 45        | 51     | 2.58%   |
| Intel               | 42        | 43     | 2.41%   |
| PNY                 | 40        | 43     | 2.29%   |
| LDLC                | 34        | 48     | 1.95%   |
| Apple               | 32        | 44     | 1.83%   |
| Transcend           | 30        | 34     | 1.72%   |
| Toshiba             | 30        | 37     | 1.72%   |
| LITEON              | 29        | 32     | 1.66%   |
| China               | 26        | 29     | 1.49%   |
| LITEONIT            | 21        | 22     | 1.2%    |
| SPCC                | 17        | 19     | 0.97%   |
| JMicron Technology  | 11        | 11     | 0.63%   |
| A-DATA Technology   | 11        | 16     | 0.63%   |
| BHT                 | 10        | 13     | 0.57%   |
| KingSpec            | 8         | 9      | 0.46%   |
| Corsair             | 8         | 10     | 0.46%   |
| OCZ                 | 7         | 11     | 0.4%    |
| Netac               | 7         | 8      | 0.4%    |
| Emtec               | 7         | 7      | 0.4%    |
| Dogfish             | 7         | 10     | 0.4%    |
| Patriot             | 6         | 6      | 0.34%   |
| Plextor             | 5         | 6      | 0.29%   |
| Teclast             | 4         | 6      | 0.23%   |
| KingDian            | 4         | 5      | 0.23%   |
| Unknown             | 4         | 4      | 0.23%   |
| Unknown             | 3         | 4      | 0.17%   |
| TCSUNBOW            | 3         | 4      | 0.17%   |
| Intenso             | 3         | 3      | 0.17%   |
| BAITITON            | 3         | 3      | 0.17%   |
| Verbatim            | 2         | 2      | 0.11%   |
| Union Memory        | 2         | 2      | 0.11%   |
| Seagate             | 2         | 2      | 0.11%   |
| ORICO               | 2         | 2      | 0.11%   |
| NMICRO              | 2         | 2      | 0.11%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1782      | 2255   | 34.45%  |
| SSD     | 1616      | 2155   | 31.25%  |
| NVMe    | 1447      | 1840   | 27.98%  |
| MMC     | 263       | 357    | 5.09%   |
| Unknown | 64        | 70     | 1.24%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3023      | 4275   | 61.72%  |
| NVMe | 1446      | 1838   | 29.52%  |
| MMC  | 263       | 357    | 5.37%   |
| SAS  | 166       | 207    | 3.39%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2174      | 2879   | 64.22%  |
| 0.51-1.0   | 1111      | 1398   | 32.82%  |
| 1.01-2.0   | 79        | 108    | 2.33%   |
| 4.01-10.0  | 10        | 12     | 0.3%    |
| 3.01-4.0   | 7         | 8      | 0.21%   |
| 2.01-3.0   | 2         | 2      | 0.06%   |
| 10.01-20.0 | 2         | 3      | 0.06%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1292      | 28.18%  |
| 251-500        | 1205      | 26.28%  |
| 501-1000       | 767       | 16.73%  |
| 1-20           | 361       | 7.87%   |
| 51-100         | 287       | 6.26%   |
| 1001-2000      | 233       | 5.08%   |
| 21-50          | 200       | 4.36%   |
| Unknown        | 120       | 2.62%   |
| More than 3000 | 62        | 1.35%   |
| 2001-3000      | 58        | 1.26%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1871      | 39.27%  |
| 21-50          | 844       | 17.72%  |
| 101-250        | 663       | 13.92%  |
| 51-100         | 615       | 12.91%  |
| 251-500        | 362       | 7.6%    |
| 501-1000       | 192       | 4.03%   |
| Unknown        | 120       | 2.52%   |
| 1001-2000      | 56        | 1.18%   |
| 2001-3000      | 26        | 0.55%   |
| More than 3000 | 13        | 0.27%   |
| 0              | 2         | 0.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| HGST HTS721010A9E630 1TB                         | 17        | 20     | 4.24%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 11        | 11     | 2.74%   |
| HGST HTS541010A9E680 1TB                         | 11        | 11     | 2.74%   |
| Toshiba MQ01ABD100 1TB                           | 9         | 11     | 2.24%   |
| Seagate ST9500325AS 500GB                        | 9         | 10     | 2.24%   |
| Seagate ST500LM021-1KJ152 500GB                  | 8         | 10     | 2%      |
| Seagate ST500LT012-1DG142 500GB                  | 7         | 7      | 1.75%   |
| WDC WD10JPVX-22JC3T0 1TB                         | 6         | 6      | 1.5%    |
| Seagate ST1000LM035-1RK172 1TB                   | 6         | 6      | 1.5%    |
| Toshiba MQ01ABD050 500GB                         | 5         | 5      | 1.25%   |
| Hitachi HTS547575A9E384 752GB                    | 5         | 5      | 1.25%   |
| Toshiba MQ01ABF050 500GB                         | 4         | 4      | 1%      |
| Toshiba MK3265GSX 320GB                          | 4         | 5      | 1%      |
| SK hynix HFS256G39TND-N210A 256GB SSD            | 4         | 4      | 1%      |
| Seagate ST320LT007-9ZV142 320GB                  | 4         | 5      | 1%      |
| Hitachi HTS727575A9E364 752GB                    | 4         | 4      | 1%      |
| Hitachi HTS545050B9A300 500GB                    | 4         | 4      | 1%      |
| Hitachi HTS545050A7E380 500GB                    | 4         | 4      | 1%      |
| Hitachi HTS543232A7A384 320GB                    | 4         | 6      | 1%      |
| HGST HTS725050A7E630 500GB                       | 4         | 4      | 1%      |
| HGST HTS545050A7E680 500GB                       | 4         | 4      | 1%      |
| Crucial CT525MX300SSD1 528GB                     | 4         | 4      | 1%      |
| Toshiba MK5055GSX 500GB                          | 3         | 3      | 0.75%   |
| Toshiba MK3261GSYN 320GB                         | 3         | 3      | 0.75%   |
| Seagate ST9250827AS 250GB                        | 3         | 3      | 0.75%   |
| Seagate ST1000LM048-2E7172 1TB                   | 3         | 3      | 0.75%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 3         | 3      | 0.75%   |
| Hitachi HTS547550A9E384 500GB                    | 3         | 3      | 0.75%   |
| HGST HTS545050A7E380 500GB                       | 3         | 3      | 0.75%   |
| WDC WD5000BEKT-75KA9T0 500GB                     | 2         | 2      | 0.5%    |
| WDC WD3200BPVT-80ZEST0 320GB                     | 2         | 2      | 0.5%    |
| WDC WD10JPCX-24UE4T0 1TB                         | 2         | 2      | 0.5%    |
| Toshiba THNSNK256GCS8 SATA 256GB SSD             | 2         | 2      | 0.5%    |
| Toshiba MQ04ABF100 1TB                           | 2         | 2      | 0.5%    |
| Toshiba MQ01ABD075 752GB                         | 2         | 2      | 0.5%    |
| Toshiba MK8052GSX 80GB                           | 2         | 2      | 0.5%    |
| Toshiba MK7575GSX 752GB                          | 2         | 2      | 0.5%    |
| Toshiba MK5059GSXP 500GB                         | 2         | 2      | 0.5%    |
| Toshiba MK3252GSX 320GB                          | 2         | 2      | 0.5%    |
| Toshiba MK2552GSX 250GB                          | 2         | 2      | 0.5%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 85        | 95     | 21.25%  |
| Toshiba             | 54        | 58     | 13.5%   |
| Hitachi             | 49        | 51     | 12.25%  |
| WDC                 | 47        | 48     | 11.75%  |
| HGST                | 44        | 47     | 11%     |
| Samsung Electronics | 19        | 22     | 4.75%   |
| Crucial             | 16        | 16     | 4%      |
| SK hynix            | 15        | 17     | 3.75%   |
| SanDisk             | 15        | 16     | 3.75%   |
| Intel               | 13        | 13     | 3.25%   |
| Kingston            | 9         | 9      | 2.25%   |
| Fujitsu             | 6         | 6      | 1.5%    |
| Micron Technology   | 3         | 3      | 0.75%   |
| LITEONIT            | 2         | 2      | 0.5%    |
| LITEON              | 2         | 2      | 0.5%    |
| LDLC                | 2         | 4      | 0.5%    |
| Dogfish             | 2         | 2      | 0.5%    |
| Corsair             | 2         | 2      | 0.5%    |
| Unknown             | 1         | 1      | 0.25%   |
| TakeMS              | 1         | 1      | 0.25%   |
| Phison              | 1         | 1      | 0.25%   |
| OCZ                 | 1         | 1      | 0.25%   |
| Netac               | 1         | 1      | 0.25%   |
| Magnetic Data       | 1         | 1      | 0.25%   |
| KingSpec            | 1         | 1      | 0.25%   |
| JMicron Technology  | 1         | 1      | 0.25%   |
| Intenso             | 1         | 1      | 0.25%   |
| IBM/Hitachi         | 1         | 1      | 0.25%   |
| China               | 1         | 1      | 0.25%   |
| ASENNO              | 1         | 1      | 0.25%   |
| Apple               | 1         | 1      | 0.25%   |
| Apacer              | 1         | 1      | 0.25%   |
| A-DATA Technology   | 1         | 1      | 0.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 85        | 95     | 29.31%  |
| Toshiba             | 50        | 54     | 17.24%  |
| Hitachi             | 49        | 51     | 16.9%   |
| WDC                 | 45        | 46     | 15.52%  |
| HGST                | 44        | 47     | 15.17%  |
| Samsung Electronics | 8         | 8      | 2.76%   |
| Fujitsu             | 6         | 6      | 2.07%   |
| Unknown             | 1         | 1      | 0.34%   |
| Magnetic Data       | 1         | 1      | 0.34%   |
| IBM/Hitachi         | 1         | 1      | 0.34%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 287       | 310    | 72.47%  |
| SSD     | 98        | 104    | 24.75%  |
| NVMe    | 10        | 13     | 2.53%   |
| Unknown | 1         | 1      | 0.25%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD7500BPVT-22HXZT1 752GB          | 2         | 3      | 12.5%   |
| WDC WD3200BEVT-11ZCT0 320GB           | 2         | 2      | 12.5%   |
| WDC WD5000BEVT-35A0RT0 500GB          | 1         | 1      | 6.25%   |
| WDC WD10SPZX-21Z10T0 1TB              | 1         | 1      | 6.25%   |
| Toshiba MQ02ABF050H 500GB             | 1         | 1      | 6.25%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 6.25%   |
| Toshiba MQ01ABD075 752GB              | 1         | 1      | 6.25%   |
| Toshiba MK5055GSX 500GB               | 1         | 1      | 6.25%   |
| Toshiba MK3259GSXP 320GB              | 1         | 1      | 6.25%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 1         | 1      | 6.25%   |
| Seagate ST1000LM048-2E7172 1TB        | 1         | 1      | 6.25%   |
| Samsung Electronics HM251JI 250GB     | 1         | 1      | 6.25%   |
| HGST HTS721010A9E630 1TB              | 1         | 1      | 6.25%   |
| HGST HTS545050A7E380 500GB            | 1         | 1      | 6.25%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 7      | 37.5%   |
| Toshiba             | 5         | 5      | 31.25%  |
| HGST                | 2         | 2      | 12.5%   |
| SK hynix            | 1         | 1      | 6.25%   |
| Seagate             | 1         | 1      | 6.25%   |
| Samsung Electronics | 1         | 1      | 6.25%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2186      | 3447   | 46.5%   |
| Works    | 2110      | 2784   | 44.88%  |
| Malfunc  | 388       | 428    | 8.25%   |
| Failed   | 16        | 17     | 0.34%   |
| Limited  | 1         | 1      | 0.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 3136      | 61.12%  |
| AMD                                     | 496       | 9.67%   |
| Samsung Electronics                     | 418       | 8.15%   |
| SanDisk                                 | 250       | 4.87%   |
| SK hynix                                | 205       | 4%      |
| Toshiba America Info Systems            | 132       | 2.57%   |
| Micron Technology                       | 94        | 1.83%   |
| Kingston Technology Company             | 75        | 1.46%   |
| KIOXIA                                  | 67        | 1.31%   |
| Nvidia                                  | 47        | 0.92%   |
| Phison Electronics                      | 46        | 0.9%    |
| Micron/Crucial Technology               | 39        | 0.76%   |
| Silicon Motion                          | 14        | 0.27%   |
| Lite-On Technology                      | 14        | 0.27%   |
| Union Memory (Shenzhen)                 | 13        | 0.25%   |
| Silicon Integrated Systems [SiS]        | 13        | 0.25%   |
| Marvell Technology Group                | 11        | 0.21%   |
| Solid State Storage Technology          | 10        | 0.19%   |
| JMicron Technology                      | 10        | 0.19%   |
| Yangtze Memory Technologies             | 8         | 0.16%   |
| Lenovo                                  | 6         | 0.12%   |
| Apple                                   | 4         | 0.08%   |
| ADATA Technology                        | 4         | 0.08%   |
| VIA Technologies                        | 3         | 0.06%   |
| Silicon Image                           | 3         | 0.06%   |
| Seagate Technology                      | 3         | 0.06%   |
| O2 Micro                                | 3         | 0.06%   |
| ASMedia Technology                      | 3         | 0.06%   |
| Realtek Semiconductor                   | 2         | 0.04%   |
| ULi Electronics                         | 1         | 0.02%   |
| Shenzhen Unionmemory Information System | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 403       | 7.35%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 321       | 5.85%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 309       | 5.63%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 265       | 4.83%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 198       | 3.61%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 187       | 3.41%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 183       | 3.34%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 182       | 3.32%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 160       | 2.92%   |
| Intel Volume Management Device NVMe RAID Controller                              | 153       | 2.79%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 145       | 2.64%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 140       | 2.55%   |
| Samsung NVMe SSD Controller 980                                                  | 123       | 2.24%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 119       | 2.17%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 110       | 2.01%   |
| Micron Non-Volatile memory controller                                            | 94        | 1.71%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 94        | 1.71%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 83        | 1.51%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 73        | 1.33%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 73        | 1.33%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 70        | 1.28%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 63        | 1.15%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 61        | 1.11%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 61        | 1.11%   |
| SK hynix Non-Volatile memory controller                                          | 59        | 1.08%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 59        | 1.08%   |
| Intel Comet Lake SATA AHCI Controller                                            | 53        | 0.97%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 53        | 0.97%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 49        | 0.89%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 49        | 0.89%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 48        | 0.88%   |
| Intel Tiger Lake-LP SATA Controller                                              | 48        | 0.88%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 46        | 0.84%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 43        | 0.78%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 42        | 0.77%   |
| Intel SSD 660P Series                                                            | 42        | 0.77%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 42        | 0.77%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 40        | 0.73%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 39        | 0.71%   |
| SanDisk Non-Volatile memory controller                                           | 38        | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 3107      | 58.46%  |
| NVMe | 1462      | 27.51%  |
| RAID | 435       | 8.18%   |
| IDE  | 311       | 5.85%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 3694      | 84.05%  |
| AMD    | 699       | 15.9%   |
| ARM    | 2         | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 94        | 2.14%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 65        | 1.48%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 64        | 1.45%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 61        | 1.39%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 61        | 1.39%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 57        | 1.3%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 53        | 1.2%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 51        | 1.16%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 51        | 1.16%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 49        | 1.11%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 46        | 1.05%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 46        | 1.05%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 46        | 1.05%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 44        | 1%      |
| Intel Core i5-8265U CPU @ 1.60GHz             | 43        | 0.98%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 43        | 0.98%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 41        | 0.93%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 40        | 0.91%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 40        | 0.91%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 39        | 0.89%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 36        | 0.82%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 35        | 0.8%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 34        | 0.77%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 31        | 0.7%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 30        | 0.68%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 30        | 0.68%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 29        | 0.66%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 29        | 0.66%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 29        | 0.66%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 27        | 0.61%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 27        | 0.61%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 26        | 0.59%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 26        | 0.59%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 26        | 0.59%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 25        | 0.57%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 25        | 0.57%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 25        | 0.57%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 24        | 0.55%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 23        | 0.52%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 22        | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1076      | 24.47%  |
| Intel Core i7           | 969       | 22.03%  |
| Intel Core i3           | 375       | 8.53%   |
| Other                   | 367       | 8.34%   |
| Intel Celeron           | 251       | 5.71%   |
| Intel Core 2 Duo        | 243       | 5.53%   |
| AMD Ryzen 5             | 154       | 3.5%    |
| Intel Pentium           | 129       | 2.93%   |
| AMD Ryzen 7             | 120       | 2.73%   |
| Intel Atom              | 94        | 2.14%   |
| AMD E1                  | 52        | 1.18%   |
| Intel Pentium Dual-Core | 51        | 1.16%   |
| AMD A4                  | 36        | 0.82%   |
| AMD E2                  | 34        | 0.77%   |
| Intel Pentium Dual      | 31        | 0.7%    |
| AMD Ryzen 7 PRO         | 31        | 0.7%    |
| AMD A6                  | 31        | 0.7%    |
| Intel Core 2            | 26        | 0.59%   |
| Intel Core i9           | 25        | 0.57%   |
| AMD E                   | 25        | 0.57%   |
| AMD Ryzen 9             | 24        | 0.55%   |
| Intel Genuine           | 21        | 0.48%   |
| AMD A8                  | 18        | 0.41%   |
| AMD Ryzen 3             | 16        | 0.36%   |
| AMD Ryzen 5 PRO         | 14        | 0.32%   |
| AMD Athlon              | 14        | 0.32%   |
| Intel Xeon              | 13        | 0.3%    |
| Intel Pentium Silver    | 13        | 0.3%    |
| Intel Celeron Dual-Core | 11        | 0.25%   |
| AMD Athlon II           | 11        | 0.25%   |
| Intel Pentium M         | 10        | 0.23%   |
| Intel Core m3           | 9         | 0.2%    |
| AMD Athlon X2           | 9         | 0.2%    |
| Intel Celeron M         | 8         | 0.18%   |
| AMD Turion 64 X2 Mobile | 8         | 0.18%   |
| AMD Athlon II Dual-Core | 8         | 0.18%   |
| AMD Athlon 64 X2        | 7         | 0.16%   |
| AMD A12                 | 7         | 0.16%   |
| AMD C-60                | 6         | 0.14%   |
| AMD A10                 | 6         | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 2188      | 49.76%  |
| 4       | 1506      | 34.25%  |
| 6       | 307       | 6.98%   |
| 8       | 223       | 5.07%   |
| 1       | 110       | 2.5%    |
| 12      | 24        | 0.55%   |
| 14      | 18        | 0.41%   |
| 10      | 11        | 0.25%   |
| Unknown | 9         | 0.2%    |
| 3       | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 4393      | 99.93%  |
| 2      | 3         | 0.07%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 3139      | 71.29%  |
| 1       | 1254      | 28.48%  |
| Unknown | 9         | 0.2%    |
| 4       | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4311      | 97.93%  |
| Unknown        | 48        | 1.09%   |
| 32-bit         | 41        | 0.93%   |
| 64-bit         | 2         | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 797       | 17.61%  |
| 0x306a9    | 274       | 6.06%   |
| 0x206a7    | 265       | 5.86%   |
| 0x806c1    | 182       | 4.02%   |
| 0x806ec    | 178       | 3.93%   |
| 0x1067a    | 166       | 3.67%   |
| 0x906ea    | 165       | 3.65%   |
| 0x40651    | 141       | 3.12%   |
| 0x306d4    | 137       | 3.03%   |
| 0x306c3    | 137       | 3.03%   |
| 0x406e3    | 136       | 3.01%   |
| 0x806ea    | 135       | 2.98%   |
| 0x806e9    | 115       | 2.54%   |
| 0x20655    | 113       | 2.5%    |
| 0x6fd      | 83        | 1.83%   |
| 0x506e3    | 76        | 1.68%   |
| 0xa0652    | 74        | 1.64%   |
| 0x906e9    | 67        | 1.48%   |
| 0x08600106 | 62        | 1.37%   |
| 0x08108109 | 59        | 1.3%    |
| 0x10676    | 52        | 1.15%   |
| 0x30678    | 51        | 1.13%   |
| 0x706e5    | 48        | 1.06%   |
| 0x406c4    | 47        | 1.04%   |
| 0x806d1    | 46        | 1.02%   |
| 0x406c3    | 40        | 0.88%   |
| 0x07030105 | 40        | 0.88%   |
| 0x806eb    | 39        | 0.86%   |
| 0x706a1    | 39        | 0.86%   |
| 0x08108102 | 38        | 0.84%   |
| 0x0a50000c | 37        | 0.82%   |
| 0x906a3    | 35        | 0.77%   |
| 0x506c9    | 35        | 0.77%   |
| 0x20652    | 34        | 0.75%   |
| 0x06006705 | 32        | 0.71%   |
| 0x05000119 | 32        | 0.71%   |
| 0x906ed    | 30        | 0.66%   |
| 0x0700010f | 26        | 0.57%   |
| 0x706a8    | 24        | 0.53%   |
| 0x08600104 | 23        | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 887       | 20.17%  |
| Haswell          | 342       | 7.78%   |
| IvyBridge        | 319       | 7.25%   |
| SandyBridge      | 296       | 6.73%   |
| Skylake          | 259       | 5.89%   |
| Penryn           | 247       | 5.62%   |
| TigerLake        | 218       | 4.96%   |
| Silvermont       | 173       | 3.93%   |
| Westmere         | 168       | 3.82%   |
| Broadwell        | 160       | 3.64%   |
| Core             | 157       | 3.57%   |
| Zen 2            | 127       | 2.89%   |
| Zen+             | 109       | 2.48%   |
| Icelake          | 104       | 2.36%   |
| CometLake        | 97        | 2.21%   |
| Unknown          | 88        | 2%      |
| Goldmont plus    | 73        | 1.66%   |
| Puma             | 63        | 1.43%   |
| Zen 3            | 61        | 1.39%   |
| Bobcat           | 60        | 1.36%   |
| Excavator        | 53        | 1.21%   |
| Goldmont         | 44        | 1%      |
| Alderlake Hybrid | 41        | 0.93%   |
| Bonnell          | 40        | 0.91%   |
| Jaguar           | 38        | 0.86%   |
| Zen              | 33        | 0.75%   |
| K10              | 28        | 0.64%   |
| K8 Hammer        | 25        | 0.57%   |
| P6               | 22        | 0.5%    |
| Nehalem          | 18        | 0.41%   |
| Piledriver       | 14        | 0.32%   |
| K8 & K10 hybrid  | 12        | 0.27%   |
| K10 Llano        | 12        | 0.27%   |
| Tremont          | 4         | 0.09%   |
| NetBurst         | 3         | 0.07%   |
| Steamroller      | 2         | 0.05%   |
| K6               | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3313      | 58.34%  |
| Nvidia                           | 1379      | 24.28%  |
| AMD                              | 977       | 17.2%   |
| Silicon Integrated Systems [SiS] | 8         | 0.14%   |
| VIA Technologies                 | 2         | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 294       | 5.03%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 265       | 4.53%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 209       | 3.58%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 207       | 3.54%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 164       | 2.81%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 151       | 2.58%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 150       | 2.57%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 149       | 2.55%   |
| Intel UHD Graphics 620                                                                   | 146       | 2.5%    |
| Intel HD Graphics 5500                                                                   | 141       | 2.41%   |
| Intel HD Graphics 620                                                                    | 138       | 2.36%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 136       | 2.33%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 126       | 2.16%   |
| AMD Renoir                                                                               | 123       | 2.1%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 110       | 1.88%   |
| Intel Core Processor Integrated Graphics Controller                                      | 108       | 1.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 95        | 1.63%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 89        | 1.52%   |
| Intel HD Graphics 530                                                                    | 83        | 1.42%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 80        | 1.37%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 78        | 1.33%   |
| Intel HD Graphics 630                                                                    | 73        | 1.25%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 64        | 1.09%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 64        | 1.09%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 61        | 1.04%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 55        | 0.94%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 53        | 0.91%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 50        | 0.86%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 49        | 0.84%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 47        | 0.8%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 43        | 0.74%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 43        | 0.74%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 43        | 0.74%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 42        | 0.72%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 40        | 0.68%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 38        | 0.65%   |
| Nvidia GM108M [GeForce 840M]                                                             | 37        | 0.63%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 36        | 0.62%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 36        | 0.62%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 34        | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 2105      | 47.76%  |
| Intel + Nvidia     | 1035      | 23.49%  |
| 1 x AMD            | 662       | 15.02%  |
| 1 x Nvidia         | 260       | 5.9%    |
| Intel + AMD        | 166       | 3.77%   |
| AMD + Nvidia       | 78        | 1.77%   |
| 2 x AMD            | 72        | 1.63%   |
| 2 x Intel          | 8         | 0.18%   |
| 1 x SiS            | 8         | 0.18%   |
| 2 x Nvidia         | 6         | 0.14%   |
| Other              | 4         | 0.09%   |
| 1 x VIA            | 2         | 0.05%   |
| Intel + 2 x Nvidia | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 3748      | 84.47%  |
| Proprietary | 579       | 13.05%  |
| Unknown     | 110       | 2.48%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2716      | 60.56%  |
| 0.01-0.5   | 604       | 13.47%  |
| 1.01-2.0   | 518       | 11.55%  |
| 0.51-1.0   | 262       | 5.84%   |
| 3.01-4.0   | 252       | 5.62%   |
| 5.01-6.0   | 72        | 1.61%   |
| 7.01-8.0   | 37        | 0.82%   |
| 2.01-3.0   | 22        | 0.49%   |
| 8.01-16.0  | 2         | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 1036      | 20.69%  |
| Chimei Innolux          | 660       | 13.18%  |
| LG Display              | 659       | 13.16%  |
| BOE                     | 589       | 11.76%  |
| Samsung Electronics     | 527       | 10.52%  |
| Sharp                   | 163       | 3.25%   |
| Chi Mei Optoelectronics | 138       | 2.76%   |
| Dell                    | 132       | 2.64%   |
| Iiyama                  | 101       | 2.02%   |
| Lenovo                  | 90        | 1.8%    |
| Apple                   | 90        | 1.8%    |
| PANDA                   | 69        | 1.38%   |
| Acer                    | 65        | 1.3%    |
| LG Philips              | 63        | 1.26%   |
| Hewlett-Packard         | 63        | 1.26%   |
| InfoVision              | 56        | 1.12%   |
| Goldstar                | 52        | 1.04%   |
| BenQ                    | 41        | 0.82%   |
| Ancor Communications    | 41        | 0.82%   |
| Philips                 | 35        | 0.7%    |
| AOC                     | 35        | 0.7%    |
| ViewSonic               | 28        | 0.56%   |
| CSO                     | 20        | 0.4%    |
| CPT                     | 18        | 0.36%   |
| ASUSTek Computer        | 17        | 0.34%   |
| HannStar                | 14        | 0.28%   |
| Sony                    | 13        | 0.26%   |
| Fujitsu Siemens         | 13        | 0.26%   |
| Vestel Elektronik       | 9         | 0.18%   |
| Seiko/Epson             | 9         | 0.18%   |
| Analogix                | 9         | 0.18%   |
| Toshiba                 | 8         | 0.16%   |
| LGD                     | 7         | 0.14%   |
| ANX                     | 7         | 0.14%   |
| Unknown                 | 6         | 0.12%   |
| TMX                     | 5         | 0.1%    |
| Panasonic               | 5         | 0.1%    |
| LPL                     | 5         | 0.1%    |
| Quanta Display          | 4         | 0.08%   |
| Packard Bell            | 4         | 0.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 44        | 0.87%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 34        | 0.67%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 33        | 0.65%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 29        | 0.57%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch      | 25        | 0.49%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch            | 25        | 0.49%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch            | 25        | 0.49%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 25        | 0.49%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 24        | 0.47%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 24        | 0.47%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 23        | 0.45%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch             | 23        | 0.45%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch           | 22        | 0.43%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 21        | 0.41%   |
| AU Optronics LCD Monitor AUO139E 1600x900 380x210mm 17.1-inch             | 20        | 0.4%    |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch          | 19        | 0.38%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 382x214mm 17.2-inch           | 19        | 0.38%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch             | 19        | 0.38%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 18        | 0.36%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch           | 17        | 0.34%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 17        | 0.34%   |
| AU Optronics LCD Monitor AUO109E 1600x900 382x214mm 17.2-inch             | 17        | 0.34%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 16        | 0.32%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch  | 16        | 0.32%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch             | 16        | 0.32%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch            | 16        | 0.32%   |
| AU Optronics LCD Monitor AUO119E 1600x900 382x214mm 17.2-inch             | 15        | 0.3%    |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                   | 14        | 0.28%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                   | 14        | 0.28%   |
| Samsung Electronics LCD Monitor SDC4852 3840x2160 340x190mm 15.3-inch     | 14        | 0.28%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch          | 14        | 0.28%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch             | 14        | 0.28%   |
| AU Optronics LCD Monitor AUO219E 1600x900 382x214mm 17.2-inch             | 14        | 0.28%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                   | 13        | 0.26%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch               | 13        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 13        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 13        | 0.26%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                     | 13        | 0.26%   |
| AU Optronics LCD Monitor AUO6287 1440x900 367x229mm 17.0-inch             | 13        | 0.26%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 13        | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2027      | 43.61%  |
| 1366x768 (WXGA)    | 1152      | 24.78%  |
| 1600x900 (HD+)     | 453       | 9.75%   |
| 1280x800 (WXGA)    | 180       | 3.87%   |
| 3840x2160 (4K)     | 147       | 3.16%   |
| 1440x900 (WXGA+)   | 114       | 2.45%   |
| 1920x1200 (WUXGA)  | 109       | 2.35%   |
| 2560x1440 (QHD)    | 100       | 2.15%   |
| 1680x1050 (WSXGA+) | 55        | 1.18%   |
| 1024x600           | 32        | 0.69%   |
| 1280x1024 (SXGA)   | 29        | 0.62%   |
| 2560x1600          | 26        | 0.56%   |
| 2880x1800          | 22        | 0.47%   |
| 3440x1440          | 20        | 0.43%   |
| 800x1280           | 18        | 0.39%   |
| 2160x1440          | 18        | 0.39%   |
| 3840x2400          | 17        | 0.37%   |
| 2560x1080          | 14        | 0.3%    |
| 3200x1800 (QHD+)   | 11        | 0.24%   |
| Unknown            | 11        | 0.24%   |
| 1360x768           | 10        | 0.22%   |
| 3840x1080          | 7         | 0.15%   |
| 3000x2000          | 7         | 0.15%   |
| 1920x540           | 7         | 0.15%   |
| 1600x1200          | 7         | 0.15%   |
| 1680x945           | 6         | 0.13%   |
| 1024x768 (XGA)     | 6         | 0.13%   |
| 3840x1200          | 4         | 0.09%   |
| 2288x1287          | 4         | 0.09%   |
| 1920x515           | 4         | 0.09%   |
| 1400x1050          | 4         | 0.09%   |
| 3072x1920          | 3         | 0.06%   |
| 2256x1504          | 3         | 0.06%   |
| 5760x2160          | 2         | 0.04%   |
| 3840x1600          | 2         | 0.04%   |
| 3286x1080          | 2         | 0.04%   |
| 2048x1152          | 2         | 0.04%   |
| 720x1280           | 1         | 0.02%   |
| 4480x1600          | 1         | 0.02%   |
| 4480x1440          | 1         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1864      | 37.26%  |
| 13      | 698       | 13.95%  |
| 17      | 696       | 13.91%  |
| 14      | 493       | 9.85%   |
| 24      | 214       | 4.28%   |
| 23      | 155       | 3.1%    |
| 12      | 139       | 2.78%   |
| 27      | 137       | 2.74%   |
| 21      | 100       | 2%      |
| Unknown | 83        | 1.66%   |
| 11      | 63        | 1.26%   |
| 16      | 47        | 0.94%   |
| 18      | 43        | 0.86%   |
| 10      | 43        | 0.86%   |
| 19      | 34        | 0.68%   |
| 22      | 33        | 0.66%   |
| 34      | 32        | 0.64%   |
| 20      | 19        | 0.38%   |
| 31      | 17        | 0.34%   |
| 84      | 14        | 0.28%   |
| 72      | 13        | 0.26%   |
| 25      | 9         | 0.18%   |
| 40      | 7         | 0.14%   |
| 54      | 6         | 0.12%   |
| 32      | 6         | 0.12%   |
| 52      | 4         | 0.08%   |
| 33      | 4         | 0.08%   |
| 26      | 4         | 0.08%   |
| 49      | 3         | 0.06%   |
| 43      | 3         | 0.06%   |
| 142     | 2         | 0.04%   |
| 48      | 2         | 0.04%   |
| 46      | 2         | 0.04%   |
| 28      | 2         | 0.04%   |
| 7       | 2         | 0.04%   |
| 74      | 1         | 0.02%   |
| 64      | 1         | 0.02%   |
| 50      | 1         | 0.02%   |
| 47      | 1         | 0.02%   |
| 41      | 1         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 2644      | 53.37%  |
| 351-400        | 786       | 15.87%  |
| 201-300        | 622       | 12.56%  |
| 501-600        | 466       | 9.41%   |
| 401-500        | 211       | 4.26%   |
| Unknown        | 83        | 1.68%   |
| 701-800        | 41        | 0.83%   |
| 601-700        | 33        | 0.67%   |
| 1501-2000      | 28        | 0.57%   |
| 1001-1500      | 22        | 0.44%   |
| 801-900        | 11        | 0.22%   |
| More than 2000 | 2         | 0.04%   |
| 101-200        | 2         | 0.04%   |
| 1-100          | 2         | 0.04%   |
| 901-1000       | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 3675      | 83.6%   |
| 16/10   | 515       | 11.72%  |
| Unknown | 42        | 0.96%   |
| 3/2     | 40        | 0.91%   |
| 21/9    | 36        | 0.82%   |
| 5/4     | 29        | 0.66%   |
| 4/3     | 23        | 0.52%   |
| 0.62    | 17        | 0.39%   |
| 32/9    | 6         | 0.14%   |
| 3.20    | 4         | 0.09%   |
| 3.73    | 3         | 0.07%   |
| 1.00    | 2         | 0.05%   |
| 0.67    | 2         | 0.05%   |
| 3.88    | 1         | 0.02%   |
| 0.56    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1881      | 37.69%  |
| 81-90          | 872       | 17.47%  |
| 121-130        | 581       | 11.64%  |
| 201-250        | 404       | 8.09%   |
| 71-80          | 322       | 6.45%   |
| 301-350        | 140       | 2.81%   |
| 61-70          | 129       | 2.58%   |
| 131-140        | 104       | 2.08%   |
| 151-200        | 85        | 1.7%    |
| Unknown        | 83        | 1.66%   |
| 251-300        | 70        | 1.4%    |
| 51-60          | 63        | 1.26%   |
| 351-500        | 61        | 1.22%   |
| 141-150        | 48        | 0.96%   |
| 41-50          | 44        | 0.88%   |
| More than 1000 | 42        | 0.84%   |
| 111-120        | 25        | 0.5%    |
| 501-1000       | 20        | 0.4%    |
| 91-100         | 13        | 0.26%   |
| 1-40           | 4         | 0.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1924      | 39.23%  |
| 101-120       | 1525      | 31.1%   |
| 51-100        | 883       | 18.01%  |
| 161-240       | 332       | 6.77%   |
| More than 240 | 124       | 2.53%   |
| Unknown       | 83        | 1.69%   |
| 1-50          | 33        | 0.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 3580      | 79.68%  |
| 2     | 702       | 15.62%  |
| 0     | 118       | 2.63%   |
| 3     | 86        | 1.91%   |
| 4     | 5         | 0.11%   |
| 6     | 1         | 0.02%   |
| 5     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 2390      | 34.17%  |
| Realtek Semiconductor             | 2254      | 32.22%  |
| Qualcomm Atheros                  | 1089      | 15.57%  |
| Broadcom                          | 465       | 6.65%   |
| Broadcom Limited                  | 97        | 1.39%   |
| Marvell Technology Group          | 88        | 1.26%   |
| Ralink                            | 73        | 1.04%   |
| MediaTek                          | 73        | 1.04%   |
| Dell                              | 42        | 0.6%    |
| ASIX Electronics                  | 36        | 0.51%   |
| Nvidia                            | 32        | 0.46%   |
| Samsung Electronics               | 30        | 0.43%   |
| Ericsson Business Mobile Networks | 26        | 0.37%   |
| Xiaomi                            | 24        | 0.34%   |
| DisplayLink                       | 23        | 0.33%   |
| Sierra Wireless                   | 21        | 0.3%    |
| TP-Link                           | 20        | 0.29%   |
| Lenovo                            | 17        | 0.24%   |
| Huawei Technologies               | 17        | 0.24%   |
| JMicron Technology                | 16        | 0.23%   |
| Ralink Technology                 | 15        | 0.21%   |
| Qualcomm                          | 15        | 0.21%   |
| NetGear                           | 15        | 0.21%   |
| Attansic Technology               | 14        | 0.2%    |
| Hewlett-Packard                   | 11        | 0.16%   |
| Silicon Integrated Systems [SiS]  | 10        | 0.14%   |
| OPPO Electronics                  | 6         | 0.09%   |
| Google                            | 6         | 0.09%   |
| Fibocom                           | 5         | 0.07%   |
| Apple                             | 5         | 0.07%   |
| Toshiba                           | 4         | 0.06%   |
| OnePlus Technology (Shenzhen)     | 4         | 0.06%   |
| ICS Advent                        | 4         | 0.06%   |
| D-Link                            | 4         | 0.06%   |
| VIA Technologies                  | 3         | 0.04%   |
| U-Blox                            | 3         | 0.04%   |
| D-Link System                     | 3         | 0.04%   |
| Belkin Components                 | 3         | 0.04%   |
| Arduino SA                        | 3         | 0.04%   |
| Shenzhen Goodix Technology        | 2         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1347      | 15.97%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 368       | 4.36%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 243       | 2.88%   |
| Intel Wi-Fi 6 AX200                                               | 209       | 2.48%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 181       | 2.15%   |
| Intel Wireless 8265 / 8275                                        | 181       | 2.15%   |
| Intel Wi-Fi 6 AX201                                               | 168       | 1.99%   |
| Intel Wireless 7265                                               | 162       | 1.92%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 158       | 1.87%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 155       | 1.84%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 144       | 1.71%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 138       | 1.64%   |
| Intel Wireless 8260                                               | 133       | 1.58%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 133       | 1.58%   |
| Intel Wireless 7260                                               | 129       | 1.53%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 107       | 1.27%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 107       | 1.27%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 105       | 1.25%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 101       | 1.2%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 95        | 1.13%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 89        | 1.06%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 89        | 1.06%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 84        | 1%      |
| Intel Comet Lake PCH CNVi WiFi                                    | 80        | 0.95%   |
| Intel Wireless 3165                                               | 70        | 0.83%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 65        | 0.77%   |
| Broadcom BCM43142 802.11b/g/n                                     | 65        | 0.77%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 62        | 0.74%   |
| Intel Ethernet Connection (4) I219-LM                             | 61        | 0.72%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 58        | 0.69%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 57        | 0.68%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 53        | 0.63%   |
| Intel Ethernet Connection I219-LM                                 | 53        | 0.63%   |
| Intel Ethernet Connection (3) I218-LM                             | 53        | 0.63%   |
| Intel WiFi Link 5100                                              | 50        | 0.59%   |
| Intel Wireless-AC 9260                                            | 49        | 0.58%   |
| Intel Wireless 3160                                               | 47        | 0.56%   |
| Intel Centrino Wireless-N 2230                                    | 46        | 0.55%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 46        | 0.55%   |
| Intel Ethernet Connection I217-LM                                 | 45        | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2269      | 50.59%  |
| Qualcomm Atheros                      | 895       | 19.96%  |
| Realtek Semiconductor                 | 648       | 14.45%  |
| Broadcom                              | 336       | 7.49%   |
| Ralink                                | 73        | 1.63%   |
| MediaTek                              | 67        | 1.49%   |
| Broadcom Limited                      | 65        | 1.45%   |
| Sierra Wireless                       | 21        | 0.47%   |
| Dell                                  | 21        | 0.47%   |
| TP-Link                               | 16        | 0.36%   |
| Ralink Technology                     | 15        | 0.33%   |
| NetGear                               | 12        | 0.27%   |
| Qualcomm                              | 10        | 0.22%   |
| Ericsson Business Mobile Networks     | 7         | 0.16%   |
| Hewlett-Packard                       | 5         | 0.11%   |
| Fibocom                               | 5         | 0.11%   |
| D-Link System                         | 3         | 0.07%   |
| D-Link                                | 3         | 0.07%   |
| Belkin Components                     | 3         | 0.07%   |
| ASUSTek Computer                      | 2         | 0.04%   |
| ZyDAS                                 | 1         | 0.02%   |
| Texas Instruments                     | 1         | 0.02%   |
| Sagem                                 | 1         | 0.02%   |
| Qualcomm Atheros Communications       | 1         | 0.02%   |
| Microsoft                             | 1         | 0.02%   |
| Guillemot                             | 1         | 0.02%   |
| Edimax Technology                     | 1         | 0.02%   |
| Accton Technology                     | 1         | 0.02%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 209       | 4.64%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 181       | 4.01%   |
| Intel Wireless 8265 / 8275                                              | 181       | 4.01%   |
| Intel Wi-Fi 6 AX201                                                     | 168       | 3.73%   |
| Intel Wireless 7265                                                     | 162       | 3.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 158       | 3.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 144       | 3.19%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 138       | 3.06%   |
| Intel Wireless 8260                                                     | 133       | 2.95%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 133       | 2.95%   |
| Intel Wireless 7260                                                     | 129       | 2.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 107       | 2.37%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 107       | 2.37%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 105       | 2.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 101       | 2.24%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 95        | 2.11%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 89        | 1.97%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 89        | 1.97%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 84        | 1.86%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 80        | 1.77%   |
| Intel Wireless 3165                                                     | 70        | 1.55%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 65        | 1.44%   |
| Broadcom BCM43142 802.11b/g/n                                           | 65        | 1.44%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 58        | 1.29%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 53        | 1.18%   |
| Intel WiFi Link 5100                                                    | 50        | 1.11%   |
| Intel Wireless-AC 9260                                                  | 49        | 1.09%   |
| Intel Wireless 3160                                                     | 47        | 1.04%   |
| Intel Centrino Wireless-N 2230                                          | 46        | 1.02%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 46        | 1.02%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 44        | 0.98%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 43        | 0.95%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 40        | 0.89%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 38        | 0.84%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 38        | 0.84%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 37        | 0.82%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 37        | 0.82%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 33        | 0.73%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 32        | 0.71%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 31        | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 2025      | 53.29%  |
| Intel                            | 862       | 22.68%  |
| Qualcomm Atheros                 | 341       | 8.97%   |
| Broadcom                         | 179       | 4.71%   |
| Marvell Technology Group         | 88        | 2.32%   |
| ASIX Electronics                 | 36        | 0.95%   |
| Broadcom Limited                 | 35        | 0.92%   |
| Nvidia                           | 32        | 0.84%   |
| Samsung Electronics              | 29        | 0.76%   |
| Xiaomi                           | 24        | 0.63%   |
| DisplayLink                      | 23        | 0.61%   |
| Lenovo                           | 17        | 0.45%   |
| JMicron Technology               | 16        | 0.42%   |
| Attansic Technology              | 14        | 0.37%   |
| Huawei Technologies              | 11        | 0.29%   |
| Silicon Integrated Systems [SiS] | 10        | 0.26%   |
| OPPO Electronics                 | 6         | 0.16%   |
| MediaTek                         | 6         | 0.16%   |
| Google                           | 6         | 0.16%   |
| Qualcomm                         | 5         | 0.13%   |
| Apple                            | 5         | 0.13%   |
| TP-Link                          | 4         | 0.11%   |
| ICS Advent                       | 4         | 0.11%   |
| NetGear                          | 3         | 0.08%   |
| VIA Technologies                 | 2         | 0.05%   |
| OnePlus Technology (Shenzhen)    | 2         | 0.05%   |
| Linksys                          | 2         | 0.05%   |
| Cypress Semiconductor            | 2         | 0.05%   |
| Aquantia                         | 2         | 0.05%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.03%   |
| ULi Electronics                  | 1         | 0.03%   |
| Motorola PCS                     | 1         | 0.03%   |
| Microchip Technology             | 1         | 0.03%   |
| Hisense                          | 1         | 0.03%   |
| Hewlett-Packard                  | 1         | 0.03%   |
| Davicom Semiconductor            | 1         | 0.03%   |
| D-Link                           | 1         | 0.03%   |
| Archos                           | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1347      | 35.11%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 368       | 9.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 243       | 6.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 155       | 4.04%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 62        | 1.62%   |
| Intel Ethernet Connection (4) I219-LM                             | 61        | 1.59%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 57        | 1.49%   |
| Intel Ethernet Connection I219-LM                                 | 53        | 1.38%   |
| Intel Ethernet Connection (3) I218-LM                             | 53        | 1.38%   |
| Intel Ethernet Connection I217-LM                                 | 45        | 1.17%   |
| Intel Ethernet Connection I218-LM                                 | 41        | 1.07%   |
| Intel 82577LM Gigabit Network Connection                          | 39        | 1.02%   |
| Intel 82567LM Gigabit Network Connection                          | 36        | 0.94%   |
| ASIX AX88179 Gigabit Ethernet                                     | 32        | 0.83%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 31        | 0.81%   |
| Intel Ethernet Connection (6) I219-V                              | 31        | 0.81%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 30        | 0.78%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 30        | 0.78%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 28        | 0.73%   |
| Intel Ethernet Connection I219-V                                  | 27        | 0.7%    |
| Intel Ethernet Connection (7) I219-LM                             | 27        | 0.7%    |
| Intel Ethernet Connection I217-V                                  | 26        | 0.68%   |
| Intel Ethernet Connection (4) I219-V                              | 26        | 0.68%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 26        | 0.68%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 24        | 0.63%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 24        | 0.63%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 23        | 0.6%    |
| Intel Ethernet Connection (6) I219-LM                             | 23        | 0.6%    |
| Intel Ethernet Connection (13) I219-V                             | 23        | 0.6%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 22        | 0.57%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 21        | 0.55%   |
| Nvidia MCP79 Ethernet                                             | 21        | 0.55%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 20        | 0.52%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 18        | 0.47%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 18        | 0.47%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 18        | 0.47%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 17        | 0.44%   |
| Intel Ethernet Connection (2) I219-LM                             | 17        | 0.44%   |
| Intel Ethernet Connection (13) I219-LM                            | 17        | 0.44%   |
| Intel Ethernet Connection (11) I219-LM                            | 17        | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 4318      | 53.85%  |
| Ethernet | 3614      | 45.07%  |
| Modem    | 81        | 1.01%   |
| Unknown  | 6         | 0.07%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3470      | 74.45%  |
| Ethernet | 1191      | 25.55%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 3249      | 73.82%  |
| 1     | 1047      | 23.79%  |
| 0     | 63        | 1.43%   |
| 3     | 42        | 0.95%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2979      | 65.97%  |
| Yes  | 1537      | 34.03%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1750      | 51.87%  |
| Realtek Semiconductor           | 272       | 8.06%   |
| IMC Networks                    | 257       | 7.62%   |
| Qualcomm Atheros Communications | 231       | 6.85%   |
| Broadcom                        | 175       | 5.19%   |
| Lite-On Technology              | 127       | 3.76%   |
| Foxconn / Hon Hai               | 114       | 3.38%   |
| Apple                           | 90        | 2.67%   |
| Dell                            | 79        | 2.34%   |
| Cambridge Silicon Radio         | 53        | 1.57%   |
| Realtek                         | 39        | 1.16%   |
| Hewlett-Packard                 | 37        | 1.1%    |
| Toshiba                         | 36        | 1.07%   |
| Ralink                          | 31        | 0.92%   |
| ASUSTek Computer                | 21        | 0.62%   |
| Ralink Technology               | 19        | 0.56%   |
| Foxconn International           | 13        | 0.39%   |
| Alps Electric                   | 13        | 0.39%   |
| MediaTek                        | 5         | 0.15%   |
| Chicony Electronics             | 5         | 0.15%   |
| USI                             | 2         | 0.06%   |
| TP-Link                         | 1         | 0.03%   |
| Syntek                          | 1         | 0.03%   |
| Integrated System Solution      | 1         | 0.03%   |
| Fujitsu                         | 1         | 0.03%   |
| Corsair                         | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 688       | 20.39%  |
| Intel Bluetooth Device                              | 412       | 12.21%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 277       | 8.21%   |
| Intel AX200 Bluetooth                               | 198       | 5.87%   |
| Realtek Bluetooth Radio                             | 167       | 4.95%   |
| IMC Networks Bluetooth Device                       | 102       | 3.02%   |
| Qualcomm Atheros  Bluetooth Device                  | 93        | 2.76%   |
| Lite-On Bluetooth Device                            | 84        | 2.49%   |
| IMC Networks Bluetooth Radio                        | 74        | 2.19%   |
| Realtek  Bluetooth 4.2 Adapter                      | 70        | 2.07%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 66        | 1.96%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 53        | 1.57%   |
| Foxconn / Hon Hai Bluetooth Device                  | 52        | 1.54%   |
| Apple Bluetooth Host Controller                     | 48        | 1.42%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 44        | 1.3%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 41        | 1.21%   |
| Realtek Bluetooth Radio                             | 39        | 1.16%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 37        | 1.1%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 35        | 1.04%   |
| Dell DW375 Bluetooth Module                         | 35        | 1.04%   |
| Ralink RT3290 Bluetooth                             | 31        | 0.92%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 27        | 0.8%    |
| Broadcom BCM2045B (BDC-2.1)                         | 27        | 0.8%    |
| Apple Bluetooth USB Host Controller                 | 26        | 0.77%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 25        | 0.74%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 24        | 0.71%   |
| Intel AX210 Bluetooth                               | 23        | 0.68%   |
| IMC Networks Wireless_Device                        | 23        | 0.68%   |
| Foxconn / Hon Hai Wireless_Device                   | 23        | 0.68%   |
| Lite-On Atheros AR3012 Bluetooth                    | 22        | 0.65%   |
| HP Broadcom 2070 Bluetooth Combo                    | 20        | 0.59%   |
| Intel Wireless-AC 3168 Bluetooth                    | 18        | 0.53%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 18        | 0.53%   |
| Realtek RTL8723B Bluetooth                          | 17        | 0.5%    |
| Dell BCM20702A0 Bluetooth Module                    | 17        | 0.5%    |
| IMC Networks Bluetooth                              | 15        | 0.44%   |
| Broadcom HP Portable SoftSailing                    | 15        | 0.44%   |
| Broadcom BCM43142A0 Bluetooth Device                | 15        | 0.44%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 15        | 0.44%   |
| Toshiba Bluetooth Device                            | 14        | 0.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 3587      | 65.88%  |
| AMD                                          | 823       | 15.11%  |
| Nvidia                                       | 676       | 12.42%  |
| Realtek Semiconductor                        | 56        | 1.03%   |
| GN Netcom                                    | 31        | 0.57%   |
| Logitech                                     | 29        | 0.53%   |
| C-Media Electronics                          | 29        | 0.53%   |
| Plantronics                                  | 22        | 0.4%    |
| JMTek                                        | 19        | 0.35%   |
| Kingston Technology                          | 18        | 0.33%   |
| Lenovo                                       | 16        | 0.29%   |
| Silicon Integrated Systems [SiS]             | 12        | 0.22%   |
| Hewlett-Packard                              | 12        | 0.22%   |
| Corsair                                      | 12        | 0.22%   |
| SteelSeries ApS                              | 6         | 0.11%   |
| Focusrite-Novation                           | 5         | 0.09%   |
| Texas Instruments                            | 4         | 0.07%   |
| Sennheiser Communications                    | 4         | 0.07%   |
| VIA Technologies                             | 3         | 0.06%   |
| Razer USA                                    | 3         | 0.06%   |
| M-Audio                                      | 3         | 0.06%   |
| Elitegroup Computer Systems (ECS)            | 3         | 0.06%   |
| Conexant Systems                             | 3         | 0.06%   |
| Blue Microphones                             | 3         | 0.06%   |
| Apple                                        | 3         | 0.06%   |
| ZOOM                                         | 2         | 0.04%   |
| XMOS                                         | 2         | 0.04%   |
| Sony                                         | 2         | 0.04%   |
| OnePlus Technology (Shenzhen)                | 2         | 0.04%   |
| No brand                                     | 2         | 0.04%   |
| Jieli Technology                             | 2         | 0.04%   |
| Generalplus Technology                       | 2         | 0.04%   |
| Dell                                         | 2         | 0.04%   |
| Cambridge Audio                              | 2         | 0.04%   |
| Barco Display Systems                        | 2         | 0.04%   |
| Avid Technology                              | 2         | 0.04%   |
| Alesis                                       | 2         | 0.04%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.02%   |
| Yealink Network Technology                   | 1         | 0.02%   |
| Yamaha                                       | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 466       | 7.13%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 377       | 5.77%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 353       | 5.4%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 238       | 3.64%   |
| Intel Cannon Lake PCH cAVS                                                                        | 233       | 3.56%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 226       | 3.46%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 217       | 3.32%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 186       | 2.85%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 185       | 2.83%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 178       | 2.72%   |
| Intel 8 Series HD Audio Controller                                                                | 165       | 2.52%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 163       | 2.49%   |
| Intel Broadwell-U Audio Controller                                                                | 160       | 2.45%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 159       | 2.43%   |
| AMD FCH Azalia Controller                                                                         | 155       | 2.37%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 151       | 2.31%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 139       | 2.13%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 133       | 2.03%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 131       | 2%      |
| AMD Kabini HDMI/DP Audio                                                                          | 112       | 1.71%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 104       | 1.59%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 90        | 1.38%   |
| Intel Comet Lake PCH cAVS                                                                         | 89        | 1.36%   |
| Intel CM238 HD Audio Controller                                                                   | 87        | 1.33%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 83        | 1.27%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 76        | 1.16%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 73        | 1.12%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 71        | 1.09%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 68        | 1.04%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 66        | 1.01%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 64        | 0.98%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 60        | 0.92%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 58        | 0.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 56        | 0.86%   |
| AMD Wrestler HDMI Audio                                                                           | 56        | 0.86%   |
| Realtek Semiconductor USB Audio                                                                   | 55        | 0.84%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 55        | 0.84%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 53        | 0.81%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 49        | 0.75%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 44        | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 985       | 29.79%  |
| SK hynix                                         | 869       | 26.28%  |
| Micron Technology                                | 401       | 12.13%  |
| Unknown                                          | 233       | 7.05%   |
| Kingston                                         | 232       | 7.02%   |
| Crucial                                          | 160       | 4.84%   |
| Elpida                                           | 66        | 2%      |
| Ramaxel Technology                               | 59        | 1.78%   |
| Corsair                                          | 54        | 1.63%   |
| Nanya Technology                                 | 45        | 1.36%   |
| A-DATA Technology                                | 43        | 1.3%    |
| G.Skill                                          | 39        | 1.18%   |
| Unknown (ABCD)                                   | 36        | 1.09%   |
| Transcend                                        | 10        | 0.3%    |
| Unknown                                          | 8         | 0.24%   |
| Patriot                                          | 5         | 0.15%   |
| ASint Technology                                 | 5         | 0.15%   |
| Apacer                                           | 4         | 0.12%   |
| V-Color                                          | 3         | 0.09%   |
| Toshiba                                          | 3         | 0.09%   |
| Timetec                                          | 3         | 0.09%   |
| Team                                             | 3         | 0.09%   |
| SHARETRONIC                                      | 3         | 0.09%   |
| PNY                                              | 3         | 0.09%   |
| TEXTORM                                          | 2         | 0.06%   |
| Goldkey                                          | 2         | 0.06%   |
| ChangXin Memory                                  | 2         | 0.06%   |
| 48spaces                                         | 2         | 0.06%   |
| Unknown (F301)                                   | 1         | 0.03%   |
| Unknown (0x8634)                                 | 1         | 0.03%   |
| Unknown (0x7301)                                 | 1         | 0.03%   |
| Unknown (0x4D3420373054353636334548332D43463720) | 1         | 0.03%   |
| Unknown (0x4D342037305432383634515A332D43463720) | 1         | 0.03%   |
| Unknown (0x36345431323830323145444C335342322020) | 1         | 0.03%   |
| Unknown (0x0C97)                                 | 1         | 0.03%   |
| Unknown (07FB)                                   | 1         | 0.03%   |
| Unknown (01F3)                                   | 1         | 0.03%   |
| Silicon Power                                    | 1         | 0.03%   |
| Qimonda                                          | 1         | 0.03%   |
| PKI                                              | 1         | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 48        | 1.38%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 48        | 1.38%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 47        | 1.35%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 44        | 1.27%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 36        | 1.04%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 36        | 1.04%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 35        | 1.01%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 35        | 1.01%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 35        | 1.01%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 34        | 0.98%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 34        | 0.98%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 34        | 0.98%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 33        | 0.95%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 32        | 0.92%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 31        | 0.89%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 31        | 0.89%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 29        | 0.83%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 28        | 0.81%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 28        | 0.81%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 26        | 0.75%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 24        | 0.69%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 23        | 0.66%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 22        | 0.63%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 20        | 0.58%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 19        | 0.55%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 17        | 0.49%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 17        | 0.49%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 17        | 0.49%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 16        | 0.46%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 16        | 0.46%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 16        | 0.46%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 16        | 0.46%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 16        | 0.46%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 15        | 0.43%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 15        | 0.43%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 15        | 0.43%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 15        | 0.43%   |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                       | 15        | 0.43%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 15        | 0.43%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 14        | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 1302      | 45.97%  |
| DDR3    | 1020      | 36.02%  |
| DDR2    | 143       | 5.05%   |
| LPDDR4  | 128       | 4.52%   |
| LPDDR3  | 99        | 3.5%    |
| SDRAM   | 66        | 2.33%   |
| Unknown | 23        | 0.81%   |
| LPDDR5  | 17        | 0.6%    |
| DDR5    | 16        | 0.56%   |
| DDR     | 12        | 0.42%   |
| DRAM    | 6         | 0.21%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 2539      | 89.78%  |
| Row Of Chips | 257       | 9.09%   |
| Chip         | 14        | 0.5%    |
| DIMM         | 11        | 0.39%   |
| Unknown      | 7         | 0.25%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 1110      | 36.27%  |
| 4096  | 998       | 32.61%  |
| 2048  | 404       | 13.2%   |
| 16384 | 384       | 12.55%  |
| 1024  | 99        | 3.24%   |
| 32768 | 56        | 1.83%   |
| 512   | 8         | 0.26%   |
| 256   | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 734       | 24.18%  |
| 2667    | 606       | 19.96%  |
| 3200    | 508       | 16.73%  |
| 2400    | 209       | 6.88%   |
| 2133    | 160       | 5.27%   |
| 1334    | 159       | 5.24%   |
| 1333    | 103       | 3.39%   |
| 667     | 83        | 2.73%   |
| 4267    | 59        | 1.94%   |
| Unknown | 50        | 1.65%   |
| 3266    | 48        | 1.58%   |
| 1067    | 47        | 1.55%   |
| 1867    | 38        | 1.25%   |
| 4199    | 33        | 1.09%   |
| 800     | 33        | 1.09%   |
| 2048    | 27        | 0.89%   |
| 4800    | 22        | 0.72%   |
| 1066    | 22        | 0.72%   |
| 6400    | 17        | 0.56%   |
| 975     | 17        | 0.56%   |
| 533     | 14        | 0.46%   |
| 4266    | 11        | 0.36%   |
| 8400    | 8         | 0.26%   |
| 2933    | 5         | 0.16%   |
| 1866    | 5         | 0.16%   |
| 3000    | 4         | 0.13%   |
| 333     | 4         | 0.13%   |
| 3733    | 3         | 0.1%    |
| 1639    | 3         | 0.1%    |
| 400     | 2         | 0.07%   |
| 933     | 1         | 0.03%   |
| 266     | 1         | 0.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 15        | 37.5%   |
| Canon               | 10        | 25%     |
| Seiko Epson         | 4         | 10%     |
| Samsung Electronics | 4         | 10%     |
| Brother Industries  | 4         | 10%     |
| Xiaomi              | 1         | 2.5%    |
| STMicroelectronics  | 1         | 2.5%    |
| QinHeng Electronics | 1         | 2.5%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP DeskJet 2700 series                                    | 4         | 10%     |
| HP DeskJet 3630 series                                    | 3         | 7.5%    |
| Canon PIXMA MG2500 Series                                 | 3         | 7.5%    |
| Seiko Epson WF-2830 Series                                | 2         | 5%      |
| Canon PIXMA MG3600 Series                                 | 2         | 5%      |
| Xiaomi MiMouse 2                                          | 1         | 2.5%    |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 2.5%    |
| Seiko Epson XP-255 257 Series                             | 1         | 2.5%    |
| Seiko Epson XP-2150 Series                                | 1         | 2.5%    |
| Samsung SCX-3200 Series                                   | 1         | 2.5%    |
| Samsung ML-2010P Mono Laser Printer                       | 1         | 2.5%    |
| Samsung M2070 Series                                      | 1         | 2.5%    |
| Samsung M2020 Series                                      | 1         | 2.5%    |
| QinHeng CH340S                                            | 1         | 2.5%    |
| HP Photosmart B010 series                                 | 1         | 2.5%    |
| HP OfficeJet Pro 69                                       | 1         | 2.5%    |
| HP OfficeJet 3830 series                                  | 1         | 2.5%    |
| HP ENVY Photo 6200 series                                 | 1         | 2.5%    |
| HP ENVY 5540 series                                       | 1         | 2.5%    |
| HP ENVY 4500 series                                       | 1         | 2.5%    |
| HP Deskjet F4500 series                                   | 1         | 2.5%    |
| HP DeskJet 2600 series                                    | 1         | 2.5%    |
| Canon TS6100 series                                       | 1         | 2.5%    |
| Canon PIXMA MP495                                         | 1         | 2.5%    |
| Canon PIXMA MP270 All-In-One Printer                      | 1         | 2.5%    |
| Canon PIXMA MG3500 Series                                 | 1         | 2.5%    |
| Canon MG2100 series                                       | 1         | 2.5%    |
| Brother MFC-L8690CDW series                               | 1         | 2.5%    |
| Brother MFC-L2710DW series                                | 1         | 2.5%    |
| Brother MFC-1810                                          | 1         | 2.5%    |
| Brother DCP-L3550CDW series                               | 1         | 2.5%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 6         | 54.55%  |
| Seiko Epson     | 4         | 36.36%  |
| Hewlett-Packard | 1         | 9.09%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                       | 3         | 27.27%  |
| Seiko Epson Scanner                           | 1         | 9.09%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]   | 1         | 9.09%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 1         | 9.09%   |
| Seiko Epson GT-7700U [Perfection 1240U]       | 1         | 9.09%   |
| HP ScanJet 3570c                              | 1         | 9.09%   |
| Canon CanoScan N670U/N676U/LiDE 20            | 1         | 9.09%   |
| Canon CanoScan N650U/N656U                    | 1         | 9.09%   |
| Canon CanoScan N1240U/LiDE 30                 | 1         | 9.09%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 972       | 24.82%  |
| IMC Networks                           | 454       | 11.59%  |
| Microdia                               | 385       | 9.83%   |
| Realtek Semiconductor                  | 375       | 9.58%   |
| Acer                                   | 329       | 8.4%    |
| Sunplus Innovation Technology          | 246       | 6.28%   |
| Suyin                                  | 165       | 4.21%   |
| Cheng Uei Precision Industry (Foxlink) | 164       | 4.19%   |
| Quanta                                 | 135       | 3.45%   |
| Lite-On Technology                     | 105       | 2.68%   |
| Apple                                  | 83        | 2.12%   |
| Syntek                                 | 78        | 1.99%   |
| Alcor Micro                            | 53        | 1.35%   |
| Ricoh                                  | 43        | 1.1%    |
| Luxvisions Innotech Limited            | 43        | 1.1%    |
| Logitech                               | 43        | 1.1%    |
| Silicon Motion                         | 40        | 1.02%   |
| Samsung Electronics                    | 23        | 0.59%   |
| Lenovo                                 | 21        | 0.54%   |
| Primax Electronics                     | 18        | 0.46%   |
| Importek                               | 15        | 0.38%   |
| DigiTech                               | 14        | 0.36%   |
| Z-Star Microelectronics                | 12        | 0.31%   |
| Sonix Technology                       | 12        | 0.31%   |
| ALi                                    | 11        | 0.28%   |
| GEMBIRD                                | 7         | 0.18%   |
| OmniVision Technologies                | 6         | 0.15%   |
| Y Media                                | 5         | 0.13%   |
| icSpring                               | 5         | 0.13%   |
| Denron                                 | 4         | 0.1%    |
| Xiaomi                                 | 3         | 0.08%   |
| SunplusIT                              | 3         | 0.08%   |
| Pixart Imaging                         | 3         | 0.08%   |
| Microsoft                              | 3         | 0.08%   |
| Intel                                  | 3         | 0.08%   |
| ARC International                      | 3         | 0.08%   |
| Sunplus Technology                     | 2         | 0.05%   |
| OPPO Electronics                       | 2         | 0.05%   |
| Novatek Microelectronics               | 2         | 0.05%   |
| Jieli Technology                       | 2         | 0.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD            | 206       | 5.24%   |
| Realtek Integrated_Webcam_HD             | 165       | 4.2%    |
| Chicony Integrated Camera                | 148       | 3.76%   |
| IMC Networks USB2.0 HD UVC WebCam        | 103       | 2.62%   |
| Chicony HD WebCam                        | 101       | 2.57%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 81        | 2.06%   |
| IMC Networks Integrated Camera           | 80        | 2.03%   |
| Acer Integrated Camera                   | 73        | 1.86%   |
| Sunplus Integrated_Webcam_HD             | 65        | 1.65%   |
| Realtek USB Camera                       | 49        | 1.25%   |
| Acer HD Webcam                           | 48        | 1.22%   |
| Chicony USB2.0 VGA UVC WebCam            | 46        | 1.17%   |
| Chicony USB2.0 Camera                    | 45        | 1.14%   |
| Sunplus Asus Webcam                      | 40        | 1.02%   |
| Chicony USB2.0 HD UVC WebCam             | 40        | 1.02%   |
| Microdia Integrated Webcam               | 39        | 0.99%   |
| Chicony HP HD Camera                     | 38        | 0.97%   |
| Acer BisonCam,NB Pro                     | 36        | 0.92%   |
| Chicony HP HD Webcam                     | 35        | 0.89%   |
| Chicony USB 2.0 Camera                   | 34        | 0.86%   |
| Chicony HP TrueVision HD                 | 33        | 0.84%   |
| Syntek Integrated Camera                 | 32        | 0.81%   |
| Realtek USB2.0 HD UVC WebCam             | 31        | 0.79%   |
| Lite-On Integrated Camera                | 31        | 0.79%   |
| Chicony HP Truevision HD camera          | 30        | 0.76%   |
| Acer Lenovo EasyCamera                   | 30        | 0.76%   |
| Acer BisonCam, NB Pro                    | 30        | 0.76%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 29        | 0.74%   |
| Apple Built-in iSight                    | 29        | 0.74%   |
| Sunplus HD WebCam                        | 27        | 0.69%   |
| Chicony TOSHIBA Web Camera - HD          | 27        | 0.69%   |
| Apple iPhone 5/5C/5S/6/SE                | 27        | 0.69%   |
| IMC Networks UVC VGA Webcam              | 25        | 0.64%   |
| Chicony VGA Webcam                       | 25        | 0.64%   |
| Samsung Galaxy A5 (MTP)                  | 23        | 0.58%   |
| Quanta HP HD Camera                      | 23        | 0.58%   |
| IMC Networks ov9734_azurewave_camera     | 22        | 0.56%   |
| Lite-On HP HD Webcam                     | 21        | 0.53%   |
| IMC Networks USB2.0 HD IR UVC WebCam     | 21        | 0.53%   |
| Chicony EasyCamera                       | 20        | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 266       | 36.59%  |
| Synaptics                  | 149       | 20.5%   |
| Shenzhen Goodix Technology | 138       | 18.98%  |
| AuthenTec                  | 59        | 8.12%   |
| LighTuning Technology      | 37        | 5.09%   |
| Elan Microelectronics      | 37        | 5.09%   |
| Upek                       | 29        | 3.99%   |
| STMicroelectronics         | 11        | 1.51%   |
| Focal-systems.Corp         | 1         | 0.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 76        | 10.45%  |
| Shenzhen Goodix  FingerPrint Device                                        | 72        | 9.9%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 62        | 8.53%   |
| Shenzhen Goodix FingerPrint                                                | 39        | 5.36%   |
| Unknown                                                                    | 39        | 5.36%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 33        | 4.54%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 29        | 3.99%   |
| Shenzhen Goodix Fingerprint Reader                                         | 27        | 3.71%   |
| Elan ELAN:Fingerprint                                                      | 27        | 3.71%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 25        | 3.44%   |
| Validity Sensors VFS491                                                    | 23        | 3.16%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 22        | 3.03%   |
| AuthenTec AES2810                                                          | 22        | 3.03%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 18        | 2.48%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 17        | 2.34%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 16        | 2.2%    |
| Validity Sensors Fingerprint scanner                                       | 16        | 2.2%    |
| AuthenTec AES1600                                                          | 13        | 1.79%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 12        | 1.65%   |
| Validity Sensors Synaptics WBDI                                            | 12        | 1.65%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 12        | 1.65%   |
| AuthenTec Fingerprint Sensor                                               | 12        | 1.65%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 11        | 1.51%   |
| STMicroelectronics Fingerprint Reader                                      | 11        | 1.51%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 10        | 1.38%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 9         | 1.24%   |
| Elan ELAN:ARM-M4                                                           | 9         | 1.24%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 8         | 1.1%    |
| Validity Sensors VFS Fingerprint sensor                                    | 6         | 0.83%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 6         | 0.83%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 0.69%   |
| Synaptics WBDI Device                                                      | 5         | 0.69%   |
| Upek TCS5B Fingerprint sensor                                              | 4         | 0.55%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 3         | 0.41%   |
| Synaptics  WBDI                                                            | 3         | 0.41%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 3         | 0.41%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 0.28%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.28%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 0.28%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.14%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 210       | 56.91%  |
| Alcor Micro               | 78        | 21.14%  |
| O2 Micro                  | 33        | 8.94%   |
| Upek                      | 16        | 4.34%   |
| Lenovo                    | 15        | 4.07%   |
| Hewlett-Packard           | 5         | 1.36%   |
| Gemalto (was Gemplus)     | 4         | 1.08%   |
| Yubico.com                | 2         | 0.54%   |
| Clay Logic                | 2         | 0.54%   |
| SpringCard                | 1         | 0.27%   |
| OmniKey                   | 1         | 0.27%   |
| Chicony Electronics       | 1         | 0.27%   |
| Aladdin Knowledge Systems | 1         | 0.27%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 78        | 21.14%  |
| Broadcom BCM5880 Secure Applications Processor                               | 71        | 19.24%  |
| Broadcom 58200                                                               | 60        | 16.26%  |
| Broadcom 5880                                                                | 45        | 12.2%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 33        | 8.94%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 30        | 8.13%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 16        | 4.34%   |
| Lenovo Integrated Smart Card Reader                                          | 15        | 4.07%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 5         | 1.36%   |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 0.81%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 0.54%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 0.54%   |
| SpringCard Two                                                               | 1         | 0.27%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.27%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.27%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.27%   |
| Clay Logic Nitrokey Start                                                    | 1         | 0.27%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.27%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.27%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.27%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.27%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 2801      | 62%     |
| 1     | 1356      | 30.01%  |
| 2     | 290       | 6.42%   |
| 3     | 51        | 1.13%   |
| 4     | 9         | 0.2%    |
| 5     | 5         | 0.11%   |
| 6     | 3         | 0.07%   |
| 7     | 2         | 0.04%   |
| 8     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 718       | 34.17%  |
| Graphics card            | 447       | 21.28%  |
| Chipcard                 | 344       | 16.37%  |
| Net/wireless             | 180       | 8.57%   |
| Multimedia controller    | 80        | 3.81%   |
| Camera                   | 74        | 3.52%   |
| Bluetooth                | 64        | 3.05%   |
| Storage                  | 52        | 2.48%   |
| Communication controller | 41        | 1.95%   |
| Card reader              | 32        | 1.52%   |
| Sound                    | 22        | 1.05%   |
| Modem                    | 16        | 0.76%   |
| Net/ethernet             | 15        | 0.71%   |
| Network                  | 5         | 0.24%   |
| Flash memory             | 3         | 0.14%   |
| Unclassified device      | 2         | 0.1%    |
| Wireless                 | 1         | 0.05%   |
| Unassigned class         | 1         | 0.05%   |
| Storage/nvme             | 1         | 0.05%   |
| Storage/ata              | 1         | 0.05%   |
| Firewire controller      | 1         | 0.05%   |
| Dvb card                 | 1         | 0.05%   |

