Linux in Sweden - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Sweden.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Sweden/Desktop/README.md) and [notebooks](/Location/Sweden/Notebook/README.md).

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

Total: 2747

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Acer          | Predator G3-605             | Desktop     | [eb21663788](https://linux-hardware.org/?probe=eb21663788) | Apr 01, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [06275c19f3](https://linux-hardware.org/?probe=06275c19f3) | Apr 01, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [36e57fb4cf](https://linux-hardware.org/?probe=36e57fb4cf) | Apr 01, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [1fa4ec7b05](https://linux-hardware.org/?probe=1fa4ec7b05) | Apr 01, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [a89c429c84](https://linux-hardware.org/?probe=a89c429c84) | Mar 31, 2023 |
| Acer          | Swift SF113-31              | Notebook    | [fc0539603c](https://linux-hardware.org/?probe=fc0539603c) | Mar 31, 2023 |
| HP            | 82B4                        | Desktop     | [9712d04ab5](https://linux-hardware.org/?probe=9712d04ab5) | Mar 30, 2023 |
| HP            | ENVY TS Sleekbook 4         | Notebook    | [f897573506](https://linux-hardware.org/?probe=f897573506) | Mar 29, 2023 |
| Fujitsu       | LIFEBOOK U938               | Notebook    | [e972904a83](https://linux-hardware.org/?probe=e972904a83) | Mar 28, 2023 |
| MSI           | Z170A SLI PLUS              | Desktop     | [50affe59d1](https://linux-hardware.org/?probe=50affe59d1) | Mar 28, 2023 |
| ASUSTek       | TP410UA                     | Convertible | [b74b7f7d31](https://linux-hardware.org/?probe=b74b7f7d31) | Mar 28, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [f0e6089a6e](https://linux-hardware.org/?probe=f0e6089a6e) | Mar 28, 2023 |
| Acer          | Nitro N50-640               | Desktop     | [2219ec0fad](https://linux-hardware.org/?probe=2219ec0fad) | Mar 27, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [011d1b8bf7](https://linux-hardware.org/?probe=011d1b8bf7) | Mar 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | Notebook    | [9fd0ee0183](https://linux-hardware.org/?probe=9fd0ee0183) | Mar 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | Notebook    | [d0f84e1bd4](https://linux-hardware.org/?probe=d0f84e1bd4) | Mar 27, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [c5a3b374a7](https://linux-hardware.org/?probe=c5a3b374a7) | Mar 27, 2023 |
| MSI           | Z170A SLI PLUS              | Desktop     | [8a1c592e98](https://linux-hardware.org/?probe=8a1c592e98) | Mar 27, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [eef16c5e09](https://linux-hardware.org/?probe=eef16c5e09) | Mar 27, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [f403538019](https://linux-hardware.org/?probe=f403538019) | Mar 26, 2023 |
| HP            | 1998                        | Desktop     | [346f37956b](https://linux-hardware.org/?probe=346f37956b) | Mar 26, 2023 |
| Gigabyte      | AORUS 15G KC                | Notebook    | [d87e89d84f](https://linux-hardware.org/?probe=d87e89d84f) | Mar 26, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [6f9300474f](https://linux-hardware.org/?probe=6f9300474f) | Mar 26, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [d1baffa910](https://linux-hardware.org/?probe=d1baffa910) | Mar 25, 2023 |
| HP            | 2B05                        | Desktop     | [b34e6d230c](https://linux-hardware.org/?probe=b34e6d230c) | Mar 24, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [b2cdf1deb7](https://linux-hardware.org/?probe=b2cdf1deb7) | Mar 24, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [1e549ae67e](https://linux-hardware.org/?probe=1e549ae67e) | Mar 24, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [09fec047e4](https://linux-hardware.org/?probe=09fec047e4) | Mar 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e7b4dc0fd4](https://linux-hardware.org/?probe=e7b4dc0fd4) | Mar 23, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [bf24fe6112](https://linux-hardware.org/?probe=bf24fe6112) | Mar 23, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QH... | Notebook    | [883d4de906](https://linux-hardware.org/?probe=883d4de906) | Mar 21, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [b4c65fead7](https://linux-hardware.org/?probe=b4c65fead7) | Mar 21, 2023 |
| Shuttle       | SH570                       | Desktop     | [3ef2bf52b7](https://linux-hardware.org/?probe=3ef2bf52b7) | Mar 21, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [240444cad9](https://linux-hardware.org/?probe=240444cad9) | Mar 21, 2023 |
| Acer          | Aspire M3-581T              | Notebook    | [a9a586ef2d](https://linux-hardware.org/?probe=a9a586ef2d) | Mar 20, 2023 |
| Acer          | Aspire M3-581T              | Notebook    | [51e5415bb0](https://linux-hardware.org/?probe=51e5415bb0) | Mar 19, 2023 |
| Schenker      | VISION 15 (SVS15E21)        | Notebook    | [c88d5f831a](https://linux-hardware.org/?probe=c88d5f831a) | Mar 19, 2023 |
| Intel         | NUC5CPYB H61145-412         | Mini pc     | [a87d0fe300](https://linux-hardware.org/?probe=a87d0fe300) | Mar 19, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [bd119c8898](https://linux-hardware.org/?probe=bd119c8898) | Mar 17, 2023 |
| MSI           | Z370 GAMING PRO CARBON      | Desktop     | [87ba801b00](https://linux-hardware.org/?probe=87ba801b00) | Mar 17, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [f219a6e14a](https://linux-hardware.org/?probe=f219a6e14a) | Mar 17, 2023 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [d95b09eda0](https://linux-hardware.org/?probe=d95b09eda0) | Mar 17, 2023 |
| Acer          | Aspire M3-581T              | Notebook    | [dfb8518fa9](https://linux-hardware.org/?probe=dfb8518fa9) | Mar 16, 2023 |
| Acer          | Aspire M3-581T              | Notebook    | [bb4f0202b7](https://linux-hardware.org/?probe=bb4f0202b7) | Mar 16, 2023 |
| Lenovo        | ThinkPad X390 20Q0000SMX    | Notebook    | [69f39892c4](https://linux-hardware.org/?probe=69f39892c4) | Mar 15, 2023 |
| Google        | Rabbid                      | Notebook    | [621762ceec](https://linux-hardware.org/?probe=621762ceec) | Mar 15, 2023 |
| Lenovo        | ThinkPad X390 20Q0000SMX    | Notebook    | [8fff8ca97d](https://linux-hardware.org/?probe=8fff8ca97d) | Mar 15, 2023 |
| ASUSTek       | X550MD                      | Notebook    | [2cd5ae8a43](https://linux-hardware.org/?probe=2cd5ae8a43) | Mar 15, 2023 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [016f5cd3be](https://linux-hardware.org/?probe=016f5cd3be) | Mar 14, 2023 |
| Lenovo        | ThinkCentre M58 7638CB8     | Desktop     | [d303f78e26](https://linux-hardware.org/?probe=d303f78e26) | Mar 14, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [070c7d809a](https://linux-hardware.org/?probe=070c7d809a) | Mar 13, 2023 |
| GPD           | P2 MAX                      | Notebook    | [dd958bf28e](https://linux-hardware.org/?probe=dd958bf28e) | Mar 13, 2023 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | Notebook    | [ff9cb78f74](https://linux-hardware.org/?probe=ff9cb78f74) | Mar 13, 2023 |
| Dell          | 0Y2MRG A00                  | Desktop     | [12120178de](https://linux-hardware.org/?probe=12120178de) | Mar 13, 2023 |
| Lenovo        | ThinkPad T510 4313CTO       | Notebook    | [c2f9a6e354](https://linux-hardware.org/?probe=c2f9a6e354) | Mar 13, 2023 |
| HP            | 1825                        | Desktop     | [85011ed37d](https://linux-hardware.org/?probe=85011ed37d) | Mar 12, 2023 |
| Lenovo        | ThinkPad T480s 20L8S7AS0... | Notebook    | [87ef2f6efb](https://linux-hardware.org/?probe=87ef2f6efb) | Mar 12, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [1169593829](https://linux-hardware.org/?probe=1169593829) | Mar 12, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [76e4cc71f5](https://linux-hardware.org/?probe=76e4cc71f5) | Mar 12, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [75fc2c0a15](https://linux-hardware.org/?probe=75fc2c0a15) | Mar 12, 2023 |
| HP            | 1998                        | Desktop     | [68d7c4350d](https://linux-hardware.org/?probe=68d7c4350d) | Mar 12, 2023 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [c22a046fc6](https://linux-hardware.org/?probe=c22a046fc6) | Mar 11, 2023 |
| SiYW          | V200 Series                 | Desktop     | [7c3751c888](https://linux-hardware.org/?probe=7c3751c888) | Mar 11, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [0555c85a89](https://linux-hardware.org/?probe=0555c85a89) | Mar 11, 2023 |
| HP            | 18E5                        | Desktop     | [82e5831486](https://linux-hardware.org/?probe=82e5831486) | Mar 10, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [03f44a913e](https://linux-hardware.org/?probe=03f44a913e) | Mar 08, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [4d15122995](https://linux-hardware.org/?probe=4d15122995) | Mar 07, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [cc6e719e99](https://linux-hardware.org/?probe=cc6e719e99) | Mar 07, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [d1768ecbaa](https://linux-hardware.org/?probe=d1768ecbaa) | Mar 07, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [15cd198548](https://linux-hardware.org/?probe=15cd198548) | Mar 07, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [081ecd2050](https://linux-hardware.org/?probe=081ecd2050) | Mar 07, 2023 |
| HP            | Presario CQ57               | Notebook    | [33b1812664](https://linux-hardware.org/?probe=33b1812664) | Mar 06, 2023 |
| HP            | Presario CQ57               | Notebook    | [26ec55c2cb](https://linux-hardware.org/?probe=26ec55c2cb) | Mar 06, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [0d202dc031](https://linux-hardware.org/?probe=0d202dc031) | Mar 06, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [baff849073](https://linux-hardware.org/?probe=baff849073) | Mar 05, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [8814af9b71](https://linux-hardware.org/?probe=8814af9b71) | Mar 05, 2023 |
| HP            | 2B05                        | Desktop     | [deb075440f](https://linux-hardware.org/?probe=deb075440f) | Mar 05, 2023 |
| HP            | 2B05                        | Desktop     | [f21bd9cc58](https://linux-hardware.org/?probe=f21bd9cc58) | Mar 05, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [14211fd55f](https://linux-hardware.org/?probe=14211fd55f) | Mar 04, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [19bd4c1e4e](https://linux-hardware.org/?probe=19bd4c1e4e) | Mar 04, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [f9a2075d54](https://linux-hardware.org/?probe=f9a2075d54) | Mar 04, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | Notebook    | [10c12a6b8a](https://linux-hardware.org/?probe=10c12a6b8a) | Mar 04, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [767045c44e](https://linux-hardware.org/?probe=767045c44e) | Mar 03, 2023 |
| Dell          | Precision 3551              | Notebook    | [7c1bc8355a](https://linux-hardware.org/?probe=7c1bc8355a) | Mar 03, 2023 |
| Clevo         | W25xHNx                     | Notebook    | [5227127f81](https://linux-hardware.org/?probe=5227127f81) | Mar 03, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [582bc638e0](https://linux-hardware.org/?probe=582bc638e0) | Mar 03, 2023 |
| Gigabyte      | A520M DS3H                  | Desktop     | [f3defb812b](https://linux-hardware.org/?probe=f3defb812b) | Mar 03, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | Desktop     | [41d9c3d9ed](https://linux-hardware.org/?probe=41d9c3d9ed) | Mar 02, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [a279108842](https://linux-hardware.org/?probe=a279108842) | Mar 02, 2023 |
| Fujitsu       | D3224-P1 S26361-D3224-P1    | Desktop     | [53649a9546](https://linux-hardware.org/?probe=53649a9546) | Feb 28, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [45403acec9](https://linux-hardware.org/?probe=45403acec9) | Feb 27, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [3cd0e65d1f](https://linux-hardware.org/?probe=3cd0e65d1f) | Feb 27, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [2fe31a709a](https://linux-hardware.org/?probe=2fe31a709a) | Feb 27, 2023 |
| Lenovo        | ThinkPad T480s 20L8S7AS0... | Notebook    | [bd62e34a09](https://linux-hardware.org/?probe=bd62e34a09) | Feb 27, 2023 |
| ASUSTek       | PRIME X299-A                | Desktop     | [5ef01d46d4](https://linux-hardware.org/?probe=5ef01d46d4) | Feb 25, 2023 |
| Lenovo        | ThinkPad T470s 20HGS0AE0... | Notebook    | [7f8c9de1aa](https://linux-hardware.org/?probe=7f8c9de1aa) | Feb 24, 2023 |
| MSI           | Z370 GAMING PRO CARBON      | Desktop     | [fc86b476d7](https://linux-hardware.org/?probe=fc86b476d7) | Feb 22, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [de328ac1ad](https://linux-hardware.org/?probe=de328ac1ad) | Feb 22, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D9... | Notebook    | [da461191e8](https://linux-hardware.org/?probe=da461191e8) | Feb 21, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [54b9c4c95c](https://linux-hardware.org/?probe=54b9c4c95c) | Feb 21, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [ecc97fee86](https://linux-hardware.org/?probe=ecc97fee86) | Feb 21, 2023 |
| Dell          | Precision M4800             | Notebook    | [b8e31b63ce](https://linux-hardware.org/?probe=b8e31b63ce) | Feb 20, 2023 |
| ASUSTek       | ROG Strix G712LWS_G712LW... | Notebook    | [05ce3a9038](https://linux-hardware.org/?probe=05ce3a9038) | Feb 20, 2023 |
| ASUSTek       | ROG Strix G712LWS_G712LW... | Notebook    | [661017eb0b](https://linux-hardware.org/?probe=661017eb0b) | Feb 20, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [bd6a746c89](https://linux-hardware.org/?probe=bd6a746c89) | Feb 20, 2023 |
| ASUSTek       | G501VW                      | Notebook    | [6e014311b2](https://linux-hardware.org/?probe=6e014311b2) | Feb 20, 2023 |
| MSI           | Z170A GAMING M5             | Desktop     | [5aa73f71fd](https://linux-hardware.org/?probe=5aa73f71fd) | Feb 20, 2023 |
| Acer          | Aspire A317-33              | Notebook    | [7427fa6886](https://linux-hardware.org/?probe=7427fa6886) | Feb 19, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [d4fdbbf1ba](https://linux-hardware.org/?probe=d4fdbbf1ba) | Feb 19, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [a11d164d69](https://linux-hardware.org/?probe=a11d164d69) | Feb 19, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [2b56edae65](https://linux-hardware.org/?probe=2b56edae65) | Feb 19, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [dde311dcb2](https://linux-hardware.org/?probe=dde311dcb2) | Feb 19, 2023 |
| ASUSTek       | X555LJ                      | Notebook    | [93f3ae1f77](https://linux-hardware.org/?probe=93f3ae1f77) | Feb 19, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [96b350db9f](https://linux-hardware.org/?probe=96b350db9f) | Feb 18, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [f594570a77](https://linux-hardware.org/?probe=f594570a77) | Feb 16, 2023 |
| MSI           | Z170A KRAIT GAMING 3X       | Desktop     | [8e521a2efc](https://linux-hardware.org/?probe=8e521a2efc) | Feb 16, 2023 |
| GPD           | P2 MAX                      | Notebook    | [9a623b2196](https://linux-hardware.org/?probe=9a623b2196) | Feb 16, 2023 |
| Fujitsu Si... | LIFEBOOK E8310              | Notebook    | [eac9c046ac](https://linux-hardware.org/?probe=eac9c046ac) | Feb 15, 2023 |
| Fujitsu Si... | LIFEBOOK E8310              | Notebook    | [3717c2476f](https://linux-hardware.org/?probe=3717c2476f) | Feb 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [7cdc5a7d89](https://linux-hardware.org/?probe=7cdc5a7d89) | Feb 15, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [4e3ff30332](https://linux-hardware.org/?probe=4e3ff30332) | Feb 15, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [eb40144624](https://linux-hardware.org/?probe=eb40144624) | Feb 13, 2023 |
| HP            | 8455                        | Desktop     | [f75db6c5d5](https://linux-hardware.org/?probe=f75db6c5d5) | Feb 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [28e98cf31f](https://linux-hardware.org/?probe=28e98cf31f) | Feb 12, 2023 |
| ASUSTek       | ROG STRIX H470-I GAMING     | Desktop     | [3a18e2226c](https://linux-hardware.org/?probe=3a18e2226c) | Feb 12, 2023 |
| ASUSTek       | Z97-P                       | Desktop     | [004535fd1c](https://linux-hardware.org/?probe=004535fd1c) | Feb 11, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [7a6b34f58c](https://linux-hardware.org/?probe=7a6b34f58c) | Feb 11, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [c1ac37fee3](https://linux-hardware.org/?probe=c1ac37fee3) | Feb 10, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [6d9d60d4b8](https://linux-hardware.org/?probe=6d9d60d4b8) | Feb 10, 2023 |
| MSI           | MS-B120                     | Mini pc     | [1d365cbddd](https://linux-hardware.org/?probe=1d365cbddd) | Feb 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | Notebook    | [8239d80ae0](https://linux-hardware.org/?probe=8239d80ae0) | Feb 10, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [a60a4191b8](https://linux-hardware.org/?probe=a60a4191b8) | Feb 10, 2023 |
| Dell          | Latitude E7250              | Notebook    | [e3c1b1e038](https://linux-hardware.org/?probe=e3c1b1e038) | Feb 09, 2023 |
| AZW           | GTR V01                     | Mini pc     | [2898aebf10](https://linux-hardware.org/?probe=2898aebf10) | Feb 08, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [fd61c4416f](https://linux-hardware.org/?probe=fd61c4416f) | Feb 08, 2023 |
| Dell          | Latitude E7250              | Notebook    | [b4a7701aa4](https://linux-hardware.org/?probe=b4a7701aa4) | Feb 07, 2023 |
| HP            | EliteBook 835 G8 Noteboo... | Notebook    | [3797cf0990](https://linux-hardware.org/?probe=3797cf0990) | Feb 07, 2023 |
| ASUSTek       | EB1501P                     | Desktop     | [687e52dcb1](https://linux-hardware.org/?probe=687e52dcb1) | Feb 06, 2023 |
| Acer          | Aspire XC-895 V:1.0         | Desktop     | [e553ba2549](https://linux-hardware.org/?probe=e553ba2549) | Feb 06, 2023 |
| Acer          | Aspire XC-895 V:1.0         | Desktop     | [d888ff5291](https://linux-hardware.org/?probe=d888ff5291) | Feb 06, 2023 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [0c6df9267b](https://linux-hardware.org/?probe=0c6df9267b) | Feb 04, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [452216b5ed](https://linux-hardware.org/?probe=452216b5ed) | Feb 04, 2023 |
| Lenovo        | ThinkPad P50 20EN001SUS     | Notebook    | [bbe182e4c2](https://linux-hardware.org/?probe=bbe182e4c2) | Feb 04, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [f265a0e81e](https://linux-hardware.org/?probe=f265a0e81e) | Feb 04, 2023 |
| ASUSTek       | PN51-E1                     | Mini pc     | [9e2380e15d](https://linux-hardware.org/?probe=9e2380e15d) | Feb 03, 2023 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [fac45201b3](https://linux-hardware.org/?probe=fac45201b3) | Feb 02, 2023 |
| Lenovo        | IdeaPad 720S-15IKB 81AC     | Notebook    | [1752779e0c](https://linux-hardware.org/?probe=1752779e0c) | Feb 02, 2023 |
| Lenovo        | IdeaPad 720S-15IKB 81AC     | Notebook    | [ef707954b8](https://linux-hardware.org/?probe=ef707954b8) | Feb 02, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [6e089e22b1](https://linux-hardware.org/?probe=6e089e22b1) | Feb 01, 2023 |
| Dell          | Latitude 7420               | Notebook    | [f0b8816283](https://linux-hardware.org/?probe=f0b8816283) | Feb 01, 2023 |
| MSI           | MAG Z590 TORPEDO            | Desktop     | [431a6c7a3a](https://linux-hardware.org/?probe=431a6c7a3a) | Feb 01, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [f1a9c37047](https://linux-hardware.org/?probe=f1a9c37047) | Jan 31, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [fe2a413caa](https://linux-hardware.org/?probe=fe2a413caa) | Jan 31, 2023 |
| Dell          | Latitude 7420               | Notebook    | [55f81648a1](https://linux-hardware.org/?probe=55f81648a1) | Jan 31, 2023 |
| Dell          | Latitude 7480               | Notebook    | [f3a84b494f](https://linux-hardware.org/?probe=f3a84b494f) | Jan 30, 2023 |
| Dell          | Latitude D630C              | Notebook    | [401357bc99](https://linux-hardware.org/?probe=401357bc99) | Jan 30, 2023 |
| Acer          | Swift SF114-31              | Notebook    | [9d7f73242e](https://linux-hardware.org/?probe=9d7f73242e) | Jan 30, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [8ef4f014f2](https://linux-hardware.org/?probe=8ef4f014f2) | Jan 27, 2023 |
| Gigabyte      | 970A-D3P                    | Desktop     | [f01366b131](https://linux-hardware.org/?probe=f01366b131) | Jan 27, 2023 |
| Dell          | 0Y2MRG A00                  | Desktop     | [54ba66711b](https://linux-hardware.org/?probe=54ba66711b) | Jan 26, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HM... | Notebook    | [26f64a2ad0](https://linux-hardware.org/?probe=26f64a2ad0) | Jan 26, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [756bf12bd7](https://linux-hardware.org/?probe=756bf12bd7) | Jan 25, 2023 |
| Valve         | Jupiter                     | Notebook    | [c4a13a66ed](https://linux-hardware.org/?probe=c4a13a66ed) | Jan 25, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [cb00a3e89d](https://linux-hardware.org/?probe=cb00a3e89d) | Jan 24, 2023 |
| Google        | Link                        | Notebook    | [5c44e38153](https://linux-hardware.org/?probe=5c44e38153) | Jan 23, 2023 |
| Valve         | Jupiter                     | Notebook    | [1a9bed0cf3](https://linux-hardware.org/?probe=1a9bed0cf3) | Jan 23, 2023 |
| Dell          | 0Y56T3 A00                  | Desktop     | [7078ea91e9](https://linux-hardware.org/?probe=7078ea91e9) | Jan 22, 2023 |
| AZW           | GTR V01                     | Mini pc     | [1d4c2002d5](https://linux-hardware.org/?probe=1d4c2002d5) | Jan 22, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [9792de46ad](https://linux-hardware.org/?probe=9792de46ad) | Jan 22, 2023 |
| AMI           | Intel                       | Notebook    | [53a3ba4e8a](https://linux-hardware.org/?probe=53a3ba4e8a) | Jan 21, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [fa1f3d8e3b](https://linux-hardware.org/?probe=fa1f3d8e3b) | Jan 21, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [1d10977303](https://linux-hardware.org/?probe=1d10977303) | Jan 21, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [fdbbb4a832](https://linux-hardware.org/?probe=fdbbb4a832) | Jan 21, 2023 |
| Lenovo        | 3730 SDK0T76465 WIN 3422... | Desktop     | [80e51b3319](https://linux-hardware.org/?probe=80e51b3319) | Jan 20, 2023 |
| Acer          | Aspire V3-571               | Notebook    | [d7e7799006](https://linux-hardware.org/?probe=d7e7799006) | Jan 20, 2023 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | Desktop     | [9a70fa222c](https://linux-hardware.org/?probe=9a70fa222c) | Jan 19, 2023 |
| Kllisre       | X99-B5 V1.1                 | Desktop     | [e221c08388](https://linux-hardware.org/?probe=e221c08388) | Jan 18, 2023 |
| Kllisre       | X99-B5 V1.1                 | Desktop     | [d2bb65ed09](https://linux-hardware.org/?probe=d2bb65ed09) | Jan 18, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [6d6698b316](https://linux-hardware.org/?probe=6d6698b316) | Jan 18, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [8bfae8a964](https://linux-hardware.org/?probe=8bfae8a964) | Jan 17, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [0e57f4ecbe](https://linux-hardware.org/?probe=0e57f4ecbe) | Jan 15, 2023 |
| Star Labs     | StarBook                    | Notebook    | [784ae24356](https://linux-hardware.org/?probe=784ae24356) | Jan 15, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [5b26575c52](https://linux-hardware.org/?probe=5b26575c52) | Jan 15, 2023 |
| Acer          | Aspire A315-43              | Notebook    | [06dfad94f5](https://linux-hardware.org/?probe=06dfad94f5) | Jan 15, 2023 |
| Radxa         | ROCK Pi 4B                  | Soc         | [0533348a3f](https://linux-hardware.org/?probe=0533348a3f) | Jan 14, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [b0308f4270](https://linux-hardware.org/?probe=b0308f4270) | Jan 13, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [bb85f0bdc7](https://linux-hardware.org/?probe=bb85f0bdc7) | Jan 12, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [73da880450](https://linux-hardware.org/?probe=73da880450) | Jan 12, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING       | Desktop     | [262fe40796](https://linux-hardware.org/?probe=262fe40796) | Jan 12, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING       | Desktop     | [18bdf2650e](https://linux-hardware.org/?probe=18bdf2650e) | Jan 12, 2023 |
| ASUSTek       | GA15DH                      | Desktop     | [e480a3bfa3](https://linux-hardware.org/?probe=e480a3bfa3) | Jan 11, 2023 |
| Dell          | Studio 1749                 | Notebook    | [28a19b2c03](https://linux-hardware.org/?probe=28a19b2c03) | Jan 11, 2023 |
| ASUSTek       | N552VX                      | Notebook    | [7697ff8cb4](https://linux-hardware.org/?probe=7697ff8cb4) | Jan 11, 2023 |
| Lenovo        | 30C7 SDK0J40700 WIN 3258... | Desktop     | [994306b125](https://linux-hardware.org/?probe=994306b125) | Jan 11, 2023 |
| Gigabyte      | GA-A75M-D2H                 | Desktop     | [72bf3e7a8b](https://linux-hardware.org/?probe=72bf3e7a8b) | Jan 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [25090a9dcb](https://linux-hardware.org/?probe=25090a9dcb) | Jan 11, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [aacfe1b351](https://linux-hardware.org/?probe=aacfe1b351) | Jan 11, 2023 |
| Toshiba       | Satellite L50D-B            | Notebook    | [5cfaf7d715](https://linux-hardware.org/?probe=5cfaf7d715) | Jan 10, 2023 |
| ASUSTek       | N552VX                      | Notebook    | [59155b3092](https://linux-hardware.org/?probe=59155b3092) | Jan 10, 2023 |
| Dell          | XPS 13 9343                 | Notebook    | [ac85316fc2](https://linux-hardware.org/?probe=ac85316fc2) | Jan 09, 2023 |
| MSI           | GP60 2PE                    | Notebook    | [e1506ca6f6](https://linux-hardware.org/?probe=e1506ca6f6) | Jan 09, 2023 |
| Acer          | Aspire A515-54G             | Notebook    | [dea6736468](https://linux-hardware.org/?probe=dea6736468) | Jan 09, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HM... | Notebook    | [8be13470fb](https://linux-hardware.org/?probe=8be13470fb) | Jan 09, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [980ee9f42c](https://linux-hardware.org/?probe=980ee9f42c) | Jan 07, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [be1be100c9](https://linux-hardware.org/?probe=be1be100c9) | Jan 07, 2023 |
| Samsung       | R530/R730                   | Notebook    | [9a138871a6](https://linux-hardware.org/?probe=9a138871a6) | Jan 06, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [e64152748d](https://linux-hardware.org/?probe=e64152748d) | Jan 06, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [0cca8fbbb6](https://linux-hardware.org/?probe=0cca8fbbb6) | Jan 05, 2023 |
| Samsung       | R530/R730                   | Notebook    | [dd26df5f4f](https://linux-hardware.org/?probe=dd26df5f4f) | Jan 05, 2023 |
| Dell          | Precision M90               | Notebook    | [b622160555](https://linux-hardware.org/?probe=b622160555) | Jan 05, 2023 |
| HP            | Pavilion g6                 | Notebook    | [6cae064dc5](https://linux-hardware.org/?probe=6cae064dc5) | Jan 04, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [a24229bc3b](https://linux-hardware.org/?probe=a24229bc3b) | Jan 04, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [8f42c7bc8c](https://linux-hardware.org/?probe=8f42c7bc8c) | Jan 04, 2023 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [2849ffe456](https://linux-hardware.org/?probe=2849ffe456) | Jan 04, 2023 |
| Dell          | XPS 13 9300                 | Notebook    | [7b1ce41c16](https://linux-hardware.org/?probe=7b1ce41c16) | Jan 03, 2023 |
| Valve         | Jupiter                     | Notebook    | [77cc17c28c](https://linux-hardware.org/?probe=77cc17c28c) | Jan 02, 2023 |
| Foxconn       | 2AAF                        | Desktop     | [813a45dc50](https://linux-hardware.org/?probe=813a45dc50) | Jan 01, 2023 |
| ASUSTek       | M52AD_M12AD_A_F_K31AD       | Desktop     | [de65990b87](https://linux-hardware.org/?probe=de65990b87) | Jan 01, 2023 |
| Acer          | Aspire V3-571G              | Notebook    | [273f6722e0](https://linux-hardware.org/?probe=273f6722e0) | Dec 31, 2022 |
| Shuttle       | SH570                       | Desktop     | [09994766ed](https://linux-hardware.org/?probe=09994766ed) | Dec 31, 2022 |
| Shuttle       | SH570                       | Desktop     | [f4d5ef752c](https://linux-hardware.org/?probe=f4d5ef752c) | Dec 31, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [270ba62d9d](https://linux-hardware.org/?probe=270ba62d9d) | Dec 31, 2022 |
| Shuttle       | SH570                       | Desktop     | [2d7f57de8f](https://linux-hardware.org/?probe=2d7f57de8f) | Dec 31, 2022 |
| Lenovo        | ChiefRiver                  | Desktop     | [847a9e86cd](https://linux-hardware.org/?probe=847a9e86cd) | Dec 30, 2022 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [16419f6991](https://linux-hardware.org/?probe=16419f6991) | Dec 30, 2022 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [4386242be1](https://linux-hardware.org/?probe=4386242be1) | Dec 30, 2022 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [34cd286c5f](https://linux-hardware.org/?probe=34cd286c5f) | Dec 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [15c60654b3](https://linux-hardware.org/?probe=15c60654b3) | Dec 30, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [87d0f67d84](https://linux-hardware.org/?probe=87d0f67d84) | Dec 30, 2022 |
| HP            | 1998                        | Desktop     | [c3404205e3](https://linux-hardware.org/?probe=c3404205e3) | Dec 29, 2022 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [b89e7eb1c9](https://linux-hardware.org/?probe=b89e7eb1c9) | Dec 28, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [f37619077b](https://linux-hardware.org/?probe=f37619077b) | Dec 26, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [e979df032a](https://linux-hardware.org/?probe=e979df032a) | Dec 26, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [82a5aa7ead](https://linux-hardware.org/?probe=82a5aa7ead) | Dec 26, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [2ef0101186](https://linux-hardware.org/?probe=2ef0101186) | Dec 25, 2022 |
| GMKtec        | NucBox8                     | Server      | [abc999a1a4](https://linux-hardware.org/?probe=abc999a1a4) | Dec 24, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [04b76a7e78](https://linux-hardware.org/?probe=04b76a7e78) | Dec 24, 2022 |
| Dell          | Latitude 3380               | Notebook    | [e4847d5b1f](https://linux-hardware.org/?probe=e4847d5b1f) | Dec 24, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [92f12e3ec7](https://linux-hardware.org/?probe=92f12e3ec7) | Dec 24, 2022 |
| GMKtec        | NucBox8                     | Server      | [66b0fbce86](https://linux-hardware.org/?probe=66b0fbce86) | Dec 24, 2022 |
| MSI           | Katana GF66 11UE            | Notebook    | [b993283081](https://linux-hardware.org/?probe=b993283081) | Dec 22, 2022 |
| Microsoft     | Surface Pro 2               | Tablet      | [3237ff6784](https://linux-hardware.org/?probe=3237ff6784) | Dec 22, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [ba82bee4c7](https://linux-hardware.org/?probe=ba82bee4c7) | Dec 22, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [a2a2f20ef4](https://linux-hardware.org/?probe=a2a2f20ef4) | Dec 22, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [92515d8a95](https://linux-hardware.org/?probe=92515d8a95) | Dec 21, 2022 |
| Schenker      | XMG APEX 15 MAX (E22)       | Notebook    | [6b46538fea](https://linux-hardware.org/?probe=6b46538fea) | Dec 21, 2022 |
| Dell          | 0020HJ A01                  | Server      | [e266254c60](https://linux-hardware.org/?probe=e266254c60) | Dec 21, 2022 |
| HP            | ProLiant DL360e Gen8        | Server      | [5477e8f714](https://linux-hardware.org/?probe=5477e8f714) | Dec 21, 2022 |
| Dell          | Latitude 3380               | Notebook    | [808c693271](https://linux-hardware.org/?probe=808c693271) | Dec 20, 2022 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [8a09a51987](https://linux-hardware.org/?probe=8a09a51987) | Dec 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [4fbc0ddbd5](https://linux-hardware.org/?probe=4fbc0ddbd5) | Dec 20, 2022 |
| HP            | 18E7                        | Desktop     | [31011a35a4](https://linux-hardware.org/?probe=31011a35a4) | Dec 17, 2022 |
| ASRock        | Z77 Extreme4                | Desktop     | [3b48a01ef2](https://linux-hardware.org/?probe=3b48a01ef2) | Dec 16, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [ffa7e28596](https://linux-hardware.org/?probe=ffa7e28596) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [143d2059a6](https://linux-hardware.org/?probe=143d2059a6) | Dec 16, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [bc3635620b](https://linux-hardware.org/?probe=bc3635620b) | Dec 15, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [888e6092a6](https://linux-hardware.org/?probe=888e6092a6) | Dec 15, 2022 |
| HP            | EliteBook 830 G6            | Notebook    | [5248ee7dbe](https://linux-hardware.org/?probe=5248ee7dbe) | Dec 15, 2022 |
| HP            | EliteBook 830 G7 Noteboo... | Notebook    | [3403282c8c](https://linux-hardware.org/?probe=3403282c8c) | Dec 15, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [bec79890c8](https://linux-hardware.org/?probe=bec79890c8) | Dec 15, 2022 |
| Dell          | 0D6H9T A02                  | Desktop     | [6266999282](https://linux-hardware.org/?probe=6266999282) | Dec 15, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [a0d408fecd](https://linux-hardware.org/?probe=a0d408fecd) | Dec 15, 2022 |
| Dell          | Latitude E7240              | Notebook    | [c47fc4fadf](https://linux-hardware.org/?probe=c47fc4fadf) | Dec 14, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [6b47a036ab](https://linux-hardware.org/?probe=6b47a036ab) | Dec 14, 2022 |
| Insyde        | G0975                       | Notebook    | [1f4823542d](https://linux-hardware.org/?probe=1f4823542d) | Dec 14, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [39a9464c10](https://linux-hardware.org/?probe=39a9464c10) | Dec 14, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [5a9654c743](https://linux-hardware.org/?probe=5a9654c743) | Dec 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [4a3ac966fc](https://linux-hardware.org/?probe=4a3ac966fc) | Dec 13, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [05ffc0ef7a](https://linux-hardware.org/?probe=05ffc0ef7a) | Dec 13, 2022 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [502792fe8a](https://linux-hardware.org/?probe=502792fe8a) | Dec 12, 2022 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [7b8b3c2a86](https://linux-hardware.org/?probe=7b8b3c2a86) | Dec 12, 2022 |
| MSI           | B75MA-E33                   | Desktop     | [65c6c18ffe](https://linux-hardware.org/?probe=65c6c18ffe) | Dec 12, 2022 |
| Dell          | Latitude 5430               | Notebook    | [b439d1e1a4](https://linux-hardware.org/?probe=b439d1e1a4) | Dec 12, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [4b0492b053](https://linux-hardware.org/?probe=4b0492b053) | Dec 11, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [ca7d835a38](https://linux-hardware.org/?probe=ca7d835a38) | Dec 11, 2022 |
| Google        | Orco                        | Notebook    | [40acd3207e](https://linux-hardware.org/?probe=40acd3207e) | Dec 10, 2022 |
| Google        | Orco                        | Notebook    | [9c369b40b3](https://linux-hardware.org/?probe=9c369b40b3) | Dec 10, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [c9cc6de1c4](https://linux-hardware.org/?probe=c9cc6de1c4) | Dec 08, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [8973296b3b](https://linux-hardware.org/?probe=8973296b3b) | Dec 08, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [3a91c2e245](https://linux-hardware.org/?probe=3a91c2e245) | Dec 07, 2022 |
| Lenovo        | ThinkPad T490s 20NX001KM... | Notebook    | [49f30d3eee](https://linux-hardware.org/?probe=49f30d3eee) | Dec 06, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [310ff494e7](https://linux-hardware.org/?probe=310ff494e7) | Dec 06, 2022 |
| HP            | 18E5                        | Desktop     | [9158a7ab6b](https://linux-hardware.org/?probe=9158a7ab6b) | Dec 06, 2022 |
| ASUSTek       | VivoBook S13 X330UA         | Notebook    | [d01d1e9652](https://linux-hardware.org/?probe=d01d1e9652) | Dec 06, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [b500d948bf](https://linux-hardware.org/?probe=b500d948bf) | Dec 05, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [ff90421b87](https://linux-hardware.org/?probe=ff90421b87) | Dec 05, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [3bc6ea9cfa](https://linux-hardware.org/?probe=3bc6ea9cfa) | Dec 05, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [aaed16d626](https://linux-hardware.org/?probe=aaed16d626) | Dec 05, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [cd63efdbd4](https://linux-hardware.org/?probe=cd63efdbd4) | Dec 05, 2022 |
| SiYW          | V200 Series                 | Desktop     | [c80a75c310](https://linux-hardware.org/?probe=c80a75c310) | Dec 03, 2022 |
| Sony          | VPCEB1M1E                   | Notebook    | [7ea8161a05](https://linux-hardware.org/?probe=7ea8161a05) | Dec 01, 2022 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [d8d5459ad6](https://linux-hardware.org/?probe=d8d5459ad6) | Dec 01, 2022 |
| Lenovo        | ThinkPad T470p 20J60018M... | Notebook    | [994d8e4b1d](https://linux-hardware.org/?probe=994d8e4b1d) | Dec 01, 2022 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [1dddd99280](https://linux-hardware.org/?probe=1dddd99280) | Dec 01, 2022 |
| Lenovo        | ThinkPad L560 20F10034MX    | Notebook    | [34842eb8d9](https://linux-hardware.org/?probe=34842eb8d9) | Dec 01, 2022 |
| Lenovo        | ThinkPad X270 20HNS03B00    | Notebook    | [bd40de3011](https://linux-hardware.org/?probe=bd40de3011) | Nov 30, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [258c074e40](https://linux-hardware.org/?probe=258c074e40) | Nov 30, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [29ec19d38e](https://linux-hardware.org/?probe=29ec19d38e) | Nov 30, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [997ffc40f0](https://linux-hardware.org/?probe=997ffc40f0) | Nov 29, 2022 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [efacbf6215](https://linux-hardware.org/?probe=efacbf6215) | Nov 29, 2022 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [85ac938c0c](https://linux-hardware.org/?probe=85ac938c0c) | Nov 29, 2022 |
| MSI           | Z370 GAMING PRO CARBON      | Desktop     | [96b383097b](https://linux-hardware.org/?probe=96b383097b) | Nov 29, 2022 |
| ASUSTek       | GA15DH                      | Desktop     | [a789d492a4](https://linux-hardware.org/?probe=a789d492a4) | Nov 28, 2022 |
| Lenovo        | ThinkPad T470p 20J60018M... | Notebook    | [c5f7049b04](https://linux-hardware.org/?probe=c5f7049b04) | Nov 28, 2022 |
| Lenovo        | ThinkPad E580 20KS001QMX    | Notebook    | [97fda88c7b](https://linux-hardware.org/?probe=97fda88c7b) | Nov 28, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [8f8f53c15b](https://linux-hardware.org/?probe=8f8f53c15b) | Nov 27, 2022 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [ac8f0475f1](https://linux-hardware.org/?probe=ac8f0475f1) | Nov 27, 2022 |
| HP            | Elite x2 1012 G2            | Tablet      | [669f6eaf1c](https://linux-hardware.org/?probe=669f6eaf1c) | Nov 26, 2022 |
| ASUSTek       | GA15DH                      | Desktop     | [ec6d666a16](https://linux-hardware.org/?probe=ec6d666a16) | Nov 24, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [b59180988d](https://linux-hardware.org/?probe=b59180988d) | Nov 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [ce5a80936d](https://linux-hardware.org/?probe=ce5a80936d) | Nov 24, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [9758f3268e](https://linux-hardware.org/?probe=9758f3268e) | Nov 23, 2022 |
| ASUSTek       | Strix GL504GW_GL504GW       | Notebook    | [f06e160e11](https://linux-hardware.org/?probe=f06e160e11) | Nov 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [7121172cc6](https://linux-hardware.org/?probe=7121172cc6) | Nov 22, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [c150f785ea](https://linux-hardware.org/?probe=c150f785ea) | Nov 21, 2022 |
| Dell          | XPS 9320                    | Notebook    | [52b55ea024](https://linux-hardware.org/?probe=52b55ea024) | Nov 21, 2022 |
| Dell          | XPS 9320                    | Notebook    | [7ea2296eaf](https://linux-hardware.org/?probe=7ea2296eaf) | Nov 21, 2022 |
| AZW           | GTR V01                     | Mini pc     | [2042d4c2c0](https://linux-hardware.org/?probe=2042d4c2c0) | Nov 21, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [71cb60b441](https://linux-hardware.org/?probe=71cb60b441) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [4f36ecd91b](https://linux-hardware.org/?probe=4f36ecd91b) | Nov 19, 2022 |
| ASRock        | Z790 PG Riptide             | Desktop     | [c852740256](https://linux-hardware.org/?probe=c852740256) | Nov 19, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [f10fc36516](https://linux-hardware.org/?probe=f10fc36516) | Nov 19, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [3534f07f4a](https://linux-hardware.org/?probe=3534f07f4a) | Nov 18, 2022 |
| ASUSTek       | N550JK                      | Notebook    | [86a2f7caea](https://linux-hardware.org/?probe=86a2f7caea) | Nov 18, 2022 |
| Dell          | Latitude 5310               | Notebook    | [8c9625dc17](https://linux-hardware.org/?probe=8c9625dc17) | Nov 17, 2022 |
| Dell          | Latitude 5310               | Notebook    | [958c48cd54](https://linux-hardware.org/?probe=958c48cd54) | Nov 17, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [4c5a2a2f55](https://linux-hardware.org/?probe=4c5a2a2f55) | Nov 16, 2022 |
| HP            | ZBook 15u G6                | Notebook    | [e6600fae5a](https://linux-hardware.org/?probe=e6600fae5a) | Nov 16, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [6cb0948dfd](https://linux-hardware.org/?probe=6cb0948dfd) | Nov 15, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | Notebook    | [64fb474239](https://linux-hardware.org/?probe=64fb474239) | Nov 14, 2022 |
| ASUSTek       | 2A73h                       | Desktop     | [08e4620733](https://linux-hardware.org/?probe=08e4620733) | Nov 13, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [fa18a7779e](https://linux-hardware.org/?probe=fa18a7779e) | Nov 13, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [0bc3c759d6](https://linux-hardware.org/?probe=0bc3c759d6) | Nov 13, 2022 |
| ASUSTek       | 2A73h                       | Desktop     | [557fb98d98](https://linux-hardware.org/?probe=557fb98d98) | Nov 13, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [aea8b4a908](https://linux-hardware.org/?probe=aea8b4a908) | Nov 12, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [4aa0411587](https://linux-hardware.org/?probe=4aa0411587) | Nov 12, 2022 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [091c048c2a](https://linux-hardware.org/?probe=091c048c2a) | Nov 12, 2022 |
| Foxconn       | 2AAF                        | Desktop     | [8dee2ceeb0](https://linux-hardware.org/?probe=8dee2ceeb0) | Nov 12, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [6eedcdeb01](https://linux-hardware.org/?probe=6eedcdeb01) | Nov 11, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [2865464ccd](https://linux-hardware.org/?probe=2865464ccd) | Nov 11, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [48f127b453](https://linux-hardware.org/?probe=48f127b453) | Nov 11, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [fd835d99e7](https://linux-hardware.org/?probe=fd835d99e7) | Nov 10, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [fae66184f2](https://linux-hardware.org/?probe=fae66184f2) | Nov 10, 2022 |
| ASUSTek       | U36SD                       | Notebook    | [d6b92cbdaa](https://linux-hardware.org/?probe=d6b92cbdaa) | Nov 07, 2022 |
| Acer          | Aspire A515-52              | Notebook    | [ed07b564ec](https://linux-hardware.org/?probe=ed07b564ec) | Nov 07, 2022 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [b6768dd5b7](https://linux-hardware.org/?probe=b6768dd5b7) | Nov 07, 2022 |
| HP            | 828A                        | Desktop     | [42d15a94b0](https://linux-hardware.org/?probe=42d15a94b0) | Nov 06, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [92c837ff5a](https://linux-hardware.org/?probe=92c837ff5a) | Nov 06, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [298819594a](https://linux-hardware.org/?probe=298819594a) | Nov 06, 2022 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [8a62c61d38](https://linux-hardware.org/?probe=8a62c61d38) | Nov 06, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [2765ed4857](https://linux-hardware.org/?probe=2765ed4857) | Nov 05, 2022 |
| HP            | ZBook 15u G6                | Notebook    | [58025a9d04](https://linux-hardware.org/?probe=58025a9d04) | Nov 05, 2022 |
| HP            | ZBook 15u G6                | Notebook    | [bd1a9c6659](https://linux-hardware.org/?probe=bd1a9c6659) | Nov 05, 2022 |
| HPE           | ProLiant MicroServer Gen... | Server      | [dd2877fcc2](https://linux-hardware.org/?probe=dd2877fcc2) | Nov 05, 2022 |
| HPE           | ProLiant MicroServer Gen... | Server      | [d95735860b](https://linux-hardware.org/?probe=d95735860b) | Nov 05, 2022 |
| Acer          | Predator G3610              | Desktop     | [783c053a62](https://linux-hardware.org/?probe=783c053a62) | Nov 05, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [7590df932b](https://linux-hardware.org/?probe=7590df932b) | Nov 05, 2022 |
| Apple         | MacBookPro16,2              | Notebook    | [ad1ae18c98](https://linux-hardware.org/?probe=ad1ae18c98) | Nov 04, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [b2af134ab3](https://linux-hardware.org/?probe=b2af134ab3) | Nov 04, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [9d1ba43c71](https://linux-hardware.org/?probe=9d1ba43c71) | Nov 04, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [dac055fa29](https://linux-hardware.org/?probe=dac055fa29) | Nov 04, 2022 |
| ASUSTek       | PRIME Z370-P II             | Desktop     | [1866954ec7](https://linux-hardware.org/?probe=1866954ec7) | Nov 04, 2022 |
| HP            | 2B05                        | Desktop     | [5c0a96cd5b](https://linux-hardware.org/?probe=5c0a96cd5b) | Nov 04, 2022 |
| HP            | 2B05                        | Desktop     | [95b5255056](https://linux-hardware.org/?probe=95b5255056) | Nov 04, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [de163caae3](https://linux-hardware.org/?probe=de163caae3) | Nov 04, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [442942f712](https://linux-hardware.org/?probe=442942f712) | Nov 04, 2022 |
| Intel         | NUC10i5FNB K61361-303       | Mini pc     | [df00a6281b](https://linux-hardware.org/?probe=df00a6281b) | Nov 03, 2022 |
| Intel         | NUC10i5FNB K61361-303       | Mini pc     | [2ec155a4b6](https://linux-hardware.org/?probe=2ec155a4b6) | Nov 03, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [ec359017a2](https://linux-hardware.org/?probe=ec359017a2) | Nov 02, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [72467c5d61](https://linux-hardware.org/?probe=72467c5d61) | Oct 31, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d99707ef15](https://linux-hardware.org/?probe=d99707ef15) | Oct 29, 2022 |
| HP            | EliteBook 830 G7 Noteboo... | Notebook    | [063675c104](https://linux-hardware.org/?probe=063675c104) | Oct 29, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [e51ca052ec](https://linux-hardware.org/?probe=e51ca052ec) | Oct 28, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [cd6e5e2095](https://linux-hardware.org/?probe=cd6e5e2095) | Oct 27, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [3c67c8efb7](https://linux-hardware.org/?probe=3c67c8efb7) | Oct 27, 2022 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [f95081e76e](https://linux-hardware.org/?probe=f95081e76e) | Oct 27, 2022 |
| HP            | EliteBook 830 G7 Noteboo... | Notebook    | [0fcfd33f95](https://linux-hardware.org/?probe=0fcfd33f95) | Oct 27, 2022 |
| Pegatron      | 2AD5                        | Desktop     | [daf7975ca0](https://linux-hardware.org/?probe=daf7975ca0) | Oct 26, 2022 |
| ASUSTek       | ROG STRIX B450-E GAMING     | Desktop     | [51cf8b4f9d](https://linux-hardware.org/?probe=51cf8b4f9d) | Oct 25, 2022 |
| Samsung       | 305V4A/305V5A/3415VA        | Notebook    | [d8f70347cf](https://linux-hardware.org/?probe=d8f70347cf) | Oct 24, 2022 |
| HP            | 2B05                        | Desktop     | [c059b9a786](https://linux-hardware.org/?probe=c059b9a786) | Oct 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [302efb993a](https://linux-hardware.org/?probe=302efb993a) | Oct 22, 2022 |
| Lenovo        | ThinkPad P52 20M90017MX     | Notebook    | [8f3fdb4d9c](https://linux-hardware.org/?probe=8f3fdb4d9c) | Oct 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [024fdc987b](https://linux-hardware.org/?probe=024fdc987b) | Oct 21, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [5e59c8933b](https://linux-hardware.org/?probe=5e59c8933b) | Oct 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [6249475f24](https://linux-hardware.org/?probe=6249475f24) | Oct 20, 2022 |
| Fujitsu Si... | D2399 S26361-D2399          | Desktop     | [77a5931c66](https://linux-hardware.org/?probe=77a5931c66) | Oct 20, 2022 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [f3ac5bf3df](https://linux-hardware.org/?probe=f3ac5bf3df) | Oct 20, 2022 |
| HP            | 8056                        | Desktop     | [37ed8a6b64](https://linux-hardware.org/?probe=37ed8a6b64) | Oct 18, 2022 |
| Lenovo        | IdeaPad S340-15APITouch ... | Notebook    | [aa65a51ac6](https://linux-hardware.org/?probe=aa65a51ac6) | Oct 18, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d727afe327](https://linux-hardware.org/?probe=d727afe327) | Oct 17, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [09a4ac981b](https://linux-hardware.org/?probe=09a4ac981b) | Oct 17, 2022 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [4138cb5064](https://linux-hardware.org/?probe=4138cb5064) | Oct 17, 2022 |
| HP            | 2AE2                        | Desktop     | [a1a8fcfe49](https://linux-hardware.org/?probe=a1a8fcfe49) | Oct 17, 2022 |
| Apple         | MacBookAir6,1               | Notebook    | [2438851671](https://linux-hardware.org/?probe=2438851671) | Oct 16, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [10a3014c1a](https://linux-hardware.org/?probe=10a3014c1a) | Oct 16, 2022 |
| ASUSTek       | P8H67                       | Desktop     | [4f03e84827](https://linux-hardware.org/?probe=4f03e84827) | Oct 16, 2022 |
| Acer          | Aspire V3-571               | Notebook    | [8457aa21e7](https://linux-hardware.org/?probe=8457aa21e7) | Oct 16, 2022 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [4f52cb1040](https://linux-hardware.org/?probe=4f52cb1040) | Oct 15, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [689281cab0](https://linux-hardware.org/?probe=689281cab0) | Oct 15, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [6def734895](https://linux-hardware.org/?probe=6def734895) | Oct 14, 2022 |
| Acer          | Aspire 8950G                | Notebook    | [8888f23e03](https://linux-hardware.org/?probe=8888f23e03) | Oct 14, 2022 |
| Lenovo        | ThinkPad E595 20NF001HMX    | Notebook    | [1ae4e8967a](https://linux-hardware.org/?probe=1ae4e8967a) | Oct 14, 2022 |
| Gigabyte      | AB350M-HD3-CF se1           | Desktop     | [89060aa147](https://linux-hardware.org/?probe=89060aa147) | Oct 13, 2022 |
| Gigabyte      | P65Q                        | Notebook    | [8e83936c53](https://linux-hardware.org/?probe=8e83936c53) | Oct 12, 2022 |
| Pegatron      | 2AD5                        | Desktop     | [512238de46](https://linux-hardware.org/?probe=512238de46) | Oct 12, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [10ea852e71](https://linux-hardware.org/?probe=10ea852e71) | Oct 12, 2022 |
| ASUSTek       | P8Z77-V                     | Desktop     | [27b7798784](https://linux-hardware.org/?probe=27b7798784) | Oct 11, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [ef1a363500](https://linux-hardware.org/?probe=ef1a363500) | Oct 11, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [7b6f3fcf28](https://linux-hardware.org/?probe=7b6f3fcf28) | Oct 10, 2022 |
| HP            | Pavilion dv7                | Notebook    | [4564037395](https://linux-hardware.org/?probe=4564037395) | Oct 07, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [c52e60caae](https://linux-hardware.org/?probe=c52e60caae) | Oct 06, 2022 |
| Microsoft     | Surface Pro 7               | Tablet      | [92704e062f](https://linux-hardware.org/?probe=92704e062f) | Oct 05, 2022 |
| MSI           | MEG Z490I UNIFY             | Desktop     | [a60e3c519e](https://linux-hardware.org/?probe=a60e3c519e) | Oct 05, 2022 |
| ASUSTek       | PRIME H570-PLUS             | Desktop     | [71da92bd30](https://linux-hardware.org/?probe=71da92bd30) | Oct 04, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [28d49251c7](https://linux-hardware.org/?probe=28d49251c7) | Oct 04, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [3ec3f59233](https://linux-hardware.org/?probe=3ec3f59233) | Oct 03, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [5ed7136249](https://linux-hardware.org/?probe=5ed7136249) | Oct 03, 2022 |
| ASUSTek       | UX303UB                     | Notebook    | [d67f04fc6e](https://linux-hardware.org/?probe=d67f04fc6e) | Oct 02, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [16a6152e10](https://linux-hardware.org/?probe=16a6152e10) | Oct 02, 2022 |
| Dell          | Latitude E6320              | Notebook    | [69290cc372](https://linux-hardware.org/?probe=69290cc372) | Oct 02, 2022 |
| ASUSTek       | UX303UB                     | Notebook    | [e09f793c1a](https://linux-hardware.org/?probe=e09f793c1a) | Oct 01, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [9d5f38913b](https://linux-hardware.org/?probe=9d5f38913b) | Oct 01, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [24a248630f](https://linux-hardware.org/?probe=24a248630f) | Sep 30, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [37a7291916](https://linux-hardware.org/?probe=37a7291916) | Sep 29, 2022 |
| HP            | 18E5                        | Desktop     | [bcc9927d20](https://linux-hardware.org/?probe=bcc9927d20) | Sep 28, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [6f9bc0cdba](https://linux-hardware.org/?probe=6f9bc0cdba) | Sep 26, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [d65cd8309b](https://linux-hardware.org/?probe=d65cd8309b) | Sep 26, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [72bd6750e5](https://linux-hardware.org/?probe=72bd6750e5) | Sep 25, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [a037b1ec8f](https://linux-hardware.org/?probe=a037b1ec8f) | Sep 24, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [0290975708](https://linux-hardware.org/?probe=0290975708) | Sep 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [8f29c3dc10](https://linux-hardware.org/?probe=8f29c3dc10) | Sep 24, 2022 |
| TUXEDO        | Unknown                     | Notebook    | [52ddc219ae](https://linux-hardware.org/?probe=52ddc219ae) | Sep 23, 2022 |
| Acer          | Veriton N4680G              | Desktop     | [a68d3f20eb](https://linux-hardware.org/?probe=a68d3f20eb) | Sep 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [c81b14b950](https://linux-hardware.org/?probe=c81b14b950) | Sep 23, 2022 |
| Lenovo        | Yoga 13sACN 2021 82CY       | Notebook    | [d374a74e0d](https://linux-hardware.org/?probe=d374a74e0d) | Sep 22, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [5e7597fb17](https://linux-hardware.org/?probe=5e7597fb17) | Sep 22, 2022 |
| Acer          | Veriton N4680G              | Desktop     | [5ed0ffde54](https://linux-hardware.org/?probe=5ed0ffde54) | Sep 22, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [1bec04d42d](https://linux-hardware.org/?probe=1bec04d42d) | Sep 21, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [b35ec1a833](https://linux-hardware.org/?probe=b35ec1a833) | Sep 21, 2022 |
| HP            | Pavilion g7                 | Notebook    | [a5f3f12174](https://linux-hardware.org/?probe=a5f3f12174) | Sep 20, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [af2eb79f4c](https://linux-hardware.org/?probe=af2eb79f4c) | Sep 20, 2022 |
| ASUSTek       | GL553VE                     | Notebook    | [4d93da1983](https://linux-hardware.org/?probe=4d93da1983) | Sep 20, 2022 |
| HP            | 2B05                        | Desktop     | [18db320ef7](https://linux-hardware.org/?probe=18db320ef7) | Sep 19, 2022 |
| Dell          | Latitude E6320              | Notebook    | [4995ae034f](https://linux-hardware.org/?probe=4995ae034f) | Sep 19, 2022 |
| Dell          | Latitude E6320              | Notebook    | [4bf59d7938](https://linux-hardware.org/?probe=4bf59d7938) | Sep 19, 2022 |
| ASUSTek       | GL553VE                     | Notebook    | [27b8d384a2](https://linux-hardware.org/?probe=27b8d384a2) | Sep 19, 2022 |
| ASUSTek       | M5A88-V EVO                 | Desktop     | [9dc35eec1a](https://linux-hardware.org/?probe=9dc35eec1a) | Sep 19, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [1d4585c98a](https://linux-hardware.org/?probe=1d4585c98a) | Sep 16, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [e85965bc82](https://linux-hardware.org/?probe=e85965bc82) | Sep 16, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [0278cf2e45](https://linux-hardware.org/?probe=0278cf2e45) | Sep 16, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [38d90248df](https://linux-hardware.org/?probe=38d90248df) | Sep 16, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [4c33a54701](https://linux-hardware.org/?probe=4c33a54701) | Sep 16, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [52fd47ee14](https://linux-hardware.org/?probe=52fd47ee14) | Sep 15, 2022 |
| Dell          | Latitude 7300               | Notebook    | [9802315270](https://linux-hardware.org/?probe=9802315270) | Sep 14, 2022 |
| Dell          | Latitude 7300               | Notebook    | [5d82c4da95](https://linux-hardware.org/?probe=5d82c4da95) | Sep 14, 2022 |
| HP            | 1497                        | Desktop     | [7d44fed5d5](https://linux-hardware.org/?probe=7d44fed5d5) | Sep 13, 2022 |
| HP            | 1497                        | Desktop     | [3afd83b18b](https://linux-hardware.org/?probe=3afd83b18b) | Sep 13, 2022 |
| Lenovo        | ThinkBook 13x ITG 20WJ      | Notebook    | [2e6e759434](https://linux-hardware.org/?probe=2e6e759434) | Sep 13, 2022 |
| MSI           | Z170A KRAIT GAMING 3X       | Desktop     | [bfcf5bab5f](https://linux-hardware.org/?probe=bfcf5bab5f) | Sep 12, 2022 |
| Intel         | NUC5CPYB H61145-413         | Mini pc     | [5987ef39e4](https://linux-hardware.org/?probe=5987ef39e4) | Sep 11, 2022 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [b8f2004ea5](https://linux-hardware.org/?probe=b8f2004ea5) | Sep 10, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [e77359618c](https://linux-hardware.org/?probe=e77359618c) | Sep 09, 2022 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Server      | [cf5955c3e1](https://linux-hardware.org/?probe=cf5955c3e1) | Sep 09, 2022 |
| HP            | ProBook 440 G7              | Notebook    | [082bf17ff0](https://linux-hardware.org/?probe=082bf17ff0) | Sep 08, 2022 |
| HP            | Compaq Presario CQ60        | Notebook    | [f6981692e0](https://linux-hardware.org/?probe=f6981692e0) | Sep 08, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [492849d42d](https://linux-hardware.org/?probe=492849d42d) | Sep 07, 2022 |
| Dell          | Precision 5530              | Notebook    | [d588e96ddc](https://linux-hardware.org/?probe=d588e96ddc) | Sep 07, 2022 |
| Rockchip      | Unknown                     | Soc         | [37447111b3](https://linux-hardware.org/?probe=37447111b3) | Sep 07, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [308047a7cb](https://linux-hardware.org/?probe=308047a7cb) | Sep 07, 2022 |
| Acer          | 1.0                         | Desktop     | [b81c44ff15](https://linux-hardware.org/?probe=b81c44ff15) | Sep 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [b1edd48233](https://linux-hardware.org/?probe=b1edd48233) | Sep 05, 2022 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [a8d726946f](https://linux-hardware.org/?probe=a8d726946f) | Sep 04, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [3f17eeffec](https://linux-hardware.org/?probe=3f17eeffec) | Sep 03, 2022 |
| Dell          | Latitude 7300               | Notebook    | [30994e1857](https://linux-hardware.org/?probe=30994e1857) | Sep 03, 2022 |
| ASRock        | X399 Taichi                 | Desktop     | [4080f853b6](https://linux-hardware.org/?probe=4080f853b6) | Sep 03, 2022 |
| ASRock        | X399 Taichi                 | Desktop     | [d54fe6c0ea](https://linux-hardware.org/?probe=d54fe6c0ea) | Sep 03, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [47dbe77b54](https://linux-hardware.org/?probe=47dbe77b54) | Sep 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [dea9852124](https://linux-hardware.org/?probe=dea9852124) | Sep 02, 2022 |
| Purism        | Librem 14                   | Notebook    | [54d6cbb49d](https://linux-hardware.org/?probe=54d6cbb49d) | Sep 01, 2022 |
| HP            | 18E5                        | Desktop     | [e7c5ab6cc4](https://linux-hardware.org/?probe=e7c5ab6cc4) | Aug 31, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [82cda7dfe9](https://linux-hardware.org/?probe=82cda7dfe9) | Aug 31, 2022 |
| HP            | Pavilion 15                 | Notebook    | [19c7cae23c](https://linux-hardware.org/?probe=19c7cae23c) | Aug 31, 2022 |
| Foxconn       | 2AAF                        | Desktop     | [a23b1b0822](https://linux-hardware.org/?probe=a23b1b0822) | Aug 30, 2022 |
| Acer          | Predator PT516-51s          | Notebook    | [5739f0b1a0](https://linux-hardware.org/?probe=5739f0b1a0) | Aug 28, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [70b2e9f836](https://linux-hardware.org/?probe=70b2e9f836) | Aug 27, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | Notebook    | [264a4fd9a7](https://linux-hardware.org/?probe=264a4fd9a7) | Aug 26, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [ce2bb0938b](https://linux-hardware.org/?probe=ce2bb0938b) | Aug 26, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [61b05137a7](https://linux-hardware.org/?probe=61b05137a7) | Aug 26, 2022 |
| ASRock        | X99 WS                      | Desktop     | [d16d59fab2](https://linux-hardware.org/?probe=d16d59fab2) | Aug 26, 2022 |
| Foxconn       | P35A01                      | Desktop     | [fa220f1ce6](https://linux-hardware.org/?probe=fa220f1ce6) | Aug 25, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [b19844ee21](https://linux-hardware.org/?probe=b19844ee21) | Aug 25, 2022 |
| ASUSTek       | T100HAN                     | Notebook    | [9438c7bb11](https://linux-hardware.org/?probe=9438c7bb11) | Aug 23, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [6fcc3e058d](https://linux-hardware.org/?probe=6fcc3e058d) | Aug 22, 2022 |
| ASUSTek       | B150M-A                     | Desktop     | [0dac247b92](https://linux-hardware.org/?probe=0dac247b92) | Aug 21, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [c74bbc2f61](https://linux-hardware.org/?probe=c74bbc2f61) | Aug 21, 2022 |
| Samsung       | 935XDB                      | Notebook    | [a8d4f5e6a0](https://linux-hardware.org/?probe=a8d4f5e6a0) | Aug 20, 2022 |
| MSI           | GF63 Thin 10UC              | Notebook    | [b04f79d93a](https://linux-hardware.org/?probe=b04f79d93a) | Aug 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [87fcf5d702](https://linux-hardware.org/?probe=87fcf5d702) | Aug 19, 2022 |
| Lenovo        | ThinkPad X201 3626FAG       | Notebook    | [0271f9018f](https://linux-hardware.org/?probe=0271f9018f) | Aug 19, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [1e2a8c815e](https://linux-hardware.org/?probe=1e2a8c815e) | Aug 16, 2022 |
| HP            | Pavilion g6                 | Notebook    | [ddc9a7396e](https://linux-hardware.org/?probe=ddc9a7396e) | Aug 16, 2022 |
| HP            | Pavilion g6                 | Notebook    | [ef1cbed5a4](https://linux-hardware.org/?probe=ef1cbed5a4) | Aug 16, 2022 |
| Acer          | Aspire ES1-512              | Notebook    | [cb59c4a321](https://linux-hardware.org/?probe=cb59c4a321) | Aug 15, 2022 |
| Acer          | Aspire ES1-512              | Notebook    | [496f0834ae](https://linux-hardware.org/?probe=496f0834ae) | Aug 15, 2022 |
| ASUSTek       | Z87-PLUS                    | Desktop     | [63d41691ef](https://linux-hardware.org/?probe=63d41691ef) | Aug 15, 2022 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [837159c07a](https://linux-hardware.org/?probe=837159c07a) | Aug 14, 2022 |
| MSI           | Prestige 15 A10SC           | Notebook    | [58d3be66c0](https://linux-hardware.org/?probe=58d3be66c0) | Aug 14, 2022 |
| ASUSTek       | PRIME B250-PLUS             | Desktop     | [6dab67810d](https://linux-hardware.org/?probe=6dab67810d) | Aug 14, 2022 |
| Intel         | NUC6i5SYB H81131-502        | Mini pc     | [0b62c9a78f](https://linux-hardware.org/?probe=0b62c9a78f) | Aug 12, 2022 |
| Intel         | NUC6i5SYB H81131-502        | Mini pc     | [2487f351d2](https://linux-hardware.org/?probe=2487f351d2) | Aug 12, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [1091d27582](https://linux-hardware.org/?probe=1091d27582) | Aug 11, 2022 |
| Lenovo        | ThinkPad X201 3626FAG       | Notebook    | [34938e0949](https://linux-hardware.org/?probe=34938e0949) | Aug 11, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [edf947ace6](https://linux-hardware.org/?probe=edf947ace6) | Aug 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [813863fbbf](https://linux-hardware.org/?probe=813863fbbf) | Aug 09, 2022 |
| ASUSTek       | PN52                        | Mini pc     | [3fbc687842](https://linux-hardware.org/?probe=3fbc687842) | Aug 08, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [c530c6e2cb](https://linux-hardware.org/?probe=c530c6e2cb) | Aug 08, 2022 |
| HP            | 304Bh                       | Desktop     | [e1e3f301cb](https://linux-hardware.org/?probe=e1e3f301cb) | Aug 08, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [f91ebc68e8](https://linux-hardware.org/?probe=f91ebc68e8) | Aug 08, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [119cdc7bf8](https://linux-hardware.org/?probe=119cdc7bf8) | Aug 07, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [b075418a73](https://linux-hardware.org/?probe=b075418a73) | Aug 07, 2022 |
| Lenovo        | Yoga SLIM 7-14ARE05 82A2    | Notebook    | [091235281e](https://linux-hardware.org/?probe=091235281e) | Aug 06, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [ec98a546e1](https://linux-hardware.org/?probe=ec98a546e1) | Aug 06, 2022 |
| Acer          | Veriton N4680G              | Desktop     | [a0f4d75db6](https://linux-hardware.org/?probe=a0f4d75db6) | Aug 06, 2022 |
| Lenovo        | Yoga SLIM 7-14ARE05 82A2    | Notebook    | [431684d65c](https://linux-hardware.org/?probe=431684d65c) | Aug 05, 2022 |
| ASRock        | H270M-ITX/ac                | Desktop     | [273c214064](https://linux-hardware.org/?probe=273c214064) | Aug 05, 2022 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [a2733a0f87](https://linux-hardware.org/?probe=a2733a0f87) | Aug 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [cdc1f14772](https://linux-hardware.org/?probe=cdc1f14772) | Aug 04, 2022 |
| Samsung       | 700G7C                      | Notebook    | [cd554f5d17](https://linux-hardware.org/?probe=cd554f5d17) | Aug 03, 2022 |
| Dell          | Precision 14 5470           | Notebook    | [089d1a151f](https://linux-hardware.org/?probe=089d1a151f) | Aug 03, 2022 |
| Dell          | 0Y56T3 A00                  | Desktop     | [c52a590c5b](https://linux-hardware.org/?probe=c52a590c5b) | Aug 02, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [64a21844e4](https://linux-hardware.org/?probe=64a21844e4) | Aug 01, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [de9a854095](https://linux-hardware.org/?probe=de9a854095) | Jul 31, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [06b58ca667](https://linux-hardware.org/?probe=06b58ca667) | Jul 31, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [ae030e58fb](https://linux-hardware.org/?probe=ae030e58fb) | Jul 31, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [249d407b66](https://linux-hardware.org/?probe=249d407b66) | Jul 30, 2022 |
| Dell          | 0TP412                      | Desktop     | [c6138574f4](https://linux-hardware.org/?probe=c6138574f4) | Jul 30, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [edd98c5418](https://linux-hardware.org/?probe=edd98c5418) | Jul 30, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [3b661517b1](https://linux-hardware.org/?probe=3b661517b1) | Jul 29, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [4fa56bac04](https://linux-hardware.org/?probe=4fa56bac04) | Jul 29, 2022 |
| HP            | 18E7                        | Desktop     | [3d7c1549eb](https://linux-hardware.org/?probe=3d7c1549eb) | Jul 29, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [32c295bae1](https://linux-hardware.org/?probe=32c295bae1) | Jul 29, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [c3f34f2c91](https://linux-hardware.org/?probe=c3f34f2c91) | Jul 28, 2022 |
| HP            | ZBook 15 G2                 | Notebook    | [34f32c0d0d](https://linux-hardware.org/?probe=34f32c0d0d) | Jul 27, 2022 |
| Acer          | Aspire X1930                | Desktop     | [6a650f512e](https://linux-hardware.org/?probe=6a650f512e) | Jul 27, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [b3df887fe1](https://linux-hardware.org/?probe=b3df887fe1) | Jul 27, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [5b4bccdf27](https://linux-hardware.org/?probe=5b4bccdf27) | Jul 27, 2022 |
| ASUSTek       | ZenBook UX325UA             | Notebook    | [587ea51239](https://linux-hardware.org/?probe=587ea51239) | Jul 26, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [960fefaee7](https://linux-hardware.org/?probe=960fefaee7) | Jul 25, 2022 |
| Dell          | Precision 7560              | Notebook    | [2fdcece648](https://linux-hardware.org/?probe=2fdcece648) | Jul 25, 2022 |
| Dell          | Precision 7560              | Notebook    | [02fb353f1e](https://linux-hardware.org/?probe=02fb353f1e) | Jul 25, 2022 |
| Gigabyte      | Z390 M-CF                   | Desktop     | [ae2926d93e](https://linux-hardware.org/?probe=ae2926d93e) | Jul 24, 2022 |
| XDO.AI        | Pantera Pico PC             | Desktop     | [e29f39ad9e](https://linux-hardware.org/?probe=e29f39ad9e) | Jul 23, 2022 |
| MSI           | Raider GE76 12UGS           | Notebook    | [65c50de21a](https://linux-hardware.org/?probe=65c50de21a) | Jul 22, 2022 |
| MSI           | Raider GE76 12UGS           | Notebook    | [6dba304ba4](https://linux-hardware.org/?probe=6dba304ba4) | Jul 22, 2022 |
| ASUSTek       | K52Dr                       | Notebook    | [efd71c663d](https://linux-hardware.org/?probe=efd71c663d) | Jul 22, 2022 |
| Acer          | Predator PT516-51s          | Notebook    | [8337c958e2](https://linux-hardware.org/?probe=8337c958e2) | Jul 22, 2022 |
| Toshiba       | BLB                         | Notebook    | [997a7c93d7](https://linux-hardware.org/?probe=997a7c93d7) | Jul 21, 2022 |
| Dell          | Latitude E5450              | Notebook    | [c8243bf1a8](https://linux-hardware.org/?probe=c8243bf1a8) | Jul 20, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [2a10c24690](https://linux-hardware.org/?probe=2a10c24690) | Jul 20, 2022 |
| Dell          | Precision 7760              | Notebook    | [742cb747ef](https://linux-hardware.org/?probe=742cb747ef) | Jul 20, 2022 |
| ASUSTek       | K52Dr                       | Notebook    | [31471e3583](https://linux-hardware.org/?probe=31471e3583) | Jul 19, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [ac6aba12f5](https://linux-hardware.org/?probe=ac6aba12f5) | Jul 19, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [7f4f42a3f7](https://linux-hardware.org/?probe=7f4f42a3f7) | Jul 19, 2022 |
| Dell          | Precision 3561              | Notebook    | [7dfa6ede1e](https://linux-hardware.org/?probe=7dfa6ede1e) | Jul 18, 2022 |
| Lenovo        | Aptio CRB SDK0F82993 WIN    | Mini pc     | [ba6f405592](https://linux-hardware.org/?probe=ba6f405592) | Jul 18, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [fb9a47e37f](https://linux-hardware.org/?probe=fb9a47e37f) | Jul 17, 2022 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [66fe37549d](https://linux-hardware.org/?probe=66fe37549d) | Jul 16, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [86ac444b35](https://linux-hardware.org/?probe=86ac444b35) | Jul 15, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [9da64b4efa](https://linux-hardware.org/?probe=9da64b4efa) | Jul 14, 2022 |
| Star Labs     | StarBook                    | Notebook    | [fdae1cd2c3](https://linux-hardware.org/?probe=fdae1cd2c3) | Jul 12, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [235fc9b289](https://linux-hardware.org/?probe=235fc9b289) | Jul 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [a42efbead1](https://linux-hardware.org/?probe=a42efbead1) | Jul 11, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [8d8610ee4f](https://linux-hardware.org/?probe=8d8610ee4f) | Jul 11, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [4dba0dc5ab](https://linux-hardware.org/?probe=4dba0dc5ab) | Jul 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [0e13eaa824](https://linux-hardware.org/?probe=0e13eaa824) | Jul 10, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [1ac13f76b1](https://linux-hardware.org/?probe=1ac13f76b1) | Jul 10, 2022 |
| Dell          | Precision 5570              | Notebook    | [e4409961fd](https://linux-hardware.org/?probe=e4409961fd) | Jul 08, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [5cff36844a](https://linux-hardware.org/?probe=5cff36844a) | Jul 07, 2022 |
| Lenovo        | Aptio CRB SDK0F82993 WIN    | Mini pc     | [dcbdde4fdf](https://linux-hardware.org/?probe=dcbdde4fdf) | Jul 06, 2022 |
| Dell          | 0M858N A01                  | Desktop     | [36aca635a8](https://linux-hardware.org/?probe=36aca635a8) | Jul 06, 2022 |
| MSI           | MS-AA71                     | All in one  | [4e7d1d05d6](https://linux-hardware.org/?probe=4e7d1d05d6) | Jul 06, 2022 |
| Dell          | 0GM819                      | Desktop     | [a366983f6a](https://linux-hardware.org/?probe=a366983f6a) | Jul 06, 2022 |
| Dell          | 0GM819                      | Desktop     | [78e233e42f](https://linux-hardware.org/?probe=78e233e42f) | Jul 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [458276506d](https://linux-hardware.org/?probe=458276506d) | Jul 06, 2022 |
| Acer          | Predator PT516-51s          | Notebook    | [9309da8b72](https://linux-hardware.org/?probe=9309da8b72) | Jul 05, 2022 |
| Acer          | Aspire 3100                 | Notebook    | [498f4edafb](https://linux-hardware.org/?probe=498f4edafb) | Jul 05, 2022 |
| Acer          | Aspire 3100                 | Notebook    | [1264fab131](https://linux-hardware.org/?probe=1264fab131) | Jul 05, 2022 |
| Dell          | Precision M4700             | Notebook    | [fad2fe7297](https://linux-hardware.org/?probe=fad2fe7297) | Jul 04, 2022 |
| HP            | ProBook x360 435 G8 Note... | Convertible | [848a8591de](https://linux-hardware.org/?probe=848a8591de) | Jul 03, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [0cb6549f23](https://linux-hardware.org/?probe=0cb6549f23) | Jun 30, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [0f4c661912](https://linux-hardware.org/?probe=0f4c661912) | Jun 27, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [27343a622f](https://linux-hardware.org/?probe=27343a622f) | Jun 25, 2022 |
| HP            | Pavilion dv7                | Notebook    | [5dd67bc68a](https://linux-hardware.org/?probe=5dd67bc68a) | Jun 25, 2022 |
| MSI           | Z370 GAMING PRO CARBON      | Desktop     | [57660d8f0f](https://linux-hardware.org/?probe=57660d8f0f) | Jun 24, 2022 |
| ASUSTek       | N61Vn                       | Notebook    | [72d62f755d](https://linux-hardware.org/?probe=72d62f755d) | Jun 24, 2022 |
| HP            | ZBook 15 G2                 | Notebook    | [cfa8a05299](https://linux-hardware.org/?probe=cfa8a05299) | Jun 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [5188bfb9d3](https://linux-hardware.org/?probe=5188bfb9d3) | Jun 23, 2022 |
| HP            | 2B05                        | Desktop     | [677bb9d569](https://linux-hardware.org/?probe=677bb9d569) | Jun 22, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [273f19137a](https://linux-hardware.org/?probe=273f19137a) | Jun 21, 2022 |
| Microsoft     | Surface Pro 2               | Tablet      | [07506542b5](https://linux-hardware.org/?probe=07506542b5) | Jun 21, 2022 |
| MSI           | B250I GAMING PRO AC         | Desktop     | [280d4af2d2](https://linux-hardware.org/?probe=280d4af2d2) | Jun 21, 2022 |
| MSI           | B250I GAMING PRO AC         | Desktop     | [c90adf6d43](https://linux-hardware.org/?probe=c90adf6d43) | Jun 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [27623895a1](https://linux-hardware.org/?probe=27623895a1) | Jun 20, 2022 |
| ASUSTek       | PN51                        | Mini pc     | [af5bb55ac5](https://linux-hardware.org/?probe=af5bb55ac5) | Jun 20, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [ad271e0eec](https://linux-hardware.org/?probe=ad271e0eec) | Jun 19, 2022 |
| HP            | 2B05                        | Desktop     | [a49ebb4aed](https://linux-hardware.org/?probe=a49ebb4aed) | Jun 19, 2022 |
| Intel         | NUC8BEB J72692-306          | Mini pc     | [5448ad3e33](https://linux-hardware.org/?probe=5448ad3e33) | Jun 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [f76be8391b](https://linux-hardware.org/?probe=f76be8391b) | Jun 18, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [530c081484](https://linux-hardware.org/?probe=530c081484) | Jun 17, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [f75b5004f9](https://linux-hardware.org/?probe=f75b5004f9) | Jun 17, 2022 |
| Gigabyte      | H67M-UD2H-B3                | Desktop     | [1c8dd20713](https://linux-hardware.org/?probe=1c8dd20713) | Jun 16, 2022 |
| Acer          | Aspire TC-230               | Desktop     | [bec506a849](https://linux-hardware.org/?probe=bec506a849) | Jun 16, 2022 |
| Acer          | Predator G3610              | Desktop     | [ff347cdb53](https://linux-hardware.org/?probe=ff347cdb53) | Jun 15, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [fe963bacc6](https://linux-hardware.org/?probe=fe963bacc6) | Jun 14, 2022 |
| congatec      | conga-PA7 A.0               | Mini pc     | [e0c6234f77](https://linux-hardware.org/?probe=e0c6234f77) | Jun 13, 2022 |
| HP            | EliteBook 830 G7 Noteboo... | Notebook    | [8153e1c68e](https://linux-hardware.org/?probe=8153e1c68e) | Jun 13, 2022 |
| HP            | EliteBook 830 G6            | Notebook    | [12fb5f93c9](https://linux-hardware.org/?probe=12fb5f93c9) | Jun 13, 2022 |
| Dell          | Precision 7520              | Notebook    | [002f7ce017](https://linux-hardware.org/?probe=002f7ce017) | Jun 12, 2022 |
| Lenovo        | ThinkPad X1 Yoga Gen 6 2... | Convertible | [d9cffc5cc6](https://linux-hardware.org/?probe=d9cffc5cc6) | Jun 10, 2022 |
| HP            | Pavilion g6                 | Notebook    | [63dcba0c57](https://linux-hardware.org/?probe=63dcba0c57) | Jun 10, 2022 |
| Dell          | Vostro 2520                 | Notebook    | [884806d49f](https://linux-hardware.org/?probe=884806d49f) | Jun 09, 2022 |
| Acer          | Aspire 5749Z                | Notebook    | [d7020510e2](https://linux-hardware.org/?probe=d7020510e2) | Jun 08, 2022 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [3de14e06c5](https://linux-hardware.org/?probe=3de14e06c5) | Jun 08, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [33dbe3e5db](https://linux-hardware.org/?probe=33dbe3e5db) | Jun 08, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [685df41f04](https://linux-hardware.org/?probe=685df41f04) | Jun 07, 2022 |
| Lenovo        | ThinkPad X61 Tablet 7762... | Notebook    | [9ccaec00d8](https://linux-hardware.org/?probe=9ccaec00d8) | Jun 06, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [ba86261552](https://linux-hardware.org/?probe=ba86261552) | Jun 06, 2022 |
| Intel         | NUC11TNBi7 M11895-402       | Mini pc     | [4b972d5b22](https://linux-hardware.org/?probe=4b972d5b22) | Jun 05, 2022 |
| Dell          | Latitude D630               | Notebook    | [fb28805860](https://linux-hardware.org/?probe=fb28805860) | Jun 05, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [d191629954](https://linux-hardware.org/?probe=d191629954) | Jun 04, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [816c29b1df](https://linux-hardware.org/?probe=816c29b1df) | Jun 04, 2022 |
| Dell          | 0WR7PY A01                  | Desktop     | [dc7a83708a](https://linux-hardware.org/?probe=dc7a83708a) | Jun 04, 2022 |
| HP            | ProBook 6450b               | Notebook    | [52467822a6](https://linux-hardware.org/?probe=52467822a6) | Jun 03, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [b414c22d34](https://linux-hardware.org/?probe=b414c22d34) | Jun 02, 2022 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [90b0bc8a37](https://linux-hardware.org/?probe=90b0bc8a37) | Jun 02, 2022 |
| HP            | ProBook 6450b               | Notebook    | [26bce40d20](https://linux-hardware.org/?probe=26bce40d20) | Jun 01, 2022 |
| Dell          | Latitude E7240              | Notebook    | [e3c9cca7e1](https://linux-hardware.org/?probe=e3c9cca7e1) | Jun 01, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [f4906f3799](https://linux-hardware.org/?probe=f4906f3799) | Jun 01, 2022 |
| Toshiba       | Satellite L50D-B            | Notebook    | [860be26e14](https://linux-hardware.org/?probe=860be26e14) | May 29, 2022 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | Desktop     | [63747954e9](https://linux-hardware.org/?probe=63747954e9) | May 29, 2022 |
| Lenovo        | ThinkPad W500 4061W8H       | Notebook    | [db9160e089](https://linux-hardware.org/?probe=db9160e089) | May 29, 2022 |
| Pegatron      | 2ACF                        | Desktop     | [bd97a6b3dd](https://linux-hardware.org/?probe=bd97a6b3dd) | May 28, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [b32a949b01](https://linux-hardware.org/?probe=b32a949b01) | May 28, 2022 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [e64dfe3f6f](https://linux-hardware.org/?probe=e64dfe3f6f) | May 28, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [8f40318937](https://linux-hardware.org/?probe=8f40318937) | May 27, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [c025e27a90](https://linux-hardware.org/?probe=c025e27a90) | May 27, 2022 |
| ASUSTek       | U31Jg                       | Notebook    | [b761173e5e](https://linux-hardware.org/?probe=b761173e5e) | May 26, 2022 |
| Fujitsu       | CELSIUS H730                | Notebook    | [6f0b24d450](https://linux-hardware.org/?probe=6f0b24d450) | May 26, 2022 |
| HP            | EliteBook 850 G6            | Notebook    | [25e4d08ac2](https://linux-hardware.org/?probe=25e4d08ac2) | May 25, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [2d28231751](https://linux-hardware.org/?probe=2d28231751) | May 25, 2022 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [c00f6e1b2a](https://linux-hardware.org/?probe=c00f6e1b2a) | May 24, 2022 |
| Apple         | MacBook6,1                  | Notebook    | [683ff3ab1a](https://linux-hardware.org/?probe=683ff3ab1a) | May 24, 2022 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [594e42160c](https://linux-hardware.org/?probe=594e42160c) | May 22, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [b620a51628](https://linux-hardware.org/?probe=b620a51628) | May 22, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [32b5f99569](https://linux-hardware.org/?probe=32b5f99569) | May 22, 2022 |
| Gigabyte      | H67N-USB3-B3                | Desktop     | [382f206597](https://linux-hardware.org/?probe=382f206597) | May 21, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [cc0b92bd45](https://linux-hardware.org/?probe=cc0b92bd45) | May 21, 2022 |
| HP            | 635                         | Notebook    | [2421582549](https://linux-hardware.org/?probe=2421582549) | May 21, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [f02fa869ff](https://linux-hardware.org/?probe=f02fa869ff) | May 20, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [bdc2dbdba3](https://linux-hardware.org/?probe=bdc2dbdba3) | May 19, 2022 |
| Apple         | MacBook6,1                  | Notebook    | [97e7c3fd74](https://linux-hardware.org/?probe=97e7c3fd74) | May 19, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [a1cbc8b911](https://linux-hardware.org/?probe=a1cbc8b911) | May 19, 2022 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [13bc0ce7c5](https://linux-hardware.org/?probe=13bc0ce7c5) | May 19, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | Notebook    | [736bd1ab68](https://linux-hardware.org/?probe=736bd1ab68) | May 18, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | Notebook    | [6c41f73e8a](https://linux-hardware.org/?probe=6c41f73e8a) | May 18, 2022 |
| HP            | 635                         | Notebook    | [3168b50a90](https://linux-hardware.org/?probe=3168b50a90) | May 18, 2022 |
| Apple         | MacBookPro16,2              | Notebook    | [ceb6a7e5a3](https://linux-hardware.org/?probe=ceb6a7e5a3) | May 16, 2022 |
| Apple         | MacBookPro16,2              | Notebook    | [5c4ebc223f](https://linux-hardware.org/?probe=5c4ebc223f) | May 16, 2022 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [efd77955ef](https://linux-hardware.org/?probe=efd77955ef) | May 15, 2022 |
| MSI           | GS73VR 7RG                  | Notebook    | [3815425b08](https://linux-hardware.org/?probe=3815425b08) | May 15, 2022 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [70809098f6](https://linux-hardware.org/?probe=70809098f6) | May 14, 2022 |
| Intel         | NUC8BEB J72692-306          | Mini pc     | [7f06d07456](https://linux-hardware.org/?probe=7f06d07456) | May 14, 2022 |
| Intel         | NUC8BEB J72692-306          | Mini pc     | [a9c9d7da8d](https://linux-hardware.org/?probe=a9c9d7da8d) | May 14, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [bfcd03ba86](https://linux-hardware.org/?probe=bfcd03ba86) | May 14, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [2152787c64](https://linux-hardware.org/?probe=2152787c64) | May 13, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [235beb3d5f](https://linux-hardware.org/?probe=235beb3d5f) | May 13, 2022 |
| Lenovo        | SKYBAY SDK0J40700 WIN 32... | Desktop     | [6f09e11de7](https://linux-hardware.org/?probe=6f09e11de7) | May 12, 2022 |
| Notebook      | NS50_70MU                   | Notebook    | [cff8de13ce](https://linux-hardware.org/?probe=cff8de13ce) | May 12, 2022 |
| Notebook      | NS50_70MU                   | Notebook    | [ebf71be1f5](https://linux-hardware.org/?probe=ebf71be1f5) | May 12, 2022 |
| MSI           | GF63 Thin 9SCSR             | Notebook    | [a80ef1636d](https://linux-hardware.org/?probe=a80ef1636d) | May 12, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [2342a9d519](https://linux-hardware.org/?probe=2342a9d519) | May 12, 2022 |
| ASUSTek       | A6U                         | Notebook    | [4a8ad00e5e](https://linux-hardware.org/?probe=4a8ad00e5e) | May 12, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [38bc924977](https://linux-hardware.org/?probe=38bc924977) | May 12, 2022 |
| Dell          | 0HD5W2 A00                  | Desktop     | [9f28ef42a4](https://linux-hardware.org/?probe=9f28ef42a4) | May 11, 2022 |
| MSI           | B75MA-E33                   | Desktop     | [220e04a116](https://linux-hardware.org/?probe=220e04a116) | May 11, 2022 |
| ASRock        | B550 Phantom Gaming 4/ac    | Desktop     | [6a69aab6ee](https://linux-hardware.org/?probe=6a69aab6ee) | May 11, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [8f62053ddd](https://linux-hardware.org/?probe=8f62053ddd) | May 11, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [018c90008f](https://linux-hardware.org/?probe=018c90008f) | May 11, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [5b6165bc68](https://linux-hardware.org/?probe=5b6165bc68) | May 10, 2022 |
| Gigabyte      | X99P-SLI-CF                 | Desktop     | [0bec73d852](https://linux-hardware.org/?probe=0bec73d852) | May 10, 2022 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [56c5f8cad8](https://linux-hardware.org/?probe=56c5f8cad8) | May 09, 2022 |
| Lenovo        | ThinkPad X270 20HMS27Q00    | Notebook    | [615d6650a0](https://linux-hardware.org/?probe=615d6650a0) | May 08, 2022 |
| Lenovo        | ThinkPad X240 20AMS6FF00    | Notebook    | [3e3da41a35](https://linux-hardware.org/?probe=3e3da41a35) | May 08, 2022 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [bd94a8145a](https://linux-hardware.org/?probe=bd94a8145a) | May 08, 2022 |
| ASUSTek       | E200HA                      | Notebook    | [ba413ad853](https://linux-hardware.org/?probe=ba413ad853) | May 08, 2022 |
| Samsung       | 750XDA                      | Notebook    | [466689475e](https://linux-hardware.org/?probe=466689475e) | May 07, 2022 |
| ASUSTek       | E200HA                      | Notebook    | [6fc7c6f086](https://linux-hardware.org/?probe=6fc7c6f086) | May 07, 2022 |
| Dell          | Precision M4700             | Notebook    | [81cc8ba45c](https://linux-hardware.org/?probe=81cc8ba45c) | May 06, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [be200c9e57](https://linux-hardware.org/?probe=be200c9e57) | May 06, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U2S... | Notebook    | [64eb136705](https://linux-hardware.org/?probe=64eb136705) | May 03, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [e2dfdb6af2](https://linux-hardware.org/?probe=e2dfdb6af2) | May 03, 2022 |
| Acer          | Aspire A315-41              | Notebook    | [1bd7f7cd93](https://linux-hardware.org/?probe=1bd7f7cd93) | May 02, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [1c3645cb67](https://linux-hardware.org/?probe=1c3645cb67) | May 02, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [f6cc5e2ad5](https://linux-hardware.org/?probe=f6cc5e2ad5) | May 01, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [adc0bdd7f8](https://linux-hardware.org/?probe=adc0bdd7f8) | May 01, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [e8fee79ec7](https://linux-hardware.org/?probe=e8fee79ec7) | Apr 30, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [995ea9538b](https://linux-hardware.org/?probe=995ea9538b) | Apr 30, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [5d02fb20c7](https://linux-hardware.org/?probe=5d02fb20c7) | Apr 29, 2022 |
| ASUSTek       | B150M-A                     | Desktop     | [fa213f6681](https://linux-hardware.org/?probe=fa213f6681) | Apr 28, 2022 |
| Gigabyte      | H67M-UD2H-B3                | Desktop     | [7defbcb7bb](https://linux-hardware.org/?probe=7defbcb7bb) | Apr 28, 2022 |
| Lenovo        | ThinkPad X131e 33683YG      | Notebook    | [58076aa8e9](https://linux-hardware.org/?probe=58076aa8e9) | Apr 28, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [37b195945a](https://linux-hardware.org/?probe=37b195945a) | Apr 28, 2022 |
| Dell          | Latitude 7420               | Notebook    | [8e3bcab404](https://linux-hardware.org/?probe=8e3bcab404) | Apr 28, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [11a6c8f173](https://linux-hardware.org/?probe=11a6c8f173) | Apr 27, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [3b4a331875](https://linux-hardware.org/?probe=3b4a331875) | Apr 26, 2022 |
| Lenovo        | ThinkPad T61 64665WG        | Notebook    | [ac1bec6053](https://linux-hardware.org/?probe=ac1bec6053) | Apr 26, 2022 |
| Lenovo        | 3716 SDK0R32862 WIN 3258... | Desktop     | [8cba4892be](https://linux-hardware.org/?probe=8cba4892be) | Apr 25, 2022 |
| ASUSTek       | UX461UN                     | Convertible | [57bbbf3023](https://linux-hardware.org/?probe=57bbbf3023) | Apr 25, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [c0af99fa7e](https://linux-hardware.org/?probe=c0af99fa7e) | Apr 24, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [6cc8c69a6c](https://linux-hardware.org/?probe=6cc8c69a6c) | Apr 23, 2022 |
| Lenovo        | ThinkPad T450s 20BWS3FX0... | Notebook    | [00d3556f08](https://linux-hardware.org/?probe=00d3556f08) | Apr 23, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [7988499108](https://linux-hardware.org/?probe=7988499108) | Apr 23, 2022 |
| HP            | 18E9                        | Desktop     | [36ff483a2f](https://linux-hardware.org/?probe=36ff483a2f) | Apr 23, 2022 |
| HP            | EliteBook Folio 9470m       | Notebook    | [cd369fb3e3](https://linux-hardware.org/?probe=cd369fb3e3) | Apr 23, 2022 |
| Lenovo        | ThinkPad T470s 20HF004MM... | Notebook    | [69a5e98a04](https://linux-hardware.org/?probe=69a5e98a04) | Apr 22, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [3e1029ed36](https://linux-hardware.org/?probe=3e1029ed36) | Apr 22, 2022 |
| Lenovo        | IdeaPad 500S-13ISK 80Q2     | Notebook    | [4548a301f8](https://linux-hardware.org/?probe=4548a301f8) | Apr 22, 2022 |
| ASUSTek       | PN51                        | Mini pc     | [757b005814](https://linux-hardware.org/?probe=757b005814) | Apr 21, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [3b76e2f5ab](https://linux-hardware.org/?probe=3b76e2f5ab) | Apr 21, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [ca406cf975](https://linux-hardware.org/?probe=ca406cf975) | Apr 21, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [32d9d8c8df](https://linux-hardware.org/?probe=32d9d8c8df) | Apr 21, 2022 |
| ASUSTek       | PN51                        | Mini pc     | [94e43177eb](https://linux-hardware.org/?probe=94e43177eb) | Apr 21, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [4c46fa8a5b](https://linux-hardware.org/?probe=4c46fa8a5b) | Apr 19, 2022 |
| ASUSTek       | G551JW                      | Notebook    | [b0d7f099f5](https://linux-hardware.org/?probe=b0d7f099f5) | Apr 18, 2022 |
| Lenovo        | ThinkPad X131e 33683YG      | Notebook    | [7855e19861](https://linux-hardware.org/?probe=7855e19861) | Apr 17, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [ce158f41e2](https://linux-hardware.org/?probe=ce158f41e2) | Apr 17, 2022 |
| Acer          | Aspire V3-571               | Notebook    | [5bd64f9988](https://linux-hardware.org/?probe=5bd64f9988) | Apr 17, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [bf54ec19d0](https://linux-hardware.org/?probe=bf54ec19d0) | Apr 16, 2022 |
| Toshiba       | BLB                         | Notebook    | [903779c2b2](https://linux-hardware.org/?probe=903779c2b2) | Apr 16, 2022 |
| Toshiba       | BLB                         | Notebook    | [1dffc347dd](https://linux-hardware.org/?probe=1dffc347dd) | Apr 16, 2022 |
| MSI           | 990FXA-GD80                 | Desktop     | [391705d3c1](https://linux-hardware.org/?probe=391705d3c1) | Apr 15, 2022 |
| HP            | ProBook 430 G1              | Notebook    | [c42de00504](https://linux-hardware.org/?probe=c42de00504) | Apr 15, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [8994d0ea9f](https://linux-hardware.org/?probe=8994d0ea9f) | Apr 15, 2022 |
| Lenovo        | ThinkPad X280 20KE001MMX    | Notebook    | [fb0da9def7](https://linux-hardware.org/?probe=fb0da9def7) | Apr 15, 2022 |
| Dell          | Latitude E7450              | Notebook    | [9af0006104](https://linux-hardware.org/?probe=9af0006104) | Apr 15, 2022 |
| ASUSTek       | Z97-K                       | Desktop     | [53cba6b4f8](https://linux-hardware.org/?probe=53cba6b4f8) | Apr 14, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [b2fdf48a7f](https://linux-hardware.org/?probe=b2fdf48a7f) | Apr 14, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [dba38dc289](https://linux-hardware.org/?probe=dba38dc289) | Apr 13, 2022 |
| HP            | 18E5                        | Desktop     | [3b4f9e8525](https://linux-hardware.org/?probe=3b4f9e8525) | Apr 13, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [ca14d0eb57](https://linux-hardware.org/?probe=ca14d0eb57) | Apr 13, 2022 |
| TUXEDO        | Pulse 14 Gen1               | Notebook    | [68e6736cd2](https://linux-hardware.org/?probe=68e6736cd2) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [0056c8d32e](https://linux-hardware.org/?probe=0056c8d32e) | Apr 13, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [502a8c9d32](https://linux-hardware.org/?probe=502a8c9d32) | Apr 13, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [68aa564b9f](https://linux-hardware.org/?probe=68aa564b9f) | Apr 13, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | Notebook    | [d9f1aff70a](https://linux-hardware.org/?probe=d9f1aff70a) | Apr 13, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [ed40a9ddc1](https://linux-hardware.org/?probe=ed40a9ddc1) | Apr 12, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [9a137f0540](https://linux-hardware.org/?probe=9a137f0540) | Apr 12, 2022 |
| Packard Be... | EasyNote ENTG71BM           | Notebook    | [44520b705b](https://linux-hardware.org/?probe=44520b705b) | Apr 11, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [b9b9565fae](https://linux-hardware.org/?probe=b9b9565fae) | Apr 10, 2022 |
| ASUSTek       | N56DY                       | Notebook    | [8fdcef45a9](https://linux-hardware.org/?probe=8fdcef45a9) | Apr 10, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [ce0316a106](https://linux-hardware.org/?probe=ce0316a106) | Apr 10, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [70e4d389af](https://linux-hardware.org/?probe=70e4d389af) | Apr 10, 2022 |
| MSI           | B250M BAZOOKA               | Desktop     | [91392a601e](https://linux-hardware.org/?probe=91392a601e) | Apr 08, 2022 |
| MSI           | Z170A XPOWER GAMING TITA... | Desktop     | [ffcbeed952](https://linux-hardware.org/?probe=ffcbeed952) | Apr 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [ff93a4d2f5](https://linux-hardware.org/?probe=ff93a4d2f5) | Apr 08, 2022 |
| Maxtang       | FP30 V1.0                   | Desktop     | [2062d8578e](https://linux-hardware.org/?probe=2062d8578e) | Apr 08, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [16fa67b6c1](https://linux-hardware.org/?probe=16fa67b6c1) | Apr 07, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [fca3b357c3](https://linux-hardware.org/?probe=fca3b357c3) | Apr 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [f4c5281aa9](https://linux-hardware.org/?probe=f4c5281aa9) | Apr 07, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | Notebook    | [1c62a4c421](https://linux-hardware.org/?probe=1c62a4c421) | Apr 07, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [53e59cf805](https://linux-hardware.org/?probe=53e59cf805) | Apr 06, 2022 |
| ASRock        | Z97 Pro3                    | Desktop     | [68397184cf](https://linux-hardware.org/?probe=68397184cf) | Apr 06, 2022 |
| ASUSTek       | PRIME X299-DELUXE II        | Desktop     | [f3bc34e630](https://linux-hardware.org/?probe=f3bc34e630) | Apr 05, 2022 |
| HP            | EliteBook 8760w             | Notebook    | [e3a9cdfd95](https://linux-hardware.org/?probe=e3a9cdfd95) | Apr 05, 2022 |
| ASUSTek       | UX32VD                      | Notebook    | [31836fcaa9](https://linux-hardware.org/?probe=31836fcaa9) | Apr 05, 2022 |
| Raspberry ... | Raspberry Pi 2 Model B R... | Soc         | [4361e01e42](https://linux-hardware.org/?probe=4361e01e42) | Apr 04, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [2af47af588](https://linux-hardware.org/?probe=2af47af588) | Apr 04, 2022 |
| Dell          | 0YXT71 A01                  | Desktop     | [5de0fab8f2](https://linux-hardware.org/?probe=5de0fab8f2) | Apr 04, 2022 |
| ASUSTek       | P7P55D-E PRO                | Desktop     | [3e01b6fb25](https://linux-hardware.org/?probe=3e01b6fb25) | Apr 03, 2022 |
| ASUSTek       | PN51                        | Mini pc     | [bcff3a3aef](https://linux-hardware.org/?probe=bcff3a3aef) | Apr 03, 2022 |
| ASUSTek       | PN51                        | Mini pc     | [893945236a](https://linux-hardware.org/?probe=893945236a) | Apr 03, 2022 |
| Lenovo        | 3106 SDK0J40705 WIN 3425... | Desktop     | [b3a74c237d](https://linux-hardware.org/?probe=b3a74c237d) | Apr 02, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [01a521b3d1](https://linux-hardware.org/?probe=01a521b3d1) | Apr 02, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [2d4957c88f](https://linux-hardware.org/?probe=2d4957c88f) | Apr 02, 2022 |
| Gigabyte      | P65Q                        | Notebook    | [c0e5b4550a](https://linux-hardware.org/?probe=c0e5b4550a) | Apr 01, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [0b247aa185](https://linux-hardware.org/?probe=0b247aa185) | Mar 30, 2022 |
| Lenovo        | SKYBAY SDK0J40700 WIN 32... | Desktop     | [137477b9ef](https://linux-hardware.org/?probe=137477b9ef) | Mar 29, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [3a33018680](https://linux-hardware.org/?probe=3a33018680) | Mar 29, 2022 |
| ASRock        | Z77 Extreme4                | Desktop     | [4ab227f4be](https://linux-hardware.org/?probe=4ab227f4be) | Mar 29, 2022 |
| ASUSTek       | P8Z68-V GEN3                | Desktop     | [e4c1632bc2](https://linux-hardware.org/?probe=e4c1632bc2) | Mar 28, 2022 |
| Dell          | Precision 5540              | Notebook    | [26060f12a6](https://linux-hardware.org/?probe=26060f12a6) | Mar 27, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [e5b0f5c259](https://linux-hardware.org/?probe=e5b0f5c259) | Mar 27, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [d5f059e17d](https://linux-hardware.org/?probe=d5f059e17d) | Mar 26, 2022 |
| Intel         | NUC6i5SYB H81131-502        | Mini pc     | [f625382909](https://linux-hardware.org/?probe=f625382909) | Mar 26, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [4e534bb83a](https://linux-hardware.org/?probe=4e534bb83a) | Mar 26, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [d08bb2f15b](https://linux-hardware.org/?probe=d08bb2f15b) | Mar 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [6af3c57a8a](https://linux-hardware.org/?probe=6af3c57a8a) | Mar 24, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [801fa902d0](https://linux-hardware.org/?probe=801fa902d0) | Mar 24, 2022 |
| Gigabyte      | H310M H x.x                 | Desktop     | [5adb4614c4](https://linux-hardware.org/?probe=5adb4614c4) | Mar 23, 2022 |
| Gigabyte      | H310M H x.x                 | Desktop     | [d277e5c6bc](https://linux-hardware.org/?probe=d277e5c6bc) | Mar 23, 2022 |
| HP            | ProBook 430 G1              | Notebook    | [9f295312dc](https://linux-hardware.org/?probe=9f295312dc) | Mar 21, 2022 |
| Dell          | Latitude 7300               | Notebook    | [751dc53e2b](https://linux-hardware.org/?probe=751dc53e2b) | Mar 20, 2022 |
| Dell          | 0F3KHR A00                  | Desktop     | [b312650d8d](https://linux-hardware.org/?probe=b312650d8d) | Mar 20, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [c0faa2a27b](https://linux-hardware.org/?probe=c0faa2a27b) | Mar 19, 2022 |
| Acer          | Aspire XC600 v1.0           | Desktop     | [4191a185d4](https://linux-hardware.org/?probe=4191a185d4) | Mar 19, 2022 |
| Dell          | 09KPNV A00                  | Desktop     | [f71ac898a8](https://linux-hardware.org/?probe=f71ac898a8) | Mar 19, 2022 |
| HP            | EliteBook 850 G5            | Notebook    | [6d8c8748e2](https://linux-hardware.org/?probe=6d8c8748e2) | Mar 17, 2022 |
| Dell          | Inspiron MP061              | Notebook    | [2b46add19f](https://linux-hardware.org/?probe=2b46add19f) | Mar 16, 2022 |
| Fujitsu       | LIFEBOOK E546               | Notebook    | [247dd3e47c](https://linux-hardware.org/?probe=247dd3e47c) | Mar 13, 2022 |
| Lenovo        | IdeaPad 710S-13IKB 80VQ     | Notebook    | [3dc49dc5f3](https://linux-hardware.org/?probe=3dc49dc5f3) | Mar 13, 2022 |
| Toshiba       | Satellite C50D-A-14E        | Notebook    | [256e08de3d](https://linux-hardware.org/?probe=256e08de3d) | Mar 13, 2022 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [21c958ad5f](https://linux-hardware.org/?probe=21c958ad5f) | Mar 12, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [f9345bd168](https://linux-hardware.org/?probe=f9345bd168) | Mar 12, 2022 |
| Lenovo        | 3704 SDK0J40700 WIN 3258... | Desktop     | [e6c507dff4](https://linux-hardware.org/?probe=e6c507dff4) | Mar 12, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [84e80f8c56](https://linux-hardware.org/?probe=84e80f8c56) | Mar 12, 2022 |
| ASUSTek       | G11CD-K                     | Desktop     | [f3347643b0](https://linux-hardware.org/?probe=f3347643b0) | Mar 12, 2022 |
| ASRock        | B550 Phantom Gaming 4/ac    | Desktop     | [d7c05bb862](https://linux-hardware.org/?probe=d7c05bb862) | Mar 11, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [c4d9b11074](https://linux-hardware.org/?probe=c4d9b11074) | Mar 10, 2022 |
| MSI           | Z170A PC MATE               | Desktop     | [181e014823](https://linux-hardware.org/?probe=181e014823) | Mar 08, 2022 |
| Intel         | NUC8BEB J72688-303          | Mini pc     | [8b499a7b72](https://linux-hardware.org/?probe=8b499a7b72) | Mar 08, 2022 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [3e4ac3a045](https://linux-hardware.org/?probe=3e4ac3a045) | Mar 07, 2022 |
| HP            | ENVY 15                     | Notebook    | [a4f5eedd3c](https://linux-hardware.org/?probe=a4f5eedd3c) | Mar 06, 2022 |
| ASUSTek       | E205SA                      | Notebook    | [4c896c9379](https://linux-hardware.org/?probe=4c896c9379) | Mar 05, 2022 |
| ASUSTek       | P5E3 Deluxe                 | Desktop     | [db85b45bf6](https://linux-hardware.org/?probe=db85b45bf6) | Mar 05, 2022 |
| ASRock        | H81M-ITX                    | Desktop     | [c04f6c7365](https://linux-hardware.org/?probe=c04f6c7365) | Mar 05, 2022 |
| Intel         | HURONRIVER                  | Desktop     | [3ff867b4e2](https://linux-hardware.org/?probe=3ff867b4e2) | Mar 05, 2022 |
| Lenovo        | ThinkPad E580 20KS001QMX    | Notebook    | [af4563cb12](https://linux-hardware.org/?probe=af4563cb12) | Mar 04, 2022 |
| ASRock        | X399 Taichi                 | Desktop     | [2efd176b6f](https://linux-hardware.org/?probe=2efd176b6f) | Mar 03, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [88a973e27f](https://linux-hardware.org/?probe=88a973e27f) | Mar 02, 2022 |
| Google        | Rammus                      | Notebook    | [a326a69db9](https://linux-hardware.org/?probe=a326a69db9) | Mar 02, 2022 |
| Google        | Rammus                      | Notebook    | [b395780983](https://linux-hardware.org/?probe=b395780983) | Mar 02, 2022 |
| MSI           | MAG B660M MORTAR DDR4       | Desktop     | [d1c5534f6d](https://linux-hardware.org/?probe=d1c5534f6d) | Feb 27, 2022 |
| HP            | ProBook 640 G2              | Notebook    | [75cdf384b5](https://linux-hardware.org/?probe=75cdf384b5) | Feb 27, 2022 |
| ASUSTek       | P5Q SE2                     | Desktop     | [2b2338382c](https://linux-hardware.org/?probe=2b2338382c) | Feb 27, 2022 |
| Acer          | Aspire V3-571               | Notebook    | [ff2de5c1da](https://linux-hardware.org/?probe=ff2de5c1da) | Feb 27, 2022 |
| Lenovo        | 36D5 SDK0J40700 WIN 3258... | Desktop     | [4ae8fd98cc](https://linux-hardware.org/?probe=4ae8fd98cc) | Feb 26, 2022 |
| Sony          | VPCEB36FG                   | Notebook    | [d46f784fbb](https://linux-hardware.org/?probe=d46f784fbb) | Feb 26, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [cfd0806662](https://linux-hardware.org/?probe=cfd0806662) | Feb 25, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [1434453fc0](https://linux-hardware.org/?probe=1434453fc0) | Feb 24, 2022 |
| Acer          | Swift SF514-52T             | Notebook    | [3bfa40a4c8](https://linux-hardware.org/?probe=3bfa40a4c8) | Feb 24, 2022 |
| MSI           | Z97 PC Mate                 | Desktop     | [1cc7d4542a](https://linux-hardware.org/?probe=1cc7d4542a) | Feb 23, 2022 |
| Elo Touch ... | Geminilake Continental Z... | Desktop     | [6d9bcef1c7](https://linux-hardware.org/?probe=6d9bcef1c7) | Feb 23, 2022 |
| Pegatron      | 2AB5                        | Desktop     | [f2ee067b5f](https://linux-hardware.org/?probe=f2ee067b5f) | Feb 23, 2022 |
| HP            | EliteBook 835 G8 Noteboo... | Notebook    | [4a18cd9a94](https://linux-hardware.org/?probe=4a18cd9a94) | Feb 22, 2022 |
| ASUSTek       | G75VW                       | Notebook    | [d31201b74c](https://linux-hardware.org/?probe=d31201b74c) | Feb 22, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [672f08c769](https://linux-hardware.org/?probe=672f08c769) | Feb 22, 2022 |
| HP            | 86C7                        | All in one  | [efb6906a46](https://linux-hardware.org/?probe=efb6906a46) | Feb 21, 2022 |
| Gigabyte      | F2A88XM-HD3P                | Desktop     | [1c3e6a4af1](https://linux-hardware.org/?probe=1c3e6a4af1) | Feb 21, 2022 |
| Dell          | Precision 3510              | Notebook    | [3956ab645b](https://linux-hardware.org/?probe=3956ab645b) | Feb 21, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [d2119e4516](https://linux-hardware.org/?probe=d2119e4516) | Feb 21, 2022 |
| Unknown       | Unknown                     | Notebook    | [129c8a24d9](https://linux-hardware.org/?probe=129c8a24d9) | Feb 20, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [34117f82de](https://linux-hardware.org/?probe=34117f82de) | Feb 20, 2022 |
| ZEPTO         | ZNOTE                       | Notebook    | [5ff5c2b966](https://linux-hardware.org/?probe=5ff5c2b966) | Feb 20, 2022 |
| Gigabyte      | F2A88XM-HD3P                | Desktop     | [ed1a78c5a6](https://linux-hardware.org/?probe=ed1a78c5a6) | Feb 20, 2022 |
| Dell          | 0P4T42 A01                  | All in one  | [6b8b0ec7f9](https://linux-hardware.org/?probe=6b8b0ec7f9) | Feb 19, 2022 |
| HP            | 3032h                       | Desktop     | [df23e573ba](https://linux-hardware.org/?probe=df23e573ba) | Feb 19, 2022 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [dda75e3ba9](https://linux-hardware.org/?probe=dda75e3ba9) | Feb 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [7b9e4b097d](https://linux-hardware.org/?probe=7b9e4b097d) | Feb 18, 2022 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [b0cf9aa220](https://linux-hardware.org/?probe=b0cf9aa220) | Feb 18, 2022 |
| HP            | Pavilion dv6                | Notebook    | [012e2b5d56](https://linux-hardware.org/?probe=012e2b5d56) | Feb 15, 2022 |
| Dell          | Latitude 5480               | Notebook    | [62ab6cb2c3](https://linux-hardware.org/?probe=62ab6cb2c3) | Feb 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [a8c5477e60](https://linux-hardware.org/?probe=a8c5477e60) | Feb 13, 2022 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [cc35d4696d](https://linux-hardware.org/?probe=cc35d4696d) | Feb 13, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [8ce0419468](https://linux-hardware.org/?probe=8ce0419468) | Feb 13, 2022 |
| HP            | 829A                        | Mini pc     | [dfd0cb667c](https://linux-hardware.org/?probe=dfd0cb667c) | Feb 12, 2022 |
| Dell          | Latitude E6430              | Notebook    | [4b91478aaa](https://linux-hardware.org/?probe=4b91478aaa) | Feb 11, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [0600ea1165](https://linux-hardware.org/?probe=0600ea1165) | Feb 11, 2022 |
| Dell          | Latitude D620               | Notebook    | [dfbcd57dc6](https://linux-hardware.org/?probe=dfbcd57dc6) | Feb 10, 2022 |
| HP            | ENVY 15                     | Notebook    | [91c40a9559](https://linux-hardware.org/?probe=91c40a9559) | Feb 08, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [95b53bcaf7](https://linux-hardware.org/?probe=95b53bcaf7) | Feb 08, 2022 |
| Acer          | Aspire ES1-111              | Notebook    | [8f36d1baac](https://linux-hardware.org/?probe=8f36d1baac) | Feb 08, 2022 |
| Acer          | Aspire ES1-111              | Notebook    | [accf5c8a43](https://linux-hardware.org/?probe=accf5c8a43) | Feb 08, 2022 |
| Lenovo        | E31-70 80KX                 | Notebook    | [d4fe754aa4](https://linux-hardware.org/?probe=d4fe754aa4) | Feb 07, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [2427f8c1da](https://linux-hardware.org/?probe=2427f8c1da) | Feb 07, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [386053c3ce](https://linux-hardware.org/?probe=386053c3ce) | Feb 07, 2022 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [fbea64f951](https://linux-hardware.org/?probe=fbea64f951) | Feb 07, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [db7f189b71](https://linux-hardware.org/?probe=db7f189b71) | Feb 06, 2022 |
| Dell          | 084J0R A00                  | Desktop     | [70c2ff9419](https://linux-hardware.org/?probe=70c2ff9419) | Feb 06, 2022 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | Desktop     | [3a8c47094b](https://linux-hardware.org/?probe=3a8c47094b) | Feb 05, 2022 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | Desktop     | [ae06eadc57](https://linux-hardware.org/?probe=ae06eadc57) | Feb 05, 2022 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [cb34c3126d](https://linux-hardware.org/?probe=cb34c3126d) | Feb 05, 2022 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [a8cc9c8481](https://linux-hardware.org/?probe=a8cc9c8481) | Feb 03, 2022 |
| Packard Be... | IMEDIA S2985                | Desktop     | [661d923ce2](https://linux-hardware.org/?probe=661d923ce2) | Feb 03, 2022 |
| Dell          | 0773VG A01                  | Desktop     | [b1c8ece218](https://linux-hardware.org/?probe=b1c8ece218) | Feb 03, 2022 |
| MSI           | GT680R/GX680R/GT683R/GT6... | Notebook    | [15419beff9](https://linux-hardware.org/?probe=15419beff9) | Feb 02, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [c51e8a279f](https://linux-hardware.org/?probe=c51e8a279f) | Feb 02, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [19cb128817](https://linux-hardware.org/?probe=19cb128817) | Feb 02, 2022 |
| HP            | EliteBook 830 G8 Noteboo... | Notebook    | [f111410eeb](https://linux-hardware.org/?probe=f111410eeb) | Feb 02, 2022 |
| HP            | EliteBook 830 G6            | Notebook    | [108d91c953](https://linux-hardware.org/?probe=108d91c953) | Feb 02, 2022 |
| HP            | EliteBook 830 G6            | Notebook    | [d866cabd88](https://linux-hardware.org/?probe=d866cabd88) | Feb 02, 2022 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [a6321e237c](https://linux-hardware.org/?probe=a6321e237c) | Feb 01, 2022 |
| Acer          | Predator G3610              | Desktop     | [126f12bd14](https://linux-hardware.org/?probe=126f12bd14) | Feb 01, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [340ecf86ab](https://linux-hardware.org/?probe=340ecf86ab) | Feb 01, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [bbe17ee442](https://linux-hardware.org/?probe=bbe17ee442) | Jan 31, 2022 |
| ASUSTek       | GR8                         | Notebook    | [1d8f5be27c](https://linux-hardware.org/?probe=1d8f5be27c) | Jan 30, 2022 |
| Linx          | LAMINALTT8W4G-HBN           | Tablet      | [6350a05df4](https://linux-hardware.org/?probe=6350a05df4) | Jan 29, 2022 |
| Linx          | LAMINALTT8W4G-HBN           | Tablet      | [fa389062e6](https://linux-hardware.org/?probe=fa389062e6) | Jan 29, 2022 |
| Apple         | MacBook3,1                  | Notebook    | [a59b4aa98d](https://linux-hardware.org/?probe=a59b4aa98d) | Jan 29, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [fdf21ecdef](https://linux-hardware.org/?probe=fdf21ecdef) | Jan 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [b584b0b69a](https://linux-hardware.org/?probe=b584b0b69a) | Jan 29, 2022 |
| Lenovo        | ThinkPad T540p 20BE0086M... | Notebook    | [707a381138](https://linux-hardware.org/?probe=707a381138) | Jan 28, 2022 |
| Dell          | 0Y2MRG A00                  | Desktop     | [1a1b794c06](https://linux-hardware.org/?probe=1a1b794c06) | Jan 28, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [6b771832b8](https://linux-hardware.org/?probe=6b771832b8) | Jan 27, 2022 |
| Lenovo        | ThinkPad T420 4236VJ7       | Notebook    | [1d8bb5fbe6](https://linux-hardware.org/?probe=1d8bb5fbe6) | Jan 27, 2022 |
| Lenovo        | ThinkPad T420 4236VJ7       | Notebook    | [87aa03d881](https://linux-hardware.org/?probe=87aa03d881) | Jan 27, 2022 |
| Fujitsu       | D3009-A1 S26361-D3009-A1    | Desktop     | [a0aecb00c0](https://linux-hardware.org/?probe=a0aecb00c0) | Jan 26, 2022 |
| AAEON         | GENE-BT05 V1.1              | Desktop     | [385d6a7c2e](https://linux-hardware.org/?probe=385d6a7c2e) | Jan 25, 2022 |
| MSI           | B85M-E45                    | Desktop     | [5751d3e736](https://linux-hardware.org/?probe=5751d3e736) | Jan 25, 2022 |
| MSI           | B85M-E45                    | Desktop     | [034f7c3687](https://linux-hardware.org/?probe=034f7c3687) | Jan 25, 2022 |
| Lenovo        | ThinkPad T410s 292494G      | Notebook    | [cd8aef64e1](https://linux-hardware.org/?probe=cd8aef64e1) | Jan 24, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [c5c764ccd7](https://linux-hardware.org/?probe=c5c764ccd7) | Jan 24, 2022 |
| Dell          | Latitude E7440              | Notebook    | [74aa958191](https://linux-hardware.org/?probe=74aa958191) | Jan 23, 2022 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [e5aea099ea](https://linux-hardware.org/?probe=e5aea099ea) | Jan 23, 2022 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [f82cb83a85](https://linux-hardware.org/?probe=f82cb83a85) | Jan 23, 2022 |
| Notebook      | N13xWU                      | Notebook    | [0d615c6812](https://linux-hardware.org/?probe=0d615c6812) | Jan 22, 2022 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | Desktop     | [2aa2fc8ed9](https://linux-hardware.org/?probe=2aa2fc8ed9) | Jan 22, 2022 |
| Acer          | Swift SF315-41              | Notebook    | [95afa35615](https://linux-hardware.org/?probe=95afa35615) | Jan 22, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [76ac118b42](https://linux-hardware.org/?probe=76ac118b42) | Jan 20, 2022 |
| Gigabyte      | 990XA-UD3                   | Desktop     | [e5b1e0c400](https://linux-hardware.org/?probe=e5b1e0c400) | Jan 20, 2022 |
| Dell          | Inspiron 5721               | Notebook    | [5310b893aa](https://linux-hardware.org/?probe=5310b893aa) | Jan 19, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [c4103d5c5a](https://linux-hardware.org/?probe=c4103d5c5a) | Jan 19, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [a7cc00f1bb](https://linux-hardware.org/?probe=a7cc00f1bb) | Jan 18, 2022 |
| Dell          | Latitude 7480               | Notebook    | [526c09a456](https://linux-hardware.org/?probe=526c09a456) | Jan 17, 2022 |
| Acer          | Aspire ES1-111              | Notebook    | [2dfe5563ef](https://linux-hardware.org/?probe=2dfe5563ef) | Jan 17, 2022 |
| HP            | EliteBook 850 G3            | Notebook    | [35b6de7b5d](https://linux-hardware.org/?probe=35b6de7b5d) | Jan 16, 2022 |
| Dell          | Precision 3561              | Notebook    | [f5417a1852](https://linux-hardware.org/?probe=f5417a1852) | Jan 16, 2022 |
| Lenovo        | ThinkPad Edge E531 68852... | Notebook    | [2e8135c20d](https://linux-hardware.org/?probe=2e8135c20d) | Jan 15, 2022 |
| Intel         | NUC7i7BNB J31145-304        | Mini pc     | [2b7802edc0](https://linux-hardware.org/?probe=2b7802edc0) | Jan 15, 2022 |
| Lenovo        | ThinkPad T410s 292494G      | Notebook    | [df5d687786](https://linux-hardware.org/?probe=df5d687786) | Jan 14, 2022 |
| Lenovo        | ThinkPad X240 20AMS6170H    | Notebook    | [03fc719875](https://linux-hardware.org/?probe=03fc719875) | Jan 14, 2022 |
| Seco          | C40 C                       | Desktop     | [4243badc3f](https://linux-hardware.org/?probe=4243badc3f) | Jan 14, 2022 |
| Dell          | Latitude 5290               | Notebook    | [f1c632a454](https://linux-hardware.org/?probe=f1c632a454) | Jan 12, 2022 |
| MSI           | Z270 GAMING M7              | Desktop     | [4899dd71f5](https://linux-hardware.org/?probe=4899dd71f5) | Jan 12, 2022 |
| MSI           | Z270 GAMING M7              | Desktop     | [9fa194bf62](https://linux-hardware.org/?probe=9fa194bf62) | Jan 12, 2022 |
| Apple         | MacBook3,1                  | Notebook    | [c670d007f3](https://linux-hardware.org/?probe=c670d007f3) | Jan 11, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [d9856d52b0](https://linux-hardware.org/?probe=d9856d52b0) | Jan 11, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [8b8a13f3b4](https://linux-hardware.org/?probe=8b8a13f3b4) | Jan 11, 2022 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | Desktop     | [19857c8f84](https://linux-hardware.org/?probe=19857c8f84) | Jan 11, 2022 |
| ASUSTek       | UX310UQ                     | Notebook    | [a9b40e5f8c](https://linux-hardware.org/?probe=a9b40e5f8c) | Jan 10, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [0fa4a81a77](https://linux-hardware.org/?probe=0fa4a81a77) | Jan 09, 2022 |
| Sony          | VPCEB3S1E                   | Notebook    | [6f78e2d423](https://linux-hardware.org/?probe=6f78e2d423) | Jan 07, 2022 |
| Lenovo        | B50-30 80ES                 | Notebook    | [42db32249d](https://linux-hardware.org/?probe=42db32249d) | Jan 07, 2022 |
| Razer         | Book 13 - RZ09-0357         | Notebook    | [148a68191d](https://linux-hardware.org/?probe=148a68191d) | Jan 06, 2022 |
| HP            | EliteBook 1040 G2           | Notebook    | [ca6f52fbeb](https://linux-hardware.org/?probe=ca6f52fbeb) | Jan 06, 2022 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [14a4cdc223](https://linux-hardware.org/?probe=14a4cdc223) | Jan 06, 2022 |
| Samsung       | 935XDB                      | Notebook    | [1bb7122515](https://linux-hardware.org/?probe=1bb7122515) | Jan 06, 2022 |
| Lenovo        | ThinkPad X240 20AMA2F8MS    | Notebook    | [7b5c7a047a](https://linux-hardware.org/?probe=7b5c7a047a) | Jan 06, 2022 |
| Supermicro    | X9DRW                       | Server      | [31684ad7e4](https://linux-hardware.org/?probe=31684ad7e4) | Jan 06, 2022 |
| Lenovo        | B50-30 80ES                 | Notebook    | [649be03cf4](https://linux-hardware.org/?probe=649be03cf4) | Jan 06, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [9ebb75d7a4](https://linux-hardware.org/?probe=9ebb75d7a4) | Jan 06, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [27756cb751](https://linux-hardware.org/?probe=27756cb751) | Jan 05, 2022 |
| Packard Be... | EasyNote TE69BM             | Notebook    | [526fc1b476](https://linux-hardware.org/?probe=526fc1b476) | Jan 05, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [a7f4591b40](https://linux-hardware.org/?probe=a7f4591b40) | Jan 05, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [81efe23b11](https://linux-hardware.org/?probe=81efe23b11) | Jan 04, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [446ac9b29a](https://linux-hardware.org/?probe=446ac9b29a) | Jan 04, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ef297a39aa](https://linux-hardware.org/?probe=ef297a39aa) | Jan 04, 2022 |
| Dell          | XPS 13 9350                 | Notebook    | [492d47c1fa](https://linux-hardware.org/?probe=492d47c1fa) | Jan 04, 2022 |
| Intel         | NUC10i5FNB K61361-303       | Mini pc     | [226a67696a](https://linux-hardware.org/?probe=226a67696a) | Jan 03, 2022 |
| Dell          | 0F3KHR A00                  | Desktop     | [a1905b9b4a](https://linux-hardware.org/?probe=a1905b9b4a) | Jan 03, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [367ef74be3](https://linux-hardware.org/?probe=367ef74be3) | Jan 01, 2022 |
| MSI           | H67MA-E45                   | Desktop     | [d15eaff050](https://linux-hardware.org/?probe=d15eaff050) | Jan 01, 2022 |
| MSI           | MPG Z690 FORCE WIFI         | Desktop     | [8317742b36](https://linux-hardware.org/?probe=8317742b36) | Jan 01, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [4a20cd5429](https://linux-hardware.org/?probe=4a20cd5429) | Jan 01, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [fbc9c7ad1a](https://linux-hardware.org/?probe=fbc9c7ad1a) | Jan 01, 2022 |
| MSI           | MS-7211                     | Desktop     | [f8d1e7a88c](https://linux-hardware.org/?probe=f8d1e7a88c) | Dec 31, 2021 |
| Samsung       | 905S3G/906S3G/915S3G        | Notebook    | [7a756782d8](https://linux-hardware.org/?probe=7a756782d8) | Dec 31, 2021 |
| ZEPTO         | ZNOTE                       | Notebook    | [f81a927e9b](https://linux-hardware.org/?probe=f81a927e9b) | Dec 31, 2021 |
| Dell          | Precision 5540              | Notebook    | [ba4fef27b9](https://linux-hardware.org/?probe=ba4fef27b9) | Dec 30, 2021 |
| ASUSTek       | X79-DELUXE                  | Desktop     | [00b9dd3788](https://linux-hardware.org/?probe=00b9dd3788) | Dec 30, 2021 |
| Gigabyte      | F2A88XM-DS2P                | Desktop     | [75eea6ae2f](https://linux-hardware.org/?probe=75eea6ae2f) | Dec 30, 2021 |
| Pegatron      | Narra6                      | Desktop     | [da3be9b31b](https://linux-hardware.org/?probe=da3be9b31b) | Dec 29, 2021 |
| MSI           | MS-7211                     | Desktop     | [3524bec1c8](https://linux-hardware.org/?probe=3524bec1c8) | Dec 29, 2021 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | Desktop     | [02f8579bf3](https://linux-hardware.org/?probe=02f8579bf3) | Dec 29, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [51d4addbb3](https://linux-hardware.org/?probe=51d4addbb3) | Dec 29, 2021 |
| Lenovo        | ThinkPad T490s 20NX000DM... | Notebook    | [e1ba67fc0f](https://linux-hardware.org/?probe=e1ba67fc0f) | Dec 28, 2021 |
| eMachines     | E525                        | Notebook    | [fd80580005](https://linux-hardware.org/?probe=fd80580005) | Dec 28, 2021 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [3ac88f1f0b](https://linux-hardware.org/?probe=3ac88f1f0b) | Dec 28, 2021 |
| Acer          | AOHAPPY                     | Notebook    | [3a8a8f6b8e](https://linux-hardware.org/?probe=3a8a8f6b8e) | Dec 27, 2021 |
| Acer          | Swift SF314-511             | Notebook    | [3a201fd936](https://linux-hardware.org/?probe=3a201fd936) | Dec 27, 2021 |
| ASRock        | X300M-STX                   | Desktop     | [64e387d031](https://linux-hardware.org/?probe=64e387d031) | Dec 27, 2021 |
| Apple         | MacBook3,1                  | Notebook    | [705810cc40](https://linux-hardware.org/?probe=705810cc40) | Dec 25, 2021 |
| eMachines     | E525                        | Notebook    | [fcc3b2a5e3](https://linux-hardware.org/?probe=fcc3b2a5e3) | Dec 25, 2021 |
| eMachines     | E525                        | Notebook    | [e5853e5629](https://linux-hardware.org/?probe=e5853e5629) | Dec 25, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [e1713d01a4](https://linux-hardware.org/?probe=e1713d01a4) | Dec 25, 2021 |
| Samsung       | 950XDB/951XDB/950XDY        | Notebook    | [edad019098](https://linux-hardware.org/?probe=edad019098) | Dec 23, 2021 |
| Foxconn       | 2ABF                        | Desktop     | [0a1cd1d1af](https://linux-hardware.org/?probe=0a1cd1d1af) | Dec 23, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [9dd62bbf73](https://linux-hardware.org/?probe=9dd62bbf73) | Dec 23, 2021 |
| Dell          | 0Y56T3 A00                  | Desktop     | [456cb4ebcc](https://linux-hardware.org/?probe=456cb4ebcc) | Dec 23, 2021 |
| Toshiba       | Satellite L50D-B            | Notebook    | [b5a9d0b1dc](https://linux-hardware.org/?probe=b5a9d0b1dc) | Dec 21, 2021 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [42d4ee98ce](https://linux-hardware.org/?probe=42d4ee98ce) | Dec 21, 2021 |
| Apple         | MacBookAir6,1               | Notebook    | [b2e3490378](https://linux-hardware.org/?probe=b2e3490378) | Dec 21, 2021 |
| Packard Be... | EasyNote TE69HW             | Notebook    | [c6876b9023](https://linux-hardware.org/?probe=c6876b9023) | Dec 20, 2021 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [3fea1de018](https://linux-hardware.org/?probe=3fea1de018) | Dec 20, 2021 |
| eMachines     | E525                        | Notebook    | [bcb03ff38c](https://linux-hardware.org/?probe=bcb03ff38c) | Dec 20, 2021 |
| Acer          | Aspire XC-330               | Desktop     | [1803a4622c](https://linux-hardware.org/?probe=1803a4622c) | Dec 19, 2021 |
| MSI           | Katana GF66 11UE            | Notebook    | [36aea8dc19](https://linux-hardware.org/?probe=36aea8dc19) | Dec 18, 2021 |
| Dell          | Precision 5540              | Notebook    | [14a6857b99](https://linux-hardware.org/?probe=14a6857b99) | Dec 18, 2021 |
| Gigabyte      | F2A88XM-DS2P                | Desktop     | [c18ddabc8d](https://linux-hardware.org/?probe=c18ddabc8d) | Dec 18, 2021 |
| MSI           | Katana GF66 11UE            | Notebook    | [56be528067](https://linux-hardware.org/?probe=56be528067) | Dec 18, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [75b2d1484e](https://linux-hardware.org/?probe=75b2d1484e) | Dec 17, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Sweden/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 266       | 13.39%  |
| Ubuntu 18.04                 | 131       | 6.59%   |
| Ubuntu 22.04                 | 107       | 5.39%   |
| Arch Rolling                 | 50        | 2.52%   |
| Pop!_OS 21.04                | 49        | 2.47%   |
| Debian 11                    | 49        | 2.47%   |
| Manjaro                      | 44        | 2.21%   |
| Arch                         | 40        | 2.01%   |
| OpenMandriva 4.3             | 39        | 1.96%   |
| OpenMandriva 4.2             | 39        | 1.96%   |
| KDE neon 20.04               | 38        | 1.91%   |
| Pop!_OS 22.04                | 33        | 1.66%   |
| Zorin 16                     | 31        | 1.56%   |
| Pop!_OS 20.04                | 30        | 1.51%   |
| Ubuntu 21.10                 | 29        | 1.46%   |
| Ubuntu 21.04                 | 29        | 1.46%   |
| Pop!_OS 20.10                | 29        | 1.46%   |
| Linux Mint 20.3              | 28        | 1.41%   |
| Ubuntu 19.04                 | 27        | 1.36%   |
| Fedora 35                    | 27        | 1.36%   |
| openSUSE Tumbleweed-XXXXXXXX | 26        | 1.31%   |
| Fedora 37                    | 26        | 1.31%   |
| Fedora 34                    | 25        | 1.26%   |
| Ubuntu 19.10                 | 24        | 1.21%   |
| Fedora 36                    | 23        | 1.16%   |
| Fedora 32                    | 23        | 1.16%   |
| ArcoLinux Rolling            | 23        | 1.16%   |
| Zorin 15                     | 21        | 1.06%   |
| Linux Mint 20.2              | 20        | 1.01%   |
| Linux Mint 20                | 20        | 1.01%   |
| Xubuntu 20.04                | 19        | 0.96%   |
| Ubuntu 20.10                 | 19        | 0.96%   |
| Fedora 33                    | 19        | 0.96%   |
| Linux Mint 21.1              | 17        | 0.86%   |
| Linux Mint 20.1              | 17        | 0.86%   |
| Fedora 31                    | 15        | 0.75%   |
| Pop!_OS 21.10                | 14        | 0.7%    |
| Debian 10                    | 14        | 0.7%    |
| Gentoo 2.6                   | 13        | 0.65%   |
| Ubuntu 18.10                 | 12        | 0.6%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 630       | 33.12%  |
| Fedora        | 155       | 8.15%   |
| Pop!_OS       | 147       | 7.73%   |
| Linux Mint    | 138       | 7.26%   |
| OpenMandriva  | 99        | 5.21%   |
| Arch          | 89        | 4.68%   |
| Manjaro       | 87        | 4.57%   |
| Debian        | 80        | 4.21%   |
| Zorin         | 52        | 2.73%   |
| KDE neon      | 47        | 2.47%   |
| Xubuntu       | 38        | 2%      |
| openSUSE      | 31        | 1.63%   |
| Gentoo        | 28        | 1.47%   |
| ArcoLinux     | 28        | 1.47%   |
| Kubuntu       | 22        | 1.16%   |
| ROSA          | 20        | 1.05%   |
| Kali          | 16        | 0.84%   |
| EndeavourOS   | 14        | 0.74%   |
| Elementary    | 14        | 0.74%   |
| Ubuntu MATE   | 13        | 0.68%   |
| CentOS        | 13        | 0.68%   |
| Endless       | 10        | 0.53%   |
| Clear Linux   | 10        | 0.53%   |
| Ubuntu Unity  | 7         | 0.37%   |
| SteamOS       | 7         | 0.37%   |
| LMDE          | 7         | 0.37%   |
| Ubuntu Budgie | 6         | 0.32%   |
| Peppermint    | 6         | 0.32%   |
| Nobara        | 6         | 0.32%   |
| MX            | 6         | 0.32%   |
| Garuda Linux  | 6         | 0.32%   |
| Solus         | 5         | 0.26%   |
| Lubuntu       | 5         | 0.26%   |
| BunsenLabs    | 5         | 0.26%   |
| Slackware     | 4         | 0.21%   |
| Parrot        | 4         | 0.21%   |
| BlackPanther  | 4         | 0.21%   |
| Alpine        | 4         | 0.21%   |
| Ubuntu Studio | 3         | 0.16%   |
| Raspbian      | 3         | 0.16%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 39        | 1.8%    |
| 5.16.7-desktop-1omv4003  | 37        | 1.71%   |
| 5.4.0-42-generic         | 33        | 1.52%   |
| 5.15.0-56-generic        | 27        | 1.25%   |
| 5.4.0-58-generic         | 21        | 0.97%   |
| 5.4.0-48-generic         | 20        | 0.92%   |
| 5.15.0-52-generic        | 19        | 0.88%   |
| 5.11.0-7620-generic      | 19        | 0.88%   |
| 5.3.0-40-generic         | 17        | 0.78%   |
| 5.13.0-7614-generic      | 17        | 0.78%   |
| 5.4.0-52-generic         | 16        | 0.74%   |
| 5.15.0-46-generic        | 15        | 0.69%   |
| 5.13.0-30-generic        | 15        | 0.69%   |
| 5.4.0-40-generic         | 14        | 0.65%   |
| 5.13.0-39-generic        | 14        | 0.65%   |
| 5.4.0-7634-generic       | 13        | 0.6%    |
| 5.15.0-58-generic        | 13        | 0.6%    |
| 5.15.0-48-generic        | 13        | 0.6%    |
| 5.4.0-54-generic         | 12        | 0.55%   |
| 5.4.0-33-generic         | 12        | 0.55%   |
| 5.11.0-37-generic        | 12        | 0.55%   |
| 5.8.0-48-generic         | 11        | 0.51%   |
| 5.4.0-70-generic         | 11        | 0.51%   |
| 5.15.0-53-generic        | 11        | 0.51%   |
| 5.15.0-50-generic        | 11        | 0.51%   |
| 5.11.0-7614-generic      | 11        | 0.51%   |
| 5.10.0-8-amd64           | 11        | 0.51%   |
| 5.8.0-43-generic         | 10        | 0.46%   |
| 5.4.0-65-generic         | 10        | 0.46%   |
| 5.4.0-29-generic         | 10        | 0.46%   |
| 5.19.0-35-generic        | 10        | 0.46%   |
| 5.15.0-60-generic        | 10        | 0.46%   |
| 5.11.0-41-generic        | 10        | 0.46%   |
| 6.1.1-desktop-1omv2290   | 9         | 0.42%   |
| 5.8.0-50-generic         | 9         | 0.42%   |
| 5.4.0-81-generic         | 9         | 0.42%   |
| 5.4.0-67-generic         | 9         | 0.42%   |
| 5.15.0-41-generic        | 9         | 0.42%   |
| 5.15.0-25-generic        | 9         | 0.42%   |
| 4.15.0-47-generic        | 9         | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 335       | 16.27%  |
| 5.15.0  | 170       | 8.26%   |
| 5.11.0  | 129       | 6.27%   |
| 5.13.0  | 118       | 5.73%   |
| 5.8.0   | 98        | 4.76%   |
| 4.15.0  | 81        | 3.93%   |
| 5.3.0   | 76        | 3.69%   |
| 5.10.0  | 65        | 3.16%   |
| 5.0.0   | 59        | 2.87%   |
| 4.18.0  | 47        | 2.28%   |
| 5.10.14 | 40        | 1.94%   |
| 5.16.7  | 38        | 1.85%   |
| 5.19.0  | 31        | 1.51%   |
| 6.1.1   | 12        | 0.58%   |
| 5.17.5  | 12        | 0.58%   |
| 5.14.0  | 11        | 0.53%   |
| 5.18.0  | 10        | 0.49%   |
| 5.12.4  | 10        | 0.49%   |
| 4.19.0  | 10        | 0.49%   |
| 6.1.0   | 9         | 0.44%   |
| 5.17.1  | 9         | 0.44%   |
| 5.16.0  | 8         | 0.39%   |
| 6.1.12  | 7         | 0.34%   |
| 6.0.12  | 7         | 0.34%   |
| 5.7.0   | 7         | 0.34%   |
| 5.19.16 | 7         | 0.34%   |
| 5.15.7  | 7         | 0.34%   |
| 6.1.11  | 6         | 0.29%   |
| 5.9.0   | 6         | 0.29%   |
| 5.8.1   | 6         | 0.29%   |
| 4.9.20  | 6         | 0.29%   |
| 6.1.9   | 5         | 0.24%   |
| 6.0.8   | 5         | 0.24%   |
| 6.0.15  | 5         | 0.24%   |
| 5.9.8   | 5         | 0.24%   |
| 5.9.14  | 5         | 0.24%   |
| 5.5.8   | 5         | 0.24%   |
| 5.18.14 | 5         | 0.24%   |
| 5.17.15 | 5         | 0.24%   |
| 5.16.15 | 5         | 0.24%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 364       | 17.98%  |
| 5.15    | 233       | 11.51%  |
| 5.11    | 158       | 7.8%    |
| 5.10    | 150       | 7.41%   |
| 5.13    | 138       | 6.81%   |
| 5.8     | 135       | 6.67%   |
| 5.3     | 88        | 4.35%   |
| 4.15    | 81        | 4%      |
| 5.16    | 78        | 3.85%   |
| 5.0     | 62        | 3.06%   |
| 4.18    | 54        | 2.67%   |
| 6.1     | 53        | 2.62%   |
| 5.19    | 49        | 2.42%   |
| 5.17    | 46        | 2.27%   |
| 6.0     | 43        | 2.12%   |
| 5.18    | 37        | 1.83%   |
| 5.12    | 36        | 1.78%   |
| 5.9     | 33        | 1.63%   |
| 5.14    | 31        | 1.53%   |
| 5.6     | 28        | 1.38%   |
| 5.7     | 24        | 1.19%   |
| 4.19    | 22        | 1.09%   |
| 6.2     | 16        | 0.79%   |
| 4.9     | 16        | 0.79%   |
| 5.5     | 15        | 0.74%   |
| 5.1     | 7         | 0.35%   |
| 5.2     | 6         | 0.3%    |
| 4.4     | 6         | 0.3%    |
| 4.14    | 3         | 0.15%   |
| 4.1     | 3         | 0.15%   |
| 4.20    | 2         | 0.1%    |
| 4.12    | 2         | 0.1%    |
| 3.10    | 2         | 0.1%    |
| 5       | 1         | 0.05%   |
| 4.16    | 1         | 0.05%   |
| 4.13    | 1         | 0.05%   |
| 3.2     | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1783      | 97.65%  |
| i686    | 22        | 1.2%    |
| aarch64 | 14        | 0.77%   |
| armv7l  | 5         | 0.27%   |
| i586    | 1         | 0.05%   |
| armv8l  | 1         | 0.05%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 889       | 46.4%   |
| Unknown         | 266       | 13.88%  |
| KDE5            | 260       | 13.57%  |
| XFCE            | 140       | 7.31%   |
| X-Cinnamon      | 111       | 5.79%   |
| KDE             | 70        | 3.65%   |
| MATE            | 37        | 1.93%   |
| Cinnamon        | 18        | 0.94%   |
| i3              | 15        | 0.78%   |
| LXDE            | 14        | 0.73%   |
| Pantheon        | 13        | 0.68%   |
| LXQt            | 12        | 0.63%   |
| KDE4            | 11        | 0.57%   |
| Budgie          | 10        | 0.52%   |
| Unity           | 8         | 0.42%   |
| Deepin          | 7         | 0.37%   |
| awesome         | 6         | 0.31%   |
| sway            | 4         | 0.21%   |
| openbox         | 4         | 0.21%   |
| GNOME Classic   | 4         | 0.21%   |
| GNOME Flashback | 3         | 0.16%   |
| DWM             | 3         | 0.16%   |
| qtile           | 2         | 0.1%    |
| LeftWM          | 2         | 0.1%    |
| xmonad          | 1         | 0.05%   |
| Trinity         | 1         | 0.05%   |
| spectrwm        | 1         | 0.05%   |
| GNOME-Flashback | 1         | 0.05%   |
| Enlightenment   | 1         | 0.05%   |
| BunsenLabs      | 1         | 0.05%   |
| bspwm           | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 1382      | 73.63%  |
| Wayland     | 292       | 15.56%  |
| Unknown     | 134       | 7.14%   |
| Tty         | 68        | 3.62%   |
| Unspecified | 1         | 0.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1029      | 54.1%   |
| SDDM    | 230       | 12.09%  |
| GDM     | 217       | 11.41%  |
| GDM3    | 181       | 9.52%   |
| LightDM | 157       | 8.25%   |
| TDM     | 63        | 3.31%   |
| KDM     | 11        | 0.58%   |
| XDM     | 6         | 0.32%   |
| Ly      | 4         | 0.21%   |
| LXDM    | 3         | 0.16%   |
| GREETD  | 1         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 893       | 47.53%  |
| sv_SE       | 512       | 27.25%  |
| Unknown     | 225       | 11.97%  |
| en_GB       | 115       | 6.12%   |
| C           | 44        | 2.34%   |
| de_DE       | 14        | 0.75%   |
| ru_RU       | 12        | 0.64%   |
| en_SE       | 8         | 0.43%   |
| pl_PL       | 7         | 0.37%   |
| en_DK       | 7         | 0.37%   |
| fr_FR       | 4         | 0.21%   |
| en_CA       | 3         | 0.16%   |
| bg_BG       | 3         | 0.16%   |
| uk_UA       | 2         | 0.11%   |
| POSIX       | 2         | 0.11%   |
| nb_NO       | 2         | 0.11%   |
| lt_LT       | 2         | 0.11%   |
| en_US.UTf-8 | 2         | 0.11%   |
| en_IE       | 2         | 0.11%   |
| en_AG       | 2         | 0.11%   |
| C.UTF8      | 2         | 0.11%   |
| zh_CN       | 1         | 0.05%   |
| sv_SE.UTF8  | 1         | 0.05%   |
| sv_FI       | 1         | 0.05%   |
| sma_SE      | 1         | 0.05%   |
| nn_NO       | 1         | 0.05%   |
| it_IT       | 1         | 0.05%   |
| hu_HU       | 1         | 0.05%   |
| fi_FI       | 1         | 0.05%   |
| es_VE       | 1         | 0.05%   |
| es_ES       | 1         | 0.05%   |
| en_IN       | 1         | 0.05%   |
| en_GB.UTF8  | 1         | 0.05%   |
| en_GB.utf-8 | 1         | 0.05%   |
| en_AU       | 1         | 0.05%   |
| el_GR       | 1         | 0.05%   |
| bs_BA       | 1         | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 959       | 51.09%  |
| BIOS | 918       | 48.91%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1419      | 75.76%  |
| Btrfs   | 200       | 10.68%  |
| Overlay | 130       | 6.94%   |
| Unknown | 58        | 3.1%    |
| Xfs     | 31        | 1.66%   |
| Zfs     | 17        | 0.91%   |
| Ext2    | 7         | 0.37%   |
| Tmpfs   | 4         | 0.21%   |
| F2fs    | 4         | 0.21%   |
| Ext3    | 2         | 0.11%   |
| XXXXXXX | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1045      | 55.38%  |
| GPT     | 682       | 36.14%  |
| MBR     | 160       | 8.48%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1608      | 86.5%   |
| Yes       | 251       | 13.5%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1413      | 76.05%  |
| Yes       | 445       | 23.95%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 407       | 22.29%  |
| Hewlett-Packard         | 269       | 14.73%  |
| Lenovo                  | 262       | 14.35%  |
| Dell                    | 197       | 10.79%  |
| MSI                     | 128       | 7.01%   |
| Gigabyte Technology     | 117       | 6.41%   |
| Acer                    | 91        | 4.98%   |
| Apple                   | 59        | 3.23%   |
| ASRock                  | 44        | 2.41%   |
| Intel                   | 26        | 1.42%   |
| Raspberry Pi Foundation | 16        | 0.88%   |
| Sony                    | 15        | 0.82%   |
| Fujitsu                 | 15        | 0.82%   |
| Toshiba                 | 14        | 0.77%   |
| Packard Bell            | 12        | 0.66%   |
| Samsung Electronics     | 10        | 0.55%   |
| Google                  | 9         | 0.49%   |
| Unknown                 | 9         | 0.49%   |
| Supermicro              | 8         | 0.44%   |
| Notebook                | 7         | 0.38%   |
| Microsoft               | 7         | 0.38%   |
| Foxconn                 | 7         | 0.38%   |
| Valve                   | 6         | 0.33%   |
| Pegatron                | 6         | 0.33%   |
| Fujitsu Siemens         | 6         | 0.33%   |
| AAEON                   | 5         | 0.27%   |
| Maxtang                 | 4         | 0.22%   |
| HUAWEI                  | 4         | 0.22%   |
| TUXEDO                  | 3         | 0.16%   |
| Star Labs               | 3         | 0.16%   |
| Schenker                | 2         | 0.11%   |
| Razer                   | 2         | 0.11%   |
| PC Specialist           | 2         | 0.11%   |
| Linx                    | 2         | 0.11%   |
| eMachines               | 2         | 0.11%   |
| Clevo                   | 2         | 0.11%   |
| AZW                     | 2         | 0.11%   |
| AMD                     | 2         | 0.11%   |
| Alienware               | 2         | 0.11%   |
| ZEPTO                   | 1         | 0.05%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| ASUS All Series                    | 21        | 1.15%   |
| Unknown                            | 12        | 0.66%   |
| ASUS ROG STRIX B450-F GAMING       | 11        | 0.6%    |
| ASUS ROG STRIX X570-F GAMING       | 9         | 0.49%   |
| MSI MS-7C37                        | 8         | 0.44%   |
| ASUS ROG STRIX B550-F GAMING       | 8         | 0.44%   |
| ASUS PRIME X470-PRO                | 7         | 0.38%   |
| Valve Jupiter                      | 6         | 0.33%   |
| HP EliteBook Folio 9470m           | 6         | 0.33%   |
| Dell XPS 13 9370                   | 6         | 0.33%   |
| Dell Precision 5540                | 6         | 0.33%   |
| ASUS Z170 PRO GAMING               | 6         | 0.33%   |
| MSI MS-7C52                        | 5         | 0.27%   |
| MSI MS-7C02                        | 5         | 0.27%   |
| MSI MS-7817                        | 5         | 0.27%   |
| Lenovo Yoga C740-14IML 81TC        | 5         | 0.27%   |
| Lenovo MIIX 310-10ICR 80SG         | 5         | 0.27%   |
| HP Pavilion dv7                    | 5         | 0.27%   |
| HP Pavilion 15                     | 5         | 0.27%   |
| HP EliteBook 840 G3                | 5         | 0.27%   |
| HP EliteBook 840 G2                | 5         | 0.27%   |
| Gigabyte B450M DS3H                | 5         | 0.27%   |
| Dell XPS 13 9310                   | 5         | 0.27%   |
| ASUS ROG STRIX B550-I GAMING       | 5         | 0.27%   |
| ASUS ROG STRIX B350-F GAMING       | 5         | 0.27%   |
| ASUS PRIME X370-PRO                | 5         | 0.27%   |
| Apple MacBookPro11,3               | 5         | 0.27%   |
| Acer Aspire V3-571                 | 5         | 0.27%   |
| RPi Raspberry Pi 4 Model B Rev 1.4 | 4         | 0.22%   |
| Maxtang FP30                       | 4         | 0.22%   |
| HP EliteBook 830 G6                | 4         | 0.22%   |
| Dell XPS 15 9570                   | 4         | 0.22%   |
| Dell XPS 15 9500                   | 4         | 0.22%   |
| Dell OptiPlex 7010                 | 4         | 0.22%   |
| ASUS TUF Gaming X570-PLUS          | 4         | 0.22%   |
| ASUS SABERTOOTH 990FX R2.0         | 4         | 0.22%   |
| ASUS ROG STRIX B450-F GAMING II    | 4         | 0.22%   |
| ASUS P8Z77-V LX                    | 4         | 0.22%   |
| ASUS M5A97 R2.0                    | 4         | 0.22%   |
| Apple MacBookPro8,1                | 4         | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 143       | 7.83%   |
| ASUS ROG              | 91        | 4.98%   |
| HP EliteBook          | 77        | 4.22%   |
| Acer Aspire           | 57        | 3.12%   |
| Dell Latitude         | 56        | 3.07%   |
| Dell Precision        | 47        | 2.57%   |
| ASUS PRIME            | 46        | 2.52%   |
| Dell XPS              | 44        | 2.41%   |
| HP Pavilion           | 40        | 2.19%   |
| Lenovo IdeaPad        | 31        | 1.7%    |
| HP ProBook            | 29        | 1.59%   |
| HP Compaq             | 27        | 1.48%   |
| Dell OptiPlex         | 24        | 1.31%   |
| ASUS All              | 21        | 1.15%   |
| Lenovo Yoga           | 18        | 0.99%   |
| HP ENVY               | 17        | 0.93%   |
| ASUS VivoBook         | 17        | 0.93%   |
| ASUS TUF              | 17        | 0.93%   |
| RPi Raspberry         | 16        | 0.88%   |
| HP ZBook              | 15        | 0.82%   |
| HP Laptop             | 13        | 0.71%   |
| Toshiba Satellite     | 12        | 0.66%   |
| Lenovo Legion         | 12        | 0.66%   |
| Unknown               | 12        | 0.66%   |
| HP EliteDesk          | 11        | 0.6%    |
| Dell Inspiron         | 11        | 0.6%    |
| ASUS ZenBook          | 11        | 0.6%    |
| Acer Swift            | 10        | 0.55%   |
| Gigabyte X570         | 9         | 0.49%   |
| ASUS P8Z77-V          | 9         | 0.49%   |
| Packard Bell EasyNote | 8         | 0.44%   |
| MSI MS-7C37           | 8         | 0.44%   |
| Dell Vostro           | 8         | 0.44%   |
| ASUS SABERTOOTH       | 8         | 0.44%   |
| Acer Predator         | 8         | 0.44%   |
| Microsoft Surface     | 7         | 0.38%   |
| Lenovo IdeaCentre     | 7         | 0.38%   |
| Gigabyte B450M        | 7         | 0.38%   |
| Acer Nitro            | 7         | 0.38%   |
| Valve Jupiter         | 6         | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 191       | 10.46%  |
| 2019    | 190       | 10.41%  |
| 2020    | 163       | 8.93%   |
| 2013    | 136       | 7.45%   |
| 2011    | 135       | 7.39%   |
| 2017    | 134       | 7.34%   |
| 2012    | 128       | 7.01%   |
| 2021    | 127       | 6.96%   |
| 2015    | 119       | 6.52%   |
| 2014    | 104       | 5.7%    |
| 2016    | 99        | 5.42%   |
| 2010    | 84        | 4.6%    |
| 2008    | 50        | 2.74%   |
| 2009    | 48        | 2.63%   |
| 2022    | 45        | 2.46%   |
| 2007    | 38        | 2.08%   |
| Unknown | 14        | 0.77%   |
| 2006    | 10        | 0.55%   |
| 2005    | 7         | 0.38%   |
| 2023    | 2         | 0.11%   |
| 2004    | 1         | 0.05%   |
| 2002    | 1         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 938       | 51.37%  |
| Desktop        | 737       | 40.36%  |
| Convertible    | 47        | 2.57%   |
| Mini pc        | 37        | 2.03%   |
| System on chip | 18        | 0.99%   |
| Tablet         | 17        | 0.93%   |
| All in one     | 16        | 0.88%   |
| Server         | 14        | 0.77%   |
| Phone          | 2         | 0.11%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1677      | 91.29%  |
| Enabled  | 160       | 8.71%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1813      | 99.29%  |
| Yes  | 13        | 0.71%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 448       | 24.2%   |
| 4.01-8.0        | 391       | 21.12%  |
| 8.01-16.0       | 314       | 16.96%  |
| 32.01-64.0      | 280       | 15.13%  |
| 3.01-4.0        | 241       | 13.02%  |
| 64.01-256.0     | 60        | 3.24%   |
| 1.01-2.0        | 52        | 2.81%   |
| 24.01-32.0      | 31        | 1.67%   |
| 2.01-3.0        | 16        | 0.86%   |
| 0.51-1.0        | 15        | 0.81%   |
| More than 256.0 | 2         | 0.11%   |
| 0.01-0.5        | 1         | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 643       | 31.83%  |
| 2.01-3.0   | 485       | 24.01%  |
| 4.01-8.0   | 375       | 18.56%  |
| 3.01-4.0   | 263       | 13.02%  |
| 8.01-16.0  | 108       | 5.35%   |
| 0.51-1.0   | 93        | 4.6%    |
| 16.01-24.0 | 24        | 1.19%   |
| 0.01-0.5   | 22        | 1.09%   |
| 24.01-32.0 | 5         | 0.25%   |
| 32.01-64.0 | 1         | 0.05%   |
| Unknown    | 1         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1111      | 58.97%  |
| 2      | 405       | 21.5%   |
| 3      | 164       | 8.7%    |
| 4      | 92        | 4.88%   |
| 5      | 42        | 2.23%   |
| 6      | 27        | 1.43%   |
| 0      | 18        | 0.96%   |
| 7      | 15        | 0.8%    |
| 8      | 5         | 0.27%   |
| 10     | 2         | 0.11%   |
| 26     | 1         | 0.05%   |
| 11     | 1         | 0.05%   |
| 9      | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1241      | 67.56%  |
| Yes       | 596       | 32.44%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1583      | 86.46%  |
| No        | 248       | 13.54%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1320      | 71.7%   |
| No        | 521       | 28.3%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1105      | 59.7%   |
| No        | 746       | 40.3%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Sweden  | 1826      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Computers | Percent |
|-------------------------|-----------|---------|
| Stockholm               | 340       | 17.35%  |
| Gothenburg              | 190       | 9.69%   |
| Malmo                   | 94        | 4.8%    |
| Uppsala                 | 55        | 2.81%   |
| Lund                    | 41        | 2.09%   |
| Linköping              | 39        | 1.99%   |
| Västerås              | 28        | 1.43%   |
| Bromma                  | 28        | 1.43%   |
| Sollentuna              | 27        | 1.38%   |
| Vaxjo                   | 25        | 1.28%   |
| Norrköping             | 25        | 1.28%   |
| Solna                   | 23        | 1.17%   |
| Umeå                   | 22        | 1.12%   |
| Örebro                 | 20        | 1.02%   |
| Haegersten              | 19        | 0.97%   |
| Vaestra Froelunda       | 18        | 0.92%   |
| Sundsvall               | 18        | 0.92%   |
| Karlstad                | 18        | 0.92%   |
| Huddinge                | 16        | 0.82%   |
| Södertälje            | 15        | 0.77%   |
| Helsingborg             | 15        | 0.77%   |
| Kista                   | 14        | 0.71%   |
| Karlskrona              | 14        | 0.71%   |
| Taby                    | 13        | 0.66%   |
| Moelndal                | 13        | 0.66%   |
| Bandhagen               | 13        | 0.66%   |
| Halmstad                | 12        | 0.61%   |
| Sundbyberg              | 11        | 0.56%   |
| Staffanstorp            | 11        | 0.56%   |
| Landskrona              | 11        | 0.56%   |
| Katrineholm             | 11        | 0.56%   |
| Järfälla Municipality | 11        | 0.56%   |
| Gävle                  | 11        | 0.56%   |
| Alvsjo                  | 11        | 0.56%   |
| Upplands Vasby          | 10        | 0.51%   |
| Spanga                  | 10        | 0.51%   |
| Nyköping               | 10        | 0.51%   |
| Norsborg                | 10        | 0.51%   |
| Luleå                  | 10        | 0.51%   |
| Arboga                  | 10        | 0.51%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 609       | 978    | 22.37%  |
| WDC                         | 374       | 599    | 13.73%  |
| Seagate                     | 335       | 547    | 12.3%   |
| Kingston                    | 206       | 289    | 7.57%   |
| Intel                       | 150       | 197    | 5.51%   |
| Toshiba                     | 134       | 177    | 4.92%   |
| SanDisk                     | 133       | 171    | 4.88%   |
| Unknown                     | 101       | 129    | 3.71%   |
| Hitachi                     | 81        | 116    | 2.97%   |
| SK hynix                    | 73        | 81     | 2.68%   |
| Crucial                     | 61        | 91     | 2.24%   |
| Micron Technology           | 55        | 69     | 2.02%   |
| HGST                        | 46        | 55     | 1.69%   |
| Apple                       | 32        | 40     | 1.18%   |
| OCZ                         | 23        | 29     | 0.84%   |
| Phison                      | 21        | 25     | 0.77%   |
| Corsair                     | 20        | 27     | 0.73%   |
| A-DATA Technology           | 19        | 19     | 0.7%    |
| LITEON                      | 17        | 22     | 0.62%   |
| KIOXIA                      | 14        | 15     | 0.51%   |
| Kingston Technology Company | 12        | 13     | 0.44%   |
| Transcend                   | 11        | 12     | 0.4%    |
| LITEONIT                    | 11        | 18     | 0.4%    |
| Intenso                     | 11        | 14     | 0.4%    |
| Silicon Motion              | 10        | 25     | 0.37%   |
| Phison Electronics          | 10        | 12     | 0.37%   |
| Fujitsu                     | 10        | 15     | 0.37%   |
| China                       | 9         | 9      | 0.33%   |
| PNY                         | 8         | 10     | 0.29%   |
| Maxtor                      | 6         | 6      | 0.22%   |
| LaCie                       | 6         | 7      | 0.22%   |
| ASMT                        | 6         | 6      | 0.22%   |
| Unknown                     | 6         | 6      | 0.22%   |
| Micron/Crucial Technology   | 5         | 8      | 0.18%   |
| JMicron Technology          | 5         | 5      | 0.18%   |
| Lenovo                      | 4         | 4      | 0.15%   |
| Hewlett-Packard             | 4         | 6      | 0.15%   |
| XPG                         | 3         | 3      | 0.11%   |
| Union Memory                | 3         | 3      | 0.11%   |
| SPCC                        | 3         | 4      | 0.11%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB                           | 48        | 1.54%   |
| Samsung SSD 850 EVO 500GB                           | 40        | 1.28%   |
| Kingston SV300S37A120G 120GB SSD                    | 29        | 0.93%   |
| Kingston SA400S37120G 120GB SSD                     | 29        | 0.93%   |
| Kingston SA400S37240G 240GB SSD                     | 27        | 0.87%   |
| Samsung SSD 860 EVO 250GB                           | 25        | 0.8%    |
| Samsung NVMe SSD Drive 500GB                        | 25        | 0.8%    |
| Samsung SSD 840 EVO 250GB                           | 23        | 0.74%   |
| Seagate ST4000DM004-2CV104 4TB                      | 21        | 0.67%   |
| Samsung SSD 860 EVO 500GB                           | 20        | 0.64%   |
| Samsung NVMe SSD Drive 512GB                        | 20        | 0.64%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 20        | 0.64%   |
| Kingston SA400S37480G 480GB SSD                     | 20        | 0.64%   |
| Samsung SSD 970 EVO Plus 500GB                      | 18        | 0.58%   |
| Seagate ST1000DM010-2EP102 1TB                      | 17        | 0.55%   |
| SanDisk NVMe SSD Drive 1TB                          | 17        | 0.55%   |
| Samsung NVMe SSD Drive 1TB                          | 16        | 0.51%   |
| Unknown MMC Card  32GB                              | 15        | 0.48%   |
| Seagate ST2000DM008-2FR102 2TB                      | 15        | 0.48%   |
| Samsung SSD 860 EVO 1TB                             | 15        | 0.48%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 15        | 0.48%   |
| HGST HTS721010A9E630 1TB                            | 14        | 0.45%   |
| WDC WD30EFRX-68EUZN0 3TB                            | 13        | 0.42%   |
| Seagate ST500DM002-1BD142 500GB                     | 13        | 0.42%   |
| SanDisk NVMe SSD Drive 512GB                        | 13        | 0.42%   |
| Samsung SSD 970 EVO Plus 1TB                        | 13        | 0.42%   |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB              | 13        | 0.42%   |
| Toshiba NVMe SSD Drive 512GB                        | 12        | 0.38%   |
| Seagate ST4000VN008-2DR166 4TB                      | 12        | 0.38%   |
| Samsung NVMe SSD Drive 1024GB                       | 12        | 0.38%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 11        | 0.35%   |
| Unknown SD/MMC/MS PRO 64GB                          | 11        | 0.35%   |
| Unknown MMC Card  16GB                              | 11        | 0.35%   |
| SK hynix NVMe SSD Drive 512GB                       | 11        | 0.35%   |
| Seagate ST2000DM006-2DM164 2TB                      | 11        | 0.35%   |
| Seagate ST1000DM003-1CH162 1TB                      | 11        | 0.35%   |
| Seagate Expansion+ 2TB                              | 11        | 0.35%   |
| Samsung SSD 840 EVO 500GB                           | 11        | 0.35%   |
| Samsung SSD 840 EVO 120GB                           | 11        | 0.35%   |
| Intel NVMe SSD Drive 1024GB                         | 11        | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 332       | 535    | 35.81%  |
| WDC                 | 288       | 474    | 31.07%  |
| Hitachi             | 81        | 116    | 8.74%   |
| Toshiba             | 74        | 101    | 7.98%   |
| Samsung Electronics | 52        | 87     | 5.61%   |
| HGST                | 46        | 55     | 4.96%   |
| Unknown             | 12        | 14     | 1.29%   |
| Fujitsu             | 10        | 15     | 1.08%   |
| Apple               | 9         | 9      | 0.97%   |
| Maxtor              | 5         | 5      | 0.54%   |
| ASMT                | 5         | 5      | 0.54%   |
| Intenso             | 3         | 3      | 0.32%   |
| ASMedia             | 3         | 3      | 0.32%   |
| Hewlett-Packard     | 2         | 4      | 0.22%   |
| USB3.0              | 1         | 1      | 0.11%   |
| SABRENT             | 1         | 1      | 0.11%   |
| MARVELL             | 1         | 1      | 0.11%   |
| LaCie               | 1         | 1      | 0.11%   |
| IB                  | 1         | 2      | 0.11%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 345       | 513    | 33.5%   |
| Kingston            | 160       | 220    | 15.53%  |
| Intel               | 87        | 110    | 8.45%   |
| SanDisk             | 68        | 84     | 6.6%    |
| Crucial             | 59        | 88     | 5.73%   |
| WDC                 | 52        | 72     | 5.05%   |
| Micron Technology   | 37        | 49     | 3.59%   |
| SK hynix            | 23        | 26     | 2.23%   |
| OCZ                 | 23        | 29     | 2.23%   |
| Apple               | 21        | 27     | 2.04%   |
| Toshiba             | 19        | 26     | 1.84%   |
| LITEON              | 16        | 21     | 1.55%   |
| Corsair             | 12        | 14     | 1.17%   |
| A-DATA Technology   | 12        | 12     | 1.17%   |
| Transcend           | 11        | 12     | 1.07%   |
| LITEONIT            | 11        | 18     | 1.07%   |
| China               | 9         | 9      | 0.87%   |
| Intenso             | 7         | 7      | 0.68%   |
| PNY                 | 5         | 7      | 0.49%   |
| SPCC                | 3         | 4      | 0.29%   |
| M4-CT128            | 3         | 3      | 0.29%   |
| JMicron Technology  | 3         | 3      | 0.29%   |
| Verbatim            | 2         | 3      | 0.19%   |
| Seagate             | 2         | 4      | 0.19%   |
| Patriot             | 2         | 3      | 0.19%   |
| OCZ-VERTEX3         | 2         | 2      | 0.19%   |
| KIOXIA-EXCERIA      | 2         | 3      | 0.19%   |
| KingSpec            | 2         | 2      | 0.19%   |
| GOODRAM             | 2         | 3      | 0.19%   |
| Emtec               | 2         | 2      | 0.19%   |
| XSTAR               | 1         | 2      | 0.1%    |
| WDC WDS2            | 1         | 1      | 0.1%    |
| WDC WDS1            | 1         | 1      | 0.1%    |
| Unknown             | 1         | 1      | 0.1%    |
| TO Exter            | 1         | 1      | 0.1%    |
| tigo                | 1         | 1      | 0.1%    |
| StoreJet            | 1         | 1      | 0.1%    |
| Star                | 1         | 1      | 0.1%    |
| SSSTC               | 1         | 2      | 0.1%    |
| SATAFIRM            | 1         | 1      | 0.1%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 884       | 1407   | 36.32%  |
| HDD     | 749       | 1432   | 30.77%  |
| NVMe    | 676       | 958    | 27.77%  |
| MMC     | 94        | 112    | 3.86%   |
| Unknown | 31        | 40     | 1.27%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1303      | 2696   | 59.52%  |
| NVMe | 675       | 954    | 30.84%  |
| SAS  | 117       | 187    | 5.34%   |
| MMC  | 94        | 112    | 4.29%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1070      | 1746   | 60.21%  |
| 0.51-1.0   | 381       | 566    | 21.44%  |
| 1.01-2.0   | 160       | 245    | 9%      |
| 3.01-4.0   | 67        | 116    | 3.77%   |
| 2.01-3.0   | 57        | 89     | 3.21%   |
| 4.01-10.0  | 39        | 73     | 2.19%   |
| 10.01-20.0 | 3         | 4      | 0.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 515       | 26.56%  |
| 251-500        | 429       | 22.12%  |
| 501-1000       | 255       | 13.15%  |
| 1-20           | 166       | 8.56%   |
| 1001-2000      | 158       | 8.15%   |
| More than 3000 | 134       | 6.91%   |
| 51-100         | 94        | 4.85%   |
| Unknown        | 75        | 3.87%   |
| 2001-3000      | 60        | 3.09%   |
| 21-50          | 53        | 2.73%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 751       | 37.68%  |
| 21-50          | 294       | 14.75%  |
| 101-250        | 258       | 12.95%  |
| 51-100         | 204       | 10.24%  |
| 251-500        | 144       | 7.23%   |
| 501-1000       | 114       | 5.72%   |
| Unknown        | 75        | 3.76%   |
| 1001-2000      | 62        | 3.11%   |
| More than 3000 | 51        | 2.56%   |
| 2001-3000      | 38        | 1.91%   |
| 0              | 2         | 0.1%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                      | 5         | 5      | 3.45%   |
| Seagate ST9250410AS 250GB                      | 3         | 4      | 2.07%   |
| HGST HTS541010A9E680 1TB                       | 3         | 3      | 2.07%   |
| WDC WD5000AAKX-75U6AA0 500GB                   | 2         | 2      | 1.38%   |
| Seagate ST9500420AS 500GB                      | 2         | 2      | 1.38%   |
| Seagate ST4000DM004-2CV104 4TB                 | 2         | 2      | 1.38%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 2         | 2      | 1.38%   |
| Samsung Electronics SSD 870 EVO 1TB            | 2         | 2      | 1.38%   |
| Samsung Electronics HD501LJ 500GB              | 2         | 2      | 1.38%   |
| Samsung Electronics HD300LJ 304GB              | 2         | 2      | 1.38%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 2         | 3      | 1.38%   |
| Intel SSDSC2BW480A4 480GB                      | 2         | 3      | 1.38%   |
| Hitachi HTS543216L9A300 160GB                  | 2         | 2      | 1.38%   |
| Crucial CT525MX300SSD1 528GB                   | 2         | 2      | 1.38%   |
| WDC WDS240G2G0A-00JH30 240GB SSD               | 1         | 1      | 0.69%   |
| WDC WD7500AACS-00ZJB0 752GB                    | 1         | 1      | 0.69%   |
| WDC WD740GD-00FLA1 74GB                        | 1         | 1      | 0.69%   |
| WDC WD6400AAKS-22A7B2 640GB                    | 1         | 1      | 0.69%   |
| WDC WD60EFRX-68L0BN1 6TB                       | 1         | 6      | 0.69%   |
| WDC WD5000LPVX-22V0TT0 500GB                   | 1         | 1      | 0.69%   |
| WDC WD5000BPKT-60PK4T0 500GB                   | 1         | 1      | 0.69%   |
| WDC WD5000AZRX-00A8LB0 500GB                   | 1         | 2      | 0.69%   |
| WDC WD5000AAKX-22ERMA0 500GB                   | 1         | 1      | 0.69%   |
| WDC WD5000AAKS-00A7B2 500GB                    | 1         | 1      | 0.69%   |
| WDC WD40EFRX-68N32N0 4TB                       | 1         | 2      | 0.69%   |
| WDC WD4003FZEX-00Z4SA0 4TB                     | 1         | 2      | 0.69%   |
| WDC WD3200AAKS-75L9A0 320GB                    | 1         | 1      | 0.69%   |
| WDC WD3200AAKS-00B3A0 320GB                    | 1         | 3      | 0.69%   |
| WDC WD30EFRX-68AX9N0 3TB                       | 1         | 1      | 0.69%   |
| WDC WD20EARS-00MVWB0 2TB                       | 1         | 1      | 0.69%   |
| WDC WD15EARS-00Z5B1 1TB                        | 1         | 1      | 0.69%   |
| WDC WD15EADS-00P8B0 1TB                        | 1         | 2      | 0.69%   |
| WDC WD10EZEX-21M2NA0 1TB                       | 1         | 2      | 0.69%   |
| WDC WD10EZEX-00WN4A0 1TB                       | 1         | 3      | 0.69%   |
| WDC WD10EZEX-00BN5A0 1TB                       | 1         | 1      | 0.69%   |
| WDC WD10EFRX-68FYTN0 1TB                       | 1         | 1      | 0.69%   |
| WDC WD10EARS-00Y5B1 1TB                        | 1         | 2      | 0.69%   |
| WDC WD10EARS-00MVWB0 1TB                       | 1         | 1      | 0.69%   |
| WDC WD10EALX-009BA0 1TB                        | 1         | 3      | 0.69%   |
| WDC WD10EADS-00M2B0 1TB                        | 1         | 1      | 0.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 32        | 38     | 22.86%  |
| WDC                 | 26        | 46     | 18.57%  |
| Samsung Electronics | 17        | 17     | 12.14%  |
| Hitachi             | 13        | 15     | 9.29%   |
| Intel               | 12        | 15     | 8.57%   |
| HGST                | 6         | 6      | 4.29%   |
| Kingston            | 4         | 4      | 2.86%   |
| Toshiba             | 3         | 4      | 2.14%   |
| OCZ                 | 3         | 5      | 2.14%   |
| Micron Technology   | 3         | 4      | 2.14%   |
| Crucial             | 3         | 3      | 2.14%   |
| Corsair             | 3         | 3      | 2.14%   |
| SK hynix            | 2         | 2      | 1.43%   |
| SanDisk             | 2         | 2      | 1.43%   |
| LITEONIT            | 2         | 2      | 1.43%   |
| Fujitsu             | 2         | 2      | 1.43%   |
| Apple               | 2         | 2      | 1.43%   |
| Union Memory        | 1         | 1      | 0.71%   |
| Transcend           | 1         | 1      | 0.71%   |
| PNY                 | 1         | 2      | 0.71%   |
| Hewlett-Packard     | 1         | 1      | 0.71%   |
| China               | 1         | 1      | 0.71%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 32        | 38     | 34.04%  |
| WDC                 | 25        | 45     | 26.6%   |
| Hitachi             | 13        | 15     | 13.83%  |
| Samsung Electronics | 10        | 10     | 10.64%  |
| HGST                | 6         | 6      | 6.38%   |
| Toshiba             | 3         | 4      | 3.19%   |
| Fujitsu             | 2         | 2      | 2.13%   |
| Apple               | 2         | 2      | 2.13%   |
| Hewlett-Packard     | 1         | 1      | 1.06%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 91        | 123    | 67.41%  |
| SSD  | 39        | 48     | 28.89%  |
| NVMe | 5         | 5      | 3.7%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                                           | Computers | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 980 1TB                                 | 1         | 1      | 50%     |
| Samsung Electronics NVMe SSD Controller SM961/PM961/SM963 256GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1193      | 2515   | 59.59%  |
| Works    | 677       | 1256   | 33.82%  |
| Malfunc  | 130       | 176    | 6.49%   |
| Failed   | 2         | 2      | 0.1%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1150      | 48.63%  |
| AMD                              | 386       | 16.32%  |
| Samsung Electronics              | 306       | 12.94%  |
| SanDisk                          | 102       | 4.31%   |
| Kingston Technology Company      | 59        | 2.49%   |
| SK hynix                         | 49        | 2.07%   |
| Toshiba America Info Systems     | 45        | 1.9%    |
| ASMedia Technology               | 41        | 1.73%   |
| Phison Electronics               | 40        | 1.69%   |
| JMicron Technology               | 32        | 1.35%   |
| Marvell Technology Group         | 30        | 1.27%   |
| Nvidia                           | 19        | 0.8%    |
| Micron Technology                | 19        | 0.8%    |
| KIOXIA                           | 13        | 0.55%   |
| Silicon Motion                   | 12        | 0.51%   |
| ADATA Technology                 | 8         | 0.34%   |
| Silicon Image                    | 6         | 0.25%   |
| Micron/Crucial Technology        | 6         | 0.25%   |
| Union Memory (Shenzhen)          | 5         | 0.21%   |
| Lite-On Technology               | 5         | 0.21%   |
| VIA Technologies                 | 4         | 0.17%   |
| Lenovo                           | 4         | 0.17%   |
| Broadcom / LSI                   | 4         | 0.17%   |
| Apple                            | 4         | 0.17%   |
| Solid State Storage Technology   | 3         | 0.13%   |
| Silicon Integrated Systems [SiS] | 3         | 0.13%   |
| LSI Logic / Symbios Logic        | 3         | 0.13%   |
| Hewlett-Packard                  | 3         | 0.13%   |
| Realtek Semiconductor            | 2         | 0.08%   |
| Seagate Technology               | 1         | 0.04%   |
| Adaptec                          | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 256       | 9.4%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 169       | 6.21%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 90        | 3.31%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 84        | 3.09%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 67        | 2.46%   |
| AMD 400 Series Chipset SATA Controller                                         | 67        | 2.46%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 57        | 2.09%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 53        | 1.95%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 53        | 1.95%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 51        | 1.87%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 47        | 1.73%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 46        | 1.69%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 43        | 1.58%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 42        | 1.54%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 40        | 1.47%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 37        | 1.36%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 35        | 1.29%   |
| Intel Volume Management Device NVMe RAID Controller                            | 34        | 1.25%   |
| Intel SSD 660P Series                                                          | 34        | 1.25%   |
| Intel SATA Controller [RAID mode]                                              | 34        | 1.25%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 34        | 1.25%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 33        | 1.21%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 33        | 1.21%   |
| AMD 500 Series Chipset SATA Controller                                         | 33        | 1.21%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 31        | 1.14%   |
| Kingston Company A2000 NVMe SSD                                                | 31        | 1.14%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 31        | 1.14%   |
| Samsung NVMe SSD Controller 980                                                | 30        | 1.1%    |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 28        | 1.03%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 28        | 1.03%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 27        | 0.99%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 22        | 0.81%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 22        | 0.81%   |
| Phison E12 NVMe Controller                                                     | 21        | 0.77%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 21        | 0.77%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 20        | 0.73%   |
| Micron NVMe Storage Controller                                                 | 19        | 0.7%    |
| Intel Comet Lake SATA AHCI Controller                                          | 18        | 0.66%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 18        | 0.66%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 18        | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1314      | 55.54%  |
| NVMe | 683       | 28.87%  |
| IDE  | 216       | 9.13%   |
| RAID | 143       | 6.04%   |
| SAS  | 8         | 0.34%   |
| SCSI | 2         | 0.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 1340      | 73.38%  |
| AMD      | 466       | 25.52%  |
| ARM      | 19        | 1.04%   |
| QUALCOMM | 1         | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 27        | 1.48%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 26        | 1.42%   |
| AMD Ryzen 5 3600 6-Core Processor       | 23        | 1.26%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 22        | 1.2%    |
| Intel Core i7-8565U CPU @ 1.80GHz       | 20        | 1.09%   |
| Intel Core i5-6600K CPU @ 3.50GHz       | 17        | 0.93%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 17        | 0.93%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 15        | 0.82%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 14        | 0.77%   |
| ARM Processor                           | 14        | 0.77%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 13        | 0.71%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 13        | 0.71%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 12        | 0.66%   |
| Intel Core i7-6700K CPU @ 4.00GHz       | 11        | 0.6%    |
| Intel Core i7-4790K CPU @ 4.00GHz       | 11        | 0.6%    |
| Intel Core i5-4690K CPU @ 3.50GHz       | 11        | 0.6%    |
| Intel Core i5-10210U CPU @ 1.60GHz      | 11        | 0.6%    |
| Intel Atom x5-Z8350 CPU @ 1.44GHz       | 11        | 0.6%    |
| AMD Ryzen 5 5600X 6-Core Processor      | 11        | 0.6%    |
| Intel Core i7-7500U CPU @ 2.70GHz       | 10        | 0.55%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 10        | 0.55%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 10        | 0.55%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 10        | 0.55%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 10        | 0.55%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 10        | 0.55%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 10        | 0.55%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 10        | 0.55%   |
| AMD Ryzen 5 2600 Six-Core Processor     | 10        | 0.55%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 9         | 0.49%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 9         | 0.49%   |
| Intel Core i7-2600 CPU @ 3.40GHz        | 9         | 0.49%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 9         | 0.49%   |
| Intel Core i5-2500K CPU @ 3.30GHz       | 9         | 0.49%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 8         | 0.44%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 8         | 0.44%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 8         | 0.44%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 8         | 0.44%   |
| Intel Celeron CPU N2840 @ 2.16GHz       | 8         | 0.44%   |
| AMD Ryzen 7 4700U with Radeon Graphics  | 8         | 0.44%   |
| AMD Ryzen 7 2700X Eight-Core Processor  | 8         | 0.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 439       | 24.03%  |
| Intel Core i7           | 428       | 23.43%  |
| AMD Ryzen 5             | 119       | 6.51%   |
| Other                   | 115       | 6.29%   |
| AMD Ryzen 7             | 96        | 5.25%   |
| Intel Core i3           | 76        | 4.16%   |
| Intel Celeron           | 65        | 3.56%   |
| Intel Core 2 Duo        | 59        | 3.23%   |
| AMD Ryzen 9             | 44        | 2.41%   |
| Intel Xeon              | 42        | 2.3%    |
| Intel Pentium           | 33        | 1.81%   |
| AMD FX                  | 32        | 1.75%   |
| Intel Atom              | 25        | 1.37%   |
| AMD Ryzen 3             | 19        | 1.04%   |
| Intel Core i9           | 16        | 0.88%   |
| Intel Core 2 Quad       | 15        | 0.82%   |
| Intel Core 2            | 13        | 0.71%   |
| AMD A8                  | 13        | 0.71%   |
| AMD Ryzen Threadripper  | 11        | 0.6%    |
| AMD A6                  | 10        | 0.55%   |
| Intel Pentium Dual-Core | 9         | 0.49%   |
| Intel Genuine           | 9         | 0.49%   |
| AMD Phenom II X4        | 9         | 0.49%   |
| AMD A4                  | 9         | 0.49%   |
| AMD Ryzen 7 PRO         | 8         | 0.44%   |
| AMD E1                  | 7         | 0.38%   |
| AMD E                   | 7         | 0.38%   |
| AMD Phenom II X6        | 6         | 0.33%   |
| AMD Athlon II X2        | 6         | 0.33%   |
| AMD Athlon 64 X2        | 6         | 0.33%   |
| AMD A10                 | 6         | 0.33%   |
| Intel Pentium Dual      | 5         | 0.27%   |
| ARM BCM                 | 5         | 0.27%   |
| AMD Ryzen Embedded      | 5         | 0.27%   |
| AMD Ryzen 5 PRO         | 5         | 0.27%   |
| Intel Pentium Silver    | 4         | 0.22%   |
| Intel Core m3           | 3         | 0.16%   |
| Intel Celeron Dual-Core | 3         | 0.16%   |
| AMD Athlon II X4        | 3         | 0.16%   |
| AMD Athlon II X3        | 3         | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 712       | 38.91%  |
| 2       | 606       | 33.11%  |
| 6       | 223       | 12.19%  |
| 8       | 153       | 8.36%   |
| 12      | 41        | 2.24%   |
| 16      | 28        | 1.53%   |
| 1       | 26        | 1.42%   |
| 3       | 16        | 0.87%   |
| 14      | 6         | 0.33%   |
| 10      | 5         | 0.27%   |
| Unknown | 5         | 0.27%   |
| 18      | 4         | 0.22%   |
| 32      | 2         | 0.11%   |
| 64      | 1         | 0.05%   |
| 28      | 1         | 0.05%   |
| 20      | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1800      | 98.58%  |
| 2       | 21        | 1.15%   |
| Unknown | 4         | 0.22%   |
| 3       | 1         | 0.05%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1250      | 68.31%  |
| 1       | 575       | 31.42%  |
| Unknown | 5         | 0.27%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1778      | 97.16%  |
| Unknown        | 41        | 2.24%   |
| 32-bit         | 10        | 0.55%   |
| 64-bit         | 1         | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 487       | 25.6%   |
| 0x306c3    | 98        | 5.15%   |
| 0x206a7    | 88        | 4.63%   |
| 0x306a9    | 83        | 4.36%   |
| 0x906ea    | 47        | 2.47%   |
| 0x1067a    | 47        | 2.47%   |
| 0x40651    | 46        | 2.42%   |
| 0x806ec    | 45        | 2.37%   |
| 0x506e3    | 44        | 2.31%   |
| 0x906e9    | 42        | 2.21%   |
| 0x806ea    | 41        | 2.16%   |
| 0x406e3    | 40        | 2.1%    |
| 0x306d4    | 40        | 2.1%    |
| 0x806e9    | 39        | 2.05%   |
| 0x08701021 | 37        | 1.95%   |
| 0x806c1    | 34        | 1.79%   |
| 0x20655    | 26        | 1.37%   |
| 0x406c4    | 19        | 1%      |
| 0x0800820d | 19        | 1%      |
| 0x0a50000c | 18        | 0.95%   |
| 0x08701013 | 18        | 0.95%   |
| 0x08108109 | 18        | 0.95%   |
| 0x906ed    | 15        | 0.79%   |
| 0x6fd      | 14        | 0.74%   |
| 0x08600106 | 14        | 0.74%   |
| 0x0810100b | 14        | 0.74%   |
| 0x06000852 | 14        | 0.74%   |
| 0x010000c8 | 14        | 0.74%   |
| 0x30678    | 13        | 0.68%   |
| 0x0a201009 | 13        | 0.68%   |
| 0xa0652    | 12        | 0.63%   |
| 0x806eb    | 12        | 0.63%   |
| 0x6f6      | 12        | 0.63%   |
| 0x306f2    | 12        | 0.63%   |
| 0x106e5    | 12        | 0.63%   |
| 0x906a3    | 11        | 0.58%   |
| 0x10676    | 11        | 0.58%   |
| 0x08108102 | 10        | 0.53%   |
| 0x08001138 | 10        | 0.53%   |
| 0x06001119 | 10        | 0.53%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 325       | 17.78%  |
| Haswell          | 196       | 10.72%  |
| SandyBridge      | 127       | 6.95%   |
| Skylake          | 117       | 6.4%    |
| IvyBridge        | 112       | 6.13%   |
| Zen 2            | 106       | 5.8%    |
| Penryn           | 70        | 3.83%   |
| Zen 3            | 66        | 3.61%   |
| Zen+             | 65        | 3.56%   |
| Unknown          | 62        | 3.39%   |
| Broadwell        | 52        | 2.84%   |
| Silvermont       | 50        | 2.74%   |
| Zen              | 49        | 2.68%   |
| Core             | 48        | 2.63%   |
| Westmere         | 47        | 2.57%   |
| TigerLake        | 47        | 2.57%   |
| K10              | 38        | 2.08%   |
| CometLake        | 35        | 1.91%   |
| Piledriver       | 33        | 1.81%   |
| Alderlake Hybrid | 21        | 1.15%   |
| Goldmont plus    | 20        | 1.09%   |
| Icelake          | 19        | 1.04%   |
| Nehalem          | 18        | 0.98%   |
| Excavator        | 15        | 0.82%   |
| K8 Hammer        | 12        | 0.66%   |
| K10 Llano        | 12        | 0.66%   |
| Jaguar           | 10        | 0.55%   |
| Bulldozer        | 10        | 0.55%   |
| Bobcat           | 10        | 0.55%   |
| Goldmont         | 9         | 0.49%   |
| Bonnell          | 7         | 0.38%   |
| Puma             | 6         | 0.33%   |
| P6               | 4         | 0.22%   |
| NetBurst         | 3         | 0.16%   |
| Steamroller      | 2         | 0.11%   |
| K8 & K10 hybrid  | 2         | 0.11%   |
| Tremont          | 1         | 0.05%   |
| K6               | 1         | 0.05%   |
| Geode            | 1         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 948       | 44.72%  |
| Nvidia                           | 678       | 31.98%  |
| AMD                              | 475       | 22.41%  |
| Matrox Electronics Systems       | 9         | 0.42%   |
| ASPEED Technology                | 7         | 0.33%   |
| Silicon Integrated Systems [SiS] | 3         | 0.14%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 83        | 3.79%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 60        | 2.74%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 56        | 2.56%   |
| Intel UHD Graphics 620                                                                   | 50        | 2.28%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 46        | 2.1%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 44        | 2.01%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 42        | 1.92%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 42        | 1.92%   |
| Intel HD Graphics 620                                                                    | 40        | 1.83%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 40        | 1.83%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 36        | 1.64%   |
| Intel HD Graphics 5500                                                                   | 35        | 1.6%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 34        | 1.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 32        | 1.46%   |
| Intel HD Graphics 630                                                                    | 30        | 1.37%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 30        | 1.37%   |
| AMD Renoir                                                                               | 29        | 1.32%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 26        | 1.19%   |
| Intel Core Processor Integrated Graphics Controller                                      | 25        | 1.14%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 25        | 1.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 23        | 1.05%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 22        | 1%      |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 22        | 1%      |
| Intel HD Graphics 530                                                                    | 21        | 0.96%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 19        | 0.87%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 18        | 0.82%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 18        | 0.82%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 18        | 0.82%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 16        | 0.73%   |
| AMD Lucienne                                                                             | 16        | 0.73%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 15        | 0.68%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 15        | 0.68%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 15        | 0.68%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 15        | 0.68%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 15        | 0.68%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 14        | 0.64%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 14        | 0.64%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 14        | 0.64%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 13        | 0.59%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 13        | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 678       | 36.83%  |
| 1 x Nvidia               | 431       | 23.41%  |
| 1 x AMD                  | 383       | 20.8%   |
| Intel + Nvidia           | 208       | 11.3%   |
| 2 x AMD                  | 31        | 1.68%   |
| Intel + AMD              | 31        | 1.68%   |
| AMD + Nvidia             | 31        | 1.68%   |
| Other                    | 21        | 1.14%   |
| 1 x Matrox               | 7         | 0.38%   |
| 1 x ASPEED               | 7         | 0.38%   |
| 2 x Nvidia               | 4         | 0.22%   |
| 1 x SiS                  | 3         | 0.16%   |
| Intel + 2 x Nvidia       | 2         | 0.11%   |
| 2 x Nvidia + 1 x Matrox  | 1         | 0.05%   |
| 2 x Intel                | 1         | 0.05%   |
| Nvidia + Matrox          | 1         | 0.05%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1365      | 73.47%  |
| Proprietary | 409       | 22.01%  |
| Unknown     | 84        | 4.52%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1008      | 53.5%   |
| 1.01-2.0   | 213       | 11.31%  |
| 0.01-0.5   | 189       | 10.03%  |
| 0.51-1.0   | 123       | 6.53%   |
| 3.01-4.0   | 119       | 6.32%   |
| 7.01-8.0   | 112       | 5.94%   |
| 5.01-6.0   | 58        | 3.08%   |
| 8.01-16.0  | 36        | 1.91%   |
| 2.01-3.0   | 22        | 1.17%   |
| 16.01-24.0 | 4         | 0.21%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 258       | 12.48%  |
| Samsung Electronics     | 244       | 11.8%   |
| LG Display              | 152       | 7.35%   |
| Chimei Innolux          | 141       | 6.82%   |
| Dell                    | 115       | 5.56%   |
| BenQ                    | 106       | 5.13%   |
| Philips                 | 101       | 4.88%   |
| BOE                     | 86        | 4.16%   |
| Ancor Communications    | 86        | 4.16%   |
| Hewlett-Packard         | 83        | 4.01%   |
| AOC                     | 83        | 4.01%   |
| Acer                    | 72        | 3.48%   |
| Sharp                   | 57        | 2.76%   |
| Goldstar                | 54        | 2.61%   |
| Apple                   | 48        | 2.32%   |
| Lenovo                  | 42        | 2.03%   |
| ASUSTek Computer        | 33        | 1.6%    |
| Chi Mei Optoelectronics | 24        | 1.16%   |
| InfoVision              | 21        | 1.02%   |
| MSI                     | 20        | 0.97%   |
| Eizo                    | 20        | 0.97%   |
| LG Philips              | 17        | 0.82%   |
| Sony                    | 14        | 0.68%   |
| Vestel Elektronik       | 13        | 0.63%   |
| Unknown                 | 11        | 0.53%   |
| LG Electronics          | 11        | 0.53%   |
| CSO                     | 11        | 0.53%   |
| Panasonic               | 10        | 0.48%   |
| PANDA                   | 9         | 0.44%   |
| ViewSonic               | 8         | 0.39%   |
| Fujitsu Siemens         | 8         | 0.39%   |
| VOXICON                 | 5         | 0.24%   |
| Toshiba                 | 5         | 0.24%   |
| Microstep               | 5         | 0.24%   |
| BOE Technology Group    | 5         | 0.24%   |
| Quanta Display          | 4         | 0.19%   |
| OEM                     | 4         | 0.19%   |
| LGD                     | 4         | 0.19%   |
| Gigabyte Technology     | 4         | 0.19%   |
| AUS                     | 4         | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 13        | 0.6%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch            | 11        | 0.51%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 10        | 0.46%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch         | 9         | 0.42%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 8         | 0.37%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 8         | 0.37%   |
| BenQ G2420HDBL BNQ785F 1920x1080 477x268mm 21.5-inch                   | 8         | 0.37%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch          | 8         | 0.37%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch         | 8         | 0.37%   |
| AOC 2460G5 AOC2460 1920x1080 531x299mm 24.0-inch                       | 8         | 0.37%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch  | 7         | 0.32%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch         | 7         | 0.32%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch          | 7         | 0.32%   |
| AOC 24G2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                     | 7         | 0.32%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                     | 6         | 0.28%   |
| Philips 273ELH PHLC07D 1920x1080 598x336mm 27.0-inch                   | 6         | 0.28%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 6         | 0.28%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch       | 6         | 0.28%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch       | 6         | 0.28%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch         | 6         | 0.28%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch          | 6         | 0.28%   |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                     | 6         | 0.28%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch       | 6         | 0.28%   |
| Ancor Communications ASUS PB278 ACI27A3 2560x1440 597x336mm 27.0-inch  | 6         | 0.28%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch                | 5         | 0.23%   |
| Philips PHL BDM3270 PHL08E7 2560x1440 708x398mm 32.0-inch              | 5         | 0.23%   |
| Philips PHL 436M6VBP PHLC179 3840x2160 941x529mm 42.5-inch             | 5         | 0.23%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                | 5         | 0.23%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch       | 5         | 0.23%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch       | 5         | 0.23%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch       | 5         | 0.23%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                     | 5         | 0.23%   |
| AOC 27B2G5 AOC2702 1920x1080 598x336mm 27.0-inch                       | 5         | 0.23%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch                | 4         | 0.19%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch                | 4         | 0.19%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 309x174mm 14.0-inch  | 4         | 0.19%   |
| Philips PHL 278E8Q PHLC161 1920x1080 598x336mm 27.0-inch               | 4         | 0.19%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 4         | 0.19%   |
| Panasonic VVX16T029D00 MEI96A2 2880x1620 344x193mm 15.5-inch           | 4         | 0.19%   |
| OEM 32W_LCD_TV OEM3700 1920x540                                        | 4         | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 871       | 43.83%  |
| 1366x768 (WXGA)    | 229       | 11.52%  |
| 2560x1440 (QHD)    | 167       | 8.4%    |
| 3840x2160 (4K)     | 164       | 8.25%   |
| 1680x1050 (WSXGA+) | 72        | 3.62%   |
| 1920x1200 (WUXGA)  | 62        | 3.12%   |
| 3440x1440          | 53        | 2.67%   |
| 1280x1024 (SXGA)   | 45        | 2.26%   |
| 1600x900 (HD+)     | 43        | 2.16%   |
| 1280x800 (WXGA)    | 39        | 1.96%   |
| Unknown            | 37        | 1.86%   |
| 1440x900 (WXGA+)   | 26        | 1.31%   |
| 2560x1600          | 24        | 1.21%   |
| 3840x2400          | 17        | 0.86%   |
| 3840x1080          | 16        | 0.81%   |
| 2880x1800          | 16        | 0.81%   |
| 1024x768 (XGA)     | 12        | 0.6%    |
| 1360x768           | 9         | 0.45%   |
| 1920x540           | 8         | 0.4%    |
| 2736x1824          | 7         | 0.35%   |
| 1280x720 (HD)      | 7         | 0.35%   |
| 3200x1800 (QHD+)   | 6         | 0.3%    |
| 800x1280           | 5         | 0.25%   |
| 2560x1080          | 5         | 0.25%   |
| 1024x600           | 5         | 0.25%   |
| 3840x1600          | 4         | 0.2%    |
| 6400x2160          | 3         | 0.15%   |
| 5760x1080          | 3         | 0.15%   |
| 2288x1287          | 3         | 0.15%   |
| 2160x1440          | 3         | 0.15%   |
| 5760x2160          | 2         | 0.1%    |
| 4480x1440          | 2         | 0.1%    |
| 3840x1200          | 2         | 0.1%    |
| 3200x1200          | 2         | 0.1%    |
| 1280x768           | 2         | 0.1%    |
| 7280x2160          | 1         | 0.05%   |
| 5520x2160          | 1         | 0.05%   |
| 5360x1440          | 1         | 0.05%   |
| 4864x1080          | 1         | 0.05%   |
| 4240x1440          | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 376       | 18.31%  |
| 13      | 233       | 11.34%  |
| 27      | 219       | 10.66%  |
| 24      | 213       | 10.37%  |
| 14      | 150       | 7.3%    |
| Unknown | 141       | 6.86%   |
| 23      | 131       | 6.38%   |
| 17      | 79        | 3.85%   |
| 12      | 57        | 2.78%   |
| 21      | 54        | 2.63%   |
| 22      | 53        | 2.58%   |
| 34      | 49        | 2.39%   |
| 31      | 46        | 2.24%   |
| 19      | 43        | 2.09%   |
| 84      | 30        | 1.46%   |
| 11      | 25        | 1.22%   |
| 32      | 18        | 0.88%   |
| 16      | 11        | 0.54%   |
| 72      | 10        | 0.49%   |
| 65      | 10        | 0.49%   |
| 25      | 10        | 0.49%   |
| 20      | 10        | 0.49%   |
| 54      | 8         | 0.39%   |
| 18      | 8         | 0.39%   |
| 42      | 6         | 0.29%   |
| 39      | 6         | 0.29%   |
| 35      | 6         | 0.29%   |
| 37      | 5         | 0.24%   |
| 29      | 5         | 0.24%   |
| 10      | 5         | 0.24%   |
| 50      | 4         | 0.19%   |
| 48      | 4         | 0.19%   |
| 49      | 3         | 0.15%   |
| 46      | 3         | 0.15%   |
| 33      | 3         | 0.15%   |
| 55      | 2         | 0.1%    |
| 47      | 2         | 0.1%    |
| 40      | 2         | 0.1%    |
| 26      | 2         | 0.1%    |
| 7       | 2         | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 642       | 31.99%  |
| 501-600        | 516       | 25.71%  |
| 201-300        | 214       | 10.66%  |
| Unknown        | 141       | 7.03%   |
| 401-500        | 134       | 6.68%   |
| 351-400        | 110       | 5.48%   |
| 601-700        | 70        | 3.49%   |
| 701-800        | 69        | 3.44%   |
| 1501-2000      | 42        | 2.09%   |
| 1001-1500      | 38        | 1.89%   |
| 801-900        | 18        | 0.9%    |
| 901-1000       | 9         | 0.45%   |
| 1-100          | 2         | 0.1%    |
| More than 2000 | 1         | 0.05%   |
| 101-200        | 1         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1295      | 70.23%  |
| 16/10   | 268       | 14.53%  |
| Unknown | 128       | 6.94%   |
| 21/9    | 59        | 3.2%    |
| 5/4     | 48        | 2.6%    |
| 3/2     | 19        | 1.03%   |
| 4/3     | 14        | 0.76%   |
| 32/9    | 5         | 0.27%   |
| 0.62    | 3         | 0.16%   |
| 0.67    | 2         | 0.11%   |
| 3.40    | 1         | 0.05%   |
| 1.00    | 1         | 0.05%   |
| 0.45    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 373       | 18.5%   |
| 201-250        | 336       | 16.67%  |
| 81-90          | 275       | 13.64%  |
| 301-350        | 221       | 10.96%  |
| Unknown        | 141       | 6.99%   |
| 351-500        | 123       | 6.1%    |
| 71-80          | 110       | 5.46%   |
| 251-300        | 84        | 4.17%   |
| More than 1000 | 72        | 3.57%   |
| 151-200        | 63        | 3.13%   |
| 121-130        | 60        | 2.98%   |
| 61-70          | 51        | 2.53%   |
| 501-1000       | 30        | 1.49%   |
| 51-60          | 26        | 1.29%   |
| 141-150        | 17        | 0.84%   |
| 111-120        | 11        | 0.55%   |
| 131-140        | 10        | 0.5%    |
| 41-50          | 6         | 0.3%    |
| 91-100         | 5         | 0.25%   |
| 1-40           | 2         | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 626       | 31.94%  |
| 121-160       | 501       | 25.56%  |
| 101-120       | 416       | 21.22%  |
| 161-240       | 153       | 7.81%   |
| Unknown       | 141       | 7.19%   |
| More than 240 | 73        | 3.72%   |
| 1-50          | 50        | 2.55%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1386      | 74%     |
| 2     | 347       | 18.53%  |
| 0     | 97        | 5.18%   |
| 3     | 38        | 2.03%   |
| 4     | 5         | 0.27%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 1030      | 38.99%  |
| Realtek Semiconductor                  | 790       | 29.9%   |
| Qualcomm Atheros                       | 260       | 9.84%   |
| Broadcom                               | 160       | 6.06%   |
| Broadcom Limited                       | 42        | 1.59%   |
| MediaTek                               | 33        | 1.25%   |
| Marvell Technology Group               | 29        | 1.1%    |
| Ralink                                 | 21        | 0.79%   |
| Hewlett-Packard                        | 17        | 0.64%   |
| ASIX Electronics                       | 17        | 0.64%   |
| Nvidia                                 | 15        | 0.57%   |
| Microsoft                              | 14        | 0.53%   |
| D-Link System                          | 14        | 0.53%   |
| ASUSTek Computer                       | 14        | 0.53%   |
| NetGear                                | 13        | 0.49%   |
| Lenovo                                 | 13        | 0.49%   |
| Dell                                   | 13        | 0.49%   |
| TP-Link                                | 11        | 0.42%   |
| D-Link                                 | 11        | 0.42%   |
| Sierra Wireless                        | 10        | 0.38%   |
| Ralink Technology                      | 10        | 0.38%   |
| Huawei Technologies                    | 9         | 0.34%   |
| DisplayLink                            | 9         | 0.34%   |
| Ericsson Business Mobile Networks      | 6         | 0.23%   |
| Qualcomm Atheros Communications        | 5         | 0.19%   |
| Qualcomm                               | 5         | 0.19%   |
| Fibocom                                | 5         | 0.19%   |
| Samsung Electronics                    | 4         | 0.15%   |
| Aquantia                               | 4         | 0.15%   |
| Silicon Integrated Systems [SiS]       | 3         | 0.11%   |
| Microchip Technology                   | 3         | 0.11%   |
| Linksys                                | 3         | 0.11%   |
| Belkin Components                      | 3         | 0.11%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.08%   |
| Wacom                                  | 2         | 0.08%   |
| Texas Instruments                      | 2         | 0.08%   |
| Standard Microsystems                  | 2         | 0.08%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.08%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.08%   |
| JMicron Technology                     | 2         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 560       | 17.73%  |
| Intel I211 Gigabit Network Connection                             | 93        | 2.94%   |
| Intel Wi-Fi 6 AX200                                               | 87        | 2.75%   |
| Intel Wireless 8265 / 8275                                        | 83        | 2.63%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 63        | 1.99%   |
| Intel Wireless 7260                                               | 63        | 1.99%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 62        | 1.96%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 51        | 1.61%   |
| Intel Wireless 8260                                               | 48        | 1.52%   |
| Intel Wireless 7265                                               | 47        | 1.49%   |
| Intel Ethernet Connection (2) I219-V                              | 46        | 1.46%   |
| Intel Wi-Fi 6 AX201                                               | 41        | 1.3%    |
| Realtek RTL8125 2.5GbE Controller                                 | 37        | 1.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 36        | 1.14%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 34        | 1.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 32        | 1.01%   |
| Intel Ethernet Connection I217-LM                                 | 32        | 1.01%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 30        | 0.95%   |
| Intel Ethernet Controller I225-V                                  | 28        | 0.89%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 26        | 0.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 26        | 0.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 25        | 0.79%   |
| Intel Ethernet Connection (7) I219-V                              | 25        | 0.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 24        | 0.76%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 23        | 0.73%   |
| Intel 82579V Gigabit Network Connection                           | 23        | 0.73%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 22        | 0.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 21        | 0.66%   |
| Intel Ethernet Connection (4) I219-V                              | 21        | 0.66%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 21        | 0.66%   |
| Intel Ethernet Connection I218-LM                                 | 20        | 0.63%   |
| Intel Ethernet Connection (4) I219-LM                             | 20        | 0.63%   |
| Intel Ethernet Connection (3) I218-LM                             | 20        | 0.63%   |
| Intel Ethernet Connection (2) I218-V                              | 19        | 0.6%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 19        | 0.6%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 18        | 0.57%   |
| Intel Ethernet Connection (6) I219-V                              | 18        | 0.57%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 18        | 0.57%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 17        | 0.54%   |
| Intel Wireless-AC 9260                                            | 17        | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 722       | 51.79%  |
| Qualcomm Atheros                | 198       | 14.2%   |
| Realtek Semiconductor           | 167       | 11.98%  |
| Broadcom                        | 103       | 7.39%   |
| MediaTek                        | 32        | 2.3%    |
| Broadcom Limited                | 24        | 1.72%   |
| Ralink                          | 21        | 1.51%   |
| ASUSTek Computer                | 14        | 1%      |
| NetGear                         | 13        | 0.93%   |
| Sierra Wireless                 | 10        | 0.72%   |
| Ralink Technology               | 10        | 0.72%   |
| D-Link System                   | 10        | 0.72%   |
| D-Link                          | 10        | 0.72%   |
| Microsoft                       | 9         | 0.65%   |
| TP-Link                         | 8         | 0.57%   |
| Dell                            | 7         | 0.5%    |
| Qualcomm Atheros Communications | 5         | 0.36%   |
| Marvell Technology Group        | 5         | 0.36%   |
| Fibocom                         | 5         | 0.36%   |
| Hewlett-Packard                 | 4         | 0.29%   |
| Qualcomm                        | 3         | 0.22%   |
| Belkin Components               | 3         | 0.22%   |
| Wacom                           | 2         | 0.14%   |
| Linksys                         | 2         | 0.14%   |
| Edimax Technology               | 2         | 0.14%   |
| Wilocity                        | 1         | 0.07%   |
| Sitecom Europe                  | 1         | 0.07%   |
| Micro Star International        | 1         | 0.07%   |
| IMC Networks                    | 1         | 0.07%   |
| Chu Yuen Enterprise             | 1         | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 87        | 6.21%   |
| Intel Wireless 8265 / 8275                                     | 83        | 5.92%   |
| Intel Wireless 7260                                            | 63        | 4.5%    |
| Intel Wireless 8260                                            | 48        | 3.43%   |
| Intel Wireless 7265                                            | 47        | 3.35%   |
| Intel Wi-Fi 6 AX201                                            | 41        | 2.93%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 36        | 2.57%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 34        | 2.43%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 32        | 2.28%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 30        | 2.14%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 26        | 1.86%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 26        | 1.86%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 25        | 1.78%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 24        | 1.71%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 23        | 1.64%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 22        | 1.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 21        | 1.5%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 21        | 1.5%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 19        | 1.36%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 18        | 1.28%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 18        | 1.28%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 17        | 1.21%   |
| Intel Wireless-AC 9260                                         | 17        | 1.21%   |
| Intel Wireless 3160                                            | 17        | 1.21%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 16        | 1.14%   |
| Intel Wireless 3165                                            | 16        | 1.14%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 16        | 1.14%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 16        | 1.14%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 15        | 1.07%   |
| Intel Centrino Advanced-N 6200                                 | 14        | 1%      |
| Intel Centrino Advanced-N 6235                                 | 13        | 0.93%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 12        | 0.86%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 11        | 0.79%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 11        | 0.79%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 11        | 0.79%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 10        | 0.71%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 10        | 0.71%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 10        | 0.71%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 10        | 0.71%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 9         | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 722       | 43.34%  |
| Intel                                  | 621       | 37.27%  |
| Qualcomm Atheros                       | 91        | 5.46%   |
| Broadcom                               | 78        | 4.68%   |
| Marvell Technology Group               | 24        | 1.44%   |
| Broadcom Limited                       | 19        | 1.14%   |
| ASIX Electronics                       | 17        | 1.02%   |
| Nvidia                                 | 15        | 0.9%    |
| Lenovo                                 | 12        | 0.72%   |
| DisplayLink                            | 9         | 0.54%   |
| Huawei Technologies                    | 7         | 0.42%   |
| Microsoft                              | 5         | 0.3%    |
| Hewlett-Packard                        | 5         | 0.3%    |
| Samsung Electronics                    | 4         | 0.24%   |
| D-Link System                          | 4         | 0.24%   |
| Aquantia                               | 4         | 0.24%   |
| TP-Link                                | 3         | 0.18%   |
| Microchip Technology                   | 3         | 0.18%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.12%   |
| Standard Microsystems                  | 2         | 0.12%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.12%   |
| Qualcomm                               | 2         | 0.12%   |
| JMicron Technology                     | 2         | 0.12%   |
| ICS Advent                             | 2         | 0.12%   |
| Xiaomi                                 | 1         | 0.06%   |
| VIA Technologies                       | 1         | 0.06%   |
| Unknown                                | 1         | 0.06%   |
| Sundance Technology Inc / IC Plus      | 1         | 0.06%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.06%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.06%   |
| Linksys                                | 1         | 0.06%   |
| Gemtek                                 | 1         | 0.06%   |
| D-Link                                 | 1         | 0.06%   |
| Apple                                  | 1         | 0.06%   |
| 3Com                                   | 1         | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 560       | 32.79%  |
| Intel I211 Gigabit Network Connection                             | 93        | 5.44%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 63        | 3.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 62        | 3.63%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 51        | 2.99%   |
| Intel Ethernet Connection (2) I219-V                              | 46        | 2.69%   |
| Realtek RTL8125 2.5GbE Controller                                 | 37        | 2.17%   |
| Intel Ethernet Connection I217-LM                                 | 32        | 1.87%   |
| Intel Ethernet Controller I225-V                                  | 28        | 1.64%   |
| Intel Ethernet Connection (7) I219-V                              | 25        | 1.46%   |
| Intel 82579V Gigabit Network Connection                           | 23        | 1.35%   |
| Intel Ethernet Connection (4) I219-V                              | 21        | 1.23%   |
| Intel Ethernet Connection I218-LM                                 | 20        | 1.17%   |
| Intel Ethernet Connection (4) I219-LM                             | 20        | 1.17%   |
| Intel Ethernet Connection (3) I218-LM                             | 20        | 1.17%   |
| Intel Ethernet Connection (2) I218-V                              | 19        | 1.11%   |
| Intel Ethernet Connection (6) I219-V                              | 18        | 1.05%   |
| Intel Ethernet Connection I219-LM                                 | 17        | 1%      |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 16        | 0.94%   |
| Intel I210 Gigabit Network Connection                             | 14        | 0.82%   |
| Intel Ethernet Connection I219-V                                  | 14        | 0.82%   |
| Intel Ethernet Connection I217-V                                  | 14        | 0.82%   |
| Intel 82577LM Gigabit Network Connection                          | 14        | 0.82%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 14        | 0.82%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 13        | 0.76%   |
| ASIX AX88179 Gigabit Ethernet                                     | 12        | 0.7%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 11        | 0.64%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 11        | 0.64%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 11        | 0.64%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 11        | 0.64%   |
| Intel Ethernet Connection (6) I219-LM                             | 10        | 0.59%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 9         | 0.53%   |
| Intel Ethernet Connection (7) I219-LM                             | 9         | 0.53%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 8         | 0.47%   |
| Intel Ethernet Connection (5) I219-LM                             | 8         | 0.47%   |
| Intel Ethernet Connection (2) I219-LM                             | 8         | 0.47%   |
| Intel 82566MM Gigabit Network Connection                          | 8         | 0.47%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 7         | 0.41%   |
| Intel Ethernet Connection (10) I219-V                             | 7         | 0.41%   |
| DisplayLink Dell Universal Dock D6000                             | 7         | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1578      | 53.58%  |
| WiFi     | 1318      | 44.75%  |
| Modem    | 40        | 1.36%   |
| Unknown  | 9         | 0.31%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 987       | 52%     |
| Ethernet | 909       | 47.89%  |
| Unknown  | 2         | 0.11%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 943       | 51.47%  |
| 1     | 783       | 42.74%  |
| 3     | 49        | 2.67%   |
| 0     | 40        | 2.18%   |
| 4     | 10        | 0.55%   |
| 5     | 5         | 0.27%   |
| 9     | 1         | 0.05%   |
| 6     | 1         | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1769      | 96.35%  |
| Yes  | 67        | 3.65%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 583       | 52.29%  |
| Realtek Semiconductor           | 74        | 6.64%   |
| Qualcomm Atheros Communications | 64        | 5.74%   |
| ASUSTek Computer                | 56        | 5.02%   |
| Cambridge Silicon Radio         | 54        | 4.84%   |
| Apple                           | 53        | 4.75%   |
| IMC Networks                    | 51        | 4.57%   |
| Broadcom                        | 46        | 4.13%   |
| Foxconn / Hon Hai               | 37        | 3.32%   |
| Lite-On Technology              | 29        | 2.6%    |
| Hewlett-Packard                 | 16        | 1.43%   |
| Dell                            | 16        | 1.43%   |
| Ralink                          | 7         | 0.63%   |
| Marvell Semiconductor           | 5         | 0.45%   |
| Toshiba                         | 4         | 0.36%   |
| MediaTek                        | 4         | 0.36%   |
| Realtek                         | 3         | 0.27%   |
| Ralink Technology               | 2         | 0.18%   |
| Micro Star International        | 2         | 0.18%   |
| HTC (High Tech Computer)        | 2         | 0.18%   |
| Chicony Electronics             | 2         | 0.18%   |
| USI                             | 1         | 0.09%   |
| Fujitsu                         | 1         | 0.09%   |
| Creative Technology             | 1         | 0.09%   |
| Alps Electric                   | 1         | 0.09%   |
| Unknown                         | 1         | 0.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 258       | 23.04%  |
| Intel AX201 Bluetooth                               | 96        | 8.57%   |
| Intel AX200 Bluetooth                               | 83        | 7.41%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 59        | 5.27%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 54        | 4.82%   |
| Realtek Bluetooth Radio                             | 50        | 4.46%   |
| Apple Bluetooth Host Controller                     | 27        | 2.41%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 26        | 2.32%   |
| IMC Networks Bluetooth Radio                        | 22        | 1.96%   |
| Intel Wireless-AC 3168 Bluetooth                    | 21        | 1.88%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 21        | 1.88%   |
| Foxconn / Hon Hai Bluetooth Device                  | 19        | 1.7%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 18        | 1.61%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 16        | 1.43%   |
| Intel AX210 Bluetooth                               | 16        | 1.43%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 15        | 1.34%   |
| Qualcomm Atheros  Bluetooth Device                  | 14        | 1.25%   |
| Realtek  Bluetooth 4.2 Adapter                      | 13        | 1.16%   |
| IMC Networks Bluetooth Device                       | 12        | 1.07%   |
| Broadcom BCM2045B (BDC-2.1)                         | 12        | 1.07%   |
| Apple Bluetooth USB Host Controller                 | 12        | 1.07%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 11        | 0.98%   |
| Intel Bluetooth Device                              | 11        | 0.98%   |
| Foxconn / Hon Hai Wireless_Device                   | 10        | 0.89%   |
| Lite-On Bluetooth Device                            | 9         | 0.8%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 9         | 0.8%    |
| IMC Networks Wireless_Device                        | 8         | 0.71%   |
| HP Broadcom 2070 Bluetooth Combo                    | 8         | 0.71%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 8         | 0.71%   |
| Ralink RT3290 Bluetooth                             | 7         | 0.63%   |
| ASUS ASUS USB-BT500                                 | 7         | 0.63%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 6         | 0.54%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 6         | 0.54%   |
| Lite-On Atheros AR3012 Bluetooth                    | 6         | 0.54%   |
| Broadcom HP Portable SoftSailing                    | 6         | 0.54%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 6         | 0.54%   |
| ASUS Bluetooth Radio                                | 6         | 0.54%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 5         | 0.45%   |
| Dell DW375 Bluetooth Module                         | 5         | 0.45%   |
| Realtek RTL8723B Bluetooth                          | 4         | 0.36%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1269      | 46.72%  |
| AMD                                  | 553       | 20.36%  |
| Nvidia                               | 503       | 18.52%  |
| C-Media Electronics                  | 50        | 1.84%   |
| Logitech                             | 34        | 1.25%   |
| Kingston Technology                  | 18        | 0.66%   |
| Creative Labs                        | 16        | 0.59%   |
| Realtek Semiconductor                | 15        | 0.55%   |
| Plantronics                          | 15        | 0.55%   |
| SteelSeries ApS                      | 14        | 0.52%   |
| Texas Instruments                    | 13        | 0.48%   |
| Focusrite-Novation                   | 12        | 0.44%   |
| Creative Technology                  | 12        | 0.44%   |
| Lenovo                               | 11        | 0.41%   |
| GN Netcom                            | 11        | 0.41%   |
| Razer USA                            | 9         | 0.33%   |
| Corsair                              | 9         | 0.33%   |
| ASUSTek Computer                     | 8         | 0.29%   |
| SAVITECH                             | 7         | 0.26%   |
| RODE Microphones                     | 7         | 0.26%   |
| Micro Star International             | 6         | 0.22%   |
| GYROCOM C&C                          | 6         | 0.22%   |
| JMTek                                | 5         | 0.18%   |
| Yamaha                               | 4         | 0.15%   |
| Sennheiser Communications            | 4         | 0.15%   |
| Hewlett-Packard                      | 4         | 0.15%   |
| Blue Microphones                     | 4         | 0.15%   |
| Antlion Audio                        | 4         | 0.15%   |
| XMOS                                 | 3         | 0.11%   |
| VIA Technologies                     | 3         | 0.11%   |
| Sony                                 | 3         | 0.11%   |
| Silicon Integrated Systems [SiS]     | 3         | 0.11%   |
| Samson Technologies                  | 3         | 0.11%   |
| PreSonus Audio Electronics           | 3         | 0.11%   |
| Generalplus Technology               | 3         | 0.11%   |
| Apple                                | 3         | 0.11%   |
| Valve Software                       | 2         | 0.07%   |
| Trust                                | 2         | 0.07%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.07%   |
| Schiit Audio                         | 2         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 148       | 4.64%   |
| AMD Family 17h/19h HD Audio Controller                                     | 137       | 4.29%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 115       | 3.6%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 111       | 3.48%   |
| AMD Starship/Matisse HD Audio Controller                                   | 103       | 3.23%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 96        | 3.01%   |
| Intel Cannon Lake PCH cAVS                                                 | 78        | 2.44%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 74        | 2.32%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 72        | 2.26%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 64        | 2.01%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 58        | 1.82%   |
| Intel Haswell-ULT HD Audio Controller                                      | 56        | 1.75%   |
| Intel 8 Series HD Audio Controller                                         | 56        | 1.75%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 55        | 1.72%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 52        | 1.63%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 50        | 1.57%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 47        | 1.47%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 46        | 1.44%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 45        | 1.41%   |
| Intel Broadwell-U Audio Controller                                         | 45        | 1.41%   |
| Intel 200 Series PCH HD Audio                                              | 45        | 1.41%   |
| AMD FCH Azalia Controller                                                  | 44        | 1.38%   |
| Nvidia GP106 High Definition Audio Controller                              | 41        | 1.28%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 41        | 1.28%   |
| Nvidia GP104 High Definition Audio Controller                              | 38        | 1.19%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 36        | 1.13%   |
| Nvidia TU106 High Definition Audio Controller                              | 34        | 1.07%   |
| Nvidia GP107GL High Definition Audio Controller                            | 31        | 0.97%   |
| Intel Comet Lake PCH-LP cAVS                                               | 28        | 0.88%   |
| Intel CM238 HD Audio Controller                                            | 28        | 0.88%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 27        | 0.85%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 27        | 0.85%   |
| Nvidia GM204 High Definition Audio Controller                              | 26        | 0.81%   |
| Nvidia GF108 High Definition Audio Controller                              | 26        | 0.81%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 26        | 0.81%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 25        | 0.78%   |
| Nvidia GK107 HDMI Audio Controller                                         | 24        | 0.75%   |
| Intel Comet Lake PCH cAVS                                                  | 24        | 0.75%   |
| AMD Navi 10 HDMI Audio                                                     | 24        | 0.75%   |
| Nvidia High Definition Audio Controller                                    | 23        | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 234       | 22.05%  |
| SK hynix                     | 182       | 17.15%  |
| Corsair                      | 146       | 13.76%  |
| Kingston                     | 132       | 12.44%  |
| Micron Technology            | 113       | 10.65%  |
| Unknown                      | 84        | 7.92%   |
| Crucial                      | 54        | 5.09%   |
| G.Skill                      | 30        | 2.83%   |
| Ramaxel Technology           | 13        | 1.23%   |
| Elpida                       | 12        | 1.13%   |
| A-DATA Technology            | 10        | 0.94%   |
| Unknown (ABCD)               | 9         | 0.85%   |
| Nanya Technology             | 7         | 0.66%   |
| Unknown                      | 6         | 0.57%   |
| Team                         | 3         | 0.28%   |
| Patriot                      | 3         | 0.28%   |
| Transcend                    | 2         | 0.19%   |
| Qimonda                      | 2         | 0.19%   |
| GSkill                       | 2         | 0.19%   |
| G-Alantic                    | 2         | 0.19%   |
| Avant                        | 2         | 0.19%   |
| Unknown (AB)                 | 1         | 0.09%   |
| Unknown (836D)               | 1         | 0.09%   |
| Unifosa                      | 1         | 0.09%   |
| TEXTORM                      | 1         | 0.09%   |
| SHARETRONIC                  | 1         | 0.09%   |
| Patriot Memory (PDP Systems) | 1         | 0.09%   |
| Netlist                      | 1         | 0.09%   |
| Hewlett-Packard              | 1         | 0.09%   |
| GOODRAM                      | 1         | 0.09%   |
| fef5                         | 1         | 0.09%   |
| ASint Technology             | 1         | 0.09%   |
| Apacer                       | 1         | 0.09%   |
| Ankowall                     | 1         | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 22        | 1.93%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 12        | 1.05%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 11        | 0.97%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s            | 11        | 0.97%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 8         | 0.7%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 0.7%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 8         | 0.7%    |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 8         | 0.7%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 7         | 0.62%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 0.62%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 6         | 0.53%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 6         | 0.53%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 6         | 0.53%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 0.53%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 6         | 0.53%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 6         | 0.53%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 6         | 0.53%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.53%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 6         | 0.53%   |
| Unknown                                                          | 6         | 0.53%   |
| Unknown (ABCD) RAM 123456789012345678 1GB DIMM DDR3 2400MT/s     | 5         | 0.44%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.44%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 5         | 0.44%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 5         | 0.44%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 5         | 0.44%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 5         | 0.44%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s              | 5         | 0.44%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 5         | 0.44%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s            | 5         | 0.44%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 4         | 0.35%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 4         | 0.35%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 4         | 0.35%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 4         | 0.35%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 4         | 0.35%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 4         | 0.35%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s                  | 4         | 0.35%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 4         | 0.35%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.35%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 4         | 0.35%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 4         | 0.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 461       | 48.48%  |
| DDR3    | 307       | 32.28%  |
| LPDDR4  | 52        | 5.47%   |
| DDR2    | 36        | 3.79%   |
| LPDDR3  | 33        | 3.47%   |
| SDRAM   | 23        | 2.42%   |
| Unknown | 16        | 1.68%   |
| DDR5    | 9         | 0.95%   |
| DDR     | 8         | 0.84%   |
| LPDDR5  | 3         | 0.32%   |
| DRAM    | 3         | 0.32%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 499       | 52.47%  |
| DIMM         | 359       | 37.75%  |
| Row Of Chips | 77        | 8.1%    |
| Chip         | 11        | 1.16%   |
| Unknown      | 4         | 0.42%   |
| FB-DIMM      | 1         | 0.11%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 8192    | 399       | 39.16%  |
| 4096    | 245       | 24.04%  |
| 16384   | 183       | 17.96%  |
| 2048    | 130       | 12.76%  |
| 1024    | 29        | 2.85%   |
| 32768   | 27        | 2.65%   |
| 512     | 5         | 0.49%   |
| Unknown | 1         | 0.1%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 199       | 19.55%  |
| 3200    | 125       | 12.28%  |
| 2667    | 120       | 11.79%  |
| 2400    | 77        | 7.56%   |
| 2133    | 73        | 7.17%   |
| 3600    | 53        | 5.21%   |
| 1333    | 53        | 5.21%   |
| 4267    | 26        | 2.55%   |
| 667     | 25        | 2.46%   |
| 1867    | 24        | 2.36%   |
| 1334    | 24        | 2.36%   |
| Unknown | 18        | 1.77%   |
| 800     | 17        | 1.67%   |
| 3466    | 16        | 1.57%   |
| 3400    | 12        | 1.18%   |
| 1067    | 12        | 1.18%   |
| 3000    | 11        | 1.08%   |
| 4266    | 10        | 0.98%   |
| 3266    | 10        | 0.98%   |
| 1066    | 9         | 0.88%   |
| 4800    | 8         | 0.79%   |
| 2666    | 8         | 0.79%   |
| 3733    | 7         | 0.69%   |
| 1800    | 7         | 0.69%   |
| 4199    | 6         | 0.59%   |
| 2933    | 6         | 0.59%   |
| 1866    | 6         | 0.59%   |
| 6400    | 4         | 0.39%   |
| 3866    | 4         | 0.39%   |
| 3800    | 4         | 0.39%   |
| 2747    | 4         | 0.39%   |
| 8400    | 3         | 0.29%   |
| 49926   | 2         | 0.2%    |
| 3151    | 2         | 0.2%    |
| 3100    | 2         | 0.2%    |
| 2800    | 2         | 0.2%    |
| 2600    | 2         | 0.2%    |
| 2048    | 2         | 0.2%    |
| 2000    | 2         | 0.2%    |
| 975     | 2         | 0.2%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 12        | 40%     |
| Brother Industries    | 6         | 20%     |
| Samsung Electronics   | 5         | 16.67%  |
| Canon                 | 3         | 10%     |
| Seiko Epson           | 2         | 6.67%   |
| Oki Data              | 1         | 3.33%   |
| Lexmark International | 1         | 3.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung ML-216x Series Laser Printer | 2         | 6.67%   |
| HP LaserJet 1020                     | 2         | 6.67%   |
| Seiko Epson XP-4100 Series           | 1         | 3.33%   |
| Seiko Epson Printer                  | 1         | 3.33%   |
| Samsung SCX-3200 Series              | 1         | 3.33%   |
| Samsung M2070 Series                 | 1         | 3.33%   |
| Samsung Color Laser Printer          | 1         | 3.33%   |
| Oki Data USB Device                  | 1         | 3.33%   |
| Lexmark International MX317dn        | 1         | 3.33%   |
| HP OfficeJet Pro 8730                | 1         | 3.33%   |
| HP OfficeJet G55                     | 1         | 3.33%   |
| HP LaserJet P2035                    | 1         | 3.33%   |
| HP LaserJet 1320                     | 1         | 3.33%   |
| HP ENVY 4520 series                  | 1         | 3.33%   |
| HP DeskJet 5650c                     | 1         | 3.33%   |
| HP Deskjet 3050 J610 series          | 1         | 3.33%   |
| HP DeskJet 2700 series               | 1         | 3.33%   |
| HP DeskJet 2130 series               | 1         | 3.33%   |
| HP Color LaserJet CP1215             | 1         | 3.33%   |
| Canon LBP7010C/7018C                 | 1         | 3.33%   |
| Canon LBP6200                        | 1         | 3.33%   |
| Canon CanoScan LiDE 300              | 1         | 3.33%   |
| Brother QL-500 label printer         | 1         | 3.33%   |
| Brother HL-5150D series              | 1         | 3.33%   |
| Brother HL-2270DW Laser Printer      | 1         | 3.33%   |
| Brother HL-2130 series               | 1         | 3.33%   |
| Brother DCP-7055W                    | 1         | 3.33%   |
| Brother DCP-7040                     | 1         | 3.33%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 6         | 85.71%  |
| Hewlett-Packard | 1         | 14.29%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| HP ScanJet 2200c                       | 1         | 14.29%  |
| Canon CanoScan LiDE 700F               | 1         | 14.29%  |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40 | 1         | 14.29%  |
| Canon CanoScan LiDE 210                | 1         | 14.29%  |
| Canon CanoScan LiDE 120                | 1         | 14.29%  |
| Canon CanoScan LiDE 110                | 1         | 14.29%  |
| Canon CanoScan LiDE 100                | 1         | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 228       | 22.55%  |
| Microdia                               | 97        | 9.59%   |
| IMC Networks                           | 86        | 8.51%   |
| Logitech                               | 83        | 8.21%   |
| Acer                                   | 75        | 7.42%   |
| Realtek Semiconductor                  | 64        | 6.33%   |
| Sunplus Innovation Technology          | 46        | 4.55%   |
| Apple                                  | 41        | 4.06%   |
| Cheng Uei Precision Industry (Foxlink) | 39        | 3.86%   |
| Quanta                                 | 34        | 3.36%   |
| Lite-On Technology                     | 33        | 3.26%   |
| Syntek                                 | 27        | 2.67%   |
| Suyin                                  | 25        | 2.47%   |
| Samsung Electronics                    | 13        | 1.29%   |
| Luxvisions Innotech Limited            | 11        | 1.09%   |
| Ricoh                                  | 10        | 0.99%   |
| Microsoft                              | 10        | 0.99%   |
| Lenovo                                 | 9         | 0.89%   |
| Alcor Micro                            | 8         | 0.79%   |
| Silicon Motion                         | 7         | 0.69%   |
| ALi                                    | 6         | 0.59%   |
| Z-Star Microelectronics                | 5         | 0.49%   |
| Creative Technology                    | 5         | 0.49%   |
| Primax Electronics                     | 4         | 0.4%    |
| Trust                                  | 3         | 0.3%    |
| Shenzhen Kingcome Optoelectronic       | 3         | 0.3%    |
| Generalplus Technology                 | 3         | 0.3%    |
| DigiTech                               | 3         | 0.3%    |
| ARC International                      | 3         | 0.3%    |
| Sunplus Technology                     | 2         | 0.2%    |
| LG Electronics                         | 2         | 0.2%    |
| Importek                               | 2         | 0.2%    |
| webcam                                 | 1         | 0.1%    |
| Valve Software                         | 1         | 0.1%    |
| Tobii Technology AB                    | 1         | 0.1%    |
| SunplusIT                              | 1         | 0.1%    |
| Sony Ericsson Mobile Communications AB | 1         | 0.1%    |
| Sony                                   | 1         | 0.1%    |
| Sonix Technology                       | 1         | 0.1%    |
| Polycom                                | 1         | 0.1%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                | 53        | 5.18%   |
| Microdia Integrated_Webcam_HD                                            | 44        | 4.3%    |
| IMC Networks USB2.0 HD UVC WebCam                                        | 33        | 3.22%   |
| IMC Networks Integrated Camera                                           | 26        | 2.54%   |
| Realtek Integrated_Webcam_HD                                             | 24        | 2.34%   |
| Acer Integrated Camera                                                   | 22        | 2.15%   |
| Syntek Integrated Camera                                                 | 20        | 1.95%   |
| Chicony HD WebCam                                                        | 19        | 1.86%   |
| Logitech Webcam C270                                                     | 16        | 1.56%   |
| Chicony HP HD Camera                                                     | 16        | 1.56%   |
| Logitech HD Pro Webcam C920                                              | 15        | 1.46%   |
| Samsung Galaxy A5 (MTP)                                                  | 13        | 1.27%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                          | 13        | 1.27%   |
| Acer Lenovo EasyCamera                                                   | 13        | 1.27%   |
| Logitech C922 Pro Stream Webcam                                          | 12        | 1.17%   |
| Lite-On HP HD Camera                                                     | 12        | 1.17%   |
| Sunplus HD WebCam                                                        | 11        | 1.07%   |
| Sunplus Integrated_Webcam_HD                                             | 10        | 0.98%   |
| Quanta HP HD Camera                                                      | 10        | 0.98%   |
| Apple Built-in iSight                                                    | 10        | 0.98%   |
| Microdia USB 2.0 Camera                                                  | 9         | 0.88%   |
| Lite-On Integrated Camera                                                | 9         | 0.88%   |
| Lite-On HP HD Webcam                                                     | 9         | 0.88%   |
| Chicony HP HD Webcam                                                     | 9         | 0.88%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                      | 9         | 0.88%   |
| Apple FaceTime HD Camera (Built-in)                                      | 9         | 0.88%   |
| Acer SunplusIT Integrated Camera                                         | 9         | 0.88%   |
| Acer EasyCamera                                                          | 9         | 0.88%   |
| Syntek Lenovo EasyCamera                                                 | 7         | 0.68%   |
| Realtek USB2.0 HD UVC WebCam                                             | 7         | 0.68%   |
| Quanta HD User Facing                                                    | 7         | 0.68%   |
| IMC Networks USB2.0 VGA UVC WebCam                                       | 7         | 0.68%   |
| Chicony HP Wide Vision HD Camera                                         | 7         | 0.68%   |
| Chicony HP Truevision HD                                                 | 7         | 0.68%   |
| Chicony HP HD Webcam [Fixed]                                             | 7         | 0.68%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 7         | 0.68%   |
| Apple FaceTime HD Camera                                                 | 7         | 0.68%   |
| Suyin HP TrueVision HD                                                   | 6         | 0.59%   |
| Chicony USB2.0 HD UVC WebCam                                             | 6         | 0.59%   |
| Chicony USB2.0 Camera                                                    | 6         | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 112       | 43.58%  |
| Synaptics                  | 73        | 28.4%   |
| Shenzhen Goodix Technology | 27        | 10.51%  |
| Elan Microelectronics      | 11        | 4.28%   |
| AuthenTec                  | 11        | 4.28%   |
| Upek                       | 10        | 3.89%   |
| LighTuning Technology      | 7         | 2.72%   |
| STMicroelectronics         | 6         | 2.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 39        | 15.18%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 15        | 5.84%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 14        | 5.45%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 13        | 5.06%   |
| Shenzhen Goodix FingerPrint                                                | 13        | 5.06%   |
| Validity Sensors VFS491                                                    | 10        | 3.89%   |
| Validity Sensors Synaptics WBDI                                            | 9         | 3.5%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 9         | 3.5%    |
| Shenzhen Goodix Fingerprint Reader                                         | 9         | 3.5%    |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 8         | 3.11%   |
| Elan ELAN:Fingerprint                                                      | 8         | 3.11%   |
| Synaptics WBDI                                                             | 7         | 2.72%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 7         | 2.72%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 2.33%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 6         | 2.33%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 2.33%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 5         | 1.95%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 1.95%   |
| Shenzhen Goodix  Fingerprint Device                                        | 5         | 1.95%   |
| AuthenTec AES2810                                                          | 5         | 1.95%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 1.95%   |
| Synaptics UWP WBDI                                                         | 4         | 1.56%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 4         | 1.56%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 1.17%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 1.17%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 1.17%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 1.17%   |
| Synaptics  WBDI                                                            | 3         | 1.17%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 1.17%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 0.78%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 0.78%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 2         | 0.78%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 0.78%   |
| Synaptics UWP WBDI Device                                                  | 2         | 0.78%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 0.78%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 0.78%   |
| Elan ELAN:ARM-M4                                                           | 2         | 0.78%   |
| Unknown                                                                    | 2         | 0.78%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.39%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.39%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 56        | 41.79%  |
| Alcor Micro                       | 53        | 39.55%  |
| O2 Micro                          | 10        | 7.46%   |
| Upek                              | 4         | 2.99%   |
| Lenovo                            | 4         | 2.99%   |
| Gemalto (was Gemplus)             | 2         | 1.49%   |
| Yubico.com                        | 1         | 0.75%   |
| VASCO Data Security International | 1         | 0.75%   |
| Hewlett-Packard                   | 1         | 0.75%   |
| Chicony Electronics               | 1         | 0.75%   |
| Cherry                            | 1         | 0.75%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 50        | 37.31%  |
| Broadcom BCM5880 Secure Applications Processor                               | 17        | 12.69%  |
| Broadcom 58200                                                               | 15        | 11.19%  |
| Broadcom 5880                                                                | 12        | 8.96%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 11        | 8.21%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 8         | 5.97%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 2.99%   |
| Lenovo Integrated Smart Card Reader                                          | 4         | 2.99%   |
| Alcor Micro Watchdata W 1981                                                 | 3         | 2.24%   |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 1.49%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 1.49%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.75%   |
| VASCO Data Security International DIGIPASS 920                               | 1         | 0.75%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.75%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.75%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.75%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.75%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1230      | 65.74%  |
| 1     | 491       | 26.24%  |
| 2     | 126       | 6.73%   |
| 3     | 17        | 0.91%   |
| 4     | 6         | 0.32%   |
| 7     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 255       | 32.04%  |
| Graphics card            | 144       | 18.09%  |
| Chipcard                 | 117       | 14.7%   |
| Net/wireless             | 70        | 8.79%   |
| Multimedia controller    | 51        | 6.41%   |
| Communication controller | 41        | 5.15%   |
| Camera                   | 25        | 3.14%   |
| Unassigned class         | 22        | 2.76%   |
| Bluetooth                | 20        | 2.51%   |
| Sound                    | 16        | 2.01%   |
| Card reader              | 11        | 1.38%   |
| Net/ethernet             | 7         | 0.88%   |
| Storage                  | 4         | 0.5%    |
| Storage/ata              | 2         | 0.25%   |
| Network                  | 2         | 0.25%   |
| Modem                    | 2         | 0.25%   |
| Flash memory             | 2         | 0.25%   |
| Storage/raid             | 1         | 0.13%   |
| Storage/nvme             | 1         | 0.13%   |
| Storage/ide              | 1         | 0.13%   |
| Firewire controller      | 1         | 0.13%   |
| Dvb card                 | 1         | 0.13%   |

