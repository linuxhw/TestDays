Fedora 35 - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Fedora 35.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

Total: 997

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | ROG Strix G512LV_G512LV     | [9cbf0f3aad](https://linux-hardware.org/?probe=9cbf0f3aad) | Apr 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [5c28fb1391](https://linux-hardware.org/?probe=5c28fb1391) | Apr 04, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [92130ffb61](https://linux-hardware.org/?probe=92130ffb61) | Apr 04, 2022 |
| Dell          | XPS 15 9570                 | [05569f49ca](https://linux-hardware.org/?probe=05569f49ca) | Apr 04, 2022 |
| Lenovo        | ThinkPad T495 20NJ000XIX    | [bdd5a36f62](https://linux-hardware.org/?probe=bdd5a36f62) | Apr 04, 2022 |
| Apple         | MacBookPro15,1              | [1c4423ca19](https://linux-hardware.org/?probe=1c4423ca19) | Apr 04, 2022 |
| HP            | ElitePad 1000 G2            | [d479e2ae4a](https://linux-hardware.org/?probe=d479e2ae4a) | Apr 04, 2022 |
| ASUSTek       | UX301LAA                    | [1c631fdb63](https://linux-hardware.org/?probe=1c631fdb63) | Apr 04, 2022 |
| ASUSTek       | X550LC                      | [30ed5cb046](https://linux-hardware.org/?probe=30ed5cb046) | Apr 03, 2022 |
| Sony          | VPCEB4L1E                   | [358783a077](https://linux-hardware.org/?probe=358783a077) | Apr 03, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [3e8d03d8d6](https://linux-hardware.org/?probe=3e8d03d8d6) | Apr 03, 2022 |
| Dell          | Latitude 5520               | [0fc592dd2c](https://linux-hardware.org/?probe=0fc592dd2c) | Apr 03, 2022 |
| HP            | EliteBook 8770w             | [e826deade2](https://linux-hardware.org/?probe=e826deade2) | Apr 03, 2022 |
| Framework     | Laptop                      | [a0e35b1871](https://linux-hardware.org/?probe=a0e35b1871) | Apr 03, 2022 |
| Lenovo        | ThinkPad X250 20CLS2B000    | [869407eb01](https://linux-hardware.org/?probe=869407eb01) | Apr 03, 2022 |
| Dell          | Precision 5530              | [96b22b6124](https://linux-hardware.org/?probe=96b22b6124) | Apr 03, 2022 |
| Dell          | Inspiron 5548               | [d187a0de09](https://linux-hardware.org/?probe=d187a0de09) | Apr 03, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [6154972f18](https://linux-hardware.org/?probe=6154972f18) | Apr 03, 2022 |
| Samsung       | 270E5J/2570EJ               | [2911dea3f0](https://linux-hardware.org/?probe=2911dea3f0) | Apr 02, 2022 |
| HP            | EliteBook Folio 9480m       | [a83be65e4f](https://linux-hardware.org/?probe=a83be65e4f) | Apr 02, 2022 |
| HP            | ProBook 650 G1              | [f13dbb1e06](https://linux-hardware.org/?probe=f13dbb1e06) | Apr 02, 2022 |
| Acer          | Swift SF114-34              | [5dcb0a1847](https://linux-hardware.org/?probe=5dcb0a1847) | Apr 02, 2022 |
| Dell          | Latitude 5500               | [798c0e5fa4](https://linux-hardware.org/?probe=798c0e5fa4) | Apr 02, 2022 |
| HP            | EliteBook Folio 9480m       | [5bb1b6ca04](https://linux-hardware.org/?probe=5bb1b6ca04) | Apr 02, 2022 |
| MSI           | GF63 Thin 9SCXR             | [3bc3694efb](https://linux-hardware.org/?probe=3bc3694efb) | Apr 02, 2022 |
| Timi          | TM1612                      | [7eb83bb23a](https://linux-hardware.org/?probe=7eb83bb23a) | Apr 02, 2022 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | [3c89c6c9d8](https://linux-hardware.org/?probe=3c89c6c9d8) | Apr 02, 2022 |
| ASUSTek       | X750JN                      | [11153fc9f1](https://linux-hardware.org/?probe=11153fc9f1) | Apr 02, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [055b15c7a9](https://linux-hardware.org/?probe=055b15c7a9) | Apr 02, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [8ae9fd4940](https://linux-hardware.org/?probe=8ae9fd4940) | Apr 02, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [29b8b7110c](https://linux-hardware.org/?probe=29b8b7110c) | Apr 01, 2022 |
| Gigabyte      | P65Q                        | [c0e5b4550a](https://linux-hardware.org/?probe=c0e5b4550a) | Apr 01, 2022 |
| PC Special... | PC5x_7xHP_HR_HS             | [82ec2ff5f6](https://linux-hardware.org/?probe=82ec2ff5f6) | Apr 01, 2022 |
| PC Special... | PC5x_7xHP_HR_HS             | [7aefa77b4b](https://linux-hardware.org/?probe=7aefa77b4b) | Apr 01, 2022 |
| Lenovo        | IdeaPad 510S-13IKB 80V0     | [97505bf353](https://linux-hardware.org/?probe=97505bf353) | Apr 01, 2022 |
| Lenovo        | G500 20236                  | [9ebbf23e28](https://linux-hardware.org/?probe=9ebbf23e28) | Apr 01, 2022 |
| Lenovo        | G500 20236                  | [95d2d82ede](https://linux-hardware.org/?probe=95d2d82ede) | Apr 01, 2022 |
| Dell          | Inspiron 14 5410            | [3acec795a6](https://linux-hardware.org/?probe=3acec795a6) | Apr 01, 2022 |
| Dell          | Inspiron N5110              | [d18cd45522](https://linux-hardware.org/?probe=d18cd45522) | Apr 01, 2022 |
| Dell          | Inspiron N5110              | [ec162ebae4](https://linux-hardware.org/?probe=ec162ebae4) | Apr 01, 2022 |
| Notebook      | NH55RGQ                     | [beed63b0d4](https://linux-hardware.org/?probe=beed63b0d4) | Apr 01, 2022 |
| GPU Compan... | GWTN141-4                   | [81e7639a72](https://linux-hardware.org/?probe=81e7639a72) | Apr 01, 2022 |
| HP            | ElitePad 1000 G2            | [b6da5f9629](https://linux-hardware.org/?probe=b6da5f9629) | Apr 01, 2022 |
| Samsung       | RC420/RC520/RC720           | [5a576e8488](https://linux-hardware.org/?probe=5a576e8488) | Apr 01, 2022 |
| Dell          | Inspiron 5548               | [06b3aacb51](https://linux-hardware.org/?probe=06b3aacb51) | Apr 01, 2022 |
| Lenovo        | ThinkPad Edge E531 6885D... | [913c396bde](https://linux-hardware.org/?probe=913c396bde) | Apr 01, 2022 |
| Lenovo        | ThinkPad Edge E531 6885D... | [6774f9f9c8](https://linux-hardware.org/?probe=6774f9f9c8) | Apr 01, 2022 |
| HP            | Laptop 17z-ca300            | [726d1e7b0f](https://linux-hardware.org/?probe=726d1e7b0f) | Mar 31, 2022 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | [c01344bd43](https://linux-hardware.org/?probe=c01344bd43) | Mar 31, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [4ad9fe021c](https://linux-hardware.org/?probe=4ad9fe021c) | Mar 31, 2022 |
| HP            | Pavilion Notebook           | [a18360bae8](https://linux-hardware.org/?probe=a18360bae8) | Mar 31, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [6ab27f6f88](https://linux-hardware.org/?probe=6ab27f6f88) | Mar 31, 2022 |
| Samsung       | RC420/RC520/RC720           | [83800436e5](https://linux-hardware.org/?probe=83800436e5) | Mar 31, 2022 |
| Sony          | SVF14213CLB                 | [b87a95ae1a](https://linux-hardware.org/?probe=b87a95ae1a) | Mar 31, 2022 |
| Sony          | SVF14213CLB                 | [fecf079b63](https://linux-hardware.org/?probe=fecf079b63) | Mar 31, 2022 |
| HP            | ElitePad 1000 G2            | [2ce0540229](https://linux-hardware.org/?probe=2ce0540229) | Mar 31, 2022 |
| HP            | ElitePad 1000 G2            | [f43d64639e](https://linux-hardware.org/?probe=f43d64639e) | Mar 31, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [43e45df9f5](https://linux-hardware.org/?probe=43e45df9f5) | Mar 30, 2022 |
| HP            | Laptop 15s-eq2xxx           | [b8716e4043](https://linux-hardware.org/?probe=b8716e4043) | Mar 30, 2022 |
| Toshiba       | TECRA Z50-A                 | [cd333e5720](https://linux-hardware.org/?probe=cd333e5720) | Mar 30, 2022 |
| Dell          | XPS 13 7390                 | [db3d70e53a](https://linux-hardware.org/?probe=db3d70e53a) | Mar 30, 2022 |
| HP            | EliteBook 840 G3            | [3a64f14cc4](https://linux-hardware.org/?probe=3a64f14cc4) | Mar 30, 2022 |
| HONOR         | NBD-WXX9                    | [dd51589f73](https://linux-hardware.org/?probe=dd51589f73) | Mar 30, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [0f18e7b54b](https://linux-hardware.org/?probe=0f18e7b54b) | Mar 30, 2022 |
| HP            | Pavilion 17                 | [f815e79449](https://linux-hardware.org/?probe=f815e79449) | Mar 30, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [fd1759c341](https://linux-hardware.org/?probe=fd1759c341) | Mar 29, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [3e3c94b9f6](https://linux-hardware.org/?probe=3e3c94b9f6) | Mar 29, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [670f83f6bb](https://linux-hardware.org/?probe=670f83f6bb) | Mar 29, 2022 |
| Lenovo        | V330-15IKB 81AX             | [8a881c75f4](https://linux-hardware.org/?probe=8a881c75f4) | Mar 29, 2022 |
| HP            | OMEN by Laptop              | [88b64a12df](https://linux-hardware.org/?probe=88b64a12df) | Mar 29, 2022 |
| Hampoo        | C1W6_AP123C_6GB Reserved    | [ff622b910d](https://linux-hardware.org/?probe=ff622b910d) | Mar 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [5e0763131c](https://linux-hardware.org/?probe=5e0763131c) | Mar 28, 2022 |
| Dell          | Vostro 3580                 | [0ec442c0be](https://linux-hardware.org/?probe=0ec442c0be) | Mar 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [c1384b9063](https://linux-hardware.org/?probe=c1384b9063) | Mar 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [92bbba70b0](https://linux-hardware.org/?probe=92bbba70b0) | Mar 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [981757ce36](https://linux-hardware.org/?probe=981757ce36) | Mar 28, 2022 |
| MSI           | Delta 15 A5EFK              | [9c5efbe2a7](https://linux-hardware.org/?probe=9c5efbe2a7) | Mar 28, 2022 |
| HP            | Pavilion Notebook           | [ac807c9324](https://linux-hardware.org/?probe=ac807c9324) | Mar 27, 2022 |
| Dell          | Inspiron 3505               | [c472ae03f6](https://linux-hardware.org/?probe=c472ae03f6) | Mar 27, 2022 |
| HP            | ProBook 470 G5              | [b8969bf34b](https://linux-hardware.org/?probe=b8969bf34b) | Mar 27, 2022 |
| HP            | EliteBook 850 G6            | [084d60ff3b](https://linux-hardware.org/?probe=084d60ff3b) | Mar 27, 2022 |
| HP            | ElitePad 1000 G2            | [73be67de2c](https://linux-hardware.org/?probe=73be67de2c) | Mar 27, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5555        | [b557a2005c](https://linux-hardware.org/?probe=b557a2005c) | Mar 27, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [64606b8247](https://linux-hardware.org/?probe=64606b8247) | Mar 26, 2022 |
| Fujitsu       | LIFEBOOK E746               | [dc5e0a376b](https://linux-hardware.org/?probe=dc5e0a376b) | Mar 26, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [25ad4e35b9](https://linux-hardware.org/?probe=25ad4e35b9) | Mar 26, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [d5e927b59e](https://linux-hardware.org/?probe=d5e927b59e) | Mar 26, 2022 |
| Acer          | Aspire E5-575G              | [b47822d246](https://linux-hardware.org/?probe=b47822d246) | Mar 26, 2022 |
| HP            | Laptop 15s-eq2xxx           | [a640b0a024](https://linux-hardware.org/?probe=a640b0a024) | Mar 26, 2022 |
| ASUSTek       | N550JK                      | [a3ecefa43f](https://linux-hardware.org/?probe=a3ecefa43f) | Mar 26, 2022 |
| HP            | ElitePad 1000 G2            | [5861c8e75a](https://linux-hardware.org/?probe=5861c8e75a) | Mar 26, 2022 |
| Acer          | Aspire E5-573G              | [b78f0137ba](https://linux-hardware.org/?probe=b78f0137ba) | Mar 26, 2022 |
| Alienware     | m15 R6                      | [5505410995](https://linux-hardware.org/?probe=5505410995) | Mar 25, 2022 |
| HP            | Laptop 15s-eq0xxx           | [22d9e9ead2](https://linux-hardware.org/?probe=22d9e9ead2) | Mar 25, 2022 |
| Lenovo        | ThinkPad X250 20CLS09Y19    | [2602549f95](https://linux-hardware.org/?probe=2602549f95) | Mar 25, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [1d0229f697](https://linux-hardware.org/?probe=1d0229f697) | Mar 25, 2022 |
| Acer          | Nitro AN515-44              | [1ab1216e5b](https://linux-hardware.org/?probe=1ab1216e5b) | Mar 25, 2022 |
| Dell          | Vostro 5402                 | [b47655a721](https://linux-hardware.org/?probe=b47655a721) | Mar 25, 2022 |
| Sony          | VGN-FW180D                  | [9bbcb3d0ac](https://linux-hardware.org/?probe=9bbcb3d0ac) | Mar 25, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [10c6384de8](https://linux-hardware.org/?probe=10c6384de8) | Mar 25, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | [a05a647662](https://linux-hardware.org/?probe=a05a647662) | Mar 25, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [da358bbf5c](https://linux-hardware.org/?probe=da358bbf5c) | Mar 25, 2022 |
| MSI           | Stealth GS66 12UHS          | [4a6b3d619c](https://linux-hardware.org/?probe=4a6b3d619c) | Mar 25, 2022 |
| MSI           | Stealth GS66 12UHS          | [7d1fa138d0](https://linux-hardware.org/?probe=7d1fa138d0) | Mar 25, 2022 |
| HP            | Pavilion 11 x360 PC         | [975bcd1031](https://linux-hardware.org/?probe=975bcd1031) | Mar 25, 2022 |
| Dell          | Inspiron 3542               | [870e407665](https://linux-hardware.org/?probe=870e407665) | Mar 25, 2022 |
| Lenovo        | G50-45 80E3                 | [8dbd85ced8](https://linux-hardware.org/?probe=8dbd85ced8) | Mar 25, 2022 |
| Dell          | XPS 15 9500                 | [911fd95d9f](https://linux-hardware.org/?probe=911fd95d9f) | Mar 25, 2022 |
| HP            | Laptop 15s-eq2xxx           | [1d606d499d](https://linux-hardware.org/?probe=1d606d499d) | Mar 24, 2022 |
| Dell          | Inspiron 5567               | [7c80283af3](https://linux-hardware.org/?probe=7c80283af3) | Mar 24, 2022 |
| Acer          | Aspire A515-43              | [52bc15cdf9](https://linux-hardware.org/?probe=52bc15cdf9) | Mar 24, 2022 |
| System76      | Gazelle                     | [5a83198dd6](https://linux-hardware.org/?probe=5a83198dd6) | Mar 24, 2022 |
| HP            | Laptop 15-db0xxx            | [ef1af7bbae](https://linux-hardware.org/?probe=ef1af7bbae) | Mar 23, 2022 |
| Dell          | XPS 13 9305                 | [1fb70f4b83](https://linux-hardware.org/?probe=1fb70f4b83) | Mar 23, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [912cb19656](https://linux-hardware.org/?probe=912cb19656) | Mar 23, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [55730a4af8](https://linux-hardware.org/?probe=55730a4af8) | Mar 23, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [3f4f125a64](https://linux-hardware.org/?probe=3f4f125a64) | Mar 23, 2022 |
| Dell          | Vostro 5402                 | [64718709d1](https://linux-hardware.org/?probe=64718709d1) | Mar 23, 2022 |
| Dell          | Vostro 5402                 | [f123e292b9](https://linux-hardware.org/?probe=f123e292b9) | Mar 23, 2022 |
| ASUSTek       | X75VCP                      | [54e978fcca](https://linux-hardware.org/?probe=54e978fcca) | Mar 23, 2022 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | [6285900fd7](https://linux-hardware.org/?probe=6285900fd7) | Mar 22, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U1S... | [f140780c32](https://linux-hardware.org/?probe=f140780c32) | Mar 22, 2022 |
| Acer          | Aspire A515-43              | [6934e641a4](https://linux-hardware.org/?probe=6934e641a4) | Mar 22, 2022 |
| Dell          | Latitude 5520               | [a8e30b61c6](https://linux-hardware.org/?probe=a8e30b61c6) | Mar 21, 2022 |
| Dell          | Latitude 5520               | [02b408b5f6](https://linux-hardware.org/?probe=02b408b5f6) | Mar 21, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [2298f934bd](https://linux-hardware.org/?probe=2298f934bd) | Mar 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [f4e2b38106](https://linux-hardware.org/?probe=f4e2b38106) | Mar 20, 2022 |
| Razer         | Blade Stealth               | [6b524f20d4](https://linux-hardware.org/?probe=6b524f20d4) | Mar 20, 2022 |
| Dell          | Inspiron 15 5501            | [1865c91af0](https://linux-hardware.org/?probe=1865c91af0) | Mar 20, 2022 |
| Lenovo        | ThinkPad X270 20HMS6AT00    | [40767d2545](https://linux-hardware.org/?probe=40767d2545) | Mar 20, 2022 |
| HP            | Laptop 14-dk0xxx            | [bde47f2d75](https://linux-hardware.org/?probe=bde47f2d75) | Mar 20, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [8793c924fe](https://linux-hardware.org/?probe=8793c924fe) | Mar 19, 2022 |
| HP            | ZBook Firefly 15 inch G8... | [674a4429c2](https://linux-hardware.org/?probe=674a4429c2) | Mar 19, 2022 |
| ASUSTek       | K46CM                       | [8366f92538](https://linux-hardware.org/?probe=8366f92538) | Mar 19, 2022 |
| ASUSTek       | K46CM                       | [8f96005683](https://linux-hardware.org/?probe=8f96005683) | Mar 19, 2022 |
| HP            | EliteBook 8470p             | [3c40b29b63](https://linux-hardware.org/?probe=3c40b29b63) | Mar 19, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [5eb63254f8](https://linux-hardware.org/?probe=5eb63254f8) | Mar 19, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [5864c55419](https://linux-hardware.org/?probe=5864c55419) | Mar 19, 2022 |
| Dell          | Inspiron 5502               | [ce6b8e3716](https://linux-hardware.org/?probe=ce6b8e3716) | Mar 19, 2022 |
| Digibras      | NH4CU03                     | [7970a8e8d2](https://linux-hardware.org/?probe=7970a8e8d2) | Mar 19, 2022 |
| eMachines     | E725 V1.03                  | [12ea923e2b](https://linux-hardware.org/?probe=12ea923e2b) | Mar 18, 2022 |
| Acer          | Aspire A317-51G             | [f2a7cadaff](https://linux-hardware.org/?probe=f2a7cadaff) | Mar 18, 2022 |
| Toshiba       | Satellite C855-12R          | [96554352c8](https://linux-hardware.org/?probe=96554352c8) | Mar 18, 2022 |
| Lenovo        | ThinkPad P53 20QN000HGE     | [db71f4d011](https://linux-hardware.org/?probe=db71f4d011) | Mar 18, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [c869642fe9](https://linux-hardware.org/?probe=c869642fe9) | Mar 18, 2022 |
| Dell          | Latitude E6420              | [e97e686e5e](https://linux-hardware.org/?probe=e97e686e5e) | Mar 17, 2022 |
| HP            | EliteBook 8460p             | [7bc2963830](https://linux-hardware.org/?probe=7bc2963830) | Mar 17, 2022 |
| Lenovo        | G40-80 80JE                 | [c41639222f](https://linux-hardware.org/?probe=c41639222f) | Mar 17, 2022 |
| Dell          | Inspiron 5502               | [b5aeb18001](https://linux-hardware.org/?probe=b5aeb18001) | Mar 17, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [6a5b5cd15e](https://linux-hardware.org/?probe=6a5b5cd15e) | Mar 17, 2022 |
| Dell          | XPS 15 9550                 | [f7eb058e61](https://linux-hardware.org/?probe=f7eb058e61) | Mar 17, 2022 |
| Lenovo        | G50-70 20351                | [16ced37ed8](https://linux-hardware.org/?probe=16ced37ed8) | Mar 17, 2022 |
| Lenovo        | ThinkPad X220 428767U       | [380351014b](https://linux-hardware.org/?probe=380351014b) | Mar 16, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [fa74626a55](https://linux-hardware.org/?probe=fa74626a55) | Mar 16, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T8S... | [1ac160aea7](https://linux-hardware.org/?probe=1ac160aea7) | Mar 15, 2022 |
| HP            | ENVY TS m6 Sleekbook        | [66bda745cd](https://linux-hardware.org/?probe=66bda745cd) | Mar 15, 2022 |
| Dell          | Vostro 5402                 | [62038e09e8](https://linux-hardware.org/?probe=62038e09e8) | Mar 15, 2022 |
| Dell          | Vostro 5402                 | [cbebb0b476](https://linux-hardware.org/?probe=cbebb0b476) | Mar 15, 2022 |
| MSI           | GE75 Raider 10SE            | [affad66907](https://linux-hardware.org/?probe=affad66907) | Mar 14, 2022 |
| Acer          | Calpella                    | [038e7b15ee](https://linux-hardware.org/?probe=038e7b15ee) | Mar 14, 2022 |
| MSI           | GE75 Raider 10SE            | [79744a34f1](https://linux-hardware.org/?probe=79744a34f1) | Mar 14, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [c334e9a1f6](https://linux-hardware.org/?probe=c334e9a1f6) | Mar 14, 2022 |
| HP            | ProBook 6465b               | [95ecc6cdbd](https://linux-hardware.org/?probe=95ecc6cdbd) | Mar 14, 2022 |
| Apple         | MacBookPro9,2               | [b400e8a455](https://linux-hardware.org/?probe=b400e8a455) | Mar 14, 2022 |
| Apple         | MacBook7,1                  | [5cdaea7c5a](https://linux-hardware.org/?probe=5cdaea7c5a) | Mar 14, 2022 |
| Dell          | Vostro 1014                 | [8df761ef60](https://linux-hardware.org/?probe=8df761ef60) | Mar 13, 2022 |
| Apple         | MacBookPro16,1              | [9cce5830b5](https://linux-hardware.org/?probe=9cce5830b5) | Mar 13, 2022 |
| Positivo      | N1250                       | [e0ac8b69f1](https://linux-hardware.org/?probe=e0ac8b69f1) | Mar 13, 2022 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [739b74effe](https://linux-hardware.org/?probe=739b74effe) | Mar 13, 2022 |
| Lenovo        | IdeaPad 710S-13IKB 80VQ     | [3dc49dc5f3](https://linux-hardware.org/?probe=3dc49dc5f3) | Mar 13, 2022 |
| Dell          | Latitude 7285               | [87e555f958](https://linux-hardware.org/?probe=87e555f958) | Mar 13, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [6e9075eebf](https://linux-hardware.org/?probe=6e9075eebf) | Mar 13, 2022 |
| Dell          | Latitude 5511               | [ec15afa8e7](https://linux-hardware.org/?probe=ec15afa8e7) | Mar 12, 2022 |
| Dell          | Precision 5540              | [99b2435d7a](https://linux-hardware.org/?probe=99b2435d7a) | Mar 12, 2022 |
| Lenovo        | G780 20138                  | [276b115350](https://linux-hardware.org/?probe=276b115350) | Mar 12, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [f2a82ddf3b](https://linux-hardware.org/?probe=f2a82ddf3b) | Mar 11, 2022 |
| Acer          | Aspire 5250                 | [a3f9e83752](https://linux-hardware.org/?probe=a3f9e83752) | Mar 11, 2022 |
| Dell          | Latitude 7480               | [bb03e5e22e](https://linux-hardware.org/?probe=bb03e5e22e) | Mar 11, 2022 |
| Dell          | Latitude 5511               | [2372b12d5c](https://linux-hardware.org/?probe=2372b12d5c) | Mar 11, 2022 |
| HUAWEI        | BOD-WXX9                    | [cbfe261386](https://linux-hardware.org/?probe=cbfe261386) | Mar 11, 2022 |
| HP            | Notebook                    | [de3091d5d4](https://linux-hardware.org/?probe=de3091d5d4) | Mar 11, 2022 |
| Apple         | MacBookPro10,1              | [2a4e580bd6](https://linux-hardware.org/?probe=2a4e580bd6) | Mar 11, 2022 |
| Dell          | G5 5505                     | [286d140bd5](https://linux-hardware.org/?probe=286d140bd5) | Mar 10, 2022 |
| HP            | Stream Laptop 14-ax0XX      | [f4a2cbf25a](https://linux-hardware.org/?probe=f4a2cbf25a) | Mar 10, 2022 |
| HP            | ZBook 14u G4                | [cc637b12de](https://linux-hardware.org/?probe=cc637b12de) | Mar 10, 2022 |
| Acer          | Swift SF314-42              | [68e933e6a3](https://linux-hardware.org/?probe=68e933e6a3) | Mar 10, 2022 |
| Apple         | MacBookPro13,2              | [f1f2a94be9](https://linux-hardware.org/?probe=f1f2a94be9) | Mar 10, 2022 |
| Apple         | MacBookPro13,2              | [fc015f45ba](https://linux-hardware.org/?probe=fc015f45ba) | Mar 10, 2022 |
| HP            | EliteBook 850 G5            | [ab88a095ac](https://linux-hardware.org/?probe=ab88a095ac) | Mar 10, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [849f4141ce](https://linux-hardware.org/?probe=849f4141ce) | Mar 09, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [49503537f5](https://linux-hardware.org/?probe=49503537f5) | Mar 09, 2022 |
| Positivo      | CHT12CP                     | [fa7f40245b](https://linux-hardware.org/?probe=fa7f40245b) | Mar 09, 2022 |
| Acer          | Aspire 4750                 | [0659469dbe](https://linux-hardware.org/?probe=0659469dbe) | Mar 09, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [4378396a20](https://linux-hardware.org/?probe=4378396a20) | Mar 08, 2022 |
| HP            | Pavilion g4                 | [3ff8cf8ed0](https://linux-hardware.org/?probe=3ff8cf8ed0) | Mar 08, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [4eb9de0f3a](https://linux-hardware.org/?probe=4eb9de0f3a) | Mar 08, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [02b4ade19f](https://linux-hardware.org/?probe=02b4ade19f) | Mar 08, 2022 |
| Acer          | Aspire A114-32              | [1260b41068](https://linux-hardware.org/?probe=1260b41068) | Mar 08, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [96833919d2](https://linux-hardware.org/?probe=96833919d2) | Mar 08, 2022 |
| Dell          | Inspiron 5458               | [16f5e2d856](https://linux-hardware.org/?probe=16f5e2d856) | Mar 08, 2022 |
| Apple         | MacBookPro11,4              | [f3eb9f941a](https://linux-hardware.org/?probe=f3eb9f941a) | Mar 08, 2022 |
| ASUSTek       | UX31E                       | [2b8b852d07](https://linux-hardware.org/?probe=2b8b852d07) | Mar 07, 2022 |
| HP            | Laptop 15s-eq2xxx           | [aebf1eb00c](https://linux-hardware.org/?probe=aebf1eb00c) | Mar 07, 2022 |
| ASUSTek       | X550LC                      | [267fa2ca76](https://linux-hardware.org/?probe=267fa2ca76) | Mar 06, 2022 |
| Lenovo        | G40-80 80JE                 | [2bf4890b1b](https://linux-hardware.org/?probe=2bf4890b1b) | Mar 06, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [e14e313311](https://linux-hardware.org/?probe=e14e313311) | Mar 06, 2022 |
| Lenovo        | V14-ADA 82C6                | [856cb873fc](https://linux-hardware.org/?probe=856cb873fc) | Mar 06, 2022 |
| HUAWEI        | HVY-WXX9                    | [fc4d2904c3](https://linux-hardware.org/?probe=fc4d2904c3) | Mar 06, 2022 |
| Acer          | Aspire E1-522               | [1d4f09c200](https://linux-hardware.org/?probe=1d4f09c200) | Mar 05, 2022 |
| ASUSTek       | G551JK                      | [a9f394c585](https://linux-hardware.org/?probe=a9f394c585) | Mar 05, 2022 |
| Dell          | Latitude 7490               | [64f0d004ce](https://linux-hardware.org/?probe=64f0d004ce) | Mar 05, 2022 |
| Dell          | Latitude E5470              | [1ef8a55ede](https://linux-hardware.org/?probe=1ef8a55ede) | Mar 05, 2022 |
| HP            | EliteBook 850 G5            | [bf630f003c](https://linux-hardware.org/?probe=bf630f003c) | Mar 04, 2022 |
| HP            | ProBook 430 G5              | [9b130dbcb5](https://linux-hardware.org/?probe=9b130dbcb5) | Mar 04, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | [134d1cf65b](https://linux-hardware.org/?probe=134d1cf65b) | Mar 03, 2022 |
| Medion        | Akoya P6638                 | [102c7910e5](https://linux-hardware.org/?probe=102c7910e5) | Mar 03, 2022 |
| HP            | Laptop 14s-dk0xxx           | [c5bf02a4d7](https://linux-hardware.org/?probe=c5bf02a4d7) | Mar 03, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [48c1285eec](https://linux-hardware.org/?probe=48c1285eec) | Mar 02, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [35507d8b67](https://linux-hardware.org/?probe=35507d8b67) | Mar 02, 2022 |
| HP            | ProBook 650 G1              | [89e589ec6b](https://linux-hardware.org/?probe=89e589ec6b) | Mar 02, 2022 |
| HP            | ProBook 650 G1              | [587195961c](https://linux-hardware.org/?probe=587195961c) | Mar 02, 2022 |
| Dell          | Latitude 5411               | [c6e4b5cf11](https://linux-hardware.org/?probe=c6e4b5cf11) | Mar 02, 2022 |
| Lenovo        | G40-80 80JE                 | [476396ef7c](https://linux-hardware.org/?probe=476396ef7c) | Mar 02, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [f1d191a15c](https://linux-hardware.org/?probe=f1d191a15c) | Mar 02, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [46656cb5cc](https://linux-hardware.org/?probe=46656cb5cc) | Mar 02, 2022 |
| System76      | Oryx Pro                    | [7c9f5c83cf](https://linux-hardware.org/?probe=7c9f5c83cf) | Mar 01, 2022 |
| Lenovo        | IdeaPad Z510 20287          | [f61c04b0a8](https://linux-hardware.org/?probe=f61c04b0a8) | Mar 01, 2022 |
| Dell          | Latitude 7285               | [8d3fe46d72](https://linux-hardware.org/?probe=8d3fe46d72) | Mar 01, 2022 |
| HP            | EliteBook 840 G3            | [9ffc6b43ec](https://linux-hardware.org/?probe=9ffc6b43ec) | Feb 28, 2022 |
| Acer          | Aspire E1-522               | [4245cd910a](https://linux-hardware.org/?probe=4245cd910a) | Feb 28, 2022 |
| HP            | ProBook 650 G1              | [d58011c0f8](https://linux-hardware.org/?probe=d58011c0f8) | Feb 28, 2022 |
| HP            | ProBook 650 G1              | [6925ab1f20](https://linux-hardware.org/?probe=6925ab1f20) | Feb 28, 2022 |
| HP            | Notebook                    | [c8cd62d913](https://linux-hardware.org/?probe=c8cd62d913) | Feb 28, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [02ea37a7a8](https://linux-hardware.org/?probe=02ea37a7a8) | Feb 28, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [fa94978a0b](https://linux-hardware.org/?probe=fa94978a0b) | Feb 28, 2022 |
| Apple         | MacBookAir7,2               | [e2bc04b6f4](https://linux-hardware.org/?probe=e2bc04b6f4) | Feb 27, 2022 |
| Apple         | MacBookAir7,2               | [592d42e16c](https://linux-hardware.org/?probe=592d42e16c) | Feb 27, 2022 |
| Lenovo        | G70-70 80HW007LNX           | [a0ba78ccea](https://linux-hardware.org/?probe=a0ba78ccea) | Feb 27, 2022 |
| HP            | ProBook 640 G2              | [75cdf384b5](https://linux-hardware.org/?probe=75cdf384b5) | Feb 27, 2022 |
| HP            | Pavilion Notebook           | [57bb50b654](https://linux-hardware.org/?probe=57bb50b654) | Feb 27, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [0a92c063a1](https://linux-hardware.org/?probe=0a92c063a1) | Feb 27, 2022 |
| Samsung       | 550P5C/550P7C               | [24861666e2](https://linux-hardware.org/?probe=24861666e2) | Feb 27, 2022 |
| Lenovo        | IdeaPad S540-14IML Touch... | [22bb5f0b44](https://linux-hardware.org/?probe=22bb5f0b44) | Feb 27, 2022 |
| HUAWEI        | KLVL-WXX9                   | [efd62e1ed7](https://linux-hardware.org/?probe=efd62e1ed7) | Feb 26, 2022 |
| Dell          | XPS 13 9305                 | [36aacb1723](https://linux-hardware.org/?probe=36aacb1723) | Feb 26, 2022 |
| HP            | Pavilion g4                 | [0e40990ec2](https://linux-hardware.org/?probe=0e40990ec2) | Feb 26, 2022 |
| HP            | Pavilion 15                 | [463d26d75c](https://linux-hardware.org/?probe=463d26d75c) | Feb 26, 2022 |
| HP            | Pavilion 17                 | [d4a3fb2dfc](https://linux-hardware.org/?probe=d4a3fb2dfc) | Feb 26, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [02ac351573](https://linux-hardware.org/?probe=02ac351573) | Feb 25, 2022 |
| Acer          | Aspire E5-471               | [194baf83e9](https://linux-hardware.org/?probe=194baf83e9) | Feb 25, 2022 |
| Dell          | Latitude 3350               | [093650ba06](https://linux-hardware.org/?probe=093650ba06) | Feb 25, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [6b0f448d7b](https://linux-hardware.org/?probe=6b0f448d7b) | Feb 24, 2022 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [13b7868e73](https://linux-hardware.org/?probe=13b7868e73) | Feb 24, 2022 |
| Dell          | Inspiron 5567               | [0e9130cffe](https://linux-hardware.org/?probe=0e9130cffe) | Feb 24, 2022 |
| Google        | Snappy                      | [cf0b11bd65](https://linux-hardware.org/?probe=cf0b11bd65) | Feb 24, 2022 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [15df5df598](https://linux-hardware.org/?probe=15df5df598) | Feb 24, 2022 |
| ASUSTek       | X553MA                      | [020df21e37](https://linux-hardware.org/?probe=020df21e37) | Feb 23, 2022 |
| Sony          | VPCEH3S6E                   | [334451b6e7](https://linux-hardware.org/?probe=334451b6e7) | Feb 23, 2022 |
| Lenovo        | IdeaPad 3 15IML05 U 81WB    | [73c7d63295](https://linux-hardware.org/?probe=73c7d63295) | Feb 23, 2022 |
| Google        | Edgar                       | [46f5948f03](https://linux-hardware.org/?probe=46f5948f03) | Feb 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [f09566c9ee](https://linux-hardware.org/?probe=f09566c9ee) | Feb 23, 2022 |
| Samsung       | 750XDA                      | [ad6823c08e](https://linux-hardware.org/?probe=ad6823c08e) | Feb 23, 2022 |
| Lenovo        | ThinkPad T495 20NJ0004US    | [d8002e9eae](https://linux-hardware.org/?probe=d8002e9eae) | Feb 23, 2022 |
| MSI           | GE63VR 7RF                  | [68e1d81309](https://linux-hardware.org/?probe=68e1d81309) | Feb 23, 2022 |
| Apple         | MacBookPro12,1              | [677ffe54b5](https://linux-hardware.org/?probe=677ffe54b5) | Feb 23, 2022 |
| Dell          | Inspiron 7577               | [660240eb93](https://linux-hardware.org/?probe=660240eb93) | Feb 22, 2022 |
| HP            | ProBook 430 G5              | [b9cb7cad60](https://linux-hardware.org/?probe=b9cb7cad60) | Feb 22, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [ee3ef301c2](https://linux-hardware.org/?probe=ee3ef301c2) | Feb 22, 2022 |
| Jumper        | EZbook                      | [9cded25245](https://linux-hardware.org/?probe=9cded25245) | Feb 22, 2022 |
| Lenovo        | V14-ADA 82C6                | [94c0f0f3a3](https://linux-hardware.org/?probe=94c0f0f3a3) | Feb 22, 2022 |
| Panasonic     | CFSV9-1                     | [fa3b39bca1](https://linux-hardware.org/?probe=fa3b39bca1) | Feb 21, 2022 |
| HP            | Notebook                    | [d8dd214532](https://linux-hardware.org/?probe=d8dd214532) | Feb 21, 2022 |
| HP            | Laptop 14z-dk100            | [65130b9760](https://linux-hardware.org/?probe=65130b9760) | Feb 21, 2022 |
| eMachines     | E725 V1.03                  | [0f12be73fa](https://linux-hardware.org/?probe=0f12be73fa) | Feb 21, 2022 |
| Acer          | Swift SFX14-41G             | [5eb9d81462](https://linux-hardware.org/?probe=5eb9d81462) | Feb 20, 2022 |
| Acer          | Aspire A515-54G             | [388a17923c](https://linux-hardware.org/?probe=388a17923c) | Feb 20, 2022 |
| ASUSTek       | G551JK                      | [93e40c8fbc](https://linux-hardware.org/?probe=93e40c8fbc) | Feb 20, 2022 |
| Apple         | MacBookPro14,1              | [229a11c203](https://linux-hardware.org/?probe=229a11c203) | Feb 20, 2022 |
| Acer          | Aspire 5250                 | [65c44b63d6](https://linux-hardware.org/?probe=65c44b63d6) | Feb 20, 2022 |
| Acer          | Aspire 5250                 | [d8c4226f82](https://linux-hardware.org/?probe=d8c4226f82) | Feb 20, 2022 |
| Apple         | MacBookPro14,1              | [2a934577d6](https://linux-hardware.org/?probe=2a934577d6) | Feb 20, 2022 |
| HP            | Notebook                    | [b2bc5693f7](https://linux-hardware.org/?probe=b2bc5693f7) | Feb 20, 2022 |
| Apple         | MacBookAir5,2               | [dc8f1e8a38](https://linux-hardware.org/?probe=dc8f1e8a38) | Feb 20, 2022 |
| Acer          | Aspire E1-532G              | [2ec2b8bf53](https://linux-hardware.org/?probe=2ec2b8bf53) | Feb 20, 2022 |
| Acer          | Aspire A515-54G             | [5d973743c8](https://linux-hardware.org/?probe=5d973743c8) | Feb 19, 2022 |
| Acer          | Nitro AN515-44              | [c73dc0aa9f](https://linux-hardware.org/?probe=c73dc0aa9f) | Feb 19, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [1ad67d12e0](https://linux-hardware.org/?probe=1ad67d12e0) | Feb 19, 2022 |
| Positivo      | CHT14B                      | [c2f39e4414](https://linux-hardware.org/?probe=c2f39e4414) | Feb 19, 2022 |
| Positivo      | CHT14B                      | [674256dc2a](https://linux-hardware.org/?probe=674256dc2a) | Feb 19, 2022 |
| HP            | ZBook 17 G4                 | [0ac02f47be](https://linux-hardware.org/?probe=0ac02f47be) | Feb 19, 2022 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | [f988c3bfdc](https://linux-hardware.org/?probe=f988c3bfdc) | Feb 18, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [1c65c7204d](https://linux-hardware.org/?probe=1c65c7204d) | Feb 18, 2022 |
| Acer          | Aspire E5-575G              | [4cbc6b81bf](https://linux-hardware.org/?probe=4cbc6b81bf) | Feb 18, 2022 |
| Avell High... | B.ON                        | [3b3e1a7730](https://linux-hardware.org/?probe=3b3e1a7730) | Feb 18, 2022 |
| HP            | Laptop 15s-eq2xxx           | [3221ab6775](https://linux-hardware.org/?probe=3221ab6775) | Feb 17, 2022 |
| Dell          | Latitude E6330              | [4d2f890592](https://linux-hardware.org/?probe=4d2f890592) | Feb 17, 2022 |
| HP            | Dratini                     | [bb3f3445ee](https://linux-hardware.org/?probe=bb3f3445ee) | Feb 17, 2022 |
| Lenovo        | ThinkPad T450 20BUS0VH08    | [c896752de0](https://linux-hardware.org/?probe=c896752de0) | Feb 17, 2022 |
| Inspire Te... | Trio Windows OD 1.0         | [a0f755c28a](https://linux-hardware.org/?probe=a0f755c28a) | Feb 17, 2022 |
| Avell High... | B.ON                        | [26b25d67d6](https://linux-hardware.org/?probe=26b25d67d6) | Feb 17, 2022 |
| Acer          | Predator G9-793             | [45ec93214f](https://linux-hardware.org/?probe=45ec93214f) | Feb 16, 2022 |
| Samsung       | 900X3C/900X3D/900X3E/900... | [c81bbf6c93](https://linux-hardware.org/?probe=c81bbf6c93) | Feb 16, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [e03bf2b8a8](https://linux-hardware.org/?probe=e03bf2b8a8) | Feb 16, 2022 |
| System76      | Lemur Pro                   | [3a7527d1e3](https://linux-hardware.org/?probe=3a7527d1e3) | Feb 16, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [faca13ef0b](https://linux-hardware.org/?probe=faca13ef0b) | Feb 16, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [d2f55f9d63](https://linux-hardware.org/?probe=d2f55f9d63) | Feb 16, 2022 |
| ASUSTek       | T200TAC                     | [87db259935](https://linux-hardware.org/?probe=87db259935) | Feb 15, 2022 |
| Lenovo        | ThinkPad X200T 7449G6G      | [9a9f646438](https://linux-hardware.org/?probe=9a9f646438) | Feb 15, 2022 |
| HUAWEI        | KLVL-WXX9                   | [881b6c0f83](https://linux-hardware.org/?probe=881b6c0f83) | Feb 15, 2022 |
| ASUSTek       | X550WE                      | [beed529fc3](https://linux-hardware.org/?probe=beed529fc3) | Feb 14, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [f199e025e3](https://linux-hardware.org/?probe=f199e025e3) | Feb 14, 2022 |
| Dell          | XPS 15 9550                 | [701eeea0ed](https://linux-hardware.org/?probe=701eeea0ed) | Feb 14, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [32022a8232](https://linux-hardware.org/?probe=32022a8232) | Feb 14, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [372c231b58](https://linux-hardware.org/?probe=372c231b58) | Feb 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [a8c5477e60](https://linux-hardware.org/?probe=a8c5477e60) | Feb 13, 2022 |
| Lenovo        | ThinkPad Edge E531 68851... | [e82c11b42e](https://linux-hardware.org/?probe=e82c11b42e) | Feb 13, 2022 |
| HP            | Laptop 15s-eq2xxx           | [a4471fe730](https://linux-hardware.org/?probe=a4471fe730) | Feb 13, 2022 |
| Acer          | Aspire A514-54              | [1f5dd04a09](https://linux-hardware.org/?probe=1f5dd04a09) | Feb 13, 2022 |
| Apple         | MacBookPro12,1              | [aeec085062](https://linux-hardware.org/?probe=aeec085062) | Feb 13, 2022 |
| PC Special... | NH5xAx                      | [5e0b855dbf](https://linux-hardware.org/?probe=5e0b855dbf) | Feb 13, 2022 |
| Apple         | MacBookAir7,2               | [91fa01f5a6](https://linux-hardware.org/?probe=91fa01f5a6) | Feb 12, 2022 |
| Apple         | MacBookAir7,2               | [dc1249f2a1](https://linux-hardware.org/?probe=dc1249f2a1) | Feb 12, 2022 |
| HP            | ProBook 635 Aero G8 Note... | [42674c38b2](https://linux-hardware.org/?probe=42674c38b2) | Feb 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [46d98c991e](https://linux-hardware.org/?probe=46d98c991e) | Feb 12, 2022 |
| Acer          | Aspire A515-54G             | [f8e7f688a6](https://linux-hardware.org/?probe=f8e7f688a6) | Feb 11, 2022 |
| HP            | ProBook 450 G5              | [4c500fd383](https://linux-hardware.org/?probe=4c500fd383) | Feb 11, 2022 |
| HP            | ProBook 635 Aero G8 Note... | [2cfb1f14b9](https://linux-hardware.org/?probe=2cfb1f14b9) | Feb 10, 2022 |
| Dell          | Latitude 5511               | [7a45e17643](https://linux-hardware.org/?probe=7a45e17643) | Feb 10, 2022 |
| Dell          | Latitude 5511               | [bf3129ad00](https://linux-hardware.org/?probe=bf3129ad00) | Feb 10, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b2d14e7f15](https://linux-hardware.org/?probe=b2d14e7f15) | Feb 10, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [2661cf0743](https://linux-hardware.org/?probe=2661cf0743) | Feb 10, 2022 |
| Acer          | Nitro AN515-42              | [4906efe7f4](https://linux-hardware.org/?probe=4906efe7f4) | Feb 09, 2022 |
| HONOR         | NBD-WXX9                    | [83ab33660d](https://linux-hardware.org/?probe=83ab33660d) | Feb 09, 2022 |
| HONOR         | NBD-WXX9                    | [52bec77385](https://linux-hardware.org/?probe=52bec77385) | Feb 09, 2022 |
| Acer          | Nitro AN515-42              | [52d6fa9b66](https://linux-hardware.org/?probe=52d6fa9b66) | Feb 09, 2022 |
| HP            | EliteBook 840 G6            | [dae40dba1f](https://linux-hardware.org/?probe=dae40dba1f) | Feb 09, 2022 |
| Lenovo        | IdeaPad S340-14IWL 81N7     | [b7e0365760](https://linux-hardware.org/?probe=b7e0365760) | Feb 08, 2022 |
| ASUSTek       | X75VC                       | [55fda8de04](https://linux-hardware.org/?probe=55fda8de04) | Feb 08, 2022 |
| Lenovo        | ThinkPad E595 20NF001PTX    | [b4cfe297d4](https://linux-hardware.org/?probe=b4cfe297d4) | Feb 08, 2022 |
| Lenovo        | ThinkPad X230 23257R2       | [4fa07e0a61](https://linux-hardware.org/?probe=4fa07e0a61) | Feb 08, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [b400a64d30](https://linux-hardware.org/?probe=b400a64d30) | Feb 07, 2022 |
| Acer          | Aspire E5-575               | [cb02bc65cc](https://linux-hardware.org/?probe=cb02bc65cc) | Feb 07, 2022 |
| HP            | Pavilion dv6                | [0ba10bc3bb](https://linux-hardware.org/?probe=0ba10bc3bb) | Feb 07, 2022 |
| Lenovo        | Unknown                     | [8f315e1abe](https://linux-hardware.org/?probe=8f315e1abe) | Feb 07, 2022 |
| Lenovo        | Unknown                     | [bf281646d9](https://linux-hardware.org/?probe=bf281646d9) | Feb 07, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [5b6802c8e3](https://linux-hardware.org/?probe=5b6802c8e3) | Feb 07, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [61e4b1c45e](https://linux-hardware.org/?probe=61e4b1c45e) | Feb 06, 2022 |
| Lenovo        | G70-70 80HW007LNX           | [79e8d4895c](https://linux-hardware.org/?probe=79e8d4895c) | Feb 06, 2022 |
| Lenovo        | Ducati 5 82ES               | [3364f4de6b](https://linux-hardware.org/?probe=3364f4de6b) | Feb 06, 2022 |
| HP            | Compaq 6730s                | [8d1fa47bb0](https://linux-hardware.org/?probe=8d1fa47bb0) | Feb 06, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [73db0d90e9](https://linux-hardware.org/?probe=73db0d90e9) | Feb 06, 2022 |
| ASUSTek       | GL702VSK                    | [d3eb319919](https://linux-hardware.org/?probe=d3eb319919) | Feb 06, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [a3397b67bd](https://linux-hardware.org/?probe=a3397b67bd) | Feb 05, 2022 |
| Dell          | Inspiron 5537               | [79e02b1ade](https://linux-hardware.org/?probe=79e02b1ade) | Feb 05, 2022 |
| Lenovo        | ThinkPad X395 20NLCTO1WW    | [ce23fdbead](https://linux-hardware.org/?probe=ce23fdbead) | Feb 05, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | [d457ee5311](https://linux-hardware.org/?probe=d457ee5311) | Feb 05, 2022 |
| HP            | ProBook 450 G3              | [7b28e44b0e](https://linux-hardware.org/?probe=7b28e44b0e) | Feb 05, 2022 |
| HUAWEI        | NBM-WXX9                    | [5256293dec](https://linux-hardware.org/?probe=5256293dec) | Feb 05, 2022 |
| Framework     | Laptop                      | [64e6669cbc](https://linux-hardware.org/?probe=64e6669cbc) | Feb 04, 2022 |
| Dell          | Inspiron 5521               | [8d4968c10a](https://linux-hardware.org/?probe=8d4968c10a) | Feb 04, 2022 |
| Acer          | Aspire A515-43              | [6bc39a1855](https://linux-hardware.org/?probe=6bc39a1855) | Feb 04, 2022 |
| Toshiba       | Satellite C645              | [d552c9b132](https://linux-hardware.org/?probe=d552c9b132) | Feb 04, 2022 |
| HUAWEI        | KLVL-WXX9                   | [ca238c69a5](https://linux-hardware.org/?probe=ca238c69a5) | Feb 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [862367b523](https://linux-hardware.org/?probe=862367b523) | Feb 03, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [e32abec202](https://linux-hardware.org/?probe=e32abec202) | Feb 03, 2022 |
| Dell          | XPS 13 9310                 | [40c74584ee](https://linux-hardware.org/?probe=40c74584ee) | Feb 03, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [d9cc5f0548](https://linux-hardware.org/?probe=d9cc5f0548) | Feb 03, 2022 |
| Dell          | Latitude E6230              | [05d9080c0c](https://linux-hardware.org/?probe=05d9080c0c) | Feb 03, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [2cb72b3867](https://linux-hardware.org/?probe=2cb72b3867) | Feb 02, 2022 |
| HP            | EliteBook 830 G8 Noteboo... | [f111410eeb](https://linux-hardware.org/?probe=f111410eeb) | Feb 02, 2022 |
| Dell          | XPS 13 7390                 | [978273c0aa](https://linux-hardware.org/?probe=978273c0aa) | Feb 02, 2022 |
| Sony          | SVD1121Q2EB                 | [8e484b15d2](https://linux-hardware.org/?probe=8e484b15d2) | Feb 02, 2022 |
| HP            | ProBook 6465b               | [aca95b9f2d](https://linux-hardware.org/?probe=aca95b9f2d) | Feb 01, 2022 |
| Dell          | Vostro 3500                 | [c9cae610a6](https://linux-hardware.org/?probe=c9cae610a6) | Feb 01, 2022 |
| PC Special... | NH5xAx                      | [6c8a746762](https://linux-hardware.org/?probe=6c8a746762) | Feb 01, 2022 |
| Samsung       | RV409/RV509/RV709           | [535f5504f0](https://linux-hardware.org/?probe=535f5504f0) | Feb 01, 2022 |
| Dell          | Precision 5530              | [3bb85a7897](https://linux-hardware.org/?probe=3bb85a7897) | Jan 31, 2022 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [b7796bb104](https://linux-hardware.org/?probe=b7796bb104) | Jan 31, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | [8efcb72970](https://linux-hardware.org/?probe=8efcb72970) | Jan 31, 2022 |
| Lenovo        | Yoga S940-14IWL 81Q7        | [316ea97198](https://linux-hardware.org/?probe=316ea97198) | Jan 31, 2022 |
| Lenovo        | Yoga S940-14IWL 81Q7        | [940c2e990d](https://linux-hardware.org/?probe=940c2e990d) | Jan 31, 2022 |
| Lenovo        | IdeaPad Z500 20202          | [ebe757d792](https://linux-hardware.org/?probe=ebe757d792) | Jan 30, 2022 |
| Dell          | Latitude 7490               | [d3a6ac321f](https://linux-hardware.org/?probe=d3a6ac321f) | Jan 30, 2022 |
| Lenovo        | ThinkPad T490 20N2000LFR    | [0c7293a8ec](https://linux-hardware.org/?probe=0c7293a8ec) | Jan 30, 2022 |
| Lenovo        | ThinkPad T420 4180F65       | [23a97a1da0](https://linux-hardware.org/?probe=23a97a1da0) | Jan 30, 2022 |
| Apple         | MacBookPro14,1              | [88eae6cdfb](https://linux-hardware.org/?probe=88eae6cdfb) | Jan 30, 2022 |
| Apple         | MacBookPro14,1              | [d8040d8fc4](https://linux-hardware.org/?probe=d8040d8fc4) | Jan 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [c1494af863](https://linux-hardware.org/?probe=c1494af863) | Jan 30, 2022 |
| Lenovo        | ThinkPad T490 20N20009RT    | [538c4fb88c](https://linux-hardware.org/?probe=538c4fb88c) | Jan 30, 2022 |
| Lenovo        | ThinkPad E570 20H500B4MH    | [209156e57d](https://linux-hardware.org/?probe=209156e57d) | Jan 29, 2022 |
| Lenovo        | ThinkPad E570 20H500B4MH    | [2f9a17c907](https://linux-hardware.org/?probe=2f9a17c907) | Jan 29, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [e06431af49](https://linux-hardware.org/?probe=e06431af49) | Jan 29, 2022 |
| Apple         | MacBookAir6,2               | [2440be23b6](https://linux-hardware.org/?probe=2440be23b6) | Jan 29, 2022 |
| HP            | ZBook 17 G2                 | [4210faf0d2](https://linux-hardware.org/?probe=4210faf0d2) | Jan 29, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [4a98af8b6c](https://linux-hardware.org/?probe=4a98af8b6c) | Jan 29, 2022 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | [e6af97e09c](https://linux-hardware.org/?probe=e6af97e09c) | Jan 29, 2022 |
| Dell          | Latitude 5511               | [94f621a74b](https://linux-hardware.org/?probe=94f621a74b) | Jan 29, 2022 |
| Lenovo        | ThinkPad X240 20AMA2AN00    | [3d321c7afd](https://linux-hardware.org/?probe=3d321c7afd) | Jan 28, 2022 |
| Lenovo        | ThinkPad X240 20AMA2AN00    | [dd9909e9f4](https://linux-hardware.org/?probe=dd9909e9f4) | Jan 28, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [c573633ba7](https://linux-hardware.org/?probe=c573633ba7) | Jan 28, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [bab2021d07](https://linux-hardware.org/?probe=bab2021d07) | Jan 28, 2022 |
| ASUSTek       | X510UNR                     | [64f7ad2ba1](https://linux-hardware.org/?probe=64f7ad2ba1) | Jan 27, 2022 |
| Toshiba       | Satellite C660              | [8609aaadb3](https://linux-hardware.org/?probe=8609aaadb3) | Jan 27, 2022 |
| Apple         | MacBookPro9,2               | [d112bf0361](https://linux-hardware.org/?probe=d112bf0361) | Jan 27, 2022 |
| Mediacom      | GTZS                        | [10a0d977b0](https://linux-hardware.org/?probe=10a0d977b0) | Jan 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [f7633506c3](https://linux-hardware.org/?probe=f7633506c3) | Jan 26, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [b930fcaa84](https://linux-hardware.org/?probe=b930fcaa84) | Jan 26, 2022 |
| Dell          | XPS 13 7390                 | [95d6e59e28](https://linux-hardware.org/?probe=95d6e59e28) | Jan 26, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [738074142b](https://linux-hardware.org/?probe=738074142b) | Jan 26, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [1bd39d2b68](https://linux-hardware.org/?probe=1bd39d2b68) | Jan 26, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [9613005856](https://linux-hardware.org/?probe=9613005856) | Jan 26, 2022 |
| MSI           | CR61 2M/CX61 2OC/CX61 2O... | [36a39bf7eb](https://linux-hardware.org/?probe=36a39bf7eb) | Jan 26, 2022 |
| MSI           | CR61 2M/CX61 2OC/CX61 2O... | [9d12ae4f9a](https://linux-hardware.org/?probe=9d12ae4f9a) | Jan 26, 2022 |
| Acer          | Nitro AN515-52              | [e9f06efa7a](https://linux-hardware.org/?probe=e9f06efa7a) | Jan 26, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [041c78217d](https://linux-hardware.org/?probe=041c78217d) | Jan 26, 2022 |
| Dell          | Precision 5510              | [511eeac9a0](https://linux-hardware.org/?probe=511eeac9a0) | Jan 25, 2022 |
| Dell          | Latitude E7470              | [c47b0efb73](https://linux-hardware.org/?probe=c47b0efb73) | Jan 25, 2022 |
| HUAWEI        | KLVL-WXX9                   | [5846d2031f](https://linux-hardware.org/?probe=5846d2031f) | Jan 25, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [c7fbcbcd07](https://linux-hardware.org/?probe=c7fbcbcd07) | Jan 25, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [f36cdb65e7](https://linux-hardware.org/?probe=f36cdb65e7) | Jan 24, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [e9c2ec480a](https://linux-hardware.org/?probe=e9c2ec480a) | Jan 24, 2022 |
| Acer          | Nitro AN515-45              | [34568da477](https://linux-hardware.org/?probe=34568da477) | Jan 23, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [d6ea0ad749](https://linux-hardware.org/?probe=d6ea0ad749) | Jan 23, 2022 |
| Acer          | Nitro AN515-45              | [1cb9ebbbd4](https://linux-hardware.org/?probe=1cb9ebbbd4) | Jan 23, 2022 |
| HP            | Laptop 15s-eq2xxx           | [e10bf3d056](https://linux-hardware.org/?probe=e10bf3d056) | Jan 23, 2022 |
| SCHNEIDER     | SCL141CTP                   | [ff14e3fa97](https://linux-hardware.org/?probe=ff14e3fa97) | Jan 23, 2022 |
| Apple         | MacBookPro14,1              | [783456509a](https://linux-hardware.org/?probe=783456509a) | Jan 22, 2022 |
| HP            | ProBook 470 G5              | [6610c7d6e1](https://linux-hardware.org/?probe=6610c7d6e1) | Jan 22, 2022 |
| Dell          | Inspiron N5110              | [3253470667](https://linux-hardware.org/?probe=3253470667) | Jan 22, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [427ce82d40](https://linux-hardware.org/?probe=427ce82d40) | Jan 22, 2022 |
| Acer          | Aspire ES1-111M             | [02368f5bb1](https://linux-hardware.org/?probe=02368f5bb1) | Jan 22, 2022 |
| HP            | ENVY Laptop 15-ep0xxx       | [2c0f007811](https://linux-hardware.org/?probe=2c0f007811) | Jan 22, 2022 |
| HP            | EliteBook 840 G3            | [4ef203e4a1](https://linux-hardware.org/?probe=4ef203e4a1) | Jan 22, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [636e98e6e5](https://linux-hardware.org/?probe=636e98e6e5) | Jan 21, 2022 |
| Dell          | XPS 13 9350                 | [485c5e0968](https://linux-hardware.org/?probe=485c5e0968) | Jan 21, 2022 |
| Notebook      | NH55RGQ                     | [92e8102b7d](https://linux-hardware.org/?probe=92e8102b7d) | Jan 21, 2022 |
| Dell          | Latitude E6530              | [bf71e70abb](https://linux-hardware.org/?probe=bf71e70abb) | Jan 21, 2022 |
| Dell          | Inspiron 7591               | [2f1c294587](https://linux-hardware.org/?probe=2f1c294587) | Jan 21, 2022 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | [c63c055197](https://linux-hardware.org/?probe=c63c055197) | Jan 21, 2022 |
| HP            | Laptop 15s-fq2xxx           | [172a8a48ad](https://linux-hardware.org/?probe=172a8a48ad) | Jan 21, 2022 |
| Acer          | Aspire A315-41G             | [03a8c77758](https://linux-hardware.org/?probe=03a8c77758) | Jan 20, 2022 |
| Acer          | Aspire A315-41G             | [df698a1427](https://linux-hardware.org/?probe=df698a1427) | Jan 20, 2022 |
| Lenovo        | B490 37722QP                | [6b32b6b8ef](https://linux-hardware.org/?probe=6b32b6b8ef) | Jan 20, 2022 |
| HP            | Compaq 6710b (RM405UT#AB... | [0ae4377d83](https://linux-hardware.org/?probe=0ae4377d83) | Jan 19, 2022 |
| Acer          | Aspire E5-573G              | [30829ce42e](https://linux-hardware.org/?probe=30829ce42e) | Jan 19, 2022 |
| HP            | Compaq 6710b (RM405UT#AB... | [1a128aada0](https://linux-hardware.org/?probe=1a128aada0) | Jan 19, 2022 |
| Positivo      | H14BU08                     | [8fb0d7e730](https://linux-hardware.org/?probe=8fb0d7e730) | Jan 19, 2022 |
| Acer          | Swift SF314-42              | [a2e70fe7b1](https://linux-hardware.org/?probe=a2e70fe7b1) | Jan 19, 2022 |
| HP            | Pavilion Notebook           | [533f74b810](https://linux-hardware.org/?probe=533f74b810) | Jan 19, 2022 |
| ASUSTek       | ROG Zephyrus M15 GU502LW... | [2407b5f5bb](https://linux-hardware.org/?probe=2407b5f5bb) | Jan 19, 2022 |
| Dell          | Latitude E6530              | [8559d4a5b0](https://linux-hardware.org/?probe=8559d4a5b0) | Jan 19, 2022 |
| Lenovo        | B490 37722QP                | [3113fb2078](https://linux-hardware.org/?probe=3113fb2078) | Jan 18, 2022 |
| Lenovo        | ThinkPad X240 20AMS1S800    | [a168ef0aa5](https://linux-hardware.org/?probe=a168ef0aa5) | Jan 18, 2022 |
| Notebook      | NH5x_NH7x_HHx_HJx_HKx       | [738f12d2e4](https://linux-hardware.org/?probe=738f12d2e4) | Jan 17, 2022 |
| Acer          | Predator PH315-51           | [d6edc6139f](https://linux-hardware.org/?probe=d6edc6139f) | Jan 17, 2022 |
| Jumper        | EZbook                      | [6c949f1929](https://linux-hardware.org/?probe=6c949f1929) | Jan 17, 2022 |
| HP            | ProBook 650 G1              | [8d78cc6770](https://linux-hardware.org/?probe=8d78cc6770) | Jan 16, 2022 |
| Lenovo        | ThinkPad X61s 7666WCQ       | [7e1d764ca8](https://linux-hardware.org/?probe=7e1d764ca8) | Jan 16, 2022 |
| Notebook      | NS50MU                      | [8527a3e637](https://linux-hardware.org/?probe=8527a3e637) | Jan 16, 2022 |
| Lenovo        | ThinkPad T410 2522PT3       | [a61f1b9d56](https://linux-hardware.org/?probe=a61f1b9d56) | Jan 16, 2022 |
| HP            | Pavilion 11 x360 PC         | [0c41cd2cd0](https://linux-hardware.org/?probe=0c41cd2cd0) | Jan 16, 2022 |
| HP            | Pavilion 11 x360 PC         | [750744f996](https://linux-hardware.org/?probe=750744f996) | Jan 16, 2022 |
| Acer          | Swift SF114-34              | [2098bc3881](https://linux-hardware.org/?probe=2098bc3881) | Jan 16, 2022 |
| HP            | ProBook 650 G1              | [829a2b8221](https://linux-hardware.org/?probe=829a2b8221) | Jan 15, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [779202413e](https://linux-hardware.org/?probe=779202413e) | Jan 15, 2022 |
| Dell          | Latitude 5480               | [6e363cb43c](https://linux-hardware.org/?probe=6e363cb43c) | Jan 15, 2022 |
| HP            | 15                          | [65d1bd3651](https://linux-hardware.org/?probe=65d1bd3651) | Jan 15, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [350fb6b638](https://linux-hardware.org/?probe=350fb6b638) | Jan 14, 2022 |
| Dell          | XPS 13 9310                 | [f695de13bf](https://linux-hardware.org/?probe=f695de13bf) | Jan 14, 2022 |
| Dell          | Inspiron M5010              | [21dddfe6a8](https://linux-hardware.org/?probe=21dddfe6a8) | Jan 14, 2022 |
| Apple         | MacBookPro11,3              | [0fbef723d5](https://linux-hardware.org/?probe=0fbef723d5) | Jan 14, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [b2ac4f1622](https://linux-hardware.org/?probe=b2ac4f1622) | Jan 13, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [ee8a872afd](https://linux-hardware.org/?probe=ee8a872afd) | Jan 13, 2022 |
| Lenovo        | ThinkPad T440p 20AWS2CH0... | [7f440733c2](https://linux-hardware.org/?probe=7f440733c2) | Jan 13, 2022 |
| Apple         | MacBook6,1                  | [e9f23e9f5f](https://linux-hardware.org/?probe=e9f23e9f5f) | Jan 13, 2022 |
| Apple         | MacBook6,1                  | [85d81f357a](https://linux-hardware.org/?probe=85d81f357a) | Jan 13, 2022 |
| Lenovo        | ThinkPad T430u 3351CTO      | [41f9777fcf](https://linux-hardware.org/?probe=41f9777fcf) | Jan 13, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [45d63385d2](https://linux-hardware.org/?probe=45d63385d2) | Jan 12, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [9fa645342b](https://linux-hardware.org/?probe=9fa645342b) | Jan 12, 2022 |
| Lenovo        | ThinkPad E15 20RD0015PG     | [008fd40914](https://linux-hardware.org/?probe=008fd40914) | Jan 11, 2022 |
| Dell          | XPS 13 7390                 | [10dea3ac81](https://linux-hardware.org/?probe=10dea3ac81) | Jan 11, 2022 |
| Lenovo        | IdeaPad Y470 20090          | [29ff376953](https://linux-hardware.org/?probe=29ff376953) | Jan 11, 2022 |
| Lenovo        | IdeaPad S540-15IWL          | [34bf588c0b](https://linux-hardware.org/?probe=34bf588c0b) | Jan 11, 2022 |
| Dell          | Venue 10 Pro 5055           | [22d084e747](https://linux-hardware.org/?probe=22d084e747) | Jan 11, 2022 |
| Lenovo        | IdeaPad S540-15IWL          | [63c5a7136b](https://linux-hardware.org/?probe=63c5a7136b) | Jan 11, 2022 |
| HP            | EliteBook 820 G1            | [37dd78dd6e](https://linux-hardware.org/?probe=37dd78dd6e) | Jan 11, 2022 |
| Lenovo        | ThinkPad T530 239265U       | [5aba32fde1](https://linux-hardware.org/?probe=5aba32fde1) | Jan 11, 2022 |
| Toshiba       | Satellite L855              | [5668d7e463](https://linux-hardware.org/?probe=5668d7e463) | Jan 10, 2022 |
| Toshiba       | Satellite L855              | [f14ba2d184](https://linux-hardware.org/?probe=f14ba2d184) | Jan 10, 2022 |
| Lenovo        | ThinkPad T460s 20FAS1NF0... | [b6b9155c53](https://linux-hardware.org/?probe=b6b9155c53) | Jan 10, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [62bf8bc805](https://linux-hardware.org/?probe=62bf8bc805) | Jan 10, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [72db511d09](https://linux-hardware.org/?probe=72db511d09) | Jan 10, 2022 |
| HP            | Laptop 15s-eq2xxx           | [2fa4c0880f](https://linux-hardware.org/?probe=2fa4c0880f) | Jan 09, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | [6b6c84515a](https://linux-hardware.org/?probe=6b6c84515a) | Jan 09, 2022 |
| Lenovo        | ThinkPad X260 20F5S0W22B    | [b9812a839e](https://linux-hardware.org/?probe=b9812a839e) | Jan 09, 2022 |
| Toshiba       | Satellite C55-A-1NU         | [208f411c99](https://linux-hardware.org/?probe=208f411c99) | Jan 08, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [dc436bb38c](https://linux-hardware.org/?probe=dc436bb38c) | Jan 08, 2022 |
| Dell          | XPS 13 9310                 | [e0dfa537f4](https://linux-hardware.org/?probe=e0dfa537f4) | Jan 08, 2022 |
| Notebook      | P15SM                       | [3b7c794008](https://linux-hardware.org/?probe=3b7c794008) | Jan 08, 2022 |
| Dell          | Precision 3551              | [73d2d759ba](https://linux-hardware.org/?probe=73d2d759ba) | Jan 07, 2022 |
| Dell          | XPS 13 9310                 | [aa1ce4d9ca](https://linux-hardware.org/?probe=aa1ce4d9ca) | Jan 07, 2022 |
| Dell          | Precision 5510              | [7a763a42bb](https://linux-hardware.org/?probe=7a763a42bb) | Jan 07, 2022 |
| Toshiba       | Satellite L755              | [df6cc34c45](https://linux-hardware.org/?probe=df6cc34c45) | Jan 07, 2022 |
| Razer         | Book 13 - RZ09-0357         | [148a68191d](https://linux-hardware.org/?probe=148a68191d) | Jan 06, 2022 |
| Apple         | MacBookPro14,1              | [a37ac164fb](https://linux-hardware.org/?probe=a37ac164fb) | Jan 06, 2022 |
| Apple         | MacBookPro14,1              | [51930e8d89](https://linux-hardware.org/?probe=51930e8d89) | Jan 06, 2022 |
| HUAWEI        | MACHD-WXX9                  | [6c5e2e7851](https://linux-hardware.org/?probe=6c5e2e7851) | Jan 06, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [cafe68988e](https://linux-hardware.org/?probe=cafe68988e) | Jan 06, 2022 |
| HP            | OMEN by Laptop 15-dc1xxx    | [8d8227634a](https://linux-hardware.org/?probe=8d8227634a) | Jan 06, 2022 |
| Panasonic     | CF-195FYCALM                | [19ad0002e5](https://linux-hardware.org/?probe=19ad0002e5) | Jan 06, 2022 |
| HP            | Laptop 15s-eq2xxx           | [527c2f975b](https://linux-hardware.org/?probe=527c2f975b) | Jan 05, 2022 |
| Samsung       | 550XDA                      | [1bdf544285](https://linux-hardware.org/?probe=1bdf544285) | Jan 05, 2022 |
| Lenovo        | ThinkPad T490 20N3S2NJ00    | [e9170a81fe](https://linux-hardware.org/?probe=e9170a81fe) | Jan 05, 2022 |
| Dell          | Latitude E6520              | [f9c32b0bee](https://linux-hardware.org/?probe=f9c32b0bee) | Jan 05, 2022 |
| Dell          | Latitude E7440              | [c8811522dd](https://linux-hardware.org/?probe=c8811522dd) | Jan 05, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B3302CEA... | [270443c029](https://linux-hardware.org/?probe=270443c029) | Jan 05, 2022 |
| Sony          | VPCEB3PGX                   | [b97121f86e](https://linux-hardware.org/?probe=b97121f86e) | Jan 05, 2022 |
| Sony          | VPCEB3PGX                   | [9fa953475a](https://linux-hardware.org/?probe=9fa953475a) | Jan 05, 2022 |
| HP            | ProBook 450 G1              | [3a0d2d3754](https://linux-hardware.org/?probe=3a0d2d3754) | Jan 05, 2022 |
| HP            | ProBook 450 G1              | [4516e6113b](https://linux-hardware.org/?probe=4516e6113b) | Jan 05, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [8d492fa1d4](https://linux-hardware.org/?probe=8d492fa1d4) | Jan 05, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [56a85d54e4](https://linux-hardware.org/?probe=56a85d54e4) | Jan 04, 2022 |
| Dell          | Latitude E5550              | [8956b15ec8](https://linux-hardware.org/?probe=8956b15ec8) | Jan 04, 2022 |
| Acer          | Swift SF114-34              | [3d15bf4d48](https://linux-hardware.org/?probe=3d15bf4d48) | Jan 04, 2022 |
| Acer          | Extensa 2540                | [c3587d4c57](https://linux-hardware.org/?probe=c3587d4c57) | Jan 04, 2022 |
| Positivo      | VJF155F11UAR                | [9ac42b2131](https://linux-hardware.org/?probe=9ac42b2131) | Jan 04, 2022 |
| Acer          | Extensa 2540                | [0a39d6fe8c](https://linux-hardware.org/?probe=0a39d6fe8c) | Jan 04, 2022 |
| Positivo      | VJF155F11UAR                | [e8bc9392ff](https://linux-hardware.org/?probe=e8bc9392ff) | Jan 04, 2022 |
| Dell          | Latitude 3470               | [9e4742c283](https://linux-hardware.org/?probe=9e4742c283) | Jan 04, 2022 |
| Dell          | Inspiron 7591               | [4044cf11d2](https://linux-hardware.org/?probe=4044cf11d2) | Jan 04, 2022 |
| Dell          | Inspiron 5402               | [3cae008c9d](https://linux-hardware.org/?probe=3cae008c9d) | Jan 04, 2022 |
| Lenovo        | Yoga 2 Pro 20266            | [d5e7352413](https://linux-hardware.org/?probe=d5e7352413) | Jan 04, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [7f5e49e07a](https://linux-hardware.org/?probe=7f5e49e07a) | Jan 04, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [8cd52a2f8f](https://linux-hardware.org/?probe=8cd52a2f8f) | Jan 03, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [3953d7ae46](https://linux-hardware.org/?probe=3953d7ae46) | Jan 03, 2022 |
| Dell          | XPS 15 7590                 | [b661a2cdf0](https://linux-hardware.org/?probe=b661a2cdf0) | Jan 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [60514a96e4](https://linux-hardware.org/?probe=60514a96e4) | Jan 02, 2022 |
| ASUSTek       | X542URR                     | [8af11eb0f1](https://linux-hardware.org/?probe=8af11eb0f1) | Jan 02, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [0692c6e121](https://linux-hardware.org/?probe=0692c6e121) | Jan 02, 2022 |
| HP            | Laptop 15s-eq2xxx           | [3bfe8cb49e](https://linux-hardware.org/?probe=3bfe8cb49e) | Jan 01, 2022 |
| Dell          | Latitude E5570              | [34af93663b](https://linux-hardware.org/?probe=34af93663b) | Dec 31, 2021 |
| Google        | Coral                       | [23a0352176](https://linux-hardware.org/?probe=23a0352176) | Dec 31, 2021 |
| ASUSTek       | TP300LD                     | [13e63153f1](https://linux-hardware.org/?probe=13e63153f1) | Dec 31, 2021 |
| Dell          | XPS 13 9380                 | [cd66e486be](https://linux-hardware.org/?probe=cd66e486be) | Dec 31, 2021 |
| Apple         | MacBookPro8,2               | [298d5a0323](https://linux-hardware.org/?probe=298d5a0323) | Dec 31, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [9d60e196d4](https://linux-hardware.org/?probe=9d60e196d4) | Dec 31, 2021 |
| Lenovo        | ThinkPad T460 20FMS1R01K    | [c6dbec8e70](https://linux-hardware.org/?probe=c6dbec8e70) | Dec 31, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS5... | [c1eeaec01b](https://linux-hardware.org/?probe=c1eeaec01b) | Dec 30, 2021 |
| Google        | Chell                       | [9a2a4a03ed](https://linux-hardware.org/?probe=9a2a4a03ed) | Dec 30, 2021 |
| Lenovo        | ThinkPad T490 20N3S6VU00    | [afb7fa66f5](https://linux-hardware.org/?probe=afb7fa66f5) | Dec 30, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [bfd79da0e0](https://linux-hardware.org/?probe=bfd79da0e0) | Dec 30, 2021 |
| Dell          | Inspiron 3521               | [af800e1071](https://linux-hardware.org/?probe=af800e1071) | Dec 29, 2021 |
| Lenovo        | IdeaPad S540-15IWL          | [c3497fe5bd](https://linux-hardware.org/?probe=c3497fe5bd) | Dec 29, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [4dfe6a5b8c](https://linux-hardware.org/?probe=4dfe6a5b8c) | Dec 29, 2021 |
| Dell          | Inspiron 7559               | [12ba9454e7](https://linux-hardware.org/?probe=12ba9454e7) | Dec 29, 2021 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [c539559392](https://linux-hardware.org/?probe=c539559392) | Dec 29, 2021 |
| Lenovo        | ThinkPad T520 4243B96       | [9ba0058839](https://linux-hardware.org/?probe=9ba0058839) | Dec 29, 2021 |
| Lenovo        | ThinkPad T520 4243B96       | [dbcf70aced](https://linux-hardware.org/?probe=dbcf70aced) | Dec 29, 2021 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | [41b463b6c4](https://linux-hardware.org/?probe=41b463b6c4) | Dec 28, 2021 |
| Hampoo        | C3W6_AP108_4GB Reserved     | [433a512192](https://linux-hardware.org/?probe=433a512192) | Dec 28, 2021 |
| Lenovo        | ThinkPad E480 20KN001QPB    | [0615d7a112](https://linux-hardware.org/?probe=0615d7a112) | Dec 28, 2021 |
| Lenovo        | ThinkPad T550 20CKA00ECD    | [bea75ed7d5](https://linux-hardware.org/?probe=bea75ed7d5) | Dec 27, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [cc15a65a54](https://linux-hardware.org/?probe=cc15a65a54) | Dec 27, 2021 |
| Toshiba       | Satellite L12-C-104         | [fae8f8e1f9](https://linux-hardware.org/?probe=fae8f8e1f9) | Dec 27, 2021 |
| HUAWEI        | HVY-WXX9                    | [23460afe38](https://linux-hardware.org/?probe=23460afe38) | Dec 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [23db048750](https://linux-hardware.org/?probe=23db048750) | Dec 27, 2021 |
| HP            | ZBook Fury 15 G7 Mobile ... | [707835b4ff](https://linux-hardware.org/?probe=707835b4ff) | Dec 27, 2021 |
| HP            | Laptop 15s-eq0xxx           | [f255947b6f](https://linux-hardware.org/?probe=f255947b6f) | Dec 27, 2021 |
| Dell          | XPS 13 7390                 | [572bbe8d7b](https://linux-hardware.org/?probe=572bbe8d7b) | Dec 27, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [86651ee07a](https://linux-hardware.org/?probe=86651ee07a) | Dec 26, 2021 |
| Lenovo        | Ducati 5 82ES               | [61dd257cc7](https://linux-hardware.org/?probe=61dd257cc7) | Dec 26, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [56c0a83ab8](https://linux-hardware.org/?probe=56c0a83ab8) | Dec 26, 2021 |
| MSI           | Alpha 15 B5EEK              | [e076af5bf8](https://linux-hardware.org/?probe=e076af5bf8) | Dec 26, 2021 |
| HP            | 2000                        | [e3408eb743](https://linux-hardware.org/?probe=e3408eb743) | Dec 26, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [1e8ce2ec6d](https://linux-hardware.org/?probe=1e8ce2ec6d) | Dec 25, 2021 |
| Dell          | Inspiron 5558               | [58e49e7f72](https://linux-hardware.org/?probe=58e49e7f72) | Dec 25, 2021 |
| Dell          | Latitude 7410               | [71a96bfc8f](https://linux-hardware.org/?probe=71a96bfc8f) | Dec 25, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [6fe369b6b7](https://linux-hardware.org/?probe=6fe369b6b7) | Dec 25, 2021 |
| Cube          | i18-L                       | [6770cf2a44](https://linux-hardware.org/?probe=6770cf2a44) | Dec 24, 2021 |
| Lenovo        | V470 439627U                | [7c44d560dc](https://linux-hardware.org/?probe=7c44d560dc) | Dec 24, 2021 |
| HP            | EliteBook 2570p             | [a02655b4b8](https://linux-hardware.org/?probe=a02655b4b8) | Dec 24, 2021 |
| HP            | EliteBook 2570p             | [6e08796257](https://linux-hardware.org/?probe=6e08796257) | Dec 24, 2021 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | [44dd4eee41](https://linux-hardware.org/?probe=44dd4eee41) | Dec 24, 2021 |
| HP            | Laptop 14-dk1xxx            | [ab7902b875](https://linux-hardware.org/?probe=ab7902b875) | Dec 24, 2021 |
| LDLC          | Mercure MH                  | [ff094fa4f3](https://linux-hardware.org/?probe=ff094fa4f3) | Dec 23, 2021 |
| Lenovo        | ThinkPad X250 20CLS2B000    | [abba53c091](https://linux-hardware.org/?probe=abba53c091) | Dec 23, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [1962ddfdb4](https://linux-hardware.org/?probe=1962ddfdb4) | Dec 23, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [d6d85114b6](https://linux-hardware.org/?probe=d6d85114b6) | Dec 23, 2021 |
| HP            | 250 G1                      | [da8e31b740](https://linux-hardware.org/?probe=da8e31b740) | Dec 23, 2021 |
| Dell          | Inspiron 5447               | [83331a9c7c](https://linux-hardware.org/?probe=83331a9c7c) | Dec 22, 2021 |
| Acer          | Aspire A315-41              | [85da21d9e9](https://linux-hardware.org/?probe=85da21d9e9) | Dec 22, 2021 |
| Apple         | MacBookPro11,3              | [1975ee2fc0](https://linux-hardware.org/?probe=1975ee2fc0) | Dec 22, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [df0d434539](https://linux-hardware.org/?probe=df0d434539) | Dec 22, 2021 |
| Apple         | MacBookPro7,1               | [5994dbd498](https://linux-hardware.org/?probe=5994dbd498) | Dec 21, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [9724b1359d](https://linux-hardware.org/?probe=9724b1359d) | Dec 21, 2021 |
| Notebook      | NH5x_NH7xHP                 | [0408aca941](https://linux-hardware.org/?probe=0408aca941) | Dec 21, 2021 |
| Apple         | MacBookPro14,1              | [e82554da93](https://linux-hardware.org/?probe=e82554da93) | Dec 21, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [7fc27f5255](https://linux-hardware.org/?probe=7fc27f5255) | Dec 21, 2021 |
| Apple         | MacBookPro7,1               | [5f47284626](https://linux-hardware.org/?probe=5f47284626) | Dec 21, 2021 |
| Apple         | MacBookPro14,1              | [022cabd3f2](https://linux-hardware.org/?probe=022cabd3f2) | Dec 21, 2021 |
| HP            | Laptop 15s-eq2xxx           | [8cd9d762c9](https://linux-hardware.org/?probe=8cd9d762c9) | Dec 20, 2021 |
| HP            | Pavilion 15                 | [7248fa574f](https://linux-hardware.org/?probe=7248fa574f) | Dec 20, 2021 |
| Notebook      | N24_25JU                    | [8ac7d4890e](https://linux-hardware.org/?probe=8ac7d4890e) | Dec 20, 2021 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [ddb3571ec6](https://linux-hardware.org/?probe=ddb3571ec6) | Dec 20, 2021 |
| HP            | Laptop 15s-eq2xxx           | [bb28c266ec](https://linux-hardware.org/?probe=bb28c266ec) | Dec 19, 2021 |
| HUAWEI        | HVY-WXX9                    | [d335e16395](https://linux-hardware.org/?probe=d335e16395) | Dec 19, 2021 |
| Samsung       | RV410/RV510/S3510/E3510     | [9c38b95aa0](https://linux-hardware.org/?probe=9c38b95aa0) | Dec 19, 2021 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [e380536aac](https://linux-hardware.org/?probe=e380536aac) | Dec 19, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [87399b5e8b](https://linux-hardware.org/?probe=87399b5e8b) | Dec 19, 2021 |
| HUAWEI        | NBLB-WAX9N                  | [ffd979b53f](https://linux-hardware.org/?probe=ffd979b53f) | Dec 19, 2021 |
| HUAWEI        | HVY-WXX9                    | [85e3feaeba](https://linux-hardware.org/?probe=85e3feaeba) | Dec 19, 2021 |
| Lenovo        | ThinkPad E580 20KS001EMX    | [366aae1cd6](https://linux-hardware.org/?probe=366aae1cd6) | Dec 18, 2021 |
| Acer          | Nitro AN515-53              | [a9affc8e28](https://linux-hardware.org/?probe=a9affc8e28) | Dec 18, 2021 |
| Dell          | Precision 5540              | [14a6857b99](https://linux-hardware.org/?probe=14a6857b99) | Dec 18, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS5... | [cda7a2c35c](https://linux-hardware.org/?probe=cda7a2c35c) | Dec 17, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [6bf6c57117](https://linux-hardware.org/?probe=6bf6c57117) | Dec 17, 2021 |
| HP            | ENVY Pro 4-b000 Ultraboo... | [1bac69aa61](https://linux-hardware.org/?probe=1bac69aa61) | Dec 17, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [e985e04d6d](https://linux-hardware.org/?probe=e985e04d6d) | Dec 17, 2021 |
| Lenovo        | Yoga S740-14IIL 81RS        | [6deb57beb2](https://linux-hardware.org/?probe=6deb57beb2) | Dec 17, 2021 |
| Dell          | XPS 15 9500                 | [98e451612c](https://linux-hardware.org/?probe=98e451612c) | Dec 17, 2021 |
| AVITA         | NS14A1US                    | [e20bf09217](https://linux-hardware.org/?probe=e20bf09217) | Dec 16, 2021 |
| HP            | Laptop 15s-eq2xxx           | [290b1d081b](https://linux-hardware.org/?probe=290b1d081b) | Dec 16, 2021 |
| Dell          | XPS 17 9700                 | [aba6548652](https://linux-hardware.org/?probe=aba6548652) | Dec 16, 2021 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [30a4a58c5d](https://linux-hardware.org/?probe=30a4a58c5d) | Dec 16, 2021 |
| Dell          | XPS 15 9500                 | [4d52a02213](https://linux-hardware.org/?probe=4d52a02213) | Dec 16, 2021 |
| Dell          | XPS 17 9700                 | [ff779fe08f](https://linux-hardware.org/?probe=ff779fe08f) | Dec 16, 2021 |
| MSI           | GL63 9SC                    | [ed637c5d15](https://linux-hardware.org/?probe=ed637c5d15) | Dec 16, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [0fc861a848](https://linux-hardware.org/?probe=0fc861a848) | Dec 16, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [39491139d5](https://linux-hardware.org/?probe=39491139d5) | Dec 15, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [615d071a26](https://linux-hardware.org/?probe=615d071a26) | Dec 15, 2021 |
| HP            | Pavilion dv7                | [0e0f0e3c23](https://linux-hardware.org/?probe=0e0f0e3c23) | Dec 15, 2021 |
| Dell          | Latitude 5500               | [5b9479065e](https://linux-hardware.org/?probe=5b9479065e) | Dec 15, 2021 |
| Lenovo        | ThinkPad E14 20RA007TUE     | [3edd54970c](https://linux-hardware.org/?probe=3edd54970c) | Dec 15, 2021 |
| ASUSTek       | K43U                        | [d7df2cd94e](https://linux-hardware.org/?probe=d7df2cd94e) | Dec 15, 2021 |
| Acer          | Swift SF314-43              | [2cabe8184b](https://linux-hardware.org/?probe=2cabe8184b) | Dec 15, 2021 |
| HP            | ENVY Pro 4-b000 Ultraboo... | [20259384ac](https://linux-hardware.org/?probe=20259384ac) | Dec 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [4290797f32](https://linux-hardware.org/?probe=4290797f32) | Dec 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [fb79be9e00](https://linux-hardware.org/?probe=fb79be9e00) | Dec 14, 2021 |
| Dell          | Inspiron 15 5510            | [dd29feeb10](https://linux-hardware.org/?probe=dd29feeb10) | Dec 14, 2021 |
| Dell          | Latitude 7300               | [23f38f8a7d](https://linux-hardware.org/?probe=23f38f8a7d) | Dec 14, 2021 |
| Acer          | Aspire A515-55              | [8d121836c9](https://linux-hardware.org/?probe=8d121836c9) | Dec 14, 2021 |
| Dell          | Latitude 7490               | [ae8a45bc5a](https://linux-hardware.org/?probe=ae8a45bc5a) | Dec 14, 2021 |
| Dell          | Inspiron 16 7610            | [e0d697a356](https://linux-hardware.org/?probe=e0d697a356) | Dec 14, 2021 |
| Acer          | Swift SF314-43              | [fd53be96e6](https://linux-hardware.org/?probe=fd53be96e6) | Dec 13, 2021 |
| Notebook      | NH5xAx                      | [fcd36c9b82](https://linux-hardware.org/?probe=fcd36c9b82) | Dec 13, 2021 |
| Dell          | Vostro 5402                 | [2074bdb7a5](https://linux-hardware.org/?probe=2074bdb7a5) | Dec 13, 2021 |
| MSI           | Modern 14 B5M               | [5274b5a06c](https://linux-hardware.org/?probe=5274b5a06c) | Dec 13, 2021 |
| Avell High... | A70 LIV                     | [3930fc87b1](https://linux-hardware.org/?probe=3930fc87b1) | Dec 12, 2021 |
| Acer          | Aspire A315-31              | [24c8e29d95](https://linux-hardware.org/?probe=24c8e29d95) | Dec 12, 2021 |
| Dell          | Latitude 7290               | [8a2ecfe430](https://linux-hardware.org/?probe=8a2ecfe430) | Dec 12, 2021 |
| Acer          | Nitro AN515-45              | [5975d86599](https://linux-hardware.org/?probe=5975d86599) | Dec 12, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [1846fa72b5](https://linux-hardware.org/?probe=1846fa72b5) | Dec 12, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1H60... | [ffb1c97626](https://linux-hardware.org/?probe=ffb1c97626) | Dec 12, 2021 |
| Dell          | Inspiron 5515               | [901f720089](https://linux-hardware.org/?probe=901f720089) | Dec 11, 2021 |
| Dell          | Inspiron 5515               | [7c0553b250](https://linux-hardware.org/?probe=7c0553b250) | Dec 11, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [54058ac7e2](https://linux-hardware.org/?probe=54058ac7e2) | Dec 11, 2021 |
| HP            | Pavilion Power Laptop 15... | [6d5c35bf9f](https://linux-hardware.org/?probe=6d5c35bf9f) | Dec 11, 2021 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [584be17bec](https://linux-hardware.org/?probe=584be17bec) | Dec 11, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [4fba952635](https://linux-hardware.org/?probe=4fba952635) | Dec 11, 2021 |
| HP            | ZBook 15 G2                 | [d7faa88624](https://linux-hardware.org/?probe=d7faa88624) | Dec 11, 2021 |
| Dell          | Latitude 7300               | [2bb3c232b6](https://linux-hardware.org/?probe=2bb3c232b6) | Dec 11, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [3030cb05b9](https://linux-hardware.org/?probe=3030cb05b9) | Dec 11, 2021 |
| Fujitsu       | LIFEBOOK U7411              | [65bc5c1c5b](https://linux-hardware.org/?probe=65bc5c1c5b) | Dec 11, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [f3d37d4574](https://linux-hardware.org/?probe=f3d37d4574) | Dec 10, 2021 |
| Dell          | Inspiron 13 5310            | [7a721d2c05](https://linux-hardware.org/?probe=7a721d2c05) | Dec 10, 2021 |
| Dell          | Vostro 3400                 | [bcb885e52b](https://linux-hardware.org/?probe=bcb885e52b) | Dec 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | [4fe4d7393e](https://linux-hardware.org/?probe=4fe4d7393e) | Dec 10, 2021 |
| Acer          | Swift SFX14-41G             | [a81ed5c974](https://linux-hardware.org/?probe=a81ed5c974) | Dec 10, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [181607bac3](https://linux-hardware.org/?probe=181607bac3) | Dec 10, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [c1de54b513](https://linux-hardware.org/?probe=c1de54b513) | Dec 10, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | [4ba265c070](https://linux-hardware.org/?probe=4ba265c070) | Dec 10, 2021 |
| Lenovo        | G570 20079                  | [439a97ec9b](https://linux-hardware.org/?probe=439a97ec9b) | Dec 09, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [195283a93a](https://linux-hardware.org/?probe=195283a93a) | Dec 09, 2021 |
| Dell          | XPS 13 9305                 | [60e57ae6dd](https://linux-hardware.org/?probe=60e57ae6dd) | Dec 09, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS0... | [73645a62d6](https://linux-hardware.org/?probe=73645a62d6) | Dec 09, 2021 |
| HP            | Laptop 15s-eq2xxx           | [b673a5f067](https://linux-hardware.org/?probe=b673a5f067) | Dec 08, 2021 |
| TUXEDO        | InfinityBook S 15 Gen6      | [3880c485fb](https://linux-hardware.org/?probe=3880c485fb) | Dec 08, 2021 |
| Apple         | MacBookPro12,1              | [fcfdb2cedc](https://linux-hardware.org/?probe=fcfdb2cedc) | Dec 08, 2021 |
| Sony          | SVE1711Z1RB                 | [adb25167ea](https://linux-hardware.org/?probe=adb25167ea) | Dec 07, 2021 |
| HP            | Laptop 15s-fq2xxx           | [9c98446833](https://linux-hardware.org/?probe=9c98446833) | Dec 07, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [ad406a6f63](https://linux-hardware.org/?probe=ad406a6f63) | Dec 07, 2021 |
| Notebook      | NH5xAx                      | [801df46937](https://linux-hardware.org/?probe=801df46937) | Dec 07, 2021 |
| HP            | 15 Notebook PC              | [0523a58e8a](https://linux-hardware.org/?probe=0523a58e8a) | Dec 07, 2021 |
| Lenovo        | ThinkPad X230 23255E4       | [3f2487b1a6](https://linux-hardware.org/?probe=3f2487b1a6) | Dec 07, 2021 |
| Lenovo        | G570 20079                  | [a6722f2ff3](https://linux-hardware.org/?probe=a6722f2ff3) | Dec 07, 2021 |
| Sony          | SVE1713S1RW                 | [41775b7503](https://linux-hardware.org/?probe=41775b7503) | Dec 07, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [8b704c0d3f](https://linux-hardware.org/?probe=8b704c0d3f) | Dec 06, 2021 |
| Lenovo        | ThinkPad T490s 20NX000DR... | [b5a282abf6](https://linux-hardware.org/?probe=b5a282abf6) | Dec 06, 2021 |
| Apple         | MacBookPro9,2               | [4fc7bc5515](https://linux-hardware.org/?probe=4fc7bc5515) | Dec 06, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [42fe75c227](https://linux-hardware.org/?probe=42fe75c227) | Dec 06, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [0dc0958719](https://linux-hardware.org/?probe=0dc0958719) | Dec 06, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [e18de7567f](https://linux-hardware.org/?probe=e18de7567f) | Dec 06, 2021 |
| Lenovo        | ThinkPad T460p 20FXS0550... | [40640fd92f](https://linux-hardware.org/?probe=40640fd92f) | Dec 06, 2021 |
| Framework     | Laptop                      | [64dc54fbc6](https://linux-hardware.org/?probe=64dc54fbc6) | Dec 06, 2021 |
| Acer          | Nitro AN515-45              | [8641f9b078](https://linux-hardware.org/?probe=8641f9b078) | Dec 05, 2021 |
| Lenovo        | ThinkPad W520 42763JF       | [50d1714228](https://linux-hardware.org/?probe=50d1714228) | Dec 05, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [e2d660554f](https://linux-hardware.org/?probe=e2d660554f) | Dec 05, 2021 |
| Dell          | Inspiron 5405               | [91806303e6](https://linux-hardware.org/?probe=91806303e6) | Dec 05, 2021 |
| Dell          | Latitude E6530              | [de5ad42b2f](https://linux-hardware.org/?probe=de5ad42b2f) | Dec 04, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [c91db7e021](https://linux-hardware.org/?probe=c91db7e021) | Dec 04, 2021 |
| Lenovo        | ThinkPad T490s 20NX000DR... | [15e8e28073](https://linux-hardware.org/?probe=15e8e28073) | Dec 04, 2021 |
| Acer          | Aspire E5-571G              | [b006a547c8](https://linux-hardware.org/?probe=b006a547c8) | Dec 04, 2021 |
| HP            | ProBook 470 G5              | [1cfd3aadd8](https://linux-hardware.org/?probe=1cfd3aadd8) | Dec 04, 2021 |
| Lenovo        | ThinkPad E480 20KNS0E200    | [be3c6c3e84](https://linux-hardware.org/?probe=be3c6c3e84) | Dec 04, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [826435e568](https://linux-hardware.org/?probe=826435e568) | Dec 04, 2021 |
| Lenovo        | ThinkPad W520 42763JF       | [23d42021b2](https://linux-hardware.org/?probe=23d42021b2) | Dec 04, 2021 |
| Lenovo        | ThinkPad E480 20KNS0E200    | [6239b4eda5](https://linux-hardware.org/?probe=6239b4eda5) | Dec 04, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [f90f047538](https://linux-hardware.org/?probe=f90f047538) | Dec 03, 2021 |
| Toshiba       | Satellite C70-A-K2W         | [8e46f67032](https://linux-hardware.org/?probe=8e46f67032) | Dec 03, 2021 |
| Lenovo        | ThinkPad X230 23257R2       | [775ec45ab8](https://linux-hardware.org/?probe=775ec45ab8) | Dec 03, 2021 |
| Lenovo        | ThinkPad X230 23257R2       | [b783f0a79d](https://linux-hardware.org/?probe=b783f0a79d) | Dec 03, 2021 |
| Gigabyte      | AERO 15 KB                  | [a7d3041cd2](https://linux-hardware.org/?probe=a7d3041cd2) | Dec 03, 2021 |
| HP            | Laptop 15s-eq2xxx           | [f53047cd0d](https://linux-hardware.org/?probe=f53047cd0d) | Dec 02, 2021 |
| Notebook      | NH55RGQ                     | [4189e1f255](https://linux-hardware.org/?probe=4189e1f255) | Dec 02, 2021 |
| Lenovo        | V15-ADA 82C7                | [5ade9a0569](https://linux-hardware.org/?probe=5ade9a0569) | Dec 02, 2021 |
| Lenovo        | ThinkPad L390 20NSS43600    | [e9aae12812](https://linux-hardware.org/?probe=e9aae12812) | Dec 02, 2021 |
| Acer          | Nitro AN515-55              | [d5c6c6edee](https://linux-hardware.org/?probe=d5c6c6edee) | Dec 01, 2021 |
| HP            | Laptop 15s-fq2xxx           | [94b9d8b093](https://linux-hardware.org/?probe=94b9d8b093) | Dec 01, 2021 |
| HP            | ProBook 470 G5              | [240ca54dfb](https://linux-hardware.org/?probe=240ca54dfb) | Dec 01, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [8cebf41624](https://linux-hardware.org/?probe=8cebf41624) | Dec 01, 2021 |
| HP            | Laptop 15s-eq1xxx           | [9b11575394](https://linux-hardware.org/?probe=9b11575394) | Dec 01, 2021 |
| HP            | ProBook 470 G5              | [610709bb66](https://linux-hardware.org/?probe=610709bb66) | Nov 30, 2021 |
| Acer          | Aspire E5-571G              | [f940ae414d](https://linux-hardware.org/?probe=f940ae414d) | Nov 30, 2021 |
| Dell          | Inspiron 7460               | [0a6feb58e7](https://linux-hardware.org/?probe=0a6feb58e7) | Nov 30, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [b2d55bd445](https://linux-hardware.org/?probe=b2d55bd445) | Nov 30, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | [23ae32af07](https://linux-hardware.org/?probe=23ae32af07) | Nov 30, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | [074ec973ae](https://linux-hardware.org/?probe=074ec973ae) | Nov 30, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS5... | [80bbba47f6](https://linux-hardware.org/?probe=80bbba47f6) | Nov 29, 2021 |
| Acer          | Aspire E5-571G              | [95cb3fe8b3](https://linux-hardware.org/?probe=95cb3fe8b3) | Nov 29, 2021 |
| Acer          | Predator G9-793             | [b9dc27ddac](https://linux-hardware.org/?probe=b9dc27ddac) | Nov 29, 2021 |
| Dell          | G5 5590                     | [e569e56450](https://linux-hardware.org/?probe=e569e56450) | Nov 29, 2021 |
| HP            | Laptop 15s-fq2xxx           | [959af2b8dd](https://linux-hardware.org/?probe=959af2b8dd) | Nov 29, 2021 |
| Acer          | Swift SF113-31              | [f1e3d8c722](https://linux-hardware.org/?probe=f1e3d8c722) | Nov 29, 2021 |
| Notebook      | NB50TL                      | [15a716161c](https://linux-hardware.org/?probe=15a716161c) | Nov 28, 2021 |
| HP            | ProBook 470 G5              | [b75e21b247](https://linux-hardware.org/?probe=b75e21b247) | Nov 28, 2021 |
| Dell          | Inspiron 5558               | [b003366a2c](https://linux-hardware.org/?probe=b003366a2c) | Nov 28, 2021 |
| Notebook      | NH5x_NH7x_HHx_HJx_HKx       | [8e5c4cc27b](https://linux-hardware.org/?probe=8e5c4cc27b) | Nov 28, 2021 |
| Apple         | MacBookPro7,1               | [6a4ed949e9](https://linux-hardware.org/?probe=6a4ed949e9) | Nov 28, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [0852350348](https://linux-hardware.org/?probe=0852350348) | Nov 28, 2021 |
| Dell          | Latitude 7420               | [7a96812e39](https://linux-hardware.org/?probe=7a96812e39) | Nov 28, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [eabdd46893](https://linux-hardware.org/?probe=eabdd46893) | Nov 28, 2021 |
| Lenovo        | G40-45 80E1                 | [b3cdb202fc](https://linux-hardware.org/?probe=b3cdb202fc) | Nov 28, 2021 |
| HP            | Laptop 15s-fq2xxx           | [d559f82ee3](https://linux-hardware.org/?probe=d559f82ee3) | Nov 28, 2021 |
| Dell          | XPS 13 7390                 | [783b49e383](https://linux-hardware.org/?probe=783b49e383) | Nov 28, 2021 |
| Lenovo        | ThinkPad T400 6474B84       | [67f32be00d](https://linux-hardware.org/?probe=67f32be00d) | Nov 27, 2021 |
| Lenovo        | ThinkPad E480 20KNS0E200    | [968f938b4e](https://linux-hardware.org/?probe=968f938b4e) | Nov 27, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [08612b7f88](https://linux-hardware.org/?probe=08612b7f88) | Nov 27, 2021 |
| Lenovo        | ThinkPad E15 20RD003JRT     | [ef8336f76a](https://linux-hardware.org/?probe=ef8336f76a) | Nov 26, 2021 |
| Dell          | Precision 5550              | [41caa6a4a0](https://linux-hardware.org/?probe=41caa6a4a0) | Nov 26, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [6056117cca](https://linux-hardware.org/?probe=6056117cca) | Nov 26, 2021 |
| ASUSTek       | K54C                        | [2604de426e](https://linux-hardware.org/?probe=2604de426e) | Nov 26, 2021 |
| Acer          | AP714-51T                   | [3fe9bcf889](https://linux-hardware.org/?probe=3fe9bcf889) | Nov 26, 2021 |
| Acer          | AP714-51T                   | [406001fc85](https://linux-hardware.org/?probe=406001fc85) | Nov 26, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [c207f61d91](https://linux-hardware.org/?probe=c207f61d91) | Nov 26, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [96c90ad6c9](https://linux-hardware.org/?probe=96c90ad6c9) | Nov 26, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [039dbf659a](https://linux-hardware.org/?probe=039dbf659a) | Nov 26, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | [a000027ce6](https://linux-hardware.org/?probe=a000027ce6) | Nov 26, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [b9c1906f2b](https://linux-hardware.org/?probe=b9c1906f2b) | Nov 26, 2021 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [366fe373c9](https://linux-hardware.org/?probe=366fe373c9) | Nov 25, 2021 |
| HUAWEI        | KLVL-WXXW                   | [beff046f56](https://linux-hardware.org/?probe=beff046f56) | Nov 25, 2021 |
| HUAWEI        | KLVL-WXXW                   | [2a96a2a7af](https://linux-hardware.org/?probe=2a96a2a7af) | Nov 25, 2021 |
| Sony          | VPCF131FM                   | [f0ba5e0db2](https://linux-hardware.org/?probe=f0ba5e0db2) | Nov 25, 2021 |
| HUAWEI        | KLVL-WXX9                   | [3352efa5cd](https://linux-hardware.org/?probe=3352efa5cd) | Nov 25, 2021 |
| Dell          | Latitude E5470              | [1e35555998](https://linux-hardware.org/?probe=1e35555998) | Nov 24, 2021 |
| Dell          | XPS 13 9300                 | [a91462bd5a](https://linux-hardware.org/?probe=a91462bd5a) | Nov 24, 2021 |
| HP            | EliteBook 735 G5            | [d80b574cb4](https://linux-hardware.org/?probe=d80b574cb4) | Nov 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [b6bfa4b827](https://linux-hardware.org/?probe=b6bfa4b827) | Nov 24, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [44bf6f6d6f](https://linux-hardware.org/?probe=44bf6f6d6f) | Nov 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [3c3fbf498a](https://linux-hardware.org/?probe=3c3fbf498a) | Nov 23, 2021 |
| HP            | ENVY Laptop 14-eb0xxx       | [5be975dd37](https://linux-hardware.org/?probe=5be975dd37) | Nov 23, 2021 |
| Lenovo        | B40-70 80F30006BR           | [d29d6c2f61](https://linux-hardware.org/?probe=d29d6c2f61) | Nov 23, 2021 |
| Lenovo        | B40-70 80F30006BR           | [6e361a8715](https://linux-hardware.org/?probe=6e361a8715) | Nov 23, 2021 |
| Acer          | Nitro AN515-54              | [b58b567113](https://linux-hardware.org/?probe=b58b567113) | Nov 22, 2021 |
| Apple         | MacBookPro11,4              | [7b9225653f](https://linux-hardware.org/?probe=7b9225653f) | Nov 22, 2021 |
| HP            | ENVY Laptop 14-eb0xxx       | [365b3888e6](https://linux-hardware.org/?probe=365b3888e6) | Nov 22, 2021 |
| Fujitsu       | LIFEBOOK U747               | [ece0600e5d](https://linux-hardware.org/?probe=ece0600e5d) | Nov 22, 2021 |
| Apple         | MacBookPro7,1               | [c686d7d85c](https://linux-hardware.org/?probe=c686d7d85c) | Nov 22, 2021 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | [f13b0fb2b9](https://linux-hardware.org/?probe=f13b0fb2b9) | Nov 22, 2021 |
| HP            | Laptop 15s-eq2xxx           | [a20fe0f647](https://linux-hardware.org/?probe=a20fe0f647) | Nov 21, 2021 |
| Lenovo        | ThinkPad T400 6474B84       | [f779165258](https://linux-hardware.org/?probe=f779165258) | Nov 21, 2021 |
| Dell          | Latitude E5570              | [8cf8db7a89](https://linux-hardware.org/?probe=8cf8db7a89) | Nov 21, 2021 |
| Google        | Relm                        | [92e569bf1e](https://linux-hardware.org/?probe=92e569bf1e) | Nov 21, 2021 |
| HP            | Pavilion 17                 | [2d69072cdf](https://linux-hardware.org/?probe=2d69072cdf) | Nov 20, 2021 |
| Dell          | Latitude 5490               | [cbe23836bf](https://linux-hardware.org/?probe=cbe23836bf) | Nov 20, 2021 |
| Dell          | Latitude E7440              | [a4581f0839](https://linux-hardware.org/?probe=a4581f0839) | Nov 20, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [8dfec492a4](https://linux-hardware.org/?probe=8dfec492a4) | Nov 19, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [78341a1a16](https://linux-hardware.org/?probe=78341a1a16) | Nov 19, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | [31cebd4e96](https://linux-hardware.org/?probe=31cebd4e96) | Nov 19, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | [0be43eb710](https://linux-hardware.org/?probe=0be43eb710) | Nov 19, 2021 |
| Acer          | Swift SF514-51              | [07e73dc8ab](https://linux-hardware.org/?probe=07e73dc8ab) | Nov 19, 2021 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [a524ba65b5](https://linux-hardware.org/?probe=a524ba65b5) | Nov 19, 2021 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [7e7b7d381e](https://linux-hardware.org/?probe=7e7b7d381e) | Nov 19, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [d0aea280e7](https://linux-hardware.org/?probe=d0aea280e7) | Nov 19, 2021 |
| Dell          | Inspiron 3593               | [0e670dc090](https://linux-hardware.org/?probe=0e670dc090) | Nov 19, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [d7a5775f61](https://linux-hardware.org/?probe=d7a5775f61) | Nov 19, 2021 |
| Notebook      | NH55RGQ                     | [d111fd1549](https://linux-hardware.org/?probe=d111fd1549) | Nov 19, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [01a15306b9](https://linux-hardware.org/?probe=01a15306b9) | Nov 19, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [709cd419bc](https://linux-hardware.org/?probe=709cd419bc) | Nov 19, 2021 |
| ASUSTek       | X750JN                      | [bb6f44b058](https://linux-hardware.org/?probe=bb6f44b058) | Nov 19, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [f5a721bf24](https://linux-hardware.org/?probe=f5a721bf24) | Nov 19, 2021 |
| Dell          | Precision 5510              | [1d46cced08](https://linux-hardware.org/?probe=1d46cced08) | Nov 19, 2021 |
| HP            | Laptop 14s-fq0xxx           | [f9b7bdfef8](https://linux-hardware.org/?probe=f9b7bdfef8) | Nov 19, 2021 |
| Dell          | Inspiron 7572               | [0953d49db6](https://linux-hardware.org/?probe=0953d49db6) | Nov 18, 2021 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [dc150f9fba](https://linux-hardware.org/?probe=dc150f9fba) | Nov 18, 2021 |
| HP            | EliteBook 840 G3            | [9e8fd0520d](https://linux-hardware.org/?probe=9e8fd0520d) | Nov 18, 2021 |
| Lenovo        | Legion R9000P2021H 82JQ     | [7734a8d28c](https://linux-hardware.org/?probe=7734a8d28c) | Nov 18, 2021 |
| Acer          | Swift SF314-43              | [46c44d537a](https://linux-hardware.org/?probe=46c44d537a) | Nov 18, 2021 |
| HP            | Pavilion Notebook           | [01f7a4c33d](https://linux-hardware.org/?probe=01f7a4c33d) | Nov 18, 2021 |
| Acer          | Swift SF314-42              | [05020e1e61](https://linux-hardware.org/?probe=05020e1e61) | Nov 18, 2021 |
| Toshiba       | Satellite C855-12R          | [dbde83db50](https://linux-hardware.org/?probe=dbde83db50) | Nov 17, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [427ee1a6de](https://linux-hardware.org/?probe=427ee1a6de) | Nov 17, 2021 |
| Login Info... | LOG-QAL30                   | [585419cd38](https://linux-hardware.org/?probe=585419cd38) | Nov 17, 2021 |
| Login Info... | LOG-QAL30                   | [9dff5423c9](https://linux-hardware.org/?probe=9dff5423c9) | Nov 17, 2021 |
| Dell          | Latitude E7270              | [70a4c30534](https://linux-hardware.org/?probe=70a4c30534) | Nov 17, 2021 |
| HP            | ZBook Fury 15 G7 Mobile ... | [6196137046](https://linux-hardware.org/?probe=6196137046) | Nov 17, 2021 |
| HP            | Pavilion 15                 | [d6caf6dd12](https://linux-hardware.org/?probe=d6caf6dd12) | Nov 17, 2021 |
| Toshiba       | Satellite C855-12R          | [eefe2dc8be](https://linux-hardware.org/?probe=eefe2dc8be) | Nov 17, 2021 |
| HP            | Pavilion 15                 | [581a56e963](https://linux-hardware.org/?probe=581a56e963) | Nov 17, 2021 |
| HP            | ENVY Laptop 15t-ep000       | [02c2ed5954](https://linux-hardware.org/?probe=02c2ed5954) | Nov 16, 2021 |
| HP            | Laptop 15s-eq2xxx           | [ec73e73572](https://linux-hardware.org/?probe=ec73e73572) | Nov 16, 2021 |
| Razer         | Blade 15 Advanced Model ... | [c4763ca2a5](https://linux-hardware.org/?probe=c4763ca2a5) | Nov 16, 2021 |
| Acer          | Swift SF314-43              | [db85b885ae](https://linux-hardware.org/?probe=db85b885ae) | Nov 16, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [6b1f5ce8b7](https://linux-hardware.org/?probe=6b1f5ce8b7) | Nov 16, 2021 |
| ASUSTek       | S551LN                      | [53b3fced16](https://linux-hardware.org/?probe=53b3fced16) | Nov 16, 2021 |
| Toshiba       | Satellite C855-12R          | [ccf125eb47](https://linux-hardware.org/?probe=ccf125eb47) | Nov 16, 2021 |
| MSI           | Modern 15 A11M              | [6398858488](https://linux-hardware.org/?probe=6398858488) | Nov 16, 2021 |
| Notebook      | NH55RGQ                     | [b3cb30c28d](https://linux-hardware.org/?probe=b3cb30c28d) | Nov 16, 2021 |
| Razer         | Blade 15 Advanced Model ... | [1119a0805e](https://linux-hardware.org/?probe=1119a0805e) | Nov 16, 2021 |
| Acer          | Aspire E1-572               | [dbaa27643e](https://linux-hardware.org/?probe=dbaa27643e) | Nov 16, 2021 |
| Acer          | Aspire E1-572               | [aad4a92e0e](https://linux-hardware.org/?probe=aad4a92e0e) | Nov 16, 2021 |
| Apple         | MacBookPro6,2               | [75e80e1ea8](https://linux-hardware.org/?probe=75e80e1ea8) | Nov 15, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [06f896ff98](https://linux-hardware.org/?probe=06f896ff98) | Nov 15, 2021 |
| Acer          | Aspire A715-71G             | [dd0bfcd823](https://linux-hardware.org/?probe=dd0bfcd823) | Nov 15, 2021 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | [ea6139e86c](https://linux-hardware.org/?probe=ea6139e86c) | Nov 15, 2021 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | [90e882710c](https://linux-hardware.org/?probe=90e882710c) | Nov 15, 2021 |
| Lenovo        | IdeaPad S540-15IWL          | [516e448510](https://linux-hardware.org/?probe=516e448510) | Nov 14, 2021 |
| MSI           | Modern 15 A11M              | [8b02ecc2b6](https://linux-hardware.org/?probe=8b02ecc2b6) | Nov 14, 2021 |
| SiComputer    | Nauta 01W PRO               | [70b84217bd](https://linux-hardware.org/?probe=70b84217bd) | Nov 14, 2021 |
| Dell          | Precision 3541              | [a21fd45ac3](https://linux-hardware.org/?probe=a21fd45ac3) | Nov 14, 2021 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | [54bb479f64](https://linux-hardware.org/?probe=54bb479f64) | Nov 14, 2021 |
| SiComputer    | Nauta 01W PRO               | [d88aea84ef](https://linux-hardware.org/?probe=d88aea84ef) | Nov 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [48f29ffe3a](https://linux-hardware.org/?probe=48f29ffe3a) | Nov 14, 2021 |
| Apple         | MacBookPro6,2               | [a778aba19c](https://linux-hardware.org/?probe=a778aba19c) | Nov 14, 2021 |
| Dell          | Vostro 3460                 | [3a6a636384](https://linux-hardware.org/?probe=3a6a636384) | Nov 14, 2021 |
| Dell          | Latitude 5511               | [dc7c10f4e2](https://linux-hardware.org/?probe=dc7c10f4e2) | Nov 13, 2021 |
| Dell          | Latitude 5511               | [b0ca679bc5](https://linux-hardware.org/?probe=b0ca679bc5) | Nov 13, 2021 |
| HP            | ProBook 430 G1              | [68633b9bf5](https://linux-hardware.org/?probe=68633b9bf5) | Nov 13, 2021 |
| MSI           | Delta 15 A5EFK              | [bc348014b5](https://linux-hardware.org/?probe=bc348014b5) | Nov 13, 2021 |
| Lenovo        | IdeaPad MIIX 700-12ISK 8... | [3cfeff5a7f](https://linux-hardware.org/?probe=3cfeff5a7f) | Nov 13, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [9e8eab1073](https://linux-hardware.org/?probe=9e8eab1073) | Nov 13, 2021 |
| Lenovo        | Legion R7000P2021H 82JU     | [19ffbfb846](https://linux-hardware.org/?probe=19ffbfb846) | Nov 13, 2021 |
| Dell          | Inspiron 14-3467            | [ebe54808c2](https://linux-hardware.org/?probe=ebe54808c2) | Nov 13, 2021 |
| Apple         | MacBookPro10,2              | [5cbec68d6e](https://linux-hardware.org/?probe=5cbec68d6e) | Nov 13, 2021 |
| Positivo      | V142N_4G                    | [6afdf02b96](https://linux-hardware.org/?probe=6afdf02b96) | Nov 13, 2021 |
| Acer          | Swift SFX14-41G             | [04e988d138](https://linux-hardware.org/?probe=04e988d138) | Nov 13, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [85929a9a18](https://linux-hardware.org/?probe=85929a9a18) | Nov 12, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [3a33eaa4c0](https://linux-hardware.org/?probe=3a33eaa4c0) | Nov 12, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | [3bbda8b194](https://linux-hardware.org/?probe=3bbda8b194) | Nov 12, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [fa348e4f87](https://linux-hardware.org/?probe=fa348e4f87) | Nov 12, 2021 |
| Dell          | Precision 5510              | [80bbc48bce](https://linux-hardware.org/?probe=80bbc48bce) | Nov 12, 2021 |
| Lenovo        | IdeaPad 5 Pro 16IHU6 82L... | [a7998fa53a](https://linux-hardware.org/?probe=a7998fa53a) | Nov 11, 2021 |
| System76      | Oryx Pro                    | [77cf902290](https://linux-hardware.org/?probe=77cf902290) | Nov 11, 2021 |
| Apple         | MacBookPro9,2               | [61afe68685](https://linux-hardware.org/?probe=61afe68685) | Nov 11, 2021 |
| Dell          | Latitude E7440              | [e907f0bbf1](https://linux-hardware.org/?probe=e907f0bbf1) | Nov 11, 2021 |
| ASUSTek       | X202EV                      | [ff0732f245](https://linux-hardware.org/?probe=ff0732f245) | Nov 11, 2021 |
| HP            | EliteBook 850 G5            | [7df8bf1476](https://linux-hardware.org/?probe=7df8bf1476) | Nov 11, 2021 |
| HP            | EliteBook 850 G5            | [1def8c2d0b](https://linux-hardware.org/?probe=1def8c2d0b) | Nov 11, 2021 |
| Dell          | XPS 13 7390                 | [f5ceaaf6fe](https://linux-hardware.org/?probe=f5ceaaf6fe) | Nov 11, 2021 |
| Apple         | MacBookAir6,1               | [588c351d40](https://linux-hardware.org/?probe=588c351d40) | Nov 10, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [ac9d7f968f](https://linux-hardware.org/?probe=ac9d7f968f) | Nov 10, 2021 |
| ASUSTek       | VivoBook S15 X510UF         | [fc4d285e0a](https://linux-hardware.org/?probe=fc4d285e0a) | Nov 10, 2021 |
| Acer          | Nitro AN515-55              | [d4f75f503d](https://linux-hardware.org/?probe=d4f75f503d) | Nov 10, 2021 |
| ASUSTek       | T102HA                      | [d648620b1a](https://linux-hardware.org/?probe=d648620b1a) | Nov 10, 2021 |
| LG Electro... | 14Z90P-G.AR53A              | [a1fb8771db](https://linux-hardware.org/?probe=a1fb8771db) | Nov 10, 2021 |
| HP            | ProBook 430 G1              | [99ece77400](https://linux-hardware.org/?probe=99ece77400) | Nov 10, 2021 |
| HUAWEI        | KPL-W0X                     | [807e59f1e3](https://linux-hardware.org/?probe=807e59f1e3) | Nov 10, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [5a2fa34576](https://linux-hardware.org/?probe=5a2fa34576) | Nov 10, 2021 |
| HP            | Laptop 15s-fq2xxx           | [c8fb558bb7](https://linux-hardware.org/?probe=c8fb558bb7) | Nov 09, 2021 |
| Lenovo        | ThinkPad X260 20F5S0E000    | [2321968d02](https://linux-hardware.org/?probe=2321968d02) | Nov 09, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [81605538eb](https://linux-hardware.org/?probe=81605538eb) | Nov 09, 2021 |
| MSI           | GL62M 7RDX                  | [3538358a06](https://linux-hardware.org/?probe=3538358a06) | Nov 09, 2021 |
| HUAWEI        | HLYL-WXX9                   | [1c63b3b4ce](https://linux-hardware.org/?probe=1c63b3b4ce) | Nov 09, 2021 |
| HP            | OMEN Laptop 15-ek0xxx       | [cb4e2271c0](https://linux-hardware.org/?probe=cb4e2271c0) | Nov 09, 2021 |
| Toshiba       | NB255                       | [3c30b0d7ad](https://linux-hardware.org/?probe=3c30b0d7ad) | Nov 09, 2021 |
| HP            | Notebook                    | [e254c5c947](https://linux-hardware.org/?probe=e254c5c947) | Nov 08, 2021 |
| HP            | ENVY Laptop 17-ce1xxx       | [5f5424fe84](https://linux-hardware.org/?probe=5f5424fe84) | Nov 08, 2021 |
| Lenovo        | ThinkPad E590 20NB005GMH    | [146b572cd0](https://linux-hardware.org/?probe=146b572cd0) | Nov 08, 2021 |
| Lenovo        | IdeaPad Z510 20287          | [0812e26e5a](https://linux-hardware.org/?probe=0812e26e5a) | Nov 08, 2021 |
| Dell          | XPS 13 9360                 | [8988b7e735](https://linux-hardware.org/?probe=8988b7e735) | Nov 08, 2021 |
| Lenovo        | ThinkPad T460s 20F9CTO1W... | [b996ce8823](https://linux-hardware.org/?probe=b996ce8823) | Nov 07, 2021 |
| Lenovo        | Ducati 5 82ES               | [6269149643](https://linux-hardware.org/?probe=6269149643) | Nov 07, 2021 |
| HP            | Pavilion Laptop 15-ck0xx    | [b4d29007be](https://linux-hardware.org/?probe=b4d29007be) | Nov 07, 2021 |
| Dell          | Latitude E7440              | [b2560457a5](https://linux-hardware.org/?probe=b2560457a5) | Nov 06, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [af116b7c35](https://linux-hardware.org/?probe=af116b7c35) | Nov 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [ced169a0b1](https://linux-hardware.org/?probe=ced169a0b1) | Nov 06, 2021 |
| Apple         | MacBookPro6,2               | [bde89fd503](https://linux-hardware.org/?probe=bde89fd503) | Nov 06, 2021 |
| HP            | ProBook 455 G1              | [44a11d66ac](https://linux-hardware.org/?probe=44a11d66ac) | Nov 06, 2021 |
| HP            | 250 G1                      | [1c52b861c7](https://linux-hardware.org/?probe=1c52b861c7) | Nov 06, 2021 |
| Lenovo        | ThinkPad E14 20RA001XIX     | [98d8c0fbdb](https://linux-hardware.org/?probe=98d8c0fbdb) | Nov 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [bb1201e75c](https://linux-hardware.org/?probe=bb1201e75c) | Nov 06, 2021 |
| HP            | EliteBook 2570p             | [dc62969834](https://linux-hardware.org/?probe=dc62969834) | Nov 05, 2021 |
| Notebook      | W65_W67RZ                   | [153b2a920d](https://linux-hardware.org/?probe=153b2a920d) | Nov 05, 2021 |
| HONOR         | NBD-WXX9                    | [1030fbbff6](https://linux-hardware.org/?probe=1030fbbff6) | Nov 05, 2021 |
| Unknown       | Unknown                     | [c78a5c81b2](https://linux-hardware.org/?probe=c78a5c81b2) | Nov 05, 2021 |
| HP            | ZBook 14u G5                | [ec192642ba](https://linux-hardware.org/?probe=ec192642ba) | Nov 05, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [8e06f2617d](https://linux-hardware.org/?probe=8e06f2617d) | Nov 05, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [1a2dda8941](https://linux-hardware.org/?probe=1a2dda8941) | Nov 05, 2021 |
| HP            | Laptop 15s-eq2xxx           | [04d4fca603](https://linux-hardware.org/?probe=04d4fca603) | Nov 04, 2021 |
| HP            | ProBook 430 G5              | [f29c3d7003](https://linux-hardware.org/?probe=f29c3d7003) | Nov 04, 2021 |
| HP            | ProBook 430 G5              | [a795236afd](https://linux-hardware.org/?probe=a795236afd) | Nov 04, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [cd291857e2](https://linux-hardware.org/?probe=cd291857e2) | Nov 04, 2021 |
| Lenovo        | ThinkPad T460 20FNCTO1WW    | [6ee78bd50a](https://linux-hardware.org/?probe=6ee78bd50a) | Nov 04, 2021 |
| Lenovo        | ThinkPad X270 20HN0013UK    | [8454cff91f](https://linux-hardware.org/?probe=8454cff91f) | Nov 04, 2021 |
| Dell          | Studio 1537                 | [d040c159b8](https://linux-hardware.org/?probe=d040c159b8) | Nov 04, 2021 |
| HP            | ProBook 430 G3              | [1d421060d7](https://linux-hardware.org/?probe=1d421060d7) | Nov 03, 2021 |
| Dell          | Precision 5510              | [eb702ce1e6](https://linux-hardware.org/?probe=eb702ce1e6) | Nov 03, 2021 |
| Dell          | Inspiron 5502               | [c68c3a5c3b](https://linux-hardware.org/?probe=c68c3a5c3b) | Nov 03, 2021 |
| Lenovo        | ThinkPad E15 20RD0011GE     | [10bd49d9c0](https://linux-hardware.org/?probe=10bd49d9c0) | Nov 03, 2021 |
| Dell          | Latitude 5590               | [5bc1ed5978](https://linux-hardware.org/?probe=5bc1ed5978) | Nov 03, 2021 |
| Lenovo        | ThinkPad T420 4236DK9       | [84e39e6c94](https://linux-hardware.org/?probe=84e39e6c94) | Nov 03, 2021 |
| System76      | Pangolin                    | [1eb0a48a30](https://linux-hardware.org/?probe=1eb0a48a30) | Nov 03, 2021 |
| HP            | Laptop 14-dq2xxx            | [f30e20e67b](https://linux-hardware.org/?probe=f30e20e67b) | Nov 03, 2021 |
| Dell          | XPS 15 9570                 | [8e3c5b2ef0](https://linux-hardware.org/?probe=8e3c5b2ef0) | Nov 03, 2021 |
| Lenovo        | ThinkPad X395 20NL0005US    | [b65f4d5ba3](https://linux-hardware.org/?probe=b65f4d5ba3) | Nov 03, 2021 |
| Lenovo        | ThinkPad E14 20RA0020AU     | [8c19662b7e](https://linux-hardware.org/?probe=8c19662b7e) | Nov 03, 2021 |
| Toshiba       | TECRA Z50-A                 | [4aae9bdc03](https://linux-hardware.org/?probe=4aae9bdc03) | Nov 03, 2021 |
| Dell          | XPS 13 9370                 | [458d3682a5](https://linux-hardware.org/?probe=458d3682a5) | Nov 03, 2021 |
| Lenovo        | ThinkPad T480s 20L70026U... | [7205a2ab55](https://linux-hardware.org/?probe=7205a2ab55) | Nov 03, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [54b32173dd](https://linux-hardware.org/?probe=54b32173dd) | Nov 03, 2021 |
| Dell          | XPS 13 7390                 | [40df244ae9](https://linux-hardware.org/?probe=40df244ae9) | Nov 02, 2021 |
| Lenovo        | ThinkPad T480s 20L70026U... | [eeb181f50b](https://linux-hardware.org/?probe=eeb181f50b) | Oct 30, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [1310b8abf4](https://linux-hardware.org/?probe=1310b8abf4) | Oct 30, 2021 |
| Framework     | Laptop                      | [04db6c2222](https://linux-hardware.org/?probe=04db6c2222) | Oct 29, 2021 |
| Acer          | Aspire F5-573G              | [1be6c8dc87](https://linux-hardware.org/?probe=1be6c8dc87) | Oct 29, 2021 |
| Lenovo        | ThinkPad T490 20N3S6VU00    | [f8024b89d4](https://linux-hardware.org/?probe=f8024b89d4) | Oct 28, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [e9a8fb1275](https://linux-hardware.org/?probe=e9a8fb1275) | Oct 27, 2021 |
| BESSTAR Te... | X400                        | [9cfc0bb300](https://linux-hardware.org/?probe=9cfc0bb300) | Oct 27, 2021 |
| Positivo B... | VJFE53F11X-XXXXXX           | [d3720f9145](https://linux-hardware.org/?probe=d3720f9145) | Oct 25, 2021 |
| Alienware     | Area-51m R2                 | [c3f94d8599](https://linux-hardware.org/?probe=c3f94d8599) | Oct 24, 2021 |
| HP            | ProBook 470 G5              | [725627d16b](https://linux-hardware.org/?probe=725627d16b) | Oct 23, 2021 |
| HP            | EliteBook 8560w             | [98bd384a42](https://linux-hardware.org/?probe=98bd384a42) | Oct 23, 2021 |
| Lenovo        | ThinkPad T480 20L5000BMX    | [91fc910cf6](https://linux-hardware.org/?probe=91fc910cf6) | Oct 23, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [1c91bc1deb](https://linux-hardware.org/?probe=1c91bc1deb) | Oct 23, 2021 |
| Lenovo        | ThinkPad T480 20L5000BMX    | [21b13fb067](https://linux-hardware.org/?probe=21b13fb067) | Oct 21, 2021 |
| Lenovo        | ThinkPad T490 20N3S6VU00    | [9932dd3c21](https://linux-hardware.org/?probe=9932dd3c21) | Oct 21, 2021 |
| Lenovo        | ThinkPad T490 20N3S6VU00    | [a99866abc1](https://linux-hardware.org/?probe=a99866abc1) | Oct 21, 2021 |
| Acer          | Swift SF114-32              | [faa49a332b](https://linux-hardware.org/?probe=faa49a332b) | Oct 20, 2021 |
| HP            | EliteBook 820 G1            | [278ec34902](https://linux-hardware.org/?probe=278ec34902) | Oct 19, 2021 |
| Lenovo        | ThinkPad T460 20FMS1R01K    | [4dbc231901](https://linux-hardware.org/?probe=4dbc231901) | Oct 18, 2021 |
| GPU Compan... | GWTN156-1                   | [3cb0b09b48](https://linux-hardware.org/?probe=3cb0b09b48) | Oct 17, 2021 |
| HP            | Laptop 14-df0xxx            | [ac488ba246](https://linux-hardware.org/?probe=ac488ba246) | Oct 16, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [362e1d3b99](https://linux-hardware.org/?probe=362e1d3b99) | Oct 15, 2021 |
| Dell          | Precision 5550              | [15a0f61f84](https://linux-hardware.org/?probe=15a0f61f84) | Oct 14, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [4bb5ac9410](https://linux-hardware.org/?probe=4bb5ac9410) | Oct 12, 2021 |
| HP            | OMEN Laptop 15-ek0xxx       | [d4acf59f3b](https://linux-hardware.org/?probe=d4acf59f3b) | Oct 11, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [5b4efb9e18](https://linux-hardware.org/?probe=5b4efb9e18) | Oct 10, 2021 |
| Lenovo        | Yoga S740-14IIL 81RS        | [fd09df16d9](https://linux-hardware.org/?probe=fd09df16d9) | Oct 10, 2021 |
| HP            | ProBook 450 G3              | [2eeb05ff03](https://linux-hardware.org/?probe=2eeb05ff03) | Oct 09, 2021 |
| HP            | ENVY Laptop 15t-ep000       | [f9b69ffa3d](https://linux-hardware.org/?probe=f9b69ffa3d) | Oct 08, 2021 |
| Dell          | Inspiron 5505               | [d136f5d8f7](https://linux-hardware.org/?probe=d136f5d8f7) | Oct 08, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [26c62915e0](https://linux-hardware.org/?probe=26c62915e0) | Oct 07, 2021 |
| ASUSTek       | VivoBook S15 X530UA         | [146866c629](https://linux-hardware.org/?probe=146866c629) | Oct 06, 2021 |
| Apple         | MacBookPro5,5               | [db435ab99c](https://linux-hardware.org/?probe=db435ab99c) | Oct 03, 2021 |
| Lenovo        | G580 20150                  | [08adba2c54](https://linux-hardware.org/?probe=08adba2c54) | Oct 02, 2021 |
| HUAWEI        | EUL-WX9                     | [dfc5c12fbf](https://linux-hardware.org/?probe=dfc5c12fbf) | Oct 01, 2021 |
| Lenovo        | G580 20150                  | [1dbb7762f6](https://linux-hardware.org/?probe=1dbb7762f6) | Oct 01, 2021 |
| HP            | EliteBook 840 G5            | [e64aeb5fa4](https://linux-hardware.org/?probe=e64aeb5fa4) | Oct 01, 2021 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [17c2d08e41](https://linux-hardware.org/?probe=17c2d08e41) | Oct 01, 2021 |
| HP            | EliteBook 840 G5            | [28bfae31ee](https://linux-hardware.org/?probe=28bfae31ee) | Oct 01, 2021 |
| Dell          | Studio 1537                 | [aae900457c](https://linux-hardware.org/?probe=aae900457c) | Oct 01, 2021 |
| Framework     | Laptop                      | [95576917c8](https://linux-hardware.org/?probe=95576917c8) | Sep 29, 2021 |
| Notebook      | N2x0WU                      | [410a2dab96](https://linux-hardware.org/?probe=410a2dab96) | Sep 28, 2021 |
| Lenovo        | IdeaPad C340-14API 81N6     | [82e0f76133](https://linux-hardware.org/?probe=82e0f76133) | Sep 25, 2021 |
| Lenovo        | ThinkPad E480 20KNS0MC00    | [ba847bc0c4](https://linux-hardware.org/?probe=ba847bc0c4) | Sep 23, 2021 |
| Apple         | MacBook6,1                  | [4fbbe3d05b](https://linux-hardware.org/?probe=4fbbe3d05b) | Sep 19, 2021 |
| HP            | G42                         | [0e9914c9cc](https://linux-hardware.org/?probe=0e9914c9cc) | Sep 18, 2021 |
| HP            | ZBook 15u G5                | [a5331a4d5e](https://linux-hardware.org/?probe=a5331a4d5e) | Sep 15, 2021 |
| Dell          | XPS 17 9700                 | [ebac1c499f](https://linux-hardware.org/?probe=ebac1c499f) | Sep 15, 2021 |
| ASUSTek       | G71V                        | [7904b934a4](https://linux-hardware.org/?probe=7904b934a4) | Sep 09, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [2b21ef140a](https://linux-hardware.org/?probe=2b21ef140a) | Sep 05, 2021 |
| Lenovo        | ThinkPad P51s 20HBCTO1WW    | [e2f22f9f40](https://linux-hardware.org/?probe=e2f22f9f40) | Aug 27, 2021 |
| Dell          | Latitude E5470              | [ac04ecb1e5](https://linux-hardware.org/?probe=ac04ecb1e5) | Aug 22, 2021 |
| Dell          | XPS 15 9550                 | [0a28b37020](https://linux-hardware.org/?probe=0a28b37020) | Aug 15, 2021 |
| Acer          | Aspire A315-42              | [4a54197130](https://linux-hardware.org/?probe=4a54197130) | Aug 15, 2021 |
| Acer          | Aspire ES1-572              | [06ddc49173](https://linux-hardware.org/?probe=06ddc49173) | Aug 13, 2021 |
| Dell          | XPS 15 9570                 | [f20e1ba8fe](https://linux-hardware.org/?probe=f20e1ba8fe) | Aug 13, 2021 |
| Dell          | XPS 13 9380                 | [1c3776f221](https://linux-hardware.org/?probe=1c3776f221) | Aug 13, 2021 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | [ab00a7e359](https://linux-hardware.org/?probe=ab00a7e359) | Aug 13, 2021 |
| Notebook      | P377SM-A                    | [be5397dd67](https://linux-hardware.org/?probe=be5397dd67) | Aug 05, 2021 |
| HUAWEI        | KLVL-WXX9                   | [d677af1f50](https://linux-hardware.org/?probe=d677af1f50) | Aug 02, 2021 |
| HUAWEI        | KLVL-WXX9                   | [66c25f9637](https://linux-hardware.org/?probe=66c25f9637) | Jul 10, 2021 |
| Notebook      | P377SM-A                    | [bf37a519fa](https://linux-hardware.org/?probe=bf37a519fa) | May 17, 2021 |
| Notebook      | P377SM-A                    | [0834d4df8b](https://linux-hardware.org/?probe=0834d4df8b) | May 16, 2021 |
| Lenovo        | ThinkPad W541 20EF000UMN    | [f366b44668](https://linux-hardware.org/?probe=f366b44668) | Apr 11, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [31475604b7](https://linux-hardware.org/?probe=31475604b7) | Mar 12, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [151d163eb9](https://linux-hardware.org/?probe=151d163eb9) | Mar 12, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [4b33f82ac0](https://linux-hardware.org/?probe=4b33f82ac0) | Mar 06, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                                       | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| 5.14.10-300.fc35.x86_64                                       | 51        | 6.38%   |
| 5.14.16-301.fc35.x86_64                                       | 45        | 5.63%   |
| 5.15.6-200.fc35.x86_64                                        | 43        | 5.38%   |
| 5.15.12-200.fc35.x86_64                                       | 40        | 5%      |
| 5.16.16-200.fc35.x86_64                                       | 39        | 4.88%   |
| 5.16.18-200.fc35.x86_64                                       | 38        | 4.75%   |
| 5.14.18-300.fc35.x86_64                                       | 38        | 4.75%   |
| 5.16.12-200.fc35.x86_64                                       | 37        | 4.63%   |
| 5.16.9-200.fc35.x86_64                                        | 31        | 3.88%   |
| 5.14.17-301.fc35.x86_64                                       | 28        | 3.5%    |
| 5.15.16-200.fc35.x86_64                                       | 25        | 3.13%   |
| 5.15.11-200.fc35.x86_64                                       | 25        | 3.13%   |
| 5.16.11-200.fc35.x86_64                                       | 24        | 3%      |
| 5.15.10-200.fc35.x86_64                                       | 22        | 2.75%   |
| 5.14.14-300.fc35.x86_64                                       | 21        | 2.63%   |
| 5.16.5-200.fc35.x86_64                                        | 20        | 2.5%    |
| 5.15.14-200.fc35.x86_64                                       | 16        | 2%      |
| 5.15.13-200.fc35.x86_64                                       | 16        | 2%      |
| 5.16.8-200.fc35.x86_64                                        | 15        | 1.88%   |
| 5.15.8-200.fc35.x86_64                                        | 15        | 1.88%   |
| 5.15.4-201.fc35.x86_64                                        | 15        | 1.88%   |
| 5.15.5-200.fc35.x86_64                                        | 14        | 1.75%   |
| 5.15.18-200.fc35.x86_64                                       | 14        | 1.75%   |
| 5.14.15-300.fc35.x86_64                                       | 13        | 1.63%   |
| 5.16.14-200.fc35.x86_64                                       | 12        | 1.5%    |
| 5.15.7-200.fc35.x86_64                                        | 12        | 1.5%    |
| 5.16.15-201.fc35.x86_64                                       | 11        | 1.38%   |
| 5.16.7-200.fc35.x86_64                                        | 10        | 1.25%   |
| 5.15.17-200.fc35.x86_64                                       | 9         | 1.13%   |
| 5.14.9-300.fc35.x86_64                                        | 9         | 1.13%   |
| 5.15.15-200.fc35.x86_64                                       | 7         | 0.88%   |
| 5.14.0-60.fc35.x86_64                                         | 7         | 0.88%   |
| 5.16.10-200.fc35.x86_64                                       | 6         | 0.75%   |
| 5.14.11-300.fc35.x86_64                                       | 5         | 0.63%   |
| 5.14.0-0.rc5.42.fc35.x86_64                                   | 5         | 0.63%   |
| 5.16.17-200.fc35.x86_64                                       | 4         | 0.5%    |
| 5.16.13-200.fc35.x86_64                                       | 4         | 0.5%    |
| 5.14.7-300.fc35.x86_64                                        | 3         | 0.38%   |
| 5.14.12-300.fc35.x86_64                                       | 3         | 0.38%   |
| 5.15.6-200.rog.fc35.x86_64                                    | 2         | 0.25%   |
| 5.14.3-300.fc35.x86_64                                        | 2         | 0.25%   |
| 5.11.12-300.fc34.x86_64                                       | 2         | 0.25%   |
| 5.17.1-xm1.0.fc35.x86_64                                      | 1         | 0.13%   |
| 5.17.0-0.rc5.102.vanilla.1.fc35.x86_64                        | 1         | 0.13%   |
| 5.16.2-200.fc35.x86_64                                        | 1         | 0.13%   |
| 5.16.16-lqx2.0.fc35.x86_64                                    | 1         | 0.13%   |
| 5.16.13-xm1.0.fc35.x86_64                                     | 1         | 0.13%   |
| 5.16.12-250.vanilla.1.fc35.x86_64                             | 1         | 0.13%   |
| 5.16.12-200.mbp.fc33.x86_64                                   | 1         | 0.13%   |
| 5.16.1-xm1.0.fc35.x86_64                                      | 1         | 0.13%   |
| 5.16.0-0.rc7.20211231git4f3d93c6eaff.52.vanilla.1.fc35.x86_64 | 1         | 0.13%   |
| 5.16.0-0.rc5.35.vanilla.1.fc35.x86_64                         | 1         | 0.13%   |
| 5.15.8_tkg_pds                                                | 1         | 0.13%   |
| 5.15.8-200.rog.fc35.x86_64                                    | 1         | 0.13%   |
| 5.15.6-250.vanilla.1.fc35.x86_64                              | 1         | 0.13%   |
| 5.15.5-xm1tt.0.fc35.x86_64                                    | 1         | 0.13%   |
| 5.15.2-225.vanilla.1.fc35.x86_64                              | 1         | 0.13%   |
| 5.15.19-xm1tt.0.fc35.x86_64                                   | 1         | 0.13%   |
| 5.15.15-200.rog.fc35.x86_64                                   | 1         | 0.13%   |
| 5.15.13-lqx1.0.fc35.x86_64                                    | 1         | 0.13%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14.10 | 51        | 6.38%   |
| 5.15.6  | 46        | 5.76%   |
| 5.14.16 | 46        | 5.76%   |
| 5.15.12 | 41        | 5.13%   |
| 5.16.16 | 40        | 5.01%   |
| 5.16.12 | 39        | 4.88%   |
| 5.16.18 | 38        | 4.76%   |
| 5.14.18 | 38        | 4.76%   |
| 5.16.9  | 31        | 3.88%   |
| 5.14.17 | 28        | 3.5%    |
| 5.15.11 | 26        | 3.25%   |
| 5.15.16 | 25        | 3.13%   |
| 5.16.11 | 24        | 3%      |
| 5.15.10 | 22        | 2.75%   |
| 5.14.14 | 22        | 2.75%   |
| 5.16.5  | 20        | 2.5%    |
| 5.15.13 | 18        | 2.25%   |
| 5.15.8  | 17        | 2.13%   |
| 5.15.14 | 16        | 2%      |
| 5.16.8  | 15        | 1.88%   |
| 5.15.5  | 15        | 1.88%   |
| 5.15.4  | 15        | 1.88%   |
| 5.14.0  | 15        | 1.88%   |
| 5.15.18 | 14        | 1.75%   |
| 5.14.15 | 14        | 1.75%   |
| 5.16.14 | 12        | 1.5%    |
| 5.15.7  | 12        | 1.5%    |
| 5.16.15 | 11        | 1.38%   |
| 5.16.7  | 10        | 1.25%   |
| 5.15.17 | 9         | 1.13%   |
| 5.14.9  | 9         | 1.13%   |
| 5.15.15 | 8         | 1%      |
| 5.16.10 | 6         | 0.75%   |
| 5.16.13 | 5         | 0.63%   |
| 5.14.11 | 5         | 0.63%   |
| 5.16.17 | 4         | 0.5%    |
| 5.14.7  | 3         | 0.38%   |
| 5.14.12 | 3         | 0.38%   |
| 5.16.0  | 2         | 0.25%   |
| 5.14.3  | 2         | 0.25%   |
| 5.13.19 | 2         | 0.25%   |
| 5.12.0  | 2         | 0.25%   |
| 5.11.12 | 2         | 0.25%   |
| 5.17.1  | 1         | 0.13%   |
| 5.17.0  | 1         | 0.13%   |
| 5.16.2  | 1         | 0.13%   |
| 5.16.1  | 1         | 0.13%   |
| 5.15.2  | 1         | 0.13%   |
| 5.15.19 | 1         | 0.13%   |
| 5.14.8  | 1         | 0.13%   |
| 5.14.6  | 1         | 0.13%   |
| 5.14.5  | 1         | 0.13%   |
| 5.14.1  | 1         | 0.13%   |
| 5.13.9  | 1         | 0.13%   |
| 5.13.4  | 1         | 0.13%   |
| 5.13.0  | 1         | 0.13%   |
| 5.12.8  | 1         | 0.13%   |
| 5.10.93 | 1         | 0.13%   |
| 5.10.23 | 1         | 0.13%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 272       | 35.37%  |
| 5.16    | 248       | 32.25%  |
| 5.14    | 235       | 30.56%  |
| 5.13    | 5         | 0.65%   |
| 5.12    | 3         | 0.39%   |
| 5.17    | 2         | 0.26%   |
| 5.11    | 2         | 0.26%   |
| 5.10    | 2         | 0.26%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 721       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 577       | 78.83%  |
| KDE5            | 68        | 9.29%   |
| Unknown         | 24        | 3.28%   |
| MATE            | 13        | 1.78%   |
| Cinnamon        | 11        | 1.5%    |
| X-Cinnamon      | 9         | 1.23%   |
| XFCE            | 8         | 1.09%   |
| GNOME Classic   | 4         | 0.55%   |
| sway            | 3         | 0.41%   |
| i3              | 3         | 0.41%   |
| Pantheon        | 2         | 0.27%   |
| LXQt            | 2         | 0.27%   |
| LXDE            | 2         | 0.27%   |
| fluxbox         | 2         | 0.27%   |
| openbox         | 1         | 0.14%   |
| KDE             | 1         | 0.14%   |
| GNOME Flashback | 1         | 0.14%   |
| bspwm           | 1         | 0.14%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 501       | 68.44%  |
| X11     | 212       | 28.96%  |
| Unknown | 12        | 1.64%   |
| Tty     | 7         | 0.96%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 352       | 48.29%  |
| GDM     | 293       | 40.19%  |
| LightDM | 42        | 5.76%   |
| SDDM    | 39        | 5.35%   |
| LXDM    | 2         | 0.27%   |
| XDM     | 1         | 0.14%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 396       | 54.62%  |
| en_GB   | 65        | 8.97%   |
| pt_BR   | 34        | 4.69%   |
| ru_RU   | 32        | 4.41%   |
| fr_FR   | 23        | 3.17%   |
| de_DE   | 21        | 2.9%    |
| it_IT   | 19        | 2.62%   |
| pl_PL   | 13        | 1.79%   |
| en_CA   | 11        | 1.52%   |
| en_AU   | 11        | 1.52%   |
| es_ES   | 9         | 1.24%   |
| es_MX   | 6         | 0.83%   |
| en_IN   | 6         | 0.83%   |
| nl_NL   | 5         | 0.69%   |
| es_CL   | 5         | 0.69%   |
| C       | 5         | 0.69%   |
| zh_CN   | 4         | 0.55%   |
| tr_TR   | 4         | 0.55%   |
| sv_SE   | 4         | 0.55%   |
| fr_CA   | 4         | 0.55%   |
| es_AR   | 4         | 0.55%   |
| en_IL   | 4         | 0.55%   |
| uk_UA   | 3         | 0.41%   |
| en_NZ   | 3         | 0.41%   |
| cs_CZ   | 3         | 0.41%   |
| pt_PT   | 2         | 0.28%   |
| nb_NO   | 2         | 0.28%   |
| fi_FI   | 2         | 0.28%   |
| es_GT   | 2         | 0.28%   |
| es_CO   | 2         | 0.28%   |
| en_ZA   | 2         | 0.28%   |
| de_AT   | 2         | 0.28%   |
| Unknown | 2         | 0.28%   |
| szl_PL  | 1         | 0.14%   |
| sk_SK   | 1         | 0.14%   |
| ru_UA   | 1         | 0.14%   |
| ro_RO   | 1         | 0.14%   |
| nl_BE   | 1         | 0.14%   |
| lt_LT   | 1         | 0.14%   |
| ga_IE   | 1         | 0.14%   |
| fr_CH   | 1         | 0.14%   |
| fr_BE   | 1         | 0.14%   |
| es_PE   | 1         | 0.14%   |
| es_EC   | 1         | 0.14%   |
| en_DK   | 1         | 0.14%   |
| de_CH   | 1         | 0.14%   |
| da_DK   | 1         | 0.14%   |
| ca_ES   | 1         | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 616       | 84.85%  |
| BIOS | 110       | 15.15%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 545       | 75.28%  |
| Ext4    | 159       | 21.96%  |
| Xfs     | 16        | 2.21%   |
| Overlay | 3         | 0.41%   |
| Unknown | 1         | 0.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 362       | 49.45%  |
| GPT     | 333       | 45.49%  |
| MBR     | 37        | 5.05%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 658       | 90.14%  |
| Yes       | 72        | 9.86%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 598       | 82.14%  |
| Yes       | 130       | 17.86%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Lenovo                   | 213       | 29.54%  |
| Dell                     | 122       | 16.92%  |
| Hewlett-Packard          | 109       | 15.12%  |
| ASUSTek Computer         | 59        | 8.18%   |
| Acer                     | 53        | 7.35%   |
| Apple                    | 30        | 4.16%   |
| HUAWEI                   | 20        | 2.77%   |
| MSI                      | 13        | 1.8%    |
| Notebook                 | 11        | 1.53%   |
| Toshiba                  | 10        | 1.39%   |
| Sony                     | 9         | 1.25%   |
| Samsung Electronics      | 7         | 0.97%   |
| Positivo                 | 6         | 0.83%   |
| Google                   | 5         | 0.69%   |
| Framework                | 5         | 0.69%   |
| System76                 | 4         | 0.55%   |
| TUXEDO                   | 3         | 0.42%   |
| Razer                    | 3         | 0.42%   |
| Fujitsu                  | 3         | 0.42%   |
| Avell High Performance   | 3         | 0.42%   |
| PC Specialist            | 2         | 0.28%   |
| Panasonic                | 2         | 0.28%   |
| HONOR                    | 2         | 0.28%   |
| Hampoo                   | 2         | 0.28%   |
| GPU Company              | 2         | 0.28%   |
| Gigabyte Technology      | 2         | 0.28%   |
| Fujitsu Siemens          | 2         | 0.28%   |
| Alienware                | 2         | 0.28%   |
| Timi                     | 1         | 0.14%   |
| SiComputer               | 1         | 0.14%   |
| SCHNEIDER                | 1         | 0.14%   |
| Positivo Bahia - VAIO    | 1         | 0.14%   |
| Medion                   | 1         | 0.14%   |
| Mediacom                 | 1         | 0.14%   |
| Login Informatica        | 1         | 0.14%   |
| LG Electronics           | 1         | 0.14%   |
| LDLC                     | 1         | 0.14%   |
| Jumper                   | 1         | 0.14%   |
| Inspire Technology Group | 1         | 0.14%   |
| eMachines                | 1         | 0.14%   |
| Digibras                 | 1         | 0.14%   |
| Cube                     | 1         | 0.14%   |
| BESSTAR Tech             | 1         | 0.14%   |
| AVITA                    | 1         | 0.14%   |
| Unknown                  | 1         | 0.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| HUAWEI KLVL-WXX9                           | 5         | 0.69%   |
| HP Notebook                                | 5         | 0.69%   |
| Framework Laptop                           | 5         | 0.69%   |
| HP Pavilion Notebook                       | 4         | 0.55%   |
| Dell XPS 13 7390                           | 4         | 0.55%   |
| Dell Latitude E7440                        | 4         | 0.55%   |
| Lenovo ThinkBook 15 G2 ITL 20VE            | 3         | 0.42%   |
| Lenovo IdeaPad 530S-14IKB 81EU             | 3         | 0.42%   |
| Lenovo IdeaPad 3 14ALC6 82KT               | 3         | 0.42%   |
| HUAWEI HVY-WXX9                            | 3         | 0.42%   |
| HP Pavilion Aero Laptop 13-be0xxx          | 3         | 0.42%   |
| HP EliteBook 840 G3                        | 3         | 0.42%   |
| Dell XPS 17 9700                           | 3         | 0.42%   |
| Dell XPS 15 9570                           | 3         | 0.42%   |
| Dell XPS 15 9550                           | 3         | 0.42%   |
| Dell XPS 13 9310                           | 3         | 0.42%   |
| Dell XPS 13 9305                           | 3         | 0.42%   |
| Dell Precision 5510                        | 3         | 0.42%   |
| Dell Latitude 7490                         | 3         | 0.42%   |
| ASUS ROG Zephyrus G14 GA401QM_GA401QM      | 3         | 0.42%   |
| ASUS ROG Strix G513QY_G513QY               | 3         | 0.42%   |
| Apple MacBookPro9,2                        | 3         | 0.42%   |
| Apple MacBookPro14,1                       | 3         | 0.42%   |
| Acer Swift SF314-42                        | 3         | 0.42%   |
| MSI GE75 Raider 10SE                       | 2         | 0.28%   |
| MSI Delta 15 A5EFK                         | 2         | 0.28%   |
| Lenovo Yoga S740-14IIL 81RS                | 2         | 0.28%   |
| Lenovo ThinkPad X1 Carbon Gen 8 20U9CTO1WW | 2         | 0.28%   |
| Lenovo ThinkPad P1 Gen 3 20TJS53A00        | 2         | 0.28%   |
| Lenovo ThinkPad E14 Gen 3 20Y7CTO1WW       | 2         | 0.28%   |
| Lenovo Legion Y530-15ICH 81FV              | 2         | 0.28%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ           | 2         | 0.28%   |
| Lenovo Legion 5 15ARH05H 82B1              | 2         | 0.28%   |
| Lenovo Legion 5 15ARH05 82B5               | 2         | 0.28%   |
| Lenovo IdeaPad S145-15API 81V7             | 2         | 0.28%   |
| Lenovo IdeaPad 320-15ISK 80XH              | 2         | 0.28%   |
| Lenovo IdeaPad 3 14ITL6 82H7               | 2         | 0.28%   |
| HUAWEI NBLK-WAX9X                          | 2         | 0.28%   |
| HUAWEI BOHK-WAX9X                          | 2         | 0.28%   |
| HONOR NBD-WXX9                             | 2         | 0.28%   |
| HP ProBook 650 G1                          | 2         | 0.28%   |
| HP ProBook 470 G5                          | 2         | 0.28%   |
| HP ProBook 450 G3                          | 2         | 0.28%   |
| HP ProBook 430 G5                          | 2         | 0.28%   |
| HP Pavilion Laptop 15-eh0xxx               | 2         | 0.28%   |
| HP Pavilion Gaming Laptop 15-ec1xxx        | 2         | 0.28%   |
| HP Pavilion Gaming Laptop 15-ec0xxx        | 2         | 0.28%   |
| HP Pavilion g4                             | 2         | 0.28%   |
| HP Pavilion 17                             | 2         | 0.28%   |
| HP Pavilion 15                             | 2         | 0.28%   |
| HP Laptop 15s-fq2xxx                       | 2         | 0.28%   |
| HP Laptop 15s-eq0xxx                       | 2         | 0.28%   |
| HP EliteBook 850 G5                        | 2         | 0.28%   |
| Dell XPS 15 9500                           | 2         | 0.28%   |
| Dell XPS 13 9380                           | 2         | 0.28%   |
| Dell Vostro 5402                           | 2         | 0.28%   |
| Dell Precision 5540                        | 2         | 0.28%   |
| Dell Latitude E6530                        | 2         | 0.28%   |
| Dell Latitude E5570                        | 2         | 0.28%   |
| Dell Latitude E5470                        | 2         | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Lenovo ThinkPad             | 119       | 16.5%   |
| Lenovo IdeaPad              | 51        | 7.07%   |
| Dell Latitude               | 40        | 5.55%   |
| Dell Inspiron               | 34        | 4.72%   |
| Dell XPS                    | 28        | 3.88%   |
| Acer Aspire                 | 28        | 3.88%   |
| HP Pavilion                 | 27        | 3.74%   |
| HP EliteBook                | 18        | 2.5%    |
| HP ProBook                  | 17        | 2.36%   |
| ASUS ROG                    | 15        | 2.08%   |
| HP Laptop                   | 14        | 1.94%   |
| Lenovo Legion               | 11        | 1.53%   |
| ASUS VivoBook               | 11        | 1.53%   |
| Acer Swift                  | 11        | 1.53%   |
| Lenovo ThinkBook            | 9         | 1.25%   |
| Dell Precision              | 9         | 1.25%   |
| Acer Nitro                  | 9         | 1.25%   |
| Toshiba Satellite           | 8         | 1.11%   |
| HP ZBook                    | 8         | 1.11%   |
| Dell Vostro                 | 7         | 0.97%   |
| Lenovo Yoga                 | 6         | 0.83%   |
| HP ENVY                     | 6         | 0.83%   |
| ASUS ASUS                   | 6         | 0.83%   |
| HUAWEI KLVL-WXX9            | 5         | 0.69%   |
| HP Notebook                 | 5         | 0.69%   |
| Framework Laptop            | 5         | 0.69%   |
| HP OMEN                     | 4         | 0.55%   |
| Apple MacBookPro11          | 4         | 0.55%   |
| HUAWEI HVY-WXX9             | 3         | 0.42%   |
| Fujitsu LIFEBOOK            | 3         | 0.42%   |
| ASUS ZenBook                | 3         | 0.42%   |
| Apple MacBookPro9           | 3         | 0.42%   |
| Apple MacBookPro14          | 3         | 0.42%   |
| TUXEDO InfinityBook         | 2         | 0.28%   |
| Razer Blade                 | 2         | 0.28%   |
| Notebook NH5x               | 2         | 0.28%   |
| MSI Modern                  | 2         | 0.28%   |
| MSI GE75                    | 2         | 0.28%   |
| MSI Delta                   | 2         | 0.28%   |
| HUAWEI NBLK-WAX9X           | 2         | 0.28%   |
| HUAWEI BOHK-WAX9X           | 2         | 0.28%   |
| HONOR NBD-WXX9              | 2         | 0.28%   |
| HP Compaq                   | 2         | 0.28%   |
| HP 15                       | 2         | 0.28%   |
| Fujitsu Siemens ESPRIMO     | 2         | 0.28%   |
| Dell G5                     | 2         | 0.28%   |
| Avell High Performance B.ON | 2         | 0.28%   |
| ASUS TUF                    | 2         | 0.28%   |
| Apple MacBookPro7           | 2         | 0.28%   |
| Apple MacBookPro6           | 2         | 0.28%   |
| Apple MacBookPro10          | 2         | 0.28%   |
| Apple MacBookAir7           | 2         | 0.28%   |
| Apple MacBookAir6           | 2         | 0.28%   |
| Apple MacBook6              | 2         | 0.28%   |
| Acer Predator               | 2         | 0.28%   |
| Unknown                     | 2         | 0.28%   |
| TUXEDO Polaris              | 1         | 0.14%   |
| Toshiba TECRA               | 1         | 0.14%   |
| Toshiba NB255               | 1         | 0.14%   |
| Timi TM1612                 | 1         | 0.14%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 142       | 19.69%  |
| 2021 | 115       | 15.95%  |
| 2019 | 94        | 13.04%  |
| 2018 | 71        | 9.85%   |
| 2017 | 50        | 6.93%   |
| 2016 | 48        | 6.66%   |
| 2013 | 41        | 5.69%   |
| 2015 | 33        | 4.58%   |
| 2014 | 32        | 4.44%   |
| 2011 | 30        | 4.16%   |
| 2012 | 28        | 3.88%   |
| 2010 | 15        | 2.08%   |
| 2008 | 10        | 1.39%   |
| 2009 | 7         | 0.97%   |
| 2022 | 4         | 0.55%   |
| 2007 | 1         | 0.14%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 721       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 577       | 79.48%  |
| Enabled  | 149       | 20.52%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 714       | 99.03%  |
| Yes  | 7         | 0.97%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 217       | 30.01%  |
| 16.01-24.0  | 177       | 24.48%  |
| 8.01-16.0   | 141       | 19.5%   |
| 32.01-64.0  | 80        | 11.07%  |
| 3.01-4.0    | 75        | 10.37%  |
| 64.01-256.0 | 13        | 1.8%    |
| 1.01-2.0    | 9         | 1.24%   |
| 24.01-32.0  | 7         | 0.97%   |
| 2.01-3.0    | 4         | 0.55%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 218       | 28.31%  |
| 4.01-8.0   | 217       | 28.18%  |
| 3.01-4.0   | 169       | 21.95%  |
| 1.01-2.0   | 111       | 14.42%  |
| 8.01-16.0  | 46        | 5.97%   |
| 16.01-24.0 | 5         | 0.65%   |
| 0.51-1.0   | 3         | 0.39%   |
| 24.01-32.0 | 1         | 0.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 518       | 71.35%  |
| 2      | 180       | 24.79%  |
| 3      | 19        | 2.62%   |
| 0      | 4         | 0.55%   |
| 5      | 2         | 0.28%   |
| 4      | 2         | 0.28%   |
| 6      | 1         | 0.14%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 586       | 81.05%  |
| Yes       | 137       | 18.95%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 521       | 71.86%  |
| No        | 204       | 28.14%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 710       | 98.47%  |
| No        | 11        | 1.53%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 611       | 84.04%  |
| No        | 116       | 15.96%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country             | Notebooks | Percent |
|---------------------|-----------|---------|
| USA                 | 109       | 15.06%  |
| Brazil              | 58        | 8.01%   |
| Russia              | 54        | 7.46%   |
| Germany             | 36        | 4.97%   |
| Italy               | 32        | 4.42%   |
| UK                  | 27        | 3.73%   |
| France              | 27        | 3.73%   |
| Canada              | 27        | 3.73%   |
| India               | 26        | 3.59%   |
| Poland              | 21        | 2.9%    |
| Netherlands         | 17        | 2.35%   |
| Spain               | 16        | 2.21%   |
| Turkey              | 13        | 1.8%    |
| Sweden              | 13        | 1.8%    |
| Czechia             | 12        | 1.66%   |
| Norway              | 11        | 1.52%   |
| Mexico              | 11        | 1.52%   |
| Indonesia           | 11        | 1.52%   |
| Austria             | 11        | 1.52%   |
| Australia           | 11        | 1.52%   |
| Ukraine             | 9         | 1.24%   |
| Belgium             | 9         | 1.24%   |
| Hungary             | 8         | 1.1%    |
| Portugal            | 7         | 0.97%   |
| Israel              | 7         | 0.97%   |
| Greece              | 7         | 0.97%   |
| Argentina           | 7         | 0.97%   |
| Switzerland         | 6         | 0.83%   |
| Romania             | 6         | 0.83%   |
| Finland             | 6         | 0.83%   |
| China               | 6         | 0.83%   |
| Chile               | 6         | 0.83%   |
| Belarus             | 6         | 0.83%   |
| South Africa        | 5         | 0.69%   |
| Denmark             | 5         | 0.69%   |
| Saudi Arabia        | 4         | 0.55%   |
| Philippines         | 4         | 0.55%   |
| New Zealand         | 4         | 0.55%   |
| Japan               | 4         | 0.55%   |
| Croatia             | 4         | 0.55%   |
| Iran                | 3         | 0.41%   |
| Georgia             | 3         | 0.41%   |
| Colombia            | 3         | 0.41%   |
| Bulgaria            | 3         | 0.41%   |
| Venezuela           | 2         | 0.28%   |
| Tunisia             | 2         | 0.28%   |
| Serbia              | 2         | 0.28%   |
| Peru                | 2         | 0.28%   |
| Panama              | 2         | 0.28%   |
| Malaysia            | 2         | 0.28%   |
| Kenya               | 2         | 0.28%   |
| Kazakhstan          | 2         | 0.28%   |
| Ireland             | 2         | 0.28%   |
| Guatemala           | 2         | 0.28%   |
| Cyprus              | 2         | 0.28%   |
| Algeria             | 2         | 0.28%   |
| Vietnam             | 1         | 0.14%   |
| Uruguay             | 1         | 0.14%   |
| UAE                 | 1         | 0.14%   |
| Trinidad and Tobago | 1         | 0.14%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 23        | 3.07%   |
| Istanbul          | 11        | 1.47%   |
| São Paulo        | 10        | 1.34%   |
| Vienna            | 8         | 1.07%   |
| Milan             | 8         | 1.07%   |
| Montreal          | 7         | 0.93%   |
| Sydney            | 6         | 0.8%    |
| St Petersburg     | 6         | 0.8%    |
| Warsaw            | 5         | 0.67%   |
| Prague            | 5         | 0.67%   |
| Minsk             | 5         | 0.67%   |
| Madrid            | 5         | 0.67%   |
| Coimbatore        | 5         | 0.67%   |
| Athens            | 5         | 0.67%   |
| Amsterdam         | 5         | 0.67%   |
| Zagreb            | 4         | 0.53%   |
| Yekaterinburg     | 4         | 0.53%   |
| Rome              | 4         | 0.53%   |
| Paris             | 4         | 0.53%   |
| Oslo              | 4         | 0.53%   |
| Munich            | 4         | 0.53%   |
| Mexico City       | 4         | 0.53%   |
| Kyiv              | 4         | 0.53%   |
| Jakarta           | 4         | 0.53%   |
| Helsinki          | 4         | 0.53%   |
| Fortaleza         | 4         | 0.53%   |
| Budapest          | 4         | 0.53%   |
| Bucharest         | 4         | 0.53%   |
| Berlin            | 4         | 0.53%   |
| Belo Horizonte    | 4         | 0.53%   |
| Zurich            | 3         | 0.4%    |
| WÃ¶rgl          | 3         | 0.4%    |
| Vancouver         | 3         | 0.4%    |
| Ufa               | 3         | 0.4%    |
| Seattle           | 3         | 0.4%    |
| Rotterdam         | 3         | 0.4%    |
| Rio de Janeiro    | 3         | 0.4%    |
| Nuremberg         | 3         | 0.4%    |
| Nizhniy Novgorod  | 3         | 0.4%    |
| New Delhi         | 3         | 0.4%    |
| Mumbai            | 3         | 0.4%    |
| Lyon              | 3         | 0.4%    |
| Los Angeles       | 3         | 0.4%    |
| Lawrenceville     | 3         | 0.4%    |
| Krakow            | 3         | 0.4%    |
| K'alak'i T'bilisi | 3         | 0.4%    |
| Frankfurt am Main | 3         | 0.4%    |
| East Longmeadow   | 3         | 0.4%    |
| Chicago           | 3         | 0.4%    |
| Brno              | 3         | 0.4%    |
| Bengaluru         | 3         | 0.4%    |
| Wroclaw           | 2         | 0.27%   |
| Tunis             | 2         | 0.27%   |
| Tel Aviv          | 2         | 0.27%   |
| Surabaya          | 2         | 0.27%   |
| Sun City Center   | 2         | 0.27%   |
| Southampton       | 2         | 0.27%   |
| Sofia             | 2         | 0.27%   |
| Shenzhen          | 2         | 0.27%   |
| Santo AndrÃ©    | 2         | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 191       | 250    | 20.9%   |
| WDC                            | 105       | 113    | 11.49%  |
| Sandisk                        | 65        | 81     | 7.11%   |
| Toshiba                        | 64        | 67     | 7%      |
| SK Hynix                       | 60        | 70     | 6.56%   |
| Seagate                        | 57        | 70     | 6.24%   |
| Unknown                        | 48        | 57     | 5.25%   |
| Kingston                       | 44        | 48     | 4.81%   |
| Intel                          | 38        | 48     | 4.16%   |
| Micron Technology              | 30        | 35     | 3.28%   |
| KIOXIA                         | 22        | 29     | 2.41%   |
| Crucial                        | 21        | 26     | 2.3%    |
| Apple                          | 16        | 18     | 1.75%   |
| HGST                           | 13        | 14     | 1.42%   |
| A-DATA Technology              | 13        | 14     | 1.42%   |
| Phison                         | 9         | 10     | 0.98%   |
| LITEON                         | 8         | 8      | 0.88%   |
| Transcend                      | 7         | 8      | 0.77%   |
| Hitachi                        | 7         | 7      | 0.77%   |
| Silicon Motion                 | 6         | 6      | 0.66%   |
| XPG                            | 4         | 5      | 0.44%   |
| PLEXTOR                        | 4         | 5      | 0.44%   |
| Lexar                          | 4         | 4      | 0.44%   |
| Corsair                        | 4         | 4      | 0.44%   |
| China                          | 4         | 4      | 0.44%   |
| ADATA Technology               | 4         | 4      | 0.44%   |
| Unknown                        | 4         | 5      | 0.44%   |
| Union Memory (Shenzhen)        | 3         | 3      | 0.33%   |
| UMIS                           | 3         | 3      | 0.33%   |
| Team                           | 3         | 4      | 0.33%   |
| PNY                            | 3         | 4      | 0.33%   |
| Patriot                        | 3         | 3      | 0.33%   |
| Mushkin                        | 3         | 4      | 0.33%   |
| YMTC                           | 2         | 2      | 0.22%   |
| SPCC                           | 2         | 2      | 0.22%   |
| Realtek Semiconductor          | 2         | 3      | 0.22%   |
| Ramsta                         | 2         | 3      | 0.22%   |
| LITEONIT                       | 2         | 2      | 0.22%   |
| Lenovo                         | 2         | 2      | 0.22%   |
| HPE                            | 2         | 4      | 0.22%   |
| Hewlett-Packard                | 2         | 1      | 0.22%   |
| FORESEE                        | 2         | 2      | 0.22%   |
| WDC WDS                        | 1         | 1      | 0.11%   |
| USB3.1                         | 1         | 1      | 0.11%   |
| TO Exter                       | 1         | 1      | 0.11%   |
| TCSUNBOW                       | 1         | 1      | 0.11%   |
| SSSTC                          | 1         | 1      | 0.11%   |
| SSK                            | 1         | 1      | 0.11%   |
| Solid State Storage Technology | 1         | 1      | 0.11%   |
| MX                             | 1         | 1      | 0.11%   |
| Mass                           | 1         | 1      | 0.11%   |
| LDLC                           | 1         | 1      | 0.11%   |
| LaCie                          | 1         | 2      | 0.11%   |
| KingSpec                       | 1         | 1      | 0.11%   |
| JMicron                        | 1         | 1      | 0.11%   |
| JetFlash                       | 1         | 1      | 0.11%   |
| HUAWEI                         | 1         | 1      | 0.11%   |
| Gigabyte Technology            | 1         | 1      | 0.11%   |
| External                       | 1         | 1      | 0.11%   |
| CT1000P2                       | 1         | 1      | 0.11%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 512GB           | 25        | 2.62%   |
| SK Hynix NVMe SSD Drive 512GB          | 15        | 1.57%   |
| Sandisk NVMe SSD Drive 512GB           | 14        | 1.47%   |
| Sandisk NVMe SSD Drive 256GB           | 11        | 1.15%   |
| Samsung NVMe SSD Drive 256GB           | 11        | 1.15%   |
| Seagate ST1000LM035-1RK172 1TB         | 10        | 1.05%   |
| Kingston SA400S37480G 480GB SSD        | 10        | 1.05%   |
| Unknown MMC Card  64GB                 | 9         | 0.94%   |
| Samsung SM963 2.5" NVMe PCIe SSD 500GB | 9         | 0.94%   |
| Samsung NVMe SSD Drive 1TB             | 8         | 0.84%   |
| Kingston SA400S37240G 240GB SSD        | 8         | 0.84%   |
| Toshiba MQ04ABF100 1TB                 | 7         | 0.73%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD    | 7         | 0.73%   |
| SK Hynix NVMe SSD Drive 256GB          | 7         | 0.73%   |
| Sandisk NVMe SSD Drive 500GB           | 7         | 0.73%   |
| Samsung NVMe SSD Drive 1024GB          | 7         | 0.73%   |
| KIOXIA NVMe SSD Drive 512GB            | 7         | 0.73%   |
| Intel NVMe SSD Drive 512GB             | 7         | 0.73%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB   | 6         | 0.63%   |
| Unknown MMC Card  32GB                 | 6         | 0.63%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 6         | 0.63%   |
| Sandisk NVMe SSD Drive 1TB             | 6         | 0.63%   |
| Samsung SSD 850 EVO 250GB              | 6         | 0.63%   |
| Samsung MZVLB1T0HBLR-000L7 1TB         | 6         | 0.63%   |
| HGST HTS721010A9E630 1TB               | 6         | 0.63%   |
| Seagate ST1000LM048-2E7172 1TB         | 5         | 0.52%   |
| Samsung SSD 970 EVO Plus 1TB           | 5         | 0.52%   |
| WDC WD10SPZX-21Z10T0 1TB               | 4         | 0.42%   |
| Unknown SD128  128GB                   | 4         | 0.42%   |
| Unknown MMC Card  128GB                | 4         | 0.42%   |
| Toshiba MQ01ABF050 500GB               | 4         | 0.42%   |
| SK Hynix BC711 NVMe 512GB              | 4         | 0.42%   |
| Seagate ST500LT012-1DG142 500GB        | 4         | 0.42%   |
| Seagate ST1000LM014-1EJ164 1TB         | 4         | 0.42%   |
| Seagate Expansion 500GB                | 4         | 0.42%   |
| Sandisk NVMe SSD Drive 1024GB          | 4         | 0.42%   |
| Samsung SSD 980 PRO 500GB              | 4         | 0.42%   |
| Samsung SSD 980 1TB                    | 4         | 0.42%   |
| Samsung SSD 860 EVO 500GB              | 4         | 0.42%   |
| Samsung SSD 860 EVO 250GB              | 4         | 0.42%   |
| Samsung NVMe SSD Drive 2TB             | 4         | 0.42%   |
| Phison 311CD0512GB                     | 4         | 0.42%   |
| Micron NVMe SSD Drive 512GB            | 4         | 0.42%   |
| KIOXIA NVMe SSD Drive 256GB            | 4         | 0.42%   |
| KIOXIA KBG40ZNS512G NVMe 512GB         | 4         | 0.42%   |
| Kingston SA400S37120G 120GB SSD        | 4         | 0.42%   |
| Unknown                                | 4         | 0.42%   |
| WDC WD10JPVX-60JC3T0 1TB               | 3         | 0.31%   |
| WDC PC SN730 SDBPNTY-512G-1027 512GB   | 3         | 0.31%   |
| Unknown MMC Card  8GB                  | 3         | 0.31%   |
| Toshiba NVMe SSD Drive 256GB           | 3         | 0.31%   |
| Toshiba MQ01ABD100 1TB                 | 3         | 0.31%   |
| Toshiba MQ01ABD075 752GB               | 3         | 0.31%   |
| Toshiba KXG6AZNV256G 256GB             | 3         | 0.31%   |
| SK Hynix PC401 NVMe 512GB              | 3         | 0.31%   |
| SK Hynix NVMe SSD Drive 1024GB         | 3         | 0.31%   |
| Seagate ST2000LM003 HN-M201RAD 2TB     | 3         | 0.31%   |
| Samsung SSD 970 EVO Plus 500GB         | 3         | 0.31%   |
| Samsung SSD 970 EVO Plus 2TB           | 3         | 0.31%   |
| Samsung SSD 860 EVO 2TB                | 3         | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 56        | 69     | 34.57%  |
| WDC                 | 53        | 56     | 32.72%  |
| Toshiba             | 28        | 29     | 17.28%  |
| HGST                | 13        | 14     | 8.02%   |
| Hitachi             | 7         | 7      | 4.32%   |
| Unknown             | 2         | 2      | 1.23%   |
| Samsung Electronics | 1         | 1      | 0.62%   |
| LaCie               | 1         | 2      | 0.62%   |
| Apple               | 1         | 1      | 0.62%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 59        | 79     | 23.32%  |
| Kingston            | 31        | 34     | 12.25%  |
| SanDisk             | 20        | 30     | 7.91%   |
| Crucial             | 19        | 24     | 7.51%   |
| WDC                 | 14        | 16     | 5.53%   |
| Intel               | 13        | 15     | 5.14%   |
| Apple               | 10        | 10     | 3.95%   |
| Micron Technology   | 9         | 10     | 3.56%   |
| A-DATA Technology   | 9         | 10     | 3.56%   |
| Toshiba             | 6         | 7      | 2.37%   |
| SK Hynix            | 6         | 6      | 2.37%   |
| LITEON              | 6         | 6      | 2.37%   |
| Transcend           | 5         | 6      | 1.98%   |
| China               | 4         | 4      | 1.58%   |
| PNY                 | 3         | 4      | 1.19%   |
| PLEXTOR             | 3         | 4      | 1.19%   |
| Patriot             | 3         | 3      | 1.19%   |
| Mushkin             | 3         | 4      | 1.19%   |
| Team                | 2         | 3      | 0.79%   |
| SPCC                | 2         | 2      | 0.79%   |
| Ramsta              | 2         | 3      | 0.79%   |
| LITEONIT            | 2         | 2      | 0.79%   |
| Lexar               | 2         | 2      | 0.79%   |
| FORESEE             | 2         | 2      | 0.79%   |
| Corsair             | 2         | 2      | 0.79%   |
| WDC WDS             | 1         | 1      | 0.4%    |
| Unknown             | 1         | 1      | 0.4%    |
| TO Exter            | 1         | 1      | 0.4%    |
| TCSUNBOW            | 1         | 1      | 0.4%    |
| MX                  | 1         | 1      | 0.4%    |
| KingSpec            | 1         | 1      | 0.4%    |
| JMicron             | 1         | 1      | 0.4%    |
| HPE                 | 1         | 3      | 0.4%    |
| Hewlett-Packard     | 1         | 1      | 0.4%    |
| Gigabyte Technology | 1         | 1      | 0.4%    |
| CT1000P2            | 1         | 1      | 0.4%    |
| BIWIN               | 1         | 1      | 0.4%    |
| ASMT                | 1         | 1      | 0.4%    |
| Apacer              | 1         | 1      | 0.4%    |
| ADATA SU            | 1         | 1      | 0.4%    |
| 1TB                 | 1         | 1      | 0.4%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 408       | 517    | 47.11%  |
| SSD     | 240       | 306    | 27.71%  |
| HDD     | 158       | 181    | 18.24%  |
| MMC     | 45        | 60     | 5.2%    |
| Unknown | 15        | 15     | 1.73%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 408       | 516    | 49.33%  |
| SATA | 341       | 462    | 41.23%  |
| MMC  | 45        | 60     | 5.44%   |
| SAS  | 33        | 41     | 3.99%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 263       | 313    | 66.58%  |
| 0.51-1.0   | 111       | 145    | 28.1%   |
| 1.01-2.0   | 20        | 28     | 5.06%   |
| 3.01-4.0   | 1         | 1      | 0.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 501-1000       | 153       | 21.07%  |
| 251-500        | 136       | 18.73%  |
| 1-20           | 116       | 15.98%  |
| 101-250        | 115       | 15.84%  |
| 1001-2000      | 75        | 10.33%  |
| Unknown        | 65        | 8.95%   |
| 51-100         | 30        | 4.13%   |
| More than 3000 | 16        | 2.2%    |
| 21-50          | 11        | 1.52%   |
| 2001-3000      | 9         | 1.24%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 250       | 33.29%  |
| 21-50          | 134       | 17.84%  |
| 101-250        | 109       | 14.51%  |
| 51-100         | 85        | 11.32%  |
| Unknown        | 65        | 8.66%   |
| 251-500        | 52        | 6.92%   |
| 501-1000       | 37        | 4.93%   |
| 1001-2000      | 16        | 2.13%   |
| More than 3000 | 2         | 0.27%   |
| 2001-3000      | 1         | 0.13%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 2         | 5      | 8.7%    |
| WDC WD5000LPLX-60ZNTT1 500GB                        | 1         | 1      | 4.35%   |
| WDC WD1600BEVT-24A23T0 160GB                        | 1         | 1      | 4.35%   |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 4.35%   |
| Toshiba MQ01ABD050V 500GB                           | 1         | 1      | 4.35%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD             | 1         | 1      | 4.35%   |
| SK Hynix HFS128G39TND-N210A 128GB SSD               | 1         | 1      | 4.35%   |
| Samsung Electronics SSD 870 EVO 500GB               | 1         | 1      | 4.35%   |
| Samsung Electronics MZNLH256HAJD-000H1 256GB SSD    | 1         | 1      | 4.35%   |
| PLEXTOR PX-256M8PeG 256GB                           | 1         | 1      | 4.35%   |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 2      | 4.35%   |
| LITEON CV3-CE256 256GB SSD                          | 1         | 1      | 4.35%   |
| Intel SSDSC2BF180A5L 180GB                          | 1         | 1      | 4.35%   |
| Hitachi HTS545050B9A300 500GB                       | 1         | 1      | 4.35%   |
| Hitachi HTS545025B9SA02 250GB                       | 1         | 1      | 4.35%   |
| Hitachi HTS543225L9A300 250GB                       | 1         | 1      | 4.35%   |
| HGST HTS721010A9E630 1TB                            | 1         | 1      | 4.35%   |
| HGST HTS545050A7E680 500GB                          | 1         | 1      | 4.35%   |
| Crucial CT240BX500SSD1 240GB                        | 1         | 1      | 4.35%   |
| Crucial CT1050MX300SSD1 1TB                         | 1         | 2      | 4.35%   |
| Crucial CT1000P1SSD8 1TB                            | 1         | 1      | 4.35%   |
| A-DATA Technology IM2S3138E-128GM-B 128GB SSD       | 1         | 1      | 4.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 3         | 3      | 13.04%  |
| Hitachi             | 3         | 3      | 13.04%  |
| Crucial             | 3         | 4      | 13.04%  |
| WDC                 | 2         | 2      | 8.7%    |
| Seagate             | 2         | 5      | 8.7%    |
| Samsung Electronics | 2         | 2      | 8.7%    |
| HGST                | 2         | 2      | 8.7%    |
| SK Hynix            | 1         | 1      | 4.35%   |
| PLEXTOR             | 1         | 1      | 4.35%   |
| Micron Technology   | 1         | 2      | 4.35%   |
| LITEON              | 1         | 1      | 4.35%   |
| Intel               | 1         | 1      | 4.35%   |
| A-DATA Technology   | 1         | 1      | 4.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 3         | 3      | 27.27%  |
| WDC     | 2         | 2      | 18.18%  |
| Toshiba | 2         | 2      | 18.18%  |
| Seagate | 2         | 5      | 18.18%  |
| HGST    | 2         | 2      | 18.18%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 14     | 47.83%  |
| SSD  | 10        | 12     | 43.48%  |
| NVMe | 2         | 2      | 8.7%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 980 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 401       | 596    | 51.94%  |
| Works    | 347       | 454    | 44.95%  |
| Malfunc  | 23        | 28     | 2.98%   |
| Failed   | 1         | 1      | 0.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 408       | 44.84%  |
| Samsung Electronics              | 139       | 15.27%  |
| AMD                              | 86        | 9.45%   |
| Sandisk                          | 77        | 8.46%   |
| SK Hynix                         | 52        | 5.71%   |
| Toshiba America Info Systems     | 32        | 3.52%   |
| Micron Technology                | 21        | 2.31%   |
| KIOXIA                           | 19        | 2.09%   |
| Kingston Technology Company      | 13        | 1.43%   |
| Silicon Motion                   | 10        | 1.1%    |
| Phison Electronics               | 10        | 1.1%    |
| ADATA Technology                 | 10        | 1.1%    |
| Nvidia                           | 6         | 0.66%   |
| Union Memory (Shenzhen)          | 5         | 0.55%   |
| Apple                            | 4         | 0.44%   |
| Lite-On Technology               | 3         | 0.33%   |
| Yangtze Memory Technologies      | 2         | 0.22%   |
| Solid State Storage Technology   | 2         | 0.22%   |
| Realtek Semiconductor            | 2         | 0.22%   |
| Micron/Crucial Technology        | 2         | 0.22%   |
| Marvell Technology Group         | 2         | 0.22%   |
| Lenovo                           | 2         | 0.22%   |
| Silicon Integrated Systems [SiS] | 1         | 0.11%   |
| JMicron Technology               | 1         | 0.11%   |
| Beijing Starblaze Technology     | 1         | 0.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 82        | 8.68%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 77        | 8.15%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 68        | 7.2%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 42        | 4.44%   |
| Samsung NVMe SSD Controller 980                                                  | 39        | 4.13%   |
| Intel Volume Management Device NVMe RAID Controller                              | 31        | 3.28%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 26        | 2.75%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 24        | 2.54%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 24        | 2.54%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 24        | 2.54%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 22        | 2.33%   |
| SK Hynix Gold P31 SSD                                                            | 21        | 2.22%   |
| Micron Non-Volatile memory controller                                            | 21        | 2.22%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 19        | 2.01%   |
| KIOXIA Non-Volatile memory controller                                            | 19        | 2.01%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 16        | 1.69%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 16        | 1.69%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 16        | 1.69%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 15        | 1.59%   |
| Sandisk Non-Volatile memory controller                                           | 15        | 1.59%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 14        | 1.48%   |
| Intel Comet Lake SATA AHCI Controller                                            | 13        | 1.38%   |
| SK Hynix Non-Volatile memory controller                                          | 12        | 1.27%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 11        | 1.16%   |
| Intel SSD 660P Series                                                            | 11        | 1.16%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 10        | 1.06%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 9         | 0.95%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 9         | 0.95%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 9         | 0.95%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 9         | 0.95%   |
| SK Hynix BC511                                                                   | 8         | 0.85%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 8         | 0.85%   |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                      | 7         | 0.74%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 7         | 0.74%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 7         | 0.74%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 7         | 0.74%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 7         | 0.74%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 6         | 0.63%   |
| Phison PS5013 E13 NVMe Controller                                                | 6         | 0.63%   |
| Intel Non-Volatile memory controller                                             | 6         | 0.63%   |
| ADATA Non-Volatile memory controller                                             | 6         | 0.63%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 5         | 0.53%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                       | 5         | 0.53%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 5         | 0.53%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 5         | 0.53%   |
| Sandisk PC SN520 NVMe SSD                                                        | 5         | 0.53%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 5         | 0.53%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 4         | 0.42%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 4         | 0.42%   |
| Samsung Electronics SATA controller                                              | 4         | 0.42%   |
| Phison E12 NVMe Controller                                                       | 4         | 0.42%   |
| Kingston Company Company Non-Volatile memory controller                          | 4         | 0.42%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 4         | 0.42%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 4         | 0.42%   |
| Toshiba America Info Systems NVMe Controller                                     | 3         | 0.32%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 3         | 0.32%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                         | 3         | 0.32%   |
| Nvidia MCP79 AHCI Controller                                                     | 3         | 0.32%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 3         | 0.32%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 3         | 0.32%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 437       | 47.92%  |
| NVMe | 406       | 44.52%  |
| RAID | 58        | 6.36%   |
| IDE  | 11        | 1.21%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 562       | 77.95%  |
| AMD    | 159       | 22.05%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 28        | 3.88%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 22        | 3.05%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 17        | 2.36%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 13        | 1.8%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 13        | 1.8%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 13        | 1.8%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 12        | 1.66%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 12        | 1.66%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 12        | 1.66%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 11        | 1.53%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 11        | 1.53%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 11        | 1.53%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 10        | 1.39%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 9         | 1.25%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 8         | 1.11%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 8         | 1.11%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 8         | 1.11%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 8         | 1.11%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 8         | 1.11%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 8         | 1.11%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 7         | 0.97%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 7         | 0.97%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 7         | 0.97%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 7         | 0.97%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 7         | 0.97%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 7         | 0.97%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 7         | 0.97%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 6         | 0.83%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 6         | 0.83%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 6         | 0.83%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 6         | 0.83%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 6         | 0.83%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 6         | 0.83%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 6         | 0.83%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 6         | 0.83%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 6         | 0.83%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 5         | 0.69%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 5         | 0.69%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 5         | 0.69%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 5         | 0.69%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 5         | 0.69%   |
| Intel Core i3-3120M CPU @ 2.50GHz             | 5         | 0.69%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 5         | 0.69%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 5         | 0.69%   |
| AMD Ryzen 5 5600U with Radeon Graphics        | 5         | 0.69%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 5         | 0.69%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 5         | 0.69%   |
| Intel Core i7-9850H CPU @ 2.60GHz             | 4         | 0.55%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 4         | 0.55%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 4         | 0.55%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 4         | 0.55%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 4         | 0.55%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 4         | 0.55%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 0.55%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 4         | 0.55%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 4         | 0.55%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 4         | 0.55%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 4         | 0.55%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 4         | 0.55%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 4         | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 212       | 29.4%   |
| Intel Core i5           | 146       | 20.25%  |
| Other                   | 81        | 11.23%  |
| Intel Core i3           | 54        | 7.49%   |
| AMD Ryzen 5             | 50        | 6.93%   |
| AMD Ryzen 7             | 48        | 6.66%   |
| Intel Celeron           | 18        | 2.5%    |
| Intel Core 2 Duo        | 14        | 1.94%   |
| AMD Ryzen 9             | 14        | 1.94%   |
| Intel Atom              | 10        | 1.39%   |
| Intel Pentium           | 8         | 1.11%   |
| Intel Core i9           | 8         | 1.11%   |
| AMD Ryzen 3             | 8         | 1.11%   |
| AMD Ryzen 7 PRO         | 7         | 0.97%   |
| Intel Pentium Silver    | 5         | 0.69%   |
| AMD Ryzen 5 PRO         | 5         | 0.69%   |
| AMD A6                  | 4         | 0.55%   |
| AMD A4                  | 4         | 0.55%   |
| AMD A10                 | 4         | 0.55%   |
| AMD Athlon              | 3         | 0.42%   |
| AMD A8                  | 3         | 0.42%   |
| Intel Pentium Dual-Core | 2         | 0.28%   |
| Intel Pentium Dual      | 2         | 0.28%   |
| Intel Core m3           | 2         | 0.28%   |
| AMD E                   | 2         | 0.28%   |
| Intel Genuine           | 1         | 0.14%   |
| Intel Core m7           | 1         | 0.14%   |
| AMD PRO A10             | 1         | 0.14%   |
| AMD E2                  | 1         | 0.14%   |
| AMD E1                  | 1         | 0.14%   |
| AMD C-60                | 1         | 0.14%   |
| AMD Athlon II           | 1         | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 307       | 42.58%  |
| 2      | 255       | 35.37%  |
| 6      | 78        | 10.82%  |
| 8      | 75        | 10.4%   |
| 12     | 2         | 0.28%   |
| 1      | 2         | 0.28%   |
| 14     | 1         | 0.14%   |
| 10     | 1         | 0.14%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 721       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 610       | 84.6%   |
| 1      | 111       | 15.4%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 721       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806c1    | 67        | 9.22%   |
| 0x806ec    | 53        | 7.29%   |
| 0x306a9    | 41        | 5.64%   |
| 0x806ea    | 39        | 5.36%   |
| Unknown    | 38        | 5.23%   |
| 0x406e3    | 33        | 4.54%   |
| 0x806e9    | 32        | 4.4%    |
| 0xa0652    | 28        | 3.85%   |
| 0x40651    | 27        | 3.71%   |
| 0x08600106 | 26        | 3.58%   |
| 0x206a7    | 25        | 3.44%   |
| 0x0a50000c | 25        | 3.44%   |
| 0x906ea    | 24        | 3.3%    |
| 0x306d4    | 19        | 2.61%   |
| 0x08108109 | 17        | 2.34%   |
| 0x306c3    | 16        | 2.2%    |
| 0x706e5    | 14        | 1.93%   |
| 0x08600104 | 14        | 1.93%   |
| 0x08608103 | 13        | 1.79%   |
| 0x906ed    | 12        | 1.65%   |
| 0x506e3    | 11        | 1.51%   |
| 0x1067a    | 11        | 1.51%   |
| 0x08108102 | 11        | 1.51%   |
| 0x906e9    | 10        | 1.38%   |
| 0x506c9    | 9         | 1.24%   |
| 0x20655    | 8         | 1.1%    |
| 0x406c4    | 7         | 0.96%   |
| 0x08608102 | 7         | 0.96%   |
| 0x706a8    | 6         | 0.83%   |
| 0x30678    | 6         | 0.83%   |
| 0x806eb    | 5         | 0.69%   |
| 0x806d1    | 5         | 0.69%   |
| 0x06001119 | 5         | 0.69%   |
| 0x40661    | 4         | 0.55%   |
| 0x10676    | 4         | 0.55%   |
| 0x08600103 | 4         | 0.55%   |
| 0x0810100b | 3         | 0.41%   |
| 0x07030105 | 3         | 0.41%   |
| 0x0700010b | 3         | 0.41%   |
| 0xa0660    | 2         | 0.28%   |
| 0x906c0    | 2         | 0.28%   |
| 0x806c2    | 2         | 0.28%   |
| 0x706a1    | 2         | 0.28%   |
| 0x6fd      | 2         | 0.28%   |
| 0x406c3    | 2         | 0.28%   |
| 0x20652    | 2         | 0.28%   |
| 0x0a404101 | 2         | 0.28%   |
| 0x08701013 | 2         | 0.28%   |
| 0x08600102 | 2         | 0.28%   |
| 0x08101016 | 2         | 0.28%   |
| 0x07030106 | 2         | 0.28%   |
| 0x06006705 | 2         | 0.28%   |
| 0x0600611a | 2         | 0.28%   |
| 0x05000101 | 2         | 0.28%   |
| 0xa0655    | 1         | 0.14%   |
| 0x906eb    | 1         | 0.14%   |
| 0x906a3    | 1         | 0.14%   |
| 0x6fa      | 1         | 0.14%   |
| 0x106ca    | 1         | 0.14%   |
| 0x0a50000b | 1         | 0.14%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 181       | 25.1%   |
| TigerLake        | 72        | 9.99%   |
| Zen 2            | 50        | 6.93%   |
| Haswell          | 50        | 6.93%   |
| Skylake          | 49        | 6.8%    |
| IvyBridge        | 43        | 5.96%   |
| CometLake        | 34        | 4.72%   |
| Zen+             | 30        | 4.16%   |
| Zen 3            | 27        | 3.74%   |
| SandyBridge      | 27        | 3.74%   |
| Unknown          | 23        | 3.19%   |
| IceLake          | 19        | 2.64%   |
| Broadwell        | 19        | 2.64%   |
| Silvermont       | 16        | 2.22%   |
| Penryn           | 15        | 2.08%   |
| Westmere         | 11        | 1.53%   |
| Goldmont         | 9         | 1.25%   |
| Goldmont plus    | 8         | 1.11%   |
| Zen              | 7         | 0.97%   |
| Puma             | 5         | 0.69%   |
| Piledriver       | 5         | 0.69%   |
| Excavator        | 4         | 0.55%   |
| Core             | 4         | 0.55%   |
| Jaguar           | 3         | 0.42%   |
| Bobcat           | 3         | 0.42%   |
| Tremont          | 2         | 0.28%   |
| K10 Llano        | 2         | 0.28%   |
| K10              | 1         | 0.14%   |
| Bonnell          | 1         | 0.14%   |
| Alderlake Hybrid | 1         | 0.14%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 527       | 56.36%  |
| Nvidia                           | 219       | 23.42%  |
| AMD                              | 188       | 20.11%  |
| Silicon Integrated Systems [SiS] | 1         | 0.11%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 64        | 6.72%   |
| AMD Renoir                                                                               | 47        | 4.94%   |
| Intel UHD Graphics 620                                                                   | 41        | 4.31%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 39        | 4.1%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 34        | 3.57%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 31        | 3.26%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 31        | 3.26%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 30        | 3.15%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 29        | 3.05%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 29        | 3.05%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 28        | 2.94%   |
| Intel HD Graphics 620                                                                    | 26        | 2.73%   |
| AMD Cezanne                                                                              | 24        | 2.52%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 20        | 2.1%    |
| AMD Lucienne                                                                             | 20        | 2.1%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 17        | 1.79%   |
| Intel HD Graphics 5500                                                                   | 16        | 1.68%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 15        | 1.58%   |
| Intel HD Graphics 530                                                                    | 12        | 1.26%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 11        | 1.16%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 9         | 0.95%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 9         | 0.95%   |
| Intel HD Graphics 630                                                                    | 9         | 0.95%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 9         | 0.95%   |
| Nvidia TU117M                                                                            | 8         | 0.84%   |
| Nvidia GP108M [GeForce MX250]                                                            | 8         | 0.84%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 8         | 0.84%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 8         | 0.84%   |
| Intel Core Processor Integrated Graphics Controller                                      | 8         | 0.84%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 8         | 0.84%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 7         | 0.74%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 7         | 0.74%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 0.74%   |
| Intel HD Graphics 500                                                                    | 7         | 0.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 0.74%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 6         | 0.63%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 6         | 0.63%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 6         | 0.63%   |
| Intel Tiger Lake UHD Graphics                                                            | 6         | 0.63%   |
| Intel Iris Plus Graphics G7                                                              | 6         | 0.63%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 6         | 0.63%   |
| Nvidia GP108M [GeForce MX150]                                                            | 5         | 0.53%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 5         | 0.53%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 5         | 0.53%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 0.53%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                                     | 5         | 0.53%   |
| Nvidia GP108M [GeForce MX330]                                                            | 4         | 0.42%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 4         | 0.42%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                                  | 4         | 0.42%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 4         | 0.42%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 4         | 0.42%   |
| Intel HD Graphics 615                                                                    | 4         | 0.42%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 4         | 0.42%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 3         | 0.32%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 3         | 0.32%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 3         | 0.32%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 3         | 0.32%   |
| Nvidia GM108M [GeForce 840M]                                                             | 3         | 0.32%   |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 3         | 0.32%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 3         | 0.32%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 339       | 47.02%  |
| Intel + Nvidia | 164       | 22.75%  |
| 1 x AMD        | 124       | 17.2%   |
| 1 x Nvidia     | 29        | 4.02%   |
| AMD + Nvidia   | 26        | 3.61%   |
| Intel + AMD    | 22        | 3.05%   |
| 2 x AMD        | 15        | 2.08%   |
| Other          | 1         | 0.14%   |
| 1 x SiS        | 1         | 0.14%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 614       | 84.34%  |
| Proprietary | 108       | 14.84%  |
| Unknown     | 6         | 0.82%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 452       | 62.17%  |
| 0.01-0.5   | 95        | 13.07%  |
| 1.01-2.0   | 90        | 12.38%  |
| 0.51-1.0   | 32        | 4.4%    |
| 3.01-4.0   | 31        | 4.26%   |
| 7.01-8.0   | 11        | 1.51%   |
| 5.01-6.0   | 9         | 1.24%   |
| 8.01-16.0  | 5         | 0.69%   |
| 2.01-3.0   | 2         | 0.28%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 145       | 16.59%  |
| Chimei Innolux          | 137       | 15.68%  |
| BOE                     | 131       | 14.99%  |
| LG Display              | 116       | 13.27%  |
| Samsung Electronics     | 62        | 7.09%   |
| Sharp                   | 42        | 4.81%   |
| Dell                    | 37        | 4.23%   |
| Apple                   | 29        | 3.32%   |
| Goldstar                | 22        | 2.52%   |
| Lenovo                  | 20        | 2.29%   |
| Philips                 | 14        | 1.6%    |
| PANDA                   | 13        | 1.49%   |
| CSO                     | 13        | 1.49%   |
| InfoVision              | 11        | 1.26%   |
| Hewlett-Packard         | 11        | 1.26%   |
| Acer                    | 11        | 1.26%   |
| Chi Mei Optoelectronics | 9         | 1.03%   |
| BenQ                    | 9         | 1.03%   |
| AOC                     | 9         | 1.03%   |
| TMX                     | 5         | 0.57%   |
| Iiyama                  | 4         | 0.46%   |
| Ancor Communications    | 4         | 0.46%   |
| InnoLux Display         | 3         | 0.34%   |
| ASUSTek Computer        | 3         | 0.34%   |
| ViewSonic               | 2         | 0.23%   |
| Sony                    | 2         | 0.23%   |
| JRY                     | 2         | 0.23%   |
| TIANMA XM               | 1         | 0.11%   |
| Panasonic               | 1         | 0.11%   |
| MSI                     | 1         | 0.11%   |
| JDI                     | 1         | 0.11%   |
| HUAWEI                  | 1         | 0.11%   |
| Hitachi                 | 1         | 0.11%   |
| Gigabyte Technology     | 1         | 0.11%   |
| CPT                     | 1         | 0.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 13        | 1.46%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 7         | 0.78%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 6         | 0.67%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 6         | 0.67%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                  | 5         | 0.56%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 5         | 0.56%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                        | 5         | 0.56%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 5         | 0.56%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 5         | 0.56%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 5         | 0.56%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 5         | 0.56%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                    | 5         | 0.56%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                    | 5         | 0.56%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 5         | 0.56%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch           | 5         | 0.56%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch           | 5         | 0.56%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch             | 4         | 0.45%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 4         | 0.45%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 4         | 0.45%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 4         | 0.45%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch         | 4         | 0.45%   |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch         | 4         | 0.45%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 4         | 0.45%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                    | 4         | 0.45%   |
| BOE LCD Monitor BOE0853 1920x1080 344x194mm 15.5-inch                    | 4         | 0.45%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch           | 4         | 0.45%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch                  | 3         | 0.34%   |
| Sharp LQ156M1JW03 SHP155D 1920x1080 344x194mm 15.5-inch                  | 3         | 0.34%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch                  | 3         | 0.34%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 3         | 0.34%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 3         | 0.34%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 3         | 0.34%   |
| LG Display LCD Monitor LGD062C 1920x1080 309x174mm 14.0-inch             | 3         | 0.34%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch             | 3         | 0.34%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 3         | 0.34%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 3         | 0.34%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 3         | 0.34%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 3         | 0.34%   |
| Dell U2412M DELA079 1920x1200 518x324mm 24.1-inch                        | 3         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 3         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 3         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch         | 3         | 0.34%   |
| Chimei Innolux LCD Monitor CMN1515 1920x1080 344x193mm 15.5-inch         | 3         | 0.34%   |
| Chimei Innolux LCD Monitor CMN150C 1920x1080 344x193mm 15.5-inch         | 3         | 0.34%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                    | 3         | 0.34%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 3         | 0.34%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch           | 3         | 0.34%   |
| AU Optronics LCD Monitor AUO6496 1920x1200 286x178mm 13.3-inch           | 3         | 0.34%   |
| AU Optronics LCD Monitor AUO5A2D 1920x1080 293x165mm 13.2-inch           | 3         | 0.34%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch           | 3         | 0.34%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 3         | 0.34%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 3         | 0.34%   |
| AU Optronics LCD Monitor AUO2036 2560x1440 309x174mm 14.0-inch           | 3         | 0.34%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch           | 3         | 0.34%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 3         | 0.34%   |
| Apple Color LCD APPA034 2880x1800 286x179mm 13.3-inch                    | 3         | 0.34%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                     | 3         | 0.34%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                     | 3         | 0.34%   |
| TMX TL156MDMP01-1 TMX1560 3200x2000 336x210mm 15.6-inch                  | 2         | 0.22%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                  | 2         | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 426       | 52.53%  |
| 1366x768 (WXGA)    | 146       | 18%     |
| 3840x2160 (4K)     | 48        | 5.92%   |
| 2560x1440 (QHD)    | 40        | 4.93%   |
| 1920x1200 (WUXGA)  | 23        | 2.84%   |
| 1600x900 (HD+)     | 23        | 2.84%   |
| 2880x1800          | 12        | 1.48%   |
| 1440x900 (WXGA+)   | 12        | 1.48%   |
| 1280x800 (WXGA)    | 12        | 1.48%   |
| 2560x1600          | 11        | 1.36%   |
| 3440x1440          | 9         | 1.11%   |
| 3840x2400          | 6         | 0.74%   |
| 2160x1440          | 6         | 0.74%   |
| 2560x1080          | 5         | 0.62%   |
| 2256x1504          | 5         | 0.62%   |
| 1680x1050 (WSXGA+) | 5         | 0.62%   |
| 3200x2000          | 2         | 0.25%   |
| 3200x1800 (QHD+)   | 2         | 0.25%   |
| 3072x1920          | 2         | 0.25%   |
| 3000x2000          | 2         | 0.25%   |
| 2880x1920          | 2         | 0.25%   |
| 2240x1400          | 2         | 0.25%   |
| 2160x1350          | 2         | 0.25%   |
| 1280x1024 (SXGA)   | 2         | 0.25%   |
| 3840x2560          | 1         | 0.12%   |
| 3840x1600          | 1         | 0.12%   |
| 2736x1824          | 1         | 0.12%   |
| 1360x768           | 1         | 0.12%   |
| 1024x600           | 1         | 0.12%   |
| Unknown            | 1         | 0.12%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 311       | 35.26%  |
| 13      | 168       | 19.05%  |
| 14      | 132       | 14.97%  |
| 27      | 42        | 4.76%   |
| 24      | 41        | 4.65%   |
| 17      | 37        | 4.2%    |
| 23      | 25        | 2.83%   |
| 12      | 25        | 2.83%   |
| 21      | 23        | 2.61%   |
| 34      | 12        | 1.36%   |
| 16      | 12        | 1.36%   |
| 11      | 12        | 1.36%   |
| 40      | 5         | 0.57%   |
| 31      | 5         | 0.57%   |
| 19      | 4         | 0.45%   |
| 18      | 4         | 0.45%   |
| 84      | 3         | 0.34%   |
| 22      | 3         | 0.34%   |
| 10      | 3         | 0.34%   |
| 35      | 2         | 0.23%   |
| 28      | 2         | 0.23%   |
| 26      | 2         | 0.23%   |
| 20      | 2         | 0.23%   |
| Unknown | 2         | 0.23%   |
| 54      | 1         | 0.11%   |
| 43      | 1         | 0.11%   |
| 37      | 1         | 0.11%   |
| 29      | 1         | 0.11%   |
| 25      | 1         | 0.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 534       | 61.1%   |
| 201-300     | 122       | 13.96%  |
| 501-600     | 99        | 11.33%  |
| 351-400     | 45        | 5.15%   |
| 401-500     | 33        | 3.78%   |
| 601-700     | 14        | 1.6%    |
| 701-800     | 12        | 1.37%   |
| 801-900     | 8         | 0.92%   |
| 1501-2000   | 3         | 0.34%   |
| Unknown     | 2         | 0.23%   |
| 1001-1500   | 1         | 0.11%   |
| 901-1000    | 1         | 0.11%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 618       | 82.84%  |
| 16/10   | 92        | 12.33%  |
| 3/2     | 18        | 2.41%   |
| 21/9    | 15        | 2.01%   |
| 5/4     | 2         | 0.27%   |
| Unknown | 1         | 0.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 315       | 35.71%  |
| 81-90          | 236       | 26.76%  |
| 201-250        | 77        | 8.73%   |
| 71-80          | 65        | 7.37%   |
| 301-350        | 43        | 4.88%   |
| 121-130        | 36        | 4.08%   |
| 61-70          | 24        | 2.72%   |
| 351-500        | 22        | 2.49%   |
| 251-300        | 14        | 1.59%   |
| 51-60          | 12        | 1.36%   |
| 151-200        | 11        | 1.25%   |
| 111-120        | 8         | 0.91%   |
| 501-1000       | 7         | 0.79%   |
| More than 1000 | 4         | 0.45%   |
| 41-50          | 3         | 0.34%   |
| 141-150        | 2         | 0.23%   |
| Unknown        | 2         | 0.23%   |
| 131-140        | 1         | 0.11%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 413       | 48.3%   |
| 101-120       | 172       | 20.12%  |
| 51-100        | 117       | 13.68%  |
| 161-240       | 107       | 12.51%  |
| More than 240 | 43        | 5.03%   |
| Unknown       | 2         | 0.23%   |
| 1-50          | 1         | 0.12%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 546       | 74.9%   |
| 2     | 148       | 20.3%   |
| 3     | 21        | 2.88%   |
| 0     | 14        | 1.92%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 430       | 39.2%   |
| Realtek Semiconductor             | 357       | 32.54%  |
| Qualcomm Atheros                  | 117       | 10.67%  |
| Broadcom                          | 52        | 4.74%   |
| MEDIATEK                          | 25        | 2.28%   |
| Lenovo                            | 15        | 1.37%   |
| Broadcom Limited                  | 12        | 1.09%   |
| Ralink                            | 10        | 0.91%   |
| Sierra Wireless                   | 7         | 0.64%   |
| TP-Link                           | 6         | 0.55%   |
| Qualcomm                          | 6         | 0.55%   |
| Marvell Technology Group          | 6         | 0.55%   |
| DisplayLink                       | 6         | 0.55%   |
| Dell                              | 6         | 0.55%   |
| ASIX Electronics                  | 5         | 0.46%   |
| Xiaomi                            | 4         | 0.36%   |
| Ralink Technology                 | 4         | 0.36%   |
| Nvidia                            | 4         | 0.36%   |
| ASUSTek Computer                  | 3         | 0.27%   |
| OPPO Electronics                  | 2         | 0.18%   |
| Linksys                           | 2         | 0.18%   |
| Hewlett-Packard                   | 2         | 0.18%   |
| FIBOCOM                           | 2         | 0.18%   |
| Ericsson Business Mobile Networks | 2         | 0.18%   |
| Cypress Semiconductor             | 2         | 0.18%   |
| Spreadtrum Communications         | 1         | 0.09%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.09%   |
| Shenzhen Goodix Technology        | 1         | 0.09%   |
| Samsung Electronics               | 1         | 0.09%   |
| Qualcomm Atheros Communications   | 1         | 0.09%   |
| NetGear                           | 1         | 0.09%   |
| Huawei Technologies               | 1         | 0.09%   |
| HMD Global                        | 1         | 0.09%   |
| D-Link                            | 1         | 0.09%   |
| Apple                             | 1         | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 217       | 16.41%  |
| Intel Wi-Fi 6 AX200                                               | 70        | 5.3%    |
| Intel Wi-Fi 6 AX201                                               | 52        | 3.93%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 48        | 3.63%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 45        | 3.4%    |
| Intel Wireless 8265 / 8275                                        | 42        | 3.18%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 28        | 2.12%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 28        | 2.12%   |
| Intel Wireless 8260                                               | 27        | 2.04%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 26        | 1.97%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 25        | 1.89%   |
| Intel Wireless 7260                                               | 24        | 1.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 23        | 1.74%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 22        | 1.66%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 20        | 1.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 20        | 1.51%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 19        | 1.44%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter     | 18        | 1.36%   |
| Intel Wireless 7265                                               | 18        | 1.36%   |
| Intel Ethernet Connection (4) I219-LM                             | 15        | 1.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 13        | 0.98%   |
| Intel Wireless 3165                                               | 13        | 0.98%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 13        | 0.98%   |
| Intel Wireless-AC 9260                                            | 12        | 0.91%   |
| Intel Ethernet Connection I219-LM                                 | 12        | 0.91%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 12        | 0.91%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 11        | 0.83%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 11        | 0.83%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 11        | 0.83%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 10        | 0.76%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 10        | 0.76%   |
| Intel Ethernet Connection I218-LM                                 | 10        | 0.76%   |
| Intel Ethernet Connection (4) I219-V                              | 10        | 0.76%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 9         | 0.68%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 9         | 0.68%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 9         | 0.68%   |
| Intel Ethernet Connection (6) I219-V                              | 9         | 0.68%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 8         | 0.61%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 7         | 0.53%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 7         | 0.53%   |
| Intel Ethernet Connection (7) I219-LM                             | 7         | 0.53%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 6         | 0.45%   |
| Intel Ethernet Connection I219-V                                  | 6         | 0.45%   |
| Intel Ethernet Connection (6) I219-LM                             | 6         | 0.45%   |
| Intel Ethernet Connection (13) I219-V                             | 6         | 0.45%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 6         | 0.45%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 6         | 0.45%   |
| Broadcom BCM43142 802.11b/g/n                                     | 6         | 0.45%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 5         | 0.38%   |
| Qualcomm QCA6390 Wireless Network Adapter [AX500-DBS (2x2)]       | 5         | 0.38%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 5         | 0.38%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 0.38%   |
| Intel Ethernet Connection (2) I219-LM                             | 5         | 0.38%   |
| Intel Ethernet Connection (10) I219-V                             | 5         | 0.38%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 5         | 0.38%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 5         | 0.38%   |
| ASIX AX88179 Gigabit Ethernet                                     | 5         | 0.38%   |
| Realtek 802.11ac NIC                                              | 4         | 0.3%    |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 4         | 0.3%    |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 0.3%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 422       | 56.57%  |
| Qualcomm Atheros                | 105       | 14.08%  |
| Realtek Semiconductor           | 96        | 12.87%  |
| Broadcom                        | 45        | 6.03%   |
| MEDIATEK                        | 24        | 3.22%   |
| Ralink                          | 10        | 1.34%   |
| Broadcom Limited                | 10        | 1.34%   |
| Sierra Wireless                 | 7         | 0.94%   |
| Qualcomm                        | 5         | 0.67%   |
| TP-Link                         | 4         | 0.54%   |
| Ralink Technology               | 4         | 0.54%   |
| Dell                            | 4         | 0.54%   |
| ASUSTek Computer                | 3         | 0.4%    |
| FIBOCOM                         | 2         | 0.27%   |
| Qualcomm Atheros Communications | 1         | 0.13%   |
| NetGear                         | 1         | 0.13%   |
| Linksys                         | 1         | 0.13%   |
| Hewlett-Packard                 | 1         | 0.13%   |
| D-Link                          | 1         | 0.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 70        | 9.36%   |
| Intel Wi-Fi 6 AX201                                            | 52        | 6.95%   |
| Intel Wireless 8265 / 8275                                     | 42        | 5.61%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 28        | 3.74%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 28        | 3.74%   |
| Intel Wireless 8260                                            | 27        | 3.61%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 26        | 3.48%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 25        | 3.34%   |
| Intel Wireless 7260                                            | 24        | 3.21%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 23        | 3.07%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 22        | 2.94%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 20        | 2.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 19        | 2.54%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter  | 18        | 2.41%   |
| Intel Wireless 7265                                            | 18        | 2.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 13        | 1.74%   |
| Intel Wireless 3165                                            | 13        | 1.74%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 13        | 1.74%   |
| Intel Wireless-AC 9260                                         | 12        | 1.6%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 12        | 1.6%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 11        | 1.47%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 11        | 1.47%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 11        | 1.47%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 10        | 1.34%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 10        | 1.34%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 9         | 1.2%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 9         | 1.2%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 9         | 1.2%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 7         | 0.94%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 6         | 0.8%    |
| Broadcom BCM43224 802.11a/b/g/n                                | 6         | 0.8%    |
| Broadcom BCM43142 802.11b/g/n                                  | 6         | 0.8%    |
| Realtek RTL8188EE Wireless Network Adapter                     | 5         | 0.67%   |
| Qualcomm QCA6390 Wireless Network Adapter [AX500-DBS (2x2)]    | 5         | 0.67%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 5         | 0.67%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 5         | 0.67%   |
| Realtek 802.11ac NIC                                           | 4         | 0.53%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 4         | 0.53%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 4         | 0.53%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 3         | 0.4%    |
| Intel Centrino Wireless-N 2230                                 | 3         | 0.4%    |
| Intel Centrino Ultimate-N 6300                                 | 3         | 0.4%    |
| Dell DW5811e Snapdragonâ¢ X7 LTE                           | 3         | 0.4%    |
| Broadcom BCM4350 802.11ac Wireless Network Adapter             | 3         | 0.4%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 3         | 0.4%    |
| TP-Link 802.11ac NIC                                           | 2         | 0.27%   |
| Sierra Wireless EM7455                                         | 2         | 0.27%   |
| Sierra Wireless EM7345 4G LTE                                  | 2         | 0.27%   |
| Sierra Wireless EM7305                                         | 2         | 0.27%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 2         | 0.27%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 2         | 0.27%   |
| Ralink RT5370 Wireless Adapter                                 | 2         | 0.27%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 0.27%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 2         | 0.27%   |
| MEDIATEK WLAN controller                                       | 2         | 0.27%   |
| MEDIATEK RZ608 Wi-Fi 6E 80MHz                                  | 2         | 0.27%   |
| MEDIATEK MT7630e 802.11bgn Wireless Network Adapter            | 2         | 0.27%   |
| Intel Wireless 3160                                            | 2         | 0.27%   |
| Intel WiFi Link 5100                                           | 2         | 0.27%   |
| Intel Wi-Fi 6 AX201 160MHz                                     | 2         | 0.27%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 315       | 57.07%  |
| Intel                            | 142       | 25.72%  |
| Qualcomm Atheros                 | 23        | 4.17%   |
| Broadcom                         | 16        | 2.9%    |
| Lenovo                           | 15        | 2.72%   |
| Marvell Technology Group         | 6         | 1.09%   |
| DisplayLink                      | 6         | 1.09%   |
| ASIX Electronics                 | 5         | 0.91%   |
| Xiaomi                           | 4         | 0.72%   |
| Nvidia                           | 4         | 0.72%   |
| TP-Link                          | 2         | 0.36%   |
| OPPO Electronics                 | 2         | 0.36%   |
| Cypress Semiconductor            | 2         | 0.36%   |
| Broadcom Limited                 | 2         | 0.36%   |
| Spreadtrum Communications        | 1         | 0.18%   |
| Silicon Integrated Systems [SiS] | 1         | 0.18%   |
| Samsung Electronics              | 1         | 0.18%   |
| Qualcomm                         | 1         | 0.18%   |
| MediaTek                         | 1         | 0.18%   |
| Linksys                          | 1         | 0.18%   |
| HMD Global                       | 1         | 0.18%   |
| Apple                            | 1         | 0.18%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 217       | 38.27%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 48        | 8.47%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 45        | 7.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 20        | 3.53%   |
| Intel Ethernet Connection (4) I219-LM                                          | 15        | 2.65%   |
| Intel Ethernet Connection I219-LM                                              | 12        | 2.12%   |
| Intel Ethernet Connection I218-LM                                              | 10        | 1.76%   |
| Intel Ethernet Connection (4) I219-V                                           | 10        | 1.76%   |
| Intel Ethernet Connection (6) I219-V                                           | 9         | 1.59%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 8         | 1.41%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 7         | 1.23%   |
| Intel Ethernet Connection (7) I219-LM                                          | 7         | 1.23%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 6         | 1.06%   |
| Intel Ethernet Connection I219-V                                               | 6         | 1.06%   |
| Intel Ethernet Connection (6) I219-LM                                          | 6         | 1.06%   |
| Intel Ethernet Connection (13) I219-V                                          | 6         | 1.06%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 5         | 0.88%   |
| Intel Ethernet Connection I217-LM                                              | 5         | 0.88%   |
| Intel Ethernet Connection (2) I219-LM                                          | 5         | 0.88%   |
| Intel Ethernet Connection (10) I219-V                                          | 5         | 0.88%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 5         | 0.88%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 4         | 0.71%   |
| Intel Ethernet Connection (3) I218-LM                                          | 4         | 0.71%   |
| Intel Ethernet Connection (11) I219-LM                                         | 4         | 0.71%   |
| Intel Ethernet Connection (10) I219-LM                                         | 4         | 0.71%   |
| DisplayLink Dell Universal Dock D6000                                          | 4         | 0.71%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 4         | 0.71%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 4         | 0.71%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 4         | 0.71%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 3         | 0.53%   |
| Realtek RTL8125 2.5GbE Controller                                              | 3         | 0.53%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 3         | 0.53%   |
| Nvidia MCP79 Ethernet                                                          | 3         | 0.53%   |
| Intel Ethernet Connection (13) I219-LM                                         | 3         | 0.53%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 2         | 0.35%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                               | 2         | 0.35%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 0.35%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 2         | 0.35%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 2         | 0.35%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2         | 0.35%   |
| OPPO SDM665-IDP _SN:18689828                                                   | 2         | 0.35%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.35%   |
| Lenovo USB-C Dock Ethernet                                                     | 2         | 0.35%   |
| Lenovo ThinkPad TBT3 LAN                                                       | 2         | 0.35%   |
| Intel Ethernet Connection I217-V                                               | 2         | 0.35%   |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 0.35%   |
| Intel 82567LM Gigabit Network Connection                                       | 2         | 0.35%   |
| Cypress K38231_03                                                              | 2         | 0.35%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.18%   |
| TP-Link USB 10/100 LAN                                                         | 1         | 0.18%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 0.18%   |
| Spreadtrum Unisoc Phone                                                        | 1         | 0.18%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 1         | 0.18%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.18%   |
| Qualcomm Redmi Note 7                                                          | 1         | 0.18%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.18%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.18%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.18%   |
| Nvidia MCP89 Ethernet                                                          | 1         | 0.18%   |
| MediaTek U FEEL                                                                | 1         | 0.18%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 710       | 57.4%   |
| Ethernet | 520       | 42.04%  |
| Modem    | 6         | 0.49%   |
| Unknown  | 1         | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 654       | 69.28%  |
| Ethernet | 290       | 30.72%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 457       | 63.3%   |
| 1     | 244       | 33.8%   |
| 0     | 13        | 1.8%    |
| 3     | 8         | 1.11%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 553       | 75.96%  |
| Yes  | 175       | 24.04%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 362       | 58.67%  |
| Realtek Semiconductor           | 59        | 9.56%   |
| Qualcomm Atheros Communications | 45        | 7.29%   |
| Lite-On Technology              | 27        | 4.38%   |
| IMC Networks                    | 24        | 3.89%   |
| Apple                           | 24        | 3.89%   |
| Foxconn / Hon Hai               | 19        | 3.08%   |
| Broadcom                        | 16        | 2.59%   |
| Realtek                         | 13        | 2.11%   |
| Ralink                          | 9         | 1.46%   |
| Cambridge Silicon Radio         | 6         | 0.97%   |
| Dell                            | 3         | 0.49%   |
| ASUSTek Computer                | 3         | 0.49%   |
| MediaTek                        | 2         | 0.32%   |
| Hewlett-Packard                 | 2         | 0.32%   |
| Foxconn International           | 2         | 0.32%   |
| Alps Electric                   | 1         | 0.16%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                                                              | 182       | 29.5%   |
| Intel Bluetooth wireless interface                                                  | 78        | 12.64%  |
| Intel AX200 Bluetooth                                                               | 68        | 11.02%  |
| Realtek Bluetooth Radio                                                             | 47        | 7.62%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 26        | 4.21%   |
| Apple Bluetooth Host Controller                                                     | 16        | 2.59%   |
| Realtek 802.11ac WLAN Adapter                                                       | 12        | 1.94%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 11        | 1.78%   |
| IMC Networks Wireless_Device                                                        | 11        | 1.78%   |
| Ralink RT3290 Bluetooth                                                             | 9         | 1.46%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 9         | 1.46%   |
| Intel AX210 Bluetooth                                                               | 9         | 1.46%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 7         | 1.13%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 7         | 1.13%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 7         | 1.13%   |
| Apple Bluetooth USB Host Controller                                                 | 7         | 1.13%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 6         | 0.97%   |
| Lite-On Bluetooth Device                                                            | 6         | 0.97%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 6         | 0.97%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 6         | 0.97%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 5         | 0.81%   |
| IMC Networks Bluetooth Radio                                                        | 5         | 0.81%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 5         | 0.81%   |
| Lite-On Wireless_Device                                                             | 4         | 0.65%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 4         | 0.65%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 4         | 0.65%   |
| Realtek RTL8723B Bluetooth                                                          | 3         | 0.49%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 0.49%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 3         | 0.49%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 3         | 0.49%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 0.32%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 2         | 0.32%   |
| MediaTek Wireless_Device                                                            | 2         | 0.32%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 2         | 0.32%   |
| IMC Networks Bluetooth Device                                                       | 2         | 0.32%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 2         | 0.32%   |
| Foxconn / Hon Hai BT                                                                | 2         | 0.32%   |
| Dell BCM20702A0                                                                     | 2         | 0.32%   |
| Broadcom HP Portable SoftSailing                                                    | 2         | 0.32%   |
| Broadcom HP Portable Bumble Bee                                                     | 2         | 0.32%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 2         | 0.32%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.16%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.16%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.16%   |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 1         | 0.16%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 1         | 0.16%   |
| Lite-On Atheros Bluetooth                                                           | 1         | 0.16%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.16%   |
| IMC Networks Bluetooth USB Host Controller                                          | 1         | 0.16%   |
| IMC Networks Bluetooth                                                              | 1         | 0.16%   |
| IMC Networks Atheros AR3012 Bluetooth                                               | 1         | 0.16%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.16%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.16%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.16%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 1         | 0.16%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth                                       | 1         | 0.16%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.16%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 1         | 0.16%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 1         | 0.16%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 1         | 0.16%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 543       | 57.34%  |
| AMD                              | 171       | 18.06%  |
| Nvidia                           | 128       | 13.52%  |
| C-Media Electronics              | 16        | 1.69%   |
| Lenovo                           | 14        | 1.48%   |
| GN Netcom                        | 9         | 0.95%   |
| Realtek Semiconductor            | 7         | 0.74%   |
| Plantronics                      | 4         | 0.42%   |
| Logitech                         | 4         | 0.42%   |
| Kingston Technology              | 4         | 0.42%   |
| Hewlett-Packard                  | 4         | 0.42%   |
| Texas Instruments                | 3         | 0.32%   |
| SteelSeries ApS                  | 3         | 0.32%   |
| JMTek                            | 3         | 0.32%   |
| Creative Technology              | 3         | 0.32%   |
| XMOS                             | 2         | 0.21%   |
| Sennheiser Communications        | 2         | 0.21%   |
| Razer USA                        | 2         | 0.21%   |
| PreSonus Audio Electronics       | 2         | 0.21%   |
| CMX Systems                      | 2         | 0.21%   |
| Apple                            | 2         | 0.21%   |
| Tenx Technology                  | 1         | 0.11%   |
| Sony                             | 1         | 0.11%   |
| Silicon Integrated Systems [SiS] | 1         | 0.11%   |
| SAVITECH                         | 1         | 0.11%   |
| Samson Technologies              | 1         | 0.11%   |
| Micronas                         | 1         | 0.11%   |
| Magic Control Technology         | 1         | 0.11%   |
| M-Audio                          | 1         | 0.11%   |
| GYROCOM C&C                      | 1         | 0.11%   |
| Fujitsu                          | 1         | 0.11%   |
| FIFINE Microphones               | 1         | 0.11%   |
| EDFIER                           | 1         | 0.11%   |
| Corsair                          | 1         | 0.11%   |
| Cooler Master                    | 1         | 0.11%   |
| Conexant Systems                 | 1         | 0.11%   |
| BY EDIFIER                       | 1         | 0.11%   |
| Barco Display Systems            | 1         | 0.11%   |
| Arturia                          | 1         | 0.11%   |
| A4Tech                           | 1         | 0.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 126       | 10.99%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 110       | 9.59%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 78        | 6.8%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 72        | 6.28%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 46        | 4.01%   |
| Intel Cannon Lake PCH cAVS                                                                        | 36        | 3.14%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 34        | 2.96%   |
| Intel Comet Lake PCH cAVS                                                                         | 32        | 2.79%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 31        | 2.7%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 30        | 2.62%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 29        | 2.53%   |
| Intel 8 Series HD Audio Controller                                                                | 29        | 2.53%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 24        | 2.09%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 22        | 1.92%   |
| Nvidia Audio device                                                                               | 21        | 1.83%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 21        | 1.83%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 19        | 1.66%   |
| Intel Broadwell-U Audio Controller                                                                | 19        | 1.66%   |
| AMD FCH Azalia Controller                                                                         | 16        | 1.39%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 14        | 1.22%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 14        | 1.22%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 14        | 1.22%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 13        | 1.13%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 12        | 1.05%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                                      | 10        | 0.87%   |
| Intel CM238 HD Audio Controller                                                                   | 10        | 0.87%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 10        | 0.87%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 10        | 0.87%   |
| AMD Kabini HDMI/DP Audio                                                                          | 10        | 0.87%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 9         | 0.78%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 9         | 0.78%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 8         | 0.7%    |
| Realtek Semiconductor USB Audio                                                                   | 7         | 0.61%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 7         | 0.61%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 7         | 0.61%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 6         | 0.52%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 6         | 0.52%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 6         | 0.52%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5         | 0.44%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 5         | 0.44%   |
| AMD Trinity HDMI Audio Controller                                                                 | 5         | 0.44%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 4         | 0.35%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 0.35%   |
| Hewlett-Packard USB Audio                                                                         | 4         | 0.35%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 0.35%   |
| Texas Instruments PCM2912A Audio Codec                                                            | 3         | 0.26%   |
| Nvidia TU104 HD Audio Controller                                                                  | 3         | 0.26%   |
| Nvidia MCP89 High Definition Audio                                                                | 3         | 0.26%   |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 0.26%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.26%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 3         | 0.26%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 3         | 0.26%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 0.26%   |
| JMTek USB PnP Audio Device                                                                        | 3         | 0.26%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 0.26%   |
| C-Media Electronics Blue Snowball                                                                 | 3         | 0.26%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 0.26%   |
| SteelSeries ApS SteelSeries Arctis 7                                                              | 2         | 0.17%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.17%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.17%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 149       | 31.7%   |
| SK Hynix            | 98        | 20.85%  |
| Micron Technology   | 72        | 15.32%  |
| Kingston            | 37        | 7.87%   |
| Crucial             | 32        | 6.81%   |
| Unknown             | 22        | 4.68%   |
| Ramaxel Technology  | 10        | 2.13%   |
| A-DATA Technology   | 9         | 1.91%   |
| Team                | 5         | 1.06%   |
| Elpida              | 5         | 1.06%   |
| Smart               | 4         | 0.85%   |
| Corsair             | 4         | 0.85%   |
| SMART Brazil        | 3         | 0.64%   |
| Avant               | 3         | 0.64%   |
| Unknown (ABCD)      | 2         | 0.43%   |
| Transcend           | 2         | 0.43%   |
| Nanya Technology    | 2         | 0.43%   |
| Goldkey             | 2         | 0.43%   |
| Qimonda             | 1         | 0.21%   |
| PUSKILL             | 1         | 0.21%   |
| Patriot             | 1         | 0.21%   |
| Miron               | 1         | 0.21%   |
| GOODRAM             | 1         | 0.21%   |
| G.Skill             | 1         | 0.21%   |
| fef5                | 1         | 0.21%   |
| ASint Technology    | 1         | 0.21%   |
| AMD                 | 1         | 0.21%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 2.01%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 2.01%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 8         | 1.61%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 7         | 1.41%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 6         | 1.2%    |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 6         | 1.2%    |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 1%      |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 5         | 1%      |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 1%      |
| Samsung RAM M471A1K43DB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 5         | 1%      |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 1%      |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 5         | 1%      |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 5         | 1%      |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 5         | 1%      |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 4         | 0.8%    |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.8%    |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 0.8%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 0.8%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.8%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.8%    |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 4         | 0.8%    |
| Samsung RAM M471A2K43DB1-CWE 16384MB SODIMM DDR4 3200MT/s        | 4         | 0.8%    |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 4         | 0.8%    |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.8%    |
| Micron RAM 4ATF51264HZ-3G2J1 4096MB SODIMM DDR4 3200MT/s         | 4         | 0.8%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 4         | 0.8%    |
| Crucial RAM CT51264BF160BJ.C8F 4096MB SODIMM DDR3 1600MT/s       | 4         | 0.8%    |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 3         | 0.6%    |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 3         | 0.6%    |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 3         | 0.6%    |
| Samsung RAM Module 8GB SODIMM DDR4 3200MT/s                      | 3         | 0.6%    |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 3         | 0.6%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.6%    |
| Samsung RAM M471A5244CB0-CWE 4096MB Row Of Chips DDR4 3200MT/s   | 3         | 0.6%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 3         | 0.6%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.6%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.6%    |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 3         | 0.6%    |
| Kingston RAM 99U5428-018.A00LF 8192MB SODIMM DDR3 1600MT/s       | 3         | 0.6%    |
| Crucial RAM CT16G4SFRA32A.M16FRS 16GB SODIMM DDR4 3200MT/s       | 3         | 0.6%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 0.4%    |
| Team RAM TEAMGROUP-SD4-3200 32GB SODIMM DDR4 3200MT/s            | 2         | 0.4%    |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s             | 2         | 0.4%    |
| SMART Brazil RAM SMS4TDC3C0K0446SCG 4096MB SODIMM DDR4 2667MT/s  | 2         | 0.4%    |
| SK Hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s             | 2         | 0.4%    |
| SK Hynix RAM Module 4GB SODIMM DDR3 1066MT/s                     | 2         | 0.4%    |
| SK Hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s          | 2         | 0.4%    |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.4%    |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 2         | 0.4%    |
| SK Hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 0.4%    |
| SK Hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.4%    |
| SK Hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 2         | 0.4%    |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 2         | 0.4%    |
| SK Hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s       | 2         | 0.4%    |
| Samsung RAM U6E3S4AA-MGCR 1GB Row Of Chips LPDDR4 4267MT/s       | 2         | 0.4%    |
| Samsung RAM Module 8GB SODIMM DDR4 2667MT/s                      | 2         | 0.4%    |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s                      | 2         | 0.4%    |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 2         | 0.4%    |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 2133MT/s              | 2         | 0.4%    |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 2         | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 225       | 56.96%  |
| DDR3    | 95        | 24.05%  |
| LPDDR4  | 35        | 8.86%   |
| LPDDR3  | 28        | 7.09%   |
| DDR2    | 6         | 1.52%   |
| Unknown | 4         | 1.01%   |
| SDRAM   | 2         | 0.51%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 325       | 79.85%  |
| Row Of Chips | 73        | 17.94%  |
| Chip         | 5         | 1.23%   |
| DIMM         | 2         | 0.49%   |
| Unknown      | 2         | 0.49%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 184       | 43.09%  |
| 4096  | 122       | 28.57%  |
| 16384 | 70        | 16.39%  |
| 2048  | 32        | 7.49%   |
| 32768 | 14        | 3.28%   |
| 1024  | 5         | 1.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 102       | 24.29%  |
| 2667    | 100       | 23.81%  |
| 1600    | 66        | 15.71%  |
| 2400    | 30        | 7.14%   |
| 2133    | 28        | 6.67%   |
| 4267    | 19        | 4.52%   |
| 1867    | 12        | 2.86%   |
| 1334    | 9         | 2.14%   |
| 1333    | 8         | 1.9%    |
| 1067    | 8         | 1.9%    |
| 3266    | 6         | 1.43%   |
| 1066    | 6         | 1.43%   |
| 4266    | 5         | 1.19%   |
| 3733    | 5         | 1.19%   |
| 667     | 4         | 0.95%   |
| 4800    | 2         | 0.48%   |
| 4199    | 2         | 0.48%   |
| 2933    | 2         | 0.48%   |
| 800     | 2         | 0.48%   |
| 8400    | 1         | 0.24%   |
| 1866    | 1         | 0.24%   |
| 975     | 1         | 0.24%   |
| Unknown | 1         | 0.24%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 2         | 40%     |
| Prolific Technology | 1         | 20%     |
| Hewlett-Packard     | 1         | 20%     |
| Canon               | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Samsung SCX-3200 Series         | 1         | 20%     |
| Samsung CLX-6260 Series         | 1         | 20%     |
| Prolific PL2305 Parallel Port   | 1         | 20%     |
| HP LaserJet 400 colorMFP M475dw | 1         | 20%     |
| Canon TR8500 series             | 1         | 20%     |

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


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 220 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 156       | 22.54%  |
| IMC Networks                           | 79        | 11.42%  |
| Acer                                   | 69        | 9.97%   |
| Microdia                               | 63        | 9.1%    |
| Realtek Semiconductor                  | 60        | 8.67%   |
| Quanta                                 | 49        | 7.08%   |
| Sunplus Innovation Technology          | 32        | 4.62%   |
| Cheng Uei Precision Industry (Foxlink) | 28        | 4.05%   |
| Logitech                               | 23        | 3.32%   |
| Syntek                                 | 21        | 3.03%   |
| Lite-On Technology                     | 20        | 2.89%   |
| Apple                                  | 17        | 2.46%   |
| Suyin                                  | 13        | 1.88%   |
| Luxvisions Innotech Limited            | 12        | 1.73%   |
| Samsung Electronics                    | 7         | 1.01%   |
| Silicon Motion                         | 6         | 0.87%   |
| Ricoh                                  | 4         | 0.58%   |
| Alcor Micro                            | 4         | 0.58%   |
| Lenovo                                 | 3         | 0.43%   |
| ARC International                      | 3         | 0.43%   |
| Primax Electronics                     | 2         | 0.29%   |
| Microsoft                              | 2         | 0.29%   |
| Importek                               | 2         | 0.29%   |
| WaveRider Communications               | 1         | 0.14%   |
| USB Camera                             | 1         | 0.14%   |
| Tobii Technology AB                    | 1         | 0.14%   |
| SunplusIT                              | 1         | 0.14%   |
| Sonix Technology                       | 1         | 0.14%   |
| Razer USA                              | 1         | 0.14%   |
| Pixart Imaging                         | 1         | 0.14%   |
| Omnivision                             | 1         | 0.14%   |
| MacroSilicon                           | 1         | 0.14%   |
| HD 2MP WEBCAM                          | 1         | 0.14%   |
| Generalplus Technology                 | 1         | 0.14%   |
| Foxconn / Hon Hai                      | 1         | 0.14%   |
| DLUPCA1UIFGOTE                         | 1         | 0.14%   |
| DigiTech                               | 1         | 0.14%   |
| Creative Technology                    | 1         | 0.14%   |
| ANYKA                                  | 1         | 0.14%   |
| ALi                                    | 1         | 0.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 53        | 7.61%   |
| Microdia Integrated_Webcam_HD                                   | 41        | 5.89%   |
| IMC Networks Integrated Camera                                  | 36        | 5.17%   |
| Acer Integrated Camera                                          | 30        | 4.31%   |
| Realtek Integrated_Webcam_HD                                    | 23        | 3.3%    |
| Sunplus Integrated_Webcam_HD                                    | 19        | 2.73%   |
| Syntek Integrated Camera                                        | 17        | 2.44%   |
| Quanta HD User Facing                                           | 17        | 2.44%   |
| Chicony HD Webcam                                               | 16        | 2.3%    |
| IMC Networks USB2.0 HD UVC WebCam                               | 12        | 1.72%   |
| Quanta HP TrueVision HD Camera                                  | 10        | 1.44%   |
| Chicony Integrated Camera (1280x720@30)                         | 10        | 1.44%   |
| Lite-On HP HD Camera                                            | 9         | 1.29%   |
| Microdia Integrated Webcam                                      | 8         | 1.15%   |
| IMC Networks HD Camera                                          | 8         | 1.15%   |
| Apple Built-in iSight                                           | 8         | 1.15%   |
| Samsung Galaxy A5 (MTP)                                         | 7         | 1.01%   |
| Chicony USB2.0 Camera                                           | 7         | 1.01%   |
| Logitech Webcam C270                                            | 6         | 0.86%   |
| Logitech HD Pro Webcam C920                                     | 6         | 0.86%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 6         | 0.86%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                | 6         | 0.86%   |
| Acer SunplusIT Integrated Camera                                | 6         | 0.86%   |
| Acer HD Webcam                                                  | 6         | 0.86%   |
| Acer BisonCam,NB Pro                                            | 6         | 0.86%   |
| Realtek USB Camera                                              | 5         | 0.72%   |
| Realtek Integrated Webcam HD                                    | 5         | 0.72%   |
| Quanta HP HD Camera                                             | 5         | 0.72%   |
| Logitech C922 Pro Stream Webcam                                 | 5         | 0.72%   |
| Lite-On Integrated Camera                                       | 5         | 0.72%   |
| Chicony HP HD Camera                                            | 5         | 0.72%   |
| Chicony HD User Facing                                          | 5         | 0.72%   |
| Chicony EasyCamera                                              | 5         | 0.72%   |
| Acer Lenovo EasyCamera                                          | 5         | 0.72%   |
| Suyin HP TrueVision HD Integrated Webcam                        | 4         | 0.57%   |
| Sunplus HD WebCam                                               | 4         | 0.57%   |
| Quanta VGA WebCam                                               | 4         | 0.57%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 4         | 0.57%   |
| IMC Networks ov9734_azurewave_camera                            | 4         | 0.57%   |
| Chicony USB2.0 HD UVC WebCam                                    | 4         | 0.57%   |
| Chicony USB 2.0 Camera                                          | 4         | 0.57%   |
| Chicony HP Wide Vision HD Camera                                | 4         | 0.57%   |
| Chicony HP TrueVision HD                                        | 4         | 0.57%   |
| Chicony HP HD Webcam                                            | 4         | 0.57%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                   | 4         | 0.57%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 4         | 0.57%   |
| Apple FaceTime HD Camera (Built-in)                             | 4         | 0.57%   |
| Apple FaceTime HD Camera                                        | 4         | 0.57%   |
| Acer BisonCam, NB Pro                                           | 4         | 0.57%   |
| Syntek EasyCamera                                               | 3         | 0.43%   |
| Suyin Integrated_Webcam_HD                                      | 3         | 0.43%   |
| Realtek Lenovo EasyCamera                                       | 3         | 0.43%   |
| Realtek Laptop Camera                                           | 3         | 0.43%   |
| Realtek Integrated Webcam                                       | 3         | 0.43%   |
| Realtek HD WebCam                                               | 3         | 0.43%   |
| Quanta ov9734_techfront_camera                                  | 3         | 0.43%   |
| Quanta HP Wide Vision HD Camera                                 | 3         | 0.43%   |
| Microdia Laptop_Integrated_Webcam_HD                            | 3         | 0.43%   |
| Luxvisions Innotech Limited Integrated Camera                   | 3         | 0.43%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera            | 3         | 0.43%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 66        | 37.71%  |
| Validity Sensors           | 47        | 26.86%  |
| Shenzhen Goodix Technology | 40        | 22.86%  |
| Elan Microelectronics      | 10        | 5.71%   |
| Upek                       | 6         | 3.43%   |
| LighTuning Technology      | 4         | 2.29%   |
| AuthenTec                  | 2         | 1.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 35        | 20%     |
| Shenzhen Goodix  Fingerprint Device                                        | 27        | 15.43%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 16        | 9.14%   |
| Unknown                                                                    | 13        | 7.43%   |
| Shenzhen Goodix FingerPrint                                                | 9         | 5.14%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 7         | 4%      |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 6         | 3.43%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 3.43%   |
| Elan ELAN:Fingerprint                                                      | 6         | 3.43%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 2.86%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 2.86%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 5         | 2.86%   |
| Validity Sensors VFS491                                                    | 4         | 2.29%   |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 2.29%   |
| Elan ELAN:ARM-M4                                                           | 4         | 2.29%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 1.71%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 1.71%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 1.14%   |
| Synaptics  WBDI                                                            | 2         | 1.14%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 1.14%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 1.14%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 1.14%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 1.14%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.57%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 0.57%   |
| Synaptics WBDI Device                                                      | 1         | 0.57%   |
| AuthenTec AES2810                                                          | 1         | 0.57%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 0.57%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 27        | 44.26%  |
| Broadcom                  | 25        | 40.98%  |
| Lenovo                    | 3         | 4.92%   |
| Upek                      | 2         | 3.28%   |
| O2 Micro                  | 1         | 1.64%   |
| Hewlett-Packard           | 1         | 1.64%   |
| Gemalto (was Gemplus)     | 1         | 1.64%   |
| Aladdin Knowledge Systems | 1         | 1.64%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 27        | 44.26%  |
| Broadcom 58200                                                               | 9         | 14.75%  |
| Broadcom 5880                                                                | 7         | 11.48%  |
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 9.84%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 4.92%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 4.92%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 3.28%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 1.64%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 1.64%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.64%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 1.64%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 423       | 57.39%  |
| 1     | 251       | 34.06%  |
| 2     | 50        | 6.78%   |
| 3     | 10        | 1.36%   |
| 4     | 2         | 0.27%   |
| 5     | 1         | 0.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 172       | 44.91%  |
| Graphics card            | 83        | 21.67%  |
| Multimedia controller    | 46        | 12.01%  |
| Net/wireless             | 31        | 8.09%   |
| Camera                   | 15        | 3.92%   |
| Bluetooth                | 13        | 3.39%   |
| Chipcard                 | 9         | 2.35%   |
| Card reader              | 6         | 1.57%   |
| Storage                  | 3         | 0.78%   |
| Net/ethernet             | 2         | 0.52%   |
| Sound                    | 1         | 0.26%   |
| Network                  | 1         | 0.26%   |
| Communication controller | 1         | 0.26%   |

