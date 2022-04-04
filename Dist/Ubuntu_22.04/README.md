Ubuntu 22.04 - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for Ubuntu 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Ubuntu_22.04/Desktop/README.md) and [notebooks](/Dist/Ubuntu_22.04/Notebook/README.md).

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

Total: 138

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Packard Be... | IMEDIA S2110A               | Desktop     | [b8bf871708](https://linux-hardware.org/?probe=b8bf871708) | Apr 04, 2022 |
| BESSTAR Te... | ATB15                       | Server      | [b7c7776f50](https://linux-hardware.org/?probe=b7c7776f50) | Apr 04, 2022 |
| Lenovo        | ThinkPad E495 20NEA00QUS    | Notebook    | [d9cbb34331](https://linux-hardware.org/?probe=d9cbb34331) | Apr 04, 2022 |
| Lenovo        | ThinkPad E495 20NEA00QUS    | Notebook    | [062e604ef0](https://linux-hardware.org/?probe=062e604ef0) | Apr 04, 2022 |
| Gigabyte      | B365 M AORUS ELITE-CF       | Desktop     | [7da8a936ea](https://linux-hardware.org/?probe=7da8a936ea) | Apr 04, 2022 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [99a152f9c7](https://linux-hardware.org/?probe=99a152f9c7) | Apr 04, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | Notebook    | [43ff476479](https://linux-hardware.org/?probe=43ff476479) | Apr 03, 2022 |
| Samsung       | R580/R590                   | Notebook    | [0b95325a5e](https://linux-hardware.org/?probe=0b95325a5e) | Apr 03, 2022 |
| Gigabyte      | Z690 UD AX                  | Desktop     | [a052a5e936](https://linux-hardware.org/?probe=a052a5e936) | Apr 03, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [bdb683ff40](https://linux-hardware.org/?probe=bdb683ff40) | Apr 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [ec51dcaf0a](https://linux-hardware.org/?probe=ec51dcaf0a) | Apr 03, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [ad5d38e378](https://linux-hardware.org/?probe=ad5d38e378) | Apr 02, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [e380073189](https://linux-hardware.org/?probe=e380073189) | Apr 02, 2022 |
| HP            | Pavilion Laptop 14-ce2xx... | Notebook    | [d103b2cb25](https://linux-hardware.org/?probe=d103b2cb25) | Apr 02, 2022 |
| MSI           | MAG B660M MORTAR DDR4       | Desktop     | [a9f2820894](https://linux-hardware.org/?probe=a9f2820894) | Apr 02, 2022 |
| Dell          | 07PR60 A00                  | Desktop     | [40f34fbc8f](https://linux-hardware.org/?probe=40f34fbc8f) | Apr 01, 2022 |
| Intel         | S2600CP G50768-505          | Server      | [cdfba65630](https://linux-hardware.org/?probe=cdfba65630) | Apr 01, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [eba4514371](https://linux-hardware.org/?probe=eba4514371) | Apr 01, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [a799c6c916](https://linux-hardware.org/?probe=a799c6c916) | Apr 01, 2022 |
| TrekStor      | Primetab S11B               | Tablet      | [c98cdfd7c7](https://linux-hardware.org/?probe=c98cdfd7c7) | Apr 01, 2022 |
| Fujitsu       | D3223-C1 S26361-D3223-C1    | Desktop     | [f0fdc95810](https://linux-hardware.org/?probe=f0fdc95810) | Apr 01, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [606eb17f56](https://linux-hardware.org/?probe=606eb17f56) | Apr 01, 2022 |
| HP            | ProLiant ML110 G7           | Desktop     | [9e1e2b2ae7](https://linux-hardware.org/?probe=9e1e2b2ae7) | Apr 01, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [6b0cd44dbb](https://linux-hardware.org/?probe=6b0cd44dbb) | Apr 01, 2022 |
| Alienware     | M11x                        | Notebook    | [f83c01bb34](https://linux-hardware.org/?probe=f83c01bb34) | Apr 01, 2022 |
| Avell High... | A70 MOB                     | Notebook    | [9e095642f0](https://linux-hardware.org/?probe=9e095642f0) | Apr 01, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [a14dde61dc](https://linux-hardware.org/?probe=a14dde61dc) | Apr 01, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [858142c2ab](https://linux-hardware.org/?probe=858142c2ab) | Apr 01, 2022 |
| MSI           | X370 GAMING PRO CARBON A... | Desktop     | [ce2e9f743d](https://linux-hardware.org/?probe=ce2e9f743d) | Mar 31, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [ceee79344c](https://linux-hardware.org/?probe=ceee79344c) | Mar 31, 2022 |
| Dell          | 0YNVJG A01                  | Desktop     | [4ccce61117](https://linux-hardware.org/?probe=4ccce61117) | Mar 30, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [83b60423e1](https://linux-hardware.org/?probe=83b60423e1) | Mar 30, 2022 |
| HP            | 250 G4                      | Notebook    | [69a3535c1a](https://linux-hardware.org/?probe=69a3535c1a) | Mar 30, 2022 |
| Medion        | S4401 MD61533               | Convertible | [0017875c99](https://linux-hardware.org/?probe=0017875c99) | Mar 30, 2022 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [f21ef43d0f](https://linux-hardware.org/?probe=f21ef43d0f) | Mar 30, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [4626f2aeab](https://linux-hardware.org/?probe=4626f2aeab) | Mar 29, 2022 |
| MSI           | GP76 Leopard 11UG           | Notebook    | [93a6b587c2](https://linux-hardware.org/?probe=93a6b587c2) | Mar 29, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [30c09eec3b](https://linux-hardware.org/?probe=30c09eec3b) | Mar 28, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [dbdd71e8b8](https://linux-hardware.org/?probe=dbdd71e8b8) | Mar 28, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [ecf7b98552](https://linux-hardware.org/?probe=ecf7b98552) | Mar 28, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [0e93a8600c](https://linux-hardware.org/?probe=0e93a8600c) | Mar 27, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [e5b0f5c259](https://linux-hardware.org/?probe=e5b0f5c259) | Mar 27, 2022 |
| Le Cube 1     | Unknown                     | Desktop     | [a881cc0397](https://linux-hardware.org/?probe=a881cc0397) | Mar 26, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [64e505d8d7](https://linux-hardware.org/?probe=64e505d8d7) | Mar 26, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [01e83234d9](https://linux-hardware.org/?probe=01e83234d9) | Mar 26, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [4fb374e78b](https://linux-hardware.org/?probe=4fb374e78b) | Mar 25, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [f06216a521](https://linux-hardware.org/?probe=f06216a521) | Mar 24, 2022 |
| HP            | 1589                        | Desktop     | [8c1f30bb6f](https://linux-hardware.org/?probe=8c1f30bb6f) | Mar 23, 2022 |
| HP            | Pavilion x2 Detachable      | Notebook    | [a82a2739a8](https://linux-hardware.org/?probe=a82a2739a8) | Mar 22, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [b03762a80b](https://linux-hardware.org/?probe=b03762a80b) | Mar 22, 2022 |
| Framework     | Laptop                      | Notebook    | [b8fcafa943](https://linux-hardware.org/?probe=b8fcafa943) | Mar 20, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [3c0450f79e](https://linux-hardware.org/?probe=3c0450f79e) | Mar 12, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [1c22760a82](https://linux-hardware.org/?probe=1c22760a82) | Mar 12, 2022 |
| Shenzhen W... | AERO 2 Pro                  | Mini pc     | [264fcd47ff](https://linux-hardware.org/?probe=264fcd47ff) | Mar 12, 2022 |
| Shenzhen W... | AERO 2 Pro                  | Mini pc     | [91a4d09517](https://linux-hardware.org/?probe=91a4d09517) | Mar 12, 2022 |
| ASRock        | 970 Extreme3 R2.0           | Desktop     | [f417e6a6ef](https://linux-hardware.org/?probe=f417e6a6ef) | Mar 11, 2022 |
| MSI           | Creator Z16 A11UET          | Notebook    | [1804e5eb77](https://linux-hardware.org/?probe=1804e5eb77) | Mar 09, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [256dc440ec](https://linux-hardware.org/?probe=256dc440ec) | Mar 09, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [8a87e0ca46](https://linux-hardware.org/?probe=8a87e0ca46) | Mar 07, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZW... | Notebook    | [9fd12bdd29](https://linux-hardware.org/?probe=9fd12bdd29) | Mar 06, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [915ca09de4](https://linux-hardware.org/?probe=915ca09de4) | Mar 05, 2022 |
| MSI           | X370 GAMING PRO CARBON A... | Desktop     | [1fb25ad2c3](https://linux-hardware.org/?probe=1fb25ad2c3) | Mar 05, 2022 |
| Toshiba       | Satellite C70D-A            | Notebook    | [c7dfd52f76](https://linux-hardware.org/?probe=c7dfd52f76) | Mar 05, 2022 |
| HP            | ZBook 15 G5                 | Notebook    | [f86a14c16d](https://linux-hardware.org/?probe=f86a14c16d) | Mar 05, 2022 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [aa80ded615](https://linux-hardware.org/?probe=aa80ded615) | Mar 04, 2022 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [3e997c5618](https://linux-hardware.org/?probe=3e997c5618) | Mar 03, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZW... | Notebook    | [206f3a7c01](https://linux-hardware.org/?probe=206f3a7c01) | Mar 02, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [35ab38818d](https://linux-hardware.org/?probe=35ab38818d) | Feb 28, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [01dd9cefa7](https://linux-hardware.org/?probe=01dd9cefa7) | Feb 28, 2022 |
| HP            | Presario CQ42               | Notebook    | [de34294599](https://linux-hardware.org/?probe=de34294599) | Feb 27, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [18d37562a8](https://linux-hardware.org/?probe=18d37562a8) | Feb 26, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [d8af57f59a](https://linux-hardware.org/?probe=d8af57f59a) | Feb 26, 2022 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [7fe4a3390b](https://linux-hardware.org/?probe=7fe4a3390b) | Feb 25, 2022 |
| Timi          | TM1709                      | Notebook    | [16e699bea8](https://linux-hardware.org/?probe=16e699bea8) | Feb 25, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | Notebook    | [076c8f6e01](https://linux-hardware.org/?probe=076c8f6e01) | Feb 23, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | Notebook    | [85c09f63f0](https://linux-hardware.org/?probe=85c09f63f0) | Feb 23, 2022 |
| Gigabyte      | H61M-DS2 DVI                | Desktop     | [90c43679f7](https://linux-hardware.org/?probe=90c43679f7) | Feb 23, 2022 |
| Acer          | Aspire A517-52              | Notebook    | [52976ad94b](https://linux-hardware.org/?probe=52976ad94b) | Feb 23, 2022 |
| Lenovo        | ThinkPad X1 Yoga Gen 6 2... | Convertible | [973f8ebf5e](https://linux-hardware.org/?probe=973f8ebf5e) | Feb 17, 2022 |
| MSI           | Stealth GS66 12UHS          | Notebook    | [bb8ef51c23](https://linux-hardware.org/?probe=bb8ef51c23) | Feb 17, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TES... | Notebook    | [da103e44c5](https://linux-hardware.org/?probe=da103e44c5) | Feb 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [1055dc7082](https://linux-hardware.org/?probe=1055dc7082) | Feb 14, 2022 |
| HP            | 620                         | Notebook    | [bd89b469e4](https://linux-hardware.org/?probe=bd89b469e4) | Feb 14, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B3302FEA... | Convertible | [20d30ebe0b](https://linux-hardware.org/?probe=20d30ebe0b) | Feb 13, 2022 |
| MSI           | X370 GAMING PRO CARBON A... | Desktop     | [fa5ed1f68b](https://linux-hardware.org/?probe=fa5ed1f68b) | Feb 13, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | Desktop     | [e329340668](https://linux-hardware.org/?probe=e329340668) | Feb 11, 2022 |
| Dell          | 0YXT71 A03                  | Desktop     | [19227aa57d](https://linux-hardware.org/?probe=19227aa57d) | Feb 11, 2022 |
| HP            | 212B                        | Desktop     | [fab24340a5](https://linux-hardware.org/?probe=fab24340a5) | Feb 10, 2022 |
| HP            | Pavilion 15                 | Notebook    | [9246e37578](https://linux-hardware.org/?probe=9246e37578) | Feb 09, 2022 |
| ASUSTek       | K52Je                       | Notebook    | [e1010983cf](https://linux-hardware.org/?probe=e1010983cf) | Feb 09, 2022 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [878c4247cb](https://linux-hardware.org/?probe=878c4247cb) | Feb 09, 2022 |
| ASRockRack    | X470D4U2/1N1                | Desktop     | [735bc0f806](https://linux-hardware.org/?probe=735bc0f806) | Feb 04, 2022 |
| Dell          | Latitude 3330               | Notebook    | [c3b39f74b4](https://linux-hardware.org/?probe=c3b39f74b4) | Jan 31, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | Notebook    | [0a04b2d1b1](https://linux-hardware.org/?probe=0a04b2d1b1) | Jan 31, 2022 |
| HP            | 15                          | Notebook    | [81961b52a9](https://linux-hardware.org/?probe=81961b52a9) | Jan 29, 2022 |
| ASUSTek       | P5P41T/USB3                 | Desktop     | [f45dc3454a](https://linux-hardware.org/?probe=f45dc3454a) | Jan 25, 2022 |
| ASUSTek       | P5P41T/USB3                 | Desktop     | [b69dafbb2b](https://linux-hardware.org/?probe=b69dafbb2b) | Jan 25, 2022 |
| Unknown       | Unknown                     | Soc         | [f60622cca7](https://linux-hardware.org/?probe=f60622cca7) | Jan 23, 2022 |
| Unknown       | Unknown                     | Soc         | [fb25f8463c](https://linux-hardware.org/?probe=fb25f8463c) | Jan 23, 2022 |
| HP            | ProBook 445 G7              | Notebook    | [bceca55120](https://linux-hardware.org/?probe=bceca55120) | Jan 23, 2022 |
| ASUSTek       | P5P41T/USB3                 | Desktop     | [105593cece](https://linux-hardware.org/?probe=105593cece) | Jan 23, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [2de98fb4d8](https://linux-hardware.org/?probe=2de98fb4d8) | Jan 22, 2022 |
| HP            | ProBook 650 G5              | Notebook    | [111cb6822e](https://linux-hardware.org/?probe=111cb6822e) | Jan 21, 2022 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [e092fc4b26](https://linux-hardware.org/?probe=e092fc4b26) | Jan 20, 2022 |
| HP            | ZBook Power 15.6 inch G8... | Notebook    | [245123d0a8](https://linux-hardware.org/?probe=245123d0a8) | Jan 20, 2022 |
| Gigabyte      | GB-BSi7-1165G7              | Desktop     | [ab94ff1199](https://linux-hardware.org/?probe=ab94ff1199) | Jan 20, 2022 |
| Dell          | Latitude E6510              | Notebook    | [c0d3a6c31a](https://linux-hardware.org/?probe=c0d3a6c31a) | Jan 16, 2022 |
| MSI           | Z490-A PRO                  | Desktop     | [b2655bbd43](https://linux-hardware.org/?probe=b2655bbd43) | Jan 15, 2022 |
| Google        | Kefka                       | Notebook    | [e62fa3eea6](https://linux-hardware.org/?probe=e62fa3eea6) | Jan 10, 2022 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [034079628f](https://linux-hardware.org/?probe=034079628f) | Jan 07, 2022 |
| Lenovo        | ThinkPad T400 2768WGB       | Notebook    | [ac0e3dfe29](https://linux-hardware.org/?probe=ac0e3dfe29) | Jan 07, 2022 |
| MSI           | C236A WORKSTATION           | Desktop     | [97795d3ebc](https://linux-hardware.org/?probe=97795d3ebc) | Jan 07, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [666b0b18f5](https://linux-hardware.org/?probe=666b0b18f5) | Dec 30, 2021 |
| Intel         | H61                         | Desktop     | [e2b49aa759](https://linux-hardware.org/?probe=e2b49aa759) | Dec 30, 2021 |
| MSI           | GT73VR 6RE                  | Notebook    | [0f41e5dd07](https://linux-hardware.org/?probe=0f41e5dd07) | Dec 28, 2021 |
| Lenovo        | Legion 7 16ACHg6 82N6       | Notebook    | [be79b3cd82](https://linux-hardware.org/?probe=be79b3cd82) | Dec 26, 2021 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [ccc85b0783](https://linux-hardware.org/?probe=ccc85b0783) | Dec 13, 2021 |
| Lenovo        | 3141 NOK                    | Desktop     | [cc90d7c889](https://linux-hardware.org/?probe=cc90d7c889) | Dec 13, 2021 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [0db33a5b23](https://linux-hardware.org/?probe=0db33a5b23) | Dec 10, 2021 |
| MSI           | Modern 15 A11MU             | Notebook    | [34b31c53cd](https://linux-hardware.org/?probe=34b31c53cd) | Dec 07, 2021 |
| Toshiba       | PORTEGE Z10T-A              | Notebook    | [5257d76a92](https://linux-hardware.org/?probe=5257d76a92) | Dec 05, 2021 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [f219ee63ff](https://linux-hardware.org/?probe=f219ee63ff) | Nov 30, 2021 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [3199d159a4](https://linux-hardware.org/?probe=3199d159a4) | Nov 30, 2021 |
| Huanan        | X99 F8D V2.2                | Desktop     | [dcd5217827](https://linux-hardware.org/?probe=dcd5217827) | Nov 29, 2021 |
| Gigabyte      | M52L-S3                     | Desktop     | [16854f2502](https://linux-hardware.org/?probe=16854f2502) | Nov 29, 2021 |
| Gigabyte      | M52L-S3                     | Desktop     | [e6f3417028](https://linux-hardware.org/?probe=e6f3417028) | Nov 27, 2021 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [d191e3f97f](https://linux-hardware.org/?probe=d191e3f97f) | Nov 22, 2021 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [6381b11078](https://linux-hardware.org/?probe=6381b11078) | Nov 22, 2021 |
| Gigabyte      | EP31-DS3L                   | Desktop     | [c0134f6231](https://linux-hardware.org/?probe=c0134f6231) | Nov 11, 2021 |
| Gigabyte      | EP31-DS3L                   | Desktop     | [4d659bf7e4](https://linux-hardware.org/?probe=4d659bf7e4) | Nov 11, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [36e64b8256](https://linux-hardware.org/?probe=36e64b8256) | Nov 10, 2021 |
| ASUSTek       | X58L                        | Notebook    | [c3df58b13b](https://linux-hardware.org/?probe=c3df58b13b) | Nov 10, 2021 |
| ASUSTek       | X58L                        | Notebook    | [e1425f037e](https://linux-hardware.org/?probe=e1425f037e) | Nov 10, 2021 |
| ASUSTek       | X58L                        | Notebook    | [f64ba3a9e4](https://linux-hardware.org/?probe=f64ba3a9e4) | Nov 10, 2021 |
| Dell          | Inspiron 1464               | Notebook    | [26f50eb4a8](https://linux-hardware.org/?probe=26f50eb4a8) | Nov 06, 2021 |
| Dell          | Inspiron 11 - 3147          | Notebook    | [6b1a282c17](https://linux-hardware.org/?probe=6b1a282c17) | Nov 05, 2021 |
| Dell          | Inspiron 1464               | Notebook    | [4063779d5a](https://linux-hardware.org/?probe=4063779d5a) | Nov 01, 2021 |
| MSI           | MS-7235                     | Desktop     | [bbfa7fb897](https://linux-hardware.org/?probe=bbfa7fb897) | Oct 24, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                     | Computers | Percent |
|-----------------------------|-----------|---------|
| 5.15.0-23-generic           | 29        | 27.36%  |
| 5.15.0-18-generic           | 25        | 23.58%  |
| 5.13.0-19-generic           | 12        | 11.32%  |
| 5.15.0-22-generic           | 8         | 7.55%   |
| 5.15.0-17-generic           | 8         | 7.55%   |
| 5.17.0-051700-generic       | 2         | 1.89%   |
| 5.16.0-051600-generic       | 2         | 1.89%   |
| 5.15.0-25-generic           | 2         | 1.89%   |
| 5.17.1-051701-generic       | 1         | 0.94%   |
| 5.17.0-051700rc6-generic    | 1         | 0.94%   |
| 5.17.0-051700rc5-lowlatency | 1         | 0.94%   |
| 5.15.6-051506-generic       | 1         | 0.94%   |
| 5.15.17-xanmod2             | 1         | 0.94%   |
| 5.15.15-76051515-generic    | 1         | 0.94%   |
| 5.15.13-051513-generic      | 1         | 0.94%   |
| 5.15.12-051512-generic      | 1         | 0.94%   |
| 5.15.11-051511-generic      | 1         | 0.94%   |
| 5.15.10-051510-generic      | 1         | 0.94%   |
| 5.15.0-14-generic           | 1         | 0.94%   |
| 5.15.0-13-generic           | 1         | 0.94%   |
| 5.15.0-12-generic           | 1         | 0.94%   |
| 5.15.0-11-generic           | 1         | 0.94%   |
| 5.15.0-051500rc7-generic    | 1         | 0.94%   |
| 5.13.19                     | 1         | 0.94%   |
| 5.13.0-20-generic           | 1         | 0.94%   |
| 3.16.85-65                  | 1         | 0.94%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 74        | 71.84%  |
| 5.13.0  | 13        | 12.62%  |
| 5.17.0  | 4         | 3.88%   |
| 5.16.0  | 2         | 1.94%   |
| 5.17.1  | 1         | 0.97%   |
| 5.15.6  | 1         | 0.97%   |
| 5.15.17 | 1         | 0.97%   |
| 5.15.15 | 1         | 0.97%   |
| 5.15.13 | 1         | 0.97%   |
| 5.15.12 | 1         | 0.97%   |
| 5.15.11 | 1         | 0.97%   |
| 5.15.10 | 1         | 0.97%   |
| 5.13.19 | 1         | 0.97%   |
| 3.16.85 | 1         | 0.97%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 81        | 78.64%  |
| 5.13    | 14        | 13.59%  |
| 5.17    | 5         | 4.85%   |
| 5.16    | 2         | 1.94%   |
| 3.16    | 1         | 0.97%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 101       | 99.02%  |
| aarch64 | 1         | 0.98%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| GNOME             | 90        | 86.54%  |
| Unknown           | 9         | 8.65%   |
| Yaru:ubuntu:GNOME | 1         | 0.96%   |
| X-Cinnamon        | 1         | 0.96%   |
| GNUstep           | 1         | 0.96%   |
| GNOME Flashback   | 1         | 0.96%   |
| Cinnamon          | 1         | 0.96%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 53        | 50.96%  |
| X11     | 41        | 39.42%  |
| Tty     | 7         | 6.73%   |
| Unknown | 3         | 2.88%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GDM3    | 86        | 83.5%   |
| Unknown | 11        | 10.68%  |
| LightDM | 3         | 2.91%   |
| GDM     | 3         | 2.91%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 49        | 48.04%  |
| de_DE   | 10        | 9.8%    |
| en_IN   | 8         | 7.84%   |
| pt_BR   | 4         | 3.92%   |
| fr_FR   | 4         | 3.92%   |
| ru_RU   | 3         | 2.94%   |
| en_GB   | 3         | 2.94%   |
| zh_CN   | 2         | 1.96%   |
| pl_PL   | 2         | 1.96%   |
| it_IT   | 2         | 1.96%   |
| cs_CZ   | 2         | 1.96%   |
| Unknown | 2         | 1.96%   |
| zh_TW   | 1         | 0.98%   |
| th_TH   | 1         | 0.98%   |
| ro_RO   | 1         | 0.98%   |
| hu_HU   | 1         | 0.98%   |
| es_ES   | 1         | 0.98%   |
| en_SG   | 1         | 0.98%   |
| en_IL   | 1         | 0.98%   |
| en_CA   | 1         | 0.98%   |
| de_IT   | 1         | 0.98%   |
| de_CH   | 1         | 0.98%   |
| C       | 1         | 0.98%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 53        | 51.96%  |
| EFI  | 49        | 48.04%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 94        | 90.38%  |
| Btrfs   | 4         | 3.85%   |
| Zfs     | 3         | 2.88%   |
| Xfs     | 2         | 1.92%   |
| Overlay | 1         | 0.96%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 54        | 52.94%  |
| GPT     | 44        | 43.14%  |
| MBR     | 4         | 3.92%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 80        | 78.43%  |
| Yes       | 22        | 21.57%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 52        | 50.49%  |
| No        | 51        | 49.51%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Hewlett-Packard                | 19        | 18.63%  |
| Lenovo                         | 13        | 12.75%  |
| ASUSTek Computer               | 13        | 12.75%  |
| MSI                            | 11        | 10.78%  |
| Dell                           | 9         | 8.82%   |
| Gigabyte Technology            | 8         | 7.84%   |
| HUAWEI                         | 3         | 2.94%   |
| Toshiba                        | 2         | 1.96%   |
| Intel                          | 2         | 1.96%   |
| Unknown                        | 2         | 1.96%   |
| TrekStor                       | 1         | 0.98%   |
| Timi                           | 1         | 0.98%   |
| Shenzhen Wangang Technology    | 1         | 0.98%   |
| Shanghai Zhaoxin Semiconductor | 1         | 0.98%   |
| Samsung Electronics            | 1         | 0.98%   |
| Packard Bell                   | 1         | 0.98%   |
| Medion                         | 1         | 0.98%   |
| Le Cube 1                      | 1         | 0.98%   |
| Huanan                         | 1         | 0.98%   |
| GPU Company                    | 1         | 0.98%   |
| Google                         | 1         | 0.98%   |
| Fujitsu                        | 1         | 0.98%   |
| Framework                      | 1         | 0.98%   |
| BESSTAR Tech                   | 1         | 0.98%   |
| Avell High Performance         | 1         | 0.98%   |
| ASRockRack                     | 1         | 0.98%   |
| ASRock                         | 1         | 0.98%   |
| Apple                          | 1         | 0.98%   |
| Alienware                      | 1         | 0.98%   |
| Acer                           | 1         | 0.98%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                              | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Unknown                                           | 3         | 2.94%   |
| TrekStor Primetab S11B                            | 1         | 0.98%   |
| Toshiba Satellite C70D-A                          | 1         | 0.98%   |
| Toshiba PORTEGE Z10T-A                            | 1         | 0.98%   |
| Timi TM1709                                       | 1         | 0.98%   |
| Shenzhen Wangang AERO 2 Pro                       | 1         | 0.98%   |
| Shanghai Zhaoxin ZXE CRB                          | 1         | 0.98%   |
| Samsung R580/R590                                 | 1         | 0.98%   |
| Packard Bell IMEDIA S2110                         | 1         | 0.98%   |
| MSI Stealth GS66 12UHS                            | 1         | 0.98%   |
| MSI MS-7D42                                       | 1         | 0.98%   |
| MSI MS-7C75                                       | 1         | 0.98%   |
| MSI MS-7B84                                       | 1         | 0.98%   |
| MSI MS-7A32                                       | 1         | 0.98%   |
| MSI MS-7998                                       | 1         | 0.98%   |
| MSI MS-7235                                       | 1         | 0.98%   |
| MSI Modern 15 A11MU                               | 1         | 0.98%   |
| MSI GT73VR 6RE                                    | 1         | 0.98%   |
| MSI GP76 Leopard 11UG                             | 1         | 0.98%   |
| MSI Creator Z16 A11UET                            | 1         | 0.98%   |
| Medion S4401 MD61533                              | 1         | 0.98%   |
| Lenovo Z50-70 20354                               | 1         | 0.98%   |
| Lenovo ThinkPad Yoga 370 20JJS01S1D               | 1         | 0.98%   |
| Lenovo ThinkPad X1 Yoga Gen 6 20XYCTO1WW          | 1         | 0.98%   |
| Lenovo ThinkPad T14s Gen 2a 20XF004WUS            | 1         | 0.98%   |
| Lenovo ThinkPad P1 Gen 4i 20Y3004KUS              | 1         | 0.98%   |
| Lenovo ThinkPad E495 20NEA00QUS                   | 1         | 0.98%   |
| Lenovo ThinkPad E15 Gen 2 20TES2H500              | 1         | 0.98%   |
| Lenovo ThinkBook 15 G3 ACL 21A4                   | 1         | 0.98%   |
| Lenovo QiTianM520-D164 90K7S03T00                 | 1         | 0.98%   |
| Lenovo Legion 7 16ACHg6 82N6                      | 1         | 0.98%   |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7                  | 1         | 0.98%   |
| Lenovo IdeaPad 5 14ITL05 82FE                     | 1         | 0.98%   |
| Lenovo Flex 2-15 20405                            | 1         | 0.98%   |
| Intel S2600CP                                     | 1         | 0.98%   |
| Intel H61                                         | 1         | 0.98%   |
| HUAWEI MACH-WX9                                   | 1         | 0.98%   |
| HUAWEI CREM-WXX9                                  | 1         | 0.98%   |
| HUAWEI BOHB-WAX9                                  | 1         | 0.98%   |
| Huanan X99 F8D V2.2                               | 1         | 0.98%   |
| HP ZBook Power 15.6 inch G8 Mobile Workstation PC | 1         | 0.98%   |
| HP ZBook 15 G5                                    | 1         | 0.98%   |
| HP Z440 Workstation                               | 1         | 0.98%   |
| HP Z420 Workstation                               | 1         | 0.98%   |
| HP ProLiant ML110 G7                              | 1         | 0.98%   |
| HP ProBook 650 G5                                 | 1         | 0.98%   |
| HP ProBook 445 G7                                 | 1         | 0.98%   |
| HP Presario CQ42                                  | 1         | 0.98%   |
| HP Pavilion x2 Detachable                         | 1         | 0.98%   |
| HP Pavilion Laptop 14-dv1xxx                      | 1         | 0.98%   |
| HP Pavilion Laptop 14-ce2xxx                      | 1         | 0.98%   |
| HP Pavilion 15                                    | 1         | 0.98%   |
| HP Laptop 15s-fq1xxx                              | 1         | 0.98%   |
| HP ENVY x360 Convertible 13m-bd0xxx               | 1         | 0.98%   |
| HP ENVY Laptop 13-ad1xx                           | 1         | 0.98%   |
| HP EliteBook 840 G3                               | 1         | 0.98%   |
| HP 620                                            | 1         | 0.98%   |
| HP 250 G4                                         | 1         | 0.98%   |
| HP 15                                             | 1         | 0.98%   |
| GPU Company GWTC116-2                             | 1         | 0.98%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 6         | 5.88%   |
| Dell Inspiron           | 5         | 4.9%    |
| ASUS ROG                | 5         | 4.9%    |
| HP Pavilion             | 4         | 3.92%   |
| Unknown                 | 3         | 2.94%   |
| Lenovo IdeaPad          | 2         | 1.96%   |
| HP ZBook                | 2         | 1.96%   |
| HP ProBook              | 2         | 1.96%   |
| HP ENVY                 | 2         | 1.96%   |
| Dell OptiPlex           | 2         | 1.96%   |
| Dell Latitude           | 2         | 1.96%   |
| ASUS ASUS               | 2         | 1.96%   |
| TrekStor Primetab       | 1         | 0.98%   |
| Toshiba Satellite       | 1         | 0.98%   |
| Toshiba PORTEGE         | 1         | 0.98%   |
| Timi TM1709             | 1         | 0.98%   |
| Shenzhen Wangang AERO   | 1         | 0.98%   |
| Shanghai Zhaoxin ZXE    | 1         | 0.98%   |
| Samsung R580            | 1         | 0.98%   |
| Packard Bell IMEDIA     | 1         | 0.98%   |
| MSI Stealth             | 1         | 0.98%   |
| MSI MS-7D42             | 1         | 0.98%   |
| MSI MS-7C75             | 1         | 0.98%   |
| MSI MS-7B84             | 1         | 0.98%   |
| MSI MS-7A32             | 1         | 0.98%   |
| MSI MS-7998             | 1         | 0.98%   |
| MSI MS-7235             | 1         | 0.98%   |
| MSI Modern              | 1         | 0.98%   |
| MSI GT73VR              | 1         | 0.98%   |
| MSI GP76                | 1         | 0.98%   |
| MSI Creator             | 1         | 0.98%   |
| Medion S4401            | 1         | 0.98%   |
| Lenovo Z50-70           | 1         | 0.98%   |
| Lenovo ThinkBook        | 1         | 0.98%   |
| Lenovo QiTianM520-D164  | 1         | 0.98%   |
| Lenovo Legion           | 1         | 0.98%   |
| Lenovo Flex             | 1         | 0.98%   |
| Intel S2600CP           | 1         | 0.98%   |
| Intel H61               | 1         | 0.98%   |
| HUAWEI MACH-WX9         | 1         | 0.98%   |
| HUAWEI CREM-WXX9        | 1         | 0.98%   |
| HUAWEI BOHB-WAX9        | 1         | 0.98%   |
| Huanan X99              | 1         | 0.98%   |
| HP Z440                 | 1         | 0.98%   |
| HP Z420                 | 1         | 0.98%   |
| HP ProLiant             | 1         | 0.98%   |
| HP Presario             | 1         | 0.98%   |
| HP Laptop               | 1         | 0.98%   |
| HP EliteBook            | 1         | 0.98%   |
| HP 620                  | 1         | 0.98%   |
| HP 250                  | 1         | 0.98%   |
| HP 15                   | 1         | 0.98%   |
| GPU Company GWTC116-2   | 1         | 0.98%   |
| Google Kefka            | 1         | 0.98%   |
| Gigabyte Z690           | 1         | 0.98%   |
| Gigabyte X570S          | 1         | 0.98%   |
| Gigabyte X570           | 1         | 0.98%   |
| Gigabyte M52L-S3        | 1         | 0.98%   |
| Gigabyte H61M-DS2       | 1         | 0.98%   |
| Gigabyte GB-BSi7-1165G7 | 1         | 0.98%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 29        | 28.43%  |
| 2020    | 14        | 13.73%  |
| 2019    | 10        | 9.8%    |
| 2010    | 9         | 8.82%   |
| 2018    | 6         | 5.88%   |
| 2013    | 6         | 5.88%   |
| 2012    | 6         | 5.88%   |
| 2014    | 5         | 4.9%    |
| 2017    | 4         | 3.92%   |
| 2015    | 3         | 2.94%   |
| 2016    | 2         | 1.96%   |
| 2011    | 2         | 1.96%   |
| 2008    | 2         | 1.96%   |
| 2022    | 1         | 0.98%   |
| 2007    | 1         | 0.98%   |
| 2006    | 1         | 0.98%   |
| Unknown | 1         | 0.98%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 57        | 55.88%  |
| Desktop        | 33        | 32.35%  |
| Convertible    | 6         | 5.88%   |
| Mini pc        | 2         | 1.96%   |
| Server         | 2         | 1.96%   |
| System on chip | 1         | 0.98%   |
| Tablet         | 1         | 0.98%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 90        | 88.24%  |
| Enabled  | 12        | 11.76%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 101       | 99.02%  |
| Yes  | 1         | 0.98%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 20        | 19.61%  |
| 16.01-24.0  | 18        | 17.65%  |
| 32.01-64.0  | 16        | 15.69%  |
| 3.01-4.0    | 16        | 15.69%  |
| 8.01-16.0   | 13        | 12.75%  |
| 64.01-256.0 | 10        | 9.8%    |
| 24.01-32.0  | 4         | 3.92%   |
| 1.01-2.0    | 3         | 2.94%   |
| 2.01-3.0    | 2         | 1.96%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 30        | 28.85%  |
| 2.01-3.0   | 27        | 25.96%  |
| 4.01-8.0   | 24        | 23.08%  |
| 3.01-4.0   | 11        | 10.58%  |
| 8.01-16.0  | 6         | 5.77%   |
| 0.01-0.5   | 3         | 2.88%   |
| 0.51-1.0   | 2         | 1.92%   |
| 24.01-32.0 | 1         | 0.96%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 61        | 59.22%  |
| 2      | 27        | 26.21%  |
| 3      | 6         | 5.83%   |
| 4      | 5         | 4.85%   |
| 20     | 1         | 0.97%   |
| 8      | 1         | 0.97%   |
| 6      | 1         | 0.97%   |
| 5      | 1         | 0.97%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 74        | 71.84%  |
| Yes       | 29        | 28.16%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 81        | 79.41%  |
| No        | 21        | 20.59%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 85        | 83.33%  |
| No        | 17        | 16.67%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 74        | 71.84%  |
| No        | 29        | 28.16%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 19        | 18.63%  |
| Germany     | 13        | 12.75%  |
| India       | 9         | 8.82%   |
| France      | 6         | 5.88%   |
| Italy       | 5         | 4.9%    |
| Russia      | 4         | 3.92%   |
| Poland      | 4         | 3.92%   |
| China       | 4         | 3.92%   |
| Brazil      | 4         | 3.92%   |
| Taiwan      | 3         | 2.94%   |
| Spain       | 3         | 2.94%   |
| UK          | 2         | 1.96%   |
| Thailand    | 2         | 1.96%   |
| Romania     | 2         | 1.96%   |
| Mexico      | 2         | 1.96%   |
| Japan       | 2         | 1.96%   |
| Czechia     | 2         | 1.96%   |
| Switzerland | 1         | 0.98%   |
| South Korea | 1         | 0.98%   |
| Slovenia    | 1         | 0.98%   |
| Singapore   | 1         | 0.98%   |
| Netherlands | 1         | 0.98%   |
| Myanmar     | 1         | 0.98%   |
| Morocco     | 1         | 0.98%   |
| Israel      | 1         | 0.98%   |
| Iceland     | 1         | 0.98%   |
| Hungary     | 1         | 0.98%   |
| Egypt       | 1         | 0.98%   |
| Colombia    | 1         | 0.98%   |
| Canada      | 1         | 0.98%   |
| Cameroon    | 1         | 0.98%   |
| Belgium     | 1         | 0.98%   |
| Argentina   | 1         | 0.98%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| Moses Lake               | 3         | 2.91%   |
| Warsaw                   | 2         | 1.94%   |
| St Petersburg            | 2         | 1.94%   |
| Oakland                  | 2         | 1.94%   |
| Madrid                   | 2         | 1.94%   |
| Kunming                  | 2         | 1.94%   |
| Chennai                  | 2         | 1.94%   |
| Chandigarh               | 2         | 1.94%   |
| Boeschepe                | 2         | 1.94%   |
| Beijing                  | 2         | 1.94%   |
| YaoundÃ©               | 1         | 0.97%   |
| Yangon                   | 1         | 0.97%   |
| Worms                    | 1         | 0.97%   |
| Wil                      | 1         | 0.97%   |
| Wake Forest              | 1         | 0.97%   |
| Tubarao                  | 1         | 0.97%   |
| The Hague                | 1         | 0.97%   |
| Tel Aviv                 | 1         | 0.97%   |
| Taoyuan District         | 1         | 0.97%   |
| Taipei                   | 1         | 0.97%   |
| Sutton Coldfield         | 1         | 0.97%   |
| Suffolk                  | 1         | 0.97%   |
| Springdale               | 1         | 0.97%   |
| Soest                    | 1         | 0.97%   |
| Singapore                | 1         | 0.97%   |
| Siegen                   | 1         | 0.97%   |
| Seward                   | 1         | 0.97%   |
| Seoul                    | 1         | 0.97%   |
| Senonches                | 1         | 0.97%   |
| San Valentino Torio      | 1         | 0.97%   |
| San Francisco            | 1         | 0.97%   |
| Richland Center          | 1         | 0.97%   |
| Reykjavik                | 1         | 0.97%   |
| Renchen                  | 1         | 0.97%   |
| Recife                   | 1         | 0.97%   |
| Pune                     | 1         | 0.97%   |
| Prague                   | 1         | 0.97%   |
| Porto Alegre             | 1         | 0.97%   |
| Ploieşti                | 1         | 0.97%   |
| Phuket                   | 1         | 0.97%   |
| Paris                    | 1         | 0.97%   |
| Papun                    | 1         | 0.97%   |
| Palermo                  | 1         | 0.97%   |
| Palau-solita i Plegamans | 1         | 0.97%   |
| Ostrava                  | 1         | 0.97%   |
| Osasco                   | 1         | 0.97%   |
| Orehova Vas              | 1         | 0.97%   |
| Novosibirsk              | 1         | 0.97%   |
| Newark                   | 1         | 0.97%   |
| New Taipei               | 1         | 0.97%   |
| Mountain Grove           | 1         | 0.97%   |
| Moscow                   | 1         | 0.97%   |
| Millville                | 1         | 0.97%   |
| Milan                    | 1         | 0.97%   |
| Mexico City              | 1         | 0.97%   |
| MÃ¶nchengladbach       | 1         | 0.97%   |
| Marnaz                   | 1         | 0.97%   |
| Mariposa                 | 1         | 0.97%   |
| Madison                  | 1         | 0.97%   |
| Ludhiana                 | 1         | 0.97%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 31        | 42     | 21.09%  |
| Seagate             | 22        | 27     | 14.97%  |
| WDC                 | 20        | 45     | 13.61%  |
| Unknown             | 10        | 14     | 6.8%    |
| Kingston            | 8         | 11     | 5.44%   |
| Intel               | 7         | 8      | 4.76%   |
| Toshiba             | 6         | 7      | 4.08%   |
| KIOXIA              | 5         | 6      | 3.4%    |
| SK Hynix            | 4         | 4      | 2.72%   |
| SanDisk             | 4         | 4      | 2.72%   |
| Hitachi             | 4         | 4      | 2.72%   |
| Phison              | 3         | 3      | 2.04%   |
| OCZ                 | 2         | 5      | 1.36%   |
| Micron Technology   | 2         | 3      | 1.36%   |
| Intenso             | 2         | 2      | 1.36%   |
| UMAX                | 1         | 1      | 0.68%   |
| Transcend           | 1         | 1      | 0.68%   |
| SPCC                | 1         | 1      | 0.68%   |
| Silicon Motion      | 1         | 1      | 0.68%   |
| PNY                 | 1         | 1      | 0.68%   |
| PLEXTOR             | 1         | 1      | 0.68%   |
| Netac SS            | 1         | 1      | 0.68%   |
| LITEON              | 1         | 1      | 0.68%   |
| KLEVV               | 1         | 1      | 0.68%   |
| JMicron             | 1         | 1      | 0.68%   |
| HGST                | 1         | 2      | 0.68%   |
| Crucial             | 1         | 1      | 0.68%   |
| China               | 1         | 1      | 0.68%   |
| Apple               | 1         | 1      | 0.68%   |
| ADATA Technology    | 1         | 2      | 0.68%   |
| A-DATA Technology   | 1         | 1      | 0.68%   |
| Unknown             | 1         | 1      | 0.68%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 512GB           | 4         | 2.37%   |
| Seagate ST1000DM010-2EP102 1TB         | 3         | 1.78%   |
| Samsung SSD 850 EVO 500GB              | 3         | 1.78%   |
| Intel NVMe SSD Drive 512GB             | 3         | 1.78%   |
| WDC WD10EZRX-00A8LB0 1TB               | 2         | 1.18%   |
| Seagate ST9500420AS 500GB              | 2         | 1.18%   |
| Seagate ST2000DM008-2FR102 2TB         | 2         | 1.18%   |
| Samsung SSD 750 EVO 250GB              | 2         | 1.18%   |
| Samsung SM963 2.5" NVMe PCIe SSD 500GB | 2         | 1.18%   |
| Samsung NVMe SSD Drive 256GB           | 2         | 1.18%   |
| Samsung NVMe SSD Drive 1TB             | 2         | 1.18%   |
| KIOXIA NVMe SSD Drive 256GB            | 2         | 1.18%   |
| WDC WDS500G3X0C-00SJG0 500GB           | 1         | 0.59%   |
| WDC WDS100T3X0C-00SJG0 1TB             | 1         | 0.59%   |
| WDC WDS100T1X0E-00AFY0 1TB             | 1         | 0.59%   |
| WDC WDBNCE0010PNC 1TB SSD              | 1         | 0.59%   |
| WDC WD80EMAZ-00WJTA0 8TB               | 1         | 0.59%   |
| WDC WD80EFZX-68UW8N0 8TB               | 1         | 0.59%   |
| WDC WD80EFAX-68LHPN0 8TB               | 1         | 0.59%   |
| WDC WD80 EMAZ-00WJTA0 8TB              | 1         | 0.59%   |
| WDC WD60 EFRX-68L0BN1 6TB              | 1         | 0.59%   |
| WDC WD40EFRX-68N32N0 4TB               | 1         | 0.59%   |
| WDC WD4000AAKS-00TMA0 400GB            | 1         | 0.59%   |
| WDC WD3200BPVT-75JJ5T0 320GB           | 1         | 0.59%   |
| WDC WD3200AAKS-00L9A0 320GB            | 1         | 0.59%   |
| WDC WD3200AAKS-00B3A0 320GB            | 1         | 0.59%   |
| WDC WD3200AAJS-00VWA0 320GB            | 1         | 0.59%   |
| WDC WD20SPZX-75UA7T1 2TB               | 1         | 0.59%   |
| WDC WD20EARX-00PASB0 2TB               | 1         | 0.59%   |
| WDC WD20EARS-00MVWB0 2TB               | 1         | 0.59%   |
| WDC WD140EDFZ-11A0VA0 14TB             | 1         | 0.59%   |
| WDC WD12 0EMAZ-11BLFA 12TB             | 1         | 0.59%   |
| WDC WD10SPSX-60A6WT0 1TB               | 1         | 0.59%   |
| WDC WD10SPCX-24HWST1 1TB               | 1         | 0.59%   |
| WDC WD10JPVX-60JC3T0 1TB               | 1         | 0.59%   |
| WDC WD100EMAZ-00WJTA0 10TB             | 1         | 0.59%   |
| WDC WD1001FALS-00J7B0 1TB              | 1         | 0.59%   |
| WDC WD10 0EMAZ-00WJTA 10TB             | 1         | 0.59%   |
| WDC PC SN810 SDCPNRZ-2T00-1032 2TB     | 1         | 0.59%   |
| WDC PC SN730 SDBPNTY-512G              | 1         | 0.59%   |
| WDC PC SN530 SDBPNPZ-512G-1027 512GB   | 1         | 0.59%   |
| WDC PC SN530 SDBPNPZ-512G-1002 512GB   | 1         | 0.59%   |
| WDC PC SN520 SDAPMUW-128G-1001 128GB   | 1         | 0.59%   |
| Unknown SLD64G  64GB                   | 1         | 0.59%   |
| Unknown SD/MMC/MS PRO 3GB              | 1         | 0.59%   |
| Unknown SC128  128GB                   | 1         | 0.59%   |
| Unknown SB16G  16GB                    | 1         | 0.59%   |
| Unknown NVMe SSD Drive 512GB           | 1         | 0.59%   |
| Unknown MMC Card  64GB                 | 1         | 0.59%   |
| Unknown MMC Card  32GB                 | 1         | 0.59%   |
| Unknown MMC Card  16GB                 | 1         | 0.59%   |
| Unknown DA4128  128GB                  | 1         | 0.59%   |
| Unknown Biwin  64GB                    | 1         | 0.59%   |
| UMAX 2280 64G SSD                      | 1         | 0.59%   |
| Transcend TS512GSSD370S 512GB          | 1         | 0.59%   |
| Toshiba MQ01ABD100M 1TB                | 1         | 0.59%   |
| Toshiba KXG50ZNV512G 512GB             | 1         | 0.59%   |
| Toshiba HDWL120 2TB                    | 1         | 0.59%   |
| Toshiba HDWE140 4TB                    | 1         | 0.59%   |
| Toshiba DT01ACA100 1TB                 | 1         | 0.59%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 22        | 27     | 44.9%   |
| WDC                 | 12        | 35     | 24.49%  |
| Toshiba             | 5         | 5      | 10.2%   |
| Hitachi             | 4         | 4      | 8.16%   |
| Samsung Electronics | 3         | 3      | 6.12%   |
| Unknown             | 1         | 1      | 2.04%   |
| HGST                | 1         | 2      | 2.04%   |
| Apple               | 1         | 1      | 2.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 12     | 27.78%  |
| Kingston            | 4         | 5      | 11.11%  |
| SanDisk             | 3         | 3      | 8.33%   |
| Intenso             | 2         | 2      | 5.56%   |
| Intel               | 2         | 2      | 5.56%   |
| WDC                 | 1         | 1      | 2.78%   |
| UMAX                | 1         | 1      | 2.78%   |
| Transcend           | 1         | 1      | 2.78%   |
| SPCC                | 1         | 1      | 2.78%   |
| PNY                 | 1         | 1      | 2.78%   |
| PLEXTOR             | 1         | 1      | 2.78%   |
| OCZ                 | 1         | 1      | 2.78%   |
| Micron Technology   | 1         | 1      | 2.78%   |
| LITEON              | 1         | 1      | 2.78%   |
| KLEVV               | 1         | 1      | 2.78%   |
| JMicron             | 1         | 1      | 2.78%   |
| Crucial             | 1         | 1      | 2.78%   |
| China               | 1         | 1      | 2.78%   |
| A-DATA Technology   | 1         | 1      | 2.78%   |
| Unknown             | 1         | 1      | 2.78%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 55        | 74     | 41.67%  |
| HDD     | 38        | 78     | 28.79%  |
| SSD     | 30        | 39     | 22.73%  |
| MMC     | 8         | 12     | 6.06%   |
| Unknown | 1         | 1      | 0.76%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 57        | 105    | 45.24%  |
| NVMe | 55        | 73     | 43.65%  |
| MMC  | 8         | 12     | 6.35%   |
| SAS  | 6         | 14     | 4.76%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 41        | 50     | 56.16%  |
| 0.51-1.0   | 20        | 28     | 27.4%   |
| 1.01-2.0   | 8         | 19     | 10.96%  |
| 10.01-20.0 | 2         | 6      | 2.74%   |
| 3.01-4.0   | 1         | 2      | 1.37%   |
| 4.01-10.0  | 1         | 12     | 1.37%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 30        | 28.57%  |
| 251-500        | 26        | 24.76%  |
| 501-1000       | 16        | 15.24%  |
| 1-20           | 8         | 7.62%   |
| 1001-2000      | 6         | 5.71%   |
| 51-100         | 6         | 5.71%   |
| More than 3000 | 5         | 4.76%   |
| 2001-3000      | 3         | 2.86%   |
| Unknown        | 3         | 2.86%   |
| 21-50          | 2         | 1.9%    |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 33        | 30.84%  |
| 21-50          | 20        | 18.69%  |
| 51-100         | 19        | 17.76%  |
| 101-250        | 16        | 14.95%  |
| 251-500        | 8         | 7.48%   |
| More than 3000 | 3         | 2.8%    |
| 501-1000       | 3         | 2.8%    |
| Unknown        | 3         | 2.8%    |
| 2001-3000      | 1         | 0.93%   |
| 0              | 1         | 0.93%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD10JPVX-60JC3T0 1TB            | 1         | 1      | 12.5%   |
| Seagate ST9500420AS 500GB           | 1         | 1      | 12.5%   |
| Seagate ST9320325AS 320GB           | 1         | 1      | 12.5%   |
| Seagate ST3750640NS 752GB           | 1         | 2      | 12.5%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 1         | 1      | 12.5%   |
| Samsung Electronics HM160HI 160GB   | 1         | 1      | 12.5%   |
| LITEON CV8-8E128-HP 128GB SSD       | 1         | 1      | 12.5%   |
| Intenso SSD 120GB                   | 1         | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 5      | 50%     |
| WDC                 | 1         | 1      | 12.5%   |
| Samsung Electronics | 1         | 1      | 12.5%   |
| LITEON              | 1         | 1      | 12.5%   |
| Intenso             | 1         | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 5      | 66.67%  |
| WDC                 | 1         | 1      | 16.67%  |
| Samsung Electronics | 1         | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 7      | 75%     |
| SSD  | 2         | 2      | 25%     |

Failed Drives
-------------

Failed drive models

Zero info for selected period =(

Failed Drive Vendor
-------------------

Failed drive vendors

Zero info for selected period =(

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 62        | 129    | 56.88%  |
| Works    | 39        | 66     | 35.78%  |
| Malfunc  | 8         | 9      | 7.34%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 63        | 44.06%  |
| Samsung Electronics          | 22        | 15.38%  |
| AMD                          | 19        | 13.29%  |
| Sandisk                      | 9         | 6.29%   |
| KIOXIA                       | 5         | 3.5%    |
| Kingston Technology Company  | 5         | 3.5%    |
| SK Hynix                     | 4         | 2.8%    |
| Phison Electronics           | 3         | 2.1%    |
| ASMedia Technology           | 2         | 1.4%    |
| Zhaoxin                      | 1         | 0.7%    |
| Toshiba America Info Systems | 1         | 0.7%    |
| Silicon Motion               | 1         | 0.7%    |
| Shenzhen Longsys Electronics | 1         | 0.7%    |
| OCZ Technology Group         | 1         | 0.7%    |
| Nvidia                       | 1         | 0.7%    |
| Micron Technology            | 1         | 0.7%    |
| Marvell Technology Group     | 1         | 0.7%    |
| LSI Logic / Symbios Logic    | 1         | 0.7%    |
| JMicron Technology           | 1         | 0.7%    |
| ADATA Technology             | 1         | 0.7%    |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 15        | 9.09%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 8         | 4.85%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 8         | 4.85%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 6         | 3.64%   |
| Samsung NVMe SSD Controller 980                                                         | 5         | 3.03%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 5         | 3.03%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 4         | 2.42%   |
| KIOXIA Non-Volatile memory controller                                                   | 4         | 2.42%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 4         | 2.42%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 4         | 2.42%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 4         | 2.42%   |
| SK Hynix Gold P31 SSD                                                                   | 3         | 1.82%   |
| Kingston Company Company Non-Volatile memory controller                                 | 3         | 1.82%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 3         | 1.82%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3         | 1.82%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3         | 1.82%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                              | 2         | 1.21%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 2         | 1.21%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 1.21%   |
| Phison E12 NVMe Controller                                                              | 2         | 1.21%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                         | 2         | 1.21%   |
| Intel SSD 660P Series                                                                   | 2         | 1.21%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2         | 1.21%   |
| Intel Non-Volatile memory controller                                                    | 2         | 1.21%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2         | 1.21%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 2         | 1.21%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 2         | 1.21%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 2         | 1.21%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 2         | 1.21%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 2         | 1.21%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1.21%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1.21%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2         | 1.21%   |
| AMD X370 Series Chipset SATA Controller                                                 | 2         | 1.21%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2         | 1.21%   |
| Zhaoxin ZX-100/ZX-200/ZX-E StorX AHCI Controller                                        | 1         | 0.61%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller        | 1         | 0.61%   |
| SK Hynix BC511                                                                          | 1         | 0.61%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1         | 0.61%   |
| Shenzhen Longsys Electronics Non-Volatile memory controller                             | 1         | 0.61%   |
| Sandisk PC SN520 NVMe SSD                                                               | 1         | 0.61%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1         | 0.61%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1         | 0.61%   |
| OCZ Group RD400/400A SSD                                                                | 1         | 0.61%   |
| Nvidia MCP61 SATA Controller                                                            | 1         | 0.61%   |
| Nvidia MCP61 IDE                                                                        | 1         | 0.61%   |
| Micron Non-Volatile memory controller                                                   | 1         | 0.61%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1         | 0.61%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                 | 1         | 0.61%   |
| KIOXIA NVMe SSD Controller Cx6                                                          | 1         | 0.61%   |
| Kingston Company OM3PDP3 NVMe SSD                                                       | 1         | 0.61%   |
| Kingston Company A2000 NVMe SSD                                                         | 1         | 0.61%   |
| JMicron JMB368 IDE controller                                                           | 1         | 0.61%   |
| Intel SSD 600P Series                                                                   | 1         | 0.61%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 1         | 0.61%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 1         | 0.61%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 1         | 0.61%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1         | 0.61%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 1         | 0.61%   |
| Intel C610/X99 series chipset sSATA Controller [RAID mode]                              | 1         | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 62        | 42.47%  |
| NVMe | 55        | 37.67%  |
| RAID | 14        | 9.59%   |
| IDE  | 12        | 8.22%   |
| SAS  | 3         | 2.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 76        | 74.51%  |
| AMD          | 24        | 23.53%  |
| CentaurHauls | 1         | 0.98%   |
| ARM          | 1         | 0.98%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 5         | 4.9%    |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 4         | 3.92%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 3         | 2.94%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 3         | 2.94%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 2         | 1.96%   |
| Intel 12th Gen Core i5-12600K           | 2         | 1.96%   |
| AMD Ryzen 7 4800HS with Radeon Graphics | 2         | 1.96%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 2         | 1.96%   |
| Intel Xeon CPU E5-2696 v2 @ 2.50GHz     | 1         | 0.98%   |
| Intel Xeon CPU E5-2690 v4 @ 2.60GHz     | 1         | 0.98%   |
| Intel Xeon CPU E5-2609 v2 @ 2.50GHz     | 1         | 0.98%   |
| Intel Xeon CPU E5-1650 v4 @ 3.60GHz     | 1         | 0.98%   |
| Intel Xeon CPU E31220 @ 3.10GHz         | 1         | 0.98%   |
| Intel Pentium Dual CPU T3200 @ 2.00GHz  | 1         | 0.98%   |
| Intel Pentium CPU G3260T @ 2.90GHz      | 1         | 0.98%   |
| Intel Pentium 4 CPU 3.00GHz             | 1         | 0.98%   |
| Intel Pentium 3558U @ 1.70GHz           | 1         | 0.98%   |
| Intel Genuine CPU U7300 @ 1.30GHz       | 1         | 0.98%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 1         | 0.98%   |
| Intel Core i7-8665U CPU @ 1.90GHz       | 1         | 0.98%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 1         | 0.98%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 0.98%   |
| Intel Core i7-6820HK CPU @ 2.70GHz      | 1         | 0.98%   |
| Intel Core i7-4510U CPU @ 2.00GHz       | 1         | 0.98%   |
| Intel Core i5-9500 CPU @ 3.00GHz        | 1         | 0.98%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 1         | 0.98%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 1         | 0.98%   |
| Intel Core i5-4460S CPU @ 2.90GHz       | 1         | 0.98%   |
| Intel Core i5-4220Y CPU @ 1.60GHz       | 1         | 0.98%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 1         | 0.98%   |
| Intel Core i5-3570 CPU @ 3.40GHz        | 1         | 0.98%   |
| Intel Core i5-3450 CPU @ 3.10GHz        | 1         | 0.98%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 1         | 0.98%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 1         | 0.98%   |
| Intel Core i5 CPU M 560 @ 2.67GHz       | 1         | 0.98%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 1         | 0.98%   |
| Intel Core i3-9100F CPU @ 3.60GHz       | 1         | 0.98%   |
| Intel Core i3-6300T CPU @ 3.30GHz       | 1         | 0.98%   |
| Intel Core i3-4005U CPU @ 1.70GHz       | 1         | 0.98%   |
| Intel Core i3-3217U CPU @ 1.80GHz       | 1         | 0.98%   |
| Intel Core i3-2330M CPU @ 2.20GHz       | 1         | 0.98%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz      | 1         | 0.98%   |
| Intel Core i3 CPU M 370 @ 2.40GHz       | 1         | 0.98%   |
| Intel Core i3 CPU M 350 @ 2.27GHz       | 1         | 0.98%   |
| Intel Core i3 CPU M 330 @ 2.13GHz       | 1         | 0.98%   |
| Intel Core 2 Duo CPU T6670 @ 2.20GHz    | 1         | 0.98%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 1         | 0.98%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz    | 1         | 0.98%   |
| Intel Celeron N5105 @ 2.00GHz           | 1         | 0.98%   |
| Intel Celeron J4105 CPU @ 1.50GHz       | 1         | 0.98%   |
| Intel Celeron CPU N3350 @ 1.10GHz       | 1         | 0.98%   |
| Intel Celeron CPU N3060 @ 1.60GHz       | 1         | 0.98%   |
| Intel Celeron CPU N2840 @ 2.16GHz       | 1         | 0.98%   |
| Intel Celeron CPU G1620 @ 2.70GHz       | 1         | 0.98%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz       | 1         | 0.98%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz       | 1         | 0.98%   |
| Intel 12th Gen Core i9-12900H           | 1         | 0.98%   |
| Intel 12th Gen Core i7-12700H           | 1         | 0.98%   |
| Intel 11th Gen Core i9-11950H @ 2.60GHz | 1         | 0.98%   |
| Intel 11th Gen Core i9-11900H @ 2.50GHz | 1         | 0.98%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Other              | 26        | 25.49%  |
| Intel Core i5      | 15        | 14.71%  |
| Intel Core i3      | 9         | 8.82%   |
| Intel Celeron      | 8         | 7.84%   |
| AMD Ryzen 7        | 7         | 6.86%   |
| Intel Core i7      | 6         | 5.88%   |
| AMD Ryzen 5        | 6         | 5.88%   |
| Intel Xeon         | 5         | 4.9%    |
| Intel Core 2 Duo   | 3         | 2.94%   |
| Intel Pentium      | 2         | 1.96%   |
| Intel Atom         | 2         | 1.96%   |
| AMD Ryzen 9        | 2         | 1.96%   |
| AMD Ryzen 7 PRO    | 2         | 1.96%   |
| Intel Pentium Dual | 1         | 0.98%   |
| Intel Pentium 4    | 1         | 0.98%   |
| Intel Genuine      | 1         | 0.98%   |
| AMD Phenom II X6   | 1         | 0.98%   |
| AMD Phenom II X4   | 1         | 0.98%   |
| AMD E1             | 1         | 0.98%   |
| AMD Athlon 64 X2   | 1         | 0.98%   |
| AMD A4             | 1         | 0.98%   |
| AMD A10            | 1         | 0.98%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 32        | 31.37%  |
| 2       | 32        | 31.37%  |
| 8       | 18        | 17.65%  |
| 6       | 10        | 9.8%    |
| 14      | 2         | 1.96%   |
| 12      | 2         | 1.96%   |
| 10      | 2         | 1.96%   |
| 1       | 2         | 1.96%   |
| 28      | 1         | 0.98%   |
| Unknown | 1         | 0.98%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 99        | 97.06%  |
| 2       | 2         | 1.96%   |
| Unknown | 1         | 0.98%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 67        | 65.69%  |
| 1       | 34        | 33.33%  |
| Unknown | 1         | 0.98%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 102       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 48        | 46.6%   |
| 0x806c1    | 7         | 6.8%    |
| 0x806ea    | 4         | 3.88%   |
| 0x806d1    | 3         | 2.91%   |
| 0x306a9    | 3         | 2.91%   |
| 0x0a50000c | 3         | 2.91%   |
| 0x906ea    | 2         | 1.94%   |
| 0x906a3    | 2         | 1.94%   |
| 0x806ec    | 2         | 1.94%   |
| 0x706a8    | 2         | 1.94%   |
| 0x40651    | 2         | 1.94%   |
| 0x306e4    | 2         | 1.94%   |
| 0x20655    | 2         | 1.94%   |
| 0xa0671    | 1         | 0.97%   |
| 0x806c2    | 1         | 0.97%   |
| 0x706e5    | 1         | 0.97%   |
| 0x706a1    | 1         | 0.97%   |
| 0x6fd      | 1         | 0.97%   |
| 0x506e3    | 1         | 0.97%   |
| 0x506c9    | 1         | 0.97%   |
| 0x306c3    | 1         | 0.97%   |
| 0x1067a    | 1         | 0.97%   |
| 0x10677    | 1         | 0.97%   |
| 0x0a50000b | 1         | 0.97%   |
| 0x0a201016 | 1         | 0.97%   |
| 0x0a201009 | 1         | 0.97%   |
| 0x08701021 | 1         | 0.97%   |
| 0x08608103 | 1         | 0.97%   |
| 0x08600104 | 1         | 0.97%   |
| 0x08001137 | 1         | 0.97%   |
| 0x0600611a | 1         | 0.97%   |
| 0x06001119 | 1         | 0.97%   |
| 0x05000119 | 1         | 0.97%   |
| 0x010000c8 | 1         | 0.97%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| TigerLake        | 11        | 10.78%  |
| KabyLake         | 11        | 10.78%  |
| Unknown          | 10        | 9.8%    |
| Zen 3            | 7         | 6.86%   |
| IvyBridge        | 7         | 6.86%   |
| Haswell          | 7         | 6.86%   |
| Zen 2            | 6         | 5.88%   |
| Westmere         | 5         | 4.9%    |
| Icelake          | 5         | 4.9%    |
| Silvermont       | 4         | 3.92%   |
| Skylake          | 3         | 2.94%   |
| Penryn           | 3         | 2.94%   |
| Goldmont plus    | 3         | 2.94%   |
| Zen              | 2         | 1.96%   |
| SandyBridge      | 2         | 1.96%   |
| K10              | 2         | 1.96%   |
| Core             | 2         | 1.96%   |
| Broadwell        | 2         | 1.96%   |
| Alderlake Hybrid | 2         | 1.96%   |
| Zen+             | 1         | 0.98%   |
| Piledriver       | 1         | 0.98%   |
| NetBurst         | 1         | 0.98%   |
| K8 Hammer        | 1         | 0.98%   |
| Jaguar           | 1         | 0.98%   |
| Goldmont         | 1         | 0.98%   |
| Excavator        | 1         | 0.98%   |
| Bobcat           | 1         | 0.98%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 57        | 47.11%  |
| Nvidia                     | 37        | 30.58%  |
| AMD                        | 24        | 19.83%  |
| Zhaoxin                    | 1         | 0.83%   |
| Matrox Electronics Systems | 1         | 0.83%   |
| ASPEED Technology          | 1         | 0.83%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 11        | 8.94%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 7         | 5.69%   |
| AMD Cezanne                                                                              | 5         | 4.07%   |
| Intel UHD Graphics 620                                                                   | 4         | 3.25%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 3.25%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 2.44%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 2.44%   |
| AMD Renoir                                                                               | 3         | 2.44%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 1.63%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 2         | 1.63%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 1.63%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                                 | 2         | 1.63%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 1.63%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1.63%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 1.63%   |
| Intel AlderLake-S GT1                                                                    | 2         | 1.63%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 2         | 1.63%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 1.63%   |
| Zhaoxin ZX-E C-960 GPU                                                                   | 1         | 0.81%   |
| Nvidia TU117M                                                                            | 1         | 0.81%   |
| Nvidia TU117GLM [T600 Mobile]                                                            | 1         | 0.81%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.81%   |
| Nvidia TU106 [GeForce RTX 2070]                                                          | 1         | 0.81%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.81%   |
| Nvidia GT215M [GeForce GT 335M]                                                          | 1         | 0.81%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.81%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.81%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                    | 1         | 0.81%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 0.81%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                                 | 1         | 0.81%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1         | 0.81%   |
| Nvidia GM204GL [Quadro M4000]                                                            | 1         | 0.81%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.81%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1         | 0.81%   |
| Nvidia GM107 [GeForce GTX 745]                                                           | 1         | 0.81%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 1         | 0.81%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 0.81%   |
| Nvidia GK110 [GeForce GTX 780]                                                           | 1         | 0.81%   |
| Nvidia GK104 [GeForce GTX 680]                                                           | 1         | 0.81%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                                        | 1         | 0.81%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                                           | 1         | 0.81%   |
| Nvidia GA106 [Geforce RTX 3050]                                                          | 1         | 0.81%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 1         | 0.81%   |
| Nvidia GA104GL [RTX A4000]                                                               | 1         | 0.81%   |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                                            | 1         | 0.81%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                                        | 1         | 0.81%   |
| Nvidia GA103M [GeForce RTX 3080 Ti Mobile]                                               | 1         | 0.81%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 1         | 0.81%   |
| Nvidia G92 [GeForce 9800 GT]                                                             | 1         | 0.81%   |
| Matrox Electronics Systems MGA G200EH                                                    | 1         | 0.81%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1         | 0.81%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 0.81%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 0.81%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 0.81%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 0.81%   |
| Intel JasperLake [UHD Graphics]                                                          | 1         | 0.81%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 0.81%   |
| Intel HD Graphics 620                                                                    | 1         | 0.81%   |
| Intel HD Graphics 500                                                                    | 1         | 0.81%   |
| Intel Haswell-ULT High Definition Audio Controller [HD Graphics]                         | 1         | 0.81%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 41        | 40.2%   |
| 1 x AMD         | 20        | 19.61%  |
| 1 x Nvidia      | 18        | 17.65%  |
| Intel + Nvidia  | 14        | 13.73%  |
| AMD + Nvidia    | 3         | 2.94%   |
| Other           | 1         | 0.98%   |
| 2 x Nvidia      | 1         | 0.98%   |
| 1 x Zhaoxin     | 1         | 0.98%   |
| Nvidia + Matrox | 1         | 0.98%   |
| Intel + AMD     | 1         | 0.98%   |
| 1 x ASPEED      | 1         | 0.98%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 74        | 71.84%  |
| Proprietary | 23        | 22.33%  |
| Unknown     | 6         | 5.83%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 75        | 72.82%  |
| 1.01-2.0   | 9         | 8.74%   |
| 7.01-8.0   | 5         | 4.85%   |
| 3.01-4.0   | 5         | 4.85%   |
| 0.51-1.0   | 4         | 3.88%   |
| 0.01-0.5   | 3         | 2.91%   |
| 2.01-3.0   | 1         | 0.97%   |
| 8.01-16.0  | 1         | 0.97%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 19        | 17.27%  |
| AU Optronics         | 15        | 13.64%  |
| BOE                  | 13        | 11.82%  |
| Dell                 | 9         | 8.18%   |
| LG Display           | 6         | 5.45%   |
| Chimei Innolux       | 6         | 5.45%   |
| CSO                  | 4         | 3.64%   |
| Philips              | 3         | 2.73%   |
| LG Electronics       | 3         | 2.73%   |
| Hewlett-Packard      | 3         | 2.73%   |
| Goldstar             | 3         | 2.73%   |
| HUAWEI               | 2         | 1.82%   |
| BenQ                 | 2         | 1.82%   |
| AOC                  | 2         | 1.82%   |
| ViewSonic            | 1         | 0.91%   |
| Vestel Elektronik    | 1         | 0.91%   |
| Skyworth             | 1         | 0.91%   |
| Sharp                | 1         | 0.91%   |
| Sceptre Tech         | 1         | 0.91%   |
| PANDA                | 1         | 0.91%   |
| Panasonic            | 1         | 0.91%   |
| Onkyo                | 1         | 0.91%   |
| OEM                  | 1         | 0.91%   |
| Microstep            | 1         | 0.91%   |
| Lenovo               | 1         | 0.91%   |
| KTC                  | 1         | 0.91%   |
| JDI                  | 1         | 0.91%   |
| InfoVision           | 1         | 0.91%   |
| Gigabyte Technology  | 1         | 0.91%   |
| Eizo                 | 1         | 0.91%   |
| Compal               | 1         | 0.91%   |
| ASUSTek Computer     | 1         | 0.91%   |
| Ancor Communications | 1         | 0.91%   |
| Acer                 | 1         | 0.91%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch    | 2         | 1.79%   |
| HUAWEI ZQE-CAA HWV6A25 3440x1440 797x334mm 34.0-inch                    | 2         | 1.79%   |
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch                  | 1         | 0.89%   |
| Vestel Elektronik 48FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch   | 1         | 0.89%   |
| Skyworth SII REPEATER SII214F 1920x1080 476x268mm 21.5-inch             | 1         | 0.89%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 382x215mm 17.3-inch                 | 1         | 0.89%   |
| Sceptre Tech F27 SPT0ABF 1920x1080 409x230mm 18.5-inch                  | 1         | 0.89%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch       | 1         | 0.89%   |
| Samsung Electronics T24D391 SAM0B73 1920x1080 521x293mm 23.5-inch       | 1         | 0.89%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch     | 1         | 0.89%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch       | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SEC504B 1600x900 382x215mm 17.3-inch    | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SEC3842 1366x768 309x174mm 14.0-inch    | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch    | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch    | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch    | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 294x165mm 13.3-inch   | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SDC4153 1920x1080 294x165mm 13.3-inch   | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 700x390mm 31.5-inch   | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1872x1053mm 84.6-inch | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch    | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SAM0B60 1920x1080 887x500mm 40.1-inch   | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SAM08FC 1366x768                        | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SAM0669 1920x1080                       | 1         | 0.89%   |
| Samsung Electronics LCD Monitor LS32A70 3840x2160                       | 1         | 0.89%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                 | 1         | 0.89%   |
| Philips FTV PHL04C3 1920x1080 1440x810mm 65.0-inch                      | 1         | 0.89%   |
| Philips 224CL PHLC075 1920x1080 492x278mm 22.2-inch                     | 1         | 0.89%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch                 | 1         | 0.89%   |
| Panasonic 10SP_AMP MEI4012 1920x540                                     | 1         | 0.89%   |
| Onkyo TX-NR747 ONK0F71 1920x1200 550x309mm 24.8-inch                    | 1         | 0.89%   |
| OEM 22_LCD_TV OEM3700 1920x540                                          | 1         | 0.89%   |
| Microstep LCD Monitor Optix AG32CQ                                      | 1         | 0.89%   |
| LG Electronics LCD Monitor LG ULTRAWIDE                                 | 1         | 0.89%   |
| LG Electronics LCD Monitor LG ULTRAGEAR 2560x1440                       | 1         | 0.89%   |
| LG Electronics LCD Monitor LG HDR WFHD 2560x1080                        | 1         | 0.89%   |
| LG Display LCD Monitor LGD06AA 3840x2400 344x215mm 16.0-inch            | 1         | 0.89%   |
| LG Display LCD Monitor LGD0671 1920x1080 382x215mm 17.3-inch            | 1         | 0.89%   |
| LG Display LCD Monitor LGD0561 1920x1080 294x165mm 13.3-inch            | 1         | 0.89%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch             | 1         | 0.89%   |
| LG Display LCD Monitor LGD02AD 1366x768 344x194mm 15.5-inch             | 1         | 0.89%   |
| LG Display LCD Monitor LGD018B 1366x768 310x174mm 14.0-inch             | 1         | 0.89%   |
| Lenovo X24q-10 LEN61A4 2560x1440 527x296mm 23.8-inch                    | 1         | 0.89%   |
| KTC 43 TV KTC4300 1920x1080 953x543mm 43.2-inch                         | 1         | 0.89%   |
| JDI LCD Monitor JDI422A 3000x2000 293x196mm 13.9-inch                   | 1         | 0.89%   |
| InfoVision LCD Monitor IVO8C5F 1920x1080 309x174mm 14.0-inch            | 1         | 0.89%   |
| Hewlett-Packard W2071d HWP299C 1600x900 443x249mm 20.0-inch             | 1         | 0.89%   |
| Hewlett-Packard L1710 HWP26EB 1280x1024 340x270mm 17.1-inch             | 1         | 0.89%   |
| Hewlett-Packard 2710 HWP2893 1920x1080 600x340mm 27.2-inch              | 1         | 0.89%   |
| Goldstar W2252 GSM567E 1680x1050 474x296mm 22.0-inch                    | 1         | 0.89%   |
| Goldstar ULTRAWIDE GSM7768 3440x1440 800x334mm 34.1-inch                | 1         | 0.89%   |
| Goldstar ULTRAWIDE GSM76FE 2560x1080 798x334mm 34.1-inch                | 1         | 0.89%   |
| Gigabyte Technology AORUS AD27QD GBT2701 2560x1440 609x355mm 27.8-inch  | 1         | 0.89%   |
| Eizo EV2436W ENC2385 1920x1200 519x324mm 24.1-inch                      | 1         | 0.89%   |
| Dell U2713H DELA091 2560x1440 597x336mm 27.0-inch                       | 1         | 0.89%   |
| Dell U2414H DELA0B2 1920x1080 527x296mm 23.8-inch                       | 1         | 0.89%   |
| Dell U2414H DELA0A3 1920x1080 527x296mm 23.8-inch                       | 1         | 0.89%   |
| Dell S2721QS DELA196 3840x2160 597x336mm 27.0-inch                      | 1         | 0.89%   |
| Dell S2421HS DEL41F4 1920x1080 530x300mm 24.0-inch                      | 1         | 0.89%   |
| Dell S2240L DELD053 1920x1080 476x267mm 21.5-inch                       | 1         | 0.89%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 44        | 40%     |
| 1366x768 (WXGA)    | 17        | 15.45%  |
| 3840x2160 (4K)     | 9         | 8.18%   |
| 2560x1440 (QHD)    | 7         | 6.36%   |
| 1280x1024 (SXGA)   | 4         | 3.64%   |
| 3440x1440          | 3         | 2.73%   |
| 2560x1600          | 3         | 2.73%   |
| 1600x900 (HD+)     | 3         | 2.73%   |
| 3840x2400          | 2         | 1.82%   |
| 2560x1080          | 2         | 1.82%   |
| 1920x540           | 2         | 1.82%   |
| 1920x1200 (WUXGA)  | 2         | 1.82%   |
| 1440x900 (WXGA+)   | 2         | 1.82%   |
| Unknown            | 2         | 1.82%   |
| 6400x2160          | 1         | 0.91%   |
| 4480x1080          | 1         | 0.91%   |
| 3000x2000          | 1         | 0.91%   |
| 2880x1800          | 1         | 0.91%   |
| 2520x1680          | 1         | 0.91%   |
| 2256x1504          | 1         | 0.91%   |
| 1680x1050 (WSXGA+) | 1         | 0.91%   |
| 1280x800 (WXGA)    | 1         | 0.91%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 22        | 20.18%  |
| 13      | 11        | 10.09%  |
| 14      | 10        | 9.17%   |
| 27      | 9         | 8.26%   |
| Unknown | 8         | 7.34%   |
| 17      | 7         | 6.42%   |
| 23      | 6         | 5.5%    |
| 24      | 5         | 4.59%   |
| 16      | 5         | 4.59%   |
| 34      | 4         | 3.67%   |
| 19      | 3         | 2.75%   |
| 11      | 3         | 2.75%   |
| 84      | 2         | 1.83%   |
| 43      | 2         | 1.83%   |
| 31      | 2         | 1.83%   |
| 21      | 2         | 1.83%   |
| 65      | 1         | 0.92%   |
| 54      | 1         | 0.92%   |
| 33      | 1         | 0.92%   |
| 32      | 1         | 0.92%   |
| 25      | 1         | 0.92%   |
| 22      | 1         | 0.92%   |
| 20      | 1         | 0.92%   |
| 10      | 1         | 0.92%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 40        | 37.38%  |
| 501-600     | 17        | 15.89%  |
| 201-300     | 12        | 11.21%  |
| Unknown     | 8         | 7.48%   |
| 401-500     | 7         | 6.54%   |
| 351-400     | 7         | 6.54%   |
| 701-800     | 6         | 5.61%   |
| 601-700     | 4         | 3.74%   |
| 1501-2000   | 2         | 1.87%   |
| 1001-1500   | 2         | 1.87%   |
| 901-1000    | 2         | 1.87%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 73        | 72.28%  |
| 16/10   | 10        | 9.9%    |
| Unknown | 5         | 4.95%   |
| 5/4     | 4         | 3.96%   |
| 3/2     | 4         | 3.96%   |
| 21/9    | 4         | 3.96%   |
| 32/9    | 1         | 0.99%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 22        | 20.37%  |
| 81-90          | 16        | 14.81%  |
| 201-250        | 11        | 10.19%  |
| 301-350        | 9         | 8.33%   |
| Unknown        | 8         | 7.41%   |
| 351-500        | 7         | 6.48%   |
| 151-200        | 6         | 5.56%   |
| 71-80          | 5         | 4.63%   |
| 111-120        | 5         | 4.63%   |
| More than 1000 | 4         | 3.7%    |
| 121-130        | 4         | 3.7%    |
| 51-60          | 3         | 2.78%   |
| 141-150        | 3         | 2.78%   |
| 251-300        | 2         | 1.85%   |
| 501-1000       | 2         | 1.85%   |
| 41-50          | 1         | 0.93%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 29        | 27.88%  |
| 121-160       | 28        | 26.92%  |
| 101-120       | 19        | 18.27%  |
| 161-240       | 12        | 11.54%  |
| Unknown       | 8         | 7.69%   |
| More than 240 | 5         | 4.81%   |
| 1-50          | 3         | 2.88%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 79        | 75.96%  |
| 2     | 17        | 16.35%  |
| 0     | 7         | 6.73%   |
| 4     | 1         | 0.96%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 61        | 39.87%  |
| Intel                    | 56        | 36.6%   |
| Qualcomm Atheros         | 13        | 8.5%    |
| Broadcom                 | 5         | 3.27%   |
| MEDIATEK                 | 4         | 2.61%   |
| Ralink                   | 2         | 1.31%   |
| Xiaomi                   | 1         | 0.65%   |
| Sierra Wireless          | 1         | 0.65%   |
| Qualcomm                 | 1         | 0.65%   |
| Pulse-Eight              | 1         | 0.65%   |
| Nvidia                   | 1         | 0.65%   |
| Mellanox Technologies    | 1         | 0.65%   |
| Marvell Technology Group | 1         | 0.65%   |
| Linksys                  | 1         | 0.65%   |
| JMicron Technology       | 1         | 0.65%   |
| Broadcom Limited         | 1         | 0.65%   |
| ASIX Electronics         | 1         | 0.65%   |
| American Megatrends      | 1         | 0.65%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 27        | 15.17%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 8         | 4.49%   |
| Intel Wi-Fi 6 AX201                                                            | 8         | 4.49%   |
| Intel Wi-Fi 6 AX200                                                            | 7         | 3.93%   |
| Realtek RTL8125 2.5GbE Controller                                              | 6         | 3.37%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 5         | 2.81%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                         | 5         | 2.81%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 4         | 2.25%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 4         | 2.25%   |
| Intel Wireless 7265                                                            | 4         | 2.25%   |
| Intel Wireless 3165                                                            | 4         | 2.25%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                             | 3         | 1.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 3         | 1.69%   |
| Realtek RTL8188EE Wireless Network Adapter                                     | 3         | 1.69%   |
| Intel Wireless 8265 / 8275                                                     | 3         | 1.69%   |
| Intel I211 Gigabit Network Connection                                          | 3         | 1.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3         | 1.69%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 2         | 1.12%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 2         | 1.12%   |
| Realtek Realtek Ethernet controller                                            | 2         | 1.12%   |
| Realtek 802.11ac NIC                                                           | 2         | 1.12%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 2         | 1.12%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter                  | 2         | 1.12%   |
| Intel Tiger Lake PCH CNVi WiFi                                                 | 2         | 1.12%   |
| Intel Ethernet Controller I225-V                                               | 2         | 1.12%   |
| Intel Ethernet Connection I217-V                                               | 2         | 1.12%   |
| Intel Ethernet Connection (7) I219-LM                                          | 2         | 1.12%   |
| Intel Ethernet Connection (2) I219-V                                           | 2         | 1.12%   |
| Intel Ethernet Connection (13) I219-V                                          | 2         | 1.12%   |
| Intel Alder Lake-P PCH CNVi WiFi                                               | 2         | 1.12%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 2         | 1.12%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.56%   |
| Sierra Wireless EM7305                                                         | 1         | 0.56%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                       | 1         | 0.56%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 1         | 0.56%   |
| Realtek RTL8191SEvA Wireless LAN Controller                                    | 1         | 0.56%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 1         | 0.56%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 0.56%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1         | 0.56%   |
| Realtek 802.11n WLAN Adapter                                                   | 1         | 0.56%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                      | 1         | 0.56%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                      | 1         | 0.56%   |
| Qualcomm Atheros QCNFA765                                                      | 1         | 0.56%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.56%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 1         | 0.56%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.56%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.56%   |
| Pulse-Eight CEC Adapter                                                        | 1         | 0.56%   |
| Nvidia MCP61 Ethernet                                                          | 1         | 0.56%   |
| Mellanox MT27500 Family [ConnectX-3]                                           | 1         | 0.56%   |
| MEDIATEK RZ608 Wi-Fi 6E 80MHz                                                  | 1         | 0.56%   |
| MediaTek 802.11ac WLAN                                                         | 1         | 0.56%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.56%   |
| Linksys AE3000 802.11abgn (3x3) Wireless Adapter [Ralink RT3573]               | 1         | 0.56%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 0.56%   |
| Intel Wireless-AC 9260                                                         | 1         | 0.56%   |
| Intel Wireless 8260                                                            | 1         | 0.56%   |
| Intel Wireless 7260                                                            | 1         | 0.56%   |
| Intel I350 Gigabit Network Connection                                          | 1         | 0.56%   |
| Intel I210 Gigabit Network Connection                                          | 1         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 43        | 49.43%  |
| Realtek Semiconductor | 18        | 20.69%  |
| Qualcomm Atheros      | 11        | 12.64%  |
| Broadcom              | 5         | 5.75%   |
| MediaTek              | 4         | 4.6%    |
| Ralink                | 2         | 2.3%    |
| Sierra Wireless       | 1         | 1.15%   |
| Qualcomm              | 1         | 1.15%   |
| Linksys               | 1         | 1.15%   |
| Broadcom Limited      | 1         | 1.15%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                              | 8         | 9.09%   |
| Intel Wi-Fi 6 AX200                                              | 7         | 7.95%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                           | 5         | 5.68%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter       | 4         | 4.55%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)   | 4         | 4.55%   |
| Intel Wireless 7265                                              | 4         | 4.55%   |
| Intel Wireless 3165                                              | 4         | 4.55%   |
| Realtek RTL88x2bu [AC1200 Techkey]                               | 3         | 3.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter         | 3         | 3.41%   |
| Realtek RTL8188EE Wireless Network Adapter                       | 3         | 3.41%   |
| Intel Wireless 8265 / 8275                                       | 3         | 3.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter         | 2         | 2.27%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter              | 2         | 2.27%   |
| Realtek 802.11ac NIC                                             | 2         | 2.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter       | 2         | 2.27%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter    | 2         | 2.27%   |
| Intel Tiger Lake PCH CNVi WiFi                                   | 2         | 2.27%   |
| Intel Alder Lake-P PCH CNVi WiFi                                 | 2         | 2.27%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter              | 2         | 2.27%   |
| Sierra Wireless EM7305                                           | 1         | 1.14%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter         | 1         | 1.14%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                  | 1         | 1.14%   |
| Realtek RTL8191SEvA Wireless LAN Controller                      | 1         | 1.14%   |
| Realtek 802.11n WLAN Adapter                                     | 1         | 1.14%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                        | 1         | 1.14%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                        | 1         | 1.14%   |
| Qualcomm Atheros QCNFA765                                        | 1         | 1.14%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)   | 1         | 1.14%   |
| MEDIATEK RZ608 Wi-Fi 6E 80MHz                                    | 1         | 1.14%   |
| MediaTek 802.11ac WLAN                                           | 1         | 1.14%   |
| Linksys AE3000 802.11abgn (3x3) Wireless Adapter [Ralink RT3573] | 1         | 1.14%   |
| Intel Wireless-AC 9260                                           | 1         | 1.14%   |
| Intel Wireless 8260                                              | 1         | 1.14%   |
| Intel Wireless 7260                                              | 1         | 1.14%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                 | 1         | 1.14%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                | 1         | 1.14%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                         | 1         | 1.14%   |
| Intel Cannon Lake PCH CNVi WiFi                                  | 1         | 1.14%   |
| Intel Alder Lake-S PCH CNVi WiFi                                 | 1         | 1.14%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                        | 1         | 1.14%   |
| Broadcom BCM4331 802.11a/b/g/n                                   | 1         | 1.14%   |
| Broadcom BCM43224 802.11a/b/g/n                                  | 1         | 1.14%   |
| Broadcom BCM43142 802.11b/g/n                                    | 1         | 1.14%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 50        | 58.14%  |
| Intel                    | 25        | 29.07%  |
| Qualcomm Atheros         | 3         | 3.49%   |
| Xiaomi                   | 1         | 1.16%   |
| Nvidia                   | 1         | 1.16%   |
| Mellanox Technologies    | 1         | 1.16%   |
| Marvell Technology Group | 1         | 1.16%   |
| JMicron Technology       | 1         | 1.16%   |
| Broadcom                 | 1         | 1.16%   |
| ASIX Electronics         | 1         | 1.16%   |
| American Megatrends      | 1         | 1.16%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 27        | 30.34%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 8         | 8.99%   |
| Realtek RTL8125 2.5GbE Controller                                              | 6         | 6.74%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 5         | 5.62%   |
| Intel I211 Gigabit Network Connection                                          | 3         | 3.37%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3         | 3.37%   |
| Realtek Realtek Ethernet controller                                            | 2         | 2.25%   |
| Intel Ethernet Controller I225-V                                               | 2         | 2.25%   |
| Intel Ethernet Connection I217-V                                               | 2         | 2.25%   |
| Intel Ethernet Connection (7) I219-LM                                          | 2         | 2.25%   |
| Intel Ethernet Connection (2) I219-V                                           | 2         | 2.25%   |
| Intel Ethernet Connection (13) I219-V                                          | 2         | 2.25%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 1.12%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 1         | 1.12%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 1.12%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1         | 1.12%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 1.12%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 1.12%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 1.12%   |
| Nvidia MCP61 Ethernet                                                          | 1         | 1.12%   |
| Mellanox MT27500 Family [ConnectX-3]                                           | 1         | 1.12%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.12%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 1.12%   |
| Intel I350 Gigabit Network Connection                                          | 1         | 1.12%   |
| Intel I210 Gigabit Network Connection                                          | 1         | 1.12%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                  | 1         | 1.12%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 1.12%   |
| Intel Ethernet Connection I218-V                                               | 1         | 1.12%   |
| Intel Ethernet Connection (6) I219-LM                                          | 1         | 1.12%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 1.12%   |
| Intel Ethernet Connection (2) I218-LM                                          | 1         | 1.12%   |
| Intel Ethernet Connection (14) I219-V                                          | 1         | 1.12%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 1.12%   |
| Intel 82574L Gigabit Network Connection                                        | 1         | 1.12%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                              | 1         | 1.12%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 1         | 1.12%   |
| American Megatrends Virtual Ethernet                                           | 1         | 1.12%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 85        | 50.6%   |
| Ethernet | 82        | 48.81%  |
| Modem    | 1         | 0.6%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 71        | 55.47%  |
| Ethernet | 57        | 44.53%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 54        | 52.94%  |
| 1     | 42        | 41.18%  |
| 3     | 4         | 3.92%   |
| 0     | 2         | 1.96%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 73        | 70.87%  |
| Yes  | 30        | 29.13%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 42        | 56%     |
| Realtek Semiconductor           | 7         | 9.33%   |
| Qualcomm Atheros Communications | 7         | 9.33%   |
| IMC Networks                    | 4         | 5.33%   |
| Cambridge Silicon Radio         | 4         | 5.33%   |
| Dell                            | 2         | 2.67%   |
| Broadcom                        | 2         | 2.67%   |
| Realtek                         | 1         | 1.33%   |
| Ralink Technology               | 1         | 1.33%   |
| Ralink                          | 1         | 1.33%   |
| MediaTek                        | 1         | 1.33%   |
| Logitech                        | 1         | 1.33%   |
| Foxconn / Hon Hai               | 1         | 1.33%   |
| Apple                           | 1         | 1.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                              | 24        | 32%     |
| Intel AX200 Bluetooth                               | 7         | 9.33%   |
| Realtek Bluetooth Radio                             | 6         | 8%      |
| Intel AX210 Bluetooth                               | 5         | 6.67%   |
| Intel Bluetooth wireless interface                  | 4         | 5.33%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 5.33%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 4%      |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 2.67%   |
| IMC Networks Wireless_Device                        | 2         | 2.67%   |
| IMC Networks Bluetooth Radio                        | 2         | 2.67%   |
| Realtek RTL8723B Bluetooth                          | 1         | 1.33%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 1.33%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 1.33%   |
| Ralink RT3290 Bluetooth                             | 1         | 1.33%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.33%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 1.33%   |
| MediaTek Wireless_Device                            | 1         | 1.33%   |
| Logitech BT Mini-Receiver (HCI mode)                | 1         | 1.33%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.33%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.33%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 1.33%   |
| Dell Wireless 365 Bluetooth                         | 1         | 1.33%   |
| Dell BCM20702A0                                     | 1         | 1.33%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 1.33%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1.33%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 72        | 51.8%   |
| Nvidia              | 30        | 21.58%  |
| AMD                 | 28        | 20.14%  |
| C-Media Electronics | 3         | 2.16%   |
| Corsair             | 2         | 1.44%   |
| Zhaoxin             | 1         | 0.72%   |
| DigiTech            | 1         | 0.72%   |
| Creative Technology | 1         | 0.72%   |
| Creative Labs       | 1         | 0.72%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 11        | 6.71%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 10        | 6.1%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 8         | 4.88%   |
| Nvidia Audio device                                                                               | 7         | 4.27%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 7         | 4.27%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 6         | 3.66%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 6         | 3.66%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 3.05%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 3.05%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 3.05%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 5         | 3.05%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 1.83%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 3         | 1.83%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3         | 1.83%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 1.83%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 3         | 1.83%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 1.22%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 1.22%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 1.22%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 1.22%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 1.22%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.22%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 2         | 1.22%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 2         | 1.22%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 1.22%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 1.22%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.22%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 1.22%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.22%   |
| AMD Navi 10 HDMI Audio                                                                            | 2         | 1.22%   |
| AMD FCH Azalia Controller                                                                         | 2         | 1.22%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 2         | 1.22%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2         | 1.22%   |
| Zhaoxin ZX-E High Definition Audio Controller                                                     | 1         | 0.61%   |
| Zhaoxin ZX-100/ZX-D/ZX-E High Definition Audio Controller                                         | 1         | 0.61%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.61%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.61%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.61%   |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 0.61%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.61%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.61%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 0.61%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 0.61%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 0.61%   |
| Nvidia GK110 High Definition Audio Controller                                                     | 1         | 0.61%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 0.61%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 0.61%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 0.61%   |
| Intel Jasper Lake HD Audio                                                                        | 1         | 0.61%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.61%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 0.61%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.61%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 1         | 0.61%   |
| Intel Audio device                                                                                | 1         | 0.61%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.61%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.61%   |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 0.61%   |
| DigiTech Lexicon Alpha                                                                            | 1         | 0.61%   |
| Creative Technology Sound Blaster Premium HD [SBX]                                                | 1         | 0.61%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                                     | 1         | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 22        | 30.14%  |
| SK Hynix            | 13        | 17.81%  |
| Kingston            | 11        | 15.07%  |
| Micron Technology   | 9         | 12.33%  |
| Unknown (ABCD)      | 3         | 4.11%   |
| Unknown             | 2         | 2.74%   |
| Ramaxel Technology  | 2         | 2.74%   |
| G.Skill             | 2         | 2.74%   |
| Crucial             | 2         | 2.74%   |
| Shenzhen WODPOSIT   | 1         | 1.37%   |
| Patriot             | 1         | 1.37%   |
| Kllisre             | 1         | 1.37%   |
| GOODRAM             | 1         | 1.37%   |
| Corsair             | 1         | 1.37%   |
| ASint Technology    | 1         | 1.37%   |
| A-DATA Technology   | 1         | 1.37%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 2.56%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 2         | 2.56%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 2         | 2.56%   |
| Samsung RAM M425R2GA3BB0-CQKOD 16GB SODIMM 4800MT/s              | 2         | 2.56%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 1.28%   |
| Unknown RAM Module 2GB DIMM 1066MT/s                             | 1         | 1.28%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 1.28%   |
| Unknown (ABCD) RAM 123456789012345678 3GB DIMM LPDDR4 2400MT/s   | 1         | 1.28%   |
| SK Hynix RAM Module 4GB DIMM DDR3 1066MT/s                       | 1         | 1.28%   |
| SK Hynix RAM Module 2GB DDR3 1600MT/s                            | 1         | 1.28%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.28%   |
| SK Hynix RAM HMT42GR7BFR4A-PB 16GB DIMM DDR3 1600MT/s            | 1         | 1.28%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM 1600MT/s                | 1         | 1.28%   |
| SK Hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 1.28%   |
| SK Hynix RAM HMAA2GS6CJR8N-XN 16384MB SODIMM DDR4 3200MT/s       | 1         | 1.28%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 1.28%   |
| SK Hynix RAM HMA851S6CJR6N-UH 4GB SODIMM DDR4 2400MT/s           | 1         | 1.28%   |
| SK Hynix RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2666MT/s             | 1         | 1.28%   |
| SK Hynix RAM HMA81GU6CJR8N-VK 8GB DIMM DDR4 2666MT/s             | 1         | 1.28%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.28%   |
| SK Hynix RAM HCNNNFAMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 1         | 1.28%   |
| Shenzhen WODPOSIT RAM Module 8GB SODIMM DDR4 2666MT/s            | 1         | 1.28%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 1         | 1.28%   |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 1         | 1.28%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.28%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.28%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 1         | 1.28%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.28%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.28%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.28%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.28%   |
| Samsung RAM M471A1K43CB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.28%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 1         | 1.28%   |
| Samsung RAM M391A2K43BB1-CTD 16GB DIMM DDR4 2667MT/s             | 1         | 1.28%   |
| Samsung RAM K4F8E304HB-MGCJ 1024MB SODIMM LPDDR4 2400MT/s        | 1         | 1.28%   |
| Samsung RAM K4E6E304EB-EGCF 4GB Row Of Chips LPDDR3 1867MT/s     | 1         | 1.28%   |
| Samsung RAM K4A8G165WC-BCWE 4GB SODIMM DDR4 3200MT/s             | 1         | 1.28%   |
| Samsung RAM K4A8G165WC-BCTD 4GB SODIMM DDR4 2667MT/s             | 1         | 1.28%   |
| Samsung RAM K4A8G165WB-BCRC 4GB SODIMM DDR4 2400MT/s             | 1         | 1.28%   |
| Ramaxel RAM RMT3020EF48E8W1333 2GB SODIMM DDR3 1334MT/s          | 1         | 1.28%   |
| Ramaxel RAM RMSA3260NA78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 1         | 1.28%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s                   | 1         | 1.28%   |
| Micron RAM MTC8C1084S1SC48BA1 16GB SODIMM 4800MT/s               | 1         | 1.28%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 1         | 1.28%   |
| Micron RAM MT40A1G16RC-062E:B 8GB Row Of Chips DDR4 3200MT/s     | 1         | 1.28%   |
| Micron RAM 8ATF2G64AZ-3G2E1 16GB DIMM DDR4 3200MT/s              | 1         | 1.28%   |
| Micron RAM 4ATF51264HZ-3G2J1 4096MB SODIMM DDR4 3200MT/s         | 1         | 1.28%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 1         | 1.28%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 1         | 1.28%   |
| Micron RAM 38ADF2G72AZ-2G6E1 16GB DIMM DDR4 2133MT/s             | 1         | 1.28%   |
| Micron RAM 36JSF2G72PZ-1G9E1 16GB DIMM DDR3 1866MT/s             | 1         | 1.28%   |
| Micron RAM 18ASF2G72AZ-2G1A1 16GB DIMM DDR4 2133MT/s             | 1         | 1.28%   |
| Micron RAM 18ADF2G72AZ-2G6E1 16GB DIMM DDR4 2667MT/s             | 1         | 1.28%   |
| Kllisre RAM KRE-D3U1600M/8G 8GB DIMM DDR3 1600MT/s               | 1         | 1.28%   |
| Kingston RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.28%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s           | 1         | 1.28%   |
| Kingston RAM KF3200C20S4/8G 8GB SODIMM DDR4 3200MT/s             | 1         | 1.28%   |
| Kingston RAM KF3200C20S4/16GX 16GB SODIMM DDR4 3200MT/s          | 1         | 1.28%   |
| Kingston RAM CL7-7-7 DDR3-1333 2GB DIMM DDR3 1333MT/s            | 1         | 1.28%   |
| Kingston RAM CBD32D4S2S8MF-16 16GB SODIMM DDR4 3200MT/s          | 1         | 1.28%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 34        | 54.84%  |
| DDR3    | 15        | 24.19%  |
| LPDDR4  | 5         | 8.06%   |
| Unknown | 3         | 4.84%   |
| SDRAM   | 2         | 3.23%   |
| LPDDR3  | 2         | 3.23%   |
| DDR2    | 1         | 1.61%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 39        | 63.93%  |
| DIMM         | 15        | 24.59%  |
| Row Of Chips | 6         | 9.84%   |
| Unknown      | 1         | 1.64%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 21        | 31.34%  |
| 16384 | 18        | 26.87%  |
| 4096  | 16        | 23.88%  |
| 2048  | 7         | 10.45%  |
| 32768 | 4         | 5.97%   |
| 1024  | 1         | 1.49%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 21        | 31.34%  |
| 1600  | 11        | 16.42%  |
| 2667  | 8         | 11.94%  |
| 2400  | 6         | 8.96%   |
| 2666  | 3         | 4.48%   |
| 4800  | 2         | 2.99%   |
| 4199  | 2         | 2.99%   |
| 2133  | 2         | 2.99%   |
| 1333  | 2         | 2.99%   |
| 1066  | 2         | 2.99%   |
| 4267  | 1         | 1.49%   |
| 3666  | 1         | 1.49%   |
| 3466  | 1         | 1.49%   |
| 1867  | 1         | 1.49%   |
| 1866  | 1         | 1.49%   |
| 1334  | 1         | 1.49%   |
| 1067  | 1         | 1.49%   |
| 667   | 1         | 1.49%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 12        | 19.67%  |
| IMC Networks                           | 8         | 13.11%  |
| Microdia                               | 5         | 8.2%    |
| Syntek                                 | 4         | 6.56%   |
| Realtek Semiconductor                  | 4         | 6.56%   |
| Acer                                   | 4         | 6.56%   |
| Sunplus Innovation Technology          | 3         | 4.92%   |
| Luxvisions Innotech Limited            | 3         | 4.92%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 4.92%   |
| Z-Star Microelectronics                | 1         | 1.64%   |
| USB Camera                             | 1         | 1.64%   |
| Suyin                                  | 1         | 1.64%   |
| Sony                                   | 1         | 1.64%   |
| Sonix Technology                       | 1         | 1.64%   |
| ShineTech                              | 1         | 1.64%   |
| Samsung Electronics                    | 1         | 1.64%   |
| Ricoh                                  | 1         | 1.64%   |
| Razer USA                              | 1         | 1.64%   |
| Quanta                                 | 1         | 1.64%   |
| Lite-On Technology                     | 1         | 1.64%   |
| Hewlett-Packard                        | 1         | 1.64%   |
| HD 2MP WEBCAM                          | 1         | 1.64%   |
| Creative Technology                    | 1         | 1.64%   |
| Alcor Micro                            | 1         | 1.64%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Chicony HP HD Camera                                         | 4         | 6.45%   |
| IMC Networks USB2.0 HD UVC WebCam                            | 3         | 4.84%   |
| Syntek Lenovo EasyCamera                                     | 2         | 3.23%   |
| Syntek Integrated Camera                                     | 2         | 3.23%   |
| Microdia Integrated_Webcam_HD                                | 2         | 3.23%   |
| IMC Networks Integrated Camera                               | 2         | 3.23%   |
| Chicony TOSHIBA Web Camera - HD                              | 2         | 3.23%   |
| Chicony Integrated Camera                                    | 2         | 3.23%   |
| Acer HD Camera                                               | 2         | 3.23%   |
| Z-Star WebCam SCB-1900N                                      | 1         | 1.61%   |
| USB Camera USB Camera                                        | 1         | 1.61%   |
| Suyin HP Webcam-101                                          | 1         | 1.61%   |
| Sunplus USB camera                                           | 1         | 1.61%   |
| Sunplus Full HD webcam                                       | 1         | 1.61%   |
| Sunplus Dell HD Webcam                                       | 1         | 1.61%   |
| Sony CEVCECM                                                 | 1         | 1.61%   |
| Sonix USB2.0 HD UVC WebCam                                   | 1         | 1.61%   |
| ShineTech HD Camera                                          | 1         | 1.61%   |
| Samsung Galaxy A5 (MTP)                                      | 1         | 1.61%   |
| Ricoh HD Webcam                                              | 1         | 1.61%   |
| Realtek Laptop Camera                                        | 1         | 1.61%   |
| Realtek Integrated Webcam                                    | 1         | 1.61%   |
| Realtek HP Wide Vision HD Camera                             | 1         | 1.61%   |
| Realtek HP "Truevision HD" laptop camera                     | 1         | 1.61%   |
| Razer USA Gaming Webcam [Kiyo]                               | 1         | 1.61%   |
| Quanta HD User Facing                                        | 1         | 1.61%   |
| Microdia USB Live camera                                     | 1         | 1.61%   |
| Microdia Laptop_Integrated_Webcam_1.3M                       | 1         | 1.61%   |
| Microdia 1.3 MPixel Integrated Webcam                        | 1         | 1.61%   |
| Luxvisions Innotech Limited Integrated RGB Camera            | 1         | 1.61%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera         | 1         | 1.61%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera          | 1         | 1.61%   |
| Lite-On HP HD Camera                                         | 1         | 1.61%   |
| IMC Networks USB2.0 VGA UVC WebCam                           | 1         | 1.61%   |
| IMC Networks Integrated Webcam                               | 1         | 1.61%   |
| IMC Networks HD Camera                                       | 1         | 1.61%   |
| HP Webcam                                                    | 1         | 1.61%   |
| HD 2MP WEBCAM HD 2MP WEBCAM                                  | 1         | 1.61%   |
| Creative Live! Cam Sync 1080p V2                             | 1         | 1.61%   |
| Chicony TOSHIBA Web Camera - 3M                              | 1         | 1.61%   |
| Chicony HP Wide Vision HD Camera                             | 1         | 1.61%   |
| Chicony HP Webcam                                            | 1         | 1.61%   |
| Chicony HP Truevision HD camera                              | 1         | 1.61%   |
| Chicony HD Webcam                                            | 1         | 1.61%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam | 1         | 1.61%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                | 1         | 1.61%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera             | 1         | 1.61%   |
| Alcor Micro USB 2.0 Camera                                   | 1         | 1.61%   |
| Acer Integrated Camera                                       | 1         | 1.61%   |
| Acer HD Webcam                                               | 1         | 1.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 4         | 33.33%  |
| Shenzhen Goodix Technology | 4         | 33.33%  |
| Validity Sensors           | 3         | 25%     |
| Elan Microelectronics      | 1         | 8.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 4         | 33.33%  |
| Unknown                                                                    | 3         | 25%     |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 8.33%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 8.33%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 8.33%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 8.33%   |
| Elan ELAN:ARM-M4                                                           | 1         | 8.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 67        | 65.05%  |
| 1     | 28        | 27.18%  |
| 2     | 8         | 7.77%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 13        | 31.71%  |
| Fingerprint reader       | 12        | 29.27%  |
| Net/wireless             | 3         | 7.32%   |
| Multimedia controller    | 3         | 7.32%   |
| Unassigned class         | 2         | 4.88%   |
| Sound                    | 2         | 4.88%   |
| Communication controller | 2         | 4.88%   |
| Camera                   | 2         | 4.88%   |
| Chipcard                 | 1         | 2.44%   |
| Bluetooth                | 1         | 2.44%   |

