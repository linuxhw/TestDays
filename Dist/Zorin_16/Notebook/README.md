Zorin 16 - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------

A project to collect tested hardware configurations for Zorin 16.

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

Total: 3512

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | TravelMate 5210             | [379e44855f](https://linux-hardware.org/?probe=379e44855f) | Jan 05, 2025 |
| Dell          | Vostro 1500                 | [b5ecc28563](https://linux-hardware.org/?probe=b5ecc28563) | Dec 31, 2024 |
| Lenovo        | ThinkPad T520 42424UU       | [b4a2895025](https://linux-hardware.org/?probe=b4a2895025) | Dec 28, 2024 |
| Lenovo        | ThinkPad T420 418062U       | [f06b701043](https://linux-hardware.org/?probe=f06b701043) | Dec 27, 2024 |
| Fujitsu Si... | LIFEBOOK S7220              | [7aa92e6daf](https://linux-hardware.org/?probe=7aa92e6daf) | Dec 27, 2024 |
| Fujitsu Si... | LIFEBOOK S7220              | [2f65653f5c](https://linux-hardware.org/?probe=2f65653f5c) | Dec 27, 2024 |
| Lenovo        | ThinkPad T520 42424UU       | [5de1acb22e](https://linux-hardware.org/?probe=5de1acb22e) | Dec 27, 2024 |
| Dell          | Latitude E4300              | [cfcc3cbd9f](https://linux-hardware.org/?probe=cfcc3cbd9f) | Dec 23, 2024 |
| Dell          | Latitude E4300              | [e67d828b77](https://linux-hardware.org/?probe=e67d828b77) | Dec 23, 2024 |
| Gateway       | NE56R                       | [cefc202761](https://linux-hardware.org/?probe=cefc202761) | Dec 10, 2024 |
| HP            | Pavilion 17                 | [0ca43719ed](https://linux-hardware.org/?probe=0ca43719ed) | Dec 06, 2024 |
| Toshiba       | Satellite C660D             | [ae20ba1091](https://linux-hardware.org/?probe=ae20ba1091) | Dec 03, 2024 |
| MSI           | MS-N014                     | [8f4f502803](https://linux-hardware.org/?probe=8f4f502803) | Nov 27, 2024 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [066e955a01](https://linux-hardware.org/?probe=066e955a01) | Nov 24, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [412e0842bc](https://linux-hardware.org/?probe=412e0842bc) | Nov 21, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [6cd8e82a85](https://linux-hardware.org/?probe=6cd8e82a85) | Nov 21, 2024 |
| Lenovo        | ThinkPad X201 36803D7       | [2488665eda](https://linux-hardware.org/?probe=2488665eda) | Nov 15, 2024 |
| HP            | EliteBook 820 G1            | [c4b2bda42d](https://linux-hardware.org/?probe=c4b2bda42d) | Nov 09, 2024 |
| HP            | Pavilion Sleekbook 15 PC    | [06aea2ac21](https://linux-hardware.org/?probe=06aea2ac21) | Nov 05, 2024 |
| Acer          | Aspire SW5-012              | [aed9a62d9a](https://linux-hardware.org/?probe=aed9a62d9a) | Nov 04, 2024 |
| Acer          | Extensa 5635ZG              | [46d4a76e28](https://linux-hardware.org/?probe=46d4a76e28) | Nov 02, 2024 |
| Lenovo        | Z70-80 80FG                 | [36e44b1959](https://linux-hardware.org/?probe=36e44b1959) | Oct 29, 2024 |
| Dell          | Latitude D830               | [9dcccfc8bd](https://linux-hardware.org/?probe=9dcccfc8bd) | Oct 28, 2024 |
| Dell          | Latitude D530               | [c1459031b7](https://linux-hardware.org/?probe=c1459031b7) | Oct 25, 2024 |
| ASUSTek       | K55A                        | [d0eea3c30a](https://linux-hardware.org/?probe=d0eea3c30a) | Oct 25, 2024 |
| Dell          | Latitude E7450              | [49d9a72f4e](https://linux-hardware.org/?probe=49d9a72f4e) | Oct 07, 2024 |
| HP            | ENVY 17 Leap Motion SE N... | [a8c1a124a9](https://linux-hardware.org/?probe=a8c1a124a9) | Oct 06, 2024 |
| Dell          | Inspiron 3543               | [8867a3f043](https://linux-hardware.org/?probe=8867a3f043) | Oct 05, 2024 |
| HP            | 625 (VW697EC)               | [ae4660d758](https://linux-hardware.org/?probe=ae4660d758) | Oct 04, 2024 |
| HP            | 625 (VW697EC)               | [933fa4ee91](https://linux-hardware.org/?probe=933fa4ee91) | Oct 03, 2024 |
| ASUSTek       | X405UA                      | [d9a22e6539](https://linux-hardware.org/?probe=d9a22e6539) | Sep 23, 2024 |
| Acer          | Aspire M5-583P              | [402d480ac7](https://linux-hardware.org/?probe=402d480ac7) | Sep 16, 2024 |
| HP            | ProBook 6570b               | [5b28f08307](https://linux-hardware.org/?probe=5b28f08307) | Sep 15, 2024 |
| Lenovo        | ThinkPad X201 36803D7       | [0951b0296f](https://linux-hardware.org/?probe=0951b0296f) | Sep 06, 2024 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [17b6d58dd6](https://linux-hardware.org/?probe=17b6d58dd6) | Sep 02, 2024 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [2c9b283a47](https://linux-hardware.org/?probe=2c9b283a47) | Sep 01, 2024 |
| Lenovo        | V14-IIL 82C4                | [6cce07e59a](https://linux-hardware.org/?probe=6cce07e59a) | Aug 27, 2024 |
| Lenovo        | G50-80 80R0                 | [fef5f4b6e6](https://linux-hardware.org/?probe=fef5f4b6e6) | Aug 27, 2024 |
| ASUSTek       | K93SV                       | [22b7252c1e](https://linux-hardware.org/?probe=22b7252c1e) | Aug 27, 2024 |
| Lenovo        | G50-80 80R0                 | [e2934da80c](https://linux-hardware.org/?probe=e2934da80c) | Aug 26, 2024 |
| MSI           | GF63 Thin 9RCX              | [6ebcf05841](https://linux-hardware.org/?probe=6ebcf05841) | Aug 21, 2024 |
| HP            | ProBook 6570b               | [742d48f2c5](https://linux-hardware.org/?probe=742d48f2c5) | Aug 18, 2024 |
| Dell          | Inspiron 5447               | [3ca233c313](https://linux-hardware.org/?probe=3ca233c313) | Aug 16, 2024 |
| Toshiba       | Satellite L50-B             | [fe95a4d9d9](https://linux-hardware.org/?probe=fe95a4d9d9) | Aug 16, 2024 |
| Lenovo        | ThinkPad A485 20MVS0X62X    | [4e79a5dba0](https://linux-hardware.org/?probe=4e79a5dba0) | Aug 12, 2024 |
| HP            | Laptop 15s-du3xxx           | [b08bd4b9be](https://linux-hardware.org/?probe=b08bd4b9be) | Aug 03, 2024 |
| Toshiba       | Satellite L50-B             | [00b4917faf](https://linux-hardware.org/?probe=00b4917faf) | Aug 02, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [ee57a214a5](https://linux-hardware.org/?probe=ee57a214a5) | Jul 31, 2024 |
| Acer          | Aspire M5-583P              | [9b35f780ba](https://linux-hardware.org/?probe=9b35f780ba) | Jul 28, 2024 |
| Medion        | S5610                       | [9f7039a688](https://linux-hardware.org/?probe=9f7039a688) | Jul 28, 2024 |
| Wortmann      | FR1220578_1470116           | [45c3f64216](https://linux-hardware.org/?probe=45c3f64216) | Jul 28, 2024 |
| Lenovo        | IdeaPad U410                | [b8b8a7241d](https://linux-hardware.org/?probe=b8b8a7241d) | Jul 27, 2024 |
| Acer          | Aspire M5-583P              | [5c5abd6cdc](https://linux-hardware.org/?probe=5c5abd6cdc) | Jul 25, 2024 |
| ASUSTek       | K93SV                       | [5d544a09dd](https://linux-hardware.org/?probe=5d544a09dd) | Jul 25, 2024 |
| HP            | 14                          | [6381dc091b](https://linux-hardware.org/?probe=6381dc091b) | Jul 24, 2024 |
| HP            | 14                          | [0c704da202](https://linux-hardware.org/?probe=0c704da202) | Jul 22, 2024 |
| HP            | 2000                        | [08dc7124d2](https://linux-hardware.org/?probe=08dc7124d2) | Jul 22, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [977e94dbb3](https://linux-hardware.org/?probe=977e94dbb3) | Jul 20, 2024 |
| Dell          | Latitude 7390               | [7fbd8bda9a](https://linux-hardware.org/?probe=7fbd8bda9a) | Jul 20, 2024 |
| ASUSTek       | UL50VT                      | [bc1ff179a3](https://linux-hardware.org/?probe=bc1ff179a3) | Jul 14, 2024 |
| Lenovo        | ThinkPad A485 20MVS0X62X    | [037fb75cc0](https://linux-hardware.org/?probe=037fb75cc0) | Jul 14, 2024 |
| Apple         | MacBook7,1                  | [118264dd2e](https://linux-hardware.org/?probe=118264dd2e) | Jul 13, 2024 |
| AMI           | Unknown                     | [bbd263c78b](https://linux-hardware.org/?probe=bbd263c78b) | Jul 10, 2024 |
| Lenovo        | Yoga Pro 9 16IMH9 83DN      | [efdb6c4558](https://linux-hardware.org/?probe=efdb6c4558) | Jul 06, 2024 |
| Dell          | Latitude E6520              | [4945d904f3](https://linux-hardware.org/?probe=4945d904f3) | Jul 05, 2024 |
| Dell          | Latitude E6520              | [43f678ce52](https://linux-hardware.org/?probe=43f678ce52) | Jul 02, 2024 |
| HP            | Notebook                    | [a093e1b594](https://linux-hardware.org/?probe=a093e1b594) | Jun 28, 2024 |
| HP            | Notebook                    | [6e535b1fd1](https://linux-hardware.org/?probe=6e535b1fd1) | Jun 28, 2024 |
| HP            | 250 15.6 inch G9 Noteboo... | [1990e46def](https://linux-hardware.org/?probe=1990e46def) | Jun 23, 2024 |
| Lenovo        | Z51-70 80K6                 | [3aea2776ac](https://linux-hardware.org/?probe=3aea2776ac) | Jun 19, 2024 |
| Dell          | Latitude E5500              | [1264354878](https://linux-hardware.org/?probe=1264354878) | Jun 18, 2024 |
| Unknown       | Unknown                     | [77d1ea732e](https://linux-hardware.org/?probe=77d1ea732e) | Jun 17, 2024 |
| Lenovo        | ThinkPad X230 2325PB3       | [391a3f4d0f](https://linux-hardware.org/?probe=391a3f4d0f) | Jun 09, 2024 |
| Lenovo        | ThinkPad X230 2325PB3       | [51ddff7468](https://linux-hardware.org/?probe=51ddff7468) | Jun 08, 2024 |
| Lenovo        | IdeaPad U410                | [6945d0a8b4](https://linux-hardware.org/?probe=6945d0a8b4) | Jun 08, 2024 |
| Acer          | Aspire A515-54              | [4964dddf37](https://linux-hardware.org/?probe=4964dddf37) | Jun 04, 2024 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [df8e59b402](https://linux-hardware.org/?probe=df8e59b402) | May 30, 2024 |
| MSI           | GS73VR 7RF                  | [9be3005158](https://linux-hardware.org/?probe=9be3005158) | May 28, 2024 |
| HP            | Pavilion dv6                | [295d1b4150](https://linux-hardware.org/?probe=295d1b4150) | May 26, 2024 |
| Lenovo        | V15-ADA 82C7                | [a12122eb2a](https://linux-hardware.org/?probe=a12122eb2a) | May 25, 2024 |
| Acer          | Aspire V3-572G              | [afbfc24291](https://linux-hardware.org/?probe=afbfc24291) | May 22, 2024 |
| HP            | EliteBook 8470p             | [68781bf67c](https://linux-hardware.org/?probe=68781bf67c) | May 18, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M360... | [b853bbc409](https://linux-hardware.org/?probe=b853bbc409) | May 16, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M360... | [6e282ab8d7](https://linux-hardware.org/?probe=6e282ab8d7) | May 15, 2024 |
| Lenovo        | V15 G4 IAH 83FS             | [bfcdaa0e75](https://linux-hardware.org/?probe=bfcdaa0e75) | May 15, 2024 |
| Samsung       | 305E4A/305E5A/305E7A        | [471865ac80](https://linux-hardware.org/?probe=471865ac80) | May 11, 2024 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | [34e765cb75](https://linux-hardware.org/?probe=34e765cb75) | May 10, 2024 |
| Lenovo        | ThinkPad Edge E530c 3366... | [d4d583a573](https://linux-hardware.org/?probe=d4d583a573) | May 07, 2024 |
| Fujitsu       | LIFEBOOK U7510              | [a52ed98e85](https://linux-hardware.org/?probe=a52ed98e85) | May 07, 2024 |
| SCHNEIDER     | SCL141CTP                   | [ce0a785c29](https://linux-hardware.org/?probe=ce0a785c29) | May 07, 2024 |
| HP            | Pavilion Notebook           | [2fc15c8d5c](https://linux-hardware.org/?probe=2fc15c8d5c) | May 02, 2024 |
| Lenovo        | ThinkPad X200s 7469W92      | [687cc00e33](https://linux-hardware.org/?probe=687cc00e33) | May 01, 2024 |
| Dell          | System Vostro 3450          | [eede1fda8a](https://linux-hardware.org/?probe=eede1fda8a) | Apr 30, 2024 |
| Lenovo        | B50-80 80EW                 | [5f20d3fde3](https://linux-hardware.org/?probe=5f20d3fde3) | Apr 29, 2024 |
| HP            | ProBook 450 G1              | [9c5d161110](https://linux-hardware.org/?probe=9c5d161110) | Apr 28, 2024 |
| Acer          | Aspire E5-575T              | [d91600e2a3](https://linux-hardware.org/?probe=d91600e2a3) | Apr 22, 2024 |
| Dell          | XPS MXC062                  | [3d7326b94d](https://linux-hardware.org/?probe=3d7326b94d) | Apr 22, 2024 |
| Dell          | XPS MXC062                  | [d217b8e5ee](https://linux-hardware.org/?probe=d217b8e5ee) | Apr 22, 2024 |
| ASUSTek       | K75VM                       | [c863c3ba6b](https://linux-hardware.org/?probe=c863c3ba6b) | Apr 21, 2024 |
| Mediacom      | SmartBook Pro i5            | [fdc40cdd18](https://linux-hardware.org/?probe=fdc40cdd18) | Apr 19, 2024 |
| Dell          | Latitude E5420              | [f937473451](https://linux-hardware.org/?probe=f937473451) | Apr 19, 2024 |
| Acer          | Aspire A515-43              | [fcd5e8e59d](https://linux-hardware.org/?probe=fcd5e8e59d) | Apr 16, 2024 |
| Dell          | XPS 15 9550                 | [22d857c49c](https://linux-hardware.org/?probe=22d857c49c) | Apr 14, 2024 |
| Dell          | Latitude 3440               | [e334ba82e5](https://linux-hardware.org/?probe=e334ba82e5) | Apr 14, 2024 |
| Dell          | Latitude 3440               | [77e2af784e](https://linux-hardware.org/?probe=77e2af784e) | Apr 14, 2024 |
| HP            | Pavilion dv6000 (GM695LA... | [21796df3a5](https://linux-hardware.org/?probe=21796df3a5) | Apr 14, 2024 |
| ASUSTek       | E402SA                      | [5266b4e65d](https://linux-hardware.org/?probe=5266b4e65d) | Apr 13, 2024 |
| ASUSTek       | N552VW                      | [02c36db055](https://linux-hardware.org/?probe=02c36db055) | Apr 12, 2024 |
| Lenovo        | G550 2958                   | [2cebfc34df](https://linux-hardware.org/?probe=2cebfc34df) | Apr 12, 2024 |
| Lenovo        | ThinkPad T520 4243F53       | [9996ba8710](https://linux-hardware.org/?probe=9996ba8710) | Apr 12, 2024 |
| ASUSTek       | N552VW                      | [981a9ddf63](https://linux-hardware.org/?probe=981a9ddf63) | Apr 11, 2024 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | [b87b1a20b9](https://linux-hardware.org/?probe=b87b1a20b9) | Apr 06, 2024 |
| MSI           | GT70 2PE                    | [13f21446e0](https://linux-hardware.org/?probe=13f21446e0) | Apr 06, 2024 |
| Acer          | Aspire 5750                 | [ee4bb4963a](https://linux-hardware.org/?probe=ee4bb4963a) | Apr 04, 2024 |
| Dell          | Latitude E7470              | [ea70b2caa0](https://linux-hardware.org/?probe=ea70b2caa0) | Apr 04, 2024 |
| Apple         | MacBookPro9,2               | [cccef069f7](https://linux-hardware.org/?probe=cccef069f7) | Apr 01, 2024 |
| Dell          | Latitude 7480               | [0ab21a354e](https://linux-hardware.org/?probe=0ab21a354e) | Mar 31, 2024 |
| HP            | 15                          | [e1c7ccf97a](https://linux-hardware.org/?probe=e1c7ccf97a) | Mar 31, 2024 |
| Lenovo        | ThinkPad E470 20H1006KGE    | [494ac5439c](https://linux-hardware.org/?probe=494ac5439c) | Mar 28, 2024 |
| Dell          | Inspiron 5537               | [f081fc7478](https://linux-hardware.org/?probe=f081fc7478) | Mar 26, 2024 |
| Dell          | Inspiron 5537               | [bbe46521b3](https://linux-hardware.org/?probe=bbe46521b3) | Mar 26, 2024 |
| Toshiba       | Satellite L355D             | [fd8ddd8b99](https://linux-hardware.org/?probe=fd8ddd8b99) | Mar 25, 2024 |
| Fujitsu       | LIFEBOOK S760               | [9ef9218d97](https://linux-hardware.org/?probe=9ef9218d97) | Mar 24, 2024 |
| Lenovo        | ThinkPad X230 2325PB3       | [399c0cd75c](https://linux-hardware.org/?probe=399c0cd75c) | Mar 23, 2024 |
| HP            | 15                          | [139e556699](https://linux-hardware.org/?probe=139e556699) | Mar 23, 2024 |
| Positivo      | Q232A                       | [46c3ff72eb](https://linux-hardware.org/?probe=46c3ff72eb) | Mar 23, 2024 |
| Positivo      | Q232A                       | [924bb4b4ee](https://linux-hardware.org/?probe=924bb4b4ee) | Mar 23, 2024 |
| Google        | Magma                       | [8fe3986816](https://linux-hardware.org/?probe=8fe3986816) | Mar 20, 2024 |
| HP            | Compaq 6715s (KE068ET#AB... | [93f757d8b3](https://linux-hardware.org/?probe=93f757d8b3) | Mar 18, 2024 |
| ASUSTek       | K42F                        | [f36df8e399](https://linux-hardware.org/?probe=f36df8e399) | Mar 18, 2024 |
| HP            | Pavilion dv6000 (GF677EA... | [ecbe5ffb1f](https://linux-hardware.org/?probe=ecbe5ffb1f) | Mar 16, 2024 |
| Apple         | MacBook5,2                  | [e482eea403](https://linux-hardware.org/?probe=e482eea403) | Mar 13, 2024 |
| Apple         | MacBook5,2                  | [7e0aa86d1c](https://linux-hardware.org/?probe=7e0aa86d1c) | Mar 13, 2024 |
| Fujitsu       | LIFEBOOK U7510              | [b78e24d0f3](https://linux-hardware.org/?probe=b78e24d0f3) | Mar 11, 2024 |
| HP            | ProBook 650 G2              | [532a823ad7](https://linux-hardware.org/?probe=532a823ad7) | Mar 11, 2024 |
| HP            | ProBook 450 G6              | [6fb4193bc2](https://linux-hardware.org/?probe=6fb4193bc2) | Mar 10, 2024 |
| Acer          | Aspire 9410                 | [3307f5eede](https://linux-hardware.org/?probe=3307f5eede) | Mar 09, 2024 |
| HP            | 1000                        | [12df954c4d](https://linux-hardware.org/?probe=12df954c4d) | Mar 09, 2024 |
| HP            | Compaq 6715s (KE068ET#AB... | [bd5a3177a0](https://linux-hardware.org/?probe=bd5a3177a0) | Mar 09, 2024 |
| HP            | Laptop 15s-du3xxx           | [d3e9bec32e](https://linux-hardware.org/?probe=d3e9bec32e) | Mar 08, 2024 |
| ASUSTek       | X205TAW                     | [6ed323ca5c](https://linux-hardware.org/?probe=6ed323ca5c) | Mar 07, 2024 |
| ASUSTek       | X205TAW                     | [2dd874e62c](https://linux-hardware.org/?probe=2dd874e62c) | Mar 07, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [e545b12914](https://linux-hardware.org/?probe=e545b12914) | Mar 07, 2024 |
| HP            | ZBook Fury 17.3 inch G8 ... | [0111e861f4](https://linux-hardware.org/?probe=0111e861f4) | Mar 07, 2024 |
| Acer          | Aspire M3-581G              | [7ab92d79ee](https://linux-hardware.org/?probe=7ab92d79ee) | Mar 06, 2024 |
| Lenovo        | V15-ADA 82C7                | [06c5a79ab1](https://linux-hardware.org/?probe=06c5a79ab1) | Mar 06, 2024 |
| TongFang      | GM7PX0N                     | [632d2a6962](https://linux-hardware.org/?probe=632d2a6962) | Mar 06, 2024 |
| TongFang      | GM7PX0N                     | [4282677961](https://linux-hardware.org/?probe=4282677961) | Mar 05, 2024 |
| Acer          | Extensa 5635ZG              | [736943715c](https://linux-hardware.org/?probe=736943715c) | Mar 04, 2024 |
| Acer          | Extensa 5635ZG              | [e32263435e](https://linux-hardware.org/?probe=e32263435e) | Mar 04, 2024 |
| Lenovo        | IdeaPad S145-15API 81V7     | [f9efc24735](https://linux-hardware.org/?probe=f9efc24735) | Mar 03, 2024 |
| Apple         | MacBookPro5,3               | [20e198611e](https://linux-hardware.org/?probe=20e198611e) | Mar 02, 2024 |
| ASUSTek       | E201NA                      | [39326f3b72](https://linux-hardware.org/?probe=39326f3b72) | Mar 01, 2024 |
| HP            | Laptop 15-ef2xxx            | [aae4ff4009](https://linux-hardware.org/?probe=aae4ff4009) | Feb 29, 2024 |
| HP            | Pavilion Sleekbook 14       | [9727db31ca](https://linux-hardware.org/?probe=9727db31ca) | Feb 28, 2024 |
| Dell          | Latitude E7470              | [d4890f7ed2](https://linux-hardware.org/?probe=d4890f7ed2) | Feb 27, 2024 |
| Lenovo        | ThinkPad T480 20L5000UUS    | [79b3e2b85f](https://linux-hardware.org/?probe=79b3e2b85f) | Feb 26, 2024 |
| Toshiba       | Satellite Pro C50-A-1EM     | [a0d0bf0a80](https://linux-hardware.org/?probe=a0d0bf0a80) | Feb 25, 2024 |
| Toshiba       | Satellite Pro C50-A-1EM     | [c398b93c14](https://linux-hardware.org/?probe=c398b93c14) | Feb 24, 2024 |
| HP            | Pavilion 17                 | [274b953249](https://linux-hardware.org/?probe=274b953249) | Feb 23, 2024 |
| HP            | 240 14 inch G9              | [54ea49a49a](https://linux-hardware.org/?probe=54ea49a49a) | Feb 23, 2024 |
| ASUSTek       | X501U                       | [1ebbe09ae2](https://linux-hardware.org/?probe=1ebbe09ae2) | Feb 21, 2024 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [d7f17aa5fd](https://linux-hardware.org/?probe=d7f17aa5fd) | Feb 21, 2024 |
| Lenovo        | ThinkPad X230 2325CY4       | [6491a02f07](https://linux-hardware.org/?probe=6491a02f07) | Feb 20, 2024 |
| Medion        | Akoya THE TOUCH 10          | [55af4d803a](https://linux-hardware.org/?probe=55af4d803a) | Feb 19, 2024 |
| Acer          | Swift SF314-54              | [a08666a01c](https://linux-hardware.org/?probe=a08666a01c) | Feb 18, 2024 |
| Dell          | Latitude E6410              | [a074f7ca62](https://linux-hardware.org/?probe=a074f7ca62) | Feb 17, 2024 |
| Notebook      | P95_96_97Ex,Rx              | [b3549ef96d](https://linux-hardware.org/?probe=b3549ef96d) | Feb 16, 2024 |
| Dell          | Studio XPS 1640             | [79baf0c0bf](https://linux-hardware.org/?probe=79baf0c0bf) | Feb 15, 2024 |
| MSI           | CR61 3M                     | [6a7b9ef9b5](https://linux-hardware.org/?probe=6a7b9ef9b5) | Feb 15, 2024 |
| Acer          | Aspire VX5-591G             | [ab712b6e6c](https://linux-hardware.org/?probe=ab712b6e6c) | Feb 14, 2024 |
| Lenovo        | ThinkPad T460 20FMS22Q00    | [85e7855e2c](https://linux-hardware.org/?probe=85e7855e2c) | Feb 13, 2024 |
| Unknown       | W1415A                      | [a0c020f290](https://linux-hardware.org/?probe=a0c020f290) | Feb 13, 2024 |
| Lenovo        | G40-45 80E1                 | [23bd060420](https://linux-hardware.org/?probe=23bd060420) | Feb 12, 2024 |
| HP            | Notebook                    | [bdd85f3367](https://linux-hardware.org/?probe=bdd85f3367) | Feb 12, 2024 |
| HP            | Laptop 14-ck0xxx            | [eb7f318e9b](https://linux-hardware.org/?probe=eb7f318e9b) | Feb 11, 2024 |
| Lenovo        | ThinkPad T410 2537CF3       | [7be1e6e033](https://linux-hardware.org/?probe=7be1e6e033) | Feb 10, 2024 |
| HP            | 250 G7 Notebook PC          | [284bdb6d3c](https://linux-hardware.org/?probe=284bdb6d3c) | Feb 10, 2024 |
| HP            | ProBook 430 G1              | [191e61f6f6](https://linux-hardware.org/?probe=191e61f6f6) | Feb 09, 2024 |
| Dell          | Latitude D630               | [3de4290e6a](https://linux-hardware.org/?probe=3de4290e6a) | Feb 09, 2024 |
| Dell          | Latitude D630               | [bb2c9bba3c](https://linux-hardware.org/?probe=bb2c9bba3c) | Feb 09, 2024 |
| MSI           | GF63 Thin 11UC              | [1c9674a221](https://linux-hardware.org/?probe=1c9674a221) | Feb 08, 2024 |
| HP            | ProBook 450 G2              | [7a2fbcd83a](https://linux-hardware.org/?probe=7a2fbcd83a) | Feb 08, 2024 |
| HP            | ProBook 450 G2              | [77995292b4](https://linux-hardware.org/?probe=77995292b4) | Feb 08, 2024 |
| Positivo      | C14CR21                     | [0c5f4aa87b](https://linux-hardware.org/?probe=0c5f4aa87b) | Feb 07, 2024 |
| ASUSTek       | UL50VT                      | [b25f172725](https://linux-hardware.org/?probe=b25f172725) | Feb 07, 2024 |
| HP            | Pavilion Laptop 15-eg0xx... | [1b1a2efc3f](https://linux-hardware.org/?probe=1b1a2efc3f) | Feb 05, 2024 |
| HP            | Pavilion Laptop 15-eg0xx... | [a16ea9a89e](https://linux-hardware.org/?probe=a16ea9a89e) | Feb 05, 2024 |
| HP            | 650                         | [1787878b4c](https://linux-hardware.org/?probe=1787878b4c) | Feb 05, 2024 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [facc68443a](https://linux-hardware.org/?probe=facc68443a) | Feb 05, 2024 |
| Dell          | Latitude E7470              | [cb6d054e87](https://linux-hardware.org/?probe=cb6d054e87) | Feb 04, 2024 |
| Acer          | Extensa 5635ZG              | [8b36e2aaa6](https://linux-hardware.org/?probe=8b36e2aaa6) | Feb 04, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [c4e7517d41](https://linux-hardware.org/?probe=c4e7517d41) | Feb 04, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [db0469bd8f](https://linux-hardware.org/?probe=db0469bd8f) | Feb 04, 2024 |
| Positivo      | Schoolmate 17 SF20PA2       | [d779dcc224](https://linux-hardware.org/?probe=d779dcc224) | Feb 04, 2024 |
| Positivo      | Schoolmate 17 SF20PA2       | [4be4aaae01](https://linux-hardware.org/?probe=4be4aaae01) | Feb 04, 2024 |
| Dell          | Venue 11 Pro 7140           | [35aa24fc01](https://linux-hardware.org/?probe=35aa24fc01) | Feb 04, 2024 |
| Lenovo        | ThinkPad T430 2349HNU       | [f73b7b76a2](https://linux-hardware.org/?probe=f73b7b76a2) | Feb 03, 2024 |
| Toshiba       | Satellite L55-C             | [747bf6b034](https://linux-hardware.org/?probe=747bf6b034) | Feb 03, 2024 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [45207cf034](https://linux-hardware.org/?probe=45207cf034) | Jan 31, 2024 |
| HP            | EliteBook 8460p             | [8ddfa07beb](https://linux-hardware.org/?probe=8ddfa07beb) | Jan 31, 2024 |
| HP            | ProBook 6570b               | [20537302e6](https://linux-hardware.org/?probe=20537302e6) | Jan 31, 2024 |
| Acer          | Aspire 9420                 | [d0c7154097](https://linux-hardware.org/?probe=d0c7154097) | Jan 30, 2024 |
| Dell          | Inspiron 1545               | [3cffc989aa](https://linux-hardware.org/?probe=3cffc989aa) | Jan 29, 2024 |
| Dell          | Inspiron 1545               | [31ce3ae751](https://linux-hardware.org/?probe=31ce3ae751) | Jan 29, 2024 |
| Acer          | Aspire M3-581G              | [b91416ad7c](https://linux-hardware.org/?probe=b91416ad7c) | Jan 28, 2024 |
| Dell          | Latitude E6430              | [237d6e4d3e](https://linux-hardware.org/?probe=237d6e4d3e) | Jan 27, 2024 |
| Toshiba       | Satellite R630              | [c888a8f4d5](https://linux-hardware.org/?probe=c888a8f4d5) | Jan 24, 2024 |
| Apple         | MacBookPro5,5               | [214ebad454](https://linux-hardware.org/?probe=214ebad454) | Jan 24, 2024 |
| Apple         | MacBookPro5,5               | [f2a415adc9](https://linux-hardware.org/?probe=f2a415adc9) | Jan 24, 2024 |
| HP            | ZBook Studio G5             | [114d79aa75](https://linux-hardware.org/?probe=114d79aa75) | Jan 23, 2024 |
| Dell          | Latitude E5420              | [8347319849](https://linux-hardware.org/?probe=8347319849) | Jan 23, 2024 |
| HP            | Pavilion g4                 | [f0cc56ebca](https://linux-hardware.org/?probe=f0cc56ebca) | Jan 23, 2024 |
| Google        | Kefka                       | [6cb0b95d02](https://linux-hardware.org/?probe=6cb0b95d02) | Jan 22, 2024 |
| HP            | Notebook                    | [8359e2a5dd](https://linux-hardware.org/?probe=8359e2a5dd) | Jan 22, 2024 |
| HP            | Laptop 15-fc0xxx            | [8dacf655a4](https://linux-hardware.org/?probe=8dacf655a4) | Jan 22, 2024 |
| HP            | Laptop 15-fc0xxx            | [c3f3bb78c6](https://linux-hardware.org/?probe=c3f3bb78c6) | Jan 22, 2024 |
| HP            | ProBook 430 G4              | [046036e7e3](https://linux-hardware.org/?probe=046036e7e3) | Jan 22, 2024 |
| HP            | ProBook 430 G4              | [262a8552de](https://linux-hardware.org/?probe=262a8552de) | Jan 22, 2024 |
| Dell          | Inspiron 5559               | [a0c06abcbd](https://linux-hardware.org/?probe=a0c06abcbd) | Jan 22, 2024 |
| Dell          | Latitude 5490               | [ebc5bed33f](https://linux-hardware.org/?probe=ebc5bed33f) | Jan 22, 2024 |
| Lenovo        | V15-ADA 82C7                | [a8893e7742](https://linux-hardware.org/?probe=a8893e7742) | Jan 22, 2024 |
| Apple         | MacBookPro14,1              | [af0244605f](https://linux-hardware.org/?probe=af0244605f) | Jan 21, 2024 |
| Apple         | MacBookPro14,1              | [024b0a26f9](https://linux-hardware.org/?probe=024b0a26f9) | Jan 21, 2024 |
| Toshiba       | Satellite L640              | [7478e6971b](https://linux-hardware.org/?probe=7478e6971b) | Jan 21, 2024 |
| HP            | Notebook                    | [2dcfaac5fd](https://linux-hardware.org/?probe=2dcfaac5fd) | Jan 21, 2024 |
| Sony          | VGN-NS11Z_S                 | [64fa921691](https://linux-hardware.org/?probe=64fa921691) | Jan 20, 2024 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [4257aab3ea](https://linux-hardware.org/?probe=4257aab3ea) | Jan 20, 2024 |
| Dell          | Inspiron 3531               | [afc0f1a968](https://linux-hardware.org/?probe=afc0f1a968) | Jan 20, 2024 |
| HP            | EliteBook 840 G1            | [becbec6f26](https://linux-hardware.org/?probe=becbec6f26) | Jan 20, 2024 |
| Acer          | Aspire E5-551G              | [c4bd469e8d](https://linux-hardware.org/?probe=c4bd469e8d) | Jan 19, 2024 |
| Acer          | Aspire E5-523               | [02378722b6](https://linux-hardware.org/?probe=02378722b6) | Jan 19, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [ae841d1af4](https://linux-hardware.org/?probe=ae841d1af4) | Jan 17, 2024 |
| HP            | ZBook 14u G6                | [668a33bda1](https://linux-hardware.org/?probe=668a33bda1) | Jan 17, 2024 |
| Toshiba       | Satellite A665              | [66c11ee330](https://linux-hardware.org/?probe=66c11ee330) | Jan 17, 2024 |
| Toshiba       | Satellite C850-B820         | [321a8ae666](https://linux-hardware.org/?probe=321a8ae666) | Jan 17, 2024 |
| Toshiba       | Satellite A665              | [640deb41af](https://linux-hardware.org/?probe=640deb41af) | Jan 17, 2024 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | [0e05a50329](https://linux-hardware.org/?probe=0e05a50329) | Jan 16, 2024 |
| HP            | Pavilion 17                 | [3594afe0d4](https://linux-hardware.org/?probe=3594afe0d4) | Jan 16, 2024 |
| Intel         | Unknown                     | [dfd975eff3](https://linux-hardware.org/?probe=dfd975eff3) | Jan 15, 2024 |
| Sony          | VGN-NS11Z_S                 | [863785eef9](https://linux-hardware.org/?probe=863785eef9) | Jan 13, 2024 |
| Dell          | Inspiron 3501               | [75a54dcccf](https://linux-hardware.org/?probe=75a54dcccf) | Jan 13, 2024 |
| Toshiba       | Satellite R630              | [0e83a06873](https://linux-hardware.org/?probe=0e83a06873) | Jan 13, 2024 |
| Acer          | Aspire V5-573G              | [09ddfeab43](https://linux-hardware.org/?probe=09ddfeab43) | Jan 12, 2024 |
| ASUSTek       | N56JR                       | [513c456753](https://linux-hardware.org/?probe=513c456753) | Jan 11, 2024 |
| Medion        | E4251 MD61435               | [6a9251fa94](https://linux-hardware.org/?probe=6a9251fa94) | Jan 11, 2024 |
| HP            | Pavilion Sleekbook 14       | [9f54d91b95](https://linux-hardware.org/?probe=9f54d91b95) | Jan 10, 2024 |
| Toshiba       | Satellite L845              | [e45e9517b3](https://linux-hardware.org/?probe=e45e9517b3) | Jan 10, 2024 |
| Dell          | Inspiron 7737               | [ae41cf1d2f](https://linux-hardware.org/?probe=ae41cf1d2f) | Jan 10, 2024 |
| Acer          | Aspire E1-570G              | [2bb5dcf476](https://linux-hardware.org/?probe=2bb5dcf476) | Jan 10, 2024 |
| ASUSTek       | X200CA                      | [c27c1b9fc2](https://linux-hardware.org/?probe=c27c1b9fc2) | Jan 10, 2024 |
| Toshiba       | Satellite C850              | [38fb6d3619](https://linux-hardware.org/?probe=38fb6d3619) | Jan 09, 2024 |
| Toshiba       | Satellite C850              | [c6faf796f4](https://linux-hardware.org/?probe=c6faf796f4) | Jan 09, 2024 |
| HONOR         | BBR-WAX9                    | [b9d1ee2b4c](https://linux-hardware.org/?probe=b9d1ee2b4c) | Jan 08, 2024 |
| HP            | EliteBook 8440p             | [6a5afb5dec](https://linux-hardware.org/?probe=6a5afb5dec) | Jan 08, 2024 |
| HP            | EliteBook Revolve 810 G1    | [c428c1eb3e](https://linux-hardware.org/?probe=c428c1eb3e) | Jan 08, 2024 |
| ASUSTek       | UL50VT                      | [428d20a1eb](https://linux-hardware.org/?probe=428d20a1eb) | Jan 07, 2024 |
| Acer          | Swift SF314-511             | [14eac9efff](https://linux-hardware.org/?probe=14eac9efff) | Jan 07, 2024 |
| Acer          | Aspire E1-570G              | [3c08b1958e](https://linux-hardware.org/?probe=3c08b1958e) | Jan 07, 2024 |
| Dell          | Latitude E5420              | [40835d5737](https://linux-hardware.org/?probe=40835d5737) | Jan 07, 2024 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [b02f06751f](https://linux-hardware.org/?probe=b02f06751f) | Jan 07, 2024 |
| Lenovo        | ThinkPad T520 4243F53       | [900bfdd9a8](https://linux-hardware.org/?probe=900bfdd9a8) | Jan 06, 2024 |
| HP            | ENVY dv6                    | [12f54bd4e0](https://linux-hardware.org/?probe=12f54bd4e0) | Jan 06, 2024 |
| HP            | Pavilion Power Laptop 15... | [37ea5af9b1](https://linux-hardware.org/?probe=37ea5af9b1) | Jan 04, 2024 |
| Dell          | Inspiron 1525               | [debaccaee2](https://linux-hardware.org/?probe=debaccaee2) | Jan 04, 2024 |
| ASUSTek       | E201NA                      | [91cac0307a](https://linux-hardware.org/?probe=91cac0307a) | Jan 04, 2024 |
| Lenovo        | ThinkPad P16s Gen 1 21BT... | [e15430e53e](https://linux-hardware.org/?probe=e15430e53e) | Jan 02, 2024 |
| Lenovo        | ThinkPad T460s 20FAS1V60... | [ca5f55438f](https://linux-hardware.org/?probe=ca5f55438f) | Jan 02, 2024 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [a37bbce8de](https://linux-hardware.org/?probe=a37bbce8de) | Dec 31, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [d975ab384e](https://linux-hardware.org/?probe=d975ab384e) | Dec 31, 2023 |
| Acer          | Aspire 8943G                | [a75a2524f2](https://linux-hardware.org/?probe=a75a2524f2) | Dec 31, 2023 |
| Sony          | VGN-CR21S_W                 | [732175d0f6](https://linux-hardware.org/?probe=732175d0f6) | Dec 29, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [9189ed311a](https://linux-hardware.org/?probe=9189ed311a) | Dec 29, 2023 |
| HP            | ZBook 14u G6                | [409e402108](https://linux-hardware.org/?probe=409e402108) | Dec 28, 2023 |
| Dell          | Vostro 2420                 | [52ae549c99](https://linux-hardware.org/?probe=52ae549c99) | Dec 28, 2023 |
| Acer          | Aspire E1-570               | [403dd9f171](https://linux-hardware.org/?probe=403dd9f171) | Dec 27, 2023 |
| HP            | Compaq 2510p                | [b7b88f9c1c](https://linux-hardware.org/?probe=b7b88f9c1c) | Dec 27, 2023 |
| UNOWHY        | Y13G012S4EI                 | [a3bb952104](https://linux-hardware.org/?probe=a3bb952104) | Dec 27, 2023 |
| HP            | EliteBook Revolve 810 G1    | [30d2bb71e5](https://linux-hardware.org/?probe=30d2bb71e5) | Dec 27, 2023 |
| Lenovo        | ThinkPad T440p 20AWS08S0... | [ae928b9cc1](https://linux-hardware.org/?probe=ae928b9cc1) | Dec 25, 2023 |
| HP            | ENVY dv6                    | [e7d00bdca8](https://linux-hardware.org/?probe=e7d00bdca8) | Dec 25, 2023 |
| HP            | ENVY dv6                    | [7feb95b534](https://linux-hardware.org/?probe=7feb95b534) | Dec 25, 2023 |
| Lenovo        | V110-15ISK 80TL             | [dd911fd507](https://linux-hardware.org/?probe=dd911fd507) | Dec 24, 2023 |
| Dell          | Latitude E6430              | [d949738171](https://linux-hardware.org/?probe=d949738171) | Dec 24, 2023 |
| Dell          | Latitude E6430              | [c821d379ec](https://linux-hardware.org/?probe=c821d379ec) | Dec 24, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | [a69b3fa1ca](https://linux-hardware.org/?probe=a69b3fa1ca) | Dec 24, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | [9ac48a1719](https://linux-hardware.org/?probe=9ac48a1719) | Dec 24, 2023 |
| HP            | Notebook                    | [69bef099c0](https://linux-hardware.org/?probe=69bef099c0) | Dec 24, 2023 |
| HP            | Victus by 15.6 inch Gami... | [b74170ede4](https://linux-hardware.org/?probe=b74170ede4) | Dec 23, 2023 |
| Toshiba       | Satellite Pro R50-C         | [b4d280ac6a](https://linux-hardware.org/?probe=b4d280ac6a) | Dec 23, 2023 |
| Toshiba       | Satellite Pro R50-C         | [421d62894b](https://linux-hardware.org/?probe=421d62894b) | Dec 23, 2023 |
| Toshiba       | QOSMIO X770                 | [dceb1203ed](https://linux-hardware.org/?probe=dceb1203ed) | Dec 23, 2023 |
| Toshiba       | QOSMIO X770                 | [b9557b6218](https://linux-hardware.org/?probe=b9557b6218) | Dec 23, 2023 |
| Fujitsu       | LIFEBOOK E736               | [49cdf35ca4](https://linux-hardware.org/?probe=49cdf35ca4) | Dec 22, 2023 |
| VTEX          | NOTEBOOK                    | [972b407abc](https://linux-hardware.org/?probe=972b407abc) | Dec 22, 2023 |
| Lenovo        | ThinkPad X131e 33691K7      | [360dc0f244](https://linux-hardware.org/?probe=360dc0f244) | Dec 21, 2023 |
| Dell          | Latitude E7270              | [4574a46c78](https://linux-hardware.org/?probe=4574a46c78) | Dec 21, 2023 |
| Dell          | Inspiron 15-3567            | [f9d9539e00](https://linux-hardware.org/?probe=f9d9539e00) | Dec 21, 2023 |
| ASUSTek       | E201NA                      | [ee5e05ce6d](https://linux-hardware.org/?probe=ee5e05ce6d) | Dec 21, 2023 |
| HP            | 1000                        | [2279f68ba4](https://linux-hardware.org/?probe=2279f68ba4) | Dec 21, 2023 |
| HP            | EliteBook 840 G6            | [5266cee35b](https://linux-hardware.org/?probe=5266cee35b) | Dec 21, 2023 |
| HP            | ProBook 430 G7              | [50a3c349a0](https://linux-hardware.org/?probe=50a3c349a0) | Dec 21, 2023 |
| HP            | ProBook 430 G7              | [f79ed192ac](https://linux-hardware.org/?probe=f79ed192ac) | Dec 21, 2023 |
| Toshiba       | Satellite C850              | [caa584d966](https://linux-hardware.org/?probe=caa584d966) | Dec 20, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [f7cd6db92f](https://linux-hardware.org/?probe=f7cd6db92f) | Dec 20, 2023 |
| Framework     | Laptop                      | [2aab7ea892](https://linux-hardware.org/?probe=2aab7ea892) | Dec 19, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [bcae8d434f](https://linux-hardware.org/?probe=bcae8d434f) | Dec 19, 2023 |
| HP            | ProBook 650 G1              | [95ab984d32](https://linux-hardware.org/?probe=95ab984d32) | Dec 19, 2023 |
| Lenovo        | V14-IIL 82C4                | [582c2df7b1](https://linux-hardware.org/?probe=582c2df7b1) | Dec 19, 2023 |
| Toshiba       | Satellite Pro C50-A-1E2     | [91b5e05490](https://linux-hardware.org/?probe=91b5e05490) | Dec 19, 2023 |
| Toshiba       | Satellite Pro C50-A-1E2     | [fde7aeea9c](https://linux-hardware.org/?probe=fde7aeea9c) | Dec 19, 2023 |
| Google        | Phaser360                   | [c739678794](https://linux-hardware.org/?probe=c739678794) | Dec 18, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [780a4cf454](https://linux-hardware.org/?probe=780a4cf454) | Dec 18, 2023 |
| Lenovo        | ThinkPad X240 20AMS0VU00    | [ecca798714](https://linux-hardware.org/?probe=ecca798714) | Dec 18, 2023 |
| HP            | ProBook 430 G4              | [c2b96a9e0f](https://linux-hardware.org/?probe=c2b96a9e0f) | Dec 18, 2023 |
| Dell          | Venue 11 Pro 5130           | [74cdfd92c0](https://linux-hardware.org/?probe=74cdfd92c0) | Dec 18, 2023 |
| HP            | ZBook 14u G6                | [125dbde28d](https://linux-hardware.org/?probe=125dbde28d) | Dec 17, 2023 |
| Sony          | VGN-FW455J                  | [f16255f9d1](https://linux-hardware.org/?probe=f16255f9d1) | Dec 17, 2023 |
| ASUSTek       | K53SD                       | [7962dd075b](https://linux-hardware.org/?probe=7962dd075b) | Dec 17, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | [304fbf1e83](https://linux-hardware.org/?probe=304fbf1e83) | Dec 17, 2023 |
| Irbis         | NB12                        | [f6eb11e455](https://linux-hardware.org/?probe=f6eb11e455) | Dec 17, 2023 |
| Google        | Phaser360                   | [784ed40440](https://linux-hardware.org/?probe=784ed40440) | Dec 16, 2023 |
| HP            | ProBook 455 15.6 inch G1... | [56e1b0ed26](https://linux-hardware.org/?probe=56e1b0ed26) | Dec 16, 2023 |
| HP            | ProBook 430 G4              | [30f8fe050c](https://linux-hardware.org/?probe=30f8fe050c) | Dec 16, 2023 |
| HP            | Notebook                    | [4973d42380](https://linux-hardware.org/?probe=4973d42380) | Dec 16, 2023 |
| HP            | Notebook                    | [a960b17c37](https://linux-hardware.org/?probe=a960b17c37) | Dec 16, 2023 |
| ASUSTek       | X553MA                      | [1bd6eab773](https://linux-hardware.org/?probe=1bd6eab773) | Dec 15, 2023 |
| Medion        | P7624                       | [4828985ec0](https://linux-hardware.org/?probe=4828985ec0) | Dec 15, 2023 |
| Medion        | P7624                       | [050fbbd613](https://linux-hardware.org/?probe=050fbbd613) | Dec 15, 2023 |
| Dell          | XPS 15 9550                 | [de4b8201ef](https://linux-hardware.org/?probe=de4b8201ef) | Dec 15, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [b5fefd59fe](https://linux-hardware.org/?probe=b5fefd59fe) | Dec 15, 2023 |
| Medion        | E4251 MD61435               | [7d20d738b1](https://linux-hardware.org/?probe=7d20d738b1) | Dec 14, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [734375c1cc](https://linux-hardware.org/?probe=734375c1cc) | Dec 14, 2023 |
| TUXEDO        | InfinityBook Pro Gen8 (M... | [5ae09c04d4](https://linux-hardware.org/?probe=5ae09c04d4) | Dec 14, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [3eb792873c](https://linux-hardware.org/?probe=3eb792873c) | Dec 14, 2023 |
| Dell          | Inspiron 15 5510            | [41dbdcf594](https://linux-hardware.org/?probe=41dbdcf594) | Dec 13, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [f9933769ef](https://linux-hardware.org/?probe=f9933769ef) | Dec 13, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [27b99be924](https://linux-hardware.org/?probe=27b99be924) | Dec 12, 2023 |
| HP            | Notebook                    | [972e86b7cf](https://linux-hardware.org/?probe=972e86b7cf) | Dec 12, 2023 |
| Lenovo        | G570 20079                  | [bdfc16eb98](https://linux-hardware.org/?probe=bdfc16eb98) | Dec 11, 2023 |
| ASUSTek       | ZenBook UX482EG_UX482EG     | [a644fcc63e](https://linux-hardware.org/?probe=a644fcc63e) | Dec 11, 2023 |
| Lenovo        | ThinkPad T440s 20ARS06C0... | [332492b0c4](https://linux-hardware.org/?probe=332492b0c4) | Dec 11, 2023 |
| HP            | Victus by Gaming Laptop ... | [949de6a6a9](https://linux-hardware.org/?probe=949de6a6a9) | Dec 10, 2023 |
| Dell          | Inspiron 7559               | [3f4af9bbdd](https://linux-hardware.org/?probe=3f4af9bbdd) | Dec 10, 2023 |
| Packard Be... | EasyNote TE11BZ             | [514899b0b9](https://linux-hardware.org/?probe=514899b0b9) | Dec 10, 2023 |
| ASUSTek       | X550VC                      | [e2c932c285](https://linux-hardware.org/?probe=e2c932c285) | Dec 09, 2023 |
| Acer          | AOD257                      | [79c121ca0e](https://linux-hardware.org/?probe=79c121ca0e) | Dec 09, 2023 |
| Dell          | Vostro 3560                 | [d2abe7128b](https://linux-hardware.org/?probe=d2abe7128b) | Dec 09, 2023 |
| Acer          | AOD257                      | [c817dc5cca](https://linux-hardware.org/?probe=c817dc5cca) | Dec 08, 2023 |
| Acer          | Nitro AN515-54              | [045ab5efca](https://linux-hardware.org/?probe=045ab5efca) | Dec 08, 2023 |
| HP            | Compaq 6730b (NB034ET#UU... | [88c39cda86](https://linux-hardware.org/?probe=88c39cda86) | Dec 08, 2023 |
| HP            | Stream Laptop 14-cb1XX      | [fc2efc3edb](https://linux-hardware.org/?probe=fc2efc3edb) | Dec 07, 2023 |
| Lenovo        | ThinkPad P52 20MAS25B1X     | [767b4efa54](https://linux-hardware.org/?probe=767b4efa54) | Dec 06, 2023 |
| Dell          | Latitude 7490               | [364b5c38d4](https://linux-hardware.org/?probe=364b5c38d4) | Dec 06, 2023 |
| Apple         | MacBookAir7,2               | [1748ab2263](https://linux-hardware.org/?probe=1748ab2263) | Dec 05, 2023 |
| HP            | 255 G6 Notebook PC          | [ee58e73f03](https://linux-hardware.org/?probe=ee58e73f03) | Dec 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [dcb521e9aa](https://linux-hardware.org/?probe=dcb521e9aa) | Dec 04, 2023 |
| Dell          | Latitude 6430U              | [45d1723559](https://linux-hardware.org/?probe=45d1723559) | Dec 03, 2023 |
| Dell          | Latitude 6430U              | [1e4dda911f](https://linux-hardware.org/?probe=1e4dda911f) | Dec 03, 2023 |
| HP            | Pavilion dv7                | [42ddf2c00c](https://linux-hardware.org/?probe=42ddf2c00c) | Dec 03, 2023 |
| HP            | Pavilion dv5                | [40e03f76cf](https://linux-hardware.org/?probe=40e03f76cf) | Dec 03, 2023 |
| Dell          | XPS 13 9360                 | [f2a9f68180](https://linux-hardware.org/?probe=f2a9f68180) | Dec 02, 2023 |
| Dell          | XPS 13 9360                 | [e6d3755007](https://linux-hardware.org/?probe=e6d3755007) | Dec 02, 2023 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [5d98fa1470](https://linux-hardware.org/?probe=5d98fa1470) | Dec 02, 2023 |
| Apple         | MacBookPro14,1              | [9dea837056](https://linux-hardware.org/?probe=9dea837056) | Dec 02, 2023 |
| Fujitsu       | LIFEBOOK E780               | [f1e82db736](https://linux-hardware.org/?probe=f1e82db736) | Dec 01, 2023 |
| Acer          | Swift SF314-511             | [ca692e6dcb](https://linux-hardware.org/?probe=ca692e6dcb) | Dec 01, 2023 |
| Acer          | Aspire A517-52G             | [72702ceb3f](https://linux-hardware.org/?probe=72702ceb3f) | Dec 01, 2023 |
| HP            | 15                          | [7bd98a81f6](https://linux-hardware.org/?probe=7bd98a81f6) | Dec 01, 2023 |
| HP            | Laptop 15-bs0xx             | [02f2ca658e](https://linux-hardware.org/?probe=02f2ca658e) | Dec 01, 2023 |
| HP            | Laptop 15-bs0xx             | [e812beed5d](https://linux-hardware.org/?probe=e812beed5d) | Dec 01, 2023 |
| Acer          | Aspire A517-52G             | [33126bb441](https://linux-hardware.org/?probe=33126bb441) | Nov 30, 2023 |
| Toshiba       | Satellite L850D-131         | [483c7cfdf6](https://linux-hardware.org/?probe=483c7cfdf6) | Nov 30, 2023 |
| AMI           | AMD                         | [9f3f9ba617](https://linux-hardware.org/?probe=9f3f9ba617) | Nov 29, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B5602CBA... | [0c08316018](https://linux-hardware.org/?probe=0c08316018) | Nov 29, 2023 |
| Dell          | Inspiron 5558               | [c934dcacd6](https://linux-hardware.org/?probe=c934dcacd6) | Nov 29, 2023 |
| HP            | EliteBook 8440p             | [9af25bdb99](https://linux-hardware.org/?probe=9af25bdb99) | Nov 28, 2023 |
| Medion        | Erazer P7643 MD60133        | [65f090fe28](https://linux-hardware.org/?probe=65f090fe28) | Nov 28, 2023 |
| HP            | 15                          | [c1ca96368f](https://linux-hardware.org/?probe=c1ca96368f) | Nov 28, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 Ub 82KU    | [f99e3c8556](https://linux-hardware.org/?probe=f99e3c8556) | Nov 28, 2023 |
| ASUSTek       | K93SV                       | [f85fb01be1](https://linux-hardware.org/?probe=f85fb01be1) | Nov 28, 2023 |
| HP            | 15                          | [aba1e87e5c](https://linux-hardware.org/?probe=aba1e87e5c) | Nov 28, 2023 |
| Dell          | XPS 15 9550                 | [6d2e371a5f](https://linux-hardware.org/?probe=6d2e371a5f) | Nov 27, 2023 |
| Dell          | Latitude D830               | [2e017edf81](https://linux-hardware.org/?probe=2e017edf81) | Nov 27, 2023 |
| HP            | ENVY m6                     | [41cff88708](https://linux-hardware.org/?probe=41cff88708) | Nov 26, 2023 |
| Apple         | MacBookPro5,4               | [fb45c81af9](https://linux-hardware.org/?probe=fb45c81af9) | Nov 26, 2023 |
| Toshiba       | TECRA W50-A                 | [91a2348496](https://linux-hardware.org/?probe=91a2348496) | Nov 25, 2023 |
| Lenovo        | Z710 20250                  | [c9522c065e](https://linux-hardware.org/?probe=c9522c065e) | Nov 24, 2023 |
| Lenovo        | ThinkPad T570 20HAS0K501    | [4fe6d8f889](https://linux-hardware.org/?probe=4fe6d8f889) | Nov 24, 2023 |
| Toshiba       | TECRA R850                  | [6930db743c](https://linux-hardware.org/?probe=6930db743c) | Nov 24, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | [eb779ea004](https://linux-hardware.org/?probe=eb779ea004) | Nov 24, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | [0d60447eea](https://linux-hardware.org/?probe=0d60447eea) | Nov 24, 2023 |
| HP            | G5000 (GF767EA#B1A)         | [5239511cca](https://linux-hardware.org/?probe=5239511cca) | Nov 24, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [9d5752b2d8](https://linux-hardware.org/?probe=9d5752b2d8) | Nov 24, 2023 |
| Unknown       | M17                         | [d3d7d176b4](https://linux-hardware.org/?probe=d3d7d176b4) | Nov 23, 2023 |
| Medion        | E5214                       | [f3ab89b2d3](https://linux-hardware.org/?probe=f3ab89b2d3) | Nov 23, 2023 |
| Acer          | Aspire E5-511               | [87ccf00042](https://linux-hardware.org/?probe=87ccf00042) | Nov 23, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [c883420b97](https://linux-hardware.org/?probe=c883420b97) | Nov 23, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | [3b995f6b47](https://linux-hardware.org/?probe=3b995f6b47) | Nov 23, 2023 |
| Toshiba       | Satellite L850D-131         | [8810505a5a](https://linux-hardware.org/?probe=8810505a5a) | Nov 23, 2023 |
| Lenovo        | ThinkPad T440 20B7S0VA05    | [37a1e3b979](https://linux-hardware.org/?probe=37a1e3b979) | Nov 23, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [0137a4a556](https://linux-hardware.org/?probe=0137a4a556) | Nov 23, 2023 |
| Acer          | Aspire ES1-731              | [649e8a4e24](https://linux-hardware.org/?probe=649e8a4e24) | Nov 22, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | [8d492b21b0](https://linux-hardware.org/?probe=8d492b21b0) | Nov 22, 2023 |
| HUAWEI        | BoDE-WXX9                   | [343ba69496](https://linux-hardware.org/?probe=343ba69496) | Nov 22, 2023 |
| HUAWEI        | BoDE-WXX9                   | [b365872b3f](https://linux-hardware.org/?probe=b365872b3f) | Nov 22, 2023 |
| Samsung       | 530XBB                      | [c31efedbdf](https://linux-hardware.org/?probe=c31efedbdf) | Nov 22, 2023 |
| ASUSTek       | E201NA                      | [11f7e8f675](https://linux-hardware.org/?probe=11f7e8f675) | Nov 22, 2023 |
| HP            | EliteBook Folio 1020 G1     | [022f885fe9](https://linux-hardware.org/?probe=022f885fe9) | Nov 22, 2023 |
| Notebook      | NL40_50CU                   | [94885b9878](https://linux-hardware.org/?probe=94885b9878) | Nov 21, 2023 |
| HP            | Stream Notebook PC 11       | [c363e01e5f](https://linux-hardware.org/?probe=c363e01e5f) | Nov 21, 2023 |
| Apple         | MacBookPro14,3              | [3664fc3164](https://linux-hardware.org/?probe=3664fc3164) | Nov 20, 2023 |
| HUAWEI        | HVY-WXX9                    | [6c2755ced9](https://linux-hardware.org/?probe=6c2755ced9) | Nov 20, 2023 |
| Lenovo        | ThinkPad Edge E530 32599... | [f472f3fd2e](https://linux-hardware.org/?probe=f472f3fd2e) | Nov 20, 2023 |
| HP            | OMEN by Laptop              | [8fbd1e56eb](https://linux-hardware.org/?probe=8fbd1e56eb) | Nov 20, 2023 |
| Lenovo        | ThinkPad T460 20FMS22Q00    | [84df1d0476](https://linux-hardware.org/?probe=84df1d0476) | Nov 20, 2023 |
| HUAWEI        | CREFG-XX                    | [97b8871652](https://linux-hardware.org/?probe=97b8871652) | Nov 20, 2023 |
| Medion        | E5214                       | [8e3148e284](https://linux-hardware.org/?probe=8e3148e284) | Nov 20, 2023 |
| HP            | ProBook 430 G2              | [e0a3622122](https://linux-hardware.org/?probe=e0a3622122) | Nov 20, 2023 |
| HUAWEI        | CREFG-XX                    | [be15ab8952](https://linux-hardware.org/?probe=be15ab8952) | Nov 19, 2023 |
| Lenovo        | ThinkPad T460 20FMS22Q00    | [626d8d9409](https://linux-hardware.org/?probe=626d8d9409) | Nov 19, 2023 |
| HUAWEI        | CREFG-XX                    | [747979b60f](https://linux-hardware.org/?probe=747979b60f) | Nov 19, 2023 |
| Lenovo        | Z50-75 80EC                 | [6876ff8fc6](https://linux-hardware.org/?probe=6876ff8fc6) | Nov 19, 2023 |
| Medion        | E5214                       | [4513f3394d](https://linux-hardware.org/?probe=4513f3394d) | Nov 18, 2023 |
| HP            | 250 G6 Notebook PC          | [b62a8b07f4](https://linux-hardware.org/?probe=b62a8b07f4) | Nov 18, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [ec19f0fa52](https://linux-hardware.org/?probe=ec19f0fa52) | Nov 18, 2023 |
| Dell          | Latitude 5490               | [b3da1a92d0](https://linux-hardware.org/?probe=b3da1a92d0) | Nov 17, 2023 |
| Compaq        | Presario CQ-17              | [7b53a480e4](https://linux-hardware.org/?probe=7b53a480e4) | Nov 17, 2023 |
| ASUSTek       | ROG Strix G814JI_G814JI     | [54bad5da51](https://linux-hardware.org/?probe=54bad5da51) | Nov 17, 2023 |
| Toshiba       | TECRA R850                  | [9974b99f5a](https://linux-hardware.org/?probe=9974b99f5a) | Nov 16, 2023 |
| HP            | Pavilion g7                 | [9f8b6f3432](https://linux-hardware.org/?probe=9f8b6f3432) | Nov 16, 2023 |
| HP            | Pavilion g7                 | [0c4816a4f2](https://linux-hardware.org/?probe=0c4816a4f2) | Nov 16, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [7edaa0f1be](https://linux-hardware.org/?probe=7edaa0f1be) | Nov 15, 2023 |
| HP            | InsydeH2O EFI BIOS          | [559ef6212b](https://linux-hardware.org/?probe=559ef6212b) | Nov 15, 2023 |
| HP            | ZBook 14u G6                | [c6471dbbfd](https://linux-hardware.org/?probe=c6471dbbfd) | Nov 14, 2023 |
| Adreamer      | PN1308P                     | [8c4d2fca5a](https://linux-hardware.org/?probe=8c4d2fca5a) | Nov 14, 2023 |
| Adreamer      | PN1308P                     | [5efc66eebc](https://linux-hardware.org/?probe=5efc66eebc) | Nov 14, 2023 |
| HP            | Compaq 6910p                | [019a154d30](https://linux-hardware.org/?probe=019a154d30) | Nov 14, 2023 |
| Dell          | System Vostro 3750          | [513485cc8f](https://linux-hardware.org/?probe=513485cc8f) | Nov 14, 2023 |
| Tactus        | GeoBook 110                 | [077bbdc325](https://linux-hardware.org/?probe=077bbdc325) | Nov 14, 2023 |
| Tactus        | GeoBook 110                 | [5e50f31cbb](https://linux-hardware.org/?probe=5e50f31cbb) | Nov 14, 2023 |
| Apple         | MacBookPro12,1              | [d00bbdf844](https://linux-hardware.org/?probe=d00bbdf844) | Nov 14, 2023 |
| Apple         | MacBookPro12,1              | [493702778b](https://linux-hardware.org/?probe=493702778b) | Nov 14, 2023 |
| Dell          | System Vostro 3750          | [3c336ad6e1](https://linux-hardware.org/?probe=3c336ad6e1) | Nov 14, 2023 |
| Lenovo        | ThinkPad E550 20DF00CNGE    | [35e0f85cf3](https://linux-hardware.org/?probe=35e0f85cf3) | Nov 13, 2023 |
| HP            | Laptop 14-ck0xxx            | [73a53ca5a4](https://linux-hardware.org/?probe=73a53ca5a4) | Nov 13, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [a0105ee2c8](https://linux-hardware.org/?probe=a0105ee2c8) | Nov 13, 2023 |
| HP            | 15                          | [20b22b2eeb](https://linux-hardware.org/?probe=20b22b2eeb) | Nov 13, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [83d6eddd15](https://linux-hardware.org/?probe=83d6eddd15) | Nov 12, 2023 |
| HUAWEI        | RLEFG-XX                    | [5f413be4fc](https://linux-hardware.org/?probe=5f413be4fc) | Nov 12, 2023 |
| HUAWEI        | BOHB-WAX9                   | [1d2a92df29](https://linux-hardware.org/?probe=1d2a92df29) | Nov 12, 2023 |
| Lenovo        | ThinkPad E580 20KS001RGE    | [55b706c3ec](https://linux-hardware.org/?probe=55b706c3ec) | Nov 12, 2023 |
| Lenovo        | ThinkPad T460 20FMS22Q00    | [4c40c1d213](https://linux-hardware.org/?probe=4c40c1d213) | Nov 11, 2023 |
| Unknown       | Unknown                     | [16acb0dabc](https://linux-hardware.org/?probe=16acb0dabc) | Nov 11, 2023 |
| Toshiba       | Satellite L655              | [b3c59942a1](https://linux-hardware.org/?probe=b3c59942a1) | Nov 11, 2023 |
| HP            | Presario CQ62               | [584d709751](https://linux-hardware.org/?probe=584d709751) | Nov 11, 2023 |
| Toshiba       | PORTEGE Z30-A               | [1b3661590f](https://linux-hardware.org/?probe=1b3661590f) | Nov 11, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [13798a5389](https://linux-hardware.org/?probe=13798a5389) | Nov 11, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [b962155541](https://linux-hardware.org/?probe=b962155541) | Nov 11, 2023 |
| Dell          | Precision M6800             | [4ad69afe3a](https://linux-hardware.org/?probe=4ad69afe3a) | Nov 11, 2023 |
| Apple         | MacBookPro9,2               | [e4fd0fa1f0](https://linux-hardware.org/?probe=e4fd0fa1f0) | Nov 10, 2023 |
| HP            | 250 G8 Notebook PC          | [fda2670cc5](https://linux-hardware.org/?probe=fda2670cc5) | Nov 10, 2023 |
| Lenovo        | Z40-70 20366                | [f1968605c1](https://linux-hardware.org/?probe=f1968605c1) | Nov 09, 2023 |
| Acer          | Aspire E1-531               | [6a30b05dcb](https://linux-hardware.org/?probe=6a30b05dcb) | Nov 08, 2023 |
| PEAQ          | PNB C1014-I1B1 MD99447      | [33d5a0aa8c](https://linux-hardware.org/?probe=33d5a0aa8c) | Nov 08, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [cc75144dea](https://linux-hardware.org/?probe=cc75144dea) | Nov 08, 2023 |
| HP            | 250 G8 Notebook PC          | [38b21b9f64](https://linux-hardware.org/?probe=38b21b9f64) | Nov 08, 2023 |
| Acer          | Aspire E5-553G              | [f77e4d524d](https://linux-hardware.org/?probe=f77e4d524d) | Nov 08, 2023 |
| HP            | Compaq 6830s                | [069a45be37](https://linux-hardware.org/?probe=069a45be37) | Nov 08, 2023 |
| Lenovo        | ThinkPad T440p 20AWS08S0... | [b7e993f677](https://linux-hardware.org/?probe=b7e993f677) | Nov 07, 2023 |
| Fujitsu Si... | AMILO Li 1818               | [ab74cc1cc6](https://linux-hardware.org/?probe=ab74cc1cc6) | Nov 07, 2023 |
| Dell          | Venue 11 Pro 5130           | [c2434cadfc](https://linux-hardware.org/?probe=c2434cadfc) | Nov 07, 2023 |
| Dell          | Venue 11 Pro 5130           | [a5628b0f9d](https://linux-hardware.org/?probe=a5628b0f9d) | Nov 07, 2023 |
| Acer          | Aspire ES1-572              | [eea33256f6](https://linux-hardware.org/?probe=eea33256f6) | Nov 07, 2023 |
| Lenovo        | IdeaPad S400u 20213         | [5ddd610c2d](https://linux-hardware.org/?probe=5ddd610c2d) | Nov 06, 2023 |
| Dell          | Venue 11 Pro 5130           | [5d63a1487d](https://linux-hardware.org/?probe=5d63a1487d) | Nov 06, 2023 |
| Acer          | Aspire ES1-521              | [8447756322](https://linux-hardware.org/?probe=8447756322) | Nov 06, 2023 |
| Acer          | Aspire ES1-521              | [af12dd22ba](https://linux-hardware.org/?probe=af12dd22ba) | Nov 06, 2023 |
| Dell          | Venue 11 Pro 5130           | [0facd311dc](https://linux-hardware.org/?probe=0facd311dc) | Nov 05, 2023 |
| Dell          | Venue 11 Pro 5130           | [27740d5118](https://linux-hardware.org/?probe=27740d5118) | Nov 05, 2023 |
| Dell          | Latitude E7450              | [71fe592aa3](https://linux-hardware.org/?probe=71fe592aa3) | Nov 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [4bf4b470a0](https://linux-hardware.org/?probe=4bf4b470a0) | Nov 05, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [8b3f431a00](https://linux-hardware.org/?probe=8b3f431a00) | Nov 05, 2023 |
| Toshiba       | IS 1412                     | [486d28dfeb](https://linux-hardware.org/?probe=486d28dfeb) | Nov 05, 2023 |
| Toshiba       | IS 1412                     | [d423a5c34a](https://linux-hardware.org/?probe=d423a5c34a) | Nov 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [38df9f5382](https://linux-hardware.org/?probe=38df9f5382) | Nov 04, 2023 |
| TrekStor      | Surfbook W2                 | [cfee0c0363](https://linux-hardware.org/?probe=cfee0c0363) | Nov 04, 2023 |
| HP            | 250 G8 Notebook PC          | [7a24e5115a](https://linux-hardware.org/?probe=7a24e5115a) | Nov 04, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [c07d28d9bc](https://linux-hardware.org/?probe=c07d28d9bc) | Nov 04, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [00cab2c4d1](https://linux-hardware.org/?probe=00cab2c4d1) | Nov 04, 2023 |
| Timi          | A35                         | [1baa5932cc](https://linux-hardware.org/?probe=1baa5932cc) | Nov 03, 2023 |
| Dell          | Latitude E6520              | [a0e05f5040](https://linux-hardware.org/?probe=a0e05f5040) | Nov 02, 2023 |
| ASUSTek       | T100TAF                     | [ea9f809740](https://linux-hardware.org/?probe=ea9f809740) | Nov 02, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [4372a2d9eb](https://linux-hardware.org/?probe=4372a2d9eb) | Nov 02, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [fb7f16d298](https://linux-hardware.org/?probe=fb7f16d298) | Nov 02, 2023 |
| ASUSTek       | U36SD                       | [e2045d61a5](https://linux-hardware.org/?probe=e2045d61a5) | Nov 02, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [ef9bc3cc1e](https://linux-hardware.org/?probe=ef9bc3cc1e) | Nov 02, 2023 |
| Acer          | Aspire 5736Z                | [9fff8956bb](https://linux-hardware.org/?probe=9fff8956bb) | Nov 01, 2023 |
| Apple         | MacBookPro3,1               | [73a395f017](https://linux-hardware.org/?probe=73a395f017) | Nov 01, 2023 |
| Sony          | SVS15116GAB                 | [03634a7731](https://linux-hardware.org/?probe=03634a7731) | Oct 30, 2023 |
| MSI           | Delta 15 A5EFK              | [185b65ebc1](https://linux-hardware.org/?probe=185b65ebc1) | Oct 30, 2023 |
| Notebook      | PA70Hx                      | [627ed781b5](https://linux-hardware.org/?probe=627ed781b5) | Oct 30, 2023 |
| HP            | 15                          | [1480b12f56](https://linux-hardware.org/?probe=1480b12f56) | Oct 30, 2023 |
| HP            | Notebook                    | [5538a0e3b2](https://linux-hardware.org/?probe=5538a0e3b2) | Oct 30, 2023 |
| HP            | Pavilion dv4                | [854806c6f4](https://linux-hardware.org/?probe=854806c6f4) | Oct 29, 2023 |
| HP            | ENVY 17                     | [8852bab8c1](https://linux-hardware.org/?probe=8852bab8c1) | Oct 29, 2023 |
| Lenovo        | ThinkPad X270 20HMS1T600    | [97fbe59dd7](https://linux-hardware.org/?probe=97fbe59dd7) | Oct 29, 2023 |
| Notebook      | PA70Hx                      | [e13de47400](https://linux-hardware.org/?probe=e13de47400) | Oct 29, 2023 |
| Lenovo        | ThinkPad E420 1141BTU       | [867e950bca](https://linux-hardware.org/?probe=867e950bca) | Oct 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [a123ac023f](https://linux-hardware.org/?probe=a123ac023f) | Oct 29, 2023 |
| ASUSTek       | ZenBook UX434IQ_Q407IQ      | [97eabba1a8](https://linux-hardware.org/?probe=97eabba1a8) | Oct 28, 2023 |
| Acer          | Aspire V3-772G              | [d48a91cce4](https://linux-hardware.org/?probe=d48a91cce4) | Oct 28, 2023 |
| HP            | ENVY 17                     | [aaa99aaa53](https://linux-hardware.org/?probe=aaa99aaa53) | Oct 27, 2023 |
| HCL Infosy... | HCL ME Laptop               | [a23dc90a3b](https://linux-hardware.org/?probe=a23dc90a3b) | Oct 27, 2023 |
| Thomson       | WWNEO14C-4BK32F             | [516a5ee33b](https://linux-hardware.org/?probe=516a5ee33b) | Oct 27, 2023 |
| ASUSTek       | ZenBook UX434IQ_Q407IQ      | [763e54c87b](https://linux-hardware.org/?probe=763e54c87b) | Oct 26, 2023 |
| HP            | G61                         | [d184a33522](https://linux-hardware.org/?probe=d184a33522) | Oct 26, 2023 |
| HP            | Pavilion g7                 | [4699d107df](https://linux-hardware.org/?probe=4699d107df) | Oct 26, 2023 |
| HP            | 250 G7 Notebook PC          | [3c8f87fe9e](https://linux-hardware.org/?probe=3c8f87fe9e) | Oct 25, 2023 |
| HP            | 250 G8 Notebook PC          | [cd1abadd3a](https://linux-hardware.org/?probe=cd1abadd3a) | Oct 25, 2023 |
| Acer          | Aspire 5738                 | [039878b1b2](https://linux-hardware.org/?probe=039878b1b2) | Oct 24, 2023 |
| Lenovo        | ThinkPad A485 20MVS0X62X    | [52661c1969](https://linux-hardware.org/?probe=52661c1969) | Oct 22, 2023 |
| Dell          | Precision 7530              | [92f2a2c99e](https://linux-hardware.org/?probe=92f2a2c99e) | Oct 22, 2023 |
| ASUSTek       | X453MA                      | [ef8715c7a7](https://linux-hardware.org/?probe=ef8715c7a7) | Oct 21, 2023 |
| Acer          | Nitro AN515-52              | [081a658255](https://linux-hardware.org/?probe=081a658255) | Oct 21, 2023 |
| TrekStor      | Surfbook W2                 | [001d67067b](https://linux-hardware.org/?probe=001d67067b) | Oct 21, 2023 |
| HP            | Laptop 14-cf2xxx            | [ef8c0bb04c](https://linux-hardware.org/?probe=ef8c0bb04c) | Oct 21, 2023 |
| HP            | Laptop 14s-dq2xxx           | [330cbe85c6](https://linux-hardware.org/?probe=330cbe85c6) | Oct 21, 2023 |
| HP            | Pavilion dv6                | [a7ee33da8f](https://linux-hardware.org/?probe=a7ee33da8f) | Oct 21, 2023 |
| Dell          | Inspiron 7560               | [6b9df8da7d](https://linux-hardware.org/?probe=6b9df8da7d) | Oct 21, 2023 |
| ASUSTek       | X453MA                      | [11d8517f7e](https://linux-hardware.org/?probe=11d8517f7e) | Oct 20, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [9ce038aa93](https://linux-hardware.org/?probe=9ce038aa93) | Oct 20, 2023 |
| HP            | Laptop 14-cf2xxx            | [3dd8426b8f](https://linux-hardware.org/?probe=3dd8426b8f) | Oct 20, 2023 |
| Dell          | Latitude 5490               | [cdf021cc62](https://linux-hardware.org/?probe=cdf021cc62) | Oct 19, 2023 |
| ASUSTek       | X751SA                      | [21a2a5b900](https://linux-hardware.org/?probe=21a2a5b900) | Oct 18, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [cde2726f48](https://linux-hardware.org/?probe=cde2726f48) | Oct 18, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [2985805059](https://linux-hardware.org/?probe=2985805059) | Oct 18, 2023 |
| ASUSTek       | X200MA                      | [c1ea75561b](https://linux-hardware.org/?probe=c1ea75561b) | Oct 18, 2023 |
| Sony          | VGN-FZ31Z                   | [9a6fd46a7d](https://linux-hardware.org/?probe=9a6fd46a7d) | Oct 17, 2023 |
| Lenovo        | ThinkPad T420 4236KU9       | [f1e77b51bc](https://linux-hardware.org/?probe=f1e77b51bc) | Oct 17, 2023 |
| Acer          | Aspire A515-57G             | [7116f7edd9](https://linux-hardware.org/?probe=7116f7edd9) | Oct 17, 2023 |
| Acer          | Aspire SW5-012              | [848b8d7c20](https://linux-hardware.org/?probe=848b8d7c20) | Oct 17, 2023 |
| Lenovo        | ThinkPad T440 20B7S1D200    | [43185c1e5b](https://linux-hardware.org/?probe=43185c1e5b) | Oct 16, 2023 |
| Apple         | MacBookPro9,2               | [fd91b9ece9](https://linux-hardware.org/?probe=fd91b9ece9) | Oct 16, 2023 |
| Multilaser    | MLSH1H LINUX                | [e87c9aab74](https://linux-hardware.org/?probe=e87c9aab74) | Oct 16, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [a0f3ae3d1a](https://linux-hardware.org/?probe=a0f3ae3d1a) | Oct 16, 2023 |
| Multilaser    | MLSH1H LINUX                | [0ca88d127f](https://linux-hardware.org/?probe=0ca88d127f) | Oct 16, 2023 |
| HP            | EliteBook 8570p             | [cfc61d2f3c](https://linux-hardware.org/?probe=cfc61d2f3c) | Oct 15, 2023 |
| Lenovo        | IdeaPad Y580 20132          | [77c1531b00](https://linux-hardware.org/?probe=77c1531b00) | Oct 15, 2023 |
| Lenovo        | IdeaPad Y580 20132          | [2960de2715](https://linux-hardware.org/?probe=2960de2715) | Oct 15, 2023 |
| Apple         | MacBookPro11,1              | [d22b6fa2e4](https://linux-hardware.org/?probe=d22b6fa2e4) | Oct 15, 2023 |
| HP            | Pavilion g7                 | [309ca4d5c7](https://linux-hardware.org/?probe=309ca4d5c7) | Oct 15, 2023 |
| HP            | Compaq Presario CQ60        | [c6321b8063](https://linux-hardware.org/?probe=c6321b8063) | Oct 14, 2023 |
| Dell          | Vostro 1015                 | [35a5d0ac7c](https://linux-hardware.org/?probe=35a5d0ac7c) | Oct 14, 2023 |
| Dell          | Vostro 1015                 | [081856b4e9](https://linux-hardware.org/?probe=081856b4e9) | Oct 14, 2023 |
| Apple         | MacBookPro3,1               | [0db9d6a5cf](https://linux-hardware.org/?probe=0db9d6a5cf) | Oct 14, 2023 |
| HP            | OMEN by Gaming Laptop 16... | [c2cbb1c407](https://linux-hardware.org/?probe=c2cbb1c407) | Oct 13, 2023 |
| HP            | 470 17 inch G9              | [d138f8f9f3](https://linux-hardware.org/?probe=d138f8f9f3) | Oct 13, 2023 |
| HP            | ProBook 455 15.6 inch G1... | [cc3dbe7ccd](https://linux-hardware.org/?probe=cc3dbe7ccd) | Oct 12, 2023 |
| Lenovo        | V110-15IAP 80TG             | [314d81343b](https://linux-hardware.org/?probe=314d81343b) | Oct 12, 2023 |
| Schenker      | XMG CORE (REN/M20)          | [48ee28954d](https://linux-hardware.org/?probe=48ee28954d) | Oct 12, 2023 |
| HP            | ProBook 455 15.6 inch G1... | [8c1ef64452](https://linux-hardware.org/?probe=8c1ef64452) | Oct 12, 2023 |
| HP            | Pavilion g7                 | [e276347e0a](https://linux-hardware.org/?probe=e276347e0a) | Oct 12, 2023 |
| Acer          | Aspire A317-55P             | [a4e8b9c99a](https://linux-hardware.org/?probe=a4e8b9c99a) | Oct 12, 2023 |
| HP            | 250 G8 Notebook PC          | [916bfc1646](https://linux-hardware.org/?probe=916bfc1646) | Oct 11, 2023 |
| Acer          | Aspire A317-55P             | [3805200b55](https://linux-hardware.org/?probe=3805200b55) | Oct 11, 2023 |
| Acer          | Aspire 5750                 | [44a7bac1b9](https://linux-hardware.org/?probe=44a7bac1b9) | Oct 10, 2023 |
| Acer          | Aspire A315-55G             | [df54ad11e5](https://linux-hardware.org/?probe=df54ad11e5) | Oct 10, 2023 |
| ASUSTek       | K42F                        | [0d099eb4f7](https://linux-hardware.org/?probe=0d099eb4f7) | Oct 10, 2023 |
| Toshiba       | Satellite Pro R50-B         | [9b41869902](https://linux-hardware.org/?probe=9b41869902) | Oct 09, 2023 |
| Apple         | MacBookPro4,1               | [407c6f0e29](https://linux-hardware.org/?probe=407c6f0e29) | Oct 09, 2023 |
| Acer          | Aspire A315-55G             | [53e4e70567](https://linux-hardware.org/?probe=53e4e70567) | Oct 09, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [332ce6061d](https://linux-hardware.org/?probe=332ce6061d) | Oct 09, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | [8984311ce7](https://linux-hardware.org/?probe=8984311ce7) | Oct 09, 2023 |
| HP            | Pavilion 15                 | [ae1e07dd63](https://linux-hardware.org/?probe=ae1e07dd63) | Oct 08, 2023 |
| Apple         | MacBookPro12,1              | [bd6094c5cd](https://linux-hardware.org/?probe=bd6094c5cd) | Oct 08, 2023 |
| Lenovo        | ThinkPad T460s 20FAS08W0... | [24dee8bc07](https://linux-hardware.org/?probe=24dee8bc07) | Oct 07, 2023 |
| UMAX          | N14R                        | [4ac10723f5](https://linux-hardware.org/?probe=4ac10723f5) | Oct 07, 2023 |
| UMAX          | N14R                        | [9852750745](https://linux-hardware.org/?probe=9852750745) | Oct 07, 2023 |
| Alienware     | M14xR2                      | [3b7dd3717c](https://linux-hardware.org/?probe=3b7dd3717c) | Oct 07, 2023 |
| Dell          | Precision 5530              | [38fdcea75f](https://linux-hardware.org/?probe=38fdcea75f) | Oct 06, 2023 |
| Thomson       | GEN360-4C128BK              | [ec04ddb0ba](https://linux-hardware.org/?probe=ec04ddb0ba) | Oct 06, 2023 |
| Dell          | Vostro 3550                 | [d68de2a20e](https://linux-hardware.org/?probe=d68de2a20e) | Oct 06, 2023 |
| HUAWEI        | BOHB-WAX9                   | [7add8932c3](https://linux-hardware.org/?probe=7add8932c3) | Oct 06, 2023 |
| Apple         | MacBookPro12,1              | [d343f99b47](https://linux-hardware.org/?probe=d343f99b47) | Oct 06, 2023 |
| Medion        | E4251 MD61435               | [b8f2dc6919](https://linux-hardware.org/?probe=b8f2dc6919) | Oct 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | [8313e4fb72](https://linux-hardware.org/?probe=8313e4fb72) | Oct 05, 2023 |
| Dell          | Latitude 7480               | [7eec2f8e4e](https://linux-hardware.org/?probe=7eec2f8e4e) | Oct 05, 2023 |
| Dell          | Latitude 7480               | [a80bc8f591](https://linux-hardware.org/?probe=a80bc8f591) | Oct 05, 2023 |
| Acer          | Aspire M3-581G              | [040dc9b84b](https://linux-hardware.org/?probe=040dc9b84b) | Oct 04, 2023 |
| Dell          | G3 3579                     | [7730315a91](https://linux-hardware.org/?probe=7730315a91) | Oct 04, 2023 |
| Acer          | Aspire ES1-521              | [1e6ec4d559](https://linux-hardware.org/?probe=1e6ec4d559) | Oct 03, 2023 |
| HP            | EliteBook 820 G3            | [c474599b04](https://linux-hardware.org/?probe=c474599b04) | Oct 03, 2023 |
| MSI           | Bravo 15 A4DDR              | [0ebc5c48b5](https://linux-hardware.org/?probe=0ebc5c48b5) | Oct 03, 2023 |
| MSI           | Bravo 15 A4DDR              | [00afde76db](https://linux-hardware.org/?probe=00afde76db) | Oct 03, 2023 |
| HP            | Pavilion dv6                | [b210c95b8e](https://linux-hardware.org/?probe=b210c95b8e) | Oct 02, 2023 |
| HP            | Pavilion dv6                | [2519f8a695](https://linux-hardware.org/?probe=2519f8a695) | Oct 02, 2023 |
| Dell          | XPS 13 9370                 | [320836ef04](https://linux-hardware.org/?probe=320836ef04) | Oct 02, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21HDC... | [aa2d376e85](https://linux-hardware.org/?probe=aa2d376e85) | Oct 02, 2023 |
| HP            | 470 17 inch G9              | [c6043cc6cc](https://linux-hardware.org/?probe=c6043cc6cc) | Oct 01, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [127980fc54](https://linux-hardware.org/?probe=127980fc54) | Oct 01, 2023 |
| Toshiba       | Satellite C870-1C2          | [d9750c9040](https://linux-hardware.org/?probe=d9750c9040) | Sep 30, 2023 |
| Apple         | MacBookPro5,3               | [0669d0020d](https://linux-hardware.org/?probe=0669d0020d) | Sep 30, 2023 |
| Apple         | MacBookPro8,2               | [237492c356](https://linux-hardware.org/?probe=237492c356) | Sep 30, 2023 |
| Apple         | MacBookPro5,3               | [d249d5e114](https://linux-hardware.org/?probe=d249d5e114) | Sep 30, 2023 |
| Lenovo        | IdeaPad Slim 3 15IRU8 82... | [e9dd0291e0](https://linux-hardware.org/?probe=e9dd0291e0) | Sep 29, 2023 |
| ASUSTek       | X551MA                      | [8ba160ee59](https://linux-hardware.org/?probe=8ba160ee59) | Sep 29, 2023 |
| Lenovo        | ThinkPad R60 9461DXG        | [4f74530d68](https://linux-hardware.org/?probe=4f74530d68) | Sep 28, 2023 |
| Lenovo        | ThinkPad R60 9461DXG        | [5fb1e549ea](https://linux-hardware.org/?probe=5fb1e549ea) | Sep 28, 2023 |
| Acer          | Aspire 5736Z                | [cfd174dbe0](https://linux-hardware.org/?probe=cfd174dbe0) | Sep 28, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | [c717c1ab13](https://linux-hardware.org/?probe=c717c1ab13) | Sep 28, 2023 |
| Lenovo        | ThinkPad E14 20RA0050US     | [097539dde8](https://linux-hardware.org/?probe=097539dde8) | Sep 27, 2023 |
| Medion        | E6431 MD60112               | [f1fee9da62](https://linux-hardware.org/?probe=f1fee9da62) | Sep 27, 2023 |
| HP            | Notebook                    | [4690fda15e](https://linux-hardware.org/?probe=4690fda15e) | Sep 27, 2023 |
| Apple         | MacBookPro11,1              | [7463d4f447](https://linux-hardware.org/?probe=7463d4f447) | Sep 26, 2023 |
| Dell          | Vostro 3550                 | [f87aee7d8f](https://linux-hardware.org/?probe=f87aee7d8f) | Sep 26, 2023 |
| Dell          | Vostro 3550                 | [7214093885](https://linux-hardware.org/?probe=7214093885) | Sep 26, 2023 |
| Dell          | Inspiron 5459               | [1095c770f0](https://linux-hardware.org/?probe=1095c770f0) | Sep 26, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [0c8a57738d](https://linux-hardware.org/?probe=0c8a57738d) | Sep 25, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [a778013e21](https://linux-hardware.org/?probe=a778013e21) | Sep 25, 2023 |
| Intel         | W7645                       | [8a83c23785](https://linux-hardware.org/?probe=8a83c23785) | Sep 25, 2023 |
| Dell          | Inspiron 14 5410            | [863dfa9b96](https://linux-hardware.org/?probe=863dfa9b96) | Sep 25, 2023 |
| Apple         | MacBookAir6,1               | [1bee981c70](https://linux-hardware.org/?probe=1bee981c70) | Sep 25, 2023 |
| Dell          | Inspiron 3581               | [11796876dd](https://linux-hardware.org/?probe=11796876dd) | Sep 25, 2023 |
| Sony          | SVF14A15CXB                 | [cbce21a887](https://linux-hardware.org/?probe=cbce21a887) | Sep 25, 2023 |
| Alienware     | M17x                        | [5c6b700486](https://linux-hardware.org/?probe=5c6b700486) | Sep 25, 2023 |
| Samsung       | 3570R/370R/470R/450R/510... | [6d75f2f29b](https://linux-hardware.org/?probe=6d75f2f29b) | Sep 24, 2023 |
| HUAWEI        | KLVL-WXXW                   | [f2a543d0dd](https://linux-hardware.org/?probe=f2a543d0dd) | Sep 24, 2023 |
| Dell          | XPS 13 9360                 | [6897fc6f5a](https://linux-hardware.org/?probe=6897fc6f5a) | Sep 23, 2023 |
| ASUSTek       | K50IJ                       | [02a39de387](https://linux-hardware.org/?probe=02a39de387) | Sep 23, 2023 |
| Lenovo        | ThinkPad E575 20H8000HUS    | [8b5a2354c5](https://linux-hardware.org/?probe=8b5a2354c5) | Sep 23, 2023 |
| Acer          | Aspire A514-54              | [c74511d498](https://linux-hardware.org/?probe=c74511d498) | Sep 22, 2023 |
| Toshiba       | Satellite Pro R40-D         | [d33d1b7b77](https://linux-hardware.org/?probe=d33d1b7b77) | Sep 22, 2023 |
| Primux Tec... | Primux_1406F_W10            | [a1911e4e9a](https://linux-hardware.org/?probe=a1911e4e9a) | Sep 22, 2023 |
| Primux Tec... | Primux_1406F_W10            | [c267e8d9a3](https://linux-hardware.org/?probe=c267e8d9a3) | Sep 22, 2023 |
| HP            | 250 G7 Notebook PC          | [cc25c24fa5](https://linux-hardware.org/?probe=cc25c24fa5) | Sep 21, 2023 |
| HP            | 255 G8 Notebook PC          | [d92a4fb2af](https://linux-hardware.org/?probe=d92a4fb2af) | Sep 21, 2023 |
| Dell          | Inspiron 3576               | [a76faead17](https://linux-hardware.org/?probe=a76faead17) | Sep 21, 2023 |
| Acer          | TravelMate P246-MG          | [197b2c18c7](https://linux-hardware.org/?probe=197b2c18c7) | Sep 21, 2023 |
| Acer          | Aspire VN7-572G             | [8936ef0637](https://linux-hardware.org/?probe=8936ef0637) | Sep 21, 2023 |
| Lenovo        | ThinkPad T570 20HAS1PC00    | [218325e9e3](https://linux-hardware.org/?probe=218325e9e3) | Sep 21, 2023 |
| Lenovo        | ThinkPad T560 20FJS2BX00    | [85a0203a02](https://linux-hardware.org/?probe=85a0203a02) | Sep 20, 2023 |
| Lenovo        | ThinkPad T560 20FJS2BX00    | [c96d3bf498](https://linux-hardware.org/?probe=c96d3bf498) | Sep 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [162a680d7d](https://linux-hardware.org/?probe=162a680d7d) | Sep 19, 2023 |
| Acer          | Aspire 5750                 | [9fb8b99e70](https://linux-hardware.org/?probe=9fb8b99e70) | Sep 19, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [ca70cb035f](https://linux-hardware.org/?probe=ca70cb035f) | Sep 19, 2023 |
| HP            | Pavilion dv7                | [2bbc187582](https://linux-hardware.org/?probe=2bbc187582) | Sep 19, 2023 |
| HP            | Laptop 15-ef1xxx            | [5ec304bdb6](https://linux-hardware.org/?probe=5ec304bdb6) | Sep 19, 2023 |
| HP            | Laptop 15-fc0xxx            | [bb3c1bf2b9](https://linux-hardware.org/?probe=bb3c1bf2b9) | Sep 18, 2023 |
| HP            | EliteBook 745 G5            | [d03b8c1860](https://linux-hardware.org/?probe=d03b8c1860) | Sep 18, 2023 |
| HP            | Laptop 15-fc0xxx            | [4e845095f4](https://linux-hardware.org/?probe=4e845095f4) | Sep 18, 2023 |
| Dell          | XPS 13 9370                 | [002401cab6](https://linux-hardware.org/?probe=002401cab6) | Sep 18, 2023 |
| Hometech      | Ultra Tab 8W                | [065988c338](https://linux-hardware.org/?probe=065988c338) | Sep 17, 2023 |
| Hometech      | Ultra Tab 8W                | [1a9e79b92e](https://linux-hardware.org/?probe=1a9e79b92e) | Sep 17, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [ef3516c115](https://linux-hardware.org/?probe=ef3516c115) | Sep 17, 2023 |
| Acer          | Aspire 5750                 | [e639402c30](https://linux-hardware.org/?probe=e639402c30) | Sep 17, 2023 |
| Apple         | MacBook4,1                  | [3774dfea8e](https://linux-hardware.org/?probe=3774dfea8e) | Sep 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [87f26cde55](https://linux-hardware.org/?probe=87f26cde55) | Sep 16, 2023 |
| HP            | 250 G7 Notebook PC          | [72503b214c](https://linux-hardware.org/?probe=72503b214c) | Sep 16, 2023 |
| Acer          | Aspire 5755G                | [16c14700d3](https://linux-hardware.org/?probe=16c14700d3) | Sep 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [00fd2287c0](https://linux-hardware.org/?probe=00fd2287c0) | Sep 16, 2023 |
| Apple         | MacBookPro3,1               | [f6be487f38](https://linux-hardware.org/?probe=f6be487f38) | Sep 16, 2023 |
| ASUSTek       | K54C                        | [23a000c4d4](https://linux-hardware.org/?probe=23a000c4d4) | Sep 16, 2023 |
| Itautec       | Infoway                     | [d4a8bc6420](https://linux-hardware.org/?probe=d4a8bc6420) | Sep 14, 2023 |
| Acer          | Aspire 5735                 | [9d3ceb6624](https://linux-hardware.org/?probe=9d3ceb6624) | Sep 14, 2023 |
| HP            | Notebook                    | [29f1834722](https://linux-hardware.org/?probe=29f1834722) | Sep 14, 2023 |
| MSI           | Bravo 15 A4DDR              | [bba9e61120](https://linux-hardware.org/?probe=bba9e61120) | Sep 13, 2023 |
| Acer          | Aspire 5750ZG               | [c9ce4cde54](https://linux-hardware.org/?probe=c9ce4cde54) | Sep 13, 2023 |
| Dell          | Inspiron 5590               | [32b69241bf](https://linux-hardware.org/?probe=32b69241bf) | Sep 13, 2023 |
| Sony          | VPCEB1E1E                   | [cbd095ee01](https://linux-hardware.org/?probe=cbd095ee01) | Sep 12, 2023 |
| Acer          | Aspire 5750ZG               | [9029730ffb](https://linux-hardware.org/?probe=9029730ffb) | Sep 12, 2023 |
| Acer          | Aspire A514-54              | [8ddb560fdc](https://linux-hardware.org/?probe=8ddb560fdc) | Sep 12, 2023 |
| Apple         | MacBookPro8,2               | [5358fa25ef](https://linux-hardware.org/?probe=5358fa25ef) | Sep 12, 2023 |
| Dell          | Inspiron 5748               | [21baf66690](https://linux-hardware.org/?probe=21baf66690) | Sep 11, 2023 |
| HP            | Pavilion dv7                | [e7c7395c7b](https://linux-hardware.org/?probe=e7c7395c7b) | Sep 11, 2023 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | [26fc33cb75](https://linux-hardware.org/?probe=26fc33cb75) | Sep 10, 2023 |
| Dell          | Latitude E5430 non-vPro     | [b211a425b2](https://linux-hardware.org/?probe=b211a425b2) | Sep 10, 2023 |
| ASUSTek       | X541UA                      | [a8184365b8](https://linux-hardware.org/?probe=a8184365b8) | Sep 10, 2023 |
| Lenovo        | V110-14IAP 80TF             | [3ee6c9a460](https://linux-hardware.org/?probe=3ee6c9a460) | Sep 09, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [382cd978ab](https://linux-hardware.org/?probe=382cd978ab) | Sep 08, 2023 |
| Lenovo        | ThinkPad T430 2349H2G       | [1d9d7c7f78](https://linux-hardware.org/?probe=1d9d7c7f78) | Sep 08, 2023 |
| HP            | 240 G8 Notebook PC          | [62735c1cd9](https://linux-hardware.org/?probe=62735c1cd9) | Sep 07, 2023 |
| HP            | Laptop 14-dq1xxx            | [125a7f7c0d](https://linux-hardware.org/?probe=125a7f7c0d) | Sep 07, 2023 |
| Dell          | Inspiron 5559               | [0428af4d14](https://linux-hardware.org/?probe=0428af4d14) | Sep 06, 2023 |
| HP            | ProBook 650 G5              | [5e6e5cd047](https://linux-hardware.org/?probe=5e6e5cd047) | Sep 06, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [0fdeca1313](https://linux-hardware.org/?probe=0fdeca1313) | Sep 06, 2023 |
| Toshiba       | Satellite A210              | [54f5fb9c03](https://linux-hardware.org/?probe=54f5fb9c03) | Sep 06, 2023 |
| Framework     | Laptop                      | [bd2852cd9e](https://linux-hardware.org/?probe=bd2852cd9e) | Sep 05, 2023 |
| Toshiba       | Satellite C70D-A            | [36070747fd](https://linux-hardware.org/?probe=36070747fd) | Sep 04, 2023 |
| Apple         | MacBookPro8,2               | [371c148953](https://linux-hardware.org/?probe=371c148953) | Sep 04, 2023 |
| Dell          | Latitude E6530              | [e1aa22b8b9](https://linux-hardware.org/?probe=e1aa22b8b9) | Sep 04, 2023 |
| Dell          | G15 5511                    | [e6afc56020](https://linux-hardware.org/?probe=e6afc56020) | Sep 03, 2023 |
| Lenovo        | Legion S7 16IAH7 82TF       | [f4c15b0551](https://linux-hardware.org/?probe=f4c15b0551) | Sep 03, 2023 |
| Toshiba       | Satellite L50-A-1DL         | [d46487843e](https://linux-hardware.org/?probe=d46487843e) | Sep 03, 2023 |
| Dell          | Vostro 14-3468              | [2f75949c09](https://linux-hardware.org/?probe=2f75949c09) | Sep 03, 2023 |
| Apple         | MacBookPro16,2              | [9ab1a9731d](https://linux-hardware.org/?probe=9ab1a9731d) | Sep 03, 2023 |
| Apple         | MacBookPro16,2              | [78d7ccad98](https://linux-hardware.org/?probe=78d7ccad98) | Sep 02, 2023 |
| HP            | EliteBook 840 G5            | [b2b0d3e018](https://linux-hardware.org/?probe=b2b0d3e018) | Sep 02, 2023 |
| Gigabyte      | G5 KF                       | [b38cdf7987](https://linux-hardware.org/?probe=b38cdf7987) | Sep 01, 2023 |
| Gigabyte      | G5 KF                       | [3eef6bf0d1](https://linux-hardware.org/?probe=3eef6bf0d1) | Sep 01, 2023 |
| Dell          | Latitude 5400               | [dee2becb07](https://linux-hardware.org/?probe=dee2becb07) | Sep 01, 2023 |
| Lenovo        | ThinkPad S5-S540 20B3006... | [e33b222d6c](https://linux-hardware.org/?probe=e33b222d6c) | Sep 01, 2023 |
| HP            | ProBook 4740s               | [0ab7fe639e](https://linux-hardware.org/?probe=0ab7fe639e) | Sep 01, 2023 |
| HP            | EliteBook 2570p             | [436e4af3ce](https://linux-hardware.org/?probe=436e4af3ce) | Aug 31, 2023 |
| HP            | 15                          | [39567282e3](https://linux-hardware.org/?probe=39567282e3) | Aug 31, 2023 |
| HP            | Pavilion dv4                | [c84d5215be](https://linux-hardware.org/?probe=c84d5215be) | Aug 30, 2023 |
| Sony          | VPCEE23FX                   | [65714e4d48](https://linux-hardware.org/?probe=65714e4d48) | Aug 30, 2023 |
| Apple         | MacBookPro11,5              | [643e8194ea](https://linux-hardware.org/?probe=643e8194ea) | Aug 30, 2023 |
| Dell          | Venue 11 Pro 5130           | [38c58406bc](https://linux-hardware.org/?probe=38c58406bc) | Aug 29, 2023 |
| ASUSTek       | K93SV                       | [01701d7ab0](https://linux-hardware.org/?probe=01701d7ab0) | Aug 29, 2023 |
| ASUSTek       | K93SV                       | [6da5e2d119](https://linux-hardware.org/?probe=6da5e2d119) | Aug 29, 2023 |
| Dell          | Precision 7710              | [9b92626f63](https://linux-hardware.org/?probe=9b92626f63) | Aug 29, 2023 |
| Acer          | Acadia V1.45                | [4bc36b4d27](https://linux-hardware.org/?probe=4bc36b4d27) | Aug 29, 2023 |
| HP            | Laptop 14-dq1xxx            | [8e13da67ed](https://linux-hardware.org/?probe=8e13da67ed) | Aug 28, 2023 |
| Lenovo        | Yoga 3 14 80JH              | [5268d75df2](https://linux-hardware.org/?probe=5268d75df2) | Aug 28, 2023 |
| Lenovo        | ThinkPad P51s W10DG 20JY... | [4c01a3be17](https://linux-hardware.org/?probe=4c01a3be17) | Aug 28, 2023 |
| HP            | Laptop 14-dk1xxx            | [bdd515fe27](https://linux-hardware.org/?probe=bdd515fe27) | Aug 28, 2023 |
| Lenovo        | ThinkPad P51s W10DG 20JY... | [783bbb68e6](https://linux-hardware.org/?probe=783bbb68e6) | Aug 27, 2023 |
| TERRA         | TERRAPC                     | [2031fd343b](https://linux-hardware.org/?probe=2031fd343b) | Aug 27, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [7e9c9debdf](https://linux-hardware.org/?probe=7e9c9debdf) | Aug 26, 2023 |
| Chuwi         | GemiBook Pro                | [06f19f4198](https://linux-hardware.org/?probe=06f19f4198) | Aug 26, 2023 |
| HP            | Pavilion dv7                | [6fbf874054](https://linux-hardware.org/?probe=6fbf874054) | Aug 26, 2023 |
| Acer          | Aspire A315-56              | [e212f5bc28](https://linux-hardware.org/?probe=e212f5bc28) | Aug 25, 2023 |
| Google        | Rammus                      | [28554e7ce5](https://linux-hardware.org/?probe=28554e7ce5) | Aug 25, 2023 |
| HP            | ProBook 640 G4              | [3b75cf22fb](https://linux-hardware.org/?probe=3b75cf22fb) | Aug 25, 2023 |
| TERRA         | TERRAPC                     | [b33c6ce6e8](https://linux-hardware.org/?probe=b33c6ce6e8) | Aug 24, 2023 |
| Lenovo        | ThinkPad Edge 25453BG       | [188af952b0](https://linux-hardware.org/?probe=188af952b0) | Aug 24, 2023 |
| HP            | ProBook 4740s               | [f9e2a275da](https://linux-hardware.org/?probe=f9e2a275da) | Aug 24, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [64859dd75d](https://linux-hardware.org/?probe=64859dd75d) | Aug 24, 2023 |
| ASUSTek       | X756UQ                      | [0ff5520460](https://linux-hardware.org/?probe=0ff5520460) | Aug 22, 2023 |
| Lenovo        | ThinkPad P51 20HJS3MY00     | [010dac0caa](https://linux-hardware.org/?probe=010dac0caa) | Aug 22, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [2a05992a61](https://linux-hardware.org/?probe=2a05992a61) | Aug 21, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [a440d57d28](https://linux-hardware.org/?probe=a440d57d28) | Aug 21, 2023 |
| Dell          | Precision M4700             | [9ec95d5a4d](https://linux-hardware.org/?probe=9ec95d5a4d) | Aug 21, 2023 |
| HP            | Notebook                    | [5b7ff7f278](https://linux-hardware.org/?probe=5b7ff7f278) | Aug 20, 2023 |
| Apple         | MacBookPro8,1               | [41edd1a16e](https://linux-hardware.org/?probe=41edd1a16e) | Aug 20, 2023 |
| Dell          | Latitude 3350               | [e86ce20d6d](https://linux-hardware.org/?probe=e86ce20d6d) | Aug 20, 2023 |
| Lenovo        | Unknown                     | [fbbadac782](https://linux-hardware.org/?probe=fbbadac782) | Aug 20, 2023 |
| Lenovo        | ThinkPad Edge 0578A66       | [6b3703818a](https://linux-hardware.org/?probe=6b3703818a) | Aug 20, 2023 |
| Alienware     | 17                          | [9e7015d530](https://linux-hardware.org/?probe=9e7015d530) | Aug 20, 2023 |
| Apple         | MacBookPro4,1               | [1c57edc329](https://linux-hardware.org/?probe=1c57edc329) | Aug 19, 2023 |
| Sony          | VPCF13Z1E                   | [98c9e71be9](https://linux-hardware.org/?probe=98c9e71be9) | Aug 19, 2023 |
| Apple         | MacBookPro5,2               | [2c20d038ca](https://linux-hardware.org/?probe=2c20d038ca) | Aug 19, 2023 |
| Acer          | Swift SF514-52T             | [9cd2857c01](https://linux-hardware.org/?probe=9cd2857c01) | Aug 18, 2023 |
| ASUSTek       | X550ZA                      | [7f23195701](https://linux-hardware.org/?probe=7f23195701) | Aug 18, 2023 |
| Lenovo        | Flex 2-15 20405             | [77942ee5db](https://linux-hardware.org/?probe=77942ee5db) | Aug 18, 2023 |
| Acer          | Aspire 5755G                | [720c3bfa88](https://linux-hardware.org/?probe=720c3bfa88) | Aug 18, 2023 |
| Lenovo        | G40-30 80FY                 | [d14c477dc9](https://linux-hardware.org/?probe=d14c477dc9) | Aug 18, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | [04ebdc3ec0](https://linux-hardware.org/?probe=04ebdc3ec0) | Aug 18, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [7092a32ce5](https://linux-hardware.org/?probe=7092a32ce5) | Aug 17, 2023 |
| Dell          | G3 3579                     | [58866ca1fb](https://linux-hardware.org/?probe=58866ca1fb) | Aug 17, 2023 |
| TAGTech       | TAGITOP-UNI C               | [d7402c2c8d](https://linux-hardware.org/?probe=d7402c2c8d) | Aug 17, 2023 |
| TAGTech       | TAGITOP-UNI C               | [1cccdef7f4](https://linux-hardware.org/?probe=1cccdef7f4) | Aug 17, 2023 |
| Google        | Coral                       | [f8ed9b3bda](https://linux-hardware.org/?probe=f8ed9b3bda) | Aug 17, 2023 |
| Lenovo        | ThinkPad T480 20L5S04F00    | [7eb670d219](https://linux-hardware.org/?probe=7eb670d219) | Aug 17, 2023 |
| Lenovo        | G40-30 80FY                 | [6574b3e96d](https://linux-hardware.org/?probe=6574b3e96d) | Aug 16, 2023 |
| Apple         | MacBookPro5,2               | [86c85e57c2](https://linux-hardware.org/?probe=86c85e57c2) | Aug 16, 2023 |
| HP            | OMEN by Laptop              | [b31bf50c6e](https://linux-hardware.org/?probe=b31bf50c6e) | Aug 16, 2023 |
| Dell          | Latitude D630               | [878b00d959](https://linux-hardware.org/?probe=878b00d959) | Aug 15, 2023 |
| HP            | 15                          | [645730bff3](https://linux-hardware.org/?probe=645730bff3) | Aug 15, 2023 |
| HP            | 15                          | [08fc74cb7b](https://linux-hardware.org/?probe=08fc74cb7b) | Aug 15, 2023 |
| Sony          | VGN-SR19VN                  | [7adc151adb](https://linux-hardware.org/?probe=7adc151adb) | Aug 15, 2023 |
| Lenovo        | ThinkPad T510 43842RG       | [9b2f268192](https://linux-hardware.org/?probe=9b2f268192) | Aug 15, 2023 |
| Medion        | E15301                      | [e42771be29](https://linux-hardware.org/?probe=e42771be29) | Aug 14, 2023 |
| HP            | Laptop 14-dq1xxx            | [102a6b136f](https://linux-hardware.org/?probe=102a6b136f) | Aug 14, 2023 |
| Lenovo        | Legion R9000P2021H 82JQ     | [777c4f7fb8](https://linux-hardware.org/?probe=777c4f7fb8) | Aug 13, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [c692882ce4](https://linux-hardware.org/?probe=c692882ce4) | Aug 13, 2023 |
| AMI           | Unknown                     | [326999bd6b](https://linux-hardware.org/?probe=326999bd6b) | Aug 12, 2023 |
| AMI           | Unknown                     | [614b443c5c](https://linux-hardware.org/?probe=614b443c5c) | Aug 12, 2023 |
| HP            | 350 G2                      | [f0fa8865d3](https://linux-hardware.org/?probe=f0fa8865d3) | Aug 12, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [71f554fd2c](https://linux-hardware.org/?probe=71f554fd2c) | Aug 12, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [edd42a9a6d](https://linux-hardware.org/?probe=edd42a9a6d) | Aug 12, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | [5ba59f878a](https://linux-hardware.org/?probe=5ba59f878a) | Aug 12, 2023 |
| Acer          | One Z1402                   | [9fd6a2d41b](https://linux-hardware.org/?probe=9fd6a2d41b) | Aug 12, 2023 |
| Unknown       | Unknown                     | [b68d99fd89](https://linux-hardware.org/?probe=b68d99fd89) | Aug 11, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [48a0f64b34](https://linux-hardware.org/?probe=48a0f64b34) | Aug 11, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [a708832571](https://linux-hardware.org/?probe=a708832571) | Aug 11, 2023 |
| HP            | 350 G2                      | [dde52cb361](https://linux-hardware.org/?probe=dde52cb361) | Aug 10, 2023 |
| Clevo         | W251EFQ/W270EFQ             | [cde80ecaf6](https://linux-hardware.org/?probe=cde80ecaf6) | Aug 10, 2023 |
| HP            | ProBook 450 G6              | [c205f19d5e](https://linux-hardware.org/?probe=c205f19d5e) | Aug 09, 2023 |
| HP            | 350 G2                      | [3b79bb8a69](https://linux-hardware.org/?probe=3b79bb8a69) | Aug 09, 2023 |
| HP            | Presario CQ56               | [cf373b9083](https://linux-hardware.org/?probe=cf373b9083) | Aug 09, 2023 |
| HP            | Laptop 14-dk1xxx            | [7c59be984f](https://linux-hardware.org/?probe=7c59be984f) | Aug 09, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [03a4763a96](https://linux-hardware.org/?probe=03a4763a96) | Aug 08, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [de86921bce](https://linux-hardware.org/?probe=de86921bce) | Aug 08, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [c90663d505](https://linux-hardware.org/?probe=c90663d505) | Aug 08, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [87ee840e89](https://linux-hardware.org/?probe=87ee840e89) | Aug 07, 2023 |
| LG Electro... | 14Z90N-V.AA78B              | [af79c7f5f5](https://linux-hardware.org/?probe=af79c7f5f5) | Aug 07, 2023 |
| Apple         | MacBookPro14,1              | [72a4a0eed2](https://linux-hardware.org/?probe=72a4a0eed2) | Aug 06, 2023 |
| ASUSTek       | X405UA                      | [97acf73dea](https://linux-hardware.org/?probe=97acf73dea) | Aug 06, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [c40308638c](https://linux-hardware.org/?probe=c40308638c) | Aug 05, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | [8b6db0bfbb](https://linux-hardware.org/?probe=8b6db0bfbb) | Aug 05, 2023 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [dbbf788e9d](https://linux-hardware.org/?probe=dbbf788e9d) | Aug 05, 2023 |
| HP            | EliteBook 8440p             | [5f0be846f0](https://linux-hardware.org/?probe=5f0be846f0) | Aug 05, 2023 |
| Dell          | Venue 11 Pro 7140           | [7188a418fc](https://linux-hardware.org/?probe=7188a418fc) | Aug 05, 2023 |
| HP            | EliteBook 8460p             | [db336dcf75](https://linux-hardware.org/?probe=db336dcf75) | Aug 05, 2023 |
| Itautec       | Infoway                     | [1708f5baae](https://linux-hardware.org/?probe=1708f5baae) | Aug 04, 2023 |
| GPD           | G1621-02                    | [d7361e9896](https://linux-hardware.org/?probe=d7361e9896) | Aug 04, 2023 |
| Apple         | MacBook8,1                  | [cf6d77d650](https://linux-hardware.org/?probe=cf6d77d650) | Aug 04, 2023 |
| Dell          | Latitude 7490               | [955c961132](https://linux-hardware.org/?probe=955c961132) | Aug 04, 2023 |
| Apple         | MacBookPro8,1               | [61cb65a2e9](https://linux-hardware.org/?probe=61cb65a2e9) | Aug 04, 2023 |
| Dell          | Inspiron 3531               | [f011e5c6cf](https://linux-hardware.org/?probe=f011e5c6cf) | Aug 03, 2023 |
| Notebook      | NJ50_70CU                   | [59cd10f50e](https://linux-hardware.org/?probe=59cd10f50e) | Aug 02, 2023 |
| Acer          | Aspire M3-581G              | [82814fbe1e](https://linux-hardware.org/?probe=82814fbe1e) | Aug 02, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [37fe1d55f8](https://linux-hardware.org/?probe=37fe1d55f8) | Aug 02, 2023 |
| HP            | Pavilion dv7                | [bd9bc8e7a6](https://linux-hardware.org/?probe=bd9bc8e7a6) | Aug 02, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [ee5b34b232](https://linux-hardware.org/?probe=ee5b34b232) | Aug 02, 2023 |
| ASUSTek       | K54C                        | [f4fcf79e7e](https://linux-hardware.org/?probe=f4fcf79e7e) | Aug 02, 2023 |
| Dell          | Inspiron 5577               | [1204832e26](https://linux-hardware.org/?probe=1204832e26) | Aug 01, 2023 |
| Dell          | Inspiron 5577               | [219723a17d](https://linux-hardware.org/?probe=219723a17d) | Aug 01, 2023 |
| Dell          | Latitude E5470              | [3be826cec4](https://linux-hardware.org/?probe=3be826cec4) | Aug 01, 2023 |
| HP            | Stream Laptop 14-cb1XX      | [957e1805d3](https://linux-hardware.org/?probe=957e1805d3) | Aug 01, 2023 |
| HP            | Stream Laptop 14-cb1XX      | [a522e7336c](https://linux-hardware.org/?probe=a522e7336c) | Aug 01, 2023 |
| MSI           | GE72MVR 7RG                 | [d935650def](https://linux-hardware.org/?probe=d935650def) | Jul 31, 2023 |
| Dell          | Inspiron 3421               | [d1651e3e43](https://linux-hardware.org/?probe=d1651e3e43) | Jul 31, 2023 |
| Chuwi         | GemiBook Pro                | [d4efd6692b](https://linux-hardware.org/?probe=d4efd6692b) | Jul 30, 2023 |
| Apple         | MacBookPro4,1               | [eedbe7eb59](https://linux-hardware.org/?probe=eedbe7eb59) | Jul 30, 2023 |
| Apple         | MacBookAir5,2               | [1a77aeef9d](https://linux-hardware.org/?probe=1a77aeef9d) | Jul 30, 2023 |
| Apple         | MacBookAir5,2               | [a6e35103c8](https://linux-hardware.org/?probe=a6e35103c8) | Jul 30, 2023 |
| Sony          | VPCF13Z1E                   | [e52969e6a8](https://linux-hardware.org/?probe=e52969e6a8) | Jul 30, 2023 |
| MSI           | GS73VR 7RF                  | [9df7170f38](https://linux-hardware.org/?probe=9df7170f38) | Jul 29, 2023 |
| HP            | Pavilion dv4                | [47e9cba85c](https://linux-hardware.org/?probe=47e9cba85c) | Jul 29, 2023 |
| Dell          | XPS 13 9350                 | [472c0bf0b0](https://linux-hardware.org/?probe=472c0bf0b0) | Jul 29, 2023 |
| Dell          | XPS 13 9350                 | [2da43364f8](https://linux-hardware.org/?probe=2da43364f8) | Jul 29, 2023 |
| ASUSTek       | K53U                        | [c1b84117db](https://linux-hardware.org/?probe=c1b84117db) | Jul 29, 2023 |
| HP            | Pavilion 15                 | [df29d1164c](https://linux-hardware.org/?probe=df29d1164c) | Jul 29, 2023 |
| HP            | Pavilion 15                 | [804d28484b](https://linux-hardware.org/?probe=804d28484b) | Jul 29, 2023 |
| HP            | ZBook 15 G5                 | [dfe51162d1](https://linux-hardware.org/?probe=dfe51162d1) | Jul 29, 2023 |
| HP            | Pavilion g7                 | [18eb2a894b](https://linux-hardware.org/?probe=18eb2a894b) | Jul 29, 2023 |
| HP            | ZBook 15 G5                 | [8996d2d4fd](https://linux-hardware.org/?probe=8996d2d4fd) | Jul 28, 2023 |
| Google        | Edgar                       | [7e19b1e507](https://linux-hardware.org/?probe=7e19b1e507) | Jul 28, 2023 |
| ASUSTek       | K50IJ                       | [7e30723b3b](https://linux-hardware.org/?probe=7e30723b3b) | Jul 28, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [9e892612ab](https://linux-hardware.org/?probe=9e892612ab) | Jul 28, 2023 |
| HP            | EliteBook 8560p             | [b7ce548e5b](https://linux-hardware.org/?probe=b7ce548e5b) | Jul 27, 2023 |
| Sony          | VPCF13Z1E                   | [5022f7359c](https://linux-hardware.org/?probe=5022f7359c) | Jul 26, 2023 |
| Apple         | MacBookPro12,1              | [45bc8cd978](https://linux-hardware.org/?probe=45bc8cd978) | Jul 26, 2023 |
| Sony          | VPCF13Z1E                   | [f5290b8791](https://linux-hardware.org/?probe=f5290b8791) | Jul 25, 2023 |
| Sony          | VPCF13Z1E                   | [99aacf2d95](https://linux-hardware.org/?probe=99aacf2d95) | Jul 25, 2023 |
| Acer          | TravelMate B113             | [b6fdce48b3](https://linux-hardware.org/?probe=b6fdce48b3) | Jul 25, 2023 |
| Toshiba       | QOSMIO X770                 | [7eda84257a](https://linux-hardware.org/?probe=7eda84257a) | Jul 25, 2023 |
| Dell          | Inspiron 3721               | [a0874e626b](https://linux-hardware.org/?probe=a0874e626b) | Jul 24, 2023 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [c16c981a88](https://linux-hardware.org/?probe=c16c981a88) | Jul 24, 2023 |
| Lenovo        | ThinkPad E15 20RD0011GE     | [8ca6d932b3](https://linux-hardware.org/?probe=8ca6d932b3) | Jul 24, 2023 |
| HP            | Laptop 15s-eq2xxx           | [35d95135f4](https://linux-hardware.org/?probe=35d95135f4) | Jul 23, 2023 |
| HP            | ProBook 640 G1              | [de254aad44](https://linux-hardware.org/?probe=de254aad44) | Jul 23, 2023 |
| Microtech     | ebookPro                    | [4427543f1a](https://linux-hardware.org/?probe=4427543f1a) | Jul 23, 2023 |
| Dell          | Latitude E6400              | [77a598aa4d](https://linux-hardware.org/?probe=77a598aa4d) | Jul 23, 2023 |
| Acer          | AO756                       | [23e3fc369f](https://linux-hardware.org/?probe=23e3fc369f) | Jul 23, 2023 |
| Apple         | MacBookAir7,2               | [c271fa70b8](https://linux-hardware.org/?probe=c271fa70b8) | Jul 23, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [19356a725e](https://linux-hardware.org/?probe=19356a725e) | Jul 22, 2023 |
| HP            | Pavilion dv4                | [4854c4b18c](https://linux-hardware.org/?probe=4854c4b18c) | Jul 22, 2023 |
| HP            | EliteBook 820 G4            | [3051483589](https://linux-hardware.org/?probe=3051483589) | Jul 22, 2023 |
| Medion        | E15301                      | [e20403ff58](https://linux-hardware.org/?probe=e20403ff58) | Jul 22, 2023 |
| Toshiba       | Satellite L50-B             | [5e7da1cf33](https://linux-hardware.org/?probe=5e7da1cf33) | Jul 22, 2023 |
| Acer          | Nitro AN515-44              | [306d51185f](https://linux-hardware.org/?probe=306d51185f) | Jul 21, 2023 |
| AMI           | Cherry Trail CR             | [42d75ac45a](https://linux-hardware.org/?probe=42d75ac45a) | Jul 21, 2023 |
| HP            | EliteBook 820 G4            | [c85c21d42e](https://linux-hardware.org/?probe=c85c21d42e) | Jul 21, 2023 |
| Dell          | Latitude E6440              | [b60d8ab453](https://linux-hardware.org/?probe=b60d8ab453) | Jul 21, 2023 |
| Dell          | Latitude 3520               | [7037e164fd](https://linux-hardware.org/?probe=7037e164fd) | Jul 20, 2023 |
| HP            | 15                          | [36b4035b57](https://linux-hardware.org/?probe=36b4035b57) | Jul 20, 2023 |
| Dell          | Inspiron 3501               | [71f9656ab2](https://linux-hardware.org/?probe=71f9656ab2) | Jul 19, 2023 |
| HP            | EliteBook 2570p             | [854bbb5dee](https://linux-hardware.org/?probe=854bbb5dee) | Jul 19, 2023 |
| HP            | 15                          | [0eeb522bec](https://linux-hardware.org/?probe=0eeb522bec) | Jul 19, 2023 |
| HP            | EliteBook 2570p             | [205b94b373](https://linux-hardware.org/?probe=205b94b373) | Jul 19, 2023 |
| Sony          | VPCEE23FX                   | [2cb9bf9d50](https://linux-hardware.org/?probe=2cb9bf9d50) | Jul 18, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [9be017a8a3](https://linux-hardware.org/?probe=9be017a8a3) | Jul 16, 2023 |
| Dell          | Inspiron 3421               | [71c4faf60f](https://linux-hardware.org/?probe=71c4faf60f) | Jul 16, 2023 |
| Dell          | Inspiron 5537               | [428df654fb](https://linux-hardware.org/?probe=428df654fb) | Jul 16, 2023 |
| Dell          | Inspiron 3531               | [0e7f83761f](https://linux-hardware.org/?probe=0e7f83761f) | Jul 15, 2023 |
| Dell          | Inspiron 3531               | [d73dcbb938](https://linux-hardware.org/?probe=d73dcbb938) | Jul 15, 2023 |
| Dell          | Latitude E4300              | [a9e8fb7884](https://linux-hardware.org/?probe=a9e8fb7884) | Jul 15, 2023 |
| Unknown       | SLR-0308                    | [8626e36716](https://linux-hardware.org/?probe=8626e36716) | Jul 15, 2023 |
| Alienware     | M11xR3                      | [9397339221](https://linux-hardware.org/?probe=9397339221) | Jul 14, 2023 |
| HUAWEI        | RLEF-XX                     | [23793e7d9c](https://linux-hardware.org/?probe=23793e7d9c) | Jul 14, 2023 |
| HP            | 15                          | [215a87518e](https://linux-hardware.org/?probe=215a87518e) | Jul 13, 2023 |
| Apple         | MacBookPro9,2               | [34fe8ff1ad](https://linux-hardware.org/?probe=34fe8ff1ad) | Jul 13, 2023 |
| Apple         | MacBookPro9,2               | [a3d301a82a](https://linux-hardware.org/?probe=a3d301a82a) | Jul 13, 2023 |
| Lenovo        | IdeaPad Creator 5 15IMH0... | [56093a48aa](https://linux-hardware.org/?probe=56093a48aa) | Jul 13, 2023 |
| HP            | Pavilion dv7                | [b2e0e73adc](https://linux-hardware.org/?probe=b2e0e73adc) | Jul 13, 2023 |
| Apple         | MacBookAir7,2               | [81f693b5b0](https://linux-hardware.org/?probe=81f693b5b0) | Jul 12, 2023 |
| Dell          | Inspiron 3421               | [d347a1b82e](https://linux-hardware.org/?probe=d347a1b82e) | Jul 12, 2023 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [bae54aa498](https://linux-hardware.org/?probe=bae54aa498) | Jul 12, 2023 |
| Dell          | Inspiron 3501               | [7190b16550](https://linux-hardware.org/?probe=7190b16550) | Jul 12, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | [052461ef4d](https://linux-hardware.org/?probe=052461ef4d) | Jul 11, 2023 |
| HP            | Compaq 2510p                | [a7cb1d43fb](https://linux-hardware.org/?probe=a7cb1d43fb) | Jul 11, 2023 |
| HP            | Pavilion g4                 | [6e76f09416](https://linux-hardware.org/?probe=6e76f09416) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [ecc4006807](https://linux-hardware.org/?probe=ecc4006807) | Jul 11, 2023 |
| HP            | ProBook 450 G6              | [8e5774c497](https://linux-hardware.org/?probe=8e5774c497) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [2c690e981a](https://linux-hardware.org/?probe=2c690e981a) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [732d09609d](https://linux-hardware.org/?probe=732d09609d) | Jul 10, 2023 |
| HP            | EliteBook 840 G5            | [08770a11c6](https://linux-hardware.org/?probe=08770a11c6) | Jul 10, 2023 |
| HP            | Compaq 2510p                | [98d500c68c](https://linux-hardware.org/?probe=98d500c68c) | Jul 10, 2023 |
| Lenovo        | ThinkPad Yoga 260 20FES3... | [621eaf410c](https://linux-hardware.org/?probe=621eaf410c) | Jul 10, 2023 |
| Lenovo        | ThinkPad Yoga 260 20FES3... | [3631291aa8](https://linux-hardware.org/?probe=3631291aa8) | Jul 10, 2023 |
| HP            | Notebook                    | [7d4bc75f38](https://linux-hardware.org/?probe=7d4bc75f38) | Jul 09, 2023 |
| ASUSTek       | K54C                        | [3f0ca5ad18](https://linux-hardware.org/?probe=3f0ca5ad18) | Jul 09, 2023 |
| HP            | Laptop 15-dy1xxx            | [938e9efd55](https://linux-hardware.org/?probe=938e9efd55) | Jul 09, 2023 |
| Unknown       | SLR-0308                    | [d5b0d30e8d](https://linux-hardware.org/?probe=d5b0d30e8d) | Jul 09, 2023 |
| Apple         | MacBookPro11,2              | [e6693c16ff](https://linux-hardware.org/?probe=e6693c16ff) | Jul 09, 2023 |
| Dell          | Latitude E5470              | [e04195b0f7](https://linux-hardware.org/?probe=e04195b0f7) | Jul 08, 2023 |
| OTVOC         | N1                          | [1b4d619110](https://linux-hardware.org/?probe=1b4d619110) | Jul 07, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [7b62ed78d1](https://linux-hardware.org/?probe=7b62ed78d1) | Jul 07, 2023 |
| Toshiba       | Satellite L670              | [fdc3192779](https://linux-hardware.org/?probe=fdc3192779) | Jul 06, 2023 |
| Lenovo        | Legion Y7000P-1060 81LF     | [203ffa97b4](https://linux-hardware.org/?probe=203ffa97b4) | Jul 06, 2023 |
| Toshiba       | Satellite L670              | [1db76edeb5](https://linux-hardware.org/?probe=1db76edeb5) | Jul 06, 2023 |
| Dell          | XPS 13 9370                 | [854ca6ff4f](https://linux-hardware.org/?probe=854ca6ff4f) | Jul 06, 2023 |
| ASUSTek       | ZenBook UX482EG_UX482EG     | [774ebec1d8](https://linux-hardware.org/?probe=774ebec1d8) | Jul 05, 2023 |
| HP            | EliteBook 820 G4            | [58ced183c2](https://linux-hardware.org/?probe=58ced183c2) | Jul 04, 2023 |
| Acer          | Nitro AN515-44              | [d3aeb3e580](https://linux-hardware.org/?probe=d3aeb3e580) | Jul 03, 2023 |
| Digibras      | NH4CU03                     | [c073941827](https://linux-hardware.org/?probe=c073941827) | Jul 03, 2023 |
| OTVOC         | N1                          | [833ed0c86b](https://linux-hardware.org/?probe=833ed0c86b) | Jul 02, 2023 |
| HP            | ENVY m6                     | [748e336af0](https://linux-hardware.org/?probe=748e336af0) | Jul 02, 2023 |
| HP            | Compaq 6830s                | [9a777f4318](https://linux-hardware.org/?probe=9a777f4318) | Jul 01, 2023 |
| Dell          | Latitude E6400              | [c8f88ff5b6](https://linux-hardware.org/?probe=c8f88ff5b6) | Jun 30, 2023 |
| Acer          | Aspire 5738                 | [b4fcb0d0c0](https://linux-hardware.org/?probe=b4fcb0d0c0) | Jun 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [9d6748ef56](https://linux-hardware.org/?probe=9d6748ef56) | Jun 28, 2023 |
| HP            | ENVY m6                     | [715d68bfc0](https://linux-hardware.org/?probe=715d68bfc0) | Jun 28, 2023 |
| Dell          | Latitude E6400              | [0f9255924f](https://linux-hardware.org/?probe=0f9255924f) | Jun 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [64433a8783](https://linux-hardware.org/?probe=64433a8783) | Jun 27, 2023 |
| HP            | Laptop 14-ck0xxx            | [663ce69f30](https://linux-hardware.org/?probe=663ce69f30) | Jun 27, 2023 |
| HP            | Laptop 14-ck0xxx            | [73eab89788](https://linux-hardware.org/?probe=73eab89788) | Jun 27, 2023 |
| Lenovo        | V110-15IKB 80TH             | [e6b9f96475](https://linux-hardware.org/?probe=e6b9f96475) | Jun 27, 2023 |
| HP            | Pavilion dv6700             | [182bf6e4a7](https://linux-hardware.org/?probe=182bf6e4a7) | Jun 27, 2023 |
| Lenovo        | ThinkPad Yoga 11e 20DA50... | [b756e54029](https://linux-hardware.org/?probe=b756e54029) | Jun 27, 2023 |
| Dell          | Latitude 3189               | [ad7c98c905](https://linux-hardware.org/?probe=ad7c98c905) | Jun 26, 2023 |
| Dell          | Latitude 3189               | [8547503af5](https://linux-hardware.org/?probe=8547503af5) | Jun 25, 2023 |
| Dell          | Latitude 3189               | [3f44430a36](https://linux-hardware.org/?probe=3f44430a36) | Jun 25, 2023 |
| Lenovo        | ThinkPad E560 20EV000UIX    | [ac6bd9497a](https://linux-hardware.org/?probe=ac6bd9497a) | Jun 25, 2023 |
| Toshiba       | Satellite U400              | [58b2ad81eb](https://linux-hardware.org/?probe=58b2ad81eb) | Jun 25, 2023 |
| Acer          | Aspire M3-581G              | [0c348c2570](https://linux-hardware.org/?probe=0c348c2570) | Jun 25, 2023 |
| Apple         | MacBookPro11,2              | [2d7e4f3505](https://linux-hardware.org/?probe=2d7e4f3505) | Jun 24, 2023 |
| Acer          | Aspire 5738                 | [8112b061f0](https://linux-hardware.org/?probe=8112b061f0) | Jun 24, 2023 |
| Dell          | Latitude E6400              | [74be208929](https://linux-hardware.org/?probe=74be208929) | Jun 24, 2023 |
| Acer          | AOD270                      | [af596f2c11](https://linux-hardware.org/?probe=af596f2c11) | Jun 24, 2023 |
| Acer          | AOD270                      | [d3204f80d5](https://linux-hardware.org/?probe=d3204f80d5) | Jun 24, 2023 |
| Toshiba       | Satellite U400              | [aa6254ebd2](https://linux-hardware.org/?probe=aa6254ebd2) | Jun 24, 2023 |
| HP            | EliteBook 8560p             | [177d2fe509](https://linux-hardware.org/?probe=177d2fe509) | Jun 22, 2023 |
| Google        | Kefka                       | [2580ed90ee](https://linux-hardware.org/?probe=2580ed90ee) | Jun 22, 2023 |
| Apple         | MacBookAir7,2               | [ae8c13c6fd](https://linux-hardware.org/?probe=ae8c13c6fd) | Jun 22, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [3d558ea9aa](https://linux-hardware.org/?probe=3d558ea9aa) | Jun 21, 2023 |
| Dell          | Vostro 5481                 | [b28f58f09e](https://linux-hardware.org/?probe=b28f58f09e) | Jun 20, 2023 |
| HP            | ENVY m6                     | [ea4c3aca13](https://linux-hardware.org/?probe=ea4c3aca13) | Jun 20, 2023 |
| Dell          | Inspiron 5558               | [72ef7ff0aa](https://linux-hardware.org/?probe=72ef7ff0aa) | Jun 20, 2023 |
| Dell          | G7 7588                     | [946a645897](https://linux-hardware.org/?probe=946a645897) | Jun 20, 2023 |
| Sony          | VPCCA15FX                   | [ed7dba1a4c](https://linux-hardware.org/?probe=ed7dba1a4c) | Jun 19, 2023 |
| Dell          | Vostro 1520                 | [bc371b62c9](https://linux-hardware.org/?probe=bc371b62c9) | Jun 19, 2023 |
| Sony          | VPCCA15FX                   | [c5660d0020](https://linux-hardware.org/?probe=c5660d0020) | Jun 19, 2023 |
| Dell          | Vostro 1520                 | [8086cf1231](https://linux-hardware.org/?probe=8086cf1231) | Jun 19, 2023 |
| Lenovo        | ThinkPad T440 20B7S0VA05    | [307c8a76ab](https://linux-hardware.org/?probe=307c8a76ab) | Jun 19, 2023 |
| GPU Compan... | GWNC21524                   | [46bd956cbf](https://linux-hardware.org/?probe=46bd956cbf) | Jun 19, 2023 |
| Toshiba       | TECRA M10                   | [37f232dce0](https://linux-hardware.org/?probe=37f232dce0) | Jun 19, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | [7546cac791](https://linux-hardware.org/?probe=7546cac791) | Jun 19, 2023 |
| HP            | EliteBook 840 G3            | [e1fc794bc5](https://linux-hardware.org/?probe=e1fc794bc5) | Jun 18, 2023 |
| ASUSTek       | VivoBook S13 X330FA_S330... | [b816a11527](https://linux-hardware.org/?probe=b816a11527) | Jun 18, 2023 |
| Acer          | Aspire 5738                 | [8247e349fc](https://linux-hardware.org/?probe=8247e349fc) | Jun 17, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [bb6859a141](https://linux-hardware.org/?probe=bb6859a141) | Jun 17, 2023 |
| HP            | ProBook 650 G5              | [1d158627b0](https://linux-hardware.org/?probe=1d158627b0) | Jun 17, 2023 |
| Dell          | Latitude 7370               | [5c2378adc5](https://linux-hardware.org/?probe=5c2378adc5) | Jun 17, 2023 |
| Dell          | Latitude 7370               | [44dba24aed](https://linux-hardware.org/?probe=44dba24aed) | Jun 17, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [3614dc460e](https://linux-hardware.org/?probe=3614dc460e) | Jun 17, 2023 |
| HP            | Laptop 14-bw0xx             | [f38253d79c](https://linux-hardware.org/?probe=f38253d79c) | Jun 17, 2023 |
| Haier         | Y11B                        | [0c2abeea6e](https://linux-hardware.org/?probe=0c2abeea6e) | Jun 17, 2023 |
| HP            | ProBook 650 G5              | [9c53e4cd72](https://linux-hardware.org/?probe=9c53e4cd72) | Jun 17, 2023 |
| HP            | G62                         | [2e1e964887](https://linux-hardware.org/?probe=2e1e964887) | Jun 16, 2023 |
| Acer          | Aspire V5-571P              | [2adeb26f8a](https://linux-hardware.org/?probe=2adeb26f8a) | Jun 15, 2023 |
| Dell          | Venue 11 Pro 5130           | [e1bb6b17b8](https://linux-hardware.org/?probe=e1bb6b17b8) | Jun 14, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [9fe9d9f03f](https://linux-hardware.org/?probe=9fe9d9f03f) | Jun 13, 2023 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [b737ce6557](https://linux-hardware.org/?probe=b737ce6557) | Jun 13, 2023 |
| HP            | ENVY m6                     | [b3c165b329](https://linux-hardware.org/?probe=b3c165b329) | Jun 12, 2023 |
| MSI           | GL62M 7RDX                  | [d1fb646d9a](https://linux-hardware.org/?probe=d1fb646d9a) | Jun 11, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [9cb593e9e1](https://linux-hardware.org/?probe=9cb593e9e1) | Jun 11, 2023 |
| ASUSTek       | U43Jc                       | [1af7e59490](https://linux-hardware.org/?probe=1af7e59490) | Jun 11, 2023 |
| ASUSTek       | U43Jc                       | [15e8e27585](https://linux-hardware.org/?probe=15e8e27585) | Jun 11, 2023 |
| Samsung       | N150/N210/N220              | [977d645961](https://linux-hardware.org/?probe=977d645961) | Jun 10, 2023 |
| Notebook      | NJ50_70CU                   | [d39b8694fd](https://linux-hardware.org/?probe=d39b8694fd) | Jun 10, 2023 |
| Packard Be... | EasyNote TE11BZ             | [a8f9a31f17](https://linux-hardware.org/?probe=a8f9a31f17) | Jun 10, 2023 |
| Google        | Pirika                      | [67fce0a645](https://linux-hardware.org/?probe=67fce0a645) | Jun 10, 2023 |
| Dell          | Precision 7520              | [c52fb2f851](https://linux-hardware.org/?probe=c52fb2f851) | Jun 10, 2023 |
| HP            | Pavilion Notebook           | [5254a5fe09](https://linux-hardware.org/?probe=5254a5fe09) | Jun 07, 2023 |
| HP            | Pavilion Laptop 14-ec1xx... | [de4c183b01](https://linux-hardware.org/?probe=de4c183b01) | Jun 06, 2023 |
| Samsung       | 300E5M/300E5L               | [e066300eac](https://linux-hardware.org/?probe=e066300eac) | Jun 06, 2023 |
| Acer          | Aspire 5736Z                | [a98deb1f54](https://linux-hardware.org/?probe=a98deb1f54) | Jun 06, 2023 |
| Apple         | MacBookPro8,1               | [8308d5da16](https://linux-hardware.org/?probe=8308d5da16) | Jun 05, 2023 |
| Apple         | MacBookPro8,1               | [2f8dbb707f](https://linux-hardware.org/?probe=2f8dbb707f) | Jun 05, 2023 |
| HP            | OMEN by Laptop              | [e3b8e1a109](https://linux-hardware.org/?probe=e3b8e1a109) | Jun 04, 2023 |
| Dell          | Latitude E5250              | [e85c6a09d1](https://linux-hardware.org/?probe=e85c6a09d1) | Jun 04, 2023 |
| Toshiba       | IS 1412                     | [b1b0369688](https://linux-hardware.org/?probe=b1b0369688) | Jun 04, 2023 |
| Lenovo        | ThinkPad T450 20BUS0LW02    | [27f6e7df80](https://linux-hardware.org/?probe=27f6e7df80) | Jun 04, 2023 |
| HP            | Stream Laptop 14-cb0XX      | [83967c7908](https://linux-hardware.org/?probe=83967c7908) | Jun 04, 2023 |
| HP            | ProBook 450 G2              | [55f28b41b4](https://linux-hardware.org/?probe=55f28b41b4) | Jun 03, 2023 |
| Toshiba       | IS 1412                     | [6ea1bc7e6a](https://linux-hardware.org/?probe=6ea1bc7e6a) | Jun 03, 2023 |
| IPASON        | P3                          | [bd9e0660a4](https://linux-hardware.org/?probe=bd9e0660a4) | Jun 02, 2023 |
| ASUSTek       | K70IJ                       | [5b877dfec5](https://linux-hardware.org/?probe=5b877dfec5) | Jun 02, 2023 |
| Toshiba       | Satellite L650              | [63eb6978fa](https://linux-hardware.org/?probe=63eb6978fa) | Jun 01, 2023 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | [a7af6cac2c](https://linux-hardware.org/?probe=a7af6cac2c) | Jun 01, 2023 |
| HP            | Pavilion dv6500             | [0198d67a15](https://linux-hardware.org/?probe=0198d67a15) | May 31, 2023 |
| Sony          | SVF14214CXW                 | [51568ce56e](https://linux-hardware.org/?probe=51568ce56e) | May 30, 2023 |
| Dell          | Latitude 3480               | [56d1834385](https://linux-hardware.org/?probe=56d1834385) | May 30, 2023 |
| Sony          | SVF14214CXW                 | [6cf7c2d7f2](https://linux-hardware.org/?probe=6cf7c2d7f2) | May 30, 2023 |
| Dell          | Inspiron 5748               | [08b61d608c](https://linux-hardware.org/?probe=08b61d608c) | May 30, 2023 |
| ASUSTek       | U43Jc                       | [db28d8f731](https://linux-hardware.org/?probe=db28d8f731) | May 28, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Zorin_16/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.15.0-56-generic | 136       | 5.12%   |
| 5.11.0-38-generic | 103       | 3.88%   |
| 5.11.0-27-generic | 95        | 3.58%   |
| 5.15.0-52-generic | 93        | 3.5%    |
| 5.15.0-58-generic | 91        | 3.43%   |
| 5.15.0-46-generic | 88        | 3.31%   |
| 5.15.0-91-generic | 83        | 3.13%   |
| 5.13.0-30-generic | 74        | 2.79%   |
| 5.15.0-78-generic | 71        | 2.67%   |
| 5.11.0-37-generic | 66        | 2.49%   |
| 5.15.0-67-generic | 64        | 2.41%   |
| 5.11.0-40-generic | 64        | 2.41%   |
| 5.15.0-69-generic | 63        | 2.37%   |
| 5.11.0-41-generic | 63        | 2.37%   |
| 5.15.0-88-generic | 60        | 2.26%   |
| 5.13.0-39-generic | 60        | 2.26%   |
| 5.15.0-60-generic | 58        | 2.18%   |
| 5.15.0-71-generic | 57        | 2.15%   |
| 5.11.0-34-generic | 57        | 2.15%   |
| 5.15.0-76-generic | 56        | 2.11%   |
| 5.11.0-43-generic | 55        | 2.07%   |
| 5.15.0-48-generic | 51        | 1.92%   |
| 5.13.0-44-generic | 48        | 1.81%   |
| 5.13.0-40-generic | 46        | 1.73%   |
| 5.15.0-86-generic | 44        | 1.66%   |
| 5.15.0-84-generic | 43        | 1.62%   |
| 5.15.0-53-generic | 43        | 1.62%   |
| 5.15.0-89-generic | 41        | 1.54%   |
| 5.13.0-35-generic | 40        | 1.51%   |
| 5.13.0-28-generic | 37        | 1.39%   |
| 5.15.0-73-generic | 36        | 1.36%   |
| 5.15.0-41-generic | 35        | 1.32%   |
| 5.15.0-79-generic | 34        | 1.28%   |
| 5.15.0-72-generic | 31        | 1.17%   |
| 5.13.0-52-generic | 31        | 1.17%   |
| 5.15.0-83-generic | 29        | 1.09%   |
| 5.13.0-27-generic | 28        | 1.05%   |
| 5.11.0-46-generic | 27        | 1.02%   |
| 5.13.0-41-generic | 25        | 0.94%   |
| 5.15.0-87-generic | 22        | 0.83%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.15.0   | 1335      | 56.47%  |
| 5.11.0   | 549       | 23.22%  |
| 5.13.0   | 406       | 17.17%  |
| 5.8.0    | 24        | 1.02%   |
| 5.14.0   | 8         | 0.34%   |
| 6.3.13   | 6         | 0.25%   |
| 6.5.7    | 2         | 0.08%   |
| 6.2.16   | 2         | 0.08%   |
| 5.4.0    | 2         | 0.08%   |
| 5.19.0   | 2         | 0.08%   |
| 5.18.15  | 2         | 0.08%   |
| 5.16.0   | 2         | 0.08%   |
| 5.10.0   | 2         | 0.08%   |
| 6.6.7    | 1         | 0.04%   |
| 6.6.1    | 1         | 0.04%   |
| 6.5.0    | 1         | 0.04%   |
| 6.3.2    | 1         | 0.04%   |
| 6.3.1    | 1         | 0.04%   |
| 6.2.14   | 1         | 0.04%   |
| 6.1.22   | 1         | 0.04%   |
| 6.0.19   | 1         | 0.04%   |
| 6.0.0    | 1         | 0.04%   |
| 5.4.180  | 1         | 0.04%   |
| 5.19.9   | 1         | 0.04%   |
| 5.19.14  | 1         | 0.04%   |
| 5.19.12  | 1         | 0.04%   |
| 5.19.1   | 1         | 0.04%   |
| 5.18.6   | 1         | 0.04%   |
| 5.16.12  | 1         | 0.04%   |
| 5.15.49  | 1         | 0.04%   |
| 5.15.24  | 1         | 0.04%   |
| 5.15.150 | 1         | 0.04%   |
| 5.15.12  | 1         | 0.04%   |
| 5.13.18  | 1         | 0.04%   |
| 5.13.12  | 1         | 0.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 1338      | 56.62%  |
| 5.11    | 549       | 23.23%  |
| 5.13    | 408       | 17.27%  |
| 5.8     | 24        | 1.02%   |
| 6.3     | 8         | 0.34%   |
| 5.14    | 8         | 0.34%   |
| 5.19    | 6         | 0.25%   |
| 6.5     | 3         | 0.13%   |
| 6.2     | 3         | 0.13%   |
| 5.4     | 3         | 0.13%   |
| 5.18    | 3         | 0.13%   |
| 5.16    | 3         | 0.13%   |
| 6.6     | 2         | 0.08%   |
| 6.0     | 2         | 0.08%   |
| 5.10    | 2         | 0.08%   |
| 6.1     | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 2271      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 1878      | 81.87%  |
| XFCE            | 376       | 16.39%  |
| Unknown         | 19        | 0.83%   |
| KDE5            | 6         | 0.26%   |
| X-Cinnamon      | 4         | 0.17%   |
| Budgie          | 3         | 0.13%   |
| i3              | 2         | 0.09%   |
| Unity           | 1         | 0.04%   |
| LXQt            | 1         | 0.04%   |
| LXDE            | 1         | 0.04%   |
| KDE             | 1         | 0.04%   |
| GNOME Flashback | 1         | 0.04%   |
| Cinnamon        | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2228      | 97.29%  |
| Wayland | 52        | 2.27%   |
| Unknown | 9         | 0.39%   |
| Tty     | 1         | 0.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1684      | 73.03%  |
| GDM     | 285       | 12.36%  |
| GDM3    | 227       | 9.84%   |
| LightDM | 107       | 4.64%   |
| SDDM    | 2         | 0.09%   |
| LXDM    | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 855       | 37.42%  |
| de_DE | 221       | 9.67%   |
| en_GB | 154       | 6.74%   |
| pt_BR | 120       | 5.25%   |
| fr_FR | 99        | 4.33%   |
| es_ES | 85        | 3.72%   |
| it_IT | 83        | 3.63%   |
| en_IN | 69        | 3.02%   |
| pl_PL | 60        | 2.63%   |
| en_CA | 57        | 2.49%   |
| nl_NL | 39        | 1.71%   |
| es_MX | 39        | 1.71%   |
| en_AU | 36        | 1.58%   |
| ru_RU | 26        | 1.14%   |
| pt_PT | 23        | 1.01%   |
| en_ZA | 23        | 1.01%   |
| cs_CZ | 20        | 0.88%   |
| sv_SE | 18        | 0.79%   |
| tr_TR | 17        | 0.74%   |
| de_CH | 15        | 0.66%   |
| fr_BE | 14        | 0.61%   |
| en_NZ | 14        | 0.61%   |
| de_AT | 14        | 0.61%   |
| hu_HU | 13        | 0.57%   |
| es_AR | 13        | 0.57%   |
| es_CL | 12        | 0.53%   |
| nl_BE | 10        | 0.44%   |
| es_CO | 9         | 0.39%   |
| ja_JP | 6         | 0.26%   |
| es_CR | 6         | 0.26%   |
| en_IE | 6         | 0.26%   |
| el_GR | 6         | 0.26%   |
| da_DK | 6         | 0.26%   |
| bg_BG | 6         | 0.26%   |
| hr_HR | 5         | 0.22%   |
| es_PE | 5         | 0.22%   |
| en_PH | 5         | 0.22%   |
| ar_EG | 5         | 0.22%   |
| sr_RS | 4         | 0.18%   |
| sk_SK | 4         | 0.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 1394      | 60.61%  |
| BIOS | 906       | 39.39%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 2087      | 91.14%  |
| Tmpfs   | 88        | 3.84%   |
| Zfs     | 40        | 1.75%   |
| Overlay | 40        | 1.75%   |
| Btrfs   | 26        | 1.14%   |
| Xfs     | 4         | 0.17%   |
| Ext2    | 3         | 0.13%   |
| Ext3    | 2         | 0.09%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1792      | 77.68%  |
| GPT     | 404       | 17.51%  |
| MBR     | 111       | 4.81%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2213      | 97.19%  |
| Yes       | 64        | 2.81%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2054      | 90.13%  |
| Yes       | 225       | 9.87%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 487       | 21.44%  |
| Lenovo              | 408       | 17.97%  |
| Dell                | 354       | 15.59%  |
| ASUSTek Computer    | 223       | 9.82%   |
| Acer                | 180       | 7.93%   |
| Toshiba             | 97        | 4.27%   |
| Apple               | 78        | 3.43%   |
| MSI                 | 38        | 1.67%   |
| Sony                | 34        | 1.5%    |
| Samsung Electronics | 34        | 1.5%    |
| Google              | 31        | 1.37%   |
| HUAWEI              | 24        | 1.06%   |
| Unknown             | 22        | 0.97%   |
| Packard Bell        | 17        | 0.75%   |
| Positivo            | 15        | 0.66%   |
| Medion              | 15        | 0.66%   |
| Fujitsu             | 12        | 0.53%   |
| Notebook            | 10        | 0.44%   |
| Chuwi               | 10        | 0.44%   |
| Alienware           | 10        | 0.44%   |
| Multilaser          | 7         | 0.31%   |
| Fujitsu Siemens     | 7         | 0.31%   |
| GPU Company         | 6         | 0.26%   |
| AMI                 | 6         | 0.26%   |
| Thomson             | 5         | 0.22%   |
| LG Electronics      | 5         | 0.22%   |
| Razer               | 4         | 0.18%   |
| Microtech           | 4         | 0.18%   |
| Jumper              | 4         | 0.18%   |
| Itautec             | 4         | 0.18%   |
| Gateway             | 4         | 0.18%   |
| Framework           | 4         | 0.18%   |
| Digibras            | 4         | 0.18%   |
| TUXEDO              | 3         | 0.13%   |
| Timi                | 3         | 0.13%   |
| Semp Toshiba        | 3         | 0.13%   |
| Mediacom            | 3         | 0.13%   |
| Intel               | 3         | 0.13%   |
| Insyde              | 3         | 0.13%   |
| Gigabyte Technology | 3         | 0.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Unknown                         | 34        | 1.5%    |
| HP Notebook                     | 26        | 1.14%   |
| HP Pavilion Notebook            | 15        | 0.66%   |
| HP 15                           | 14        | 0.62%   |
| HP Pavilion dv6                 | 10        | 0.44%   |
| HP Pavilion dv7                 | 9         | 0.4%    |
| HP Pavilion 15                  | 9         | 0.4%    |
| Apple MacBookPro8,1             | 8         | 0.35%   |
| Dell Latitude E6520             | 7         | 0.31%   |
| Apple MacBookPro12,1            | 7         | 0.31%   |
| HP Pavilion g7                  | 6         | 0.26%   |
| Dell Latitude E6540             | 6         | 0.26%   |
| Dell Latitude E6430             | 6         | 0.26%   |
| Dell Inspiron 15-3567           | 6         | 0.26%   |
| Lenovo IdeaPad 3 15ALC6 82KU    | 5         | 0.22%   |
| HP ProBook 640 G1               | 5         | 0.22%   |
| HP Pavilion g6                  | 5         | 0.22%   |
| HP EliteBook 8460p              | 5         | 0.22%   |
| HP EliteBook 840 G1             | 5         | 0.22%   |
| HP EliteBook 2570p              | 5         | 0.22%   |
| Dell Latitude E5500             | 5         | 0.22%   |
| Dell Latitude D630              | 5         | 0.22%   |
| Dell Latitude 5490              | 5         | 0.22%   |
| Dell Inspiron 5537              | 5         | 0.22%   |
| Dell Inspiron 1545              | 5         | 0.22%   |
| Apple MacBookPro11,1            | 5         | 0.22%   |
| Apple MacBookAir7,2             | 5         | 0.22%   |
| Toshiba Satellite C660          | 4         | 0.18%   |
| Toshiba Satellite C55-C         | 4         | 0.18%   |
| Lenovo ThinkBook 15 G2 ITL 20VE | 4         | 0.18%   |
| Lenovo IdeaPad 3 15ADA05 81W1   | 4         | 0.18%   |
| HP Victus by Laptop 16-e0xxx    | 4         | 0.18%   |
| HP Stream Notebook              | 4         | 0.18%   |
| HP Stream Laptop 14-ax0XX       | 4         | 0.18%   |
| HP ProBook 6570b                | 4         | 0.18%   |
| HP Pavilion Laptop 15-eg0xxx    | 4         | 0.18%   |
| HP Laptop 15-db0xxx             | 4         | 0.18%   |
| HP Laptop 15-bw0xx              | 4         | 0.18%   |
| HP Laptop 14-ck0xxx             | 4         | 0.18%   |
| HP EliteBook 8570p              | 4         | 0.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 171       | 7.53%   |
| Dell Latitude         | 140       | 6.16%   |
| Acer Aspire           | 131       | 5.77%   |
| Lenovo IdeaPad        | 124       | 5.46%   |
| Dell Inspiron         | 114       | 5.02%   |
| HP Pavilion           | 113       | 4.98%   |
| Toshiba Satellite     | 80        | 3.52%   |
| HP EliteBook          | 69        | 3.04%   |
| HP ProBook            | 60        | 2.64%   |
| HP Laptop             | 50        | 2.2%    |
| ASUS VivoBook         | 39        | 1.72%   |
| Unknown               | 34        | 1.5%    |
| Dell Vostro           | 27        | 1.19%   |
| HP Notebook           | 26        | 1.14%   |
| Dell XPS              | 24        | 1.06%   |
| HP Compaq             | 22        | 0.97%   |
| HP Stream             | 19        | 0.84%   |
| Dell Precision        | 19        | 0.84%   |
| HP ENVY               | 18        | 0.79%   |
| HP 15                 | 16        | 0.7%    |
| Packard Bell EasyNote | 15        | 0.66%   |
| ASUS ZenBook          | 15        | 0.66%   |
| ASUS ROG              | 15        | 0.66%   |
| ASUS ASUS             | 15        | 0.66%   |
| Lenovo Yoga           | 13        | 0.57%   |
| HP OMEN               | 13        | 0.57%   |
| Lenovo Legion         | 12        | 0.53%   |
| HP ZBook              | 11        | 0.48%   |
| Apple MacBookPro8     | 11        | 0.48%   |
| Fujitsu LIFEBOOK      | 10        | 0.44%   |
| Apple MacBookPro5     | 10        | 0.44%   |
| Apple MacBookPro11    | 10        | 0.44%   |
| Acer Swift            | 10        | 0.44%   |
| Lenovo ThinkBook      | 9         | 0.4%    |
| Dell Studio           | 9         | 0.4%    |
| HP 255                | 8         | 0.35%   |
| HP 250                | 8         | 0.35%   |
| Toshiba TECRA         | 7         | 0.31%   |
| Dell Venue            | 7         | 0.31%   |
| Apple MacBookPro12    | 7         | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2012 | 205       | 9.03%   |
| 2013 | 195       | 8.59%   |
| 2021 | 192       | 8.45%   |
| 2011 | 187       | 8.23%   |
| 2020 | 163       | 7.18%   |
| 2019 | 148       | 6.52%   |
| 2014 | 145       | 6.38%   |
| 2018 | 144       | 6.34%   |
| 2017 | 144       | 6.34%   |
| 2015 | 136       | 5.99%   |
| 2010 | 130       | 5.72%   |
| 2016 | 124       | 5.46%   |
| 2008 | 109       | 4.8%    |
| 2009 | 74        | 3.26%   |
| 2022 | 65        | 2.86%   |
| 2007 | 61        | 2.69%   |
| 2023 | 35        | 1.54%   |
| 2006 | 13        | 0.57%   |
| 2024 | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2271      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1945      | 84.79%  |
| Enabled  | 349       | 15.21%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2236      | 98.46%  |
| Yes  | 35        | 1.54%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 782       | 34.12%  |
| 3.01-4.0    | 612       | 26.7%   |
| 8.01-16.0   | 301       | 13.13%  |
| 16.01-24.0  | 295       | 12.87%  |
| 1.01-2.0    | 137       | 5.98%   |
| 32.01-64.0  | 90        | 3.93%   |
| 2.01-3.0    | 39        | 1.7%    |
| 64.01-256.0 | 16        | 0.7%    |
| 24.01-32.0  | 14        | 0.61%   |
| 0.51-1.0    | 6         | 0.26%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 971       | 38.86%  |
| 2.01-3.0   | 838       | 33.53%  |
| 3.01-4.0   | 335       | 13.41%  |
| 4.01-8.0   | 251       | 10.04%  |
| 0.51-1.0   | 64        | 2.56%   |
| 8.01-16.0  | 35        | 1.4%    |
| 24.01-32.0 | 3         | 0.12%   |
| 16.01-24.0 | 2         | 0.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1755      | 75.84%  |
| 2      | 488       | 21.09%  |
| 3      | 50        | 2.16%   |
| 4      | 9         | 0.39%   |
| 0      | 8         | 0.35%   |
| 5      | 3         | 0.13%   |
| 8      | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1339      | 58.63%  |
| Yes       | 945       | 41.37%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1778      | 78.09%  |
| No        | 499       | 21.91%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2192      | 96.44%  |
| No        | 81        | 3.56%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1648      | 71.65%  |
| No        | 652       | 28.35%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 460       | 20.17%  |
| Germany      | 243       | 10.65%  |
| Brazil       | 141       | 6.18%   |
| UK           | 135       | 5.92%   |
| Spain        | 90        | 3.95%   |
| France       | 87        | 3.81%   |
| Italy        | 85        | 3.73%   |
| India        | 72        | 3.16%   |
| Canada       | 72        | 3.16%   |
| Netherlands  | 66        | 2.89%   |
| Mexico       | 55        | 2.41%   |
| Poland       | 53        | 2.32%   |
| Belgium      | 35        | 1.53%   |
| Australia    | 35        | 1.53%   |
| Austria      | 33        | 1.45%   |
| Russia       | 31        | 1.36%   |
| Switzerland  | 29        | 1.27%   |
| Sweden       | 29        | 1.27%   |
| Portugal     | 28        | 1.23%   |
| Turkey       | 27        | 1.18%   |
| South Africa | 27        | 1.18%   |
| Czechia      | 22        | 0.96%   |
| Romania      | 20        | 0.88%   |
| Argentina    | 19        | 0.83%   |
| Norway       | 16        | 0.7%    |
| Hungary      | 15        | 0.66%   |
| Greece       | 15        | 0.66%   |
| Colombia     | 15        | 0.66%   |
| Chile        | 15        | 0.66%   |
| New Zealand  | 14        | 0.61%   |
| Japan        | 14        | 0.61%   |
| Indonesia    | 14        | 0.61%   |
| Ireland      | 11        | 0.48%   |
| Egypt        | 11        | 0.48%   |
| Finland      | 10        | 0.44%   |
| Bulgaria     | 10        | 0.44%   |
| Denmark      | 8         | 0.35%   |
| Croatia      | 8         | 0.35%   |
| Serbia       | 7         | 0.31%   |
| Saudi Arabia | 7         | 0.31%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Berlin            | 20        | 0.83%   |
| Vienna            | 18        | 0.75%   |
| Madrid            | 17        | 0.71%   |
| New York          | 14        | 0.58%   |
| Hamburg           | 13        | 0.54%   |
| Amsterdam         | 13        | 0.54%   |
| Sydney            | 12        | 0.5%    |
| Sao Paulo         | 12        | 0.5%    |
| Rome              | 12        | 0.5%    |
| Munich            | 12        | 0.5%    |
| Paris             | 11        | 0.46%   |
| Bogotá           | 10        | 0.42%   |
| Athens            | 10        | 0.42%   |
| Valencia          | 9         | 0.37%   |
| Rio de Janeiro    | 9         | 0.37%   |
| Milan             | 9         | 0.37%   |
| Mexico City       | 9         | 0.37%   |
| Glasgow           | 9         | 0.37%   |
| Delhi             | 9         | 0.37%   |
| Toronto           | 8         | 0.33%   |
| Moscow            | 8         | 0.33%   |
| Montreal          | 8         | 0.33%   |
| Melbourne         | 8         | 0.33%   |
| London            | 8         | 0.33%   |
| Johannesburg      | 8         | 0.33%   |
| Frankfurt am Main | 8         | 0.33%   |
| Denver            | 8         | 0.33%   |
| Dallas            | 8         | 0.33%   |
| Widnau            | 7         | 0.29%   |
| Warsaw            | 7         | 0.29%   |
| Stockholm         | 7         | 0.29%   |
| Jakarta           | 7         | 0.29%   |
| Istanbul          | 7         | 0.29%   |
| Bengaluru         | 7         | 0.29%   |
| Barcelona         | 7         | 0.29%   |
| Stuttgart         | 6         | 0.25%   |
| Seattle           | 6         | 0.25%   |
| Santiago          | 6         | 0.25%   |
| Nairobi           | 6         | 0.25%   |
| Krakow            | 6         | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 345       | 475    | 12.67%  |
| Seagate                     | 302       | 381    | 11.09%  |
| WDC                         | 283       | 357    | 10.39%  |
| Unknown                     | 253       | 339    | 9.29%   |
| Toshiba                     | 237       | 278    | 8.7%    |
| SanDisk                     | 188       | 227    | 6.9%    |
| Kingston                    | 123       | 159    | 4.52%   |
| Crucial                     | 93        | 117    | 3.41%   |
| SK hynix                    | 83        | 94     | 3.05%   |
| Intel                       | 80        | 98     | 2.94%   |
| HGST                        | 78        | 93     | 2.86%   |
| Micron Technology           | 67        | 85     | 2.46%   |
| Hitachi                     | 63        | 78     | 2.31%   |
| China                       | 39        | 52     | 1.43%   |
| Apple                       | 37        | 43     | 1.36%   |
| A-DATA Technology           | 34        | 41     | 1.25%   |
| KIOXIA                      | 30        | 37     | 1.1%    |
| Intenso                     | 24        | 27     | 0.88%   |
| Unknown                     | 24        | 26     | 0.88%   |
| SPCC                        | 18        | 26     | 0.66%   |
| Netac                       | 17        | 17     | 0.62%   |
| PNY                         | 16        | 19     | 0.59%   |
| LITEONIT                    | 15        | 17     | 0.55%   |
| Fujitsu                     | 14        | 16     | 0.51%   |
| Phison                      | 13        | 17     | 0.48%   |
| Patriot                     | 12        | 14     | 0.44%   |
| LITEON                      | 12        | 14     | 0.44%   |
| Silicon Motion              | 11        | 12     | 0.4%    |
| JMicron Technology          | 10        | 11     | 0.37%   |
| GOODRAM                     | 10        | 11     | 0.37%   |
| Team                        | 9         | 10     | 0.33%   |
| Phison Electronics          | 9         | 9      | 0.33%   |
| Transcend                   | 8         | 11     | 0.29%   |
| Kingston Technology Company | 7         | 8      | 0.26%   |
| OCZ                         | 6         | 7      | 0.22%   |
| KingSpec                    | 6         | 6      | 0.22%   |
| SABRENT                     | 5         | 6      | 0.18%   |
| Micron/Crucial Technology   | 5         | 7      | 0.18%   |
| MAXIO Technology (Hangzhou) | 5         | 5      | 0.18%   |
| Lite-On                     | 5         | 7      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                              | 79        | 2.78%   |
| Unknown MMC Card  64GB                              | 71        | 2.5%    |
| Seagate ST1000LM035-1RK172 1TB                      | 42        | 1.48%   |
| Toshiba MQ01ABD100 1TB                              | 38        | 1.34%   |
| Unknown MMC Card  128GB                             | 31        | 1.09%   |
| Toshiba MQ01ABF050 500GB                            | 31        | 1.09%   |
| Kingston SA400S37240G 240GB SSD                     | 29        | 1.02%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 28        | 0.98%   |
| Seagate ST500LT012-1DG142 500GB                     | 26        | 0.91%   |
| Toshiba MQ04ABF100 1TB                              | 24        | 0.84%   |
| Unknown                                             | 24        | 0.84%   |
| Kingston SA400S37480G 480GB SSD                     | 21        | 0.74%   |
| Unknown MMC Card  16GB                              | 19        | 0.67%   |
| Seagate ST9500325AS 500GB                           | 19        | 0.67%   |
| SanDisk NVMe SSD Drive 256GB                        | 19        | 0.67%   |
| Samsung NVMe SSD Drive 512GB                        | 18        | 0.63%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 18        | 0.63%   |
| Kingston SA400S37120G 120GB SSD                     | 17        | 0.6%    |
| HGST HTS721010A9E630 1TB                            | 17        | 0.6%    |
| Crucial CT240BX500SSD1 240GB                        | 16        | 0.56%   |
| Crucial CT500MX500SSD1 500GB                        | 15        | 0.53%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 14        | 0.49%   |
| Unknown SD/MMC/MS PRO 128GB                         | 14        | 0.49%   |
| HGST HTS545050A7E680 500GB                          | 14        | 0.49%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 13        | 0.46%   |
| SanDisk NVMe SSD Drive 512GB                        | 13        | 0.46%   |
| Samsung SSD 850 EVO 500GB                           | 13        | 0.46%   |
| HGST HTS541010A9E680 1TB                            | 13        | 0.46%   |
| Seagate Expansion 1TB                               | 12        | 0.42%   |
| Samsung NVMe SSD Drive 256GB                        | 12        | 0.42%   |
| Intel NVMe SSD Drive 512GB                          | 12        | 0.42%   |
| Samsung SSD 860 EVO 500GB                           | 11        | 0.39%   |
| HGST HTS725050A7E630 500GB                          | 11        | 0.39%   |
| Seagate ST9500420AS 500GB                           | 10        | 0.35%   |
| Samsung SSD 850 EVO 250GB                           | 10        | 0.35%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 10        | 0.35%   |
| Crucial CT480BX500SSD1 480GB                        | 10        | 0.35%   |
| China SSD 256GB                                     | 10        | 0.35%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB    | 9         | 0.32%   |
| SanDisk SSD PLUS 480GB                              | 9         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 296       | 372    | 32.46%  |
| WDC                 | 218       | 272    | 23.9%   |
| Toshiba             | 184       | 211    | 20.18%  |
| HGST                | 78        | 93     | 8.55%   |
| Hitachi             | 63        | 78     | 6.91%   |
| Samsung Electronics | 19        | 19     | 2.08%   |
| Unknown             | 14        | 16     | 1.54%   |
| Fujitsu             | 14        | 16     | 1.54%   |
| JMicron Technology  | 7         | 8      | 0.77%   |
| SABRENT             | 5         | 6      | 0.55%   |
| Apple               | 5         | 5      | 0.55%   |
| ASMT                | 4         | 4      | 0.44%   |
| XrayDisk            | 1         | 1      | 0.11%   |
| TO Exter            | 1         | 1      | 0.11%   |
| LaCie               | 1         | 1      | 0.11%   |
| KESU                | 1         | 1      | 0.11%   |
| Intenso             | 1         | 1      | 0.11%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 181       | 250    | 19.26%  |
| Kingston            | 108       | 141    | 11.49%  |
| SanDisk             | 96        | 118    | 10.21%  |
| Crucial             | 89        | 111    | 9.47%   |
| WDC                 | 40        | 54     | 4.26%   |
| China               | 38        | 51     | 4.04%   |
| Intel               | 30        | 35     | 3.19%   |
| Toshiba             | 27        | 30     | 2.87%   |
| Apple               | 27        | 31     | 2.87%   |
| A-DATA Technology   | 27        | 34     | 2.87%   |
| Micron Technology   | 26        | 32     | 2.77%   |
| SK hynix            | 22        | 22     | 2.34%   |
| SPCC                | 17        | 25     | 1.81%   |
| Netac               | 17        | 17     | 1.81%   |
| Intenso             | 17        | 18     | 1.81%   |
| PNY                 | 16        | 19     | 1.7%    |
| LITEONIT            | 15        | 17     | 1.6%    |
| Patriot             | 12        | 14     | 1.28%   |
| LITEON              | 12        | 14     | 1.28%   |
| Team                | 9         | 10     | 0.96%   |
| GOODRAM             | 9         | 10     | 0.96%   |
| Transcend           | 8         | 11     | 0.85%   |
| OCZ                 | 6         | 7      | 0.64%   |
| KingSpec            | 6         | 6      | 0.64%   |
| Unknown             | 6         | 8      | 0.64%   |
| Phison              | 4         | 7      | 0.43%   |
| Hewlett-Packard     | 4         | 6      | 0.43%   |
| Teclast             | 3         | 3      | 0.32%   |
| Plextor             | 3         | 3      | 0.32%   |
| Mushkin             | 3         | 3      | 0.32%   |
| Lexar               | 3         | 3      | 0.32%   |
| Fanxiang            | 3         | 4      | 0.32%   |
| Apacer              | 3         | 3      | 0.32%   |
| Verbatim            | 2         | 2      | 0.21%   |
| HS-SSD-E100         | 2         | 2      | 0.21%   |
| Gigabyte Technology | 2         | 2      | 0.21%   |
| BHT                 | 2         | 3      | 0.21%   |
| ZOTAC               | 1         | 1      | 0.11%   |
| Wibtek              | 1         | 2      | 0.11%   |
| VISIPRO             | 1         | 1      | 0.11%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 900       | 1176   | 34.23%  |
| HDD     | 888       | 1105   | 33.78%  |
| NVMe    | 543       | 727    | 20.65%  |
| MMC     | 255       | 340    | 9.7%    |
| Unknown | 43        | 48     | 1.64%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1651      | 2214   | 65.13%  |
| NVMe | 542       | 721    | 21.38%  |
| MMC  | 255       | 340    | 10.06%  |
| SAS  | 87        | 121    | 3.43%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1229      | 1591   | 69.67%  |
| 0.51-1.0   | 477       | 608    | 27.04%  |
| 1.01-2.0   | 48        | 64     | 2.72%   |
| 3.01-4.0   | 6         | 14     | 0.34%   |
| 4.01-10.0  | 4         | 4      | 0.23%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 817       | 35%     |
| 251-500        | 600       | 25.71%  |
| 501-1000       | 340       | 14.57%  |
| 51-100         | 223       | 9.55%   |
| 21-50          | 146       | 6.26%   |
| 1001-2000      | 75        | 3.21%   |
| 1-20           | 52        | 2.23%   |
| Unknown        | 32        | 1.37%   |
| More than 3000 | 28        | 1.2%    |
| 2001-3000      | 21        | 0.9%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 960       | 38.82%  |
| 21-50          | 735       | 29.72%  |
| 51-100         | 311       | 12.58%  |
| 101-250        | 251       | 10.15%  |
| 251-500        | 107       | 4.33%   |
| 501-1000       | 50        | 2.02%   |
| Unknown        | 32        | 1.29%   |
| 1001-2000      | 13        | 0.53%   |
| More than 3000 | 9         | 0.36%   |
| 2001-3000      | 5         | 0.2%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                           | 3         | 3      | 4.92%   |
| Toshiba MQ02ABD100H 1TB                          | 2         | 2      | 3.28%   |
| SK hynix BC711 HFM512GD3JX013N 512GB             | 2         | 2      | 3.28%   |
| Seagate ST9500325AS 500GB                        | 2         | 2      | 3.28%   |
| Seagate ST500LT012-1DG142 500GB                  | 2         | 2      | 3.28%   |
| Seagate ST1000LM048-2E7172 1TB                   | 2         | 2      | 3.28%   |
| Seagate ST1000LM035-1RK172 1TB                   | 2         | 2      | 3.28%   |
| HGST HTS545050A7E680 500GB                       | 2         | 2      | 3.28%   |
| HGST HTS545050A7E380 500GB                       | 2         | 3      | 3.28%   |
| WDC WD6400BEVT-22A0RT0 640GB                     | 1         | 1      | 1.64%   |
| WDC WD5000LPVX-75V0TT0 500GB                     | 1         | 1      | 1.64%   |
| WDC WD5000BEVT-24A0RT0 500GB                     | 1         | 1      | 1.64%   |
| WDC WD1200BEVS-60UST0 120GB                      | 1         | 1      | 1.64%   |
| WDC WD10SPZX-75Z10T2 1TB                         | 1         | 1      | 1.64%   |
| WDC WD10JPVX-22JC3T0 1TB                         | 1         | 1      | 1.64%   |
| WDC WD10JPVT-55A1YT0 1TB                         | 1         | 1      | 1.64%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD             | 1         | 1      | 1.64%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD         | 1         | 1      | 1.64%   |
| Toshiba MQ01ABF050 500GB                         | 1         | 1      | 1.64%   |
| Toshiba MQ01ABD075 752GB                         | 1         | 1      | 1.64%   |
| Teclast 128GB NS550-2242 SSD                     | 1         | 1      | 1.64%   |
| Seagate ST9500420AS 500GB                        | 1         | 1      | 1.64%   |
| Seagate ST9320310AS 320GB                        | 1         | 1      | 1.64%   |
| Seagate ST9250315AS 250GB                        | 1         | 1      | 1.64%   |
| Seagate ST9200420ASG 200GB                       | 1         | 1      | 1.64%   |
| Seagate ST9160411ASG 160GB                       | 1         | 1      | 1.64%   |
| Seagate ST500LT012-9WS142 500GB                  | 1         | 1      | 1.64%   |
| Seagate ST500LM000-SSHD-8GB                      | 1         | 1      | 1.64%   |
| Seagate ST320LT007-9ZV142 320GB                  | 1         | 1      | 1.64%   |
| Seagate ST1000LX015-1U7172 1TB                   | 1         | 1      | 1.64%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 1         | 1      | 1.64%   |
| Samsung Electronics MZHPV256HDGL-00000 256GB SSD | 1         | 1      | 1.64%   |
| Samsung Electronics MMCRE64G8MPP-0VA 64GB SSD    | 1         | 1      | 1.64%   |
| Samsung Electronics HM160JI 160GB                | 1         | 1      | 1.64%   |
| Samsung Electronics HM160HI 160GB                | 1         | 1      | 1.64%   |
| POLION SSD 240GB                                 | 1         | 1      | 1.64%   |
| LITEONIT LCT-256M3S 2.5 7mm 256GB SSD            | 1         | 1      | 1.64%   |
| Kingston SUV400S37240G 240GB SSD                 | 1         | 1      | 1.64%   |
| Kingston SA400S37120G 120GB SSD                  | 1         | 1      | 1.64%   |
| Kingston RBU-SNS8152S3256GG2 256GB SSD           | 1         | 1      | 1.64%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 18        | 18     | 29.51%  |
| Toshiba             | 9         | 9      | 14.75%  |
| HGST                | 8         | 9      | 13.11%  |
| WDC                 | 7         | 7      | 11.48%  |
| Samsung Electronics | 4         | 4      | 6.56%   |
| Kingston            | 3         | 3      | 4.92%   |
| Hitachi             | 3         | 3      | 4.92%   |
| SK hynix            | 2         | 2      | 3.28%   |
| Teclast             | 1         | 1      | 1.64%   |
| POLION              | 1         | 1      | 1.64%   |
| LITEONIT            | 1         | 1      | 1.64%   |
| Intel               | 1         | 1      | 1.64%   |
| Hewlett-Packard     | 1         | 1      | 1.64%   |
| Drevo               | 1         | 1      | 1.64%   |
| Unknown             | 1         | 1      | 1.64%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 18        | 18     | 40%     |
| HGST                | 8         | 9      | 17.78%  |
| WDC                 | 7         | 7      | 15.56%  |
| Toshiba             | 7         | 7      | 15.56%  |
| Hitachi             | 3         | 3      | 6.67%   |
| Samsung Electronics | 2         | 2      | 4.44%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 45        | 46     | 73.77%  |
| SSD  | 14        | 14     | 22.95%  |
| NVMe | 2         | 2      | 3.28%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                          | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate ST2000LX001-1RG174 2TB | 1         | 1      | 50%     |
| SanDisk SSD i100 24GB          | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| SanDisk | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1967      | 2953   | 84.2%   |
| Works    | 306       | 378    | 13.1%   |
| Malfunc  | 60        | 62     | 2.57%   |
| Failed   | 2         | 2      | 0.09%   |
| Fixed    | 1         | 1      | 0.04%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1628      | 65.28%  |
| AMD                              | 273       | 10.95%  |
| Samsung Electronics              | 177       | 7.1%    |
| SanDisk                          | 105       | 4.21%   |
| SK hynix                         | 59        | 2.37%   |
| Micron Technology                | 42        | 1.68%   |
| KIOXIA                           | 30        | 1.2%    |
| Toshiba America Info Systems     | 27        | 1.08%   |
| Nvidia                           | 26        | 1.04%   |
| Kingston Technology Company      | 22        | 0.88%   |
| Phison Electronics               | 20        | 0.8%    |
| Silicon Motion                   | 14        | 0.56%   |
| Micron/Crucial Technology        | 10        | 0.4%    |
| ADATA Technology                 | 10        | 0.4%    |
| MAXIO Technology (Hangzhou)      | 6         | 0.24%   |
| Marvell Technology Group         | 5         | 0.2%    |
| Lite-On Technology               | 5         | 0.2%    |
| Union Memory (Shenzhen)          | 4         | 0.16%   |
| ASMedia Technology               | 4         | 0.16%   |
| Apple                            | 4         | 0.16%   |
| VIA Technologies                 | 3         | 0.12%   |
| Silicon Integrated Systems [SiS] | 3         | 0.12%   |
| Realtek Semiconductor            | 3         | 0.12%   |
| Yangtze Memory Technologies      | 2         | 0.08%   |
| Solid State Storage Technology   | 2         | 0.08%   |
| Shenzhen Longsys Electronics     | 2         | 0.08%   |
| Seagate Technology               | 2         | 0.08%   |
| Lenovo                           | 2         | 0.08%   |
| Silicon Image                    | 1         | 0.04%   |
| JMicron Technology               | 1         | 0.04%   |
| INNOGRIT                         | 1         | 0.04%   |
| Biwin Storage Technology         | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 232       | 8.59%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 201       | 7.44%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 174       | 6.44%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 141       | 5.22%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 135       | 5%      |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 99        | 3.67%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 88        | 3.26%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 76        | 2.81%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 72        | 2.67%   |
| Intel Volume Management Device NVMe RAID Controller                              | 67        | 2.48%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 61        | 2.26%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 60        | 2.22%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 53        | 1.96%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 51        | 1.89%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 51        | 1.89%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 48        | 1.78%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 45        | 1.67%   |
| Intel Tiger Lake-LP SATA Controller                                              | 39        | 1.44%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 37        | 1.37%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 36        | 1.33%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 34        | 1.26%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 32        | 1.19%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 30        | 1.11%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 28        | 1.04%   |
| Intel Comet Lake SATA AHCI Controller                                            | 24        | 0.89%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 23        | 0.85%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 22        | 0.81%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 22        | 0.81%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 22        | 0.81%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                            | 19        | 0.7%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 19        | 0.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 19        | 0.7%    |
| Intel SSD 670p Series [Keystone Harbor]                                          | 18        | 0.67%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)        | 17        | 0.63%   |
| Micron 2210 NVMe SSD [Cobain]                                                    | 17        | 0.63%   |
| Nvidia MCP79 AHCI Controller                                                     | 15        | 0.56%   |
| Intel SSD 660P Series                                                            | 15        | 0.56%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 14        | 0.52%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                       | 13        | 0.48%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 13        | 0.48%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1671      | 64.29%  |
| NVMe | 543       | 20.89%  |
| RAID | 217       | 8.35%   |
| IDE  | 168       | 6.46%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 1917      | 84.41%  |
| AMD    | 354       | 15.59%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron N4020 CPU @ 1.10GHz             | 33        | 1.45%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 30        | 1.32%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 30        | 1.32%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 28        | 1.23%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 27        | 1.19%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 27        | 1.19%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 26        | 1.14%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 26        | 1.14%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 25        | 1.1%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 25        | 1.1%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 25        | 1.1%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 22        | 0.97%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 22        | 0.97%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 21        | 0.92%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 21        | 0.92%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 21        | 0.92%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 19        | 0.84%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 19        | 0.84%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 18        | 0.79%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 18        | 0.79%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 17        | 0.75%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 17        | 0.75%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 16        | 0.7%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 16        | 0.7%    |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 16        | 0.7%    |
| Intel Core i3-3110M CPU @ 2.40GHz             | 16        | 0.7%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 15        | 0.66%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 15        | 0.66%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 15        | 0.66%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 14        | 0.62%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 14        | 0.62%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 14        | 0.62%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 14        | 0.62%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 14        | 0.62%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 14        | 0.62%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 13        | 0.57%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 13        | 0.57%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 13        | 0.57%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 13        | 0.57%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 12        | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5                        | 559       | 24.6%   |
| Intel Core i7                        | 378       | 16.64%  |
| Intel Core i3                        | 221       | 9.73%   |
| Intel Celeron                        | 212       | 9.33%   |
| Other                                | 161       | 7.09%   |
| Intel Core 2 Duo                     | 141       | 6.21%   |
| Intel Atom                           | 82        | 3.61%   |
| Intel Pentium                        | 78        | 3.43%   |
| AMD Ryzen 5                          | 76        | 3.35%   |
| AMD Ryzen 7                          | 50        | 2.2%    |
| AMD A6                               | 30        | 1.32%   |
| AMD A4                               | 27        | 1.19%   |
| Intel Pentium Dual-Core              | 24        | 1.06%   |
| AMD A8                               | 22        | 0.97%   |
| AMD A10                              | 20        | 0.88%   |
| AMD Ryzen 3                          | 16        | 0.7%    |
| Intel Pentium Dual                   | 15        | 0.66%   |
| Intel Core 2                         | 15        | 0.66%   |
| AMD E1                               | 14        | 0.62%   |
| Intel Core M                         | 11        | 0.48%   |
| AMD E                                | 11        | 0.48%   |
| Intel Pentium Silver                 | 10        | 0.44%   |
| AMD Turion 64 X2 Mobile              | 10        | 0.44%   |
| AMD Ryzen 9                          | 10        | 0.44%   |
| AMD Athlon II                        | 6         | 0.26%   |
| Intel Core m5                        | 5         | 0.22%   |
| AMD Ryzen 7 PRO                      | 5         | 0.22%   |
| AMD E2                               | 5         | 0.22%   |
| Intel Pentium Gold                   | 4         | 0.18%   |
| Intel Genuine                        | 4         | 0.18%   |
| Intel Celeron Dual-Core              | 4         | 0.18%   |
| AMD Athlon                           | 4         | 0.18%   |
| Intel Celeron M                      | 3         | 0.13%   |
| AMD FX                               | 3         | 0.13%   |
| Intel Core i9                        | 2         | 0.09%   |
| AMD V120                             | 2         | 0.09%   |
| AMD Turion X2 Ultra Dual-Core Mobile | 2         | 0.09%   |
| AMD Turion X2 Dual-Core Mobile       | 2         | 0.09%   |
| AMD Turion II Dual-Core              | 2         | 0.09%   |
| AMD Turion II                        | 2         | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1374      | 60.48%  |
| 4      | 664       | 29.23%  |
| 6      | 91        | 4.01%   |
| 8      | 75        | 3.3%    |
| 1      | 29        | 1.28%   |
| 10     | 14        | 0.62%   |
| 12     | 10        | 0.44%   |
| 14     | 9         | 0.4%    |
| 16     | 3         | 0.13%   |
| 24     | 2         | 0.09%   |
| 3      | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2271      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1490      | 65.61%  |
| 1      | 781       | 34.39%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2271      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x306a9    | 188       | 8.16%   |
| 0x206a7    | 183       | 7.94%   |
| Unknown    | 156       | 6.77%   |
| 0x40651    | 111       | 4.82%   |
| 0x1067a    | 95        | 4.12%   |
| 0x406e3    | 92        | 3.99%   |
| 0x306d4    | 91        | 3.95%   |
| 0x20655    | 81        | 3.52%   |
| 0x806c1    | 78        | 3.39%   |
| 0x30678    | 73        | 3.17%   |
| 0x806e9    | 67        | 2.91%   |
| 0x806ec    | 61        | 2.65%   |
| 0x806ea    | 60        | 2.6%    |
| 0x306c3    | 60        | 2.6%    |
| 0x706a8    | 50        | 2.17%   |
| 0x406c4    | 50        | 2.17%   |
| 0x6fd      | 42        | 1.82%   |
| 0x906ea    | 39        | 1.69%   |
| 0x706e5    | 39        | 1.69%   |
| 0x506c9    | 37        | 1.61%   |
| 0x10676    | 35        | 1.52%   |
| 0x906e9    | 32        | 1.39%   |
| 0x20652    | 31        | 1.35%   |
| 0x406c3    | 30        | 1.3%    |
| 0x08108109 | 29        | 1.26%   |
| 0x07030105 | 23        | 1%      |
| 0x0a50000c | 22        | 0.95%   |
| 0xa0652    | 21        | 0.91%   |
| 0x06006705 | 20        | 0.87%   |
| 0x706a1    | 17        | 0.74%   |
| 0x506e3    | 17        | 0.74%   |
| 0x08108102 | 17        | 0.74%   |
| 0x08608103 | 16        | 0.69%   |
| 0x0700010f | 16        | 0.69%   |
| 0x08600106 | 15        | 0.65%   |
| 0x906a3    | 14        | 0.61%   |
| 0x806d1    | 14        | 0.61%   |
| 0x6fb      | 13        | 0.56%   |
| 0x6f6      | 13        | 0.56%   |
| 0x05000119 | 13        | 0.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 296       | 13.03%  |
| IvyBridge        | 196       | 8.63%   |
| SandyBridge      | 189       | 8.32%   |
| Haswell          | 183       | 8.06%   |
| Silvermont       | 166       | 7.31%   |
| Penryn           | 131       | 5.77%   |
| Westmere         | 114       | 5.02%   |
| Skylake          | 114       | 5.02%   |
| TigerLake        | 92        | 4.05%   |
| Broadwell        | 91        | 4.01%   |
| Core             | 82        | 3.61%   |
| Goldmont plus    | 70        | 3.08%   |
| IceLake          | 54        | 2.38%   |
| Unknown          | 51        | 2.25%   |
| Zen+             | 49        | 2.16%   |
| Excavator        | 48        | 2.11%   |
| Zen 3            | 39        | 1.72%   |
| Goldmont         | 39        | 1.72%   |
| Zen 2            | 35        | 1.54%   |
| Puma             | 34        | 1.5%    |
| Alderlake Hybrid | 26        | 1.14%   |
| CometLake        | 25        | 1.1%    |
| Jaguar           | 20        | 0.88%   |
| Bobcat           | 18        | 0.79%   |
| K10              | 16        | 0.7%    |
| Piledriver       | 15        | 0.66%   |
| K8 Hammer        | 14        | 0.62%   |
| K10 Llano        | 12        | 0.53%   |
| Nehalem          | 11        | 0.48%   |
| Tremont          | 10        | 0.44%   |
| Bonnell          | 10        | 0.44%   |
| Zen              | 9         | 0.4%    |
| Steamroller      | 6         | 0.26%   |
| K8 & K10 hybrid  | 6         | 0.26%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1737      | 63.6%   |
| Nvidia                           | 497       | 18.2%   |
| AMD                              | 492       | 18.02%  |
| Silicon Integrated Systems [SiS] | 3         | 0.11%   |
| VIA Technologies                 | 2         | 0.07%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 187       | 6.62%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 171       | 6.05%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 114       | 4.04%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 85        | 3.01%   |
| Intel Core Processor Integrated Graphics Controller                                      | 83        | 2.94%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 81        | 2.87%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 81        | 2.87%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 76        | 2.69%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 71        | 2.51%   |
| Intel HD Graphics 620                                                                    | 66        | 2.34%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 63        | 2.23%   |
| Intel UHD Graphics 620                                                                   | 62        | 2.19%   |
| Intel HD Graphics 5500                                                                   | 61        | 2.16%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 53        | 1.88%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 51        | 1.81%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 39        | 1.38%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 39        | 1.38%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 39        | 1.38%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 35        | 1.24%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 35        | 1.24%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 34        | 1.2%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 33        | 1.17%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 32        | 1.13%   |
| Intel HD Graphics 630                                                                    | 32        | 1.13%   |
| Intel HD Graphics 500                                                                    | 32        | 1.13%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 31        | 1.1%    |
| AMD Lucienne                                                                             | 24        | 0.85%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 23        | 0.81%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 23        | 0.81%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 23        | 0.81%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 23        | 0.81%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 22        | 0.78%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 22        | 0.78%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 21        | 0.74%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 20        | 0.71%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 17        | 0.6%    |
| Intel HD Graphics 530                                                                    | 16        | 0.57%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 15        | 0.53%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 15        | 0.53%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 14        | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 1311      | 57.63%  |
| Intel + Nvidia | 333       | 14.64%  |
| 1 x AMD        | 331       | 14.55%  |
| 1 x Nvidia     | 121       | 5.32%   |
| Intel + AMD    | 87        | 3.82%   |
| 2 x AMD        | 38        | 1.67%   |
| AMD + Nvidia   | 37        | 1.63%   |
| Other          | 6         | 0.26%   |
| 2 x Nvidia     | 6         | 0.26%   |
| 1 x SiS        | 3         | 0.13%   |
| 1 x VIA        | 2         | 0.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1977      | 86.75%  |
| Proprietary | 258       | 11.32%  |
| Unknown     | 44        | 1.93%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1578      | 68.49%  |
| 0.01-0.5   | 297       | 12.89%  |
| 1.01-2.0   | 179       | 7.77%   |
| 0.51-1.0   | 140       | 6.08%   |
| 3.01-4.0   | 60        | 2.6%    |
| 5.01-6.0   | 21        | 0.91%   |
| 7.01-8.0   | 16        | 0.69%   |
| 2.01-3.0   | 11        | 0.48%   |
| 8.01-16.0  | 2         | 0.09%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 474       | 19.78%  |
| Chimei Innolux          | 345       | 14.4%   |
| BOE                     | 340       | 14.19%  |
| LG Display              | 338       | 14.11%  |
| Samsung Electronics     | 264       | 11.02%  |
| Apple                   | 76        | 3.17%   |
| Chi Mei Optoelectronics | 69        | 2.88%   |
| Sharp                   | 45        | 1.88%   |
| Lenovo                  | 44        | 1.84%   |
| Goldstar                | 40        | 1.67%   |
| Dell                    | 36        | 1.5%    |
| LG Philips              | 34        | 1.42%   |
| PANDA                   | 30        | 1.25%   |
| InfoVision              | 23        | 0.96%   |
| Hewlett-Packard         | 20        | 0.83%   |
| CPT                     | 13        | 0.54%   |
| Acer                    | 12        | 0.5%    |
| Philips                 | 11        | 0.46%   |
| Vizio                   | 10        | 0.42%   |
| BenQ                    | 10        | 0.42%   |
| Ancor Communications    | 9         | 0.38%   |
| Sony                    | 8         | 0.33%   |
| ASUSTek Computer        | 7         | 0.29%   |
| AOC                     | 7         | 0.29%   |
| SLD                     | 6         | 0.25%   |
| LGD                     | 6         | 0.25%   |
| HannStar                | 6         | 0.25%   |
| Unknown                 | 6         | 0.25%   |
| InnoLux Display         | 5         | 0.21%   |
| BOE Technology Group    | 5         | 0.21%   |
| ViewSonic               | 4         | 0.17%   |
| Toshiba                 | 4         | 0.17%   |
| Panasonic               | 4         | 0.17%   |
| KDC                     | 4         | 0.17%   |
| CSO                     | 4         | 0.17%   |
| TMX                     | 3         | 0.13%   |
| MSI                     | 3         | 0.13%   |
| Iiyama                  | 3         | 0.13%   |
| Eizo                    | 3         | 0.13%   |
| VIE                     | 2         | 0.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch     | 23        | 0.95%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 20        | 0.83%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 18        | 0.75%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 16        | 0.66%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 15        | 0.62%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 14        | 0.58%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 14        | 0.58%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 14        | 0.58%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch              | 12        | 0.5%    |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 12        | 0.5%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 12        | 0.5%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 12        | 0.5%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 11        | 0.46%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 11        | 0.46%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 11        | 0.46%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 10        | 0.41%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch    | 9         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 9         | 0.37%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 9         | 0.37%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 9         | 0.37%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 9         | 0.37%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 8         | 0.33%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch                  | 8         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 8         | 0.33%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 8         | 0.33%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 7         | 0.29%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 7         | 0.29%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 7         | 0.29%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 7         | 0.29%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 7         | 0.29%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 7         | 0.29%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 7         | 0.29%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch            | 7         | 0.29%   |
| AU Optronics LCD Monitor AUO193C 1366x768 309x173mm 13.9-inch            | 7         | 0.29%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch            | 7         | 0.29%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch           | 7         | 0.29%   |
| SLD LCD Monitor SLD003C 1366x768 309x173mm 13.9-inch                     | 6         | 0.25%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 309x174mm 14.0-inch     | 6         | 0.25%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 6         | 0.25%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch              | 6         | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 922       | 39.79%  |
| 1920x1080 (FHD)    | 790       | 34.1%   |
| 1600x900 (HD+)     | 141       | 6.09%   |
| 1280x800 (WXGA)    | 120       | 5.18%   |
| 1440x900 (WXGA+)   | 55        | 2.37%   |
| 3840x2160 (4K)     | 53        | 2.29%   |
| 1920x1200 (WUXGA)  | 32        | 1.38%   |
| 2560x1600          | 27        | 1.17%   |
| 2560x1440 (QHD)    | 23        | 0.99%   |
| 1680x1050 (WSXGA+) | 17        | 0.73%   |
| 1280x1024 (SXGA)   | 13        | 0.56%   |
| 2880x1800          | 11        | 0.47%   |
| 2560x1080          | 11        | 0.47%   |
| 2160x1440          | 10        | 0.43%   |
| Unknown            | 9         | 0.39%   |
| 3200x1800 (QHD+)   | 8         | 0.35%   |
| 2256x1504          | 8         | 0.35%   |
| 1360x768           | 8         | 0.35%   |
| 1920x540           | 7         | 0.3%    |
| 3840x2400          | 6         | 0.26%   |
| 1024x600           | 6         | 0.26%   |
| 3440x1440          | 5         | 0.22%   |
| 3840x1080          | 4         | 0.17%   |
| 1920x515           | 3         | 0.13%   |
| 5760x1080          | 2         | 0.09%   |
| 2880x1920          | 2         | 0.09%   |
| 2880x1620          | 2         | 0.09%   |
| 2304x1440          | 2         | 0.09%   |
| 2240x1400          | 2         | 0.09%   |
| 1920x1280          | 2         | 0.09%   |
| 1280x720 (HD)      | 2         | 0.09%   |
| 4480x1600          | 1         | 0.04%   |
| 3840x1200          | 1         | 0.04%   |
| 3600x1080          | 1         | 0.04%   |
| 3456x2160          | 1         | 0.04%   |
| 3072x1920          | 1         | 0.04%   |
| 3000x2000          | 1         | 0.04%   |
| 2520x1680          | 1         | 0.04%   |
| 2288x1287          | 1         | 0.04%   |
| 1680x945           | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1017      | 42.61%  |
| 13      | 354       | 14.83%  |
| 14      | 289       | 12.11%  |
| 17      | 190       | 7.96%   |
| 11      | 91        | 3.81%   |
| 12      | 71        | 2.97%   |
| 27      | 45        | 1.89%   |
| Unknown | 42        | 1.76%   |
| 24      | 40        | 1.68%   |
| 16      | 30        | 1.26%   |
| 23      | 29        | 1.21%   |
| 18      | 26        | 1.09%   |
| 31      | 24        | 1.01%   |
| 21      | 24        | 1.01%   |
| 34      | 18        | 0.75%   |
| 10      | 15        | 0.63%   |
| 19      | 13        | 0.54%   |
| 54      | 9         | 0.38%   |
| 40      | 6         | 0.25%   |
| 22      | 6         | 0.25%   |
| 20      | 6         | 0.25%   |
| 84      | 5         | 0.21%   |
| 72      | 4         | 0.17%   |
| 32      | 4         | 0.17%   |
| 25      | 4         | 0.17%   |
| 48      | 3         | 0.13%   |
| 26      | 3         | 0.13%   |
| 52      | 2         | 0.08%   |
| 49      | 2         | 0.08%   |
| 46      | 2         | 0.08%   |
| 37      | 2         | 0.08%   |
| 8       | 2         | 0.08%   |
| 86      | 1         | 0.04%   |
| 74      | 1         | 0.04%   |
| 65      | 1         | 0.04%   |
| 64      | 1         | 0.04%   |
| 63      | 1         | 0.04%   |
| 58      | 1         | 0.04%   |
| 42      | 1         | 0.04%   |
| 36      | 1         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 1489      | 62.64%  |
| 201-300     | 336       | 14.14%  |
| 351-400     | 229       | 9.63%   |
| 501-600     | 111       | 4.67%   |
| 401-500     | 72        | 3.03%   |
| Unknown     | 42        | 1.77%   |
| 601-700     | 31        | 1.3%    |
| 701-800     | 23        | 0.97%   |
| 1001-1500   | 23        | 0.97%   |
| 1501-2000   | 10        | 0.42%   |
| 801-900     | 8         | 0.34%   |
| 101-200     | 2         | 0.08%   |
| 901-1000    | 1         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1841      | 83.8%   |
| 16/10   | 255       | 11.61%  |
| Unknown | 29        | 1.32%   |
| 3/2     | 28        | 1.27%   |
| 21/9    | 17        | 0.77%   |
| 5/4     | 12        | 0.55%   |
| 4/3     | 6         | 0.27%   |
| 3.73    | 3         | 0.14%   |
| 32/9    | 2         | 0.09%   |
| 0.62    | 2         | 0.09%   |
| 1.96    | 1         | 0.05%   |
| 0.56    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1016      | 42.58%  |
| 81-90          | 536       | 22.46%  |
| 121-130        | 155       | 6.5%    |
| 71-80          | 107       | 4.48%   |
| 51-60          | 92        | 3.86%   |
| 201-250        | 88        | 3.69%   |
| 61-70          | 69        | 2.89%   |
| 301-350        | 47        | 1.97%   |
| 351-500        | 46        | 1.93%   |
| Unknown        | 42        | 1.76%   |
| 141-150        | 33        | 1.38%   |
| More than 1000 | 30        | 1.26%   |
| 151-200        | 28        | 1.17%   |
| 131-140        | 28        | 1.17%   |
| 111-120        | 22        | 0.92%   |
| 41-50          | 14        | 0.59%   |
| 501-1000       | 14        | 0.59%   |
| 91-100         | 9         | 0.38%   |
| 251-300        | 8         | 0.34%   |
| 1-40           | 2         | 0.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 944       | 40.05%  |
| 121-160       | 821       | 34.83%  |
| 51-100        | 333       | 14.13%  |
| 161-240       | 140       | 5.94%   |
| Unknown       | 43        | 1.82%   |
| More than 240 | 40        | 1.7%    |
| 1-50          | 36        | 1.53%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1988      | 85.99%  |
| 2     | 263       | 11.38%  |
| 0     | 40        | 1.73%   |
| 3     | 18        | 0.78%   |
| 4     | 2         | 0.09%   |
| 5     | 1         | 0.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1161      | 32.42%  |
| Intel                             | 1036      | 28.93%  |
| Qualcomm Atheros                  | 549       | 15.33%  |
| Broadcom                          | 305       | 8.52%   |
| Broadcom Limited                  | 98        | 2.74%   |
| Marvell Technology Group          | 46        | 1.28%   |
| Ralink                            | 44        | 1.23%   |
| MediaTek                          | 38        | 1.06%   |
| TP-Link                           | 29        | 0.81%   |
| Nvidia                            | 24        | 0.67%   |
| Dell                              | 24        | 0.67%   |
| Samsung Electronics               | 22        | 0.61%   |
| ASIX Electronics                  | 22        | 0.61%   |
| Ralink Technology                 | 18        | 0.5%    |
| Sierra Wireless                   | 14        | 0.39%   |
| DisplayLink                       | 14        | 0.39%   |
| JMicron Technology                | 13        | 0.36%   |
| Hewlett-Packard                   | 12        | 0.34%   |
| Xiaomi                            | 10        | 0.28%   |
| Huawei Technologies               | 9         | 0.25%   |
| Qualcomm                          | 7         | 0.2%    |
| Ericsson Business Mobile Networks | 7         | 0.2%    |
| OPPO Electronics                  | 6         | 0.17%   |
| NetGear                           | 6         | 0.17%   |
| Qualcomm Atheros Communications   | 5         | 0.14%   |
| OnePlus Technology (Shenzhen)     | 4         | 0.11%   |
| Motorola PCS                      | 4         | 0.11%   |
| Edimax Technology                 | 4         | 0.11%   |
| VIA Technologies                  | 3         | 0.08%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.08%   |
| Linksys                           | 3         | 0.08%   |
| Google                            | 3         | 0.08%   |
| D-Link System                     | 3         | 0.08%   |
| ASUSTek Computer                  | 3         | 0.08%   |
| T & A Mobile Phones               | 2         | 0.06%   |
| Lenovo                            | 2         | 0.06%   |
| D-Link                            | 2         | 0.06%   |
| ZyXEL Communications              | 1         | 0.03%   |
| ZyDAS                             | 1         | 0.03%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 627       | 14.72%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 274       | 6.43%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 113       | 2.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 98        | 2.3%    |
| Intel Wireless 7260                                                    | 89        | 2.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 85        | 2%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 84        | 1.97%   |
| Intel Wireless 7265                                                    | 78        | 1.83%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 73        | 1.71%   |
| Intel Wireless 8265 / 8275                                             | 69        | 1.62%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 63        | 1.48%   |
| Intel Wi-Fi 6 AX201                                                    | 61        | 1.43%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 56        | 1.31%   |
| Intel Wireless 8260                                                    | 56        | 1.31%   |
| Broadcom BCM43142 802.11b/g/n                                          | 56        | 1.31%   |
| Intel Wi-Fi 6 AX200                                                    | 51        | 1.2%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 48        | 1.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 46        | 1.08%   |
| Intel Wireless 3165                                                    | 46        | 1.08%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 45        | 1.06%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 43        | 1.01%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 41        | 0.96%   |
| Intel WiFi Link 5100                                                   | 34        | 0.8%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 34        | 0.8%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 32        | 0.75%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 30        | 0.7%    |
| Intel Centrino Ultimate-N 6300                                         | 29        | 0.68%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 28        | 0.66%   |
| Intel Ethernet Connection I219-LM                                      | 28        | 0.66%   |
| Intel Ethernet Connection I218-LM                                      | 28        | 0.66%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 26        | 0.61%   |
| Intel Wireless 3160                                                    | 26        | 0.61%   |
| Intel 82577LM Gigabit Network Connection                               | 26        | 0.61%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 26        | 0.61%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 25        | 0.59%   |
| Intel Ethernet Connection I217-LM                                      | 25        | 0.59%   |
| Intel Ethernet Connection (4) I219-LM                                  | 25        | 0.59%   |
| Intel Centrino Advanced-N 6200                                         | 21        | 0.49%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 20        | 0.47%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 20        | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 992       | 42.58%  |
| Qualcomm Atheros                | 467       | 20.04%  |
| Realtek Semiconductor           | 388       | 16.65%  |
| Broadcom                        | 242       | 10.39%  |
| Broadcom Limited                | 64        | 2.75%   |
| Ralink                          | 44        | 1.89%   |
| MediaTek                        | 30        | 1.29%   |
| TP-Link                         | 21        | 0.9%    |
| Ralink Technology               | 18        | 0.77%   |
| Sierra Wireless                 | 14        | 0.6%    |
| Dell                            | 14        | 0.6%    |
| NetGear                         | 6         | 0.26%   |
| Qualcomm Atheros Communications | 5         | 0.21%   |
| Edimax Technology               | 4         | 0.17%   |
| D-Link System                   | 3         | 0.13%   |
| Linksys                         | 2         | 0.09%   |
| Hewlett-Packard                 | 2         | 0.09%   |
| D-Link                          | 2         | 0.09%   |
| ASUSTek Computer                | 2         | 0.09%   |
| ZyXEL Communications            | 1         | 0.04%   |
| ZyDAS                           | 1         | 0.04%   |
| TRENDnet                        | 1         | 0.04%   |
| Tenda                           | 1         | 0.04%   |
| Qualcomm                        | 1         | 0.04%   |
| Microsoft                       | 1         | 0.04%   |
| Mercucys                        | 1         | 0.04%   |
| Fibocom                         | 1         | 0.04%   |
| Belkin Components               | 1         | 0.04%   |
| Askey Computer                  | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 113       | 4.8%    |
| Intel Wireless 7260                                                     | 89        | 3.78%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 85        | 3.61%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 84        | 3.57%   |
| Intel Wireless 7265                                                     | 78        | 3.31%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 73        | 3.1%    |
| Intel Wireless 8265 / 8275                                              | 69        | 2.93%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 63        | 2.68%   |
| Intel Wi-Fi 6 AX201                                                     | 61        | 2.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 56        | 2.38%   |
| Intel Wireless 8260                                                     | 56        | 2.38%   |
| Broadcom BCM43142 802.11b/g/n                                           | 56        | 2.38%   |
| Intel Wi-Fi 6 AX200                                                     | 51        | 2.17%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 48        | 2.04%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 46        | 1.95%   |
| Intel Wireless 3165                                                     | 46        | 1.95%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 43        | 1.83%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 41        | 1.74%   |
| Intel WiFi Link 5100                                                    | 34        | 1.44%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 34        | 1.44%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 32        | 1.36%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 30        | 1.27%   |
| Intel Centrino Ultimate-N 6300                                          | 29        | 1.23%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 26        | 1.1%    |
| Intel Wireless 3160                                                     | 26        | 1.1%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 25        | 1.06%   |
| Intel Centrino Advanced-N 6200                                          | 21        | 0.89%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 20        | 0.85%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 20        | 0.85%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 20        | 0.85%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 20        | 0.85%   |
| Intel Centrino Advanced-N 6235                                          | 20        | 0.85%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 19        | 0.81%   |
| Realtek 802.11n WLAN Adapter                                            | 18        | 0.76%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 18        | 0.76%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 18        | 0.76%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 18        | 0.76%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 18        | 0.76%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 17        | 0.72%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 17        | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 980       | 53.03%  |
| Intel                            | 383       | 20.73%  |
| Qualcomm Atheros                 | 137       | 7.41%   |
| Broadcom                         | 100       | 5.41%   |
| Marvell Technology Group         | 46        | 2.49%   |
| Broadcom Limited                 | 38        | 2.06%   |
| Nvidia                           | 24        | 1.3%    |
| ASIX Electronics                 | 22        | 1.19%   |
| Samsung Electronics              | 16        | 0.87%   |
| DisplayLink                      | 14        | 0.76%   |
| JMicron Technology               | 13        | 0.7%    |
| Xiaomi                           | 10        | 0.54%   |
| TP-Link                          | 8         | 0.43%   |
| MediaTek                         | 7         | 0.38%   |
| Qualcomm                         | 6         | 0.32%   |
| OPPO Electronics                 | 6         | 0.32%   |
| Huawei Technologies              | 6         | 0.32%   |
| Motorola PCS                     | 4         | 0.22%   |
| VIA Technologies                 | 3         | 0.16%   |
| Silicon Integrated Systems [SiS] | 3         | 0.16%   |
| Hewlett-Packard                  | 3         | 0.16%   |
| Google                           | 3         | 0.16%   |
| OnePlus Technology (Shenzhen)    | 2         | 0.11%   |
| Lenovo                           | 2         | 0.11%   |
| vivo                             | 1         | 0.05%   |
| T & A Mobile Phones              | 1         | 0.05%   |
| Spreadtrum Communications        | 1         | 0.05%   |
| Novatel Wireless                 | 1         | 0.05%   |
| Motorola BCS                     | 1         | 0.05%   |
| Linksys                          | 1         | 0.05%   |
| LG Electronics                   | 1         | 0.05%   |
| ICS Advent                       | 1         | 0.05%   |
| HTC (High Tech Computer)         | 1         | 0.05%   |
| HMD Global                       | 1         | 0.05%   |
| GoPro                            | 1         | 0.05%   |
| ASUSTek Computer                 | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 627       | 33.73%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 274       | 14.74%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 98        | 5.27%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 45        | 2.42%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 28        | 1.51%   |
| Intel Ethernet Connection I219-LM                                      | 28        | 1.51%   |
| Intel Ethernet Connection I218-LM                                      | 28        | 1.51%   |
| Intel 82577LM Gigabit Network Connection                               | 26        | 1.4%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 26        | 1.4%    |
| Intel Ethernet Connection I217-LM                                      | 25        | 1.34%   |
| Intel Ethernet Connection (4) I219-LM                                  | 25        | 1.34%   |
| Intel 82567LM Gigabit Network Connection                               | 20        | 1.08%   |
| ASIX AX88179 Gigabit Ethernet                                          | 20        | 1.08%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 18        | 0.97%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 17        | 0.91%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 17        | 0.91%   |
| Intel Ethernet Connection I219-V                                       | 17        | 0.91%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 16        | 0.86%   |
| Nvidia MCP79 Ethernet                                                  | 15        | 0.81%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 15        | 0.81%   |
| Intel Ethernet Connection (4) I219-V                                   | 14        | 0.75%   |
| Intel Ethernet Connection (3) I218-LM                                  | 14        | 0.75%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 13        | 0.7%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 13        | 0.7%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 12        | 0.65%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                | 12        | 0.65%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 11        | 0.59%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 11        | 0.59%   |
| Intel 82566MM Gigabit Network Connection                               | 11        | 0.59%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 10        | 0.54%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 8         | 0.43%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 8         | 0.43%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 7         | 0.38%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 7         | 0.38%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 7         | 0.38%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 7         | 0.38%   |
| Intel Ethernet Connection (6) I219-LM                                  | 7         | 0.38%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 7         | 0.38%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 6         | 0.32%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 6         | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2192      | 54.69%  |
| Ethernet | 1771      | 44.19%  |
| Modem    | 41        | 1.02%   |
| Unknown  | 4         | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1862      | 79.5%   |
| Ethernet | 479       | 20.45%  |
| Unknown  | 1         | 0.04%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1614      | 71.01%  |
| 1     | 550       | 24.2%   |
| 0     | 98        | 4.31%   |
| 3     | 10        | 0.44%   |
| 4     | 1         | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1590      | 68.77%  |
| Yes  | 722       | 31.23%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 715       | 42.87%  |
| Realtek Semiconductor           | 198       | 11.87%  |
| Qualcomm Atheros Communications | 187       | 11.21%  |
| Broadcom                        | 105       | 6.29%   |
| IMC Networks                    | 82        | 4.92%   |
| Apple                           | 68        | 4.08%   |
| Foxconn / Hon Hai               | 60        | 3.6%    |
| Lite-On Technology              | 54        | 3.24%   |
| Dell                            | 42        | 2.52%   |
| Hewlett-Packard                 | 35        | 2.1%    |
| Toshiba                         | 32        | 1.92%   |
| Cambridge Silicon Radio         | 22        | 1.32%   |
| Ralink                          | 18        | 1.08%   |
| ASUSTek Computer                | 11        | 0.66%   |
| Realtek                         | 9         | 0.54%   |
| Foxconn International           | 7         | 0.42%   |
| Alps Electric                   | 7         | 0.42%   |
| Ralink Technology               | 3         | 0.18%   |
| Askey Computer                  | 3         | 0.18%   |
| Integrated System Solution      | 2         | 0.12%   |
| Unknown                         | 2         | 0.12%   |
| Taiyo Yuden                     | 1         | 0.06%   |
| Qcom                            | 1         | 0.06%   |
| MediaTek                        | 1         | 0.06%   |
| Conwise Technology              | 1         | 0.06%   |
| Chicony Electronics             | 1         | 0.06%   |
| Belkin Components               | 1         | 0.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 345       | 20.66%  |
| Realtek Bluetooth Radio                             | 120       | 7.19%   |
| Intel AX201 Bluetooth                               | 110       | 6.59%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 99        | 5.93%   |
| Qualcomm Atheros  Bluetooth Device                  | 79        | 4.73%   |
| Intel AX200 Bluetooth                               | 49        | 2.93%   |
| Realtek  Bluetooth 4.2 Adapter                      | 44        | 2.63%   |
| Apple Bluetooth Host Controller                     | 42        | 2.51%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 34        | 2.04%   |
| IMC Networks Bluetooth Device                       | 28        | 1.68%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 27        | 1.62%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 26        | 1.56%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 24        | 1.44%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 22        | 1.32%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 21        | 1.26%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 21        | 1.26%   |
| Lite-On Atheros AR3012 Bluetooth                    | 20        | 1.2%    |
| Intel AX210 Bluetooth                               | 20        | 1.2%    |
| IMC Networks Wireless_Device                        | 20        | 1.2%    |
| Foxconn / Hon Hai Bluetooth Device                  | 19        | 1.14%   |
| Ralink RT3290 Bluetooth                             | 18        | 1.08%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 18        | 1.08%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 18        | 1.08%   |
| IMC Networks Bluetooth Radio                        | 18        | 1.08%   |
| Intel AX211 Bluetooth                               | 17        | 1.02%   |
| Intel Wireless-AC 3168 Bluetooth                    | 15        | 0.9%    |
| Dell DW375 Bluetooth Module                         | 15        | 0.9%    |
| Broadcom BCM2045B (BDC-2.1)                         | 15        | 0.9%    |
| Realtek 802.11ac WLAN Adapter                       | 14        | 0.84%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 14        | 0.84%   |
| HP Broadcom 2070 Bluetooth Combo                    | 14        | 0.84%   |
| Broadcom HP Portable SoftSailing                    | 12        | 0.72%   |
| Apple Bluetooth USB Host Controller                 | 12        | 0.72%   |
| Toshiba Bluetooth Device                            | 10        | 0.6%    |
| Realtek RTL8723B Bluetooth                          | 10        | 0.6%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 10        | 0.6%    |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 10        | 0.6%    |
| Realtek Bluetooth Radio                             | 9         | 0.54%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 9         | 0.54%   |
| Dell BCM20702A0 Bluetooth Module                    | 8         | 0.48%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1823      | 69.85%  |
| AMD                                  | 413       | 15.82%  |
| Nvidia                               | 292       | 11.19%  |
| Generalplus Technology               | 6         | 0.23%   |
| C-Media Electronics                  | 6         | 0.23%   |
| Realtek Semiconductor                | 5         | 0.19%   |
| Lenovo                               | 5         | 0.19%   |
| SteelSeries ApS                      | 4         | 0.15%   |
| Logitech                             | 4         | 0.15%   |
| Silicon Integrated Systems [SiS]     | 3         | 0.11%   |
| PreSonus Audio Electronics           | 3         | 0.11%   |
| Plantronics                          | 3         | 0.11%   |
| JMTek                                | 3         | 0.11%   |
| VIA Technologies                     | 2         | 0.08%   |
| Texas Instruments                    | 2         | 0.08%   |
| Tenx Technology                      | 2         | 0.08%   |
| Sony                                 | 2         | 0.08%   |
| KTMicro                              | 2         | 0.08%   |
| Focusrite-Novation                   | 2         | 0.08%   |
| Creative Technology                  | 2         | 0.08%   |
| Corsair                              | 2         | 0.08%   |
| Apple                                | 2         | 0.08%   |
| XMOS                                 | 1         | 0.04%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.04%   |
| Sennheiser Communications            | 1         | 0.04%   |
| SAVITECH                             | 1         | 0.04%   |
| Roland                               | 1         | 0.04%   |
| Razer USA                            | 1         | 0.04%   |
| Nordic Semiconductor ASA             | 1         | 0.04%   |
| M-Audio                              | 1         | 0.04%   |
| Kingston Technology                  | 1         | 0.04%   |
| Huawei Technologies                  | 1         | 0.04%   |
| Hewlett-Packard                      | 1         | 0.04%   |
| GN Netcom                            | 1         | 0.04%   |
| FiiO Electronics Technology          | 1         | 0.04%   |
| DSEA A/S                             | 1         | 0.04%   |
| Dell                                 | 1         | 0.04%   |
| Conexant Systems                     | 1         | 0.04%   |
| CMX Systems                          | 1         | 0.04%   |
| BEHRINGER International              | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 235       | 7.4%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 233       | 7.33%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 160       | 5.04%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 152       | 4.78%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 125       | 3.93%   |
| Intel 8 Series HD Audio Controller                                                                | 115       | 3.62%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 111       | 3.49%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 109       | 3.43%   |
| AMD FCH Azalia Controller                                                                         | 95        | 2.99%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 92        | 2.9%    |
| Intel Broadwell-U Audio Controller                                                                | 91        | 2.86%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 90        | 2.83%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 79        | 2.49%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 70        | 2.2%    |
| AMD Kabini HDMI/DP Audio                                                                          | 69        | 2.17%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 68        | 2.14%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 62        | 1.95%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 57        | 1.79%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 53        | 1.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 51        | 1.61%   |
| Intel Cannon Lake PCH cAVS                                                                        | 46        | 1.45%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 46        | 1.45%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 40        | 1.26%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 39        | 1.23%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 39        | 1.23%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 38        | 1.2%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 38        | 1.2%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 37        | 1.16%   |
| Intel CM238 HD Audio Controller                                                                   | 36        | 1.13%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 36        | 1.13%   |
| AMD High Definition Audio Controller                                                              | 33        | 1.04%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 31        | 0.98%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 27        | 0.85%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 26        | 0.82%   |
| Intel Comet Lake PCH cAVS                                                                         | 24        | 0.76%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 22        | 0.69%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 17        | 0.54%   |
| Nvidia High Definition Audio Controller                                                           | 17        | 0.54%   |
| Nvidia GA107 High Definition Audio Controller                                                     | 17        | 0.54%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 17        | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 175       | 28.5%   |
| SK hynix               | 132       | 21.5%   |
| Micron Technology      | 82        | 13.36%  |
| Kingston               | 43        | 7%      |
| Unknown                | 37        | 6.03%   |
| Crucial                | 24        | 3.91%   |
| Unknown (ABCD)         | 22        | 3.58%   |
| A-DATA Technology      | 13        | 2.12%   |
| Elpida                 | 12        | 1.95%   |
| Ramaxel Technology     | 9         | 1.47%   |
| Smart                  | 7         | 1.14%   |
| Nanya Technology       | 5         | 0.81%   |
| Patriot                | 4         | 0.65%   |
| Unknown                | 4         | 0.65%   |
| Transcend              | 3         | 0.49%   |
| Timetec                | 3         | 0.49%   |
| Team                   | 3         | 0.49%   |
| G.Skill                | 3         | 0.49%   |
| Corsair                | 3         | 0.49%   |
| Teikon                 | 2         | 0.33%   |
| ff                     | 2         | 0.33%   |
| fef5                   | 2         | 0.33%   |
| 4ea5                   | 2         | 0.33%   |
| Unknown (08B5)         | 1         | 0.16%   |
| Unknown (07F7)         | 1         | 0.16%   |
| Unknown (000080B30080) | 1         | 0.16%   |
| Strontium              | 1         | 0.16%   |
| Smart Brazil           | 1         | 0.16%   |
| Silicon Power          | 1         | 0.16%   |
| SHARETRONIC            | 1         | 0.16%   |
| Qimonda                | 1         | 0.16%   |
| PUSKILL                | 1         | 0.16%   |
| ProMos/Mosel Vitelic   | 1         | 0.16%   |
| pqi                    | 1         | 0.16%   |
| PNY                    | 1         | 0.16%   |
| Netlist                | 1         | 0.16%   |
| Kllisre                | 1         | 0.16%   |
| Kingmax                | 1         | 0.16%   |
| GSkill                 | 1         | 0.16%   |
| Essencore              | 1         | 0.16%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 19        | 2.95%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 11        | 1.71%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 8         | 1.24%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 7         | 1.09%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 7         | 1.09%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 1.09%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 1.09%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 1.09%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 7         | 1.09%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 7         | 1.09%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 0.93%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 6         | 0.93%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.93%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.93%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 6         | 0.93%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 5         | 0.78%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.78%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 5         | 0.78%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.78%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 5         | 0.78%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 5         | 0.78%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 5         | 0.78%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 4         | 0.62%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.62%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.62%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 4         | 0.62%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.62%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.62%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.62%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.62%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 0.62%   |
| Samsung RAM M471A1G44BB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 4         | 0.62%   |
| Samsung RAM M4 70T5663EH3-CF7 2GB SODIMM DDR2 975MT/s            | 4         | 0.62%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 4         | 0.62%   |
| Unknown                                                          | 4         | 0.62%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 3         | 0.47%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 3         | 0.47%   |
| Unknown RAM Module 4096MB Chip DDR4 2133MT/s                     | 3         | 0.47%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM DDR3 2400MT/s     | 3         | 0.47%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 975MT/s         | 3         | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 220       | 42.72%  |
| DDR3    | 184       | 35.73%  |
| LPDDR4  | 42        | 8.16%   |
| DDR2    | 23        | 4.47%   |
| LPDDR3  | 20        | 3.88%   |
| SDRAM   | 11        | 2.14%   |
| LPDDR5  | 5         | 0.97%   |
| Unknown | 5         | 0.97%   |
| DDR5    | 4         | 0.78%   |
| DDR     | 1         | 0.19%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 434       | 83.78%  |
| Row Of Chips | 58        | 11.2%   |
| DIMM         | 9         | 1.74%   |
| Chip         | 9         | 1.74%   |
| Unknown      | 8         | 1.54%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 219       | 38.22%  |
| 4096  | 176       | 30.72%  |
| 2048  | 84        | 14.66%  |
| 16384 | 65        | 11.34%  |
| 1024  | 20        | 3.49%   |
| 32768 | 8         | 1.4%    |
| 512   | 1         | 0.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 123       | 22%     |
| 3200    | 102       | 18.25%  |
| 2667    | 96        | 17.17%  |
| 2400    | 61        | 10.91%  |
| 1334    | 28        | 5.01%   |
| 2133    | 22        | 3.94%   |
| 1333    | 20        | 3.58%   |
| 667     | 12        | 2.15%   |
| 4267    | 11        | 1.97%   |
| Unknown | 10        | 1.79%   |
| 1066    | 9         | 1.61%   |
| 800     | 9         | 1.61%   |
| 3266    | 8         | 1.43%   |
| 2048    | 8         | 1.43%   |
| 1867    | 8         | 1.43%   |
| 6400    | 5         | 0.89%   |
| 8400    | 4         | 0.72%   |
| 4800    | 4         | 0.72%   |
| 1067    | 4         | 0.72%   |
| 975     | 4         | 0.72%   |
| 4199    | 3         | 0.54%   |
| 2933    | 2         | 0.36%   |
| 7467    | 1         | 0.18%   |
| 5600    | 1         | 0.18%   |
| 4266    | 1         | 0.18%   |
| 3733    | 1         | 0.18%   |
| 1866    | 1         | 0.18%   |
| 533     | 1         | 0.18%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 8         | 44.44%  |
| Seiko Epson           | 4         | 22.22%  |
| Canon                 | 2         | 11.11%  |
| Zebra                 | 1         | 5.56%   |
| Samsung Electronics   | 1         | 5.56%   |
| Lexmark International | 1         | 5.56%   |
| Brother Industries    | 1         | 5.56%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                             | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| HP ENVY Photo 6200 series         | 2         | 11.11%  |
| Zebra ZP 450 Printer              | 1         | 5.56%   |
| Seiko Epson XP-235 Series         | 1         | 5.56%   |
| Seiko Epson L3110 Series          | 1         | 5.56%   |
| Seiko Epson ET-2810 Series        | 1         | 5.56%   |
| Seiko Epson AcuLaser C1700        | 1         | 5.56%   |
| Samsung M2020 Series              | 1         | 5.56%   |
| Lexmark International 2400 series | 1         | 5.56%   |
| HP LaserJet P1102                 | 1         | 5.56%   |
| HP LaserJet 1200                  | 1         | 5.56%   |
| HP LaserJet 1000                  | 1         | 5.56%   |
| HP DeskJet 2300 series            | 1         | 5.56%   |
| HP Deskjet 1510                   | 1         | 5.56%   |
| HP DeskJet 1110 series            | 1         | 5.56%   |
| Canon TS3100 series               | 1         | 5.56%   |
| Canon PIXMA MG3000 series         | 1         | 5.56%   |
| Brother MFC-J5730DW               | 1         | 5.56%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Canon       | 5         | 62.5%   |
| Seiko Epson | 3         | 37.5%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X750 [Perfection 4490 Photo] | 3         | 37.5%   |
| Canon CanoScan N670U/N676U/LiDE 20          | 1         | 12.5%   |
| Canon CanoScan LiDE 90                      | 1         | 12.5%   |
| Canon CanoScan LiDE 700F                    | 1         | 12.5%   |
| Canon CanoScan LIDE 25                      | 1         | 12.5%   |
| Canon CanoScan LiDE 110                     | 1         | 12.5%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 460       | 23.48%  |
| Microdia                               | 181       | 9.24%   |
| Realtek Semiconductor                  | 175       | 8.93%   |
| IMC Networks                           | 163       | 8.32%   |
| Sunplus Innovation Technology          | 118       | 6.02%   |
| Bison Electronics                      | 117       | 5.97%   |
| Quanta                                 | 98        | 5%      |
| Cheng Uei Precision Industry (Foxlink) | 96        | 4.9%    |
| Suyin                                  | 78        | 3.98%   |
| Syntek                                 | 57        | 2.91%   |
| Apple                                  | 55        | 2.81%   |
| Lite-On Technology                     | 44        | 2.25%   |
| Alcor Micro                            | 36        | 1.84%   |
| Silicon Motion                         | 35        | 1.79%   |
| Luxvisions Innotech Limited            | 28        | 1.43%   |
| Acer                                   | 27        | 1.38%   |
| Ricoh                                  | 22        | 1.12%   |
| Sonix Technology                       | 17        | 0.87%   |
| Logitech                               | 16        | 0.82%   |
| icSpring                               | 14        | 0.71%   |
| Primax Electronics                     | 12        | 0.61%   |
| SunplusIT                              | 9         | 0.46%   |
| Samsung Electronics                    | 9         | 0.46%   |
| Lenovo                                 | 9         | 0.46%   |
| ALi                                    | 8         | 0.41%   |
| Importek                               | 7         | 0.36%   |
| Z-Star Microelectronics                | 6         | 0.31%   |
| Y Media                                | 5         | 0.26%   |
| OmniVision Technologies                | 5         | 0.26%   |
| GEMBIRD                                | 5         | 0.26%   |
| Microsoft                              | 4         | 0.2%    |
| Sunplus Technology                     | 3         | 0.15%   |
| Intel                                  | 3         | 0.15%   |
| Genesys Logic                          | 3         | 0.15%   |
| Generalplus Technology                 | 3         | 0.15%   |
| ARC International                      | 3         | 0.15%   |
| Unknown                                | 3         | 0.15%   |
| Tripath Technology                     | 2         | 0.1%    |
| KYE Systems (Mouse Systems)            | 2         | 0.1%    |
| YGTek                                  | 1         | 0.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 79        | 4.02%   |
| Microdia Integrated_Webcam_HD                       | 48        | 2.44%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 41        | 2.09%   |
| Chicony HD WebCam                                   | 41        | 2.09%   |
| Syntek Integrated Camera                            | 35        | 1.78%   |
| Realtek Integrated_Webcam_HD                        | 32        | 1.63%   |
| IMC Networks Integrated Camera                      | 31        | 1.58%   |
| Bison Integrated Camera                             | 30        | 1.53%   |
| Chicony HP Truevision HD                            | 28        | 1.42%   |
| Microdia Integrated Webcam                          | 26        | 1.32%   |
| Chicony TOSHIBA Web Camera - HD                     | 26        | 1.32%   |
| Sunplus Integrated_Webcam_HD                        | 25        | 1.27%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 22        | 1.12%   |
| Bison Lenovo EasyCamera                             | 21        | 1.07%   |
| Realtek USB Camera                                  | 19        | 0.97%   |
| Lite-On HP HD Camera                                | 18        | 0.92%   |
| Alcor Micro USB 2.0 Camera                          | 18        | 0.92%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 17        | 0.87%   |
| Sunplus HD WebCam                                   | 16        | 0.81%   |
| Quanta HD User Facing                               | 16        | 0.81%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 16        | 0.81%   |
| Apple Built-in iSight                               | 16        | 0.81%   |
| Realtek Integrated Webcam                           | 15        | 0.76%   |
| Realtek HP Truevision HD                            | 15        | 0.76%   |
| Chicony Lenovo EasyCamera                           | 15        | 0.76%   |
| Apple FaceTime HD Camera                            | 15        | 0.76%   |
| icSpring camera                                     | 14        | 0.71%   |
| Chicony VGA WebCam                                  | 14        | 0.71%   |
| Chicony USB2.0 VGA UVC WebCam                       | 14        | 0.71%   |
| Chicony HP Truevision HD camera                     | 14        | 0.71%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                  | 14        | 0.71%   |
| Realtek Integrated Webcam HD                        | 13        | 0.66%   |
| Quanta HP Wide Vision HD Camera                     | 13        | 0.66%   |
| Chicony HP HD Camera                                | 13        | 0.66%   |
| Chicony EasyCamera                                  | 13        | 0.66%   |
| Sonix USB2.0 HD UVC WebCam                          | 12        | 0.61%   |
| Chicony HP HD Webcam                                | 12        | 0.61%   |
| Cheng Uei Precision Industry (Foxlink) Webcam       | 12        | 0.61%   |
| Realtek Lenovo EasyCamera                           | 11        | 0.56%   |
| Quanta HP TrueVision HD Camera                      | 11        | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 152       | 45.24%  |
| Synaptics                          | 43        | 12.8%   |
| Shenzhen Goodix Technology         | 39        | 11.61%  |
| AuthenTec                          | 38        | 11.31%  |
| Upek                               | 26        | 7.74%   |
| Elan Microelectronics              | 16        | 4.76%   |
| LighTuning Technology              | 9         | 2.68%   |
| STMicroelectronics                 | 7         | 2.08%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 0.89%   |
| Samsung Electronics                | 2         | 0.6%    |
| Focal-systems.Corp                 | 1         | 0.3%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 32        | 9.52%   |
| Shenzhen Goodix  Fingerprint Device                                        | 29        | 8.63%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 24        | 7.14%   |
| Validity Sensors VFS491                                                    | 16        | 4.76%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 16        | 4.76%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 15        | 4.46%   |
| Validity Sensors Fingerprint scanner                                       | 12        | 3.57%   |
| AuthenTec AES2810                                                          | 12        | 3.57%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 12        | 3.57%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 11        | 3.27%   |
| Elan ELAN:ARM-M4                                                           | 11        | 3.27%   |
| Validity Sensors Synaptics WBDI                                            | 10        | 2.98%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 9         | 2.68%   |
| Synaptics Fingerprint reader [HP G6]                                       | 9         | 2.68%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 8         | 2.38%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 8         | 2.38%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 2.38%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 2.08%   |
| Shenzhen Goodix Fingerprint Reader                                         | 7         | 2.08%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 1.79%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 6         | 1.79%   |
| AuthenTec Fingerprint Sensor                                               | 5         | 1.49%   |
| AuthenTec AES1600                                                          | 5         | 1.49%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 1.19%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 1.19%   |
| Validity Sensors VFS Fingerprint sensor                                    | 4         | 1.19%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 3         | 0.89%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 0.89%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 0.89%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 0.89%   |
| Elan ELAN:Fingerprint                                                      | 3         | 0.89%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 0.6%    |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.6%    |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 0.6%    |
| Synaptics WBDI                                                             | 2         | 0.6%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 0.6%    |
| Synaptics Prometheus Fingerprint Reader                                    | 2         | 0.6%    |
| LighTuning Fingerprint Reader                                              | 2         | 0.6%    |
| Elan WBF Fingerprint Sensor                                                | 2         | 0.6%    |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 0.6%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 84        | 56%     |
| Alcor Micro                       | 26        | 17.33%  |
| O2 Micro                          | 16        | 10.67%  |
| Upek                              | 7         | 4.67%   |
| Lenovo                            | 7         | 4.67%   |
| Yubico.com                        | 2         | 1.33%   |
| VASCO Data Security International | 2         | 1.33%   |
| SCM Microsystems                  | 2         | 1.33%   |
| Realtek Semiconductor             | 1         | 0.67%   |
| OmniKey                           | 1         | 0.67%   |
| Gemalto (was Gemplus)             | 1         | 0.67%   |
| Fujitsu Siemens Computers         | 1         | 0.67%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 32        | 21.33%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 26        | 17.33%  |
| Broadcom 5880                                                                | 25        | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 21        | 14%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 15        | 10%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 7         | 4.67%   |
| Lenovo Integrated Smart Card Reader                                          | 7         | 4.67%   |
| Broadcom 58200                                                               | 4         | 2.67%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 1.33%   |
| VASCO Data Security International DIGIPASS 870                               | 2         | 1.33%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 1.33%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 1.33%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.67%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.67%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.67%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.67%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.67%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1504      | 65.14%  |
| 1     | 613       | 26.55%  |
| 2     | 168       | 7.28%   |
| 3     | 22        | 0.95%   |
| 4     | 2         | 0.09%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 329       | 33.23%  |
| Graphics card            | 188       | 18.99%  |
| Chipcard                 | 142       | 14.34%  |
| Net/wireless             | 116       | 11.72%  |
| Multimedia controller    | 108       | 10.91%  |
| Storage                  | 30        | 3.03%   |
| Bluetooth                | 24        | 2.42%   |
| Sound                    | 10        | 1.01%   |
| Communication controller | 10        | 1.01%   |
| Camera                   | 7         | 0.71%   |
| Net/ethernet             | 5         | 0.51%   |
| Card reader              | 5         | 0.51%   |
| Network                  | 3         | 0.3%    |
| Modem                    | 3         | 0.3%    |
| Flash memory             | 3         | 0.3%    |
| Storage/nvme             | 2         | 0.2%    |
| Storage/ide              | 2         | 0.2%    |
| Dvb card                 | 2         | 0.2%    |
| Unclassified device      | 1         | 0.1%    |

